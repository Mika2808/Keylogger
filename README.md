# Keylogger
Projekt implementuje keylogger dla systemów Windows 10/11, który przechwytuje i zapisuje kody klawiszy (Make Codes) do pliku tekstowego. Do realizacji wykorzystano zmodyfikowany sterownik kbfiltr, udostępniany przez Microsoft, co pozwala na niskopoziomowe przechwytywanie danych z klawiatury.

Dodatkowo, w ramach projektu powstała prostsza wersja keyloggera w Pythonie, działająca na wyższym poziomie abstrakcji.

# Funkcjonalności
- Przechwytywanie Make Codes klawiatury
- Zapisywanie przechwyconych danych do pliku tekstowego
- Działanie w tle bez ingerencji w inne procesy
- Wersja w C++ wykorzystująca sterownik kbfiltr
- Alternatywna wersja w Pythonie
