# nfl_play_prediction
Project for General Assembly data science class. Using machine learning algorithims to predict NFL plays.

### What is the question you hope to answer?
How accurately can machine learning predict what offensive play an NFL offense will run, given the down, distance, score, time remaining and other factors? Can we predict whether an offense will pass or run the ball? Beyond that, can we predict what side of the field the play will go to? Can we predict if the team will choose to punt, try for a field goal or go for it on 4th down?

### What data are you planning to use to answer that question?
I will use NFL play-by-play data found here http://www.nflsavant.com/about.php.

### What do you know about the data so far?
Play-by-play data is available for 2013, 2014, 2015 and 2016. Each of these datasets is around 46,000 rows long and has 44 columns, or features. The "result" columns I'm looking, i.e. the outcome of each play, are present, such as `PlayType`, `IsRush`, `IsPass`, `IsIncomplete`, `IsTouchdown`, `PassType`, `IsSack`.

### Why did you choose this topic?
I enjoy watching the NFL for the tactical decisionmaking involved. The NFL is kind of a turn-based strategy game, where both offenses and defenses must anticipate what the other side will do on any given play. As a spectator, this anticipation is part of the fun as well. I'm very curious to see how well a machine learning algorithm can guess what an offense will do, and if it can predict better than I can as a spectator. Ultimately, it would be amazing to tap into a live play-by-play datasource and create a twitterbot which live predicts plays before they happen.
