                                                                                                                Text Analysis ( Web Scraping ) 

I first saved the URL and URL ID in Excel format and then imported them using pandas.

After importing, I had a problem that I will do Text Analysis and compute variables and after computing, I will create a Dataframe and save these values ​​in Excel format, but how will I know which URL's values ​​are there in that particular Row?

That's why I also saved the URL ID of every website.

Now I converted both the columns URL ID and URL into one list so that I can use them in one loop and calculate the variables.

After that I defined a function using beautiful soup and different libraries for text analysis.

I saved the extracted text in my directory.

Then I defined another function to compute variables like positive score, negative score, polarity score, average sentence length, etc.

I again faced another problem: In Text Analysis, the variables which I am computing are saving them in a dictionary format in each row of the column.

I have the dictionary format data in the first row of our column and I have the key name in which I created the column and stored the values ​​in each column.

I also defined a function for that and converted those column values ​​into dictionary format values ​​and then passed them into this function.

But at that time also another problem was found that the data in each row was shown in dictionary format when printed but actually it was in string (dictionary data) format.

Therefore, to overcome this problem, I again use a for loop in the uss column, which removes the rows in my main string format and just keeps them in dictionary format and then converts them into list and then passes them to the uss function and then my project is complete.

hogaya finally.

Then finally I have saved our Dataframe in Excel format and saved it in my directory.

Whenever I need to calculate anything in an article from any URL, I pass that URL to my code and get the final output.

Last point - By doing this project I got to learn a lot and I learned different ways to deal with problems.
