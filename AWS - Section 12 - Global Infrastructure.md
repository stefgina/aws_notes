#########
Route53 (DNS)

basic records:
![](imgs/dns.png)

Basics of DNS work:
![](imgs/basics-dns.png)


Routing policies:
Simple routing policy (no health checks)
Weighted routing policy (distribute traffic based on weighting, like loadballancing) healthcheck
latency routing policy (will look where the user is located and set the closest ip) healthcheck
failover routing policy (dns does healthcheck and in case of disaster goes to other instance)


#######
CloudFront

Caches requests, for the next user not to wait the full route.

Content Delivery Network (CDN)
Improves read performance, content is cached at the edge
216 points globally
Ddos protection naturally 

Origins: 
S3 buckets
Custom Origin (HTTP,ec2,s3 website)

#######
S3 Transfer Acceleration




 