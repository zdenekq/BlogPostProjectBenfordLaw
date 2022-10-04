# BlogPostprojectBenfordLawFrom Wikidata

Blog can be found here:
https://zdenekq.blogspot.com/2022/09/benfordlaw .html


Used libraries:

#import libraries
import pandas as pd
import numpy as np
import math

from collections import defaultdict

import sys
import math
import matplotlib.pyplot as plt
%matplotlib inline

from SPARQLWrapper import SPARQLWrapper, JSON
from SPARQLWrapper import SPARQLWrapper2







1. Business Understanding - This means understanding the problem and questions we are interested in tackling in the context of whatever domain we're working in.

My motivation has been to learn how to 

a) reuse wikipedia data and learn about wikidata and query language sparql
b) check wikipedia data quality
c) pass Udacity blog project requirements
d) Learn about Benford law and show, that this law can be applied in practice






2. Data Understanding - At this step, we need to move the questions from Business Understanding to data. We might already have data that could be used to answer the questions, or we might have to collect data to get at our questions of interest.

a) reuse wikipedia data
 aa) wikipedia presentation is based on wikidata https://www.wikidata.org/wiki/Wikidata:Main_Page  graph model, which allows to query through special wikidata sparql https://query.wikidata.org/. 

 ab)I was looking for some complete dataset of numeric data and I have found , that population by state and city population are rather complete and of good quality. I expected potentionaly differencs based on continents, so I included this data segmentation. 



3. The files in the repository:
   a) The jupyter notebeook file Population.ipynb contains code
   b) The file wikidata_population. csv containes the following columns from wikidata:
    country	continent	totalCityPopulation	population	ratio


4. Summary:
   We were able to query data at wikidata for country population and we were able to prove, that these data behaves accordint to Benford's law prediction

5. Acknowledgement: I would like to acknowlwdge explanation of Benford law by Mr. Rokyta and Mr. Valášek: https://www.youtube.com/watch?v=2wZslU6P94o


README.md file that communicates the libraries used, the motivation for the project, the files in the repository with a small description of each, a summary of the results of the analysis, and necessary acknowledgements. 