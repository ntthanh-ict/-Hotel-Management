# -Hotel-Management
Bài tập tuần 07 lớp SE04
1. Goals:

-Phần mềm dạng ứng dụng cho máy tính cá nhân, chỉ có nhân viên lễ tân, nhân viên bán hàng, quản lí khách sạn được sử dụng

-Nhân viên lễ tân có thể tìm phòng trống theo yêu cầu trực tiếp của khách, checkin cho khách đã đặt phòng hoặc đặt phòng trực tiếp, checkout cho khách và in hóa đơn thanh toán cho khách

-Nhân viên bán hàng có thể tìm phòng trống và đặt phòng theo yêu cầu của khách

-Quản lí có thể: thêm/sửa/xóa thông tin phòng, xem các báo cáo doanh thu theo thời gian/theo phòng/theo loại phòng, xem báo cáo tỉ lệ phòng trống theo thời gian/theo phòng/theo loại phòng, xem báo cáo khách hàng đặt nhiều theo thời gian/theo nguồn gốc khách hàng.

-Trong khách sạn có nhiều phòng, mỗi phòng được mô tả bằng các thông tin: tên phòng (duy nhất, để phân biệt các phòng), loại phòng, giá niêm yết, các loại dịch vụ đi kèm, mô tả phòng.

-Mỗi khách hàng, khi đến ở hoặc đặt phòng, sẽ được lưu các thông tin bao gồm số CMND (số passport nếu là người nước ngoài), loại giấy tùy thân (CMND, passport), họ tên đầy đủ, địa chỉ, số điện thoại


-Khách hàng chỉ có thể đặt phòng nếu phòng đó còn trống trong suốt thời gian khách hàng muốn đặt.

-Khách hàng có thể thanh toán nhiều lần cho đến ngày trả phòng.

-Mỗi lần thanh toán, lễ tân sẽ in hóa đơn cho lần thanh toán đó bao gồm các thông tin: họ tên và địa chỉ khách hàng, số phòng, ngày đến, ngày đi, giá phòng, các dịch vụ đi kèm (mỗi dịch vụ bao gồm tên dịch vụ, đơn vị tính, đơn giá, tổng tiền), số tiền thanh toán.


2. Business Objectives:

-Thông tin khách hàng và dữ liệu được lưu trữ khoa học và bảo mật.

-Tăng hiệu suất làm việc vủa nhân viên

-Giảm thời gian của khách hàng khi đặt phòng

-Máy chủ có thể lưu trữ và hoạt động tốt sau thời gian dài hoạt động và phải lưu trữ rất nhiều dữ liệu.
