# Advertisement-Usecase

-- With increase in online streaming of videos (example: Youtube, Tik-Tok, Facebook, etc), the ability to optimize advertisement placement is getting easier and easier. Not only Industries have lot of information on their customers (like their likes, dislikes, engagements, and internet browsing interest), with advent of computer vision, they can also optimize advertisement placement based on content of the show being watched.

-- For example: A television channel company/organisation makes money from advertisement. An interesting area for ML use-case would be to look for moments of their programming that might be of commercial interest. For example, if the program the viewer is watching contains scenes of someone drinking a hot beverage, that might be a particularly good opportunity to show an ad for coffee. Whiskey contextual image appears in Homeland at 8 mins 46 seconds, thus the next ad-break at 11 minutes show a whiskey ad by Haig Club (Hypothetical Scenario)

In the world of customization, and customer engagement, any added benefit to improve sales by 0.1% could have huge impact on organisation's profit.

#### Data:
Provided is a dataset (in //Data folder) where we applied a 3rd party object recognition model (AWS) to images, extracted from some of TV shows at 1-second intervals. Essentially, we took a screenshot every second and fed it to AWS Recognition, which outputs continuous “confidence scores” between 0-1 for over a thousand pre-defined object and scene types. What we want to do with this data is to identify moments in the video that correspond to categories that may be of particular interest for advertising, like Food, Hot Drinks, Phones, etc. These are binary Output Labels for the model being built. In this test dataset, these output labels are given as ground truth labels for every observation, but in real life their job is to infer them. So, to summarize: the goal of this test is to build a product that identifies when the Output Labels are present, e.g. a moment in time where hot drinks were present on the screen, based on the Recognition confidence scores.


#### Models:
In this project we will explore few models as below:
  1. Simple Majority Class Predictor
  2. Business Understanding, and use that to build a crude model
  3. Logistic Regression
  4. Random Forest Model
  5. Gradient Boosting Classifier
