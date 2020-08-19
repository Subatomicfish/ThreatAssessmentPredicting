# ThreatAssessmentPredicting
Predicting values for Threat Assessment fields in Fatal Encounters database to semi-automate the task of researching and filling in these columns for about 17 years of data.

Fatal Encounters is currently trying to fill in new fields relating to Threat Assessment on historical and future records. 
These columns are: Armed or Unarmed, Alleged weapon,Physical movement, Fleeing/Not fleeing.
The goal is to at least partially automate the task of identifying these details and filling in these fields, 
to try to shift the human work to that of reviewing, skepticizing, and investigating non-obvious cases.

The first goal will be to be able to automatically retrieve the actual text from articles referenced so text analysis and Natural Language Processing (NLP) can be done on it to help identify important keywords/search terms.
Next, I will probably implement and test the simplest model that I predict could actually be effective: use the existence of the term "unarmed" in the text to predict the "Unarmed" in the "Armed or Unarmed" field. This will be tested against records that have already been filled in and reviewed. 
