# ScrapSpank

Русификатор сборки модов Scrap Mechanic.

## Установка

1. Скачай последнюю сборку из [Releases](https://github.com/Xinevi/ScrapSpank/releases).
2. Запусти `ScrapSpank-(Release/Beta)-v.X.X.exe`.
3. Укажи директорию `steamapps\workshop\content\387990` и запусти установку.
4. Нужно перезапустить игру — тексты применятся.

## Обновление

Программа сама проверяет обновления при запуске: если есть новая сборка —
появится кнопка «Доступно — Установить», скачивание и замена происходят автоматически.

## Поддерживаемые моды (A–Z)

Установка и удаление русификации выполняются в том же порядке — по алфавиту (A–Z).

1. [Bearing Lock Logic](https://steamcommunity.com/sharedfiles/filedetails/?id=3344671725)
2. [Fants Block and Parts](https://steamcommunity.com/sharedfiles/filedetails/?id=2950134231)
3. [Fants Grinder](https://steamcommunity.com/sharedfiles/filedetails/?id=3011575610)
4. [Fants Logic Stuff](https://steamcommunity.com/sharedfiles/filedetails/?id=2947206586)
5. [Fants Mountable Weapons](https://steamcommunity.com/sharedfiles/filedetails/?id=3039777840)
6. [Fants Parking Space](https://steamcommunity.com/sharedfiles/filedetails/?id=2965553955)
7. [Fants Pipes Container Pumps Recycler](https://steamcommunity.com/sharedfiles/filedetails/?id=2963115530)
8. [Fants Propulsion Stuff](https://steamcommunity.com/sharedfiles/filedetails/?id=2949730799)
9. [Storage Manager](https://steamcommunity.com/sharedfiles/filedetails/?id=3223948145)

## Что нового в 1.4

- **Переводы новых модов**: Fants Mountable Weapons (00Fant: Банананатор, Танковая пушка,
  Навесной дробовик, Свечесмёт и боеприпасы) и Storage Manager — теперь поддерживается 9 модов.
- **Новости и опросы в приложении**: лента с поиском, бейджи непрочитанных, голосования
  с реальной статистикой через Cloudflare Worker (полосы, проценты, защита от повторных
  голосов по HWID). У опросов есть срок действия: до закрытия идут голоса, после —
  автоматический показ итогов всем.
- **Виджеты баннера**: карточки «Поддерживается модов», «Следующее обновление» (дата патча
  и отсчёт «через 23 ч 38 мин») и таймер сезона (Новый год / Лето) с единой сеткой.
- **Темы**: тёмная и светлая для новостей и опросов.
- **Окно приложения**: запрещено разворачивание на весь экран; DevTools открываются по F12.
- **Голосование**: кнопка активируется после выбора варианта, ответ сервера применяется
  мгновенно, при ошибке показывается её текст прямо в окне опроса.

## Обратная связь

Ошибки, опечатки и идеи — через кнопку «Сообщить об ошибке» в приложении
или [Issues](https://github.com/Xinevi/ScrapSpank/issues).