# Toronto House Price Analysis

![pexels-ennvisionn-1868676](https://github.com/nwyGit/Python-Toronto-Housing-Analysis/assets/105307947/845f7632-8757-4b5a-8e3a-8904290d4af3)


This project involves web scraping and data analysis using Python to gain insights into the Toronto housing market. The target site for data collection is zillow.com. 

## Project Overview

In this project, we will scrape data from zillow.com and perform data analysis to understand the housing market trends in Toronto. The analysis will involve visualizing price distributions, correlations between prices and property features, and identifying areas with higher property prices.

## Getting Started

To start working on this project, follow these steps:

1. Clone this repository to your local machine.
2. Install the required libraries using `pip install -r requirements.txt`.
3. Run the web scraping script to collect data from zillow.com.
4. Load the collected data into your preferred data analysis environment (e.g., Jupyter Notebook).
5. Explore the dataset's columns, data types, and structure to understand the available information.

## Analysis and Insights

### Price Distribution by Bedroom Count

![Price Distribution by Bedroom Count](https://github.com/nwyGit/Python-Toronto-Housing-Analysis/assets/105307947/80fb74d3-7cfb-41db-9795-c416346f63ab)


The histogram portrays a housing market where the bulk of properties are priced below 1 million dollars, emphasizing the prominent emphasis on affordability in property pricing. These insights can prove invaluable for both prospective homebuyers and real estate professionals seeking to understand the distribution of prices within the market.

### Price by Road Type: Violin Plot

![Price by Road Type - Violin Plot](https://github.com/nwyGit/Python-Toronto-Housing-Analysis/assets/105307947/6a316626-2f83-4620-ac2d-d4e6c346e4d0)


In the violin plot analysis of price variation by address type, we observe that the lower quartiles of most address types are quite consistent, indicating similar starting price points. However, significant distinctions arise in the upper quartiles, with "avenue" and "drive" displaying notably higher values among all the road types. Notably, the upper quartile of "drive" exceeds that of "avenue," suggesting a higher upper price range for properties located on "drive" streets. Although outliers are evident in the "street," "avenue," and "road" categories, the "drive" type consistently stands out with comparatively higher prices. These observations could potentially be attributed to factors such as location, property size, local amenities, or desirability, which contribute to the varying pricing trends across different address types.

### Top 5 Areas by Forward Sortation Area

![Top 5 Areas by Forward Sortation Area](https://github.com/nwyGit/Python-Toronto-Housing-Analysis/assets/105307947/022ba87e-1d47-47a8-a6eb-0efaf3a32aa9)


The analysis has divulged intriguing insights, highlighting the top 5 areas with the most elevated average prices: M4N, M4W, M5R, M2P, M5M. To provide a deeper understanding, let's delve into each area along with specific examples:

- M4N: The presence of elevated average prices in this area could be exemplified by exclusive attributes such as proximity to renowned private schools, tree-lined streets, and historic architecture.
- M4W: The higher average prices in M4W could be attributed to its central downtown location, offering luxurious penthouses with stunning skyline views and convenient access to cultural hubs.
- M5R: M5R's elevated average prices may stem from its Victorian-era charm, cultural venues, and trendy boutiques. Victorian-style townhouses and restored heritage homes could contribute to the higher property values.
- M2P: The M2P area commands premium prices for its spacious properties on large lots. Luxurious finishes and proximity to esteemed golf clubs enhance its allure, creating an exclusive and leisurely environment.
- M5M: Known for upscale living and convenience, M5M sustains its premium prices. It offers a diverse array of high-end properties, from elegant homes to sophisticated condos. Well-regarded schools, chic shopping, and recreational spaces amplify its desirability for discerning home seekers.

These observations collectively suggest that the identified areas command higher prices due to their unique attributes, which cater to specific preferences and lifestyles. The discerned patterns offer valuable insights for real estate stakeholders, aiding in investment decisions, market analysis, and comprehending the drivers behind property valuation in these distinct locales.

### Price Correlation with Bedroom and Bathroom Counts: Scatter Plot Matrix

![Price Correlation with Bedroom and Bathroom Counts - Scatter Plot Matrix](https://github.com/nwyGit/Python-Toronto-Housing-Analysis/assets/105307947/82634fb9-32d9-4149-b01b-9c4eac5958aa)


This scatter plot matrix will display scatter plots for each combination of the variables (Price, Bedroom, and Bathroom), allowing us to visually inspect potential correlations.

### Scatter Plot of Price vs Bedroom and Bathroom Counts

![Scatter Plot of Price vs Bedroom and Bathroom Counts](https://github.com/nwyGit/Python-Toronto-Housing-Analysis/assets/105307947/3493dfe4-7758-4404-ba0d-b3883937ba79)


Both graphs showcase positive correlations between property prices and bedroom/bathroom counts. The steeper slope in the bathroom graph indicates that bathrooms might have a slightly stronger influence on property prices than bedrooms, possibly due to the luxury and convenience they provide. These insights can be invaluable for real estate market analysis, guiding buyers, sellers, and investors in understanding the factors influencing property values.

## Conclusion

![pexels-binyamin-mellish-186077](https://github.com/nwyGit/Python-Toronto-Housing-Analysis/assets/105307947/0237fc31-5a18-4c5c-9ec2-c4c7876459e3)


Through a comprehensive analysis of Toronto's housing market, this project reveals key insights. The market emphasizes affordability, with a majority of properties priced below 1 million dollars. Road types exhibit diverse pricing trends, driven by factors like location and desirability. Specific premium areas command higher prices due to unique attributes, aiding investment decisions. Bedrooms and bathrooms positively impact property values, with bathrooms showing a slightly stronger influence. These findings collectively provide a valuable resource for understanding and navigating Toronto's dynamic real estate landscape.

## Contributing

Contributions to this project are welcome! If you have suggestions for additional analyses, improvements to the code, or new visualizations, please submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

## Contact

For any questions or suggestions related to this project, you can reach out to [me](mailto:nwyraymond@gmail.com).
