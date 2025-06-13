# Pytania na kolokwium z mechaniki kwantowej

Repozytorium zawiera zestaw pytań do kolokwium z przedmiotu "Podstawy mechaniki kwantowej" w formacie LaTeX. Główny plik [`Pytania.tex`](Pytania.tex) automatycznie dołącza pliki [`Lista1.tex`](Lista1.tex) oraz [`Lista2.tex`](Lista2.tex) za pomocą polecenia `\input`.

## Kompilacja

Aby wygenerować plik PDF z pytaniami, należy użyć kompilatora `pdflatex`. W terminalu (w katalogu z plikami) wykonaj:

```sh
pdflatex Pytania.tex
```

W razie potrzeby komendę można powtórzyć, aby poprawnie wygenerować spis treści i odnośniki.

**Wymagania:**  
Do kompilacji potrzebny jest zainstalowany system LaTeX (np. TeX Live, MikTeX lub MacTeX).
