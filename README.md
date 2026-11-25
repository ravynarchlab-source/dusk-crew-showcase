<img src="media/gif/hero.gif" alt="Dusk Crew, work-in-progress footage through the bodycam. A quiet street by day under a pale sky. Then a floating axe on a cyan beam chops a tree until wood chips fly. Then the same street at night, lit only by the pool of the crew's lamp, with a black moon overhead." width="100%">

# Dusk Crew

**First-person co-op horror for one or two players. Free demo on itch.io when it's ready.**

Every light in the valley went out. You are the line crew sent back to turn them on.<br>
By day you build light. By night you walk out of it to bring people home.<br>
Something is watching from the dark.

## How a night works

<img src="media/svg/how-a-night-works.svg" alt="How a night works, four steps that loop. Day: build and wire, light the lamps before the sun goes. Dusk: the light fades, something watches from the dark. Night: walk out of the light and bring people home. Dawn: back to the light, count who made it, then a new day." width="100%">

## Systems

### Light and dark

<img src="media/gif/light-and-dark.gif" alt="The same street walked twice, side by side. On the left by day: bright road, houses and power lines. On the right by night: black sky and a black moon, the road visible only inside the lamp's pool." width="100%">

The same street by day and by night. After dark, the light you carry and the lamps you build are the only safe ground.<br>
Lamps throw pools of light with dark gaps between them. The gaps are where the fear lives.

### The cabinet

<img src="media/still/cabinet-panel.png" alt="Greybox test: an open electrical panel with a main switch, a fuse, two contactors and coloured wires to numbered terminals. A line on the panel reads: Game rules. Not instructions." width="100%">

One player wires the panel with their back to the street. The other guards them with the lamp and reads the wiring list off the cuff, because the Wirer cannot see it. Get it right and the street lamps come on one after another.<br>
**Footage coming:** the two-player take is next. This is a greybox still. The panel is game rules, not instructions.

### The Kinetic Rig

<img src="media/gif/kinetic-rig.gif" alt="First-person view at dusk. An axe floats on a cyan beam from the wrist cuff and strikes a tree by itself. Wood chips fly." width="100%">

Your tools float on a beam from the wrist cuff. Send the axe off to fell a tree on its own, then lift the logs home with the same beam.<br>
In development. Not in the friend-test build yet.

### The bodycam

<img src="media/gif/bodycam.gif" alt="The same night walk twice, side by side. Left: Standard, with grain, lens bend and head sway. Right: Comfort, calmer and steadier." width="100%">

You see everything through the helmet camera: grain, lens bend, sway. Human faces are mosaicked, the way footage is censored before release.<br>
Standard on the left. Comfort on the right, for players who want a steadier picture. Every effect has its own slider.

### The creature

It is there from the first minute. It freezes when you look at it and moves when you look away.<br>
It cannot enter light: not the lamp's beam, not a lit lamp post. It waits at the edge and goes for whoever is left in the dark. A teammate's beam drives it off. You cannot kill it.

## Spoiler zone

<img src="media/svg/spoiler-banner.svg" alt="Bodycam warning: a red REC dot, a running timecode and a stamp reading RESTRICTED FOOTAGE. Spoilers below: the creature's full look and the Returned. Content note: blood and gore, filtered by the bodycam." width="100%">

<details>
<summary>I've been warned. Show me.</summary>

### The creature, stage 1

<img src="media/spoiler/creature-stage1.png" alt="The creature's body as black silhouettes on white: front, three-quarter and top views. Low and wide on four long jointed legs, with two long feelers curving ahead of the head. Bottom right: the same shape at night in the game, 8 m away, against a white test card." width="100%">

Stage 1 of the creature's body: the silhouette. Our own model, built by script, and the first stage to pass its review. Work in progress.<br>
Its two feelers never stop. They sweep ahead, tap the walls and turn toward any sound you make. A close-up is coming.

### The Returned

The creature takes your partner. Later something walks back up the road in your partner's suit, one foot dragging, head too far to the side.<br>
Close up, black blades tear out of the back and the arms. Hit it with the beam and the blades melt back for two seconds. That is your window.<br>
Words only for now. Footage comes when there is a clean capture.

</details>

## On the drawing board

> Design only. None of this is built.

**MAKER.** Real electronics inside the game: boards, sensors, LEDs, relays, motors. What works in the game works for real. Every 5 V and 12 V circuit can be exported as a real wiring diagram, parts list and code. Anything that would not work for real is marked "game only". The mains side stays game rules, not instructions. Lights you build help but never solve the night: the creature only flinches at them.

<img src="media/svg/relay-vs-mosfet.svg" alt="Design only, not built. Two ways a MAKER build switches a load. Relay, for the AC side in the game: board pin, transistor, relay coil with a flyback diode across it; the contacts switch an AC lamp, and that side is game rules, not instructions. MOSFET, for DC loads: plus 12 volts, LED strip, N-channel MOSFET, ground; a board pin drives the gate, with a 10 kilo-ohm pull-down." width="100%">

**LineNet.** An in-game network for the crew. It only works where you have restored the power.

## Devlog

**25 Nov 2026 — The creature's shape.** Stage 1 of its new body, the silhouette, passed its review. Next: its main forms.

**25 Nov 2026 — The cabinet works with two.** In a two-player network test, one player wired and one read, and the panel came out the same on both machines. Joining late and a dropped Wirer both hold.

**25 Nov 2026 — The bodycam look.** A fifth pass on the camera: grain, lens, light pools and the Comfort preset. Shown above as work in progress.

**25 Nov 2026 — Holo-Glass HUD.** Still mock-ups of a HUD projected from the cuff, in five states, from a calm day to a dead battery. Nothing in the game yet.

**25 Nov 2026 — Physical animation.** First tests of our own active ragdoll: dragging a downed teammate by the collar. Not there yet.

**24 Nov 2026 — The rig at work.** One take: the axe prints, fells a tree on its own, and the beam lifts three logs home.

**20 Nov 2026 — Holo-print.** Equipping a tool now prints it: grid, wireframe, voxels, then the real material.

**20 Nov 2026 — A whole day.** The district now runs dawn, noon, golden hour, dusk and a night under the black moon.

**17 Nov 2026 — The visor has a face.** Each teammate's visor shows a small face drawn in light, in their own colour, with seven expressions.

## Fact sheet

**Developer:** RAVYN<br>
**Genre:** First-person co-op horror<br>
**Players:** 1–2 in the demo. Online co-op with a room code, or solo with a bot teammate<br>
**Platform:** Windows PC<br>
**Engine:** Unity (URP), Photon PUN 2<br>
**Demo:** Free on itch.io when it's ready<br>
**Status:** In development. Everything on this page is work in progress (WIP) and will change<br>
**Footage:** full clips in the [Footage WIP release](https://github.com/ravynarchlab-source/dusk-crew-showcase/releases/tag/footage-wip)

## More

[How it plays](docs/HOW_IT_PLAYS.md) · [Systems](docs/systems/) · [Spoilers](docs/SPOILERS.md) · [Press](docs/PRESS.md) · [Credits](docs/CREDITS.md)

## Press

You may use the images and GIFs on this page in coverage of Dusk Crew. Please credit RAVYN. Details in [PRESS.md](docs/PRESS.md).

Contact: [Discord — RAVYN: Riftfall](https://discord.gg/YMws83FPS) · [github.com/ravynarchlab-source](https://github.com/ravynarchlab-source)
