# docker_tutorial
docker tutorial

## Linux Ubuntu
1. sudo snap refresh
1. sudo snap install docker

1. sudo docker --version
```
Docker version 28.4.0, build d8eb465

```

4. sudo docker inf0

```
Client:
 Version:    28.4.0
 Context:    default
 Debug Mode: false
 Plugins:
  buildx: Docker Buildx (Docker Inc.)
    Version:  v0.24.0
    Path:     /usr/libexec/docker/cli-plugins/docker-buildx
  compose: Docker Compose (Docker Inc.)
    Version:  v2.39.1
    Path:     /usr/libexec/docker/cli-plugins/docker-compose

Server:
 Containers: 0
  Running: 0
  Paused: 0
  Stopped: 0
 Images: 0
 Server Version: 28.4.0
 Storage Driver: overlay2
  Backing Filesystem: extfs
  Supports d_type: true
  Using metacopy: false
  Native Overlay Diff: true
  userxattr: false
 Logging Driver: json-file
 Cgroup Driver: systemd
 Cgroup Version: 2
 Plugins:
  Volume: local
  Network: bridge host ipvlan macvlan null overlay
  Log: awslogs fluentd gcplogs gelf journald json-file local splunk syslog
 CDI spec directories:
  /etc/cdi
  /var/run/cdi
 Swarm: inactive
 Runtimes: io.containerd.runc.v2 runc
 Default Runtime: runc
 Init Binary: docker-init
 containerd version: 05044ec0a9a75232cad458027ca83437aae3f4da
 runc version: 
 init version: de40ad0
 Security Options:
  apparmor
  seccomp
   Profile: builtin
  cgroupns
 Kernel Version: 6.14.0-35-generic
 Operating System: Ubuntu Core 24
 OSType: linux
 Architecture: x86_64
 CPUs: 2
 Total Memory: 15.56GiB
 Name: bilbo-VMware-Virtual-Platform
 ID: 8f5bcf5e-d70c-4729-a2e1-bf4e5d5a4617
 Docker Root Dir: /var/snap/docker/common/var-lib-docker
 Debug Mode: false
 Experimental: false
 Insecure Registries:
  ::1/128
  127.0.0.0/8
 Live Restore Enabled: false
 ```

5. sudo groupadd docker
1. sudo usermod -aG docker $USER
1. sudo snap start docker
1. sudo snap services docker
1. newgrp docker  # switch to docker
1. docker run hello-world

## Chapter 2