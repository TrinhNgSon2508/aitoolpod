# Hướng Dẫn Đưa Trang Giới Thiệu Lên Mạng Miễn Phí (100% Free Hosting)

Để đăng trang giới thiệu sản phẩm của bạn lên internet cho khách hàng xem mà không tốn bất kỳ chi phí nào (không cần mua tên miền `.com`, `.vn` và không cần thuê hosting hàng tháng), bạn có thể sử dụng các dịch vụ Cloud Hosting miễn phí tốt nhất hiện nay là **Netlify Drop**, **Vercel** hoặc **GitHub Pages**.

Dưới đây là hướng dẫn chi tiết từng cách thực hiện cực kỳ đơn giản (chỉ mất 1 - 2 phút).

---

## 🚀 Cách 1: Sử dụng Netlify Drop (Đơn giản nhất, không cần cài đặt)

Đây là cách nhanh nhất dành cho người không chuyên. Bạn chỉ cần kéo và thả thư mục.

1. **Truy cập**: Mở trình duyệt và truy cập trang web [app.netlify.com/drop](https://app.netlify.com/drop)
2. **Kéo thả thư mục**: Kéo toàn bộ thư mục **`landing`** chứa tệp `index.html` trên máy tính của bạn và thả vào khung nét đứt màu xanh trên trang web Netlify.
3. **Chờ xử lý**: Hệ thống sẽ tải lên và khởi tạo trang web của bạn trong vòng 5 giây.
4. **Nhận link**: Bạn sẽ nhận được một đường dẫn ngẫu nhiên dạng `https://ten-ngau-nhien.netlify.app`. 
5. **Đổi tên miền (Tùy chọn)**:
   - Nhấp vào **"Sign up"** để đăng ký một tài khoản miễn phí (để quản lý và giữ trang web này vĩnh viễn).
   - Sau khi đăng nhập, vào **Site Configuration** -> **Change Site Name** -> Điền tên bạn muốn (Ví dụ: `aipodupscaler` để có link đẹp là `https://aipodupscaler.netlify.app`).

---

## ⚡ Cách 2: Sử dụng Vercel (Hiện đại, tốc độ tải trang cực nhanh)

Vercel là nền tảng máy chủ đám mây mạnh mẽ, tải trang siêu nhanh và hoàn toàn miễn phí cho trang web tĩnh.

1. **Đăng ký tài khoản**: Truy cập [vercel.com](https://vercel.com) và đăng ký một tài khoản miễn phí (bằng Email hoặc liên kết tài khoản GitHub).
2. **Tải Vercel CLI (Cách nhanh)** hoặc **Tải qua Web**:
   - Cách dễ nhất không cần code: Bạn nén thư mục **`landing`** thành tệp **`landing.zip`**.
   - Đăng nhập vào trang quản trị Vercel Dashboard, chọn **Add New** -> **Project** -> Chọn phần **Drag & Drop** để tải tệp `.zip` lên.
3. **Nhận link**: Vercel sẽ tự động deploy và cấp cho bạn link dạng `https://landing-xxx.vercel.app`.
4. **Đổi tên miền**: Bạn có thể vào tab **Settings** -> **Domains** để sửa đổi tên miền phụ `.vercel.app` theo ý thích của mình.

---

## 🐙 Cách 3: Sử dụng GitHub Pages (Cho ai muốn lưu trữ lâu dài bằng Git)

Nếu bạn có tài khoản GitHub và muốn lưu trữ quản lý code lâu dài:

1. **Tạo Repository**: Truy cập [github.com](https://github.com), đăng nhập và tạo một Repository mới (để chế độ **Public**).
2. **Tải file lên**: Tải file `index.html` của thư mục `landing` lên Repository này.
3. **Kích hoạt Pages**:
   - Vào mục **Settings** (Cài đặt) của Repository đó.
   - Nhấp vào mục **Pages** ở thanh menu bên trái.
   - Dưới phần **Build and deployment** -> **Source**, chọn **Deploy from a branch**.
   - Tại mục **Branch**, chọn nhánh **`main`** (hoặc `master`) và thư mục gốc `/ (root)`, sau đó bấm **Save**.
4. **Hoàn thành**: Chờ khoảng 1 phút, GitHub sẽ hiển thị đường link trang web của bạn ở đầu trang Pages đó (thường có dạng: `https://ten-tai-khoan.github.io/ten-repository/`).
