Raspberry Pi
=========

Raspberry Piの基本設定のためのAnsible Role。

Requirements
------------

* Raspberry Pi 3 Model B
* Raspbian Buster with desktop
  * Version:September 2019
  * Release date:2019-09-26
  * Kernel version:4.19

Role Variables
--------------

/defaults/main.yml を参照する。

Example Playbook
----------------

Playbookに以下のように追加する。

```yaml
- hosts: servers
  roles:
    - raspberry pi
```

