## Setup

1. Ensure you have Python installed on your system.
2. Install the required dependencies by running `pip install -r requirements.txt`.

## Running the App

To run the application:

1. Open a terminal or command prompt.
2. Navigate to the project directory.
3. Run the Streamlit app by executing `streamlit run app.py`.

## Functionality

Once the application is running:

- It calculates the Perplexity score and Burstiness score for the provided data.
- Perplexity: 
- Burstiness

Perplexity is a measure used in natural language processing to evaluate how well a probability model predicts a sample. The formula for perplexity depends on the specific model being used. In some cases, particularly when the model is unable to assign a probability to certain words or sequences, the perplexity can be calculated as infinity (inf).

The Burstiness Score measures the degree of burstiness or clustering of words in a text corpus. It is calculated using the formula:

## BurstinessScore= (Variance+Mean)/Variance−Mean
​

Where:

1.Variance is the statistical variance of the word frequencies in the text corpus.
2.Mean is the average word frequency in the text corpus.
