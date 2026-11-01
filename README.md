# Смены такси — Android-приложение

Учёт смен внутри оболочки Android (WebView). Иконка уже подключена. Данные хранятся на телефоне.

## Как получить APK
1. Создай репозиторий на GitHub и загрузи в него все файлы этой папки (вместе с папкой .github).
2. Открой вкладку Actions и дождись зелёной галочки у «Сборка APK» (или нажми Run workflow).
3. В готовой сборке внизу, в разделе Artifacts, скачай smeny-taksi-apk: внутри лежит app-debug.apk.
4. Перенеси APK на телефон и установи (разреши установку из этого источника).

## Где что менять
- Учёт: app/src/main/assets/index.html
- Иконка: app/src/main/res/mipmap-*/ic_launcher.png
- Название: app/src/main/res/values/strings.xml
