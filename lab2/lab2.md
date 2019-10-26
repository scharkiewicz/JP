## Zadania

Program skopiowano z:
https://www.programiz.com/c-programming/c-file-examples



1. Wyświetl na ekran 2 pierwsze wiersze pliku program.c. (head)

```sh
head --lines 2 program.c
head -n 2 program.c
```

2. Wyświetl na ekran 4 ostatnie wiersze pliku program.c. (head, tail)

```sh
tail -n 4 program.c
```

3. W pliku program.c znajdź wszystkie wiersze z wystąpieniem słowa „main”. (grep)

```sh
grep main program.c
```

4. Plikowi program.c nadaj następujące uprawnienia: właściciel – czytanie, pisanie, grupa – czytanie, pozostali użytkownicy: brak uprawnień. (chmod)

```sh
chmod 640 program.c
```

5. Będąc w katalogu temp przenieś katalog wazne-sprawy do katalogu praca.

```sh
mv dom/wazne-sprawy/ /praca/
```

6. Zarchiwizuj cały katalog temp. (zip i tar)

```sh
zip temp temp
tar -cf temp.tar temp
```


7. Usuń katalog temp.

```sh
rm -r temp
```

8. Odtwórz z archiwum katalog temp. (unzip i tar)

```sh
unzip temp.zip
tar -xf temp.tar
```
