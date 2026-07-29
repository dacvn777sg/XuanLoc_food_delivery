# Hướng dẫn tạo form SRQ trên Tally.so

Form này thu thập yêu cầu từ khách hàng cho dự án giao đồ ăn Xuân Lộc.
Mỗi block dưới đây = 1 nhóm câu hỏi. Khi paste vào Tally:
- Dùng **Question** cho mỗi câu trong block
- Loại câu: **Multiple choice** (chọn 1) hoặc **Checkboxes** (chọn nhiều) hoặc **Short text / Long text** (nhập)
- Bật **'Allow other'** nếu có option 'Khác'

---

## 📋 Block 0 — Thông tin doanh nghiệp (intake)

| STT | Câu hỏi | Loại | Bắt buộc |
|---|---|---|---|
| 1 | Tên dự án | Short text | ✅ |
| 2 | Tên doanh nghiệp | Short text | ✅ |
| 3 | Người đại diện | Short text | ✅ |
| 4 | Người phối hợp nghiệp vụ | Short text | ❌ |
| 5 | Đơn vị tư vấn/phát triển | Short text | ❌ |
| 6 | Ngày thực hiện khảo sát | Date | ❌ |

---

## 📝 Block 1 — Q01

**Câu hỏi chính:** Hệ thống dự kiến gồm những kênh sử dụng nào?

**Loại câu hỏi:** Checkboxes (multi-select, 6 lựa chọn)

| # | Lựa chọn |
|---|---|
| 1 | Ứng dụng cho khách đặt món. |
| 2 | Ứng dụng cho cửa hàng nhận và xử lý đơn. |
| 3 | Ứng dụng cho tài xế nhận và giao đơn. |
| 4 | Website quản trị dành cho nhân viên vận hành. |
| 5 | Website đặt món cho khách. |
| 6 | Kênh khác *(có ô nhập text bổ sung)* |

> **Tick 'Other'** trên Tally để khách nhập thêm khi chọn option có marker ở trên.

---

## 📝 Block 2 — Q02

**Câu hỏi chính:** Mỗi cửa hàng trong phiên bản đầu tiên chỉ có một địa chỉ hoạt động?

**Loại câu hỏi:** Checkboxes (multi-select, 3 lựa chọn)

| # | Lựa chọn |
|---|---|
| 1 | Đúng. |
| 2 | Không, một cửa hàng có thể có nhiều chi nhánh. |
| 3 | Hiện tại một địa chỉ, nhưng cần chuẩn bị cho nhiều chi nhánh trong tương lai. |

> **Tick 'Other'** trên Tally để khách nhập thêm khi chọn option có marker ở trên.

---

## 📝 Block 3 — Q03

**Câu hỏi chính:** Mỗi đơn hàng chỉ được đặt từ một cửa hàng?

**Loại câu hỏi:** Checkboxes (multi-select, 3 lựa chọn)

| # | Lựa chọn |
|---|---|
| 1 | Đúng. |
| 2 | Không, khách có thể đặt từ nhiều cửa hàng trong cùng một đơn. |
| 3 | Chưa xác định — cần tư vấn. |

> **Tick 'Other'** trên Tally để khách nhập thêm khi chọn option có marker ở trên.

---

## 📝 Block 4 — Q04

**Câu hỏi chính:** Mỗi tài xế chỉ giao một đơn tại một thời điểm trong MVP?

**Loại câu hỏi:** Checkboxes (multi-select, 3 lựa chọn)

| # | Lựa chọn |
|---|---|
| 1 | Đúng. |
| 2 | Không, tài xế có thể nhận nhiều đơn cùng lúc. |
| 3 | MVP một đơn; tương lai cần hỗ trợ ghép nhiều đơn. |

> **Tick 'Other'** trên Tally để khách nhập thêm khi chọn option có marker ở trên.

---

## 📝 Block 5 — Q05

**Câu hỏi chính:** Hình thức thanh toán chính của MVP là tiền mặt khi nhận hàng (COD)?

**Loại câu hỏi:** Checkboxes (multi-select, 4 lựa chọn)

| # | Lựa chọn |
|---|---|
| 1 | Đúng, chỉ COD. |
| 2 | COD và chuyển khoản trực tiếp. |
| 3 | Cần thanh toán trực tuyến ngay trong MVP. |
| 4 | Chưa xác định — cần tư vấn. |

> **Tick 'Other'** trên Tally để khách nhập thêm khi chọn option có marker ở trên.

---

## 📝 Block 6 — Q06

**Câu hỏi chính:** Việc chọn tài xế được thực hiện như thế nào?

**Loại câu hỏi:** Checkboxes (multi-select, 5 lựa chọn)

| # | Lựa chọn |
|---|---|
| 1 | Hệ thống tự chọn tài xế phù hợp. |
| 2 | Nhân viên vận hành chọn tài xế. |
| 3 | Hệ thống tự chọn; nhân viên có thể can thiệp khi cần. |
| 4 | Cửa hàng tự chọn tài xế. |
| 5 | Chưa xác định — cần tư vấn. |

> **Tick 'Other'** trên Tally để khách nhập thêm khi chọn option có marker ở trên.

---

## 📝 Block 7 — Q07

**Câu hỏi chính:** Khách không được tự hủy sau khi cửa hàng đã chấp nhận đơn?

**Loại câu hỏi:** Checkboxes (multi-select, 4 lựa chọn)

| # | Lựa chọn |
|---|---|
| 1 | Đúng. |
| 2 | Vẫn được hủy nhưng cần cửa hàng/Admin phê duyệt. |
| 3 | Được hủy ở các trạng thái khác *(có ô nhập text bổ sung)* |
| 4 | Chưa xác định — cần tư vấn. |

> **Tick 'Other'** trên Tally để khách nhập thêm khi chọn option có marker ở trên.

---

## 📝 Block 8 — Q08

**Câu hỏi chính:** Thông tin doanh nghiệp và đầu mối dự án

---

## 📝 Block 9 — Q09

**Câu hỏi chính:** Dự án đang ở giai đoạn nào?

**Loại câu hỏi:** Checkboxes (multi-select, 6 lựa chọn)

| # | Lựa chọn |
|---|---|
| 1 | Ý tưởng ban đầu. |
| 2 | Đang thử nghiệm thủ công. |
| 3 | Đã có cửa hàng và tài xế hoạt động. |
| 4 | Đã có phần mềm nhưng cần thay thế. |
| 5 | Đang mở rộng sang khu vực mới. |
| 6 | Khác *(có ô nhập text bổ sung)* |

> **Tick 'Other'** trên Tally để khách nhập thêm khi chọn option có marker ở trên.

---

## 📝 Block 10 — Q10

**Câu hỏi chính:** Ba mục tiêu quan trọng nhất của dự án là gì?

**Loại câu hỏi:** Checkboxes (multi-select, 10 lựa chọn)

| # | Lựa chọn |
|---|---|
| 1 | Tăng số lượng đơn hàng. |
| 2 | Giảm thời gian xử lý đơn. |
| 3 | Tự động hóa việc tìm tài xế. |
| 4 | Giảm sai sót khi nhận và giao hàng. |
| 5 | Theo dõi đơn hàng minh bạch hơn. |
| 6 | Quản lý cửa hàng tập trung. |
| 7 | Quản lý tiền COD và đối soát. |
| 8 | Có dữ liệu báo cáo để ra quyết định. |
| 9 | Xây dựng thương hiệu và kênh bán riêng. |
| 10 | Mục tiêu khác *(có ô nhập text bổ sung)* |

> **Tick 'Other'** trên Tally để khách nhập thêm khi chọn option có marker ở trên.

---

## 📝 Block 11 — Q11

**Câu hỏi chính:** Hiện nay đơn hàng đến từ những kênh nào?

**Loại câu hỏi:** Checkboxes (multi-select, 8 lựa chọn)

| # | Lựa chọn |
|---|---|
| 1 | Điện thoại. |
| 2 | Zalo. |
| 3 | Facebook/Messenger. |
| 4 | Website. |
| 5 | Ứng dụng hiện có. |
| 6 | Nhân viên nhập đơn trực tiếp. |
| 7 | Chưa vận hành. |
| 8 | Kênh khác *(có ô nhập text bổ sung)* |

> **Tick 'Other'** trên Tally để khách nhập thêm khi chọn option có marker ở trên.

---

## 📝 Block 12 — Q12

**Câu hỏi chính:** Quy trình hiện tại từ lúc nhận đơn đến khi giao xong diễn ra như thế nào?

**Câu bổ sung (nhập text):**

- **Mô tả chi tiết** — Loại: Short text
- **Mô tả chi tiết** — Loại: Short text
- **Mô tả chi tiết** — Loại: Short text

---

## 📝 Block 13 — Q13

**Câu hỏi chính:** Những khó khăn lớn nhất trong quy trình hiện tại là gì?

**Loại câu hỏi:** Checkboxes (multi-select, 10 lựa chọn)

| # | Lựa chọn |
|---|---|
| 1 | Bỏ sót hoặc nhập sai đơn. |
| 2 | Cửa hàng phản hồi chậm. |
| 3 | Khó tìm tài xế. |
| 4 | Không biết tài xế đang ở đâu. |
| 5 | Khách liên hệ hỏi trạng thái quá nhiều. |
| 6 | Khó quản lý tiền thu hộ. |
| 7 | Khó xử lý đơn hủy hoặc giao thất bại. |
| 8 | Không có báo cáo chính xác. |
| 9 | Khó mở rộng thêm cửa hàng/khu vực. |
| 10 | Khó khăn khác *(có ô nhập text bổ sung)* |

> **Tick 'Other'** trên Tally để khách nhập thêm khi chọn option có marker ở trên.

---

## 📝 Block 14 — Q14

**Câu hỏi chính:** Dự án được xem là thành công khi đạt được kết quả nào?

---

## 📝 Block 15 — Q15

**Câu hỏi chính:** Khu vực triển khai ban đầu ở đâu?

**Loại câu hỏi:** Checkboxes (multi-select, 5 lựa chọn)

| # | Lựa chọn |
|---|---|
| 1 | Một xã/phường hoặc khu vực nhỏ. |
| 2 | Một huyện/quận. |
| 3 | Một tỉnh/thành phố. |
| 4 | Nhiều tỉnh/thành phố. |
| 5 | Khu vực cụ thể *(có ô nhập text bổ sung)* |

> **Tick 'Other'** trên Tally để khách nhập thêm khi chọn option có marker ở trên.

---

## 📝 Block 16 — Q16

**Câu hỏi chính:** Quy mô dự kiến trong 6 tháng đầu

---

## 📝 Block 17 — Q17

**Câu hỏi chính:** Hệ thống cần hoạt động trong khung giờ nào?

**Loại câu hỏi:** Checkboxes (multi-select, 4 lựa chọn)

| # | Lựa chọn |
|---|---|
| 1 | Theo giờ mở cửa chung: từ  đến . *(có ô nhập text bổ sung)* |
| 2 | Mỗi cửa hàng có giờ mở cửa riêng. |
| 3 | Hoạt động 24/7. |
| 4 | Có ngày nghỉ cố định *(có ô nhập text bổ sung)* |

> **Tick 'Other'** trên Tally để khách nhập thêm khi chọn option có marker ở trên.

---

## 📝 Block 18 — Q18

**Câu hỏi chính:** Khách được đặt giao trong phạm vi nào?

**Loại câu hỏi:** Checkboxes (multi-select, 5 lựa chọn)

| # | Lựa chọn |
|---|---|
| 1 | Chỉ trong khu vực phục vụ cố định. |
| 2 | Trong khoảng cách tối đa tính từ cửa hàng. |
| 3 | Theo danh sách xã/phường được cấu hình. |
| 4 | Nhân viên kiểm tra và xác nhận thủ công. |
| 5 | Chưa xác định — cần tư vấn. |

> **Tick 'Other'** trên Tally để khách nhập thêm khi chọn option có marker ở trên.

---

## 📝 Block 19 — Q19

**Câu hỏi chính:** Cách triển khai mong muốn

**Loại câu hỏi:** Checkboxes (multi-select, 4 lựa chọn)

| # | Lựa chọn |
|---|---|
| 1 | Thử nghiệm với một số cửa hàng và tài xế trước. |
| 2 | Mở toàn bộ khu vực ngay khi ra mắt. |
| 3 | Triển khai theo nhiều giai đoạn. |
| 4 | Chưa xác định — cần tư vấn. |

> **Tick 'Other'** trên Tally để khách nhập thêm khi chọn option có marker ở trên.

---

## 📝 Block 20 — Q20

**Câu hỏi chính:** Khách có bắt buộc đăng ký tài khoản trước khi đặt món?

**Loại câu hỏi:** Checkboxes (multi-select, 4 lựa chọn)

| # | Lựa chọn |
|---|---|
| 1 | Có. |
| 2 | Không, được đặt nhanh bằng số điện thoại. |
| 3 | Được xem món không cần tài khoản; đăng nhập khi xác nhận đơn. |
| 4 | Chưa xác định — cần tư vấn. |

> **Tick 'Other'** trên Tally để khách nhập thêm khi chọn option có marker ở trên.

---

## 📝 Block 21 — Q21

**Câu hỏi chính:** Khách đăng nhập bằng cách nào?

**Loại câu hỏi:** Checkboxes (multi-select, 6 lựa chọn)

| # | Lựa chọn |
|---|---|
| 1 | Số điện thoại và mã xác nhận OTP. |
| 2 | Số điện thoại và mật khẩu. |
| 3 | Google. |
| 4 | Apple. |
| 5 | Facebook. |
| 6 | Cách khác *(có ô nhập text bổ sung)* |

> **Tick 'Other'** trên Tally để khách nhập thêm khi chọn option có marker ở trên.

---

## 📝 Block 22 — Q22

**Câu hỏi chính:** Khách cần quản lý địa chỉ giao hàng như thế nào?

**Loại câu hỏi:** Checkboxes (multi-select, 5 lựa chọn)

| # | Lựa chọn |
|---|---|
| 1 | Chỉ nhập địa chỉ cho từng đơn. |
| 2 | Lưu được nhiều địa chỉ như Nhà, Công ty. |
| 3 | Chọn vị trí trên bản đồ và bổ sung mô tả. |
| 4 | Dùng vị trí hiện tại của điện thoại. |
| 5 | Nhân viên xác nhận lại địa chỉ qua điện thoại. |

> **Tick 'Other'** trên Tally để khách nhập thêm khi chọn option có marker ở trên.

---

## 📝 Block 23 — Q23

**Câu hỏi chính:** Khách tìm cửa hàng và món ăn theo cách nào?

**Loại câu hỏi:** Checkboxes (multi-select, 8 lựa chọn)

| # | Lựa chọn |
|---|---|
| 1 | Danh sách cửa hàng gần nhất. |
| 2 | Danh mục món ăn. |
| 3 | Tìm theo tên cửa hàng. |
| 4 | Tìm theo tên món. |
| 5 | Lọc theo khoảng cách. |
| 6 | Lọc theo trạng thái đang mở cửa. |
| 7 | Danh sách cửa hàng nổi bật/được đề xuất. |
| 8 | Cách khác *(có ô nhập text bổ sung)* |

> **Tick 'Other'** trên Tally để khách nhập thêm khi chọn option có marker ở trên.

---

## 📝 Block 24 — Q24

**Câu hỏi chính:** Khách cần thao tác gì khi chọn món?

**Loại câu hỏi:** Checkboxes (multi-select, 7 lựa chọn)

| # | Lựa chọn |
|---|---|
| 1 | Chọn số lượng. |
| 2 | Chọn kích cỡ/phiên bản món. |
| 3 | Chọn topping hoặc món thêm. |
| 4 | Ghi chú cho từng món. |
| 5 | Xem thành phần hoặc mô tả món. |
| 6 | Xem ảnh món. |
| 7 | Không cần tùy chọn phức tạp. |

> **Tick 'Other'** trên Tally để khách nhập thêm khi chọn option có marker ở trên.

---

## 📝 Block 25 — Q25

**Câu hỏi chính:** Thông tin nào cần hiển thị trước khi khách xác nhận đơn?

**Loại câu hỏi:** Checkboxes (multi-select, 9 lựa chọn)

| # | Lựa chọn |
|---|---|
| 1 | Danh sách món và số lượng. |
| 2 | Giá từng món. |
| 3 | Phí giao hàng. |
| 4 | Tổng tiền cần thanh toán. |
| 5 | Địa chỉ giao hàng. |
| 6 | Thời gian giao dự kiến. |
| 7 | Ghi chú cho cửa hàng. |
| 8 | Ghi chú cho tài xế. |
| 9 | Điều kiện hủy đơn. |

> **Tick 'Other'** trên Tally để khách nhập thêm khi chọn option có marker ở trên.

---

## 📝 Block 26 — Q26

**Câu hỏi chính:** Khách có được đặt món trước theo ngày/giờ không?

**Loại câu hỏi:** Checkboxes (multi-select, 4 lựa chọn)

| # | Lựa chọn |
|---|---|
| 1 | Không, chỉ đặt giao ngay. |
| 2 | Có, chọn thời gian mong muốn. |
| 3 | Chỉ một số cửa hàng hỗ trợ. |
| 4 | Tính năng tương lai. |

> **Tick 'Other'** trên Tally để khách nhập thêm khi chọn option có marker ở trên.

---

## 📝 Block 27 — Q27

**Câu hỏi chính:** Trong lúc giao, khách cần xem hoặc thực hiện những gì?

**Loại câu hỏi:** Checkboxes (multi-select, 9 lựa chọn)

| # | Lựa chọn |
|---|---|
| 1 | Xem trạng thái đơn. |
| 2 | Xem thời gian giao dự kiến. |
| 3 | Xem vị trí tài xế trên bản đồ. |
| 4 | Xem tên và số điện thoại tài xế. |
| 5 | Gọi tài xế. |
| 6 | Gọi cửa hàng. |
| 7 | Liên hệ bộ phận hỗ trợ. |
| 8 | Hủy đơn nếu vẫn còn được phép. |
| 9 | Nội dung khác *(có ô nhập text bổ sung)* |

> **Tick 'Other'** trên Tally để khách nhập thêm khi chọn option có marker ở trên.

---

## 📝 Block 28 — Q28

**Câu hỏi chính:** Một cửa hàng cần bao nhiêu người sử dụng hệ thống?

**Loại câu hỏi:** Checkboxes (multi-select, 4 lựa chọn)

| # | Lựa chọn |
|---|---|
| 1 | Một tài khoản dùng chung. |
| 2 | Nhiều tài khoản nhân viên. |
| 3 | Có chủ cửa hàng và nhân viên với quyền khác nhau. |
| 4 | Chưa xác định — cần tư vấn. |

> **Tick 'Other'** trên Tally để khách nhập thêm khi chọn option có marker ở trên.

---

## 📝 Block 29 — Q29

**Câu hỏi chính:** Cửa hàng cần quản lý trạng thái hoạt động nào?

**Loại câu hỏi:** Checkboxes (multi-select, 5 lựa chọn)

| # | Lựa chọn |
|---|---|
| 1 | Mở cửa/Đóng cửa theo lịch. |
| 2 | Tạm dừng nhận đơn. |
| 3 | Quá tải — kéo dài thời gian chuẩn bị. |
| 4 | Nghỉ đột xuất. |
| 5 | Không cần, Admin quản lý toàn bộ. |

> **Tick 'Other'** trên Tally để khách nhập thêm khi chọn option có marker ở trên.

---

## 📝 Block 30 — Q30

**Câu hỏi chính:** Khi có đơn mới, cửa hàng cần làm gì?

**Loại câu hỏi:** Checkboxes (multi-select, 7 lựa chọn)

| # | Lựa chọn |
|---|---|
| 1 | Nhận thông báo và âm thanh cảnh báo. |
| 2 | Xem chi tiết đơn. |
| 3 | Chấp nhận đơn. |
| 4 | Từ chối và chọn lý do. |
| 5 | Nhập thời gian chuẩn bị dự kiến. |
| 6 | Liên hệ khách khi cần. |
| 7 | In phiếu bếp/in hóa đơn. |

> **Tick 'Other'** trên Tally để khách nhập thêm khi chọn option có marker ở trên.

---

## 📝 Block 31 — Q31

**Câu hỏi chính:** Nếu cửa hàng không phản hồi đơn trong thời gian quy định thì xử lý thế nào?

**Loại câu hỏi:** Checkboxes (multi-select, 5 lựa chọn)

| # | Lựa chọn |
|---|---|
| 1 | Nhắc lại cho cửa hàng. |
| 2 | Thông báo nhân viên vận hành. |
| 3 | Tự động hủy đơn. |
| 4 | Nhân viên gọi xác nhận thủ công. |
| 5 | Chưa xác định — cần tư vấn. |

> **Tick 'Other'** trên Tally để khách nhập thêm khi chọn option có marker ở trên.

---

## 📝 Block 32 — Q32

**Câu hỏi chính:** Ai chịu trách nhiệm tạo và cập nhật thực đơn?

**Loại câu hỏi:** Checkboxes (multi-select, 5 lựa chọn)

| # | Lựa chọn |
|---|---|
| 1 | Cửa hàng tự quản lý. |
| 2 | Admin quản lý cho cửa hàng. |
| 3 | Cửa hàng cập nhật; Admin phê duyệt. |
| 4 | Nhập dữ liệu ban đầu bởi đội dự án, sau đó cửa hàng quản lý. |
| 5 | Chưa xác định — cần tư vấn. |

> **Tick 'Other'** trên Tally để khách nhập thêm khi chọn option có marker ở trên.

---

## 📝 Block 33 — Q33

**Câu hỏi chính:** Thực đơn cần hỗ trợ những nội dung nào?

**Loại câu hỏi:** Checkboxes (multi-select, 10 lựa chọn)

| # | Lựa chọn |
|---|---|
| 1 | Danh mục món. |
| 2 | Tên và mô tả món. |
| 3 | Ảnh món. |
| 4 | Giá bán. |
| 5 | Giá khuyến mãi. |
| 6 | Kích cỡ/phiên bản món. |
| 7 | Topping/món thêm. |
| 8 | Món bán theo khung giờ. |
| 9 | Món nổi bật. |
| 10 | Nội dung khác *(có ô nhập text bổ sung)* |

> **Tick 'Other'** trên Tally để khách nhập thêm khi chọn option có marker ở trên.

---

## 📝 Block 34 — Q34

**Câu hỏi chính:** Cửa hàng xử lý món tạm hết như thế nào?

**Loại câu hỏi:** Checkboxes (multi-select, 5 lựa chọn)

| # | Lựa chọn |
|---|---|
| 1 | Bật/tắt món thủ công. |
| 2 | Chọn thời gian món có lại. |
| 3 | Báo khách và đề xuất đổi món sau khi đã đặt. |
| 4 | Admin cập nhật thay cửa hàng. |
| 5 | Không cần quản lý tồn món trong MVP. |

> **Tick 'Other'** trên Tally để khách nhập thêm khi chọn option có marker ở trên.

---

## 📝 Block 35 — Q35

**Câu hỏi chính:** Cửa hàng có được tự thay đổi giá món?

**Loại câu hỏi:** Checkboxes (multi-select, 4 lựa chọn)

| # | Lựa chọn |
|---|---|
| 1 | Có, áp dụng ngay. |
| 2 | Có, nhưng cần Admin phê duyệt. |
| 3 | Không, chỉ Admin được thay đổi. |
| 4 | Chưa xác định — cần tư vấn. |

> **Tick 'Other'** trên Tally để khách nhập thêm khi chọn option có marker ở trên.

---

## 📝 Block 36 — Q36

**Câu hỏi chính:** Cửa hàng cần xem những thông tin nào sau bán hàng?

**Loại câu hỏi:** Checkboxes (multi-select, 7 lựa chọn)

| # | Lựa chọn |
|---|---|
| 1 | Lịch sử đơn. |
| 2 | Số đơn hoàn thành/hủy. |
| 3 | Doanh thu theo ngày/tháng. |
| 4 | Số tiền cần đối soát. |
| 5 | Món bán chạy. |
| 6 | Đánh giá/phản hồi của khách. |
| 7 | Không cần báo cáo trong MVP. |

> **Tick 'Other'** trên Tally để khách nhập thêm khi chọn option có marker ở trên.

---

## 📝 Block 37 — Q37

**Câu hỏi chính:** Vui lòng xác nhận luồng đơn hàng cơ bản

**Loại câu hỏi:** Checkboxes (multi-select, 2 lựa chọn)

| # | Lựa chọn |
|---|---|
| 1 | Đồng ý với luồng trên. |
| 2 | Cần điều chỉnh như sau *(có ô nhập text bổ sung)* |

> **Tick 'Other'** trên Tally để khách nhập thêm khi chọn option có marker ở trên.

---

## 📝 Block 38 — Q38

**Câu hỏi chính:** Cửa hàng có cần cập nhật riêng trạng thái “đang chuẩn bị” và “đã sẵn sàng”?

**Loại câu hỏi:** Checkboxes (multi-select, 4 lựa chọn)

| # | Lựa chọn |
|---|---|
| 1 | Có cả hai trạng thái. |
| 2 | Chỉ cần “đã sẵn sàng”. |
| 3 | Không cần; khi chấp nhận được xem là đang chuẩn bị. |
| 4 | Chưa xác định — cần tư vấn. |

> **Tick 'Other'** trên Tally để khách nhập thêm khi chọn option có marker ở trên.

---

## 📝 Block 39 — Q39

**Câu hỏi chính:** Khách được hủy đơn trong trường hợp nào?

**Loại câu hỏi:** Checkboxes (multi-select, 5 lựa chọn)

| # | Lựa chọn |
|---|---|
| 1 | Trước khi cửa hàng chấp nhận. |
| 2 | Sau khi cửa hàng chấp nhận nhưng chưa chuẩn bị. |
| 3 | Khi chưa tìm được tài xế sau  phút. *(có ô nhập text bổ sung)* |
| 4 | Chỉ Admin có quyền hủy sau khi cửa hàng chấp nhận. |
| 5 | Trường hợp khác *(có ô nhập text bổ sung)* |

> **Tick 'Other'** trên Tally để khách nhập thêm khi chọn option có marker ở trên.

---

## 📝 Block 40 — Q40

**Câu hỏi chính:** Cửa hàng được hủy/từ chối đơn trong trường hợp nào?

**Loại câu hỏi:** Checkboxes (multi-select, 6 lựa chọn)

| # | Lựa chọn |
|---|---|
| 1 | Hết món. |
| 2 | Đóng cửa/quá tải. |
| 3 | Không giao được đến khu vực của khách. |
| 4 | Không liên hệ được khách. |
| 5 | Sau khi đã chấp nhận, cửa hàng không được tự hủy. |
| 6 | Trường hợp khác *(có ô nhập text bổ sung)* |

> **Tick 'Other'** trên Tally để khách nhập thêm khi chọn option có marker ở trên.

---

## 📝 Block 41 — Q41

**Câu hỏi chính:** Nếu một món trong đơn bị hết sau khi khách đã đặt thì xử lý thế nào?

**Loại câu hỏi:** Checkboxes (multi-select, 5 lựa chọn)

| # | Lựa chọn |
|---|---|
| 1 | Cửa hàng từ chối toàn bộ đơn. |
| 2 | Cửa hàng gọi khách để đổi món. |
| 3 | Cửa hàng đề xuất món thay thế trên hệ thống. |
| 4 | Xóa món hết và điều chỉnh tổng tiền với sự đồng ý của khách. |
| 5 | Nhân viên vận hành xử lý thủ công. |

> **Tick 'Other'** trên Tally để khách nhập thêm khi chọn option có marker ở trên.

---

## 📝 Block 42 — Q42

**Câu hỏi chính:** Nếu không tìm được tài xế thì xử lý thế nào?

**Loại câu hỏi:** Checkboxes (multi-select, 6 lựa chọn)

| # | Lựa chọn |
|---|---|
| 1 | Tiếp tục tìm trong phạm vi rộng hơn. |
| 2 | Chuyển cho nhân viên vận hành chọn thủ công. |
| 3 | Thông báo khách chờ thêm. |
| 4 | Cho khách hủy đơn. |
| 5 | Tự động hủy sau  phút. *(có ô nhập text bổ sung)* |
| 6 | Cách khác *(có ô nhập text bổ sung)* |

> **Tick 'Other'** trên Tally để khách nhập thêm khi chọn option có marker ở trên.

---

## 📝 Block 43 — Q43

**Câu hỏi chính:** Nếu khách không nghe máy hoặc không nhận hàng thì xử lý thế nào?

**Loại câu hỏi:** Checkboxes (multi-select, 6 lựa chọn)

| # | Lựa chọn |
|---|---|
| 1 | Tài xế thử liên hệ ít nhất  lần trong  phút. *(có ô nhập text bổ sung)* |
| 2 | Tài xế liên hệ bộ phận hỗ trợ. |
| 3 | Tài xế trả món về cửa hàng. |
| 4 | Đơn được đánh dấu giao thất bại. |
| 5 | Khách chịu một khoản phí theo chính sách. |
| 6 | Cách xử lý khác *(có ô nhập text bổ sung)* |

> **Tick 'Other'** trên Tally để khách nhập thêm khi chọn option có marker ở trên.

---

## 📝 Block 44 — Q44

**Câu hỏi chính:** Cần bằng chứng nào để xác nhận giao hàng thành công?

**Loại câu hỏi:** Checkboxes (multi-select, 6 lựa chọn)

| # | Lựa chọn |
|---|---|
| 1 | Tài xế bấm “Đã giao”. |
| 2 | Mã xác nhận từ khách. |
| 3 | Ảnh giao hàng. |
| 4 | Chữ ký người nhận. |
| 5 | Vị trí GPS tại điểm giao. |
| 6 | Không cần bằng chứng bổ sung trong MVP. |

> **Tick 'Other'** trên Tally để khách nhập thêm khi chọn option có marker ở trên.

---

## 📝 Block 45 — Q45

**Câu hỏi chính:** Ai tạo tài khoản tài xế?

**Loại câu hỏi:** Checkboxes (multi-select, 4 lựa chọn)

| # | Lựa chọn |
|---|---|
| 1 | Tài xế tự đăng ký. |
| 2 | Admin tạo tài khoản. |
| 3 | Tài xế đăng ký và Admin phê duyệt. |
| 4 | Doanh nghiệp nhập danh sách tài xế có sẵn. |

> **Tick 'Other'** trên Tally để khách nhập thêm khi chọn option có marker ở trên.

---

## 📝 Block 46 — Q46

**Câu hỏi chính:** Tài xế cần cung cấp/xác minh thông tin nào?

**Loại câu hỏi:** Checkboxes (multi-select, 8 lựa chọn)

| # | Lựa chọn |
|---|---|
| 1 | Họ tên và số điện thoại. |
| 2 | Ảnh đại diện. |
| 3 | CCCD/giấy tờ tùy thân. |
| 4 | Giấy phép lái xe. |
| 5 | Thông tin phương tiện và biển số. |
| 6 | Tài khoản ngân hàng. |
| 7 | Khu vực hoạt động. |
| 8 | Không cần xác minh giấy tờ trong MVP. |

> **Tick 'Other'** trên Tally để khách nhập thêm khi chọn option có marker ở trên.

---

## 📝 Block 47 — Q47

**Câu hỏi chính:** Tài xế cần những trạng thái hoạt động nào?

**Loại câu hỏi:** Checkboxes (multi-select, 6 lựa chọn)

| # | Lựa chọn |
|---|---|
| 1 | Online — sẵn sàng nhận đơn. |
| 2 | Đang xem đề nghị giao hàng. |
| 3 | Đang thực hiện đơn. |
| 4 | Tạm nghỉ. |
| 5 | Offline. |
| 6 | Bị tạm khóa bởi Admin. |

> **Tick 'Other'** trên Tally để khách nhập thêm khi chọn option có marker ở trên.

---

## 📝 Block 48 — Q48

**Câu hỏi chính:** Tiêu chí nào quan trọng khi hệ thống chọn tài xế?

**Loại câu hỏi:** Checkboxes (multi-select, 7 lựa chọn)

| # | Lựa chọn |
|---|---|
| 1 | Gần cửa hàng nhất. |
| 2 | Đang online và không có đơn khác. |
| 3 | Hoạt động trong đúng khu vực. |
| 4 | Đã chờ lâu nhưng chưa nhận được đơn. |
| 5 | Tỷ lệ nhận/hoàn thành đơn tốt. |
| 6 | Nhân viên vận hành ưu tiên thủ công. |
| 7 | Chỉ cần tiêu chí đơn giản cho MVP: gần nhất và đang rảnh. |

> **Tick 'Other'** trên Tally để khách nhập thêm khi chọn option có marker ở trên.

---

## 📝 Block 49 — Q49

**Câu hỏi chính:** Đề nghị giao hàng nên được gửi như thế nào?

**Loại câu hỏi:** Checkboxes (multi-select, 5 lựa chọn)

| # | Lựa chọn |
|---|---|
| 1 | Gửi lần lượt cho từng tài xế; hết thời gian mới chuyển người tiếp theo. |
| 2 | Gửi cho một nhóm tài xế gần nhất; người nhận trước được giao đơn. |
| 3 | Nhân viên chọn và gửi cho một tài xế cụ thể. |
| 4 | Kết hợp tự động và thủ công. |
| 5 | Chưa xác định — cần tư vấn. |

> **Tick 'Other'** trên Tally để khách nhập thêm khi chọn option có marker ở trên.

---

## 📝 Block 50 — Q50

**Câu hỏi chính:** Tài xế có bao lâu để chấp nhận đề nghị giao hàng?

**Loại câu hỏi:** Checkboxes (multi-select, 5 lựa chọn)

| # | Lựa chọn |
|---|---|
| 1 | 10 giây. |
| 2 | 15 giây. |
| 3 | 30 giây. |
| 4 | Thời gian khác:  giây. *(có ô nhập text bổ sung)* |
| 5 | Chưa xác định — cần tư vấn. |

> **Tick 'Other'** trên Tally để khách nhập thêm khi chọn option có marker ở trên.

---

## 📝 Block 51 — Q51

**Câu hỏi chính:** Khi tài xế từ chối hoặc không phản hồi thì sao?

**Loại câu hỏi:** Checkboxes (multi-select, 5 lựa chọn)

| # | Lựa chọn |
|---|---|
| 1 | Tự động tìm tài xế tiếp theo. |
| 2 | Hỏi lý do từ chối. |
| 3 | Thông báo nhân viên vận hành sau  lần thất bại. *(có ô nhập text bổ sung)* |
| 4 | Chuyển hoàn toàn sang xử lý thủ công. |
| 5 | Cách khác *(có ô nhập text bổ sung)* |

> **Tick 'Other'** trên Tally để khách nhập thêm khi chọn option có marker ở trên.

---

## 📝 Block 52 — Q52

**Câu hỏi chính:** Tài xế có được hủy sau khi đã nhận đơn?

**Loại câu hỏi:** Checkboxes (multi-select, 4 lựa chọn)

| # | Lựa chọn |
|---|---|
| 1 | Không. |
| 2 | Có, phải chọn lý do. |
| 3 | Có, nhưng cần Admin phê duyệt. |
| 4 | Chỉ trong trường hợp khẩn cấp. |

> **Tick 'Other'** trên Tally để khách nhập thêm khi chọn option có marker ở trên.

**Câu bổ sung (nhập text):**

- **Mô tả chi tiết** — Loại: Short text

---

## 📝 Block 53 — Q53

**Câu hỏi chính:** Khi tài xế đã nhận nhưng không di chuyển hoặc mất kết nối thì xử lý thế nào?

**Loại câu hỏi:** Checkboxes (multi-select, 5 lựa chọn)

| # | Lựa chọn |
|---|---|
| 1 | Gửi nhắc nhở cho tài xế. |
| 2 | Thông báo nhân viên vận hành. |
| 3 | Cho phép Admin đổi tài xế. |
| 4 | Tự động đổi tài xế sau  phút. *(có ô nhập text bổ sung)* |
| 5 | Nhân viên gọi xác nhận trước khi đổi. |

> **Tick 'Other'** trên Tally để khách nhập thêm khi chọn option có marker ở trên.

---

## 📝 Block 54 — Q54

**Câu hỏi chính:** Tài xế và khách cần sử dụng bản đồ như thế nào?

**Loại câu hỏi:** Checkboxes (multi-select, 7 lựa chọn)

| # | Lựa chọn |
|---|---|
| 1 | Tài xế xem đường đến cửa hàng. |
| 2 | Tài xế xem đường đến khách. |
| 3 | Mở ứng dụng Google Maps/Apple Maps để dẫn đường. |
| 4 | Dẫn đường ngay trong ứng dụng tài xế. |
| 5 | Khách xem vị trí tài xế khi đơn đang giao. |
| 6 | Cửa hàng xem vị trí tài xế đang đến lấy món. |
| 7 | Admin xem vị trí các tài xế đang hoạt động. |

> **Tick 'Other'** trên Tally để khách nhập thêm khi chọn option có marker ở trên.

---

## 📝 Block 55 — Q55

**Câu hỏi chính:** Phí giao hàng được tính theo cách nào?

**Loại câu hỏi:** Checkboxes (multi-select, 7 lựa chọn)

| # | Lựa chọn |
|---|---|
| 1 | Mức phí cố định cho mọi đơn. |
| 2 | Theo khoảng cách. |
| 3 | Theo khu vực/xã/phường. |
| 4 | Theo từng cửa hàng. |
| 5 | Admin nhập thủ công. |
| 6 | Miễn phí giao hàng trong một số trường hợp. |
| 7 | Chưa xác định — cần tư vấn. |

> **Tick 'Other'** trên Tally để khách nhập thêm khi chọn option có marker ở trên.

---

## 📝 Block 56 — Q56

**Câu hỏi chính:** Phí giao hàng được hiển thị và thu như thế nào?

**Loại câu hỏi:** Checkboxes (multi-select, 4 lựa chọn)

| # | Lựa chọn |
|---|---|
| 1 | Cộng vào tổng tiền khách trả tài xế. |
| 2 | Cửa hàng trả phí giao hàng. |
| 3 | Doanh nghiệp hỗ trợ một phần. |
| 4 | Chia theo quy tắc khác *(có ô nhập text bổ sung)* |

> **Tick 'Other'** trên Tally để khách nhập thêm khi chọn option có marker ở trên.

---

## 📝 Block 57 — Q57

**Câu hỏi chính:** Tài xế sẽ thu những khoản tiền nào từ khách?

**Loại câu hỏi:** Checkboxes (multi-select, 4 lựa chọn)

| # | Lựa chọn |
|---|---|
| 1 | Tiền món ăn và phí giao hàng. |
| 2 | Chỉ tiền món ăn. |
| 3 | Chỉ phí giao hàng. |
| 4 | Khoản khác *(có ô nhập text bổ sung)* |

> **Tick 'Other'** trên Tally để khách nhập thêm khi chọn option có marker ở trên.

---

## 📝 Block 58 — Q58

**Câu hỏi chính:** Tiền COD được đối soát theo quy trình nào?

**Loại câu hỏi:** Checkboxes (multi-select, 6 lựa chọn)

| # | Lựa chọn |
|---|---|
| 1 | Tài xế ứng trước/nộp tiền món cho cửa hàng khi nhận món, sau đó thu lại từ khách. |
| 2 | Tài xế thu tiền và nộp lại doanh nghiệp cuối ngày. |
| 3 | Đối soát theo tuần. |
| 4 | Tài xế chuyển khoản theo từng đơn. |
| 5 | Doanh nghiệp chưa có quy trình — cần tư vấn. |
| 6 | Quy trình khác *(có ô nhập text bổ sung)* |

> **Tick 'Other'** trên Tally để khách nhập thêm khi chọn option có marker ở trên.

---

## 📝 Block 59 — Q59

**Câu hỏi chính:** Tài xế được trả thu nhập như thế nào?

**Loại câu hỏi:** Checkboxes (multi-select, 6 lựa chọn)

| # | Lựa chọn |
|---|---|
| 1 | Nhận toàn bộ phí giao hàng. |
| 2 | Nhận mức cố định theo đơn. |
| 3 | Nhận theo khoảng cách. |
| 4 | Nhận lương cố định. |
| 5 | Kết hợp lương và phí theo đơn. |
| 6 | Cách khác *(có ô nhập text bổ sung)* |

> **Tick 'Other'** trên Tally để khách nhập thêm khi chọn option có marker ở trên.

---

## 📝 Block 60 — Q60

**Câu hỏi chính:** Doanh nghiệp thu phí/hoa hồng từ cửa hàng như thế nào?

**Loại câu hỏi:** Checkboxes (multi-select, 6 lựa chọn)

| # | Lựa chọn |
|---|---|
| 1 | Không thu trong MVP. |
| 2 | Mức cố định theo đơn. |
| 3 | Phần trăm giá trị đơn. |
| 4 | Phí thành viên theo tháng. |
| 5 | Kết hợp nhiều loại phí. |
| 6 | Chưa xác định — cần tư vấn. |

> **Tick 'Other'** trên Tally để khách nhập thêm khi chọn option có marker ở trên.

---

## 📝 Block 61 — Q61

**Câu hỏi chính:** Khi đơn bị hủy hoặc giao thất bại, tiền và công nợ được xử lý thế nào?

**Câu bổ sung (nhập text):**

- **Mô tả chi tiết** — Loại: Short text
- **Mô tả chi tiết** — Loại: Short text

---

## 📝 Block 62 — Q62

**Câu hỏi chính:** Những vai trò nào cần sử dụng Web Admin?

**Loại câu hỏi:** Checkboxes (multi-select, 7 lựa chọn)

| # | Lựa chọn |
|---|---|
| 1 | Chủ doanh nghiệp/Super Admin. |
| 2 | Nhân viên điều phối tài xế. |
| 3 | Nhân viên chăm sóc khách hàng. |
| 4 | Nhân viên quản lý cửa hàng/thực đơn. |
| 5 | Kế toán/đối soát. |
| 6 | Chỉ cần một loại tài khoản Admin trong MVP. |
| 7 | Vai trò khác *(có ô nhập text bổ sung)* |

> **Tick 'Other'** trên Tally để khách nhập thêm khi chọn option có marker ở trên.

---

## 📝 Block 63 — Q63

**Câu hỏi chính:** Admin cần quản lý những nội dung nào?

**Loại câu hỏi:** Checkboxes (multi-select, 11 lựa chọn)

| # | Lựa chọn |
|---|---|
| 1 | Khách hàng. |
| 2 | Cửa hàng và tài khoản cửa hàng. |
| 3 | Danh mục và món ăn. |
| 4 | Tài xế và hồ sơ xác minh. |
| 5 | Đơn hàng. |
| 6 | Phân công/đổi tài xế. |
| 7 | Phí giao hàng. |
| 8 | Khu vực hoạt động. |
| 9 | Banner/nội dung hiển thị. |
| 10 | Thông báo hệ thống. |
| 11 | Cấu hình khác *(có ô nhập text bổ sung)* |

> **Tick 'Other'** trên Tally để khách nhập thêm khi chọn option có marker ở trên.

---

## 📝 Block 64 — Q64

**Câu hỏi chính:** Admin được phép can thiệp vào đơn hàng như thế nào?

**Loại câu hỏi:** Checkboxes (multi-select, 8 lựa chọn)

| # | Lựa chọn |
|---|---|
| 1 | Xem toàn bộ lịch sử trạng thái. |
| 2 | Chấp nhận/từ chối thay cửa hàng. |
| 3 | Chỉ định hoặc đổi tài xế. |
| 4 | Hủy đơn và ghi lý do. |
| 5 | Điều chỉnh phí giao hàng. |
| 6 | Điều chỉnh tổng tiền với lịch sử thay đổi. |
| 7 | Đánh dấu giao thành công/thất bại. |
| 8 | Liên hệ nhanh với khách, cửa hàng và tài xế. |

> **Tick 'Other'** trên Tally để khách nhập thêm khi chọn option có marker ở trên.

---

## 📝 Block 65 — Q65

**Câu hỏi chính:** Những thông báo nào là bắt buộc?

---

## 📝 Block 66 — Q66

**Câu hỏi chính:** Doanh nghiệp cần những báo cáo nào trong MVP?

**Loại câu hỏi:** Checkboxes (multi-select, 10 lựa chọn)

| # | Lựa chọn |
|---|---|
| 1 | Tổng số đơn theo ngày/tháng. |
| 2 | Đơn hoàn thành, hủy và giao thất bại. |
| 3 | Doanh thu/giá trị đơn hàng. |
| 4 | Phí giao hàng. |
| 5 | Doanh số theo cửa hàng. |
| 6 | Hiệu suất tài xế. |
| 7 | Tiền COD và công nợ. |
| 8 | Món bán chạy. |
| 9 | Xuất Excel/CSV. |
| 10 | Báo cáo khác *(có ô nhập text bổ sung)* |

> **Tick 'Other'** trên Tally để khách nhập thêm khi chọn option có marker ở trên.

---

## 📝 Block 67 — Q67

**Câu hỏi chính:** Khi có khiếu nại hoặc tranh chấp, ai xử lý?

**Loại câu hỏi:** Checkboxes (multi-select, 4 lựa chọn)

| # | Lựa chọn |
|---|---|
| 1 | Cửa hàng xử lý trực tiếp. |
| 2 | Bộ phận chăm sóc khách hàng của doanh nghiệp. |
| 3 | Nhân viên vận hành/Admin. |
| 4 | Chưa có quy trình — cần tư vấn. |

> **Tick 'Other'** trên Tally để khách nhập thêm khi chọn option có marker ở trên.

---

## 📝 Block 68 — Q68

**Câu hỏi chính:** Khách, cửa hàng và tài xế liên hệ hỗ trợ bằng kênh nào?

**Loại câu hỏi:** Checkboxes (multi-select, 6 lựa chọn)

| # | Lựa chọn |
|---|---|
| 1 | Gọi hotline. |
| 2 | Zalo. |
| 3 | Email. |
| 4 | Biểu mẫu hỗ trợ trong ứng dụng. |
| 5 | Chat trực tiếp trong ứng dụng — tính năng tương lai. |
| 6 | Kênh khác *(có ô nhập text bổ sung)* |

> **Tick 'Other'** trên Tally để khách nhập thêm khi chọn option có marker ở trên.

---

## 📝 Block 69 — Q69

**Câu hỏi chính:** Người dùng sẽ sử dụng hệ thống trên thiết bị nào?

---

## 📝 Block 70 — Q70

**Câu hỏi chính:** Yêu cầu về thương hiệu và giao diện

**Loại câu hỏi:** Checkboxes (multi-select, 5 lựa chọn)

| # | Lựa chọn |
|---|---|
| 1 | Đã có logo và bộ nhận diện thương hiệu. |
| 2 | Đã có thiết kế giao diện hoàn chỉnh. |
| 3 | Cần đội dự án thiết kế trải nghiệm và giao diện (UI/UX) từ đầu. |
| 4 | Có ứng dụng tham khảo mong muốn. |
| 5 | Chỉ cần giao diện đơn giản để thử nghiệm MVP. |

> **Tick 'Other'** trên Tally để khách nhập thêm khi chọn option có marker ở trên.

---

## 📝 Block 71 — Q71

**Câu hỏi chính:** Ngôn ngữ cần hỗ trợ

**Loại câu hỏi:** Checkboxes (multi-select, 3 lựa chọn)

| # | Lựa chọn |
|---|---|
| 1 | Chỉ tiếng Việt. |
| 2 | Tiếng Việt và tiếng Anh. |
| 3 | Ngôn ngữ khác *(có ô nhập text bổ sung)* |

> **Tick 'Other'** trên Tally để khách nhập thêm khi chọn option có marker ở trên.

---

## 📝 Block 72 — Q72

**Câu hỏi chính:** Dữ liệu và quyền riêng tư cần lưu ý điều gì?

**Loại câu hỏi:** Checkboxes (multi-select, 7 lựa chọn)

| # | Lựa chọn |
|---|---|
| 1 | Chỉ lưu thông tin cần thiết để vận hành đơn. |
| 2 | Cần chính sách bảo mật và điều khoản sử dụng. |
| 3 | Cần ghi nhận sự đồng ý khi theo dõi vị trí tài xế. |
| 4 | Chỉ theo dõi vị trí khi tài xế online/đang giao. |
| 5 | Cần quy định thời gian lưu lịch sử vị trí. |
| 6 | Cần cho phép người dùng yêu cầu cập nhật/xóa dữ liệu. |
| 7 | Chưa có chính sách — cần tư vấn. |

> **Tick 'Other'** trên Tally để khách nhập thêm khi chọn option có marker ở trên.

---

## 📝 Block 73 — Q73

**Câu hỏi chính:** Khi xảy ra sự cố hệ thống hoặc mất dữ liệu, mức chấp nhận của doanh nghiệp là gì?

**Loại câu hỏi:** Checkboxes (multi-select, 6 lựa chọn)

| # | Lựa chọn |
|---|---|
| 1 | Có thể tạm ngưng vài giờ trong giai đoạn MVP. |
| 2 | Cần hoạt động liên tục trong giờ kinh doanh. |
| 3 | Cần có người nhận cảnh báo khi hệ thống lỗi. |
| 4 | Cần sao lưu dữ liệu hằng ngày. |
| 5 | Cần khôi phục nhanh trong vòng  giờ. *(có ô nhập text bổ sung)* |
| 6 | Chưa xác định — cần tư vấn. |

> **Tick 'Other'** trên Tally để khách nhập thêm khi chọn option có marker ở trên.

---

## 📝 Block 74 — Q74

**Câu hỏi chính:** Doanh nghiệp đã có các tài khoản/dịch vụ nào?

**Loại câu hỏi:** Checkboxes (multi-select, 9 lựa chọn)

| # | Lựa chọn |
|---|---|
| 1 | Apple Developer. |
| 2 | Google Play Console. |
| 3 | Tên miền. |
| 4 | Máy chủ/Cloud. |
| 5 | Google Maps hoặc nhà cung cấp bản đồ khác. |
| 6 | Dịch vụ SMS OTP. |
| 7 | Email theo tên miền. |
| 8 | Chưa có; cần hướng dẫn đăng ký. |
| 9 | Khác *(có ô nhập text bổ sung)* |

> **Tick 'Other'** trên Tally để khách nhập thêm khi chọn option có marker ở trên.

---

## 📝 Block 75 — Q75

**Câu hỏi chính:** Ai là người kiểm tra và xác nhận sản phẩm hoàn thành?

---

## 📝 Block 76 — Q76

**Câu hỏi chính:** Hình thức bàn giao mong muốn

**Loại câu hỏi:** Checkboxes (multi-select, 8 lựa chọn)

| # | Lựa chọn |
|---|---|
| 1 | Mã nguồn đầy đủ. |
| 2 | Tài liệu hướng dẫn sử dụng. |
| 3 | Tài liệu cài đặt và vận hành. |
| 4 | Tài khoản quản trị và tài khoản dịch vụ. |
| 5 | Hướng dẫn/đào tạo cho Admin. |
| 6 | Hướng dẫn/đào tạo cho cửa hàng và tài xế. |
| 7 | Hỗ trợ đưa ứng dụng lên App Store/Google Play. |
| 8 | Nội dung khác *(có ô nhập text bổ sung)* |

> **Tick 'Other'** trên Tally để khách nhập thêm khi chọn option có marker ở trên.

---

## 📝 Block 77 — Q77

**Câu hỏi chính:** Thời gian và ngân sách dự kiến

**Loại câu hỏi:** Checkboxes (multi-select, 5 lựa chọn)

| # | Lựa chọn |
|---|---|
| 1 | Dưới 150 triệu VNĐ. |
| 2 | 150–250 triệu VNĐ. |
| 3 | 250–400 triệu VNĐ. |
| 4 | Trên 400 triệu VNĐ. |
| 5 | Chưa xác định — cần đơn vị phát triển đề xuất theo phạm vi. |

> **Tick 'Other'** trên Tally để khách nhập thêm khi chọn option có marker ở trên.

---

## 📝 Block 78 — Q78

**Câu hỏi chính:** Nhu cầu bảo hành và hỗ trợ sau triển khai

**Loại câu hỏi:** Checkboxes (multi-select, 6 lựa chọn)

| # | Lựa chọn |
|---|---|
| 1 | Chỉ cần bảo hành sửa lỗi theo hợp đồng. |
| 2 | Cần gói bảo trì hằng tháng. |
| 3 | Cần giám sát hệ thống và xử lý sự cố. |
| 4 | Cần hỗ trợ cửa hàng/tài xế sử dụng hệ thống. |
| 5 | Cần tiếp tục phát triển tính năng mới theo từng giai đoạn. |
| 6 | Chưa xác định — cần tư vấn. |

> **Tick 'Other'** trên Tally để khách nhập thêm khi chọn option có marker ở trên.

**Câu bổ sung (nhập text):**

- **Mô tả chi tiết** — Loại: Short text
- **Mô tả chi tiết** — Loại: Short text

---

## ✅ Sau khi tạo xong

1. Click **'Publish'** trên Tally → copy link
2. Click **'Connect'** → chọn **Google Sheets** → tự động lưu mỗi response vào 1 dòng Sheet
3. Gửi link cho khách hàng qua email/Zalo

**Tip:** Để bật skip-logic (vd: Q07 'Không' → nhảy sang cuối), click 'Logic' trong Tally editor.

*Generated from SRQ.md — 78 questions, 1 intro block.*