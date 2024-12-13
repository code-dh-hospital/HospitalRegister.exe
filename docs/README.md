<div align="center">

# Nhật ký thay đổi</div>

<div align="center" style="font-size:xx-small">(✨: Tính năng, chức năng mới. 🐛: Chỉnh lỗi. ☑: Giải quyết công việc, issue. 📗: Nghiệp vụ, thao tác. 📕: Mô tả cơ sở dữ liệu) </div>

#

## [v.3.24.1213.4]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32412134-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32412134-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32412134-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - Register gọi bệnh chưa theo mô tả
- 📕: Cập nhật gọi bệnh trên Register giống với mô tả https://github.com/dhhiswork/Mo-ta-he-thong/blob/main/Thong-mo-ta-cau-hinh-cach-doc-goi-benh-tren-speaker.md
- ☑: https://github.com/dhhiswork/Loi/issues/83

## [v.3.24.1213.3]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32412133-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32412133-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32412133-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - phần mềm bắt buộc nhập mã bệnh viện Lao (khi đăng ký bant)
![](https://i.imgur.com/MuclybP.gif)
- ☑: https://github.com/dhhiswork/Loi/issues/81

## [v.3.24.1213.2]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32412132-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32412132-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32412132-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - Hiệu chỉnh thông tin chỉnh đối tượng bệnh nhân không lưu được đối tượng cần chỉnh (BV Ung Bướu)
- ✨: Trường hợp `psdangky.dain = 1` thông báo đến người dùng không thể thay đổi đối tượng
![](https://i.imgur.com/aITaIoD.gif)
- ☑: https://github.com/dhhiswork/Loi/issues/68

## [v.3.24.1213.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32412131-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32412131-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32412131-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - Đăng ký bệnh án ngoại trú thanh toán theo ngày không lấy được bệnh nhân vừa đăng ký
- 📕: Xóa mã phòng khám khi người dùng chọn vào bệnh nhân khác, tránh trường hợp người dùng chọn mã phòng trước, rồi chuyển sang khoa khác dẫn đến khi lưu bệnh nhân có mã phòng không thuộc khoa đó nên Pre không load được bệnh nhân lên
![](https://i.imgur.com/AoKOiZs.gif)
- ☑: https://github.com/dhhiswork/Loi/issues/81

## [v.3.24.1213.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32412130-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32412130-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32412130-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu - REGISTER ĐĂNG KÝ BANT - BỔ SUNG CHỨC NĂNG TAB KHÁM LAO
![](https://i.imgur.com/Fs2xGE1.png)
- ☑: https://github.com/dhhiswork/YeuCau/issues/32

## [v.3.24.1212.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32412120-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32412120-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32412120-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu - ĐĂNG KÝ KCB TAB CHUYỂN TUYẾN - CHẨN ĐOÁN CHO CHỌN NHIỀU ICD
![](https://i.imgur.com/Debo9j3.gif)
- ☑: https://github.com/dhhiswork/YeuCau/issues/21

## [v.3.24.1211.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32412111-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32412111-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32412111-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - Chức năng đăng ký BANT quá chậm
![](https://i.imgur.com/fYeU2qm.gif)
- ☑: https://github.com/dhhiswork/Loi/issues/40

## [v.3.24.1211.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32412110-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32412110-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32412110-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - Chức năng hiệu chỉnh thông tin bệnh nhân trên Admin, Register, Prescription, Printer, hiệu chỉnh thông tin BANT không cập nhật lại trạng thái tuyenxml từ 1 thành 0 khi đổi BV cấp thẻ trong psdangky, bnnoitru -> khi in bảng kê bị sai trang thái tuyến (trái tuyến) đúng là thông tuyến.
![](https://i.imgur.com/PCmnZNx.gif)
- ☑: https://github.com/dhhiswork/YeuCau/issues/14

## [v.3.24.1210.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32412100-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32412100-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32412100-NasDHSolutions.json)</sup></sup></sub>
- ✨: Cập nhật báo cáo nhận diện người bệnh té ngã.

## [v.3.24.1205.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32412050-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32412050-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32412050-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu - Triển khai Kios và phát thuốc hiển thị ra Tivi Bệnh viện Tâm Phúc
- ✨: Mở chức năng gọi bệnh trên Register với `mabvbh = 60152`
- ☑: https://github.com/dhhiswork/YeuCau/issues/34

## [v.3.24.1203.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32412031-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32412031-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32412031-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu - PK Minh Quang: Hỗ trợ trường hợp thẻ BH của quân đội, công an có mã tỉnh đăng ký thẻ và 2 ký tự đầu mã nơi đăng ký ban đầu khác với 2 ký tự đầu mã BV KCB
- ✨: Cập nhật chức năng xuất XML4750.MA_DOITUONG_KCB. theo mô tả [ma_doituong_kcb](https://github.com/dhhiswork/Mo-ta-he-thong/blob/main/XML130/QD4570/ma_doituong_kcb.md)
- ☑: https://github.com/dhhiswork/YeuCau/issues/14

## [v.3.24.1203.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32412030-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32412030-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32412030-NasDHSolutions.json)</sup></sup></sub>
- ✨: Hiệu chỉnh thống kê bệnh nhân có dấu hiệu té ngã.

## [v.3.24.1129.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32411290-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32411290-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32411290-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu - Thêm cách nhập Hộ chiếu mẫu mới gồm 1 chữ cái + 8 số (hiện tại phần mềm chưa cho nhập)
- 🐛: Cho phép nhập thêm dạng hộ chiếu 9 ký tự (1 chữ, 8 số) ![](https://i.imgur.com/FIXDzaJ.png) ![](https://i.imgur.com/PsbqqQY.png)
- ☑: https://github.com/dhhiswork/YeuCau/issues/28

## [v.3.24.1128.10]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F324112810-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F324112810-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F324112810-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - Register khi nhập lại thông tin cũ báo lỗi cấu trúc noicap
- ☑: https://github.com/dhhiswork/Loi/issues/46

## [v.3.24.1128.9]()
- 🐛: Lỗi - Register khi nhập lại thông tin cũ báo lỗi cấu trúc noicap\
![](https://i.imgur.com/iLH6p6z.gif)
- ☑: https://github.com/dhhiswork/Loi/issues/46

## [v.3.24.1128.8]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32411288-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32411288-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32411288-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - Register khi nhập lại thông tin cũ báo lỗi cấu trúc noicap\
- ☑: https://github.com/dhhiswork/Loi/issues/46

## [v.3.24.1128.7]()
- 🐛: Lỗi - Register khi nhập lại thông tin cũ báo lỗi cấu trúc noicap\
![](https://i.imgur.com/iLH6p6z.gif)
- ☑: https://github.com/dhhiswork/Loi/issues/46

## [v.3.24.1128.6]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32411286-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32411286-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32411286-NasDHSolutions.json)</sup></sup></sub>
push test

## [v.3.24.1128.4]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32411284-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32411284-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32411284-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - Register khi nhập lại thông tin cũ báo lỗi cấu trúc noicap\
![](https://i.imgur.com/iLH6p6z.gif)
- ☑: https://github.com/dhhiswork/Loi/issues/46

## [v.3.24.1128.3]()
- 🐛: Lỗi - Register khi nhập lại thông tin cũ báo lỗi cấu trúc noicap\
![](https://i.imgur.com/iLH6p6z.gif)
- ☑: https://github.com/dhhiswork/Loi/issues/46

## [v.3.24.1128.2]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32411282-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32411282-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32411282-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - Register khi nhập lại thông tin cũ báo lỗi cấu trúc noicap
- ☑: https://github.com/dhhiswork/Loi/issues/46

## [v.3.24.1128.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32411281-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32411281-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32411281-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - NƠI CẤP CỦA CMND TRONG FROM HIỆU CHỈNH THÔNG TIN
- 🐛: Chỉnh lỗi khi không chọn ngày cấp vẫn lưu có giá trị ![](https://i.imgur.com/YrrrAV3.png) ![](https://i.imgur.com/MDrZc69.png)
- ☑: https://github.com/dhhiswork/Loi/issues/52

## [v.3.24.1128.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32411280-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32411280-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32411280-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - Register, Prescription không nhập được cân nặng với 4 kí tự
- 🐛: Kiểm tra cân nặng vượt quá 200 thì cảnh báo
![](https://i.imgur.com/lVlx9dp.png)
- ☑: https://github.com/dhhiswork/Loi/issues/35

## [v.3.24.1127.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32411271-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32411271-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32411271-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu - BỔ SUNG NGÀY CẤP - NƠI CẤP CỦA CMND TRONG FROM HIỆU CHỈNH THÔNG TIN 
![](https://i.imgur.com/pR3bRVS.png)
- ☑: https://github.com/dhhiswork/YeuCau/issues/18

## [v.3.24.1127.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32411270-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32411270-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32411270-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - Register khi nhập lại thông tin cũ báo lỗi cấu trúc noicap
![](https://i.imgur.com/2zhr1tw.gif)
- ☑: https://github.com/dhhiswork/Loi/issues/46

## [v.3.24.1125.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32411250-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32411250-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32411250-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu - Register hỗ trợ báo cáo theo nơi công tác

- ☑: https://github.com/dhhiswork/YeuCau/issues/19

- ![](https://i.imgur.com/YcHaL0J.png)
- ![](https://i.imgur.com/nlyYUek.png)

## [v.3.24.1121.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32411211-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32411211-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32411211-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - Test: Register, Prescription: Nhận bệnh bệnh nhân Lãnh thuốc Lao không ghi nhận được ngày cấp giấy chứng nhận Lao 
![](https://i.imgur.com/FRiR0HC.gif)
- ☑: https://github.com/dhhiswork/Loi/issues/20

## [v.3.24.1121.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32411210-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32411210-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32411210-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu - REGISTER VÀ PRECRIPTION BỘ CLS SẮP XẾP MÃ BỘ THEO THỨ TỰ A-Z
![](https://i.imgur.com/khJpSUv.png)
- ☑: https://github.com/dhhiswork/YeuCau/issues/6

## [v.3.24.1120.3]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32411203-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32411203-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32411203-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu - cho phép chọn hoặc nhập tay nơi cấp CCCD
![](https://i.imgur.com/cANcQdt.gif)
- ☑: https://github.com/dhhiswork/YeuCau/issues/9

## [v.3.24.1120.2]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32411202-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32411202-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32411202-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu - form đăng ký load thông tin ngày cấp - nơi cấp CCCD đã đăng ký trước đó khi đăng ký lại bằng mabn
![](https://i.imgur.com/QyKA5SJ.gif)
- ☑: https://github.com/dhhiswork/YeuCau/issues/9

## [v.3.24.1120.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32411201-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32411201-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32411201-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - Chức năng đăng ký ksk hợp đồng load ds từ file excle không đăng ký được các bệnh có mã xã theo danh mục địa phương 4750
![](https://i.imgur.com/QyKA5SJ.gif)
- ☑: https://github.com/dhhiswork/Loi/issues/9

## [v.3.24.1120.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32411200-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32411200-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32411200-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - Chức năng đăng ký ksk hợp đồng load ds từ file excle không đăng ký được các bệnh có mã xã theo danh mục địa phương 4750
![](https://i.imgur.com/Da4aMq4.gif)
- ☑: https://github.com/dhhiswork/Loi/issues/10

## [v.3.24.1119.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32411190-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32411190-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32411190-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - Chức năng đăng ký ksk hợp đồng load ds từ file excle không đăng ký được các bệnh có mã xã theo danh mục địa phương 4750
![](https://i.imgur.com/Da4aMq4.gif)
- ☑: https://github.com/dhhiswork/Loi/issues/10

## [v.3.24.1118.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32411181-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32411181-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32411181-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - psdangky.tuyenxml lưu chưa đúng mô tả.
- Trường hợp `tuyenbv <= 2` ⇒ Người bệnh ngoài tỉnh: Nếu `psdangky.giayxacnhancutru = 1` thì `[psdangky.tuyen = 0 và psdangky.tuyenxml = 0]`, ngược lại `[psdangky.tuyen = 0 và psdangky.tuyenxml = 1]`.
![](https://i.imgur.com/DbX0EBP.png)
- ☑: https://github.com/dh-his/Ghi_Nhan_Loi/issues/37

## [v.3.24.1118.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32411180-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32411180-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32411180-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - psdangky.tuyenxml lưu chưa đúng mô tả.
- Trường hợp `tuyenbv <= 2` ⇒ Người bệnh ngoài tỉnh: Nếu `psdangky.giayxacnhancutru = 1` thì `[psdangky.tuyen = 0 và psdangky.tuyenxml = 0]`, ngược lại `[psdangky.tuyen = 0 và psdangky.tuyenxml = 1]`.
![](https://i.imgur.com/DbX0EBP.png)
- ☑: https://github.com/dh-his/Ghi_Nhan_Loi/issues/37
<<<<<<< HEAD

## [v.3.24.1118.0]()
- 🐛: Lỗi - psdangky.tuyenxml lưu chưa đúng mô tả.
- Trường hợp `tuyenbv <= 2` ⇒ Người bệnh ngoài tỉnh: Nếu `psdangky.giayxacnhancutru = 1` thì `[psdangky.tuyen = 0 và psdangky.tuyenxml = 0]`, ngược lại `[psdangky.tuyen = 0 và psdangky.tuyenxml = 1]`.
![](https://i.imgur.com/DbX0EBP.png)
- ☑: https://github.com/dh-his/Ghi_Nhan_Loi/issues/37
=======

## [v.3.24.1115.2]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32411152-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32411152-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32411152-NasDHSolutions.json)</sup></sup></sub>
- ✨: Cập nhật chức năng theo dõi bệnh nhân té ngã.

## [v.3.24.1115.1]()
- ✨: Cập nhật chức năng theo dõi bệnh nhân té ngã.

## [v.3.24.1115.0]()
- ✨: Cập nhật chức năng theo dõi bệnh nhân té ngã.

## [v.3.24.1108.0]() <sub><sup><sup>[⬇️OneDrive](https://tolaptrinh.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32411080-OneDrive.json) [⬇️GoogleStorage](https://tolaptrinh.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32411080-GoogleStorage.json) [⬇️NasDHSolutions](https://tolaptrinh.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32411080-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Fix - Lỗi khi nhận bệnh, ấn nút đăng ký thì checkbox `Điều trị OPC` không tự động uncheck
![](https://i.imgur.com/RqU7PVS.gif)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/662

## [v.3.24.1106.0]() <sub><sup><sup>[⬇️OneDrive](https://tolaptrinh.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32411060-OneDrive.json) [⬇️GoogleStorage](https://tolaptrinh.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32411060-GoogleStorage.json) [⬇️NasDHSolutions](https://tolaptrinh.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32411060-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - Form KSK không mở được
![](https://i.imgur.com/ROs0pi2.gif)
- ☑: https://github.com/dh-his/Ghi_Nhan_Loi/issues/36
<<<<<<< HEAD

## [v.3.24.1106.0]()
- 🐛: Lỗi - Form KSK không mở được
![](https://i.imgur.com/ROs0pi2.gif)
- ☑: https://github.com/dh-his/Ghi_Nhan_Loi/issues/36
=======

## [v.3.24.1105.2]() <sub><sup><sup>[⬇️OneDrive](https://tolaptrinh.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32411052-OneDrive.json) [⬇️GoogleStorage](https://tolaptrinh.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32411052-GoogleStorage.json) [⬇️NasDHSolutions](https://tolaptrinh.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32411052-NasDHSolutions.json)</sup></sup></sub>
- ✨: Hiệu chỉnh báo cáo nhận diện người bệnh có nguy cơ té ngã

## [v.3.24.1105.1]() <sub><sup><sup>[⬇️OneDrive](https://tolaptrinh.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32411051-OneDrive.json) [⬇️GoogleStorage](https://tolaptrinh.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32411051-GoogleStorage.json) [⬇️NasDHSolutions](https://tolaptrinh.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32411051-NasDHSolutions.json)</sup></sup></sub>
- ✨: Hiệu chỉnh báo cáo nhận diện người bệnh có nguy cơ té ngã

## [v.3.24.1105.0]() <sub><sup><sup>[⬇️OneDrive](https://tolaptrinh.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32411050-OneDrive.json) [⬇️GoogleStorage](https://tolaptrinh.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32411050-GoogleStorage.json) [⬇️NasDHSolutions](https://tolaptrinh.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32411050-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Fix lỗi khi đăng ký không nhập ngày chứng nhận lao nhưng vào hiệu chỉnh thông tin lại thấy có ghi nhận
![](https://i.imgur.com/DYTNtEC.gif)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/699

## [v.3.24.1104.0]() <sub><sup><sup>[⬇️OneDrive](https://tolaptrinh.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32411040-OneDrive.json) [⬇️GoogleStorage](https://tolaptrinh.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32411040-GoogleStorage.json) [⬇️NasDHSolutions](https://tolaptrinh.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32411040-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu - ĐIỀU CHỈNH LẠI THAO TÁC XÁC ĐỊNH CÙNG TUYẾN/TRÁI TUYẾN KHI TIẾP NHẬN/CHỈNH THÔNG TIN
- 🐛: Trường hợp `psdangky.manoigt` khác rỗng và `psdangky.trangthaichuyentuyen IN (2,3,4,5) => `psdangky.tuyen = 0` thì không hiện message xác nhận có giấy chuyển tuyến
- ☑: https://github.com/dh-his/Phieu_Yeu_Cau/issues/12

## [v.3.24.1101.0]() <sub><sup><sup>[⬇️OneDrive](https://tolaptrinh.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32411010-OneDrive.json) [⬇️GoogleStorage](https://tolaptrinh.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32411010-GoogleStorage.json) [⬇️NasDHSolutions](https://tolaptrinh.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32411010-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Hiệu chỉnh thông tin hiển thị sai nội dung tab khám lao
![](https://i.imgur.com/8LQCrii.png)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/699

## [v.3.24.1031.1]() <sub><sup><sup>[⬇️OneDrive](https://tolaptrinh.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32410311-OneDrive.json) [⬇️GoogleStorage](https://tolaptrinh.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32410311-GoogleStorage.json) [⬇️NasDHSolutions](https://tolaptrinh.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32410311-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - Xem kết quả xét nghiệm hiển thị nhiều lần (BV Phụ Sản)
![](https://i.imgur.com/ZCWftIM.png)
- ☑: https://github.com/dh-his/Ghi_Nhan_Loi/issues/20

## [v.3.24.1031.0]() <sub><sup><sup>[⬇️OneDrive](https://tolaptrinh.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32410310-OneDrive.json) [⬇️GoogleStorage](https://tolaptrinh.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32410310-GoogleStorage.json) [⬇️NasDHSolutions](https://tolaptrinh.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32410310-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu - Điều chỉnh lại thao tác xác định cùng tuyến/trái tuyến khi tiếp nhận/chỉnh thông tin
![](https://i.imgur.com/g2CYlyF.png)
![](https://i.imgur.com/35OxSY5.gif)
- ☑: https://github.com/dh-his/Phieu_Yeu_Cau/issues/12

## [v.3.24.1030.4]() <sub><sup><sup>[⬇️OneDrive](https://tolaptrinh.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32410304-OneDrive.json) [⬇️GoogleStorage](https://tolaptrinh.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32410304-GoogleStorage.json) [⬇️NasDHSolutions](https://tolaptrinh.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32410304-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - Có nhập Ngày chứng nhận nhưng psdangky.ngaychungnhan_lao = Null
![](https://i.imgur.com/pVWacvi.png)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/699

## [v.3.24.1030.3]() <sub><sup><sup>[⬇️OneDrive](https://tolaptrinh.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32410303-OneDrive.json) [⬇️GoogleStorage](https://tolaptrinh.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32410303-GoogleStorage.json) [⬇️NasDHSolutions](https://tolaptrinh.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32410303-NasDHSolutions.json)</sup></sup></sub>
Push test 1

## [v.3.24.1030.2]() <sub><sup><sup>[⬇️OneDrive](https://tolaptrinh.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32410302-OneDrive.json) [⬇️GoogleStorage](https://tolaptrinh.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32410302-GoogleStorage.json) [⬇️NasDHSolutions](https://tolaptrinh.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32410302-NasDHSolutions.json)</sup></sup></sub>
- ✨: Cập nhật hỗ trợ ghi nhận bệnh nhân có dấu hiệu té ngã (test)

## [v.3.24.1030.1]() <sub><sup><sup>[⬇️OneDrive](https://tolaptrinh.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32410301-OneDrive.json) [⬇️GoogleStorage](https://tolaptrinh.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32410301-GoogleStorage.json) [⬇️NasDHSolutions](https://tolaptrinh.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32410301-NasDHSolutions.json)</sup></sup></sub>
- ✨: Cập nhật hỗ trợ ghi nhận bệnh nhân có dấu hiệu té ngã

## [v.3.24.1030.0]()
- ✨: Cập nhật hỗ trợ ghi nhận bệnh nhân có dấu hiệu té ngã

## [v.3.24.1029.0]() <sub><sup><sup>[⬇️OneDrive](https://tolaptrinh.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32410290-OneDrive.json) [⬇️GoogleStorage](https://tolaptrinh.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32410290-GoogleStorage.json) [⬇️NasDHSolutions](https://tolaptrinh.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32410290-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - Ràng buộc dữ liệu khi nhập cân nặng.
![](https://i.imgur.com/xHzAmAE.png)
- ☑: https://github.com/dh-his/Ghi_Nhan_Loi/issues/12

## [v.3.24.1028.5]() <sub><sup><sup>[⬇️OneDrive](https://tolaptrinh.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32410285-OneDrive.json) [⬇️GoogleStorage](https://tolaptrinh.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32410285-GoogleStorage.json) [⬇️NasDHSolutions](https://tolaptrinh.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32410285-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Fix lỗi đọc CCCD - Websocket

## [v.3.24.1028.4]() <sub><sup><sup>[⬇️OneDrive](https://tolaptrinh.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32410284-OneDrive.json) [⬇️GoogleStorage](https://tolaptrinh.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32410284-GoogleStorage.json) [⬇️NasDHSolutions](https://tolaptrinh.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32410284-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Fix lỗi đọc CCCD - Websocket

## [v.3.24.1028.3]() <sub><sup><sup>[⬇️OneDrive](https://tolaptrinh.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32410283-OneDrive.json) [⬇️GoogleStorage](https://tolaptrinh.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32410283-GoogleStorage.json) [⬇️NasDHSolutions](https://tolaptrinh.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalRegisterexe%2F32410283-NasDHSolutions.json)</sup></sup></sub>
- ✨: Push test 2
- ☑: https://github.com/dh-his/Ghi_Nhan_Loi/issues/14

## [v.3.24.1028.2]()
- ✨: Push test
- ☑: https://github.com/dh-his/Ghi_Nhan_Loi/issues/14

## [v.3.24.1028.1]()
- ✨: Push test

## [v.3.24.1028.0]()
- ✨: - ✨:Cập nhật chức năng đọc CCCD bằng Websocket

## [v.3.24.1022.2]()
- ✨: Cập nhật theo -Sửa đổi Mô tả XML130 - Bổ sung QĐ 4750.md - Trường hợp Đối với psdangky.trangthaichuyentuyen = 5 hoặc 6.
- ✨: Điều chỉnh checkbox `[Bệnh nhân khám lao]` thành radiobutton `[Khám lao]`, tương ứng với `psdangky.trangthaichuyentuyen = 4`.
- ✨: Bổ sung radiobutton `[Lãnh thuốc lao]`, tương ứng với `psdangky.trangthaichuyentuyen = 6`.
![](https://i.imgur.com/39o0KOs.png)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/699

## [v.3.24.1022.1]()
- ✨: Yêu cầu - ĐIỀU CHỈNH LẠI CÁCH RÀNG BUỘC BỆNH NHÂN CHỈ CÓ PHIẾU THU TẠM ỨNG KHÔNG CHO CHỈNH ĐỐI TƯỢNG
![](https://i.imgur.com/VBXnkbB.gif)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/712

## [v.3.24.1022.0]()
- ✨: Yêu cầu - ĐIỀU CHỈNH LẠI CÁCH RÀNG BUỘC BỆNH NHÂN CHỈ CÓ PHIẾU THU TẠM ỨNG KHÔNG CHO CHỈNH ĐỐI TƯỢNG
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/712

## [v.3.24.1021.1]()
- 🐛: Lỗi - Register và Prescription: Chức năng nhận bệnh không nhập được nơi cấp CCCD (phần mềm đang bị giới hạn 12 ký tự)
![](https://i.imgur.com/XvKtw9s.png)
- ☑: https://github.com/dh-hos/dhg.hospitalregister/issues/82

## [v.3.24.1021.0]()
- ✨: Khi hiệu chỉnh thông tin, nếu đối tượng là BHYT - kiểm tra chỉ số sinh hiệu theo tham số ktsinhhieu.customize
![](https://i.imgur.com/JY8OrMU.gif)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/700

## [v.3.24.1017.3]()
- 🐛: Fix - Lỗi khi bấm nút đăng ký bệnh nhân
![](https://i.imgur.com/W3Fnljt.gif)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/693

## [v.3.24.1017.2]()
✨: Cập nhât chức năng phân loại bệnh nhân té ngã

## [v.3.24.1017.1]()
- ✨: Cập nhât chức năng phân loại bệnh nhân té ngã
- 📗: https://github.com/dh-hos/Mo-ta-he-thong/blob/main/Bi%20-%20Mo_ta_cap_nhat_Theo_doi_benh_nhan_te_nga.md

## [v.3.24.1017.0]()
- ✨: Cập nhât chức năng phân loại bệnh nhân té ngã
- 📗: https://github.com/dh-hos/Mo-ta-he-thong/blob/main/Bi%20-%20Mo_ta_cap_nhat_Theo_doi_benh_nhan_te_nga.md

## [v.3.24.1016.2]()
- 🐛: Chỉnh lỗi bắt sai trường hợp Hộ chiếu 8 ký tự
![](https://i.imgur.com/O1HaD2r.gif)
![](https://i.imgur.com/C7mw5Qp.gif)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/693

## [v.3.24.1016.1]()
- 🐛: Chỉnh lỗi bắt sai trường hợp Hộ chiếu 8 ký tự
![](https://i.imgur.com/O1HaD2r.gif)
![](https://i.imgur.com/C7mw5Qp.gif)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/663

## [v.3.24.1016.0]()
- ✨: Thực hiện yêu cầu - Tích hợp đầu đọc CCCD
![](https://i.imgur.com/OB27bw0.gif)
https://github.com/dh-hos/Mo-ta-he-thong/blob/main/REGISTER/Tich-hop-cccd-chip/Tich-hop-cccd-jth.md
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/663

## [v.3.24.1015.5]()
- 🐛: Fix lỗi - NGOẠI TRÚ - LƯỢT KHÁM THEO BÁC SĨ THỐNG KÊ THEO GIỜ KHÔNG LOAD SỐ LIỆU.(Build lại do thiếu dll)
- ☑: https://github.com/dh-hos/dhg.hospitalreports/issues/133

## [v.3.24.1015.4]()
- 🐛: fix - Lỗi khi chỉnh thông tin BN mới đăng ký từ danh sách đăng ký
- ☑: https://github.com/dh-hos/dhg.hospitalregister/issues/81

## [v.3.24.1015.3]()
- 🐛: Lỗi - NGOẠI TRÚ - LƯỢT KHÁM THEO BÁC SĨ THỐNG KÊ THEO GIỜ KHÔNG LOAD SỐ LIỆU
![](https://i.imgur.com/t8sD0Yj.png)
- ☑: https://github.com/dh-hos/dhg.hospitalreports/issues/133

## [v.3.24.1015.2]()
- ✨: Thực hiện - Điều chỉnh ghi nhận số hộ chiếu.
![](https://i.imgur.com/TGLVXLQ.png)
![](https://i.imgur.com/PURyujH.png)
![](https://i.imgur.com/a0uFl79.png)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/693

## [v.3.24.1015.1]()
- ✨: Thực hiện - Điều chỉnh ghi nhận số hộ chiếu
![](https://i.imgur.com/TGLVXLQ.png)
![](https://i.imgur.com/PURyujH.png)
![](https://i.imgur.com/a0uFl79.png)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/693

## [v.3.24.1015.0]()
- ✨: Thực hiện - Điều chỉnh ghi nhận số hộ chiếu (BV Phụ Sản)
![](https://i.imgur.com/TGLVXLQ.png)
![](https://i.imgur.com/PURyujH.png)
![](https://i.imgur.com/a0uFl79.png)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/693

## [v.3.24.1014.1]()
- ✨: Cập nhật chức năng phân loại bệnh nhân có nguy cơ té ngã

## [v.3.24.1014.0]()
- ✨: Test Merge

## [v.3.24.1013.0]()
- ✨: Thực hiện Yêu cầu - Prescription hỗ trợ thêm trường ngày cấp và nơi cấp Căn cước công dân
- ✨: Bắt buộc nhập ngày cấp và nơi cấp CMND/CCCD theo mô tả
https://github.com/dh-hos/Mo-ta-he-thong/blob/main/Thong-mo-ta-tham-so-bat-buoc-nhap-thong-tin-cccd.md
![](https://i.imgur.com/ikn5Tj4.png)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/691

## [v.3.24.1010.1]()
- 🐛: Fix - Đối với người bệnh khám lao có giấy chuyển tuyến: psdangky.trangthaichuyentuyen = 4 và psdangky.manoigt <> '' (Chuyển tuyến người bệnh khám và điều trị bệnh lao) thì hỗ trợ check chọn mặc định [Bệnh nhân khám lao] = true tại tab [Khám lao] và psdangky.mabv_dieutri_lao = psdangky.manoigt
- ☑: https://github.com/dh-hos/dhg.hospitalregister/issues/79

## [v.3.24.1010.0]()
- 🐛: Hiệu chỉnh thông tin - Trường hợp bệnh nhân khám lao có giấy hẹn lãnh thuốc : khi chọn psdangky.trangthaichuyentuyen = 6 (giấy hẹn lãnh thuốc người bệnh lao) thì hỗ trợ check chọn mặc định [Bệnh nhân khám lao] = true đồng thời không bắt buộc phải nhập mã bệnh viện nơi giới thiệu
- ☑: https://github.com/dh-hos/dhg.hospitalregister/issues/79

## [v.3.24.1009.0]()
- 🐛: Trường hợp bệnh nhân khám lao có giấy hẹn lãnh thuốc : khi chọn `psdangky.trangthaichuyentuyen = 6` (giấy hẹn lãnh thuốc người bệnh lao) thì hỗ trợ check chọn mặc định `[Bệnh nhân khám lao]` = true đồng thời không bắt buộc phải nhập mã bệnh viện nơi giới thiệu
![](https://i.imgur.com/kPLKX2U.png)
- ☑: https://github.com/dh-hos/dhg.hospitalregister/issues/79`

## [v.3.24.0924.0]()
- 🐛: Khi các Phân khu ngoài Kios chưa phát sinh số thứ tự thì khi người dùng bấm vào nút Next trên Register thì không ghi nhận dữ liệu vào bảng goibenh và monitor.
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/649

## [v.3.24.0923.1]()
- 🐛: Fix - Lỗi BV Tim Mạch CT: Chỉ định CLS tự do Thêm CLS lần 2 báo lỗi khi lưu
![](https://i.imgur.com/HPf1MAG.gif)
- ☑: https://github.com/dh-hos/dhg.hospitalregister/issues/78

## [v.3.24.0923.0]()
- 🐛: Khi các Phân khu ngoài Kios chưa phát sinh số thứ tự thì khi người dùng bấm vào nút Next trên Register thì không ghi nhận dữ liệu vào bảng goibenh và monitor
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/648

## [v.3.24.0921.0]()
- ✨: Mở chức năng gọi bệnh BV Sa Đéc
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/648

## [v.3.24.0920.0]()
- ✨: Mở chức năng gọi bệnh cho BV Thốt Nốt
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/649

## [v.3.24.0919.1]()
- ✨: Mở chức năng gọi bệnh cho BV Sa Đéc
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/648

## [v.3.24.0919.0]()
- 🐛: Fix - lỗi phát sinh khi load danh sách đã đăng ký khám bệnh
- ☑: https://github.com/dh-hos/dhg.hospitalregister/issues/77

## [v.3.24.0916.0]()
- ✨: Thực hiện thay đổi theo mô tả nhập bệnh nhân lao, bệnh nhân lĩnh thuốc
- ✨: Đối với `psdangky.trangthaichuyentuyen = 5 hoặc 6`, khi đăng ký khám bệnh chỉ ràng buộc mã nơi giới thiệu
![](https://i.imgur.com/XpJA6V8.png)
- ✨: Đối với người bệnh khám lao có giấy chuyển tuyến: `psdangky.trangthaichuyentuyen = 4` và `psdangky.manoigt <> ''` thì hỗ trợ check chọn mặc định `Bệnh nhân khám lao = true` tại tab `khám lao`
![](https://i.imgur.com/tGjtjWT.gif)
- ☑: https://github.com/dh-hos/THEO-DOI-THUC-HIEN/issues/129

## [v.3.24.0913.0]()
- 🐛: Sửa lỗi: Form cập nhật thông tin chỉ định giải phẫu bệnh sinh thiết đã lập, khi đóng form mở lại bị thiếu chẩn đoán.
- ![](https://i.imgur.com/Zj0ODxE.png)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/629

## [v.3.24.0909.0]()
- 🐛: **💼**: **_Lỗi - kiểm tra thông tuyến (PK Thiên Phú)_**
- 🐛: ![](https://i.imgur.com/IvMhgmA.gif)
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/308

## [v.3.24.0908.0]()

- 🐛: Fix lỗi sai giới tính khi chỉnh thông tin bệnh nhân
- ☑: https://github.com/dh-hos/dhg.hospitalregister/issues/64

## [v.3.24.0907.0]()
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

## [v.3.24.0812.1]()
- ✨: Hỗ trợ check trạng thái ưu tiên lần khám gần nhất để xác định trạng thái ưu tiên cho bệnh nhân khi bắt số [Ordinal]
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/434
![](https://i.imgur.com/BwpDxKu.png)

## [v.3.24.0812.0]()
- ✨: Hỗ trợ check trạng thái ưu tiên lần khám gần nhất để xác định trạng thái ưu tiên cho bệnh nhân khi bắt số [Ordinal]
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/434
![](https://i.imgur.com/BwpDxKu.png)
<<<<<<< HEAD

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

## [v.3.24.0621.1]()
- ✨: bổ sung combobox cho phép chọn, nhập thông tin nhóm máu - form nhận bệnh, form hiệu chỉnh thông tin
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/397
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
![](https://i.imgur.com/dHPZzxI.png)
![](https://i.imgur.com/1PSay8u.png)

## [v.3.24.0621.0]()
- ✨: Cảnh báo số lần đăng ký của bệnh nhân trong tháng theo tham số "reg.solankham"  
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/334

=======

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