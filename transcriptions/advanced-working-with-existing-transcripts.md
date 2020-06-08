---
description: >-
  This is generally discouraged, but making a note in case anyone has a use case
  where they already have an accurate transcription they'd want to use with the
  app.
---

# Advanced - working with existing transcripts

At the moment the main workflow assumes you don't have transcriptions, and that you are using the app to generate those as well as to correct them if needed.

However there is an advanced workaround to add existing transcriptions if you have those. Eg when working off scripted material that is read out loud by a presenter or etc..

1. Use [DeepSpeech](../speech-to-text/mozilla-deepspeech.md) or [pocketsphinx](../speech-to-text/pocketsphinx.md) as [STT option ](../setup.md)
2. [Create a transcription](create-a-new-transcription/) with your media 
   1. \(this assumes you have [created a project](../projects-1/create-a-new-project.md) already\)
3. Once the automated STT from [DeepSpeech](../speech-to-text/mozilla-deepspeech.md) or [pocketsphinx](../speech-to-text/pocketsphinx.md) as completed go in the view where you'd go to [correct the transcript](correct-the-text-of-a-transcription.md)
4. Select all of the text of the transcript, delete it and replace it with the text of the transcript you already have. 
5. The app will re-align the text you provided with timecodes at word level.

{% hint style="warning" %}
For this workaround to succeed you'd need to paste the text without speakers or time-codes informations.  
\(Possibly from a plain text file with not a lot of formatting\)
{% endhint %}

6. You should then add speaker labels, and review the paragraph breaks [🤞](https://emojipedia.org/crossed-fingers/)

{% hint style="info" %}
Note that If there's enough of a need, and use case, we could consider adding a feature to do this with fewer steps. 
{% endhint %}

