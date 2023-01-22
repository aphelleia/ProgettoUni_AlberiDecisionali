Autori: H.Zamorska, C.Palo, M.Della Peruta, M.Di Siero
PowerPointPresentazione: Presente

Linguaggio di programmazione: Python
Tematiche: Alberi decisionali + ottimizzazione 
Programma con cui sono stati scritti e gestiti i progetti: PyCharm e Colab (piattaforma di Google online)

-Ogni cartella rappresenta un progetto a se stante, 
.ipynb è l'eseguibile, mentre .csv è il database.
Per ogni .ipynb è annesso il proprio .csv con il quale va eseguito insieme.

-Per algoritmo CART si consiglia piattaforma Colab , da inserire in input il training set (database voli_train.csv), 
 eseguire i singoli blocchi sequenzialmente. I risultati dei voli ottimi sarannò nell'ultima parte interattiva.   

-Per Cart e Chaid è stata utilizzata interamente una libreria chefboost
Una volta eseguito gli algoritmi, verrà generato nella cartella del progetto(outputs su PyCharm)
un file rules.py che contiene l'albero relativo al progetto.
N.B è possibile modificare il database direttamente su PyCharm, aprire a destra la sezione database.

-Id3 utilizza chefboost per il calcolo dell'indice entropico mentre per la costruzione dell'albero e per l'ottimizzazione 
l'algoritmo è stato scritto manualmente

