COMPANY: CODTECH IT SOLUTIONS

NAME: GOWRI SANGEETHA V 

INTERN ID: CT08VKR

DOMAIN: JAVA PROGRAMMING 

DURATION: 4 WEEEKS

MENTOR: NEELA SANTOSH
A simple Java REST API client that makes a GET request to fetch data from a public API. This project is designed to be compiled and run in Visual Studio Code (VS Code).

Prerequisites

Java 17+ (Check with java -version)

VS Code installed

Java Extensions in VS Code (Install "Extension Pack for Java")


Setup Instructions

1. Clone or create the file manually
If you are using Git:

git clone https://github.com/your-repo/java-rest-api-client.git
cd java-rest-api-client

Otherwise, create a file named RestApiClient.java and copy the code.


2. Open in VS Code
Navigate to the project folder and open it in VS Code:

code .


3. Compile the Java File
Run the following command in the terminal:

javac RestApiClient.java


4. Run the Program
Execute the compiled Java file:

java RestApiClient



Code Overview

Uses HttpURLConnection to send an HTTP GET request.

Fetches data from https://jsonplaceholder.typicode.com/posts/1.

Prints the response data in JSON format.


Example Output

Response Code: 200
Response:
{
  "userId": 1,
  "id": 1,
  "title": "sunt aut facere repellat provident occaecati excepturi optio reprehenderit",
  "body": "quia et suscipit..."
}

Customization

Change apiUrl in RestApiClient.java to request a different API.

Modify the request method (GET, POST, etc.) as needed.
