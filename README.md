# rea-kb

Kho tri thức công khai cho [rea-workflow](https://github.com/thaoht2109/rea-workflow): bản ghi đã làm sạch từ các case đã qua cổng phản biện (vân tay file và IOC; không có mẫu, đường dẫn máy hay tên case).

- Người dùng: `flow.py setup --yes` hoặc `flow.py kb update` tự kéo `manifest.json` ở repo này, kiểm sha256 rồi nhập vào kho cá nhân. Dữ liệu nhập chỉ là gợi ý, không phải fact.
- Người duy trì: `flow.py kb share add CASE`, rồi `flow.py kb publish --out <thư mục repo này>` sinh `rea-kb-<ngày>.jsonl.gz` và `manifest.json`.

Chưa có bản phát hành nào.
