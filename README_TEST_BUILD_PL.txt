CULTURES: 8TH WONDER – TESTOWA WERSJA REKONSTRUKCJI
===================================================

To jest wczesna wersja testowa projektu rekonstrukcji Cultures: 8th Wonder of the World.

Ta wersja została udostępniona wyłącznie do testowania. Rekonstrukcja jest nadal aktywnie rozwijana, dlatego wiele funkcji jest jeszcze nieukończonych, brakuje ich lub mogą nie działać poprawnie.

Głównym celem tej wersji jest testowanie gry oraz wyszukiwanie błędów, crashy, nieprawidłowego działania i różnic względem oryginalnego Cultures: 8th Wonder of the World.

CO ZAWIERA PACZKA
-----------------
  cultures_reconstruction.exe   gra
  libc++.dll                    wymagany plik
  libunwind.dll                 wymagany plik
  libwinpthread-1.dll           wymagany plik
  game.ini                      konfiguracja gry

Nie usuwaj dołączonych plików DLL ani pliku game.ini. Są one wymagane do poprawnego uruchomienia gry.

DANE GRY – WYMAGANE
-------------------
Ta wersja testowa NIE zawiera żadnych oryginalnych plików gry Cultures: 8th Wonder of the World.

Do uruchomienia potrzebujesz własnej kopii Cultures: 8th Wonder of the World, z której zostaną pobrane wymagane dane gry.

Aby przygotować grę:

  1. Znajdź folder „DataX” w swojej instalacji Cultures.

  2. Skopiuj cały folder „DataX” do folderu z wersją testową, obok pliku
     cultures_reconstruction.exe.

     Powinno to wyglądać mniej więcej tak:

       <ten folder>\cultures_reconstruction.exe
       <ten folder>\DataX\Libs\data0001.lib
       <ten folder>\DataX\...

  3. Uruchom cultures_reconstruction.exe.

Jeśli twoja instalacja zawiera kilka ponumerowanych archiwów, na przykład:

  data0001.lib
  data0002.lib
  data0003.lib
  ...

skopiuj cały folder Libs. Rekonstrukcja automatycznie wykryje dostępne archiwa.

WAŻNE
-----
DataX musi być prawdziwą kopią folderu.

Nie używaj skrótu, symlinka ani junctiona. Jeśli dane gry nie będą mogły zostać poprawnie załadowane, gra może uruchomić się z czarnym ekranem zamiast przejść do menu.

Jeśli nie chcesz kopiować całego folderu DataX, możesz otworzyć game.ini i ustawić ścieżkę do istniejącego pliku data0001.lib za pomocą dostępnej opcji use_data_file_9.

Jeśli po uruchomieniu pojawi się czarne okno lub gra nie przejdzie do menu, sprawdź plik:

  startup.log

Powinna znajdować się tam informacja o tym, co poszło nie tak podczas uruchamiania.

JAK URUCHOMIĆ
-------------
Kliknij dwukrotnie:

  cultures_reconstruction.exe

Najprostszym i zalecanym sposobem jest uruchamianie wersji testowej bezpośrednio z jej folderu.

OBECNY STAN
-----------
To NIE jest jeszcze ukończony zamiennik oryginalnej gry.

Niektóre elementy gry już działają, natomiast wiele systemów nadal jest rekonstruowanych i testowanych.

Obecnie zaimplementowane i ręcznie potwierdzone jako działające są między innymi:

  - renderowanie świata
  - poruszanie kamerą
  - zaznaczanie obiektów i postaci
  - interfejs gry
  - poruszanie się postaci
  - część zawodów i zachowań związanych z pracą
  - przypisywanie domów i pracowników
  - zbieranie drewna

Wiele innych systemów nadal jest niekompletnych lub znajduje się w trakcie prac, między innymi:

  - łańcuchy produkcyjne budynków
  - magazyny i logistyka
  - głód i sen
  - rozrywka i religia
  - rodziny
  - szkoła
  - budowanie
  - drogi i drogowskazy
  - walka
  - pojazdy
  - zapis i wczytywanie gry
  - przeciwnicy komputerowi (AI)
  - multiplayer

Ponieważ jest to wczesna wersja testowa, należy spodziewać się brakujących funkcji, nieprawidłowego działania, problemów graficznych, niedokończonych systemów oraz możliwych crashy.

TESTOWANIE
----------
Podczas gry zwracaj uwagę przede wszystkim na wszystko, co zachowuje się inaczej niż w oryginalnym Cultures: 8th Wonder of the World.

W szczególności zgłaszaj:

  - crashe gry
  - zawieszanie się gry
  - zacinające się postacie
  - nieprawidłowo działające zawody
  - nieprawidłowe zachowanie budynków
  - brakujące lub błędne animacje
  - problemy graficzne
  - problemy z interfejsem
  - nieprawidłowe lub brakujące dźwięki
  - obiekty pojawiające się w nieprawidłowych miejscach
  - wszystko, co działa inaczej niż w oryginalnej grze

Podczas zgłaszania błędu opisz, co dokładnie się wydarzyło oraz co robiłeś bezpośrednio przed wystąpieniem problemu.

Jeżeli błąd da się powtórzyć, bardzo pomocne będą również screenshoty lub nagrania.

ZGŁASZANIE BŁĘDÓW
-----------------
Jest to niezależny projekt rekonstrukcji, który znajduje się obecnie na etapie testów.

Wszelkie błędy, crashe, brakujące funkcje lub nieprawidłowe zachowanie gry zgłaszaj bezpośrednio osobie, od której otrzymałeś tę wersję testową.

Dzięki za pomoc w testowaniu rekonstrukcji!