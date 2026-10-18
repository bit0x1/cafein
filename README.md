# منوی کافه این

سایت تک‌فایلهٔ منو (فونت‌ها و عکس‌ها داخل خود فایل).

## ساختار
- `menu/index.html` → خود منو (این پوشه باعث می‌شه آدرس بشه `site.com/menu/`)
- `index.html` → صفحهٔ انتقال خودکار به `/menu/`

## بالا آوردن روی گیت‌هاب
1. مخزن جدید (Public، بدون README) بسازید.
2. داخل همین پوشه:
   git init
   git add .
   git commit -m "Cafein menu"
   git branch -M main
   git remote add origin https://github.com/USERNAME/cafein-menu.git
   git push -u origin main
3. Settings → Pages → Deploy from a branch → شاخهٔ main و `/ (root)` → Save.
4. آدرس: https://USERNAME.github.io/cafein-menu/menu/

## دامنهٔ اختصاصی
Settings → Pages → Custom domain دامنه را وارد کنید و در DNS یک CNAME به USERNAME.github.io بدهید → site.com/menu/
