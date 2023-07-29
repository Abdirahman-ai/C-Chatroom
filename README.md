# C-Chatroom
## Chat Application

This is a simple chat application built using socket programming in C.

## Features

- Real-time chat between multiple clients and a server.
- Basic chat room functionality to organize conversations.
- Private messaging for one-on-one communication.
- File transfer capability to share files between clients.

## Requirements

- C compiler (e.g., GCC)
- Operating system compatible with socket programming (e.g., Linux)

## Installation

1. Clone the repository:

   ```shell
   $ git clone https://github.com/your-username/chat-application.git

2. Compile the server and client programs:

   ```shell 
   $ cd chat-application
   ```
       $ gcc server.c -o server
   ```
   $ gcc client.c -o client
## Usage

Start the server:
```shell 
$ ./server
````
Launch multiple client instances:
```
$ ./client
````
## Use the chat commands to interact with the application:

- Join a chat room using the command /join [room_name].
- Send a message to the current chat room using the command /msg [message].
- Send a private message to a specific user using the command /private [username] [message].
- Share a file with the chat room using the command /file [file_path].

## Contributing

Contributions are welcome! If you find any bugs or want to suggest new features, please open an issue or submit a pull request. Make sure to follow the existing coding style and provide clear commit messages.

## License

This project is licensed under the [MIT](https://choosealicense.com/licenses/mit/) Licence.


## Contact

If you have any questions or inquiries, feel free to contact Abdinahmen or Jun Yeol at ahme0313@umn.edu, ryoo0005@umn.edu
