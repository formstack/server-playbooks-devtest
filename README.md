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
- Update your `/etc/hosts` file

    ```
    echo 192.168.59.76   testbox.dev www.testbox.dev | sudo tee -a /etc/hosts
    ```

- Next you can simply use the `vagrant up` command to start provisioning your local environment!
- Adding an index.php file into your repository should allow you to see its contents at http://www.testbox.dev
- Remember part of the process is to see how you work so commit and push changes as you would on day to day projects.
