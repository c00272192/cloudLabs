# Lab 1 

### 1. Check if your processor supports Intel/AMD virtualization technology. Enable Intel virtualization technology in BIOS if possible.  
Processors from Intel and AMD support virtualization (Intel VT-x or AMD-V). You can check if your system supports virtualization via system tools, and if it’s disabled, you can enable it in the BIOS settings.  

### 2. The cloud is almost everywhere in our lives now. What do you think are the fundamental reasons behind its success? Name three pros and three cons of cloud.  
The cloud is successful because it offers **scalability, cost efficiency, and accessibility** for both consumers and businesses.  

**Pros:**  
- Lower costs for hardware and maintenance  
- Flexible scalability (scale up or down as needed)  
- Reliable with built-in redundancy and high availability  

**Cons:**  
- Security concerns, as data is stored off-site  
- Downtime risks if the cloud service experiences outages  
- Vendor lock-in, making it difficult to migrate between providers  

### 3. What is the primary function of a hypervisor in virtualization?  
A hypervisor is responsible for managing multiple virtual machines (VMs) on a single physical machine by allocating hardware resources and providing isolation between VMs.  

### 4. What is a virtual machine (VM)?  
A virtual machine is a software emulation of a physical computer. It runs its own operating system (OS) and applications, independent of the underlying physical machine.  

### 5. What are the benefits of using virtual machines?  
- Efficient use of hardware resources  
- Isolation of systems and applications from the host machine  
- Easy to create backups and snapshots  
- Ability to run different OSes on the same machine  
- Portability, allowing VMs to be moved between different physical machines  

### 6. List five use cases of virtual machines.  
- Cloud services (e.g., AWS, Azure)  
- Testing and development of software in different environments  
- Cybersecurity research and sandboxing  
- Running legacy applications that require older OSes  
- Disaster recovery through VM backups  

### 7. In virtualization, what is the guest operating system?  
**b)** The operating system installed on a virtual machine  

### 8. What does virtual machine isolation mean?  
**c)** Virtual machines run independently and are isolated from each other and the host system. This ensures that the operation of one VM does not affect others or the host.  

### 9. What is the benefit of virtual machine portability?  
**c)** It allows virtual machines to be moved between different physical machines with compatible hypervisors, making it easier to migrate or scale VMs across infrastructure.  

### 10. What is the purpose of cloning a virtual machine?  
Cloning a VM creates an exact copy of it, which is useful for testing, deploying multiple identical systems, or creating backups for disaster recovery.
