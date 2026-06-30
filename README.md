# NPPDelphiFormatter

# Delphi-style Formatter for Notepad++

An intelligent, lightweight, and ultra-fast Delphi/Object Pascal code formatter plugin for Notepad++. Written in pure C, it processes code directly in RAM to ensure maximum performance.

Inteligentna, lekka i niezwykle szybka wtyczka do Notepad++ służąca do formatowania kodu Delphi/Object Pascal. Napisana w czystym C, przetwarza kod bezpośrednio w pamięci RAM, zapewniając maksymalną wydajność.

---

## English Description

### Features
* **Smart Indentation**: Automatically manages code structure indentation (`begin/end`, `if-then-else`, `try-except-finally`).
* **Section Formatting**: Dedicated alignment rules for `uses`, `var`, `type`, `const`, and `label` blocks.
* **OOP Support**: Formats complex `class` definitions, visibility sections (`private`, `public`, etc.), and `record` structures.
* **Clean Code Mode**: Optional automatic removal of redundant empty lines (keeps maximum 1 consecutive empty line), preserving strings and multi-line comments.
* **Keyword Casing**: Standardizes Delphi keyword casing.

### Configuration (`DelphiFormatter.ini`)
The plugin configuration file should be placed in the plugin directory.
* `IndentWidth`: Sets block indentation width (accepts values `2` to `4`, default: `2`).
* `WordStyle`: Style of delphi keys/directives (`1` = always lowercase (e.g. begin, procedure) `2` = first letter uppercase (e.g. Begin, Procedure)).
* `CleanCode`: Enbles/disables empty line stripping (`1` = enabled, `0` = disabled).

Example:
```ini
[Settings]
IndentWidth=2
WordStyle=1
CleanCode=1
```

### How to Use & Shortcuts
To use the formatter comfortably, you should assign a keyboard shortcut to it:
1. Open Notepad++ and go to **Settings** -> **Shortcut Mapper...**
2. Switch to the **Plugin commands** tab.
3. Find **NPPDelphiFormatter** in the list.
4. Click **Modify** and assign your preferred shortcut (e.g., `Ctrl + Shift + F`).

---

## Opis po Polsku

### Funkcje
* **Inteligentne wcięcia**: Automatycznie zarządza strukturą kodu i wcięciami dla bloków `begin/end`, `if-then-else` oraz `try-except-finally`.
* **Formatowanie sekcji**: Dedykowane reguły wyrównywania dla sekcji `uses`, `var`, `type`, `const` oraz `label`.
* **Wsparcie dla OOP**: Precyzyjnie formatuje definicje klas (`class`), sekcje widoczności (`private`, `public` itp.) oraz rekordy (`record`).
* **Tryb Clean Code**: Opcjonalne automatyczne usuwanie nadmiarowych pustych linii (zostawia maksymalnie jedną linię odstępu), w pełni bezpieczne dla stringów i komentarzy wielolinijkowych.
* **Standaryzacja wielkości liter**: Ujednolica styl zapisu słów kluczowych Delphi.

### Konfiguracja (`DelphiFormatter.ini`)
Plik konfiguracyjny powinien znajdować się w katalogu wtyczki.
* `IndentWidth`: Szerokość podstawowego wcięcia bloków kodu (wartości od `2` do `4`, domyślnie: `2`).
* `WordStyle`: Styl kluczy/dyrektyw delphi (`1` =  zawsze małe litery (np. begin, procedure)  `2` = pierwsza litera duża (np. Begin, Procedure)).
* `CleanCode`: Włącza/wyłącza czyszczenie pustych linii (`1` = włączone, `0` = wyłączone).

Przykład:
```ini
[Settings]
IndentWidth=2
WordStyle=1
CleanCode=1
```

### Jak używać i skróty klawiszowe
Aby wygodnie korzystać z formatownika, zaleca się przypisanie własnego skrótu klawiszowego:
1. Otwórz Notepad++ i przejdź do **Ustawienia** -> **Zarządzaj skrótami...**
2. Przełącz się na zakładkę **Polecenia wtyczek** (Plugin commands).
3. Znajdź na liście pozycję **NPPDelphiFormatter**.
4. Kliknij **Zmień** (Modify) i ustaw wygodną kombinację klawiszy (np. `Ctrl + Shift + F`).
