# Scenario — Kịch bản chạy buổi Lab Day 02

> Tài liệu dành cho **Lab Lead / Facilitator** và **Lab Coach**. Có lời dẫn cụ thể để đọc trước lớp, xen kẽ hướng dẫn cho coach đi vòng.
>
> **Thời lượng mục tiêu:** ~4h30 – 5h (gồm demo 5 nhóm). Có thể rút ngắn bằng cách giảm thời gian pitch hoặc chuyển Phase 7 về bài tập về nhà.

---

## Tổng quan 3 phần chính

| Phần | Nội dung | Phase worksheet | Thời gian gợi ý |
|---|---|---|---:|
| **Phần 1 — Cá nhân** | Scan problem, Problem Cards, chuẩn bị pitch | Phase 0, 1, 2 | ~75' + break 10' |
| **Phần 2 — Nhóm** | Hội tụ, validate, workflow, PS, quyết định AI | Phase 3, 4, 5, 6 | ~130' + break 10' |
| **Phần 3 — Demo & phản biện** | 5 nhóm trình bày, Q&A, rút bài học chung | (trình diễn output Phase 3–6) + Phase 7 | ~50' – 60' |

```text
[Mở buổi 5']
    ↓
Phần 1: Cá nhân — Phase 0 → 1 → 2          (~75')
    ↓
Break 1                                      (10')
    ↓
Phần 2: Nhóm — Phase 3 → 4 → 5 → 6         (~130')
    ↓
Break 2 / chuẩn bị demo                      (10')
    ↓
Phần 3: Demo & phản biện — 5 nhóm           (~50')
    ↓
Phase 7 Reflection + đóng buổi               (~15')
```

---

## Vai trò trong buổi lab

| Vai trò | Làm gì |
|---|---|
| **Lab Lead** | Đọc lời dẫn, giữ timebox, mở/đóng phần, điều phối demo |
| **Lab Coach** (1 coach / 2–3 nhóm) | Đi vòng, hỏi Socratic, không chốt giúp — tham chiếu `Question.md` |
| **Học viên** | Làm theo `01-worksheet.md`, tự pitch/challenge, tự quyết định |

**Tài liệu cần mở sẵn:**

- `01-worksheet.md` — học viên làm bài
- `02-deliverable-example.md` — Phase 0
- `Suggestion-problem.md` — khi ai đó bí ý tưởng
- `Question.md` — coach dùng khi ghé nhóm

---

## Trước buổi lab (15' chuẩn bị)

**Lab Lead checklist:**

- [ ] Chia nhóm 3–4 người (ghi số nhóm lên bảng/Discord)
- [ ] Gửi link repo lab + worksheet
- [ ] Chuẩn bị timer hiển thị (điện thoại/projector)
- [ ] Bảng hoặc slide ghi 6 nguyên tắc lab (từ đầu worksheet)
- [ ] Chuẩn bị form/slide **chọn 5 nhóm demo** (xem Phần 3)

**Lab Coach checklist:**

- [ ] Đọc `Question.md` — phần nguyên tắc chung
- [ ] Nhận danh sách nhóm phụ trách
- [ ] Không mang sẵn "đáp án đề tài" — chỉ mang câu hỏi

---

# MỞ BUỔI (5')

## Lab Lead — lời dẫn mở đầu

> Chào mọi người. Hôm nay là **Day 02 — Tìm đúng bài toán cho AI**.
>
> Buổi lab không phải để xây chatbot. Buổi lab để trả lời một câu hỏi khó hơn: **Vấn đề nào xung quanh mình thật sự đáng giải — và có cần AI không?**
>
> Chúng ta chia làm **3 phần**:
>
> 1. **Cá nhân** — mỗi người scan problem từ trải nghiệm thật, chuẩn bị pitch.
> 2. **Nhóm** — hội tụ về một candidate problem, validate, vẽ workflow, viết Problem Statement, chọn Rule / Workflow / Agent.
> 3. **Demo & phản biện** — **5 nhóm** được chọn trình bày trước lớp; cả lớp hỏi đáp, phản biện.
>
> Điểm cao **không** thuộc về ai chọn Agent. Điểm cao thuộc về ai **lập luận chặt**: actor rõ, workflow vẽ được, metric đo được, biết vì sao Go hoặc No-Go.
>
> Mở `01-worksheet.md`. Mọi người làm trong repo cá nhân; phần nhóm sẽ copy chung sau.
>
> Có **Lab Coach** đi vòng — coach sẽ hỏi, không trả lời thay. Đừng ngại bị hỏi "vì sao?".
>
> Bắt đầu Phần 1.

**Ghi bảng:**

```text
Problem first → Workflow → Metric → Boundary → Rule/Workflow/Agent → Go/Not Yet/No-Go
```

---

# PHẦN 1 — CÁ NHÂN (~75')

> **Output cá nhân khi hết Phần 1:** 5+ problems, top 3 Problem Cards, draft workflow trước/sau, biết card nào sẽ pitch với nhóm.

---

## Phase 0 — Worked Example (15')

### Lab Lead — lời dẫn

> **Phase 0 — 15 phút.** Mục tiêu: nhìn thấy bài nộp cuối trông như thế nào **trước khi** làm.
>
> Mở file `02-deliverable-example.md` — ví dụ **Weekly Report**.
>
> Khi đọc, chú ý 4 điểm:
>
> 1. Cá nhân scan **rộng** — 10 problems — rồi mới chọn top 3.
> 2. Nhóm **không** chọn Problem Statement ngay; nhóm chọn **một candidate problem** để đào sâu.
> 3. Workflow trước/sau cho thấy **bottleneck** và **human boundary** — ai review khi AI sai.
> 4. Problem Statement **v0** viết sau workflow; **v1** thêm AI intervention point sau khi chọn Rule/Workflow/Agent.
>
> 15 phút đọc im lặng hoặc thảo luận cặp nhanh. Hết giờ tôi hỏi nhanh 2 câu.

**Sau 12' — nhắc:**

> Còn 3 phút. Ai chưa đọc phần Group Convergence và Final Decision, nhảy tới đó.

**Hết 15' — check nhanh (2 câu, không gọi dài):**

> Câu 1: Candidate problem khác Problem Statement ở chỗ nào?
>
> *(Chờ 1–2 người trả lời — candidate là đề hẹp để đào sâu; PS là mô tả chặt sau validate/workflow.)*
>
> Câu 2: Trong ví dụ, bottleneck là bước nào?
>
> *(Đáp án kỳ vọng: viết narrative — 25 phút.)*
>
> Tốt. Phase 1 — mỗi người tự scan.

### Lab Coach — trong Phase 0

- Đứng quan sát; chưa cần đi vòng nhiều.
- Nếu ai hỏi "copy ví dụ được không": *"Học cách đi, không copy nội dung. Problem của bạn phải từ trải nghiệm của bạn."*

---

## Phase 1 — Individual Scan (25')

### Lab Lead — lời dẫn

> **Phase 1 — 25 phút.** Mục tiêu: **ít nhất 5 problems** từ trải nghiệm thật.
>
> Đây là bước **phân kỳ** — mỗi người list riêng, chưa cần thống nhất với nhóm.
>
> Dùng **4 lăng kính** trong worksheet:
>
> - **Lặp lại** — việc gì cứ xuất hiện đều đặn?
> - **Tốn thời gian** — mỗi lần làm nặng ở đâu?
> - **AI có thể tốt hơn** — bước nào cần đọc/viết/tổng hợp ngữ cảnh?
> - **Pain từ người khác** — ai hay phàn nàn, hỏi lại, mở ticket?
>
> Mỗi dòng ghi: **ai đang đau** và **dấu hiệu thật** — bao lâu, bao nhiêu lần/tuần, bao nhiêu người.
>
> **Được dùng AI** — nhưng **tự scan trước**, rồi mới hỏi AI gợi ý thêm. Bỏ ý không có trải nghiệm thật.
>
> Bí ý tưởng: mở `Suggestion-problem.md` để mở rộng góc nhìn — **không copy nguyên văn**.
>
> 25 phút. Bắt đầu.

**Sau 10':**

> Cảnh báo nhẹ: nếu list toàn "làm app AI" hoặc "chatbot cho mọi thứ" — quay lại **một người cụ thể** đang làm **một việc cụ thể** trong **một ngày cụ thể**.

**Sau 20':**

> Còn 5 phút. Đủ 5 dòng chưa? Nếu rồi, thêm 1–2 problem từ lăng kính bạn chưa dùng.

**Hết 25' — chuyển Phase 2:**

> Dừng scan. Phase 2 — chọn **top 3** và làm Problem Card. Không cần hoàn hảo; cần **đủ rõ để pitch**.

### Lab Coach — trong Phase 1

Ghé từng người, hỏi 1 câu:

- *"Problem này bạn quan sát trực tiếp hay đọc được?"*
- *"Ai đang đau — một người hay cả nhóm vai trò?"*
- *"Dấu hiệu thật là gì — ngoài cảm giác 'khó chịu'?"*

Nếu bí: gợi `Suggestion-problem.md`, không đưa đề sẵn.

---

## Phase 2 — Top 3 Problem Cards + draft workflow (35')

### Lab Lead — lời dẫn

> **Phase 2 — 35 phút.** Từ 5+ problems, chọn **top 3**.
>
> Mỗi problem cần:
>
> 1. **Problem Card** đủ field — actor, workflow 3–7 bước, bottleneck, metric, non-AI alternative.
> 2. **Draft workflow trước** — current state, ghi thời gian từng bước, đánh dấu bottleneck.
> 3. **Draft workflow sau** — future state; ai review; fallback nếu AI sai.
>
> Tiêu chí chọn top 3: actor rõ, vẽ được workflow, bottleneck **một bước**, metric ước lượng được.
>
> Cuối phase, điền: **"Card tôi muốn pitch nhất"** và **"Câu hỏi tôi muốn nhóm challenge"**.
>
> **Được dùng AI** để phản biện card — prompt trong worksheet: *"chỉ ra điểm yếu, đừng khen"*. Không để AI viết card thay.
>
> 35 phút. Sau phase này là **break 10 phút** — rồi sang **Phần 2 làm nhóm**.

**Sau 15':**

> Nhắc: bottleneck phải là **một bước** — không phải "cả quy trình chậm". Ví dụ: không phải "báo cáo tuần khó", mà là "bước viết narrative — 25 phút".

**Sau 28':**

> Còn 7 phút. Chọn xong card muốn pitch chưa? Ghi câu hỏi muốn nhóm challenge.

**Hết 35' — chốt Phần 1:**

> Dừng. Kiểm tra nhanh trước break:
>
> - [ ] Ít nhất 5 problems?
> - [ ] Top 3 có Problem Card?
> - [ ] Mỗi card có workflow trước/sau nháp?
> - [ ] Biết pitch card nào?
>
> Thiếu phần nào — ghi chú, break xong nhóm sẽ cần pitch ngay.
>
> **Break 10 phút.** Quay lại đúng giờ — Phần 2 bắt đầu bằng pitch, không chờ ai muộn.

### Lab Coach — trong Phase 2

- Ưu tiên người có card mơ hồ: *"Đọc problem 1 câu — người nghe có biết ai và khi nào không?"*
- Ai chọn Agent sớm: *"Rule hoặc checklist giải được bao nhiêu %? Vì sao chưa đủ?"*

---

## Break 1 (10')

### Lab Lead

> Break. 10 phút.
>
> Khi quay lại: ngồi đúng **nhóm 3–4 người**. Mỗi người sẽ pitch **3 candidates** — mỗi candidate **1–2 phút**.
>
> Chuẩn bị tinh thần bị hỏi. **Không dùng AI** để pitch hoặc challenge thay.

---

# PHẦN 2 — LÀM THEO NHÓM (~130')

> **Output nhóm khi hết Phần 2:** 1 candidate problem đã chọn, validation/research, workflow trước/sau, PS v0/v1, so sánh Rule/Workflow/Agent, Go/Not Yet/No-Go.

**Lab Lead — mở Phần 2:**

> Chào lại. **Phần 2 — làm theo nhóm.** Cả phần này khoảng **2 tiếng 10 phút**, chia 4 phase.
>
> Nguyên tắc nhóm:
>
> - Pitch và challenge **bằng miệng** — không AI nói thay.
> - Nhóm chọn **candidate problem**, chưa viết Problem Statement hoàn chỉnh ngay.
> - **No-Go** hoặc chọn **Rule** là kết luận tốt nếu lập luận đúng.
>
> Coach sẽ ghé từng nhóm. Bắt đầu Phase 3 — pitch.

---

## Phase 3 — Group Convergence (30')

### Lab Lead — lời dẫn

> **Phase 3 — 30 phút.** Nhóm có khoảng **9–12 candidates** (mỗi người 3).
>
> 4 bước — **không vote cảm tính ngay**:
>
> 1. **Trình bày** — mỗi người 3 candidates, mỗi candidate 1–2 phút.
> 2. **Gom cluster** — tìm pattern chung (tổng hợp, tìm kiếm, review…).
> 3. **Shortlist** — 2–3 candidate đáng đào sâu.
> 4. **Score 1–5** — bảng trong worksheet; chọn **1 candidate**.
>
> Pitch nói: problem, actor, bottleneck, impact — **không** kể solution trước.
>
> 30 phút. Tôi báo thời gian.

**Sau 10' (giữa pitch):**

> Nhóm đang ở candidate thứ mấy? Nếu chưa pitch xong — tăng tốc: 1 phút/candidate.

**Sau 20':**

> 10 phút cuối: phải có **1 candidate** và ghi **vì sao chọn / vì sao không chọn** các bài còn lại.

**Hết 30' — chốt:**

> Dừng Phase 3. Mỗi nhóm đọc to tên **candidate đã chọn** — 1 câu.
>
> *(Ghi nhanh lên bảng — dùng cho Phần 3 chọn nhóm demo.)*
>
> Phase 4 — validate pain có thật không.

### Lab Coach — trong Phase 3

- Đứng nghe pitch; không chen ngang.
- Khi nhóm shortlist: *"Ai trong nhóm hiểu workflow này sâu nhất? Đủ để validate không?"*
- Câu challenge gợi ý cho cả nhóm dùng với nhau:
  - *"Actor có đủ cụ thể không?"*
  - *"Rule đơn giản đã đủ chưa?"*
  - *"Có dấu hiệu thật ngoài người pitch không?"*

---

## Phase 4 — Validation + Research (30')

### Lab Lead — lời dẫn

> **Phase 4 — 30 phút.** Đã chọn candidate — giờ **kiểm chứng**, đừng đoán.
>
> **Bước 4.1 — Quick validation** (chọn ít nhất 1):
>
> - Hỏi nhanh 2–3 người ngoài nhóm (interview 3 phút/người), hoặc
> - Poll Discord 5–10 người, hoặc
> - Dùng log/ticket/review thật nếu có.
>
> Ghi: tín hiệu **xác nhận** và tín hiệu **phản bác**. Validation có thể làm bạn **sửa lại** problem.
>
> **Bước 4.2 — Research giải pháp đã có:**
>
> - Tìm 2–3 tool/case/pattern tương tự.
> - Họ giải bước nào? Khoảng trống còn lại là gì?
> - **Kiểm link** — không dùng số liệu AI đưa nếu chưa verify.
>
> 30 phút. Ưu tiên validate trước, research song song nếu chia việc được.

**Sau 15':**

> Nhắc: nếu chưa hỏi ai — gửi poll ngay. 5 câu trả lời cũng là bằng chứng.

**Hết 30':**

> Dừng. Nhóm nào validation làm **đổi** problem hoặc metric — giơ tay.
>
> *(Khuyến khích 1–2 nhóm chia sẻ ngắn — 30 giây.)*
>
> Phase 5 — workflow và Problem Statement.

### Lab Coach — trong Phase 4

- *"Đã hỏi bao nhiêu người? Có ai nói không đau không?"*
- *"Tool tìm được giải quyết hết chưa — vì sao vẫn đáng làm hoặc nên No-Go?"*

---

## Phase 5 — Workflow + Problem Statement (45')

### Lab Lead — lời dẫn

> **Phase 5 — 45 phút.** Phase dài nhất — làm kỹ workflow và **Problem Statement v0**.
>
> **5.1 — Current workflow:** mỗi bước có actor, input, output, thời gian, handoff. Chỉ rõ **bottleneck chính**.
>
> **5.2 — Future workflow:** bước nào Rule, bước nào AI hỗ trợ, bước nào người bắt buộc làm; **human boundary**; **fallback** nếu AI sai.
>
> Bảng before/after: tổng thời gian, số bước thủ công, risk mới.
>
> **5.3 — Problem Statement v0** — 6 field:
>
> Actor | Workflow | Bottleneck | Impact | Success Metric | Boundary
>
> Metric phải có **baseline + target + cách đo** — không chỉ "nhanh hơn".
>
> Được dùng AI vẽ Mermaid / phản biện PS — nhưng **tự kiểm từng bước**.
>
> 45 phút.

**Sau 20':**

> Kiểm tra: future workflow đã ghi **ai review** output AI chưa? Fallback là gì?

**Sau 38':**

> Còn 7 phút — ưu tiên chốt PS v0. Field nào còn mơ hồ nhất?

**Hết 45':**

> Dừng. **Break 10 phút.** Sau break: Phase 6 — chọn Rule / Workflow / Agent và quyết định cuối. Đây cũng là nội dung các nhóm sẽ demo.

### Lab Coach — trong Phase 5

- *"Nhìn workflow — bottleneck có nhìn ra ngay không?"*
- *"Boundary: nhóm **không** làm gì trong scope này?"*
- *"Metric baseline từ đâu ra?"*

---

## Break 2 (10')

### Lab Lead

> Break 10 phút.
>
> Sau break: **Phase 6 — 25 phút** để chốt quyết định.
>
> Song song: các nhóm nộp **tên nhóm + candidate + 1 câu pitch** vào form/sheet — tôi dùng để chọn **5 nhóm demo** ở Phần 3.
>
> *(Facilitator: mở form hoặc ghi nhận từ bảng Phase 3.)*

---

## Phase 6 — Rule / Workflow / Agent + Decision (25')

### Lab Lead — lời dẫn

> **Phase 6 — 25 phút.** Chốt **mức AI** và **quyết định Go / Not Yet / No-Go**.
>
> **6.0** — Xác định bài toán: độ mơ hồ thấp/cao? độ phức tạp thấp/cao?
>
> **6.1** — Điền bảng so sánh **Rule / Workflow / Agent** cho cùng một bài. Hỏi:
>
> - Rule giải được 70–80% case không?
> - Workflow đủ vì các bước đã rõ chưa?
> - Agent có thật sự cần **tự** quyết định bước tiếp theo không?
>
> **6.2** — Problem Statement **v1**: thêm AI intervention point, mức chọn, rủi ro & người review.
>
> **6.3** — Bảng câu hỏi Yes/Not Yet/No → Decision + lý do.
>
> Nếu **Go**: pilot nhỏ nhất là gì? Nếu **No-Go**: làm gì thay AI?
>
> 25 phút — xong là nhóm **sẵn sàng demo**.

**Sau 18':**

> Còn 7 phút. Phải có dòng **Go / Not Yet / No-Go** và **một lý do** dựa trên evidence — không phải "vì muốn làm AI".

**Hết 25' — chốt Phần 2:**

> Hết Phần 2. Mỗi nhóm:
>
> - [ ] Workflow trước/sau
> - [ ] PS v1
> - [ ] So sánh Rule/Workflow/Agent
> - [ ] Decision có lý do
>
> Copy bản nhóm vào repo cá nhân sau buổi học.
>
> **10 phút chuẩn bị demo** — tôi công bố 5 nhóm trình bày.

### Lab Coach — trong Phase 6

- Ép so sánh đủ 3 mức — không nhảy thẳng Agent.
- *"No-Go với lý do chặt — điểm tốt. Process fix thay AI là gì?"*

---

# PHẦN 3 — DEMO & PHẢN BIỆN (~50' – 60')

> **Mục tiêu:** 5 nhóm trình bày artifact; cả lớp luyện phản biện; rút pattern chung. Đây là phần thay thế cho "kiểm tra hiểu bài" quy mô lớn.

---

## Chọn 5 nhóm demo (trong break / đầu Phần 3)

### Tiêu chí chọn — Lab Lead dùng nội bộ

Chọn **đa dạng**, không chỉ chọn bài "đẹp":

| Ưu tiên | Lý do |
|---|---|
| 1 nhóm **Go + Workflow** | Ví dụ chuẩn problem-first |
| 1 nhóm **Go + Rule** | Cho thấy không cần AI vẫn mạnh |
| 1 nhóm **Not Yet** | Lập luận thận trọng, metric chưa đủ |
| 1 nhóm **No-Go** | Dũng cảm kết luận không dùng AI |
| 1 nhóm **còn lỗ hổng rõ** | Cả lớp luyện challenge (coach chỉ định nhẹ) |

**Cân bằng:** không toàn PM, không toàn sinh viên; có bài học tập và bài đi làm.

### Lab Lead — lời dẫn công bố (2')

> **Phần 3 — Demo & phản biện.**
>
> 5 nhóm sau sẽ pitch **4 phút**, sau đó lớp và tôi hỏi **4 phút**:
>
> *(Đọc tên 5 nhóm — ví dụ:)*
>
> 1. Nhóm 2 — Weekly lab progress summary  
> 2. Nhóm 5 — Tìm quyết định cũ trên Discord  
> 3. Nhóm 1 — Checklist nộp bài thiếu field  
> 4. Nhóm 7 — Review PRD trước comment  
> 5. Nhóm 4 — No-Go: chatbot FAQ lớp học  
>
> Nhóm không demo: vẫn chấm điểm đầy đủ từ bản nộp. Dùng 8 phút này làm **reflection cá nhân** (Phase 7) im lặng.
>
> Format pitch — **4 phút**, không slide dài:
>
> 1. Actor + problem 1 câu (30 giây)
> 2. Workflow trước — bottleneck (1 phút)
> 3. Workflow sau + human boundary (1 phút)
> 4. Metric + Rule/Workflow/Agent + **Go/Not Yet/No-Go** (1.5 phút)

---

## Format từng nhóm demo (8' / nhóm × 5 = 40')

### Lab Lead — trước mỗi nhóm (15 giây)

> Nhóm [X]. [Tên thành viên pitch]. 4 phút. Bắt đầu.

**Timer 4' — giơ biển "1 phút" / "30 giây"**

### Sau pitch — Lab Lead mở Q&A (4')

> Cả lớp và coach — **2–3 câu hỏi**, không speech. Ưu tiên câu **challenge**, không hỏi gợi ý solution.

**Ngân hàng câu hỏi phản biện — Lab Lead / cả lớp:**

| Hướng | Câu hỏi mẫu |
|---|---|
| Actor | "Ai cụ thể — một vai trò hay 'mọi sinh viên'?" |
| Evidence | "Số liệu baseline từ đâu — validate hay ước lượng cá nhân?" |
| Bottleneck | "Bottleneck có phải một bước không — hay cả flow?" |
| Metric | "Target 30 phút — đo bằng stopwatch hay survey sau 2 tuần?" |
| Alternative | "Template Notion đơn giản đã thử chưa — vì sao chưa đủ?" |
| AI level | "Vì sao không hạ từ Agent xuống Workflow?" |
| Risk | "AI sai narrative — ai phát hiện, trong bao lâu?" |
| No-Go | "Nếu No-Go — đề xuất process fix cụ thể nhất là gì?" |

**Sau Q&A — Lab Lead chốt 1 câu (30 giây):**

> Cảm ơn nhóm [X]. Điểm mạnh: [1 câu cụ thể]. Chỗ cần làm chặt hơn nếu làm tiếp: [1 câu cụ thể].

### Lab Coach — trong demo

- Không sửa giúp khi nhóm đang pitch.
- Ghi 1–2 câu hỏi hay từ học viên để Lab Lead khen ở cuối buổi.
- Nhóm không demo: coach nhắc làm Phase 7 reflection.

---

## Sau 5 nhóm — rút bài học chung (8')

### Lab Lead — lời dẫn

> Vừa nghe 5 nhóm — 3 pattern tôi thấy:
>
> 1. Nhóm nào nói rõ **một bước nghẽn** — dễ tin hơn nhóm nói "cả quy trình chậm".
> 2. Nhóm có **validation** — kể cả 5 người poll — metric đáng tin hơn.
> 3. Nhóm chọn **Rule** hoặc **No-Go** có lý do — không thua nhóm chọn Agent.
>
> Câu hỏi mở cho cả lớp — **1 phút suy nghĩ**, rồi 2–3 người giơ tay:
>
> *"Sau buổi này, bước nào trong quy trình làm product AI bạn sẽ **không** nhảy qua?"*
>
> *(Nhận 2–3 ý — kỳ vọng: workflow, metric, validate, không chọn Agent sớm.)*

---

# PHASE 7 — INDIVIDUAL REFLECTION (15')

> Có thể làm **song song** khi 5 nhóm demo (nhóm không demo) hoặc **sau demo** cả lớp.

### Lab Lead — lời dẫn

> **Phase 7 — 15 phút reflection cá nhân.** Không AI viết thay.
>
> Mở worksheet Phase 7. Trả lời trung thực:
>
> - Tôi đóng góp gì vào artifact nhóm?
> - AI hỗ trợ phase nào — sai/hời hợt ở đâu?
> - Nhóm có lúc solution-first không?
> - Nếu làm lại, tôi challenge ở điểm nào mạnh hơn?
>
> Đây là phần **điểm cá nhân** — copy vào `03-individual-reflection/` trong repo.
>
> 15 phút im lặng.

**Hết 15':**

> Dừng. Nộp repo theo hướng dẫn `README.md` — deadline [ghi deadline].

---

# ĐÓNG BUỔI (5')

### Lab Lead — lời dẫn kết

> Kết thúc Day 02.
>
> Hôm nay các bạn đi đúng mạch:
>
> **Problem → Workflow → Metric → Boundary → Rule/Workflow/Agent → Quyết định**
>
> Không phải nhóm nào cũng cần AI. Nhóm nào biết **No-Go** với lý do chặt — đó là năng lực product thật.
>
> Việc về nhà:
>
> 1. Hoàn thiện repo cá nhân — đủ 3 folder: scan, bản nhóm, reflection.
> 2. Nhóm không demo: tự luyện pitch 2 phút từ artifact — phòng vấn sau nếu cần.
> 3. Bonus: đăng 1 insight lên Discord — problem nào khiến bạn đổi ý sau khi bị challenge.
>
> Cảm ơn các coach. Hẹn [buổi tiếp theo / deadline nộp bài].

---

## Bảng thời gian tổng hợp (in cho Lab Lead)

| Thời điểm | Phút tích lũy | Nội dung |
|---|---:|---|
| 0:00 | 0 | Mở buổi |
| 0:05 | 5 | Phase 0 — Worked Example |
| 0:20 | 20 | Phase 1 — Individual Scan |
| 0:45 | 45 | Phase 2 — Problem Cards |
| 0:80 | 80 | Break 1 |
| 0:90 | 90 | Phase 3 — Group Convergence |
| 1:20 | 120 | Phase 4 — Validation + Research |
| 1:50 | 150 | Phase 5 — Workflow + PS |
| 2:35 | 155 | Break 2 |
| 2:45 | 165 | Phase 6 — Decision |
| 3:10 | 190 | Chuẩn bị demo + chọn 5 nhóm |
| 3:20 | 200 | Phần 3 — Demo nhóm 1–2 |
| 3:36 | 216 | Demo nhóm 3–4 |
| 3:52 | 232 | Demo nhóm 5 + rút bài học |
| 4:00 | 240 | Phase 7 — Reflection |
| 4:15 | 255 | Đóng buổi |

*Tổng ~4h15. Điều chỉnh: rút Phase 5 xuống 35' nếu cần gọn 4h.*

---

## Xử lý tình huống phát sinh

| Tình huống | Cách xử lý |
|---|---|
| Nhóm chưa chốt candidate ở Phase 3 | Cho thêm 5' từ Phase 4; Facilitator chốt timebox cứng |
| Ít hơn 5 nhóm trong lớp | Demo tất cả; mỗi nhóm 6–7 phút |
| Nhóm muộn sau break | Không chờ; pitch cuối trong nhóm, có thể pitch 2 candidates thay vì 3 |
| Cả lớp solution-first | Dừng 2 phút: *"Ai là actor? Workflow hiện tại mấy bước?"* — quay lại |
| Demo quá giờ | Cắt Q&A còn 2 câu/nhóm; reflection về nhà |
| Không có nhóm No-Go | Lab Lead đóng vai skeptical: *"Tôi challenge: có cần AI không?"* trong Q&A |

---

## Phụ lục — Script ngắn cho Lab Coach

**Khi ghé nhóm lần đầu (Phần 2):**

> Nhóm đang ở phase nào? Candidate đã chọn chưa? Tôi hỏi 1 câu thôi.

**Khi nhóm xong Phase 6:**

> Đọc cho tôi decision và **một lý do** — 20 giây.

**Khi nhóm được chọn demo:**

> 4 phút — nói bottleneck và metric trước. Đừng giải thích tool.

---

*Tài liệu liên quan: `01-worksheet.md` · `Question.md` · `Suggestion-problem.md` · `README.md`*

*Day 02 Lab — Facilitator Scenario*
