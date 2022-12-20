# sartak's fork of Ferris Sweep

|                     Front                     |                    Back                     |
| :-------------------------------------------: | :-----------------------------------------: |
| ![front](/gallery/sweep-half-swept/front.png) | ![back](/gallery/sweep-half-swept/back.png) |

This is a fork of [Sweep](https://github.com/davidphilipbarr/Sweep) with the following modifications to the Half-Swept board:

- Removed all the silkscreen text (so you better already know how to build one of these!)
- Refined the top edge to be staggered with the keys, a la [Ben Vallack](https://www.youtube.com/watch?v=JqpBKuEVinw)
- Adjusted the position of the power switch and reset button
- Removed tenting puck and holes unnecessary for Kailh choc v1 switches

The [`half-swept_gerber.zip`](https://github.com/sartak/Sweep/raw/main/Sweep%20half-swept/half-swept_gerber.zip) has been updated, ready to be sent to a PCB manufacturer.

My impressions so far:

- Tidying up the PCB feels real nice! When I'm using the keyboard, I appreciate that there are no distractions—no tenting holes peeking through keycaps, no overhang above the top row… I can't even see the power switch or reset button unless I'm above looking nearly straight down. And of course, no noisy silkscreen or superfluous holes makes the board feel more premium when inspecting the reverse sides.
- The reset button is a hair too close to the switch below it. It works, but only _just_ barely. There's a ~1 millimeter gap. Next revision will fix that.
- I've only done a wired build so far, but I'm satisfied with the multimeter testing I did for the power switch.

See [https://github.com/sartak/keyboard](https://github.com/sartak/keyboard) for how I use this.
