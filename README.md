<div align="center">

# PET-800

**An animated T-800-inspired desktop pet for ChatGPT / Codex**

<img src="assets/preview.gif" alt="PET-800 waving" width="192">

A tiny chrome endoskeleton with glowing red eyes. It reacts to work, waiting, errors, and completed tasks.

[Download PET-800.zip](https://github.com/dmbaev/PET-800/releases/latest/download/PET-800.zip) · [View all animations](assets/contact-sheet.png) · [Русская версия](#русский)

</div>

## Features

- 9 animations: idle, run right, run left, wave, jump, error, waiting, working, and reviewing a result.
- 16 gaze directions with a rotating metal head.
- Transparent v2 sprite atlas: **1536 × 2288**, with **192 × 208** cells.

## Install and launch

1. [Download PET-800.zip](https://github.com/dmbaev/PET-800/releases/latest/download/PET-800.zip) and extract it. The archive contains a `t-800` folder.
2. Copy the **entire** `t-800` folder to your local pets directory:
   - **Windows:** `%USERPROFILE%\.codex\pets\t-800\`
   - **macOS / Linux:** `~/.codex/pets/t-800/`
3. Make sure `pet.json` and `spritesheet.webp` are directly inside that folder, without another nested `t-800` folder.
4. Open the ChatGPT / Codex desktop app. From the profile menu, open **Settings → Pets**, click **Refresh**, and select **T-800**.
5. Enter `/pet` in the app's command field or choose **Show pet** from the command menu to display it on your desktop. Enter `/pet` again to hide it.

If **T-800** does not appear in the list, check the folder structure in step 3 and click **Refresh** again. The source `pet.json` and `spritesheet.webp` are also available in the repository root.

## Preview

![Neutral pose and 16 gaze directions](assets/look-directions.png)

<details>
<summary>View every animation frame</summary>

![All PET-800 animations](assets/contact-sheet.png)

</details>

## Compatibility

This package is for the ChatGPT / Codex desktop app. The [official pets documentation](https://learn.chatgpt.com/docs/pets) explains how to select a local pet in **Settings → Pets**. Web upload currently requires a 1536 × 1872 atlas; PET-800 uses the 1536 × 2288 v2 format.

PET-800 is an unofficial fan project and is not affiliated with the Terminator rights holders.

---

## Русский

**PET-800** — анимированный питомец в образе T-800 для настольного приложения ChatGPT / Codex. Миниатюрный хромированный эндоскелет с красными сенсорами реагирует на работу, ожидание, ошибки и завершение задач.

### Возможности

- 9 анимаций: покой, бег вправо и влево, приветствие, прыжок, ошибка, ожидание, работа и просмотр результата.
- 16 направлений взгляда с поворотом металлической головы.
- Прозрачный атлас v2: **1536 × 2288**, ячейка **192 × 208**.

### Установка и запуск

1. [Скачайте PET-800.zip](https://github.com/dmbaev/PET-800/releases/latest/download/PET-800.zip) и распакуйте архив. Внутри находится папка `t-800`.
2. Скопируйте **всю папку** `t-800` в каталог питомцев:
   - **Windows:** `%USERPROFILE%\.codex\pets\t-800\`
   - **macOS / Linux:** `~/.codex/pets/t-800/`
3. Проверьте, что в конечной папке лежат `pet.json` и `spritesheet.webp`, без дополнительной вложенной папки `t-800`.
4. Откройте настольное приложение ChatGPT / Codex. В меню профиля выберите **Settings → Pets**, нажмите **Refresh** и выберите **T-800**.
5. Введите `/pet` в поле команд приложения или выберите **Show pet** в меню команд. Повторная команда `/pet` скрывает питомца.

Если **T-800** не появился в списке, проверьте путь к файлам из шага 3 и повторно нажмите **Refresh**.

Пакет предназначен для настольного приложения. Для веб-загрузки сейчас требуется атлас 1536 × 1872, а PET-800 использует формат v2 1536 × 2288. PET-800 — неофициальный фанатский проект, не связанный с правообладателями Terminator.