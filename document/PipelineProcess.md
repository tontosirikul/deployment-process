# Pipeline Process

1. The pipeline acquires the followind orbs
   - node (circleci/node@4.7.0)
   - aws cli (circleci/aws-cli@2.0.3)
   - eb (circleci/aws-elastic-beanstalk@2.0.1)
2. Running Ubuntu docker
3. Install node
4. checkout code on git
5. Setup aws-cli
6. Setup eb-cli
7. Install yarn
8. Install frontend/backend dependencies
9. Build frontend/backend
10. Deploy backend
11. Set backend env variables
12. Deploy frontend

![](/screenshot/linear_pipeline.png)
