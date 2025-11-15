# Основные команды Git

## 1. `git init`
Инициализирует новый Git-репозиторий в текущей папке.
```bash
git init
mkdir my-project && cd my-project
git init
## 2. `git clone`
Клонирует репозиторий на локальную машину.
```bash
git clone https://github.com/user/repo.git
## 3. `git add`
Добавляет изменения в индекс.
```bash
git add README.md
## 4. `git commit`
Фиксирует изменения в репозитории.
```bash
git commit -m "Add new feature"
## 5. `git push`
Отправляет коммиты в репозиторий.```bash
git push origin main
## 6. `git pull`
Получает и объединяет изменения из репозитория.
```bash
git pull origin main
