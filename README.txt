Projekt strony internetowej Portfolio fotograficzne

1. Standardowe polecenie do pobrania zmian(kiedy chcemy wprowadzić zmiany)":

git pull origin master

2. Standardowe polecenie do commitowania:

git commit -m "Zmiany-konieczny opis"

3. Standardowe polecenie po wprowadzeniu zmian:

git push origin master

4. Polecenia w odpowiedniej kolejności po pracy na swojej gałęzi i zmianach w róznych plikach, na któych już był kod

PISZEMY NA SWOICH GAŁĘZIACH A PÓŻNIEJ WYKONUJEMY TE CZYNNOŚCI:

git status //żeby sprawdzić zmiany które trzeba zakomitować
git add .
git commit -m "Komentarz"
git checkout <branch> //branch - nazwa brancha na którym pracowałaś
git push --force origin branch:master

DO SPRAWDZENIA PRZED PISANIEM KODU

Komentarze do projektu od Marta B:
1. 28.12.24
- zmieniłam footer w home.css - nie trzeba bawić się z tym już w wersji mobilnej, wszystko wyświetla się prawidłowo
- zmieniłam wyświetlanie menu - teraz ma półprzezroczyste tło
- podstrona O nas jest już gotowa w obu wersjach - na duże i małe ekrany

Komentarze do projektu od Marta H:
1. 29.12.2024
- zmieniłam obrazek, żeby wyświetlał się na całej stronie,
- zmieniłam menu: teraz zaraz po otwarciu strony jest niewidoczne, dodałam klasę show,
 -przy pierwszym kliknięciu menu się pojawaia, przy każdym kolejnym rozwija,
 -zmeiniłam tez kolor tła na stronie głównej na brak tła bo tak jest ładniej