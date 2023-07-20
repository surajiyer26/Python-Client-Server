Simple client-server programs, written in python

Here, 'mysocket.py' represents the client, which is a simple python program written using the socket module
The 'myserver.py' represents the server, written again using only the socket module

You'll have to initially run the 'myserver.py' program, following which, you can run the 'mysocket.py' program in a different window any number of times

No matter what 'mysocket.py' requests for, 'myserver.py' is going to send it a 'Hello Word' html file

<img width="398" alt="image" src="https://github.com/surajiyer26/Python-Client-Server/assets/114157491/c2959161-221c-4635-9a83-0757b6cdc97f">
Initialized the server

<img width="395" alt="image" src="https://github.com/surajiyer26/Python-Client-Server/assets/114157491/e0bafcb4-cdbc-412a-88a8-12fda5c45325">
Ran the client, and received a 'Hello World' html file

<img width="394" alt="image" src="https://github.com/surajiyer26/Python-Client-Server/assets/114157491/c39503e7-829b-4172-833d-74bb9d55c5fb">
The 'GET' request the server received from the client just now

<img width="388" alt="image" src="https://github.com/surajiyer26/Python-Client-Server/assets/114157491/ecba6989-5c8f-47c6-aa8a-0330f96edd90">
If you open localhost:9000 on your browser, you see the html from the server response formatted out

<img width="399" alt="image" src="https://github.com/surajiyer26/Python-Client-Server/assets/114157491/befccd68-c039-4089-855c-c39c3f214e08">
The 'GET' requests the server received due to above action. It'll now continually wait for favicon, which will never be sent by the program we've written
