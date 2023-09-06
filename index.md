---
layout: default
---
# ScoreDec
  
## **Demo Sounds**
- VCTK (***fs***: 48 kHz) (codec bitrate: 24 kbps)

| Codec | Male (p232_005) | Female (p257_016) |
|:--|:--:|:--:|
| Natural | <audio src="res/audio/vctk48k_male/Natural/2.wav" controls preload></audio> | <audio src="res/audio/vctk48k_female/Natural/17.wav" controls preload></audio> |
| symAD | <audio src="res/audio/vctk48k_male/symAD/2.wav" controls preload></audio> | <audio src="res/audio/vctk48k_female/symAD/17.wav" controls preload></audio> |
| AudioDec | <audio src="res/audio/vctk48k_male/AD/2.wav" controls preload></audio>   | <audio src="res/audio/vctk48k_female/AD/17.wav" controls preload></audio>   |
| **ScoreDec** | <audio src="res/audio/vctk48k_male/SD/2.wav" controls preload></audio>   | <audio src="res/audio/vctk48k_female/SD/17.wav" controls preload></audio>   |
| Opus | <audio src="res/audio/vctk48k_male/opus/2.wav" controls preload></audio>   | <audio src="res/audio/vctk48k_female/opus/17.wav" controls preload></audio>   |
| **Opus_SPF** | <audio src="res/audio/vctk48k_male/opus_SD/2.wav" controls preload></audio>   | <audio src="res/audio/vctk48k_female/opus_SD/17.wav" controls preload></audio>   |

| Codec | Male (p232_007) | Female (p257_080) |
|:--|:--:|:--:|
| Natural | <audio src="res/audio/vctk48k_male/Natural/3.wav" controls preload></audio> | <audio src="res/audio/vctk48k_female/Natural/21.wav" controls preload></audio> |
| symAD | <audio src="res/audio/vctk48k_male/symAD/3.wav" controls preload></audio> | <audio src="res/audio/vctk48k_female/symAD/21.wav" controls preload></audio> |
| AudioDec | <audio src="res/audio/vctk48k_male/AD/3.wav" controls preload></audio>   | <audio src="res/audio/vctk48k_female/AD/21.wav" controls preload></audio>   |
| **ScoreDec** | <audio src="res/audio/vctk48k_male/SD/3.wav" controls preload></audio>   | <audio src="res/audio/vctk48k_female/SD/21.wav" controls preload></audio>   |
| Opus | <audio src="res/audio/vctk48k_male/opus/3.wav" controls preload></audio>   | <audio src="res/audio/vctk48k_female/opus/21.wav" controls preload></audio>   |
| **Opus_SPF** | <audio src="res/audio/vctk48k_male/opus_SD/3.wav" controls preload></audio>   | <audio src="res/audio/vctk48k_female/opus_SD/21.wav" controls preload></audio>   |


<sup>symAD: `symmetric AudioDec (autoencoder)` </sup>  
<sup>AudioDec: `AudioDec (encoder + multi-group HiFi-GAN vocoder)` </sup>  
<sup>**ScoreDec**: `the proposed ScoreDec` </sup>  
<sup>Opus: `opus w/ 24kbps for mono audio` </sup>  
<sup>**Opus_SPF**: `the proposed score-based post-filter combined with opus` </sup>  

##  Liability Disclaimer
<p align="justify">The demo page utilizes public speech datasets (<a href="https://datashare.ed.ac.uk/handle/10283/3443">VCTK</a> and <a href="https://www.openslr.org/60/">LibriTTS</a>) for demonstration purposes only, and we do not claim ownership over these speech samples. The Content of the demo files is provided "as is" and for general informational purposes only. We make no warranties regarding its accuracy or suitability. If you believe that any speech samples infringe upon your rights or violate any laws, please contact us to remove the demo files. We are not liable for any damages arising from the use or reliance on our demo page or open-source code. By accessing the demo page and using the open-source code, you agree to release us from any claims or liabilities related to its use. </p>
<br /> 

[Home](https://bigpon.github.io/)

<br />  
<br />