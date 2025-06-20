# CoHDI - Composable Hardware Disaggregated Infrastructure: Vision statement

The objective is to foster a community-driven, standards-based open ecosystem for next-generation architectures and frameworks built on [Composable Hardware Disaggregated Infrastructure](https://github.com/CoHDI/README.md/blob/main/SPEC.md) (CoHDI, pronounced "Cody"), also known as [Composable Disaggregated Infrastructure technology](https://github.com/InfraDDS/README.md/blob/main/SPEC.md).
CoHDI enables data center operators to realize the benefits of cost efficiency, high availability, and sustainability through a disaggregated computing system.
However, a gap still exists between Kubernetes and CoDHI, making it challenging to achieve more dynamic composability within the Kubernetes cloud-native environment.
The DDS project and Composable Resource Operator project aim to bridge this gap by collaborating with the Dynamic Resource Allocation in Node, Autoscaler, and Scheduler projects.
![image](https://github.com/user-attachments/assets/1109c4f9-a37a-427e-b065-bb4726252135)

# CoHDI Project Goals
- Create a community-driven, standards-based open ecosystem for composable resource technologies
- Develop a vendor-agnostic framework and architecture for composable resource software stacks
- Reuse existing APIs or define a new set of common APIs for composable resource technologies as needed
- Provide implementation examples to validate the architectures/APIs

# CoHDI Project Backgrounder
A data-centric infrastructure is emerging in the AI era.
New infrastructure elements in cloud data center services and in the IOWN Global Forum’s Data-Centric Infrastructure as a Service (DCIaaS) demand more dynamic composability with various types of PCIe-connected devices, including GPUs, DPUs/IPUs/Smart NICs, FPGAs, NVMe, and CXL memory.
These components must be dynamically composed and decomposed into CPU hosts running Kubernetes nodes via PCIe/CXL switch fabrics, in order to enable flexible combinations of host server scale-up/scale-down and application scale-out/scale-in within a Kubernetes cluster.
CoHDI provides dynamic device scaling capabilities on each Kubernetes node.

# How To Contribute
This project welcomes contributions and suggestions. We are happy to have the Community involved via submission of Issues and Pull Requests (with substantive content or even just fixes). We are hoping for the documents, test framework, etc. to become a community process with active engagement. PRs can be reviewed by by any number of people, and a maintainer may accept.

See [CONTRIBUTING](https://github.com/InfraDDS/composable-dra-driver/blob/main/CONTRIBUTING.md) and GitHub Basic Process for more details.
