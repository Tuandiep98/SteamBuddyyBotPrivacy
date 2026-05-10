# Steam Buddy — public privacy texts

Thư mục này đồng bộ lên repo GitHub **Public** [Tuandiep98/SteamBuddyyBotPrivacy](https://github.com/Tuandiep98/SteamBuddyyBotPrivacy). Repo code bot có thể **Private**.

## Nội dung

- `privacy-policy.vi.md` / `privacy-policy.en.md` — nguồn chỉnh sửa.
- `docs/` — trang **HTML** tĩnh (GitHub Pages): `privacy-vi.html`, `privacy-en.html`, `index.html`, `.nojekyll`.

## Tạo lại HTML sau khi sửa `.md`

Từ root monorepo **steam-buddy**:

```bash
rtk uv run python scripts/build_privacy_html.py
```

Sau đó commit & push repo `SteamBuddyyBotPrivacy` (gồm cả `docs/`).

## GitHub Pages (một lần)

1. Repo → **Settings** → **Pages**.
2. **Build and deployment**: Source = **Deploy from a branch**, Branch = **main**, folder = **`/docs`**.
3. Sau vài phút, site: `https://tuandiep98.github.io/SteamBuddyyBotPrivacy/` (redirect tới bản VI).

## Biến môi trường bot (`.env`)

Dùng URL Pages (trang HTML), không dùng blob GitHub:

- `PRIVACY_POLICY_URL=https://tuandiep98.github.io/SteamBuddyyBotPrivacy/privacy-vi.html`
- `PRIVACY_POLICY_URL_EN=https://tuandiep98.github.io/SteamBuddyyBotPrivacy/privacy-en.html`

## Đồng bộ repo public

Push toàn bộ `privacy-public/` (gồm `docs/` đã build) lên nhánh `main` của `SteamBuddyyBotPrivacy`.
