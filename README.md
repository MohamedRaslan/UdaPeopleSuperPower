## Give your Application Auto-Deploy Superpowers

In this project, you will prove your mastery of the following learning objectives:

- Explain the fundamentals and benefits of CI/CD to achieve, build, and deploy automation for cloud-based software products.
- Utilize Deployment Strategies to design and build CI/CD pipelines that support Continuous Delivery processes.
- Utilize a configuration management tool to accomplish deployment to cloud-based servers.
- Surface critical server errors for diagnosis using centralized structured logging.

![Diagram of CI/CD Pipeline we will be building.](udapeople.png)

### Instructions

* [Selling CI/CD](instructions/0-selling-cicd.md)
* [Getting Started](instructions/1-getting-started.md)
* [Deploying Working, Trustworthy Software](instructions/2-deploying-trustworthy-code.md)
* [Configuration Management](instructions/3-configuration-management.md)
* [Turn Errors into Sirens](instructions/4-turn-errors-into-sirens.md)

### Project Submission

For your submission, please submit the following:

- A text file named `urls.txt` including:
  1. Public Url to GitHub repository (not private) [[URL01](https://github.com/MohamedRaslan/UdaPeopleSuperPower)]
  2. . Public URL for your S3 Bucket (aka, your green candidate front-end) [URL02]
  3. Public URL for your CloudFront distribution (aka, your blue production front-end) [[URL03](http://dg4bh2kiolgv0.cloudfront.net/)]
  4. Public URLs to deployed application back-end in EC2 [URL04]
  5. Public URL to your Prometheus Server [URL05]
     5.1.  [Prometheus](http://ec2-54-167-199-5.compute-1.amazonaws.com:9090/targets)
     5.2.  [Alertmanager](http://ec2-54-167-199-5.compute-1.amazonaws.com:9093/#/alerts)

- Your screenshots in JPG or PNG format, named using the screenshot number listed in the instructions. These screenshots should be included in your code repository in the root folder.
  1. Job failed because of compile errors. [[SCREENSHOT01](./docs/screenshots/SCREENSHOT01.png)]
  2. Job failed because of unit tests. [[SCREENSHOT02](./docs/screenshots/SCREENSHOT02.png)]
  3. Job that failed because of vulnerable packages. [[SCREENSHOT03](./docs/screenshots/SCREENSHOT03.png)]
  4. An alert from one of your failed builds. [[SCREENSHOT04](./docs/screenshots/SCREENSHOT04.png)]
  5. Appropriate job failure for infrastructure creation. [[SCREENSHOT05](./docs/screenshots/SCREENSHOT05.png)]
  6. Appropriate job failure for the smoke test job. [[SCREENSHOT06](./docs/screenshots/SCREENSHOT06.png)]
  7. Successful rollback after a failed smoke test. [[SCREENSHOT07](./docs/screenshots/SCREENSHOT07.png)]
  8. Successful promotion job. [[SCREENSHOT08](./docs/screenshots/SCREENSHOT08.png)]
  9. Successful cleanup job. [[SCREENSHOT09](./docs/screenshots/SCREENSHOT09.png)]
  10. Only deploy on pushed to `master` branch. [[SCREENSHOT10](./docs/screenshots/SCREENSHOT10.png)]
  11. Provide a screenshot of a graph of your EC2 instance including available memory, available disk space, and CPU usage. [[SCREENSHOT11](./docs/screenshots/SCREENSHOT11.png)]
  12. Provide a screenshot of an alert that was sent by Prometheus. [[SCREENSHOT12](./docs/screenshots/SCREENSHOT12.png)]

- Your presentation should be in PDF format named "[presentation.pdf](./docs/presentation.pdf)" and should be included in your code repository root folder.

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
