# Hotel Booking Image-Based Prototype

Prototype này dùng trực tiếp ảnh PNG export từ Figma:

- `Hotel-wed/`: frame Website
- `Hotel-mobile-app/`: frame Mobile app

## Cách mở

Mở trực tiếp file HTML ở thư mục gốc, ví dụ:

- `open.html`
- `login.html`
- `index.html`
- `room.html`

Không cần backend, không cần JavaScript, không cần asset riêng.

## Responsive

- Dưới `768px`: hiển thị ảnh Mobile app.
- Từ `768px` trở lên: hiển thị ảnh Website.

Một số màn có header Website được crop fixed top từ chính ảnh frame. Một số màn Mobile có bottom navigation được crop fixed bottom từ chính ảnh frame.

## Hotspot

Các link demo là vùng click trong suốt đặt đè lên ảnh. Có thể chỉnh tọa độ trong từng file HTML bằng các thẻ `a.hotspot`.
