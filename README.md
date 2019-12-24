<img style="display:block; text-align:center" src="https://raw.githubusercontent.com/sapo-tech/home_test_mobile/master/Sapo-logo-noel.png" alt="Sapo Logo" max-width="100%" height="240px"/> 

# Chào mừng các bạn đến với công ty Sapo! 

Để giúp các bạn đánh giá chính xác năng lực của mình, đồng thời cũng giúp công ty xây dựng kế hoạch sử dụng, phát triển năng lực của các bạn, chúng tôi có một bài kiểm tra năng lực nhỏ. 

## Home Test for iOS Developer or Android Developer

#### Trong bài này, chúng ta sẽ mô phỏng thực hiện việc đăng ký sử dụng app.
<img style="display:block; text-align:center" src="https://raw.githubusercontent.com/sapo-tech/home_test_mobile/master/0.%20Overview.png" alt="Sapo Logo" max-width="100%" height="250px"/> 

* Hiển thị màn đăng ký. Kiểm tra điều kiện:  
```swift
- username > 8 ký tự.
- password > 8 ký tự. Có chữ hoa, chữ thường, và ký tự đặc biệt.
- repeat password phải trùng với password
```
<img  src="https://raw.githubusercontent.com/sapo-tech/home_test_mobile/master/1.%20Username%20Password.jpg" alt="Sapo Logo" max-width="100%" height="400px"/> 

* Load dữ liệu các thành phố từ [Link](https://raw.githubusercontent.com/sapo-tech/home_test_mobile/master/Cities.json) và hiển thị lên như hình vẽ 
<img style="display:block; text-align:center" src="https://raw.githubusercontent.com/sapo-tech/home_test_mobile/master/2.%20City%20Selection.jpg" alt="Sapo Logo" max-width="100%" height="400px"/> 

* Load dữ liệu các Quận huyện từ [Link](https://raw.githubusercontent.com/sapo-tech/home_test_mobile/master/Districts.json) và hiển thị lên như hình vẽ 

<img style="display:block; text-align:center" src="https://raw.githubusercontent.com/sapo-tech/home_test_mobile/master/3.%20Dictrict%20Selection.jpg" alt="Sapo Logo" max-width="100%" height="400px"/>


* Khi chọn một tỉnh thành, app sẽ hiển thị các quận huyện ở trong tỉnh thành đó. Khi Back lại màn chọn tỉnh thành, cell được chọn lúc trước vẫn hiển thị ở trạng thái Selected.

* Lựa chọn giới tính bằng 1 combo 3 nút radio button: Nam, Nữ, Khác. Sử dụng PickerView để lựa chọn tuổi. Bắt đầu từ 8 tuổi, kết thúc ở 80 tuổi. Tuổi mặc định là 25 tuổi.
<img style="display:block; text-align:center" src="https://raw.githubusercontent.com/sapo-tech/home_test_mobile/master/4.%20General%20Selection.jpg" alt="Sapo Logo" max-width="100%" height="400px"/>

* Hiển thị màn tổng kết: Tên, tuổi, giới tính, tỉnh thành, quận huyện. và Nút xác nhận Để login vào Màn Welcome của app. 
<img style="display:block; text-align:center" src="https://raw.githubusercontent.com/sapo-tech/home_test_mobile/master/5.%20Overall.jpg" alt="Sapo Logo" max-width="100%" height="400px"/>

* Màn Welcome 
<img style="display:block; text-align:center" src="https://raw.githubusercontent.com/sapo-tech/home_test_mobile/master/6.%20welcome.jpg" alt="Sapo Logo" max-width="100%" height="400px"/>


* Đẩy dự án lên Git và gửi đường link cho chúng tôi theo địa chỉ: thangtm@sapo.vn

#### Một số lưu ý:
* Các bạn có thể tham khảo tất cả các nguồn tài nguyên bạn có.
* Vì bài Test được thiết kế cho nhiều Level khác nhau, bạn không nhất thiết phải hoàn thành được hết tất cả các bài Test.
