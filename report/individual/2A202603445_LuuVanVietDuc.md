# Báo cáo cá nhân — 2A202603445_LuuVanVietDuc

## 1. Thông tin học viên

- Họ tên: Lưu Văn Việt Đức
- MSSV:2A202603445
- Email trường (không bắt buộc, repo có thể để public):
- Tên nhóm: NhomNhomNhom
- Link repo nhóm:https://github.com/bato-bato/K5-L3A-DAY02-NhomNhomNhom-DiscoveryProblemFraming.git

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng) |
|---:|---|---|---|---|
| 1 | Tốn thời gian | Khi bắt đầu bài tập, tôi muốn rõ các bước và thứ tự thực hiện, để lập kế hoạch đúng yêu cầu. | Tôi | Lab 02 tại VinUni ngày 06/11/2026: tôi hiểu chưa rõ hướng dẫn phần cá nhân, làm sai bước và thiếu ý; mất thêm 25–30 phút để làm rõ yêu cầu và lập lại kế hoạch. |
| 2 | Lặp lại | Khi tích hợp code nhóm, tôi muốn thống nhất luồng xử lý, để tránh sửa lệch yêu cầu đã chốt. | Nhóm phát triển | Khi merge phần flashcard, bài tập và HLS video, luồng xử lý xung đột, mỗi người sửa một kiểu. Người phụ trách bài tập kiểm tra lại thấy lệch đề xuất ban đầu. Tôi sửa 2 lần, tổng khoảng 3 giờ theo trí nhớ. |
| 3 | Lặp lại | Khi template đồ án thay đổi, tôi muốn rõ phần cần chuyển và bổ sung, để cập nhật đúng và giảm làm lại. | Nhóm viết tài liệu | Template đổi từ v0.8 → v0.9 → v1.0. Mỗi lần, nhóm mất khoảng 3 ngày để cập nhật theo trí nhớ; đây là thời gian hoàn thiện, không phải ngày công/người. |
| 4 | Cần đọc, tổng hợp nhiều thông tin | Khi xác định yêu cầu chức năng AI, tôi muốn rõ phạm vi nội dung được phép xử lý, để chức năng đáp ứng mục tiêu học tập. | Nhóm đồ án | Khi giảng viên thử yêu cầu là cho dữ liệu về Ngữ văn 8, yêu cầu Toán 9, AI vẫn sinh Ngữ văn 8 thay vì yêu cầu làm rõ. Nhóm chưa thiết lập ràng buộc phạm vi bài học trong prompt. |
| 5 | Cần đọc, tổng hợp nhiều thông tin | Khi nộp bài tại VinUni, tôi muốn kiểm tra đủ các bước, để tránh bỏ sót yêu cầu. | Tôi | Lab Day 01: tôi tưởng push code lên GitHub là hoàn tất nên bỏ sót Google Form; mất thêm 3–5 phút để bổ sung, vẫn kịp hạn. |
| 6 | Cần đọc, tổng hợp nhiều thông tin | Khi làm phần việc phụ thuộc thành viên khác, tôi muốn biết yêu cầu, người phụ trách và thời điểm bàn giao, để sắp xếp công việc và tránh xung đột. | Nhóm phát triển | Tôi thường xuyên tra bảng Excel để kiểm tra yêu cầu và tiến độ; một lần tìm yêu cầu flashcard mất khoảng 3–5 phút. Với notification, phần frontend của tôi cần chờ backend của bạn khác nên phải kiểm tra người phụ trách và thời gian dự kiến hoàn thành. |
| 7 | Lặp lại | Khi sửa chức năng sau review, tôi muốn làm rõ kỳ vọng của giảng viên, để sửa đúng và hạn chế làm lại nhiều lần. | Nhóm đồ án | Chức năng log đăng nhập chưa đúng ý giảng viên, phải sửa 2 lần. Cuối cùng, nhóm bỏ chức năng này và chỉ ghi nhận ai đang làm bài trong tính năng bài kiểm tra. |

**Nếu có dùng AI để gợi ý thêm:** ý nào AI gợi ý mà bạn giữ lại, ý nào bỏ và vì sao.
**AI hỗ trợ scan và đề xuất **
- Tôi đưa ra 7 vấn đề ban đầu từ trải nghiệm làm bài, học tập và đồ án nhóm.AI gợi ý bổ sung thêm các thông tin chi tiết của các vấn đề , rút gọn lại vấn đề tập trung vào trọng tâm và đặt hoài nghi cho vấn đề 7 vì chưa nói rõ ràng.
- Tôi phản biện ý #7 vì nhóm có ghi hình tất cả các buổi review, chưa gặp tình trạng bỏ sót góp ý hoặc sửa trùng. 
- Từ danh sách đang xem xét, AI đề xuất #2, #4 và #5 để phát triển thành Problem Card vì có phạm vi tương đối rõ và có thể bổ sung bằng chứng.

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | AI vẫn sinh tài liệu khi dữ liệu và yêu cầu không khớp — CP1 #4 | Có tình huống lỗi cụ thể khi review; nhóm chưa sửa thành công; có thể kiểm thử bằng các cặp dữ liệu–yêu cầu. | Cách xác định mức độ khớp và xử lý dữ liệu thiếu hoặc liên quan một phần. |
| 2 | Tốn thời gian xử lý xung đột code khi tích hợp — CP1 #2 | Đã sửa 2 lần, tổng khoảng 3 giờ; ảnh hưởng nhiều thành viên. | Bao nhiêu thời gian có thể giảm nhờ thống nhất yêu cầu, bao nhiêu thuộc việc sửa code kỹ thuật? |
| 3 | Bỏ sót bước xác nhận nộp bài — CP1 #5 | Có trải nghiệm thật, phạm vi nhỏ, dễ thử bằng checklist. | Mới ghi nhận một lần; checklist thủ công có thể đã đủ, chưa chắc cần AI. |

### Problem Card #1 — Dữ liệu và yêu cầu sinh tài liệu không khớp

| Trường | Nội dung |
|---|---|
| Job Story | Khi sinh tài liệu học tập từ dữ liệu đầu vào, tôi muốn biết dữ liệu có phù hợp với yêu cầu hay không, để tránh tạo nội dung sai và phải làm lại. |
| Actor | Người soạn nội dung bài học trong hệ thống. |
| Thời điểm / bối cảnh | Khi thêm hoặc sửa bài học và sử dụng AI để sinh tài liệu từ dữ liệu được cung cấp. |
| Quy trình hiện tại (3–7 bước) | 1. Mở Add/Edit nội dung bài học; 2. Nhập dữ liệu dạng text hoặc tải Word, Excel, PDF; 3. Nhập yêu cầu sinh tài liệu; 4. Gửi cho AI xử lý; 5. Xem kết quả dạng text dưới phần input; 6. Kiểm tra nội dung có đáp ứng yêu cầu không. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 4–6: chưa phát hiện sự không khớp trước khi sinh. Khi đưa dữ liệu Ngữ văn 8 và yêu cầu Toán 9, AI vẫn sinh nội dung Ngữ văn 8. Chưa đo thời gian xử lý lại; nhóm chưa sửa thành công. |
| Impact (nếu không giải thì sao) | Người soạn phải tự phát hiện sai lệch, sửa yêu cầu và thử lại; có nguy cơ đưa nội dung không phù hợp vào bài học nếu kiểm tra không kỹ. |
| Success metric (baseline → target) | **Baseline:** ca Ngữ văn 8 → yêu cầu Toán 9 vẫn sinh nội dung, không yêu cầu làm rõ. **Target đề xuất:** trên 20 ca thử gồm 10 ca khớp và 10 ca không khớp, xử lý đúng ít nhất 9/10 ca ở mỗi nhóm. Ca không khớp phải dừng sinh và yêu cầu làm rõ; ca khớp được tiếp tục sinh. |
| Phương án không dùng AI | Gắn nhãn môn, lớp cho dữ liệu; yêu cầu chọn môn, lớp đầu ra; dùng quy tắc chặn khi nhãn không khớp và để người soạn kiểm tra nội dung. |
| Giả thuyết về AI (nếu có) | AI có thể đối chiếu nội dung nguồn với yêu cầu và chỉ ra điểm không khớp. Nếu thiếu thông tin hoặc không chắc, hệ thống yêu cầu người dùng làm rõ trước khi sinh. Cần kiểm thử thay vì chỉ dựa vào việc sửa prompt. |
| Cảm nhận nhanh | **Workflow** — kiểm tra đầu vào → xác nhận mức độ phù hợp → sinh nội dung hoặc yêu cầu làm rõ. |

**Quy trình nháp hiện tại:**

1. Mở Add/Edit bài học.
2. Nhập dữ liệu nguồn và yêu cầu sinh tài liệu.
3. Gửi AI xử lý.
4. AI trả nội dung dạng text, kể cả khi dữ liệu và yêu cầu không khớp.
5. Người soạn kiểm tra và phát hiện sai lệch.

### Problem Card #2 — Tốn thời gian xử lý xung đột khi tích hợp code

| Trường | Nội dung |
|---|---|
| Job Story | Khi tích hợp code nhóm, tôi muốn thống nhất cách giữ và kết nối các phần chức năng, để giảm xung đột và sửa lại nhiều lần. |
| Actor | Tôi, các thành viên có code xung đột và trưởng nhóm. |
| Thời điểm / bối cảnh | Khi tích hợp các phần flashcard, bài tập và HLS video vào đồ án nhóm. |
| Quy trình hiện tại (3–7 bước) | 1. Xem yêu cầu trong Excel; 2. Mỗi người code phần mình; 3. Merge và chạy thử; 4. Tìm nguyên nhân xung đột; 5. Hỏi trưởng nhóm và thành viên liên quan, thống nhất cách xử lý; 6. Tách phần code xung đột để giữ cả hai chức năng rồi merge lại; 7. Kiểm thử. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 4–5: tìm lỗi khoảng 20–30 phút, trao đổi khoảng 30 phút, chốt yêu cầu khoảng 5 phút; tổng 55–65 phút/lần. Code lại khoảng 20 phút và kiểm thử khoảng 10 phút. Tổng khoảng 85–95 phút/lần, phù hợp với ước lượng 2 lần mất khoảng 3 giờ. |
| Impact (nếu không giải thì sao) | Các thành viên phải sửa và kiểm thử lại; việc tích hợp bị chậm, có nguy cơ sửa lệch yêu cầu hoặc ảnh hưởng chức năng của nhau. |
| Success metric (baseline → target) | **Baseline:** khoảng 85–95 phút cho một lần xử lý như đã gặp. **Target đề xuất:** giảm còn tối đa 60 phút với ca tương đương, đồng thời cả hai chức năng vẫn vượt qua các bước kiểm thử đã thống nhất. |
| Phương án không dùng AI | Thống nhất luồng xử lý và ranh giới phần việc trước khi code; ghi quyết định vào bảng chung; review thay đổi và dùng checklist kiểm thử trước khi merge. |
| Giả thuyết về AI (nếu có) | AI có thể hỗ trợ đọc phần code xung đột, tóm tắt khác biệt và gợi ý câu hỏi cần thống nhất. Thành viên phụ trách xác nhận yêu cầu và quyết định cách sửa. |
| Cảm nhận nhanh | **Workflow** — ưu tiên cải thiện phối hợp và kiểm tra trước merge; AI chỉ hỗ trợ phân tích. |

**Quy trình nháp hiện tại:**

1. Đọc yêu cầu trong Excel và code riêng.
2. Merge code, chạy thử và phát hiện xung đột.
3. Tìm lỗi: 20–30 phút.
4. Trao đổi với trưởng nhóm và người liên quan: khoảng 30 phút.
5. Chốt cách xử lý: khoảng 5 phút.
6. Tách, sửa code để giữ hai chức năng và merge lại: khoảng 20 phút.
7. Kiểm thử: khoảng 10 phút.

### Problem Card #3 — Bỏ sót bước xác nhận nộp bài

| Trường | Nội dung |
|---|---|
| Job Story | Khi nộp bài tại VinUni, tôi muốn kiểm tra đủ các bước bắt buộc, để hoàn thành đúng quy định và đúng hạn. |
| Actor | Tôi khi thực hiện bài lab tại VinUni. |
| Thời điểm / bối cảnh | Khi hoàn thành Lab Day 01; hướng dẫn điền Google Form nằm cuối tài liệu PDF trên LMS nhưng tôi chưa đọc hết. |
| Quy trình hiện tại (3–7 bước) | 1. Đọc hướng dẫn trên LMS nhưng chưa hết; 2. Fork repository; 3. Làm bài; 4. Push code và tưởng đã hoàn tất; 5. Nghe lab coach nhắc khi một bạn hỏi; 6. Mở Google Form, điền thông tin và link GitHub đã fork rồi gửi. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 1 và 4: chưa đọc đủ hướng dẫn nên xác định sai thời điểm hoàn tất. Sau khi phát hiện, mất thêm khoảng 3–5 phút để điền form; vẫn kịp hạn. |
| Impact (nếu không giải thì sao) | Có nguy cơ hoàn thành code nhưng chưa hoàn tất thủ tục nộp bài, hoặc phát hiện thiếu bước khi đã hết hạn. |
| Success metric (baseline → target) | **Baseline:** bỏ sót 1 bước bắt buộc trong lần nộp Lab Day 01. **Target đề xuất:** không bỏ sót bước bắt buộc trong 3 lần nộp tiếp theo, đối chiếu checklist với hướng dẫn gốc. |
| Phương án không dùng AI | Đọc hết hướng dẫn, tự lập checklist và đánh dấu từng bước; kiểm tra lại trước hạn nộp. |
| Giả thuyết về AI (nếu có) | AI có thể trích các bước bắt buộc từ tài liệu thành checklist, kèm vị trí nguồn để người học kiểm tra. Lợi ích cần được so sánh với checklist tự lập. |
| Cảm nhận nhanh | **No AI** — thử checklist thủ công trước; chỉ cân nhắc AI nếu hướng dẫn dài hoặc phân tán. |

**Quy trình nháp hiện tại:**

1. Đọc chưa hết PDF hướng dẫn trên LMS.
2. Fork repository và làm bài.
3. Push code, tưởng đã nộp xong.
4. Một bạn hỏi, lab coach nhắc về Google Form.
5. Mở form, điền thông tin và link GitHub.
6. Gửi form sát thời hạn.

### Card muốn pitch nhất

- **Card số:** 1 — Dữ liệu và yêu cầu sinh tài liệu không khớp.
- **Vì sao:** Có lỗi cụ thể đã quan sát khi review và nhóm chưa sửa thành công. Phạm vi thử nghiệm rõ: phát hiện sự không khớp trước khi cho phép sinh tài liệu.
- **Câu hỏi muốn nhóm phản biện:** Chọn môn/lớp và kiểm tra bằng quy tắc đã đủ chưa, hay cần AI đọc nội dung nguồn? Với dữ liệu chỉ liên quan một phần, khi nào nên yêu cầu người dùng làm rõ?

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| Mô tả ban đầu của vấn đề AI chưa đúng trọng tâm lỗi thực tế. | Đồng ý | Chuyển từ “sinh nội dung ngoài bài học” sang “chưa kiểm tra sự khớp giữa dữ liệu và yêu cầu”. |
| Chưa có số liệu đo hiệu quả hoặc thời gian xử lý cho Card #1. | Đồng ý | Ghi rõ chưa đo; tách ca lỗi đã quan sát khỏi target thử nghiệm đề xuất. |
| Card #2 có thể cần cải thiện phối hợp trước khi dùng AI. | Đồng ý | Bổ sung phương án thống nhất yêu cầu, review và checklist; giới hạn AI ở vai trò hỗ trợ phân tích. |
| Card #3 chưa chứng minh cần AI và mới có một lần bỏ sót. | Đồng ý | Chọn No AI cho hướng thử ban đầu và đề xuất theo dõi 3 lần nộp tiếp theo. |

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card | Chuẩn bị 3 Problem Cards cá nhân về kiểm tra dữ liệu–yêu cầu sinh tài liệu, xung đột khi tích hợp code và bỏ sót bước nộp bài. | Có các candidate cá nhân để đưa ra thảo luận; phần trình bày trực tiếp chưa ghi nhận chi tiết. |
| Phản biện bài của bạn khác | Chưa ghi nhận câu hỏi phản biện trực tiếp cụ thể. | Chưa có kết quả để ghi nhận. |
| Nhận phản biện | Đối chiếu lại cách hiểu actor: ban đầu tôi nghĩ là người ngoài xem giải, sau đó xác định theo Card của Bảo là tuyển thủ. | Điều chỉnh phạm vi CP4 về lịch thi đấu, thể lệ, địa điểm và check-in. |
| Gom cluster / cây OST | Không trực tiếp phụ trách tổng hợp cluster và cây OST. | Tham khảo kết quả hội tụ chung để thực hiện CP4. |
| Chọn candidate problem | Thực hiện CP4 theo Card #1 của Bảo được nhóm chọn. | Giữ nội dung research thống nhất với đề tài thông tin giải đấu XayGame. |
| Kiểm chứng / research | Tổng hợp Assumption Map, rà soát nguồn công khai về XayGame và tham khảo Notion Sites, Discord Forum, start.gg. Chuẩn bị khung kiểm chứng; chưa có phỏng vấn thực tế được xác nhận. | Bổ sung mục 3 của báo cáo nhóm; phân biệt thông tin có nguồn với các tình huống minh họa cần kiểm chứng. |
| Quy trình nhóm | Cung cấp các bước và giả định cần kiểm tra trong CP4: tìm thông báo, đối chiếu cập nhật và hỏi BTC. | Làm đầu vào tham khảo cho thành viên phụ trách CP5; chưa xác nhận được bottleneck bằng số đo. |
| Problem Statement | Không trực tiếp phụ trách viết Problem Statement của nhóm. | Qua CP4, ghi rõ các giới hạn bằng chứng để tránh kết luận vượt quá dữ liệu hiện có. |
| Mức can thiệp AI | Research các phương án tổ chức và tra cứu thông tin có sẵn, gồm cả phương án không dùng AI. | Cung cấp cơ sở tham khảo khi nhóm so sánh No AI, Rule và Workflow. |
| Quyết định | Không trực tiếp phụ trách chốt quyết định cuối. | Cung cấp kết quả research và những điểm chưa chắc để nhóm cân nhắc. |

---

## 5. Dùng AI

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan | Hỗ trợ diễn đạt và rút gọn các vấn đề từ trải nghiệm tôi cung cấp. | Giúp làm rõ Job Story và chỉ ra thông tin còn thiếu. | Có giả định chưa đúng về việc bỏ sót góp ý hoặc sửa trùng sau review. | Tôi giải thích nhóm có ghi hình review và bổ sung tình huống thực tế, số lần sửa, thời gian ước lượng. |
| CP2 Problem Card | Hỗ trợ sắp xếp nội dung theo mẫu và phản biện các card. | Giúp phân biệt actor, bottleneck, impact và mục tiêu thử nghiệm. | Ban đầu mô tả lỗi sinh tài liệu chưa đúng trọng tâm. | Tôi làm rõ tình huống dữ liệu Ngữ văn 8 nhưng yêu cầu Toán 9; vấn đề là chưa kiểm tra sự khớp giữa dữ liệu và yêu cầu. |
| CP4 Research | Hỗ trợ tìm nguồn, tổng hợp giải pháp có sẵn và xây dựng khung kiểm chứng. | Gợi ý các hướng tham khảo từ Notion Sites, Discord Forum, start.gg và nguồn VNGGames về XayGame. | Nguồn công khai chỉ xác nhận bối cảnh, chưa chứng minh khó khăn của tuyển thủ; các tình huống phỏng vấn AI tạo chỉ là minh họa. | Tôi đối chiếu actor với Card của nhóm, giới hạn kết luận theo bằng chứng và giữ rõ trạng thái dữ liệu chưa xác minh. |
| CP5 Quy trình | Không trực tiếp dùng AI cho phần này trong phạm vi công việc cá nhân. | — | — | Phần quy trình do thành viên được phân công phụ trách. |
| CP5–6 Problem Statement | Không trực tiếp dùng AI để thực hiện phần này. | — | — | Tôi phụ trách CP4 và tham khảo kết quả chung để hiểu bài nhóm. |
| CP6 Mức can thiệp / quyết định | Không trực tiếp dùng AI để chốt quyết định của nhóm. | — | — | Mức can thiệp và quyết định cuối cần đối chiếu với bản nhóm đã thống nhất. |
| CP7 Reflection | Hỗ trợ gợi ý câu hỏi, biên tập và định dạng từ các ý tôi cung cấp. | Giúp rà soát nội dung còn thiếu và cách trình bày. | AI không biết đầy đủ trải nghiệm tham gia nhóm của tôi. | Tôi cung cấp điều đã học, khó khăn khi xác định bottleneck và cách muốn cải thiện nếu làm lại. |

---

## 6. Reflection (CP7)

### 6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?

Qua việc tìm hiểu đề tài của nhóm, tôi học được cách tổ chức và phân tích một vấn đề trước khi lựa chọn cách ứng dụng AI. Với đề tài XayGame, tôi hiểu rằng cần xác định rõ người sử dụng, thông tin họ cần và nguồn dữ liệu được phép sử dụng. Tôi cũng nhận ra việc đặt giới hạn cho AI rất quan trọng: AI chỉ nên hỗ trợ trong phạm vi dữ liệu giải đấu do BTC cung cấp, thay vì tự đưa ra câu trả lời khi thiếu thông tin.

### 6.2. Nhóm có lúc nào bị “solution-first” không? Lúc đó nhóm nhận ra và xử lý thế nào?

Trong quá trình tham gia, tôi chưa ghi nhận một tình huống cụ thể mà nhóm phải thay đổi hướng vì nghĩ giải pháp trước khi hiểu vấn đề. Tuy nhiên, khi tìm hiểu các phương án cho CP4, tôi nhận thấy cần kiểm tra sự cần thiết của AI. Việc có thể xây dựng một chức năng AI chưa đủ để kết luận đó là lựa chọn phù hợp với nhu cầu của tuyển thủ.

### 6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.
Ban đầu, tôi nghĩ đối tượng sử dụng là người ngoài muốn xem thông tin giải đấu. Sau khi đối chiếu lại tôi thấy actor mới chính là tuyển thủ tham gia giải. Sự điều chỉnh này giúp tôi hiểu rằng việc xác định actor ảnh hưởng đến cả nội dung cần kiểm chứng: tuyển thủ cần thể lệ, đăng ký và check-in, còn khán giả thường quan tâm lịch trận, kết quả và cách xem.

### 6.4. Kết quả kiểm chứng hoặc research có làm tôi bất ngờ không? Điều gì?

Điều làm tôi bất ngờ là đã có các công cụ hỗ trợ những phần việc tương tự, như tập trung thông tin, tổ chức câu hỏi theo chủ đề và quản lý dữ liệu giải đấu. Tôi nhận ra trước khi xây dựng sản phẩm mới, có thể tìm hiểu các giải pháp trên thị trường để học cách họ xử lý vấn đề. Tuy nhiên, việc công cụ đã tồn tại chưa có nghĩa là phù hợp ngay với XayGame; nhóm vẫn cần kiểm tra khả năng áp dụng trong bối cảnh của mình.

### 6.5. Điều khó nhất khi viết Problem Statement là gì?

Với tôi, khó nhất là xác định bottleneck. Tôi chưa trực tiếp trải nghiệm quy trình tìm thông tin của tuyển thủ nên chưa chắc bước nào thực sự gây khó khăn nhất. Việc tìm thông báo, đối chiếu thông tin và chờ BTC phản hồi đều có thể là điểm nghẽn, nhưng tôi chưa có đủ bằng chứng để lựa chọn. Qua đó, tôi hiểu rằng cần phân biệt bước nghẽn giả định với bước nghẽn đã được kiểm chứng, đồng thời tránh đưa số liệu chưa xác nhận vào Problem Statement.

### 6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?

Nếu làm lại, tôi sẽ lên kế hoạch cụ thể theo từng bước, xác định đầu ra và thông tin cần thu thập trước khi thực hiện. Sau khi làm rõ quy trình, tôi sẽ xem bước nào có thể cần AI và tìm hiểu các giải pháp có sẵn. Cách này có thể tiết kiệm thời gian, chi phí hơn việc tự xây dựng ngay từ đầu. Tôi sẽ cân nhắc tích hợp công cụ phù hợp và chỉ tự xây phần còn thiếu. Tôi cũng sẽ đặt câu hỏi rõ hơn về bằng chứng của bottleneck và lý do lựa chọn AI thay vì phương án đơn giản hơn.

### 6.7. Hiểu bài

Người dùng chính của đề tài là các tuyển thủ tham gia giải đấu do XayGame tổ chức. Vấn đề nhóm đang xem xét là tuyển thủ đôi khi gặp khó khăn khi tiếp nhận và xác nhận thông tin từ BTC qua fanpage hoặc các kênh thông báo. Quy trình hiện tại gồm đọc thông báo, tìm cập nhật, đối chiếu và hỏi BTC khi chưa rõ. Bottleneck và các chỉ số đo vẫn cần được xác minh thêm. Nếu sử dụng AI, hệ thống chỉ được trả lời trong phạm vi dữ liệu giải đấu do BTC cung cấp và chuyển câu hỏi thiếu căn cứ cho người phụ trách. Hướng can thiệp có thể cân nhắc là Workflow, trong đó AI hỗ trợ tra cứu theo các bước xác định sẵn, còn BTC kiểm soát nguồn và các quyết định quan trọng. 
## 7. Tài liệu tham khảo

1. VNGGames. (2025, 18 tháng 9). *[ĐTCL - VĐQG] Tổng hợp giải đấu Vô địch Quốc gia từ ngày 18/09–28/09/2025*.  
   https://community.vnggames.com/news/tft/dtcl-vdqg-tong-hop-giai-dau-vo-dich-quoc-gia-t-ngay-18-09-28-09-2025.html

2. Notion. (Không ghi năm). *Publish a Notion Site*.  
   https://www.notion.com/help/public-pages-and-web-publishing

3. Discord. (Không ghi năm). *Forum Channels FAQ*.  
   https://support.discord.com/hc/en-us/articles/6208479917079-Forum-Channels-FAQ

4. start.gg. (Không ghi năm). *Get Event — Developer Portal*.  
   https://developer.start.gg/docs/examples/queries/get-event/