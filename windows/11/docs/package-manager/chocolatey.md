# CHOCOLATEY

>[!NOTE]
>
>це :package: для керування :package: в командному рядку та інсталятор :package: забезпечення в Microsoft :desktop_computer: на рівні машини. Він використовує інфраструктуру :package: NuGet і :desktop_computer: PowerShell для спрощення процесу завантаження та встановлення :package: забезпечення

## Встановлення

- відкриваємо PowerShell з правами адміністратора
- Вводимо команду для встановлення

```powershell
Set-ExecutionPolicy Bypass -Scope Process -Force; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))
```

- після встановлення перевіряємо чи Chocolatey працює коректно

```powershell
choco
```

- якщо побачимо список команд Chocolatey, то встановлення пройшло успішно
