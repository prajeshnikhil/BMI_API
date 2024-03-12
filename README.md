# BMI_API
A simple API designed to calculate BMI based on weight and height. The API provides a straightforward means to compute BMI and offers interpretations regarding the calculated value, categorizing individuals into underweight, normal weight, or overweight categories.

# Features:

Computes BMI based on weight and height inputs.
Provides interpretations regarding the calculated BMI, categorizing individuals into underweight, normal weight, or overweight categories.
Base URL:
The base URL for accessing the API is: https://dm3y42j2bl.execute-api.eu-west-1.amazonaws.com/dev/bmi?weight=70&height=170

# Authentication:
Currently, the API does not require any form of authentication.

# Endpoints:

GET /bmi: Computes the BMI based on weight and height parameters provided as query string parameters. Returns a JSON response containing the calculated BMI and its interpretation.
Response Format:
The response format for successful requests is JSON. Below is an example of a successful response for the GET /bmi endpoint:

{
  "bmi": 24.22,
  "interpretation": "Normal weight"
}


Repository Link:
GitHub Repository: https://github.com/prajeshnikhil/BMI_API

Feel free to clone, fork, or contribute to the repository as needed. If you have any questions or suggestions, please don't hesitate to reach out.
