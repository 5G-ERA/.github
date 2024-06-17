## 5G-ERA Connected robotics platform (CRoP)

### What is CRop?

An open-source platform for enhancing robotics integration with communication technologies like 5G. It enables seamless interaction between robots and their vertical applications across unstructured, multi-domain, multi-administration network environments hosted on cloud/edge devices (Cloud robotics). CRoP focuses on developing and orchestrating ROS1/2 framework applications, emphasizing dynamically on-demand deployment and comprehensive resource management.

[**Video: "CROP"**](https://www.youtube.com/watch?v=onze4jM2J0A)
![Preview](https://i1.ytimg.com/vi/onze4jM2J0A/maxresdefault.jpg)


### What are the problems CRop is solving for robots?

Robots applications are usually designed for estructured, industry enviroments, fix QoS and static network topoloy, single domain and single administration.
ROS is de-facto standard for robotics and the adopted DDS communication technology presents limitations for cloud robotics. Both TCP, used by ROS, and UDP multicast, used by ROS2's Data Distribution Service (DDS), operate at the transport layer and are susceptible to blocking across different network domains due to administrative or physical differences. This limits the deployment of ROS applications from research labs to real-world settings. 

### How does it work?

CRoP has two main components: Middleware and Relay. The middleware orchestrates the vertical network application deployments and relay enables the cloud communiation. For the full documentation of the project, please visit [documentation](https://github.com/5G-ERA/docs)


<p align="center">
  <img src="https://github.com/5G-ERA/.github/assets/26432703/4e1fe1b7-1e50-43a4-8a09-5a31dbaa0d7d" alt="description" width="500"/>
</p>

### CRoP License:

For the licensing information see [LICENSE](https://github.com/5G-ERA/middleware/blob/main/LICENSE).

### Reference:

Visit the 5G ERA project website for more information.
https://5g-era.eu 

*The 5G-ERA project was developed by the following partners under the [consortium](https://5g-era.eu/consortium/) with funding of the European Union's Horizon 2020 Research and Innovation programme under grant agreement No. 101016681.*

For workshops demostrations and tutorials visit our [Youtube Channel](https://www.youtube.com/channel/UCFn5FI9OYLA9_jTwl2cwdFA/videos )



