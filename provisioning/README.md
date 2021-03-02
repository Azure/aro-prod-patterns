### ARO Deployment for Private Cluster


Specilaist: I think we are the lead in this compete with HCI against Openshift and Tanzu
Me: Why do yu think that?
Specialist: Because we are the leader of hybrid


- Sounds very innovated, but in reality it's just Google delivering a very opinated Kubernetes stack with their technologies. Smart of them to keep pushing the lockin to make Kubernetes sticky in GCP.

- Customers are going to have a fit with the cost. 

- I'm not sure that Enterprise customers will be able to adopt it, as there's a lot of pre-configured pieces that an Enterprise would want control over. Every customer says they want a fully managed service, but really what they want is a fully managed service that is on their terms.

- Probably as great platform for startups and mid sized companies

- Doesn't support Istio, so why would I ever want to use this :)

Couple other things I noticed in the limitations sections....

- No Privledged pods
- No support for container threat detection
- Only supports approved monitoring tools
- Pods or in QoS , so a pod will have the same request and limit
- No support for Gatekeeper or mutating webhooks