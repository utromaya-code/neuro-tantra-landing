# Загрузка на GitHub Pages (3 шага)

Репозиторий в папке уже инициализирован, коммит сделан. Осталось создать репозиторий на GitHub и выполнить две команды.

## 1. Создайте репозиторий на GitHub

1. Откройте **https://github.com/new**
2. **Repository name:** `neuro-tantra-landing` (или любое имя)
3. **Public**
4. **НЕ** ставьте галочки «Add a README» / «Add .gitignore» — репозиторий должен быть пустым
5. Нажмите **Create repository**

## 2. Подключите remote и запушьте

В терминале перейдите в папку лендинга и выполните (подставьте **ВАШ_ЛОГИН** вместо `YOUR_USERNAME`):

```bash
cd "/Users/poslednijgeroj/Library/Mobile Documents/com~apple~CloudDocs/neuro-tantra-landing"

git remote add origin https://github.com/YOUR_USERNAME/neuro-tantra-landing.git
git push -u origin main
```

Если GitHub попросит логин/пароль — используйте **Personal Access Token** вместо пароля (Settings → Developer settings → Personal access tokens). Либо настройте SSH и используйте адрес `git@github.com:YOUR_USERNAME/neuro-tantra-landing.git`.

## 3. Включите GitHub Pages

1. В репозитории на GitHub: **Settings** → слева **Pages**
2. **Source:** Deploy from a branch
3. **Branch:** `main` → папка **/ (root)** → **Save**

Через 1–2 минуты сайт откроется по адресу:

**https://YOUR_USERNAME.github.io/neuro-tantra-landing/**
