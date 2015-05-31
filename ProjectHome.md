# Vavi Sound SPI #

## vavi-sound ##

| **SPI** |  **Codec** |  **Description** | **IN Status** | **OUT Status** | **SPI Status** |
|:--------|:-----------|:-----------------|:--------------|:---------------|:---------------|
| midi    | MFi        | Japanese cell phone format |  c            | o              | o              |
| midi    | SMAF       | YAMAHA cell phone format | c             | o              | o              |
| sampled | MFi        | Japanese cell phone format |  x            | o              | x              |
| sampled | SMAF       | YAMAHA cell phone format | o             | o              | o              |
| sampled | CCITT ADPCM | G711, G721, G723 | o             | o              | x              |
| -       | DVI ADPCM  | DVI ADPCM        | o             | o              | -              |
| -       | IMA ADPCM  | IMA ADPCM        | o             | o              | -              |
| -       | MA ADPCM   | YAMAHA ADPCM     | o             | o              | -              |
| -       | MS ADPCM   | Microsoft ADPCM  | o             | o              | -              |
| -       | OKI ADPCM  | OKI ADPCM        | o             | o              | -              |
| -       | ROHM ADPCM | ROHM ADPCM       | o             | o              | -              |
| -       | VOX ADPCM  | VOX ADPCM        | o             | o              | -              |
| -       | YAMAHA ADPCM | YAMAHA ADPCM     | o             | o              | -              |
| -       | YM2068 ADPCM | YAMAHA ADPCM     | o             | o              | -              |
| -       | ssrc       | resampling       | o             | -              | -              |

## vavi-sound-sandbox ##

| **SPI** |  **Codec** |  **Description** | **IN Status** | **OUT Status** | **SPI Status** |
|:--------|:-----------|:-----------------|:--------------|:---------------|:---------------|
| midi    | unknown    | MFi by unknown   | x             | x              | -              |
| midi    | ittake     | MFi by ittake    | x             | x              | -              |
| -       | ilbc       |                  | x             | x              | -              |
| -       | ldcelp     |                  | x             | x              | -              |
| -       | mp3        |                  | x             | -              | -              |
| -       | sse        | equalizing       | x             | -              | x              |
| -       | laoe       | resampling       | ?             | -              | -              |
| -       | rohm       | resampling       | ?             | -              | -              |
| -       | polyphase  | sox resampling   | o             | -              | -              |
| -       | resampler  | sox resampling   | ?             | -              | -              |
| -       | perfext    | sox resampling   | x             | -              | -              |
| -       | ssrc2      | resampling       | x             | -              | -              |
| -       | trironus   | resampling       | o             | -              | o              |
| -       | alac       | Aple Lossless Audio Decoder | o             | -              | x              |
| -       | rocococa   | QT wrapper       | o             | -              | -              |
| -       | twinvq     |                  | x             | x              | -              |
| -       | vsq        | YAMAHA Vocaloid  | o             | -              | -              |

## vavi-apps-mfieditor ##
## vavi-apps-mfiplayer ##
## vavi-apps-midieditor ##

## vavi-speech ##

| **Type** | **Description** | **Staus** | **SPI Status** |
|:---------|:----------------|:----------|:---------------|
| aquestalk | AquesTalk wrapper | o         |  o             |
| aquestalk2 | AquesTalk2 wrapper | o         | o              |

## vavi-util-tag ##

| **Type** | **Description** | **IN Status** | **OUT Status** |
|:---------|:----------------|:--------------|:---------------|
| mp3 v1   |                 | o             | ?              |
| mp3 v2   |                 | o             | o              |
| mp4      |                 | o             | ?              |
| ITCBox   | iTunes Artwork  | o             | -              |

### Legend ###

| o | ok |
|:--|:---|
| ? | not tested |
| c | under construction |
| x | ng |
| - | n/a |


---

&lt;wiki:gadget url="http://www.ohloh.net/p/461441/widgets/project\_thin\_badge.xml" height="38" border="0"/&gt;