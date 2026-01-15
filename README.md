# Smart Geometry Drawing V2 (MVP)

Đây là bản MVP chạy local (Vite + React + TypeScript) để bạn test nhanh trên Codex / máy tính.

## Tính năng đã có (đúng bài bạn đưa)
- Dán đề (có LaTeX) vào ô **Nội dung bài toán** → bấm **Xử lý & Vẽ**
- App tự chuẩn hóa LaTeX (\sqrt{}, \widehat{}, \text{}, ^\circ …)
- Dựng hình theo công thức tọa độ cho bài:
  - O(0,0), A(-R,0), B(R,0)
  - M nằm giữa O và A
  - Dây CD qua M, CM=√56, DM=12, ∠AMC=45°
  - Tính được R=10 và vẽ đầy đủ: C, D, dây CD, OC, OD, góc 45°, nhãn CM/DM
- Click vào “DỮ KIỆN TRÍCH XUẤT” hoặc “CHI TIẾT THỰC HIỆN” để highlight đối tượng
- Pan/Zoom, grid, độ dày nét, nét đứt, màu
- Export PNG/PDF/WORD (WORD dạng .doc HTML mở bằng Word)

## Chạy dự án
```bash
npm install
npm run dev
```
Mở: http://localhost:5173

## Ghi chú
- Nút “Tải ảnh” hiện chưa OCR (MVP). Bạn vẫn test được bằng cách dán đề vào textarea.
