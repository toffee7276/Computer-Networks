# Computer-Networks
In the stop and wait ARQ, the sender keeps a copy of the currently sending frame so that if the receiver does not receive the frame then it can retransmit it.
The sender sets a timer for each frame so whenever the timer is over and the sender has not received any acknowledgment for the frame, then the sender knows that the particular frame is either lost or damaged.
So, the sender sends back the lost or damaged frame once the timer is out. The sender needs to wait for the timer to expire before retransmission.
The sequence number in the data packet helps the receiver to identify and discard the duplicate packet and to send the same feedback again. 
The sequence number in the acknowledgement helps the sender to know which frames are correctly received by the receiver and which frame is to be sent next.
Here, Server runs on one system and Client running on another system given IP address of server and other required arguments 
A text file of messages is sent from client to server by giving the path of the message file (i.e.,  ./messages.txt) 
Noisy channel is implemented over the same network of different hosts
The messages have been sent, received and acknowledged in order




## RESULTS
The simulation of stop and wait ARQ is executed, as the distance between the two hosts increases the number of frames decreases which shows the property of noisy channel.
The efficiency of this protocol can be improvised by increasing the window size on both sender and receiver ends 


