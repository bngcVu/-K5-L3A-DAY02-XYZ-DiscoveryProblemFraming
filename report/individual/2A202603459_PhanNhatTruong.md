# Báo cáo cá nhân — MSSV_HoTen

> Đổi tên file theo quy tắc `MSSV_HoTen.md`, ví dụ `20241234_NguyenVanAn.md` (MSSV trước, dấu `_`, họ tên viết liền không dấu). Sửa cả dòng tiêu đề phía trên cho khớp.
> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).
> Mỗi thành viên một file trong `report/individual/` trên repo nhóm: copy template này thành file mới, điền, rồi commit bằng tài khoản GitHub của bạn. Không viết hộ người khác.

## 1. Thông tin học viên

- Họ tên: Phan Nhật Trường
- MSSV: 2A202603459
- Email trường (không bắt buộc, repo có thể để public): 26ai.truongpn@vinuni.edu.vn
- Tên nhóm: XYZ
- Link repo nhóm: https://github.com/bngcVu/-K5-L3A-DAY02-XYZ-DiscoveryProblemFraming

---

## 2. Scan problem (CP1)


| # | Lăng kính | Job Story | Ai chịu ảnh hưởng? | Dấu hiệu thật |
|---:|---|---|---|---|
| 1 | Lặp lại | Khi hoàn thành công đoạn, tôi muốn ghi đủ sản lượng, để được tính công chính xác | Công nhân | ghi sản lượng 4–6 lần/ca, tổng khoảng 10–15 phút/người/ca |
| 2 | Tốn thời gian | Khi hết ca, tôi muốn tổng hợp sản lượng từng người theo công đoạn, để báo cáo kịp thời | Tổ trưởng, nhân viên thống kê | tổng hợp cho 20 công nhân mất 30–45 phút cuối mỗi ca |
| 3 | Cần đọc, tổng hợp nhiều thông tin | Khi số liệu các công đoạn không khớp, tôi muốn tìm nguyên nhân, để chốt đúng sản lượng | Tổ trưởng, nhân viên thống kê | chênh lệch 2–3 lần/tuần, mất 15–20 phút đối chiếu mỗi lần |
| 4 | Tốn thời gian | Khi đến kỳ tính công, tôi muốn đối chiếu đúng sản lượng và đơn giá, để trả đúng tiền cho từng người | Nhân viên tính lương | tính công cho 20 người với 5 đơn giá công đoạn mất 2–3 giờ/kỳ |
| 5 | Pain từ người khác | Khi kiểm tra tiền công, tôi muốn xem sản lượng đã ghi nhận, để phản ánh kịp thời nếu có sai lệch | Công nhân | 3–5 yêu cầu kiểm tra lại/kỳ, mất 10–15 phút xử lý mỗi yêu cầu |
| 6 | Cần đọc, tổng hợp nhiều thông tin | Khi có sản phẩm lỗi, tôi muốn biết số lượng và công đoạn cần sửa, để xử lý và ghi nhận đúng sản lượng | Nhân viên kiểm hàng, tổ trưởng | 2–3 đợt trả hàng lỗi/tuần, mất 15–20 phút truy tìm công đoạn mỗi đợt |


---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)



### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | Tổng hợp sản lượng cuối ca (#2) | Lặp lại mỗi ca, actor rõ, dễ đo thời gian | Phiếu hiện có đủ mã hàng, công đoạn và người làm không? |
| 2 | Tính công theo công đoạn và đơn giá (#4) | Ảnh hưởng trực tiếp tiền công, có thể kiểm tra bằng phép tính | Đơn giá được duyệt và cập nhật thế nào? |
| 3 | Ghi nhận sản lượng sau công đoạn (#1) | Là dữ liệu đầu vào cho tổng hợp và tính công; sai từ đầu có thể ảnh hưởng cả hai bước sau | Ai ghi, ai xác nhận và có ghi thiếu/trùng không? |

### Problem Card #1 — Tổng hợp sản lượng cuối ca

| Trường | Nội dung |
|---|---|
| Job Story | Khi hết ca, tôi muốn tổng hợp sản lượng từng người theo mã hàng và công đoạn, để báo cáo kịp thời và có dữ liệu tính công |
| Actor | Nhân viên thống kê sản lượng, tổ trưởng xác nhận |
| Thời điểm / bối cảnh | Cuối mỗi ca, tổng hợp phiếu của 20 công nhân |
| Quy trình hiện tại (3–7 bước) | Thu phiếu → kiểm tra thông tin → nhập và cộng sản lượng → đối chiếu với tổ trưởng → chốt báo cáo |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3: nhập và cộng sản lượng theo người, mã hàng, công đoạn; 20 phút/ca |
| Impact (nếu không giải thì sao) | Tổng hợp mất 45 phút/ca; có nguy cơ thiếu hoặc trùng dòng, chậm báo cáo |
| Success metric (baseline → target) | 45 → ≤15 phút/ca cho 20 người; không thiếu/trùng dòng khi đối chiếu phiếu. Bấm giờ từ thu phiếu đến chốt báo cáo |
| Phương án không dùng AI | Phiếu thống nhất trường dữ liệu; bảng tính kiểm tra mã, cảnh báo trùng và tự cộng sản lượng |
| Giả thuyết về AI (nếu có) | AI sẽ tự quét ảnh phiếu đọc mã, sản lượng và cộng vào data, excel của nhân viên |
| Cảm nhận nhanh | Rule — ưu tiên chuẩn hóa dữ liệu và công thức |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — 45 phút/ca
[1 Thu phiếu: 5'] → [2 Kiểm tra thông tin: 5']
→ [3 Nhập và cộng sản lượng: 20'] ← BOTTLENECK
→ [4 Đối chiếu với tổ trưởng: 10'] → [5 Chốt báo cáo: 5']
```

Card #2 và #3 (tóm tắt):

| Card | Actor | Bottleneck | Metric | Cảm nhận nhanh |
|---|---|---|---|---|
| #2 — Tính công theo công đoạn và đơn giá | Nhân viên tính công | Ghép sản lượng với đơn giá và tính tiền: 80 phút/kỳ | 180 → ≤60 phút/kỳ, khớp sản lượng và đơn giá đã duyệt | Rule |
| #3 — Ghi nhận sản lượng sau công đoạn | Công nhân, tổ trưởng xác nhận | Ghi lặp lại thông tin trên phiếu: 6 phút/người/ca | 15 → ≤5 phút/người/ca, không thiếu hoặc trùng dòng | No AI |



### AI phản biện Card #1


| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| Baseline 45 phút/ca của Card #1 chưa được đo thực tế | Đồng ý | Bổ sung cách bấm giờ từ thu phiếu đến chốt báo cáo; cần đo thực tế để xác nhận baseline |
| Card #1 chọn Rule nhưng giả thuyết lại dùng AI đọc ảnh phiếu | Chờ xác nhận | Đề xuất thử bảng tính và dữ liệu chuẩn trước; nếu cần AI đọc phiếu thì xem xét mức Workflow |
| AI đọc sai mã hoặc số lượng có thể làm sai báo cáo nếu tự cộng vào Excel | Chờ xác nhận | Đề xuất AI chỉ tạo bảng nháp; nhân viên đối chiếu phiếu và xác nhận trước khi cập nhật dữ liệu chính thức |

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card | | |
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt: | |
| Nhận phản biện | Câu hỏi tôi nhận được: | Tôi đã sửa gì: |
| Gom cluster / cây OST | | |
| Chọn candidate problem | | |
| Kiểm chứng / research | | |
| Quy trình nhóm | | |
| Problem Statement | | |
| Mức can thiệp AI | | |
| Quyết định | | |

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan | | | | |
| CP2 Problem Card | Hỗ trợ soạn bản nháp 3 card, quy trình và chỉ phản biện Card #1 | Làm rõ bước nghẽn, cách đo và phương án không AI của Card #1 | Thời gian từng bước chỉ là minh họa, chưa quan sát tại xưởng | Cần tự kiểm tra quy trình, đo baseline và xác nhận các nhận định trước khi chốt |
| CP4 Research | | | | |
| CP5 Quy trình | | | | |
| CP5–6 Problem Statement | | | | |
| CP6 Mức can thiệp / quyết định | | | | |

---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**

**6.5. Điều khó nhất khi viết Problem Statement là gì?**

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**

**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình.

---

## 7. Tài liệu tham khảo

-
