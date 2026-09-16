# Aurora Sub — 3x-ui Subscription Page

A white-label custom subscription page for **3x-ui** panels — "Aurora Glass" design.
RTL-first, 4 languages (فارسی / English / 中文 / Русский), zero external branding.

- `sub.html` — drop-in subscription theme file (production)
- `demo.html` — rendered preview with fake data (open in a browser)

## Features
- 🌌 Aurora Glass design — animated aurora background, glass cards, dark + light themes
- 🎯 4 tabs: Home / Configs / Apps / Profile
- ⚡ Live search over configs (box appears when > 3 configs; JSON/Clash quick rows)
- 🌍 Visitor IP & geo card with protection-status banner and manual refresh
- 📢 Panel announce banner (auto-hidden when empty)
- 🟢 Online status dot in header (pulsing green = online)
- 📊 Usage ring, expiry countdown, upload/download stats
- 📱 QR codes generated locally in-page (no external QR service — no data leak)
- 🧩 IPv6-safe layout · iPhone safe-area · smooth scroll

## 3x-ui compatibility
- Works on 3x-ui v3.7+ (uses `announce` / `isOnline` when the panel provides them)
- On older panels (< v3.6.0) these fields don't exist → banner/dot auto-hide, no errors

## Install
1. Enable the custom subscription theme in your 3x-ui panel settings.
2. Point the sub theme directory (`subThemeDir`) to a folder containing `sub.html`.

---
## فارسی
صفحهٔ اشتراک سفارشی وایت‌لیبل برای پنل **3x-ui** با طراحی Aurora Glass.

- فایل اصلی: `sub.html` — پیش‌نمایش رندرشده: `demo.html`
- بدون هیچ نام/برند فروشنده و بدون دکمهٔ پشتیبانی یا تمدید — کاملاً وایت‌لیبل
- سرچ زندهٔ کانفیگ، کارت IP و موقعیت، بنر اعلان پنل، دات آنلاین هدر
- QR به‌صورت محلی داخل صفحه (بدون سرویس بیرونی)، ۴ زبان، راست‌چین
- روی پنل‌های قدیمی‌تر از 3.6.0 (بدون فیلدهای announce/isOnline) همه‌چیز بی‌خطا و خودکار مخفی می‌شود

**نصب:** در تنظیمات پنل 3x-ui قالب اشتراک سفارشی را فعال کن و پوشهٔ قالب (`subThemeDir`) را به پوشه‌ای که `sub.html` داخل آن است اشاره بده.
