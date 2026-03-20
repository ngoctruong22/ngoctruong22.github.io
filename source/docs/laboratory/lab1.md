---
title: Lab 1
description: Laboratory Work 1
---

# Laboratory Work 1

!!! info "Lab Info"
    | | |
    |---|---|
    | 🗓️ **Date**   | 07/03/2026|
    | 👨‍💻 **Author** | Chu Ngoc Truong |
    | 🐙 **GitHub** | [View source code](https://github.com/ngoctruong22/ngoctruong22.github.io) |

---

## 🎯 Objective

+ Освоить процесс создания статического сайта с использованием генератора документации MkDocs. 
+ Научиться организовывать структуру документации проекта (портфолио лабораторных работ). 
+ Изучить базовые принципы работы с системой контроля версий Git и платформой GitHub. Развернуть статический сайт с использованием механизма GitHub Pages на домене вида username.github.io. 
+ Освоить базовую настройку темы оформления и конфигурационного файла mkdocs.yml.

---

## 📋 Task Description

<!-- Mô tả đề bài / yêu cầu của lab -->
Основные задачи работы:

+ создать публичный репозиторий на платформе GitHub для размещения сайта;

+ настроить механизм публикации сайта с использованием GitHub Pages;

+ установить и настроить инструмент MkDocs для генерации статического сайта;

+ организовать структуру документации проекта;

+ создать несколько страниц сайта (главная страница, страница «Об авторе», раздел лабораторных работ);

+ настроить конфигурационный файл mkdocs.yml, включая название сайта, тему оформления и структуру навигации;

+ выполнить сборку сайта и опубликовать его в сети Интернет.

Результатом выполнения лабораторной работы должен стать опубликованный статический сайт, доступный по адресу вида username.github.io.

---

## 💡 Solution
<!-- Trình bày hướng giải quyết, thuật toán, hoặc cách tiếp cận -->
+ В процессе работы я следовал структуре, которую преподаватель показал на занятии. Для настройки проекта я использовал искусственный интеллект Claude, который помог мне правильно написать файл mkdocs.yml, а также добавить и оформить необходимые разделы в навигации (nav). Благодаря этому я смог быстро разобраться в синтаксисе и избежать типичных ошибок при конфигурации.

---

## 💻 Code

```Bash
# Create virtual environment
python -m venv venv

# Activate virtual environment
venv\Scripts\activate

# Install MkDocs
pip install mkdocs

# Create new MkDocs project
mkdocs new source

# Run local development server
mkdocs serve

# Build static site
mkdocs build -d ../docs

# Commit and push changes to GitHub
git add .
git commit -m ""
git push
```

---

## 📊 Results

<!-- Kết quả chạy chương trình, ảnh chụp màn hình, hoặc output -->
 ***url: https://ngoctruong22.github.io***

---

## 📝 Conclusion
<!-- Nhận xét, rút ra bài học sau khi hoàn thành lab -->
+ *Наконец, я успешно выполнил публикацию готового проекта в интернете. Я убедился, что для размещения статического сайта не нужен "тяжелый" сервер с бэкендом: достаточно использовать специальные сервисы (такие как GitHub Pages), которые обслуживают готовые файлы напрямую.*

---

<div style="display: flex; justify-content: space-between; margin-top: 2rem;" markdown>
[← Back to Overview](index.md){ .md-button }
[Lab 2 →](lab2.md){ .md-button .md-button--primary }
</div>