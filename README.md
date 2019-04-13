# mp3encode
Command-line application that turns a directory of WAVE files into MP3s. 

This is an educational project - I guess there are more versatile encoders out there for real-world use. I was tasked with it for a job application, to prove my ability to develop portable, concurrent multimedia software.  

I am sharing my results in the hope that it might be a useful example for LAME usage.

## Requirements
I can't provide the full specification (it is not my work), but the gist of it was:
 * find all *.WAV files in the given directory.
 * MP3 files to be put in same directory.
 * Do not process subdirectories.
 * Use all available CPU cores efficiently.
 * Use sensible encoder settings.
 * Use LAME library for encoding and link to it statically.
 * Use pthread library - on Windows, too.
 * Compile on Windows and Linux.
 
# NO MORE CHEATING
Sorry guys, but in case you're applying to you-know-where - find your own solution :)
All code removed from this repo (including history).
