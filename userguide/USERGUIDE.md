<h1>User Guide</h1>

noiseCrush is a "Bitcrush" audio effect with a unique twist. Instead sampling audio at a consistent rate, a noise generator is used to sample audio when its value is below a threshold set in the UI which roughly corresponds to an average frequency. The result is an aggressive and "noisey" sample rate reduction that is well suited to material with sharp transients such as drums, percussion, and rhythmic textures.

<h2>Requirements</h2>
  <ul>Ableton Live 10</ul>
  <ul>Max For Live 8 (made with 8.1.5)</ul>

<h2>Usage</h2>

Add the file [noiseCrush.amxd](/devices/noiseCrush.amxd) to your preferred Max For Live Audio Effects Path.<br>
Drag and drop the patch into an available empty channel as an audio effect.<br>

<h2>Parameter Guide</h2>

<h4>Avg Sampling Rate</h4>
The average sampling rate of the effect.

<h4>Mix</h4>
The wet/dry mix of the effect.

<h4>Anti-alias filter</h4>
Turns on a simple lowpass anti-aliasing filter synchronized with the effect sampling rate.

<h4>Channel Crush</h4>
2-channel mode is a dual stereo effect where each of the left and right channels has their own noise channel. 1-channel mode has both left and right channels sharing the same noise generator.

<h4>Interpolation</h4>
A crude interpolation effect which smooths transitions between sample values over the set number of samples. 1 = no interpolation effect.

<h4>Bit Depth</h4>
A bit depth reduction achieved by rounding multiplied signal values.

<h4>Bit Round Type</h4>
The type of bit crush rounding. Values are ceiling (round up), nearest (round), and floor (round down).