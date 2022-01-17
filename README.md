# Email-DNS
DNS stands for Domain Name System and is a protocol for exchanging data on the Internet and  which will convert IPs to Email address.
An email address is matched to a domain name (what follows the @), and this needs to be matched to an IP address to be able to send the data. So the mail server uses DNS to match the address on the ‘envelope’ to its destination, and deliver the email. Also, the public key needed to decode your DKIM signature can be accessed from the DNS. This is needed to verify your identity as a sender. Finally, DNS records can be used to publish an SPF (Sender Policy Framework) record to allow their email marketing software to send email on behalf of their clients.
We created this model in cisco packet tracer  and  We assign IPs to each PC and Server. It is required to keep IP in same network 
because here is connected network by single switch. There is no layer 3 device and VLAN. Then in mail servers we created the domain names for respective pc.
