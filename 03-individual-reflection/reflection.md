# 03 — Individual Reflection

> Viết bằng lời của bạn (Phase 7 trong `01-worksheet.md`). Có thể dùng AI gợi ý câu hỏi tự soi, không dùng AI viết thay. 8-12 câu, có chuyện cụ thể.

## Thông tin cá nhân

- Họ và tên: Đặng Quốc Hiệp
- Mã học viên: 2A202602755
- Nhóm: [điền số/tên nhóm] — thành viên: [Tên bạn A], [Tên bạn B], [Tên bạn C]
- Candidate problem nhóm chọn: Sinh viên lớp K4A mất 8-12 phút mỗi lần tìm lại một thông tin đã chốt trong Discord lớp (đổi deadline, format nộp, câu trả lời của TA), nhiều lúc phải hỏi lại rồi chờ TA; hệ quả là ~2 câu hỏi trùng nội dung mỗi tuần trong channel.

---

## 1. Tôi đã tham gia vào phần nào?

Ghi việc cụ thể + kết quả cụ thể. Không ghi chung chung kiểu "tham gia thảo luận".

| Hoạt động | Tôi đã làm gì? (việc cụ thể) | Kết quả / ảnh hưởng tới nhóm |
|---|---|---|
| Scan cá nhân | Scan 10 problems theo đủ 4 lăng kính, mỗi dòng bấm giờ hoặc đếm số thật (12 run/tuần, 200 tin/ngày, 5 bạn bị nhắc sửa bài Day01) thay vì ước lượng | Nhóm có thêm 3 candidate từ mình, trong đó bài Discord vào shortlist và cuối cùng được chọn |
| Pitch Problem Card | Pitch Card #1 (đối chiếu bài nộp với rubric) trong 2 phút: workflow 6 bước, baseline 37 phút, bottleneck 12 phút ở bước map rubric ↔ nội dung | Nhóm vào shortlist nhưng chỉ ra đúng chỗ yếu mình đã tự nghi ngờ: metric không có ground truth |
| Challenge bài của bạn khác | Hỏi [Tên bạn A] hai câu về bài tóm tắt paper: "actor là ai ngoài chính bạn?" và "làm sao biết bản tóm tắt của AI là đúng, ai kiểm?" | Nhóm nhận ra bài đó chưa có cách kiểm chứng đầu ra nên hạ xuống dưới shortlist |
| Gom trùng / cluster | Chỉ ra bài Discord của mình, bài "search slide trong Drive" và bài "hỏi lại quy trình nộp bài" thực ra cùng một pattern: thông tin đã tồn tại nhưng không tìm lại được | Từ 3 candidate rời rạc gom thành 1 cluster "tìm lại thông tin đã có", giúp nhóm rút từ 10-12 ý xuống 4 cụm |
| Chọn candidate problem | Bỏ phiếu cho bài Discord thay vì bài của chính mình, lý do: nhiều người cùng đau và có dấu hiệu khách quan (câu hỏi trùng trong channel) chứ không chỉ từ trải nghiệm 1 người | Nhóm đồng thuận chọn bài Discord, không ai phải bảo vệ bài của mình vì lý do cá nhân |
| Validation / research | [Ghi lại đúng việc mình đã làm: hỏi nhanh mấy bạn, đếm bao nhiêu câu hỏi trùng trong channel, tìm được tool/pattern nào] | [Kết quả: nhóm sửa lại problem/metric ở điểm nào] |
| Workflow nhóm | Đưa bản ASCII current/future workflow của mình làm bản nháp đầu, đề nghị thêm cột thời gian chờ vì bottleneck thật nằm ở chỗ chờ người trả lời, không chỉ ở thời gian search | Bản workflow nhóm tách riêng "thời gian thao tác" và "thời gian chờ", nhìn ra bottleneck rõ hơn |
| Problem Statement | Viết nháp field Success Metric và Boundary, ép mỗi metric phải có 3 phần: hiện trạng, mục tiêu, cách đo | [Ghi phần nhóm giữ lại / sửa lại] |
| Rule / Workflow / Agent | Lập luận chọn Workflow, không chọn Agent: đường đi cố định (nhận câu hỏi → tìm → trả lời kèm link), không cần AI tự lập kế hoạch | [Ghi nhóm chốt mức nào và mình ảnh hưởng tới quyết định ra sao] |
| Decision | Đề nghị điều kiện bắt buộc cho quyết định Go: mọi câu trả lời phải kèm link tin nhắn gốc + ngày, không tìm thấy thì nói không tìm thấy chứ không đoán | [Ghi decision cuối của nhóm: Go / Not Yet / No-Go] |

**Dấu tay rõ nhất của tôi trong artifact cuối (1-2 câu):**

```text
Hai chỗ mang dấu tay mình rõ nhất: (1) việc tách "thời gian thao tác" và "thời gian chờ
người trả lời" trong workflow nhóm, vì trước đó cả nhóm chỉ đếm 9 phút search mà bỏ qua
việc phải chờ TA 20 phút đến vài giờ — đó mới là phần đau nhất; (2) ràng buộc boundary
"AI bắt buộc trả lời kèm link tin nhắn gốc + ngày, không tìm thấy thì nói không tìm thấy"
xuất phát từ rủi ro mình nêu: đưa nhầm deadline cũ đã bị cập nhật.
```

---

## 2. Bảng dùng AI (mỗi dòng 1 phase có dùng AI — 2 cột cuối bắt buộc)

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Tự scan 6 ý trước, sau đó nhờ AI gợi ý thêm theo 4 lăng kính, yêu cầu mỗi gợi ý phải có actor + cách đo | Gợi ý "nhìn vào chỗ dữ liệu bị mất khi bàn giao" giúp mình nhớ ra 2 problem thật: dataset CSV bẩn và card Notion không cập nhật | Đưa 3 ý rộng và kêu to: trợ lý cá nhân hoá lộ trình học, chatbot tư vấn chọn môn, dự đoán điểm. Không ý nào mình quan sát được người thật đang kẹt | Bỏ cả 3 ý đó. Đặt tiêu chí tự lọc: ý nào mình không vẽ nổi workflow hiện tại và không có số thật thì không đưa vào bảng scan |
| Problem Card | Nhờ AI đóng vai skeptical PM phản biện Card #1, prompt ghi rõ "chỉ ra điểm yếu, đừng khen" | Chỉ đúng điểm yếu mình mơ hồ cảm thấy nhưng chưa gọi tên: metric "số mục bị sót" không có ground truth | Sau đó lại đề xuất nâng cấp thành "trợ lý chấm bài tự động cho cả lớp", tức nhảy sang giải pháp to hơn thay vì siết bài toán nhỏ lại | Giữ lại phần phê bình metric, đổi cách đo sang đếm comment nhắc sửa của TA và số lần push sửa sau deadline. Bỏ hẳn đề xuất mở rộng vì lệch khỏi bottleneck đã xác định |
| Workflow | Nhờ AI chuyển mô tả bằng lời thành sơ đồ ASCII trước/sau | Vẽ nhanh, đỡ mất thời gian căn khung | Gộp bước "search" và "chờ người trả lời" thành một bước, làm mất luôn phần đau nhất là thời gian chờ | Tách lại thành 2 bước riêng và ghi rõ thời gian chờ 20' đến vài giờ. Đây chính là ý mình mang sang bản workflow của nhóm |
| Research | [Điền nếu có dùng: hỏi AI tool/pattern nào đang giải bài tìm lại thông tin trong chat] | [AI gợi ý được gì dùng được] | [Chỗ AI đưa số liệu hoặc link không kiểm được] | [Mình đã bỏ số liệu nào, chỉ giữ link chính thức nào] |
| Problem Statement | Nhờ AI soi các field còn mơ hồ trong PS v0 | Chỉ ra Boundary mới nói phần "làm gì" mà chưa nói phần "không làm gì" | Viết lại metric thành câu nghe hay nhưng bỏ mất cách đo, kiểu "giúp sinh viên tra cứu nhanh hơn đáng kể" | Viết lại metric theo đúng 3 phần hiện trạng - mục tiêu - cách đo, và thêm vào Boundary phần không làm: không trả lời câu hỏi chuyên môn của môn học, chỉ tra lại thông tin đã được chốt trong channel |
| Rule / Workflow / Agent | Hỏi AI phản biện lựa chọn Workflow của nhóm | Nhắc nhóm kiểm tra xem có hạ xuống Rule được không | Mặc định nghiêng về Agent vì "linh hoạt hơn, tự tìm nhiều nguồn", nhưng không nói gì về rủi ro khi AI trả lời sai deadline | Không nghe. Nhóm giữ mức Workflow vì đường đi cố định và vì với Agent thì không ai kiểm soát được nó lấy thông tin từ đâu |
| Decision | Không dùng | Đây là phần nhóm phải tự chịu trách nhiệm. Nhóm tự chốt dựa trên bằng chứng đã thu được và những giả định còn chưa kiểm chứng, không để AI chốt thay | — | — |

> Nếu phase nào không dùng AI, ghi `Không dùng` và vì sao tự làm.

---

## 3. Reflection câu hỏi mở

Chọn 3-4 câu trong 6 câu dưới để viết thành đoạn 8-12 câu (không trả lời bullet 1 dòng):
- Tôi học được gì khi nghe top 3 problems của các bạn khác?
- Nhóm có lúc nào bị solution-first, đòi làm Agent cho ngầu không?
- Tôi có thay đổi ý kiến sau khi bị challenge không, vì sao đổi?
- Tôi đóng góp gì thật sự vào artifact cuối, phần nào có dấu tay của tôi?
- Điều khó nhất khi viết Problem Statement là gì, metric hay boundary?
- Nếu làm lại, tôi sẽ challenge nhóm mạnh hơn ở điểm nào?

**Reflection:**

```text
(Trả lời 3 câu: đổi ý sau khi bị challenge / nhóm có solution-first không / điều khó nhất
khi viết Problem Statement)

Mình vào lab với tâm thế khá chắc chắn rằng Card #1 của mình — đối chiếu bài nộp với
rubric — là bài đáng làm nhất, vì mình có baseline bấm giờ thật 37 phút và biết rõ từng
bước. Nhưng khi pitch xong, [Tên bạn B] hỏi đúng một câu làm mình khựng lại: "Nếu AI bảo
một mục còn mơ hồ mà bạn thấy đủ rồi, thì ai đúng?" Mình không trả lời được, vì baseline
thời gian thì đo được còn baseline chất lượng thì hoàn toàn do mình tự chấm mình. So với
bài Discord, nơi có dấu hiệu khách quan là mỗi tuần có khoảng 2 câu hỏi trùng nội dung mà
bất kỳ ai vào channel cũng đếm được, thì bài của mình yếu hơn về bằng chứng chứ không
phải yếu hơn về mức độ đau. Nên mình tự bỏ phiếu cho bài Discord thay vì bảo vệ bài của
mình, và đó là lần đầu mình thấy rõ khác biệt giữa "vấn đề mình tin là có thật" và "vấn
đề mình chứng minh được là có thật".

Nhóm mình có bị solution-first một lúc. Ngay sau khi chốt candidate, có bạn đề xuất luôn
là làm một con bot Discord tự đọc toàn bộ lịch sử rồi tự trả lời mọi câu hỏi, nghe rất
đã. Mình phản đối bằng một câu hỏi thay vì bằng quan điểm: nếu bot trả lời nhầm một
deadline đã bị đổi thì ai là người phát hiện ra, và phát hiện sau bao lâu? Cả nhóm im
mấy giây rồi nhận ra hậu quả rơi thẳng vào bạn nộp muộn, còn người phát hiện thì có khi
là TA, tức là phát hiện quá trễ. Từ đó nhóm hạ xuống mức Workflow với đường đi cố định
và ràng buộc bắt buộc kèm link tin nhắn gốc. Mình cũng phải thừa nhận là trước buổi lab,
chính mình cũng mặc định "chọn Agent thì mới ra dáng làm AI", và phần so sánh trên cùng
một bài toán mới cho mình thấy Rule với Workflow không hề kém hơn, chỉ là ít ồn ào hơn.

Phần khó nhất khi viết Problem Statement, với mình, là metric chứ không phải boundary.
Boundary chỉ cần nhóm ngồi liệt kê thẳng ra làm gì và không làm gì, mất chừng mười phút
là xong. Còn metric thì lần nào viết ra mình cũng thấy nó trôi về mấy chữ chung chung
kiểu "tra cứu nhanh hơn", và phải tự hỏi ba lần "đo bằng cách nào, ai đo, đo trong bao
lâu" thì mới ép được nó thành một con số kiểm chứng được. Bài học mình rút ra là metric
tốt không phải metric nghe tham vọng, mà là metric mà tuần sau có thể mở channel ra đếm
và biết ngay mình đúng hay sai.
```

---

## 4. Tự kiểm cuối bài (check trước khi nộp repo)

- [x] [12đ] Cá nhân có 5+ problems + top 3 Problem Cards — 10 problems, 3 Cards đủ field
- [x] [12đ] Tôi đã pitch rõ + challenge nhóm đúng trọng tâm (ghi ở bảng mục 1)
- [ ] Nhóm có nhật ký hội tụ từ candidates về 1 bài — đang ở `02-group-problem-statement/`, chờ nhóm hoàn thiện
- [ ] [15đ] Nhóm có workflow trước/sau
- [ ] [20đ] Nhóm có PS v0/v1 với metric + boundary rõ
- [ ] [15đ] Nhóm có so sánh No AI / Rule / Workflow / Agent
- [ ] [10đ] Nhóm có Go / Not Yet / No-Go + lý do rõ
- [x] [10đ] Reflection này có vai trò thật + AI giúp/sai ở đâu + điều học được + nếu làm lại đổi gì
- [x] [6đ] Tôi tự giải thích được mạch problem → workflow → metric → boundary → độ phù hợp AI

**Tự giải thích mạch bài (để trả lời nhanh nếu bị hỏi):**

```text
Problem: sinh viên K4A không tìm lại được thông tin đã chốt trong Discord, mất ~9 phút
mỗi lần tìm và nhiều lúc phải hỏi lại rồi chờ TA từ 20 phút đến vài giờ.
Workflow: đoán channel → search keyword → cuộn thread đọc ngữ cảnh → hỏi lại → chờ.
Bottleneck nằm ở bước search + đọc ngữ cảnh, vì search khớp từ khoá chứ không hiểu câu
hỏi, và phải đọc mới biết bản nào là bản cập nhật cuối cùng.
Metric: thời gian tìm ~9' xuống dưới 3' (bấm giờ 5 lần tìm), số câu hỏi trùng nội dung
~2/tuần xuống dưới 1/tuần (đếm tay trong 2 tuần).
Boundary: chỉ tra lại thông tin đã được chốt trong channel lớp; không trả lời câu hỏi
chuyên môn của môn học, không tự đưa ra quyết định mới thay TA.
Độ phù hợp AI: chọn Workflow chứ không chọn Agent, vì đường đi cố định (nhận câu hỏi →
tìm → trả lời kèm nguồn) nên không cần AI tự lập kế hoạch; cũng không chọn Rule vì câu
hỏi được diễn đạt tự do nên khớp từ khoá không đủ. Boundary con người: mọi câu trả lời
bắt buộc kèm link tin nhắn gốc + ngày để người hỏi tự xác minh; AI không tìm thấy nguồn
thì phải nói không tìm thấy chứ không được đoán; fallback là quay lại hỏi TA như cũ.
```
