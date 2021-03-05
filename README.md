# P5.sound-release-1.0.0
## Bug Fixes
* Fallback when AudioWorklet buffer array length is zero
 https://github.com/processing/p5.js-sound/pull/542 
* Remove extra callbacks for SoundFile cue 
 https://github.com/processing/p5.js-sound/pull/449 
* Fixed abnormal behaviour of audio output in p5.signal example section
  https://github.com/processing/p5.js-sound/pull/476
* Fixed error while playing sound through `p5.soundFile.play()` method
 https://github.com/processing/p5.js-sound/pull/542

## Infrastructure Improvements 
* Library is re-written in ESM ( ECMASCRIPT MODULES). 
* Audio Nodes are written as `Class` style rather than being  written as `function` style.
* Library using features of es6 like `let` , `const` keywords and many other es6+ features.
* Testing architecture has been made more clean and robust.
* All above listed improvements are part of [Divyanshu's](https://github.com/endurance21) GSOC-20 Project , more details can be found in his [wrap-up-post](https://github.com/endurance21/GSOC-20-WrapUp).
* Improvements in pre-commit-hook action  https://github.com/processing/p5.js-sound/pull/574

## Documentation Improvements 
* Fixed broken anchor tags in p5.Audioln
 https://github.com/processing/p5.js-sound/pull/450	
* Fixed typo  in p5.fft documentation
  https://github.com/processing/p5.js-sound/pull/433
* Added documentations for P5.oscillator APIs
 https://github.com/processing/p5.js-sound/pull/420
* Improved documentation of p5.soundloop
  https://github.com/processing/p5.js-sound/pull/437
* Fixed broken links in p5.panner3D documentations
 https://github.com/processing/p5.js-sound/pull/465
* Typo improvements in p5.soundloop reference
 https://github.com/processing/p5.js-sound/pull/557


	


## Deprecations
We have deprecated functionality in an effort to focus the API
* p5.Signal
* p5.SoundFile.processPeaks

