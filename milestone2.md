# How co-partisan are the left and right communities in Reddit

## Abstract
In [Echo Tunnels: Polarized News Sharing Online Runs Narrow but Deep](https://ojs.aaai.org/index.php/ICWSM/article/view/22177/21956), analysis was conducted to see how polarization happened in reddit. However, later in tha paper, this analysis was used to determine how co-partisan left and right communities were in Reddit. Unfortunately, this analysis had a fatal flaw, in that it did not take into account the fact that Reddit is inherently left leaning in its media consumption. This resulted in conclusions that hilighted 'the skewed media co-partisanship for the right-most community' when the media partisanship of r/Conservatives was not as high as r/democrats. In this analysis I will consider how the left and right communities of reddit compare in their media consumption using different techniques to normalize and standardize the values so that the comparisons are accurate and fair on both sides.

## Research questions
- How do different communities on Reddit lean in their news consumption bias
- How do the most left and right communities compare in their bias towards their media consumption
- How biased is the selected media entities towards the left or right
- Are both communities reasonable in their attitudes towards bi-partisan news

## Additional databases
None

## Methods
This analysis relies heavily on the methods used in [Echo Tunnels: Polarized News Sharing Online Runs Narrow but Deep](https://ojs.aaai.org/index.php/ICWSM/article/view/22177/21956). In terms of machine learning models, I plan to use mainly the community embedding for the partisan values of the subreddit communities. Otherwise, the statistical methods used are:
- Scaling partisanship values to maintain fairness in treatment of both left and right communities
- Calculating weighted means over the partisanship scores of the news sources to determine their social partisanship
Consequently, most of the visualizations will be either chart vs chart comparisons of the different news consumption bias of the left vs the right leaning communities, or singular charts showing detailed averages and extremes of how each partisan side deals with their news consumption. Initially, and explatory analysis was done to see the distribution of Reddit communities and news sources with respect to their biases, and normalize or scale these values to not unfairly treat either side.

## Team organisation
I will be working alone


