# Function: <code>get_pid_ns</code>

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
In kernel/pid.c (ffffffff8109e283)
Location: include/linux/pid_namespace.h:55
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/cgroup.c (ffffffff81118da3)
Location: include/linux/pid_namespace.h:55
Inline: True
Inline callers:
  - kernel/cgroup.c:pidlist_array_load
```
```
In kernel/pid_namespace.c (ffffffff8111f747)
Location: include/linux/pid_namespace.h:55
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_get
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/events/core.c (ffffffff8117ea33)
Location: include/linux/pid_namespace.h:55
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In fs/proc/root.c (ffffffff8127a0e1)
Location: include/linux/pid_namespace.h:55
Inline: True
```
```
In fs/fuse/inode.c (ffffffff8131ac43)
Location: include/linux/pid_namespace.h:55
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff817f6342)
Location: include/linux/pid_namespace.h:55
Inline: True
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
In kernel/pid.c (ffffffff810a1931)
Location: include/linux/pid_namespace.h:55
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/cgroup.c (ffffffff81120ad1)
Location: include/linux/pid_namespace.h:55
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_pidlist_start
```
```
In kernel/pid_namespace.c (ffffffff8112778c)
Location: include/linux/pid_namespace.h:55
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_get
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/events/core.c (ffffffff81190512)
Location: include/linux/pid_namespace.h:55
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In fs/proc/inode.c (ffffffff812a6a1b)
Location: include/linux/pid_namespace.h:55
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_fill_super
```
```
In fs/fuse/inode.c (ffffffff8134f713)
Location: include/linux/pid_namespace.h:55
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81865502)
Location: include/linux/pid_namespace.h:55
Inline: True
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
In kernel/pid.c (ffffffff810a69f1)
Location: include/linux/pid_namespace.h:56
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/cgroup.c (ffffffff81128fbe)
Location: include/linux/pid_namespace.h:56
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_pidlist_start
```
```
In kernel/pid_namespace.c (ffffffff81131313)
Location: include/linux/pid_namespace.h:56
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_get_parent
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_get
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/events/core.c (ffffffff8119f3d2)
Location: include/linux/pid_namespace.h:56
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In fs/proc/inode.c (ffffffff812bc2fb)
Location: include/linux/pid_namespace.h:56
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_fill_super
```
```
In fs/fuse/inode.c (ffffffff8136502d)
Location: include/linux/pid_namespace.h:56
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81897bcf)
Location: include/linux/pid_namespace.h:56
Inline: True
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
In kernel/pid.c (ffffffff810a395b)
Location: include/linux/pid_namespace.h:62
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8112a4a3)
Location: include/linux/pid_namespace.h:62
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
```
```
In kernel/pid_namespace.c (ffffffff81132673)
Location: include/linux/pid_namespace.h:62
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_get_parent
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:pidns_get
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/events/core.c (ffffffff811a5e34)
Location: include/linux/pid_namespace.h:62
Inline: True
```
```
In fs/proc/inode.c (ffffffff812c96b7)
Location: include/linux/pid_namespace.h:62
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_fill_super
```
```
In fs/fuse/inode.c (ffffffff8137973c)
Location: include/linux/pid_namespace.h:62
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff818bdfa7)
Location: include/linux/pid_namespace.h:62
Inline: True
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
In kernel/pid.c (ffffffff810aa122)
Location: include/linux/pid_namespace.h:55
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81137124)
Location: include/linux/pid_namespace.h:55
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
```
In kernel/pid_namespace.c (ffffffff8113f770)
Location: include/linux/pid_namespace.h:55
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_get_parent
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:pidns_get
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/events/core.c (ffffffff811b9a24)
Location: include/linux/pid_namespace.h:55
Inline: True
```
```
In fs/proc/inode.c (ffffffff812edf37)
Location: include/linux/pid_namespace.h:55
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_fill_super
```
```
In fs/fuse/inode.c (ffffffff8139e5dc)
Location: include/linux/pid_namespace.h:55
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff819410d7)
Location: include/linux/pid_namespace.h:55
Inline: True
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
In kernel/pid.c (ffffffff810b0d50)
Location: include/linux/pid_namespace.h:55
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81145920)
Location: include/linux/pid_namespace.h:55
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
```
In kernel/pid_namespace.c (ffffffff8114dfc0)
Location: include/linux/pid_namespace.h:55
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_get_parent
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:pidns_get
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/events/core.c (ffffffff811d8dac)
Location: include/linux/pid_namespace.h:55
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In fs/proc/inode.c (ffffffff8131afa7)
Location: include/linux/pid_namespace.h:55
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_fill_super
```
```
In fs/fuse/inode.c (ffffffff813cd98d)
Location: include/linux/pid_namespace.h:55
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
```
```
In ipc/util.c (ffffffff813d5f2a)
Location: include/linux/pid_namespace.h:55
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_open
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
In kernel/pid.c (ffffffff810b9e47)
Location: include/linux/pid_namespace.h:55
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff811514e0)
Location: include/linux/pid_namespace.h:55
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
```
In kernel/pid_namespace.c (ffffffff8115ad70)
Location: include/linux/pid_namespace.h:55
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_get_parent
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:pidns_get
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/events/core.c (ffffffff811e92a4)
Location: include/linux/pid_namespace.h:55
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In fs/proc/inode.c (ffffffff81332027)
Location: include/linux/pid_namespace.h:55
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_fill_super
```
```
In fs/fuse/inode.c (ffffffff813e6d6d)
Location: include/linux/pid_namespace.h:55
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
```
```
In ipc/util.c (ffffffff813f05ea)
Location: include/linux/pid_namespace.h:55
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_open
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
In kernel/pid.c (ffffffff810bfd35)
Location: include/linux/pid_namespace.h:55
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8115c7ad)
Location: include/linux/pid_namespace.h:55
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
```
In kernel/pid_namespace.c (ffffffff81167426)
Location: include/linux/pid_namespace.h:55
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_get_parent
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:pidns_get
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/events/core.c (ffffffff812025c6)
Location: include/linux/pid_namespace.h:55
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In fs/proc/root.c (ffffffff8135a340)
Location: include/linux/pid_namespace.h:55
Inline: True
Inline callers:
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/proc/root.c:proc_init_fs_context
  - fs/proc/root.c:proc_fill_super
```
```
In fs/fuse/inode.c (ffffffff81412d9d)
Location: include/linux/pid_namespace.h:55
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
```
```
In ipc/util.c (ffffffff8141c90a)
Location: include/linux/pid_namespace.h:55
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_open
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
In kernel/pid.c (ffffffff810c6105)
Location: include/linux/pid_namespace.h:55
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81167f59)
Location: include/linux/pid_namespace.h:55
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
```
In kernel/pid_namespace.c (ffffffff811732e6)
Location: include/linux/pid_namespace.h:55
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_get_parent
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:pidns_get
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/events/core.c (ffffffff8120f3f6)
Location: include/linux/pid_namespace.h:55
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In fs/proc/root.c (ffffffff81372570)
Location: include/linux/pid_namespace.h:55
Inline: True
Inline callers:
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/proc/root.c:proc_init_fs_context
  - fs/proc/root.c:proc_fill_super
```
```
In fs/fuse/inode.c (ffffffff8142ca82)
Location: include/linux/pid_namespace.h:55
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
```
```
In ipc/util.c (ffffffff8143675a)
Location: include/linux/pid_namespace.h:55
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_open
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
In kernel/pid.c (ffffffff810cdf3f)
Location: include/linux/pid_namespace.h:43
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/nsproxy.c (ffffffff810d61f9)
Location: include/linux/pid_namespace.h:43
Inline: True
Inline callers:
  - kernel/nsproxy.c:validate_nsset
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81179ad0)
Location: include/linux/pid_namespace.h:43
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_find_create
```
```
In kernel/pid_namespace.c (ffffffff811853fc)
Location: include/linux/pid_namespace.h:43
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_get_parent
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:pidns_get
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/pid_namespace.c:create_pid_namespace
```
```
In kernel/bpf/task_iter.c (ffffffff81216320)
Location: include/linux/pid_namespace.h:43
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:init_seq_pidns
```
```
In kernel/events/core.c (ffffffff8123a5df)
Location: include/linux/pid_namespace.h:43
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In fs/proc/root.c (ffffffff813ba834)
Location: include/linux/pid_namespace.h:43
Inline: True
Inline callers:
  - fs/proc/root.c:proc_init_fs_context
  - fs/proc/root.c:proc_fill_super
```
```
In fs/fuse/inode.c (ffffffff8147d4de)
Location: include/linux/pid_namespace.h:43
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
```
```
In ipc/util.c (ffffffff814867de)
Location: include/linux/pid_namespace.h:43
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_open
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
In kernel/pid.c (ffffffff810c8a1a)
Location: include/linux/pid_namespace.h:41
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/nsproxy.c (ffffffff810d0d76)
Location: include/linux/pid_namespace.h:41
Inline: True
Inline callers:
  - kernel/nsproxy.c:validate_nsset
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81176840)
Location: include/linux/pid_namespace.h:41
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_find_create
```
```
In kernel/pid_namespace.c (ffffffff811824fc)
Location: include/linux/pid_namespace.h:41
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_get_parent
  - kernel/pid_namespace.c:pidns_get_parent
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:pidns_get
  - kernel/pid_namespace.c:pidns_get
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/pid_namespace.c:create_pid_namespace
  - kernel/pid_namespace.c:create_pid_namespace
```
```
In kernel/bpf/task_iter.c (ffffffff81218360)
Location: include/linux/pid_namespace.h:41
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:init_seq_pidns
```
```
In kernel/events/core.c (ffffffff81243a08)
Location: include/linux/pid_namespace.h:41
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In fs/proc/root.c (ffffffff813cc334)
Location: include/linux/pid_namespace.h:41
Inline: True
Inline callers:
  - fs/proc/root.c:proc_init_fs_context
  - fs/proc/root.c:proc_init_fs_context
  - fs/proc/root.c:proc_fill_super
  - fs/proc/root.c:proc_fill_super
```
```
In fs/fuse/inode.c (ffffffff8149888c)
Location: include/linux/pid_namespace.h:41
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
```
```
In ipc/util.c (ffffffff814a3e8b)
Location: include/linux/pid_namespace.h:41
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_open
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
In kernel/pid.c (ffffffff810ca4ba)
Location: include/linux/pid_namespace.h:41
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/nsproxy.c (ffffffff810d2952)
Location: include/linux/pid_namespace.h:41
Inline: True
Inline callers:
  - kernel/nsproxy.c:validate_nsset
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8117753e)
Location: include/linux/pid_namespace.h:41
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
```
In kernel/pid_namespace.c (ffffffff81183649)
Location: include/linux/pid_namespace.h:41
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_get_parent
  - kernel/pid_namespace.c:pidns_get_parent
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:pidns_get
  - kernel/pid_namespace.c:pidns_get
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/pid_namespace.c:create_pid_namespace
  - kernel/pid_namespace.c:create_pid_namespace
```
```
In kernel/bpf/task_iter.c (ffffffff8121b7b0)
Location: include/linux/pid_namespace.h:41
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:init_seq_pidns
```
```
In kernel/events/core.c (ffffffff812489ac)
Location: include/linux/pid_namespace.h:41
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In fs/proc/root.c (ffffffff813d32f4)
Location: include/linux/pid_namespace.h:41
Inline: True
Inline callers:
  - fs/proc/root.c:proc_init_fs_context
  - fs/proc/root.c:proc_init_fs_context
  - fs/proc/root.c:proc_fill_super
  - fs/proc/root.c:proc_fill_super
```
```
In fs/fuse/inode.c (ffffffff8149d91c)
Location: include/linux/pid_namespace.h:41
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
```
```
In ipc/util.c (ffffffff814a9dbb)
Location: include/linux/pid_namespace.h:41
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_open
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
In kernel/pid.c (ffffffff810dd30a)
Location: include/linux/pid_namespace.h:41
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/nsproxy.c (ffffffff810e5a92)
Location: include/linux/pid_namespace.h:41
Inline: True
Inline callers:
  - kernel/nsproxy.c:validate_nsset
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8119ecae)
Location: include/linux/pid_namespace.h:41
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
```
In kernel/pid_namespace.c (ffffffff811ab729)
Location: include/linux/pid_namespace.h:41
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_get_parent
  - kernel/pid_namespace.c:pidns_get_parent
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:pidns_get
  - kernel/pid_namespace.c:pidns_get
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/pid_namespace.c:create_pid_namespace
  - kernel/pid_namespace.c:create_pid_namespace
```
```
In kernel/bpf/task_iter.c (ffffffff812526b0)
Location: include/linux/pid_namespace.h:41
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:init_seq_pidns
```
```
In kernel/events/core.c (ffffffff812837b0)
Location: include/linux/pid_namespace.h:41
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In fs/proc/root.c (ffffffff81424844)
Location: include/linux/pid_namespace.h:41
Inline: True
Inline callers:
  - fs/proc/root.c:proc_init_fs_context
  - fs/proc/root.c:proc_init_fs_context
  - fs/proc/root.c:proc_fill_super
  - fs/proc/root.c:proc_fill_super
```
```
In fs/fuse/inode.c (ffffffff814f53cc)
Location: include/linux/pid_namespace.h:41
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
```
```
In ipc/util.c (ffffffff8150226b)
Location: include/linux/pid_namespace.h:41
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_open
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
In kernel/pid.c (ffffffff810f6c21)
Location: include/linux/pid_namespace.h:41
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/nsproxy.c (ffffffff810ff892)
Location: include/linux/pid_namespace.h:41
Inline: True
Inline callers:
  - kernel/nsproxy.c:validate_nsset
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff811cf45a)
Location: include/linux/pid_namespace.h:41
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
```
In kernel/pid_namespace.c (ffffffff811dcf63)
Location: include/linux/pid_namespace.h:41
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_get_parent
  - kernel/pid_namespace.c:pidns_get_parent
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:pidns_get
  - kernel/pid_namespace.c:pidns_get
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/pid_namespace.c:create_pid_namespace
  - kernel/pid_namespace.c:create_pid_namespace
```
```
In kernel/bpf/task_iter.c (ffffffff8129a680)
Location: include/linux/pid_namespace.h:41
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:init_seq_pidns
```
```
In kernel/events/core.c (ffffffff812d67c4)
Location: include/linux/pid_namespace.h:41
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In fs/proc/root.c (ffffffff8149d454)
Location: include/linux/pid_namespace.h:41
Inline: True
Inline callers:
  - fs/proc/root.c:proc_init_fs_context
  - fs/proc/root.c:proc_init_fs_context
  - fs/proc/root.c:proc_fill_super
  - fs/proc/root.c:proc_fill_super
```
```
In fs/fuse/inode.c (ffffffff8158547c)
Location: include/linux/pid_namespace.h:41
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
```
```
In ipc/util.c (ffffffff815938d8)
Location: include/linux/pid_namespace.h:41
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_open
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
In kernel/pid.c (ffffffff81119301)
Location: include/linux/pid_namespace.h:41
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/nsproxy.c (ffffffff811245c2)
Location: include/linux/pid_namespace.h:41
Inline: True
Inline callers:
  - kernel/nsproxy.c:validate_nsset
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81212dea)
Location: include/linux/pid_namespace.h:41
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
```
In kernel/pid_namespace.c (ffffffff81222903)
Location: include/linux/pid_namespace.h:41
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_get_parent
  - kernel/pid_namespace.c:pidns_get_parent
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:pidns_get
  - kernel/pid_namespace.c:pidns_get
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/pid_namespace.c:create_pid_namespace
  - kernel/pid_namespace.c:create_pid_namespace
```
```
In kernel/bpf/task_iter.c (ffffffff812f6805)
Location: include/linux/pid_namespace.h:41
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:init_seq_pidns
```
```
In kernel/events/core.c (ffffffff8133f59d)
Location: include/linux/pid_namespace.h:41
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In fs/proc/root.c (ffffffff81531f54)
Location: include/linux/pid_namespace.h:41
Inline: True
Inline callers:
  - fs/proc/root.c:proc_init_fs_context
  - fs/proc/root.c:proc_init_fs_context
  - fs/proc/root.c:proc_fill_super
  - fs/proc/root.c:proc_fill_super
```
```
In fs/fuse/inode.c (ffffffff8162b67c)
Location: include/linux/pid_namespace.h:41
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
```
```
In ipc/util.c (ffffffff8163c458)
Location: include/linux/pid_namespace.h:41
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_open
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
In kernel/pid.c (ffffffff811267d1)
Location: include/linux/pid_namespace.h:51
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/nsproxy.c (ffffffff811318c2)
Location: include/linux/pid_namespace.h:51
Inline: True
Inline callers:
  - kernel/nsproxy.c:validate_nsset
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff812286fa)
Location: include/linux/pid_namespace.h:51
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
```
In kernel/pid_namespace.c (ffffffff81238f63)
Location: include/linux/pid_namespace.h:51
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_get_parent
  - kernel/pid_namespace.c:pidns_get_parent
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:pidns_get
  - kernel/pid_namespace.c:pidns_get
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/pid_namespace.c:create_pid_namespace
  - kernel/pid_namespace.c:create_pid_namespace
```
```
In kernel/bpf/task_iter.c (ffffffff813246d5)
Location: include/linux/pid_namespace.h:51
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:init_seq_pidns
```
```
In kernel/events/core.c (ffffffff813706d3)
Location: include/linux/pid_namespace.h:51
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In fs/proc/root.c (ffffffff8156a124)
Location: include/linux/pid_namespace.h:51
Inline: True
Inline callers:
  - fs/proc/root.c:proc_init_fs_context
  - fs/proc/root.c:proc_init_fs_context
  - fs/proc/root.c:proc_fill_super
  - fs/proc/root.c:proc_fill_super
```
```
In fs/fuse/inode.c (ffffffff816638ac)
Location: include/linux/pid_namespace.h:51
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
```
```
In ipc/util.c (ffffffff816748d8)
Location: include/linux/pid_namespace.h:51
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_open
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
In kernel/pid.c (ffffffff81130dc1)
Location: include/linux/pid_namespace.h:51
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/nsproxy.c (ffffffff8113c694)
Location: include/linux/pid_namespace.h:51
Inline: True
Inline callers:
  - kernel/nsproxy.c:validate_nsset
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8124050e)
Location: include/linux/pid_namespace.h:51
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
```
In kernel/pid_namespace.c (ffffffff81252c33)
Location: include/linux/pid_namespace.h:51
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_get_parent
  - kernel/pid_namespace.c:pidns_get_parent
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:pidns_get
  - kernel/pid_namespace.c:pidns_get
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/pid_namespace.c:create_pid_namespace
  - kernel/pid_namespace.c:create_pid_namespace
```
```
In kernel/bpf/task_iter.c (ffffffff81348945)
Location: include/linux/pid_namespace.h:51
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:init_seq_pidns
```
```
In kernel/events/core.c (ffffffff813999d3)
Location: include/linux/pid_namespace.h:51
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In fs/proc/root.c (ffffffff815a27a3)
Location: include/linux/pid_namespace.h:51
Inline: True
Inline callers:
  - fs/proc/root.c:proc_init_fs_context
  - fs/proc/root.c:proc_init_fs_context
  - fs/proc/root.c:proc_fill_super
  - fs/proc/root.c:proc_fill_super
```
```
In fs/fuse/inode.c (ffffffff8169d99c)
Location: include/linux/pid_namespace.h:51
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
```
```
In ipc/util.c (ffffffff816b0c98)
Location: include/linux/pid_namespace.h:51
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_open
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
In kernel/pid.c (ffff80001012473c)
Location: include/linux/pid_namespace.h:55
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/cgroup/cgroup-v1.c (ffff8000101daa7c)
Location: include/linux/pid_namespace.h:55
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
```
In kernel/pid_namespace.c (ffff8000101e7170)
Location: include/linux/pid_namespace.h:55
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_get_parent
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:pidns_get
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/events/core.c (ffff8000102973b0)
Location: include/linux/pid_namespace.h:55
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In fs/proc/root.c (ffff80001043c99c)
Location: include/linux/pid_namespace.h:55
Inline: True
Inline callers:
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/proc/root.c:proc_init_fs_context
  - fs/proc/root.c:proc_fill_super
```
```
In fs/fuse/inode.c (ffff80001051242c)
Location: include/linux/pid_namespace.h:55
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
```
```
In ipc/util.c (ffff80001051cc2c)
Location: include/linux/pid_namespace.h:55
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_open
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
In kernel/pid.c (c0377904)
Location: include/linux/pid_namespace.h:55
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/cgroup/cgroup-v1.c (c041d364)
Location: include/linux/pid_namespace.h:55
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
```
```
In kernel/pid_namespace.c (c0427608)
Location: include/linux/pid_namespace.h:55
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_get_parent
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:pidns_get
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/events/core.c (c04c753c)
Location: include/linux/pid_namespace.h:55
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In fs/proc/root.c (c06029d8)
Location: include/linux/pid_namespace.h:55
Inline: True
Inline callers:
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/proc/root.c:proc_init_fs_context
  - fs/proc/root.c:proc_fill_super
```
```
In fs/fuse/inode.c (c06cc124)
Location: include/linux/pid_namespace.h:55
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
```
```
In ipc/util.c (c06d9050)
Location: include/linux/pid_namespace.h:55
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_open
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
In kernel/pid.c (c00000000016e584)
Location: include/linux/pid_namespace.h:55
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/cgroup/cgroup-v1.c (c000000000248ba8)
Location: include/linux/pid_namespace.h:55
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
```
In kernel/pid_namespace.c (c0000000002578b0)
Location: include/linux/pid_namespace.h:55
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_get_parent
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:pidns_get
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/events/core.c (c000000000346c94)
Location: include/linux/pid_namespace.h:55
Inline: True
```
```
In fs/proc/root.c (c00000000055070c)
Location: include/linux/pid_namespace.h:55
Inline: True
Inline callers:
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/proc/root.c:proc_init_fs_context
  - fs/proc/root.c:proc_fill_super
```
```
In fs/fuse/inode.c (c000000000658464)
Location: include/linux/pid_namespace.h:55
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
```
```
In ipc/util.c (c000000000665a30)
Location: include/linux/pid_namespace.h:55
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_open
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
In kernel/pid.c (ffffffe0000dc858)
Location: include/linux/pid_namespace.h:55
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/cgroup/cgroup-v1.c (ffffffe000152fe0)
Location: include/linux/pid_namespace.h:55
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
```
In kernel/pid_namespace.c (ffffffe00015c720)
Location: include/linux/pid_namespace.h:55
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_get_parent
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:pidns_get
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/events/core.c (ffffffe0001c9eb8)
Location: include/linux/pid_namespace.h:55
Inline: True
```
```
In fs/proc/root.c (ffffffe0002d4af0)
Location: include/linux/pid_namespace.h:55
Inline: True
Inline callers:
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/proc/root.c:proc_init_fs_context
  - fs/proc/root.c:proc_fill_super
```
```
In fs/fuse/inode.c (ffffffe00037b180)
Location: include/linux/pid_namespace.h:55
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
```
```
In ipc/util.c (ffffffe0003845e0)
Location: include/linux/pid_namespace.h:55
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_open
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
In kernel/pid.c (ffffffff810c0485)
Location: include/linux/pid_namespace.h:55
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81160579)
Location: include/linux/pid_namespace.h:55
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
```
In kernel/pid_namespace.c (ffffffff8116b906)
Location: include/linux/pid_namespace.h:55
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_get_parent
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:pidns_get
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/events/core.c (ffffffff81207a16)
Location: include/linux/pid_namespace.h:55
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In fs/proc/root.c (ffffffff8136ab50)
Location: include/linux/pid_namespace.h:55
Inline: True
Inline callers:
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/proc/root.c:proc_init_fs_context
  - fs/proc/root.c:proc_fill_super
```
```
In fs/fuse/inode.c (ffffffff81425062)
Location: include/linux/pid_namespace.h:55
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
```
```
In ipc/util.c (ffffffff8142ed3a)
Location: include/linux/pid_namespace.h:55
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_open
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
In kernel/pid.c (ffffffff810aec89)
Location: include/linux/pid_namespace.h:55
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff811537e9)
Location: include/linux/pid_namespace.h:55
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
```
In kernel/pid_namespace.c (ffffffff8115eb06)
Location: include/linux/pid_namespace.h:55
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_get_parent
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:pidns_get
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/events/core.c (ffffffff811fab46)
Location: include/linux/pid_namespace.h:55
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In fs/proc/root.c (ffffffff8135b5e0)
Location: include/linux/pid_namespace.h:55
Inline: True
Inline callers:
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/proc/root.c:proc_init_fs_context
  - fs/proc/root.c:proc_fill_super
```
```
In fs/fuse/inode.c (ffffffff81415ae2)
Location: include/linux/pid_namespace.h:55
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
```
```
In ipc/util.c (ffffffff8141f7ba)
Location: include/linux/pid_namespace.h:55
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_open
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
In kernel/pid.c (ffffffff810bf9d5)
Location: include/linux/pid_namespace.h:55
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8115e349)
Location: include/linux/pid_namespace.h:55
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
```
In kernel/pid_namespace.c (ffffffff811696d6)
Location: include/linux/pid_namespace.h:55
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_get_parent
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:pidns_get
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/events/core.c (ffffffff812057e6)
Location: include/linux/pid_namespace.h:55
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In fs/proc/root.c (ffffffff81368620)
Location: include/linux/pid_namespace.h:55
Inline: True
Inline callers:
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/proc/root.c:proc_init_fs_context
  - fs/proc/root.c:proc_fill_super
```
```
In fs/fuse/inode.c (ffffffff81421202)
Location: include/linux/pid_namespace.h:55
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
```
```
In ipc/util.c (ffffffff8142aeda)
Location: include/linux/pid_namespace.h:55
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_open
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
In kernel/pid.c (ffffffff810c7e00)
Location: include/linux/pid_namespace.h:55
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8116b779)
Location: include/linux/pid_namespace.h:55
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
```
In kernel/pid_namespace.c (ffffffff81176de6)
Location: include/linux/pid_namespace.h:55
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_get_parent
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:pidns_get
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/events/core.c (ffffffff81214656)
Location: include/linux/pid_namespace.h:55
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In fs/proc/root.c (ffffffff8137bc70)
Location: include/linux/pid_namespace.h:55
Inline: True
Inline callers:
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/proc/root.c:proc_init_fs_context
  - fs/proc/root.c:proc_fill_super
```
```
In fs/fuse/inode.c (ffffffff81438082)
Location: include/linux/pid_namespace.h:55
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
```
```
In ipc/util.c (ffffffff81441d9a)
Location: include/linux/pid_namespace.h:55
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_open
```
</details>
</li>
</ul>

## Differences
