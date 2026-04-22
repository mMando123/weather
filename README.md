# موقع تغير المناخ

تم تجهيز هذا المشروع ليعمل كموقع ثابت على GitHub Pages.

## ملفات المشروع

- `index.html` (الصفحة الرئيسية التي يعتمد عليها GitHub Pages)
- `climate-change-website.html` (نسخة الملف الأصلي)
- `.github/workflows/deploy-pages.yml` (نشر تلقائي للموقع)

## طريقة النشر على GitHub Pages

1. أنشئ مستودع جديد على GitHub وارفع هذه الملفات على فرع `main`.
2. افتح `Settings` ثم `Pages` داخل المستودع.
3. تأكد أن مصدر النشر هو **GitHub Actions**.
4. افتح تبويب `Actions` وانتظر انتهاء Workflow باسم **Deploy Static Site to GitHub Pages**.
5. رابط موقعك سيكون:
   - `https://<your-username>.github.io/<repo-name>/`

## تشغيل محلي

يمكنك فتح `index.html` مباشرة في المتصفح أو تشغيله عبر أي Local Static Server.
