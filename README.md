# Praat Scripts
Here are some of the Praat scripts from my own collection. I will be updating this repository as soon as I have something new to add.

## Opening and Saving Files
[open_all](./code/open_all.praat): its main purpose is to open all objects in Objects' window.

[save_raw](./code/save_raw.praat): saves all sound files in object's window as raw 16-bit little-endian files.

[save_all](./code/save_all.praat): saves all objects in the object window.

## View and Edit Files
[view_edit_all](./code/view_edit_all.praat): This script opens all wav files in the Praat Objects' window. If you want to open the files with their associated TextGrid, I have found [this script](./code/check2.praat) created by [Pauline Welby](http://aune.lpl.univ-aix.fr/~welby/PAGES/praat-fr.html) extremely useful.


## Process Sounds
[vowels](./code/vowels.praat): This script provides measures vowels formants (F1-F5) at multiple time points in stepwise manner from vowel onset (0) to vowel offset (100). The step it is set to five (5) but you may modify the code as you prefer. Caution is also required to set the parameters to the ones that address the physiological properties of your speakers. 

[vowel analysis](./code/tier_analysis_write): This script provides measures of F0, intensity, duration, and writes the output on a csv file.