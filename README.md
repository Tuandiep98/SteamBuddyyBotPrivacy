# Steam Buddy — public privacy texts

Thư mục này chỉ chứa **Chính sách bảo mật** (VI + EN) để đặt trong một **repository GitHub riêng, Public**. Repo code bot có thể giữ **Private**; user Telegram vẫn mở được link policy qua repo public.

## Việc cần làm (một lần)

1. Trên GitHub: **New repository** — ví dụ `SteamBuddyyBotPrivacy`, chọn **Public**, không cần README nếu bạn push từ máy.
2. Clone repo mới về máy, copy **toàn bộ nội dung thư mục `privacy-public/`** (các file `privacy-policy.*.md` và tùy chọn README này) vào **root** của repo đó.
3. Commit & push lên nhánh mặc định (thường `main`).
4. Trong `.env` của bot, đặt URL blob (đổi `OWNER` / `REPO` / `main` nếu khác):
   - `PRIVACY_POLICY_URL=https://github.com/OWNER/REPO/blob/main/privacy-policy.vi.md`
   - `PRIVACY_POLICY_URL_EN=https://github.com/OWNER/REPO/blob/main/privacy-policy.en.md`

## Đồng bộ khi sửa policy

Sửa file trong **`privacy-public/`** trên máy (bản trong monorepo steam-buddy), rồi copy lại sang clone của repo public và push — hoặc chỉnh trực tiếp trên repo public và định kỳ pull về monorepo nếu bạn muốn một nguồn.

## Repo đang dùng

`Tuandiep98/SteamBuddyyBotPrivacy` — khớp `.env.example` của dự án bot.
