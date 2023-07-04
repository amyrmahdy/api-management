# API Management 

## Introduction:
The API management dataset is a log of providers, endpoints, and consumers that are part of an API management system. When a consumer uses a provider endpoint through API management, this dataset logs information about the transaction, including response time, method, gateway type, and payment type. This dataset contains approximately one million transactions between different providers and consumers.

The dataset provided is generated using real data, ensuring its authenticity and relevance. It incorporates all existing relationships and connections between the columns, accurately representing the interactions and dependencies found in the original data. Furthermore, the dataset encompasses the complete dispersion or variability for each column, capturing the full range of values and patterns observed in the real-world data. This comprehensive representation allows for a thorough analysis and exploration of the dataset, enabling meaningful insights to be derived from the various attributes and their interplay.

Here is a detailed explanation of each column in the dataset:

log_level: Represents the level or severity of the log message. In the sample, values include "WARNING" and "ERROR" indicating different levels of warning or error events.

code: Indicates the specific code associated with the log event. It may represent an error code, HTTP status code, or any other relevant code. Sample values include 429, 335, 404, and 400.

method: Denotes the HTTP method used in the API request. It specifies the type of action performed on the endpoint. Examples in the sample include "POST" and "GET".

username: Refers to the username associated with the API request or operation. It identifies the user initiating the action. In the sample, values are labeled as "username_1376".

Price: Represents the price associated with the API request or operation. It signifies the cost or monetary value related to the action. Sample values include 10, 20, and 50.

gwStatus: Indicates the status of the gateway. It may represent the operational status or any other relevant status of the gateway system. In the sample, values are labeled as 0 (presumably indicating an inactive status).

planName: Represents the name of the plan associated with the API request or operation. It denotes the subscription or service plan chosen for the action. Sample values include "Silver", "Bronze", and "Gold".

received_at: Represents the timestamp indicating when the API request was received. It provides the date and time information of the request. In the sample, values are in a timestamp format.

log_type: Specifies the type of log event. It categorizes the log entry based on its purpose or nature. Sample values include "INPUT" and "OUTPUT".

providerName: Refers to the name of the API provider. It represents the entity or organization providing the API services. In the sample, values are labeled as "provider_186".

gatewayName: Represents the name of the gateway associated with the API request or operation. It signifies the gateway through which the request was processed. Sample values include "gateway_657".

response_status: Indicates the HTTP response status code associated with the API request. It represents the outcome or result of the request. Sample values include 200, 400, and 403.

status: Denotes the status of the API request or operation. It represents the success or failure status of the action. In the sample, values are labeled as 1 or 0, indicating success or failure, respectively.

response_Time: Represents the time taken for the API response to be processed. It measures the duration between the request and response. Sample values include 958, 576, and 342.

paymentType: Indicates the payment type associated with the API request or operation. It denotes the method or type of payment used. Sample values include "PREPAID" and "POSTPAID".

endpoint: Refers to the specific endpoint or URL path targeted by the API request. It represents the location or resource being accessed. Sample values include "endpoint_1201".

providerResponse_Time: Represents the response time of the API provider. It measures the duration taken by the provider to process the request and generate a response. Sample values include 479, 288, and 197.

gwCode: Denotes the gateway code associated with the API request or operation. It represents a specific code or identifier related to the gateway system. Sample values include

The goal of this project is to analyze an API management dataset to gain insights into API usage and performance within an organization. The dataset consists of various columns such as log_level, code, method, username, Price, gwStatus, planName, received_at, log_type, providerName, gatewayName, response_status, status, response_Time, paymentType, endpoint, providerResponse_Time, gwCode, call_type, and api_type.

The project is divided into three main phases: data cleaning, exploration, and feature engineering. During the data cleaning phase, various data quality issues is addressed, such as missing values, duplicates, and outliers. In the exploration phase, the cleaned dataset is visualized and analyzed to gain insights into the distribution of the data and identify any patterns or trends. Finally, in the feature engineering phase, new features are created to help improve the accuracy of the analysis.

By completing these phases, the project aim to provide valuable insights into API usage and performance, which could help inform decision-making within the organization. The project is a critical step towards understanding and optimizing the organization's API management strategy.
