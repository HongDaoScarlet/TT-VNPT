# **📖 BÁO CÁO THỰC TẬP TUẦN 1**
✨✨✨

🍁 **Nguyễn Thị Hồng Đào - Đoàn Nhật Linh** 🍁


### **Câu 1: Angular là gì? Lợi ích của Angular so với javascript thuần**
- Angular được xe là một open source (mã nguồn mở) hay frameworks miễn phí chuyên dụng cho 
công việc thiết kế giao diện web. Angular được phát triển từ những năm 2009 và được duy trì bởi Google. 
Frameworks này được xem là frameworks frontend mạnh mẽ nhất chuyên dụng bởi các lập trình viên cắt HTML cao cấp.
- Lợi ích của Angular:
  + Angular được “chống lưng” bởi Google, giúp cho Developer có cảm giác được đảm bảo. Mặc nhiên, họ sẽ ám thị rằng framework này khó mà bị “khai tử”, 
  vì vậy cứ yên tâm sử dụng.
  + Cộng đồng người dùng lớn nên nếu có thắc mắc gì cũng sẽ nhanh chóng được giải đáp.
  + Giúp phát triển Ứng dụng trang đơn (Single-page Application). Đây là ứng dụng chạy trên browser mà không bắt buộc phải tải lại trang khi sử dụng.

### **Câu 2: So sánh CSDL quan hệ và CSDL không quan hệ**
| **Tiêu chí** | **Cơ sở dữ liệu quan hệ** | **Cơ sở dữ liệu không quan hệ** |
|----------------|:---------------------:| :--------------------------:|
| Ngôn ngữ Query | Structured Query Language | Không có ngôn ngữ Query |
| Loại hình | SQL databases là cơ sở dữ liệu dựa trên bảng | NoSQL databases có thể dựa trên tài liệu, cặp khóa-giá trị, cơ sở dữ liệu biểu đồ |
| Khả năng mở rộng | Có thể mở rộng theo chiều dọc | Có thể mở rộng theo chiều ngang |
| Lưu trữ dữ liệu phân cấp | Không thích hợp cho việc lưu trữ dữ liệu phân cấp. |	Phù hợp cho kho lưu trữ dữ liệu phân cấp vì nó hỗ trợ phương thức cặp khóa-giá trị |
| Mục đích sử dụng | Được thiết kế dành cho các ứng dụng xử lý giao dịch trực tuyến trong giao dịch có độ ổn định cao và thích hợp để xử lí phân tích trực tuyến | Được thiết kế để phục vụ phân tích dữ liệu có cấu trúc chưa hoàn chỉnh. |
| Lựa chọn sử dụng | Dự án đã có yêu cầu dữ liệu rõ ràng xác định quan hệ logic có thể được xác định trước | Dự án yêu cầu dữ liệu không liên quan, khó xác định, đơn giản mềm dẻo khi đang phát triển |
| Mã nguồn | Một sự kết hợp của mã nguồn mở như Postgres & MySQL, và thương mại như Oracle Database. | Open-source |
### **Câu 3: Cơ sở dữ liệu phân tán**
> Cơ sở dữ liệu phân tán là một tập hợp dữ liệu có liên quan với nhau về mặt logic được dùng chung nhưng được lưu trữ phân tán về mặt vật lý với nhau.

- Một hệ QTCSDL phân tán là một hệ thống phần mềm cho phép quản trị CSDL phân tán và làm cho người sử dụng không nhận thấy sự phân tán về lưu trữ dữ liệu.
- Người dùng truy cập vào cơ sở dữ liệu phân tán thông qua chương trình ứng dụng. Có 2 loại:
  + Chương trình không yêu cầu dữ liệu từ nơi khác,
  + Chương trình có yêu cầu dữ liệu từ nơi khác.
- Có thể chia các hệ cơ sở dữ liệu phân tán thành 2 loại chính:
  + ***Hệ CSDL phân tán thuần nhất:*** các nút trên mạng đều cùng một hệ QTCSDL.
  + ***Hệ CSDL phân tán hỗn hợp:*** các nút trên mạng có thể dùng các hệ QTCSDL khác nhau.

### **Câu 4: So sánh kiến trúc Micro service và kiến trúc ứng dụng nguyên khối (Monolithic application)**
> Microservice là một loại kiến trúc phần mềm hướng dịch vụ, tập trung vào việc xây dựng một loạt các thành phần tự quản lý tạo nên ứng dụng. Không giống như các ứng dụng nguyên khối được xây dựng dưới dạng một đơn vị không thể chia tách, các ứng dụng microservice bao gồm nhiều thành phần độc lập output ra các API.

|  | **Microservices Architecture** | **Monolithic Architecture** |
|:-|:---------------------------|:------------------------|
| **Tổng quát** | Microservice chia rất nhỏ, dịch vụ độc lập kết hợp lỏng lẻo và có tính năng phát triển liên tục nhanh chóng. | Gồm các đơn vị phụ thuộc lẫn nhau, không thể phân chia và có tốc độ phát triển rất thấp |
| **Ưu điểm**| - Một microservice có thể được phát triển bởi một team nhỏ. Do vậy việc quản lý sẽ dễ dàng hơn.<br/> - Các microservice khởi động nhanh giúp quá trình phát triển, kiểm thử cũng nhanh hơn.<br/> - Dễ dàng mở rộng và tích hợp với các dịch vụ của bên thứ ba.<br/> - Cô lập lỗi tốt hơn, khi một microservice bị lỗi và ngừng hoạt động thì các microservice khác vẫn có thể hoạt động bình thường.<br/> - Khi cần thay đổi một thành phần, thì chỉ cần sửa đổi, cập nhật và triển khai lại thành phần đó chứ không cần triển khai lại toàn bộ hệ thống.| - Dễ phát triển, yêu cầu cơ sở hạ tầng đơn giản, nhân lực nhỏ và có thể chia sẻ ít nhiều về kỹ năng.<br/> - Việc phát triển và triển khai ứng dụng với kiến trúc này khá đơn giản khi mà các IDE hỗ trợ rất tốt việc kiểm tra và chạy ứng dụng với chỉ một cú click chuột hay một phím tắt.<br/> - Kiến trúc nguyên khối có thể mở rộng bằng cách thêm một load balancer (thiết bị cân bằng tải) và triển khai thêm các khối ứng dụng nữa nếu cần.|
| **Nhược điểm**| - Việc triển khai hệ thống microservice phức tạp hơn nhiều so với việc triển khai hệ thống nguyên khối.<br/> - Các lập trình viên phải tốn nhiều công sức hơn để thực hiện phần giao tiếp giữa các microservice.<br/> - Cần tính toán kích cỡ của một microservice. Nếu một microservice quá lớn, bản thân nó trở thành một ứng dụng theo kiến trúc nguyên khối. Nếu một microservice quá nhỏ thì độ phức tạp của hệ thống tăng lên rất nhiều.| - Với mô hình nguyên khối, một lỗi nhỏ có thể làm cả hệ thống ngừng hoạt động.<br/> - Khi ứng dụng nguyên khối ngày một lớn thì quá trình maintain (duy trì) và sửa lỗi ứng dụng cũng trở thành ác mộng vì thời gian build và khởi động lại ứng dụng rất lớn.<br/> - Áp dụng công nghệ mới khó khăn vì toàn bộ ứng dụng phải thay đổi. Do đó nhiều ứng dụng một khối thường phụ thuộc một công nghệ cũ và lỗi thời.|

### **Câu 5: Tìm hiểu về Spring Boot**

- Để phát triển một ứng dụng web cơ bản HelloWorld sử dụng Spring framework bạn sẽ cần ít nhất 5 công đoạn sau:
  + Tạo một project sử dụng Maven với các dependency cần thiết của Spring MVC và Servlet API.
  + Một tập tin web.xml để khai báo DispatcherServlet của Spring MVC.
  + Một tập tin cấu hình của Spring MVC.
  + Một class Controller trả về một trang “Hello World” khi có request đến.
  + Cuối cùng là phải có một web server dùng để triển khai ứng dụng lên chạy.

> **Spring Boot** là một dự án phát triển bởi **JAV** (ngôn ngữ java) trong hệ sinh thái Spring framework. Nó giúp cho các lập trình viên chúng ta đơn giản hóa quá trình lập trình một ứng dụng với Spring, chỉ tập trung vào việc phát triển business cho ứng dụng.

- Với Spring Boot chúng ta có thể triển khai dự án Spring một cách nhanh chóng và cấu hình đơn giản với các tính năng nổi bật:
  + Tạo các ứng dụng Spring độc lập
  + Nhúng trực tiếp Tomcat, Jetty hoặc Undertow (không cần phải deploy ra file WAR)
  + Các starter dependency giúp việc cấu hình Maven đơn giản hơn
  + Tự động cấu hình Spring khi cần thiết
  + Không sinh code cấu hình và không yêu cầu phải cấu hình bằng XML …  

---

### **I : Angular**

#### 1: Angular là gì ?

- Angular là một nền tảng để xây dựng các ứng dụng web dành cho thiết bị di động và máy tính để bàn. Nó có một cộng đồng lớn với hàng triệu nhà phát triển chọn Angular để xây dựng giao diện người dùng hấp dẫn.
- Angular là một front-end framework mã nguồn mở viết bằng JavaScript cho ứng dụng web. Nó chủ yếu được duy trì bởi Google cùng với một cộng đồng mở gồm các nhà phát triển và các công ty. Angular giải quyết nhiều thách thức phải đối mặt khi phát triển các ứng dụng SPA (Single Page Application), đa nền tảng, hiệu suất cao. Nó hoàn toàn có thể mở rộng và hoạt động rất tốt với các thư viện khác.

#### 2: Ưu điểm

- Angular cho phép người dùng xây dựng các component của riêng họ và có thể đóng gói chức năng cùng với logic kết xuất thành các phần có thể tái sử dụng. Nó cũng hoạt động tốt với các component của web.
- Angular cho phép người dùng dễ dàng di chuyển dữ liệu từ mã JavaScript sang view và phản hồi với các sự kiện của người dùng mà không cần phải viết bất kỳ mã nào theo cách thủ công.
- Angular cho phép người dùng viết các service mô-đun và đưa chúng vào bất cứ nơi nào họ cần. Điều này cải thiện khả năng kiểm tra và khả năng tái sử dụng của các service giống nhau.
- Có thể dễ dàng Unit test mọi phần trong ứng dụng
- Angular là một full-fledged Framework và có thể cung cấp các giải pháp tiện ích cho giao tiếp máy chủ, định tuyến trong ứng dụng và hơn thế nữa.
- Angular cung cấp đa nền tảng và tương thích với nhiều trình duyệt. Một ứng dụng Angular thường có thể chạy trên tất cả các trình duyệt (Ví dụ: Chrome, Firefox) và hệ điều hành, chẳng hạn như Windows, macOS và Linux.

#### 3: Nhược điểm

- Không an toàn: Thông thường, bản chất của Angular là một trong những Framework Front End, mà Front end này thường vốn không thể bảo mật bằng Back-end. Chính vì vậy, khi sử dụng API thì bạn cần xây dựng cho một hệ thống kiểm tra dữ liệu sao cho việc trả về được tốt nhất.
- Với một số trình duyệt sở hữu tính năng Disable JavaScript nên có nghĩa là website sẽ không hoàn toàn có thể sử dụng được dựa trên những trình duyệt đó nữa
- Bạn nên viết mã ứng dụng Angular bằng TypeScript, vì vậy bạn phải học TypeScript.

#### 4. Tính năng nổi bật của Angular

- Controller: Tính năng hỗ trợ xử lý dữ liệu dành cho $scope. Với tính năng này, views dùng dữ liệu có sẵn tại scope để tiến hành hiển thị tương ứng.
- Data-binding: Tính năng tự động đồng bộ hóa tất cả các dữ liệu giữa hai chiều model và view khi view có thay đổi.
- Service: Cung cấp một loạt phương án dữ liệu bởi là singleton object có năng lực khởi tạo.
- Scope: Là đối tượng giao tiếp giữa hai phía controller và view trong ứng dụng.
- Filter: Hỗ trợ lọc tập hợp con có trong item rồi trả chúng về mảng mới.
- Directive: Tính năng hỗ trợ tạo thẻ HTML. Một vài directive phổ biến là ngBind, ngModel…
- Temple: Tính năng hiển thị các thông tin từ controller, được coi như một phần trong view.
- Routing: Tính năng điều hướng, chuyển đổi trong controller. Người dùng có thể tạo SPA với tính năng này.
- MVC & MVVM: Tính năng phân chia những ứng dụng chưa nhiều thành phần, gắn liền với MVC.
- Deep link: Các liên kết sâu hỗ trợ lập trình viên trong việc mã hóa trạng thái ứng dụng trong các URL, nó khả năng bookmark với công cụ tìm kiếm.
- Dependency Injection: Tính năng này thường được tích hợp trong bản AngularJS, mang lại khả năng tạo lập những ứng dụng giàu tiềm năng phát triển, thao tác đơn giản, dễ kiểm tra.

### **II : Hệ cơ sở dữ liệu phân tán**

#### 1 : Khái niệm CSDL phân tán

- CSDL phân tán là một tập hợp dữ liệu có liên quan (ᴠề logic) được dùng chung ᴠà phân tán ᴠề mặt ᴠật lí trên một mạng máу tính.
- Một hệ QTCSDL phân tán là một hệ thống phần mềm cho phép quản trị CSDL phân tán ᴠà làm cho người ѕử dụng không nhận thấу ѕự phân tán ᴠề lưu trữ dữ liệu.
- Người dùng truу cập ᴠào CSDL phân tán thông quan chương trình ứng dụng. Các chương trình ứng dụng được chia làm hai loại:
  Chương trình không уêu cầu dữ liệu từ nơi khác. Chương trình có уêu cầu dữ liệu từ nơi khác.
- Có thể chia các hệ CSDL phân tán thành 2 loại chính: thuần nhất ᴠà hỗn hợp.
- Hệ CSDL phân tán thuần nhất: các nút trên mạng đều dùng cùng một hệ QTCSDL. Hệ CSDL phân tán hỗn hợp: các nút trên mạng có thể dùng các hệ QTCSDL khác nhau.

#### 2:Ưu điểm và hạn chế

- Ưu điểm
  - Cấu trúc phân tán dữ liệu thích hợp cho bản chất phân tán của nhiều người dùng.
  - Dữ liệu được chia sẽ trên mạng nhưng vẫn cho phép quản trị đữ liệu địa phương.
  - Dữ liệu có tính sẵn sàng cao.
  - Dữ liệu có tính tin cậy cao vì khi một nút gặp sự cố, có thể khôi phục dữ liệu tại đây do bản sao của nó có thể được lưu trữ tại một nút khác nữa.
  - Hiệu năng của hệ thống được nâng cao.
  - Cho phép mở rộng các tổ chức một cách linh hoạt. Có thể thêm nút mới mà không ảnh hưởng đến hoạt động của các nút sẵn có.
- Hạn chế
  - Hệ thống phức tạp
  - Chi phí cao
  - Đảm bảo an ninh khó hơn
  - Khó đảm bảo tính nhất quán dữ liệu
  - Thiết kế CSDL phân tán phức tạp hơn

### **III: Microservices**

#### 1 : Microservices là gì?

- Microservices là tên gọi của các dịch vụ nhỏ thuộc dạng tách biệt đại diện cho 1 phần nhỏ tương ứng bên trong các Business domain của lập trình viên. Microservices được xem như giải pháp có thể cân bằng được tất cả các traffic dựa theo yêu cầu của doanh nghiệp.

#### 2 : Ưu điểm

- Microservices cho phép dễ dàng continuous delivery và deployment các ứng dụng lớn và phức tạp hơn.
- Có thể cải thiện khả năng bảo trì: bởi vì các service tương đối nhỏ nên dễ hiểu và dễ thay đổi hơn.
- Có khả năng testing dễ dàng: nhờ các services nhỏ
- Có thể triển khai tốt hơn: các services thường rất dễ cho việc triển khai độc lập.
- Cho phép các services được phát triển nhanh chóng bởi những team khác nhau. Khi đó, mỗi team đều sẽ được phát triển và thử nghiệm để triển khai cũng như mở rộng được quy mô của dịch vụ của mình một cách độc lập nhất với tất cả các team.
- Nếu như có lỗi xảy ra trong một service thì chỉ có service đó bị ảnh hưởng và các service khác sẽ thực hiện xử lý các yêu cầu cần thiết. Trong khi đó, thì mỗi một thành phần nếu như hoạt động sai của kiến trúc một khối thì nó sẽ làm ảnh hưởng đến toàn bộ hệ thống.
- Lập trình viên có thể thay đổi dễ dàng bằng cách sử dụng công nghệ mới khi triển khai các service. Tương tự như khi có thay đổi lớn thì các service đều có thể thực hiện và bạn dễ dàng thay đổi được công nghệ hơn.

#### 3 : Hạn chế

- Bởi vì các nhà phát triển thường xuyên phải đối phó với sự phức tạp khi tạo ra một hệ thống phân tán.
- Cần phải implement việc communication giữa các inter-services
- Handle partial failure rất phức tạp bởi vì luồng xử lý cần phải đi qua nhiều service khác nhau.
- Khi thực hiện các requests trải rộng trên nhiều service khó khăn thì điều này cần đòi hỏi sự phối hợp giữa các team.
- Thường rất khó khăn trong việc đảm bảo toàn vẹn cho CSDL nếu như triển khai theo các cấu trúc cơ sở dữ liệu dạng phân vùng.
- Việc triển khai và quản lý microservices nếu như làm thủ công theo cách làm với ứng dụng thì sẽ rất phức tạp.
- Lập trình viên cần phải xử lý các sự cố kết nối chậm, lỗi nếu như thông điệp không được gửi hoặc nếu như thông điệp được gửi đến nhiều đích đến vào các thời điểm khác nhau.

#### 4: Lợi ích của Microservices

- Source code rất tinh gọn: Bởi vì hệ thống được cấu thành từ các dự án nhỏ, và mỗi dự án đều rất đơn giản cũng như tập trung vào 1 hoặc 1 vài nghiệp vụ chính. Vì vậy, các code base và độ phức tạp của chúng đều không cao. Nhờ vậy, nó sẽ giúp mang lại tính gọn nhẹ, dễ bảo trì cũng như mở rộng hơn.
- Bảo mật tối ưu cho source code: Khi nhân viên làm việc ở các dự án thì chỉ truy cập được vào một source code của dự án đó.
- Được tồn tại độc lập: Bởi vì đây là 4 dự án khác nhau và chúng có thể có cách deploy riêng biệt và một service nào đó chết thì các service khác vẫn sẽ hoạt động một cách bình thường.
- Scale hoàn toàn độc lập: Tùy thuộc vào nhu cầu sử dụng của hệ thống mà bạn có thể scale riêng cho service đó. Có thể như service đơn hàng mà sử dụng thường xuyên nên chạy từ 2 đến 3 server để gia tăng performance.

___
<br/>

# **📖 BÁO CÁO THỰC TẬP TUẦN 2**
✨✨✨ 

-	**Dự án: _Xây dựng hệ thống quản lý bệnh viện HISL2._**
- Phân tích tài liệu hướng dẫn sử dụng Quản lý bệnh nhân. Vẽ sơ đồ use case, sơ đồ lớp và sơ đồ tuần tự.

## **I. Sơ đồ use case (Use case diagram)**
\
\
![UseCaseBenhNhan](https://user-images.githubusercontent.com/106305844/173265349-43a72ff8-b8e0-4299-9138-8643a4d27861.png)
\
\
💎  **Đặc tả use case**
\
\
💫 ___Usecase Đăng nhập:___ 💫

| **Mã use case**     | **UC01**      |
| --------------------|:----------|
| Tên use case	      | Đăng nhập |
| Tác nhân chính      | Bệnh nhân |
| Tiền điều kiện      | Không có  |
| Hậu điều kiện       | Đăng nhập thành công vào hệ thống |
| Điều kiện tối thiểu	| Yêu cầu bệnh nhân đăng nhập lại |
| Sự kiện chính	| 1. Hệ thống hiển thị màn hình đăng nhập <br/>2. Bệnh nhân nhập thông tin tài khoản và mật khẩu <br/>3. Bệnh nhân nhấn “Đăng nhập” <br/>4. Hệ thống chứng thực tài khoản <br/>5. Hệ thống thông báo đăng nhập thành công |
| Ngoại lệ	| 4.1. Hệ thống chứng thực thất bại, yêu cầu bệnh nhân nhập lại thông tin tài khoản, mật khẩu. |

\
💫 ___Usecase Đăng kí hẹn khám:___ 💫

| **Mã use case**     | **UC03**  |
| --------------------|:----------|
| Tên use case	      | Đăng kí hẹn khám |
| Tác nhân chính      | Bệnh nhân |
| Tiền điều kiện      | Đăng nhập thành công vào hệ thống |
| Hậu điều kiện       | Đăng kí thành công lịch hẹn khám |
| Điều kiện tối thiểu	| Loại bỏ thông tin đã nhập và quay lại bước trước |
| Sự kiện chính	      | 1. Hệ thống hiển thị màn hình đăng kí hẹn khám <br />2. Bệnh nhân điền đầy đủ thông tin hẹn khám <br />3. Bệnh nhân nhấn “Đăng ký” <br />4. Hệ thống chứng thực thông tin hẹn khám <br/>5. Hệ thống thông báo đăng kí thành công |
| Ngoại lệ	          | 4.1. Hệ thống chứng thực thất bại, quay lại màn hình đăng kí hẹn khám. |

\
💫 ___Use case Quản lý lịch hẹn khám:___ 💫

| **Mã use case**     | **UC04**  |
| --------------------|:----------|
| Tên use case	      | Quản lý lịch hẹn khám |
| Tác nhân chính      | Bệnh nhân |
| Tiền điều kiện      | Đăng nhập thành công vào hệ thống |
| Hậu điều kiện       | Xem được lịch sử hẹn khám |
| Điều kiện tối thiểu	| Không có dữ liệu để xuất |
| Sự kiện chính	      | 1. Hệ thống hiển thị màn hình xem lịch sử hẹn khám <br/>2. Bệnh nhân nhấn vào các chức năng muốn thực hiện (sửa, xóa) <br/>3. Bệnh nhân nhập thông tin cần thiết <br/>4. Hệ thống chứng thực thông tin lịch hẹn khám <br/>5. Hệ thống thông báo cập nhật thành công |
| Ngoại lệ	          | 4.1. Hệ thống chứng thực thất bại, quay về màn hình quản lý lịch hẹn khám. |

\
💫	___Use case Quản lý tài khoản:___ 💫

| **Mã use case**     | **UC05**  |
| --------------------|:----------|
| Tên use case	      | Quản lý tài khoản |
| Tác nhân chính      | Bệnh nhân |
| Tiền điều kiện      | Đăng nhập thành công vào hệ thống |
| Hậu điều kiện       | Cập nhật thành công tài khoản |
| Điều kiện tối thiểu	| Loại bỏ thông tin đã nhập và quay lại bước trước |
| Sự kiện chính	      | 1. Hệ thống hiển thị màn hình thông tin tài khoản <br/>2. Bệnh nhân nhấp chọn chức năng muốn thực hiện (sửa thông tin, đổi mật khẩu) <br/>3. Bệnh nhân nhập thông tin cần thiết để thực hiện chức năng <br/>4. Hệ thống chứng thực thông tin tài khoản <br/>5. Hệ thống thông báo cập nhật thành công. |
| Ngoại lệ	          | 4.1. Hệ thống chứng thực thất bại, yêu cầu bệnh nhân nhập lại thông tin tài khoản |

\
💫	___Use case Thống kê chi phí khám chữa bệnh:___ 💫

| **Mã use case**     | **UC06**  |
| --------------------|:----------|
| Tên use case	      | Thống kê chi phí khám chữa bệnh |
| Tác nhân chính      | Bệnh nhân |
| Tiền điều kiện      | Đăng nhập thành công vào hệ thống |
| Hậu điều kiện       | Xuất thống kê chi phí khám chữa bệnh |
| Điều kiện tối thiểu	| Không có dữ liệu để xuất |
| Sự kiện chính	      | 1. Hệ thống hiển thị màn hình thống kê chi phí khám chữa bệnh <br/>2. Bệnh nhân nhấp chọn chi tiết để xem chi tiết từng khoảng chi <br/>3. Hệ thống hiển thị kết quả thống kê |
| Ngoại lệ	          | Không có |

\
💫	___Use case Quản lý khám chữa bệnh:___ 💫

| **Mã use case**     | **UC07**  |
| --------------------|:----------|
| Tên use case	      | Quản lý khám chữa bệnh |
| Tác nhân chính      | Bệnh nhân |
| Tiền điều kiện      | Đăng nhập thành công vào hệ thống |
| Hậu điều kiện       | Xuất thông tin khám chữa bệnh |
| Điều kiện tối thiểu	| Không có dữ liệu để xuất |
| Sự kiện chính	      | 1. Hệ thống hiển thị màn hình thống kê lịch sử điều trị tổng hợp <br/>2. Bệnh nhân nhấp chọn nút chức năng chi tiết để xem thông tin lịch sử điều trị, thông tin khám chữa bệnh, các thông tin các phiếu điều trị, thông tin lịch sử thuốc. <br/>3. Hệ thống hiển thị thông tin khám chữa bệnh |
| Ngoại lệ	          | Không có |

\
💫	___Use case Tra cứu xét nghiệm:___ 💫

| **Mã use case**     | **UC08**  |
| --------------------|:----------|
| Tên use case	      | Tra cứu xét nghiệm |
| Tác nhân chính      | Bệnh nhân |
| Tiền điều kiện      | Đăng nhập thành công vào hệ thống |
| Hậu điều kiện       | Xuất thông tin phiếu xét nghiệm |
| Điều kiện tối thiểu	| Không có dữ liệu để xuất |
| Sự kiện chính	      | 1. Hệ thống hiển thị màn hình tra cứu xét nghiệm <br/>2. Bệnh nhân nhập thông tin tìm kiếm phiếu xét nghiệm và bấm nút tìm kiếm. <br/>3. Hệ thống hiển thị thông tin phiếu xét nghiệm |
| Ngoại lệ	          | Không có |

\
💫	___Use case Tra cứu CĐHA:___ 💫

| **Mã use case**     | **UC09**  |
| --------------------|:----------|
| Tên use case	      | Tra cứu CĐHA |
| Tác nhân chính      | Bệnh nhân |
| Tiền điều kiện      | Đăng nhập thành công vào hệ thống |
| Hậu điều kiện       | Xuất thông tin phiếu CĐHA|
| Điều kiện tối thiểu	| Không có dữ liệu để xuất |
| Sự kiện chính	      | 1. Hệ thống hiển thị màn hình tra cứu CĐHA <br/>2. Bệnh nhân nhập thông tin tìm kiếm phiếu CĐHA và bấm nút tìm kiếm. <br/>3. Hệ thống hiển thị thông tin phiếu CĐHA |
| Ngoại lệ	          | Không có |


## **II. Sơ đồ lớp (Class diagram)**
\
\
![ClassQuanLyBenhNhan](https://user-images.githubusercontent.com/106305844/173264222-a8dd3f5d-dbcf-4564-84e8-329842d86c89.png)
<br/>
<br/>

## **III. Sơ đồ tuần tự (Sequence Diagram)**
### ***1. Sơ đồ tuần tự chức năng Đăng nhập***
\
![dangNhap](https://user-images.githubusercontent.com/106305844/173264227-010570b2-ab86-43dd-80e8-e958730b8218.png)


### ***2.	Sơ đồ tuần tự chức năng Quản lí tài khoản***
\
![quanLyTaiKhoan](https://user-images.githubusercontent.com/106305844/173264244-75376912-a62d-438a-b9d4-b9766b48a17b.png)

### ***3.	Sơ đồ tuần tự chức năng Đăng kí hẹn khám***
\
![dangKiHenKham](https://user-images.githubusercontent.com/106305844/173264225-8bb39b3b-d093-4c70-a267-ea353b0f0fe1.png)

### ***4.	Sơ đồ tuần tự chức năng xem Lịch sử hẹn khám***
\
![xemLichSuHenKham](https://user-images.githubusercontent.com/106305844/173264219-c3bcca3c-74f6-4cd4-8912-c5dc7fcbd2e5.png)

### ***5.	Sơ đồ tuần tự chức năng Thống kê chi phí***
\
![thongKeChiPhi](https://user-images.githubusercontent.com/106305844/173264245-b6ebdf6a-89c7-4cf5-bd01-edb77c25f7d6.png)

### ***6.	Sơ đồ tuần tự chức năng Quản lý khám chữa bệnh***
\
![quanLyKhamChuaBenh](https://user-images.githubusercontent.com/106305844/173264243-dcf62fd2-eb51-4e38-b309-9d8079514e7b.png)

### ***7.	Sơ đồ tuần tự chức năng Tra cứu xét nghiệm***
\
![traCuuXetNghiem](https://user-images.githubusercontent.com/106305844/173264250-f18eabe1-24e6-4efb-b966-7433acce7ee3.png)

### ***8.	Sơ đồ tuần tự chức năng Tra cứu CĐHA***
\
![traCuuCDHA](https://user-images.githubusercontent.com/106305844/173264249-bde88b87-d519-46a3-9664-1dd59e369d44.png)


___
<br/>

# **📖 BÁO CÁO THỰC TẬP TUẦN 3**
✨✨✨

>**Nhiệm Vụ**: _Viết báo cáo về jhipster và các áp dụng angular trong jhipster (06 - 10/06/2022)_

## **I. Tìm hiểu Jhipster**
- JHipster (***Java Hipster***) có thể giúp bạn tạo các ứng dụng web đẹp mắt và các kiến trúc microservices phức tạp trong nháy mắt. JHipster cũng cung cấp các công cụ khác nhau để phát triển ứng dụng hơn nữa bằng cách sử dụng các thực thể kinh doanh và triển khai chúng cho các dịch vụ và nền tảng đám mây khác nhau. Về cốt lõi, JHipster là một trình tạo mã Yeoman tạo ra Spring Boot và Angular

- Mục tiêu của JHipster là cung cấp cho các nhà phát triển một nền tảng nơi bạn có thể tập trung vào business logic của mình thay vì lo lắng về việc kết nối các công nghệ khác nhau với nhau và cũng là một nền tảng cung cấp trải nghiệm tuyệt vời cho nhà phát triển.

💬 ***Cài đặt Jhipster*** 

1. Cài đặt và cấu hình Java 11 : [AdoptOpenJDK builds](https://adoptopenjdk.net/) (***jdk-11.0.14.1+1***)
2. Cài đặt Node.js từ [Node.js website](https://nodejs.org/) (***sử dụng phiên bản LTS 64-bit***)
3. Cài đặt Jhipster (cmd): __`npm install -g generator-jhipster`__
4. Cài đặt Yeoman (cmd): __`npm instal -g yo`__

\
💬 ***Khởi tạo dự án mới***

Thực hiện trên cmd:

1. Tạo thư mục lưu trữ dự án, gõ lệnh: __`mkdir Test`__
2. Di chuyển vào thư mục vừa tạo, gõ lệnh: __`cd Test`__
3. Tạo dự án mới, gõ lệnh: __`jhipster`__
4. Sau đó trả lời những câu hỏi để tạo một ứng dụng phù hợp với nhu cầu.

\
![new-jhipster](https://user-images.githubusercontent.com/106305844/173264237-3e4a4e8e-52c6-4f4a-8a57-7e6b43b13637.png)



>🚩 __Note:__ Đối với dự án có sẳn, cài đặt theo các sự lựa chọn sẳn có trong file __.yo-rc.json__ được đặt trong thư mục lưu trữ dự án.
>
>\
>![exits-yo-rc](https://user-images.githubusercontent.com/106305844/173264229-f3c55272-be1c-48ac-8272-620c07c0e587.png)
>
> 1. Di chuyển vào thư mục: __`cd Test`__
> 2. Gõ lệnh: __`jhipster`__
> 3. Ứng dụng sẽ được tạo và bạn sẽ có một project mới.

\
\
💬 ***Khởi chạy ứng dụng***

- Vẫn ở tại project, gõ lệnh: __`gradlew`__ hoặc __`gradlew.bat`__
- Quá trình có thể mất khá nhiều thời gian, do lần đầu thực hiện.
- Ứng dụng sẽ hiển thị trên: `http://localhost:8080`

\
![webapp-localhost](https://user-images.githubusercontent.com/106305844/173264216-658c9e27-dc25-4aa5-ba46-ce1415f85656.png)


> ✨  _Để chuyển hướng trang đăng nhập_

1. Mở file __`src\main\resources\config\application.yml`__:
    * Tìm dòng: __`issuer-uri: http://localhost:9080/auth/realms/jhipster`__
    * Đổi thành: __`issuer-uri: http://danquy.vnpthis.vn/auth/realms/bsgd`__ . Lưu lại

\
![url-login](https://user-images.githubusercontent.com/106305844/173264253-b7d1126f-d56f-4563-b86d-fa0d29027f2b.png)

2. Mở cmd di chuyển đến thư mục lưu trữ dự án, gõ lệnh: `gradlew.bat`
3. Ứng dụng hiển thị trên web: `http://localhost:8080`
4. Trang đăng nhập mong muốn:

\
![login](https://user-images.githubusercontent.com/106305844/173264233-59883c96-a15d-471a-9844-58e83c1b59f1.png)

\
\
💬 ***Tạo entity và thêm file JDL và dự án***

1. Tạo các entity trên [JDL-Studio](https://start.jhipster.tech/jdl-studio/), sau khi hoàn tất tải file về và lưu ở thư mục dự án
2. Mở cmd tại đường dẫn thư mục của dự án, gõ lệnh: __`jhipster jdl <name>.jdl`__
3. Quá trình build hoàn tất, tiếp tục gõ lệnh: __`gradlew.bat`__ để chạy lại ứng dụng web.
4. Mở `http://localhost:8080`, đăng nhập, nhấp chọn __Entities__ sẽ hiện ra những bảng đã được import vào.

\
![entities](https://user-images.githubusercontent.com/106305844/173264228-27685bae-92c5-4095-8553-ab053cec44f0.png)


\
\
💬 ***Chỉnh sửa file tiếng Việt***

- Giao diện Danh mục bệnh nhân
\
\
![benh-nhan](https://user-images.githubusercontent.com/106305844/173264220-a7644275-1a8d-4886-be64-3c0dc3256063.png)


- Giao diện Danh mục phiếu hẹn khám
\
\
![phieu-hen-kham](https://user-images.githubusercontent.com/106305844/173264239-faa2e64c-451c-4b40-9d4f-2440066f3736.png)

- Giao diện Danh mục hồ sơ bệnh án
\
\
![ho-so-benh-an](https://user-images.githubusercontent.com/106305844/173264230-51ce7a38-9055-410a-bf93-b88551938392.png)


- Giao diện Danh mục thống kê chi phí
\
\
![thong-ke-chi-phi](https://user-images.githubusercontent.com/106305844/173264247-c28211bb-c07e-4f10-b998-541ea4e5e545.png)


- Giao diện Danh mục thông tin khám chữa bệnh
\
\
![thong-tin-kcb](https://user-images.githubusercontent.com/106305844/173264248-d7e7dd7f-e31c-41c1-a5bf-5b6ed05ddd9f.png)


- Giao diện Danh mục phiếu xét nghiệm
\
\
![phieu-xet-nghiem](https://user-images.githubusercontent.com/106305844/173264242-22960850-b2b9-4bb6-bfa7-89ae1f5b6b57.png)


- Giao diện Danh mục phiếu chuẩn đoán hình ảnh
\
\
![phieu-cdha](https://user-images.githubusercontent.com/106305844/173264238-7a5a8756-442c-49d8-aefa-9f744827f040.png)

<br/>



## **II. Áp dụng Angular vào jhipster**

- Thư mục `src/main/java` sẽ chưa Java code.
- Thư mục `src/main/resources` chứa các tài nguyên tĩnh và các file cấu hình.
- Thư mục `src/main/webapp` là thư mục gốc cho giao diện người dùng.
- Thư mục `app` chứa các modules AngularJs
- Thư mục `src/main/webapp/i18n` chứa các file ngôn ngữ
- Thư mục `src/main/webapp/app/entities` chứa các bảng được import từ file JDL


___
<br/>

# **📖 BÁO CÁO THỰC TẬP TUẦN 4**
✨✨✨

>**Nhiệm Vụ**:
>
>- _Vẽ sơ đồ luồng các chức năng thêm, sửa, xóa phiếu hẹn khám_
>- _Tìm hiểu cấu trúc thư mục trong jhipster và ý nghĩa của từng tập tin trong đó_


\
💬 ***Các sơ đồ luồng***

- Sơ đồ luồng của chức năng **Thêm phiếu hẹn khám**

\
![FlowAddPhieuHenKham](https://user-images.githubusercontent.com/106305844/174708182-a995d311-4c13-4c2e-9e3c-e33a0df55716.png)

- Sơ đồ luồng chức năng **Xóa phiếu hẹn khám**

\
![FlowDeletePhieuHenKham](https://user-images.githubusercontent.com/106305844/174708191-cc9c257a-5737-4f88-8cbb-f4e37bf61f95.png)

- Sơ đồ luồng chức năng **Sửa phiếu hẹn khám**

\
![FlowEditPhieuHenKham](https://user-images.githubusercontent.com/106305844/174708193-fa8100cb-953f-4f99-91b6-8d0ed9fb649f.png)


\
💬 ***Mã nguồn java chính cho ứng dụng `src/main/java/com/mycompany/myapp`***

\
![cau-truc-source-java](https://user-images.githubusercontent.com/106305844/174707986-def2e99f-6837-47fb-9df4-868117b8f4b9.png)


```
java/com/mycompany/myapp
├── domain                                        - Lưu các Models/ Entites (BenhNhan, PhieuHenKham,..)
|	├── PhieuHenKham.java                     - Class đại diện cho thực thể phiếu hẹn khám
|	├── ...
├──	repository                                - Chứa các kho lưu trữ dữ liệu trong spring cho các thực thể
|	├── PhieuHenKhamRepository.java           - Tương tác với cở sở dữ liệu để tìm, thêm, sửa, xóa một PhieuHenKham
|	├── ...
├── service                                       - Dịch vụ quản lý các model/ thực thể (save, edit, ...)
|	├── PhieuHenKhamService.java		
|	├──
├── web									
|	├── rest                                  - Gói này chứa các lớp tài nguyên Spring cho REST API (dùng để giao tiếp giữa client và server)
|		├── PhieuHenKhamResource.java	  - Chứa request và method của PhieuHenKham
```

💬 ***Cấu trúc Angular***

\
![cau-truc-angular](https://user-images.githubusercontent.com/106305844/174708263-ad609559-d52e-4b78-ad5e-8505f2f7fe56.png)

\
💬 **Ý nghĩa các file của chức năng Thêm phiếu hẹn khám**

- Khi người dùng nhấn vào nút thêm phiếu hẹn tại trang Phiếu hẹn khám:

\
![angular-phieu-hen-kham](https://user-images.githubusercontent.com/106305844/174708290-75826dfb-debd-478e-8e35-dcb6cc31b7d6.png)

\
💫 ___phieu-hen-kham.component.html___ 💫

- Là giao diện chính của **Quản lý Phiếu hẹn khám**. Tại đây giá trị của thuộc tính **`[routerLink]` là `['/phieu-hen-kham/new']`**, giá trị này sẽ là định tuyến làm đường dẫn cho các component.

\
![routeLink](https://user-images.githubusercontent.com/106305844/174708363-36132db7-0764-4a25-8de1-3278d6fc592f.png)

\
💫 ___phieu-hen-kham-routing.module.ts___ 💫
 
- Là nơi mà các **Route** ứng dụng được khai báo. **Path** : Khai báo đường dẫn đến một component.
- Đường dẫn **`[routerLink]="['/phieu-hen-kham/new']`** thì component PhieuHenKhamUpdateComponent sẽ được biểu diễn.

\
![route-new](https://user-images.githubusercontent.com/106305844/174708527-0addf84f-0fc3-4ad2-89c8-c015d746d577.png)

\
💫 ___phieu-hen-kham-update.component.html___ 💫

- Là giao diện của from thêm mới phiếu hẹn.

\
![phieu-hen-kham-update-component-html](https://user-images.githubusercontent.com/106305844/174708569-e2a3ee0e-100d-42fc-8d61-af9e027105c7.png)

- Người dùng nhập thông tin hẹn khám và nhấn lưu.
- Tại **phieu-hen-kham-update.component.html** phương thức **(ngSubmit)="save()"**  sự kiện **save()** được thực thi khi người dùng ấn nút lưu.

\
![](../HinhAnh/nf.PNG)

\
💫 ___phieu-hen-kham-update.component.ts___ 💫

- Nơi lưu trữ các hàm xử lý sự kiện.
- Sự kiện **save()** để lưu thông tin đối tượng 
- Thực hiện tạo mới, kiểm tra **`id`** truyền vào chưa tồn tại nên thực thi hàm **create(phieuHenKham)** có tham số là phieuHenKham.

\
![](../HinhAnh/111.PNG)

\
💫 ___phieu-hen-kham.service.ts___ 💫

- Là file dịch vụ và phương thức cho chức năng phiếu hẹn khám
- Hàm **create()** sử dụng phương thức **POST** và dịch vụ **HTTP** để khởi tạo 1 URL.

\
![](../HinhAnh/pt.PNG)

\
💫 ___PhieuHenKhamResource.java___ 💫

- Là các bộ điều khiển REST để quản lý Phiếu Hẹn Khám
- Có các phương thức đại diện cho các request (GET, POST, PUT, DELETE)
- **`@RestController`** : chú thích xác định đây là lớp controller

- Từ client gọi API của phương thức POST đã khởi tạo trước đó đến file `src\main\java\com\mycompany\myapp\web\rest\PhieuHenKhamResource.java`
- **`@RequestMapping("/api")`** : chỉ định đường dẫn để biết là gửi request đến controller này để yêu cầu method.
- **`@PostMapping("/phieu-hen-khams")`**: định tuyến method POST, sử dụng hàm `createPhieuHenKham()` để yêu cầu tạo một __PhieuHenKham__
- **`phieuHenKhamService.save()`**: lưu lại đối tượng __PhieuHenKham__ vừa tạo
- **`.created(new  URI("/api/phieu-hen-khams/"  +  result.getId())):`** tạo đường dẫn đến đối tượng __PhieuHenKham__ vừa tạo.

\
![phieu-hen-kham-resource](https://user-images.githubusercontent.com/106305844/174708714-9e6d1426-0a13-42b0-bcf0-30569e8d5958.png)

> ⇒ Trả kết quả gọi đến **`@Repository`** để yêu cầu tạo thực thể __PhieuHenKham__

\
💫 ___PhieuHenKhamRepository.java___ 💫

- Kho lưu trữ dữ liệu của thực thể **PhieuHenKham**
- Chú thích **`@Repository`** xác định đây là kho lưu trữ và làm việc với dữ liệu

- Gọi đến kho lưu trữ dữ liệu của PhieuHenKham **`src\main\java\com\mycompany\myapp\repository\PhieuHenKhamRepository.java`** để yêu cầu khởi tạo dữ liệu cho thực thể PhieuHenKham
- Kế thừa từ **`JpaRepository`** cho phép thực hiện hoạt động ***thêm PhieuHenKham***

\
![phieu-hen-kham-repository](https://user-images.githubusercontent.com/106305844/174708741-991ae99b-7088-4c59-a54f-51132762e639.png)

> ⇒ Thực hiện yêu cầu thêm mới một đối tượng **PhieuHenKham** thông qua lớp đại diện cho thực thể __PhieuHenKham__

\
💫 ___PhieuHenKham.java___ 💫

- Thông qua lớp **`src\main\java\com\mycompany\myapp\domain\PhieuHenKham.java`** khởi tạo đối tượng PhieuHenKham
- Đây là lớp đại diện cho thực thể **PhieuHenKham**
- Có các chú thích (_annotation_)
  + **`@Entity`** :  đánh dấu lớp này là thực thể,
  + **`@Table(name  =  "phieu_hen_kham")`**:  ánh xạ đến bảng `phieu_hen_kham` trong cơ sở dữ liệu,
  + **`@Cache(usage  =  CacheConcurrencyStrategy.READ_WRITE)`**:  khai báo entity có thể cache (cơ chế truy cập đồng thời),
  + **`@Id`**: chú thích xác định khóa chính,
  + **`@NotNull`,`@Column`**: xác định cột và cột không được rỗng.
- Có các thuộc tính là các trường của thực thể, phương thức **set()** để thêm  giá trị của các trường và hàm xây dựng tạo đối tượng **PhieuHenKham**.

\
![phieu-hen-kham-entity](https://user-images.githubusercontent.com/106305844/174708756-ca01971d-3878-44f6-b37e-94fdc4bb38be.png)

> ⇒ Tạo mới một đối tượng **PhieuHenKham** lưu vào bảng **`phieu_hen_kham`** trong cơ sở dữ liệu.


\
💫 ___phieu-hen-kham.component.ts___ 💫

- Thực thi hàm **loadAll()** gọi hàm **query()** yêu cầu lấy thông tin Phiếu hẹn khám.

\
![loadAll](https://user-images.githubusercontent.com/106305844/174708791-803229cb-8440-40bc-8000-7242a397965e.png)

\
💫 ___phieu-hen-kham.service.ts___ 💫

- Thực thi hàm **query()** với phương thức **get** và dịch vụ **HTTP** để tạo URL lấy thông tin Phiếu hẹn khám.

\
![angular-get](https://user-images.githubusercontent.com/106305844/174708816-1f287ea7-ba80-4fa9-9e2f-0edd51e1d188.png)

\
💫 ___PhieuHenKhamResource.java___ 💫

- Hàm query() ở client tạo URL API của phương thức GET gọi đến file **`src\main\java\com\mycompany\myapp\web\rest\PhieuHenKhamResource.java`**
- **`@RestController`** : chú thích xác định đây là lớp controller
- **`@RequestMapping("/api")`** : chỉ định đường dẫn để biết là gửi request đến controller này để yêu cầu method.
- **`@GetMapping("/phieu-hen-khams")`**: định tuyến method GET (theo cách hàm query() gọi, không có lấy tìm theo 'id'), thực thi hàm **`getAllPhieuHenKhams`** để yêu cầu lấy thông tin tất cả __PhieuHenKham__
- **`phieuHenKhamService.findAll()`**: để tìm kiếm tất cả dữ liệu của __PhieuHenKham__

\
![phieu-hen-kham-resource-getmapping](https://user-images.githubusercontent.com/106305844/174708880-904a8a07-289a-43e2-b7ec-cbcb4427d3ae.png)

> ⇒ Thông tin tìm được sẽ lưu thành một danh sách và phản hồi lại cho client.


___
<br/>

# **📖 BÁO CÁO THỰC TẬP TUẦN 5, 6**
✨✨✨

## **1. Domain**

💫 ___PhieuHenKham.java___ 💫

```java
@Entity
@Table(name = "phieu_hen_kham")
@Cache(usage = CacheConcurrencyStrategy.READ_WRITE)
public class PhieuHenKham implements Serializable {

    private static final long serialVersionUID = 1L;

    @Id
    @GeneratedValue(strategy = GenerationType.SEQUENCE, generator = "sequenceGenerator")
    @SequenceGenerator(name = "sequenceGenerator")
    @Column(name = "id")
    private Long id;

    @NotNull
    @Enumerated(EnumType.STRING)
    @Column(name = "loai_kham", nullable = false)
    private LoaiKham loaiKham;

    @NotNull
    @Column(name = "ngay_hen", nullable = false)
    private Instant ngayHen;

    @NotNull
    @Column(name = "co_so_kham", nullable = false)
    private String coSoKham;

    @Column(name = "bac_si")
    private String bacSi;

    @Column(name = "noi_dung")
    private String noiDung;

    @ManyToOne
    @JsonIgnoreProperties(value = { "phieuHenKhams", "hoSoBenhAns" }, allowSetters = true)
    private BenhNhan benhnhan;

    //Getter, setter...
```

- Một __`@Entity`__ (domain) là nơi ánh xạ của một bảng (__PhieuHenKham__) từ cơ sở dữ liệu vào Java, với __`@Table(name = "phieu_hen_kham")`__ là tên của bảng được ánh xạ.
- Các annotation (chú thích):
  + __`@Id`__ định nghĩa trường id tương ứng với cơ sơ dữ liệu và gán giá trị __`@GeneratedValue`__ tự động tăng cho trường id đó.
  + __`@Column(name = "tencotdb")`__ tên cột của DB được ánh xạ tương ứng với tên trong Java. Thuộc tính ___`nullable = false`___ và __`@NotNull`__ không cho phép giá trị của cột đó Null.
  + __`@Enumerated(EnumType.STRING)`__ chú thích trường này sẽ sử dụng một enum đã được định nghĩa sẳn làm giá trị, và giá trị đó có kiểu String.
- Mối quan hệ __`@ManyToOne`__, khóa ngoại sẽ được thể hiện thông qua việc entity __PhieuHenKham__ chứa entity __BenhNhan__. Có nghĩa là bảng _phieu-hen-kham_ có chứa khóa ngoại được tham chiếu từ bảng _benhnhan_.
- __`@JsonIgnoreProperties`__ đánh dấu thuộc tính sẽ bị bỏ qua trong quá trình biên dịch khởi tạo và gán giá trị (___phieuHenKhams, hoSoBenhAns___).
- Có các __`getter`__ và __`setter`__ để tương tác với các thuộc tính private nhằm đảm bảo tính đóng gói(1) của OOP, tránh tình trạng dữ liệu hư hỏng ngoài ý muốn.

> __Tính đóng gói (Encapsulation):__ cho phép private các thuộc tính bên trong đối tượng, đối tượng khác chỉ có thể tác động đến các thuộc tính đó thông qua các phương thức public đã được chính đối tượng đó định nghĩa.


## **2. Repository**

💫 ___PhieuHenKhamRepository.java___ 💫

```java
/**
 * Spring Data SQL repository for the PhieuHenKham entity.
 */
@SuppressWarnings("unused")
@Repository
public interface PhieuHenKhamRepository extends JpaRepository<PhieuHenKham, Long>, JpaSpecificationExecutor<PhieuHenKham> {}

```
- Repository là một interface được định nghĩa __`@Repository`__, là nơi lưu trữ  và truy xuất dữ liệu giữa cơ sở dữ liệu và entity (ở đây là __PhieuHenKham__).
- Là một lớp interface kế thừa từ __`JpaRepository`__ cho phép thực hiện các __CRUD__ (create, read, update, delete) cơ bản.
- Hỗ trợ tạo các query từ các method của JPA, ví dụ:

```java
Optional<PhieuHenKham> findByBenhNhan(BenhNhan benhNhan)
```

==> Được hiểu như:
\
__`select * from PhieuHenKham phk where phk.BenhNhan = benhNhan`__ 

> 🚩 Nếu dữ liệu trả về có thể là duy nhất hoặc không tồn tại thì hứng bằng __Optional__.


## **3. DTO**

- __DTO (Data Transfer Object):__ là các class đóng gói data để chuyển giữa client - server hoặc giữa các service trong microservice.
- Mục đích tạo ra DTO là để giảm bớt lượng thông tin không cần thiết phải chuyển đi, chỉ gửi đi những gì mà người dùng yêu cầu, nhằm ___tăng cường độ bảo mật___.
- Việc tạo ra một lớp DTO có thể có hoặc không thông qua việc khai báo DTO trong file __`tenjdl.jdl`__
```
dto all with mapstruct (với all là tất cả entity)
```
- DTO tương ứng với entity, nhưng khác ở chỗ khóa ngoại sẽ không phải tên của entity làm khóa ngoại, mà thay bằng tên trường id của entity khóa ngoại đó. Sẽ không còn là các entity lồng nhau nữa.

💫 ___PhieuHenKhamDTO.java___ 💫

```java
...

/**
* Mã bệnh nhân
*/
@ApiModelProperty(value = "Mã bệnh nhân")
private Long benhNhanId;

...
```
- Repository của Spring sẽ hiểu được các khóa ngoại id này thông qua __Mapper__

## **4. Mapper(Mapstruct)**

- __Mapstruct__ là một interface thường dùng để map các thuộc tính của các object lại với nhau
- Nếu sử dụng DTO thì sử dụng mapper để map thuộc tính của entity và DTO của entity đó.


## **5. Criteria**

- __Criteria__ là 1 class sử dụng thư viện criteria do jhipster hỗ trợ. Các thuộc tính sẽ tương ứng với các thuộc tính trong DTO nhưng kiểu dữ liệu sẽ kèm theo Filer ví dụ: __`Long = LongFilter`__
- Các filter này sẽ hỗ trợ việc lọc theo một hoặc nhiều điều kiện được thuận tiện dễ dàng hơn. Như `equals, contains(LongFilter)...` các thuộc tính này sẽ được sử dụng trong phần __`createSpecification`__ ở trong __PhieuHenKhamQueryService__

💫 ___PhieuHenKhamCriteria.java___ 💫

```java
public class PhieuHenKhamCriteria implements Serializable, Criteria {

private static final long serialVersionUID = 1L;

    private LongFilter id;

    private LoaiKhamFilter loaiKham;

    private InstantFilter ngayHen;

    private StringFilter coSoKham;

    private StringFilter bacSi;

    private StringFilter noiDung;

    private LongFilter benhnhanId;

    private Boolean distinct;

    public PhieuHenKhamCriteria() {}

    public PhieuHenKhamCriteria(PhieuHenKhamCriteria other) {
        this.id = other.id == null ? null : other.id.copy();
        this.loaiKham = other.loaiKham == null ? null : other.loaiKham.copy();
        this.ngayHen = other.ngayHen == null ? null : other.ngayHen.copy();
        this.coSoKham = other.coSoKham == null ? null : other.coSoKham.copy();
        this.bacSi = other.bacSi == null ? null : other.bacSi.copy();
        this.noiDung = other.noiDung == null ? null : other.noiDung.copy();
        this.benhnhanId = other.benhnhanId == null ? null : other.benhnhanId.copy();
        this.distinct = other.distinct;
    }

}
```

## **6. QueryService**

- Trong QueryService sẽ có một hàm __`createSpecification`__, Specification là phần điều kiện phía sau `where` trong query.
- `Specification<PhieuHenKham>` sẽ được sử dụng trong `Repository` với hàm  `findAll()`.

💫 ___PhieuHenKhamQueryService.java___ 💫

```java
public class PhieuHenKhamQueryService extends QueryService<PhieuHenKham> {

protected Specification<PhieuHenKham> createSpecification(PhieuHenKhamCriteria criteria) {
        Specification<PhieuHenKham> specification = Specification.where(null);
        if (criteria != null) {
            // This has to be called first, because the distinct method returns null
            if (criteria.getDistinct() != null) {
                specification = specification.and(distinct(criteria.getDistinct()));
            }
            if (criteria.getId() != null) {
                specification = specification.and(buildRangeSpecification(criteria.getId(), PhieuHenKham_.id));
            }
            if (criteria.getLoaiKham() != null) {
                specification = specification.and(buildSpecification(criteria.getLoaiKham(), PhieuHenKham_.loaiKham));
            }
            if (criteria.getNgayHen() != null) {
                specification = specification.and(buildRangeSpecification(criteria.getNgayHen(), PhieuHenKham_.ngayHen));
            }
            if (criteria.getCoSoKham() != null) {
                specification = specification.and(buildStringSpecification(criteria.getCoSoKham(), PhieuHenKham_.coSoKham));
            }
            if (criteria.getBacSi() != null) {
                specification = specification.and(buildStringSpecification(criteria.getBacSi(), PhieuHenKham_.bacSi));
            }
            if (criteria.getNoiDung() != null) {
                specification = specification.and(buildStringSpecification(criteria.getNoiDung(), PhieuHenKham_.noiDung));
            }
            if (criteria.getBenhnhanId() != null) {
                specification =
                    specification.and(
                        buildSpecification(
                            criteria.getBenhnhanId(),
                            root -> root.join(PhieuHenKham_.benhnhan, JoinType.LEFT).get(BenhNhan_.id)
                        )
                    );
            }
        }
        return specification;
    }

}
```

## **7. Service**

- Quản lý dịch vụ thêm, sửa, xóa, tìm kiếm.
  + **save()**: dấu chú thích nội dung `@param` và `@return`, có tác dụng chú thích dữ liệu được lấy ở đâu và trả về ở đâu.
  + **update()**: cập nhật một ___`PhieuHenKham`___
  + **findAll()**: tìm tất cả phieuHenKham, trả về 1 danh sách lưu trong giao diện phân trang
  + **findOne()**: tìm 1 phieuHenKham theo id, **`Optional`** cho phép nhận kết quả trả về null nếu như id đó không tồn tại.
  

💫 ___PhieuHenKhamService.java___ 💫

```java
public interface PhieuHenKhamService {
    /**
     * Save a phieuHenKham.
     *
     * @param phieuHenKham the entity to save.
     * @return the persisted entity.
     */
    PhieuHenKham save(PhieuHenKham phieuHenKham);

    /**
     * Updates a phieuHenKham.
     *
     * @param phieuHenKham the entity to update.
     * @return the persisted entity.
     */
    PhieuHenKham update(PhieuHenKham phieuHenKham);

    /**
     * Partially updates a phieuHenKham.
     *
     * @param phieuHenKham the entity to update partially.
     * @return the persisted entity.
     */
    Optional<PhieuHenKham> partialUpdate(PhieuHenKham phieuHenKham);

    /**
     * Get all the phieuHenKhams.
     *
     * @param pageable the pagination information.
     * @return the list of entities.
     */
    Page<PhieuHenKham> findAll(Pageable pageable);

    /**
     * Get the "id" phieuHenKham.
     *
     * @param id the id of the entity.
     * @return the entity.
     */
    Optional<PhieuHenKham> findOne(Long id);

    /**
     * Delete the "id" phieuHenKham.
     *
     * @param id the id of the entity.
     */
    void delete(Long id);
}
```

## **8. ServiceImpl**

- Thực hiện các nghiệp vụ thêm, sửa, xóa.
- **`@Service`** : đánh dấu lớp phục vụ cho các logic nghiệp vụ.
- **`@Transactional`** : đánh dấu một giao dịch, để khi thực hiện xảy ra lỗi thì transaction này sẽ rollback lại để bảo toàn dữ liệu
- **`@Override`** : ghi đè dữ liệu
- **`PhieuHenKham save()`** : lưu trữ dữ liệu của phieuHenKham

💫 ___PhieuHenKhamServiceImpl.java___ 💫

```java
@Service
@Transactional
public class PhieuHenKhamServiceImpl implements PhieuHenKhamService {

public PhieuHenKhamServiceImpl(PhieuHenKhamRepository phieuHenKhamRepository) {
        this.phieuHenKhamRepository = phieuHenKhamRepository;
    }

    @Override
    public PhieuHenKham save(PhieuHenKham phieuHenKham) {
        log.debug("Request to save PhieuHenKham : {}", phieuHenKham);
        return phieuHenKhamRepository.save(phieuHenKham);
    }

    @Override
    public PhieuHenKham update(PhieuHenKham phieuHenKham) {
        log.debug("Request to save PhieuHenKham : {}", phieuHenKham);
        return phieuHenKhamRepository.save(phieuHenKham);
    }

    @Override
    public Optional<PhieuHenKham> partialUpdate(PhieuHenKham phieuHenKham) {
        log.debug("Request to partially update PhieuHenKham : {}", phieuHenKham);

        return phieuHenKhamRepository
            .findById(phieuHenKham.getId())
            .map(existingPhieuHenKham -> {
                if (phieuHenKham.getLoaiKham() != null) {
                    existingPhieuHenKham.setLoaiKham(phieuHenKham.getLoaiKham());
                }
                if (phieuHenKham.getNgayHen() != null) {
                    existingPhieuHenKham.setNgayHen(phieuHenKham.getNgayHen());
                }
                if (phieuHenKham.getCoSoKham() != null) {
                    existingPhieuHenKham.setCoSoKham(phieuHenKham.getCoSoKham());
                }
                if (phieuHenKham.getBacSi() != null) {
                    existingPhieuHenKham.setBacSi(phieuHenKham.getBacSi());
                }
                if (phieuHenKham.getNoiDung() != null) {
                    existingPhieuHenKham.setNoiDung(phieuHenKham.getNoiDung());
                }

                return existingPhieuHenKham;
            })
            .map(phieuHenKhamRepository::save);
    }

    @Override
    @Transactional(readOnly = true)
    public Page<PhieuHenKham> findAll(Pageable pageable) {
        log.debug("Request to get all PhieuHenKhams");
        return phieuHenKhamRepository.findAll(pageable);
    }

    @Override
    @Transactional(readOnly = true)
    public Optional<PhieuHenKham> findOne(Long id) {
        log.debug("Request to get PhieuHenKham : {}", id);
        return phieuHenKhamRepository.findById(id);
    }

    @Override
    public void delete(Long id) {
        log.debug("Request to delete PhieuHenKham : {}", id);
        phieuHenKhamRepository.deleteById(id);
    }

}

```

## **9. Resource (Controller)**

- **`@RestController`**: đánh dấu lớp chứa các bộ điều khiển REST để quản lý PhieuHenKham.
- Có các phương thức đại diện cho các request (GET, POST, PUT, DELETE).
- **`@RequestMapping("/api")`** : đinh tuyến đường dẫn chung đến lớp thực hiện các request.
- **`@PostMapping("/phieu-hen-khams")`**: định tuyến sử dụng phương thức POST áp dụng cho __phieu-hen-khams__
- **`@PutMapping("/phieu-hen-khams/{id}")`**: định tuyến sử dụng phương thức PUT áp dụng cho __phieu-hen-khams__ với __`id`__ được truyền vào 


💫 __PhieuHenKhamResource.java__ 💫

```java
@RestController
@RequestMapping("/api")
public class PhieuHenKhamResource {

    private final Logger log = LoggerFactory.getLogger(PhieuHenKhamResource.class);

    private static final String ENTITY_NAME = "phieuHenKham";

    @Value("${jhipster.clientApp.name}")
    private String applicationName;

    private final PhieuHenKhamService phieuHenKhamService;

    private final PhieuHenKhamRepository phieuHenKhamRepository;

    private final PhieuHenKhamQueryService phieuHenKhamQueryService;

    public PhieuHenKhamResource(
        PhieuHenKhamService phieuHenKhamService,
        PhieuHenKhamRepository phieuHenKhamRepository,
        PhieuHenKhamQueryService phieuHenKhamQueryService
    ) {
        this.phieuHenKhamService = phieuHenKhamService;
        this.phieuHenKhamRepository = phieuHenKhamRepository;
        this.phieuHenKhamQueryService = phieuHenKhamQueryService;
    }

    /**
     * {@code POST  /phieu-hen-khams} : Create a new phieuHenKham.
     *
     * @param phieuHenKham the phieuHenKham to create.
     * @return the {@link ResponseEntity} with status {@code 201 (Created)} and with body the new phieuHenKham, or with status {@code 400 (Bad Request)} if the phieuHenKham has already an ID.
     * @throws URISyntaxException if the Location URI syntax is incorrect.
     */
    @PostMapping("/phieu-hen-khams")
    public ResponseEntity<PhieuHenKham> createPhieuHenKham(@Valid @RequestBody PhieuHenKham phieuHenKham) throws URISyntaxException {
        log.debug("REST request to save PhieuHenKham : {}", phieuHenKham);
        if (phieuHenKham.getId() != null) {
            throw new BadRequestAlertException("A new phieuHenKham cannot already have an ID", ENTITY_NAME, "idexists");
        }
        PhieuHenKham result = phieuHenKhamService.save(phieuHenKham);
        return ResponseEntity
            .created(new URI("/api/phieu-hen-khams/" + result.getId()))
            .headers(HeaderUtil.createEntityCreationAlert(applicationName, true, ENTITY_NAME, result.getId().toString()))
            .body(result);
    }

    /**
     * {@code PUT  /phieu-hen-khams/:id} : Updates an existing phieuHenKham.
     *
     * @param id the id of the phieuHenKham to save.
     * @param phieuHenKham the phieuHenKham to update.
     * @return the {@link ResponseEntity} with status {@code 200 (OK)} and with body the updated phieuHenKham,
     * or with status {@code 400 (Bad Request)} if the phieuHenKham is not valid,
     * or with status {@code 500 (Internal Server Error)} if the phieuHenKham couldn't be updated.
     * @throws URISyntaxException if the Location URI syntax is incorrect.
     */
    @PutMapping("/phieu-hen-khams/{id}")
    public ResponseEntity<PhieuHenKham> updatePhieuHenKham(
        @PathVariable(value = "id", required = false) final Long id,
        @Valid @RequestBody PhieuHenKham phieuHenKham
    ) throws URISyntaxException {
        log.debug("REST request to update PhieuHenKham : {}, {}", id, phieuHenKham);
        if (phieuHenKham.getId() == null) {
            throw new BadRequestAlertException("Invalid id", ENTITY_NAME, "idnull");
        }
        if (!Objects.equals(id, phieuHenKham.getId())) {
            throw new BadRequestAlertException("Invalid ID", ENTITY_NAME, "idinvalid");
        }

        if (!phieuHenKhamRepository.existsById(id)) {
            throw new BadRequestAlertException("Entity not found", ENTITY_NAME, "idnotfound");
        }

        PhieuHenKham result = phieuHenKhamService.update(phieuHenKham);
        return ResponseEntity
            .ok()
            .headers(HeaderUtil.createEntityUpdateAlert(applicationName, true, ENTITY_NAME, phieuHenKham.getId().toString()))
            .body(result);
    }
```


## **10. Swagger**
- __Swagger__ là một bộ công cụ mã nguồn mở để xây dựng OpenAPI specifications giúp chúng ta có thể thiết kế, xây dựng tài liệu và sử dụng REST APIs.
Swagger cung cấp 3 tools chính cho các developers :

  + __Swagger-Editor:__ dùng để design lên các APIs hoàn toàn mới hoặc edit lại các APIs có sẵn thông qua 1 file config.
  + __Swagger-Codegen:__ dùng để generate ra code từ các file config có sẵn
  + __Swagger-UI:__ dùng để generate ra file html,css,… từ 1 file config.
- Một file swagger có thể viết bằng JSON hoặc YAML.
  + __Metadata:__ Mọi thông số kỹ thuật của Swagger đều bắt đầu với phiên bản Swagger . Phiên bản Swagger xác định cấu trúc tổng thể của đặc tả API - những gì bạn có thể ghi lại và cách bạn ghi lại nó. Ngoài ra các thông tin chi tiết như tiêu đề, mô tả hay version của bản api hiện tại cũng được khai báo tại đây.
  + __Base Url:__ Nơi bạn sẽ định nghĩa host của server, đường dẫn cơ bản cũng như giao thức https hoặc http.
  + __Paths:__ xác định các điểm cuối riêng lẻ (đường dẫn) trong API của bạn và các phương thức HTTP (hoạt động) được hỗ trợ bởi các điểm cuối này. Và đây là phần quan trọng chứa thông tin API của bạn sẽ như thế nào bằng đường dẫn API, phương thức (GET, POST, PUT...), request (query, path, body..), response API.


## **11. Chỉnh sửa giao diện và một số chức năng**

### **11.1 : Giao diện Trang chủ của ứng dụng**

\
![InterfaceHome](https://user-images.githubusercontent.com/106305844/178146847-0bad6d9c-2ff5-4c9a-9937-a404d190d7b0.png)

### **11.2 : Giao diện Thông tin bệnh nhân**

\
![InterfaceBenhNhan](https://user-images.githubusercontent.com/106305844/178146839-84424f59-af2e-448d-a8d0-dd555e16ca4b.png)

### **11.3 : Giao diện Đăng ký hẹn khám**

\
![InterfaceDKHK](https://user-images.githubusercontent.com/106305844/178146843-b48169e3-f0b5-4050-b761-9a1351d8a227.png)

### **11.4 : Giao diện lLịch sử hẹn khám**

\
![InterfaceLSHK](https://user-images.githubusercontent.com/106305844/178146852-0a9d93f1-6027-4dfe-9df1-91d70d558565.png)

### **11.5 : Giao diện Lịch sử điều trị**

\
![InterfaceLSDT](https://user-images.githubusercontent.com/106305844/178146851-84084991-977d-4e52-a174-7d71a1e646eb.png)

### **11.6 : Giao diện Thống kê chi phí**

\
![InterfaceThongKeChiPhi](https://user-images.githubusercontent.com/106305844/178146854-037b8dee-05af-4086-8308-a19af58bc1bf.png)

### **11.7 : Giao diện Thông tin điều trị**

\
![InterfaceTTKCB](https://user-images.githubusercontent.com/106305844/178146835-5f7df99d-2c2d-4b2d-bd1f-fa3dd665ad77.png)


### **11.8 : Giao diện Tra cứu xét nghiệm**

\
![InterfacePXN](https://user-images.githubusercontent.com/106305844/178146853-76130976-e2b7-454f-a535-dbeac0f2971e.png)

### **11.9 : Giao diện Tra cứu CĐHA**

\
![InterfaceCDHA](https://user-images.githubusercontent.com/106305844/178146841-4ba38f40-3c40-4868-a29d-2fdef585b628.png)


___

# **📖 BÁO CÁO THỰC TẬP TUẦN 7**
✨✨✨

>**Nhiệm Vụ**:
>
>- _Tiếp tục hoàn thiện các chức năng_
>- _Viết test case_


## **I. Công việc hoàn thiện giao diện, chức năng**

### **1 :Giao diện Thông tin bệnh nhân**

\
![ResultTTBN](https://user-images.githubusercontent.com/106305844/178147382-b0c072a3-b529-4dab-b592-5225d54f0d34.png)

Hoàn thiện giao diện xem thông tin bệnh nhân . Thông tin bệnh nhân được với mỗi tài khoản mỗi bệnh nhân theo tài khoản được đăng kí. Sửa thông tin bệnh nhân.

### **2 :Giao diện đăng kí hẹn khám**

\
![ResultDKHK](https://user-images.githubusercontent.com/106305844/178147384-d7bdbbaa-a82d-4374-8087-cd5a598d3c52.png)

Bệnh nhân có thể đăng kí hẹn khám trước với bệnh viện. Các trường có dấu * là bắt buộc không được để trống

### **3 :Giao diện Lịch sử hẹn khám**

\
![ResultLSDKHK](https://user-images.githubusercontent.com/106305844/178147386-a4428fd3-a115-47be-b6d6-88113c159631.png)

Bệnh nhân có thể xem lại lịch sử đăng kí hẹn khám. Có thể sửa hoặc xóa phiếu hẹn khám.

### **4 : Giao diện Lịch sử khám/điều trị**

\
![ResultLSKDT](https://user-images.githubusercontent.com/106305844/178147388-51476fdc-600f-4d18-b1fa-fef72d53543c.png)

- Bệnh nhân xem được lịch sử khám và điều trị của mình, xem chi tiết hồ sơ bệnh án.
- Bệnh nhân có thể nhập mã vào ô **Mã bệnh án** và ấn nút tìm kiếm để tìm hồ sơ bệnh án.
- Nếu ô tìm kiếm trống mà ấn nút ___Tìm kiếm___ thì sẽ hiện ra toàn bộ danh sách bệnh án của bệnh nhân.

### **5: Giao diện thống kê chi phí**

\
![ResultTKCP](https://user-images.githubusercontent.com/106305844/178147391-901d9f28-a2f6-4487-ae1f-ab2833dab1ec.png)

Xem chi phí khám chữa bệnh


### **6 :Giao diện tra cứu xét nghiệm**

\
![ResultTCXN](https://user-images.githubusercontent.com/106305844/178147390-20743f07-3c34-4654-aa4b-22abac5e08c3.png)

- Bệnh nhân xem được phiếu xét nghiệm của mình, xem chi tiết phiếu.
- Bệnh nhân có thể nhập mã vào ô **Mã phiếu** và ấn nút tìm kiếm để tìm phiếu xét nghiệm.
- Nếu ô tìm kiếm trống mà ấn nút ___Tìm kiếm___ thì sẽ hiện ra toàn bộ danh sách phiếu xét nghiệm của bệnh nhân.

### **7 :Giao diện tra cứu CDHA**

\
![ResultCDHA](https://user-images.githubusercontent.com/106305844/178147383-c6465364-77be-460c-858c-024e5ff380a6.png)

- Bệnh nhân xem được phiếu chuẩn đoán hình ảnh của mình, xem chi tiết phiếu.
- Bệnh nhân có thể nhập mã vào ô **Mã phiếu** và ấn nút tìm kiếm để tìm phiếu chuẩn đoán hình ảnh.
- Nếu ô tìm kiếm trống mà ấn nút ___Tìm kiếm___ thì sẽ hiện ra toàn bộ danh sách phiếu chuẩn đoán hình ảnh của bệnh nhân.


## **II. Kiểm thử chức năng (Test case)**

<br/>

> **Note:** Các chức năng được kiểm thử với tiền điều kiện là đã đăng nhập với tài khoản bệnh nhân thành công.


### 💫 ___1. Kiểm thử chức năng Xem thông tin cá nhân___ 💫

| **Tên trường** | **Giá trị** |
|------:|:-----|
| Test Case ID: | TC_BN_001 |
| Test Title: | Kiểm tra hiển thị thông tin một bệnh nhân |
| Description: | Lấy đúng dữ liệu của bệnh nhân được lưu và hiển thị ra thông tin |

<br/>

| **Bước** | **Bước kiểm thử** | **Kết quả mong đợi** | **Kết quả thực tế** | **Trạng thái (Pass/Fail)** | **Ngày kiểm thử** |
|:-----:|:-----|:-----|:-----|:-----|:-----|
|1|Vào trang chủ|Thành công vào trang chủ|Như mong đợi|Pass||
|2|Chọn menu chứ năng ___Thông tin bệnh nhân___|Hiển thị thông tin bệnh nhân|Như mong đợi|Pass||

### 💫 ___2. Kiểm thử chức năng Sửa thông tin cá nhân___ 💫

| **Tên trường** | **Giá trị** |
|------:|:-----|
| Test Case ID: | TC_BN_002 |
| Test Title: | Kiểm tra sửa đổi thông tin một bệnh nhân |
| Description: | Cập nhật lại thông tin bệnh nhân |

<br/>

| **Bước** | **Bước kiểm thử** | **Kết quả mong đợi** | **Kết quả thực tế** | **Trạng thái (Pass/Fail)** | **Ngày kiểm thử** |
|:-----:|:-----|:-----|:-----|:-----|:-----|
|1|Vào trang chủ|Thành công vào trang chủ|Như mong đợi|Pass||
|2|Chọn menu chứ năng ___Thông tin bệnh nhân___|Hiển thị thông tin bệnh nhân|Như mong đợi|Pass||
|3|Chọn nút ___Sửa thông tin___|Hiển thị form sửa thông tin|Như mong đợi|Pass||
|4|Nhấn nút __Hủy__|Quay lại trang thông tin|Như mong đợi|Pass||
|5|Chọn nút ___Sửa thông tin___|Hiển thị form sửa thông tin|Như mong đợi|Pass||
|6|Nhập dữ liệu trường ID|Không thể nhập|Như mong đợi|Pass||
|7|Để trống trường __"Họ Tên"__|Nút lưu bị vô hiệu hóa|Như mong đợi|Fail||
|8|Nhập chữ cái, hoặc để trống tại trường __"Ngày Sinh"__`|Nút lưu bị vô hiệu hóa|Như mong đợi|Fail||
|9|Đầy đủ trường cần thay đổi và đúng kiểu dữ liệu|Có thể nhập và nút lưu được tác động|Như mong đợi|Pass||
|10|Nhấn nút __Lưu__|Thông báo thông tin đã được cập nhật|Pass||


### 💫 ___3. Kiểm thử chức năng Đăng kí hẹn khám___ 💫

| **Tên trường** | **Giá trị** |
|------:|:-----|
| Test Case ID: | TC_BN_003 |
| Test Title: | Đăng kí hẹn khám |
| Description: | Kiểm tra việc thêm mới một phiếu hẹn khám |

<br/>

| **Bước** | **Bước kiểm thử** | **Kết quả mong đợi** | **Kết quả thực tế** |**Trạng thái**| **Ngày kiểm thử** |
|:-----:|:-----|:-----|:-----|:-----|:-----|
|1|Vào trang chủ|Thành công vào trang chủ|Như mong đợi|Pass||
|2|Chọn chức năng ___Đăng ký hẹn khám___|Hiển thị form Đăng ký hẹn khám|Như mong đợi|Pass||
|2|Click nút __Hủy__|Quay lại trang trước đó|Như mong đợi|Pass||
|3|Chọn chức năng ___Đăng ký hẹn khám___|Hiển thị form Đăng ký hẹn khám|Như mong đợi|Pass||
|4|Để trống __"Loại khám"__|Nút lưu không tác động được|Như mong đợi|Fail||
|5|Để trống __"Cơ sở khám"__|Nút lưu không tác động được|Như mong đợi|Fail||
|6|Để trống __"Ngày hẹn"__|Nút lưu không tác động được|Như mong đợi|Fail||
|7|Nhập "Loại Khám" -> Nhập "Cơ Sở Khám" -> Chọn Ngày hẹn -> Nhập tên "Bác sĩ" (có thể bỏ trống) -> Nhập "Nội dung" (có thể bỏ trống)|Nhập được thông tin, đúng kiểu, nút lưu có thể tác động|Như mong đợi|Pass||
|4|Click nút __Lưu__|Hiển thị ra thông báo đăng ký thành công|- Đăng kí thành công phiếu hẹn khám|Pass||

### 💫 ___4. Kiểm thử chức năng Sửa phiếu hẹn khám___ 💫

| **Tên trường** | **Giá trị** |
|------:|:-----|
| Test Case ID: | TC_BN_004 |
| Test Title: | Sửa thông tin hẹn khám |
| Description: | Kiểm tra việc cập nhật một phiếu hẹn khám |

<br/>

| **Bước** | **Bước kiểm thử** | **Kết quả mong đợi** | **Kết quả thực tế** | **Trạng Thái** | **Ngày kiểm thử** |
|:-----:|:-----|:-----|:-----|:-----|:-----|
|1|Vào trang chủ|Vào trang chủ thành công|Như mong đợi|Pass||
|2|Chọn chức năng ___Lịch sử hẹn khám___|Hiển thị danh sách phiếu hẹn khám của bệnh nhân|Như mong đợi|Pass||
|3|Nhấp chọn nút ___Sửa___ của một phiếu hẹn khám|Hiển thị form cập nhật, có các dữ liệu của phiếu cần sửa|Như mong đợi|Pass||
|4|Nhấn nút __Hủy__|Không thực hiện sửa đổi và quay lại trang ___Lịch sử hẹn khám___|Quay lại trang hiển thị danh sách lịch sử hẹn khám|Pass||
|5|Thực hiện lại **Bước 3**|Hiển thị form cập nhật, có các dữ liệu của phiếu cần sửa|Như mong đợi|Pass||
|6|Xóa trống __"Loại Khám"__|Thông báo trường bắt buộc nhập, nút **lưu** bị vô hiệu hóa|Như mong đợi|Fail||
|7|Xóa trống __"Cơ Sở Khám"__|Thông báo trường bắt buộc nhập, nút **lưu** bị vô hiệu hóa|Như mong đợi|Fail||
|8|Xóa trống __"Ngày hẹn"__|Thông báo trường bắt buộc nhập, nút **lưu** bị vô hiệu hóa|Như mong đợi|Fail||
|9|Thay đổi nội dung cần sửa và không để trống 3 trường ở __bước 6, 7, 8__|Nút **lưu** hiển thị trở lại|Như mong đợi|Pass||
|10|Nhấn nút __Lưu__|Thông báo thay đổi đã được lưu|Sửa đổi thông tin thành công||

### 💫 ___5. Kiểm thử chức năng Xóa phiếu hẹn khám___ 💫

| **Tên trường** | **Giá trị** |
|------:|:-----|
| Test Case ID: | TC_BN_005 |
| Test Title: | Xóa phiếu hẹn khám |
| Description: | Kiểm tra việc xóa một phiếu hẹn khám |

<br/>

| **Bước** | **Bước kiểm thử** | **Kết quả mong đợi** | **Kết quả thực tế** | **Trạng thái** | **Ngày kiểm thử** |
|:-----:|:-----|:-----|:-----|:-----|:-----|
|1|Vào trang chủ|Vào trang chủ thành công|Như mong đợi|Pass||
|2|Chọn chức năng ___Lịch sử hẹn khám___|Hiển thị danh sách phiếu hẹn khám của bệnh nhân|Như mong đợi|Pass||
|3|Nhấp chọn nút ___Xóa___ của một phiếu hẹn khám:<br/> - Xác nhận xóa -->  __bước 4__ <br/> - Không thực hiện xóa --> __bước 5__|Hiển thị hộp thoại thông báo xác nhận xóa|Như mong đợi|Pass||
|4|Nhấn nút __Xóa__|Xóa và hiển thị ra thông báo xóa thành công, tắt hộp thoại và hiển thị lại danh sách sau khi xóa|Như mong đợi|Pass||
|5|Nhấn nút __Hủy__|Tắt hộp thoại và không thực hiện xóa |Như mong đợi|Pass||


### 💫 ___6. Kiểm thử chức năng Tìm kiếm lịch sử khám điều trị___ 💫

| **Tên trường** | **Giá trị** |
|------:|:-----|
| Test Case ID: | TC_BN_006 |
| Test Title: | Tìm kiếm lịch sử khám điều trị |
| Description: | Kiểm tra việc tìm kiếm một bệnh án của bệnh nhân |

<br/>

| **Bước** | **Bước kiểm thử** | **Kết quả mong đợi** | **Kết quả thực tế** | **Trang thái** | **Ngày kiểm thử** |
|:-----:|:-----|:-----|:-----|:-----|:-----|
|1|Vào trang chủ|Vào trang chủ thành công|Như mong đợi|Pass||
|2|Chọn chức năng ___Lịch sử khám điều trị___|Hiển thị form tìm kiếm và danh sách bệnh án|Như mong đợi|Pass||
|3|- Tại form tìm kiếm nhập __`Mã Bệnh Án`__ --> __Bước 4__<br/> - Không nhập thông tin tìm kiếm --> __Bước 5__|- Nhập được dữ liệu vào textbox<br/> - Textbox rỗng |Như mong đợi|Pass||
|4|Nhấn nút __Tìm kiếm__|- Có kết quả phù hợp: hiển thị ra hồ sơ bệnh án tìm được<br/> - Không có kết quả phù hợp: hiển thị ra thông báo __`không tìm thấy`__|Như mong đợi|Pass||
|5|Nhấn nút __Tìm kiếm__ khi ô nhập sữ liệu rỗng|Hiển thị toàn bộ danh sách Hồ sơ bệnh án của bênh nhân|Như mong đợi|Pass||
