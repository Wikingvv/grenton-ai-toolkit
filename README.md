# Grenton AI Toolkit

> Zestaw narzędzi wspomagających tworzenie projektów dla systemu Grenton z wykorzystaniem sztucznej inteligencji.

## Cel projektu

Grenton AI Toolkit powstaje z myślą o programistach i integratorach systemu Grenton.

Celem projektu jest stworzenie kompletnego środowiska wspomagającego tworzenie automatyki budynkowej poprzez:

- uporządkowaną bazę wiedzy,
- bibliotekę gotowych modułów Lua,
- przykłady praktycznych rozwiązań,
- dokumentację integracji z urządzeniami i usługami,
- narzędzia wspierające programowanie,
- generator projektów ObjectManager.

Projekt ma ograniczyć czas potrzebny na tworzenie nowych instalacji oraz ułatwić utrzymanie istniejących projektów.

---

# Główne założenia

Projekt będzie rozwijany w kilku obszarach.

## 📚 Baza wiedzy

Zawiera opracowaną dokumentację dotyczącą:

- ObjectManager
- języka Lua w środowisku Grenton
- Virtual Objects
- zdarzeń i harmonogramów
- najlepszych praktyk programowania
- typowych problemów i ich rozwiązań

---

## 📦 Biblioteka Lua

Gotowe moduły wielokrotnego wykorzystania.

Przykładowe biblioteki:

- sterowanie oświetleniem
- rolety
- ogrzewanie
- klimatyzacja
- alarm
- harmonogramy
- funkcje pomocnicze

---

## 🔌 Integracje

Dokumentacja oraz gotowe przykłady integracji z urządzeniami i usługami.

Między innymi:

- Somfy TaHoma
- MQTT
- HTTP REST
- Modbus
- Satel
- KNX
- inne systemy

---

## 🤖 Generator projektów

Docelowo projekt będzie umożliwiał automatyczne generowanie projektów ObjectManager na podstawie opisu w języku naturalnym.

Przykład:

> Utwórz projekt zawierający:
>
> - 12 obwodów oświetlenia
> - 8 rolet
> - pompę ciepła Panasonic
> - Somfy TaHoma
> - alarm Satel
> - tryb nocny

Efektem będzie kompletny projekt gotowy do importu do ObjectManager.

---

# Struktura repozytorium

```
docs/               Dokumentacja
examples/           Przykłady
integrations/       Integracje
library/            Biblioteki Lua
objectmanager/      Dokumentacja formatu projektów
tools/              Narzędzia pomocnicze
```

---

# Aktualny etap prac

Projekt znajduje się na etapie budowy fundamentów.

Aktualnie realizowane są:

- organizacja repozytorium,
- przygotowanie dokumentacji,
- analiza ObjectManager,
- tworzenie bazy wiedzy,
- opracowanie standardów kodowania.

---

# Plan rozwoju

- [ ] Dokumentacja ObjectManager
- [ ] Dokumentacja Lua
- [ ] Biblioteka funkcji Lua
- [ ] Integracje
- [ ] Dokumentacja formatu projektów OM
- [ ] Generator kodu
- [ ] Generator projektów ObjectManager
- [ ] Asystent AI dla Grentona

---

# Współpraca

Projekt jest rozwijany jako otwarta baza wiedzy dla użytkowników systemu Grenton.

Wszelkie propozycje, poprawki oraz przykłady praktycznych zastosowań są mile widziane.

---

# Licencja

Licencja zostanie określona przed pierwszym publicznym wydaniem projektu.
