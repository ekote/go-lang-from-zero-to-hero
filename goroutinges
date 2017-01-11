http://www.icsr.agh.edu.pl/~malawski/dydakt/tw/lab11/


Teoria współbieżności

Informatyka

Laboratorium - wstęp do języka Go

Podstawowe informacje o języku Go

Strona główna: golang.org.
Kompilacja i uruchamianie: instrukcja (zainstalowane na Windows 8 ICSR, można uruchamiać z git-bash).
Przykłady interaktywne: https://tour.golang.org/welcome/1 uruchamiane przez przeglądarkę.
Strona po polsku: http://golang.org.pl/
Współbieżność w Go

Gorutyny (goroutines) - lekkie procesy, funkcje uruchamiane współbieżnie instrukcją go. Przykład: https://tour.golang.org/concurrency/1.
Kanały (channels) - komunikacja i synchronizacja (blokujące)
Kanały buforowane
Model procesów i kanałów różni się od modelu aktorów: komunikaty wysyłamy nie do procesu, ale do kanału.
Ćwiczenie

Problem producentów-konsumentów (4 pkt.) 
Przykład: https://play.golang.org/p/MIfcmCtxzD. 
Zadanie: przerobić program, aby używał:
wielu producentów, jednego konsumenta.
jednego producenta, wielu konsumentów.
Zaimplementować sumowanie linii w plikach w drzewie katalogów (PAM08) przy pomocy gorutyn i buforowanych kanałów. (6 pkt). 
Można użyć funkcji filepath.Walk https://golang.org/pkg/path/filepath/#Walk
Bibliografia

Wykład o współbieżności - https://talks.golang.org/2012/concurrency.slide#1
Caleb Doxsey: An Introduction to Programming in Go https://www.golang-book.com/
