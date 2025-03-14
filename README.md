# Chat Client & Server

## Overview
This project is a chat client and server program that enables users to connect to the same IP address and port number to communicate in real time. It was developed as part of CS 3500 at the University of Utah, focusing on networking and logging concepts.

## Authors
- **Phuc Hoang**
- **Chanphone Visathip**

## Repository Information
- **GitHub Repository:** [Networking & Logging Repository](https://github.com/uofu-cs3500-spring24/assignment-seven-logging-and-networking-v_tekkkkk2)
- **Commit Date:** April 4, 2024, 11:25 PM

## Features
- **Real-time chat:** Users can send and receive messages over a network.
- **Multiple clients support:** Multiple users can connect to the same server.
- **Logging functionality:** Logs network events and errors for debugging.
- **Server shutdown (Issue Identified):** Attempted implementation of a shutdown button.

## Issues and Debugging Challenges
- The shutdown button works correctly on the professor’s chat client but causes our chat client to freeze.
- Error encountered: `Error handling incoming data: Unable to read data from the transport connection: The I/O operation has been aborted because of either a thread exit or an application request.`
- This issue was not present until April 3rd but appeared unexpectedly.

## Time Expenditures
- **Predicted Time:** 48 hours
- **Actual Time:** 54 hours
- **Pair Programming:** 40 hours
- **Debugging:** 19 hours

## Testing Approach
- Wrote basic function tests for the networking class.
- Most testing was conducted by running multiple clients and servers simultaneously to observe behaviors and fix issues.

## Good Software Practices (GSP)
1. **Well-named, Commented, and Short Methods**
   - Used inline comments to clarify method functionality.
2. **Separation of Concerns**
   - The `Networking` class handles both `ChatClient` and `ChatServer`, but we believe a better approach would be separate classes for each.

## Consulted Peers
- Discussions with Trenton, Mia, Ted, and Shadrach helped in resolving issues.

## References
1. Piazza Posts
2. ChatGPT - [ChatGPT](https://chat.openai.com/)
3. [TcpClient Documentation](https://learn.microsoft.com/en-us/dotnet/api/system.net.sockets.tcpclient?view=net-8.0)
4. [Logger in C#](https://learn.microsoft.com/en-us/dotnet/core/extensions/logging?tabs=command-line)
5. [Error Handling on StackOverflow](https://stackoverflow.com/questions/7228703/error-the-i-o-operation-has-been-aborted-because-of-either-a-thread-exit-or-an)

## License
This project is copyrighted by CS 3500, Phuc Hoang, and Chanphone Visathip. It may not be copied for use in academic coursework.

