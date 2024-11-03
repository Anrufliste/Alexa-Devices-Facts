# Alexa-Devices-Facts
A(n upcoming) comprehensive collection of facts about different Alexa empowered devices.

## Support of Emojis

A visual archive of all Emojis, how they are visualized on black and white background. Done for FireOS (e.g. Echo Show 15) and OS (e.g. Echo Spot Gen 2). 

In the [linking overview](emoji/README.md) (white version), there is a traffic light color to indicate:
* 🟢 Full visual support
* 🟡 Particular visual support (no [combined Emoji](https://emojipedia.org/emoji-zwj-sequence), but the parts are displayed)
* 🔴 Unsupported (just a rectangle - for [combined Emoji](https://emojipedia.org/emoji-zwj-sequence) at least one part is not supported)

Additionally, there is an audio archive of English and German SSML generated Alexa audio for each Emoji. Those audio is present in English and German. 
In the Overview there those are linked with the text, generated via STT from those audio using Wisper large-v3 model in python on M1 Mac.
If the text is wrongly transcribed it is Strikethrough and manually corrected (heard and typed). 
For each audio is also a traffic light - for better differentiation it is not using circles but squares:
* 🟩 Full audio support
* 🟨 Particular audio support (no [combined Emoji](https://emojipedia.org/emoji-zwj-sequence), main Emoji is supported, but skin tone and/or gender is missing.
* 🟥 Unsupported or wrong text (completely unrelated - we are not judging Boxer vs. Boxing see above)

Scripts and other things used to generate those data will be added in the future.