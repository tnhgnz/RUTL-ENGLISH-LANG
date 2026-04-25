# RUTL-ENGLISH-LANG

English language resources for **Throne and Liberty** (client-side localization).

Repository: [github.com/tnhgnz/RUTL-ENGLISH-LANG](https://github.com/tnhgnz/RUTL-ENGLISH-LANG)

---

## Русский

### О проекте

Патч подменяет локализацию так, чтобы в клиенте отображался **английский** текст при выборе **корейского** языка в настройках игры.

### Ручная установка

1. Найди папку клиента игры и открой каталог:
   `Throne and Liberty\TL\Content`  
   (полный путь зависит от лаунчера: VK Play, Astrum Play)

2. **Сделай резервную копию** оригинальных файлов локализации :
   - `TL\Content\Paks\pakchunk-Localization-ko.pak`
   - `TL\Content\Paks\pakchunk-Localization-ko.sig`  

   Пример пути (VK Play):  
   `E:\VK Play\Throne and Liberty\TL\Content\Paks\`

3. Скопируй **всё содержимое** папки [`Install`](./Install) из этого репозитория в каталог:
   `Throne and Liberty\TL\Content`  
   (файлы должны оказаться рядом с `Paks`, `Localization` и остальной структурой `Content`, как задумано в пакете.)

4. Запусти игру и в настройках выстави язык **корейский** (Korean) — так активируется подменённая локализация.

### Автоматическая установка

Можно поставить патч через мой софт **[TL-Vanced](https://github.com/tnhgnz/TL-VANCED)**.

### Файлы перевода

В корне репозитория также лежит [`Translate.csv`](./Translate.csv) — таблица строк для правок и обновлений.
Её никуда переносить не надо! Она лежит для меня.

### Лицензия и отказ от ответственности

Проект распространяется под лицензией **Apache 2.0** (см. файл [`LICENSE`](./LICENSE)).  
Не связан с издателем или разработчиком игры; использование — на **свой риск**. Перед заменой файлов всегда сохраняй бэкапы.

---

## Спасибо всем

Если вам очень понравилась моя программа, вы можете подписаться на мои соцсети или швырнуть в меня свои грязные гроши!

- [Twitch](https://www.twitch.tv/tnhgnz)
- [YouTube](https://www.youtube.com/@Tnhgnz)
- [Telegram](https://t.me/tnhgnz)
- [Донат](https://www.donationalerts.com/r/tnhgnz)

---

## English

### About

This patch replaces packaged localization so the client shows **English** UI text while **Korean** is selected in the game language settings.

### Manual install

1. Open your game install folder and go to:
   `Throne and Liberty\TL\Content`  
   (exact root depends on your launcher: VK Play, Astrum Play)

2. **Back up** the original Korean localization files :
   - `TL\Content\Paks\pakchunk-Localization-ko.pak`
   - `TL\Content\Paks\pakchunk-Localization-ko.sig`  

   Example (VK Play):  
   `E:\VK Play\Throne and Liberty\TL\Content\Paks\`

3. Copy **everything inside** the repository [`Install`](./Install) folder into:
   `Throne and Liberty\TL\Content`  
   so the patched files sit next to `Paks`, `Localization`, and the rest of the shipped `Content` layout.

4. Launch the game and set the language to **Korean** — that is the combination this patch targets.

### Automatic install

You can apply the localization via the my software **[TL-Vanced](https://github.com/tnhgnz/TL-VANCED)**.

### Translation data

[`Translate.csv`](./Translate.csv) in the repo root holds the string table for edits and updates.
You don't need to move it anywhere! It's here for me.

### License and disclaimer

Licensed under **Apache 2.0** (see [`LICENSE`](./LICENSE)).  
Not affiliated with the publisher or game developer; use at **your own risk**. Always keep backups before overwriting client files.

---

## Thank you all

If you really liked my program, you can subscribe to my social networks or throw your dirty pennies at me!

- [Twitch](https://www.twitch.tv/tnhgnz)
- [YouTube](https://www.youtube.com/@Tnhgnz)
- [Telegram](https://t.me/tnhgnz)
- [Donat](https://www.donationalerts.com/r/tnhgnz)

---
