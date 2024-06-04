## Communication Commands

### In-Character (IC) Communication

- **say**: Talk to people in the same room.
	- **Usage**: `say Hello everyone!`
	- **Example**: `[player name] says, "Hello everyone!"`

- **yell**: Talk to people in the current and adjacent rooms.
	- **Usage**: `yell Help!`
	- **Example**: `[player name] yells, "Help!"`

- **shout**: Talk to people across the server.
	- **Usage**: `shout We should all meet at the town square.`
	- **Example**: `[player name] shouts, "We should all meet at the town square."`

### Out-of-Character (OOC) Communication

- **occ**: Talk OOC to people in the same room.
	- **Usage**: `occ Can someone explain how this puzzle works?`
	- **Example**: `[player name] OOC, "Can someone explain how this puzzle works?"`

- **looc**: Talk OOC to people in the same and adjacent rooms.
	- **Usage**: `looc That was an intense battle!`
	- **Example**: `[player name] LOOC, "That was an intense battle!"`

- **gooc**: Talk OOC to people across the server.
	- **Usage**: `gooc Great event today!`
	- **Example**: `[player name] GOOC, "Great event today!"`

### Action and Emote Commands

- **act**: Emote an action to people in the same room.
	- **Usage**: `act smiles warmly.`
	- **Example**: `[player name] smiles warmly.`

- **lact**: Emote an action to people in the same and adjacent rooms.
	- **Usage**: `lact waves at everyone.`
	- **Example**: `(from nearby) [player name] waves at everyone.`

- **gact**: Emote an action to people across the server.
	- **Usage**: `gact cheers loudly!`
	- **Example**: `(from somewhere) [player name] cheers loudly!`

## Movement Commands

Movement is an integral part of role-playing on Astralen. Depending on the verb used, different actions are described. Here are some examples of movement commands and their resulting messages:

- **walk north**:
	- **Leaving Message**: `[player name] walks out of the room headed north.`
	- **Entering Message**: `[player name] walks in from the south.`

- **run north**:
	- **Leaving Message**: `[player name] runs out of the room headed north.`
	- **Entering Message**: `[player name] runs in from the south.`

- **whiz north**:
	- **Leaving Message**: `[player name] whizzes out of the room headed north.`
	- **Entering Message**: `[player name] whizzes in from the south.`

### Complete List of Movement Aliases

`abate, amble, bang, bolt, bounce, bound, burst, bust, cant, canter, caper, careen, cavort, circle, clamber, claw, cleave, climb, coil, collapse, crawl, creep, crouch, crush, curve, dance, dart, dash, descend, dip, dive, double, drop, edge, erupt, escape, fade, fall, fight, flit, float, flop, flounce, flow, flutter, fly, frisk, frolic, gallop, galumph, glide, hike, hobble, hop, hopscotch, hover, hunch, hurry, hurtle, jog, jump, kneel, kowtow, lean, leap, lie, limp, list, loll, lope, lounge, lower, lunge, lurch, march, meander, parade, pirouette, pivot, plod, plummet, plunge, pop, pounce, prance, promenade, prowl, pull, race, ramble, retreat, revolve, rip, rocket, roll, run, rush, sag, sail, saunter, scamper, scatter, scoot, scurry, scuttle, shamble, shiver, shoot, shuffle, sidestep, sink, skid, skip, skitter, slide, slink, slither, slog, slouch, slump, smash, snap, sneak, snuggle, soar, spin, spiral, sprawl, spring, sprint, squat, squirm, stagger, stalk, stamp, stoop, stomp, straggle, stride, stroll, strut, stumble, swagger, sway, swerve, swim, swing, swoop, tear, tilt, tip, tiptoe, toddle, traipse, tramp, tread, trip, trot, trudge, twirl, twist, vault, waddle, wade, waft, walk, wander, wane, weave, wheel, whip, whirl, whisk, whiz, wiggle, wobble, wriggle, writhe, zag, zigzag`

## Examination Commands

Players can also examine room objects, themselves, exits or other players using different verbs:

- **look**:
	- **Example**: `[player name] looks at the room.`

- **inspect self**:
	- **Example**: `[player name] inspects themselves.`

- **examine supplies**:
	- **Example**: `[player name] examines the supplies.`

- **check north**:
	- **Example**: `[player name] checks north.`

- **glance another player**:
	- **Example**: `[player name] glances at [another player].`

### Complete List of Examination Aliases

`look, read, examine, inspect, view, check, study, observe, scrutinize, survey, glance, explore, focus, glimpse, stare, peek, analyze, notice, identify`

## Dice Commands

For contested actions, players can roll dice using the following commands:

- **dice**: Roll dice and broadcast the result in the same room.
	- **Usage**: `dice <dice>`
	- **Example**: `dice 2d6+3`
	- **Output**:
    ```
    > dice 2d6+3
    [player name] rolls: 2d6+3
    2, 6 = 8 + 3 = 11
    ```

- **ldice**: Roll dice and broadcast the result in the same and adjacent rooms.
	- **Usage**: `ldice <dice>`
	- **Example**: `ldice 1d20-2`
	- **Output**:
    ```
    > ldice 1d20-2
    [player name] rolls: 1d20-2
    15 = 15 - 2 = 13
    ```

- **gdice**: Roll dice and broadcast the result globally across the server.
	- **Usage**: `gdice <dice>`
	- **Example**: `gdice 2d20adv`
	- **Output**:
    ```
    > gdice 2d20adv
    [player name] rolls: 2d20adv
     > Adv: 15 = 15
       Dis: 11 = 11
    ```

### Dice Roll Format

Use the following format for dice rolls:

- `<number of dice>d<dice sides>[+/-<modifier>][adv/dis]`
  - **Examples**:
    - `dice 2d6+3`
    - `dice 1d20-2`
    - `dice 2d20adv`
    - `dice 4d10-2dis`
