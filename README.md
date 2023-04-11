# dummy_API
This is the repository to test the dummy rest API

# CI/CD
Enable the testing of the provided functionality as part of a CI/CD pipeline (hint: Postman collections can
be executed via newman)


The test has been exported and the exported files have been uploaded to the github repository; the uploaded files are the API call containing test and then the environment variables; the repository is linked to the CI tool.


# Describe the chosen API testing approach

The chosen API that was tested is a get API and based on the importance of such call, a perfomance test was added to check that the call is returned within a stipulated time frame.




Provide execution instructions and enough information explaining the final solution

# Run from Postman
To Run from Postman, all you do is

Create a collection

Import the environment variables

Import the API

Select the environment at the top right

Click the send button

You can see the response and number of test passed

# Run in CLI
Install newman using this command (npm install -g newman)

Run this script (newman run Dummy API.postman_collection.json -e Staging.postman_environment.json --reporters cli,junit --reporter-junit-export /Results/junitReport.xml)
  
Note: this API file contains tests.

