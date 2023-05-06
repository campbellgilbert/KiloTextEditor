The result of following Snaptoken's tutorial for Antirez's kilo text editor (named so for containing under 1000 lines of code) in C: https://viewsourcecode.org/snaptoken/kilo/

Instructions on how to run:
1) You will need to install some kind of C compiler.
  a) LINUX: Run "sudo apt-get install gcc make" on terminal.
  b) MAC: Run the "cc" command; a a window should pop up asking if you want to install the command line developer tools. You can also run "xcode-select --install" to get this window to pop up. Then just click “Install” and it will install a C compiler and make, among other things.
  c) WINDOWS: You'll need to install a Windows linux environment; I prefer Bash, which you can download using the installation guide: https://learn.microsoft.com/en-us/windows/wsl/install
  Run "bash" on the command line to get to the Linux environment, then run "sudo apt-get install gcc make".
2) Install Git.
  a) LINUX & MAC: git should already be installed from when you installed command line tools
  b) WINDOWS: For Ubuntu/Bash, run "sudo apt-get install git"
3) Clone the repo into the directory of your choosing: cd into the directory you want to use (for Windows users: WITHIN YOUR LINUX ENVIRONMENT), run "git clone https://github.com/campbellgilbert/KiloTextEditor"
4) Enter the repo: "cd kilo-src"
5) Checkout the most recent branch (to your repository of choice): "git checkout" 
6) Compile: "make" (or, if that doesn't work, try "cc kilo.c -o kilo"
7) Run: "./kilo" and hit "enter". Have fun!
