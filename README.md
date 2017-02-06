# mha-rpm

[![Build Status](https://travis-ci.org/takumakume/mha-rpm.svg?branch=master)](https://travis-ci.org/takumakume/mha-rpm)


This is RPM build tool at [mha4mysql-manager](https://github.com/yoshinorim/mha4mysql-manager) and [mha4mysql-node](https://github.com/yoshinorim/mha4mysql-node)

### RPM build

```shell
docker-compose build {OS_RELEASE}
docker-compose run {OS_RELEASE}
```

##### for CentOS 6

```shell
docker-compose build centos6
docker-compose run centos6

# RPMS
$ ls RPMS/centos6/
mha4mysql-manager-0.57-0.el6.noarch.rpm mha4mysql-node-0.57-0.el6.noarch.rpm
```

### Supported OS

- centos6
- centos7

### Author

- [takumakume](https://twitter.com/takumakume)
