# Realm of Physics and Electronics (prototype v0.1)

A roguelite, open-world RPG prototype where machines and nature share a world with broken physics. Placeholder art and numbers.

## Play

https://crisai2026.github.io/broken-wild/

Or open `index.html` in a desktop browser. Everything is in that one file (HTML, CSS, JavaScript). Progress is saved in the browser's localStorage.

## Controls

- Move: WASD
- Aim and shoot: mouse
- Special: Space or right click
- Interact (repair gates and machines, open the Vault): E
- Recall to the hub: R
- Tech skills, hero stats, journal: 1, 2, 3
- Menu: Esc

## What is in it

- Three classes (Knight, Archer, Wizard) with permanent potion upgrades per class
- A shared Vault at the hub, so gear can pass between classes
- Open world in four rings (Mossy Shallows, Rusted Grove, Gearworks, Corrupted Core)
- Level 1 (Mossy Shallows) has one exit gate driven by four gears (A to D), linked by a gear chain, a shaft and cables. Eleven repairs restore it: a main lever, two fuse boxes, a sync circuit, a jammed gear chain, a cut cable and five gate breakers. Each uses its own puzzle, and the gate swings open when everything works together
- The outer rings are each sealed by four rusted gates you can repair in any order
- Zone physics anomalies: curved shots, low friction, pulsing shots
- Repair puzzles (fuse matching, a sync gauge, clearing a jammed chain, breaker switch panels, wire matching) with a separate Tech skill track
- A three-phase final boss; beating it restores the world and play continues

## Tweaking

The game title, the villain's name and balance values live in the `CONFIG` block at the top of the script in `index.html`.

## Not built yet

Touch controls, music, multiple save slots, the life-sim side of the concept. The outer rings still use the older single-gate repair.
