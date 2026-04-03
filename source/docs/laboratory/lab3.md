---
title: Lab 3
description: Laboratory Work 3
---

# Laboratory Work 3

!!! info "Lab Info"
    | | |
    |---|---|
    | 🗓️ **Date**   | 04/04/2026|
    | 👨‍💻 **Author** | Chu Ngoc Truong |
    | 🐙 **GitHub** |  |

---

## 🎯 Objective
Цель лабораторной работы — изучить библиотеку NumPy для численных вычислений и анализа данных.  
Я должен научиться работать с массивами, выполнять векторные и матричные операции, делать простой статистический анализ и строить графики.

---

## 📋 Task Description

<!-- Mô tả đề bài / yêu cầu của lab -->
CI/CD для статического сайта в SourceCraft (P3123)  

Основные задачи:
- Реализовать сценарий автоматического развёртывания статического сайта на MkDocs с использованием платформы SourceCraft
- Реализовать сценарий автоматического развёртывания того же сайта с помощью GitHub Actions
- В рамках одного локального репозитория добавить 2 удалённых репозитория (SourceCraft и GitHub)


---

## 💡 Solution

<!-- Trình bày hướng giải quyết, thuật toán, hoặc cách tiếp cận -->
Для выполнения задания был использован существующий проект MkDocs.

**SourceCraft:**
1. Создана публичная организация в SourceCraft
2. Создан репозиторий из шаблона `sites-landing`
3. Создан персональный токен доступа (PAT) с правами Maintainer
4. Файлы Node.js заменены на конфигурацию MkDocs
5. Настроен файл `.sourcecraft/ci.yaml` для автоматической сборки и публикации

**GitHub Actions:**
1. Создан репозиторий на GitHub
2. Настроен файл `.github/workflows/deploy.yml`
3. В настройках репозитория активирован хостинг из ветки `gh-pages`

**Оба удалённых репозитория добавлены в один локальный:**

---

## 💻 Code

Репозиторий SourceCraft: https://sourcecraft.dev/ngoctruong22/portfolio22
Репозиторий GitHub: https://github.com/ngoctruong22/ngoctruong_22.github.io

---

## 📊 Results

<!-- Kết quả chạy chương trình, ảnh chụp màn hình, hoặc output -->
Сайт на SourceCraft: https://ngoctruong22.sourcecraft.site/portfolio22

Репозиторий SourceCraft: https://sourcecraft.dev/ngoctruong22/portfolio22

Сайт на GitHub Pages: https://ngoctruong22.github.io

Репозиторий GitHub: https://github.com/ngoctruong22/ngoctruong_22.github.io

## 📝 Conclusion

<!-- Nhận xét, rút ra bài học sau khi hoàn thành lab -->
Я узнал:

1. Как настроить CI/CD пайплайн в SourceCraft с использованием файла `.sourcecraft/ci.yaml`
2. Как автоматически деплоить MkDocs сайт через GitHub Actions
3. Как добавить два удалённых репозитория в один локальный проект
4. Разницу между платформами SourceCraft и GitHub в подходе к CI/CD
5. Как работает автоматическая публикация статического сайта при каждом `git push`
---

<div style="display: flex; justify-content: space-between; margin-top: 2rem;" markdown>
[← Back to Lab 2](lab2.md){ .md-button }
[Lab 4 →](lab4.md){ .md-button .md-button--primary }
</div>