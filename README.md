installation:

pip install basicpreprocessing

basicpreprocessing library will be used to do basic preprocessing operations on dataframe


importing :
from basicpreprocessing.BasicPreprocessing import BasicPreprocessing

Please create a object with input as filepath
eg: 
BasicPreprocessing(path_of_the_file)


Methods available in this package:


create_logger(): 
    Used to create a logger named 'pre_processing_logger.log'

load_dataset(): 
    Used load the dataset
    returns dataframe object

display_sample_rows(df) : 
    Used to display the first 5 rows
    input parameter: dataframe object
    returns dataframe object

find_missing_values(df): 
    Used to find missing values in each column
    input parameter: dataframe object
    returns series object

column_data_types(df): 
    Used to find data types of columns
    input parameter: dataframe object
    returns series object

correlation_between_columns(df): 
    Used to find correlation between columns
    input parameter: dataframe object
    returns series object