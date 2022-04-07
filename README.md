# Proiect_1_POO-Tema_8

Tema 8. Clasa ”Multime” (multimi finite de numere intregi reprezentate ca tablouri unidimensionale)
	- membri privati pentru vectorul propriuzis si numarul de elemente;
    	- constructori pentru initializare si copiere;
	- destructor (în cazul alocarii statice, se seteaza dimensiunea vectorului la zero, iar în cazul alocarii dinamice, se dezaloca zona de memorie utilizata);
	- metoda publica pentru transformare a unui vector in multime, prin eliminarea duplicatelor din respectivul vector;
	- reuniune a doua multimi, implementata prin supraincarcarea operatorului +;
	- intersectie a doua multimi, implementata prin supraincarcarea operatorului *;
	- diferenta a doua multimi, implementata prin supraincarcarea operatorului -.

Cerinte comune tuturor temelor:

•	implementare in C++ folosind clase

•	datele membre private

•	constructori de initializare (cu si fara parametrii), constructor de copiere

•	get, set pentru toate datele membre

•	ATENTIE: functiile pe care le-am numit mai jos metode (fie ca sunt supraincarcari de operatori, fie altfel de functii), pot fi implementate ca functii prieten in loc de metode ale claselor respective, daca se considera ca aceasta alegere este mai naturala;

•	supraincarcarea operatorilor << si >> pentru iesiri si intrari de obiecte, dupa indicatiile de mai jos, astfel incat sa fie permise (si ilustrate in program):

•	sa existe o metoda publica prin care se realizeaza citirea informațiilor complete a n obiecte, memorarea și afisarea acestora.

•	programul sa aiba un meniu interactiv

Necesar: programul sa nu contina erori de compilare si sa ruleze in CodeBlocks
