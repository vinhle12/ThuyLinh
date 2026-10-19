# Mẫu trang quà tặng người thương

Giao diện nền sao và hoa rơi, bộ đếm kỷ niệm, sơ đồ khoảng cách, chân dung, hành trình, album và thư tình. Không còn nội dung hay ảnh cá nhân cũ; mini game đã được gỡ. Nhạc nền được giữ nguyên.

## Cá nhân hóa cho từng khách

Chỉnh **config.js** để thay tên người nhận, tên người gửi, biệt danh, ngày kỷ niệm, địa điểm, sở thích, các mốc kỷ niệm và nội dung thư. Tên người nhận sẽ tự cập nhật ở đầu trang, thư, chân trang và tiêu đề trình duyệt.

- **metAt**: điền ngày bắt đầu theo dạng YYYY-MM-DDTHH:mm:ss+07:00. Để trống sẽ hiển thị --, không sử dụng ngày cũ.
- **anniversaryLabel**: ngày kỷ niệm hiển thị trên trang, cần khớp với metAt.
- **timeline**: gồm bốn mốc; thay tiêu đề và lời kể của từng mốc.
- **letter**: mỗi chuỗi là một đoạn thư.
- **photos**: để trống sẽ hiện khung ảnh mẫu. Để thêm ảnh thật, tải các tệp ảnh của khách lên repo rồi thêm các mục có src và alt vào danh sách.

Ví dụ danh sách ảnh:

    photos: [
      { src: 'photos/ky-niem-01.jpg', alt: 'Kỷ niệm đầu tiên' },
      { src: 'photos/ky-niem-02.jpg', alt: 'Một ngày bên nhau' }
    ]

Mở **index.html** để xem mẫu, hoặc triển khai các tệp tĩnh trên GitHub Pages. Không cần cài thư viện hay chạy bước biên dịch. Nhạc phát lặp với âm lượng nhẹ sau thao tác nhấp, chạm hoặc nhấn phím; trình duyệt có thể chặn nhạc trước khi có tương tác.
