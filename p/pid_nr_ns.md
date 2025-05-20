# Function: <code>pid_nr_ns</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
pid_t pid_nr_ns(struct pid *pid, struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff8109dc50)
Location: kernel/pid.c:500
Inline: True
Inline callers:
  - kernel/pid.c:pid_vnr
  - kernel/pid.c:task_tgid_nr_ns
  - kernel/pid.c:__task_pid_nr_ns
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
  - fs/proc/base.c:show_timer
  - fs/proc/base.c:next_tgid
  - fs/proc/array.c:children_seq_show
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - fs/fuse/file.c:fuse_setlk
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_show
```
**Symbols:**

```
ffffffff8109dc50-ffffffff8109dc83: pid_nr_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
pid_t pid_nr_ns(struct pid *pid, struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810a1367)
Location: kernel/pid.c:500
Inline: True
Inline callers:
  - kernel/pid.c:task_tgid_nr_ns
  - kernel/pid.c:__task_pid_nr_ns
  - kernel/pid.c:pid_vnr
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
  - fs/proc/base.c:next_tgid
  - fs/proc/base.c:show_timer
  - fs/proc/array.c:children_seq_show
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - fs/fuse/file.c:fuse_setlk
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_show
```
**Symbols:**

```
ffffffff810a12b0-ffffffff810a12e3: pid_nr_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
pid_t pid_nr_ns(struct pid *pid, struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810a6427)
Location: kernel/pid.c:500
Inline: True
Inline callers:
  - kernel/pid.c:task_tgid_nr_ns
  - kernel/pid.c:__task_pid_nr_ns
  - kernel/pid.c:pid_vnr
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
  - fs/locks.c:locks_show
  - fs/locks.c:lock_get_status
  - fs/proc/base.c:next_tgid
  - fs/proc/base.c:show_timer
  - fs/proc/array.c:children_seq_show
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - fs/fuse/file.c:fuse_setlk
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_show
```
**Symbols:**

```
ffffffff810a6370-ffffffff810a63a3: pid_nr_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
pid_t pid_nr_ns(struct pid *pid, struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810a3453)
Location: kernel/pid.c:501
Inline: True
Inline callers:
  - kernel/pid.c:__task_pid_nr_ns
  - kernel/pid.c:pid_vnr
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
  - fs/locks.c:locks_show
  - fs/locks.c:lock_get_status
  - fs/proc/base.c:next_tgid
  - fs/proc/base.c:show_timer
  - fs/proc/array.c:children_seq_show
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - fs/fuse/file.c:fuse_setlk
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_show
```
**Symbols:**

```
ffffffff810a3350-ffffffff810a337f: pid_nr_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
pid_t pid_nr_ns(struct pid *pid, struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810a9ce3)
Location: kernel/pid.c:370
Inline: True
Inline callers:
  - kernel/pid.c:__task_pid_nr_ns
  - kernel/pid.c:pid_vnr
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
  - fs/proc/base.c:next_tgid
  - fs/proc/base.c:show_timer
  - fs/proc/array.c:children_seq_show
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - fs/fuse/file.c:fuse_setlk
  - fs/fuse/file.c:fuse_getlk
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_show
```
**Symbols:**

```
ffffffff810a9b70-ffffffff810a9b9c: pid_nr_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
pid_t pid_nr_ns(struct pid *pid, struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810b0853)
Location: kernel/pid.c:395
Inline: True
Inline callers:
  - kernel/pid.c:__task_pid_nr_ns
  - kernel/pid.c:pid_vnr
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
  - fs/proc/base.c:next_tgid
  - fs/proc/base.c:show_timer
  - fs/proc/array.c:children_seq_show
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
  - fs/fuse/dev.c:__fuse_get_req
  - fs/fuse/file.c:fuse_setlk
  - fs/fuse/file.c:fuse_getlk
  - ipc/msg.c:sysvipc_msg_proc_show
  - ipc/msg.c:sysvipc_msg_proc_show
  - ipc/shm.c:sysvipc_shm_proc_show
  - ipc/shm.c:sysvipc_shm_proc_show
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_show
```
**Symbols:**

```
ffffffff810b0780-ffffffff810b07ac: pid_nr_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
pid_t pid_nr_ns(struct pid *pid, struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810b9998)
Location: kernel/pid.c:402
Inline: True
Inline callers:
  - kernel/pid.c:__task_pid_nr_ns
  - kernel/pid.c:pid_vnr
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
  - fs/proc/base.c:next_tgid
  - fs/proc/base.c:show_timer
  - fs/proc/array.c:children_seq_show
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
  - fs/fuse/dev.c:__fuse_get_req
  - fs/fuse/file.c:fuse_setlk
  - fs/fuse/file.c:fuse_getlk
  - ipc/msg.c:sysvipc_msg_proc_show
  - ipc/msg.c:sysvipc_msg_proc_show
  - ipc/shm.c:sysvipc_shm_proc_show
  - ipc/shm.c:sysvipc_shm_proc_show
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_show
```
**Symbols:**

```
ffffffff810b98c0-ffffffff810b98ec: pid_nr_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
pid_t pid_nr_ns(struct pid *pid, struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810bf79f)
Location: kernel/pid.c:405
Inline: True
Inline callers:
  - kernel/pid.c:__task_pid_nr_ns
  - kernel/pid.c:pid_vnr
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
  - kernel/fork.c:pidfd_show_fdinfo
  - fs/proc/base.c:next_tgid
  - fs/proc/base.c:show_timer
  - fs/proc/array.c:children_seq_show
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:task_state
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
  - fs/fuse/dev.c:__fuse_get_req
  - fs/fuse/file.c:fuse_setlk
  - fs/fuse/file.c:fuse_getlk
  - ipc/msg.c:sysvipc_msg_proc_show
  - ipc/msg.c:sysvipc_msg_proc_show
  - ipc/shm.c:sysvipc_shm_proc_show
  - ipc/shm.c:sysvipc_shm_proc_show
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_show
```
**Symbols:**

```
ffffffff810bf610-ffffffff810bf644: pid_nr_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
pid_t pid_nr_ns(struct pid *pid, struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810c5b50)
Location: kernel/pid.c:405
Inline: True
Inline callers:
  - kernel/pid.c:__task_pid_nr_ns
  - kernel/pid.c:pid_vnr
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
  - kernel/fork.c:pidfd_show_fdinfo
  - fs/proc/base.c:next_tgid
  - fs/proc/base.c:show_timer
  - fs/proc/array.c:children_seq_show
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:task_state
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/file.c:fuse_setlk
  - fs/fuse/file.c:fuse_getlk
  - ipc/msg.c:sysvipc_msg_proc_show
  - ipc/msg.c:sysvipc_msg_proc_show
  - ipc/shm.c:sysvipc_shm_proc_show
  - ipc/shm.c:sysvipc_shm_proc_show
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_show
```
**Symbols:**

```
ffffffff810c59e0-ffffffff810c5a14: pid_nr_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
pid_t pid_nr_ns(struct pid *pid, struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810cd3cc)
Location: kernel/pid.c:471
Inline: True
Inline callers:
  - kernel/pid.c:__task_pid_nr_ns
  - kernel/pid.c:pid_vnr
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
  - kernel/fork.c:pidfd_show_fdinfo
  - kernel/bpf/task_iter.c:task_seq_get_next
  - fs/proc/base.c:next_tgid
  - fs/proc/base.c:show_timer
  - fs/proc/array.c:children_seq_show
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:task_state
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/file.c:fuse_setlk
  - fs/fuse/file.c:fuse_getlk
  - ipc/msg.c:sysvipc_msg_proc_show
  - ipc/msg.c:sysvipc_msg_proc_show
  - ipc/shm.c:sysvipc_shm_proc_show
  - ipc/shm.c:sysvipc_shm_proc_show
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_show
```
**Symbols:**

```
ffffffff810cd310-ffffffff810cd344: pid_nr_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
pid_t pid_nr_ns(struct pid *pid, struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810c7f6e)
Location: kernel/pid.c:472
Inline: True
Inline callers:
  - kernel/pid.c:__task_pid_nr_ns
  - kernel/pid.c:pid_vnr
Direct callers:
  - kernel/fork.c:kernel_clone
  - kernel/fork.c:kernel_clone
  - kernel/fork.c:pidfd_show_fdinfo
  - kernel/bpf/task_iter.c:task_seq_get_next
  - fs/proc/base.c:next_tgid
  - fs/proc/base.c:show_timer
  - fs/proc/array.c:children_seq_show
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:task_state
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/file.c:fuse_setlk
  - fs/fuse/file.c:fuse_getlk
  - ipc/msg.c:sysvipc_msg_proc_show
  - ipc/msg.c:sysvipc_msg_proc_show
  - ipc/shm.c:sysvipc_shm_proc_show
  - ipc/shm.c:sysvipc_shm_proc_show
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_show
```
**Symbols:**

```
ffffffff810c7e20-ffffffff810c7e54: pid_nr_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
pid_t pid_nr_ns(struct pid *pid, struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810c9a0e)
Location: kernel/pid.c:472
Inline: True
Inline callers:
  - kernel/pid.c:__task_pid_nr_ns
  - kernel/pid.c:pid_vnr
Direct callers:
  - kernel/fork.c:kernel_clone
  - kernel/fork.c:kernel_clone
  - kernel/fork.c:pidfd_show_fdinfo
  - kernel/bpf/task_iter.c:task_seq_get_next
  - fs/proc/base.c:next_tgid
  - fs/proc/base.c:show_timer
  - fs/proc/array.c:children_seq_show
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:task_state
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/file.c:fuse_setlk
  - fs/fuse/file.c:fuse_getlk
  - ipc/msg.c:sysvipc_msg_proc_show
  - ipc/msg.c:sysvipc_msg_proc_show
  - ipc/shm.c:sysvipc_shm_proc_show
  - ipc/shm.c:sysvipc_shm_proc_show
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_show
```
**Symbols:**

```
ffffffff810c98c0-ffffffff810c98f4: pid_nr_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
pid_t pid_nr_ns(struct pid *pid, struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810dc974)
Location: kernel/pid.c:472
Inline: True
Inline callers:
  - kernel/pid.c:__task_pid_nr_ns
  - kernel/pid.c:pid_vnr
Direct callers:
  - kernel/fork.c:kernel_clone
  - kernel/fork.c:kernel_clone
  - kernel/fork.c:pidfd_show_fdinfo
  - kernel/bpf/task_iter.c:task_seq_get_next
  - fs/proc/base.c:next_tgid
  - fs/proc/base.c:show_timer
  - fs/proc/array.c:children_seq_show
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:task_state
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/file.c:fuse_setlk
  - fs/fuse/file.c:fuse_getlk
  - ipc/msg.c:sysvipc_msg_proc_show
  - ipc/msg.c:sysvipc_msg_proc_show
  - ipc/shm.c:sysvipc_shm_proc_show
  - ipc/shm.c:sysvipc_shm_proc_show
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_show
```
**Symbols:**

```
ffffffff810dc820-ffffffff810dc854: pid_nr_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
pid_t pid_nr_ns(struct pid *pid, struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810f616a)
Location: kernel/pid.c:472
Inline: True
Inline callers:
  - kernel/pid.c:__task_pid_nr_ns
  - kernel/pid.c:pid_vnr
Direct callers:
  - kernel/fork.c:kernel_clone
  - kernel/fork.c:kernel_clone
  - kernel/fork.c:pidfd_show_fdinfo
  - kernel/bpf/task_iter.c:task_seq_get_next
  - fs/proc/base.c:next_tgid
  - fs/proc/base.c:show_timer
  - fs/proc/array.c:children_seq_show
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:task_state
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/file.c:fuse_setlk
  - fs/fuse/file.c:fuse_getlk
  - ipc/msg.c:sysvipc_msg_proc_show
  - ipc/msg.c:sysvipc_msg_proc_show
  - ipc/shm.c:sysvipc_shm_proc_show
  - ipc/shm.c:sysvipc_shm_proc_show
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_show
```
**Symbols:**

```
ffffffff810f5fc0-ffffffff810f6004: pid_nr_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
pid_t pid_nr_ns(struct pid *pid, struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff8111871a)
Location: kernel/pid.c:472
Inline: True
Inline callers:
  - kernel/pid.c:__task_pid_nr_ns
  - kernel/pid.c:pid_vnr
Direct callers:
  - kernel/fork.c:kernel_clone
  - kernel/fork.c:kernel_clone
  - kernel/fork.c:pidfd_show_fdinfo
  - kernel/bpf/task_iter.c:bpf_iter_attach_task
  - kernel/bpf/task_iter.c:task_seq_get_next
  - fs/proc/base.c:next_tgid
  - fs/proc/base.c:show_timer
  - fs/proc/array.c:children_seq_show
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:task_state
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/file.c:fuse_setlk
  - fs/fuse/file.c:fuse_getlk
  - ipc/msg.c:sysvipc_msg_proc_show
  - ipc/msg.c:sysvipc_msg_proc_show
  - ipc/shm.c:sysvipc_shm_proc_show
  - ipc/shm.c:sysvipc_shm_proc_show
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_show
```
**Symbols:**

```
ffffffff81118520-ffffffff81118564: pid_nr_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
pid_t pid_nr_ns(struct pid *pid, struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff8112595a)
Location: kernel/pid.c:475
Inline: True
Inline callers:
  - kernel/pid.c:__task_pid_nr_ns
  - kernel/pid.c:pid_vnr
Direct callers:
  - kernel/fork.c:kernel_clone
  - kernel/fork.c:kernel_clone
  - kernel/fork.c:pidfd_show_fdinfo
  - kernel/bpf/task_iter.c:bpf_iter_attach_task
  - kernel/bpf/task_iter.c:task_seq_get_next
  - fs/proc/base.c:next_tgid
  - fs/proc/base.c:show_timer
  - fs/proc/array.c:children_seq_show
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:task_state
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/file.c:fuse_setlk
  - fs/fuse/file.c:fuse_getlk
  - ipc/msg.c:sysvipc_msg_proc_show
  - ipc/msg.c:sysvipc_msg_proc_show
  - ipc/shm.c:sysvipc_shm_proc_show
  - ipc/shm.c:sysvipc_shm_proc_show
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_show
```
**Symbols:**

```
ffffffff81125760-ffffffff811257a4: pid_nr_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
pid_t pid_nr_ns(struct pid *pid, struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff8112ff5a)
Location: kernel/pid.c:475
Inline: True
Inline callers:
  - kernel/pid.c:__task_pid_nr_ns
  - kernel/pid.c:pid_vnr
Direct callers:
  - kernel/fork.c:kernel_clone
  - kernel/fork.c:kernel_clone
  - kernel/fork.c:pidfd_show_fdinfo
  - kernel/bpf/task_iter.c:bpf_iter_attach_task
  - kernel/bpf/task_iter.c:task_seq_get_next
  - fs/proc/base.c:next_tgid
  - fs/proc/base.c:show_timer
  - fs/proc/array.c:children_seq_show
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:task_state
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/file.c:fuse_setlk
  - fs/fuse/file.c:fuse_getlk
  - ipc/msg.c:sysvipc_msg_proc_show
  - ipc/msg.c:sysvipc_msg_proc_show
  - ipc/shm.c:sysvipc_shm_proc_show
  - ipc/shm.c:sysvipc_shm_proc_show
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_show
```
**Symbols:**

```
ffffffff8112fd60-ffffffff8112fda4: pid_nr_ns (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
pid_t pid_nr_ns(struct pid *pid, struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffff800010124068)
Location: kernel/pid.c:405
Inline: True
Inline callers:
  - kernel/pid.c:__task_pid_nr_ns
  - kernel/pid.c:pid_vnr
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
  - kernel/fork.c:pidfd_show_fdinfo
  - fs/proc/base.c:next_tgid
  - fs/proc/base.c:show_timer
  - fs/proc/array.c:children_seq_show
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:task_state
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/file.c:fuse_setlk
  - fs/fuse/file.c:fuse_getlk
  - ipc/msg.c:sysvipc_msg_proc_show
  - ipc/msg.c:sysvipc_msg_proc_show
  - ipc/shm.c:sysvipc_shm_proc_show
  - ipc/shm.c:sysvipc_shm_proc_show
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_show
```
**Symbols:**

```
ffff800010123f08-ffff800010123f70: pid_nr_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
pid_t pid_nr_ns(struct pid *pid, struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (c03773b4)
Location: kernel/pid.c:405
Inline: True
Inline callers:
  - kernel/pid.c:__task_pid_nr_ns
  - kernel/pid.c:pid_vnr
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
  - kernel/fork.c:pidfd_show_fdinfo
  - fs/proc/base.c:next_tgid
  - fs/proc/base.c:show_timer
  - fs/proc/array.c:children_seq_show
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:task_state
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/file.c:fuse_setlk
  - fs/fuse/file.c:fuse_getlk
  - ipc/msg.c:sysvipc_msg_proc_show
  - ipc/msg.c:sysvipc_msg_proc_show
  - ipc/shm.c:sysvipc_shm_proc_show
  - ipc/shm.c:sysvipc_shm_proc_show
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_show
```
**Symbols:**

```
c0377288-c03772d4: pid_nr_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
pid_t pid_nr_ns(struct pid *pid, struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (c00000000016ddb8)
Location: kernel/pid.c:405
Inline: True
Inline callers:
  - kernel/pid.c:__task_pid_nr_ns
  - kernel/pid.c:pid_vnr
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
  - kernel/fork.c:pidfd_show_fdinfo
  - fs/proc/base.c:next_tgid
  - fs/proc/base.c:show_timer
  - fs/proc/array.c:children_seq_show
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:task_state
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/file.c:fuse_setlk
  - fs/fuse/file.c:fuse_getlk
  - ipc/msg.c:sysvipc_msg_proc_show
  - ipc/msg.c:sysvipc_msg_proc_show
  - ipc/shm.c:sysvipc_shm_proc_show
  - ipc/shm.c:sysvipc_shm_proc_show
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_show
```
**Symbols:**

```
c00000000016dbc0-c00000000016dc08: pid_nr_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
pid_t pid_nr_ns(struct pid *pid, struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffe0000dc3ac)
Location: kernel/pid.c:405
Inline: True
Inline callers:
  - kernel/pid.c:__task_pid_nr_ns
  - kernel/pid.c:pid_vnr
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
  - kernel/fork.c:pidfd_show_fdinfo
  - fs/proc/base.c:next_tgid
  - fs/proc/base.c:show_timer
  - fs/proc/array.c:children_seq_show
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:task_state
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/file.c:fuse_setlk
  - fs/fuse/file.c:fuse_getlk
  - ipc/msg.c:sysvipc_msg_proc_show
  - ipc/msg.c:sysvipc_msg_proc_show
  - ipc/shm.c:sysvipc_shm_proc_show
  - ipc/shm.c:sysvipc_shm_proc_show
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_show
```
**Symbols:**

```
ffffffe0000dc202-ffffffe0000dc252: pid_nr_ns (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
pid_t pid_nr_ns(struct pid *pid, struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810bfed0)
Location: kernel/pid.c:405
Inline: True
Inline callers:
  - kernel/pid.c:__task_pid_nr_ns
  - kernel/pid.c:pid_vnr
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
  - kernel/fork.c:pidfd_show_fdinfo
  - fs/proc/base.c:next_tgid
  - fs/proc/base.c:show_timer
  - fs/proc/array.c:children_seq_show
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:task_state
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/file.c:fuse_setlk
  - fs/fuse/file.c:fuse_getlk
  - ipc/msg.c:sysvipc_msg_proc_show
  - ipc/msg.c:sysvipc_msg_proc_show
  - ipc/shm.c:sysvipc_shm_proc_show
  - ipc/shm.c:sysvipc_shm_proc_show
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_show
```
**Symbols:**

```
ffffffff810bfd60-ffffffff810bfd94: pid_nr_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
pid_t pid_nr_ns(struct pid *pid, struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810ae6e0)
Location: kernel/pid.c:405
Inline: True
Inline callers:
  - kernel/pid.c:__task_pid_nr_ns
  - kernel/pid.c:pid_vnr
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
  - kernel/fork.c:pidfd_show_fdinfo
  - fs/proc/base.c:next_tgid
  - fs/proc/base.c:show_timer
  - fs/proc/array.c:children_seq_show
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:task_state
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/file.c:fuse_setlk
  - fs/fuse/file.c:fuse_getlk
  - ipc/msg.c:sysvipc_msg_proc_show
  - ipc/msg.c:sysvipc_msg_proc_show
  - ipc/shm.c:sysvipc_shm_proc_show
  - ipc/shm.c:sysvipc_shm_proc_show
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_show
```
**Symbols:**

```
ffffffff810ae570-ffffffff810ae5a4: pid_nr_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
pid_t pid_nr_ns(struct pid *pid, struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810bf420)
Location: kernel/pid.c:405
Inline: True
Inline callers:
  - kernel/pid.c:__task_pid_nr_ns
  - kernel/pid.c:pid_vnr
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
  - kernel/fork.c:pidfd_show_fdinfo
  - fs/proc/base.c:next_tgid
  - fs/proc/base.c:show_timer
  - fs/proc/array.c:children_seq_show
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:task_state
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/file.c:fuse_setlk
  - fs/fuse/file.c:fuse_getlk
  - ipc/msg.c:sysvipc_msg_proc_show
  - ipc/msg.c:sysvipc_msg_proc_show
  - ipc/shm.c:sysvipc_shm_proc_show
  - ipc/shm.c:sysvipc_shm_proc_show
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_show
```
**Symbols:**

```
ffffffff810bf2b0-ffffffff810bf2e4: pid_nr_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
pid_t pid_nr_ns(struct pid *pid, struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810c7892)
Location: kernel/pid.c:405
Inline: True
Inline callers:
  - kernel/pid.c:__task_pid_nr_ns
  - kernel/pid.c:pid_vnr
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
  - kernel/fork.c:pidfd_show_fdinfo
  - fs/proc/base.c:next_tgid
  - fs/proc/base.c:show_timer
  - fs/proc/array.c:children_seq_show
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:task_state
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/file.c:fuse_setlk
  - fs/fuse/file.c:fuse_getlk
  - ipc/msg.c:sysvipc_msg_proc_show
  - ipc/msg.c:sysvipc_msg_proc_show
  - ipc/shm.c:sysvipc_shm_proc_show
  - ipc/shm.c:sysvipc_shm_proc_show
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_show
```
**Symbols:**

```
ffffffff810c75e0-ffffffff810c7614: pid_nr_ns (STB_GLOBAL)
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
