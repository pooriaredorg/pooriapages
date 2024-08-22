> **[🇬🇧English](README.md)**
>
>  **[🇮🇷فارسی](README-fa.md)**

<p align="center">
  <img src="docs/assets/images/Panel.jpg">
</p>

<p align="center">
  <img src="docs/assets/images/Panel-2.jpg">
</p>

<p align="center">
  <img src="docs/assets/images/Panel-3.jpg">
</p>

<p align="center">
  <img src="docs/assets/images/Panel-4.jpg">
</p>

<p align="center">
  <img src="docs/assets/images/Panel-5.jpg">
</p>

<p align="center">
  <img src="docs/assets/images/Panel-6.jpg">
</p>

<br><br>



## معرفی

این پروژه توسعه‌ی یک پنل کاربری برای اسکریپت <a href="https://github.com/yonggekkk/Cloudflare-workers-pages-vless">پروکسی Cloudflare-workers/pages</a> ایجاد شده توسط <a href="https://github.com/yonggekkk">yonggekkk</a> می‌باشد.

و همچنین قدردانی می‌کنم از توسعه دهنده اصلی پروژه [bia pain bache](https://github.com/bia-pain-bache) بخاطر پنل فوق العاده ای که خلق کردند.

### این پنل به دو روش راه‌اندازی می‌شود:

- راه‌اندازی با **Cloudflare Worker**
- راه‌اندازی با **Cloudflare Worker**
<br>



## ویژگی‌ها
<br>
<ol dir="rtl">
  <li><strong>رایگان</strong></li>
  <li><strong>پنل کاربری راحت:</strong> قابلیت آسان تنظیمات و دریافت کانفیگ ها و لینک های اشتراک.</li>
  <li><strong>پشتیبانی از فرگمنت:</strong> قابل استفاده حتی در صورت فیلتر شدن دامنه.</li>
  <li><strong>مسدود کردن تبلیغات  و پورن. (اختیاری):</strong> گزینه‌ای برای مسدودسازی تبلیغات ایرانی و خارجی و وب‌سایت‌های پورنوگرافی.</li>
  <li><strong>دسترسی مستقیم به ایران (اختیاری):</strong> شامل یک گزینه برای دسترسی مستقیم به سایت های ایران بدون قطع VPN. ،شامل اتصالات LAN نیز می‌شود.</li>
  <li><strong>مسیریابی کامل Sing-box:</strong> شامل دور زدن سایت‌های ایرانی، مسدودسازی Malware، Phishing و تبلیغات ایرانی و خارجی.</li>
  <li><strong>زنجیره‌ی Proxy:</strong> قابلیت اضافه کردن Proxy خروجی جهت تثبیت IP.</li>
  <li><strong>پشتیبانی از طیف وسیعی از برنامه‌ها:</strong> لینک‌های اشتراک را برای انواع نرم افزار ها با هسته‌های Xray و Sing-box ارائه می‌دهد.</li>
  <li><strong>لینک اشتراک (JSON):</strong> لینک‌ اشتراک کانفیگ‌های فرگمنت را در فرمت JSON فراهم می‌کند.</li>
  <li><strong>پنل با رمز عبور محافظت شده:</strong> ایمن‌سازی پنل با استفاده از رمز عبور.</li>
  <li><strong>دامنه و IP تمیز Cloudflare سفارشی:</strong> قابلیت اسکن آنلاین و تنظیم IP یا دامنه‌ی تمیز Cloudflare را دارد.</li>
<li><strong>سابسکریپشن Warp: </strong>ارائه‌ی کانفیگ‌های Warp و Warp on Warp همراه اسکنر Endpoint</li>
  <li><strong>سابسکریپشن Warp Pro: </strong>ارائه‌ی کانفیگ‌های وارپ بهینه شده برای شرایط همیشه خاص ایران</li>
</ol>
<br><br>

## نحوه‌ی راه‌اندازی، تنظیمات و استفاده
- [نصب به صورت Pages](docs/pages_installation_fa.md)
- [نصب به صورت Worker](docs/worker_installation_fa.md)
- [نحوه استفاده از پنل](docs/configuration_fa.md)
- [پرسش‌های متداول (FAQ)](docs/faq.md)
<br>

## برنامه‌های پشتیبانی شده
<div dir="rtl">
<table>
  <thead>
    <th>برنامه</th>
    <th>نسخه</th>
    <th>Fragment</th>
    <th>Warp Pro</th>
  </thead>
  <tbody  align="center">
          <td>❌</td>
    <tr>
      <td><b>v2rayNG</b></td>
      <td>1.8.19 و بالاتر</td>
      <td>✔️</td>
      <td>❌</td>
    </tr>
    <tr>
      <td><b>v2rayN</b></td>
      <td>6.42 و بالاتر</td>
      <td>✔️</td>
      <td>❌</td>
    </tr>
    <tr>
      <td><b>v2rayN-Pro</b></td>
      <td>1.4 و بالاتر</td>
      <td>✔️</td>
      <td>✔️</td>
    </tr>
    <tr>
      <td><b>Nekobox</b></td>
      <td></td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td><b>Sing-box</b></td>
      <td>1.8.10 و بالاتر</td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td><b>Streisand</b></td>
      <td></td>
      <td>✔️</td>
      <td>❌</td>
    </tr>
    <tr>
      <td><b>V2Box</b></td>
      <td></td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td><b>Shadowrocket</b></td>
      <td></td>
      <td>❌</td>
      <td>❌</td>
    </tr>
    <tr>
      <td><b>Nekoray</b></td>
      <td></td>
      <td>✔️</td>
      <td>❌</td>
    </tr>
    <tr>
      <td><b>Hiddify</b></td>
      <td>2.0.5 و بالاتر</td>
      <td>❌</td>
      <td>✔️</td>
    </tr>
    <tr>
      <td><b>NikaNG</b></td>
      <td></td>
      <td>✔️</td>
      <td>✔️</td>
    </tr>
  </tbody>
</table>
</div>

---
## تعداد ستاره‌ها به مرور زمان

[![تعداد ستاره‌ها به مرور زمان](https://starchart.cc/bia-pain-bache/BPB-Worker-Panel.svg?variant=adaptive)](https://starchart.cc/bia-pain-bache/BPB-Worker-Panel)

---
### تشکر ویژه

- نویسنده کد CF-vless <a href="https://github.com/3Kmfi6HP/EDtunnel">3Kmfi6HP</a>
- نویسنده برنامه IP ترجیحی CF <a href="https://github.com/badafans/Cloudflare-IP-SpeedTest">badafans</a>، <a href="https://github.com/XIU2/CloudflareSpeedTest">XIU2</a>

---
برای آموزش جزئیات اسکریپت اصلی، لطفاً به <a href="https://ygkkk.blogspot.com/2023/07/cfworkers-vless.html">وبلاگ و آموزش‌های ویدیویی Yongge</a> مراجعه کنید.
