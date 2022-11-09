# IUH4-KTPM-OnTapKTTH-WebService
IUH-KTPM-OnTapKTTH-WebService

## Các bước thực hiện
  - Tạo mới một ASP.NET Web Application
  - Trong cửa số Solution Explorer, nhấn chuột phải lên project, chọ Add => New Item . Tìm chọn mục Web Service (ASMX). Gõ tên ten.asmx
  - Chú ý mỗi phương thức mà ta muốn xem như một web-method thì ta phải đánh dấu attribute [WebMethod]
  - Chạy thử trên Microsoft Edge browser => Nhấn Service Description link => Copy URL này cho việc viết client
  - Tạo Windows Form Application
  - Nhấn phải chuột lên mục References của project, chọn “Add Service Reference..”
  - Dán uri đã copy vào
  - Nhấn nút Go, đặt Namespace lại thành CalcRef như hình trên. Sau đó nhấn OK
