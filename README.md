## Yêu Cầu Hệ Thống
- **Android SDK**: 21+ | Kotlin 2.1.0+  (Android 5.0+)
  - **Package:** *Android SDK Platform, Android SDK Build-Tools, Android Emulator Mới Nhất*

- **JDK**: 11+ LST (Java 17 20 LST)
- **Gradle**: 8.1.0+
- **JVM:** 1.8+
- **Flutter SDK**: 3.6.0+
- **iOS SDK**: 11+
- **Xcode**: 14.0+
- **CocoaPods**: 1.11.0+

## Miêu Tả Ứng Dụng
- **Tên Ứng Dụng**: Quản Lý Phòng Trọ
- **Tên Tiếng Anh**: Simple House App
- **Phiên Bản**: 1.0.0+1

**Ứng dụng quản lý phòng trọ giúp người dùng quản lý thông tin phòng trọ, thống kê chi phí, hiển thị biểu đồ thống kê chi phí theo thời gian.**

## Các Chức Năng Chính
- **Quản Lý Phòng Trọ**: Thêm, sửa, xóa và xem thông tin chi tiết của các phòng trọ.
- **Thống Kê Chi Phí**: Thống kê chi phí hàng tháng, hàng năm và hiển thị biểu đồ chi phí.
- **Quản Lý Người Thuê**: Thêm, sửa, xóa và xem thông tin chi tiết của người thuê phòng.
- **Thông Báo**: Gửi thông báo nhắc nhở thanh toán tiền phòng, tiền điện, nước.
- **Đăng Nhập/Đăng Xuất**: Hỗ trợ đăng nhập, đăng xuất và quản lý tài khoản người dùng.
- **Đa Ngôn Ngữ**: Hỗ trợ nhiều ngôn ngữ: en và vi.
- **Sao Lưu và Khôi Phục Dữ Liệu**: Sao lưu dữ liệu lên đám mây và khôi phục khi cần thiết.
- **Tìm Kiếm**: Tìm kiếm thông tin phòng trọ, người thuê nhanh chóng.
- **Cài Đặt**: Tùy chỉnh các cài đặt của ứng dụng theo nhu cầu người dùng.
- **Hỗ Trợ Ngoại Tuyến**: Sử dụng ứng dụng ngay cả khi không có kết nối mạng.
- **Mini App Calculator**: Tính toán nhanh chóng mà không cần thoát ứng dụng.


## Công Nghệ Sử Dụng
- **Ngôn Ngữ Lập Trình**: Dart
- **Framework**: Flutter
- **Database**: SQLite
- **API**: RESTful API
- **Biểu Đồ**: Fl_Chart
- **Quản Lý Trạng Thái**: Provider
- **Quản Lý Dữ Liệu**: Riverpod
- **Kiểm Thử**: Mockito, Flutter Test
- **Kiểm Tra Lỗi**: Flutter Lint
- **Quản Lý Dự Án**: Git, Github - Bitbucket
- **IDE**: Visual Studio Code
- **Công Cụ Phát Triển**: Flutter SDK 2.5.3
- **Mô hình thiết kế**: MVVM
- **Kiến Trúc**: Clean Architecture
- **Đa Ngôn Ngữ**: Easy Localization
- **Địa Phương Hóa**: Flutter Localizations
- **Sao Lưu Dữ Liệu**: Shared Preferences
- **Giao Diện Người Dùng**: Cupertino Icons, Font Awesome Flutter

## Các Thư Viện Sử Dụng
- **Cupertino Icons**: Cung cấp các biểu tượng phong cách iOS.
- **MobX**: Quản lý trạng thái phản ứng cho Dart và Flutter.
- **Flutter MobX**: Tích hợp MobX với Flutter.
- **Provider**: Quản lý trạng thái và phụ thuộc.
- **MobX Codegen**: Tạo mã tự động cho MobX.
- **Shared Preferences**: Lưu trữ dữ liệu đơn giản trên thiết bị.
- **Dio**: Thư viện HTTP mạnh mẽ cho Dart.
- **Json Serializable**: Tạo mã tự động cho JSON serialization.
- **HTTP**: Thư viện HTTP đơn giản cho Dart.
- **FL Chart**: Vẽ biểu đồ trong Flutter.
- **Pie Chart**: Vẽ biểu đồ tròn trong Flutter.
- **Font Awesome Flutter**: Sử dụng các biểu tượng Font Awesome trong Flutter.
- **Easy Localization**: Hỗ trợ đa ngôn ngữ cho ứng dụng Flutter.
- **Flutter Localizations**: Hỗ trợ đa ngôn ngữ và địa phương hóa.
- **Math Expressions**: Đánh giá các biểu thức toán học.
- **Flutter Test**: Kiểm thử đơn vị và tích hợp cho Flutter.
- **Flutter Lints**: Bộ quy tắc linting cho Flutter.

## Các Thư Viện Flutter.dev
- **permission_handler: ^11.3.1**: Cấp quyền truy cập bộ nhớ.
- **path_provider: ^2.1.5**: Hỗ trợ truy cập bộ nhớ.
- **file_picker: ^8.1.7**:
- **open_filex: ^4.6.0**:
- **screenshot: ^3.0.0**: Chụp và lưu ảnh Widget.
- **pdf: ^3.11.1**: Tạo file PDF.

## Cài Đặt
- **Yêu Cầu**: Đã cài đặt Flutter SDK và thiết lập môi trường phát triển Flutter.
- **Bước 1**: Clone dự án từ Github.
- **Bước 2**: Mở thư mục dự án trong Visual Studio Code.
- **Bước 3**: Mở terminal và chạy lệnh `flutter pub get` để cài đặt các gói phụ thuộc.
- **Bước 4**: Chạy ứng dụng bằng lệnh `flutter run`.

## Tùy chỉnh AndroidManifest.xml và Info.plist IOS

### AndroidManifest.xml
- android/app/src/main/AndroidManifest.xml
```xml

    <uses-permission android:name="android.permission.READ_EXTERNAL_STORAGE"/>
    <uses-permission android:name="android.permission.WRITE_EXTERNAL_STORAGE"/>
    <uses-permission android:name="android.permission.INTERNET"/>
    <!-- Quyền INTERNET để hỗ trợ giao tiếp trong quá trình phát triển -->
    <uses-permission android:name="android.permission.INTERNET" />
    <!-- Quyền MANAGE_EXTERNAL_STORAGE (chỉ dành cho Android 11 trở lên) -->
    <uses-permission android:name="android.permission.MANAGE_EXTERNAL_STORAGE" />
    <!-- Các quyền READ/WRITE_EXTERNAL_STORAGE dành cho Android 10 trở xuống -->
    <uses-permission android:name="android.permission.READ_EXTERNAL_STORAGE" />
    <uses-permission android:name="android.permission.WRITE_EXTERNAL_STORAGE" />
    
    <!-- Quyền ACCESS_MEDIA_LOCATION dành cho Android 10 trở lên -->
    <uses-permission android:name="android.permission.ACCESS_MEDIA_LOCATION" />
    <!-- Quyền CAMERA để sử dụng camera -->
    <uses-permission android:name="android.permission.CAMERA" />
    <!-- Quyền Vị trí -->
    <uses-permission android:name="android.permission.ACCESS_FINE_LOCATION" />
    <uses-permission android:name="android.permission.ACCESS_COARSE_LOCATION" />
    <!-- Quyền Truy cập lịch -->
    <uses-permission android:name="android.permission.READ_CALENDAR" />
    <uses-permission android:name="android.permission.WRITE_CALENDAR" />


<application
       android:requestLegacyExternalStorage="true"

<meta-data android:name="android.permission.MANAGE_EXTERNAL_STORAGE"
        android:value="true" />

</application>

```

- android/app/src/profile/AndroidManifest.xml

## Info.plist
ios/Runner/Info.plist
```swift
<key>NSCameraUsageDescription</key>
		<string>Ứng dụng cần sử dụng camera để chụp ảnh hoặc quay video.</string>
		<key>NSLocationWhenInUseUsageDescription</key>
		<string>Ứng dụng cần sử dụng vị trí của bạn để cung cấp dịch vụ tốt hơn.</string>
		
		<key>NSPhotoLibraryUsageDescription</key>
		<string>Ứng dụng cần truy cập thư viện ảnh để lưu và xem ảnh.</string>
		
		<key>NSPhotoLibraryAddUsageDescription</key>
		<string>Ứng dụng cần quyền để lưu ảnh vào thư viện của bạn.</string>
		
		<key>NSCalendarsUsageDescription</key>
		<string>Ứng dụng cần truy cập lịch để lên lịch hẹn hoặc sự kiện.</string>
		
		<key>NSDocumentsFolderUsageDescription</key>
		<string>Ứng dụng cần quyền truy cập tài liệu để lưu và đọc file.</string>
		
		<key>NSUserTrackingUsageDescription</key>
		<string>Ứng dụng cần quyền theo dõi để cung cấp nội dung cá nhân hóa.</string
```


## Cấu trúc thư mục
### **- ```lib```**
Chứa mã nguồn chính của ứng dụng Flutter.

- **```api```**: Chứa các lớp để gọi API.
  - `api_service.dart`: Lớp quản lý các yêu cầu API chung.
  - `room_statistic_api.dart`: Lớp quản lý các yêu cầu API liên quan đến thống kê phòng.
  - `room_chart_api.dart`: Lớp quản lý các yêu cầu API liên quan đến biểu đồ phòng.
  - `room_api.dart`: Lớp quản lý các yêu cầu API liên quan đến phòng.
  - `tenant_api.dart`: Lớp quản lý các yêu cầu API liên quan đến người thuê.
  - `notification_api.dart`: Lớp quản lý các yêu cầu API liên quan đến thông báo.
  - `auth_api.dart`: Lớp quản lý các yêu cầu API liên quan đến đăng nhập và đăng ký.
  - `backup_api.dart`: Lớp quản lý các yêu cầu API liên quan đến sao lưu và khôi phục dữ liệu.
  - `search_api.dart`: Lớp quản lý các yêu cầu API liên quan đến tìm kiếm.
  - `settings_api.dart`: Lớp quản lý các yêu cầu API liên quan đến cài đặt.
  - `offline_api.dart`: Lớp quản lý các yêu cầu API liên quan đến dữ liệu ngoại tuyến.

- **```feature```**: Chứa các tính năng chính của ứng dụng.
  - **```home```**: Chứa tất cả thành phần giao diện và sự kiện người dùng.
    - **```view```**: Chứa các widget hiển thị giao diện người dùng.
      - `home_tab.dart`: Widget hiển thị tab Home.
      - `room_tab.dart`: Widget hiển thị tab Room.
      - `calculation_tab.dart`: Widget hiển thị tab Calculation.
    - **```viewModel```**: Chứa các lớp quản lý trạng thái và logic của các view.
      - `home_tab_viewmodel.dart`: Lớp quản lý trạng thái và logic của `home_tab.dart`.
      - `room_tab_viewmodel.dart`: Lớp quản lý trạng thái và logic của `room_tab.dart`.
      - `calculation_tab_viewmodel.dart`: Lớp quản lý trạng thái và logic của `calculation_tab.dart`.

- **```model```**
     - `room.dart`: Lớp mô hình dữ liệu cho phòng trọ.
     - `room_statistic.dart`: Lớp mô hình dữ liệu cho thống kê phòng.
     - `room_chart.dart`: Lớp mô hình dữ liệu cho biểu đồ phòng.
     - ...

- **```utils```**: Chứa các tiện ích dùng chung.
  - `font_size_utils.dart`: Tiện ích để quản lý kích thước font chữ tự động theo kích thước màn hình.

- **```widgets```**: Chứa các widget dùng chung trong ứng dụng.
  - `custom_button.dart`: Widget nút tùy chỉnh.
  - `custom_text_field.dart`: Widget trường văn bản tùy chỉnh.

### **- ```assets```**
Chứa các tài sản tĩnh như hình ảnh, dữ liệu JSON.

- `offline_api_data.json`: Dữ liệu JSON để sử dụng khi không có kết nối mạng, test máy thực.
- **```images```**: Chứa các hình ảnh sử dụng trong ứng dụng.
  - `logo.png`: Hình ảnh logo của ứng dụng.
  - `background.jpg`: Hình ảnh nền của ứng dụng.
- **```icons```**: Chứa các biểu tượng sử dụng trong ứng dụng.
- **```fonts```**: Chứa các font chữ sử dụng trong ứng dụng.
- **```lang```**: Chứa các file ngôn ngữ dùng cho En và Vi.

### Cây Cấu trúc thư mục
```
lib/
├── api/
│   ├── api_service.dart
│   ├── room_statistic_api.dart
│   └── room_chart_api.dart
├── feature/
│   ├── home/
│   │   ├── view/
│   |   |   ├── calculation_tab/
│   │   │   |   ├── calculation_screen.dart
│   │   │   |   └──
│   │   │   ├── home_tab/
│   │   │   |   ├── home_screen.dart
│   │   │   |   └──
│   │   │   ├── room_tab/
│   │   │   |   ├── room_screen.dart
│   │   │   |   └──
│   │   └── viewModel/
│   |       ├── calculation_tab/
│   │       |   ├── calculation_tab_viewmodel.dart
│   │       |   └──
│   │       ├── home_tab/
│   │       |   ├── home_tab_viewmodel.dart
│   │       |   └──
│   │       └── room_tab/
│   │           ├── room_tab_viewmodel.dart
│   │           └── ...
│   ├── login/
│   │   ├── view/
│   │   │   ├── login_screen.dart
│   │   │   └── forgot_password_screen.dart
│   │   └── viewModel/
│   │       ├── login_viewmodel.dart
│   │       └── forgot_password_viewmodel.dart
│   └── settings/
│       ├── view/
│       │   ├── settings_screen.dart
│       │   └── profile_screen.dart
│       └── viewModel/
│           ├── settings_viewmodel.dart
│           └── profile_viewmodel.dart
├── utils/
│   ├── font_size_utils.dart
│   └── date_utils.dart
├── widgets/
│   ├── custom_button.dart
│   ├── custom_text_field.dart
│   └── custom_dialog.dart
assets/
├── offline_api_data.json
├── images/
│   ├── logo.png
│   └── background.jpg
```

## Screenshots
<p align="center">
<img src=.images\p-01.png width="200" style="border: 2px solid black">
<img src=.images\p-02.png width="200" style="border: 2px solid black">
<img src=.images\p-03.png width="200" style="border: 2px solid black">
</p>
<p align="center">
<img src=.images\p-04.png width="200" style="border: 2px solid black">
<img src=.images\p-05.png width="200" style="border: 2px solid black">
<img src=.images\p-06.png width="200" style="border: 2px solid black">
</p>
<p align="center">
<img src=.images\p-07.png width="200" style="border: 2px solid black">
<img src=.images\p-08.png width="200" style="border: 2px solid black">
<img src=.images\p-09.png width="200" style="border: 2px solid black">
</p>
<p align="center">
<img src=.images\p-10.png width="200" style="border: 2px solid black">
<img src=.images\p-11.png width="200" style="border: 2px solid black">
<img src=.images\p-12.png width="200" style="border: 2px solid black">
</p>
<p align="center">
<img src=.images\p-14.png width="200" style="border: 2px solid black"></p>
</p>
</br>

<img src=.images\p-l-01.png width="500" style="border: 2px solid black"></p>
<img src=.images\p-l-02.png width="500" style="border: 2px solid black"></p>
<img src=.images\p-l-03.png width="500" style="border: 2px solid black"></p>
