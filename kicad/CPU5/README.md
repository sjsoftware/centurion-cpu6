# CPU 5 Reverse Engineering

Use at your own risk

The schematics are a bit of a mess, I wanted to get them to fit on A1 paper. If you have suggestions for
improvement, raise an issue.

I've included board layouts. If you're going to use them note the following:
* Before getting the boards made, ensure that the interboard connections actually align
    * Currently there is the A revision which is based off the board images
    * The boards have been designed to be fabricated without front solder mask and silkscreen to
      make them the same style as the original. Fabricating with the silkscreen will result in a
      messy board.
    * When new revisions arrive, they are intended to be used as a pair, don't mix them
* Making these is complex and involves a lot of soldering
    * Start with the interboard connections
    * Make sure power and ground are where you expect
    * Put in the passives
    * I haven't designed the breakout boards for the page table/registers yet - you're on your own
    * The A revision expects that you'll bodge things to make an "authentic" CPU5
    * That's about as far as I've got

## Known layout differences

There are at least the following differences:
* Pad 1 on the IC footprints is rectangular on this schematic
* The pads on the solder side, and the vias are slightly smaller than the original
* The position of components, traces and vias are not in exactly the right place
* The power and ground traces are not exactly the right size
* There are some layout differences due to not having the original board to measure from

## Future

I'm planning to design several versions of these, but it's not going to happen quickly.

The passives need more accurate 3-d models, to do this I'd need to learn 3-d CAD which again, is not going to happen
quickly
