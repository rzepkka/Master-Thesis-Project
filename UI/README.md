# Master Thesis Project

### Environment recommendation: 
- Python == 3.9
- R == 4.2 (or earlier version with working Biobase package)

## HOW-TO run the Streamlit App

1. Clone this repository
2. Create new conda environment

>> conda create -n env_name

3. Install requirements.txt

>> pip install -r requirements.txt

4. Install Snowphlake (it is a private github repository, access permission is needed)
5. Within R, install NMF, ggseg3d, htmlwidgets and Biobase 

>> install.packages('NMF')

>> install.packages('ggseg3d')

>> install.packages('htmlwidgets')

>> if (!require("BiocManager", quietly = TRUE))

>> install.packages("BiocManager")

>> BiocManager::install("Biobase")

6. Pass your data by editing *input_data.py* file. Required inputs:
- pickle file with Snowphlake outputs
- csv with patients' data
- JSON mapping files for brain regions
- disease name
- a list of subtype names

7. Run the setup file from command line:

>> python app_setup.py

8. Wait 2-3 minutes before Streamlit App is ready. You can track the progress in the cmd/terminal. 

9. Run Streamlit App from command line:

>> streamlit run app.py

