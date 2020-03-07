## EMOSPEECH-DATASET version 0.1
<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.

### Data Description

> folder name represents the location from where the audio is collected.


> Format of this datset is described as below

```
keyword-environment-emotion-timestamp-hash.wav
```
example 1 :- 
```
bacho-safe-angry-1562907046662-d14a028c2a3a2bc9476102bb288234c415a2b01f828ea62ac5b3e42f.wav
```
here, bacho is keyword, safe is environment, and angry as emotion

example 2 :-

```
background-safe-None-20190701193438-d14a028c2a3a2bc9476102bb288234c415a2b01f828ea62ac5b3e42f.wav
```
**NOTE** - Hash value ```d14a028c2a3a2bc9476102bb288234c415a2b01f828ea62ac5b3e42f``` represents Unknown user

possible values of keywords,environments,emotion is described below:

### Keywords:
 - help
 - bacho
 - stop
 - no
 - go
 - yes
 - **unknown**
 - **background**

### Emotions:
 - Happy
 - Angry
 - Fearful
 - Calm
 - **None**

### Environments:
 - safe
 - gunshots
 - glass break
 
 **NOTE** -  ```background``` represents absense of keyword, it is not an actual keyword, and ```unknown``` represents keyword that are not present in list

### Citation

Please consider citing.
```
@misc{1910.13801,
Author = {Subham Banga and Ujjwal Upadhyay and Piyush Agarwal and Aniket Sharma and Prerana Mukherjee},
Title = {Indian EmoSpeech Command Dataset: A dataset for emotion based speech recognition in the wild},
Year = {2019},
Eprint = {arXiv:1910.13801},
}
```
