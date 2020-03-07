## EMOSPEECH-DATASET version 0.1

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

possible values of keywords,environments,emotion is described below

### Keywords:
 - help
 - bacho
 - stop
 - no
 - go
 - yes
 - **background**

### Emotions:
 - Happy
 - Angry
 - Fearful
 - Calm
 - **None**

## Environments:
 - safe
 - gunshots
 - glass break
 
 **NOTE** -  ```background``` represents is absense of keyword not an actual keyword
