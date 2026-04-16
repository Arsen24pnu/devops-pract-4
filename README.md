![CI Status](https://github.com/Arsen24pnu/devops-pract-4/actions/workflows/ci.yml/badge.svg)
## CI/CD Пайплайн
У цьому репозиторії налаштовано GitHub Actions для автоматизації:
* [cite_start]**Тригери:** Запускається при кожному `push` або `pull request` у гілку `main`[cite: 23, 30].
* [cite_start]**Кроки:** 1. **Checkout:** Копіювання коду в середовище[cite: 33].
  2. [cite_start]**Install:** Встановлення залежностей[cite: 36].
  3. [cite_start]**Lint:** Перевірка якості коду (Linter)[cite: 46].
  4. [cite_start]**Test:** Автоматичний запуск тестів[cite: 39].
