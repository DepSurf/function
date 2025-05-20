# Function: <code>ptrace_may_access</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool ptrace_may_access(struct task_struct *task, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff8108b910)
Location: kernel/ptrace.c:307
Inline: False
Direct callers:
  - kernel/fork.c:mm_access
  - kernel/kcmp.c:SyS_kcmp
  - kernel/kcmp.c:SyS_kcmp
  - kernel/futex.c:SyS_get_robust_list
  - kernel/futex_compat.c:compat_SyS_get_robust_list
  - kernel/events/core.c:SYSC_perf_event_open
  - fs/proc/base.c:proc_pid_wchan
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_fd_access_allowed
  - fs/proc/base.c:proc_pid_permission
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/array.c:do_task_stat
  - fs/proc/namespaces.c:proc_ns_readlink
  - fs/proc/namespaces.c:proc_ns_follow_link
```
**Symbols:**

```
ffffffff8108b910-ffffffff8108b956: ptrace_may_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool ptrace_may_access(struct task_struct *task, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff8108e910)
Location: kernel/ptrace.c:306
Inline: False
Direct callers:
  - kernel/fork.c:mm_access
  - kernel/kcmp.c:SyS_kcmp
  - kernel/kcmp.c:SyS_kcmp
  - kernel/futex.c:SyS_get_robust_list
  - kernel/futex_compat.c:compat_SyS_get_robust_list
  - kernel/events/core.c:SYSC_perf_event_open
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:timerslack_ns_show
  - fs/proc/base.c:timerslack_ns_write
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_pid_permission
  - fs/proc/base.c:proc_fd_access_allowed
  - fs/proc/base.c:proc_pid_wchan
  - fs/proc/array.c:do_task_stat
  - fs/proc/namespaces.c:proc_ns_readlink
  - fs/proc/namespaces.c:proc_ns_get_link
```
**Symbols:**

```
ffffffff8108e910-ffffffff8108e956: ptrace_may_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool ptrace_may_access(struct task_struct *task, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810938a0)
Location: kernel/ptrace.c:319
Inline: False
Direct callers:
  - kernel/fork.c:mm_access
  - kernel/kcmp.c:SyS_kcmp
  - kernel/kcmp.c:SyS_kcmp
  - kernel/futex.c:SyS_get_robust_list
  - kernel/futex_compat.c:compat_SyS_get_robust_list
  - kernel/events/core.c:SYSC_perf_event_open
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_pid_permission
  - fs/proc/base.c:proc_fd_access_allowed
  - fs/proc/base.c:proc_pid_wchan
  - fs/proc/array.c:do_task_stat
  - fs/proc/namespaces.c:proc_ns_readlink
  - fs/proc/namespaces.c:proc_ns_get_link
```
**Symbols:**

```
ffffffff810938a0-ffffffff810938e6: ptrace_may_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool ptrace_may_access(struct task_struct *task, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff81090990)
Location: kernel/ptrace.c:334
Inline: False
Direct callers:
  - kernel/fork.c:mm_access
  - kernel/kcmp.c:SyS_kcmp
  - kernel/kcmp.c:SyS_kcmp
  - kernel/futex.c:SyS_get_robust_list
  - kernel/futex_compat.c:compat_SyS_get_robust_list
  - kernel/events/core.c:SYSC_perf_event_open
  - mm/migrate.c:SYSC_move_pages
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_pid_permission
  - fs/proc/base.c:proc_fd_access_allowed
  - fs/proc/base.c:proc_pid_wchan
  - fs/proc/array.c:do_task_stat
  - fs/proc/namespaces.c:proc_ns_readlink
  - fs/proc/namespaces.c:proc_ns_get_link
```
**Symbols:**

```
ffffffff81090990-ffffffff810909d6: ptrace_may_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool ptrace_may_access(struct task_struct *task, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff81097800)
Location: kernel/ptrace.c:334
Inline: False
Direct callers:
  - kernel/fork.c:mm_access
  - kernel/kcmp.c:SyS_kcmp
  - kernel/kcmp.c:SyS_kcmp
  - kernel/futex.c:SyS_get_robust_list
  - kernel/futex_compat.c:compat_SyS_get_robust_list
  - kernel/events/core.c:SYSC_perf_event_open
  - mm/mempolicy.c:SYSC_migrate_pages
  - mm/migrate.c:SYSC_move_pages
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_pid_permission
  - fs/proc/base.c:proc_fd_access_allowed
  - fs/proc/base.c:proc_pid_wchan
  - fs/proc/array.c:do_task_stat
  - fs/proc/namespaces.c:proc_ns_readlink
  - fs/proc/namespaces.c:proc_ns_get_link
```
**Symbols:**

```
ffffffff81097800-ffffffff81097846: ptrace_may_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool ptrace_may_access(struct task_struct *task, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff8109b110)
Location: kernel/ptrace.c:334
Inline: False
Direct callers:
  - kernel/fork.c:mm_access
  - kernel/kcmp.c:__ia32_sys_kcmp
  - kernel/kcmp.c:__ia32_sys_kcmp
  - kernel/kcmp.c:__x64_sys_kcmp
  - kernel/kcmp.c:__x64_sys_kcmp
  - kernel/futex.c:__ia32_sys_get_robust_list
  - kernel/futex.c:__x64_sys_get_robust_list
  - kernel/futex_compat.c:__x32_compat_sys_get_robust_list
  - kernel/futex_compat.c:__ia32_compat_sys_get_robust_list
  - kernel/events/core.c:__do_sys_perf_event_open
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/migrate.c:kernel_move_pages
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_pid_permission
  - fs/proc/base.c:proc_fd_access_allowed
  - fs/proc/base.c:proc_pid_wchan
  - fs/proc/array.c:do_task_stat
  - fs/proc/namespaces.c:proc_ns_readlink
  - fs/proc/namespaces.c:proc_ns_get_link
```
**Symbols:**

```
ffffffff8109b110-ffffffff8109b156: ptrace_may_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool ptrace_may_access(struct task_struct *task, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810a3350)
Location: kernel/ptrace.c:334
Inline: False
Direct callers:
  - kernel/fork.c:mm_access
  - kernel/kcmp.c:__ia32_sys_kcmp
  - kernel/kcmp.c:__ia32_sys_kcmp
  - kernel/kcmp.c:__x64_sys_kcmp
  - kernel/kcmp.c:__x64_sys_kcmp
  - kernel/futex.c:__x32_compat_sys_get_robust_list
  - kernel/futex.c:__ia32_compat_sys_get_robust_list
  - kernel/futex.c:__ia32_sys_get_robust_list
  - kernel/futex.c:__x64_sys_get_robust_list
  - kernel/events/core.c:__do_sys_perf_event_open
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/migrate.c:kernel_move_pages
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_pid_permission
  - fs/proc/base.c:proc_fd_access_allowed
  - fs/proc/base.c:proc_pid_wchan
  - fs/proc/array.c:do_task_stat
  - fs/proc/namespaces.c:proc_ns_readlink
  - fs/proc/namespaces.c:proc_ns_get_link
```
**Symbols:**

```
ffffffff810a3350-ffffffff810a3396: ptrace_may_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool ptrace_may_access(struct task_struct *task, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810a8020)
Location: kernel/ptrace.c:349
Inline: False
Direct callers:
  - kernel/fork.c:mm_access
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/futex.c:__x32_compat_sys_get_robust_list
  - kernel/futex.c:__ia32_compat_sys_get_robust_list
  - kernel/futex.c:__ia32_sys_get_robust_list
  - kernel/futex.c:__x64_sys_get_robust_list
  - kernel/events/core.c:__do_sys_perf_event_open
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/migrate.c:kernel_move_pages
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_pid_permission
  - fs/proc/base.c:proc_fd_access_allowed
  - fs/proc/base.c:proc_pid_wchan
  - fs/proc/array.c:do_task_stat
  - fs/proc/namespaces.c:proc_ns_readlink
  - fs/proc/namespaces.c:proc_ns_get_link
```
**Symbols:**

```
ffffffff810a8020-ffffffff810a8068: ptrace_may_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool ptrace_may_access(struct task_struct *task, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810ae640)
Location: kernel/ptrace.c:354
Inline: False
Direct callers:
  - kernel/fork.c:mm_access
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/futex.c:__x32_compat_sys_get_robust_list
  - kernel/futex.c:__ia32_compat_sys_get_robust_list
  - kernel/futex.c:__ia32_sys_get_robust_list
  - kernel/futex.c:__x64_sys_get_robust_list
  - kernel/events/core.c:__do_sys_perf_event_open
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/migrate.c:kernel_move_pages
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_pid_permission
  - fs/proc/base.c:proc_fd_access_allowed
  - fs/proc/base.c:proc_pid_wchan
  - fs/proc/array.c:do_task_stat
  - fs/proc/namespaces.c:proc_ns_readlink
  - fs/proc/namespaces.c:proc_ns_get_link
```
**Symbols:**

```
ffffffff810ae640-ffffffff810ae688: ptrace_may_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool ptrace_may_access(struct task_struct *task, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810b61e0)
Location: kernel/ptrace.c:354
Inline: False
Direct callers:
  - kernel/fork.c:mm_access
  - kernel/pid.c:pidfd_getfd
  - kernel/nsproxy.c:validate_nsset
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/futex.c:__x32_compat_sys_get_robust_list
  - kernel/futex.c:__ia32_compat_sys_get_robust_list
  - kernel/futex.c:__ia32_sys_get_robust_list
  - kernel/futex.c:__x64_sys_get_robust_list
  - kernel/events/core.c:__do_sys_perf_event_open
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/migrate.c:kernel_move_pages
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:proc_pid_lookup
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_pid_readlink
  - fs/proc/base.c:proc_pid_permission
  - fs/proc/base.c:proc_pid_stack
  - fs/proc/base.c:proc_pid_wchan
  - fs/proc/array.c:do_task_stat
  - fs/proc/namespaces.c:proc_ns_readlink
  - fs/proc/namespaces.c:proc_ns_get_link
```
**Symbols:**

```
ffffffff810b61e0-ffffffff810b6228: ptrace_may_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool ptrace_may_access(struct task_struct *task, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810b13d0)
Location: kernel/ptrace.c:348
Inline: False
Direct callers:
  - kernel/fork.c:mm_access
  - kernel/pid.c:pidfd_getfd
  - kernel/nsproxy.c:validate_nsset
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/futex.c:__x32_compat_sys_get_robust_list
  - kernel/futex.c:__ia32_compat_sys_get_robust_list
  - kernel/futex.c:__ia32_sys_get_robust_list
  - kernel/futex.c:__x64_sys_get_robust_list
  - kernel/events/core.c:__do_sys_perf_event_open
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/migrate.c:find_mm_struct
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:proc_pid_lookup
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_pid_readlink
  - fs/proc/base.c:proc_pid_permission
  - fs/proc/base.c:proc_pid_stack
  - fs/proc/base.c:proc_pid_wchan
  - fs/proc/array.c:do_task_stat
  - fs/proc/namespaces.c:proc_ns_readlink
  - fs/proc/namespaces.c:proc_ns_get_link
```
**Symbols:**

```
ffffffff810b13d0-ffffffff810b1418: ptrace_may_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool ptrace_may_access(struct task_struct *task, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810b2990)
Location: kernel/ptrace.c:365
Inline: False
Direct callers:
  - kernel/fork.c:mm_access
  - kernel/pid.c:pidfd_getfd
  - kernel/nsproxy.c:validate_nsset
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/futex.c:__x32_compat_sys_get_robust_list
  - kernel/futex.c:__ia32_compat_sys_get_robust_list
  - kernel/futex.c:__ia32_sys_get_robust_list
  - kernel/futex.c:__x64_sys_get_robust_list
  - kernel/events/core.c:__do_sys_perf_event_open
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/migrate.c:find_mm_struct
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:proc_pid_lookup
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_pid_readlink
  - fs/proc/base.c:proc_pid_permission
  - fs/proc/base.c:proc_pid_stack
  - fs/proc/base.c:proc_pid_wchan
  - fs/proc/array.c:do_task_stat
  - fs/proc/namespaces.c:proc_ns_readlink
  - fs/proc/namespaces.c:proc_ns_get_link
```
**Symbols:**

```
ffffffff810b2990-ffffffff810b29d8: ptrace_may_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool ptrace_may_access(struct task_struct *task, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810c4b30)
Location: kernel/ptrace.c:365
Inline: False
Direct callers:
  - kernel/fork.c:mm_access
  - kernel/pid.c:pidfd_getfd
  - kernel/nsproxy.c:validate_nsset
  - kernel/sched/core_sched.c:sched_core_share_pid
  - kernel/sched/core_sched.c:sched_core_share_pid
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/futex.c:__x64_compat_sys_get_robust_list
  - kernel/futex.c:__ia32_compat_sys_get_robust_list
  - kernel/futex.c:__ia32_sys_get_robust_list
  - kernel/futex.c:__x64_sys_get_robust_list
  - kernel/events/core.c:__do_sys_perf_event_open
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/migrate.c:find_mm_struct
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:proc_pid_lookup
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_pid_readlink
  - fs/proc/base.c:proc_pid_permission
  - fs/proc/base.c:proc_pid_stack
  - fs/proc/base.c:proc_pid_wchan
  - fs/proc/array.c:do_task_stat
  - fs/proc/fd.c:seq_fdinfo_open
  - fs/proc/namespaces.c:proc_ns_readlink
  - fs/proc/namespaces.c:proc_ns_get_link
```
**Symbols:**

```
ffffffff810c4b30-ffffffff810c4b78: ptrace_may_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool ptrace_may_access(struct task_struct *task, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810dbf20)
Location: kernel/ptrace.c:359
Inline: False
Direct callers:
  - kernel/fork.c:mm_access
  - kernel/pid.c:pidfd_getfd
  - kernel/nsproxy.c:validate_nsset
  - kernel/sched/build_utility.c:sched_core_share_pid
  - kernel/sched/build_utility.c:sched_core_share_pid
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/futex/syscalls.c:__ia32_compat_sys_get_robust_list
  - kernel/futex/syscalls.c:__ia32_sys_get_robust_list
  - kernel/futex/syscalls.c:__x64_sys_get_robust_list
  - kernel/events/core.c:__do_sys_perf_event_open
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/migrate.c:find_mm_struct
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:proc_pid_lookup
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_pid_readlink
  - fs/proc/base.c:proc_pid_get_link
  - fs/proc/base.c:proc_pid_permission
  - fs/proc/base.c:proc_pid_syscall
  - fs/proc/base.c:proc_pid_stack
  - fs/proc/base.c:proc_pid_wchan
  - fs/proc/array.c:do_task_stat
  - fs/proc/fd.c:proc_open_fdinfo
  - fs/proc/namespaces.c:proc_ns_readlink
  - fs/proc/namespaces.c:proc_ns_get_link
```
**Symbols:**

```
ffffffff810dbf20-ffffffff810dbf6c: ptrace_may_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool ptrace_may_access(struct task_struct *task, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810fc050)
Location: kernel/ptrace.c:359
Inline: False
Direct callers:
  - kernel/fork.c:mm_access
  - kernel/pid.c:pidfd_getfd
  - kernel/nsproxy.c:validate_nsset
  - kernel/sched/build_utility.c:sched_core_share_pid
  - kernel/sched/build_utility.c:sched_core_share_pid
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/futex/syscalls.c:__ia32_compat_sys_get_robust_list
  - kernel/futex/syscalls.c:__ia32_sys_get_robust_list
  - kernel/futex/syscalls.c:__x64_sys_get_robust_list
  - kernel/events/core.c:__do_sys_perf_event_open
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/migrate.c:find_mm_struct
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:proc_pid_lookup
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_pid_readlink
  - fs/proc/base.c:proc_pid_get_link
  - fs/proc/base.c:proc_pid_permission
  - fs/proc/base.c:proc_pid_syscall
  - fs/proc/base.c:proc_pid_stack
  - fs/proc/base.c:proc_pid_wchan
  - fs/proc/array.c:do_task_stat
  - fs/proc/fd.c:proc_open_fdinfo
  - fs/proc/namespaces.c:proc_ns_readlink
  - fs/proc/namespaces.c:proc_ns_get_link
```
**Symbols:**

```
ffffffff810fc050-ffffffff810fc09c: ptrace_may_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool ptrace_may_access(struct task_struct *task, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff811080f0)
Location: kernel/ptrace.c:360
Inline: False
Direct callers:
  - kernel/fork.c:mm_access
  - kernel/pid.c:pidfd_getfd
  - kernel/nsproxy.c:validate_nsset
  - kernel/sched/build_utility.c:sched_core_share_pid
  - kernel/sched/build_utility.c:sched_core_share_pid
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/futex/syscalls.c:__ia32_compat_sys_get_robust_list
  - kernel/futex/syscalls.c:__ia32_sys_get_robust_list
  - kernel/futex/syscalls.c:__x64_sys_get_robust_list
  - kernel/events/core.c:__do_sys_perf_event_open
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/migrate.c:find_mm_struct
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:proc_pid_lookup
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_pid_readlink
  - fs/proc/base.c:proc_pid_get_link
  - fs/proc/base.c:proc_pid_permission
  - fs/proc/base.c:proc_pid_syscall
  - fs/proc/base.c:proc_pid_stack
  - fs/proc/base.c:proc_pid_wchan
  - fs/proc/array.c:do_task_stat
  - fs/proc/fd.c:proc_open_fdinfo
  - fs/proc/namespaces.c:proc_ns_readlink
  - fs/proc/namespaces.c:proc_ns_get_link
```
**Symbols:**

```
ffffffff811080f0-ffffffff8110813c: ptrace_may_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool ptrace_may_access(struct task_struct *task, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff81111a80)
Location: kernel/ptrace.c:349
Inline: False
Direct callers:
  - kernel/fork.c:mm_access
  - kernel/pid.c:pidfd_getfd
  - kernel/nsproxy.c:validate_nsset
  - kernel/sched/build_utility.c:sched_core_share_pid
  - kernel/sched/build_utility.c:sched_core_share_pid
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/futex/syscalls.c:__ia32_compat_sys_get_robust_list
  - kernel/futex/syscalls.c:__ia32_sys_get_robust_list
  - kernel/futex/syscalls.c:__x64_sys_get_robust_list
  - kernel/events/core.c:__do_sys_perf_event_open
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/migrate.c:find_mm_struct
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:proc_pid_lookup
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_pid_readlink
  - fs/proc/base.c:proc_pid_get_link
  - fs/proc/base.c:proc_pid_permission
  - fs/proc/base.c:proc_pid_syscall
  - fs/proc/base.c:proc_pid_stack
  - fs/proc/base.c:proc_pid_wchan
  - fs/proc/array.c:do_task_stat
  - fs/proc/fd.c:proc_open_fdinfo
  - fs/proc/namespaces.c:proc_ns_readlink
  - fs/proc/namespaces.c:proc_ns_get_link
```
**Symbols:**

```
ffffffff81111a80-ffffffff81111acc: ptrace_may_access (STB_GLOBAL)
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
bool ptrace_may_access(struct task_struct *task, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffff800010108680)
Location: kernel/ptrace.c:354
Inline: False
Direct callers:
  - kernel/fork.c:mm_access
  - kernel/kcmp.c:__arm64_sys_kcmp
  - kernel/kcmp.c:__arm64_sys_kcmp
  - kernel/futex.c:__arm64_compat_sys_get_robust_list
  - kernel/futex.c:__arm64_sys_get_robust_list
  - kernel/events/core.c:__do_sys_perf_event_open
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/migrate.c:kernel_move_pages
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_pid_permission
  - fs/proc/base.c:proc_fd_access_allowed
  - fs/proc/base.c:proc_pid_wchan
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/namespaces.c:proc_ns_readlink
  - fs/proc/namespaces.c:proc_ns_get_link
```
**Symbols:**

```
ffff800010108680-ffff800010108714: ptrace_may_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool ptrace_may_access(struct task_struct *task, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (c0361ff8)
Location: kernel/ptrace.c:354
Inline: False
Direct callers:
  - kernel/fork.c:mm_access
  - kernel/kcmp.c:__se_sys_kcmp
  - kernel/kcmp.c:__se_sys_kcmp
  - kernel/futex.c:__se_sys_get_robust_list
  - kernel/events/core.c:__do_sys_perf_event_open
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:proc_fd_access_allowed
  - fs/proc/base.c:proc_pid_wchan
  - fs/proc/array.c:do_task_stat
  - fs/proc/namespaces.c:proc_ns_readlink
  - fs/proc/namespaces.c:proc_ns_get_link
```
**Symbols:**

```
c0361ff8-c0362050: ptrace_may_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool ptrace_may_access(struct task_struct *task, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (c00000000014fcb0)
Location: kernel/ptrace.c:354
Inline: False
Direct callers:
  - kernel/fork.c:mm_access
  - kernel/kcmp.c:__se_sys_kcmp
  - kernel/kcmp.c:__se_sys_kcmp
  - kernel/futex.c:__se_compat_sys_get_robust_list
  - kernel/futex.c:__se_sys_get_robust_list
  - kernel/events/core.c:__do_sys_perf_event_open
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/migrate.c:kernel_move_pages
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:proc_fd_access_allowed
  - fs/proc/base.c:proc_pid_wchan
  - fs/proc/array.c:do_task_stat
  - fs/proc/namespaces.c:proc_ns_readlink
  - fs/proc/namespaces.c:proc_ns_get_link
```
**Symbols:**

```
c00000000014fcb0-c00000000014fd80: ptrace_may_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool ptrace_may_access(struct task_struct *task, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffe0000cbfca)
Location: kernel/ptrace.c:354
Inline: False
Direct callers:
  - kernel/fork.c:mm_access
  - kernel/kcmp.c:__se_sys_kcmp
  - kernel/kcmp.c:__se_sys_kcmp
  - kernel/futex.c:__se_sys_get_robust_list
  - kernel/events/core.c:__do_sys_perf_event_open
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:proc_fd_access_allowed
  - fs/proc/base.c:proc_pid_wchan
  - fs/proc/array.c:do_task_stat
  - fs/proc/namespaces.c:proc_ns_readlink
  - fs/proc/namespaces.c:proc_ns_get_link
```
**Symbols:**

```
ffffffe0000cbfca-ffffffe0000cc04c: ptrace_may_access (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
bool ptrace_may_access(struct task_struct *task, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810a89b0)
Location: kernel/ptrace.c:354
Inline: False
Direct callers:
  - kernel/fork.c:mm_access
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/futex.c:__x32_compat_sys_get_robust_list
  - kernel/futex.c:__ia32_compat_sys_get_robust_list
  - kernel/futex.c:__ia32_sys_get_robust_list
  - kernel/futex.c:__x64_sys_get_robust_list
  - kernel/events/core.c:__do_sys_perf_event_open
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/migrate.c:kernel_move_pages
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_pid_permission
  - fs/proc/base.c:proc_fd_access_allowed
  - fs/proc/base.c:proc_pid_wchan
  - fs/proc/array.c:do_task_stat
  - fs/proc/namespaces.c:proc_ns_readlink
  - fs/proc/namespaces.c:proc_ns_get_link
```
**Symbols:**

```
ffffffff810a89b0-ffffffff810a89f8: ptrace_may_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool ptrace_may_access(struct task_struct *task, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff81097380)
Location: kernel/ptrace.c:354
Inline: False
Direct callers:
  - kernel/fork.c:mm_access
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/futex.c:__x32_compat_sys_get_robust_list
  - kernel/futex.c:__ia32_compat_sys_get_robust_list
  - kernel/futex.c:__ia32_sys_get_robust_list
  - kernel/futex.c:__x64_sys_get_robust_list
  - kernel/events/core.c:__do_sys_perf_event_open
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/migrate.c:kernel_move_pages
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_pid_permission
  - fs/proc/base.c:proc_fd_access_allowed
  - fs/proc/base.c:proc_pid_wchan
  - fs/proc/array.c:do_task_stat
  - fs/proc/namespaces.c:proc_ns_readlink
  - fs/proc/namespaces.c:proc_ns_get_link
```
**Symbols:**

```
ffffffff81097380-ffffffff810973c8: ptrace_may_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool ptrace_may_access(struct task_struct *task, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810a7f10)
Location: kernel/ptrace.c:354
Inline: False
Direct callers:
  - kernel/fork.c:mm_access
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/futex.c:__x32_compat_sys_get_robust_list
  - kernel/futex.c:__ia32_compat_sys_get_robust_list
  - kernel/futex.c:__ia32_sys_get_robust_list
  - kernel/futex.c:__x64_sys_get_robust_list
  - kernel/events/core.c:__do_sys_perf_event_open
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/migrate.c:kernel_move_pages
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_pid_permission
  - fs/proc/base.c:proc_fd_access_allowed
  - fs/proc/base.c:proc_pid_wchan
  - fs/proc/array.c:do_task_stat
  - fs/proc/namespaces.c:proc_ns_readlink
  - fs/proc/namespaces.c:proc_ns_get_link
```
**Symbols:**

```
ffffffff810a7f10-ffffffff810a7f58: ptrace_may_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool ptrace_may_access(struct task_struct *task, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810b0040)
Location: kernel/ptrace.c:354
Inline: False
Direct callers:
  - kernel/fork.c:mm_access
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/futex.c:__x32_compat_sys_get_robust_list
  - kernel/futex.c:__ia32_compat_sys_get_robust_list
  - kernel/futex.c:__ia32_sys_get_robust_list
  - kernel/futex.c:__x64_sys_get_robust_list
  - kernel/events/core.c:__do_sys_perf_event_open
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/migrate.c:kernel_move_pages
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_pid_permission
  - fs/proc/base.c:proc_fd_access_allowed
  - fs/proc/base.c:proc_pid_wchan
  - fs/proc/array.c:do_task_stat
  - fs/proc/namespaces.c:proc_ns_readlink
  - fs/proc/namespaces.c:proc_ns_get_link
```
**Symbols:**

```
ffffffff810b0040-ffffffff810b0088: ptrace_may_access (STB_GLOBAL)
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
