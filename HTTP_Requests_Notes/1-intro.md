```
,--.  ,--.,--------.,--------.,------.     ,------. ,------. ,-----.   ,--. ,--.,------. ,---. ,--------. ,---.
|  '--'  |'--.  .--''--.  .--'|  .--. '    |  .--. '|  .---''  .-.  '  |  | |  ||  .---''   .-''--.  .--''   .-'
|  .--.  |   |  |      |  |   |  '--' |    |  '--'.'|  `--, |  | |  |  |  | |  ||  `--, `.  `-.   |  |   `.  `-.
|  |  |  |   |  |      |  |   |  | --'     |  |\  \ |  `---.'  '-'  '-.'  '-'  '|  `---..-'    |  |  |   .-'    |
`--'  `--'   `--'      `--'   `--'         `--' '--'`------' `-----'--' `-----' `------'`-----'   `--'   `-----'
```

Course 15 - Programming 101

#### In this module

We'll learn what HTTP requests are, how are they helpful, and how to make and receive requests.

##### So, what is HTTP?

HTTP is a protocol for distributed information systems. It is the standard for cross-system communication, and it is
used by all modern webservers to send and receive data.

Let's think about this in the context of logging into Myspace.

When you log in to Myspace, there are technically two parties communicating - your browser (the client), and Myspace (the server). When you click on the login button, your browser sends an HTTP request to Myspace containing information like your email and password. Myspace then verifies if that information is correct, and responds with either a "success" or a "failed" message.

The flow would look something like this:
![diagram1](https://github.com/joshua-alex/github101/blob/githubNotes/HTTP_Requests_Notes/assets/diagram2.png)

And if we abstract the concepts, this is what an HTTP interaction looks like:

![diagram2](https://github.com/joshua-alex/github101/blob/githubNotes/HTTP_Requests_Notes/assets/diagram1.png)

##### What data can HTTP transport?

HTTP is designed to support multiple data types, including large data structures and rich media. Using HTTP, you can send
and receive:

1. Text
2. Images and videos
3. Complex data structures
4. Web pages (HTML)

##### What tools will we use to learn HTTP?

1. Axios - an easy-to-use Node-based HTTP client designed to work with ES6
2. A dummy REST API

[So what is that word you used, REST?](https://github.com/joshua-alex/github101/blob/githubNotes/HTTP_Requests_Notes/2-rest.md)
