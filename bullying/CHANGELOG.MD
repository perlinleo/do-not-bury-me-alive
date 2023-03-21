# [0.0.9] - 21-03-2023 13-30

## Added: 
- §1.1 Kaggle link
- §1.2 Описание
- §4.1 eliminated data gaps;
- §4.2 coded categorical features;
- §4.3 normalizated numerical attributes.
- §4.4 scaling of attributes
    - §4.4.1.minimax scaling for future ml model 
    
    ```python
    bullying_df_scaled_minimax = bullying.copy()
    ```
   
    - §4.4.2.standard scaling for future ml model

    ```python
    bullying_df_scaled_standard = bullying.copy()
    ``` 

    - §4.4.3.robust scaling for future ml model

    ```python
    bullying_df_scaled_robust = bullying.copy()
    ``` 

- §6. processing of *outliers* for numerical attributes 

    - §6.1 outliers removal
    - §6.2 outliers change
    
# [1.0.0] - 21-03-2023-14-00

## Added:

- feature selection

- processing of at least one non-standard feature (which is not numeric or categorical)

1. one method from the filter methods group (filter methods);
2. one method from the wrapper methods group (wrapper methods);
3. one method from the embedding methods group (embedded methods).