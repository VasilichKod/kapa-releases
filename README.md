# КАПА Releases

Публичное хранилище файлов обновления КАПА.

Здесь не должно быть исходного кода, приватных ключей или `.env` файлов.

## Что можно публиковать

```text
latest.json
v0.1.1/
  kapa-windows-x64-setup.exe
  kapa-windows-x64-setup.exe.sig
  kapa-macos-aarch64.dmg
  kapa-macos-aarch64.app.tar.gz
  kapa-macos-aarch64.app.tar.gz.sig
```

## Что нельзя публиковать

```text
kapa-update.key
kapa-update.key.pub
kapa-update.env
исходники проекта
архив рабочей папки проекта
```

`latest.json` лежит в корне репозитория, потому что приложение смотрит сюда:

```text
https://raw.githubusercontent.com/VasilichKod/kapa-releases/main/latest.json
```
