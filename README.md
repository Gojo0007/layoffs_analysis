# layoffs_analysis
  Here we will see the layoffs by the companies all over the world from the last 2 years.
  
  ## Creating a table:
     I created a table in pgadmin(postgresql), then i imported the csv file from kaggle dataset of layoffs.
     
  ## Cleaning the database:
     * Removing the null values.
     * Deleting the duplicates.
     * Adding a month column for making analysis easy.
     
  ## EDA Analysis
     We calculated the following:
     *Industry with the most number of layoffs.
     *Most affected country.
     *Companies with the maximum numbers of layoffs.
     * Most affected Cities in the top affected countries.
     * How the stage of the company affected the layoff.
     
     For SQL Queries checkout the layoff_sql file.
     
  ## Visualisations:
     Check out my Tableau profile for visuals here: [Tableau](https://public.tableau.com/app/profile/shubham.saini1159/viz/layoffvisuals/Dashboard1)
  
  ## CONCLUSION
     *We see that consumer industry is most affected followed by transportation and retail respectively.
     *USA is the most affected country followed by India and Brazil respectively.
     *This shows us that Meta company of consumer industry did the maximum number of layoffs followed by Amazon(Retail) and Uber(Transportation).
     *SF Bay Area and New York are the most affected cities in USA,followed by Banglore in India.
     *Companies at the SEED stage have the least number of layoffs while Companies at IPO stage has the most number of layoffs.
     *It is interesting to see that as maximum number of workforce laid off is from CONSUMER industry while the Maximum percent of workforce laid off is by FINANCE industry.
     *We can see that the month of november has the maximum number of layoffs.
     *Through Visuals we can conclude that companies with more fund raised have less layoffs. 
