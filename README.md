# About

Fork of the original EnvelopForLive, adding an extra E4L Master plugin named "E4L Master Satosphere" with the following features :
- Custom 31 channel decoder, modeled to match the speaker configuration of the Satosphere dome at Society for Arts and Technology in Montréal, Canada (https://sat.qc.ca)
- 32 channel output routing
- Output meter (post decoder)
- Multichannel output recorder (read below)
- Added a master EQ for emergency adjustments (notch that unexpected feedback frequency)

This version has been tried and tested on dozens of projects in live conditions with different artists and is considered stable as is (Windows / MacOS). The two last features listed above are still experimental. If not sure, do not use them.
I will try to update this repo whenever I'm reported something wrong, or when a significant update appears on the original EnvelopForLive repo.

Open to comments and extra features suggestions, as long as I feel they won't break what's already stable.

# Recorder

As noted above, this feature is somehow experimental and needs some polishing. However, it does work. Properly. The recorder feature is pretty simple, and allows you to record interleaved audio of your performance, or simply export a pre-written spatialized project into channel based audio.
Operation :
- Press the "=" button
- Name the file you want to record
- When ready, press the "o" (record) button on the right. It should become red.
- Press it again to stop.
- I planned to add a MIDI Note to record feature : All B note received will toggle the recording on and off. This said, while implemented in the patch, something's still missing to make it work. I promise it'll be updated soon.

Quick notes :
- The default format is .aiff, but you can change it for .wav
- Note that the .wav format imposes a 2GB filesize limit. Good to know if you record long projects with a high channel count.
- Multichannel files can't be re-opened in Ableton. You should use Reaper or similar alternatives to read / edit them (use the Explode Multichannel feature if needed). Else, simply use Wave Agent or FFMPEG to split it into mono files.
- Recording is 48KHz / 16bit, which should be enough. If you want more, go ahead and fix the M4L patch.

# About SAT

This fork of E4L was made to meet the needs some artists have when preparing shows for the Satosphere, an immersive A/V 18m dome equipped with a 31 channel speaker setup. This unique space is located in the Society for arts and technologies in Montréal, Canada, a research / art center where multiple tools for immersive creation have been tested, supported and developed over the years, including tools such as SATIE (https://gitlab.com/sat-metalab/SATIE)

Learn more here : https://sat.qc.ca

# About E4L

This is just a fork, but it couldn't have existed without the amazing work made by the [Envelop](http://envelop.us) team on their open source toolbox.

[Envelop](http://envelop.us) is a nonprofit organization that amplifies the connective power of music through immersive listening spaces and open source spatial audio software. Three-dimensional experiences of sound and music bring people together, catalyzing shared moments of inspiration, empathy and wonder.

Envelop for Live (E4L) is an open source audio production framework for spatial audio composition and performance. Envelop for Live operates within the music production environment of Ableton Live 10+ and Max for Live. Envelop for Live is designed to be a highly modular, flexible platform for artists to compose and perform spatial audio, and for developers to create new kinds of audio effects for the Ambisonics domain.

* [Join the Facebook Group for questions, tips, etc.](https://www.facebook.com/groups/E4LUsers)
* [Sign up for the Envelop email newsletter](http://www.envelop.us/connect/)
* [Learn more on the Envelop for Live Wiki](https://github.com/EnvelopSound/EnvelopForLive/wiki)

***E4L is free to use — but it takes time, energy, and resources to create and maintain. If you find these tools useful, please consider making a donation to support the Envelop nonprofit organization: https://www.envelop.us/membership-donations***


## Learn More

For more in-depth documentation and tutorials, see the [Envelop for Live Wiki](https://github.com/EnvelopSound/EnvelopForLive/wiki).
