# Daily Expenses | روزانہ اخراجات

## English

A simple, private expense tracker for everyday household spending in Pakistani rupees (PKR). It works in English and Urdu, works offline, and keeps all data on your own phone.

### Features

- Language button to switch between English and Urdu at any time.
- Login screen. The first login is `Admin` / `admin`, and the app asks you to choose your own username and password straight away.
- Dashboard for any month: net amount, amount spent, remaining balance, spent and remaining percentages, and a bar for each main item.
- Add expenses with item, amount, date and an optional note.
- Save a net amount with a date. You can edit or delete it later.
- Item list with common household items. You can add or remove items. Cigarettes always stays at the end.
- Export all data to CSV.

### Files

| File | Purpose |
| --- | --- |
| `index.html` | The whole app |
| `manifest.json` | App name, colours and icons |
| `sw.js` | Lets the app work offline |
| `icon-192.png`, `icon-512.png` | Web app icons |
| `icon-only.png`, `icon-foreground.png`, `icon-background.png` | Source files for the phone app icon |
| `.nojekyll` | Tells GitHub Pages to serve files as they are |
| `.github/workflows/build-apk.yml` | Builds the Android APK on GitHub |

### Build the APK

1. Open the **Actions** tab, then **Build Android APK**, then **Run workflow**.
2. Wait 5 to 10 minutes for the green tick.
3. Download `daily-expenses-apk` from **Artifacts**, unzip it, and install `app-debug.apk`.

### Privacy

- All data stays in your phone's app storage. Nothing is sent to any server.
- The login only locks the app on your device. It does not encrypt your data.
- Uninstalling the app deletes your data, so use **Export CSV** in Settings for backups.

---

## اردو

روزمرہ گھریلو اخراجات کا حساب رکھنے کے لیے ایک سادہ اور نجی ایپ، پاکستانی روپوں میں۔ یہ اردو اور انگریزی دونوں میں چلتی ہے، آف لائن کام کرتی ہے، اور آپ کا سارا ڈیٹا صرف آپ کے فون میں رہتا ہے۔

### خصوصیات

- زبان کا بٹن، جس سے کسی بھی وقت اردو اور انگریزی بدلی جا سکتی ہے۔
- لاگ اِن اسکرین۔ پہلی بار صارف نام `Admin` اور پاس ورڈ `admin` ہے، اور ایپ فوراً آپ سے اپنا صارف نام اور پاس ورڈ منتخب کرنے کو کہتی ہے۔
- ڈیش بورڈ: ہر مہینے کی نیٹ رقم، کل خرچ، بقایا رقم، خرچ اور بقایا کی فیصد، اور ہر اہم چیز کا فیصد۔
- خرچہ شامل کریں: چیز، رقم، تاریخ اور اختیاری نوٹ۔
- نیٹ رقم تاریخ کے ساتھ محفوظ کریں، اور بعد میں ترمیم یا حذف کریں۔
- اشیاء کی فہرست میں نئی چیز شامل یا پرانی ہٹائی جا سکتی ہے۔ "سگریٹ" ہمیشہ آخر میں رہتا ہے۔
- تمام ڈیٹا CSV میں ایکسپورٹ کریں۔

### APK بنانا

1. **Actions** ٹیب میں **Build Android APK** کھولیں اور **Run workflow** دبائیں۔
2. 5 سے 10 منٹ انتظار کریں، جب تک سبز ٹِک نہ آ جائے۔
3. **Artifacts** سے `daily-expenses-apk` ڈاؤن لوڈ کریں، ZIP کھولیں اور `app-debug.apk` انسٹال کریں۔

### پرائیویسی

- ڈیٹا صرف آپ کے فون میں محفوظ ہوتا ہے۔ کچھ بھی کسی سرور کو نہیں بھیجا جاتا۔
- لاگ اِن صرف آپ کے فون پر ایپ کو لاک کرتا ہے، ڈیٹا کو انکرپٹ نہیں کرتا۔
- ایپ ان انسٹال کرنے سے ڈیٹا ختم ہو جاتا ہے، اس لیے ترتیبات میں **CSV ایکسپورٹ** سے بیک اپ لیتے رہیں۔
