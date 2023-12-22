---
layout: page
title: "Hollywood Unveiled"
cover-img: images/women-collage.png
---
The perception and role of women in the US society has greatly evolved during the past century with women being granted a myriad of new rights. Simultaneously, their perception has also evolved, shifting away from mere housewives. Movies are often seen as a reflection of society, moving along with its ebbs and flows. But has this specific social movement bled into the entertainment industry? Has the depiction of women progressed alongside important milestones in the Feminist movement? Or on the contrary, do stereotypes around women still prevail in Hollywood?

This data story will explore the <a href="http://www.cs.cmu.edu/~ark/personas/"><em>CMU Movie Summary Corpus</em></a> to explore how women are portrayed in Hollywood. Not only by mere representation but whether women are now being put at the forefront of storylines. It will also dive deeper into the characteristics of stereotypical movies.

## Over the decades
The proportion of actresses over time gives us a first insight into how well the industry is representing women.  According to expert Dr. Martha Lauzen, “Despite the major disruptions in the film business over the last couple of years, onscreen gender ratios have remained relatively stable.”[^1] But what if we compare to 100 years ago, is the picture still as bleak?

<object>
  <iframe frameborder="no" border="0" marginwidth="0" marginheight="0" width="700" height="550" src="html_plots/proportion_men_women.html"></iframe>
</object>

<div class="left">
  <a href="html_plots/proportion_men_women.html">Figure 1</a>
</div>


<div class="withSidenote" markdown="1">

Figure 1 shows us that the ratio of women in Hollywood has remained fairly constant over time, staying close to 30% until the 2010s. The 40% mark has been broken for the first time during this decade, getting actresses closer pairing. This increasing trend seems to have started in the 70s, and allows us to fit a regression line to the ratios from the 70s to today. If the industry keeps evolving at this rate, we could naively say that parity would be reached in 2064. If 70s really were the start of this increase, can it be explained by any significant event in history ? According to our [timeline](https://www.history.com/topics/womens-history/womens-history-us-timeline), the 60s saw the occurence of two major events for women's rights in the US: the Equal Pay Act and the Civil Rights Act. The Equal Pay Act prohibits a difference of salary based on sex while the Civil Rights Act prohibits (amongst others) employment discrimination based on sex. These two events were a huge step towards gender equality and they might have prompted a change in mentality, resulting in the proportion of women in movies increasing.

<figure class="sidenote">
    <img src="images/Equal_Pay_Act.jpg">
    <figcaption><a href="https://en.wikipedia.org/wiki/Equal_Pay_Act_of_1963"><em>Figure 2.</em></a> Signing of the Equal Pay Act of 1963.</figcaption>
</figure>
</div>

### Breakdown of women's representation in movies

Nevertheless, this result doesn't mean that each movie has 30-40% of women in their cast. This result might be biased by movies that have an extremely low or high proportion of women.

<object>
  <iframe frameborder="no" border="0" marginwidth="0" marginheight="0" width="700" height="550" src="html_plots/movie_proportions.html"></iframe>
</object>

<div class="left">
  <a href="html_plots/movie_proportions.html">Figure 3</a>
</div>

This is in fact what we see with the plot above. In over 40% of movies, actresses make up less than 25% of the cast, meaning that they will spend much of their career outnumbered 3-1 by their male counterparts. Further, 85% of movies have less than 50% of actresses, showing the rarity of female majority casts. So while we may think from Figure 1 that women represent 40% of characters in movies, this plot may be a better representation of what actresses are experiencing during their work. Nonetheless, from 2000 onwards there is a growing number of movies with a majority of women actors in their cast. Lets break this trend down further by looking into some individual genres.

<object>
  <iframe frameborder="no" border="0" marginwidth="0" marginheight="0" width="700" height="550" src="html_plots/movie_proportions_percentages_actress_by_genre.html"></iframe>
</object>

<div class="left">
  <a href="html_plots/movie_proportions_percentages_actress_by_genre.html">Figure 4</a>
</div>

We see that all genres aren’t equal when it comes to the representation of women. On one hand we have Action, Western and Drama for which over 50% of movies have less than 25% of women in their casts. On the other, three genres seem to do slightly better than the average namely Musical, Adventure and Horror.

### Is the age gap even real? 
> Male actors see their careers peak at the age of 46, female actors reach their professional pinnacles at age 30. -  TIME magazine 2015[^2]

<object>
  <iframe frameborder="no" border="0" marginwidth="0" marginheight="0" width="700" height="550" src="html_plots/Average_age_actor.html"></iframe>
</object>

<div class="left">
  <a href="html_plots/Average_age_actor.html">Figure 5</a>
</div>

<div class="withSidenote" markdown="1"> 

On average, female actors are **significantly** younger than men at any point throughout the last century. This clearly emphasises the age gap in the industry. Interestingly, the average age of actors increases over time regardless of gender, potentially reflecting the long career span of actors (we see you Judi Dench, keep slayin). However, even throughout this maturing of the industry, the average age gap does not get any smaller. Have a go playing around with this next animation, showing the complete breakdown of actors' and actresses' ages throughout the decades!

<figure class="sidenote">
  <img src="images/Judi_Dench_1959.jpeg">
  <figcaption><a href="https://en.wikipedia.org/wiki/Judi_Dench"><em>Figure 6.</em></a> Judi Dench in 1959. By Stevan Kragujević. </figcaption>
</figure>
</div>

<object>
  <iframe frameborder="no" border="0" marginwidth="0" marginheight="0" width="700" height="550" src="html_plots/age_distribution_plot.html"></iframe>
</object>

<div class="left">
  <a href="html_plots/age_distribution_plot.html">Figure 7</a>
</div>

Now all of this does not tell us in any way **how** women are portrayed in these movies. We've seen that women's representation is increasing but what kind of representation ? 

## We want major roles!
Having a women lead is much more meaningful than adding only female secondary characters. It is therefore crucial to be able to differentiate the two. 

<object>
  <iframe frameborder="no" border="0" marginwidth="0" marginheight="0" width="700" height="550" src="html_plots/main_char_ratio.html"></iframe>
</object>

<div class="left">
  <a href="html_plots/main_char_ratio.html">Figure 8</a>
</div>

It is interesting to point out the initial decrease that occurred from the 1910s until the 40s.  The lack of data in the earliest decades could bias the original two decades (10s and 20s), only including a few movies where women portrayed main roles. The confidence interval is indeed the largest sound these decades. Furthermore, it could be tempting to say that we start to see an increase starting in the 40s. However this cannot be conclusively said due to the large confidence intervals up until the 1990s.  There has been an Increase in recent decades, but we cannot be sure exactly when this trend started. Nonetheless this is a further insight indicating that women are being offered an increasing amount of leading roles. What events may have prompted this around the 80s?

<div class="withSidenote" markdown="1"> 

- 1981 :  Sandra Day O’Connor is sworn in by President Ronald Reagan as the first woman to serve in the U.S. Supreme Court. She retired in 2006, after serving for 24 years.
- 1983 :  Flying on the Space Shuttle Challenger, Sally Ride becomes the first American woman in space.
- 1984 :  Democratic presidential nominee Walter Mondale names U.S. Rep. Geraldine Ferraro (N.Y.) as his running mate, making her the first woman vice president nominee by a major party.
<figure class="sidenote">
<img src="images/Sandra_day_oconnor.jpeg">
<figcaption><a href="https://en.wikipedia.org/wiki/Sandra_Day_O%27Connor"><em>Figure 9.</em></a> Sandra Day O'Connor being sworn in by Chief Justice Warren Burger. From the US National Archive. </figcaption>
</figure>
</div>

We thus see women accessing political positions that were so far only occupied by men. Moreover, this decade saw the first American into space. Seeing women accessing jobs that previously seemed out of reach may have impacted society. Therefore, as Hollywood picked up on these cues and wanting to reflect the advancement of mentalities, it portrayed more women in main character roles. In 2022, our analysis suggests that 41.1% of main characters are women, with a 95% confidence interval going up to 42.9% According to the San Diego State University Center for the Study of Women in Television and Film, females comprised 43.8% of major characters in 2022. [^3] We are not far off! 

When breaking this down futher by genre we see that our top 3 genres, Musical, Adventure and Horror, reach similar or even higher ratios than overall. Unsuprisingly, Drama, Western and Action are lagging behind.
<object>
  <iframe frameborder="no" border="0" marginwidth="0" marginheight="0" width="700" height="550" src="html_plots/proportion_main_characters_per_genre.html"></iframe>
</object>

<div class="left">
  <a href="html_plots/proportion_main_characters_per_genre.html">Figure 10</a>
</div>

***If you’ve made it so far, that’s great! What have we learned?***

&#x2713; The overall proportion of women has increased in the last 50 years to reach ~40% of actresses

&#x2713; That does **not** mean that all movies have 40% of women! Some genres have more women than others like Musical or Adventure movies, whereas Westerns or Drama are trailing behind 

&#x2713; The age gap in Hollywood is still a thing and does not seem to be closing down, though the mean age of both men and women in the industry is increasing 

&#x2713; The kind of representation matters, and we do see an increase in women main character roles

## Can we classify all these movies?

<div class="withSidenote" markdown="1">
What do you think of when you think of a stereotypical portrayal of a woman ? Does a young pretty actress not contributing to the plot pop into your mind? Being able to classify a movie into stereotypical or non-stereotypical is very valuable in this case. By clustering movies based on the proportion of women, the proportion of women main characters and the difference in the mean ages of men and women in the cast, we were able to cluster all movies into 3 categories. A cluster of stereotypical movies (turquoise), a cluster of non-stereotypical movies (purple), and finally a cluster that falls somewhere in between, not extreme enough to go into either category (yellow).  

<figure class="sidenote">
    <img src="images/cluster.png">
    <figcaption>Figure 11. Clustering of Stereotypical and non stereotypical movies.</figcaption>
</figure>
</div>

Purple Cluster has a higher proportion of women in the cast, also as main character and a smaller difference of mean ages than the other clusters. Turquoise Cluster is the most stereotypical, with no women as main characters, a low proportion of actresses, and the highest mean age difference. 


| cluster index | proportion of women | proportion of women main characters | difference in mean ages |
|---------------|---------------------|-------------------------------------|-------------------------|
| 0             | 0.531               | 0.978                               | -6.755                  |
| 1             | 0.321               | 0                                   | -8.079                  |
| 2             | 0.398               | 0.461                               | -7.197                  |

<div class="left">
  Table 1
</div>

What has been the evolution of the release of these 2 types of movies you may ask! 

<object>
  <iframe frameborder="no" border="0" marginwidth="0" marginheight="0" width="700" height="550" src="html_plots/fraction_stereo_movies_per_decades.html"></iframe>
</object>

<div class="left">
  <a href="html_plots/fraction_stereo_movies_per_decades.html">Figure 12</a>
</div>

From 1920 up to 2020, there seem to always have been a bigger percentage of movies produced that had a stereotypical depiction of women. In the 70s the proportion of stereotypical movies was almost 50% and is the highest in the years analysed. Of course, due to the large confidence intervals that result should be taken with some precaution. Interestingly, the proportion of non-stereotypical movies was relatively stable throughout the decades until 2000. From 2000 to 2020 we see a strong increase of the proportion of movies with a non-stereotypical depiction of women to reach approximately the same percentage as stereotypical movies. (YAY!) Going back to our beloved timeline, multiple events where women ascended to a position of power could have prompted this increase, such as the first female attorney, the first female secretary of state or the first female speaker of the house.

Now that we have a way of categorising these movies and we’ve seen the release trends, what genres are overrepresented into our two clusters of interest ? Reminder that previously we saw that 
- Musical
- Adventure
- Horror
  
genres tended to do better in terms of women proportion in their cast. Whereas 
- Action 
- Western
- Drama
  
tend to do worse. Now how does that compare to this clustering ? When  looking at the difference of ratio between the not stereotypical and the stereotypical movies, we obtain the next plot. If the difference is negative it means that there is a higher proportion of this movie genre in the stereotypical movies. Inversely, if the difference is positive, it means that there is a higher proportion of this movie genre in the non-stereotypical movies. We thresholded the graph to only see movies that had a difference bigger than 0.01. We assumed that a smaller difference was too small to assume a real difference between the clusters.

<object>
  <iframe frameborder="no" border="0" marginwidth="0" marginheight="0" width="700" height="550" src="html_plots/clustering_genre_barplot.html"></iframe>
</object>

<div class="left">
  <a href="html_plots/clustering_genre_barplot.html">Figure 13</a>
</div>

Action and Western still fall into the category of stereotypical as expected by the previous analysis.  Similarly, but on the other side of the spectrum, Horror and Musical are in the  non-stereotypical cluster. Surprisingly, Drama and Adventure are not on the side we would expect. Indeed, we previously saw that Drama had low women representation, but is actually overrepresented into the non-stereotypical cluster, and Adventure has a similar trend but in the opposite direction. 

There are of course limitations with this analysis. Most prevalently, we see that romantic comedies appear in movies that have a non-stereotypical representation of women. It is however well-known that in general in romantic comedies women are solely love interests and are thus portrayed stereotypically. This highlights the need to not only look at the proportion of actresses, the proportion of women character and the age difference but consider other factors. More precisely **the vocabulary linked** to female and male actors in general. This is a perfect segue into our final analysis: *The Vocabulary Analysis*

## Hey kids, spelling is fun! - Let's look at words

As we’ve seen so far, it is not only important to have more women on screen, or even women be leads. It is also crucial to understand what kind of leads they’re portraying. This is why we have analysed the word, more specifically verbs adjectives and nouns, associated with each gender throughout the decades. This captures how women are depicted beyond being present and tagged as a main characters. JE SUIS CONFIANT

<label for="plotSelector1">Select a Plot:</label>
<select id="plotSelector1" onchange="loadPlot()">
    <option value="html_plots/interactive_plot_frequencies_Verbs.html">Verbs</option>
    <option value="html_plots/interactive_plot_frequencies_Adjectives.html">Adjectives</option>
    <option value="html_plots/interactive_plot_frequencies_Nouns.html">Nouns</option>
</select>

<style>
    #plotSelector1 option:checked {
        display: none;
    }
</style>

<iframe id="plotFrame1" width="100%" height="400px" frameborder="0" src=""></iframe>

<script src="https://code.jquery.com/jquery-3.6.4.min.js"></script>
<script>
    $(document).ready(function() {
        $("#plotSelector1").val("html_plots/interactive_plot_frequencies_Verbs.html");
        loadPlot();
    });

    function loadPlot1() {
        var selectedPlot = $("#plotSelector1").val();
        $("#plotFrame1").attr("src", selectedPlot);
    }
</script>

<div class="left">
  Figure 14
</div>

With this visualisation we can observe the top 5 associated verbs, nouns and adjectives for men and women respectively in all genres combined. We first  notice that these ratios seem to be quite constant through time. More striking is the contrast of words associated with men versus  women.  Men are highly linked to action related words such as kill, save or soldier. On the other hand  women are mostly associated with everyday life type of words such as love, marry or family or appearance like beautiful or pretty. So have we really moved away  from the housewise representation ? It seems that women are still very  much associated with 
While this analysis captures the most commonly associated words, it’s important to note that it may  miss changes in less common words, highlighting one of its caveats. 

But one last time, let’s  break it down by genres. 

<label for="plotSelector2">Select a Plot:</label>
<select id="plotSelector2" onchange="loadPlot()">
    <option value="html_plots/rel_freq_interactive_Action.html">Action</option>
    <option value="html_plots/rel_freq_interactive_Adventure.html">Adventure</option>
    <option value="html_plots/rel_freq_interactive_Drama.html">Drama</option>
    <option value="html_plots/rel_freq_interactive_Horror.html">Horror</option>
    <option value="html_plots/rel_freq_interactive_Musical.html">Musical</option>
    <option value="html_plots/rel_freq_interactive_Western.html">Western</option>
</select>

<style>
    #plotSelector2 option:checked {
        display: none;
    }
</style>

<iframe id="plotFrame2" width="100%" height="400px" frameborder="0" src=""></iframe>

<script src="https://code.jquery.com/jquery-3.6.4.min.js"></script>
<script>
    $(document).ready(function() {
        $("#plotSelector2").val("html_plots/rel_freq_interactive_Action.html");
        loadPlot();
    });

    function loadPlot2() {
        var selectedPlot = $("#plotSelector2").val();
        $("#plotFrame2").attr("src", selectedPlot);
    }
</script>

<div class="left">
  Figure 15
</div>

Each genre is in fact recognizable for example action movies with words such as _kill_ _death_ or _battle_,  or  Westerns with _sheriff_, _ranch_ and _money_, and Horror with _alien_ ,_supernatural_ or _attack_. However, women both in stereotypical and non-stereotypical movies are associated with _mother_, _young_, _love_ and  _beautiful_, and this all regadless of the genre, up until the most recent decades. Thus, women are  mostly described based on their physical appearance and their relationship to others instead of having their own personality and being someone even in absence of others. As opposed to men who have a wider variety of words in every genre and mainly action words like  _kill_ and  _party_.  Nevertheless, we focused on the representation of  women here, but when looking at the words associated with men, even in what should be non-stereotypical movies, they're still not words like _father_ or _caring_, but rather still the stereotypical words. It therefore seems that when looking at the overarching trend, there has been no real improvement in ***how*** women are portrayed in the movie industry. Should you lose all hope? Most definitely not! 

## Conclusion
It’s been a wild ride, thank you for tagging along with us! It’s time for a rewind.

<span class="pink-star">&#9733;</span> The representation of women is increasing, but all genres  are not made equal.

<span class="pink-star">&#9733;</span> The industry is ageing but the age gap shows no signs of shrinking. 

<span class="pink-star">&#9733;</span> Women want to be multifaceted and no longer want to be  mere loving, pregnant housewives. And while we have observed an increase in women main characters  the vocabulary analysis has shown little improvement of the words associated with women characters. 

<span class="pink-star">&#9733;</span> So should we be hopeless, not at all!  We want to leave you with a positive outlook of the future  of  Hollywood. Indeed this 2023  year has been promising for the future of women in the industry. Female  led movies can be massive successes when they’re  actually made by the studios. The perfect  example of this is the Barbie wave that hit us this summer. Directed by Greta Gerwig and with Margot Robie as the lead, it has been the highest grossing movie in Warner Brothers’ 100-year history with box office sales exceeding $567 million. [^4] . Change is incremental and  starts  with  a  spark and  this  seems  bright enough for people to start looking. 

# References 
[^1]: [The Hollywood Reporter, *Study Finds Women Represent a Third of Onscreen Population in Film*, 2022](https://www.hollywoodreporter.com/movies/movie-news/women-onscreen-representation-film-study-1235111493/)
[^2]: [TIMES magazine, *This Chart Shows Hollywood’s Glaring Gender Gap*, 2015](https://time.com/4062700/hollywood-gender-gap/)
[^3]: [San Diego State University center for STudy of Women in Television and Film, *Streaming Women: Representation and Employment in Original U.S. Films Released by Streaming Services in 2022*, 2023](https://womenintvfilm.sdsu.edu/research/#:~:text=Females%20comprised%2044%25%20(43.8%25),producers%2C%20editors%2C%20and%20cinematographers.)
[^4]: [Forbes, *Did The Summer of Barbie Save The Movies?*](https://www.forbes.com/sites/georgeschultze/2023/08/24/did-the-summer-of-barbie-save-the-movies/)
