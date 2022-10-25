# Home Loan Decision Prediction
## Project description
Using the U.S. HDMA (Home Mortgage Disclosure Act), 2017 I am attempting to predict what loan status (Approved, denied by a lender, closed for incompleteness) an individual’s application would get. An individual could benefit by using this model before going to a lender to see if they will be approved. Lenders could use this model as a preliminary check to see if they should approve or deny a loan. With the given dataset I believe a data analytics approach is appropriate because this is a prediction problem that can be solved using details about the customer and lender.

For more detailed dataset information visit this link: https://www.consumerfinance.gov/data-research/hmda/historic-data/?geo=nationwide&records=all-records&field_descriptions=labels

## Get the Data

#### Option 1: Unzip zip file already in project folder
1. Unzip the hmda_2017_ca_all-records_labels.zip
2. save the csv in the same folder as this python file.

#### Option 2: Download zip file direclty from
Direct Dataset Link: https://files.consumerfinance.gov/hmda-historic-loan-data/hmda_2017_ca_all-records_labels.zip
1. Download zip file from link above
2. Unzip the hmda_2017_ca_all-records_labels.zip
3. Save the csv in the same folder as this python file.

#### Option 3: Navigate HMDA site and download file
1. Visit: https://www.consumerfinance.gov/data-research/hmda/historic-data/
2. Select California in Geographic area drop down
3. Select All records in Records included Section
4. Select Plain language labels and HMDA codes in  Variable descriptions Section
5. Click search
6. Download the csv for 2017
7. Unzip the hmda_2017_ca_all-records_labels.zip
8. Make sure file has 1,714,264 datapoints.
9. Save the csv in the same folder as this python file.


## Install Packages
Install any missing packages mentioned in the requiremets.txt file

## Run Code:
Note: Running the grid search and model training steps takes around 15 hours (on my machine atleast)

1. If the read_csv file location is different change it.
2. Then simply run all lines



#### BY: Vibhavi Peiris
