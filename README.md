# DevSecOps
DevSecOps is an essential methodology that integrates security practices into the DevOps process, emphasizing the need to consider security at every stage of the software development lifecycle. This approach ensures that security is not an afterthought but a continuous, integral part of the development and operations pipeline. 

# Origins of DevOps!

When the code reaches the server, it breaks. The development team reports that their application is not functioning correctly, while the operations team insists that the servers are running smoothly.

From the developers' perspective, the code was working perfectly, but the operations team denies any responsibility, claiming it's not their issue. This discrepancy leads to a debate over who is at fault.

To resolve this conflict and bridge the gap between the two teams, DevOps emerged. By automating processes and fostering collaboration, DevOps ensures that the code works consistently across both development and operations environments, eliminating these types of disputes.


<p align="center">
What is DevOps ???  <br/>
 <img src="https://imgur.com/jXwqakf.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

A DevOps Engineer's role is to automate the Software Development Lifecycle (SDLC), represented by the infinity symbol that illustrates the continuous flow between development and operations. As a DevOps Engineer, you bridge the gap between these two areas, automating processes to ensure everything runs smoothly within the SDLC.

Planning Phase: involves using agile practices, such as Scrum. Essentially, it entails organizing your work, breaking it into smaller tasks, and assigning these tasks to team members for execution.

Coding Phase: developers write code and push it to a GitHub repository. Multiple engineers often collaborate on an application, with each developer contributing their code to version control, ensuring that all changes are tracked and integrated.

Building/Test Phase (CI - Continuous Integration):
The building and test phase, also known as Continuous Integration (CI), involves committing your code to version control, which initiates a build of your artifact and runs various tests. These tests can include performance tests, bug tests, and code quality tests.
Continuous Integration allows developers to merge their code into the main branch multiple times a day. Each merge triggers a build, similar to compiling, followed by a series of tests. The goal is to produce a deployable artifact, whether it's a binary, a container, or another form, ensuring that the code version is safe for deployment.


Release Phase (CD - Continuous Delivery/Deployment):
The release phase involves Continuous Delivery (CD) or Continuous Deployment. Though similar, these two have slight differences. After compiling and testing your code to ensure it is safe for deployment, the CD process takes over. This phase deploys or releases the code to the server. Often, this step includes a manual approval gate, where a team lead or manager authorizes the deployment to proceed. Once approved, the code is deployed to the production environment.

Operate/Monitor
During the operate and monitor phase: applications are maintained and continuously observed for issues. Engineers ensure high availability and track any problems that arise. This phase generates valuable feedback, highlighting problems and limitations, which feeds directly back into the planning phase, completing and repeating the cycle.





