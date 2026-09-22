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

## 🛠️ Tecnologie

* **C++**
* **ncurses**
* **Makefile**

## 🚀 Avvio

Dopo aver clonato il repository, compilare il progetto tramite:

```bash
make
```

Verrà generato l'eseguibile `BunnyFury.exe`.

In alternativa, è possibile compilare manualmente con:

```bash
g++ ProgettoGame.cpp Map.cpp MapList.cpp MapManager.cpp Character.cpp Hero.cpp Enemy.cpp SetEnemiesList.cpp FlyingEnemyX.cpp FlyingEnemyY.cpp ThiefEnemy.cpp JumpingEnemy.cpp Drop.cpp OggettoMappa.cpp OggettoMarket.cpp MarketScreen.cpp EnemiesManager.cpp FileManager.cpp -lncurses -o BunnyFury.exe
```
