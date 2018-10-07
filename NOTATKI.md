# Nauka BASH

#### 3 widoki, ktorych mozemy uzywac w BASH:
- terminal
- nautilius.
- mc

#### Edytory tekstu:
- vim
- atom
- nano

#### Komendy

<b>instalowanie z uprawnieniami admina </b>

sudo apt-get install nazwa_programu

<b>cd $HOME <i>lub</i> cd ~ </b>- otwiera katalog domowy

<b>cd / </b>- otwiera lokalizacje domyslna (analogicznie do c://)

<b>nautilius.</b> - otwiera interfejs graficzny

<b>ls </b> - wyswietla zawartosc folderu

<b>pwd </b> - wyswietla obecna sciezke

<b>cd ..</b> <i>lub<b> cd folder/folder/itd. </b> - przemieszczanie sie miedzy folderami

<b>mv 1 2 </b> - zmienia nazwe 1 na 2
lub przenosi miedzy lokalizacjami

<b>cp 1 2 </b> - kopuij 1 do 2

<b>touch 1.txt </b> - tworzy plik 1.txt

<b>echo "tekst" > plik1.txt </b> - dodaje tekst do tresci plik1.txt i nadpisuje to co bylo

<b>echo "tekst" >> plik1.txt </b> - dodaje tekst do tresci plik1.txt i nie nadpisuje tylko dodaje tresc

<b>cat plik1.txt</b> - wyswietla zawartosc pliku

<b>grep wyszukiwany_tekst plik1.txt</b> - wyszukiwanie ciagu znakow w plik1

<b>mkdir 1</b> - tworzy folder o nazwie 1 ( -p jesli jest jakas sciezka do utworzenia to tworzy ja cala)

<b>rm plik</b> - usun plik (-rf wlacznie z zawaroscia)

<b>rmdir folder</b> - usun folder


<b>cat sciezka/plik.txt </b> - wyswietla zawartosc pliku z podanej sciezki

<b>pass scieka/plik.txt </b> - wyswietla zawartosc pliku z podanej sciezki z mozliwoscia przewijania tresci

<b>head sciezka/plik.txt </b> - wyswietla zawartosc poczatku pliku

<b>tail sciezka/plik.txt </b> - wyswietla zawartosc konca pliku

<b>cat tekst.txt | </b><i> #dodatki </i>

<i>#dodatki:</i>

<b>sort -n</b> - sortuje numerycznie

<b>cut -d'<i>separator</i>' -f<i>kolumna</i></b> - wycina tekst na kolumny rozdzielone separatorem i wyswietla wybrana kolumne

<b>paste - - </b> - pokazuje w koumnach zgodnych z iloscia myslnikow

<b>tr ',' '='</b> - zamienia , na =

<b>sed 's/wartosc1/wartosc2/g'</b> - zastepuje wartosc1 wartoscia2 (tylko string)

<b>xargs -I {} echo "https:/url.com?{}"</b> - wkleja argument {} w wtbrane miejsce

<b>curl </b> - wypytywanie przegladarki np. curl google.com (-L wyswietla odp., -I, -A -user_agent)



#### Zmienne srodowiskowe

definiujemy je w ~/.bashrc

echo "Witam ${USER}"
