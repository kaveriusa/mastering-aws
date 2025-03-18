# AWS VPC

# What is VPC?
A Virtual Private Cloud (VPC) is a virtual network environment within AWS that allows you to create a logically isolated section of the AWS Cloud where you can launch AWS resources in a virtual network that you define.
# Creating VPC
To create a VPC:

Go to the AWS Management Console.
Navigate to the VPC dashboard.
Click on "Create VPC" and specify the VPC details such as CIDR block.
# Creating Subnets & Internet Gateway
Subnets
Subnets are subdivisions of a VPC's IP address range. They help organize and manage different parts of your network.
To create subnets:

Navigate to the VPC dashboard.
Click on "Subnets" and then "Create Subnet".
Specify the subnet details including CIDR block and Availability Zone (AZ).

# Internet Gateway (IGW)
An Internet Gateway allows communication between instances in your VPC and the internet.

To create an Internet Gateway:

Navigate to the VPC dashboard.
Click on "Internet Gateways" and then "Create Internet Gateway".
Attach the Internet Gateway to your VPC

# Route Tables
Route tables control the flow of traffic within the VPC. They ensure that traffic is directed efficiently and securely to its intended destination.

To configure Internet Gateway and Route Tables:

Create an Internet Gateway and attach it to your VPC.
Create a Route Table and define routing rules, allowing traffic to flow between subnets and the internet.
Remember to allow public subnets to access the internet by configuring the route table appropriately.

Note: In routing tables, 0.0.0.0/0 means traffic not destined for the local network (e.g., 10.35.0.0/16) should be routed to the internet gateway.   

Internet Gateway (IGW)
An Internet Gateway allows communication between instances in your VPC and the internet.

Route Tables
Route tables control the flow of traffic within the VPC. They ensure that traffic is directed efficiently and securely to its intended destination.

To configure Internet Gateway and Route Tables:

Create an Internet Gateway and attach it to your VPC.
Create a Route Table and define routing rules, allowing traffic to flow between subnets and the internet.
Remember to allow public subnets to access the internet by configuring the route table appropriately.

Note: In routing tables, 0.0.0.0/0 means traffic not destined for the local network (e.g., 10.35.0.0/16) should be routed to the internet gateway.

Now you have a fully functional VPC with its components set up properly.
