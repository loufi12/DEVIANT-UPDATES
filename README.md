# DEVIANT TOOL

<p align="center">
  <strong>🎮 Оптимизация GTA 5 и Majestic RP под Windows</strong><br>
  Без ASI-модов, без читов, без закрытия Discord и самой игры
</p>

<p align="center">
  <a href="https://github.com/loufi12/DEVIANT-UPDATES/releases/latest"><img src="https://img.shields.io/github/v/release/loufi12/DEVIANT-UPDATES?label=%D0%B2%D0%B5%D1%80%D1%81%D0%B8%D1%8F&color=2ea043" alt="Latest release"></a>
  <a href="https://github.com/loufi12/DEVIANT-UPDATES/releases/latest"><img src="https://img.shields.io/github/downloads/loufi12/DEVIANT-UPDATES/total?label=%D1%81%D0%BA%D0%B0%D1%87%D0%B8%D0%B2%D0%B0%D0%BD%D0%B8%D0%B9&color=0969da" alt="Downloads"></a>
  <a href="https://www.virustotal.com/gui/file/900bb204e2104093c6f8931ac96bdf6fe8c66724f02910f5f21be0009222df10"><img src="https://img.shields.io/badge/VirusTotal-%D0%BF%D1%80%D0%BE%D0%B2%D0%B5%D1%80%D0%B8%D1%82%D1%8C_файл-394eff" alt="VirusTotal"></a>
  <a href="https://discord.gg/fNTh4mRk3w"><img src="https://img.shields.io/badge/Discord-%D1%81%D0%B5%D1%80%D0%B2%D0%B5%D1%80-5865F2" alt="Discord"></a>
</p>

<p align="center">
  <a href="https://github.com/loufi12/DEVIANT-UPDATES/releases/latest"><strong>📥 Скачать последнюю версию</strong></a>
  ·
  <a href="https://www.virustotal.com/gui/file/900bb204e2104093c6f8931ac96bdf6fe8c66724f02910f5f21be0009222df10"><strong>🛡️ Проверить на вирусы</strong></a>
  ·
  <a href="https://discord.gg/fNTh4mRk3w"><strong>🎮 Discord</strong></a>
</p>

---

## 🎮 Что это

DEVIANT TOOL — программа для слабых и средних ПК, которые играют в **GTA 5** на **Majestic RP**. Она освобождает память, убирает оверлеи и запись экрана, правит графику против чёрных текстур и пишет только **официальные** параметры запуска Rockstar.

Исходников в этом репозитории нет: здесь лежат только готовые сборки. Качайте exe **только из Releases** на этой странице. Другие ссылки — не наши.

---

## 🛡️ Безопасность — проверьте сами

Не верьте «на слово». Файл можно прогнать через 70+ антивирусов на **VirusTotal** и сверить контрольную сумму.

| | |
|---|---|
| **VirusTotal** | [Открыть отчёт по этому файлу](https://www.virustotal.com/gui/file/900bb204e2104093c6f8931ac96bdf6fe8c66724f02910f5f21be0009222df10) |
| **Загрузить сами** | [virustotal.com/gui/home/upload](https://www.virustotal.com/gui/home/upload) — выберите скачанный `DEVIANT TOOL.exe` |
| **SHA256** | `900BB204E2104093C6F8931AC96BDF6FE8C66724F02910F5F21BE0009222DF10` |
| **Версия** | 1.1.1 |
| **Размер** | ≈ 30 МБ |

Как сверить хеш на своём компьютере (PowerShell):

```powershell
Get-FileHash -LiteralPath "$env:USERPROFILE\Downloads\DEVIANT TOOL.exe" -Algorithm SHA256
```

Строка `Hash` должна совпасть с таблицей выше. Если не совпала — файл чужой, не запускайте.

> Если VirusTotal пишет *Item not found*, файл ещё не заливался в их базу. Нажмите **Upload file** на той же странице или по ссылке «Загрузить сами» — через минуту появится отчёт.

**Важно про ложные срабатывания.** Программа собрана через PyInstaller (один exe без установки). Некоторые антивирусы помечают такие сборки как «generic packed» — это не вирус, а общая реакция на упакованный Python. Смотрите конкретные названия детектов и сравнивайте SHA256.

### ✅ Чего программа не делает

- не ставит ASI и не лезет в античит Majestic
- не пишет запрещённые ключи вроде `-textureQuality`, `-memrestrict`, `-norestrictions`
- не закрывает Discord, GTA и лаунчер Majestic
- не крадёт пароли и не шлёт ваши данные «налево»
- обновления качает только с этих официальных релизов GitHub

---

## ✨ Что нового в 1.1.1

- Своя иконка, цвет у главной кнопки, короткая главная
- Советы именно для вашего ПК и кнопка «исправить»
- Прогресс оптимизации, итог после работы, первый запуск из трёх шагов
- Журнал с цветом и копированием
- Свернуть в трей (Discord не трогаем)

---

## ⚡ Что умеет

### 💻 Память и картинка

- освобождает ОЗУ, не трогая Discord / GTA / Majestic
- пресеты **Дыры / Баланс / FPS**
- графика против чёрных текстур + официальный `commandline.txt`

### 🖥️ Оверлеи и фон

- NVIDIA Broadcast, Epic Overlay, NVIDIA Overlay, Xbox Game Bar
- оверлей Discord выключается без закрытия самого Discord
- Game Mode, Game DVR, высокий приоритет GTA

### ⚙️ Система (по желанию)

- подкачка, планирование GPU и другие пункты Windows
- часть работает только от имени администратора
- предупреждает про `OpenIV.asi`

После смены графики нужен **релог** в Majestic.

---

## 🚀 Как пользоваться

1. Скачайте exe из [последнего релиза](https://github.com/loufi12/DEVIANT-UPDATES/releases/latest).
2. Проверьте на [VirusTotal](https://www.virustotal.com/gui/file/900bb204e2104093c6f8931ac96bdf6fe8c66724f02910f5f21be0009222df10).
3. Запустите. Для системных пунктов — от имени администратора.
4. Пресет или «Оптимизировать».
5. Если меняли графику на запущенной GTA — выйдите из персонажа и зайдите снова.

---

## 💬 Связь

- Discord: https://discord.gg/fNTh4mRk3w
- Автор: **Erik** · `dvnterik`
