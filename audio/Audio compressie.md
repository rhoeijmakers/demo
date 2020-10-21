# Digital audio

Different aspects of Digital Audio explained and demo’ed.  

For Mic to recording, to podcast stream, to wireless earphones. AAC all the way or use high quality uncompressed audio to compress later?

## Compression

Uncompressed digital audio files are large. There are compressions that are lossless (great for portability) and lossy (for standard playing and streaming). 

1. Uncompressed (WAV, AIFF, AU, PCM)
2. Lossless compression (FLAC, ALAC)
3. Lossy compression (MP3, AAC, WMA, OGG)

## Codecs

The codec is software that compresses an audio file. The word derives from Coding and Decoding. There are different brands of codecs. Some examples: AAC, MP3, WAV, WMA.

An audio file that is compressed with the AAC coded needs a files extension called M4A.

## Bitrate

Bitrate is the measure of the rate at which data is transferred from one point to another. It is measured in bits per second (bps), kilobits per second (kbps), or megabits per second (Mbps).

We also use bitrate to describe the fidelity of audio files. An MP3 file that was compressed at 320kbps, will have a much better dynamic range and sound quality to one compressed at 128kbps.

With higher bitrate, audio files with higher bit depth and sample rate can be sent wirelessly, thus increasing the quality of the audio. However, this means an increase in bandwidth used for transmission.

> Bitrate formula = Sample rate x Bit-depth x No. of Channels 

A typical, uncompressed high-quality audio file has a sample rate of 44,100 samples per second, a bit depth of 16 bits per sample and 2 channels of stereo audio. The bit rate for this file would be:

44,100 samples per second × 16 bits per sample × 2 channels = 1,411,200 bits per second (or 1,411.2 kbps)

![](https://www.headphonesty.com/wp-content/uploads/2020/03/Bluetooth-Audio-Codecs-Explained_Audio-Bitrate-Comparison.jpg)

## Sample rate or frequency

How many samples of data are taken per second. This is normally measured in hertz, eg an audio file usually uses samples of 44.1 kHz (44,100 audio samples per second).

Example: Actually a single voice signal occupies 8 kHz, not 8 kbps, of bandwidth. Each sample is quantized into 8 bits, yielding a rate of 64 kbps which is used universally.


## Bit depth, 16bit / 24bit 

For music, the bit depths you will come across are 16bit and 24bit. While the sample rate is concerned with capturing frequency accurately, bit depth is related to dynamic range.

Dynamic range is the distance between the quietest and loudest sounds in a piece of music, and the quality of the resolution within this range.

For many years 16bit was the standard, the depth used on CDs. While 16bit is still very common, 24bit is now becoming more widely used for Hi-Res (HD) audio. Consumers can now purchase music in lossless formats that support higher sample rates and bit depths.

![](https://tomsrayaudiomastering.com/wp-content/uploads/2017/03/bit-depth-OPT.jpg)

Bit depth is fixed for PCM encoding, but for lossy compression codecs (like MP3 and AAC) it is calculated during encoding and can vary from sample to sample.

[Bit depth comparison](https://youtu.be/IPGU_Wv9VgQ)

## HD Audio

As internet speeds have increased and technology has developed, lossless formats have become more popular as a means to distribute and purchase music. Music streaming platforms like Qobuz and Tidal are already using lossless files.

Digital HD formats such as FLAC, ALAC, WAV, and AIFF, are the choice of audiophiles and music collectors who are moving away from the physical medium.

![](https://homedjstudio.com/wp-content/uploads/2019/05/Audio-Formats-Bitrate-File-Size.jpg)

## Dolby Atmos surround 

The Apple AirPods Pro now support Dolby Atmos Surround, also referred to as Spatial Audio. Spatial audio with dynamic head tracking brings a theater-like surround-sound experience to the movie or video you're watching, so that it seems as if the sound is coming from all around you. The sound field stays mapped to the actor or action on the screen even as you move your head or your device.

## Microphone

Different types and the naming. 

## Wireless headphones

Wireless audio can be a bit confusing, and is super complex, especially when talking about codecs. Knowing which codecs are supported on your devices will help create a superior wireless audio experience.

At the bare minimum, make sure your Bluetooth audio devices support AAC as that will give you a solid experience across the biggest range of devices.
 
Apple only supports SBC and AAC on its devices. Everything purchased or streamed via iTunes or Apple Music is encoded over AAC. The only exception is the Mac, which supports aptX.

I learned that headphones that use a Lightning cable or Bluetooth have a Digital to Analogue Converter (DAC) inside the headphones. These include Apple's AirPods and EarPods.

## Audio in applications

| Application | Audio Codec | Sampling rate | Bit rate|
|:--|:--|:--|:--|
| Netflix | Multiple |||
| Whatsapp | OPUS |||
| CD | N/A | 44.1 kHz||
| FaceTime | AAC-LD |16kHz||
| AM Radio || 5 kHz ||
| Phone call || 8 kHz ||
| Apple Music | AAC |||
| Spotify Free | AAC | 44.1 kHz |128 kbits/s |
| Spotify Premium | AAC | 44.1 kHz | 256 kbits/s |
| Skype | SILK |Variable||


## Audio compression comparisons and examples

| Codec | Bitrate | Filesize |
|:--|:--|:--|
| [AAC](Glass-160.m4a) | 160 kbps | 16.3 KB |
| [AAC](Glass-256.m4a) | 256 kbps | 21.8 KB |
| [MP3](Glass-128.mp3) | 128 kbps | 13.4 KB |
| [MP3](Glass-256.mp3) | 256 kbps | 26.8 KB |
| [FLAC](Glass.flac)| 432 kbps |53KB|
| [WAV](Glass.wav)| 1411 kbps |155KB|
| [AIFF](Glass.aiff) | 2 mbps | 250 KB|

## Some example set ups

Audio pipelines found in the wild.

![](https://rob.hoeijmakers.net/demo/audio/images/audio-a.jpg)

![](https://rob.hoeijmakers.net/demo/audio/images/audio-r.jpg)
