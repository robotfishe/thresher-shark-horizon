### Meet the Thresher Shark Horizon, a split keyboard for Gateron low profile keyswitches with a couple of unique features.

![photo of a split keyboard](TSH.jpg)

The name comes from one of my favourite animals, the thresher shark, a creature endowed with a permanent facial expression that can only be described as "why is existence happening to me":

![image of a thresher shark](thresher-shark.jpg)

and my favourite video game series, Horizon Zero Dawn/Horizon Forbidden West. Since the general approach to naming a keyboard design seems to be "throw a dart at a dictionary", this seemed as good as anything.

The TSH keyboard has a couple of design choices that set it apart:
- It uses Gateron low profile switches, which are a lot less commonly supported in the custom keyboard space than other switch types.
- It mostly uses a full standard ANSI key layout, somewhat rare among split keyboards.
- It has an electrically coupled split spacebar (see below for what that means).
- It uses a Molex Micro-fit cable to connect the split halves rather than a TRRS (see below for why).

### Electrically coupled split spacebar: what and why?
The TSH uses what I call an "electrically coupled split spacebar" design. What that means is that the two halves of the spacebar are connected directly to each other via two extra conductors in the cable between the two keyboard halves. Because of this, the keyboard firmware actually *sees them as a single key*.

I designed the keyboard this way because I have a habit of slamming both my thumbs down on the spacebar at once, and I didn't want to risk that with a split layout that might lead to lots of accidental double-spaces. I could have fixed that in software somehow, but this was a cleaner solution. If you're not a double-space-slammer, you won't notice any difference at all, *except* for the fact that the right spacebar "doesn't exist" in software, so it can't be reassigned to another function.

### Molex Micro-fit connectors: what and why?
The two halves of the TSH are connected with a Molex Micro-fit 3.0 5-pin cable. There are two main advantages of this connector over the TRRS jacks that are traditionally used in split keyboards. First, the connectors are parallel, so the cable is hot-plug-safe (TRRS cables, because the various contacts pass through in sequence when you connect them, are usually NOT hot-pluggable because you will end up inadvertently dumping voltage somewhere you don't want it). Second, Micro-fit connectors are crimped rather than soldered, so putting together your own cable with custom sleeving should be easier. Pre-built cable assemblies are also readily available. Micro-fit connectors are also low-profile enough that they don't make the keyboard any thicker than it already has to be to accommodate the microcontroller board.
