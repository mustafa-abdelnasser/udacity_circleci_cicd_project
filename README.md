
## Give your Application Auto-Deploy Superpowers

In this project, you will prove your mastery of the following learning objectives:

- Explain the fundamentals and benefits of CI/CD to achieve, build, and deploy automation for cloud-based software products.
- Utilize Deployment Strategies to design and build CI/CD pipelines that support Continuous Delivery processes.
- Utilize a configuration management tool to accomplish deployment to cloud-based servers.
- Surface critical server errors for diagnosis using centralized structured logging.

![Diagram of CI/CD Pipeline we will be building.](udapeople-pipeline.png)

![image](https://user-images.githubusercontent.com/6891966/204634658-a58147ad-0a97-44c0-af14-bf7b69e0e3ee.png)

![image](https://user-images.githubusercontent.com/6891966/204634812-fc231954-bb67-4e5c-829b-fa1ed740a2d9.png)


### Instructions

* [Selling CI/CD](instructions/0-selling-cicd.md)
* [Getting Started](instructions/1-getting-started.md)
* [Deploying Working, Trustworthy Software](instructions/2-deploying-trustworthy-code.md)
* [Configuration Management](instructions/3-configuration-management.md)
* [Turn Errors into Sirens](instructions/4-turn-errors-into-sirens.md)

### Project Submission

For your submission, please submit the following:

- A text file named `urls.txt` including:
  1. Public Url to GitHub repository (not private) [URL01]
  1. Public URL for your S3 Bucket (aka, your green candidate front-end) [URL02]
  1. Public URL for your CloudFront distribution (aka, your blue production front-end) [URL03]
  1. Public URLs to deployed application back-end in EC2 [URL04]
  1. Public URL to your Prometheus Server [URL05]
- Your screenshots in JPG or PNG format, named using the screenshot number listed in the instructions. These screenshots should be included in your code repository in the root folder.
  1. Job failed because of compile errors. [SCREENSHOT01]
![SCREENSHOT01](SCREENSHOT01.jpg)
  1. Job failed because of unit tests. [SCREENSHOT02]
![SCREENSHOT02](SCREENSHOT02.jpg)
  1. Job that failed because of vulnerable packages. [SCREENSHOT03]
![SCREENSHOT03](SCREENSHOT03.jpg)
  1. An alert from one of your failed builds. [SCREENSHOT04]
![SCREENSHOT04](SCREENSHOT04.jpg)
  1. Appropriate job failure for infrastructure creation. [SCREENSHOT05]
![SCREENSHOT05](SCREENSHOT05.jpg)
  1. Appropriate job failure for the smoke test job. [SCREENSHOT06]
![SCREENSHOT06](SCREENSHOT06.jpg)
  1. Successful rollback after a failed smoke test. [SCREENSHOT07]  
![SCREENSHOT07](SCREENSHOT07.jpg)
  1. Successful promotion job. [SCREENSHOT08]
![SCREENSHOT08](SCREENSHOT08.jpg)
  1. Successful cleanup job. [SCREENSHOT09]
![SCREENSHOT09](SCREENSHOT09.jpg)
  1. Only deploy on pushed to `master` branch. [SCREENSHOT10]
![SCREENSHOT10](SCREENSHOT10.jpg)
  1. Provide a screenshot of a graph of your EC2 instance including available memory, available disk space, and CPU usage. [SCREENSHOT11]
![SCREENSHOT11](SCREENSHOT11-cpu.jpg)
![SCREENSHOT11](SCREENSHOT11-disk.jpg)
![SCREENSHOT11](SCREENSHOT11-memory.jpg)
  1. Provide a screenshot of an alert that was sent by Prometheus. [SCREENSHOT12]
![SCREENSHOT12](SCREENSHOT12.jpg)

- Your presentation should be in PDF format named "presentation.pdf" and should be included in your code repository root folder. 

Before you submit your project, please check your work against the project rubric. If you haven’t satisfied each criterion in the rubric, then revise your work so that you have met all the requirements. 

### Built With

- [Circle CI](www.circleci.com) - Cloud-based CI/CD service
- [Amazon AWS](https://aws.amazon.com/) - Cloud services
- [AWS CLI](https://aws.amazon.com/cli/) - Command-line tool for AWS
- [CloudFormation](https://aws.amazon.com/cloudformation/) - Infrastrcuture as code
- [Ansible](https://www.ansible.com/) - Configuration management tool
- [Prometheus](https://prometheus.io/) - Monitoring tool

### License

[License](LICENSE.md)
