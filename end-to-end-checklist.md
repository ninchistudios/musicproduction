# Music Production End to End Checklist

## Songwriting & Arrangement

These steps may occur in any order depending on your process.

### Hook

* The hook is one of the key ingredients of a memorable song
* It's possible to start writing a song from one phrase or word that forms the hook

### Lyrics

* Avoid cliche
* Songwriting references e.g. [Writing Better Lyrics](https://www.amazon.com.au/Writing-Better-Lyrics-Pat-Pattison-ebook/dp/B008Y0XH1C)

### Melody

Consider a Mode that suits the feel of the song, e.g.

1. Ionian (natural Major): Bright and happy, can be overly saccharine. Suits pop, rock, jazz, punk, country.
2. Dorian (natural Minor with a sharp 6th): Cheeky, partly sad, hopeful. Suits blues, jazz, rock, funk, prog.
3. Phrygian (natural Minor with a flat 2nd): Dark and tense. Spanish/oriental, suits metal, jazz, flamenco.
4. Lydian (natural Major with a sharp 4th): Mystical. Mostly used in jazz.
5. Mixolydian (natural Major with a flat 7th): Positive but edgy. Rock, blues, jazz, funk. The AC/DC progression.
6. Aeolian (natural Minor): Sad, subdued. Suits most genres.
7. Locrian (natural Major with flat 2nd and flat 5th): Dissonant, unstable, tense. 

Important to create a memorable melody.

### Chord Progression

### Arranging

Try to include something surprising or unique in the arrangement to create interest. Take the listener on a journey.

The song should grab the listener in the first verse/chorus.

Repetition is ok with a good arrangement. Even if the lyrics repeat, the arrangement should change and progress and stay fresh and interesting from section to section.

Some techniques:

* Vocal harmonies
* Vocal effects (radio/lofi, ring mod, etc)
* Percussion (bells, shakers etc)
* Synth instruments
* Strings and other orchestrals
* Doubled/tripled vocals
* Doubled guitars
* Time signature or tempo changes
* Key changes
* Quiet/highly simplified sections

## Production & Recording

* Mic placement is more important than mic choice.
* The analogue advice of recording at the highest possible level without clipping doesn't apply to digital. Record at -18dBFS on a VU without clipping.
* Don't "fix it in the mix" - originate the highest possible quality recordings.
* Lay down final MIDI arrangements if possible rather than placeholder. 
* Record MIDI notes with instruments (MIDI keys/pads/drums etc) rather than drawing notes if possible to humanise.
* Watch mic bleed from ambient sound and/or headphones when recording. Closed back cans preferred for vocalists.

### Basic Order for Rock

1. click track at target tempo
2. Rough simple take to the click track for arrangement reference
3. Percussion
4. Vocals
5. Rhythm instruments
6. Lead instruments
7. Others

## Editing & Mixing

### Edit

1. Gain stage tracks to 0dB VU.
2. Create composite track from all takes for each track.
3. Clean up, tighten up and tune up each track.
4. Tune vocals.
5. Clean up breaths, smacks and plosives.
6. Quantize instruments judiciously - don't overdo and dehumanise it. Drums/bass can take/need more quantization than others.

### Mix

#### General Tips

* Keep the Master bus clear (meter only) so that the reference track is unaffected. Use a Mix Bus to glue the mix.
* Generally mix at conservative volume, and check the mix at very low volume to make sure it still sounds ok. Volume distorts perception of the mix quality.

#### Gain Staging with Basic Bus Layout

![Gain Staging with Basic Buses](https://github.com/ninchistudios/musicproduction/blob/master/gain-stage-buses.png "Gain Staging with Basic Buses")

#### Key Mixing Steps

. Create buses as above or as desired.
. Gain stage as above or as desired.
. Lowend Bus balance: with Drum Bus gained to -3dB VU on the kick, a simultaneous bass and kick hit should kiss 0dB VU on the Lowend Bus.
. Add a very conservative glue compressor/reverb on the Mix Bus.
. Bring in a professionally mastered reference track that sounds similar to what you're aiming for.
. Gain down the reference track so it VUs at a similar level as the Mix Bus.
. Volume and Pan TODO

#### Specific Track/Effect Mixing Tips

##### Drums

* Use a signal generator, gated from the specific drum track, to add meat to a drum. ~50Hz works ok for a kick. e.g. Tone Gate in Reaper.
* Tape saturation can sound great on drums to give them a warm compression.
* Gate out drums between hits to create headroom/clarity and remove mud. 
* Very high compression with a long release on a drum room mic can add a nice meat to a drum mix when blended judiciously. EQ may be needed after the compressor to cut anything annoying.
* Cutting the close drums to room mic only during a song's quiet/low break can create good energy when the break ends.
* Reverb pre-delay can embiggen a snare and make it sound less unnatural by smoothing the decay wash.

##### Bass Guitar

* Compress bass to give consistent volume and punch
* Subtle bass saturation/distortion on a sidechain and blended in will fatten up a bassline. Reduce lowend freqs on the sidechain as it gets dirtier - emphasise mids.

##### Piano/Keys

* Wide stereo keys are great for keys/vocal heavy music, but the more complex the mix, the more you probably need keys in mono so they have space in the mix.

##### Vocals

* Sidechain and pan a 1/4 note delay with a low pass filter to give a nice space and ambience without a washy reverb
* Hard pan widened doubled harmonies to add huge presence
* Vocal stutter on a long drawn out phrase by slicing (e.g. on 16ths/32nds) and muting.
* Telephone/lofi vocals with EQ with low+high pass filters, and boost the nice midtone. Maybe use on a delay.
* De-ess every vocal to remove annoying sibilance. 

##### Automation

* Judiciously mute tracks when they're not adding something that's needed
* Automate the fader as an EQ before tweaking specific EQ

##### Panning

* Kick/snare/bass/vocal in the centre
* you can smear/widen a part left and right by sidechaining with a < 30ms delay panned opposite
* Check the mix in mono to verify it will sound ok in the real world. Correct lost parts with volume and EQ.

##### Volume

* Ride faders to emphasise different parts or e.g. stop a vocal note/phrase being lost under instruments.
* Work in 3dB steps to make audible differences.
* Automate drum overheads up during more energetic parts

##### EQ

* Consider a light High Pass Filter on every track to remove mud. If you can notice the effect thinning the mix, it's too much.

## Mastering

TODO

## Ancillary & Release

TODO
