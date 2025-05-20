# Function: <code>get_pid</code>

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
In kernel/pid.c (ffffffff8109dbc5)
Location: include/linux/pid.h:75
Inline: True
Inline callers:
  - kernel/pid.c:get_task_pid
  - kernel/pid.c:find_get_pid
```
```
In kernel/time/posix-timers.c (ffffffff810f165a)
Location: include/linux/pid.h:75
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:SyS_timer_create
  - kernel/time/posix-timers.c:SyS_timer_create
```
```
In fs/fcntl.c (ffffffff8121eb5f)
Location: include/linux/pid.h:75
Inline: True
Inline callers:
  - fs/fcntl.c:f_modown
```
```
In fs/notify/fanotify/fanotify.c (ffffffff812529e3)
Location: include/linux/pid.h:75
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/locks.c (ffffffff8125f984)
Location: include/linux/pid.h:75
Inline: True
Inline callers:
  - fs/locks.c:locks_insert_lock_ctx
```
```
In fs/proc/array.c (ffffffff812808d0)
Location: include/linux/pid.h:75
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
  - fs/proc/array.c:get_children_pid
```
```
In ipc/mqueue.c (ffffffff8132e29b)
Location: include/linux/pid.h:75
Inline: True
Inline callers:
  - ipc/mqueue.c:SyS_mq_notify
```
```
In drivers/tty/tty_io.c (ffffffff814df605)
Location: include/linux/pid.h:75
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_get_pgrp
  - drivers/tty/tty_io.c:__proc_set_tty
  - drivers/tty/tty_io.c:__proc_set_tty
  - drivers/tty/tty_io.c:__tty_fasync
  - drivers/tty/tty_io.c:__tty_hangup
  - drivers/tty/tty_io.c:__tty_hangup
  - drivers/tty/tty_io.c:tty_ioctl
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff814ef8f7)
Location: include/linux/pid.h:75
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
```
In drivers/usb/core/devio.c (ffffffff81619d07)
Location: include/linux/pid.h:75
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:proc_do_submiturb
```
```
In net/netlink/af_netlink.c (ffffffff8174e6f8)
Location: include/linux/pid.h:75
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/unix/af_unix.c (ffffffff817be341)
Location: include/linux/pid.h:75
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_scm_to_skb
  - net/unix/af_unix.c:init_peercred
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:maybe_init_creds
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_connect
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
In kernel/pid.c (ffffffff810a129f)
Location: include/linux/pid.h:75
Inline: True
Inline callers:
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:get_task_pid
```
```
In kernel/time/posix-timers.c (ffffffff810f872e)
Location: include/linux/pid.h:75
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:SyS_timer_create
  - kernel/time/posix-timers.c:SyS_timer_create
```
```
In fs/fcntl.c (ffffffff812464ef)
Location: include/linux/pid.h:75
Inline: True
Inline callers:
  - fs/fcntl.c:f_modown
```
```
In fs/notify/fanotify/fanotify.c (ffffffff8127b1a3)
Location: include/linux/pid.h:75
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/locks.c (ffffffff8128bb24)
Location: include/linux/pid.h:75
Inline: True
Inline callers:
  - fs/locks.c:locks_insert_lock_ctx
```
```
In fs/proc/array.c (ffffffff812ad930)
Location: include/linux/pid.h:75
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
  - fs/proc/array.c:get_children_pid
```
```
In ipc/mqueue.c (ffffffff81362f26)
Location: include/linux/pid.h:75
Inline: True
Inline callers:
  - ipc/mqueue.c:SyS_mq_notify
```
```
In drivers/tty/tty_io.c (ffffffff815342da)
Location: include/linux/pid.h:75
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_get_pgrp
  - drivers/tty/tty_io.c:__tty_fasync
  - drivers/tty/tty_io.c:__tty_hangup
  - drivers/tty/tty_io.c:__tty_hangup
  - drivers/tty/tty_io.c:__proc_set_tty
  - drivers/tty/tty_io.c:__proc_set_tty
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff81540542)
Location: include/linux/pid.h:75
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
```
In drivers/usb/core/devio.c (ffffffff8167c772)
Location: include/linux/pid.h:75
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:async_completed
```
```
In net/netlink/af_netlink.c (ffffffff817ba90e)
Location: include/linux/pid.h:75
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/unix/af_unix.c (ffffffff8182c77f)
Location: include/linux/pid.h:75
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:maybe_init_creds
  - net/unix/af_unix.c:unix_scm_to_skb
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
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
In kernel/pid.c (ffffffff810a635f)
Location: include/linux/pid.h:75
Inline: True
Inline callers:
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:get_task_pid
```
```
In kernel/time/posix-timers.c (ffffffff811060be)
Location: include/linux/pid.h:75
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:SyS_timer_create
  - kernel/time/posix-timers.c:SyS_timer_create
```
```
In fs/fcntl.c (ffffffff812594dc)
Location: include/linux/pid.h:75
Inline: True
Inline callers:
  - fs/fcntl.c:f_modown
```
```
In fs/notify/fanotify/fanotify.c (ffffffff8128ed53)
Location: include/linux/pid.h:75
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/locks.c (ffffffff8129f886)
Location: include/linux/pid.h:75
Inline: True
Inline callers:
  - fs/locks.c:locks_insert_lock_ctx
```
```
In fs/proc/array.c (ffffffff812c3220)
Location: include/linux/pid.h:75
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
  - fs/proc/array.c:get_children_pid
```
```
In ipc/mqueue.c (ffffffff81379702)
Location: include/linux/pid.h:75
Inline: True
Inline callers:
  - ipc/mqueue.c:SyS_mq_notify
```
```
In drivers/tty/tty_io.c (ffffffff81560a05)
Location: include/linux/pid.h:75
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_get_pgrp
  - drivers/tty/tty_io.c:__tty_fasync
  - drivers/tty/tty_io.c:__tty_hangup
  - drivers/tty/tty_io.c:__tty_hangup
  - drivers/tty/tty_io.c:__proc_set_tty
  - drivers/tty/tty_io.c:__proc_set_tty
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff8156cb82)
Location: include/linux/pid.h:75
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
```
In drivers/usb/core/devio.c (ffffffff816aa492)
Location: include/linux/pid.h:75
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:async_completed
```
```
In net/netlink/af_netlink.c (ffffffff817ea2ae)
Location: include/linux/pid.h:75
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/unix/af_unix.c (ffffffff8185e236)
Location: include/linux/pid.h:75
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:maybe_init_creds
  - net/unix/af_unix.c:unix_scm_to_skb
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
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
In kernel/pid.c (ffffffff810a3341)
Location: include/linux/pid.h:77
Inline: True
Inline callers:
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:get_task_pid
```
```
In kernel/time/posix-timers.c (ffffffff811080ce)
Location: include/linux/pid.h:77
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/audit.c (ffffffff81136ae3)
Location: include/linux/pid.h:77
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
```
```
In fs/fcntl.c (ffffffff812655bc)
Location: include/linux/pid.h:77
Inline: True
Inline callers:
  - fs/fcntl.c:f_modown
```
```
In fs/notify/fanotify/fanotify.c (ffffffff8129bbc5)
Location: include/linux/pid.h:77
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/locks.c (ffffffff812ae6f6)
Location: include/linux/pid.h:77
Inline: True
Inline callers:
  - fs/locks.c:locks_insert_lock_ctx
```
```
In fs/proc/array.c (ffffffff812d04a0)
Location: include/linux/pid.h:77
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
  - fs/proc/array.c:get_children_pid
```
```
In ipc/mqueue.c (ffffffff8138c317)
Location: include/linux/pid.h:77
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_notify
```
```
In drivers/tty/tty_io.c (ffffffff8157260b)
Location: include/linux/pid.h:77
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:__tty_fasync
```
```
In drivers/tty/tty_jobctrl.c (ffffffff8157d8aa)
Location: include/linux/pid.h:77
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_get_pgrp
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff81580528)
Location: include/linux/pid.h:77
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
```
In drivers/usb/core/devio.c (ffffffff816bf373)
Location: include/linux/pid.h:77
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:async_completed
```
```
In net/netlink/af_netlink.c (ffffffff81809f72)
Location: include/linux/pid.h:77
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/unix/af_unix.c (ffffffff818836b2)
Location: include/linux/pid.h:77
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:maybe_init_creds
  - net/unix/af_unix.c:unix_scm_to_skb
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
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
In kernel/pid.c (ffffffff810a9e2c)
Location: include/linux/pid.h:76
Inline: True
Inline callers:
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:get_task_pid
```
```
In kernel/time/posix-timers.c (ffffffff8111327c)
Location: include/linux/pid.h:76
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/audit.c (ffffffff81143472)
Location: include/linux/pid.h:76
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
```
```
In fs/fcntl.c (ffffffff812881cc)
Location: include/linux/pid.h:76
Inline: True
```
```
In fs/notify/fanotify/fanotify.c (ffffffff812befd5)
Location: include/linux/pid.h:76
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/proc/array.c (ffffffff812f4ce0)
Location: include/linux/pid.h:76
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
  - fs/proc/array.c:get_children_pid
```
```
In ipc/mqueue.c (ffffffff813b16c7)
Location: include/linux/pid.h:76
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_notify
```
```
In drivers/tty/tty_io.c (ffffffff815d698b)
Location: include/linux/pid.h:76
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:__tty_fasync
```
```
In drivers/tty/tty_jobctrl.c (ffffffff815e23cf)
Location: include/linux/pid.h:76
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_get_pgrp
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff815e50a8)
Location: include/linux/pid.h:76
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
```
In drivers/usb/core/devio.c (ffffffff8172ad58)
Location: include/linux/pid.h:76
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:async_completed
```
```
In net/netlink/af_netlink.c (ffffffff81888ef2)
Location: include/linux/pid.h:76
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/unix/af_unix.c (ffffffff81903dba)
Location: include/linux/pid.h:76
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:maybe_init_creds
  - net/unix/af_unix.c:unix_scm_to_skb
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
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
In kernel/pid.c (ffffffff810b0a4a)
Location: include/linux/pid.h:76
Inline: True
Inline callers:
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:get_task_pid
```
```
In kernel/time/posix-timers.c (ffffffff8111f9b1)
Location: include/linux/pid.h:76
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/audit.c (ffffffff81151f62)
Location: include/linux/pid.h:76
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
```
```
In fs/fcntl.c (ffffffff812ae51c)
Location: include/linux/pid.h:76
Inline: True
Inline callers:
  - fs/fcntl.c:f_modown
```
```
In fs/notify/fanotify/fanotify.c (ffffffff812e7f26)
Location: include/linux/pid.h:76
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/proc/array.c (ffffffff81321242)
Location: include/linux/pid.h:76
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
  - fs/proc/array.c:get_children_pid
```
```
In ipc/msg.c (ffffffff813d8b5f)
Location: include/linux/pid.h:76
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
```
```
In ipc/sem.c (ffffffff813dd291)
Location: include/linux/pid.h:76
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:perform_atomic_semop
  - ipc/sem.c:perform_atomic_semop
```
```
In ipc/shm.c (ffffffff813de566)
Location: include/linux/pid.h:76
Inline: True
Inline callers:
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
```
```
In ipc/mqueue.c (ffffffff813e191d)
Location: include/linux/pid.h:76
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_notify
```
```
In drivers/tty/tty_io.c (ffffffff8160f9c0)
Location: include/linux/pid.h:76
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:__tty_fasync
```
```
In drivers/tty/tty_jobctrl.c (ffffffff8161b6bc)
Location: include/linux/pid.h:76
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_get_pgrp
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff8161e8ef)
Location: include/linux/pid.h:76
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
```
In drivers/usb/core/devio.c (ffffffff81769990)
Location: include/linux/pid.h:76
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:async_completed
```
```
In net/netlink/af_netlink.c (ffffffff818dc962)
Location: include/linux/pid.h:76
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/unix/af_unix.c (ffffffff8195bee4)
Location: include/linux/pid.h:76
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:maybe_init_creds
  - net/unix/af_unix.c:unix_scm_to_skb
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
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
In kernel/pid.c (ffffffff810b9b1a)
Location: include/linux/pid.h:69
Inline: True
Inline callers:
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:get_task_pid
```
```
In kernel/time/posix-timers.c (ffffffff8112b188)
Location: include/linux/pid.h:69
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/audit.c (ffffffff8115ec1d)
Location: include/linux/pid.h:69
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
```
```
In fs/fcntl.c (ffffffff812c360c)
Location: include/linux/pid.h:69
Inline: True
Inline callers:
  - fs/fcntl.c:f_modown
```
```
In fs/notify/fanotify/fanotify.c (ffffffff812fcb91)
Location: include/linux/pid.h:69
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/proc/array.c (ffffffff81338352)
Location: include/linux/pid.h:69
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
  - fs/proc/array.c:get_children_pid
```
```
In ipc/msg.c (ffffffff813f29df)
Location: include/linux/pid.h:69
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
```
```
In ipc/sem.c (ffffffff813f78f1)
Location: include/linux/pid.h:69
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:perform_atomic_semop
  - ipc/sem.c:perform_atomic_semop
```
```
In ipc/shm.c (ffffffff813f8c24)
Location: include/linux/pid.h:69
Inline: True
Inline callers:
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
```
```
In ipc/mqueue.c (ffffffff813fc4ed)
Location: include/linux/pid.h:69
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_notify
```
```
In drivers/tty/tty_io.c (ffffffff8162c970)
Location: include/linux/pid.h:69
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:__tty_fasync
```
```
In drivers/tty/tty_jobctrl.c (ffffffff816389c6)
Location: include/linux/pid.h:69
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_get_pgrp
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff8163bb4f)
Location: include/linux/pid.h:69
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
```
In drivers/usb/core/devio.c (ffffffff8178e01b)
Location: include/linux/pid.h:69
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:async_completed
```
```
In net/netlink/af_netlink.c (ffffffff81909346)
Location: include/linux/pid.h:69
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/unix/af_unix.c (ffffffff819906fd)
Location: include/linux/pid.h:69
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:maybe_init_creds
  - net/unix/af_unix.c:unix_scm_to_skb
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
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
In kernel/fork.c (ffffffff810999d5)
Location: include/linux/pid.h:75
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/pid.c (ffffffff810bf8e5)
Location: include/linux/pid.h:75
Inline: True
Inline callers:
  - kernel/pid.c:pidfd_create
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:get_task_pid
```
```
In kernel/time/posix-timers.c (ffffffff811361cf)
Location: include/linux/pid.h:75
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/audit.c (ffffffff8116b0b8)
Location: include/linux/pid.h:75
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
```
```
In fs/fcntl.c (ffffffff812e002c)
Location: include/linux/pid.h:75
Inline: True
Inline callers:
  - fs/fcntl.c:f_modown
```
```
In fs/notify/fanotify/fanotify.c (ffffffff8131d689)
Location: include/linux/pid.h:75
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/proc/array.c (ffffffff81360a06)
Location: include/linux/pid.h:75
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
  - fs/proc/array.c:get_children_pid
```
```
In ipc/msg.c (ffffffff8141f818)
Location: include/linux/pid.h:75
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
```
```
In ipc/sem.c (ffffffff81423e1f)
Location: include/linux/pid.h:75
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:perform_atomic_semop
  - ipc/sem.c:perform_atomic_semop
```
```
In ipc/shm.c (ffffffff8142513e)
Location: include/linux/pid.h:75
Inline: True
Inline callers:
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
```
```
In ipc/mqueue.c (ffffffff8142915e)
Location: include/linux/pid.h:75
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_notify
```
```
In drivers/tty/tty_io.c (ffffffff816608c4)
Location: include/linux/pid.h:75
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:__tty_fasync
```
```
In drivers/tty/tty_jobctrl.c (ffffffff8166cc51)
Location: include/linux/pid.h:75
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_get_pgrp
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff8166fad5)
Location: include/linux/pid.h:75
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
```
In drivers/usb/core/devio.c (ffffffff817cc8a9)
Location: include/linux/pid.h:75
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:async_completed
```
```
In net/netlink/af_netlink.c (ffffffff8196a657)
Location: include/linux/pid.h:75
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/unix/af_unix.c (ffffffff819fbdef)
Location: include/linux/pid.h:75
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:maybe_init_creds
  - net/unix/af_unix.c:unix_scm_to_skb
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
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
In kernel/fork.c (ffffffff8109f652)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffff810a5bfd)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - kernel/exit.c:kernel_waitid
```
```
In kernel/pid.c (ffffffff810c5cb5)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - kernel/pid.c:pidfd_create
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:get_task_pid
```
```
In kernel/time/posix-timers.c (ffffffff8114226f)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/audit.c (ffffffff81176f83)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
```
```
In fs/fcntl.c (ffffffff812f1acc)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - fs/fcntl.c:f_modown
```
```
In fs/notify/fanotify/fanotify.c (ffffffff813304c9)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/proc/array.c (ffffffff81378c66)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
  - fs/proc/array.c:get_children_pid
```
```
In ipc/msg.c (ffffffff81439638)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
```
```
In ipc/sem.c (ffffffff8143db75)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:perform_atomic_semop
  - ipc/sem.c:perform_atomic_semop
```
```
In ipc/shm.c (ffffffff8143ee8e)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
```
```
In ipc/mqueue.c (ffffffff81442e9c)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_notify
```
```
In drivers/tty/tty_io.c (ffffffff81682f14)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:__tty_fasync
```
```
In drivers/tty/tty_jobctrl.c (ffffffff8168f2c1)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_get_pgrp
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff81692136)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
```
In drivers/usb/core/devio.c (ffffffff817fd545)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:async_completed
```
```
In net/netlink/af_netlink.c (ffffffff819a10c7)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/unix/af_unix.c (ffffffff81a32a7f)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:maybe_init_creds
  - net/unix/af_unix.c:unix_scm_to_skb
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
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
In kernel/fork.c (ffffffff810a6781)
Location: include/linux/pid.h:81
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffff810ad72e)
Location: include/linux/pid.h:81
Inline: True
Inline callers:
  - kernel/exit.c:kernel_waitid
  - kernel/exit.c:release_task
```
```
In kernel/pid.c (ffffffff810cd748)
Location: include/linux/pid.h:81
Inline: True
Inline callers:
  - kernel/pid.c:__ia32_sys_pidfd_open
  - kernel/pid.c:__x64_sys_pidfd_open
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:get_task_pid
```
```
In kernel/time/posix-timers.c (ffffffff81150b08)
Location: include/linux/pid.h:81
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811528c4)
Location: include/linux/pid.h:81
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_create
```
```
In kernel/audit.c (ffffffff81189903)
Location: include/linux/pid.h:81
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
```
```
In fs/fcntl.c (ffffffff81329d0c)
Location: include/linux/pid.h:81
Inline: True
```
```
In fs/notify/fanotify/fanotify.c (ffffffff8136aa6f)
Location: include/linux/pid.h:81
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/proc/array.c (ffffffff813c1cda)
Location: include/linux/pid.h:81
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
  - fs/proc/array.c:get_children_pid
```
```
In ipc/msg.c (ffffffff8148982f)
Location: include/linux/pid.h:81
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
```
```
In ipc/sem.c (ffffffff8148e6f5)
Location: include/linux/pid.h:81
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:perform_atomic_semop
  - ipc/sem.c:perform_atomic_semop_slow
```
```
In ipc/shm.c (ffffffff8148f9e3)
Location: include/linux/pid.h:81
Inline: True
Inline callers:
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
```
```
In ipc/mqueue.c (ffffffff8149376b)
Location: include/linux/pid.h:81
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_notify
```
```
In drivers/tty/tty_io.c (ffffffff81737002)
Location: include/linux/pid.h:81
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_fasync
```
```
In drivers/tty/tty_jobctrl.c (ffffffff8174187a)
Location: include/linux/pid.h:81
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tiocspgrp
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff81744a32)
Location: include/linux/pid.h:81
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
```
In drivers/usb/core/devio.c (ffffffff818ccd55)
Location: include/linux/pid.h:81
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:async_completed
```
```
In net/netlink/af_netlink.c (ffffffff81a7a9ef)
Location: include/linux/pid.h:81
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/unix/af_unix.c (ffffffff81b27610)
Location: include/linux/pid.h:81
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:maybe_init_creds
  - net/unix/af_unix.c:copy_peercred
  - net/unix/af_unix.c:init_peercred
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/fork.c (ffffffff810a2215)
Location: include/linux/pid.h:82
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffff810a7cee)
Location: include/linux/pid.h:82
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/pid.c (ffffffff810c811e)
Location: include/linux/pid.h:82
Inline: True
Inline callers:
  - kernel/pid.c:pidfd_create
  - kernel/pid.c:pidfd_create
  - kernel/pid.c:pidfd_get_pid
  - kernel/pid.c:pidfd_get_pid
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:get_task_pid
  - kernel/pid.c:get_task_pid
```
```
In kernel/usermode_driver.c (ffffffff810d5568)
Location: include/linux/pid.h:82
Inline: True
Inline callers:
  - kernel/usermode_driver.c:umd_setup
```
```
In kernel/time/posix-timers.c (ffffffff8114cd88)
Location: include/linux/pid.h:82
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8114eb14)
Location: include/linux/pid.h:82
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_create
```
```
In kernel/audit.c (ffffffff81183a8d)
Location: include/linux/pid.h:82
Inline: True
Inline callers:
  - kernel/audit.c:auditd_set
```
```
In fs/fcntl.c (ffffffff8133526c)
Location: include/linux/pid.h:82
Inline: True
```
```
In fs/notify/fanotify/fanotify.c (ffffffff81377d07)
Location: include/linux/pid.h:82
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/proc/array.c (ffffffff813d3dfa)
Location: include/linux/pid.h:82
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
  - fs/proc/array.c:get_children_pid
  - fs/proc/array.c:get_children_pid
```
```
In ipc/msg.c (ffffffff814a6e68)
Location: include/linux/pid.h:82
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
```
```
In ipc/sem.c (ffffffff814abe31)
Location: include/linux/pid.h:82
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:perform_atomic_semop
  - ipc/sem.c:perform_atomic_semop_slow
```
```
In ipc/shm.c (ffffffff814ad0e3)
Location: include/linux/pid.h:82
Inline: True
Inline callers:
  - ipc/shm.c:newseg
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
  - ipc/shm.c:shm_close
```
```
In ipc/mqueue.c (ffffffff814b106b)
Location: include/linux/pid.h:82
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_notify
```
```
In drivers/tty/tty_io.c (ffffffff817528a2)
Location: include/linux/pid.h:82
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_fasync
  - drivers/tty/tty_io.c:tty_fasync
```
```
In drivers/tty/tty_jobctrl.c (ffffffff8175c97c)
Location: include/linux/pid.h:82
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_get_pgrp
  - drivers/tty/tty_jobctrl.c:tty_get_pgrp
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff817610f3)
Location: include/linux/pid.h:82
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_setactivate
  - drivers/tty/vt/vt_ioctl.c:vt_setactivate
  - drivers/tty/vt/vt_ioctl.c:vt_k_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_k_ioctl
Direct callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
```
In drivers/usb/core/devio.c (ffffffff818d7f4d)
Location: include/linux/pid.h:82
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:async_completed
```
```
In net/netlink/af_netlink.c (ffffffff81a83845)
Location: include/linux/pid.h:82
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/unix/af_unix.c (ffffffff81b35ef6)
Location: include/linux/pid.h:82
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:maybe_init_creds
  - net/unix/af_unix.c:maybe_init_creds
  - net/unix/af_unix.c:copy_peercred
  - net/unix/af_unix.c:copy_peercred
  - net/unix/af_unix.c:init_peercred
  - net/unix/af_unix.c:init_peercred
```
**Symbols:**

```
ffffffff81760300-ffffffff81760332: get_pid.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In init/main.c (ffffffff831b9a3a)
Location: include/linux/pid.h:82
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In kernel/fork.c (ffffffff810a2f0b)
Location: include/linux/pid.h:82
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffff810a8bce)
Location: include/linux/pid.h:82
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/pid.c (ffffffff810c9bbe)
Location: include/linux/pid.h:82
Inline: True
Inline callers:
  - kernel/pid.c:pidfd_create
  - kernel/pid.c:pidfd_create
  - kernel/pid.c:pidfd_get_pid
  - kernel/pid.c:pidfd_get_pid
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:get_task_pid
  - kernel/pid.c:get_task_pid
```
```
In kernel/usermode_driver.c (ffffffff810d7228)
Location: include/linux/pid.h:82
Inline: True
Inline callers:
  - kernel/usermode_driver.c:umd_setup
```
```
In kernel/time/posix-timers.c (ffffffff8114f25e)
Location: include/linux/pid.h:82
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8114ffa4)
Location: include/linux/pid.h:82
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_create
```
```
In kernel/audit.c (ffffffff81187c57)
Location: include/linux/pid.h:82
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
```
```
In fs/fcntl.c (ffffffff8133b33c)
Location: include/linux/pid.h:82
Inline: True
```
```
In fs/notify/fanotify/fanotify.c (ffffffff8137e7cb)
Location: include/linux/pid.h:82
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/proc/array.c (ffffffff813dac2a)
Location: include/linux/pid.h:82
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
  - fs/proc/array.c:get_children_pid
  - fs/proc/array.c:get_children_pid
```
```
In ipc/msg.c (ffffffff814acdc0)
Location: include/linux/pid.h:82
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
```
```
In ipc/sem.c (ffffffff814b1ce9)
Location: include/linux/pid.h:82
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:perform_atomic_semop
  - ipc/sem.c:perform_atomic_semop_slow
```
```
In ipc/shm.c (ffffffff814b2f6b)
Location: include/linux/pid.h:82
Inline: True
Inline callers:
  - ipc/shm.c:newseg
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
  - ipc/shm.c:shm_close
```
```
In ipc/mqueue.c (ffffffff814b6edb)
Location: include/linux/pid.h:82
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_notify
```
```
In drivers/tty/tty_io.c (ffffffff817360e2)
Location: include/linux/pid.h:82
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_fasync
  - drivers/tty/tty_io.c:tty_fasync
```
```
In drivers/tty/tty_jobctrl.c (ffffffff817415fe)
Location: include/linux/pid.h:82
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_get_pgrp
  - drivers/tty/tty_jobctrl.c:tty_get_pgrp
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff81744aff)
Location: include/linux/pid.h:82
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_k_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_k_ioctl
Direct callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
```
In drivers/usb/core/devio.c (ffffffff818bae40)
Location: include/linux/pid.h:82
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:async_completed
```
```
In net/netlink/af_netlink.c (ffffffff81a6c91a)
Location: include/linux/pid.h:82
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/unix/af_unix.c (ffffffff81b23ae3)
Location: include/linux/pid.h:82
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:maybe_init_creds
  - net/unix/af_unix.c:maybe_init_creds
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
  - net/unix/af_unix.c:init_peercred
```
**Symbols:**

```
ffffffff81743f30-ffffffff81743f62: get_pid.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In init/main.c (ffffffff83299e16)
Location: include/linux/pid.h:83
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In kernel/fork.c (ffffffff810b4679)
Location: include/linux/pid.h:83
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffff810ba6c1)
Location: include/linux/pid.h:83
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/pid.c (ffffffff810dd9bc)
Location: include/linux/pid.h:83
Inline: True
Inline callers:
  - kernel/pid.c:pidfd_create
  - kernel/pid.c:pidfd_create
  - kernel/pid.c:pidfd_get_pid
  - kernel/pid.c:pidfd_get_pid
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:get_task_pid
  - kernel/pid.c:get_task_pid
```
```
In kernel/usermode_driver.c (ffffffff810eaad8)
Location: include/linux/pid.h:83
Inline: True
Inline callers:
  - kernel/usermode_driver.c:umd_setup
```
```
In kernel/time/posix-timers.c (ffffffff81173412)
Location: include/linux/pid.h:83
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81174194)
Location: include/linux/pid.h:83
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_create
```
```
In kernel/audit.c (ffffffff811b00b7)
Location: include/linux/pid.h:83
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
```
```
In fs/fcntl.c (ffffffff81388f7c)
Location: include/linux/pid.h:83
Inline: True
```
```
In fs/notify/fanotify/fanotify.c (ffffffff813cb8ab)
Location: include/linux/pid.h:83
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/proc/array.c (ffffffff8142c3ca)
Location: include/linux/pid.h:83
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
  - fs/proc/array.c:get_children_pid
  - fs/proc/array.c:get_children_pid
```
```
In ipc/msg.c (ffffffff815052ab)
Location: include/linux/pid.h:83
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
```
```
In ipc/sem.c (ffffffff8150a2a7)
Location: include/linux/pid.h:83
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:perform_atomic_semop
  - ipc/sem.c:perform_atomic_semop_slow
```
```
In ipc/shm.c (ffffffff8150b69d)
Location: include/linux/pid.h:83
Inline: True
Inline callers:
  - ipc/shm.c:newseg
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
  - ipc/shm.c:shm_close
```
```
In ipc/mqueue.c (ffffffff8150f81b)
Location: include/linux/pid.h:83
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_notify
```
```
In drivers/tty/tty_io.c (ffffffff817b6aa2)
Location: include/linux/pid.h:83
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_fasync
  - drivers/tty/tty_io.c:tty_fasync
```
```
In drivers/tty/tty_jobctrl.c (ffffffff817c205e)
Location: include/linux/pid.h:83
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_get_pgrp
  - drivers/tty/tty_jobctrl.c:tty_get_pgrp
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff817c594f)
Location: include/linux/pid.h:83
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_k_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_k_ioctl
Direct callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
```
In drivers/usb/core/devio.c (ffffffff819515cc)
Location: include/linux/pid.h:83
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:async_completed
```
```
In net/netlink/af_netlink.c (ffffffff81b25f6f)
Location: include/linux/pid.h:83
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/unix/af_unix.c (ffffffff81be7f9d)
Location: include/linux/pid.h:83
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:__unix_dgram_recvmsg
  - net/unix/af_unix.c:__unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:maybe_init_creds
  - net/unix/af_unix.c:maybe_init_creds
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
  - net/unix/af_unix.c:init_peercred
```
**Symbols:**

```
ffffffff817c4ca0-ffffffff817c4cd2: get_pid.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In init/main.c (ffffffff83448015)
Location: include/linux/pid.h:84
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In kernel/fork.c (ffffffff810cab8c)
Location: include/linux/pid.h:84
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffff810d1249)
Location: include/linux/pid.h:84
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/pid.c (ffffffff810f757b)
Location: include/linux/pid.h:84
Inline: True
Inline callers:
  - kernel/pid.c:__ia32_sys_pidfd_open
  - kernel/pid.c:__ia32_sys_pidfd_open
  - kernel/pid.c:__x64_sys_pidfd_open
  - kernel/pid.c:__x64_sys_pidfd_open
  - kernel/pid.c:pidfd_create
  - kernel/pid.c:pidfd_create
  - kernel/pid.c:pidfd_get_pid
  - kernel/pid.c:pidfd_get_pid
  - kernel/pid.c:get_task_pid
  - kernel/pid.c:get_task_pid
```
```
In kernel/usermode_driver.c (ffffffff811058c0)
Location: include/linux/pid.h:84
Inline: True
Inline callers:
  - kernel/usermode_driver.c:umd_setup
```
```
In kernel/time/posix-timers.c (ffffffff811a677b)
Location: include/linux/pid.h:84
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811a8ecb)
Location: include/linux/pid.h:84
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_create
```
```
In kernel/audit.c (ffffffff811e22a8)
Location: include/linux/pid.h:84
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
```
```
In fs/fcntl.c (ffffffff81409ece)
Location: include/linux/pid.h:84
Inline: True
```
```
In fs/notify/fanotify/fanotify.c (ffffffff81453fe3)
Location: include/linux/pid.h:84
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/proc/array.c (ffffffff814a56b4)
Location: include/linux/pid.h:84
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
  - fs/proc/array.c:get_children_pid
  - fs/proc/array.c:get_children_pid
```
```
In ipc/msg.c (ffffffff81596c6f)
Location: include/linux/pid.h:84
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
```
```
In ipc/sem.c (ffffffff8159c014)
Location: include/linux/pid.h:84
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:perform_atomic_semop
  - ipc/sem.c:perform_atomic_semop_slow
```
```
In ipc/shm.c (ffffffff8159d8fd)
Location: include/linux/pid.h:84
Inline: True
Inline callers:
  - ipc/shm.c:newseg
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
  - ipc/shm.c:shm_close
```
```
In ipc/mqueue.c (ffffffff815a2ae3)
Location: include/linux/pid.h:84
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_notify
```
```
In drivers/tty/tty_io.c (ffffffff818f40ef)
Location: include/linux/pid.h:84
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:__do_SAK
  - drivers/tty/tty_io.c:__do_SAK
  - drivers/tty/tty_io.c:tty_fasync
  - drivers/tty/tty_io.c:tty_fasync
```
```
In drivers/tty/tty_jobctrl.c (ffffffff818feadb)
Location: include/linux/pid.h:84
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_get_pgrp
  - drivers/tty/tty_jobctrl.c:tty_get_pgrp
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff81902823)
Location: include/linux/pid.h:84
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_k_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_k_ioctl
Direct callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
```
In drivers/usb/core/devio.c (ffffffff81aaa248)
Location: include/linux/pid.h:84
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:async_completed
```
```
In net/netlink/af_netlink.c (ffffffff81caeb91)
Location: include/linux/pid.h:84
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/unix/af_unix.c (ffffffff81d7f82a)
Location: include/linux/pid.h:84
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:__unix_dgram_recvmsg
  - net/unix/af_unix.c:__unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:maybe_init_creds
  - net/unix/af_unix.c:maybe_init_creds
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
  - net/unix/af_unix.c:init_peercred
```
**Symbols:**

```
ffffffff81901ae0-ffffffff81901b36: get_pid.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In init/main.c (ffffffff83e61959)
Location: include/linux/pid.h:84
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In kernel/fork.c (ffffffff810e8121)
Location: include/linux/pid.h:84
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffff810efc86)
Location: include/linux/pid.h:84
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/pid.c (ffffffff81119cfb)
Location: include/linux/pid.h:84
Inline: True
Inline callers:
  - kernel/pid.c:__ia32_sys_pidfd_open
  - kernel/pid.c:__ia32_sys_pidfd_open
  - kernel/pid.c:__x64_sys_pidfd_open
  - kernel/pid.c:__x64_sys_pidfd_open
  - kernel/pid.c:pidfd_create
  - kernel/pid.c:pidfd_create
  - kernel/pid.c:pidfd_get_pid
  - kernel/pid.c:pidfd_get_pid
  - kernel/pid.c:get_task_pid
  - kernel/pid.c:get_task_pid
```
```
In kernel/usermode_driver.c (ffffffff8112b3b0)
Location: include/linux/pid.h:84
Inline: True
Inline callers:
  - kernel/usermode_driver.c:umd_setup
```
```
In kernel/time/posix-timers.c (ffffffff811e631b)
Location: include/linux/pid.h:84
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811e8d3b)
Location: include/linux/pid.h:84
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_create
```
```
In kernel/audit.c (ffffffff8122814c)
Location: include/linux/pid.h:84
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
```
```
In fs/fcntl.c (ffffffff8149463e)
Location: include/linux/pid.h:84
Inline: True
```
```
In fs/notify/fanotify/fanotify.c (ffffffff814e2e93)
Location: include/linux/pid.h:84
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/proc/array.c (ffffffff8153ac94)
Location: include/linux/pid.h:84
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
  - fs/proc/array.c:get_children_pid
  - fs/proc/array.c:get_children_pid
```
```
In ipc/msg.c (ffffffff8163fb74)
Location: include/linux/pid.h:84
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
```
```
In ipc/sem.c (ffffffff81645414)
Location: include/linux/pid.h:84
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:perform_atomic_semop
  - ipc/sem.c:perform_atomic_semop_slow
```
```
In ipc/shm.c (ffffffff81646ecd)
Location: include/linux/pid.h:84
Inline: True
Inline callers:
  - ipc/shm.c:newseg
  - ipc/shm.c:newseg
  - ipc/shm.c:__shm_close
  - ipc/shm.c:__shm_close
  - ipc/shm.c:__shm_open
  - ipc/shm.c:__shm_open
```
```
In ipc/mqueue.c (ffffffff8164c603)
Location: include/linux/pid.h:84
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_notify
```
```
In drivers/tty/tty_io.c (ffffffff81a4c7c6)
Location: include/linux/pid.h:84
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:__do_SAK
  - drivers/tty/tty_io.c:__do_SAK
```
```
In drivers/tty/tty_jobctrl.c (ffffffff81a5831b)
Location: include/linux/pid.h:84
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_get_pgrp
  - drivers/tty/tty_jobctrl.c:tty_get_pgrp
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:get_current_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff81a5c7f3)
Location: include/linux/pid.h:84
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_k_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_k_ioctl
Direct callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
```
In drivers/usb/core/devio.c (ffffffff81c315c8)
Location: include/linux/pid.h:84
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:async_completed
```
```
In net/netlink/af_netlink.c (ffffffff81e6c1e1)
Location: include/linux/pid.h:84
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/unix/af_unix.c (ffffffff81f4d51a)
Location: include/linux/pid.h:84
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:__unix_dgram_recvmsg
  - net/unix/af_unix.c:__unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:maybe_init_creds
  - net/unix/af_unix.c:maybe_init_creds
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
  - net/unix/af_unix.c:init_peercred
```
**Symbols:**

```
ffffffff81a5ba50-ffffffff81a5baa6: get_pid.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In init/main.c (ffffffff83681d79)
Location: include/linux/pid.h:85
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In kernel/fork.c (ffffffff810f115e)
Location: include/linux/pid.h:85
Inline: True
Inline callers:
  - kernel/fork.c:__pidfd_prepare
```
```
In kernel/exit.c (ffffffff810fbc46)
Location: include/linux/pid.h:85
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/pid.c (ffffffff81125e0c)
Location: include/linux/pid.h:85
Inline: True
Inline callers:
  - kernel/pid.c:__ia32_sys_pidfd_open
  - kernel/pid.c:__ia32_sys_pidfd_open
  - kernel/pid.c:__x64_sys_pidfd_open
  - kernel/pid.c:__x64_sys_pidfd_open
  - kernel/pid.c:pidfd_get_pid
  - kernel/pid.c:pidfd_get_pid
  - kernel/pid.c:get_task_pid
  - kernel/pid.c:get_task_pid
```
```
In kernel/usermode_driver.c (ffffffff811386a0)
Location: include/linux/pid.h:85
Inline: True
Inline callers:
  - kernel/usermode_driver.c:umd_setup
```
```
In kernel/time/posix-timers.c (ffffffff811fa90e)
Location: include/linux/pid.h:85
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811fd80b)
Location: include/linux/pid.h:85
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_create
```
```
In kernel/audit.c (ffffffff8123e759)
Location: include/linux/pid.h:85
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
```
```
In fs/fcntl.c (ffffffff814c96ae)
Location: include/linux/pid.h:85
Inline: True
```
```
In fs/notify/fanotify/fanotify.c (ffffffff81519687)
Location: include/linux/pid.h:85
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/proc/array.c (ffffffff81572f92)
Location: include/linux/pid.h:85
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
  - fs/proc/array.c:get_children_pid
  - fs/proc/array.c:get_children_pid
```
```
In ipc/msg.c (ffffffff8167809d)
Location: include/linux/pid.h:85
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
```
```
In ipc/sem.c (ffffffff8167d905)
Location: include/linux/pid.h:85
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:perform_atomic_semop
  - ipc/sem.c:perform_atomic_semop_slow
```
```
In ipc/shm.c (ffffffff8167f40d)
Location: include/linux/pid.h:85
Inline: True
Inline callers:
  - ipc/shm.c:newseg
  - ipc/shm.c:newseg
  - ipc/shm.c:__shm_close
  - ipc/shm.c:__shm_close
  - ipc/shm.c:__shm_open
  - ipc/shm.c:__shm_open
```
```
In ipc/mqueue.c (ffffffff81684d78)
Location: include/linux/pid.h:85
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_notify
```
```
In drivers/tty/tty_io.c (ffffffff81a96ab6)
Location: include/linux/pid.h:85
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:__do_SAK
  - drivers/tty/tty_io.c:__do_SAK
```
```
In drivers/tty/tty_jobctrl.c (ffffffff81aa2944)
Location: include/linux/pid.h:85
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_get_pgrp
  - drivers/tty/tty_jobctrl.c:tty_get_pgrp
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:get_current_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff81aa7328)
Location: include/linux/pid.h:85
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_k_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_k_ioctl
Direct callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
```
In drivers/usb/core/devio.c (ffffffff81c98856)
Location: include/linux/pid.h:85
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:async_completed
```
```
In net/core/sock.c (ffffffff81e0ee40)
Location: include/linux/pid.h:85
Inline: True
Inline callers:
  - net/core/sock.c:sk_getsockopt
```
```
In net/netlink/af_netlink.c (ffffffff81ec8241)
Location: include/linux/pid.h:85
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/unix/af_unix.c (ffffffff81facf33)
Location: include/linux/pid.h:85
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:__unix_dgram_recvmsg
  - net/unix/af_unix.c:__unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
  - net/unix/af_unix.c:init_peercred
```
**Symbols:**

```
ffffffff81aa6070-ffffffff81aa60c6: get_pid.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In init/main.c (ffffffff838b0da9)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In kernel/fork.c (ffffffff810fa52e)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - kernel/fork.c:__pidfd_prepare
```
```
In kernel/exit.c (ffffffff81105146)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - kernel/exit.c:release_task
```
```
In kernel/pid.c (ffffffff8113040c)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - kernel/pid.c:__ia32_sys_pidfd_open
  - kernel/pid.c:__ia32_sys_pidfd_open
  - kernel/pid.c:__x64_sys_pidfd_open
  - kernel/pid.c:__x64_sys_pidfd_open
  - kernel/pid.c:pidfd_get_pid
  - kernel/pid.c:pidfd_get_pid
  - kernel/pid.c:get_task_pid
  - kernel/pid.c:get_task_pid
```
```
In kernel/time/posix-timers.c (ffffffff81210afe)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81213a0b)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_create
```
```
In kernel/audit.c (ffffffff81254909)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - kernel/audit.c:auditd_set
```
```
In fs/fcntl.c (ffffffff814fbf6e)
Location: include/linux/pid.h:79
Inline: True
```
```
In fs/notify/fanotify/fanotify.c (ffffffff8154da67)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/proc/array.c (ffffffff815abec2)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
  - fs/proc/array.c:get_children_pid
  - fs/proc/array.c:get_children_pid
```
```
In ipc/msg.c (ffffffff816b445d)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
```
```
In ipc/sem.c (ffffffff816b9cd1)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:perform_atomic_semop
  - ipc/sem.c:perform_atomic_semop
```
```
In ipc/shm.c (ffffffff816bb7fd)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - ipc/shm.c:newseg
  - ipc/shm.c:newseg
  - ipc/shm.c:__shm_close
  - ipc/shm.c:__shm_close
  - ipc/shm.c:__shm_open
  - ipc/shm.c:__shm_open
```
```
In ipc/mqueue.c (ffffffff816c11ad)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_notify
```
```
In drivers/tty/tty_io.c (ffffffff81ae94a6)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:__do_SAK
  - drivers/tty/tty_io.c:__do_SAK
```
```
In drivers/tty/tty_jobctrl.c (ffffffff81af5324)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_get_pgrp
  - drivers/tty/tty_jobctrl.c:tty_get_pgrp
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:get_current_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff81af9db8)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_k_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_k_ioctl
Direct callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
```
In drivers/gpu/drm/drm_file.c (ffffffff81c97ff4)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_file.c:drm_file_update_pid
  - drivers/gpu/drm/drm_file.c:drm_file_update_pid
  - drivers/gpu/drm/drm_file.c:drm_file_alloc
  - drivers/gpu/drm/drm_file.c:drm_file_alloc
```
```
In drivers/usb/core/devio.c (ffffffff81d4d395)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:async_completed
```
```
In net/core/sock.c (ffffffff81ecb8d9)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - net/core/sock.c:sk_getsockopt
```
```
In net/netlink/af_netlink.c (ffffffff81f8b650)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/unix/af_unix.c (ffffffff8207b386)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:__unix_dgram_recvmsg
  - net/unix/af_unix.c:__unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
  - net/unix/af_unix.c:init_peercred
```
**Symbols:**

```
ffffffff81af8b00-ffffffff81af8b56: get_pid.part.0 (STB_LOCAL)
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
In kernel/fork.c (ffff8000100f3cb4)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffff8000100fbc9c)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - kernel/exit.c:kernel_waitid
```
```
In kernel/pid.c (ffff80001012438c)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - kernel/pid.c:__arm64_sys_pidfd_open
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:get_task_pid
```
```
In kernel/time/posix-timers.c (ffff8000101ac358)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/audit.c (ffff8000101ebee8)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
```
```
In fs/fcntl.c (ffff80001039b4d4)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - fs/fcntl.c:f_modown
```
```
In fs/notify/fanotify/fanotify.c (ffff8000103ed6d4)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/proc/array.c (ffff800010444ba8)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
  - fs/proc/array.c:get_children_pid
```
```
In ipc/msg.c (ffff80001051fb54)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
```
```
In ipc/sem.c (ffff8000105259d8)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:perform_atomic_semop
  - ipc/sem.c:perform_atomic_semop
```
```
In ipc/shm.c (ffff800010526628)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
```
```
In ipc/mqueue.c (ffff80001052c224)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_notify
```
```
In drivers/tty/tty_io.c (ffff800010851070)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:__tty_fasync
```
```
In drivers/tty/tty_jobctrl.c (ffff800010860fec)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_get_pgrp
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
```
```
In drivers/tty/vt/vt_ioctl.c (ffff80001086600c)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
```
In drivers/usb/core/devio.c (ffff800010a2e990)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:async_completed
```
```
In net/netlink/af_netlink.c (ffff800010c4f798)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/unix/af_unix.c (ffff800010cf2230)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:maybe_init_creds
  - net/unix/af_unix.c:unix_scm_to_skb
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
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
In kernel/fork.c (c0352718)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (c0359c80)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - kernel/exit.c:kernel_waitid
```
```
In kernel/pid.c (c0377d38)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - kernel/pid.c:__se_sys_pidfd_open
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:get_task_pid
```
```
In kernel/time/posix-timers.c (c03f67b0)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/audit.c (c042bb58)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
```
```
In fs/fcntl.c (c0581710)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - fs/fcntl.c:f_modown
```
```
In fs/notify/fanotify/fanotify.c (c05c3ec8)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/proc/array.c (c0609fec)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
  - fs/proc/array.c:get_children_pid
```
```
In ipc/msg.c (c06db92c)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
```
```
In ipc/sem.c (c06dfebc)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:ksys_semctl
  - ipc/sem.c:semctl_main
  - ipc/sem.c:perform_atomic_semop
  - ipc/sem.c:perform_atomic_semop
```
```
In ipc/shm.c (c06e0770)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
  - ipc/shm.c:__shm_open
```
```
In ipc/mqueue.c (c06e43d0)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_notify
```
```
In drivers/tty/tty_io.c (c095b394)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:__tty_fasync
```
```
In drivers/tty/tty_jobctrl.c (c0967d2c)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_get_pgrp
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
```
```
In drivers/tty/vt/vt_ioctl.c (c096c1cc)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
```
In drivers/usb/core/devio.c (c0b04670)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:async_completed
```
```
In sound/core/control.c (c0c85ab8)
Location: include/linux/pid.h:79
Inline: True
```
```
In sound/core/pcm.c (c0c90b2c)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - sound/core/pcm.c:snd_pcm_attach_substream
```
```
In net/netlink/af_netlink.c (c0d5f924)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/unix/af_unix.c (c0dfa108)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_scm_to_skb
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
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
In kernel/fork.c (c00000000013a050)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (c0000000001432f4)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - kernel/exit.c:kernel_waitid
```
```
In kernel/pid.c (c00000000016dfc8)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - kernel/pid.c:__se_sys_pidfd_open
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:get_task_pid
```
```
In kernel/time/posix-timers.c (c00000000020ffdc)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/audit.c (c00000000025d7c4)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
```
```
In fs/fcntl.c (c0000000004962b8)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - fs/fcntl.c:f_modown
```
```
In fs/notify/fanotify/fanotify.c (c0000000004f4db4)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/proc/array.c (c00000000055a9a4)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
  - fs/proc/array.c:get_children_pid
```
```
In ipc/msg.c (c00000000066a140)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
```
```
In ipc/sem.c (c00000000066ff2c)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:perform_atomic_semop
  - ipc/sem.c:perform_atomic_semop
```
```
In ipc/shm.c (c000000000671a8c)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
```
```
In ipc/mqueue.c (c000000000677cf8)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_notify
```
```
In drivers/tty/tty_io.c (c0000000008ee678)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:__tty_fasync
```
```
In drivers/tty/tty_jobctrl.c (c000000000900368)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_get_pgrp
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
```
```
In drivers/tty/vt/vt_ioctl.c (c000000000905f24)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
```
In drivers/usb/core/devio.c (c000000000aedb68)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:async_completed
```
```
In net/netlink/af_netlink.c (c000000000d4e0d8)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/unix/af_unix.c (c000000000e18640)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:maybe_init_creds
  - net/unix/af_unix.c:unix_scm_to_skb
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
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
In kernel/fork.c (ffffffe0000c0574)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffe0000c56ea)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - kernel/exit.c:kernel_waitid
```
```
In kernel/pid.c (ffffffe0000dcd1a)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - kernel/pid.c:__se_sys_pidfd_open
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:get_task_pid
```
```
In kernel/time/posix-timers.c (ffffffe0001362b6)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/audit.c (ffffffe000160674)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
```
```
In fs/fcntl.c (ffffffe000268602)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - fs/fcntl.c:f_modown
```
```
In fs/notify/fanotify/fanotify.c (ffffffe0002a110a)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/proc/array.c (ffffffe0002dabbc)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
  - fs/proc/array.c:get_children_pid
```
```
In ipc/msg.c (ffffffe000386186)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
```
```
In ipc/sem.c (ffffffe00038a304)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:__se_sys_semctl
  - ipc/sem.c:semctl_main
  - ipc/sem.c:perform_atomic_semop
  - ipc/sem.c:perform_atomic_semop
```
```
In ipc/shm.c (ffffffe00038aed8)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
```
```
In ipc/mqueue.c (ffffffe00038e6e6)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - ipc/mqueue.c:__se_sys_mq_notify
```
```
In drivers/tty/tty_io.c (ffffffe00052d756)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:__tty_fasync
```
```
In drivers/tty/tty_jobctrl.c (ffffffe0005389c4)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_get_pgrp
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffe00053c3e8)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
```
In drivers/usb/core/devio.c (ffffffe00064ec94)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:async_completed
```
```
In net/netlink/af_netlink.c (ffffffe0007bb3c0)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/unix/af_unix.c (ffffffe00083f1f8)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:maybe_init_creds
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
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
In kernel/fork.c (ffffffff81098f72)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffff8109f51d)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - kernel/exit.c:kernel_waitid
```
```
In kernel/pid.c (ffffffff810c0035)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - kernel/pid.c:pidfd_create
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:get_task_pid
```
```
In kernel/time/posix-timers.c (ffffffff8113aa1f)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/audit.c (ffffffff8116f5a3)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
```
```
In fs/fcntl.c (ffffffff812ea0ac)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - fs/fcntl.c:f_modown
```
```
In fs/notify/fanotify/fanotify.c (ffffffff81328aa9)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/proc/array.c (ffffffff81371246)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
  - fs/proc/array.c:get_children_pid
```
```
In ipc/msg.c (ffffffff81431c18)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
```
```
In ipc/sem.c (ffffffff81436155)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:perform_atomic_semop
  - ipc/sem.c:perform_atomic_semop
```
```
In ipc/shm.c (ffffffff8143746e)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
```
```
In ipc/mqueue.c (ffffffff8143b47c)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_notify
```
```
In drivers/tty/tty_io.c (ffffffff81648994)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:__tty_fasync
```
```
In drivers/tty/tty_jobctrl.c (ffffffff81654d41)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_get_pgrp
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff81657bb6)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
```
In drivers/usb/core/devio.c (ffffffff817b5925)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:async_completed
```
```
In net/netlink/af_netlink.c (ffffffff81940f37)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/unix/af_unix.c (ffffffff819d210f)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:maybe_init_creds
  - net/unix/af_unix.c:unix_scm_to_skb
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
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
In kernel/fork.c (ffffffff810879c2)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffff8108df4d)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - kernel/exit.c:kernel_waitid
```
```
In kernel/pid.c (ffffffff810ae845)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - kernel/pid.c:pidfd_create
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:get_task_pid
```
```
In kernel/time/posix-timers.c (ffffffff8112d46f)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/audit.c (ffffffff81162743)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
```
```
In fs/fcntl.c (ffffffff812daa76)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - fs/fcntl.c:f_modown
```
```
In fs/notify/fanotify/fanotify.c (ffffffff81319649)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/proc/array.c (ffffffff81361cd6)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
  - fs/proc/array.c:get_children_pid
```
```
In ipc/msg.c (ffffffff81422698)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
```
```
In ipc/sem.c (ffffffff81426bd5)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:perform_atomic_semop
  - ipc/sem.c:perform_atomic_semop
```
```
In ipc/shm.c (ffffffff81427ede)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
```
```
In ipc/mqueue.c (ffffffff8142beec)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_notify
```
```
In drivers/tty/tty_io.c (ffffffff81628df4)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:__tty_fasync
```
```
In drivers/tty/tty_jobctrl.c (ffffffff8163510b)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_get_pgrp
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff81637f46)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
```
In drivers/usb/core/devio.c (ffffffff817a7355)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:async_completed
```
```
In net/netlink/af_netlink.c (ffffffff818faa27)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/unix/af_unix.c (ffffffff8198eecf)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:maybe_init_creds
  - net/unix/af_unix.c:unix_scm_to_skb
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
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
In kernel/fork.c (ffffffff81098f22)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffff8109f4cd)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - kernel/exit.c:kernel_waitid
```
```
In kernel/pid.c (ffffffff810bf585)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - kernel/pid.c:pidfd_create
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:get_task_pid
```
```
In kernel/time/posix-timers.c (ffffffff8113873f)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/audit.c (ffffffff8116d373)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
```
```
In fs/fcntl.c (ffffffff812e7ebc)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - fs/fcntl.c:f_modown
```
```
In fs/notify/fanotify/fanotify.c (ffffffff81326579)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/proc/array.c (ffffffff8136ed16)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
  - fs/proc/array.c:get_children_pid
```
```
In ipc/msg.c (ffffffff8142ddb8)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
```
```
In ipc/sem.c (ffffffff814322f5)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:perform_atomic_semop
  - ipc/sem.c:perform_atomic_semop
```
```
In ipc/shm.c (ffffffff8143360e)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
```
```
In ipc/mqueue.c (ffffffff8143761c)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_notify
```
```
In drivers/tty/tty_io.c (ffffffff81676d54)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:__tty_fasync
```
```
In drivers/tty/tty_jobctrl.c (ffffffff81683101)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_get_pgrp
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff81685f76)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
```
In drivers/usb/core/devio.c (ffffffff817f23c5)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:async_completed
```
```
In net/netlink/af_netlink.c (ffffffff819920c7)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/unix/af_unix.c (ffffffff81a3cb8f)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:maybe_init_creds
  - net/unix/af_unix.c:unix_scm_to_skb
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a0b44)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/exit.c (ffffffff810a742d)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - kernel/exit.c:kernel_waitid
```
```
In kernel/pid.c (ffffffff810c7975)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - kernel/pid.c:pidfd_create
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:get_task_pid
```
```
In kernel/time/posix-timers.c (ffffffff81145341)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/audit.c (ffffffff8117ab69)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
```
```
In fs/fcntl.c (ffffffff812f8d30)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - fs/fcntl.c:f_modown
```
```
In fs/notify/fanotify/fanotify.c (ffffffff81338399)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/proc/array.c (ffffffff813826a5)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
  - fs/proc/array.c:get_children_pid
```
```
In ipc/msg.c (ffffffff81444815)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
```
```
In ipc/sem.c (ffffffff814493bf)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:perform_atomic_semop
  - ipc/sem.c:perform_atomic_semop
```
```
In ipc/shm.c (ffffffff8144a9de)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
```
```
In ipc/mqueue.c (ffffffff8144ed26)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_notify
```
```
In drivers/tty/tty_io.c (ffffffff81691474)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:__tty_fasync
```
```
In drivers/tty/tty_jobctrl.c (ffffffff8169d73f)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_get_pgrp
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff816a0576)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
```
In drivers/usb/core/devio.c (ffffffff8180c605)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:async_completed
```
```
In net/netlink/af_netlink.c (ffffffff819b4bb7)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/unix/af_unix.c (ffffffff81a48147)
Location: include/linux/pid.h:79
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:maybe_init_creds
  - net/unix/af_unix.c:unix_scm_to_skb
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
```
</details>
</li>
</ul>

## Differences
