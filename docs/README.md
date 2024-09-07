<div align="center">

# Nhật ký thay đổi</div>

<div align="center" style="font-size:xx-small">(✨: Tính năng, chức năng mới. 🐛: Chỉnh lỗi. ☑: Giải quyết công việc, issue. 📗: Nghiệp vụ, thao tác. 📕: Mô tả cơ sở dữ liệu) </div>

#
## 3.24.0907.0 [⬇️OneDrive](https://dh-hos-code.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2F%2FdirectTo%2FHospitalRegisterexe%2F32409070-OneDrive.json) [⬇️GoogleStorage](https://dh-hos-code.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2F%2FdirectTo%2FHospitalRegisterexe%2F32409070-GoogleStorage.json) [⬇️NasDHSolutions](https://dh-hos-code.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2F%2FdirectTo%2FHospitalRegisterexe%2F32409070-NasDHSolutions.json)
- 🐛: Fix lỗi kiểm tra CCCD đăng ký KSK hợp đồng
- ☑: https://github.com/dh-hos/dhg.hospitalregister/issues/59
## [v.3.24.0829.0]()
- 🐛: Fix - Hiệu chỉnh thông tin - bệnh nhân có công khám 2 phòng bị lấy sai phòng, sai thông tin
- 🐛: Fix - Hiệu chỉnh thông tin - bệnh nhân có công khám phòng 1 đã thu tiền (dathu =1) khi chỉnh thông tin (click chuột vào đối tượng nhưng không đổi đối tượng) thì phần mềm tạo thêm công khám phòng 2
- 🐛: Fix - Hiệu chỉnh thông tin - Khi chỉnh bệnh nhân sang đối tượng khác thì phần mềm xóa hết tất cả công khám của các phòng và thêm lại 1 công khám mới theo đối tượng.
- ☑: https://github.com/dh-hos/dhg.hospitalregister/issues/67
## [v.3.24.0827.0]()
- 🐛: **💼**: **_Lỗi - kiểm tra thông tuyến (PK Thiên Phú)_**
- 🐛: Thông báo chi tiết lỗi khi kiểm tra thông tuyến
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/308
## [v.3.24.0826.0]()
- 🐛: Fix Lỗi - Bệnh nhân có chỉ định CLS tự do khi vào phòng khám chỉ định thêm CLS đó thì không ghi nhận thêm được, xóa công khám phòng 2 chỉ định công khám khác thì mất công khám phòng đầu.
* Do thiếu idchidinh dẫn đến khi chỉ định CLS tự do 1 CLS DV (Register ) vào phòng khám bác sĩ khám và chỉ định thêm CLS đó khi lưu lại thì chỉ có 1 CLS đó, không tăng số lượng hay ghi nhận thêm 1 CLS.
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/304
## [v.3.24.0821.0]()
- 🐛: Fix - Hiệu chỉnh thông tin chưa hỗ trợ tự lấy trạng thái chuyển tuyến = 5(Giấy hẹn lãnh thuốc) khi check bệnh nhân khám lao
- 🐛: Fix - Thiếu thông tin Check giấy xác nhận lưu trú và chọn giấy lưu ở tab Thông tin thêm
- ☑: https://github.com/dh-hos/dhg.hospitaladmin/issues/89
- ☑: https://github.com/dh-hos/THEO-DOI-THUC-HIEN/issues/105
![](https://i.imgur.com/HU06FFQ.png)
![](https://i.imgur.com/aVn0Vhd.png)
## [v.3.24.0820.0]()
- 🐛: Fix - Công khám cũ đã thu tiền hiệu chỉnh thông tin vẫn tạo công khám mới
- 🐛: Fix - Khi chỉnh qua đối tượng khác thì có phần mềm có cập nhật lại thông tin công khám thành công khám theo đối tượng nhưng còn thiếu thông tin ICD, Chẩn đoán chính
- ☑: https://github.com/dh-hos/dhg.hospitalregister/issues/67
## [v.3.24.0819.0]()
- ✨: Khi check chọn `[Bệnh nhân khám lao]` thì gán giá trị mặc định `psdangky.trangthaichuyentuyen = 5` (Giấy hẹn lãnh thuốc), đồng thời không bắt buộc phải chọn mã bệnh viện nơi giới thiệu (`psdangky.manoigt`)
- ☑: https://github.com/dh-hos/THEO-DOI-THUC-HIEN/issues/108
![](https://i.imgur.com/dF4Ii1d.png)
## [v.3.24.0816.0]()
- ✨: Hỗ trợ check trạng thái ưu tiên lần khám gần nhất để xác định trạng thái ưu tiên cho bệnh nhân khi bắt số [Ordinal](push lại do thiếu dùng dll củ)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/434
## [v.3.24.0814.2]()
- 🐛: Fix - Hỗ trợ check trạng thái ưu tiên lần khám gần nhất để xác định trạng thái ưu tiên cho bệnh nhân khi bắt số [Ordinal]
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/434
![](https://i.imgur.com/iHsj8ZS.png)
## [v.3.24.0814.1]()
- 🐛:Fix - thiếu trường hợp khi mở chức năng load danh sách BN đăng ký online (92017 - Bệnh viện Da liễu, 92015 - BV TMH Cần Thơ, 92014 - BV Mắt - Răng Hàm Mặt, 92086 - Bệnh viện Ung bướu Cần Thơ, 92016 - BV Lao và Bệnh phổi).
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/601
## [v.3.24.0814.0]()
- ✨: Mở chức năng load danh sách BN đăng ký online (92017 - Bệnh viện Da liễu, 92015 - BV TMH Cần Thơ, 92014 - BV Mắt - Răng Hàm Mặt, 92086 - Bệnh viện Ung bướu Cần Thơ, 92016 - BV Lao và Bệnh phổi).
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/601
![](https://i.imgur.com/1q9NJ0M.png)
## [v.3.24.0812.0]()
- ✨: Hỗ trợ check trạng thái ưu tiên lần khám gần nhất để xác định trạng thái ưu tiên cho bệnh nhân khi bắt số [Ordinal]
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/434
![](https://i.imgur.com/BwpDxKu.png)
<<<<<<< HEAD
## [v.3.24.0812.1]()
- ✨: Hỗ trợ check trạng thái ưu tiên lần khám gần nhất để xác định trạng thái ưu tiên cho bệnh nhân khi bắt số [Ordinal]
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/434
![](https://i.imgur.com/BwpDxKu.png)
## [v.3.24.0812.0]()
- ✨: Hỗ trợ check trạng thái ưu tiên lần khám gần nhất để xác định trạng thái ưu tiên cho bệnh nhân khi bắt số [Ordinal]
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/434
![](https://i.imgur.com/BwpDxKu.png)
=======
## [v.3.24.0811.0]()
- ✨: Yêu cầu - Hỗ trợ hàm kiểm tra thông tuyến theo Công văn 1923/BHXH-CNTT ngày 20/06/2024
- ✨: Mô tả thực hiện [Ham API tra cuu TT - theo CV 1923-BHXHVN.md
](https://github.com/dh-hos/Mo-ta-he-thong/blob/main/XML130/QD4570/Ham%20API%20tra%20cuu%20TT%20-%20theo%20CV%201923-BHXHVN.md)
- ✨:  + Chuyển hàm sử dụng thông tuyến KQNhanLichSuKCB2024 (Không theo cấu hình trên Admin)
- ✨:  + Sử dụng tài khoản kiểm tra theo tài khoản đăng nhập, điều kiện cụ thể để tài khoản có thể sử dụng tra cứu là có tài khoản BHXH cung cấp khác rỗng, có họ lót và Số CCCD
- ✨:  + Trường hợp tài khoản đăng nhập không hợp lệ, sẽ tìm theo tài khoản được cấu hình theo khoa, và theo bệnh viện trên Danh mục Nhân viên
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/565
>>>>>>> 8ec0d04e68faff035cc0e29ffe3887b4cbcf0a87
## [v.3.24.0808.0]()
- 🐛: Fix lỗi - Hiệu chỉnh thông tin thêm lại công khám bị thiếu 1 số thông tin khám bệnh ví dụ như icd phụ, chẩn đoán phụ, icd yhct, tên yhct
- ☑: https://github.com/dh-hos/dhg.hospitalregister/issues/67
## [v.3.24.0805.0]()
- ✨: Thiết kế thêm chức năng chuyển tuyến này trong phần hiệu chỉnh thông tin và có hỗ trợ ràng buộc giống như Register nhận bệnh
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/560
![](https://i.imgur.com/74toDut.png)
## [v.3.24.0731.0]()
- 🐛: Công khám mới không có thông tin khám bệnh
- 🐛: Fix lỗi Bệnh nhân có nhiều công khám tại nhiều phòng khi vào hiệu chỉnh thông tin bấm hiệu chỉnh rồi lưu lại thì phần mềm xóa hết công khám chỉ còn lại 1 công khám theo đối tượng
- ☑: https://github.com/dh-hos/dhg.hospitalregister/issues/67
## [v.3.24.0727.0]()
- 🐛: Fix lỗi - Bấm hiệu chỉnh lưu lại là phần mềm tự thêm công khám mới và không xóa công khám cũ
- ☑: https://github.com/dh-hos/dhg.hospitalregister/issues/67
## [v.3.24.0726.0]()
- ✨: mở chức năng cho nhập ô CMND đối với đối tượng trẻ em trên form nhận bệnh
- ✨: thay đổi ràng buộc ô CMND (bắt thêm 12 ký tự và hộ chiếu 8 ký tự bắt đầu là chữ in hoa và 7 ký tự số ở sau) đối với form đăng ký mã vạch
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/507
## [v.3.24.0723.0]()
- 🐛: Fix lỗi - Báo cáo lượt khám theo phòng: bị double danh sách bệnh nhân
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/273
![](https://i.imgur.com/UTLW0iS.png)
## [v.3.24.0719.3]()
- 🐛:Fix - Form nhận bệnh không tự xóa trống nhóm máu khi nhận bệnh nhân mới và không chọn xóa được.
- 🐛:Fix - Hiệu chỉnh thông tin không xóa trống được nhóm máu nếu đã chọn
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/500
![](https://i.imgur.com/dCID09G.png)
![](https://i.imgur.com/Khqhji0.png)
## [v.3.24.0719.2]()
- 🐛: Fix - Báo cáo lượt khám theo phòng: bị double danh sách bệnh nhân
- 🐛: Fix - Báo cáo lượt khám theo bác sĩ thống kê sai số lượng
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/273
![](https://i.imgur.com/CjVH3C2.png)
![](https://i.imgur.com/E4WCml2.png)
## [v.3.24.0719.1]()
- 🐛: Fix - đăng ký tái khám BANT các thông tin Null lấy dữ liệu theo lần đăng ký trước đó
- ☑: https://github.com/dh-hos/dhg.hospitalregister/issues/73
## [v.3.24.0719.0]()
- 🐛: Thêm cảnh báo - khi nhập chuyển tuyến thiếu số chuyển , điều trị từ.. đến ...
- ☑: https://github.com/dh-hos/dhg.hospitalregister/issues/74
## [v.3.24.0718.0]()
- ✨: Nhận bệnh trên Register bắt nhập thiếu Trạng thái Chuyển tuyến
- ☑: https://github.com/dh-hos/dhg.hospitalregister/issues/74
- 🐛: Fix lỗi sai thông tin chuyển tuyến khi đăng ký tái khám BANT
- ☑: https://github.com/dh-hos/dhg.hospitalregister/issues/73
## [v.3.24.0705.2]()
- ✨: đổi thông báo sang cảnh báo yêu cầu nhập lại địa chỉ đối với bệnh nhân củ có maxa đã lưu trước đó không lấy từ dmxa4750
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/443
![](https://i.imgur.com/6THYnCa.png)
## [v.3.24.0705.1]()
- ✨: cập nhật câu thông báo yêu cầu nhập lại địa chỉ đối với bệnh nhân củ có maxa đã lưu trước đó không lấy từ dmxa4750
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/443
![](https://i.imgur.com/PCffdDg.png);
## [v.3.24.0705.0]()
- ✨: Thêm thông báo yêu cầu nhập lại địa chỉ đối với bệnh nhân củ có maxa đã lưu trước đó không lấy từ dmxa4750
- 🐛: Fix lỗi trường hợp load thông tin bệnh nhân theo mabn không lấy được mã địa phương theo dmxa4750
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/443
![](https://i.imgur.com/wwY9FGf.png)
## [v.3.24.0630.3]()
- 🐛: Fix lỗi mất ngày giờ in phiếu chỉ định cận lâm sàng tự do
- ☑: https://github.com/dh-hos/dhg.hospitalregister/issues/66
## [v.3.24.0630.2]()
- 🐛: Fix lỗi mất ngày giờ in phiếu chỉ định cận lâm sàng tự do
- ☑: https://github.com/dh-hos/dhg.hospitalregister/issues/66
## [v.3.24.0630.1]()
- 🐛: Fix lỗi mất ngày giờ in phiếu chỉ định cận lâm sàng tự do
- ☑: https://github.com/dh-hos/dhg.hospitalregister/issues/66
<<<<<<< HEAD
## [v.3.24.0630.0]()
- 🐛: Fix lỗi mất ngày giờ in phiếu chỉ định cận lâm sàng tự do
- ☑: https://github.com/dh-hos/dhg.hospitalregister/issues/66
=======
## [v.3.24.0628.2]()
- 🐛: Fix lỗi form hiệu chỉnh thông tin lưu sai maxa
- ☑: https://github.com/dh-hos/dhg.hospitalregister/issues/71
## [v.3.24.0628.1]()
- 🐛: Fix lỗi mất mã xã 4750 trên form nhận bệnh
- ☑: https://github.com/dh-hos/dhg.hospitalregister/issues/71
## [v.3.24.0628.0]()
- 🐛: Fix lỗi kiểm tra thông tuyến
- 🐛: Fix lỗi Phường xã đã lấy danh mục 4750 nhưng khi xem lại thông tin nhận bệnh hoặc hiệu chỉnh thông tin mất phường xã
- ☑: https://github.com/dh-hos/dhg.hospitalregister/issues/71
## [v.3.24.0627.0]()
- 🐛: fix lỗi form nhận bệnh và form hiệu chỉnh thông tin chưa lấy được theo dmxa4750
- ☑: https://github.com/dh-hos/dhg.hospitalregister/issues/71
## [v.3.24.0626.0]()
- ✨: Cập nhật kết nối đăng ký khám online - Nhi đồng - 92003
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/414
## [v.3.24.0625.0]()
- 🐛: Fix lỗi Bổ sung tiêu chí xem báo cáo - sổ khám bệnh chỉ lấy theo tháng đăng nhập
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/373
## [v.3.24.0624.0]()
- 🐛: Fix lỗi Sổ khám bệnh, sổ thủ thuật, sổ phẩu thuật - kết quả trả về không bị giới hạn bởi nmakt, thangkt
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/373

## [v.3.24.0623.1]()
- ✨: Bổ sung tính năng theo dõi STT nhận bệnh
- 🐛: Push lại do HosRed.code failed
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/409
![](https://i.imgur.com/h8Uk6eV.png)
## [v.3.24.0623.0]()
- ✨: Bổ sung tính năng theo dõi STT nhận bệnh
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/409
![](https://i.imgur.com/h8Uk6eV.png)
## [v.3.24.0621.5]()
Push lại.
- ✨: Update - bổ sung combobox cho phép chọn, nhập thông tin nhóm máu - form nhận bệnh, form hiệu chỉnh thông tin
- 🐛: combobox nhóm máu chỉ cho phép chọn, không thể nhập
- ☑: https://github.com/dh-hos/Yeu_cau_ho_tro/issues/141
## [v.3.24.0621.4]()
- ✨: Update - bổ sung combobox cho phép chọn, nhập thông tin nhóm máu - form nhận bệnh, form hiệu chỉnh thông tin
- 🐛: combobox nhóm máu chỉ cho phép chọn, không thể nhập
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/397
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
>>>>>>> 2cb4347ba4103ee7807770d0cf79b7f8f74e21ea
## [v.3.24.0621.3]()
- 🐛: Lẫy mẫu mặc định sổ khám bệnh trạm xã
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/361
## [v.3.24.0621.2]()
- ✨: Cảnh báo số lần đăng ký của bệnh nhân trong tháng theo tham số `reg.solankham`  
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/334
<<<<<<< HEAD
## [v.3.24.0621.0]()
- ✨: Cảnh báo số lần đăng ký của bệnh nhân trong tháng theo tham số "reg.solankham"  
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/334

=======
## [v.3.24.0621.1]()
- ✨: bổ sung combobox cho phép chọn, nhập thông tin nhóm máu - form nhận bệnh, form hiệu chỉnh thông tin
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/397
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
![](https://i.imgur.com/dHPZzxI.png)
![](https://i.imgur.com/1PSay8u.png)
## [v.3.24.0621.0]()
- ✨: bổ sung combobox cho phép chọn, nhập thông tin nhóm máu - form nhận bệnh, form hiệu chỉnh thông tin
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/397
![](https://i.imgur.com/dHPZzxI.png)
![](https://i.imgur.com/1PSay8u.png)
>>>>>>> f51c149867def570e5afcea40bf54c5005aa5b2e
## [v.3.24.0620.0]()
- ✨: Push lại - Thay đổi cách ghi nhận maxa trên form nhận bệnh, khám bệnh, hiệu chỉnh thông tin
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/400
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
![](https://i.imgur.com/KGNPU2W.png)
![](https://i.imgur.com/3bky44G.png)
![](https://i.imgur.com/VVaB7q7.png)
## [v.3.24.0619.1]()
- ✨: Số khám bệnh trạm xã cho tự thiết kế
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/361
## [v.3.24.0619.0]()

- 🐛: Fix lỗi trùng hồ sơ chuyển viện ![](https://i.imgur.com/Rw1iliX.png)
- ☑: https://github.com/dh-hos/dhg.hospitalreports/issues/116
## [v.3.24.0617.0]()
- 🐛: Fix lỗi chọn ngày bắt đầu và kết thúc khi chọn combo loại báo cáo
- ☑: https://github.com/dh-hos/dhg.hospitalreports/issues/116
## [v.3.24.0613.0]()
- ✨: Bổ sung tiêu chí thời gian xem báo cáo #373
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/373
- 📕: cho phép chọn thời gian xem báo cáo ngoài tháng/năm kế toán - (sổ khám bệnh, sổ thủ thuật, sổ phẩu thuật)
## [v.3.24.0612.2]()
- 🐛: Không bắt buộc chọn giấy lưu trú ngay cả khi có xác nhận lưu trú
- ☑:  https://github.com/dh-hos/dhg.hospitalregister/issues/65
## [v.3.24.0612.1]()
- 🐛: Bỏ chức năng xét cùng tuyến BV ngoài tỉnh code riêng cho đơn vị: 74206
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/389
## [v.3.24.0612.0]()
- 🐛: Không bắt buộc chọn giấy lưu trú và giấy lưu chuyển tuyến
- ☑:  https://github.com/dh-hos/dhg.hospitalregister/issues/65
## [v.3.24.0610.0]()
- 🐛: fix lỗi Kiểm tra dữ liệu thông tin bệnh nhân kiểm tra ô [CMND], trường hợp không có CMND được lưu lại
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/370
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
## [v.3.24.0607.0]()
- ✨: Thêm kiểm tra trước khi lưu đối với CCCD phải có 9,12 ký tự số hoặc hộ chiếu 8 ký tự bắt đầu là chữ in hoa và 7 ký tự số ở sau
- 📕: Thêm hàm kiểm tra CCCD,hộ chiếu và kiểm tra toàn bộ chuỗi là ký tự số 
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/370
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
![](https://i.imgur.com/q4LLfU0.png)
## [v.3.24.0606.0]()
- 🐛: Fix lỗi mất logo
- ☑: https://github.com/dh-hos/dhg.hospitalregister/issues/68
## [v.3.24.0516.5]()
- 🐛: Fix lỗi mất Logo
- ☑: https://github.com/dh-hos/dhg.hospitalregister/issues/68
