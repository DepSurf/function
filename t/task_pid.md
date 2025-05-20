# Function: <code>task_pid</code>

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
In init/main.c (0)
Location: include/linux/sched.h:1872
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/sched.h:1872
Inline: True
```
```
In kernel/sys.c (ffffffff81094d4d)
Location: include/linux/sched.h:1872
Inline: True
Inline callers:
  - kernel/sys.c:SyS_setpgid
  - kernel/sys.c:sys_setsid
```
```
In kernel/pid.c (ffffffff8109db2f)
Location: include/linux/sched.h:1872
Inline: True
Inline callers:
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:pid_vnr
  - kernel/pid.c:__task_pid_nr_ns
  - kernel/pid.c:find_task_by_vpid
```
```
In kernel/time/posix-timers.c (ffffffff810f1653)
Location: include/linux/sched.h:1872
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:SyS_timer_create
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/sched.h:1872
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/sched.h:1872
Inline: True
```
```
In fs/notify/dnotify/dnotify.c (0)
Location: include/linux/sched.h:1872
Inline: True
```
```
In fs/locks.c (0)
Location: include/linux/sched.h:1872
Inline: True
```
```
In fs/proc/base.c (ffffffff8127e77b)
Location: include/linux/sched.h:1872
Inline: True
Inline callers:
  - fs/proc/base.c:proc_flush_task
```
```
In fs/proc/array.c (ffffffff812808c9)
Location: include/linux/sched.h:1872
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
  - fs/proc/array.c:get_children_pid
```
```
In fs/fuse/dev.c (0)
Location: include/linux/sched.h:1872
Inline: True
```
```
In drivers/tty/tty_io.c (ffffffff814e12aa)
Location: include/linux/sched.h:1872
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:__tty_fasync
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff814ef8f0)
Location: include/linux/sched.h:1872
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
```
In drivers/net/tun.c (0)
Location: include/linux/sched.h:1872
Inline: True
```
```
In drivers/usb/core/devio.c (ffffffff81619d00)
Location: include/linux/sched.h:1872
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:proc_do_submiturb
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
In init/main.c (0)
Location: include/linux/sched.h:2011
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/sched.h:2011
Inline: True
```
```
In kernel/sys.c (ffffffff810980a0)
Location: include/linux/sched.h:2011
Inline: True
Inline callers:
  - kernel/sys.c:sys_setsid
  - kernel/sys.c:SyS_setpgid
```
```
In kernel/pid.c (ffffffff810a1439)
Location: include/linux/sched.h:2011
Inline: True
Inline callers:
  - kernel/pid.c:__task_pid_nr_ns
  - kernel/pid.c:pid_vnr
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:find_task_by_vpid
```
```
In kernel/time/posix-timers.c (ffffffff810f8727)
Location: include/linux/sched.h:2011
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:SyS_timer_create
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/sched.h:2011
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/sched.h:2011
Inline: True
```
```
In fs/notify/dnotify/dnotify.c (0)
Location: include/linux/sched.h:2011
Inline: True
```
```
In fs/locks.c (0)
Location: include/linux/sched.h:2011
Inline: True
```
```
In fs/proc/base.c (ffffffff812ab77b)
Location: include/linux/sched.h:2011
Inline: True
Inline callers:
  - fs/proc/base.c:proc_flush_task
```
```
In fs/proc/array.c (ffffffff812ad929)
Location: include/linux/sched.h:2011
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
  - fs/proc/array.c:get_children_pid
```
```
In fs/fuse/dev.c (0)
Location: include/linux/sched.h:2011
Inline: True
```
```
In drivers/tty/tty_io.c (ffffffff81531009)
Location: include/linux/sched.h:2011
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:__tty_fasync
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff8154053b)
Location: include/linux/sched.h:2011
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
```
In drivers/net/tun.c (0)
Location: include/linux/sched.h:2011
Inline: True
```
```
In drivers/usb/core/devio.c (ffffffff8167c76b)
Location: include/linux/sched.h:2011
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
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
In init/main.c (0)
Location: include/linux/sched.h:2098
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/sched.h:2098
Inline: True
```
```
In kernel/sys.c (ffffffff8109d050)
Location: include/linux/sched.h:2098
Inline: True
Inline callers:
  - kernel/sys.c:sys_setsid
  - kernel/sys.c:SyS_setpgid
```
```
In kernel/pid.c (ffffffff810a64f9)
Location: include/linux/sched.h:2098
Inline: True
Inline callers:
  - kernel/pid.c:__task_pid_nr_ns
  - kernel/pid.c:pid_vnr
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:find_task_by_vpid
```
```
In kernel/time/posix-timers.c (ffffffff811060b7)
Location: include/linux/sched.h:2098
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:SyS_timer_create
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/sched.h:2098
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/sched.h:2098
Inline: True
```
```
In fs/notify/dnotify/dnotify.c (0)
Location: include/linux/sched.h:2098
Inline: True
```
```
In fs/locks.c (0)
Location: include/linux/sched.h:2098
Inline: True
```
```
In fs/proc/base.c (ffffffff812c103b)
Location: include/linux/sched.h:2098
Inline: True
Inline callers:
  - fs/proc/base.c:proc_flush_task
```
```
In fs/proc/array.c (ffffffff812c3219)
Location: include/linux/sched.h:2098
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
  - fs/proc/array.c:get_children_pid
```
```
In fs/fuse/dev.c (0)
Location: include/linux/sched.h:2098
Inline: True
```
```
In drivers/tty/tty_io.c (ffffffff8155d759)
Location: include/linux/sched.h:2098
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:__tty_fasync
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff8156cb7b)
Location: include/linux/sched.h:2098
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
```
In drivers/net/tun.c (0)
Location: include/linux/sched.h:2098
Inline: True
```
```
In drivers/usb/core/devio.c (ffffffff816aa48b)
Location: include/linux/sched.h:2098
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
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
In init/main.c (0)
Location: include/linux/sched.h:1108
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/sched.h:1108
Inline: True
```
```
In kernel/sys.c (ffffffff8109776b)
Location: include/linux/sched.h:1108
Inline: True
Inline callers:
  - kernel/sys.c:propagate_has_child_subreaper
  - kernel/sys.c:sys_setsid
  - kernel/sys.c:SyS_setpgid
```
```
In kernel/pid.c (ffffffff810a347b)
Location: include/linux/sched.h:1108
Inline: True
Inline callers:
  - kernel/pid.c:__task_pid_nr_ns
  - kernel/pid.c:pid_vnr
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:find_task_by_vpid
```
```
In kernel/time/posix-timers.c (ffffffff81108194)
Location: include/linux/sched.h:1108
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/sched.h:1108
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/sched.h:1108
Inline: True
```
```
In fs/notify/dnotify/dnotify.c (0)
Location: include/linux/sched.h:1108
Inline: True
```
```
In fs/locks.c (0)
Location: include/linux/sched.h:1108
Inline: True
```
```
In fs/proc/base.c (ffffffff812ce3cb)
Location: include/linux/sched.h:1108
Inline: True
Inline callers:
  - fs/proc/base.c:proc_flush_task
```
```
In fs/proc/array.c (ffffffff812d0499)
Location: include/linux/sched.h:1108
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
  - fs/proc/array.c:get_children_pid
```
```
In fs/fuse/dev.c (0)
Location: include/linux/sched.h:1108
Inline: True
```
```
In drivers/tty/tty_io.c (ffffffff81572640)
Location: include/linux/sched.h:1108
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:__tty_fasync
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff81580521)
Location: include/linux/sched.h:1108
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
```
In drivers/net/tun.c (0)
Location: include/linux/sched.h:1108
Inline: True
```
```
In drivers/usb/core/devio.c (ffffffff816bf36c)
Location: include/linux/sched.h:1108
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
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
In init/main.c (0)
Location: include/linux/sched.h:1108
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/sched.h:1108
Inline: True
```
```
In kernel/sys.c (ffffffff8109e45b)
Location: include/linux/sched.h:1108
Inline: True
Inline callers:
  - kernel/sys.c:propagate_has_child_subreaper
  - kernel/sys.c:sys_setsid
  - kernel/sys.c:SyS_setpgid
```
```
In kernel/pid.c (ffffffff810a9d09)
Location: include/linux/sched.h:1108
Inline: True
Inline callers:
  - kernel/pid.c:__task_pid_nr_ns
  - kernel/pid.c:pid_vnr
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:find_task_by_vpid
```
```
In kernel/time/posix-timers.c (ffffffff81113371)
Location: include/linux/sched.h:1108
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/sched.h:1108
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/sched.h:1108
Inline: True
```
```
In fs/notify/dnotify/dnotify.c (0)
Location: include/linux/sched.h:1108
Inline: True
```
```
In fs/locks.c (0)
Location: include/linux/sched.h:1108
Inline: True
```
```
In fs/proc/base.c (ffffffff812f2c2b)
Location: include/linux/sched.h:1108
Inline: True
Inline callers:
  - fs/proc/base.c:proc_flush_task
```
```
In fs/proc/array.c (ffffffff812f4cd9)
Location: include/linux/sched.h:1108
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
  - fs/proc/array.c:get_children_pid
```
```
In fs/fuse/dev.c (0)
Location: include/linux/sched.h:1108
Inline: True
```
```
In drivers/tty/tty_io.c (ffffffff815d69c0)
Location: include/linux/sched.h:1108
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:__tty_fasync
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff815e50a1)
Location: include/linux/sched.h:1108
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
```
In drivers/net/tun.c (0)
Location: include/linux/sched.h:1108
Inline: True
```
```
In drivers/usb/core/devio.c (ffffffff8172ad51)
Location: include/linux/sched.h:1108
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
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
In init/main.c (ffffffff826cd2a0)
Location: include/linux/sched.h:1200
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In kernel/exit.c (ffffffff81093b6f)
Location: include/linux/sched.h:1200
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
```
In kernel/sys.c (ffffffff810a2f3b)
Location: include/linux/sched.h:1200
Inline: True
Inline callers:
  - kernel/sys.c:propagate_has_child_subreaper
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
```
```
In kernel/pid.c (ffffffff810b0878)
Location: include/linux/sched.h:1200
Inline: True
Inline callers:
  - kernel/pid.c:__task_pid_nr_ns
  - kernel/pid.c:pid_vnr
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:find_task_by_vpid
```
```
In kernel/time/posix-timers.c (ffffffff8111f9aa)
Location: include/linux/sched.h:1200
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81120ff2)
Location: include/linux/sched.h:1200
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:check_clock
```
```
In fs/exec.c (ffffffff812a25da)
Location: include/linux/sched.h:1200
Inline: True
```
```
In fs/notify/dnotify/dnotify.c (ffffffff812e69d5)
Location: include/linux/sched.h:1200
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
```
```
In fs/locks.c (ffffffff812fda56)
Location: include/linux/sched.h:1200
Inline: True
Inline callers:
  - fs/locks.c:lease_setup
```
```
In fs/proc/base.c (ffffffff8131d8cc)
Location: include/linux/sched.h:1200
Inline: True
Inline callers:
  - fs/proc/base.c:next_tgid
  - fs/proc/base.c:proc_flush_task
```
```
In fs/proc/array.c (ffffffff8132123b)
Location: include/linux/sched.h:1200
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
  - fs/proc/array.c:get_children_pid
```
```
In fs/fuse/dev.c (ffffffff813c3ad4)
Location: include/linux/sched.h:1200
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
  - fs/fuse/dev.c:__fuse_get_req
```
```
In ipc/msg.c (ffffffff813d8364)
Location: include/linux/sched.h:1200
Inline: True
Inline callers:
  - ipc/msg.c:do_msgsnd
```
```
In drivers/tty/tty_io.c (ffffffff8160f9b9)
Location: include/linux/sched.h:1200
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:__tty_fasync
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff8161e8e8)
Location: include/linux/sched.h:1200
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
```
In drivers/net/tun.c (ffffffff8173bafc)
Location: include/linux/sched.h:1200
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_fasync
```
```
In drivers/usb/core/devio.c (ffffffff81769989)
Location: include/linux/sched.h:1200
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
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
In init/main.c (ffffffff82883276)
Location: include/linux/sched.h:1222
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In kernel/exit.c (ffffffff8109a432)
Location: include/linux/sched.h:1222
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
```
In kernel/sys.c (ffffffff810abb3b)
Location: include/linux/sched.h:1222
Inline: True
Inline callers:
  - kernel/sys.c:propagate_has_child_subreaper
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
```
```
In kernel/pid.c (ffffffff810b99aa)
Location: include/linux/sched.h:1222
Inline: True
Inline callers:
  - kernel/pid.c:__task_pid_nr_ns
  - kernel/pid.c:pid_vnr
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:find_task_by_vpid
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8112c712)
Location: include/linux/sched.h:1222
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:check_clock
```
```
In fs/exec.c (ffffffff812b71b9)
Location: include/linux/sched.h:1222
Inline: True
```
```
In fs/notify/dnotify/dnotify.c (ffffffff812fb56b)
Location: include/linux/sched.h:1222
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
```
```
In fs/notify/fanotify/fanotify.c (ffffffff812fcb8a)
Location: include/linux/sched.h:1222
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/locks.c (ffffffff81313466)
Location: include/linux/sched.h:1222
Inline: True
Inline callers:
  - fs/locks.c:lease_setup
```
```
In fs/proc/base.c (ffffffff8133465e)
Location: include/linux/sched.h:1222
Inline: True
Inline callers:
  - fs/proc/base.c:next_tgid
  - fs/proc/base.c:proc_flush_task
```
```
In fs/proc/array.c (ffffffff8133834b)
Location: include/linux/sched.h:1222
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
  - fs/proc/array.c:get_children_pid
```
```
In fs/fuse/dev.c (ffffffff813dd284)
Location: include/linux/sched.h:1222
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
  - fs/fuse/dev.c:__fuse_get_req
```
```
In ipc/msg.c (ffffffff813f2fd9)
Location: include/linux/sched.h:1222
Inline: True
Inline callers:
  - ipc/msg.c:do_msgsnd
```
```
In drivers/tty/tty_io.c (ffffffff8162c969)
Location: include/linux/sched.h:1222
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:__tty_fasync
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff8163bb48)
Location: include/linux/sched.h:1222
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
```
In drivers/net/tun.c (ffffffff8175f25c)
Location: include/linux/sched.h:1222
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_fasync
```
```
In drivers/usb/core/devio.c (ffffffff8178e014)
Location: include/linux/sched.h:1222
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
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
In init/main.c (ffffffff8289a2cc)
Location: include/linux/sched.h:1294
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In kernel/exit.c (ffffffff8109ef8b)
Location: include/linux/sched.h:1294
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:release_task
```
```
In kernel/signal.c (ffffffff810aff4f)
Location: include/linux/sched.h:1294
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_pidfd_send_signal
  - kernel/signal.c:__x64_sys_pidfd_send_signal
  - kernel/signal.c:do_notify_parent
```
```
In kernel/sys.c (ffffffff810b109b)
Location: include/linux/sched.h:1294
Inline: True
Inline callers:
  - kernel/sys.c:propagate_has_child_subreaper
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
```
```
In kernel/pid.c (ffffffff810bf7b2)
Location: include/linux/sched.h:1294
Inline: True
Inline callers:
  - kernel/pid.c:__task_pid_nr_ns
  - kernel/pid.c:pid_vnr
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:find_task_by_vpid
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811370b2)
Location: include/linux/sched.h:1294
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_create
  - kernel/time/posix-cpu-timers.c:check_clock
```
```
In fs/exec.c (ffffffff812d4bb2)
Location: include/linux/sched.h:1294
Inline: True
Inline callers:
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
```
```
In fs/notify/dnotify/dnotify.c (ffffffff8131be50)
Location: include/linux/sched.h:1294
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
```
```
In fs/notify/fanotify/fanotify.c (ffffffff8131d682)
Location: include/linux/sched.h:1294
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/locks.c (ffffffff8133ae06)
Location: include/linux/sched.h:1294
Inline: True
Inline callers:
  - fs/locks.c:lease_setup
```
```
In fs/proc/base.c (ffffffff8135cc2c)
Location: include/linux/sched.h:1294
Inline: True
Inline callers:
  - fs/proc/base.c:next_tgid
  - fs/proc/base.c:proc_flush_task
```
```
In fs/proc/array.c (ffffffff813609ff)
Location: include/linux/sched.h:1294
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
  - fs/proc/array.c:get_children_pid
```
```
In fs/fuse/dev.c (ffffffff81408db6)
Location: include/linux/sched.h:1294
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
  - fs/fuse/dev.c:__fuse_get_req
```
```
In ipc/msg.c (ffffffff8141eb3b)
Location: include/linux/sched.h:1294
Inline: True
Inline callers:
  - ipc/msg.c:do_msgsnd
```
```
In drivers/tty/tty_io.c (ffffffff816608bd)
Location: include/linux/sched.h:1294
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:__tty_fasync
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff8166face)
Location: include/linux/sched.h:1294
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
```
In drivers/net/tun.c (ffffffff8179ca8b)
Location: include/linux/sched.h:1294
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_fasync
```
```
In drivers/usb/core/devio.c (ffffffff817cc8a2)
Location: include/linux/sched.h:1294
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
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
In init/main.c (ffffffff8289d2b1)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In kernel/exit.c (ffffffff810a551b)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:release_task
```
```
In kernel/signal.c (ffffffff810b6560)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_pidfd_send_signal
  - kernel/signal.c:__x64_sys_pidfd_send_signal
  - kernel/signal.c:do_notify_parent
```
```
In kernel/sys.c (ffffffff810b776b)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - kernel/sys.c:propagate_has_child_subreaper
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
```
```
In kernel/pid.c (ffffffff810c5b84)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - kernel/pid.c:__task_pid_nr_ns
  - kernel/pid.c:pid_vnr
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:find_task_by_vpid
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811431ab)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:__get_task_for_clock
```
```
In fs/exec.c (ffffffff812e6732)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
```
```
In fs/notify/dnotify/dnotify.c (ffffffff8132ec49)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
```
```
In fs/notify/fanotify/fanotify.c (ffffffff813304c2)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/locks.c (ffffffff81353326)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - fs/locks.c:lease_setup
```
```
In fs/proc/base.c (ffffffff8137505c)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - fs/proc/base.c:next_tgid
  - fs/proc/base.c:proc_flush_task
```
```
In fs/proc/array.c (ffffffff81378c5f)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
  - fs/proc/array.c:get_children_pid
```
```
In fs/fuse/dev.c (ffffffff81422dd2)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
```
```
In ipc/msg.c (ffffffff8143898b)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - ipc/msg.c:do_msgsnd
```
```
In drivers/tty/tty_io.c (ffffffff81682f0d)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:__tty_fasync
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff8169212f)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
```
In drivers/net/tun.c (ffffffff817c053b)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_fasync
```
```
In drivers/usb/core/devio.c (ffffffff817fd53e)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
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
In init/main.c (ffffffff82cc38f9)
Location: include/linux/sched.h:1329
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In kernel/exit.c (ffffffff810ad31b)
Location: include/linux/sched.h:1329
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:forget_original_parent
  - kernel/exit.c:forget_original_parent
```
```
In kernel/signal.c (ffffffff810be770)
Location: include/linux/sched.h:1329
Inline: True
Inline callers:
  - kernel/signal.c:__do_sys_pidfd_send_signal
  - kernel/signal.c:do_notify_parent
```
```
In kernel/sys.c (ffffffff810bf6bb)
Location: include/linux/sched.h:1329
Inline: True
Inline callers:
  - kernel/sys.c:propagate_has_child_subreaper
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__do_sys_setpgid
```
```
In kernel/pid.c (ffffffff810cd40a)
Location: include/linux/sched.h:1329
Inline: True
Inline callers:
  - kernel/pid.c:__task_pid_nr_ns
  - kernel/pid.c:pid_vnr
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:find_get_task_by_vpid
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81152b52)
Location: include/linux/sched.h:1329
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_clock_getres
```
```
In fs/notify/dnotify/dnotify.c (ffffffff81368b19)
Location: include/linux/sched.h:1329
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
```
```
In fs/notify/fanotify/fanotify.c (ffffffff8136aa68)
Location: include/linux/sched.h:1329
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/locks.c (ffffffff81399766)
Location: include/linux/sched.h:1329
Inline: True
Inline callers:
  - fs/locks.c:lease_setup
```
```
In fs/proc/array.c (ffffffff813c1cd3)
Location: include/linux/sched.h:1329
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
  - fs/proc/array.c:get_children_pid
```
```
In fs/fuse/dev.c (ffffffff81472032)
Location: include/linux/sched.h:1329
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
```
```
In ipc/msg.c (ffffffff81488bdd)
Location: include/linux/sched.h:1329
Inline: True
Inline callers:
  - ipc/msg.c:do_msgsnd
```
```
In drivers/tty/tty_io.c (ffffffff81736ffb)
Location: include/linux/sched.h:1329
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_fasync
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff81744a2b)
Location: include/linux/sched.h:1329
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
```
In drivers/net/tun.c (ffffffff81889fcb)
Location: include/linux/sched.h:1329
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_fasync
```
```
In drivers/usb/core/devio.c (ffffffff818ccd4e)
Location: include/linux/sched.h:1329
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
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
In init/main.c (ffffffff82fafa06)
Location: include/linux/sched.h:1388
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In kernel/exit.c (ffffffff810a89eb)
Location: include/linux/sched.h:1388
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:forget_original_parent
  - kernel/exit.c:forget_original_parent
```
```
In kernel/signal.c (ffffffff810b9a70)
Location: include/linux/sched.h:1388
Inline: True
Inline callers:
  - kernel/signal.c:__do_sys_pidfd_send_signal
  - kernel/signal.c:do_notify_parent
```
```
In kernel/sys.c (ffffffff810ba86b)
Location: include/linux/sched.h:1388
Inline: True
Inline callers:
  - kernel/sys.c:propagate_has_child_subreaper
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__do_sys_setpgid
```
```
In kernel/pid.c (ffffffff810c7fb5)
Location: include/linux/sched.h:1388
Inline: True
Inline callers:
  - kernel/pid.c:__task_pid_nr_ns
  - kernel/pid.c:pid_vnr
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:find_get_task_by_vpid
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8114edc3)
Location: include/linux/sched.h:1388
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_clock_getres
```
```
In fs/notify/dnotify/dnotify.c (ffffffff81375e3a)
Location: include/linux/sched.h:1388
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
```
```
In fs/notify/fanotify/fanotify.c (ffffffff81377d00)
Location: include/linux/sched.h:1388
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/locks.c (ffffffff813ab246)
Location: include/linux/sched.h:1388
Inline: True
Inline callers:
  - fs/locks.c:lease_setup
```
```
In fs/proc/array.c (ffffffff813d3df3)
Location: include/linux/sched.h:1388
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
  - fs/proc/array.c:get_children_pid
```
```
In fs/fuse/dev.c (ffffffff8148c832)
Location: include/linux/sched.h:1388
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
```
```
In ipc/msg.c (ffffffff814a6225)
Location: include/linux/sched.h:1388
Inline: True
Inline callers:
  - ipc/msg.c:do_msgsnd
```
```
In drivers/tty/tty_io.c (ffffffff8175289b)
Location: include/linux/sched.h:1388
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_fasync
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff817610ec)
Location: include/linux/sched.h:1388
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_setactivate
  - drivers/tty/vt/vt_ioctl.c:vt_k_ioctl
```
```
In drivers/net/tun.c (ffffffff8189816b)
Location: include/linux/sched.h:1388
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_fasync
```
```
In drivers/usb/core/devio.c (ffffffff818d7f46)
Location: include/linux/sched.h:1388
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
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
In init/main.c (ffffffff831b9a33)
Location: include/linux/sched.h:1410
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In kernel/exit.c (ffffffff810a9855)
Location: include/linux/sched.h:1410
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:forget_original_parent
  - kernel/exit.c:forget_original_parent
```
```
In kernel/signal.c (ffffffff810bb260)
Location: include/linux/sched.h:1410
Inline: True
Inline callers:
  - kernel/signal.c:__do_sys_pidfd_send_signal
  - kernel/signal.c:do_notify_parent
```
```
In kernel/sys.c (ffffffff810bc19b)
Location: include/linux/sched.h:1410
Inline: True
Inline callers:
  - kernel/sys.c:propagate_has_child_subreaper
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__do_sys_setpgid
```
```
In kernel/pid.c (ffffffff810c9a55)
Location: include/linux/sched.h:1410
Inline: True
Inline callers:
  - kernel/pid.c:__task_pid_nr_ns
  - kernel/pid.c:pid_vnr
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:find_get_task_by_vpid
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81150253)
Location: include/linux/sched.h:1410
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_clock_getres
```
```
In fs/notify/dnotify/dnotify.c (ffffffff8137c7d8)
Location: include/linux/sched.h:1410
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
```
```
In fs/notify/fanotify/fanotify.c (ffffffff8137e7c4)
Location: include/linux/sched.h:1410
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/locks.c (ffffffff813b2716)
Location: include/linux/sched.h:1410
Inline: True
Inline callers:
  - fs/locks.c:lease_setup
```
```
In fs/proc/array.c (ffffffff813dac23)
Location: include/linux/sched.h:1410
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
  - fs/proc/array.c:get_children_pid
```
```
In fs/fuse/dev.c (ffffffff814921c8)
Location: include/linux/sched.h:1410
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
```
```
In ipc/msg.c (ffffffff814ac1ac)
Location: include/linux/sched.h:1410
Inline: True
Inline callers:
  - ipc/msg.c:do_msgsnd
```
```
In drivers/tty/tty_io.c (ffffffff817360db)
Location: include/linux/sched.h:1410
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_fasync
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff81744af8)
Location: include/linux/sched.h:1410
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_k_ioctl
```
```
In drivers/net/tun.c (ffffffff8187aa3b)
Location: include/linux/sched.h:1410
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_fasync
```
```
In drivers/usb/core/devio.c (ffffffff818bae39)
Location: include/linux/sched.h:1410
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
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
In init/main.c (ffffffff83299e0f)
Location: include/linux/sched.h:1508
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In kernel/exit.c (ffffffff810bb35a)
Location: include/linux/sched.h:1508
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:forget_original_parent
  - kernel/exit.c:forget_original_parent
```
```
In kernel/signal.c (ffffffff810cdb70)
Location: include/linux/sched.h:1508
Inline: True
Inline callers:
  - kernel/signal.c:__do_sys_pidfd_send_signal
  - kernel/signal.c:do_notify_parent
```
```
In kernel/sys.c (ffffffff810ceb8b)
Location: include/linux/sched.h:1508
Inline: True
Inline callers:
  - kernel/sys.c:propagate_has_child_subreaper
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__do_sys_setpgid
```
```
In kernel/pid.c (ffffffff810dc9c2)
Location: include/linux/sched.h:1508
Inline: True
Inline callers:
  - kernel/pid.c:__task_pid_nr_ns
  - kernel/pid.c:pid_vnr
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:find_get_task_by_vpid
```
```
In kernel/sched/core_sched.c (0)
Location: include/linux/sched.h:1508
Inline: True
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811744a3)
Location: include/linux/sched.h:1508
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_clock_getres
```
```
In fs/notify/dnotify/dnotify.c (ffffffff813c9677)
Location: include/linux/sched.h:1508
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
```
```
In fs/notify/fanotify/fanotify.c (ffffffff813cb8a4)
Location: include/linux/sched.h:1508
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/locks.c (ffffffff81402216)
Location: include/linux/sched.h:1508
Inline: True
Inline callers:
  - fs/locks.c:lease_setup
```
```
In fs/proc/array.c (ffffffff8142c3c3)
Location: include/linux/sched.h:1508
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
  - fs/proc/array.c:get_children_pid
```
```
In fs/fuse/dev.c (ffffffff814e9cc8)
Location: include/linux/sched.h:1508
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
```
```
In ipc/msg.c (ffffffff8150468f)
Location: include/linux/sched.h:1508
Inline: True
Inline callers:
  - ipc/msg.c:do_msgsnd
```
```
In drivers/tty/tty_io.c (ffffffff817b6a9b)
Location: include/linux/sched.h:1508
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_fasync
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff817c5948)
Location: include/linux/sched.h:1508
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_k_ioctl
```
```
In drivers/net/tun.c (ffffffff8190bf5b)
Location: include/linux/sched.h:1508
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_fasync
```
```
In drivers/usb/core/devio.c (ffffffff819515c5)
Location: include/linux/sched.h:1508
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff8344800e)
Location: include/linux/sched.h:1520
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In kernel/exit.c (ffffffff810d09d5)
Location: include/linux/sched.h:1520
Inline: True
Inline callers:
  - kernel/exit.c:child_wait_callback
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:forget_original_parent
  - kernel/exit.c:forget_original_parent
```
```
In kernel/signal.c (ffffffff810e5d1c)
Location: include/linux/sched.h:1520
Inline: True
Inline callers:
  - kernel/signal.c:__do_sys_pidfd_send_signal
  - kernel/signal.c:do_notify_parent
```
```
In kernel/sys.c (ffffffff810e6cfd)
Location: include/linux/sched.h:1520
Inline: True
Inline callers:
  - kernel/sys.c:propagate_has_child_subreaper
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__do_sys_setpgid
```
```
In kernel/pid.c (ffffffff810f7558)
Location: include/linux/sched.h:1520
Inline: True
Inline callers:
  - kernel/pid.c:__ia32_sys_pidfd_open
  - kernel/pid.c:__x64_sys_pidfd_open
  - kernel/pid.c:__task_pid_nr_ns
  - kernel/pid.c:pid_vnr
  - kernel/pid.c:find_get_task_by_vpid
```
```
In kernel/sched/build_utility.c (0)
Location: include/linux/sched.h:1520
Inline: True
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811a92ab)
Location: include/linux/sched.h:1520
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_clock_getres
```
```
In fs/notify/dnotify/dnotify.c (ffffffff81451063)
Location: include/linux/sched.h:1520
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
```
```
In fs/notify/fanotify/fanotify.c (ffffffff81453fdc)
Location: include/linux/sched.h:1520
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/locks.c (ffffffff81476a76)
Location: include/linux/sched.h:1520
Inline: True
Inline callers:
  - fs/locks.c:lease_setup
```
```
In fs/proc/array.c (ffffffff814a56ad)
Location: include/linux/sched.h:1520
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
  - fs/proc/array.c:get_children_pid
```
```
In fs/fuse/dev.c (ffffffff815784d0)
Location: include/linux/sched.h:1520
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
```
```
In ipc/msg.c (ffffffff81596506)
Location: include/linux/sched.h:1520
Inline: True
Inline callers:
  - ipc/msg.c:do_msgsnd
```
```
In drivers/tty/tty_io.c (ffffffff818f3b06)
Location: include/linux/sched.h:1520
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_fasync
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff8190281c)
Location: include/linux/sched.h:1520
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_k_ioctl
```
```
In drivers/net/tun.c (ffffffff81a5f7cf)
Location: include/linux/sched.h:1520
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_fasync
```
```
In drivers/usb/core/devio.c (ffffffff81aaa241)
Location: include/linux/sched.h:1520
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff83e61952)
Location: include/linux/sched.h:1542
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In kernel/exit.c (ffffffff810ef375)
Location: include/linux/sched.h:1542
Inline: True
Inline callers:
  - kernel/exit.c:child_wait_callback
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:forget_original_parent
  - kernel/exit.c:forget_original_parent
```
```
In kernel/signal.c (ffffffff811068bc)
Location: include/linux/sched.h:1542
Inline: True
Inline callers:
  - kernel/signal.c:__do_sys_pidfd_send_signal
  - kernel/signal.c:do_notify_parent
```
```
In kernel/sys.c (ffffffff8110789d)
Location: include/linux/sched.h:1542
Inline: True
Inline callers:
  - kernel/sys.c:propagate_has_child_subreaper
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__do_sys_setpgid
```
```
In kernel/pid.c (ffffffff81119cd8)
Location: include/linux/sched.h:1542
Inline: True
Inline callers:
  - kernel/pid.c:__ia32_sys_pidfd_open
  - kernel/pid.c:__x64_sys_pidfd_open
  - kernel/pid.c:__task_pid_nr_ns
  - kernel/pid.c:pid_vnr
  - kernel/pid.c:find_get_task_by_vpid
```
```
In kernel/sched/build_utility.c (0)
Location: include/linux/sched.h:1542
Inline: True
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811e911b)
Location: include/linux/sched.h:1542
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_clock_getres
```
```
In fs/notify/dnotify/dnotify.c (ffffffff814dfad3)
Location: include/linux/sched.h:1542
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
```
```
In fs/notify/fanotify/fanotify.c (ffffffff814e2e8c)
Location: include/linux/sched.h:1542
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/locks.c (ffffffff81509226)
Location: include/linux/sched.h:1542
Inline: True
Inline callers:
  - fs/locks.c:lease_setup
```
```
In fs/proc/array.c (ffffffff8153ac8d)
Location: include/linux/sched.h:1542
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
  - fs/proc/array.c:get_children_pid
```
```
In fs/fuse/dev.c (ffffffff8161da06)
Location: include/linux/sched.h:1542
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
```
```
In ipc/msg.c (ffffffff8163f3c8)
Location: include/linux/sched.h:1542
Inline: True
Inline callers:
  - ipc/msg.c:do_msgsnd
```
```
In drivers/tty/tty_io.c (ffffffff81a4b85e)
Location: include/linux/sched.h:1542
Inline: True
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff81a5c7ec)
Location: include/linux/sched.h:1542
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_k_ioctl
```
```
In drivers/net/tun.c (ffffffff81beac4f)
Location: include/linux/sched.h:1542
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_fasync
```
```
In drivers/usb/core/devio.c (ffffffff81c315c1)
Location: include/linux/sched.h:1542
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff83681d72)
Location: include/linux/sched.h:1551
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In kernel/exit.c (ffffffff810fb395)
Location: include/linux/sched.h:1551
Inline: True
Inline callers:
  - kernel/exit.c:child_wait_callback
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:forget_original_parent
  - kernel/exit.c:forget_original_parent
```
```
In kernel/signal.c (ffffffff81112bac)
Location: include/linux/sched.h:1551
Inline: True
Inline callers:
  - kernel/signal.c:__do_sys_pidfd_send_signal
  - kernel/signal.c:do_notify_parent
```
```
In kernel/sys.c (ffffffff81113b8d)
Location: include/linux/sched.h:1551
Inline: True
Inline callers:
  - kernel/sys.c:propagate_has_child_subreaper
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__do_sys_setpgid
```
```
In kernel/pid.c (ffffffff81125de9)
Location: include/linux/sched.h:1551
Inline: True
Inline callers:
  - kernel/pid.c:__ia32_sys_pidfd_open
  - kernel/pid.c:__x64_sys_pidfd_open
  - kernel/pid.c:__task_pid_nr_ns
  - kernel/pid.c:pid_vnr
  - kernel/pid.c:find_get_task_by_vpid
```
```
In kernel/sched/build_utility.c (0)
Location: include/linux/sched.h:1551
Inline: True
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811fd70b)
Location: include/linux/sched.h:1551
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_clock_getres
```
```
In fs/notify/dnotify/dnotify.c (ffffffff81516357)
Location: include/linux/sched.h:1551
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
```
```
In fs/notify/fanotify/fanotify.c (ffffffff81519680)
Location: include/linux/sched.h:1551
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/locks.c (ffffffff815407e6)
Location: include/linux/sched.h:1551
Inline: True
Inline callers:
  - fs/locks.c:lease_setup
```
```
In fs/proc/array.c (ffffffff81572f8b)
Location: include/linux/sched.h:1551
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
  - fs/proc/array.c:get_children_pid
```
```
In fs/fuse/dev.c (ffffffff81655b33)
Location: include/linux/sched.h:1551
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
```
```
In ipc/msg.c (ffffffff816778f8)
Location: include/linux/sched.h:1551
Inline: True
Inline callers:
  - ipc/msg.c:do_msgsnd
```
```
In drivers/tty/tty_io.c (ffffffff81a95a61)
Location: include/linux/sched.h:1551
Inline: True
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff81aa7321)
Location: include/linux/sched.h:1551
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_k_ioctl
```
```
In drivers/net/tun.c (ffffffff81c43099)
Location: include/linux/sched.h:1551
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_fasync
```
```
In drivers/usb/core/devio.c (ffffffff81c9884f)
Location: include/linux/sched.h:1551
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff838b0da2)
Location: include/linux/pid.h:210
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In kernel/exit.c (ffffffff81104cc5)
Location: include/linux/pid.h:210
Inline: True
Inline callers:
  - kernel/exit.c:child_wait_callback
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:forget_original_parent
  - kernel/exit.c:forget_original_parent
```
```
In kernel/signal.c (ffffffff8111c59c)
Location: include/linux/pid.h:210
Inline: True
Inline callers:
  - kernel/signal.c:__do_sys_pidfd_send_signal
  - kernel/signal.c:do_notify_parent
```
```
In kernel/sys.c (ffffffff8111d57d)
Location: include/linux/pid.h:210
Inline: True
Inline callers:
  - kernel/sys.c:propagate_has_child_subreaper
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__do_sys_setpgid
```
```
In kernel/pid.c (ffffffff811303e9)
Location: include/linux/pid.h:210
Inline: True
Inline callers:
  - kernel/pid.c:__ia32_sys_pidfd_open
  - kernel/pid.c:__x64_sys_pidfd_open
  - kernel/pid.c:__task_pid_nr_ns
  - kernel/pid.c:pid_vnr
  - kernel/pid.c:find_get_task_by_vpid
```
```
In kernel/sched/build_utility.c (0)
Location: include/linux/pid.h:210
Inline: True
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8121390b)
Location: include/linux/pid.h:210
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:thread_cpu_clock_getres
```
```
In fs/notify/dnotify/dnotify.c (ffffffff8154a661)
Location: include/linux/pid.h:210
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
```
```
In fs/notify/fanotify/fanotify.c (ffffffff8154da60)
Location: include/linux/pid.h:210
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/locks.c (ffffffff81575cc6)
Location: include/linux/pid.h:210
Inline: True
Inline callers:
  - fs/locks.c:lease_setup
```
```
In fs/proc/array.c (ffffffff815abebb)
Location: include/linux/pid.h:210
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
  - fs/proc/array.c:get_children_pid
```
```
In fs/fuse/dev.c (ffffffff8168f293)
Location: include/linux/pid.h:210
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
```
```
In ipc/msg.c (ffffffff816b3cb8)
Location: include/linux/pid.h:210
Inline: True
Inline callers:
  - ipc/msg.c:do_msgsnd
```
```
In drivers/tty/tty_io.c (ffffffff81ae84c1)
Location: include/linux/pid.h:210
Inline: True
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff81af9db1)
Location: include/linux/pid.h:210
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_k_ioctl
```
```
In drivers/net/tun.c (ffffffff81cf8bc9)
Location: include/linux/pid.h:210
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_fasync
```
```
In drivers/usb/core/devio.c (ffffffff81d4d38e)
Location: include/linux/pid.h:210
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
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
In init/main.c (ffff800011431284)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In virt/kvm/kvm_main.c (ffff8000100b9294)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - virt/kvm/kvm_main.c:kvm_vcpu_ioctl
```
```
In kernel/exit.c (ffff8000100fb4d0)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:release_task
```
```
In kernel/signal.c (ffff8000101128dc)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - kernel/signal.c:__arm64_sys_pidfd_send_signal
  - kernel/signal.c:do_notify_parent
```
```
In kernel/sys.c (ffff8000101140b8)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - kernel/sys.c:propagate_has_child_subreaper
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__arm64_sys_setpgid
```
```
In kernel/pid.c (ffff8000101240b0)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - kernel/pid.c:__task_pid_nr_ns
  - kernel/pid.c:pid_vnr
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:find_task_by_vpid
```
```
In kernel/time/posix-cpu-timers.c (ffff8000101ad278)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:__get_task_for_clock
```
```
In fs/exec.c (ffff80001038ea34)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
```
```
In fs/notify/dnotify/dnotify.c (ffff8000103eb69c)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
```
```
In fs/notify/fanotify/fanotify.c (ffff8000103ed710)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/locks.c (ffff800010414e34)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - fs/locks.c:lease_setup
```
```
In fs/proc/base.c (ffff80001043e974)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - fs/proc/base.c:next_tgid
  - fs/proc/base.c:proc_flush_task
```
```
In fs/proc/array.c (ffff800010444ba4)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
  - fs/proc/array.c:get_children_pid
```
```
In fs/fuse/dev.c (ffff800010505bc0)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
```
```
In ipc/msg.c (ffff80001051f614)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - ipc/msg.c:do_msgsnd
```
```
In drivers/tty/tty_io.c (ffff80001085106c)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:__tty_fasync
```
```
In drivers/tty/vt/vt_ioctl.c (ffff800010866008)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
```
In drivers/net/tun.c (ffff8000109dac08)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_fasync
```
```
In drivers/usb/core/devio.c (ffff800010a2e98c)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
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
In init/main.c (c15012ac)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In kernel/exit.c (c0359474)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:release_task
```
```
In kernel/signal.c (c0369840)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - kernel/signal.c:__se_sys_pidfd_send_signal
  - kernel/signal.c:do_notify_parent
```
```
In kernel/sys.c (c036ab28)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - kernel/sys.c:propagate_has_child_subreaper
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__se_sys_setpgid
```
```
In kernel/pid.c (c03773ec)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - kernel/pid.c:__task_pid_nr_ns
  - kernel/pid.c:pid_vnr
  - kernel/pid.c:find_task_by_vpid
  - kernel/pid.c:find_vpid
```
```
In kernel/time/posix-cpu-timers.c (c03f8218)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:__get_task_for_clock
```
```
In fs/exec.c (c0574f9c)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
```
```
In fs/notify/dnotify/dnotify.c (c05c264c)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
```
```
In fs/notify/fanotify/fanotify.c (c05c3f78)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/locks.c (c05e1a7c)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - fs/locks.c:lease_setup
```
```
In fs/proc/base.c (c0605b84)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - fs/proc/base.c:next_tgid
  - fs/proc/base.c:proc_flush_task
```
```
In fs/proc/array.c (c0609fe8)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
  - fs/proc/array.c:get_children_pid
```
```
In fs/fuse/dev.c (c06c21d0)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
```
```
In ipc/msg.c (c06dbbd8)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - ipc/msg.c:do_msgsnd
```
```
In drivers/tty/tty_io.c (c095b37c)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:__tty_fasync
```
```
In drivers/tty/vt/vt_ioctl.c (c096c1bc)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
```
In drivers/net/tun.c (c0ac169c)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_fasync
```
```
In drivers/usb/core/devio.c (c0b04668)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
```
```
In sound/core/control.c (c0c85d50)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - sound/core/control.c:snd_ctl_get_preferred_subdevice
```
```
In sound/core/pcm.c (c0c90b18)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - sound/core/pcm.c:snd_pcm_attach_substream
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
In init/main.c (c000000001344530)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In kernel/exit.c (c000000000142930)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:release_task
```
```
In kernel/signal.c (c00000000015a308)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - kernel/signal.c:__se_sys_pidfd_send_signal
  - kernel/signal.c:do_notify_parent
```
```
In kernel/sys.c (c00000000015b9a8)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - kernel/sys.c:propagate_has_child_subreaper
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__se_sys_setpgid
```
```
In kernel/pid.c (c00000000016de04)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - kernel/pid.c:__task_pid_nr_ns
  - kernel/pid.c:pid_vnr
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:find_task_by_vpid
```
```
In kernel/time/posix-cpu-timers.c (c0000000002114f0)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:__get_task_for_clock
```
```
In fs/exec.c (c000000000485964)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
```
```
In fs/notify/dnotify/dnotify.c (c0000000004f2a44)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
```
```
In fs/notify/fanotify/fanotify.c (c0000000004f4e04)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/locks.c (c000000000524340)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - fs/locks.c:lease_setup
```
```
In fs/proc/base.c (c0000000005544c0)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - fs/proc/base.c:next_tgid
  - fs/proc/base.c:proc_flush_task
```
```
In fs/proc/array.c (c00000000055a9a0)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
  - fs/proc/array.c:get_children_pid
```
```
In fs/fuse/dev.c (c00000000064b404)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
```
```
In ipc/msg.c (c000000000668ffc)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - ipc/msg.c:do_msgsnd
```
```
In drivers/tty/tty_io.c (c0000000008ee674)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:__tty_fasync
```
```
In drivers/tty/vt/vt_ioctl.c (c000000000905f20)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
```
In drivers/net/tun.c (c000000000a9cbd4)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_fasync
```
```
In drivers/usb/core/devio.c (c000000000aedb64)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
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
In init/main.c (ffffffe000000fd4)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In kernel/exit.c (ffffffe0000c50c8)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:release_task
```
```
In kernel/signal.c (ffffffe0000d17dc)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - kernel/signal.c:__se_sys_pidfd_send_signal
  - kernel/signal.c:do_notify_parent
```
```
In kernel/sys.c (ffffffe0000d1f80)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - kernel/sys.c:propagate_has_child_subreaper
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__se_sys_setpgid
```
```
In kernel/pid.c (ffffffe0000dc3da)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - kernel/pid.c:__task_pid_nr_ns
  - kernel/pid.c:pid_vnr
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:find_task_by_vpid
```
```
In kernel/time/posix-cpu-timers.c (ffffffe0001372de)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:__get_task_for_clock
```
```
In fs/exec.c (ffffffe00025e506)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
```
```
In fs/notify/dnotify/dnotify.c (ffffffe00029fa2a)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
```
```
In fs/notify/fanotify/fanotify.c (ffffffe0002a113c)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/locks.c (ffffffe0002bca36)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - fs/locks.c:lease_setup
```
```
In fs/proc/base.c (ffffffe0002d6476)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - fs/proc/base.c:next_tgid
  - fs/proc/base.c:proc_flush_task
```
```
In fs/proc/array.c (ffffffe0002dabb8)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
  - fs/proc/array.c:get_children_pid
```
```
In fs/fuse/dev.c (ffffffe0003724d2)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
```
```
In ipc/msg.c (ffffffe0003863c2)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - ipc/msg.c:do_msgsnd
```
```
In drivers/tty/tty_io.c (ffffffe00052d792)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:__tty_fasync
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffe00053c3e4)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
```
In drivers/net/tun.c (ffffffe0006258e4)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_fasync
```
```
In drivers/usb/core/devio.c (ffffffe00064ec90)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
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
In init/main.c (ffffffff8288b2b1)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In kernel/exit.c (ffffffff8109ee3b)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:release_task
```
```
In kernel/signal.c (ffffffff810b08d0)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_pidfd_send_signal
  - kernel/signal.c:__x64_sys_pidfd_send_signal
  - kernel/signal.c:do_notify_parent
```
```
In kernel/sys.c (ffffffff810b1adb)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - kernel/sys.c:propagate_has_child_subreaper
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
```
```
In kernel/pid.c (ffffffff810bff04)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - kernel/pid.c:__task_pid_nr_ns
  - kernel/pid.c:pid_vnr
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:find_task_by_vpid
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8113b95b)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:__get_task_for_clock
```
```
In fs/exec.c (ffffffff812ded12)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
```
```
In fs/notify/dnotify/dnotify.c (ffffffff81327229)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
```
```
In fs/notify/fanotify/fanotify.c (ffffffff81328aa2)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/locks.c (ffffffff8134b906)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - fs/locks.c:lease_setup
```
```
In fs/proc/base.c (ffffffff8136d63c)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - fs/proc/base.c:next_tgid
  - fs/proc/base.c:proc_flush_task
```
```
In fs/proc/array.c (ffffffff8137123f)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
  - fs/proc/array.c:get_children_pid
```
```
In fs/fuse/dev.c (ffffffff8141b3b2)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
```
```
In ipc/msg.c (ffffffff81430f6b)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - ipc/msg.c:do_msgsnd
```
```
In drivers/tty/tty_io.c (ffffffff8164898d)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:__tty_fasync
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff81657baf)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
```
In drivers/net/tun.c (ffffffff8178500b)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_fasync
```
```
In drivers/usb/core/devio.c (ffffffff817b591e)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
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
In init/main.c (ffffffff8288922e)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In kernel/exit.c (ffffffff8108d87b)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:release_task
```
```
In kernel/signal.c (ffffffff8109f1f0)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_pidfd_send_signal
  - kernel/signal.c:__x64_sys_pidfd_send_signal
  - kernel/signal.c:do_notify_parent
```
```
In kernel/sys.c (ffffffff810a03fb)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - kernel/sys.c:propagate_has_child_subreaper
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
```
```
In kernel/pid.c (ffffffff810ae714)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - kernel/pid.c:__task_pid_nr_ns
  - kernel/pid.c:pid_vnr
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:find_task_by_vpid
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8112e31b)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:__get_task_for_clock
```
```
In fs/exec.c (ffffffff812cee37)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
```
```
In fs/notify/dnotify/dnotify.c (ffffffff81317dc9)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
```
```
In fs/notify/fanotify/fanotify.c (ffffffff81319642)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/locks.c (ffffffff8133c5e6)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - fs/locks.c:lease_setup
```
```
In fs/proc/base.c (ffffffff8135e0cc)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - fs/proc/base.c:next_tgid
  - fs/proc/base.c:proc_flush_task
```
```
In fs/proc/array.c (ffffffff81361ccf)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
  - fs/proc/array.c:get_children_pid
```
```
In fs/fuse/dev.c (ffffffff8140be32)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
```
```
In ipc/msg.c (ffffffff814219eb)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - ipc/msg.c:do_msgsnd
```
```
In drivers/tty/tty_io.c (ffffffff81628ded)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:__tty_fasync
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff81637f3f)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
```
In drivers/net/tun.c (ffffffff8176495b)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_fasync
```
```
In drivers/usb/core/devio.c (ffffffff817a734e)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
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
In init/main.c (ffffffff8289e2b1)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In kernel/exit.c (ffffffff8109edeb)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:release_task
```
```
In kernel/signal.c (ffffffff810afe30)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_pidfd_send_signal
  - kernel/signal.c:__x64_sys_pidfd_send_signal
  - kernel/signal.c:do_notify_parent
```
```
In kernel/sys.c (ffffffff810b103b)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - kernel/sys.c:propagate_has_child_subreaper
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
```
```
In kernel/pid.c (ffffffff810bf454)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - kernel/pid.c:__task_pid_nr_ns
  - kernel/pid.c:pid_vnr
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:find_task_by_vpid
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8113967b)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:__get_task_for_clock
```
```
In fs/exec.c (ffffffff812dcb22)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
```
```
In fs/notify/dnotify/dnotify.c (ffffffff81324cf9)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
```
```
In fs/notify/fanotify/fanotify.c (ffffffff81326572)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/locks.c (ffffffff813493d6)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - fs/locks.c:lease_setup
```
```
In fs/proc/base.c (ffffffff8136b10c)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - fs/proc/base.c:next_tgid
  - fs/proc/base.c:proc_flush_task
```
```
In fs/proc/array.c (ffffffff8136ed0f)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
  - fs/proc/array.c:get_children_pid
```
```
In fs/fuse/dev.c (ffffffff81417552)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
```
```
In ipc/msg.c (ffffffff8142d10b)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - ipc/msg.c:do_msgsnd
```
```
In drivers/tty/tty_io.c (ffffffff81676d4d)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:__tty_fasync
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff81685f6f)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
```
In drivers/net/tun.c (ffffffff817b53bb)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_fasync
```
```
In drivers/usb/core/devio.c (ffffffff817f23be)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
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
In init/main.c (ffffffff8289e2b6)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In kernel/exit.c (ffffffff810a6d2b)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:release_task
```
```
In kernel/signal.c (ffffffff810b8100)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_pidfd_send_signal
  - kernel/signal.c:__x64_sys_pidfd_send_signal
  - kernel/signal.c:do_notify_parent
```
```
In kernel/sys.c (ffffffff810b932b)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - kernel/sys.c:propagate_has_child_subreaper
  - kernel/sys.c:ksys_setsid
  - kernel/sys.c:__ia32_sys_setpgid
  - kernel/sys.c:__x64_sys_setpgid
```
```
In kernel/pid.c (ffffffff810c78d2)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - kernel/pid.c:__task_pid_nr_ns
  - kernel/pid.c:pid_vnr
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:find_task_by_vpid
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81146129)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:__get_task_for_clock
```
```
In fs/exec.c (ffffffff812ed8cb)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
```
```
In fs/notify/dnotify/dnotify.c (ffffffff81336a5e)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
```
```
In fs/notify/fanotify/fanotify.c (ffffffff81338392)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/locks.c (ffffffff8135c8b6)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - fs/locks.c:lease_setup
```
```
In fs/proc/base.c (ffffffff8137e953)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - fs/proc/base.c:next_tgid
  - fs/proc/base.c:proc_flush_task
```
```
In fs/proc/array.c (ffffffff8138269e)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
  - fs/proc/array.c:get_children_pid
```
```
In fs/fuse/dev.c (ffffffff8142e2e0)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
```
```
In ipc/msg.c (ffffffff81444fbf)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - ipc/msg.c:do_msgsnd
```
```
In drivers/tty/tty_io.c (ffffffff8169146d)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:__tty_fasync
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff816a056f)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
```
In drivers/net/tun.c (ffffffff817cf3ab)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_fasync
```
```
In drivers/usb/core/devio.c (ffffffff8180c5fe)
Location: include/linux/sched.h:1288
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
```
</details>
</li>
</ul>

## Differences
