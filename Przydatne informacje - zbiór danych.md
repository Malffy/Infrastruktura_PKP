
[Link do repo](https://github.com/PrzedmiotFakultatywny2024/GLIP-2024-UWMOlsztyn)  
[Link do Trello](https://trello.com/invite/b/wi7bfaBH/ATTI8bb8ff84831fa27d67b52dd929e62ef7BB2FF447/pkp-informatyka-siemsonymielsony)

## Logowanie apache-01
Login: `adminer`  
Hasło: `!1Olsztyn`  
`sudo su`  
Hasło: `!1Olsztyn`  


## Logowanie GLPI
Login: `glpi`  
Hasło: `!1Olsztyn`

---
### DOKUMENT - "nazwa", krótki opis zawartości dokumentu lub przydatne dla nas informacje w nim zawarte.

#### JEŚLI OBOK NAZWY JEST (DO WYKONANIA) OZNACZA TO, ŻE MUSIMY PRZEROBIĆ ZADANIA Z DANEGO DOKUMENTU + NAPISANIE DOKUMENTACJI

---
### DOKUMENT - Case study uslugi transportowe

**GLPI** to otwarte oprogramowanie służące do zarządzania zasobami informatycznymi w organizacjach.  
Jest to narzędzie, które umożliwia skuteczne monitorowanie, organizowanie i zarządzanie infrastrukturą IT.  
Pozwala w centralny sposób, efektywnie zarządzać zasobami IT, zgłoszeniami, Service Desk, projektami, budżetami, zmianami, statystykami, licencjami, oprogramowaniem, jednostkami organizacyjnymi, grupami użytkowników oraz pojedynczymi użytkownikami.

Założenia poszczególnych kroków przedsięwzięcia:
- propozycje rozwiązania z wykorzystaniem narzędzia GLPI;
- projekt rozwiązania zarówno dla biznesu (Prezesi firm) oraz zespołu implementującego rozwiązanie;
  - architektura logiczna i fizyczna w narzędziu do modelowania BPMN
  - Utworzenie słowników (lokalizacje, statusy, komponenty)
- zamodelowanie bazy danych
  - w tym insert, trigery
- implementacja rozwiązania:
  - przygotowanie środowiska deweloperskiego
  - instalacja agentów na urządzeniach
  - Inwentory + Discovery zasobów IT
  - modyfikacja GUI użytkownika + security
  - inicjalne zasilenie danymi z csv (REST API + Plugin DataInjection)
  - utworzenie nowej wtyczki i jej wyprofilowanie funkcjonalne
  - modyfikacja agenta
  - konfiguracja brokera + instalacja agenta
  - skanowanie sprzętu SSH, SNMP, WMI, WinRM
  - skanowanie sieci
  - skanowanie VMWare
- testy (scenariusz testowy);
- dokumentacja;
- prezentacja zaimplementowanego rozwiązania.


> Projekt ma na celu transfer wiedzy i podzielenie się doświadczeniem przez pracowników Wydziału Matematyki i Informatyki, Uniwersytetu Warmińsko-Mazurskiego oraz PKP Informatyka sp. z o.o. ze studentami uczestniczącymi w przedmiocie fakultatywnym.  
> Powyższy scenariusz może być rozwijany, zgodnie z Waszymi pomysłami i kreatywnością.  
> Jednakże rozwój scenariusza powinien mieć swoje odzwierciedlenie w dostarczonych materiałach zaprezentowanych przez Was podczas zaliczenia.  
> Podczas oceniania powyższego zadania najwyżej oceniane będą zaprezentowane materiały wytworzone przez Was, ale także cechy zaprezentowane przez Was jak kreatywność, aktywność oraz terminowość przy realizacji poszczególnych zadań.  
> Liczymy, że uczestnictwo w projekcie pozwoli Wam uzyskać doświadczenie przy planowaniu i realizacji projektów, a tym samym na zbudowanie podstaw dla własnego portfolio.

---
### DOKUMENT - Domena AreoTrans (DO WYKONANIA)

Poradnik - instalacja domeny AreoTrans

---
### DOKUMENT - GLPi Ćwiczenia - Backup-Policy-Template
### DOKUMENT - GLPi Ćwiczenia - data_backup_and_recovery_policy_template

**Backup policy templaty** - Przydatne do procedury back-upu.

---
### DOKUMENT - GLPI Ćwiczenia - DCIM Hardware

Dokumentacja i obrazy fizycznych urządzeń w firmie.

---
### DOKUMENT - GLPi Ćwiczenia - instalacja agenta, procedura backup&restore 1.1 (DO WYKONANIA)

Poradnik - instalacja Agenta GLPi dla systemu Windows z MSI.  
Poradnik - procedury Backup i Restore GLPi.

W pliku tym znajdują się również zadania jakie mamy wykonać.

**Zadanie 1**: Procedura Backup i Restore GLPi.

**Zadanie 2**: Instalacja GLPi Agent dla systemu Windows z MSI.

**Zadanie 3**: Instalacja Agenta GLPi dla platformy Unix.

**Zadanie 4**: Instalacja Agenta GLPi dla platformy Laptop Studenta.

**Zadanie 5**: Instalacja Agenta GLPi dla platformy Telefon Studenta.

---
### DOKUMENT - GLPi Ćwiczenia - zasilenie ActiveDirectory 1.1 (DO WYKONANIA)

#### Ważne zadanie, które musimy wykonać:

> Utwórz masowo konta użytkowników, oraz grupy zabezpieczeń w Katalogu ActiveDirectory na podstawie listy csv.


Zadanie częściowo przerobiliśmy wspólnie na zajęciach, posiadamy wiedzę i umiejętności by je wykonać.

---
### DOKUMENT - GLPi Projekt studencki UWM 1.3 (DO WYKONIANIA)

Podsumowanie wszystkich zadań, które zostały przydzielone nam do wykonania (Końcowe podsumowanie wykonanej przez nas pracy).
Architektura i technologia maszyn.

Linki (Oficjalna dokumentacja GLPi): 
- model bazy danych GLPi
- tworzenie wtyczek
- przykładowe wtyczki
- kod agenta
- komunikacja agent-serwer

---
### DOKUMENT - Instalacja GLPi 1.3 LAB

Poradnik 

---
### DOKUMENT - Instrukcja deployment wtyczek

Zadanie dla zespołu aplikacyjnego

---
## Przygotowanie do modelowania (DO WYKONANIA)

Tworzenie diagramów BPMN - Przydatne będą diagramy BPMN, z zajęć z projektowania systemów informatycznych oraz inżynierii oprogramowania.
Dokument ten będzie przydatny przy wykonywaniu zadania - Architektura logiczna i fizyczna w narzędziu do modelowania BPMN.

Link do modelera - https://bpmn-io.github.io/bpmn-js-token-simulation/modeler.html

#### ZADANIE

Założenie konta dla Uzytkownika w AD:
- przyjecie wniosku
- rozpatrzenie wniosku
- obsługa wniosku
- powiadowmienie wnioskodawcy
- 15 kroków (zdarzeń, czynności, bramek)


## DO SŁOWNIKA POJĘĆ:

**Usługa katalogowa** - baza danych, która wystawia informację o użytkownikach i ich różne informacje opisowe 
(np. przełożeni, biuro w jakim pracuje itp.), oraz o komputerach - działa to w ten sam sposób, gdy korzystamy z
facebooka lub yt, jesteśmy skatalogowani na tych serwisach, mamy swoje atrybuty które uzupełniamy w większym
lub mniejszym stopniu, są nadawane nam uprawnienia, zwykle każda organizacja ma jedną usługę katalogową,
można powiedzieć, że jest to rdzeń firmy i referują do niej różne systemy.






