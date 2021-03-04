
#################################
User story on Basic NFS Configuration on NFS Server and NFS Client 

These user stories includes installation of NFS on Server and client. 

Configuring NFS resources on NFS server and NFS Clients.

Creating a Directory to mount on the NFS-Client.

There is a patching file for ptaching activity on the server. 

NFS-Server.yml includes the installation of NFS, enabling NFS services on NFS server and NFS clients creating a mountpoint, configuring of NFS Client resources on NFS-Client Server and access control list for filesystems which has to be exported to NFS-CLients.

NFS-Client.yml includes the installation of NFS, Exporting a Mountpoint.  

Firewall.yml includes firewall installation and starting of firewalld services.

Config_Firewall.yml includes the configuration of Firewall pertaining to NFS.

Patching.yml includes patching activity on the server.

exports.j2 includes the access control list for filesystems

Order of exceution : NFS-Server.yml NFS-Client.yml Firewall.yml Config_Firewall.yml Patching.yml

##################################
