---
layout: post
title:  "Flutter 3.7 có gì mới?"
author: dantino
categories: [Flutter, Flutter 3.7, Flutter Updates]
image: assets/images/posts/whats-new-3_7-post-thumbnail-vi.jpeg
tags: [featured]
---
# Các điểm mới và cải tiến trong bản Flutter 3.7 

The start of 2023 is fabulous for developers using Flutter, as Google has just released Flutter 3.7. Developers can further enhance the ease of the coding process with great new features. Additionally, Flutter has revamped and optimized the existing features. However, the Dart 3 stable release is still not announced but it will bring productivity and portability in future.
Đầu năm 2023 thật tuyệt vời đối với các nhà phát triển sử dụng Flutter, vì Google vừa phát hành Flutter 3.7. Các nhà phát triển có thể tăng cường hơn nữa sự dễ dàng của quy trình lập trình với các tính năng mới tuyệt vời. Ngoài ra, Flutter đã cải tiến và tối ưu hóa các tính năng hiện có. Tuy nhiên, bản phát hành ổn định của Dart 3 vẫn chưa được công bố nhưng nó sẽ mang lại năng suất và tính di động trong tương lai.

Hãy cùng điểm qua các tính năng và các cải tiến trong Flutter 3.7!

>
> ***Các nội dung trong bài viết:***
>  	
> 1. Các tính năng mới trong Flutter 3.7?
> 
> - Thanh menu và menu ngữ cảnh xếp tầng
>
> - Bản preview Impeller
> 
> - Xác thực phát hành cho iOS
> 
> - Menu ngữ cảnh tuỳ biến
> 
> 2. Các cải tiến trong Flutter 3.7?
> 
> 3. Các điều chỉnh trong Flutter 3.7?
> 
> 4. Các điều tiếp theo cho cộng đồng Flutter?

## Các tính năng mới trong Flutter 3.7?

### **Thanh menu và menu xếp chồng** 
Flutter hiện có thể xây dựng các thanh menu và menu ngữ cảnh xếp tầng.

Đối với macOS, hãy tạo thanh menu bằng tiện ích PlatformMenuBar xác định thanh menu gốc của nền tảng được macOS hiển thị thay vì nền tảng Flutter.

Tuy nhiên, đối với tất cả các nền tảng, bạn có thể xác định MaterialDesignMenu, cung cấp thanh menu xếp tầng hoặc menu xếp tầng độc lập được kích hoạt bởi các thành phần giao diện người dùng khác. Do đó, các menu này có thể tùy chỉnh và các mục menu có thể là tiện ích con tùy chỉnh hoặc bạn có thể sử dụng tiện ích con mục menu mới.

![Menu Bars & Cascading menus]({{ site.baseurl }}/assets/images/posts/whats-new-3_7-Menu-Bars-Cascading-menus.jpeg)

### **Impeller preview** 
Cộng đồng Flutter rất vui khi thấy một công cụ kết xuất Impeller mới đã sẵn sàng để phát triển ứng dụng iOS. Hiệu suất của Impeller sẽ đáp ứng hoặc vượt qua trình kết xuất Skia đối với hầu hết các ứng dụng và về độ trung thực. Impeller là mặc định được hiển thị trên nền tảng iOS.

Chúng tôi tin tưởng rằng Impeller trên iOS sẽ đáp ứng nhu cầu kết xuất của tất cả các ứng dụng Flutter hiện có và một số lỗi còn thiếu sốt chưa được thực hiện bới các API của Flutter. Do đó, người dùng có thể nhận thấy sự khác biệt trực quan trong kết xuất giữa Impeller và Skia trong Flutter. Vì vậy, những khác biệt nhỏ này có thể là lỗi, vì vậy vui lòng gửi vấn đề cho đội ngũ phát triển của Flutter.

Do đó, chúng tôi tiếp tục phát triển chương trình phụ trợ Vulkan cho Impeller, nhưng Impeller trên Android vẫn cần phải sẵn sàng để xem trước. Hỗ trợ Android đang được phát triển tích cực và hy vọng sẽ chia sẻ nó với tin tức về hỗ trợ web và máy tính để bàn trong các bản phát hành trong tương lai.

### **Xác thực khi phát hành ứng dụng trên iOS** 
Khi bạn phát hành ứng dụng iOS, hãy kiểm tra danh sách cài đặt để cập nhật và đảm bảo rằng ứng dụng của bạn đã sẵn sàng để gửi lên App Store.

Lệnh Flutter build ipa giờ đây sẽ xác thực một số cài đặt và thông báo cho bạn nếu có những sửa đổi cần được thực hiện đối với ứng dụng của bạn trước khi phát hành.

![iOS Release validation]({{ site.baseurl }}/assets/images/posts/whats-new-3_7-iOs-release-validation.jpeg)

### **Menu theo ngữ cảnh** 
YoBạn có thể tạo các menu tùy chỉnh ở bất cứ đâu bạn muốn trong ứng dụng của mình.

Ví dụ: các nhà phát triển có thể trình bày trực quan cho người dùng những gì họ đã chọn thông qua menu kiểu di chuột.
tham số contextMenuBuilder có thể trả về TextField.

![Custom context menus]({{ site.baseurl }}/assets/images/posts/whats-new-3_7-Custom-context-menus.gif)

## Các cải tiến trong Flutter 3.7?
1. Trong Flutter 3.7, Google đã tăng cường hỗ trợ material 3 và di chuyển một loạt tiện ích con. Để sử dụng các cải tiến của material 3, bạn phải chỉ định useMaterial3 trong tiện ích ThemeData của ứng dụng. Flutter sẽ tự tạo bảng màu cho bạn. Đây là cách mã hoàn chỉnh hoạt động.
   
    ![Sử dụng Material 3]({{ site.baseurl }}/assets/images/posts/whats-new-3_7-usematerial3.jpeg)

2. DevTools được cập nhật với Flutter 3.7 mới mang lại trải nghiệm tuyệt vời cho các nhà phát triển, đặc biệt là trong khi gỡ lỗi.
   
3. Các cải tiến về thao tác cuộn được cung cấp cùng với bản phát hành này để mang lại sự trau chuốt và tinh tế hơn cho các tương tác trên bàn di chuột. Các vật dụng mới như ScrollBars và DraggableScrollableSheet sẽ đảm bảo như vậy.
   
4. Hỗ trợ quốc tế hóa được nhóm Flutter sửa đổi hoàn toàn. Bây giờ chúng đại diện cho các lỗi cú pháp mô tả để cho phép các nhà phát triển thực hiện gỡ lỗi một cách chi tiết.
   
5. Vùng chọn cho phép mở rộng vùng chọn thông qua bàn phím. Ví dụ: phím tắt Shift+phải sẽ hoạt động trong ứng dụng Flutter. Ngoài ra, kính lúp văn bản xuất hiện trong khi chọn văn bản. Vùng chọn cho phép lựa chọn mở rộng thông qua bàn phím.
   
![Sử dụng Material 3]({{ site.baseurl }}/assets/images/posts/whats-new-3_7-SelectionArea-allows-extended-selection-through-the-keyboard.gif)

6. iOS platformView BackdropFilter làm mờ các phần tử bên dưới phần tử chính. Nó mang lại mục đích cung cấp giao diện người dùng tốt nhất cho người dùng. Nền tảng iOSView BackdropFilter làm mờ các phần tử bên dưới phần tử chính.
   
![Sử dụng Material 3]({{ site.baseurl }}/assets/images/posts/whats-new-3_7-backdropblur.jpeg)

7. Quản lý bộ nhớ tốt hơn với Flutter 3.7. Nó giảm rác sau khi thu gom rác, mang lại khả năng sử dụng CPU tốt hơn trong các ứng dụng. Dung lượng bộ nhớ được giảm so với phiên bản trước.
   
## Các điều chỉnh được thực hiện trong Flutter 3.7? 

- Plugin quick_actions được di chuyển từ Mục tiêu C sang Swift, cung cấp các phương pháp phát triển tốt nhất và được cập nhật cho các nhà phát triển.
- Trong Xcode 14, bitcode không còn quan trọng trong khi xây dựng ứng dụng cho watchOS và tvOS. Cửa hàng ứng dụng không chấp nhận bitcoder nữa trong quá trình đưa ứng dụng lên App Store.
  
  ![iOS Release validation]({{ site.baseurl }}/assets/images/posts/whats-new-3_7-bitcode-disable.jpeg)
## Các điều tiếp theo cho cộng đồng Flutter? 
Flutter dường như đã sẵn sàng để đột phá và nâng cao hiệu suất đồ họa với Impeller.

Các cải tiến và loại bỏ các tiện ích không cần thiết là một hướng đi chính khác mà Flutter dường như đang hoạt động. Hơn nữa, cộng đồng có hiệu quả cao trong việc mang lại các tính năng và chức năng hấp dẫn để làm cho trải nghiệm giao diện người dùng trở nên linh hoạt cho người dùng cuối.

Tuy nhiên, chúng tôi vẫn đang chờ bản phát hành ổn định của [Dart 3].

Thông tin chính thức về bản phát hành [Flutter 3.7 tại đây].

[Dart 3]: https://medium.com/dartlang/dart-3-alpha-f1458fb9d232
[Flutter 3.7 tại đây]: https://medium.com/flutter/whats-new-in-flutter-3-7-38cbea71133c
