# Software Templates

Collection of Software Templates / Golden Path for Backstage.


# Testing

Create a secret in the project called "ssh" with the ssh private key in the field "id_rsa". This is needed by tekton pipeline to commit into the gitops repo

Import a valid registry credential for registry.redhat.io

For the Java project using sonarqube, create the configmap 'hello-tomcat-s2ienvironment' that contains valid sonarqube url, and user token



curl -XPOST -d '{"source_image_hash": "7ddaf9c664ffaddb024d38dbe27f7c4a32723606ac26e238cc4284263f00814d", "dest_image_tag": "v1.0"}' https://webhook-hello-tomcat-el-hello-tomcat.apps.cluster-cm7p7.cm7p7.sandbox400.opentlc.com/ -H 'Content-Type: application/json' -H 'X-Internal-Event: promote'
