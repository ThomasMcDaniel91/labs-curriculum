# Module Inquiry 2

## Questions

1. What technical choices did you make today?
    * Today I made the choice to pursue a large portion of our data from a website by process
       of webscraping with beautifulsoup4.
2. Pick two technical choices you're happy with. What was your thought process as you made those choices? What did you consider and what did you decide against?
    * One technical choice I was happy with is the initial use of static data for our database.
        The DS team agreed that scraping data from  the website was a useful route to follow
        given the formatting of the website was uniform throughout all pages and the vast amount of data they had.

        We considered going the direction of a constantly updated database with interactions to different third party APIs
        but eventually decided that in order to get the project up and running sooner, we would use a static database with
        the updating database connected to APIs saved as a task for the end as a stretch goal.

    * The other technical choice I am happy with is the use of a K Nearest Neighbors model for predicting cities
        with similar attributes to the city chosen for the search.
    - Take a moment to think about the advantages in choosing the route that you did.
    - Now take a moment to consider the disadvantages.
3. In one or two sentences, summarize why you ultimately made the choice you did.
    The choices our team made were ultimately because of the facts that the webscraper is able to get us data we need in an acceptable amount of time
        and KNN model is the only choice that really makes sense for finding similar cities by the user.

4. Extracting useful conclusions from your process:
    - According to your understanding, what makes a good technical choice?
        I believe the main thing that makes a good technical choice is that it has been made after ample planning and with the pros and cons
        of the choice in mind with regards to things such as scalability, runtime, storage and whatever else is relevant to the project.