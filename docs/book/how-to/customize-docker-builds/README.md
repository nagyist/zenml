---
icon: docker
description: Using Docker images to run your pipeline.
---

# Customize Docker Builds

ZenML executes pipeline steps sequentially in the active Python environment when running locally. However, with remote [orchestrators](https://docs.zenml.io/user-guides/production-guide/cloud-orchestration) or [step operators](https://docs.zenml.io/stacks/step-operators), ZenML builds [Docker](https://www.docker.com/) images to run your pipeline in an isolated, well-defined environment.

This section discusses how to control this dockerization process.

<figure><img src="https://static.scarf.sh/a.png?x-pxid=f0b4f458-0a54-4fcd-aa95-d5ee424815bc" alt="ZenML Scarf"><figcaption></figcaption></figure>
