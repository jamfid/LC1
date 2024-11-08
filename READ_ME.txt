
Progetto di Linguistica Computazionale di Fidone Giacomo (531668), A.A. 2023/24

-------------------------------------------------------------------------------

La presente cartella contiene:

- Tre file di testo:
  
  - 'animal_farm.txt';
  - 'constitution_of_the_united_states.txt';
  – il presente file 'READ_ME.txt'.

- Tre python nb:

  – 'nb_1.ipynb';
  – 'nb_2_animal_farm.ipynb'.
  - 'nb_2_constitution_of_the_united_states.ipynb'
     

I due file di testo 'animal_farm.txt' e 'constitution_of_the_united_states.txt' sono lunghi (rispettivamente) 34453 e 20283 token. Ciascuno rappresenta un diverso genere testuale, rispettivamente quello narrativo e quello giuridico.

Il nb 'nb_1.ipynb' implementa la fase 1 del progetto, ovvero definisce una classe 'Compare()' per il confronto di due testi – segnalo che la classe supporta anche il confronto di un numero di testi maggiore di due – quindi inizializza un oggetto della classe per confrontare 'animal_farm.txt' e 'constitution_of_the_united_states.txt'. Per l'analisi del sentiment il nb contiene anche una sezione per l'addestramento del classificatore, da eseguire prima di chiamare 'Compare().compare_sentiment()'.

I nb 'nb_2_animal_farm.ipynb' e 'nb_2_constitution_of_the_united_states.ipynb' implementano la fase 2 del progetto. In ciascuno è definita una classe 'Analyze()' per l'estrazione di informazione da un testo. 'nb_2_animal_farm.ipynb' inizializza un oggetto della classe per l'estrazione di informazione da 'animal_farm.txt'. 'nb_2_constitution_of_the_united_states.ipynb' inizializza un oggetto della classe per l'estrazione di informazione da 'constitution_of_the_united_states.txt'.
