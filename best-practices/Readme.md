# Best Practices Guidance

## Cluster Configuration

### Multi-tenancy
- In ARO - every setup consists of 3 master nodes, apart from worker nodes 
- Application can be isolated inside the same cluster through namespaces
- Worker nodes can be isolated using Machinesets
- There is a single point of Ingress and Egress as only one SLB is created

## Network and Security

### North South 

- Leverage current investments in firewall and other shared perimeter security solutions
- Use Azure Well Architected Framework best practices around Hub and Spoke model
- Use Private ingress for application access and expose it via WAF/firewall/etc. 
- Use Landing Zones as per best practices"

### East West

Use Network Policies to restrict traffic inside the cluster
Enable grouping of application components via namespaces and labels
Define network policies based on labels
Enable Source Control and DevOps for implementing Network Policies"


### DNS
### IP Address
### Ingress
### Egress

## Access Control	

### RBAC Rules
### LDAP Integration

## Management and Monitoring	

### Patching

### Scaling

### Upgrade
