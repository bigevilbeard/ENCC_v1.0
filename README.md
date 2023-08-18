# Designing and Implementing Cloud Connectivity v1.0 (300-440) Exam Study 

Useful Documents for 300-440 ENCC v1.0

For the Designing and Implementing Cloud Connectivity v1.0 (ENCC 300-440) exam, the following AWS, Azure, and Google Cloud resources will aid anyone studying for the exam. These resources can also be beneficial for other exams within the Cisco Multicloud Specialist Certifications.

## Exam Topics 

### 1.0 Architecture Models (15%)

#### 1.1 Internet-based connectivity to cloud providers

##### 1.1.a Native IPsec

Relevant Resources:

- [Cisco ASA Site-to-Site VPN](https://www.cisco.com/c/en/us/support/docs/security/asa-5500-x-series-firewalls/215884-configure-a-site-to-site-vpn-tunnel-with.html)
- [Security for VPNs with IPsec Configuration Guide, Cisco IOS XE ](https://www.cisco.com/c/en/us/td/docs/ios-xml/ios/sec_conn_vpnips/configuration/xe-16-12/sec-sec-for-vpns-w-ipsec-xe-16-12-book/sec-cfg-vpn-ipsec.html)
- [AWS Site-to-Site VPN](https://docs.aws.amazon.com/vpn/latest/s2svpn/VPC_VPN.html)  
- [Azure VPN Gateway Overview]([https://docs.microsoft.com/en-us/azure/vpn-gateway/vpn-gateway-about-vnet-to-vnet-connectivity](https://learn.microsoft.com/en-us/azure/vpn-gateway/vpn-gateway-about-vpngateways)) 
- [Google Cloud VPN Overview](https://cloud.google.com/network-connectivity/docs/vpn/concepts/overview)
- [SAFE Secure Cloud Architecture Guide](https://www.cisco.com/c/en/us/solutions/collateral/enterprise/design-zone-security/safe-secure-cloud-architecture-guide.html) 
- [Enterprise Core ENCOR 350-401 and Advanced Routing ENARSI 300-410 Official Cert Guide Library](https://www.ciscopress.com/store/ccnp-enterprise-core-encor-350-401-and-advanced-routing-9781587147111)

##### 1.1.b Cisco SD-WAN internet connectivity  

Relevant Resources:

- [Cisco SD-WAN Design Guide](https://www.cisco.com/c/en/us/solutions/collateral/enterprise-networks/intelligent-wan-iwan/design-guide-c07-739736.html)
- [Cisco SD-WAN: Secure and Optimize Cloud-Enabled Branch](https://www.ciscopress.com/store/cisco-sd-wan-secure-and-optimize-cloud-enabled-branch-9780137148582)
- [AWS Site-to-Site VPN](https://docs.aws.amazon.com/vpn/latest/s2svpn/VPC_VPN.html)  
- [Google Cloud VPN Overview](https://cloud.google.com/network-connectivity/docs/vpn/concepts/overview)
- [Azure VPN Gateway Overview]([https://docs.microsoft.com/en-us/azure/vpn-gateway/vpn-gateway-about-vnet-to-vnet-connectivity](https://learn.microsoft.com/en-us/azure/vpn-gateway/vpn-gateway-about-vpngateways)) 

#### 1.2 Private connectivity to cloud providers  

##### 1.2.a MPLS provider
##### 1.2.b Colocation provider
##### 1.2.c SDCI regional cross-connect 

Relevant Resources:

- [Cisco Cloud OnRamp for Colocation](https://www.cisco.com/c/dam/en/us/products/collateral/routers/cloud-services-router-1000v-series/cloud-onramp-colo-deployment-guide.pdf) 
- [Cisco Cloud OnRamp for MPLS](https://www.cisco.com/c/dam/en/us/products/collateral/routers/cloud-services-router-1000v-series/cloud-onramp-mpls-deployment-guide.pdf)
- [AWS Direct Connect User Guide](https://docs.aws.amazon.com/directconnect/latest/UserGuide/Welcome.html)
- [Azure ExpressRoute Overview](https://docs.microsoft.com/en-us/azure/expressroute/expressroute-introduction)
- [Google Cloud Interconnect Overview](https://cloud.google.com/network-connectivity/docs/interconnect/concepts/overview)
- [Cisco Cloud Infrastructure](https://www.ciscopress.com/store/cisco-cloud-infrastructure-9780137690121)
- [Enterprise Core ENCOR 350-401 and Advanced Routing ENARSI 300-410 Official Cert Guide Library](https://www.ciscopress.com/store/ccnp-enterprise-core-encor-350-401-and-advanced-routing-9781587147111)

#### 1.3 Connectivity to SaaS cloud providers

##### 1.3.a Direct internet access models into SaaS  
##### 1.3.b Indirect access models via a Cloud Security Provider
##### 1.3.c SaaS connectivity via a centralized internet gateway
##### 1.3.d Dedicated connectivity to a SaaS provider  

Relevant Resources: 

- [Cisco SD-WAN Design Guide](https://www.cisco.com/c/dam/en/us/td/docs/solutions/CVD/SDWAN/CVD-SD-WAN-Design-2018OCT.pdf)  
- [AWS Direct Connect User Guide](https://docs.aws.amazon.com/directconnect/latest/UserGuide/Welcome.html)
- [Azure ExpressRoute Overview](https://docs.microsoft.com/en-us/azure/expressroute/expressroute-introduction)
- [Google Cloud Interconnect Overview](https://cloud.google.com/network-connectivity/docs/interconnect/concepts/overview)

### 2.0 Design (15%)

#### 2.1 Recommend connectivity model for HA, resiliency, SLAs, reliability

#### 2.2 Recommend connectivity model based on bandwidth, QoS, dedicated vs shared, multi-homing, routing  

#### 2.3 Recommend connectivity model for regulatory compliance (NIST, FEDRAMP, ISO)

#### 2.4 Describe cloud-native security policies (AWS, Azure, Google Cloud) 

Relevant Resources:

- [AWS Transit Gateway Guide](https://docs.aws.amazon.com/transit-gateway/latest/tgw-ug/what-is-transit-gateway.html) 
- [Azure Virtual Network Integration](https://learn.microsoft.com/en-us/azure/app-service/overview-vnet-integration)
- [Google Cloud Networks Overview](https://cloud.google.com/vpc/docs/vpc)  
- [Cisco Cloud Infrastructure](https://www.ciscopress.com/store/cisco-cloud-infrastructure-9780137690121)
- [Enterprise Core ENCOR 350-401 and Advanced Routing ENARSI 300-410 Official Cert Guide Library](https://www.ciscopress.com/store/ccnp-enterprise-core-encor-350-401-and-advanced-routing-9781587147111)

### 3.0 IPsec Cloud Connectivity (25%)   

#### 3.1 Configure IPsec to cloud endpoint

#### 3.2 Configure IPsec between on-prem and cloud-hosted routers

#### 3.3 Configure routing with BGP and OSPF

Relevant Resources:

- [AWS Site-to-Site VPN](https://docs.aws.amazon.com/vpn/latest/s2svpn/VPC_VPN.html)
- [Azure VPN Gateway](https://docs.microsoft.com/en-us/azure/vpn-gateway/vpn-gateway-about-vnet-to-vnet-connectivity) 
- [Google Cloud VPN](https://cloud.google.com/network-connectivity/docs/vpn/overview)  
- [AWS Route Tables](https://docs.aws.amazon.com/vpc/latest/userguide/VPC_Route_Tables.html)
- [Azure Virtual Network Integration](https://learn.microsoft.com/en-us/azure/app-service/overview-vnet-integration)
- [VPC firewall rules](https://cloud.google.com/firewall/docs/firewalls)
- [Cisco Cloud Infrastructure](https://www.ciscopress.com/store/cisco-cloud-infrastructure-9780137690121)
- [Enterprise Core ENCOR 350-401 and Advanced Routing ENARSI 300-410 Official Cert Guide Library](https://www.ciscopress.com/store/ccnp-enterprise-core-encor-350-401-and-advanced-routing-9781587147111)

### 4.0 SD-WAN Cloud Connectivity (25%)

#### 4.1 Configure SD-WAN to cloud providers  

#### 4.2 Configure SD-WAN OnRamp to SaaS

#### 4.3 Configure SD-WAN policies (security, routing, application)

Relevant Resources:

- [Cisco Software-Defined Wide Area Networks: Designing, Deploying and Securing Your Next Generation WAN with Cisco SD-WAN](https://www.ciscopress.com/store/cisco-software-defined-wide-area-networks-designing-9780136533177)
- [Cisco SD-WAN Policies](https://learningnetwork.cisco.com/s/article/cisco-sd-wan-policy)
- [Cisco SD-WAN Design Guide](https://www.cisco.com/c/dam/en/us/td/docs/solutions/CVD/SDWAN/CVD-SD-WAN-Design-2018OCT.pdf)  
- [AWS Site-to-Site VPN](https://docs.aws.amazon.com/vpn/latest/s2svpn/VPC_VPN.html)
- [Azure VPN Gateway](https://docs.microsoft.com/en-us/azure/vpn-gateway/vpn-gateway-about-vnet-to-vnet-connectivity) 
- [Google Cloud VPN](https://cloud.google.com/network-connectivity/docs/vpn/overview)  
- [Cisco Cloud Infrastructure](https://www.ciscopress.com/store/cisco-cloud-infrastructure-9780137690121)
- [Enterprise Core ENCOR 350-401 and Advanced Routing ENARSI 300-410 Official Cert Guide Library](https://www.ciscopress.com/store/ccnp-enterprise-core-encor-350-401-and-advanced-routing-9781587147111)

### 5.0 Operation (20%)  

#### 5.1 Diagnose IPsec connectivity issues

#### 5.2 Diagnose routing issues 

#### 5.3 Diagnose SD-WAN connectivity issues  

#### 5.4 Diagnose SD-WAN policy issues

Relevant Resources:

- [Cisco SD-WAN Troubleshooting Tech Notes](https://www.cisco.com/c/en/us/support/routers/sd-wan/products-tech-notes-list.html) 
- [AWS VPN Troubleshooting](https://docs.aws.amazon.com/vpn/latest/s2svpn/Troubleshooting.html)
- [Azure VPN Troubleshooting](https://docs.microsoft.com/en-us/azure/vpn-gateway/vpn-gateway-troubleshoot)
- [Google Cloud VPN Troubleshooting](https://cloud.google.com/network-connectivity/docs/vpn/support/troubleshooting)
- [Cisco Cloud Infrastructure](https://www.ciscopress.com/store/cisco-cloud-infrastructure-9780137690121)
- [Enterprise Core ENCOR 350-401 and Advanced Routing ENARSI 300-410 Official Cert Guide Library](https://www.ciscopress.com/store/ccnp-enterprise-core-encor-350-401-and-advanced-routing-9781587147111)
