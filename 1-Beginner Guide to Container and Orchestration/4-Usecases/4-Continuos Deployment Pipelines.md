# Continuous Deployment Pipelines

Continuous deployment is the practice of deploying new code automatically and frequently

Instead of writing new code for months and doing a big deployment, continuos deployment means constantly doing many small deployments. Some companies even do multiple deployments a day!

This allows you to get new functionality in front of customers faster, and it also reduce the risk associated with big deployments containing a large number of changes.

To maintain stability while doing continuos deployment, it is important to make use of automation to ensure that deployments are stable and consistent.

Containers work very well in the context of continuos deployment.

They make it easy to test code in an environment that is the same as production, because the code can be automatically tested inside the container itself.

An automation pipeline for continuous delivery can automatically build a container image with the new code, test it, then automatically ship that same container image production

Because the production environment (the container) is built right into this automated process, developers even have the ability to use it for testing and troubleshooting