# Function: <code>pid_vnr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
pid_t pid_vnr(struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff8109dc90)
Location: kernel/pid.c:514
Inline: False
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/sysctl.c:proc_do_cad_pid
  - kernel/signal.c:do_send_specific
  - kernel/signal.c:do_tkill
  - kernel/signal.c:SYSC_kill
  - kernel/sys.c:sys_getpid
  - kernel/sys.c:sys_getppid
  - kernel/sys.c:sys_getpgrp
  - kernel/sys.c:SyS_getsid
  - kernel/sys.c:sys_setsid
  - kernel/cgroup.c:pidlist_array_load
  - kernel/audit.c:audit_receive_msg
  - kernel/trace/ftrace.c:fpid_show
  - fs/fcntl.c:f_getown
  - fs/fcntl.c:SyS_fcntl
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/locks.c:lock_get_status
  - fs/locks.c:posix_test_lock
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/fuse/file.c:fuse_getlk
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgrcv
  - ipc/sem.c:SYSC_semtimedop
  - ipc/sem.c:SyS_semctl
  - ipc/sem.c:exit_sem
  - ipc/shm.c:shm_close
  - ipc/shm.c:newseg
  - ipc/mqueue.c:mqueue_read_file
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/condition.c:tomoyo_condition
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - net/core/sock.c:sock_getsockopt
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_stream_read_generic
```
**Symbols:**

```
ffffffff8109dc90-ffffffff8109dceb: pid_vnr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
pid_t pid_vnr(struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810a12f0)
Location: kernel/pid.c:514
Inline: False
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/sysctl.c:proc_do_cad_pid
  - kernel/signal.c:do_tkill
  - kernel/signal.c:do_send_specific
  - kernel/signal.c:SYSC_kill
  - kernel/sys.c:sys_setsid
  - kernel/sys.c:SyS_getsid
  - kernel/sys.c:sys_getpgrp
  - kernel/sys.c:sys_getppid
  - kernel/sys.c:sys_getpid
  - kernel/cgroup.c:cgroup_pidlist_start
  - kernel/audit.c:audit_receive_msg
  - fs/fcntl.c:SyS_fcntl
  - fs/fcntl.c:f_getown
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/locks.c:lock_get_status
  - fs/locks.c:posix_test_lock
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/fuse/file.c:fuse_getlk
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/sem.c:exit_sem
  - ipc/sem.c:SYSC_semtimedop
  - ipc/sem.c:SyS_semctl
  - ipc/sem.c:semctl_main
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
  - ipc/mqueue.c:mqueue_read_file
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/condition.c:tomoyo_condition
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - net/core/sock.c:sock_getsockopt
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
**Symbols:**

```
ffffffff810a12f0-ffffffff810a134b: pid_vnr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
pid_t pid_vnr(struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810a63b0)
Location: kernel/pid.c:514
Inline: False
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/sysctl.c:proc_do_cad_pid
  - kernel/signal.c:do_tkill
  - kernel/signal.c:do_send_specific
  - kernel/signal.c:SYSC_kill
  - kernel/sys.c:sys_setsid
  - kernel/sys.c:SyS_getsid
  - kernel/sys.c:sys_getpgrp
  - kernel/sys.c:sys_getppid
  - kernel/sys.c:sys_getpid
  - kernel/cgroup.c:cgroup_pidlist_start
  - kernel/audit.c:audit_receive_msg
  - fs/fcntl.c:SyS_fcntl
  - fs/fcntl.c:f_getown
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/locks.c:posix_test_lock
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/fuse/file.c:fuse_getlk
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/sem.c:exit_sem
  - ipc/sem.c:SYSC_semtimedop
  - ipc/sem.c:SyS_semctl
  - ipc/sem.c:semctl_main
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
  - ipc/mqueue.c:mqueue_read_file
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/condition.c:tomoyo_condition
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - net/core/sock.c:sock_getsockopt
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
**Symbols:**

```
ffffffff810a63b0-ffffffff810a640b: pid_vnr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
pid_t pid_vnr(struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810a3380)
Location: kernel/pid.c:515
Inline: False
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/sysctl.c:proc_do_cad_pid
  - kernel/sys.c:sys_setsid
  - kernel/sys.c:SyS_getsid
  - kernel/sys.c:sys_getpgrp
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_getown
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/locks.c:posix_test_lock
  - fs/fuse/file.c:fuse_getlk
  - ipc/mqueue.c:mqueue_read_file
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - net/core/sock.c:sock_getsockopt
  - net/core/scm.c:__scm_send
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
**Symbols:**

```
ffffffff810a3380-ffffffff810a33d2: pid_vnr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
pid_t pid_vnr(struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810a9ba0)
Location: kernel/pid.c:384
Inline: False
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/sysctl.c:proc_do_cad_pid
  - kernel/sys.c:sys_setsid
  - kernel/sys.c:SyS_getsid
  - kernel/sys.c:sys_getpgrp
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_getown
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - ipc/mqueue.c:mqueue_read_file
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - net/core/sock.c:sock_getsockopt
  - net/core/scm.c:__scm_send
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
**Symbols:**

```
ffffffff810a9ba0-ffffffff810a9bf3: pid_vnr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
pid_t pid_vnr(struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810b07b0)
Location: kernel/pid.c:409
Inline: False
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/sysctl.c:proc_do_cad_pid
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__ia32_sys_getsid
  - kernel/sys.c:__x64_sys_getsid
  - kernel/sys.c:__x64_sys_getpgrp
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_getown
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - ipc/msg.c:msgctl_stat
  - ipc/msg.c:msgctl_stat
  - ipc/sem.c:semctl_main
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shmctl_stat
  - ipc/mqueue.c:mqueue_read_file
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - net/core/sock.c:sock_getsockopt
  - net/core/scm.c:__scm_send
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
**Symbols:**

```
ffffffff810b07b0-ffffffff810b0805: pid_vnr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
pid_t pid_vnr(struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810b98f0)
Location: kernel/pid.c:416
Inline: False
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/sysctl.c:proc_do_cad_pid
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__ia32_sys_getsid
  - kernel/sys.c:__x64_sys_getsid
  - kernel/sys.c:__x64_sys_getpgrp
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_getown
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - ipc/msg.c:msgctl_stat
  - ipc/msg.c:msgctl_stat
  - ipc/sem.c:semctl_main
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shmctl_stat
  - ipc/mqueue.c:mqueue_read_file
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - net/core/sock.c:sock_getsockopt
  - net/core/scm.c:__scm_send
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
**Symbols:**

```
ffffffff810b98f0-ffffffff810b9941: pid_vnr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
pid_t pid_vnr(struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810bf650)
Location: kernel/pid.c:419
Inline: False
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/sysctl.c:proc_do_cad_pid
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__ia32_sys_getsid
  - kernel/sys.c:__x64_sys_getsid
  - kernel/sys.c:do_getpgid
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:auditd_pid_vnr
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_getown
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - ipc/msg.c:msgctl_stat
  - ipc/msg.c:msgctl_stat
  - ipc/sem.c:semctl_main
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shmctl_stat
  - ipc/mqueue.c:mqueue_read_file
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - net/core/sock.c:sock_getsockopt
  - net/core/scm.c:__scm_send
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
**Symbols:**

```
ffffffff810bf650-ffffffff810bf6a5: pid_vnr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
pid_t pid_vnr(struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810c5a20)
Location: kernel/pid.c:419
Inline: False
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/sysctl.c:proc_do_cad_pid
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__ia32_sys_getsid
  - kernel/sys.c:__x64_sys_getsid
  - kernel/sys.c:do_getpgid
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:auditd_pid_vnr
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_getown
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - ipc/msg.c:msgctl_stat
  - ipc/msg.c:msgctl_stat
  - ipc/sem.c:semctl_main
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shmctl_stat
  - ipc/mqueue.c:mqueue_read_file
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - net/core/sock.c:sock_getsockopt
  - net/core/scm.c:__scm_send
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
**Symbols:**

```
ffffffff810c5a20-ffffffff810c5a75: pid_vnr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
pid_t pid_vnr(struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810cd350)
Location: kernel/pid.c:485
Inline: False
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/sysctl.c:proc_do_cad_pid
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__ia32_sys_getsid
  - kernel/sys.c:__x64_sys_getsid
  - kernel/sys.c:__do_sys_getpgrp
  - kernel/sys.c:__ia32_sys_getpgid
  - kernel/sys.c:__x64_sys_getpgid
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - fs/fcntl.c:f_getown_ex
  - fs/fcntl.c:f_getown
  - fs/notify/fanotify/fanotify_user.c:copy_event_to_user
  - ipc/msg.c:msgctl_stat
  - ipc/msg.c:msgctl_stat
  - ipc/sem.c:semctl_main
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shmctl_stat
  - ipc/mqueue.c:mqueue_read_file
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - net/core/sock.c:sock_getsockopt
  - net/core/scm.c:__scm_send
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
**Symbols:**

```
ffffffff810cd350-ffffffff810cd3a5: pid_vnr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
pid_t pid_vnr(struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810c7e60)
Location: kernel/pid.c:486
Inline: False
Direct callers:
  - kernel/fork.c:kernel_clone
  - kernel/sysctl.c:proc_do_cad_pid
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__ia32_sys_getsid
  - kernel/sys.c:__x64_sys_getsid
  - kernel/sys.c:__do_sys_getpgrp
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - fs/fcntl.c:f_getown_ex
  - fs/fcntl.c:f_getown
  - fs/notify/fanotify/fanotify_user.c:copy_event_to_user
  - ipc/msg.c:msgctl_stat
  - ipc/msg.c:msgctl_stat
  - ipc/sem.c:semctl_main
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shmctl_stat
  - ipc/mqueue.c:mqueue_read_file
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - net/core/sock.c:sock_getsockopt
  - net/core/scm.c:__scm_send
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
**Symbols:**

```
ffffffff810c7e60-ffffffff810c7eb5: pid_vnr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
pid_t pid_vnr(struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810c9900)
Location: kernel/pid.c:486
Inline: False
Direct callers:
  - kernel/fork.c:kernel_clone
  - kernel/sysctl.c:proc_do_cad_pid
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__ia32_sys_getsid
  - kernel/sys.c:__x64_sys_getsid
  - kernel/sys.c:__do_sys_getpgrp
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_getown
  - fs/notify/fanotify/fanotify_user.c:copy_event_to_user
  - ipc/msg.c:msgctl_stat
  - ipc/msg.c:msgctl_stat
  - ipc/sem.c:semctl_main
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shmctl_stat
  - ipc/mqueue.c:mqueue_read_file
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - net/core/sock.c:sock_getsockopt
  - net/core/scm.c:__scm_send
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
**Symbols:**

```
ffffffff810c9900-ffffffff810c9955: pid_vnr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
pid_t pid_vnr(struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810dc860)
Location: kernel/pid.c:486
Inline: False
Direct callers:
  - kernel/fork.c:kernel_clone
  - kernel/sysctl.c:proc_do_cad_pid
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__ia32_sys_getsid
  - kernel/sys.c:__x64_sys_getsid
  - kernel/sys.c:__do_sys_getpgrp
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_getown
  - fs/notify/fanotify/fanotify_user.c:copy_event_to_user
  - ipc/msg.c:msgctl_stat
  - ipc/msg.c:msgctl_stat
  - ipc/sem.c:semctl_main
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shmctl_stat
  - ipc/mqueue.c:mqueue_read_file
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - net/core/sock.c:sock_getsockopt
  - net/core/scm.c:__scm_send
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:__unix_dgram_recvmsg
```
**Symbols:**

```
ffffffff810dc860-ffffffff810dc8b5: pid_vnr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
pid_t pid_vnr(struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810f6010)
Location: kernel/pid.c:486
Inline: False
Direct callers:
  - kernel/fork.c:kernel_clone
  - kernel/sysctl.c:proc_do_cad_pid
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__ia32_sys_getsid
  - kernel/sys.c:__x64_sys_getsid
  - kernel/sys.c:__do_sys_getpgrp
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_getown
  - fs/notify/fanotify/fanotify_user.c:copy_event_to_user
  - ipc/msg.c:msgctl_stat
  - ipc/msg.c:msgctl_stat
  - ipc/sem.c:semctl_main
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shmctl_stat
  - ipc/mqueue.c:mqueue_read_file
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - net/core/sock.c:sock_getsockopt
  - net/core/scm.c:__scm_send
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:__unix_dgram_recvmsg
```
**Symbols:**

```
ffffffff810f6010-ffffffff810f6075: pid_vnr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
pid_t pid_vnr(struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff81118580)
Location: kernel/pid.c:486
Inline: False
Direct callers:
  - kernel/fork.c:kernel_clone
  - kernel/sysctl.c:proc_do_cad_pid
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__ia32_sys_getsid
  - kernel/sys.c:__x64_sys_getsid
  - kernel/sys.c:__do_sys_getpgrp
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_getown
  - fs/notify/fanotify/fanotify_user.c:copy_event_to_user
  - ipc/msg.c:msgctl_stat
  - ipc/msg.c:msgctl_stat
  - ipc/sem.c:semctl_main
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shmctl_stat
  - ipc/mqueue.c:mqueue_read_file
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - net/core/sock.c:sk_getsockopt
  - net/core/scm.c:__scm_send
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:__unix_dgram_recvmsg
```
**Symbols:**

```
ffffffff81118580-ffffffff811185e5: pid_vnr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
pid_t pid_vnr(struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff811257c0)
Location: kernel/pid.c:489
Inline: False
Direct callers:
  - kernel/fork.c:kernel_clone
  - kernel/sysctl.c:proc_do_cad_pid
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__ia32_sys_getsid
  - kernel/sys.c:__x64_sys_getsid
  - kernel/sys.c:__do_sys_getpgrp
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_getown
  - fs/notify/fanotify/fanotify_user.c:copy_event_to_user
  - ipc/msg.c:msgctl_stat
  - ipc/msg.c:msgctl_stat
  - ipc/sem.c:semctl_main
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shmctl_stat
  - ipc/mqueue.c:mqueue_read_file
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - net/core/sock.c:sk_getsockopt
  - net/core/scm.c:__scm_send
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:__unix_dgram_recvmsg
```
**Symbols:**

```
ffffffff811257c0-ffffffff81125825: pid_vnr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
pid_t pid_vnr(struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff8112fdc0)
Location: kernel/pid.c:489
Inline: False
Direct callers:
  - kernel/fork.c:kernel_clone
  - kernel/sysctl.c:proc_do_cad_pid
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__ia32_sys_getsid
  - kernel/sys.c:__x64_sys_getsid
  - kernel/sys.c:__do_sys_getpgrp
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_getown
  - fs/notify/fanotify/fanotify_user.c:copy_event_to_user
  - ipc/msg.c:msgctl_stat
  - ipc/msg.c:msgctl_stat
  - ipc/sem.c:semctl_main
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shmctl_stat
  - ipc/mqueue.c:mqueue_read_file
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/gpu/drm/drm_debugfs.c:drm_clients_info
  - net/core/sock.c:sk_getsockopt
  - net/core/scm.c:__scm_send
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:__unix_dgram_recvmsg
```
**Symbols:**

```
ffffffff8112fdc0-ffffffff8112fe25: pid_vnr (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
pid_t pid_vnr(struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffff800010123f70)
Location: kernel/pid.c:419
Inline: False
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
  - kernel/sysctl.c:proc_do_cad_pid
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__arm64_sys_getsid
  - kernel/sys.c:__arm64_sys_getpgrp
  - kernel/sys.c:__arm64_sys_getpgid
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:auditd_pid_vnr
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_getown
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - ipc/msg.c:msgctl_stat
  - ipc/msg.c:msgctl_stat
  - ipc/sem.c:semctl_main
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shmctl_stat
  - ipc/mqueue.c:mqueue_read_file
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - net/core/sock.c:sock_getsockopt
  - net/core/scm.c:__scm_send
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
**Symbols:**

```
ffff800010123f70-ffff800010123fe8: pid_vnr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
pid_t pid_vnr(struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (c03772d4)
Location: kernel/pid.c:419
Inline: False
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/sysctl.c:proc_do_cad_pid
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__se_sys_getsid
  - kernel/sys.c:do_getpgid
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:auditd_pid_vnr
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_getown
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - ipc/msg.c:ksys_msgctl
  - ipc/msg.c:ksys_msgctl
  - ipc/sem.c:semctl_main
  - ipc/shm.c:ksys_shmctl
  - ipc/shm.c:ksys_shmctl
  - ipc/mqueue.c:mqueue_read_file
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - sound/core/control.c:snd_ctl_elem_info_user
  - sound/core/pcm.c:snd_pcm_substream_proc_status_read
  - net/core/sock.c:sock_getsockopt
  - net/core/scm.c:__scm_send
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
**Symbols:**

```
c03772d4-c0377344: pid_vnr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
pid_t pid_vnr(struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (c00000000016dc10)
Location: kernel/pid.c:419
Inline: False
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/sysctl.c:proc_do_cad_pid
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__se_sys_getsid
  - kernel/sys.c:sys_getpgrp
  - kernel/sys.c:__se_sys_getpgid
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:auditd_pid_vnr
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_getown
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - ipc/msg.c:msgctl_stat
  - ipc/msg.c:msgctl_stat
  - ipc/sem.c:semctl_main
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shmctl_stat
  - ipc/mqueue.c:mqueue_read_file
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - net/core/sock.c:sock_getsockopt
  - net/core/scm.c:__scm_send
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
**Symbols:**

```
c00000000016dc10-c00000000016dc78: pid_vnr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
pid_t pid_vnr(struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffe0000dc252)
Location: kernel/pid.c:419
Inline: False
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/sysctl.c:proc_do_cad_pid
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__se_sys_getsid
  - kernel/sys.c:__se_sys_getpgid
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:auditd_pid_vnr
  - fs/fcntl.c:__se_sys_fcntl
  - fs/fcntl.c:f_getown
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - ipc/sem.c:semctl_main
  - ipc/mqueue.c:mqueue_read_file
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - net/core/sock.c:sock_getsockopt
  - net/core/scm.c:__scm_send
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
**Symbols:**

```
ffffffe0000dc252-ffffffe0000dc2a8: pid_vnr (STB_GLOBAL)
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
pid_t pid_vnr(struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810bfda0)
Location: kernel/pid.c:419
Inline: False
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/sysctl.c:proc_do_cad_pid
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__ia32_sys_getsid
  - kernel/sys.c:__x64_sys_getsid
  - kernel/sys.c:do_getpgid
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:auditd_pid_vnr
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_getown
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - ipc/msg.c:msgctl_stat
  - ipc/msg.c:msgctl_stat
  - ipc/sem.c:semctl_main
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shmctl_stat
  - ipc/mqueue.c:mqueue_read_file
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - net/core/sock.c:sock_getsockopt
  - net/core/scm.c:__scm_send
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
**Symbols:**

```
ffffffff810bfda0-ffffffff810bfdf5: pid_vnr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
pid_t pid_vnr(struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810ae5b0)
Location: kernel/pid.c:419
Inline: False
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/sysctl.c:proc_do_cad_pid
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__ia32_sys_getsid
  - kernel/sys.c:__x64_sys_getsid
  - kernel/sys.c:do_getpgid
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:auditd_pid_vnr
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_getown
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - ipc/msg.c:msgctl_stat
  - ipc/msg.c:msgctl_stat
  - ipc/sem.c:semctl_main
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shmctl_stat
  - ipc/mqueue.c:mqueue_read_file
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - net/core/sock.c:sock_getsockopt
  - net/core/scm.c:__scm_send
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
**Symbols:**

```
ffffffff810ae5b0-ffffffff810ae605: pid_vnr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
pid_t pid_vnr(struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810bf2f0)
Location: kernel/pid.c:419
Inline: False
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/sysctl.c:proc_do_cad_pid
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__ia32_sys_getsid
  - kernel/sys.c:__x64_sys_getsid
  - kernel/sys.c:do_getpgid
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:auditd_pid_vnr
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_getown
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - ipc/msg.c:msgctl_stat
  - ipc/msg.c:msgctl_stat
  - ipc/sem.c:semctl_main
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shmctl_stat
  - ipc/mqueue.c:mqueue_read_file
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - net/core/sock.c:sock_getsockopt
  - net/core/scm.c:__scm_send
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
**Symbols:**

```
ffffffff810bf2f0-ffffffff810bf345: pid_vnr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
pid_t pid_vnr(struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810c7620)
Location: kernel/pid.c:419
Inline: False
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/sysctl.c:proc_do_cad_pid
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__ia32_sys_getsid
  - kernel/sys.c:__x64_sys_getsid
  - kernel/sys.c:do_getpgid
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:auditd_pid_vnr
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_getown
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - ipc/msg.c:msgctl_stat
  - ipc/msg.c:msgctl_stat
  - ipc/sem.c:semctl_main
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shmctl_stat
  - ipc/mqueue.c:mqueue_read_file
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - net/core/sock.c:sock_getsockopt
  - net/core/scm.c:__scm_send
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
**Symbols:**

```
ffffffff810c7620-ffffffff810c7675: pid_vnr (STB_GLOBAL)
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
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
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
