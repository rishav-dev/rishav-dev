<div align="center">
  <img src="./assets/banner.png" alt="Rishav Chakravarty. Built on data. Driven by curiosity." width="100%" />
</div>

<div align="center">

<a href="https://www.rishavchakravarty.com"><img src="https://img.shields.io/badge/Portfolio-rishavchakravarty.com-22D9FF?style=for-the-badge&labelColor=050509&logo=googlechrome&logoColor=22D9FF" alt="Portfolio" /></a>
<a href="https://www.linkedin.com/in/rishav-dsc"><img src="https://img.shields.io/badge/LinkedIn-rishav--dsc-6258FF?style=for-the-badge&labelColor=050509&logo=linkedin&logoColor=6258FF" alt="LinkedIn" /></a>
<a href="https://kinnovationgroup.com"><img src="https://img.shields.io/badge/Venture_studio-Kinnovation-FFB02E?style=for-the-badge&labelColor=050509&logo=rocket&logoColor=FFB02E" alt="Kinnovation" /></a>
<a href="mailto:rishavchakra@umass.edu"><img src="https://img.shields.io/badge/Email-rishavchakra@umass.edu-B2FF3E?style=for-the-badge&labelColor=050509&logo=gmail&logoColor=B2FF3E" alt="Email" /></a>

</div>

<div align="center">
  <img src="./assets/stats.png" alt="Six public repositories. $1,550 in pitch prizes. 25,886 records in one analysis. 519 documents across ten universities." width="100%" />
</div>

<div align="center">
  <sub><b>Every number above links to something on this profile you can open and check.</b></sub>
</div>

<br />

## About

I came into data science through psychology. Four years of behavioural research
before I wrote a line of production code, which is why I tend to start with the
decision a person actually made rather than the feature that happens to
correlate with it.

I am finishing an **M.S. in Data Analytics and Computational Social Science** at
UMass Amherst. Before that, a postgraduate diploma at UT Austin and a B.S. in
Psychology with a computer science minor at Virginia Tech. I ran a dining hall
for five and a half years while doing most of it.

Everything below is a public repository. Clone it, run it, check my numbers
against my data. If I cannot link it, it is not on this page.

<img src="https://img.shields.io/badge/Open_to-Data_Science_·_Machine_Learning_·_Analytics_roles-22D9FF?style=flat-square&labelColor=050509" alt="Open to roles" />

<br />

## Work you can open

<table>
<tr>
<td width="50%" valign="top">

### [Mental Health Signal on Reddit](https://github.com/rishav-dev/MentalHealthResearch-SocialMedia)

<img src="https://img.shields.io/badge/25,886-posts_and_comments-22D9FF?style=flat-square&labelColor=050509" alt="25,886 posts and comments" />

6,398 posts and 19,488 comments out of r/Anxiety, r/depression and
r/mentalhealth. Every item scored three separate ways, then three
classifiers put against each other on the labels.

Raw CSVs, scored CSVs, model results and the Dash dashboard are all in
the repo.

`Python` `PRAW` `scikit-learn` `NLTK VADER` `Transformers` `Plotly Dash`

</td>
<td width="50%" valign="top">

### [Campus Safety Alerts, Ten Universities](https://github.com/rishav-dev/Project-DACSS-758)

<img src="https://img.shields.io/badge/519-documents,_10_universities-FFB02E?style=flat-square&labelColor=050509" alt="519 documents across 10 universities" />

Ten universities publish their crime alerts ten different ways, so I
wrote ten bespoke scrapers and one comparable dataset out the other side.
HTML and PDF, 506 and 13.

Every row carries the archive URL, source URL, content hash and scrape
timestamp.

`Python` `BeautifulSoup` `pdfminer.six` `cloudscraper`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [The Evolution of the Billboard Hot 100](https://github.com/rishav-dev/690s-final)

<img src="https://img.shields.io/badge/24-years_of_charts,_scrollytold-6258FF?style=flat-square&labelColor=050509" alt="24 years of charts" />

An argument you scroll through rather than a dashboard you poke at.
Billboard chart data joined to Spotify audio features, 2000 to 2023,
ending in a 3D pass through the feature space.

Missing numerics are filtered, not imputed. A quietly imputed audio
feature is a lie you then plot.

`D3.js` `Three.js` `JavaScript` `Python`

</td>
<td width="50%" valign="top">

### [Misere Nim Agent](https://github.com/rishav-dev/nim-agent)

<img src="https://img.shields.io/badge/0.82s-hard_move_budget-B2FF3E?style=flat-square&labelColor=050509" alt="0.82 second move budget" />

Iterative-deepening minimax with alpha-beta pruning, a transposition
table keyed on sorted pile shape, and move ordering from a misere
specific evaluator.

The server allows one second. I budget 0.82 and compute a known-good
fallback before the search starts, so a slow board still returns a legal
move.

`Python` `Minimax` `Alpha-beta pruning` `Memoisation`

</td>
</tr>
</table>

<details>
<summary><b>The number I would defend in a room, from the Reddit study</b></summary>

<br />

Logistic regression and the random forest tied. The SVM was a hair behind.

| Model | Accuracy | Precision | Recall | F1 |
|---|---|---|---|---|
| Logistic Regression | 0.9125 | 0.8327 | 0.9125 | 0.8708 |
| Random Forest | 0.9125 | 0.8327 | 0.9125 | 0.8708 |
| Linear SVM | 0.9063 | 0.8322 | 0.9063 | 0.8676 |

Those three are closer to each other than any of them is to a careful reading of
what the labels actually mean, and I think that is the honest thing to say about
this kind of work.

The finding worth having came from the topic modelling instead. The clusters are
mostly **not** about mental health. They are about money, housing, politics and
social media. The subreddit is where people go to talk about anxiety, and what
they talk about is rent.

Figures are in `ml_model_results.csv` in the repo.

</details>

<details>
<summary><b>Two more repositories</b></summary>

<br />

**[nutri-navigator-app](https://github.com/rishav-dev/nutri-navigator-app)** `Dart`
The NutriNavigator client, built in Flutter. One of the six Kinnovation ventures.

**[rishav-dev.github.io](https://github.com/rishav-dev/rishav-dev.github.io)** `TypeScript`
My portfolio, hand-built. Next.js static export, a WebGL boot sequence written
against raw WebGL2 rather than a library, and an assistant that runs on a
Cloudflare Worker so there is no API key anywhere in the client.

</details>

<br />

## Kinnovation

A venture studio I co-founded with **[Kinjal Pandey](https://kinjalpandey.com/)**.
Six ventures, all joint work, all built by the two of us:
[Karnah](https://kinnovationgroup.com/karnah),
[CalendAI](https://kinnovationgroup.com/calendai),
[MeAsmi](https://kinnovationgroup.com/measmi),
[NutriNavigator](https://kinnovationgroup.com/nutri-navigator),
[Witness](https://kinnovationgroup.com/witness-platform), and Trendify AI.

Three pitch competitions, **$1,550** in prize money, won together. Neither of us
has ever pitched alone.

| Venture | Prize | Competition | Awarded by | When |
|---|---|---|---|---|
| Karnah | **$750**, second place | UPitch Spring 2026 | UMass Amherst Entrepreneurship Club | Apr 2026 |
| CalendAI | **$500** | Pitch competition | Apex Center for Entrepreneurs, Virginia Tech | Nov 2024 |
| Trendify AI | **$300** | Minute Pitch | Berthiaume Center, UMass Amherst | Oct 2025 |

All six are in development or at concept stage. None is a launched commercial
product and none is fundraising. More at
**[kinnovationgroup.com](https://kinnovationgroup.com)**.

<br />

## Stack

**Languages**

<img src="https://img.shields.io/badge/Python-22D9FF?style=flat-square&labelColor=050509&logo=python&logoColor=22D9FF" alt="Python" />
<img src="https://img.shields.io/badge/R-22D9FF?style=flat-square&labelColor=050509&logo=r&logoColor=22D9FF" alt="R" />
<img src="https://img.shields.io/badge/SQL-22D9FF?style=flat-square&labelColor=050509&logo=postgresql&logoColor=22D9FF" alt="SQL" />
<img src="https://img.shields.io/badge/JavaScript-22D9FF?style=flat-square&labelColor=050509&logo=javascript&logoColor=22D9FF" alt="JavaScript" />
<img src="https://img.shields.io/badge/TypeScript-22D9FF?style=flat-square&labelColor=050509&logo=typescript&logoColor=22D9FF" alt="TypeScript" />
<img src="https://img.shields.io/badge/Java-22D9FF?style=flat-square&labelColor=050509&logo=openjdk&logoColor=22D9FF" alt="Java" />
<img src="https://img.shields.io/badge/MATLAB-22D9FF?style=flat-square&labelColor=050509" alt="MATLAB" />
<img src="https://img.shields.io/badge/Bash-22D9FF?style=flat-square&labelColor=050509&logo=gnubash&logoColor=22D9FF" alt="Bash" />

**Machine learning and analysis**

<img src="https://img.shields.io/badge/scikit--learn-6258FF?style=flat-square&labelColor=050509&logo=scikitlearn&logoColor=6258FF" alt="scikit-learn" />
<img src="https://img.shields.io/badge/TensorFlow-6258FF?style=flat-square&labelColor=050509&logo=tensorflow&logoColor=6258FF" alt="TensorFlow" />
<img src="https://img.shields.io/badge/pandas-6258FF?style=flat-square&labelColor=050509&logo=pandas&logoColor=6258FF" alt="pandas" />
<img src="https://img.shields.io/badge/NumPy-6258FF?style=flat-square&labelColor=050509&logo=numpy&logoColor=6258FF" alt="NumPy" />
<img src="https://img.shields.io/badge/Transformers-6258FF?style=flat-square&labelColor=050509&logo=huggingface&logoColor=6258FF" alt="Transformers" />
<img src="https://img.shields.io/badge/NLTK-6258FF?style=flat-square&labelColor=050509" alt="NLTK" />
<img src="https://img.shields.io/badge/statnet_/_ERGM-6258FF?style=flat-square&labelColor=050509" alt="statnet and ERGM" />
<img src="https://img.shields.io/badge/Time_series-6258FF?style=flat-square&labelColor=050509" alt="Time series" />

**Visualisation**

<img src="https://img.shields.io/badge/D3.js-FFB02E?style=flat-square&labelColor=050509&logo=d3dotjs&logoColor=FFB02E" alt="D3.js" />
<img src="https://img.shields.io/badge/Three.js-FFB02E?style=flat-square&labelColor=050509&logo=threedotjs&logoColor=FFB02E" alt="Three.js" />
<img src="https://img.shields.io/badge/Plotly_Dash-FFB02E?style=flat-square&labelColor=050509&logo=plotly&logoColor=FFB02E" alt="Plotly Dash" />
<img src="https://img.shields.io/badge/Power_BI-FFB02E?style=flat-square&labelColor=050509&logo=powerbi&logoColor=FFB02E" alt="Power BI" />
<img src="https://img.shields.io/badge/Matplotlib-FFB02E?style=flat-square&labelColor=050509" alt="Matplotlib" />

**Platforms**

<img src="https://img.shields.io/badge/MongoDB-B2FF3E?style=flat-square&labelColor=050509&logo=mongodb&logoColor=B2FF3E" alt="MongoDB" />
<img src="https://img.shields.io/badge/SQL_Server-B2FF3E?style=flat-square&labelColor=050509&logo=microsoftsqlserver&logoColor=B2FF3E" alt="Microsoft SQL Server" />
<img src="https://img.shields.io/badge/Google_Cloud-B2FF3E?style=flat-square&labelColor=050509&logo=googlecloud&logoColor=B2FF3E" alt="Google Cloud" />
<img src="https://img.shields.io/badge/React-B2FF3E?style=flat-square&labelColor=050509&logo=react&logoColor=B2FF3E" alt="React" />
<img src="https://img.shields.io/badge/Node.js-B2FF3E?style=flat-square&labelColor=050509&logo=nodedotjs&logoColor=B2FF3E" alt="Node.js" />
<img src="https://img.shields.io/badge/Flutter-B2FF3E?style=flat-square&labelColor=050509&logo=flutter&logoColor=B2FF3E" alt="Flutter" />
<img src="https://img.shields.io/badge/Docker-B2FF3E?style=flat-square&labelColor=050509&logo=docker&logoColor=B2FF3E" alt="Docker" />
<img src="https://img.shields.io/badge/Cloudflare_Workers-B2FF3E?style=flat-square&labelColor=050509&logo=cloudflare&logoColor=B2FF3E" alt="Cloudflare Workers" />

<br />

## Also

**The Action Taker Award**, LISC Massachusetts and the IXL Center, 2025. Given
for leading the digital upgrades through their Digital Growth Accelerator. The
name is the part I liked. It was for executing, not for proposing.

Selected for the **Franklin County CDC Entrepreneurs Accelerator**, Spring 2026.

**IBM Z Xplore**, Mainframes and Machine Learning.

<br />

<div align="center">
  <a href="https://www.rishavchakravarty.com"><img src="https://img.shields.io/badge/There_is_an_assistant_on_my_site._Press_⌘K_and_ask_it_anything.-050509?style=for-the-badge&labelColor=050509&color=6258FF" alt="Press command K on rishavchakravarty.com" /></a>
</div>

<div align="center">
  <sub>Amherst, Massachusetts · <a href="mailto:rishavchakra@umass.edu">rishavchakra@umass.edu</a></sub>
</div>
