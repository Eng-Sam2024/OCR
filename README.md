# TaskFlow | انسياب المهام 🌊

<div align="center">

![TaskFlow Logo](https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/solid/list-check.svg)

**حوّل فوضى المهام إلى انسياب منظم وفعّال.**

</div>

<p align="center">
  <img alt="GitHub license" src="https://img.shields.io/badge/license-MIT-blue.svg">
  <img alt="GitHub stars" src="https://img.shields.io/github/stars/your-username/taskflow?style=social">
  <img alt="GitHub forks" src="https://img.shields.io/github/forks/your-username/taskflow?style=social">
</p>

---

**TaskFlow** هو تطبيق ويب حديث مصمم لمساعدة الأفراد والفرق الصغيرة على إدارة مهامهم ومشاريعهم بسلاسة. من خلال واجهة بسيطة وبديهية، يمكنك تتبع التقدم وتحديد المواعيد النهائية والتعاون مع فريقك بكل سهولة.

<br>

<div align="center">

![عرض حي لتطبيق TaskFlow](./docs/app_demo.gif)
*عرض توضيحي لواجهة المستخدم الرئيسية.*

</div>

---

<details>
  <summary>📚 **جدول المحتويات**</summary>
  <ol>
    <li><a href="#-الميزات-الرئيسية">الميزات الرئيسية</a></li>
    <li><a href="#-التقنيات-المستخدمة">التقنيات المستخدمة</a></li>
    <li><a href="#-التثبيت-والتشغيل">التثبيت والتشغيل</a></li>
    <li><a href="#-هيكلة-المشروع">هيكلة المشروع</a></li>
    <li><a href="#-كيفية-المساهمة">كيفية المساهمة</a></li>
    <li><a href="#-الترخيص">الترخيص</a></li>
    <li><a href="#-تواصل-معي">تواصل معي</a></li>
  </ol>
</details>

---

## ✨ الميزات الرئيسية

- **🎨 لوحات مهام مرئية:** نظّم مهامك باستخدام لوحات Kanban قابلة للسحب والإفلات.
- **📅 تحديد المواعيد النهائية:** أضف تواريخ استحقاق وتلقَّ إشعارات لتظل على المسار الصحيح.
- **👥 مصمم للفرق:** قم بدعوة أعضاء الفريق إلى مشاريعك وعيّن لهم المهام.
- **📊 تتبع التقدم:** رسوم بيانية بسيطة توضح لك نسبة إنجاز المشروع.
- **📱 تصميم متجاوب:** يعمل بسلاسة على أجهزة الكمبيوتر المكتبية والأجهزة اللوحية والهواتف المحمولة.
- **🔐 نظام مصادقة آمن:** تسجيل الدخول والخروج مع حماية بيانات المستخدم.

## 💻 التقنيات المستخدمة

تم بناء هذا المشروع باستخدام أحدث التقنيات لضمان أداء عالٍ وتجربة مستخدم ممتازة:

| الجزء | التقنية |
| :--- | :--- |
| **الواجهة الأمامية (Frontend)** | `React` `Vite` `Tailwind CSS` `Axios` |
| **الواجهة الخلفية (Backend)** | `Node.js` `Express.js` |
| **قاعدة البيانات (Database)** | `MongoDB` `Mongoose` |
| **المصادقة (Authentication)** | `JSON Web Tokens (JWT)` |

## 🚀 التثبيت والتشغيل

للحصول على نسخة محلية وتشغيلها، اتبع هذه الخطوات البسيطة.

### المتطلبات المسبقة

تأكد من أن لديك `Node.js` و `npm` و `Git` مثبتة على جهازك.

### خطوات التثبيت

1. **انسخ المستودع (Clone the repo):**
   ```sh
   git clone [https://github.com/your-username/taskflow.git](https://github.com/your-username/taskflow.git)
   cd taskflow
