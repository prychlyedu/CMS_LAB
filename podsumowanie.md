Podsumowanie audytu dostępności i zmian (MP1 – G1, G2, G3)
Kontrast i kolorystyka (G1): Zweryfikowano zestawienie kolorów projektu Pedal & Co. (#ffffff, #1a1a1a, #0b5d7a, #14532d) pod kątem progów kontrastu dla tekstu i elementów interaktywnych (spełnienie wymagań kontrastu dla treści oraz elementów UI).

Dodatkowy CSS – fokus, cele dotykowe i RWD (G2): Wdrożono arkusz w Dodatkowym CSS zapewniający wyraźny fokus klawiatury (:focus-visible z outline i outline-offset), bezpieczny margines przewijania pod nagłówkiem (scroll-padding-top), wygodny rozmiar celów dotykowych oraz poprawki układu na wąskich ekranach (w tym widok 375 px w DevTools — brak rozjeżdżania się elementów).

Audyt przed poprawkami (G3 – Lighthouse i WAVE):

Strona główna: Lighthouse Accessibility na poziomie 100/100; w WAVE 0 Errors oraz 0 Contrast Errors, a także 12 Alerts (m.in. Possible heading oraz Redundant link) i puste teksty alternatywne (alt) dla grafik dekoracyjnych.

Strona Kontakt: Przeprowadzono pomiar początkowy w Lighthouse (Accessibility) oraz WAVE (zapisano wyniki „przed” w celu porównania z pomiarem „po”).

Poprawki i ocena alertów (G3): Uporządkowano wybrane elementy treści i interakcji (m.in. opisowe etykiety/teksty zamiast ogólników w rodzaju „kliknij tutaj” oraz weryfikację struktury nagłówków). Pozostałe alerty w WAVE (np. Possible heading wynikające z szablonu/motywu) zweryfikowano jako ostrzeżenia niebędące błędami krytycznymi (Errors), co zostało odnotowane w raporcie.

Audyt po poprawkach (G3): Powtórzono testy w Lighthouse (Accessibility) oraz WAVE po wdrożeniu CSS i zmian na stronie, zapisując wyniki „po” obok wyników „przed”.