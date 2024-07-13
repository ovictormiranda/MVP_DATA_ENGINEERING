# MVP_DATA_ENGENIEERING

## Objective
The objective of this project is to develop a Minimum Viable Product (MVP) in data engineering to analyze Lionel Messi's career at FC Barcelona, specifically in La Liga matches. This project aims to explore and answer various questions about Messi's performance over the seasons using data provided by StatsBomb.

### Questions to be Answered
#### How many goals did Messi have?
  Analyze the total number of goals a Messi achieved in all La Liga seasons.
  
#### How many goals were from Open Play, Penalty, or Free Kick?
Categorize Messi's goals as coming from open play, penalties, or free kicks.
  
#### Who are the top 5 players who provided the most assists to Messi?
  Identify the five players who contributed the most assists to Messi's goals.

#### Who are the top 5 players who received the most assists from Messi?
  Determine the five players who received the most goal-assisting passes from Messi.

#### Which parts of the body did Messi use to score his goals?
  Classify Messi's goals according to the body part used (left foot, right foot, head, etc.).

#### In which position did he score the most goals?
  Analyze the position on the field where Messi scored the most goals.
  
#### What were the outcomes of his shots (off the post, off target, saved, goals)?
Analyze the outcomes of Messi's shots, classifying them as hitting the post, off target, saved, or goals.

#### How many nutmegs did he perform?
  Count the number of times Messi dribbled opponents by passing the ball between their legs (nutmeg).


Carrying out this MVP will provide a detailed understanding of Messi's performance in La Liga, offering valuable insights into his career and contributing to future analyses in the fields of data science and sports.

## Data Collection
The data is extracted from the StatsBomb platform, a company that develops databases of football statistics worldwide. Prominent clubs around the world, such as Liverpool, Lyon, West Ham, Roma, Newcastle, Aston Villa, and Borussia Dortmund, as well as Brazilian clubs like Atlético Mineiro, Internacional, and RedBull Bragantino, utilize these data in their daily operations to analyze their own players and performance, as well as rich data for analyzing opponents to make the best data-driven decisions.

Naturally, a platform with such value comes at a cost. However, StatsBomb also freely provides some data, such as the data on Bayer Leverkusen's undefeated championship campaign under Xabi Alonso, the 2023 Women's World Cup data, and the dataset I chose for this project, called 'The Lionel Messi Data Biography.' This dataset gathers data from Messi's entire career playing in La Liga, covering every touch, pass, and dribble over the 17 seasons he played for Barcelona.

The data is freely available and can be accessed through the provided API. However, it's not contained in a single file where we could simply download a package of Messi's data alone. This API offers all its free data, so obtaining specific data requires exploring it to understand how it works and how to 'mine this gold.'

## Conslusion
Throughout the project development, I realized the need to deepen my knowledge in big data and tools like cloud computing and Spark. Developing the pipeline to extract and transform data from the StatsBomb API into a table was the most challenging aspect. I managed to address the main proposed questions and explored additional queries to understand the database operations better.

Handling large volumes of data posed a significant challenge during the project execution. Iterations and tests on Google Colab and Databricks were crucial in overcoming these obstacles and achieving robust results.

In summary, developing this project was an experience that provided me with a foundation for future studies and projects, inspiring me to further study and understand Data Engineering.


