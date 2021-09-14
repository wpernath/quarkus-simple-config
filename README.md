# quarkus-simple-config
This is the manifest description and configuration of the [quarkus-simple](https://github.com/wpernath/quarkus-simple) application. It contains descriptions to create an ArgoApp and it contains the actual application manifest files for the Quarkus-Simple App in stages dev, stage and prod.

- `argo/`: Contains all the manifest files to create ArgoCD applications
- `config/`: Contains all the Kustomized manifests for the actual application itself

In order to use this example, have a look at the corresponding series **Automated Application Packaging and Distribution with OpenShift**  blog posts here:

- [Part one](https://www.opensourcerers.org/2021/04/26/automated-application-packaging-and-distribution-with-openshift-part-12/) talks about container images and explains all the basic files and gives you a guide through OpenShift Templates and Kustomize as a base technology for application packaging
- [Part two](https://www.opensourcerers.org/2021/05/24/automated-application-packaging-and-distribution-with-openshift-part-23/) provides an overview of the various packaging formats, namely Helm Charts and Kubernetes Operators, and explains how they differ from each other and how to create them
- [Part three](https://www.opensourcerers.org/2021/07/26/automated-application-packaging-and-distribution-with-openshift-tekton-pipelines-part-34-2/) gives you a detailed view of Tekton / OpenShift Pipelines and helps you to quickly start your CI/CD process
- [And finally part four](https://www.opensourcerers.org/2021/09/06/automated-application-packaging-and-distribution-with-openshift-gitops-and-argocd-part-44/), provides a detailed overview of GitOps and how to use it with OpenShift. 
