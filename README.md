# Recidivism Prediction

## Report
Our final R Markdown file is called Recidivism_Master.Rmd. It is accompanied by html output. Original versions of these files, showing a full history of commits are located in the prg folder.

## Summary
In 2016, ProPublica published a story on how a commonly-used pre-trial risk assessment tool called the COMPAS is racially biased. The journalists showed that in spite of a 2009 validation study showing similar accuracy rates for black and white men (67 percent versus 69 percent), the inaccuracies were in opposite directions for the two groups. Our goal was to investigate whether we could use tools learned in Professor Igoche's data mining course to create Risk Assessment Instrument (RAI) that was more accurate and less racist than the COMPAS.

We show in this report that with fewer variables, data mining tools available to the average student, and a limited amount of time, we were able to replicate the accuracy rate of a model already in use by governmental agencies, along with providing adjustments. However, both our model and the COMPAS have different types of errors across demographic groups. Specifically, while both our model and the government model are racist and ageist, ours has the unfortunate distinction of also being sexist. Additionally, we acknowledge that any model based on American crime data, no matter how internally sound, will reflect the biased data from which it is built.

## ProPublica Resources
[ProPublica main article]( https://www.propublica.org/article/machine-bias-risk-assessments-in-criminal-sentencing)  
[ProPublica methodology]( https://www.propublica.org/article/how-we-analyzed-the-compas-recidivism-algorithm)  
[ProPublica github]( https://github.com/propublica/compas-analysis)  
