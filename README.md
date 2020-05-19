# Urban Sound Classification
This dataset contains 8732 sound excerpts (<=4s) of urban sounds from 10 classes: air_conditioner, car_horn, children_playing, dog_bark, drilling, enginge_idling, gun_shot, jackhammer, siren, and street_music.

This sound classification challenge contains 5435 training samples with labels and 3297 unlabelled test samples. This classification challenge is hosted on Analytics Vidhya which can be found [here](https://datahack.analyticsvidhya.com/contest/practice-problem-urban-sound-classification).

# Understanding Audio Signals

##### Amplitude and Frequency
 **Amplitude** is the size of vibration and it determines how loud a sound is.  **Frequency** is the speed of vibration and it describes the pitch of the sound. 

##### Bit Rate and Sample Rate
The audio quality can be measured using bit rate and sample rate. **Bit Rate** is measured in Kilo-bits-per-sec and it is the number of bit encoded in a second of audio. A lower bit-rate would mean lower sound quality and lower file size. **Sample Rate** is measured in Hertz and it defines how many times per second a sound is sampled. Sampling is the reduction of a continious time signal to a discrete time signal. A sampler extracts samples from a continious time signals. So if an audio has a sample rate of 44100 Hz, it means that each second is broken down into 44100 parts and values at those timestamps are stored.

##### Spectorgram
A specrogram is a heatmap where the X-axis represents the time, Y-axis represents the frequency, with lower frequency at the bottom and the color determines the amplitude (how loud the sound is). So it basically shows how loud a particular frequency is at a particular time.

##### Fast Fourier Transform of audio signals
The fast fourier transform algorithm computes the discrete fourier transform (DFT) of an audio signal. It basically converts the audio from time domain to frequency domain. A time-domain graph shows how a signal changes over time, whereas a frequency-domain graph shows how much of the signal lies within each given frequency band over a range of frequencies.

![](https://en.wikipedia.org/wiki/Frequency_domain#/media/File:Fourier_transform_time_and_frequency_domains_(small).gif)

# References
[Amplitude and Frequency](https://www.howmusicworks.org/103/Sound-and-Music/Amplitude-and-Frequency)
[Understanding Audio Quality: Bit Rate, Sample Rate](https://micropyramid.com/blog/understanding-audio-quality-bit-rate-sample-rate/)
[What is a Spectrogram?](https://pnsn.org/spectrograms/what-is-a-spectrogram)
[Fast Fourier Transform](https://en.wikipedia.org/wiki/Fast_Fourier_transform)