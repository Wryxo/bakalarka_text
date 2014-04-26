LaTeX sablona pre Univerzitu Komenskeho.
==

Pouzitie:
```
xelatex -shell-escape  main.tex
bibtex main
xelatex -shell-escape  main.tex
xelatex -shell-escape  main.tex
```

Treba upravit `settings.tex`, `thanks.tex`, `abstracts.tex` a `contents.tex`.

Ak to chcete po anglicky treba prepnut babel v `main.tex` a upravit par nepevno zadanych textov.