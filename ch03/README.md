# Chapter 3 - Ad-Hoc Commands

|本期版本|上期版本
|:---:|:---:
`Tue Dec 21 22:34:49 CST 2021` | `Thu Nov 18 14:30:12 CST 2021`


```
config.vm.provider :virtualbox do |v|
	v.memory = 512
	v.linked_clone = true
end
```


```
ansible_ssh_private_key_file=~/.vagrant.d/insecure_private_key
```

> `ansible.cfg`

```
[defaults]
inventory = hosts.ini
```