# Prezentacja: Zastosowanie metod formalnych do weryfikacji struktur wskaźnikowych w systemie PVS

## Wymagania

Aby skompilować ten projekt LaTeX, potrzebujesz:
- **Linux** lub **Windows** z zainstalowanym środowiskiem LaTeX (np. TeX Live lub MikTeX).
- Edytor kodu **Visual Studio Code** z odpowiednimi wtyczkami.

### Wtyczki do Visual Studio Code
Zainstaluj następujące wtyczki w VS Code:
1. **LaTeX Workshop** - do obsługi LaTeX.
2. **Code Spell Checker** (opcjonalnie) - do sprawdzania pisowni.
3. **Polish - Code Spell Checker** (opcjonalnie) - do obsługi polskiej pisowni.

---

## Instrukcja kompilacji na Linuxie

1. **Zainstaluj TeX Live**:
   ```bash
   sudo apt update
   sudo apt install texlive-full
   pdflatex -synctex=1 -interaction=nonstopmode main.tex
   ```   

## Instrukcja kompilacji na Windowsie
1. **Zainstaluj MikTeX**:
   - Pobierz i zainstaluj MikTeX z [oficjalnej strony](https://miktex.org/download).
   - Upewnij się, że zaznaczone jest automatyczne pobieranie brakujących pakietów.
2. **Zainstaluj Visual Studio Code**:
   - Pobierz i zainstaluj Visual Studio Code z [oficjalnej strony](https://code.visualstudio.com/).
3. **Zainstaluj wtyczki**:
   - Otwórz Visual Studio Code.
   - Przejdź do zakładki "Extensions" (Ctrl+Shift+X).
   - Wyszukaj i zainstaluj wtyczki: **LaTeX Workshop**, **Code Spell Checker**, **Polish - Code Spell Checker**.
4. **Otwórz projekt**:
   - Otwórz folder projektu w Visual Studio Code.
5. **Kompilacja**:
   - Otwórz plik `main.tex`.
   - Naciśnij `Ctrl+Alt+B` lub wybierz "Build LaTeX project" z menu kontekstowego.
   - Po zakończeniu kompilacji, plik PDF zostanie wygenerowany w tym samym folderze co plik `.tex`.
6. **Podgląd PDF**:
   - Otwórz plik `main.pdf` w przeglądarce PDF lub użyj wbudowanego podglądu w LaTeX Workshop.
