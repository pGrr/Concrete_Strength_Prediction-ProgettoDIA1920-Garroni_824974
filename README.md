# Concrete compressive strength prediction - IT

## Progetto di Programmazione di Applicazioni Data Intensive a.a. 2019/20 - Paolo Garroni

L'obiettivo è predire la resistenza a compressione del calcestruzzo in MPa (megapascal), avendo a disposizione la quantità dei componenti e la sua età, utilizzando [un dataset fornito da UCI](https://archive.ics.uci.edu/ml/datasets/Concrete+Compressive+Strength).

Dopo analisi esplorativa del dataset, calcolo degli indici di correlazione di Spearman e indagine sulla rilevanza delle feature con standardizzazione e regressione Lasso vengono generati e confrontati diversi modelli di regressione con nested-cross-validation.

In particolare vengono confrontati e analizzati i risultati ottenuti con:

* Regressione polinomiale
* Regressione Ridge (regolarizzazione L2)
* Regressione ElasticNet (Regolarizzazione L1 + L2)
* Regressione Kernel Ridge polinomiale
* Regressione Kernel Ridge Radial Basis Function

[Link per esecuzione in Colab](https://colab.research.google.com/drive/1UC62P846nFO8KtU-PMb5T-JkkOPJNcf8?usp=sharing)
