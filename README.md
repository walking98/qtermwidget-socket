A simple example showing how to use QTermWidget to control and display a remote terminal.

To run this example, you should: 
1. Build client-side program. In my PC, I use 'apt-get' to install the QTermWidget library (e.g. apt install libqtermwidget5-0-dev).
   mkdir build
   cd build 
   qmake ../RemoteTerm.pro
   make (will generate the client side exe: RemoteTerm)
2. Start the shell-srv.py with specific paramenters.This will expose a shell via socket.
3. Start the client-side program from commandline with specific paramenters.

Now you will get your own remote terminal work with QTermWidget.
