**Thông tin sinh viên:**
- **Họ và tên:** Nguyễn Tuấn Kiệt
- **MSSV:** 22120173

---

## 1. Giới thiệu chung

Repo này là nơi tổng hợp các bài giải cho 6 challenges đầu tiên của speedrunethereum.

Vì các thư mục code gốc khá nặng nên em đã tách riêng mỗi challenge thành một repo độc lập. Repo này đóng vai trò là mục lục dẫn đến các bài làm chi tiết.

---

## 2. Danh sách bài làm

Dưới đây là liên kết đến Source Code của từng Challenge:

| STT | Tên Challenge | Link Repository
|:---:|:---|:---|
| 1 | **Decentralized Staking** | https://github.com/hmm0214/challenge1
| 2 | **Token Vendor** | https://github.com/hmm0214/challenge2
| 3 | **Dice Game** | https://github.com/hmm0214/challenge3
| 4 | **Build a DEX** | https://github.com/hmm0214/challenge4
| 5 | **Over-Collateralized Lending** | https://github.com/hmm0214/challenge5
| 6 | **Stablecoins** | https://github.com/hmm0214/challenge6

---

## 3. Hướng dẫn chạy

Giảng viên vui lòng truy cập vào từng đường link ở bảng trên để xem mã nguồn chi tiết. Quy trình chạy cho mỗi bài như sau:

**Bước 1:** Clone Repository về máy
```bash
git clone [link_repo]
cd [ten_thu_muc]

```

**Bước 2:** Cài đặt thư viện

```bash
yarn install

```

**Bước 3:** Khởi chạy mạng blockchain ảo ở terminal 1

```bash
yarn chain

```

**Bước 4:** Deploy Smart Contract ở terminal 2

```bash
yarn deploy --reset

```

**Bước 5:** Khởi chạy Frontend ở terminal 3

```bash
yarn start

```

Truy cập trình duyệt tại: `http://localhost:3000`
