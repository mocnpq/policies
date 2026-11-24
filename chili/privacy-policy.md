---
title: Chi Li – Chính sách quyền riêng tư / Privacy Policy
---

<!-- Publish: copy this file to repo mocnpq/policies as chili/privacy-policy.md (GitHub Pages on, branch main, root).
     URL: https://mocnpq.github.io/policies/chili/privacy-policy — fixed in the app (BuildConfig.PRIVACY_POLICY_URL). -->

# Chi Li – Sổ Thu Chi Đơn Giản

[Tiếng Việt](#tiếng-việt) · [English](#english)

Ngày hiệu lực / Effective date: 24/11/2026 (Chi Li v1.3.0)

## Tiếng Việt

Chi Li là ứng dụng ghi chép thu chi cá nhân, lưu sổ thu chi trên điện thoại của bạn và cho phép bạn chủ động gửi báo lỗi.

**Dữ liệu ứng dụng lưu trữ**
- Các giao dịch bạn nhập (số tiền, danh mục, ngày, ghi chú), danh mục của bạn và các cài đặt của ứng dụng.
- Tất cả được lưu trong bộ nhớ riêng của ứng dụng trên thiết bị của bạn.

**Báo lỗi và dịch vụ xử lý**
- Chỉ khi bạn nhấn Gửi, báo cáo được gửi qua kết nối mã hóa tới Firebase Cloud Firestore của Google để hỗ trợ và khắc phục lỗi. Báo cáo gồm mã UUID ngẫu nhiên, mô tả do bạn nhập (tối đa 2.000 đơn vị UTF-16), phiên bản và số bản dựng ứng dụng, phiên bản Android, mẫu thiết bị và thời gian tạo do máy chủ ghi. Đừng nhập thông tin cá nhân hay tài chính vào mô tả.
- Phần đính kèm chẩn đoán mặc định tắt; bạn có thể xem trước và chọn gửi tối đa 30 mã sự kiện cho phép cùng thời gian tương đối. Các sự kiện không dự kiến chứa số tiền, ghi chú, ngày giao dịch, tên danh mục hoặc đường dẫn file. Sổ thu chi không thuộc nội dung báo cáo, nhưng văn bản tự nhập có thể chứa thông tin riêng tư.
- Firebase Firestore và App Check xử lý thông tin tác nhân Firebase (thông tin hệ điều hành/thiết bị, trình cài đặt và phiên bản SDK) để cung cấp, duy trì và cải thiện dịch vụ. App Check sử dụng mã Play Integrity để bảo vệ dịch vụ khỏi lạm dụng. Play Integrity xử lý dữ liệu xác minh ứng dụng, giấy phép và thiết bị, gồm hash/nonce yêu cầu, gói, phiên bản, chứng chỉ ký, trạng thái giấy phép và dữ liệu chứng thực thiết bị; Google xử lý theo thời hạn lưu riêng của họ. Xem [Firebase](https://firebase.google.com/docs/android/play-data-disclosure) và [Play Integrity](https://developer.android.com/google/play/integrity/terms).
- Quyền xem và xóa báo cáo được dành cho người phụ trách hỗ trợ được ủy quyền. Quy tắc Firestore không cho ứng dụng đọc báo cáo đã gửi. Chúng tôi lưu báo cáo trong 90 ngày kể từ thời điểm máy chủ ghi nhận, sau đó xóa báo cáo. Bạn có thể liên hệ địa chỉ bên dưới để yêu cầu xóa báo cáo; cung cấp mã tham chiếu nếu có. Xóa ứng dụng không tự xóa báo cáo đã gửi.

**Tài khoản và quảng cáo**
- Không cần tài khoản, không đăng nhập.
- Không có quảng cáo, công cụ phân tích hay theo dõi, hoặc SDK phục vụ các mục đích này.

**Sao lưu và khôi phục bằng file**
- Khi bạn chọn xuất bản sao lưu, Chi Li ghi toàn bộ danh mục và giao dịch (bao gồm số tiền, ngày và ghi chú) vào một file JSON ở vị trí bạn chọn qua trình chọn file của Android. File không chứa cài đặt ứng dụng.
- File JSON không được Chi Li mã hóa hay bảo vệ bằng mật khẩu. Người hoặc ứng dụng có quyền truy cập file có thể đọc nội dung; hãy lưu file ở nơi bạn tin cậy.
- Trình chọn file có thể hiển thị bộ nhớ trên thiết bị hoặc dịch vụ lưu trữ đám mây bạn đã cài đặt. Nếu bạn chọn dịch vụ đó, việc lưu trữ, đồng bộ và xử lý file tuân theo điều khoản và chính sách của nhà cung cấp; nhà phát triển Chi Li không nhận được bản sao.
- Chi Li chỉ đọc file bạn chọn để khôi phục. Bạn có thể gộp với dữ liệu hiện có hoặc thay toàn bộ dữ liệu giao dịch và danh mục trong ứng dụng; cài đặt ứng dụng được giữ nguyên.

**Sao lưu tự động của Android**
- Nếu bạn bật tính năng sao lưu của Android, hệ thống có thể sao lưu dữ liệu của Chi Li vào tài khoản Google của chính bạn để khôi phục khi đổi máy.
- Việc sao lưu này do Android và Google thực hiện theo [Chính sách quyền riêng tư của Google](https://policies.google.com/privacy); nhà phát triển không truy cập được bản sao lưu.
- Bạn có thể tắt trong Cài đặt của điện thoại (mục Sao lưu).

**Xóa dữ liệu**
- Xóa từng giao dịch ngay trong ứng dụng, hoặc xóa toàn bộ bằng cách gỡ cài đặt ứng dụng hay chọn "Xóa dữ liệu" trong phần thông tin ứng dụng của Android.
- File bạn đã xuất nằm ngoài bộ nhớ riêng của ứng dụng và không bị xóa khi gỡ cài đặt hoặc xóa dữ liệu ứng dụng. Hãy tự xóa file và các bản sao đã đồng bộ trong ứng dụng quản lý file hoặc dịch vụ lưu trữ bạn chọn. Bản sao lưu tự động của Android được quản lý trong cài đặt sao lưu của Android/Google.

**Trẻ em**
- Ứng dụng không hướng tới trẻ em dưới 13 tuổi và không cố ý thu thập thông tin của trẻ em.

**Thay đổi chính sách**
- Nếu ứng dụng thay đổi cách xử lý dữ liệu (ví dụ thêm quảng cáo), chính sách này sẽ được cập nhật trước khi phiên bản đó phát hành, kèm ngày hiệu lực mới.

**Liên hệ:** moc.npq@gmail.com

## English

Chi Li is a personal income and expense notebook that stores your notebook on your phone and lets you choose to send a bug report.

**Data the app stores**
- The transactions you enter (amount, category, date, note), your categories and the app's settings.
- All of it stays in the app's private storage on your device.

**Bug reports and service processing**
- Only when you press Send, a report is transmitted over an encrypted connection to Google's Firebase Cloud Firestore for support and troubleshooting. It contains a random UUID, your description (up to 2,000 UTF-16 units), app version and build number, Android version, device model and a server creation timestamp. Please leave personal and financial details out of your description.
- The diagnostic attachment is off by default; you can preview and choose to send up to 30 allowlisted event codes with relative times. These events are not intended to contain amounts, notes, transaction dates, category names or file paths. The notebook is not included in the report, although free text can contain private information.
- Firebase Firestore and App Check process the Firebase user agent (OS/device information, installer and SDK versions) to provide, maintain and improve their services. App Check uses a Play Integrity token to protect the service from abuse. Play Integrity processes app, licensing and device verification data including request hash/nonce, package, version, signing certificate, license status and device attestation data; Google applies its own retention period. See [Firebase](https://firebase.google.com/docs/android/play-data-disclosure) and [Play Integrity](https://developer.android.com/google/play/integrity/terms).
- Only authorized support operators have permission to view and delete reports. Firestore rules deny the app access to read submitted reports. We retain reports for 90 days from the server-recorded submission time and then delete them. Contact us below to request deletion, supplying the reference if available. Uninstalling the app does not automatically delete a submitted report.

**Accounts and advertising**
- No account and no sign-in.
- No ads, analytics or tracking, or SDKs for those purposes.

**File backup and restore**
- When you choose to export a backup, Chi Li writes all categories and transactions (including amounts, dates and notes) to a JSON file at the location you select through Android's system file picker. App settings are not included.
- Chi Li does not encrypt or password-protect the JSON file. Anyone or any app with access to the file can read its contents; keep it in a location you trust.
- The picker may offer local storage or a cloud storage service installed on your device. If you choose that service, its terms and privacy policy govern storage, synchronization and handling of the file; the Chi Li developer does not receive a copy.
- Chi Li reads only the file you select for restore. You can merge it with existing data or replace all transactions and categories in the app; app settings are kept.

**Android Auto Backup**
- If Android backup is turned on, the system may back up Chi Li's data to your own Google account so it can be restored on a new phone.
- This backup is done by Android and Google under the [Google Privacy Policy](https://policies.google.com/privacy); the developer has no access to it.
- You can turn it off in your phone's Settings (Backup).

**Deleting data**
- Delete single transactions in the app, or delete everything by uninstalling the app or using "Clear storage" in Android's app info.
- Exported files are outside the app's private storage and are not deleted when you uninstall the app or clear its storage. Delete those files and any synchronized copies yourself using your file manager or chosen storage service. Android Auto Backup copies are managed in Android/Google backup settings.

**Children**
- The app is not directed at children under 13 and does not knowingly collect information from children.

**Changes**
- If the app changes how it handles data (for example by adding ads), this policy will be updated before that version is released, with a new effective date.

**Contact:** moc.npq@gmail.com
