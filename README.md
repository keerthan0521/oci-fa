# Oracle Cloud Infrastructure Foundations Associate Certification

## Physical architecture concepts
### Regions
-  A region is a localized geographic area, and an availability domain is one or more data centers located within a region.
-  Oracle cloud regions are globally distributed data centers that provide secure, high-performance, local environments. These regions allow businesses to move, build, and run all workloads in the cloud from infrastructure to applications, while meeting regional data regulations

### Availability Domains
- Availability domains are isolated from each other, fault tolerant, and very unlikely to fail simultaneously or be impacted by the failure of another availability domain.

### Fault Domains
- A fault domain is a grouping of hardware and infrastructure within an availability domain.
- Each availability domain contains three fault domains.
- they let you distribute your instances so that the instances are not on the same physical hardware within a single availability domain.

### Realm
- A realm is a logical collection of regions. Realms are isolated from each other and do not share any data.

## Account and Access Concepts

### Tenancy 
- tenancy is basically secure and isolated partition or account within oci.

### Compartment
- A compartment is a collection of related resources (such as instances, virtual cloud networks, block volumes) that can be accessed only by certain groups that have been given permission by an administrator.

### Identity Domains and Policies
- An identity domain is a container for managing users and roles, federating and provisioning of users, secure application integration through Oracle Single Sign-On (SSO) configuration, and OAuth administration.

### Oracle Cloud Identifier (OCID)
- Every Oracle Cloud Infrastructure resource has an Oracle-assigned unique ID called an Oracle Cloud Identifier (OCID). This ID is included as part of the resource's information in both the Console and API.

### Security Zone
- Security Zones allows your Compute, Networking, Object Storage, Database, and other resources comply with Oracle security principles and best practices. A security zone is associated with one or more compartments 
  
  

  

