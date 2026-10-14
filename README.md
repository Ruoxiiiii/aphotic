# Aphotic — the deepest water

An interactive text piece about the bottom of the ocean and the bottom of
the heart. Say what moves in you; the words surface, hold, drift apart and
bleed into slow blooms of colour, the way thinned pigment soaks into raw
canvas. When you stop, the deep goes on murmuring to itself.

Built with **p5.js** and **RiTa**.

## The language

Everything the piece says on its own is a phrase of two words — a noun and
a verb, and every verb is a present participle. Nothing has happened and
nothing is finished; it is all going on, and goes on while you watch.

> sea heaving · billows thundering · gloom brooding · darkness creeping
> medusae floating · tentacles trailing · whales swarming · fish lurking

Those phrases are **measured, not invented**. They were mined from about
1,184,000 words of public-domain sea literature — *Moby-Dick* (Melville),
*Twenty Thousand Leagues Under the Sea* and *The Mysterious Island*
(Verne), *The Voyage of the Beagle* (Darwin), *Two Years Before the Mast*
(Dana), *The Sea-Wolf* (London), *Heart of Darkness* and *Typhoon*
(Conrad), and *Leaves of Grass* (Whitman).

The method: find every ocean noun and every creature noun, collect the
verb that follows it, confirm the part of speech with RiTa, and drop the
narrative verbs and copulas. **Every phrase occurs verbatim in those
texts.** The verbs were then conjugated to the participle, which is why
some read in a tense the books did not use — *"sea broke"* became *"sea
breaking"*. Excluded by hand: Verne's *Nautilus* (a submarine, not a
mollusc), *rays* where it means light, and human activity such as whale
hunting.

How often a word attaches to the sea in those books decides how large and
how present it arrives. The habitual motions — *sea*, *water*, *waves*,
*breaking* — loom. The rarest ones — *maelstrom lashing*, *sea flaming*,
*tentacles springing* — stay small, faint and half-seen.

## How each word behaves

Colour, motion and sound come from the word itself. RiTa supplies its
phonemes, syllables and stress; an affective vocabulary supplies the rest.
Violent motions throw dark turbulent indigo, tidal ones move blue,
brooding ones sink heavy and dim, luminous ones bloom pale teal. Words
that aren't in the vocabulary are still read by their *sound*, so invented
words work.

The light from above belongs to the words: it gathers as they surface and
goes out as they bleed away.

## Using it

- **Type** a word or a line, press **enter** to release it into the water
- **Enter on an empty line**, or **escape**, lets the water clear
- **♪** in the corner toggles the sound

Browsers block audio until the page has been interacted with, so the
drone arrives on your first click or keypress.

## Running it

Open `index.html`. Nothing to build, nothing to install — p5, RiTa and the
typeface are bundled in `lib/` and `fonts/`, so it also runs with no
network at all.
