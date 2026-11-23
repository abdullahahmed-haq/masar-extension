# مسار — إضافة لتنظيم التعلّم على يوتيوب

مسار إضافة مجانية لمتصفح Chrome على الكمبيوتر، تساعدك على تنظيم قوائم يوتيوب في مكتبة وكورسات، ومتابعة التقدم، وإضافة ملاحظات ومراجعات، وحظر القنوات. تدعم العربية والإنجليزية.

## التحميل

[حمّل أحدث إصدار من مسار](https://github.com/abdullahahmed-haq/masar-extension/releases/latest/download/masar-v1.0.39.zip) — الإصدار 1.0.39.

يمكنك أيضًا فتح [صفحة الإصدارات](https://github.com/abdullahahmed-haq/masar-extension/releases) واختيار ملف `masar-v1.0.39.zip` من قسم Assets. هذا المستودع مخصص لتوزيع النسخة الجاهزة.

## التثبيت على Chrome

1. حمّل ملف ZIP وفك الضغط عنه في مجلد دائم على جهازك. لا تحذف المجلد بعد التثبيت.
2. افتح `chrome://extensions` في Chrome على الكمبيوتر.
3. فعّل **وضع المطوّر / Developer mode**.
4. اضغط **تحميل إضافة غير مضغوطة / Load unpacked** واختر المجلد الذي يحتوي على ملف `manifest.json` مباشرةً، وليس ملف ZIP.
5. ثبّت أيقونة مسار من قائمة الإضافات، وحدّث صفحات يوتيوب المفتوحة.

الإضافة تعمل على `www.youtube.com` وتتطلب Chrome 120 أو أحدث. قد يعرض Chrome تنبيهًا بشأن الإضافات في وضع المطوّر، وقد تمنع إعدادات أجهزة العمل أو المدرسة تحميلها. [تعليمات Chrome الرسمية للتحميل غير المضغوط](https://developer.chrome.com/docs/extensions/get-started/tutorial/hello-world#load-unpacked).

## التحديث والبيانات

التحديث يدوي: صدّر نسخة احتياطية من إعدادات مسار أولًا، ثم حمّل الإصدار الجديد وفك ملفاته في **المجلد نفسه** الذي اخترته عند التثبيت، واستبدل الملفات القديمة، واضغط **إعادة تحميل / Reload** على بطاقة الإضافة في `chrome://extensions`، ثم حدّث يوتيوب. لا تزل الإضافة أو تنقل مجلدها قبل أخذ نسخة احتياطية؛ فقد يؤدي ذلك إلى فقدان البيانات المحلية أو تحميلها كإضافة منفصلة. إصدارات GitHub لا تتحدث تلقائيًا عبر متجر Chrome.

تُحفظ المكتبة والتقدم والإعدادات محليًا في المتصفح. يمكنك تصدير نسخة احتياطية واستعادتها من إعدادات الإضافة. تستخدم الإضافة يوتيوب لعرض المحتوى وقراءة بيانات الفيديو والقوائم عند الحاجة؛ وقد تتضمن روابط التنقل سياق الكورس أو المسار المحلي. تُحذف البيانات المحلية عند إزالة الإضافة أو حذف بيانات ملف المتصفح، لذا احتفظ بنسخة احتياطية.

## التحقق من الملف

بصمة SHA-256 للملف `masar-v1.0.39.zip`:

```text
46468350c130f6f4865c336db1f728786e7adb08ee11982f1f552769090ec116
```

## English

Download the ZIP from [Releases](https://github.com/abdullahahmed-haq/masar-extension/releases), extract it to a permanent folder, open `chrome://extensions`, enable Developer mode, choose **Load unpacked**, and select the folder containing `manifest.json`. Pin Masar and refresh YouTube. Updates are manual: back up your data, replace the files in the same folder, and reload the extension. Chrome 120 or later on desktop is required.
