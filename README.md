# Analysing the political content uploaded on YouTube near Indian Elections

Social media platforms such as Facebook, Twitter (now X), Instagram, and YouTube have emerged as powerful ecosystems for information generation, dissemination, and consumption, engaging vast user bases across the globe. Business corporations and public institutions increasingly leverage these platforms to gauge public sentiment, influence discourse, and market products or services. Simultaneously, media organizations and journalists utilize digital platforms and web portals to propagate news, current affairs, governance initiatives, and political developments, thereby shaping public awareness and opinion. Among these platforms, YouTube has witnessed a significant user shift toward video-centric content, especially during politically sensitive periods such as elections. Despite this trend, there remains a critical research gap in quantifying the impact of YouTube-based news channels on governance narratives and ideological discourse. Notably, YouTube videos have, in several instances, triggered public outrage and mass mobilization, particularly during general and state elections in India. This study investigates the role of YouTube in ideological framing and issue-based discourse during the 2019 Indian General Elections and the 2023 Karnataka State Elections. It introduces a novel dataset comprising videos from the top 10 English news channels (ranked by TRP) over the three months leading up to each election. The research proposes a fine-tuned, text-based classification model capable of accurately and efficiently categorizing YouTube video content as pro-government, anti-government, or neutral. Furthermore, the study presents a temporal analysis of content trends across electoral cycles, highlighting shifts in thematic focus and ideological tone. The proposed model has significant implications for political parties, media strategists, and governance bodies, offering a valuable tool for monitoring public discourse, assessing policy perception, and guiding strategic communication. It also provides a framework for real-time citizen feedback on government initiatives and policy interventions.

## Contributions

1. An original dataset of YouTube videos posted 3 months before the Indian General Elections of 2019 and Karnataka State Elections of 2023.
2. A word-frequency-based mathematical model for manually labeling a YouTube video as pro-government, anti-government, or neutral based on a score.
3. Analyzing the trends in the dataset and how these trends change as the election date approaches.
4. Deep Learning textual models trained on the dataset to classify any video as pro-government, anti-government, or neutral.
5. A Large Language Model in-context trained on a subset of data to assess whether it exhibits a bias toward a specific political party or remains neutral.

## Original questions

1. How much pro-government, anti-government, or neutral content is uploaded on YouTube during the election year, and how does its quantity vary near the election period?
2. Are citizens interacting more with a particular type of content uploaded on YouTube near elections or are citizens consuming content wisely?
3. Is there a particular news channel which is constantly favouring or opposing the current government, or are they all uploading neutral content?
4. Can we label any Indian news YouTube video as pro-government, anti-government, or neutral?
5. Will a Large Language Model in-context trained on a subset of these transcripts be biased towards a party or will it stay neutral?

## Conclusion

The news media tend to upload more ProGov and Neutral videos on their YouTube channels near the election date. The amount of AntiGov videos stays at an all-time low and completely disappears a few weeks before the elections. Furthermore, consumers interact more with ProGov and Neutral videos than they do with AntiGov videos. The interaction of people with only ProGov and neutral news makes them live in an eutopian bubble, where they assume nothing is wrong. From the word clouds created for the pre-election period, it becomes very clear that the media is negligent towards national and state matters. The main focus of the media remains talking about Pakistan and irrelevant matters, only highlighting the plus points of the government, instead of questioning the government over topics of public interest. 

The pre-trained textual models perform decently on the collected and mathematically labelled dataset, with the highest training accuracy of 99.9% and the highest testing accuracy of 74.7% for Indian General Elections. Similarly, for the Karnataka State Elections, the model achieved a training accuracy of 99.9% and a testing accuracy of 77.02%. Finally, the Large Language Model trained on a subset of the dataset performs neutrally on the asked questions. The model does not favour a particular party, but that can also be because of the security mechanisms built in the language model.

## Future work

This work can be extended to include more elections from Indian history, especially the elections where the working government changed, to get a more holistic answer to our questions. Additionally, more textual models can be trained to achieve a better testing accuracy on our dataset. Finally, with enough resources, a custom Large Language Model with no security barriers can be trained to give a transparent view of the type of the content uploaded on YouTube near Indian elections.

## Details

The [final report](https://github.com/Saransh-cpp/CSSProject/blob/main/report.pdf) has more detailed information about the work. A publication based on this work is under review.

## Contributions

The work was carried out by Saransh Chopra and Nikunj Saini under the supervision of Prof. Sachin Kumar at the University of Delhi.
