# Инструкция по сборке

## Зависимости:

```sh
sudo apt update
sudo apt install texlive-full
```

## Сборка:

```sh
pdflatex --shell-escape -interaction nonstopmode report.tex
```
