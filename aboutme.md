---
layout: page
title: Explosive Narratives - Terrorism through the Cinematic Lens
subtitle: Investigating the impact of Terrorism on World Cinema
cover-img: /assets/img/main_img.jpg
thumbnail-img: /assets/img/main_img.jpg
share-img: /assets/img/main_img.jpg
use-site-title: true
---

Welcome to "Explosive Narratives: Terrorism through the Cinematic Lens" – where we light the fuse on the dynamite topic of terrorism in movies, without any real explosions, of course! Picture this: you're sitting in your comfy chair, popcorn in hand, ready to dive deep into the world of cinema where the only thing more thrilling than a car chase is our data-driven analysis.
So, grab your 3D glasses, because we're about to embark on a cinematic journey that's part data, part drama, and totally explosive – metaphorically speaking, of course! 🍿🎬💥

Throughout history, humans have used violence and intimidation, especially against civilians, in the pursuit of political and ideological aims. This idea defines terrorism, which has had a significant impact on society and culture. It is fair to assume that cinema portrays diverse cultures, lifestyles and issues, reflecting society, its joys, struggles, and complexities. Through films, we witness stories that resonate with our own experiences, making us feel connected and understood, and allowing us to learn more about what is happening in our world. In this context, terrorism has been portrayed in multiple movies. It is interesting to investigate the impact that terrorism has had on cinema, using the CMU Movie Corpus dataset and focusing on popularity across continents and countries, genre association, topic patterns, as well as emotional depiction.

---

## An Explosive Data Set💥

### Introduction to the Data Set

We are using the CMU Movie Summary Corpus dataset, where we've got 42,306 movie plot summaries extracted from Wikipedia, ready to detonate with information! It is packed with metadata extracted from Freebase, including Revenue, Genre, Release Data, Runtime and Language, as well as Character names and information about the actors who portray them. 

We're going to explore every nook and cranny of how movies depict terrorism. We hunted for the movies that have enough terror in their summaries, by filtering the data set to only keep movies that contain keywords relating to terrorism-themes in their plot summary.

Our mission includes four parts:
- Popularity Analysis: We'll find out if terrorism movies are the box office bomb or just a dud.
- Genre Analysis: We'll dissect whether these movies are action-packed thrill rides or dramatic tear-jerkers.
- Topic Modeling: We dig through words, phrases and dialogues to discover the topics underlying terrorism movies. It's like a treasure hunt, but with more words and less gold.
- Emotional Depiction: Here, we're going to dive into the emotional rollercoaster of terrorism-themed movies.

Let's start by getting to know our data. Shall we?🍿💣📊

### Basic Visualizations

Let's start by visualizing the counts of terrorism-related movies through time:

{% include_relative assets/img/time_series_t_movies.html %}

We can observe a growing trend in the production of terrorism-related movies over the years. This could suggest a growing interest in terrorism movies in cinema, but it could however be related to the smaller number of movies provided by the CMU dataset in the 1907-1940s period. There is a dramatic increase in the early 21st century period, where the bars reach their highest points. This could be reflective of global events and the increased prevalence of terrorism in news media, telling us about the role of terrorism in the public consciousness during these times, which may have influenced the film industry.

Now, let's look at the top countries that produce terrorism-related movies.

{% include_relative assets/img/pie_chart.html %}

As we can see, the US, followed by India, United Kingdom and Japan, are the most important countries when it comes to producing terrorism-related movies. This plot is of course a little biased, and it does not necessarily mean that these countries like to produce terrorism-related movies more than other. Hollywood and Bollywood are the most important movie production industries in the world, and they by nature produce more movies than other countries.

The next plot offers a sight into how many terrorism-related movies were produced in each country.

{% include_relative assets/img/map_t_movies_per_country.html %}

Again, we see that the US and India dominate with respect to the the number of terrorism-movies produced.

Alright, now that we've got to know our data a little better, it's time to dive into the fiery depths of analysis! First up: the Popularity Analysis. 

Lights, camera, analyze! 🍿💥🎬

---

## 1. Popularity Analysis - The Box Office Boom
Welcome to 'The Box Office Boom' – our explosive journey into the popularity analysis of terrorism movies! 🎥💥📈

Think of this section as our own red carpet into the world of blockbusters and hidden gems. We're not just talking numbers; we're diving into what makes audiences tick, cheer, and sometimes, jump out of their seats. It's a wild ride through ticket sales, audience reactions, and those jaw-dropping moments that make these films a hit or a miss.
#### Are terrorism-themed movies the box office's best friend or its awkward acquaintance? 
Terrorism-themed movies often walk a fine line between capturing the audience's attention with intense, suspenseful narratives and potentially alienating viewers due to the sensitive nature of the subject. The popularity of these films at the box office can provide insights into how well they strike this balance. Our analysis focused on two crucial metrics: box office revenue and movie ratings. The findings we uncovered not only surprised us but also painted a compelling picture of the audience's response to this genre.

### 1.1 The Box Office Showdown: Terrorism vs. Other Movies
We began our journey by examining the box office performance of terrorism-related movies and contrasting them with the rest of the cinematic landscape. The initial histogram we crafted displayed a clear trend: terrorism-related movies consistently outperformed others in terms of box office revenue.


{% include_relative assets/plots/boxoffice_trends.html %}


The histogram vividly illustrated that, on average, terrorism-related movies generated higher box office revenue than their counterparts. However, understanding the significance of this observation required statistical analysis.
### 1.2 The Numbers Speak Louder
Our team conducted a rigorous statistical analysis to validate our initial findings. The results were unequivocal - there existed a statistically significant difference in box office revenue between terrorism-related movies and others. This raised intriguing questions: Was it the gripping narratives or the inherent curiosity that led audiences to theaters?


{% include_relative assets/plots/boxoffice_comparative.html %}

![My Image](/assets/img/boxoffice_comparative_2.png)


### 1.3 The Ratings Game: A Closer Look at Critical Acclaim
Undeterred by the box office success, we shifted our focus to movie ratings. We asked ourselves, "Did terrorism-related movies not only capture the audience's wallets but also their hearts?" The ensuing histogram answered with a resounding "yes." Terrorism-related movies consistently received higher ratings compared to other genres.

{% include_relative assets/plots/rating_trends.html %}


The visualization portrayed a compelling story - audiences, it seemed, not only flocked to theaters for these movies but also appreciated the cinematic quality they offered. Again, statistical analysis supported our observation of a significant difference in ratings.

{% include_relative assets/plots/rating_comparative.html %}

![My Image](/assets/img/rating_comparative_2.png)

### 1.4 Conclusion
In conclusion, as we examined the impact of terrorism-related movies on the global film industry, we unearthed intriguing findings. These films not only achieve success in terms of box office revenue but also earn commendation from critics. Despite the inherent difficulties associated with a genre marked by tension and controversy, these movies distinguish themselves. It appears that viewers are drawn not solely for the gripping narratives but also for the artistic skill and creativity evident in crafting these insightful films.

Stay tuned for more insights as we explore other aspects of terrorism in cinema. Next up: Genre Analysis!

---

## 2. Genre Analysis - The Movie Genre Cocktail

Think of genre as secret agents; they've got all the gear - narrative elements, thematic content, stylistic approach, and the emotional response they aim to evoke in the audience. They help categorize films so that you don't end up in a rom-com when you were ready for a story high in suspense and plot twists about a hero saving thousands of people from the action of terrorists.

And when it comes to terrorism movies, they sneak up on you with action, disguise themselves in drama, and occasionally, they even wear the mask of comedy before the big kaboom! Our mission is to dissect the relationship between genres and terrorism movies.

So buckle up data nerds, as we dive bomb into the world of movie genres. It's going to be a blast! (pun intented) 🎥💣🔍

### 2.1 Are terrorism-related movies associated to particular genres?

#### Part 1: Chi-Square Independency Test
To know whether particular genres are used to depict terrorism-themed movies, we first test whether there is a significant association between movie genres and their portrayal of terrorism. We do a Chi-Square Independency Test that can validate whether any observed association between genres and terrorism portrayal is statistically significant, rather than due to random chance.

We have associated each genre with a unique integer, and associated to each movie a binary variable. Its value is 1 if the movie is terrorism-related, and it is 0 if it is not.

The null hypothesis in a Chi-Square Test of Independence states that there is no association or relationship between the two variables being tested. In the context of our analysis, the null hypothesis is formulated as follows:

Null Hypothesis (H0): There is no significant association between the genre of a movie and its classification as terrorism-related.

We find the following results:

![My Image](/assets/img/chi_square.png)

The p-value is lower than the significance level, meaning that we reject the null hypothesis. There is a significant association between genre and terrorism-related movies. Now, let's look at this association in a bit more detail by extracting the top 10 most prevalent genres of terrorism movies.

#### Part 2: Frequency Analysis - Terrorism vs Non-Terrorism Movies
For both non-terrorism- and terrorism-related movies, we have gathered the top 10 most common genres. We then plot the counts of both types of movies against the genres. We obtain the figure below.

![My Image](/assets/img/freq_analysis_t_vs_nont_movies.png)

What are the most prevalent genres of non-terrorism vs terrorism movies? Do they differ?
We see that:

- The top 10 most common genres of terrorism movies are: Drama, Action, Thriller, Comedy, Action/Adventure, Horror, Adventure, World cinema, Crime fiction and Science fiction.
- The top 10 most common genres of non-terrorism movies are: Drama, Comedy, Romance Film, Black-and-white, Short film, Thriller, Action, Indie, World cinema and Crime ficiton.
- We notice that for both sets of movies, the most prevalent genre is Drama. This could suggest that dramatic elements are central to storytelling in films regardless of the terrorism theme.

Now, for a more significant comparison, we will focus on the top 10 most common genres in terrorism movies, and we will look at the proportion of non-terrorism and terrorism movies for these genres.

![My Image](/assets/img/proportion_per_genre2.png)

What genres are more prevalent in terrorism related movies than in non-terrorism related movies?
- Action and Thriller: These genres seem to be more prevalent in terrorism-related movies when compared to non-terrorism-related movies.
- Adventure and Horror: While not as dominant as Drama, Action, or Thriller, these genres also appear more frequently in terrorism-related movies than in non-terrorism-related ones.
- Drama: This genre has a very high proportion in both terrorism and non-terrorism related movies.

Do these genre preferences suggest that certain genres are better suited to explore terrorism-related themes?
- **Action and Thriller:** These genres are traditionally associated with high energy, suspense, and conflict, which are common elements in terrorism narratives. The prevalence of Action and Thriller genres in terrorism-related movies could reflect the intensity and high stakes often associated with terrorism.
- **Adventure and Horror:** These genres could be more prevalent due to the way they can incorporate elements of the unknown and fear, which can reflect unpredictability and fear associated with acts of terrorism.
- **Drama:** While Drama is prevalent in both types of movies, its slightly reduced prevalence in terrorism-related movies compared to non-terrorism-related ones might indicate that while dramatic storytelling is universal, terrorism movies might need the inclusion of action or thriller elements to better portray the specific themes associated to terrorism.

Do these genre trends in terrorism-related movies reflect a global influence, or are they more indicative of Western cinematic trends?
   We discuss this in **section 2.2**.

How have the representations of terrorism in various genres evolved over time? We discuss this in **section 2.3**.

### 2.2 Does the prevalence of certain genres of terrorism-related movies change between world regions? And between countries?

 We visualize the heatmap of counts of movies of each genre for each region, then country.
This would provide a qualitative measure of the association between genres of terrorism-themed movies and regions/countries.

First, we look at the heatmap of movie genres by region:
{% include_relative assets/img/heatmap_per_region.html %}

Now, we do the same but by country. We only focus on the top 10 countries with the most terrorism movies.
Since there are a lot more movies from the USA, we can't really see the variation between genres for the rest of the countries. 
Therefore, we decided to check out the genre frequency of the USA movies alone, and look at a heatmap for the rest of the countries.
{% include_relative assets/img/heatmap_per_country.html %}

Here is a bar chart for the counts of movies per genre in the USA.

![My Image](/assets/img/counts_USA_tmovies_per_genre.png)

The prevalence of genres like Drama and Thriller in many regions might indicate a universal appeal of intense narratives that deal with complex human emotions and ethical dilemmas, which are often at the core of terrorism-related stories. In contrast, regions where certain genres are more popular may reflect regional storytelling traditions or preferences, such as a penchant for Action/Adventure in the Americas, which could be tied to the Hollywood influence and its history of high-stakes blockbusters.

Economic factors, including the availability of funding and resources, market size, and audience demographics, can significantly influence which genres are produced within a region. For instance, regions where Action/Adventure and Thriller genres are highly prevalent may have more established film industries capable of supporting the high production costs associated with these genres. They may also have larger audiences that provide the box office revenues needed to justify such investments.

The representation of certain genres, such as Action/Adventure and Drama, across multiple regions suggests that these genres have broad international appeal, likely influenced by the widespread distribution of Hollywood films. However, the presence of genres like World Cinema, which is more prevalent in Europe, indicates that unique cultural differences and cinematic expressions still persist despite the forces of globalization.

### 2.3 Were some genres of terrorism movies more popular during specific periods?

Here, we plot the evolution of counts of movies through time, for each genre.

{% include_relative assets/img/time_series_per_genre.html %}

By comparing these plots to the "Number of Terrorism-Related Movies per Year" in section **Introduction**, the number of terrorism-related movies for each genre follows the same general trend as for all terrorism-related movies together. Indeed, we see a net increase of movies over time for all genres. We notice that some genres are more prevalent than others (Drama, Thriller, Comedy, Action/Adventure and Horror).
In general, the film industry often goes through phases where certain themes become popular. The rise in popularity of terrorism-related themes could be part of a broader trend or movement within the industry during this time.

Let's look at particular peaks.
The peaks that stand out are those corresponding to Drama, Action, Thriller, Comedy, Action/Adventure and Horror.

Drama, Action and Thriller movies have a net increase starting from around 1995. We see a very important peak for these genres in the period from 1995 to 2011. This peak could be attributed to several factors, such as global events. This period saw significant global events that likely influenced cinematic trends. The end of the Cold War, the 9/11 attacks in 2001, and subsequent global events focusing on terrorism likely influenced filmmakers to explore these themes. Also, the early 2000s saw 
rapid advancements in filmmaking technology, enabling filmmakers to use advanced effects to explore the terrorism theme, particularly in action and thriller genres where effects are often very important.

As for Comedy and Action/Adventure movies, we don't notice as net an increase as for the previous genres. The increase is smoother.

Finally, Horror movies decrese in 1991, then have a net increase in 2002, which could be linked to specific cinematic trends at the time.

To conclude, the representation of terrorism in various genres have the same overall evolution over time, with an increase in the number of terrorism-movies of all genres. Some genres stand out with important peaks, notably Drama, Action and Thriller. However, no particular genre has a different evolution compared to others.

### 2.4 Conclusion:

And that's a wrap on our Genre Analysis!

So, what have we learned? Drama is the most prevalent movie genre, in both terrorism- and non-terrorism-relatd movies. It seems that whether our protagonists are diffusing a bomb or a dramatic love triangle, we just can't get enough of those emotional rollercoasters.

But when the smoke clears, it's Action and Thriller that really stand out. These genres are to terrorism movies what a fuse is to dynamite – absolutely essential for a spectacular show.
Adventure and Horror genres are the next most prevalent genres of terrorism movies. They serve up a blend of chills and thrills, often leaving us with the kind of cliffhangers that make you wish you had a parachute.

Globally speaking, it looks like genres representing terrorism movies are not very diverse between world regions and conutries. Drama and Thriller seem to be the universal language of 'boom'. However, we do notice some regional preferences for Action/Adventure or World Cinema.

As for the evolution of the number of terrorism films throughout time, all genres have the same trend. They are all characterized by an increase in movie counts, and some genres stand out with high peaks, such as Drama, Action and Thriller.
Whatever the genre, it seems like audiences are always ready for narrative detonation.

Now, grab your popcorn and your protective gear; we're moving on to the next explosive analysis before the timer runs out! 🍿💥🎥

---

## 3. Topic Patterns : Unraveling the Thematic Tapestry of Terrorism in Cinema

Alright, movie buffs and data detectives, gear up for a bit of fun in the serious world of terrorism movies! 🕵️‍♂️🍿💥

In our topic modeling adventure, we're not just crunching numbers, we're uncovering the secret sauce that spices up these films. It's like digging through a treasure chest of words, phrases, and dialogues to discover what makes these movies tick, boom, and sometimes, unexpectedly, make us chuckle.

So, let's take a light-hearted leap into this deep dive. Who knows? We might just find that amidst the chaos and drama, there's a quirky line or two waiting to be discovered.

### 3.1 The Art of Decoding Themes: A Peek Behind the Curtain

In the world of terrorism-themed movies, each frame, each dialogue carries a universe of themes. To unravel this complex web, we turn to Latent Dirichlet Allocation (LDA), a model that treats topics as a blend of words, and movies as a blend of topics. Our mission? To decode the underlying themes that shape these movies.

### 3.2 Topic Modeling with LDA: The Heart of Our Analysis

The magic of LDA transforms our collection of terrorism-themed movies into a rich mosaic of topics, each a complex tapestry of words, revealing hidden narratives.

#### Global Lens: The Universal Themes

Our first foray is into the general landscape. We examine movies from across the globe to identify overarching themes.

<p align="center">
  <img src="/assets/img/general_topics.png" alt="General Topics in Global Cinema"/>
  <br><em>Fig. 1: General Topics in Global Cinema</em>
</p>

Words like "attack," "police," "man," "kill," and "escape" dominate the scene, painting a picture of action, conflict, and suspense – the quintessential elements of terrorism movies. These terms are the brushstrokes of a universal cinematic language, illustrating the common narrative threads that bind diverse cultures in their portrayal of terrorism.

#### Country-Specific Narratives: Diverse Stories Unfold

Now, we zoom in on specific countries - the USA, the UK, India, and other key film-producing nations.

<p align="center">
  <img src="/assets/img/USA_TOPICS.png" alt="Themes in American Terrorism Movies"/>
  <br><em>Fig. 2: Themes in American Terrorism Movies</em>
</p>

<p align="center">
  <img src="/assets/img/INDIA_TOPICS.png" alt="Themes in Indian Terrorism Movies"/>
  <br><em>Fig. 3: Themes in Indian Terrorism Movies</em>
</p>

American movies often deploy themes of tactical operations and military might, mirroring the nation's real-world engagement with global security issues. Indian films, on the other hand, interweave terrorism with rich emotional and familial narratives, reflecting a cinema culture deeply rooted in personal stories and societal fabric.

#### Spotlight on Diversity: Beyond Borders

Expanding our lens to ten relevant countries, we uncover a spectrum of themes. From the poignant tales of personal loss in French cinema to the shadowy underworlds depicted in Japanese films, each country's cinematic portrayal of terrorism is a mirror to its cultural heartbeat and historical scars.

#### American vs. Indian Narratives: A Study in Contrast

The American and Indian cinemas stand out for their distinct approach to terrorism. American films often mirror the country's political stance, portraying terrorism through a lens of counterterrorism operations and strategic maneuvers. In contrast, Indian cinema delves into the emotional and societal impact of terrorism, painting a vivid picture of its ripple effects on human relationships and communities.

### 3.3 Conclusion: A World of Stories Told Differently

Our exploration into the thematic depths of terrorism-themed movies reveals the profound impact of cinema in mirroring the complexities of our world. Each film, from every corner of the globe, weaves a narrative that transcends mere storytelling, reflecting the nuanced interplay of cultural, historical, and societal influences.

American and Indian cinemas, with their contrasting portrayals of terrorism, highlight the diversity of this genre. American films often echo the nation's geopolitical stance with a focus on tactical narratives, while Indian cinema delves into the emotional and societal impacts, portraying a deeper human connection.

This thematic journey has shown that movies are more than entertainment; they are powerful cultural artifacts that encapsulate the fears, struggles, and aspirations of societies. They serve not only as reflections of the times but also as mediums for empathy and understanding across diverse global audiences.

As we conclude our examination of thematic patterns in terrorism-themed cinema, we are poised to delve into the realms of emotional depiction and sentiment analysis. This journey through the narrative landscapes of terrorism has laid the groundwork for our next exploration, where we will uncover not just what these films portray, but how they resonate emotionally with audiences. The intricate themes we've discovered set the stage for a deeper understanding of the emotional tones and sentiments that these films evoke, revealing yet another layer of the complex relationship between cinema and its portrayal of terrorism.

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

To extract more detailed insights, we aim to cluster the emotional arcs of movies, considering both country-specific and genre-specific contexts. It is crucial to note that attempting to cluster movies from diverse genres together may not yield meaningful results due to the inherent variation in storytelling approaches. Consequently, we will focus on drama, action, and thriller genres, given their prevalence in terrorism-themed movies, as shown in **Section 2: Genre Analysis**.

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


Transitioning to the thriller genre posed additional challenges in interpretation. For the United Kingdom (GBR), the analysis revealed a "Tragedy" cluster 1 (Riches to Rags), an uninterpretable cluster 2, and a "Man in the Hole" cluster for cluster 3. The intricacies of these clusters suggest diverse emotional arcs, making it a complex genre to analyse comprehensively.
In the case of the United States (USA), the first cluster appears to follow an "Oedipus" narrative, followed by a "Rags to Riches" arc. Cluster 2 aligns with a "Cinderella" narrative, while the third cluster exhibits a "Cinderella" arc at the beginning and end, resembling a "Man in the Hole" emotional trajectory. This diversity within the clusters showcases the multifaceted nature of storytelling in the thriller genre.
For India (IND), the first two clusters exhibit a "Man in the Hole" emotional arc, while the third cluster, initially appearing dissimilar, surprisingly aligns with the trends observed in the drama and action genres. This remarkable consistency indicates a recurring thematic pattern, where the emotional trajectory comprises an "Oedipus" phase followed by a "Cinderella" arc. Lastly, Latin American countries (LAT) exhibit distinctive emotional arcs in the thriller genre. Cluster 1 aligns with a “Man in the Hole” narrative, while cluster 2 follows a “Rags to Riches” emotional arc. This genre-specific analysis sheds light on the diversity and complexity of emotional narratives within terrorism-themed movies, offering a nuanced perspective on how different countries approach storytelling in this challenging genre.



In summary, our thorough analysis of sentiment scores in terrorism-themed movies has uncovered distinct patterns and notable variations across key countries. The United States, India, and the United Kingdom stand out as focal points, providing substantial datasets for nuanced exploration. Additionally, South and Central American countries exhibit intriguing sentiment differentials, prompting a collective analysis for meaningful insights.



India distinguishes itself with a significant positive sentiment of approximately 27.59%, deviating from global trends. We also encountered a cluster present for every genre that has an ascending tendency of sentiment score, meaning an increase in positive sentiments coupling this with the fact that the USA and the United Kingdom resemble each other so much, suggests a nuanced approach in Indian cinema . Here, we can list a few reason making Bollywood and Indian cinema in general special :

- **Cultural tradition :** Bollywood cinema is deeply interwoven with the rich tapestry of Indian culture, traditions, and societal norms. Films often mirror the socio-cultural narratives prevalent in Indian society, highlighting familial ties, societal obligations,... The emotional arcs within these films are reflective of these themes, providing a cinematic expression of the societal narratives.
- **Emotional Range:** In Bollywood, the "Fall-Rise" and "Cinderella" story arcs are particularly evocative, depicting protagonists who confront and surmount formidable obstacles. Such narratives resonate with the cultural values of resilience and perseverance, which are esteemed within Indian culture.
- **Musical Influence:** The integration of music and dance is a hallmark of Bollywood storytelling, which can serve to amplify the emotional arcs of the narratives. For example, the depiction of a character's ascension from hardship to success—a "Steady Rise"—is often punctuated with exuberant musical interludes, intensifying the emotional resonance and providing a unique cinematic experience.




Looking ahead, as we employ advanced techniques like BERT, we anticipate uncovering deeper insights and hidden nuances in the data. Our commitment to precision and thorough exploration remains steadfast as we unravel the intricacies of sentiment and storytelling dynamics in terrorism-themed movies.🔍



And now, ladies and gentlemen, let me introduce the all mighty analytical beast (drum roll 🥁): <code>DistilBERT-base-uncased-emotion</code>. This distilled version of our heavyweight champ, BERT, is quicker on its data feet, but still manages to provide just as much insights on the emotional depiction of movies as its bigger brother. Thanks to its world-class pre-training on datasets labeled with emotional states, it predicts the emotional tone of a text. How is that? Well, for each sentence in a given text, it outputs 6 scores, all between 0 and 1, and each one referring to specific emotions: Sadness 😢, joy 😁, love🥰, anger😡, fear😰 and Surprise 😲!  
Enough with the introductions, let's unpack the emotional suitcase that terrorism-related movies have carried.

### Global mood swings: an emotional journey through the cinematic lense of terror
Remember the map of the Vader sentiments across all countries? Well, we did the same exact thing...But this time, with the emotion predictions we obtained from running our high-tech secret weapon, and with each emotion independently!

{% include_relative assets/img/map_individual_scores_bert.html %}

With our fancy map of individual emotion scores around the world, we are all set to understand the depiction of terrorism-related movies.

- **Global emotional tendencies**

Unsurprisingly, the fear map is quite homogeneous, showcasing high scores for practically all the countries around the globe. One cannot help but find it comforting that we share a collective shiver down our spine when terrorist plots unfold on the big screen. Anger is also present around the world since its map illustration is quite heated, perhaps evocating storylines of retaliation. And sadness, well it caught the blues! Indeed, this map shows lower scores that for the other emotions depicted, indicating that terrorism-related productions globally hold back on the watery eyes and do not globally depict sorrow or tragedy. On the other side of the emotional spectrum, joy and love are clearly under-represented. However, surprise shows the lowest scores across the globe indicating that these movies might not give much importance to delivering plot twists. Furthermore, if we look at the range of scores for the surprise emotion, it is by far the smallest one with all scores inferior to 0.07!  The same applies for love, for which the score across countries is always smaller than 0.1. It looks like we found the least popular emotion across terrorism-related movies...
All in all, terrorism-related movies seem to have a negative emotional tone, unsurprising given the nature of the subject. But, is it really homogeneous between all the regions?      

- **Regional emotional tendencies**

As we navigate over the globe, it appears that different regions add their specific touch when it comes to representing terrorism in the movies they produce. For instance, countries like Egypt, Senegal and Chilihave the highest scores associated to the anger emotion (0.54 and 0.48 respectively). On the other side, western countries such as Great-Britain or the USA, seem to focus more on fear and anger, being the two emotions with the highest scores acording to the maps.

Then there are a few **outliers**; regions that have overall less cinematic productions, where the emotional tone could be influenced by a smaller sample of films. For example, Tunisia shows an extremely high joy score (0.87) in comparison to very low scores associated to the other emotions, and this is due to the fact that these scores are extracted from a single production, being a short documentary entitled "De Carthage à Carthage" on the Carthage Film Festival...

### Time travelling through terror

{%include_relative assets/img/time_series.html%} 
The graph starts off with the cinematic equivalent of a mood swing. The early 1900's to early '20s show ups and downs -or oscillations- in all 6 emotions, more importantly in anger, fear and joy, with anger then fear being the top emotions. This probably mirrors the confusion experienced by a society in times of war.
Moving forward to the mid-century, it is as if the world took a deep breath, steadying itself: The emotion scores slightly simmer down. What is most surprising is that this 'steady-state' remains up until the '2000s even though the world has experienced several wars and terrorist attacks during such a long time period...
Perhaps it is more interesting to change perspectives to draw more concrete conclusions on our emotional rollercoaster of terror...

{% include_relative assets/img/time_heatmap.html %}

While the line graph allows us to track the oscillations of emotions over time, the heatmap offers an immediate visual comparison of the different emotions along the years.

Looking at the heatmap, there seems to be a combination of emotions that dominate certain periods. The following patterns clearly stand out:

- In the **early period** covered by our dataset, the heatmap shows the most vibrant palette of all covered periods. Indeed, the emotional swings are the most pronounced during this time period, showing a clear inferiority of the surprise, sadness and love emotional scores, but on the other side, a diversity in the depiction of anger, fear and...joy! Why is that? Well, nothing screams entertainment more than post-war times.

- Moving into the **mid-century**, the heatmap seems to adopt a slightly cooler hue - indicating lower overall emotion scores - as if the world takes a break from overly emotional cinematic productions.
- When we arrive to the **21st century**, the heatmap looks like it has been hit by an anger and fear bomb, possibly due to the context of the rise of terrorism attacks around the world, such as 9/11 and the wars it lead to after.  

### The emotional cinematic portrayal of terror across Cultures
{% include_relative assets/img/bar_movies.html %}  
This bar chart was obtained after selecting the top 10 movies with the highest number of productions and it shows how these specific countries depict terrorism in their movies. Overall, this bar chart confirms the fact that anger seems to be the most represented emotion in terrorism-related movies, directly followed by fear. As an example, the United States and the United-Kingdom, the countries with the most production, are like twins with nearly-identical emotional distributions showing high fear and anger as well as very low sadness scores.

***🔍 Zoom on India 🇮🇳 :*** **Why focus on one emotion when you can have them all?**

India's bar chart resembles a Bollywood dance—colorful, vibrant, and full of energy- it is high on every emotion, having the highest joy score among all countries represented. What is interesting to see is that India seems to showcase every emotional aspect in these movies, even though they are related to a heavy subject -terrorism-. India therefore shows a unique storytelling style, embracing the complexity of life - nothing is completely black or white. As said before, this is clearly reflective of a broader trend within Indian cinema.

This being said, it is clear that when it comes to the leaders in the film industry, they seem to agree on the emotional depiction of terrorism-related movies, with some exceptions putting their grain of salt.

### Do genres align with their traditional emotional depiction when it comes to terrorism?
No, it is not the stock market but the rollercoaster of emotions in movie genres across decades!  

{% include_relative assets/img/genre_sentiments.html %} 

Seriously, to answer the question and keep it short, based on the emotion scores, most genres do align with their artistic direction: 

- True to its nature, drama seems to have taken "dramatic" to heart 🎭, showcasing fluctuations in all emotions.
- Anger and joy mirror themselves in action movies, with anger being the most represented emotion.

Now let's turn the spotlight on...Comedy! Traditionnaly, comedy is not really influenced by the gravity of the subjects it portrays. Yet, for terrorism-related movies, anger is surpringly high, even higher than joy overall -but this could be due to satiristic jokes around the subject of terrorism.

Overall, the emotion scores we obtained are quite special: they do not simply reflect the usual emotional routes of the genres, but the take them-twist them and turn them all the way around, giving us a portrayal as complicated as the subject itself.   

You think we are done? Well, brace yourself because we still have one trick up our sleeve. Up until now, we did not look into the evolution of emotional depiction in plots. Yet, this is precisely what allows us to have an idea about story arcs. Let's dive in!

### The Emotional journey of terrorism-related movies

{% include_relative assets/img/story_arcs_countries.html %} 

First and foremost, let's set the stage for how we orchestrated this data. We crafted a list of la crème de la crème terrorism-related movies by selecting the top 10 movies with the highest emotional scores for each one of our 6 emotion categories. Then, for each country in our crafted list, we averaged the emotional scores sentence by sentence, to visualise the narratives' emotional pulse. And well, it looks like every country took 'emotional journey' way too literally.

---

## Explosive Narratives: Terrorism through the Cinematic Lens

Ladies and gentlemen, as our cinematic bomb squad, we have come to the end of "Explosive Narratives: Terrorism through the Cinematic Lens". It's been a blast, and we've discovered some dynamite insights into the world of terrorism-themed movies!

In our Popularity Analysis, we saw that terrorism-related movies are like Leonardo DiCaprio in Cinema: very popular! These films don't just tickle the cash registers; they earn recommendation from critics. 

Genre Analysis taught us that Drama, Action, and Thriller genres are the dynamite trio in this explosive mix. These genres have seen their popularity skyrocket particularly from 1995 to 2011. Comedy and Action/Adventure genres, on the other hand, took a more scenic route, rising steadily but less dramatically.

As for Topic Modeling, we realized that terrorism-themed movies are more than just a series of bangs and booms; they're a mirror reflecting societal fears and triumphs. American and Indian cinemas, in particular, offered contrasting lenses - one tactical and the other emotional, showing us different facets of the same category of movies.

Our Sentiment Analysis revealed that emotions in these films are as volatile as a chemistry experiment gone wrong. From the dramatic highs and lows in Indian cinema to the surprising anger in comedy genres, we found that terrorism-related movies can stir up a whole cocktail of emotions, making for a thrilling movie-watching experience.

As we roll the credits on this project, remember: the next time you watch a terrorism-themed movie, it's not just about the booms and bangs. It's a journey through a complex landscape of genres, emotions, and cultural narratives. And who knows, maybe the next big blockbuster will be a data-driven analysis of movie trends – now that would be a real plot twist! 🎬💥🍿