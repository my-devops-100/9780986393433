# Chapter 4 - Ansible Playbooks

|本期版本| 上期版本
|:---:|:---:
`Tue Nov 16 09:49:08 CST 2021` | -


### Ansible Playbook

* `>`: [YAML Multiline](https://yaml-multiline.info/)


### Launch a Node.js app

```
- name Check list of running Node.js apps
  command: forever list
  register: forver_list
  changed_when: false
```

* `ansible-playbook`
* `pre_tasks`
* `tasks`
* `post_tasks`
* `handlers`

* `vars_files`
* `notify`

* `acl`: 支持 `become`  


## Ref

* [ansible playbook中的条件判断与错误处理（fail模块 failed_when changed_when关键字）](https://blog.csdn.net/qq_36417677/article/details/105342211)
