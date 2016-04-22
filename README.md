# docker_playbook
This playbook is used to install and configure Docker on your CentOS 7 boxes.
It eventually removes old Docker version, copy the latest repo and install latest version, configures proxy (http-proxy.conf file) and a certificate for you private Docker registry (docker.crt).
These last steps are optional.

