# Anomaly-Dectection-for-Financial-data

Dataset from Active Competition from Kaggle 
https://www.kaggle.com/competitions/anomaly-dectection-for-financial/data

![image](https://github.com/sandeep822/Anomaly-Dectection-for-Financial-data/assets/50867031/192d230c-5bbc-424d-bf8f-a3202ffc9a07)

The above plot diagram represents a series of data points plotted on a graph. The x-axis shows numerical values ranging from -0.2 to 1.0, while the y-axis displays specific categories labeled as 4.0, 3.5, 3.0, W_Avg, 2.5, 2.0, 1.5, and IRR. The plot indicates a distribution of data points across these categories, with some points clustering around certain values such as 0.0 and 0.4. The diagram provides a visual representation of the data distribution and the relative frequency of data points within each category, allowing for quick insights into the overall pattern and distribution of the dataset.

![image](https://github.com/sandeep822/Anomaly-Dectection-for-Financial-data/assets/50867031/06217e9b-6c33-4aec-8552-623e7f8b3ac0)

histogram to visualize the distribution of the 'IRR' (Internal Rate of Return) column in the cleaned DataFrame. The histogram is divided into 20 bins, providing a frequency count of IRR values within each bin. The 'kde=True' parameter overlays a kernel density estimate on top of the histogram, showing the estimated probability density function of the data. This visualization helps in understanding the distribution pattern, central tendency, and spread of the IRR values across the dataset. In the plot, the x-axis represents different IRR values, while the y-axis represents the frequency or count of occurrences of each IRR value within the dataset.


![image](https://github.com/sandeep822/Anomaly-Dectection-for-Financial-data/assets/50867031/105d3d40-9958-46e3-a1ba-909f68eaa268)

The time series analysis plots the trend of the Internal Rate of Return (IRR) over time using a line plot. The x-axis represents time, specifically the dates from January 2021 to January 2022, and the y-axis represents the corresponding IRR values. The line plot visually depicts how the IRR values fluctuate or trend over the specified time period. This type of analysis is valuable for identifying patterns, seasonality, or trends in financial data over time. In this case, it helps in understanding how the IRR values have evolved or varied across different dates, providing insights into the performance dynamics of the investments or financial metrics associated with the dataset.

![image](https://github.com/sandeep822/Anomaly-Dectection-for-Financial-data/assets/50867031/f18453a8-a1c9-4511-810e-274f2335e18b)

segment performs several analyses on a DataFrame df for a specific time period from January 1, 2021, to December 31, 2021.

First, it filters the DataFrame based on the specified time period and selects relevant columns (IRR, W_Avg, Reduction, Vision, Opt_Pw, KPIs, Bus_Int, FA_Opt, Digi_Trans, Del_Acct, Lead_Own, Lead_Own_old) for descriptive statistics and correlation analysis.

Next, it calculates descriptive statistics such as count, mean, standard deviation, minimum, quartiles, and maximum for the selected columns using the describe() method.

It also calculates the correlation matrix among these selected columns and the Anomaly_label column using the corr() method.

Finally, it visualizes the pair plot of these features colored by the Anomaly_label, where the diagonal plots are kernel density estimates (kde) of the distributions, and the off-diagonal plots show the relationships between pairs of features. This visualization is helpful in identifying any patterns or correlations between the features and how they relate to the anomaly labels.

![image](https://github.com/sandeep822/Anomaly-Dectection-for-Financial-data/assets/50867031/ff032830-1794-445e-9f25-afbbc0148c5b)

A powerful visualization for multivariate analysis. In this plot, each line represents an individual observation (or data point), and the vertical axes represent different variables (IRR, W_Avg, Vision, Opt_Pw, KPIs) plotted against these axes. The lines are color-coded based on the Anomaly_label, allowing for a quick visual comparison of how the variables relate to each other across different anomaly labels. This plot is particularly useful for identifying patterns, trends, and potential outliers in multivariate datasets, offering a comprehensive view of the data distribution and relationships.


![image](https://github.com/sandeep822/Anomaly-Dectection-for-Financial-data/assets/50867031/be1f42c2-80aa-45fc-84ef-15d5ed760e64)

pairwise scatter plot matrix with kernel density estimates, a comprehensive visualization technique for exploring relationships between multiple variables simultaneously. Each cell in the matrix represents a scatter plot between two variables, while the diagonal cells display the kernel density estimate (KDE) for each variable's distribution. The plots are color-coded based on the Anomaly_label, aiding in the visualization of how different variables vary across different anomaly labels. This visualization is valuable for identifying patterns, correlations, clusters, and outliers in the dataset, providing insights into the relationships and distributions of the variables under consideration. The KDEs on the diagonal allow for a quick assessment of the data's distributional characteristics, such as skewness and multimodality, enhancing the understanding of the data's underlying structure.




