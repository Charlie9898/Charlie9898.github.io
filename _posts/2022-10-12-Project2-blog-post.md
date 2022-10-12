1. Explain what you did in the project and any interesting findings

I created the repository in my Github site, helped with my partner to connect to the repo. I developed the functions to grab data from the API, called the functions to extract original numerical and catagorical data, and created the contingency tables with the categorical data as part of the EDA. Finally, I drafted the framework of our vignette, write down the background information and requirement, as well as the context explaining the effort I contributed. 

Some interesting findings are: (1) the parameters of the API does not need to follow a fixed sequence, it is just like function call. I thought the eventual link is just like a URL, you have to ensure every character is in the fixed sequence to get the webpage. (2) Even we force the returned data to be a dataframe, some sub-level data type can be stored in the returned dataframe. For example, the keywords of a news (a vector) can be saved as a cell in a two-dimensional dataframe.


2. Reflect on the process you went through for this project. Discuss things like:
– what was the most difficult part of the logic and programming for you?

Understanding the returned data of the API is quite hard, so it took me some time to understand the data structure and clean up the returned data before running the EDA.


– what would you do differently in approaching a similar project in the future?

I should discuss with my partner about everything we find regarding the API, the initial plan for the EDA, and the expected returned data form API before writting the functions to grab the data. I tried my best to extract suitable data from the API for the EDA, but there still were some issues for us to digest the data and summarize some meaningful findings from the EDA.
