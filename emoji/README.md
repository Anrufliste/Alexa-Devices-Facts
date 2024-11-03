# EMOJIs on ALEXA devices
While using APL with a text Element on an Echo Show, I recognized that not all emoji have been supported. So in late 2019 I made an analysis of every available emoji and discovered that back then 410 emoji have not been supported. I published this result within a picture of all unsupported emoji:
* in an [article about APL](hhttps://github.com/Anrufliste/Web-Mobile-Developer/blob/main/wmd_0220_S058_069.pdf) in the Web & Mobile Developer Magazin 02/20
* in a [twitter post](https://twitter.com/anrufliste/status/1217137755643400198?s=21)

Here I try to keep up to date with the improvement of the APL emoji support as well as new emoji. For the later there are specialized sources like <https://emojipedia.org>

While my wife is using a lot of Emojis in text message, I recognized that Siri is using similar text for different. So I was curious how Alexa handles Emojis if they are part of TTS output. So
besides the visual support I also included Audio support, how Alexa is "speaking" out the emoji in English and German.

## EMOJI Info by groups

* [Smiley & People](Smiley_and_People.md) - (1283/2116) FireOS and (1887/2116) OS
* [Animals & Nature](Animals_and_Nature.md) - (175/212) FireOS and (198/212) OS
* [Food & Drink](Food_and_Drink.md) - (106/129) FireOS and (123/129) OS
* [Activity](Activity.md) - (322/335) FireOS and (332/335) OS
* [Travel & Places](Travel_and_Places.md) - (120/131) FireOS and (128/131) OS
* [Objects](Objects.md) - (200/230) FireOS and (222/230) OS
* [Symbols](Symbols.md) - (276/302) FireOS and (292/302) OS
* [Flags](Flags.md) - (253/259) FireOS and (259/259) OS

Last Update July 2024 based on [Emoji Version 15.1](https://emojipedia.org/emoji-15.1)

#### Legend
* 🟢 Full support
* 🟡 Particular support (no [combined Emoji](https://emojipedia.org/emoji-zwj-sequence), but the parts are displayed)
* 🔴 Unsupported (just a rectangle - for [combined Emoji](https://emojipedia.org/emoji-zwj-sequence) at least one part is not supported)

1st 🚦 is FireOS (eg. Echo Show 5 second generation) & 2nd 🚦 is OS (eg. Echo Show 15)


## Project Documentation

### Screen-Capturing

TBD: APL Script and Device Simulator to sent to Device

TBD: Browser & Camera Controlling

TBD: LEGO construction for fix and stable distance & touch simulation for Echo Show 15

### Audio-Capturing

TBD: SSML Script and Device Simulator

TBD: Browser Controlling

TBD: STT for getting the text via AWS and local on Mac