 
# accounting fraud model selection
## Project Order


* Order: 
    * `model_experiment`
    * `RUSBoost_experiments`
    * `AutoML`
    * `XGBoost`
    * `anomaly_detection`
    * `conversion from non-image to image data`

## Project Structure
* Folders
    * `Dataset`: Contains all types of datasets.
        * `columns.docx`: Information regarding columns used in different datasets.
        * `ricardo_ratios.csv`: Ratios suggested by Ricardo.
        * `uni_fraud.csv`: Cleaned Raw university dataset.
        * `uni_ratios_fraud.csv`: Cecchini over 'sale' and 'at' ratios.
    * `TPOT output`: Outputs of TPOT library.
    * `RUSBoost`:
        * `RUSBoost.py`: Python implementation of RUSBoost.
    * `RUSBoost`:             
* Jupyter Notebooks:
    * `AutoML`: AutoML was used to find an optimal model for our dataset.
    * `RUSBoost_experiments`: Experiments were conducted on RUSBoost model to find its generalization and the impact of randomizing distribution of training and test data.
    * `XGBoost`: XGBoost is one of the leading ML model, so it seemed only fair to perform experiment on it.
    * `model_experiment`: Experiments were conducted to find an optimal machine learning model.
    * `anomaly_detection`: Experiments to find distribution of fraud and non fraud data. Moreover, we worked on this case as anomaly detection and how clustering provides the corresponding results.
    * `conversion from non-image to image data`: Explored different scaling methods along with that implemented different research papers for non image data to image conversion.
