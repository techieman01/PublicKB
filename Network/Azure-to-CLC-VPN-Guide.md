{{{
  "title": "Azure to CenturyLink Cloud VPN Guide",
  "date": "01-30-2019",
  "author": "Thomas Houser",
  "attachments": [],
  "contentIsHTML": false,
  "sticky": false
}}}

### Overview
You can connect your Azure VNET to CenturyLink Cloud networks by using a IPSEC VPN connection. The following steps guide you on how to use the Azure portal to configure Azure VNET.

### Prereqisites 
*Must have Account Administrator permissions on the platform

*Listing of the cloud network(s) you wish to connect to across your tunnel

*The make, model, and code version of the endpoint device you'll be terminating to

*Static IP of the peering interface on your device

*The network blocks you wish to have be reached on your end of the tunnel - these must be private IP blocks (RFC-1918)

*You must have resources (server and a network) provisioned for the account and the Cloud data center you wish to connect to.

### Note the following items are not covered by Portal Self-Service VPN:
*IPSEC IKEv2 VPN - setup must be done as a Service Task per this link - https://www.ctl.io/service-tasks/#vpn-tunnels-deployment

*NAT requirement (for example an IPSEC peer device behind a NAT device on the customer network)

*Failover capabilities (redundant vpn or failover devices/tunnels)

*Use of NON RFC1918 address spaces

*Integration with other customized Century Link products (IE direct-connect)

### Portal Self Service VPN Setup Process

If you would like to setup IPSEC IKEv1 and configure it via the Self Service Portal, you can follow the guide below to configure a site-to-site IPSEC IKEv1 VPN between Azure and the CenturyLink Cloud using the self-service portal.

If you would like to use IKEv1, you can follow the guide below to configure site-to-site VPN between Azure and CenturyLink Cloud using self-service.

1.	You can follow Azure VPN documentation to configure VPN on their end. Once this is completed proceed to step 2.
2.	Follow this guide to setup an IPSEC VPN tunnel from the CenturyLink side: https://www.ctl.io/knowledge-base/network/creating-a-self-service-ipsec-site-to-site-vpn-tunnel/

### Custom VPN Setup Process

If a custom VPN better fits your specific IPSEC VPN requirements, create a request as outlined below.

To create a custom VPN Century Link will need specific details about your IPSEC VPN configuration. 

1. Please create a request by emailing help@ctl.io and note you wish to setup a custom VPN as a Service Task, and request the custom VPN worksheet be sent via email.
2. Complete and email the custom VPN worksheet template to help@ctl.io with the required details.
3. Century Link will work with you via the ticket to implement the custom VPN service task item.

