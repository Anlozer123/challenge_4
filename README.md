# 🚩 Challenge 4: Build a DEX ⚖️

Dự án này là giải pháp cho Challenge 4: Build a DEX của SpeedRunEthereum. Nó bao gồm một sàn giao dịch phi tập trung (DEX) đơn giản cho phép swap giữa ETH và token Balloons ($BAL), cung cấp thanh khoản, và tính phí giao dịch 0.3%.

## 🌟 Tính năng
- **Init:** Khởi tạo thanh khoản ban đầu cho sàn.
- **Price:** Tính toán giá token dựa trên công thức Constant Product Formula (x * y = k).
- **Swap:** Đổi ETH sang Token và ngược lại.
- **Liquidity:** Nạp (Deposit) và Rút (Withdraw) thanh khoản để nhận phí giao dịch.

## 🛠 Cài đặt và Chạy dự án

Yêu cầu: [Node.js](https://nodejs.org/) (>= v20.18.3) và [Yarn](https://yarnpkg.com/).

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
