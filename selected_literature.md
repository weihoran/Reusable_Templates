# Search Strategy and Selection Criteria for Implementation Best Practices

This document outlines the **search strategy**, **inclusion criteria**, and **exclusion criteria** used to identify and select relevant literature for summarizing implementation best practices for reusable Infrastructure as Code (IaC) templates.

## 1. Search Strategy

To comprehensively identify implementation best practices for reusable IaC templates, we conducted a multivocal review encompassing both academic and grey literature. The search strategy included the following steps:

### 1.1. Information Sources

We utilized a variety of information sources to ensure a comprehensive review:

| **Category**          | **Sources**                                                                                           |
|-----------------------|-------------------------------------------------------------------------------------------------------|
| **Academic Databases**| IEEE Xplore, ACM Digital Library, SpringerLink, ScienceDirect                        |
| **Grey Literature**   | Whitepapers from authoritative organizations (e.g., CNCF, AWS, Azure), Industry reports, Tool documentation and official guides (e.g., Terraform, Helm) |
                                
### 1.2. Search Keywords

We employed a combination of primary and secondary keywords to capture relevant literature:

| **Type**             | **Keywords/Phrases**                                                                                  |
|----------------------|--------------------------------------------------------------------------------------------------------|
| **Primary Keywords** | "Infrastructure as Code", "IaC best practices", "Reusable IaC templates", "Terraform best practices", "Helm Chart best practices" |
| **Secondary Keywords** | "Cloud-native infrastructure", "IaC template development", "DevOps automation", "IaC modularity", "IaC scalability", "IaC documentation" |


### 1.3. Search Process

1. **Initial Search:**
   - Conducted keyword searches across all identified information sources.
   - Utilized advanced search features to filter results by relevance and publication date (last 10 years).

2. **Screening Titles and Abstracts:**
   - Reviewed titles and abstracts to assess relevance to reusable IaC template development.

3. **Full-Text Review:**
   - Retrieved and reviewed full texts of shortlisted documents to evaluate their suitability based on inclusion and exclusion criteria.

4. **Snowball Sampling:**
   - Examined references of selected papers and documents to identify additional relevant literature.

## 2. Inclusion Criteria

Documents were included in the review if they met **all** the following criteria:

| **Criteria**            | **Description**                                                                                                               |
|-------------------------|-------------------------------------------------------------------------------------------------------------------------------|
| **Relevance**           | Focused on implementation best practices for reusable IaC templates.                                                          |
| **Type of Literature**  | Scientific papers, peer-reviewed articles, authoritative books, grey literature including whitepapers, industry reports, tool documentation, and reputable blog posts. |
| **Actionable Insights** | Provided clear, actionable best practices or guidelines applicable to IaC template development.                                |

## 3. Exclusion Criteria

Documents were excluded from the review if they met **any** of the following criteria:

| **Criteria**            | **Description**                                                                                                               |
|-------------------------|-------------------------------------------------------------------------------------------------------------------------------|
| **Irrelevance**         | Focused on general IaC concepts without specific best practices for reusable templates or addressed unrelated topics.           |
| **Type of Literature**  | Opinion pieces, editorials, informal blog posts lacking authoritative backing, duplicate publications, or multiple versions of the same document. |
| **Language**            | Published in languages other than English.                                                                                     |
| **Publication Date**    | Published before 2014, as older literature may not reflect current best practices and tool capabilities.                       |
| **Lack of Actionable Content** | Provided high-level overviews without detailed best practices or implementation strategies.                                           |


## 4. Selected Literature

I. Kumara et al., "The do’s and don’ts of infrastructure code: A systematic gray literature review," Inf. Softw. Technol., vol. 137, p. 106593, 2021.

HashiCorp, "Module creation - recommended pattern | Terraform | HashiCorp Developer," [Online]. Available: https://developer.hashicorp.com/terraform/tutorials/modules/pattern-module-creation.

HashiCorp, "Customize modules with object attributes | Terraform | HashiCorp Developer," [Online]. Available: https://developer.hashicorp.com/terraform/tutorials/modules/module-object-attributes.

R. Botwright, IaC Mastery: Infrastructure As Code: Your All-In-One Guide To Terraform, AWS, Azure, And Kubernetes. United States: Rob Botwright, 2023.

Y. Brikman, Terraform: Up & Running: Writing Infrastructure as Code. Sebastopol, CA, USA: O'Reilly Media, 2019.

A. Rahman, R. Mahdavi-Hezaveh, and L. Williams, "A systematic mapping study of infrastructure as code research," Inf. Softw. Technol., vol. 108, pp. 65–77, 2019.

HashiCorp, "Best practices to automate infrastructure | HashiCorp Developer," [Online]. Available: https://developer.hashicorp.com/well-architected-framework/operational-excellence/operational-excellence-automate-infrastructure.

Truemark, "truemark | Terraform Registry," [Online]. Available: https://registry.terraform.io/modules/truemark/istio/kubernetes/latest.

Combinator, "combinator | Terraform Registry," [Online]. Available: https://registry.terraform.io/modules/combinator-ml/istio/k8s/latest.

Bakuppus, "bakuppus | Terraform Registry," [Online]. Available: https://registry.terraform.io/modules/bakuppus/istio/module/latest.

 W. Li, Y. Lemieux, J. Gao, Z. Zhao and Y. Han, "Service Mesh: Challenges, State of the Art, and Future Research Opportunities," 2019 IEEE International Conference on Service-Oriented System Engineering (SOSE), San Francisco, CA, USA, 2019, pp. 122-1225, https://doi.org/10.1109/SOSE.2019.00026.

Y. Pan, I. Chen, F. Brasileiro, G. Jayaputera and R. Sinnott, "A Performance Comparison of Cloud-Based Container Orchestration Tools," 2019 IEEE International Conference on Big Knowledge (ICBK), Beijing, China, 2019, pp. 191-198, https://doi.org/10.1109/ICBK.2019.00033.

F. Zampetti, S. Geremia, G. Bavota and M. Di Penta, "CI/CD Pipelines Evolution and Restructuring: A Qualitative and Quantitative Study," 2021 IEEE International Conference on Software Maintenance and Evolution (ICSME), Luxembourg, 2021, pp. 471-482, https://doi.org/10.1109/ICSME52107.2021.00048.

M. Guerriero, M. Garriga, D. A. Tamburri and F. Palomba, "Adoption, Support, and Challenges of Infrastructure-as-Code: Insights from Industry," 2019 IEEE International Conference on Software Maintenance and Evolution (ICSME), Cleveland, OH, USA, 2019, pp. 580-589, https://doi.org/10.1109/ICSME.2019.00092.

H. Kang, M. Le, and S. Tao. ”Container and microservice driven design for cloud infrastructure devops”. In: 2016 IEEE International Conference on Cloud Engineering (IC2E), pp. 202–211, IEEE, 2016. https://doi.org/10.1109/IC2E.2016.26.

C. Guerrero, I. Lera, and C. Juiz. ”Resource optimization of container orchestration: a case study in multi-cloud microservicesbased applications”. The Journal of Supercomputing, Vol. 74, No. 7, pp. 2956–2983, 2018.

S. Haselböck and R. Weinreich, "Decision Guidance Models for Microservice Monitoring," 2017 IEEE International Conference on Software Architecture Workshops (ICSAW), Gothenburg, Sweden, 2017, pp. 54-61, doi: 10.1109/ICSAW.2017.31.  

Stefan Haselböck, Rainer Weinreich, and Georg Buchgeher. 2017. Decision guidance models for microservices: service discovery and fault tolerance. In Proceedings of the Fifth European Conference on the Engineering of Computer-Based Systems (ECBS '17). Association for Computing Machinery, New York, NY, USA, Article 4, 1–10. https://doi.org/10.1145/3123779.3123804

K. Jander, L. Braubach, and A. Pokahr. ”Defense-in-depth and Role Authentication for Microservice Systems”. Procedia computer science, Vol. 130, No. C, pp. 456–463, 2018.





