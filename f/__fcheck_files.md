# Function: <code>__fcheck_files</code>

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
In kernel/kcmp.c (ffffffff810e973f)
Location: include/linux/fdtable.h:80
Inline: True
Inline callers:
  - kernel/kcmp.c:get_file_raw_ptr
```
```
In fs/file.c (ffffffff81229c26)
Location: include/linux/fdtable.h:80
Inline: True
Inline callers:
  - fs/file.c:__fget
  - fs/file.c:SyS_dup2
  - fs/file.c:SyS_dup2
```
```
In fs/notify/dnotify/dnotify.c (ffffffff8125153a)
Location: include/linux/fdtable.h:80
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
```
```
In fs/locks.c (ffffffff81262d2d)
Location: include/linux/fdtable.h:80
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
```
```
In fs/proc/fd.c (ffffffff812815b6)
Location: include/linux/fdtable.h:80
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_fd_link
  - fs/proc/fd.c:seq_show
  - fs/proc/fd.c:tid_fd_revalidate
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
In kernel/kcmp.c (ffffffff810f049f)
Location: include/linux/fdtable.h:80
Inline: True
Inline callers:
  - kernel/kcmp.c:get_file_raw_ptr
```
```
In fs/file.c (ffffffff81253644)
Location: include/linux/fdtable.h:80
Inline: True
Inline callers:
  - fs/file.c:SyS_dup2
  - fs/file.c:SyS_dup2
  - fs/file.c:__fget
```
```
In fs/notify/dnotify/dnotify.c (ffffffff81279d38)
Location: include/linux/fdtable.h:80
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
```
```
In fs/locks.c (ffffffff8128efdc)
Location: include/linux/fdtable.h:80
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
```
```
In fs/proc/fd.c (ffffffff812ae675)
Location: include/linux/fdtable.h:80
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_fd_link
  - fs/proc/fd.c:tid_fd_revalidate
  - fs/proc/fd.c:seq_show
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
In kernel/kcmp.c (ffffffff810f75ff)
Location: include/linux/fdtable.h:80
Inline: True
Inline callers:
  - kernel/kcmp.c:get_file_raw_ptr
```
```
In fs/file.c (ffffffff81266894)
Location: include/linux/fdtable.h:80
Inline: True
Inline callers:
  - fs/file.c:SyS_dup2
  - fs/file.c:SyS_dup2
  - fs/file.c:__fget
```
```
In fs/notify/dnotify/dnotify.c (ffffffff8128d8e8)
Location: include/linux/fdtable.h:80
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
```
```
In fs/locks.c (ffffffff812a3f90)
Location: include/linux/fdtable.h:80
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
```
```
In fs/proc/fd.c (ffffffff812c4055)
Location: include/linux/fdtable.h:80
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_fd_link
  - fs/proc/fd.c:tid_fd_revalidate
  - fs/proc/fd.c:seq_show
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
In kernel/kcmp.c (ffffffff810f9756)
Location: include/linux/fdtable.h:80
Inline: True
Inline callers:
  - kernel/kcmp.c:SyS_kcmp
  - kernel/kcmp.c:get_file_raw_ptr
```
```
In fs/file.c (ffffffff8127407b)
Location: include/linux/fdtable.h:80
Inline: True
Inline callers:
  - fs/file.c:SyS_dup2
  - fs/file.c:SyS_dup2
  - fs/file.c:__fget
```
```
In fs/notify/dnotify/dnotify.c (ffffffff8129a82f)
Location: include/linux/fdtable.h:80
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
```
```
In fs/locks.c (ffffffff812b2bbc)
Location: include/linux/fdtable.h:80
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
```
```
In fs/proc/fd.c (ffffffff812d1464)
Location: include/linux/fdtable.h:80
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_fd_link
  - fs/proc/fd.c:tid_fd_revalidate
  - fs/proc/fd.c:seq_show
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
In kernel/kcmp.c (ffffffff811041db)
Location: include/linux/fdtable.h:82
Inline: True
Inline callers:
  - kernel/kcmp.c:SyS_kcmp
  - kernel/kcmp.c:get_file_raw_ptr
```
```
In fs/file.c (ffffffff8129695c)
Location: include/linux/fdtable.h:82
Inline: True
Inline callers:
  - fs/file.c:SyS_dup2
  - fs/file.c:SyS_dup2
  - fs/file.c:__fget
```
```
In fs/notify/dnotify/dnotify.c (ffffffff812bdc0f)
Location: include/linux/fdtable.h:82
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
```
```
In fs/locks.c (ffffffff812d6652)
Location: include/linux/fdtable.h:82
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
```
```
In fs/proc/fd.c (ffffffff812f5c54)
Location: include/linux/fdtable.h:82
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_fd_link
  - fs/proc/fd.c:tid_fd_revalidate
  - fs/proc/fd.c:seq_show
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
In kernel/kcmp.c (ffffffff8110e9cb)
Location: include/linux/fdtable.h:82
Inline: True
Inline callers:
  - kernel/kcmp.c:kcmp_epoll_target
  - kernel/kcmp.c:get_file_raw_ptr
```
```
In kernel/bpf/syscall.c (ffffffff811b38e1)
Location: include/linux/fdtable.h:82
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_task_fd_query
```
```
In fs/file.c (ffffffff812bc100)
Location: include/linux/fdtable.h:82
Inline: True
Inline callers:
  - fs/file.c:__ia32_sys_dup2
  - fs/file.c:__x64_sys_dup2
  - fs/file.c:ksys_dup3
  - fs/file.c:__fget
```
```
In fs/notify/dnotify/dnotify.c (ffffffff812e68a9)
Location: include/linux/fdtable.h:82
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
```
```
In fs/locks.c (ffffffff8130120d)
Location: include/linux/fdtable.h:82
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
```
```
In fs/proc/fd.c (ffffffff813234d4)
Location: include/linux/fdtable.h:82
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_fd_link
  - fs/proc/fd.c:tid_fd_mode
  - fs/proc/fd.c:seq_show
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
In kernel/kcmp.c (ffffffff81119f4b)
Location: include/linux/fdtable.h:82
Inline: True
Inline callers:
  - kernel/kcmp.c:kcmp_epoll_target
  - kernel/kcmp.c:get_file_raw_ptr
```
```
In kernel/bpf/syscall.c (ffffffff811c456e)
Location: include/linux/fdtable.h:82
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
```
In fs/file.c (ffffffff812d12f0)
Location: include/linux/fdtable.h:82
Inline: True
Inline callers:
  - fs/file.c:__ia32_sys_dup2
  - fs/file.c:__x64_sys_dup2
  - fs/file.c:ksys_dup3
  - fs/file.c:__fget
```
```
In fs/notify/dnotify/dnotify.c (ffffffff812fb43c)
Location: include/linux/fdtable.h:82
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
```
```
In fs/locks.c (ffffffff81316cfb)
Location: include/linux/fdtable.h:82
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
```
```
In fs/proc/fd.c (ffffffff8133a3f4)
Location: include/linux/fdtable.h:82
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_fd_link
  - fs/proc/fd.c:tid_fd_mode
  - fs/proc/fd.c:seq_show
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
In kernel/kcmp.c (ffffffff81124bc9)
Location: include/linux/fdtable.h:82
Inline: True
Inline callers:
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:get_file_raw_ptr
```
```
In kernel/bpf/syscall.c (ffffffff811d60bd)
Location: include/linux/fdtable.h:82
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
```
In fs/file.c (ffffffff812ee310)
Location: include/linux/fdtable.h:82
Inline: True
Inline callers:
  - fs/file.c:__ia32_sys_dup2
  - fs/file.c:__x64_sys_dup2
  - fs/file.c:ksys_dup3
  - fs/file.c:__fget
```
```
In fs/notify/dnotify/dnotify.c (ffffffff8131bd23)
Location: include/linux/fdtable.h:82
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
```
```
In fs/locks.c (ffffffff8133e58b)
Location: include/linux/fdtable.h:82
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
```
```
In fs/proc/fd.c (ffffffff81362594)
Location: include/linux/fdtable.h:82
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_fd_link
  - fs/proc/fd.c:tid_fd_mode
  - fs/proc/fd.c:seq_show
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
In kernel/kcmp.c (ffffffff81130b89)
Location: include/linux/fdtable.h:82
Inline: True
Inline callers:
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:get_file_raw_ptr
```
```
In kernel/bpf/syscall.c (ffffffff811e2063)
Location: include/linux/fdtable.h:82
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
```
In fs/file.c (ffffffff812ffdd0)
Location: include/linux/fdtable.h:82
Inline: True
Inline callers:
  - fs/file.c:__ia32_sys_dup2
  - fs/file.c:__x64_sys_dup2
  - fs/file.c:ksys_dup3
  - fs/file.c:__fget
```
```
In fs/notify/dnotify/dnotify.c (ffffffff8132eb0c)
Location: include/linux/fdtable.h:82
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
```
```
In fs/locks.c (ffffffff81356b7b)
Location: include/linux/fdtable.h:82
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
```
```
In fs/proc/fd.c (ffffffff8137a7f4)
Location: include/linux/fdtable.h:82
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_fd_link
  - fs/proc/fd.c:tid_fd_mode
  - fs/proc/fd.c:seq_show
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
In kernel/kcmp.c (ffffffff8113fc1a)
Location: include/linux/fdtable.h:82
Inline: True
Inline callers:
  - kernel/kcmp.c:kcmp_epoll_target
  - kernel/kcmp.c:get_file_raw_ptr
```
```
In kernel/bpf/syscall.c (ffffffff811fc75b)
Location: include/linux/fdtable.h:82
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_task_fd_query
```
```
In kernel/bpf/task_iter.c (ffffffff812166cc)
Location: include/linux/fdtable.h:82
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:task_file_seq_get_next
```
```
In fs/file.c (ffffffff81338f14)
Location: include/linux/fdtable.h:82
Inline: True
Inline callers:
  - fs/file.c:__ia32_sys_dup2
  - fs/file.c:__x64_sys_dup2
  - fs/file.c:ksys_dup3
  - fs/file.c:__fget_files
```
```
In fs/notify/dnotify/dnotify.c (ffffffff813689e5)
Location: include/linux/fdtable.h:82
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
```
```
In fs/io_uring.c (ffffffff8137fdf0)
Location: include/linux/fdtable.h:82
Inline: True
Inline callers:
  - fs/io_uring.c:io_grab_files
```
```
In fs/locks.c (ffffffff8139df40)
Location: include/linux/fdtable.h:82
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
```
```
In fs/proc/fd.c (ffffffff813c3bfb)
Location: include/linux/fdtable.h:82
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_fd_link
  - fs/proc/fd.c:tid_fd_mode
  - fs/proc/fd.c:seq_show
```
</details>
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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In kernel/kcmp.c (ffff800010197acc)
Location: include/linux/fdtable.h:82
Inline: True
Inline callers:
  - kernel/kcmp.c:kcmp_epoll_target
  - kernel/kcmp.c:get_file_raw_ptr
```
```
In kernel/bpf/syscall.c (ffff80001026579c)
Location: include/linux/fdtable.h:82
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
```
In fs/file.c (ffff8000103b195c)
Location: include/linux/fdtable.h:82
Inline: True
Inline callers:
  - fs/file.c:__arm64_sys_dup2
  - fs/file.c:ksys_dup3
  - fs/file.c:__fget
```
```
In fs/notify/dnotify/dnotify.c (ffff8000103eb51c)
Location: include/linux/fdtable.h:82
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
```
```
In fs/locks.c (ffff800010419688)
Location: include/linux/fdtable.h:82
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
```
```
In fs/proc/fd.c (ffff800010446ac0)
Location: include/linux/fdtable.h:82
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_fd_link
  - fs/proc/fd.c:tid_fd_mode
  - fs/proc/fd.c:seq_show
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
In kernel/kcmp.c (c03e2de8)
Location: include/linux/fdtable.h:82
Inline: True
Inline callers:
  - kernel/kcmp.c:__se_sys_kcmp
  - kernel/kcmp.c:get_file_raw_ptr
```
```
In kernel/bpf/syscall.c (c0493984)
Location: include/linux/fdtable.h:82
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_task_fd_query
```
```
In fs/file.c (c0591b94)
Location: include/linux/fdtable.h:82
Inline: True
Inline callers:
  - fs/file.c:__se_sys_dup2
  - fs/file.c:ksys_dup3
  - fs/file.c:__fget
```
```
In fs/notify/dnotify/dnotify.c (c05c2528)
Location: include/linux/fdtable.h:82
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
```
```
In fs/locks.c (c05e5b90)
Location: include/linux/fdtable.h:82
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk64
  - fs/locks.c:fcntl_setlk
```
```
In fs/proc/fd.c (c060bc98)
Location: include/linux/fdtable.h:82
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_fd_link
  - fs/proc/fd.c:tid_fd_mode
  - fs/proc/fd.c:seq_show
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
In kernel/kcmp.c (c0000000001f7ccc)
Location: include/linux/fdtable.h:82
Inline: True
Inline callers:
  - kernel/kcmp.c:__se_sys_kcmp
  - kernel/kcmp.c:get_file_raw_ptr
```
```
In kernel/bpf/syscall.c (c00000000030a2bc)
Location: include/linux/fdtable.h:82
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
```
In fs/file.c (c0000000004ad01c)
Location: include/linux/fdtable.h:82
Inline: True
Inline callers:
  - fs/file.c:__se_sys_dup2
  - fs/file.c:ksys_dup3
  - fs/file.c:__fget
```
```
In fs/notify/dnotify/dnotify.c (c0000000004f2878)
Location: include/linux/fdtable.h:82
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
```
```
In fs/locks.c (c000000000529188)
Location: include/linux/fdtable.h:82
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
```
```
In fs/proc/fd.c (c00000000055cb60)
Location: include/linux/fdtable.h:82
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_fd_link
  - fs/proc/fd.c:tid_fd_mode
  - fs/proc/fd.c:seq_show
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
In kernel/kcmp.c (ffffffe000128c9c)
Location: include/linux/fdtable.h:82
Inline: True
Inline callers:
  - kernel/kcmp.c:__se_sys_kcmp
  - kernel/kcmp.c:get_file_raw_ptr
```
```
In kernel/bpf/syscall.c (ffffffe0001a105c)
Location: include/linux/fdtable.h:82
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
```
In fs/file.c (ffffffe0002768ea)
Location: include/linux/fdtable.h:82
Inline: True
Inline callers:
  - fs/file.c:__se_sys_dup2
  - fs/file.c:ksys_dup3
  - fs/file.c:__fget
```
```
In fs/notify/dnotify/dnotify.c (ffffffe00029f916)
Location: include/linux/fdtable.h:82
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
```
```
In fs/locks.c (ffffffe0002bfe1c)
Location: include/linux/fdtable.h:82
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
```
```
In fs/proc/fd.c (ffffffe0002dca16)
Location: include/linux/fdtable.h:82
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_fd_link
  - fs/proc/fd.c:tid_fd_mode
  - fs/proc/fd.c:seq_show
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
In kernel/kcmp.c (ffffffff81129339)
Location: include/linux/fdtable.h:82
Inline: True
Inline callers:
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:get_file_raw_ptr
```
```
In kernel/bpf/syscall.c (ffffffff811da683)
Location: include/linux/fdtable.h:82
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
```
In fs/file.c (ffffffff812f83b0)
Location: include/linux/fdtable.h:82
Inline: True
Inline callers:
  - fs/file.c:__ia32_sys_dup2
  - fs/file.c:__x64_sys_dup2
  - fs/file.c:ksys_dup3
  - fs/file.c:__fget
```
```
In fs/notify/dnotify/dnotify.c (ffffffff813270ec)
Location: include/linux/fdtable.h:82
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
```
```
In fs/locks.c (ffffffff8134f15b)
Location: include/linux/fdtable.h:82
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
```
```
In fs/proc/fd.c (ffffffff81372dd4)
Location: include/linux/fdtable.h:82
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_fd_link
  - fs/proc/fd.c:tid_fd_mode
  - fs/proc/fd.c:seq_show
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
In kernel/kcmp.c (ffffffff8111bbc9)
Location: include/linux/fdtable.h:82
Inline: True
Inline callers:
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:get_file_raw_ptr
```
```
In kernel/bpf/syscall.c (ffffffff811cd443)
Location: include/linux/fdtable.h:82
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
```
In fs/file.c (ffffffff812e8fd0)
Location: include/linux/fdtable.h:82
Inline: True
Inline callers:
  - fs/file.c:__ia32_sys_dup2
  - fs/file.c:__x64_sys_dup2
  - fs/file.c:ksys_dup3
  - fs/file.c:__fget
```
```
In fs/notify/dnotify/dnotify.c (ffffffff81317c8c)
Location: include/linux/fdtable.h:82
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
```
```
In fs/locks.c (ffffffff8133fe3b)
Location: include/linux/fdtable.h:82
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
```
```
In fs/proc/fd.c (ffffffff813638a4)
Location: include/linux/fdtable.h:82
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_fd_link
  - fs/proc/fd.c:tid_fd_mode
  - fs/proc/fd.c:seq_show
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
In kernel/kcmp.c (ffffffff81127059)
Location: include/linux/fdtable.h:82
Inline: True
Inline callers:
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:get_file_raw_ptr
```
```
In kernel/bpf/syscall.c (ffffffff811d8453)
Location: include/linux/fdtable.h:82
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
```
In fs/file.c (ffffffff812f61c0)
Location: include/linux/fdtable.h:82
Inline: True
Inline callers:
  - fs/file.c:__ia32_sys_dup2
  - fs/file.c:__x64_sys_dup2
  - fs/file.c:ksys_dup3
  - fs/file.c:__fget
```
```
In fs/notify/dnotify/dnotify.c (ffffffff81324bbc)
Location: include/linux/fdtable.h:82
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
```
```
In fs/locks.c (ffffffff8134cc2b)
Location: include/linux/fdtable.h:82
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
```
```
In fs/proc/fd.c (ffffffff813708a4)
Location: include/linux/fdtable.h:82
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_fd_link
  - fs/proc/fd.c:tid_fd_mode
  - fs/proc/fd.c:seq_show
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
In kernel/kcmp.c (ffffffff8113369c)
Location: include/linux/fdtable.h:82
Inline: True
Inline callers:
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:get_file_raw_ptr
```
```
In kernel/bpf/syscall.c (ffffffff811e67eb)
Location: include/linux/fdtable.h:82
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
```
In fs/file.c (ffffffff813073d7)
Location: include/linux/fdtable.h:82
Inline: True
Inline callers:
  - fs/file.c:__ia32_sys_dup2
  - fs/file.c:__x64_sys_dup2
  - fs/file.c:ksys_dup3
  - fs/file.c:__fget
```
```
In fs/notify/dnotify/dnotify.c (ffffffff8133693c)
Location: include/linux/fdtable.h:82
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
```
```
In fs/locks.c (ffffffff8136016b)
Location: include/linux/fdtable.h:82
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
```
```
In fs/proc/fd.c (ffffffff81384283)
Location: include/linux/fdtable.h:82
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_fd_link
  - fs/proc/fd.c:tid_fd_mode
  - fs/proc/fd.c:seq_show
```
</details>
</li>
</ul>

## Differences
