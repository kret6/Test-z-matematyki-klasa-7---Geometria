# 📐 Asystent Nauki: Matematyka (Klasa 7)

Interaktywna aplikacja webowa stworzona, aby wspierać naukę geometrii i matematyki. Projekt powstał z myślą o uczniach, dla których tradycyjne pisanie i rysowanie jest barierą (np. z MPD), pozwalając skupić się na **logice, wzorach i myśleniu matematycznym**.

> **"Nie musisz pisać, żeby być świetnym z matematyki."**

## 🚀 Jak to działa?
Aplikacja jest dostępna w przeglądarce (telefon/tablet/komputer).
* **Zero pisania:** Cała obsługa opiera się na klikaniu.
* **System Podpowiedzi:** Przycisk "💡 Potrzebuję koła ratunkowego" pozwala podejrzeć wzór bez stresu przed oceną.
* **Wsparcie wizualne:** Zadania geometryczne oparte są o czytelne schematy i rysunki.
* **Losowość:** Pytania i odpowiedzi są mieszane przy każdym uruchomieniu.

## 🔗 Link do aplikacji
https://kret6.github.io/Test-z-matematyki-klasa-7---Geometria/

## 🛠️ Instrukcja dla Administratora

### 1. Jak dodać nowe pytanie?
Otwórz plik .html i znajdź sekcję "const rawQuestions". Dodaj nowy blok według schematu:

    {
        q: "Treść pytania", 
        imgSrc: "nazwa_pliku.jpg", // lub null, jeśli brak obrazka
        hint: "Podpowiedź (wzór)",
        a: ["Poprawna Odp", "Zła 1", "Zła 2", "Zła 3"],
        correct: 0 // ZAWSZE zostawiamy 0, skrypt sam pomiesza odpowiedzi
    },

### 2. Jak dodać obrazek?
1. Wytnij fragment zadania (np. Narzędziem Wycinanie).
2. Zapisz jako .jpg (bez spacji w nazwie, np. zad15.jpg).
3. Wgraj plik do repozytorium na GitHubie.
4. Wpisz nazwę pliku w polu "imgSrc".

### 3. Polskie znaki (Krzaczki)
Jeśli zamiast "ą, ę" widzisz dziwne symbole:
* Otwórz plik w Notepad++.
* Wybierz z menu: Format -> Konwertuj na format UTF-8.
* Zapisz i wgraj ponownie.

## 📚 Technologie
* HTML5 & CSS3 - Struktura i wygląd.
* Vanilla JavaScript - Logika quizu.
* Prywatność - Brak śledzenia i reklam.

---
*Stworzono z ❤️ dla Julii.*
