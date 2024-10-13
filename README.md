## Project "FakeNews Detection"

This project is part of my Udacity´s Data Scientist Nanodegree Program. 

### Table of Contents
 
1. [Project Motivation](#motivation)
2. [Data](#data)
3. [Files](#files)
4. [Libraries](#libraries)
5. [Results](#results)
6. [Licensing](#licensing)

## Project Motivation <a name="motivation"></a>

The CapStone project is one of the projects within the Udacity Data Scientist Nanodegree Program. In an era where information spreads rapidly, the ability to distinguish between fact and fiction is crucial for an informed society. The project "Fake News Detection" aims to develop tools that help users separate credible content from misleading information, thereby promoting responsible engagement with information. The WELFake dataset was chosen as the data basis.

## Data <a name="data"></a>

The WELFake dataset contains of 72k news articles with 35k real and 37k fake news. For a larger data base and to avoid overfitting of the models, four popular news datasets were merged. The focus is on developing algorithms to distinguish between real and fake news. The dataset contains four columns: serial number (starting from 0); title (news heading); text (news content); and label (0 = real and 1 = fake).</br>

Further information about the original dataset can be found [here](https://zenodo.org/records/4561253)

## Files <a name="files"></a>

The following files are provided within this project:
<ul>
  <li><b>FAKENews.ipynb:</b> Jupyter Notebook containing the Python code for the analysis</li>
  <li><b>README.md:</b> This file</li>
</ul>

## Libraries <a name="libraries"></a>

I created a Jupyter notebook (Python) for the data analysis. For this I used the integrated workspaces from Udacity. The ipynb file should run on any Python 3 version (3.0.* or higher) without any problems.</br>

Here are the additional Python libraries used within this project:
<ul>
  <li>numpy</li>
  <li>pandas</li>
  <li>matplotlib.PyPlot</li>
  <li>seaborn</li>
  <li>sklearn</li>
  <li>nltk</li>
</ul>

You will need to download the WELFake dataset and put it in your folder. [Here](https://zenodo.org/records/4561253) you can find the data. </br>

## Results <a name="results"></a>

The aim of the analysis was to find out whether machine learning algorithms and natural language processing can be used to distinguish/classify real articles from fake articles. The results can be found on my GitHub [Blog](https://techdataman.github.io/2024/10/11/blog-post-second.html).

## Licensing <a name="licensing"></a>

Thanks to XXX for providing the data.
