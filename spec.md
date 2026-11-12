# Dàn ý bài nộp *(spec.md — nộp trước 23:59 ngày lab của lớp)*

> Copy dàn ý này vào `spec.md` của nhóm. Đây **không** phải form để điền đủ ô: mỗi mục chỉ cần đủ **bằng chứng** và **lập luận** ghi bên dưới. Viết ngắn, gạch đầu dòng là được. Hướng dẫn từng chặng: `02-guide.md`. Cách chấm: `04-rubric.md`.
>
> **Một quyết định = bốn ý:** đã cân nhắc phương án nào · chọn phương án nào · vì sao · loại các phương án kia vì sao. Bằng chứng = lập luận trỏ về một chỗ cụ thể: tool nào, dòng dữ liệu nào của track, điều gì trong mục "Sản phẩm thật hôm nay", chỗ nào trên prototype (ảnh đánh số). Không chạy agent.


# Bài nộp LAB5 — T2 · Nhóm NhomABC
| Họ và Tên | Mã Học Viên | Việc đã làm |
|---|---|---|
| Vũ Nguyễn Hoàng Minh | 2A202603541 | §5 Prototype (`prototype/index.html`: màn hình học viên + màn hình TA, chế độ Mock và AI thật OpenAI, ảnh đánh số) |
| Nguyễn Tuấn Phong | 2A202603712 | §1 Lát cắt & phạm vi · §2 Kịch bản rủi ro (11 kịch bản, chọn 2 kịch bản đắt nhất) · §4 Mức tự chủ (4 tool, tách `dang_FAQ`, phiếu xếp mức, thử mức trên 3 kịch bản) |
| Bùi Thế Anh | 2A202603546 | §3 Khi AI sai thì người dùng thấy gì, §5 Prototype |

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
Bối cảnh dùng cho mọi quyết định bên dưới: học viên hỏi sau 22:00, ca TA tiếp theo bắt đầu 08:00 sáng hôm sau (dữ liệu B chỉ có giờ làm việc, không có giờ phản hồi cam kết), Bài tập 3 hết hạn 13/11/2026 23:59. Vì vậy "cần người duyệt" ban đêm nghĩa là **chờ ít nhất tới 08:00**. Mỗi mức bên dưới đều tính cả cái giá của việc chờ đó.

### Bảng tổng hợp

| Tool | Mức của nhóm | Ai duyệt | Một câu lý do |
|---|---|---|---|
| `tra_cuu_tai_lieu` | **tự làm** | — | Chỉ đọc, kết quả luôn hiện kèm mã mục để học viên tự kiểm; chờ người thì mất toàn bộ giá trị lúc tối muộn |
| `goi_y_bai_tap` | **tách theo trạng thái bài** (xem dưới) | TA (gợi ý sâu cho bài đang mở) | Gợi ý đã đọc thì không rút lại được (#8), nhưng chặn hết thì học viên kẹt lúc 23:00 bỏ bài |
| `chuyen_TA` | **cần học viên xác nhận** (bản xem trước, xem §3.4) | Học viên | Nội dung gửi đi là của học viên; thêm một cú bấm không làm chậm gì, vì ca TA chỉ bắt đầu lúc 08:00 |
| `dang_FAQ` | **tách 2 bước:** soạn = tự làm · đăng = **cần giảng viên duyệt** | Giảng viên (TA được duyệt câu không liên quan tài liệu sai) | Một câu sai đến cả lớp, gỡ được nhưng nhiều người đã đọc (#1); FAQ không gấp nên chờ duyệt gần như không mất gì |

### Từng tool

**1. `tra_cuu_tai_lieu`: tự làm**
- **Sai thì ai chịu gì:** tool trả nhầm mục thì AI trích nhầm, học viên đọc sai đoạn. Nhưng mã mục (§3.x) luôn hiện cạnh câu trả lời, nên học viên tự mở tài liệu và thấy được chỗ lệch. Đây là lỗi "nhẹ".
- **Đảo được không:** không có gì để đảo, vì tool chỉ đọc.
- **Chờ người thì mất gì:** mất toàn bộ giá trị. Lúc 23:00 không có ai để duyệt, học viên chờ tới 08:00 chỉ để biết trung vị ở §3.2 (#3).
- **Luật kèm theo:**
  - Chỉ tìm trong tài liệu các buổi đã mở (1–3).
  - Mọi câu về nội dung phải kèm mã mục.
  - Không tìm thấy thì nói "tài liệu không có", không lấp bằng kiến thức ngoài (#2, #4).
- **Đã loại:** "cần TA duyệt" là chờ vô ích cho một việc chỉ đọc. Lưu ý: nguồn sai như #1 **không phải lỗi của mức tự chủ**. Tool chạy đúng, chỉ nội dung tài liệu sai. Rủi ro này được xử lý bằng `chuyen_TA` và bước tách của `dang_FAQ`, không xử lý bằng cách bắt duyệt việc tra cứu.

**2. `goi_y_bai_tap`: tách theo trạng thái bài (dữ liệu B)**

| Loại yêu cầu | Mức | Vì sao |
|---|---|---|
| Bài **đã hết hạn**, đã công bố đáp án (Bài tập 2) | **tự làm**, giải đầy đủ | Không còn gì để chép. Chặn ở đây là lỗi #11: học viên kẹt ở chỗ sai mà không ai gỡ |
| Bài **đang mở**, gợi ý **bước đầu** dưới dạng câu hỏi ngược ("có số nào khác hẳn phần còn lại không? §3.4 gọi nó là gì?") | **tự làm** | Học viên kẹt lúc 23:00 cần đi tiếp ngay. Câu hỏi ngược không chứa đáp án, học viên vẫn phải tự nghĩ |
| Bài đang mở, gợi ý **sâu hơn bước đầu** | **cần TA duyệt** | AI soạn gợi ý vào hàng chờ của TA. TA thấy câu hỏi, gợi ý nháp, mã mục được trích và hạn bài, rồi sửa hoặc gửi |
| Bài đang mở, **đáp số, xác nhận đúng/sai, viết hộ** (#7, #8) | **cấm** | Đọc rồi là chép được, không đảo lại được. Không có bước xác nhận nào chặn được, vì chính học viên là người muốn nhận |

- **Gợi ý sâu không ai duyệt kịp thì sao:** gợi ý nằm trong hàng chờ, **không tự gửi**. Hỏi đêm 12/11 thì ca TA bắt đầu 08:00 ngày 13/11, vẫn còn khoảng 16 giờ trước hạn. Hỏi sau 22:00 ngày 13/11 thì gợi ý sâu không tới kịp. Nhóm chấp nhận cái giá này, và AI phải nói rõ ngay lúc đó: "gợi ý thêm cần TA xem; ca TA tiếp theo bắt đầu 08:00, sau hạn nộp".
- **Luật nội dung cho mọi gợi ý của bài đang mở:**
  - không chứa con số là đáp án;
  - không nói đúng hay sai với con số học viên đưa ra;
  - không trích đoạn tài liệu chứa sẵn kết luận của câu hỏi. Ví dụ: câu "thường dùng cho dữ liệu lệch như **thu nhập**" ở §3.2 chính là đáp án câu (b), vì Bài tập 3 là lương.

**3. `chuyen_TA`: cần học viên xác nhận**
- **Cách chạy:** AI tự **soạn** bản nháp: câu hỏi, đoạn tài liệu liên quan, chỗ học viên đang kẹt. Học viên xem trước, sửa hoặc huỷ, rồi bấm "Gửi TA". Chỉ phần hội thoại liên quan được gửi, không gửi toàn bộ lịch sử chat (§3.4).
- **Sai thì ai chịu gì:**
  - Chuyển nhầm thì TA nhận thừa một câu hỏi, mất vài phút.
  - Cái giá thật nằm ở **nội dung gửi đi**. Ở #9, học viên kể "em ốm"; ở #8, tin nhắn có câu "em chép vào thôi". Gửi cho TA khi học viên chưa xem thì lộ chuyện riêng và gắn nhãn học viên.
- **Đảo được không:** được (theo bảng tool), nhưng TA có thể đã đọc.
- **Chờ người thì mất gì:** gần như không. Ca TA bắt đầu 08:00, nên một cú bấm lúc 23:00 không làm câu hỏi tới TA chậm hơn chút nào.
- **Học viên không bấm thì sao:** câu hỏi không được chuyển. Riêng lỗi tài liệu (#1) vẫn tới được giảng viên qua `soan_FAQ` (mục 4), bằng một nháp ẩn danh. Vì vậy lỗi nguồn không phụ thuộc vào việc một học viên có bấm hay không.
- **Luật kèm theo:**
  - AI chỉ nói "đã chuyển cho TA" **sau khi tool trả về thành công**, kèm giờ do tool báo. Luật này chặn lỗi "hứa việc mình không làm được" (#9).
  - Chuyển câu hỏi **không** có nghĩa là hứa kết quả: không hứa gia hạn, không hứa đáp án.
  - Không có tool nhắn giảng viên trực tiếp. Lỗi tài liệu đi qua TA, và **TA** chuyển cho giảng viên.
- **Đã loại:**
  - *Tự làm:* ban đầu được chọn vì việc chuyển rẻ và đảo được. Loại vì không xét tới nội dung riêng của học viên, và vì chờ một cú bấm thực tế không tốn gì.
  - *Cấm:* học viên mất đường duy nhất tới người thật lúc tối muộn.

**4. `dang_FAQ`: tách thành 2 tool**
- **`soan_FAQ` (tool mới): tự làm.** AI soạn câu hỏi và câu trả lời vào hàng chờ của giảng viên. Cả lớp **chưa thấy** gì, nên sai cũng không tốn gì. Nháp có cờ "tài liệu có thể sai" chỉ chứa đoạn tài liệu và chỗ mâu thuẫn (ví dụ §3.3 với phương sai 0,25), **không chứa tên hay tin nhắn của học viên**. Đây là đường để giảng viên biết lỗi nguồn ngay cả khi học viên không gửi TA.
- **`dang_FAQ`: cần giảng viên duyệt.**
  - **Người duyệt thấy:** câu hỏi, câu trả lời nháp, đoạn tài liệu được trích kèm mã mục, số học viên đã hỏi câu tương tự, và cờ **"liên quan tài liệu có thể sai"** nếu có.
  - **Ai được duyệt:** câu có cờ đó thì chỉ giảng viên duyệt. Câu khác thì TA duyệt được.
  - **Quá hạn thì sao:** nháp nằm nguyên trong hàng chờ. **Không bao giờ tự đăng khi hết hạn duyệt.**
  - **Luật thêm:** không đăng FAQ về Bài tập 3 trước 13/11 23:59.
- **Sai thì ai chịu gì:** cả lớp học sai. Gỡ được, nhưng nhiều người đã đọc. #1 là ví dụ rõ nhất: câu sai ở §3.3 đi kèm mã mục, đăng lên FAQ thì cả lớp tin.
- **Chờ người thì mất gì:** gần như không. Người hỏi đã được trả lời riêng ngay lúc đó; FAQ chỉ phục vụ người hỏi sau, mà họ cũng được trợ lý trả lời riêng.
- **Đã loại:**
  - *Tự làm:* #1 lan ra cả lớp.
  - *Cấm:* mất tín hiệu có giá trị cho giảng viên. Nhiều học viên vấp cùng một chỗ, như §3.3, là dấu hiệu tài liệu có vấn đề.

### Tool khó xếp nhất: `goi_y_bai_tap`

**Phiếu xếp mức độc lập (5 phút, chưa bàn):**

| Tool | Phong | Thế Anh | Minh |
|---|---|---|---|
| `tra_cuu_tai_lieu` | Tự làm | Tự làm | Tự làm |
| `goi_y_bai_tap` | Tự làm | Cấm (vì sợ #7, #8) | Cần TA duyệt |
| `chuyen_TA` | Tự làm | Cần SV xác nhận | Tự làm |
| `dang_FAQ` | Cần TA duyệt | Cấm (sợ sai cả lớp) | Cần TA duyệt |

**Mức nào cũng có giá:**
- **Tự làm toàn bộ:** #8 thì học viên chép được câu (b), không rút lại được; #7 thì AI xác nhận 15,25 và 11,5 là đúng.
- **Cấm toàn bộ:** học viên kẹt lúc 23:00 bỏ bài (lời của học viên trong track: "kẹt một chữ trong tài liệu là coi như bỏ"). #11 cũng bị chặn nhầm, dù bài 2 đã hết hạn.
- **Cần TA duyệt toàn bộ:** mọi gợi ý, kể cả bước đầu, phải chờ tới 08:00. Đó là chờ vô ích cho phần không có rủi ro.

**Cách chốt:** không chọn một mức cho cả tool. Nhóm tách theo **trạng thái bài** (lấy từ dữ liệu B) và **độ sâu của gợi ý**, như bảng ở mục 2. Câu hỏi quyết định là: *gợi ý này đọc xong rồi thì có thể chép thẳng vào bài không?* Không chép được thì tự làm. Có thể chép thì cấm. Ở giữa thì TA duyệt.

Kết quả là cả ba phiếu đều được giữ một phần:
- Phiếu "cấm" của Thế Anh giữ cho đáp số, xác nhận đúng/sai và viết hộ.
- Phiếu "cần TA duyệt" của Minh giữ cho gợi ý sâu.
- Phiếu "tự làm" của Phong giữ cho gợi ý bước đầu và bài đã hết hạn.

**Hai chỗ lệch khác trong phiếu:**
- **`chuyen_TA`:** Thế Anh chọn "cần học viên xác nhận", hai người còn lại chọn "tự làm". Nhóm chốt theo Thế Anh. Lý do: nội dung gửi đi là của học viên (#8, #9), và ca TA bắt đầu 08:00 nên thêm một cú bấm không làm chậm gì. Cái lo của phía "tự làm" là lỗi tài liệu #1 không tới giảng viên. Nhóm giải quyết lo đó bằng nháp ẩn danh của `soan_FAQ`, không cần bỏ bước xác nhận.
- **`dang_FAQ`:** Thế Anh chọn "cấm" vì sợ sai lan cả lớp. Phong và Minh chọn "cần TA duyệt". Nhóm chốt **tách hai bước, giảng viên duyệt câu liên quan tài liệu sai**. Cách này chặn đúng cái Thế Anh lo, mà không mất tín hiệu "nhiều người vấp cùng một chỗ". Câu liên quan tài liệu sai cần giảng viên chứ không phải TA, vì chỉ giảng viên quyết được tài liệu đúng hay sai (§1, việc không làm số 3).

### Thử mức đã đặt trên 3 kịch bản

| Kịch bản | Với mức của nhóm, AI làm gì · người dùng thấy gì | Cái sai ở §2 có bị chặn không? | Còn việc nào AI làm khi lẽ ra phải hỏi? | Người dùng bình thường có phải chờ vô ích không? |
|---|---|---|---|---|
| **#1** tài liệu §3.3 sai | `tra_cuu_tai_lieu` trả §3.3 (tự làm). AI soạn sẵn câu hỏi gửi TA; học viên xem trước rồi bấm gửi (`chuyen_TA`, cần học viên xác nhận). Chỉ sau khi tool báo thành công, học viên mới thấy "Đã chuyển — Chờ TA, ca TA bắt đầu 08:00"; TA chuyển tiếp cho giảng viên. `soan_FAQ` tự tạo nháp ẩn danh có cờ "tài liệu có thể sai"; `dang_FAQ` chờ giảng viên | **Lan cả lớp: chặn được**, vì đăng FAQ cần giảng viên duyệt. **Bảo học viên đúng là sai: chặn được một phần.** Mức tự chủ không sửa được nguồn sai; nó chỉ bảo đảm lỗi không lan và có người biết. Phần còn lại thuộc thiết kế câu chữ ở §3 | Không | Không. Học viên nhận trả lời ngay; chỉ FAQ phải chờ, mà FAQ không gấp |
| **#8** xin viết hộ câu (b) | Viết hộ là **cấm**: AI không có nút làm, nói rõ không viết hộ được. AI tự đưa gợi ý bước đầu (câu hỏi ngược về giá trị 45 và §3.4). Học viên muốn gợi ý sâu hơn thì gợi ý vào hàng chờ TA, kèm giờ trả lời | **Chặn được.** Đáp án và câu trích "thu nhập" ở §3.2 đều không được gửi | **Rủi ro còn lại:** gợi ý bước đầu do AI tự soạn, nên vẫn có thể vô tình lộ đáp án. Luật nội dung ở mục 2 giảm rủi ro này, nhưng không về 0 | Có chờ, nhưng **có chủ đích**: gợi ý sâu chờ tới 08:00, vẫn còn khoảng 16 giờ trước hạn |
| **#3** "slide 12" (bình thường) | `tra_cuu_tai_lieu` (tự làm) không tìm thấy slide nào. AI trả ngay: "tài liệu buổi 3 không có slide đánh số; trung vị ở §3.2", kèm đoạn trích | Chặn được lỗi bịa nguồn | Không | **Không.** Không có bước người duyệt nào |

### Luật thêm và tool tách bước

1. **Tách `dang_FAQ` thành `soan_FAQ` (tự làm) và `dang_FAQ` (giảng viên duyệt).** Chặn #1 lan ra cả lớp mà vẫn giữ được tín hiệu "nhiều người vấp cùng một chỗ".
2. **`goi_y_bai_tap` phân nhánh theo trạng thái bài** (đang mở / đã hết hạn, lấy từ dữ liệu B). Chặn #7 và #8, đồng thời tránh chặn nhầm #11.
3. **Luật nội dung cho bài đang mở:** không con số đáp án, không xác nhận đúng/sai, không trích đoạn chứa sẵn kết luận (#8: câu "thu nhập" ở §3.2).
4. **Chỉ nói "đã làm" sau khi tool trả về thành công**, và mọi việc không có tool (gia hạn, chấm điểm) thì nói thẳng là không làm được. Chặn #9.
5. **`tra_cuu_tai_lieu` chỉ trong phạm vi buổi đã mở.** Chặn #4.

### Mức tự chủ đã đổi lời hứa nào với người dùng

- **`goi_y_bai_tap`:**
  - *Nếu tự làm toàn bộ*, lời hứa là "trợ lý giúp bạn làm bài lúc nào cũng được".
  - *Với mức của nhóm*, lời hứa thành: "trợ lý giúp bạn **bắt đầu** ngay; phần còn lại bạn tự làm, hoặc chờ TA xem gợi ý sâu hơn từ 08:00".

  Học viên mất cảm giác "có người làm hộ", đổi lại bài nộp là bài của chính mình, đúng kết quả của lát cắt.
- **`dang_FAQ`:**
  - *Nếu tự làm*, lời hứa là "FAQ do AI cập nhật tức thì".
  - *Với mức của nhóm*, lời hứa thành: "FAQ **đã được giảng viên kiểm**".

  Chậm hơn, nhưng đó là lý do để cả lớp tin FAQ.

## §5. Prototype  (chặng 5)


### 5.1. File, công cụ và phạm vi mô phỏng

- **File chạy:** [prototype/index.html](prototype/index.html). Tải về rồi mở bằng Chrome/Edge; xem hướng dẫn tại [prototype/README.md](prototype/README.md). Đây là file chạy cục bộ, chưa có link hosting.
- **Công cụ:** một file HTML chứa CSS và JavaScript thuần. Hai màn hình chuyển bằng nút **“Học viên”** và **“TA / Giảng viên”**; không đăng nhập, không backend. Các khung chat, bằng chứng, hàng chờ và FAQ nằm trong hai màn hình đó.
- **Dữ liệu dựng:** tài liệu A §3.1–§3.5, trang khoá học B, Bài tập 3 đang mở và giờ mô phỏng 23:00 ngày 12/11/2026. HV-07, HV-12, TA Lan, lớp 38 học viên và số người hỏi tương tự là dữ liệu mẫu, không phải dữ liệu thu thập thực tế.
- **Chế độ Mock:** câu trả lời và các nhánh sửa lỗi được viết sẵn; câu nhập tự do được ghép kịch bản theo từ khoá. Tra cứu là đối chiếu với dữ liệu có trong file. Chuyển TA, duyệt gợi ý, đăng/gỡ FAQ chỉ cập nhật trạng thái trong tab; không gửi cho TA hay lớp thật. Thời điểm 08:05/08:10 trên phản hồi TA là giờ mô phỏng, không phải hệ thống đã đợi đến sáng.
- **Chế độ AI thật:** đã có mã gọi OpenAI Chat Completions, model mặc định trong giao diện là `gpt-4o-mini`; nhận câu trả lời rồi kiểm tra trích dẫn và một số mẫu lộ đáp án trước khi hiện. API key do người demo nhập lúc chạy, giữ trong bộ nhớ tab, không ghi sẵn trong mã nguồn hay trường log. Các thao tác TA/FAQ vẫn là mô phỏng ngay cả khi bật AI thật.
- **Bằng chứng AI thật:** hiện chưa có `ai-log.json` hoặc ảnh lời gọi thành công trong bài nộp; hai ảnh dưới đều ở chế độ **Mock**, panel log ghi **0 lời gọi**. Vì vậy chưa nhận bonus “đã có lời gọi AI thật”. Khi có lời gọi thành công với dữ liệu dựng, dùng nút “Tải ai-log.json” để lưu bằng chứng; việc có nút kết nối chưa chứng minh đã gọi thành công.

### 5.2. Luồng demo khoảng 4 phút

Mở lại trang bằng **F5** để bắt đầu từ dữ liệu mẫu. Nút “Làm mới hội thoại” chỉ xoá hội thoại, không xoá hàng chờ, FAQ hay cờ nguồn; không dùng nút này để giả lập một phiên hoàn toàn mới. Giữ chế độ **Mock**, bật **“Hiện mã chú thích”**.

| Thời lượng | Bấm vào đâu | Thấy gì, chứng minh quyết định nào |
|---|---|---|
| 0:00–0:30 | Màn hình **Học viên**, ca **#8** đã mở sẵn | Hạn Bài tập 3, nhãn “Chỉ gợi ý bước đầu”, câu hỏi ngược và căn cứ §3.4. AI hỗ trợ ngay nhưng không viết hộ câu (b). |
| 0:30–1:20 | **Hỏi TA** → sửa nháp → **Huỷ**; sau đó **Xin gợi ý sâu hơn** → **TA / Giảng viên** | Nháp câu hỏi chưa gửi khi chưa xác nhận. Gợi ý sâu vào hàng chờ; TA thấy câu hỏi, câu AI đã trả lời, gợi ý nháp và hạn bài. Học viên chưa nhận phần gợi ý sâu. |
| 1:20–1:50 | TA sửa gợi ý → **Duyệt và gửi gợi ý** → trở lại **Học viên** | Gợi ý chỉ xuất hiện sau thao tác duyệt, có nhãn TA. Có thể thử nhập `15,25` vào nháp để thấy cảnh báo và nút duyệt bị vô hiệu hoá, rồi sửa lại. |
| 1:50–2:40 | Bấm **#1 · Tài liệu §3.3 có câu sai** → mở thẻ trích dẫn | A1 tách phép tính đã kiểm khỏi câu cần xác minh; A2 cho đối chiếu nguồn. Bản hiện tại còn tự chuyển báo lỗi và có nút **Rút lại** ở C2 — đây là điểm lệch §4, ghi rõ tại §5.6. |
| 2:40–3:20 | **TA / Giảng viên** → xem nháp FAQ có cờ lỗi nguồn → đổi sang **Vai: Giảng viên** | TA không đăng được nháp có cờ. Giảng viên sửa nội dung, tích ô đã kiểm rồi mới bấm **Duyệt và đăng**; FAQ đã đăng có nút **Gỡ**. Đây chỉ là thao tác đóng vai trong prototype. |
| 3:20–4:00 | Trở lại **Học viên** → ca **#1 · AI đã lỡ nói “bạn tính sai” (đường sửa)** → **Báo câu trả lời sai** | Tin cũ được gắn “Câu trả lời đã được sửa”, có liên kết tới lời nhận lỗi và sửa ngay bên dưới. Nhánh tương ứng của #8 dùng ca **“AI đã lỡ lộ đáp án”** và nút **“Gợi ý đang lộ đáp án”**. |

Hai ca mang tên **“AI đã lỡ…”** cố ý hiển thị câu sai để demo đường sửa; đó là dữ liệu mô phỏng, không phải kết quả một lần model thật thất bại. Không dùng chúng làm bằng chứng rằng bộ soát đã chặn được lỗi.

### 5.3. Hai ảnh đánh số và ý nghĩa từng vị trí

**Ảnh 1 — Màn hình học viên:** ca #8 đã xin gợi ý sâu, ca #1 đã hiện mâu thuẫn nguồn. Ảnh chụp trực tiếp từ prototype ở chế độ Mock, mở các thẻ bằng chứng và bật chú thích có sẵn trong giao diện.

![Ảnh 1: Học viên — hai ca khó, bằng chứng và điều khiển A1–A3, B1–B3, C1–C4](prototype/stage5-01-hoc-vien.png)

**Ảnh 2 — Màn hình TA:** cùng phiên của ảnh 1, có gợi ý sâu đang chờ duyệt và nháp FAQ có cờ “Tài liệu có thể sai”. Vai hiện tại là TA nên nháp có cờ chưa đăng được.

![Ảnh 2: TA — hàng chờ gợi ý và nháp FAQ cần giảng viên duyệt tại C4](prototype/stage5-02-ta.png)

| Mã trên ảnh | Thể hiện gì | Nguyên tắc HAX/PAIR | Mức tự chủ liên quan |
|---|---|---|---|
| **A1 · ảnh 1** | Tách “Phép tính đã kiểm” khỏi “Câu trong tài liệu cần xem lại”; không biến tìm đúng nguồn thành kết luận nguồn đúng. | **G10** — thu hẹp phần khẳng định khi có mâu thuẫn. | AI tự trả lời phần kiểm được; việc xác minh/đính chính nguồn chuyển người. |
| **A2 · ảnh 1** | Mã §3.3, đoạn gốc, phần tô sáng và phép kiểm `0,5 × 0,5 = 0,25`; câu đang có vấn đề mang cảnh báo. | **PAIR — Errors + Graceful Failure** — thấy được chỗ lỗi và căn cứ để sửa. | `tra_cuu_tai_lieu`: **tự làm**, chỉ đọc. |
| **A3 · ảnh 1** | “Xem trước câu hỏi gửi TA”, “Báo câu trả lời sai”, “Học tiếp phần khác”; nhánh sửa giữ liên kết với câu cũ. | **G9** — sửa dễ; **PAIR** — có đường tiếp tục. | Câu hỏi riêng **cần học viên xác nhận**; mở nháp chưa phải gửi. |
| **B1 · ảnh 1** | Trạng thái bài và hạn nộp từ B, nhãn chỉ hỗ trợ bước đầu. | **G10** — giới hạn phạm vi hỗ trợ theo tình huống. | Bước đầu **tự làm**; đáp số/viết hộ **cấm**. |
| **B2 · ảnh 1** | Gợi ý có căn cứ §3.4; §3.5 cho đối chiếu đề bài, không chọn hộ kết luận câu (b). | **G10** — giữ gợi ý trong phần được phép hỗ trợ. | Tra cứu và gợi ý bước đầu **tự làm**. |
| **B3 · ảnh 1** | Ô cách nghĩ, “Dừng gợi ý”, “Hỏi TA”, “Gợi ý đang lộ đáp án”. | **G9** và **PAIR — Errors + Graceful Failure**. | Học viên điều khiển bước tiếp; dừng không thể hoàn tác phần đã đọc. |
| **C1 · ảnh 1** | Dấu “khớp tài liệu” cạnh đoạn trích, cho mở nguồn để kiểm. Dấu này kiểm đoạn có trong fixture, không chứng nhận kiến thức đúng. | **G10** — bám nguồn đã có; gắn với căn cứ tại A2. | `tra_cuu_tai_lieu`: **tự làm**, không cần hoàn tác vì chỉ đọc. |
| **C2 · ảnh 1** | Báo lỗi tài liệu đã vào hàng chờ, giờ ca TA tiếp theo và nút “Rút lại”. | **G9** — sửa/thu hồi thao tác khi còn tác dụng. | **Hiện tại tự làm + rút lại; chưa khớp §4 yêu cầu xác nhận.** Đây là bằng chứng của sai khác, không tính là đã đáp ứng quy tắc đó. |
| **C3 · ảnh 1; hàng chờ ảnh 2** | Không có nút giải hộ; gợi ý sâu có trạng thái chờ và màn hình TA sửa/duyệt. | **G10** và **PAIR** — giới hạn việc AI làm, giữ đường hỗ trợ. | Thấy cả ba mức: bước đầu **tự làm**; sâu hơn **TA duyệt**; đáp số/viết hộ **cấm**. |
| **C4 · ảnh 1 và 2** | AI chỉ soạn nháp FAQ; nháp có cờ lỗi nguồn yêu cầu vai giảng viên và ô xác nhận đã kiểm. | **PAIR — Errors + Graceful Failure** — hạn chế lỗi lan sang cả lớp. | `soan_FAQ`: **tự làm**; `dang_FAQ`: **cần duyệt**, riêng lỗi nguồn do giảng viên duyệt. |

### 5.4. Quyết định hiển thị và các phương án đã loại

| Quyết định | Phương án đã cân nhắc và loại | Vì sao chọn cách hiện tại |
|---|---|---|
| **Hiện điều đã biết/cần xác minh bằng nhãn và bằng chứng** | Điểm tin cậy như “95%”; chỉ ghi chung “AI có thể sai”. | Không có dữ liệu hiệu chuẩn để đưa phần trăm. Ca #1 cho thấy trích đúng vẫn có thể sai; A1/A2 chỉ đúng câu cần xem lại và phép tính kiểm được, giúp học viên quyết định học tiếp hay hỏi người. |
| **Đặt nguồn sát câu trả lời, bấm mở được** | Gom nguồn ở cuối trang; chỉ hiện mã § nhưng không có nội dung. | Học viên đang hỏi một chỗ cụ thể, cần đối chiếu ngay. Tuy nhiên việc mở cả mục nguồn đang có lỗ hổng với bài đang mở, được ghi ở §5.6; dấu “khớp tài liệu” không thay cho việc soát nội dung. |
| **Hai màn hình học viên và TA, cùng một phiên dữ liệu** | Chỉ có chat và một nút “Chuyển người”; dựng hệ thống tài khoản/nhắn tin thật. | Màn hình TA cho thấy người duyệt nhận gì, sửa gì, quyết định gửi/đăng lúc nào. Dữ liệu trong cùng tab đủ demo chuỗi hành động theo yêu cầu 1–2 màn hình, không cần backend. |
| **Gợi ý sâu nằm trong hàng chờ, câu hỏi riêng có bản xem trước** | Gửi mọi thứ ngay rồi cho hoàn tác; chờ TA cho cả gợi ý bước đầu. | Gợi ý đã đọc không thu hồi được; cần chặn trước khi gửi. Chờ duyệt cả bước đầu lại khiến học viên kẹt lúc 23:00. Bản xem trước giúp học viên kiểm nội dung riêng trước khi chuyển. Luồng báo lỗi tự gửi ở C2 cần được đưa về cùng quy tắc xác nhận của §4. |
| **Tách nháp FAQ và đăng FAQ, phân quyền TA/giảng viên trong demo** | AI tự đăng; cấm hoàn toàn FAQ. | #1 sai thì lan ra cả lớp, nên người duyệt phải thấy nháp và cờ nguồn trước khi đăng. Soạn nháp vẫn giữ được tín hiệu tài liệu có vấn đề; cả lớp chưa thấy nháp. Gỡ FAQ giảm lan truyền tiếp nhưng không xoá điều người khác đã đọc. |
| **Giữ Mock để demo ổn định, tách chế độ AI thật và log** | Chỉ dùng AI thật cho mọi lần bấm; gắn nhãn AI thật cho câu viết sẵn. | Mock giúp trình bày nhất quán cả lỗi và đường sửa. Chế độ AI thật có nhãn riêng và log để kiểm bằng chứng; chưa gọi thành công thì chưa kết luận đạt bonus. |

### 5.5. Khi gặp ca lạ

- **Mock có từ khoá nhận diện:** chuyển vào kịch bản tương ứng. Ví dụ câu có “slide” đi nhánh nguồn không tồn tại; câu có “viết hộ/chép” đi nhánh bài đang mở. Đây là phân nhánh bằng từ khoá, không phải hiểu mọi cách diễn đạt hay mọi yêu cầu gộp.
- **Mock không khớp:** hiện “Mình chưa tìm thấy nội dung này…” và cho nói rõ mục đang hỏi hoặc mở nháp gửi TA. Đã thử câu “Em muốn tìm tài liệu về thiết kế đồ hoạ” và thấy nhánh này; không sinh kiến thức ngoài fixture.
- **AI thật:** có thể dùng câu tự do khi đã nhập key; phản hồi được đối chiếu mã mục và soát một số mẫu đáp án. Nếu gọi API lỗi, giao diện hiện lỗi để người demo xử lý; không lấy câu Mock rồi ghi là phản hồi API. Các ca lỗi được dựng sẵn vẫn chạy Mock để minh hoạ đường sửa.
- **Giới hạn:** không khẳng định đã xử lý đúng mọi ca lạ. Ghép từ khoá có thể chọn sai nhánh; bộ soát theo mẫu có thể bỏ sót cách diễn đạt khác hoặc chuỗi gợi ý qua nhiều lượt. Phần này chưa thay thế một bộ đánh giá model.

### 5.6. Kết quả kiểm tra và phần còn thiếu

Đã bấm thử trên Chrome ở chế độ Mock, chỉ dùng dữ liệu dựng; hai ảnh trên chụp từ chính phiên chạy. Các luồng đã kiểm: mở nháp không gửi → xác nhận mới vào hàng chờ → rút lại; gợi ý sâu chờ TA → cảnh báo khi nhập đáp số → duyệt gợi ý hợp lệ mới hiện cho học viên; TA không đăng được FAQ có cờ → giảng viên xác nhận mới đăng → gỡ được; hai nhánh sửa lỗi #1/#8; câu không khớp đi nhánh hỏi thêm/chuyển TA. Không gặp ngoại lệ JavaScript trong các luồng này.

| Đối chiếu guide §5 / rubric R5 | Bằng chứng và kết luận |
|---|---|
| **1–2 màn hình, ca khó bấm qua được** | Có hai màn hình và các luồng trên. Có dữ liệu giả, không đăng nhập, không backend; thao tác duyệt là người demo đóng vai, không có bảo mật phân quyền thật. |
| **Thấy bằng chứng và giới hạn của AI** | A1/A2, B1/B2 và C1 trong ảnh 1; dấu khớp chỉ nói về trích dẫn. |
| **Ít nhất hai mức tự chủ; HAX/PAIR trỏ đúng vị trí** | C3/C4 thể hiện tự làm, cần duyệt, cấm; bảng §5.3 nối ba nguyên tắc đã chọn ở §3 với vị trí cụ thể. |
| **Mức tự chủ khớp §4** | **Chưa đầy đủ:** `addAI()` gọi `startDocReport()` ngay khi có lỗi nguồn, đưa cả mã học viên và câu hỏi vào hàng chờ mà chưa xác nhận. C2/ảnh 2 thể hiện đúng hành vi đó. Theo §3.4 và §4, câu hỏi phải qua bản xem trước; đường tự báo lỗi nguồn nên là nháp FAQ ẩn danh. Có nút rút lại không thay cho bước xác nhận trước khi gửi. |
| **Không làm lộ lời giải qua bằng chứng** | **Còn lỗi:** ca #7 trích một câu an toàn ở §3.2, nhưng `citeHTML()` mở toàn bộ mục nguồn, gồm câu về “thu nhập”. Cần giới hạn nội dung hiển thị theo bài đang mở, không chỉ kiểm đoạn trích ban đầu. Chưa coi luồng #7 là đã chặn hết rủi ro. |
| **Trạng thái thất bại/không chắc khi chuyển TA** | Mới mô phỏng chuyển thành công bằng bộ hẹn giờ; chưa có nhánh gửi thất bại hoặc mất xác nhận như thiết kế §3.4. Chưa có backend để kiểm độ tin cậy chuyển thật. |
| **Bonus AI thật** | Có mã tích hợp và nút xuất log; **chưa có bằng chứng lời gọi thành công**, chưa tính bonus. |

## §6. Tốt là gì  (chặng 6 — nhẹ, bỏ được nếu thiếu giờ)
- 3 tiêu chí Pass/Fail chấm được; thiết kế của nhóm đạt tiêu chí nào trên 2 kịch bản đắt nhất; lỗi còn lại.

## §7. Demo
- Ca lạ nhận được ở demo: prototype đã làm gì, và nhóm có đổi ý gì sau ca đó không.
