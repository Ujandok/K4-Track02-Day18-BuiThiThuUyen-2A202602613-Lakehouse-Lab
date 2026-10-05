# Khai báo sử dụng AI

**Công cụ:** Claude Code 

## AI đã hỗ trợ

- Đọc README, CHECKPOINTS, RUBRIC, RULES, SUBMISSION và 8 notebook để lập thứ tự làm từ CP0 đến CP9.
- Chạy smoke test, sinh dữ liệu, pytest, `run_all.py` và thực thi 8 notebook bằng `nbconvert --execute`.
  Mọi số liệu đều lấy từ các lần chạy thật trên máy này.
- Soạn nháp các ô "🔎 Giải thích kết quả" trong notebook, cùng `INFO.md` và `REFLECTION.md`.

## Nguyên tắc đã giữ

- Không tạo output giả. Không hạ ngưỡng, không xóa hay nới lỏng assertion. Các thay đổi chỉ làm phép kiểm tra chặt hơn hoặc sửa phép đo sai, và đều kèm lý do.


## Trách nhiệm của người nộp

Người nộp rà soát lại mã đã sửa, các số liệu và phần giải thích, và phải tự giải thích được cơ chế đằng sau
mỗi kết quả (transaction log, file skipping, time travel, hidden partitioning, maintenance, vòng đời embedding, provenance).
