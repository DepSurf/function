# Function: <code>_raw_write_lock_irq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void _raw_write_lock_irq(rwlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff81824150)
Location: kernel/locking/spinlock.c:309
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/exit.c:release_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/ptrace.c:ptrace_traceme
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:ptrace_request
  - kernel/sys.c:SyS_setpgid
  - kernel/sys.c:sys_setsid
  - fs/fcntl.c:f_modown
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_set_bools
  - drivers/scsi/sg.c:sg_ioctl
```
**Symbols:**

```
ffffffff81824150-ffffffff81824177: _raw_write_lock_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void _raw_write_lock_irq(rwlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff8189ee00)
Location: kernel/locking/spinlock.c:309
Inline: False
Direct callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:release_task
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_traceme
  - kernel/ptrace.c:ptrace_attach
  - kernel/sys.c:sys_setsid
  - kernel/sys.c:SyS_setpgid
  - fs/fcntl.c:f_modown
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
  - drivers/scsi/sg.c:sg_ioctl
```
**Symbols:**

```
ffffffff8189ee00-ffffffff8189ee28: _raw_write_lock_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void _raw_write_lock_irq(rwlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff818d42c0)
Location: kernel/locking/spinlock.c:309
Inline: False
Direct callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:release_task
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_traceme
  - kernel/ptrace.c:ptrace_attach
  - kernel/sys.c:sys_setsid
  - kernel/sys.c:SyS_setpgid
  - fs/fcntl.c:f_modown
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
  - drivers/scsi/sg.c:sg_ioctl
```
**Symbols:**

```
ffffffff818d42c0-ffffffff818d42e8: _raw_write_lock_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void _raw_write_lock_irq(rwlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff8190b430)
Location: kernel/locking/spinlock.c:309
Inline: False
Direct callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:release_task
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_traceme
  - kernel/ptrace.c:ptrace_attach
  - kernel/sys.c:sys_setsid
  - kernel/sys.c:SyS_setpgid
  - fs/fcntl.c:f_modown
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
  - drivers/scsi/sg.c:sg_ioctl
```
**Symbols:**

```
ffffffff8190b430-ffffffff8190b458: _raw_write_lock_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void _raw_write_lock_irq(rwlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff819958d0)
Location: kernel/locking/spinlock.c:302
Inline: False
Direct callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:release_task
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_traceme
  - kernel/ptrace.c:ptrace_attach
  - kernel/sys.c:sys_setsid
  - kernel/sys.c:SyS_setpgid
  - fs/fcntl.c:f_delown
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
  - drivers/scsi/sg.c:sg_ioctl
```
**Symbols:**

```
ffffffff819958d0-ffffffff819958f8: _raw_write_lock_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void _raw_write_lock_irq(rwlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff819f1e40)
Location: kernel/locking/spinlock.c:302
Inline: False
Direct callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_traceme
  - kernel/ptrace.c:ptrace_attach
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
  - fs/fcntl.c:fasync_insert_entry
  - fs/fcntl.c:fasync_remove_entry
  - fs/fcntl.c:f_modown
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
  - drivers/scsi/sg.c:sg_ioctl
```
**Symbols:**

```
ffffffff819f1e40-ffffffff819f1e68: _raw_write_lock_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void _raw_write_lock_irq(rwlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff81a2d3c0)
Location: kernel/locking/spinlock.c:302
Inline: False
Direct callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_traceme
  - kernel/ptrace.c:ptrace_attach
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
  - fs/fcntl.c:fasync_insert_entry
  - fs/fcntl.c:fasync_remove_entry
  - fs/fcntl.c:f_modown
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
  - drivers/scsi/sg.c:sg_ioctl
```
**Symbols:**

```
ffffffff81a2d3c0-ffffffff81a2d3e6: _raw_write_lock_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void _raw_write_lock_irq(rwlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff81a9d520)
Location: kernel/locking/spinlock.c:309
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:release_task
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_traceme
  - kernel/ptrace.c:ptrace_attach
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/fcntl.c:fasync_insert_entry
  - fs/fcntl.c:fasync_remove_entry
  - fs/fcntl.c:f_modown
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_remove
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
  - drivers/scsi/sg.c:sg_ioctl
```
**Symbols:**

```
ffffffff81a9d520-ffffffff81a9d546: _raw_write_lock_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void _raw_write_lock_irq(rwlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff81ad4d00)
Location: kernel/locking/spinlock.c:309
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:release_task
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_traceme
  - kernel/ptrace.c:ptrace_attach
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/fcntl.c:fasync_insert_entry
  - fs/fcntl.c:fasync_remove_entry
  - fs/fcntl.c:f_modown
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_remove
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
  - drivers/scsi/sg.c:sg_ioctl
```
**Symbols:**

```
ffffffff81ad4d00-ffffffff81ad4d26: _raw_write_lock_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void _raw_write_lock_irq(rwlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff81bccd00)
Location: kernel/locking/spinlock.c:309
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:exit_notify
  - kernel/exit.c:find_child_reaper
  - kernel/exit.c:release_task
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_traceme
  - kernel/ptrace.c:ptrace_attach
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__do_sys_setpgid
  - fs/exec.c:unshare_sighand
  - fs/exec.c:de_thread
  - fs/fcntl.c:fasync_insert_entry
  - fs/fcntl.c:fasync_remove_entry
  - fs/fcntl.c:f_delown
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_modify
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_remove
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
  - drivers/scsi/sg.c:sg_ioctl_common
  - net/netlink/af_netlink.c:netlink_change_ngroups
  - net/netlink/af_netlink.c:__netlink_kernel_create
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_realloc_groups
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_remove
```
**Symbols:**

```
ffffffff81bccd00-ffffffff81bccd26: _raw_write_lock_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void _raw_write_lock_irq(rwlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff81c45860)
Location: kernel/locking/spinlock.c:309
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:exit_notify
  - kernel/exit.c:find_child_reaper
  - kernel/exit.c:release_task
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_traceme
  - kernel/ptrace.c:ptrace_attach
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__do_sys_setpgid
  - fs/exec.c:unshare_sighand
  - fs/exec.c:de_thread
  - fs/fcntl.c:fasync_insert_entry
  - fs/fcntl.c:fasync_remove_entry
  - fs/fcntl.c:f_delown
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_send_events
  - fs/eventpoll.c:ep_modify
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_remove
  - fs/eventpoll.c:ep_done_scan
  - security/keys/keyctl.c:keyctl_session_to_parent
  - drivers/scsi/sg.c:sg_ioctl_common
  - net/netlink/af_netlink.c:netlink_change_ngroups
  - net/netlink/af_netlink.c:__netlink_kernel_create
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_realloc_groups
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_remove
```
**Symbols:**

```
ffffffff81c45860-ffffffff81c45886: _raw_write_lock_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void _raw_write_lock_irq(rwlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff81c38b20)
Location: kernel/locking/spinlock.c:309
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:exit_notify
  - kernel/exit.c:forget_original_parent
  - kernel/exit.c:release_task
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_traceme
  - kernel/ptrace.c:ptrace_attach
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__do_sys_setpgid
  - fs/exec.c:begin_new_exec
  - fs/exec.c:de_thread
  - fs/fcntl.c:fasync_insert_entry
  - fs/fcntl.c:fasync_remove_entry
  - fs/fcntl.c:f_delown
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_send_events
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_remove
  - fs/eventpoll.c:ep_done_scan
  - security/keys/keyctl.c:keyctl_session_to_parent
  - drivers/scsi/sg.c:sg_ioctl_common
  - net/netlink/af_netlink.c:netlink_change_ngroups
  - net/netlink/af_netlink.c:__netlink_kernel_create
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_realloc_groups
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_remove
```
**Symbols:**

```
ffffffff81c38b20-ffffffff81c38b46: _raw_write_lock_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void _raw_write_lock_irq(rwlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff81d57400)
Location: kernel/locking/spinlock.c:314
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:exit_notify
  - kernel/exit.c:forget_original_parent
  - kernel/exit.c:release_task
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_traceme
  - kernel/ptrace.c:ptrace_attach
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__do_sys_setpgid
  - fs/exec.c:begin_new_exec
  - fs/exec.c:de_thread
  - fs/fcntl.c:fasync_insert_entry
  - fs/fcntl.c:fasync_remove_entry
  - fs/fcntl.c:f_delown
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_send_events
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_remove
  - fs/eventpoll.c:ep_done_scan
  - security/keys/keyctl.c:keyctl_session_to_parent
  - drivers/scsi/sg.c:sg_ioctl_common
  - net/netlink/af_netlink.c:netlink_change_ngroups
  - net/netlink/af_netlink.c:__netlink_kernel_create
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_realloc_groups
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_release
```
**Symbols:**

```
ffffffff81d57400-ffffffff81d57426: _raw_write_lock_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void _raw_write_lock_irq(rwlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff81f2a010)
Location: kernel/locking/spinlock.c:324
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:forget_original_parent
  - kernel/exit.c:release_task
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_traceme
  - kernel/ptrace.c:ptrace_attach
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__do_sys_setpgid
  - fs/exec.c:begin_new_exec
  - fs/exec.c:de_thread
  - fs/fcntl.c:fasync_insert_entry
  - fs/fcntl.c:fasync_remove_entry
  - fs/fcntl.c:f_delown
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_send_events
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_remove
  - fs/eventpoll.c:ep_done_scan
  - security/keys/keyctl.c:keyctl_session_to_parent
  - drivers/scsi/sg.c:sg_ioctl_common
  - net/netlink/af_netlink.c:netlink_change_ngroups
  - net/netlink/af_netlink.c:__netlink_kernel_create
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_realloc_groups
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_release
```
**Symbols:**

```
ffffffff81f2a010-ffffffff81f2a050: _raw_write_lock_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void _raw_write_lock_irq(rwlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff820d6030)
Location: kernel/locking/spinlock.c:324
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:forget_original_parent
  - kernel/exit.c:release_task
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_traceme
  - kernel/ptrace.c:ptrace_attach
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__do_sys_setpgid
  - fs/exec.c:unshare_sighand
  - fs/exec.c:de_thread
  - fs/fcntl.c:fasync_insert_entry
  - fs/fcntl.c:fasync_remove_entry
  - fs/fcntl.c:f_delown
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_send_events
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_remove
  - fs/eventpoll.c:ep_done_scan
  - security/keys/keyctl.c:keyctl_session_to_parent
  - drivers/scsi/sg.c:sg_ioctl_common
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/af_netlink.c:netlink_change_ngroups
  - net/netlink/af_netlink.c:__netlink_kernel_create
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_realloc_groups
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_release
```
**Symbols:**

```
ffffffff820d6030-ffffffff820d6085: _raw_write_lock_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void _raw_write_lock_irq(rwlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff82159410)
Location: kernel/locking/spinlock.c:324
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:forget_original_parent
  - kernel/exit.c:release_task
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_traceme
  - kernel/ptrace.c:ptrace_attach
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__do_sys_setpgid
  - fs/exec.c:unshare_sighand
  - fs/exec.c:de_thread
  - fs/fcntl.c:fasync_insert_entry
  - fs/fcntl.c:fasync_remove_entry
  - fs/fcntl.c:f_delown
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_send_events
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:__ep_remove
  - fs/eventpoll.c:ep_done_scan
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_rename_ns
  - security/keys/keyctl.c:keyctl_session_to_parent
  - drivers/scsi/sg.c:sg_ioctl_common
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/af_netlink.c:netlink_change_ngroups
  - net/netlink/af_netlink.c:__netlink_kernel_create
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_realloc_groups
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_release
```
**Symbols:**

```
ffffffff82159410-ffffffff82159465: _raw_write_lock_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void _raw_write_lock_irq(rwlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff8223cc90)
Location: kernel/locking/spinlock.c:324
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:exit_notify
  - kernel/exit.c:forget_original_parent
  - kernel/exit.c:release_task
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_traceme
  - kernel/ptrace.c:ptrace_attach
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__do_sys_setpgid
  - fs/exec.c:unshare_sighand
  - fs/exec.c:de_thread
  - fs/fcntl.c:fasync_insert_entry
  - fs/fcntl.c:fasync_remove_entry
  - fs/fcntl.c:f_delown
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_send_events
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:__ep_remove
  - fs/eventpoll.c:ep_done_scan
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_rename_ns
  - security/keys/keyctl.c:keyctl_session_to_parent
  - drivers/scsi/sg.c:sg_ioctl_common
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/af_netlink.c:netlink_change_ngroups
  - net/netlink/af_netlink.c:__netlink_kernel_create
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_realloc_groups
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_release
```
**Symbols:**

```
ffffffff8223cc90-ffffffff8223cce5: _raw_write_lock_irq (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void _raw_write_lock_irq(rwlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (c0e9f4fc)
Location: kernel/locking/spinlock.c:309
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:release_task
  - kernel/ptrace.c:__se_sys_ptrace
  - kernel/ptrace.c:__se_sys_ptrace
  - kernel/ptrace.c:ptrace_request
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__se_sys_setpgid
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/fcntl.c:fasync_insert_entry
  - fs/fcntl.c:fasync_remove_entry
  - fs/fcntl.c:f_modown
  - fs/eventpoll.c:do_epoll_wait
  - fs/eventpoll.c:do_epoll_wait
  - fs/eventpoll.c:do_epoll_wait
  - fs/eventpoll.c:__do_sys_epoll_ctl
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_remove
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
  - drivers/scsi/sg.c:sg_ioctl
```
**Symbols:**

```
c0e9f4fc-c0e9f53c: _raw_write_lock_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void _raw_write_lock_irq(rwlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (c000000000eeab40)
Location: kernel/locking/spinlock.c:309
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:release_task
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_traceme
  - kernel/ptrace.c:ptrace_attach
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__se_sys_setpgid
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/fcntl.c:fasync_insert_entry
  - fs/fcntl.c:fasync_remove_entry
  - fs/fcntl.c:f_modown
  - fs/eventpoll.c:__se_sys_epoll_ctl
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_remove
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
  - drivers/scsi/sg.c:sg_ioctl
```
**Symbols:**

```
c000000000eeab40-c000000000eeac14: _raw_write_lock_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void _raw_write_lock_irq(rwlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffe0008c945e)
Location: kernel/locking/spinlock.c:309
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:release_task
  - kernel/ptrace.c:__se_sys_ptrace
  - kernel/ptrace.c:__se_sys_ptrace
  - kernel/ptrace.c:ptrace_request
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__se_sys_setpgid
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/fcntl.c:fasync_insert_entry
  - fs/fcntl.c:fasync_remove_entry
  - fs/fcntl.c:f_modown
  - fs/eventpoll.c:do_epoll_wait
  - fs/eventpoll.c:do_epoll_wait
  - fs/eventpoll.c:do_epoll_wait
  - fs/eventpoll.c:__se_sys_epoll_ctl
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_remove
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
  - drivers/scsi/sg.c:sg_ioctl
```
**Symbols:**

```
ffffffe0008c945e-ffffffe0008c9494: _raw_write_lock_irq (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void _raw_write_lock_irq(rwlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff81a73b70)
Location: kernel/locking/spinlock.c:309
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:release_task
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_traceme
  - kernel/ptrace.c:ptrace_attach
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/fcntl.c:fasync_insert_entry
  - fs/fcntl.c:fasync_remove_entry
  - fs/fcntl.c:f_modown
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_remove
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
  - drivers/scsi/sg.c:sg_ioctl
```
**Symbols:**

```
ffffffff81a73b70-ffffffff81a73b96: _raw_write_lock_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void _raw_write_lock_irq(rwlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff81a2fee0)
Location: kernel/locking/spinlock.c:309
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:release_task
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_traceme
  - kernel/ptrace.c:ptrace_attach
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/fcntl.c:fasync_insert_entry
  - fs/fcntl.c:fasync_remove_entry
  - fs/fcntl.c:f_modown
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_remove
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
  - drivers/scsi/sg.c:sg_ioctl
```
**Symbols:**

```
ffffffff81a2fee0-ffffffff81a2feff: _raw_write_lock_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void _raw_write_lock_irq(rwlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff81adff80)
Location: kernel/locking/spinlock.c:309
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:release_task
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_traceme
  - kernel/ptrace.c:ptrace_attach
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/fcntl.c:fasync_insert_entry
  - fs/fcntl.c:fasync_remove_entry
  - fs/fcntl.c:f_modown
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_remove
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
  - drivers/scsi/sg.c:sg_ioctl
```
**Symbols:**

```
ffffffff81adff80-ffffffff81adffa6: _raw_write_lock_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void _raw_write_lock_irq(rwlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff81aec960)
Location: kernel/locking/spinlock.c:309
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:release_task
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_traceme
  - kernel/ptrace.c:ptrace_attach
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/fcntl.c:fasync_insert_entry
  - fs/fcntl.c:fasync_remove_entry
  - fs/fcntl.c:f_modown
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_remove
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
  - drivers/scsi/sg.c:sg_ioctl
```
**Symbols:**

```
ffffffff81aec960-ffffffff81aec98d: _raw_write_lock_irq (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
