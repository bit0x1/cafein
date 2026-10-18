# منوی کافه این

## ساختار
- `index.html`          → انتقال خودکار به /menu/
- `menu/index.html`     → منو (عکس‌ها را از پوشهٔ photos کنار خودش می‌خواند)
- `menu/photos/…`       → ۱۱۲ عکس با اسم انگلیسی

## آپلود بدون ترمینال (وب گیت‌هاب)
1. مخزن جدید Public بدون README بسازید.
2. Add file → Create new file → اسم: `menu/photos/.gitkeep` → Commit (پوشه‌ها ساخته می‌شوند).
3. ریشه: Add file → Upload files → `index.html` و `README.md` → Commit.
4. وارد پوشهٔ menu شوید: Add file → Upload files → `index.html` → Commit.
5. وارد menu/photos شوید: Add file → Upload files → همهٔ jpgها → Commit.
6. Settings → Pages → Deploy from a branch → main و / (root) → Save.
   آدرس: https://USERNAME.github.io/NAME/menu/
