# Gợi ý đề tài problem cho các nhóm — Day 02

> Đây là **ngân hàng gợi ý** để học viên mở rộng quan sát, không phải danh sách đề bắt buộc. Mỗi nhóm vẫn phải chọn problem từ **trải nghiệm thật**, viết lại theo actor/workflow/metric của mình, và sẵn sàng bị challenge.

## Cách dùng

1. Mỗi người scan riêng trước — chỉ đọc gợi ý khi bí hoặc muốn mở rộng lăng kính.
2. Không copy nguyên văn vào Problem Card.
3. Ưu tiên bài có: actor rõ, workflow vẽ được, bottleneck một bước, metric đo được trong lab.
4. Ký hiệu **Quick gut** chỉ là hướng suy nghĩ ban đầu — nhóm vẫn phải so sánh No AI / Rule / Workflow / Agent ở Phase 6.

---

## Bảng chọn nhanh theo bối cảnh

| Bối cảnh | Số gợi ý | Phù hợp khi nhóm… |
|---|---:|---|
| Học tập / lớp học | 8 | Đa số sinh viên, ít kinh nghiệm đi làm |
| Thực tập / công việc mới | 6 | Có người đang intern hoặc mới onboard |
| Người đi làm / PM / dev | 8 | Có người đã làm product, ops, support |
| Nhóm / CLB / dự án nhỏ | 5 | Pain từ làm việc nhóm, không phải công ty |
| Cải thiện sản phẩm đang dùng | 5 | Muốn phân tích app/tool quen thuộc |
| Đời sống cá nhân | 4 | Muốn bài gần gũi, dễ validate với bạn bè |

---

## 1. Học tập / lớp học

| # | Gợi ý problem | Ai đang đau? | Bottleneck gợi ý | Metric gợi ý | Quick gut |
|---|---|---|---|---|---|
| H1 | Tìm lại quyết định/câu trả lời cũ trong Discord/LMS sau vài tuần | Sinh viên, TA | Search + đọc nhiều thread | 15 phút → dưới 3 phút/lần tìm | Workflow |
| H2 | Đọc tài liệu dài (slide/PDF) trước deadline để làm bài tập | Sinh viên | Đọc + tóm tắt + nhận diện phần cần làm | 60 phút → 25 phút/bài | Workflow |
| H3 | Không biết bài nộp thiếu field/format nào cho đến khi bị trả | Sinh viên | Đối chiếu yêu cầu với file đã làm | Số lần nộp lại: 2 → 0 | Rule |
| H4 | Ôn thi từ nhiều nguồn rời rạc (slide, video, note bạn) | Sinh viên | Tổng hợp chủ đề trùng/lệch | 3 giờ → 1.5 giờ/kỳ ôn | Workflow |
| H5 | Hỏi lại deadline, cách nộp, rubric — câu hỏi lặp trong lớp | TA, giảng viên | Trả lời cùng một kiểu nhiều lần | 10 câu/tuần → 2 câu cần người trả lời | Rule / Workflow |
| H6 | Tổng hợp tiến độ lab nhóm để báo coach | Nhóm trưởng | Gom update từ từng thành viên | 45 phút/tuần → 15 phút | Workflow |
| H7 | Peer review bài của bạn — khó chỉ ra thiếu sót cụ thể | Sinh viên | Đọc bài + so rubric + viết feedback | 30 phút → 15 phút/bài | Workflow |
| H8 | Chọn đề tài đồ án/khóa luận — quá nhiều ý tưởng mơ hồ | Sinh viên năm cuối | Thu hẹp theo actor/metric/feasibility | 2 tuần → 3 ngày chốt hướng | Workflow |

---

## 2. Thực tập / công việc mới

| # | Gợi ý problem | Ai đang đau? | Bottleneck gợi ý | Metric gợi ý | Quick gut |
|---|---|---|---|---|---|
| I1 | Onboarding — không biết hỏi ai việc X | Intern mới | Tìm owner + context rải rác | 30 phút → 5 phút/lần hỏi | Workflow |
| I2 | Hiểu task từ Slack thread + doc + comment Jira | Intern, junior | Nối thông tin từ nhiều nguồn | 40 phút → 15 phút/task | Workflow |
| I3 | Viết daily/weekly update cho mentor | Intern | Nhớ việc đã làm + format chuẩn | 20 phút/ngày → 7 phút | Rule / Workflow |
| I4 | Không biết quy trình deploy/release đúng thứ tự | Dev mới | Tra wiki nhiều chỗ, sợ sót bước | Số lần nhờ senior: 3 → 0/tuần | Rule |
| I5 | Ghi chú sau meeting 1-1 với manager | Intern | Tóm tắt action item + ưu tiên | 25 phút → 10 phút/buổi | Workflow |
| I6 | Review PR/code lần đầu — không biết focus đâu | Intern dev | Đọc diff + hiểu impact | 50 phút → 25 phút/PR | Workflow |

---

## 3. Người đi làm — PM, ops, support, dev

| # | Gợi ý problem | Ai đang đau? | Bottleneck gợi ý | Metric gợi ý | Quick gut |
|---|---|---|---|---|---|
| W1 | Tổng hợp weekly report từ Jira, Sheets, Slack | PM | Viết narrative từ raw data | 90 phút → 30 phút/tuần | Workflow |
| W2 | Chuẩn bị meeting recap + action items sau họp cross-team | PM, team lead | Phân loại quyết định vs ý kiến | 35 phút → 12 phút/buổi | Workflow |
| W3 | Review PRD/spec dài trước khi comment | PM, designer | Đọc hiểu context + tìm lỗ hổng | 45 phút → 20 phút/bản | Workflow |
| W4 | Phân loại ticket support lặp lại | Support lead | Gắn nhãn + routing đúng team | 5 phút → 1 phút/ticket | Rule / Workflow |
| W5 | Tìm quyết định/product decision cũ trước khi làm feature mới | PM, dev | Search Slack/Notion/Confluence | 15 phút → 2 phút/lần | Workflow / Agent |
| W6 | Tổng hợp monthly KPI từ nhiều dashboard | Manager | Copy số + giải thích biến động | 2 giờ → 45 phút/tháng | Workflow |
| W7 | Viết release note từ changelog kỹ thuật | PM, devrel | Dịch technical → user-facing | 40 phút → 15 phút/release | Workflow |
| W8 | Handoff bug từ QA sang dev — thiếu context tái hiện | QA, dev | Tóm tắt steps + expected/actual | 2 vòng hỏi lại → 0 vòng | Rule / Workflow |

---

## 4. Nhóm / CLB / dự án nhỏ

| # | Gợi ý problem | Ai đang đau? | Bottleneck gợi ý | Metric gợi ý | Quick gut |
|---|---|---|---|---|---|
| G1 | Phân công việc sau họp nhóm — mọi người hiểu khác nhau | Nhóm trưởng | Chốt owner + deadline rõ | 30% task trễ → dưới 10% | Rule |
| G2 | Theo dõi action item — việc bị rơi giữa tuần | Cả nhóm | Nhắc + cập nhật trạng thái | 3 việc rơi/sprint → 0 | Workflow |
| G3 | Tổng hợp feedback từ nhiều người cho một deliverable | Lead dự án | Gom ý trùng/khác, ưu tiên | 2 giờ → 40 phút/vòng feedback | Workflow |
| G4 | Onboard thành viên mới vào CLB/dự án | Core team | Giải thích quy trình + tài liệu rải rác | 1 tuần → 2 ngày hiểu cơ bản | Rule / Workflow |
| G5 | Lên lịch họp nhóm — conflict lịch, timezone | Nhóm trưởng | Thu thập availability + chốt slot | 20 phút → 5 phút/lần họp | Rule |

---

## 5. Cải thiện sản phẩm đang dùng

| # | Gợi ý problem | Ai đang đau? | Bottleneck gợi ý | Metric gợi ý | Quick gut |
|---|---|---|---|---|---|
| P1 | Search trong app nội bộ/LMS — kết quả không đúng ý | User nội bộ | Keyword search + lọc thủ công | 10 lần search → 2 lần/session | Workflow |
| P2 | Onboarding app mới — không biết bắt đầu từ đâu | User mới | Đọc help rải rác | Time-to-first-value: 2 ngày → 2 giờ | Workflow |
| P3 | Form dài — dễ nhập sai field bắt buộc | User, ops | Validate + sửa lỗi sau submit | 25% submit lỗi → 5% | Rule |
| P4 | Notification quá nhiều / không đúng lúc | User | Lọc signal vs noise | 20 noti/ngày → 5 noti quan trọng | Rule / Workflow |
| P5 | Support phải hỏi lại cùng thông tin (email, order ID) | Support, user | Thu thập context ban đầu | 2 vòng chat → 1 vòng | Rule / Workflow |

---

## 6. Đời sống cá nhân (dễ validate với bạn bè)

| # | Gợi ý problem | Ai đang đau? | Bottleneck gợi ý | Metric gợi ý | Quick gut |
|---|---|---|---|---|---|
| L1 | Theo dõi chi tiêu rải rác nhiều app/ngân hàng | Cá nhân | Tổng hợp + phân loại | 30 phút/tuần → 10 phút | Rule / Workflow |
| L2 | Lên kế hoạch đi chơi/ăn cho nhóm bạn | Người tổ chức | Gom preference + chốt địa điểm | 45 phút → 15 phút/lần | Workflow |
| L3 | Nhắc việc định kỳ (thuốc, học, họp) nhưng hay quên context | Cá nhân | Nhắc đúng việc đúng lúc | 3 lần quên/tháng → 0 | Rule |
| L4 | Tổng hợp giấy tờ/hồ sơ khi cần nộp (visa, thực tập) | Sinh viên | Tìm file + checklist thiếu gì | 2 giờ → 30 phút/lần | Rule |

---

## Gợi ý theo 4 lăng kính scan

Dùng khi muốn đa dạng hóa danh sách cá nhân trước khi vào nhóm.

### Lăng kính: Lặp lại

- Báo cáo tuần/tháng theo cùng format
- Standup update mỗi sáng
- Nhập liệu từ email vào spreadsheet
- Trả lời FAQ lớp học / Discord
- Copy metric từ tool này sang slide/tool khác

### Lăng kính: Tốn thời gian

- Đọc tài liệu 20+ trang để ra một quyết định nhỏ
- Review code/PR lớn lần đầu
- Chuẩn bị slide từ nhiều nguồn số liệu
- Tìm lại file/version đúng trong Drive
- Viết lại nội dung từ meeting recording

### Lăng kính: AI có thể tốt hơn (một bước trong workflow)

- Tóm tắt thread dài
- Phân loại feedback theo chủ đề
- Draft email/message từ bullet points
- Gợi ý câu hỏi khi đọc tài liệu
- So sánh hai bản spec và chỉ khác biệt

### Lăng kính: Pain từ người khác

- Designer hỏi lại vì spec mơ hồ
- CEO/manager hỏi update khi report chưa xong
- User support ticket cùng một lỗi
- Bạn học nhờ giải thích lại phần đã dạy trên lớp
- Thành viên mới không biết quy trình nộp bài

---

## Combo đề tài gợi ý cho từng "kiểu nhóm"

Không phải phân nhóm cứng — chỉ giúp coach gợi ý khi cả nhóm đang bí.

### Nhóm chủ yếu sinh viên

Ưu tiên: **H1, H2, H5, H6, H7** + **G1, G2**  
Lý do: dễ có trải nghiệm thật, validate nhanh trong lớp/Discord.

### Nhóm có người đang thực tập

Ưu tiên: **I1, I2, I3** + **W3, W8**  
Lý do: pain onboarding và handoff rất cụ thể, metric thời gian rõ.

### Nhóm có PM / người đi làm

Ưu tiên: **W1, W2, W3, W5, W6**  
Lý do: workflow nhiều bước, so sánh Rule/Workflow/Agent có ý nghĩa (xem ví dụ `02-deliverable-example.md`).

### Nhóm thích phân tích sản phẩm

Ưu tiên: **P1–P5**  
Lý do: bắt buộc research giải pháp đã có; tránh solution-first bằng cách mô tả user workflow trước.

---

## Tiêu chí một đề tài **đủ tốt** cho lab hôm nay

| Tiêu chí | Đạt | Chưa đạt |
|---|---|---|
| Actor | Một vai trò cụ thể (PM intern, TA, nhóm trưởng…) | "Mọi người", "user" |
| Workflow | 3–7 bước, vẽ được trước/sau | Chỉ có ý tưởng feature |
| Bottleneck | Một bước, ước lượng được thời gian | "Toàn bộ quy trình chậm" |
| Evidence | Thời gian, tần suất, số người, log | "Em nghĩ là đau" |
| Metric | Baseline + target + cách đo | "Nhanh hơn", "tiện hơn" |
| Scope lab | Làm được validate + PS + decision trong 4 giờ | "Xây nền tảng AI cho công ty" |

---

## Đề tài nên **thận trọng** (dễ trượt scope hoặc thiếu evidence)

| Đề tài nghe hấp dẫn | Vì sao khó trong lab | Hướng thu hẹp |
|---|---|---|
| Chatbot trả lời mọi câu hỏi về công ty | Quá rộng, solution-first | Một loại câu hỏi lặp lại + một kênh (Discord FAQ) |
| AI tutor cá nhân hóa toàn bộ lộ trình học | Metric và boundary khó | Một môn, một bước: gợi ý ôn từ slide tuần này |
| Tự động review code thay senior | Rủi ro cao, cần data | AI chỉ checklist security/style trước khi người review |
| Dịch realtime mọi ngôn ngữ | Thiếu actor và workflow cụ thể | Một meeting notes: tóm tắt tiếng Việt từ transcript |
| Agent tự đặt lịch, tự email, tự follow-up | Agent quá sớm | Workflow: draft email nhắc deadline, human gửi |

---

## Gợi ý ghép nhóm đa dạng (cho coach)

Nếu 3–4 người trong nhóm có bối cảnh khác nhau, khuyến khích:

- Mỗi người mang 1 problem từ bối cảnh **khác** (học / intern / làm / CLB).
- Khi cluster, tìm **pattern workflow** (tổng hợp, tìm kiếm, review…) thay vì gom theo ngành.
- Chọn candidate mà **ít nhất 2 người** trong nhóm hiểu workflow đủ để validate.

---

## Liên kết tài liệu lab

- Hướng dẫn chi tiết từng phase: `01-worksheet.md`
- Ví dụ bài nộp hoàn chỉnh (Weekly Report): `02-deliverable-example.md`
- Câu hỏi coach khi đi vòng: `Question.md`

---

*Day 02 Lab — Problem Suggestion Bank*
