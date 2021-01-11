<h2>Welcome to my Linear Regression project!</h2>
<br>
For my project, I chose to examine Broadway musicals that have film counterparts, specifically the relationship between film performance and the average weekly gross of a Broadway show. This can include blockbuster musicals with film adaptations (Phantom Of The Opera, Mamma Mia!), stage musicals that are adapted from film (Legally Blonde, Big) or movies that became musicals that became movies once again (Footloose, Hairspray). Recorded versions of live performances (Hamilton) were not included - only adaptations. For a qualitative analysis of this project, and further insight into why data purity was a huge concern, please check out my <a href="https://towardsdatascience.com/data-purity-why-it-makes-or-breaks-a-project-3-easy-ways-to-ensure-it-a55b3e869ae0">Towards Data Science article</a>. 
<br>
<br>
In this repository, you will find three Jupyter notebooks:
<ol>
    <li>Initial_Web_Scraping - this notebook continues the scraping function that I used to scrape web data from IMDB. I began with <a href='https://www.imdb.com/search/title/?genres=musical&explore=title_type,genres&title_type=movie&ref_=adv_explore_rhs'>this page of musical movies</a> and scraped the first 10,000 results, including various quantifiable metrics of success.</li>
    <li>Table_Merge_and_Feature_Engineering - in this notebook, I merge my scraped data with existing data sets, including Broadway gross information by week for all shows since 1985. I also engineer several features, including average Broadway gross per week, amounts adjusted for inflation (using Consumer Price Index) and dummy variables for movie genre.</li>
    <li>Regularization_and_Model_Fitting - in my final notebook, I attempt to develop a predictive model to predict Broadway gross based on a movie performance. Ultimately, this was an unsuccessful model, with residuals showing a strong linear downtrend. I discuss why below.</li>
    </ol>
<h3>Conclusions:</h3>
<br>
Ultimately, this model was hindered by limited access to domestic gross and budget for older or TV movies. It led to supplementing over 300 NaN values on a dataset with less than 600 entries. I believe that with a team dedicated to data entry and factual figures, a successful model could be developed, including a further look into the relationship between stage or screen adaptations coming first. 
<br>
<h3>Datasets</h3>
<br>
For a full list of datasets and their source, please refer to the 'data' folder. 
