# Консольные утилиты Шатохина 🏁

Полезные (и не очень) утилиты на PowerShell™

## 🔽 Установка

Тут всё просто, копируем в любимую папку с модулями и используем:
- `C:\Users\$env:USERNAME\Documents\PowerShell\Modules`
- `C:\Program Files\PowerShell\Modules`
- `C:\Program Files\WindowsPowerShell\Modules`
- `C:\WINDOWS\system32\WindowsPowerShell\v1.0\Modules`

Доступные утилиты для использования:

## Get-FilePaths

Вывод путей файлов в консоль с заданной маской 🎭

Может принимать ровно 1 строковый параметр (а может и не принимать):

```powershell
PS C:\Users\shatohin\Pictures> Get-FilePaths -Filemask снимок*
C:\Users\shatohin\Pictures\Снимок экрана 2020-09-10 125922.png
C:\Users\shatohin\Pictures\Снимок экрана 2020-09-12 113529.png
C:\Users\shatohin\Pictures\Снимок экрана 2020-10-17 124817.png
C:\Users\shatohin\Pictures\Снимок экрана 2020-10-25 000125.png
C:\Users\shatohin\Pictures\Снимок экрана 2020-10-25 000205.png
```
