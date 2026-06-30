# NPPDelphiFormatter

[PL] Opis w języku polskim znajduje się w dolnej części pliku.

---

## 🇬🇧 English Description

An intelligent, lightweight, and ultra-fast Delphi/Object Pascal code formatter plugin for Notepad++. Written in pure C, it processes code directly in RAM to ensure maximum performance.

### 🚀 Features
* **Smart Indentation:** Automatically manages code structure indentation (`begin/end`, `if-then-else`, `try-except-finally`).
* **Section Formatting:** Dedicated alignment rules for `uses`, `var`, `type`, `const`, and `label` blocks to keep your declarations neat.
* **OOP & Record Support:** Formats complex `class` definitions, visibility sections (`private`, `public`, etc.), and `record` structures beautifully.
* **Clean Code Mode:** Optional automatic removal of redundant empty lines (keeps a maximum of 1 consecutive empty line), preserving strings and multi-line comments.
* **Keyword Casing:** Automatically standardizes Delphi keyword casing according to your preferences.

### ⏱️ Usage & Shortcuts

| Action | Recommended Shortcut | Description |
| :--- | :--- | :--- |
| **Format Current File** | `Ctrl + Shift + F` | Instantly formats and cleans up the active Delphi source file. |

> ⚠️ **Note:** To use the formatter comfortably, you need to manually assign a keyboard shortcut for it. You can easily do this in Notepad++ via `Settings > Shortcut Mapper > Plugin commands`, then find **NPPDelphiFormatter** on the list and click **Modify**.

### 🛠️ Configuration
The plugin includes a configuration file (`DelphiFormatter.ini`) where you can customize its behavior:
* **IndentWidth:** Sets block indentation width (accepts values `2` to `4`, default: `2`).
* **WordStyle:** Style of delphi keys/directives (`1` = always lowercase (e.g. begin, procedure) `2` = first letter uppercase (e.g. Begin, Procedure)).
* **CleanCode:** Enables/disables empty line stripping (`1` = enabled, `0` = disabled).

Example `DelphiFormatter.ini`:
```ini
[Settings]
IndentWidth=2
WordStyle=1
CleanCode=1
```

### 📄 License
This project is licensed under the **MIT License** - see the `LICENSE` file for details.

---

## 🇵🇱 Opis po polsku

Inteligentna, lekka i niezwykle szybka wtyczka do programu Notepad++ służąca do formatowania kodu Delphi/Object Pascal. Napisana w czystym C, przetwarza kod bezpośrednio w pamięci RAM, zapewniając maksymalną wydajność.

### 🚀 Funkcje
* **Inteligentne wcięcia:** Automatycznie zarządza strukturą kodu i wcięciami dla bloków `begin/end`, `if-then-else` oraz `try-except-finally`.
* **Formatowanie sekcji:** Dedykowane reguły wyrównywania dla sekcji `uses`, `var`, `type`, `const` oraz `label`, które porządkują deklaracje.
* **Wsparcie dla OOP i Rekordów:** Precyzyjnie formatuje definicje klas (`class`), sekcje widoczności (`private`, `public` itp.) oraz struktury rekordów (`record`).
* **Tryb Clean Code:** Opcjonalne automatyczne usuwanie nadmiarowych pustych linii (zostawia maksymalnie jedną linię odstępu), w pełni bezpieczne dla stringów i komentarzy.
* **Standaryzacja wielkości liter:** Automatycznie ujednolica styl zapisu słów kluczowych Delphi.

### ⏱️ Użycie i skróty klawiszowe

| Akcja | Sugerowany skrót | Opis |
| :--- | :--- | :--- |
| **Formatuj bieżący plik** | `Ctrl + Shift + F` | Natychmiastowo formatuje i oczyszcza aktywny plik źródłowy Delphi. |

> ⚠️ **Uwaga:** Aby wygodnie korzystać z formatownika, należy ręcznie przypisać mu skrót klawiszowy. Zrobisz to w menu Notepad++: `Ustawienia > Zarządzaj skrótami... > Polecenia wtyczek`. Znajdź pozycję **NPPDelphiFormatter**, kliknij **Zmień** i ustaw swoją kombinację.

### 🛠️ Konfiguracja
Wtyczka posiada plik konfiguracyjny (`DelphiFormatter.ini`), w którym możesz dostosować jej działanie:
* **IndentWidth:** Szerokość podstawowego wcięcia bloków kodu (wartości od `2` do `4`, domyślnie: `2`).
* **WordStyle:** Styl kluczy/dyrektyw delphi (`1` =  zawsze małe litery (np. begin, procedure)  `2` = pierwsza litera duża (np. Begin, Procedure)).
* **CleanCode:** Włącza lub wyłącza oczyszczanie kodu z nadmiarowych pustych linii (`1` = włączone, `0` = wyłączone).

Przykład `DelphiFormatter.ini`:
```ini
[Settings]
IndentWidth=2
WordStyle=1
CleanCode=1
```

### 📄 Licencja
Ten projekt jest wydany na licencji **MIT** – szczegóły znajdziesz w pliku `LICENSE`.
