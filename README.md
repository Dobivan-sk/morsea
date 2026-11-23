# Morse.-

Pixel-art hra do mobilu: torpédoborec na hliadke v Atlantiku, Stredomorí a v Čiernom mori.
**Nauč sa morzeovku a bav sa pri tom.**

A pixel-art phone game: a destroyer on patrol in the Atlantic, the Mediterranean and the Black Sea.
**Learn Morse code and have fun doing it.**

## Ako sa hrá

- Sonar pípne každé 3 sekundy a nájdené ponorky ukáže v sieti na 2,5 sekundy, každú s jej súradnicou (napr. DELTA2).
- Zameraj štvorec morzeovkou: písmeno stĺpca, potom číslo riadku. Napríklad B7 je `–··· ––···`.
- Krátke ťuknutie na kľúč je bodka, podržanie je čiarka. Krátka pauza ukončí znak. Na počítači funguje aj medzerník.
- Ponorka, ktorú nestihneš, vystrelí torpédo. Máš 3 životy.
- Každú minútu sa loď posunie o písmeno: ABC, BCD … až XYZ. Atlantik má 24 levelov, potom Stredozemné a Čierne more, kde nepriateľské rušičky miešajú písmená stĺpcov.
- Režimy: **Výuka** (1 ponorka, 20 s do výstrelu, morzeovka pri súradniciach, štart od ľubovoľného písmena), **Normálne** (vždy 1 ponorka, 15 s do výstrelu, nezrýchľuje sa) a **Co-op** (dvaja hráči cez internet bránia jednu loď: kapitán pozve kamaráta kódom alebo QR; až 3 ponorky naraz).
- Body zo všetkých hier sa sčítavajú do skúseností (XP) a prinášajú 10 hodností U.S. Navy, od Ensign po Admiral. V režime Normálne a Co-op násobí séria zásahov: 2.–5. zásah ×2, od 6. ×3. Výuka dá najviac hodnosť Lieutenant.
- Pri prvom spustení si zadáš meno hráča a názov lode; loď uvidíš pri každej hre v Najlepšom skóre.
- Hru môžeš v pauze uložiť do doku a neskôr v nej pokračovať.
- Hra je v slovenčine aj angličtine, s 8-bitovou hudbou pre každé more.

## How to play

- The sonar pings every 3 seconds and shows the submarines it finds on the grid for 2.5 seconds, each with its coordinate (e.g. DELTA2).
- Aim at a square in Morse code: the column letter, then the row number. For example, B7 is `–··· ––···`.
- A short tap on the key is a dot, holding is a dash. A short pause ends the character. On a computer the space bar works too.
- A submarine you don't sink in time fires a torpedo. You have 3 lives.
- Every minute the ship moves on by one letter: ABC, BCD … up to XYZ. The Atlantic has 24 levels, then the Mediterranean and the Black Sea, where enemy jammers shuffle the column letters.
- Modes: **Training** (1 submarine, 20 s to fire, Morse code by the coordinates, start at any letter), **Normal** (always 1 submarine, 15 s to fire, never speeds up) and **Co-op** (two players defend one ship over the internet: the captain invites a friend by code or QR; up to 3 submarines at once).
- Points from all your games add up to experience (XP) and earn 10 U.S. Navy ranks, from Ensign to Admiral. In Normal and Co-op mode a streak of hits multiplies it: 2nd–5th hit ×2, from the 6th ×3. Training goes up to Lieutenant.
- On the first start you enter your player name and your ship's name; the ship shows with every game in the high scores.
- Save the game to the dock from the pause screen and continue later.
- In Slovak and English, with an 8-bit soundtrack for each sea.

## Technika

Celá hra je jeden súbor `index.html` (písma z Google Fonts). Skóre, skúsenosti, uložená hra a história sa ukladajú len v prehliadači hráča. Co-op sa spája cez Firebase Realtime Database; počas hry sa tam posiela len meno hráča, názov lode a priebeh hry. Návštevy a spustené hry sa anonymne počítajú cez [GoatCounter](https://www.goatcounter.com), bez cookies a bez osobných údajov.
The whole game is a single `index.html` (fonts from Google Fonts). Scores, XP, the saved game and history stay in the player's browser. Co-op connects through Firebase Realtime Database; during a game only the player name, the ship name and the game itself are sent. Visits and started games are counted anonymously with [GoatCounter](https://www.goatcounter.com), with no cookies and no personal data.

---

Created by Ivan Hrušovský
