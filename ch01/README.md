# Chapter 1 - Getting Started with Ansible

|本期版本| 上期版本
|:---:|:---:
`Thu Nov 18 13:51:09 CST 2021` | -


## Debian/Ubuntu

> `Sun Nov 21 21:08:51 CST 2021`

`20.04`、`pip`

```
sudo apt-get install -y python3-pip python3-dev
pip install -i https://pypi.tuna.tsinghua.edu.cn/simple ansible
```

`20.04`、`apt`

```
apt-get install software-properties-common
apt-add-repository -y ppa:ansible/ansible
apt-get update
apt-get install -y ansible
```


## Ref

* [ppa:ansible/ansible](https://launchpad.net/~ansible/+archive/ubuntu/ansible)
* [pypi 镜像使用帮助](https://mirrors.tuna.tsinghua.edu.cn/help/pypi/)