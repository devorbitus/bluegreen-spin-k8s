# Blue-Green Deployments on Google Kubernetes Engine with Spinnaker 

This directory contains the assets necessary to configure a simple blue-green pipeline
with Spinnaker on GKE.  

**Note**: this sample uses features only available in [Spinnaker 1.11](https://www.spinnaker.io/guides/user/kubernetes-v2/traffic-management/).  

* The `app` directory contains the source code for the small "Hello World"
  application used.

* The `manifests` directory contains the Kubernetes that will be deployed to GKE
  before the pipeline runs for the first time. 

* The `pipelines` directory contains the blue-green pipeline JSON.

Copied from [here](https://github.com/spinnaker/spinnaker/tree/master/solutions/bluegreen) to alter and use for demonstration purposes