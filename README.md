<h3>Visualising data with cutecharts library</h3>
<hr>

<p>Utilizing <a href="https://github.com/cutecharts/cutecharts.py">cutecharts</a> to visualize data from <a href="https://www.kaggle.com/thomaskonstantin/highly-rated-children-books-and-stories"> Kaggle</a>.</p>
<p>There are 2 datasets, both containing the Book title, description and suitable age group. I want to use the visuals to answer the following:</p>
<ul>
  <li>What are the popular words used in the description overall?</li>
  <li>What are the popular words used in each age categories?</li>
  <li>Are the popular words the same throughout each age categories?</li>
  <li>Which age categories have the most stories written?</li>
</ul>  
<p>The dataset will then be put through a text classiciation model using Python SkLearn.</p>

<p>In order to answer those questions, the datasets needed to be prepped so the data can be better visualised.
Upon exploring the datasets, there are a lot of texts. Despite having 3269 records in the <a href="https://github.com/foofx88/story_time_with_FX/blob/main/datasets/children_books.csv">children books dataset</a>, there are only 39 unique books after removing duplicates and null values. This will then be used for test data for the text classification model.</p>
<img src="https://github.com/foofx88/story_time_with_FX/blob/main/images/duplicated_title.PNG" width="80%">

<p>Moving on to the <a href="https://github.com/foofx88/story_time_with_FX/blob/main/datasets/children_stories.csv">children stories dataset</a>, there are 393 unique books out of 430 after cleaning the data. I have identified that there are a few duplicated story names with different description but there are a number of duplicated descriptions with different categories ("cats" column). The "cats" column was also in a mess, with more than 59 unique values. <img src="https://github.com/foofx88/story_time_with_FX/blob/main/images/unique_cats.PNG" width="80%"> <br>
As there are some age gaps in between, I will take account of the start age and reference to this <a href="https://www.healthychildren.org/English/ages-stages/Pages/default.aspx">guide</a>. <br> 
My Stages column would look like: 
<ul>
  <li>Toddler: 0-3 years</li> 
  <li>Preschool: 3-5 years</li> 
  <li>Gradeschooler: 5-12 years</li> 
  <li>Teen: 12-18 years</li></ul> </p>


<a href="https://foofx88.github.io/story_time_with_FX/">Explore the charts</a>
<h3>Still in Progress, please check back later. Thank you</h3>
