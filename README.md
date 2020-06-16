# Utilizing_Predictive_Models_to_Analyze_Movie_Reviews

Goal:

To implement a text clustering process in order to provide wether the review of a movie is positive or negative.

Dataset:

The data set here we used for this project is a set of two thousand movie reviews. The link of the dataset is 
here: http://www.cs.cornell.edu/people/pabo/movie-review-data/. The movie reviews were classified as either positive
or negative with regard to the movie. Therefore, the data set initial dimensions were 2,000 rows by 2 columns which 
is regarded as classification and text. However, in order to more effectively train the models, the data set was divided 
into Train and Test partitions. The Train partition made up 75% of the initial data set, or 1,500 observations; the Test 
partition made up 25% of the initial data set, or 500 observations.
The data set was initially evenly divided with 1,000 positive reviews, and 1,000 negative reviews. The order of the reviews 
were randomized in order to create a more varied distribution for both the Train and Test partitions. After the partitions 
were created, the Train data contained 745 positive reviews, or 49.67% of the total Train reviews; there were 755 negative 
reviews, or 50.33% of the Train observations. The Test partition contained 255 positive reviews, or 51% of the total Test 
reviews; there were 245 negative reviews, or 49% of the train observations. Then the data set was copied, and the columns 
were swapped because the predictive models performed better when the review came before the classification in the data set.
As part of the preprocessing stage, the classification values were modified from 'Neg' and 'Pos' to 0 and 1, respectively.
