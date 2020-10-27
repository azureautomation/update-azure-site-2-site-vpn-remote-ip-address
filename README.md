Update Azure Site 2 Site VPN Remote IP Address
==============================================

            

**Update Azure Site 2 Site VPN Remote IP Address**

This Script will Download the current Virtual Network Configuration from Azure.

(You must first have connected to your Azure Subscription).

Then it will look up your current Gateway IP Address and detect if there has been any change compared to what is in Azure Site to Site VPN configuration.

This is particularly useful for Home Labs, where your WAN IP address may change over time.

The config will then be uploaded back to Azure and your S2S VPN should connect again.


You will also need this other script to detect your WAN IP Address:


[http://gallery.technet.microsoft.com/scriptcenter/Discover-your-WAN-IP-2d7b70e1](http://gallery.technet.microsoft.com/scriptcenter/Discover-your-WAN-IP-2d7b70e1)

 







Update Azure Site to Site VPN WAN Ip address in Azure




[https://gallery.technet.microsoft.com/scriptcenter/Update-Azure-2-VPN-Remote-765c12f2](https://gallery.technet.microsoft.com/scriptcenter/Update-Azure-2-VPN-Remote-765c12f2)






Update Azure Site to Site VPN Secret in RRAS




[https://gallery.technet.microsoft.com/scriptcenter/Update-Azure-S2S-vpn-7127f27b](https://gallery.technet.microsoft.com/scriptcenter/Update-Azure-S2S-vpn-7127f27b)







** *** *

 

 



        
    
TechNet gallery is retiring! This script was migrated from TechNet script center to GitHub by Microsoft Azure Automation product group. All the Script Center fields like Rating, RatingCount and DownloadCount have been carried over to Github as-is for the migrated scripts only. Note : The Script Center fields will not be applicable for the new repositories created in Github & hence those fields will not show up for new Github repositories.
