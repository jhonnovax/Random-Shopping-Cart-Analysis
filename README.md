# Random-Shopping-Cart-Analysis
Analysis based on dataset of random shopping car data

# Notebook Steps  
  * Install libraries  
  * Load dataset  
    * Source  
    * Local drive  
    * Network  
  * Data Engineering  
    * Inspect Data  
      * Summary Stats (Mean, Median, Mode, Std dev)  
    * Inspect Correlations  
      * Heatmap  
    * Distributions  
      * Histograms  
      * Box plot  
    * Remove null values  
      * Missing data (delete columns if missing data is more or equal to 40%)  
  * Feature Engineering  
    * Remove outliers  
      * Z-Score  
      * IQR  
    * Transform features  
      * SQRT transformation  
      * Log Transformation  
    * Handling the categorical values  
      * Dummy Encoder  
      * OneHot Encoder  
      * Label Encoder  
    * Choosing features  
      * Features Importance  
  * Modeling  
    * Train and test split  
      * Scaling data  
    * Apply models  
      * Clustering   
      * Basket Analysis  
        * Support: most frequent items  
          * Low \<= 0.10  
          * Medium \<= 0.39  
          * High \<= 0.79  
          * Strongest \>= 0.8  
        * Rules: Confidence items  
        * Combine them: Support, lift, confidence  
      * Regression (Linear Model \= Predict)  
      * Classification (Targat variable (A,B, C…etc) :   
  * Validations  
    * Tune the model  
    * Changing parameters

# Project Steps
* Discovery:   
  * Project Objective  
    * Improve NPV  
    * Retain Customers  
  * Project Requirements  
    * Reduce churn rate by 5%  
  * Business Problem  
* Data preparation  
  * Do I have enough good quality data to start building a model?  
* Model planning  
  * Do I have a good idea about the type of model to try? Can I refine the analytic plan?  
* Model building  
  * Is the model robust enough? Have we failed for sure?  
* Communicate results  
* Operationalize
