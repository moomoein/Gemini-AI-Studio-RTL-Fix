# Gemini & AI Studio RTL Fix – Firefox & Chrome Extension

<p align="center">
  <img src="https://addons.mozilla.org/user-media/addon_icons/2919/2919442-64.png" alt="Extension Icon" width="128">
</p>

<p align="center">
  افزونه‌ای برای فایرفاکس و گوگل کروم جهت بهبود تجربه کاربری فارسی در سایت‌های Gemini و AI Studio گوگل.
  <br>
  A Firefox add-on to improve the Persian user experience on Google's Gemini & AI Studio.
</p>

<p align="center">
  <a href="https://addons.mozilla.org/en-US/firefox/addon/gemini-ai-studio-rtl-fix/">
    <img src="https://img.shields.io/amo/v/gemini-ai-studio-rtl-fix.svg?style=for-the-badge" alt="AMO Version">
  </a>

</p>

---

## مشکل چیست؟ (The Problem)

استفاده از ابزارهای هوش مصنوعی گوگل مانند Gemini و AI Studio برای کاربران فارسی‌زبان به دلیل چپ‌چین بودن (LTR) محیط چت، دشوار و ناخواناست. این افزونه با هدف حل این مشکل طراحی شده است.

## ✨ ویژگی‌ها (Features)

*   **راست‌چین‌سازی کامل**: محیط ورود متن، پیام‌های شما و پاسخ‌های هوش مصنوعی به صورت کامل راست‌چین (RTL) می‌شوند.
*   **فونت خوانا و زیبا**: فونت استاندارد و محبوب وزیرمتن (Vazirmatn) برای تمام متون فارسی اعمال می‌شود.
*   **سبک و سریع**: فقط با استفاده از CSS و بدون هیچ کد جاوااسکریپتی، تاثیری بر سرعت سایت‌ها ندارد.
*   **امن و خصوصی**: این افزونه هیچ‌گونه اطلاعاتی را جمع‌آوری یا ارسال نمی‌کند. کد منبع آن برای بررسی در دسترس همگان است.

## 🚀 نصب (Installation)

می‌توانید این افزونه را مستقیماً از فروشگاه افزونه‌های فایرفاکس نصب کنید:

**[Install from Mozilla Add-ons (AMO)](https://addons.mozilla.org/en-US/firefox/addon/gemini-ai-studio-rtl-fix/)**

---

همچنین برای نصب این افزونه برای Chrome به این صورت اقدام کنید:


1. Download or clone this repository.
2. Go to `chrome://extensions/` in your Chrome browser.
3. Enable “Developer Mode” (top-right).
4. Click “Load unpacked”.
5. Select the folder: `chrome-extension`



The extension will now be active on:
- [gemini.google.com](https://gemini.google.com)
- [aistudio.google.com](https://aistudio.google.com)

## 📸 تصاویر (Screenshots)
<table align="center">
  <tr>
    <td align="center"><strong>قبل (Before)</strong></td>
    <td align="center"><strong>بعد (After)</strong></td>
  </tr>
  <tr>
    <td>
      <img src="before-screenshot.png" alt="Before installing the add-on" width="100%">
    </td>
    <td>
      <img src="after-screenshot.png" alt="After installing the add-on" width="100%">
    </td>
  </tr>
</table>


## 📁 Folder Structure

├── chrome-extension/ # Chrome version of the extension
│ ├── manifest.json
│ ├── styles.css
│ └── fonts/
├── manifest.json # Firefox version
├── styles.css # Firefox stylesheet
├── README.md
└── ...


## 📜 مجوز (License)

این پروژه تحت مجوز [MIT License](LICENSE) منتشر شده است.
