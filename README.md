# station-console
A station console, to connect an operator, logger, and radio together

This branch (v1-eagle) is the first version I made of the console.

**IT IS BROKEN!  DO NOT BUILD AS IT IS!!**

~Unfortunately, I can't remember what is broke, I built it 5 years ago.
So instead, I'll describe what the INTENTION was, and let you figure it out.~

**I REMEMBER!** When connected to power, it would brown out the supply and draw
as much current as possible. I just debugged it and figured out that I wired the
2.1mm barrel plug backwards!  Oops.  So I'm going to remove the barrel plugs, 
solder wires in their place, and put Anderson Powerpoles at the end of the wire.

# Goals:
* Allow an operator and a logger to both have headsets on and use an HF radio.
* Audio outputs are mixed, with individual volume knobs for each input:
  * Audio into the mic port on the radio is mixed from the operator and loggers's mics.
  * Audio into the operator and loggers headsets is mixed from eachothers' mics,
    and the speaker audio from the radio.
  * Audio into the external speaker is from the speaker audio from the radio.
* All inputs have a simple VU meter (two LEDs) to set input levels.  
* Audio connections to the radio are transformer isolated, so no ground loops.
* Audio connections to the head sets and external speaker are on the console ground,
  which is tied to power ground.
* PTT is not handled by this mixer console at all. PTT must be routed externally.

# Build:
These files are from an old version of Eagle, circa 2015.  I don't use Eagle anymore,
so I can't update the files.  You're on your own for any conversions.

You might be able to fabricate the board as it is and wire your own power in, leaving
off the 2.1mm barrel plug.
