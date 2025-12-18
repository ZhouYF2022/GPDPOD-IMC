# GPDPOD-IMC
This project contains instances for Paper 《Green logistics: a matheuristic approach for the pickup and delivery problem with occasional drivers in community group-buying》

# Source of the instance
This example is adapted from the dataset proposed by Sartori and Buriol (10.1016/j.cor.2020.105065) and can be obtained on website https://data.mendeley.com/datasets/wr2ct4r22f/2

# Description：
Name：Instance name
Type: Problem type
Commodity type: The maximum number of different product types that the same node in an instance can contain
Compartment num：The number of available compartments when hiring a vehicle
CapacityHD：Capacity of hired drivers
VehicleHDs：The maximum number of available hired vehicles
CapacityOD：Capacity of occasional drivers

# ID Xc Yc DEMAND StartT EndT SerT PairedID (depot node, pick-up node or delivery node)
The index of the node
The longitude of the node
The latitude of the node
A list, representing the demand for each type of commodity
The earliest start time of service for the node
The latest start time of service for the node
Service time
The pickup node or delivery node corresponding to the node

# StartID EndID StartX StartY EndX EndY StartT EndT (The information of each accidental driver)
The index of occasional driver departure node
The index of occasional driver destination node
The longitude coordinates of the occasional driver's departure node
The latitude coordinates of the occasional driver's departure node
The longitude coordinates of the occasional driver's destination node
The latitude coordinates of the occasional driver's destination node
The earliest departure time of the occasional driver
The latest arrival time of the occasional driver at the destination

# edge
The distances between each node
