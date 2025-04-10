## MSBA Team 4
Andrew Linton: https://github.com/amlinton7  

Malachi Ndur: https://github.com/MalachiNdur  

Grace Schaaff: https://github.com/gschaaff  

Mauni Branch: https://github.com/ybranchy

## Visualizations

## Project Scope

This project focuses specifically on AI in creative industries, with a narrow focus on AI-powered recommender systems in music streaming platforms. We aim to explore how user behaviors impact the effectiveness of recommendations, and how this behavior can be modeled to enhance user experience and engagement with the platform.

## Project Details

The business problem we aim to address is increasing customer loyalty and growth. The majority of music streaming platforms are driven by a subscription model, meaning that they rely on the recurring revenue of customers' monthly or annual payments to the platform. Thus, stable revenue is dependent on loyal customers, and growing revenue is dependent on growing the customer base. 

Much of the reason for the expansion of digital music streaming in the past 10 years, as compared to CDs, iPods, etc. is the level of customizeability and recommendation that a streaming platform can offer. A key differentiator for major platforms such as Spotify and Apple Music, is the companies' abilities to procure music that is directly to the user's taste. As these companies, and their smaller competitors continue to fight for customers, building AI models that are more in-tune with a customer's preferences is a crucial competitive advantage. 

Through out project, we demonstrate the benefits of recommender systems to companies in growing subscriptions and revenue, and value-add to consumers in bettering their music-listening experiences. 

As with any recommender system, whether social media, entertainment, or music, we risk bias in the recommendations that the model provides to users. With music specifically, users with aggressive or extreme beliefs could be recommended songs containing lyrics that motivate them to act in a harmful manner. Additionally, children could easily be recommended music with innapropriate or explicit content if not specifically marked as a children's account. 


### Overview

Art is extremely subjective. Whether you are looking at a painting, reading a book, listening to a song, or watching a movie, you may have a completely different response to it than the person sitting next to you, experiencing the same piece of work, but in an entirely different way. This subjectivity is what makes it very difficult for AI to recreate art that has the same effect as that of created by human beings. 
While AI may not be the best way to create art, it can be useful in many different ways to supplement art made by humans. Within creative industries, AI is  transforming how artists, designers, writers, and musicians work, as it has the ability to edit photos and videos, proofread writing, and even generate its own images. 

### Our Topic: AI In Music Streaming Platforms 

Another example of AI being used to supplement creativity is through recommender systems. Because all forms of art are experienced in a very personal way, it can be useful to have the art you experience, whether it be books, movies, music, or something else entirely, be personalized to your tastes. AI can enhance discovery by understanding user behavior patterns. Many streaming services, such as Netflix or Spotify, are already using AI in order to make movie or music recommendations for their users. This is why, for the purposes of our project, we have chosen to explore how recommender systems, specifically in music streaming platforms, use AI to personalize listening experiences and make recommendations. 


### Problem

The business problem we aim to address is increaseing customer loyalty and growth. The majority of music streaming platforms are driven by a subscription model, meaning that they rely on the recurring revenue of customers' monthly or annual payments to the platform. Thus, stable revenue is dependent on loyal customers, and growing revenue is dependent on growing the customer base. 

Much of the reason for the expansion of digital music streaming in the past 10 years, as compared to CDs, iPods, etc. is the level of customizeability and recommendation that a streaming platform can offer. A key differentiator for major platforms such as Spotify and Apple Music, is the companies' abilities to procure music that is directly to the user's taste. As these companies, and their smaller competitors continue to fight for customers, building AI models that are more in-tune with a customer's preferences is a crucial competitive advantage. 

Through out project, we demonstrate the benefits of recommender systems to companies in growing subscriptions and revenue, and value-add to consumers in bettering their music-listening experiences. 

As with any recommender system, whether social media, entertainment, or music, we risk bias in the recommendations that the model provides to users. With music specifically, users with aggressive or extreme beliefs could be recommended songs containing lyrics that motivate them to act in a harmful manner. Additionally, children could easily be recommended music with innapropriate or explicit content if not specifically marked as a children's account.

### Business Importance

Recommender systems are important for businesses in order to cater to their specific customer base overall, as well as allowing them to target multiple niche customer segments simultaneously. Personalized recommendations will improve user experience, which is always good for businesses. A user who feels the platform "gets" them is more likely to return, listen longer, and subscribe. Accurate recommendations increase  interaction with the platform and overall brand loyalty. The accuracy or quality of recommendations and personalization can even be used as a way for brands to differentiate among competitors.

Recommender systems are also very useful for platforms that rely on ad revenue, as targeted ads are more likely to lead to interactions or purchases.

Using AI for recommendations can also increase operational efficiency. The model has the ability to collect user data and make recommendations for a large scale of users in a short time. 


### Research: MUSE 

MUSE is an example of an advanced music recommender system that takes “shuffle play” into account. Shuffling songs puts tracks in a random order, and the user is not actively choosing to listen to that specific song, so it can hinder a typical recommender system and lead to less accurate suggestions.

Therefore, the MUSE system focuses on improving music recommendations by learning from the seemingly random shuffle play behavior. Unlike traditional systems that focus only on individual songs, MUSE models entire sequences of tracks (like how users move from one song to the next) to capture how users engage with a playlist or listening session. It also takes into account data like number of skips, replays, and total listening duration. 


## Demo Code: Recommender Systems
[Click here to launch the demo notebook in Colab](https://colab.research.google.com/drive/1uDB6mOqb_SkLPCkuKNFWAYupRd5mLrOT?usp=sharing)

We wanted to create a very simple model—as opposed to the more complex MUSE recommender mentioned in the research article—that gives personalized song recommendations based on individual songs and user interactions. Our goal was to recommend five songs to a user based on their listening history, while also displaying useful metadata like the song title, genre, and whether the user has that song saved to their library or favorites.
To achieve this, we used Python and TensorFlow to build a basic retrieval-based recommendation system. We started by using GenAI to generate two synthetic datasets:
- User Ratings Dataset: user_id, song_id, song_title, song_genres, in_library, is_favorited
- Song Information Dataset: song_id, song_title, song_genres

We first converted user and song IDs into numeric values to make them compatible with TensorFlow. Then we created a TensorFlow dataset, defined a simple retrieval model using embedding layers, and trained it on user-song interaction data. Finally, we generated the top 5 personalized song recommendations for a sample user and mapped the results back to include each song’s title, genre, and whether it was in the user’s library or favorites.

This project demonstrates how even simple machine learning models, developed in Python, can be used to create meaningful, personalized experiences based on user behavior.

## Website Demo: Vibe Coding


## What's Next?
Looking ahead, future directions include:
- **Emotion-based or mood-aware recommendations**.
- **Real-time adaptation** to changing user behavior.
- Addressing **bias and fairness** in recommendation outputs.
- Exploring **multi-modal AI** (e.g., combining audio features, text metadata, and behavior).
- Considering **ethical implications** like filter bubbles and artist representation.

OR 

As music recommender systems become more advanced, future directions include:
- Incorporating mood/emotion detection from songs and user behavior.
- Real-time learning to adapt to shifting user tastes.
- Ethical concerns, such as reinforcing filter bubbles or limiting exposure to diverse music.
- Fairness and bias in music recommendations (e.g., under-promoting certain artists or genres).
- Broader application of multi-modal AI, combining text, audio, and user behavior to create richer models.
  
## Responsible AI Considerations

## References List

[OpenAI](https://openai.com/)
[Research Article](https://arxiv.org/pdf/2308.09649)
[Claude](https://claude.ai/)


<!--
**MSBA-Team4/MSBA-Team4** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
