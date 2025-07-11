# Evaluation of heart failure probabilities for Smurfs

Using a dataset containing 20+ different variables and heart scan pictures, the goal is to determine the probabilities a smurf has to develop a heart failure in the 10 upcoming years.

1. Extracting the data
2. Handling of outliers and missing values
3. Evaluation of the best variables for this task
4. Training of several machine learning models
5. Comparison/discussion of the different results

### Selection of variables

<!-- Row 1: feature‑selection images (unchanged) -->
<p align="center">
  <img src="https://github.com/user-attachments/assets/0e084837-aca3-4cbe-85c5-f44caaa085e3" width="45%" alt="features_MI" />
  <img src="https://github.com/user-attachments/assets/17819440-9993-48f1-9051-315dff3215e5" width="45%" alt="features_selected" />
</p>


### Results


<table>
  <tr>
    <td align="center" width="50%">
      <img src="https://github.com/user-attachments/assets/2586f599-f7b1-48c2-924c-1335c4c668f1" width="100%" alt="MLP_hist_new"><br>
      <sub><b>MLP</b></sub>
    </td>
    <td align="center" width="50%">
      <img src="https://github.com/user-attachments/assets/ed4b3fd1-b83a-4b3e-a85d-f8f2ae3924f6" width="100%" alt="LinReg_hist_new"><br>
      <sub><b>Linear regression</b></sub>
    </td>
  </tr>
  <tr>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/e057fc5c-96b0-47a3-a469-9fd632e16a8a" width="100%" alt="KNN_hist_new"><br>
      <sub><b>KNN</b></sub>
    </td>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/1182c58d-9edf-4bc7-ba83-3a0156883f4f" width="100%" alt="RF_hist_new"><br>
      <sub><b>Random forest</b></sub>
    </td>
  </tr>
</table>
