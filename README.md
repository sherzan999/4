# Бричка — демо-сайт

> **Демо-версия.** Это прототип, а не официальный сайт организации. Он будет удалён по первой просьбе владельца. Данные и фото взяты из публичной карточки на Яндекс Картах (23.11.2026), права на них принадлежат владельцам.

- Организация: Бричка, Бобруйск, микрорайон Авиагородок
- Карточка: https://yandex.by/maps/-/CXc6iS8T
- Сайт: один файл `index.html` (React + Framer Motion + Tailwind через CDN, сборка не нужна)
- Данные карточки: `data.json`; фото подгружаются ссылками с серверов Яндекса, не как фон

## Публикация на GitHub Pages

```bash
git init && git add . && git commit -m "Демо-сайт Бричка"
git branch -M main
git remote add origin https://github.com/<user>/brichka.git
git push -u origin main
```

Затем: Settings → Pages → Deploy from a branch → `main` / `(root)`.
Адрес: `https://<user>.github.io/brichka/`
