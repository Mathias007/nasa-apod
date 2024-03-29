# NASA APOD (NASA APOD)

Zbudowany w HTML, CSS i Javascript responsywny projekt wykorzystujący **NASA APOD API** do prezentowania zdjęć z kosmosu z ich opisami z możliwością zapisywania i usuwania przez użytkownika ulubionych w `localStorage`.

## Opis

Aplikacja pobiera do tablicy obiektów (`fetch()`), a następnie wizualizuje (`DOM`) dane z **NASA APOD API**. Pobrane grafiki są prezentowane wraz ze swym opisem i metadanymi w ramach kolejnych elementów (kart). Na okres ładowania strony wyświetla się `loader` w postaci `animacji wektorowej`.
Istnieje możliwość odawania obrazów do ulubionych (**Add to Favorites**). Obiekt zawierający dane ulubionych grafik użytkownika jest zapisywany w `localStorage` i dostępny w sekcji **Favorites**. Przycisk **Load More** przeładowuje z kolei obrazy, prezentując nowy zestaw.

## Zastosowanie i plany rozwoju

Projekt jest w pełni `responsywny`. Jego struktura i logika mogą zostać użyte do prezentacji newsó na stronie czy też wpisów społeczności. Równolegle aplikacja prezentuje wycinek możliwości udostępnionych przez NASA API, z użyciem których możliwe jest stworzenie mniej lub bardziej zaawansowanych projektów.

Preview dostępne [na serwerze własnym (eGildia Graczy)](https://egildia.pl/projects/nasa-apod/)
