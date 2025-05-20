# Function: <code>proc_sb_info</code>

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
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a3b4a)
Location: include/linux/proc_fs.h:68
Inline: True
Inline callers:
  - kernel/fork.c:pidfd_show_fdinfo
```
```
In fs/locks.c (ffffffff81399d34)
Location: include/linux/proc_fs.h:68
Inline: True
Inline callers:
  - fs/locks.c:locks_show
  - fs/locks.c:lock_get_status
```
```
In fs/proc/inode.c (ffffffff813b9c45)
Location: include/linux/proc_fs.h:68
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_reg_open
  - fs/proc/inode.c:proc_show_options
```
```
In fs/proc/root.c (ffffffff813ba1b5)
Location: include/linux/proc_fs.h:68
Inline: True
Inline callers:
  - fs/proc/root.c:proc_kill_sb
  - fs/proc/root.c:proc_reconfigure
```
```
In fs/proc/base.c (ffffffff813bf766)
Location: include/linux/proc_fs.h:68
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:proc_pid_lookup
  - fs/proc/base.c:proc_timers_open
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:sched_show
  - fs/proc/base.c:proc_single_show
  - fs/proc/base.c:proc_pid_permission
```
```
In fs/proc/generic.c (ffffffff813c1259)
Location: include/linux/proc_fs.h:68
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_readdir
```
```
In fs/proc/array.c (ffffffff813c16a5)
Location: include/linux/proc_fs.h:68
Inline: True
Inline callers:
  - fs/proc/array.c:children_seq_show
```
```
In fs/proc/self.c (ffffffff813c6335)
Location: include/linux/proc_fs.h:68
Inline: True
Inline callers:
  - fs/proc/self.c:proc_setup_self
  - fs/proc/self.c:proc_self_get_link
```
```
In fs/proc/thread_self.c (ffffffff813c6515)
Location: include/linux/proc_fs.h:68
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/proc/thread_self.c:proc_thread_self_get_link
```
```
In security/tomoyo/realpath.c (ffffffff814e8c64)
Location: include/linux/proc_fs.h:68
Inline: True
Inline callers:
  - security/tomoyo/realpath.c:tomoyo_get_local_path
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81b70124)
Location: include/linux/proc_fs.h:68
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
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
In kernel/fork.c (ffffffff8109f29a)
Location: include/linux/proc_fs.h:69
Inline: True
Inline callers:
  - kernel/fork.c:pidfd_show_fdinfo
```
```
In fs/locks.c (ffffffff813ab824)
Location: include/linux/proc_fs.h:69
Inline: True
Inline callers:
  - fs/locks.c:locks_show
  - fs/locks.c:lock_get_status
```
```
In fs/proc/inode.c (ffffffff813cb6d5)
Location: include/linux/proc_fs.h:69
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_reg_open
  - fs/proc/inode.c:proc_show_options
```
```
In fs/proc/root.c (ffffffff813cbcb5)
Location: include/linux/proc_fs.h:69
Inline: True
Inline callers:
  - fs/proc/root.c:proc_kill_sb
  - fs/proc/root.c:proc_reconfigure
```
```
In fs/proc/base.c (ffffffff813d15e6)
Location: include/linux/proc_fs.h:69
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:proc_pid_lookup
  - fs/proc/base.c:proc_timers_open
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:sched_show
  - fs/proc/base.c:proc_single_show
  - fs/proc/base.c:proc_pid_permission
```
```
In fs/proc/generic.c (ffffffff813d3149)
Location: include/linux/proc_fs.h:69
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_readdir
```
```
In fs/proc/array.c (ffffffff813d359e)
Location: include/linux/proc_fs.h:69
Inline: True
Inline callers:
  - fs/proc/array.c:children_seq_show
```
```
In fs/proc/self.c (ffffffff813d82e5)
Location: include/linux/proc_fs.h:69
Inline: True
Inline callers:
  - fs/proc/self.c:proc_setup_self
  - fs/proc/self.c:proc_self_get_link
```
```
In fs/proc/thread_self.c (ffffffff813d84d5)
Location: include/linux/proc_fs.h:69
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/proc/thread_self.c:proc_thread_self_get_link
```
```
In security/tomoyo/realpath.c (ffffffff81505fa4)
Location: include/linux/proc_fs.h:69
Inline: True
Inline callers:
  - security/tomoyo/realpath.c:tomoyo_get_local_path
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81b7ec54)
Location: include/linux/proc_fs.h:69
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
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
In kernel/fork.c (ffffffff810a016a)
Location: include/linux/proc_fs.h:70
Inline: True
Inline callers:
  - kernel/fork.c:pidfd_show_fdinfo
```
```
In fs/locks.c (ffffffff813b2d0f)
Location: include/linux/proc_fs.h:70
Inline: True
Inline callers:
  - fs/locks.c:locks_show
  - fs/locks.c:lock_get_status
```
```
In fs/proc/inode.c (ffffffff813d1e35)
Location: include/linux/proc_fs.h:70
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_show_options
```
```
In fs/proc/root.c (ffffffff813d2ca5)
Location: include/linux/proc_fs.h:70
Inline: True
Inline callers:
  - fs/proc/root.c:proc_kill_sb
  - fs/proc/root.c:proc_reconfigure
```
```
In fs/proc/base.c (ffffffff813d84e5)
Location: include/linux/proc_fs.h:70
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:proc_pid_lookup
  - fs/proc/base.c:proc_timers_open
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:sched_show
  - fs/proc/base.c:proc_single_show
  - fs/proc/base.c:proc_pid_permission
```
```
In fs/proc/generic.c (ffffffff813d9f99)
Location: include/linux/proc_fs.h:70
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_readdir
```
```
In fs/proc/array.c (ffffffff813da3ce)
Location: include/linux/proc_fs.h:70
Inline: True
Inline callers:
  - fs/proc/array.c:children_seq_show
```
```
In fs/proc/self.c (ffffffff813df185)
Location: include/linux/proc_fs.h:70
Inline: True
Inline callers:
  - fs/proc/self.c:proc_setup_self
  - fs/proc/self.c:proc_self_get_link
```
```
In fs/proc/thread_self.c (ffffffff813df365)
Location: include/linux/proc_fs.h:70
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/proc/thread_self.c:proc_thread_self_get_link
```
```
In security/tomoyo/realpath.c (ffffffff8150cae5)
Location: include/linux/proc_fs.h:70
Inline: True
Inline callers:
  - security/tomoyo/realpath.c:tomoyo_get_local_path
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81b6d854)
Location: include/linux/proc_fs.h:70
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
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
In kernel/fork.c (ffffffff810b157a)
Location: include/linux/proc_fs.h:70
Inline: True
Inline callers:
  - kernel/fork.c:pidfd_show_fdinfo
```
```
In fs/locks.c (ffffffff814029ff)
Location: include/linux/proc_fs.h:70
Inline: True
Inline callers:
  - fs/locks.c:locks_show
  - fs/locks.c:lock_get_status
```
```
In fs/proc/inode.c (ffffffff81423445)
Location: include/linux/proc_fs.h:70
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_show_options
```
```
In fs/proc/root.c (ffffffff814241f5)
Location: include/linux/proc_fs.h:70
Inline: True
Inline callers:
  - fs/proc/root.c:proc_kill_sb
  - fs/proc/root.c:proc_reconfigure
```
```
In fs/proc/base.c (ffffffff81429c15)
Location: include/linux/proc_fs.h:70
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:proc_pid_lookup
  - fs/proc/base.c:proc_timers_open
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:sched_show
  - fs/proc/base.c:proc_single_show
  - fs/proc/base.c:proc_pid_permission
```
```
In fs/proc/generic.c (ffffffff8142b6c9)
Location: include/linux/proc_fs.h:70
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_readdir
```
```
In fs/proc/array.c (ffffffff8142bafe)
Location: include/linux/proc_fs.h:70
Inline: True
Inline callers:
  - fs/proc/array.c:children_seq_show
```
```
In fs/proc/self.c (ffffffff81430b35)
Location: include/linux/proc_fs.h:70
Inline: True
Inline callers:
  - fs/proc/self.c:proc_setup_self
  - fs/proc/self.c:proc_self_get_link
```
```
In fs/proc/thread_self.c (ffffffff81430d15)
Location: include/linux/proc_fs.h:70
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/proc/thread_self.c:proc_thread_self_get_link
```
```
In security/tomoyo/realpath.c (ffffffff8156a615)
Location: include/linux/proc_fs.h:70
Inline: True
Inline callers:
  - security/tomoyo/realpath.c:tomoyo_get_local_path
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81c356de)
Location: include/linux/proc_fs.h:70
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
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
In kernel/fork.c (ffffffff810c7889)
Location: include/linux/proc_fs.h:70
Inline: True
Inline callers:
  - kernel/fork.c:pidfd_show_fdinfo
```
```
In fs/locks.c (ffffffff8147744f)
Location: include/linux/proc_fs.h:70
Inline: True
Inline callers:
  - fs/locks.c:locks_show
  - fs/locks.c:lock_get_status
```
```
In fs/proc/inode.c (ffffffff8149be95)
Location: include/linux/proc_fs.h:70
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_show_options
```
```
In fs/proc/root.c (ffffffff8149cd95)
Location: include/linux/proc_fs.h:70
Inline: True
Inline callers:
  - fs/proc/root.c:proc_kill_sb
  - fs/proc/root.c:proc_reconfigure
```
```
In fs/proc/base.c (ffffffff814a3086)
Location: include/linux/proc_fs.h:70
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:proc_pid_lookup
  - fs/proc/base.c:proc_timers_open
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:sched_show
  - fs/proc/base.c:proc_single_show
  - fs/proc/base.c:proc_pid_permission
```
```
In fs/proc/generic.c (ffffffff814a4df9)
Location: include/linux/proc_fs.h:70
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_readdir
```
```
In fs/proc/array.c (ffffffff814a52cd)
Location: include/linux/proc_fs.h:70
Inline: True
Inline callers:
  - fs/proc/array.c:children_seq_show
```
```
In fs/proc/self.c (ffffffff814aa885)
Location: include/linux/proc_fs.h:70
Inline: True
Inline callers:
  - fs/proc/self.c:proc_setup_self
  - fs/proc/self.c:proc_self_get_link
```
```
In fs/proc/thread_self.c (ffffffff814aaa75)
Location: include/linux/proc_fs.h:70
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/proc/thread_self.c:proc_thread_self_get_link
```
```
In security/tomoyo/realpath.c (ffffffff816065d0)
Location: include/linux/proc_fs.h:70
Inline: True
Inline callers:
  - security/tomoyo/realpath.c:tomoyo_get_local_path
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81dd310e)
Location: include/linux/proc_fs.h:70
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
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
In kernel/fork.c (ffffffff810e43f9)
Location: include/linux/proc_fs.h:70
Inline: True
Inline callers:
  - kernel/fork.c:pidfd_show_fdinfo
```
```
In fs/locks.c (ffffffff81509c6f)
Location: include/linux/proc_fs.h:70
Inline: True
Inline callers:
  - fs/locks.c:locks_show
  - fs/locks.c:lock_get_status
```
```
In fs/proc/inode.c (ffffffff81530785)
Location: include/linux/proc_fs.h:70
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_show_options
```
```
In fs/proc/root.c (ffffffff815317c5)
Location: include/linux/proc_fs.h:70
Inline: True
Inline callers:
  - fs/proc/root.c:proc_kill_sb
  - fs/proc/root.c:proc_reconfigure
```
```
In fs/proc/base.c (ffffffff81538306)
Location: include/linux/proc_fs.h:70
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:proc_pid_lookup
  - fs/proc/base.c:proc_timers_open
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:sched_show
  - fs/proc/base.c:proc_single_show
  - fs/proc/base.c:proc_pid_permission
```
```
In fs/proc/generic.c (ffffffff8153a339)
Location: include/linux/proc_fs.h:70
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_readdir
```
```
In fs/proc/array.c (ffffffff8153a85d)
Location: include/linux/proc_fs.h:70
Inline: True
Inline callers:
  - fs/proc/array.c:children_seq_show
```
```
In fs/proc/self.c (ffffffff815404f5)
Location: include/linux/proc_fs.h:70
Inline: True
Inline callers:
  - fs/proc/self.c:proc_setup_self
  - fs/proc/self.c:proc_self_get_link
```
```
In fs/proc/thread_self.c (ffffffff81540715)
Location: include/linux/proc_fs.h:70
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/proc/thread_self.c:proc_thread_self_get_link
```
```
In security/tomoyo/realpath.c (ffffffff816b7a40)
Location: include/linux/proc_fs.h:70
Inline: True
Inline callers:
  - security/tomoyo/realpath.c:tomoyo_get_local_path
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81fa469e)
Location: include/linux/proc_fs.h:70
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
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
In kernel/fork.c (ffffffff810efa89)
Location: include/linux/proc_fs.h:70
Inline: True
Inline callers:
  - kernel/fork.c:pidfd_show_fdinfo
```
```
In fs/locks.c (ffffffff815413df)
Location: include/linux/proc_fs.h:70
Inline: True
Inline callers:
  - fs/locks.c:locks_show
  - fs/locks.c:lock_get_status
```
```
In fs/proc/inode.c (ffffffff81568905)
Location: include/linux/proc_fs.h:70
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_show_options
```
```
In fs/proc/root.c (ffffffff81569995)
Location: include/linux/proc_fs.h:70
Inline: True
Inline callers:
  - fs/proc/root.c:proc_kill_sb
  - fs/proc/root.c:proc_reconfigure
```
```
In fs/proc/base.c (ffffffff81570549)
Location: include/linux/proc_fs.h:70
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:proc_pid_lookup
  - fs/proc/base.c:proc_timers_open
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:sched_show
  - fs/proc/base.c:proc_single_show
  - fs/proc/base.c:proc_pid_permission
```
```
In fs/proc/generic.c (ffffffff815725dc)
Location: include/linux/proc_fs.h:70
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_readdir
```
```
In fs/proc/array.c (ffffffff81572b3d)
Location: include/linux/proc_fs.h:70
Inline: True
Inline callers:
  - fs/proc/array.c:children_seq_show
```
```
In fs/proc/self.c (ffffffff815788b5)
Location: include/linux/proc_fs.h:70
Inline: True
Inline callers:
  - fs/proc/self.c:proc_setup_self
  - fs/proc/self.c:proc_self_get_link
```
```
In fs/proc/thread_self.c (ffffffff81578ad5)
Location: include/linux/proc_fs.h:70
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/proc/thread_self.c:proc_thread_self_get_link
```
```
In security/tomoyo/realpath.c (ffffffff816f0410)
Location: include/linux/proc_fs.h:70
Inline: True
Inline callers:
  - security/tomoyo/realpath.c:tomoyo_get_local_path
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff82004f54)
Location: include/linux/proc_fs.h:70
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
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
In kernel/fork.c (ffffffff810f8e99)
Location: include/linux/proc_fs.h:71
Inline: True
Inline callers:
  - kernel/fork.c:pidfd_show_fdinfo
```
```
In fs/locks.c (ffffffff815768bf)
Location: include/linux/proc_fs.h:71
Inline: True
Inline callers:
  - fs/locks.c:locks_show
  - fs/locks.c:lock_get_status
```
```
In fs/proc/inode.c (ffffffff815a0f25)
Location: include/linux/proc_fs.h:71
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_show_options
```
```
In fs/proc/root.c (ffffffff815a1fa5)
Location: include/linux/proc_fs.h:71
Inline: True
Inline callers:
  - fs/proc/root.c:proc_kill_sb
  - fs/proc/root.c:proc_reconfigure
```
```
In fs/proc/base.c (ffffffff815a8ee8)
Location: include/linux/proc_fs.h:71
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:proc_pid_lookup
  - fs/proc/base.c:proc_timers_open
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:sched_show
  - fs/proc/base.c:proc_single_show
  - fs/proc/base.c:proc_pid_permission
```
```
In fs/proc/generic.c (ffffffff815aaf8c)
Location: include/linux/proc_fs.h:71
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_readdir
```
```
In fs/proc/array.c (ffffffff815ab4ed)
Location: include/linux/proc_fs.h:71
Inline: True
Inline callers:
  - fs/proc/array.c:children_seq_show
```
```
In fs/proc/self.c (ffffffff815b1045)
Location: include/linux/proc_fs.h:71
Inline: True
Inline callers:
  - fs/proc/self.c:proc_setup_self
  - fs/proc/self.c:proc_self_get_link
```
```
In fs/proc/thread_self.c (ffffffff815b12b5)
Location: include/linux/proc_fs.h:71
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/proc/thread_self.c:proc_thread_self_get_link
```
```
In security/tomoyo/realpath.c (ffffffff8172d1e0)
Location: include/linux/proc_fs.h:71
Inline: True
Inline callers:
  - security/tomoyo/realpath.c:tomoyo_get_local_path
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff820d3d24)
Location: include/linux/proc_fs.h:71
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
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
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
