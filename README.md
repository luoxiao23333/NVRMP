Network Virtualization Resource Management Platform (NVRMP)  

MLScheduler: The scheduler to create containers and allocate virtualized resources to services  
Containing the scheduler container

UsableK8SDeployment: Kubernetes config yaml file for the whole framwork  
Integrating scheduler container, resource virtualization daemonset, AD services containers including Detection, Tracking, SLAM-Localization and Fusion  

ProcessResourceLimiter: Including containers of AD services and their related wrap. The wrap is used to collaborate with the scheduler.

MetricsAnalysis: The source code of data analysis and visualization.  

MLTaskDeviceSimulator: To simulate devices that send AD services request. 