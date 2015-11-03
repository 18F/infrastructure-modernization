# Architect

The goal of this phase is to start thinking about the architecture of the applications (in each phase) that are going to migrate to the cloud. Do this step twice, once for the Alpha phase, and once for the Beta phase.

## Determine list of services

### Goal

For each application, determine the list of services it will need access to in the cloud environment.

### Process

Here we're determining the ecosystem that needs to support the application when it's in the cloud environment.

Sit down with the developers and infrastructure team to workshop through the answers for each application.

### Questions

  * Does the team need a jump box?
  * Does the team need a continuous integration server?
  * Are there any firewalls that need to be put into the place? Or crossed?
  * Might the application need access to an single sign on service (like active directory)?

### Deliverables

For each application, enumerate the list of tools and services in the ecosystem of the application. These tools and services help determine a healthy environment for the application.

## Architect the application for the cloud

### Goal

Figure out the architecture of the application in the cloud.

### Process

  * Determine the network/data topology
  * Determine the security boundaries

### Deliverables

A complete diagram of the application as it exists in the cloud provider. Most often, this will be Amazon Web Services. The diagram must also have explanations of all decisions.

## Determine common configurations and components

Common components of the cloud infrastructure will likely become the responsibility of the DevOps team as opposed to the specific application team.

### Goal

Determine the common components of the cloud infrastructure.

### Questions, some *examples* to ask: 

  * Does everything need to be routed through the Trusted Internet Connection (TIC)?
  * Does everything need to be routed through a VPN?
  * Does the application have the need for in/outbound traffic?

### Process

Look across the applications in the Alpha phase, are there any common components?

### Deliverable

The common architecture components express as a layered diagram. Each diagram will be accompanied with an explanation of any design decisions made.

Roles and responsibilities for common components

### Goal

For each layer of the common architecture, figure out the roles and responsibilities through the team for that layer.

### Questions

  * Who's in charge of the master account?
  * Who's responsible for monitoring the logs?
  * Who's monitoring the financials?
  * Who's provisioning?
  * Who's creating images?
  * Who's turning off unused resources?
  * Who's responsible for backups?

### Process

  * Go through each layer to determine responsibilities. Ask questions, such as above.

### Deliverables

  * A roles and responsibilities matrix for each layer.
