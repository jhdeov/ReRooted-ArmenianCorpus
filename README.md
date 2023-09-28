# Rerooted: Speech corpus of Syrian Armenian refugee testimonials
 
 The [Rerooted Archive](https://www.rerooted.org/) is an archive of spoken testimonials by Syrian Armenian refugees. The original archive contains almost 80hrs of transcribed speech. This repository is my workbench for slowly cleaning up transcripts from those recordings, to make them the archive be suitable as a speech corpus for work on linguistics and NLP. 

 | Speaker             | Duration (hh:mm:ss) | Converted to textgrid? | Word/phone-aligned? | Morphologically tagged? | Translated? |
|---------------------|---------------------|------------------------|---------------------|-------------------------|-------------|
| Ani   Avakian       | 0:42:56             | x                      |                     |                         |             |
| Ara   Boudakian     | 1:04:00             | x                      |                     |                         |             |
| Dikran   Sazian     | 1:26:00             | x                      |                     |                         |             |
| Garbis   Arabatlian | 0:34:25             | x                      |                     |                         |             |

For my first pass, I automatically convert the SRT transcripts into TextGrids (using [SrtToTextgrid](https://github.com/rctatman/SrtToTextgrid)). I then manually clean up the TextGrid to catch missing words and to re-align the the utterance boundaries. It takes around 10hrs to clean up 1hr video. My goal is to this first pass for the first 10 recordings, and then go from there.
