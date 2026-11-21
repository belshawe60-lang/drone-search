# مساحة البحث عن الدرونات (Web App)

تطبيق ويب قابل للتثبيت (PWA). الملفات:
- index.html  — التطبيق كاملًا
- manifest.webmanifest — بيانات التثبيت
- sw.js — التخزين المؤقت للتشغيل السريع
- icon-180/192/512.png — الأيقونات

## النشر على GitHub Pages
1. أنشئ مستودعًا عامًا (Public) جديدًا.
2. Add file ← Upload files، ثم اسحب كل الملفات (وليس المجلد) إلى الجذر، ثم Commit changes.
3. Settings ← Pages ← Source: Deploy from a branch ← Branch: main / (root) ← Save.
4. بعد دقيقة أو دقيقتين يظهر الرابط: https://USERNAME.github.io/REPO/
5. iPhone: Safari ← مشاركة ← Add to Home Screen. Edge/Chrome: أيقونة التثبيت في شريط العنوان.

## التحديث
استبدل index.html في المستودع، وغيّر رقم النسخة dsa-v1 إلى dsa-v2 في sw.js.
