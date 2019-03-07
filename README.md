# Kickstart Dataset Analysis and Visualization

## What questions did we ask about our data?
1. What are the characteristics of the campaigns that succeeded? Failed? Were cancelled?
2. Does category or main category have anything to do with the state of a campaign?
3. Maybe currency has something to do with success, cancellation, failure or any other state? Perhaps British campaigns are more/less successful that American or Australian, etc.
4. Does the monetary goal have anything to with final state?
5. How does the number of backers affect the overall amount raised and the state of the campaign?

## Notes about the dataset

- Most of the column names are self-explanatory when looking at them in the context of the dataframe:
  - ID, name, category, main_category, currency, deadline, goal, launched, pledged, state, backers, country
- Except for the following (from [Kaggle](From https://www.kaggle.com/kemical/kickstarter-projects) ):
  - **usd_pledged:** conversion to US dollars of the pledged column (conversion done by kickstarter).
  - **usd pledged real:** conversion to US dollars of the pledged column (conversion from Fixer.io API).
  - **usd goal real:** conversion to US dollars of the goal column (conversion from Fixer.io API).
- We can keep this in mind for context when looking at analyses and visualizations.

## Conclusions drawn:

- Since the vast majority of campaigns fail in the end, the difference between goals set and amounts actually raised is drastic.
- It seems that campaigns that ask for lower pledges succeed at a higher rate and those which ask for higher pledges fail at a higher rate.
- Translated currency amounts show that the Swiss set the highest goals. It also seems that they receive the most pledges in the end.

## Additional Questions to Ask in the Future:

- Is there a better currency for having success in a kickstarter campaign?
- If I'm from Australia, should I conduct my campaign in USD for more success or stick to my local currency? Will there even be a difference?
