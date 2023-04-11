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

Screenshots:

![image](https://user-images.githubusercontent.com/96374713/231174757-dd3e5b0f-e7ab-4053-997c-3fb42f5b641e.png)

![image](https://user-images.githubusercontent.com/96374713/231174838-1a5b28d6-c24e-47a3-a479-af7400ef57aa.png)

![image](https://user-images.githubusercontent.com/96374713/231174905-df56a145-0c50-4c9e-9712-d48e6012657e.png)

![image](https://user-images.githubusercontent.com/96374713/231174972-cfc510d8-af6c-41b1-8845-e2e18d6d2a38.png)
