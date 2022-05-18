# Attacking Kubernetes 
### A field guide for cloud ninjas and red teams
![image](https://user-images.githubusercontent.com/24460340/169073810-c0a06695-2f0f-492d-8283-a129b8e9ab3c.png)
 
Note: sorry this is sort of a dump of notes at the moment. Hopefully I will organize this eventually.
## Recon

## Initial Foothold
- Typosquatting
  - Create a malicious image in a public container registry with a name similar to a real image. The backdoor planted in your malicious image will allow you a foothold in the container
## Pod Enumeration
- env | grep KUBE
  - this should expose IP's and service ports `    
## Container Escape 

## Privilege Escalation

## Establish Persistence

### Sources 
- "Hacking Kubernetes: Threat Driven Analysis and defense" by Andew Martin and Michael Hausenblas
