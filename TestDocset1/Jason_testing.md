  - **Port Mirrored Domain Controllers (FQDN)** (required for the ATA Gateway, this cannot be changed for the ATA Lightweight Gateway): Enter the complete FQDN of your domain controller and click the plus sign to add it to the list. For example,  **dc01.contoso.com** 

        The following information applies to the servers you enter in the **Domain Controllers** list: 

        - All domain controllers whose traffic is being monitored via port mirroring by the ATA Gateway must be listed in the **Domain Controllers** list. If a domain controller is not listed in the **Domain Controllers** list, detection of suspicious activities might not function as expected. 
        - At least one domain controller in the list should be a global catalog. This will enable ATA to resolve computer and user objects in other domains in the forest. 
