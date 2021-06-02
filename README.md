## Systemy Operacyjne 2 - Laboratoria
### Lab01

**Co zostało zrealizowane?**
- skrypt, który pobiera 3 argumenty: ```SOURCE_DIR```, ```RM_LIST```, ```TARGET_DIR``` o wartościach domyślnych: ```lab_uno```, ```lab_uno/2remove``` oraz ```bakap```;
- jeżeli ```TARGET_DIR``` nie istnieje to zostaje utworzony;
- następuje iterowanie po zawartości pliku ```RM_LIST``` i w przypadku, gdy plik o podanej nazwie występuje w katalogu ```SOURCE_DIR``` to zostaje usunięty;
- jeżeli jakiegoś pliku nie ma na liście, ale jest plikiem regularnym to zostaje przeniesiony do ```TARGET_DIR```
- jeżeli po zakończeniu operacji jakieś pliki są jeszcze w katalogu ```SOURCE_DIR``` to wyświetlane zostają stosowne komunikaty;
- ponadto wszystkie pliki w katalogu ```TARGET_DIR``` mają odebrane prawa do edycji;
- na koniec katalog ```TARGET_DIR``` zostaje spakowany (nazwa: ```bakap_RRR-MM-DD.zip```).


### Lab02

**Co zostało zrealizowane?**
-

A tak prompt wygląda po zmianach:

![env](https://user-images.githubusercontent.com/49610728/116263192-76be5a80-a779-11eb-801d-957a64c1dad2.png)


### Lab05

**Co zostało zrealizowane?**
- Napisana została aplikacja w Pythonie umożliwiająca grę w kółko i krzyżyk.
- Użytkownik przed przystąpieniem do gry z komputerem wybiera, czy chce być X czy O.
- Jakość sprawdzanego kodu poprzez PyLinta wynosi 10.0/10.0.

![lab05](https://user-images.githubusercontent.com/49610728/120439062-5ee28380-c382-11eb-99a7-32a16a0f6f9a.png)
