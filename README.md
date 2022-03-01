# SpringBootQuestion


#### 1. Spring boot là gì?
- Spring Boot là một dự án phát triển bởi JAV (ngôn ngữ java) trong hệ sinh thái Spring framework. Nó giúp cho các lập trình viên chúng ta đơn giản hóa quá trình lập trình một ứng dụng với Spring, chỉ tập trung vào việc phát triển business cho ứng dụng.
#### 2. Ưu điểm của spring boot?
- Phát triển các ứng dụng dựa trên Spring một cách tiết kiệm thời gian và dễ dàng.
- Tự động cấu hình tất cả các components cho một ứng dụng Spring cấp sản xuất
- Các máy chủ nhúng được tạo sẵn (Tomcat,...), dẫn đến việc triển khai ứng dụng được tăng tốc và hiệu quả hơn
#### 3. Tên file configuration cái mà bạn có thể sử dụng trong Spring Boot?
- File configuration được sử dụng trong dự án Spring Boot được gọi là application.properties. Nó là 1 file quan trọng cho phép bạn ghi đè các cấu hình mặc định của bạn.
#### 4.Các thành phần cơ bản của spring boot?
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
#### 5.  'IOC' là gì?
- IOC là viết tắt của Inversion of Control. Nó là core container của Java Spring. Nó sử dụng phép dependency injection được đề cập trước đó để quản lý và định cấu hình các ứng dụng tích hợp khác nhau. Hiện tại có hai loại IOC có thể được đặt trong Java Spring - ApplicationContext  và BeanFactory.
#### 6. ‘Bean’ là gì?
- “Bean” là một đối tượng được tích hợp và cấu hình bởi IOC container.
#### 7. Tại sao nên sử dụng ‘constructor injection’ cho injecting bean?
- constructor injection chỉ được sử dụng để inject mandatory dependencies.
- vì kiểu injection này làm cho quá trình kiểm tra sau đó dễ dàng hơn rất nhiều.
#### 8. Có bao nhiêu cách để thực hiện Dependency Injection?
- Có ba cách để làm điều đó:
  + Constructor Injection
  + Setter Injection
  + Interface Injection
- Trong Spring framework, chủ yếu là constructor và setter injection được sử dụng.
#### 9.  ‘autowriting’ là gì?
- cho phép nhà phát triển tự động inject bean vào ứng dụng của mình mà không cần can thiệp thủ công.
#### 10. @Controll làm gì?
- @Controll đặt tên một lớp Spring được chỉ định cụ thể như lớp trình điều khiển.
#### 11. @Autowired làm gì?
- Lệnh @Autowired cho phép bạn linh hoạt quyết định nơi muốn wire đối tượng của mình. 
- Lệnh này làm cho quá trình dễ dàng và mượt mà hơn, cho phép độ chính xác cao hơn.
#### 12.  @RequestMapping làm gì?
- Lệnh này được sử dụng bất cứ khi nào bạn muốn sắp xếp  một phương thức HTTP cụ thể đến một lớp cụ thể. 
- Bạn có thể sử dụng lệnh này trong cả hai cấp độ lớp và phương thức.
