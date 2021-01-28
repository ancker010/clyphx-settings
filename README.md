## My personal ClyphX Pro settings

### Branches
**main** - Novation Launch Control

### Settings

`X-Controls.txt`

#### Pads
1. `play = cc, 16, 1, 52, 0, sel/play` - Play selected clip. If it's Midi, record too.
2. `stop = cc, 16, 2, 11, 0, stopall` - Stop all clips, quantized. Does not stop overall playing.
3. `dupe = cc, 16, 3, 62, 0, sel/clip(sel) dupe` - Duplicate Selected Clip
4. NOT CURRENTLY USED
5. `over = cc, 16, 5, 55, 0, srec` - Overdub a Midi clip.
6. `rec2 = cc, 16, 6, 3, 0, sel/recfix 2` - Record for 2 bars in the current clip. (Works for Audio too.)
7. `rec4 = cc, 16, 7, 5, 0, sel/recfix 4` - Record for 4 bars in the current clip. (Works for Audio too.)
8. `rec8 = cc, 16, 8, 7, 0, sel/recfix 8` - Record for 8 bars in the current clip. (Works for Audio too.)

#### Arrows
1. `up = cc, 16, 9, 0, 127, up` - Move up.
2. `down = cc, 16, 10, 0, 127, down` - Move down.
3. `left = cc, 16, 11, 127, 0, left ; all/arm off; sel/arm on` - Move one track to the left, and arm it. (Disarm all others)
4. `right = cc, 16, 12, 127, 0, right ; all/arm off; sel/arm on` - Move one track to the right, and arm it. (Disarm all others)

### Pad Color Table

| Hex | Decimal | Color | Brightness |
|:----|:--------|:------|:-----------|
| 0Ch | 12      | Off   | Off        |
| 0Dh | 13      | Red   | Low        |
| 0Fh | 15      | Red   | Full       |
| 1Dh | 29      | Amber | Low        |
| 3Fh | 63      | Amber | Full       |
| 3Eh | 62      | Yellow| Full       |
| 1Ch | 28      | Green | Low        |
| 3Ch | 60      | Green | Full       |

Flashing LEDs - (I'm not sure these work)
| Hex | Decimal | Color | Brightness |
|:----|:--------|:------|:-----------|
| 0Bh | 11      | Red   | Full       |
| 3Bh | 59      | Amber | Full       |
| 3Ah | 58      | Yellow| Full       |
| 38h | 56      | Green | Full       |
