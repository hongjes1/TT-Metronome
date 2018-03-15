# TT-Metronome
Allows users to tap float-value tempos and play a metronome click at that tempo. Originally written in C#. Appropriate for Windows/Wine users. Will figure out how compatible it is within the Windows environment in the future.

## Tips ##
- The click sound in the folder is required for use. Generated using Audacity. If you want to supply your own sound, it must be called "click.wav".
- The tap button is highlighted at initial use. Click on it to start tapping the tempo.
- The millisecond wait period between clicks had to be an integer; therefore, it might not be 100% precise; however, it does get close (I used ticks to calculate the tap).
- Ctrl-R to reset the metronome works, particularly if restarting tapping.
