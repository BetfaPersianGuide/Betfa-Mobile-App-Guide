<!DOCTYPE html>
<html lang="fa" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>مستندات فنی و راهنمای نسخه موبایل بت فا | Betfa App Guide</title>
    <meta name="description" content="مستندات فنی، مشخصات نرم‌افزاری و راهنمای نصب نسخه موبایل و وب‌اپلیکیشن بت فا برای کاربران فارسی‌زبان.">
    <style>
        :root {
            --primary-color: #24292e;
            --accent-color: #0366d6;
            --bg-color: #f6f8fa;
            --border-color: #e1e4e8;
            --text-color: #24292e;
        }
        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
            line-height: 1.7;
            color: var(--text-color);
            background-color: var(--bg-color);
            margin: 0;
            padding: 20px;
        }
        .container {
            max-width: 880px;
            margin: 0 auto;
            background: #ffffff;
            padding: 40px;
            border: 1px solid var(--border-color);
            border-radius: 6px;
            box-shadow: 0 1px 3px rgba(0,0,0,0.04);
        }
        h1 { border-bottom: 2px solid var(--border-color); padding-bottom: 10px; color: var(--primary-color); }
        h2 { border-bottom: 1px solid var(--border-color); padding-bottom: 8px; margin-top: 30px; color: var(--primary-color); }
        h3 { color: #444; margin-top: 20px; }
        code { background: #f3f3f3; padding: 2px 6px; border-radius: 3px; font-family: monospace; }
        .table-responsive { overflow-x: auto; margin: 20px 0; }
        table { width: 100%; border-collapse: collapse; text-align: right; }
        th, td { border: 1px solid var(--border-color); padding: 10px 15px; }
        th { background-color: var(--bg-color); }
        .alert-box {
            background-color: #fff3cd;
            border: 1px solid #ffeeba;
            color: #856404;
            padding: 15px;
            border-radius: 4px;
            margin: 20px 0;
        }
        .anchor-link {
            color: var(--accent-color);
            text-decoration: none;
            font-weight: bold;
        }
        .anchor-link:hover { text-decoration: underline; }
        footer { margin-top: 40px; font-size: 0.85em; color: #6a737d; border-top: 1px solid var(--border-color); padding-top: 20px; }
    </style>
</head>
<body>

<div class="container">
    <h1>مستندات فنی و راهنمای کاربردی نسخه موبایل بت فا (Betfa)</h1>

    <div class="alert-box">
        <strong>💡 یادداشت مستندات:</strong> این صفحه یک مرجع آموزشی و مستندات فنی مستقل جهت بررسی عملکرد رابط کاربری موبایل بت فا است. این وب‌سایت فایل‌های ناشناس ارائه نداده و صرفاً به آموزش تنظیمات نرم‌افزاری می‌پردازد.
    </div>

    <h2>۱. مقدمه و نمای کلی نسخه موبایل</h2>
    <p>استفاده از خدمات تحت وب روی تجهیزات همراه، نیازمند بهینه‌سازی کدهای فرانت‌اند و سازگاری کامل با سیستم‌عامل‌های iOS و Android است. پلتفرم <strong>بت فا (Betfa)</strong> با ارائه دو راهکار «نسخه وب‌اپلیکیشن پیشرفته (PWA)» و «برنامه اختصاصی»، امکان دسترسی به امکانات مختلف را روی نمایشگرهای لمسی فراهم کرده است.</p>

    <h2>۲. مشخصات فنی و جدول پیش‌نیازهای سیستم‌عامل</h2>
    <p>پیش از اقدام به راه‌اندازی، بررسی تطابق مشخصات دستگاه با جدول پیش‌نیازهای زیر توصیه می‌شود:</p>

    <div class="table-responsive">
        <table>
            <thead>
                <tr>
                    <th>ویژگی</th>
                    <th>نسخه اندروید (Android)</th>
                    <th>نسخه آیفون (iOS WebApp)</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>حداقل سیستم‌عامل</td>
                    <td>Android 6.0 و بالاتر</td>
                    <td>iOS 12.0 و بالاتر</td>
                </tr>
                <tr>
                    <td>مرورگر پیشنهادی</td>
                    <td>Google Chrome / Firefox</td>
                    <td>Safari / Chrome</td>
                </tr>
                <tr>
                    <td>فضای مورد نیاز</td>
                    <td>حدود ۱۵ مگابایت</td>
                    <td>بدون نیاز به فضای ذخیره‌سازی اصلی</td>
                </tr>
                <tr>
                    <td>پشتیبانی از PWA</td>
                    <td>کامل</td>
                    <td>کامل (Add to Home Screen)</td>
                </tr>
            </tbody>
        </table>
    </div>

    <h2>۳. مراحل گام‌به‌گام راه‌اندازی نسخه PWA روی آیفون و اندروید</h2>
    <p>بهترین روش برای استفاده بدون لگ و اختلال از رابط کاربری بت فا روی تلفن همراه، استفاده از قابلیت WebApp است:</p>
    
    <h3>راه‌اندازی در iOS (مرورگر Safari):</h3>
    <ol>
        <li>آدرس وب‌سایت را در مرورگر Safari باز کنید.</li>
        <li>روی دکمه <code>Share</code> (آیکون مربع با فلش رو به بالا) کلیک کنید.</li>
        <li>گزینه <code>Add to Home Screen</code> را انتخاب نمایید.</li>
        <li>نام میانبر را تأیید کرده و روی <code>Add</code> بزنید تا آیکون Betfa به صفحه اصلی گوشی اضافه شود.</li>
    </ol>

    <h3>راه‌اندازی در اندروید (مرورگر Chrome):</h3>
    <ol>
        <li>سایت را در مرورگر Chrome باز کنید.</li>
        <li>روی منوی سه‌نقطه در بالای صفحه کلیک کنید.</li>
        <li>گزینه <code>Install app</code> یا <code>Add to Home Screen</code> را انتخاب نمایید.</li>
    </ol>

    <h2>۴. اطلاعات دسترسی و منابع راهنمای دریافت برنامه</h2>
    <p>بسیاری از کاربران برای حل چالش‌های اتصال و آگاهی از آخرین به‌روزرسانی‌های نرم‌افزاری، نیازمند مطالعه مقالات تحلیلی هستند. جهت بررسی دقیق مشخصات، آموزش‌های تصویری و آشنایی با مراحل دریافت فایل‌ها، مطالعه راهنمای تخصصی مربوط به <a href="https://betfa90.org/app/" class="anchor-link">دانلود اپلیکیشن بت فا</a> به شما کمک می‌کند تا بدون سردرگمی، تمام مراحل نصب را روی تلفن همراه خود اجرا نمایید.</p>

    <h2>۵. عیب‌یابی خطاهای متداول نسخه موبایل</h2>
    <h3>خطای عدم بارگذاری عناصر صفحه (White Screen Error):</h3>
    <p>در صورت مواجهه با صفحه سفید، کش مرورگر خود را پاک کرده و یا مرورگر را به آخرین نسخه به‌روزرسانی کنید.</p>

    <h3>تداخل کوکی‌های قدیمی:</h3>
    <p>پیشنهاد می‌شود هر چند وقت یک‌بار از مسیر <code>Settings > Privacy > Clear Browsing Data</code> داده‌های موقت را پاکسازی نمایید.</p>

    <footer>
        <p><strong>سلب مسئولیت:</strong> این مستندات صرفاً یک پروژه آموزشی و راهنمای فنی مستقل برای کاربران فارسی‌زبان است و هیچ‌گونه وابستگی رسمی به برند بت فا ندارد.</p>
    </footer>
</div>

</body>
</html>
