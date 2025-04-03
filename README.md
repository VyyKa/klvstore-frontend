# KLV Email Viewer Frontend

Giao diện đơn giản để người dùng nhập email và xem thư gần nhất từ Gmail (thông qua n8n).

## 🚀 Cách deploy lên Vercel

1. Fork hoặc clone repo này.
2. Vào [https://vercel.com](https://vercel.com) → đăng nhập và kết nối GitHub.
3. Deploy project này.
4. Trỏ tên miền `klvstore.shop` về domain Vercel cấp.

## 🔗 API đang gọi đến

```bash
POST https://backup.eclatduteint.vn/webhook/get-email
```
