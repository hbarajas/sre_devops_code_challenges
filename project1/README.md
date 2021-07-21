Your task is the following:
● Create an API in Python that implements the specifications described below.
● Provision a machine and deploy your code into it using AWS.
● The machine should be reachable via port 80 and through the ELB called `default-elb`.
Ideally, we should be able to manage it via the same API you built.


API Specs:
 - The API should contain below endpoints:
   * /healthcheck
   * /elb/<elb_name>
   * 