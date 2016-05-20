
UNIWERSYTET GDAŃSKI

WYDZIAŁ MATEMATYKI, FIZYKI I INFORMATYKI

**Jessica Tkacz**

**Tomasz Wilk**

*Kierunek*: Informatyka

*Specjalność*: Aplikacje internetowe i bazy danych

Aplikacja dla systemu Android usprawniająca kontakty z bliskimi.

Praca licencjacka napisana

pod kierunkiem dr Włodzimierza Bzyla

Gdańsk 2016

Spis treści

1. Opis problemu

1.1 Porównanie dostępnych rozwiązań

1.2 Możliwości zastosowania praktycznego

2. Projekt i analiza

2.1 Aktorzy i Przypadki użycia

2.2 Wymagania funkcjonalne i niefunkcjonalne

2.3 Diagram klas

2.4 Diagram modelu danych

2.5 Projekt interfejsu użytkownika

2.6 Funkcjonalności - fragmenty kodu aplikacji

3. Implementacja

3.1 Architektura rozwiązania

3.2 Użyte technologie

3.3 Testowanie aplikacji

4. Wkład własny

5. Bibliografia

WSTĘP

Przedmiotem naszej pracy jest aplikacja napisana dla systemu Android na telefony oraz tablety. Jest ona przeznaczona dla tych, którzy cenią sobie pielęgnowanie kontaktów z rodziną i przyjaciółmi, a przy tym są zbyt zajęci bądź zapominalscy, by pamiętać o choćby cotygodniowym telefonie do danej osoby. Aplikacja służy do przypominania użytkownikowi o wykonaniu telefonu do konkretnej osoby na podstawie zaznaczonych przez użytkownika preferencji, co do częstotliwości połączeń z danym kontaktem.

Analiza dostępnych rozwiązań rozpoczęła się na długo przed podjęciem decyzji o pisaniu naszej aplikacji, jako że szukaliśmy czegoś podobnego do własnego użytku. Istnieją oczywiście aplikacje dla systemu Android, które choć po części miały spełniać podobną rolę, ale posiadały one zazwyczaj zbyt wiele skomplikowanych ustawień oraz niepotrzebnych funkcji, do których po krótkim czasie traciło się cierpliwość. Celem naszego rozwiązania jest prostota oraz brak konieczności częstego powracania do ustawień, co z kolei prowadzi do kolejnych atutów – oszczędności czasu oraz użyteczność osobom starszym, niezaznajomionym dobrze z nowymi technologiami. Ponadto aplikacja wszystkim swoim użytkownikom wysyła adnotacje z przypomnieniem o np. Dniu Dziadka albo Dniu Matki, co jest ponadprogramową okazją do wykonania telefonu.

Aplikacja ma na celu wspomóc osoby, które z różnych powodów nie pamiętają o wykonaniu telefonu do bliskich osób, choć ważne jest dla nich utrzymywanie dobrych stosunków z nimi oraz regularny kontakt. Naszym celem było by prosty w obsłudze interfejs oraz jednorazowa konieczność tworzenia ustawień sprawiły by aplikacja mogła cieszyć się popularnością wśród różnych grup wiekowych. Nasze rozwiązanie może posłużyć zarówno młodzieży, która przez nawał obowiązków nie zawsze pamięta o tym, żeby zadzwonić do ukochanej babci, jak i również osobom starszym w kontaktach z rodziną czy w przypadku regularnych wizyt u lekarza wymagających rejestracji. Ponadto aplikacja może zostać wykorzystana przez specjalistów różnych dziedzin jako wsparcie w kontakcie z klientami w regularnych odstępach czasu (np. comiesięczne przypomnienie o wizycie ortodontycznej).

2. Projekt i analiza

W tym rozdziale pragniemy przedstawić wybrane diagramy związane ze sposobem działania naszej aplikacji, jej strukturą oraz samym jej zaprojektowaniem.

…...

Tu diagram use case może

…..

2.2. Wymagania funkcjonalne i niefunkcjonalne

Wymagania funkcjonalne:

Aplikacja pobiera pełną listę kontaktów z telefonu użytkownika i wyświetla ją wraz z opcjami ustawień. Właściciel ustawia pożądaną częstotliwość przypomnień o połączeniu z danym kontaktem za pomocą *seekBar,* a obok prezentują się rezultaty wykonanych czynności w postaci ilości dni. Następnie wstępnie zapisuje te ustawienia za pomocą *checkBox*, ponieważ tylko zaznaczone w ten sposób kontakty zostaną uwzględnione przez aplikację. Jest to zabezpieczenie na wypadek, gdyby użytkownik przypadkiem ustalił priorytet w kontakcie, na temat którego powiadomień nie chce otrzymywać. Na sam koniec wystarczy potwierdzić wszystkie ustawienia za pomocą guzika na dole, co da aplikacji ostateczną wersję, którą ma wziąć pod uwagę. W każdym momencie użytkownik może powrócić do owych ustawień i je zmienić.

Wymagania niefunkcjonalne:

Oczywistym ograniczeniem jest fakt, iż aplikacja jest zorientowana na system Android i na żadnym innym nie będzie działała. Możliwe jest używanie jej zarówno na *smartfonach*, jak i tabletach posiadających wersję systemu Android 5.0. i wzwyż.

Można również uruchomić aplikację w środowisku Android Studio, w którym była pisana i oglądać efekty próbnych działań na wybranym emulatorze posiadającym odpowiednią wersję systemu.

SŁOWA KLUCZOWE:

„aplikacja” „Android” ”rodzina” „przypomnienia” „prostota” „adnotacje”

„babcia” „kontakt” „organizacja” „oszczędność czasu” „zadzwonić” „telefon”

„systematyczność” „regularny” „połączenie”
