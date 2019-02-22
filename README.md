## Name
- Tên phải diễn đạt được ý định khi đặt tên cho biến, hàm, lớp…
- Nếu đặt tên mà cần comment thì tên đó chưa diễn đạt được ý định
- Tên cần đặt theo quy ước (convention) của ngôn ngữ triển khai, team
- Nên dùng tên tiếng anh
- Tên Class và object nên dùng danh từ hoặc cụm danh từ. Tên Class không nên dùng động từ
- Tránh dùng các từ như: Manager, Processor, Data hoặc Info làm tên cho class
- Tên Methods/function nên dùng động từ hoặc cụm động từ
- Accessors, mutators, and predicates should be named for their value and prefixed with get,set, and is 
## Function
- Nên tạo các function có độ dài càng nhỏ càng tốt (Độ dài của mỗi function không nên lớn quá độ cao của màn hình. Tốt nhất không nên quá 20 dòng code)
- FUNCTIONS SHOULD DO ONE THING. THEY SHOULD DO IT WELL. THEY SHOULD DO IT ONLY.
- Function chỉ thực hiện một chức năng là function không thể chia thành các section nhỏ bên trong.
- Các lệnh trong function phải ở cùng mức trừu tượng (same level of abstraction)
- Không nên tạo function với đối số dạng boolean để thực hiện nhiều hơn 1 nhiệm vụ. Nên tạo 2 function riêng biệt
- Khi một function dùng nhiều hơn 2 hoặc 3 đối số thì nên dùng đến đối số là object 
## Comments
- One of the more common motivations for writing comments is bad code
- Các comment nên dùng
+ Comment liên quán đến tính pháp lý, bản quyền...
+ Comment cảnh báo về hậu quả khi không dùng đoạn code đó
+ Comment giải thích ý định
## Class
- Tạo class nhỏ nhất có thể (đo bằng số tính năng trong một class)
- Nên mô tả class trong khoảng 25 từ sao cho không dùng các từ “if,” “and,” “or,” hoặc  “but.”. Nếu xuất hiện các từ đó thì class chưa phải là nhỏ nhất
- Nên tạo các class có tính liên kết cao (Class có tính liên kết cao là class có số lượng thuộc tính nhỏ và mỗi method của class đó có thể sử dụng nhiều thuộc tính)
- Single Responsibility Principle (SRP): A class should have one and only one reason to change, meaning that a class should have only one job.
- Open-Closed Principle: Objects or entities should be open for extension, but closed for modification.
- Liskov substitution principle: Let q(x) be a property provable about objects of x of type T. Then q(y) should be provable for objects y of type S where S is a subtype of T.
- Interface segregation principle: A client should never be forced to implement an interface that it doesn't use or clients shouldn't be forced to depend on methods they do not use.
- Dependency Inversion Principle (DIP): Entities must depend on abstractions not on concretions. It states that the high level module must not depend on the low level module, but they should depend on abstractions.
## General
- Code không dùng nữa thì nên xoá đi không nên comment.
- Luôn luôn test các điều kiện biên
- Tìm và loại bỏ các dòng code trùng lặp khi có thể
## Example
[Some example](https://drive.google.com/open?id=1pEuiVJ0yh7p2SRn8j85n4AtiSqmZdJodntfRbNFWvmg)
