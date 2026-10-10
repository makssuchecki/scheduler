# Plan zajęć

Prosty, minimalistyczny tygodniowy plan zajęć w jednym pliku HTML — bez instalacji i zależności.

## Uruchomienie

Otwórz `index.html` w przeglądarce.

## Funkcje

- **Dodawanie zajęć** — przyciskiem „Dodaj zajęcia” lub kliknięciem w pustą komórkę siatki (dzień i godzina uzupełniają się same).
- **Dane zajęć** — przedmiot, rodzaj (wykład / laboratorium / ćwiczenia / inne), prowadzący, sala, dzień, godziny, grupa, notatka.
- **Niestandardowe godziny** — dowolny czas z dokładnością do 5 minut (np. 11:35–14:00); siatka sama rozszerza się poza 8:00–18:00.
- **Zajęcia co 2 tygodnie** — oznaczenie tygodnia A/B i filtr wyróżniający wybrany tydzień.
- **Nakładające się zajęcia** — wyświetlane obok siebie.
- **Notatki** — notatki przypięte do zajęć zbierane w osobnej sekcji oraz pole na notatki ogólne.
- **Edycja / usuwanie** — kliknięcie w zajęcia otwiera formularz.
- Opcjonalna sobota, podświetlenie dzisiejszego dnia i linia bieżącej godziny.
- Jasny i ciemny motyw zgodny z ustawieniami systemu.

## Dane

Plan zapisuje się w `localStorage` przeglądarki — jest powiązany z konkretną przeglądarką i komputerem, a wyczyszczenie danych przeglądarki go usuwa.

Do kopii zapasowej i przenoszenia między urządzeniami służą przyciski **Eksportuj JSON** / **Importuj JSON** na dole strony.
