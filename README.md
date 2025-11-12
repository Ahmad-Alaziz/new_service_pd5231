# Dokumentacja i raport końcowy

## Opis usługi medycznej oraz dokumentów stworzonych w projekcie

Projekt dotyczy usługi telekonsultacji zdrowotnych prowadzonej zdalnie (wideo, telefon lub komunikatory), aby skrócić czas oczekiwania pacjenta i obniżyć koszty świadczeń. Najważniejsze materiały w repozytorium to: `opis_usługi.txt` (szczegóły świadczenia i korzyści), `plan_wdrożenia.txt` (podział prac na etapy), `ryzyka.txt` (zagrożenia i działania zapobiegawcze), `kampania_marketingowa.txt` oraz `ankieta_pacjentów.txt` (materiały z gałęzi `marketing`) i `images/logo.png` (prototyp identyfikacji wizualnej).

## Instrukcje dotyczące pracy z repozytorium

```bash
git clone git@github.com:Ahmad-Alaziz/new_service_pd5231.git
cd new_service_pd5231
git branch -a        # lista dostępnych gałęzi
git switch marketing # przejście do treści marketingowych
git switch main      # powrót do stabilnej wersji
git log --oneline --graph --decorate --all # historia skrócona z grafem
git log --oneline --follow -- <plik>       # historia wybranego dokumentu
git checkout <SHA> -- <plik>               # przywrócenie wcześniejszej wersji pliku
```
