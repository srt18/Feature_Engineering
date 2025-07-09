![image](https://github.com/user-attachments/assets/ea4bed6f-66ec-459d-8cd5-c4a1b178df28)


# Feature_Engineering
 - Feature Transformation
 - Feature Construction
 - Feature Selection
 - Feature Extraction

## Feature Transformation 
 - Missing values imputation
 - Handling Categorical Features
 - Outlier Detection
 - Feature Scaling

    1. Missing Values Imputation
        - SciktLearn don't expect missing values
        - Either we need fill or replace or remove
    
    2. Handling Categorical Features
        - SciktLearn handle numerical values
            For ex.:- Dog - 0, Cat - 1 (One-Hot Encoding)
    
    3. Outlier Detection
        - Removal of outlier makes linear best fit line function accurately

    4. Feature Scaling
        - Feature Scaling according range scale (-1 to 1)

## Feature Scaling
    - The technique to standardization the independent feature present in datain fixed range.

    Why do we need this?
    Example - KNN --> Independent variable have different scale not as per the model

### Types of Feature Scaling
    1. Standarization (Z-score Normalization) 
    2. Normalization 
        - MinMax Scaler
        - Robust Scaler

#### 1. Standardization (Z-score Normalization)

![alt text](image-1.png)

    Z-Score = (Current_value - Mean) / Standard Deviation

    Standard Deviation > 1 - Squeenze
    Standard Deviation ~ 1 - Expand
