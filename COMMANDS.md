# Notes
git init     - Tworzy nowe repozytorium w intniejącym projekcie i nie widac go, trzeba go odkryc
git clone    - Pobieramy repozytorium zdalne
git status   - Sprawdzamy stan repozytorium
git add      - Dodajemy plik do sledzenia - np. README albo nazwa folderu albo cały
                folder w ktorym sie znajdujemy to git add . (z kropka)
                sprawdzamy czy dziala - git staus
git rm --cached README - usuwamy/wykluczamy pojedyncze pliki ze sledzenia
git reset              - usuwamy/wykluczamy wszystkie pliki ze sledzenia
git commit             - Wyslanie zmiany do lokalnego repozytorium, przed trzeba dodac git add .
git restore README     - przywracam konkretny plik do wersji z repozytorium, lepiej dac commita i ew. przywrocic commita poprzedniego
git commit -a          - wiele rzeczy jednoczesnie, nie polecane, robi git add . i commituje jednoczesnie
git log                - Wyswietlenie wszystkich commitow, ktore 
                        wykonalismy w repozytorium
git revert #xxx         - Cofniecie okreslonego commita
git commit -m "Add revert to README" - juz z opisem w " opis "
git show #xxx          - Wyswietlenie informacji o konkretnym commicie
git commit -m "Error"
git commit --amend      - zmiana opisu commitu, wyswietla sie okno do opisu
git config --global user.name "SebastianLenart"
git config --global user.email "stentbike7@gmail.com"
git config --global --list
git config --global core.editor "code -w" WAZNE  DLA VSC!!!!!
git info 
git clone "link" w gitbashu potem cd pyfestival potem dir 
git push                    - Publikuje lokalne zmiany, czyli wysyłam je go repo    zdalnego
git pull                    - Pobiera zmiany
git checkout -b NazwaBrancha   - utworzenie nowej galezi
git push --set-upstream origin feature/1-header-at-index        - tworzy nowy branch
git branch -M main
git remote add origin git@github.com:SebastianLenart/pyfestival2.git
git push -u origin main














