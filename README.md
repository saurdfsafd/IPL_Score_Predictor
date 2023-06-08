<h1>IPL Score Predictor</h1>
This Streamlit webapp enables user to predict total runs between teams using current runs and wickets.
<br>
<br>
<b>Algorithms used:
<li>Linear Regression</li>
<li>K-Nearest Neighbor Regressor</li>
<li>XGBoost Regressor</li>
<li>RandomForest Regressor</li>
<li>SVM</li>
<li>Decision Tree Regressor</li>
<br>
<br>
<b>Hyperparamter Optimization:<br>
  <br>
  Used optuna for paramter optimization.<br><br>
<b>Dataset:<br>
<br>
The dataset comprises of over by over details of matches and runs from 2008 to 2020.
  <br>
<br>Dataset Used: ipl_data.csv
<li>mid - match id</li>
<li>date - when matches are played</li>
<li>venue - place where matches aew played</li>
<li>bat_team - batting team</li>
<li>bowl_team - bowling team</li>
<li>batsman - batsman</li>
<li>bowler - bowler</li>
<li>runs - runs scored</li>
<li>wickets - wickets</li>
<li>overs - overs - next 3 are based on this</li>
<li>run_last_5 - runs scored in last 5 overs</li>
<li>wicket_last_5 - wickets in last 5 overs</li>
<li>stricker - batsman playing as main 1</li>
<li>non-striker - batsman playing as runner up - not main 0</li>
<li>total - total score (target variable)</li>
  
  
