# All about AWS

1) AWS Regions are separate geographic areas that AWS uses to house its infrastructure. These are distributed around the world so that customers can choose a region closest to them in order to host their cloud infrastructure there. The closer your region is to you, the better, so that you can reduce network latency as much as possible for your end-users. You want to be near the data centers for fast service.

2) Not all regions are created equally. These regions have more services than others in their general areas:
    Americas: US East (N. Virginia), US West (N. California)
    Asia Pacific:  Singapore, Sydney, Tokyo
    EU: Frankfurt, Ireland

3) In general, try to follow these best practices when you choose a region, to help ensure top performance and resilience:
    Proximity: Choose a region closest to your location and your customers’ location to optimize network latency.

    Services: Try and think about what are your most needed services. Usually, the newest services start on a few main regions then pop up in other regions later.

    Cost: Certain regions will cost more than others, so use built-in AWS calculators to do rough cost estimates to inform your choices.
    
    Service Level Agreement (SLA): Just as with cost, your SLA details will vary by region, so be sure to be aware of what your needs are and if they’re being met.
    
    Compliance: You may need to meet regulatory compliance needs such as GDPR by hosting your deployment in a specific — or multiple regions.

4) When you own the infrastructure, it's easy to understand how you interact with it because you can see it, touch it and work
with it on every level. If I have a server that I've stood up in my closet, interacting with that server is easy because it's mine. I can touch it.

5) When I remove the ability for me to touch and see something, when the infrastructure becomes virtual, the way that I work with that infrastructure has to change a bit. Instead of physically managing my infrastructure, I now logically manage it through the AWS application programming interface or API. So now when I create, delete or change any AWS resource, whether it's a virtual server or a storage system for employee photos, I use API calls to AWS to do that. You can make these API calls in several ways but the three main ways we're going to talk about are the AWS Management Console, the AWS Command Line Interface and the AWS Software Development Kits or SDKs.

# Shared Responsibility model in AWS

## AWS Responsibility                                                   

### Infrastructure services
AWS manages the infrastructure and foundation services.               


### Container services
AWS manages the infrastructure and foundation services, operating system, and application platform.


### Abstracted services
AWS operates the infrastructure layer, operating system, and platforms, as well as server-side encryption and data protection.


## Customer Responsibility                                                   

### Infrastructure services
You control the operating system and application platform, as well as encrypting, protecting, and managing customer data           


### Container services
You are responsible for customer data, encrypting that data, and protecting it through network firewalls and backups


### Abstracted services
You are responsible for managing customer data and protecting it through client-side encryption.




