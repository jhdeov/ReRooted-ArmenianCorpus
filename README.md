# ReRooted: Speech corpus of Syrian Armenian refugee testimonials
 
 The [ReRooted Archive](https://www.rerooted.org/) is an archive of spoken testimonials by Syrian Armenian refugees. The original archive contains almost 80hrs of transcribed speech. This repository is my workbench for slowly cleaning up transcripts from those recordings, to make the archive be suitable as a speech corpus for work on linguistics and NLP. 

| Speaker              | Duration (hh:mm:ss) | Interviewee cleaned? | Interviewer cleaned? | Translation? | 
|----------------------|---------------------|----------------------|----------------------|----------------------|
| Ani Avakian          | 0:42:56             | x                    |    x                  |         |
| Ara Boudakian        | 1:04:00             | x                    |     x                  |        |
| Dikran Sazian        | 1:26:00             | x                    |      x              |           |
| Garbis Arabatlian    | 0:34:25             | x                    |   x                |            |
| Hagop Kereshian      | 0:30:51             | x                    |    x              |            |
| Kevork Mouradian     | 0:47:50             | x                    |    x               |            |
| Pardy Minassian      | 0:54:00             | x                    |    x              |             |
| Terez Barsoum        | 0:22:18             | x                    |    x               |            |
| Zarouhi Hamalian     | 0:43:29             | x                    |     x              |            |
| Talar Berberian      | 0:56:48             | x                    |     x              |            |
| Talene               | 0:38:52             | x                    |     x              |           |
| Vartanoush Shitilian | 0:33:02             | x                    |                      |          |
| Anjel Iranian        | 0:45:35             | x                    |                      |         |
| Shushanik Nargozian        | 0:20:03             | x                    |                |               |



For my first pass, I automatically convert the SRT transcripts into TextGrids (using [SrtToTextgrid](https://github.com/rctatman/SrtToTextgrid)). I then manually clean up the TextGrid to catch missing words and to re-align the the utterance boundaries. It takes around 10hrs to clean up 1hr video. I first prioritze editing the Interviewee's speech. I then fix the Interviewer's. I then finally merge English translations with the Armenian dialogue

My initial goal was to do a first pass for the first 10hrs of recordings. The interviewee tiers from the first pass have been cleaned. I'll now go through the interviewer tier.

The repo contains the cleaned up TextGrids. The accompanying sound file is stored on Google Drive. The link to the sound file is found in the [metadata](/metadata.tsv) file.
