# q4-assiignment-2

📄 Code Description
This is a basic FastAPI application that returns a "Hello, World!" message when accessed through the root URL (/). Here's what each part does:

from fastapi import FastAPI: Imports the FastAPI class needed to create the app.

app = FastAPI(): Creates an instance of the FastAPI application.

@app.get("/"): Defines a GET route at the root path (/).

def read_root(): This function is called when the root URL is accessed.

return {"message": "Hello, World!"}: Returns a JSON response with a simple greeting.

When you run this app and visit http://127.0.0.1:8000, you'll receive:

json
Copy
Edit
{
  "message": "Hello, World!"
}
FastAPI also auto-generates interactive API documentation, which you can access at /docs and /redoc.
