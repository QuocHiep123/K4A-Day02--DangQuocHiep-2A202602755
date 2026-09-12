# 01 — Individual Problem Scan

> Điền theo Phase 1 + Phase 2 trong `01-worksheet.md`. Tự scan trước, dùng AI sau để phản biện. Không copy ví dụ Weekly Report.

## Thông tin cá nhân

- Họ và tên: Đặng Quốc Hiệp
- Mã học viên: 2A202602755
- Vai trò / bối cảnh: Sinh viên đang học lớp AI Thực Chiến K4A, song song đi intern mảng AI/Data ở một team nhỏ (3 intern + 1 mentor)
- Công việc hằng tuần (3-5 gạch đầu dòng để soi problem):
  - Chạy và so sánh các thí nghiệm ML nhỏ theo task mentor giao (~12 run/tuần), ghi lại kết quả để mentor review.
  - Làm sạch và chuẩn hoá dataset CSV nhận từ nhiều nguồn khác nhau (~2 lần/tuần).
  - Học các môn trên lớp + lớp AI Thực Chiến: đọc paper/slide, làm bài nhóm, nộp lab hằng tuần lên GitHub.
  - Trao đổi với lớp và TA qua Discord (channel chung + channel nhóm), theo dõi deadline và thay đổi lịch học ở đó.
  - Hỗ trợ 3 bạn trong nhóm bài tập chạy được code của mình (setup môi trường, đường dẫn dataset).

---

## Phase 1 — Scan 5+ problems (tối thiểu 5, khuyến khích 8-10)

**Cách điền:** mỗi dòng = việc gì + ai chịu + đo bằng gì. Cột `Dấu hiệu thật` bắt buộc có số: mất bao lâu (bấm giờ mấy lần), mấy lần/tuần, bao nhiêu người gặp, log/ticket/quote nào.

| # | Lăng kính (Lặp lại / Tốn thời gian / AI có thể tốt hơn / Pain từ người khác) | Problem quan sát được | Ai chịu ảnh hưởng? | Dấu hiệu thật (số + bằng chứng) |
|---|---|---|---|---|
| 1 | Lặp lại | Trước mỗi lần nộp lab phải tự đối chiếu bài với rubric + self-check xem thiếu mục nào | Mình + 3 bạn trong nhóm, rộng hơn là ~20 bạn lớp K4A | Bấm giờ 2 lần gần nhất: 41' và 34' cho cả quy trình kiểm + sửa, riêng bước đối chiếu ~12'. Lab Day01 mình vẫn sót 2 mục self-check, phải push sửa sau deadline |
| 2 | Lặp lại | Ghi tay config + kết quả mỗi run thí nghiệm vào Google Sheet | Mình + 2 intern cùng team; mentor là người đọc lại sheet | ~12 run/tuần, mỗi run ~6' thao tác ghi chép. Tuần trước 2/12 run thiếu seed và dataset version nên không tái lập được, phải chạy lại mất ~25' |
| 3 | Tốn thời gian | Tìm lại thông tin/quyết định đã chốt trong Discord lớp (đổi deadline, format nộp, câu trả lời của TA) | ~20 bạn trong lớp, nặng nhất là bạn vắng buổi hoặc đọc muộn | Bấm giờ 3 lần tìm trong tuần: 8', 12', 6'. Channel chung ~200 tin/ngày. Quan sát ~2 câu hỏi trùng nội dung mỗi tuần, TA phải trả lời lại |
| 4 | Tốn thời gian | Đọc 1 paper 10-14 trang chỉ để lấy 3 ý cho buổi seminar: method, dataset, kết quả chính | Mình + 3 bạn nhóm seminar | 60-75'/paper, 2 paper/tuần. Phần lớn thời gian nằm ở đoạn dò Section 3-4 để tìm đúng phần method |
| 5 | Pain từ người khác | Mentor phải hỏi lại "task này đang ở đâu, đang kẹt gì" vì card trên Notion không được cập nhật kịp | Mentor + 3 intern | 2-3 lần hỏi lại/tuần trên Slack, mỗi lần cắt ngang công việc ~10'. Quote mentor: "Em update card giúp anh, anh không biết đang chờ ai" |
| 6 | Pain từ người khác | Bạn cùng nhóm hỏi lại cùng một câu về cách chạy code của mình (env, đường dẫn dataset) | 3 bạn trong nhóm bài tập | 4 lần trong 2 tuần, mỗi lần mình mất 15-20' hướng dẫn lại gần như y hệt |
| 7 | Tốn thời gian | Làm sạch dataset CSV từ nhiều nguồn: khác header, khác định dạng ngày, khác encoding | Mình; mentor phải chờ dữ liệu sạch mới review được | 40-50'/lần, ~2 lần/tuần. Lần gần nhất phát hiện sai định dạng ngày sau khi đã train xong, mất thêm 1 lượt chạy |
| 8 | AI có thể tốt hơn | Search trong Drive/LMS môn học chỉ khớp tên file, không khớp nội dung slide | ~20 bạn trong lớp | Tìm lại "slide có phần đánh giá mô hình" mất 5-10'/lần, tuần trước 3 lần. Tên file kiểu `Buoi5_v2_final.pdf` nên không đoán được nội dung |
| 9 | Lặp lại | Nhớ và làm đúng convention đặt tên repo/thư mục/file khi nộp bài | ~20 bạn trong lớp | Ở Day01, mình đếm trong channel có 5 bạn bị nhắc sửa lại cấu trúc repo hoặc tên file trước khi được chấm |
| 10 | AI có thể tốt hơn | Notification Discord quá dày nên bỏ lỡ thông báo quan trọng | Mình + các bạn theo dõi nhiều channel | ~200 tin/ngày ở channel chung. Tuần trước bỏ lỡ 1 thông báo đổi giờ buổi học, đến muộn 15' |

> Gợi ý tự soi: tuần trước mất nhiều thời gian nhất vào việc gì? Việc gì hay trì hoãn? Người khác hay hỏi lại câu gì? Workflow nào ai cũng biết là chậm?

**AI đã dùng ở Phase 1 (nếu có):**
- Prompt đã hỏi: "Tôi là sinh viên đang intern mảng AI/Data. Việc hằng tuần của tôi gồm: chạy thí nghiệm ML, làm sạch dataset, học trên lớp, nộp lab hằng tuần, trao đổi qua Discord. Tôi đã tự nghĩ ra 6 vấn đề: [liệt kê 6 dòng đầu]. Hãy gợi ý thêm problem theo 4 lăng kính, mỗi gợi ý ghi rõ actor, workflow sơ bộ và cách đo. Đừng đưa ý tưởng rộng kiểu xây trợ lý AI toàn năng."
- Ý dùng được: gợi ý "nhìn vào chỗ dữ liệu bị mất khi bàn giao" giúp mình nhớ ra dòng 7 (làm sạch CSV) và dòng 5 (Notion không cập nhật nên mentor phải hỏi lại). Gợi ý "nhìn vào câu người mới hay hỏi" ra dòng 6 và dòng 9.
- Ý bỏ vì không phải pain thật: "trợ lý AI cá nhân hoá lộ trình học tập", "chatbot tư vấn chọn môn", "hệ thống dự đoán điểm". Ba ý này mình chưa từng thấy ai trong lớp thật sự kẹt, và không vẽ được workflow hiện tại nên bỏ.

**Self-check Phase 1:**
- [x] Đủ 5+ dòng, mỗi dòng có actor + số đo cụ thể
- [x] Dùng ít nhất 3/4 lăng kính (dùng đủ cả 4)
- [x] Không có dòng chung chung kiểu "mất nhiều thời gian"

---

## Phase 2 — Top 3 Problem Cards

### 2.1. Chọn top 3

Giữ bài nào: actor cụ thể, workflow vẽ được 3-7 bước, bottleneck ở 1 bước, impact đo được. Loại bài quá rộng.

| Rank | Problem (copy từ bảng scan) | Vì sao chọn (2-3 ý) | Điều còn chưa chắc |
|---|---|---|---|
| 1 | #1 — Tự đối chiếu bài nộp với rubric trước khi nộp lab | Mình là actor trực tiếp nên có baseline bấm giờ thật, không phải ước lượng. Workflow 6 bước, nghẽn gọn ở đúng 1 bước là đối chiếu rubric ↔ nội dung. Tách được rất rõ phần Rule (cấu trúc file) và phần cần đọc hiểu (nội dung đủ ý chưa) nên so sánh Rule / Workflow / Agent được trên cùng một bài | Chuẩn "mục này viết đủ hay chưa" mang tính chủ quan, chưa có ground truth. Baseline "sót 2 mục" mới chỉ từ 1 lần nộp của riêng mình |
| 2 | #2 — Ghi tay config + kết quả mỗi run thí nghiệm | Tần suất cao (12 run/tuần) và hậu quả đo được (2 run phải chạy lại). Bằng chứng nằm ngay trên sheet hiện tại: có cột bị bỏ trống | Nhiều khả năng đây là bài của script chứ không phải của AI. Nếu vậy thì có đủ "chất" để nhóm đào sâu cả buổi không |
| 3 | #3 — Tìm lại quyết định/thông tin đã chốt trong Discord lớp | Nhiều người cùng đau chứ không chỉ mình, có dấu hiệu khách quan là câu hỏi trùng lặp trong channel. Hậu quả rõ khi dùng nhầm thông tin đã bị cập nhật | Quyền truy cập lịch sử channel và vấn đề riêng tư. Dễ phình thành bài "làm search cho mọi thứ" |

### 2.2. Problem Cards chi tiết (lặp lại cho cả 3 cards)

---

#### Problem Card #1 — Đối chiếu bài nộp với rubric trước khi nộp lab

```text
Problem 1 câu:
Trước mỗi lần nộp lab, sinh viên mất 30-40 phút tự đối chiếu bài với rubric và self-check,
trong đó bước map từng tiêu chí rubric sang nội dung đã viết tốn nhất và vẫn bị sót mục.

Actor:
Sinh viên lớp AI Thực Chiến K4A là người nộp bài (~20 người); quan sát trực tiếp được là
mình và 3 bạn trong nhóm. Người chịu ảnh hưởng thứ hai là TA vì phải nhắc sửa lại bài.

Thời điểm / bối cảnh:
1-2 tiếng trước deadline nộp repo lab, 1-2 lần/tuần.

Current workflow 3-7 bước:
1. Mở README rubric + phần self-check trong worksheet (3')
2. Mở lại từng file bài nộp, đọc lướt xem đã viết gì (5')
3. Đối chiếu từng tiêu chí rubric với nội dung đã viết, nhảy qua lại 2 tab (12')
4. Sửa những chỗ thiếu hoặc còn chung chung (10-20')
5. Kiểm cấu trúc thư mục và tên file theo convention (4')
6. Commit, push, mở lại trên GitHub kiểm tra hiển thị (3')

Bottleneck:
Bước 3. Rubric viết theo tiêu chí ("metric phải có hiện trạng, mục tiêu và cách đo"),
còn bài viết theo mạch kể chuyện, nên phải tự đọc hiểu rồi map hai bên với nhau.
Đây là bước duy nhất không làm được bằng Ctrl+F.

Impact:
30-45'/lần nộp x ~1.5 lần/tuần = ~50-65'/tuần cho riêng mình.
Lab Day01 mình sót 2 mục self-check và phải push sửa sau deadline.
Trong channel lớp, mình đếm được 5 bạn bị nhắc sửa lại bài ở Day01.

Success metric:
- Thời gian bước đối chiếu: 12' -> dưới 4' (bấm giờ 3 lần nộp kế tiếp, lấy trung bình).
- Số mục rubric bị sót ở bản nộp đầu: 2 -> 0, đo bằng số comment nhắc sửa của TA và
  số lần phải push sửa sau deadline, theo dõi trong 3 lần nộp.

Non-AI alternative:
Một file checklist markdown dùng lại được + script grep kiểm cấu trúc thư mục, tên file,
heading rỗng và ô self-check chưa tick. Giải được nhóm lỗi "thiếu file / thiếu mục",
nhưng không phát hiện được lỗi "có viết nhưng viết chung chung, metric không có cách đo".

AI hypothesis:
AI đọc bài nộp cùng rubric, trả về bảng 3 cột: mục nào đã đủ / thiếu hẳn / có viết
nhưng còn mơ hồ, kèm trích dẫn đúng đoạn văn trong bài. Người vẫn tự quyết sửa gì.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow        <- Rule cho bước kiểm cấu trúc, AI cho bước đánh giá nội dung
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #1** (ASCII / Mermaid / ảnh đính kèm):

```text
CURRENT STATE — 37 phút (đo ở lần nộp gần nhất)

[1 Mở rubric + self-check: 3']
→ [2 Đọc lướt bài đã viết: 5']
→ [3 Đối chiếu rubric ↔ nội dung: 12']   <-- bottleneck, làm tay, vẫn sót 2 mục
→ [4 Sửa chỗ thiếu: 14']
→ [5 Kiểm cấu trúc file: 4']
→ [6 Commit + push + xem lại: 3']

FUTURE STATE — 16 phút

[1 Script kiểm cấu trúc + heading rỗng + ô self-check: 0.5' - máy/Rule]
→ [2 AI đối chiếu nội dung với rubric, xuất bảng đủ/thiếu/mơ hồ kèm trích dẫn: 1' - AI]
→ [3 Mình đọc bảng, tự quyết giữ hay bỏ từng cảnh báo: 3']   <-- human boundary
→ [4 Sửa chỗ thiếu: 9']
→ [5 Commit + push + xem lại: 2.5']

Boundary: AI chỉ đánh dấu và trích dẫn, không tự sửa nội dung bài.
Fallback: AI báo sai hoặc bỏ sót → quay lại checklist tay như hiện tại (mất thêm 12').
Rủi ro: AI nói "đủ rồi" trong khi thực tế còn thiếu, nên vẫn giữ 1 lượt mình tự đọc rubric.
```

File đính kèm (nếu vẽ riêng): chưa có, workflow vẽ trực tiếp bằng ASCII ở trên.

---

#### Problem Card #2 — Ghi tay config và kết quả mỗi run thí nghiệm

```text
Problem 1 câu:
Mỗi run thí nghiệm, intern mất ~6 phút gõ tay config và kết quả vào Google Sheet, và vì
gõ tay nên tuần trước có 2/12 run thiếu seed, dataset version, không tái lập lại được.

Actor:
Mình và 2 intern cùng team là người ghi; mentor là người đọc lại sheet để so sánh kết quả.

Thời điểm / bối cảnh:
Ngay sau mỗi lần chạy xong 1 run train/eval trên máy lab, ~12 run/tuần.

Current workflow 3-7 bước:
1. Sửa config (lr, batch size, seed, dataset version) trong file hoặc CLI args (2')
2. Chạy run và chờ kết quả (thời gian chờ không tính vào thao tác tay)
3. Copy số liệu metric từ terminal/log (2')
4. Mở Google Sheet, dán metric và gõ lại config bằng tay (3')
5. Đặt tên run + ghi note ngắn "chạy để thử gì" (1')
6. Cuối tuần lọc lại sheet để so sánh các run (10'/tuần)

Bottleneck:
Bước 4. Config đã tồn tại sẵn trong máy nhưng vẫn phải gõ lại bằng tay sang chỗ khác.
Đây vừa là chỗ tốn thời gian vừa là nơi phát sinh lỗi thiếu field.

Impact:
~6'/run x 12 run = ~72'/tuần thao tác tay cho một người, nhân với 3 intern.
Rủi ro lớn hơn cả thời gian: 2/12 run tuần trước không tái lập được, phải chạy lại ~25'
và mentor không so sánh được kết quả vì thiếu dataset version.

Success metric:
- Thời gian ghi log: 6'/run -> dưới 1'/run (bấm giờ 5 run liên tiếp).
- Số run thiếu field bắt buộc (seed, dataset version, commit hash): 2/12 -> 0/12,
  đếm trực tiếp trên sheet trong 2 tuần.

Non-AI alternative:
Viết một wrapper script: sau mỗi run tự ghi config đang dùng + git commit hash + metric
ra một dòng CSV/JSON, hoặc dùng thẳng một công cụ tracking thí nghiệm có sẵn.
Cách này giải gần như trọn vẹn bài toán.

AI hypothesis:
Rất yếu. Chỗ duy nhất AI có thể thêm giá trị là cuối tuần tóm tắt "run nào tốt nhất và
khác các run còn lại ở tham số nào", nhưng đó là nice-to-have, không phải bottleneck.

Quick gut:
[ ] No AI / process fix
[x] Rule            <- dữ liệu có cấu trúc, đúng/sai rõ ràng, không có gì mơ hồ cần phán đoán
[ ] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #2:**

```text
CURRENT STATE — ~6 phút thao tác tay / run (chưa tính thời gian chờ chạy)

[1 Sửa config: 2'] → [2 Chạy + chờ] → [3 Copy metric từ log: 2']
→ [4 Gõ tay config vào Sheet: 3']   <-- bottleneck, nguồn gốc lỗi thiếu field
→ [5 Đặt tên + note: 1']
→ [6 Cuối tuần lọc sheet so sánh: 10'/tuần]

FUTURE STATE — dưới 1 phút thao tác tay / run

[1 Sửa config: 2'] → [2 Chạy + chờ]
→ [3 Script tự ghi config + git commit hash + metric ra 1 dòng: 0' - máy/Rule]
→ [4 Mình gõ 1 dòng note "chạy để thử gì": 0.5']   <-- human boundary, phần máy không biết
→ [5 Cuối tuần đọc bảng đã tự tổng hợp: 4']

Fallback: script lỗi hoặc phải chạy trên máy khác → ghi tay như cũ nhưng theo template
có sẵn đủ field bắt buộc, để ít nhất không sót seed và dataset version.
```

File đính kèm: chưa có.

---

#### Problem Card #3 — Tìm lại quyết định đã chốt trong Discord lớp

```text
Problem 1 câu:
Sinh viên mất 8-12 phút mỗi lần tìm lại một thông tin đã được chốt trong Discord lớp
(đổi deadline, format nộp, câu trả lời của TA), và nhiều lúc phải hỏi lại rồi ngồi chờ.

Actor:
~20 bạn trong lớp K4A, nặng nhất là bạn vắng buổi hoặc đọc muộn. TA là người chịu ảnh
hưởng thứ hai vì phải trả lời lặp lại cùng một câu hỏi.

Thời điểm / bối cảnh:
Lúc chuẩn bị nộp bài hoặc trước buổi học, khi cần xác minh một thông tin đã nói trước đó.

Current workflow 3-7 bước:
1. Đoán thông tin nằm ở channel nào (1')
2. Search keyword, thử cả tiếng Việt có dấu lẫn không dấu, kết quả lệch (3')
3. Cuộn ngược thread đọc ngữ cảnh, xem thông tin có bị cập nhật lại sau đó không (4')
4. Vẫn không chắc nên hỏi lại trong channel (1')
5. Chờ TA hoặc bạn khác trả lời (20' đến vài giờ)

Bottleneck:
Bước 2-3. Search của Discord khớp từ khoá chứ không hiểu câu hỏi, và thông tin đúng
thường nằm rải trong một thread dài nên phải đọc mới biết bản nào là bản cuối cùng.

Impact:
Riêng mình 3 lần/tuần x ~9' = ~27'/tuần, chưa tính thời gian chờ.
Trong channel có ~2 câu hỏi trùng nội dung mỗi tuần, tức TA trả lời lại việc đã trả lời.
Hậu quả nặng nhất là dùng nhầm thông tin cũ khi thông tin đó đã được cập nhật.

Success metric:
- Thời gian tìm một thông tin đã chốt: ~9' -> dưới 3' (bấm giờ 5 lần tìm).
- Số câu hỏi trùng nội dung trong channel: ~2/tuần -> dưới 1/tuần (đếm tay trong 2 tuần).

Non-AI alternative:
Một file `decisions.md` hoặc một message pin duy nhất, TA hoặc lớp trưởng cập nhật sau
mỗi buổi: ngày, nội dung chốt, link tin nhắn gốc. Rẻ và chính xác, nhưng phụ thuộc hoàn
toàn vào việc có người chịu duy trì đều đặn hay không.

AI hypothesis:
AI đọc lịch sử channel, trả lời câu hỏi bằng ngôn ngữ tự nhiên và bắt buộc kèm link tin
nhắn gốc + ngày, để người hỏi tự xác minh trước khi tin.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow        <- câu hỏi diễn đạt tự do nên cần hiểu ngôn ngữ, nhưng đường đi cố định:
[ ] Agent              nhận câu hỏi -> tìm -> trả lời kèm nguồn, không cần tự lập kế hoạch
[ ] Chưa biết
```

**Draft workflow Card #3:**

```text
CURRENT STATE — 9 phút thao tác + 20' đến vài giờ chờ

[1 Đoán channel: 1'] → [2 Search keyword: 3'] → [3 Cuộn thread đọc ngữ cảnh: 4']
→ [4 Vẫn không chắc, hỏi lại trong channel: 1']   <-- bottleneck: đứt mạch, phải chờ người
→ [5 Chờ TA trả lời: 20' đến vài giờ]

FUTURE STATE — dưới 3 phút, không phải chờ người

[1 Hỏi bằng câu tự nhiên: 0.5']
→ [2 AI tìm trong lịch sử channel, trả lời kèm link tin nhắn gốc + ngày: 0.5' - AI]
→ [3 Mình mở link gốc xác minh, xem có bản cập nhật sau đó không: 1.5']  <-- human boundary
→ [4 Nếu vẫn không rõ thì mới hỏi TA: 0.5']

Boundary: AI không được trả lời khi không tìm thấy nguồn, phải nói "không tìm thấy, hỏi
TA" thay vì đoán. Mọi câu trả lời bắt buộc kèm link tin nhắn gốc.
Fallback: AI không tìm ra hoặc trả lời sai → quay về hỏi trong channel như hiện tại.
Rủi ro: AI đưa deadline cũ đã bị thay đổi, đây chính là lý do bắt buộc phải có link + ngày.
```

File đính kèm: chưa có.

---

### 2.3. Card muốn pitch nhất (chuẩn bị 2 phút)

**Card tôi muốn pitch nhất:**

```text
Card #1 — Đối chiếu bài nộp với rubric trước khi nộp lab.
```

**Vì sao (2-3 câu: workflow gì, số đo gì, impact gì):**

```text
Workflow 6 bước và mình là actor trực tiếp nên có baseline bấm giờ thật chứ không ước
lượng: 37 phút ở lần nộp gần nhất, riêng bước đối chiếu rubric với nội dung là 12 phút.
Impact đo được ở hai mặt: thời gian (~50-65 phút/tuần cho riêng mình) và chất lượng
(Day01 mình sót 2 mục self-check, trong channel có 5 bạn bị nhắc sửa lại bài).
Bài này tách rất rõ phần nào là Rule và phần nào mới cần AI: kiểm cấu trúc thư mục, tên
file, ô self-check chưa tick là rule thuần; chỉ bước "mục này viết đủ ý chưa" mới cần đọc
hiểu, nên nhóm có thể so sánh Rule / Workflow / Agent trên cùng một bài toán.
```

**Câu hỏi tôi muốn nhóm challenge (1-2 câu hỏi đúng chỗ yếu):**

```text
1. Metric "số mục bị sót" của mình đang dựa vào đánh giá chủ quan: nếu AI bảo một mục
   "còn mơ hồ" mà mình thấy đã đủ thì lấy gì làm chuẩn? Nhóm giúp mình nghĩ cách đo có
   ground truth thật (ví dụ đếm comment nhắc sửa của TA) thay vì để mình tự chấm mình.
2. Baseline "sót 2 mục" mới chỉ đến từ 1 lần nộp của riêng mình. Như vậy có đủ làm
   baseline cho cả nhóm không, hay phải hỏi thêm vài bạn trong lớp trước khi chốt metric?
```

**AI phản biện Card (nếu có):**
- Điểm yếu AI chỉ ra: (1) actor đang bó hẹp trong đúng một lớp học nên khó khẳng định pain tồn tại ngoài phạm vi này; (2) metric "số mục bị sót" không có ground truth, hai người chấm khác nhau sẽ ra kết quả khác nhau; (3) nếu để AI đánh giá nội dung thì rủi ro lớn nhất là AI báo "đủ rồi" trong khi thực tế còn thiếu, tức lỗi bỏ sót nguy hiểm hơn lỗi báo thừa, nhưng card của mình chưa xử lý điều đó.
- Tôi sửa gì: đổi cách đo từ "mình tự chấm" sang đếm số comment nhắc sửa của TA và số lần phải push sửa sau deadline, vì đây là số kiểm chứng được từ bên ngoài. Bổ sung vào future workflow dòng boundary "AI chỉ đánh dấu và trích dẫn, không tự sửa", và giữ lại một lượt mình tự đọc rubric ở cuối để chặn trường hợp AI báo sót. Ý AI gợi ý mở rộng thành "trợ lý chấm bài tự động cho cả lớp" thì mình bỏ, vì vượt xa phạm vi một buổi lab và làm đổi luôn bản chất bài toán.

### Self-check nộp phần 01
- [x] Có 5+ problems + top 3 Cards đủ field (10 problems, 3 Cards đầy đủ)
- [x] Mỗi Card có workflow trước/sau + bottleneck + metric + fallback
- [x] Đã chọn 1 card pitch + câu hỏi challenge
