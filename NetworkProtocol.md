- There are 7 layers , Application layer, Presentation layer, Transport Layer ...
- Important layers are Application & Trabsport Layer
- In Application Layer we have Client Server Protocol & Peer to Peer protocol
- Client Server protocols are HTTP, FTP, SMTP, Websocket
- In HTTP, FTP, SMTP client send request to server and server responds , In Websocket there is a bi directional communication between client and server.
- We use Websocket when we are designing any chat application
- HTTP creates a conncetion and data gets transferred via that connection
- FTP creates a control connection which persists, and then a data link connection, Data Link connection is not secured so we generally dont use FTP
- SMTP is used for sending mail, for receiving mail, we use IMAP/POP , IMAP is generally used, POP is not used because in POP it deletes the mail after reading from server, so to access the mail from multiple device we use IMAP
- Now coming to Transport layer - We have TCP and UDP
- in TCP one virtual connection gets created, message gets chunked into packaets and sent, ordering is maintained, and on each packet arrival we get ack, if any packet does not receive pack there is a retry mechanism
- UDP is lossy, it creates multiple virtual connection and send the chunks, no ack / retry is available, this is fast, used for vedio streaming
