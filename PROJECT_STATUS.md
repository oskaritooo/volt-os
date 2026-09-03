# VOLT — stan projektu

Ten dokument pokazuje publiczny, uproszczony stan projektu. Nie opisuje wewnętrznych szczegółów kodu ani dokumentacji technicznej.

## Działa i jest sprawdzane

- główny interfejs VOLT,
- obsługa wybranych urządzeń domowych,
- zbieranie i porządkowanie danych o energii,
- podstawowe analizy zużycia i kosztów,
- mechanizmy rozróżniające dane rzeczywiste od brakujących,
- zasady bezpiecznego udostępniania funkcji sterowania.

## W trakcie domykania

- pełna obsługa pompy ciepła,
- model fotowoltaiki i ocena oczekiwanej produkcji,
- wykrywanie i wykorzystanie nadwyżki energii z PV,
- bilans poboru i oddawania energii do sieci,
- dane taryfowe i rzeczywisty koszt energii,
- pierwsze automatyczne działania oparte na bieżącej sytuacji energetycznej domu.

## Następny etap

Po domknięciu powyższych elementów celem jest sprawdzenie pełnego przepływu:

**produkcja energii → sytuacja w domu → decyzja → bezpieczne działanie urządzenia → sprawdzenie efektu.**

Dopiero później zakres urządzeń i producentów będzie rozszerzany szerzej.

## Zasady, których projekt się trzyma

- brak danych nie oznacza wartości zero,
- system nie udaje, że zna dane, których nie posiada,
- każde urządzenie jest obsługiwane zgodnie z tym, co rzeczywiście udostępnia,
- sterowanie ma być możliwe tylko wtedy, gdy można wykonać je bezpiecznie,
- podstawowe działanie ma pozostawać lokalne tam, gdzie jest to możliwe,
- rozwój odbywa się na podstawie testów na rzeczywistych urządzeniach, a nie wyłącznie danych demonstracyjnych.

---

Status będzie aktualizowany wraz z kolejnymi potwierdzonymi etapami rozwoju.
