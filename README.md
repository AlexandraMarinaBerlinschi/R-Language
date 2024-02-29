# R-Language
## Probabilitati si Statistica

* [Cerinte proiect](https://github.com/AlexandraMarinaBerlinschi/R-Language/blob/86253c79337bd6523cdb39a9e2115c8fc501ad5f/Proiect%20la%20Probabilita%CC%86t%CC%A6i%20s%CC%A6i%20Statistica%CC%86%20INFO%202023.pdf/)
* [Documentatie Proiect](https://github.com/AlexandraMarinaBerlinschi/R-Language/blob/86253c79337bd6523cdb39a9e2115c8fc501ad5f/DocumentatieProiectPS.pdf/)

* [Primul exercitiu](https://github.com/AlexandraMarinaBerlinschi/R-Language/blob/86253c79337bd6523cdb39a9e2115c8fc501ad5f/proiect_ex1.R/) furnizează funcții pentru lucrul cu distribuții de probabilitate comune, probabilități condiționate, covarianță și corelație între variabile aleatoare. Mai exact:

Generarea Variabilelor Aleatoare (SUBPUNCTUL A): Funcția frepcomgen generează variabile aleatoare cu probabilități date și completează parțial o matrice de probabilitate comună.

Completarea Matricei de Probabilitate Comună (SUBPUNCTUL B): Funcția fcomplrepcom completează valorile lipsă din matricea de probabilitate comună pe baza probabilităților marginale.

Calcularea Distribuțiilor Marginale (SUBPUNCTUL C): Funcția frepmarginal calculează distribuțiile marginale ale variabilelor aleatoare X și Y.

Calcularea Covarianței (SUBPUNCTUL D): Implementează funcția fpropcov pentru a calcula covarianța a două variabile aleatoare dată distribuția lor comună de probabilitate.

Calcularea Probabilităților Condiționate (SUBPUNCTUL E): Funcția fPcond calculează probabilități condiționate P(X|Y=yi) și P(Y|X=xi) pe baza distribuției de probabilitate comună.

Determinarea Probabilității Comune (SUBPUNCTUL F): Oferă funcția fComun pentru a găsi probabilitatea comună P(X=xi, Y=yi) pentru valori date xi și yi.

Verificarea Independenței (SUBPUNCTUL H): Implementează funcțiile fverind și fvernecor pentru a verifica dacă variabilele aleatoare X și Y sunt independente și pentru a calcula coeficientul de corelație între ele.


* [Al doilea exercitiu](https://github.com/AlexandraMarinaBerlinschi/R-Language/blob/86253c79337bd6523cdb39a9e2115c8fc501ad5f/proiect_ex2.R/) implementează o aplicație Shiny pentru integrarea funcțiilor bidimensionale folosind Teorema lui Fubini. Interfața utilizatorului este împărțită în două secțiuni: secțiunea de intrare și cea de ieșire.

Secțiunea de intrare permite utilizatorului să introducă o funcție  f(x,y) și limitele inferioare  superioare pentru x și y. Utilizatorul poate, de asemenea, să selecteze tipul variabilei aleatoare și să introducă o densitate de probabilitate pentru variabila aleatoare unidimensională sau bidimensională.

Funcțiile disponibile pentru utilizator includ:

Calculul integralei duble pentru funcția  f(x,y) pe baza limitelor date.
Verificarea dacă funcția introdusă reprezintă o densitate de probabilitate.
Crearea unei variabile aleatoare unidimensionale sau bidimensionale pe baza densității de probabilitate introduse.
Calculul densităților marginale pentru variabilele aleatoare unidimensionale sau bidimensionale.
Calculul densităților condiționate date valori specifice ale variabilelor.
Reprezentarea grafică a densităților sau a funcțiilor de repartiție pentru variabilele aleatoare.
Secțiunea de ieșire afișează rezultatele calculelor și graficele generate în funcție de acțiunile utilizatorului.
