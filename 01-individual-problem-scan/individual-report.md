# 01 — Individual Problem Scan

> Điền theo Phase 1 + Phase 2 trong `01-worksheet.md`. Tự scan trước, dùng AI sau để phản biện. Không copy ví dụ Weekly Report.

## Thông tin cá nhân

- Họ và tên:
- Mã học viên:
- Vai trò / bối cảnh (VD: sinh viên năm X, intern PM, ...):
- Công việc hằng tuần (3-5 gạch đầu dòng để soi problem):

---

## Phase 1 — Scan 5+ problems (tối thiểu 5, khuyến khích 8-10)

**Cách điền:** mỗi dòng = việc gì + ai chịu + đo bằng gì. Cột `Dấu hiệu thật` bắt buộc có số: mất bao lâu (bấm giờ mấy lần), mấy lần/tuần, bao nhiêu người gặp, log/ticket/quote nào.

| # | Lăng kính (Lặp lại / Tốn thời gian / AI có thể tốt hơn / Pain từ người khác) | Problem quan sát được | Ai chịu ảnh hưởng? | Dấu hiệu thật (số + bằng chứng) |
|---|---|---|---|---|
| 1 | Lặp lại| Tìm kiếm và đọc nhiều bài báo để xác định phương pháp, biến đầu vào và kết quả có liên quan đến đề tài| Người thực hiện nghiên cứu| Mỗi bài tốn 5-15p để đọc và ghi chú các điểm quan tâm của bài báo|
| 2 | Lặp lại| Đọc và ghi chú ý tưởng từ các báo khoa học| Người thực hiện nghiên cứu| Tốn 30-45 phút/bài báo trong việc hình thành ý tưởng|
| 3 | Tốn thời gian| Làm sạch và xử lý dữ liệu thiếu| Người xử lí dữ liệu| Tùy thuộc vào đề tài có thể 1 - 3 tuần|
| 4 | AI có thể tốt hơn| Phát hiện lỗi/ bất thường trong dữ liệu| Người xử lí dữ liệu| 1 ngày làm việc|
| 5 | Tốn thời gian| Kiểm tra và đồng bộ dữ liệu từ nhiều nguồn trước khi ghép thành dataset cuối cùng| Người xử lí dữ liệu| Có thể phải kiểm tra nhiều file/bảng dữ liệu, đối chiếu ngày tháng, tên biến và đơn vị trước khi merge|
| 6 | Pain từ người khác| Khó giải thích vì sao phải giữ hoặc loại bỏ một số dữ liệu/feature trong quá trình nghiên cứu| Người thực hiện, giảng viên| Thường phải giải thích lại nhiều lần về nguồn dữ liệu, cách xử lý missing, feature selection và lý do lựa chọn phương pháp|
| 7 | AI có thể tốt hơn| Xác định feature nào có khả năng hữu ích cho mô hình và feature nào dư thừa| Người nghiên cứu| Dataset có thể có hàng chục biến và nhiều biến trễ/rolling; phải kết hợp correlation, VIF và kiến thức chuyên ngành để sàng lọc|
| 8 | Pain từ người khác| Việc kiểm tra và tái hiện lại pipeline xử lý dữ liệu khó khi các bước preprocessing nằm rải rác trong nhiều đoạn code| Người nghiên cứu| Khi cần kiểm tra lại kết quả phải lần lượt rà soát nhiều bước preprocessing/modeling, dễ mất thêm thời gian để xác định dữ liệu được biến đổi ở đâu|

> Gợi ý tự soi: tuần trước mất nhiều thời gian nhất vào việc gì? Việc gì hay trì hoãn? Người khác hay hỏi lại câu gì? Workflow nào ai cũng biết là chậm?

**AI đã dùng ở Phase 1 (nếu có):**
- Prompt đã hỏi:
- Ý dùng được:
- Ý bỏ vì không phải pain thật:

**Self-check Phase 1:**
- [x] Đủ 5+ dòng, mỗi dòng có actor + số đo cụ thể
- [x] Dùng ít nhất 3/4 lăng kính
- [x] Không có dòng chung chung kiểu "mất nhiều thời gian"

---

## Phase 2 — Top 3 Problem Cards

### 2.1. Chọn top 3

Giữ bài nào: actor cụ thể, workflow vẽ được 3-7 bước, bottleneck ở 1 bước, impact đo được. Loại bài quá rộng.

| Rank | Problem (copy từ bảng scan) | Vì sao chọn (2-3 ý) | Điều còn chưa chắc |
|---|---|---|---|
| 1 | Phát hiện lỗi/ bất thường trong dữ liệu| Có actor rõ là người xử lí dữ liệu; workflow có thể mô tả từ kiểm tra dữ liệu -> phát hiện giá trị nghi ngờ -> đối chiếu nguồn -> quyết định giữ/xóa/sửa. AI có tiềm năng hỗ trợ tốt ở bước phát hiện bất thường.| Chưa đo chính xác số lượng lỗi/bất thường thực tế và tỷ lệ phát hiện bằng phương pháp thủ công. Cần xác minh AI có giảm đáng kể thời gian hay không|
| 2 | Kiểm tra và đồng bộ dữ liệu từ nhiều nguồn trước khi ghép thành dataset cuối cùng| Là công việc thường gặp trong xử lí dữ liệu; bottleneck tập trung ở việc đối chiếu ngày tháng, tên biến và đơn vị trước khi merge. Có thể đo thời gian xử lí và số lần phải kiểm tra/sửa dữ liệu.| Chưa có số liệu cụ thể về số file/bảng và thời gian trung bình cho mỗi lần đồng bộ. Mức độ lặp lại còn phụ thuộc từng đề tài|
| 3 | Tìm kiếm và đọc nhiều bài báo để xác định phương pháp, biến đầu vào và kết quả có liên quan đến đề tài| Actor cụ thể là người nghiên cứu; workflow dễ vẽ: tìm kiếm -> mở bài -> đọc -> tìm thông tin -> ghi chú -> so sánh. Đã có dấu hiệu định lượng là 5–15 phút/bài.| Chưa biết chính xác trung bình phải đọc bao nhiêu bài cho một đề tài và bao nhiêu thời gian bị mất cho việc tìm kiếm thay vì đọc|

### 2.2. Problem Cards chi tiết (lặp lại cho cả 3 cards)

---

#### Problem Card #1 — Phát hiện lỗi/ bất thường trong dữ liệu

```text
Problem 1 câu: Người xử lí dữ liệu mất nhiều thời gian để phát hiện và xác minh các giá trị bất thường trước khi đưa dữ liệu vào mô hình ML/DL.


Actor: Người xử lí dữ liệu / người thực hiện nghiên cứu

Thời điểm / bối cảnh: Sau khi thu thập và hợp nhất dữ liệu, trước bước xây dựng dataset đầu vào và huấn luyện mô hình ML/DL.

Current workflow 3-7 bước:
1. Kiểm tra dataset và xác định các biến cần kiểm tra.
2. Kiểm tra phân phối, min/max và các giá trị nghi ngờ của từng biến.
3. Xác định các giá trị có dấu hiệu bất thường.
4. Đối chiếu giá trị bất thường với dữ liệu gốc hoặc nguồn dữ liệu liên quan.
5. Xác định nguyên nhân: lỗi nhập liệu, lỗi đo đạc hay giá trị thực tế.
6. Quyết định giữ nguyên, loại bỏ hoặc xử lý giá trị bất thường.
7. Kiểm tra lại dataset sau khi xử lý.

Bottleneck: Bước 3-5 — phát hiện giá trị nghi ngờ và đối chiếu để xác định đó là lỗi thực sự hay một hiện tượng bất thường nhưng có ý nghĩa.


Impact: Quy trình thủ công mất khoảng 1 ngày làm việc khi phải kiểm tra dataset lớn; đồng thời có nguy cơ bỏ sót lỗi hoặc loại bỏ nhầm một giá trị bất thường nhưng có ý nghĩa khoa học.


Success metric: Giảm thời gian kiểm tra dữ liệu bất thường từ khoảng 1 ngày xuống còn dưới 2 giờ, đồng thời không làm tăng số trường hợp bất thường bị bỏ sót hoặc xử lý sai.


Non-AI alternative: Sử dụng các rule thống kê như IQR, Z-score, ngưỡng min/max hoặc biểu đồ boxplot để tự động đánh dấu các giá trị nghi ngờ.


AI hypothesis: AI/ML có thể học hoặc kết hợp nhiều đặc trưng của dữ liệu để tự động phát hiện và ưu tiên các giá trị bất thường, sau đó cung cấp danh sách các điểm cần người xử lí kiểm tra thay vì yêu cầu kiểm tra toàn bộ dataset.


Quick gut:
[ ] No AI / process fix
[ ] Rule
[ ] Workflow
[ ] Agent
[x] Chưa biết
```

**Draft workflow Card #1** (ASCII / Mermaid / ảnh đính kèm):

```text
CURRENT STATE — ~1 ngày

[1 Kiểm tra dataset: 30']
        ↓
[2 Kiểm tra phân phối/min-max: 60']
        ↓
[3 Phát hiện giá trị nghi ngờ: 120']
        ↓
[4 Đối chiếu dữ liệu gốc: 120']  <-- BOTTLENECK
        ↓
[5 Quyết định giữ/xóa/sửa: 60']
        ↓
[6 Kiểm tra lại dataset: 30']

FUTURE STATE — ~2 giờ

[1 Đưa dataset vào hệ thống: 10']
        ↓
[2 AI phát hiện + xếp hạng giá trị nghi ngờ: 30']
        ↓
[3 Human review: đối chiếu nguồn + quyết định: 60']  <-- HUMAN BOUNDARY
        ↓
[4 Xuất dataset đã xác nhận: 20']

Fallback:
Nếu AI đánh dấu sai hoặc không chắc chắn, hệ thống không tự động
xóa/sửa dữ liệu mà chuyển giá trị đó cho người xử lí kiểm tra thủ công.
```

File đính kèm (nếu vẽ riêng): `01-individual-problem-scan-workflow-card-1.png`

---

#### Problem Card #2 — Kiểm tra và đồng bộ dữ liệu từ nhiều nguồn

```text
Problem 1 câu: Người xử lí dữ liệu mất thời gian kiểm tra và đồng bộ dữ liệu từ nhiều nguồn trước khi có thể ghép chúng thành một dataset thống nhất

Actor: Người xử lí dữ liệu / người thực hiện nghiên cứu

Thời điểm / bối cảnh: Sau khi thu thập dữ liệu từ nhiều nguồn và trước bước merge thành dataset cuối cùng để phân tích hoặc đưa vào mô hình ML/DL

Current workflow 3-7 bước:

1. Thu thập các file/bảng dữ liệu từ các nguồn khác nhau.
2. Kiểm tra cấu trúc, tên cột và định dạng của từng nguồn.
3. Đối chiếu ngày tháng/thời gian giữa các nguồn.
4. Kiểm tra và quy đổi đơn vị đo nếu các nguồn sử dụng đơn vị khác nhau.
5. Chuẩn hóa tên biến và định dạng dữ liệu.
6. Xử lý các trường hợp không khớp hoặc thiếu dữ liệu.
7. Merge các nguồn thành dataset cuối cùng và kiểm tra lại.

Bottleneck: Bước 3-6 — đối chiếu và xử lý các điểm không đồng nhất giữa các nguồn trước khi merge

Impact: Người xử lí phải thực hiện nhiều bước kiểm tra thủ công trước khi có thể ghép dữ liệu. Nếu không phát hiện sai lệch về ngày tháng, tên biến hoặc đơn vị, dataset sau khi merge có thể bị sai và ảnh hưởng đến các bước phân tích hoặc huấn luyện mô hình

Success metric: Giảm thời gian kiểm tra và chuẩn hóa dữ liệu trước khi merge; giảm số lần phải sửa lại dữ liệu sau khi merge; không phát sinh lỗi về ngày tháng, tên biến hoặc đơn vị trong dataset cuối cùng

Non-AI alternative: Xây dựng template/schema chuẩn, quy tắc đặt tên biến, bảng mapping giữa các nguồn và các rule tự động kiểm tra định dạng, ngày tháng và đơn vị trước khi merge

AI hypothesis: AI có thể tự động phân tích schema của các nguồn dữ liệu, đề xuất mapping giữa các cột tương ứng, phát hiện sự khác biệt về định dạng/đơn vị và cảnh báo các trường hợp không chắc chắn trước khi thực hiện merge

Quick gut:
[ ] No AI / process fix
[x] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #2:**

```text
CURRENT STATE — thời gian cần đo

[1 Thu thập dữ liệu]
        ↓
[2 Kiểm tra cấu trúc + tên cột]
        ↓
[3 Đối chiếu ngày tháng]
        ↓
[4 Kiểm tra đơn vị + định dạng]  <-- BOTTLENECK
        ↓
[5 Chuẩn hóa + xử lý không khớp]
        ↓
[6 Merge dataset]
        ↓
[7 Kiểm tra lại kết quả]

FUTURE STATE — thời gian cần đo

[1 Upload/đưa các nguồn dữ liệu vào hệ thống]
        ↓
[2 AI kiểm tra schema + đề xuất mapping]
        ↓
[3 AI kiểm tra ngày tháng + đơn vị + định dạng]
        ↓
[4 Human review các trường hợp không chắc chắn]  <-- HUMAN BOUNDARY
        ↓
[5 Merge + validation]

Fallback:
Nếu AI mapping sai hoặc không xác định được cột tương ứng,
hệ thống không tự động merge mà đánh dấu trường hợp đó để
người xử lí kiểm tra và xác nhận thủ công.
```

File đính kèm: `01-individual-problem-scan-workflow-card-2.png`

---

#### Problem Card #3 — Tìm kiếm và đọc bài báo để xác định thông tin liên quan

```text
Problem 1 câu: Người nghiên cứu mất thời gian tìm kiếm và đọc nhiều bài báo để xác định phương pháp, biến đầu vào và kết quả có liên quan đến đề tài

Actor: Người thực hiện nghiên cứu

Thời điểm / bối cảnh: Trong giai đoạn tổng quan tài liệu và xây dựng phương pháp nghiên cứu, khi cần tìm các nghiên cứu liên quan để lựa chọn phương pháp và biến đầu vào

Current workflow 3-7 bước:

1. Xác định từ khóa và tìm kiếm các bài báo liên quan.
2. Mở và xem nhanh các bài báo có khả năng phù hợp.
3. Đọc abstract và các phần liên quan để đánh giá mức độ phù hợp.
4. Tìm thông tin cụ thể về phương pháp, biến đầu vào và kết quả.
5. Ghi chú các thông tin quan trọng của từng bài.
6. So sánh thông tin giữa các bài báo để lựa chọn hướng phù hợp.

Bottleneck: Bước 3-5 — tìm đúng thông tin cần thiết trong bài báo và ghi chú lại để có thể sử dụng khi so sánh nhiều nghiên cứu

Impact: Mỗi bài báo mất khoảng 5–15 phút để đọc và ghi chú các điểm quan tâm. Khi phải xem nhiều bài, thời gian dành cho việc tìm kiếm và tổng hợp thông tin tăng lên đáng kể

Success metric: Giảm thời gian để xác định thông tin liên quan trong mỗi bài báo; giảm thời gian ghi chú và tổng hợp; vẫn giữ được các thông tin quan trọng như phương pháp, biến đầu vào và kết quả

Non-AI alternative: Sử dụng template đọc paper với các trường cố định như mục tiêu, dữ liệu, phương pháp, biến đầu vào, kết quả và hạn chế để chuẩn hóa việc ghi chú

AI hypothesis: AI có thể hỗ trợ đọc và trích xuất các thông tin được xác định trước từ bài báo, sau đó tổng hợp thành bảng để người nghiên cứu kiểm tra và so sánh thay vì phải tìm thủ công từng thông tin trong từng bài


Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[x] Agent
[ ] Chưa biết
```

**Draft workflow Card #3:**

```text
CURRENT STATE — 5–15 phút/bài

[1 Tìm kiếm bài báo]
        →
[2 Mở + đọc abstract]
        →
[3 Tìm phương pháp, biến đầu vào, kết quả]  <-- BOTTLENECK
        →
[4 Ghi chú thông tin]
        →
[5 So sánh với các bài khác]

FUTURE STATE — thời gian cần đo

[1 Đưa bài báo vào hệ thống]
        →
[2 AI trích xuất phương pháp + biến đầu vào + kết quả]
        →
[3 Người nghiên cứu review và xác nhận thông tin]  <-- HUMAN BOUNDARY
        →
[4 Lưu vào bảng tổng hợp]

Fallback:
Nếu AI không tìm thấy thông tin, trích xuất sai hoặc không chắc chắn,
hệ thống đánh dấu phần đó để người nghiên cứu kiểm tra trực tiếp
trong bài báo.
```

File đính kèm: `01-individual-problem-scan-workflow-card-3.png`

---

### 2.3. Card muốn pitch nhất (chuẩn bị 2 phút)

**Card tôi muốn pitch nhất:**

```
Phát hiện lỗi/bất thường trong dữ liệu

```

**Vì sao (2-3 câu: workflow gì, số đo gì, impact gì):**

```
Tôi chọn problem này vì trong quá trình xử lý dữ liệu, người nghiên cứu phải kiểm tra các giá trị bất thường, sau đó đối chiếu với nguồn dữ liệu để xác định đó là lỗi hay giá trị thực tế. Workflow này hiện còn nhiều bước kiểm tra thủ công và có thể mất khoảng 1 ngày làm việc khi phải kiểm tra một dataset lớn. Nếu phát hiện sai hoặc bỏ sót các giá trị bất thường, dữ liệu đầu vào có thể ảnh hưởng đến các bước phân tích và xây dựng mô hình sau đó.

```

**Câu hỏi tôi muốn nhóm challenge (1-2 câu hỏi đúng chỗ yếu):**

```
Liệu vấn đề này thực sự cần AI, hay chỉ cần các rule thống kê như IQR, Z-score và các quy tắc kiểm tra dữ liệu là đã đủ?
Nếu AI chỉ phát hiện và đánh dấu các giá trị nghi ngờ, còn quyết định giữ, sửa hay loại bỏ vẫn do con người thực hiện, liệu giá trị mang lại có đủ lớn để xây dựng thành một giải pháp không?

```

**AI phản biện Card (nếu có):**
- Điểm yếu AI chỉ ra:
    Không phải mọi giá trị bất thường đều là lỗi; một số có thể là các giá trị thực tế quan trọng.
    Nếu chỉ dùng AI để phát hiện outlier mà không có bước kiểm tra nguồn dữ liệu và ngữ cảnh, hệ thống có thể đánh dấu sai.
    Cần có tiêu chí đo lường rõ ràng để chứng minh AI tốt hơn hoặc nhanh hơn cách kiểm tra hiện tại.
- Tôi sửa gì:
    Không để AI tự động xóa hoặc sửa dữ liệu.
    Thiết kế AI như một bước phát hiện và ưu tiên các giá trị cần kiểm tra, sau đó người nghiên cứu xác nhận và quyết định xử lý.
    Bổ sung các metric như thời gian kiểm tra, tỷ lệ phát hiện đúng các lỗi đã biết và tỷ lệ cảnh báo sai.

### Self-check nộp phần 01
- [x] Có 5+ problems + top 3 Cards đủ field
- [x] Mỗi Card có workflow trước/sau + bottleneck + metric + fallback
- [x] Đã chọn 1 card pitch + câu hỏi challenge
