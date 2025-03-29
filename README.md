# Extra-Trees Regressor Model for Predicting the Magnetic Moments of Transition Metal Borides

In this project, the development of an extra-trees regressor (ETR) model trained to predict the magnetic moments of intermetallic compounds with the goal of guiding experimental chemists and speed up the discovery of novel rare earth free (REF) permanent magnets as part of Johan's doctoral thesis. An XGBoost, SNN, and FNN models were also developed by our collaborator Andrew Krikorian available [here](https://github.com/andykr1k/ChemML).

![image](https://github.com/user-attachments/assets/e71bd4e3-fb66-4e7a-a951-ed0252eba9cd)

**Figure 1.** (Top) ETR linear regression result on the hold-out test dataset with a correlation coefficient of 0.8524 and (bottom) residuals plot.

From this study we predict the magnetic moments of over 288 never before synthesized intermetallic borides in the Ti<sub>3</sub>Co<sub>5</sub>B<sub>2</sub> structure type which is a well studied composition for REF magnets especially in literature.

Another important result from these studies from regression analysis of the model was that we were able to determine most important features of ferromagnetic intermetallic compounds and quantify the magnitude in determining the magnetic moments of these compounds such as through SHAP value analysis seen in **Figure 2.**. This is important because it gives further insight chemists can use to guide their work in synthesizing magnetic intermetallic compounds.

![image](https://github.com/user-attachments/assets/8f02bdae-f46b-4537-84e7-688adfadc08c)

**Figure 2.** SHAP Beeswarm plot for XGB model on the hold-out test dataset arranged from highest to lowest mean absolute SHAP values (top 20). 

## 1) Cloning the Repository

To clone the **MagnBorides** repository, use the following command:

```sh
git clone https://github.com/johan-yapo/MagnBorides.git
```



