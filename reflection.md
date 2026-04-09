# Individual reflection — Nguyễn Văn A (AI20K001)

## 1. Role
Thiết kế flow chatbot agent, viết và chỉnh sửa tool

## 2. Đóng góp cụ thể
- Thiết kế luồng agent + kết nối các tool.
- Tạo tool interaction_checker: kiểm tra tương thích của thuốc thay thế đối với đơn thuốc.

## 3. SPEC mạnh/yếu
- Mạnh nhất: Tìm thuốc thay thế có hoạt tính tương tự và kiểm tra tính an toàn khi kết hợp trong đơn thuốc.
- Yếu nhất: Phụ thuộc vào API và Model chưa được tối ưu chuyên biệt cho lĩnh vực tư vấn thuốc.

## 4. Đóng góp khác
- Test prompt với agent để kiểm tra tool xem đã hoạt động chưa. 
- Refactor code để làm base cho việc tạo agent.

## 5. Điều học được
- Cần xác định đúng mục đích trước khi làm vì mục đích mới là vấn đề lớn nhất.
- Học được các cách xử lí github chuyên nghiệp hơn.

## 6. Nếu làm lại
- Sẽ xác định vấn đề sớm hơn và chuẩn bị kiến thức thật sớm.
- Kết nối Backend với Frontend sớm hơn.

## 7. AI giúp gì / AI sai gì
- **Giúp:** Gemini AI để tạo tìm kiếm api và tạo tool, đồng thời cũng giúp reffactor lại code
- **Sai/mislead:** Gemini AI refactor code còn bị nhiều lỗi, vẫn cần con người tìm bug và fix lại, đề xuất một vài api bị lỗi thời vào năm 2025 phải lên google tra api khác.