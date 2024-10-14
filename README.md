# ai-magnet-generator-service
This project uses OPEN AI to generate a meaningful test data for your applications. Initial version allows you to generate two value records on a specific topic. Details should be provided through application property file.

# Frameworks used
- Spring Boot WEB
- Spring AI

# Prerequesties
In the current version of the application, the user must have Open AI API account to generate OPENAI API key to access the service. Unfortunately, it's not free.

# How to install
1) Set up your API key as an environment variable OPENAI_API_KEY
   * or update application.properties accordingly
2) Build the project with MAVEN build
3) Run the application as Java application
4) Application will test API key on startup by printing "Application startup joke"

# CURL command example
curl -X POST localhost:15501/vg/generate/10
