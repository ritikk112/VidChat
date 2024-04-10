# VidChat
&nbsp;
## Started Guide

### 1-> Run the development server using: 


   &nbsp;

	npm run devStart



  > This executes npm run nodemon server.js to initiate the local server.
  
  &nbsp;
  
    
### 2-> Run the peerjs server using command:
	
  &nbsp;

 
	peerjs --port 3001


 
	
  > This command launches the PeerJS server and binds it to port 3001.

  &nbsp;
    
### 3-> (Optional) To launch the server over your own ip-address



  If you want to share your development server with others outside your local network, ngrok provides a secure way to do so.
     
Prerequisites:
    
  * An ngrok account (https://ngrok.com/)
    
  * ngrok installed on your system
     
   Once all set up execute the following command:

   &nbsp;


	ngrok http <your ip-address>:<port>

 > Instantly creates a secure HTTPS URL for your local server, making it accessible from anywhere on the internet.

 &nbsp;
 &nbsp;&nbsp;
