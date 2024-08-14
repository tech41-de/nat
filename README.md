# nat
Discover nat type to debug webRTC connections

The three main NAT types are static NAT, dynamic NAT, and port address translation (PAT).

Symmetric: A symmetric NAT is one where all requests from the same internal IP address and port, to a specific destination IP address and port, are mapped to the same external IP address and port. To use this NAT type with webRTC you will need a TUN server to relay data.

Other NAT types allow direct p2p connection. You still need a STUN server to discover external IP and Port.

Browse the page at https://nat.tech41.de to discover your networks NAT type.

# npm:
npm install --save-dev snowpack


# test width:
npm run start

