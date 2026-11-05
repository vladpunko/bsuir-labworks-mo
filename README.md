### Лабораторные работы по курсу: машинное обучение

[![Made With Python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org)
[![Сommon Size](https://img.shields.io/github/repo-size/vladpunko/bsuir-labworks-mo)](https://github.com/vladpunko/bsuir-labworks-mo)

Реализация лабораторных работ с дополнительными оптимизациями по предмету машинного обучения в магистратуре кафедры Информатики в Белорусском Государственном Университете Информатики и Радиоэлектроники.

### Установка и запуск

Для управления окружением и зависимостями используется [uv](https://docs.astral.sh/uv/getting-started/installation/).

```bash
# Клонирование данного репозитория.
git clone https://github.com/vladpunko/bsuir-labworks-mo && cd ./bsuir-labworks-mo

# Создание виртуального окружения и установка зависимостей.
uv sync

# Запуск сервера для разработки.
uv run jupyter notebook --notebook-dir="$PWD"
```
