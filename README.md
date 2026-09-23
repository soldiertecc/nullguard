<div dir="rtl">

# Null Guard

**مدير كلمات مرور لويندوز يعمل على جهازك فقط — لا يتصل بالإنترنت إطلاقًا.**

خزنة مشفّرة لكل حساباتك، تفتحها بكلمة مرور رئيسية واحدة أو بـ Windows Hello (بصمة / وجه / رمز PIN).

## أهم ما يميّزه

- **محلي بالكامل:** لا خوادم، ولا حسابات، ولا مزامنة سحابية.
- **تشفير قوي:** Argon2id لاشتقاق المفتاح + XChaCha20-Poly1305 للتشفير المُصادَق.
- **يسد تسريبات ويندوز:** كلمات المرور المنسوخة لا تدخل سجل الحافظة (Win+V) وتُمسح تلقائيًا، ومحتوى النافذة لا يظهر في لقطات الشاشة ولا في مشاركة الشاشة، ومفتاح الخزنة لا يُكتب على القرص.
- **يُقفل تلقائيًا** عند الخمول، وعند قفل الشاشة أو سكون الجهاز.
- **واجهة عربية وإنجليزية**، مع وضع ليلي ونهاري.

## التحميل والتثبيت

1. من صفحة [**Releases**](../../releases/latest) حمّل الملف `NullGuard_1.0.0_x64-setup.exe`.
2. انقر عليه نقرتين. إن ظهر تحذير SmartScreen: **More info** ← **Run anyway** (البرنامج غير موقّع بشهادة مدفوعة).
3. اضغط **Install**، وسيظهر البرنامج في قائمة ابدأ.

**المتطلبات:** ويندوز ١٠ (إصدار 2004 أو أحدث) أو ويندوز ١١.

> الخزنة لا تنتقل مع ملف التثبيت. لنقل حساباتك إلى جهاز آخر: الإعدادات ← تصدير، ثم استيراد على الجهاز الجديد.

</div>

---

# Null Guard (English)

An offline, zero-knowledge password manager for Windows. Your vault stays on your machine: no servers, no accounts, no cloud sync.

- Argon2id key derivation + XChaCha20-Poly1305 authenticated encryption
- Copied passwords are excluded from clipboard history and cloud clipboard, then auto-cleared
- Window content is excluded from screenshots and screen sharing
- Auto-lock on idle, screen lock and sleep; Windows Hello unlock
- Arabic and English UI, light and dark themes

**Download:** [latest release](../../releases/latest) · **Requires:** Windows 10 (2004+) or Windows 11
