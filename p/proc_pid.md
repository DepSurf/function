# Function: <code>proc_pid</code>

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
In fs/proc_namespace.c (0)
Location: fs/proc/internal.h:90
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff81277076)
Location: fs/proc/internal.h:90
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (ffffffff8127a215)
Location: fs/proc/internal.h:90
Inline: True
Inline callers:
  - fs/proc/base.c:pid_delete_dentry
  - fs/proc/base.c:proc_timers_open
  - fs/proc/base.c:proc_loginuid_write
  - fs/proc/base.c:oom_score_adj_write
  - fs/proc/base.c:sched_write
  - fs/proc/base.c:sched_autogroup_show
  - fs/proc/base.c:sched_show
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_single_show
  - fs/proc/base.c:proc_sessionid_read
  - fs/proc/base.c:comm_show
  - fs/proc/base.c:proc_exe_link
  - fs/proc/base.c:proc_cwd_link
  - fs/proc/base.c:proc_loginuid_read
  - fs/proc/base.c:proc_coredump_filter_read
  - fs/proc/base.c:oom_score_adj_read
  - fs/proc/base.c:oom_adj_read
  - fs/proc/base.c:proc_pid_attr_write
  - fs/proc/base.c:proc_map_files_get_link
  - fs/proc/base.c:proc_coredump_filter_write
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/base.c:oom_adj_write
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_map_files_readdir
```
```
In fs/proc/array.c (0)
Location: fs/proc/internal.h:90
Inline: True
```
```
In fs/proc/fd.c (ffffffff81281561)
Location: fs/proc/internal.h:90
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_fd_link
  - fs/proc/fd.c:seq_show
```
```
In fs/proc/namespaces.c (ffffffff812836de)
Location: fs/proc/internal.h:90
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_readdir
```
```
In fs/proc/proc_net.c (0)
Location: fs/proc/internal.h:90
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
In fs/proc_namespace.c (0)
Location: fs/proc/internal.h:90
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff812a35da)
Location: fs/proc/internal.h:90
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (ffffffff812a9f60)
Location: fs/proc/internal.h:90
Inline: True
Inline callers:
  - fs/proc/base.c:proc_coredump_filter_write
  - fs/proc/base.c:proc_coredump_filter_read
  - fs/proc/base.c:proc_pid_attr_write
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:timerslack_ns_show
  - fs/proc/base.c:proc_timers_open
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:pid_delete_dentry
  - fs/proc/base.c:proc_exe_link
  - fs/proc/base.c:comm_show
  - fs/proc/base.c:sched_autogroup_show
  - fs/proc/base.c:sched_write
  - fs/proc/base.c:sched_show
  - fs/proc/base.c:proc_sessionid_read
  - fs/proc/base.c:proc_loginuid_write
  - fs/proc/base.c:proc_loginuid_read
  - fs/proc/base.c:oom_score_adj_read
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:oom_adj_read
  - fs/proc/base.c:proc_single_show
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
```
```
In fs/proc/array.c (0)
Location: fs/proc/internal.h:90
Inline: True
```
```
In fs/proc/fd.c (ffffffff812ae621)
Location: fs/proc/internal.h:90
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_fd_link
  - fs/proc/fd.c:seq_show
```
```
In fs/proc/namespaces.c (ffffffff812b098e)
Location: fs/proc/internal.h:90
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_readdir
```
```
In fs/proc/proc_net.c (0)
Location: fs/proc/internal.h:90
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
In fs/proc_namespace.c (0)
Location: fs/proc/internal.h:90
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff812b8fba)
Location: fs/proc/internal.h:90
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (ffffffff812bf880)
Location: fs/proc/internal.h:90
Inline: True
Inline callers:
  - fs/proc/base.c:proc_coredump_filter_write
  - fs/proc/base.c:proc_coredump_filter_read
  - fs/proc/base.c:proc_pid_attr_write
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:timerslack_ns_show
  - fs/proc/base.c:proc_timers_open
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:pid_delete_dentry
  - fs/proc/base.c:proc_exe_link
  - fs/proc/base.c:comm_show
  - fs/proc/base.c:sched_autogroup_show
  - fs/proc/base.c:sched_write
  - fs/proc/base.c:sched_show
  - fs/proc/base.c:proc_sessionid_read
  - fs/proc/base.c:proc_loginuid_write
  - fs/proc/base.c:proc_loginuid_read
  - fs/proc/base.c:oom_score_adj_read
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:oom_adj_read
  - fs/proc/base.c:proc_single_show
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
```
```
In fs/proc/array.c (0)
Location: fs/proc/internal.h:90
Inline: True
```
```
In fs/proc/fd.c (ffffffff812c4001)
Location: fs/proc/internal.h:90
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_fd_link
  - fs/proc/fd.c:seq_show
```
```
In fs/proc/namespaces.c (ffffffff812c637e)
Location: fs/proc/internal.h:90
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_readdir
```
```
In fs/proc/proc_net.c (0)
Location: fs/proc/internal.h:90
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
In fs/proc_namespace.c (0)
Location: fs/proc/internal.h:94
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff812c72c0)
Location: fs/proc/internal.h:94
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (ffffffff812cc950)
Location: fs/proc/internal.h:94
Inline: True
Inline callers:
  - fs/proc/base.c:proc_coredump_filter_write
  - fs/proc/base.c:proc_coredump_filter_read
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:timerslack_ns_show
  - fs/proc/base.c:proc_timers_open
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:pid_delete_dentry
  - fs/proc/base.c:proc_exe_link
  - fs/proc/base.c:comm_show
  - fs/proc/base.c:sched_autogroup_show
  - fs/proc/base.c:sched_write
  - fs/proc/base.c:sched_show
  - fs/proc/base.c:proc_sessionid_read
  - fs/proc/base.c:proc_loginuid_write
  - fs/proc/base.c:proc_loginuid_read
  - fs/proc/base.c:oom_score_adj_read
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:oom_adj_read
  - fs/proc/base.c:proc_single_show
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
```
```
In fs/proc/array.c (0)
Location: fs/proc/internal.h:94
Inline: True
```
```
In fs/proc/fd.c (ffffffff812d1381)
Location: fs/proc/internal.h:94
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_fd_link
  - fs/proc/fd.c:seq_show
```
```
In fs/proc/namespaces.c (ffffffff812d34ae)
Location: fs/proc/internal.h:94
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_readdir
```
```
In fs/proc/proc_net.c (0)
Location: fs/proc/internal.h:94
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
In fs/proc_namespace.c (0)
Location: fs/proc/internal.h:94
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff812eb0e0)
Location: fs/proc/internal.h:94
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (ffffffff812f11f0)
Location: fs/proc/internal.h:94
Inline: True
Inline callers:
  - fs/proc/base.c:proc_coredump_filter_write
  - fs/proc/base.c:proc_coredump_filter_read
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:timerslack_ns_show
  - fs/proc/base.c:proc_timers_open
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:pid_delete_dentry
  - fs/proc/base.c:proc_exe_link
  - fs/proc/base.c:comm_show
  - fs/proc/base.c:sched_autogroup_show
  - fs/proc/base.c:sched_write
  - fs/proc/base.c:proc_sessionid_read
  - fs/proc/base.c:proc_loginuid_write
  - fs/proc/base.c:proc_loginuid_read
  - fs/proc/base.c:oom_score_adj_read
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:oom_adj_read
  - fs/proc/base.c:proc_single_show
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
```
```
In fs/proc/array.c (0)
Location: fs/proc/internal.h:94
Inline: True
```
```
In fs/proc/fd.c (ffffffff812f5b71)
Location: fs/proc/internal.h:94
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_fd_link
  - fs/proc/fd.c:seq_show
```
```
In fs/proc/namespaces.c (ffffffff812f7cde)
Location: fs/proc/internal.h:94
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_readdir
```
```
In fs/proc/proc_net.c (0)
Location: fs/proc/internal.h:94
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
In fs/proc_namespace.c (ffffffff812e4172)
Location: fs/proc/internal.h:119
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/proc/task_mmu.c (ffffffff81317270)
Location: fs/proc/internal.h:119
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (ffffffff8131d0bb)
Location: fs/proc/internal.h:119
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_getattr
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:proc_tid_comm_permission
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_open
  - fs/proc/base.c:proc_coredump_filter_write
  - fs/proc/base.c:proc_coredump_filter_read
  - fs/proc/base.c:proc_pid_attr_write
  - fs/proc/base.c:proc_pid_attr_read
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_pident_lookup
  - fs/proc/base.c:timerslack_ns_show
  - fs/proc/base.c:timerslack_ns_write
  - fs/proc/base.c:proc_timers_open
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:pid_delete_dentry
  - fs/proc/base.c:pid_revalidate
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_exe_link
  - fs/proc/base.c:comm_show
  - fs/proc/base.c:comm_write
  - fs/proc/base.c:sched_autogroup_write
  - fs/proc/base.c:sched_autogroup_show
  - fs/proc/base.c:sched_write
  - fs/proc/base.c:sched_show
  - fs/proc/base.c:proc_sessionid_read
  - fs/proc/base.c:proc_loginuid_write
  - fs/proc/base.c:proc_loginuid_read
  - fs/proc/base.c:oom_score_adj_read
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:oom_adj_read
  - fs/proc/base.c:proc_mem_open
  - fs/proc/base.c:proc_single_show
  - fs/proc/base.c:proc_pid_permission
  - fs/proc/base.c:proc_fd_access_allowed
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
```
```
In fs/proc/array.c (ffffffff813211b5)
Location: fs/proc/internal.h:119
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
```
```
In fs/proc/fd.c (ffffffff81322f4a)
Location: fs/proc/internal.h:119
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_fd_permission
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_lookupfd_common
  - fs/proc/fd.c:proc_fd_link
  - fs/proc/fd.c:tid_fd_revalidate
  - fs/proc/fd.c:seq_show
```
```
In fs/proc/namespaces.c (ffffffff81324e75)
Location: fs/proc/internal.h:119
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_lookup
  - fs/proc/namespaces.c:proc_ns_dir_readdir
  - fs/proc/namespaces.c:proc_ns_readlink
  - fs/proc/namespaces.c:proc_ns_get_link
```
```
In fs/proc/proc_net.c (ffffffff81327f55)
Location: fs/proc/internal.h:119
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_task_net
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
In fs/proc_namespace.c (ffffffff812f8df2)
Location: fs/proc/internal.h:118
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/proc/task_mmu.c (ffffffff8132e6c0)
Location: fs/proc/internal.h:118
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (ffffffff8133439b)
Location: fs/proc/internal.h:118
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_getattr
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:proc_tid_comm_permission
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_open
  - fs/proc/base.c:proc_coredump_filter_write
  - fs/proc/base.c:proc_coredump_filter_read
  - fs/proc/base.c:proc_pid_attr_write
  - fs/proc/base.c:proc_pid_attr_read
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_pident_lookup
  - fs/proc/base.c:timerslack_ns_show
  - fs/proc/base.c:timerslack_ns_write
  - fs/proc/base.c:proc_timers_open
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:pid_delete_dentry
  - fs/proc/base.c:pid_revalidate
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_exe_link
  - fs/proc/base.c:comm_show
  - fs/proc/base.c:comm_write
  - fs/proc/base.c:sched_autogroup_write
  - fs/proc/base.c:sched_autogroup_show
  - fs/proc/base.c:sched_write
  - fs/proc/base.c:sched_show
  - fs/proc/base.c:proc_sessionid_read
  - fs/proc/base.c:proc_loginuid_write
  - fs/proc/base.c:proc_loginuid_read
  - fs/proc/base.c:oom_score_adj_read
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:oom_adj_read
  - fs/proc/base.c:proc_mem_open
  - fs/proc/base.c:proc_single_show
  - fs/proc/base.c:proc_pid_permission
  - fs/proc/base.c:proc_fd_access_allowed
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
```
```
In fs/proc/array.c (ffffffff813382c5)
Location: fs/proc/internal.h:118
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
```
```
In fs/proc/fd.c (ffffffff8133a09a)
Location: fs/proc/internal.h:118
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_fd_permission
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_lookupfd_common
  - fs/proc/fd.c:proc_fd_link
  - fs/proc/fd.c:tid_fd_revalidate
  - fs/proc/fd.c:seq_show
```
```
In fs/proc/namespaces.c (ffffffff8133c015)
Location: fs/proc/internal.h:118
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_lookup
  - fs/proc/namespaces.c:proc_ns_dir_readdir
  - fs/proc/namespaces.c:proc_ns_readlink
  - fs/proc/namespaces.c:proc_ns_get_link
```
```
In fs/proc/proc_net.c (ffffffff8133f145)
Location: fs/proc/internal.h:118
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_task_net
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
In fs/proc_namespace.c (ffffffff81319412)
Location: fs/proc/internal.h:114
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/proc/task_mmu.c (ffffffff813571f0)
Location: fs/proc/internal.h:114
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (ffffffff8135c84b)
Location: fs/proc/internal.h:114
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_getattr
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:proc_tid_comm_permission
  - fs/proc/base.c:tgid_pidfd_to_pid
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_open
  - fs/proc/base.c:proc_coredump_filter_write
  - fs/proc/base.c:proc_coredump_filter_read
  - fs/proc/base.c:proc_pid_attr_write
  - fs/proc/base.c:proc_pid_attr_read
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_pident_lookup
  - fs/proc/base.c:timerslack_ns_show
  - fs/proc/base.c:timerslack_ns_write
  - fs/proc/base.c:proc_timers_open
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:pid_delete_dentry
  - fs/proc/base.c:pid_revalidate
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_exe_link
  - fs/proc/base.c:comm_show
  - fs/proc/base.c:comm_write
  - fs/proc/base.c:sched_autogroup_write
  - fs/proc/base.c:sched_autogroup_show
  - fs/proc/base.c:sched_write
  - fs/proc/base.c:sched_show
  - fs/proc/base.c:proc_sessionid_read
  - fs/proc/base.c:proc_loginuid_write
  - fs/proc/base.c:proc_loginuid_read
  - fs/proc/base.c:oom_score_adj_read
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:oom_adj_read
  - fs/proc/base.c:proc_mem_open
  - fs/proc/base.c:proc_single_show
  - fs/proc/base.c:proc_pid_permission
  - fs/proc/base.c:proc_fd_access_allowed
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
```
```
In fs/proc/array.c (ffffffff81360975)
Location: fs/proc/internal.h:114
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
```
```
In fs/proc/fd.c (ffffffff81362233)
Location: fs/proc/internal.h:114
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_fd_permission
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_lookupfd_common
  - fs/proc/fd.c:proc_fd_link
  - fs/proc/fd.c:tid_fd_revalidate
  - fs/proc/fd.c:seq_show
```
```
In fs/proc/namespaces.c (ffffffff81364265)
Location: fs/proc/internal.h:114
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_lookup
  - fs/proc/namespaces.c:proc_ns_dir_readdir
  - fs/proc/namespaces.c:proc_ns_readlink
  - fs/proc/namespaces.c:proc_ns_get_link
```
```
In fs/proc/proc_net.c (ffffffff8136747d)
Location: fs/proc/internal.h:114
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_task_net
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
In fs/proc_namespace.c (ffffffff8132c242)
Location: fs/proc/internal.h:114
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/proc/task_mmu.c (ffffffff8136ed60)
Location: fs/proc/internal.h:114
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (ffffffff81374deb)
Location: fs/proc/internal.h:114
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_getattr
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:proc_tid_comm_permission
  - fs/proc/base.c:tgid_pidfd_to_pid
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_open
  - fs/proc/base.c:proc_coredump_filter_write
  - fs/proc/base.c:proc_coredump_filter_read
  - fs/proc/base.c:proc_pid_attr_write
  - fs/proc/base.c:proc_pid_attr_read
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_pident_lookup
  - fs/proc/base.c:timerslack_ns_show
  - fs/proc/base.c:timerslack_ns_write
  - fs/proc/base.c:proc_timers_open
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:pid_delete_dentry
  - fs/proc/base.c:pid_revalidate
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_exe_link
  - fs/proc/base.c:comm_show
  - fs/proc/base.c:comm_write
  - fs/proc/base.c:sched_autogroup_write
  - fs/proc/base.c:sched_autogroup_show
  - fs/proc/base.c:sched_write
  - fs/proc/base.c:sched_show
  - fs/proc/base.c:proc_sessionid_read
  - fs/proc/base.c:proc_loginuid_write
  - fs/proc/base.c:proc_loginuid_read
  - fs/proc/base.c:oom_score_adj_read
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:oom_adj_read
  - fs/proc/base.c:proc_mem_open
  - fs/proc/base.c:proc_single_show
  - fs/proc/base.c:proc_pid_permission
  - fs/proc/base.c:proc_fd_access_allowed
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
```
```
In fs/proc/array.c (ffffffff81378bd5)
Location: fs/proc/internal.h:114
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
```
```
In fs/proc/fd.c (ffffffff8137a493)
Location: fs/proc/internal.h:114
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_fd_permission
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_lookupfd_common
  - fs/proc/fd.c:proc_fd_link
  - fs/proc/fd.c:tid_fd_revalidate
  - fs/proc/fd.c:seq_show
```
```
In fs/proc/namespaces.c (ffffffff8137c4f5)
Location: fs/proc/internal.h:114
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_lookup
  - fs/proc/namespaces.c:proc_ns_dir_readdir
  - fs/proc/namespaces.c:proc_ns_readlink
  - fs/proc/namespaces.c:proc_ns_get_link
```
```
In fs/proc/proc_net.c (ffffffff8137f6fd)
Location: fs/proc/internal.h:114
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_task_net
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
In fs/proc_namespace.c (ffffffff81365f12)
Location: fs/proc/internal.h:123
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/proc/task_mmu.c (ffffffff813b7080)
Location: fs/proc/internal.h:123
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (ffffffff813bc9db)
Location: fs/proc/internal.h:123
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_getattr
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:proc_tid_comm_permission
  - fs/proc/base.c:tgid_pidfd_to_pid
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_open
  - fs/proc/base.c:proc_coredump_filter_write
  - fs/proc/base.c:proc_coredump_filter_read
  - fs/proc/base.c:proc_pid_attr_write
  - fs/proc/base.c:proc_pid_attr_read
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_pident_lookup
  - fs/proc/base.c:timerslack_ns_show
  - fs/proc/base.c:timerslack_ns_write
  - fs/proc/base.c:proc_timers_open
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:pid_delete_dentry
  - fs/proc/base.c:pid_revalidate
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_pid_readlink
  - fs/proc/base.c:proc_exe_link
  - fs/proc/base.c:comm_show
  - fs/proc/base.c:comm_write
  - fs/proc/base.c:timens_offsets_write
  - fs/proc/base.c:timens_offsets_show
  - fs/proc/base.c:sched_autogroup_write
  - fs/proc/base.c:sched_autogroup_show
  - fs/proc/base.c:sched_write
  - fs/proc/base.c:sched_show
  - fs/proc/base.c:proc_sessionid_read
  - fs/proc/base.c:proc_loginuid_write
  - fs/proc/base.c:proc_loginuid_read
  - fs/proc/base.c:oom_score_adj_read
  - fs/proc/base.c:oom_adj_read
  - fs/proc/base.c:proc_mem_open
  - fs/proc/base.c:proc_single_show
  - fs/proc/base.c:proc_pid_permission
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
```
```
In fs/proc/array.c (ffffffff813c1c45)
Location: fs/proc/internal.h:123
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
```
```
In fs/proc/fd.c (ffffffff813c37f9)
Location: fs/proc/internal.h:123
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_lookupfdinfo
  - fs/proc/fd.c:proc_fd_permission
  - fs/proc/fd.c:proc_lookupfd
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_fd_link
  - fs/proc/fd.c:tid_fd_revalidate
  - fs/proc/fd.c:seq_show
```
```
In fs/proc/namespaces.c (ffffffff813c6195)
Location: fs/proc/internal.h:123
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_lookup
  - fs/proc/namespaces.c:proc_ns_dir_readdir
  - fs/proc/namespaces.c:proc_ns_readlink
  - fs/proc/namespaces.c:proc_ns_get_link
```
```
In fs/proc/proc_net.c (ffffffff813c99cd)
Location: fs/proc/internal.h:123
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_task_net
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
In fs/proc_namespace.c (ffffffff81372de2)
Location: fs/proc/internal.h:123
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/proc/task_mmu.c (ffffffff813c89d7)
Location: fs/proc/internal.h:123
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (ffffffff813ce48b)
Location: fs/proc/internal.h:123
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_getattr
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:proc_tid_comm_permission
  - fs/proc/base.c:tgid_pidfd_to_pid
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_open
  - fs/proc/base.c:proc_coredump_filter_write
  - fs/proc/base.c:proc_coredump_filter_read
  - fs/proc/base.c:proc_pid_attr_write
  - fs/proc/base.c:proc_pid_attr_read
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_pident_lookup
  - fs/proc/base.c:timerslack_ns_show
  - fs/proc/base.c:timerslack_ns_write
  - fs/proc/base.c:proc_timers_open
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:pid_delete_dentry
  - fs/proc/base.c:pid_revalidate
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_pid_readlink
  - fs/proc/base.c:proc_exe_link
  - fs/proc/base.c:comm_show
  - fs/proc/base.c:comm_write
  - fs/proc/base.c:timens_offsets_write
  - fs/proc/base.c:timens_offsets_show
  - fs/proc/base.c:sched_autogroup_write
  - fs/proc/base.c:sched_autogroup_show
  - fs/proc/base.c:sched_write
  - fs/proc/base.c:sched_show
  - fs/proc/base.c:proc_sessionid_read
  - fs/proc/base.c:proc_loginuid_write
  - fs/proc/base.c:proc_loginuid_read
  - fs/proc/base.c:oom_score_adj_read
  - fs/proc/base.c:oom_adj_read
  - fs/proc/base.c:proc_mem_open
  - fs/proc/base.c:proc_single_show
  - fs/proc/base.c:proc_pid_permission
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
```
```
In fs/proc/array.c (ffffffff813d3d65)
Location: fs/proc/internal.h:123
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
```
```
In fs/proc/fd.c (ffffffff813d55f3)
Location: fs/proc/internal.h:123
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_fd_permission
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_lookupfd_common
  - fs/proc/fd.c:proc_fd_link
  - fs/proc/fd.c:tid_fd_revalidate
  - fs/proc/fd.c:seq_show
```
```
In fs/proc/namespaces.c (ffffffff813d8135)
Location: fs/proc/internal.h:123
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_lookup
  - fs/proc/namespaces.c:proc_ns_dir_readdir
  - fs/proc/namespaces.c:proc_ns_readlink
  - fs/proc/namespaces.c:proc_ns_get_link
```
```
In fs/proc/proc_net.c (ffffffff813db63d)
Location: fs/proc/internal.h:123
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_task_net
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
In fs/proc_namespace.c (ffffffff81379772)
Location: fs/proc/internal.h:123
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/proc/task_mmu.c (ffffffff813cfa19)
Location: fs/proc/internal.h:123
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (ffffffff813d510b)
Location: fs/proc/internal.h:123
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_getattr
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:tgid_pidfd_to_pid
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_open
  - fs/proc/base.c:proc_coredump_filter_write
  - fs/proc/base.c:proc_coredump_filter_read
  - fs/proc/base.c:proc_pid_attr_write
  - fs/proc/base.c:proc_pid_attr_read
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_pident_lookup
  - fs/proc/base.c:timerslack_ns_show
  - fs/proc/base.c:timerslack_ns_write
  - fs/proc/base.c:proc_timers_open
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:pid_delete_dentry
  - fs/proc/base.c:pid_revalidate
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_pid_readlink
  - fs/proc/base.c:proc_exe_link
  - fs/proc/base.c:comm_show
  - fs/proc/base.c:comm_write
  - fs/proc/base.c:timens_offsets_write
  - fs/proc/base.c:timens_offsets_show
  - fs/proc/base.c:sched_autogroup_write
  - fs/proc/base.c:sched_autogroup_show
  - fs/proc/base.c:sched_write
  - fs/proc/base.c:sched_show
  - fs/proc/base.c:proc_sessionid_read
  - fs/proc/base.c:proc_loginuid_write
  - fs/proc/base.c:proc_loginuid_read
  - fs/proc/base.c:oom_score_adj_read
  - fs/proc/base.c:oom_adj_read
  - fs/proc/base.c:proc_mem_open
  - fs/proc/base.c:proc_single_show
  - fs/proc/base.c:proc_pid_permission
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
```
```
In fs/proc/array.c (ffffffff813dab95)
Location: fs/proc/internal.h:123
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
```
```
In fs/proc/fd.c (ffffffff813dc74a)
Location: fs/proc/internal.h:123
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_lookupfdinfo
  - fs/proc/fd.c:proc_fd_permission
  - fs/proc/fd.c:proc_lookupfd
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_fd_link
  - fs/proc/fd.c:tid_fd_revalidate
  - fs/proc/fd.c:seq_show
```
```
In fs/proc/namespaces.c (ffffffff813defe5)
Location: fs/proc/internal.h:123
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_lookup
  - fs/proc/namespaces.c:proc_ns_dir_readdir
  - fs/proc/namespaces.c:proc_ns_readlink
  - fs/proc/namespaces.c:proc_ns_get_link
```
```
In fs/proc/proc_net.c (ffffffff813e256d)
Location: fs/proc/internal.h:123
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_task_net
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
In fs/proc_namespace.c (ffffffff813c62d2)
Location: fs/proc/internal.h:123
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/proc/task_mmu.c (ffffffff81420df9)
Location: fs/proc/internal.h:123
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (ffffffff81426a4b)
Location: fs/proc/internal.h:123
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_getattr
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:tgid_pidfd_to_pid
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_open
  - fs/proc/base.c:proc_coredump_filter_write
  - fs/proc/base.c:proc_coredump_filter_read
  - fs/proc/base.c:proc_pid_attr_write
  - fs/proc/base.c:proc_pid_attr_read
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_pident_lookup
  - fs/proc/base.c:timerslack_ns_show
  - fs/proc/base.c:timerslack_ns_write
  - fs/proc/base.c:proc_timers_open
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:pid_delete_dentry
  - fs/proc/base.c:pid_revalidate
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_pid_readlink
  - fs/proc/base.c:proc_exe_link
  - fs/proc/base.c:comm_show
  - fs/proc/base.c:comm_write
  - fs/proc/base.c:timens_offsets_write
  - fs/proc/base.c:timens_offsets_show
  - fs/proc/base.c:sched_autogroup_write
  - fs/proc/base.c:sched_autogroup_show
  - fs/proc/base.c:sched_write
  - fs/proc/base.c:sched_show
  - fs/proc/base.c:proc_sessionid_read
  - fs/proc/base.c:proc_loginuid_write
  - fs/proc/base.c:proc_loginuid_read
  - fs/proc/base.c:oom_score_adj_read
  - fs/proc/base.c:oom_adj_read
  - fs/proc/base.c:proc_mem_open
  - fs/proc/base.c:proc_single_show
  - fs/proc/base.c:proc_pid_permission
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
```
```
In fs/proc/array.c (ffffffff8142c335)
Location: fs/proc/internal.h:123
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
```
```
In fs/proc/fd.c (ffffffff8142dd3a)
Location: fs/proc/internal.h:123
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_lookupfdinfo
  - fs/proc/fd.c:proc_fd_permission
  - fs/proc/fd.c:proc_lookupfd
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_fd_link
  - fs/proc/fd.c:tid_fd_revalidate
  - fs/proc/fd.c:seq_fdinfo_open
  - fs/proc/fd.c:seq_show
```
```
In fs/proc/namespaces.c (ffffffff81430995)
Location: fs/proc/internal.h:123
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_lookup
  - fs/proc/namespaces.c:proc_ns_dir_readdir
  - fs/proc/namespaces.c:proc_ns_readlink
  - fs/proc/namespaces.c:proc_ns_get_link
```
```
In fs/proc/proc_net.c (ffffffff8143407d)
Location: fs/proc/internal.h:123
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_task_net
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
In fs/proc_namespace.c (ffffffff8144cb42)
Location: fs/proc/internal.h:118
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/proc/task_mmu.c (ffffffff81498c60)
Location: fs/proc/internal.h:118
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (ffffffff814a03db)
Location: fs/proc/internal.h:118
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_getattr
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:tgid_pidfd_to_pid
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_open
  - fs/proc/base.c:proc_coredump_filter_write
  - fs/proc/base.c:proc_coredump_filter_read
  - fs/proc/base.c:proc_pid_attr_write
  - fs/proc/base.c:proc_pid_attr_read
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_pident_lookup
  - fs/proc/base.c:timerslack_ns_show
  - fs/proc/base.c:timerslack_ns_write
  - fs/proc/base.c:proc_timers_open
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:pid_delete_dentry
  - fs/proc/base.c:pid_revalidate
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_pid_readlink
  - fs/proc/base.c:proc_pid_get_link
  - fs/proc/base.c:proc_exe_link
  - fs/proc/base.c:comm_show
  - fs/proc/base.c:comm_write
  - fs/proc/base.c:timens_offsets_write
  - fs/proc/base.c:timens_offsets_show
  - fs/proc/base.c:sched_autogroup_write
  - fs/proc/base.c:sched_autogroup_show
  - fs/proc/base.c:sched_write
  - fs/proc/base.c:sched_show
  - fs/proc/base.c:proc_sessionid_read
  - fs/proc/base.c:proc_loginuid_write
  - fs/proc/base.c:proc_loginuid_read
  - fs/proc/base.c:oom_score_adj_read
  - fs/proc/base.c:oom_adj_read
  - fs/proc/base.c:proc_mem_open
  - fs/proc/base.c:proc_single_show
  - fs/proc/base.c:proc_pid_permission
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
```
```
In fs/proc/array.c (ffffffff814a5615)
Location: fs/proc/internal.h:118
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
```
```
In fs/proc/fd.c (ffffffff814a7565)
Location: fs/proc/internal.h:118
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_open_fdinfo
  - fs/proc/fd.c:proc_lookupfdinfo
  - fs/proc/fd.c:proc_fd_permission
  - fs/proc/fd.c:proc_lookupfd
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_fd_link
  - fs/proc/fd.c:tid_fd_revalidate
  - fs/proc/fd.c:seq_show
```
```
In fs/proc/namespaces.c (ffffffff814aa6c5)
Location: fs/proc/internal.h:118
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_lookup
  - fs/proc/namespaces.c:proc_ns_dir_readdir
  - fs/proc/namespaces.c:proc_ns_readlink
  - fs/proc/namespaces.c:proc_ns_get_link
```
```
In fs/proc/proc_net.c (ffffffff814ae104)
Location: fs/proc/internal.h:118
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_task_net
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
In fs/proc_namespace.c (ffffffff814db0b2)
Location: fs/proc/internal.h:123
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/proc/task_mmu.c (ffffffff8152cf39)
Location: fs/proc/internal.h:123
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (ffffffff815352fb)
Location: fs/proc/internal.h:123
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_getattr
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:tgid_pidfd_to_pid
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_open
  - fs/proc/base.c:proc_coredump_filter_write
  - fs/proc/base.c:proc_coredump_filter_read
  - fs/proc/base.c:proc_pid_attr_write
  - fs/proc/base.c:proc_pid_attr_read
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_pident_lookup
  - fs/proc/base.c:timerslack_ns_show
  - fs/proc/base.c:timerslack_ns_write
  - fs/proc/base.c:proc_timers_open
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:pid_delete_dentry
  - fs/proc/base.c:pid_revalidate
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_pid_readlink
  - fs/proc/base.c:proc_pid_get_link
  - fs/proc/base.c:proc_exe_link
  - fs/proc/base.c:comm_show
  - fs/proc/base.c:comm_write
  - fs/proc/base.c:timens_offsets_write
  - fs/proc/base.c:timens_offsets_show
  - fs/proc/base.c:sched_autogroup_write
  - fs/proc/base.c:sched_autogroup_show
  - fs/proc/base.c:sched_write
  - fs/proc/base.c:sched_show
  - fs/proc/base.c:proc_sessionid_read
  - fs/proc/base.c:proc_loginuid_write
  - fs/proc/base.c:proc_loginuid_read
  - fs/proc/base.c:oom_score_adj_read
  - fs/proc/base.c:oom_adj_read
  - fs/proc/base.c:proc_mem_open
  - fs/proc/base.c:proc_single_show
  - fs/proc/base.c:proc_pid_permission
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
```
```
In fs/proc/array.c (ffffffff8153abf5)
Location: fs/proc/internal.h:123
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
```
```
In fs/proc/fd.c (ffffffff8153cc45)
Location: fs/proc/internal.h:123
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_open_fdinfo
  - fs/proc/fd.c:proc_lookupfdinfo
  - fs/proc/fd.c:proc_fd_permission
  - fs/proc/fd.c:proc_lookupfd
  - fs/proc/fd.c:proc_readfd_count
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_fd_link
  - fs/proc/fd.c:tid_fd_revalidate
  - fs/proc/fd.c:seq_show
```
```
In fs/proc/namespaces.c (ffffffff81540315)
Location: fs/proc/internal.h:123
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_lookup
  - fs/proc/namespaces.c:proc_ns_dir_readdir
  - fs/proc/namespaces.c:proc_ns_readlink
  - fs/proc/namespaces.c:proc_ns_get_link
```
```
In fs/proc/proc_net.c (ffffffff815446d4)
Location: fs/proc/internal.h:123
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_task_net
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
In fs/proc_namespace.c (ffffffff8150f662)
Location: fs/proc/internal.h:123
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/proc/task_mmu.c (ffffffff81564c09)
Location: fs/proc/internal.h:123
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (ffffffff8156d4cb)
Location: fs/proc/internal.h:123
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_getattr
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:tgid_pidfd_to_pid
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_open
  - fs/proc/base.c:proc_coredump_filter_write
  - fs/proc/base.c:proc_coredump_filter_read
  - fs/proc/base.c:proc_pid_attr_write
  - fs/proc/base.c:proc_pid_attr_read
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_pident_lookup
  - fs/proc/base.c:timerslack_ns_show
  - fs/proc/base.c:timerslack_ns_write
  - fs/proc/base.c:proc_timers_open
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:pid_delete_dentry
  - fs/proc/base.c:pid_revalidate
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_pid_readlink
  - fs/proc/base.c:proc_pid_get_link
  - fs/proc/base.c:proc_exe_link
  - fs/proc/base.c:comm_show
  - fs/proc/base.c:comm_write
  - fs/proc/base.c:timens_offsets_write
  - fs/proc/base.c:timens_offsets_show
  - fs/proc/base.c:sched_autogroup_write
  - fs/proc/base.c:sched_autogroup_show
  - fs/proc/base.c:sched_write
  - fs/proc/base.c:sched_show
  - fs/proc/base.c:proc_sessionid_read
  - fs/proc/base.c:proc_loginuid_write
  - fs/proc/base.c:proc_loginuid_read
  - fs/proc/base.c:oom_score_adj_read
  - fs/proc/base.c:oom_adj_read
  - fs/proc/base.c:proc_mem_open
  - fs/proc/base.c:proc_single_show
  - fs/proc/base.c:proc_pid_permission
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
```
```
In fs/proc/array.c (ffffffff81572ef3)
Location: fs/proc/internal.h:123
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
```
```
In fs/proc/fd.c (ffffffff81574f05)
Location: fs/proc/internal.h:123
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_open_fdinfo
  - fs/proc/fd.c:proc_lookupfdinfo
  - fs/proc/fd.c:proc_fd_permission
  - fs/proc/fd.c:proc_lookupfd
  - fs/proc/fd.c:proc_readfd_count
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_fd_link
  - fs/proc/fd.c:tid_fd_revalidate
  - fs/proc/fd.c:seq_show
```
```
In fs/proc/namespaces.c (ffffffff815782b5)
Location: fs/proc/internal.h:123
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_lookup
  - fs/proc/namespaces.c:proc_ns_dir_readdir
  - fs/proc/namespaces.c:proc_ns_readlink
  - fs/proc/namespaces.c:proc_ns_get_link
```
```
In fs/proc/proc_net.c (ffffffff8157c2d4)
Location: fs/proc/internal.h:123
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_task_net
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
In fs/proc_namespace.c (ffffffff81543b62)
Location: fs/proc/internal.h:123
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/proc/task_mmu.c (ffffffff8159b6c9)
Location: fs/proc/internal.h:123
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (ffffffff815a5e40)
Location: fs/proc/internal.h:123
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_getattr
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:tgid_pidfd_to_pid
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_open
  - fs/proc/base.c:proc_coredump_filter_write
  - fs/proc/base.c:proc_coredump_filter_read
  - fs/proc/base.c:proc_pid_attr_write
  - fs/proc/base.c:proc_pid_attr_read
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_pident_lookup
  - fs/proc/base.c:timerslack_ns_show
  - fs/proc/base.c:timerslack_ns_write
  - fs/proc/base.c:proc_timers_open
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:pid_delete_dentry
  - fs/proc/base.c:pid_revalidate
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_pid_readlink
  - fs/proc/base.c:proc_pid_get_link
  - fs/proc/base.c:proc_exe_link
  - fs/proc/base.c:comm_show
  - fs/proc/base.c:comm_write
  - fs/proc/base.c:timens_offsets_write
  - fs/proc/base.c:timens_offsets_show
  - fs/proc/base.c:sched_autogroup_write
  - fs/proc/base.c:sched_autogroup_show
  - fs/proc/base.c:sched_write
  - fs/proc/base.c:sched_show
  - fs/proc/base.c:proc_sessionid_read
  - fs/proc/base.c:proc_loginuid_write
  - fs/proc/base.c:proc_loginuid_read
  - fs/proc/base.c:oom_score_adj_read
  - fs/proc/base.c:oom_adj_read
  - fs/proc/base.c:proc_mem_open
  - fs/proc/base.c:proc_single_show
  - fs/proc/base.c:proc_pid_permission
  - fs/proc/base.c:lstats_write
  - fs/proc/base.c:lstats_show_proc
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
```
```
In fs/proc/array.c (ffffffff815abe23)
Location: fs/proc/internal.h:123
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
```
```
In fs/proc/fd.c (ffffffff815ad8d5)
Location: fs/proc/internal.h:123
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_open_fdinfo
  - fs/proc/fd.c:proc_fd_permission
  - fs/proc/fd.c:proc_readfd_count
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_lookupfd_common
  - fs/proc/fd.c:proc_fd_link
  - fs/proc/fd.c:tid_fd_revalidate
  - fs/proc/fd.c:seq_show
```
```
In fs/proc/namespaces.c (ffffffff815b09e5)
Location: fs/proc/internal.h:123
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_lookup
  - fs/proc/namespaces.c:proc_ns_dir_readdir
  - fs/proc/namespaces.c:proc_ns_readlink
  - fs/proc/namespaces.c:proc_ns_get_link
```
```
In fs/proc/proc_net.c (ffffffff815b4be4)
Location: fs/proc/internal.h:123
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_task_net
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
In fs/proc_namespace.c (ffff8000103e79d0)
Location: fs/proc/internal.h:114
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/proc/task_mmu.c (ffff8000104391cc)
Location: fs/proc/internal.h:114
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (ffff80001043e614)
Location: fs/proc/internal.h:114
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_getattr
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:proc_tid_comm_permission
  - fs/proc/base.c:tgid_pidfd_to_pid
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_open
  - fs/proc/base.c:proc_coredump_filter_write
  - fs/proc/base.c:proc_coredump_filter_read
  - fs/proc/base.c:proc_pid_attr_write
  - fs/proc/base.c:proc_pid_attr_read
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_pident_lookup
  - fs/proc/base.c:timerslack_ns_show
  - fs/proc/base.c:timerslack_ns_write
  - fs/proc/base.c:proc_timers_open
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:pid_delete_dentry
  - fs/proc/base.c:pid_revalidate
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_exe_link
  - fs/proc/base.c:comm_show
  - fs/proc/base.c:comm_write
  - fs/proc/base.c:sched_autogroup_write
  - fs/proc/base.c:sched_autogroup_show
  - fs/proc/base.c:sched_write
  - fs/proc/base.c:sched_show
  - fs/proc/base.c:proc_sessionid_read
  - fs/proc/base.c:proc_loginuid_write
  - fs/proc/base.c:proc_loginuid_read
  - fs/proc/base.c:oom_score_adj_read
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:oom_adj_read
  - fs/proc/base.c:proc_mem_open
  - fs/proc/base.c:proc_single_show
  - fs/proc/base.c:proc_pid_permission
  - fs/proc/base.c:proc_fd_access_allowed
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
```
```
In fs/proc/array.c (ffff800010444ac4)
Location: fs/proc/internal.h:114
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
```
```
In fs/proc/fd.c (ffff8000104467a0)
Location: fs/proc/internal.h:114
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_fd_permission
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_lookupfd_common
  - fs/proc/fd.c:proc_fd_link
  - fs/proc/fd.c:tid_fd_revalidate
  - fs/proc/fd.c:seq_show
```
```
In fs/proc/namespaces.c (ffff800010448d4c)
Location: fs/proc/internal.h:114
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_lookup
  - fs/proc/namespaces.c:proc_ns_dir_readdir
  - fs/proc/namespaces.c:proc_ns_readlink
  - fs/proc/namespaces.c:proc_ns_get_link
```
```
In fs/proc/proc_net.c (ffff80001044d040)
Location: fs/proc/internal.h:114
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_task_net
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
In fs/proc_namespace.c (c05bf544)
Location: fs/proc/internal.h:114
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/proc/task_mmu.c (c0600168)
Location: fs/proc/internal.h:114
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (c06052bc)
Location: fs/proc/internal.h:114
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_getattr
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:proc_tid_comm_permission
  - fs/proc/base.c:tgid_pidfd_to_pid
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_open
  - fs/proc/base.c:proc_coredump_filter_write
  - fs/proc/base.c:proc_coredump_filter_read
  - fs/proc/base.c:proc_pid_attr_write
  - fs/proc/base.c:proc_pid_attr_read
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_pident_lookup
  - fs/proc/base.c:timerslack_ns_show
  - fs/proc/base.c:timerslack_ns_write
  - fs/proc/base.c:proc_timers_open
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:pid_delete_dentry
  - fs/proc/base.c:pid_revalidate
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_exe_link
  - fs/proc/base.c:comm_show
  - fs/proc/base.c:comm_write
  - fs/proc/base.c:sched_autogroup_write
  - fs/proc/base.c:sched_autogroup_show
  - fs/proc/base.c:sched_write
  - fs/proc/base.c:sched_show
  - fs/proc/base.c:proc_sessionid_read
  - fs/proc/base.c:proc_loginuid_write
  - fs/proc/base.c:proc_loginuid_read
  - fs/proc/base.c:oom_score_adj_read
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:oom_adj_read
  - fs/proc/base.c:proc_mem_open
  - fs/proc/base.c:proc_single_show
  - fs/proc/base.c:proc_pid_permission
  - fs/proc/base.c:proc_fd_access_allowed
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
```
```
In fs/proc/array.c (c0609f68)
Location: fs/proc/internal.h:114
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
```
```
In fs/proc/fd.c (c060b8b0)
Location: fs/proc/internal.h:114
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_fd_permission
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_lookupfd_common
  - fs/proc/fd.c:proc_fd_link
  - fs/proc/fd.c:tid_fd_revalidate
  - fs/proc/fd.c:seq_show
```
```
In fs/proc/namespaces.c (c060de9c)
Location: fs/proc/internal.h:114
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_lookup
  - fs/proc/namespaces.c:proc_ns_dir_readdir
  - fs/proc/namespaces.c:proc_ns_readlink
  - fs/proc/namespaces.c:proc_ns_get_link
```
```
In fs/proc/proc_net.c (c06115fc)
Location: fs/proc/internal.h:114
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_task_net
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
In fs/proc_namespace.c (c0000000004ee198)
Location: fs/proc/internal.h:114
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/proc/task_mmu.c (c00000000054bfc8)
Location: fs/proc/internal.h:114
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (c000000000554168)
Location: fs/proc/internal.h:114
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_getattr
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:proc_tid_comm_permission
  - fs/proc/base.c:tgid_pidfd_to_pid
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_open
  - fs/proc/base.c:proc_coredump_filter_write
  - fs/proc/base.c:proc_coredump_filter_read
  - fs/proc/base.c:proc_pid_attr_write
  - fs/proc/base.c:proc_pid_attr_read
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_pident_lookup
  - fs/proc/base.c:timerslack_ns_show
  - fs/proc/base.c:timerslack_ns_write
  - fs/proc/base.c:proc_timers_open
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:pid_delete_dentry
  - fs/proc/base.c:pid_revalidate
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_exe_link
  - fs/proc/base.c:comm_show
  - fs/proc/base.c:comm_write
  - fs/proc/base.c:sched_autogroup_write
  - fs/proc/base.c:sched_autogroup_show
  - fs/proc/base.c:sched_write
  - fs/proc/base.c:sched_show
  - fs/proc/base.c:proc_sessionid_read
  - fs/proc/base.c:proc_loginuid_write
  - fs/proc/base.c:proc_loginuid_read
  - fs/proc/base.c:oom_score_adj_read
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:oom_adj_read
  - fs/proc/base.c:proc_mem_open
  - fs/proc/base.c:proc_single_show
  - fs/proc/base.c:proc_pid_permission
  - fs/proc/base.c:proc_fd_access_allowed
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
```
```
In fs/proc/array.c (c00000000055a8e0)
Location: fs/proc/internal.h:114
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
```
```
In fs/proc/fd.c (c00000000055c600)
Location: fs/proc/internal.h:114
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_fd_permission
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_lookupfd_common
  - fs/proc/fd.c:proc_fd_link
  - fs/proc/fd.c:tid_fd_revalidate
  - fs/proc/fd.c:seq_show
```
```
In fs/proc/namespaces.c (c00000000055f588)
Location: fs/proc/internal.h:114
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_lookup
  - fs/proc/namespaces.c:proc_ns_dir_readdir
  - fs/proc/namespaces.c:proc_ns_readlink
  - fs/proc/namespaces.c:proc_ns_get_link
```
```
In fs/proc/proc_net.c (c0000000005645c0)
Location: fs/proc/internal.h:114
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_task_net
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
In fs/proc_namespace.c (ffffffe00029c838)
Location: fs/proc/internal.h:114
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/proc/task_mmu.c (ffffffe0002d2f76)
Location: fs/proc/internal.h:114
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (ffffffe0002d4e6a)
Location: fs/proc/internal.h:114
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_getattr
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:proc_tid_comm_permission
  - fs/proc/base.c:tgid_pidfd_to_pid
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_open
  - fs/proc/base.c:proc_coredump_filter_write
  - fs/proc/base.c:proc_coredump_filter_read
  - fs/proc/base.c:proc_pid_attr_write
  - fs/proc/base.c:proc_pid_attr_read
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_pident_lookup
  - fs/proc/base.c:timerslack_ns_show
  - fs/proc/base.c:timerslack_ns_write
  - fs/proc/base.c:proc_timers_open
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:pid_delete_dentry
  - fs/proc/base.c:pid_revalidate
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_exe_link
  - fs/proc/base.c:comm_show
  - fs/proc/base.c:comm_write
  - fs/proc/base.c:sched_autogroup_write
  - fs/proc/base.c:sched_autogroup_show
  - fs/proc/base.c:sched_write
  - fs/proc/base.c:sched_show
  - fs/proc/base.c:proc_sessionid_read
  - fs/proc/base.c:proc_loginuid_write
  - fs/proc/base.c:proc_loginuid_read
  - fs/proc/base.c:oom_score_adj_read
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:oom_adj_read
  - fs/proc/base.c:proc_mem_open
  - fs/proc/base.c:proc_single_show
  - fs/proc/base.c:proc_pid_permission
  - fs/proc/base.c:proc_fd_access_allowed
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
```
```
In fs/proc/array.c (ffffffe0002dab42)
Location: fs/proc/internal.h:114
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
```
```
In fs/proc/fd.c (ffffffe0002dc774)
Location: fs/proc/internal.h:114
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_fd_permission
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_lookupfd_common
  - fs/proc/fd.c:proc_fd_link
  - fs/proc/fd.c:tid_fd_revalidate
  - fs/proc/fd.c:seq_show
```
```
In fs/proc/namespaces.c (ffffffe0002deb4a)
Location: fs/proc/internal.h:114
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_lookup
  - fs/proc/namespaces.c:proc_ns_dir_readdir
  - fs/proc/namespaces.c:proc_ns_readlink
  - fs/proc/namespaces.c:proc_ns_get_link
```
```
In fs/proc/proc_net.c (ffffffe0002e1d3a)
Location: fs/proc/internal.h:114
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_task_net
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
In fs/proc_namespace.c (ffffffff81324822)
Location: fs/proc/internal.h:114
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/proc/task_mmu.c (ffffffff81367340)
Location: fs/proc/internal.h:114
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (ffffffff8136d3cb)
Location: fs/proc/internal.h:114
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_getattr
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:proc_tid_comm_permission
  - fs/proc/base.c:tgid_pidfd_to_pid
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_open
  - fs/proc/base.c:proc_coredump_filter_write
  - fs/proc/base.c:proc_coredump_filter_read
  - fs/proc/base.c:proc_pid_attr_write
  - fs/proc/base.c:proc_pid_attr_read
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_pident_lookup
  - fs/proc/base.c:timerslack_ns_show
  - fs/proc/base.c:timerslack_ns_write
  - fs/proc/base.c:proc_timers_open
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:pid_delete_dentry
  - fs/proc/base.c:pid_revalidate
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_exe_link
  - fs/proc/base.c:comm_show
  - fs/proc/base.c:comm_write
  - fs/proc/base.c:sched_autogroup_write
  - fs/proc/base.c:sched_autogroup_show
  - fs/proc/base.c:sched_write
  - fs/proc/base.c:sched_show
  - fs/proc/base.c:proc_sessionid_read
  - fs/proc/base.c:proc_loginuid_write
  - fs/proc/base.c:proc_loginuid_read
  - fs/proc/base.c:oom_score_adj_read
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:oom_adj_read
  - fs/proc/base.c:proc_mem_open
  - fs/proc/base.c:proc_single_show
  - fs/proc/base.c:proc_pid_permission
  - fs/proc/base.c:proc_fd_access_allowed
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
```
```
In fs/proc/array.c (ffffffff813711b5)
Location: fs/proc/internal.h:114
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
```
```
In fs/proc/fd.c (ffffffff81372a73)
Location: fs/proc/internal.h:114
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_fd_permission
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_lookupfd_common
  - fs/proc/fd.c:proc_fd_link
  - fs/proc/fd.c:tid_fd_revalidate
  - fs/proc/fd.c:seq_show
```
```
In fs/proc/namespaces.c (ffffffff81374ad5)
Location: fs/proc/internal.h:114
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_lookup
  - fs/proc/namespaces.c:proc_ns_dir_readdir
  - fs/proc/namespaces.c:proc_ns_readlink
  - fs/proc/namespaces.c:proc_ns_get_link
```
```
In fs/proc/proc_net.c (ffffffff81377cdd)
Location: fs/proc/internal.h:114
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_task_net
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
In fs/proc_namespace.c (ffffffff813153c2)
Location: fs/proc/internal.h:114
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/proc/task_mmu.c (ffffffff81357fe0)
Location: fs/proc/internal.h:114
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (ffffffff8135de5b)
Location: fs/proc/internal.h:114
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_getattr
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:proc_tid_comm_permission
  - fs/proc/base.c:tgid_pidfd_to_pid
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_open
  - fs/proc/base.c:proc_coredump_filter_write
  - fs/proc/base.c:proc_coredump_filter_read
  - fs/proc/base.c:proc_pid_attr_write
  - fs/proc/base.c:proc_pid_attr_read
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_pident_lookup
  - fs/proc/base.c:timerslack_ns_show
  - fs/proc/base.c:timerslack_ns_write
  - fs/proc/base.c:proc_timers_open
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:pid_delete_dentry
  - fs/proc/base.c:pid_revalidate
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_exe_link
  - fs/proc/base.c:comm_show
  - fs/proc/base.c:comm_write
  - fs/proc/base.c:sched_autogroup_write
  - fs/proc/base.c:sched_autogroup_show
  - fs/proc/base.c:sched_write
  - fs/proc/base.c:sched_show
  - fs/proc/base.c:proc_sessionid_read
  - fs/proc/base.c:proc_loginuid_write
  - fs/proc/base.c:proc_loginuid_read
  - fs/proc/base.c:oom_score_adj_read
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:oom_adj_read
  - fs/proc/base.c:proc_mem_open
  - fs/proc/base.c:proc_single_show
  - fs/proc/base.c:proc_pid_permission
  - fs/proc/base.c:proc_fd_access_allowed
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
```
```
In fs/proc/array.c (ffffffff81361c45)
Location: fs/proc/internal.h:114
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
```
```
In fs/proc/fd.c (ffffffff81363543)
Location: fs/proc/internal.h:114
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_fd_permission
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_lookupfd_common
  - fs/proc/fd.c:proc_fd_link
  - fs/proc/fd.c:tid_fd_revalidate
  - fs/proc/fd.c:seq_show
```
```
In fs/proc/namespaces.c (ffffffff813655a5)
Location: fs/proc/internal.h:114
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_lookup
  - fs/proc/namespaces.c:proc_ns_dir_readdir
  - fs/proc/namespaces.c:proc_ns_readlink
  - fs/proc/namespaces.c:proc_ns_get_link
```
```
In fs/proc/proc_net.c (ffffffff813687ad)
Location: fs/proc/internal.h:114
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_task_net
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
In fs/proc_namespace.c (ffffffff813222f2)
Location: fs/proc/internal.h:114
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/proc/task_mmu.c (ffffffff81364e10)
Location: fs/proc/internal.h:114
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (ffffffff8136ae9b)
Location: fs/proc/internal.h:114
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_getattr
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:proc_tid_comm_permission
  - fs/proc/base.c:tgid_pidfd_to_pid
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_open
  - fs/proc/base.c:proc_coredump_filter_write
  - fs/proc/base.c:proc_coredump_filter_read
  - fs/proc/base.c:proc_pid_attr_write
  - fs/proc/base.c:proc_pid_attr_read
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_pident_lookup
  - fs/proc/base.c:timerslack_ns_show
  - fs/proc/base.c:timerslack_ns_write
  - fs/proc/base.c:proc_timers_open
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:pid_delete_dentry
  - fs/proc/base.c:pid_revalidate
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_exe_link
  - fs/proc/base.c:comm_show
  - fs/proc/base.c:comm_write
  - fs/proc/base.c:sched_autogroup_write
  - fs/proc/base.c:sched_autogroup_show
  - fs/proc/base.c:sched_write
  - fs/proc/base.c:sched_show
  - fs/proc/base.c:proc_sessionid_read
  - fs/proc/base.c:proc_loginuid_write
  - fs/proc/base.c:proc_loginuid_read
  - fs/proc/base.c:oom_score_adj_read
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:oom_adj_read
  - fs/proc/base.c:proc_mem_open
  - fs/proc/base.c:proc_single_show
  - fs/proc/base.c:proc_pid_permission
  - fs/proc/base.c:proc_fd_access_allowed
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
```
```
In fs/proc/array.c (ffffffff8136ec85)
Location: fs/proc/internal.h:114
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
```
```
In fs/proc/fd.c (ffffffff81370543)
Location: fs/proc/internal.h:114
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_fd_permission
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_lookupfd_common
  - fs/proc/fd.c:proc_fd_link
  - fs/proc/fd.c:tid_fd_revalidate
  - fs/proc/fd.c:seq_show
```
```
In fs/proc/namespaces.c (ffffffff813725a5)
Location: fs/proc/internal.h:114
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_lookup
  - fs/proc/namespaces.c:proc_ns_dir_readdir
  - fs/proc/namespaces.c:proc_ns_readlink
  - fs/proc/namespaces.c:proc_ns_get_link
```
```
In fs/proc/proc_net.c (ffffffff813757ad)
Location: fs/proc/internal.h:114
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_task_net
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
In fs/proc_namespace.c (ffffffff81334054)
Location: fs/proc/internal.h:114
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/proc/task_mmu.c (ffffffff81377e54)
Location: fs/proc/internal.h:114
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (ffffffff8137e8ab)
Location: fs/proc/internal.h:114
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_getattr
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:proc_tid_comm_permission
  - fs/proc/base.c:tgid_pidfd_to_pid
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_open
  - fs/proc/base.c:proc_coredump_filter_write
  - fs/proc/base.c:proc_coredump_filter_read
  - fs/proc/base.c:proc_pid_attr_write
  - fs/proc/base.c:proc_pid_attr_read
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_pident_lookup
  - fs/proc/base.c:timerslack_ns_show
  - fs/proc/base.c:timerslack_ns_write
  - fs/proc/base.c:proc_timers_open
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:pid_delete_dentry
  - fs/proc/base.c:pid_revalidate
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_exe_link
  - fs/proc/base.c:comm_show
  - fs/proc/base.c:comm_write
  - fs/proc/base.c:sched_autogroup_write
  - fs/proc/base.c:sched_autogroup_show
  - fs/proc/base.c:sched_write
  - fs/proc/base.c:sched_show
  - fs/proc/base.c:proc_sessionid_read
  - fs/proc/base.c:proc_loginuid_write
  - fs/proc/base.c:proc_loginuid_read
  - fs/proc/base.c:oom_score_adj_read
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:oom_adj_read
  - fs/proc/base.c:proc_mem_open
  - fs/proc/base.c:proc_single_show
  - fs/proc/base.c:proc_pid_permission
  - fs/proc/base.c:proc_fd_access_allowed
  - fs/proc/base.c:lstats_write
  - fs/proc/base.c:lstats_show_proc
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
```
```
In fs/proc/array.c (ffffffff81382615)
Location: fs/proc/internal.h:114
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
```
```
In fs/proc/fd.c (ffffffff81383f08)
Location: fs/proc/internal.h:114
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_fd_permission
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_lookupfd_common
  - fs/proc/fd.c:proc_fd_link
  - fs/proc/fd.c:tid_fd_revalidate
  - fs/proc/fd.c:seq_show
```
```
In fs/proc/namespaces.c (ffffffff81385f85)
Location: fs/proc/internal.h:114
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_lookup
  - fs/proc/namespaces.c:proc_ns_dir_readdir
  - fs/proc/namespaces.c:proc_ns_readlink
  - fs/proc/namespaces.c:proc_ns_get_link
```
```
In fs/proc/proc_net.c (ffffffff81389255)
Location: fs/proc/internal.h:114
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_task_net
```
</details>
</li>
</ul>

## Differences
