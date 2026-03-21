# 🎬 JF Video Autoplay Plugin

<p align="center">
  <img src="https://github.com/General-c4/JF-Video-Autoplay-Releases/blob/main/Image/logo-JF.png" width="200"/>
</p>

<p align="center">
🔥 Install directly in Jellyfin using the repository below
</p>

---

## 🔗 Plugin Repository (Direct Install) | التثبيت المباشر

📥 أضف الرابط التالي داخل Jellyfin لتثبيت الإضافة مباشرة:

```
https://raw.githubusercontent.com/General-c4/JF-Video-Autoplay-Releases/main/manifest.json
```

### 📍 المسار:

```
Dashboard → Plugins → Repositories → Add
```

---

## 🌍 Description | الوصف

### 🇺🇸 English

JF Video Autoplay Plugin adds a **cinematic hero section** to your Jellyfin home page that automatically plays trailers for the latest movies and TV shows.

It enhances the browsing experience with dynamic visuals, smooth playback, and intelligent performance optimizations.

---

### 🇸🇦 العربية

إضافة **JF Video Autoplay** تضيف قسم سينمائي (Hero) في الصفحة الرئيسية لـ Jellyfin يقوم بتشغيل التريلرات تلقائيًا لأحدث الأفلام والمسلسلات.

توفر تجربة تصفح احترافية مع عرض ديناميكي، تشغيل سلس، وتحسينات ذكية للأداء.

---

## 🖼️ Preview | معاينة

<p align="center">
  <img src="https://raw.githubusercontent.com/General-c4/JF-Video-Autoplay-Releases/main/Image/Background.png"/>
</p>

---

## ✨ Features | المميزات

### 🎥 Playback

* Auto-playing trailers (Muted autoplay)
* Supports YouTube, Vimeo, and direct video (mp4, webm, m3u8)
* Smart fallback if video is not supported
* Auto pause/resume using IntersectionObserver

### 🔊 Audio

* Starts muted (mobile compatibility)
* Unmute on first interaction
* Saves volume & mute state (LocalStorage)

### 🎬 UI / UX

* Cinematic full-width hero section
* Toggle between Movies & TV Shows
* Fast switching via logo thumbnails
* Displays logos, metadata, and details
* Fully responsive (Desktop / Mobile / TV)

### ⚡ Performance & Stability

* API retry system (with backoff)
* Prevent duplicate rendering (SPA safe)
* Lazy loading & prefetch for images
* Works across WebViews and different browsers

---

### 🇸🇦 المميزات بالعربي

### 🎥 التشغيل

* تشغيل تلقائي للتريلرات (بدون صوت بالبداية)
* دعم YouTube و Vimeo وروابط مباشرة
* fallback تلقائي عند عدم دعم الفيديو
* إيقاف/تشغيل ذكي حسب الظهور في الشاشة

### 🔊 الصوت

* يبدأ مكتوم (متوافق مع الجوال)
* تفعيل الصوت عند أول تفاعل
* حفظ مستوى الصوت بين الجلسات

### 🎬 الواجهة

* واجهة سينمائية بعرض كامل
* التبديل بين الأفلام والمسلسلات
* شريط شعارات للتنقل السريع
* عرض معلومات العمل بشكل جذاب
* متجاوب مع جميع الأجهزة

### ⚡ الأداء

* إعادة محاولة تلقائية للطلبات
* منع التكرار داخل الواجهة
* تحميل مسبق للصور
* يعمل على جميع المتصفحات

---

## 🚀 Installation | التثبيت

### 🟢 الطريقة السريعة (من داخل Jellyfin)

1. اذهب إلى:

```
Dashboard → Plugins → Repositories
```

2. أضف رابط الـ manifest
3. ثبّت الإضافة مباشرة

---

### 🔵 الطريقة اليدوية

1. Download the latest version from **Releases**
2. Move the file to:

```
/plugins/VideoAutoplay/
```

3. Restart Jellyfin

---

## ⚙️ Configuration | الإعدادات

* Go to:

```
Dashboard → Plugins → Video Autoplay
```

* Customize:

  * Library detection (AltTitles)
  * Max items per type
  * Script injection

---

## 📦 Download | التحميل

👉 من تبويب **Releases**

---

## ⚠️ Note | ملاحظة

* This repository contains **compiled releases only**
* Source code is not included
* Plugin starts muted due to browser autoplay policies

---

## ❤️ Support

If you like the plugin, consider giving it a ⭐

---
