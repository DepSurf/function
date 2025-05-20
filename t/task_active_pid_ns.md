# Function: <code>task_active_pid_ns</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct pid_namespace *task_active_pid_ns(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff8109db2f)
Location: kernel/pid.c:545
Inline: True
Inline callers:
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:pid_vnr
  - kernel/pid.c:__task_pid_nr_ns
  - kernel/pid.c:find_task_by_vpid
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
  - kernel/exit.c:do_exit
  - kernel/sysctl_binary.c:do_sysctl
  - kernel/signal.c:__send_signal
  - kernel/signal.c:send_signal
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/reboot.c:SYSC_reboot
  - kernel/acct.c:SyS_acct
  - kernel/acct.c:SyS_acct
  - kernel/acct.c:acct_process
  - kernel/cgroup.c:cgroup_pidlist_find
  - kernel/cgroup.c:pidlist_array_load
  - kernel/pid_namespace.c:pid_ns_ctl_handler
  - kernel/pid_namespace.c:pidns_get
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/audit.c:audit_receive_msg
  - kernel/taskstats.c:add_del_listener
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/events/core.c:perf_event_alloc
  - fs/proc/root.c:proc_mount
  - fs/proc/loadavg.c:loadavg_proc_show
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/inode.c:fuse_conn_init
  - net/core/scm.c:__scm_send
```
**Symbols:**

```
ffffffff8109dd40-ffffffff8109dd67: task_active_pid_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct pid_namespace *task_active_pid_ns(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810a1439)
Location: kernel/pid.c:545
Inline: True
Inline callers:
  - kernel/pid.c:__task_pid_nr_ns
  - kernel/pid.c:pid_vnr
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:find_task_by_vpid
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
  - kernel/exit.c:do_exit
  - kernel/sysctl_binary.c:do_sysctl
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:send_signal
  - kernel/signal.c:__send_signal
  - kernel/reboot.c:SYSC_reboot
  - kernel/acct.c:acct_process
  - kernel/acct.c:SyS_acct
  - kernel/acct.c:SyS_acct
  - kernel/cgroup.c:cgroup_pidlist_start
  - kernel/cgroup.c:cgroup_pidlist_find
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_get
  - kernel/pid_namespace.c:pid_ns_ctl_handler
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/audit.c:audit_receive_msg
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:add_del_listener
  - kernel/events/core.c:perf_event_alloc
  - fs/proc/root.c:proc_mount
  - fs/proc/loadavg.c:loadavg_proc_show
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/inode.c:fuse_conn_init
  - net/core/scm.c:__scm_send
```
**Symbols:**

```
ffffffff810a13a0-ffffffff810a13c7: task_active_pid_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct pid_namespace *task_active_pid_ns(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810a64f9)
Location: kernel/pid.c:545
Inline: True
Inline callers:
  - kernel/pid.c:__task_pid_nr_ns
  - kernel/pid.c:pid_vnr
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:find_task_by_vpid
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
  - kernel/exit.c:do_exit
  - kernel/sysctl_binary.c:do_sysctl
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:send_signal
  - kernel/signal.c:__send_signal
  - kernel/reboot.c:SYSC_reboot
  - kernel/acct.c:acct_process
  - kernel/acct.c:SyS_acct
  - kernel/acct.c:SyS_acct
  - kernel/cgroup.c:cgroup_pidlist_start
  - kernel/cgroup.c:cgroup_pidlist_find
  - kernel/pid_namespace.c:pidns_get_parent
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_get
  - kernel/pid_namespace.c:pid_ns_ctl_handler
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/audit.c:audit_receive_msg
  - kernel/taskstats.c:add_del_listener
  - kernel/events/core.c:perf_event_alloc
  - fs/proc/root.c:proc_mount
  - fs/proc/loadavg.c:loadavg_proc_show
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/inode.c:fuse_conn_init
  - net/core/scm.c:__scm_send
```
**Symbols:**

```
ffffffff810a6460-ffffffff810a6487: task_active_pid_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct pid_namespace *task_active_pid_ns(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810a347b)
Location: kernel/pid.c:543
Inline: True
Inline callers:
  - kernel/pid.c:__task_pid_nr_ns
  - kernel/pid.c:pid_vnr
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:find_task_by_vpid
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
  - kernel/exit.c:do_exit
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:send_signal
  - kernel/signal.c:__send_signal
  - kernel/reboot.c:SYSC_reboot
  - kernel/acct.c:acct_process
  - kernel/acct.c:SyS_acct
  - kernel/acct.c:SyS_acct
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_find
  - kernel/pid_namespace.c:pidns_get_parent
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_get
  - kernel/pid_namespace.c:pid_ns_ctl_handler
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/audit.c:audit_receive_msg
  - kernel/taskstats.c:add_del_listener
  - fs/proc/root.c:proc_mount
  - fs/proc/loadavg.c:loadavg_proc_show
  - fs/fuse/inode.c:fuse_conn_init
  - net/core/scm.c:__scm_send
```
**Symbols:**

```
ffffffff810a33e0-ffffffff810a3407: task_active_pid_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct pid_namespace *task_active_pid_ns(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810a9d09)
Location: kernel/pid.c:413
Inline: True
Inline callers:
  - kernel/pid.c:__task_pid_nr_ns
  - kernel/pid.c:pid_vnr
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:find_task_by_vpid
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
  - kernel/exit.c:do_exit
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:send_signal
  - kernel/signal.c:__send_signal
  - kernel/reboot.c:SYSC_reboot
  - kernel/acct.c:acct_process
  - kernel/acct.c:SyS_acct
  - kernel/acct.c:SyS_acct
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_find
  - kernel/pid_namespace.c:pidns_get_parent
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_get
  - kernel/pid_namespace.c:pid_ns_ctl_handler
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/audit.c:audit_receive_msg
  - kernel/taskstats.c:add_del_listener
  - fs/locks.c:fcntl_getlk
  - fs/proc/root.c:proc_mount
  - fs/proc/loadavg.c:loadavg_proc_show
  - fs/fuse/inode.c:fuse_conn_init
  - net/core/scm.c:__scm_send
```
**Symbols:**

```
ffffffff810a9c00-ffffffff810a9c2b: task_active_pid_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct pid_namespace *task_active_pid_ns(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810b0878)
Location: kernel/pid.c:438
Inline: True
Inline callers:
  - kernel/pid.c:__task_pid_nr_ns
  - kernel/pid.c:pid_vnr
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:find_task_by_vpid
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
  - kernel/exit.c:do_exit
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:send_signal
  - kernel/signal.c:__send_signal
  - kernel/reboot.c:__do_sys_reboot
  - kernel/acct.c:acct_process
  - kernel/acct.c:__ia32_sys_acct
  - kernel/acct.c:__x64_sys_acct
  - kernel/acct.c:acct_on
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_find
  - kernel/pid_namespace.c:pidns_get_parent
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_get
  - kernel/pid_namespace.c:pid_ns_ctl_handler
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/audit.c:audit_receive_msg
  - kernel/taskstats.c:add_del_listener
  - kernel/events/core.c:perf_event_alloc
  - fs/locks.c:fcntl_getlk
  - fs/proc/root.c:proc_mount
  - fs/proc/loadavg.c:loadavg_proc_show
  - fs/fuse/inode.c:fuse_conn_init
  - ipc/util.c:sysvipc_proc_open
  - net/core/scm.c:__scm_send
```
**Symbols:**

```
ffffffff810b0900-ffffffff810b092b: task_active_pid_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct pid_namespace *task_active_pid_ns(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810b99aa)
Location: kernel/pid.c:438
Inline: True
Inline callers:
  - kernel/pid.c:__task_pid_nr_ns
  - kernel/pid.c:pid_vnr
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:find_task_by_vpid
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
  - kernel/exit.c:do_exit
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:send_signal
  - kernel/signal.c:__send_signal
  - kernel/reboot.c:__do_sys_reboot
  - kernel/acct.c:acct_process
  - kernel/acct.c:__ia32_sys_acct
  - kernel/acct.c:__x64_sys_acct
  - kernel/acct.c:acct_on
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_find
  - kernel/pid_namespace.c:pidns_get_parent
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_get
  - kernel/pid_namespace.c:pid_ns_ctl_handler
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/audit.c:audit_receive_msg
  - kernel/taskstats.c:add_del_listener
  - kernel/events/core.c:perf_event_alloc
  - fs/locks.c:fcntl_getlk
  - fs/proc/root.c:proc_mount
  - fs/proc/loadavg.c:loadavg_proc_show
  - fs/fuse/inode.c:fuse_conn_init
  - ipc/util.c:sysvipc_proc_open
  - net/core/scm.c:__scm_send
```
**Symbols:**

```
ffffffff810b99e0-ffffffff810b9a07: task_active_pid_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct pid_namespace *task_active_pid_ns(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810bf7b2)
Location: kernel/pid.c:441
Inline: True
Inline callers:
  - kernel/pid.c:__task_pid_nr_ns
  - kernel/pid.c:pid_vnr
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:find_task_by_vpid
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
  - kernel/fork.c:copy_process
  - kernel/exit.c:do_exit
  - kernel/signal.c:__ia32_sys_pidfd_send_signal
  - kernel/signal.c:__x64_sys_pidfd_send_signal
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:send_signal
  - kernel/signal.c:__send_signal
  - kernel/reboot.c:__do_sys_reboot
  - kernel/acct.c:acct_process
  - kernel/acct.c:__ia32_sys_acct
  - kernel/acct.c:__x64_sys_acct
  - kernel/acct.c:acct_on
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_find
  - kernel/pid_namespace.c:pidns_get_parent
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_get
  - kernel/pid_namespace.c:pid_ns_ctl_handler
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/audit.c:audit_receive_msg
  - kernel/taskstats.c:add_del_listener
  - kernel/events/core.c:perf_event_alloc
  - fs/locks.c:fcntl_getlk
  - fs/proc/root.c:proc_init_fs_context
  - fs/proc/loadavg.c:loadavg_proc_show
  - fs/fuse/inode.c:fuse_conn_init
  - ipc/util.c:sysvipc_proc_open
  - net/core/scm.c:__scm_send
```
**Symbols:**

```
ffffffff810bf6b0-ffffffff810bf6d3: task_active_pid_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct pid_namespace *task_active_pid_ns(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810c5b84)
Location: kernel/pid.c:441
Inline: True
Inline callers:
  - kernel/pid.c:__task_pid_nr_ns
  - kernel/pid.c:pid_vnr
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:find_task_by_vpid
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
  - kernel/fork.c:copy_process
  - kernel/exit.c:do_exit
  - kernel/signal.c:__ia32_sys_pidfd_send_signal
  - kernel/signal.c:__x64_sys_pidfd_send_signal
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:send_signal
  - kernel/signal.c:__send_signal
  - kernel/reboot.c:__do_sys_reboot
  - kernel/acct.c:acct_process
  - kernel/acct.c:__ia32_sys_acct
  - kernel/acct.c:__x64_sys_acct
  - kernel/acct.c:acct_on
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_find
  - kernel/pid_namespace.c:pidns_get_parent
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_get
  - kernel/pid_namespace.c:pid_ns_ctl_handler
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/audit.c:audit_receive_msg
  - kernel/taskstats.c:add_del_listener
  - kernel/events/core.c:perf_event_alloc
  - fs/locks.c:fcntl_getlk
  - fs/proc/root.c:proc_init_fs_context
  - fs/proc/loadavg.c:loadavg_proc_show
  - fs/fuse/inode.c:fuse_conn_init
  - ipc/util.c:sysvipc_proc_open
  - net/core/scm.c:__scm_send
```
**Symbols:**

```
ffffffff810c5a80-ffffffff810c5aa3: task_active_pid_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct pid_namespace *task_active_pid_ns(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810cd40a)
Location: kernel/pid.c:506
Inline: True
Inline callers:
  - kernel/pid.c:__task_pid_nr_ns
  - kernel/pid.c:pid_vnr
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:find_get_task_by_vpid
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
  - kernel/fork.c:copy_process
  - kernel/exit.c:find_child_reaper
  - kernel/signal.c:__do_sys_pidfd_send_signal
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:send_signal
  - kernel/signal.c:__send_signal
  - kernel/nsproxy.c:validate_nsset
  - kernel/reboot.c:__do_sys_reboot
  - kernel/acct.c:acct_process
  - kernel/acct.c:__ia32_sys_acct
  - kernel/acct.c:__x64_sys_acct
  - kernel/acct.c:acct_on
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_find_create
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_find_create
  - kernel/pid_namespace.c:pidns_get_parent
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_get
  - kernel/pid_namespace.c:pid_ns_ctl_handler
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/audit.c:audit_receive_msg
  - kernel/taskstats.c:add_del_listener
  - kernel/taskstats.c:fill_stats_for_pid
  - kernel/bpf/helpers.c:bpf_get_ns_current_pid_tgid
  - kernel/bpf/task_iter.c:init_seq_pidns
  - kernel/events/core.c:perf_event_alloc
  - fs/exec.c:exec_binprm
  - fs/locks.c:fcntl_getlk
  - fs/proc/root.c:proc_init_fs_context
  - fs/proc/loadavg.c:loadavg_proc_show
  - fs/fuse/inode.c:fuse_conn_init
  - ipc/util.c:sysvipc_proc_open
  - net/core/scm.c:__scm_send
```
**Symbols:**

```
ffffffff810cd430-ffffffff810cd453: task_active_pid_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct pid_namespace *task_active_pid_ns(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810c7fb5)
Location: kernel/pid.c:507
Inline: True
Inline callers:
  - kernel/pid.c:__task_pid_nr_ns
  - kernel/pid.c:pid_vnr
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:find_get_task_by_vpid
Direct callers:
  - kernel/fork.c:kernel_clone
  - kernel/fork.c:kernel_clone
  - kernel/fork.c:copy_process
  - kernel/exit.c:find_child_reaper
  - kernel/signal.c:__do_sys_pidfd_send_signal
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:send_signal
  - kernel/signal.c:__send_signal
  - kernel/nsproxy.c:validate_nsset
  - kernel/reboot.c:__do_sys_reboot
  - kernel/acct.c:acct_process
  - kernel/acct.c:__ia32_sys_acct
  - kernel/acct.c:__x64_sys_acct
  - kernel/acct.c:acct_on
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_find_create
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_find_create
  - kernel/pid_namespace.c:pidns_get_parent
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_get
  - kernel/pid_namespace.c:pid_ns_ctl_handler
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/audit.c:audit_receive_msg
  - kernel/taskstats.c:add_del_listener
  - kernel/taskstats.c:fill_stats_for_pid
  - kernel/bpf/helpers.c:bpf_get_ns_current_pid_tgid
  - kernel/bpf/task_iter.c:init_seq_pidns
  - kernel/events/core.c:perf_event_alloc
  - fs/exec.c:exec_binprm
  - fs/locks.c:fcntl_getlk
  - fs/proc/root.c:proc_init_fs_context
  - fs/proc/loadavg.c:loadavg_proc_show
  - fs/fuse/inode.c:fuse_conn_init
  - ipc/util.c:sysvipc_proc_open
  - net/core/scm.c:__scm_send
```
**Symbols:**

```
ffffffff810c7ec0-ffffffff810c7ee3: task_active_pid_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct pid_namespace *task_active_pid_ns(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810c9a55)
Location: kernel/pid.c:507
Inline: True
Inline callers:
  - kernel/pid.c:__task_pid_nr_ns
  - kernel/pid.c:pid_vnr
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:find_get_task_by_vpid
Direct callers:
  - kernel/fork.c:kernel_clone
  - kernel/fork.c:kernel_clone
  - kernel/fork.c:copy_process
  - kernel/exit.c:forget_original_parent
  - kernel/signal.c:__do_sys_pidfd_send_signal
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:send_signal
  - kernel/signal.c:__send_signal
  - kernel/nsproxy.c:validate_nsset
  - kernel/reboot.c:__do_sys_reboot
  - kernel/acct.c:acct_process
  - kernel/acct.c:__ia32_sys_acct
  - kernel/acct.c:__x64_sys_acct
  - kernel/acct.c:acct_on
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/pid_namespace.c:pidns_get_parent
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_get
  - kernel/pid_namespace.c:pid_ns_ctl_handler
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/audit.c:audit_receive_msg
  - kernel/taskstats.c:cmd_attr_pid
  - kernel/taskstats.c:add_del_listener
  - kernel/bpf/helpers.c:bpf_get_ns_current_pid_tgid
  - kernel/bpf/task_iter.c:init_seq_pidns
  - kernel/events/core.c:perf_event_alloc
  - fs/exec.c:exec_binprm
  - fs/locks.c:fcntl_getlk
  - fs/proc/root.c:proc_init_fs_context
  - fs/proc/loadavg.c:loadavg_proc_show
  - fs/fuse/inode.c:fuse_conn_init
  - ipc/util.c:sysvipc_proc_open
  - net/core/scm.c:__scm_send
```
**Symbols:**

```
ffffffff810c9960-ffffffff810c9983: task_active_pid_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct pid_namespace *task_active_pid_ns(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810dc9c2)
Location: kernel/pid.c:507
Inline: True
Inline callers:
  - kernel/pid.c:__task_pid_nr_ns
  - kernel/pid.c:pid_vnr
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:find_get_task_by_vpid
Direct callers:
  - kernel/fork.c:kernel_clone
  - kernel/fork.c:kernel_clone
  - kernel/fork.c:copy_process
  - kernel/exit.c:forget_original_parent
  - kernel/signal.c:__do_sys_pidfd_send_signal
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:send_signal
  - kernel/signal.c:__send_signal
  - kernel/nsproxy.c:validate_nsset
  - kernel/reboot.c:__do_sys_reboot
  - kernel/acct.c:acct_process
  - kernel/acct.c:__ia32_sys_acct
  - kernel/acct.c:__x64_sys_acct
  - kernel/acct.c:acct_on
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/pid_namespace.c:pidns_get_parent
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_get
  - kernel/pid_namespace.c:pid_ns_ctl_handler
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/audit.c:audit_receive_msg
  - kernel/taskstats.c:cmd_attr_pid
  - kernel/taskstats.c:add_del_listener
  - kernel/bpf/helpers.c:bpf_get_ns_current_pid_tgid
  - kernel/bpf/task_iter.c:init_seq_pidns
  - kernel/events/core.c:perf_event_alloc
  - fs/exec.c:exec_binprm
  - fs/locks.c:fcntl_getlk
  - fs/proc/root.c:proc_init_fs_context
  - fs/proc/loadavg.c:loadavg_proc_show
  - fs/fuse/inode.c:fuse_conn_init
  - ipc/util.c:sysvipc_proc_open
  - net/core/scm.c:__scm_send
```
**Symbols:**

```
ffffffff810dc8c0-ffffffff810dc8e3: task_active_pid_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct pid_namespace *task_active_pid_ns(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810f7558)
Location: kernel/pid.c:507
Inline: True
Inline callers:
  - kernel/pid.c:__ia32_sys_pidfd_open
  - kernel/pid.c:__x64_sys_pidfd_open
  - kernel/pid.c:__task_pid_nr_ns
  - kernel/pid.c:pid_vnr
  - kernel/pid.c:find_get_task_by_vpid
Direct callers:
  - kernel/fork.c:kernel_clone
  - kernel/fork.c:kernel_clone
  - kernel/fork.c:copy_process
  - kernel/exit.c:forget_original_parent
  - kernel/signal.c:__do_sys_pidfd_send_signal
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:send_signal_locked
  - kernel/signal.c:__send_signal_locked
  - kernel/nsproxy.c:validate_nsset
  - kernel/reboot.c:__do_sys_reboot
  - kernel/acct.c:acct_process
  - kernel/acct.c:__ia32_sys_acct
  - kernel/acct.c:__x64_sys_acct
  - kernel/acct.c:acct_on
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/pid_namespace.c:pidns_get_parent
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_get
  - kernel/pid_namespace.c:pid_ns_ctl_handler
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/audit.c:audit_receive_msg
  - kernel/taskstats.c:cmd_attr_pid
  - kernel/taskstats.c:add_del_listener
  - kernel/bpf/helpers.c:bpf_get_ns_current_pid_tgid
  - kernel/bpf/task_iter.c:init_seq_pidns
  - kernel/events/core.c:perf_event_alloc
  - fs/exec.c:exec_binprm
  - fs/locks.c:fcntl_getlk
  - fs/proc/root.c:proc_init_fs_context
  - fs/proc/loadavg.c:loadavg_proc_show
  - fs/fuse/inode.c:fuse_conn_init
  - ipc/util.c:sysvipc_proc_open
  - net/core/scm.c:__scm_send
```
**Symbols:**

```
ffffffff810f6080-ffffffff810f60ab: task_active_pid_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct pid_namespace *task_active_pid_ns(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff81119cd8)
Location: kernel/pid.c:507
Inline: True
Inline callers:
  - kernel/pid.c:__ia32_sys_pidfd_open
  - kernel/pid.c:__x64_sys_pidfd_open
  - kernel/pid.c:__task_pid_nr_ns
  - kernel/pid.c:pid_vnr
  - kernel/pid.c:find_get_task_by_vpid
Direct callers:
  - kernel/fork.c:kernel_clone
  - kernel/fork.c:kernel_clone
  - kernel/fork.c:copy_process
  - kernel/exit.c:forget_original_parent
  - kernel/signal.c:__do_sys_pidfd_send_signal
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:send_signal_locked
  - kernel/signal.c:__send_signal_locked
  - kernel/nsproxy.c:validate_nsset
  - kernel/reboot.c:__do_sys_reboot
  - kernel/acct.c:acct_process
  - kernel/acct.c:__ia32_sys_acct
  - kernel/acct.c:__x64_sys_acct
  - kernel/acct.c:acct_on
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/pid_namespace.c:pidns_get_parent
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_get
  - kernel/pid_namespace.c:pid_ns_ctl_handler
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/audit.c:audit_receive_msg
  - kernel/taskstats.c:cmd_attr_pid
  - kernel/taskstats.c:add_del_listener
  - kernel/bpf/helpers.c:bpf_get_ns_current_pid_tgid
  - kernel/bpf/task_iter.c:init_seq_pidns
  - kernel/bpf/task_iter.c:bpf_iter_attach_task
  - kernel/events/core.c:perf_event_alloc
  - fs/exec.c:exec_binprm
  - fs/locks.c:fcntl_getlk
  - fs/proc/root.c:proc_init_fs_context
  - fs/proc/loadavg.c:loadavg_proc_show
  - fs/fuse/inode.c:fuse_conn_init
  - ipc/util.c:sysvipc_proc_open
  - net/core/scm.c:__scm_send
```
**Symbols:**

```
ffffffff81118600-ffffffff8111862b: task_active_pid_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct pid_namespace *task_active_pid_ns(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff81125de9)
Location: kernel/pid.c:510
Inline: True
Inline callers:
  - kernel/pid.c:__ia32_sys_pidfd_open
  - kernel/pid.c:__x64_sys_pidfd_open
  - kernel/pid.c:__task_pid_nr_ns
  - kernel/pid.c:pid_vnr
  - kernel/pid.c:find_get_task_by_vpid
Direct callers:
  - kernel/fork.c:kernel_clone
  - kernel/fork.c:kernel_clone
  - kernel/fork.c:copy_process
  - kernel/exit.c:forget_original_parent
  - kernel/signal.c:__do_sys_pidfd_send_signal
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:send_signal_locked
  - kernel/signal.c:__send_signal_locked
  - kernel/nsproxy.c:validate_nsset
  - kernel/reboot.c:__do_sys_reboot
  - kernel/acct.c:acct_process
  - kernel/acct.c:__ia32_sys_acct
  - kernel/acct.c:__x64_sys_acct
  - kernel/acct.c:acct_on
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/pid_namespace.c:pidns_get_parent
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_get
  - kernel/pid_namespace.c:pid_ns_ctl_handler
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/pid_namespace.c:pid_mfd_noexec_dointvec_minmax
  - kernel/audit.c:audit_receive_msg
  - kernel/taskstats.c:cmd_attr_pid
  - kernel/taskstats.c:add_del_listener
  - kernel/bpf/helpers.c:bpf_get_ns_current_pid_tgid
  - kernel/bpf/task_iter.c:init_seq_pidns
  - kernel/bpf/task_iter.c:bpf_iter_attach_task
  - kernel/events/core.c:perf_event_alloc
  - mm/memfd.c:__do_sys_memfd_create
  - mm/memfd.c:__do_sys_memfd_create
  - fs/exec.c:exec_binprm
  - fs/locks.c:fcntl_getlk
  - fs/proc/root.c:proc_init_fs_context
  - fs/proc/loadavg.c:loadavg_proc_show
  - fs/fuse/inode.c:fuse_conn_init
  - ipc/util.c:sysvipc_proc_open
  - net/core/scm.c:__scm_send
```
**Symbols:**

```
ffffffff81125840-ffffffff8112586b: task_active_pid_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct pid_namespace *task_active_pid_ns(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff811303e9)
Location: kernel/pid.c:510
Inline: True
Inline callers:
  - kernel/pid.c:__ia32_sys_pidfd_open
  - kernel/pid.c:__x64_sys_pidfd_open
  - kernel/pid.c:__task_pid_nr_ns
  - kernel/pid.c:pid_vnr
  - kernel/pid.c:find_get_task_by_vpid
Direct callers:
  - kernel/fork.c:kernel_clone
  - kernel/fork.c:kernel_clone
  - kernel/fork.c:copy_process
  - kernel/exit.c:forget_original_parent
  - kernel/signal.c:__do_sys_pidfd_send_signal
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:send_signal_locked
  - kernel/signal.c:__send_signal_locked
  - kernel/nsproxy.c:validate_nsset
  - kernel/reboot.c:__do_sys_reboot
  - kernel/acct.c:acct_process
  - kernel/acct.c:__ia32_sys_acct
  - kernel/acct.c:__x64_sys_acct
  - kernel/acct.c:acct_on
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/pid_namespace.c:pidns_get_parent
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_get
  - kernel/pid_namespace.c:pid_ns_ctl_handler
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/pid_namespace.c:pid_mfd_noexec_dointvec_minmax
  - kernel/audit.c:audit_receive_msg
  - kernel/taskstats.c:cmd_attr_pid
  - kernel/taskstats.c:add_del_listener
  - kernel/trace/bpf_trace.c:bpf_uprobe_multi_link_fill_link_info
  - kernel/bpf/helpers.c:bpf_get_ns_current_pid_tgid
  - kernel/bpf/task_iter.c:init_seq_pidns
  - kernel/bpf/task_iter.c:bpf_iter_attach_task
  - kernel/events/core.c:perf_event_alloc
  - mm/memfd.c:__do_sys_memfd_create
  - fs/exec.c:exec_binprm
  - fs/locks.c:fcntl_getlk
  - fs/proc/root.c:proc_init_fs_context
  - fs/proc/loadavg.c:loadavg_proc_show
  - fs/fuse/inode.c:fuse_conn_init
  - ipc/util.c:sysvipc_proc_open
  - net/core/scm.c:__scm_send
```
**Symbols:**

```
ffffffff8112fe40-ffffffff8112fe6b: task_active_pid_ns (STB_GLOBAL)
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
struct pid_namespace *task_active_pid_ns(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffff8000101240b0)
Location: kernel/pid.c:441
Inline: True
Inline callers:
  - kernel/pid.c:__task_pid_nr_ns
  - kernel/pid.c:pid_vnr
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:find_task_by_vpid
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
  - kernel/fork.c:copy_process
  - kernel/exit.c:do_exit
  - kernel/signal.c:__arm64_sys_pidfd_send_signal
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:send_signal
  - kernel/signal.c:__send_signal
  - kernel/reboot.c:__do_sys_reboot
  - kernel/acct.c:acct_process
  - kernel/acct.c:__arm64_sys_acct
  - kernel/acct.c:__arm64_sys_acct
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_find
  - kernel/pid_namespace.c:pidns_get_parent
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_get
  - kernel/pid_namespace.c:pid_ns_ctl_handler
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/audit.c:audit_receive_msg
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:add_del_listener
  - kernel/events/core.c:perf_event_alloc
  - fs/locks.c:fcntl_getlk
  - fs/proc/root.c:proc_init_fs_context
  - fs/proc/loadavg.c:loadavg_proc_show
  - fs/fuse/inode.c:fuse_conn_init
  - ipc/util.c:sysvipc_proc_open
  - net/core/scm.c:__scm_send
```
**Symbols:**

```
ffff800010123fe8-ffff800010124020: task_active_pid_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct pid_namespace *task_active_pid_ns(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (c03773ec)
Location: kernel/pid.c:441
Inline: True
Inline callers:
  - kernel/pid.c:__task_pid_nr_ns
  - kernel/pid.c:pid_vnr
  - kernel/pid.c:find_task_by_vpid
  - kernel/pid.c:find_vpid
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
  - kernel/fork.c:copy_process
  - kernel/exit.c:do_exit
  - kernel/signal.c:__se_sys_pidfd_send_signal
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:send_signal
  - kernel/signal.c:__send_signal
  - kernel/reboot.c:__do_sys_reboot
  - kernel/acct.c:acct_process
  - kernel/acct.c:__se_sys_acct
  - kernel/acct.c:__se_sys_acct
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_find
  - kernel/pid_namespace.c:pidns_get_parent
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_get
  - kernel/pid_namespace.c:pid_ns_ctl_handler
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/audit.c:audit_receive_msg
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:add_del_listener
  - kernel/events/core.c:perf_event_alloc
  - fs/exec.c:__do_execve_file
  - fs/locks.c:fcntl_getlk64
  - fs/locks.c:fcntl_getlk
  - fs/proc/root.c:proc_init_fs_context
  - fs/proc/loadavg.c:loadavg_proc_show
  - fs/fuse/inode.c:fuse_conn_init
  - ipc/util.c:sysvipc_proc_open
  - net/core/scm.c:__scm_send
```
**Symbols:**

```
c0377344-c0377370: task_active_pid_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct pid_namespace *task_active_pid_ns(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (c00000000016de04)
Location: kernel/pid.c:441
Inline: True
Inline callers:
  - kernel/pid.c:__task_pid_nr_ns
  - kernel/pid.c:pid_vnr
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:find_task_by_vpid
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
  - kernel/fork.c:copy_process
  - kernel/exit.c:do_exit
  - kernel/signal.c:__se_sys_pidfd_send_signal
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:send_signal
  - kernel/signal.c:__send_signal
  - kernel/reboot.c:__do_sys_reboot
  - kernel/acct.c:acct_process
  - kernel/acct.c:__se_sys_acct
  - kernel/acct.c:__se_sys_acct
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_find
  - kernel/pid_namespace.c:pidns_get_parent
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_get
  - kernel/pid_namespace.c:pid_ns_ctl_handler
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/audit.c:audit_receive_msg
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:add_del_listener
  - fs/locks.c:fcntl_getlk
  - fs/proc/root.c:proc_init_fs_context
  - fs/proc/loadavg.c:loadavg_proc_show
  - fs/fuse/inode.c:fuse_conn_init
  - ipc/util.c:sysvipc_proc_open
  - net/core/scm.c:__scm_send
```
**Symbols:**

```
c00000000016dc80-c00000000016dcac: task_active_pid_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct pid_namespace *task_active_pid_ns(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffe0000dc3da)
Location: kernel/pid.c:441
Inline: True
Inline callers:
  - kernel/pid.c:__task_pid_nr_ns
  - kernel/pid.c:pid_vnr
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:find_task_by_vpid
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
  - kernel/fork.c:copy_process
  - kernel/exit.c:do_exit
  - kernel/signal.c:__se_sys_pidfd_send_signal
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:send_signal
  - kernel/signal.c:send_signal
  - kernel/signal.c:__send_signal
  - kernel/reboot.c:__do_sys_reboot
  - kernel/acct.c:acct_process
  - kernel/acct.c:__se_sys_acct
  - kernel/acct.c:__se_sys_acct
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_find
  - kernel/pid_namespace.c:pidns_get_parent
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_get
  - kernel/pid_namespace.c:pid_ns_ctl_handler
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/audit.c:audit_receive_msg
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:add_del_listener
  - fs/exec.c:__do_execve_file
  - fs/locks.c:fcntl_getlk
  - fs/proc/root.c:proc_init_fs_context
  - fs/proc/loadavg.c:loadavg_proc_show
  - fs/fuse/inode.c:fuse_conn_init
  - ipc/util.c:sysvipc_proc_open
  - net/core/scm.c:__scm_send
```
**Symbols:**

```
ffffffe0000dc2a8-ffffffe0000dc2da: task_active_pid_ns (STB_GLOBAL)
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
struct pid_namespace *task_active_pid_ns(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810bff04)
Location: kernel/pid.c:441
Inline: True
Inline callers:
  - kernel/pid.c:__task_pid_nr_ns
  - kernel/pid.c:pid_vnr
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:find_task_by_vpid
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
  - kernel/fork.c:copy_process
  - kernel/exit.c:do_exit
  - kernel/signal.c:__ia32_sys_pidfd_send_signal
  - kernel/signal.c:__x64_sys_pidfd_send_signal
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:send_signal
  - kernel/signal.c:__send_signal
  - kernel/reboot.c:__do_sys_reboot
  - kernel/acct.c:acct_process
  - kernel/acct.c:__ia32_sys_acct
  - kernel/acct.c:__x64_sys_acct
  - kernel/acct.c:acct_on
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_find
  - kernel/pid_namespace.c:pidns_get_parent
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_get
  - kernel/pid_namespace.c:pid_ns_ctl_handler
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/audit.c:audit_receive_msg
  - kernel/taskstats.c:add_del_listener
  - kernel/events/core.c:perf_event_alloc
  - fs/locks.c:fcntl_getlk
  - fs/proc/root.c:proc_init_fs_context
  - fs/proc/loadavg.c:loadavg_proc_show
  - fs/fuse/inode.c:fuse_conn_init
  - ipc/util.c:sysvipc_proc_open
  - net/core/scm.c:__scm_send
```
**Symbols:**

```
ffffffff810bfe00-ffffffff810bfe23: task_active_pid_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct pid_namespace *task_active_pid_ns(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810ae714)
Location: kernel/pid.c:441
Inline: True
Inline callers:
  - kernel/pid.c:__task_pid_nr_ns
  - kernel/pid.c:pid_vnr
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:find_task_by_vpid
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
  - kernel/fork.c:copy_process
  - kernel/exit.c:do_exit
  - kernel/signal.c:__ia32_sys_pidfd_send_signal
  - kernel/signal.c:__x64_sys_pidfd_send_signal
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:send_signal
  - kernel/signal.c:__send_signal
  - kernel/reboot.c:__do_sys_reboot
  - kernel/acct.c:acct_process
  - kernel/acct.c:__ia32_sys_acct
  - kernel/acct.c:__x64_sys_acct
  - kernel/acct.c:acct_on
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_find
  - kernel/pid_namespace.c:pidns_get_parent
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_get
  - kernel/pid_namespace.c:pid_ns_ctl_handler
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/audit.c:audit_receive_msg
  - kernel/taskstats.c:add_del_listener
  - kernel/events/core.c:perf_event_alloc
  - fs/locks.c:fcntl_getlk
  - fs/proc/root.c:proc_init_fs_context
  - fs/proc/loadavg.c:loadavg_proc_show
  - fs/fuse/inode.c:fuse_conn_init
  - ipc/util.c:sysvipc_proc_open
  - net/core/scm.c:__scm_send
```
**Symbols:**

```
ffffffff810ae610-ffffffff810ae633: task_active_pid_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct pid_namespace *task_active_pid_ns(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810bf454)
Location: kernel/pid.c:441
Inline: True
Inline callers:
  - kernel/pid.c:__task_pid_nr_ns
  - kernel/pid.c:pid_vnr
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:find_task_by_vpid
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
  - kernel/fork.c:copy_process
  - kernel/exit.c:do_exit
  - kernel/signal.c:__ia32_sys_pidfd_send_signal
  - kernel/signal.c:__x64_sys_pidfd_send_signal
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:send_signal
  - kernel/signal.c:__send_signal
  - kernel/reboot.c:__do_sys_reboot
  - kernel/acct.c:acct_process
  - kernel/acct.c:__ia32_sys_acct
  - kernel/acct.c:__x64_sys_acct
  - kernel/acct.c:acct_on
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_find
  - kernel/pid_namespace.c:pidns_get_parent
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_get
  - kernel/pid_namespace.c:pid_ns_ctl_handler
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/audit.c:audit_receive_msg
  - kernel/taskstats.c:add_del_listener
  - kernel/events/core.c:perf_event_alloc
  - fs/locks.c:fcntl_getlk
  - fs/proc/root.c:proc_init_fs_context
  - fs/proc/loadavg.c:loadavg_proc_show
  - fs/fuse/inode.c:fuse_conn_init
  - ipc/util.c:sysvipc_proc_open
  - net/core/scm.c:__scm_send
```
**Symbols:**

```
ffffffff810bf350-ffffffff810bf373: task_active_pid_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct pid_namespace *task_active_pid_ns(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810c78d2)
Location: kernel/pid.c:441
Inline: True
Inline callers:
  - kernel/pid.c:__task_pid_nr_ns
  - kernel/pid.c:pid_vnr
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:find_task_by_vpid
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
  - kernel/fork.c:copy_process
  - kernel/exit.c:do_exit
  - kernel/signal.c:__ia32_sys_pidfd_send_signal
  - kernel/signal.c:__x64_sys_pidfd_send_signal
  - kernel/signal.c:do_notify_parent_cldstop
  - kernel/signal.c:do_notify_parent
  - kernel/signal.c:send_signal
  - kernel/signal.c:__send_signal
  - kernel/reboot.c:__do_sys_reboot
  - kernel/acct.c:acct_process
  - kernel/acct.c:__ia32_sys_acct
  - kernel/acct.c:__x64_sys_acct
  - kernel/acct.c:acct_on
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_find
  - kernel/pid_namespace.c:pidns_get_parent
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_get
  - kernel/pid_namespace.c:pid_ns_ctl_handler
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/audit.c:audit_receive_msg
  - kernel/taskstats.c:add_del_listener
  - kernel/events/core.c:perf_event_alloc
  - fs/locks.c:fcntl_getlk
  - fs/proc/root.c:proc_init_fs_context
  - fs/proc/loadavg.c:loadavg_proc_show
  - fs/fuse/inode.c:fuse_conn_init
  - ipc/util.c:sysvipc_proc_open
  - net/core/scm.c:__scm_send
```
**Symbols:**

```
ffffffff810c7680-ffffffff810c76a3: task_active_pid_ns (STB_GLOBAL)
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
