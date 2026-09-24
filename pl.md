---
layout: default
title: Polityka prywatności — Fastivo
lang: pl
---

[English version](en.html)

# Polityka prywatności aplikacji Fastivo

**Obowiązuje od:** 24 września 2026 · **Wersja:** 1.0

Ta polityka prywatności opisuje, jakie dane przetwarza aplikacja mobilna **Fastivo**
(Android: `pl.sakowicz.fastivo`) i co się z nimi dzieje.

## 1. Kto odpowiada za aplikację

Twórcą i wydawcą aplikacji jest **Dariusz Sakowicz** (osoba fizyczna, Polska),
widoczny w sklepie Google Play jako wydawca Fastivo.

Kontakt w sprawach prywatności: **d.sakowicz@gmail.com**

## 2. Najważniejsze w skrócie

- Fastivo **nie wymaga konta** ani logowania i **nie ma własnego serwera**.
- Wszystko, co wpisujesz w aplikacji (posty, waga, notatki, profil), jest zapisywane
  **wyłącznie na Twoim telefonie**. Twórca aplikacji **nie otrzymuje tych danych** i nie ma do nich dostępu.
- Aplikacja nie zawiera narzędzi analitycznych ani raportowania awarii.
- Jedyne zewnętrzne usługi, które przetwarzają dane, to **reklamy Google (AdMob)** i **sklep
  (Google Play, a w wersji na iOS — App Store)** przy zakupie „Usuń reklamy”.
  Dane o zdrowiu **nigdy** nie są przekazywane do tych usług.

## 3. Dane zapisywane na Twoim telefonie

Aplikacja zapisuje w lokalnej bazie danych na urządzeniu:

| Dane | Po co |
|---|---|
| Posty: początek, koniec, cel, status | timer postu, historia, statystyki, dni z rzędu |
| Notatki po poście: samopoczucie (1–5), czym przerwano post, powód, własna notatka | Twoje notatki i wnioski z nich |
| Pomiary wagi z porą dnia (rano/wieczór/inna) | wykresy i porównanie wagi |
| Profil (opcjonalny): płeć, wiek, wzrost, waga początkowa i docelowa, aktywność fizyczna, tempo odchudzania | BMI, zakres prawidłowej wagi, szacunkowe zapotrzebowanie kaloryczne |
| Dni z rzędu i dni wolne | licznik serii |
| Ustawienia: plan postu, przypomnienia, informacja o zakupie „bez reklam”, data akceptacji ostrzeżenia zdrowotnego | działanie aplikacji |

Część tych danych to **dane dotyczące zdrowia** (np. waga, samopoczucie, informacje o poście).
Są przetwarzane wyłącznie na Twoim urządzeniu, tylko po to, żeby aplikacja działała,
i nie są wysyłane nigdzie przez aplikację.

Wszystkie pola profilu są opcjonalne — bez nich aplikacja działa, ale nie pokaże wskaźników,
które ich wymagają.

## 4. Eksport i import danych

W Ustawieniach możesz wyeksportować swoje dane do pliku (JSON). Aplikacja otwiera wtedy
systemowe okno udostępniania, a **Ty wybierasz**, gdzie trafi plik (np. Twój dysk w chmurze
lub e-mail do siebie). Aplikacja niczego nie wysyła sama. Plik nie jest szyfrowany i zawiera
dane o zdrowiu — przechowuj go bezpiecznie i nie udostępniaj innym.

Import wczytuje taki plik i zastępuje dane zapisane w aplikacji.

## 5. Reklamy (Google AdMob)

Darmowa wersja Fastivo wyświetla reklamy dostarczane przez **Google AdMob** (Google Ireland
Limited / Google LLC): reklamy wideo, które sam(a) uruchamiasz, żeby otrzymać nagrodę
(np. dzień wolny), i najwyżej jedną reklamę pełnoekranową na sesję. Aplikacja nie wyświetla banerów.

Aby wyświetlić reklamę, zestaw SDK Google Mobile Ads przetwarza — według dokumentacji Google —
m.in.:

- **adres IP** (z którego można oszacować przybliżoną lokalizację),
- **identyfikator reklamowy urządzenia** (Android Advertising ID) i identyfikator zestawu aplikacji,
- **interakcje z reklamami** (np. wyświetlenia, kliknięcia, uruchomienie aplikacji),
- **informacje diagnostyczne** o działaniu aplikacji i SDK oraz ogólne informacje o urządzeniu.

Google wykorzystuje te dane do wyświetlania i mierzenia reklam, analityki oraz zapobiegania
oszustwom. Google jest w tym zakresie odrębnym administratorem danych. Szczegóły:
[Jak Google wykorzystuje informacje z witryn i aplikacji partnerów](https://policies.google.com/technologies/partner-sites?hl=pl)
oraz [Polityka prywatności Google](https://policies.google.com/privacy?hl=pl).

**Zgoda (EOG, Wielka Brytania, Szwajcaria).** Przed pierwszą reklamą aplikacja wyświetla
formularz zgody Google (UMP, standard IAB TCF). Jeśli nie zgodzisz się na reklamy
spersonalizowane, możesz otrzymywać reklamy niespersonalizowane (oparte np. na kontekście).
Swój wybór zmienisz w każdej chwili w aplikacji: **Ustawienia → Reklamy → Ustawienia prywatności reklam**.

**Identyfikator reklamowy** możesz zresetować lub usunąć w ustawieniach Androida
(Prywatność → Reklamy lub Google → Reklamy).

Reklamy są dostosowane do treści odpowiednich dla wszystkich (klasyfikacja maks. „PG”).

Po zakupie „Usuń reklamy” moduł reklam **w ogóle się nie uruchamia**, więc dane opisane
w tym punkcie nie są już przetwarzane.

## 6. Zakup „Usuń reklamy”

Jednorazowy zakup obsługuje **Google Play** (a w wersji na iOS **App Store**). Płatność
i dane rozliczeniowe przetwarza sklep zgodnie z własną polityką prywatności — twórca aplikacji
nie otrzymuje Twoich danych płatniczych. Aplikacja zapisuje na telefonie tylko informację,
że zakup został zrealizowany, i może ją przywrócić na podstawie Twojego konta w sklepie
(„Przywróć zakup”).

## 7. Powiadomienia

Przypomnienia (fazy postu, osiągnięcie celu, codzienne ważenie) są **planowane lokalnie na
telefonie**. Aplikacja nie korzysta z powiadomień push z serwera. Powiadomienia możesz wyłączyć
w aplikacji lub w ustawieniach telefonu.

## 8. Uprawnienia

- **Internet i stan sieci** — do reklam i obsługi zakupu.
- **Identyfikator reklamowy (AD_ID)** — do reklam (patrz pkt 5).
- **Płatności w Google Play (BILLING)** — do zakupu „Usuń reklamy”.
- **Powiadomienia, uruchamianie po restarcie, wybudzanie, wibracje** — do lokalnych przypomnień,
  także po ponownym uruchomieniu telefonu.

Aplikacja nie prosi o dostęp do lokalizacji, kontaktów, aparatu, mikrofonu, zdjęć ani plików.
Niektóre biblioteki dodają techniczne uprawnienia (np. do liczników na ikonie aplikacji),
z których Fastivo nie korzysta do zbierania danych.

## 9. Wersja na iOS

Gdy Fastivo będzie dostępne na iPhone'a, przed wyświetleniem reklam system zapyta o zgodę na
śledzenie (App Tracking Transparency). Aplikacja działa w pełni także bez tej zgody — reklamy są
wtedy niespersonalizowane. Pozostałe zasady tej polityki obowiązują bez zmian.

## 10. Przechowywanie i usuwanie danych

- Dane w aplikacji są przechowywane na telefonie, dopóki ich nie usuniesz. Pomiary wagi
  i trwający post możesz usuwać w aplikacji; **wszystkie dane** usuniesz, odinstalowując aplikację
  lub czyszcząc jej dane w ustawieniach Androida.
- Aplikacja nie tworzy kopii danych w chmurze. Kopię zapasową tworzysz sam(a) przez eksport (pkt 4).
- Ponieważ twórca nie przechowuje Twoich danych, nie ma czego usuwać po jego stronie.
- Dane przetwarzane przez Google w związku z reklamami i zakupami są przechowywane zgodnie
  z zasadami Google.

## 11. Bezpieczeństwo

Dane aplikacji leżą w prywatnym obszarze aplikacji na telefonie, do którego inne aplikacje nie
mają dostępu. Komunikacja SDK reklamowego i sklepu z serwerami Google jest szyfrowana (TLS).
Chroń telefon blokadą ekranu — każdy, kto ma dostęp do odblokowanego telefonu, może zobaczyć
dane w aplikacji.

## 12. Osoby niepełnoletnie

Fastivo jest przeznaczone **wyłącznie dla osób dorosłych (18+)**. Post przerywany nie jest
zalecany osobom poniżej 18 roku życia. Aplikacja nie jest kierowana do dzieci i świadomie nie
zbiera danych dzieci.

## 13. Twoje prawa (RODO)

Masz prawo do dostępu do danych, ich sprostowania, usunięcia, ograniczenia przetwarzania,
przenoszenia, sprzeciwu i wycofania zgody, a także prawo wniesienia skargi do Prezesa Urzędu
Ochrony Danych Osobowych (ul. Stawki 2, 00-193 Warszawa, [uodo.gov.pl](https://uodo.gov.pl)).

W praktyce: dane w aplikacji masz w pełni pod kontrolą — możesz je przeglądać, poprawiać,
eksportować (przenoszenie) i usuwać bezpośrednio w aplikacji. Zgodę na reklamy spersonalizowane
zmienisz w Ustawieniach (pkt 5). W sprawie danych przetwarzanych przez Google możesz też
skontaktować się bezpośrednio z Google. Z pytaniami pisz na adres z pkt 1.

Podstawy prawne: dane w aplikacji przetwarzasz Ty, na swoim urządzeniu, na potrzeby działania
aplikacji; przetwarzanie danych na potrzeby reklam odbywa się na podstawie Twojej zgody
(reklamy spersonalizowane) lub prawnie uzasadnionego interesu (reklamy niespersonalizowane,
zapobieganie oszustwom) — zgodnie z zasadami Google.

## 14. Przekazywanie danych poza EOG

Google może przetwarzać dane związane z reklamami i zakupami również poza Europejskim Obszarem
Gospodarczym, w tym w USA, na podstawie mechanizmów przewidzianych w RODO (np. EU-U.S. Data
Privacy Framework lub standardowych klauzul umownych).

## 15. Zmiany polityki

O istotnych zmianach poinformujemy w opisie aktualizacji aplikacji i na tej stronie.
Na górze strony zawsze widać datę obowiązywania aktualnej wersji.
