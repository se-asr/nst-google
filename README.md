# NST Transcriptions by Google
Google's Cloud Speech-to-Text transcriptions of the NST Dataset

This repository contains the testing part of the [NST Acoustic database for Swedish (16 kHz)](https://www.nb.no/sprakbanken/show?serial=oai%3Anb.no%3Asbr-16&lang=en).

Along with the original transcriptions, it also contains the predicted transcriptions as provided by [Google's Cloud Speech-to-Text](https://cloud.google.com/speech-to-text) service. We hope that, by publishing this data to the public domain, other researchers can use this as a benchmark to evaluate their ASR systems against commercial services such as the one provided by Google.

The data can be found in the file `nst-test.csv`, which has the following columns:

- **wav_filename**: path to the sound file in the NST Testing set
- **transcription**: the original transcription provided in the NST Testing set
- **google_transcription**: the transcription predicted by Google's Speech-to-text service
