# راهنمای استفاده

1. **اعداد**: روی اعداد ضربه بزنید تا در نمایشگر ظاهر شوند
2. **عملیات**: از دکمه‌های +، -، ×، ÷ برای انجام عملیات استفاده کنید
3. **نتیجه**: دکمه = را برای محاسبه نتیجه فشار دهید
4. **پاک کردن**: دکمه AC برای پاک کردن کامل
5. **حذف**: دکمه ⌫ برای حذف آخرین رقم

## تنظیمات اضافی

### تغییر نام اپلیکیشن
فایل `android/app/src/main/AndroidManifest.xml` را ویرایش کنید:
```xml
<application
    android:label="Balal_calulation"
    ...>
```

### تغییر آیکن
آیکن جدید را در مسیر `android/app/src/main/res/mipmap-*/` قرار دهید.

## مسائل رایج

### خطای "Flutter SDK not found"
مطمئن شوید که Flutter در PATH شما قرار دارد و دستور `flutter doctor` را اجرا کنید.

### خطای "Gradle build failed"
```bash
cd android
./gradlew clean
cd ..
flutter clean
flutter pub get
```

## مشارکت

1. Fork کنید
2. شاخه جدید بسازید (`git checkout -b feature/amazing-feature`)
3. تغییرات خود را commit کنید (`git commit -m 'Add amazing feature'`)
4. Push کنید (`git push origin feature/amazing-feature`)
5. Pull Request باز کنید

## لایسنس

این پروژه تحت لایسنس MIT منتشر شده است.

## پشتیبانی

اگر مشکلی داشتید، لطفاً یک Issue ایجاد کنید.

---

**نوت**: این اپلیکیشن برای آموزش و استفاده شخصی ساخته شده است.
