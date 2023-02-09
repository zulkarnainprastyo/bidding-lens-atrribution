# Bidding-Lens-Atrribution

## Core attribution

## Final Project Intro ML
The majority of display advertising inventory is sold in real-time auctions. These auctions are typically attended by bidders (such as Google, Criteo, RTB House, and Trade Desk) acting on behalf of advertisers. They typically train advanced machine learning algorithms on historical data to estimate the value of each display opportunity. The inputs in the labeled training set are feature vectors representing each display opportunity, and the labels are the generated rewards. In practice, the advertiser provides the rewards, which are tied to whether or not a specific user converts. As a result, rewards are aggregated at the user level and are never seen at the display level. To the best of our knowledge, a fundamental task that has been overlooked is accounting for this mismatch and splitting, or attributing, the rewards at the appropriate granularity level before training a learning algorithm. This is known as the label attribution problem.

In this paper, I propose a theoretically justified and practically applicable approach to the label attribution problem. Because it satisfies several desirable properties, including distributional robustness, I call our solution the robust label attribution. Furthermore, I create a fixed point algorithm that enables large-scale implementation and demonstrate our solution using a large scale publicly available dataset from Criteo, a large Demand Side Platform.

## Outline

## Background Project

## Work Instructions
#### Step #1 Select a topic & category
#### Step #2 Select the object and look for reference/related wokrs
#### Step #3 Select dataset
#### Step #4 Start the experiment and model


## Outcome Project
#### Code
#### Easy report 
#### Presentasi

### Software And Tools Requirements

1. [Github Account](https://github.com)
3. [VSCodeIDE](https://code.visualstudio.com/)
4. [GitCLI](https://git-scm.com/book/en/v2/Getting-Started-The-Command-Line)

Create a new environment

```
conda create -p venv python==3.7 -y
```

