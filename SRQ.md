---
title: "Bộ câu hỏi khảo sát yêu cầu — Nền tảng giao đồ ăn"
document_id: "SRQ-FDP-001"
version: "2.0"
status: "Dự thảo gửi khách hàng"
language: "vi-VN"
---

# BỘ CÂU HỎI KHẢO SÁT YÊU CẦU

## Nền tảng giao đồ ăn

| Thông tin | Nội dung |
|---|---|
| Tên dự án | ______________________________________________ |
| Tên doanh nghiệp | ______________________________________________ |
| Người đại diện | ______________________________________________ |
| Người phối hợp nghiệp vụ | ______________________________________________ |
| Đơn vị tư vấn/phát triển | ______________________________________________ |
| Ngày thực hiện khảo sát | ____ / ____ / ________ |
| Phiên bản tài liệu | 2.0 |

---

## 1. Mục đích tài liệu

Tài liệu này giúp hai bên hiểu và thống nhất nhu cầu trước khi lập Proposal, phạm vi công việc, thời gian và báo giá chính thức.

Người trả lời **không cần có kiến thức kỹ thuật**. Vui lòng chọn phương án gần nhất với nhu cầu thực tế và ghi thêm giải thích nếu cần.

Kết quả khảo sát sẽ được sử dụng để:

- Xác định phạm vi phiên bản đầu tiên (MVP).
- Mô tả quy trình đặt món và giao hàng.
- Liệt kê chức năng và màn hình của từng ứng dụng.
- Ước lượng nguồn lực, thời gian và chi phí.
- Ghi nhận các giả định, giới hạn và tính năng dự kiến trong tương lai.

> **Lưu ý:** Đây là tài liệu khảo sát, chưa phải hợp đồng hoặc cam kết báo giá. Những nội dung chưa được xác nhận sẽ được ghi rõ là giả định trong Proposal.

### Cách trả lời

- Đánh dấu `[x]` vào phương án được chọn.
- Có thể chọn nhiều phương án nếu câu hỏi cho phép.
- Ghi thêm nội dung tại dòng `Trả lời khác/Ghi chú`.
- Câu có nhãn **Nếu áp dụng** chỉ cần trả lời khi phù hợp.
- Nếu chưa quyết định, chọn **Chưa xác định — cần tư vấn**.

### Mức độ ưu tiên

Khi được yêu cầu đánh dấu độ ưu tiên, sử dụng một trong các mức sau:

| Mức | Ý nghĩa |
|---|---|
| Bắt buộc | Phải có để phiên bản đầu tiên vận hành được |
| Nên có | Quan trọng nhưng có thể triển khai sau khi MVP ổn định |
| Tương lai | Ghi nhận để thiết kế khả năng mở rộng, chưa triển khai trong MVP |
| Không cần | Không thuộc nhu cầu của dự án |

---

# PHẦN A — XÁC NHẬN PHẠM VI ĐANG HIỂU

Các nội dung dưới đây được tổng hợp từ trao đổi ban đầu. Vui lòng xác nhận hoặc sửa lại.

## Q01. Hệ thống dự kiến gồm những kênh sử dụng nào?

- [ ] Ứng dụng cho khách đặt món.
- [ ] Ứng dụng cho cửa hàng nhận và xử lý đơn.
- [ ] Ứng dụng cho tài xế nhận và giao đơn.
- [ ] Website quản trị dành cho nhân viên vận hành.
- [ ] Website đặt món cho khách.
- [ ] Kênh khác: ______________________________________________

## Q02. Mỗi cửa hàng trong phiên bản đầu tiên chỉ có một địa chỉ hoạt động?

- [ ] Đúng.
- [ ] Không, một cửa hàng có thể có nhiều chi nhánh.
- [ ] Hiện tại một địa chỉ, nhưng cần chuẩn bị cho nhiều chi nhánh trong tương lai.

**Ghi chú:** ______________________________________________

## Q03. Mỗi đơn hàng chỉ được đặt từ một cửa hàng?

- [ ] Đúng.
- [ ] Không, khách có thể đặt từ nhiều cửa hàng trong cùng một đơn.
- [ ] Chưa xác định — cần tư vấn.

## Q04. Mỗi tài xế chỉ giao một đơn tại một thời điểm trong MVP?

- [ ] Đúng.
- [ ] Không, tài xế có thể nhận nhiều đơn cùng lúc.
- [ ] MVP một đơn; tương lai cần hỗ trợ ghép nhiều đơn.

## Q05. Hình thức thanh toán chính của MVP là tiền mặt khi nhận hàng (COD)?

- [ ] Đúng, chỉ COD.
- [ ] COD và chuyển khoản trực tiếp.
- [ ] Cần thanh toán trực tuyến ngay trong MVP.
- [ ] Chưa xác định — cần tư vấn.

## Q06. Việc chọn tài xế được thực hiện như thế nào?

- [ ] Hệ thống tự chọn tài xế phù hợp.
- [ ] Nhân viên vận hành chọn tài xế.
- [ ] Hệ thống tự chọn; nhân viên có thể can thiệp khi cần.
- [ ] Cửa hàng tự chọn tài xế.
- [ ] Chưa xác định — cần tư vấn.

## Q07. Khách không được tự hủy sau khi cửa hàng đã chấp nhận đơn?

- [ ] Đúng.
- [ ] Vẫn được hủy nhưng cần cửa hàng/Admin phê duyệt.
- [ ] Được hủy ở các trạng thái khác: ______________________________________________
- [ ] Chưa xác định — cần tư vấn.

---

# PHẦN B — DOANH NGHIỆP, MỤC TIÊU VÀ QUY TRÌNH HIỆN TẠI

## Q08. Thông tin doanh nghiệp và đầu mối dự án

| Nội dung | Trả lời |
|---|---|
| Tên doanh nghiệp/đơn vị vận hành | |
| Địa chỉ | |
| Người quyết định cuối cùng | |
| Người xác nhận nghiệp vụ hằng ngày | |
| Số điện thoại/Email | |

## Q09. Dự án đang ở giai đoạn nào?

- [ ] Ý tưởng ban đầu.
- [ ] Đang thử nghiệm thủ công.
- [ ] Đã có cửa hàng và tài xế hoạt động.
- [ ] Đã có phần mềm nhưng cần thay thế.
- [ ] Đang mở rộng sang khu vực mới.
- [ ] Khác: ______________________________________________

## Q10. Ba mục tiêu quan trọng nhất của dự án là gì?

- [ ] Tăng số lượng đơn hàng.
- [ ] Giảm thời gian xử lý đơn.
- [ ] Tự động hóa việc tìm tài xế.
- [ ] Giảm sai sót khi nhận và giao hàng.
- [ ] Theo dõi đơn hàng minh bạch hơn.
- [ ] Quản lý cửa hàng tập trung.
- [ ] Quản lý tiền COD và đối soát.
- [ ] Có dữ liệu báo cáo để ra quyết định.
- [ ] Xây dựng thương hiệu và kênh bán riêng.
- [ ] Mục tiêu khác: ______________________________________________

**Mục tiêu ưu tiên số 1:** ______________________________________________

## Q11. Hiện nay đơn hàng đến từ những kênh nào?

- [ ] Điện thoại.
- [ ] Zalo.
- [ ] Facebook/Messenger.
- [ ] Website.
- [ ] Ứng dụng hiện có.
- [ ] Nhân viên nhập đơn trực tiếp.
- [ ] Chưa vận hành.
- [ ] Kênh khác: ______________________________________________

## Q12. Quy trình hiện tại từ lúc nhận đơn đến khi giao xong diễn ra như thế nào?

> Vui lòng mô tả ngắn gọn ai nhận đơn, ai xác nhận món, ai gọi tài xế, ai thu tiền và ai xử lý khi có sự cố.

**Trả lời:**

________________________________________________________________________________

________________________________________________________________________________

________________________________________________________________________________

## Q13. Những khó khăn lớn nhất trong quy trình hiện tại là gì?

- [ ] Bỏ sót hoặc nhập sai đơn.
- [ ] Cửa hàng phản hồi chậm.
- [ ] Khó tìm tài xế.
- [ ] Không biết tài xế đang ở đâu.
- [ ] Khách liên hệ hỏi trạng thái quá nhiều.
- [ ] Khó quản lý tiền thu hộ.
- [ ] Khó xử lý đơn hủy hoặc giao thất bại.
- [ ] Không có báo cáo chính xác.
- [ ] Khó mở rộng thêm cửa hàng/khu vực.
- [ ] Khó khăn khác: ______________________________________________

## Q14. Dự án được xem là thành công khi đạt được kết quả nào?

| Chỉ số mong muốn | Mục tiêu dự kiến |
|---|---|
| Số cửa hàng tham gia | |
| Số tài xế hoạt động | |
| Số đơn/ngày | |
| Thời gian trung bình từ đặt đến giao | |
| Tỷ lệ đơn hoàn thành | |
| Tỷ lệ đơn hủy | |
| Chỉ số khác | |

---

# PHẦN C — KHU VỰC VÀ QUY MÔ VẬN HÀNH

## Q15. Khu vực triển khai ban đầu ở đâu?

- [ ] Một xã/phường hoặc khu vực nhỏ.
- [ ] Một huyện/quận.
- [ ] Một tỉnh/thành phố.
- [ ] Nhiều tỉnh/thành phố.
- [ ] Khu vực cụ thể: ______________________________________________

## Q16. Quy mô dự kiến trong 6 tháng đầu

| Nội dung | Số lượng dự kiến |
|---|---:|
| Cửa hàng | |
| Tài xế đã đăng ký | |
| Tài xế online cùng lúc | |
| Khách hàng đăng ký | |
| Đơn trung bình/ngày | |
| Đơn cao điểm/giờ | |

## Q17. Hệ thống cần hoạt động trong khung giờ nào?

- [ ] Theo giờ mở cửa chung: từ ________ đến ________.
- [ ] Mỗi cửa hàng có giờ mở cửa riêng.
- [ ] Hoạt động 24/7.
- [ ] Có ngày nghỉ cố định: ______________________________________________

## Q18. Khách được đặt giao trong phạm vi nào?

- [ ] Chỉ trong khu vực phục vụ cố định.
- [ ] Trong khoảng cách tối đa tính từ cửa hàng.
- [ ] Theo danh sách xã/phường được cấu hình.
- [ ] Nhân viên kiểm tra và xác nhận thủ công.
- [ ] Chưa xác định — cần tư vấn.

**Khoảng cách/khu vực dự kiến:** ______________________________________________

## Q19. Cách triển khai mong muốn

- [ ] Thử nghiệm với một số cửa hàng và tài xế trước.
- [ ] Mở toàn bộ khu vực ngay khi ra mắt.
- [ ] Triển khai theo nhiều giai đoạn.
- [ ] Chưa xác định — cần tư vấn.

---

# PHẦN D — TRẢI NGHIỆM KHÁCH HÀNG

## Q20. Khách có bắt buộc đăng ký tài khoản trước khi đặt món?

- [ ] Có.
- [ ] Không, được đặt nhanh bằng số điện thoại.
- [ ] Được xem món không cần tài khoản; đăng nhập khi xác nhận đơn.
- [ ] Chưa xác định — cần tư vấn.

## Q21. Khách đăng nhập bằng cách nào?

- [ ] Số điện thoại và mã xác nhận OTP.
- [ ] Số điện thoại và mật khẩu.
- [ ] Google.
- [ ] Apple.
- [ ] Facebook.
- [ ] Cách khác: ______________________________________________

## Q22. Khách cần quản lý địa chỉ giao hàng như thế nào?

- [ ] Chỉ nhập địa chỉ cho từng đơn.
- [ ] Lưu được nhiều địa chỉ như Nhà, Công ty.
- [ ] Chọn vị trí trên bản đồ và bổ sung mô tả.
- [ ] Dùng vị trí hiện tại của điện thoại.
- [ ] Nhân viên xác nhận lại địa chỉ qua điện thoại.

## Q23. Khách tìm cửa hàng và món ăn theo cách nào?

- [ ] Danh sách cửa hàng gần nhất.
- [ ] Danh mục món ăn.
- [ ] Tìm theo tên cửa hàng.
- [ ] Tìm theo tên món.
- [ ] Lọc theo khoảng cách.
- [ ] Lọc theo trạng thái đang mở cửa.
- [ ] Danh sách cửa hàng nổi bật/được đề xuất.
- [ ] Cách khác: ______________________________________________

## Q24. Khách cần thao tác gì khi chọn món?

- [ ] Chọn số lượng.
- [ ] Chọn kích cỡ/phiên bản món.
- [ ] Chọn topping hoặc món thêm.
- [ ] Ghi chú cho từng món.
- [ ] Xem thành phần hoặc mô tả món.
- [ ] Xem ảnh món.
- [ ] Không cần tùy chọn phức tạp.

## Q25. Thông tin nào cần hiển thị trước khi khách xác nhận đơn?

- [ ] Danh sách món và số lượng.
- [ ] Giá từng món.
- [ ] Phí giao hàng.
- [ ] Tổng tiền cần thanh toán.
- [ ] Địa chỉ giao hàng.
- [ ] Thời gian giao dự kiến.
- [ ] Ghi chú cho cửa hàng.
- [ ] Ghi chú cho tài xế.
- [ ] Điều kiện hủy đơn.

## Q26. Khách có được đặt món trước theo ngày/giờ không?

- [ ] Không, chỉ đặt giao ngay.
- [ ] Có, chọn thời gian mong muốn.
- [ ] Chỉ một số cửa hàng hỗ trợ.
- [ ] Tính năng tương lai.

## Q27. Trong lúc giao, khách cần xem hoặc thực hiện những gì?

- [ ] Xem trạng thái đơn.
- [ ] Xem thời gian giao dự kiến.
- [ ] Xem vị trí tài xế trên bản đồ.
- [ ] Xem tên và số điện thoại tài xế.
- [ ] Gọi tài xế.
- [ ] Gọi cửa hàng.
- [ ] Liên hệ bộ phận hỗ trợ.
- [ ] Hủy đơn nếu vẫn còn được phép.
- [ ] Nội dung khác: ______________________________________________

---

# PHẦN E — CỬA HÀNG VÀ THỰC ĐƠN

## Q28. Một cửa hàng cần bao nhiêu người sử dụng hệ thống?

- [ ] Một tài khoản dùng chung.
- [ ] Nhiều tài khoản nhân viên.
- [ ] Có chủ cửa hàng và nhân viên với quyền khác nhau.
- [ ] Chưa xác định — cần tư vấn.

**Số người dự kiến/cửa hàng:** ______________________________________________

## Q29. Cửa hàng cần quản lý trạng thái hoạt động nào?

- [ ] Mở cửa/Đóng cửa theo lịch.
- [ ] Tạm dừng nhận đơn.
- [ ] Quá tải — kéo dài thời gian chuẩn bị.
- [ ] Nghỉ đột xuất.
- [ ] Không cần, Admin quản lý toàn bộ.

## Q30. Khi có đơn mới, cửa hàng cần làm gì?

- [ ] Nhận thông báo và âm thanh cảnh báo.
- [ ] Xem chi tiết đơn.
- [ ] Chấp nhận đơn.
- [ ] Từ chối và chọn lý do.
- [ ] Nhập thời gian chuẩn bị dự kiến.
- [ ] Liên hệ khách khi cần.
- [ ] In phiếu bếp/in hóa đơn.

## Q31. Nếu cửa hàng không phản hồi đơn trong thời gian quy định thì xử lý thế nào?

- [ ] Nhắc lại cho cửa hàng.
- [ ] Thông báo nhân viên vận hành.
- [ ] Tự động hủy đơn.
- [ ] Nhân viên gọi xác nhận thủ công.
- [ ] Chưa xác định — cần tư vấn.

**Thời gian chờ mong muốn:** ________ phút.

## Q32. Ai chịu trách nhiệm tạo và cập nhật thực đơn?

- [ ] Cửa hàng tự quản lý.
- [ ] Admin quản lý cho cửa hàng.
- [ ] Cửa hàng cập nhật; Admin phê duyệt.
- [ ] Nhập dữ liệu ban đầu bởi đội dự án, sau đó cửa hàng quản lý.
- [ ] Chưa xác định — cần tư vấn.

## Q33. Thực đơn cần hỗ trợ những nội dung nào?

- [ ] Danh mục món.
- [ ] Tên và mô tả món.
- [ ] Ảnh món.
- [ ] Giá bán.
- [ ] Giá khuyến mãi.
- [ ] Kích cỡ/phiên bản món.
- [ ] Topping/món thêm.
- [ ] Món bán theo khung giờ.
- [ ] Món nổi bật.
- [ ] Nội dung khác: ______________________________________________

## Q34. Cửa hàng xử lý món tạm hết như thế nào?

- [ ] Bật/tắt món thủ công.
- [ ] Chọn thời gian món có lại.
- [ ] Báo khách và đề xuất đổi món sau khi đã đặt.
- [ ] Admin cập nhật thay cửa hàng.
- [ ] Không cần quản lý tồn món trong MVP.

## Q35. Cửa hàng có được tự thay đổi giá món?

- [ ] Có, áp dụng ngay.
- [ ] Có, nhưng cần Admin phê duyệt.
- [ ] Không, chỉ Admin được thay đổi.
- [ ] Chưa xác định — cần tư vấn.

## Q36. Cửa hàng cần xem những thông tin nào sau bán hàng?

- [ ] Lịch sử đơn.
- [ ] Số đơn hoàn thành/hủy.
- [ ] Doanh thu theo ngày/tháng.
- [ ] Số tiền cần đối soát.
- [ ] Món bán chạy.
- [ ] Đánh giá/phản hồi của khách.
- [ ] Không cần báo cáo trong MVP.

---

# PHẦN F — ĐƠN HÀNG VÀ CÁC TRƯỜNG HỢP NGOẠI LỆ

## Q37. Vui lòng xác nhận luồng đơn hàng cơ bản

```text
Khách đặt món
→ Cửa hàng chấp nhận
→ Hệ thống/nhân viên tìm tài xế
→ Tài xế nhận đơn
→ Tài xế đến cửa hàng
→ Cửa hàng bàn giao món
→ Tài xế giao cho khách và thu tiền
→ Đơn hoàn thành
```

- [ ] Đồng ý với luồng trên.
- [ ] Cần điều chỉnh như sau: ______________________________________________

## Q38. Cửa hàng có cần cập nhật riêng trạng thái “đang chuẩn bị” và “đã sẵn sàng”?

- [ ] Có cả hai trạng thái.
- [ ] Chỉ cần “đã sẵn sàng”.
- [ ] Không cần; khi chấp nhận được xem là đang chuẩn bị.
- [ ] Chưa xác định — cần tư vấn.

## Q39. Khách được hủy đơn trong trường hợp nào?

- [ ] Trước khi cửa hàng chấp nhận.
- [ ] Sau khi cửa hàng chấp nhận nhưng chưa chuẩn bị.
- [ ] Khi chưa tìm được tài xế sau ________ phút.
- [ ] Chỉ Admin có quyền hủy sau khi cửa hàng chấp nhận.
- [ ] Trường hợp khác: ______________________________________________

## Q40. Cửa hàng được hủy/từ chối đơn trong trường hợp nào?

- [ ] Hết món.
- [ ] Đóng cửa/quá tải.
- [ ] Không giao được đến khu vực của khách.
- [ ] Không liên hệ được khách.
- [ ] Sau khi đã chấp nhận, cửa hàng không được tự hủy.
- [ ] Trường hợp khác: ______________________________________________

## Q41. Nếu một món trong đơn bị hết sau khi khách đã đặt thì xử lý thế nào?

- [ ] Cửa hàng từ chối toàn bộ đơn.
- [ ] Cửa hàng gọi khách để đổi món.
- [ ] Cửa hàng đề xuất món thay thế trên hệ thống.
- [ ] Xóa món hết và điều chỉnh tổng tiền với sự đồng ý của khách.
- [ ] Nhân viên vận hành xử lý thủ công.

## Q42. Nếu không tìm được tài xế thì xử lý thế nào?

- [ ] Tiếp tục tìm trong phạm vi rộng hơn.
- [ ] Chuyển cho nhân viên vận hành chọn thủ công.
- [ ] Thông báo khách chờ thêm.
- [ ] Cho khách hủy đơn.
- [ ] Tự động hủy sau ________ phút.
- [ ] Cách khác: ______________________________________________

## Q43. Nếu khách không nghe máy hoặc không nhận hàng thì xử lý thế nào?

- [ ] Tài xế thử liên hệ ít nhất ________ lần trong ________ phút.
- [ ] Tài xế liên hệ bộ phận hỗ trợ.
- [ ] Tài xế trả món về cửa hàng.
- [ ] Đơn được đánh dấu giao thất bại.
- [ ] Khách chịu một khoản phí theo chính sách.
- [ ] Cách xử lý khác: ______________________________________________

## Q44. Cần bằng chứng nào để xác nhận giao hàng thành công?

- [ ] Tài xế bấm “Đã giao”.
- [ ] Mã xác nhận từ khách.
- [ ] Ảnh giao hàng.
- [ ] Chữ ký người nhận.
- [ ] Vị trí GPS tại điểm giao.
- [ ] Không cần bằng chứng bổ sung trong MVP.

---

# PHẦN G — TÀI XẾ, ĐIỀU PHỐI VÀ THEO DÕI VỊ TRÍ

## Q45. Ai tạo tài khoản tài xế?

- [ ] Tài xế tự đăng ký.
- [ ] Admin tạo tài khoản.
- [ ] Tài xế đăng ký và Admin phê duyệt.
- [ ] Doanh nghiệp nhập danh sách tài xế có sẵn.

## Q46. Tài xế cần cung cấp/xác minh thông tin nào?

- [ ] Họ tên và số điện thoại.
- [ ] Ảnh đại diện.
- [ ] CCCD/giấy tờ tùy thân.
- [ ] Giấy phép lái xe.
- [ ] Thông tin phương tiện và biển số.
- [ ] Tài khoản ngân hàng.
- [ ] Khu vực hoạt động.
- [ ] Không cần xác minh giấy tờ trong MVP.

## Q47. Tài xế cần những trạng thái hoạt động nào?

- [ ] Online — sẵn sàng nhận đơn.
- [ ] Đang xem đề nghị giao hàng.
- [ ] Đang thực hiện đơn.
- [ ] Tạm nghỉ.
- [ ] Offline.
- [ ] Bị tạm khóa bởi Admin.

## Q48. Tiêu chí nào quan trọng khi hệ thống chọn tài xế?

- [ ] Gần cửa hàng nhất.
- [ ] Đang online và không có đơn khác.
- [ ] Hoạt động trong đúng khu vực.
- [ ] Đã chờ lâu nhưng chưa nhận được đơn.
- [ ] Tỷ lệ nhận/hoàn thành đơn tốt.
- [ ] Nhân viên vận hành ưu tiên thủ công.
- [ ] Chỉ cần tiêu chí đơn giản cho MVP: gần nhất và đang rảnh.

## Q49. Đề nghị giao hàng nên được gửi như thế nào?

- [ ] Gửi lần lượt cho từng tài xế; hết thời gian mới chuyển người tiếp theo.
- [ ] Gửi cho một nhóm tài xế gần nhất; người nhận trước được giao đơn.
- [ ] Nhân viên chọn và gửi cho một tài xế cụ thể.
- [ ] Kết hợp tự động và thủ công.
- [ ] Chưa xác định — cần tư vấn.

## Q50. Tài xế có bao lâu để chấp nhận đề nghị giao hàng?

- [ ] 10 giây.
- [ ] 15 giây.
- [ ] 30 giây.
- [ ] Thời gian khác: ________ giây.
- [ ] Chưa xác định — cần tư vấn.

## Q51. Khi tài xế từ chối hoặc không phản hồi thì sao?

- [ ] Tự động tìm tài xế tiếp theo.
- [ ] Hỏi lý do từ chối.
- [ ] Thông báo nhân viên vận hành sau ________ lần thất bại.
- [ ] Chuyển hoàn toàn sang xử lý thủ công.
- [ ] Cách khác: ______________________________________________

## Q52. Tài xế có được hủy sau khi đã nhận đơn?

- [ ] Không.
- [ ] Có, phải chọn lý do.
- [ ] Có, nhưng cần Admin phê duyệt.
- [ ] Chỉ trong trường hợp khẩn cấp.

**Nếu có, hệ thống xử lý đơn tiếp theo như thế nào?**

________________________________________________________________________________

## Q53. Khi tài xế đã nhận nhưng không di chuyển hoặc mất kết nối thì xử lý thế nào?

- [ ] Gửi nhắc nhở cho tài xế.
- [ ] Thông báo nhân viên vận hành.
- [ ] Cho phép Admin đổi tài xế.
- [ ] Tự động đổi tài xế sau ________ phút.
- [ ] Nhân viên gọi xác nhận trước khi đổi.

## Q54. Tài xế và khách cần sử dụng bản đồ như thế nào?

- [ ] Tài xế xem đường đến cửa hàng.
- [ ] Tài xế xem đường đến khách.
- [ ] Mở ứng dụng Google Maps/Apple Maps để dẫn đường.
- [ ] Dẫn đường ngay trong ứng dụng tài xế.
- [ ] Khách xem vị trí tài xế khi đơn đang giao.
- [ ] Cửa hàng xem vị trí tài xế đang đến lấy món.
- [ ] Admin xem vị trí các tài xế đang hoạt động.

---

# PHẦN H — GIÁ GIAO HÀNG, COD VÀ ĐỐI SOÁT

## Q55. Phí giao hàng được tính theo cách nào?

- [ ] Mức phí cố định cho mọi đơn.
- [ ] Theo khoảng cách.
- [ ] Theo khu vực/xã/phường.
- [ ] Theo từng cửa hàng.
- [ ] Admin nhập thủ công.
- [ ] Miễn phí giao hàng trong một số trường hợp.
- [ ] Chưa xác định — cần tư vấn.

**Quy tắc hoặc mức phí dự kiến:** ______________________________________________

## Q56. Phí giao hàng được hiển thị và thu như thế nào?

- [ ] Cộng vào tổng tiền khách trả tài xế.
- [ ] Cửa hàng trả phí giao hàng.
- [ ] Doanh nghiệp hỗ trợ một phần.
- [ ] Chia theo quy tắc khác: ______________________________________________

## Q57. Tài xế sẽ thu những khoản tiền nào từ khách?

- [ ] Tiền món ăn và phí giao hàng.
- [ ] Chỉ tiền món ăn.
- [ ] Chỉ phí giao hàng.
- [ ] Khoản khác: ______________________________________________

## Q58. Tiền COD được đối soát theo quy trình nào?

- [ ] Tài xế ứng trước/nộp tiền món cho cửa hàng khi nhận món, sau đó thu lại từ khách.
- [ ] Tài xế thu tiền và nộp lại doanh nghiệp cuối ngày.
- [ ] Đối soát theo tuần.
- [ ] Tài xế chuyển khoản theo từng đơn.
- [ ] Doanh nghiệp chưa có quy trình — cần tư vấn.
- [ ] Quy trình khác: ______________________________________________

## Q59. Tài xế được trả thu nhập như thế nào?

- [ ] Nhận toàn bộ phí giao hàng.
- [ ] Nhận mức cố định theo đơn.
- [ ] Nhận theo khoảng cách.
- [ ] Nhận lương cố định.
- [ ] Kết hợp lương và phí theo đơn.
- [ ] Cách khác: ______________________________________________

## Q60. Doanh nghiệp thu phí/hoa hồng từ cửa hàng như thế nào?

- [ ] Không thu trong MVP.
- [ ] Mức cố định theo đơn.
- [ ] Phần trăm giá trị đơn.
- [ ] Phí thành viên theo tháng.
- [ ] Kết hợp nhiều loại phí.
- [ ] Chưa xác định — cần tư vấn.

## Q61. Khi đơn bị hủy hoặc giao thất bại, tiền và công nợ được xử lý thế nào?

> **Nếu MVP chỉ dùng COD**, vui lòng mô tả ai chịu chi phí món ăn, phí giao và khoản bồi hoàn nếu có.

**Trả lời:**

________________________________________________________________________________

________________________________________________________________________________

---

# PHẦN I — QUẢN TRỊ, THÔNG BÁO, BÁO CÁO VÀ HỖ TRỢ

## Q62. Những vai trò nào cần sử dụng Web Admin?

- [ ] Chủ doanh nghiệp/Super Admin.
- [ ] Nhân viên điều phối tài xế.
- [ ] Nhân viên chăm sóc khách hàng.
- [ ] Nhân viên quản lý cửa hàng/thực đơn.
- [ ] Kế toán/đối soát.
- [ ] Chỉ cần một loại tài khoản Admin trong MVP.
- [ ] Vai trò khác: ______________________________________________

## Q63. Admin cần quản lý những nội dung nào?

- [ ] Khách hàng.
- [ ] Cửa hàng và tài khoản cửa hàng.
- [ ] Danh mục và món ăn.
- [ ] Tài xế và hồ sơ xác minh.
- [ ] Đơn hàng.
- [ ] Phân công/đổi tài xế.
- [ ] Phí giao hàng.
- [ ] Khu vực hoạt động.
- [ ] Banner/nội dung hiển thị.
- [ ] Thông báo hệ thống.
- [ ] Cấu hình khác: ______________________________________________

## Q64. Admin được phép can thiệp vào đơn hàng như thế nào?

- [ ] Xem toàn bộ lịch sử trạng thái.
- [ ] Chấp nhận/từ chối thay cửa hàng.
- [ ] Chỉ định hoặc đổi tài xế.
- [ ] Hủy đơn và ghi lý do.
- [ ] Điều chỉnh phí giao hàng.
- [ ] Điều chỉnh tổng tiền với lịch sử thay đổi.
- [ ] Đánh dấu giao thành công/thất bại.
- [ ] Liên hệ nhanh với khách, cửa hàng và tài xế.

## Q65. Những thông báo nào là bắt buộc?

| Sự kiện | Khách | Cửa hàng | Tài xế | Admin |
|---|:---:|:---:|:---:|:---:|
| Có đơn mới |  | [ ] |  | [ ] |
| Cửa hàng chấp nhận/từ chối | [ ] |  |  | [ ] |
| Có đề nghị giao hàng |  |  | [ ] |  |
| Tài xế nhận đơn | [ ] | [ ] |  | [ ] |
| Tài xế đến cửa hàng | [ ] | [ ] |  | [ ] |
| Tài xế đã lấy món | [ ] | [ ] |  | [ ] |
| Đang giao | [ ] |  |  | [ ] |
| Giao thành công/thất bại | [ ] | [ ] | [ ] | [ ] |
| Không tìm được tài xế | [ ] | [ ] |  | [ ] |
| Đơn bị hủy | [ ] | [ ] | [ ] | [ ] |

## Q66. Doanh nghiệp cần những báo cáo nào trong MVP?

- [ ] Tổng số đơn theo ngày/tháng.
- [ ] Đơn hoàn thành, hủy và giao thất bại.
- [ ] Doanh thu/giá trị đơn hàng.
- [ ] Phí giao hàng.
- [ ] Doanh số theo cửa hàng.
- [ ] Hiệu suất tài xế.
- [ ] Tiền COD và công nợ.
- [ ] Món bán chạy.
- [ ] Xuất Excel/CSV.
- [ ] Báo cáo khác: ______________________________________________

## Q67. Khi có khiếu nại hoặc tranh chấp, ai xử lý?

- [ ] Cửa hàng xử lý trực tiếp.
- [ ] Bộ phận chăm sóc khách hàng của doanh nghiệp.
- [ ] Nhân viên vận hành/Admin.
- [ ] Chưa có quy trình — cần tư vấn.

**Các loại khiếu nại thường gặp:** ______________________________________________

## Q68. Khách, cửa hàng và tài xế liên hệ hỗ trợ bằng kênh nào?

- [ ] Gọi hotline.
- [ ] Zalo.
- [ ] Email.
- [ ] Biểu mẫu hỗ trợ trong ứng dụng.
- [ ] Chat trực tiếp trong ứng dụng — tính năng tương lai.
- [ ] Kênh khác: ______________________________________________

---

# PHẦN J — THIẾT BỊ, AN TOÀN DỮ LIỆU, TRIỂN KHAI VÀ THƯƠNG MẠI

## Q69. Người dùng sẽ sử dụng hệ thống trên thiết bị nào?

| Nhóm người dùng | Android | iPhone/iPad | Trình duyệt web | Chưa xác định |
|---|:---:|:---:|:---:|:---:|
| Khách hàng | [ ] | [ ] | [ ] | [ ] |
| Cửa hàng | [ ] | [ ] | [ ] | [ ] |
| Tài xế | [ ] | [ ] | [ ] | [ ] |
| Admin | [ ] | [ ] | [ ] | [ ] |

**Thiết bị phổ biến đang sử dụng:** ______________________________________________

## Q70. Yêu cầu về thương hiệu và giao diện

- [ ] Đã có logo và bộ nhận diện thương hiệu.
- [ ] Đã có thiết kế giao diện hoàn chỉnh.
- [ ] Cần đội dự án thiết kế trải nghiệm và giao diện (UI/UX) từ đầu.
- [ ] Có ứng dụng tham khảo mong muốn.
- [ ] Chỉ cần giao diện đơn giản để thử nghiệm MVP.

**Màu sắc/ứng dụng tham khảo:** ______________________________________________

## Q71. Ngôn ngữ cần hỗ trợ

- [ ] Chỉ tiếng Việt.
- [ ] Tiếng Việt và tiếng Anh.
- [ ] Ngôn ngữ khác: ______________________________________________

## Q72. Dữ liệu và quyền riêng tư cần lưu ý điều gì?

- [ ] Chỉ lưu thông tin cần thiết để vận hành đơn.
- [ ] Cần chính sách bảo mật và điều khoản sử dụng.
- [ ] Cần ghi nhận sự đồng ý khi theo dõi vị trí tài xế.
- [ ] Chỉ theo dõi vị trí khi tài xế online/đang giao.
- [ ] Cần quy định thời gian lưu lịch sử vị trí.
- [ ] Cần cho phép người dùng yêu cầu cập nhật/xóa dữ liệu.
- [ ] Chưa có chính sách — cần tư vấn.

**Thời gian muốn lưu dữ liệu đơn hàng:** ______________________________________________

## Q73. Khi xảy ra sự cố hệ thống hoặc mất dữ liệu, mức chấp nhận của doanh nghiệp là gì?

- [ ] Có thể tạm ngưng vài giờ trong giai đoạn MVP.
- [ ] Cần hoạt động liên tục trong giờ kinh doanh.
- [ ] Cần có người nhận cảnh báo khi hệ thống lỗi.
- [ ] Cần sao lưu dữ liệu hằng ngày.
- [ ] Cần khôi phục nhanh trong vòng ________ giờ.
- [ ] Chưa xác định — cần tư vấn.

## Q74. Doanh nghiệp đã có các tài khoản/dịch vụ nào?

- [ ] Apple Developer.
- [ ] Google Play Console.
- [ ] Tên miền.
- [ ] Máy chủ/Cloud.
- [ ] Google Maps hoặc nhà cung cấp bản đồ khác.
- [ ] Dịch vụ SMS OTP.
- [ ] Email theo tên miền.
- [ ] Chưa có; cần hướng dẫn đăng ký.
- [ ] Khác: ______________________________________________

## Q75. Ai là người kiểm tra và xác nhận sản phẩm hoàn thành?

| Hạng mục | Người xác nhận |
|---|---|
| App Khách hàng | |
| App Cửa hàng | |
| App Tài xế | |
| Web Admin | |
| Quy trình vận hành | |
| Báo cáo/đối soát | |
| Nghiệm thu cuối cùng | |

## Q76. Hình thức bàn giao mong muốn

- [ ] Mã nguồn đầy đủ.
- [ ] Tài liệu hướng dẫn sử dụng.
- [ ] Tài liệu cài đặt và vận hành.
- [ ] Tài khoản quản trị và tài khoản dịch vụ.
- [ ] Hướng dẫn/đào tạo cho Admin.
- [ ] Hướng dẫn/đào tạo cho cửa hàng và tài xế.
- [ ] Hỗ trợ đưa ứng dụng lên App Store/Google Play.
- [ ] Nội dung khác: ______________________________________________

## Q77. Thời gian và ngân sách dự kiến

**Thời điểm mong muốn bắt đầu:** ____ / ____ / ________

**Thời điểm mong muốn đưa MVP vào vận hành:** ____ / ____ / ________

**Lý do cần hoàn thành vào thời điểm trên:** ______________________________________________

**Ngân sách dự kiến:**

- [ ] Dưới 150 triệu VNĐ.
- [ ] 150–250 triệu VNĐ.
- [ ] 250–400 triệu VNĐ.
- [ ] Trên 400 triệu VNĐ.
- [ ] Chưa xác định — cần đơn vị phát triển đề xuất theo phạm vi.

## Q78. Nhu cầu bảo hành và hỗ trợ sau triển khai

- [ ] Chỉ cần bảo hành sửa lỗi theo hợp đồng.
- [ ] Cần gói bảo trì hằng tháng.
- [ ] Cần giám sát hệ thống và xử lý sự cố.
- [ ] Cần hỗ trợ cửa hàng/tài xế sử dụng hệ thống.
- [ ] Cần tiếp tục phát triển tính năng mới theo từng giai đoạn.
- [ ] Chưa xác định — cần tư vấn.

---

# PHẦN K — TÍNH NĂNG TƯƠNG LAI VÀ NGOÀI PHẠM VI MVP

Vui lòng đánh dấu định hướng có thể cần trong 1–3 năm tới. Việc đánh dấu tại đây **không mặc nhiên đưa tính năng vào báo giá MVP**.

| Tính năng | Bắt buộc trong MVP | Nên có | Tương lai | Không cần |
|---|:---:|:---:|:---:|:---:|
| Thanh toán trực tuyến | [ ] | [ ] | [ ] | [ ] |
| Voucher/khuyến mãi | [ ] | [ ] | [ ] | [ ] |
| Điểm thưởng/thành viên | [ ] | [ ] | [ ] | [ ] |
| Đánh giá cửa hàng/tài xế | [ ] | [ ] | [ ] | [ ] |
| Chat trong ứng dụng | [ ] | [ ] | [ ] | [ ] |
| Nhiều chi nhánh/cửa hàng | [ ] | [ ] | [ ] | [ ] |
| Một đơn từ nhiều cửa hàng | [ ] | [ ] | [ ] | [ ] |
| Một tài xế giao nhiều đơn | [ ] | [ ] | [ ] | [ ] |
| Đặt món trước theo lịch | [ ] | [ ] | [ ] | [ ] |
| Giao hàng ngoài đồ ăn | [ ] | [ ] | [ ] | [ ] |
| Hóa đơn điện tử | [ ] | [ ] | [ ] | [ ] |
| Tích hợp POS/phần mềm cửa hàng | [ ] | [ ] | [ ] | [ ] |
| Tổng đài/chăm sóc khách hàng | [ ] | [ ] | [ ] | [ ] |
| Mở rộng nhiều tỉnh/thành phố | [ ] | [ ] | [ ] | [ ] |
| Báo cáo phân tích nâng cao | [ ] | [ ] | [ ] | [ ] |

**Tính năng/định hướng khác:**

________________________________________________________________________________

________________________________________________________________________________

---

# PHẦN L — CÂU HỎI MỞ VÀ XÁC NHẬN

## Điều doanh nghiệp lo ngại nhất về dự án

________________________________________________________________________________

________________________________________________________________________________

## Yêu cầu bắt buộc chưa được đề cập trong tài liệu

________________________________________________________________________________

________________________________________________________________________________

## Nội dung cần đơn vị phát triển tư vấn thêm

________________________________________________________________________________

________________________________________________________________________________

## Tài liệu doanh nghiệp có thể cung cấp

- [ ] Logo và bộ nhận diện thương hiệu.
- [ ] Danh sách cửa hàng.
- [ ] Danh sách món và giá.
- [ ] Danh sách tài xế.
- [ ] Quy trình vận hành hiện tại.
- [ ] Chính sách hủy/giao thất bại.
- [ ] Quy định phí giao hàng.
- [ ] Quy trình COD và đối soát.
- [ ] Mẫu báo cáo đang sử dụng.
- [ ] Điều khoản/chính sách hiện có.
- [ ] Tài liệu khác: ______________________________________________

---

# XÁC NHẬN KẾT QUẢ KHẢO SÁT

Sau buổi khảo sát, đơn vị tư vấn/phát triển sẽ tổng hợp các nội dung sau để hai bên xác nhận:

1. Phạm vi MVP.
2. Danh sách tính năng ngoài phạm vi.
3. Luồng trạng thái và quy tắc hủy đơn.
4. Quy trình tìm và phân công tài xế.
5. Quy trình COD và đối soát.
6. Danh sách màn hình của từng ứng dụng.
7. Các giả định và nội dung chưa quyết định.
8. Kế hoạch triển khai, estimate và báo giá.

| Đại diện khách hàng | Đại diện tư vấn/phát triển |
|---|---|
| Họ tên: | Họ tên: |
| Chức vụ: | Chức vụ: |
| Ngày xác nhận: | Ngày xác nhận: |
| Chữ ký: | Chữ ký: |

---

# PHỤ LỤC — NHÁNH CÂU HỎI BỔ SUNG

Các phần dưới đây chỉ thực hiện khi khách hàng chọn tính năng tương ứng.

## A. Nếu cần thanh toán trực tuyến trong MVP

- Nhà cung cấp mong muốn: MoMo / VNPay / ngân hàng / khác.
- Ai đứng tên tài khoản nhận tiền?
- Tiền món, phí giao và hoa hồng được chia như thế nào?
- Có cần hoàn tiền tự động không?
- Ai chịu phí giao dịch?
- Khi thanh toán thành công nhưng tạo đơn thất bại thì xử lý thế nào?
- Có cần lưu hoặc xuất thông tin đối soát giao dịch không?

## B. Nếu một tài xế được giao nhiều đơn

- Số đơn tối đa tài xế được nhận cùng lúc.
- Các đơn có bắt buộc cùng cửa hàng hoặc cùng hướng không?
- Ai quyết định thứ tự lấy và giao hàng?
- Thời gian giao tối đa cho mỗi đơn.
- Cách xử lý khi một đơn trong nhóm bị hủy.

## C. Nếu một cửa hàng có nhiều chi nhánh

- Thực đơn và giá có giống nhau giữa các chi nhánh không?
- Tồn món được quản lý chung hay riêng?
- Khách tự chọn chi nhánh hay hệ thống tự chọn?
- Doanh thu và báo cáo cần tổng hợp theo thương hiệu hay theo chi nhánh?
- Người quản lý có được xem nhiều chi nhánh không?

## D. Nếu cần khuyến mãi/voucher

- Ai tạo chương trình khuyến mãi?
- Khuyến mãi áp dụng cho món, cửa hàng, phí giao hay toàn đơn?
- Có giới hạn số lượt, thời gian và nhóm khách không?
- Cửa hàng hay doanh nghiệp chịu chi phí khuyến mãi?
- Có cho phép dùng nhiều ưu đãi trên một đơn không?

---

## Lịch sử thay đổi

| Phiên bản | Ngày | Nội dung | Người thực hiện |
|---|---|---|---|
| 1.0 | 29/07/2026 | Bản câu hỏi sơ bộ | |
| 2.0 | 29/07/2026 | Viết lại theo ngôn ngữ nghiệp vụ, bổ sung lựa chọn và nhánh điều kiện | |
