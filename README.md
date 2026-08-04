# ScrapSpank

Русификатор сборки модов Scrap Mechanic.

## Установка

1. Скачай последнюю сборку из [Releases](https://github.com/Xinevi/ScrapSpank/releases).
2. Запусти `ScrapSpank-(Release/Beta)-v.X.X.exe`.
3. Укажи директорию `steamapps\workshop\content\387990` и запусти установку.
4. Нужно **перезапустить игру** — тексты применятся.

## Обновление

Программа сама проверяет обновления при запуске: если есть новая сборка —
появится кнопка «Доступно — Установить», скачивание и замена происходят
автоматически.

## Сборка (для разработки)

1. `gen_installer3.ps1` собирает `SM_Russian_Installer.py`.
2. `pyinstaller --onefile --noconsole --icon=ScrapSpank_logo.ico ...`.
3. `gh release create "ScrapSpank-Beta-v.X.0" ./ScrapSpank-Beta-v.X.0.exe`.
