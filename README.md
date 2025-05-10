# Project : Steam's videogames platform

Steam is a digital distribution service and storefront for video games, developed by Valve. Launched in September 2003 as a software client to automate updates for Valve’s titles, it expanded in late 2005 to include third-party releases. Steam provides digital rights management (DRM), game server matchmaking with Valve Anti-Cheat, social networking features, and game streaming. Core client functions include automatic game updates, cloud-based progress storage, an in-game overlay, direct messaging, and a virtual marketplace for collectable items.

Project Background:
Ubisoft, a French video game publisher, has commissioned a global analysis of the Steam marketplace to gain insight into the video game ecosystem and current market trends in preparation for the launch of a groundbreaking new title.

Objectives:
The primary aim of this project is to identify the factors influencing a game’s popularity and sales. Additionally, the opportunity should be leveraged to conduct a comprehensive global market analysis. The project sponsor has provided the following illustrative questions to guide the investigation:

    Macro-Level Analysis

        Which publisher has released the greatest number of titles on Steam?

        Which games have received the highest ratings?

        How have annual release volumes varied over time, and did events such as the COVID-19 pandemic affect release counts?

        What is the distribution of price points, and how prevalent are discounted titles?

        Which languages are most commonly supported?

        How many titles carry age restrictions prohibiting players under 16 or 18?

    Genre Analysis

        Which genres are most frequently represented?

        Which genres exhibit the highest ratio of positive to negative reviews?

        Do certain publishers specialize in particular genres?

        Which genres generate the highest revenues?

    Platform Analysis

        What proportion of titles is available on Windows, macOS, and Linux?

        Are specific genres more likely to be released on particular operating systems?

These guidelines may be followed or an alternative analytical framework may be adopted, provided that the analysis yields meaningful and actionable insights.

Project Scope
Databricks and PySpark will be utilized to perform exploratory data analysis. Visualizations should be created using Databricks’ built-in tools.

The dataset is located in the following S3 bucket:

s3://full-stack-bigdata-datasets/Big_Data/Project_Steam/steam_game_output.json 

---
# Key Findings:
https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/24004397296925/3637557713592149/528102077592261/latest.html

**Top 10 publishers who released the most games on Steam**
![image](https://github.com/user-attachments/assets/8921c6e9-56e2-4057-a9e3-8612a574db50)

**Top 10 best rated games**
![image](https://github.com/user-attachments/assets/2c41300b-22a4-45bf-ab12-ba5050eaaa34)

**Steam Game Releases – Trends Over the Years**
![image](https://github.com/user-attachments/assets/67f3a226-7688-44e6-8477-d9b6939a68f0)

**Price distribution**
![image](https://github.com/user-attachments/assets/c27a7a2a-8c0e-4792-8dcf-8381621b0b40)

**Number of discounted games per year**
![image](https://github.com/user-attachments/assets/c1fb0d0e-c4bf-44f1-9425-b1b6273f343d)

**Discount percentage per year**
![image](https://github.com/user-attachments/assets/a6811bef-64e9-43b6-98c5-2d526b3f7ddc)

**Top  most represented languages**
![image](https://github.com/user-attachments/assets/45d4ad47-d418-45f3-b410-3f8f57fffd24)

**Required Age Distribution of restricted games**
![image](https://github.com/user-attachments/assets/020a5103-0ab8-4dcb-aa9b-9e657f18b24e)

**Required Age per genre**
![image](https://github.com/user-attachments/assets/1fc6172a-7880-4694-ae57-d9bc606ed189)

**Top 10 most represented genres**
![image](https://github.com/user-attachments/assets/af6a8500-4b9c-471d-9a1a-28542f0360d5)

**Top 10 genres with good average rating**
![image](https://github.com/user-attachments/assets/c898bec9-1f94-42a0-9873-69eebd716fe2)

**Top 10 genres with highest revenue**
![image](https://github.com/user-attachments/assets/58f074a4-9c4c-414c-ac48-dcf4c2bb3790)








