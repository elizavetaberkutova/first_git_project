
# Завдання 2. Перший репозиторій

## Мета роботи
Навчитися створювати Git-репозиторій.

## Команди Git

### 1. Створення папки
```bash
mkdir first_git_project
```

### 2. Перехід до папки
```bash
cd first_git_project
```

### 3. Ініціалізація Git
```bash
git init
```

### 4. Перевірка стану
```bash
git status
```

## Результат виконання

Після створення репозиторію Git показав:

```text
On branch master
No commits yet
nothing to commit
```

Після цього створено перший коміт,
а проєкт завантажено на GitHub.

## Висновок
Завдання виконано успішно!


## Додаткові команди Git

### 5. Додавання файлу
```bash
git add main.py
```

### 6. Створення коміту
```bash
git commit -m "Add main file"
```

### 7. Перегляд історії комітів
```bash
git log --oneline
```

## Результат
Файл main.py додано до репозиторію.
Створено новий коміт.
Перевірено історію комітів.


## Завдання 4. Другий коміт

### 1. Зміна файлу main.py

Додано новий рядок:

```python
print("Git saves project history")
```

### 2. Перегляд змін

```bash
git diff
```

### 3. Додавання файлу

```bash
git add main.py
```

### 4. Створення коміту

```bash
git commit -m "Update program output"
```

### 5. Перегляд історії

```bash
git log --oneline
```

### Результат

Файл main.py змінено.
Створено новий коміт Update program output.
Історію комітів перевірено.


