# SpringBootQuestion


### 1. Spring boot là gì?
- Spring Boot là một dự án phát triển bởi JAV (ngôn ngữ java) trong hệ sinh thái Spring framework. Nó giúp cho các lập trình viên chúng ta đơn giản hóa quá trình lập trình một ứng dụng với Spring, chỉ tập trung vào việc phát triển business cho ứng dụng.
### 2. Ưu điểm của spring boot?
- Phát triển các ứng dụng dựa trên Spring một cách tiết kiệm thời gian và dễ dàng.
- Tự động cấu hình tất cả các components cho một ứng dụng Spring cấp sản xuất
- Các máy chủ nhúng được tạo sẵn (Tomcat,...), dẫn đến việc triển khai ứng dụng được tăng tốc và hiệu quả hơn
### 3. Tên file configuration cái mà bạn có thể sử dụng trong Spring Boot?
- File configuration được sử dụng trong dự án Spring Boot được gọi là application.properties. Nó là 1 file quan trọng cho phép bạn ghi đè các cấu hình mặc định của bạn.
### 4.Các thành phần cơ bản của spring boot?
- Spring Bean: 
  + Spring Bean là trung tâm của Spring Core và là trái tim của một ứng dụng Spring. Spring Bean có thể được hiểu là các đối tượng Java đơn giản.
- Dependency Injection (DI): 
  + là một mẫu thiết kế phần mềm mà các đối tượng phụ thuộc sẽ được inject vào một lớp nào đó.
  + Dependency Injection là một implementation cụ thể của khái niệm Inversion of Control (đảo ngược điều khiển).
- Spring Context: 
  + Spring Context kế thừa các tính năng của Spring Bean và bổ sung các hỗ trợ cho internationalization (ví dụ như các resource bundle), event propagation, resource loading… 
  + Spring Context cũng hỗ trợ các tính năng của Java EE như EJB, JMX và RMI. Interface ApplicationContext chính là trọng tâm của Spring Context.
- Spring Expression Language (SpEL): 
  + là một ngôn ngữ ngắn gọn giúp cho việc cấu hình Spring Framework trở nên linh hoạt hơn.
### 5. Làm thế nào để tạo một dự án Spring Boot bằng Maven?
- Spring Initializer.
- Spring Boot CLI.
- Spring Starter Project Wizard.
### 6. 'IOC' là gì?
- IOC là viết tắt của Inversion of Control. Nó là core container của Java Spring. Nó sử dụng phép dependency injection được đề cập trước đó để quản lý và định cấu hình các ứng dụng tích hợp khác nhau. Hiện tại có hai loại IOC có thể được đặt trong Java Spring - ApplicationContext  và BeanFactory.
### 7. ‘Bean’ là gì?
- “Bean” là một đối tượng được tích hợp và cấu hình bởi IOC container.
### Bean Factory là gì?
- BeanFactory là root interface dùng để thao tác với Spring container
- nó cung cấp những tính năng cơ bản để quản lý bean trong ứng dụng.
### 8. Tại sao nên sử dụng ‘constructor injection’ cho injecting bean?
- constructor injection chỉ được sử dụng để inject mandatory dependencies.
- vì kiểu injection này làm cho quá trình kiểm tra sau đó dễ dàng hơn rất nhiều.
### 9. Có bao nhiêu cách để thực hiện Dependency Injection?
- Có ba cách để làm điều đó:
  + Constructor Injection
  + Setter Injection
  + Interface Injection
- Trong Spring framework, chủ yếu là constructor và setter injection được sử dụng.
### 10. ‘autowriting’ là gì?
- cho phép nhà phát triển tự động inject bean vào ứng dụng của mình mà không cần can thiệp thủ công.
### 11. @Controll làm gì?
- @Controll đặt tên một lớp Spring được chỉ định cụ thể như lớp controller.
### 12. @Autowired làm gì?
- Lệnh @Autowired cho phép bạn linh hoạt quyết định nơi muốn wire đối tượng của mình. 
- Lệnh này làm cho quá trình dễ dàng và mượt mà hơn, cho phép độ chính xác cao hơn.
### 13. Dispatcher servlet được sử dụng làm gì?
- Công việc của DispatcherServlet là lấy một URI đến và tìm ra sự kết hợp đúng của các trình xử lý (nói chung là các phương thức trên các lớp Trình điều khiển ) và các khung nhìn (nói chung là các tệp JSP) kết hợp để tạo ra trang hoặc tài nguyên được cho là tìm thấy tại vị trí đó.
- Hiểu đơn giản là nó sẽ tiếp nhận và xử lý mọi yêu cầu từ phía người dùng.
### 14.  @RequestMapping làm gì?
- Lệnh này được sử dụng bất cứ khi nào bạn muốn sắp xếp một phương thức HTTP cụ thể đến một lớp cụ thể. 
- Bạn có thể sử dụng lệnh này trong cả hai cấp độ lớp và phương thức.
### 15. CORS trong Spring Boot?
- CORS là viết tắt của Cross-Origin Resource Sharing là một cơ chế được thực hiện bởi các trình duyệt và giúp người dùng cho phép các yêu cầu giữa các miền.
### 16. CSRF là gì?
- là kỹ thuật tấn công bằng cách sử dụng quyền chứng thực của người dùng đối với một website. 
- Hiểu đơn giản, đây là kỹ thuật tấn công dựa vào mượn quyền trái phép.
### 17. @RestController làm gì?
- @RestController bao gồm 2 anotation là @Controller và @Responbody.
- tất cả các request sẽ được tự động trả về đối tượng bên trong HttpResponse.
### 18 @RequestHeader và @ResponseHeader có ý nghĩa gì?
- @RequestHeader được sử dụng khi ta muốn lấy dữ liệu được truyền bằng Header của một request (yêu cầu từ client).
- @ResponseHeader khi mình muốn trả về thêm dữ liệu cho client ở phần trên cùng của mỗi response.
### 19.Giải thích Spring CLI?
- Được sử dụng trong ứng dụng Groovy Spring boot.
- Giúp viết code ngắn gọn hơn.
### 20. @pathVariable là gì?
- lấy thông tin từ url. Ví dụ:
```
@GetMapping("/{id}")
    public Book getBook(@PathVariable int id) {
        return findBookById(id);
    }
```
### 21.@Component có ý nghĩa gì?
- Là một annotation của class. Nó dùng để đánh dấu class Java là một bean. 
- Một class Java được đánh dấu @Component được tìm thấy trong classpath. 
- Spring Framework chọn nó và cấu hình trong ngữ cảnh ứng dụng như một Spring Bean.
### 22. @Bean có ý nghĩa gì?
- là 1 anotation của method. Nó biết rằng một method tạo ra một bean sẽ được quản lý bởi Spring container
- Trong khi cấu hình Java (@Configuration), phương thức được thực thi và giá trị trả về của nó được đăng ký dưới dạng bean trong BeanFactory.
### 23. Hãy nêu các bean scope có trong Spring?
- Có 5 scope được định nghĩa cho Spring Bean:
  + Singleton: Chỉ duy nhất một thể hiện của bean sẽ được tạo cho mỗi container. Đây là scope mặc định cho spring bean. Khi sử dụng scope này cần chắc chắn rằng các bean không có các biến/thuộc tính được share.
  + Prototype: Một thể hiện của bean sẽ được tạo cho mỗi lần được yêu cầu(request)
  + Request: giống với prototype scope, tuy nhiên nó dùng cho ứng dụng web, một thể hiện của bean sẽ được tạo cho mỗi HTTP request.
  + Session: Mỗi thể hiện của bean sẽ được tạo cho mỗi HTTP Session
  + Global-Session: Được sử dụng để tạo global sesion bean cho các ứng dụng Portlet.
### 24. ApplicationContext là gì?
- Là khái niệm Spring Boot dùng để chỉ Spring IoC container, tương tự như bean là đại diện cho các dependency.
- Khi ứng dụng Spring chạy, Spring IoC container sẽ quét toàn bộ packages, tìm ra các bean và đưa vào ApplicationContext.
### 25. JPA là gì?
- JPA (Java Persistence API) là 1 giao diện lập trình ứng dụng Java, nó mô tả cách quản lý các mối quan hệ dữ liệu trong ứng dụng sử dụng Java Platform.
### 26.  Spring Data JPA là gì?
- Spring Boot JPA là một bản ghi chi tiết của Java để quản lý dữ liệu quan hệ trong các ứng dụng Java. 
- Nó cho phép chúng ta truy cập và lưu trữ dữ liệu giữa các object/class Java và database quan hệ. 
- JPA tuân theo Object-Relation Mapping (ORM). Nó là một tập hợp các interface.
### 27. Làm cách nào bạn có thể kết nối Spring Boot với database bằng JPA?
- Trong file pom.xml chúng ta thêm dependency spring-boot-data-JPA vào để kết nối với database
### 28. Để sử dụng interface JpaRepository cần cung cấp những thông tin nào?
- nó nhận vào 1 entity class tương ứng với 1 bảng trong db, và kiểu dữ liệu của khoá chính chúng ta khai báo trong entity trước đó.
### 29. Hibernate là gì?
- Hibernate là một thư viện ORM (Object Relational Mapping) mã nguồn mở giúp lập trình viên viết ứng dụng Java có thể map các objects (pojo) với hệ quản trị cơ sở dữ liệu quan hệ, và hỗ trợ thực hiện các khái niệm lập trình hướng đối tượng với cớ dữ liệu quan hệ.
- 1 số anotation của hibernate : 
  + @Entity: Đánh dấu class là 1 entity.
  + @Table: cho phép chú thích tên bảng thông qua thuộc tính name (thuộc tính này không bắt buộc).
  + @Column: chú thích các thuộc tính của class ứng với từng fiel của entity...
### 30. Câu lệnh truy vấn động là gì? Câu lệnh truy vấn tĩnh là gì?
- Statement: 
  + Sử dụng để thực hiện các câu truy vấn SQL tĩnh
  + Chúng ta không thể truyền tham số vào câu SQL trong thời gian runtime.
  + có hiệu năng (performance) kém hơn  PrepareStatement.
  + thường được sử dụngtrong trường hợp câu lệnh SQL chỉ chạy 1 lần
- PreparedStatement: 
  + Sử dụng để thực hiện các  câu truy vấn SQL động hoặc có tham số
  + thừa kế từ Statement nhưng nó cho phép truyền các tham số vào câu SQL trong thời gian run time.
  + sử dụng trong trường hợp câu SQL được sử dụng nhiều lần.
### 31. Trình bày Spring Security?
- Spring Security cung cấp các dịch vụ bảo mật toàn diện cho các ứng dụng doanh nghiệp có nền tảng Java EE.
- Hiểu đơn giản là mã hóa mật khẩu, xác thực và phân quyền người dùng.
- Spring Security cung cấp 2 cơ chế cơ bản:
  + Authentication (xác thực): là tiến trình thiết lập một principal. Principal có thể hiểu là một người, hoặc một thiết bị, hoặc một hệ thống nào đó có thể thực hiện một hành động trong ứng dụng của bạn.
  + Authorization (phân quyền) hay Access-control: là tiến trình quyết định xem một principal có được phép thực hiện một hành động trong ứng dụng của bạn hay không. Trước khi diễn tiến tới Authorization, principal cần phải được thiết lập bởi Authentication.
### 32.  @Transaction làm gì?
- @Transactional annotation trên các interface, class, method và Spring sẽ bao bao ngoài chúng một proxy giúp chúng ta thực thi các thao tác tự động như start, commit hay rollback transaction.
### 33. Data Binding là gì?
- Data Binding là cơ chế liên kết dữ liệu đầu vào hoặc đầu ra với các đối tượng model. Hay nói cách khác đó là sự kết nối dữ liệu của bean đặt trong model đến các điều khiển trên form.
- Data Binding giúp cho việc tương tác với dữ liệu trở nên dễ dàng
### 34. Validation là gì?
-  Là hành động kiểm tra tính hợp lệ của dữ liệu. Việc này giúp cho hệ thống hoạt động an toàn, đảm bảo, tránh xử lý dữ liệu lỗi,... và cũng giúp ngăn chặn một số cuộc tấn công phổ biến như SQL injection hoặc XSS.
### 35. I18N là gì?
- là quá trình thi công một vận dụng ứng dụng nhằm nó rất có thể được kiểm soát và điều chỉnh thích hợp cho những ngữ điệu và Khu Vực cơ mà không có sự biến đổi về chuyên môn.
- đơn giản là chúng ta có thể chuyển dỗi dễ dàng các loại ngôn ngữ hiển thị theo yêu cầu của khách hàng.
### 36. Sự khác nhau giữa SpringBoot và SpringMVC là gì?
- Spring Boot là một module của Spring để đóng gói ứng dụng dựa trên Spring với các giá trị mặc định hợp lý. 
- Spring MVC model view controller-based web framework dựa trên Spring. Nó cung cấp các cấu hình mặc định để xây dựng Spring-powered framework
### 37. ORM là gì ?
- ORM (Object Relational Mapping), là một kỹ thuật/cơ chế lập trình thực hiện ánh xạ CSDL sang các đối tượng trong các ngôn ngữ lập trình hướng đối tượng như Java, C# …(các table tương ứng các class, mối ràng buộc giữa các table tương ứng quan hệ giữa các class ‘has a’ , ‘is a’).
