<h1>Laboratory Activity #3: Working with JSON</h1> <br>
<h3>Objectives:</h3> <br>
- Familiarize and identify JSON as a primary data format for API development <br>
- Parse JSON strings and traverse data in the JSON string using Python <br>
- Convert Python data structures into a valid JSON format <br>

<h3>Instructions: </h3> 

<h3>Prerequisites: </h3> <br>
- Clone the Github repository:  https://github.com/jpcanamaque/itec116_it4e_lab <br>
- Go to the `lab3` folder, create your .venv and install the pip packages inside the folder <br>

<h3>Requirements: </h3> <br>
- Create a new API that has the following specs: <br>
- Endpoint: /detailed_post/{userID} <br>
- Method: GET <br>
- Given the userID, you should show all the post of that specific user and all comments per each post. <br>
- Use necessary key names based on the value to be outputted. <br>

<h3>Importance: </h3>

<h3>API Integration </h3>
Many APIs require data to be sent and received in JSON format. Understanding how to parse JSON and convert Python data structures into JSON allows you to effectively interact with these APIs.

<h3>Data Handling </h3>
Working with JSON gives you the ability to work with complex, nested data structures. You’ll learn how to access, manipulate, and traverse deeply nested JSON objects, which is a critical skill in modern software development.

<h3>Building Better Web Services </h3>
If you're creating an API, understanding how to handle JSON input and output is essential. You need to know how to serialize your server’s response data into JSON and also handle incoming requests that include JSON payloads.

<h3>Steps: </h3><br>
1. Installing dependencies like, ("pip install -r requirements.txt"). <br>
2. Implementing the following endpoints. <br>
3. Ensuring that it has a proper JSON formatting, validation, and error handling. <br>
4. Run the API using, ("uvicorn main:app --reload"). <br>
5. Perform the GET command for POST, COMMENTS, FORMATTED_POSTS, FORMATTED_COMMENT, and DETAILED_POST. <br>
- "GET http://127.0.0.1:8000/posts/" (To get the all Posts) <br>
- "GET http://127.0.0.1:8000/posts/1" (To get the specific Post)
