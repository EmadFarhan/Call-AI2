# بناء APK عبر الإنترنت — Call AI

أضفنا سير عمل GitHub Actions لتجربة بناء نسخة Debug ورفع ملف APK الناتج كـ Artifact.

## الخطوات من الهاتف
1. افتح GitHub وأنشئ مستودعاً جديداً (Repository) باسم `Call-AI`.
2. ارفع ملفات المشروع ومجلد `.github/workflows/android.yml` إلى المستودع، مع الحفاظ على بنية المجلدات.
3. افتح تبويب **Actions** واسمح بتشغيل workflows إذا طُلب منك.
4. اختر **Build Call AI APK** ثم **Run workflow**.
5. إذا انتهى التشغيل باللون الأخضر، افتح نتيجة التشغيل وانزل إلى **Artifacts** وحمّل `Call-AI-debug-apk`.
6. فك ضغط ملف الـArtifact على الهاتف؛ داخله `app-debug.apk`. ثبّته بعد مراجعة الأذونات.
