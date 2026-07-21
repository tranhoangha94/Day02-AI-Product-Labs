# Ví dụ Candidate Problem + Workflow + Pain Point

> File này cho học viên **nhìn mẫu** trước khi tự scan. Mỗi ví dụ chỉ dừng ở mức **candidate problem** + **workflow hiện tại** + **xác định pain point ở bước nào** — chưa phải bài nộp hoàn chỉnh.
>
> **Không copy nguyên văn.** Hãy thay actor, số phút, và workflow bằng trải nghiệm thật của bạn.
>
> Bài nộp đầy đủ: xem `02-deliverable-example.md`.

---

## Cách đọc workflow và tìm pain point

Trước khi nói AI, hãy trả lời 4 câu:

1. **Ai** làm từng bước?
2. **Mỗi bước** mất khoảng bao lâu?
3. Bước nào **tốn nhiều nhất** hoặc **hay bị kẹt / phải làm lại**?
4. Nếu chỉ cải **một bước**, impact có đáng kể không?

**Pain point (bottleneck)** thường là bước:

- Mất **nhiều thời gian nhất** so với các bước khác.
- Cần **hiểu ngữ cảnh** — không chỉ copy/paste.
- **Hay lỗi** → phải quay lại làm lại bước sau.
- **Chờ người khác** hoặc **tìm thông tin rời rạc**.

Ký hiệu trong các sơ đồ dưới đây:

```text
[Bước: thời gian]           ← bước bình thường
[Bước: thời gian]  ⚠️ PAIN  ← pain point / bottleneck chính
[Bước: thời gian]  ✓ nhanh  ← bước nhẹ, ít khi là bottleneck
```

---

## Ví dụ 1 — Tìm lại quyết định cũ trên Discord (học tập)

### Candidate problem

> Sinh viên mất khoảng 15 phút mỗi lần cần tìm lại quyết định của lớp (đổi deadline, format nộp bài, cách làm lab) vì thông tin nằm rải rác trong nhiều thread Discord.

| Field | Nội dung |
|---|---|
| **Actor** | Sinh viên đang làm bài tập / lab, cần tra cứu quyết định đã chốt vài tuần trước |
| **Bối cảnh** | Trước deadline nộp bài, hoặc khi làm lab và không chắc rubric |
| **Dấu hiệu thật** | 2–3 lần/tuần; mỗi lần 10–20 phút; hay hỏi lại TA cùng một câu |
| **Tần suất** | Mỗi khi có assignment mới hoặc sau 1–2 tuần không đọc Discord |

### Workflow hiện tại

```text
CURRENT STATE — ~15 phút/lần

[Sinh viên nhớ "hình như đã nói trên Discord": 1']
    ↓
[Search keyword trong Discord — deadline, nộp bài, lab: 3']
    ↓
[Đọc lần lượt 4–6 thread không liên quan: 6']  ⚠️ PAIN — bottleneck
    ↓
[Đọc thread đúng nhưng comment dài, phải lọc quyết định cuối: 4']
    ↓
[Không chắc → hỏi TA/bạn trên group: 3' + chờ phản hồi]
    ↓
[Ghi lại vào note cá nhân: 1']
```

### Pain point nằm ở bước nào?

| Bước | Vì sao / vì sao không phải pain chính |
|---|---|
| Search keyword | Chỉ 3 phút — đau nhưng chưa phải nặng nhất |
| **Đọc nhiều thread sai + lọc quyết định** | **⚠️ Bottleneck** — 6–10 phút, hay lặp lại, dễ đọc nhầm thread cũ |
| Hỏi lại TA | Hậu quả của bottleneck trên — không phải gốc workflow |
| Ghi note | Bước phòng thủ sau cùng — tốn ít thời gian |

**Tóm 1 câu:** Pain nằm ở bước **đọc và lọc thông tin từ nhiều thread** — không phải ở bước search hay hỏi TA.

**Quick gut (chưa chốt):** Workflow — AI có thể hỗ trợ tóm tắt thread hoặc trả lời từ FAQ đã chốt.

---

## Ví dụ 2 — Nộp bài thiếu field, bị trả về (học tập)

### Candidate problem

> Sinh viên nộp assignment trên LMS bị trả về 1–2 lần vì thiếu field hoặc sai format file — mỗi vòng mất thêm 20–30 phút sửa và chờ xác nhận.

| Field | Nội dung |
|---|---|
| **Actor** | Sinh viên nộp bài cuối kỳ / lab có rubric chi tiết |
| **Bối cảnh** | 1–2 giờ trước deadline |
| **Dấu hiệu thật** | 30–40% lớp từng bị trả ít nhất 1 lần; TA nhắc lặp trên Discord |
| **Tần suất** | Mỗi môn có 2–4 assignment/ học kỳ |

### Workflow hiện tại

```text
CURRENT STATE — ~45 phút (lần nộp đầu + sửa lại)

[Đọc đề bài trên LMS: 5']  ✓
    ↓
[Làm bài trong Word/Code: 25']  ✓ (không phải pain của bài toán này)
    ↓
[Export / đặt tên file theo cảm giác: 3']  ✓
    ↓
[Đối chiếu checklist rubric + field bắt buộc: 2' hoặc... bỏ qua: 0']  ⚠️ PAIN
    ↓
[Upload LMS + điền metadata: 5']  ✓
    ↓
[Nhận email/trả bài thiếu PDF phụ lục: —]
    ↓
[Sửa + nộp lại + chờ TA: 20']  ⚠️ hậu quả
```

### Pain point nằm ở bước nào?

| Bước | Vì sao / vì sao không phải pain chính |
|---|---|
| Làm nội dung bài | Tốn thời gian nhưng **không phải** lý do bị trả bài |
| **Đối chiếu checklist trước khi nộp** | **⚠️ Bottleneck** — bước bị **bỏ qua** hoặc làm qua loa; thiếu 1 field → cả vòng nộp lại |
| Upload | Thao tác ngắn nếu file đã đúng |
| Sửa + nộp lại | **Hậu quả**, không phải gốc — gốc là không check trước |

**Tóm 1 câu:** Pain nằm ở bước **đối chiếu yêu cầu nộp bài trước khi upload** — một bước ngắn nhưng hay bị skip.

**Quick gut (chưa chốt):** **Rule** — checklist cố định, validate file trước submit; có thể chưa cần AI.

```text
Gợi ý future state (nháp) — Rule đủ?

[Làm bài: 25']
    ↓
[Checklist tự động: đủ field? đúng định dạng? đúng tên file?: 1']
    ↓
[Upload: 5']
    ↓
[Không bị trả vì thiếu format]
```

---

## Ví dụ 3 — Intern hiểu task từ Slack + Jira + doc (thực tập)

### Candidate problem

> Intern mới mất khoảng 40 phút để hiểu một task được giao vì mô tả nằm rải rác giữa Slack thread, ticket Jira và Google Doc — phải tự nối lại thành một việc cần làm.

| Field | Nội dung |
|---|---|
| **Actor** | Intern dev/product, tuần đầu–đầu tháng thứ 2 |
| **Bối cảnh** | Sáng thứ Hai nhận task mới từ mentor qua Slack |
| **Dấu hiệu thật** | 3–4 task/tuần × 30–45 phút; mentor phải giải thích lại 1–2 lần/tuần |
| **Tần suất** | Mỗi task mới có nhiều nguồn tham chiếu |

### Workflow hiện tại

```text
CURRENT STATE — ~40 phút/task

[Đọc tin nhắn Slack "làm ticket JIRA-123": 2']  ✓
    ↓
[Mở Jira — đọc title + description ngắn: 5']  ✓
    ↓
[Thấy link Google Doc spec — mở đọc 8 trang: 15']  ✓
    ↓
[Quay lại Slack đọc thread 20 tin nhắn tìm quyết định: 12']  ⚠️ PAIN — bottleneck
    ↓
[Tự viết lại "task của tôi là gì" vào note: 4']
    ↓
[Hỏi mentor "em hiểu đúng chưa?": 5' + chờ]
```

### Pain point nằm ở bước nào?

| Bước | Vì sao / vì sao không phải pain chính |
|---|---|
| Đọc Jira | Description thường thiếu context đầy đủ — nhưng chỉ 5 phút |
| Đọc Google Doc | Dài nhưng **có cấu trúc** — 15 phút, ít khi đọc nhầm hoàn toàn |
| **Đọc Slack thread tìm quyết định** | **⚠️ Bottleneck** — tin nhắn xen kẽ, quyết định cuối không rõ, phải đoán ý mentor |
| Viết lại task | Hệ quả của chưa hiểu rõ — intern tự tóm để giảm rủi ro |
| Hỏi mentor | Chi phí thêm — có thể giảm nếu bước trên rõ hơn |

**Tóm 1 câu:** Pain nằm ở bước **nối context từ Slack thread** — không phải ở đọc Jira hay đọc doc dài.

**Quick gut (chưa chốt):** Workflow — tóm tắt thread + link doc thành "task brief" một trang; mentor review brief trước khi intern code.

```text
FUTURE STATE (nháp) — ~18 phút

[Slack + Jira + Doc → workflow gom link: 2']
    ↓
[AI/tóm tắt: scope, done criteria, link quan trọng: 2']
    ↓
[Intern đọc brief 1 trang: 5']
    ↓
[Mentor confirm brief — 5 phút async: 5']  ← human boundary
    ↓
[Bắt đầu làm task]
```

---

## Ví dụ 4 — Nhóm trưởng gom tiến độ lab để báo coach (làm nhóm)

### Candidate problem

> Nhóm trưởng mất khoảng 45 phút mỗi tuần để gom tiến độ lab từ 3–4 thành viên (Discord, Google Doc, GitHub) rồi viết báo cáo ngắn cho coach — hay trễ vì phải nhắc từng người.

| Field | Nội dung |
|---|---|
| **Actor** | Nhóm trưởng lớp học / lab 3–4 người |
| **Bối cảnh** | Chủ nhật tối hoặc sáng thứ Hai trước buổi lab |
| **Dấu hiệu thật** | 45 phút/tuần; 1–2 thành viên thường trả lời muộn; coach hỏi "nhóm đến đâu rồi?" |
| **Tần suất** | Hằng tuần trong 8–12 tuần học |

### Workflow hiện tại

```text
CURRENT STATE — ~45 phút/tuần

[Nhắc từng người gửi update trên Discord: 10']  ⚠️ PAIN (chờ + nhắc)
    ↓
[Đọc 4 tin nhắn / thread khác format: 8']
    ↓
[Mở Google Doc + GitHub xem commit/PR: 7']
    ↓
[Tổng hợp thành 1 bảng tiến độ: 10']
    ↓
[Viết 5–7 câu báo cáo cho coach: 10']  ⚠️ PAIN (bottleneck thứ hai)
    ↓
[Gửi Discord/email: 2']
```

### Pain point — có thể có 2 bước, nhưng chọn 1 bottleneck chính

| Bước | Đánh giá |
|---|---|
| Nhắc từng người | Đau vì **phụ thuộc người khác** — 10 phút + chờ không kiểm soát được |
| Đọc update rời format | 8 phút — có thể chuẩn hóa bằng template |
| **Viết báo cáo narrative cho coach** | **⚠️ Bottleneck chính** — 10 phút, blank page, phải diễn đạt lại từ bullet rời |
| Tổng hợp bảng | 10 phút — có thể giảm nếu có form chuẩn |

**Cách chọn bottleneck khi có 2 bước đau:**

- Nhóm trưởng **không kiểm soát** được việc người khác trả lời muộn → pain ở **nhắc + chờ**.
- Nếu đã có **template update cố định** và mọi người gửi đúng giờ → pain chuyển sang **viết báo cáo**.

**Tóm 1 câu (giả sử chưa có template):** Pain gốc ở bước **thu thập update không chuẩn + phải nhắc**; pain thứ hai ở **viết narrative báo cáo**.

**Quick gut (chưa chốt):** Rule cho bước thu thập (form cố định, deadline) + Workflow cho bước draft báo cáo từ bullet.

```text
FUTURE STATE (nháp) — ~15 phút/tuần

[Form cố định — mỗi người điền 3 field cuối CN: 0' cho nhóm trưởng]
    ↓
[Rule: auto nhắc nếu thiếu 1 field: 1']
    ↓
[AI draft báo cáo từ 4 dòng update: 2']
    ↓
[Nhóm trưởng review + sửa: 10']  ← human boundary
    ↓
[Gửi coach: 2']
```

---

## Ví dụ 5 — Support phân loại ticket lặp lại (đi làm)

### Candidate problem

> Nhân viên support mất 5 phút/ticket để đọc email dài rồi gắn nhãn và chuyển đúng team — trong khi 60% ticket là 5–6 loại câu hỏi lặp lại mỗi ngày.

| Field | Nội dung |
|---|---|
| **Actor** | Support agent tier-1, xử lý inbox chung |
| **Bối cảnh** | 40–60 ticket/ngày, SLA phản hồi đầu tiên 4 giờ |
| **Dấu hiệu thật** | 5 phút/ticket × 50 ticket ≈ 4+ giờ/ngày chỉ cho bước đầu |
| **Tần suất** | Hằng ngày |

### Workflow hiện tại

```text
CURRENT STATE — ~5 phút/ticket

[Đọc email/ticket từ đầu đến cuối: 2']
    ↓
[Đoán category — billing / bug / how-to / account: 1']
    ↓
[Gắn nhãn + chọn team routing trong Zendesk: 1']  ✓
    ↓
[Viết 1–2 câu internal note tóm tắt: 1']  ⚠️ PAIN (khi ticket dài)
    ↓
[Chuyển ticket — hoặc trả lời template nếu FAQ: 1']
```

### Pain point nằm ở bước nào?

| Bước | Vì sao |
|---|---|
| Đọc email dài | Đau khi ticket **không** thuộc FAQ — nhưng với ticket lặp lại thì đọc lại cùng pattern |
| **Tóm tắt internal note** | **⚠️ Bottleneck** với ticket dài — agent phải viết lại context cho tier-2 |
| Routing | 1 phút nếu category đã rõ |

**Tóm 1 câu:** Với ticket **lặp lại**, pain có thể giảm bằng **Rule** (auto-tag + template). Với ticket **dài, lạ**, pain ở **tóm tắt context**.

**Quick gut (chưa chốt):** Rule cho FAQ lặp lại; Workflow cho tóm tắt ticket dài.

---

## Bảng so sánh nhanh 5 ví dụ

| # | Candidate problem (rút gọn) | Actor | Tổng thời gian | **Pain point (bước)** | Loại pain |
|---|---|---|---:|---|---|
| 1 | Tìm quyết định cũ Discord | Sinh viên | ~15'/lần | Đọc + lọc nhiều thread | Tốn thời gian + dễ nhầm |
| 2 | Nộp bài thiếu field | Sinh viên | ~45' (có sửa lại) | Bỏ qua bước đối chiếu checklist | Bước bị skip → làm lại |
| 3 | Hiểu task từ nhiều nguồn | Intern | ~40'/task | Đọc Slack thread nối context | Thông tin rời rạc |
| 4 | Gom tiến độ lab báo coach | Nhóm trưởng | ~45'/tuần | Nhắc + chờ update / viết báo cáo | Phụ thuộc người khác + narrative |
| 5 | Phân loại ticket support | Support agent | ~5'/ticket | Tóm tắt ticket dài | Lặp lại + viết lại context |

---

## Bài tập ngắn — tự luyện trước Phase 2

Chọn **một** problem từ scan cá nhân của bạn (hoặc lấy cảm hứng từ `Suggestion-problem.md`), rồi điền:

```text
1. Actor + bối cảnh (1–2 câu):

2. Workflow hiện tại (5–7 bước, ghi thời gian mỗi bước):

   [Bước 1: __']
       ↓
   [Bước 2: __']
       ↓
   ...

3. Pain point là bước số ___ vì:

4. Bước nào là HẬU QUẢ của pain (không phải gốc)?

5. Nếu chỉ sửa 1 bước — metric có thay đổi đáng kể không? Đo thế nào?
```

**Tự kiểm:**

- [ ] Pain là **một bước** cụ thể, không phải "cả quy trình chậm".
- [ ] Đã ghi **thời gian** hoặc **tần suất** cho bước pain.
- [ ] Phân biệt được **bottleneck** vs **hậu quả** (làm lại, hỏi lại, chờ).
- [ ] Chưa nhảy sang "làm chatbot" — mới mô tả workflow hiện tại.

---

## Liên kết tài liệu

| File | Dùng khi |
|---|---|
| `02-deliverable-example.md` | Xem bài nộp **hoàn chỉnh** (thêm research, PS, decision) |
| `Suggestion-problem.md` | Bí ý tưởng — ngân hàng đề gợi ý |
| `01-worksheet.md` | Template Problem Card + phase làm bài |
| `Question.md` | Coach hỏi khi ghé nhóm |

---

*Day 02 Lab — Candidate Workflow Examples*
