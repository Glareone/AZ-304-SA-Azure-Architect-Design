# AZ-304 SA Azure Architecture Design Exam materials

## Powershell intro
[powershell materials coming from Skylines Academy](https://slstudentpublic.blob.core.windows.net/operations/PowerShell%20Guide_AZ__Skylines%20Academy-v3-Student.pdf)

## Jeffrey Richter's Course
[?aaS Cloud course from Jeffrey Richter](https://www.youtube.com/watch?v=LkJr0Ld85AE&list=PL9XzOCngAkqs0Q8ZRdafnSYExKQurZrBY&index=4)   
[Jeffry Richter Presentation, Why cloud apps, Embracing Failures, Orchestrators, Virtualization.pptx](https://github.com/Glareone/AZ-304-SA-Azure-Architect-Design/files/8095517/Jeffrey.Richter.Part1.pptx)  
[Jeffrey Richter Presentation, Regions and Microservices.pptx](https://github.com/Glareone/AZ-304-SA-Azure-Architect-Design/files/8173857/Jeffrey.Richter.Part2.pptx)  
[Jeffrey Richter, Scaling, 12-Factor, Containers.pptx](https://github.com/Glareone/AZ-304-SA-Azure-Architect-Design/files/8193156/Jeffrey.Richter.Part3.pptx)  
[Jeffrey Richter, Docker, Hyper-V containers, Containerd runtime, CI and CD.pptx](https://github.com/Glareone/AZ-304-SA-Azure-Architect-Design/files/8205732/Jeffrey.Richter.Part.4.pptx)  

* Addiional Materials: 
[The twelve factor application (12-factor)](https://12factor.net/)  
[8 Fallacies of Distributed Computing Explained](https://arnon.me/wp-content/uploads/Files/fallacies.pdf)  

<details>
<summary>Most important screens from Richter's course</summary>

![4 reasons to split the monolith onto microservices](https://user-images.githubusercontent.com/4239376/156473112-b224feef-fec9-4184-8d58-b5a40ee6005a.png)
  
</details>

<details>
<summary>SLA, SLO, SLI</summary>
Difference: https://www.atlassian.com/incident-management/kpis/sla-vs-slo-vs-sli   
* SLI Explained in details:  
http://cs.brown.edu/courses/csci2952-f/slides/Class9.pdf  
SLI Of The Platform  
- Critical Replica Threshold = CRT  
- Available replicas = min(total available pods, CRT)  
- Replica availability = (available replicas / CRT) * 100  
- Critical Replica Availability = mean(replica availability of each service)  
</details>

## AZ-300 AZ-301 AZ-304 AZ-305 Exam tips
[AZ+301 SKYLINES ACADEMY Slides_Student_Version.pdf](https://github.com/Glareone/AZ-304-SA-Azure-Architect-Design/files/8092664/AZ%2B301%2BSlides_Student%2BVersion_Skylines%2BAcademy.pdf)

### SKYLINES ACADEMY MATERIALS:
[SECTION-1 Workload requirements](https://www.skylinesacademy.com/az301-section-1)  
[SECTION-2 Identity and Security](https://www.skylinesacademy.com/az301-section-2)  
[SECTION-3 Data Platform Solutions](https://www.skylinesacademy.com/az301-section-3)  
[SECTION-4 Business Continuity](https://www.skylinesacademy.com/az301-section-4)  
[SECTION-5 Deployment, Migration, Integration](https://www.skylinesacademy.com/az301-section-5)  
[SECTION-6 Infrastructure Strategy](https://www.skylinesacademy.com/az301-section-6)  

# Logging. Monitoring. Design solutions for them. 
Insights and everything related to that.
* All information related to logging and monitoring are grouped here: [Logging and Monitoring Information](Logging,Monitoring.md)

# Cost Optimizations materials

# Security materials
## Design Authorization & Authentication
## Design Security
<details>
<summary>Trust Center, Compliance Manager, Data Protection, Azure Security and Compliance, Blueprints</summary>

[Microsoft Trust Center](https://www.microsoft.com/en-ww/trust-center/product-overview)  
* In-depth information access tp FedRAMP, ISO, SOC audit reports, data protection white papers and different assessment reports
* Centralized resources around security, compliance and privacy

[Compliance Manager](https://compliance.microsoft.com/compliancemanager)   
* Manage compliance from a central location
* Proactive risk assessment
* Insights and recommended actions
* Prepare compliance reports for audit

[Data Protection Resources](https://servicetrust.microsoft.com/viewpage/trustdocuments)  
* Trust documents, GDPR, Compliance guides, Pen test and Security Assessment tests

[Azure Security and Compliance, Blueprints](https://servicetrust.microsoft.com/ViewPage/BlueprintOverview)
* Industry-specific overview and guidance
* Customer responsibilities matrix
* References architectures with threat models

</details>

# Governance and Compliance materials
## Design Governance 

# Data materials
## Design for Data Storage
## Design for Storage Accounts
## Design for Backups and Recovery
