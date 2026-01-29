<h2> Taylor's Homelab Project </h2>
 Documentation and journal into my Homelab project and the progress I've made
 
 Started 1/25/2026



## Equipment and Specs

| Machine 1                  | Dell OptiPlex 7050      |
|----------------------------|-------------------------|
| **OS**                     | ProxMox VE 9.1.4        |
| **LXC**                    | Debian GNU 12 (Bookworm)|
| **Motherboard**            | NW6H5                   |
| **CPU**                    | 8xIntel i7-7700         | 
| **RAM**                    | 8 GB DDR4               |
| **GPU**                    | AMD Radeon HD 8830M     |
| **HDD**                    | 2x 1 TB HDDs            |

| Machine 2                  |                    |
|----------------------------|--------------------|
| **OS**                     | ProxMox HyperVisor |
| **Motherboard**            |                    |
| **CPU**                    |                    | 
| **RAM**                    |                    |
| **GPU**                    |                    |
| **HDD**                    |                    |

| Switch                     | Dell x1026         |
|----------------------------|--------------------|




## 1/25/2026
Wiped the hard drives off of Machine 1, reinstalled the ProxMox 9.1.4 ISO to begin setting up a ProxMox Hypervisor setup. 

Plugged ethernet from access port into Dell x1026, both machines got CAT 6a patch panel cables from the Dell x1026. 

Went through ProxMox setup and created a Prox Enviroment. Connected from seperate PC to the Web UI. Created a LXC with Debian 12 (Bookworm)

and assigned the LXC with 4 cores of CPU, 4 GB of ram and 27 GB of storage. Plans to upgrade in future, just testing for now. 

Used console in LXC to install Docker daemon. Created a directory for Movie / TV storage. 

Installed Jellyfin and Jellyseerr onto LXC. Ran through setup and created a library and a connection for both. 

## 1/28/2026
