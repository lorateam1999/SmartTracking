#SmartTracking
- Download git 
- Tạo thư mục mới có tên là Git
- Vào thư mục nhấn chuột phải. Tiếp theo chọn Git Bash Here. Một terminal sẽ xuất hiện.
- Nhập câu lệnh git clone + url, theo repos này thì sẽ như thế này:

  git clone :https://github.com/lorateam1999/SmartTracking
  
- Sau đó một thư mục có tên SmartTracking sẽ xuất hiện, vào đó và tiếp tục chuột phải chọn Git Bash Here 
- Tạo branch riêng để phát triển: git checkout -b feature-01
  + nếu code app thì đẩy vào nhánh app, ví dụ: git checkout -b Appcode
  + Nếu code lora thì đẩy vào nhánh lora, ví dụ: git checkout -b Loracode
- Coppy toàn bộ code của mình đã code vào trong folder SmartTracking. Vào lại GitBashHere và tiếp tục thêm câu lệnh: git add .
- Code xong thì commit lên branch riêng đấy của từng phần: git commit -m "Feature hien thi .... xong"
- Đẩy code lên account cá nhân: git push origin <brach phần mình làm> 
 Ví dụ: git push origin Appcode
# trước mắt cứ làm vậy. nếu có xảy ra xung đột khi đẩy code thì nói ta hỉ.
