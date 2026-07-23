---
title: "Event 1"
date: 2024-01-01
weight: 1
chapter: false
pre: " <b> 4.1. </b> "
---

# Bài thu hoạch “AI & Cloud Sharing Session”

### Mục Đích Của Sự Kiện

- Chia sẻ cách cung cấp ngữ cảnh hiệu quả để AI tạo ra kết quả phù hợp hơn
- Giới thiệu các trợ lý AI hỗ trợ phân tích dữ liệu và xây dựng workflow
- Trình bày vai trò của Amazon CloudFront trong tối ưu hiệu năng, bảo mật và chi phí
- Chia sẻ kinh nghiệm phát triển sản phẩm trong cuộc thi hackathon
- Giải thích tính không tất định của LLM và các chiến lược giảm thiểu
- Giới thiệu cách xây dựng hệ thống multi-agent cho bài toán doanh nghiệp

### Danh Sách Diễn Giả

- **Tinh Truong** - Context Is Everything: Making AI Actually Work for You
- **Anh Pham** - Friendly AI Assistant with Amazon Quick
- **Thinh Nguyen** - From Edge To Origin: CloudFront as Your Foundation
- **Team VIB** - 36 hrs with LotusHacks – Building UTMorpho from Idea to Reality
- **Duc Dao** - Non-Determinism of "Deterministic" LLM Settings
- **Vy Lam** - Enterprise-Grade Multi-Agent System: The Case of Startup Credit Scoring

### Nội Dung Nổi Bật

#### Context Is Everything: Making AI Actually Work for You — 09:00 - 09:30

- Phân tích lý do AI thường tạo ra kết quả chưa phù hợp khi thiếu context
- Giải thích ý nghĩa của context khi làm việc với AI
- Trình bày sự phát triển từ prompt đến memory và khái niệm **Second AI Brain**
- Chia sẻ tư duy và các mẹo thực tế để cung cấp context tốt hơn
- Đưa ra góc nhìn nghề nghiệp và cách sinh viên có thể bắt đầu xây dựng với AI
- Trao đổi thêm với người tham dự qua phần Q&A

#### Friendly AI Assistant with Amazon Quick — 09:30 - 09:45

- **Quick Chat Agent**: Trợ lý AI hỗ trợ khám phá dữ liệu và phân tích insight
- **Quick Flows**: Tạo workflow thông minh bằng ngôn ngữ tự nhiên mà không cần lập trình
- **Quick Spaces**: Không gian cộng tác giúp chuyển insight cá nhân thành tri thức chung của nhóm
- **Quick Sight**: Xây dựng dashboard và report từ dữ liệu thô bằng ngôn ngữ tự nhiên

#### From Edge To Origin: CloudFront as Your Foundation — 09:45 - 10:25

- Giới thiệu cách sử dụng **Amazon CloudFront** cho nhiều loại workload
- Tối ưu chi phí phân phối nội dung với Amazon CloudFront
- Tìm hiểu các khả năng bảo mật của CloudFront
- Nâng cao độ tin cậy của ứng dụng thông qua edge network
- Cải thiện hiệu năng và giảm độ trễ khi phục vụ người dùng ở nhiều khu vực

#### 36 hrs with LotusHacks – Building UTMorpho from Idea to Reality — 10:25 - 10:55

- Lý do Team VIB tham gia LotusHacks
- Hành trình brainstorm từ con số 0 đến ý tưởng sản phẩm
- Cách xác định vấn đề và định hình **UTMorpho**
- Quá trình phát triển sản phẩm trong sprint 36 giờ
- Những thách thức, thất bại và các bước ngoặt quan trọng
- Tổng quan sản phẩm UTMorpho và phần demo
- Bài học rút ra và định hướng tiếp theo

#### Break — 10:55 - 11:00

- Thời gian nghỉ ngắn giữa các phiên chia sẻ

#### Non-Determinism of "Deterministic" LLM Settings — 11:00 - 11:30

- Giải thích cách LLM lựa chọn token tiếp theo
- Phân tích giả định `temperature = 0` sẽ đảm bảo tính tất định
- Làm rõ ảnh hưởng của các tối ưu trong quá trình inference đến kết quả đầu ra
- Trình bày tác động thực tế của tính không tất định đối với hệ thống AI
- Chia sẻ các chiến lược giảm thiểu khi triển khai LLM trong sản phẩm

#### Enterprise-Grade Multi-Agent System: The Case of Startup Credit Scoring — 11:30 - 12:00

- Phân tích sự khác biệt giữa hệ thống ngân hàng truyền thống và dữ liệu của startup
- Làm rõ khi nào nên và không nên sử dụng Single Agent
- Giới thiệu mô hình **Multi-Agent Paradigm**
- Trình bày blueprint của một **Virtual Credit Committee**
- Phân tích vai trò của guardrails và compliance
- Đánh giá ROI vận hành và roadmap triển khai
- Chia sẻ định hướng phát triển tiếp theo và Q&A

### Những Gì Học Được

#### Tư Duy Làm Việc Với AI

- **Context is everything**: Chất lượng kết quả phụ thuộc nhiều vào bối cảnh, mục tiêu, dữ liệu và ràng buộc được cung cấp
- **From prompts to memory**: AI đang phát triển từ công cụ hỏi đáp thành hệ thống có khả năng sử dụng memory và tri thức cá nhân
- **Second AI Brain**: Có thể tổ chức tài liệu, ghi chú và kiến thức để AI hỗ trợ học tập và làm việc hiệu quả hơn
- **Practical AI mindset**: Không chỉ chọn model mạnh mà còn cần thiết kế context và quy trình sử dụng phù hợp

#### Trợ Lý AI Và Khai Thác Dữ Liệu

- Sử dụng AI assistant để khám phá dữ liệu và phân tích insight
- Tạo workflow bằng ngôn ngữ tự nhiên mà không cần viết code
- Chuyển tri thức cá nhân thành nguồn kiến thức có thể chia sẻ trong nhóm
- Xây dựng dashboard và report trực tiếp từ dữ liệu thô

#### Kiến Trúc Cloud Và Amazon CloudFront

- CloudFront không chỉ là CDN mà còn hỗ trợ hiệu năng, bảo mật và độ tin cậy
- Edge network giúp giảm độ trễ cho người dùng ở nhiều khu vực
- Cần cân nhắc CloudFront như một lớp nền trong kiến trúc web và API
- Tối ưu kiến trúc cần cân bằng giữa performance, security và cost

#### Phát Triển Sản Phẩm

- Xác định đúng vấn đề là bước quan trọng trước khi xây dựng giải pháp
- Trong thời gian giới hạn, team cần phân chia công việc rõ ràng và tập trung vào tính năng cốt lõi
- Thất bại và thay đổi hướng đi là một phần của quá trình phát triển sản phẩm
- Demo hoạt động là kết quả của khả năng phối hợp, thích nghi và ra quyết định nhanh

#### Độ Tin Cậy Của LLM

- `temperature = 0` không phải lúc nào cũng bảo đảm kết quả giống nhau hoàn toàn
- Các tối ưu ở tầng inference có thể ảnh hưởng đến token được lựa chọn
- Hệ thống AI cần có test, monitoring và cơ chế xử lý sai khác đầu ra
- Không nên dựa vào một thiết lập duy nhất để đảm bảo tính ổn định

#### Kiến Trúc Multi-Agent

- Single Agent không phải lúc nào cũng phù hợp với quy trình nghiệp vụ phức tạp
- Multi-agent giúp phân tách trách nhiệm theo từng vai trò chuyên môn
- Các Agent cần phối hợp theo một quy trình thống nhất thay vì hoạt động độc lập
- Guardrails và compliance là thành phần quan trọng trong hệ thống AI doanh nghiệp
- Việc triển khai cần dựa trên giá trị vận hành và roadmap rõ ràng

### Ứng Dụng Vào Công Việc

- **Cải thiện prompt và context**: Cung cấp đầy đủ mục tiêu, dữ liệu, ràng buộc và định dạng kết quả khi làm việc với AI
- **Xây dựng kho tri thức cá nhân**: Áp dụng tư duy Second AI Brain để tổ chức tài liệu và ghi chú học tập
- **Ứng dụng AI vào workflow**: Nghiên cứu sử dụng AI assistant để phân tích dữ liệu, tạo báo cáo và tự động hóa tác vụ
- **Tối ưu ứng dụng với CloudFront**: Cân nhắc sử dụng CloudFront để cải thiện performance, security và reliability
- **Thiết kế khả năng kiểm thử LLM**: Xây dựng bộ test, tiêu chí đánh giá và monitoring thay vì giả định đầu ra luôn tất định
- **Đánh giá mô hình multi-agent**: Chỉ sử dụng nhiều Agent khi bài toán thật sự cần phân tách vai trò và có cơ chế phối hợp rõ ràng
- **Áp dụng tư duy hackathon**: Ưu tiên vấn đề cốt lõi, xây dựng MVP và điều chỉnh nhanh dựa trên phản hồi

### Trải nghiệm trong event

Tham gia sự kiện **“AI & Cloud Sharing Session”** là một trải nghiệm bổ ích, giúp em có góc nhìn rộng hơn về cách AI và Cloud đang được áp dụng vào học tập, phát triển sản phẩm và hệ thống doanh nghiệp. Một số trải nghiệm nổi bật:

#### Học hỏi từ các diễn giả có chuyên môn

- Mỗi diễn giả mang đến một góc nhìn khác nhau, từ cách làm việc hiệu quả với AI đến thiết kế kiến trúc Cloud và multi-agent.
- Các nội dung được trình bày gắn với tình huống thực tế, giúp em hiểu rõ hơn giá trị và giới hạn của từng công nghệ.

#### Thay đổi cách sử dụng AI

- Phiên **Context Is Everything** giúp em nhận ra rằng kết quả AI không chỉ phụ thuộc vào model hay prompt, mà còn phụ thuộc vào chất lượng context.
- Khái niệm **Second AI Brain** gợi mở cách tổ chức kiến thức cá nhân để AI có thể hỗ trợ học tập và làm việc tốt hơn.

#### Hiểu thêm về kiến trúc Cloud

- Phiên chia sẻ về Amazon CloudFront giúp em hiểu CloudFront không chỉ dùng để cache nội dung.
- CloudFront còn có thể trở thành một lớp quan trọng để cải thiện hiệu năng, bảo mật, độ tin cậy và chi phí của hệ thống.

#### Học hỏi từ quá trình xây dựng sản phẩm thực tế

- Câu chuyện 36 giờ phát triển UTMorpho cho thấy tầm quan trọng của việc chọn đúng vấn đề và tập trung vào sản phẩm cốt lõi.
- Những khó khăn và bước ngoặt của Team VIB cho thấy khả năng thích nghi đóng vai trò quan trọng khi làm việc dưới áp lực thời gian.

#### Nhận thức rõ hơn về giới hạn của LLM

- Phiên về non-determinism giúp em hiểu rằng `temperature = 0` không đồng nghĩa với đầu ra luôn giống nhau.
- Bài học này rất hữu ích khi thiết kế test và đánh giá độ ổn định cho ứng dụng sử dụng LLM.

#### Tiếp cận hệ thống Multi-Agent trong doanh nghiệp

- Use case Startup Credit Scoring minh họa cách nhiều Agent chuyên biệt có thể phối hợp như một hội đồng tín dụng ảo.
- Em hiểu thêm rằng hệ thống multi-agent cần guardrails, compliance và quy trình điều phối rõ ràng để có thể triển khai trong thực tế.

#### Một số hình ảnh khi tham gia sự kiện

<img src="/images/4-EventParticipated/4.1-Event1/01-workshop-exercises.png" alt="Slide bài tập workshop về xác thực, guardrails, permission boundaries, tích hợp MCP và triển khai Terraform" width="960" height="1280" style="width: 100%; max-width: 760px; height: auto; display: block; margin: 1.5rem auto 0.5rem; border-radius: 6px;" />

<p style="text-align: center;"><em>Các bài tập workshop về xác thực, guardrails, kiểm soát truy cập, tích hợp MCP và triển khai hạ tầng theo tiêu chuẩn doanh nghiệp.</em></p>

> Tổng thể, sự kiện không chỉ cung cấp kiến thức về AI và Cloud mà còn giúp em thay đổi cách tư duy về context, độ tin cậy của LLM, phát triển sản phẩm và thiết kế hệ thống multi-agent trong môi trường thực tế.
