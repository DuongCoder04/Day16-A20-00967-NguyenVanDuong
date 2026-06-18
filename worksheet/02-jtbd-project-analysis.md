---
artifact: 02 — JTBD Project Analysis
bai-tap: Lab 2 — Dùng JTBD để soi lại dự án nhóm
format: Theo nhóm dự án → share trong bàn → chốt hypothesis cuối
time: 25 phút trên lớp
nop-cuoi: Có — đây là file nộp cuối của Lab 2
companion-reference: Strategyn_JTBD_Playbook.pdf (giảng viên gửi kèm)
---

# Lab 2 — JTBD Project Analysis / Dùng JTBD để soi lại dự án nhóm

**Tên dự án / sản phẩm:** **TraVy** — trợ lý cá nhân hóa kế hoạch hành trình du lịch, khám phá Việt Nam.  
**Người làm:** **Nguyễn Văn Dưỡng**  
**Ngày:** **18/06/2026**  

> Đây là **file duy nhất** của Lab 2.  
> File này đồng thời đóng vai trò:
>
> - guide từng bước,
> - worksheet để điền trực tiếp,
> - và file nộp cuối cho người chấm.

Mục tiêu của bài này không phải brainstorm thêm thật nhiều tính năng AI.
Mục tiêu là:

1. **xác định người dùng thực sự đang cố hoàn thành job gì**
2. **hiểu họ đang dùng giải pháp nào để hoàn thành job đó hôm nay**
3. **chỉ ra AI nên chen vào đúng bước nào trong workflow**
4. **viết ra product hypothesis và assumption còn phải validate**

Quy tắc xuyên suốt: **không rõ job thì đừng bàn feature.**

---

## Cần mở song song 2 thứ

1. **File này** — để điền trực tiếp
2. **`Strategyn_JTBD_Playbook.pdf`** — giảng viên gửi kèm

### Cách dùng playbook cho đúng

Bạn **không cần đọc hết 48 trang**.  
Trong bài này, playbook chủ yếu dùng để tra 4 thứ:

1. **Cách nhìn thị trường qua JTBD lens**
2. **`Job executor` là ai**
3. **Cách viết `job statement`: `verb + object + contextual clarifier`**
4. **8 bước của `job map`**:
   `define -> locate -> prepare -> confirm -> execute -> monitor -> modify -> conclude`

### 2 chương nên mở nhiều nhất

- **Chapter 2 — Define Your Market**
- **Chapter 3 — Build Your Job Map**

> Dùng playbook để **tra framework và ví dụ**.  
> Dùng file này để **làm bài và chốt output**.

---

## Đầu ra bắt buộc

Người chấm cần thấy đủ 6 phần trong chính file này:

1. **`Project slice` + market context**
2. **`Job executor` + `core JTBD`**
3. **3 `job stories`**
4. **`JTBD lite map` + pain points**
5. **`AI leverage point` + `product hypothesis`**
6. **`Assumptions to validate` + verdict cuối sau thảo luận**

Nếu thiếu một trong sáu phần trên, bài sẽ bị xem là chưa hoàn chỉnh.

---

## Cách làm trong lớp (25 phút)

```text
3'  Chốt 1 lát cắt cụ thể của dự án
7'  Viết market context + job executor + core JTBD
6'  Viết 3 job stories + current alternatives
6'  Điền JTBD lite map + AI leverage point + hypothesis
3'  Share trong bàn và sửa version cuối
```

> Nếu dự án làm theo nhóm, cả nhóm có thể thảo luận chung.  
> Nhưng file này vẫn nên có **version chốt rõ ràng** của người nộp.

---

## Bước 0 — Khoanh đúng 1 lát cắt của dự án

Phần lớn dự án nhóm viết quá rộng ở bước này, rồi sau đó mọi thứ mơ hồ theo.

### Khoanh đúng 1 lát cắt theo 4 điểm

- [x] **1 nhóm người dùng chính**
- [x] **1 hoàn cảnh / tình huống rõ**
- [x] **1 job cốt lõi**
- [x] **1 workflow đủ cụ thể để vẽ ra được**

### Điền nhanh trước khi làm

- **Dự án của nhóm tôi là:** **TraVy** — trợ lý du lịch AI chuyên biệt cho Việt Nam, giúp du khách tạo lịch trình cá nhân hóa qua hội thoại tự nhiên, dựa trên dữ liệu RAG tuyển chọn (171 địa điểm, 5 tỉnh/thành).
- **Lát cắt tôi chọn để phân tích hôm nay là:** Giúp du khách nội địa tự túc lên lịch trình chuyến đi ngắn ngày (2–5 ngày) đến một tỉnh/thành chưa quen, từ bước research đến khi có lịch trình theo ngày sẵn sàng đi.
- **Vì sao tôi chọn lát cắt này:**  
  > Đây là **use case cốt lõi nhất** của MVP: workflow rõ ràng (research → sắp xếp → chốt lịch trình), pain point lớn nhất (mất 4–10 giờ research theo PRD), và là lát cắt mà dữ liệu RAG hiện tại đã đủ phục vụ (5 tỉnh/thành, 171 địa điểm active). Du khách nội địa chiếm phần lớn thị trường du lịch Việt Nam (~85 triệu lượt/năm) và ít bị chặn bởi rào cản ngôn ngữ.

### Viết quá rộng vs viết sắc hơn

| Viết quá rộng | Viết sắc hơn |
|---|---|
| Giúp SME dùng AI để marketing | Giúp chủ shop online phản hồi câu hỏi trước mua hàng nhanh và nhất quán trong giờ cao điểm |
| Dùng AI để làm slide | Tạo bản nháp deck nội bộ mạch lạc cho buổi họp gấp trong thời gian rất ngắn |
| AI cho tuyển dụng | Giúp recruiter sàng lọc CV đầu vào nhanh hơn trước vòng gọi sơ bộ |

> Nếu bạn không mô tả được **một hoàn cảnh cụ thể**, khả năng cao bạn đang viết quá rộng.

---

## Bước 1 — Viết `Project Snapshot`

### Tóm tắt dự án trong 3 dòng

1. **Nhóm tôi đang nghĩ mình đang giải quyết vấn đề gì?**  
   > Việc lập kế hoạch du lịch Việt Nam bị **phân mảnh** giữa nhiều nguồn (Google, blog, Facebook, bản đồ, nền tảng đặt dịch vụ), khiến du khách mất **4–10 giờ research** mỗi chuyến và nhận lịch trình chung chung, thiếu tri thức địa phương.

2. **Người dùng chính hiện nhóm đang nhắm tới là ai?**  
   > **Du khách nội địa tự túc** (20–35 tuổi, có thu nhập, tự tổ chức chuyến đi ngắn ngày) — người trực tiếp research và quyết định lịch trình, không dùng tour agency.

3. **Hiện tại người dùng đó đang giải quyết vấn đề này bằng cách nào?**  
   > Tự gom thông tin từ **Google search + blog du lịch + group Facebook + hỏi bạn bè** → copy-paste vào Google Sheets/Notes → tự sắp xếp thành lịch trình. Gần đây một số người dùng **ChatGPT/Gemini** nhưng gặp vấn đề bịa địa điểm và thiếu dữ liệu Việt Nam chuyên sâu.

---

## Bước 2 — Viết `Market Context`

Ở đây chưa cần solution. Chỉ cần bối cảnh thị trường đủ để hiểu:
**ai đang gặp chuyện gì, trong hoàn cảnh nào, và vì sao bây giờ đáng giải.**

### Trả lời 4 câu ngắn

1. **Ai đang gặp vấn đề này?**  
   > Du khách nội địa tự túc muốn đi du lịch ngắn ngày (2–5 ngày) đến tỉnh/thành chưa quen — đặc biệt nhóm 20–35 tuổi, đi cùng bạn hoặc gia đình nhỏ.

2. **Vấn đề xuất hiện trong hoàn cảnh nào?**  
   > Trước chuyến đi 1–2 tuần, khi cần lên lịch trình nhưng thông tin phân mảnh trên hàng chục nguồn (blog, Facebook, Google Maps). Đặc biệt đau khi đi đến nơi chưa quen và không có bạn bè địa phương để hỏi.

3. **Hiện tại họ đang dùng giải pháp thay thế nào?**  
   > Google search + blog du lịch (Traveloka Magazine, VnExpress Du lịch), group Facebook ("Review du lịch"), ChatGPT/Gemini generic, hỏi bạn bè đã đi — hoặc **đặt tour trọn gói** để khỏi phải tự research.

4. **Vì sao đây là thời điểm đáng giải?**  
   > AI generative đã đủ mạnh để tạo lịch trình cá nhân hóa, nhưng các tool generic (ChatGPT, Gemini) **thiếu dữ liệu Việt Nam chuyên sâu** và **hay bịa địa điểm**. Đồng thời du lịch nội địa Việt Nam đang bùng nổ (~85 triệu lượt/năm) — nhu cầu lớn nhưng chưa có giải pháp chuyên biệt nào chiếm entry point.

### Tóm tắt market context trong 3-4 dòng

> Du khách nội địa tự túc đang mất 4–10 giờ gom thông tin rời rạc từ blog, Facebook, Google Maps để lên lịch trình cho chuyến đi ngắn ngày. Các tool AI generic (ChatGPT/Gemini) giúp nhanh hơn nhưng hay bịa địa điểm và thiếu tri thức địa phương Việt Nam. Trong khi đó du lịch nội địa đang bùng nổ (~85 triệu lượt/năm) nhưng chưa có giải pháp chuyên biệt nào giúp cá nhân hóa lịch trình dựa trên dữ liệu tuyển chọn và đáng tin.

---

## Bước 3 — Xác định `Job Executor`

`Job executor` là người **trực tiếp dùng một giải pháp để hoàn thành job**.

### Đừng nhầm với:

- người mua tiền nhưng không trực tiếp làm job
- người ảnh hưởng quyết định
- cả một công ty hay một phòng ban quá rộng

### Gợi ý viết cho đúng

- Sai hoặc quá rộng: `SME`, `doanh nghiệp`, `thị trường`
- Tốt hơn: `chủ shop online`, `nhân viên CSKH`, `recruiter`, `sales ops manager`

### Điền

- **Job executor của dự án này là:** **Du khách nội địa tự túc** — người trực tiếp ngồi research, chọn địa điểm, và sắp xếp lịch trình cho chuyến đi của mình.
- **Vì sao tôi tin đây là người trực tiếp "thuê" giải pháp để làm job:**  
  > Đây là người **trực tiếp mở Google/blog/Facebook để tìm thông tin** và **tự tay ghép lịch trình**. Không phải travel agent (bên thứ ba), không phải người đi cùng chỉ "follow" lịch trình, không phải công ty tour (buyer nhưng không làm job). Họ là người chịu toàn bộ friction của quá trình research → sắp xếp → chốt lịch trình.

---

## Bước 4 — Viết `Core JTBD`

`Core JTBD` là công việc cốt lõi người dùng đang cố hoàn thành.

### Công thức gợi ý

```text
[verb] + [object] + [contextual clarifier]
```

### Ví dụ

- Chưa tốt: `trả lời inbox bằng AI`
- Tốt hơn: `giải quyết câu hỏi trước mua hàng nhanh và chính xác trong giờ cao điểm`

- Chưa tốt: `dùng AI để viết nội dung`
- Tốt hơn: `tạo bản nháp nội dung chiến dịch phù hợp với brand trong thời gian rất ngắn`

### 3 tiêu chí tự kiểm

- [x] Nếu bỏ tool hiện tại đi, job này vẫn còn tồn tại
- [x] Trong câu không có tên sản phẩm, AI, chatbot, app, màn hình
- [x] Câu đang mô tả **điều user muốn hoàn thành**, không phải thứ product đang làm

### Bản nháp 1

**Core JTBD bản nháp:**  
> Lên lịch trình du lịch cá nhân hóa bằng hội thoại AI cho chuyến đi ngắn ngày đến nơi chưa quen ở Việt Nam

### Gạch bỏ từ solution nếu có

- Các từ solution tôi đang lỡ nhét vào câu: **"bằng hội thoại AI"** — đây là solution/delivery method, không phải job

### Bản chốt

**Core JTBD cuối cùng:**  
> **Lên lịch trình du lịch phù hợp sở thích cá nhân và ràng buộc thời gian cho chuyến đi ngắn ngày đến nơi chưa quen**

---

## Bước 5 — Viết 3 `Job Stories`

Nếu `core JTBD` là job ở mức cốt lõi, thì `job story` giúp bạn thấy
**job này xuất hiện trong hoàn cảnh nào**.

### Format

```text
When [trigger], I want to [motivation], so I can [outcome].
```

### Ví dụ

`When inbox đổ dồn vào buổi tối, tôi muốn có câu trả lời nhất quán ngay lập tức, so I can không mất đơn vì phản hồi chậm.`

### Bảng 3 job stories

| # | Trigger / When | Motivation / I want to | Outcome / so I can | Điều story này cho thấy |
|---|---|---|---|---|
| JS1 | Quyết định đi Hội An 3 ngày cuối tuần tới nhưng chưa biết gì về Hội An ngoài phố cổ | Có lịch trình theo ngày với địa điểm + ẩm thực + hoạt động phù hợp sở thích (ẩm thực, lịch sử) | Không mất cả tuần research mà vẫn có trải nghiệm chất lượng, không chỉ đến mấy chỗ quá đông khách | **Pain chính: research tốn thời gian** — user cần output nhanh, cá nhân hóa, từ nguồn đáng tin |
| JS2 | Lịch trình đã lên nhưng ngày 2 quá dày (5 điểm + di chuyển xa) hoặc trời mưa bất ngờ | Điều chỉnh nhanh mà không phải lên lại từ đầu — gộp/bỏ/đổi điểm, giữ logic di chuyển hợp lý | Giữ nhịp độ thoải mái mà không bỏ lỡ điểm quan trọng, không bị stress giữa chuyến | **Pain phụ: kế hoạch cứng khó sửa** — user cần khả năng tinh chỉnh linh hoạt |
| JS3 | Đi cùng gia đình (bố mẹ 60+ tuổi, con nhỏ) đến Đà Lạt lần đầu, muốn ăn địa phương nhưng lo chỗ không phù hợp người lớn tuổi | Biết chỗ nào phù hợp cả nhóm + có gợi ý ít tourist trap + nhịp độ vừa phải cho người lớn tuổi | Có trải nghiệm authentic mà vẫn an toàn, thoải mái cho cả nhà — không bị bố mẹ phàn nàn "đi đâu cũng đông" | **Constraint đặc biệt: thành phần nhóm** — cùng 1 job nhưng ràng buộc khác nhau hoàn toàn |

### Tự kiểm nhanh

- [x] Mỗi story là một **tình huống thật**, không phải slogan chung chung
- [x] 3 story không trùng hệt nhau
- [x] Sau khi đọc 3 story, tôi hình dung được lúc nào product của mình đáng xuất hiện

---

## Bước 6 — Liệt kê `Current Alternatives`

Qua JTBD lens, đối thủ không chỉ là app cùng ngành.
Đối thủ là **bất kỳ thứ gì user đang "thuê" để làm job**:

- thao tác tay
- file Excel / Google Sheets
- intern / nhân viên
- agency
- ChatGPT / Claude / Gemini
- công cụ chuyên dụng khác
- hoặc thậm chí là **không làm gì cả**

### Bảng alternatives

| Alternative hiện tại | User đang thuê nó để làm gì? | Nó làm tốt gì? | Nó fail ở đâu? | Switching cost hiện tại cao hay thấp? |
|---|---|---|---|---|
| **Google search + blog du lịch** (VnExpress, Traveloka Magazine) | Tìm "lịch trình Hội An 3 ngày", đọc blog → tự ghép | Miễn phí, nguồn phong phú, có ảnh/review thật | **Phân mảnh** (mỗi blog 1 góc nhìn), tốn 4–10h gom + sắp xếp, thông tin hay cũ (giờ mở cửa, giá), không cá nhân hóa | **Thấp** — không tốn tiền, không lock-in |
| **Group Facebook du lịch** ("Review Hội An", "Du lịch Việt Nam") | Hỏi "đi Hội An 3 ngày nên đi đâu?" → nhận gợi ý từ người đã đi | Kinh nghiệm thật, cập nhật, có thể hỏi lại chi tiết | **Không có cấu trúc** (mỗi người gợi ý khác nhau), phải tự ghép, chất lượng trả lời không đều, chờ reply | **Thấp** — miễn phí, quen thuộc |
| **ChatGPT / Gemini generic** | Hỏi "lên lịch trình Hội An 3 ngày cho 2 người thích ẩm thực" → nhận lịch trình tức thì | **Nhanh** (có output ngay), hiểu ngữ cảnh, cá nhân hóa cơ bản | **Bịa địa điểm** (hallucination), thiếu dữ liệu Việt Nam chuyên sâu (giờ mở cửa, giá, mẹo địa phương), không có source citation → user phải double-check toàn bộ | **Thấp** — miễn phí, ai cũng đã có sẵn |

### Kết luận nhanh

**Nếu project của tôi biến mất hôm nay, user nhiều khả năng sẽ quay về:**  
> **ChatGPT/Gemini generic** — vì nhanh nhất và đã quen, dù phải tự double-check. Nhóm ít tech-savvy hơn sẽ quay về **Google + blog + Facebook**.

---

## Bước 7 — Điền `JTBD Lite Map`

Đây là bản rút gọn của `job map` trong playbook.

### Mục tiêu

Không phải để làm consultant workshop hoàn chỉnh.  
Mục tiêu là nhìn ra:

1. workflow hiện tại của user đi qua những bước nào
2. bước nào đang đau nhất
3. AI có nên chen vào đó không

### 8 bước tham chiếu từ playbook

1. `Define`
2. `Locate`
3. `Prepare`
4. `Confirm`
5. `Execute`
6. `Monitor`
7. `Modify`
8. `Conclude`

> Không nhất thiết bước nào cũng quan trọng như nhau trong dự án của bạn.  
> Nếu ít liên quan, ghi `N/A`, đừng để trống.

### Bảng JTBD Lite Map

| Step | Trong workflow này user đang cố làm gì? | Hôm nay họ đang dùng gì? | Friction / pain hiện tại | Mức đau |
|---|---|---|---|---|
| Define | Xác định đi đâu, bao nhiêu ngày, đi với ai, ngân sách, loại trải nghiệm mong muốn | Bàn bạc với bạn/gia đình, tự quyết | Ít friction — đây là quyết định cá nhân, không cần tool | **Low** |
| Locate | Tìm địa điểm, quán ăn, hoạt động phù hợp tại điểm đến chưa quen | Google search + blog + Facebook group + hỏi bạn bè | **Phân mảnh nghiêm trọng**: mỗi nguồn 1 góc nhìn, mất 4–10h gom, thông tin hay cũ, thiên vị điểm đông khách, thiếu tri thức địa phương | **High** |
| Prepare | Sắp xếp các địa điểm đã tìm thành lịch trình theo ngày hợp lý (khoảng cách, nhịp độ, thời gian mở cửa) | Google Sheets / Notes / tự viết tay + Google Maps đo khoảng cách | **Tốn thời gian, thiếu kiến thức địa lý**: user không biết 2 điểm gần hay xa, giờ mở cửa có khớp không, nhịp độ 1 ngày có quá dày không | **High** |
| Confirm | Kiểm tra giờ mở cửa, giá vé, khoảng cách thực tế, tình trạng hoạt động | Google Maps + gọi điện + đọc review gần nhất trên Google/TripAdvisor | Tốn thời gian nhưng có tool rõ ràng (Google Maps) — friction vừa phải | **Med** |
| Execute | Đi theo lịch trình đã lên | Google Maps dẫn đường + lịch trình trên điện thoại | Ít friction nếu lịch trình tốt — chỉ cần follow | **Low** |
| Monitor | Theo dõi tiến độ trong ngày: có kịp lịch không, có bỏ lỡ gì không | Tự nhìn đồng hồ + đối chiếu lịch trình | Ít friction — kiểm soát được | **Low** |
| Modify | Điều chỉnh khi có thay đổi bất ngờ (mưa, mệt, phát hiện chỗ hay, chỗ đóng cửa) | Tự nghĩ lại + hỏi locals + search lại trên Google | **Khó sửa khi đang đi**: không biết thay bằng gì, lịch trình cứng trên giấy/note, phải research lại từ đầu cho phần còn lại | **Med** |
| Conclude | Đánh giá chuyến đi, lưu kinh nghiệm cho lần sau | Ghi nhớ + đăng review Facebook/Google | Ít friction — không liên quan đến planning | **Low** |

### Chốt 2 bước đau nhất

**Bước đau nhất #1:** **Locate** — Tìm địa điểm/ẩm thực/hoạt động phù hợp tại nơi chưa quen  
**Bước đau nhất #2:** **Prepare** — Sắp xếp thành lịch trình theo ngày hợp lý

**Vì sao đây là nơi đáng chú ý nhất:**  
> Hai bước này **chiếm 80–90% thời gian** của toàn bộ quá trình lên kế hoạch (4–10 giờ theo PRD). Chúng đau vì: (1) thông tin phân mảnh trên hàng chục nguồn khiến **Locate** biến thành "mò kim đáy bể", (2) user thiếu kiến thức địa lý nên **Prepare** trở thành bài toán tối ưu mà không có dữ liệu — sắp 5 điểm vào 1 ngày nhưng không biết có kịp di chuyển không.  
> Đây cũng là 2 bước mà **current alternatives fail nặng nhất**: blog/Facebook không có cấu trúc (Locate), ChatGPT generic bịa địa điểm (Locate), và không tool nào giúp tự động sắp lịch trình tối ưu khoảng cách (Prepare).

---

## Bước 8 — Chỉ ra `AI Leverage Point`

Sau khi map workflow, mới hỏi:
**AI nên vào đâu, với vai trò gì, và vì sao là ở đó?**

### Nhắc nhanh

- Đừng nhét AI vào chỉ vì "có AI thì nghe hay"
- Nếu pain lớn nhất không nằm ở chỗ AI giải tốt, hãy thành thật ghi ra
- Nếu current alternative đã đủ tốt, project cần xem lại

### Bảng leverage point

| Step | AI nên giúp bằng cách nào? | Vì sao AI hợp ở đây? | Rủi ro chính nếu dùng AI |
|---|---|---|---|
| **Locate** | Tổng hợp từ dữ liệu RAG tuyển chọn (171 địa điểm, 5 tỉnh/thành), gợi ý địa điểm + ẩm thực + hoạt động **phù hợp sở thích** + **ít phổ biến** — kèm citation nguồn | AI giỏi **tổng hợp thông tin phân mảnh** thành câu trả lời có cấu trúc. RAG chuyên biệt giải quyết đúng điểm yếu của ChatGPT generic (bịa địa điểm, thiếu data VN) | **Hallucination**: nếu RAG thiếu data → AI có thể bịa. **Coverage gap**: 171 địa điểm chưa đủ cho mọi sở thích (ẩm thực mới chiếm ~5% corpus) |
| **Prepare** | Tự động sắp xếp địa điểm thành **lịch trình theo ngày** tối ưu khoảng cách và nhịp độ, qua hội thoại cho phép user tinh chỉnh | AI giỏi **tối ưu hóa + cá nhân hóa có constraint** (thời gian, khoảng cách, sở thích, thành phần nhóm). Đây là bài toán tốn hàng giờ nếu làm tay | **Chất lượng routing**: AI có thể sắp sai khoảng cách nếu thiếu data PostGIS. **Over-packed**: AI có xu hướng nhét quá nhiều điểm vào 1 ngày |

### Kết luận nhanh

**AI leverage point quan trọng nhất của dự án tôi là:**  
> **Locate → Prepare liên tục**: AI tổng hợp địa điểm phù hợp từ RAG (Locate) rồi ngay lập tức sắp xếp thành lịch trình theo ngày (Prepare) — gộp 2 bước đau nhất thành **1 bước duy nhất** qua hội thoại.

**Vì sao không phải ở bước khác:**  
> **Define** ít đau (user tự quyết, không cần tool). **Execute/Monitor** là khi đang đi — không phải lúc planning. **Modify** đau vừa phải và có thể giải bằng cùng cơ chế hội thoại của Locate+Prepare (hỏi lại AI để sửa lịch trình). Giá trị lớn nhất nằm ở **Locate + Prepare** vì đây là nơi user mất nhiều thời gian nhất và current alternatives fail nặng nhất.

---

## Bước 9 — Viết `Product Hypothesis`

Bây giờ mới đến lúc viết hypothesis.

### Công thức gợi ý

```text
Nếu chúng ta giúp [job executor] làm [job / sub-job] tốt hơn ở bước [x],
bằng cách [AI leverage],
thì họ sẽ chuyển từ [current alternative] sang [hướng giải pháp của nhóm],
vì [giá trị rõ nhất].
```

### Bản hypothesis của tôi

> Nếu chúng ta giúp **du khách nội địa tự túc** tìm và sắp xếp địa điểm thành **lịch trình cá nhân hóa** tốt hơn ở bước **Locate** và **Prepare**,  
> bằng cách **dùng dữ liệu du lịch Việt Nam tuyển chọn (RAG) kết hợp hội thoại tự nhiên** để gộp 2 bước thành 1,  
> thì họ sẽ chuyển từ **tự gom blog/Facebook/ChatGPT generic** sang **dùng TraVy**,  
> vì **tiết kiệm 4–10 giờ research** mà vẫn có lịch trình chất lượng, cá nhân hóa, và đáng tin (có citation nguồn, không bịa địa điểm).

### Tín hiệu sớm nếu hypothesis này đúng

1. User hoàn thành hội thoại tạo lịch trình mà **không cần mở tab Google/blog nào khác** để verify lại.
2. User quay lại dùng TraVy cho chuyến đi tiếp theo hoặc **share lịch trình cho bạn bè** (organic referral).

---

## Bước 10 — Liệt kê `Assumptions to Validate`

Job story chưa có research vẫn chỉ là **giả thuyết tốt hơn**, chưa phải sự thật.

### 5 assumption thường đáng kiểm

- Tôi đã chọn đúng `job executor`
- Pain này thật sự đủ đau và xảy ra đủ thường xuyên
- User sẽ đổi khỏi alternative hiện tại nếu có giải pháp tốt hơn
- AI thực sự tạo giá trị ở step tôi chọn
- User đủ tin kết quả AI để đưa vào workflow thật

### Bảng assumptions

| Assumption | Vì sao assumption này rủi ro? | Tôi đang có bằng chứng gì? | Cần validate bằng cách nào tiếp theo? |
|---|---|---|---|
| A1: Du khách nội địa tự túc **thật sự thấy đau** khi tự lên lịch trình (pain đủ lớn để đổi tool) | Có thể họ **thích tự research** (coi là một phần vui của chuyến đi) hoặc pain chưa đủ lớn để thay đổi hành vi | PRD ước tính 4–10h research; group Facebook du lịch có hàng triệu thành viên hỏi "đi đâu, ăn gì" → demand rõ | **Phỏng vấn 5–10 du khách**: hỏi "lần cuối bạn tự lên lịch trình mất bao lâu?" và "nếu có tool làm xong trong 5 phút, bạn có dùng không?" |
| A2: Dữ liệu RAG tuyển chọn **tạo ra lịch trình tốt hơn** ChatGPT generic | ChatGPT đang cải thiện rất nhanh (GPT-4o, search tool); RAG 171 địa điểm có thể **không đủ coverage** — đặc biệt food_drink chỉ ~5% | Retrieval eval hit_rate 1.0, sim 0.82+ trên Hà Nội; ChatGPT không có dữ liệu giờ mở cửa/giá VN chính xác | **A/B test**: cho 10 user cùng yêu cầu, so sánh lịch trình TraVy vs ChatGPT — đo accuracy + user preference |
| A3: User **tin kết quả AI** đủ để đi theo mà không double-check toàn bộ | Du khách rất cẩn thận với thông tin du lịch (sợ đến nơi đóng cửa, bị lừa giá); trust barrier cao với AI | TraVy có citation nguồn (khác ChatGPT generic) — nhưng chưa test user reaction | **Prototype test**: cho user đọc lịch trình TraVy (có citation) vs ChatGPT (không citation) — đo mức tin tưởng |
| A4: **Hội thoại tự nhiên** là cách user muốn tương tác (vs. form/filter/drag-drop) | Nhiều travel app thành công dùng form (TripAdvisor, Google Travel) hoặc drag-drop (Wanderlog). Có thể user thích **nhìn map + kéo thả** hơn chat | Xu hướng AI-first UX đang tăng; nhưng chưa có data riêng. 5 câu hỏi onboarding có thể gây friction | **Usability test**: cho 5 user dùng prototype chat flow, đo completion rate và hỏi "bạn thích chat hay form hơn?" |
| A5: User sẵn sàng **bỏ workflow cũ** (Google + blog + Facebook) nếu có giải pháp tốt hơn | Workflow cũ **miễn phí + quen thuộc**, switching cost gần 0 nhưng **inertia cao** — "tôi vẫn hay search Google thôi" | Sự phổ biến nhanh chóng của ChatGPT cho thấy user sẵn sàng đổi tool nếu nhanh + tốt hơn | **Landing page test**: đo conversion từ "describe your trip" CTA → hoàn thành lịch trình — nếu >30% hoàn thành = signal tốt |

### Assumption nguy hiểm nhất nếu tôi đang sai

> **A1: Pain chưa đủ lớn.** Nếu du khách nội địa tự túc **thích tự research** (coi research là một phần vui) hoặc **ChatGPT generic đã đủ tốt** (pain giảm về 0 trước khi TraVy launch), thì toàn bộ hypothesis sụp — không ai cần tool chuyên biệt để giải pain đã biến mất. Đây là assumption cần validate **đầu tiên** trước khi invest thêm vào RAG/feature.

---

## Bước 11 — Share trong bàn (3')

### Mỗi người / mỗi nhóm chỉ nói 4 thứ

1. **Job executor của bạn là ai**
2. **Core JTBD của bạn là gì**
3. **Step đau nhất đang nằm ở đâu**
4. **AI leverage point + assumption rủi ro nhất là gì**

### Nếu chưa biết hỏi ngược gì, dùng 4 câu này

1. **"Câu JTBD này có đang lỡ nhét solution vào không?"**
2. **"Alternative hiện tại của user là gì, và tại sao họ chưa bỏ nó?"**
3. **"Pain mạnh nhất nằm ở bước nào trong workflow, có chắc AI giải tốt được không?"**
4. **"Assumption nào nếu sai thì cả hypothesis sẽ sập?"**

### Ghi nhanh sau khi nghe bàn phản biện

| Ý phản biện tôi nghe được | Nó chạm vào phần nào? | Tôi sẽ giữ / sửa gì? |
|---|---|---|
| | | |
| | | |
| | | |

---

## Bước 12 — Chốt version cuối sau thảo luận

### Sau khi nghe phản biện, tôi thay đổi gì?

- [ ] Giữ nguyên `job executor`
- [ ] Sửa `job executor`
- [ ] Giữ nguyên `core JTBD`
- [ ] Sửa `core JTBD`
- [ ] Giữ nguyên `AI leverage point`
- [ ] Sửa `AI leverage point`
- [ ] Giữ nguyên `product hypothesis`
- [ ] Sửa `product hypothesis`

### Vì sao tôi giữ / sửa?

> _______________________________________________  
> _______________________________________________

### Version cuối cùng tôi nộp

**Job executor:**  
> _______________________________________________

**Core JTBD:**  
> _______________________________________________

**2 bước đau nhất trong workflow:**  
> _______________________________________________

**AI leverage point chính:**  
> _______________________________________________

**Product hypothesis:**  
> _______________________________________________

**Assumption cần validate đầu tiên:**  
> _______________________________________________

---

## Checklist trước khi nộp

- [x] Tôi đã khoanh đúng 1 lát cắt cụ thể của dự án.
- [x] Tôi đã phân biệt được `job executor` với buyer / influencer.
- [x] `Core JTBD` của tôi không nhét solution vào câu.
- [x] Tôi đã viết đủ 3 `job stories`.
- [x] Tôi đã điền `JTBD lite map` và khoanh ra 2 bước đau nhất.
- [x] Tôi đã chỉ ra `AI leverage point` thay vì nhảy thẳng vào feature list.
- [x] Tôi đã ghi rõ `assumptions to validate`.
- [ ] Tôi đã sửa version cuối sau khi share trong bàn.

---

## Nếu còn thời gian / làm về nhà

- Phỏng vấn nhanh 1 người dùng thật để kiểm xem `job story` nào là sát nhất.
- So sánh `current alternatives` với project của nhóm theo 3 tiêu chí: nhanh hơn, rẻ hơn, tin hơn.
- Tự hỏi lại một câu khó: **nếu không dùng AI, project này còn tạo giá trị không?**
- Nếu câu trả lời là "không", hãy xem lại liệu nhóm đang giải **job thật** hay chỉ đang tìm chỗ để nhét AI.
