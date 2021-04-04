# Infastructure as Code - IaC
## About me
- **My Name**: Audel Diaz
- **Role**: Software and DevOps Engineer
- **LinkedIn**: https://www.linkedin.com/in/audeldiaz/

## Defining Infrastructure as Code?
*Infrastructure as code (IaC) means to manage your IT infrastructure using configuration files.*

## The Pain of Managing IT Infrastructure
### Bare Metal Problems:
- Too costly
- Scalability and Availability
- Monitoring and Performance visibility
- Inconsistency

### Cloud Computing Problems
- Inconsistency

## IaC Benefits
- Speed
- Consistency
- Accountability
- Lower cost

## How Does IaC Work?
### Imperative
Defines a sequece of commands or instructions so the infrastructure can reach the final result.
### Declarative
Instead of explicitly outlining the sequence of steps the infrastructure needs to reach the final result, the declarative approach shows what the final result looks like.

## Some Best Practices
- **Make code your single source of truth**: You should explicitly code all the infrastructure specifications in configuration files. Your configuration files should be the single source of truth for all your infrastructure management concerns.

- **Version control all of your configuration files**: This probably should go without saying, but put all of your config files under source control.

- **Use little documentation (or none at all) for your infrastructure specifications**: This point is the logical consequence of the first one. Since your config files should be your single source of truth, there should be no need for more documentation. External documentation can easily get out of sync with the real configurations, but that won’t happen with the config files.
- **Test and Monitor Your Configurations**: IaC is code, and like all code, it can be tested. So test it you should! By employing testing and monitoring tools for IaC, you can check for errors and inconsistencies in your servers before you deploy them to production.

## Lab Time
### Requirements
- Linux or Mac Machine / VM
- Ansible

Resources:
- This repository: https://github.com/AudelDiaz/6_sysadmin_tasks
- Swarm Cluster Demo: https://github.com/AudelDiaz/vagrant-swarm-cluster

References:
- What Is Infrastructure as Code? How It Works, Best Practices, Carlos Shults, 2019: https://stackify.com/what-is-infrastructure-as-code-how-it-works-best-practices-tutorials/
- Infrastructure as Code, Wikipedia: https://en.wikipedia.org/wiki/Infrastructure_as_code