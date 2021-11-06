# shell-exec-cloud-run
Execute a shell command within Cloud Run.

This repository contains sample code for use in conjunction with the article on
debugging Cloud Run applications by running shell commands within a Cloud Run container.

![Architecture](docs/architecture.png)

# Created new Makefile.bak for Python - Kody
Changed deploy command to gcloud beta run so I was able to add --execution-environment gen2. 
Gen2 does not start via gVisor and using the alt Makefile.bak in place of Makefile when building will show that.
