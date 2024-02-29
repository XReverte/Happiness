# "Analysis of Influencing Factors on Personal Happiness: A Machine Learning Approach Using Multidimensional Data"

## Table of contents
- README.md --> Overview of the project, the goals, the tools used, and how to navigate the repository
- Happiness_XReverte.pdf --> The project itself
- encuesta.ipynb --> Sample code used for the 'Survey' study
- relookyou.ipynb --> Sample code used for the "Relookyou" case in the 'Personal' study

## Motivation
**Do we understand our happiness? Do we know what fosters it?** Perhaps we are too drawn to the ease and comfort of audiovisual content 'to help you disconnect,' relegating more enriching options that promote personal growth, such as reading a book, practicing sports, meeting new people, or simply reflecting. This 'comfort zone' in which our contemporary society finds itself could be a degenerative and corrupt spiral: work, distract oneself by watching a series, and sleep. Technological comforts, perhaps the *'soma'* of the 21st century, may provide immediate rewards and numb those who consume them, but do they truly lead to happiness? Reflections like those portrayed in *Aldous Huxley's 'Brave New World' (1932)* urge us to consider whether the pursuit of happiness should go further.

The pursuit of happiness and its determinants has been a recurring theme throughout human history. In this ever-changing world, where social dynamics and technologies evolve rapidly, it becomes even more plausible that the factors shaping happiness also undergo transformations. **Understanding these nuances becomes crucial**, not only for individual satisfaction but also for addressing collective challenges related to mental health and well-being.

In this context of exploration and discovery, the present work is dedicated to examining the **determinants of happiness**, adopting a multidimensional and analytical approach. Seeking to unravel the complexity of how an interconnection of factors affects the experience of happiness, and to contribute to enriching our understanding of the pursuit of authentic happiness in the present world.

To achieve this goal, we utilized two sets of datasets (*'Encuesta'* and *'Personal'*) and applied a combination of data analysis techniques and machine learning tailored to their particularities.

***'Encuesta'*** refers to a questionnaire aimed at describing the personal profile of the respondent and defining the set of activities and habits that most influence their happiness and well-being. These habits and activities (referred to as 'subtopics') are grouped into 8 different topics: hobbies, external aspects, sports, diet, social interactions, productive time, sleep patterns, and harmful habits or vices.

***'Personal'***, on the other hand, captures the daily activities and habits of different participants, as well as the target variable, the subjective evaluation of perceived happiness each day. Similarly to the 'Survey' dataset, these activities can be grouped into the same 8 topics.

## Goals
The main objective of this work is to **identify and understand the factors that influence individuals' personal happiness** in different contexts and situations. With this, we implicitly aim to **design a methodology** based on advanced data analysis techniques and machine learning that allows us to identify these influencing factors.

The intention is to **segment the respondents** based on their personal profiles and declared preferences, in order to **characterize these groups** according to their habits and activities to understand how different segments pursue happiness.

Regarding the *'Personal'* study, the intention is to analyze this diverse set of longitudinal data, **evaluating the relative importance of variables and factors in predicting personal happiness**, determining which of these factors have a more significant impact on individuals' quality of life.

In conjunction with the two approaches, participants will also respond to the survey, allowing them to be labeled based on their groups according to their segmentation. Analyzing the characterization of their groups in *'Encuesta'*, the aim is to **study the discrepancies** between the preferences declared by their group and the actual behaviors of the participants in the *'Personal'* study. The objective is to understand how these discrepancies can affect the perception of happiness, and also determine the **feasibility of clustering** to accurately segment the population based on the determinants of their happiness.

In addition to these objectives, which are more related to the methodology of our case study, this project aims to **contribute to the growth of knowledge about human well-being** by providing a more comprehensive understanding of how various factors interact to influence individual and collective happiness.

## Methodology
The methodology begins with the study of the ***'Encuesta'***.. Once the dataset has been appropriately processed, it was divided into 3 fractions: based on personal profile (*'pProfile'*), the topics that most influence happiness (*'topics'*), and their associated subtopics (*'subtopics'*). Each portion and the complete set (*'encuesta'*) were then clustered. Our intention is to segment the respective datasets using the 'K-means' technique, identifying significant differences between groups and constructing and assembling different machine learning models that predict the labels assigned to each dataset. The importance of features in predicting groups will be extracted, allowing us to identify which of the differences between groups are the most important.

Subsequently, in the ***'Personal'*** study, we will work with multiple longitudinal datasets. The purpose is to discern the variables that have the greatest influence on each participant's happiness. Different machine learning models predicting the daily level of happiness were constructed and assembled based on the various recorded activities, obtaining the importance of features in their prediction. Additionally, each participant also responded to the survey, allowing the determination of the groups to which they belong according to their various segmentations in 'Encuesta' ('pProfile', 'topics', 'subtopics', and 'encuesta'), and the presumed factors that most influence their happiness.

**Interweaving the two approaches**, this procedure aims to anticipate the most influential variables for each participant (*'Personal'*) according to their segmentations (*'Encuesta'*), providing guidance to correctly focus attention on the variables for each participant. Additionally, we can confirm or refute the generalities previously identified through the analysis of *'Encuesta'*. Specifically, for each participant, the activities were highlighted that, according to their segmentation, are assumed to have extreme influences (high or low compared to the rest of the groups), based on the analysis of differences between groups in *'Encuesta'*. These were then contrasted with the importance of features obtained in assembling predictive models of the happiness level in *'Personal'*.

**In summary**, this work addresses the determination of influential factors in personal happiness through two distinct studies, *'Encuesta'* and *'Personal'*. It employs techniques of statistical data analysis and machine learning to study differences between groups, segment and predict, in order to highlight the relevance of features in happiness. The intersection of both approaches seeks to understand to what extent segmentation of the population can provide insight into the variables that affect happiness in different groups.

## Results and conclusions
**Our study results** indicate that, overall, the characteristics predicted based on segmentation in the survey do not correspond too closely with the results obtained in the *'Personal'* study. Thus, there are discrepancies between the expectations, understood as the influence of variables on happiness based on segmentation, and the actual influences of the participants according to their personal study.

The **most influential aspects** on happiness vary depending on the participant, but topics and activities related to fatigue, external factors, and leisure time tend to be the most influential on participants' happiness.

The topic of **sports** was attributed with an influence, perhaps, lower than expected. This may be due to the lack of devices that successfully capture the appropriate variables among the different participants. Conversely, much importance was attributed to the aspect of **weather**, belonging to the topic of external circumstances, possibly for the opposite reason: the inclusion of too many variables capturing its information compared to other aspects.

The relationship between preferences, activities, and happiness is **complex and multifaceted**. The influencing characteristics are a combination of factors related to lifestyle, external aspects, social interactions, leisure time, and an endless list of other elements.

The respondents were successfully segmented based on their personal profiles and declared preferences, as well as the characterization of the groups formed according to their habits and activities, **understanding how different segments pursue happiness**.

We effectively analyzed personal longitudinal data, **determining the relative influence of variables and factors on participants' happiness**.

However, considering that there are discrepancies between expectations and actual influences, we conclude that **our segmentation is not appropriate for conjecturing the influential characteristics of an individual**.

Nevertheless, we consider the methodological framework designed to link both approaches and evaluate the accuracy of segmentation in predicting the influence of activities on an individual to be successful. Despite certain limitations, **we have achieved a better understanding of the factors influencing personal happiness**.

## Limitations
It must be acknowledged that this study is not without certain limitations that could have influenced the results and their interpretation. These limitations are essential for understanding the extent and applicability of the presented conclusions. Below are some of the key limitations that should be considered.  

The **sample size** used in this study, while providing valuable information, may not be representative of the population as a whole. Additionally, the sample may have lacked diversity in terms of various factors (demographic, socioeconomic, cultural, etc.). This lack of representativeness can limit the generalization of findings to broader and more diverse groups.

Despite efforts to standardize the measurement of subjective variables such as happiness, it is important to recognize that the nature of these measurements can be very complex. The scale used to assess happiness may have been **interpreted differently by participants**, introducing some subjectivity into the results.

Although efforts were made to collect accurate and reliable data, there is a possibility that some participants **may not have provided entirely accurate information** in their activity logs. This lack of precision could have affected the coherence and reliability of the results. In hindsight, handling missing values could have been addressed using prediction algorithms instead of relying solely on averages based on the day of the week and timely dates.

The study focused on a specific set of variables related to participants' preferences and activities. However, undoubtedly, there are **many other factors** that could play a significant role in predicting happiness and were not considered in this analysis.

Individuals' preferences and activities can change over time. The study is based on a **specific moment in the participants' lives**, not allowing for capturing the evolutionary dynamics of preferences over time.

Finally, the **lack of graphical representations** in the results is acknowledged. A simple, effective, innovative, and impactful visualization of the results is essential for clearly communicating the findings and impressing the reader.

These limitations highlight the complexity in researching happiness, as well as our own areas for improvement in the field of data science. However, despite these limitations, the results continue to provide valuable information about the interplay between activities, preferences, and happiness.

## Future work
The present study has provided valuable insights into the complex interplay between individual preferences, actual activities, and the experienced happiness of participants. However, it has become evident that the work has certain shortcomings. In future work, efforts will be made to mitigate these aforementioned limitations, and additionally, new areas for improvement and enrichment in research will be explored.

In an effort to improve the accuracy and understanding of the results, it is proposed **to further explore models**. This includes evaluating a wider variety of model hyperparameters and more suitable data processing methods. We will seek among a wider variety of approaches to enhance the identification of relationships between preferences, activities, and happiness, considering possible interactions and more subtle correlations that may have gone unnoticed in the present study.

To identify more robust patterns related to happiness, the intention is **to apply clustering techniques to personal data**. With this technique, participant records with similar characteristics and activities will be grouped together, allowing for a deeper understanding of how certain combinations of activities can influence happiness.

## Contributions
Although the results may not precisely identify influential characteristics through population segmentation, they lay the groundwork for future attempts. Success in this approach could provide guidance in formulating more effective strategies to promote happiness and well-being in different population segments. Therefore, we consider the **design of the methodology used** for interpreting the results of both approaches together, 'Survey' and 'Personal', as the main contribution of the work.

This study contributes to the understanding of human well-being, allowing for a more comprehensive view of how various factors interact to influence individual happiness. By delving deeper, **opportunities for personalized interventions** are opened, which could improve people's quality of life. In fact, upon completion of the study, each participant in the 'Personal' dataset will be able to enjoy the benefits of knowing the activities that most influence their happiness.

The approach taken **addresses the gap between perceptions** (*'Survey'*) **and behaviors** (*'Personal'*), which could become a relevant phenomenon in psychological and sociological research. This work provides a valuable approach to understanding how these discrepancies affect happiness.

## Tools
- Technologies: Python | Excel | Google Forms | Coogle
- Libraries: numpy | pandas | matplotlib | seaborn | graphviz | sklearn | scipy | statsmodels | skmultilearn | xgboost | prince | requests
- Machine Learning Models: K-Means | Decission Tree | Random Forest | Gradient Boosting | Extreme Gradient Boosting | Support Vector Machine | Linear Regression | Ensemble approach
