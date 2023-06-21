# YouTube-Video-Summariser
A chrome extension to summarise long YouTube videos by utilising YouTube's transcript feature.

## Requirements
- The following python modules must be installed to run the API
  - ```flask```
  - ```youtube-transcript-api```
  - ```transformers```
![image_cover_f](https://github.com/Sanchariii/YouTubeSynops/assets/88083502/5589bbfa-7580-4045-aace-a48cc358fd5a)

*Pre-requisite Knowledge:* YouTube is an American free to use online video sharing and social media platform launched in February 2005. It is currently one of the biggest video platforms where its users watch more than 1 billion hours of videos every day.\
Closed captions are the text derived from the video which are intended for adding more details (such as dialogues, speech translation, non-speech elements) for the viewer. They are widely used to understand video without understanding its audio.
![demonstration](https://github.com/Sanchariii/YouTubeSynops/assets/88083502/26e0b889-fb13-46d1-80a4-06257dc2feb4)

*Use case Scenario:* YouTube has very large number of videos which has transcripts. Summarization would be especially helpful in the cases where videos are longer in length and different parts might have varying importance. In this sense, Summarization of the video might be useful in saving the viewer’s time. It will help in improving user productivity since they will focus only on the important text spoken in video. 

## Instructions
- Run ```app.py``` to start the summarizer API.
- Load the custom extension into any Chromium browser.
- Go to any YouTube video and click on the extension logo to start summarizing.
