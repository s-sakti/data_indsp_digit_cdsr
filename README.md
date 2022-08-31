# INDspeech_DIGIT_CDSR

This is one of the first Indonesian speech datasets for connected digit speech recognition (CDSR). The data was developed by TELKOMRisTI (R&D Division, PT Telekomunikasi Indonesia) under the Asia-Pacific Telecommunity (APT) project. Although it was originally developed for a telecommunication system for hearing and speaking impaired people, it can be used for other applications, i.e., automatic call centers that recognize telephone numbers. 

## Text and Speech Resources

The text source is an adaptation of the official [English AURORA2 dataset](http://aurora.hsnr.de/aurora-2.html) for [noisy digit speech recognition tasks](http://dnt.kr.hsnr.de/aurora/download/asr2000_final_footer.pdf), which is also related to the Japanese version [AURORA2J](http://research.nii.ac.jp/src/en/CENSREC-1.html). So if you have these AURORA2 and AURORA2J, you will have an English-Japanese-Indonesian parallel dataset. It consists of connected digit tasks among the following digit words: 1 (satu), 2 (dua), 3 (tiga), 4 (empat), 5 (lima), 6 (enam), 7 (tujuh), 8 (delapan), 9 (sembilan), 0 (nol and kosong).

The recording is conducted in parallel for both clean and telephone speech, but we open only the clean speech due to quality issues on telephone speech. Each audio file is a single-channel 16-bit PCM WAV with a sample rate of 16000 Hz. The speech is recorded with 214 speakers (20-40 years). Both genders are distributed evenly. The age is limited to middle age (20-40 years), but they present a wide range of spoken dialects from different ethnic groups.


## Training and Test Dataset

As it is close to the official AURORA2 digit task, The data consists of 8440 training utterances (spoken by 55 Females, 55 Males) and 4004 testing utterances (spoken by 52 Females, 52 Males), which are equally split into four subsets (1001 utterances in each). These training and testing sets consist of about 8 and 4 hours of speech, respectively.

## File Format
"SPK00_F_XXXX" where "SPK00_F" represents the ID of the single female speaker and "XXXX" represents the sentence ID.

## License
This data is licensed under the Creative Commons Attribution-NonCommercial 4.0 (CC BY-NC 4.0) International License (see LICENSE_CC-BY-NC-4.0.txt).
You can use the data free for non-commercial purposes, but you have to cite our paper if your work uses our data in your publication. Furthermore, you are not allowed to create a copy of this dataset and share it publicly in your own repository without our permission.
Citation
