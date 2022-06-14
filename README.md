## Что это?
Это отчёт по ознакомительной практике 1 курса, содержащий формализованные знания по двум аттестационным вопросам:
 - Библиотека многократно используемых компонентов (30 вопрос)
 - Интерфейсы интеллектуальных систем (29 вопрос)

Заранее предупреждаю, что скопировать отчёт и сдать его под видом своего вряд ли получится :)
Но можете использовать в качестве примера того, что нужно делать.

[Ссылочка на Стандарт OSTIS](https://github.com/ostis-ai/ostis-standard)

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
