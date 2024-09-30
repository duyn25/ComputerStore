

|  |
| ----- |
| **TRƯỜNG ĐẠI HỌC CÔNG NGHIỆP HÀ NỘI KHOA CÔNG NGHỆ THÔNG TIN  \---------------------------------------** |
|   |
| **BÁO CÁO ĐỒ ÁN CHUYÊN NGÀNH** MÃ HỌC PHẦN: IT6121  **Đề tài**: Xây dựng website bán máy tính cho công ty GearVN  |
|  |
| **GVHD:** TS. Phạm Văn Hiệp |
| **Nhóm sinh viên thực hiện:**     |
| Trịnh Mai Dương Đinh Văn Duy Nguyễn Duy Nguyễn Hữu Duy |
| **Mã lớp:** 20241IT6121001	**Khóa:** 16 	**Nhóm:** 9 |
|  |
|  |
| **Hà Nội – Năm 2024** |

**MỤC LỤC**

**[LỜI CẢM ƠN](#lời-cảm-ơn)**	[4](#lời-cảm-ơn)

[**MỤC LỤC**	4](#mục-lục)

[**DANH MỤC CÁC THUẬT NGỮ, KÝ HIỆU VÀ CÁC CHỮ VIẾT TẮT**	4](#danh-mục-các-thuật-ngữ,-ký-hiệu-và-các-chữ-viết-tắt)

[**DANH MỤC HÌNH VẼ**	4](#danh-mục-hình-vẽ)

[**DANH MỤC BẢNG BIỂU**	4](#danh-mục-bảng-biểu)

[**MỞ ĐẦU**	5](#mở-đầu)

[1\. Lý do chọn đề tài	5](#1.-lý-do-chọn-đề-tài)

[2\. Mục đích	5](#2.-mục-đích)

[3\. Đối tượng và phạm vi nghiên cứu	5](#3.-đối-tượng-và-phạm-vi-nghiên-cứu)

[4\. Ý nghĩa khoa học và thực tiễn của đề tài.	5](#4.-ý-nghĩa-khoa-học-và-thực-tiễn-của-đề-tài.)

[**CHƯƠNG 1: GIỚI THIỆU TỔNG QUAN**	6](#chương-1:-giới-thiệu-tổng-quan)

[1.1. Giới thiệu chung	6](#1.1.-giới-thiệu-chung)

[1.2. Nghiên cứu hiện trạng và giải quyết vấn đề	6](#1.2.-nghiên-cứu-hiện-trạng-và-giải-quyết-vấn-đề)

[1.3. Giới thiệu về công nghệ, ngôn ngữ sử dụng	6](#1.3.-giới-thiệu-về-công-nghệ,-ngôn-ngữ-sử-dụng)

[**CHƯƠNG 2: PHÂN TÍCH THIẾT KẾ HỆ THỐNG**	6](#chương-2:-phân-tích-thiết-kế-hệ-thống)

[2.1. Xác định các tác nhân hệ thống, ca sử dụng	6](#2.1.-xác-định-các-tác-nhân-hệ-thống,-ca-sử-dụng)

[2.2. Biểu đồ usecase	6](#2.2.-biểu-đồ-usecase)

[2.3. Mô tả chi tiết usecase	6](#2.3.-mô-tả-chi-tiết-usecase)

[2.4 Thiết lập biểu đồ lớp chi tiết	6](#2.4-thiết-lập-biểu-đồ-lớp-chi-tiết)

[2.5 Cơ sở dữ liệu	6](#2.5-cơ-sở-dữ-liệu)

[2.6 Thiết kế giao diện hệ thống	6](#2.6-thiết-kế-giao-diện-hệ-thống)

[**CHƯƠNG 3: CÀI ĐẶT VÀ TRIỂN KHAI**	7](#chương-3:-cài-đặt-và-triển-khai)

[3.1. Giới thiệu về công cụ và môi trường cài đặt	7](#3.1.-giới-thiệu-về-công-cụ-và-môi-trường-cài-đặt)

[3.2. Giao diện của khách hàng (Front-end)	7](#3.2.-giao-diện-của-khách-hàng-\(front-end\))

[3.3 Giao diện của người quản trị(Back-end)	7](#3.3-giao-diện-của-người-quản-trị\(back-end\))

[3.4 Kiểm thử phẩn mềm	7](#3.4-kiểm-thử-phẩn-mềm)

[**KẾT LUẬN**	8](#kết-luận)

[**PHỤ LỤC (NẾU CÓ)**	8](#phụ-lục-\(nếu-có\))

### **LỜI CẢM ƠN** {#lời-cảm-ơn}

(viết ngắn gọn, trên một trang)

### **MỤC LỤC** {#mục-lục}

(trình bày theo Phụ lục 3\)

### **DANH MỤC CÁC THUẬT NGỮ, KÝ HIỆU VÀ CÁC CHỮ VIẾT TẮT**  {#danh-mục-các-thuật-ngữ,-ký-hiệu-và-các-chữ-viết-tắt}

(nếu có)  
	Tất cả các thuật ngữ, ký hiệu và các chữ viết tắt (được sử dụng nhiều hơn 3 lần trong báo cáo) được trình bày trong báo cáo thì cần giải thích tại đây.

### **DANH MỤC HÌNH VẼ** {#danh-mục-hình-vẽ}

(nếu có)  
	Tất cả các hình vẽ trong báo cáo cần được đánh chỉ số và được đặt tên (hay giải thích ngắn về hình vẽ đó và đặt phía dưới hình vẽ. Ví dụ về cách đánh chỉ số cho hình số 1 của chương 2: *Hình 2.1. Sơ đồ minh họa hoạt động của người dùng hệ thống ABC*)

### **DANH MỤC BẢNG BIỂU** {#danh-mục-bảng-biểu}

**(**nếu có)

# **MỞ ĐẦU**  {#mở-đầu}

## **1\. Lý do chọn đề tài** {#1.-lý-do-chọn-đề-tài}

Trong thời đại công nghệ số, việc kinh doanh trực tuyến ngày càng trở nên phổ biến, đặc biệt là trong lĩnh vực bán lẻ các sản phẩm công nghệ cao như máy tính và thiết bị điện tử. GearVN là một trong những công ty hàng đầu tại Việt Nam trong lĩnh vực cung cấp các sản phẩm công nghệ. Tuy nhiên, với sự cạnh tranh ngày càng khốc liệt trong ngành, việc xây dựng một website hiện đại, thân thiện với người dùng và tối ưu hóa trải nghiệm mua sắm trực tuyến là vô cùng cần thiết. Điều này không chỉ giúp công ty tiếp cận được nhiều khách hàng hơn mà còn nâng cao hiệu quả kinh doanh. Vì vậy, việc lựa chọn đề tài "Xây dựng website bán máy tính cho công ty GearVN" là hoàn toàn phù hợp với xu hướng phát triển hiện nay và mang tính ứng dụng cao.

## **2\. Mục đích** {#2.-mục-đích}

**\-Xây dựng một hệ thống thương mại điện tử hoàn chỉnh**: Mục tiêu chính của đề tài là phát triển một website bán máy tính, linh kiện và phụ kiện máy tính, nơi người dùng có thể tìm kiếm, xem chi tiết sản phẩm, thêm vào giỏ hàng và thực hiện các bước thanh toán.

**\-Cung cấp trải nghiệm người dùng tiện lợi và bảo mật**: Đề tài hướng đến xây dựng giao diện thân thiện, dễ sử dụng, đảm bảo các thao tác như đăng nhập, thanh toán, quản lý đơn hàng diễn ra mượt mà và an toàn.

**\-Quản trị sản phẩm và đơn hàng hiệu quả**: Hệ thống quản lý sản phẩm và đơn hàng cho phép admin dễ dàng thêm, sửa, xóa sản phẩm, đồng thời theo dõi và xử lý đơn hàng của khách hàng.

## **3\. Đối tượng và phạm vi nghiên cứu** {#3.-đối-tượng-và-phạm-vi-nghiên-cứu}

## **4\. Ý nghĩa khoa học và thực tiễn của đề tài.** {#4.-ý-nghĩa-khoa-học-và-thực-tiễn-của-đề-tài.}

**\-Ý nghĩa khoa học**

* **Ứng dụng công nghệ ASP.NET**: Đề tài là một ví dụ cụ thể về việc ứng dụng ASP.NET trong việc phát triển hệ thống thương mại điện tử, giúp người học hiểu rõ hơn về mô hình MVC, cách xử lý dữ liệu, và các kỹ thuật tối ưu hiệu suất, bảo mật web.  
* **Phát triển hệ thống quản lý dữ liệu**: Dự án sử dụng SQL Server để quản lý dữ liệu về sản phẩm, người dùng và đơn hàng, giúp nâng cao kỹ năng thiết kế cơ sở dữ liệu và tối ưu hóa truy vấn.  
* **Nghiên cứu và ứng dụng các kỹ thuật web tiên tiến**: Đề tài có thể ứng dụng các công nghệ web mới như AJAX, Entity Framework, Razor Pages, giúp người thực hiện dự án nâng cao kiến thức về công nghệ phát triển web hiện đại.

**\-Ý nghĩa thực tiễn**

* **Ứng dụng vào thực tế kinh doanh**: Website bán máy tính có thể được triển khai thực tế, hỗ trợ các doanh nghiệp nhỏ và vừa trong việc quản lý và bán hàng trực tuyến, tối ưu hóa quy trình bán hàng và chăm sóc khách hàng.  
* **Đáp ứng nhu cầu mua bán trực tuyến**: Trong bối cảnh thương mại điện tử ngày càng phát triển, website giúp khách hàng có thể dễ dàng mua sắm, tìm kiếm sản phẩm và so sánh giá cả trực tuyến.  
* **Cải thiện hiệu quả quản lý cho doanh nghiệp**: Nhờ hệ thống quản trị đơn hàng, quản lý sản phẩm và người dùng, các doanh nghiệp có thể quản lý hàng tồn kho, theo dõi và xử lý đơn hàng một cách hiệu quả hơn, đồng thời nâng cao trải nghiệm khách hàng.

# **CHƯƠNG 1: GIỚI THIỆU TỔNG QUAN**  {#chương-1:-giới-thiệu-tổng-quan}

## **1.1. Giới thiệu chung** {#1.1.-giới-thiệu-chung}

## **1.2. Nghiên cứu hiện trạng và giải quyết vấn đề**  {#1.2.-nghiên-cứu-hiện-trạng-và-giải-quyết-vấn-đề}

1.2.1. Hiện trạng của công ty

GearVN hiện đang kinh doanh các sản phẩm công nghệ như máy tính, laptop, linh kiện và phụ kiện gaming. Mặc dù đã có một số kênh bán hàng trực tuyến, nhưng website hiện tại chưa thực sự tối ưu, còn thiếu một số tính năng hỗ trợ trải nghiệm người dùng và hiệu quả quản lý bán hàng.

1.2.2. Cơ cấu tổ chức 

Công ty GearVN được tổ chức theo mô hình phòng ban gồm: Phòng Kinh doanh, Phòng Kỹ thuật, Phòng Marketing, Phòng Hành chính – Nhân sự, và Phòng Dịch vụ khách hàng. Mỗi phòng ban có nhiệm vụ chuyên biệt, phối hợp để đảm bảo vận hành trơn tru.

1.2.3. Mô tả hoạt động của các bộ phận

**Phòng Kinh doanh:** Quản lý bán hàng, nhập hàng và phân phối sản phẩm.

**Phòng Kỹ thuật:** Hỗ trợ kỹ thuật về sản phẩm, bảo trì và sửa chữa thiết bị.

**Phòng Marketing:** Triển khai các chiến dịch quảng cáo, tiếp thị trực tuyến và ngoại tuyến.

**Phòng Hành chính – Nhân sự:** Quản lý nhân sự và các công việc hành chính.

**Phòng Dịch vụ khách hàng:** Hỗ trợ khách hàng trước và sau bán hàng, xử lý khiếu nại và bảo hành.

1.2.4. Xác định yêu cầu 

**Về giao diện:** Website cần có giao diện thân thiện, dễ sử dụng, tương thích trên nhiều thiết bị.

**Về chức năng:** Tích hợp các tính năng giỏ hàng, thanh toán trực tuyến, quản lý kho hàng, theo dõi đơn hàng, và hỗ trợ khách hàng trực tuyến.

**Về hiệu suất:** Website phải hoạt động ổn định, tốc độ tải trang nhanh, có khả năng mở rộng khi nhu cầu tăng.

**Bảo mật:** Đảm bảo an toàn dữ liệu khách hàng và giao dịch trực tuyến.

## **1.3. Giới thiệu về công nghệ, ngôn ngữ sử dụng**  {#1.3.-giới-thiệu-về-công-nghệ,-ngôn-ngữ-sử-dụng}

1.3.1. ASP.NET

**ASP.NET** là một framework ứng dụng web do **Microsoft** phát triển, dùng để xây dựng các ứng dụng web và dịch vụ web động. Nó cho phép các lập trình viên phát triển các website, ứng dụng web và API một cách nhanh chóng và dễ dàng bằng cách sử dụng **C\#** hoặc **VB.NET và có thể chạy trên hầu hết các nền tảng hệ điều hành như Windows, Linux, MacOS**.

.NET Framework được ra mắt lần đầu vào năm 2002\. Hệ thống là một nền tảng phát triển phần mềm mạnh mẽ cho việc xây dựng ứng dụng trên nền tảng Windows. .NET Framework cung cấp một môi trường chạy ứng dụng hữu ích. Kèm theo đó có một tập hợp các thư viện lớn để hỗ trợ nhiều nền tảng công nghệ phát triển phổ biến như Windows Forms, WPF, ASP.NET.

ASP.NET là một phần quan trọng của .NET Framework dùng để tập trung vào phát triển các ứng dụng web. Phiên bản đầu tiên của ASP.NET được gọi là ASP.NET 1.0. Chương trình đã được giới thiệu cùng với .NET Framework 1.0 vào năm 2002\. Kể từ đó, Microsoft đã liên tục cải tiến, phát triển ASP.NET. Nhà phát hành liên tục giới thiệu các phiên bản mới hoặc bổ sung các tính năng, nâng cao hiệu suất của mỗi chương trình.

ASP.NET đã trở thành nền tảng công nghệ phát triển web phổ biến trong việc xây dựng ứng dụng web mạnh mẽ, tăng độ bảo mật và hiệu suất hoạt động trên Windows. Nó đã được sử dụng trong nhiều dự án phát triển web quan trọng. Từ đó hình thành cộng đồng phát triển khổng lồ trong lĩnh vực công nghệ.

1.3.2.Mô hình MVC

Mô hình MVC (Model-View-Controller) là một mẫu kiến trúc phần mềm được sử dụng phổ biến trong lập trình để phân tách ứng dụng thành ba thành phần logic chính: Model: Quản lý dữ liệu; View: Hiển thị dữ liệu; Controller: Xử lý tương tác người dùng.

**Models:**

\-      Lưu trữ thông tin, trạng thái của các đối tượng, là 1 lớp được ánh xạ từ 1 bảng trong CSDL.

\-      Chứa tất cả các nghiệp vụ logic, phương thức xử lý, truy xuất database, các Class, hàm xử lý, …

**Views**

\-  	Chịu trách nhiệm hiển thị các thông tin lên cho người dùng thông qua giao diện.

\-      Chứa các đối tượng GUI(Textbox, images...).

\-      Các thông tin cần hiển thị được lấy từ thành phần Models.

**Controllers**

\-      Xử lý các tác động về mặt giao diện, các thao tác đối với models, và chọn view để hiển thị ra màn hình.

\-      Điều hướng các yêu cầu từ người dùng và gọi phương thức xử lý.

\-      Trong MVC, view chỉ có tác dụng hiển thị giao diện,còn điều khiển vẫn do Controllers đảm trách.

Cách hoạt động của MVC: User tương tác với View, bằng cách click vào button, gửi yêu cầu đi. Controller nhận và điều hướng đến phương thức xử lý ở Model. Model nhận thông tin và thực thi các yêu cầu, View sẽ nhận kết quả từ Model và hiển thị lại cho người dùng.

*Hình 1.?: Cách hoạt động của mô hình MVC.*

Ưu và khuyết điểm:

\-      Ưu điểm:

\+   Thể hiện tính chuyên nghiệp trong lập trình, PTTK.

\+   Được chia thành các thành phần độc lập nên giúp phát triển ứng dụng nhanh, dễ nâng cấp, bảo trì, …

\+   Ứng dụng tạo ra chạy ổn định trên Windows.

\+   Đáp ứng nhiều loại thiết bị truy cập

\+   An toàn, Dễ tích hợp.

\-      Khuyết điểm:

\+   Đối với dự án nhỏ việc áp dụng mô hình MVC gây cồng kềnh, tốn thời gian trong quá trình phát triển.

\+   Tốn thời gian trung chuyển dữ liệu của các thành phần.

1.3.3. ASP.NET MVC

**ASP.NET MVC** là một framework phát triển ứng dụng web dựa trên kiến trúc **Model-View-Controller (MVC)**, được phát hành bởi Microsoft vào năm 2009\. Framework này cho phép lập trình viên phát triển các ứng dụng web với cách tiếp cận tách biệt giữa các thành phần: dữ liệu (Model), giao diện người dùng (View), và điều khiển luồng dữ liệu (Controller). ASP.NET MVC mang đến sự linh hoạt, rõ ràng trong cách tổ chức mã nguồn, dễ dàng bảo trì và kiểm thử, đặc biệt thích hợp cho các ứng dụng web lớn và phức tạp.

*Hình 1.?: Quá trình phát triển của ASP.NET MVC.*

Tuy ASP.Net MVC ra đời năm 2009 nhưng mà tính tới năm 2013 thì nó đã được update lên tới phiên bản ASP.Net MVC 5, đây cũng là 1 trong những ưu điểm của ông lớn Microsoft cập nhật công nghệ liên tục. Với sự cập nhật thường xuyên như vậy đã giúp cho ASP.Net MVC ngày nay phát triển mạnh mẽ không thua kém gì các công nghệ lập trình web sử dụng Java và Php.

ASP.Net MVC đã khắc phục được các nhược điểm của web forms vì vậy web forms hiện nay không còn được dùng phổ biến nữa. Tuy nhiên, ASP.NET Core (ra mắt năm 2016\) cũng đang dần thay thế ASP.NET MVC nhờ vào khả năng đa nền tảng, hiệu suất cao hơn, và kiến trúc hiện đại, giúp các nhà phát triển dễ dàng xây dựng các ứng dụng web linh hoạt và mở rộng hơn, trong khi vẫn giữ lại các ưu điểm của mô hình MVC truyền thống.

1.3.4.SQL server

SQL Server là hệ quản trị cơ sở dữ liệu được phát triển bởi tập đoàn Microsoft. Với ngôn ngữ truy vấn chính là Transact-SQL (T-SQL) giúp hỗ trợ quản lý nhiều loại dữ liệu, bảo mật mạnh mẽ và tích hợp chặt chẽ với các ứng dụng Microsoft khác. SQL Server cung cấp dịch vụ đám mây trên Azure giúp giảm gánh nặng quản lý hạ tầng.

Chức năng của SQL Server gồm quản lý hiệu suất, dự trữ dữ liệu phân tán và quản lý phiên bản. Với cộng đồng lớn và sự hỗ trợ từ Microsoft, SQL Server là một giải pháp mạnh mẽ cho việc quản lý cơ sở dữ liệu doanh nghiệp.

**Các tính năng chính của Microsoft SQL Server:**

\-        **Khả năng mở rộng**: SQL Server hỗ trợ lưu trữ và xử lý dữ liệu với quy mô lớn, từ các ứng dụng nhỏ đến các hệ thống lớn, cho phép mở rộng dễ dàng khi nhu cầu tăng lên.

\-        **Bảo mật mạnh mẽ**: Hệ thống quản lý người dùng và quyền truy cập của SQL Server giúp đảm bảo an toàn cho dữ liệu, ngăn chặn các cuộc tấn công từ bên ngoài và bên trong.

\-        **Tính năng sao lưu và phục hồi**: SQL Server cung cấp nhiều tùy chọn sao lưu và phục hồi để bảo vệ dữ liệu, bao gồm sao lưu toàn bộ, sao lưu gia tăng, và khả năng phục hồi nhanh chóng trong trường hợp xảy ra sự cố.

\-        **Tích hợp dễ dàng với ASP.NET**: SQL Server hỗ trợ Entity Framework, cho phép lập trình viên dễ dàng thực hiện các thao tác CRUD (Create, Read, Update, Delete) trên cơ sở dữ liệu thông qua mã C\# mà không cần viết nhiều câu lệnh SQL phức tạp.

\-        **Phân tích và báo cáo**: SQL Server cung cấp các công cụ phân tích dữ liệu mạnh mẽ và hỗ trợ tạo báo cáo, giúp doanh nghiệp có thể nắm bắt thông tin và đưa ra quyết định chính xác.

\-        **Hỗ trợ đa nền tảng**: Với SQL Server 2017 và các phiên bản mới hơn, Microsoft đã cho phép SQL Server chạy trên cả Windows và Linux, tạo điều kiện thuận lợi cho các lập trình viên.

1.3.5 Bootstrap và Jquery

**Bootstrap** và **jQuery** là hai công nghệ phổ biến trong phát triển web, giúp cải thiện giao diện người dùng và trải nghiệm tương tác của các ứng dụng web.

**Bootstrap:**

**Bootstrap** là một framework CSS mã nguồn mở được phát triển bởi Twitter, giúp lập trình viên dễ dàng thiết kế giao diện người dùng responsive (tương thích với nhiều kích thước màn hình) và hiện đại mà không cần viết nhiều mã CSS tùy chỉnh.

**Các tính năng chính của Bootstrap:**

\-        **Responsive Design**: Bootstrap sử dụng hệ thống lưới (grid system) linh hoạt giúp giao diện tự động điều chỉnh kích thước theo màn hình thiết bị.

\-        **Các thành phần UI**: Bao gồm nhiều thành phần như buttons, forms, modals, dropdowns, và nhiều hơn nữa, giúp lập trình viên tiết kiệm thời gian trong việc phát triển giao diện.

\-        **Tùy chỉnh dễ dàng**: Bootstrap cho phép tùy chỉnh dễ dàng với các biến SCSS, giúp lập trình viên có thể thay đổi màu sắc, kích thước và các thuộc tính khác mà không cần phải viết lại nhiều mã.

\-        **Tính tương thích với trình duyệt**: Bootstrap hỗ trợ các trình duyệt phổ biến, đảm bảo giao diện hoạt động nhất quán trên nhiều nền tảng khác nhau.

**jQuery:**

**jQuery** là một thư viện JavaScript nhẹ, giúp đơn giản hóa việc thao tác với DOM (Document Object Model), xử lý sự kiện, và thực hiện AJAX (Asynchronous JavaScript and XML).

**Các tính năng chính của jQuery:**

\-        **Thao tác DOM dễ dàng**: jQuery cho phép lập trình viên truy cập và thay đổi các phần tử HTML dễ dàng với cú pháp đơn giản và rõ ràng.

\-        **Xử lý sự kiện**: Cung cấp các phương thức để lắng nghe và xử lý các sự kiện như click, hover, và keyboard, giúp tạo ra trải nghiệm người dùng tương tác phong phú.

\-        **AJAX đơn giản**: jQuery giúp thực hiện các cuộc gọi AJAX dễ dàng, cho phép cập nhật nội dung trang mà không cần tải lại toàn bộ trang.

\-        **Tính năng mở rộng**: jQuery có nhiều plugin có sẵn, cho phép lập trình viên mở rộng khả năng của thư viện này để đáp ứng nhu cầu cụ thể của ứng dụng.

# **CHƯƠNG 2: PHÂN TÍCH THIẾT KẾ HỆ THỐNG** {#chương-2:-phân-tích-thiết-kế-hệ-thống}

## **2.1. Xác định các tác nhân hệ thống, ca sử dụng** {#2.1.-xác-định-các-tác-nhân-hệ-thống,-ca-sử-dụng}

## **2.2. Biểu đồ usecase** {#2.2.-biểu-đồ-usecase}

## **2.3. Mô tả chi tiết usecase** {#2.3.-mô-tả-chi-tiết-usecase}

## **2.4 Thiết lập biểu đồ lớp chi tiết** {#2.4-thiết-lập-biểu-đồ-lớp-chi-tiết}

## **2.5 Cơ sở dữ liệu** {#2.5-cơ-sở-dữ-liệu}

## **2.6 Thiết kế giao diện hệ thống** {#2.6-thiết-kế-giao-diện-hệ-thống}

# **CHƯƠNG 3: CÀI ĐẶT VÀ TRIỂN KHAI** {#chương-3:-cài-đặt-và-triển-khai}

## **3.1. Giới thiệu về công cụ và môi trường cài đặt** {#3.1.-giới-thiệu-về-công-cụ-và-môi-trường-cài-đặt}

## **3.2. Giao diện của khách hàng (Front-end)** {#3.2.-giao-diện-của-khách-hàng-(front-end)}

3.2.1. Trang chủ

3.2.2. Đăng ký

3.2.3 Thông tin khách hàng

3.2.4. Danh sách sản phẩm

3.2.5. Chi tiết sản phẩm

3.2.6. Giỏ hàng

3.2.7. Đặt hàng

3.2.8. Lịch sử giao dịch 

3.2.9.  Kiểm tra đơn hàng

3.2.10. Tin tức

## **3.3 Giao diện của người quản trị(Back-end)** {#3.3-giao-diện-của-người-quản-trị(back-end)}

3.3.1. Quản lý danh mục

3.3.1. Quản lý tài khoản 

3.3.1. Quản lý đơn hàng

3.3.1. Quản lý nhà sản xuất

3.3.1. Quản lý danh mục

## **3.4 Kiểm thử phẩn mềm** {#3.4-kiểm-thử-phẩn-mềm}

# **KẾT LUẬN**  {#kết-luận}

**TÀI LIỆU THAM KHẢO** 

# **PHỤ LỤC (NẾU CÓ)** {#phụ-lục-(nếu-có)}