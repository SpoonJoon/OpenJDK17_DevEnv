# OpenJDK17_DevEnv
Dockerfile for OpenJDK 17 development

## Building the JDK
* Create the docker image
* Run the image as a container 
* inside the image build the JDK
``` bash configure ```
``` make images ```
* Verify your newly built JDK:
``` ./build/*/images/jdk/bin/java -version ```
* run basic tests
``` make run-test-tier1 ```

