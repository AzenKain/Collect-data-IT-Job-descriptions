
# Dự Án chỉ mang tính chất nghiên cứu không bất kì mục đích thương mại nào!

# Dự Án Thu Thập và Xử Lý Dữ Liệu Tuyển Dụng Ngành IT

## Giới Thiệu
Dự án này nhằm mục đích thu thập và xử lý dữ liệu tuyển dụng liên quan đến ngành IT từ Top CV. Chúng tôi sử dụng các kỹ thuật thu thập dữ liệu web để lấy thông tin tuyển dụng và tiến hành phân tích, xử lý dữ liệu để tạo ra các báo cáo chi tiết về thị trường việc làm trong ngành IT.

## Công Nghệ Sử Dụng
- Python
- BeautifulSoup
- Selenium
- Docker
- Docker Compose
- Undetected-Driver
- Stealth
- Flareresolver

## Cài Đặt

### Clone Repository
```bash
git clone https://github.com/yourusername/your-repo.git
cd your-repo


### Cài Đặt Docker
Đảm bảo rằng bạn đã cài đặt Docker và Docker Compose trên máy tính của mình. Nếu chưa, bạn có thể tham khảo [tài liệu chính thức của Docker](https://docs.docker.com/get-docker/) để cài đặt.

## Chạy Dự Án

Để chạy dự án, bạn có thể sử dụng lệnh sau:

```bash
docker-compose up --build
```

### Lưu Ý
- **Flareresolver**: Đây là một công cụ tuyệt vời cho việc xử lý dữ liệu. Tuy nhiên, nó có thể chiếm một lượng lớn dung lượng ổ cứng. Khi bạn hoàn tất việc thu thập và xử lý dữ liệu, hãy xóa container của `flareresolver` để giải phóng không gian.

```bash
docker-compose down
docker volume rm flareresolver  
```
