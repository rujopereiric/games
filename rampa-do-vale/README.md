# Rampa do Vale — fan game

A retro pixel-art browser game based on the Subida da Rampa do Vale de Santo António,
an uphill cobblestone bike time trial in Lisbon. You ride over the cyclist's shoulder
up the steep street, through a tunnel of cheering people.

Fan-made and unofficial. Riders, crowd and rival names are fictional.

## How to open it

Double-click `jogo-da-rampa.html`. It opens in any modern browser and works offline.
Everything is in that one file: graphics are drawn by code, and the font is built in.

## How to play

- **Pedal:** Space or Up arrow in a steady rhythm. On a phone, tap the red PEDALAR button.
  Keep the rhythm marker in the green zone. Too fast on a steep part makes the wheel slip.
  Too slow and you stall.
- **Steer:** Left/Right arrows or A/D, or the arrow buttons on a phone. Bends push you outwards.
- **Crowd:** brushing it slows you down; on the packed steep part the crowd sometimes pushes
  you up instead. Hitting it hard, or stalling, means a foot down and a 5-second penalty.
- **Energy:** contest balconies, marked with a gold star, give energy as you pass them.
- **Boosts from the crowd:** close up, fans hold out a brown beer bottle ("mini", +15 energy, a little wobble after)
  and a vendor a bifana (slow +20 energy). They shout in comic balloons: "OLHA A MINI!!", "BIFANAS 3,50€!". Steer close to grab.
- **People in the road:** a distracted spectator taking photos (camera flash, balloon "CA GRANDA FOTO!") stands in the road at least once per race
  (sometimes also in the tunnel). A warning sign and a whistle come first; hitting them is a foot down, +5 s.
- **Other keys:** P or Esc pauses, M mutes, Enter starts.

Five categories, as in the real race: Women 18–45, Women 45+, Men 18–45, Men 45+ and Electric.
The fastest rival in each category rides the real 2025 winning time; beat it to win the
cobblestone trophy.

## What the game is based on

- Route shape from Google Maps (Rui's sketch) and a public elevation chart:
  3% → 10% → 15% (peak 22%) → 11% → 7% → 5%, fitted to the official 450 m course.
- Packed crowd tunnel at the side-street crossing on the steepest part; few people higher up;
  finish area with riders who have finished and the timekeeper's table.
- Finish celebration: just past the line the crowd closes the street, jumping, with flares, red smoke
  and a hand-painted banner "VIVA O DESPORTO POPULAR" (inspired by the club's banner at the race).
- History: 1941–1954 by Mirantense FC (first winner 1941: Francisco Inácio, Sporting);
  back since 2021 with ADR "O Relâmpago".
- 2025 winning times from rampadovale.pt/rampa-2025.
- The cyclist wears the white race jersey of ADR "O Relâmpago" with claret and sky-blue bands.
- Start area from race photos: barrier chute, official with a clipboard, countdown by megaphone,
  stewards in hi-vis vests, zebra crossing on asphalt; tall 1960s–70s apartment blocks at the top.
- Street look from public race photos (general traits only; no photos used).

## Sound

- Crowd: real recordings, free to use (from Wikimedia Commons, credit not required):
  "large-crowd-medium-distance-stereo" by eguobyte (CC0), "Clapping for Carers in Oxford, April 2020"
  by Pierre Marshall (CC0), "Clapping hurray" by starlite (public domain).
  The murmur is always there; street cheering swells with the crowd; a "hurray" plays at key moments.
- Music: Rampa's Anthem (a 32-beat loop at 125 bpm),
  arranged as old-console chiptune: pulse-wave lead, off-beat arpeggio blips, triangle oom-pah bass,
  noise drums. Notes snapped to the eighth-note grid; no echo.
- Menu music: a calm version of the same melody (96 bpm, soft pulse lead, arpeggios, slow bass, no drums)
  on the title, how-to, category and results screens; silent countdown; race music starts at GO.
- Shouts ("VAI!", "BORA!"): self recordings; each also has a deeper and a higher version.
- Megaphone countdown and finish fanfare are made by the game.

## Font

Press Start 2P by CodeMan38, SIL Open Font License 1.1 (`FONT-LICENSE-OFL.txt`). Built into the game file.

## Files

- `jogo-da-rampa.html` — the whole game in one file (graphics, sounds, music and font included).
- `FONT-LICENSE-OFL.txt` — licence of the built-in font.

Old looks are still reachable: `jogo-da-rampa.html?style=plain` (cartoon), `?style=litho`, `?cam=far` (old camera).

Best times, chosen category, language and sound setting are saved in the browser on that device only.
