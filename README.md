# Formstack Developer Project Environment Setup

## Prerequisites

- Virtualbox > 5.1
- Vagrant > 1.8.6
- Git
- Root access to your local machine

## Getting your Environment Setup
- Create a new git repository that you can share with us via github.
- Download the `Vagrantfile` using curl into the new repository directory locally.

    ```
    curl -sS https://raw.githubusercontent.com/formstack/server-playbooks-devtest/master/Vagrantfile -o Vagrantfile
    ```

- Make sure your SSH is configured to work with Github -
    [https://help.github.com/articles/generating-an-ssh-key/](https://help.github.com/articles/generating-an-ssh-key/)
- After the Vagrantfile is downloaded you can simply use the `vagrant up` command to start provisioning your local environment!

This will install the environment you'll need.  You'll want to modify your `/etc/hosts` file to reflect the following changes:

```
192.168.59.76   testbox.dev www.testbox.dev
```
