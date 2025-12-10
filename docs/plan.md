# Piano di Documentazione: DataMuncher 3000

## 1. Analisi del Pubblico (Audience)
Per chi stiamo scrivendo?
* **Target Primario:** Sviluppatori Backend Junior che devono integrare lo script.
* **Target Secondario:** DevOps che devono fare il deploy sul server.
* **Cosa sanno già:** Conoscono Python base e la shell.
* **Cosa NON sanno:** Non conoscono le nostre variabili d'ambiente specifiche né la logica di business dei "numeri magici".

## 2. Struttura Proposta (Table of Contents)
Verranno creati i seguenti file nella cartella `/docs`:
* **01-getting-started.md** (Guida introduttiva)
	* Prerequisiti (Python version, OS supportati)
	* Installazione dipendenze (`pip install...`)
	* Primo avvio ("Hello World")
* **02-configuration.md** (Reference)
	* Spiegazione variabili d'ambiente (quella famosa `API_KEY...`)
	* Spiegazione del file `config_prod.json`
* **03-troubleshooting.md** (Problem Solving)
	* Cosa fare in caso di "Errore 99"
	* Log degli errori comuni
* **04-api-reference.md** (Per sviluppatori)
	* Dettaglio funzioni `main.py`
	* Input/Output attesi

