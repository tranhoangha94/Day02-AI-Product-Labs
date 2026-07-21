# Câu hỏi Lab Coach — Day 02

> Tài liệu này dành cho Lab Coach khi đi vòng quanh các nhóm trong lab 4 tiếng. Mục tiêu không phải trả lời thay nhóm, mà **ép nhóm nói rõ lập luận**, phát hiện chỗ mơ hồ, và giữ đúng nguyên tắc **problem first, not AI first**.

## Cách dùng

- Hỏi **1–2 câu mỗi lần ghé nhóm**, không phỏng vấn liên tục.
- Ưu tiên câu hỏi mở: *"Vì sao?"*, *"Đo thế nào?"*, *"Ai làm bước đó?"*
- Nếu nhóm đang đi đúng hướng, hỏi câu **challenge sâu hơn** thay vì gợi ý giải pháp.
- Nếu nhóm bí, dùng câu **gợi mở** — không đưa luôn đề tài hay chốt Rule/Workflow/Agent thay họ.
- Phase 3 (pitch + challenge) và Phase 7 (reflection): **không dùng AI thay người** — coach cũng không viết giúp.

---

## Nguyên tắc chung (dùng xuyên suốt lab)

| Khi nhóm… | Coach có thể hỏi |
|---|---|
| Nói về công nghệ / chatbot / agent trước | "Trước khi nói AI, workflow hiện tại của người đó gồm mấy bước? Bước nào đau nhất?" |
| Mô tả problem chung chung | "Ai cụ thể đang gặp? Lần gần nhất xảy ra khi nào? Mất bao lâu?" |
| Metric mơ hồ ("nhanh hơn", "tốt hơn") | "Baseline hiện tại là bao nhiêu? Sau cải thiện muốn đạt con số gì? Đo bằng cách nào?" |
| Chọn Agent quá sớm | "Rule hoặc checklist đơn giản có giải được 70–80% case không? Vì sao chưa thử mức đó?" |
| Không có bằng chứng | "Dấu hiệu thật ở đâu — log, ticket, thời gian, số người, hay chỉ là cảm giác cá nhân?" |
| Boundary không rõ | "AI được phép làm đến đâu? Bước nào bắt buộc có người kiểm tra? Nếu AI sai thì sao?" |

---

## Phase 0 — Worked Example (15')

**Mục tiêu coach:** Đảm bảo cả nhóm hiểu output cuối trước khi làm.

- "Sau khi đọc ví dụ, phần nào khác nhất giữa *candidate problem* và *Problem Statement*?"
- "Trong ví dụ Weekly Report, bottleneck là bước nào — và họ đo impact thế nào?"
- "Nhóm có thể tóm tắt được mạch: scan → hội tụ → validate → workflow → PS → Rule/Workflow/Agent → Go/Not Yet/No-Go không?"

---

## Phase 1 — Individual Scan (25')

**Mục tiêu coach:** Mỗi người scan từ trải nghiệm thật, đủ 5+ problems, đa dạng lăng kính.

### Gợi mở khi học viên bí ý tưởng

- "Tuần trước bạn mất nhiều thời gian nhất vào việc gì?"
- "Việc gì bạn hay trì hoãn vì nhàm hoặc rối?"
- "Ai hay hỏi lại bạn cùng một câu? Bao nhiêu lần/tuần?"
- "Có workflow nào ở trường/công ty mà ai cũng biết là chậm không?"

### Kiểm tra chất lượng scan

- "Problem này thuộc lăng kính nào — lặp lại, tốn thời gian, AI có thể giúp, hay pain từ người khác?"
- "Ai đang đau? Một người hay một nhóm vai trò?"
- "Dấu hiệu thật là gì — thời gian, tần suất, số người, hay artifact cụ thể?"
- "Nếu không sửa, hậu quả là gì — chỉ khó chịu hay ảnh hưởng deadline/chất lượng?"

### Cảnh báo sớm

- "Danh sách này có problem nào bạn chưa từng trải nghiệm hoặc quan sát trực tiếp không?"
- "Có problem nào nghe giống 'làm app AI' hơn là pain thật không?"

---

## Phase 2 — Top 3 Problem Cards + draft workflow (35')

**Mục tiêu coach:** Top 3 đủ cụ thể để pitch; có workflow trước/sau nháp.

### Chọn top 3

- "Vì sao rank 1 quan trọng hơn rank 2? Impact khác nhau thế nào?"
- "Bài nào vẽ được workflow rõ nhất trong 3 bài?"
- "Bài nào có metric đo được mà không cần đoán mò?"

### Problem Card

- "Đọc problem 1 câu của bạn — người nghe có biết ngay *ai* và *khi nào* gặp không?"
- "Bottleneck là **một bước** hay cả một quy trình dài?"
- "Non-AI alternative là gì? Template, quy trình, checklist đã thử chưa?"
- "Quick gut của bạn là Rule/Workflow/Agent — vì sao? Điều gì còn chưa chắc?"

### Draft workflow

- "Trong current workflow, bước nào do ai làm? Handoff qua ai?"
- "Future workflow giảm thời gian ở bước nào — và **ai** vẫn phải review?"
- "Nếu AI draft tệ, fallback là gì?"

### Chuẩn bị pitch

- "Bạn muốn nhóm challenge điểm yếu nào của card bạn?"
- "Câu hỏi nào bạn **không** trả lời được nếu bị hỏi ngay bây giờ?"

---

## Break 1 (10')

- "Mỗi người đã chọn xong card muốn pitch chưa? Ai pitch đầu tiên?"

---

## Phase 3 — Group Convergence (30')

**Mục tiêu coach:** Nhóm hội tụ bằng lập luận, không vote theo cảm tính. **Không dùng AI thay pitch/challenge.**

### Bước 3.1 — Trình bày top 3

- "Pitch trong 1–2 phút: problem, actor, bottleneck, vì sao đáng làm — không kể solution."
- "Workflow future của bạn thay đổi **một bước** hay cả chuỗi?"
- "Impact của bạn đo bằng gì — phút, lần/tuần, số người, hay chất lượng?"

### Bước 3.2 — Gom cluster

- "Hai candidate này có cùng actor và cùng bottleneck không, hay chỉ giống từ khóa?"
- "Cluster này pattern chung là gì — tổng hợp thông tin, tìm kiếm, review, hay follow-up?"

### Bước 3.3 — Shortlist

- "Trong nhóm, ai hiểu workflow thật của candidate này sâu nhất?"
- "Candidate này có quá rộng để làm xong trong lab hôm nay không?"
- "Có so sánh được No AI / Rule / Workflow / Agent không — hay mới chỉ nghĩ đến chatbot?"

### Bước 3.4 — Score và chốt

- "Điểm cao nhất vì tiêu chí nào — actor, evidence, hay nhóm hiểu domain?"
- "Candidate bị loại vì lý do gì — không phải vì 'ít thích'?"
- "Nếu có disagreement, nhóm ghi lại được vì sao chưa đồng thuận 100% không?"

### Câu challenge mẫu (coach có thể nhắc nhóm dùng với nhau)

- "Actor có đủ cụ thể không — hay đang nói 'mọi người'?"
- "Bottleneck có phải một bước đo được thời gian không?"
- "Có dấu hiệu thật ngoài trải nghiệm của người pitch không?"
- "Rule/process fix đơn giản đã đủ chưa? Vì sao chưa?"
- "Nếu không dùng AI, bài này còn đáng làm không?"

---

## Phase 4 — Validation + Research (30')

**Mục tiêu coach:** Pain có bằng chứng; biết giải pháp đã có trên thị trường.

### Quick validation

- "Nhóm validate bằng interview, survey, hay log — tại sao chọn cách đó?"
- "Đã hỏi bao nhiêu người? Có tín hiệu **phản bác** không?"
- "Kết quả validate có làm nhóm sửa lại problem hoặc actor không?"
- "Nếu chưa kịp hỏi ai, giả định nào đang được coi là sự thật?"

### Research giải pháp

- "Đã tìm được tool/case nào giải bài tương tự chưa? Họ xử lý bước nào trong workflow?"
- "Khoảng trống còn lại là gì — vì sao nhóm vẫn thấy đáng làm?"
- "Link nguồn đã kiểm chưa? Claim nào AI/search đưa ra mà nhóm **chưa** verify?"

### Sau research

- "Research có làm nhóm đổi metric, boundary, hoặc hạ từ Agent xuống Workflow/Rule không?"
- "Có phát hiện bài toán này **không cần AI** không?"

---

## Phase 5 — Workflow + Problem Statement (45')

**Mục tiêu coach:** Workflow trước/sau rõ; PS v0 đủ 6 field.

### Current workflow

- "Mỗi bước: ai làm, input gì, output gì, mất bao lâu?"
- "Bottleneck chính — một bước hay nhiều bước cùng nghẽn?"
- "Handoff giữa các bước qua kênh nào — chat, email, doc, ticket?"

### Future workflow

- "Bước nào Rule xử lý, bước nào AI hỗ trợ, bước nào người bắt buộc làm?"
- "Human boundary nằm ở đâu — trước gửi, trước quyết định, hay trước publish?"
- "Phương án quay về nếu AI sai là gì — ai phát hiện, trong bao lâu?"

### Before / after impact

- "Tổng thời gian trước/sau — con số từ đâu ra?"
- "Có risk mới nào khi thêm AI/automation không — sai sót, hallucination, phụ thuộc tool?"

### Problem Statement v0

- "Đọc 6 field — field nào còn mơ hồ nhất?"
- "Success metric: baseline, target, và cách đo đã đủ chưa?"
- "Boundary: nhóm **không** làm gì trong scope lab này?"
- "PS v0 có nhảy sang giải pháp quá sớm không — hay vẫn mô tả problem?"

---

## Break 2 (10')

- "PS v0 đã có metric số chưa? Future workflow đã ghi human boundary chưa?"

---

## Phase 6 — Rule / Workflow / Agent + Decision (25')

**Mục tiêu coach:** So sánh đủ 3 mức; quyết định Go/Not Yet/No-Go có lý do.

### Ma trận độ phù hợp

- "Bài toán nhóm: độ mơ hồ thấp hay cao? Độ phức tạp thấp hay cao?"
- "Output mỗi lần có thể khác nhau mà vẫn chấp nhận được không?"
- "AI có cần **tự** quyết định bước tiếp theo không — hay chỉ hỗ trợ một bước cố định?"

### So sánh Rule / Workflow / Agent

- "Rule giải được phần nào của workflow? Case nào Rule không đủ?"
- "Workflow đủ vì các bước đã khá rõ — vì sao chưa cần Agent?"
- "Nếu chọn Agent: cần gọi tool, lập kế hoạch, hay đổi hướng giữa chừng không?"
- "Vì sao **không** chọn mức đơn giản hơn mức đang chọn?"

### Problem Statement v1

- "AI intervention point — chính xác là bước nào trong workflow?"
- "Ai review output AI? Tiêu chí pass/fail là gì?"

### Final decision

- "Go / Not Yet / No-Go — lý do dựa trên evidence nào, không phải 'muốn làm AI'?"
- "Nếu Go: pilot nhỏ nhất là gì — 1 user, 1 tuần, 1 loại input?"
- "Nếu Not Yet: cần validate gì trước khi Go?"
- "Nếu No-Go: phương án thay AI là gì — process, template, tool có sẵn?"

### Checklist nhanh trước khi nhóm kết thúc phase

| Câu hỏi | Coach nghe nhóm tự trả lời |
|---|---|
| Actor và workflow đã rõ chưa? | |
| Baseline và metric đo được chưa? | |
| Có data/input đủ dùng chưa? | |
| AI sai thì hậu quả chấp nhận được không? | |
| Có owner review vận hành không? | |
| Có cách non-AI đơn giản hơn không? | |

---

## Phase 7 — Individual Reflection (15')

**Mục tiêu coach:** Reflection cá nhân, trung thực — không AI viết thay.

- "Bạn đóng góp gì **cụ thể** vào artifact nhóm — không chỉ 'tham gia thảo luận'?"
- "Lúc nào nhóm (hoặc bạn) suýt bị solution-first?"
- "Bạn có đổi ý sau khi bị challenge không — vì điều gì?"
- "AI hỗ trợ phase nào hữu ích nhất? Phase nào AI hời hợt hoặc sai?"
- "Nếu làm lại lab, bạn sẽ challenge nhóm ở điểm nào mạnh hơn?"

---

## Câu hỏi theo rubric (khi gần hết lab)

Dùng khi nhóm tưởng đã xong nhưng artifact còn thiếu điểm rubric.

| Thành phần điểm | Coach hỏi |
|---|---|
| Workflow trước/sau (15) | "Nhìn vào 2 workflow — bottleneck và human boundary có nhìn ra ngay không?" |
| PS + metric + boundary (20) | "Metric có baseline và target số không? Boundary có nói rõ *không làm* gì không?" |
| Phù hợp AI + thay thế (15) | "Nhóm đã điền đủ Rule, Workflow, Agent và giải thích vì sao loại từng mức chưa?" |
| Quyết định cuối (10) | "Go/Not Yet/No-Go có map với research và rủi ro thật không?" |
| Scan + Problem Cards (12) | "Mỗi người có 5+ problems và top 3 đủ để người khác hiểu không?" |
| Pitch + challenge (12) | "Ai đã challenge ai — có câu hỏi làm sửa problem/metric không?" |

---

## Tình huống thường gặp — cách coach can thiệp

| Tình huống | Hướng xử lý |
|---|---|
| Nhóm chọn đề "xây chatbot cho mọi thứ" | "User cụ thể là ai? Một câu hỏi điển hình họ hỏi là gì? Workflow hiện tại họ trả lời thế nào?" |
| Hai người im, một người nói hết | "Người chưa pitch: top 1 của bạn khác gì bài nhóm đang chọn?" |
| Metric chỉ có "tiết kiệm thời gian" | "Bao nhiêu phút/lần hiện tại? Muốn còn bao nhiêu? Đo bằng stopwatch hay log?" |
| Chốt Agent vì "ngầu" | "Nếu chỉ cần AI gợi ý draft một bước, Workflow có đủ không? Agent thêm gì mà Workflow không làm được?" |
| Không có validation | "Trong 10 phút còn lại, hỏi được 2 người ngoài nhóm không? Poll Discord 5 người được không?" |
| Copy problem từ gợi ý nguyên văn | "Bạn quan sát pain này ở đâu — lớp, thực tập, CLB? Dấu hiệu thật của **bạn** là gì?" |
| No-Go nhưng ngại | "No-Go với lý do chặt là điểm tốt. Process fix đơn giản nhất nhóm đề xuất là gì?" |

---

## Giọng điệu coach

**Nên:** tò mò, skeptical nhẹ, khích lệ khi nhóm tự sửa lời nói của mình.  
**Không nên:** chốt giúp đề tài, viết Problem Statement, hoặc nói "đề này chắc chắn nên dùng Agent".

---

*Day 02 Lab — Lab Coach Playbook*
