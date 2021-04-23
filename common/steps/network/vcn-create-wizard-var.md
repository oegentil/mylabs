### ***Create your Virtual Cloud Network (VCN) and subnets***



Set up a VCN to connect your Linux instance to the internet. You will configure all the components needed to create your virtual network.

1. Open the navigation menu. Under Core Infrastructure, go to Networking and click Virtual Cloud Networks.

Ensure that a compartment (or the compartment designated for you) is selected in the Compartment list on the left.

2. Click **Start VCN Wizard**.

3. Select VCN with Internet Connectivity, and then click **Start VCN Wizard**.

4. Enter the following (sample values/descriptions are italicized):

 * **Name**: VNCName
 * **COMPARTMENT**: select the desired compartment
 * **VCN CIDR BLOCK**: VCNCDIRBlock
 * **PUBLIC SUBNET CIDR BLOCK**: PublicSubnetCIDR
 * **PRIVATE SUBNET CIDR BLOCK**: PrivateSubnetCIDR
 * **DNS RESOLUTION**: DNS_resolution

    Note: Notice the public and private subnets have different CIDR blocks.

4. Click Next. 

    The Create a VCN with Internet Connection configuration dialog will be displayed, confirming all the values you just entered and listing additional components that will be created.

5. Click **Create** to start the workflow.

6. After the workflow completes, click on **View Virtual Cloud Networks** and you will be directed to the details page of the VCN you created.