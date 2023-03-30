# Hoax Detection on Social Media with Convolutional Neural Network (CNN) and Support Vector Machine (SVM)

## About the Project
This is my Final Project course research for completing my bachelor study. The research is about hoax detection on social media (Twitter) with Convolutional Neural Network (CNN) dan Support Vector Machine (SVM). </br></br>
Tools: Google Spreadsheet, Google Colab, Jupyter Notebook </br>
Programming language: Python

## Dataset
The data was crawled from Twitter using Snscrape library. The research focused on two topics, i.e. Ferdy Sambo Case and Kanjuruhan Tragedy. After all data passed preprocessing, all data labelled with 0 for fact news or 1 for hoax news. Labelling was suppoerted by three person for each news to avoid subjectivity. The distribution of hoax/fact news is represented by table below.

<table>
    <thead>
        <tr>
            <th>Topic</th>
            <th>Category</th>
            <th>Number of Data</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td rowspan=2>Kanjuruhan Tragedy</td>
            <td>Fact</td>
            <td>1,279</td>
        </tr>
        <tr>
            <td>Hoax</td>
            <td>1,420</td>
        </tr>
        <tr>
            <td rowspan=2>Ferdy Sambo Case</td>
            <td>Fact</td>
            <td>11,588</td>
        </tr>
        <tr>
            <td>Hoax</td>
            <td>11,038</td>
        </tr>
        <tr>
            <td colspan=2>Total</td>
            <td>25,325</td>
        </tr>
    </tbody>
</table>

## Preprocessing Data
The table below is the preprocessing phases and its example for each phase.

<table>
    <thead>
        <tr>
            <th>Preprocessing Phase</th>
            <th>Text</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Raw Data</td>
            <td>Ratusan Orang Meninggal dalam Tragedi Kanjuruhan, Tersangkanya Hanya 6</td>
        </tr>
        <tr>
            <td>Data Cleaning</td>
            <td>Ratusan Orang Meninggal dalam Tragedi Kanjuruhan Tersangkanya Hanya</td>
        </tr>
        <tr>
            <td>Case Folding</td>
            <td>ratusan orang meninggal dalam tragedi kanjuruhan tersangkanya hanya</td>
        </tr>
        <tr>
            <td>Stopword Removal</td>
            <td>ratusan orang meninggal tragedi kanjuruhan tersangkanya</td>
        </tr>
        <tr>
            <td>Stemming</td>
            <td>ratus orang tinggal tragedi kanjuruhan sangka</td>
        </tr>
        <tr>
            <td>Tokenizing</td>
            <td>[‘ratus’, ‘orang’, ‘tinggal’, ‘tragedi’, ‘kanjuruhan’, ‘sangka’]</td>
        </tr>
    </tbody>
</table>

## Feature Extraction with TF-IDF


## Feature Expansion with GloVe


## Splitting Data
The splitting data in this research used three spliting ratios (data train : data test), i.e. 90:10, 80:20, and 70:30. The detail use is on Testing Scenario.

## Machine Learning Models

### Convolutional Neural Network (CNN)

### Support Vector Machine (SVM)


## Testing Scenario

### Scenario I: Choosing the best splitting ratio

<table>
    <thead>
        <tr>
            <th rowspan=2>Splitting ratio</th>
            <th colspan=2>Accuracy (%)</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td></td>
            <td>CNN</td>
            <td>SVM</td>
        </tr>
        <tr>
            <td><strong>90:10</strong></td>
            <td><strong>93.91</strong></td>
            <td><strong>95.52</strong></td>
        </tr>
        <tr>
            <td>80:20</td>
            <td>93.61</td>
            <td>95.25</td>
        </tr>
        <tr>
            <td>70:10</td>
            <td>93.53</td>
            <td>95.15</td>
        </tr>
    </tbody>
</table>

### Scenario II


### Scenario III

### Scenario IV

### Scenario V


## Result, Analysis, and Conclusion

