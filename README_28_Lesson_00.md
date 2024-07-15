Docker Desktop for Windows or macOs
	https://www.docker.com/get-started
	Download and run the installer for your OS
Sign up for a Docker Hub account
	https://hub.docker.com


Docker Containers
GNU Compiler Collection
>docker pull gcc:latest
LLVM/Clang
>docker pull teeks99/clang-ubuntu:16


Getting Your Questions Answered
Online C++ documentation
https://cppreferecne.com
https://stackoverflow.com
	Search C++ posts with [tag] c++
For live C++ discussions, check out the Slack channel cpplang:
https://cpplang-inviter.cppalliance.org
https://www.includecpp.org/discord/

README.md
cd C:\Users\jonhp28\Documents\examples\
cd C:/Users/jonhp28/Documents/examples/
docker run --rm -it -v "%CD%":/usr/src teeks99/clang-ubuntu:16


Docker
Start(button) cmd administrator
>docker version
Start Службы > Docker
>docker run -d -p 80:80 docker/getting-started



=== Lesson === ch01
cd /usr/src
cd ch01
clang++-16 --version
clang++-16 -std=c++20 GuessNumber.cpp -o GuessNumber
ls
clang++-16 -std=c++20 -stdlib=libc++ -fexperimental-library GuessNumber.cpp -o GuessNumber
./GuessNumber
Ctrl + D - to exit



==== Lesson 01 (Docker and GNU C++ Version) Test-Driving a C++ Application ======
 Windows
docker run --rm -it -v "%CD%":/usr/src gcc:latest
 macOS/Linux
docker run --rm -it -v "$(pwd)":/usr/src gcc:latest

cd /usr/src
g++ --version
	g++ (GCC) 13.2.0 
g++ -std=c++20 GuessNumber.cpp -o GuessNumber
./GuessNumber





