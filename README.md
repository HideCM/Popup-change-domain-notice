### Giải thích:

-   **Kiểm tra domain**: JavaScript kiểm tra domain hiện tại bằng `window.location.hostname`. Nếu domain là `domain-cu.com`, popup sẽ hiển thị.
-   **Nếu domain không phải `domain-moi.net`**: Popup sẽ không hiển thị, và người dùng sẽ không thấy bất kỳ thay đổi nào.

Hãy đảm bảo rằng bạn thay thế `"https://domainmoi.com"` bằng URL của domain mới mà bạn muốn chuyển hướng người dùng tới.

### Sử dụng
Đưa code vào sau `<head>`
