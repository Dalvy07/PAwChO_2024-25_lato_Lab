# PAwChO_2024-25_lato_Lab
# Author - Vladyslav Liulka
# Lab5 Instrukcja uruchomienia kontenera

## 1. Budowanie  i uruchomienie obrazu
Po pobraniu projektu w głównym katalogu uruchom (w PowerShell/CMD/Bash):

```bash
docker build -t zadanie-lab5 --build-arg APP_VERSION=2.3.4 .

```bash
docker run -d -p 8080:80 --name kontener-lab5 zadanie-lab5
