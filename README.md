# Purpose
Documentation of a plan to take an agency into using a cloud-based infrastructure.

# Overall Approach
The cloud migration is broken down into four major phases:

1. Discovery: The goal is to inventory the applications and services the agency wants to migrate.

2. Alpha: This phase focuses on easy, demonstrable migrations. The goal is to choose applications and services that are easy to migrate.

  * [Post Alpha retrospective](https://github.com/18F/infrastructure-modernization/wiki/alpha-retro)
  * [Metrics workshop](https://github.com/18F/infrastructure-modernization/wiki/metrics-workshop)

3. Beta: This phase focuses on the cost to footprint ratio. The goal is to migrate (in order) simple applications with significant running costs.

  * Post-Beta metrics baseline

4. Live: The system graduates to production status, and the focus shifts to improving key performance metrics. Deploying applications into the cloud is now normal operating procedure.

# Three Key Stages
Each of the active migration phases `alpha`, `beta`, and `Live` requires execution of three key activities:

  * [Prepare](./Prepare/README.md)

  * [Architect](./Architect/README.md)

  * [Deploy](./Deploy/README.md)
