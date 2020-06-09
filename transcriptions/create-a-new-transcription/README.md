# Create a new transcription

{% hint style="info" %}
Make sure you have gone through the [initial setup](../../setup.md). Chose a [Speech To Text engine ](../../speech-to-text/)to use for your transcription. And added API credentials where appropriate as part of the[ initial setup](../../setup.md).
{% endhint %}

After[ creating a project](../../projects-1/create-a-new-project.md) click on `New Transcript`

{% hint style="success" %}
**You don't need to convert your media before adding it to the app.**

_**How does this work?**_   
 The app will read the metadata of the **original rushes** \(no matter how big the file\) and convert it to an audio and video preview.   
 The **audio** is used to send to the Speech To Text Engine to get a transcription.   
 The **video** is a lower resolution proxy used by the app to generate previews.   
 When exporting a **sequence** \(eg a paper-edit/programme script as EDL, XML etc... for a video editing software\) the app will use the original source metadata to reconnect to the high resolution rushes.
{% endhint %}

![](../../.gitbook/assets/screen-shot-2020-02-05-at-5.06.29-pm.png)

Choose a video or audio file and click `save`.

![Transcription will shop up as in progress until they are done processing](../../.gitbook/assets/screen-shot-2020-02-05-at-5.08.44-pm.png)

{% hint style="warning" %}
If you get an error when create a new transcription, feel free to take a screenshot of the error message and [raise an issue. See here for more detail on how to do that.](../../reporting-issues.md)
{% endhint %}

