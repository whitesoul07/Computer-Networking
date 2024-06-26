# ***Basic Computer Network Devices*** 

1 ***Network Interface Card***
 ( Ethernet card, network card, LAN card, Network Adapter Card(NAC) )
  -> Its a physical layer and data link  devices which computer use to connect other device in LAN network .
  
   i) MAC Address -> (Media Acess Control Address) hardware identification number that uniquely identified each devices on a network.(6 byte number)

   ![download](https://github.com/whitesoul07/Computer-Networking/assets/165417316/ab298041-e634-4f98-8e2b-218114127f24)
   ![download](https://github.com/whitesoul07/Computer-Networking/assets/165417316/b60c02fb-50f2-4219-bde6-d9c9d1fa174d)

2 ***WI-FI Card***
-> used to connect any device to local network wirelessely.

 i) Wifi accessing point-> (WAP) physical area of network which provides internet access through wifi also known as wifi hotspot.

  ![images](https://github.com/whitesoul07/Computer-Networking/assets/165417316/2c9dc0e0-af04-4630-87e9-2953f8321744)

3 ***HUB***
-> it is a device which has multiple ports use connect multiple computers of LAN together.

 i) Passive HUB - allow signal to pass without any change.
 
 ii) Active HUB -> increase the strength of signal as it moves from one device to another.

 -> HUB is not secure and safe  as copying the data packets on all the interfaces make it slower and more congested.

 -> HUB sends data in byttes.

 -> it connects devices with same network and store MAC Adresss.

4 ***Switch***
-> Switch do the same work of HUB  but in more   filter and forwarding way.

-> It use an application integrated circuit(ASIC) chip.

-> when a packet is deliver to switch it checks the address and many more things and transfer the packet to the right device.(Packet Switching Technique)

-> Switch sends data in Frames.

-> It connect devices with network and store MAC Adress.

5 ***Router***
->It is a **Network Layer Device**. It routes data packet based on IP Address.

->Router sends message in Packets.

-> It connects two Networks and store MAC Adress.

   ![download](https://github.com/whitesoul07/Computer-Networking/assets/165417316/5f05b933-cb2a-461e-89f9-b33a84c8e301)

6 ***Bridges***
-> It connects Two or more LANs. operates as a Data link Layer. It handels the network that folow the same protocol.

  **Fuction**

  -> Filtering packets

  -> Forwarding Packets

  -> Blocking packets

  ![download](https://github.com/whitesoul07/Computer-Networking/assets/165417316/8f39b238-5ade-4b48-94f4-96c2752a6732)

7 ***Gateway***

-> connects two or more dissimilar networks.

-> it also acts as a Proxy server, Firewall, Malware protection.

   ![download](https://github.com/whitesoul07/Computer-Networking/assets/165417316/6ff868ef-5585-4843-ba39-b81ea85ddf21)


8 ***Reapeater***

-> it is extend transmission so that signal can cover longer distance or be received on the other side of an obstruction.

-> increase the power of ssignal and retransmitted it.

-> In computer networks, a repeater is used to increase the network's reach, restore a damaged or weak signal, or provide access to inaccessible nodes.   


   ![download](https://github.com/whitesoul07/Computer-Networking/assets/165417316/1faba62f-575e-47cc-8d7b-5f0493ef7517)

   ![download](https://github.com/whitesoul07/Computer-Networking/assets/165417316/a611e5ea-bf00-406d-8ee2-aeffe213c067)

9 ***Multi Layer Switch***

-> it is a devices that switches an OSI layer 2 like an ordinary network switch and provides extra functions on higher OSI layers

-> It is highly  programmable and complex which may have few ports or more ports.
# ***Types of Computer Network***

1) **Local Area Network** -> It interconnects  the computer within the limited area like school, office, etc.

   i) Wired LAN -> Ethernet- HUB, Switches.
   ii) Wireless LAN -> WI-FI.

2) **Metropolitian Area Network** -> It connect the user with other computer network in geographic region of a city.

    **Devices used in it is** ->

      i) Switches/HUB -> to establish LAN network.
      ii) Router/Bridges -> to connect two LAN network.

 3) **Wide Area Network**  -> It is a Telecommunicatiion Network that extend over a large geographical area.

    **Devices used in it** -> End and Intermediate Devices.

 4) **Storage  Area Network** -> Cloud Computing ->  on-demand delivery of computing services such as servers, storage, databases, networking, software, and analytics
    
 5) **Virtual  Private Network** ->  A secure network established over the public internet, encrypting the data transferred and restricting access to authorized users only.

# ***Security Devices***

1) **Firewall**
   -> It can be placed on router or hosts(software based) or it can be its own devices. It blocks packets from entering and leaving the network.
   -> It functions at multiple layer of the OSI model specially at layers  2, 3 ,4 and 7.

   **Types of inspection in firewall**

  i) **Stateless Inspection** ->  in this firewall examines every packet under some set of rules
