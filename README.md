## Thư viện chính

> iuh-thuc-hanh

## Các thư viện khác

> Ở trong folder `other libraries`

## Hướng dẫn

### Tải về

*Yêu cầu máy tính phải cài đặt git*
- Chạy dòng lệnh bên dưới trong cmd tại folder muốn lưu thư viện
```bash
git clone --recurse-submodules https://github.com/nhthai173/altium-lib
```
- Kiểm tra cập nhật thư viện bằng dòng lệnh sau
```bash
git pull
```

### Cài đặt thư viện
- Mở file `.IntLib` trong folder `Project Outputs`
- Chọn **Install**
![Alt text](./images/README/image.png)

*Một số thư viện sẽ không có file `.IntLib` vì giới hạn dụng lượng của github.*

*Giải pháp: Mở file `.LibPkg` trong Altium, sau đó chuột phải, chọn **Compile***

### Cập nhật thư viện
- Mở file `.LibPkg`
- Chuột phải vào thư viện viện và chọn **Compile**
![Alt text](./images/README/image1.png)
- Đợi một lúc để Altium compile thư viện, thư viện đã được cập nhật

### Mở và chỉnh sửa thư viện
- Mở file `.LibPkg`
- Sửa thư viện nguyên lý ở file `.SchLib`
- Sửa thư viện PCB ở file `.PcbLib` 
- Compile thư viện bằng cách chuột phải vào thư viện và chọn **Compile**
![Alt text](./images/README/image1.png)