# MOBA_Map

Każda mapa powinna byc w oddzielnym podkatalogu w lokalizacji \Maps\
Wszsytkie piki powiązane powinny byc w katalogu mapy. Jezeli cos zostalo doimportowane to trzeba od razu przeniesc i zaktualziwac odnosniki.
Jezeli sa uzywane zasoby innych osob to trzeba dopisac ponizej w pliku link i radzaj licencji, zeby potem sie nie pogóbić.

Testowy kontent powinien byc w katalogu o nazwie test. Pliki z katologów test sa usuwane z builda. Grę mozna spakowac i powinno sie dac w multi :)
Jezeli dodajesz pliki, tym czasowo i nie wiesz czy beda czescia mapy to dodawaj odpowiednie wpisy do .gitignore - żeby nie zasmiecac repo
Przykaldowy wpisy blokujący dodanie katalogow do repo.

#ignore big data files form other projects
Content/ParagonGideon/*
Content/ParagonGreystone/*


Jezeli w menu startowym ma pojawic sie nowa mapa to trzeba dopisac nazwę w pliku \CGS\Gameplay\Multiplayer\MainMenu\GM_MainMenu w tablicy z listą map.
 
