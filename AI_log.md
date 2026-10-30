# AI LOG – BUỔI 7, TIẾT 3

> Điền vào `[ ... ]`, tích `[x]` vào lựa chọn phù hợp. Ghi đúng việc đã làm; chưa kiểm tra thì ghi “Chưa kiểm tra”. Không cần chép toàn bộ cuộc trò chuyện AI.

## Thông tin sinh viên

- Họ và tên: [ Tống Xuân Thành ]
- Mã sinh viên – Lớp: [ 2071020169 CNTT20-02 ]
- Ngày thực hiện: [ 30/10/2026 ]
- Link repository: [ https://github.com/Thanhtong-255/K20_Portfolio_CNTT20_02.git ]
- URL website: [ https://thanhtong-255.github.io/K20_Portfolio_CNTT20_02/ ]
- Tình huống: [CSS ] Website của tôi  [ ] Repo luyện của giảng viên

## 1. Nhận định của tôi trước khi hỏi AI

- Trang/thao tác gặp lỗi: [ trang chính ]
- Mong muốn và hiện tượng thực tế: [ Mong muốn trang chính hiển thị đầy đủ nội dung, hình ảnh và các chức năng bình thường. Tuy nhiên, khi truy cập, một số hình ảnh không hiển thị  ]
- Dữ kiện đã kiểm tra (cấu trúc tệp, Request URL, Status…): [  Đã kiểm tra thư mục chứa hình ảnh, đường dẫn tài nguyên và tab Network trong Developer Tools. Phát hiện một số yêu cầu tải hình ảnh trả về lỗi 404 (Not Found). ]
- Tôi nghi nguyên nhân là: [ Đường dẫn đến các tệp hình ảnh chưa chính xác hoặc tên tệp không khớp. ]
- Vì sao tôi nhận định như vậy: [ Vì trình duyệt không tìm thấy tài nguyên tại đường dẫn được yêu cầu, mặc dù các tệp hình ảnh vẫn tồn tại trong thư mục dự án. ]

## 2. Tôi hỏi AI và nhận được gợi ý

- Nguồn: [ ] Công cụ AI: [ ChatGPT. ]  [ ] Phản hồi mẫu của giảng viên
- Câu hỏi/prompt tôi đã gửi (hoặc tình huống của phản hồi mẫu):

  [ Tại sao hình ảnh trên trang chính không hiển thị dù tôi đã thêm hình ảnh vào dự án? Hãy hướng dẫn cách kiểm tra và khắc phục lỗi. ]

- Gợi ý chính của AI:

  [ Kiểm tra lại đường dẫn đến hình ảnh.

Kiểm tra tên tệp và phần mở rộng của hình ảnh.

Kiểm tra vị trí lưu trữ hình ảnh trong dự án.

Sử dụng đường dẫn tương đối hoặc đường dẫn phù hợp với cấu trúc dự án.

Kiểm tra lại kết quả trong tab Network của trình duyệt.

3. Quyết định của tôi ]

## 3. Quyết định của tôi

- [ ] Chấp nhận gợi ý
- [ ] Chỉnh sửa gợi ý rồi áp dụng
- [ ] Bác bỏ gợi ý

- Tôi quyết định làm gì: [ Kiểm tra lại cấu trúc thư mục và chỉnh sửa đường dẫn hình ảnh trong mã nguồn để trỏ đúng đến vị trí lưu trữ. ]
- Lý do, dựa trên dữ kiện nào: [Dựa vào lỗi 404 trong Network và kết quả kiểm tra đường dẫn tài nguyên, tôi xác định nguyên nhân có khả năng nằm ở đường dẫn hình ảnh. ]

## 4. Thực hiện và kiểm chứng

- Tệp/vị trí đã sửa (không sửa thì ghi rõ): [ Tệp giao diện trang chính (Home) chứa các đường dẫn hình ảnh (tệp html) ]
- Nội dung thay đổi hoặc cách xử lý khác: [ Chỉnh sửa đường dẫn hình ảnh cho đúng với cấu trúc thư mục dự án. ]
- Commit của bản sửa, nếu có: [ file index.html ]
- Bản sửa đã deploy: [ ] Có  

| Nội dung kiểm tra | Trước xử lý | Sau xử lý/thử lại |
| --- | --- | --- |
| Request URL và Status của tài nguyên liên quan | [ Một số hình ảnh trả về lỗi 404 ] | [ Hình ảnh tải thành công, Status 200 ] |
| Giao diện/chức năng trên URL website | [ Một số hình ảnh không hiển thị ] | [Hình ảnh hiển thị bình thường  ] |

- Cách thử lại và kết quả thực tế: [  Lưu lại mã nguồn, tải lại trang chính bằng Ctrl + F5 và kiểm tra tab Network. Kết quả: Hình ảnh đã hiển thị bình thường, không còn lỗi 404. ]
- Căn cứ để đối chiếu (URL tệp, commit, đường dẫn ảnh chụp hoặc dữ kiện quan sát): [  Kết quả kiểm tra trong tab Network của trình duyệt và giao diện trang chính sau khi chỉnh sửa. ]

## 5. Kết luận

- [ ] Đã xử lý được  
- Điều tôi rút ra hoặc việc cần làm tiếp: []

---

*Tệp là minh chứng MC2 để nhận định mức đạt của tiết học; không tính điểm MC2 riêng. Nếu có tình huống khác, sao chép mục 1–5 để ghi thêm.*
