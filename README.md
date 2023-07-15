# Authorship attribution problem
>Autori:
>- Elisa Venditti
>- Francesca Venditti


La repository contiene il progetto del corso MACHINE LEARNING (A.A 20222/2023). Si intende approfondire il problema dell'_authorship attribution_ facendo uso di modelli studiati durante il corso di Machine Learning assieme alle principali tecniche di analisi del testo. 

I dati testuali presenti nel dataset sono stati sottoposti ad un preprocessamento:
1. lemmatizzazione per ridurre le parole nella loro forma canonica;
2. eliminazione delle _stop words_, ovvero parole poco informative (e.g. and, or, the);
3. eliminazione delle parole molto frequenti che, quindi, non aiutano con la classificazione;
4. eliminazione degli _hapax_, ovvero parole che occorrono una sola volta e quindi troppo deboli per aiutare con la classificazione.

Sono stati sviluppati i modelli _Random Forest_, _SVM_, _Softmax Regression_ e _Multilayer Perceptron_. A seguito dell'osservazione dei risultati, è stata effettuata un'analisi critica per valutare se alcune caratteristiche intrinseche delle classi potessero essere la causa degli errori dei classificatori.

Il punto di partenza del presente progetto è rappresentato dallo studio: "Gungor, A. (2018). Fifty Victorian Era Novelists Authorship Attribution Data. IUPUI University Library (http://dx.doi.org/10.7912/D2N65J)." A tale studio si deve la creazione del dataset utilizzato. Gli autori si sono occupati dell'estrazione di testi di 1000 parole da una serie di libri risalenti all'epoca vittoriana. 
