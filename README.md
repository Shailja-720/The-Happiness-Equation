# The-Happiness-Equation
Decoding the relationship between income, health, freedom, and life satisfaction
What Inspired Me
I was inspired by a simple but striking contradiction: some of the world’s richest countries are not always among its happiest. Countries such as Finland, Denmark, and Iceland consistently rank near the top of the World Happiness Report, while several high-income nations experience weaker life satisfaction, rising youth distress, or declining social trust. This made me want to investigate whether happiness can truly be explained by income alone.
The central question became:
\text{National Well-Being} \neq f(\text{GDP per capita}) \text{ alone}
Instead, happiness appears to depend on a broader system of social, institutional, cultural, and personal factors.
What I Learned
Through this project, I learned that economic growth is important, but it is not sufficient for well-being. Higher GDP can improve access to healthcare, education, housing, and security; however, it does not automatically create trust, belonging, freedom, or strong social relationships.
I also learned that happiness is multidimensional. The World Happiness Report and related research commonly connect life evaluations to factors such as:
•	GDP per capita
•	Social support
•	Healthy life expectancy
•	Freedom to make life choices
•	Generosity
•	Perceptions of corruption
•	Mental health and emotional well-being
A useful way to express this relationship is:
H_i = \beta_0 + \beta_1 GDP_i + \beta_2 SocialSupport_i + \beta_3 Health_i + \beta_4 Freedom_i + \beta_5 Trust_i + \epsilon_i
where H_i represents the happiness or life-evaluation score for country i, and \epsilon_i captures unobserved cultural, historical, and individual differences.
Another major lesson was that measurement matters. A country may score highly on self-reported life satisfaction but still face serious challenges in youth mental health, inequality, loneliness, or day-to-day emotional distress. Therefore, rankings should be interpreted carefully rather than treated as a complete measure of national well-being.
How I Built the Project
I built the project around the idea of comparing economic performance with happiness outcomes across countries and regions.
Research Question
My main research question was:
Why do national happiness rankings diverge from economic growth, and which non-economic factors best explain differences in well-being across countries?
Data and Variables
I used country-level data on happiness scores, GDP per capita, social support, health, freedom, corruption perceptions, and demographic indicators. The project focused especially on comparing Nordic countries, wealthy Western nations, and Latin American countries.
Variable	Role in the Project
Happiness / life evaluation score	Main outcome variable
GDP per capita	Economic factor
Social support	Measures availability of someone to rely on
Healthy life expectancy	Captures physical well-being
Freedom to make life choices	Measures autonomy and agency
Corruption perceptions	Proxy for institutional trust
Youth well-being indicators	Helps examine generational differences
Analytical Approach
First, I explored the data using visualizations to identify patterns and outliers. I compared happiness scores with GDP per capita and observed that wealth alone could not explain the full variation between countries.
Next, I examined correlations between happiness and social variables. Social support, institutional trust, and freedom showed particularly strong relationships with life satisfaction.
I then used regression analysis to estimate the relationship between happiness and multiple predictors:
Happiness = \beta_0 + \beta_1 GDP + \beta_2 SocialSupport + \beta_3 Health + \beta_4 Freedom + \beta_5 Trust
This helped me assess which factors remained important after accounting for income. I also grouped countries by region to understand why Latin America often performs better than its economic indicators alone would predict.
Key Findings
•	High GDP improves well-being, especially at lower income levels, but its effect weakens once basic needs are met.
•	Social support is one of the strongest predictors of happiness across countries.
•	Trust in institutions and low perceived corruption are closely linked with higher life satisfaction.
•	Latin American countries often score higher than expected because of strong family networks, community ties, and social connection.
•	Some wealthy countries face declining youth well-being, suggesting that economic success does not guarantee emotional security or social belonging.
•	Happiness rankings can mask differences between overall life evaluation and everyday emotional experience.
Challenges I Faced
Data Consistency
One major challenge was that countries measure and report well-being differently. Some datasets were updated annually, while others had missing values or used different definitions of social support, health, and trust. I had to clean the data, align years, and decide how to handle missing observations.
Cultural Differences
Another challenge was interpreting self-reported happiness across cultures. People may respond differently to survey questions depending on cultural norms, language, expectations, and social pressure. For example, in some cultures, reporting very high happiness may be seen as boastful, while in others it may be more socially acceptable.
This means that a lower reported score does not always mean people are objectively less happy; it may also reflect differences in how happiness is expressed or evaluated.
Separating Correlation from Causation
I initially wanted to say that social support causes happiness. However, the relationship is more complex: happier people may also find it easier to build social relationships, and strong communities may improve both happiness and economic outcomes.
Therefore, I learned to phrase findings carefully. Instead of claiming direct causation, I focused on associations and used regression to control for several factors at once.
Explaining Youth Distress
Youth well-being was especially difficult to analyze because it is influenced by factors that are not always captured in national-level datasets, such as social media use, academic pressure, housing costs, loneliness, climate anxiety, and access to mental-health care.
This taught me that country-level averages can hide important differences within populations. A country may have a high overall happiness score while particular groups—such as young people, low-income households, or marginalized communities—experience much lower well-being.
What I Would Improve
If I continued this project, I would:
•	Use time-series data to examine whether happiness changes before or after major economic or policy changes.
•	Break results down by age group, income level, gender, and region within countries.
•	Compare life evaluations with measures of daily positive and negative emotions.
•	Include mental-health prevalence, loneliness, housing affordability, and inequality indicators.
•	Use machine-learning models to test which variables are most important for predicting happiness.
•	Conduct case studies of countries such as Finland, the United States, Costa Rica, and Mexico to understand their different well-being models.
Final Reflection
This project taught me that national happiness cannot be reduced to a single economic number. GDP is important, but people also need security, trust, health, freedom, meaningful relationships, and a sense of belonging.
The most valuable insight was that well-being is shaped by both material conditions and human connection. A country can become wealthier without becoming happier if social bonds weaken, inequality grows, or people lose trust in institutions. Understanding happiness therefore requires looking beyond economic growth and asking a more human question: Do people feel supported, safe, free, and connected in their daily lives?

