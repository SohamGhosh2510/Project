# TDS Project 1

- Data on users from Stockholm with over 100 followers and their repositories was scraped using Python functions in colab in the required form, into CSV files. The files were further exported and opened in MS Excel, converted into tables for filtering, sorting and analyzed in other sheets.
- An interesting and surprising fact found was that for the users, average stargazer_count for their repositories was slightly negatively correlated with the number of unique languages they used and also their number of repositories. These facts were visualized using scatterplots and then backed using linear regression analysis.
- Thus a recommendation for the developers, if they are purely aiming to maximize their average stargazer_count per repository (as a popularity metric), would be to focus their work while using only the minimal number of languages required. Also, one cannot expect more average stargazer_count with a large number of repositories.

### *Notes*

*It can be expected that using a large number of languages in their works might be seen as a sign of skill or proficiency and might lead to a greater popularity or likability. Similarly, More number of repositories might indicate more time spent on the platform, which is often accompanied by popularity. However, the results observed during the analysis vary quite a bit from the above implications.*

- Possible reasons:

*It might be that the work of users that use a lesser variety of languages appeals to a more specific audience, thus resulting in a higher popularity.*

*Also it can be that an extremely large number of repositories diverts interests or intimidates viewers away from the user themselves, regardless of code quality while a lower number of repositories is comparatively more welcoming for other viewers.*

*However, without a doubt, the individual correlations between the average stargazers_count and #repositories or #unique languages used was reasonably low.*

*Factors like code quality and presentation are intuitively more significant when it comes to popularity or likability.*
