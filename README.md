# Continuous Delivery with Tanzu Mission Control
This code is used to set up continuous delivery for Tanzu Mission Control demos and POCs.

## Prerequisites and Setup
In order to complete this section you will require the following:

1.  Two Cluster groups: *demo-clustergroup-dev* and *demo-clustergroup-prod*.  Please refer to this section of the guide if you have not completed these steps: Getting Started with Tanzu Mission Control git binary
2.  Clone the following git repo using: git clone https://github.com/rroque99/tmc-poc.git
3.  Create a new empty public git repo using your source control vendor of choice ie. github, gitlab etc
4.  In the root directory of the cloned tmc-poc repo run the following:
   ```
    git remote add tmcpoc <your-new-repo-url>
    git push -u tmcpoc main
   ```

