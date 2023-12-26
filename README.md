# libritts-r-f0-ranges

This repository provides the results of an investigation into speaker-wise fundamental frequency (F0) search ranges of the [Libri-TTS-R](https://www.openslr.org/141/) Corpus.

The Libri-TTS-R Corpus is a large English speech dataset consisting of numerous speakers.

F0 is a fundamental element representing pitch information in a speech signal, crucial for tasks such as speech synthesis and voice conversion.
Accurate estimation in F0 estimation algorithms is recommended through the proper setting of the F0 search range.

Therefore, this repository offers the following contents:

- `spk_info.yaml`: A file detailing the recommended F0 search range specified by the minimum and maximum F0 values, along with the number of utterances per speaker in the LibriTTS-R Corpus.
- `spk_info.csv`: The CSV version of `spk_info.yaml`.
- `obj_score.yaml`: The aggregated results of objective evaluations on F0, summarized for each speaker. Provided to assess the validity of the recommended F0 range.
- `obj_score.csv`: The CSV version of `obj_score.yaml`.
- `f0_histgrams`: A directory containing histograms of F0 occurrence frequencies for each speaker. The recommended F0 range is used for F0 extraction.

The license of this repository complies with the LibriTTS-R Corpus and is licensed under CC-BY-SA 4.0.
