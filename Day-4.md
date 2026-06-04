---
Before Day-4
---
I already knew the fundamentals of web APIs and the MERN stack, including designing routes, handling HTTP requests, and working with JSON payloads. I was also comfortable utilizing developer tools for fundamental web debugging.

---
## Day-4 Checklist
- [x] I know the 5 core HTTP methods (GET, POST, PUT, PATCH, DELETE) and what each is used for
- [x] I can read a status code and know what went wrong — e.g., 401 vs. 403 vs. 404 vs. 500
- [x] I can open Chrome DevTools Network tab, find a request, and inspect its headers, payload, and response
- [x] I can copy a browser request as a cURL command and run it in the terminal
- [x] I can change the `User-Agent` in the browser and see the change in the Network tab
- [x] I can use `curl` to make a GET request with query parameters and a POST request with a JSON body
- [x] I have a running FastAPI app with at least two endpoints (`GET /health` and `POST /echo`)
- [x] I can test my API using the Swagger UI at `/docs` and via `curl` from the terminal

---
After Day-4
---
I learned these things as well, apart from the checklist:
* How rapidly FastAPI generates interactive OpenAPI/Swagger documentation out-of-the-box compared to writing manual documentation patterns.
* Using the Chrome DevTools "Copy as cURL" feature to effortlessly replicate complex browser network requests locally inside the WSL terminal for testing.

------
Feedback (Suggestions for the TDS Team)
---
Pairing command-line `curl` testing with FastAPI’s `/docs` page is an excellent way to bridge the gap between frontend inspection and backend API development. The flow was smooth and highly practical.

---------
### Personal Notes
* **401 Unauthorized** means you aren't authenticated (the system doesn't know who you are), while **403 Forbidden** means you are authenticated but lack the permissions for that resource.
* Testing a local FastAPI app via `curl`:
  `curl -X POST "http://127.0.0.1:8000/echo" -H "Content-Type: application/json" -d '{"message": "hello"}'`
* FastAPI automatically handles data validation based on Python type hints, saving a lot of manual boilerplate validation logic.
