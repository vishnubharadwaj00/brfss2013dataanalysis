**Exploring the BRFSS 2013 using Statistical Analysis**

*The Data:*

According to the BRFSS website and the codebook provided about the dataset, the dataset is used for surveillance purposes of the entire non-institutionalized US adult population.

The aim is to collect information on a wide rnage of factors, such as preventive health practices and risk behaviors that are linked to diseases or injuries. In this dataset, the factors range from exercise and sleep patterns to HIV/AIDS knowledge and healthcare access.

The wesbite further illustrates the two methods of data collection: landline-telephone based surveys and cellular-telephone based surveys. In the landline-telephone based surveys, the interviewers collect data from a randomly sampled adult in a household. In the cellular-telephone based surveys, the interviewers collect data from an adult who uses his cellular telephone and resides in a private residence or college premises.

This explanation of the data collection makes it clear that random sampling was used, to select randomly an adult in the household, making it possible to generalize to the adult population of that household to a large extent. A form of stratified sampling could have been used, or multistage sampling. That is not sure. The households must also have been randomly sampled, although such information is not explicitly provided in the website or codebook. Information on how the households were sampled, and the factors on which they were sampled, such as demographic or locality, should be further specified.

The results can be generalized to the entire US population, because of the random sampling that haas been carried out.

Random assignment is not done, so we cannot ensure that causality is the case for all the results.

Further information about each of the 330 variables is given in the codebook, which shall be used later. 

*The Research Questions:*

Looking at the codebook and its explanation of each of the variables, many interesting questions can be raised, thanks to the vast amount of data at our hands.

These are only some of the possible questions that could have been asked. I have chosen a few questions that might seem a bit different, but might prove to be interesting, maybe even useful.

**Research question 1**: Which state uses the seatbelts least in their cars and which state uses them the most? (Is there a correlation between states and seatbelt usage?)

Seatbelts do save lives and whether this behavior reduces or does not affect the number of car accident deaths can be easily found by further comparing these results with the accident statistics, perhaps from another dataset. Again, causation and correlation cannot be seperated, because it is also possible that because of the low number of car accidents, people do not wear seatbelts.

**Research question 2**: Is there any correlation between exercise and heart attacks/heart diseases?

Exercise is said to be healthy for the body and the brain, but here, we have a chance to see an actual outcome of doing exercise, in relation to the heart. This may help drive home the point that exercise is an inherently pivotal part of everyday life.

**Research question 3**: How does amount of sleep change with age? (Is there a correlation between sleep time and age?)

Sleep is again a very important part of well-being. 6-8 hours of sleep is recommended usually, but with a lot of responsibilities, this tends to change. With a difference in age, comes a difference in responsibilities and routines. Does this affect sleep patterns?

Note: All programming is done in R, and code as well as interpretations of the data can be found in the Rmd file.
