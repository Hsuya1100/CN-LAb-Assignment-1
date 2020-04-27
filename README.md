# CN-LAb-Assignment-1
mininet topology, SDN firewall

## Question-1 
> 1. Build a Data Center Topology as shown below using Mininet CLI (DatacenterBasicTopo). In this topology, we have four brackets, each with four forces and one top-of-rack (ToR) switch. These ToR switches are connected to a central root switch.

> 2. Implement the SDN firewall in the network to obstruct traffic coming its way and filters it according to some rules. A general firewall usually Protect the system from internet. 
Hint :
[For an SDN based Firewall, an OpenFlow controller is required to filter traffic between hosts according to some rules and accordingly let it pass through or not]. [use POX controller to establish our required policies or rules and filter traffic between hosts using the switches.] 

## Question-2 
TCP throughput & fairness 

### Scenario 1: 
> + Start 10 long lived TCP flows sending data from h2 to h1, and similarly 10 long lived TCP flows from h5 to h1. 
> + Start back-to-back ping trains from h2 to h1, and h5 to h1. Record the RTTs with ping 10 times a second.
> + Measure the following: 
> The average throughput for h2->h1 and h5->h1 flows. For each group, measure the aggregate throughput of the 10 flows.
> The average RTT for h2->h1 and h5->h1 flows.
### Scenario 2: 
> + Now start 10 long lived TCP flows from h4 to h3.
> + Repeat the above measurements (average throughput and RTT) for the three groups of flows: h2->h1, h5->h1, and h4->h3. 
> + The starter code sets up the topology and configures PIE. You have to write code to generate the traffic (with Iperf) and do the RTT measurements (with ping). 

