# موقع الكاتب عبدالله شاهين — نسخة GitHub Pages

موقع ثابت بدون قاعدة بيانات. الأعمال متخزنة في `works.json` والصور في `images/`.

## الرفع على GitHub
1. أنشئ ريبو جديد (Public) على GitHub، مثلاً باسم `abdullah-shahin`.
2. ارفع كل محتويات هذا المجلد (index.html و admin.html و works.json و images و .nojekyll).
3. من Settings ثم Pages: اختر Deploy from a branch، الفرع main، المجلد root، ثم Save.
4. بعد دقيقة الموقع يشتغل على: https://USERNAME.github.io/REPO/

## تفعيل لوحة التحكم (مرة واحدة)
1. من GitHub: Settings ثم Developer settings ثم Personal access tokens ثم Fine-grained tokens ثم Generate new token.
2. Repository access: Only select repositories واختر الريبو ده فقط.
3. Permissions ثم Repository permissions ثم Contents: Read and write.
4. اختر مدة صلاحية مناسبة، ثم Generate وانسخ المفتاح.
5. افتح https://USERNAME.github.io/REPO/admin.html والصق المفتاح. الحساب والريبو بيتعبوا تلقائياً. المفتاح بيتحفظ على جهازك فقط.

## الاستخدام
- أضف أو عدّل أو احذف الأعمال، وارفع الأغلفة، وغيّر رقم واتساب الطلبات من لوحة التحكم.
- كل حفظ بيعدل `works.json` في الريبو والموقع يتحدث خلال دقيقة تقريباً.
- زر "اشترِ عبر واتساب" بيفتح محادثة على الرقم المحدد برسالة جاهزة فيها اسم العمل وسعره.

## ملاحظات أمان
- لا تشارك المفتاح مع أحد. لو ضاع الجهاز، احذف المفتاح من GitHub وأنشئ غيره.
- صفحة admin.html ظاهرة لمن يعرف رابطها، لكن بدون المفتاح لا يمكن الحفظ.
