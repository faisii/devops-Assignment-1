# devops-Assignment-1

Q#1 Agile vs DevOps?

    DevOps is a practice of bringing development and operations teams together whereas Agile is an iterative approach that focuses on collaboration, customer feedback and small rapid releases.

    The target area of Agile is Software development whereas the Target area of DevOps is to give end-to-end business solutions and fast delivery.

    DevOps focuses more on operational and business readiness whereas Agile focuses on functional and non-function readiness.

Q#2 Define CI, Continuous Delivery & Continuous Deployment?
    
    - Continuous integration

    Developers practicing continuous integration merge their changes back to the main branch as often as possible. The developer's changes are validated by creating a build and running automated tests against the build. By doing so, you avoid integration challenges that can happen when waiting for release day to merge changes into the release branch.

    Continuous integration puts a great emphasis on testing automation to check that the application is not broken whenever new commits are integrated into the main branch.

    - Continuous delivery

    Continuous delivery is an extension of continuous integration since it automatically deploys all code changes to a testing and/or production environment after the build stage. 

    This means that on top of automated testing, you have an automated release process and you can deploy your application any time by clicking a button.

    - Continuous deployment

    Continuous deployment goes one step further than continuous delivery. With this practice, every change that passes all stages of your production pipeline is released to your customers. There's no human intervention, and only a failed test will prevent a new change to be deployed to production.

Q#3 What are the benefits of Cloud Computing?

    Cloud computing is a term that has gained widespread use over the last few years. With the exponential increase in data use that has accompanied society's transition into the digital 21st century, it is becoming more and more difficult for individuals and organisations to keep all of their vital information, programs, and systems up and running on in-house computer servers.
    
    Here are some benefits of cloud computing.
    - Cost Savings
    - Security
    - Flexibility
    - Mobility
    - Insight
    - Quality Control

Q#4 Difference b/w Git & Github?

    Git is a version control system that lets you manage and keep track of your source code history. GitHub is a cloud-based hosting service that lets you manage Git repositories. If you have open-source projects that use Git, then GitHub is designed to help you better manage them.

Q#5 Stages of Git?

    There are four stages of Git
    - Working Directory
    - Staging area
    - Local repository
    - Remote repository

Q#6 Three methods of git reset?

    - git reset(--mixed): Uncommit and move to previous commit
    - git reset --soft: Uncommit but ﬁle will be in staging
    - git reset --hard: Uncommit, remove from stage, remove from local repo
