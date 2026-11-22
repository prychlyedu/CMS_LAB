Mini Projekt MP1 — Pedal & Co. (Serwis Rowerowy)

1. Opis fikcyjnej firmy (Karta MP1)
* **Nazwa firmy:** Pedal & Co. – Serwis i Spa Rowerowe
* **Branża:** Lokalne usługi serwisowe i konserwacja rowerów (szosowe, gravel, MTB, miejskie oraz e-bike).
* **Oferta:** Przeglądy okresowe (podstawowy i kompleksowy), centrowanie kół, serwis amortyzatorów i hamulców hydraulicznych, diagnostyka napędów elektrycznych oraz usługa „Door-to-Door” (odbiór i zwrot roweru od klienta).
* **Grupa docelowa:** Mieszkańcy dużego miasta i okolic dojeżdżający rowerem do pracy (commuterzy) oraz amatorzy kolarstwa szosowego i MTB szukający rzetelnego, terminowego serwisu z przejrzystym cennikiem.

---

2. Persony użytkowników

Persona 1: Marek Kowalski (34 lata) — Kolarz amator (Gravel / Szosa)
* **Cel:** Przygotować rower gravelowy przed startem w wiosennym ultramaratonie (odpowietrzenie hamulców, wymiana napędu, regulacja przerzutek) i zarezerwować konkretny termin bez czekania w kolejce.
* **Problem:** W sezonie wiosennym lokalne serwisy mają odległe terminy, nie odbierają telefonów i nie podają orientacyjnych kosztów przed oddaniem roweru.
* **Urządzenie:** Laptop (wieczorem w domu — przegląda dokładny zakres pakietów serwisowych i cennik) oraz smartfon (szybki kontakt / dojazd).
* **Oczekiwana akcja (CTA):** Wysłanie zgłoszenia rezerwacji terminu przez formularz na podstronie *Kontakt* („Umów serwis”).

Persona 2: Anna Nowak (28 lat) — Rowerzystka miejska (Commuter)
* **Cel:** Szybko naprawić przebitą dętkę i wyregulować hamulce w rowerze miejskim, którym codziennie dojeżdża do biura.
* **Problem:** Nie zna się na terminologii technicznej, potrzebuje szybkiej informacji o godzinach otwarcia, lokalizacji warsztatu lub możliwości odbioru roweru spod domu.
* **Urządzenie:** Smartfon (szuka serwisu w drodze do pracy lub w przerwie).
* **Oczekiwana akcja (CTA):** Szybkie sprawdzenie pakietu podstawowego i wysłanie zapytania lub kliknięcie numeru telefonu/adresu w stopce.

---

3. Mapa strony (Sitemap — 6 podstron, maks. 2 poziomy)

1. **Strona główna** (`/`) — Sekcja Hero z H1 i CTA „Umów serwis”, 3 główne pakiety usług, opinie klientów.
2. **O nas** (`/o-nas/`) — Historia warsztatu Pedal & Co., zespół mechaników, standardy pracy i używane narzędzia.
3. **Oferta i cennik** (`/oferta/`) — Szczegółowy zakres przeglądów (Pakiet Miejski, Pakiet Pełny, Serwis E-Bike) + usługa Door-to-Door.
4. **Aktualności** (`/aktualnosci/`) — Poradnik rowerowy i komunikaty sezonowe (wpisy podzielone na kategorie: *Porady serwisowe* oraz *Życie warsztatu*).
5. **Kontakt** (`/kontakt/`) — Formularz rezerwacji terminu (Contact Form 7), godziny otwarcia, adres i dane kontaktowe.
6. **Polityka prywatności** (`/polityka-prywatnosci/`) — Informacje o przetwarzaniu danych osobowych (RODO) i plikach cookies.

---

4. Uzasadnienie wyboru systemu CMS (WordPress)
Według danych W3Techs (październik 2026) WordPress napędza 40,2% wszystkich witryn w internecie i posiada 58,7% udziału w rynku CMS, co gwarantuje długoterminowe wsparcie, bezpieczeństwo oraz łatwe przekazanie panelu redakcyjnego pracownikom warsztatu bez uzależnienia od dostawcy (vendor lock-in), w przeciwieństwie do zamkniętych platform SaaS takich jak Wix (6,1%)[cite: 11, 13]. Dla lokalnego serwisu usługowego Pedal & Co., który nie prowadzi rozbudowanego sklepu internetowego, platforma e-commerce taka jak Shopify (7,8%) generowałaby zbędne koszty abonamentowe, natomiast wdrożenie korporacyjnego Drupala (0,6%) byłoby nieproporcjonalnie drogie i czasochłonne[cite: 11, 13]. WordPress w modelu self-hosted pozwala wykorzystać lekki motyw blokowy (Full Site Editing), własne wzorce sekcji oraz darmową wtyczkę formularzy (Contact Form 7), zachowując pełną kontrolę nad danymi i optymalizacją pod kątem dostępności WCAG 2.2[cite: 1, 7, 11].

---

5. Użycie AI
* **Narzędzie:** Asystent AI (Gemini).
* **Zakres użycia:** Pomoc w opracowaniu struktury person, szkieletu mapy strony, tekstów opisowych dla fikcyjnej firmy Pedal & Co. oraz weryfikacja składni plików konfiguracyjnych (`blueprint.json`, `docker-compose.yml`).
* **Weryfikacja ręczna:** Wszystkie pliki konfiguracyjne zostały przetestowane lokalnie w WordPress Playground / GitHub Codespaces, a treści i układy bloków zostały dostosowane ręcznie w edytorze Gutenberg[cite: 7, 11].


passy do wordpresa admin:prychly , hasło: admin