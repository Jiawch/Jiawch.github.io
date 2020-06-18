# Singing Demos for "XiaoiceSing2"

Authors: Jiawei Chen, Xu Tan, Jian Luan

Abstract: This paper introduces XiaoiceSing 2, a neural-network based high-quality singing voice synthesis (SVS) system, which improves upon XiaoiceSing~\cite{lu2020xiaoicesing} with some specific designs: 1) We adopt FastSpeech as the acoustic model similar to XiaoiceSing while leverage Parallel WaveGAN as the neural vocoder instead of conventional WORLD vocoder to improve the voice quality. 2) To handle large range of frequencies caused by high sampling rate in singing voices (e.g., 48kHz vs. 24kHz in speaking voices), we propose a novel multi-frequency GAN on mel-spectrogram generation to model high-frequency details and ensure high-fidelity singing voices. Specifically, we split the full 80-dimensional mel-frequency into multiple sub-bands (e.g., low, middle and high frequency bands) and model each sub-band with a separate discriminator. 3) To model the large range of pitch in singing voices, we use fundamental frequency (F0) and voiced/unvoiced (V/UV) to better model pitch in the vocoder, and also carefully study the window/hop size in STFT to better align with the range of pitch. 4) To model the large range of duration on vowels in singing voices, we increase the length of the audio clip and enlarge the receptive field in the vocoder. 5) We further change the linear-scale STFT loss in original Parallel WaveGAN to mel scale to better align with human perception and thus improve the expressiveness. Experiment results show that XiaoiceSing 2 synthesizes singing voices with much higher quality than XiaoiceSing. More ablation studies verify the effectiveness of each design in XiaoiceSing 2. 

---

Note: Please ensure your web browser supports wav audio format. You can choose Microsoft Edge, Google Chrome, Firefox, Opera and Safari.

## Demo

