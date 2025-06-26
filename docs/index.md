# AI Software Template Gitops

This repository contains the necessary content required for managing GitOps. It was created as part of an AI Software Template. The associated source component is available for reference in the **Overview** tab. You can find an example of this reference in the following image.

![Overview Tab](./images/overview-dependency.png)

# Deployed Resources
Based on the input from the AI Software Template, a deployment with the following characterisics was made:

# Model Server
**Model Server:** [whisper.cpp]( https://github.com/containers/ai-lab-recipes/tree/main/model_servers/whispercpp)

**Port:** 8001

# Application
An application built from https://github.com/rhdh-JslYoon-org/rhdhpai802-final2 will be stored in [quay.io/rh-ee-lyoon/rhdhpai802-final2](https://quay.io/rh-ee-lyoon/rhdhpai802-final2) and deployed through GitOps. This application is accessible on port **8501**.