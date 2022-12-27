# sshuttle

## Installation

```
sudo apt install sshuttle
```

## Usage

```
sshuttle --dns -vr <remote-user>@<remote-address>[:port] 0/0
```

e.g.

```
sshuttle --dns -vr root@192.168.10.100 0/0
```

```
sshuttle --dns -vr root@192.168.10.100:10022 0/0
```
