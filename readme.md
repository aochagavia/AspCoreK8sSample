# AspCoreK8Sample

This repository shows a minimal ASP Core MVC application meant to run as a kubernetes pod.
It has been initialized using `dotnet new mvc` and slightly modified to be deployable to a
kubernetes cluster.

It is able to:

* TODO: Persist data protection keys (otherwise cookies would become invalid upon restarts)
* Retrieve settings and secrets from the kubernetes cluster
* TODO: handle probes
* TODO: gracefully shutdown
* TODO: Target a local cluster for development or a remote cluster for deployment

Things to figure out:

* Do we really need to care about running the application from an unprivileged account?

### References

* [K8s friendly aspnetcore](https://github.com/Lybecker/k8s-friendly-aspnetcore)
* [Deploying ASP.NET Core applications to Kubernetes](https://andrewlock.net/deploying-asp-net-core-applications-to-kubernetes-part-1-an-introduction-to-kubernetes/)

### License

MIT