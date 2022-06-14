## Overleaf
Ссылка на проект на Overleaf: [*тык*](https://www.overleaf.com/read/bhfxbpctkbsw)

## Инструкция по сборке (Ubuntu)

### Зависимости:

```sh
sudo apt update
sudo apt install texlive-full
```

### Сборка:

```sh
git clone https://github.com/ungaf/junior-practice
cd junior-practice
pdflatex --shell-escape -interaction nonstopmode report.tex
```
