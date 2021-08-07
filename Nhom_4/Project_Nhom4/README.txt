*Thông tin nhóm
Nhóm 4
Lâm Thị Hoài Thanh - K184060802
Nguyễn Phạm Thủy Tiên - K184060809
Ngô Hữu Tài - K184060801
Trần Khánh Duy - K184060780

------------------------------------------------------------------------------
*Thông tin chương trình
Chương trình được viết và biên dịch trên nền tảng của Google Colab. Đồng thời có
sử dụng bộ thư viện Sklearn của Python.

------------------------------------------------------------------------------
*Cách biên dịch chương trình
Bước 1: Truy cập vào trang: https://colab.research.google.com
Bước 2: Trong cửa sổ hiện lên chọn mục Upload, và bỏ file Nhom4.ipynb
Bước 3: Nhấn tổ hợp Ctrl + F9, hoặc vào Runtime -> Run all
Bước 4 (Nếu có): Đối với lần đầu chạy GG Colab, tại phần code đầu tiên sẽ nhận được
		một đường link để nhận mã xác thực từ Google. Truy cập vào đường link,
		đăng nhập vào tài khoản google, và lấy mã xác thực bỏ vào khung trống.
		Sau đó, nhấn Enter.
Bước 5: Tại phần code đọc file dữ liệu sẽ hiện nút để chọn file. Nhấn vào và chọn file
	'online_shoppers_intention.csv' đính kèm trong thư mục.
Bước 6: Thưởng thức thành quả.

-------------------------------------------------------------------------------
*Phần mềm vẫn có thể hỗ trợ chạy các file dữ liệu khác, nhưng cần bạn thay đổi code
tại mục #Đọc file dữ liệu. Chép dòng sau với ABC là tên file dữ liệu.

from google.colab import files
uploaded = files.upload()
import io
df = pd.read_csv(io.BytesIO(uploaded['ABC']))