# Secrets

## Exam Study Point

* **Control access to resources**
    * _Create and apply secrets to manage sensitive information_

## Reference Info

* [Providing sensitive data to pods](https://docs.openshift.com/container-platform/4.2/nodes/pods/nodes-pods-secrets.html)

## Tasks

* Create 2 files `username.txt` and `password.txt` which contains username and password
* Create the secret from these files using `oc` tool and GUI
* Mount the secret to the nginx deployment pod as a file in read-only mode:
    * username and password together
    * only username
    * only password
* Mount the secret to the nginx deployment pod as env vars