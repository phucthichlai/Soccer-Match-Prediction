# <h1 align="center">:game_die: :soccer: Goal Scoring And Win Probability Prediction :soccer: :game_die: <img src="https://github.com/PrinceCorwin/Useful-tech-icons/blob/main/images/python.png" width="50" height="50"></h1>

## **1. Introduction** :pushpin:
<ul>
<li><strong>Objective:</strong> The upcoming match between UAE (home team) and Thailand (away team) will be hold on March 28th. This project aims to utilize Machine Learning to predict 2 specific questions given a dataset of performance history and team status:</li>
<br>
<ul>
<li>The number of goals scored in the match.</li> 
<li>The win probability of UAE and Thailand.</li>
</ul>
<br>
<li><strong>Target Audiences:</strong> Soccer club manager, coaches, trainers and relevant stakeholders.</li>
</ul>

## **2. Methodology**:microscope:

- **Data Source:** Private information provided by <a href="https://www.linkedin.com/company/caspo-one/?trk=public_profile_experience-item_profile-section-card_image-click&originalSubdomain=ph">Caspo Ltd</a> - an Online Gambling company.
- **Prediction method:**<br>
++ Linear and Polynomial Regression Model.<br>
++ Random Forest Regression Model and Parameter Tuning.

## **3. Findings Summary** :bulb:

<h3>Question 1:</h3>

- Only <strong>"rating_diff"</strong> has a considerable relationship with target <strong>goal_score</strong>.

<img width="602" alt="Ảnh chụp Màn hình 2023-03-27 lúc 01 00 12" src="https://user-images.githubusercontent.com/104643138/227791792-3b687147-11f2-443d-a8c2-2f42f86a7f2d.png">

<img width="602" alt="Ảnh chụp Màn hình 2023-03-27 lúc 00 56 34" src="https://user-images.githubusercontent.com/104643138/227791619-bc657e5c-7e79-4556-a5e9-8ffbf34dd251.png">

- The function for predicting a team s goal is:
                       
goal_score = 8.77e-10 x^3 + 2.079e-06 x^2 + 0.002308 x + 1.15

where x = rating_diff

- Answer:
<h4>In the next football match, UAE will score ~1.59 and Thailand will score ~0.82 goal.</h4>

<h3>Question 2:</h3>

<img width="659" alt="Ảnh chụp Màn hình 2023-03-27 lúc 01 37 12" src="https://user-images.githubusercontent.com/104643138/227793801-4cc78cf0-bf6f-4934-b4dc-b1a540e60574.png">

We've found out the best parameters as above for the Random Forest Regression model, with accuracy score ~ 56.35%. 

- Answer:
<h4>In the next football match vs Thailand, UAE will have ~58.09% WIN, ~23.50% DRAW, and ~18.41% LOSE.</h4>

For more detail, please visit my code for <a href="https://github.com/phucthichlai/Soccer-Match-Prediction/blob/main/Goal%20Prediction%20(question%201).ipynb">question 1</a> and <a href="https://github.com/phucthichlai/Soccer-Match-Prediction/blob/main/Win%20Probability%20(question%202).ipynb">question 2</a>.

## 4. Technologies used ⚙️:satellite:
- [Python](https://coursera.org/share/9633cd154ac74544f87f83434258a90b) <img src="https://github.com/PrinceCorwin/Useful-tech-icons/blob/main/images/python.png" width="24" height="24">
- [Statistics](https://www.sagepub.com/sites/default/files/upm-binaries/33663_Chapter4.pdf) :bar_chart:
- [Jupyter Notebook](https://jupyter.org/) <img src="https://user-images.githubusercontent.com/104643138/226098051-177ede6d-3fe5-49a8-8f57-446caf49f94c.png" width="24" height="24">
- Python Libraries: [Pandas](https://pandas.pydata.org/) <img src="https://user-images.githubusercontent.com/104643138/225993416-31cf4034-962c-4842-8821-5a5ccfc8e729.png" width="24" height="24"/> | [NumPy](https://numpy.org/) <img src="https://user-images.githubusercontent.com/104643138/225993758-e1b3af8b-47a0-405d-90ff-b2edeeac3d37.png" width="24" height="24"/> | [Matplotlib](https://matplotlib.org/) <img src="https://user-images.githubusercontent.com/104643138/225994026-078da32e-a169-4f83-9fa4-fc0d00c911c1.png" width="24" height="24"/>
| [Seaborn](https://seaborn.pydata.org/) <img src="https://user-images.githubusercontent.com/104643138/225994199-d9f150a0-27b6-44bc-a581-2e21d7d0e9af.svg" width="24" height="24"/> | [Scikit-learn](https://scikit-learn.org/)<img src="https://user-images.githubusercontent.com/104643138/226148658-1612b9c8-9995-41ec-b3ce-5864f39b61d9.jpeg" width="24" height="24"/>

## You can reach me at 👇
<img href="https://www.facebook.com/dobaophuc98/" src="https://img.shields.io/badge/Facebook-@dobaophuc98-1877F2?style=for-the-badge&logo=Facebook"/>
<img href="https://www.linkedin.com/in/andy-data-analyst/" src="https://img.shields.io/badge/LinkedIn-@Andy_data_analyst-0A66C2?style=for-the-badge&logo=LinkedIn"/>
<img src="https://img.shields.io/badge/Gmail-dobaophuc1998@gmail.com-EA4335?style=for-the-badge&logo=Gmail"/>
