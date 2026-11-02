# World Free TV (Android TV)
Открывает https://famelack.com/tv в WebView.

## Сборка APK
Вариант 1 (GitHub): создай репозиторий, залей эти файлы, вкладка Actions -> Build APK -> Artifacts -> famelack-tv-apk (app-debug.apk).
Вариант 2: открой папку в Android Studio -> Build -> Build APK(s).

## Установка на ТВ
adb connect <IP_ТВ>:5555
adb install app-debug.apk
