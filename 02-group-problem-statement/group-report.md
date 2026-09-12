# 02 — Group Problem Statement (Bản nộp nhóm)

> Làm chung 1 bản, mỗi thành viên copy vào repo cá nhân. Đi theo Phase 3 → 6 trong `01-worksheet.md`. Nhóm chỉ chọn **candidate problem** ở Phase 3, viết Problem Statement sau khi validate + vẽ workflow.

## Thành viên nhóm

| STT | Họ và tên | Mã học viên | Vai trò trong nhóm (VD: facilitator, workflow, research, writer) |
|-----|-----------|-------------|---------------------------------------------------------------|
| 1   |           |             |                                                               |
| 2   |           |             |                                                               |
| 3   |           |             |                                                               |
| 4   |           |             |                                                               |

**Candidate problem nhóm chọn (1 câu):**

Sinh viên đại học phải tự theo dõi deadline học tập từ nhiều kênh rời rạc, khiến họ mất thời gian tổng hợp và có nguy cơ bỏ sót hoặc xử lý công việc sát hạn.

---

## Phase 3 — Group Convergence: từ 9-12 candidates về 1

### 3.1. Trình bày top 3 mỗi người (mỗi candidate 1-2 phút)

| # | Người đưa ra | Candidate problem | Người gặp vấn đề | Điểm nghẽn | Cảm nhận nhanh của nhóm |
|---|---|---|---|---|---|
| 1 | Nguyễn Thị Bảo Trang | Khó bàn giao task giữa người mạnh Finance và người mạnh Technology | Sinh viên Fintech năm 3 làm bài nhóm, đặc biệt các thành viên phụ trách Finance, Technology, dữ liệu và báo cáo | Ghép các phần và kiểm tra sự thống nhất; input, output, công thức, biến số hoặc tiêu chí hoàn thành chưa rõ | Workflow rõ, đúng đặc thù bài nhóm Fintech; cần kiểm tra nguyên nhân chính là task chưa rõ hay thiếu kiến thức |
| 2 | Nguyễn Thị Bảo Trang | Khó liên kết một khái niệm tài chính với cách công nghệ triển khai khái niệm đó | Sinh viên Fintech năm 3 làm bài tập hoặc thuyết trình liên ngành | Tự nối tài liệu Finance với tài liệu Technology để tạo ví dụ hoặc cách giải thích thống nhất | Đúng đặc thù Fintech và có thể đo thời gian chuẩn bị; cần làm rõ cách đo mức độ hiểu và chất lượng liên kết |
| 3 | Nguyễn Thị Bảo Trang | Không biết cách xác định và xử lý lỗi Python/SQL trong bài phân tích tài chính | Sinh viên Fintech năm 3 làm bài thực hành hoặc project phân tích dữ liệu tài chính | Tìm nguyên nhân và thử cách sửa khi lỗi có thể đến từ code, dữ liệu hoặc logic tính toán | Workflow lặp lại, dễ đo thời gian xử lý lỗi; cần kiểm chứng kết quả tài chính sau khi sửa |
| 4 | Cường|Agent chọn sai tool trong 170+ tool registry, phải trace log thủ công |Dev vận hành agent | Đọc reasoning trace + so khớp registry thủ công| |
| 5 |Cường |Debug latency spike trên pipeline giọng nói robot, đối chiếu log 4 lớp thủ công | Dev tối ưu pipeline|Đối chiếu timestamp qua VAD/ASR/TTS/ALSA | |
| 6 |Cường |Handoff task thiếu context |Người nhận task |Note bàn giao thiếu chuẩn | |
| 7 | Nguyễn Tất Đạt | Phát hiện requirement mơ hồ trước khi bắt đầu implementation | Engineer, PM, QA | Clarification/rework chỉ xuất hiện sau khi đã code hoặc chạy experiment |  |
| 8 | Nguyễn Tất Đạt | Tìm và lọc paper, trend, expert insight từ nhiều nguồn | AI Engineer, Research Engineer | Mất vài giờ/topic trước khi đọc sâu | |
| 9 | Nguyễn Thanh Giang | Kiểm tra và đồng bộ dữ liệu từ nhiều nguồn trước khi ghép thành dataset cuối cùng | Người xử lí dữ liệu | Phải kiểm tra nhiều file/bảng, đối chiếu ngày tháng, tên biến và đơn vị trước khi merge |
| 10 | Người đưa ra |Tìm kiếm và đọc nhiều bài báo để xác định phương pháp, biến đầu vào và kết quả liên quan đến đề tài | Người thực hiện nghiên cứu | Phải đọc từng bài, tìm thông tin cần thiết và ghi chú lại để so sánh |
|11 | Đặng Thế Vinh | Nhân viên mới thường hỏi lặp lại các câu hỏi nội bộ | Newbie/mentor/HR | Phải dành thời gian trả lời lại | 
|12| Đặng Thế Vinh | Quên deadline công việc, bài tập hoặc lịch kiểm tra | Học sinh/ Người đi làm| Phải dành thời gian tra cứu từ nhiều kênh thông tin|

### 3.2. Gom trùng / cluster (gom 9-12 ý thành 3-4 cụm)

| Cluster | Candidates included | Pattern chung | Ghi chú |
|---|---|---|---|
| A — Phối hợp công việc, yêu cầu và deadline | #1 Bàn giao Finance–Technology; #6 Handoff task thiếu context; #7 Phát hiện requirement mơ hồ trước implementation; #12 Quên deadline do thông tin nằm ở nhiều kênh | Thông tin cần để thực hiện công việc chưa được chuẩn hóa hoặc tập trung, khiến người nhận phải hỏi lại, phát hiện mơ hồ muộn hoặc bỏ sót mốc thời gian. | #1 có workflow chi tiết nhất; #12 có tập người dùng rộng hơn nhưng phải thu hẹp actor còn sinh viên đại học và pain còn deadline học tập đa kênh trước khi đưa vào shortlist. |
| B — Tìm, tổng hợp và sử dụng tri thức | #2 Kết nối Finance với Technology; #8 Tìm/lọc paper, trend, expert insight; #10 Tìm và đọc bài báo để xác định phương pháp, biến và kết quả; #11 Nhân viên mới hỏi lặp lại câu hỏi nội bộ | Người dùng phải tìm thông tin từ tài liệu hoặc từ người khác, rồi chọn, kết nối và diễn giải thông tin để hoàn thành công việc. | #8 và #10 gần như cùng một pattern research. #11 có thể xử lý một phần bằng FAQ/onboarding chuẩn trước khi cần AI. |
| C — Kiểm tra, debug và đồng bộ dữ liệu/kỹ thuật | #3 Xác định và xử lý lỗi Python/SQL; #5 Debug latency spike qua 4 lớp log; #9 Kiểm tra và đồng bộ dữ liệu đa nguồn trước khi merge | Cùng là workflow đối chiếu nhiều tín hiệu để tìm nguyên nhân sai lệch trước khi tạo output cuối. | #9 có workflow dữ liệu khá rõ; #3 và #5 cần boundary kiểm chứng rất chặt vì code chạy được chưa chắc kết quả đã đúng. |
| D — Chọn công cụ cho agent | #4 Agent chọn sai tool trong registry 170+ tools | Cần tìm đúng công cụ từ tập lựa chọn lớn và trace lại lý do chọn sai. | Pain kỹ thuật cụ thể nhưng nhóm có ít thông tin về registry, log và môi trường vận hành thực tế để validate trong lab. |

### 3.3. Shortlist (giữ 2-3 bài trả lời được 7 câu hỏi worksheet)

| Candidate | Vì sao vào shortlist (2-3 ý) | Rủi ro / điều chưa rõ |
|---|---|---|
| #12 — Theo dõi deadline học tập từ nhiều kênh | Thu hẹp actor còn sinh viên đại học và scope còn deadline trên LMS, email, nhóm chat và lịch học. Problem scan cá nhân đã có baseline sơ bộ: kiểm tra khoảng 4 kênh, mất khoảng 10 phút/ngày. Bài toán dễ khảo sát trong lớp và có thể đo thời gian tổng hợp, số deadline bỏ sót, số việc làm sát hạn. | Chưa có dữ liệu tại VinUni về tỷ lệ bỏ sót deadline và chưa biết pain chính là thông tin phân tán, thông báo quá nhiều hay thói quen lập kế hoạch. Cần tránh mở rộng thành “trợ lý quản lý cuộc sống”. |
| #1 — Khó bàn giao task giữa người mạnh Finance và Technology | Actor, workflow 6 bước và bottleneck ghép bài đều rõ; baseline sơ bộ là 30–60 phút, 3–5 lần hỏi lại và 1–2 lần sửa. Có thể thử template handoff trước khi đánh giá AI. | Khá đặc thù với nhóm Fintech và phụ thuộc cách phân chia năng lực trong từng nhóm. Cần xác nhận nguyên nhân là task thiếu cấu trúc hay thành viên thiếu kiến thức liên ngành. |
| #11 — Nhân viên mới hỏi lặp lại câu hỏi nội bộ | Pain onboarding dễ hiểu; có thể đo số câu hỏi lặp lại và thời gian mentor/HR trả lời. Có thể so sánh handbook/FAQ, search workflow và chatbot có kiểm soát. | Actor và tổ chức chưa cụ thể; chưa có số câu hỏi, thời gian hoặc kho tài liệu nội bộ thật. Nhóm khó validation nhanh nếu không tiếp cận đủ nhân viên mới và mentor. |

### 3.4. Score để đồng thuận (chấm 1-5, ép nói rõ vì sao cho 5 / cho 3)

| Candidate | Actor rõ | Workflow rõ | Pain có evidence | Impact đo được | Làm trong lab | So sánh R/W/A được | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| #12 — Theo dõi deadline học tập đa kênh | 5 | 5 | 4 | 5 | 5 | 5 | 5 | 34 |
| #1 — Bàn giao Finance–Technology | 5 | 5 | 4 | 5 | 5 | 5 | 4 | 33 |
| #11 — Câu hỏi nội bộ lặp lại khi onboarding | 4 | 3 | 3 | 4 | 5 | 5 | 4 | 28 |

**Cách đọc điểm:** #12 đạt điểm cao nhất vì actor đã được thu hẹp thành sinh viên đại học, workflow kiểm tra nhiều kênh có thể vẽ và mọi thành viên đều tiếp cận được người dùng để validation. Evidence chỉ là 4, không phải 5, vì baseline 4 kênh và 10 phút/ngày mới đến từ problem scan cá nhân; bằng chứng bên ngoài chưa đại diện cho sinh viên VinUni. #1 rất rõ nhưng phạm vi người gặp hẹp hơn; #11 dễ hiểu nhưng thiếu workflow và bằng chứng nội bộ cụ thể.

**Tín hiệu research hỗ trợ việc chọn #12:** Khảo sát Pathify 2025 với 1.010 sinh viên đại học Mỹ cho biết 47% từng bỏ lỡ một deadline quan trọng vì không biết hạn, thường trong bối cảnh phải điều hướng nhiều portal tách rời; 75% ưu tiên một điểm truy cập tập trung. Đây là khảo sát do nhà cung cấp giải pháp tài trợ nên chỉ dùng làm bằng chứng định hướng, không thay validation tại VinUni. Ngoài ra, hai thử nghiệm được công bố trên *IEEE Transactions on Learning Technologies* cho thấy thông báo chủ động trước hạn làm giảm assignment bị bỏ lỡ, chứng minh đây là pain có thể can thiệp và đo lường. Nguồn: [EDUCAUSE/Pathify Student Digital Experience Survey 2025](https://www.educause.edu/about/corporate-participation/member-press-releases/new-survey-finds-fragmented-digital-systems-are-eroding-student-success), [ERIC — Automated Educative Nudges to Reduce Missed Assignments in College](https://eric.ed.gov/?id=EJ1297780).

**Candidate nhóm chọn (1 bài duy nhất):**

```text
Sinh viên đại học phải tự kiểm tra deadline bài tập, quiz, thuyết trình và lịch họp từ LMS, email, nhóm chat và lịch học; thông tin phân tán khiến họ mất thời gian tổng hợp và có nguy cơ bỏ sót hoặc xử lý công việc sát hạn.
```

**Vì sao chọn (4-5 câu):**

```text
Nhóm chọn candidate này vì deadline phân tán là vấn đề mà nhiều sinh viên có thể trải nghiệm và nhóm dễ tiếp cận người dùng để khảo sát. Problem scan cá nhân đã ghi nhận workflow phải kiểm tra khoảng bốn kênh và tốn khoảng 10 phút mỗi ngày; research bên ngoài cũng cho thấy bỏ lỡ deadline do hệ thống số phân mảnh là một pain đáng kể. Bài toán có thể đo bằng thời gian tổng hợp lịch, số deadline phải nhập tay, số deadline bị bỏ sót và số đầu việc chỉ bắt đầu sát hạn. Scope được thu hẹp vào deadline học tập của sinh viên đại học, không bao gồm toàn bộ công việc và đời sống cá nhân. Nhóm vẫn phải khảo sát tại VinUni xem nguyên nhân chính là thông tin phân tán, thông báo quá tải hay thói quen quản lý thời gian trước khi chọn giải pháp.
```

**Vì sao KHÔNG chọn các candidate còn lại (mỗi bài 2-3 câu):**

```text
#1 — Bàn giao Finance–Technology: Candidate có workflow và baseline cụ thể, nhưng chỉ tác động mạnh đến một nhóm sinh viên Fintech có sự phân chia vai trò Finance–Technology. #12 được ưu tiên vì có tập người dùng rộng hơn và dễ validation với sinh viên trong lớp.

#2 — Kết nối khái niệm Finance với cách Technology triển khai: Candidate đúng bối cảnh Fintech và có workflow tìm–đọc–kết nối tài liệu, nhưng “hiểu đúng” và chất lượng liên kết hiện chưa có thước đo khách quan. Phạm vi người gặp cũng hẹp hơn bài toán deadline học tập.

#3 — Xác định và xử lý lỗi Python/SQL: Thời gian debug có thể đo, nhưng bài toán đang gộp lỗi cú pháp, dữ liệu và logic tài chính thành nhiều nguyên nhân khác nhau. Việc kiểm chứng kết quả sau khi sửa cũng cần test case và người hiểu domain sâu.

#4 — Agent chọn sai tool trong registry: Pain kỹ thuật rõ và có số lượng 170+ tools, nhưng cần quyền truy cập registry, reasoning trace và log thực tế để validate. Scope dễ chuyển thành bài toán vận hành agent chuyên sâu, khó hoàn thành chắc chắn trong lab.

#5 — Debug latency pipeline giọng nói: Workflow đối chiếu bốn lớp log khá cụ thể nhưng cần log thật và kiến thức về VAD, ASR, TTS, ALSA. Nhóm chưa có đủ evidence về tần suất và thời gian debug nên không chọn.

#6 — Handoff task thiếu context: Candidate gần như trùng pattern với #1 nhưng actor, bối cảnh, workflow và metric còn quá ngắn. Nếu tiếp tục nghiên cứu cluster handoff, nhóm sẽ dùng #1 làm phiên bản cụ thể hơn.

#7 — Requirement mơ hồ trước implementation: Actor và tác động rework rõ, nhưng notes chưa có baseline hoặc ví dụ requirement cụ thể. Scope cũng có thể mở rộng sang toàn bộ quy trình phát triển sản phẩm, nên nhóm chưa đưa vào shortlist cuối.

#8 — Tìm và lọc paper, trend, expert insight: Pain mất vài giờ mỗi topic là tín hiệu đáng chú ý nhưng workflow tìm, tiêu chí lọc và output mong muốn chưa cụ thể. Candidate cũng gần trùng với #10 và cần metric chất lượng nguồn.

#9 — Đồng bộ dữ liệu trước khi merge: Workflow và impact có thể đo, nhưng nhóm chưa ghi nhận dataset mẫu, schema chuẩn hoặc bối cảnh dữ liệu mà mọi người cùng hiểu sâu. Việc validation cũng khó mở rộng ra nhiều người bằng #12.

#10 — Đọc bài báo để xác định phương pháp, biến và kết quả: Workflow research có thể vẽ được nhưng chưa có baseline thời gian, số bài phải đọc hoặc tiêu chí thế nào là trích xuất đúng. Candidate gần trùng #8 nên nhóm không giữ cả hai trong shortlist.

#11 — Nhân viên mới hỏi lặp lại câu hỏi nội bộ: Pain dễ hiểu và có thể đo số câu hỏi hoặc thời gian mentor trả lời, nhưng chưa có tần suất, loại câu hỏi, nguồn tri thức nội bộ hay bối cảnh tổ chức cụ thể. Nhóm khó tiếp cận dữ liệu doanh nghiệp và cần thử FAQ/handbook trước khi giả định cần AI.
```

**Disagreement (nếu có — ai lo gì, chốt ra sao):**

```text
Ban đầu nhóm nghiêng về #1 vì workflow và baseline cụ thể, nhưng có lo ngại rằng bài toán quá đặc thù và khó chứng minh nhiều người gặp. Sau khi so lại các candidate và xem tín hiệu research, nhóm chuyển sang #12 nhưng thu hẹp actor còn sinh viên đại học và pain còn việc theo dõi deadline học tập đa kênh. Đây vẫn là quyết định tạm thời: nếu Phase 4 cho thấy sinh viên không thường bỏ sót deadline vì thông tin phân tán, nhóm sẽ hạ bài toán xuống một giải pháp Rule/process như lịch chung và checklist, hoặc quay lại candidate #1.
```

---

## Phase 4 — Quick Validation + Research

### 4.1. Quick validation (ít nhất 1 cách: interview 2-3 người hoặc survey 5-10 người)

| Nguồn | Số người / mẫu | Tín hiệu xác nhận (kèm quote nguyên văn) | Tín hiệu phản bác | Nhóm sửa problem thế nào |
|---|---:|---|---|---|
| Phỏng vấn mô phỏng — Sinh viên A | 1 (Nguyên - Zone C) | “Mình phải xem LMS, email và nhóm chat; tuần trước suýt quên một quiz vì thông báo bị trôi.” | Bạn này vẫn dùng Google Calendar nên chưa bỏ lỡ deadline hoàn toàn. | Tập trung vào bước gom deadline từ nhiều kênh, không chỉ gửi thêm thông báo. |
| Phỏng vấn mô phỏng — Sinh viên B | 1 (Nhóm Hắc Bạch Vô Thường - Zone B) | “Mỗi tối mình mất khoảng 10 phút kiểm tra ba hoặc bốn kênh để cập nhật việc ngày mai.” | Deadline trên LMS tương đối rõ; đôi khi nguyên nhân làm sát hạn là trì hoãn. | Tách pain thông tin phân tán khỏi pain quản lý thời gian cá nhân. |
| Phỏng vấn mô phỏng — Sinh viên C | 1 (Đình Long - Zone A) | “Lịch họp nhóm hay đổi trong chat nhưng lịch cá nhân không cập nhật, nên mình từng nhớ nhầm giờ.” | Một lịch chung của nhóm có thể đã đủ, chưa chắc cần AI. | So sánh lịch/checklist đơn giản với workflow có AI trước khi chọn giải pháp. |

> **Lưu ý:** Ba câu trả lời trên là dữ liệu mô phỏng để chuẩn bị phỏng vấn, không phải quote thật. Trước khi nộp, nhóm phải hỏi 2–3 sinh viên và thay bằng câu trả lời thực tế.

**Insight sau validation (1-2 câu — pain thật nằm ở đâu):**

```text
Giả thuyết ban đầu là pain nằm ở bước sinh viên phải tự gom và đối chiếu deadline từ nhiều kênh. Tuy nhiên, nhóm cần phân biệt ba nguyên nhân: thông tin phân tán, lịch thay đổi không đồng bộ và trì hoãn cá nhân.
```

**Ba câu hỏi phỏng vấn thật cần hỏi:**

1. Tuần gần nhất bạn phải kiểm tra những kênh nào để biết deadline?
2. Lần gần nhất bạn bỏ sót hoặc phát hiện deadline muộn là khi nào, vì sao?
3. Một lịch tập trung có đủ giải quyết vấn đề không, hay bạn cần hỗ trợ gì khác?

Bằng chứng đính kèm (nếu có): `02-group-problem-statement-survey.png`, `...-interview-notes.md`

### 4.2. Research giải pháp đã có (ít nhất 2-3 tools/patterns + 1-2 link kiểm được)

| Nguồn / tool / case | Link | Họ giải quyết bước nào? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| Canvas Calendar | [Canvas Guide](https://community.canvaslms.com/html/assets/Canvas_Basics_Guide.pdf) | Gom assignment/event trong LMS và xuất lịch sang Google/Outlook. | Tự đồng bộ deadline có cấu trúc, không cần AI. | Không lấy được deadline chỉ xuất hiện trong email hoặc nhóm chat. | Dùng Rule/calendar feed cho nguồn có cấu trúc. |
| Google Tasks/Calendar | [Google Calendar Help](https://support.google.com/calendar/answer/9901136) | Lưu task, deadline và gửi nhắc việc. | Dễ dùng và phù hợp làm pilot. | Vẫn phải nhập tay; nhập sai thì lịch cũng sai. | Đây là phương án non-AI cần thử trước. |
| Todoist | [Calendar integration](https://www.todoist.com/help/todoist/integrations/use-the-calendar-integration-rCqwLCt3G) | Hiển thị task và lịch trong một nơi, hỗ trợ Today/Upcoming. | Hữu ích cho planning và time-blocking. | Không tự xác minh deadline từ email/chat; thêm app có thể tăng phân mảnh. | Khoảng trống nằm ở thu thập và xác minh deadline. |
| Automated Educative Nudges | [Nghiên cứu IEEE/ERIC](https://eric.ed.gov/?id=EJ1297780) | Gửi nhắc việc khi assignment sắp đến hạn nhưng chưa nộp. | Hai pilot ghi nhận giảm bài bị bỏ lỡ. | Phụ thuộc dữ liệu LMS và có thể tạo quá nhiều thông báo. | Chỉ nhắc đúng lúc, có điều kiện và đo mức độ khó chịu. |

**Research takeaway (2-3 câu — nên build gì / không build gì):**

```text
Nhóm nên thử một lịch tập trung và quy tắc nhập deadline trước. Chỉ dùng AI để trích xuất deadline từ email/chat không có cấu trúc; sinh viên phải xác nhận nội dung và thời hạn trước khi lưu. Chưa cần Agent tự quản lý toàn bộ lịch.
```

> Lưu ý: không dùng số liệu AI đưa nếu không verify được link chính thức. Ghi rõ giả định chưa chắc.

---

## Phase 5 — Workflow + Problem Statement

### 5.1. Current workflow bản nhóm

Dán workflow hoặc link file: `02-group-problem-statement-workflow.png/pdf/md`

```text
[1 ...: __' - ai làm] → [2 ...: __'] → [3 ...: __'] → [4 ... bottleneck: __'] → ...
```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú (handoff? bottleneck?) |
|---|---|---|---|---|---|
| 1 | | | | | |
| 2 | | | | | |
| 3 | | | | | |
| 4 | | | | | |
| 5 | | | | | |
| 6 | | | | | |
| 7 | | | | | |

**Bottleneck chính (2-3 câu):**

```text

```

### 5.2. Future workflow bản nhóm

Phải nhìn ra 5 thứ: bước nào máy (Rule), bước nào AI, bước nào người, boundary ở đâu, fallback khi AI sai.

```text
[1 ...: __' - máy] → [2 AI ...: __'] → [3 ... review: __' - boundary] → [4 ... gửi]

Fallback: ...
```

**Before/after impact:**

| Metric | Trước | Sau kỳ vọng | Cách đo |
|---|---:|---:|---|
| Tổng thời gian | | | |
| Số bước | | | |
| Số bước thủ công | | | |
| Bottleneck chính | | | |
| Risk mới | | | |

### 5.3. Problem Statement v0 (mỗi field 2-3 câu)

| Field | Nội dung |
|---|---|
| **Actor** | |
| **Workflow** | |
| **Bottleneck** | |
| **Impact** | |
| **Success Metric** | |
| **Boundary** | |

**Câu hỏi AI phản biện v0 (nếu có):**
- Field nào mơ hồ:
- Tôi sửa gì:

---

## Phase 6 — Rule / Workflow / Agent + Decision

### 6.0. Ma trận độ phù hợp (suy nghĩ nhanh, không thay quyết định cuối)

- Độ mơ hồ: [ ] Thấp (có đúng/sai rõ) / [ ] Cao (nhiều cách trả lời vẫn OK) — Vì sao:
- Độ phức tạp: [ ] Thấp (1-2 bước) / [ ] Cao (3+ bước/nguồn, phụ thuộc nhau) — Vì sao:

**Bài toán nhóm nằm ở ô nào:**

```text

```

**Vì sao (2-3 câu):**

```text

```

### 6.1. So sánh Rule / Workflow / Agent (so trên cùng 1 bài)

| Mức | Phương án cho bài toán nhóm | Khi nào đủ | Rủi ro | Chọn? (Dùng cho bước nào?) |
|---|---|---|---|---|
| **Rule** | | | | |
| **Workflow** | | | | |
| **Agent** | | | | |

**5 câu hỏi chốt (trả lời câu đầy đủ):**
1. Rule có giải được 70-80% case không?
2. Các bước có đi thẳng một đường không hay phải rẽ nhánh?
3. Có thật sự cần Agent tự lập kế hoạch + gọi tool không?
4. Nếu AI sai, ai phát hiện đầu tiên và sửa trong bao lâu?
5. Có hạ được từ Agent → Workflow → Rule không?

**Mức chọn:**

```text
[Rule / Workflow / Agent]
```

**Vì sao chọn (3-4 câu):**

```text

```

**Vì sao không chọn mức đơn giản hơn (2-3 câu):**

```text

```

### 6.2. Problem Statement v1 (v0 sửa chặt hơn + 3 field cuối)

| Field | Nội dung |
|---|---|
| **Actor** | |
| **Workflow** | |
| **Bottleneck** | |
| **Impact** | |
| **Success Metric** | |
| **Boundary** (làm / không làm) | |
| **AI intervention point** (can thiệp sau bước nào, trước bước nào) | |
| **Mức chọn** (Rule / Workflow / Agent + 1 câu vì sao) | |
| **Rủi ro & người thật kiểm tra** (rủi ro lớn nhất + ai kiểm tra bằng cách nào) | |

### 6.3. Final decision

| Câu hỏi | Yes / Not Yet / No | Ghi chú (câu đầy đủ) |
|---|---|---|
| Actor + workflow rõ chưa? | | |
| Baseline + metric đo được chưa? | | |
| Data/input đủ dùng chưa? | | |
| AI sai, hậu quả chấp nhận được không? | | |
| Có người review/owner không? | | |
| Có cách non-AI đơn giản hơn không? | | |

**Decision:**

```text
[Go / Not Yet / No-Go]
```

**Lý do (3-4 câu dựa trên bằng chứng):**

```text

```

**Nếu Go — pilot nhỏ nhất (data nào, chạy tay ra sao, đo 3 số nào):**

```text

```

**Nếu Not Yet — cần validate gì trước:**

```text

```

**Nếu No-Go — làm gì thay AI:**

```text

```

**Exit / rollback (khi nào dừng AI, quay về cách cũ):**

```text

```

---

### Self-check nộp phần 02 (nhóm)
- [ ] Có nhật ký hội tụ 9-12 → 1 (cluster + shortlist + score)
- [ ] Có validation (quote thật) + research (link kiểm được)
- [ ] Có workflow trước/sau đủ thời gian, handoff, bottleneck, boundary, fallback
- [ ] Có PS v0 → v1, metric có trước/sau + cách đo, boundary có làm/không làm
- [ ] Có so sánh Rule/Workflow/Agent + Decision Go/Not Yet/No-Go có lý do
