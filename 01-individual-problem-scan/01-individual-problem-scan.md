# Idea 4: AI hỗ trợ soạn email bán hàng, nhưng con người duyệt trước khi gửi

## Bối cảnh

Bạn là nhân viên bán hàng. Bạn có danh sách khách hàng và thường cần gửi email khi có sản phẩm mới, chương trình khuyến mãi mới, hoặc thông tin cần cập nhật cho khách. Ngoài ra, khách hàng có thể trả lời email để hỏi thêm về giá, tính năng, tồn kho, điều kiện ưu đãi, hoặc cách mua hàng.

Ràng buộc quan trọng: AI agent không được tự động gửi email. AI chỉ được phép tạo nháp email hoặc gợi ý câu trả lời. Nhân viên bán hàng phải kiểm tra, chỉnh sửa nếu cần, rồi tự quyết định gửi.

## Scan rộng

| # | Lăng kính | Problem quan sát được | Ai đang đau? | Dấu hiệu thật | Khả năng AI nên có |
|---|---|---|---|---|---|
| 1 | Tốn thời gian | Nhân viên bán hàng mất nhiều thời gian viết email giới thiệu sản phẩm mới cho từng khách hoặc từng nhóm khách | Sales | Phải copy-paste, sửa tên, sửa nội dung thủ công cho nhiều email | Tạo nháp email cá nhân hóa |
| 2 | Tốn thời gian | Mỗi chương trình khuyến mãi mới cần nhiều phiên bản email khác nhau | Sales, Marketing | Cùng một chương trình nhưng phải viết riêng cho khách cũ, khách mới, khách VIP, khách chưa mua | Tạo nhiều biến thể email theo phân khúc |
| 3 | Chất lượng thấp | Email gửi đi quá chung chung, không phù hợp nhu cầu từng khách | Sales, khách hàng | Tỷ lệ mở mail, phản hồi, hoặc click thấp | Cá nhân hóa nội dung dựa trên thông tin khách |
| 4 | Dễ sai sót | Sales có thể gửi nhầm thông tin sản phẩm, sai giá, sai thời gian áp dụng ưu đãi | Sales, Sales manager, khách hàng | Khách hỏi lại vì thông tin không rõ hoặc không khớp với chương trình | Kiểm tra nội dung theo nguồn thông tin chuẩn |
| 5 | Lặp lại | Khách hàng hỏi đi hỏi lại các câu giống nhau về giá, tồn kho, tính năng, bảo hành, điều kiện ưu đãi | Sales | Inbox có nhiều câu hỏi lặp, sales phải trả lời thủ công | Sinh nháp câu trả lời từ FAQ và thông tin sản phẩm |
| 6 | Chậm phản hồi | Sales không trả lời kịp các email khách hàng quan tâm | Sales, khách hàng | Khách nóng bị bỏ lỡ, phản hồi đến muộn làm giảm khả năng chốt đơn | Tóm tắt email đến và gợi ý phản hồi nhanh |
| 7 | Khó ưu tiên | Sales không biết email nào cần xử lý trước | Sales | Email hỏi mua thật bị lẫn với email hỏi chung chung hoặc email ít tiềm năng | Phân loại mức độ ưu tiên của email |
| 8 | Thiếu nhất quán | Mỗi sales trả lời theo một cách khác nhau, làm thông tin và tone thương hiệu không đồng đều | Sales manager | Có email quá dài, quá ngắn, thiếu CTA, hoặc dùng sai giọng thương hiệu | Chuẩn hóa tone và cấu trúc email |
| 9 | Dễ quên follow-up | Sau khi gửi email chiến dịch, sales dễ quên theo dõi khách chưa phản hồi | Sales | Khách từng quan tâm nhưng không được nhắc lại đúng lúc | Gợi ý nháp email follow-up |
| 10 | Khó chọn đúng nội dung | Sales có danh sách khách nhưng không biết nên gửi sản phẩm/chương trình nào cho ai | Sales | Một email gửi cho toàn bộ danh sách, nhiều khách không thấy liên quan | Gợi ý phân nhóm khách và thông điệp phù hợp |

## Top 3 problem đáng chọn

### 1. Soạn nháp email cá nhân hóa cho sản phẩm mới hoặc chương trình mới

Đây là vấn đề rõ nhất trong bối cảnh bán hàng. Sales thường cần gửi email cho nhiều khách, nhưng nếu viết thủ công thì mất thời gian, còn nếu gửi một email chung thì thiếu cá nhân hóa.

Điều chưa chắc: danh sách khách hàng có đủ dữ liệu để cá nhân hóa hay không, ví dụ tên, công ty, lịch sử mua hàng, sản phẩm từng quan tâm, phân khúc, hoặc lần tương tác gần nhất.

### 2. Gợi ý câu trả lời cho email khách hàng

Khách hàng thường trả lời email để hỏi thêm thông tin. Nếu sales phải tự đọc và tự trả lời mọi email, thời gian phản hồi sẽ chậm. AI có thể giúp đọc email đến, hiểu câu hỏi, và tạo nháp trả lời.

Điều chưa chắc: AI có được truy cập nguồn thông tin đáng tin cậy như bảng giá, tồn kho, FAQ, chính sách bảo hành, và điều kiện khuyến mãi hay không.

### 3. Phân nhóm khách hàng và gợi ý nội dung phù hợp

Nếu gửi cùng một nội dung cho toàn bộ khách hàng, email dễ bị bỏ qua. Phân nhóm khách giúp nội dung liên quan hơn, ví dụ khách cũ nhận ưu đãi quay lại, khách tiềm năng nhận email giới thiệu, khách VIP nhận thông tin sớm.

Điều chưa chắc: dữ liệu khách hàng có sạch và có đủ thuộc tính để phân nhóm chính xác hay không.

## Problem Card #1: Soạn nháp email cá nhân hóa cho chiến dịch bán hàng

### Actor

Nhân viên bán hàng có danh sách khách hàng và cần gửi email về sản phẩm mới hoặc chương trình khuyến mãi mới.

### Current workflow

Sales nhận thông tin sản phẩm hoặc chương trình mới. Sau đó sales mở danh sách khách hàng, viết một email mẫu, copy-paste cho nhiều người, chỉnh tên khách, chỉnh một vài câu cá nhân hóa, kiểm tra lại thông tin, rồi gửi email thủ công.

### Bottleneck

Việc viết và chỉnh email cho nhiều khách rất tốn thời gian. Nếu sales gửi hàng loạt thì nội dung bị chung chung. Nếu sales cá nhân hóa từng email thì mất nhiều công và dễ sai sót.

### Impact

Sales gửi email chậm hơn, ít cá nhân hóa hơn, và tỷ lệ phản hồi có thể thấp hơn. Ngoài ra còn có rủi ro gửi nhầm thông tin về sản phẩm, giá, thời gian áp dụng, hoặc điều kiện ưu đãi.

### Success metric

- Thời gian chuẩn bị email cho một chiến dịch giảm 50-70%.
- Tỷ lệ mở mail, click, hoặc phản hồi tăng.
- Số lỗi nội dung trước khi gửi giảm.
- 100% email vẫn được sales kiểm tra và duyệt trước khi gửi.

### Non-AI alternative

Sales có thể dùng email template cố định, mail merge, CRM campaign tool, hoặc checklist thủ công để giảm lỗi. Tuy nhiên các cách này thường cá nhân hóa kém hoặc vẫn cần nhiều thao tác thủ công.

### AI hypothesis

AI có thể tạo nháp email dựa trên thông tin sản phẩm, chương trình khuyến mãi, phân khúc khách hàng, và lịch sử tương tác. AI cũng có thể đề xuất subject line, CTA, và tone phù hợp. Nhân viên sales kiểm tra nháp, chỉnh sửa nếu cần, rồi tự bấm gửi.

### Quick gut

Workflow. Đây không nên là một agent tự động gửi email, vì hành động gửi email có rủi ro cao và cần con người duyệt. AI phù hợp nhất ở vai trò hỗ trợ soạn nháp, cá nhân hóa, kiểm tra nội dung, và đề xuất bước tiếp theo.

## Problem Card #2: Gợi ý trả lời email khách hàng

### Problem

Khách hàng trả lời email để hỏi về giá, ưu đãi, tính năng, thời gian áp dụng, cách mua, hoặc so sánh lựa chọn. Sales phải đọc và trả lời từng email, dễ chậm hoặc trả lời thiếu nhất quán.

### AI role

AI đọc email đến, xác định câu hỏi chính của khách, tóm tắt nhu cầu, tra thông tin liên quan từ nguồn dữ liệu đã được cung cấp, và tạo nháp câu trả lời.

### Human role

Sales kiểm tra nội dung, xác nhận thông tin nhạy cảm như giá hoặc điều kiện ưu đãi, chỉnh lại tone nếu cần, rồi tự gửi email.

### Quick gut

Agent-assisted workflow. AI có thể làm nhiều bước như đọc email, hiểu ý định, tra thông tin, và soạn nháp, nhưng không được tự gửi câu trả lời.

## Problem Card #3: Phân nhóm khách hàng và gợi ý nội dung phù hợp

### Problem

Sales có danh sách khách hàng nhưng không biết nên gửi nội dung nào cho ai. Một email chung cho tất cả khách hàng thường không đủ liên quan, làm khách dễ bỏ qua hoặc hủy nhận email.

### AI role

AI phân nhóm khách dựa trên dữ liệu có sẵn, ví dụ khách cũ, khách mới, khách VIP, khách lâu chưa mua, khách quan tâm sản phẩm A, hoặc khách từng phản hồi chiến dịch trước. Sau đó AI gợi ý nội dung email phù hợp cho từng nhóm.

### Human role

Sales kiểm tra nhóm khách, loại bỏ những khách không phù hợp, duyệt nội dung email, rồi quyết định gửi.

### Quick gut

Workflow. AI hỗ trợ phân tích và đề xuất, nhưng sales vẫn là người kiểm soát chiến dịch và chịu trách nhiệm với email gửi ra.
