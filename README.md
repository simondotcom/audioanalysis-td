# audioanalysis-td

This audio analyser gathers informations from audio source and tranforms it to values that we can remap and use to create audio reactive programs. 

---------------------------------

Plug any audio signal (Audio File IN CHOP for instance) in the input.

---------------------------------


First output of the tox gives you amplitude of certain frenquency ranges (that you can modify in the tox parameters)

Second output gives you kick, snare and beat detection

Last output is the audio spectrum (you can choose the resolution in the parameters page aswell)

----------------------------------

HOW TO USE : 

- smoothing : smooths the signal coming out of different filters.
  - effect : proportion of smoothed signal added to the dry signal (dry/wet)
  - width : size (in seconds) of the smoothing. 0.2 is a good one to start with (depending on what you want).
  
! Be careful because increasing width too much will create a latency between the signal and the audio !

- frequencies : use it to modify filters frequencies according to your needs and depending on the music that goes in.

- beat detection : 
  - threshold : use it to refine the sensitivity of the detection
  - freq : sets the frequency of different components (kick/snare)
  
- spectrum : sets the resolution of the audio spectrum by modifying the number of points
