## **Configure Security List to allow inbound connections**

Create a rule in a the default security list that will allow 

1. Click View Virtual Cloud Network to view your new VCN.
2. With your new VCN displayed, click on your Public subnet link.

    The public subnet information is displayed with the Security Lists at the bottom of the page. There should be a link to the Default Security List for your VCN.
3. Click the **Default Security List** link.
    
    The default Ingress Rules for your VCN are displayed.
4. Click Add Ingress Rules.

    An **Add Ingress Rules** dialog is displayed.

5. Enter the following (descriptions are italicized. replace with the values for your scenario):

| Field | Value |
| --- | --- |
| Stateless: | Checked |
| Source Type: | CIDR | 
| Source CIDR: | 0.0.0.0/0 |
| IP Protocol: | TCP |
| Source port range: | (leave-blank) |
| Destination Port Range: | 80 |
| Description: | Allow HTTP connections |
        
Once you click Add Ingress Rule, HTTP connections are allowed. Your VCN is configured for Apache server.