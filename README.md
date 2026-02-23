# L2-Segmentation-Security
Logical Segmentation: Created a segmented network for 15 end-devices using a Cisco 2950-24 switch to simulate a corporate departmental environment.

Departmental Isolation: Configured three distinct VLANs to separate IT (VLAN 5), Sales (VLAN 12), and HR (VLAN 10).

Objective: To enhance network performance by reducing broadcast domains and improving security by preventing unauthorized inter-departmental access.

Implemented a 172.16.x.0/24 addressing scheme where the third octet corresponds to the VLAN ID for administrative clarity.

Security & Performance.
Access Layer Security: Utilized Layer 2 segmentation to mitigate the risk of lateral movement between sensitive departments like HR and IT.

Traffic Optimization: Successfully isolated broadcast traffic within each department.

Department - VLAN ID , Subnet - Port Range

IT Dept - 5 ,172.16.5.0/24 - Fa0/1 - 5.

HR Dept - 10,172.16.10.0/24 - Fa0/12 - 16.

Sales Dept - 12,172.16.12.0/24 - Fa0/6 - 11.
