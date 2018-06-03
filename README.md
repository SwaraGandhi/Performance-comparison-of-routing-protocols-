# Performance-comparison-of-routing-protocols-
Comparing protocols AODV (Ad hoc On-Demand Distance Vector), DSR (Dynamic Source Routing) and DSDV (DestinationSequenced Distance-Vector) to ascertain their qualities for different sized networks. 

Platform

• Network Simulator 3

• NetAnim

• Ubuntu Terminal

Protocols

DSDV (Destination Sequenced Distance Vector)

DSR (Dynamic Source Routing)

AODV (Ad hoc On-Demand Distance Vector)


Results

The simulation results show the performance of three routing protocols AODV, DSR and DSDV under various scenarios, by varying the number of nodes from 10 (low density), to 25(medium density) and to 50 (high density) in a fixed area of
1000*1000 meters. Random Waypoint Mobility Model has been implemented to monitor and generate node mobility. It can be observed that performance differs broadly across diverse number of nodes and different type of pause in node mobility.
In High Mobility Networks AODV works better compared to other 2 protocols (DSR and DSDV). Whereas DSR works decently for low bandwidth and low power Network. Also, when delay is compared, DSR will be having added delay because it does not choose shortest path constantly and takes numerous route to reach destination while AODV will always select the shortest path. Since in DSDV, it will have high overhead because of unnecessary advertisement thus packet received will be less and works good only for the low mobility networks. Thus, AODV will have better versatile performance compared to DSR and DSDV because it provides more
steady results.
