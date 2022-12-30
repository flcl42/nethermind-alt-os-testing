```
cd nethermind
git checkout master # or a branch you want to test

# Centos 8

docker build . -f Dockerfile.centos -t nethermind:centos
docker run -it nethermind:centos

# Fedora 36
docker build . -f Dockerfile.fedora -t nethermind:fedora
docker run -it nethermind:fedora 

etc
```