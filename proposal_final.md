# FAKE NEWS DETECTION

<img src="fakenews.jpeg" width="700" height="400">







## What is your issue of interest?

Fake news, which is defined as a false tale created with the purpose to deceive, has been heavily blamed for the outcome of the 2016 US presidential election. While Facebook's CEO, Mark Zuckerberg, issued a public statement [1] denying that the company had any influence on the election's outcome, Facebook and other online media outlets have begun to create tactics for detecting false news and preventing its spread. "This is an area where I feel we must move very carefully," Zuckerberg wrote, admitting that identifying false news is challenging. It is difficult to determine the truth. Fake news is becoming a growing threat to our society. It is usually produced for business purposes in order to attract viewers and create advertising income. People and groups with potentially harmful goals have been known to spread fake news around the world in order to influence events and policy. It's also believed that the spread of fake news influenced the outcome of the 2016 US Presidential Election [2].

## Why is this issue important to you and/or to others?

Nowadays, the technical advancements and the widespread use of 4G networks, consumers can readily access countless news sites. But have we thought about the possibility that a news item could have entirely different versions? I believe that fake news, which has contributed to social unrest in many parts of the world, is mostly to blame for this.
Most importantly, society is typically divided into pro- and anti-government factions. People may attempt to hide the truth in such circumstances in order to advance their own political agendas, which raises concerns about the media sector. However, untrained logical thinkers are susceptible to being fooled by false information.

## Where do you get the data to analyze and help answer your questions?

This project's datasets were sourced from Kaggle [3]. The training dataset contains 20800 rows and 5 columns of data from various internet articles. In order to train our models, we had to undertake a lot of data pre-processing, as evidenced by the source code.
The following are the characteristics of a complete training dataset:
- id: a news article's unique identifier
- title: a news article's headline
- author: the news article's author
- Text: the article's text; in some situations, it is incomplete.
- label: a marker that indicates that the article is potentially untrustworthy                                        
- 1: Unreliable 
- 0: reliable

## What variables/measures do you plan to use in your analysis?

<img src="fakenews.jpeg" width="700" height="400">




The dataset's title, author, and text columns are where I would like to focus the most.

Text and title:

Does every piece of fake news use the same cliched terminology?   What search terms are frequently utilized in false news?

Author:

Are the authors of the majority of fake news stories the same? Decide if the author's next version will be a fake.

## What kinds of techniques/models do you plan to use
To evaluate the efficacy of fake news detection classifiers, I examined into four different machine-learning algorithms in particular
- Passive aggressive classifier

- Random Forest Classifier

- Logistic Regression

- Support Vector Machine

- Multinomial Naïve Bayes

## What outcomes do you intend to achieve (better understanding of problems, tools to help solve problems, predictive analytics with practical applications, etc?

The goal of this project is to create a tool that users may use to identify and remove news stories that include inaccurate or misleading information. To spot false articles and news, it is planned to carefully choose features.
- Documentation

- Data EDA

- Data Cleanup

- Implementing NLP algorithms

## The variables you use are all texts. How do you perform Machine learning?
Since the project's goal is to categorize and predict fake news, I would view this more as a classification problem and work on creating the classification report, which is used to evaluate how well a classification algorithm predicts using the precision, AU-ROC, recall, F1 Score, and support from our trained classification model. In order to compare the effectiveness and comprehend the metrics of each model, I want to use visualization techniques.
Since the dataset is mostly contianing textual data columns like "Text" , "Title" and "Subject", I would to do perform text preprocessing steps as follows:
- Removing punctuations like . , ! $( ) * % @
- Removing URLs
- Removing Stop words
- Lower casing
- Tokenization
- Lemmatization
