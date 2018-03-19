[Source](https://www.codeproject.com/Tips/808058/Reasons-for-using-design-patterns "Permalink to Reasons for using design patterns")

# Lý do sử dụng mẫu thiết kế

## Giới thiệu

Theo bài báo trước có tựa đề [Why design is Critical to Software Development][1], Tôi muốn giải quyết một khía cạnh nâng cao hơn một chút về thiết kế phần mềm được gọi là  `Design Patterns`. Giống như bài báo trước của tôi, ý tưởng này đã xuất hiện trong một cuộc thảo luận liên quan đến thành công của việc thiết kế phần mềm với một đồng nghiệp làm việc. Trọng tâm chính của cuộc thảo luận là ý kiến ​​cho rằng `design patterns` quá tốn thời gian để sử dụng trong lĩnh vực phát triển phần mềm thương mại. Mục đích của tôi ở đây là để chứng minh tại sao tôi tin rằng nó sai.

Tôi sẽ không đi vào bất kỳ chi tiết về cơ học hoặc thực hiện của bất kỳ mẫu `Design Patterns` cụ thể. Có nhiều nguồn xuất sắc có sẵn ở bên ngoài.

## Mẫu thiết kế là gì?

Vậy bắt đầu, chính xác là một `Design Pattern` là gì? Dưới đây là một vài định nghĩa cho thuật ngữ:

Trích xuất từ [Wikipedia][2]:

> "Một mẫu thiết kế trong kiến ​​trúc và khoa học máy tính là một cách chính thức để ghi lại một giải pháp cho một vấn đề thiết kế trong một lĩnh vực chuyên môn cụ thể."

Trích xuất từ [Data & Object Factory][3]:

> "Mẫu thiết kế là các giải pháp định kỳ cho các vấn đề thiết kế phần mềm mà bạn tìm thấy trong phát triển ứng dụng thực tế. Các mẫu là về thiết kế và tương tác của các đối tượng, cũng như cung cấp một nền tảng giao tiếp liên quan đến những giải pháp thanh lịch, có thể tái sử dụng đối với những thách thức lập trình thường gặp. "

Vì vậy `Design Pattern` là một mục đích chung của một vấn đề, có thể được áp dụng cho một giải pháp cụ thể. Khi các nhà phát triển phần mềm có xu hướng giải quyết nhiều loại vấn đề tương tự, điều đó có nghĩa là bất kỳ giải pháp phần mềm nào sẽ kết hợp các yếu tố tương tự từ các giải pháp khác. Tại sao lại phát minh lại bánh xe?

## Well documented and understood 

Vì `Design Patterns` được các nhà kiến ​​trúc sư, nhà thiết kế và phát triển phần mềm biết đến và hiểu rõ, thì ứng dụng của họ trong một giải pháp cụ thể cũng sẽ được hiểu rõ.

`Design Patterns` cho một nhà phát triển phần mềm một loạt các giải pháp được thử và thử nghiệm cho các vấn đề chung, do đó giảm nguy cơ kỹ thuật cho dự án bằng cách không phải sử dụng một thiết kế mới và chưa được kiểm tra.

`Design Patterns` có thể không dẫn đến giảm thời gian phát triển vì có một đường cong học tập nếu đội không quen với chúng. Tuy nhiên, nhìn sâu hơn xuống đường ống phát triển, một khi quen thuộc với chúng tăng lên, thời gian phát triển nên giảm dần.

## Đồng điệu với kỹ thuật dân dụng

Để đưa ra một sự tương tự của một mẫu thiết kế từ lĩnh vực kỹ thuật dân dụng (như tôi đã nêu trong bài báo của tôi [Why design is Critical to Software Development][1]) có những điểm tương đồng gần giống với công nghệ phần mềm), sẽ là một giải pháp để vượt sông. Đây là một vấn đề thường xuyên đối với các kỹ sư dân dụng, trong đó có một số giải pháp được ghi nhận và hiểu rõ. Các kỹ sư dân dụng có thể xây dựng một cầu hoặc đường hầm.

Tại sao một kỹ sư dân dụng cố gắng giải quyết vấn đề này từ đầu khi có những giải pháp thế giới thực có thể được đề cập đến? Có sự tương đồng gần gũi giữa kỹ sư dân dụng giải quyết vấn đề về sông, và kỹ sư phần mềm giải quyết vấn đề phần mềm:

* Các giải pháp (cầu hoặc đường hầm) đều được hiểu và ghi lại
* Các giải pháp (cầu hoặc đường hầm) giải quyết các vấn đề kỹ thuật xây dựng định kỳ
* Các giải pháp (cầu hoặc đường hầm) không xác định hoặc quy định, nhưng là trừu tượng và có thể được điều chỉnh cho các vấn đề cụ thể để ra tay (cầu hoặc các vật liệu xây dựng đường hầm ví dụ có thể được lựa chọn để liên kết với các vấn đề cụ thể)

Lập luận đối với `Design Patterns` cho thấy chúng không phù hợp với mục đích thương mại do quá trình thực hiện lâu dài của chúng không giữ được. `Design Patterns` tiết kiệm thời gian (khi được xem qua suốt đời của ứng dụng) bằng cách cho nhà phát triển lựa chọn các giải pháp đã được thử và thử nghiệm sẵn có mà họ có thể tùy chỉnh theo nhu cầu cụ thể của riêng họ..

Vấn đề duy nhất tôi đã gặp với `Design Patterns` là họ mất thời gian để tìm hiểu. Một số người trong số họ có thể khó hiểu và hiểu. Đây là một lời chỉ trích hợp lý, vì nó đòi hỏi một nhà phát triển có tay nghề cao hơn sử dụng chúng. Điều này sau đó có thể làm tăng chi phí dự án ban đầu. Tuy nhiên, khi xem xét trong suốt thời gian sử dụng một ứng dụng, tôi sẽ hoàn toàn mong đợi những chi phí phát triển ban đầu này sẽ được bù đắp lại do chi phí bảo trì thấp hơn do sự hiểu biết cao hơn và khả năng mở rộng dễ dàng hơn (làm cho ứng dụng dễ dàng mở rộng trong tương lai để đáp ứng những cơ hội đang nổi lên).

`Design Patterns` giảm sự phức tạp, và do đó giải pháp trở nên dễ hiểu hơn.

`Design Patterns` là các giải pháp được thử và thử nghiệm, nhà phát triển không cần phải bắt đầu từ đầu, và có thể chạy nền với một giải pháp đã được chứng minh là có hiệu quả (miễn là `Design Patterns` được sử dụng giải quyết một vấn đề tương tự). Sẽ là sai khi mong đợi một cây cầu để giải quyết vấn đề băng qua đại dương, nơi mà cây cầu chỉ đơn giản là không phù hợp.

## Lợi ích của việc sử dụng mẫu thiết kế

`Design Patterns` do đó cung cấp các lợi ích sau.

* Họ cung cấp cho nhà phát triển một loạt các giải pháp thử và thử nghiệm để làm việc với
* Chúng là ngôn ngữ trung tính và do đó có thể được áp dụng cho bất kỳ ngôn ngữ nào hỗ trợ hướng đối tượng
* Họ hỗ trợ truyền thông bởi thực tế là họ có tài liệu tốt và có thể được nghiên cứu nếu đó không phải là trường hợp.
* Họ đã có một hồ sơ theo dõi đã được chứng minh vì chúng đã được sử dụng rộng rãi và do đó làm giảm nguy cơ kỹ thuật cho dự án
* Chúng rất linh hoạt và có thể được sử dụng trong bất kỳ loại ứng dụng hoặc tên miền nàon

## Phần kết luận

`Design Patterns`, mặc dù đường cong học tập ban đầu, là một sự đầu tư rất đáng giá. Họ sẽ cho phép bạn thực hiện các giải pháp được thử và thử nghiệm cho các vấn đề, do đó tiết kiệm thời gian và nỗ lực trong giai đoạn triển khai của vòng đời phát triển phần mềm. Bằng cách sử dụng các giải pháp được hiểu rõ và có tài liệu, sản phẩm cuối cùng sẽ có một mức độ hiểu biết cao hơn nhiều. Nếu giải pháp được dễ dàng hơn để hiểu, sau đó bằng cách mở rộng, nó cũng sẽ được dễ dàng hơn để duy trì.

[1]: http://www.codeproject.com/Tips/806867/Why-Design-is-Critical-to-Software-Development
[2]: http://en.wikipedia.org/wiki/Design_pattern
[3]: http://www.dofactory.com/Patterns/Patterns.aspx

## Thực hành
- https://coderoncode.com/design-patterns/programming/php/coding/development/2014/01/19/design-patterns-php-factories.html
- https://www.binpress.com/tutorial/the-factory-design-pattern-explained-by-example/142
- https://www.codeproject.com/Articles/852232/PHP-Singleton-Pattern-A-Step-by-Step-And-Problem-s
- http://www.fluffycat.com/PHP-Design-Patterns/

**Từ khóa:** `how to separate code to package php`, `step by step php design pattern singleton`(change singleton to other for more result)
