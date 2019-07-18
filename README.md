# ocp-4-app-deployment-homework
Homework files repository for the July 15-19 OCP 4 App Deployment Bootcamp

# General Notes
- ${GUID} = d5ee

# Lab Env Notes
Create a public Git repository with your homework code.

MitziCom has a shared Nexus Artifact Repository deployed in the cluster.

The Service for Nexus is nexus3.gpte-hw-cicd.svc.cluster.local:8081/repository/all-maven-public

The public route for Nexus is http://nexus3-gpte-hw-cicd.apps.na311.openshift.opentlc.com

The Service for the Nexus Container Registry is https://nexus-registry.gpte-hw-cicd.svc.cluster.local:5000.

The public route for the Nexus Container Registry is https://nexus-registry-gpte-hw-cicd.apps.na311.openshift.opentlc.com

The User ID to access Nexus repositories and container registries is admin with password redhat.

MitziCom has a Shared SonarQube installation deployed in the Cluster.

The SonarQube service is sonarqube.gpte-hw-cicd.svc.cluster.local:9000.

The SonarQube public route is http://sonarqube-gpte-hw-cicd.apps.na311.openshift.opentlc.com

The UserID for SonarQube is also admin with password redhat - although you should not need to use credentials to analyze projects.