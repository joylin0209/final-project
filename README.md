# Final Project
## Research Question
My research aims to explore the phenomenon of misogyny on Taiwanese online forums. In recent years, gender issues in Taiwan have gained increased attention due to the legalization of same-sex marriage, the #MeToo movement, and the introduction of women's representation quotas in elections. Despite progress towards gender equality in legal and societal realms, there is a prevalent trend of misogyny on the internet. Therefore, I intend to delve into the content of this phenomenon as observed on online platforms.

The motivation behind this study is to investigate why, in societies striving for gender equality, such sentiments intensify. Exploring this phenomenon can reveal its origins, reflect societal conditions or macro structures, and potentially suggest solutions.

## Research Data


I plan to utilize web scraping techniques to extract posts from Taiwan's prominent PTT forum, focusing on the keyword "Tai-Nu台女" for selection. This term has frequently stirred controversy on Taiwanese forums, often categorizing women based on specific societal standards such as materialism, princess behavior, or preferences for foreign men. By selecting this contentious keyword, we not only capture posts related to anti-women sentiment but also explore whether these posts carry negative emotion. 
The content of the captured information currently mainly includes the article title, author (anonymous code name), publication date, article title, published bulletin board, and article type. It is expected that the original URL and a unique specific number will be added.

## Analysis Strategy
The methods I intend to use include categorization to determine the frequency of these posts appearing in different sections of the forum. Additionally, I will examine how temporal changes affect the frequency of keyword usage and identify the most commonly occurring context surrounding the keyword. This approach will help us understand the evolution of attitudes and discussions regarding this keyword across different times and communities.

## Coding Notebook description
This database contains two codings. Basically the task content is the same, the difference lies in the data. Final_Project_tainu.ipynb uses "台女(Taiwanese Girl)" as the keyword in PTT, and a total of 2969 articles were used for subsequent analysis. Although final_project_cow.ipynb also uses PTT as the database source, it uses "母豬 (cow)" as the keyword for deleting articles, and finally obtained 418 articles.
