# 03 — Individual Reflection

## Problem nhóm chọn

Nhóm chọn problem: AI hỗ trợ nhân viên sales soạn nháp email bán hàng và gợi ý câu trả lời cho email khách hàng, nhưng mọi email phải được con người kiểm tra và duyệt trước khi gửi.

Điểm quan trọng của problem này là AI không được tự động gửi email. AI chỉ hỗ trợ ở các bước như biến thông tin sản phẩm/chương trình thành email nháp, cá nhân hóa nội dung theo nhóm khách hàng, hoặc tạo câu trả lời nháp khi khách hỏi lại. Nhân viên sales vẫn là người review, chỉnh sửa và quyết định gửi.

## Đóng góp của tôi trong nhóm

| Hoạt động | Tôi đã làm gì? | Kết quả |
|---|---|---|
| Đề xuất case | Tôi đưa ra ý tưởng về một công cụ hỗ trợ nhân viên sales gửi email cho khách hàng khi có sản phẩm mới hoặc chương trình mới | Ý tưởng được nhóm chấp nhận để đưa vào thảo luận |
| Làm rõ problem | Ban đầu case của tôi còn mơ hồ: "tôi là nhân viên sale đang muốn làm một cái tool tự động gửi mail". Sau đó tôi dùng GPT để cải tiến case thành một problem cụ thể hơn | Problem rõ hơn về actor, workflow, bottleneck và boundary |
| Scan problem | Tôi dùng GPT để liệt kê nhiều problem liên quan đến gửi email bán hàng, sau đó tự review lại các problem được sinh ra | Nhóm có thêm nhiều candidate để so sánh |
| Chọn top 3 | Tôi chọn 3 problem tiềm năng, sau đó nhờ AI đánh giá và hỗ trợ chọn lại | Một problem của tôi được chọn vào top 3 problem để xử lý |
| Đề xuất workflow | Tôi đề xuất và chỉnh sửa workflow với sự trợ giúp của GPT | Workflow rõ hơn: AI tạo nháp, người dùng review, người dùng tự gửi |
| Đặt boundary | Tôi nhấn mạnh rằng agent không thể tự gửi email, chỉ được sinh nháp hoặc câu trả lời để người dùng kiểm tra | Scope an toàn hơn và thực tế hơn, tránh biến bài toán thành agent tự động quá rủi ro |

## Bảng dùng AI trong reflection

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai/hời hợt ở đâu? | Tôi sửa gì? |
|---|---|---|---|---|
| Cải tiến case | Tôi đưa case mơ hồ cho AI và nhờ AI làm rõ thành problem cụ thể | AI giúp biến một ý tưởng chung thành case có actor, bối cảnh, workflow và pain point | Case đầu tiên AI sinh ra chưa hoàn toàn phù hợp với ý định của tôi | Tôi chỉnh lại để nhấn mạnh vai trò nhân viên sales và ràng buộc human review |
| Scan problem | Tôi dùng AI để liệt kê nhiều problem xoay quanh email sales | AI giúp mở rộng góc nhìn nhanh hơn, không chỉ nghĩ đến "gửi email" mà còn có trả lời email, cá nhân hóa, phân nhóm khách hàng | Một số problem còn khá chung hoặc hơi xa với case ban đầu | Tôi review lại và giữ các problem gần nhất với workflow sales |
| Chọn top 3 | Tôi tự chọn 3 problem, rồi nhờ AI đánh giá lại | AI giúp so sánh problem nào rõ workflow hơn và phù hợp để làm trong lab hơn | AI vẫn có xu hướng chọn hướng rộng nếu prompt chưa đủ chặt | Tôi tự quyết định lại dựa trên bối cảnh thật của nhóm |
| Workflow | Tôi nhờ GPT hỗ trợ đề xuất và chỉnh sửa workflow | AI giúp tách rõ các bước: nhập thông tin sản phẩm, chọn khách hàng, tạo nháp, review, rồi người dùng gửi | AI ban đầu có thể làm workflow giống automation quá mạnh | Tôi chỉnh lại boundary: AI không tự gửi email |
| Review | Tôi mở một khung chat mới để nhờ AI đánh giá lại nội dung và sau đó tự review | Cách này giúp tôi có thêm góc nhìn phản biện | AI không thể thay tôi quyết định nội dung nào thật sự phù hợp với nhóm | Tôi đọc lại, chọn lọc và chỉnh sửa theo ý hiểu của mình |

## Bài học của tôi

- Prompt càng tốt thì kết quả đầu ra càng tốt. Khi tôi chỉ đưa một câu mơ hồ, AI vẫn có thể trả lời, nhưng kết quả thường chung chung và phải sửa nhiều.
- AI thật sự giúp tăng hiệu quả rất nhiều, đặc biệt ở bước biến một ý tưởng mơ hồ thành một problem có cấu trúc.
- Tuy nhiên, AI không thay thế được phần review của con người. Với case email bán hàng, nếu AI tự gửi hoặc viết sai thông tin thì có thể ảnh hưởng trực tiếp đến khách hàng.
- Tôi học được rằng không nên bắt đầu bằng câu "làm một tool AI", mà nên bắt đầu từ actor, workflow, bottleneck, impact và boundary.
- Trong case này, hướng hợp lý hơn là Workflow, không phải full Agent. AI nên hỗ trợ tạo nháp và đề xuất, còn quyết định cuối vẫn thuộc về người dùng.

## Nếu làm lại

Nếu làm lại, tôi sẽ prompt cẩn thận hơn ngay từ đầu. Trước khi prompt, tôi sẽ lên kế hoạch sẵn dạng mục lục gồm actor, bối cảnh, input, output, workflow hiện tại, pain point, boundary, success metric và điều AI không được làm.

Tôi thấy việc chỉnh sửa prompt nhiều lần không hiệu quả bằng việc chuẩn bị một prompt chi tiết ngay từ đầu. Nếu prompt đầu tiên có cấu trúc tốt hơn, AI sẽ sinh ra kết quả gần với mong muốn hơn và tôi sẽ tốn ít thời gian sửa lại hơn.
