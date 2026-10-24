# Acampada

A pixel-art browser game about the housing protest camps (#acampadapelahabitação) in Portugal.
Keep the camp standing in five squares: Porto, Lisboa, Coimbra, Braga and Faro, and hold
the square when the police come at dawn.

## How to open it

Open `index.html` in any modern browser. Everything is in that one file; the fonts load
from Google Fonts when online and fall back to system fonts offline.

## How to play

- **Move:** tap the square (or WASD / arrow keys).
- **Cordão (C):** human chain that shields nearby tents from the police.
- **Direto (L):** go live, so raids go viral and bring support.
- **Montar (B):** build a kitchen, info point, first aid or stage with donated supplies.
- **Assembleia (V):** vote for a perk for the camp.
- **E / Space:** the context action next to a station; **P / Esc:** pause; **I:** info posters; **F:** full screen (computers).

Fill the pressure bar to hold a square. Hold all five to win.

- **? / H:** "Como jogar", the goal and rules of the game.
- **Partilha:** after a square is cleared, makes an Instagram story (1080×1920) with the square as it was won,
  a rotating slogan and the next rally, and opens the phone's share sheet (or downloads the image on a computer).
  Rallies and slogans are in `RALLIES` and `SLOGANS` in `index.html`.
- On phones the camera starts zoomed out, showing the whole square; the magnifier button zooms in on the player.

The game is entirely in Portuguese. On a computer the game scales up to fill the window,
and the ⛶ button (or F) switches to full screen.

In Lisboa, the Coro da Achada (the open choir of the Casa da Achada) holds its rehearsal every day at 18:00:
campers come out of their tents, stand in a circle and sing the refrain of *A semana sangrenta* (the choir's
Portuguese version of *La Semaine sanglante*, tune by Pierre Dupont, transcribed from a public-domain SATB score),
and passers-by join the camp. Singing
*Grândola* while the choir is there adds much more pressure. The DJ, the choir and the donkey tandem take turns
in the square, and the stage rotates through artists who played at the Rossio and Porto acampadas (Porto's from @acampadaporto's daily programmes).
Bicicletadas ride in with the dawn raid and hold up the police van.

In every square, once the crowd is big enough, gather in the centre and sing *Grândola, Vila Morena*:
the police freeze for 30 seconds while Rui's own MIDI arrangement (0:06–0:43, sped up to fit 30 s) plays on the game's built-in synth.

Cleared squares are saved in the browser on that device only.

`og.jpg` (link preview) and `apple-touch-icon.png` (iPhone home-screen icon) sit next to `index.html` for hosting;
the preview tags point to https://acampadapixel.pt/. The favicon is embedded in the page.
