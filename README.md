# League Analysis

The goal of this project was to create an analysis tool that would be able to predict who is going to win a League of Legends match. I used a Kaggle dataset to get ~25000 game IDs and then used the Riot Developer API in order to pull the full information from each game. After doing a little bit of data cleaning, I trained a random forest model on the data, with good results. The accuracy ended up being about 98%, which seems quite possible because I used the end of game statistics. I also anaylzed what the best predictors of a win are, which ended up being the towers you take down. For more discussion of these results, look at "Erik Final Project.pdf".

Thanks,
Erik Van Cruyningen
