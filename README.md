# hp-laserjet-p1102-macos-tahoe-ready
Ready-to-install HP LaserJet P1102 / P1102w driver package for macOS Tahoe 26 | Готовый драйвер HP LaserJet P1102 / P1102w для macOS Tahoe 26

## Download / Скачать

👉 [Releases](../../releases) — download the `.pkg` file and run it.  
👉 [Releases](../../releases) — скачай `.pkg` файл и запусти его.

---

## What's inside / Что внутри

The official HP LaserJet driver (v10.6.0.1.1) with a modified version check —  
the only change is `system.version.ProductVersion '15.0'` → `'27.0'` in the installer's `Distribution` file.  
No driver files were modified.

Официальный драйвер HP LaserJet (v10.6.0.1.1) с изменённой версионной проверкой —  
единственное изменение: `system.version.ProductVersion '15.0'` → `'27.0'` в файле `Distribution` установщика.  
Файлы самого драйвера не менялись.

---

## Tested on / Проверено на

- macOS Tahoe 26.3.1
- Apple Silicon
- HP LaserJet **P1102w** 

---

## Supported models / Поддерживаемые модели

- HP LaserJet P1102
- HP LaserJet Pro P1102w
- HP LaserJet P1102s
- HP LaserJet P1106
- HP LaserJet P1108

---

## Do it yourself / Сделать самому

If you prefer to build the package yourself, follow the instructions from  
[pavelbinar's gist](https://gist.github.com/pavelbinar/e14bb47f98768d83828bdee89a47490e),  
changing the version to `'27.0'` instead of `'16.0'`.

---

## Disclaimer / Отказ от ответственности

Unofficial workaround, not supported by HP. Use at your own risk.  
Неофициальное решение, не поддерживается HP. Используйте на свой страх и риск.
