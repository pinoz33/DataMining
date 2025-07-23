Questo progetto si occupa di classificazione automatica di commenti testuali per identificarne lo stato mentale o emotivo espresso.

In sintesi, gli obiettivi e le fasi principali del progetto sono:

    Obiettivo Principale: Valutare la capacità di modelli di Machine Learning di prevedere e categorizzare lo stato mentale (come ansia, depressione, stress, solitudine, suicidio, supporto, bipolare, ecc.) espresso nei commenti testuali, probabilmente tratti da social media o piattaforme online. L'intento è capire come gli algoritmi di raccomandazione possano influenzare la salute mentale.

    Dataset: Viene utilizzato un dataset (Combined Data.csv) contenente colonne di testo (text) e le rispettive etichette (sentiment) che indicano lo stato mentale associato.

    Fasi del Progetto:

        Caricamento ed Esplorazione dei Dati (EDA): Caricamento del dataset, ispezione delle sue caratteristiche (colonne, valori mancanti), e analisi preliminare della distribuzione delle etichette e della lunghezza dei commenti.

        Pre-processing del Testo: Pulizia dei commenti testuali per renderli adatti all'analisi dei modelli. Questo include la conversione in minuscolo, la rimozione di URL, punteggiatura, numeri, caratteri speciali e l'eliminazione delle "stopwords" (parole comuni prive di significato discriminatorio).

        Trasformazione Vettoriale (TF-IDF): Conversione dei testi puliti in una rappresentazione numerica (vettori) utilizzando l'algoritmo TF-IDF (Term Frequency-Inverse Document Frequency), che pesa l'importanza di ogni parola in un contesto specifico.

        Suddivisione del Dataset: Divisione del dataset in un set di addestramento (training set) e un set di test, mantenendo la proporzione delle classi (stratified split) per garantire una valutazione imparziale dei modelli.

        Addestramento dei Modelli di Classificazione: Applicazione e addestramento di diversi algoritmi di Machine Learning sui dati di training:

            Naive Bayes (MultinomialNB)

            Logistic Regression

            Support Vector Machine (LinearSVC)

            Random Forest

        Valutazione delle Performance: Analisi delle prestazioni di ciascun modello sul set di test utilizzando metriche come Accuracy, Precision, Recall e F1-Score, e visualizzazione delle Confusion Matrix per comprendere gli errori specifici.

        Discussione e Confronto dei Risultati: Confronto delle performance dei diversi modelli per identificare il più efficace per il compito di classificazione degli stati mentali.

        Conclusioni e Lavoro Futuro: Sintesi delle scoperte, discussione delle limitazioni del progetto attuale e proposte per miglioramenti futuri (es. ottimizzazione, word embeddings, deep learning).

In sintesi, è un progetto di Natural Language Processing (NLP) applicato al Sentiment Analysis / Classificazione di Stati Mentali, utilizzando tecniche standard di Machine Learning per analizzare e interpretare il linguaggio naturale.
