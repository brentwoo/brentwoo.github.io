---
layout: post
title: "Visualizing Cute Meows"
date: 2018-01-30
---

I live with two cats with crazy different personalities. One called Lila, is stubborn and middle-aged, she's extremely cuddly and loves to sleep on beds next to you. The other called Kuma, is very young and playful, she doesn't cuddle too much but she comes out immediately if you start swinging a toy around. Kuma also has an incredibly cute meow, and just now meowed at me to come play.

Then I wondered, what do cute meows look like? Why is her meow so much cuter than when I do it? So let's pop it into Praat and see!

Kuma came into my room and I recorded a little conversation. Here it is, and here is the associated spectrogram with pitch tracking. The spectrogram, the shaded gray background, shows the different qualities of the sound, and is tough to interpret without some phonetics training (I sure don't know much about it). The line is the 'pitch', also called fundamental frequency or f0. It is the lowest, most prominent frequency of the sound, and what a listener would identify as the "musical note" were you to sing that pitch. Orchestras tune to A4 at 440 Hz, and there are a zillion other estimates and measures but in general male voices average at 110 Hz and female voices at 211 Hz. Cats, apparently, meow at 550 Hz.

<audio controls>
  <source src="{{ site.url }}/assets/total-pitch.mp3" type="audio/mpeg">
Your browser does not support the audio element.
</audio>
<center><img src="{{ site.url }}/assets/total-pitch.png" style="width:780px; height:auto"></center>

I then took the second and third tokens, where Kuma calls and I'm responding by copying the sound. Already you see that Kuma has a much higher-pitched sound than me (average 559 Hz). (My average, non-excted reading pitch is 107 Hz) Turns out when I tried to mimic it, I still ended up producing a much lower-pitched sound (276 Hz) than intended. You can also see what I was interested in—how the spectral qualities differ. I don't really know how to interpret the spectrogram, but you see that for my voice there seems to be more "noise", more formants/harmonics? than for Kuma, whose voice seems to be "purer". I suppose that's what timbre is; the difference between a richer sax (me) and a more pure flute or piccolo (Kuma).

SO. I wonder what would happened if we evened things out a little. What if I really did produce the same pitch as Kuma, what would it look like? Well for some reason I tried and Praat wasn't really able to make a good spectrogram of my sound (if you have any hints on why this is let me know). So I thought I'd try a little pitch manipulation. 

In the long sound file, you can Extract the selected sound segment. In the Object window, you select that Sound, and select Manipulate. If you View & Edit that Manipulation object, the view will be mostly the same, except there are different colors over pulses, pitch, and duration, and there is no spectrogram. For some simple pitch manipulation, select the whole segment, go to Pitch > Shift pitch frequencies, and enter the value: a positive value will increase the pitch, a negative will lower it. Since I was manipulating my voice I wanted to put in a positive value, so I increased it to the average of Kuma's sound, to about 550 Hz. Then to get it as a separate Object, File > Publish Resynthesis. If you open up that Object, then you can see the spectrogram.

This is the result. On the left is Kuma's original, unmanipulated sound, and on the right is my manipulated, pitch-shifted sound.

<audio controls>
  <source src="{{ site.url }}/assets/kuma-pitch.mp3" type="audio/mpeg">
Your browser does not support the audio element.
</audio>
<audio controls>
  <source src="{{ site.url }}/assets/me-pitch.mp3" type="audio/mpeg">
</audio>
<center><img src="{{ site.url }}/assets/kuma-me-pitch.png" style="width:780px; height:auto"></center>

Still looks way different (as expected)! Even though we're producing the same pitch contour, my sound is much "richer" (I'll just casually use that word, ignorant of its precise meaning in phonetics), and it's clear that Kuma's is much "purer". It must be that pure quality that lends Kuma's sound to being so much "cuter", not just the pitch.

For kicks, here's the equivalent musical note, a C♯<sub>5</sub>, played out of tune on a crappy plastic recorder (my flute is off-limits for now, for mysterious reason...).


<audio controls>
  <source src="{{ site.url }}/assets/recorder-cis-pitch.mp3" type="audio/mpeg">
Your browser does not support the audio element.
</audio>
<center><img src="{{ site.url }}/assets/recorder-cis-pitch.png" style="width:350px; height:auto"></center>

It also sounds AND looks distinct from both the cat and human sound. I lack the words to describe the visual and sonic differences.

And for additional kicks, here's what Kuma looks and sounds like pitched-down.

<audio controls>
  <source src="{{ site.url }}/assets/kuma-down.mp3" type="audio/mpeg">
Your browser does not support the audio element.
</audio>
<center><img src="{{ site.url }}/assets/kuma-down.png" style="width:350px; height:auto"></center>

Big cat!











