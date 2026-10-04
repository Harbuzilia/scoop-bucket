# Scoop bucket for Puryx

[Scoop](https://scoop.sh/) bucket for [Puryx](https://github.com/Harbuzilia/Puryx) — умная очистка и оптимизация Windows / smart Windows cleaner and optimizer.

## Установка / Install

Добавьте бакет и установите Puryx / Add the bucket and install Puryx:

```powershell
scoop bucket add puryx https://github.com/Harbuzilia/scoop-bucket
scoop install puryx
```

Или установите напрямую из манифеста / Or install straight from the manifest:

```powershell
scoop install https://raw.githubusercontent.com/Harbuzilia/scoop-bucket/main/bucket/puryx.json
```

## Приложения / Apps

| Manifest | Description | Version |
|----------|-------------|---------|
| [`puryx`](bucket/puryx.json) | Умная очистка и оптимизация Windows: 16 сканеров, безопасное удаление, NTFS Compact, приватность / Smart Windows cleaner and optimizer | [3.0.0](https://github.com/Harbuzilia/Puryx/releases/tag/v3.0.0) |

## Обновление / Update

Манифест содержит `checkver` (GitHub releases) и `autoupdate`, поэтому при выпуске новой версии Puryx обновляется одной командой:

```powershell
scoop update puryx
```

## Лицензия / License

Puryx распространяется по лицензии [MIT](https://github.com/Harbuzilia/Puryx). Манифесты этого бакета — MIT.
