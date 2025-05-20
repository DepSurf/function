# Function: <code>put_pid_ns</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void put_pid_ns(struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid_namespace.c (ffffffff8111f6d0)
Location: kernel/pid_namespace.c:171
Inline: False
Direct callers:
  - kernel/pid.c:put_pid
  - kernel/pid.c:alloc_pid
  - kernel/nsproxy.c:create_new_namespaces
  - kernel/nsproxy.c:free_nsproxy
  - kernel/cgroup.c:cgroup_pidlist_destroy_work_fn
  - kernel/pid_namespace.c:pidns_put
  - kernel/pid_namespace.c:pidns_install
  - kernel/events/core.c:free_event_rcu
  - kernel/events/core.c:perf_event_alloc
  - fs/proc/root.c:proc_kill_sb
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_release
```
**Symbols:**

```
ffffffff8111f6d0-ffffffff8111f709: put_pid_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void put_pid_ns(struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid_namespace.c (ffffffff81127610)
Location: kernel/pid_namespace.c:171
Inline: False
Direct callers:
  - kernel/pid.c:alloc_pid
  - kernel/pid.c:put_pid
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
  - kernel/cgroup.c:cgroup_pidlist_destroy_work_fn
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_put
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:free_event_rcu
  - fs/proc/root.c:proc_kill_sb
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_release
```
**Symbols:**

```
ffffffff81127610-ffffffff81127659: put_pid_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void put_pid_ns(struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid_namespace.c (ffffffff811311e0)
Location: kernel/pid_namespace.c:190
Inline: False
Direct callers:
  - kernel/pid.c:alloc_pid
  - kernel/pid.c:put_pid
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
  - kernel/cgroup.c:cgroup_pidlist_destroy_work_fn
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_put
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:free_event_rcu
  - fs/proc/root.c:proc_kill_sb
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_release
```
**Symbols:**

```
ffffffff811311e0-ffffffff81131229: put_pid_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void put_pid_ns(struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid_namespace.c (ffffffff811326b0)
Location: kernel/pid_namespace.c:193
Inline: False
Direct callers:
  - kernel/pid.c:alloc_pid
  - kernel/pid.c:put_pid
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_destroy_work_fn
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_put
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/events/core.c:free_event_rcu
  - fs/proc/root.c:proc_kill_sb
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_release
```
**Symbols:**

```
ffffffff811326b0-ffffffff81132747: put_pid_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void put_pid_ns(struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid_namespace.c (ffffffff8113f6ba)
Location: kernel/pid_namespace.c:186
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_put
  - kernel/pid_namespace.c:pidns_for_children_get
Direct callers:
  - kernel/pid.c:alloc_pid
  - kernel/pid.c:put_pid
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_destroy_work_fn
  - kernel/events/core.c:free_event_rcu
  - fs/proc/root.c:proc_kill_sb
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_release
```
**Symbols:**

```
ffffffff8113f560-ffffffff8113f59a: put_pid_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void put_pid_ns(struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid_namespace.c (ffffffff8114e11d)
Location: kernel/pid_namespace.c:167
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_put
  - kernel/pid_namespace.c:pidns_for_children_get
Direct callers:
  - kernel/pid.c:alloc_pid
  - kernel/pid.c:put_pid
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_destroy_work_fn
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:free_event_rcu
  - fs/proc/root.c:proc_kill_sb
  - ipc/util.c:sysvipc_proc_release
```
**Symbols:**

```
ffffffff8114dea0-ffffffff8114deda: put_pid_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void put_pid_ns(struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid_namespace.c (ffffffff8115acbd)
Location: kernel/pid_namespace.c:167
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_put
  - kernel/pid_namespace.c:pidns_for_children_get
Direct callers:
  - kernel/pid.c:alloc_pid
  - kernel/pid.c:put_pid
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_destroy_work_fn
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:free_event_rcu
  - fs/proc/root.c:proc_kill_sb
  - ipc/util.c:sysvipc_proc_release
```
**Symbols:**

```
ffffffff8115ab70-ffffffff8115abaa: put_pid_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void put_pid_ns(struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid_namespace.c (ffffffff81167379)
Location: kernel/pid_namespace.c:168
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_put
  - kernel/pid_namespace.c:pidns_for_children_get
Direct callers:
  - kernel/pid.c:alloc_pid
  - kernel/pid.c:put_pid
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_destroy_work_fn
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:free_event_rcu
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/proc/root.c:proc_kill_sb
  - fs/proc/root.c:proc_fs_context_free
  - ipc/util.c:sysvipc_proc_release
```
**Symbols:**

```
ffffffff81167220-ffffffff8116725d: put_pid_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void put_pid_ns(struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid_namespace.c (ffffffff81173239)
Location: kernel/pid_namespace.c:168
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_put
  - kernel/pid_namespace.c:pidns_for_children_get
Direct callers:
  - kernel/pid.c:alloc_pid
  - kernel/pid.c:put_pid
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_destroy_work_fn
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:free_event_rcu
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/proc/root.c:proc_kill_sb
  - fs/proc/root.c:proc_fs_context_free
  - ipc/util.c:sysvipc_proc_release
```
**Symbols:**

```
ffffffff811730e0-ffffffff8117311d: put_pid_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void put_pid_ns(struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid_namespace.c (ffffffff811851a0)
Location: kernel/pid_namespace.c:159
Inline: False
Direct callers:
  - kernel/pid.c:alloc_pid
  - kernel/nsproxy.c:validate_nsset
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_destroy_work_fn
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_put
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/bpf/task_iter.c:fini_seq_pidns
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:free_event_rcu
  - fs/proc/root.c:proc_kill_sb
  - fs/proc/root.c:proc_fs_context_free
  - ipc/util.c:sysvipc_proc_release
```
**Symbols:**

```
ffffffff811851a0-ffffffff8118522d: put_pid_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void put_pid_ns(struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid_namespace.c (ffffffff81181f90)
Location: kernel/pid_namespace.c:151
Inline: False
Direct callers:
  - kernel/pid.c:alloc_pid
  - kernel/nsproxy.c:validate_nsset
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_destroy_work_fn
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_put
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/bpf/task_iter.c:fini_seq_pidns
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:free_event_rcu
  - fs/proc/root.c:proc_kill_sb
  - fs/proc/root.c:proc_fs_context_free
  - ipc/util.c:sysvipc_proc_release
```
**Symbols:**

```
ffffffff81181f90-ffffffff81182023: put_pid_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void put_pid_ns(struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid_namespace.c (ffffffff811830e0)
Location: kernel/pid_namespace.c:151
Inline: False
Direct callers:
  - kernel/pid.c:alloc_pid
  - kernel/nsproxy.c:validate_nsset
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_destroy_work_fn
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_put
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/bpf/task_iter.c:fini_seq_pidns
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:free_event_rcu
  - fs/proc/root.c:proc_kill_sb
  - fs/proc/root.c:proc_fs_context_free
  - ipc/util.c:sysvipc_proc_release
```
**Symbols:**

```
ffffffff811830e0-ffffffff81183173: put_pid_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void put_pid_ns(struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid_namespace.c (ffffffff811ab190)
Location: kernel/pid_namespace.c:152
Inline: False
Direct callers:
  - kernel/pid.c:alloc_pid
  - kernel/nsproxy.c:validate_nsset
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_destroy_work_fn
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_put
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/bpf/task_iter.c:fini_seq_pidns
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:free_event_rcu
  - fs/proc/root.c:proc_kill_sb
  - fs/proc/root.c:proc_fs_context_free
  - ipc/util.c:sysvipc_proc_release
```
**Symbols:**

```
ffffffff811ab190-ffffffff811ab223: put_pid_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void put_pid_ns(struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid_namespace.c (ffffffff811dc8c0)
Location: kernel/pid_namespace.c:152
Inline: False
Direct callers:
  - kernel/pid.c:alloc_pid
  - kernel/nsproxy.c:validate_nsset
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_destroy_work_fn
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_put
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/bpf/task_iter.c:fini_seq_pidns
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:free_event_rcu
  - fs/proc/root.c:proc_kill_sb
  - fs/proc/root.c:proc_fs_context_free
  - ipc/util.c:sysvipc_proc_release
```
**Symbols:**

```
ffffffff811dc8c0-ffffffff811dc97b: put_pid_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void put_pid_ns(struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid_namespace.c (ffffffff81222200)
Location: kernel/pid_namespace.c:152
Inline: False
Direct callers:
  - kernel/pid.c:alloc_pid
  - kernel/nsproxy.c:validate_nsset
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_destroy_work_fn
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_put
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/bpf/task_iter.c:fini_seq_pidns
  - kernel/events/core.c:free_event_rcu
  - fs/proc/root.c:proc_kill_sb
  - fs/proc/root.c:proc_fs_context_free
  - ipc/util.c:sysvipc_proc_release
```
**Symbols:**

```
ffffffff81222200-ffffffff812222bb: put_pid_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void put_pid_ns(struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid_namespace.c (ffffffff81238830)
Location: kernel/pid_namespace.c:155
Inline: False
Direct callers:
  - kernel/pid.c:alloc_pid
  - kernel/nsproxy.c:validate_nsset
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_destroy_work_fn
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_put
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/bpf/task_iter.c:fini_seq_pidns
  - kernel/events/core.c:free_event_rcu
  - fs/proc/root.c:proc_kill_sb
  - fs/proc/root.c:proc_fs_context_free
  - ipc/util.c:sysvipc_proc_release
```
**Symbols:**

```
ffffffff81238830-ffffffff812388eb: put_pid_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void put_pid_ns(struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid_namespace.c (ffffffff81252500)
Location: kernel/pid_namespace.c:156
Inline: False
Direct callers:
  - kernel/pid.c:alloc_pid
  - kernel/nsproxy.c:validate_nsset
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_destroy_work_fn
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_put
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/bpf/task_iter.c:fini_seq_pidns
  - kernel/events/core.c:free_event_rcu
  - fs/proc/root.c:proc_kill_sb
  - fs/proc/root.c:proc_fs_context_free
  - ipc/util.c:sysvipc_proc_release
```
**Symbols:**

```
ffffffff81252500-ffffffff812525bb: put_pid_ns (STB_GLOBAL)
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
void put_pid_ns(struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid_namespace.c (ffff8000101e7220)
Location: kernel/pid_namespace.c:168
Inline: False
Direct callers:
  - kernel/pid.c:alloc_pid
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_destroy_work_fn
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_put
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:free_event_rcu
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/proc/root.c:proc_kill_sb
  - fs/proc/root.c:proc_fs_context_free
  - ipc/util.c:sysvipc_proc_release
```
**Symbols:**

```
ffff8000101e7220-ffff8000101e72a4: put_pid_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void put_pid_ns(struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid_namespace.c (c042770c)
Location: kernel/pid_namespace.c:168
Inline: False
Direct callers:
  - kernel/pid.c:alloc_pid
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_destroy_work_fn
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_put
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:free_event_rcu
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/proc/root.c:proc_kill_sb
  - fs/proc/root.c:proc_fs_context_free
  - ipc/util.c:sysvipc_proc_release
```
**Symbols:**

```
c042770c-c042777c: put_pid_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void put_pid_ns(struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid_namespace.c (c0000000002579a0)
Location: kernel/pid_namespace.c:168
Inline: False
Direct callers:
  - kernel/pid.c:alloc_pid
  - kernel/pid.c:put_pid
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_destroy_work_fn
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_put
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/events/core.c:free_event_rcu
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/proc/root.c:proc_kill_sb
  - fs/proc/root.c:proc_fs_context_free
  - ipc/util.c:sysvipc_proc_release
```
**Symbols:**

```
c0000000002579a0-c000000000257a88: put_pid_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void put_pid_ns(struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid_namespace.c (ffffffe00015ca1c)
Location: kernel/pid_namespace.c:168
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_put
  - kernel/pid_namespace.c:pidns_for_children_get
Direct callers:
  - kernel/pid.c:alloc_pid
  - kernel/pid.c:put_pid
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_destroy_work_fn
  - kernel/events/core.c:free_event_rcu
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/proc/root.c:proc_kill_sb
  - fs/proc/root.c:proc_fs_context_free
  - ipc/util.c:sysvipc_proc_release
```
**Symbols:**

```
ffffffe00015ca80-ffffffe00015cae0: put_pid_ns (STB_GLOBAL)
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
void put_pid_ns(struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid_namespace.c (ffffffff8116b859)
Location: kernel/pid_namespace.c:168
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_put
  - kernel/pid_namespace.c:pidns_for_children_get
Direct callers:
  - kernel/pid.c:alloc_pid
  - kernel/pid.c:put_pid
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_destroy_work_fn
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:free_event_rcu
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/proc/root.c:proc_kill_sb
  - fs/proc/root.c:proc_fs_context_free
  - ipc/util.c:sysvipc_proc_release
```
**Symbols:**

```
ffffffff8116b700-ffffffff8116b73d: put_pid_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void put_pid_ns(struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid_namespace.c (ffffffff8115ea59)
Location: kernel/pid_namespace.c:168
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_put
  - kernel/pid_namespace.c:pidns_for_children_get
Direct callers:
  - kernel/pid.c:alloc_pid
  - kernel/pid.c:put_pid
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_destroy_work_fn
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:free_event_rcu
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/proc/root.c:proc_kill_sb
  - fs/proc/root.c:proc_fs_context_free
  - ipc/util.c:sysvipc_proc_release
```
**Symbols:**

```
ffffffff8115e900-ffffffff8115e93d: put_pid_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void put_pid_ns(struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid_namespace.c (ffffffff81169629)
Location: kernel/pid_namespace.c:168
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_put
  - kernel/pid_namespace.c:pidns_for_children_get
Direct callers:
  - kernel/pid.c:alloc_pid
  - kernel/pid.c:put_pid
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_destroy_work_fn
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:free_event_rcu
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/proc/root.c:proc_kill_sb
  - fs/proc/root.c:proc_fs_context_free
  - ipc/util.c:sysvipc_proc_release
```
**Symbols:**

```
ffffffff811694d0-ffffffff8116950d: put_pid_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void put_pid_ns(struct pid_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid_namespace.c (ffffffff81176d39)
Location: kernel/pid_namespace.c:168
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_put
  - kernel/pid_namespace.c:pidns_for_children_get
Direct callers:
  - kernel/pid.c:alloc_pid
  - kernel/pid.c:put_pid
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_destroy_work_fn
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:free_event_rcu
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/proc/root.c:proc_kill_sb
  - fs/proc/root.c:proc_fs_context_free
  - ipc/util.c:sysvipc_proc_release
```
**Symbols:**

```
ffffffff81176bc0-ffffffff81176bfd: put_pid_ns (STB_GLOBAL)
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
