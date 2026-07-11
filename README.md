# 369 Fractal Lab

Web học cấu trúc 369 và backtest XAUUSD M15 dạng replay.

## Chức năng

- Biểu đồ nến XAUUSD M15 mô phỏng bằng Canvas.
- Replay từng nến, điều chỉnh tốc độ và timeline.
- Đặt lệnh BUY/SELL bằng nút hoặc phím `B` / `S`.
- Tự động tính SL, TP, P&L và win rate.
- Phân tích token `AB → BC → CD → D.E` và strength 369.
- Bài học về macro route, mid route, micro trigger và node memory.
- Nhật ký các lệnh backtest.

## Cấu trúc

- `worker/index.js`: toàn bộ HTML, CSS, JavaScript và Worker handler.
- `scripts/build.sh`: tạo artifact để triển khai lên ChatGPT Sites.
- `scripts/validate-artifact.mjs`: kiểm tra Worker export hợp lệ.
- `.openai/hosting.json`: liên kết project ChatGPT Sites.

## Kiểm tra

```bash
npm run build
npm run validate
```

Nội dung phục vụ học tập và nghiên cứu, không phải khuyến nghị đầu tư.
