# Function: <code>proc_pid_ns</code>

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
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8131f66e)
Location: include/linux/proc_fs.h:132
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:proc_timers_open
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:sched_show
  - fs/proc/base.c:proc_single_show
  - fs/proc/base.c:proc_pid_permission
```
```
In fs/proc/array.c (ffffffff813210c5)
Location: include/linux/proc_fs.h:132
Inline: True
Inline callers:
  - fs/proc/array.c:children_seq_show
```
```
In fs/proc/self.c (ffffffff8132532b)
Location: include/linux/proc_fs.h:132
Inline: True
Inline callers:
  - fs/proc/self.c:proc_setup_self
  - fs/proc/self.c:proc_self_get_link
```
```
In fs/proc/thread_self.c (ffffffff8132551b)
Location: include/linux/proc_fs.h:132
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/proc/thread_self.c:proc_thread_self_get_link
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff819997bd)
Location: include/linux/proc_fs.h:132
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
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
In fs/proc/base.c (ffffffff8133679e)
Location: include/linux/proc_fs.h:132
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:proc_timers_open
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:sched_show
  - fs/proc/base.c:proc_single_show
  - fs/proc/base.c:proc_pid_permission
```
```
In fs/proc/array.c (ffffffff813381d5)
Location: include/linux/proc_fs.h:132
Inline: True
Inline callers:
  - fs/proc/array.c:children_seq_show
```
```
In fs/proc/self.c (ffffffff8133c4cb)
Location: include/linux/proc_fs.h:132
Inline: True
Inline callers:
  - fs/proc/self.c:proc_setup_self
  - fs/proc/self.c:proc_self_get_link
```
```
In fs/proc/thread_self.c (ffffffff8133c6bb)
Location: include/linux/proc_fs.h:132
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/proc/thread_self.c:proc_thread_self_get_link
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff819d010d)
Location: include/linux/proc_fs.h:132
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
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
In kernel/fork.c (ffffffff81096855)
Location: include/linux/proc_fs.h:147
Inline: True
Inline callers:
  - kernel/fork.c:pidfd_show_fdinfo
```
```
In fs/proc/base.c (ffffffff8135e84e)
Location: include/linux/proc_fs.h:147
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:proc_timers_open
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:sched_show
  - fs/proc/base.c:proc_single_show
  - fs/proc/base.c:proc_pid_permission
```
```
In fs/proc/array.c (ffffffff81360355)
Location: include/linux/proc_fs.h:147
Inline: True
Inline callers:
  - fs/proc/array.c:children_seq_show
```
```
In fs/proc/self.c (ffffffff8136472b)
Location: include/linux/proc_fs.h:147
Inline: True
Inline callers:
  - fs/proc/self.c:proc_setup_self
  - fs/proc/self.c:proc_self_get_link
```
```
In fs/proc/thread_self.c (ffffffff8136490b)
Location: include/linux/proc_fs.h:147
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/proc/thread_self.c:proc_thread_self_get_link
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81a3ee2d)
Location: include/linux/proc_fs.h:147
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
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
In kernel/fork.c (ffffffff8109cf25)
Location: include/linux/proc_fs.h:147
Inline: True
Inline callers:
  - kernel/fork.c:pidfd_show_fdinfo
```
```
In fs/proc/base.c (ffffffff81376aae)
Location: include/linux/proc_fs.h:147
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:proc_timers_open
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:sched_show
  - fs/proc/base.c:proc_single_show
  - fs/proc/base.c:proc_pid_permission
```
```
In fs/proc/array.c (ffffffff813785b5)
Location: include/linux/proc_fs.h:147
Inline: True
Inline callers:
  - fs/proc/array.c:children_seq_show
```
```
In fs/proc/self.c (ffffffff8137c9bb)
Location: include/linux/proc_fs.h:147
Inline: True
Inline callers:
  - fs/proc/self.c:proc_setup_self
  - fs/proc/self.c:proc_self_get_link
```
```
In fs/proc/thread_self.c (ffffffff8137cb9b)
Location: include/linux/proc_fs.h:147
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/proc/thread_self.c:proc_thread_self_get_link
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81a75a9d)
Location: include/linux/proc_fs.h:147
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
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
In kernel/fork.c (ffffffff810a3b4a)
Location: include/linux/proc_fs.h:208
Inline: True
Inline callers:
  - kernel/fork.c:pidfd_show_fdinfo
```
```
In fs/locks.c (ffffffff81399d34)
Location: include/linux/proc_fs.h:208
Inline: True
Inline callers:
  - fs/locks.c:locks_show
  - fs/locks.c:lock_get_status
```
```
In fs/proc/base.c (ffffffff813bf766)
Location: include/linux/proc_fs.h:208
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:proc_timers_open
  - fs/proc/base.c:sched_show
  - fs/proc/base.c:proc_single_show
```
```
In fs/proc/array.c (ffffffff813c16a5)
Location: include/linux/proc_fs.h:208
Inline: True
Inline callers:
  - fs/proc/array.c:children_seq_show
```
```
In fs/proc/self.c (ffffffff813c6275)
Location: include/linux/proc_fs.h:208
Inline: True
Inline callers:
  - fs/proc/self.c:proc_self_get_link
```
```
In fs/proc/thread_self.c (ffffffff813c6435)
Location: include/linux/proc_fs.h:208
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_thread_self_get_link
```
```
In security/tomoyo/realpath.c (ffffffff814e8c64)
Location: include/linux/proc_fs.h:208
Inline: True
Inline callers:
  - security/tomoyo/realpath.c:tomoyo_get_local_path
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81b70124)
Location: include/linux/proc_fs.h:208
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
Location: include/linux/proc_fs.h:216
Inline: True
Inline callers:
  - kernel/fork.c:pidfd_show_fdinfo
```
```
In fs/locks.c (ffffffff813ab824)
Location: include/linux/proc_fs.h:216
Inline: True
Inline callers:
  - fs/locks.c:locks_show
  - fs/locks.c:lock_get_status
```
```
In fs/proc/base.c (ffffffff813d15e6)
Location: include/linux/proc_fs.h:216
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:proc_timers_open
  - fs/proc/base.c:sched_show
  - fs/proc/base.c:proc_single_show
```
```
In fs/proc/array.c (ffffffff813d359e)
Location: include/linux/proc_fs.h:216
Inline: True
Inline callers:
  - fs/proc/array.c:children_seq_show
```
```
In fs/proc/self.c (ffffffff813d8215)
Location: include/linux/proc_fs.h:216
Inline: True
Inline callers:
  - fs/proc/self.c:proc_self_get_link
```
```
In fs/proc/thread_self.c (ffffffff813d83e5)
Location: include/linux/proc_fs.h:216
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_thread_self_get_link
```
```
In security/tomoyo/realpath.c (ffffffff81505fa4)
Location: include/linux/proc_fs.h:216
Inline: True
Inline callers:
  - security/tomoyo/realpath.c:tomoyo_get_local_path
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81b7ec54)
Location: include/linux/proc_fs.h:216
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
Location: include/linux/proc_fs.h:217
Inline: True
Inline callers:
  - kernel/fork.c:pidfd_show_fdinfo
```
```
In fs/locks.c (ffffffff813b2d0f)
Location: include/linux/proc_fs.h:217
Inline: True
Inline callers:
  - fs/locks.c:locks_show
  - fs/locks.c:lock_get_status
```
```
In fs/proc/base.c (ffffffff813d84e5)
Location: include/linux/proc_fs.h:217
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:proc_timers_open
  - fs/proc/base.c:sched_show
  - fs/proc/base.c:proc_single_show
```
```
In fs/proc/array.c (ffffffff813da3ce)
Location: include/linux/proc_fs.h:217
Inline: True
Inline callers:
  - fs/proc/array.c:children_seq_show
```
```
In fs/proc/self.c (ffffffff813df0c5)
Location: include/linux/proc_fs.h:217
Inline: True
Inline callers:
  - fs/proc/self.c:proc_self_get_link
```
```
In fs/proc/thread_self.c (ffffffff813df285)
Location: include/linux/proc_fs.h:217
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_thread_self_get_link
```
```
In security/tomoyo/realpath.c (ffffffff8150cae5)
Location: include/linux/proc_fs.h:217
Inline: True
Inline callers:
  - security/tomoyo/realpath.c:tomoyo_get_local_path
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81b6d854)
Location: include/linux/proc_fs.h:217
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
Location: include/linux/proc_fs.h:217
Inline: True
Inline callers:
  - kernel/fork.c:pidfd_show_fdinfo
```
```
In fs/locks.c (ffffffff814029ff)
Location: include/linux/proc_fs.h:217
Inline: True
Inline callers:
  - fs/locks.c:locks_show
  - fs/locks.c:lock_get_status
```
```
In fs/proc/base.c (ffffffff81429c15)
Location: include/linux/proc_fs.h:217
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:proc_timers_open
  - fs/proc/base.c:sched_show
  - fs/proc/base.c:proc_single_show
```
```
In fs/proc/array.c (ffffffff8142bafe)
Location: include/linux/proc_fs.h:217
Inline: True
Inline callers:
  - fs/proc/array.c:children_seq_show
```
```
In fs/proc/self.c (ffffffff81430a75)
Location: include/linux/proc_fs.h:217
Inline: True
Inline callers:
  - fs/proc/self.c:proc_self_get_link
```
```
In fs/proc/thread_self.c (ffffffff81430c35)
Location: include/linux/proc_fs.h:217
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_thread_self_get_link
```
```
In security/tomoyo/realpath.c (ffffffff8156a615)
Location: include/linux/proc_fs.h:217
Inline: True
Inline callers:
  - security/tomoyo/realpath.c:tomoyo_get_local_path
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81c356de)
Location: include/linux/proc_fs.h:217
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
Location: include/linux/proc_fs.h:234
Inline: True
Inline callers:
  - kernel/fork.c:pidfd_show_fdinfo
```
```
In fs/locks.c (ffffffff8147744f)
Location: include/linux/proc_fs.h:234
Inline: True
Inline callers:
  - fs/locks.c:locks_show
  - fs/locks.c:lock_get_status
```
```
In fs/proc/base.c (ffffffff814a3086)
Location: include/linux/proc_fs.h:234
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:proc_timers_open
  - fs/proc/base.c:sched_show
  - fs/proc/base.c:proc_single_show
```
```
In fs/proc/array.c (ffffffff814a52cd)
Location: include/linux/proc_fs.h:234
Inline: True
Inline callers:
  - fs/proc/array.c:children_seq_show
```
```
In fs/proc/self.c (ffffffff814aa7b5)
Location: include/linux/proc_fs.h:234
Inline: True
Inline callers:
  - fs/proc/self.c:proc_self_get_link
```
```
In fs/proc/thread_self.c (ffffffff814aa985)
Location: include/linux/proc_fs.h:234
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_thread_self_get_link
```
```
In security/tomoyo/realpath.c (ffffffff816065d0)
Location: include/linux/proc_fs.h:234
Inline: True
Inline callers:
  - security/tomoyo/realpath.c:tomoyo_get_local_path
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81dd310e)
Location: include/linux/proc_fs.h:234
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
Location: include/linux/proc_fs.h:236
Inline: True
Inline callers:
  - kernel/fork.c:pidfd_show_fdinfo
```
```
In fs/locks.c (ffffffff81509c6f)
Location: include/linux/proc_fs.h:236
Inline: True
Inline callers:
  - fs/locks.c:locks_show
  - fs/locks.c:lock_get_status
```
```
In fs/proc/base.c (ffffffff81538306)
Location: include/linux/proc_fs.h:236
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:proc_timers_open
  - fs/proc/base.c:sched_show
  - fs/proc/base.c:proc_single_show
```
```
In fs/proc/array.c (ffffffff8153a85d)
Location: include/linux/proc_fs.h:236
Inline: True
Inline callers:
  - fs/proc/array.c:children_seq_show
```
```
In fs/proc/self.c (ffffffff81540415)
Location: include/linux/proc_fs.h:236
Inline: True
Inline callers:
  - fs/proc/self.c:proc_self_get_link
```
```
In fs/proc/thread_self.c (ffffffff81540615)
Location: include/linux/proc_fs.h:236
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_thread_self_get_link
```
```
In security/tomoyo/realpath.c (ffffffff816b7a40)
Location: include/linux/proc_fs.h:236
Inline: True
Inline callers:
  - security/tomoyo/realpath.c:tomoyo_get_local_path
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81fa469e)
Location: include/linux/proc_fs.h:236
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
Location: include/linux/proc_fs.h:238
Inline: True
Inline callers:
  - kernel/fork.c:pidfd_show_fdinfo
```
```
In fs/locks.c (ffffffff815413df)
Location: include/linux/proc_fs.h:238
Inline: True
Inline callers:
  - fs/locks.c:locks_show
  - fs/locks.c:lock_get_status
```
```
In fs/proc/base.c (ffffffff81570549)
Location: include/linux/proc_fs.h:238
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:proc_timers_open
  - fs/proc/base.c:sched_show
  - fs/proc/base.c:proc_single_show
```
```
In fs/proc/array.c (ffffffff81572b3d)
Location: include/linux/proc_fs.h:238
Inline: True
Inline callers:
  - fs/proc/array.c:children_seq_show
```
```
In fs/proc/self.c (ffffffff815787d5)
Location: include/linux/proc_fs.h:238
Inline: True
Inline callers:
  - fs/proc/self.c:proc_self_get_link
```
```
In fs/proc/thread_self.c (ffffffff815789d5)
Location: include/linux/proc_fs.h:238
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_thread_self_get_link
```
```
In security/tomoyo/realpath.c (ffffffff816f0410)
Location: include/linux/proc_fs.h:238
Inline: True
Inline callers:
  - security/tomoyo/realpath.c:tomoyo_get_local_path
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff82004f54)
Location: include/linux/proc_fs.h:238
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
Location: include/linux/proc_fs.h:240
Inline: True
Inline callers:
  - kernel/fork.c:pidfd_show_fdinfo
```
```
In fs/locks.c (ffffffff815768bf)
Location: include/linux/proc_fs.h:240
Inline: True
Inline callers:
  - fs/locks.c:locks_show
  - fs/locks.c:lock_get_status
```
```
In fs/proc/base.c (ffffffff815a8ee8)
Location: include/linux/proc_fs.h:240
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:proc_timers_open
  - fs/proc/base.c:sched_show
  - fs/proc/base.c:proc_single_show
```
```
In fs/proc/array.c (ffffffff815ab4ed)
Location: include/linux/proc_fs.h:240
Inline: True
Inline callers:
  - fs/proc/array.c:children_seq_show
```
```
In fs/proc/self.c (ffffffff815b0f05)
Location: include/linux/proc_fs.h:240
Inline: True
Inline callers:
  - fs/proc/self.c:proc_self_get_link
```
```
In fs/proc/thread_self.c (ffffffff815b1155)
Location: include/linux/proc_fs.h:240
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_thread_self_get_link
```
```
In security/tomoyo/realpath.c (ffffffff8172d1e0)
Location: include/linux/proc_fs.h:240
Inline: True
Inline callers:
  - security/tomoyo/realpath.c:tomoyo_get_local_path
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff820d3d24)
Location: include/linux/proc_fs.h:240
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
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffff8000100f11fc)
Location: include/linux/proc_fs.h:147
Inline: True
Inline callers:
  - kernel/fork.c:pidfd_show_fdinfo
```
```
In fs/proc/base.c (ffff800010442118)
Location: include/linux/proc_fs.h:147
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:proc_timers_open
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:sched_show
  - fs/proc/base.c:proc_single_show
  - fs/proc/base.c:proc_pid_permission
```
```
In fs/proc/array.c (ffff80001044495c)
Location: include/linux/proc_fs.h:147
Inline: True
Inline callers:
  - fs/proc/array.c:children_seq_show
```
```
In fs/proc/self.c (ffff800010449328)
Location: include/linux/proc_fs.h:147
Inline: True
Inline callers:
  - fs/proc/self.c:proc_setup_self
  - fs/proc/self.c:proc_self_get_link
```
```
In fs/proc/thread_self.c (ffff8000104494fc)
Location: include/linux/proc_fs.h:147
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/proc/thread_self.c:proc_thread_self_get_link
```
```
In net/ipv6/ip6_flowlabel.c (ffff800010d3e440)
Location: include/linux/proc_fs.h:147
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
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
In kernel/fork.c (c0350678)
Location: include/linux/proc_fs.h:147
Inline: True
Inline callers:
  - kernel/fork.c:pidfd_show_fdinfo
```
```
In fs/proc/base.c (c0607924)
Location: include/linux/proc_fs.h:147
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:proc_timers_open
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:sched_show
  - fs/proc/base.c:proc_single_show
  - fs/proc/base.c:proc_pid_permission
```
```
In fs/proc/array.c (c060984c)
Location: include/linux/proc_fs.h:147
Inline: True
Inline callers:
  - fs/proc/array.c:children_seq_show
```
```
In fs/proc/self.c (c060e3f8)
Location: include/linux/proc_fs.h:147
Inline: True
Inline callers:
  - fs/proc/self.c:proc_setup_self
  - fs/proc/self.c:proc_self_get_link
```
```
In fs/proc/thread_self.c (c060e614)
Location: include/linux/proc_fs.h:147
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/proc/thread_self.c:proc_thread_self_get_link
```
```
In net/ipv6/ip6_flowlabel.c (c0e41814)
Location: include/linux/proc_fs.h:147
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
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
In kernel/fork.c (c000000000136d70)
Location: include/linux/proc_fs.h:147
Inline: True
Inline callers:
  - kernel/fork.c:pidfd_show_fdinfo
```
```
In fs/proc/base.c (c000000000557670)
Location: include/linux/proc_fs.h:147
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:proc_timers_open
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:sched_show
  - fs/proc/base.c:proc_single_show
  - fs/proc/base.c:proc_pid_permission
```
```
In fs/proc/array.c (c00000000055a010)
Location: include/linux/proc_fs.h:147
Inline: True
Inline callers:
  - fs/proc/array.c:children_seq_show
```
```
In fs/proc/self.c (c00000000055fe28)
Location: include/linux/proc_fs.h:147
Inline: True
Inline callers:
  - fs/proc/self.c:proc_setup_self
  - fs/proc/self.c:proc_self_get_link
```
```
In fs/proc/thread_self.c (c0000000005600d8)
Location: include/linux/proc_fs.h:147
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/proc/thread_self.c:proc_thread_self_get_link
```
```
In net/ipv6/ip6_flowlabel.c (c000000000e72ca4)
Location: include/linux/proc_fs.h:147
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
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
In kernel/fork.c (ffffffe0000be8fe)
Location: include/linux/proc_fs.h:147
Inline: True
Inline callers:
  - kernel/fork.c:pidfd_show_fdinfo
```
```
In fs/proc/base.c (ffffffe0002d8e1c)
Location: include/linux/proc_fs.h:147
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:proc_timers_open
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:sched_show
  - fs/proc/base.c:proc_single_show
  - fs/proc/base.c:proc_pid_permission
```
```
In fs/proc/array.c (ffffffe0002daa18)
Location: include/linux/proc_fs.h:147
Inline: True
Inline callers:
  - fs/proc/array.c:children_seq_show
```
```
In fs/proc/self.c (ffffffe0002decc8)
Location: include/linux/proc_fs.h:147
Inline: True
Inline callers:
  - fs/proc/self.c:proc_setup_self
  - fs/proc/self.c:proc_self_get_link
```
```
In fs/proc/thread_self.c (ffffffe0002dee76)
Location: include/linux/proc_fs.h:147
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/proc/thread_self.c:proc_thread_self_get_link
```
```
In net/ipv6/ip6_flowlabel.c (ffffffe00087aa8a)
Location: include/linux/proc_fs.h:147
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
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
In kernel/fork.c (ffffffff81096845)
Location: include/linux/proc_fs.h:147
Inline: True
Inline callers:
  - kernel/fork.c:pidfd_show_fdinfo
```
```
In fs/proc/base.c (ffffffff8136f08e)
Location: include/linux/proc_fs.h:147
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:proc_timers_open
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:sched_show
  - fs/proc/base.c:proc_single_show
  - fs/proc/base.c:proc_pid_permission
```
```
In fs/proc/array.c (ffffffff81370b95)
Location: include/linux/proc_fs.h:147
Inline: True
Inline callers:
  - fs/proc/array.c:children_seq_show
```
```
In fs/proc/self.c (ffffffff81374f9b)
Location: include/linux/proc_fs.h:147
Inline: True
Inline callers:
  - fs/proc/self.c:proc_setup_self
  - fs/proc/self.c:proc_self_get_link
```
```
In fs/proc/thread_self.c (ffffffff8137517b)
Location: include/linux/proc_fs.h:147
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/proc/thread_self.c:proc_thread_self_get_link
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81a1512d)
Location: include/linux/proc_fs.h:147
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
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
In kernel/fork.c (ffffffff810852c5)
Location: include/linux/proc_fs.h:147
Inline: True
Inline callers:
  - kernel/fork.c:pidfd_show_fdinfo
```
```
In fs/proc/base.c (ffffffff8135fb1e)
Location: include/linux/proc_fs.h:147
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:proc_timers_open
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:sched_show
  - fs/proc/base.c:proc_single_show
  - fs/proc/base.c:proc_pid_permission
```
```
In fs/proc/array.c (ffffffff81361625)
Location: include/linux/proc_fs.h:147
Inline: True
Inline callers:
  - fs/proc/array.c:children_seq_show
```
```
In fs/proc/self.c (ffffffff81365a6b)
Location: include/linux/proc_fs.h:147
Inline: True
Inline callers:
  - fs/proc/self.c:proc_setup_self
  - fs/proc/self.c:proc_self_get_link
```
```
In fs/proc/thread_self.c (ffffffff81365c4b)
Location: include/linux/proc_fs.h:147
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/proc/thread_self.c:proc_thread_self_get_link
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff819d1eed)
Location: include/linux/proc_fs.h:147
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
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
In kernel/fork.c (ffffffff810967f5)
Location: include/linux/proc_fs.h:147
Inline: True
Inline callers:
  - kernel/fork.c:pidfd_show_fdinfo
```
```
In fs/proc/base.c (ffffffff8136cb5e)
Location: include/linux/proc_fs.h:147
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:proc_timers_open
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:sched_show
  - fs/proc/base.c:proc_single_show
  - fs/proc/base.c:proc_pid_permission
```
```
In fs/proc/array.c (ffffffff8136e665)
Location: include/linux/proc_fs.h:147
Inline: True
Inline callers:
  - fs/proc/array.c:children_seq_show
```
```
In fs/proc/self.c (ffffffff81372a6b)
Location: include/linux/proc_fs.h:147
Inline: True
Inline callers:
  - fs/proc/self.c:proc_setup_self
  - fs/proc/self.c:proc_self_get_link
```
```
In fs/proc/thread_self.c (ffffffff81372c4b)
Location: include/linux/proc_fs.h:147
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/proc/thread_self.c:proc_thread_self_get_link
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81a7fbad)
Location: include/linux/proc_fs.h:147
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
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
In kernel/fork.c (ffffffff8109e685)
Location: include/linux/proc_fs.h:147
Inline: True
Inline callers:
  - kernel/fork.c:pidfd_show_fdinfo
```
```
In fs/proc/base.c (ffffffff8138043f)
Location: include/linux/proc_fs.h:147
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:proc_timers_open
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:sched_show
  - fs/proc/base.c:proc_single_show
  - fs/proc/base.c:proc_pid_permission
```
```
In fs/proc/array.c (ffffffff81381fb5)
Location: include/linux/proc_fs.h:147
Inline: True
Inline callers:
  - fs/proc/array.c:children_seq_show
```
```
In fs/proc/self.c (ffffffff8138644b)
Location: include/linux/proc_fs.h:147
Inline: True
Inline callers:
  - fs/proc/self.c:proc_setup_self
  - fs/proc/self.c:proc_self_get_link
```
```
In fs/proc/thread_self.c (ffffffff8138662b)
Location: include/linux/proc_fs.h:147
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_setup_thread_self
  - fs/proc/thread_self.c:proc_thread_self_get_link
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81a8c46d)
Location: include/linux/proc_fs.h:147
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
```
</details>
</li>
</ul>

## Differences
