# LAN P2P Chat

## Comprehensive Project Documentation

### Features
- Peer-to-peer communication
- Encrypted chat messages
- File sharing capabilities
- User-friendly interface
- Cross-platform compatibility

### Quick Start
1. Clone this repository:  
   `git clone https://github.com/gustavmanfred/lan-p2p-chat.git`  
2. Navigate to the project directory:  
   `cd lan-p2p-chat`  
3. Install the necessary dependencies:  
   `npm install`  
4. Run the application:  
   `npm start`

### Architecture
The application is built using a modular architecture comprising several core components:
- **Client**: The user interface allowing interaction with other peers.
- **Network Layer**: Manages the peer connections and message routing.
- **Database**: Stores user credentials and chat history.

### Technology Stack
- **Frontend**: JavaScript, React.js
- **Backend**: Node.js
- **Database**: MongoDB
- **Communication Protocol**: WebRTC for real-time peer-to-peer communication

### How It Works
1. Users connect to the same local area network.
2. The application establishes peer connections using WebRTC.
3. Users can send and receive messages or files directly without a central server.
4. Messages are encrypted for security.

### Configuration
- Open `config.json` to configure various settings:
  - `port`: The port number for the server.
  - `encryptionKey`: Defines the key used for message encryption.

### Troubleshooting
- **Cannot connect to peers**: Ensure that all users are on the same local network and check firewall settings.
- **Messages are not sending**: Verify that the application has the necessary permissions to access network interfaces.
- **Slow performance**: Check the network speed and try restarting the application to clear any existing connections.

---  
**Last Updated:** 2026-02-20 11:29:02 (UTC)