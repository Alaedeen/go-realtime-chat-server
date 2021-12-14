# Realtime Chat Server With Go and WebSockets

This realtime chat application built using the Go programming language and WebSockets. The frontend is written using HTML5 and VueJS.

You can find the full tutorial [here](https://scotch.io/bar-talk/build-a-realtime-chat-server-with-go-and-websockets).

## Setup and run the app

1. Clone the project
2. Open a cmd int the project directory
3. run the following command in the cmd to add module requirements and sums
```
go mod tidy
```
4. To run the application, open a console window and make sure you are in the "src" directory of your application then run the following command.

```
go run main.go
```

you will see the following message in the terminal to indicate that the server has started
```
http server started on :8000
```

5. visit the [Gravatar](https://en.gravatar.com/) page and create multiple avatars (at least 2) with different emails so you can use it in the app.

6. Open a web browser and navigate to "http://localhost:8000". The chat screen will be displayed and you can now enter an email (created in [Gravatar](https://en.gravatar.com/)) and username.

7. Open another browser tab or window and navigate to "http://localhost:8000". Enter a different email (the second one created in [Gravatar](https://en.gravatar.com/)) and username.


### Take turns sending messages from both windows.