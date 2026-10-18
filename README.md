<div align="center">

<img src="docs/logo.svg" width="76" alt="Rhytmix">

# Rhytmix

Десктопный плеер: поиск и прослушивание из YouTube, SoundCloud, Spotify и
Яндекс.Музыки в одном приложении.

[![скачать](https://img.shields.io/github/v/release/salenyo/rhytmix-releases?label=%E2%AC%87%20%D1%81%D0%BA%D0%B0%D1%87%D0%B0%D1%82%D1%8C&color=0a84ff&style=for-the-badge)](https://github.com/salenyo/rhytmix-releases/releases/latest)
[![платформы](https://img.shields.io/badge/Windows%20%7C%20macOS%20%7C%20Linux-6e6e73?style=for-the-badge)](https://github.com/salenyo/rhytmix-releases/releases/latest)

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="docs/preview-dark.png">
  <img src="docs/preview-light.png" alt="Интерфейс Rhytmix" width="100%">
</picture>

</div>

## Возможности

- **Поиск по всем источникам сразу** — YouTube, SoundCloud, Spotify и Яндекс.Музыка из одной строки; можно найти песню по строчке из текста
- **Тексты песен** с подсветкой по словам, как в караоке
- **Лайки и плейлисты**, импорт плейлистов по ссылке из SoundCloud и Spotify
- **Рекомендации** по прослушанному, мировые и региональные чарты, жанры
- **Звук** — 10-полосный эквалайзер с пресетами, плавный переход между треками, выравнивание громкости, таймер сна
- **Оформление** — светлая и тёмная темы, свой акцент и фон, магазин тем
- **Итоги** месяца, сезона и года — топ треков и артистов, любимый жанр, картинкой
- **Друзья** — профили, подписки, «что сейчас играет»
- **Слушать вместе** — комната по коду: друзья слышат то же, что и вы, синхронно
- Медиа-клавиши, системный виджет плеера, трей, статус в Discord
- Встроенное обновление

<img src="docs/screens.png" alt="Плеер, текст песни, поиск и статистика" width="100%">

## Установка

| ОС | Файл | Примечание |
|----|------|------------|
| **Windows** | `Rhytmix_<версия>_x64-setup.exe` | обычный установщик |
| **macOS** | `Rhytmix_<версия>_universal.dmg` | при первом запуске macOS скажет, что не может проверить приложение: **Системные настройки → Конфиденциальность и безопасность → Всё равно открыть** |
| **Linux** | `.AppImage`, `.deb` или `.rpm` | AppImage нужно сделать исполняемым: `chmod +x` |
| **Arch Linux** | `rhytmix-app_<версия>_x86_64-linux.tar.gz` | распаковать и запустить `./rhytmix-app` либо `sudo ./install.sh`; зависимости: `pacman -S webkit2gtk-4.1 alsa-lib`. Обновляется вручную |

<div align="center">

### [⬇ Скачать последнюю версию](https://github.com/salenyo/rhytmix-releases/releases/latest)

</div>

## Обновления

Приложение проверяет обновления при запуске и ставит их в один клик — приходят только стабильные
релизы. Ночные сборки (`1.0.0-nightly.42`, помечены как Pre-release) ставятся вручную со страницы
релизов: новое в них появляется раньше, но бывают ошибки.

## Аккаунт

Регистрация открыта — достаточно придумать логин и пароль. Аккаунт общий с
[мобильной версией](https://github.com/salenyo/lamusica-mobile-releases): лайки, плейлисты и история
синхронизируются.

---

<div align="center">

Мобильная версия — [lamusica-mobile-releases](https://github.com/salenyo/lamusica-mobile-releases).

Нашли проблему или есть идея — [заведите issue](https://github.com/salenyo/rhytmix-releases/issues).

</div>
