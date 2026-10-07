# LIFE POV — MY LIFE, MY CHOICES
Mô phỏng đời sống 2D (SVG) tối ưu điện thoại. Node.js + HTML/CSS/JS thuần.

## Chạy thử
`npm install && npm start` → http://localhost:3000

## Deploy Render (bằng điện thoại)
1. Tạo repo GitHub, upload toàn bộ thư mục (web GitHub → Add file → Upload files).
2. render.com → New → Web Service → chọn repo.
3. Build Command: `npm install` — Start Command: `npm start`
4. Environment: `NODE_ENV=production`, `AI_API_KEY` (tùy chọn, Anthropic), `DATABASE_URL` (tùy chọn, PostgreSQL Render). Không cần đặt PORT, Render tự cấp.
5. Deploy, mở link.

Không có DATABASE_URL: save lưu file (mất khi Render restart) + localStorage trên máy. Không có AI_API_KEY: IDEA BOX dùng bộ luật có sẵn.
