# DIY-Exercises-4.1


MuleSoft.U DevelopmentFundamentals - DIY ExercisesExercise 4-1: Implement a REST API using APIkitTime 

Estimate: 2 hoursIn this exercise, you implement a REST API that has a RAML specification. 


You will:

•Use APIkit to create implementation flows.
•Add logic to APIkit auto-generated flows.
•Enhance the API and regenerate the flows using APIkit.


Scenario: 

A RAML specification for an Accounts API was published to Anypoint Exchange. You need to implement this API using Anypoint Studio. Account data should be retrieved from the flights_customers database and then transformed to match the Account data type defined in the Accounts API.
After you finish implementing the API, the requirements change, and you will have to extend the existing RAML specificationand modify the API implementation.


Use Anypoint Studio to create an API Implementation from an API 

Create a new Anypoint Studio project that uses APIkit to generate an API implementation for your API solution from exercise 3-1 or use /files/module03/accounts-mod03-api.zip (in the MUFundamentals_DIYexercises.zip that you can download from the Course Resources).


Retrieve account data

Add logic toreturn all customer data from the flights_customers database for GET /accountsusing the following MySQL database credentials:
•Host: mudb.mulesoft-training.com
•Port: 3306•User: mule•Password: mule
•Database: training
•Table: flights_customers
Add logic to only return accounts that match a particular type (business or personal).

etc... Refer to "MuleSoft.U DevelopmentFundamentals"
