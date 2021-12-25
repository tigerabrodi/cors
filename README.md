# Cross-Origin Requests

- Exists to protect the internet from evil hackers.

- You can't send fetch to any random site.

- Tricks people used to send requests to another site in order to do malicious stuff were scripts, iframe...

- Safe requests: Method must be GET, POST or HEAD. Allowed header are Accept, Accept-Language, Content-Language, Content Type with the value application/x-www-form-urlencoded, multipart/form-data or text/plain.

- When we try to make unsafe requests, the browser first sends a special preflight request, to ask the server if it does accept such requests.

- If a request is cross-origin, the browser always adds Origin header to it.

- The browser plays a role as a trusted mediator.
