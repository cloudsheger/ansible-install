# Install Ansible on Ubuntu, you can use the following steps:

### Update the package manager's list of available packages:

```sudo apt update```

### Install the software-properties-common package, which allows you to easily manage your software sources:

```sudo apt install software-properties-common```

### Add the Ansible repository to your sources list:

```sudo apt-add-repository ppa:ansible/ansible```

### Update the package manager's list of available packages again:

```sudo apt update```

### Install Ansible:

```sudo apt install ansible```

### Verify the installation by running the following command:

```ansible --version```
