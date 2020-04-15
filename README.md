# Gendera
Marta Witkowska
Jagoda Zarzeka
Monika Gendera

## Spis treści
* [Informacje ogólne](#informacje-ogólne)
* [Technologie](#technologie)
* [Opis projektu](#opis-projektu)
* [Status](#status)

## Informacje ogólne
Celem naszego projektu jest obliczanie odległości z miasta do miasta w Polsce, a także uzyskiwanie informacji na temat województw i miast. Projekt powstał w ramach pracy zaliczeniowej z przedmiotu "podstawy programowania" na uczelni UAM w Poznaniu.

## Technologie
* R - wersja 3.6.3

### Użyte pakiety:
* "remotes"
* "maps"
* "geosphere"
* "stringr"

## Opis projektu
Nasz program zaczyna się od zainstalowania potrzebnych pakietów oraz bibliotek. Użytkownik deklaruje użycie pakietów, następnie wywołuje dane, które go interesują. Deklaruje zmienne,zawierające długości list z województwami i miastami. W późniejszym etapie projektu otrzymuje menu, a w nim opcje wyboru działań. Program należy kompilować linia po linii. 
Funkcja pierwsza i druga opierają się na wykorzystaniu pętli. Pierwsza podaje informację o powierzchni wybranego województwa. Przy wprowadzaniu danych do tej funkcji należy pamiętać o polskich znakach. Druga informuje w jakim województwie położone jest wybrane przez użytkownika miasto. Gdy użytkownik wprowadzi niewłaściwe dane, zostanie o tym poinformowany. Funkcja trzecia pozwala na określenie odległości między dwoma miastami.

### Przykład użycia:
* przykład dla województwa wielkopolskiego
1. Wczytujemy zakładkę "Wczytanie danych"
2. Wczytujemy zakładkę "Funkcje"
3. Wybieramy miasta: Poznań, Kalisz
4. Wczytujemy zakładkę "Program 1"
5. Wybieramy opcję 1
6. Wczytujemy zakładkę "Program 2"

## Status
Projekt jest zakończony.
