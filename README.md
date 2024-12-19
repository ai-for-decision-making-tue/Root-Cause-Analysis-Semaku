Multi agent system simulation of a manufacuring process of the diebonding and wirebonding of semiconductor lots.
The physical system is created in python, the cyber system in JADE (Java).
In order to run the physical system, directory locations must be changed.
In order to run the cyber system JADE must be installed correctly and the agents must be loaded in at run configurations, arguments and then the following line must be implemented:
-gui -agents "Communicator:JadeCommunicationAgentv2;DigitalWB1:DigitalWBv2;WBMonitor1:WBMonitor;WBMonitor2:WBMonitorM2;ProductionPlanner1:ProductionPlanner;CommunicatorT2:JadeCommunicationAgentT2;DBMonitorM11:DBMonitorM1;DBMonitorM22:DBMonitorM2;DigitalDB1:DigitalDB"
