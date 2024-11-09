# Pitsa tellimise veebileht

Tegemist on pitsa tellimise veebilehega, kus saab valida endale sobiliku toidu välja ning liigutada see edasi ostukorvi.
Ostukorvis saab klient sisestada enda andmed ning need edastada. Kliendi andmed kuhugi välja ei jõua.

## Paigaldamine

1. **Ava terminal ja, mine oma projektikausta (asenda "projektinimi" oma kausta nimega):**
   ```bash
   cd projektinimi
   ```
   Kui kausta veel ei eksisteeri, saad selle luua käsuga (asenda "projektinimi" enda soovitud kausta nimega):
   ```bash
   mkdir projektid
   ```
     
2. **Kopeeri repostiiorium oma arvuti kausta**  
   Kirjuta järgmine käsk terminali, et kloonida projekt oma arvutisse:
    ```bash
    git clone https://github.com/krosta12/stravy.git
    ```    
3. **Veebilehe avamine internetis**
    Veebilehe nägemiseks otsige üles oma kaust, kuhu te kloonisite projekti ning kaustas avage fail nimega
   ```bash
   index.html
   ```

## Kasutamine
Veebileht sisaldab järgmisi kausti:
- *CSS*
  Selles kaustas on css failid, mis kujundavad veebilehe stiili. Igal failil on konkreetne nimi, mis ütleb juba ära, kus seda kasutatakse.
- **pages**
     Pages all on veebilehe lehtede html-id. Nende failide pealkirjad ütlevad lühidalt ära, et millise lehega on tegu.
- src
  Src all on mitmed muud asjad, nagu näiteks veebilehe pildid, js (javascript).

  ## Autorid
- krosta 12
- TristanSaraskin
- henrilipping
