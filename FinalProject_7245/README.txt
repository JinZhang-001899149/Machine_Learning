# CSYE 7245 Final Project-PUBG Finish Placement Prediction ##
 
## ABSTRACT

JinZhang  NUID:001899149

This project is licensed under MIT which is available on the GitHub site :
https://github.com/JinZhang-001899149/Machine_Learning/blob/master/LICENSE


To run the Notebook, you will need to dowland the data first.

### Dataset
***PUBG Finish Placement Prediction***
https://www.kaggle.com/c/pubg-finish-placement-prediction/data

### Introduction of the dataset
**Context**
- You are given over 65,000 games' worth of anonymized player data, split into training and testing sets, and asked to predict final placement from final in-game stats and initial player ratings.

- What's the best strategy to win in PUBG? Should you sit in one spot and hide your way into victory, or do you need to be the top shot? Let's let the data do the talking!

**Challenge**
- In a PUBG game, up to 100 players start in each match (matchId). Players can be on teams (groupId) which get ranked at the end of the game (winPlacePerc) based on how many other teams are still alive when they are eliminated. In game, players can pick up different munitions, revive downed-but-not-out (knocked) teammates, drive vehicles, swim, run, shoot, and experience all of the consequences -- such as falling too far or running themselves over and eliminating themselves.

- You are provided with a large number of anonymized PUBG game stats, formatted so that each row contains one player's post-game stats. The data comes from matches of all types: solos, duos, squads, and custom; there is no guarantee of there being 100 players per match, nor at most 4 player per group.

- You must create a model which predicts players' finishing placement based on their final stats, on a scale from 1 (first place) to 0 (last place).


### Why I choose this Project?
- This game was launched in December 2017 and It becomes quite popular after several months.  And I have been playing this game for a while. So When I see this dataset, It got my attention immediately. So I would like to go deeper and explore this dataset and see how the masterpiece players dominate this game.

- Also, after the popularity of this game. now it is dying. maybe through this project, might give me some idea why this phenomenon is happeneing. 

### Achievement and conclusion.
- A good prediction with my Stacked Ensemble Super-Model
- Which strategy helps the player win the game. 
- Which fact cause this game to lose so many players in a very short term.
