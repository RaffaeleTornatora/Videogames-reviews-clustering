Tornatora Raffaele
Mat. 786357
2 Febbraio 2019

VIDEOGAME’S REVIEWS CLUSTERING

OBIETTIVO

L’obiettivo dello studio è ricercare pattern e trend da una parte del dataset di recensioni dei prodotti 
Amazon nella categoria Video Games attraverso un’analisi di Text Clustering del testo delle recensioni.

STRUTTURA

Il progetto si struttura in un file ipynb, un file csv, utilizzato come struttura temporanea di appoggio per lo script e una serie di cartelle.

Il file Script.ipynb è il codice che esegue l’analisi di Text Clustering.

Le cartelle invece sono:
- dataset: contiene i dataset utilizzati per lo studio;
- Strutture Dati: contiene le strutture dati create dal codice, come la matrice Tf-Idf, le features e i modelli in un’apposita cartella;
- Grafici: contiene i grafici creati dal codice Graph_generator e programmi esterni;
- Documenti: contiene i documenti derivanti dallo studio. In questa cartella c’è il report in formato Word e la presentazione in formato PowerPoint.

INSTALLARE E FAR GIRARE IL CODICE

Il codice è un notebook Python quindi prima di poterlo eseguire si richiede di verificare i seguenti requisiti:

- Aver installato sul PC Python 2.7 o 3.7:
     Python può essere installato direttamente dal sito: https://www.python.org.
     Oppure può essere installato attraverso una distribuzione, come Anaconda: 
     https://www.anaconda.com

- Aver installato un notebook Python compatibile, come:
    Jupyter: https://jupyter.org
    Apache Zeppelin: https://zeppelin.apache.org
Nota: se si installa Python attraverso distribuzione Anaconda, Jupyter viene fornito nella distribuzione.

- Aver installato le seguenti librerie in Python:
    - pandas
    - gzip
    - time
    - nltk
    - sci-kit
    - numpy
    - matplotlib
    - wordcloud
Con Python installato le librerie possono essere tranquillamente installate attraverso il gestore di 
pacchetti pip. Si apre il terminale e si dà il comando pip install libreria.
Se non si possiede pip lo si può installare da qui: https://pypi.org/project/pip/

Per far girare il codice basta aprirlo nel notebook e far girare i blocchi di codice in maniera sequenziale selezionando il blocco e premendo il tasto Run, che solitamente è raffigurato come il testo Play di un comune lettore musicale. Il codice da far girare è Script.ipynb.