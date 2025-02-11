# Introductions
Organizations often struggle with a variety of circumstances that can impact productivity within the teams (high cognitive load, lack of standardization, domain knowledge fragmentation). 
This could result in inefficient or reduced Productivity, higher maintenance costs and/or security vulnerabilities.

Red Hat provides the tools and know-how to help "The Providers" (The Platform Engineers) to create "The Product" (their custom IDP) based on the needs of "The Customers" (all Development Teams within the organization).


This roadshow is meant for Platform Engineers who are in charge of 

* creating standard technologies that can be used in all environments (Development, Testing, Production), and
* defining processes and ensure they are maximizing the time and resources for Development Teams.

Development Teams who are  in charge of creating a software solution and empower (traditionally speaking) in picking their own tools for coding, building, deploying, running, monitoring and documentation may also benefit from this.



# What attendees will  learn:

* Understand the need to implement Platform Engineering disciplines in their organization and see the clearly benefits of improving the Developer Productivity
* How to design a Thinest Viable Platform (TVP) based on the needs of ALL development teams in the organization and ensure they are highly productive as possible
* Constantly assessing the investment into their own IDP and understand how they can enhance and convince ALL development teams to start adopting
* See how Red Hat can help as a partner in your Platform Engineering journey



# Running this workshop in your OpenShift environment

Run the ansible playbook form the `ansible` repo
```
git clone https://github.com/redhat-pe-workshop/ansible
cd ansible
ansible-playbook playbooks/ocp4_workload_platform_engineering_workshop.yml -e ACTION=create
```
