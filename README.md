![VOLT — lokalne zarządzanie energią](assets/baner.png)

# VOLT

**Lokalne zarządzanie energią w domu**

**Strona projektu:** https://volt-os.web.app/

VOLT to rozwijany system, który łączy w jednym miejscu informacje z fotowoltaiki, ogrzewania, sieci energetycznej i urządzeń domowych.

Celem projektu jest pokazanie użytkownikowi prostego obrazu tego, co dzieje się z energią w całym domu: ile energii jest produkowane, ile zużywane, ile kosztuje pobór z sieci i kiedy można wykorzystać energię lepiej.

## Co robi VOLT

- zbiera dostępne dane z różnych urządzeń i usług,
- porządkuje je tak, aby można było analizować je razem,
- pokazuje produkcję, zużycie i koszty w jednym miejscu,
- pomaga ocenić, kiedy warto wykorzystać energię z fotowoltaiki,
- pozwala budować automatyczne działania tam, gdzie urządzenie rzeczywiście umożliwia bezpieczne sterowanie,
- działa przede wszystkim lokalnie, a z usług producenta korzysta wtedy, gdy jest to potrzebne do obsługi konkretnego urządzenia.

## Dlaczego powstał VOLT

Domowe systemy energetyczne najczęściej działają osobno. Fotowoltaika ma własną aplikację, ogrzewanie własną, urządzenia domowe kolejną, a dane o energii i kosztach znajdują się jeszcze gdzie indziej.

VOLT ma połączyć te informacje w jeden spójny system, bez budowania całego rozwiązania pod jednego producenta sprzętu.

## Jak rozwijany jest projekt

VOLT jest testowany na rzeczywistych urządzeniach i domowej instalacji energetycznej.

Podstawowa zasada jest prosta: system pokazuje tylko to, co rzeczywiście wie. Brak danych nie jest traktowany jak zero, a funkcje sterowania są udostępniane tylko wtedy, gdy konkretne urządzenie pozwala wykonać je w bezpieczny i przewidywalny sposób.

Aktualny zakres prac obejmuje m.in.:

- urządzenia domowe i pomiar ich zużycia,
- fotowoltaikę i ocenę dostępnej nadwyżki energii,
- ogrzewanie i pompę ciepła,
- bilans poboru i oddawania energii do sieci,
- taryfy i rzeczywisty koszt energii,
- automatyzację decyzji dotyczących wykorzystania energii.

## Wybrane ekrany

### Przegląd energii w domu
![VOLT — przegląd energii](assets/screens/home-overview.jpg)

### Fotowoltaika
![VOLT — fotowoltaika](assets/screens/pv-view.jpg)

### Urządzenia
![VOLT — urządzenia](assets/screens/devices-overview.jpg)

### Szczegóły urządzenia
![VOLT — szczegóły urządzenia](assets/screens/device-detail.jpg)

### Rynek i taryfa
![VOLT — rynek i taryfa](assets/screens/market-view.jpg)

## Stan projektu

VOLT jest aktywnie rozwijanym projektem przed pełnym wdrożeniem produkcyjnym. Poszczególne elementy są wdrażane i sprawdzane etapami na rzeczywistym sprzęcie.

Szczegółowy, uproszczony status znajduje się w [PROJECT_STATUS.md](PROJECT_STATUS.md).

Plan najbliższego rozwoju znajduje się w [ROADMAP.md](ROADMAP.md).

## Współpraca

Projekt jest otwarty na współpracę z:

- producentami urządzeń energetycznych i smart home,
- instalatorami fotowoltaiki i pomp ciepła,
- firmami zainteresowanymi pilotażowym wdrożeniem,
- partnerami technologicznymi,
- inwestorami i programami wspierającymi rozwój nowych rozwiązań energetycznych.

Szczególnie interesują nas możliwości testowania urządzeń, dostęp do dokumentacji integracyjnej oraz rzeczywiste instalacje, na których można sprawdzać kolejne elementy systemu.

**Zobacz działającą stronę projektu:** https://volt-os.web.app/

## Kod źródłowy

To repozytorium ma pełnić rolę publicznej prezentacji projektu. Główny kod źródłowy VOLT pozostaje prywatny.

---

**VOLT — niezależnie rozwijany system zarządzania energią.**

[English version](README_EN.md)