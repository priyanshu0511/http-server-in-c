
# Simple HTTP Server in C

A tiny HTTP server written from scratch in C using raw sockets on Windows.  
It serves a static HTML form and handles basic GET and POST requests.

Yeah, it was painful. Wouldn't recommend unless you're into suffering. 😅

## How to Run

```bash
gcc main.c -o server.exe -lws2_32
./server.exe
```
Then open your browser and go to: [http://127.0.0.1:5500](http://127.0.0.1:5500)

## Files
-   `main.c` – the server source code
-   `input.html` – the HTML form served by the server
