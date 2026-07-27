# 01 — Individual Problem Scan

## Scan rộng

Mình scan 8 problems dựa trên trải nghiệm học tập và làm lab, vượt mức tối thiểu 5.

| # | Lăng kính | Problem quan sát được | Ai chịu ảnh hưởng? | Dấu hiệu thật |
|---|---|---|---|---|
| 1 | Lặp lại | Mỗi tuần phải tổng hợp tiến độ lab từ Discord, GitHub, Google Docs để viết update cho giảng viên | Sinh viên, giảng viên | Mất khoảng 30-45 phút/tuần |
| 2 | Tốn thời gian | Tìm lại quyết định, comment hoặc câu trả lời cũ trong Discord/Docs trước khi làm tiếp | Sinh viên | Thường phải mở nhiều thread và đọc lại 2-3 lần |
| 3 | Tốn thời gian | Đọc tài liệu dài trước deadline rồi tự tóm tắt thành note ngắn để nhớ nội dung | Sinh viên | Mất 20-30 phút mỗi lần đọc |
| 4 | AI có thể tốt hơn | Tóm tắt nhiều nguồn rời rạc (slide, docs, issue) thành một bản ghi ngắn, dễ hiểu | Sinh viên | Việc này cần hiểu ngữ cảnh và viết lại câu chữ |
| 5 | Pain từ người khác | Bạn cùng nhóm hỏi lại task vì spec chưa rõ hoặc không có note chuẩn | Sinh viên, nhóm | Thường phải giải thích lại 2-3 lần/task |
| 6 | Lặp lại | Viết note sau buổi họp nhóm hoặc review bằng cùng một format | Sinh viên | Mỗi buổi mất 10-15 phút để ghi lại action items |
| 7 | AI có thể tốt hơn | Phân loại ưu tiên nhiệm vụ khi deadline dồn và task nhiều | Sinh viên | Hay bị lẫn giữa việc quan trọng và việc khẩn cấp |
| 8 | Pain từ người khác | Giảng viên hoặc trưởng nhóm hỏi tiến độ nhưng chưa có bản tóm tắt sẵn | Sinh viên, giảng viên | Bị trễ khi cần update nhanh trước buổi gặp |

## Top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---|---|---|---|
| 1 | Tổng hợp tiến độ lab/weekly update từ nhiều nguồn | Workflow rõ, có bottleneck thật, có thể đo thời gian | Cần làm rõ metric và boundary của AI |
| 2 | Tìm lại quyết định cũ trong Discord/Docs | Pain rất thực tế, AI có thể hỗ trợ tốt | Scope có thể nhỏ hơn nếu chỉ tập trung vào tìm kiếm nội dung |
| 3 | Tóm tắt tài liệu dài trước deadline | Có bottleneck rõ, AI hỗ trợ tốt ở bước đọc và tóm tắt | Metric chất lượng cần đo cẩn thận |

## Problem Card #1 — Tổng hợp tiến độ lab / weekly update

**Problem 1 câu:**  
Mỗi tuần sinh viên mất khá nhiều thời gian để tổng hợp tiến độ từ Discord, GitHub và Google Docs thành một bản update ngắn, dễ hiểu cho giảng viên hoặc nhóm.

**Actor:**  
Sinh viên làm lab và cần gửi update tiến độ cho giảng viên hoặc nhóm.

**Thời điểm / bối cảnh:**  
Cuối tuần hoặc trước buổi họp nhóm, khi cần tổng hợp nhiều nguồn thông tin khác nhau.

**Current workflow:**
1. Mở Discord/Slack để xem các comment và quyết định đã trao đổi.
2. Xem GitHub để kiểm tra task đã hoàn thành hoặc đang làm.
3. Đọc Google Docs/Markdown note để xem ghi chú và tài liệu liên quan.
4. Tự tổng hợp thành một bản update ngắn.
5. Chỉnh sửa format và gửi cho người liên quan.

**Bottleneck:**  
Bước tổng hợp và viết bản update mất nhiều thời gian vì phải chuyển từ nhiều nguồn rời rạc thành một câu chuyện thống nhất.

**Impact:**  
Mất khoảng 30-45 phút/tuần; đôi khi update bị trễ vì phải dành thời gian suy nghĩ cách viết sao cho rõ ràng.

**Success metric:**  
Giảm thời gian tổng hợp từ khoảng 40 phút xuống dưới 15 phút; không làm tăng số câu hỏi phải sửa lại từ người nhận.

**Non-AI alternative:**  
Template update + checklist + bảng tiến độ có thể giảm phần format, nhưng chưa giải quyết tốt phần viết nội dung tổng hợp.

**AI hypothesis:**  
AI có thể giúp sắp xếp dữ liệu từ nhiều nguồn và draft một bản update ban đầu; người thật vẫn chỉnh sửa và gửi.

**Quick gut:**  
[ ] No AI / process fix  
[ ] Rule  
[x] Workflow  
[ ] Agent  
[ ] Chưa biết

### Draft current workflow

```text
CURRENT STATE — 40 phút

[1 Xem Discord/Slack: 10']
→ [2 Xem GitHub: 10']
→ [3 Đọc Docs/Note: 10']
→ [4 Tự tổng hợp nội dung: 7']
→ [5 Chỉnh sửa và gửi: 3']
```

### Draft future workflow

```text
FUTURE STATE — 15 phút

[1 Auto-collect dữ liệu từ các nguồn: 3']
→ [2 AI tóm tắt và cấu trúc thông tin: 2']
→ [3 AI draft bản update: 2']
→ [4 Sinh viên review + chỉnh sửa: 7']
→ [5 Gửi: 1']
```

Fallback: Nếu AI draft chưa tốt, sinh viên tự viết lại phần cần thiết.

## Problem Card #2 — Tìm lại quyết định cũ trong Discord/Docs

**Problem 1 câu:**  
Mỗi khi cần làm tiếp một task, sinh viên thường mất thời gian tìm lại quyết định, comment hoặc câu trả lời cũ trong Discord/Docs vì thông tin bị phân tán.

**Actor:**  
Sinh viên đang làm lab hoặc dự án nhóm.

**Thời điểm / bối cảnh:**  
Khi bắt đầu một task mới, hoặc khi cần kiểm tra lại hướng làm trước đó.

**Current workflow:**
1. Mở Discord/Docs/Google Drive để tìm thread hoặc ghi chú cũ.
2. Đọc nhiều message hoặc đoạn văn để xác định quyết định trước đó.
3. Tự suy ra cách làm tiếp phù hợp.
4. Tiếp tục task mới.

**Bottleneck:**  
Việc tìm kiếm và đọc lại nội dung cũ mất thời gian vì thông tin nằm rải rác ở nhiều nơi.

**Impact:**  
Mất khoảng 10-15 phút mỗi lần; làm chậm tiến độ và dễ bỏ sót context.

**Success metric:**  
Giảm thời gian tìm lại thông tin xuống dưới 5 phút/lần; ít cần hỏi lại người khác.

**Non-AI alternative:**  
Tạo note chuẩn hoặc hệ thống lưu quyết định ở một nơi tập trung, nhưng vẫn cần người chủ động tra cứu.

**AI hypothesis:**  
AI có thể hỗ trợ tìm kiếm ngữ cảnh và tóm tắt quyết định cũ nhanh hơn, giúp sinh viên đi tiếp mà không phải đọc lại toàn bộ thread.

**Quick gut:**  
[ ] No AI / process fix  
[ ] Rule  
[x] Workflow  
[ ] Agent  
[ ] Chưa biết

### Draft current workflow

```text
CURRENT STATE — 15 phút

[1 Tìm thread/ghi chú cũ: 8']
→ [2 Đọc lại nhiều nội dung: 5']
→ [3 Suy ra quyết định tiếp theo: 2']
```

### Draft future workflow

```text
FUTURE STATE — 5 phút

[1 AI tìm và tóm tắt thông tin liên quan: 2']
→ [2 Sinh viên xác nhận context: 2']
→ [3 Tiếp tục task: 1']
```

Fallback: Nếu AI không tìm đúng, sinh viên vẫn có thể mở lại tài liệu gốc.

## Problem Card #3 — Tóm tắt tài liệu dài trước deadline

**Problem 1 câu:**  
Trước deadline, sinh viên thường phải đọc tài liệu dài rồi tự tóm tắt thành note ngắn để hiểu nội dung và chuẩn bị làm bài.

**Actor:**  
Sinh viên học tập và cần nắm nhanh nội dung tài liệu.

**Thời điểm / bối cảnh:**  
Trước buổi học, trước deadline nộp bài, hoặc khi cần ôn tập từ nhiều tài liệu.

**Current workflow:**
1. Đọc tài liệu dài từ đầu đến cuối.
2. Ghi chú các ý chính và từ khóa quan trọng.
3. Tự viết lại thành note ngắn để dễ nhớ.
4. Dùng note đó khi làm bài hoặc ôn tập.

**Bottleneck:**  
Việc đọc và tóm tắt mất nhiều thời gian, nhất là khi tài liệu dài và có nhiều chi tiết phụ.

**Impact:**  
Mất khoảng 20-30 phút mỗi lần; làm giảm hiệu quả học tập khi phải dành nhiều thời gian cho việc đọc lại.

**Success metric:**  
Giảm thời gian đọc/tóm tắt xuống dưới 10 phút/lần; note vẫn đủ rõ để dùng cho việc học tiếp.

**Non-AI alternative:**  
Tạo template note, dùng sơ đồ tư duy hoặc highlight chữ quan trọng, nhưng vẫn cần người tự tóm lại.

**AI hypothesis:**  
AI có thể tóm tắt tài liệu dài thành note ngắn và sắp xếp ý chính, giúp sinh viên tiết kiệm thời gian đọc và hiểu nhanh hơn.

**Quick gut:**  
[ ] No AI / process fix  
[ ] Rule  
[x] Workflow  
[ ] Agent  
[ ] Chưa biết

### Draft current workflow

```text
CURRENT STATE — 25 phút

[1 Đọc tài liệu dài: 15']
→ [2 Ghi chú ý chính: 7']
→ [3 Viết lại thành note ngắn: 3']
```

### Draft future workflow

```text
FUTURE STATE — 10 phút

[1 AI tóm tắt tài liệu: 2']
→ [2 Sinh viên chỉnh sửa và chọn ý chính: 6']
→ [3 Dùng note để học tiếp: 2']
```

Fallback: Nếu tóm tắt thiếu chính xác, sinh viên vẫn đọc lại phần cần thiết.

## Card mình muốn pitch nhất

**Card:** Tổng hợp tiến độ lab / weekly update

**Vì sao:**
- Có workflow rõ và lặp lại mỗi tuần.
- Bottleneck nằm ở bước viết và tổng hợp thay vì bước thu thập dữ liệu.
- Có thể đo bằng thời gian và mức độ cần chỉnh sửa.

**Câu hỏi mình muốn nhóm challenge:**
- Metric có nên là thời gian hay nên bao gồm cả chất lượng của update không?
- AI có nên chỉ hỗ trợ bước draft, hay còn có thể làm thêm bước thu thập dữ liệu?
