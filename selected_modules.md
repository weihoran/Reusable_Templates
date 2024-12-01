# Review of Related IaC Modules

# Evaluation Criteria
The criteria used to evaluate 46 reusable Infrastructure as Code (IaC) modules. Each criterion reflects a key aspect of design and functionality.

## 1. Platform Independence
- **Definition:** Determines whether the module can be used across different cloud providers or in hybrid environments.
- **Evaluation Approach:**
  - Check if the module supports multiple cloud providers (e.g., AWS, Azure, GCP).
  - Verify the use of abstractions to avoid provider-specific dependencies.
  - Confirm compatibility with hybrid or on-premises setups.

## 2. Input Variables
- **Definition:** Assesses if the module allows configuration through input variables.
- **Evaluation Approach:**
  - Inspect the module's code for the presence of input variables.
  - Evaluate the flexibility and range of configurable parameters.
  - Verify if the variables are documented for ease of use.

## 3. Output Variables
- **Definition:** Determines whether the module provides output interfaces to facilitate integration with other modules.
- **Evaluation Approach:**
  - Check for defined output variables in the module.
  - Validate the relevance and completeness of the outputs for integration.
  - Review documentation to ensure outputs are clearly described.

## 4. Comprehensive Documentation
- **Definition:** Measures the quality and depth of the module’s documentation.
- **Evaluation Approach:**
  - Check for README files with detailed usage instructions.
  - Assess the presence of examples and descriptions of inputs/outputs.
  - Verify whether naming conventions and module structure are clearly explained.

## 5. Scalable Configuration
- **Definition:** Evaluates the module's ability to handle varying loads and optimize resource utilization.
- **Evaluation Approach:**
  - Check for the inclusion of scaling mechanisms (e.g., auto-scaling groups).
  - Analyze the module's adaptability to different workload scenarios.
  - Verify resource efficiency through tagging and configuration options.

## 6. Modular Structure
- **Definition:** Determines whether the module employs a modular design with base and sub-modules for extensibility.
- **Evaluation Approach:**
  - Inspect the module's structure for clear separation of concerns.
  - Verify the presence of reusable sub-modules.
  - Assess the ease of extending or integrating the module with others.


# Modules selected for evaluation

## Kuberrnetes Modules

- **Terraform Module for Deploying Metrics Server to Kubernetes Cluster**  
  Repository: [github.com/cookielab/terraform-kubernetes-metrics-server](https://github.com/cookielab/terraform-kubernetes-metrics-server)  
  Inputs: 18, Outputs: 2  

- **Terraform Module for Kubernetes Cert Manager**  
  Repository: [github.com/terraform-iaac/terraform-kubernetes-cert-manager](https://github.com/terraform-iaac/terraform-kubernetes-cert-manager)  
  Inputs: 13, Outputs: 5  

- **Terraform Module for Kubernetes Ingress**  
  Repository: [github.com/terraform-iaac/terraform-kubernetes-ingress](https://github.com/terraform-iaac/terraform-kubernetes-ingress)  
  Inputs: 11, Outputs: 2  

- **Terraform Module for Kubernetes Stateful Set**  
  Repository: [github.com/terraform-iaac/terraform-kubernetes-stateful-set](https://github.com/terraform-iaac/terraform-kubernetes-stateful-set)  
  Inputs: 44, Outputs: 2
  
## Istio Modules
- **Terraform Kubernetes Istio Release**  
  Repository: [github.com/truemark/terraform-kubernetes-istio](https://github.com/truemark/terraform-kubernetes-istio)  
  Inputs: 27, Outputs: 0  

- **Combinator component that installs Istio**  
  Repository: [github.com/combinator-ml/terraform-k8s-istio](https://github.com/combinator-ml/terraform-k8s-istio)  
  Inputs: 6, Outputs: 0  

- **terraform-module-istio**  
  Repository: [github.com/bakuppus/terraform-module-istio](https://github.com/bakuppus/terraform-module-istio)  
  Inputs: 6, Outputs: 0  

## Linkerd Modules
- **Deploy Linkerd2 on Kubernetes with ease**  
  Repository: [github.com/GaruGaru/terraform-kubernetes-linkerd2](https://github.com/GaruGaru/terraform-kubernetes-linkerd2)  
  Inputs: 9, Outputs: 0  

- **Terraform module to deploy Linkerd2 on Kubernetes**  
  Repository: [github.com/rtlnl/terraform-kubernetes-linkerd2](https://github.com/rtlnl/terraform-kubernetes-linkerd2)  
  Inputs: 24, Outputs: 0  

## Jaeger Modules
- **Jaeger tracing**  
  Repository: [github.com/basisai/terraform-kubernetes-jaeger](https://github.com/basisai/terraform-kubernetes-jaeger)  
  Inputs: 45, Outputs: 0  

- **Module Jaeger created with Terraform**  
  Repository: [github.com/easy-modules/terraform-easy-jaeger](https://github.com/easy-modules/terraform-easy-jaeger)  
  Inputs: 9, Outputs: 5  

## FluentD Modules
- **FluentD collector on Kubernetes via Terraform**  
  Repository: [github.com/mateothegreat/terraform-kubernetes-fluentd-collector](https://github.com/mateothegreat/terraform-kubernetes-fluentd-collector)  
  Inputs: 9, Outputs: 0

## Kibana Modules
- **Kibana Module for Kubernetes based on Elastic Helm Charts**  
  Repository: [github.com/kiwicom/terraform-kubernetes-kibana](https://github.com/kiwicom/terraform-kubernetes-kibana)  
  Inputs: 16, Outputs: 1  

## Ambassador Modules
- **Ambassador Terraform Emissary Ingress via Helm**  
  Repository: [github.com/basisai/terraform-helm-ambassador](https://github.com/basisai/terraform-helm-ambassador)  
  Inputs: 72, Outputs: 0  

- **Terraform Kubernetes Ambassador Deployment**  
  Repository: [github.com/sailthru/terraform-kubernetes-ambassador](https://github.com/sailthru/terraform-kubernetes-ambassador)  
  Inputs: 38, Outputs: 0  

## Kong Modules
- **Kong Gateway**  
  Repository: [github.com/Kong/terraform-kubernetes-kong-gateway](https://github.com/Kong/terraform-kubernetes-kong-gateway)  
  Inputs: 45, Outputs: 0  

- **Terraform Module for Kong Configurations**  
  Repository: [github.com/vaibhavkhurana2018/terraform-kong-kong-module](https://github.com/vaibhavkhurana2018/terraform-kong-kong-module)  
  Inputs: 4, Outputs: 1  

- **Helm with Kong Chart as Kong Ingress Controller**  
  Repository: [github.com/bennu/terraform-helm-kong](https://github.com/bennu/terraform-helm-kong)  
  Inputs: 49, Outputs: 3  

## Prometheus Modules
- **Deploys Prometheus and supporting services on a Kubernetes cluster**  
  Repository: [github.com/basisai/terraform-helm-prometheus](https://github.com/basisai/terraform-helm-prometheus)  
  Inputs: 242, Outputs: 2  

- **Prometheus Terraform Module for Kubernetes by Kubestack**  
  Repository: [github.com/kubestack-modules/terraform-kustomization-prometheus](https://github.com/kubestack-modules/terraform-kustomization-prometheus)  
  Inputs: 3, Outputs: 0  

- **Prometheus on Kubernetes via Terraform**  
  Repository: [github.com/mateothegreat/terraform-kubernetes-prometheus](https://github.com/mateothegreat/terraform-kubernetes-prometheus)  
  Inputs: 19, Outputs: 0  

## Grafana Modules
- **Deploys Grafana and supporting services on a Kubernetes cluster**  
  Repository: [github.com/basisai/terraform-helm-grafana](https://github.com/basisai/terraform-helm-grafana)  
  Inputs: 75, Outputs: 0  

- **Grafana on Kubernetes via Terraform**  
  Repository: [github.com/mateothegreat/terraform-kubernetes-grafana](https://github.com/mateothegreat/terraform-kubernetes-grafana)  
  Inputs: 9, Outputs: 0  

## Consul Modules
- **Deploy Consul on Kubernetes using Terraform**  
  Repository: [github.com/basisai/terraform-kubernetes-consul](https://github.com/basisai/terraform-kubernetes-consul)  
  Inputs: 185, Outputs: 2  

- **Basic Configuration for Consul**  
  Repository: [github.com/resinstack/terraform-consul-base](https://github.com/resinstack/terraform-consul-base)  
  Inputs: 17, Outputs: 0  


