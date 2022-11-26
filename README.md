<h1>Football Player Predictor</h1>
<br>
<p>The problem of evaluating the performance of a football player is attracting a lot of companies and scientific communities, thanks to the availability of a massive data being generated during a match.<br>
Thus the football player rating predictor is a consolidated metric that can be used to not only provide the present but also the future potential ratings of a player.
</p>
<h3>Features:</h3>
<ul>
  <li>Football Player Predictor predicts player position and their potential and overall rating. It uses various classifier and regression models to predict player's       position, potential and overall, accurately.</li>
  <li>It uses:
    <br>
    For classifying:
    <ul>
      <li>KNN</li>
      <li>SVC</li>
      <li>Naive Bayes</li>
      <li>Decision Tree</li>
      <li>Random Forest</li>
    </ul>
    <br>
    For Regression:
    <ul>
      <li>Multiple Regression</li>
      <li>Polynomial regression</li>
      <li>SVR</li>
      <li>Decision Tree</li>
      <li>Random Forest</li>
    </ul>
    <li>Interactive Dashboar(.pbix file) for visual analysis of Player's data and to generate scouting reports</li>
</ul>
<h3>Steps:</h3>
<ul>
  <li>Clone the repository in your local device and then into your google drive, if you want to use colab, otherwise local device works well and good</li>
  <li>Run Non-Professional.ipynb</li>
  <li>You can also use your custom player ratings prediction by creating a csv fila and giving player attributes but do make sure of the dataset format</li>
</ul>
<h3>Technologies:</h3>
<ul>
  <li>Pyhton(version 2.7+)</li>
  <li>Pandas to load data frame</li>
  <li>Power BI for visualization</li>
</ul>
<h3>Dataset:</h3>
<a href="https://www.kaggle.com/datasets/stefanoleone992/fifa-20-complete-player-dataset">FIFA 20 complete player dataset</a>
<ul>
  <li>Every player available in FIFA 15, 16, 17, 18, 19, and also FIFA 20</li>
  <li>100+ attributes</li>
  <li>URL of the scraped player</li>
  <li>Player positions, with the role in the club and in the national team</li>
  <li>Player attributes with statistics as Attacking, Skills, Defense, Mentality, GK Skills, etc.</li>
  <li>Player personal data like Nationality, Club, DateOfBirth, Wage, Salary, etc.</li>
</ul>
<h3>Visualization: </h3>
<img src="https://user-images.githubusercontent.com/76468810/204091161-33213268-67b8-48c8-9654-7e446c6e5fe1.png">
<br>
<h3>Result accuracy:</h3>
<h5>Player Position</h5>
<p>Since player's actual playing position is very subjective based on team's playing style, manager's tactics,etc. it is very difficult to predict their positions accurately. Image below shows the accuracy of the results using various models.</p>
<img src="https://user-images.githubusercontent.com/76468810/204091099-3fe81ca9-e0bc-4911-8151-b3c9ba536f42.png">
<br>
<h5>Potential and Overall Rating</h5>
<p>As we can see in the below image, that Football Player Predictor predicts overall and potential rating very accurately, with polynomial regression being the most accurate (97.3% accuracy).</p>
<img src="https://user-images.githubusercontent.com/76468810/204091353-cbebeb7f-cd12-4bc9-9a0e-f6cf055f7afa.png">
