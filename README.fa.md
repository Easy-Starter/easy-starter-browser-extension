<div dir="rtl" align="right">

<div align="center">

# استارتر افزونه مرورگر

**پایه‌ی Cross-browser با Extension.js برای افزونه‌های Chrome، Edge و Firefox با React و TypeScript.**

[![Use this template](https://img.shields.io/badge/Use%20this%20template-2ea44f?logo=github&logoColor=white)](https://github.com/easy-starter/easy-starter-browser-extension/generate) [![CI](https://github.com/easy-starter/easy-starter-browser-extension/actions/workflows/ci.yml/badge.svg)](https://github.com/easy-starter/easy-starter-browser-extension/actions/workflows/ci.yml) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) ![Status: foundation](https://img.shields.io/badge/status-foundation-orange) ![Extension.js](https://img.shields.io/badge/Extension.js-5B21B6) ![React](https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=black) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white) ![Cross-browser](https://img.shields.io/badge/Cross--browser-2ea44f)

[مستندات](https://github.com/easy-starter/easy-starter-docs) · [گزارش مشکل](https://github.com/easy-starter/easy-starter-browser-extension/issues/new/choose)

</div>

> [!IMPORTANT]
> این ریپوزیتوری در مرحله‌ی **Foundation** است. تا انتشار اولین نسخه‌ی پایدار، آن را Production-ready در نظر نگیرید.

## چه مشکلی را حل می‌کند؟

یک معماری و ورک‌فلوی Build واحد برای سطوح افزونه، Permission، پیام‌رسانی، Storage، تست و بسته‌های آماده‌ی انتشار فراهم می‌کند.

## این تمپلیت برای چه پروژه‌هایی مناسب است؟

- افزونه‌های Popup، Options، Side Panel و New Tab
- بهبود صفحات با Content Script
- افزونه‌های بهره‌وری و دستیار AI
- انتشار Chrome، Edge و Firefox از یک پروژه

**مناسب این موارد نیست:** برای وب‌سایت عادی یا افزونه‌ای که به اپلیکیشن Native نامرتبط نیاز دارد مناسب نیست.

## امکانات پایه

- Extension.js، React و TypeScript
- مرزهای Background، Content، Popup، Options و Shared
- قرارداد حداقل Permission و پیام‌رسانی امن
- فرمان‌های توسعه و بسته‌بندی مخصوص مرورگر
- تست، CI، انتشار و چک‌لیست Store Submission

توضیحات جزئی معماری، قراردادها، پروفایل‌های استقرار و روش توسعه در [`docs/`](docs/) قرار می‌گیرند. توسعه‌ی فیچر از [`specs/`](specs/) شروع می‌شود و قوانین ایجنت‌ها در [`AGENTS.md`](AGENTS.md) نگهداری می‌شوند.

## شروع سریع

۱. روی **Use this template** بزنید یا فرمان زیر را اجرا کنید:

```bash
gh repo create my-project --template easy-starter/easy-starter-browser-extension --private --clone
cd my-project
```

۲. نام پروژه، متادیتای پکیج و متغیرهای محیطی را تنظیم کنید.
۳. پروژه را اجرا کنید:

```bash
cp .env.example .env.local
make setup
make dev
make check
```

۴. اولین مشخصات فیچر را در `specs/` بنویسید.
۵. فیچر را پیاده‌سازی کنید و `make check` را سبز نگه دارید.

## قرارداد همکاری

- قبل از تغییر کد، `AGENTS.md` و Spec مرتبط را بخوانید.
- پیش از افزودن Abstraction یا Dependency جدید، از الگوهای موجود استفاده کنید.
- Credential یا داده‌ی واقعی پروداکشن را Commit نکنید.
- پیش از Pull Request تمام Quality Checkهای ریپو را اجرا کنید.
- تصمیم‌های معماری را در `docs/decisions/` ثبت کنید.

## مستندات

از `docs/getting-started.md` شروع کنید. راهنمای کامل‌تر توسعه‌ی AI-first در [Easy Starter Docs](https://github.com/easy-starter/easy-starter-docs) نگهداری می‌شود.

## مشارکت و پشتیبانی

قوانین مشارکت در [`CONTRIBUTING.md`](CONTRIBUTING.md)، روش دریافت کمک در [`SUPPORT.md`](SUPPORT.md) و گزارش مسائل امنیتی در [`SECURITY.md`](SECURITY.md) قرار دارد.

## مجوز

این پروژه تحت [مجوز MIT](LICENSE) منتشر می‌شود.

</div>
