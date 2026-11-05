# Лабораторные работы по машинному обучению

[![Made With Python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org)
[![Repository size](https://img.shields.io/github/repo-size/vladpunko/bsuir-labworks-mo)](https://github.com/vladpunko/bsuir-labworks-mo)

Лабораторные работы по машинному обучению с дополнительными оптимизациями, выполненные в магистратуре кафедры информатики БГУИР.

[Задания к лабораторным работам](ASSIGNMENTS.pdf).

## Установка и запуск

Для установки зависимостей и запуска ноутбуков используется [uv](https://docs.astral.sh/uv/getting-started/installation/).

```bash
# Клонирование репозитория.
git clone https://github.com/vladpunko/bsuir-labworks-mo && cd ./bsuir-labworks-mo

# Создание виртуального окружения и установка зависимостей.
uv sync --locked

# Запуск Jupyter Notebook.
uv run jupyter notebook --notebook-dir="${PWD}"
```
