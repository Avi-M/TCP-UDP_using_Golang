# TCP-UDP_using_Golang
Throughout above Program i have  created the following:

(a).A TCP server and client. The TCP server accepts incoming messages from a TCP client and responds with the current date and time.
You can now test your TCP client and server. You will need to execute the TCP server first so that the TCP client has somewhere it can connect to.

Run your TCP server. From the directory containing the tcpS.go file, run the following command:

$ go run tcpS.go 1234
The server will listen on port number 1234. You will not see any output as a result of this command.

Open a second shell session to execute the TCP client and to interact with the TCP server. Run the following command:

$ go run tcpC.go 127.0.0.1:1234

You will see a >> prompt waiting for you to enter some text. Type in Hello! to receive a response from the TCP server:

 Hello!
 
(b).A UDP server and client. The UDP server accepts incoming messages from a UDP client and responds with a random number.
You can now test your UDP client and server. You will need to execute the UDP server first so that the UDP client has somewhere it can connect to.

Run your UDP server. From the directory containing the udpS.go file, run the following command:

 $ go run udpS.go 1234
The server will listen on port number 1234. You will not see any output as a result of this command.

Open a second shell session to execute the UDP client and to interact with the UDP server. Run the following command:

$ go run udpC.go 127.0.0.1:1234
You will see a >> prompt waiting for you to enter some text. Type in Hello! to receive a response from the UDP server:

 Hello!
