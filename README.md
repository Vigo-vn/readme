# Vigo - Nền tảng du lịch thuần Việt

## Giới Thiệu
* Trong thời đại du lịch bền vững, du lịch trải nghiệm (Experiential Tourism) đang trở thành một xu hướng nổi bật.
    - Du lịch trải nghiệm bao gồm bất cứ loại hình du lịch nào có yếu tố “trải nghiệm”: du lịch di sản, du lịch văn hoá, du lịch cộng đồng, du lịch sinh thái,…
    - Trong loại hình du lịch này, chính những người bản xứ là những người am hiểu rõ và tường tận nhất những văn hóa, bản sắc tại địa phương mình.
* Vigo là một nền tảng du lịch thuần Việt, nhằm mục tiêu mang đến cho du khách những trải nghiệm độc đáo và sâu sắc về văn hóa, phong tục và con người Việt Nam. Thông qua Vigo, người dùng có thể dễ dàng tìm kiếm, lên kế hoạch và đặt dịch vụ du lịch phù hợp với nhu cầu cá nhân, đồng thời khám phá sâu sắc hơn về đất nước và con người Việt Nam.
- Vigo tập trung vào vai trò của người bản xứ trong việc giới thiệu cuộc sống và văn hóa địa phương, kết nối họ với du khách yêu thích du lịch bền vững. Mục tiêu:
	- Giúp người dân thu hút khách du lịch.
	- Cung cấp cho du khách chuyến đi khám phá Việt Nam đáng nhớ.
## Tính Năng Chính
- **Trải nghiệm theo chủ đề**: Du khách có thể chọn các gói du lịch theo chủ đề như "Trải nghiệm ẩm thực", "Sống cùng dân địa phương", hoặc "Khám phá văn hóa làng nghề".
- **Lên lịch trình cá nhân hóa**: Hỗ trợ người dùng tự tạo lịch trình du lịch riêng, phù hợp với sở thích, thời gian, và ngân sách cá nhân.
- **Hướng dẫn viên bản địa**: Cung cấp dịch vụ hướng dẫn viên bản địa để du khách có thể tiếp cận thông tin từ người dân địa phương.
- **Hoạt động tương tác cộng đồng**: Kết nối du khách với cộng đồng địa phương thông qua các hoạt động như tham gia lễ hội, làm đồ thủ công, và giao lưu văn hóa.
## Tổng Quan Hệ Thống
### Người dùng
1. Quản trị viên hệ thống
2. Khách du lịch
3. Hướng dẫn viên địa phương: là người dân bản địa.
4. Quản trị viên địa phương: là người phụ trách quản lý tài khoản và thông tin của hướng dẫn viên.
### Chức năng
1. **Dành cho quản trị viên hệ thống**:
   * Quản lý thông tin địa danh và thông tin các quản trị viên địa phương.

2. **Dành cho khách du lịch**:
   * Tìm kiếm, xem thông tin: các địa danh, các hướng dẫn viên bản địa.
   * Đặt vé với hướng dẫn viên: dựa trên lịch có sẵn.
	   * Yêu cầu thanh toán trong vòng 2h kể từ khi đặt vé.
   * Thanh toán.
   * Lưu album kỷ niệm.
	   * Lưu dấu những nơi từng đặt chân trên bản đồ VN.
	   * Có thể tùy chọn chia sẻ dạng bài đăng công khai.
   * Viết đánh giá (chỉ dành cho người từng đặt vé qua app)
   * Tương tác với bài đăng.

3. **Dành cho quản trị viên địa phương**:
	* Quản lý tài khoản, thông tin của các hướng dẫn viên.
	* Tương tác với bài đăng.

4. **Dành cho hướng dẫn viên bản địa**:
     * Quản lý lịch hoạt động cá nhân.
     * Khai báo thông tin vé: số người tối thiểu - tối đa, giá vé, số giờ, dịch vụ và trải nghiệm cung cấp.
     * Đăng tải video ngắn (có thể nhúng video từ TikTok, Youtube Shorts)
     * Theo dõi đánh giá từ người dùng.
### Công nghệ sử dụng (dự kiến)
* Web application (React): dành cho các chức năng quản lý
* Mobile (...): dành cho người dùng
* Backend (...)
