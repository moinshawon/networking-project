# networking-project
Project  XYZ:

Network Requirements:

XYZ University has the following 5 departments.
1. IT
o	Consists of 50 hosts.
2. Accounts 20
o	Consists of 20 hosts.
3. Office of the Registrar 
o	Consists of 50 hosts.
4. Faculty 
o	Consists of 250 hosts.
5. Students 
o	Consists of 2000 hosts.

Some things to keep in mind while designing the network:

●	Use routers/switches wherever required.
●	But the university cannot afford to have more than 3 routers. Each department should be a separate network.  
●	Install at least 2 PC/Laptop for each individual network
●	All the departments should be able to communicate with each other.
●	One router (Border router) should have the connection to the ISP for the Internet. The Internet in this example consists of  ONLY 3 servers i.e (Google, Youtube & Facebook)
●	RIPv2 routing protocol should be used between the internal routers and static routing with the ISP router.
●	The IT department maintains two servers, the web server and the email server.
●	Only the IT, Accounts and the Office of the Registrar are allowed access to all three sites.
●	Faculties can browse Youtube and Google Only.
●	Students can only access Google.
●	Students should not be able to access Accounts and IT departments.
●	Private IP used by the university is 172.16.0.0/12 
●	The Faculty and Students department should get their IP through DHCP, but rest of the departments should have static addressing.
●	The ISP has allocated 10 public addresses for this university, 105.12.32.15 – 24/25. The last two addresses are statically allocated for the web server and email server at the IT department. So all private addresses allocated must be translated to public when accessing the Internet.

Deliverables:

The network mentioned above should be implemented in packet tracer, with necessary devices and full configuration.
After completion you should be able to test the conditions imposed.
As hardcopies, you will have to submit the network topology diagram with proper labels and also all the configurations of all the routers that you have implemented. 
