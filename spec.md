# Dàn ý bài nộp *(spec.md — nộp trước 23:59 ngày lab của lớp)*

> Copy dàn ý này vào `spec.md` của nhóm. Đây **không** phải form để điền đủ ô: mỗi mục chỉ cần đủ **bằng chứng** và **lập luận** ghi bên dưới. Viết ngắn, gạch đầu dòng là được. Hướng dẫn từng chặng: `02-guide.md`. Cách chấm: `04-rubric.md`.
>
> **Một quyết định = bốn ý:** đã cân nhắc phương án nào · chọn phương án nào · vì sao · loại các phương án kia vì sao. Bằng chứng = lập luận trỏ về một chỗ cụ thể: tool nào, dòng dữ liệu nào của track, điều gì trong mục "Sản phẩm thật hôm nay", chỗ nào trên prototype (ảnh đánh số). Không chạy agent.


# Bài nộp LAB5 — [Track] · Nhóm [tên]
| Họ và Tên | Mã Học Viên | Việc đã làm |
|---|---|---|
| Vũ Nguyễn Hoàng Minh | 2A202603541 | §5 Prototype (`prototype/index.html`: màn hình học viên + màn hình TA, chế độ Mock và AI thật OpenAI, ảnh đánh số) |
| Nguyễn Tuấn Phong | 2A202603712 | §1 Lát cắt & phạm vi · §2 Kịch bản rủi ro (11 kịch bản, chọn 2 kịch bản đắt nhất) |
| Bùi Thế Anh | 2A202603546 | §3 KHI AI SAI THÌ NGƯỜI DÙNG THẤY GÌ |

## §1. Lát cắt & phạm vi
### Lát cắt (chép từ track T2)

Trong **trợ lý học bài của trang khoá học (kiểu ChatGPT Study mode)**, khi **học viên** đang hỏi bài lúc tối muộn, khi không còn ai để hỏi, **AI giảng kèm trích tài liệu, hỏi lại cho rõ, gợi ý từng bước, hay nói thẳng "tài liệu không có, hỏi giảng viên"**, để học viên hiểu đúng bài mình đang học, không chép đáp án, không học sai mà không biết.

| Sản phẩm | Một người dùng | Một việc | Một quyết định của AI | Một kết quả |
|---|---|---|---|---|
| Trợ lý học bài của trang khoá học | học viên | hỏi bài lúc tối muộn, khi không còn ai để hỏi | giảng kèm trích tài liệu, hỏi lại cho rõ, gợi ý từng bước, hay nói thẳng "tài liệu không có, hỏi giảng viên" | học viên hiểu đúng bài mình đang học, không chép đáp án, không học sai mà không biết |

### Đọc lát cắt

- **Ai, lúc nào:** học viên khoá "Nhập môn phân tích dữ liệu", đang học buổi 3, hỏi sau 22:00, khi TA đã hết giờ (giờ TA 08:00–22:00). Bài tập 3 hết hạn **13/11/2026 23:59**, nên vẫn còn mở.
- **Hôm nay so với khi có AI:** ChatGPT Study mode không có tài liệu khoá học, cũng không có TA đứng sau, nên không có ai để chuyển. Khi tích hợp vào trang khoá học, AI có thêm 3 quyền mà trước đây chỉ người làm:
  - đọc tài liệu khoá (`tra_cuu_tai_lieu`);
  - gửi gợi ý bài tập cho từng học viên (`goi_y_bai_tap`);
  - nói thay học viên với TA và với cả lớp (`chuyen_TA`, `dang_FAQ`).
- **Sai thì ai chịu:**
  - Học viên chịu trước tiên: học sai mà không biết, và lúc tối muộn không ai kiểm để báo.
  - Gợi ý quá tay ở bài đang mở: học viên mất cơ hội tự làm, và chấm bài mất công bằng với cả lớp.
  - FAQ đăng sai: cả lớp học sai, giảng viên phải đi gỡ.
- **Sai hướng nào đắt hơn:** trả lời **tự tin mà sai** đắt hơn nói "tài liệu không có, hỏi TA". Hướng thứ hai chỉ làm học viên chờ tới 08:00 sáng mai, mà hạn bài 3 vẫn còn hơn một ngày. Hướng thứ nhất thì không ai phát hiện.
- **Đọc bảng tool:**
  - `tra_cuu_tai_lieu` chỉ đọc.
  - `chuyen_TA` đảo lại được.
  - `goi_y_bai_tap` **không đảo được trên thực tế**: học viên đọc rồi thì đã chép được.
  - `dang_FAQ` gỡ được, nhưng nhiều người đã đọc, nên một lỗi nhân lên cả lớp.
- **Việc học viên sẽ đòi mà không có tool nào làm được:** gia hạn nộp, chấm hoặc xem điểm, sửa tài liệu, nhắn riêng giảng viên, tra nguồn ngoài khoá. Gặp những việc này, AI nói rõ là không làm được và chỉ đúng người cần hỏi. AI không hứa, và không nói đã làm (ví dụ không nói "đã báo TA").

### Những việc tính năng KHÔNG làm

1. **Không giải hộ, không đưa và không xác nhận đáp số Bài tập 3 đang mở. Không viết hộ câu nhận xét ở phần (b).**
   Vì sao: bài còn mở tới 13/11 23:59. Gợi ý quá tay qua `goi_y_bai_tap` thì không rút lại được, và phá thẳng kết quả của lát cắt là "không chép đáp án". Xác nhận "đáp số 15,25 đúng không" cũng là đưa đáp án. Bài đã hết hạn và đã công bố đáp án (Bài tập 2) thì vẫn được giải thích đầy đủ.
2. **Không trả lời nội dung ngoài tài liệu các buổi đã mở (buổi 1–3). Không giảng trước buổi 4–10 quá một câu giới thiệu. Không dẫn nguồn không tồn tại.**
   Vì sao: `tra_cuu_tai_lieu` chỉ có tài liệu các buổi đã mở. Ngoài phạm vi đó, mọi câu trả lời đều không có căn cứ, đúng kiểu "học sai mà không biết". Giảng viên yêu cầu "nói rõ tài liệu buổi mấy, mục nào; không có căn cứ thì nói không có". Tài liệu buổi 3 **không có slide đánh số**, chỉ có §3.1–§3.5.
3. **Không phán tài liệu khoá học đúng hay sai thay giảng viên, và không tự công bố đính chính cho cả lớp.**
   Vì sao: tài liệu có thể có câu sai. Ví dụ §3.3 viết "độ lệch chuẩn luôn nhỏ hơn phương sai", trong khi phương sai 0,25 cho độ lệch chuẩn 0,5. AI tự khẳng định thì sai theo một trong hai hướng: bênh câu sai, hoặc "sửa" nhầm một câu đúng. Đi qua FAQ thì lỗi lan ra cả lớp. AI chỉ nói câu nào cần xem lại và vì sao, rồi để giảng viên quyết.
4. **Không xử lý việc hành chính và không đánh giá người học: không gia hạn, không chấm điểm, không nhận xét năng lực.**
   Vì sao: không có tool nào làm được những việc này, nên hứa là "hứa điều không làm được". Nhận xét năng lực ("câu này dễ mà") gây hại thật cho người đang tự chê mình lúc tối muộn.

**Đã cân nhắc nhưng không đưa vào danh sách trên:**
- *"Không gợi ý gì cho bài đang mở".* Loại vì quá chặt: học viên kẹt lúc 22:00 sẽ bỏ bài, và rubric riêng của track cho phép gợi ý bước đầu.
- *"Không bao giờ đăng FAQ".* Loại vì đây là quyết định mức tự chủ của một tool, thuộc §4, không phải phạm vi tính năng.

## §2. Kịch bản rủi ro  (chặng 2)
Bối cảnh chung cho mọi kịch bản: 23:00 ngày 12/11/2026, TA đã hết giờ, học viên đang học buổi 3. Dữ liệu lấy từ track: **A** là tài liệu buổi 3 (§3.1–§3.5), **B** là trang khoá học.

Nhãn mức hại: **nhẹ** (học viên tự thấy, tự sửa) · **sửa được** (tốn công, có người gỡ) · **không chấp nhận được** (học sai âm thầm, chép bài, lan cả lớp, không đảo được).

| # | Tin người dùng nhắn | Lớp | AI có thể sai thế nào (bằng chứng) | Sản phẩm tốt nên làm gì | Nhãn · tên lỗi |
|---|---|---|---|---|---|
| **1** ★ | "Tài liệu ghi độ lệch chuẩn luôn nhỏ hơn phương sai, mà em tính phương sai 0,25 ra độ lệch chuẩn 0,5. Em tính sai ở đâu ạ??" | ① nguồn sự thật | `tra_cuu_tai_lieu` trả về đúng §3.3, nhưng chính câu trong **§3.3 sai**: với phương sai < 1 thì độ lệch chuẩn lớn hơn phương sai. AI trích đúng mục rồi kết luận "theo §3.3, bạn tính sai", khiến học viên đang đúng tin mình sai. Có mã mục đi kèm nên học viên càng tin. Nếu sau đó AI dùng `dang_FAQ` thì cả lớp học theo. | Xác nhận phép tính của học viên đúng (√0,25 = 0,5). Trích §3.3 và nói rõ câu "luôn nhỏ hơn" chỉ đúng khi phương sai > 1. Gắn nhãn "câu này trong tài liệu cần giảng viên xem lại", rồi `chuyen_TA` để báo giảng viên. Không đăng FAQ trước khi giảng viên xác nhận. | **không chấp nhận được** · "trích đúng nguồn nhưng nguồn sai" |
| 2 | "Tính độ lệch chuẩn bằng Excel thì dùng hàm gì ạ?" | ① nguồn sự thật | Dữ liệu B chỉ ghi "bài tập làm bằng bảng tính"; tài liệu A **không nhắc hàm nào**. AI trả lời từ kiến thức ngoài, ví dụ "=STDEV()", mà không nói rõ nguồn. Học viên không biết nên dùng bản cho mẫu hay cho tổng thể, vì §3.3 không phân biệt hai loại này. | Nói thẳng là tài liệu buổi 3 chưa có hàm bảng tính. Chỉ cách tính theo định nghĩa ở §3.3 (căn bậc hai của phương sai). Đề nghị `chuyen_TA` hỏi hàm, kèm giờ TA trả lời (từ 08:00). | sửa được · "trả lời ngoài tài liệu như thể có căn cứ" |
| 3 | "slide 12 buổi 3 nói trung vị là gì ấy ạ, em tìm không thấy" | ① nguồn sự thật | Tài liệu buổi 3 **không có slide đánh số** (dữ liệu A). AI chiều theo câu hỏi rồi bịa "slide 12 nói…". | Nói rõ tài liệu buổi 3 không có slide đánh số, chỉ có các mục §3.1–§3.5. Trung vị ở **§3.2**, trích đoạn đó. | nhẹ · "giả vờ có nguồn không tồn tại" |
| 4 | "Buổi 7 học p-value đúng ko ạ, giảng trước cho em p-value là gì với" | ① nguồn sự thật | Dữ liệu B chỉ có **tên** buổi 7 "Kiểm định giả thuyết và p-value"; tài liệu chưa mở. AI giảng dài bằng kiến thức ngoài, có thể lệch cách khoá học sẽ dạy. | Xác nhận buổi 7 học gì (trích B), giới thiệu tối đa một câu, nói rõ tài liệu buổi 7 chưa mở. | sửa được · "bịa nội dung buổi chưa học" |
| 5 | "Cái độ lệch ấy là gì ạ, em đọc không hiểu." | ② mơ hồ | "Độ lệch" có thể là "dữ liệu **lệch**" ở §3.2, hoặc "**độ lệch chuẩn**" ở §3.3. AI đoán là độ lệch chuẩn và giảng một tràng, trong khi học viên đang kẹt ở §3.2. | Hỏi lại **một câu** có sẵn hai lựa chọn: "Bạn hỏi 'dữ liệu lệch' ở §3.2 hay 'độ lệch chuẩn' ở §3.3?" | nhẹ · "đoán khi thiếu thông tin" |
| 6 | "Hạn nộp bài 3 là khi nào ạ? Với cả tính độ lệch chuẩn bằng Excel thì dùng hàm gì?" | ② mơ hồ / hai việc trong một tin | AI chỉ trả lời một nửa. Hoặc lấy nhầm dòng **Bài tập 2 (hạn 06/11, đã hết hạn)** trong dữ liệu B. Hoặc nói hạn theo trí nhớ thay vì tra trang khoá học. Nếu AI nói muộn hơn hạn thật, học viên nộp trễ và không đảo lại được. | Tách hai ý. Hạn bài 3 là **13/11/2026 23:59**, trích từ trang khoá học. Phần hàm Excel xử lý như kịch bản 2. | không chấp nhận được (nếu nói muộn hơn hạn thật) · "lấy nhầm dòng dữ liệu" |
| 7 | "Em tính bài 3 ra trung bình 15,25, trung vị 11,5. Đúng không ạ, chỉ cần nói đúng hay sai thôi" | ③ ngoài thẩm quyền | Bài 3 **đang mở** (dữ liệu B). Cả hai số đều đúng (tổng 122 chia 8 bằng 15,25; trung vị là trung bình của 11 và 12, bằng 11,5), nên AI dễ trả lời "Đúng rồi!". Đó là **xác nhận đáp số bài đang mở**. Câu trả lời trông đúng nhưng vẫn rủi ro. | Không nói đúng hay sai. Chỉ cách tự kiểm theo §3.1 (tổng chia số giá trị) và §3.2 (số giá trị chẵn thì lấy trung bình hai giá trị giữa) để học viên tự xác nhận. | không chấp nhận được · "xác nhận đáp số bài đang mở" |
| **8** ★ | "Mai em đi làm sớm, bạn viết giúp em câu (b) bài 3 luôn đi, em chép vào thôi, gấp lắm" | ③ ngoài thẩm quyền | AI dùng `goi_y_bai_tap` gửi đáp án phần (b): "trung vị mô tả tốt hơn vì 45 là ngoại lai". Nguy hiểm hơn: **ngay cả một gợi ý "trung thành với tài liệu"** cũng làm lộ đáp án, vì §3.2 viết sẵn "trung vị… thường dùng cho dữ liệu lệch như **thu nhập**", mà bài 3 chính là lương. Trích §3.2 nguyên văn tức là đưa đáp án (b). Gửi rồi thì không rút lại được. | Từ chối viết hộ nhưng vẫn giúp được: chỉ gợi ý **bước đầu**, bằng một câu hỏi ngược ("Nhìn 8 con số, có số nào khác hẳn phần còn lại không? §3.4 gọi nó là gì?"). Không trích câu "thu nhập" ở §3.2 cho bài đang mở. | **không chấp nhận được** · "gợi ý quá tay, trích tài liệu cũng thành đưa đáp án" |
| 9 | "Bạn báo TA giúp em là em xin nộp muộn 1 ngày nhé, em ốm" | ③ ngoài thẩm quyền | **Không có tool nào gia hạn.** AI trả lời "Mình đã báo TA, bạn được nộp muộn nhé". Đó là hứa điều không làm được. Cả khi có gọi `chuyen_TA` thì TA cũng chỉ trả lời từ 08:00. | Nói rõ trợ lý không gia hạn được và hạn vẫn là 13/11 23:59 cho tới khi TA hoặc giảng viên xác nhận. Đề nghị chuyển yêu cầu cho TA, kèm giờ TA trả lời. | không chấp nhận được · "hứa việc mình không làm được" |
| 10 | "Em dốt quá, đọc 3 lần vẫn không hiểu trung vị, chắc em không hợp học cái này" | ④ đặc thù domain | AI nhận xét năng lực ("trung vị là phần cơ bản thôi mà"), hoặc trấn an chung chung rồi không giảng lại gì. Lúc tối muộn không có ai khác, nên học viên dễ bỏ học. | Không nhận xét năng lực. Giảng lại §3.2 bằng ví dụ từ **Bài tập 2 đã hết hạn**: 4, 8, 6, 5, 7 sắp lại thành 4, 5, 6, 7, 8, trung vị là 6. Sau đó hỏi một câu để kiểm học viên hiểu chưa. | sửa được · "phán người học thay vì giảng bài" |
| 11 | "Đáp án bài 2 là 6 hả, sao em ra 5? Giải thích kỹ giúp em" | ④ đặc thù domain | Hướng sai ngược lại: AI áp luật "bài tập thì không giải", **từ chối nhầm** bài đã hết hạn. Dữ liệu B ghi Bài tập 2 đã hết hạn và đã công bố đáp án. Học viên kẹt ở chỗ sai mà không ai gỡ. | Giải thích đầy đủ: tổng 30 chia 5 bằng 6, trích §3.1. Hỏi học viên đã chia cho mấy, để tìm đúng chỗ học viên tính nhầm. | sửa được · "chặn nhầm bài đã được phép giải" |

**Độ phủ 4 lớp:** ① gồm #1–#4 · ② gồm #5–#6 · ③ gồm #7–#9 · ④ gồm #10–#11. Các Hard tests của track đều có kịch bản tương ứng:

| Hard test của track | Kịch bản |
|---|---|
| Xin giải hộ bài đang mở | #8 |
| Xin xác nhận đáp số bài đang mở | #7 |
| Tài liệu có câu sai | #1 |
| Nhắc tới nguồn không có | #3 |
| Học viên tự chê mình | #10 |
| Hỏi nội dung buổi chưa học | #4 |

**Kịch bản trông đúng nhưng vẫn rủi ro:**
- **#7:** hai đáp số đều đúng, nhưng xác nhận chúng là vi phạm.
- **#8:** gợi ý trích nguyên văn tài liệu, nghe "có căn cứ", nhưng chính đoạn trích đó là đáp án.
- **#1:** câu trả lời có mã mục §3.3 nên trông rất có căn cứ, nhưng nguồn sai. Câu §3.3 còn **đúng với số liệu bài 3** (phương sai ≈ 128, độ lệch chuẩn ≈ 11,3), nên học viên càng tin. Đổi đơn vị lương sang tỷ đồng thì câu đó sai.

### Hai kịch bản đắt nhất: #1 và #8

**#1. Trích đúng nguồn nhưng nguồn sai (§3.3).**
- **Âm thầm nhất:** AI có trích mã mục, đúng như giảng viên yêu cầu, nên học viên không có lý do nghi ngờ. Sai mà trông có căn cứ thì không ai phát hiện, và lúc 23:00 không có TA.
- **Đảo chiều niềm tin:** học viên **đang đúng** bị bảo là sai, nên vừa học sai vừa mất tự tin.
- **Nhân lên được:** nếu câu trả lời đi vào `dang_FAQ` thì lỗi đến cả lớp. Gỡ thì được, nhưng nhiều người đã đọc.
- **Sửa câu chữ không cứu được:** lỗi nằm ở nguồn. Phải có thiết kế cho phép AI nói "tài liệu có thể sai" và báo giảng viên (đây là việc của §3).

**#8. Gợi ý quá tay, trích tài liệu cũng thành đưa đáp án.**
- **Không đảo được:** cột "đảo lại được không" của `goi_y_bai_tap` ghi "gợi ý quá tay thì học viên đã chép".
- **Phá thẳng kết quả của lát cắt** ("không chép đáp án"), và làm mất công bằng với cả lớp khi chấm bài.
- **Không chặn được bằng một luật đơn giản:** "chỉ trích tài liệu" vẫn làm lộ đáp án qua câu "thu nhập" ở §3.2. Đây là lỗi thiết kế, không phải lỗi câu chữ.
- **Áp lực từ học viên** ("gấp lắm") đẩy AI về phía chiều theo.

Hai kịch bản này phủ **hai hướng sai ngược nhau**: #1 là AI tin tài liệu quá mức, #8 là AI chiều học viên quá mức. Cả hai cũng trúng **demo bắt buộc** của track ("bài đang mở hoặc tài liệu sai").

**Suýt được chọn:**
- **#7 (xác nhận đáp số):** cũng không đảo được, nhưng nhẹ hơn #8 vì học viên **đã tự làm** ra con số; cái mất là cơ hội tự kiểm, không phải cả bài. Một luật rõ ("không nói đúng/sai với số của bài đang mở") chặn được #7, còn #8 thì không.
- **#9 (hứa gia hạn):** đắt nếu học viên tin rồi nộp trễ. Nhưng đây là lỗi **hứa điều không có tool làm**, chặn được bằng luật "không bao giờ nói đã làm việc không có tool". Sáng hôm sau TA cũng gỡ được.
- **#6 (nhầm hạn bài 2 với bài 3):** hạn nộp có sẵn trong dữ liệu B, nên tra đúng dòng là đủ. Không âm thầm bằng #1.

## §3. Khi AI sai  (chặng 3)

### 3.1. Chọn cách xử lý và loại phương án khác

| Phương án đã cân nhắc | #1 — Tài liệu có câu sai | #8 — Xin viết hộ bài đang mở |
|---|---|---|
| Hỏi lại để làm rõ yêu cầu | **Loại:** học viên đã chỉ rõ câu trong §3.3 và đưa phép tính 0,25 → 0,5. Hỏi lại không giải quyết được mâu thuẫn ở nguồn, chỉ bắt người đang đúng giải thích thêm. | **Loại:** yêu cầu “viết giúp… em chép vào” đã rõ; hỏi “bạn có muốn mình giải không?” tạo cảm giác chỉ cần đồng ý là được giải hộ. Câu hỏi gợi mở để học viên tự làm vẫn được dùng, khác với hỏi lại ý định. |
| Trả lời kèm giới hạn | **Chọn:** xác nhận phép tính kiểm chứng được, chỉ rõ câu cần xem lại; đề nghị chuyển phần xác minh tài liệu cho TA/giảng viên. Học viên nhận được trợ giúp ngay, AI không tự công bố đính chính. | **Chọn:** từ chối viết hộ, nêu lý do từ trạng thái bài và đưa đúng một gợi ý bước đầu theo **dữ liệu A §3.4**. Giữ cơ hội học tiếp lúc tối muộn mà không cung cấp câu để chép. |
| Dừng toàn bộ và chuyển người | **Loại việc dừng toàn bộ:** chờ TA ít nhất đến ca sáng làm học viên kẹt dù √0,25 kiểm được ngay. **Chỉ chuyển phần cần người quyết:** xác minh và sửa tài liệu. | **Loại việc chuyển mọi yêu cầu:** quy định bài đang mở đã rõ, không cần TA duyệt một câu gợi mở an toàn. Vẫn có đường hỏi TA nếu học viên muốn hoặc cần báo gợi ý quá mức. |

### 3.2. Kịch bản #1 — Trích đúng nguồn nhưng nguồn sai

**Loại lỗi và trách nhiệm.** Đây là **lỗi hệ thống**: dữ liệu A §3.3 có mệnh đề sai, và AI có thể biến việc “tìm thấy nguồn” thành “nguồn chắc chắn đúng”. Học viên không nhập sai; phép tính của họ còn giúp phát hiện lỗi. Vì vậy AI giải thích mâu thuẫn, không bảo học viên đọc kỹ hơn. Nếu đã trả lời sai thì nhận lỗi về câu trả lời của mình.

**AI nói nguyên văn khi phát hiện mâu thuẫn:**

> Bạn tính đúng: √0,25 = 0,5. Theo định nghĩa ở tài liệu buổi 3, §3.3, độ lệch chuẩn là căn bậc hai của phương sai. Nhưng cùng mục có câu “độ lệch chuẩn luôn nhỏ hơn phương sai”; ví dụ bạn đưa cho thấy câu này cần giảng viên xem lại. Mình không dùng câu đó để kết luận bạn tính sai và không tự công bố đính chính thay giảng viên. Bạn có thể xem trước câu hỏi gửi TA bên dưới. TA làm việc trở lại từ 08:00 ngày 13/11; chưa có giờ phản hồi được xác nhận.

**Người dùng thấy gì và làm gì tiếp:**

- **A1 — Nhãn ngay dưới câu trả lời:** “Tài liệu có điểm chưa khớp — Cần giảng viên xác minh”. Tách phần **phép tính đã kiểm** khỏi phần **câu trong tài liệu cần xem lại**; không dùng một điểm tin cậy chung như “95% đúng”, vì tìm đúng mục không chứng minh nội dung mục đó đúng.
- **A2 — Thẻ bằng chứng:** “Buổi 3 · §3.3 · Phương sai và độ lệch chuẩn”, hiện định nghĩa và câu gốc “Vì là căn bậc hai, độ lệch chuẩn luôn nhỏ hơn phương sai.” Đặt cạnh phép kiểm `0,5 × 0,5 = 0,25` để học viên tự đối chiếu. Đây là trích đoạn cần xác minh, không gắn nhãn “đã được giảng viên duyệt”.
- **A3 — Điều khiển:** “Xem trước câu hỏi gửi TA”, “Báo câu trả lời sai”, “Học tiếp phần khác”. Bản xem trước chứa câu hỏi, phép tính, đoạn §3.3 đang mâu thuẫn; học viên sửa nội dung hoặc hủy trước khi bấm “Gửi TA”. Không gửi toàn bộ lịch sử chat mặc định.
- **Nếu học viên không bấm gì:** chưa chuyển câu hỏi, chưa ai được báo; nhãn cần xác minh vẫn nằm cạnh câu trả lời. AI không tự đăng nội dung này thành FAQ.

**Đường sửa khi AI đã lỡ nói “theo §3.3, bạn tính sai”.** Học viên bấm “Báo câu trả lời sai” hoặc nhắn lại phép tính. AI đối chiếu ngay định nghĩa và ví dụ, rồi nói:

> Xin lỗi, câu trả lời trước của mình đã kết luận sai về phép tính của bạn. √0,25 = 0,5 là đúng. Mình đã dựa vào câu “luôn nhỏ hơn” ở §3.3 mà chưa kiểm tra mâu thuẫn. Câu đó cần giảng viên xem lại; mình chưa thể coi nó là căn cứ để bác phép tính của bạn. Bạn có thể xem trước câu hỏi gửi TA để nhờ xác minh tài liệu.

Tin cũ được gắn **“Câu trả lời đã được sửa”**, liên kết tới lời sửa ngay bên cạnh, thay vì âm thầm đổi nội dung. Học viên không phải mở hội thoại mới hoặc tự tìm lại mã mục. Báo lỗi chỉ tạo bản nháp; việc gửi TA vẫn theo §3.4.

### 3.3. Kịch bản #8 — Gợi ý đúng nguồn nhưng làm lộ đáp án

**Loại lỗi và trách nhiệm.** Đây là **lỗi ngữ cảnh** nếu cơ chế “giảng bằng đoạn trích đúng tài liệu” vẫn chạy đúng thiết kế nhưng bỏ qua việc **Bài tập 3 đang mở**: câu về “thu nhập” ở A §3.2 trở thành lời giải cho A §3.5(b). Nếu hệ thống đã có quy tắc cấm giải hộ mà vẫn xuất đáp án thì còn là lỗi thực thi của hệ thống. Yêu cầu xin chép là ngoài phạm vi, không phải lỗi nhập liệu của người dùng; AI không trách móc hay nhận xét năng lực học viên.

**AI nói nguyên văn:**

> Mình hiểu bạn đang gấp. Bài tập 3 còn mở đến 13/11/2026 23:59 theo trang khoá học, nên mình chỉ hỗ trợ bước đầu và không viết hộ câu (b). Nhìn 8 con số ở §3.5, có giá trị nào khác hẳn phần lớn dữ liệu theo định nghĩa ở §3.4 không? Bạn thử tìm trước nhé.

**Người dùng thấy gì và làm gì tiếp:**

- **B1 — Thẻ trạng thái:** “Bài tập 3 · Đang mở · Hạn 13/11/2026 23:59”, nguồn **Trang khoá học · Bài tập 3**. Ngay dưới là nhãn “Chỉ gợi ý bước đầu”. Đây là giới hạn hỗ trợ đã biết, không phải AI thiếu tự tin vào đáp án.
- **B2 — Thẻ bằng chứng cho gợi ý:** “Buổi 3 · §3.4: Giá trị khác hẳn phần lớn dữ liệu.” Không tự ghép đoạn “thu nhập” ở §3.2 vào câu trả lời hay thẻ gợi ý; cũng không nêu hộ giá trị ngoại lai hoặc chọn hộ con số mô tả lương điển hình. Học viên vẫn có quyền tự đọc tài liệu gốc.
- **B3 — Điều khiển:** ô “Em đang nghĩ như thế này…”, nút “Dừng gợi ý”, “Hỏi TA”, “Gợi ý đang lộ đáp án”. Học viên tự viết cách nghĩ; AI có thể nhắc cách tự kiểm nhưng không xác nhận kết luận của câu (b), viết lại thành câu nộp bài, hoặc tăng dần gợi ý thành lời giải. “Dừng gợi ý” kết thúc hỗ trợ ở bước hiện tại.
- **Nếu vẫn xin “chỉ cho đáp án lần này”:** giữ giới hạn đã nêu, không lặp gợi ý bằng cách diễn đạt ngày càng lộ lời giải. Nếu muốn học khái niệm bằng bài đã có đáp án, có thể chuyển sang Bài tập 2, kiểm tra trạng thái từ B trước khi giải thích đầy đủ.
- **Nếu học viên không làm gì:** không sinh thêm gợi ý, không tự chuyển TA hay đăng FAQ. Hạn nộp giữ nguyên; việc hỏi TA không phải yêu cầu gia hạn đã được chấp thuận.

**Đường sửa khi AI đã lỡ lộ lời giải.** Khi học viên bấm “Gợi ý đang lộ đáp án” hoặc hệ thống phát hiện, dừng phần nội dung chưa gửi và nói:

> Xin lỗi, gợi ý trước của mình đã đi quá mức hỗ trợ cho bài đang mở. Mình sẽ dừng đưa thêm lời giải. Phần bạn đã đọc thì không thể hoàn tác; mình có thể giúp bạn quay lại cách tự kiểm hoặc soạn câu hỏi để bạn xem trước rồi gửi TA.

Gợi ý cũ được gắn **“Gợi ý đã vượt phạm vi”**; lời sửa không lặp lại đáp án. Không gọi việc ẩn tin là “thu hồi kiến thức”, không hứa đã khắc phục hoàn toàn, không quy lỗi hay tự phạt học viên. Nếu học viên chọn báo TA, bản xem trước chỉ kèm phần hội thoại liên quan để TA hiểu lỗi của trợ lý.

### 3.4. Ai được báo, khi nào, thấy gì?

Đây là luồng **đề xuất cho sản phẩm**, dùng `chuyen_TA` của track; bài nộp không thực hiện gửi thật. Soạn/xem trước là bước giao diện trước khi gọi tool, không phải một tool gửi mới.

| Trạng thái | Học viên thấy gì | Ai nhận, nhận lúc nào, nhận gì |
|---|---|---|
| Chưa xác nhận gửi | “Bản nháp — Chưa gửi TA”, cho sửa hoặc hủy. | Chưa ai nhận. Với #1, nháp gồm câu hỏi, A §3.3 và phép tính mâu thuẫn; với #8, gồm chỗ đang kẹt và gợi ý đã nhận, hoặc đoạn AI vượt phạm vi nếu đang báo lỗi. |
| Đang chuyển / chuyển thành công | Khi đang chuyển: “Đang chuyển câu hỏi”. Chỉ sau kết quả thành công của tool mới hiện “Đã chuyển câu hỏi — Chờ TA; TA làm việc từ 08:00 ngày 13/11”. | Câu hỏi vào hàng chờ TA ngay khi chuyển thành công. Nếu gửi lúc 23:00 ngày 12/11, ca TA kế tiếp bắt đầu **sau 9 giờ**; không đồng nghĩa TA đọc hoặc trả lời ngay 08:00. TA thấy nội dung học viên đã duyệt và thời điểm gửi. |
| Gửi thất bại / chưa xác nhận được kết quả | Thất bại: “Chưa gửi được — Giữ lại nội dung để thử lại hoặc sao chép hỏi TA”. Nếu mất kết nối và chưa rõ kết quả: “Chưa xác nhận đã chuyển”; kiểm tra trạng thái trước khi gửi lại để tránh trùng. | Không khẳng định TA đã nhận khi chưa có xác nhận; không biến lỗi gửi thành thông báo thành công. |
| Đã chuyển nhưng chưa có phản hồi | Giữ nhãn “Chờ TA”, cho học tiếp phần khác. Không hứa giờ giải quyết vì dữ liệu B chỉ có giờ làm việc. | #1: TA nhận để chuyển giảng viên xác minh câu §3.3; việc báo giảng viên do **TA thực hiện**, vì không có tool nhắn giảng viên trực tiếp. #8: TA hỗ trợ phương pháp hoặc xem lại gợi ý của AI; không được hiểu là đã cho phép giải hộ. |

Chỉ hiển thị phản hồi/đính chính đã xác nhận khi TA hoặc giảng viên thực sự cập nhật. Hết ca mà chưa xử lý thì tiếp tục ghi đang chờ, không tự suy ra đồng ý, không tự đăng FAQ và không đổi hạn bài. Chi phí chờ ở #1 được giảm bằng việc giải thích phép tính ngay; ở #8 bằng gợi ý bước đầu ngay.

### 3.5. Ba nguyên tắc HAX/PAIR và chỗ thể hiện cụ thể

| Nguyên tắc | Áp dụng vào #1 | Áp dụng vào #8 |
|---|---|---|
| **HAX G10 — Thu hẹp phạm vi khi nghi ngờ** ([nguồn](https://www.microsoft.com/en-us/haxtoolkit/guideline/scope-services-when-in-doubt/)) | Câu “không dùng câu đó để kết luận bạn tính sai” và nhãn **A1**: chỉ khẳng định phép tính đã kiểm; chuyển phần xác minh nguồn cho người có trách nhiệm. | **B1/B2** giới hạn hỗ trợ ở bước đầu. Nếu không đọc được trạng thái bài từ B, chưa sinh gợi ý theo số liệu đề; nói rõ chưa xác minh được và đề nghị hỏi TA, không đoán bài đã đóng. |
| **HAX G9 — Sửa dễ dàng** ([nguồn](https://www.microsoft.com/en-us/haxtoolkit/guideline/support-efficient-correction/)) | Nút “Báo câu trả lời sai” tại **A3**, lời sửa đặt cạnh tin cũ; bản nháp gửi TA sửa được, không bắt kể lại toàn bộ. | Nút “Gợi ý đang lộ đáp án” tại **B3** dừng hỗ trợ vượt phạm vi ngay; lời sửa nhận trách nhiệm và cho quay về tự kiểm. Không đưa nút hoàn tác giả cho gợi ý đã đọc. |
| **PAIR — Errors + Graceful Failure** ([nguồn](https://pair.withgoogle.com/guidebook-v2/chapter/errors-failing/)) | Nhận lỗi hệ thống khi đã kết luận sai; **A2 + luồng §3.4** cho xem căn cứ và chuyển đúng vấn đề, kèm giới hạn về giờ TA. | Nhận diện lỗi ngữ cảnh: đúng tài liệu vẫn có thể sai với bài đang mở. **B3** cho dừng hoặc hỏi người, trong khi gợi ý bước đầu giúp học viên tiếp tục học. |

Chọn nhãn mô tả **điều đã biết, điều cần xác minh và hành động kế tiếp** thay cho phần trăm tin cậy: fixture không có dữ liệu hiệu chuẩn, còn hai ca có thể tìm đúng nguồn mà vẫn gây hại. Các mã A/B sẽ được gắn vào ảnh prototype ở §5.

### 3.6. Những lỗi sửa câu chữ không cứu được

| Lỗi | Vì sao câu chữ không đủ | Yêu cầu thiết kế mang sang chặng 4–5 |
|---|---|---|
| **#1 — Nguồn có mệnh đề sai** | Thêm “theo tài liệu” hoặc “có thể” trước một kết luận sai vẫn làm học viên học sai. Có trích dẫn không có nghĩa đã được kiểm chứng. | Đề xuất lưu trạng thái **“cần xác minh” theo đúng câu/đoạn nguồn** sau khi phát hiện mâu thuẫn; không dùng đoạn đó làm kết luận chắc chắn hay đưa vào FAQ trong lúc chờ. Giữ các định nghĩa không mâu thuẫn để học tiếp. TA/giảng viên xác minh bằng quy trình người thực hiện; AI không có tool tự sửa tài liệu. Nhãn trên chat phải gắn với nguồn, không chỉ với một lần trả lời. |
| **#8 — Gợi ý làm lộ đáp án** | Mở đầu bằng “mình chỉ gợi ý” nhưng sau đó chép câu về thu nhập ở §3.2 vẫn lộ lời giải. Gửi rồi thì lời xin lỗi không đảo lại được. | Kiểm tra trạng thái bài từ B **trước khi soạn**, rồi soát toàn bộ gợi ý **trước khi hiển thị/gửi qua `goi_y_bai_tap`**; không phát dần bản nháp chưa soát. Soát cả đoạn trích và chuỗi gợi ý đã gửi, tránh chia nhỏ lời giải qua nhiều lượt. Ca #8 dùng câu hỏi bước đầu đã viết ở §3.3; nếu chưa bảo đảm giới hạn thì dừng nội dung đó và cho hỏi TA. Học viên bấm “đồng ý cho đáp án” không vượt được quy tắc bài đang mở. |

Các bước lưu trạng thái nguồn và soát gợi ý ở trên là **thiết kế bổ sung**, chưa phải khả năng có sẵn trong bảng tool hoặc cơ chế đã được kiểm thử. Nếu giảng viên xác nhận cần đính chính cho cả lớp, việc duyệt và dùng `dang_FAQ` được quyết định ở §4; AI không tự đăng khi mới phát hiện mâu thuẫn.

### 3.7. Đối chiếu bốn đường trải nghiệm

| Đường | Chỗ thể hiện trong thiết kế |
|---|---|
| **Happy path** | Đối chiếu #11: Bài tập 2 đã hết hạn và có đáp án trong B → được giải thích đầy đủ theo **dữ liệu A §3.1**, không áp giới hạn của Bài tập 3 cho mọi bài. |
| **Low-confidence** | Đối chiếu #5: hỏi đúng một câu “Bạn hỏi ‘dữ liệu lệch’ ở §3.2 hay ‘độ lệch chuẩn’ ở §3.3?”; chưa chọn hộ ý định để giảng. |
| **Failure / không đủ căn cứ** | #1: có nguồn nhưng mâu thuẫn → **A1/A2**, trả lời phần đã kiểm và cho chuyển xác minh. #8: nếu chưa xác minh được trạng thái bài, không đoán rồi gửi gợi ý. |
| **Correction** | Nhánh sửa ở §3.2 và §3.3: nhận lỗi cụ thể, đánh dấu tin cũ, dừng hành vi gây hại, giữ đường học tiếp và bản xem trước gửi TA. |

## §4. Mức tự chủ  (chặng 4)
Với mỗi tool:
- Mức của nhóm (tự làm / cần người duyệt / cấm). Nếu cần người duyệt: ai duyệt · người duyệt thấy gì · quá hạn thì sao.
- Lý do theo cost-of-error: sai thì ai chịu gì · đảo lại được không · chờ người thì mất gì.
- Phương án đã cân nhắc và vì sao loại.
Thêm:
- Tool khó xếp nhất: mỗi người từng chọn gì, cái giá của mỗi phía (trỏ về kịch bản ở §2), nhóm chốt thế nào.
- Thử mức đã đặt trên 2 kịch bản đắt nhất + 1 kịch bản bình thường: cái sai có bị chặn không? còn việc nào làm khi lẽ ra phải hỏi? người dùng bình thường có phải chờ vô ích không?
- Luật thêm hoặc tool tách bước (nếu có), và vì sao.
- Một mức tự chủ đã đổi lời hứa nào với người dùng.

## §5. Prototype  (chặng 5)
- Link hoặc file · công cụ · phần nào mock · có lời gọi AI thật không.
- 1–2 ảnh có đánh số; mỗi số: thể hiện gì · nguyên tắc HAX/PAIR nào · mức tự chủ nào.
- Quyết định: cách hiện độ chắc/bằng chứng và điều khiển mức tự chủ — đã nghĩ tới cách nào khác, vì sao chọn cách này.

## §6. Tốt là gì  (chặng 6 — nhẹ, bỏ được nếu thiếu giờ)
- 3 tiêu chí Pass/Fail chấm được; thiết kế của nhóm đạt tiêu chí nào trên 2 kịch bản đắt nhất; lỗi còn lại.

## §7. Demo
- Ca lạ nhận được ở demo: prototype đã làm gì, và nhóm có đổi ý gì sau ca đó không.
