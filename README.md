# Кристалл — установщик для Windows

Публичный канал скачивания программы **Кристалл** (Electron, Windows).

| | |
|---|---|
| **Последний релиз** | [Releases / latest](https://github.com/Vladimir-Vestnik/cristall-installer/releases/latest) |
| **Сборка** | `Cristall-ElectronBuilder-Setup-x.y.z.exe` |
| **Исходники приложения** | локально у разработчика (`CristallInstaller`), не в этом репозитории |

## Что скачивать

На странице Release прикреплены:

1. **Cristall-ElectronBuilder-Setup-*.exe** — установщик
2. **README.txt** — прочитайте **до** установки
3. **VIA_Zodiak_-_Polyot_k_zvyozdam.mp3** — рингтон (по желанию)

Прямая ссылка на установщик 1.0.0 (пример):

```
https://github.com/Vladimir-Vestnik/cristall-installer/releases/download/v1.0.0/Cristall-ElectronBuilder-Setup-1.0.0.exe
```

## Для разработчика: как опубликовать новую версию

1. В `CristallInstaller/ElectronCristall/package.json` — версия `x.y.z`.
2. `npm run build` → exe в `CristallInstaller/dist/`.
3. Обновить `release-bundle/README.txt` (номер версии в тексте).
4. Commit + push в этот репозиторий.
5. GitHub → **Releases** → новый тег `vx.y.z` → прикрепить exe, README.txt, mp3.

Подробнее: `CristallInstaller/docs/КАНАЛ_СКАЧИВАНИЯ_И_РУКОВОДСТВО_ПОЛЬЗОВАТЕЛЯ.md`.

## Связанные репозитории

- [cristall-relay](https://github.com/Vladimir-Vestnik/cristall-relay) — скрипт relay-сервера
