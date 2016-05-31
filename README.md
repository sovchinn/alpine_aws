# alpine_aws
Alpine based container with aws sdk

Usage:

Run using the below command to map local ~/.aws folder to container: 

sudo docker run -it -v ~/.aws:/root/.aws sovchinn/alpine_aws /bin/bash
