This file is just a descriptor for the diagram.  

On the diagram, starting from top-down, and left to right, you can see all the resources we make for a cloud instance.
The Subnet breaks up the VPC IPAddresses.
The instance thus relies on the subnet to have its own networking protocols seperate from everyone elses.
The right side larger square is the route table with all of the routes we added to it.
On the next row down, the VPC is a logically seperated network that connects all the components.
The security group is in the VPC as it is the firewall rules we created controlling where what connections can be made from.
Outside of those is the internet gateway, that connects the whole cloud structure we built to the wider internet.
Lastly is the IP address which is for the incoming traffic acting as a sort of mailing address.
