# Networking-Project
Game of tic-tac-toe developed in Python. It allows two players to play with one another on different command lines through networking. The server starts the game by first running server.py, waiting for the client to connect by then running client.py. Once they’re connected, the game itself starts.

Once they’re connected, the game itself starts. The server starts as "X" and goes first, and the client is "O." The players choose the square they would like to use with coordinates; both "A1" and "1A" would be accepted, for example. The game proceeds, with the players taking turns until one wins or the game is a draw. The host, then the client, is asked whether they'd like a rematch. If both agree, the game starts anew. Socket programming is a way of connecting two nodes on a network to communicate with each other. One socket(node) listens on a particular port at an IP, while the other socket reaches out to the other to form a connection. The server forms the listener socket while the client reaches out to the server.

-------------------------------------------------------------------------------------------------------------------------------------
Rules of the game:

One by one the players have to enter a key ,‘O’ or ‘X’.A player can win the game when either of the diagonals have the same key i.e. ‘O’ or ‘X’ or any of the rows or the columns have the same key otherwise the game will result in a draw.

-------------------------------------------------------------------------------------------------------------------------------------

INTRODUCTION

1.The client-server programming approach separates information producers from information users in a distributed computing system (servers).

2.A client is a software programme that requests resources from a server, such as web pages or IP addresses.

3.Clients can ask a server for this information whenever they want. Users of information are customers.

4.A server is a programme that gives clients access to resources or information. It must be continuously operational and ready to respond to client requirements.

5.Only server apps and their client counterparts can exchange data. Clients are not in direct contact with one another.

   a)Here, we have used python compiler to execute our code.

   b)Python is a multiprogramming language and it can be used for game development Tic-Tac-Toe game is created using no extra libraries, but just socket programming.
