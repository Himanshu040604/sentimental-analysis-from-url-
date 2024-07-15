# **Sentimental Analysis from url**
This project performs sentiment analysis on text extracted from specified URLs. It evaluates the sentiment of the content and calculates various readability metrics. The results are saved in a structured format for further analysis.

**Table of Contents**

      1)Features

      2)Technologies Used

      3)Getting Started

      4)How to Use

      5)Results

**Features**

     Extracts article titles and texts from a list of URLs.

     Analyzes sentiment by counting positive and negative words.

     Computes polarity and subjectivity scores.

     Evaluates readability metrics such as average sentence length, fog index, and complex word percentage.

     Counts personal pronouns for stylistic analysis.

     Outputs results to a CSV file.
     
**Technologies Used**

    Python
    Pandas
    NLTK
    Beautiful Soup
    Requests
    Google Colab

**prerequisites**
 Install the required libraries 

     pip install requests beautifulsoup4 pandas textblob readability-lxml

**Getting Started**

    Clone the repository or download the files.

    Upload the necessary Excel files (Input.xlsx and Output Data Structure.xlsx) to your Google Drive.

    Ensure you have the required libraries installed in your Python environment. If you're using Google Colab, the necessary packages will be available by default.

## **How to Use**

1. **Set Up Your Environment**: Ensure that you have Python and the required libraries installed as mentioned in the installation instructions.

2. **Update File Paths**: Modify the file paths in the code to match your local directory structure.

3. **Run the Script**: Execute the script sequentially to:
   - Extract text from specified URLs.
   - Analyze the text for sentiment and readability metrics.
   - Save the output as a CSV file.

4. **View Output**: Once the script has completed, check the designated output directory for the generated CSV file containing the analysis results.
