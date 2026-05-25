# Btolux OS: Zamysł i Filozofia Nowego Systemu Od Podstaw

**Nie ma tu jeszcze ani jednej linii kodu. Jest pusta kartka i wielka idea.**

Btolux OS to propozycja stworzenia zupełnie nowego, niezależnego systemu operacyjnego od absolutnego zera — od poziomu assemblera, języka C i surowego jądra (kernela). Dla mnie napisanie tego kodu od czystej kartki to żaden problem. Jednak ten projekt nie ma być kolejną bezużyteczną zabawką czy kolejną taką samą dystrybucją. Ma przywrócić światu to, co bezpowrotnie stracił współczesny Linux.

---

## Lekcja Historii: Duch Unixa i Linuxa

Aby zrozumieć, czym ma być **Btolux OS**, musimy cofnąć się do korzeni i zobaczyć, skąd czerpiemy inspirację i przed czym chcemy się obronić.

### 1. Era Unixa (Lata 70.) – Potęga Prostoty
Unix narodził się w Bell Labs jako system czysty, piękny w swojej prostocie i piekielnie logiczny. Przyświecała mu jedna główna filozofia: 
> *Program ma robić jedną rzecz, ale robić ją dobrze. Wszystko w systemie jest plikiem.*

Unix dawał użytkownikowi pełną, niczym nieskrępowaną kontrolę nad maszyną. Był transparentny – programista dokładnie wiedział, co dzieje się w pamięci i procesorze. Był tworzony przez pasjonatów dla pasjonatów.

### 2. Era Linuxa (1991 r.) – Walka o Wolność
Kiedy Unix stał się systemem komercyjnym i zamkniętym, Linus Torvalds napisał legendarne jądro Linux. Duch, który mu wtedy przyświecał, był czystym buntem przeciwko wielkim korporacjom. Linux miał być darmowy, otwarty (Open-Source) i dostępny dla każdego człowieka na Ziemi, bez względu na status materialny. To miało być cyfrowe dobro wspólne ludzkości.

### 3. Dzisiejsza Rzeczywistość – Upadek Idei
Co stało się z Linuxem dzisiaj? **Sprzedał swoją duszę wielkiemu kapitałowi.**
* **Korporacyjne przejęcie:** Ponad 90% kodu współczesnego jądra Linux jest pisane i dotowane przez gigantyczne korporacje (Google, Intel, Red Hat, Microsoft).
* **Narzędzie inwigilacji:** System, który miał gwarantować wolność, stał się silnikiem napędowym inwigilacji (Android zbierający telemetrię) oraz wielkich korporacyjnych chmur obliczeniowych.
* **Skomplikowanie zamiast elegancji:** Kod stał się tak gigantyczny i przeładowany, że zwykły człowiek nie ma szans kontrolować tego, co system robi w tle jego własnego komputera.

---

## Jak ma wyglądać Btolux OS?

Btolux OS powstaje w identycznym, surowym duchu jak dawny Unix i wczesny Linux, ale wyciąga wnioski z ich błędów. Budujemy go tak, aby **nigdy** nie stało się z nim to, co z Linuxem.

Oto fundamentalny zamysł architektoniczny i moralny:

* **Niezależność od Korporacji (0% wpływów korporacyjnych):** Btolux OS nigdy nie przyjmie pieniędzy ani kodu od wielkich firm technologicznych. Rozwój systemu ma zależeć wyłącznie od niezależnych ludzi i otwartej społeczności.
* **Wracamy do Monolitycznej Prostoty:** System operacyjny musi być zrozumiały. Kod źródłowy jądra ma być czysty, elegancki i wolny od tysięcy zbędnych linii kodu, które korporacje dopisują pod swoje interesy.
* **Absolutny Brak Inwigilacji:** Blokada telemetrii, śledzenia pakietów i jakiegokolwiek szpiegowania zostanie zaszyta bezpośrednio w najgłębszej architekturze jądra. System ma służyć użytkownikowi, a nie zbierać o nim dane.
* **Zupełnie za Darmo na Zawsze:** Żadnych licencji, żadnych zamkniętych sterowników binarnych (*binary blobs*), których nie da się przeanalizować. Wszystko jawne, transparentne i darmowe dla każdego.

---

## Droga Od Zera

Skoro zaczynamy od czystej kartki, projekt będzie rósł etapami:
1. **Projektowanie Jądra (Kernel):** Napisanie własnego bootloadera, zarządzania pamięcią RAM i obsługi procesora bez polegania na gotowcach.
2. **Budowa Systemu Plików:** Stworzenie logicznej struktury przechowywania danych opartej o czyste zasady Unixa.
3. **Własna Powłoka (Shell):** Tekstowy interfejs dający bezpośredni dostęp do surowej mocy sprzętu.

Dla mnie napisanie tego od zera to nie problem. Jeśli jednak czujesz tego samego, dawnego ducha wolności, który umarł we współczesnym świecie IT — obserwuj ten projekt. Stwórzmy alternatywę, której nikt nie będzie mógł kupić ani kontrolować.
