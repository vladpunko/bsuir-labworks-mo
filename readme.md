### Лабораторные работы по курсу: машинное обучение

[![Made With Python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org)
[![Сommon Size](https://img.shields.io/github/repo-size/vladpunko/bsuir-labworks-mo)](https://github.com/vladpunko/bsuir-labworks-mo)

Реализация лабораторных работ с дополнительными оптимизациями по предмету машинного обучения в магистратуре кафедры Информатики в Белорусском Государственном Университете Информатики и Радиоэлектроники.

### Установка и запуск

```bash
# Клонирование данного репозитория.
git clone https://github.com/vladpunko/bsuir-labworks-mo && cd ./bsuir-labworks-mo

# Активация виртуального окружения.
python3 -m venv .venv && source ./.venv/bin/activate

# Установка зависимостей репозитория.
pip3 install -r requirements.txt

# Запуск сервера для разработки.
jupyter notebook --notebook-dir="$PWD"
```
