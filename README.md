# U.S. Medical Insurance Costs

For this project a **CSV file** with raw data about _Medical Insurance Costs_ was provided for free analysis, based on attributes such as `age`, `sex`, `bmi`, `children`, `smoker`, `region`, and `charges`

Taking those aspects into account, i chose to go deep analyzing the following:
- which `sex` in this dataset tends to smoke more: men or women.
- which `sex`  in this dataset tends to gain more and less `BMI`.
- for men and women who are smokers, where the majority of individuals are from.
- The **average insurance cost** for men and for women in this dataset (including all ages, BMIs, and if they have children or not).
  
I have opted to make simple analyses because I could not, for example, find a _causation_ for the insurance cost based on the _correlation_ between men and women who are smokers or not. Once other important elements can influence the medical insurance cost, such as whether they have children or have higher or lower BMI values, jumping to conclusions by just analyzing the `smoker` element would skew the analysis.

To be fair, in the end, I just calculated the **average insurance cost** for men and women in this dataset with all the other elements included.

## Findings

The analysis resulted in the following findings:

- _men_ in this dataset smoke more than _women_:
  - 159 **men** are smokers
  - 115 **women** are smokers

- the _Southeast region_ have registered the higher number of smokers - 91:
  - 36 are **women**
  - 55 are **men** 

- the _median BMI value_ for each sex is:
  - `male`: 36.69
  - `female`: 30.11

- the _median insurance cost value_ for each sex is:
  - `male`: 9369.62
  - `female`: 9412.96

## Technologies used

 - Jupyter Notebook
 - Python programming language
