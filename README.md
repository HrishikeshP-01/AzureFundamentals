## Cloud computing characteristics
*Idea with cloud computing* – have a metered self-provisioned way to access IT services over a network
### 5 main cloud computing characteristics
1. Resource pooling – 
- Cloud service provider (CSP) has equipment available for cloud tenants (us)
- Some resources of a cloud are – compute, network, storage, etc.
- Resource pooling means that all these resources appear to be infinite to the cloud tenant
2. Broad access – 
- We can use a wide array of devices to access a cloud service
- Cloud service – Some kind of IT service available on cloud
3. Rapid Elasticity –
- We as tenants have the ability to add or remove IT services running in the cloud.
- This allows us to scale.
- Eg:- Adding or removing storage as needed, Adding/Removing VMs, resizing VMs, autoscaling
4. On-demand self-service –
- Cloud user can deploy & manage resources by themselves. The CSP technicians don’t have to get involved.
- This provides us with control to provision & de-provision resources by ourselves.
5. Metered Usage –
- Our usage of power-based resources, etc. are tracked & we pay for what we use. 

## Virtualization & Azure
- Virtualization doesn’t mean that the environment is a cloud. But cloud means that virtualization is possible.
- OS virtualization requires a hypervisor. 
*Hypervisor* - A hypervisor is a streamlined OS that’s designed to regulate access from multiple VMs to  one set of underlying hardware.
- Type 1 hypervisor
- Type 2 hypervisor

*Application virtualization / App streaming* – Users have access to an app but it isn’t installed on the device they are using. It’s running in the cloud.

*Application container* – Logical boundary containing everything an app needs to run. It runs on a host that has an installed engine that can run containers. They are smaller than VMs & run faster.

*Virtual Desktop Infrastructure (VDI)* – Access a desktop OS which actually runs on the cloud.

*SDN* – Allows customers to configure their own cloud networks without connecting to an underlying network infrastructure device. It provides an abstraction layer that allows user to easily configure networks using CLI or GUIs instead of native language of routers & switches.

####Type 1 hypervisor
- Is an OS.
- Runs directly on hardware. Therefore the name “Bare metal hypervisor”
- Streamlined to support virtualization hosting.
- Eg:- VMWare

#####Type 2 hypervisor
- Runs as an app within OS. 
- Stability & performance of host OS affects VM guests.

*Type 1 > Type 2 hypervisor*

####In Azure cloud we have an option of dedicated VM Hosting
- A single cloud customer has access to a hypervisor running on a physical host in a data center. It will not run any other VMs of other customers on it.
- This is more expensive than shared hosting of VMs.
- We use it especially when there’s legal/regulatory compliance.

**VM Sprawl** – It’s quick & easy to provision VMs in cloud. However, it is also very easy to forget about VMs. VM Sprawl occurs when no: of VMs increase to the extent that admins can no longer control or manage them. This will lead to wasteful consumption of resources, increased costs, loss of performance & even server crash.


