## CoHDI Project: Vision Statement
The objective is to foster a community-driven, standards-based open ecosystem for next-generation architectures and frameworks built on Composable Hardware Disaggregated Infrastructure ([CoHDI](https://github.com/CoHDI/.github/blob/main/README.md), pronounced "Cody"), also known as Composable Disaggregated Infrastructure.  
CoHDI enables data center operators to realize the benefits of cost efficiency, high availability, and sustainability through a disaggregated computing system.
However, a gap still exists between Kubernetes and CoDHI, making it challenging to achieve more dynamic composability within the Kubernetes cloud-native environment.
The DDS project and Composable Resource Operator project aim to bridge this gap by collaborating with Dynamic Resource Allocation, sig-node, sig-autoscaling and sig-scheduling projects.

## How it works
CoHDI system is composed of hardware resource pool and Composable manager (CoDHI manager) software. In the hardware resource pool, all components are connected to PCIe or CXL switches. The CoHDI manager controls the switches to create composed bare metal/hardware servers by software definition. It has Composable Resource API and Composable Resource Operator or Kubernetes may call the API. 

![image](https://github.com/user-attachments/assets/d051630b-00dd-43f9-aef7-9177ae73bb57)

[Composable DRA Driver](https://github.com/InfraDDS/composable-dra-driver)

[Dynamic Device Scaler](https://github.com/InfraDDS/dynamic-device-scaler)

[Customer Resource Operator](https://github.com/InfraDDS/composable-resource-operator)
