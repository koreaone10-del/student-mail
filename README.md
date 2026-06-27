# 📧 Student Mail

بريد مؤقت ودائم للطلاب — تطبيق ويب من ملف واحد (HTML/CSS/JS) يعمل بالكامل من المتصفح دون أي خادم خلفي (backend)، ومستضاف مجاناً على GitHub Pages.

Temporary & disposable email for students — a single-file (HTML/CSS/JS) web app that runs entirely in the browser with no backend, hosted free on GitHub Pages.

## ✨ المميزات
- إنشاء بريد مؤقت فوري بنطاقات **حقيقية ومتعددة** (مدمجة من 3 مزودين: mail.tm + mail.gw + 1secmail)
- صندوق وارد تلقائي بتحديث كل 15 ثانية
- واجهة عربية/إنجليزية (RTL/LTR) بتصميم Cyberpunk غامق
- نسخة "Premium" مدفوعة عبر USDT (TRC20) — تحقق حقيقي من المعاملة على البلوكشين (بدون أي ثغرة تجاوز)
- حماية: تحديد معدل الطلبات، تعقيم المدخلات

## 🛠️ مبني على
- [mail.tm](https://mail.tm) و [mail.gw](https://mail.gw) — مزودا بريد مؤقت مجانيان (API متطابق، بدون مفتاح)
- [1secmail.com](https://www.1secmail.com) — مزود ثالث بنطاقاته الخاصة (لا يحتاج تسجيل حساب)
- TronScan / TronGrid — للتحقق الفعلي من معاملات USDT-TRC20 (بدون أي تجاوز/bypass)

## 📂 الملفات
| الملف | الوظيفة |
|---|---|
| `index.html` | الموقع الكامل |
| `sitemap.xml` | خريطة الموقع لمحركات البحث |
| `robots.txt` | تعليمات محركات البحث |
| `404.html` | صفحة الخطأ |
| `.nojekyll` | تعطيل معالجة Jekyll على GitHub Pages |

## 🚀 النشر
راجع [`DEPLOY_GUIDE.md`](./DEPLOY_GUIDE.md) لخطوات النشر الكاملة على GitHub Pages.

## ⚠️ ملاحظة
عدّل `CONFIG.WALLET_ADDRESS` ومعلومات التواصل في `index.html` قبل النشر.

---
**المطور:** غيّر هذا الاسم في `index.html` قبل النشر.
