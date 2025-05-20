# Function: <code>__register_sysctl_init</code>

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
In <code>5.8</code>: Absent ⚠️
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
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __register_sysctl_init(const char *path, struct ctl_table *table, const char *table_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff834968d5)
Location: fs/proc/proc_sysctl.c:1433
Inline: False
Direct callers:
  - init/do_mounts_initrd.c:kernel_do_mounts_initrd_sysctls_init
  - kernel/panic.c:kernel_panic_sysctls_init
  - kernel/reboot.c:reboot_ksysfs_init
  - kernel/sched/core.c:sched_core_sysctl_init
  - kernel/sched/fair.c:sched_fair_sysctl_init
  - kernel/sched/build_policy.c:sched_dl_sysctl_init
  - kernel/sched/build_policy.c:sched_rt_sysctl_init
  - kernel/sched/build_utility.c:autogroup_init
  - kernel/sched/build_utility.c:sched_energy_aware_sysctl_init
  - kernel/printk/sysctl.c:printk_sysctl_init
  - kernel/acct.c:kernel_acct_sysctls_init
  - kernel/kexec_core.c:kexec_core_sysctl_init
  - kernel/kprobes.c:init_kprobes
  - kernel/hung_task.c:hung_task_init
  - kernel/watchdog.c:lockup_detector_init
  - kernel/delayacct.c:kernel_delayacct_sysctls_init
  - kernel/trace/ftrace.c:ftrace_sysctl_init
  - kernel/bpf/syscall.c:bpf_syscall_sysctl_init
  - mm/oom_kill.c:oom_init
  - mm/page-writeback.c:page_writeback_init
  - mm/hugetlb_vmemmap.c:hugetlb_vmemmap_sysctls_init
  - fs/file_table.c:init_fs_stat_sysctls
  - fs/exec.c:init_fs_exec_sysctls
  - fs/pipe.c:init_pipe_fs
  - fs/namei.c:init_fs_namei_sysctls
  - fs/dcache.c:init_fs_dcache_sysctls
  - fs/inode.c:init_fs_inode_sysctls
  - fs/namespace.c:init_fs_namespace_sysctls
  - fs/notify/dnotify/dnotify.c:dnotify_init
  - fs/aio.c:aio_setup
  - fs/locks.c:init_fs_locks_sysctls
  - fs/coredump.c:init_fs_coredump_sysctls
  - drivers/char/random.c:random_sysctls_init
```
**Symbols:**

```
ffffffff834968d5-ffffffff83496921: __register_sysctl_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __register_sysctl_init(const char *path, struct ctl_table *table, const char *table_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff83ecba00)
Location: fs/proc/proc_sysctl.c:1432
Inline: False
Direct callers:
  - init/do_mounts_initrd.c:kernel_do_mounts_initrd_sysctls_init
  - arch/x86/kernel/cpu/intel.c:sld_mitigate_sysctl_init
  - kernel/panic.c:kernel_panic_sysctls_init
  - kernel/exit.c:kernel_exit_sysctls_init
  - kernel/reboot.c:reboot_ksysfs_init
  - kernel/sched/core.c:sched_core_sysctl_init
  - kernel/sched/fair.c:sched_fair_sysctl_init
  - kernel/sched/build_policy.c:sched_dl_sysctl_init
  - kernel/sched/build_policy.c:sched_rt_sysctl_init
  - kernel/sched/build_utility.c:autogroup_init
  - kernel/sched/build_utility.c:sched_energy_aware_sysctl_init
  - kernel/printk/sysctl.c:printk_sysctl_init
  - kernel/acct.c:kernel_acct_sysctls_init
  - kernel/kexec_core.c:kexec_core_sysctl_init
  - kernel/kprobes.c:init_kprobes
  - kernel/hung_task.c:hung_task_init
  - kernel/watchdog.c:lockup_detector_init
  - kernel/delayacct.c:kernel_delayacct_sysctls_init
  - kernel/trace/ftrace.c:ftrace_sysctl_init
  - kernel/bpf/syscall.c:bpf_syscall_sysctl_init
  - mm/oom_kill.c:oom_init
  - mm/page-writeback.c:page_writeback_init
  - mm/hugetlb_vmemmap.c:hugetlb_vmemmap_init
  - fs/file_table.c:init_fs_stat_sysctls
  - fs/exec.c:init_fs_exec_sysctls
  - fs/pipe.c:init_pipe_fs
  - fs/namei.c:init_fs_namei_sysctls
  - fs/dcache.c:init_fs_dcache_sysctls
  - fs/inode.c:init_fs_inode_sysctls
  - fs/namespace.c:init_fs_namespace_sysctls
  - fs/notify/dnotify/dnotify.c:dnotify_init
  - fs/aio.c:aio_setup
  - fs/locks.c:init_fs_locks_sysctls
  - fs/coredump.c:init_fs_coredump_sysctls
  - drivers/char/random.c:random_sysctls_init
```
**Symbols:**

```
ffffffff83ecba00-ffffffff83ecba5d: __register_sysctl_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __register_sysctl_init(const char *path, struct ctl_table *table, const char *table_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff836f0a80)
Location: fs/proc/proc_sysctl.c:1447
Inline: False
Direct callers:
  - init/do_mounts_initrd.c:kernel_do_mounts_initrd_sysctls_init
  - arch/x86/kernel/cpu/intel.c:sld_mitigate_sysctl_init
  - kernel/panic.c:kernel_panic_sysctls_init
  - kernel/exit.c:kernel_exit_sysctls_init
  - kernel/sysctl.c:sysctl_init_bases
  - kernel/sysctl.c:sysctl_init_bases
  - kernel/signal.c:init_signal_sysctls
  - kernel/umh.c:init_umh_sysctls
  - kernel/reboot.c:reboot_ksysfs_init
  - kernel/sched/core.c:sched_core_sysctl_init
  - kernel/sched/fair.c:sched_fair_sysctl_init
  - kernel/sched/build_policy.c:sched_dl_sysctl_init
  - kernel/sched/build_policy.c:sched_rt_sysctl_init
  - kernel/sched/build_utility.c:autogroup_init
  - kernel/sched/build_utility.c:sched_energy_aware_sysctl_init
  - kernel/printk/sysctl.c:printk_sysctl_init
  - kernel/acct.c:kernel_acct_sysctls_init
  - kernel/kexec_core.c:kexec_core_sysctl_init
  - kernel/pid_namespace.c:pid_namespaces_init
  - kernel/kprobes.c:init_kprobes
  - kernel/hung_task.c:hung_task_init
  - kernel/watchdog.c:lockup_detector_check
  - kernel/watchdog.c:lockup_detector_check
  - kernel/seccomp.c:seccomp_sysctl_init
  - kernel/delayacct.c:kernel_delayacct_sysctls_init
  - kernel/trace/ftrace.c:ftrace_sysctl_init
  - kernel/trace/trace_events_user.c:trace_events_user_init
  - kernel/bpf/syscall.c:bpf_syscall_sysctl_init
  - mm/oom_kill.c:oom_init
  - mm/page-writeback.c:page_writeback_init
  - mm/compaction.c:kcompactd_init
  - mm/page_alloc.c:page_alloc_sysctl_init
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb_vmemmap.c:hugetlb_vmemmap_init
  - mm/memory-failure.c:memory_failure_init
  - fs/file_table.c:init_fs_stat_sysctls
  - fs/exec.c:init_fs_exec_sysctls
  - fs/pipe.c:init_pipe_fs
  - fs/namei.c:init_fs_namei_sysctls
  - fs/dcache.c:init_fs_dcache_sysctls
  - fs/inode.c:init_fs_inode_sysctls
  - fs/namespace.c:init_fs_namespace_sysctls
  - fs/notify/dnotify/dnotify.c:dnotify_init
  - fs/userfaultfd.c:userfaultfd_init
  - fs/aio.c:aio_setup
  - fs/locks.c:init_fs_locks_sysctls
  - fs/coredump.c:init_fs_coredump_sysctls
  - fs/sysctls.c:init_fs_sysctls
  - fs/quota/dquot.c:dquot_init
  - security/keys/sysctl.c:init_security_keys_sysctls
  - drivers/xen/balloon.c:balloon_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/char/random.c:random_sysctls_init
```
**Symbols:**

```
ffffffff836f0a80-ffffffff836f0add: __register_sysctl_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __register_sysctl_init(const char *path, struct ctl_table *table, const char *table_name, size_t table_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff83923b10)
Location: fs/proc/proc_sysctl.c:1443
Inline: False
Direct callers:
  - init/do_mounts_initrd.c:kernel_do_mounts_initrd_sysctls_init
  - arch/x86/kernel/cpu/intel.c:sld_mitigate_sysctl_init
  - kernel/panic.c:kernel_panic_sysctls_init
  - kernel/exit.c:kernel_exit_sysctls_init
  - kernel/sysctl.c:sysctl_init_bases
  - kernel/sysctl.c:sysctl_init_bases
  - kernel/signal.c:init_signal_sysctls
  - kernel/umh.c:init_umh_sysctls
  - kernel/reboot.c:reboot_ksysfs_init
  - kernel/sched/core.c:sched_core_sysctl_init
  - kernel/sched/fair.c:sched_fair_sysctl_init
  - kernel/sched/build_policy.c:sched_dl_sysctl_init
  - kernel/sched/build_policy.c:sched_rt_sysctl_init
  - kernel/sched/build_utility.c:autogroup_init
  - kernel/sched/build_utility.c:sched_energy_aware_sysctl_init
  - kernel/printk/sysctl.c:printk_sysctl_init
  - kernel/acct.c:kernel_acct_sysctls_init
  - kernel/kexec_core.c:kexec_core_sysctl_init
  - kernel/pid_namespace.c:pid_namespaces_init
  - kernel/kprobes.c:init_kprobes
  - kernel/hung_task.c:hung_task_init
  - kernel/watchdog.c:lockup_detector_check
  - kernel/watchdog.c:lockup_detector_check
  - kernel/seccomp.c:seccomp_sysctl_init
  - kernel/delayacct.c:kernel_delayacct_sysctls_init
  - kernel/latencytop.c:init_lstats_procfs
  - kernel/trace/ftrace.c:ftrace_sysctl_init
  - kernel/trace/trace_events_user.c:trace_events_user_init
  - kernel/bpf/syscall.c:bpf_syscall_sysctl_init
  - mm/oom_kill.c:oom_init
  - mm/page-writeback.c:page_writeback_init
  - mm/compaction.c:kcompactd_init
  - mm/page_alloc.c:page_alloc_sysctl_init
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb_vmemmap.c:hugetlb_vmemmap_init
  - mm/memory-failure.c:memory_failure_init
  - fs/file_table.c:init_fs_stat_sysctls
  - fs/exec.c:init_fs_exec_sysctls
  - fs/pipe.c:init_pipe_fs
  - fs/namei.c:init_fs_namei_sysctls
  - fs/dcache.c:init_fs_dcache_sysctls
  - fs/inode.c:init_fs_inode_sysctls
  - fs/namespace.c:init_fs_namespace_sysctls
  - fs/notify/dnotify/dnotify.c:dnotify_init
  - fs/userfaultfd.c:userfaultfd_init
  - fs/aio.c:aio_setup
  - fs/locks.c:init_fs_locks_sysctls
  - fs/coredump.c:init_fs_coredump_sysctls
  - fs/sysctls.c:init_fs_sysctls
  - fs/quota/dquot.c:dquot_init
  - security/keys/sysctl.c:init_security_keys_sysctls
  - io_uring/io_uring.c:io_uring_init
  - drivers/xen/balloon.c:balloon_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/char/random.c:random_sysctls_init
```
**Symbols:**

```
ffffffff83923b10-ffffffff83923b71: __register_sysctl_init (STB_GLOBAL)
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
<b>Regular</b>
<ul>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>size_t table_size</code>
</li>
</ul>
</details>
</li>
</ul>
