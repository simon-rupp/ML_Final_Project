Simon Rupp, YongJae Lee, Aryavrat Gupta
a) The Problem You Are Solving
Our project aims to predict symptoms of depression using all available features in the
NHANES dataset (physical activity, diet, sleep patterns, and demographics, etc.). Beyond
prediction, we seek to determine which factors have a causal impact on depression symptoms,
distinguishing causation from correlation.
b) Why It’s Important
Depression is a major health concern, and understanding both predictors and causal factors
is important for prevention/treatment. By identifying features that have a causal impact on
depression, this study can suggest/support treatments designed to mitigate depression risk.
c) The Data You Will Use
We will use data from the National Health and Nutrition Examination Survey (NHANES),
which provides fairly comprehensive health data. We can access many different health,
lifestyle, and demographic related features that may play a role in prediction of depression.
Of course, the depression variable is also accessible through the PHQ-9 assessment.
NHANES data is publicly accessible, so all group members have access to this data. Preprocessing steps will address missing values and to ensure we understand all features available
to us to use.
d) The Method/Model You Will Use
We want to focus our project on causal inference. We are aiming not only to predict depression but also to identify which features are causally linked to it, as opposed to merely
correlated.
There are several ways we could evaluate prediction which are still to be determined. We
could try to simply predict a patient’s PHQ-9 score (ranging from 0-27), split up the scores
into several categories of depression to predict into those categories, or even into a binary
classification of depression vs no depression.
To achieve this, we will use a causal forest. This model will allow us to create a predictive model of depression while providing insights into which variables have a significant
causal impact on depression compared to others. Casual forests are an extension of random
forests.
