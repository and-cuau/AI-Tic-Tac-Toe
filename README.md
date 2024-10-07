# AI-Tic-Tac-Toe
Tic-Tac-Toe in C++ with two game modes. The first mode is single-player mode in which the player competes against an AI opponent. The second mode is two-player mode in which the player competes against a second player over LAN. LAN connection is performed using the Boost.Asio library. Designed for demonstration purposes, the program currently supports two-player mode on a single computer.

## Prerequisites
- C++ compiler (gcc, g++)
- Windows


# Installation
## Download Boost
1. Visit the Boost website: Go to the [Boost Downloads page](https://www.boost.org/users/download/).
2. Download "boost_1_86_0.zip" zip file for Windows.
3. Extract the files: Unzip the downloaded file to your desired location.


1. Navigate to the Boost directory:
   ```bash
   cd path/to/boost

2. Run bootstrap.bat:
   ```bash
   ./bootstrap.bat

2. Run bootstrap.bat:
   ```bash
   ./b2.exe


## Download and run GitHub files
1. Clone the repository:
   ```bash
   git clone https://github.com/and-cuau/AI-Tic-Tac-Toe.git
   
2. Navigate into the project directory:
    ```bash
   cd directory

3. Build tttserver.cpp:
   ```bash
   g++ -I"path\to\boost" tttserver.cpp -o tttserver -L"path\to\boost\stage\lib" -lstdc++ "path\to\boost\stage\lib\libboost_system-vc143-mt-x64-1_86.lib" -lws2_32

4. Run the tttserver object file:
      ```bash
   ./tttserver

5. Open another terminal

6. Build tttclient.cpp:
   ```bash
   g++ -I"path\to\boost" tttclient.cpp -o tttclient -L"path\to\boost\stage\lib" -lstdc++ "path\to\boost\stage\lib\libboost_system-vc143-mt-x64-1_86.lib" -lws2_32

7. Run the tttclient object file:
      ```bash
   ./tttclient



10. Repeat steps 3-7 excluding steps 3 and 6 to play again.
   

