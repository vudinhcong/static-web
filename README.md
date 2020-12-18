# static-web

Bài thực hành của em là 1 website gồm 2 trang chính là trang chủ và ẩm thực. Website có tên là ViVuHàNội viết về những địa danh cũng nhưng ẩm thực của Hà Nội.
*Nội dung các trang
  1. Trang chủ
  Bố cục Trang chủ của em e chia làm 4 phần:
  +) phần đầu tiên chứa menu
  +) phần thứ hai chứa nội dung 
  +) phần thứ 3 đăng ký email để gửi thông tin khi có bài viết mới
  +) cuối cùng là footer
  - Phần đầu tiên:
    +)Về HTML: em có tạo ra 1 div lớn container bên trong có div banner để chứa ảnh và nội dung, trong div banner sẽ là một cái banner có chiều rộn width 100% , chiều cao      height 680px trong cái ảnh đó em chia làm 2 phần phần làm 2 thẻ div (top) và div(bootom).Div top gồm thẻ h2 chứa tên trang Web và 3 tiêu đề mục con, div bootom gồm thẻ p và h4 
    +)Về CSS:div top em có đặt cho nó position: fixed để khi kéo chuột xuống sẽ nằm im ở trên đầu, dùng position: absolute với các thẻ h2, ul, bootom để cho chũ nằm ở trên banner,em còn dùng một vài font chữ khác nhau và text-shadow để tạo độ bóng cho chữ mà mình muốn.
    +)Về javascript: thì em có sử dụng đối với banner em sẽ để 5 cái banner và sẽ đặt cho nó thời gian cứ 6s nó sẽ chuyển sang một cái banner khác
    +)Tron div container em có đặt nút button có tên Top kết hợp với CSS và javascript sự kiện onclick khi cuộn chuột xuống 20px tính từ đầu trang thì nó sẽ hiện ra môt cái nút bấm để giúp người dụng hạn chế thời gian quay lại đầu khi cuộn chuột xuống sâu.  
  - Phần thứ hai:
    +)Về HTML: em có sử dụng 1 thẻ div lớn có class content với width 90%, height 13150px, margin auto căn đều 2 bên bên trong e lại chia thành hai div là content-left và conten-right.Đổi với content-left để chứa ảnh với kịch thước khác nhau dưới mỗi cái ảnh sẽ là thẻ p để viết nội dung của cái ảnh đó em để width 69%, float left với content-right chứ thanh tìm kiếm ở trên đầu bên là 5 cái video em lấy trên youtube em để width 30% với float right để cho sang bên phải
    +)Về CSS: mỗi cái ảnh bên phải em có để border-radius 10px để bo tròn 4 góc lại, Bên thẻ content-right em có sử dụng position sticky để khi kéo cuột xuống dưới khi nội dung bên phải thay đổi thì contet-right vẫn đứng im cho đến hết height 13150px.
  - Phần thứ ba: là phần để người dung đăng ký email thì khi có nội dung mới thì thông tin sẽ được gửi đến email của người dùng giúp người dùng cập nhật nhanh hơn
    +)Về HTML: gồm thẻ p, input và button có tên Đăng Ký
    +)Về Javascript: để check xem người dùng đã nhập đúng email hay chưa khi người dùng nhấn vào nút đăng ký nếu vị trí của @ đặt sai thì nó sẽ báo lỗi email không hợp lệ
  - Phần cuối cùng là footer
    +)Về HTML: em có chia footer thành 2 phần ft-left và ft-right là bên trái và bên phải, bên trái là tên trang, bên phải dụng thẻ h3 với thẻ p để liệt kê một số ẩm thực và điểm đến nổi bật ở Hà Nội
    
    
    
    
    
    
