# Base Service for the BPF (Bundle Protocol Framework) 

## General
### About
This is a project made by (or partially by) WSN-Team 2012 in the course CSD, which is part of the [Technology Transfer Alliance](http://ttaportal.org/).
### Purpose
One of the goals of the project is to be able to send data upstream from rural areas and to do this DTN communication has been used.
One of the main goals of the project was to provide a platform independent solution for DTN communication. This was achieved by developing the BPF (Bundle Protocol Framework). The BPF cannot work on its own. It needs to be implemented with a application/service, which is device specific. This project, BPF-Base-Service, is an example of such a service.
### Description
This project is a service implementing the BPF and providing the basic functionalities for DTN communication. It implements the platform-dependent classes of the BPF. This service is based on a Linux environment.

## Build & Install
### Prerequisites
You will need to have ant to compile this in an easy way. To get ant look into how to install it on your platform.

### Building
The BPF is included as a submodule and it is built automatically when building the service. It is possible to configure several settings in the configuration file.
Follow the below steps to build service and BPF.

1.  `git clone https://github.com/WSN-2012/BPF-Base-Service.git`
2.  `cd BPF-Base-Service`
3.  `git submodule init`
4.  `git submodule update`
5.  change config file config/dtn.config.xml
3.  `ant`