# ReRooted: Speech corpus of Syrian Armenian refugee testimonials
 
 The [ReRooted Archive](https://www.rerooted.org/) is an archive of spoken testimonials by Syrian Armenian refugees. The original archive contains almost 80hrs of transcribed speech. This repository is my workbench for slowly cleaning up transcripts from those recordings, to make the archive be suitable as a speech corpus for work on linguistics and NLP. 

I automatically convert the SRT transcripts into TextGrids (using [SrtToTextgrid](https://github.com/rctatman/SrtToTextgrid)). I then manually clean up the TextGrid to catch missing words and to re-align the utterance boundaries.

The repo contains the cleaned up TextGrids. The accompanying sound file is stored on Google Drive. The link to the sound file is found in the [metadata](/metadata.tsv) file.

There are English translations available on YouTube, and we will eventually like to integrate them with the corpus.

The data is also cataloged at the [Mozilla Data Collective](https://mozilladatacollective.com/datasets/cmp4ijosh00h9mp078ggnaatm).
