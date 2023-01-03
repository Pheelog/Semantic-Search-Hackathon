# Semantic-Search-Hackathon
Using Cohere for Semantic Search for a AI Hackaton at [LabLab](https://lablab.ai/)

##Steps

1. Read the Multilingual Dataset, this is already in correct columns
2. Read the QA dataset, this data needs to be cleaned and seperated into seperate columns
3. Join the cleaned dataset and make the final dataset to be used for training named `finaldf.csv`
4. Train all rows from dataset using multilingual model
5. Visualize
6. For Final Training, train the model again and save it using np.save along with all columns of final dataset
7. For Production, make a class, load the model from file and use it for queries

##Running the Streamlit web app on your local machine

To do this, follow the steps below by running the given commands within a Git bash (Windows), or terminal (Mac/Linux):

 1. Ensure that you have the prerequisite Python libraries installed on your local machine:

 ```bash
 pip install -U streamlit numpy pandas scikit-learn
 ```

 2. Clone the *forked* repo to your local machine.

 ```bash
 git clone https://github.com/{your-account-name}/Semantic-Search-Hackathon.git
 ```  

 3. Navigate to the base of the cloned repo, and start the Streamlit app.

 ```bash
 cd classification-predict-streamlit-template/
 streamlit run app.py
 ```

 If the web server was able to initialise successfully, the following message should be displayed within your bash/terminal session:

```
  You can now view your Streamlit app in your browser.

    Local URL: http://localhost:8501
    Network URL: http://192.168.43.41:8501
