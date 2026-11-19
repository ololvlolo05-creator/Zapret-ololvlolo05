# Zapret Freedom

Обход DPI-блокировок на Android без root: Discord, YouTube и другие сайты.

Приложение не меняет системные настройки и не требует root: весь трафик
заворачивается в локальный SOCKS-туннель, а `ciadpi` разбирает и «ломает»
сигнатуры DPI.

## Возможности

- VPN-туннель на базе ByeDPI (`ciadpi`) и `hev-socks5-tunnel`;
- стратегии — наборы аргументов `ciadpi`: встроенные, свои, импорт `.bat` с ПК;
- автоподбор рабочей стратегии с проверкой доступности целей;
- автозапуск при открытии выбранных приложений;
- плитка в шторке, виджет, тихий режим;
- диагностика и отправка отчётов.

## Сборка

```bash
export ANDROID_HOME=/path/to/android-sdk
./gradlew :app:assembleRelease
```

Требуется JDK 17+, Android SDK 34, Gradle 8.8.

## Лицензия

GNU General Public License v3.0. Сторонние компоненты перечислены в
[THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md).

## Соглашение об отправке отчётов

<https://raw.githubusercontent.com/ololvlolo05-creator/Zapret-ololvlolo05/main/agreement.md>
