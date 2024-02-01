# Mental-Health-Datasets

The **DatasetMH.xlsx** excel corresponds to a corpus of mental health in social networks labelled with polarity and stigma. In particular, the corpus consists of 2,287 comments labelled with polarity (positive, negative, neutral) and stigma from comments on Instagram posts about celebrity mental health disclosures:
1. Polarity: It consists of giving a positive, negative or neutral/undefined value to the comments in response to the disclosure or description of the symptomatology in the post. Positive polarity reflects understanding, encouragement or even admiration of the publication. E.g., “Cheer up, we love you".”. Negative polarity is assigned when the person expresses negative opinions, usually questioning the post with ironic, sarcastic or even mocking and disparaging comments. E.g., “how you show that you don't know what depression or anxiety is, shame on you!”. Neutral or undefined polarity is assigned in cases where no clear opinion is detected or can be interpreted in both directions. E.g., “take medication, it will help you" "and your partner?”
2. Stigma: stigmatising responses to comments are behaviours in which negative beliefs and emotions towards MH problems are expressed. Stigma manifests in a variety of forms including rejection and anger against the person, which may extend to contempt or mockery, belittling their problem. E.g.,"What a desire to draw attention to yourself"; "what you have is a story"; "you're so inconsistent and seeking the limelight". Because socially we know that "stigma is wrong" many rejection comments are made in an ironic or sarcastic way. E.g., and how do you write on insta?"; "better information from someone who doesn't have a current account". Additionally, anger is shown by arguing that such posts "trivialise or commercialise" MH. E.g.,"don't come and tell me your false stories of overcoming, without even knowing what it is to work...". Other times the stigma manifests itself as pity or sorrow for the person. E.g.,“It breaks my heart”; “poor thing”.

The file **DatasetMH_Emotions.xlsx** corresponds to a corpus of mental health in social networks labelled with emotions. In particular, the corpus consists of 2,287 comments labelled with five emotions plus a neutral class from comments on Instagram posts about celebrity mental health disclosures. These emotions are:
+ Love/admiration: Emotions present in Fredrickson (2013) and Plutchick (2001) models where admiration, approval and love are closely related.
+ Gratitude: Present in recent models (Ekman, 2004; Fredrickson, 2013), the messages imply a sincere appreciation for sharing mental health-related content on social networks. 
+ Comprehension/empathy/identification: Present in Plutchick (2001). They involve interest in and understanding of the message, including self-identification with the situation or context.
+ Sadness: This primary emotion (Ekman, 2004) is produced by events that are not pleasant and that denote heaviness. It includes many manifestations of pity for the person.
+ Anger/contempt/mockery: This category involves responses of irritation and attacks on the person as ridiculous and superficial (Ekman, 2004).
+ Neutral: This category corresponds to messages without emotions.

The labelling process of both datasets was divided into two phases: an initial phase with a pilot corpus (N = 787 comments) and a second phase focused on the development of the corpus with all the comments of the selected posts (N = 21151). The same methodology was followed in both phases: once the comments were collected, the corpus was cleaned, and then two independent experts were responsible for labelling each category. A third expert then reviewed the comments to resolve discrepancies. In the third and final phase, a final corpus for application to the machine learning algorithms is built from the large corpus (N = 2287). 

# Contact

This development belongs to the MentAI (Mental health Artificial Intelligence) project. The main contacts of the team is Noemí Merayo, Teresa Clara González Sanguino and Alba Ayuso Lanchares, whose e-mail addresses are as follows:

noemer@uva.es
clara.gonzalez.sanguino@uva.es
alba.ayuso@uva.es

