# Formstack Developer Project Environment Setup

## Prerequisites

- Virtualbox > 5.1
- Vagrant > 1.8.6
- Git
- Root access to your local machine

## Getting your Environment Setup
- Download the `Vagrantfile` using curl.

    ```
    curl -sS https://raw.githubusercontent.com/formstack/server-playbooks-devtest/master/Vagrantfile -o Vagrantfile
    ```

After the Vagrant file is downloaded you can simply use the `vagrant up` command to start provisioning your local environment!

This will install the environment you'll need.  You'll want to modify your `/etc/hosts` file to reflect the following changes:

```
192.168.59.76   testbox.dev www.testbox.dev
```
