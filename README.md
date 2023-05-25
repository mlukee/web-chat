# Web Chat using sockets
You need one instance of server, and one or more instances of clients running. When programming this program, I used Visual Studio 2022. Program is written in **C#**, server is running in command line, and for the clients I created a simple GUI. All the messages between server and client are **encrypted** with **MD5 and TripleDES**.

I also defined simple protocol for communicating:
  - JMatic -> Matic has joined the chat (**j**oin)
  - MMatic: Pozdravljen -> message "Matic: Pozdravljen" (**m**essage)
  - #GAMESTART -> start the game
  - #GAMESTOP -> stop the game

The code for client can be viewed [here](https://github.com/mlukee/web-chat/blob/main/TCPSockets/Odjemalec/Form1.cs).

The code for the server can be viewed [here](https://github.com/mlukee/web-chat/blob/main/TCPSockets/Streznik/Streznik.cs).

Here is a screenshot of server and two clients.
![image](https://github.com/mlukee/web-chat/assets/31586745/12a72820-ba4c-4992-86ec-a633d4343c0f)

Here is a screenshot of a simple **Hangman game** between two players.
![image](https://github.com/mlukee/web-chat/assets/31586745/efcc2710-ead0-4893-9ca9-38d5a3d7a479)

