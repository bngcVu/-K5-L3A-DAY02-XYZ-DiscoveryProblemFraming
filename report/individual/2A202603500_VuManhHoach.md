# Báo cáo cá nhân — 2A202603500_VuManhHoach

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
| 2 | Tốn thời gian; lặp lại | Khi chương trình Python gặp lỗi, tôi muốn biết nguyên nhân và cách kiểm tra bản sửa, để tiếp tục hoàn thành bài thực hành. | Bản thân. | Khoảng 1–2 giờ/ngày sửa lỗi code. |
| 3 | Cần đọc, tổng hợp nhiều thông tin | Khi đọc tài liệu FinTech bằng tiếng Anh, tôi muốn hiểu chính xác thuật ngữ và nối được các ý chính, để áp dụng vào việc học. | Bản thân. | Khoảng 1 giờ/tài liệu tiếng Anh |
| 4 | Tốn thời gian | Khi làm bài có công thức tài chính, tôi muốn hiểu ý nghĩa biến số và điều kiện áp dụng, để chọn đúng công thức và giải thích được kết quả. | Bản thân. | Khoảng 20 phút/công thức |
| 5 | Tốn thời gian; lặp lại | Khi nhận một bộ dữ liệu để làm bài bằng Excel hoặc Python, tôi muốn phát hiện và xử lý các giá trị thiếu, trùng hoặc sai định dạng, để có dữ liệu đủ tin cậy cho phân tích. | Bản thân; người dùng kết quả phân tích nếu làm bài nhóm. | Khoảng 30 phút - 1 tiếng để làm sạch dữ liệu |
| 6 | Lặp lại; cần tổng hợp nhiều thông tin | Khi ôn thi một môn có nhiều slide và tài liệu, tôi muốn gom kiến thức theo chủ đề và nhận ra nội dung trọng tâm, để ôn tập có hệ thống. | Bản thân. | Khoảng 2 giờ tổng hợp kiến thức cho 1 môn học. |
| 7 | Cần đọc, tổng hợp nhiều thông tin | Khi kết quả phân tích dữ liệu khác kỳ vọng, tôi muốn lần ra bước xử lý hoặc giả định gây sai lệch, để báo cáo kết quả có thể kiểm tra lại. |Bản thân; người đọc báo cáo. | Khoảng 30 phút để tìm ra lỗi. |
| 8 | Pain từ người khác | Khi làm bài nhóm, tôi muốn biết rõ ai phụ trách việc gì và tiến độ từng phần, để các thành viên phối hợp mà không phải hỏi lại nhiều lần. | Bản thân và các thành viên nhóm. | Khó phối hợp, phân chia và theo dõi việc nhóm. |

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
| Cảm nhận nhanh | Workflow |

Quy trình nháp hiện tại:

```
[1 Chạy code, phát hiện lỗi: 5']
  → [2 Đọc traceback/đầu ra: 10']
  → [3 Khoanh vùng nguyên nhân: 20']
  → [4 Tìm tài liệu/cách sửa: 25'] ← BOTTLENECK GIẢ THUYẾT (3–5)
  → [5 Sửa và chạy lại: 20']
  → [6 Đối chiếu kết quả: 10']

TỔNG MINH HỌA: 90 phút.
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
| Cảm nhận nhanh | Workflow |

Quy trình nháp hiện tại:

```
[1 Xác định chủ đề: 10']
  → [2 Tìm trên các nguồn: 30']
  → [3 Mở và lọc tài liệu: 40'] ← BOTTLENECK GIẢ THUYẾT (3–4)
  → [4 Kiểm độ phù hợp/tin cậy: 25']
  → [5 Lưu link và ghi chú: 15']

TỔNG MINH HỌA: 120 phút/tuần cho 3 môn.
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

```
[1 Mở/nhập dữ liệu: 5']
  → [2 Kiểm tra dữ liệu thiếu/trùng/sai định dạng: 8']
  → [3 Chọn quy tắc làm sạch: 8'] ← BOTTLENECK GIẢ THUYẾT (3–5)
  → [4 Xử lý trong Excel/Python: 14']
  → [5 Kiểm tra dữ liệu sau làm sạch: 8']
  → [6 Xuất dữ liệu: 2']

TỔNG MINH HỌA: 45 phút/lần.
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
| Pitch Problem Card | Tôi chuẩn bị ba Card từ các vấn đề đã scan: sửa lỗi Python, tìm tài liệu học tập và làm sạch dữ liệu. Card sửa lỗi Python là đề xuất tôi muốn pitch nhất. | Cả ba đề xuất được đưa vào bảng pitch của nhóm (mục 2.1, dòng #7–#9); Card sửa lỗi Python (#7) vào shortlist ở mục 2.4. Báo cáo nhóm chưa lưu biên bản phát biểu trong buổi pitch. |
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt: nếu kế toán phải đọc lại điều khoản gốc thì có thật sự tiết kiệm thời gian, hay bản tin và checklist đã đủ? |  |
| Nhận phản biện | Câu hỏi tôi nhận được: | Tôi đã sửa gì: |
| Gom cluster / cây OST |Theo phân công, tôi hỗ trợ CP3. Tôi sử dụng cách phân nhóm bốn cluster A–D để xem các vấn đề giống nhau ở thao tác nào; candidate Python #7 của tôi nằm ở cluster D (tìm nguyên nhân, tìm nguồn khi học). | Bảng cluster và OST rút gọn nằm ở mục 2.2–2.3 báo cáo nhóm. |
| Chọn candidate problem | Tôi đưa Card #7 vào danh sách để nhóm so sánh, đồng thời nhìn nhận hạn chế: actor chủ yếu là bản thân, thời gian chưa được đo và debugger/tài liệu/test có thể đủ. | Nhóm chọn cập nhật văn bản pháp luật (#1) thay vì #7; #1 được 27 điểm, #7 được 25 điểm. |
| Kiểm chứng / research | Tôi được phân công hỗ trợ CP4 và đọc kết quả assumption map, nguồn công khai và nghiên cứu các công cụ sẵn có phục vụ candidate #1. | Mục 3 báo cáo nhóm nêu sáu giả định và research giải pháp. |
| Quy trình nhóm | Tôi là người phụ trách chính CP5 theo bảng phân công: phần quy trình hiện tại, quy trình tương lai và bảng so sánh trước/sau. | Mục 4.1–4.3 báo cáo nhóm mô tả 5 bước hiện tại (150 phút/tuần, ước lượng) và 6 bước tương lai (37 phút/tuần, giả định). Phương án giữ kế toán kiểm tra điều khoản và tự gửi cho giám đốc. |
| Problem Statement | Tôi hỗ trợ CP5–CP6 theo phân công, đối chiếu nội dung Problem Statement với các bước quy trình, bottleneck, metric và boundary. | Mục 5 và 7 báo cáo nhóm có v0/v1. Điểm thay đổi quan trọng: thu hẹp actor, bổ sung cách đo baseline, tiêu chí chất lượng và giới hạn việc AI được kết luận. |
| Mức can thiệp AI | Theo phân công, tôi hỗ trợ CP6; từ quy trình CP5, tôi có cơ sở để phân biệt Rule lọc văn bản, AI soạn nháp và bước người kiểm tra. | Mục 6 báo cáo nhóm chọn Workflow có điều kiện, không chọn Agent; No AI/checklist là phương án thử trước hoặc quay về. |
| Quyết định | Tôi hỗ trợ CP6 theo phân công và đối chiếu kết luận với kết quả kiểm chứng còn thiếu. | Nhóm chọn Not Yet vì rủi ro Value còn cao; cần phỏng vấn 2–3 kế toán đúng actor, hỏi một giám đốc và đo baseline trước khi cân nhắc pilot (mục 8). |

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan | Báo cáo cá nhân chưa ghi nhận lần sử dụng AI cụ thể ở bước scan; tôi liệt kê tám vấn đề từ bốn lăng kính của bài tập. | Nếu dùng để gợi ý, AI có thể giúp mở rộng cách nhìn về vấn đề lặp lại và tốn thời gian. | Ý tưởng AI gợi ra không tự chứng minh pain có thật hoặc tần suất chính xác. | Giữ những vấn đề tôi nhận diện được và ghi dấu hiệu ở mức tự ước lượng. |
| CP2 Problem Card | Tôi dùng phản biện từ AI cho Card sửa lỗi Python, đặc biệt về thời gian 1–2 giờ/ngày và phân bổ phút từng bước. | AI giúp phát hiện chỗ thiếu bằng chứng và đặt câu hỏi liệu khó khăn xuất phát từ kỹ năng Python hay từ quá trình tìm nguyên nhân lỗi. | Quy trình sáu bước và con số 65/90 phút là mô hình minh họa, không phải số liệu AI có thể xác nhận từ quan sát. | Tôi ghi rõ “tự báo cáo”, “quy trình nháp”, “bottleneck giả thuyết”, đồng thời đề xuất nhật ký thời gian 10 ngày; giữ bước test do người học thực hiện. |
| CP4 Research | Trong báo cáo nhóm, Claude được dùng để tổng hợp nguồn công khai, đối chiếu các công cụ sẵn có và xây assumption map. Vai trò sử dụng trực tiếp của tôi cần xác nhận. | Tạo bức tranh ban đầu về bản tin pháp lý, hỗ trợ pháp lý, công cụ hỏi đáp và rủi ro sai trích dẫn. | Bằng chứng chủ yếu là nguồn thứ cấp; lời kể không đến từ đúng actor. Trang giới thiệu sản phẩm không chứng minh tính năng, giá hay hiệu quả trong bối cảnh công ty cụ thể. | Khi đọc kết quả, tôi phải phân biệt tín hiệu pain chung với bằng chứng đo thực tế; không gọi sáu nguồn công khai là sáu cuộc phỏng vấn và giữ trạng thái chưa kiểm chứng. |
| CP5 Quy trình | Báo cáo nhóm ghi AI hỗ trợ dựng quy trình hiện tại/tương lai từ Card #1. Tôi phụ trách chính sản phẩm CP5 theo phân công nhóm. | AI giúp hệ thống hóa actor, input/output, thời gian từng bước và vị trí Rule → AI → con người kiểm duyệt. | AI có thể làm quy trình trông hợp lý dù chưa được quan sát; 150 phút hiện tại và 37 phút tương lai đều chưa phải kết quả đo. | Tôi cần giữ nhãn ước lượng/giả định, bổ sung bước lướt danh sách văn bản bị loại, kiểm điều khoản gốc và phương án quay về bản tin + checklist. |
| CP5–6 Problem Statement | Báo cáo nhóm ghi AI hỗ trợ soạn và phản biện v0, đề xuất sửa thành v1. Phần thao tác cá nhân của tôi cần xác nhận. | AI chỉ ra các lỗ hổng về actor thuê ngoài, định nghĩa tuần có văn bản liên quan, bộ mẫu và chất lượng bản nháp. | AI không thể tự biến số phút ước lượng thành baseline hoặc chứng minh người dùng thật muốn công cụ. | Tôi đối chiếu v1 với quy trình: thời gian cần đo riêng từng bước, bổ sung tỉ lệ viết lại, câu hỏi giám đốc hỏi lại và ranh giới AI chỉ nêu “có thể áp dụng”. |
| CP6 Mức can thiệp / quyết định | Báo cáo nhóm dùng AI để hỗ trợ so sánh No AI, Rule, Workflow, Agent và phân tích bốn rủi ro. Tôi được phân công hỗ trợ CP6. | AI giúp đặt các phương án cạnh nhau và nhận diện rủi ro Value, Usability, Feasibility, Viability. | AI dễ đề xuất giải pháp Workflow khi chưa có dữ liệu người dùng; mức điểm và rủi ro vẫn là đánh giá ban đầu. | Tôi giữ logic Workflow chỉ chọn có điều kiện; nếu phỏng vấn cho thấy checklist/Rule đủ dùng thì không cần AI. Quyết định cuối là Not Yet, không phải Go. |

---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**

Điểm tôi có thể rút ra từ việc so sánh các Problem Card là một vấn đề không chỉ được đánh giá qua cảm giác “mất nhiều thời gian”. Đề xuất sửa lỗi Python của tôi có trải nghiệm trực tiếp và tần suất cao nhưng actor chỉ là bản thân; việc mất nhiều thời gian đôi khi còn do thiếu kiến thức, chưa chắc cần AI. Đề xuất tổng hợp sản lượng cuối ca của bạn Trường có quy trình nhập và cộng số liệu khá rõ, nhưng có khả năng chỉ cần biểu mẫu và công thức theo quy tắc. Trong khi đó, đề xuất theo dõi văn bản pháp luật của bạn Vũ có actor cụ thể và một khâu đối chiếu thông tin phức tạp hơn, nhưng số phút vẫn là ước lượng. Bài học tôi muốn giữ là phải tách ba câu hỏi: ai thật sự gặp vấn đề, bằng chứng pain mạnh đến đâu và cách đơn giản nhất để xử lý là gì.

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**

Trong tài liệu OST của nhóm có một ví dụ rõ về nguy cơ solution-first: các ý “đăng ký bản tin pháp lý trả phí”, “bộ lọc văn bản theo ngành” và “trợ lý AI soạn nháp tác động” ban đầu dễ bị coi là opportunity. Thực ra, đó đã là những cách giải. Opportunity cần mô tả khó khăn của kế toán, chẳng hạn mất thời gian xác định điều khoản liên quan hoặc chưa chắc có bỏ sót nghĩa vụ mới. Việc tách hai tầng này giúp nhóm không mặc định rằng phải xây một trợ lý AI. Sau khi nhìn lại research, ngay cả các bước tìm nguồn và lọc văn bản cũng đã có công cụ. Tôi sẽ dùng trường hợp này để tự kiểm tra thói quen nghĩ đến công nghệ quá sớm.

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**

Trường hợp có ghi nhận trực tiếp nhất là Card sửa lỗi Python của tôi ở CP2. Ban đầu, tôi dùng khoảng 1–2 giờ/ngày để thể hiện mức độ mất thời gian và minh họa một quy trình 90 phút, trong đó các bước khoanh vùng lỗi, tìm cách sửa và chạy lại chiếm 65 phút. Phản biện từ AI nhắc rằng 1–2 giờ là tự ước lượng; chưa biết con số này có gồm cả thời gian viết code mới không, và thời gian từng bước chưa được bấm giờ. Tôi đồng ý với điểm này nên sửa cách trình bày thành “quy trình nháp”, “bottleneck giả thuyết”, đồng thời nêu cách ghi nhật ký 10 ngày để kiểm tra. Điều đổi ý quan trọng không phải bỏ vấn đề Python, mà là không dùng một con số thuận tiện để khẳng định pain đã được đo.

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**

Điểm đáng chú ý trong phần research của nhóm là khoảng trống giữa “có người thấy khó theo kịp chính sách” và “đúng nhân viên kế toán mục tiêu mất 150 phút/tuần ở bước đối chiếu”. Nguồn báo chí và tổ chức chuyên môn cho thấy khó khăn chung, nhưng nhóm chưa phỏng vấn hoặc survey người đúng actor; vì vậy chưa thể xác nhận bottleneck chính. Tôi cũng thấy research đặt lại câu hỏi về nhu cầu xây mới: đã có bản tin theo lĩnh vực và dịch vụ phân tích một phần quy định; hơn nữa, có doanh nghiệp thuê ngoài công việc liên quan. Kết quả này khiến phương án No AI hoặc Rule đáng được thử trước. Với tôi, bài học là research không chỉ tìm bằng chứng ủng hộ một ý tưởng; nó còn phải giúp nhận ra trường hợp ý tưởng đó không cần thiết.

**6.5. Điều khó nhất khi viết Problem Statement là gì?**

Khó nhất là viết đủ cụ thể để đo và kiểm chứng, trong khi vẫn trung thực với dữ liệu chưa có. Nếu chỉ ghi “kế toán tốn nhiều thời gian đọc văn bản”, vấn đề quá rộng: không rõ công ty nào, quy trình nào và bước nào thực sự nghẽn. Nhưng nếu khẳng định bước đối chiếu mất 45 phút, lại dễ biến ước lượng thành một sự thật chưa được kiểm chứng. Bản v1 của nhóm đã thu hẹp actor về doanh nghiệp nhỏ không thuê ngoài việc theo dõi quy định, xác định rõ tuần có văn bản liên quan và bổ sung cách đo baseline. Tôi nhận thấy metric cũng không thể chỉ là tốc độ: AI soạn nhanh mà trích dẫn sai, bỏ sót nghĩa vụ hoặc buộc kế toán viết lại quá nhiều thì vẫn thất bại. Vì thế, boundary và bước kiểm của con người phải nằm ngay trong Problem Statement, không chỉ là cảnh báo ở cuối tài liệu.

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**

Nếu làm lại, tôi muốn thu thập bằng chứng từ sớm hơn, trước khi mất nhiều công sức mô tả quy trình tương lai. Với Card Python của bản thân, tôi có thể ghi nhật ký lỗi trong vài ngày, phân loại lỗi, thời gian tìm nguyên nhân và thời gian chạy test để có số liệu thay vì ước lượng. Với candidate chung về văn bản pháp luật, tôi sẽ ưu tiên tìm 2–3 kế toán đúng actor, hỏi về lần gần nhất họ phải xử lý quy định mới và yêu cầu họ chỉ ra bước mất thời gian nhất. Tôi cũng sẽ phản biện mạnh hơn câu hỏi: “Nếu bản tin theo ngành và checklist đã đủ thì vì sao cần AI?” Khi so sánh trước/sau, tôi sẽ yêu cầu kiểm cả tổng thời gian người duyệt, tỉ lệ bản nháp phải sửa và nguy cơ bỏ sót nghĩa vụ. Cuối cùng, tôi muốn mỗi phát biểu về đóng góp, phản biện và việc dùng AI có dấu vết rõ ràng, để báo cáo phản ánh đúng điều nhóm thực sự làm.

**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình.

Vấn đề là kế toán kiêm hành chính ở doanh nghiệp nhỏ khó theo dõi và đối chiếu văn bản pháp luật mới với hoạt động công ty. Quy trình hiện tại gồm nhận bản tin, lọc, đọc, đối chiếu rồi báo giám đốc; khâu đối chiếu là bottleneck giả thuyết. Metric cần đo cả thời gian, nghĩa vụ bị bỏ sót và chất lượng bản nháp. Boundary là AI không tự kết luận hoặc gửi thông báo; kế toán phải kiểm điều khoản gốc. Mức can thiệp đang được xem xét là Workflow có AI ở một bước, còn No AI/Rule là phương án đơn giản hơn. Quyết định của nhóm là Not Yet vì thiếu kiểm chứng với người dùng thật.

---

## 7. Tài liệu tham khảo

- Python Software Foundation. [The Python Tutorial — Errors and Exceptions](https://docs.python.org/3/tutorial/errors.html). Tài liệu về lỗi cú pháp, ngoại lệ và traceback; liên quan Problem Card #1 — sửa lỗi Python.
- Google Scholar. [Google Scholar Search Help](https://scholar.google.com/intl/en/scholar/help.html). Hướng dẫn tìm bài nghiên cứu, lọc theo thời gian, lần theo trích dẫn và tìm bản toàn văn; liên quan Problem Card #2 — tìm tài liệu học tập.
- pandas Development Team. [Working with Missing Data](https://pandas.pydata.org/docs/user_guide/missing_data.html). Tài liệu nhận diện và xử lý giá trị thiếu; liên quan Problem Card #3 — làm sạch dữ liệu Excel/Python.
