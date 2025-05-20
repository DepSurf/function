# Function: <code>__raw_write_unlock_irq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8107f461)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffff81082788)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - kernel/exit.c:release_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
```
In kernel/ptrace.c (ffffffff8108acca)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_traceme
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:ptrace_request
```
```
In kernel/sys.c (ffffffff81094c38)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - kernel/sys.c:SyS_setpgid
  - kernel/sys.c:sys_setsid
```
```
In fs/exec.c (ffffffff812135ba)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
```
```
In fs/fcntl.c (ffffffff8121eb46)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - fs/fcntl.c:f_modown
```
```
In security/keys/keyctl.c (ffffffff813334c2)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/selinux/ss/services.c (ffffffff813596dd)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_set_bools
```
```
In drivers/scsi/sg.c (ffffffff815c68e9)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
```
```
In net/netlink/af_netlink.c (ffffffff8174d251)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_table_ungrab
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81081617)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
```
```
In kernel/exit.c (ffffffff810863bf)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:release_task
```
```
In kernel/ptrace.c (ffffffff8108f0ee)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_traceme
  - kernel/ptrace.c:ptrace_attach
```
```
In kernel/sys.c (ffffffff810980d9)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - kernel/sys.c:sys_setsid
  - kernel/sys.c:SyS_setpgid
```
```
In fs/exec.c (ffffffff8123a11e)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
```
```
In fs/fcntl.c (ffffffff812464d6)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - fs/fcntl.c:f_modown
```
```
In security/keys/keyctl.c (ffffffff81368366)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/selinux/ss/services.c (ffffffff8138f927)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
```
```
In drivers/scsi/sg.c (ffffffff8161f142)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
```
```
In net/netlink/af_netlink.c (ffffffff817b96b9)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_table_ungrab
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8108604f)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
```
```
In kernel/exit.c (ffffffff8108b32f)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:release_task
```
```
In kernel/ptrace.c (ffffffff81094078)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_traceme
  - kernel/ptrace.c:ptrace_attach
```
```
In kernel/sys.c (ffffffff8109d089)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - kernel/sys.c:sys_setsid
  - kernel/sys.c:SyS_setpgid
```
```
In fs/exec.c (ffffffff8124ce69)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
```
```
In fs/fcntl.c (ffffffff812594c3)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - fs/fcntl.c:f_modown
```
```
In security/keys/keyctl.c (ffffffff8137eb76)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/selinux/ss/services.c (ffffffff813a6547)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
```
```
In drivers/scsi/sg.c (ffffffff8164fc1f)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
```
```
In net/netlink/af_netlink.c (ffffffff817e9059)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_table_ungrab
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81082a96)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
```
```
In kernel/exit.c (ffffffff81088100)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:release_task
```
```
In kernel/ptrace.c (ffffffff8109115a)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_traceme
  - kernel/ptrace.c:ptrace_attach
```
```
In kernel/sys.c (ffffffff81099f69)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - kernel/sys.c:sys_setsid
  - kernel/sys.c:SyS_setpgid
```
```
In fs/exec.c (ffffffff81258e84)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
```
```
In fs/fcntl.c (ffffffff812655a3)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - fs/fcntl.c:f_modown
```
```
In security/keys/keyctl.c (ffffffff81392a06)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/selinux/ss/services.c (ffffffff813bcfaf)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
```
```
In drivers/scsi/sg.c (ffffffff81664247)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
```
```
In net/netlink/af_netlink.c (ffffffff81808d49)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_table_ungrab
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810898c4)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
```
```
In kernel/exit.c (ffffffff8108ee8b)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:release_task
```
```
In kernel/ptrace.c (ffffffff81097fca)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_traceme
  - kernel/ptrace.c:ptrace_attach
```
```
In kernel/sys.c (ffffffff810a0c49)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - kernel/sys.c:sys_setsid
  - kernel/sys.c:SyS_setpgid
```
```
In fs/exec.c (ffffffff8127b01a)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
```
```
In fs/fcntl.c (ffffffff81288311)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - fs/fcntl.c:f_delown
```
```
In security/keys/keyctl.c (ffffffff813b8066)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/selinux/ss/services.c (ffffffff813e3122)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
```
```
In drivers/scsi/sg.c (ffffffff816cd897)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
```
```
In net/netlink/af_netlink.c (ffffffff81887c19)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_table_ungrab
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8108d275)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
```
```
In kernel/exit.c (ffffffff8109298a)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
```
In kernel/ptrace.c (ffffffff8109b66c)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_traceme
  - kernel/ptrace.c:ptrace_attach
```
```
In kernel/sys.c (ffffffff810a749c)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
```
```
In fs/exec.c (ffffffff812a2468)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
```
```
In fs/fcntl.c (ffffffff812af668)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - fs/fcntl.c:fasync_insert_entry
  - fs/fcntl.c:fasync_remove_entry
  - fs/fcntl.c:f_modown
```
```
In security/keys/keyctl.c (ffffffff813e8c4c)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/selinux/ss/services.c (ffffffff8141389f)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
```
```
In drivers/scsi/sg.c (ffffffff8170a222)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
```
```
In net/netlink/af_netlink.c (ffffffff818db605)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_table_ungrab
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81094bc5)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
```
```
In kernel/exit.c (ffffffff8109ac7d)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
```
In kernel/ptrace.c (ffffffff810a38a0)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_traceme
  - kernel/ptrace.c:ptrace_attach
```
```
In kernel/sys.c (ffffffff810b01ac)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
```
```
In fs/exec.c (ffffffff812b72ed)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
```
```
In fs/fcntl.c (ffffffff812c47e8)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - fs/fcntl.c:fasync_insert_entry
  - fs/fcntl.c:fasync_remove_entry
  - fs/fcntl.c:f_modown
```
```
In security/keys/keyctl.c (ffffffff8140344a)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/selinux/ss/services.c (ffffffff8142fdcc)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
```
```
In drivers/scsi/sg.c (ffffffff8172c6aa)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
```
```
In net/netlink/af_netlink.c (ffffffff81907f05)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_table_ungrab
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81099640)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffff8109eefd)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:release_task
```
```
In kernel/ptrace.c (ffffffff810a8831)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_traceme
  - kernel/ptrace.c:ptrace_attach
```
```
In kernel/sys.c (ffffffff810b5b7a)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
```
```
In fs/exec.c (ffffffff812d4ce4)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
```
```
In fs/fcntl.c (ffffffff812e1241)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - fs/fcntl.c:fasync_insert_entry
  - fs/fcntl.c:fasync_remove_entry
  - fs/fcntl.c:f_modown
```
```
In fs/eventpoll.c (ffffffff813217fb)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_remove
```
```
In security/keys/keyctl.c (ffffffff81430059)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/selinux/ss/services.c (ffffffff8145d75e)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
```
```
In drivers/scsi/sg.c (ffffffff81767aa1)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
```
```
In net/netlink/af_netlink.c (ffffffff819691e5)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_table_ungrab
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8109fc3a)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffff810a548d)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:release_task
```
```
In kernel/ptrace.c (ffffffff810aee4b)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_traceme
  - kernel/ptrace.c:ptrace_attach
```
```
In kernel/sys.c (ffffffff810bc16a)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
```
```
In fs/exec.c (ffffffff812e6864)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
```
```
In fs/fcntl.c (ffffffff812f2cf1)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - fs/fcntl.c:fasync_insert_entry
  - fs/fcntl.c:fasync_remove_entry
  - fs/fcntl.c:f_modown
```
```
In fs/eventpoll.c (ffffffff813355eb)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_remove
```
```
In security/keys/keyctl.c (ffffffff81449db9)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/selinux/ss/services.c (ffffffff8147750e)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
```
```
In drivers/scsi/sg.c (ffffffff8178ba91)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
```
```
In net/netlink/af_netlink.c (ffffffff8199fc85)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_table_ungrab
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a6cce)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffff810ad244)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:exit_notify
  - kernel/exit.c:find_child_reaper
  - kernel/exit.c:release_task
```
```
In kernel/ptrace.c (ffffffff810b69e5)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_traceme
  - kernel/ptrace.c:ptrace_attach
```
```
In kernel/sys.c (ffffffff810c3b0a)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__do_sys_setpgid
```
```
In fs/exec.c (ffffffff8131dbda)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - fs/exec.c:unshare_sighand
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
```
```
In fs/fcntl.c (ffffffff8132af84)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - fs/fcntl.c:fasync_insert_entry
  - fs/fcntl.c:fasync_remove_entry
  - fs/fcntl.c:f_delown
```
```
In fs/eventpoll.c (ffffffff8136e5af)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_modify
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_remove
```
```
In security/keys/keyctl.c (ffffffff8149b7b9)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/selinux/ss/services.c (ffffffff814cc94c)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
```
```
In drivers/scsi/sg.c (ffffffff81850948)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_ioctl_common
```
```
In net/netlink/af_netlink.c (ffffffff81a79405)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_table_ungrab
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a280d)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffff810a890d)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:exit_notify
  - kernel/exit.c:find_child_reaper
  - kernel/exit.c:release_task
```
```
In kernel/ptrace.c (ffffffff810b1c5d)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_traceme
  - kernel/ptrace.c:ptrace_attach
```
```
In kernel/sys.c (ffffffff810beefa)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__do_sys_setpgid
```
```
In fs/exec.c (ffffffff81328a3a)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - fs/exec.c:unshare_sighand
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
```
```
In fs/fcntl.c (ffffffff81336554)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - fs/fcntl.c:fasync_insert_entry
  - fs/fcntl.c:fasync_remove_entry
  - fs/fcntl.c:f_delown
```
```
In fs/eventpoll.c (ffffffff8137baa0)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_send_events
  - fs/eventpoll.c:ep_modify
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_remove
  - fs/eventpoll.c:ep_done_scan
```
```
In security/keys/keyctl.c (ffffffff814b9249)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In drivers/scsi/sg.c (ffffffff81860d99)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_ioctl_common
```
```
In net/netlink/af_netlink.c (ffffffff81a82215)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_table_ungrab
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a34d6)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffff810a9782)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:exit_notify
  - kernel/exit.c:forget_original_parent
  - kernel/exit.c:release_task
```
```
In kernel/ptrace.c (ffffffff810b2e42)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_traceme
  - kernel/ptrace.c:ptrace_attach
```
```
In kernel/sys.c (ffffffff810c088a)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__do_sys_setpgid
```
```
In fs/exec.c (ffffffff8132fc5d)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - fs/exec.c:begin_new_exec
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
```
```
In fs/fcntl.c (ffffffff8133c6f4)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - fs/fcntl.c:fasync_insert_entry
  - fs/fcntl.c:fasync_remove_entry
  - fs/fcntl.c:f_delown
```
```
In fs/eventpoll.c (ffffffff813839b5)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_send_events
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_remove
  - fs/eventpoll.c:ep_done_scan
```
```
In security/keys/keyctl.c (ffffffff814bf099)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In drivers/scsi/sg.c (ffffffff81843a5a)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_ioctl_common
```
```
In net/netlink/af_netlink.c (ffffffff81a6b2f5)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_table_ungrab
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810b4c64)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffff810bb272)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:exit_notify
  - kernel/exit.c:forget_original_parent
  - kernel/exit.c:release_task
```
```
In kernel/ptrace.c (ffffffff810c4fe2)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_traceme
  - kernel/ptrace.c:ptrace_attach
```
```
In kernel/sys.c (ffffffff810d337a)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__do_sys_setpgid
```
```
In fs/exec.c (ffffffff8137d286)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - fs/exec.c:begin_new_exec
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
```
```
In fs/fcntl.c (ffffffff8138a3f4)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - fs/fcntl.c:fasync_insert_entry
  - fs/fcntl.c:fasync_remove_entry
  - fs/fcntl.c:f_delown
```
```
In fs/eventpoll.c (ffffffff813d0c55)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_send_events
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_remove
  - fs/eventpoll.c:ep_done_scan
```
```
In security/keys/keyctl.c (ffffffff81517ab9)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In drivers/scsi/sg.c (ffffffff818d0526)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_ioctl_common
```
```
In net/netlink/af_netlink.c (ffffffff81b24925)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_table_ungrab
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff81f29cc5)
Location: include/linux/rwlock_api_smp.h:269
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_unlock_irq
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff820d5bd5)
Location: include/linux/rwlock_api_smp.h:269
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_unlock_irq
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff82158fb5)
Location: include/linux/rwlock_api_smp.h:269
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_unlock_irq
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff8223c835)
Location: include/linux/rwlock_api_smp.h:269
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_unlock_irq
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffff8000100f419c)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffff8000100fb380)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:release_task
```
```
In kernel/ptrace.c (ffff80001010941c)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_traceme
  - kernel/ptrace.c:ptrace_attach
```
```
In kernel/sys.c (ffff800010118c18)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__arm64_sys_setpgid
```
```
In fs/exec.c (ffff80001038eb14)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
```
```
In fs/fcntl.c (ffff80001039d300)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - fs/fcntl.c:fasync_insert_entry
  - fs/fcntl.c:fasync_remove_entry
  - fs/fcntl.c:f_modown
```
```
In fs/eventpoll.c (ffff8000103f230c)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - fs/eventpoll.c:__do_sys_epoll_ctl
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_remove
```
```
In security/keys/keyctl.c (ffff800010533b30)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/selinux/ss/services.c (ffff800010567180)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
```
```
In drivers/scsi/sg.c (ffff800010994570)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
```
```
In net/netlink/af_netlink.c (ffff800010c4e140)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_table_ungrab
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (c0352c70)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (c035940c)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:release_task
```
```
In kernel/ptrace.c (c036263c)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - kernel/ptrace.c:__se_sys_ptrace
  - kernel/ptrace.c:__se_sys_ptrace
  - kernel/ptrace.c:ptrace_request
```
```
In kernel/sys.c (c036d274)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__se_sys_setpgid
```
```
In fs/exec.c (c0575088)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
```
```
In fs/fcntl.c (c0582b70)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - fs/fcntl.c:fasync_insert_entry
  - fs/fcntl.c:fasync_remove_entry
  - fs/fcntl.c:f_modown
```
```
In fs/eventpoll.c (c05c6568)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_wait
  - fs/eventpoll.c:do_epoll_wait
  - fs/eventpoll.c:do_epoll_wait
  - fs/eventpoll.c:__do_sys_epoll_ctl
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_remove
```
```
In security/keys/keyctl.c (c06eb364)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/selinux/ss/services.c (c071b708)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
```
```
In drivers/scsi/sg.c (c0a64c3c)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
```
```
In net/netlink/af_netlink.c (c0d5e3ac)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_table_ungrab
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (c00000000013a5d4)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (c00000000014246c)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:release_task
```
```
In kernel/ptrace.c (c0000000001504f8)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_traceme
  - kernel/ptrace.c:ptrace_attach
```
```
In kernel/sys.c (c0000000001606c0)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__se_sys_setpgid
```
```
In fs/exec.c (c000000000485a7c)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
```
```
In fs/fcntl.c (c000000000498050)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - fs/fcntl.c:fasync_insert_entry
  - fs/fcntl.c:fasync_remove_entry
  - fs/fcntl.c:f_modown
```
```
In fs/eventpoll.c (c0000000004fa4b8)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - fs/eventpoll.c:__se_sys_epoll_ctl
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_remove
```
```
In security/keys/keyctl.c (c0000000006819dc)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/selinux/ss/services.c (c0000000006ca4b0)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
```
```
In drivers/scsi/sg.c (c000000000a560c8)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
```
```
In net/netlink/af_netlink.c (c000000000d4c4dc)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_table_ungrab
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffe0000c0954)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffe0000c4ffa)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:release_task
```
```
In kernel/ptrace.c (ffffffe0000cc366)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - kernel/ptrace.c:__se_sys_ptrace
  - kernel/ptrace.c:__se_sys_ptrace
  - kernel/ptrace.c:ptrace_request
```
```
In kernel/sys.c (ffffffe0000d3fa8)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__se_sys_setpgid
```
```
In fs/exec.c (ffffffe00025e40e)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
```
```
In fs/fcntl.c (ffffffe0002693a2)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - fs/fcntl.c:fasync_insert_entry
  - fs/fcntl.c:fasync_remove_entry
  - fs/fcntl.c:f_modown
```
```
In fs/eventpoll.c (ffffffe0002a331e)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_wait
  - fs/eventpoll.c:do_epoll_wait
  - fs/eventpoll.c:do_epoll_wait
  - fs/eventpoll.c:__se_sys_epoll_ctl
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_remove
```
```
In security/keys/keyctl.c (ffffffe000393f46)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/selinux/ss/services.c (ffffffe0003bcf30)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
```
```
In drivers/scsi/sg.c (ffffffe0005f5ff6)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
```
```
In net/netlink/af_netlink.c (ffffffe0007ba2bc)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_table_ungrab
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8109955a)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffff8109edad)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:release_task
```
```
In kernel/ptrace.c (ffffffff810a91bb)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_traceme
  - kernel/ptrace.c:ptrace_attach
```
```
In kernel/sys.c (ffffffff810b64da)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
```
```
In fs/exec.c (ffffffff812dee44)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
```
```
In fs/fcntl.c (ffffffff812eb2d1)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - fs/fcntl.c:fasync_insert_entry
  - fs/fcntl.c:fasync_remove_entry
  - fs/fcntl.c:f_modown
```
```
In fs/eventpoll.c (ffffffff8132dbcb)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_remove
```
```
In security/keys/keyctl.c (ffffffff81442399)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/selinux/ss/services.c (ffffffff8146faee)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
```
```
In drivers/scsi/sg.c (ffffffff81740181)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
```
```
In net/netlink/af_netlink.c (ffffffff8193faf5)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_table_ungrab
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81087faa)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffff8108d7d0)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:release_task
```
```
In kernel/ptrace.c (ffffffff81097b8b)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_traceme
  - kernel/ptrace.c:ptrace_attach
```
```
In kernel/sys.c (ffffffff810a4e1a)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
```
```
In fs/exec.c (ffffffff812cef69)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
```
```
In fs/fcntl.c (ffffffff812dbf01)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - fs/fcntl.c:fasync_insert_entry
  - fs/fcntl.c:fasync_remove_entry
  - fs/fcntl.c:f_modown
```
```
In fs/eventpoll.c (ffffffff8131df53)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_remove
```
```
In security/keys/keyctl.c (ffffffff81432df4)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/selinux/ss/services.c (ffffffff814604e6)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
```
```
In drivers/scsi/sg.c (ffffffff81721e21)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
```
```
In net/netlink/af_netlink.c (ffffffff818f95f5)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_table_ungrab
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8109950a)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffff8109ed5d)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:release_task
```
```
In kernel/ptrace.c (ffffffff810a871b)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_traceme
  - kernel/ptrace.c:ptrace_attach
```
```
In kernel/sys.c (ffffffff810b5a3a)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
```
```
In fs/exec.c (ffffffff812dcc54)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
```
```
In fs/fcntl.c (ffffffff812e90e1)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - fs/fcntl.c:fasync_insert_entry
  - fs/fcntl.c:fasync_remove_entry
  - fs/fcntl.c:f_modown
```
```
In fs/eventpoll.c (ffffffff8132b69b)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_remove
```
```
In security/keys/keyctl.c (ffffffff8143e539)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/selinux/ss/services.c (ffffffff8146bb8e)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
```
```
In drivers/scsi/sg.c (ffffffff81780911)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
```
```
In net/netlink/af_netlink.c (ffffffff81990c85)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_table_ungrab
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff81aec635)
Location: include/linux/rwlock_api_smp.h:263
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_unlock_irq
```
</details>
</li>
</ul>

## Differences
