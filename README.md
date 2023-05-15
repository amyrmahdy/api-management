# api-management

## About Dataset


The dataset provided is generated using real data, ensuring its authenticity and relevance. It incorporates all existing relationships and connections between the columns, accurately representing the interactions and dependencies found in the original data. Furthermore, the dataset encompasses the complete dispersion or variability for each column, capturing the full range of values and patterns observed in the real-world data. This comprehensive representation allows for a thorough analysis and exploration of the dataset, enabling meaningful insights to be derived from the various attributes and their interplay.



Here is a detailed explanation of each column in the dataset:

- log_level: Represents the level or severity of the log message. In the sample, values include "WARNING" and "ERROR" indicating different levels of warning or error events.

- code: Indicates the specific code associated with the log event. It may represent an error code, HTTP status code, or any other relevant code. Sample values include 429, 335, 404, and 400.
 
- method: Denotes the HTTP method used in the API request. It specifies the type of action performed on the endpoint. Examples in the sample include "POST" and "GET".

- username: Refers to the username associated with the API request or operation. It identifies the user initiating the action. In the sample, values are labeled as "username_1376".

- Price: Represents the price associated with the API request or operation. It signifies the cost or monetary value related to the action. Sample values include 10, 20, and 50.

- gwStatus: Indicates the status of the gateway. It may represent the operational status or any other relevant status of the gateway system. In the sample, values are labeled as 0 (presumably indicating an inactive status).

- planName: Represents the name of the plan associated with the API request or operation. It denotes the subscription or service plan chosen for the action. Sample values include "Silver", "Bronze", and "Gold".

- received_at: Represents the timestamp indicating when the API request was received. It provides the date and time information of the request. In the sample, values are in a timestamp format.

- log_type: Specifies the type of log event. It categorizes the log entry based on its purpose or nature. Sample values include "INPUT" and "OUTPUT".

- providerName: Refers to the name of the API provider. It represents the entity or organization providing the API services. In the sample, values are labeled as "provider_186".

- gatewayName: Represents the name of the gateway associated with the API request or operation. It signifies the gateway through which the request was processed. Sample values include "gateway_657".

- response_status: Indicates the HTTP response status code associated with the API request. It represents the outcome or result of the request. Sample values include 200, 400, and 403.

- status: Denotes the status of the API request or operation. It represents the success or failure status of the action. In the sample, values are labeled as 1 or 0, indicating success or failure, respectively.

- response_Time: Represents the time taken for the API response to be processed. It measures the duration between the request and response. Sample values include 958, 576, and 342.

- paymentType: Indicates the payment type associated with the API request or operation. It denotes the method or type of payment used. Sample values include "PREPAID" and "POSTPAID".

- endpoint: Refers to the specific endpoint or URL path targeted by the API request. It represents the location or resource being accessed. Sample values include "endpoint_1201".

- providerResponse_Time: Represents the response time of the API provider. It measures the duration taken by the provider to process the request and generate a response. Sample values include 479, 288, and 197.

- gwCode: Denotes the gateway code associated with the API request or operation. It represents a specific code or identifier related to the gateway system. Sample values include







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















