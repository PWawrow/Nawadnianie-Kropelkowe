# Zautomatyzowany system nawadniania kropelkowego

Ten projekt przedstawia system nawadniania kropelkowego, który został zaprojektowany i zaimplementowany w celu optymalizacji zużycia wody i automatyzacji procesu nawadniania.

## Opis projektu

System wykorzystuje:
- **Cztery zbiorniki** z wodą jako źródła zasilania systemu.
- **Jedną pompę** do pompowania wody do systemu nawadniającego.
- **Niestandardowy system sterowania** oparty na stycznikach, który:
  - Automatycznie wybiera odpowiedni zbiornik w zależności od poziomu wody i zapotrzebowania.
  - Minimalizuje ryzyko wyczerpania wody w jednym zbiorniku, równomiernie korzystając z dostępnych zasobów.

## Funkcjonalności
1. **Automatyczne przełączanie zbiorników**  
   System wykrywa poziom wody w każdym zbiorniku i przełącza źródło nawadniania w czasie rzeczywistym, zapewniając ciągłość pracy.
   
2. **Efektywne zarządzanie zasobami**  
   Dzięki zastosowanemu algorytmowi sterowania system efektywnie wykorzystuje dostępne zasoby wody, ograniczając jej marnotrawstwo.

3. **Prosta architektura sterowania**  
   Opracowanie systemu sterowania na kontaktorach pozwala na łatwą implementację i niskie koszty eksploatacji.

## Cele projektu
- Automatyzacja procesu nawadniania w oparciu o zasady oszczędnego gospodarowania wodą.
- Minimalizacja kosztów i skomplikowania układu sterowania.
- Zwiększenie niezawodności systemu nawadniającego.

## Technologie
- **Układ sterowania:** stycznikowy  
- **Elementy wykonawcze:** pompa, zawory  
- **Sensory:** wykrywanie poziomu wody w zbiornikach  

## Możliwości rozwoju
- Integracja z systemem IoT w celu monitorowania i sterowania nawadnianiem zdalnie.
- Dodanie pomiaru wilgotności gleby, aby dostosować nawadnianie do aktualnych potrzeb.
- Zastosowanie bardziej zaawansowanego algorytmu sterowania, np. na mikrokontrolerze.

