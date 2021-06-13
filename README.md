There are broadly known three layers of clouds; 
1.	Infrastructure as a Service -IaaS-, 
2.	Software as a Service -SaaS-,
3.	Platform as a Service -PaaS-
To be clear about understanding of the Among these three layers, IaaS systems (e.g., AWS,Azure,GCloud,DigitalOcean,Linode) offer fundamental infrastructure configurations and tools like VMs and virtual storages, and these have got the most recognition from the IT market. [4]. 
Either we focus SaaS or IaaS, we must organize and automate our works and applications on the servers, especially on the cloud based organizations.
Therefore updating, managing, creating basically configurating the whole infrastructure means a lot of hardwork and that means more money and time to consume. 
To achieve effectivity on time, budget and human sources we focused on Immutable Infrastructure services to achieve managing VMIs and systems by using Hashicorp Packer to automate and clarify all these steps of IaC and we will examine all these layers and their problems in this paper. 
1.1.	Problem Statement
When we try to deploy a series of apps, configurations and services for a certain aim on an instance of a virtual image, it will take longer time to make it ready for work and do exact setting of our desired purpose. 
We, developers always want to automate the system so DevOps teams can easily maintain and alter each time we need to be interact with our servers.[5]
On DevOps[1]; software codes emerging as an automation is called as Infrastructure-as-Code (IaC). Infrastructure-as-Code means; promoting managing the information and late works inside re-usable scripts of IaC rather than old-school reserving it for the vast amount of work for developers, which makes the process quite slow, time and money wasting, and generally open to make errors [2].
Traditional mutable server infrastructure needs to be continually updated and altered for each configurations. That means developers must work with this the infrastructure and make secure shell into their servers -either upgrade or downgrade- packages one by one manually, change configuration files on a server by working for each (an infrustructure can have hundereds of servers) and deploy new set of code onto existing servers. Whole these configurations means that this servers servers are changeable (mutable) so they can be altered after they’re created. [7]
8 
However we need to eliminate this process and make autonomous. Therefore we resort to the Immutable Infrustructures which means kill the server if you want to make a change. To reduce the time for creating and configuring machine images we need to develop complex infrastructure and modify each time whenever we needs an update. 
