# saltstack-ssh-test
Playing with Saltstack's salt-ssh

## Setup

```bash
$ vagrant up
```

## Use

```base
$ vagrant ssh controller
# run your salt-ssh commands as normal
```

### Setting up the slaves

The slaves are only basically setup using vagrant.  The actual setup is done via salt-ssh.

```bash
controller:~ $
# sets up the slaves
```
