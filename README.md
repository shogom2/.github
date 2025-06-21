# What is CoHDI
CoHDI (Composable Hardware Disaggregated Infrastructure, also known as Composable Disaggregated Infrastructure) is an innovative server architecture that allows flexible reconfiguration of server components and on-demand provisioning of servers with the required specifications.

Traditionally, deploying a large number of GPUs required provisioning multiple physical servers, often leading to inefficient use of CPU and memory resources. CoHDI addresses this by disaggregating server components and connecting them via PCIe, CXL, or optical switches to form a shared resource pool. These switches enable the software-defined composition of custom bare-metal servers by connecting only the necessary components.

This architecture—referred to as composed bare metal hardware —aims to deliver both high performance and energy efficiency by dynamically adjusting server configurations to match workload requirements.
![スクリーンショット 2025-06-21 22 28 52](https://github.com/user-attachments/assets/fafb21a1-a2b4-4635-a63b-5aeb6b8685e1)


# CoHDI project: Vision statement

The objective is to foster a community-driven, standards-based open ecosystem for next-generation architectures and frameworks built on Composable Hardware Disaggregated Infrastructure (CoHDI, pronounced "Cody"), also known as [Composable Disaggregated Infrastructure technology](https://github.com/InfraDDS/README.md/blob/main/SPEC.md).
CoHDI enables data center operators to realize the benefits of cost efficiency, high availability, and sustainability through a disaggregated computing system. 
However, a gap still exists between Kubernetes and CoDHI, making it challenging to achieve more dynamic composability within the Kubernetes cloud-native environment. 
The DDS project and Composable Resource Operator project aim to bridge this gap by collaborating with Dynamic Resource Allocation, sig-node, sig-autoscaling and sig-scheduling projects.

![image](https://github.com/user-attachments/assets/b74707a8-5a48-46c8-93fe-945f9df13646)

# Project Goals
- Create a community-driven, standards-based open ecosystem for composable resource technologies
- Develop a vendor-agnostic framework and architecture for composable resource software stacks
- Reuse existing APIs or define a new set of common APIs for composable resource technologies as needed
- Provide implementation examples to validate the architectures/APIs

# Project Backgrounder
Generative AI has ushered in a new era of artificial intelligence, significantly increasing power consumption compared to previous generations. As a result, many workloads now require data-centric infrastructure amid rapid hardware evolution.
Composable Disaggregated Infrastructure (CoHDI) is a key subset of data-centric infrastructure, designed to reduce power consumption by leveraging heterogeneous, composable resources. This approach enables workloads to run on the most appropriate resources, allocated in a timely and efficient manner.
New infrastructure elements in cloud data center services, as well as in the IOWN Global Forum’s Data-Centric Infrastructure as a Service (DCIaaS), demand more dynamic composability with various types of PCIe-connected devices—including GPUs, DPUs/IPUs/SmartNICs, FPGAs, NVMe, and CXL memory—in order to enable power-saving operations.
These components must be dynamically composed and decomposed into CPU hosts running Kubernetes nodes via PCIe/CXL switch fabrics. This allows for flexible scaling of host servers (scale-up/scale-down) and applications (scale-out/scale-in) within a Kubernetes cluster.
CoHDI system provides dynamic device scaling capabilities for each Kubernetes node.

# How To Contribute
This project welcomes contributions and suggestions. We are happy to have the Community involved via submission of Issues and Pull Requests (with substantive content or even just fixes). We are hoping for the documents, test framework, etc. to become a community process with active engagement. PRs can be reviewed by by any number of people, and a maintainer may accept.

See [CONTRIBUTING](https://github.com/InfraDDS/composable-dra-driver/blob/main/CONTRIBUTING.md) and GitHub Basic Process for more details.
