## Bước 1: Cài đặt dự án

1. Clone dự án về máy tính của bạn:
   ```bash
   git clone [https://github.com/USERNAME_CUA_BAN/challenge-1-decentralized-staking.git](https://github.com/USERNAME_CUA_BAN/challenge-1-decentralized-staking.git)
   cd challenge-1-decentralized-staking
Cài đặt các thư viện cần thiết:
  ```bash
  yarn install
```
### Bước 2: Chạy trên mạng Local (Máy cá nhân)
Sử dụng môi trường này để phát triển và kiểm thử nhanh mà không tốn phí gas thật. Bạn cần mở 3 cửa sổ Terminal riêng biệt:

Terminal 1: Khởi chạy mạng blockchain ảo
```bash
yarn chain
```
Terminal 2: Deploy Smart Contract lên mạng ảo
```bash
yarn deploy
```
Terminal 3: Chạy giao diện Web (Frontend)
```bash
yarn start
```
Sau đó truy cập trình duyệt tại: http://localhost:3000
