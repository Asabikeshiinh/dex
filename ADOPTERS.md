# Adopters

This is a list of production adopters of Dex (in alphabetical order).

# Companies

- [Aspect](https://www.aspect.com/) uses Dex for authenticating users across their Kubernetes infrastructure (using Kubernetes OIDC support).
- [Banzai Cloud](https://banzaicloud.com) is using Dex for authenticating to its Pipeline control plane and also to authenticate users against provisioned Kubernetes clusters (via Kubernetes OIDC support).
- [Ericsson](https://www.ericsson.com) is using Dex to authenticate access to Kubernetes API server in [Cloud Container Distribution](https://www.ericsson.com/en/portfolio/cloud-software-and-services/cloud-core/cloud-infrastructure/nfvi/cloud-container-distribution).
- [Flant](https://flant.com) uses Dex for providing access to core components of [Managed Kubernetes as a Service](https://flant.com/services/managed-kubernetes-as-a-service), integration with various authentication providers, plugging custom applications.
- [JuliaBox](https://juliabox.com/) is leveraging federated OIDC provided by Dex for authenticating users to their compute infrastructure based on Kubernetes.
- [Pusher](https://pusher.com) uses Dex for authenticating users across their Kubernetes infrastructure (using Kubernetes OIDC support) in conjunction with the [OAuth2 Proxy](https://github.com/pusher/oauth2_proxy) for protecting web UIs.

# Projects

- [Argo CD](https://argoproj.github.io/cd) integrates Dex to provide convenient Single Sign On capabilities to its web UI and CLI
- [Chef](https://chef.io) uses Dex for authenticating users in [Chef Automate](https://automate.chef.io/). The code is Open Source, available at [`github.com/chef/automate`](https://github.com/chef/automate).
- [Elastisys](https://elastisys.com) uses Dex for authentication in their [Compliant Kubernetes](https://compliantkubernetes.io) distribution, including SSO to the custom dashboard, Grafana, Kibana, and Harbor.
- [Kasten](https://www.kasten.io) is using Dex for authenticating access to the dashboard of [K10](https://www.kasten.io/product/), a Kubernetes-native platform for backup, disaster recovery and mobility of Kubernetes applications. K10 is widely used by a variety of customers including large enterprises, financial services, design firms, and IT companies.
- [Kubeflow](https://www.kubeflow.org/) [uses](https://github.com/kubeflow/manifests#dex) Dex as one of its components in the Kubeflow Platform for external OIDC authentication.
- [Kyma](https://kyma-project.io) is using Dex to authenticate access to Kubernetes API server (even for managed Kubernetes like Google Kubernetes Engine or Azure Kubernetes Service) and for protecting web UI of [Kyma Console](https://github.com/kyma-project/console) and other UIs integrated in Kyma ([Grafana](https://github.com/grafana/grafana), [Loki](https://github.com/grafana/loki), and [Jaeger](https://github.com/jaegertracing/jaeger)). Kyma is an open-source project ([`github.com/kyma-project`](https://github.com/kyma-project/kyma)) designed natively on Kubernetes, that allows you to extend and customize your applications in a quick and modern way, using serverless computing or microservice architecture. 
- [LLMariner](https://llmariner.ai/) uses Dex for [user management](https://llmariner.ai/docs/features/user_management/).
- [Pydio](https://pydio.com/) Pydio Cells is an open source sync & share platform written in Go. Cells is using Dex as an OIDC service for authentication and authorizations. Check out [Pydio Cells repository](https://github.com/pydio/cells) for more information and/or to contribute.
- [sigstore](https://sigstore.dev) uses Dex for authentication in their public Fulcio instance, which is a certificate authority for code signing certificates bound to OIDC-based identities.
