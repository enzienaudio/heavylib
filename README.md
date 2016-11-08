# heavylib
Library of [Heavy](https://enzienaudio.com) compatible abstractions.

See the -help.pd patches for more information on each object.

Synthesis
---
`[hv.blepsaw]` - Band-limited PolyBlep sawtooth signal generator. [_more info_](https://github.com/cfloisand/pd-polyblep/blob/master/Source/polyblep~.c)

`[hv.pinknoise]` - Cheapish pinknoise generator. [_more info_](http://www.firstpr.com.au/dsp/pink-noise/)

`[hv.vline]` - Envelope generator, replacement for Pd's [vline~] object.

Processing
---
`[hv.compressor]` - Compressor unit with Threshold and Ratio parameters. (Attack/Release is fixed at 40ms)

`[hv.compressor2]` - Stereo version of `[hv.compressor]`.

`[hv.comb]` - Comb filter effect unit.

`[hv.flanger]` - Flange effect unit.

`[hv.flanger2]` - Stereo version of `[hv.flanger]`.

`[hv.envfollow]` - Cheap envelope follower.

`[hv.filter]` - Variable type filter with Frequency, Q parameters. Options are currently `lowpassq`, `highpassq` and `allpassq`.

`[hv.filter.gain]` - Variable type filter with Frequency, Q and Gain parameters. Options are currently `peakq`.

Math Operations
---
`[hv.tanh]` - Static non-linear waveshaper.

`[hv.gt]` - Signal-rate greater than ( > ).

`[hv.gte]` - Signal-rate greater than or equal to ( >= ).

`[hv.lt]` - Signal-rate less than ( < ).

`[hv.lte]` - Signal-rate less than or equal to ( <= ).

Logic
---

`[hv.dispatch]` - Utility for organising parameter interfaces to other abstractions.

`[hv.drunk]` - Randomised walk number generator.
