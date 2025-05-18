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
[[https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/24004397296925/3637557713592149/528102077592261/latest.html](https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/24004397296925/3637557713592149/528102077592261/latest.html)](https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/24004397296925/3637557713592149/528102077592261/latest.html)

**Top 10 publishers who released the most games on Steam**
![image](https://github.com/user-attachments/assets/c2cb03b2-c3fd-492b-a0ef-96c5d349e3ac)



**Top 10 best rated games**
![image](https://github.com/user-attachments/assets/2520e22b-1a23-4398-99e2-b055aa12b65d)


**Steam Game Releases – Trends Over the Years**
![image](https://github.com/user-attachments/assets/46080839-45ff-40d2-87a9-615055ce0050)



**Price distribution**
![image](https://github.com/user-attachments/assets/e48c0416-a34a-46d6-aae3-86c7028548e7)


**Number of discounted games per year**
![image](https://github.com/user-attachments/assets/a80ef33b-98d0-452d-94b2-0270b1e718c8)



**Discount percentage per year**
![image](https://github.com/user-attachments/assets/a6811bef-64e9-43b6-98c5-2d526b3f7ddc)


**Top  most represented languages**
![image](https://github.com/user-attachments/assets/acf908ec-e79a-4afa-837f-80f95c92183a)



**Required Age Distribution of restricted games**
![image](https://github.com/user-attachments/assets/f3adf769-c94f-4f46-a8ab-515dd4537606)


**Required Age per genre**
![image](https://github.com/user-attachments/assets/8a77b4e0-5188-47cd-b2ef-22fe73dd565a)


**Top 10 most represented genres**
![image](https://github.com/user-attachments/assets/c43ed807-1001-42c1-9f21-148aff08a92d)



**Top 10 genres with good average rating**
![image](https://github.com/user-attachments/assets/0a2be534-1565-49c8-94b5-f6665f53bda1)


**Top 10 genres with highest revenue**
![image](https://github.com/user-attachments/assets/71602109-32d7-4db4-aa5f-7b453941f3c9)

**Platforms**
![image](https://github.com/user-attachments/assets/075500ca-d5be-465f-b92c-19cb57acaa08)

**Number of games in each platform**
![image](https://github.com/user-attachments/assets/fe94fa43-b120-4deb-92d8-8ab5a8e0b4fa)

![image](https://github.com/user-attachments/assets/1ad86667-2e13-472a-9fb5-f81594f5b668)





