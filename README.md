# api-management

## About Dataset



## lower_upper_bound_finder:

The `lower_upper_bound_finder(column_name)` function detects and replaces outliers in a specified column of a DataFrame using the interquartile range (IQR) method. It calculates the lower bound (LB) and upper bound (UB) based on the first quartile (Q1) and third quartile (Q3) of the column, which define a range within which data points are considered non-outliers. The function prints the lower and upper bounds and returns them as a tuple.


## create_displot(column_name, title)

The `create_displot(column_name, title)` function creates a distribution plot (displot) for a specified column in a DataFrame. It calculates the mean and standard deviation of the column, identifies outliers beyond two standard deviations from the mean, replaces those outliers with the mean value, and then plots the distribution using seaborn's `displot` function with a specified title.


## top5_plot(column_name, color='pink')

The `top5_plot(column_name, color='pink')` function creates a bar plot to display the top five most frequent values in a specified column of a DataFrame. It uses the `value_counts()` function to count the occurrences of each unique value, selects the top five values, and plots them as bars. The color of the bars can be optionally specified using the `color` parameter, which defaults to 'pink'. The plot includes a title indicating the column being analyzed.


## create_pie(column_name, title)

The `create_pie(column_name, title)` function generates a pie chart to visualize the distribution of values in a specified column of a DataFrame. It uses `plt.pie()` to create the chart with values obtained from the value counts of the column. The chart includes labels, colors, and autopct for percentage display. The title is set using `plt.title()`, and the chart is displayed using `plt.show()`.


##  count_percentage_plot_by_column(column_name, given_title, color_name='aqua', vertical=True)

The ` count_percentage_plot_by_column(column_name, given_title, color_name='aqua', vertical=True)` function generates a bar plot using Plotly Express to visualize the count percentage of unique values in a specified column of a DataFrame. It calculates the count percentage for each unique value, creates a DataFrame with the values and count percentages, and plots a bar chart with either vertical or horizontal orientation based on the vertical parameter. The plot's title, color, and dimensions are customized, and the resulting plot is displayed.

## loss_money_by_provider(pname)

The `loss_money_by_provider(pname)` function calculates the total loss of money for a specific provider in the dataset. It checks if the provider name exists in the dataset, calculates the sum of "Price" values for entries with "ERROR" log level and matching provider name, and creates an Indicator chart using Plotly to display the total loss of money. The chart's title is customized with the provider name, and it is displayed.















