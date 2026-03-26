# ПП «КОМПАНІЯ УНІТРАНС» — сайт-візитівка

Ця папка містить окремий статичний сайт, який можна винести в окремий GitHub-репозиторій і публікувати через GitHub Pages / Netlify / Cloudflare Pages.

## Структура
- `index.html`
- `styles.css`

## Як створити окремий GitHub-репозиторій і завантажити сайт

```bash
cd untrans-business-card
git init
git add .
git commit -m "Initial commit: UNITRANS business card website"

# Варіант через GitHub CLI (потрібен login: gh auth login)
gh repo create untrans-business-card --public --source=. --remote=origin --push
```

## Публікація через GitHub Pages
1. Відкрити репозиторій на GitHub.
2. Settings → Pages.
3. Build and deployment: `Deploy from a branch`.
4. Branch: `main` + `/ (root)`.
5. Зберегти, дочекатися публікації.
