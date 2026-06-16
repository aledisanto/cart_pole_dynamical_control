# Cart-Pole Control & Trajectory Optimization (Hands-On)

Questo repository raccoglie i moduli pratici (Hands-On) e gli script di simulazione sviluppati per il corso di **Learning-Based Control** presso l'**Università degli Studi di Trieste**. 

Il percorso didattico affronta l'evoluzione delle strategie di controllo su sistemi dinamici complessi, partendo dagli approcci classici e ottimi sul benchmark del pendolo inverso su carrello (*Cart-Pole*) fino all'introduzione dell'apprendimento per rinforzo (*Reinforcement Learning*).

## Struttura delle Attività Pratiche

### Parte 1: Controllo Dinamico e Ottimizzazione (Modello Cart-Pole)
* **Hands-On 1 (Sistemi Lineari - LIN):** Modellazione del sistema, analisi della stabilità transitoria e ottimizzazione dei parametri di controllo classici.
* **Hands-On 2 (Controllo Ottimo Vincolato - OCP):** Formulazione di *Optimal Control Problems* sia lineari che non lineari, introducendo vincoli fisici e saturazioni sugli attuatori.
* **Hands-On 3 (Iterative LQR - iLQR):** Estensione del controllo LQR a scenari non lineari tramite l'algoritmo iterativo iLQR. I vettori di controllo calcolati lungo la traiettoria ottima sono memorizzati in `ilqr_u.mat`.

### Parte 2: Introduzione al Controllo Data-Driven (Reinforcement Learning)
* **Hands-On 4 (Q-Learning Tabulare):** Risoluzione di problemi di controllo model-free in spazi di stato discretizzati, programmando la funzione di ricompensa (*Reward Shaping*) e analizzando il bilanciamento tra esplorazione e sfruttamento.
* **Hands-On 5 (Approssimazione Lineare RBF):** Evoluzione dell'agente di RL tramite l'integrazione di approssimatori di funzione a basi radiali (*Radial Basis Functions*), essenziali per gestire in modo fluido ed efficiente gli spazi di stato continui.

## Organizzazione del Repository
* `HandsOn_1/` fino a `HandsOn_5/` — Cartelle dedicate a ciascun modulo contenenti i relativi file di codice **MATLAB Live Script**.
* **Video d'animazione (`.mp4`):** Simulazioni visive delle risposte dinamiche del sistema ed esecuzione dei test di validazione degli agenti addestrati.

---
*Studente: Alessandro Di Santo*  
*Professoressa: Erica Salvato*  
*Corso di Laurea Magistrale in Computer Engineering (Robotics & AI) — Università degli Studi di Trieste*
