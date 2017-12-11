---
layout: post
title: "Subreddits use Coordinators differently"
date: 2017-12-10
---

I was playing with the Reddit API, and specifically the <a href="https://praw.readthedocs.io/en/latest/">Python wrapper (PRAW)</a> which makes it straightforward to grab large numbers of post titles or comments. I don't have any current research questions about it, but I thought I'd do some butterfly collecting with coordinators. So, I'm just curious: do subreddits use coordinators differently?

For each subreddit, I got the titles from a random 1000 "hot" posts in the subreddit's history. "Hot" posts are dynamic and updated constantly. How "hot" a post is a combination of high upvotes, and a lot of current activity. (Other categories of posts are "top" and "new", self-explanatory, and "controversial", which is also a post with current activity, but an even split of up- and down-votes.) I figure "hot" posts mean the subreddit generally agrees with the content or ideology of the sub, and "hot" also means that I'm getting a snapshot of current and fresh content. For those 1000 titles, I just counted the instances of "and" "but" "or" and "and/or". This is what I got.

<center><img src="{{ site.url }}/assets/subreddit-coords-line.png" style="width:600px; height:auto"></center>

Right off the bat you see that for the most part, every sub follows the same pattern of use. "And" is the most common coordinator", followed by "but" and "or", which occur at usually 1/4 the rate of "and". All the titles were in English, though that is not the case across Reddit. Even though these subs have very different content and the nature of their titles varies, this overall pattern persists. There is not much research on corpus frequency of coordinators and whether or not it's tied to any variable. I was only able to find a few works that discuss the sociolinguistics of coordinators, for example Mary Shapiro's 1997 dissertation, which discusses the issue briefly and I think one finding was that increased use of "and" is correlated with increased perception of formality. 

Globally, I was curious if there were any effects of "braininess" or even "assumed gender" on coordinator use. I don't have a normalized ranking of subreddits by "impressions of braininess", but Science and AskHistorians are typically considered very brainy subreddits. They are both outliers in their frequent use of "and". The subreddit Funny is typically not considered very brainy, and it ranks very low in use of "and" and other coordinators. More brainy subreddits are characterized by complex sentences and extended argumentation, which generally requires increased coordinator use. If I were to speculate on why Fifthworldproblems is the highest user of "and", it would be that it uses very odd and idiosyncratic language, and users are attempting to simulate surreality but stringing together sentences (Although it remains to be seen why the seventhworld is inhabited by so few "ands"). By assumed gender, I coarsely chose two subs known for their subscriber population dominated by a particular gender: TwoXChromosomes, which deals with women's issues, is assumed to be populated mostly by women. MensRights, which deals with social justice advocacy for men, is assumed to be populated mostly by men. These didn't show much of a difference in use of coordinators. Another comparison could be made between the subreddits Christianity and Atheism, although it isn't very different: apparently Christians and Atheists do not vary much in their use of coordinators.

Besides those extremely coarse and assumed pseudo-sociolinguistic variables, the more easily definable content type of subreddit seems to have some effect on coordinator use. I've identified three groups: question-oriented, surreal, and headline-oriented. The lines in fine dots are "question-oriented" subreddts: AskReddit and AskHistorians. The titles are either all or for the most part questions. For the question-oriented subreddits, you see an uptick in the use of "or" compared to other subs. The lines in wide dashes are "surreal" subreddits that intentionally use semantically obscure language to create a surreal world: Fifthworldproblems, VXJunkies, and seventhworldproblems. Even though the post titles are nonsense, they still follow the pattern of coordinator use. Fifthworldproblems even surpasses Science in its use of "and". If someone really wanted to create surreal, irregular English, they would cut down the use of "and" in favor of the other coordinators. But this variation is below the level of consciousness for most. Lastly, there are "headline-oriented" subreddits, indicated by a line started with a large dot: these are Science and Politics. The posts of these subs are for the most part simply pithy article or news headlines, which is definitely a separate type of language use from asking questions or playing with language in a surreal way. It doesn't seem like a post title being a headline makes any difference since they seem to be at opposite ends of the spectrum in coordinate use.

The clustered bar graph allows you to compare more easily the relative proportions of coordinators for each subreddit.

<center><img src="{{ site.url }}/assets/subreddit-coords-bars.png" style="width:600px; height:auto"></center>

Some new observations emerge. It is easier to see that most subreddits follow the pattern. In order of frequency are AND > BUT > OR > AND/OR. Green > blue > yellow > Dark green. Except for AskReddit, Science, and AskHistorians (and marginally TwoXChromosomes, and politics). The three clear cases are all fairly brainy subs, the two "Ask-" Reddits are question-oriented, showing an increased preference for disjunction. Setting these three aside: for most of the subreddits, BUT and OR appear about the same number of times. Except for VXJunkies, SeventhworldProblems, and Fifthworldproblems, where it seems like BUT is used way out of proportion, many more times than OR. I suppose this is one aspect where users succeed in using surreal or irregular English, in that they use too many BUTs.

Definitely looking for tips on visualization, but at this point I'm just exploring, so I'll look at everything all at once. 