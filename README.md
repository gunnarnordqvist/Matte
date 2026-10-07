# Matte
## Times Tables – Table Monsters
Open `index.html` (or publish it with GitHub Pages: Settings → Pages → branch, root). A quest in the style of the classic Pokémon games for practising the times tables.

* The map of Timesland has one monster per table: SIXCRAB (6), SEVENPILLAR (7), OCTOINK (8), NINELIVES (9), DOZENTROLL (12) and SPOOKTEEN (13). The next place unlocks once the previous monster has been caught. At the end, the TIMESDRAGON mixes all the tables evenly.
* Every correct answer damages the monster – 20 correct answers beat it. Every wrong answer damages you – after 20 wrong answers you faint and can try again.
* Beaten monsters are caught in a Maths Ball and added to the Monsterdex, rated 1–3 stars depending on the number of mistakes. Every caught monster joins your team, and the team members take turns to attack (sharing 20 HP). The leader who goes first can be chosen in the Monsterdex.
* You can practise the same table again: every new win gives the monster more levels and another chance at more stars, and after 3 wins it evolves into a new form (e.g. SIXCRAB → SIXLOBSTER).
* Every battle won gives one hour of reward time.
* Chiptune music (map, a different battle theme for every monster, boss, victory, catch, level-up, evolution) and sound effects are synthesised in the browser with the Web Audio API – no audio files. Sound starts after the first tap, and music and sounds can be switched off separately with the buttons at the top.
* Progress is saved in the browser (localStorage) and can be reset from the Monsterdex.
