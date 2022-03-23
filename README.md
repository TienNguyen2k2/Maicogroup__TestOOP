# Phần mềm quản lý đơn hàng

> Cửa hàng bán các thiết bị điện gia dụng.

## Cơ sở dữ liệu

### Hóa đơn

- Tin mã sản phẩm

- Tin khách hàng

- 1 tập danh sách của các **_chi tiết hóa đơn_**

- Ngày lập hóa đơn

- Giá hóa đơn
  > Giá hóa đơn bằng tổng giá của tất cả sản phẩm tương ứng với số lượng bán ra của sản
  > phẩm đó

### Khách hàng

- Mã khách hàng

- Tên khách hàng

- Số điện thoại

- Địa chỉ

### Chi tiết hóa đơn

- Thông tin sản phẩm (Thiết bị điện gia dụng)

- Số lượng sản phẩm đó được bán ra trong hóa đơn

### Sản phẩm

- Mã sản phẩm

- Tên sản phẩm

- Giá bán

- Nơi sản xuất

#### Máy quạt (3 loại)

- Máy quạt đứng

  - Giá: 500

- Máy quạt hơi nước

  > Thêm thông số dung tích nước tối đa (lit)

  - Gía: dung tích \* 400

- Máy quạt sạc điện

  > Thêm thông số dung lượng của pin

  - Giá: dung lượng pin \* 500

#### Máy lạnh

> Thêm thuộc tính có hỗ trợ công nghệ inverter (Giá += 500)

- Máy lạnh 1 chiều

  - Giá: 1000

  - Inverter Giá += 500

- Máy lạnh 2 chiều

  - Giá: 2000

  - Inverter Giá += 500

  > Thêm thông số công nghệ khử mùi (Giá += 500)

  > Thêm thông số công nghệ kháng khuẩn (Giá += 500)

## Yêu cầu ứng dụng

- Chương trình chạy

- Áp dụng tốt tư tưởng lập trình hướng đối tượng

- Có tính mở rộng trong tương lai

- sử dụng được kĩ thuật _kế thừa_, _đa hình_, _nạp chồng_, _toán tử_,...
