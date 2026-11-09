# Báo cáo cá nhân — MSSV_HoTen

> Đổi tên file theo quy tắc `MSSV_HoTen.md`, ví dụ `20241234_NguyenVanAn.md` (MSSV trước, dấu `_`, họ tên viết liền không dấu). Sửa cả dòng tiêu đề phía trên cho khớp.
> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).
> Mỗi thành viên một file trong `report/individual/` trên repo nhóm: copy template này thành file mới, điền, rồi commit bằng tài khoản GitHub của bạn. Không viết hộ người khác.

## 1. Thông tin học viên

- Họ tên: Vũ Mạnh Hoạch
- MSSV: 2A202603500
- Email trường (không bắt buộc, repo có thể để public): 
- Tên nhóm: XYZ
- Link repo nhóm: https://github.com/bngcVu/-K5-L3A-DAY02-XYZ-DiscoveryProblemFraming

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng) |
|---:|---|---|---|---|
| 1 | Lặp lại; tốn thời gian | Khi chuẩn bị học hoặc làm bài tập cho các môn, tôi muốn tìm nhanh tài liệu đúng nội dung và đáng tin cậy, để có thêm thời gian đọc hiểu và thực hành. | Bản thân | Khoảng 2 giờ/tuần tìm tài liệu cho 3 môn. |
| 2 | Tốn thời gian; lặp lại | Khi chương trình Python gặp lỗi, tôi muốn biết nguyên nhân và cách kiểm tra bản sửa, để tiếp tục hoàn thành bài thực hành. | Bản thân. | dùng Python, mất khoảng 1–2 giờ/ngày sửa lỗi code. |
| 3 | Cần đọc, tổng hợp nhiều thông tin | Khi đọc tài liệu FinTech bằng tiếng Anh, tôi muốn hiểu chính xác thuật ngữ và nối được các ý chính, để áp dụng vào việc học. | Bản thân. | Khoảng 1 giờ/tài liệu tiếng Anh |
| 4 | Tốn thời gian | Khi làm bài có công thức tài chính, tôi muốn hiểu ý nghĩa biến số và điều kiện áp dụng, để chọn đúng công thức và giải thích được kết quả. | Bản thân. | Khoảng 20 phút/công thức |
| 5 | Tốn thời gian; lặp lại | Khi nhận một bộ dữ liệu để làm bài bằng Excel hoặc Python, tôi muốn phát hiện và xử lý các giá trị thiếu, trùng hoặc sai định dạng, để có dữ liệu đủ tin cậy cho phân tích. | Bản thân; người dùng kết quả phân tích nếu làm bài nhóm. | Khoảng 30 phút - 1 tiếng để làm sạch dữ liệu |
| 6 | Lặp lại; cần tổng hợp nhiều thông tin | Khi ôn thi một môn có nhiều slide và tài liệu, tôi muốn gom kiến thức theo chủ đề và nhận ra nội dung trọng tâm, để ôn tập có hệ thống. | Bản thân. | Khoảng 2 giờ tổng hợp kiến thức cho 1 môn học. |
| 7 | Cần đọc, tổng hợp nhiều thông tin | Khi kết quả phân tích dữ liệu khác kỳ vọng, tôi muốn lần ra bước xử lý hoặc giả định gây sai lệch, để báo cáo kết quả có thể kiểm tra lại. |Bản thân; người đọc báo cáo. | Khoảng 30 phút để tìm ra lỗi. |
| 8 | Pain từ người khác | Khi làm bài nhóm, tôi muốn biết rõ ai phụ trách việc gì và tiến độ từng phần, để các thành viên phối hợp mà không phải hỏi lại nhiều lần. | Bản thân và các thành viên nhóm. | Khó phối hợp, phân chia và theo dõi việc nhóm. |

**Nếu có dùng AI để gợi ý thêm:** ý nào AI gợi ý mà bạn giữ lại, ý nào bỏ và vì sao.

-

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | Sửa lỗi code Python (#2) | Pain diễn ra hằng ngày, thời gian tự ước lượng lớn nhất (1–2 giờ/ngày), có đầu vào/đầu ra để kiểm chứng việc sửa đúng. | 1–2 giờ có bao gồm viết code mới không? Lỗi nào gặp thường xuyên? Thời gian từng bước? |
| 2 | Tìm tài liệu học tập (#1) | Lặp lại mỗi tuần cho 3 môn, có baseline khoảng 2 giờ/tuần, quy trình tìm–lọc–lưu tài liệu có thể mô tả và đo. | Tài liệu nằm ở đâu? Nghẽn ở tìm kiếm, đánh giá độ tin cậy hay đọc hiểu? |
| 3 | Làm sạch dữ liệu Excel/Python (#5) | Gắn trực tiếp với bài tập FinTech và đã có khoảng thời gian 30–60 phút/lần, thuận tiện đo thời gian lẫn chất lượng dữ liệu. | Bộ dữ liệu và loại lỗi cụ thể? Tần suất bao lâu? Liệu Power Query/pandas theo rule đã đủ? |

### Problem Card #1

| Trường | Nội dung |
|---|---|
| Job Story | Khi chương trình Python gặp lỗi, tôi muốn xác định nguyên nhân và kiểm tra bản sửa, để tiếp tục hoàn thành bài thực hành. |
| Actor | Bản thân |
| Thời điểm / bối cảnh | Khi thực hành Python và chương trình báo lỗi hoặc chạy ra kết quả không đúng; theo tự báo cáo, việc sửa code tốn 1–2 giờ/ngày. |
| Quy trình hiện tại (3–7 bước) | (1) Chạy code, phát hiện lỗi ; (2) đọc traceback/đầu ra ; (3) khoanh vùng nguyên nhân ; (4) tìm tài liệu/cách sửa ; (5) sửa, chạy lại ; (6) kiểm tra kết quả. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3–5 chiếm 65/90 phút minh họa; trong đó bước 4 (tìm hướng sửa) 25 phút. |
| Impact (nếu không giải thì sao) | Chiếm khoảng 1–2 giờ trong những ngày có sửa code, làm giảm quỹ thời gian dành cho các phần học khác. |
| Success metric (baseline → target) | Dưới 60 phút/ngày trên khối lượng/độ khó tương đương, code vẫn vượt các bài test hoặc cho kết quả đúng. |
| Phương án không dùng AI | Đọc traceback, dùng debugger/print, chia nhỏ code, viết test nhỏ, tra tài liệu Python chính thức hoặc ghi lại lỗi từng gặp. |
| Giả thuyết về AI (nếu có) | AI giải thích lỗi và gợi ý hướng kiểm tra sau khi người học cung cấp traceback và đoạn code liên quan; người học tự sửa, chạy test và đối chiếu yêu cầu. Chưa giả định AI giải được mọi lỗi. |
| Cảm nhận nhanh | Workflow (giả thuyết): có bước AI giải thích/gợi ý, nhưng các bước chạy test và quyết định sửa do người học thực hiện. Cần so với No AI/Rule trước khi chốt. |

Quy trình nháp hiện tại:

```[1 Chạy code, phát hiện lỗi: 5']
  → [2 Đọc traceback/đầu ra: 10']
  → [3 Khoanh vùng nguyên nhân: 20']
  → [4 Tìm tài liệu/cách sửa: 25'] ← BOTTLENECK GIẢ THUYẾT (3–5)
  → [5 Sửa và chạy lại: 20']
  → [6 Đối chiếu kết quả: 10']

TỔNG MINH HỌA: 90 phút (người học tự báo cáo 60–120 phút/ngày).

```

### Problem Card #2

| Trường | Nội dung |
|---|---|
| Job Story | Khi chuẩn bị học hoặc làm bài tập cho các môn, tôi muốn tìm nhanh tài liệu đúng nội dung và đáng tin cậy, để có thêm thời gian đọc hiểu và thực hành. |
| Actor | Bản thân |
| Thời điểm / bối cảnh | Hằng tuần khi chuẩn bị bài, làm bài tập hoặc cần nguồn giải thích kiến thức cho 3 môn; khoảng 2 giờ/tuần để tìm tài liệu. |
| Quy trình hiện tại (3–7 bước) | (1) Xác định chủ đề; (2) tìm trên các nguồn đang dùng; (3) mở và lọc tài liệu; (4) đối chiếu độ phù hợp và tin cậy; (5) lưu link, ghi chú |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3–4 chiếm 65/120 phút minh họa; bước 3 (mở và lọc tài liệu) lâu nhất, 40 phút. |
| Impact (nếu không giải thì sao) | Khoảng 2 giờ/tuần dành cho tìm kiếm thay vì đọc sâu/làm bài; chưa ghi nhận điểm kém hay nộp muộn do việc này. |
| Success metric (baseline → target) | Dưới 60 phút/tuần, vẫn có tài liệu sử dụng được cho cả 3 môn |
| Phương án không dùng AI | Lập danh sách nguồn học thuật/giáo trình đáng tin cậy cho từng môn, dùng từ khóa chuẩn, bộ lọc tìm kiếm, thư mục bookmark và mẫu ghi chú nguồn. |
| Giả thuyết về AI (nếu có) | AI gợi ý từ khóa, giúp lập tiêu chí lọc và tóm tắt tài liệu có đường dẫn/được người học cung cấp. Người học tự mở nguồn, xác nhận nội dung và trích dẫn; không sử dụng tài liệu do AI bịa. |
| Cảm nhận nhanh | Workflow: chỉ nên dùng AI nếu danh sách nguồn và quy tắc tìm kiếm thông thường không đủ. |

Quy trình nháp hiện tại:

```[1 Xác định chủ đề: 10']
  → [2 Tìm trên các nguồn: 30']
  → [3 Mở và lọc tài liệu: 40'] ← BOTTLENECK GIẢ THUYẾT (3–4)
  → [4 Kiểm độ phù hợp/tin cậy: 25']
  → [5 Lưu link và ghi chú: 15']

TỔNG MINH HỌA: 120 phút/tuần cho 3 môn (đã có tổng thời gian tự báo cáo).

```

### Problem Card #3

| Trường | Nội dung |
|---|---|
| Job Story | Khi nhận dữ liệu cho bài thực hành bằng Excel hoặc Python, tôi muốn làm sạch lỗi dữ liệu và kiểm tra kết quả xử lý, để phân tích trên bộ dữ liệu đáng tin cậy. |
| Actor | Bản thân |
| Thời điểm / bối cảnh | Khi làm bài tập có file dữ liệu cần xử lý bằng Excel/Python; mỗi lần mất khoảng 30–60 phút. |
| Quy trình hiện tại (3–7 bước) | (1) Mở/nhập dữ liệu; (2) kiểm tra thiếu/trùng/sai định dạng; (3) chọn quy tắc xử lý; (4) làm sạch Excel/Python; (5) kiểm tra dữ liệu sau làm sạch; (6) xuất dữ liệu. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3–5 chiếm 30/45 phút minh họa, trong đó thao tác làm sạch ở bước 4 mất 14 phút. |
| Impact (nếu không giải thì sao) | Mỗi lần làm sạch tốn khoảng 30–60 phút và có nguy cơ phân tích trên dữ liệu lỗi. |
| Success metric (baseline → target) | Dưới 30 phút/lần trên dataset tương đương, vẫn đạt checklist kiểm tra. |
| Phương án không dùng AI | Power Query, Excel Filter/Remove Duplicates, các hàm pandas được viết thành script tái sử dụng, checklist kiểm tra dữ liệu trước/sau. |
| Giả thuyết về AI (nếu có) | Nếu quy tắc làm sạch thay đổi theo dataset, AI có thể gợi ý câu lệnh pandas và các phép kiểm tra; người học tự xem logic, chạy trên bản sao và đối chiếu trước/sau. Với quy tắc ổn định, script không AI có thể đã đủ. |
| Cảm nhận nhanh | Rule |

Quy trình nháp hiện tại:

```[1 Mở/nhập dữ liệu: 5']
  → [2 Kiểm tra dữ liệu thiếu/trùng/sai định dạng: 8']
  → [3 Chọn quy tắc làm sạch: 8'] ← BOTTLENECK GIẢ THUYẾT (3–5)
  → [4 Xử lý trong Excel/Python: 14']
  → [5 Kiểm tra dữ liệu sau làm sạch: 8']
  → [6 Xuất dữ liệu: 2']

TỔNG MINH HỌA: 45 phút/lần (người học tự báo cáo 30–60 phút/lần).

```

### Card muốn pitch nhất

- Card số: #1 — Sửa lỗi code Python.
- Vì sao: Có tần suất hằng ngày và thời gian tự báo cáo 1–2 giờ/ngày, nên dễ theo dõi hiệu quả; việc sửa đúng có thể kiểm bằng chạy code/test.
- Câu hỏi muốn nhóm phản biện: “Vấn đề thật nằm ở việc tìm nguyên nhân lỗi hay ở chỗ tôi chưa nắm chắc kiến thức Python? Debugger, tài liệu và test có đủ giải quyết mà không cần AI không?”

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| Số 1–2 giờ/ngày là tự ước lượng, chưa chứng minh mỗi ngày đều sửa code và chưa biết riêng bước nào tốn nhất. | Đồng ý | Đã ghi rõ “tự báo cáo”, đề xuất nhật ký thời gian 10 ngày; các phút theo bước chỉ là phân bổ minh họa. |
| Quy trình và phân bổ thời gian là các bước AI đề xuất, chưa chắc đúng thói quen thực tế của bạn. | Đồng ý | Đánh dấu “quy trình nháp”, “bottleneck giả thuyết” và “phút cần kiểm”; không trình bày như số đã đo. |
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
| CP2 Problem Card | | | | |
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
