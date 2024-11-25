# Portfolio
---
## eSports and Game Analytics

### Dota 2 Tundra Esports


<div style="text-align: justify">
My current freelance activity is professional eSports analytics in Dota 2 for Tundra Esports - The International 2022 champions. I provide the team - players and a coach - with the most relevant data regarding the upcoming oponents as well as develop custom solutions for every possible request they might have. I rely heavliy on in-game data from the replay files as well as publicly available data sources - Spectral.gg, STRATZ, DotaBuff, OpenDota, and Dota2ProTracker. I also help the SMM team by providing instersting data findings to help grow the social media channels. I know how to use data to  to uncover hidden opportunities and transform them into successful outcomes, even in challenging or less-explored areas.

During our time together we achieved:
4th place at Esports World Cup, Riyadh
3rd place at FISSURE Universe: Episode 3
3rd place at The International 2024, Copenhagen
3rd place at PGL Wallachia Season 2, Bucharest
2nd place at BetBoom Dacha 2024, Belgrade

You can also read the interview I gave in Copenhagen here - [Stats, Strategy, and Saksa: Interview with Tundra Esports Data Analyst](https://bo3.gg/dota2/articles/stats-strategy-and-saksa-a-conversation-with-tundras-data-analyst-degaz)
</div>

<br>
<center><img src="https://i.imgur.com/1YyingY.jpeg" height="420"/></center>
<br>

## Data Analysis

### Osuuspankki GIS Dashboard Project

[![Static Badge](https://img.shields.io/badge/Open_on_GitHub-teal?logo=github)](https://github.com/DegaZZZ/op_project_map) <br>
[![Static Badge](https://img.shields.io/badge/Open_Web_Demo-%233F4F75?logo=Plotly)](https://opmap-ff2c08ccb99b.herokuapp.com)


<div style="text-align: justify">
A Data Science Project made in Aalto University for a task right from OP representatives. Most of the Data Engineering in this project was done by me. <b>Dash</b> and <b>FastAPI</b> are wrapped into a single <b>Asynchronous Server Gateway Interface (AGSI)</b> which is hosted on Heroku using Uvicorn as a server. <b>BigQuery</b> is used for storing all the table datasets that were used during the development of the project and analytics. Connections to the database can be made via an API. The latter also contains some very useful methods. Documentation for the API exists, but currently is not available (soon will be added). Active usage of latest and most powerful <b>GIS</b> techonologies. A demo map is available via a URL on GitHub page or by clicking a badge above. Final version is under NDA, but some parts can be shown on request if needed. Dashboard also has a <b>GenAI-powered</b> chatbot that helps users to understand data.
</div>
<br>
<center><img src="https://i.imgur.com/JfEk1UU.png" width="420"/></center>
<br>

### Exoplanet Data Analysis

[![Open in browser](https://img.shields.io/badge/HTML-Open%20in%20browser-blue)](https://degazzz.github.io/projects/SpaceKeplerPortfolio.html)

<div style="text-align: justify">
This project explores the properties and distribution of exoplanet candidates using the Kepler Object of Interest (KOI) dataset. Analyzing the class distribution, orbital periods, magnitude distribution, correlation matrix, right ascension and declination, and KOI scores, valuable insights are gained. The findings reveal the prevalence of shorter orbital periods for confirmed planets, a bi-modal magnitude distribution, variations in stellar density based on celestial coordinates, and confidence levels of planet candidates.
</div>
<br>
<center><img src="https://i.imgur.com/gPt16B5.png" width="420"/></center>
<br>

### Musical Instrument(s) Review Analysis

<a target="_blank" href="https://colab.research.google.com/github/DegaZZZ/degazzz.github.io/blob/main/projects/AmazonMusicReviews.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>


<div style="text-align: justify">
This project demonstrates the ability to perform data analysis on customer reviews. It showcases skills in data preprocessing, natural language processing (NLP), and data visualization using Python libraries such as pandas, spaCy, and Plotly. The project focuses on extracting valuable insights from text data, including the top 20 most used words and adjectives in the reviews. It highlights skills in NLP techniques, data manipulation, and generating visualizations to gain a deeper understanding of customer sentiments and provide actionable insights for businesses.
</div>
<br>
<center><img src="https://i.imgur.com/rFIqG2O.png" width="420"/></center>
<br>


### Dota 2 Facets Rankings using Wilson Score

[![Static Badge](https://img.shields.io/badge/Read_on_Reddit-FF4500?logo=reddit&logoColor=white&link=https%3A%2F%2Fwww.reddit.com%2Fr%2FDotA2%2Fcomments%2F1d430ys%2Ftop_20_facets_by_rank_per_role_8k_mmr_30_matches%2F)](https://www.reddit.com/r/DotA2/comments/1d430ys/top_20_facets_by_rank_per_role_8k_mmr_30_matches/)

Innovative implementation of Wilson score for analysis of Dota 2 in-game data. Report was highly supported by the community and used by multiple professional eSports teams. Calculations were done with <b>Pandas</b> with visualisations made via <b>Datawrapper</b>

<br>
<center><img src="https://imgur.com/OTVSB3l.png" width="420"/></center>
<br>

---
## Machine Learning

### Dota 2 Match Outcome Prediction using CatBoost

[![View on GitHub](https://img.shields.io/badge/HTML-Open%20in%20browser-blue)](https://degazzz.github.io/projects/Dota2CatBoost.html)

<div style="text-align: justify">
In this project, I developed a CatBoost Classifier model to predict outcomes of Dota 2 matches, a complex task due to the game's dynamic environment. Despite these challenges, my model showcased strong performance, achieving an AUC-ROC score of 0.80±0.0053, indicating its ability to accurately differentiate between wins and losses. This project highlights my capability to apply advanced machine learning techniques to real-world scenarios, providing reliable predictive insights.
</div>
<br>
<center><img src="https://i.imgur.com/uErCCR0.png" height="420"/></center>
<br>

---
## Software Development

### Data Guild GPT Telegram Bot

[![Static Badge](https://img.shields.io/badge/Open_in_Telegram-blue?logo=telegram)](https://t.me/dg_amabot)

<div style="text-align: justify">
Developed a whole Telegram bot for Aalto University's Data Guild internal chats written on <b>Python</b> using. Bot uses <b>API of GPT-3.5 and GPT-4 models</b> for various useful (and sometimes fun) features, as well <b>Stable Diffusion API</b> for Image Geneneration on a given prompt. Bot is hosted on Heroku. Some but not all of the features are - poll generation on a given prompt, image generation, making graphs on a given topic, answering any questions. In publicly available version of the bot messages are not collected and are not stored anywhere due to Code of Conduct and GDPR. However, internal test local version make usage of <b>Redis</b> for caching and preserving some sort of consistence in the dialog.
</div>
<br>
<center><img src="https://i.imgur.com/VrslndZ.png" width="420"/></center>

