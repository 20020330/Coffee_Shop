# Coffee_Shop

CHƯƠNG 1: TỔNG QUAN ĐỀ TÀI

1.1. Mô tả đề tài.

1.1.1. Bàn

Trong cửa hàng có nhiều bàn được đánh số thứ tự theo cách sắp xếp của quản lý. Có 3 loại bàn theo số chỗ ngồi: 2, 4 và 8 chỗ. Khách hàng không được tự ý chuyển chỗ bàn ghế.

1.1.2. Thực đơn của quán. 

Thực đơn của quán bao gồm 5 loại thức uống chính: trà sữa, cà phê, sữa chua, nước trái cây và đá xay.

1.1.3. Sản phẩm.

Mỗi loại nước uống có nhiều lựa chọn gọi là sản phẩm của quán. Ví dụ trà sữa có trà sữa truyền thống, trà sữa thạch kim cương đen, trà sữa trân châu hoàng kim, hồng trà sữa tươi, trà đào, trà chanh,... Sữa chua có sữa chua xoài, sữa chua việt quốc, sữa chua tắc chanh dây,...

Mỗi phần sẽ có 3 cỡ: cỡ nhỏ, vừa và lớn tương ứng với 3 size S, M, L.

Mỗi sản phẩm có giá riêng tùy vào kích cỡ.

1.1.4. Đơn hàng.

Đơn hàng gồm hai loại: đơn dùng tại bàn và đơn mua mang đi.

1.1.5. Nhân viên.

Nhân viên bao gồm: nhân viên đặt hàng và nhân viên quản lý. 

1.1.6. Đặt đơn và tính tiền.  

Bước 1: Xác định khách dùng tại bàn hay mang đi. 

Khi khách hàng đến, nhân viên sẽ hỏi khách dùng tại bàn hay mang đi, nếu khách dùng tại bàn thì hỏi số lượng khách hàng và chọn bàn phù hợp.

Bước 2: Đặt đơn. 

Nhân viên sẽ tiến hành đặt đơn cho khách thông qua ứng dụng, do đó việc thay đổi nước uống chỉ được thực hiện trong quá trình đặt đơn của nhân viên, và sau đó khi bấm thanh toán thì không thể điều chỉnh được nữa.

Bước 3. Tính tiền. 

Nhân viên tính tiền và xuất hóa đơn cho khách bao gồm ngày lập hóa đơn, chi tiết hóa đơn, tổng tiền, nhân viên lập hóa đơn.

1.1.7. Món thêm.

Quán có bán kèm các món thêm như thạch dừa, trân châu thủy tinh, bánh cookie, pudding,... và tùy theo từng sản phẩm mới có. Ví dụ hồng trà sữa tươi có món thêm là kem, trân châu, pudding và khách hàng có thể chọn thêm 1 hoặc cả 3 món thêm cùng lúc. Tuy nhiên, cà phê đen thì không có món thêm nào. Mỗi loại món thêm có 1 giá riêng.

1.1.8. Thống kê và báo cáo.

Hàng tháng nhân viên quản lý sẽ thực hiện việc thống kê và báo số số lượng đơn hàng, doanh thu, số lượng mỗi sản phẩm bán được, để có thể biết được sản phẩm nào bán chạy, sản phẩm nào bán không chạy từ đó có những kế hoạch kinh doanh phù hợp cho những tháng sau.

Hàng ngày nhân viên bán hàng phải thực hiện việc thống kê báo cáo theo ngày khi kết ca.

1.2. Mục tiêu đề tài.	

Vì đây là một dự án nhỏ em sẽ ứng dụng “Mô hình thác nước” (Waterfall Model) để xây dựng phần mềm. Nhóm đã đặt ra các mục tiêu như sau:

Thứ nhất, hiểu rõ hơn về quy trình xây dựng phần mềm một cách chuyên nghiệp và bài bản thông qua mô hình Waterfall Model.

Thứ hai, áp dụng những kiến thức đã học vào đề tài như: lập trình Java, lập trình hướng đối tượng, Java Swing, mô hình ba lớp, SQL,.. để xây dựng phần mềm, lập trình giao diện và quản lý dữ liệu.

Thứ ba, đề tài còn giúp các thành viên trong nhóm sử dụng thành thạo các công cụ như: Apache NetBeans IDE, SQL Server, Github, Drawio, Photoshop CS6, Trello,... để quản lý dự án và xây dựng phần mềm. 

Mục tiêu cuối cùng và không kém phần quan trọng đó là sau đồ án này, mỗi người em đều sẽ nâng cao kinh nghiệm về cách tổ chức và làm việc nhóm (teamwork).

1.3. Phạm vi đề tài.

1.3.1. Dữ liệu.

Phần mềm sử dụng hệ quản trị cơ sở dữ liệu SQL Server để lưu trữ và quản lý dữ liệu.

1.3.2. Xử lý.

Phần mềm tập trung vào việc quản lý và bán hàng, không tập trung nhiều vào việc quản lý nhân sự.

1.3.3. Giao diện.

Phần mềm hướng đến một giao diện đơn giản, thân thiện với người dùng và rất dễ sử dụng.

1.4.4. Mạng.

Phần mềm hoạt động trên mạng cục bộ (LAN).

1.6. Tổng quan về mô hình thác nước (Waterfall model) và phương pháp thực hiện đề tài.

1.6.1 Khái niệm.

Waterfall model (mô hình thác nước) hay còn được gọi là mô hình tuần tự tuyến tính được Winston Royce giới thiệu vào năm 1970. Nó được gọi là mô hình tuần tự tuyến tính là vì các pha của mô hình thông thường chỉ được thực hiện một lần và không có sự quay lại giữa các pha và phải đi theo trình tự từ trên xuống dưới trông như thác nước đổ. Pha tiếp theo chỉ được bắt đầu khi pha trước đó đã được hoàn thành.
Trước đây mô hình thác nước được sử dụng rất phổ biến nhưng ngày nay nó rất ít khi được sử dụng bởi tính kém linh hoạt giữa các giai đoạn trong quá trình phát triển phần mềm và đòi hỏi phải có sự chặt chẽ, rõ ràng về yêu cầu ngay từ giai đoạn đầu tiên của quá trình phát triển. Mặc dù độ phổ biến của mô hình thác nước không còn được rộng rãi như trước nhưng nó vẫn rất quan trọng vì tất cả các mô hình phát triển phần mềm khác đều dựa trên mô hình thác nước. 

1.6.2. Phân tích các giai đoạn.

Mô hình thác nước được chia thành 5 giai đoạn:

1.	Phân tích yêu cầu (Requirements definition)
	
2.	Thiết kế hệ thống và phần mềm (System and software design)
   
3.	Hiện thực và kiểm tra modules (Implementation and unit testing)

4.	Tích hợp và kiểm tra hệ thống (Integration and system testing)
	
5.	Chuyển giao và bảo trì (Operation and maintenance)
    
Hình ảnh minh họa mô hình thác nước:

![image](https://github.com/20020330/img_caption/assets/85932447/f80760eb-64ea-46a7-99cf-324ac72e3743)

1.6.3. Chi tiết các giai đoạn.

1.6.3.1. Phân tích yêu cầu (Requirements definition).

Người dùng thường chỉ đưa ra những ý tưởng, nhiều khi rất mơ hồ về phần mềm mà họ mong muốn xây dựng. Chính vì vậy mục đích của giai đoạn này là để hiểu một cách chính xác các yêu cầu của khách hàng. Vậy nên các lập trình viên sẽ phải thu thập tất cả các yêu cầu cần thiết từ khách hàng, sau đó sẽ phân tích để hiểu đúng những yêu cầu về phần mềm. Yêu cầu của phần mềm là tất cả các yêu cầu về phần mềm do người dùng nêu ra bao gồm các chức năng của phần mềm, hiệu năng của phần mềm, giao diện của phần mềm và một số các yêu cầu khác.

1.6.3.2. Thiết kế hệ thống và phần mềm (System and software design).

Giai đoạn này nhằm mục đích chuyển đổi các yêu cầu thu thập được từ khách hàng thành các bản vẽ thiết kế chi tiết cũng như kiến trúc phần mềm tổng thể của hệ thống.

1.6.3.3. Hiện thực và kiểm tra modules (Implementation and unit testing).

Tại đây, các bản thiết kế được thực hiện. Từ đó, các lập trình viên sẽ tạo ra chương trình bằng ngôn ngữ lập trình. Các đoạn code sẽ được kiểm tra kỹ lưỡng và sửa đổi nếu có lỗi phát sinh. Các đoạn code nhỏ được thử nghiệm một cách cô lập ban đầu. 

1.6.3.4. Tích hợp và kiểm tra hệ thống (Integration and system testing).

Các lập trình viên sẽ tích hợp code và kiểm tra sự tương tác của toàn bộ hệ thống để xem các đơn vị có vận hành trơn tru hay không, nếu có trục trặc thì sẽ tiến hành sửa lỗi. 

Giai đoạn này rất quan trọng vì chất lượng của phần mềm có tốt hay không là do chất lượng của quá trình kiểm tra. Phần mềm tốt sẽ dẫn đến khách hàng hài lòng.

1.6.3.5. Chuyển giao và bảo trì (Operation and maintenance).

Ở phần cuối, sau khi chắc chắn đã sửa hết lỗi và vận hành trơn tru, các lập trình viên sẽ tiến hành chuyển giao cho khách hàng để đưa vào sử dụng, chạy hệ thống trong môi trường thực tế.						
Công đoạn bảo trì sửa chữa - nâng cấp sẽ được thực hiện nếu có lỗi phát sinh trong quá trình sử dụng hoặc nếu muốn nâng cao năng suất hệ thống thì các lập trình viên sẽ dựa trên yêu cầu của khách hàng để tiến hành bảo trì nâng cấp, cải tiến phần mềm.

1.6.4. Sự phụ thuộc của các giai đoạn.

Trong mô hình này, hoạt động phát triển phần mềm được chia thành các giai đoạn khác nhau và ở mỗi giai đoạn sẽ bao gồm hàng loạt các nhiệm vụ và có các mục tiêu khác nhau.

Giai đoạn trước bắt buộc phải được hoàn thành trước khi bắt đầu giai đoạn tiếp theo, do đó sẽ không có sự chồng chéo nào trong mô hình thác nước.

1.6.5. Ưu điểm và nhược điểm.

1.6.5.1. Ưu điểm.

•	Đây là mô hình đơn giản, dễ áp dụng, quy trình rõ ràng theo từng bước.

•	Dễ quản lý và bảo trì bởi cách tiếp cận tuyến tính và cố định theo từng bước. 

•	Các tiêu chí đầu vào và đầu ra được xác định rõ ràng nên dễ dàng trong công tác kiểm tra chất lượng.

•	Hoạt động hiệu quả trong các dự án nhỏ, với các yêu cầu rõ ràng.

•	Có nhiều tài liệu cung cấp cho khách hàng.

1.6.5.2. Nhược điểm.

•	Không phải mô hình lý tưởng cho các dự án lớn và dài ngày.

•	Không hiệu quả đối với những dự án đối mặt với các yêu cầu không rõ ràng từ đầu.

•	Khó thích ứng với thay đổi bao gồm yêu cầu, kế hoạch, phạm vi dự án…

•	Độ trực quan thấp và giá trị chuyển giao chậm khi đến cuối chu trình người dùng mới nhìn thấy và sử dụng sản phẩm.

1.6.6. Lý do lựa chọn mô hình.

Mô hình thác nước phù hợp với quy mô kinh doanh nhỏ. Cho nên với đồ án lần này, nhóm chúng em quyết định chọn mô hình thác nước để triển khai. Lí do là vì cửa hàng mà chúng em thực hiện phần mềm có quy mô kinh doanh không quá lớn, chỉ yêu cầu các chức năng quan trọng đối với các nhân viên trong cửa hàng.

1.7. Mô tả nghiệp vụ các công cụ, công nghệ sử dụng trong đồ án: Apache NetBeans IDE 12.6, SQL Server, Github, Draw.io, Photoshop CS6, Trello,…

1.7.1. Apache NetBeans IDE 12.6.

NetBeans IDE là một công cụ hỗ trợ lập trình viết mã code, được sử dụng chủ yếu cho các lập trình viên phát triển Java. Đây là môi trường phát triển tích hợp và cực kỳ cần thiết cho các lập trình viên, công cụ này có thể hoạt động tốt với rất nhiều nền tảng hệ điều hành khác nhau như Linux, Windows, MacOS,... là một mã nguồn mở cung cấp các tính năng cần thiết nhất nhằm tạo ra các ứng dụng web, thiết bị di động, desktop.

NetBeans IDE có các ưu điểm giao diện trực quan, dễ thao tác và là một môi trường rất thích hợp cho việc lập trình xây dựng giao diện đồ họa, phần mềm máy tính. Chính vì thế, nhóm chúng em chọn NetBeans IDE để làm công cụ lập trình giao diện và các thao tác xử lý dữ liệu cho đồ án “Xây dựng phần mềm quản lý quán cà phê”.

1.7.2. Github.

Github là một dịch vụ nổi tiếng cung cấp kho lưu trữ mã nguồn Git cho các dự án phần mềm. Github có đầy đủ những tính năng của Git, ngoài ra nó còn bổ sung những tính năng về social để các developer tương tác với nhau trong dự án.

Github là công cụ giúp quản lý source code tổ chức theo dạng dữ liệu phân tán. Giúp đồng bộ source code của team lên 1 server. Hỗ trợ các thao tác kiểm tra source code trong quá trình làm việc.

Github là công cụ giúp nhóm em quản lý source code và kết nối tương tác với nhau trong lúc thực hiện đồ án.

1.7.3. Draw.io.

Draw.io là một chương trình có nhiều công cụ cho phép người sử dụng tạo ra cơ quan đại diện về cấu trúc và đồ họa của mô hình kinh doanh.

Draw.io được nhóm sử dụng để hỗ trợ vẽ các sơ đồ BFD, DFD, class, usecase, sequence, workflow,...

1.7.4. Photoshop CS6.

Photoshop CS6 là phần mềm chỉnh sửa ảnh chuyên nghiệp. Với phần mềm này, người dùng có thể chỉnh sửa, biên tập ảnh, video một cách dễ dàng tùy theo ý muốn và sở thích của mình.

Photoshop CS6 được nhóm sử dụng để thiết kế các giao diện phần mềm cho đồ án.

1.7.5	SQL Server :

SQL Server là một máy chủ cơ sở dữ liệu, có chức năng chính là lưu trữ và truy xuất dữ liệu theo yêu cầu của các ứng dụng phần mềm.

SQL Server được nhóm sử dụng để xây dựng các bảng lưu trữ dữ liệu để phục vụ cho các chức năng cần thao tác và trích xuất dữ liệu của phần mềm.

1.7.6	Trello :

Trello là một phần mềm giúp đội nhóm dễ dàng quản lý và theo dõi tiến trình công việc, dự án. Với các thẻ ghim có thể là nhiệm vụ, ghi chú, dự án, file chia sẻ giúp cho làm việc nhóm tốt và hiệu quả hơn. 

Trello được nhóm sử dụng để quản lý, theo dõi và phân chia nhiệm vụ cho nhau trong suốt quá trình thực hiện đồ án.

1.8. Activity Bar Chart.

![image](https://github.com/20020330/img_caption/assets/85932447/c75df250-57ae-40ec-abde-3e6918dfcef2)

CHƯƠNG 2: XÁC ĐỊNH VÀ THU THẬP YÊU CẦU
2.1. Tổng quan về cửa hàng.
Cửa hàng cà phê “Coffee Shop” chuyên kinh doanh các sản phẩm nước uống thuộc nhiều thể loại như cà phê, trà sữa, nước trái cây, sữa chua và đá xay. Với quy mô kinh doanh nhỏ và hình thức kinh doanh vẫn theo kiểu truyền thống là mua bán trực tiếp tại cửa hàng. 
Cửa hàng sẽ phục vụ hai loại khách hàng: khách hàng mua mang đi và khách hàng dùng tại bàn.
Cửa hàng chỉ vừa kinh doanh trong thời gian gần đây, nên chưa có bất kỳ phần mềm nào hỗ trợ cho việc quản lý và bán hàng. Do đó sẽ không tránh khỏi nhiều khó khăn trong việc doanh thu và thống kê, cũng vì vậy mà khó đề ra nhiều chiến lược kinh doanh trong tương lai. Nắm bắt được những bất cập trên, cửa hàng quyết định xây dựng một phần mềm để quản lý nội bộ việc kinh doanh nhằm nâng cao doanh số, đồng thời giúp cho quản lý có thể dễ dàng quản lý mọi thứ trong cửa hàng.
2.2. Khảo sát hiện trạng.
2.2.1. Hiện trạng tổ chức.

	

	

2.2.2. Hiện trạng nghiệp vụ.
Cửa hàng cà phê kinh doanh nhiều loại nước uống. Mỗi loại nước uống có nhiều sản phẩm. Mỗi sản phẩm có 3 cỡ (S, M, L) và có một số topping đi kèm. 
Khi khách hàng đến, nhân viên đặt hàng sẽ hỏi khách dùng tại bàn hay mang đi. Nếu khách dùng tại bàn thì chọn bàn cho khách, sau đó tiến hành đặt đơn, chọn món và topping đi kèm. Khi khách yêu cầu thanh toán thì tiến hành tính tiền và thanh toán đơn hàng trên số bàn mà khách đang ngồi, sau đó xuất hóa đơn cho khách. Nếu là khách dùng mang đi thì không cần chọn bàn cho khách, chỉ cần đặt đơn, tính tiền, thanh toán và xuất hóa đơn.
Quản lý cửa hàng sẽ quản lý nhiều công việc như quản lý thể loại sản phẩm, quản lý sản phẩm, quản lý món thêm, quản lý tài khoản đăng nhập, quản lý nhân viên, quản lý đơn hàng,...
Hàng ngày, nhân viên cửa hàng phải thực hiện việc thống kê và báo cáo doanh thu, đơn hàng, sản phẩm, món thêm. Cuối tháng, nhân viên quản lý sẽ tổng hợp để biết được tình hình trạng kinh doanh cũng như sản phẩm nào bán chạy, sản phẩm nào bán không chạy để có những chiến lược kinh doanh phù hợp trong tương lai.
2.2.3. Hiện trạng tin học.
Cửa hàng đã trang bị được máy tính cho các bộ phận để thuận tiện cho việc sử dụng phần mềm.
Phần cứng:
•	CPU: Core i5.
•	Tốc độ xử lý 3.9GHz
•	RAM: 16GB
•	Các máy tính đã được kết nối mạng, tốc độ đường truyền là 40 Mb/s
Phần mềm: Các máy tính sử dụng hệ điều hành Windows 10 và chưa có bất kỳ phần mềm nào hỗ trợ cho việc quản lý và bán hàng.
Các nhân viên trong cửa hàng đều có kiến thức về tin học, có khả năng sử dụng máy tính.
2.3. Xác định yêu cầu.
2.3.1. Báo cáo phỏng vấn.

Lịch hẹn phỏng vấn

Hệ thống: Cửa hàng cà phê.
Người lập: Đoàn Thành Lợi.
Ngày lập: 05/04/2022.
Chủ đề	Yêu cầu	Ngày bắt đầu	Ngày kết thúc
Quy trình điều hành cửa hàng cà phê.	Hiểu về cách thức và quy trình vận hành của cửa hàng cà phê. Nắm bắt được yêu cầu về hệ thống của khách hàng	10/04/2022	10/04/2022

 
                                
	  Báo cáo phỏng vấn
Người thực hiện: Đoàn Thành Lợi 
Người được phỏng vấn: Quản lý cửa hàng cà phê.
Ngày phỏng vấn: 10/04/2022
Mục tiêu: Hiểu rõ quy trình điều hành hoạt động của cửa hàng cà phê, nắm bắt được mong muốn của khách hàng về các tiêu chí và chức năng của phần mềm.
Nội dung: 
Sau khi phỏng vấn quản lý cửa hàng. Thì cửa hàng được tổ chức với 2 bộ phận với các nhiệm vụ sau:
Quản lý cửa hàng:
-	Quản lý, kiểm soát và điều hành hoạt động kinh doanh của cửa hàng cà phê.
-	Tiếp nhận báo cáo doanh thu theo từng ngày từ nhân viên bán hàng.
-	Hàng tháng thống kê số lượng đơn hàng nhập liệu, doanh thu, sản phẩm được ưa chuộng. Từ đó nắm bắt được tình hình kinh doanh và đưa ra các giải pháp giúp thúc đẩy việc kinh doanh của cửa hàng trong tương lai.
Nhân viên bán hàng:
-	Lập đơn hàng mang về.
-	Lập đơn hàng tại bàn.
-	Thanh toán đơn hàng tại bàn.
-	Pha chế thức uống.
-	Dọn dẹp và giữ vệ sinh cửa hàng.
-	Thống kê sản phẩm, món thêm và doanh thu khi kết thúc ca làm việc.
Tiêu chí phần mềm: Phải đáp ứng được các chức năng cơ bản cho việc quản lý và bán hàng. Phần mềm xử lý linh hoạt, dễ sử dụng, giao diện dễ nhìn.


Câu hỏi phỏng vấn
1.	Quy mô tổ chức cửa hàng gồm bao nhiêu bộ phận ?
2.	Cửa hàng hiện chưa có phần mềm nào hổ trợ, vậy các bộ phận thực hiện quy trình làm việc hằng ngày như thế nào ?
3.	Cửa hàng kinh doanh với quy mô như thế nào ? ( Quy mô nhỏ hay lớn )
4.	Tiêu chí mong đợi của anh/chị về các chức năng của phần mềm là gì ?

2.3.2. Yêu cầu chức năng.
Quản lý cửa hàng có thể thực hiện tất cả các chức năng của phần mềm như:
•	Đăng nhập hệ thống
•	Đăng xuất hệ thống
•	Quản lý tài khoản đăng nhập (tìm kiếm, thêm, sửa, xóa).
•	Quản lý nhân viên (tìm kiếm, thêm, sửa, xóa).
•	Quản lý thể loại sản phẩm (tìm kiếm, thêm, sửa).
•	Quản lý sản phẩm (tìm kiếm, thêm, sửa).
•	Quản lý món thêm (tìm kiếm, thêm, sửa).
•	Quản lý đơn hàng (tìm kiếm, xóa, in).
•	Xử lý đơn hàng cho khách dùng tại bàn.
•	Xử lý đơn hàng cho khách dùng mang về.
•	Thanh toán và xuất hóa đơn.
•	Thống kê báo cáo sản phẩm theo thời gian.
•	Thống kế báo cáo món thêm theo thời gian.
•	Thống kê báo cáo doanh thu theo thời gian,
Nhân viên bán hàng chỉ được sử dụng một số chức năng đặc thù phục vụ cho việc bán hàng như:
•	Đăng nhập hệ thống
•	Đăng xuất hệ thống
•	Xử lý đơn hàng cho khách dùng tại bàn.
•	Xử lý đơn hàng cho khách dùng mang về.
•	Thanh toán và xuất hóa đơn.
•	Thống kê báo cáo sản phẩm theo ngày.
•	Thống kê báo cáo món thêm theo ngày.
•	Thống kê báo cáo doanh thu theo ngày.
2.3.3. Yêu cầu phi chức năng.
•	Giao diện: nhân viên bán hàng phải thường xuyên tiếp xúc với giao diện phần mềm để đặt đơn cho khách hàng. Do đó giao diện phần mềm cần được thiết kế đơn giản, màu sắc hài hoà để thuận tiện cho nhân viên thao tác.
•	Phân quyền: cần phải có sự phân quyền chặt chẽ giữa nhân viên bán hàng và quản lý cửa hàng để thuận tiện cho việc quản lý và kiểm soát dữ liệu một cách có tổ chức.
•	Xử lý: Tốc độ xử lý các tiến trình phải nhanh và ổn định.
2.3.4. Hệ thống các yêu cầu.
2.3.4.1. Bảng mô tả nghiệp vụ.
STT	Chức vụ	
1	Quản Lý Cửa Hàng.	Thực hiện theo dõi và thống kê hoạt động bán hàng tại cửa hàng như thống kê doanh thu, sản phẩm bán chạy, quản lý nhân viên, quản lý sản phẩm......
2	Nhân viên bán hàng.	Lập đơn hàng và xuất hóa đơn thanh toán cho khách.
Thống kê doanh thu theo ngày.
Pha chế, giữ vệ sinh cho cửa hàng.

2.3.4.2. Bảng yêu cầu nghiệp vụ.
STT	Tên yêu cầu	Biểu mẫu	Quy định	Chú thích
1	Quản lý hoạt động cửa hàng.			
2	Tiếp nhận thông tin nhân viên.	BM1.	QĐ1.	Lưu trữ thông tin nhân viên vào cơ sở dữ liệu.
3	Tra cứu thông tin nhân viên.			
4	Thống kê doanh thu theo mốc thời gian.	BM2.		
5	Thống kê mặt hàng bán chạy.	BM3.		
6	Lập hóa đơn bán hàng.	BM4.	QĐ2.	
7	Xuất hóa đơn bán hàng.			
8	Tra cứu hóa đơn bán hàng.			
9	Tra cứu thông tin sản phẩm.			
10	Tra cứu thông tin topping.			
11	Tra cứu thông tin thể loại sản phẩm.			
12	Thống kê món thêm bán chạy	BM5		

BM1

THÔNG TIN NHÂN VIÊN
Mã nhân viên
Họ và tên                                                                                     Ngày sinh
Địa chỉ                                                                                         Giới tính
Số điện thoại

=> QĐ1: Họ và tên nhân viên không được bỏ trống.








BM2

BÁO CÁO THỐNG KÊ SẢN PHẨM THEO MỐC THỜI GIAN 
Từ ngày……………….… đến ngày………………

STT	Mã sản phẩm	Tên sản phẩm	Size	Số lượng	Thể loại sản phẩm	Đơn giá	Doanh thu
1							
2							
3							
4							
…							
                                                                                                                                                       Tổng:                                           	
                                                                                                                  
                                                                                                              Người lập
                                                                                                       (Ký, ghi rõ họ tên)

BM3


BÁO CÁO SẢN PHẨM BÁN CHẠY
                                        Từ ngày……………….… đến ngày………………

STT	Mã sản phẩm	Tên sản phẩm	Số lượng	Đơn giá	Doanh thu
1					
2					
3					
4					
…					
                                                                                              Tổng:                                                                                                            	
                                                                                                                  
                                                                                                    Người lập
                                                                                               (Ký, ghi rõ họ tên)

BM4



HÓA ĐƠN BÁN HÀNG
                                
                                  Mã hóa đơn……………………………..
                          
                                  Ngày lập………………………………..

                                  Nhân viên………………………………

                                  Hình thức…………………………........ 

STT	Mã 	Tên	Số lượng 	Giá	Thành tiền
1					
2					
3					
4					
…					
                                                                                                                  
Tổng tiền(VNĐ)……………………….

Tiền nhận(VNĐ)……………………….

Tiền thối(VNĐ)………………………..

QĐ2: Hóa đơn phải có ít nhất một sản phẩm.







BM5

THỐNG KÊ MÓN THÊM BÁN CHẠY
                                        Từ ngày……………….… đến ngày………………

STT	Mã món thêm	Tên món thêm	Số lượng	Đơn giá	Doanh thu
1					
2					
3					
4					
...					
                                                                                              Tổng:                                                                                                            	
                                                                                                                  

                                                                                                    Người lập
                                                                                               (Ký, ghi rõ họ tên)


2.3.4.3. Bảng trách nhiệm yêu cầu nghiệp vụ.
STT	Tên yêu cầu	Người dùng	Phần mềm	Chú thích
1	Quản lý cửa hàng.	Có thể tùy chọn sử dụng các chức năng sau: xem hóa đơn, xem thống kê thu nhập, quản lý nhân viên, sản phẩm và topping.	Hiển thị thông tin hóa đơn, thu chi sản phẩm và các xử lý liên quan đến nhân viên sản phẩm và topping.	Cho phép thao tác: thêm, sửa nhân viên, sản phẩm, topping, xóa nhân viên.
2	Tiếp nhận thông tin nhân viên.	Cung cấp thông tin theo BM1.	Kiểm tra thông tin, quy định và ghi nhận.	
3	Tra cứu thông tin nhân viên.	Cung cấp mã hoặc tên nhân viên.	Tìm và xuất thông tin của nhân viên.	Cho phép: xóa và sửa thông tin nhân viên.
4	Thống kê doanh thu theo mốc thời gian.	Cung cấp mốc thời gian muốn thống kê.	Thực hiện thống kê theo mốc thời gian cung cấp và hiển thị.	
5	Thống kê mặt hàng bán chạy.	Cung cấp khoảng thời gian muốn thống kê.	Thực hiện thống kê và hiển thị.	
6	Lập hóa đơn bán hàng.	Lựa chọn các sản phẩm muốn thanh toán.	Kiểm tra quy định và hiển thị các sản phẩm được lựa chọn theo BM5.	
7	Xuất hóa đơn bán hàng.	Chọn thao tác xuất hóa đơn.	Thực hiện xuất hóa đơn và lưu thông tin hóa đơn vào CSDL.	
8	Tra cứu hóa đơn bán hàng.	Cung cấp mã hóa đơn.	Thực hiện tìm kiếm mã hóa đơn và xuất thông tin hóa đơn.	
9	Tra cứu thông tin sản phẩm.	Cung cấp mã hoặc tên sản phẩm.	Tìm kiếm và xuất thông tin sản phẩm.	Cho phép sửa thông tin hoặc thay đổi trạng thái kinh doanh của sản phẩm.
10	Tra cứu thông tin topping.	Cung cấp mã hoặc tên topping.	Tìm kiếm và xuất thông tin topping.	Cho phép sửa thông tin hoặc thay đổi trạng thái kinh doanh của topping.

11	Tra cứu thông tin thể loại sản phẩm.	Cung cấp mã hoặc tên loại sản phẩm.	Tìm kiếm và xuất thông tin loại sản phẩm.	Cho phép thay đổi trạng thái kinh doanh của loại sản phẩm.


12	Thống kê món thêm bán chạy	Cung cấp mốc thời gian muốn thống kê	Thực hiện thống kê theo mốc thời gian cung cấp và hiển thị theo BM5.	
	
Yêu cầu chất lượng:
-	Tính chính xác:
Các chức năng của hệ thống phải thực hiện đúng với yêu cầu của người dùng. Kiểm tra thông tin mà người dùng nhập vào có hợp lệ hay không. Lưu trữ và phân bố dữ liệu trong cơ sở dữ liệu phải thật chính xác. Trích xuất dữ liệu đúng với yêu cầu của người dùng. Khả năng xử lý, lưu trữ và trích xuất dữ liệu phải diễn ra nhanh chóng và chính xác.
-	Tính tiện dụng:
Các chức năng của phần mềm phải dễ học, dễ sử dụng để rút ngắn thời gian học cách sử dụng đối với một số người dùng còn ít kinh nghiệm trong việc tiếp xúc và thao tác với phần mềm. Giao diện phải sử dụng các hình ảnh mang tính đặc trưng cho từng chức năng để người dùng có thể dễ dàng ghi nhớ.
-	Tính an toàn:
Cho phép người dùng như quản lý có thể chỉnh sửa thông tin lỗi do nhập sai hoặc thay đổi trạng thái kinh doanh của sản phẩm, thể loại sản phẩm và topping.
VD: Quản lý có thể thay đổi thông tin của sản phẩm nếu thông tin bị sai.
-	Tính hiệu quả:
Hệ thống giúp cho nhân viên thực hiện các nghiệp vụ một cách nhanh chóng và đạt hiệu quả cao hơn.
-	Tính bảo mật:
STT	Nghiệp vụ	Quản lý	Nhân viên bán hàng
1	Phân quyền	x	
2	Tìm kiếm, thêm, xóa , sửa tài khoản	x	
3	Tra cứu nhân viên	x	
4	Lập hóa đơn bán hàng	x	x
5	Xuất hóa đơn	x	x
6	Thêm, sửa, tìm kiếm sản phẩm	x	
7	Thống kê báo cáo	x	x
8	Tìm kiếm, thêm, sửa thể loại sản phẩm	x	
9	Tìm kiếm, thêm, sửa topping	x	

Hệ thống chỉ cho phép nguời dùng thực hiện các chức năng tương ứng với quyền tài khoản mà họ đăng nhập.

-	Khả năng nâng cấp:
STT	Khả năng nâng cấp	Yêu cầu
1	Thêm vào nghiệp vụ mới	Thời gian cập nhật nhanh, không ảnh hưởng đến các chức năng nếu phát sinh lỗi.
Phải đồng bộ với các nghiệp vụ trước đó.
2	Nâng cấp cơ sở dữ liệu	Import dữ liệu cũ nhanh chóng chính xác.
Không ảnh hưởng tốc độ tương tác với dữ liệu.

-	Yêu cầu hệ thống:
	Yêu cầu người dùng: Phải biết sử dụng cơ bản về hệ thống.
	Yêu cầu thiết bị: Phải có máy tính, máy in và máy chủ lưu dữ liệu.
-	Yêu cầu công nghệ:
STT	Yêu cầu	Mô tả chi tiết	Ghi chú
1	Dễ sửa lỗi	Xác định sửa lỗi trung bình trong 15 phút.	Khi sửa lỗi một chức năng không ảnh hưởng đến chức năng khác.
2	Dễ bảo trì	Thêm chức năng mới nhanh.	Không ảnh hưởng đến chức năng đã có.
3	Tái sử dụng	Có thể tái sử dụng xây dựng phần mềm quản lý bán hàng trong 5 ngày.	Cùng với các yêu cầu.
4	Dễ chuyển đổi	Chuyển đổi sang cơ sở dữ liệu mới tối đa 2 ngày.	Cùng với các yêu cầu.


2.3.5. BRD tổng quát.
2.3.5.1. Lịch sử cập nhật.
Ngày	Phiên bản	Thay đổi
04/04/2022	1.0	Khởi tạo.
05/04/2022	2.0	Chỉnh sửa.

2.3.5.2. Tóm tắt dự án.
a. Trạng thái hiện tại.
Hiện tại, cửa hàng cà phê “Coffee Shop” vẫn chưa được số hóa, mọi quy trình nghiệp vụ từ quản lý, bán hàng đến thống kê báo cáo đều phải tiến hành một cách thủ công. Do chưa có bất kì phần mềm nào hỗ trợ, nên cửa hàng gặp rất nhiều khó khăn trong việc quản lý, bán hàng, thanh toán đơn hàng cũng như thống kê theo ngày, theo tháng, theo năm.
b. Mục tiêu.
Từ những hiện trạng nêu trên, cửa hàng yêu cầu thiết kế, cài đặt riêng cho cửa hàng một phần mềm hỗ trợ cho những nghiệp vụ đặt ra. Với mục tiêu có thể dễ dàng hơn trong việc quản lý, bán hàng, thống kê báo cáo... Từ đó góp phần tăng doanh số, giúp cửa hàng ngày càng làm ăn thuận lợi.
Ngoài ra, việc thống kê bằng hệ thống có tính chính xác cao còn giúp những người chủ của cửa hàng có thể quản lý doanh thu hiệu quả hơn, đồng thời vạch ra nhiều chiến lược kinh doanh trong tương lai.
2.3.5.3.  Phạm vi dự án.
a. Bên trong.
Khi nhận dự án, bên bộ phận triển khai chỉ cần quan tâm đến những phạm vi nghiệp vụ mà bên cửa hàng đề ra như sau:
•	Đăng nhập, đăng xuất.
•	Quản lý thể loại sản phẩm, sản phẩm, món thêm, đơn hàng, nhân viên, tài khoản đăng nhập.
•	Xử lý đơn hàng cho khách dùng tại bàn, xử lý đơn hàng cho khách dùng mang đi, thanh toán đơn hàng và xuất hóa đơn.
•	Thống kê báo cáo sản phẩm, món thêm, doanh thu theo giời gian.
b. Bên ngoài.
	Hiện tại cửa hàng chưa cần số hóa những phạm vi như sau:
•	Quản lý kho.
•	Thanh toán bằng các hình thức khác ngoài tiền mặt như ví điện thử, thẻ ngân hàng...
•	Bán hàng qua các ứng dụng điện tử như grap food, go food, beamin, foody...
2.3.5.4. Tổng quan các yêu cầu nghiệp vụ.
a. Yêu cầu chức năng.
•	Đăng nhập.
•	Đăng xuất.
•	Quản lý thể loại sản phẩm (tìm kiếm, thêm, sửa).
•	Quản lý sản phẩm (tìm kiếm, thêm, sửa).
•	Quản lý món thêm (tìm kiếm, thêm, sửa).
•	Quản lý đơn hàng (tìm kiếm, xóa, in).
•	Quản lý nhân viên (tìm kiếm, thêm, sửa, xóa).
•	Quản lý tài khoản đăng nhập (tìm kiếm, thêm, sửa, xóa).
•	Lập đơn hàng cho khách dùng tại bàn.
•	Lập đơn hàng cho khách đung mang về.
•	Thanh toán đơn hàng tại bàn và xuất hóa đơn.
•	Thống kê sản phẩm theo thời gian.
•	Thống kê món thêm theo thời gian.
•	Thống kê doanh thu theo thời gian.
b. Yêu cầu phi chức năng.
•	Giao diện đẹp mắt, dễ sử dụng.
•	Phân quyền chặt chẽ giữa nhân viên quản lý và nhân viên bán hàng.
•	Tốc độ xử lý nhanh và ổn định.
2.3.6.  BRD chi tiết.
2.3.6.1. BRD chức năng đăng nhập, đăng xuất.
a. Lịch sử cập nhật.
Ngày	Phiên bản	Mô tả
04/04/2022	1.0	Khởi tạo.
13/05/2022	2.0	Chỉnh sửa.

b. Lý do.
Nghiên cứu chức năng đăng nhập của một số hệ thống bán hàng, kết hợp với kỹ thuật khảo sát hiện trạng và thu thập yêu cầu của khách hàng.
•	Từ quá trình khảo sát hiện trạng tổ chức, nhận thấy hệ thống bao gồm hai phân hệ người dùng gồm nhân viên quản lý và nhân viên bán hàng.
•	Từ quá trình khảo sát hiện trạng nghiệp vụ và thu thập yêu cầu, nhận thấy mỗi phân hệ người dùng sẽ sử dụng những chức năng được phân quyền chặt chẽ. Ví dụ trong khi nhân viên bán hàng chỉ được sử dụng những chức năng như: đăng nhập, đăng xuất, bán hàng, thống kê sản phẩm, món thêm và doanh thu theo ngày. Thì nhân viên quản lý lại được sử dụng nhiều chức năng hơn như quản lý các loại danh mục (thể loại sản phẩm, sản phẩm, món thêm, nhân viên, hóa đơn, tài khoản đăng nhập) và có thể thực hiện được tất cả các chức năng của nhân viên bán hàng nhưng mở rộng hơn ở chức năng thống kê sản phẩm, món thêm và doanh thu sẽ được thực hiện trong khoảng thời gian bất kì (ngày, quý, tháng, năm...).
Từ những hiện trạng nêu trên, bắt buộc hệ thống cần phải có chức năng đăng nhập để các chức năng có thể được phân quyền một cách rõ ràng đối với từng phân hệ người dùng.
Bên cạnh chức năng đăng nhập thì bắt buộc phải có chức năng đăng xuất, để người dùng có thể đăng xuất khỏi hệ thống chức năng của mình và trở về giao diện đăng nhập khi kết thúc một quy trình nghiệp vụ.
c. Yêu cầu nghiệp vụ.
Đăng nhập vào hệ thống với username và password.
•	Nếu đăng nhập thành công sẽ hiển thị danh mục chức năng tương ứng với từng loại tài khoản của nhân viên.
•	Nếu đăng nhập thất bại thì hiển thị thông báo lỗi cụ thể ra màn hình đăng nhập.
	Khi đăng xuất sẽ trở về giao diện đăng nhập của chương trình.
d. Yêu cầu logic.
•	Username và password không được để trống.
•	Username có độ tài từ 6 đến 20 kí tự và không được chứa khoảng trắng.
•	Password có độ dài từ 7 đến 20 kí tự và không được chứa khoảng trắng.
•	Password không được hiển thị khi người dùng nhập vào.
2.3.6.2. BRD chức năng quản lý thể loại sản phẩm.
a. Lịch sử cập nhật.
Ngày	Phiên bản	Mô tả
04/04/2022	1.0	Khởi tạo

b. Lý do và trạng thái hiện tại.
Trạng thái: chưa được số hóa.
Nghiên cứu chức năng quản lý thể loại sản phẩm của các hệ thống bán hàng cùng với kỹ thuật khảo sát hiện trạng và thu thập yêu cầu của khách hàng, nhận thấy đây là chức năng dành riêng cho quản lý cửa hàng.
Từ quá trình khảo sát hiện trạng nghiệp vụ và thu thập yêu cầu, nhận thấy chức năng quản lý thể loại sản phẩm cần đáp ứng đủ các chức năng cơ bản sau: Thêm thể loại sản phẩm mới, tìm kiếm thể loại sản phẩm, chỉnh sửa thông tin thể loại sản phẩm.
c. Yêu cầu nghiệp vụ.
Về thao tác:
•	Cần đăng nhập vào hệ thống với tài khoản có phân quyền là quản lý.
•	Nếu tài khoản có phân quyền không phải là quản lý thì sẽ không hiển thị chức năng quản lý thể loại sản phẩm.
Về chức năng:
•	Với chức năng thêm thể loại sản phẩm mới: Quản lý có thể thêm nhiều loại sản phẩm, nhưng tại một thời điểm chỉ được kinh doanh tối đa 10 thể loại sản phẩm.
•	Với chức năng tìm kiếm thể loại sản phẩm: Quản lý có thể tìm kiếm thể loại sản phẩm theo tên hoặc mã của thể loại sản phẩm.
•	Với chức năng chỉnh sửa thông tin thể loại sản phẩm: Quản lý có thể thay đổi tên hoặc trạng thái kinh doanh của thể loại sản phẩm. 
•	Không thực hiện chức năng xóa thể loại sản phẩm, vì một thể loại sản phẩm gồm có rất nhiều sản phẩm. Nếu xóa một thể loại, thì bắt buộc phải xóa tất cả các sản phẩm thuộc thể loại này. Điều này sẽ gây khó khăn trong việc sau này nếu cửa hàng muốn kinh doanh lại các sản phẩm trong thể loại đó, thì phải nhập vào tất cả thông tin của từng sản phẩm, như vậy tốn rất nhiều thời gian và công sức. Cho nên nếu không muốn kinh doanh bất kì thể loại nào chỉ cần điều chỉnh trạng thái kinh doanh (Business) của thể loại đó về false. Thì thể loại và tất cả các sản phẩm liên quan đến thể loại đó sẽ bị ẩn đi trên giao diện bán hàng. Sau này nếu muốn kinh doanh lại chỉ cần điều chỉnh trạng thái kinh doanh về lại giá trị true. Thì thể loại và tất cả sản phẩm liên quan sẽ được hiển thị.
d. Yêu cầu logic.
•	Tên thể loại sản phẩm mới không được trùng với tên của các thể loại sản phẩm đã tồn tại.
•	Trường nhập tên thể loại sản phẩm không được bỏ trống.
•	Do giao diện bán hàng chỉ có thể hiển thị tối đa 10 thể loại sản phẩm cho người dùng thao tác. Nên tại một thời điểm, cửa hàng chỉ có thể kinh doanh tối đa 10 thể loại sản phẩm.
2.3.6.3. BRD chức năng quản lý sản phẩm.
a. Lịch sử cập nhật.
Ngày	Phiên bản	Mô tả
04/04/2022	1.0	Khởi tạo.

b. Lý do và trạng thái hiện tại.
Trạng thái: chưa được số hóa.
Nghiên cứu chức năng quản lý sản phẩm của các hệ thống bán hàng cùng với kỹ thuật khảo sát hiện trạng và thu thập yêu cầu của khách hàng, nhận thấy đây là chức năng dành riêng cho quản lý cửa hàng.
Từ quá trình khảo sát hiện trạng nghiệp vụ và thu thập yêu cầu, nhận thấy chức năng quản lý sản phẩm cần đáp ứng đủ các chức năng cơ bản sau: Thêm sản phẩm mới, tìm kiếm sản phẩm, chỉnh sửa thông tin sản phẩm.
c. Yêu cầu nghiệp vụ.
Về thao tác:
•	Cần đăng nhập vào hệ thống với tài khoản có phân quyền là quản lý.
•	Nếu tài khoản có phân quyền không phải là quản lý thì sẽ không hiển thị chức năng quản lý sản phẩm.
Về chức năng:
•	Với chức năng thêm sản phẩm mới: Quản lý có thể thêm nhiều sản phẩm mới để phục vụ mục đích kinh doanh.
•	 Với chức năng tìm kiếm sản phẩm: Quản lý có thể tìm kiếm sản phẩm theo tên, mã hoặc thể loại của sản phẩm.
•	 Với chức năng chỉnh sửa thông tin sản phẩm: Quản lý có thể thay đổi tên, trạng thái kinh doanh, trạng thái nóng/lạnh, số lượng size của sản phẩm, giá bán của mỗi size, các topping đi kèm với sản phẩm.
•	Không thực hiện chức năng xóa sản phẩm. Vì việc xóa một sản phẩm sẽ gây khó khăn trong việc sau này nếu cửa hàng muốn kinh doanh lại sản phẩm đó, thì phải nhập vào tất cả thông tin của sản phẩm, như vậy tốn rất nhiều thời gian và công sức. Cho nên nếu không muốn kinh doanh bất kì sản phẩm nào chỉ cần điều chỉnh trạng thái kinh doanh (Business) của tsản phẩm đó về false. Thì sản phẩm đó sẽ bị ẩn đi trên giao diện bán hàng. Sau này nếu muốn kinh doanh lại chỉ cần điều chỉnh trạng thái kinh doanh về lại giá trị true. Thì sản phẩm sẽ được hiển thị.
d. Yêu cầu logic.
•	Trường nhập tên sản phẩm không được bỏ trống.
•	Tên sản phẩm mới không được trùng với tên sản phẩm đã tồn tại.
•	Sản phẩm có thể uống nóng hoặc lạnh tùy vào từng sản phẩm.
•	Sản phẩm phải có ít nhất 1 size.
•	Giá sản phẩm phải lớn hơn 0.
•	Không được thay đổi thể loại sản phẩm của sản phẩm.
•	Mỗi sản phẩm có thể đi kèm với nhiều loại topping (món thêm).
2.3.6.4. BRD chức năng quản lý món thêm.
a. Lịch sử cập nhật.

Ngày	Phiên bản	Mô tả
04/04/2022	1.0	Khởi tạo

b. Lý do và trạng thái hiện tại.
Trạng thái: chưa được số hóa.
Nghiên cứu chức năng quản lý món thêm đi kèm sản phẩm của một số hệ thống bán cà phê, trà sữa, kết hợp với kỹ thuật khảo sát hiện trạng và thu thập yêu cầu của khách hàng.
Từ kết quả khảo sát nghiệp vụ và thu thập yêu cầu, nhận thấy chức năng quản lý món thêm chỉ dành cho nhân viên quản lý của cửa hàng. Việc quản lý các món thêm là quan trọng đối với một cửa hàng. Và việc này sẽ được giao cho nhân viên quản lý. Nhân viên quản lý sẽ quản lý các món thêm đã và đang kinh doanh trong cửa hàng.
Từ những điều trên, ta thấy hệ thống cần phải có chức năng quản lý món thêm để hoạt động kinh doanh của cửa hàng diễn ra một cách hiệu quả.
c. Yêu cầu nghiệp vụ.
Nhân viên quản lý đăng nhập vào hệ thống bằng username và password của mình.
Chọn chức năng quản lý món thêm và thực hiện các thao tác như thêm, sửa, tìm kiếm hoặc chỉ xem danh sách các món thêm.
Các thao tác được thực hiện trong chức năng này gồm có: 
•	Thêm: thêm một món thêm mới vào hệ thống.
•	Sửa (cập nhật): cập nhật thông tin món thêm khi quá trình nhập liệu có sai sót hoặc thông tin của món thêm đã thay đổi. Ẩn hoặc hiện món thêm (Hiện món thêm nếu đang kinh doanh, khi không còn kinh doanh món nào đó thì ẩn đi).
•	Tìm kiếm: Tìm kiếm thông tin món thêm có trong hệ thống.
d. Yêu cầu logic.
Khi thực hiện các thao tác thêm hoặc sửa: 
•	Tên món thêm không được để trống.
•	Tên món thêm không được trùng lặp.
•	Giá của món thêm không được để trống và phải lớn hơn hoặc bằng 0. 
2.3.6.5. BRD chức năng quản lý đơn hàng.
a. Lịch sử cập nhật.
Ngày	Phiên bản	Mô tả
04/04/2022	1.0	Khởi tạo
b.  Lý do và trạng thái hiện tại.
Trạng thái: chưa được số hóa.
Nghiên cứu chức năng quản lý đơn hàng của một số hệ thống bán cà phê, trà sữa... kết hợp với kỹ thuật khảo sát hiện trạng và thu thập yêu cầu của khách hàng.
Từ quá trình khảo sát hiện trạng nghiệp vụ và thu thập yêu cầu, nhận thấy chức năng quản lý đơn hàng cần đáp ứng đủ các chức năng cơ bản sau: Tìm kiếm đơn hàng, xóa đơn hàng, in đơn hàng.
c. Yêu cầu nghiệp vụ.
Về thao tác:
•	Cần đăng nhập vào hệ thống với tài khoản có phân quyền là quản lý.
•	Nếu tài khoản có phân quyền không phải là quản lý thì sẽ không hiển thị chức năng quản lý đơn hàng.
Về chức năng:
•	Tìm kiếm đơn hàng: Yêu cầu có thể tìm kiếm đơn hàng với mã đơn hàng, loại đơn hàng, id nhân viên lập đơn hàng hoặc ngày lập đơn hàng.
•	Xóa đơn hàng: Yêu cầu có thể xóa đơn hàng bất kỳ.
•	In đơn hàng: Yêu cầu có thể in đơn hàng trong quá trình thao tác.
2.3.6.6. BRD chức năng quản lý nhân viên.
a. Lịch sử cập nhật.
Ngày	Phiên bản	Mô tả
04/04/2022	1.0	Khởi tạo

b. Lý do và trạng thái hiện tại.
Trạng thái: chưa được số hóa.
Nghiên cứu chức năng quản lý nhân viên của một số hệ thống bán hàng, kết hợp với kỹ thuật khảo sát hiện trạng và thu thập yêu cầu của khách hàng:
Từ quá trình khảo sát hiện trạng tổ chức, nhận thấy hệ thống nhân viên bao gồm nhân viên quản lý và nhân viên bán hàng.
Từ kết quả khảo sát nghiệp vụ và thu thập yêu cầu, nhận thấy chức năng quản lý nhân viên chỉ dành cho nhân viên quản lý của cửa hàng. Việc quản lý nhân sự rất quan trọng đối với một cửa hàng. Và việc này sẽ được giao cho nhân viên quản lý. Nhân viên quản lý sẽ quản lý thông tin của chính mình và các nhân viên bán hàng (họ tên, sinh nhật, địa chỉ, số điện thoại, thông tin chức vụ).
Từ những điều trên, ta thấy hệ thống cần phải có chức năng quản lý nhân viên để có thể quản lý nhân sự một cách hiệu quả.
c. Yêu cầu nghiệp vụ.
Nhân viên quản lý đăng nhập vào hệ thống bằng username và password của mình.
Chọn chức năng quản lý nhân viên và thực hiện các thao tác như thêm, xóa, sửa, tìm kiếm hoặc chỉ xem danh sách nhân viên.
Các thao tác được thực hiện trong chức năng này gồm có: 
•	Thêm: thêm một nhân viên mới vào hệ thống.
•	Xóa: xóa nhân viên ra khỏi hệ thống.
•	Sửa (cập nhật): cập nhật thông tin nhân viên khi quá trình nhập liệu có sai sót hoặc thông tin của nhân viên đã thay đổi.
•	Tìm kiếm: Tìm kiếm thông tin nhân viên có trong hệ thống.
d. Yêu cầu logic.
Khi thực hiện các thao tác thêm hoặc sửa: 
•	Tên nhân viên không được để trống.
•	Thông tin chức vụ của nhân viên không được để trống.
•	Tuổi nhân viên phải lớn hơn hoặc bằng 16.
2.3.6.7. BRD chức năng quản lý tài khoản đăng nhập.
a. Lịch sử cập nhật.
Ngày	Phiên bản	Mô tả
04/04/2022	1.0	Khởi tạo.

b. Lý do và trạng thái hiện tại.
Trạng thái: chưa được số hóa.
Từ quá trình khảo sát hiện trạng nghiệp vụ và thu thập yêu cầu, nhận thấy chức năng quản lý tài khoản đăng nhập cần đáp ứng đủ các chức năng cơ bản sau: Thêm tài khoản mới, tìm kiếm tài khoản, chỉnh sửa thông tin tài khoản, xóa tài khoản.
c. Yêu cầu nghiệp vụ.
Nhân viên quản lý đăng nhập vào hệ thống bằng username và password của mình.
Chọn chức năng quản lý tài khoản đăng nhập và thực hiện các thao tác như thêm, xóa, sửa, tìm kiếm.
	Các thao tác được thực hiện trong chức năng này gồm có: 
•	Thêm: thêm một tài khoản đăng nhập mới vào hệ thống.
•	Xóa: xóa một tài khoản đăng nhập ra khỏi hệ thống.
•	Sửa (cập nhật): cập nhật thông tin tài khoản đăng nhập khi quá trình nhập liệu có sai sót hoặc muốn thay đổi thông tin của tài khoản đăng nhập.
•	Tìm kiếm: Tìm kiếm thông tin của tài khoản đăng nhập có trong hệ thống.
d. Yêu cầu logic.
•	Username và password không được để trống.
•	Username có độ tài từ 6 đến 20 kí tự và không được chứa khoảng trắng.
•	Password có độ dài từ 7 đến 20 kí tự và không được chứa khoảng trắng.
•	Password không được hiển thị khi người dùng nhập vào.
2.3.6.8. BRD chức năng bán hàng.
a. Lịch sử cập nhật.
Ngày	Phiên bản	Mô tả
04/04/2022	1.0	Khởi tạo

b. Trạng thái hiện tại.
Quy trình bán hàng chưa được số hóa, mọi công đoạn điều phải thực hiện một cách thủ công trên các biểu mẫu, sổ sách... 
c. Yêu cầu nghiệp vụ.
Cửa hàng cần xử lý hai loại đơn hàng: đơn hàng cho khách dùng tại bàn trong cửa hàng và đơn hàng cho khách dùng mang đi. Từ đó yêu cầu phải thiết kế ra chức năng xử lý đơn hàng có thể giải quyết được hai loại đơn hàng này.
Đối với chức năng xử lý đơn hàng cho khách dùng tại bàn: nhân viên tiến hành chọn bàn, sau đó chọn món và topping đi kèm. Tiếp đến nhân viên có thể tiến hành đặt đơn của bàn khác hoặc đặt đơn mang về. Và khi khách hàng của bàn nào dùng nước xong và yêu cầu thanh toán, thì nhân viên bấm vào bàn đó, thông tin đơn hàng sẽ hiện ra và nhân viên tiến hành thanh toán, xuất hóa đơn cho khách.
Đối với chức năng xử lý đơn hàng mang về: nhân viên không cần chọn bàn, chỉ cần chọn món và topping đi kèm. Sau đó thanh toán và xuất hóa đơn cho khách.
Như vậy, ta thấy trong chức năng xử lý đơn hàng cần có những chức năng như sau:
•	Lập đơn hàng cho khách dùng tại bàn.
•	Lập đơn hàng cho khách dùng mang đi.
•	Thanh toán đơn hàng tại bàn.
•	Xuất hóa đơn.
2.3.6.9. BRD chức năng thống kê.
a. Lịch sử cập nhật.
Ngày	Phiên bản	Mô tả
04/04/2022	1.0	Khởi tạo

b. Trạng thái hiện tại.
Quy trình thống kê chưa được số hóa, mọi công đoạn điều phải thực hiện một cách thủ công trên các biểu mẫu, sổ sách... 
c. Lý do.
Từ quá trình khảo sát hiện trạng và thu thập yêu cầu, cửa hàng mong muốn đạt được hiệu quả tối ưu trong quy trình thống kê (sản phẩm bán chạy, món thêm bán chạy, doanh thu) từ đó có những căn cứ chính xác hơn để lên những kế hoạch kinh doanh trong tương lai như nhập nhiều nguyên liệu của sản phẩm bán chạy, cắt giảm việc nhập những nguyên liệu của những sản phẩm không bán chạy, hay mở rộng quy mô kinh doanh... góp phần thúc đẩy tăng doanh thu cho cửa hàng.
Ngoài ra, trong quá trình khảo sát, nhận thấy nhân viên bán hàng chỉ được quyền thống kê báo cáo theo ngày. Trong khi đó, nhân viên quản lý có thể thống kê báo cáo trong bất kì khoảng thời gian nào (ngày, quý, tháng, năm...).
Từ những hiện trạng nêu trên, bắt buộc phải triển khai chức năng thống kê cho cửa hàng.
d. Yêu cầu nghiệp vụ.
Đối với chức năng thống kê cần phân ra làm 3 loại thống kê: Sản phẩm, món thêm và doanh thu. Nhân viên phải thực hiện được 3 loại thống kê trên để làm báo cáo thống kê.
•	Thống kê sản phẩm: thống kê các sản phẩm bán chạy theo sản phẩm và theo size.
•	Thống kê món thêm: thống kê các món thêm bán chạy.
•	Thống kê doanh thu: thống kê số lượng đơn hàng bán được và doanh thu chi tiết.
Chức năng cần phải có sự phân quyền chặt chẽ giữa quản lý và nhân viên bán hàng vì các lý do nêu trong mục 3.
Đồng thời khi thực hiện chức năng thống kê, yêu cầu phải có thêm chức năng in kết quả thống kê để làm báo cáo.
2.3.7. PRD.
2.3.7.1. PRD chức năng đăng nhập, đăng xuất.
a. Lịch sử cập nhật.
Ngày	Phiên bản	Mô tả
04/04/2022	1.0	Khởi tạo
13/05/2022	2.0	Chỉnh sửa

b. Tổng quan chức năng.
b.1. Chức năng đăng nhập.
Cho phép nhân viên đăng nhập vào hệ thống với username và password được cấp bởi quản lý cửa hàng.
•	Nếu đăng nhập thành công, hệ thống sẽ điều hướng đến màn hình hiển thị menu chức năng tương ứng với từng tài khoản của nhân viên (trên tài khoản này có chứa thông tin phân quyền).
•	Nếu đăng nhập thất bại, hệ thống sẽ hiển thị thông báo lỗi cụ thể ra màn hình đăng nhập.
b.2. Chức năng đăng xuất.
Khi người dùng muốn thoát khỏi phiên đăng nhập, thì thực hiện đăng xuất để trở về giao diện đăng nhập.
c. Workflow.





c.1. Workflow.
 
c.2. Mô tả workflow.
Bước 1: Bắt đầu.
Bước 2: Cho người dùng nhập username và password từ bàn phím. 
Bước 3: Kiểm tra tính hợp lệ của tài khoản đăng nhập. Một tài khoản là hợp lệ khi nó hội tụ đủ các điều kiện sau:
+ Username và password không được để trống.
+ Username có độ dài từ 6 đến 20 kí tự và không được chứa khoảng trắng.
+ Password có độ dài từ 7 đến 20 kí tự và không được chứa khoảng trắng.
+ Tài khoản đăng nhập tồn tại trong hệ thống.
Bước 4: Nếu tài khoản hợp lệ thì bỏ qua bước 5.
Bước 5: Thông báo lỗi và quay về bước 2.
Bước 6: Kiểm tra phân quyền từ tài khoản đăng nhập.
Bước 7: Hiển thị danh mục chức năng theo phân quyền tương ứng với nhân viên quản lý hoặc nhân viên bán hàng.
Bước 8: Kết thúc.
d. Giao diện thiết kế.
d.1. Giao diện đăng nhập.
 
Mô tả giao diện:
+ 1: Khung dành cho người dùng nhập username và password.
+ 2: Nút đăng nhập
Cách xử lý: Người dùng nhập đầy đủ username và password (1). Tiếp theo nhấn nút “Sign In” (2). Hệ thống sẽ kiểm tra đăng nhập và trả kết quả ra màn hình. Nếu đăng nhập thành công thì hệ thống sẽ kiểm tra phân quyền và hiển thị một trong hai giao diện menu bên dưới tùy vào phân quyền của tài khoản đăng nhập.
d.2. Giao diện danh mục hiển thị menu chức năng dành cho nhân viên quản lý.
 
Mô tả giao diện:
+ 1: Nút điều hướng đến giao diện quản lý thể loại sản phẩm.
+ 2: Nút điều hướng đến giao diện quản lý sản phẩm.
+ 3: Nút điều hướng đến giao diện quản lý món thêm.
+ 4: Nút điều hướng đến giao diện quản lý hóa đơn.
+ 5: Nút điều hướng đến giao diện quản lý nhân viên.
+ 6: Nút điều hướng đến giao diện quản lý tài  khoản đăng nhập.
+ 7: Nút điều hướng đến giao diện doanh thu.
+ 8: Nút điều hướng đến giao diện thống kê.
+ 9: Nút điều hướng đến giao diện bán hàng.
+ 10: Nút đăng xuất, điều hướng đến giao diện đăng nhập.
d.3. Giao diện danh mục hiển thị menu chức năng dành cho nhân viên bán hàng.
 
Mô tả giao diện:
+ 1: Nút điều hướng đến giao diện bán hàng.
+ 2: Nút điều hướng đến giao diện doanh thu.
+ 3: Nút điều hướng đến giao diện thống kê.
+ 4: Nút đăng xuất, điều hướng đến giao diện đăng nhập.
2.3.7.2. PRD chức năng quản lý thể loại sản phẩm.
a. Lịch sử cập nhật.
Ngày	Phiên bản	Mô tả
04/04/2022	1.0	Khởi tạo

b. Tổng quan chức năng.
Chức năng giúp quản lý thuận tiện trong việc quản lý các thể loại sản phẩm. 
b.1. Thêm thể loại sản phẩm.
Khi tiến hành thêm một thể loại sản phẩm, cần tuân thủ theo những logic như sau: 
•	Trường nhập tên thể loại sản phẩm không được bỏ trống.
•	Tên thể loại sản phẩm mới không được trùng với tên thể loại sản phẩm đã tồn tại.
Nếu thỏa cả 2 điều kiện trên sẽ tiến hành lưu và xuất thông báo thêm thành công. Ngược lại xuất thông báo thêm thất bại.
b.2. Tìm kiếm thể loại sản phẩm.
Nếu nhập đúng tên hoặc mã của thể loại sản phẩm hiện có, hệ thống sẽ hiển thị các thông tin của thể loại sản phẩm đó ra màn hình. Ngược lại, hệ thống sẽ xuất ra thông báo không tìm thấy thể loại sản phẩm này.
b.3. Chỉnh sửa thông tin thể loại sản phẩm.
Chỉnh sửa tên thể loại sản phẩm: Nếu tên mới không trùng với tên của các thể loại sản phẩm khác sẽ cho phép thay đổi và xuất thông báo sửa thành công. Ngược lại, không cho thay đổi và xuất thông báo sửa không thành công.
Chỉnh sửa trạng thái kinh doanh của thể loại sản phẩm: Cho phép thay đổi trạng thái kinh doanh của thể loại sản phẩm từ kinh doanh sang không kinh doanh và ngược lại. 
b.4. Quy định.
Do giao diện bán hàng tại một thời điểm chỉ có thể hiển thị tối đa 10 thể loại sản phẩm cho nhân viên thao tác. Nên đối với chức năng thêm thể loại sản phẩm và sửa thể loại sản phẩm thì tại cùng 1 thời điểm hệ thống chỉ cho phép kinh doanh tối đa 10 thể loại sản phẩm. Nếu quản lý muốn kinh doanh thêm thể loại sản phẩm khác trong khi có 10 thể loại sản phẩm đang được kinh doanh, người quản lý bắt buộc phải thay đổi trạng kinh doanh của một trong 10 thể loại sản phẩm đang kinh doanh thì mới được phép kinh doanh thể loại sản phẩm mới.
c. Workflow.
c.1. Workflow chức năng thêm thể loại sản phẩm mới.
 
Mô tả workflow:
Bước 1: Bắt đầu.
Bước 2: Cho người dùng nhập tên thể loại sản phẩm mới từ bàn phím. 
Bước 3: Kiểm tra tính hợp lệ của tên vừa nhập. Tên thể loại sản phẩm mới chỉ hợp lệ khi nó hội tụ đủ các điều kiện sau:
+ Tên thể loại sản phẩm mới không được để trống.
+ Tên thể loại sản phẩm mới không được trùng với tên thể loại sản phẩm đã tồn tại.
Bước 4: Nếu tên thể loại sản phẩm mới hợp lệ thì bỏ qua bước 5.
Bước 5: Thông báo lỗi và quay về bước 2.
Bước 6: Thêm thể loại sản phẩm vào cơ sở dữ liệu.
Bước 7: Thông báo thêm thể loại sản phẩm mới thành công.
Bước 8: Hiển thị thông tin thể loại sản phẩm thêm mới.
Bước 9: Kết thúc.
c.2. Workflow chức năng tìm kiếm thể loại sản phẩm.
 

Mô tả workflow:
Bước 1: Bắt đầu.
Bước 2: Cho người dùng nhập tên hoặc mã thể loại sản phẩm muốn tìm từ bàn phím. 
Bước 3: Tiến hành tìm kiếm trong cơ sở dữ liệu.
Bước 4: Nếu tìm được thì bỏ qua bước 5.
Bước 5: Thông báo không tìm thấy và đến bước 7.
Bước 6: Hiển thị thể loại sản phẩm tìm được.
Bước 7: Kết thúc.
c.3. Workflow chức năng chỉnh sửa thông tin thể loại sản phẩm.
 
Mô tả workflow:
Bước 1: Bắt đầu.
Bước 2: Cho người dùng nhập thông tin thể loại sản phẩm cần sửa từ bàn phím. 
Bước 3: Kiểm tra tính hợp lệ của thông tin vừa nhập. Thông tin thể loại sản phẩm chỉ hợp lệ khi nó thỏa điều kiện sau:
+ Tên thể loại sản phẩm không được trùng với tên thể loại sản phẩm đã tồn tại.
Bước 4: Nếu thông tin cần sửa của thể loại sản phẩm hợp lệ thì bỏ qua bước 5.
Bước 5: Thông báo lỗi và quay về bước 2.
Bước 6: Cập nhật thông tin của thể loại sản phẩm.
Bước 7: Thông báo sửa thông tin thành công.
Bước 8: Hiển thị thông tin thể loại sản phẩm chỉnh sửa.
Bước 9: Kết thúc.
d. Thiết kế giao diện quản lý thể loại sản phẩm.
 
Mô tả giao diện:
Khung số 1: Khung hiển thị danh sách thể loại sản phẩm.
Khung số 2: Gồm các trường nhập thông tin của thể loại sản phẩm khi thêm hoặc sửa thông tin thể loại sản phẩm và cũng là trường hiển thị thông tin thể loại sản phẩm khi ấn chọn một thể loại sản phẩm nào đó trên khung số 1.
+ ClassifyID: Trường hiển thị ID của thể loại sản phẩm (trường này hệ thống tự cấp, người dùng không nhập vào).
+ Name: Trường hiển thị tên thể loại sản phẩm.
+ Business: Nút thay đổi trạng thái kinh doanh của thể loại sản phẩm.
Khung số 3 gồm: Trường nhập tên, mã thể loại sản phẩm và nút tìm kiếm (nút Search) theo từ khóa đã nhập.
Khung số 4 (Nút Add): Nút thêm thể loại sản phẩm mới khi người dùng nhập vào trường tên của thể loại sản phẩm mới ở khung số 2.
Khung số 5 (Nút Edit): Nút lưu thông tin đã chỉnh sửa của thể loại sản phẩm khi người dùng chọn thể loại sản phẩm cần sửa ở khung số 1 và thay đổi tên thể loại sản phẩm tại trường Name hoặc thay đổi trạng thái kinh doanh ở khung số 2.
Khung số 6 (Nút home): Nút quay về giao diện menu chọn chức năng của nhân viên quản lý.
2.3.7.3. PRD chức năng quản lý sản phẩm.
a. Lịch sử cập nhật.
Ngày	Phiên bản	Mô tả
04/04/2022	1.0	Khởi tạo

b. Tổng quan chức năng.
Giúp quản lý thuận tiện trong việc quản lý các sản phẩm.
b.1. Chức năng thêm sản phẩm mới.
Khi tiến hành thêm mới một sản phẩm vào hệ thống, cần thỏa các điều kiện sau:
•	Trường nhập tên sản phẩm không được bỏ trống.
•	Tên sản phẩm mới không được trùng với tên sản phẩm đã tồn tại.
•	Giá của sản phẩm phải lớn hơn 0.
•	Sản phẩm phải có ít nhất 1 size.
Nếu thỏa các điều kiện trên sẽ tiến hành lưu và xuất thông báo thêm thành công. Ngược lại xuất thông báo thêm thất bại.
Ngoài ra, cần phải quan tâm đến những điều sau:
•	Sản phẩm có thể uống nóng, lạnh hoặc cả hai tùy vào từng sản phẩm.
•	Sản phẩm có thể đi kèm với nhiều loại topping.
b.2. Chức năng tìm kiếm sản phẩm.
Nếu nhập đúng tên, mã hoặc thể loại của sản phẩm hiện có, hệ thống sẽ hiển thị các thông tin của sản phẩm đó ra màn hình. Ngược lại, hệ thống sẽ xuất ra thông báo không tìm thấy sản phẩm này.
b.3. Chức năng chỉnh sửa thông tin sản phẩm.
•	Chỉnh sửa tên sản phẩm: Nếu tên mới không trùng với tên của các sản phẩm khác sẽ cho phép thay đổi và xuất thông báo sửa thành công. Ngược lại, không cho thay đổi và xuất thông báo sửa không thành công.
•	Chỉnh sửa trạng thái kinh doanh của sản phẩm: Cho phép thay đổi trạng thái kinh doanh của sản phẩm từ kinh doanh sang không kinh doanh và ngược lại.
•	Chỉnh sửa giá theo từng size của sản phẩm: Mỗi sản phẩm phải có ít nhất 1 size. Cho phép thay đổi giá của size nếu giá là một số dương. Nếu không thỏa các điều kiện trên thì không cho thay đổi và xuất thông báo lỗi. 
•	Chính sửa trạng tháng nóng/lạnh của sản phẩm: Cho phép thay đổi trạng thái nóng/lạnh của sản phẩm. Có thể dùng nóng, dùng lạnh hoặc cả hai.
•	Chỉnh sửa topping đi kèm sản phẩm: Mỗi sản phẩm có thể có nhiều loại topping đi kèm. Người thao tác có thể điều chỉnh ràng buộc này.
c. Workflow.
c.1. Workflow chức năng thêm sản phẩm mới.
 
Mô tả workflow:
Bước 1: Bắt đầu.
Bước 2: Cho người dùng nhập thông tin sản phẩm mới từ bàn phím. 
Bước 3: Kiểm tra tính hợp lệ của thông tin vừa nhập. Thông tin sản phẩm mới chỉ hợp lệ khi nó hội tụ đủ các điều kiện sau:
+ Trường nhập tên sản phẩm không được để trống.
+ Tên sản phẩm mới không được trùng với tên sản phẩm đã tồn tại.
+ Phải có ít nhất 1 size.
+ Giá phải lớn hơn 0.
Bước 4: Nếu thông tin sản phẩm mới hợp lệ thì bỏ qua bước 5.
Bước 5: Thông báo lỗi và quay về bước 2.
Bước 6: Thêm sản phẩm vào cơ sở dữ liệu.
Bước 7: Thông báo sản phẩm mới thành công.
Bước 8: Hiển thị thồn tin sản phẩm thêm mới.
Bước 9: Kết thúc.
c.2. Workflow chức năng tìm kiếm sản phẩm.
 
Mô tả workflow:
Bước 1: Bắt đầu.
Bước 2: Cho người dùng nhập tên, mã hoặc thể loại của sản phẩm muốn tìm từ bàn phím. 
Bước 3: Tiến hành tìm kiếm trong cơ sở dữ liệu.
Bước 4: Nếu tìm được thì bỏ qua bước 5.
Bước 5: Thông báo không tìm thấy và đến bước 7.
Bước 6: Hiển thị sản phẩm tìm được.
Bước 7: Kết thúc.
c.3. Workflow chức năng chỉnh sửa thông tin sản phẩm.
 
Mô tả workflow:
Bước 1: Bắt đầu.
Bước 2: Cho người dùng nhập thông tin sản phẩm cần sửa từ bàn phím. 
Bước 3: Kiểm tra tính hợp lệ của thông tin vừa nhập. Thông tin sản phẩm chỉ hợp lệ khi nó thỏa điều kiện sau:
+ Tên sản phẩm không được trùng với tên sản phẩm đã tồn tại.
+ Sản phẩm phải có ít nhất 1 size.
+ Giá phải lớn hơn 0.
Bước 4: Nếu thông tin cần sửa của sản phẩm hợp lệ thì bỏ qua bước 5.
Bước 5: Thông báo lỗi và quay về bước 2.
Bước 6: Cập nhật thông tin của sản phẩm.
Bước 7: Thông báo sửa thông tin thành công.
Bước 8: Hiển thị thông tin sản phẩm chỉnh sửa.
Bước 9: Kết thúc.
d. Thết kế giao diện quản lý sản phẩm.
 
Mô tả giao diện:
Khung số 1: Khung hiển thị danh sách sản phẩm.
Khung số 2: Gồm các trường nhập thông tin của sản phẩm khi thêm hoặc sửa thông tin sản phẩm và cũng là trường hiển thị thông tin sản phẩm khi ấn chọn một sản phẩm (hàng) nào đó trên khung số 1.
+ Classify: Trường nhập tên thể loại sản phẩm của sản phẩm.
+ ID: Trường hiển thị ID của sản phẩm (Trường này hệ thống tự cấp dựa trên classify của sản phẩm).
+ Name: Trường nhập tên sản phẩm.
+ NickName: Trường nhập tên tóm tắt của sản phẩm để hiển thị ra màn hình bán hàng.
+ S, M, L: Trường nhập giá của sản phẩm theo các size S, M, L. Nếu sản phẩm không kinh doanh size nào thì không nhập giá của size đó.
+ Status: Trường chọn trạng thái nóng/lạnh đi kèm sản phẩm.
			+ Business: Trường chọn trạng thái kinh doanh của sản phẩm.
Khung số 3 (Nút Topping): Khi chọn nút này, giao diện chọn món thêm đi kèm sản phẩm sẽ được hiển thị như bên dưới, sau đó nhân viên quản lý chỉ cần chọn các loại topping phù hợp đi kèm sản phẩm và nhấn nút “OK”.
 
Khung số 4 gồm: Trường nhập tên, mã hoặc tên thể loại của sản phẩm và nút tìm kiếm (nút Search) theo từ khóa đã nhập.
Khung số 5 (nút Add): Nút thêm sản phẩm mới khi người dùng nhập đầy đủ các trường thông tin của sản phẩm mới ở khung số 2.
Khung số 6 (nút Edit): Nút lưu thông tin đã chỉnh sửa của sản phẩm khi người dùng chọn sản phẩm cần sửa ở khung số 1 và thay đổi thông tin sản phẩm tại các trường hiển thị, thay đổi trạng thái kinh doanh hoặc chỉnh sửa món thêm (Topping) đi kèm ở khung số 2.
Khung số 7 (nút Home): Nút quay về giao diện menu chọn chức năng của nhân viên quản lý.
2.3.7.4. PRD chức năng quản lý món thêm.
a. Lịch sử cập nhật.
Ngày	Phiên bản	Mô tả
04/04/2022	1.0	Khởi tạo

b. Tổng quan chức năng.
Nhân viên quản lý đăng nhập vào hệ thống với username và password được cấp.
Sau đó lựa chọn chức năng quản lý món thêm để thực hiện các thao tác như: tìm kiếm, thêm, sửa hoặc chỉ xem danh sách các nhân viên trong cửa hàng.
c. Workflow.
c.1. Workflow thêm món thêm.
 
Mô tả workflow:
Bước 1: Bắt đầu.
Bước 2: Người dùng nhập thông tin món thêm mới từ bàn phím (hệ thống sẽ tự cấp id cho món thêm).
Bước 3: Kiểm tra tính hợp lệ của thông tin vừa nhập. Thông tin món thêm mới chỉ hợp lệ khi hội tụ đủ các điều kiện sau:
+ Tên món thêm không được để trống.
+ Tên món thêm không được trùng lặp.
+ Giá món thêm không được để trống và phải lớn hơn hoặc bằng 0.
Bước 4: Nếu thông tin món thêm mới hợp lệ thì bỏ qua bước 5.
Bước 5: Thông báo lỗi và quay về bước 2.
Bước 6: Thêm món thêm mới vào cơ sở dữ liệu.
Bước 7: Thông báo thêm thành công.
Bước 8: Hiển thị danh sách món thêm vừa được cập nhật.
Bước 9: Kết thúc.








c.2. Workflow sửa món thêm.
 
Mô tả workflow:
Bước 1: Bắt đầu.
Bước 2: Người dùng nhập thông tin món thêm muốn sửa từ bàn phím. 
Bước 3: Kiểm tra tính hợp lệ của thông tin vừa nhập. Thông tin món thêm chỉ hợp lệ khi hội tụ đủ các điều kiện sau:
+ Tên món thêm không được để trống.
+ Tên món thêm không được trùng lặp.
+ Giá món thêm không được để trống phải lớn hơn hoặc bằng 0.
Bước 4: Nếu thông tin món thêm hợp lệ thì bỏ qua bước 5.
Bước 5: Thông báo lỗi và quay về bước 2.
Bước 6: Cập nhật món thêm vừa sửa vào cơ sở dữ liệu.
Bước 7: Thông báo sửa thành công.
Bước 8: Hiển thị danh sách món thêm vừa được cập nhật.
Bước 9: Kết thúc.
c.3. Workflow tìm kiếm món thêm.
 
Mô tả workflow:
Bước 1: Bắt đầu.
Bước 2: Cho người dùng nhập mã (ID) hoặc tên (NAME) món thêm muốn tìm từ bàn phím. 
Bước 3: Tiến hành tìm kiếm trong cơ sở dữ liệu.
Bước 4: Nếu tìm được thì bỏ qua bước 5.
Bước 5: Thông báo không tìm thấy rồi đến bước 7.
Bước 6: Hiển thị thông tin món thêm tìm được.
Bước 7: Kết thúc.
d. Giao diện quản lý món thêm.
d.1. Giao diện.
 
d.2. Mô tả giao diện.
Khung số 1:
Gồm có bảng hiển thị danh sách món thêm trong cửa hàng với các thông tin như ID (mã món thêm), NAME (tên món thêm), PRICE (giá món thêm). 
Khung số 2: 
Là khung INFO (thông tin) bao gồm các ô nhập liệu dùng để thêm hoặc để chỉnh sửa thông tin của món thêm và 2 checkbox để thể hiện trạng thái kinh doanh của món thêm (Trạng thái là “On” khi cửa hàng đang kinh doanh món thêm này, ngược lại là “Off”). Lưu ý, ô ID sẽ được tạo tự động và không cho phép chỉnh sửa trên ô này. Ngoài ra, ô NAME, PRICE không được để trống và ô PRICE phải nhập giá trị lớn hơn hoặc bằng 0.
Khung số 3:
Đây là khung tìm kiếm, khi danh sách món thêm quá dài và không thể tra cứu thủ công chính xác, quản lý có thể sử dụng chức năng này để tra cứu thông tin của món thêm nhanh và chính xác hơn. 
Để sử dụng công cụ này, người quản lý nhập từ khóa (keyword) vào ô bên trái sau đó nhấn nút “Search” để tra cứu. Kết quả tra cứu sẽ hiển thị trên bảng ở khung số 1.
Khung số 4:
Đây là khung bao gồm các nút để thực hiện việc thêm, sửa món thêm.
Khi thêm món thêm: 
Bước 1: Nhập và tích đầy đủ thông tin món thêm vào các ô và checkbox ở khung số 2.
Bước 2: Nhấn nút “Add”.
Khi sửa thông tin của món thêm:
Bước 1: Nhấp chọn dòng món thêm cần sửa trên bảng ở khung số 1.
Bước 2: Thông tin của món thêm được chọn sẽ hiển thị qua các ô ở khung số 2. Quản lý chọn và sửa ô cần sửa.
Bước 3: Nhấn nút “Edit”.
2.3.7.5. PRD chức năng quản lý đơn hàng.
a. Lịch sử cập nhật.
Ngày	Phiên bản	Mô tả
04/04/2022	1.0	Khởi tạo

b. Tổng quan chức năng.
Nhân viên quản lý đăng nhập vào hệ thống. Sau đó lựa chọn chức năng quản lý đơn hàng để thực hiện các thao tác như: tìm kiếm, xóa, in hoặc chỉ xem danh sách các đơn hàng trong cửa hàng 
c. Workflow.
c.1. Workflow tìm kiếm đơn hàng.

 
Thuật toán xử lý:
Bước 1: Bắt đầu.
Bước 2: Nhập thông tin đơn hàng cần tìm như mã, loại, ngày lập, nhân viên lập đơn.
Bước 3: Tìm kiếm trong cơ sở dữ liệu dựa vào thông tin ở bước 2.
Bước 4: Nếu không tìm thấy thì thông báo không tìm thấy và chuyển đến bước 6.
Bước 5: Hiển thị thông tin đơn hàng tìm được.
Bước 6: Kết thúc.
c.2. Workflow xóa đơn hàng.
 

Thuật toán xử lý:
Bước 1: Bắt đầu.
Bước 2: Cung cấp thông tin đơn hàng cần xóa bằng cách chọn đơn hàng hiển thị trên giao diện.
Bước 3: Hệ thống hiển thị thông báo xác nhận xóa. Nếu xác nhận không xóa thì chuyển đến bước 6.
Bước 4: Xóa đơn hàng trong cơ sở dữ liệu.
Bước 5: Hiển thị danh sách đơn hàng sau khi xóa.
Bước 6: Kết thúc.
c.3. Workflow in đơn hàng.

 
Thuật toán xử lý:
Bước 1: Bắt đầu.
Bước 2: Cung cấp thông tin đơn hàng cần in bằng cách chọn đơn hàng hiển thị trên giao diện.
Bước 3: Hệ thống hiển thị thông báo xác nhận in. Nếu xác nhận không in thì chuyển đến bước 6.
Bước 4: Thực hiện in đơn hàng và xuất file excel.
Bước 6: Kết thúc.
d. Giao diện.
 
 	Mô tả giao diện:
Khung số 1: Gồm có bảng hiển thị danh sách đơn hàng.
Khung số 2: Ô để nhập thông tin tìm kiếm đơn hàng và nút search để tìm kiếm.
Khung số 3: Đây là khung bao gồm các nút để thực hiện việc in, xóa đơn hàng.
Khi xóa đơn hàng: 
Bước 1: Chọn đơn hàng muốn xóa từ bảng.
Bước 2: Nhấn nút “delete”.
Khi tìm kiếm đơn hàng: 
Bước 1: Nhập thông tin đơn hàng vào ô search.
Bước 2: Nhấn vào nút “tìm kiếm”.
Khi in đơn hàng
Bước 1: Chọn đơn hàng muốn in từ bảng.
Bước 2: Nhấn nút “in”.
2.3.7.6. PRD chức năng quản lý nhân viên.
a. Lịch sử cập nhật.
Ngày	Phiên bản	Mô tả
04/04/2022	1.0	Khởi tạo

b. Tổng quan chức năng.
Nhân viên quản lý đăng nhập vào hệ thống với username và password được cấp.
Sau đó lựa chọn chức năng quản lý nhân viên để thực hiện các thao tác như: tìm kiếm, thêm, sửa, xóa hoặc chỉ xem danh sách các nhân viên trong cửa hàng.
c. Workflow.
c.1. Workflow thêm nhân viên.
 
Mô tả workflow:
Bước 1: Bắt đầu.
Bước 2: Người dùng nhập thông tin nhân viên mới từ bàn phím (hệ thống sẽ tự cấp id cho nhân viên).
Bước 3: Kiểm tra tính hợp lệ của thông tin vừa nhập. Thông tin nhân viên mới chỉ hợp lệ khi hội tụ đủ các điều kiện sau:
+ Tất cả các trường họ tên, ngày sinh, địa chỉ, số điện thoại và thông tin chức vụ không được để trống.
+ Tuổi nhân viên phải lớn hơn hoặc bằng 16.
Bước 4: Nếu thông tin nhân viên mới hợp lệ thì bỏ qua bước 5.
Bước 5: Thông báo lỗi và quay về bước 2.
Bước 6: Thêm nhân viên mới vào cơ sở dữ liệu.
Bước 7: Thông báo thêm thành công.
Bước 8: Hiển thị danh sách nhân viên vừa được cập nhật.
Bước 9: Kết thúc.
c.2. Workflow sửa nhân viên.
 
Mô tả workflow:
Bước 1: Bắt đầu.
Bước 2: Người dùng nhập thông tin nhân viên muốn sửa từ bàn phím. 
Bước 3: Kiểm tra tính hợp lệ của thông tin vừa nhập. Thông tin nhân viên chỉ hợp lệ khi hội tụ đủ các điều kiện sau:
+ Tất cả các trường họ tên, ngày sinh, địa chỉ, số điện thoại và thông tin chức vụ không được để trống.
+ Tuổi nhân viên phải lớn hơn hoặc bằng 16.
Bước 4: Nếu thông tin nhân viên hợp lệ thì bỏ qua bước 5.
Bước 5: Thông báo lỗi và quay về bước 2.
Bước 6: Cập nhật nhân viên vừa sửa vào cơ sở dữ liệu.
Bước 7: Thông báo sửa thành công.
Bước 8: Hiển thị danh sách nhân viên vừa được cập nhật.
Bước 9: Kết thúc.
c.3. Workflow xóa nhân viên.
 
Mô tả workflow:
Bước 1: Bắt đầu.
Bước 2: Người dùng chọn nhân viên cần xóa bằng cách chọn dòng dữ liệu của nhân viên đó trên bảng hiển thị. 
Bước 3: Hệ thống hiển thị thông báo xác nhận xóa, nếu xác nhận không xóa thì chuyển đến bước 9.
Bước 4: Xóa nhân viên.
Bước 5: Cập nhật cơ sở dữ liệu.
Bước 6: Thông báo xóa nhân viên thành công.
Bước 7: Hiển thị danh sách nhân viên vừa được cập nhật.
Bước 8: Kết thúc.
c.4. Workflow tìm kiếm nhân viên.
 
Mô tả workflow:	
Bước 1: Bắt đầu.
Bước 2: Cho người dùng nhập mã nhân viên (ID), tên (NAME) hoặc vị trí/chức vụ (POSITION) muốn tìm từ bàn phím. 
Bước 3: Tiến hành tìm kiếm trong cơ sở dữ liệu.
Bước 4: Nếu tìm được thì bỏ qua bước 5.
Bước 5: Thông báo không tìm thấy rồi đến bước 7.
Bước 6: Hiển thị thông tin nhân viên tìm được.
Bước 7: Kết thúc.
d. Giao diện quản lý nhân viên.
d.1. Giao diện.
 
d.2. Mô tả giao diện.
Khung số 1:
Gồm có bảng hiển thị danh sách nhân viên trong cửa hàng với các thông tin như ID (mã nhân viên), NAME (họ tên nhân viên), BIRTHDAY (sinh nhật), ADDRESS (địa chỉ), PHONE (số điện thoại), POSITION (vị trí hay chức vụ). 
Khung số 2: 
Là khung INFO (thông tin) bao gồm các ô nhập liệu dùng để thêm hoặc để chỉnh sửa thông tin của nhân viên. Lưu ý, ô ID sẽ được tạo tự động và không cho phép chỉnh sửa trên ô này. Ngoài ra, ô NAME không được để trống. Các ô còn lại nhập bình thường nhưng lưu ý điều kiện về tuổi của nhân viên và định dạng của số điện thoại.
Khung số 3:
Đây là khung tìm kiếm, khi danh sách nhân viên quá dài và không thể tra cứu thủ công chính xác, quản lý có thể sử dụng chức năng này để tra cứu thông tin của một hoặc một nhóm nhân viên. 
Để sử dụng công cụ này, người quản lý nhập từ khóa (keyword) vào ô bên trái sau đó nhấn nút “Search” để tra cứu. Kết quả tra cứu sẽ hiển thị trên bảng ở khung số 1.
Khung số 4:
Đây là khung bao gồm các nút để thực hiện việc thêm, sửa, xóa nhân viên.
Khi thêm nhân viên: 
Bước 1: Nhập đầy đủ thông tin nhân viên vào các ô ở khung số 2.
Bước 2: Nhấn nút “Add”.
Khi sửa thông tin của nhân viên:
Bước 1: Nhấp chọn dòng nhân viên cần sửa trên bảng ở khung số 1.
Bước 2: Thông tin của nhân viên được chọn sẽ hiển thị qua các ô ở khung số 2. Quản lý chọn và sửa ô cần sửa.
Bước 3: Nhấn nút “Edit”.
Khi xóa nhân viên:
Bước 1: Nhấp chọn dòng nhân viên cần xóa trên bảng ở khung số 1.
		Bước 2: Nhấn nút “Delete”.
2.3.7.7. PRD chức năng quản lý tài khoản.
a. Lịch sử cập nhật.
Ngày	Phiên bản	Mô tả
04/04/2022	1.0	Khởi tạo

b. Tổng quan chức năng.
Quản lý cửa hàng đăng nhập vào hệ thống. Sau đó lựa chọn chức năng quản lý tài khoản để thực hiện các thao tác như: tìm kiếm, thêm, sửa, xóa.
c. Workflow.
c.1. Workflow tìm kiếm tài khoản.
 
Mô tả workflow:
Bước 1: Bắt đầu.
Bước 2: Cho người dùng nhập thông tin tài khoản muốn tìm từ bàn phím: username hoặc mã nhân viên. 
Bước 3: Tiến hành tìm kiếm trong cơ sở dữ liệu.
Bước 4: Nếu tìm được thì bỏ qua bước 5.
Bước 5: Thông báo không tìm thấy rồi đến bước 7.
Bước 6: Hiển thị thông tin đầy đủ của tài khoản tìm được.
Bước 7: Kết thúc.
c.2. Workflow sửa tài khoản.
 
Mô tả workflow:
Bước 1: Bắt đầu.
Bước 2: Người dùng nhập thông tin chỉnh sửa tài khoản. 
Bước 3: Kiểm tra tính hợp lệ của thông tin vừa nhập. 
Bước 4: Nếu thông tin tài khoản chỉnh sửa hợp lệ thì bỏ qua bước 5.
Bước 5: Thông báo lỗi và quay về bước 2.
Bước 6: Hệ thống cập nhật tài khoản chỉnh sửa vào database.
Bước 7: Thông báo sửa thành công.
Bước 8: Hiển thị thông tin tài khoản vừa chỉnh sửa.
           Bước 9: Kết thúc
c.3. Workflow xóa tài khoản.
 

Thuật toán xử lý:
Bước 1: Bắt đầu.
Bước 2: Cung cấp thông tin tài khoản cần xóa bằng cách chọn tài khoản hiển thị trên giao diện.
Bước 3: Hệ thống hiển thị thông báo xác nhận xóa. Nếu xác nhận không xóa thì chuyển đến bước 6.
Bước 4: Xóa tài khoản trong cơ sở dữ liệu.
Bước 5: Hiển thị danh sách tài khoản sau khi xóa.
Bước 6: Kết thúc.
c.4. Workflow thêm tài khoản.
 

Mô tả workflow:
Bước 1: Bắt đầu.
Bước 2: Cho người dùng nhập thông tin tài khoản mới từ bàn phím. 
Bước 3: Kiểm tra tính hợp lệ của thông tin vừa nhập.
Bước 4: Nếu hợp thì thì bỏ qua bước 5.
Bước 5: Thông báo lỗi và quay về bước 2.
Bước 6: Thêm tài khoản mới vào cơ sở dữ liệu.
Bước 7: Thông báo thêm tài khoản mới thành công.
Bước 8: Hiển thị danh sách tài khoản cập nhật.
Bước 9: Kết thúc.
d. Giao diện quản lý tài khoản.
 
Mô tả giao diện
Khung số 1: Bảng hiển thị danh sách tài khoản.
Khung số 2:  Bao gồm các ô nhập liệu dùng để thêm hoặc để chỉnh sửa thông tin của tài khoản.
Khung số 3: Bao gồm ô nhập thông tin tài khoản muốn tìm và nút search để tìm kiếm.
Khung số 4: Đây là khung bao gồm các nút để thực hiện việc thêm, sửa, xóa tài khoản.
Khi thêm tài khoản: 
Bước 1: Nhập đầy đủ thông tin tài khoản vào các ô ở khung số 2.
Bước 2: Nhấn nút “Add”.
Khi sửa thông tin của tài khoản:
Bước 1: Nhấp chọn dòng tài khoản cần sửa trên bảng ở khung số 1.
Bước 2: Thông tin của tài khoản được chọn sẽ hiển thị qua các ô ở khung	số 2. Quản lý chọn và sửa ô cần sửa.
Bước 3: Nhấn nút “Edit”.
Khi xóa tài khoản:
Bước 1: Nhấp chọn dòng tài khoản cần xóa trên bảng ở khung số 1.
Bước 2: Nhấn nút “Delete”.
2.3.7.8. PRD chức năng xứ lý đơn hàng.
a. Lịch sử cập nhật.
Ngày	Phiên bản	Mô tả
04/04/2022	1.0	Khởi tạo

b. Tổng quan chức năng.
Chức năng xử lý đơn hàng sẽ bao gồm các chức năng con như sau:
b.1. Lập đơn hàng.
b.1.1. Lập đơn hàng cho khách dùng tại bàn.
Khi khách hàng yêu cầu muốn dùng cà phê tại bàn trong cửa hàng, nhân viên bán hàng tiến hành chọn bàn cho khách thông qua ứng dụng, hệ thống sẽ khởi tạo thông tin của đơn hàng tại bàn, sau đó nhân viên chọn món và topping đi kèm dựa trên yêu cầu của khách. Hệ thống sẽ lưu đơn hàng tại bàn với trạng thái là chưa thanh toán vào cơ sở dữ liệu, đồng thời cập nhật lại trạng thái bàn là đã có đơn. Thông tin đơn hàng đã lập sẽ được lưu trên bàn tương ứng. Nếu muốn biết thông tin đơn hàng của bàn nào, chỉ cần chọn bàn đó, thông tin đơn hàng sẽ hiển thị.
b.1.2. Lập đơn hàng cho khách dùng mang về.
Khi khách hàng yêu cầu muốn mua cà phê mang về, nhân viên không cần chọn bàn cho khách, hệ thống khởi tạo đơn hàng mang về, nhân viên tiến hành chọn món và topping đi kèm. Sau đó phải thanh toán ngay để hệ thống lưu đơn hàng vào cơ sở dữ liệu, đồng thời xuất hóa đơn cho khách.
b.2. Thanh toán đơn hàng tại bàn.
Đối với đơn hàng cho khách dùng tại bàn, khi khách yêu cầu thanh toán, nhân viên bán hàng chọn bàn muốn thanh toán trên giao diện, thông tin đơn hàng của bàn đó sẽ được hiển thị, sau đó nhân viên tiến hành thanh toán đơn hàng cho khách. Sau khi thanh toán, hệ thống sẽ cập nhật lại trạng thái bàn của đơn hàng vừa thanh toán là bàn trống, có thể đặt đơn cho khách tiếp theo vào ngồi.
c. Workflow.
c.1. Workflow lập đơn hàng cho khách dùng tại bàn.

 
Thuật toán xử lý:
Bước 1: Bắt đầu.
Bước 2: Hệ thống khởi tạo đơn hàng.
Bước 3: Nhân viên chọn bàn, sản phẩm và món thêm đi kèm.
Bước 4: Hệ thống lưu đơn hàng tại bàn với trạng thái chưa thanh toán vào cơ sở dữ liệu.
Bước 5: Hệ thống cập nhật trạng thái bàn đã có đơn.
Bước 6: Hiển thị thông tin đơn hàng tại bàn ra giao diện.
Bước 7: Kết thúc.
c.2. Workflow lập đơn hàng cho khách dùng mang về.

 
Thuật toán xử lý:
Bước 1: Bắt đầu.
Bước 2: Hệ thống khởi tạo thông tin đơn hàng.
Bước 3: Nhân viên chọn sản phẩm và món thêm đi kèm.
Bước 4: Nhân viên tiến hành thanh toán đơn hàng.
Bước 5: Hệ thống lưu đơn hàng mang về vào cở sở dữ liệu.
Bước 6: Hệ thống hỏi có muốn xuất hóa đơn không? Nếu không thì đến bước 9.
Bước 7: In hóa đơn.
Bước 8: Xuất hóa đơn ra file excel.
Bước 9: Kết thúc.
c.3. Workflow thanh toán đơn hàng cho khách dùng tại bàn.
 
Thuật toán xử lý:
Bước 1: Bắt đầu.
Bước 2: Nhân viên chọn bàn muốn thanh toán.
Bước 3: Hệ thống hiển thị thông tin đơn hàng của bàn ra giao diện.
Bước 4: Xử lý thanh toán.
Bước 5: Cập nhật lại trạng thái bàn trống, sẵn sàng đặt đơn mới.
Bước 6: Hệ thống hỏi có muốn xuất hóa đơn không? Nếu không thì đến bước 9.
Bước 7: In hóa đơn.
Bước 8: Xuất hóa đơn ra excel.
Bước 9: Kết thúc.
d. Giao diện.
d.1. Chọn bàn.
 

Mô tả giao diện:
Số 1 (nút Table): Khi chọn nút này thì danh sách bàn sẽ hiện ra bên dưới.
Số 2 (nút Choose): Khi nhấn chọn vào nút Choose của bàn nào thì thồn tin của bàn đó sẽ hiện lên như khung số 3.
Khung số 3 là thông tin đơn hàng do hệ thống khởi tạo.
Nếu muốn biết thông tin đơn hàng của bàn nào, chỉ cần bấm chọn vào bàn đó, thông tin đơn hàng sẽ được hiển thị để nhân viên thao tác thêm, sửa, xóa món hay thanh toán đơn hàng.
d.2. Chọn món.

 

Mô tả giao diện: 
Số 1 (nút Tea): nút đại diện cho thể loại sản phẩm (các nút Coffee, Fruit Juice, Yogurt, Smoothie cũng tương tự). Khi bấm vào nút này tất cả các sản phẩm thuộc thể loại đó sẽ hiện ra tại khung số 2.
Số 3 (nút Payment): Nút thanh toán đơn hàng.
 

Mô tả giao diện:
Nút số 1 (nút Golden Pearl MT): Nút đại diện cho một món nước trong cửa hàng, khi nhấn vào nút này thì một giao diện khác sẽ hiện ra như khung số 2.
Khung số 2: Giao diện chọn thông tin của món nước vừa nhấn vào. Tại đây, nhân viên có thể chọn size, số lượng, giá, trạng/thái nóng lạnh và topping đi kèm sản phẩm sau đó nhấn nút “OK” ở khung số 3.
Khung số 3 (nút OK): Sau khi nhấn các thông tin của sản phẩm vừa chọn sẽ hiện ra ở khung số 4 bao gồm thông tin món nước, các món thêm đi kèm và đơn giá. Nếu muốn chỉnh sửa chỉ cần nhấn vào khung số 4, giao diện số 2 sẽ hiện ra cho nhân viên chỉnh sửa. Nếu muốn xóa chỉ cần nhấn nút “−“ bên cạnh.
Khung số 5: Khung hiển thị tổng giá của đơn hàng, thông tin tiền nhận và tiền trả khách.
2.3.7.9. PRD chức năng thống kê.
a. Lịch sử cập nhật.
Ngày	Phiên bản	Mô tả
04/04/2022	1.0	Khởi tạo

b. Tổng quan chức năng.
Đối với nhân viên bán hàng, khi tiến hành chọn một trong 3 chức năng thống kê bên dưới thì hệ thống sẽ tự động hiển thị kết quả thống kê của ngày hôm đó và không cho phép thay đổi thời gian thống kê. Ngược lại, nhân viên quản lý có quyền thay đổi khoảng thời gian thống kê bất kỳ để thực hiện quy trình thống kê theo quý, tháng, năm...
b.1. Thống kê sản phẩm theo thời gian.
Khi người dùng điều chỉnh thời gian thống kê, chức năng sẽ thực hiện việc thống kê sản phẩm bán chạy theo sản phẩm và theo size, sau đó hiển thị kết quả thống kê sản phẩm.
b.2. Thống kê món thêm theo thời gian.
Khi người dùng điều chỉnh thời gian thống kê, chức năng sẽ thực hiện việc thống kê món thêm, sau đó hiển thị bảng thống kê món thêm ra màn hình.
b.3. Thống kê doanh thu theo thời gian.
Khi người dùng điều chỉnh thời gian thống kê, chức năng sẽ thực hiện việc thống kê doanh thu, sau đó hiển thị kết quả thống kê doanh thu ra màn hình.
b.4. In kết quả thống kê.
Chức năng thực hiện việc in kết quả thống kê để làm báo cáo.
c. Workflow.
c.1. Workflow chức năng thống kê sản phẩm theo thời gian.
 
Thuật toán xử lý:
Bước 1: Bắt đầu.
Bước 2: Người dùng điều chỉnh thời gian thống kê.
Bước 3: Hệ thống thực hiện việc thống kê sản phẩm.
Bước 4: Trả kết quả thống kê sản phẩm cho người dùng.
Bước 5: Kết thúc.
c.2. Workflow chức năng thống kê món thêm theo thời gian.
 

Thuật toán xử lý:
Bước 1: Bắt đầu.
Bước 2: Người dùng điều chỉnh thời gian thống kê.
Bước 3: Hệ thống thực hiện việc thống kê món thêm.
Bước 4: Trả kết quả thống kê sản phẩm cho người dùng.
Bước 5: Kết thúc.
c.3. Workflow chức năng thống kê doanh thu theo thời gian.
 

Thuật toán xử lý:
Bước 1: Bắt đầu.
Bước 2: Người dùng điều chỉnh thời gian thống kê.
Bước 3: Hệ thống thực hiện việc thống kê doanh thu.
Bước 4: Trả kết quả thống kê sản phẩm cho người dùng.
Bước 5: Kết thúc.
c.4. Workflow chức năng in kết quả thống kê.
 

Thuật toán xử lý:
Bước 1: Bắt đầu.
Bước 2: Người dùng cung cấp thông tin kết quả thống kê muốn in.
Bước 3: Hệ thống thực hiện việc in thống kê.
Bước 4: Xuất bảng in thống kê ra excel.
Bước 5: Kết thúc.
d. Giao diện.
d.1. Giao diện thống kê sản phẩm và món thêm.
 

Mô tả giao diện:
Khung số 1: Bảng hiển thị kết quả thống kê sản phẩm.
Khung số 2: Khung chọn mốc thời gian thống kê gồm ngày, tháng, năm bắt đầu (Start) và ngày, tháng, năm kết thúc (Finish). Đối với nhân viên bán hàng thì khung này sẽ bị ẩn đi và không cho nhân viên điều chỉnh thời gian.
Khung số 3 gồm các nút: Product khi giao diện đang hiển thị kết quả thống kê món thêm, người dùng nhấn vào nút Product, hệ thống sẽ điều hướng đến giao diện thống kê sản phẩm và hiển thị kết quả thống kê sản phẩm. Ngược lại nếu nhấn nút Topping thì hệ thống sẽ điều hướng đến giao diện thống kê món thêm như bên dưới. Nút Print để in kết quả thống kê trên màn hình ra file excel.
 

Số 4 là ô tìm kiếm kết quả thống kê nếu danh sách thống kê trả về quá dài.
Số 5 (nút Search) là nút tìm kiếm kết quả thống kê.
Số 6 (nút Home) là nút điều hướng đến giao diện menu chọn chức năng.
d.2. Giao diện thống kê doanh thu theo thời gian.
 
Mô tả giao diện:
Khung số 1: Khung hiển thị kết quả thống kê các đơn hàng bán được dựa vào khoảng thời gian mà người dùng yêu cầu.
Khung số 2: Khung chọn mốc thời gian thống kê gồm ngày, tháng, năm bắt đầu (Start) và ngày, tháng, năm kết thúc (Finish). Đối với nhân viên bán hàng thì khung này sẽ bị ẩn đi và không cho nhân viên điều chỉnh thời gian.
Khung số 3: Khung hiển thị kết quả thống kê doanh thu gồm tổng số đơn hàng tại bàn, tổng số đơn hàng mang về, tổng số cả hai loại đơn hàng và tổng doanh thu.
Số 4 (nút Print): nút thực hiện chức năng in kết quả thống kê doanh thu trên màn hình ra excel.
Số 5 (nút Home): là nút điều hướng đến giao diện menu chọn chức năng.
 

CHƯƠNG 3: PHÂN TÍCH THIẾT KẾ
3.1. Phân tích, thiết kế các xử lý của hệ thống theo hướng chức năng.
3.1.1. Sơ đồ phân rã chức năng BFD.
 
3.1.2. DFD tổng quát từng chức năng.
3.1.2.1. Đăng nhập.
 
	Ý nghĩa từng dòng dữ liệu:
D1: Thông tin tài khoản đăng nhập.
D2: Danh mục chọn chức năng theo chức vụ.
D3: Danh sách tài khoản.
D4: Không có.
D5: D4.
D6: D5.
	Thuật toán xử lý:
Bước 1: Nhận D1 từ nhân viên quản lý hoặc nhân viên bán hàng.
Bước 2: Kiểm tra tính hợp lệ của D1.
Bước 3: Kết nối cơ sở dữ liệu.
Bước 4: Đọc D3 từ bộ nhớ phụ.
Bước 5: Kiểm tra D1 có tồn tại trong hệ thống.
Bước 6: Thông báo đăng nhập thành công hay thất bại tại D2. Nếu thành công thì hiển thị danh mục chọn chức năng tương ứng với vai trò của người dùng tại D2.
Bước 7: Đóng kết nối cơ sở dữ liệu.
Bước 8: Kết thúc
3.1.2.2. Quản lý thể loại sản phẩm.
a. Tìm kiếm thể loại sản phẩm.
 

	Ý nghĩa từng dòng dữ liệu:
D1: Thông tin về thể loại sản phẩm muốn tìm: Tên loại sản phẩm, mã loại sản phẩm.
D2: Không có.
D3: Danh sách kết quả tìm kiếm thể loại sản phẩm.
D4: Không cần.
D5: D2.
D6: D3.
	Thuật toán xử lý:
Bước 1: Kết nối cơ sở dữ liệu.
Bước 2: Đọc D3 từ bộ nhớ phụ.
Bước 3:  Nhận D1 từ nhân viên quản lý.
Bước 4: Tìm kiếm theo các tiêu chí D1, nhận danh sách các đối tượng tìm được từ D3.
Bước 5: Nếu thông tin tìm kiếm không có trong danh sách thì đến bước 7.
Bước 6: Thông báo phản hồi và hiển thị D6.
Bước 7: Đóng kết nối cơ sở dữ liệu.
Bước 8: Kết thúc.
b. Thêm thể loại sản phẩm.
 

	Ý nghĩa từng dòng dữ liệu:
D1: Thông tin về thể loại sản phẩm muốn thêm: mã thể loại sản phẩm, tên thể loại sản phẩm, trạng thái kinh doanh.
D2: Không có.
D3: Không có.
D4: D1.
D5: Không có.
D6: Danh sách thể loại sản phẩm.
	Thuật toán xử lý:
Bước 1: Kết nối cơ sở dữ liệu.
Bước 2: Nhận D1 từ nhân viên quản lý.
Bước 3: Kiểm tra D1 có hợp lệ không, nếu không hợp lệ xuống bước 5.
Bước 4: Nếu hợp lệ, lưu D4 xuống bộ nhớ phụ.
Bước 5: Thông báo thành công hoặc thất bại và hiển thị D6.
Bước 6: Đóng kết nối cơ sở dữ liệu.
Bước 7: Kết thúc.
c. Sửa thể loại sản phẩm.
 

	Ý nghĩa từng dòng dữ liệu:
D1: Thông tin về thể loại sản phẩm muốn sửa: Tên loại sản phẩm, trạng thái kinh doanh.
D2: Không có.
D3: Không có.
D4: D1.
D5: Không có.
D6: Thông báo sửa đổi thành công hay thất bại và xuất thông tin sửa đổi.
	Thuật toán xử lý:
Bước 1: Kết nối cơ sở dữ liệu.
Bước 2: Nhận D1 từ nhân viên quản lý.
Bước 3: Kiểm tra D1 có hợp lệ không, nếu không hợp lệ xuống bước 5.
Bước 4: Nếu hợp lệ, cập nhật D4 xuống bộ nhớ phụ.
Bước 5: Thông báo thành công hay thất bại và hiển thị kết quả D6.
Bước 6: Đóng kết nối cơ sở dữ liệu.
Bước 7: Kết thúc.
3.1.2.3. Quản lý sản phẩm.
a. Tìm kiếm sản phẩm.
 

	Ý nghĩa từng dòng dữ liệu:
D1: Thông tin về sản phẩm muốn tìm: Mã sản phẩm, tên sản phẩm, tên thể loại, mã thể loại.
D2: Không có.
D3: Danh sách sản phẩm tìm được.
D4: Không cần.
D5: D2.
D6: D3.
	Thuật toán xử lý:
Bước 1: Kết nối cở sở dữ liệu.
Bước 2: Đọc D3 từ bộ nhớ phụ.
Bước 3: Nhận D1 từ nhân viên quản lý.
Bước 4: Tìm kiếm theo các tiêu chí D1, nhận danh sách các đối tượng tìm được từ D3.
Bước 5: Nếu thông tin tìm kiếm không có trong danh sách thì đến bước 7.
Bước 6: Thông báo phản hồi và hiển thị D6.
Bước 7: Đóng cơ sở dữ liệu.
Bước 8: Kết thúc.
b. Thêm sản phẩm.
 

	Ý nghĩa từng dòng dữ liệu:
D1: Thông tin về sản phẩm muốn thêm: Mã thể loại sản phẩm, Tên sản phẩm, số lượng size, giá bán của mỗi size, trạng thái nóng/lạnh, trạng thái kinh doanh, topping đi kèm.
D2: Không có.
D3: Không có.
D4: D1.
D5: Không có.
D6: Danh sách sản phẩm.
	Thuật toán xử lý:
Bước 1: Kết nối cơ sở dữ liệu.
Bước 2:  Nhận D1 từ nhân viên quản lý.
Bước 3: Kiểm tra D1 có hợp lệ không, nếu không hợp lệ xuống bước 5.
Bước 4: Nếu hợp lệ, lưu D4 xuống bộ nhớ phụ.
Bước 5: Thông báo thành công hoặc thất bại và hiển thị D6.
Bước 6: Đóng kết nối cơ sở dữ liệu.
Bước 7: Kết thúc.
c. Sửa sản phẩm.
 
	Ý nghĩa từng dòng dữ liệu:
D1: Thông tin về sản phẩm muốn sửa: Tên sản phẩm, số lượng size, giá bán của mỗi size, trạng thái nóng/lạnh, trạng thái kinh doanh, topping đi kèm.
D2: Không có.
D3: Không có.
D4: D1.
D5: Không có.
D6: Thông báo chỉnh sửa thành công hay thất bại và xuất thông tin sửa đổi.
	Thuật toán xử lý:
Bước 1: Kết nối cơ sở dữ liệu.
Bước 2: Nhận D1 từ nhân viên quản lý.
Bước 3: Kiểm tra D1 có hợp lệ không, nếu không hợp lệ xuống bước 5.
Bước 4: Nếu hợp lệ, cập nhật D4 xuống bộ nhớ phụ.
Bước 5: Thông báo thành công hay thất bại và hiển thị kết quả D6.
Bước 6: Đóng cơ sở dữ liệu.
Bước 7: Kết thúc.
3.1.2.4. Quản lý món thêm.
a. Tìm kiếm món thêm.
 

	Ý nghĩa từng dòng dữ liệu:
		D1: Thông tin về món thêm muốn tìm kiếm: mã, tên món thêm.
		D2: Không có.
		D3: Danh sách món thêm tìm được.
		D4: Không cần.
		D5: Không có.
		D6: D3.
	Thuật toán xử lý:
		Bước 1: Kết nối cơ sở dữ liệu.
		Bước 2: Đọc D3 từ bộ nhớ phụ.
		Bước 3: Nhận D1 từ nhân viên quản lý.
		Bước 4: Nếu thông tin tìm kiếm không có trong danh sách thì đến bước 6.
		Bước 5: Tìm kiếm theo các tiêu chí D1, nhận được danh sách các đối tượng tìm được từ D3.
		Bước 6: Thông báo không tìm thấy hoặc hiển thị D6.
		Bước 7: Đóng kết nối cơ sở dữ liệu.
		Bước 8: Kết thúc.
b. Thêm món thêm.

	Ý nghĩa từng dòng dữ liệu:
		D1: Thông tin về món thêm muốn thêm: tên, giá và tình trạng kinh doanh của món thêm.
		D2: Không có.
		D3: D2.
		D4: D1.
		D5: Không có.
		D6: Danh sách món thêm.
	Thuật toán xử lý:
		Bước 1: Kết nối cơ sở dữ liệu.
		Bước 2: Nhận D1 từ nhân viên quản lý.
		Bước 3: Kiểm tra D1 có hợp lệ không, nếu không hợp lệ xuống bước 5.
		Bước 4: Nếu hợp lệ, lưu D4 xuống bộ nhớ phụ.
		Bước 5: Thông báo thành công hoặc thất bại và hiển thị D6.
		Bước 6: Đóng kết nối cơ sở dữ liệu.
	 Bước 7: Kết thúc.







c. Sửa món thêm.













	Ý nghĩa từng dòng dữ liệu:
		D1: Thông tin sửa món thêm: tên, giá và tình trạng kinh doanh của món thêm.
		D2: Không có.
		D3: Không có.
		D4: D1.
		D5: Không có.
		D6: Danh sách món thêm sau khi sửa.
	Thuật toán xử lý:
		Bước 1: Kết nối cở sở dữ liệu.
		Bước 2: Nhận D1 từ nhân viên quản lý.
		Bước 3: Kiểm tra D1 có hợp lệ không, nếu không hợp lệ xuống bước 5.
		Bước 4: Nếu hợp lệ, cập nhật D4 xuống bộ nhớ phụ.
		Bước 5: Thông báo thành công hoặc thất bại và hiển thị D6.
		Bước 6: Đóng kết nối cơ sở dữ liệu.
		Bước 7: Kết thúc.
3.1.2.5. Quản lý đơn hàng.
a. Tìm kiếm đơn hàng.
 

	Ý nghĩa từng dòng dữ liệu:
		D1: Thông tin về đơn hàng muốn tìm kiếm: mã đơn, ngày lập, loại đơn, nhân viên lập đơn.
		D2: Không có.
		D3: Danh sách đơn hàng tìm được.
		D4: Không cần.
		D5: Không có.
		D6: D3.
	Thuật toán xử lý:
		Bước 1: Kết nối cơ sở dữ liệu.
		Bước 2: Đọc D3 từ bộ nhớ phụ.
		Bước 3: Nhận D1 từ nhân viên quản lý.
		Bước 4: Nếu thông tin tìm kiếm không có trong danh sách thì đến bước 6.
		Bước 5: Tìm kiếm theo các tiêu chí D1, nhận được danh sách các đối tượng tìm được từ D3.
		Bước 6: Thông báo không tìm thấy hoặc hiển thị D6.
		Bước 7: Đóng kết nối cơ sở dữ liệu.
		Bước 8: Kết thúc.
b. Xóa đơn hàng.
 

	Ý nghĩa từng dòng dữ liệu:
		D1: Thông tin về đơn hàng muốn xóa.
		D2: Không có.
		D3: Không có.
		D4: Lệnh xóa đơn hàng dựa vào D1.
		D5: Không có.
		D6: Danh sách đơn hàng sau khi xóa.
	Thuật toán xử lý:
		Bước 1: Kết nối cơ sở dữ liệu.
		Bước 2: Nhận D1 từ nhân viên quản lý.
		Bước 3: Hiển thị thông báo xác nhận xóa. Nếu không xác nhận bỏ qua bước 4.
		Bước 4: Gửi D4 xuống bộ nhớ phụ để xóa đơn hàng.
		Bước 5: Thông báo thành công hoặc thất bại và hiển thị D6.
		Bước 6: Đóng kết nối cơ sở dữ liệu.
		Bước 7: Kết thúc.
c. In đơn hàng.
 

	Ý nghĩa từng dòng dữ liệu:
		D1: Thông tin về đơn hàng muốn in.
		D2: Không có.
		D3: Dữ liệu đơn hàng cần in.
		D4: Không có.
		D5: Đơn hàng xuất ra file excel.
		D6: Không có.
	Thuật toán xử lý:
		Bước 1: Kết nối cơ sở dữ liệu.
		Bước 2: Nhận D1 từ nhân viên quản lý.
		Bước 3: Hiển thị thông báo xác nhận in đơn hàng. Nếu không xác nhận bỏ qua bước 4.
		Bước 4: Lấy D3 từ bộ nhớ phụ lên (dựa vào thông tin D1) để in.
		Bước 5: Thông báo in thành công hay thất bại. Nếu thành công thì nhận đơn hàng đã in tại D5.
		Bước 6: Đóng kết nối cơ sở dữ liệu.
		Bước 7: Kết thúc.
3.1.2.6. Quản lý nhân viên.
a. Tìm kiếm nhân viên.
 

	Ý nghĩa từng dòng dữ liệu:
		D1: Thông tin về nhân viên muốn tìm kiếm: mã, tên, ngày tháng năm sinh, địa chỉ, số điện thoại, chức vụ.
		D2: Không có.
		D3: Danh sách nhân viên cần tìm.
		D4: Không cần.
		D5: Không có.
		D6: D3.
	Thuật toán xử lý:
		Bước 1: Kết nối cơ sở dữ liệu.
		Bước 2: Đọc D3 từ bộ nhớ phụ.
		Bước 3: Nhận D1 từ nhân viên quản lí.
		Bước 4: Tìm kiếm theo các tiêu chí D1, nhận được danh sách các đối tượng tìm được từ D3.
		Bước 5: Nếu thông tin tìm kiếm không có trong danh sách thì đến bước 7.
		Bước 6: Hiển thị danh sách nhân viên tìm được D6.
		Bước 7: Đóng kết nối cơ sở dữ liệu.
		Bước 8: Kết thúc.
b. Thêm nhân viên.













	Ý nghĩa từng dòng dữ liệu:
		D1: Thông tin về nhân viên muốn thêm: tên, ngày tháng năm sinh, địa chỉ, số điện thoại, chức vụ của nhân viên.
		D2: Không có.
		D3: Không có.
		D4: D1.
		D5: Không có.
		D6: Danh sách nhân viên.
	Thuật toán xử lý:
		Bước 1: Kết nối cở sở dữ liệu.
		Bước 2: Nhận D1 từ nhân viên quản lý.
		Bước 3: Kiểm tra D1 có hợp lệ không, nếu không hợp lệ xuống bước 5.
		Bước 4: Nếu hợp lệ, lưu D4 xuống bộ nhớ phụ.
		Bước 5: Thông báo thành công hoặc thất bại và hiển thị D6.
		Bước 6: Đóng kết nối cơ sở dữ liệu.
		Bước 7: Kết thúc.
c. Sửa nhân viên.
 
	Ý nghĩa từng dòng dữ liệu:
		D1: Thông tin cập nhật nhân viên: tên, ngày tháng năm sinh, địa chỉ, số điện thoại, vị trí công việc của nhân viên.
		D2: Không có.
		D3: Không có.
		D4: D1.
		D5: Không có.
		D6: Danh sách nhân viên sau khi cập nhật.
	Thuật toán xử lý:
		Bước 1: Kết nối dữ liệu.
		Bước 2: Nhận D1 từ nhân viên quản lý.
		Bước 3: Kiểm tra D1 có hợp lệ không, nếu không hợp lệ xuống bước 5.
		Bước 4: Nếu hợp lệ, cập nhật D4 xuống bộ nhớ phụ.
		Bước 5: Thông báo thành công hoặc thất bại và hiển thị D6.
		Bước 6: Đóng kết nối cơ sở dữ liệu.
		Bước 7: Kết thúc.

d. Xóa nhân viên.
 

	Ý nghĩa từng dòng dữ liệu:
		D1: Thông tin về nhân viên muốn xóa.
		D2: Không có.
		D3: Không có.
		D4: Lệnh xóa nhân viên dựa vào D1.
		D5: Không có.
		D6: Danh sách nhân viên sau khi xóa.
	Thuật toán xử lý:
		Bước 1: Kết nối cơ sở dữ liệu.
		Bước 2: Nhận D1 từ nhân viên quản lý.
		Bước 3: Hiển thị thông báo xác nhận xóa. Nếu không xác nhận bỏ qua bước 4.
		Bước 4: Gửi D4 xuống bộ nhớ phụ để xóa nhân viên.
		Bước 5: Thông báo thành công hoặc thất bại và hiển thị D6.
		Bước 6: Đóng kết nối cơ sở dữ liệu.
		Bước 7: Kết thúc.
3.1.2.7. Quản lý tài khoản đăng nhập.
a. Tìm kiếm tài khoản đăng nhập.
 

	Ý nghĩa từng dòng dữ liệu:
		D1: Thông tin về tài khoản muốn tìm kiếm: username, mã nhân viên.
		D2: Không có.
		D3: Danh sách tài khoản cần tìm.
		D4: Không cần.
		D5: Không có.
		D6: D3.
	Thuật toán xử lý:
		Bước 1: Kết nối cơ sở dữ liệu.
		Bước 2: Đọc D3 từ bộ nhớ phụ.
		Bước 3: Nhận D1 từ nhân viên quản lí.
		Bước 4: Tìm kiếm theo các tiêu chí D1, nhận được danh sách các đối tượng tìm được từ D3.
		Bước 5: Nếu thông tin tìm kiếm không có trong danh sách thì đến bước 7.
		Bước 6: Hiển thị danh sách tài khoản tìm được D6.
		Bước 7: Đóng kết nối cơ sở dữ liệu.
		Bước 8: Kết thúc.
b. Thêm tài khoản đăng nhập.
 

	Ý nghĩa từng dòng dữ liệu:
		D1: Thông tin về tài khoản muốn thêm: username, password, mã nhân viên.
		D2: Không có.
		D3: Không có.
		D4: D1.
		D5: Không có.
		D6: Danh sách tài khoản.
	Thuật toán xử lý:
		Bước 1: Kết nối cở sở dữ liệu.
		Bước 2: Nhận D1 từ nhân viên quản lý.
		Bước 3: Kiểm tra D1 có hợp lệ không, nếu không hợp lệ xuống bước 5.
		Bước 4: Nếu hợp lệ, lưu D4 xuống bộ nhớ phụ.
		Bước 5: Thông báo thành công hoặc thất bại và hiển thị D6.
		Bước 6: Đóng kết nối cơ sở dữ liệu.
		Bước 7: Kết thúc.
c. Sửa tài khoản đăng nhập.
 

	Ý nghĩa từng dòng dữ liệu:
		D1: Thông tin cập nhật tài khoản: username, password, mã nhân viên.
		D2: Không có.
		D3: Không có.
		D4: D1.
		D5: Không có.
		D6: Danh sách tài khoản sau khi cập nhật.
	Thuật toán xử lý:
		Bước 1: Kết nối dữ liệu.
		Bước 2: Nhận D1 từ nhân viên quản lý.
		Bước 3: Kiểm tra D1 có hợp lệ không, nếu không hợp lệ xuống bước 5.
		Bước 4: Nếu hợp lệ, cập nhật D4 xuống bộ nhớ phụ.
		Bước 5: Thông báo thành công hoặc thất bại và hiển thị D6.
		Bước 6: Đóng kết nối cơ sở dữ liệu.
		Bước 7: Kết thúc.
d. Xóa tài khoản đăng nhập.
 

	Ý nghĩa từng dòng dữ liệu:
		D1: Thông tin về tài khoản muốn xóa.
		D2: Không có.
		D3: Không có.
		D4: Lệnh xóa tài khoản dựa vào D1.
		D5: Không có.
		D6: Danh sách tài khoản sau khi xóa.
	Thuật toán xử lý:
		Bước 1: Kết nối cơ sở dữ liệu.
		Bước 2: Nhận D1 từ nhân viên quản lý.
		Bước 3: Hiển thị thông báo xác nhận xóa. Nếu không xác nhận bỏ qua bước 4.
		Bước 4: Gửi D4 xuống bộ nhớ phụ để xóa tài khoản.
		Bước 5: Thông báo thành công hoặc thất bại và hiển thị D6.
		Bước 6: Đóng kết nối cơ sở dữ liệu.
		Bước 7: Kết thúc.
3.1.2.8. Bán hàng.
a. Lập đơn hàng.
a.1. Lập đơn hàng cho khách dùng tại bàn.
 

	Ý nghĩa từng dòng dữ liệu:
D1: Thông tin đơn hàng tại bàn, thông tin bàn, thông tin sản phẩm và topping đi kèm.
D2: Không có.
D3: Không có.
D4: Thông tin đơn hàng tại bàn chưa thanh toán.
D5: Không có.
D6: Thông tin đơn hàng tại bàn chưa thanh toán.
	Thuật toán xử lý:
Bước 1: Kết nối cơ sở dữ liệu.
Bước 2: Nhận D1 từ người dùng.
Bước 3: Thực hiện lưu D4 vào bộ nhớ phụ.
Bước 4: Hiển thị thông tin D6.
Bước 6: Đóng kết nối cơ sở dữ liệu.
Bước 7: Kết thúc.
a.2. Lập đơn hàng cho khách dùng mang về.
 

	Ý nghĩa từng dòng dữ liệu:
D1: Thông tin đơn hàng mang vể, thông tin sản phẩm và topping đi kèm.
D2: Không có.
D3: Không có.
D4: Thông tin đơn hàng mang về.
D5: Hóa đơn bán hàng.
D6: Thông tin đơn hàng mang về.
	Thuật toán xử lý:
Bước 1: Kết nối cơ sở dữ liệu.
Bước 2: Nhận D1 từ người dùng.
Bước 3: Thực hiện lưu D4 vào bộ nhớ phụ.
Bước 4: Hiển thị thông tin D6.
Bước 5: Xuất hóa đơn bán hàng.
Bước 6: Đóng kết nối cơ sở dữ liệu.
Bước 7: Kết thúc.
b. Thanh toán đơn hàng tại bàn.
 

	Ý nghĩa từng dòng dữ liệu:
D1: Thông tin đơn hàng tại bàn muốn thanh toán
D2: Không có.
D3: Thông tin đơn hàng tại bàn chưa thanh toán.
D4: Thông tin đơn hàng tại bàn đã thanh toán.
D5: Hóa đơn bán hàng.
D6: Thông báo kết quả thanh toán.
	Thuật toán xử lý:
Bước 1: Kết nối cơ sở dữ liệu.
Bước 2: Nhận D1 từ người dùng.
Bước 3: Đọc D3 từ bộ nhớ phụ.
Bước 4: Cập nhật trạng thái D3 là đơn hàng tại bàn đã thanh toán.
Bước 5: Thực hiện lưu D4 vào bộ nhớ phụ.
Bước 6: Hiển thị kết quả thanh toán D6 và thông báo xác nhận in hóa đơn. Nếu xác nhận không in thì chuyển đến bước 6.
Bước 7: In D5 dựa trên đơn hàng đã thanh toán ra excel.
Bước 8: Đóng kết nối cơ sở dữ liệu.
Bước 9: Kết thúc.
3.1.2.9. Thống kê báo cáo.
a. Thống kê sản phẩm bán được theo thời gian.
 

	Ý nghĩa từng dòng dữ liệu:
D1: Thông tin yêu cầu thống kê sản phẩm: thời gian.
D2: Không có.
D3: Danh sách sản phẩm, hóa đơn bán hàng.
D4: Không có.
D5: Báo cáo thống kê sản phẩm ra excel.
D6: Báo cáo thống kê sản phẩm.
	Thuật toán xử lý:
Bước 1: Kết nối cơ sở dữ liệu.
Bước 2: Nhận D1 từ người dùng.
Bước 3: Lấy D3 từ bộ nhớ phụ.
Bước 4: Thực hiện thống kê.
Bước 5: Trả kết quả thống kê sản phẩm ra D6, đồng thời xuất file excel D5 (nếu yêu cầu).
Bước 6: Đóng kết nối cơ sở dữ liệu.
Bước 7: Kết thúc.
b. Thống kê món thêm bán được theo thời gian.
 

	Ý nghĩa từng dòng dữ liệu:
D1: Thông tin yêu cầu thống kê món thêm: thời gian.
D2: Không có.
D3: Danh sách món thêm, hóa đơn bán hàng.
D4: Không có.
D5: Báo cáo thống kê món thêm ra excel.
D6: Báo cáo thống kê món thêm.
	Thuật toán xử lý:
Bước 1: Kết nối cơ sở dữ liệu.
Bước 2: Nhận D1 từ người dùng.
Bước 3: Lấy D3 từ bộ nhớ phụ.
Bước 4: Thực hiện thống kê.
Bước 5: Trả kết quả thống kê món thêm ra D6, đồng thời xuất file excel D5 (nếu yêu cầu).
Bước 6: Đóng kết nối cơ sở dữ liệu.
Bước 7: Kết thúc.
c. Thống kê doanh thu theo thời gian.
 

	Ý nghĩa từng dòng dữ liệu:
D1: Thông tin yêu cầu thống kê doanh thu: thời gian.
D2: Không có.
D3: Danh sách hóa đơn bán hàng.
D4: Không có.
D5: Báo cáo thống kê doanh thu ra excel.
D6: Báo cáo thống kê doanh thu.
	Thuật toán xử lý:
Bước 1: Kết nối cơ sở dữ liệu.
Bước 2: Nhận D1 từ người dùng.
Bước 3: Lấy D3 từ bộ nhớ phụ.
Bước 4: Thực hiện thống kê.
Bước 5: Trả kết quả thống kê doanh thu ra D6, đồng thời xuất file excel D5 (nếu yêu cầu).
Bước 6: Đóng kết nối cơ sở dữ liệu.
Bước 7: Kết thúc.
3.1.3. DFD các mức ngữ cảnh, 0, 1, 2, 3.
a. Mức ngữ cảnh.
 
b. Mức 0.
 
c. Mức 1, 2, 3
c.1. Phân rã của 1.0 (quản lý đăng nhập)
 



















c.2. Mức 1 phân rã của 2.0 (quản lý danh mục)
	Mức 1:
 



	Mức 2 phân rã của 2.1 (quản lý thể loại sản phẩm):
 







+ Mức 3 phân rã của 2.1.1 (tìm kiếm thể loại sản phẩm):
 

+ Mức 3 phân rã của 2.1.2 (thêm thể loại sản phẩm):
 
	



+ Mức 3 phân rã của 2.1.3 (sửa thể loại sản phẩm):
 
















	Mức 2 phân rã của 2.2 (quản lý sản phẩm):
 








	+ Mức 3 phân rã của 2.2.1 (tìm kiếm sản phẩm):
 
	+ Mức 3 phân rã của 2.2.2 (thêm sản phẩm):
 

	
+ Mức 3 phân rã của 2.2.3 (sửa sản phẩm):
 


















	Mức 2 phân rã của 2.3 (quản lý món thêm):
 








	+ Mức 3 phân rã của 2.3.1 (tìm kiếm món thêm):
 

	+ Mức 3 phân rã của 2.3.2 (thêm món thêm):
 
	

+ Mức 3 phân rã của 2.3.3 (sửa món thêm):
 
















	Mức 2 phân rã của 2.4 (quản lý nhân viên):
 



	+ Mức 3 phân rã của 2.4.1 (tìm kiếm nhân viên):
 

	+ Mức 3 phân rã của 2.4.2 (thêm nhân viên):
 

	+ Mức 3 phân rã của 2.4.3 (sửa nhân viên):
 

	+ Mức 3 phân rã của 2.4.4 (xóa nhân viên):
 



	Mức 2 phân rã của 2.5 (quản lý đơn hàng):
 









	+ Mức 3 phân rã của 2.5.1 (tìm kiếm đơn hàng):
 

	+ Mức 3 phân rã của 2.5.2 (xóa đơn hàng):
 




	+ Mức 3 phân rã của 2.5.3 (in đơn hàng):
 





















	Mức 2 phân rã của 2.6 (quản lý tài khoản đăng nhập):
 


	+ Mức 3 phân rã của 2.6.1 (tìm kiếm tài khoản):
 

	+ Mức 3 phân rã của 2.6.2 (thêm tài khoản):
 
	

+ Mức 3 phân rã của 2.6.3 (sửa tài khoản):
 
	+ Mức 3 phân rã của 2.6.4 (xóa tài khoản):
 

c.3. Mức 1 phân rã của 3.0 (thống kê báo cáo).
 












c.4. Phân rã của 4.0 (xử lý đơn hàng).
	Mức 1:
 

	Mức 2 phân rã của 4.1 (lập đơn hàng):
 






	Mức 2 phân rã của 4.2 (thanh toán đơn hàng):
 

3.2. Phân tích, thiết kế các xử lý của hệ thống theo hướng chức năng.
3.2.1. Use case.
3.2.1.1. Use case tổng quát.

 
3.2.1.2. Phân rã và đặc tả usecase.





a. Usecase đăng nhập.

 

Đặc tả usecase:
Tên usecase	Đăng nhập.
Tác nhân	Nhân viên quản lý, nhân viên bán hàng.
Tóm tắt	Usecase này bắt đầu khi các tác nhân cần đăng nhập vào hệ thống.
Điều kiện tiên quyết	Bắt buộc phải có tài khoản trong hệ thống và người dùng chưa đăng nhập vào hệ thống.
Kết quả	1.	Nếu thành công: thì đăng nhập vào hệ thống đúng với chức vụ của tác nhân đó.
2.	Nếu thất bại: thông báo lỗi và trở về giao diện đăng nhập.
Kịch bản chính	1.	Người dùng mở chương trình ứng dụng.
2.	Người dùng nhập username và password vào hệ thống.
3.	Nhấn nút đăng nhập.
4.	Hệ thống kiểm tra username và password có hợp lệ không.
5.	Nếu hợp lệ thì hiển thị menu chọn chức năng tương ứng với vai trò của người dùng.
Kịch bản phụ	Nếu trong dòng sự kiện chính, người dùng cung cấp vào hệ thống tài khoản không hợp lệ thì:
1.	Hệ thống thông báo lỗi cụ thể.
2.	Trở về giao diện đăng nhập.

b. Usecase đăng xuất.
 

Đặc tả usecase:
Tên usecase	Đăng xuất.
Tác nhân	Nhân viên quản lý, nhân viên bán hàng.
Tóm tắt	Usecase này bắt đầu khi các tác nhân muốn kết thúc phiên đăng nhập của mình và đăng xuất khỏi hệ thống.
Điều kiện tiên quyết	Đã đăng nhập vào hệ thống.
Kết quả	1.	Nếu người dùng xác nhận đăng xuất: thì hệ thống sẽ trở về giao diện đăng nhập.
2.	Nếu người dùng xác nhận không đăng xuất: thì không có thay đổi nào diễn ra và giữ nguyên phiên đăng nhập.
Kịch bản chính	1.	Người dùng nhấn chọn vào biểu tượng đăng xuất trên màn hình menu chọn chức năng.
2.	Hệ thống hiển thị hộp thoại hỏi người dùng có chắc chắn muốn đăng xuất hay không?
3.	Nếu có thì thoát khỏi phiên đăng nhập và trở về giao diện đăng nhập. Ngược lại không có thay đổi nào diễn ra.
Kịch bản phụ	Không có.






c. Usecase quản lý thể loại sản phẩm.

 

Đặc tả usecase:
Tên use case	Quản lý thể loại sản phẩm.
Tác nhân	Nhân viên quản lý.
Tóm tắt	Usecase bắt đầu khi nhân viên quản lý muốn thực hiện các chức năng quản lý thể loại sản phẩm của cửa hàng bao gồm các việc tìm kiếm, thêm, sửa thể loại sản phẩm.
Điều kiện tiên quyết	Nhân viên phải đăng nhập bằng tài khoản có phân quyền là quản lý.
Kết quả	1.	Nếu thành công: Thì dữ liệu được truy xuất hoặc cập nhật trong cơ sở dữ liệu.
2.	Nếu thất bại: Thông báo lỗi.
Kịch bản chính	1. Người dùng chọn chức năng quản lý thể loại sản phẩm.
2. Hệ thống hiển thị danh sách thể loại sản phẩm và các chức năng cho người dùng lựa chọn:
a.	Tìm kiếm thể loại sản phẩm.
b.	 Thêm thể loại sản phẩm.
c.	Sửa thể loại sản phẩm.
a)	Tìm kiếm thể loại sản phẩm:
- Người dùng nhập thông tin của thể loại sản phẩm cần tìm.
- Nhấn nút tìm kiếm trên giao diện.
- Hệ thống hiển thị thông tin đầy đủ của thể loại sản phẩm tìm được.
b)	Thêm thể loại sản phẩm:
- Hệ thống hiển thị form nhập thông tin thể loại sản phẩm. 
- Người dùng nhập thông tin thể loại sản phẩm mới và nhấn chọn nút thêm trên giao diện.
- Hệ thống kiểm tra tính hợp lệ của thể loại sản phẩm mới.
- Nếu hợp lệ thì hệ thống sẽ hiển thị thông báo xác nhận có chắc chắn muốn thêm thể loại sản phẩm mới này vào cơ sở dữ liệu hay không?
- Nếu có thì hệ thống sẽ lưu thể loại sản phẩm mới vào cơ sở dữ liệu.
- Hiển thị thông báo thêm thành công và hiển thị thông tin của thể loại sản phẩm mới ra màn hình.
c)	Sửa thể loại sản phẩm:
- Người dùng chọn thể loại sản phẩm cần sửa.
- Hệ thống hiển thị thông tin thể loại sản phẩm đã chọn lên màn hình.
- Người dùng tiến hành thay đổi thông tin của thể loại sản phẩm.
- Nhấn nút sửa trên giao diện.
- Hệ thống kiểm tra tính hợp lệ của thể loại sản phẩm vừa chỉnh sửa.
- Nếu hợp lệ thì thì hệ thống sẽ hiển thị thông báo xác nhận có chắc chắn muốn sửa thể loại sản phẩm này trong cơ sở dữ liệu hay không?
- Nếu có thì hệ thống sẽ lưu vào cơ sở dữ liệu.
- Thông báo sửa thành công và hiển thị thông tin thể loại sản phẩm vừa sửa lên màn hình. 
Kịch bản phụ	-	Trong luồng sự kiện chính ở chức năng thêm, sửa nếu:
+ Thông tin thể loại sản phẩm nhập vào không hợp lệ, hệ thống sẽ báo lỗi cụ thể và không lưu.
+ Người dùng không chọn xác nhận lưu thay đổi thì hệ thống sẽ không lưu vào cơ sở dữ liệu.


d. Usecase quản lý sản phẩm.
 

Đặc tả usecase:
Tên use case	Quản lý sản phẩm.
Tác nhân	Nhân viên quản lý.
Tóm tắt	Usecase bắt đầu khi nhân viên quản lý muốn thực hiện các chức năng quản lý sản phẩm của cửa hàng bao gồm các việc tìm kiếm, thêm, sửa sản phẩm.
Điều kiện tiên quyết	Nhân viên phải đăng nhập bằng tài khoản có phân quyền là quản lý.
Kết quả	1.	Nếu thành công: Thì dữ liệu được truy xuất hoặc cập nhật trong cơ sở dữ liệu.
2.	Nếu thất bại: Thông báo lỗi.
Kịch bản chính	1.	Người dùng chọn chức năng quản lý sản phẩm.
2.	Hệ thống hiển thị danh sách sản phẩm và các chức năng cho người dùng lựa chọn:
a.	Tìm kiếm sản phẩm.
b.	Thêm sản phẩm.
c.	Sửa sản phẩm.
a)	Tìm kiếm sản phẩm:
- Người dùng nhập thông tin của sản phẩm cần tìm.
- Nhấn nút tìm kiếm trên giao diện.
- Hệ thống hiển thị thông tin đầy đủ của sản phẩm tìm được.
b)	Thêm sản phẩm:
- Hệ thống hiển thị form nhập thông tin sản phẩm. 
- Người dùng nhập thông tin sản phẩm mới và nhấn chọn nút thêm trên giao diện.
- Hệ thống kiểm tra tính hợp lệ của sản phẩm mới.
- Nếu hợp lệ thì hệ thống sẽ hiển thị thông báo xác nhận có chắc chắn muốn thêm sản phẩm mới này vào cơ sở dữ liệu hay không?
- Nếu có thì hệ thống sẽ lưu sản phẩm mới vào cơ sở dữ liệu.
- Hiển thị thông báo thêm thành công và hiển thị thông tin của sản phẩm mới ra màn hình.
c)	Sửa sản phẩm:
- Người dùng chọn sản phẩm cần sửa.
- Hệ thống hiển thị thông tin sản phẩm đã chọn lên màn hình.
- Người dùng tiến hành thay đổi thông tin của sản phẩm.
- Nhấn nút sửa trên giao diện.
- Hệ thống kiểm tra tính hợp lệ của sản phẩm vừa chỉnh sửa.
- Nếu hợp lệ thì thì hệ thống sẽ hiển thị thông báo xác nhận có chắc chắn muốn sửa sản phẩm này trong cơ sở dữ liệu hay không?
- Nếu có thì hệ thống sẽ lưu vào cơ sở dữ liệu.
- Thông báo sửa thành công và hiển thị thông tin sản phẩm vừa sửa lên màn hình. 
Kịch bản phụ	-	Trong luồng sự kiện chính ở chức năng thêm, sửa nếu:
+ Thông tin sản phẩm nhập vào không hợp lệ, hệ thống sẽ báo lỗi cụ thể và không lưu.
+ Người dùng không chọn xác nhận lưu thay đổi thì hệ thống sẽ không lưu vào cơ sở dữ liệu.


e. Usecase quản lý món thêm đi kèm sản phẩm.
 

Đặc tả usecase:
Tên use case	Quản lý món thêm.
Tác nhân	Nhân viên quản lý.
Tóm tắt	Usecase bắt đầu khi nhân viên quản lý muốn thực hiện các chức năng quản lý món thêm của cửa hàng bao gồm các việc tìm kiếm, thêm, sửa món thêm.
Điều kiện tiên quyết	Nhân viên phải đăng nhập bằng tài khoản có phân quyền là quản lý.
Kết quả	1.	Nếu thành công: Thì dữ liệu được truy xuất hoặc cập nhật trong cơ sở dữ liệu.
2.	Nếu thất bại: Thông báo lỗi.
Kịch bản chính	1.	Người dùng chọn chức năng quản lý món thêm.
2.	Hệ thống hiển thị danh sách món thêm và các chức năng cho người dùng lựa chọn:
a. Tìm kiếm món thêm.
b. Thêm món thêm.
c. Sửa món thêm.
a)	Tìm kiếm món thêm:
- Người dùng nhập thông tin của món thêm cần tìm.
- Nhấn nút tìm kiếm trên giao diện.
- Hệ thống hiển thị thông tin đầy đủ của món thêm tìm được.
b)	Thêm món thêm:
- Hệ thống hiển thị form nhập thông tin món thêm. 
- Người dùng nhập thông tin món thêm mới và nhấn chọn nút thêm trên giao diện.
- Hệ thống kiểm tra tính hợp lệ của món thêm mới.
- Nếu hợp lệ thì hệ thống sẽ hiển thị thông báo xác nhận có chắc chắn muốn thêm món thêm mới này vào cơ sở dữ liệu hay không?
- Nếu có thì hệ thống sẽ lưu món thêm mới vào cơ sở dữ liệu.
- Hiển thị thông báo thêm thành công và hiển thị thông tin của món thêm mới ra màn hình.
c)	Sửa món thêm:
- Người dùng chọn món thêm cần sửa.
- Hệ thống hiển thị thông tin món thêm đã chọn lên màn hình.
- Người dùng tiến hành thay đổi thông tin của món thêm.
- Nhấn chọn nút sửa trên giao diện.
- Hệ thống kiểm tra tính hợp lệ của món thêm vừa chỉnh sửa.
- Nếu hợp lệ thì thì hệ thống sẽ hiển thị thông báo xác nhận có chắc chắn muốn sửa món thêm này trong cơ sở dữ liệu hay không?
- Nếu có thì hệ thống sẽ lưu vào cơ sở dữ liệu.
- Thông báo sửa thành công và hiển thị thông tin món thêm vừa sửa lên màn hình. 
Kịch bản phụ	-	Trong luồng sự kiện chính ở chức năng thêm, sửa nếu:
+ Thông tin món thêm nhập vào không hợp lệ, hệ thống sẽ báo lỗi cụ thể và không lưu.
+ Người dùng không chọn xác nhận lưu thay đổi thì hệ thống sẽ không lưu vào cơ sở dữ liệu.

f. Usecase quản lý đơn hàng.
 

Đặc tả usecase:
Tên use case	Quản lý đơn hàng.
Tác nhân	Nhân viên quản lý.
Tóm tắt	Usecase bắt đầu khi nhân viên quản lý muốn thực hiện các chức năng quản lý đơn hàng của cửa hàng bao gồm các việc tìm kiếm, xóa và in đơn hàng.
Điều kiện tiên quyết	Nhân viên phải đăng nhập bằng tài khoản có phân quyền là quản lý.
Kết quả	1.	Nếu thành công: Thì dữ liệu được truy xuất hoặc cập nhật trong cơ sở dữ liệu.
2.	Nếu thất bại: Thông báo lỗi.
Kịch bản chính	1.	Người dùng chọn chức năng quản lý đơn hàng.
2.	Hệ thống hiển thị danh sách đơn hàng và các chức năng cho người dùng lựa chọn:
a. Tìm kiếm đơn hàng.
b. Xóa đơn hàng.
c. In đơn hàng.
a)  Tìm kiếm đơn hàng:
- Người dùng nhập thông tin của đơn hàng cần tìm.
- Nhấn chọn nút tìm kiếm trên giao diện.
- Hệ thống hiển thị thông tin đầy đủ của đơn hàng cần tìm.
b)	Xóa đơn hàng:
- Chọn đơn hàng cần xóa.
- Nhấn chọn nút xóa trên giao diện.
- Hệ thống hiển thị thông báo xác nhận có chắc chắn muốn xóa đơn hàng ra khỏi hệ thống hay không?
- Nếu xác nhận thì hệ thống sẽ xóa đơn hàng ra khỏi cơ sở dữ liệu.
- Hiển thị thông báo xóa thành công.
c)	In đơn hàng:
- Người dùng chọn đơn hàng muốn in.
- Nhấn chọn nút in trên giao diện.
- Hệ thống hiển thị thông báo xác nhận có chắc chắn muốn in đơn hàng này hay không?
- Nếu xác nhận thì hệ thống sẽ in đơn hàng.

Kịch bản phụ	-	Trong luồng sự kiện chính ở chức năng xóa nếu: Người dùng không chọn xác nhận xóa thì hệ thống sẽ không xóa đơn hàng ra khỏi cơ sở dữ liệu.
-	Trong luồng sự kiện chính ở chức năng in nếu: Người dùng không chọn xác nhận in thì hệ thống sẽ không in đơn hàng.

g. Usecase quản lý nhân viên.
 

Đặc tả usecase:
Tên use case	Quản lý nhân viên.
Tác nhân	Nhân viên quản lý.
Tóm tắt	Usecase bắt đầu khi nhân viên quản lý muốn thực hiện các chức năng quản lý nhân viên của cửa hàng bao gồm các việc tìm kiếm, thêm, sửa, xóa nhân viên.
Điều kiện tiên quyết	Nhân viên phải đăng nhập bằng tài khoản có phân quyền là quản lý.
Kết quả	1.	Nếu thành công: Thì dữ liệu được truy xuất hoặc cập nhật trong cơ sở dữ liệu.
2.	Nếu thất bại: Thông báo lỗi.
Kịch bản chính	1.	Người dùng chọn chức năng quản lý nhân viên.
2.	Hệ thống hiển thị danh sách nhân viên và các chức năng cho người dùng lựa chọn:
a. Tìm kiếm nhân viên.
b. Thêm nhân viên.
c. Sửa nhân viên.
d. Xóa nhân viên.
a)	Tìm kiếm nhân viên:
- Người dùng nhập thông tin của nhân viên cần tìm.
- Nhấn chọn nút tìm kiếm trên giao diện.
- Hệ thống hiển thị thông tin đầy đủ của nhân viên tìm được.
b)	Thêm nhân viên:
- Hệ thống hiển thị form nhập thông tin nhân viên. 
- Người dùng nhập thông tin nhân viên mới và nhấn chọn nút thêm trên giao diện.
- Hệ thống kiểm tra tính hợp lệ của nhân viên mới.
- Nếu hợp lệ thì hệ thống sẽ hiển thị thông báo xác nhận có chắc chắn muốn thêm nhân viên mới này vào cơ sở dữ liệu hay không?
- Nếu có thì hệ thống sẽ lưu nhân viên mới vào cơ sở dữ liệu.
- Hiển thị thông báo thêm thành công và hiển thị thông tin của nhân viên mới ra màn hình.
c)	Sửa nhân viên:
- Người dùng chọn nhân viên cần sửa.
- Hệ thống hiển thị thông tin nhân viên đã chọn lên màn hình.
- Người dùng tiến hành thay đổi thông tin của nhân viên.
- Nhấn chọn nút sửa trên giao diện.
- Hệ thống kiểm tra tính hợp lệ của nhân viên vừa chỉnh sửa.
- Nếu hợp lệ thì thì hệ thống sẽ hiển thị thông báo xác nhận có chắc chắn muốn sửa nhân viên này trong cơ sở dữ liệu hay không?
- Nếu có thì hệ thống sẽ lưu vào cơ sở dữ liệu.
- Thông báo sửa thành công và hiển thị thông tin nhân viên vừa sửa lên màn hình.
d) Xóa nhân viên:
- Chọn nhân viên cần xóa.
- Nhấn chọn nút xóa trên giao diện.
- Hệ thống hiển thị thông báo xác nhận có chắc chắn muốn xóa nhân viên ra khỏi hệ thống hay không?
- Nếu xác nhận thì hệ thống sẽ xóa nhân viên ra khỏi cơ sở dữ liệu.
- Hiển thị thông báo xóa thành công.
Kịch bản phụ	-	Trong luồng sự kiện chính ở chức năng thêm, sửa nếu:
+ Thông tin nhân viên nhập vào không hợp lệ, hệ thống sẽ báo lỗi cụ thể và không lưu.
+ Người dùng không chọn xác nhận lưu thay đổi thì hệ thống sẽ không lưu vào cơ sở dữ liệu.
-	Trong luồng sự kiện chính ở chức năng xóa nếu: Người dùng không chọn xác nhận xóa thì hệ thống sẽ không xóa nhân viên ra khỏi cơ sở dữ liệu.

h. Usecase quản lý tài khoản đăng nhập.
 

Đặc tả usecase:
Tên use case	Quản lý tài khoản đăng nhập.
Tác nhân	Nhân viên quản lý.
Tóm tắt	Usecase bắt đầu khi nhân viên quản lý muốn thực hiện các chức năng quản lý tài khoản đăng nhập của cửa hàng bao gồm các việc tìm kiếm, thêm, sửa, xóa tài khoản đăng nhập.
Điều kiện tiên quyết	Nhân viên phải đăng nhập bằng tài khoản có phân quyền là quản lý.
Kết quả	1.	Nếu thành công: Thì dữ liệu được truy xuất hoặc cập nhật trong cơ sở dữ liệu.
2.	Nếu thất bại: Thông báo lỗi.
Kịch bản chính	1.	Người dùng chọn chức năng quản lý tài khoản đăng nhập.
2.	Hệ thống hiển thị danh sách tài khoản đăng nhập và các chức năng cho người dùng lựa chọn:
a. Tìm kiếm tài khoản.
b. Thêm tài khoản.
c. Sửa tài khoản.
d. Xóa tài khoản.
a)	Tìm kiếm tài khoản:
- Người dùng nhập thông tin của tài khoản cần tìm.
- Nhấn chọn nút tìm kiếm trên giao diện.
- Hệ thống hiển thị thông tin đầy đủ của tài khoản tìm được.
b)	Thêm tài khoản:
- Hệ thống hiển thị form nhập thông tin tài khoản.
- Người dùng nhập thông tin tài khoản mới và nhấn chọn nút thêm trên giao diện.
- Hệ thống kiểm tra tính hợp lệ của tài khoản mới.
- Nếu hợp lệ thì hệ thống sẽ hiển thị thông báo xác nhận có chắc chắn muốn thêm tài khoản mới này vào cơ sở dữ liệu hay không?
- Nếu có thì hệ thống sẽ lưu tài khoản mới vào cơ sở dữ liệu.
- Hiển thị thông báo thêm thành công và hiển thị thông tin của tài khoản mới ra màn hình.
c)	Sửa tài khoản:
- Người dùng chọn tài khoản cần sửa.
- Hệ thống hiển thị thông tin tài khoản đã chọn lên màn hình.
- Người dùng tiến hành thay đổi thông tin của tài khoản.
- Nhấn chọn nút sửa trên giao diện.
- Hệ thống kiểm tra tính hợp lệ của tài khoản vừa chỉnh sửa.
- Nếu hợp lệ thì thì hệ thống sẽ hiển thị thông báo xác nhận có chắc chắn muốn sửa tài khoản này trong cơ sở dữ liệu hay không?
- Nếu có thì hệ thống sẽ lưu vào cơ sở dữ liệu.
- Thông báo sửa thành công và hiển thị thông tin tài khoản vừa sửa lên màn hình.
d) Xóa tài khoản:
- Chọn tài khoản cần xóa.
- Nhấn chọn nút xóa trên giao diện.
- Hệ thống hiển thị thông báo xác nhận có chắc chắn muốn xóa tài khoản ra khỏi hệ thống hay không?
- Nếu xác nhận thì hệ thống sẽ xóa tài khoản ra khỏi cơ sở dữ liệu.
- Hiển thị thông báo xóa thành công.
Kịch bản phụ	-	Trong luồng sự kiện chính ở chức năng thêm, sửa nếu:
+ Thông tin tài khoản nhập vào không hợp lệ, hệ thống sẽ báo lỗi cụ thể và không lưu.
+ Người dùng không chọn xác nhận lưu thay đổi thì hệ thống sẽ không lưu vào cơ sở dữ liệu.
-	Trong luồng sự kiện chính ở chức năng xóa nếu: Người dùng không chọn xác nhận xóa thì hệ thống sẽ không xóa tài khoản ra khỏi cơ sở dữ liệu.

















i. Usecase bán hàng.
 

Đặc tả usecase:
Tên use case	Bán hàng
Tác nhân	Nhân viên quản lý, nhân viên bán hàng
Tóm tắt	Usecase bắt đầu khi tác nhân muốn thực hiện quy trình nghiệp vụ bán hàng. Bao gồm các công việc: lập đơn hàng (gồm lập đơn hàng cho khách dùng tại bàn, lập đơn hàng cho khách dùng mang về), thanh toán đơn hàng tại bàn và xuất hóa đơn.
Điều kiện tiên quyết	Phải đăng nhập vào hệ thống.
Kết quả	Khi thực hiện chức năng lập đơn hàng:
1.	Nếu lập đơn hàng mang về thì sau khi lập xong phải lưu đơn hàng mang về vào cơ sở dữ liệu và xuất hóa đơn cho khách.
2.	Nếu lập đơn hàng tại bàn thì sau khi lập phải lưu đơn hàng tại bàn với trạng thái chưa thanh toán vào cơ sở dữ liệu đồng thời cập nhật trạng thái bàn.
Khi thực hiện chức năng thanh toán đơn hàng tại bàn, thông tin đơn hàng tại bàn sẽ được cập nhật trạng thái đã thanh toán vào cơ sở dữ liệu, đồng thời cập nhật lại trạng thái bàn của đơn đã thanh toán, sau đó xuất hóa đơn cho khách.
Kịch bản chính	1.	Nhân viên nhấn chọn vào chức năng bán hàng trên giao diện menu chọn chức năng.
2.	Sau đó xác định các yêu cầu của khách hàng để thực hiện chức năng:
a.	Lập đơn hàng cho khách dùng mang về.
b.	Lập đơn hàng cho khách dùng tại bàn.
c.	Thanh toán đơn hàng tại bàn.
a)	Lập đơn hàng cho khách dùng mang về:
- Hệ thống khởi tạo thông tin đơn hàng mới.
- Nhân viên tiến hành chọn món và topping đi kèm (có thể sửa, xóa chi tiết đơn hàng trong quá trình thao tác).
- Hiển thị thông tin đơn hàng mang về lên giao diện.
- Nhân viên bấm nút thanh toán.
- Hệ thống lưu đơn hàng mang về và các chi tiết đơn hàng vào cơ sở dữ liệu, đồng thời hệ thống hiển thị thông báo xác nhận nhân viên có muốn in hóa đơn hay không?
- Nếu có thì hệ thống sẽ in hóa đơn cho nhân viên. 
b)  Lập đơn hàng cho khách dùng tại bàn:
- Hệ thống khởi tạo thông tin đơn hàng mới.
- Nhân viên tiến hành chọn bàn cho khách.
- Nhân viên tiến hành chọn món và topping đi kèm (có thể sửa, xóa chi tiết đơn hàng trong quá trình thao tác).
- Hệ thống sẽ lưu đơn hàng tại bàn cùng các chi tiết đơn hàng với trạng thái là chưa thanh toán, đồng thời cập nhật lại trạng thái bàn đã có đơn.
- Hiển thị thông tin đơn hàng tại bàn lên giao diện.
c) Thanh toán đơn hàng tại bàn:
- Nhân viên nhấn chọn vào bàn muốn thanh toán đơn hàng.
- Thông tin đơn hàng của bàn đó sẽ hiển thị lên màn hình.
- Nhấn vào nút thanh toán.
- Hệ thống cập nhật lại trạng thái bàn khách trả và đơn hàng tại bàn đã thanh toán vào cơ sở dữ liệu, đồng thời hệ thống hiển thị thông báo xác nhận nhân viên có muốn in hóa đơn hay không?
- Nếu có thì hệ thống sẽ in hóa đơn cho nhân viên. 

Kịch bản phụ	Trong kịch bản chính, luồng in hóa đơn, nếu nhân viên xác nhận từ chối in hóa đơn, thì hệ thống sẽ không in hóa đơn cho nhân viên.

j. Usecase thống kê báo cáo.
 

Đặc tả usecase:
Tên use case	Thống kế báo cáo.
Tác nhân	Nhân viên quản lý, nhân viên bán hàng.
Tóm tắt	Usecase bắt đầu khi tác nhân muốn thực hiện việc thống kê báo cáo (thống kê sản phẩm, món thêm và doanh thu). Đối với nhân viên bán hàng chỉ được quyền thống kê báo cáo theo ngày. Ngược lại, đối với nhân viên quản lý thì được quyền thống kê báo cáo theo thời gian bất kỳ (ngày, quý, tháng, năm...).
Điều kiện tiên quyết	Phải đăng nhập vào hệ thống.
Kết quả	1.	Nếu tìm thấy kết quả: Hiển thị kết quả thống kê.
2.	Nếu không tìm thấy kết quả: Hiển thị danh sách thống kê trống.
Kịch bản chính	1.	Người dùng chọn chức năng thống kê báo cáo trên giao diện.
2.	Hệ thống hiển thị các chức năng cho người dùng lựa chọn như sau:
a. Thống kê sản phẩm
b. Thống kê món thêm
c. Thống kê doanh thu
a)	Thống kê sản phẩm:
-	Người dùng nhấn chọn vào nút thống kê sản phẩm trên giao diện.
-	Hệ thống hiển thị danh sách thống kê các sản phẩm bán được của ngày hiện tại (nếu là nhân viên bán hàng thì việc thực hiện chức năng chỉ dừng ở đây).
-	Nhân viên quản lý chọn khoảng thời gian thống kê cụ thể.
-	Sau đó bấm vào nút tìm kiếm.
-	Hệ thống hiển thị danh sách thống kê sản phẩm của khoảng thời gian đã chọn lên giao diện.
b)	Thống kê món thêm:
-	Người dùng nhấn chọn vào nút thống kê món thêm trên giao diện.
-	Hệ thống hiển thị danh sách thống kê các món thêm bán được của ngày hiện tại (nếu là nhân viên bán hàng thì việc thực hiện chức năng chỉ dừng ở đây).
-	Nhân viên quản lý chọn khoảng thời gian thống kê cụ thể.
-	Sau đó nhấn chọn vào nút tìm kiếm.
-	Hệ thống hiển thị danh sách thống kê món thêm của khoảng thời gian đã chọn lên giao diện.
c)	Thống kê doanh thu:
-	Người dùng nhấn chọn vào nút thống kê doanh thu trên giao diện.
-	Hệ thống hiển thị danh sách thống kê các đơn hàng bán được và doanh thu của ngày hiện tại (nếu là nhân viên bán hàng thì việc thực hiện chức năng chỉ dừng ở đây).
-	Nhân viên quản lý chọn khoảng thời gian thống kê cụ thể.
-	Sau đó nhấn chọn vào nút tìm kiếm.
-	Hệ thống hiển thị danh sách thống kê các đơn hàng bán được và doanh thu của khoảng thời gian đã chọn lên giao diện.

Kịch bản phụ	Không có.




3.2.2. Biểu đồ lớp.

3.2.3. Sequence.
3.2.3.1. Sequence quản lý thể loại sản phẩm.






a. Thêm thể loại sản phẩm.
 

b. Sửa thông tin thể loại sản phẩm.
 




c. Tìm kiếm thể loại sản phẩm.
 

3.2.3.2. Sequence quản lý sản phẩm.
a. Thêm sản phẩm.
 



b. Sửa thông tin sản phẩm.
 

c. Tìm kiếm sản phẩm.
 

3.2.3.3. Sequence quản lý nhân viên.
a. Thêm nhân viên.
 

b. Sửa nhân viên.
 


c. Xóa nhân viên.
 

d. Tìm kiếm nhân viên.
 

3.2.3.4. Sequence quản lý món thêm.
a. Thêm món thêm.
 

b. Sửa món thêm.
 



c. Tìm kiếm món thêm.
 

3.2.3.5. Sequence quản lý tài khoản đăng nhập.
a. Thêm tài khoản.
 


b. Sửa tài khoản.
 















c. Xóa tài khoản.
 

d. Tìm kiếm tài khoản.
 

3.2.3.6. Sequence quản lý đơn hàng.
a. Tìm kiếm đơn hàng.
 

b. Xóa đơn hàng.
 

c. In đơn hàng.
 

3.2.3.7. Sequence đăng nhập.
 
3.2.3.8. Sequence thống kê.
a. Sequence thống kê sản phẩm.
	Thống kê sản phẩm quyền nhân viên:
 

	Thống kê sản phẩm quyền quản lý:
 



b. Sequence thống kê món thêm.
	Thống kê món thêm quyền nhân viên:
 
















	Thống kê món thêm quyền quản lý:
 
c. Sequence thống kê doanh thu.
	Thống kê doanh thu quyền nhân viên:
 




	Thống kê doanh thu quyền quản lý:
 















3.2.3.9. Sequence xử lý đơn hàng.
a. Sequence lập đơn hàng mang về.
 


b. Sequence lập đơn hàng dùng tại bàn.
 









c. Sequence thanh toán đơn hàng tại bàn.
 
3.3. Thiết kế dữ liệu.
3.3.1. Phân tích, thiết kế ERD.
 

3.3.1.1. Mô tả ERD.
Thể loại sản phẩm (CLASSIFY): gồm mã thể loại, tên thể loại và tình trạng kinh doanh của thể loại sản phẩm (nếu không muốn kinh doanh nữa thì cài đặt tình trạng kinh doanh về giá trị false, thể loại sản phẩm sẽ bị ẩn đi trên giao diện bán hàng).
Mỗi thể loại sản phẩm bao gồm nhiều sản phẩm nước uống.
Sản phẩm nước uống của quán (PRODUCT): gồm mã thể loại, mã sản phẩm, tên, tên hiển thị ra giao diện, size + giá, trạng thái nóng/lạnh và trạng thái kinh doanh (nếu không muốn kinh doanh nữa thì cài đặt tình trạng kinh doanh về giá trị false, sản phẩm sẽ bị ẩn đi trên giao diện bán hàng).
Mỗi sản phẩm nước uống chỉ thuộc về một thể loại sản phẩm.
Mỗi sản phẩm nước uống có thể kết hợp với nhiều loại topping.
Mỗi sản phẩm có một hoặc nhiều size (tối đa là 3).
Sản phẩm và size (PRODUCT-SIZE): gồm mã sản phẩm, size và giá.
Món thêm đi kèm (TOPPING): gồm mã món thêm, tên, giá và tình trạng kinh doanh (nếu không muốn kinh doanh nữa thì cài đặt tình trạng kinh doanh về giá trị false, món thêm sẽ bị ẩn đi trên giao diện bán hàng).
Mỗi topping có thể kết hợp với nhiều loại nước uống.
Sản phẩm và topping đi kèm (PRODUCT-TOPPING): mã sản phẩm, mã topping.
Đơn hàng (BILL): gồm mã đơn hàng, ngày lập, tổng cộng, tiền nhận khách, tiền trả khách, tình trạng thanh toán, loại đơn hàng (tại bàn hay mang đi).
Mỗi đơn hàng sẽ bao gồm nhiều chi tiết đơn hàng. 
Mỗi đơn hàng được lập bởi một nhân viên. 
Chi tiết đơn hàng (DETAIL_BILL): gồm mã đơn hàng, mã sản phẩm, mã chi tiết đơn hàng, số thứ tự, số lượng, và đơn giá.
Mỗi chi tiết đơn hàng chỉ thuộc về một đơn hàng, bao gồm một sản phẩm và có thể có nhiều topping đi kèm.
Chi tiến đơn hàng – topping (DETAILBILL_TOPPING): gồm mã chi tiết đơn hàng, mã topping, số lượng và đơn giá.
Đơn hàng tại bàn (SPOT_BILL): BILL sẽ có một tập con là SPOT_BILL (đơn hàng tại bàn). Nếu là đơn hàng tại bàn thì có thêm số bàn.
Mỗi đơn hàng tại bàn chỉ thuộc về một bàn.
Bàn (TABLE): gồm mã bàn, số chỗ ngồi, tình trạng còn trống hay đã có người ngồi.
Mỗi bàn sẽ có nhiều đơn hàng tại bàn.
Nhân viên (STAFF): gồm mã nhân viên, tên, phone, address, birthday và chức vụ.
Mỗi nhân viên lập nhiều đơn hàng.
Mỗi nhân viên sẽ có một tài khoản đăng nhập vào hệ thống.
Tài khoản đăng nhập hệ thống của nhân viên (ACCOUNT): gồm username và password và mã nhân viên (mã nhân viên dùng để phân quyền đăng nhập giữa nhân viên quản lý và nhân viên bán hàng).
Mỗi tài khoản đăng nhập chỉ thuộc về một nhân viên trong cửa hàng.
3.3.2. Phân tích, thiết kế lược đồ cơ sở dữ liệu.


 








3.3.3. Cài đặt cơ sở dữ liệu.

 

3.3.4. Mô tả cơ sở dữ liệu.
3.3.4.1. Danh sách các bảng.

STT	Bảng	Ý nghĩa	Ghi chú
1	CLASSIFY	Lưu trữ dữ liệu của tất cả các thể loại sản phẩm trong cửa hàng.	Thể loại sản phẩm
2	PRODUCT	Lưu trữ dữ liệu của tất cả các sản phẩm trong cửa hàng.	Sản phẩm
3	PRODUCT-SIZE	Lưu trữ dữ liệu của tất cả các size của sản phẩm và giá tương ứng của từng size trong cửa hàng.	Sản phẩm – Size
4	TOPPING	Lưu trữ dữ liệu của tất cả các món thêm trong cửa hàng.	Món thêm đi kèm sản phẩm
5	PRODUCT-TOPPING	Lưu trữ dữ liệu của tất cả các chi tiết sản phẩm – món thêm trong cửa hàng.	Sản phẩm – Món thêm
6	BILL	Lưu trữ dữ liệu của tất cả các đơn hàng trong cửa hàng.	Đơn hàng
7	SPOT-BILL	Lưu trữ dữ liệu của tất cả các chi tiết đơn hàng tại bàn - bàn trong cửa hàng.	Đơn hàng tại bàn
8	DETAIL-BILL	Lưu trữ dữ liệu của tất cả các chi tiết đơn hàng trong cửa hàng.	Chi tiết đơn hàng
9	DETAILBILL-TOPPING	Lưu trữ dữ liệu của tất cả các chi tiết đơn hàng – món thêm trong cửa hàng.	Chi tiết đơn hàng – món thêm
10	TABLE-IN-STORE	Lưu trữ dữ liệu của tất cả các bàn trong cửa hàng.	Bàn
11	STAFF	Lưu trữ dữ liệu của tất cả các nhân viên trong cửa hàng.	Nhân viên
12	ACCOUNT	Lưu trữ dữ liệu của tất cả các tài khoản đăng nhập của các nhân viên trong cửa hàng.	Tài khoản đăng nhập

3.3.4.2. Mô tả chi tiết các bảng.
a. Bảng CLASSIFY.

STT	Thuộc tính	Loại	Kiểu	Độ dài	Ràng buộc	Diễn giải
1	CLASSIFY-ID	Khóa chính	Char	5	Not null	Mã thể loại 
2	CLASSIFY-NAME		Varchar	50	Not null	Tên thể loại
3	CLASSIFY-BUSINESS		Bit		Not null	Tình trạng kinh doanh của thể loại

b. Bảng PRODUCT.

STT	Thuộc tính	Loại	Kiểu	Độ dài	Ràng buộc	Diễn giải
1	PRODUCT-ID	Khóa chính 	Char	5	Not null	Mã sản phẩm 
2	PRODUCT-NAME		Varchar	100	Not null	Tên sản phẩm
3	PRODUCT-NICKNAME		Varchar	50	Not null	Tên hiển thị ra giao diện
4	PRODUCT-STATUS		Char	4	Not null, in (‘HOT’, ‘COLD’, ‘BOLD’)	Trạng thái nóng/lạnh
5	PRODUCT-BUSINESS		Bit		Not null	Tình trạng kinh doanh của sản phẩm
6	CLASSIFY-ID	Khóa ngoại	Char	5	Not null	Mã thể loại

c. Bảng PRODUCT_SIZE.

STT	Thuộc tính	Loại	Kiểu	Độ dài	Ràng buộc	Diễn giải
1	PRODUCT-ID	Khóa chính, Khóa ngoại	Char	5	Not null	Mã sản phẩm 
2	PRODUCT-SIZE	Khóa chính	Char	1	Not null	Kích cỡ
3	PRODUCT-PRICE		Money		Not null, >0	Giá

d. Bảng TOPPING.

STT	Thuộc tính	Loại	Kiểu	Độ dài	Ràng buộc	Diễn giải
1	TOPPING-ID	Khóa chính	Char	5	Not null	Mã món thêm 
2	TOPPING-NAME		Varchar	50	Not null	Tên món thêm
3	TOPPING-PRICE		Money		Not null, >0	Giá
4	TOPPING-BUSINESS		Bit		Not null	Tình trạng kinh doanh

e. Bảng PRODUCT_TOPPING.

STT	Thuộc tính	Loại	Kiểu	Độ dài	Ràng buộc	Diễn giải
1	PRODUCT-ID	Khóa chính, Khóa ngoại	Char	5	Not null	Mã sản phẩm 
2	TOPPING-ID	Khóa chính, Khóa ngoại	Char	5	Not null	Mã món thêm

f. Bảng BILL.

STT	Thuộc tính	Loại	Kiểu	Độ dài	Ràng buộc	Diễn giải
1	BILL-ID	Khóa chính 	Char	7	Not null	Mã đơn hàng 
2	BILL-DATE		Datetime		Not null	Ngày lập
3	BILL-TOTAL		Money		Not null, > 0	Tổng cộng
4	RECEIVED-MONEY		Money		> 0	Tiền nhận khách
5	EXCESS-MONEY		Money		> 0	Tiền trả khách
6	BILL-STATUS		Bit		Not null	Tình trạng thanh toán
7	BILL-TYPE		Varchar	10	Not null	Loại đơn
8	STAFF-ID	Khóa ngoại	Char	5		Mã nhân viên

g. Bảng SPOT_BILL.

STT	Thuộc tính	Loại	Kiểu	Độ dài	Ràng buộc	Diễn giải
1	BILL-ID	Khóa chính, Khóa ngoại	Char	7	Not null	Mã đơn hàng 
2	TABLE-ID	Khóa ngoại	Char	5		Mã bàn

h. Bảng DETAIL-BILL.

STT	Thuộc tính	Loại	Kiểu	Độ dài	Ràng buộc	Diễn giải
1	DETAIL-BILL-ID	Khóa chính 	Char	10	Not null	Mã chi tiết đơn hàng 
2	BILL-ID	Khóa ngoại	Char	7	Not null	Mã đơn hàng
3	PRODUCT-ID	Khóa ngoại	Char	5	Not null	Mã sản phẩm
4	ORDINAL-NUMBER		Int		Not null, > 0	Số thứ tự
5	QUANTITY		Int		Not null, > 0	Số lượng sản phẩm
6	UNIT-PRICE		Money		Not null, > 0	Đơn giá
7	PRODUCT-SIZE		Char	1	Not null	Size
8	PRODUCT-STATUS		Char	4	Not null	Trạng thái nóng/lạnh

i. Bảng DETAILBILL_TOPPING.

STT	Thuộc tính	Loại	Kiểu	Độ dài	Ràng buộc	Diễn giải
1	DETAIL-BILL-ID	Khóa chính, khóa ngoại	Char	10	Not null	Mã chi tiết đơn hàng 
2	TOPPING-ID	Khóa chính, khóa ngoại	Char	5	Not null	Mã món thêm
3	QUANTITY		Int		Not null, >0	Số lượng
4	PRICE		Money		Not null, >0	Giá

j. Bảng TABLE_IN_STORE.

STT	Thuộc tính	Loại	Kiểu	Độ dài	Ràng buộc	Diễn giải
1	TABLE-ID	Khóa chính	Char	5	Not null	Mã bàn 
2	TABLE-TYPE		Int		Not null, in (2, 4, 8)	Số chỗ ngồi
3	TABLE-STATUS		Bit		Not null	Tình trạng bàn trống

k. Bảng STAFF.

STT	Thuộc tính	Loại	Kiểu	Độ dài	Ràng buộc	Diễn giải
1	STAFF-ID	Khóa chính	Char	5	Not null	Mã nhân viên 
2	STAFF-NAME		Nvarchar	100	Not null	Tên nhân viên
3	BIRTHDAY		Datetime		Not null	Ngày sinh
4	ADDRESS		Nvarchar	200	Not null	Địa chỉ
5	PHONE		Char	20	Not null	Số điện thoại
6	POSITION		Varchar	50	Not null	Chức vụ

l. Bảng ACCOUNT.

STT	Thuộc tính	Loại	Kiểu	Độ dài	Ràng buộc	Diễn giải
1	A-USERNAME	Khóa chính	Varchar	20	Not null	Tên đăng nhập 
2	A-PASSWORD		Varchar	20	Not null	Mật khẩu
3	STAFF-ID	Khóa ngoại	Char	5	Not null	Mã nhân viên

3.4. Thiết kế giao diện.
3.5. Thiết kế xử lý giao diện.





