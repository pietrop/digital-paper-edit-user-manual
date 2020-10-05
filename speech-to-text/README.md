# Speech to text options

There are three options for speech to text APIs that you can use with this system.

Check them out individually for extra setup instruction.

{% hint style="danger" %}
Unfortunately **Speechmatics** is no longer an option as they discontinuing their web portal \(meaning the access to STT with API key will no longer be supported\) from 30th of Sept 2020. See their [deprecation notice for more details](https://www.speechmatics.com/transcription-web-portal-deprecation-notice).
{% endhint %}

1. ~~~~[~~Speechmatics~~](speechmatics.md)~~~~
2. [AssemblyAI](assemblyai.md)
3. [Mozilla Deep Speech](mozilla-deepspeech.md) \(Open Source, need to download 1.8gig for the English language model\)
4. [Pocketsphinx](pocketsphinx.md) \(Open Source, integrate inside the app, no extra setup needed\)

## Overview

### AssemblyAI  <a id="ibm-watson-stt-service"></a>

* Free tier: 5 hours free per month
* Competitive [pricing at $0.0003 per second](https://www.assemblyai.com/pricing)
* Easy to setup credentials 
* Generally very accurate \(my opinion, judge for yourself\)
* For now only support for English but more coming soon

### ~~Speechmatics~~  <a id="ibm-watson-stt-service"></a>

* ~~1 hour free credit with new account~~ 
* ~~Easy to setup credentials~~ 
* ~~Generally pretty accurate \(my opinion, judge for yourself\)~~
* ~~~~[~~28 languages, see full list~~](https://www.speechmatics.com/language-support/) ~~~~
* ~~Including support for "accent agnostic global english".~~

### Mozilla Deepspeech  <a id="gentle-open-source-stt"></a>

#### Pros:

* Free as in free speech as well as in free beer.
* Working locally on your machine. No internet connection needed because of that, good for sensitive material.
* Open source
* requires to download 1.8gig for the English language model

#### Cons:

* Not as accurate as commercial STT but still pretty good \(in my opinion, but decide for yourself\).
* Only support US english STT.

[Check out for extra setup instructions for Mozilla Deepspeech ](mozilla-deepspeech.md).

### Pocketsphinx  <a id="pocketsphinx-open-source-stt"></a>

#### Pros:

* Free as in free speech as well as in free beer.
* working locally on your machine. no internet connection needed because of that, good for sensitive material.
* [Open source module in autoEdit ](https://github.com/OpenNewsLabs/autoEdit_2)originally extracted from [Videogrep](https://github.com/antiboredom/videogrep) project.

#### Cons:

* Not as accurate as IBM or Gentle.
* Only support US english STT.
* Transcription takes a little longer then the length of the media. \(eg 27 min takes 30 min to transcribe\).

[Pocketsphinx does not require extra setup to use.](pocketsphinx.md)

\_\_

