# 🚀 DotNet-Deployer: Smart Linux & Plesk Deployment Generator

> A lightweight, interactive web tool to seamlessly configure, deploy, and hot-update **ASP.NET Core Web APIs** under Linux environment (Systemd & Nginx reverse proxy / Plesk).

---

## 🌟 Key Features
- **⚡ Smart Port Scanner:** Automatically finds and suggests the first available port (above `5000`) on your Linux server.
- **🔄 Fast Release & Hot-Reload Script:** A robust one-liner terminal command to apply updates, fix directory ownership, and restart services in less than 2 seconds.
- **🛡️ Clean Permissions Configurator:** Safely configures standard `www-data` user ownership to avoid runtime errors.
- **🔗 Auto Nginx Directives:** Ready-to-paste Nginx proxy blocks fully compatible with Plesk panel.

---

## 📝 How to Use
1. Open the tool (`index.html`) in any browser.
2. Fill out your project's settings (Domain, App Path, DLL entry point, etc.).
3. Run **Step 0** in your server terminal to dynamically identify an unoccupied port.
4. Apply the generated bash scripts sequentially.
5. Save the **Fast Publish** script for future hot-reload updates!

---

## 🗺️ Supported Languages / اللغات المدعومة / زبان‌ها
- **English** (Standard LTR)
- **العربية** (RTL - Cairo Font)
- **فارسی** (RTL - Vazir Font)
