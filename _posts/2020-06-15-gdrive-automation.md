---
title: Обслуживание папок в Google Drive
tags: [python, airflow, google drive api]
---


👨‍🏫 задача: настроить автоматическую уборку в папка Google Drive

🤕 проблема: у компании есть несколько папок, в которых ведется текущая работа. Эти папки со временем становятся завалены хламом и в них трудно что-то найти.

😎 решение: сделать робота, который будет прибираться регулярно, как робот пылесос.

Каждый день робот берет файлы, старше одного месяца и переносит из текущей папки с заказами в архивную папку. Название архивной папки состоит из года и месяца создания файла.

🤓 технологии: Python, Airflow, Google Drive API
