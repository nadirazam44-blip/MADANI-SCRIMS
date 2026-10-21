MADANI SCRIMS - Android Studio Project

هذا مشروع Android مبدئي يعرض واجهة MADANI SCRIMS داخل WebView.
ليس ملف APK مبنيًا بعد.

طريقة بناء APK:
1. ثبّت Android Studio على كمبيوتر.
2. افتح Android Studio واختر Open ثم اختر مجلد MADANI_SCRIMS_Android.
3. وافق على تثبيت Android SDK / Build Tools المطلوبة إذا طلبها البرنامج.
4. انتظر انتهاء Gradle Sync.
5. اختر Build > Build Bundle(s) / APK(s) > Build APK(s).
6. ستجد الملف عادةً في app/build/outputs/apk/debug/app-debug.apk.

ملاحظات:
- يتطلب Android SDK وGradle لبناء APK؛ بيئة إعداد هذا الملف لا تحتوي على Android SDK/Gradle، لذلك لم أستطع إخراج APK فعلي هنا.
- هذه نسخة واجهة تجريبية. البيانات تُحفظ محليًا في WebView ولا تتم مزامنتها بين أجهزة مختلفة.
- قفل الإدارة في الواجهة ليس حماية إنتاجية؛ قبل نشر التطبيق يجب تنفيذ تسجيل دخول حقيقي وقواعد صلاحيات في الخادم/قاعدة البيانات.
- التطبيق يستخدم اتصالًا محليًا بملف HTML المضمّن ولا يحتاج إنترنت لتشغيل الواجهة.
