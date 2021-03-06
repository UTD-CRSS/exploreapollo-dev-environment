# Exploreapollo.org Development Environment

development setup for working on all the exploreapollo modules

## Get Started

1. You need to install [vagrant][vagrant-install] and [virtualbox][virtualbox-install]. You also need git installed. You should be able to authenticate to GitHub with SSH (https://help.github.com/articles/generating-an-ssh-key/).
2. Clone this repo in a convenient location
3. Initialize the project: `./init`
4. Inside the folder run `vagrant up`

## Usage

```
vagrant ssh
```

This will put you inside the ubuntu box. Mess with your projects:

```
cd /projects
ls
```

[vagrant-install]: https://www.vagrantup.com/docs/installation/
[virtualbox-install]: https://www.virtualbox.org/wiki/Downloads
