# Content_Analysis_YT_2020_Debates

The purpose of this project was to gauge sentiment among viewers of the 2020 U.S. Presidential Debates. This analysis uses YouTube comment data from the first (and perhaps most memorable) debate of that election cycle. Videos were selected based on three major criteria. Firstly, the number of views the video. I wanted videos with the highest views. Secondly, I wanted the video to contain the full debate from start to finish; so the videos were not “highlights” of the debate, featuring various clips. Those clips show specific moments of a candidate in a particularly positive or negative light, and so (perhaps inadvertently), this could slant the types of comments that I could get. And so in that way, I avoid such inherent bias. Lastly, the video must be published by a "mainstream" news source. Much like the previous example, pulling comments made under a stream by a left-leaning channel or a right-leaning channel could introduce bias into the sample. 

With these criteria in place, the debate videos came from the following YouTube channels: C-SPAN, CBS News, CNN, Fox News, NBC News, and the Wall Street Journal. 
Table 1 shows a breakdown of the metadata for each YouTube video including the number of views, likes, dislikes, and the number of comments each video received. Notably, across these six channels, there were 36,489,491 viewers and 183,471 comments. Given the substantial amount of text (comments) to work within this first debate, we felt it is appropriate to place our focus here, rather than all the debates.

![](https://github.com/JohnM-Eaton/Content_Analysis_YT_2020_Debates/blob/main/Table%201.png)

Figure 1 shows the results of the first sentiment analysis using the Bing lexicon. Recall, CSPAN had over 80,000 comments, while CBS news had about 6,000. This explains the substantial difference in the number of words. The main point here, in any event, is two-fold. One is that across the channels, there’s the same pattern. Which is that there are more positive words than negative words. Given the overall negative consensus towards both candidate performances in the aftermath of the debates, this is quite surprising.
![](https://github.com/JohnM-Eaton/Content_Analysis_YT_2020_Debates/blob/main/Figure%201-%20Bing.svg)

Performing another sentiment analysis with the nrc lexicon (Figure 2), I see the same pattern: There’s more positive words than negative words, and more “positive” emotions than negative emotions. Futhermore, when expanding this analysis to compare comment sentiment across channels (Figure 3), I do not see significant variation.
![](https://github.com/JohnM-Eaton/Content_Analysis_YT_2020_Debates/blob/main/Figure%201-%20Bing.svg)
![](https://github.com/JohnM-Eaton/Content_Analysis_YT_2020_Debates/blob/main/Figure%201-%20Bing.svg)
