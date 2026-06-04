LANDING ZONE : A landing zone is basically a ready-made environment aligned to best practices, where you can deploy workloads with guardrails already in place. You could mention it covers governance, security, networking, and identity, so teams don’t start from scratch.

A VPC is a virtual network that closely resembles a traditional network that you'd operate in your own data center. After you create a VPC, you can add subnets.

A subnet is a range of IP addresses in your VPC. A subnet must reside in a single Availability Zone. After you add subnets, you can deploy AWS resources in your VPC.

You can assign IP addresses, both IPv4 and IPv6, to your VPCs and subnets. You can also bring your public IPv4 and IPv6 GUA addresses to AWS and allocate them to resources in your VPC, such as EC2 instances, NAT gateways, and Network Load Balancers.

A Network Access Control List is a stateless firewall that controls inbound and outbound traffic at the subnet level. It operates at the IP address level and can allow or deny traffic based on rules that you define. NACLs provide an additional layer of network security for your VPC.

A security group acts as a virtual firewall for instances (EC2 instances or other resources) within a VPC. It controls inbound and outbound traffic at the instance level. Security groups allow you to define rules that permit or restrict traffic based on protocols, ports, and IP addresses.  

Use route tables to determine where network traffic from your subnet or gateway is directed.

Use a VPC peering connection to route traffic between the resources in two VPCs.

Copy network traffic from network interfaces and send it to security and monitoring appliances for deep packet inspection.

A flow log captures information about the IP traffic going to and from network interfaces in your VPC.

Connect your VPCs to your on-premises networks using AWS Virtual Private Network (AWS VPN).
