## iblazr original protocol
Basical information about how working with iblazr original.

iblazr sync with the app by audio frequency.<br>
And it work only one way - iblazr only receives the signal from the audio jack, not sending it. 


## How works
You must generate audio signal and send to audio jack.

IOS:
 - for manualy generate signal: [iOS-Tone-Generator](https://github.com/picciano/iOS-Tone-Generator) 
 - official tool for iblazr original and iblazr 2: [iblazr SDK](https://github.com/ConcepterDev/iblazr-sdk-ios)
 
Android:
 - *soon*

NOTE:  iblazr is turning to `sleep` mode if it`s not active the for 60 sec. You must send special signal every 55 second for awake iblazr.

## Frequency values
    effect      | frequency (Hz)  | time
--------------  | -------------   | ------------
awake iblazr    |       800       | 200±150ms 
flash           |      15750      | 300ms (auto) 
pre-flash       |      10000      | until focus 
constant light  |    2500-9500    | infinite

## What it mean
you can control: 
  1. power of light by "constant light" mode - set frequency range from 2500 to 9500 Hz at time what you want 
  2. for preview - use "pre-flash" mode - set frequency an 10000 hz at time of until focus 
  3. for made selfie (by front cam) set 8000-10000 hz (you choice) at 1±0.5sec 
  4. for made flash - set 15750 Hz at 300ms time 

## Feedback
Send any questions to support@concepter.co or create new issue.
