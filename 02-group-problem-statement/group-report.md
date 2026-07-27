# Group Report — Day 02

## Thành viên nhóm

| STT | Họ và tên | Mã học viên | Vai trò trong nhóm |
|-----|-----------|-------------|--------------------|
| 1   |Nguyễn Tuấn Khanh           |2A202601139             |Thuyết trình                    |
| 2   |Trần Vương Hưng           |2A202601789             |Thuyết trình                    |
| 3   |Đoàn Quốc Việt           |2A202601623             |Nhà đầu tư                    |
| 4   |Nguyễn Đức Trọng           |2A202601291             |Nhà đầu tư                    |
| 5   |Trần Việt Bách           |2A202601773             |Nhà đầu tư                    |

## Group convergence

Nhóm tổng hợp 11 candidate problems từ phần scan cá nhân. Ở bước này, nhóm chỉ ghi nhận vấn đề, actor và dấu hiệu quan sát được; chưa mặc định bài nào cũng cần AI.

### Danh sách candidate problems

| # | Lăng kính | Problem quan sát được | Ai chịu ảnh hưởng? | Dấu hiệu thật |
|---:|---|---|---|---|
| 1 | Lặp lại | Mỗi tuần phải tổng hợp tiến độ lab từ Discord, GitHub và Google Docs để viết update cho giảng viên | Sinh viên, giảng viên | Mất khoảng 30–45 phút/tuần |
| 2 | Tốn thời gian | Tìm lại quyết định, comment hoặc câu trả lời cũ trong Discord/Docs trước khi làm tiếp | Sinh viên | Thường phải mở nhiều thread và đọc lại 2–3 lần |
| 3 | Tốn thời gian | Đọc tài liệu dài trước deadline rồi tự tóm tắt thành note ngắn để nhớ nội dung | Sinh viên | Mất khoảng 20–30 phút/lần đọc |
| 4 | AI có thể tốt hơn | Tóm tắt nhiều nguồn rời rạc như slide, docs và issue thành một bản ghi ngắn, dễ hiểu | Sinh viên | Cần hiểu ngữ cảnh và viết lại nội dung từ nhiều định dạng |
| 5 | Pain từ người khác | Bạn cùng nhóm hỏi lại task vì spec chưa rõ hoặc không có note chuẩn | Sinh viên, nhóm | Thường phải giải thích lại 2–3 lần/task |
| 6 | Lặp lại | Viết note sau buổi họp nhóm hoặc review theo cùng một format | Sinh viên | Mỗi buổi mất khoảng 10–15 phút để ghi action items |
| 7 | AI có thể tốt hơn | Phân loại ưu tiên nhiệm vụ khi deadline dồn và task nhiều | Sinh viên | Dễ nhầm giữa việc quan trọng và việc khẩn cấp |
| 8 | Pain từ người khác | Giảng viên hoặc trưởng nhóm hỏi tiến độ nhưng chưa có bản tóm tắt sẵn | Sinh viên, giảng viên | Bị chậm khi cần update nhanh trước buổi gặp |
| 9 | Lặp lại | Nhân viên tư vấn phải tra cứu và đối chiếu nhiều học bổng với năng lực, tài chính và mong muốn của từng học viên | Nhân viên tư vấn du học, học viên | Tư vấn viên dựa vào thông tin học viên cung cấp nhưng chưa đề xuất được học bổng phù hợp; việc tra cứu phải làm thủ công |
| 10 | Lặp lại | Sinh viên trì hoãn, thường chỉ học và ôn thi vào những ngày cuối trước kỳ thi | Sinh viên 18–22 tuổi | Hành vi lặp lại giữa kỳ và cuối kỳ |
| 11 | AI có thể tốt hơn | Người học dùng AI làm hộ bài tập nên điểm có thể tăng nhưng năng lực thực tế không tiến bộ tương ứng | Người sử dụng AI trong học tập | Có nguy cơ mất chất học và phụ thuộc vào AI |

### Gom trùng / cluster

| Cluster | Candidates included | Pattern chung | Ghi chú |
|---|---|---|---|
| Tổng hợp và truy xuất thông tin | #1, #2, #3, #4, #6, #8 | Gom, tìm và viết lại thông tin từ nhiều nguồn để phục vụ học tập hoặc báo cáo | Workflow rõ, dễ làm trong lab nhưng có nhiều giải pháp tóm tắt sẵn |
| Phối hợp và quản lý công việc | #5, #7, #10 | Thiếu thông tin chuẩn, khó ưu tiên hoặc trì hoãn dẫn đến phải làm lại/chậm deadline | Pain có thật nhưng nguyên nhân có thể thuộc hành vi hoặc cách tổ chức, không chỉ do thiếu công cụ |
| Học tập có trách nhiệm với AI | #11 | AI tạo output nhanh nhưng có thể làm giảm quá trình tự học | Impact lớn nhưng khó đặt metric và boundary trong phạm vi một bài lab ngắn |
| Tư vấn và đối chiếu học bổng | #9 | Phải đọc điều kiện không đồng nhất từ nhiều nguồn rồi so với hồ sơ từng học viên | Actor, workflow, bottleneck và điểm kiểm tra của con người tương đối rõ |

## Shortlist

| Candidate | Vì sao vào shortlist | Rủi ro / điều chưa rõ |
|---|---|---|
| Trợ lý đối chiếu học bổng | Có actor cụ thể, quy trình nhiều bước, bottleneck rõ và impact có thể đo bằng thời gian tạo shortlist | Baseline mới là ước lượng; thông tin học bổng thay đổi; điều kiện có thể mơ hồ hoặc mâu thuẫn |
| Tóm tắt nhiều nguồn phục vụ update | Tần suất lặp lại cao, có baseline 30–45 phút/tuần, dễ tạo prototype | Nhiều công cụ hiện có đã hỗ trợ; chất lượng “đủ tốt” cần tiêu chí chấm rõ |
| Tìm lại quyết định cũ trong Discord/Docs | Nhu cầu xảy ra thường xuyên, kết quả có thể đo bằng thời gian tìm và tỷ lệ tìm đúng | Cần quyền truy cập nhiều nguồn và dữ liệu lịch sử đủ sạch |
| Làm rõ task/spec và tạo note chuẩn | Có pain từ nhiều thành viên, giảm số lần phải giải thích lại | Nguyên nhân có thể là kỷ luật viết spec; template/process fix có thể đã đủ |

## Shortlist và score

Thang điểm: `1 = yếu/chưa rõ`, `5 = rất rõ/rất phù hợp`. Điểm dùng để buộc nhóm giải thích lựa chọn, không phải kết quả đo lường tuyệt đối.

| Candidate | Actor rõ | Workflow rõ | Pain có evidence | Impact đo được | Làm trong lab | So sánh R/W/A được | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| Trợ lý đối chiếu học bổng | 5 | 5 | 3 | 5 | 4 | 5 | 5 | **32** |
| Tóm tắt nhiều nguồn phục vụ update | 4 | 5 | 4 | 4 | 5 | 5 | 4 | **31** |
| Tìm lại quyết định cũ | 4 | 4 | 4 | 4 | 3 | 5 | 4 | **28** |
| Làm rõ task/spec và tạo note chuẩn | 4 | 4 | 4 | 3 | 5 | 4 | 4 | **28** |

Nhóm chọn candidate:

```text
Nhân viên tư vấn du học mất nhiều thời gian tra cứu, đọc và đối chiếu học bổng
phù hợp với năng lực, tài chính và mong muốn của từng học viên.
```

Vì sao chọn:

- Actor trực tiếp là nhân viên tư vấn du học; người hưởng lợi gián tiếp là học viên, phụ huynh và trung tâm.
- Có thể vẽ được workflow từ tiếp nhận hồ sơ đến tạo shortlist và giải thích kết quả.
- Bottleneck tập trung ở bước đọc và đối chiếu thủ công các điều kiện không đồng nhất.
- Có thể đo bằng thời gian tạo shortlist, tỷ lệ kết luận đúng và tỷ lệ kết quả có nguồn chính thức.
- Có đủ chỗ để so sánh process fix, Rule, Workflow và Agent mà không mặc định phải chọn Agent.

Vì sao không chọn các candidate còn lại:

- Tóm tắt nhiều nguồn có baseline rõ và dễ làm, nhưng giá trị khác biệt thấp hơn và có thể giải quyết phần lớn bằng template cùng công cụ tóm tắt hiện có.
- Tìm quyết định cũ có impact rộng nhưng phụ thuộc quyền truy cập Discord/Docs và chất lượng dữ liệu lịch sử.
- Làm rõ task/spec có thể nên bắt đầu bằng template, Definition of Done và kỷ luật handoff trước khi thêm AI.

## Quick validation

Nhóm đã tìm kiếm trên Internet và đối chiếu 4 nguồn/công cụ đang giải quyết một phần bài toán học bổng. Nhóm chưa có biên bản phỏng vấn chuyên viên tư vấn để làm bằng chứng, vì vậy phần trao đổi với chuyên viên được ghi thành kế hoạch validation cần thực hiện, không trình bày như kết quả đã xảy ra.

| Nguồn | Số người / số mẫu | Tín hiệu xác nhận | Tín hiệu phản bác / chưa chắc | Nhóm sửa problem thế nào |
|---|---:|---|---|---|
| Tìm kiếm và đối chiếu trên Internet | 4 nguồn/công cụ | Đã có pattern tìm kiếm theo bộ lọc, matching theo hồ sơ và danh mục nguồn chính thức | Không có nguồn nào chứng minh workflow của nhóm sẽ đạt metric đề xuất | Triển khai nội bộ có kiểm soát và đo kết quả thực tế; không dùng claim marketing làm bằng chứng hiệu quả |
| Quan sát candidate của nhóm | 1 tình huống được mô tả | Tư vấn viên phải dựa vào thông tin học viên và tra cứu thủ công nhưng chưa tạo được đề xuất phù hợp | Chưa có log thời gian hoặc số lượng hồ sơ | Dùng khoảng 90–180 phút như baseline giả định cần đo lại |
| Phỏng vấn chuyên viên tư vấn | 0 — chưa thực hiện | Cần hỏi về lần gần nhất tạo shortlist, thời gian thực tế, bước đau nhất và cách kiểm nguồn | Chưa có dữ liệu để xác nhận hoặc phản bác | Phỏng vấn 2–3 chuyên viên trước khi go-live, sau đó tiếp tục thu phản hồi của toàn bộ nhân viên trong quá trình vận hành |

Insight sau validation:

```text
Pain không chỉ nằm ở việc “tìm học bổng”, mà nằm ở đoạn chuyển thông tin điều kiện
không đồng nhất thành một shortlist có căn cứ, phù hợp với hồ sơ và đủ an toàn để tư vấn.
```

Các giả định cần kiểm chứng:

- Một shortlist thủ công hiện mất trung bình 90–180 phút.
- Đọc và đối chiếu điều kiện là bước tốn thời gian nhất.
- Tư vấn viên chấp nhận dùng một bản xếp hạng sơ bộ nếu mỗi kết luận đều kèm nguồn.
- Có thể giảm ít nhất 50% thời gian mà vẫn giữ độ chính xác tối thiểu 90%.

### Bằng chứng đã có và giả định còn mở

| Nội dung | Trạng thái | Căn cứ hiện có | Cách kiểm chứng tiếp theo |
|---|---|---|---|
| Có các hệ thống tìm kiếm/matching học bổng theo profile và điều kiện | **Đã có bằng chứng** | 4 nguồn/công cụ được đối chiếu trong phần research | Lưu link, ngày truy cập và phạm vi mà từng nguồn hỗ trợ |
| Điều kiện học bổng nằm ở nhiều nguồn và có cách trình bày khác nhau | **Đã có tín hiệu** | Quan sát candidate và cấu trúc khác nhau giữa các trang học bổng | Chọn 20–30 học bổng từ các nguồn chính thức và thống kê field/ngoại lệ |
| Tư vấn viên mất 90–180 phút cho một shortlist | **Giả định mở** | Ước lượng của nhóm, chưa có log thực tế | Bấm giờ tối thiểu 5 ca xử lý thủ công với 2–3 chuyên viên |
| Đọc và đối chiếu là bottleneck lớn nhất | **Giả định mở** | Suy ra từ current workflow | Phỏng vấn chuyên viên và ghi thời gian theo từng bước |
| Workflow có thể giảm ít nhất 50% thời gian | **Giả định cần thử nghiệm** | Mục tiêu thiết kế, chưa phải kết quả | Chạy cùng hồ sơ bằng cách thủ công và workflow rồi so sánh |
| Tư vấn viên chấp nhận output AI có citation | **Giả định cần kiểm chứng** | Chưa có phỏng vấn hoặc usability test | Cho 2–3 chuyên viên review output mẫu và chấm mức hữu ích 1–5 |

## Research giải pháp

| Nguồn / tool / case | Link | Họ giải quyết phần nào? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| BigFuture Scholarship Search | [College Board](https://bigfuture.collegeboard.org/help-center/how-does-scholarship-search-work) | Dùng thông tin trong profile để match với yêu cầu của nhà cung cấp học bổng | Pattern profile → eligibility match rõ ràng | Tập trung vào hệ sinh thái của họ; match vẫn phụ thuộc dữ liệu profile và yêu cầu đã cấu trúc | Chuẩn hóa hồ sơ trước khi match và không chạy khi thiếu field bắt buộc |
| DAAD Scholarship Database | [DAAD](https://www2.daad.de/deutschland/stipendium/datenbank/en/21148-scholarship-database/?back=1&page=1) | Cung cấp cơ sở dữ liệu học bổng và bộ lọc tìm kiếm | Nguồn chính thức, phù hợp làm nguồn kiểm tra | Phạm vi tập trung vào chương trình liên quan DAAD/Đức; tư vấn viên vẫn phải đọc chi tiết | Ưu tiên nguồn chính thức và lưu URL, ngày kiểm tra cho từng kết luận |
| EducationUSA Financial Aid | [EducationUSA](https://educationusa.state.gov/find-financial-aid/) | Cho phép tìm các cơ hội tài trợ và lọc thông tin liên quan du học Mỹ | Nguồn thuộc mạng lưới tư vấn chính thức, có danh sách cơ hội cụ thể | Không tự đối chiếu toàn bộ điều kiện với hồ sơ cá nhân | Search/filter là input; lớp đối chiếu và giải thích vẫn cần workflow riêng |
| ScholarMatched | [ScholarMatched](https://www.scholarmatched.com/about) | Mô tả mô hình AI match học bổng theo quốc tịch, bậc học, học lực, ngành và mục tiêu | Gần với candidate của nhóm; cho thấy pattern ranking và giải thích theo profile | Các claim hiệu quả trên trang sản phẩm chưa phải bằng chứng độc lập; nguồn dữ liệu cần được kiểm tra | Không dùng “điểm phù hợp” như xác suất đậu; chỉ dùng để ưu tiên thứ tự tư vấn viên review |

Tham khảo phương pháp thiết kế AI lấy con người làm trung tâm: [People + AI Guidebook](https://pair.withgoogle.com/guidebook/). Với bài toán này, nguyên tắc được áp dụng là xác định rõ lúc AI cần chuyển quyền cho con người, giải thích căn cứ của output và thiết kế fallback khi AI không đủ tin cậy.

Research takeaway:

```text
Không cần bắt đầu bằng một Agent tự tìm và tự gửi kết quả. MVP hợp lý hơn là
Workflow: chuẩn hóa hồ sơ → Rule lọc điều kiện cứng → AI đọc/trích xuất/đối chiếu
→ tư vấn viên kiểm nguồn và phê duyệt.
```

## Current workflow

| Bước | Actor | Input | Output | Thời gian / tần suất | Handoff | Ghi chú |
|---:|---|---|---|---|---|---|
| 1 | Học viên, tư vấn viên | Nhu cầu du học ban đầu | Thông tin mục tiêu và ngân sách | 10–15 phút / mỗi hồ sơ mới | Học viên cung cấp thông tin → tư vấn viên ghi nhận | Phỏng vấn, làm rõ mong muốn |
| 2 | Tư vấn viên | Hồ sơ học viên | Hồ sơ đủ trường dữ liệu cần thiết | 5–15 phút / mỗi hồ sơ; lặp lại nếu thiếu | Tư vấn viên yêu cầu học viên bổ sung rồi nhận lại hồ sơ | Có thể phát sinh chờ đợi |
| 3 | Tư vấn viên | Hồ sơ và mục tiêu | Danh sách học bổng thô | 15–30 phút / mỗi shortlist | Danh sách thô → bước đọc điều kiện | Tìm trên nhiều website |
| 4 | Tư vấn viên | Trang học bổng | Bộ điều kiện của từng học bổng | 20–40 phút / mỗi shortlist | Điều kiện đã đọc → bước đối chiếu hồ sơ | Cách trình bày không đồng nhất |
| 5 | Tư vấn viên | Điều kiện và hồ sơ | Kết luận phù hợp/chưa phù hợp | 25–45 phút / mỗi shortlist | Kết luận sơ bộ → bước kiểm deadline và tài trợ | **Bottleneck chính** |
| 6 | Tư vấn viên | Deadline, mức tài trợ | Danh sách còn hiệu lực | 5–10 phút / mỗi shortlist | Danh sách còn hạn → bước lập shortlist | Có nguy cơ dùng thông tin cũ |
| 7 | Tư vấn viên | Danh sách đã kiểm tra | Shortlist và giải thích cho học viên | 10–25 phút / mỗi hồ sơ | Tư vấn viên → học viên/phụ huynh | Tư vấn viên chịu trách nhiệm cuối |

```text
CURRENT STATE — 7 bước, khoảng 90–180 phút/shortlist

[1 Tiếp nhận nhu cầu: 10–15']
→ [2 Kiểm tra/bổ sung hồ sơ: 5–15']
→ [3 Tìm trên nhiều website: 15–30']
→ [4 Đọc điều kiện: 20–40']
→ [5 Đối chiếu thủ công: 25–45']  <-- bottleneck
→ [6 Kiểm tra deadline/tài trợ: 5–10']
→ [7 Tạo shortlist và giải thích: 10–25']
```

Bottleneck chính:

```text
Tư vấn viên phải đọc, diễn giải và đối chiếu thủ công các điều kiện được viết
không đồng nhất với nhiều trường hồ sơ như GPA, IELTS, quốc tịch, ngành học,
kinh nghiệm, khả năng tài chính và deadline.
```

## Future workflow

| Bước | Actor / cơ chế | Input | Output | Thời gian / tần suất mục tiêu | Handoff | Boundary |
|---:|---|---|---|---|---|---|
| 1 | Học viên, tư vấn viên | Form hồ sơ chuẩn hóa | Hồ sơ có cấu trúc | 5–10 phút / mỗi hồ sơ mới | Học viên nhập → tư vấn viên xác nhận nhu cầu | Con người làm rõ nhu cầu |
| 2 | Rule | Hồ sơ có cấu trúc | Danh sách field thiếu/sai | Dưới 1 phút / mỗi lần submit | Rule trả lỗi → học viên/tư vấn viên bổ sung | Không suy đoán field còn thiếu |
| 3 | Rule | Hồ sơ đủ và học bổng còn hạn | Danh sách qua điều kiện cứng | 1–2 phút / mỗi lần chạy | Danh sách đã lọc → AI trích xuất chi tiết | Lọc tuổi, quốc tịch, bậc học, GPA, IELTS, deadline |
| 4 | AI trong workflow | Nguồn học bổng chính thức | Điều kiện, mức tài trợ, deadline có trích nguồn | 2–5 phút / mỗi shortlist | Dữ liệu đã trích → bước đối chiếu | Không có nguồn thì không được kết luận |
| 5 | AI trong workflow | Hồ sơ và điều kiện đã trích xuất | Match sơ bộ, lý do và cờ cần xác minh | 2–5 phút / mỗi shortlist | AI draft → hàng đợi review của tư vấn viên | Điểm match không phải xác suất đậu |
| 6 | Tư vấn viên | Match sơ bộ và nguồn | Shortlist đã xác minh | 15–25 phút / mỗi shortlist | Tư vấn viên duyệt → bước tư vấn học viên | **Human review bắt buộc** |
| 7 | Tư vấn viên | Shortlist đã duyệt | Giải thích và checklist gửi học viên | 5–10 phút / mỗi hồ sơ | Tư vấn viên → học viên/phụ huynh | AI không tự gửi hoặc cam kết kết quả |

```text
FUTURE STATE — 7 bước, mục tiêu 30–60 phút/shortlist

[1 Điền form chuẩn hóa: 5–10']               -- Học viên + tư vấn viên
→ [2 Kiểm tra field thiếu: <1']               -- Rule
→ [3 Lọc điều kiện cứng: 1–2']                -- Rule
→ [4 Trích xuất từ nguồn chính thức: 2–5']    -- AI trong Workflow
→ [5 Đối chiếu + giải thích sơ bộ: 2–5']      -- AI trong Workflow
→ [6 Kiểm nguồn + phê duyệt: 15–25']          -- Human boundary
→ [7 Tư vấn viên gửi và giải thích: 5–10']    -- Human owner

Fallback:
- Không có nguồn chính thức hoặc nguồn mâu thuẫn → gắn “Cần xác minh”, không đưa vào shortlist chính thức.
- AI trích sai hoặc độ tin cậy thấp → tư vấn viên bỏ kết quả AI và kiểm tra thủ công.
- Chất lượng vận hành không đạt ngưỡng → hạ xuống form chuẩn + Rule + checklist và tạm dừng phần AI.
```

## Before/after impact

| Metric | Trước | Sau kỳ vọng | Cách đo / ghi chú |
|---|---:|---:|---|
| Tổng thời gian tạo một shortlist | 90–180 phút (ước lượng) | 30–60 phút | Bấm giờ từ lúc hồ sơ đủ đến khi shortlist được duyệt; mục tiêu giảm ít nhất 50% |
| Số bước chính | 7 | 7 | Không giảm số bước bằng mọi giá; giảm effort tại bước đọc và đối chiếu |
| Bước xử lý thủ công chính | 6–7 bước | 2–3 bước | Con người vẫn làm rõ nhu cầu, xử lý ngoại lệ và phê duyệt |
| Tỷ lệ đề xuất sơ bộ có nguồn chính thức | Chưa đo | Từ 90% trở lên | Audit URL, đoạn trích và ngày kiểm tra; đề xuất thiếu nguồn phải gắn cờ và không được tự động đưa vào shortlist |
| Tỷ lệ kết luận được tư vấn viên xác nhận đúng | Chưa đo | Từ 90% trở lên | Chấm trên tập test có nhãn của tư vấn viên |
| Tỷ lệ học bổng còn hạn | Chưa đo | Từ 95% trở lên | Đối chiếu deadline tại thời điểm review |
| Bottleneck chính | Đọc và đối chiếu thủ công | Review ngoại lệ và xác minh nguồn | Bottleneck mới là điểm kiểm soát chất lượng chấp nhận được |
| Risk mới | Bỏ sót, hiểu sai, dùng tin cũ | Hallucination, trích sai, xếp hạng gây hiểu nhầm | Kiểm soát bằng citation, cờ “Cần xác minh” và human approval |

Các con số trên là mục tiêu giả định. Trung tâm phải đo lại baseline trong giai đoạn triển khai ban đầu trước khi kết luận giải pháp tạo ra cải thiện.

## Boundary người – máy

| Rule thực hiện | AI trong Workflow thực hiện | Con người thực hiện |
|---|---|---|
| Kiểm tra trường bắt buộc và định dạng | Đọc nội dung từ nguồn học bổng được cho phép | Làm rõ nhu cầu và ưu tiên của học viên |
| Lọc tuổi, quốc tịch, bậc học | Trích xuất điều kiện, deadline, mức tài trợ | Xác minh điều kiện mơ hồ hoặc nguồn mâu thuẫn |
| So sánh ngưỡng GPA, IELTS, deadline | Đối chiếu hồ sơ và giải thích match sơ bộ | Đánh giá mức phù hợp tổng thể |
| Loại học bổng đã đóng đơn | Gắn cờ trường hợp thiếu căn cứ/cần xác minh | Phê duyệt shortlist và trao đổi với học viên |

AI không được:

- Tự cam kết học viên sẽ nhận học bổng hoặc trình bày điểm match như xác suất trúng tuyển.
- Tạo điều kiện, deadline, mức tài trợ hoặc URL nguồn khi không có bằng chứng.
- Tự gửi shortlist chưa được tư vấn viên phê duyệt.
- Tự suy diễn khả năng tài chính, hoàn cảnh cá nhân hoặc dữ liệu hồ sơ còn thiếu.
- Dùng nguồn không chính thức làm căn cứ duy nhất cho kết luận đủ/không đủ điều kiện.

Phạm vi triển khai nội bộ:

- Áp dụng cho toàn bộ nhân viên tư vấn tại một trung tâm du học.
- Mỗi nhân viên sử dụng cùng form hồ sơ, checklist kiểm nguồn và quy trình review.
- Chỉ sử dụng các quốc gia và nguồn học bổng chính thức đã được trung tâm phê duyệt; có thể bổ sung nguồn theo từng đợt kiểm tra.
- Hệ thống chỉ tạo shortlist sơ bộ và checklist xác minh.
- Không tự nộp đơn, không viết toàn bộ hồ sơ xin học bổng và không tự gửi kết quả cho học viên.
- Chỉ thu thập dữ liệu hồ sơ cần thiết; trung tâm quy định quyền truy cập, thời gian lưu và quy trình xóa dữ liệu.

## Success metrics

| Chỉ số | Baseline | Mục tiêu triển khai nội bộ | Cách đo |
|---|---:|---:|---|
| Thời gian trung bình tạo một shortlist có nguồn và đã được duyệt | 90–180 phút (cần đo lại) | Giảm ít nhất 50%, hướng tới 30–60 phút | Bấm giờ trên cùng loại hồ sơ, so sánh manual và workflow |
| Tỷ lệ kết luận điều kiện đúng | Chưa đo | ≥ 90% | Tư vấn viên chấm đúng/sai trên tập test |
| Tỷ lệ đề xuất sơ bộ có nguồn chính thức | Chưa đo | ≥ 90% | Audit URL, đoạn trích và ngày kiểm tra cho từng đề xuất |
| Tỷ lệ học bổng còn hạn | Chưa đo | ≥ 95% | Kiểm tra deadline khi duyệt |
| Hallucination nghiêm trọng | Chưa đo | 0 trường hợp | Ghi log mọi claim không có trong nguồn |
| Năng suất xử lý hồ sơ | Chưa đo | Tăng ≥ 30% hồ sơ/tư vấn viên/tuần | So sánh số hồ sơ cùng khung thời gian |
| Mức hữu ích do tư vấn viên đánh giá | Chưa đo | ≥ 4/5 | Survey ngắn sau từng ca xử lý trong giai đoạn đầu |

## Problem Statement v0

| Field | Nội dung |
|---|---|
| **Actor** | Nhân viên tư vấn du học là người chịu ảnh hưởng trực tiếp; học viên, phụ huynh và trung tâm chịu ảnh hưởng gián tiếp. |
| **Workflow** | Tiếp nhận nhu cầu → thu thập/bổ sung hồ sơ → tìm học bổng trên nhiều website → đọc điều kiện → đối chiếu hồ sơ → kiểm tra deadline/mức tài trợ → tạo và giải thích shortlist. |
| **Bottleneck** | Đọc và đối chiếu thủ công các điều kiện không đồng nhất như GPA, IELTS, quốc tịch, ngành học, kinh nghiệm, tài chính và deadline. |
| **Impact** | Một shortlist được ước lượng mất 90–180 phút; dễ bỏ sót cơ hội, hiểu sai điều kiện hoặc dùng thông tin đã cũ; kết quả phụ thuộc kinh nghiệm từng tư vấn viên. |
| **Success Metric** | Giảm ít nhất 50% thời gian; ít nhất 90% đề xuất sơ bộ có nguồn chính thức; ít nhất 90% kết luận được tư vấn viên xác nhận đúng. |
| **Boundary** | Rule xử lý điều kiện cứng; AI chỉ đọc, trích xuất và đối chiếu sơ bộ; tư vấn viên kiểm nguồn, xử lý ngoại lệ và phê duyệt. AI không tự cam kết hoặc tự gửi kết quả. |

Problem Statement v0 dạng một đoạn:

> Nhân viên tư vấn du học phải tìm kiếm, đọc và đối chiếu thủ công điều kiện học bổng từ nhiều nguồn trước khi lập danh sách đề xuất cho học viên. Điểm nghẽn nằm ở bước xử lý các điều kiện không đồng nhất như GPA, IELTS, quốc tịch, ngành học, kinh nghiệm, tài chính và deadline. Việc này được ước lượng làm một shortlist mất 90–180 phút, đồng thời tăng nguy cơ bỏ sót cơ hội hoặc sử dụng thông tin không còn hiệu lực. Giải pháp thành công khi giảm ít nhất 50% thời gian, có ít nhất 90% đề xuất sơ bộ kèm nguồn chính thức và ít nhất 90% kết luận được tư vấn viên xác nhận. Rule xử lý điều kiện cứng, AI hỗ trợ đọc và đối chiếu, còn tư vấn viên review và phê duyệt cuối cùng.

## No AI / Rule / Workflow / Agent

| Mức | Phương án cho bài toán nhóm | Khi nào đủ | Rủi ro / giới hạn | Chọn? |
|---|---|---|---|---|
| **No AI / Process fix** | Form hồ sơ chuẩn, checklist nguồn, template shortlist và quy ước ngày cập nhật | Đủ nếu pain chủ yếu do hồ sơ thiếu hoặc cách làm giữa tư vấn viên không thống nhất | Vẫn phải đọc và diễn giải từng điều kiện dài | Dùng làm nền bắt buộc |
| **Rule** | Lọc GPA, IELTS, tuổi, quốc tịch, bậc học, deadline và điều kiện cứng | Đủ với dữ liệu đã cấu trúc và tiêu chí đúng/sai rõ | Không xử lý tốt văn bản dài, ngoại lệ và tiêu chí mơ hồ | Dùng cho bước lọc cứng |
| **Workflow** | Form → Rule kiểm tra/lọc → AI trích xuất/đối chiếu → tư vấn viên review | Phù hợp vì thứ tự bước rõ, AI chỉ hỗ trợ các bước ngôn ngữ | AI có thể hiểu sai hoặc trích sai; cần nguồn và human review | **Chọn cho MVP** |
| **Agent** | Tự tìm nhiều nguồn, gọi công cụ, theo dõi thay đổi và chủ động cập nhật shortlist | Chỉ cần khi nguồn và nhánh xử lý đã ổn định, quyền truy cập rõ, có monitoring | Quá phức tạp ở giai đoạn đầu; khó kiểm soát nguồn, quyền và lỗi dây chuyền | Chưa chọn |

Mức chọn:

```text
Workflow: No-AI process foundation + Rule + LLM + Human Review.
```

Vì sao:

- Bài toán có đường đi tương đối cố định nên chưa cần Agent tự lập kế hoạch.
- Process fix và Rule xử lý tốt dữ liệu thiếu cùng điều kiện cứng, nhưng chưa giải quyết bottleneck đọc văn bản không đồng nhất.
- AI phù hợp ở bước trích xuất, chuẩn hóa và giải thích ngôn ngữ.
- Tư vấn viên giữ quyền quyết định nên có thể kiểm soát hậu quả khi AI sai.

## Rủi ro và biện pháp kiểm soát

| Rủi ro | Hậu quả | Biện pháp kiểm soát | Owner |
|---|---|---|---|
| AI hiểu sai điều kiện | Đưa học bổng không phù hợp vào shortlist | Hiển thị đoạn nguồn, URL và cờ độ tin cậy; bắt buộc review | Tư vấn viên |
| AI dùng thông tin cũ | Học viên bỏ lỡ deadline hoặc chuẩn bị sai | Lưu ngày kiểm tra, ưu tiên nguồn chính thức, kiểm deadline trước khi gửi | Tư vấn viên |
| AI bịa thông tin/nguồn | Tư vấn sai và mất uy tín | Không chấp nhận kết quả thiếu citation; ghi log hallucination | Owner vận hành |
| Xếp hạng gây hiểu nhầm | Học viên hiểu điểm cao là chắc chắn nhận học bổng | Gọi là “ưu tiên review”, không gọi là xác suất đậu | Tư vấn viên |
| Hồ sơ thiếu | Matching sai hoặc thiên lệch | Rule chặn workflow và yêu cầu bổ sung | Học viên, tư vấn viên |
| Lộ dữ liệu cá nhân | Ảnh hưởng quyền riêng tư của học viên | Thu thập tối thiểu, phân quyền truy cập, quy định thời gian lưu/xóa | Trung tâm |
| Nhân viên tin AI tuyệt đối | Lỗi không được phát hiện trước khi gửi | Human approval bắt buộc và audit mẫu định kỳ | Trưởng nhóm tư vấn |

## Problem Statement v1

| Field | Nội dung |
|---|---|
| **Actor** | Nhân viên tư vấn du học phụ trách tạo shortlist học bổng cho học viên. |
| **Workflow** | Tiếp nhận hồ sơ → kiểm tra dữ liệu → tìm nguồn chính thức → đọc/trích điều kiện → đối chiếu hồ sơ → kiểm deadline và mức tài trợ → review → giải thích cho học viên. |
| **Bottleneck** | Bước đọc, diễn giải và đối chiếu thủ công điều kiện không đồng nhất từ nhiều nguồn. |
| **Impact** | Ước lượng 90–180 phút/shortlist, giảm năng suất và tăng nguy cơ bỏ sót, hiểu sai hoặc dùng thông tin hết hiệu lực. Baseline này được đo lại trong giai đoạn triển khai ban đầu. |
| **Success Metric** | Giảm ít nhất 50% thời gian; ≥ 90% đề xuất sơ bộ có nguồn chính thức; ≥ 90% kết luận được xác nhận đúng; ≥ 95% học bổng còn hạn; 0 hallucination nghiêm trọng. |
| **Boundary** | Hệ thống nội bộ chỉ tạo shortlist sơ bộ từ tập nguồn chính thức được trung tâm phê duyệt. Không tự nộp hồ sơ, không cam kết khả năng nhận học bổng, không tự gửi kết quả và không suy diễn dữ liệu còn thiếu. |
| **AI intervention point** | Sau khi hồ sơ đã được chuẩn hóa và Rule lọc điều kiện cứng: AI trích xuất điều kiện, đối chiếu và tạo lý do sơ bộ trước bước tư vấn viên review. |
| **Mức chọn** | Workflow: Process foundation + Rule + LLM + Human Review. |
| **Rủi ro & người thật kiểm tra** | Rủi ro gồm hiểu sai, nguồn cũ, hallucination, xếp hạng gây hiểu nhầm và lộ dữ liệu. Tư vấn viên kiểm nguồn và phê duyệt; owner vận hành theo dõi log lỗi. |

Problem Statement v1 dạng một đoạn:

> Nhân viên tư vấn du học hiện phải tiếp nhận hồ sơ, tìm học bổng trên nhiều nguồn, đọc từng điều kiện và tự đối chiếu với năng lực, tài chính và mong muốn của học viên. Điểm nghẽn lớn nhất là bước đọc, diễn giải và đối chiếu thủ công các điều kiện không đồng nhất, khiến thời gian xử lý được ước lượng ở mức 90–180 phút/shortlist và làm tăng nguy cơ bỏ sót hoặc sử dụng thông tin không còn hiệu lực. Nhóm đề xuất Workflow kết hợp process chuẩn hóa, Rule, LLM và Human Review: Rule xử lý điều kiện cứng; AI đọc nguồn chính thức, trích xuất và đối chiếu sơ bộ; tư vấn viên kiểm tra và phê duyệt. Triển khai nội bộ được xem là đạt yêu cầu khi giảm ít nhất 50% thời gian, ít nhất 90% đề xuất sơ bộ có nguồn chính thức, ít nhất 90% kết luận được xác nhận đúng, ít nhất 95% học bổng còn hạn và không có hallucination nghiêm trọng.

## Final decision

### Đối chiếu khung Go / Not Yet / No-Go

| Nhánh quyết định | Tiêu chí của khung | Đánh giá với bài toán nhóm | Kết luận |
|---|---|---|---|
| **Go** | Bài toán rõ; chỉ số đo lường khả thi; điểm AI can thiệp phù hợp; kiểm soát được rủi ro | Actor, workflow và bottleneck đã rõ. Có thể đo thời gian, độ chính xác và citation. AI chỉ hỗ trợ trích xuất/đối chiếu; tư vấn viên giữ quyền phê duyệt và có fallback | **Go cho triển khai nội bộ có kiểm soát với toàn bộ nhân viên tư vấn trong một trung tâm** |
| **Not Yet** | Cần thêm dữ liệu thực tế; chuẩn hóa quy trình; thiết lập chỉ số; xác định ranh giới | Chưa có dữ liệu đại diện cho nhiều trung tâm, nhiều quy trình và toàn bộ thị trường học bổng quốc tế | **Not Yet cho mở rộng sang nhiều trung tâm hoặc triển khai diện rộng ở nhiều quốc gia** |
| **No-Go** | AI không tạo giá trị vượt trội; rủi ro vận hành quá cao; giải pháp không AI tối ưu hơn | Agent tự tìm nguồn, tự quyết định, tự gửi hoặc cam kết kết quả tạo rủi ro vượt quá boundary hiện tại | **No-Go với Agent tự chủ, tự gửi kết quả hoặc tự cam kết khả năng nhận học bổng** |

Lập luận quyết định:

```text
Nhóm Go cho triển khai nội bộ tại một trung tâm và cho phép toàn bộ nhân viên tư vấn
sử dụng theo cùng một workflow có human review. Việc mở rộng sang nhiều trung tâm
hoặc nhiều quốc gia là “Not Yet”; Agent tự chủ, tự gửi hoặc tự cam kết là “No-Go”.
```

| Câu hỏi | Yes / Not Yet / No | Ghi chú |
|---|---|---|
| Actor và workflow đã rõ chưa? | Yes | Actor trực tiếp và 7 bước hiện tại đã được mô tả |
| Baseline và success metric có đo được không? | Yes, có điều kiện | Có khoảng ước lượng 90–180 phút và cách bấm giờ; đo lại trong 2 tuần vận hành đầu tiên |
| Có data/input đủ dùng chưa? | Yes, có điều kiện | Chỉ go-live sau khi trung tâm phê duyệt form hồ sơ và tập nguồn chính thức ban đầu |
| Nếu AI sai, hậu quả có chấp nhận được không? | Yes, có điều kiện | Chỉ chấp nhận khi output là bản sơ bộ, có citation và bắt buộc human review |
| Có người review/owner vận hành không? | Yes, có điều kiện | Mỗi tư vấn viên review hồ sơ của mình; trung tâm chỉ định một owner theo dõi nguồn, quyền truy cập và log lỗi trước go-live |
| Có cách non-AI đơn giản hơn không? | Yes, một phần | Form, checklist và Rule nên được triển khai trước/làm nền |

Decision:

```text
GO cho triển khai nội bộ có kiểm soát với toàn bộ nhân viên tư vấn tại một trung tâm;
NOT YET cho mở rộng sang nhiều trung tâm hoặc nhiều quốc gia;
NO-GO với Agent tự chủ, tự gửi hoặc tự cam kết kết quả.
```

Phạm vi đưa vào hoạt động:

- Một trung tâm du học.
- Toàn bộ nhân viên tư vấn của trung tâm được đào tạo và sử dụng cùng workflow.
- Tập nguồn học bổng chính thức do trung tâm phê duyệt và có lịch kiểm tra cập nhật.
- Các quốc gia được kích hoạt theo danh sách trung tâm đã kiểm tra, không tự động mở toàn bộ Internet.
- Chỉ tạo shortlist sơ bộ; tư vấn viên bắt buộc kiểm nguồn và phê duyệt trước khi gửi.
- Trong 2 tuần đầu, ghi thời gian xử lý, lỗi phải sửa và phản hồi của từng tư vấn viên để đo baseline và hiệu quả.

Điều kiện vận hành đạt yêu cầu:

- Giảm ít nhất 50% thời gian trung bình tạo shortlist.
- Ít nhất 90% kết luận điều kiện được tư vấn viên xác nhận đúng.
- Ít nhất 90% đề xuất sơ bộ có nguồn chính thức và ít nhất 95% học bổng còn hạn.
- Không có hallucination nghiêm trọng.
- Tư vấn viên đánh giá mức hữu ích từ 4/5 và muốn tiếp tục sử dụng.

Exit / rollback:

- Kết quả không có nguồn hoặc nguồn mâu thuẫn thì không được đưa vào shortlist chính thức.
- Nếu độ chính xác dưới 90%, xuất hiện hallucination nghiêm trọng hoặc thời gian không giảm đủ 50%, dừng mở rộng AI.
- Khi rollback, giữ form hồ sơ chuẩn, checklist nguồn và Rule lọc điều kiện cứng; tư vấn viên quay lại đọc/đối chiếu thủ công.

Decision rationale:

- Problem, actor, workflow và bottleneck đã đủ rõ để kiểm thử.
- Metric định lượng và cách đo đã rõ; baseline được hiệu chỉnh bằng log trong 2 tuần vận hành đầu tiên.
- No-AI process fix và Rule là nền tảng, AI chỉ can thiệp tại bước ngôn ngữ khó chuẩn hóa.
- Toàn bộ nhân viên trong một trung tâm có thể dùng chung workflow vì boundary, trách nhiệm review và fallback đã được xác định.
- Agent tự chủ vẫn không phù hợp vì quyền truy cập, nguồn dữ liệu và hậu quả của việc tư vấn sai chưa cho phép bỏ human approval.
