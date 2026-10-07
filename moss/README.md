# Moss — Mobile Web Prototype

Статичен сайт (чист HTML/CSS/JS, без build стъпка).

```
index.html
assets/img/      # изображения (извлечени от оригиналния single-file прототип)
vercel.json      # кеш + security headers
```

## Локално
```bash
npx serve .
```

## Deploy (GitHub → Vercel)
1. Push към GitHub.
2. vercel.com → Add New → Project → Import репото.
3. Framework Preset: **Other**; Build Command: празно; Output Directory: празно (root).
4. Deploy. Всеки push към `main` деплойва автоматично.
