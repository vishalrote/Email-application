# Email-application

To make this we will use Python as a language and its libraries Smtplib for email sending and Tkinter for GUI.

SMTP:
SMTP stands for Simple Mail Transfer Protocol is an internet standard communication protocol for electronic mail transmission. Mail servers and other message transfer agents use SMTP to send and receive mail messages.

How SMTP Works:
Let's try to understand it using a simple example.


SMTP mechanism of communication

![image](https://user-images.githubusercontent.com/96374713/231174381-4247cdbd-8d60-4ef1-b5f1-6c73f538035c.png)

1. Bob uses a UA (user-agent) to compose a message and send it to Alice.
2. Bob’s UA sends the message to his mail server; the message is placed in a queue.
3. The client-side of Bob’s mail server opens a TCP connection with Alice’s mail server.
4. SMTP client sends Bob’s message over the TCP connection.
5. Alice’s mail server places the message in Alice’s mailbox.
6. Alice invokes her UA to read the message.

Screenshot:

![image](https://user-images.githubusercontent.com/96374713/231190947-993bc018-84ee-4670-a003-be5912b6d481.png)
