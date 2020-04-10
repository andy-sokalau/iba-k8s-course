# HTPasswd Identity Provider

## Exam Study Point

* **Manage users and policies**
    * _Configure the HTPasswd identity provider for authentication_

## Reference Info

* [Configuring an HTPasswd identity provider](https://docs.openshift.com/container-platform/4.2/authentication/identity_providers/configuring-htpasswd-identity-provider.html)
* [htpasswd(1) - Linux man page](https://linux.die.net/man/1/htpasswd)

## Tasks

* Create password file with `htpasswd` and add several users
* Use `oc` tool to setup **HTPasswd** identity provider and 
    login as one of the users created during the previous step
    via `oc login`
* Use GUI to setup **HTPasswd** identity provider and login to
    console via one of the users