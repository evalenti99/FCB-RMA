# project-plotting-fcb-rma
3-hour project where a comparison is made between FC Barcelona and Real Madrid over the period 2011-2019. The main output is a graph that should check all Al Cairo's indicators. This is my final assignment for the online course "Applied Plotting, Charting & Data Representation in Python".

# Question: 
Is there a relationship between the ratio of ‘goals in favour/goals against’ and winning LaLiga games? Close look at the two best clubs in Spain: FC Barcelona and Real Madrid.

# Datasets links: 
Real Madrid dataset: https://es.wikipedia.org/wiki/Anexo:Estad%C3%ADsticas_del_Real_Madrid_Club_de_F%C3%BAtbol
FC Barcelona dataset:
https://es.wikipedia.org/wiki/Anexo:Estad%C3%ADsticas_del_F%C3%BAtbol_Club_Barcelona

# Discussion
This chart was made trying to answer the question of an existing -or not- relationship between  the ratio of ‘goals in favour/goals against’ and winning LaLiga games. Two Wikipedia pages were scraped for data considering wins, losses, ties, goals in favour and goals against. 10 years of data were selected, leaving the current 2021 season. That is because not all teams had played the same games on this day.

The plot has two indicators, but in the end ‘Win ratio’ is the most important one -it is what wins LaLiga championship-. We can see that FC Barcelona has an overall better win and G+/G- ratio. But concretely, in terms of winning, FC Barcelona’s best year was 2012 with 84%, the exact same percentage as Real Madrid back in 2011. Although, the best indicator for me is the following: FCB has only one time beated G+/G- score, which is in 2012. Meanwhile, Real Madrid has beaten it on: 2011, 2014, 2016. We see that Real Madrid apparently does not need that much big ratio of G+/G- to win games, while FC Barcelona does.

# Al Cairo’s indicators
- Truthfulness: Data is represented just like it was, with no modifications. The two plots share the y-axis in order to equally compare them.
- Beauty: Removed the frame, and selected carefully the best colors for the lines, which are the ones that represent the teams.
- Functionality: reduced the y-axis scale; instead of [0,1], I went from [0.5,1], so it is more clear. I put them one next to the other -and not one above the other- because the y-axis is what interests us.
- Insightfullness: There is a clear evidence of when does the line of 'Win ratio' get ahead of 'G+/G- ratio'. The colors are not similar at all, so one can see it in a moment.

