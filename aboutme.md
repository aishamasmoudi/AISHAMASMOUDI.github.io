---
layout: page
title: Explosive Narratives - Terrorism through the Cinematic Lens
subtitle: Investigating the impact of Terrorism on World Cinema
cover-img: /assets/img/main_img.jpg
thumbnail-img: /assets/img/main_img.jpg
share-img: /assets/img/main_img.jpg
use-site-title: true
---

Throughout history, humans have used violence and intimidation, especially against civilians, in the pursuit of political and ideological aims. This idea defines terrorism, which has had a significant impact on society and culture. It is fair to assume that cinema portrays diverse cultures, lifestyles and issues, reflecting society, its joys, struggles, and complexities. Through films, we witness stories that resonate with our own experiences, making us feel connected and understood, and allowing us to learn more about what is happening in our world. In this context, terrorism has been portrayed in multiple movies. It is interesting to investigate the impact that terrorism has had on cinema, using the CMU Movie corpus dataset and focusing on emotional depiction, genre association, topic patterns, as well as popularity across continents and countries.

## Introduction

Welcome to "Explosive Narratives: Terrorism through the Cinematic Lens" – where we light the fuse on the dynamite topic of terrorism in movies, without any real explosions, of course! Picture this: you're sitting in your comfy chair, popcorn in hand, ready to dive deep into the world of cinema where the only thing more thrilling than a car chase is our data-driven analysis.
So, grab your 3D glasses, because we're about to embark on a cinematic journey that's part data, part drama, and totally explosive – metaphorically speaking, of course! 🍿🎬💥

Let's start by visualizing the counts of terrorism-related movies through time:

![My Image](/assets/img/terrorism_movies_time_series.png)

We can observe a growing trend in the production of terrorism-related movies over the years. This could suggest a growing interest in terrorism movies in cinema, but it could however be related to the smaller number of movies provided by the CMU dataset in the 1907-1940s period. There is a dramatic increase in the early 21st century period, where the bars reach their highest points. This could be reflective of global events and the increased prevalence of terrorism in news media, telling us about the role of terrorism in the public consciousness during these times, which may have influence the film industry.

![My Image](/assets/img/terrorism_movies_countries.png)
**figure out how to insert interactive plots**

As we can see, the US, followed by India, United Kingdom and Japan, are the most important countries when it comes to producing terrorism-related movies. This plot is of course a little biased, since the Hollywood and Bollywood are the most important movie production industries in the world, and they by nature produce more movies than other countries.

{% include_relative assets/img/map_movie_count.html %}

This plot offers a sight into how many terrorism-related movies were produced in each country.

---

## 1. Popularity Analysis - The Box Office Boom

##### Are terrorism-themed movies the box office's best friend or its awkward acquaintance?

---

## 2. Genre Association - The Movie Genre Cocktail

Think of genre as secret agents; they've got all the gear - narrative elements, thematic content, stylistic approach, and the emotional response they aime to evoke in the audience. They help categorize films so that you don't end up in a rom-com when you were ready for a story high in suspense and plot twists about a hero saving thousands of people from the action of terrorists.

And when it comes to terrorism movies, they sneak up on you with action, disguise themselves in drama, and occasionally, they even wear the mask of comedy before the big kaboom! Our mission is to dissect the relationship between genres and terrorism movies.

So buckle up data nerds, as we dive bomb into the world of movie genres. It's going to be a blast! (pun intented) 🎥💣🔍

### 2.1 How often does each genre appear in terrorism vs non-terrorism movies?

For both non-terrorism- and terrorism-related movies, we have gathered the top 10 most common genres. We then plot the counts of both types of movies against the genres. We obtain the figure below.

![My Image](/assets/img/top_10_genres.png)

What are the most prevalent genres of non-terrorism vs terrorism movies? Do they differ?
We see that:

- The top 10 most common genres of terrorism movies are: Drama, Action, Thriller, Comedy, Action/Adventure, Horror, Adventure, World cinema, Crime fiction and Science fiction.
- The top 10 most common genres of non-terrorism movies are: Drama, Comedy, Romance Film, Black-and-white, Short film, Thriller, Action, Indie, World cinema and Crime ficiton.
- We notice that for both sets of movies, the most prevalent genre is Drama. This could suggest that dramatic elements are central to storytelling in films regardless of the terrorism theme.

Now, for a more significant comparison, we will focus on the top 10 most common genres in terrorism movies, and we will look at the proprtion of non-terrorism and terrorism movies for these genres.

![My Image](/assets/img/proportion_genres.png)

1. What genres are more prevalent in terrorism related movies than in non-terrorism related movies?

- Action and Thriller: These genres seem to be more prevalent in terrorism-related movies when compared to non-terrorism-related movies.
- Adventure and Horror: While not as dominant as Drama, Action, or Thriller, these genres also appear more frequently in terrorism-related movies than in non-terrorism-related ones.
- Drama: This genre has a very high proportion in both terrorism and non-terrorism related movies.

2. How do these genre preferences for terrorism movies reflect cultural attitudes towards terrorism? Do they suggest that certain genres are better suited to explore terrorism-related themes?

- Action and Thriller: These genres are traditionally associated with high energy, suspense, and conflict, which are common elements in terrorism narratives. The prevalence of Action and Thriller genres in terrorism-related movies could reflect the intensity and high stakes often associated with terrorism.
- Adventure and Horror: These genres could be more prevalent due to the way they can incorporate elements of the unknown and fear, which can reflect unpredictability and fear associated with acts of terrorism.
- Drama: While Drama is prevalent in both types of movies, its slightly reduced prevalence in terrorism-related movies compared to non-terrorism-related ones might indicate that while dramatic storytelling is universal, terrorism movies might need the inclusion of action or thriller elements to better portray the specific themes associated to terrorism.

3. Do these genre trends in terrorism-related movies reflect a global influence, or are they more indicative of Western cinematic trends?
   We discuss this in **section 2.2**.

4. Evolution Over Time: How have the representations of terrorism in various genres evolved over time? We discuss this in **section 2.3**.

### 2.2 Does the prevalence of certain genres of terrorism-related movies change between world regions? And between countries?

Let's visualize the heatmap of Movie Genres by Region, by Country, and a bar chart for the counts of movies per genre in the USA.

![My Image](/assets/img/heatmaps_genres.png)

The prevalence of genres like Drama and Thriller in many regions might indicate a universal appeal of intense narratives that deal with complex human emotions and ethical dilemmas, which are often at the core of terrorism-related stories. In contrast, regions where certain genres are more popular may reflect regional storytelling traditions or preferences, such as a penchant for Action/Adventure in the Americas, which could be tied to the Hollywood influence and its history of high-stakes blockbusters.

Economic factors, including the availability of funding and resources, market size, and audience demographics, can significantly influence which genres are produced within a region. For instance, regions where Action/Adventure and Thriller genres are highly prevalent may have more established film industries capable of supporting the high production costs associated with these genres. They may also have larger audiences that provide the box office revenues needed to justify such investments.

The representation of certain genres, such as Action/Adventure and Drama, across multiple regions suggests that these genres have broad international appeal, likely influenced by the widespread distribution of Hollywood films. However, the presence of genres like World Cinema, which is more prevalent in Europe, indicates that unique cultural differences and cinematic expressions still persist despite the forces of globalization.

### 2.3 Were some genres of terrorism movies more popular during specific periods?

Here, we plot the evolution of counts of movies through time, for each genre.

![My Image](/assets/img/genre_time_series.png)

By comparing these plots to the "Number of Terrorism-Related Movies per Year" in section **Introduction**, the number of terrorism-related movies for each genre follows the same general trend as for all terrorism-related movies together. Indeed, we see a net increase of movies over time for all genres. We notice that some genres are more prevalent than others (Drama, Thriller, Action/Adventure, Horror and World cinema).
We notice that World cinema has had a peak in the 1990s decade. This could be due to many factors: the global political climate, with the end of the cold war, dissolution of the Soviet Union, the end of apartheid in South Africa, etc, which may have encouraged filmmakers to explore the theme of terrorism through movies; this could also be due to the rise of independent and international cinema in the 1990s (**reference**: https://nofilmschool.com/independent-movies-90s-dominate). The 1990s saw a surge in independent filmmaking, with more films being produced outside the traditional Hollywood system.
Thriller, Action and Horror have a similar peak, roughly from 2005 to 2015. Drama knows a very important peak in the late 2010s.

To conclude, the representation of terrorism in various genres have the same overall evolution over time, with an increase in the number of terrorism-movies of all genres. Some genres stand out with specific peaks, notably World cinema in the 1990s.

### Conclusion:

And that's a wrap on our Genre Analysis!

So, what have we learned? When it comes to terrorism movies, Drama is the most prevalent movie genre, in both terrorism- and non-terrorism-relatd movies. It seems that whether our protagonists are diffusing a bomb or a dramatic love triangle, we just can't get enough of those emotional rollercoasters.

But when the smoke clears, it's Action and Thriller that really stand out. These genres are to terrorism movies what a fuse is to dynamite – absolutely essential for a spectacular show.
Adventure and Horror genres are the next most prevalent genres of terrorism movies. They serve up a blend of chills and thrills, often leaving us with the kind of cliffhangers that make you wish you had a parachute.

Globally speaking, it looks like genres representing terrorism movies are not very diverse between world regions and conutries. Drama and Thriller seem to be the universal language of 'boom'. However, we do notice some regional preferences for Action/Adventure or World Cinema.

As for the evolution of terror in films throughout time, all genres have the same trend. They are all characterized by an increase in movie counts, and some genres stand out with important peaks, such as World cinema in the 1990s, Horror, Action and Thriller in the 2000-2010s, and Drama in the 2010s.
Whatever the genre, it seems like audiences are always ready for narrative detonation.

Now, grab your popcorn and your protective gear; we're moving on to the next explosive analysis before the timer runs out! 🍿💥🎥

---

## 3. Topic Patterns : Unraveling the Thematic Tapestry of Terrorism in Cinema

##### Last but not least, we delve into the thematic jungle of terrorism movies. Are we spotting patterns, or is it as unpredictable as a plot twist in a Hitchcock film?

### 3.1 The Art of Decoding Themes: A Peek Behind the Curtain

In the world of terrorism-themed movies, each frame, each dialogue carries a universe of themes. To unravel this complex web, we turn to Latent Dirichlet Allocation (LDA), a model that treats topics as a blend of words, and movies as a blend of topics. Our mission? To decode the underlying themes that shape these movies.

### 3.2 Topic Modeling with LDA: The Heart of Our Analysis

Here's where the magic happens. We run LDA to discern the dominant themes in our collection of terrorism-themed movies. Each movie is now a mosaic of topics, each topic a tapestry of words.

#### Global Lens: The Universal Themes

Our first foray is into the general landscape. We examine movies from across the globe to identify overarching themes.

`[Insert Global LDA Topic Model Visualization Here]`

Words like "attack," "police," "man," "kill," and "escape" dominate the scene, painting a picture of action, conflict, and suspense – the quintessential elements of terrorism movies.

#### Country-Specific Narratives: Diverse Stories Unfold

Now, we zoom in on specific countries - the USA, the UK, India, and other key film-producing nations.

`[Insert Country-Specific LDA Topic Model Visualizations Here]`

Each country brings its unique narrative style and cultural nuances to the fore. The themes vary – from the emotional and familial in Indian cinema to the tactical and militaristic in American movies. We explore how each country's history, culture, and political climate influence its cinematic portrayal of terrorism.

### Conclusion: A World of Stories Told Differently

Our journey through the thematic realms of terrorism-themed movies reveals a rich diversity in storytelling. While there's a universal language of action and conflict, each country adds its distinct flavor, embedding its unique historical, cultural, and political narratives into these portrayals. The thematic tapestry we uncover is as diverse and intricate as the world itself.

---

## 4. Emotional Depiction

🎉 Welcome to the Sentimental Rollercoaster: The Explosive Edition! 🧨

Hold on tight as we continue on our data adventure that's more suspenseful than a spy thriller – we're diving into the world of Sentiment Analysis, where emotions run wild and insights detonate like plot twists in a terrorism-themed blockbuster! 💣🍿

Just like a master detective decodes cryptic messages, we're here to unravel the sentiments behind every cinematic explosion and heart-pounding chase scene. Get ready to sift through the data debris and uncover the hidden gems (and maybe a few landmines) in the vast landscape of terrorism-themed movies.

So, strap in, data daredevils! Our Sentimental Rollercoaster: The Explosive Edition is on the launchpad, and we assure you the only thing in jeopardy is your ordinary view of movie emotions. 🎬💥

### 4.1 Do the emotional tones in the cinematic representation of terrorism differ between specific countries/regions ?

To gain an initial perspective, we can generate a map depicting the average sentiment score for each country within our dataset. The sentiment scores were computed utilizing Vader sentiment analysis, a powerful tool that assigns scores ranging from -1 to 1. Vader sentiment analysis specializes in evaluating the polarity of text, offering insights into whether the expressed sentiment is positive, negative, or neutral. Scores closer to -1 indicate a more negative sentiment, scores near 1 suggest a more positive sentiment, and scores around 0 signify a neutral sentiment. This approach provides a nuanced understanding of the emotional tone embedded in the narratives of terrorism-themed movies across different countries.

{% include_relative assets/img/sentiment_score_map.html %}

Here are some key observations :

- **Negative Sentiment Dominance:** The majority of countries exhibit negative average sentiment scores, indicating a prevalent trend toward portraying terrorism-related themes with a more critical emotional tone.
- **Range of Sentiment Scores:** The sentiment scores exhibit a spectrum, spanning from negative values, such as -0.344 (Egypt) and -0.340 (Uruguay), to positive values, like 0.426 (Tunisia) and 0.291 (Lebanon). This wide range indicates diverse emotional representations across different countries. However, it's crucial to note that several of these countries have a lower movie count, potentially influencing the accuracy and representativeness of the results.
- **Consistency Across Regions:** Countries within certain regions, like Europe, share similar negative sentiment trends, as seen in Germany (DEU), France (FRA), and the United Kingdom (GBR).

Upon careful examination of the average sentiment scores map, we have identified several key countries for in-depth analysis. The United States, India, and the United Kingdom stand out due to their significant volume of terrorism-themed movies, providing a robust dataset for exploration.
In addition, we find intriguing variations in sentiment scores in South America and Central America. While some countries, such as Brazil, exhibit neutral sentiments with a low score of -0.08, others, like Chile, lean slightly positive with a score of 0.06. Notably, Uruguay portrays a comparatively low sentiment score of -0.35, whereas Venezuela emerges with a distinctive high score of 0.24.
To ensure meaningful analysis, we will aggregate data for all Latin American countries into a single group, allowing us to glean insights from a more substantial dataset.
By narrowing our focus to these regions, we aim to explore patterns and correlations between the depiction of terrorism in movies and the associated sentiment scores, uncovering nuanced insights that may be obscured when considering the entire dataset.
This refined introduction provides more detail about the chosen focus countries and the rationale behind selecting them. It sets the stage for a more comprehensive analysis of terrorism-themed movies and their sentiments.

To gain a comprehensive understanding of sentiment distribution across all genres for the chosen countries, we initially examined the broader landscape by plotting the percentage of emotional and non-emotional movies for each country before delving into the negative, neutral, and positive categorization.

{% include_relative assets/img/emotion_percentage_plot.html %}

Not surprisingly, the analysis revealed a consistent pattern across all focus countries, with more than 80% of terrorism-themed movies eliciting emotional responses.
Following this preliminary exploration, we proceeded to classify the terrorism-themed movies into three categories: negative, neutral, and positive.

{% include_relative assets/img/sentiment_percentage_plot.html %}

Notably, negative sentiments are prominently represented within terrorism-themed movies, indicating a common trend across the dataset.
An intriguing observation arises when analysing the sentiments of terrorism-themed movies, particularly in the case of India. Unlike other focus countries, India stands out with a noteworthy positive sentiment of approximately 27.59%. This positive sentiment is more than two times higher than that observed in other countries and regions of interest.
The prevalence of negative sentiments aligns with the nature of terrorism-themed movies, often portraying intense and dramatic narratives. However, India's distinctive positive sentiment introduces an interesting dynamic. This unique trend suggests that Indian cinema, even when depicting terrorism, tends to incorporate elements that evoke positive emotions or portray resilience in the face of adversity.
As we delve deeper into our analysis, exploring the thematic elements, plot structures, and character dynamics of terrorism-themed movies, we anticipate uncovering nuanced insights that contribute to a richer understanding of how different countries approach and depict this genre. India's positive sentiment, in particular, warrants further investigation to unravel the factors contributing to this distinctive trend.

To extract more detailed insights, we aim to cluster the emotional arcs of movies, considering both country-specific and genre-specific contexts. It is crucial to note that attempting to cluster movies from diverse genres together may not yield meaningful results due to the inherent variation in storytelling approaches. Consequently, we will focus on drama, action, and thriller genres, given their prevalence in terrorism-themed movies.

To delve into the analysis of this plot type, we will use a terminology established by the American writer Kurt Vonnegut. Vonnegut's framework demonstrates the identification of six primary story plots, commonly known as story arcs. These arcs encompass a diverse array of narrative structures that significantly influence the emotional trajectory of a story. Kurt Vonnegut's work showcases that stories, irrespective of their genres, tend to follow specific patterns, contributing to a richer understanding of storytelling dynamics.
The six main arcs are (where Rise mean a rise in happiness):

- **Rise-Fall-Rise:** “Cinderella”
- **Fall-Rise-Fall:** “Oedipus”
- **Fall-Rise:** “Man in a Hole”
- **Steady Fall:** “Riches to Rags” or “Tragedy”
- **Steady Rise:** “Rags to Riches”
- **Rise-Fall:** “Icarus”

![My Image](/assets/img/drama_cluster_page-0001.jpg)

Examining the clusters within the drama genre reveals intriguing patterns. The first cluster, observed for the United Kingdom (GBR), the United States (USA), and India (IND), appears to follow the same narrative curve but on different scales, emphasising the universality of certain emotional arcs across these countries.
Furthermore, GBR and USA exhibit similar clusters for the second and third clusters, resembling the "Man in the Hole" (cluster 2) and "Cinderella" (cluster 3) arcs. This consistency across countries suggests shared storytelling structures. Notably, the third cluster for India introduces a compelling dynamic, starting with a very low sentiment (-0.4), descending even lower before rising and oscillating at the end. This nuanced emotional trajectory prompts further exploration to uncover potential thematic correlations.
In contrast, the clusters for Latin American countries pose challenges in interpretation, possibly due to limited data and its quality.

![My Image](/assets/img/action_cluster_page-0001.jpg)

Transitioning to the action genre, similar narrative structures emerge, with instances of "Cinderella" clusters (cluster 1 for GBR, cluster 3 for USA; cluster 2 for IND, and possibly cluster 2 for LAT) and "Man in the Hole" clusters (cluster 3 for GBR, cluster 1 for USA, IND, and LAT). Notably, the third cluster for India in the action genre closely mirrors the corresponding cluster in the drama genre. This alignment may contribute to the observed difference in positive sentiment percentages for India, highlighting the importance of exploring cross-genre patterns in emotional arcs.

<style>
    p {
        text-align: justify;
    }
</style>

![My Image](/assets/img/thriller_clusters_page-0001.jpg)

<p>
Transitioning to the thriller genre posed additional challenges in interpretation. For the United Kingdom (GBR), the analysis revealed a "Tragedy" cluster 1 (Riches to Rags), an uninterpretable cluster 2, and a "Man in the Hole" cluster for cluster 3. The intricacies of these clusters suggest diverse emotional arcs, making it a complex genre to analyse comprehensively.
In the case of the United States (USA), the first cluster appears to follow an "Oedipus" narrative, followed by a "Rags to Riches" arc. Cluster 2 aligns with a "Cinderella" narrative, while the third cluster exhibits a "Cinderella" arc at the beginning and end, resembling a "Man in the Hole" emotional trajectory. This diversity within the clusters showcases the multifaceted nature of storytelling in the thriller genre.
For India (IND), the first two clusters exhibit a "Man in the Hole" emotional arc, while the third cluster, initially appearing dissimilar, surprisingly aligns with the trends observed in the drama and action genres. This remarkable consistency indicates a recurring thematic pattern, where the emotional trajectory comprises an "Oedipus" phase followed by a "Cinderella" arc. Lastly, Latin American countries (LAT) exhibit distinctive emotional arcs in the thriller genre. Cluster 1 aligns with a “Man in the Hole” narrative, while cluster 2 follows a “Rags to Riches” emotional arc. This genre-specific analysis sheds light on the diversity and complexity of emotional narratives within terrorism-themed movies, offering a nuanced perspective on how different countries approach storytelling in this challenging genre.
</p>

<p>
In summary, our thorough analysis of sentiment scores in terrorism-themed movies has uncovered distinct patterns and notable variations across key countries. The United States, India, and the United Kingdom stand out as focal points, providing substantial datasets for nuanced exploration. Additionally, South and Central American countries exhibit intriguing sentiment differentials, prompting a collective analysis for meaningful insights.
</p>

<p>
India distinguishes itself with a significant positive sentiment of approximately 27.59%, deviating from global trends. This suggests a nuanced approach in Indian cinema, where the genre’s unrestrained and uninhibited storytelling allows for a rich array of emotional expressions. Characters traverse a wide spectrum of feelings without the need for meticulous justification, enabling Hindi movies to tap into a reservoir of emotional vulnerability, particularly in male characters—a facet less frequently explored in Hollywood narratives. Conversely, Hollywood narratives typically unfold with calculated emotional intensity, reserving tear jerkers for narratives of profound significance and contributing to the cinematic canon as important works. The emotional terrain explored in Hollywood is often tethered to the gravity of the overarching plot, resulting in a more measured and controlled emotional resonance.
</p>

<p>
Looking ahead, as we employ advanced techniques like BERT, we anticipate uncovering deeper insights and hidden nuances in the data. Our commitment to precision and thorough exploration remains steadfast as we unravel the intricacies of sentiment and storytelling dynamics in terrorism-themed movies.🔍
</p>

<p>
And now, ladies and gentlemen, let me introduce the all mighty analytical beast (drum roll 🥁): <code>DistilBERT-base-uncased-emotion</code>. This distilled version of our heavyweight champ, BERT, is quicker on its data feet, but still manages to provide just as much insights on the emotional depiction of movies as its bigger brother. Thanks to its world-class pre-training on datasets labeled with emotional states, it predicts the emotional tone of a text. How is that? Well, for each sentence in a given text, it outputs 6 scores, all between 0 and 1, and each one referring to specific emotions: Sadness 😢, joy 😁, love🥰, anger😡, fear😰 and Surprise 😲!  Enough with the introductions, let's unpack the emotional suitcase that terrorism-related movies have carried.
</p>

<p>
<strong>Global mood swings: an emotional journey through the cinematic lense of terror</strong>
Remember the map of the Vader sentiments across all countries? Well, we did the same exact thing...But this time, with the emotion predictions we obtained from running our high-tech secret weapon, just for fun, before diving into the emotions independently!
</p>

{% include_relative assets/img/map_meanscores_bert.html %}

<p>
Starting with North America and European countries, they have slightly higher mean emotional scores than the rest of the world -like the tip of Mount Everest-, probably due to the tendency of these countries to emphasize on patriotism or heroism patterns. And then, we have more subtle emotional nuances in the Middle East and parts of Asia where the movies might deliver a somber depiction of terrorism in movies. It is also interesting to note that there a few emotional outliers - Cameroon, Senegal, and Uruguay – hitting the emotional jackpot with the highest scores, and - Morocco, Kenya, and Vietnam- keeping their empotions more reserved. But let's not get carried away with these numbers since these countries do not count among those with the highest number of cinematic productions. One must also note that this mosaic of emotions might look impressing at first sight, but it is in reality a subtle color gradient, with an extremely tight range of emotion scores hovering around 0.1666, indicating that all countries seem to be on the same page... How to make the cut? Let's dissect these mean scores into individual emotions and visualise their distribution.
</p>

{% include_relative assets/img/map_individual_scores_bert.html %}

<p>
With our fancy map of individual emotion scores across the world, we are all set to understand the depiction of terrorism-related movies.   
<strong>Global emotional tendencies</strong>  
Unsurprisingly, the fear map is quite homogeneous, showcasing high scores for practically all the countries around the globe. One cannot help but find it comforting that we share a collective shiver down our spine when terrorist plots unfold on the big screen. Anger is also present around the world since its map illustration is quite heated, perhaps evocating storylines of retaliation. And sadness, well it caught the blues! Indeed, this map shows lower scores that for the other emotions depicted, indicating that terrorism-related productions globally hold back on the watery eyes and do not globally depict sorrow or tragedy. On the other side of the emotional spectrum, joy and love are clearly under-represented. However, surprise shows the lowest scores across the globe indicating that these movies might not give much importance to delivering plot twists. Furthermore, if we look at the range of scores for the surprise emotion, it is by far the smallest one with all scores inferior to 0.07!  The same applies for love, for which the score across countries is always smaller than 0.1. It looks like we found the least popular emotions across terrorism-related movies. It looks like we found the least popular emotion across terrorism-related movies...
All in all, terrorism-related movies seem to have a negative emotional tone, unsurprising given the nature of the subject. But, is it really homogeneous between all the regions?      
<strong>Regional emotional tendencies</strong>  
As we navigate over the globe, it appears that different regions add their specific touch when it comes to representing terrorism in the movies they produce. For instance, countries like Egypt, Senegal and Chilihave the highest scores associated to the anger emotion (0.54 and 0.48 respectively). On the other side, western countries such as Great-Britain or the USA, seem to focus more on fear and anger, being the two emotions with the highest scores acording to the maps.

Then there are a few outliers; regions that have overall less cinematic productions, where the emotional tone could be influenced by a smaller sample of films. For example, Tunisia shows an extremely high joy score (0.87) in comparison to very low scores associated to the other emotions, and this is due to the fact that these scores are extracted from a single production, being a short documentary entitled "De Carthage à Carthage" on the Carthage Film Festival...

</p>

<p>
<strong>Time travelling through terror</strong>
{%include_relative assets/img/time_series.html%} 
The graph starts off with the cinematic equivalent of a mood swing. The early 1900's to early '20s show ups and downs -or oscillations- in all 6 emotions, more importantly in anger, fear and joy, with anger then fear being the top emotions. This probably mirrors the confusion experienced by a society in times of war.
Moving forward to the mid-century, it is as if the world took a deep breath, steadying itself: The emotion scores slightly simmer down. What is most surprising is that this 'steady-state' remains up until the '2000s even though the world has experienced several wars and terrorist attacks during such a long time period...
Perhaps it is more interesting to change perspectives to draw more concrete conclusions on our emotional rollercoaster of terror...
</p>

{% include_relative assets/img/time_heatmap.html %}

<p>
While the line graph allows us to track the oscillations of emotions over time, the heatmap offers an immediate visual comparison of the different emotions along the years.

Looking at the heatmap, there seems to be a combination of emotions that dominate certain periods. The following patterns clearly stand out:

- In the early period covered by our dataset, the heatmap shows the most vibrant palette of all covered periods. Indeed, the emotional swings are the most pronounced during this time period, showing a clear inferiority of the surprise, sadness and love emotional scores, but on the other side, a diversity in the depiction of anger, fear and...joy! Why is that? Well, nothing screams entertainment more than post-war times.
- Moving into the mid-century, the heatmap seems to adopt a slightly cooler hue - indicating lower overall emotion scores - as if the world takes a break from overly emotional cinematic productions.
- When we arrive to the 21st century, the heatmap looks like it has been hit by an anger and fear bomb, possibly due to the context of the rise of terrorism attacks around the world, such as 9/11 and the wars it lead to after.
</p>
