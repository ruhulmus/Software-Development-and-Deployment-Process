# Software-Development-and-Deployment-Process

The smooth software development and deployment process are vital for the smooth operation of any organization. Every organization has its own process to develop any software.
Different projects have different natures. So development and deployment processes are also different based on the nature of that project.

I have worked on many projects under different organizations and follow many processes. After all calculations, it was discovered Software Development process mainly consists of a few stages. **Here** I have shared a **few stages** (requirement analysis to release) at a very high level that I follow most of the time.

1. **Requirement Analysis** 
2. **Requirement Finalization**
3. **Architecture and application design** 
4. **Sprintwise Development Start - (back-end, front-end, Mobile apps) Parallely**
5. **Prepare Local server and Version controlling (Branching/Push-Pull)**
6. **Implement CI/CD and containerazion** 
7. **Feature Test and Issue resolve** 
8. **Test/Re-test into UAT server** 
9. **Finalize UAT and Prepare for Production Deployment** 
10. **Production Release** 


### Requirement Analysis: 
Start Requirement Analysis with the team and get knowledge about the project as much as possible. It can be meeting with the business team or client or other stake holders. 
Go through the User story or any other Documents if available.

### Requirement Finalization:
In this step, need to finalize the requirement as much as possible. 
Few requirements may come later, but still, we need to understand and finalized the current requirement. If needed sit again with stock holders to validate and finalize your current understanding.
Make Task breakdown in detail level. Start Sprint plans and distribute tasks to developers/Designers

### Architecture and application design: 
It's the most important part before starting development directly.
It’s the root of the software. It creates a solid foundation for the software project to ensure that your project will be scalable and powerful.
After finalization, the architecture design, then starts your work.

### Sprint-wise Development Start:
Now come to the development part :). 
Start work on a feature or module based on the sprint plan. Multiple teams and multiple members can work in different modules or in the same module. The back-end/API development team can work on API design and development. The front-end team can work on their side. The mobile application team can work on their module. The designer can work on the Designing and Preparing Asset sections. Also, the Testing team can prepare their test cases based on the user story or requirement.


### Prepare Local Server and Version controlling: 

Prepare a local server. It's not the local development machine that you are working on :).
Its means, it's a server machine that is hosted in your local Network.
So you can deploy your completed tasks/module/feature to test or debugging. 

Firstly, you can work on your machine and once it has been done, you can deploy it into your local server for any dev or QA level testing.

Use different types of profiling for different servers (Local, Dev, QA, UAT, Prod, etc.)

Don't forget to maintain proper Branching and tagging. Otherwise, you will be in big trouble :). 
You can use any local or central version controlling system for your organization. 
I prefer GIT for version control and GitFlow architecture for any project. You can check it out from here.


### Implement CI/CD and containerazion :

If possible use any CI/CD pipeline and containerization for deployment. 

You can check benifit of CI/CD pipeline [Here](https://www.ranorex.com/blog/5-benefits-ci-cd-pipeline/#:~:text=One%20of%20the%20biggest%20advantages,deployed%20to%20prevent%20production%20outages)


For Benefit of Containerization You can check it out from [Here](https://circleci.com/blog/benefits-of-containerization/)


### Feature Test and Issue resolve: 
After your feature deployment, QA can test with test cases.
Unit Testing, Integration Testing & System Testing should be done as much as possible. If any issue is found Need to resolve, redeploy and retest.

Once your feature is tested now it's ready for DEV/UAT server deployment. So merge the feature and deploy the application/Services into DEV/UAT server. If you use CI/CD and containerization then its very easy to deploy.

Test/Re-test into UAT server:
Now time to test on the UAT server. The main purpose of UAT is to validate end-to-end business flow.
It is a kind of black-box testing where two or more end-users will be involved.

Most of the time I used the same server for DEV/QA level regression testing and User Acceptance testing. So it depends on the projects and available servers that are allocated for that project.

Finalize UAT and Prepare for Production Deployment:
So after completing the UAT testing make sure that your production release checklist is ready.
