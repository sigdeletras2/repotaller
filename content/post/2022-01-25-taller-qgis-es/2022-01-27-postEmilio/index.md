---
title: Ejemplo para el taller 
subtitle: 
date: 2022-01-25T08:40:00.000Z
summary: Resumen del Taller
draft: false
featured: true
authors:
  - emilio-sanchez
tags:
  - QGIS
  - actividad
  - Git
categories:
  - Noticias
image:
  filename: featured.png
  focal_point: TOPRIGHT
  preview_only: true
---
Procesos Git (apuntes)

- IDENTIFICACION

    ```bash
    git config --global user.name "John Doe"
    git config --global user.email johndoe@example.com
    git config --list
    ```
- Controlar el estado 
    ```bash
    git status
    ```
- Añadir los archivos modificados o añadidos
    ```bash
    git add .
    ```
- identificar el envio para prepararlo
    ```bash
    git commit -m "PostEmilio commit"
    ```
- subir los añadidos al repositorio, sincronizar

    ```bash
    git push -u origin main
    ```

