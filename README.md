# static-web

Bài thực hành của em là 1 website gồm 2 trang chính là trang chủ và ẩm thực. Website có tên là ViVuHàNội viết về những địa danh cũng nhưng ẩm thực của Hà Nội.
### Nội dung các trang
#### I. Trang chủ
  ##### Bố cục Trang chủ của em chia làm 4 phần:
  - phần đầu tiên chứa menu
  - phần thứ hai chứa nội dung 
  - phần thứ 3 đăng ký email để gửi thông tin khi có bài viết mới
  - cuối cùng là footer
  1. Phần đầu tiên:
    - Về HTML: em có tạo ra 1 div lớn container bên trong có div banner để chứa ảnh và nội dung, trong div banner sẽ là một cái banner có chiều rộn width 100% , chiều cao      height 680px trong cái ảnh đó em chia làm 2 phần phần làm 2 thẻ div (top) và div(bootom).Div top gồm thẻ h2 chứa tên trang Web và 3 tiêu đề mục con, div bootom gồm thẻ p và h4 
    - Về CSS:div top em có đặt cho nó position: fixed để khi kéo chuột xuống sẽ nằm im ở trên đầu, dùng position: absolute với các thẻ h2, ul, bootom để cho chũ nằm ở trên banner,em còn dùng một vài font chữ khác nhau và text-shadow để tạo độ bóng cho chữ mà mình muốn.
    - Về javascript: thì em có sử dụng đối với banner em sẽ để 5 cái banner và sẽ đặt cho nó thời gian cứ 6s nó sẽ chuyển sang một cái banner khác
    - Tron div container em có đặt nút button có tên Top kết hợp với CSS và javascript sự kiện onclick khi cuộn chuột xuống 20px tính từ đầu trang thì nó sẽ hiện ra môt cái nút bấm để giúp người dụng hạn chế thời gian quay lại đầu khi cuộn chuột xuống sâu.  
    ![anh1](https://scontent.xx.fbcdn.net/v/t1.15752-0/p206x206/131894693_214955230158046_5112427218121865617_n.png?_nc_cat=103&ccb=2&_nc_sid=58c789&_nc_ohc=cE5jWzrwoRYAX-7c9B1&_nc_ad=z-m&_nc_cid=0&_nc_ht=scontent.xx&_nc_tp=30&oh=1df05cdc7564930f1cd001909dc2aac4&oe=60024463)
  2. Phần thứ hai:
    - Về HTML: em có sử dụng 1 thẻ div lớn có class content với width 90%, height 13150px, margin auto căn đều 2 bên bên trong e lại chia thành hai div là content-left và conten-right.Đổi với content-left để chứa ảnh với kịch thước khác nhau dưới mỗi cái ảnh sẽ là thẻ p để viết nội dung của cái ảnh đó em để width 69%, float left với content-right chứ thanh tìm kiếm ở trên đầu bên là 5 cái video em lấy trên youtube em để width 30% với float right để cho sang bên phải
    - Về CSS: mỗi cái ảnh bên phải em có để border-radius 10px để bo tròn 4 góc lại, Bên thẻ content-right em có sử dụng position sticky để khi kéo cuột xuống dưới khi nội dung bên phải thay đổi thì contet-right vẫn đứng im cho đến hết height 13150px.
  3. Phần thứ ba: là phần để người dung đăng ký email thì khi có nội dung mới thì thông tin sẽ được gửi đến email của người dùng giúp người dùng cập nhật nhanh hơn
    - Về HTML: gồm thẻ p, input và button có tên Đăng Ký
    - Về Javascript: để check xem người dùng đã nhập đúng email hay chưa khi người dùng nhấn vào nút đăng ký nếu vị trí của @ đặt sai thì nó sẽ báo lỗi email không hợp lệ
  4. Phần cuối cùng là footer
    - Về HTML: em có chia footer thành 2 phần ft-left và ft-right là bên trái và bên phải, bên trái là tên trang, bên phải dụng thẻ h3 với thẻ p để liệt kê một số ẩm thực và điểm đến nổi bật ở Hà Nội
 #### II.Trang Ẩm Thực
   ##### Bố cục Trang Ẩm thực cua em cũng chia thành 4 phần
   - Phần chứa menu
   - phần chứa nội dung gômg      
   - phàn đăng ký email
   - footer
   1. Phần đầu:
    - Về HTML: gồm thẻ h2 chứa tên trang và 2 để mục con
    - Về CSS : em có sử dụng một số font chữ và text-shadow làm bóng chữ
    - Về Javascrip thì cũng như trang chủ thì im cũng đặt nút button có tên Top kết hợp với css và javascript khi cuộn chuột xuống 20px thì nó sẽ hiện ra nút bấm để quay lại đầu trang
   2. Phần nội dung
    - Về HTML/CSS: em cia thành 4 thẻ div lớn với width 80% và margin auto căn đều 2 bên, bên trong thẻ div đầu tiên chứ ảnh và tên các món ăn em có sủ dụng phân trang thành 5 trang với 5 thẻ a link đến 5 trang amthuc1, amthuc2, amthuc3, amthuc4, amthuc5 css sử dụng display flex để dàn iteams. Div thứ 2 em chia thành 2 bên trái và phải ben trái có width 76%, height 870px bên phải width 23% . Div thứ 3 em cũng chia thành 2 bên trái và phải bên trái em chứa một số video trên youtobe bên có width 76% bên phải width 23%. Div thứ tư chứ một số ảnh và tên ảnh có sử dụng CSS display flex để dàn iteams.
   3. Phần đăng ký email
    - Về HTML: cũng giống như trang chủ gồm thẻ p, input và button
    - Về Javascript: để check xem người dùng đã nhập đúng email hay chưa khi người dùng nhấn vào nút đăng ký nếu vị trí của @ đặt sai thì nó sẽ báo lỗi email không hợp lệ
   4. Là footer
    - cũng giống như Trang chủ thì em có chia footer thành 2 phần ft-left và ft-right là bên trái và bên phải, bên trái là tên trang, bên phải dụng thẻ h3 với thẻ p để liệt kê một số ẩm thực và điểm đến nổi bật ở Hà Nội
    
    
    
    
    
  
