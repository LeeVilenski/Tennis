# Lee HATES tennis

Two-on-two arcade tennis that runs in the browser. Lee plays doubles with Ed, Ryan or Will, works through a three-round tour on grass, clay and hard courts, and complains the whole way. He would rather be playing padel.

## Play

Open `index.html` in any modern browser. There's no build step and nothing to install.

To play it online, turn on GitHub Pages (Settings → Pages → deploy from the `main` branch, root folder).

## Controls

| Key | Action |
| --- | --- |
| Arrows / WASD | Move Lee, and aim at contact |
| J or Space | Serve, drive, volley, or smash a high ball |
| K or Shift | Lob, or a controlled overhead on a high ball |
| P / Esc | Pause |

**Versus (two players on one keyboard):**

| | Move | Shot | Lob |
| --- | --- | --- | --- |
| P1 (near court) | WASD | F or Space | G or Left Shift |
| P2 (far court) | Arrows | K or Enter | L or Right Shift |

Game controllers work in every mode: stick or d-pad to move, A to hit, B to lob, Start to pause. In Versus the first controller is P1 and the second is P2.

Press early: Lee winds up and swings when the ball arrives. Down at contact plays a drop shot. Phones and tablets get an on-screen stick and buttons.

## Modes

- **World Tour**: Village Open (grass), Riverside Clay Classic (clay), then The Big Slam (hard court). Each surface bounces differently.
- **Career**: a seven-level ladder from Sunday Club Doubles to The Big Slam. Win to move up the rankings, lose and you drop a level.
- **Quick Match**: easy, medium or hard opponents.
- **Versus**: two players, on one computer or online. P1 is Lee and an AI partner on the near court, P2 picks an opponent pair and controls its lead player on the far court. Pick the court and match length. Both human players get the same stats, and there are no Rage Smashes or partner specials, so it's a fair fight.
  - **Online**: one player picks **Host online** and gets a five-letter code; the other picks **Join online** and types it in. Works on phones too. The host plays Lee and their browser runs the match; the friend sees the court from their own end. It uses [PeerJS](https://peerjs.com) to connect the two browsers directly, so there's no server to run. A few strict networks (some offices and mobile carriers) block direct connections.
- **Training**: the **Ball Machine** (20 balls, land them on the target) and the **Rally Challenge** (keep a co-op rally going as it speeds up, three lives).
- Matches run to 2, 4 or 6 games with a tie-break at 6–6 (or N–N), or pick **Tie-break** to play a single tie-break. No-ad scoring and auto-run can be toggled on the title screen.

## Partners

- **Ed, The Apologiser**: lobs a lot and says sorry whenever he loses a point.
- **Ryan, Big Server**: a much faster first serve, and he loves an overhead.
- **Will, Net Hog**: camps on the net and poaches volleys.

Winning points fills your partner's bar. When it's full they play their special: Ed's **Moonball** (a perfect lob over the net players), Ryan's **Thunderbolt** (a huge serve or smash), or Will's **Poach** (an angled volley winner). Lee moaning too much drains it.

## Opponents

Each pair has a personality and talks back: the Baseliners grind and lecture, the Slice Sisters tease, and the Big Servers brag and make excuses. When Lee moans, opponents or his partner may answer him.

## Moan meter

Every complaint from Lee fills the moan meter. When it's full, his next drive is a **Rage Smash**: very fast, aimed away from the opponents, and hard to return. If he keeps moaning while it's full, his partner gets fed up and plays worse until they win a few points. In Carlos Alcaraz mode it becomes the **Hype meter** and the **Vamos Shot**, and the partner cringes instead.

## Trophies & kit

16 trophies to win. Some of them unlock new shirts, rackets and caps for Lee in the Trophies & kit screen.
