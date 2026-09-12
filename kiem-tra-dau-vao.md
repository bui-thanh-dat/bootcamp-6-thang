# Bài kiểm tra đầu vào — 30 câu

Trả lời hết rồi gửi lại cho tôi theo dạng `1B 2C 3A ...` hoặc mỗi dòng một câu, kiểu nào cũng được.

---

## Phần I — Lập trình cơ bản (câu 1–10)

**1.** Kiểu dữ liệu của một biến quyết định điều gì?
A. Tên biến được đặt như thế nào
B. Biến chứa được loại giá trị nào và chiếm bao nhiêu bộ nhớ
C. Vị trí của biến trong file mã nguồn
D. Số lần biến được sử dụng

**2.** Với vòng lặp `for (int i = 0; i < 5; i++)`, thân vòng lặp chạy bao nhiêu lần?
A. 4
B. 5
C. 6
D. Không lần nào

**3.** Khác biệt cơ bản giữa `while` và `do-while` là gì?
A. `do-while` chạy nhanh hơn
B. `while` luôn chạy ít nhất một lần
C. `do-while` luôn chạy ít nhất một lần
D. Không có khác biệt, chỉ khác cách viết

**4.** Một mảng có 5 phần tử. Các chỉ số hợp lệ là gì?
A. Từ 1 đến 5
B. Từ 0 đến 5
C. Từ 0 đến 4
D. Từ 1 đến 4

**5.** Câu lệnh `return` trong một hàm có tác dụng gì?
A. Dừng toàn bộ chương trình
B. Kết thúc hàm và trả giá trị về nơi đã gọi hàm
C. Bỏ qua dòng kế tiếp rồi chạy tiếp phần còn lại của hàm
D. In giá trị ra màn hình

**6.** Bạn truyền một biến số nguyên vào hàm, bên trong hàm gán cho tham số đó một giá trị mới. Biến gốc bên ngoài thế nào?
A. Thay đổi theo
B. Giữ nguyên giá trị cũ
C. Báo lỗi biên dịch
D. Trở thành rỗng

**7.** Chuỗi `"Hello"` có bao nhiêu ký tự, và ký tự tại chỉ số 0 là gì?
A. 5 ký tự, chỉ số 0 là `H`
B. 5 ký tự, chỉ số 0 là `e`
C. 4 ký tự, chỉ số 0 là `H`
D. 6 ký tự, chỉ số 0 là `H`

**8.** Kết quả của phép `"12" + "3"` (hai toán hạng đều là chuỗi) là gì?
A. Số 15
B. Chuỗi `"123"`
C. Số 123
D. Lỗi vì không cộng được hai chuỗi

**9.** `17 % 5` bằng bao nhiêu?
A. 3
B. 2
C. 3.4
D. 0

**10.** Một biến được khai báo bên trong thân một hàm thì:
A. Dùng được ở mọi nơi trong chương trình
B. Chỉ dùng được bên trong hàm đó
C. Tự động trở thành biến toàn cục
D. Chỉ dùng được sau khi hàm kết thúc

---

## Phần II — Hướng đối tượng (câu 11–18)

**11.** Quan hệ giữa lớp và đối tượng giống với cặp nào nhất?
A. Bản thiết kế và ngôi nhà xây từ bản thiết kế đó
B. Ngôi nhà và bản thiết kế vẽ lại từ ngôi nhà đó
C. Hai thứ hoàn toàn giống nhau, chỉ khác tên gọi
D. Hàm và biến

**12.** Hàm khởi tạo (constructor) được gọi vào lúc nào?
A. Mỗi lần gọi một phương thức của đối tượng
B. Khi một đối tượng mới được tạo ra
C. Khi chương trình kết thúc
D. Khi đối tượng bị hủy

**13.** Đặt thuộc tính ở mức `private` rồi cung cấp getter và setter nhằm mục đích gì?
A. Tiết kiệm bộ nhớ
B. Kiểm soát cách thuộc tính được đọc và ghi
C. Làm chương trình chạy nhanh hơn
D. Bắt buộc lớp khác phải kế thừa

**14.** Lớp `Cho` kế thừa lớp `DongVat`. Điều nào đúng?
A. `DongVat` dùng được mọi phương thức riêng của `Cho`
B. `Cho` dùng được các phương thức public của `DongVat`
C. Hai lớp hoàn toàn không liên quan sau khi kế thừa
D. `Cho` buộc phải viết lại toàn bộ phương thức của `DongVat`

**15.** Ghi đè phương thức (override) nghĩa là gì?
A. Lớp con định nghĩa lại một phương thức đã có ở lớp cha
B. Viết nhiều phương thức cùng tên nhưng khác tham số trong cùng một lớp
C. Xóa hẳn phương thức của lớp cha
D. Đổi tên một phương thức cho dễ đọc

**16.** Hai phương thức cùng tên, nằm trong cùng một lớp, khác nhau ở danh sách tham số. Đó gọi là gì?
A. Ghi đè (override)
B. Nạp chồng (overload)
C. Kế thừa
D. Đóng gói

**17.** Interface về cơ bản dùng để làm gì?
A. Lưu trữ dữ liệu của đối tượng
B. Quy định danh sách phương thức mà lớp cài đặt nó bắt buộc phải có
C. Tạo ra đối tượng một cách trực tiếp
D. Thay thế cho cơ sở dữ liệu

**18.** Đa hình (polymorphism) cho phép điều gì?
A. Một biến kiểu lớp cha có thể trỏ tới đối tượng của nhiều lớp con khác nhau
B. Một lớp được đặt nhiều tên gọi
C. Một đối tượng chiếm nhiều vùng nhớ cùng lúc
D. Nhiều lớp bắt buộc phải có chung một thuộc tính

---

## Phần III — Cơ sở dữ liệu (câu 19–25)

**19.** Khóa chính (primary key) của một bảng phải thỏa điều kiện gì?
A. Bắt buộc phải là kiểu số
B. Duy nhất trong bảng và không được rỗng
C. Được phép trùng nhau nếu nằm ở hai dòng khác nhau
D. Bắt buộc phải đặt tên là `id`

**20.** Khóa ngoại (foreign key) dùng để làm gì?
A. Tăng tốc độ truy vấn cho cột đó
B. Liên kết bảng này tới khóa chính của một bảng khác
C. Mã hóa dữ liệu trong cột
D. Đánh số tự động tăng dần cho từng dòng

**21.** Câu `SELECT * FROM sinhvien WHERE diem > 8` trả về cái gì?
A. Toàn bộ các dòng trong bảng
B. Chỉ riêng cột `diem` của mọi dòng
C. Mọi cột của những dòng có `diem` lớn hơn 8
D. Số lượng dòng có `diem` lớn hơn 8

**22.** Trong cơ sở dữ liệu quan hệ, một dòng trong bảng đại diện cho cái gì?
A. Một thuộc tính
B. Một bản ghi, tức một thực thể cụ thể
C. Tên của bảng
D. Kiểu dữ liệu của một cột

**23.** `INNER JOIN` giữa hai bảng trả về gì?
A. Toàn bộ dòng của cả hai bảng
B. Chỉ những dòng có giá trị khớp nhau ở cả hai bảng
C. Toàn bộ dòng của bảng bên trái
D. Chỉ những dòng không khớp nhau

**24.** `LEFT JOIN` khác `INNER JOIN` ở điểm nào?
A. Giữ lại mọi dòng của bảng bên trái, kể cả khi không có dòng khớp ở bảng bên phải
B. Chỉ lấy những dòng khớp nhau, giống hệt `INNER JOIN`
C. Chạy nhanh hơn nhờ bỏ qua bước so khớp
D. Chỉ dùng được khi nối từ ba bảng trở lên

**25.** Mệnh đề `ORDER BY` dùng để làm gì?
A. Lọc bớt số dòng trả về
B. Sắp xếp kết quả trả về
C. Gộp các dòng thành nhóm
D. Nối hai bảng với nhau

---

## Phần IV — Web hoạt động ra sao (câu 26–30)

**26.** Câu nào mô tả đúng về client và server?
A. Client luôn là điện thoại, server luôn là máy tính cỡ lớn
B. Client là bên mở lời hỏi, server là bên trả lời
C. Server luôn có cấu hình mạnh hơn client
D. Một máy không bao giờ đóng được cả hai vai

**27.** Nói HTTP là giao thức stateless nghĩa là gì?
A. Máy chủ không lưu trữ bất kỳ dữ liệu nào, kể cả trong database
B. Máy chủ không giữ thông tin về bạn giữa hai request
C. Máy chủ chỉ xử lý được một request tại một thời điểm
D. Kết nối luôn bị đóng sau đúng một giây

**28.** `GET /api/orders` và `POST /api/orders` khác nhau ở chỗ nào?
A. Không khác gì vì cùng một đường dẫn
B. `GET` là xem danh sách, `POST` là tạo mới
C. `GET` gửi qua HTTP còn `POST` gửi qua HTTPS
D. `GET` nhanh hơn vì bỏ qua bước bắt tay

**29.** Mã trạng thái 404 và 500 khác nhau ở chỗ nào?
A. 404 nghiêm trọng hơn 500
B. 404 là phía gọi hỏi sai, 500 là máy chủ gặp lỗi khi xử lý
C. 404 xảy ra ở mạng, 500 xảy ra ở trình duyệt
D. Giống nhau về bản chất, chỉ khác cách đánh số

**30.** HTML, CSS và JavaScript của một trang web được thực thi ở đâu?
A. Trên máy chủ, rồi máy chủ gửi ảnh kết quả về cho người dùng
B. Trên trình duyệt của người dùng
C. Một nửa ở máy chủ, một nửa ở trình duyệt
D. Trên máy chủ DNS

---

Gửi đủ 30 lựa chọn, tôi chấm trên thang 30 và chỉ giải thích những câu bạn sai.

## Kết quả: 28/30

Sai 2 câu: **9,  11**. Cả 2 đều nằm ở phần nền, và cả 2 đều sai vì cùng một kiểu — hiểu nhầm một ký hiệu hoặc đảo ngược một quan hệ, chứ không phải không biết.

Theo barem của khóa học (dưới 18/30 thì cần củng cố bốn tuần trước), bạn vào Vòng 1 được ngay.

---

### Câu 9 — Đáp án đúng: B

`%` trong lập trình **không phải phần trăm**. Nó là toán tử **chia lấy dư** (modulo).

17 chia 5 được 3, dư 2. Nên `17 % 5 = 2`.

Bạn tính 17% của 5 nên ra 0.85. Đây là nhầm lẫn rất phổ biến và cũng chính là lý do câu này có mặt. Muốn tính phần trăm thì phải tự viết `17 / 100 * 5`.

Toán tử này bạn sẽ dùng suốt: kiểm tra số chẵn lẻ (`n % 2 == 0`), lấy chữ số cuối (`n % 10`), chia đều vào các nhóm.

### Câu 11 — Đáp án đúng: A

Bạn chọn đúng cặp nhưng **đảo ngược thứ tự**.

- **Lớp** là bản thiết kế. Nó có trước, bạn viết nó ra.
- **Đối tượng** là ngôi nhà. Nó được tạo ra **từ** bản thiết kế, và tạo được bao nhiêu cái cũng được.

Đáp án B nói ngược: ngôi nhà có trước rồi mới vẽ lại bản thiết kế.

Nhớ theo chiều thời gian: viết `class SinhVien` trước, rồi mới `new SinhVien()` để ra một sinh viên cụ thể. Bản thiết kế chỉ có một, nhà xây ra thì nhiều.

---

