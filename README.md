# getns

A kubectl plugin that can be used to get namespace of the passed resource.

# Installation

Download the file

```
curl https://raw.githubusercontent.com/viveksinghggits/getns/master/kubectl-getns
chmod +x kubectl-getns
```

Move the above file to PATH.

# Usage

```
kubectl getns resourcetype resourcename
```
for example

```
kubectl getns service kubernetes
```
