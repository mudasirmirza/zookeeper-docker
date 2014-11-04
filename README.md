zookeeper-docker
================

Containerize Zookeeper

The Dockerfile will help you run a standalone Zookeeper version 3.4.6 instance.

```bash
git clone git@github.com:mudasirmirza/zookeeper-docker.git
cd zookeeper-docker
docker build .
```

---

If you do not want to build it, just run

docker run -d -p 2181:2181 -p 2888:2888 -p 3888:3888 mudasirmirza/zookeeper:3.4.6
