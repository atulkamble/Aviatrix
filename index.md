## Aviatrix ACE (Aviatrix Certified Engineer) Multi-Cloud Networking Associate Exam Notes

### Aviatrix
Aviatrix Systems is a software company headquartered in Santa Clara, California, the heart of Silicon Valley. Aviatrix software provides a platform for companies to build networking and security infrastructure in the public cloud. The platform provides architecture applicable to both single and multiple public cloud deployments. Currently, the software supports public clouds such as AWS, Azure, GCP, and OCI.
Aviatrix Systems was the recipient of the Gartner Cool Vendor award in Cloud Computing in 2017 and is the pioneer of Multi-Cloud Network Architecture (MCNA).

### Multi Cloud Network Architecture (MCNA)
MCNA is unlike any other architecture because it embraces, controls, and manages not only the native cloud constructs but also provides advanced services beyond what the Cloud Services Providers (AWS, Azure, GCP, and OCI) can provide. It provides a consistent and repeatable architecture across multiple clouds, being the first in the industry to do so, making it an essential part of the present and future of the public cloud.
Aviatrix creates a purpose-built Multi-Cloud Network Architecture (MCNA) by implementing a data plane through dynamic and software-defined routing with a centralized control plane. Security is built into the network architecture through segmentation, encryption, ingress and egress filtering, and security services insertion. Aviatrix also leverages orchestrating cloud-native constructs, where necessary, in building and controlling the enterprise network and life-cycle management of the overall architecture. 
The architecture is valid for single-cloud-single-region, single-cloud-multiple-regions, or multiple-clouds-multiple-regions and can be easily referenced by both green and brownfield businesses with no issues. This is a common and repeatable architecture across multiple clouds, which creates simplicity and abstraction for the users by hiding all the underlying complexities and limitations of Cloud Service Providers. Because this architecture functions as a reference, it is vendor-agnostic.Architecture defines four distinct layers at a high level. These are Cloud Core, Cloud Security, Cloud Access, and Cloud Operations.

### The Components of the MCNA
1. The Cloud Core has the applications connecting to the Global Transit Layer, which is a unified, global data plane across multiple/single clouds.
2. The Cloud Access Layer is where the on-prem components connect to the cloud.
3. The Cloud Security should be embedded in the Cloud Core Layer and the Cloud Access layer, because the public cloud is a shared infrastructure. This can be seen in the MCN Architecture when the Cloud Security layer cuts through the others.
4. Similarly, the Cloud Operations layer makes Day 1, 2, and 3 operations accessible to all the parts of the cloud. This allows troubleshooting and visibility.

## The Benefits of the MCNA Approach
- The architecture is easily replicated in the Aviatrix controller.
- There is a normalized data plane.
- Service insertion and chaining are easily configured through the transit layer.

