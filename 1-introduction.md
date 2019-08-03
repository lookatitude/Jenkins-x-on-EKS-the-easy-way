# Introduction

### Reasoning and intention

There are several official tutorials on how to do this things and more in the [official Jenkins-X website](https://jenkins-x.io) 
but the big majority is based on GCP, and when it comes to AWS things work slightly different, you can find the information you need on the Jenkins-X (refered to as JX going forward)
website and the AWS documentation.

Based on a personal experience I wanted to compile a set of instructions in one place where you can go from 0 to App deployed in production with a set of easy to follow steps. 
This will guide will not cover all the possible cases only a set of basic steps to get started, you can always change, add and remove parts according to your specific case.

What we are looking to accomplish here:
- Create and setup a basic cluster.
- Install JX in the cluster.
- Setup Vault (to manage secrets as it is basic to any app in production)
- TLS setup
- Create an app or import an existing one
- Follow the GitOps flow up to promotion into production.

The contents of this guide can change as the JX dev team is also improving their documentation. If this becomes useful enough we will share the content in the form of contribution to the JX docs.


### Requirements

- Access to a AWS account. (tested with admin privileges)
- Command line. (tested on linux and macOS)


