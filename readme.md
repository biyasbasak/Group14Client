# Peer Audio Sharing
### Description
Peer Audio Sharing is a desktop application in Elixir used to share audio files peer to peer instead of downloading it from main server. When a user wants an audio file, he/she searches for it. This application will check whether that file is availabe on any  peer's application. If the file is available, it will download it from peer. Otherwise it will download it from main server. Peer Sharing reduces the traffic between client-server communication.
### Technologies Used
Language: Elixir

Client-side: Json, mint, libcluster, CSV

Database: Sqlite3

Library for Backend: SqliteX, Plug, Json, Poison
### Prerequisits
To run this application, it is necessary to install Elixir on the desktop. You can download Elixir here: https://elixir-lang.org/install.html