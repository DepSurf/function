# Function: <code>_raw_write_unlock_irq</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void _raw_write_unlock_irq(rwlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff81f29cc0)
Location: kernel/locking/spinlock.c:356
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:do_exit
  - kernel/exit.c:forget_original_parent
  - kernel/exit.c:release_task
  - kernel/exit.c:release_task
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_traceme
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:ptrace_attach
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__do_sys_setpgid
  - fs/exec.c:begin_new_exec
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/fcntl.c:fasync_insert_entry
  - fs/fcntl.c:fasync_remove_entry
  - fs/fcntl.c:f_delown
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_send_events
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_remove
  - fs/eventpoll.c:ep_done_scan
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_session_to_parent
  - drivers/scsi/sg.c:sg_ioctl_common
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
ffffffff81f29cc0-ffffffff81f29cf4: _raw_write_unlock_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void _raw_write_unlock_irq(rwlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff820d5bd0)
Location: kernel/locking/spinlock.c:356
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:do_exit
  - kernel/exit.c:forget_original_parent
  - kernel/exit.c:release_task
  - kernel/exit.c:release_task
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_traceme
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:ptrace_attach
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__do_sys_setpgid
  - fs/exec.c:unshare_sighand
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/fcntl.c:fasync_insert_entry
  - fs/fcntl.c:fasync_remove_entry
  - fs/fcntl.c:f_delown
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_send_events
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_remove
  - fs/eventpoll.c:ep_done_scan
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_session_to_parent
  - drivers/scsi/sg.c:sg_ioctl_common
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
ffffffff820d5bd0-ffffffff820d5c10: _raw_write_unlock_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void _raw_write_unlock_irq(rwlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff82158fb0)
Location: kernel/locking/spinlock.c:356
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:do_exit
  - kernel/exit.c:forget_original_parent
  - kernel/exit.c:release_task
  - kernel/exit.c:release_task
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_traceme
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:ptrace_attach
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__do_sys_setpgid
  - fs/exec.c:unshare_sighand
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/fcntl.c:fasync_insert_entry
  - fs/fcntl.c:fasync_remove_entry
  - fs/fcntl.c:f_delown
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_send_events
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:__ep_remove
  - fs/eventpoll.c:ep_done_scan
  - fs/kernfs/dir.c:kernfs_rename_ns
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_session_to_parent
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_ioctl_common
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/af_netlink.c:netlink_change_ngroups
  - net/netlink/af_netlink.c:__netlink_kernel_create
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_realloc_groups
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_release
```
**Symbols:**

```
ffffffff82158fb0-ffffffff82158ff0: _raw_write_unlock_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void _raw_write_unlock_irq(rwlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff8223c830)
Location: kernel/locking/spinlock.c:356
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:exit_notify
  - kernel/exit.c:forget_original_parent
  - kernel/exit.c:release_task
  - kernel/exit.c:release_task
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_traceme
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:ptrace_attach
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__do_sys_setpgid
  - fs/exec.c:unshare_sighand
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/fcntl.c:fasync_insert_entry
  - fs/fcntl.c:fasync_remove_entry
  - fs/fcntl.c:f_delown
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_send_events
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:__ep_remove
  - fs/eventpoll.c:ep_done_scan
  - fs/kernfs/dir.c:kernfs_rename_ns
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_session_to_parent
  - drivers/scsi/sg.c:sg_ioctl_common
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
ffffffff8223c830-ffffffff8223c870: _raw_write_unlock_irq (STB_GLOBAL)
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
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void _raw_write_unlock_irq(rwlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/spinlock.c (ffffffff81aec630)
Location: kernel/locking/spinlock.c:341
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:release_task
  - kernel/exit.c:release_task
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_traceme
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:ptrace_attach
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/fcntl.c:fasync_insert_entry
  - fs/fcntl.c:fasync_remove_entry
  - fs/fcntl.c:f_modown
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_poll
  - fs/eventpoll.c:ep_remove
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - net/netlink/af_netlink.c:netlink_table_ungrab
```
**Symbols:**

```
ffffffff81aec630-ffffffff81aec655: _raw_write_unlock_irq (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<b>Flavor</b>
<ul>
</ul>
