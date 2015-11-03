Goals

In this stage, collect additional data points for each application in the Alpha or Beta phase. Note: only one phase is done at a time.

Process

For each application in the phase, collect the following:

The application goal as it relates to the migration.

For example, this might read: "Replicate the production back-end database into the cloud environment so that development efforts can be supported without connecting the production database). Work with the partner agency to determine this goal.

Determine ownership

It's important to determine the ownership of each application. This step basically identifies the team that's responsible for each of the applications.

Who is current in charge of:

application development
infrastructure
architecture
testing
security
monitoring
compliance
the change management process
the business (who's the business owner for the application)
Determine the timeline

It's important to know if there are any key milestones coming up for the application (such as upcoming releases).

Investigate the application architecture

Goal

Learn more details about the application architecture, it's data flow, and how it interacts with other components.

Questions

What software stack does the application use?
What database(s) does the application use?
Are there any shared services (like active directory) that the application connects to?
Deliverables

Diagram the data flow through the application.

Security bounds

Goal

We determine the 'security enclave' that the application runs under.

Process

Meet with the security and infrastructure team to determine what security environment an application runs under.

Questions

What sorts of networks does the application access (e.g. public, VPN)?
Does it run in a physical datacenter?
What machine images are used?
Deliverable

Document the security of the application - paying special attention to any security properties it might inherit from it's physical environment, or from the machine image (for example).

Understand the change management process

Goal

Understand the current change management process for the application.

Process

Sit down with the application team (developers, security, infrastructure) to understand the process to change the application in production.

Deliverables

Draw a diagram detailing the steps to make a production change.
