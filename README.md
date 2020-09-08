# Ansible-up-and-running
my ansible version is 2.9.12

## Vagrantfile
vagrant is used to create virtual machines to test on it locally

## secrets.yml
this file should include sample on data but it doesn't include the right keys

## Important Notes
you need to run the following command each time you start a new ssh-agent to be able to use **git module** inside ansible where id_rsa includes the ssh key for your github account. See the Useful Links for more details.
```sh
$ ssh-add ~/.ssh/id_rsa
```

### Useful Links
[how to create ssh key, adding it to ssh-agent and github (to solve public key permission denied error)](https://docs.github.com/en/github/authenticating-to-github/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent#generating-a-new-ssh-key).

### Problems
It fails in TASK [intialize the database (syncdb, migrate, collectstatic)]
