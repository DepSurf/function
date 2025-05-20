# Function: <code>put_pid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void put_pid(struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff8109de00)
Location: kernel/pid.c:237
Inline: False
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/exit.c:SyS_waitid
  - kernel/exit.c:SyS_waitpid
  - kernel/sysctl.c:proc_do_cad_pid
  - kernel/pid.c:delayed_put_pid
  - kernel/time/posix-timers.c:release_posix_timer
  - kernel/trace/ftrace.c:ftrace_pid_write
  - kernel/trace/ftrace.c:ftrace_pid_write
  - fs/file_table.c:__fput
  - fs/fcntl.c:f_modown
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/proc/inode.c:proc_evict_inode
  - fs/proc/array.c:children_seq_stop
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:children_seq_next
  - ipc/mqueue.c:__do_notify
  - ipc/mqueue.c:remove_notification
  - drivers/tty/tty_io.c:tty_do_resize
  - drivers/tty/tty_io.c:__proc_set_tty
  - drivers/tty/tty_io.c:__proc_set_tty
  - drivers/tty/tty_io.c:__proc_set_tty
  - drivers/tty/tty_io.c:__proc_set_tty
  - drivers/tty/tty_io.c:__proc_set_tty
  - drivers/tty/tty_io.c:release_one_tty
  - drivers/tty/tty_io.c:release_one_tty
  - drivers/tty/tty_io.c:__tty_fasync
  - drivers/tty/tty_io.c:__tty_hangup
  - drivers/tty/tty_io.c:__tty_hangup
  - drivers/tty/tty_io.c:__tty_hangup
  - drivers/tty/tty_io.c:__tty_hangup
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/n_tty.c:__isig
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/vt/vt_ioctl.c:reset_vc
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/keyboard.c:fn_spawn_con
  - drivers/tty/vt/vt.c:vc_deallocate
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
  - drivers/usb/core/devio.c:usbdev_release
  - net/core/sock.c:sk_destruct
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/unix/af_unix.c:init_peercred
  - net/unix/af_unix.c:unix_listen
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_destruct_scm
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/ipv6/ip6_flowlabel.c:fl_free
```
**Symbols:**

```
ffffffff8109de00-ffffffff8109de46: put_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void put_pid(struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810a1460)
Location: kernel/pid.c:237
Inline: False
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/exit.c:SyS_waitpid
  - kernel/exit.c:SyS_waitid
  - kernel/sysctl.c:proc_do_cad_pid
  - kernel/pid.c:delayed_put_pid
  - kernel/time/posix-timers.c:release_posix_timer
  - fs/file_table.c:__fput
  - fs/fcntl.c:f_modown
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/proc/inode.c:proc_evict_inode
  - fs/proc/array.c:children_seq_stop
  - fs/proc/array.c:children_seq_next
  - fs/proc/array.c:do_task_stat
  - ipc/mqueue.c:remove_notification
  - ipc/mqueue.c:__do_notify
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_do_resize
  - drivers/tty/tty_io.c:__tty_fasync
  - drivers/tty/tty_io.c:release_one_tty
  - drivers/tty/tty_io.c:release_one_tty
  - drivers/tty/tty_io.c:__tty_hangup
  - drivers/tty/tty_io.c:__tty_hangup
  - drivers/tty/tty_io.c:__tty_hangup
  - drivers/tty/tty_io.c:__tty_hangup
  - drivers/tty/tty_io.c:__proc_set_tty
  - drivers/tty/tty_io.c:__proc_set_tty
  - drivers/tty/tty_io.c:__proc_set_tty
  - drivers/tty/n_tty.c:__isig
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/vt/vt_ioctl.c:reset_vc
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/keyboard.c:fn_spawn_con
  - drivers/tty/vt/vt.c:vc_deallocate
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
  - net/core/sock.c:__sk_destruct
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_destruct_scm
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_listen
  - net/unix/af_unix.c:init_peercred
  - net/ipv6/ip6_flowlabel.c:fl_free
```
**Symbols:**

```
ffffffff810a1460-ffffffff810a14a2: put_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void put_pid(struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810a6520)
Location: kernel/pid.c:237
Inline: False
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/exit.c:SyS_waitpid
  - kernel/exit.c:SyS_waitid
  - kernel/sysctl.c:proc_do_cad_pid
  - kernel/pid.c:delayed_put_pid
  - kernel/time/posix-timers.c:release_posix_timer
  - fs/file_table.c:__fput
  - fs/fcntl.c:f_modown
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/proc/inode.c:proc_evict_inode
  - fs/proc/array.c:children_seq_stop
  - fs/proc/array.c:children_seq_next
  - fs/proc/array.c:do_task_stat
  - ipc/mqueue.c:remove_notification
  - ipc/mqueue.c:__do_notify
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_do_resize
  - drivers/tty/tty_io.c:__tty_fasync
  - drivers/tty/tty_io.c:release_one_tty
  - drivers/tty/tty_io.c:release_one_tty
  - drivers/tty/tty_io.c:__tty_hangup
  - drivers/tty/tty_io.c:__tty_hangup
  - drivers/tty/tty_io.c:__tty_hangup
  - drivers/tty/tty_io.c:__tty_hangup
  - drivers/tty/tty_io.c:__proc_set_tty
  - drivers/tty/tty_io.c:__proc_set_tty
  - drivers/tty/tty_io.c:__proc_set_tty
  - drivers/tty/n_tty.c:__isig
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/vt/vt_ioctl.c:reset_vc
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/keyboard.c:fn_spawn_con
  - drivers/tty/vt/vt.c:vc_deallocate
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
  - net/core/sock.c:__sk_destruct
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_destruct_scm
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_listen
  - net/unix/af_unix.c:init_peercred
  - net/ipv6/ip6_flowlabel.c:fl_free
```
**Symbols:**

```
ffffffff810a6520-ffffffff810a6562: put_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void put_pid(struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810a34b0)
Location: kernel/pid.c:236
Inline: False
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:kernel_waitid
  - kernel/sysctl.c:proc_do_cad_pid
  - kernel/pid.c:delayed_put_pid
  - kernel/time/posix-timers.c:release_posix_timer
  - kernel/audit.c:auditd_conn_free
  - fs/file_table.c:__fput
  - fs/fcntl.c:f_modown
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/proc/inode.c:proc_evict_inode
  - fs/proc/array.c:children_seq_stop
  - fs/proc/array.c:children_seq_next
  - fs/proc/array.c:do_task_stat
  - ipc/mqueue.c:remove_notification
  - ipc/mqueue.c:__do_notify
  - drivers/tty/tty_io.c:tty_do_resize
  - drivers/tty/tty_io.c:__tty_fasync
  - drivers/tty/tty_io.c:release_one_tty
  - drivers/tty/tty_io.c:release_one_tty
  - drivers/tty/n_tty.c:__isig
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/vt/vt_ioctl.c:reset_vc
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/keyboard.c:fn_spawn_con
  - drivers/tty/vt/vt.c:vc_deallocate
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
  - net/core/sock.c:__sk_destruct
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_destruct_scm
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_listen
  - net/unix/af_unix.c:init_peercred
  - net/ipv6/ip6_flowlabel.c:fl_free
```
**Symbols:**

```
ffffffff810a34b0-ffffffff810a34f3: put_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void put_pid(struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810a9c30)
Location: kernel/pid.c:89
Inline: False
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:kernel_waitid
  - kernel/sysctl.c:proc_do_cad_pid
  - kernel/pid.c:delayed_put_pid
  - kernel/time/posix-timers.c:release_posix_timer
  - kernel/audit.c:auditd_conn_free
  - fs/file_table.c:__fput
  - fs/fcntl.c:f_delown
  - fs/proc/inode.c:proc_evict_inode
  - fs/proc/array.c:children_seq_stop
  - fs/proc/array.c:children_seq_next
  - fs/proc/array.c:do_task_stat
  - ipc/mqueue.c:remove_notification
  - ipc/mqueue.c:__do_notify
  - drivers/tty/tty_io.c:tty_do_resize
  - drivers/tty/tty_io.c:__tty_fasync
  - drivers/tty/tty_io.c:release_one_tty
  - drivers/tty/tty_io.c:release_one_tty
  - drivers/tty/n_tty.c:__isig
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/vt/vt_ioctl.c:reset_vc
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/keyboard.c:fn_spawn_con
  - drivers/tty/vt/vt.c:vc_deallocate
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
  - net/core/sock.c:__sk_destruct
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_destruct_scm
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_listen
  - net/unix/af_unix.c:init_peercred
  - net/ipv6/ip6_flowlabel.c:fl_free
```
**Symbols:**

```
ffffffff810a9c30-ffffffff810a9c74: put_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void put_pid(struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810b0930)
Location: kernel/pid.c:101
Inline: False
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:kernel_waitid
  - kernel/sysctl.c:proc_do_cad_pid
  - kernel/pid.c:delayed_put_pid
  - kernel/time/posix-timers.c:release_posix_timer
  - kernel/audit.c:auditd_conn_free
  - fs/file_table.c:__fput
  - fs/fcntl.c:f_modown
  - fs/proc/inode.c:proc_evict_inode
  - fs/proc/array.c:children_seq_stop
  - fs/proc/array.c:children_seq_next
  - fs/proc/array.c:do_task_stat
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:freeque
  - ipc/msg.c:freeque
  - ipc/sem.c:exit_sem
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:freeary
  - ipc/sem.c:perform_atomic_semop
  - ipc/sem.c:perform_atomic_semop
  - ipc/shm.c:newseg
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
  - ipc/shm.c:shm_destroy
  - ipc/shm.c:shm_destroy
  - ipc/mqueue.c:remove_notification
  - ipc/mqueue.c:__do_notify
  - drivers/tty/tty_io.c:tty_do_resize
  - drivers/tty/tty_io.c:__tty_fasync
  - drivers/tty/tty_io.c:release_one_tty
  - drivers/tty/tty_io.c:release_one_tty
  - drivers/tty/n_tty.c:__isig
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/vt/vt_ioctl.c:reset_vc
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/keyboard.c:fn_spawn_con
  - drivers/tty/vt/vt.c:vc_deallocate
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
  - net/core/sock.c:__sk_destruct
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_destruct_scm
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_listen
  - net/unix/af_unix.c:init_peercred
  - net/ipv6/ip6_flowlabel.c:fl_free
  - net/xdp/xdp_umem.c:xdp_umem_create
  - net/xdp/xdp_umem.c:xdp_umem_create
  - net/xdp/xdp_umem.c:xdp_umem_create
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
```
**Symbols:**

```
ffffffff810b0930-ffffffff810b0973: put_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void put_pid(struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810b9a10)
Location: kernel/pid.c:101
Inline: False
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:kernel_waitid
  - kernel/sysctl.c:proc_do_cad_pid
  - kernel/pid.c:delayed_put_pid
  - kernel/time/posix-timers.c:release_posix_timer
  - kernel/audit.c:auditd_conn_free
  - fs/file_table.c:__fput
  - fs/fcntl.c:f_modown
  - fs/proc/inode.c:proc_evict_inode
  - fs/proc/array.c:children_seq_stop
  - fs/proc/array.c:children_seq_next
  - fs/proc/array.c:do_task_stat
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:freeque
  - ipc/msg.c:freeque
  - ipc/sem.c:exit_sem
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:freeary
  - ipc/sem.c:perform_atomic_semop
  - ipc/sem.c:perform_atomic_semop
  - ipc/shm.c:newseg
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
  - ipc/shm.c:shm_destroy
  - ipc/shm.c:shm_destroy
  - ipc/mqueue.c:remove_notification
  - ipc/mqueue.c:__do_notify
  - drivers/tty/tty_io.c:tty_do_resize
  - drivers/tty/tty_io.c:__tty_fasync
  - drivers/tty/tty_io.c:release_one_tty
  - drivers/tty/tty_io.c:release_one_tty
  - drivers/tty/n_tty.c:__isig
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/vt/vt_ioctl.c:reset_vc
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/keyboard.c:fn_spawn_con
  - drivers/tty/vt/vt.c:vc_deallocate
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
  - net/core/sock.c:__sk_destruct
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_destruct_scm
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_listen
  - net/unix/af_unix.c:init_peercred
  - net/ipv6/ip6_flowlabel.c:fl_free
  - net/xdp/xdp_umem.c:xdp_umem_create
  - net/xdp/xdp_umem.c:xdp_umem_create
  - net/xdp/xdp_umem.c:xdp_umem_create
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
```
**Symbols:**

```
ffffffff810b9a10-ffffffff810b9a53: put_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void put_pid(struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810bf6e0)
Location: kernel/pid.c:103
Inline: False
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/fork.c:pidfd_release
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:kernel_waitid
  - kernel/sysctl.c:proc_do_cad_pid
  - kernel/pid.c:__ia32_sys_pidfd_open
  - kernel/pid.c:__x64_sys_pidfd_open
  - kernel/pid.c:pidfd_create
  - kernel/pid.c:delayed_put_pid
  - kernel/time/posix-timers.c:release_posix_timer
  - kernel/audit.c:auditd_conn_free
  - fs/file_table.c:__fput
  - fs/fcntl.c:f_modown
  - fs/proc/inode.c:proc_evict_inode
  - fs/proc/array.c:children_seq_stop
  - fs/proc/array.c:children_seq_next
  - fs/proc/array.c:do_task_stat
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:freeque
  - ipc/msg.c:freeque
  - ipc/sem.c:exit_sem
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:freeary
  - ipc/sem.c:perform_atomic_semop
  - ipc/sem.c:perform_atomic_semop
  - ipc/shm.c:newseg
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
  - ipc/shm.c:shm_destroy
  - ipc/shm.c:shm_destroy
  - ipc/mqueue.c:remove_notification
  - ipc/mqueue.c:__do_notify
  - drivers/tty/tty_io.c:tty_do_resize
  - drivers/tty/tty_io.c:__tty_fasync
  - drivers/tty/tty_io.c:release_one_tty
  - drivers/tty/tty_io.c:release_one_tty
  - drivers/tty/n_tty.c:__isig
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/vt/vt_ioctl.c:reset_vc
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/keyboard.c:fn_spawn_con
  - drivers/tty/vt/vt.c:vc_deallocate
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
  - net/core/sock.c:__sk_destruct
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_listen
  - net/unix/af_unix.c:init_peercred
  - net/unix/scm.c:unix_destruct_scm
  - net/ipv6/ip6_flowlabel.c:fl_free_rcu
```
**Symbols:**

```
ffffffff810bf6e0-ffffffff810bf721: put_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void put_pid(struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810c5ab0)
Location: kernel/pid.c:103
Inline: False
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/fork.c:pidfd_release
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:kernel_waitid
  - kernel/sysctl.c:proc_do_cad_pid
  - kernel/pid.c:__ia32_sys_pidfd_open
  - kernel/pid.c:__x64_sys_pidfd_open
  - kernel/pid.c:pidfd_create
  - kernel/pid.c:delayed_put_pid
  - kernel/time/posix-timers.c:release_posix_timer
  - kernel/audit.c:auditd_conn_free
  - fs/file_table.c:__fput
  - fs/fcntl.c:f_modown
  - fs/proc/inode.c:proc_evict_inode
  - fs/proc/array.c:children_seq_stop
  - fs/proc/array.c:children_seq_next
  - fs/proc/array.c:do_task_stat
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:freeque
  - ipc/msg.c:freeque
  - ipc/sem.c:exit_sem
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:freeary
  - ipc/sem.c:perform_atomic_semop
  - ipc/sem.c:perform_atomic_semop
  - ipc/shm.c:newseg
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
  - ipc/shm.c:shm_destroy
  - ipc/shm.c:shm_destroy
  - ipc/mqueue.c:remove_notification
  - ipc/mqueue.c:__do_notify
  - drivers/tty/tty_io.c:tty_do_resize
  - drivers/tty/tty_io.c:__tty_fasync
  - drivers/tty/tty_io.c:release_one_tty
  - drivers/tty/tty_io.c:release_one_tty
  - drivers/tty/n_tty.c:__isig
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/vt/vt_ioctl.c:reset_vc
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/keyboard.c:fn_spawn_con
  - drivers/tty/vt/vt.c:vc_deallocate
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
  - net/core/sock.c:__sk_destruct
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_listen
  - net/unix/af_unix.c:init_peercred
  - net/unix/scm.c:unix_destruct_scm
  - net/ipv6/ip6_flowlabel.c:fl_free_rcu
```
**Symbols:**

```
ffffffff810c5ab0-ffffffff810c5af1: put_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void put_pid(struct pid *pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/pid.c (ffffffff810cd781)
Location: kernel/pid.c:104
Inline: True
Inline callers:
  - kernel/pid.c:__ia32_sys_pidfd_open
  - kernel/pid.c:__ia32_sys_pidfd_open
  - kernel/pid.c:__x64_sys_pidfd_open
  - kernel/pid.c:__x64_sys_pidfd_open
  - kernel/pid.c:delayed_put_pid
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/fork.c:pidfd_release
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:kernel_waitid
  - kernel/exit.c:release_task
  - kernel/sysctl.c:proc_do_cad_pid
  - kernel/pid.c:__ia32_sys_pidfd_open
  - kernel/pid.c:__ia32_sys_pidfd_open
  - kernel/pid.c:__x64_sys_pidfd_open
  - kernel/pid.c:__x64_sys_pidfd_open
  - kernel/pid.c:delayed_put_pid
  - kernel/time/posix-timers.c:release_posix_timer
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
  - kernel/audit.c:auditd_conn_free
  - fs/file_table.c:__fput
  - fs/fcntl.c:f_delown
  - fs/notify/fanotify/fanotify.c:fanotify_free_event
  - fs/proc/base.c:proc_pid_evict_inode
  - fs/proc/base.c:proc_pid_evict_inode
  - fs/proc/array.c:children_seq_stop
  - fs/proc/array.c:children_seq_next
  - fs/proc/array.c:do_task_stat
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:freeque
  - ipc/msg.c:freeque
  - ipc/sem.c:exit_sem
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:freeary
  - ipc/sem.c:perform_atomic_semop
  - ipc/sem.c:perform_atomic_semop_slow
  - ipc/shm.c:newseg
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
  - ipc/shm.c:shm_destroy
  - ipc/shm.c:shm_destroy
  - ipc/mqueue.c:remove_notification
  - ipc/mqueue.c:__do_notify
  - drivers/tty/tty_io.c:tty_do_resize
  - drivers/tty/tty_io.c:tty_fasync
  - drivers/tty/tty_io.c:release_one_tty
  - drivers/tty/tty_io.c:release_one_tty
  - drivers/tty/n_tty.c:isig
  - drivers/tty/n_tty.c:isig
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tiocspgrp
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/pty.c:pty_signal
  - drivers/tty/vt/vt_ioctl.c:change_console
  - drivers/tty/vt/vt_ioctl.c:complete_change_console
  - drivers/tty/vt/vt_ioctl.c:vc_SAK
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/keyboard.c:fn_spawn_con
  - drivers/tty/vt/vt.c:vc_deallocate
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
  - net/core/sock.c:__sk_destruct
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_listen
  - net/unix/af_unix.c:copy_peercred
  - net/unix/af_unix.c:init_peercred
  - net/unix/scm.c:unix_destruct_scm
  - net/ipv6/ip6_flowlabel.c:fl_free_rcu
```
**Symbols:**

```
ffffffff810cd4c0-ffffffff810cd51d: put_pid.part.0 (STB_LOCAL)
ffffffff810cd520-ffffffff810cd536: put_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void put_pid(struct pid *pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/pid.c (ffffffff810c829c)
Location: kernel/pid.c:105
Inline: True
Inline callers:
  - kernel/pid.c:__ia32_sys_pidfd_open
  - kernel/pid.c:__x64_sys_pidfd_open
  - kernel/pid.c:pidfd_create
  - kernel/pid.c:delayed_put_pid
Direct callers:
  - kernel/fork.c:kernel_clone
  - kernel/fork.c:pidfd_release
  - kernel/exit.c:kernel_wait
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:kernel_waitid
  - kernel/exit.c:release_task
  - kernel/sysctl.c:proc_do_cad_pid
  - kernel/pid.c:__ia32_sys_pidfd_open
  - kernel/pid.c:__x64_sys_pidfd_open
  - kernel/pid.c:pidfd_create
  - kernel/pid.c:delayed_put_pid
  - kernel/usermode_driver.c:umd_cleanup
  - kernel/time/posix-timers.c:release_posix_timer
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
  - kernel/audit.c:auditd_conn_free
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_delete_elem
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_update_elem
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_lookup_elem
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_lookup_elem
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_lookup_elem
  - mm/madvise.c:__do_sys_process_madvise
  - fs/file_table.c:__fput
  - fs/fcntl.c:f_delown
  - fs/notify/fanotify/fanotify.c:fanotify_free_event
  - fs/proc/base.c:proc_pid_evict_inode
  - fs/proc/base.c:proc_pid_evict_inode
  - fs/proc/array.c:children_seq_stop
  - fs/proc/array.c:children_seq_next
  - fs/proc/array.c:do_task_stat
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:freeque
  - ipc/msg.c:freeque
  - ipc/sem.c:exit_sem
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:freeary
  - ipc/sem.c:perform_atomic_semop
  - ipc/sem.c:perform_atomic_semop_slow
  - ipc/shm.c:newseg
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
  - ipc/shm.c:shm_destroy
  - ipc/shm.c:shm_destroy
  - ipc/mqueue.c:remove_notification
  - ipc/mqueue.c:__do_notify
  - drivers/tty/tty_io.c:tty_do_resize
  - drivers/tty/tty_io.c:tty_fasync
  - drivers/tty/tty_io.c:release_one_tty
  - drivers/tty/tty_io.c:release_one_tty
  - drivers/tty/n_tty.c:isig
  - drivers/tty/n_tty.c:isig
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/pty.c:pty_signal
  - drivers/tty/vt/vt_ioctl.c:reset_vc
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_setactivate
  - drivers/tty/vt/vt_ioctl.c:vt_k_ioctl
  - drivers/tty/vt/keyboard.c:fn_spawn_con
  - drivers/tty/vt/vt.c:vc_deallocate
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
  - net/core/sock.c:__sk_destruct
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/ipv4/bpfilter/sockopt.c:bpfilter_mbox_request
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:copy_peercred
  - net/unix/af_unix.c:init_peercred
  - net/unix/scm.c:unix_destruct_scm
  - net/ipv6/ip6_flowlabel.c:fl_free_rcu
```
**Symbols:**

```
ffffffff810c7ff0-ffffffff810c804d: put_pid.part.0 (STB_LOCAL)
ffffffff810c8050-ffffffff810c8066: put_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void put_pid(struct pid *pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/pid.c (ffffffff810c9dc2)
Location: kernel/pid.c:105
Inline: True
Inline callers:
  - kernel/pid.c:__ia32_sys_pidfd_open
  - kernel/pid.c:__x64_sys_pidfd_open
  - kernel/pid.c:pidfd_create
  - kernel/pid.c:delayed_put_pid
Direct callers:
  - kernel/fork.c:kernel_clone
  - kernel/fork.c:pidfd_release
  - kernel/exit.c:kernel_wait
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:kernel_waitid
  - kernel/exit.c:release_task
  - kernel/sysctl.c:proc_do_cad_pid
  - kernel/pid.c:__ia32_sys_pidfd_open
  - kernel/pid.c:__x64_sys_pidfd_open
  - kernel/pid.c:pidfd_create
  - kernel/pid.c:delayed_put_pid
  - kernel/usermode_driver.c:umd_cleanup
  - kernel/time/posix-timers.c:release_posix_timer
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
  - kernel/audit.c:auditd_conn_free
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_delete_elem
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_update_elem
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_lookup_elem
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_lookup_elem
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_lookup_elem
  - mm/madvise.c:__do_sys_process_madvise
  - fs/file_table.c:__fput
  - fs/fcntl.c:f_delown
  - fs/notify/fanotify/fanotify.c:fanotify_free_event
  - fs/proc/base.c:proc_pid_evict_inode
  - fs/proc/base.c:proc_pid_evict_inode
  - fs/proc/array.c:children_seq_stop
  - fs/proc/array.c:children_seq_next
  - fs/proc/array.c:do_task_stat
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:freeque
  - ipc/msg.c:freeque
  - ipc/sem.c:exit_sem
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:freeary
  - ipc/sem.c:perform_atomic_semop
  - ipc/sem.c:perform_atomic_semop_slow
  - ipc/shm.c:newseg
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
  - ipc/shm.c:shm_destroy
  - ipc/shm.c:shm_destroy
  - ipc/mqueue.c:remove_notification
  - ipc/mqueue.c:__do_notify
  - drivers/tty/tty_io.c:tty_do_resize
  - drivers/tty/tty_io.c:tty_fasync
  - drivers/tty/tty_io.c:release_one_tty
  - drivers/tty/tty_io.c:release_one_tty
  - drivers/tty/n_tty.c:isig
  - drivers/tty/n_tty.c:isig
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/pty.c:pty_signal
  - drivers/tty/vt/vt_ioctl.c:change_console
  - drivers/tty/vt/vt_ioctl.c:complete_change_console
  - drivers/tty/vt/vt_ioctl.c:vc_SAK
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_k_ioctl
  - drivers/tty/vt/keyboard.c:fn_spawn_con
  - drivers/tty/vt/vt.c:vc_deallocate
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
  - net/core/sock.c:__sk_destruct
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/ipv4/bpfilter/sockopt.c:bpfilter_mbox_request
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
  - net/unix/scm.c:unix_destruct_scm
  - net/ipv6/ip6_flowlabel.c:fl_free_rcu
```
**Symbols:**

```
ffffffff810c9a90-ffffffff810c9aed: put_pid.part.0 (STB_LOCAL)
ffffffff810c9af0-ffffffff810c9b06: put_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void put_pid(struct pid *pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/pid.c (ffffffff810dda73)
Location: kernel/pid.c:105
Inline: True
Inline callers:
  - kernel/pid.c:__ia32_sys_pidfd_open
  - kernel/pid.c:__x64_sys_pidfd_open
  - kernel/pid.c:pidfd_create
  - kernel/pid.c:delayed_put_pid
Direct callers:
  - kernel/fork.c:kernel_clone
  - kernel/fork.c:pidfd_release
  - kernel/exit.c:kernel_wait
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:kernel_waitid
  - kernel/exit.c:release_task
  - kernel/sysctl.c:proc_do_cad_pid
  - kernel/pid.c:__ia32_sys_pidfd_open
  - kernel/pid.c:__x64_sys_pidfd_open
  - kernel/pid.c:pidfd_create
  - kernel/pid.c:delayed_put_pid
  - kernel/usermode_driver.c:umd_cleanup
  - kernel/time/posix-timers.c:release_posix_timer
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
  - kernel/audit.c:auditd_conn_free
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_delete_elem
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_update_elem
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_lookup_elem
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_lookup_elem
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_lookup_elem
  - mm/oom_kill.c:__do_sys_process_mrelease
  - mm/oom_kill.c:__do_sys_process_mrelease
  - mm/madvise.c:__do_sys_process_madvise
  - fs/file_table.c:__fput
  - fs/fcntl.c:f_delown
  - fs/notify/fanotify/fanotify.c:fanotify_free_event
  - fs/proc/base.c:proc_pid_evict_inode
  - fs/proc/base.c:proc_pid_evict_inode
  - fs/proc/array.c:children_seq_stop
  - fs/proc/array.c:children_seq_next
  - fs/proc/array.c:do_task_stat
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:freeque
  - ipc/msg.c:freeque
  - ipc/sem.c:exit_sem
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:freeary
  - ipc/sem.c:perform_atomic_semop
  - ipc/sem.c:perform_atomic_semop_slow
  - ipc/shm.c:newseg
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
  - ipc/shm.c:shm_destroy
  - ipc/shm.c:shm_destroy
  - ipc/mqueue.c:remove_notification
  - ipc/mqueue.c:__do_notify
  - drivers/tty/tty_io.c:tty_do_resize
  - drivers/tty/tty_io.c:tty_fasync
  - drivers/tty/tty_io.c:release_one_tty
  - drivers/tty/tty_io.c:release_one_tty
  - drivers/tty/n_tty.c:isig
  - drivers/tty/n_tty.c:isig
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/pty.c:pty_signal
  - drivers/tty/vt/vt_ioctl.c:change_console
  - drivers/tty/vt/vt_ioctl.c:complete_change_console
  - drivers/tty/vt/vt_ioctl.c:vc_SAK
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_k_ioctl
  - drivers/tty/vt/keyboard.c:fn_spawn_con
  - drivers/tty/vt/vt.c:vc_deallocate
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
  - net/core/sock.c:__sk_destruct
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/ipv4/bpfilter/sockopt.c:bpfilter_mbox_request
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:__unix_dgram_recvmsg
  - net/unix/af_unix.c:__unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
  - net/unix/scm.c:unix_destruct_scm
  - net/ipv6/ip6_flowlabel.c:fl_free_rcu
```
**Symbols:**

```
ffffffff810dca00-ffffffff810dca5d: put_pid.part.0 (STB_LOCAL)
ffffffff810dca60-ffffffff810dca76: put_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void put_pid(struct pid *pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/pid.c (ffffffff810f75aa)
Location: kernel/pid.c:105
Inline: True
Inline callers:
  - kernel/pid.c:__ia32_sys_pidfd_open
  - kernel/pid.c:__x64_sys_pidfd_open
  - kernel/pid.c:pidfd_create
  - kernel/pid.c:pidfd_get_task
  - kernel/pid.c:delayed_put_pid
Direct callers:
  - kernel/fork.c:kernel_clone
  - kernel/fork.c:pidfd_release
  - kernel/exit.c:kernel_wait
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:kernel_waitid
  - kernel/exit.c:kernel_waitid
  - kernel/exit.c:release_task
  - kernel/exit.c:release_task
  - kernel/sysctl.c:proc_do_cad_pid
  - kernel/pid.c:__ia32_sys_pidfd_open
  - kernel/pid.c:__x64_sys_pidfd_open
  - kernel/pid.c:pidfd_create
  - kernel/pid.c:pidfd_get_task
  - kernel/pid.c:pidfd_get_task
  - kernel/pid.c:pidfd_get_task
  - kernel/pid.c:delayed_put_pid
  - kernel/usermode_driver.c:umd_cleanup
  - kernel/time/posix-timers.c:release_posix_timer
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
  - kernel/audit.c:auditd_conn_free
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_delete_elem
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_update_elem
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_lookup_elem
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_lookup_elem
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_lookup_elem
  - fs/file_table.c:__fput
  - fs/fcntl.c:f_delown
  - fs/notify/fanotify/fanotify.c:fanotify_free_event
  - fs/proc/base.c:proc_pid_evict_inode
  - fs/proc/base.c:proc_pid_evict_inode
  - fs/proc/array.c:children_seq_stop
  - fs/proc/array.c:children_seq_next
  - fs/proc/array.c:do_task_stat
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:freeque
  - ipc/msg.c:freeque
  - ipc/sem.c:exit_sem
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:freeary
  - ipc/sem.c:perform_atomic_semop
  - ipc/sem.c:perform_atomic_semop_slow
  - ipc/shm.c:newseg
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
  - ipc/shm.c:shm_destroy
  - ipc/shm.c:shm_destroy
  - ipc/mqueue.c:remove_notification
  - ipc/mqueue.c:__do_notify
  - drivers/tty/tty_io.c:__do_SAK
  - drivers/tty/tty_io.c:tty_do_resize
  - drivers/tty/tty_io.c:tty_fasync
  - drivers/tty/tty_io.c:release_one_tty
  - drivers/tty/tty_io.c:release_one_tty
  - drivers/tty/n_tty.c:isig
  - drivers/tty/n_tty.c:isig
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/pty.c:pty_signal
  - drivers/tty/vt/vt_ioctl.c:change_console
  - drivers/tty/vt/vt_ioctl.c:complete_change_console
  - drivers/tty/vt/vt_ioctl.c:vc_SAK
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_k_ioctl
  - drivers/tty/vt/keyboard.c:fn_spawn_con
  - drivers/tty/vt/vt.c:vc_deallocate
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
  - net/core/sock.c:__sk_destruct
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/ipv4/bpfilter/sockopt.c:bpfilter_mbox_request
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
  - net/unix/scm.c:unix_destruct_scm
  - net/ipv6/ip6_flowlabel.c:fl_free_rcu
```
**Symbols:**

```
ffffffff810f61e0-ffffffff810f6256: put_pid.part.0 (STB_LOCAL)
ffffffff810f6260-ffffffff810f6282: put_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void put_pid(struct pid *pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/pid.c (ffffffff81119d2a)
Location: kernel/pid.c:105
Inline: True
Inline callers:
  - kernel/pid.c:__ia32_sys_pidfd_open
  - kernel/pid.c:__x64_sys_pidfd_open
  - kernel/pid.c:pidfd_create
  - kernel/pid.c:pidfd_get_task
  - kernel/pid.c:delayed_put_pid
Direct callers:
  - kernel/fork.c:kernel_clone
  - kernel/fork.c:pidfd_release
  - kernel/exit.c:kernel_wait
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:kernel_waitid
  - kernel/exit.c:kernel_waitid
  - kernel/exit.c:release_task
  - kernel/exit.c:release_task
  - kernel/sysctl.c:proc_do_cad_pid
  - kernel/pid.c:__ia32_sys_pidfd_open
  - kernel/pid.c:__x64_sys_pidfd_open
  - kernel/pid.c:pidfd_create
  - kernel/pid.c:pidfd_get_task
  - kernel/pid.c:pidfd_get_task
  - kernel/pid.c:pidfd_get_task
  - kernel/pid.c:delayed_put_pid
  - kernel/usermode_driver.c:umd_cleanup
  - kernel/time/posix-timers.c:release_posix_timer
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
  - kernel/audit.c:auditd_conn_free
  - kernel/bpf/task_iter.c:bpf_iter_attach_task
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_delete_elem
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_update_elem
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_lookup_elem
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_lookup_elem
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_lookup_elem
  - fs/file_table.c:__fput
  - fs/fcntl.c:f_delown
  - fs/notify/fanotify/fanotify.c:fanotify_free_event
  - fs/proc/base.c:proc_pid_evict_inode
  - fs/proc/base.c:proc_pid_evict_inode
  - fs/proc/array.c:children_seq_stop
  - fs/proc/array.c:children_seq_next
  - fs/proc/array.c:do_task_stat
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:freeque
  - ipc/msg.c:freeque
  - ipc/sem.c:exit_sem
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:freeary
  - ipc/sem.c:perform_atomic_semop
  - ipc/sem.c:perform_atomic_semop_slow
  - ipc/shm.c:newseg
  - ipc/shm.c:newseg
  - ipc/shm.c:__shm_close
  - ipc/shm.c:shm_destroy
  - ipc/shm.c:shm_destroy
  - ipc/shm.c:__shm_open
  - ipc/mqueue.c:remove_notification
  - ipc/mqueue.c:__do_notify
  - drivers/tty/tty_io.c:__do_SAK
  - drivers/tty/tty_io.c:tty_do_resize
  - drivers/tty/tty_io.c:__tty_fasync
  - drivers/tty/tty_io.c:release_one_tty
  - drivers/tty/tty_io.c:release_one_tty
  - drivers/tty/n_tty.c:isig
  - drivers/tty/n_tty.c:isig
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/pty.c:pty_signal
  - drivers/tty/vt/vt_ioctl.c:change_console
  - drivers/tty/vt/vt_ioctl.c:complete_change_console
  - drivers/tty/vt/vt_ioctl.c:vc_SAK
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_k_ioctl
  - drivers/tty/vt/keyboard.c:fn_spawn_con
  - drivers/tty/vt/vt.c:vc_deallocate
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
  - net/core/sock.c:__sk_destruct
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/ipv4/bpfilter/sockopt.c:bpfilter_mbox_request
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
  - net/unix/scm.c:unix_destruct_scm
  - net/ipv6/ip6_flowlabel.c:fl_free_rcu
```
**Symbols:**

```
ffffffff81118810-ffffffff81118886: put_pid.part.0 (STB_LOCAL)
ffffffff811188a0-ffffffff811188c2: put_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void put_pid(struct pid *pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/pid.c (ffffffff81125e53)
Location: kernel/pid.c:108
Inline: True
Inline callers:
  - kernel/pid.c:__ia32_sys_pidfd_open
  - kernel/pid.c:__x64_sys_pidfd_open
  - kernel/pid.c:pidfd_get_task
  - kernel/pid.c:delayed_put_pid
Direct callers:
  - kernel/fork.c:kernel_clone
  - kernel/fork.c:pidfd_release
  - kernel/exit.c:kernel_wait
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:kernel_waitid
  - kernel/exit.c:release_task
  - kernel/exit.c:release_task
  - kernel/sysctl.c:proc_do_cad_pid
  - kernel/pid.c:__ia32_sys_pidfd_open
  - kernel/pid.c:__x64_sys_pidfd_open
  - kernel/pid.c:pidfd_get_task
  - kernel/pid.c:pidfd_get_task
  - kernel/pid.c:pidfd_get_task
  - kernel/pid.c:delayed_put_pid
  - kernel/usermode_driver.c:umd_cleanup
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/posix-timers.c:posix_timer_unhash_and_free
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
  - kernel/audit.c:auditd_conn_free
  - kernel/bpf/task_iter.c:bpf_iter_attach_task
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_delete_elem
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_update_elem
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_lookup_elem
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_lookup_elem
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_lookup_elem
  - fs/file_table.c:__fput
  - fs/fcntl.c:f_delown
  - fs/notify/fanotify/fanotify.c:fanotify_free_event
  - fs/proc/base.c:proc_pid_evict_inode
  - fs/proc/base.c:proc_pid_evict_inode
  - fs/proc/array.c:children_seq_stop
  - fs/proc/array.c:children_seq_next
  - fs/proc/array.c:do_task_stat
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:freeque
  - ipc/msg.c:freeque
  - ipc/sem.c:exit_sem
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:freeary
  - ipc/sem.c:perform_atomic_semop
  - ipc/sem.c:perform_atomic_semop_slow
  - ipc/shm.c:newseg
  - ipc/shm.c:newseg
  - ipc/shm.c:__shm_close
  - ipc/shm.c:shm_destroy
  - ipc/shm.c:shm_destroy
  - ipc/shm.c:__shm_open
  - ipc/mqueue.c:remove_notification
  - ipc/mqueue.c:__do_notify
  - drivers/tty/tty_io.c:__do_SAK
  - drivers/tty/tty_io.c:tty_do_resize
  - drivers/tty/tty_io.c:__tty_fasync
  - drivers/tty/tty_io.c:release_one_tty
  - drivers/tty/tty_io.c:release_one_tty
  - drivers/tty/n_tty.c:isig
  - drivers/tty/n_tty.c:isig
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/pty.c:pty_signal
  - drivers/tty/vt/vt_ioctl.c:change_console
  - drivers/tty/vt/vt_ioctl.c:complete_change_console
  - drivers/tty/vt/vt_ioctl.c:vc_SAK
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_k_ioctl
  - drivers/tty/vt/keyboard.c:fn_spawn_con
  - drivers/tty/vt/vt.c:vc_deallocate
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:sk_getsockopt
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:__unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
  - net/unix/scm.c:unix_destruct_scm
  - net/ipv6/ip6_flowlabel.c:fl_free_rcu
```
**Symbols:**

```
ffffffff81125a50-ffffffff81125ac6: put_pid.part.0 (STB_LOCAL)
ffffffff81125ae0-ffffffff81125b02: put_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void put_pid(struct pid *pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/pid.c (ffffffff81130453)
Location: kernel/pid.c:108
Inline: True
Inline callers:
  - kernel/pid.c:__ia32_sys_pidfd_open
  - kernel/pid.c:__x64_sys_pidfd_open
  - kernel/pid.c:pidfd_get_task
  - kernel/pid.c:delayed_put_pid
Direct callers:
  - kernel/fork.c:kernel_clone
  - kernel/fork.c:pidfd_release
  - kernel/exit.c:kernel_wait
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:kernel_waitid
  - kernel/exit.c:release_task
  - kernel/exit.c:release_task
  - kernel/sysctl.c:proc_do_cad_pid
  - kernel/pid.c:__ia32_sys_pidfd_open
  - kernel/pid.c:__x64_sys_pidfd_open
  - kernel/pid.c:pidfd_get_task
  - kernel/pid.c:pidfd_get_task
  - kernel/pid.c:pidfd_get_task
  - kernel/pid.c:delayed_put_pid
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/posix-timers.c:posix_timer_unhash_and_free
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
  - kernel/audit.c:auditd_conn_free
  - kernel/bpf/task_iter.c:bpf_iter_attach_task
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_delete_elem
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_update_elem
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_lookup_elem
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_lookup_elem
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_lookup_elem
  - fs/file_table.c:__fput
  - fs/fcntl.c:f_delown
  - fs/notify/fanotify/fanotify.c:fanotify_free_event
  - fs/proc/inode.c:proc_free_inode
  - fs/proc/array.c:children_seq_stop
  - fs/proc/array.c:children_seq_next
  - fs/proc/array.c:do_task_stat
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:freeque
  - ipc/msg.c:freeque
  - ipc/sem.c:exit_sem
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:freeary
  - ipc/sem.c:perform_atomic_semop
  - ipc/sem.c:perform_atomic_semop
  - ipc/shm.c:newseg
  - ipc/shm.c:newseg
  - ipc/shm.c:__shm_close
  - ipc/shm.c:shm_destroy
  - ipc/shm.c:shm_destroy
  - ipc/shm.c:__shm_open
  - ipc/mqueue.c:remove_notification
  - ipc/mqueue.c:__do_notify
  - io_uring/waitid.c:io_waitid
  - io_uring/waitid.c:io_waitid
  - io_uring/waitid.c:io_waitid_complete
  - io_uring/waitid.c:io_waitid_complete
  - drivers/tty/tty_io.c:__do_SAK
  - drivers/tty/tty_io.c:tty_do_resize
  - drivers/tty/tty_io.c:__tty_fasync
  - drivers/tty/tty_io.c:release_one_tty
  - drivers/tty/tty_io.c:release_one_tty
  - drivers/tty/n_tty.c:isig
  - drivers/tty/n_tty.c:isig
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/pty.c:pty_signal
  - drivers/tty/vt/vt_ioctl.c:change_console
  - drivers/tty/vt/vt_ioctl.c:complete_change_console
  - drivers/tty/vt/vt_ioctl.c:vc_SAK
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_k_ioctl
  - drivers/tty/vt/keyboard.c:fn_spawn_con
  - drivers/tty/vt/vt.c:vc_deallocate
  - drivers/gpu/drm/drm_file.c:drm_file_update_pid
  - drivers/gpu/drm/drm_file.c:drm_file_free
  - drivers/gpu/drm/drm_file.c:drm_file_alloc
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:sk_getsockopt
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:__unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
  - net/unix/scm.c:unix_destruct_scm
  - net/ipv6/ip6_flowlabel.c:fl_free_rcu
```
**Symbols:**

```
ffffffff81130050-ffffffff811300c6: put_pid.part.0 (STB_LOCAL)
ffffffff811300e0-ffffffff81130102: put_pid (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void put_pid(struct pid *pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/pid.c (ffff8000101243b8)
Location: kernel/pid.c:103
Inline: True
Inline callers:
  - kernel/pid.c:__arm64_sys_pidfd_open
  - kernel/pid.c:__arm64_sys_pidfd_open
  - kernel/pid.c:delayed_put_pid
Direct callers:
  - virt/kvm/kvm_main.c:kvm_vcpu_ioctl
  - virt/kvm/kvm_main.c:kvm_vcpu_uninit
  - kernel/fork.c:_do_fork
  - kernel/fork.c:pidfd_release
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:kernel_waitid
  - kernel/sysctl.c:proc_do_cad_pid
  - kernel/pid.c:__arm64_sys_pidfd_open
  - kernel/pid.c:__arm64_sys_pidfd_open
  - kernel/pid.c:delayed_put_pid
  - kernel/time/posix-timers.c:release_posix_timer
  - kernel/audit.c:auditd_conn_free
  - fs/file_table.c:__fput
  - fs/fcntl.c:f_modown
  - fs/proc/inode.c:proc_evict_inode
  - fs/proc/array.c:children_seq_stop
  - fs/proc/array.c:children_seq_next
  - fs/proc/array.c:do_task_stat
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:freeque
  - ipc/msg.c:freeque
  - ipc/sem.c:exit_sem
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:freeary
  - ipc/sem.c:perform_atomic_semop
  - ipc/sem.c:perform_atomic_semop
  - ipc/shm.c:newseg
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
  - ipc/shm.c:shm_destroy
  - ipc/shm.c:shm_destroy
  - ipc/mqueue.c:remove_notification
  - ipc/mqueue.c:__do_notify
  - drivers/tty/tty_io.c:tty_do_resize
  - drivers/tty/tty_io.c:__tty_fasync
  - drivers/tty/tty_io.c:release_one_tty
  - drivers/tty/tty_io.c:release_one_tty
  - drivers/tty/n_tty.c:__isig
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/vt/vt_ioctl.c:reset_vc
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/keyboard.c:fn_spawn_con
  - drivers/tty/vt/vt.c:vc_deallocate
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
  - net/core/sock.c:__sk_destruct
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_listen
  - net/unix/af_unix.c:init_peercred
  - net/unix/scm.c:unix_destruct_scm
  - net/ipv6/ip6_flowlabel.c:fl_free_rcu
```
**Symbols:**

```
ffff800010124288-ffff8000101242e8: put_pid.part.0 (STB_LOCAL)
ffff8000101242e8-ffff800010124318: put_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
void put_pid(struct pid *pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/pid.c (c0377d64)
Location: kernel/pid.c:103
Inline: True
Inline callers:
  - kernel/pid.c:__se_sys_pidfd_open
  - kernel/pid.c:__se_sys_pidfd_open
  - kernel/pid.c:delayed_put_pid
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/fork.c:pidfd_release
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:kernel_waitid
  - kernel/sysctl.c:proc_do_cad_pid
  - kernel/pid.c:__se_sys_pidfd_open
  - kernel/pid.c:__se_sys_pidfd_open
  - kernel/pid.c:delayed_put_pid
  - kernel/time/posix-timers.c:release_posix_timer
  - kernel/audit.c:auditd_conn_free
  - fs/file_table.c:__fput
  - fs/fcntl.c:f_modown
  - fs/proc/inode.c:proc_evict_inode
  - fs/proc/array.c:children_seq_stop
  - fs/proc/array.c:children_seq_next
  - fs/proc/array.c:do_task_stat
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:freeque
  - ipc/msg.c:freeque
  - ipc/sem.c:exit_sem
  - ipc/sem.c:ksys_semctl
  - ipc/sem.c:semctl_main
  - ipc/sem.c:freeary
  - ipc/sem.c:perform_atomic_semop
  - ipc/sem.c:perform_atomic_semop
  - ipc/shm.c:newseg
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
  - ipc/shm.c:shm_destroy
  - ipc/shm.c:shm_destroy
  - ipc/shm.c:__shm_open
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:remove_notification
  - drivers/tty/tty_io.c:tty_do_resize
  - drivers/tty/tty_io.c:__tty_fasync
  - drivers/tty/tty_io.c:release_one_tty
  - drivers/tty/tty_io.c:release_one_tty
  - drivers/tty/n_tty.c:__isig
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/pty.c:pty_signal
  - drivers/tty/vt/vt_ioctl.c:reset_vc
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/keyboard.c:fn_spawn_con
  - drivers/tty/vt/vt.c:vc_deallocate
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
  - sound/core/control.c:snd_ctl_release
  - sound/core/pcm.c:snd_pcm_detach_substream
  - net/core/sock.c:__sk_destruct
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_listen
  - net/unix/af_unix.c:init_peercred
  - net/unix/scm.c:unix_destruct_scm
  - net/ipv6/ip6_flowlabel.c:fl_free_rcu
```
**Symbols:**

```
c0377554-c037759c: put_pid.part.0 (STB_LOCAL)
c037759c-c03775c0: put_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void put_pid(struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (c00000000016dcb0)
Location: kernel/pid.c:103
Inline: False
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/fork.c:pidfd_release
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:kernel_waitid
  - kernel/sysctl.c:proc_do_cad_pid
  - kernel/pid.c:__se_sys_pidfd_open
  - kernel/pid.c:__se_sys_pidfd_open
  - kernel/pid.c:delayed_put_pid
  - kernel/time/posix-timers.c:release_posix_timer
  - kernel/time/posix-timers.c:release_posix_timer
  - kernel/audit.c:auditd_conn_free
  - fs/file_table.c:__fput
  - fs/fcntl.c:f_modown
  - fs/proc/inode.c:proc_evict_inode
  - fs/proc/array.c:children_seq_stop
  - fs/proc/array.c:children_seq_next
  - fs/proc/array.c:do_task_stat
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:freeque
  - ipc/msg.c:freeque
  - ipc/sem.c:exit_sem
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:freeary
  - ipc/sem.c:perform_atomic_semop
  - ipc/sem.c:perform_atomic_semop
  - ipc/shm.c:newseg
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
  - ipc/shm.c:shm_destroy
  - ipc/shm.c:shm_destroy
  - ipc/mqueue.c:remove_notification
  - ipc/mqueue.c:__do_notify
  - drivers/tty/tty_io.c:tty_do_resize
  - drivers/tty/tty_io.c:__tty_fasync
  - drivers/tty/tty_io.c:release_one_tty
  - drivers/tty/tty_io.c:release_one_tty
  - drivers/tty/n_tty.c:__isig
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/pty.c:pty_signal
  - drivers/tty/vt/vt_ioctl.c:reset_vc
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/keyboard.c:fn_spawn_con
  - drivers/tty/vt/vt.c:vc_deallocate
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
  - net/core/sock.c:__sk_destruct
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_listen
  - net/unix/af_unix.c:init_peercred
  - net/unix/scm.c:unix_destruct_scm
  - net/ipv6/ip6_flowlabel.c:fl_free_rcu
```
**Symbols:**

```
c00000000016dcb0-c00000000016dd54: put_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void put_pid(struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffe0000dc2da)
Location: kernel/pid.c:103
Inline: False
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/fork.c:pidfd_release
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:kernel_waitid
  - kernel/sysctl.c:proc_do_cad_pid
  - kernel/pid.c:__se_sys_pidfd_open
  - kernel/pid.c:__se_sys_pidfd_open
  - kernel/pid.c:delayed_put_pid
  - kernel/time/posix-timers.c:release_posix_timer
  - kernel/audit.c:auditd_conn_free
  - fs/file_table.c:__fput
  - fs/fcntl.c:f_modown
  - fs/proc/inode.c:proc_evict_inode
  - fs/proc/array.c:children_seq_stop
  - fs/proc/array.c:children_seq_next
  - fs/proc/array.c:do_task_stat
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:freeque
  - ipc/msg.c:freeque
  - ipc/sem.c:exit_sem
  - ipc/sem.c:__se_sys_semctl
  - ipc/sem.c:semctl_main
  - ipc/sem.c:freeary
  - ipc/sem.c:perform_atomic_semop
  - ipc/sem.c:perform_atomic_semop
  - ipc/shm.c:newseg
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
  - ipc/shm.c:shm_destroy
  - ipc/shm.c:shm_destroy
  - ipc/mqueue.c:remove_notification
  - ipc/mqueue.c:__do_notify
  - drivers/tty/tty_io.c:tty_do_resize
  - drivers/tty/tty_io.c:__tty_fasync
  - drivers/tty/tty_io.c:release_one_tty
  - drivers/tty/tty_io.c:release_one_tty
  - drivers/tty/n_tty.c:__isig
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/pty.c:pty_signal
  - drivers/tty/vt/vt_ioctl.c:reset_vc
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/keyboard.c:fn_spawn_con
  - drivers/tty/vt/vt.c:vc_deallocate
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
  - net/core/sock.c:__sk_destruct
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_listen
  - net/unix/af_unix.c:init_peercred
  - net/unix/scm.c:unix_destruct_scm
  - net/ipv6/ip6_flowlabel.c:fl_free_rcu
```
**Symbols:**

```
ffffffe0000dc2da-ffffffe0000dc340: put_pid (STB_GLOBAL)
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
void put_pid(struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810bfe30)
Location: kernel/pid.c:103
Inline: False
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/fork.c:pidfd_release
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:kernel_waitid
  - kernel/sysctl.c:proc_do_cad_pid
  - kernel/pid.c:__ia32_sys_pidfd_open
  - kernel/pid.c:__x64_sys_pidfd_open
  - kernel/pid.c:pidfd_create
  - kernel/pid.c:delayed_put_pid
  - kernel/time/posix-timers.c:release_posix_timer
  - kernel/audit.c:auditd_conn_free
  - fs/file_table.c:__fput
  - fs/fcntl.c:f_modown
  - fs/proc/inode.c:proc_evict_inode
  - fs/proc/array.c:children_seq_stop
  - fs/proc/array.c:children_seq_next
  - fs/proc/array.c:do_task_stat
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:freeque
  - ipc/msg.c:freeque
  - ipc/sem.c:exit_sem
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:freeary
  - ipc/sem.c:perform_atomic_semop
  - ipc/sem.c:perform_atomic_semop
  - ipc/shm.c:newseg
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
  - ipc/shm.c:shm_destroy
  - ipc/shm.c:shm_destroy
  - ipc/mqueue.c:remove_notification
  - ipc/mqueue.c:__do_notify
  - drivers/tty/tty_io.c:tty_do_resize
  - drivers/tty/tty_io.c:__tty_fasync
  - drivers/tty/tty_io.c:release_one_tty
  - drivers/tty/tty_io.c:release_one_tty
  - drivers/tty/n_tty.c:__isig
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/vt/vt_ioctl.c:reset_vc
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/keyboard.c:fn_spawn_con
  - drivers/tty/vt/vt.c:vc_deallocate
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
  - net/core/sock.c:__sk_destruct
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_listen
  - net/unix/af_unix.c:init_peercred
  - net/unix/scm.c:unix_destruct_scm
  - net/ipv6/ip6_flowlabel.c:fl_free_rcu
```
**Symbols:**

```
ffffffff810bfe30-ffffffff810bfe71: put_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void put_pid(struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810ae640)
Location: kernel/pid.c:103
Inline: False
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/fork.c:pidfd_release
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:kernel_waitid
  - kernel/sysctl.c:proc_do_cad_pid
  - kernel/pid.c:__ia32_sys_pidfd_open
  - kernel/pid.c:__x64_sys_pidfd_open
  - kernel/pid.c:pidfd_create
  - kernel/pid.c:delayed_put_pid
  - kernel/time/posix-timers.c:release_posix_timer
  - kernel/audit.c:auditd_conn_free
  - fs/file_table.c:__fput
  - fs/fcntl.c:f_modown
  - fs/proc/inode.c:proc_evict_inode
  - fs/proc/array.c:children_seq_stop
  - fs/proc/array.c:children_seq_next
  - fs/proc/array.c:do_task_stat
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:freeque
  - ipc/msg.c:freeque
  - ipc/sem.c:exit_sem
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:freeary
  - ipc/sem.c:perform_atomic_semop
  - ipc/sem.c:perform_atomic_semop
  - ipc/shm.c:newseg
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
  - ipc/shm.c:shm_destroy
  - ipc/shm.c:shm_destroy
  - ipc/mqueue.c:remove_notification
  - ipc/mqueue.c:__do_notify
  - drivers/tty/tty_io.c:tty_do_resize
  - drivers/tty/tty_io.c:__tty_fasync
  - drivers/tty/tty_io.c:release_one_tty
  - drivers/tty/tty_io.c:release_one_tty
  - drivers/tty/n_tty.c:__isig
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/vt/vt_ioctl.c:reset_vc
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/keyboard.c:fn_spawn_con
  - drivers/tty/vt/vt.c:vc_deallocate
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
  - net/core/sock.c:__sk_destruct
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_listen
  - net/unix/af_unix.c:init_peercred
  - net/unix/scm.c:unix_destruct_scm
  - net/ipv6/ip6_flowlabel.c:fl_free_rcu
```
**Symbols:**

```
ffffffff810ae640-ffffffff810ae681: put_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void put_pid(struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810bf380)
Location: kernel/pid.c:103
Inline: False
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/fork.c:pidfd_release
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:kernel_waitid
  - kernel/sysctl.c:proc_do_cad_pid
  - kernel/pid.c:__ia32_sys_pidfd_open
  - kernel/pid.c:__x64_sys_pidfd_open
  - kernel/pid.c:pidfd_create
  - kernel/pid.c:delayed_put_pid
  - kernel/time/posix-timers.c:release_posix_timer
  - kernel/audit.c:auditd_conn_free
  - fs/file_table.c:__fput
  - fs/fcntl.c:f_modown
  - fs/proc/inode.c:proc_evict_inode
  - fs/proc/array.c:children_seq_stop
  - fs/proc/array.c:children_seq_next
  - fs/proc/array.c:do_task_stat
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:freeque
  - ipc/msg.c:freeque
  - ipc/sem.c:exit_sem
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:freeary
  - ipc/sem.c:perform_atomic_semop
  - ipc/sem.c:perform_atomic_semop
  - ipc/shm.c:newseg
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
  - ipc/shm.c:shm_destroy
  - ipc/shm.c:shm_destroy
  - ipc/mqueue.c:remove_notification
  - ipc/mqueue.c:__do_notify
  - drivers/tty/tty_io.c:tty_do_resize
  - drivers/tty/tty_io.c:__tty_fasync
  - drivers/tty/tty_io.c:release_one_tty
  - drivers/tty/tty_io.c:release_one_tty
  - drivers/tty/n_tty.c:__isig
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/vt/vt_ioctl.c:reset_vc
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/keyboard.c:fn_spawn_con
  - drivers/tty/vt/vt.c:vc_deallocate
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
  - net/core/sock.c:__sk_destruct
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_listen
  - net/unix/af_unix.c:init_peercred
  - net/unix/scm.c:unix_destruct_scm
  - net/ipv6/ip6_flowlabel.c:fl_free_rcu
```
**Symbols:**

```
ffffffff810bf380-ffffffff810bf3c1: put_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void put_pid(struct pid *pid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810c76b0)
Location: kernel/pid.c:103
Inline: False
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/fork.c:pidfd_release
  - kernel/exit.c:kernel_wait4
  - kernel/exit.c:kernel_waitid
  - kernel/sysctl.c:proc_do_cad_pid
  - kernel/pid.c:__ia32_sys_pidfd_open
  - kernel/pid.c:__x64_sys_pidfd_open
  - kernel/pid.c:pidfd_create
  - kernel/pid.c:delayed_put_pid
  - kernel/time/posix-timers.c:release_posix_timer
  - kernel/audit.c:auditd_conn_free
  - fs/file_table.c:__fput
  - fs/fcntl.c:f_modown
  - fs/proc/inode.c:proc_evict_inode
  - fs/proc/array.c:children_seq_stop
  - fs/proc/array.c:children_seq_next
  - fs/proc/array.c:do_task_stat
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:freeque
  - ipc/msg.c:freeque
  - ipc/sem.c:exit_sem
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:freeary
  - ipc/sem.c:perform_atomic_semop
  - ipc/sem.c:perform_atomic_semop
  - ipc/shm.c:newseg
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
  - ipc/shm.c:shm_destroy
  - ipc/shm.c:shm_destroy
  - ipc/mqueue.c:remove_notification
  - ipc/mqueue.c:__do_notify
  - drivers/tty/tty_io.c:tty_do_resize
  - drivers/tty/tty_io.c:__tty_fasync
  - drivers/tty/tty_io.c:release_one_tty
  - drivers/tty/tty_io.c:release_one_tty
  - drivers/tty/n_tty.c:__isig
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/pty.c:pty_resize
  - drivers/tty/vt/vt_ioctl.c:reset_vc
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/keyboard.c:fn_spawn_con
  - drivers/tty/vt/vt.c:vc_deallocate
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
  - net/core/sock.c:__sk_destruct
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_listen
  - net/unix/af_unix.c:init_peercred
  - net/unix/scm.c:unix_destruct_scm
  - net/ipv6/ip6_flowlabel.c:fl_free_rcu
```
**Symbols:**

```
ffffffff810c76b0-ffffffff810c76f1: put_pid (STB_GLOBAL)
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
