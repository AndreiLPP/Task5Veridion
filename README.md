# Task5Veridion
Mail ul trimis in readme: 

Buna ziua, 

Am ales taskul 5 pe care urmeaza sa il incarc si pe platforma Veridion.
Voi lasa si aici codul care sta la baza realizatii taskului.

Observatii : 

Codul functioneaza "reasonably well on all datasets", insa poate fi destul de lent in functie de timpul de incarcare al paginii html. 

De asemenea, locatia folderelor de date si raspuns este hardcodata, le puteti modifica ulterior pentru a testa exemplul pe pc ul dumneavoastra. Se afla in aceasta bucata de cod : 

string folder = @"C:\Users\Andreilpp\Desktop\TaskVeridion\clones\tier4";
string folderrezultat = @"C:\Users\Andreilpp\Desktop\RezultatTask\tier4rezultat";
string rezultatfinal = @"C:\Users\Andreilpp\Desktop\final";

Modul de gandire este urmatorul: 
Incerc sa fac o grupare initiala in functie de nodurile de baza ce se afla in tagurile <body> ale fiecarui html - numele si ordinea lor, dupa care, pentru fiecare grup salvez screenshot uri la paginile web pe care le compar pixel cu pixel si verific similaritatea dintre acestea pentru a forma noi grupuri ce le voi scrie in folderul "rezultatfinal".

Daca solutia este in regula, astept raspunsul dumneavoastra. 

Multumesc ! 
