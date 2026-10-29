<p align="center">
  <img src="docs/logo.png" width="110" alt="AEF Download Manager">
</p>

<h1 align="center">AEF Download Manager</h1>

<p align="center">
  برنامج تحميل لويندوز بفكرة IDM — سريع، بواجهة عربية وإنجليزية، وبيحدّث نفسه لوحده.<br>
  A fast IDM-style download manager for Windows — Arabic &amp; English UI, self-updating.
</p>

<p align="center">
  <a href="../../releases/latest"><b>⬇️ تحميل آخر إصدار / Download the latest version</b></a>
</p>

---

## التحميل والتثبيت

من صفحة **[Releases](../../releases/latest)** نزّل واحد من الملفات دي:

| الملف | الاستخدام |
|---|---|
| `AEF-Download-Manager-Setup-x.y.z.exe` | برنامج التثبيت: اختصارات على سطح المكتب وقائمة ابدأ، وإزالة من لوحة التحكم |
| `AEFDownloadManager.exe` | نسخة محمولة تشتغل على طول من غير تثبيت |
| `AEF-Firefox.xpi` | إضافة Firefox |

يشتغل على **Windows 10 / 11 (64-bit)**، ومش محتاج تثبّت أي حاجة تانية.

> لو ظهرت رسالة "Windows protected your PC" اضغط **More info ← Run anyway**. الرسالة دي بتظهر لأي برنامج جديد مش موقّع رقمياً.

## التحديثات

البرنامج بيدوّر على الإصدارات الجديدة هنا ويعرض عليك تحدّثه بضغطة واحدة. ولو حبيت تدوّر بنفسك: **Options ← Updates ← Check now**.
محرك تحميل الفيديو كمان بيحدّث نفسه تلقائياً.

## الخصائص

- **تسريع التحميل**: الملف بيتقسم لحد 32 اتصال في نفس الوقت، مع تقسيم ديناميكي زي IDM.
- **إيقاف واستكمال** حتى بعد ما تقفل البرنامج أو الجهاز، وإعادة محاولة ذكية لو النت فصل.
- **تحميل الفيديو من أي موقع**: يوتيوب وفيسبوك وإنستجرام وتيك توك و+1800 موقع. ولو الموقع مش معروف، البرنامج بيدوّر على الفيديو جوه الصفحة بنفسه. تقدر تختار الجودة لحد 4K أو MP3، وتنزّل قوائم تشغيل كاملة مع الترجمة.
- **زرار "Download this video"** بيظهر فوق أي فيديو في المتصفح.
- **VPN مدمج**: Cloudflare WARP مجاني بضغطة واحدة، أو ملف WireGuard / بروكسي خاص بيك. بيفتح المواقع المحجوبة للبرنامج وللمتصفح كمان.
- **تورنت وماجنت** مع اختيار الملفات اللي عايزها.
- **AEF للموبايل**: من أي موبايل (أندرويد أو آيفون) وعلى أي شبكة، تبعت رابط فيديو والكمبيوتر يحمّله.
- **تحويل وضغط وقص الفيديو**: MP4 / MP3 / M4A / WebM / GIF.
- **مشغّل ومعاينة** وهو لسه بيتحمل، وصور مصغرة للفيديوهات.
- **التحقق من الملف** (MD5 / SHA)، وفحص بـ Windows Defender بعد التحميل.
- قوائم انتظار وجدولة، محدد سرعة، مراقبة الحافظة، إحصائيات، نسخ احتياطي واستيراد، إشعارات ويندوز بأزرار.

## إضافة المتصفح

**Chrome / Edge / Brave / Opera**
1. من البرنامج: **Options ← Browser integration ← Install extension** (هيفتح مجلد الإضافة).
2. في المتصفح افتح `chrome://extensions` (أو `edge://extensions`) وفعّل **Developer mode**.
3. اضغط **Load unpacked** واختار مجلد `BrowserExtension`.

بعد كل تحديث للبرنامج ادخل نفس الصفحة واضغط زرار التحديث ↻ على إضافة AEF.

**Firefox**
افتح `about:debugging#/runtime/this-firefox` ← **Load Temporary Add-on…** واختار ملف `manifest.json` من مجلد `BrowserExtension-Firefox`.

## أسئلة شائعة

**الـ VPN مش بيغيّر بلدي؟**
WARP بيفتح المواقع المحجوبة بس بيفضل في مكان قريب منك. لو عايز دولة معيّنة ضيف ملف WireGuard من خدمة VPN (مثلاً Proton VPN المجاني).

**فيديو مش راضي يتحمل؟**
شغّل الفيديو في المتصفح واضغط "Download this video" اللي فوقه. ولو الموقع محجوب عندك، شغّل الـ VPN من البرنامج.

**الإعدادات والتحميلات بتتحفظ فين؟**
في `%APPDATA%\AEF Download Manager`.

## ادعم البرنامج ❤️

AEF مجاني. لو البرنامج بيفيدك وحابب تدعم تطويره، تقدر تتبرع بأي مبلغ، وده اختياري تماماً:

<p align="center">
  <a href="https://www.paypal.com/paypalme/ElsayedMohamed278"><b>💙 Donate with PayPal / تبرع عن طريق PayPal</b></a>
</p>

## الإبلاغ عن مشكلة

افتح **[Issue](../../issues/new)** واكتب المشكلة، ولو تقدر ضيف صورة. ملف الأخطاء موجود في `%APPDATA%\AEF Download Manager\error.log`.

---

<sub>© AEF — جميع الحقوق محفوظة. الكود المصدري غير متاح للعامة.<br>
All rights reserved. The source code is not public.</sub>
