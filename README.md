# Youtube Text Analysis Case Study of BabyFace NPR Concert
Text Analysis of Youtube Comments on BabyFace NPR performance
https://github.com/PauloDaguvnor/Youtube-Text-Analysis---Case-Study-of-BabyFace-NPR-Concert/blob/main/babyface-tiny-desk.png

BabyFace, Kenny Brian Edmonds, is a popular American singer, producer and songwriter.
Recently, he performed at NPR’s Tiny Disk for the June Black History Month. Tiny Desk is a video series of live concerts where artists come to perform, giving fans the pleasure of experiencing their favourite artists live. Tiny Desk has hosted popular artists ranging from Burna Boy of Nigeria to Mariachi.

Babyface performed in June but what made him special aside from his great catalogue was the calibre of backup vocalists he had with him.
- Tank
- Avery Wilson
- Chante Moore
These were successful artists in their right but they were excited and honoured to back up the great Kenny Edmonds.
The YouTube comments on Baby Face's performance were collected to measure the sentiments and discover topics people discussed.

# Data Collection
Data was collected using the YouTube API in Python. YouTube offered an API which could be used to obtain comments on a particular video.
After registering with Google Cloud API, we search for Enabled API and services and select YouTube Data API v3

# Analysis and Finding
I have attached the Python code to the repository
https://github.com/PauloDaguvnor/Youtube-Text-Analysis---Case-Study-of-BabyFace-NPR-Concert/blob/main/BabyFace_NPR_Youtube_Text_Analysis.ipynb

# Conclusion
Given the overall analysis, BabyFace aka Kenny Edmonds is whose talent for songwriting and music performance is established in the comments as dominating topics.

From the comment exploration, we see that most of the comments are in English, making it easier for the sentiment and topic analysis models to evaluate.

The Vader model performed well in classifying the comments despite the limitations and will be considered suitable because YouTube comments are also considered social media comments which VADER is suited for.
The result of the Vader model can be confidently used to assess the music performance of Baby Face and his band as we validated the result based on the top extreme comments.

For the Topic modelling, we see the major classification around general admiration for Babyface’s artistry, songwriting prowess and background vocalists’ ability. The LDA model performed well in grouping the topics.
