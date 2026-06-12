---
title: Polityka Prywatności — Recupon
---

# Polityka Prywatności — Recupon

**Data wejścia w życie:** 13 czerwca 2026
**Ostatnia aktualizacja:** 13 czerwca 2026

**Deweloper:** Piotr Hołubowicz (Tiger AI Studio)
**Kontakt:** tigeraistudio@gmail.com

---

## 1. Wstęp

Niniejsza Polityka Prywatności opisuje, w jaki sposób aplikacja mobilna **Recupon**
(dalej: „Aplikacja") przetwarza dane użytkowników.

**Recupon nie zbiera żadnych danych osobowych.** Aplikacja działa w całości offline —
nie wymaga konta, rejestracji ani połączenia z naszymi serwerami. Wszystkie dane
pozostają wyłącznie na urządzeniu użytkownika.

## 2. Dane przechowywane lokalnie (wyłącznie na urządzeniu)

| Typ danych | Cel | Miejsce przechowywania |
|---|---|---|
| Kody kuponów kaucyjnych | Zarządzanie kuponami | Pamięć lokalna aplikacji |
| Kwoty i daty ważności | Wyświetlanie i przypomnienia | Pamięć lokalna aplikacji |
| Notatki do kuponów | Funkcja edycji | Pamięć lokalna aplikacji |
| Ustawienia aplikacji | Konfiguracja | Pamięć lokalna aplikacji |

Żadne z powyższych danych **nie są przesyłane na zewnętrzne serwery**, nie są
udostępniane osobom trzecim ani nie są wykorzystywane do celów reklamowych.

## 3. Uprawnienia aplikacji

| Uprawnienie | Cel | Wymagane |
|---|---|---|
| Aparat (CAMERA) | Skanowanie kodów kreskowych kuponów | Opcjonalne |
| Powiadomienia (POST_NOTIFICATIONS) | Przypomnienia o wygasających kuponach | Opcjonalne |
| Lokalizacja (ACCESS_FINE/COARSE_LOCATION) | Mapa recyklomatów w pobliżu | Opcjonalne |
| Internet (INTERNET) | Pobieranie danych mapy (OpenStreetMap) | Wymagane dla funkcji mapy |

Wszystkich uprawnień oznaczonych jako „Opcjonalne" można odmówić — Aplikacja będzie
działać z ograniczoną funkcjonalnością. Lokalizacja jest używana wyłącznie na żywo
do wyszukania recyklomatów w pobliżu i **nie jest zapisywana ani przesyłana** —
do usługi mapy trafia jedynie anonimowe zapytanie o punkty w okolicy.

## 4. Usługi zewnętrzne

- **OpenStreetMap / Overpass API** — pobieranie lokalizacji recyklomatów. Zapytania
  zawierają wyłącznie współrzędne obszaru wyszukiwania i nie zawierają żadnych danych
  osobowych. Połączenie jest szyfrowane (HTTPS). Polityka prywatności:
  https://wiki.osmfoundation.org/wiki/Privacy_Policy

Aplikacja **nie korzysta** z narzędzi analitycznych, śledzących ani reklamowych
(brak Google Analytics, Firebase Analytics, Facebook SDK itp.) i **nie wyświetla reklam**.

## 5. Dane dzieci

Aplikacja nie jest skierowana do dzieci poniżej 13. roku życia i świadomie nie zbiera
danych od takich osób (nie zbiera danych od nikogo).

## 6. Bezpieczeństwo danych

Dane kuponów przechowywane są w pamięci lokalnej aplikacji, w piaskownicy (sandbox)
systemu Android/iOS, niedostępnej dla innych aplikacji.

## 7. Kontrola nad danymi

Masz pełną, bezpośrednią kontrolę nad swoimi danymi:

- **Eksport:** *Ustawienia → Eksportuj kopię zapasową JSON* lub *Eksportuj raport PDF*
- **Usunięcie:** *Ustawienia → Wyczyść wszystkie dane* lub odinstalowanie aplikacji
- **Przeniesienie:** *Ustawienia → Importuj kopię zapasową* na nowym urządzeniu

## 8. Zmiany w Polityce Prywatności

O istotnych zmianach (np. wprowadzeniu opcjonalnych kont użytkownika w przyszłych
wersjach) poinformujemy poprzez aktualizację daty „Ostatnia aktualizacja" oraz
powiadomienie w Aplikacji. Funkcje wymagające przetwarzania danych osobowych zostaną
opisane w zaktualizowanej Polityce zanim trafią do użytkowników.

## 9. Kontakt

W sprawach dotyczących prywatności i danych:
E-mail: **tigeraistudio@gmail.com**
Deweloper: Piotr Hołubowicz (Tiger AI Studio)

---

*Niniejsza Polityka Prywatności jest dostępna w języku polskim.*
*This Privacy Policy is available in Polish.*

<!--
═══════════════════════════════════════════════════════════════════════════
ANEKS v1.1 (NIE PUBLIKOWAĆ w v1.0) — sekcje do dodania przy włączeniu kont
(ACCOUNTS_ENABLED=true w constants/features.ts):

Do §2 dodać tabelę "Dane konta (opcjonalne)": imię, e-mail, hash hasła (bcrypt),
data logowania — podstawa: art. 6 ust. 1 lit. b RODO; przechowywane do usunięcia
konta; usuwanie: Ustawienia → Konto → Usuń konto (natychmiastowe).
Do §4 dodać: serwer aplikacji (HTTPS).
Do §7 dodać prawa RODO: dostęp/sprostowanie/usunięcie/przenoszenie/sprzeciw/skarga
do UODO.
Pełna wersja tych sekcji: git log tego pliku (commit "Google Play compliance").
═══════════════════════════════════════════════════════════════════════════
-->
