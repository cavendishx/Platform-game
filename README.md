# 🐰 Bunny Fury

**Bunny Fury** è un platform game sviluppato in **C++** con la libreria **ncurses** realizzato nel 2023.

Il giocatore controlla un eroe-coniglio che esplora diversi livelli, sconfigge nemici, raccoglie oggetti e accumula **punti e denaro**. La difficoltà aumenta progressivamente e il denaro può essere utilizzato nel **Market** per acquistare oggetti utili.

## 🎮 Gameplay

* Movimento tra piattaforme e diversi livelli
* Salto e attacco dall'alto
* Attacco a distanza tramite proiettili
* Diversi tipi di nemici
* Raccolta di oggetti
* Sistema di punteggio, vite e denaro
* Market per acquistare oggetti
* Difficoltà progressiva
* Persistenza dello stato dei livelli precedentemente esplorati

## ⌨️ Comandi

| Tasto                      | Azione                                                 |
| -------------------------- | ------------------------------------------------------ |
| `←` / `→`                  | Movimento                                              |
| `←` / `→` (tenuto premuto) | Movimento continuo e aumento temporaneo della velocità |
| `SPACE`                    | Spara un proiettile                                    |
| `↑`                        | Salta                                                  |
| `↓` durante il salto       | Attacco dall'alto                                      |

Durante il salto è possibile continuare a sparare e modificare la direzione di movimento.

## 📋 Prerequisiti

Per compilare il progetto sono necessari:

* C++ compiler (g++)
* GNU Make
* Libreria ncurses

Su sistemi Windows è necessario utilizzare un ambiente che fornisca g++, make e ncurses, come MSYS2/MinGW.

## 🚀 Avvio

Dopo aver clonato il repository, compilare il progetto tramite:

```bash
make
```

Verrà generato l'eseguibile `BunnyFury.exe`.
