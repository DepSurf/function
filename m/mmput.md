# Function: <code>mmput</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void mmput(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8107ddb0)
Location: kernel/fork.c:700
Inline: True
Direct callers:
  - kernel/fork.c:mm_access
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/exit.c:do_exit
  - kernel/sys.c:k_getrusage
  - kernel/cpuset.c:cpuset_migrate_mm_workfn
  - kernel/cpuset.c:cpuset_migrate_mm
  - kernel/cpuset.c:update_tasks_nodemask
  - kernel/cpuset.c:cpuset_attach
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/events/uprobes.c:register_for_each_vma
  - kernel/events/uprobes.c:register_for_each_vma
  - mm/util.c:get_cmdline
  - mm/memory.c:access_process_vm
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/mempolicy.c:SyS_migrate_pages
  - mm/migrate.c:SyS_move_pages
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/memcontrol.c:mem_cgroup_can_attach
  - fs/userfaultfd.c:SyS_userfaultfd
  - fs/proc/task_mmu.c:vma_stop
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/base.c:environ_read
  - fs/proc/base.c:proc_pid_auxv
  - fs/proc/base.c:proc_exe_link
  - fs/proc/base.c:proc_coredump_filter_read
  - fs/proc/base.c:proc_map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:proc_coredump_filter_write
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/base.c:proc_mem_open
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_statm
  - drivers/iommu/intel-svm.c:prq_event_thread
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
```
**Symbols:**

```
ffffffff8107ddb0-ffffffff8107ded6: mmput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void mmput(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8107f9a0)
Location: kernel/fork.c:733
Inline: False
Direct callers:
  - kernel/fork.c:mm_access
  - kernel/exit.c:do_exit
  - kernel/sys.c:k_getrusage
  - kernel/cpuset.c:cpuset_attach
  - kernel/cpuset.c:update_tasks_nodemask
  - kernel/cpuset.c:cpuset_migrate_mm
  - kernel/cpuset.c:cpuset_migrate_mm_workfn
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/events/core.c:perf_event_addr_filters_apply
  - kernel/events/uprobes.c:register_for_each_vma
  - kernel/events/uprobes.c:register_for_each_vma
  - mm/util.c:get_cmdline
  - mm/memory.c:access_process_vm
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/mempolicy.c:SyS_migrate_pages
  - mm/migrate.c:SyS_move_pages
  - mm/memcontrol.c:mem_cgroup_clear_mc
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_release
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:vma_stop
  - fs/proc/base.c:proc_coredump_filter_write
  - fs/proc/base.c:proc_coredump_filter_read
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:environ_read
  - fs/proc/base.c:proc_mem_open
  - fs/proc/base.c:proc_pid_auxv
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - drivers/iommu/intel-svm.c:prq_event_thread
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
```
**Symbols:**

```
ffffffff8107f9a0-ffffffff8107fabd: mmput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void mmput(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810840c0)
Location: kernel/fork.c:887
Inline: False
Direct callers:
  - kernel/fork.c:mm_access
  - kernel/exit.c:do_exit
  - kernel/ptrace.c:ptrace_access_vm
  - kernel/ptrace.c:ptrace_access_vm
  - kernel/sys.c:k_getrusage
  - kernel/cpuset.c:cpuset_attach
  - kernel/cpuset.c:update_tasks_nodemask
  - kernel/cpuset.c:cpuset_migrate_mm
  - kernel/cpuset.c:cpuset_migrate_mm_workfn
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/events/core.c:perf_event_addr_filters_apply
  - kernel/events/uprobes.c:register_for_each_vma
  - kernel/events/uprobes.c:register_for_each_vma
  - mm/util.c:get_cmdline
  - mm/memory.c:access_process_vm
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/mempolicy.c:SYSC_migrate_pages
  - mm/migrate.c:SYSC_move_pages
  - mm/memcontrol.c:mem_cgroup_clear_mc
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_release
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:vma_stop
  - fs/proc/base.c:proc_coredump_filter_write
  - fs/proc/base.c:proc_coredump_filter_read
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:environ_read
  - fs/proc/base.c:proc_mem_open
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - drivers/iommu/intel-svm.c:prq_event_thread
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
```
**Symbols:**

```
ffffffff810840c0-ffffffff810841ed: mmput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void mmput(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81081010)
Location: kernel/fork.c:934
Inline: False
Direct callers:
  - kernel/fork.c:mm_access
  - kernel/exit.c:do_exit
  - kernel/ptrace.c:ptrace_access_vm
  - kernel/ptrace.c:ptrace_access_vm
  - kernel/sys.c:getrusage
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/cgroup/cpuset.c:cpuset_migrate_mm
  - kernel/cgroup/cpuset.c:cpuset_migrate_mm_workfn
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/events/core.c:perf_event_addr_filters_apply
  - kernel/events/uprobes.c:register_for_each_vma
  - kernel/events/uprobes.c:register_for_each_vma
  - mm/util.c:get_cmdline
  - mm/memory.c:access_process_vm
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/mempolicy.c:SYSC_migrate_pages
  - mm/migrate.c:SYSC_move_pages
  - mm/memcontrol.c:mem_cgroup_clear_mc
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_release
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:vma_stop
  - fs/proc/base.c:proc_coredump_filter_write
  - fs/proc/base.c:proc_coredump_filter_read
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:environ_read
  - fs/proc/base.c:proc_mem_open
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - drivers/iommu/intel-svm.c:prq_event_thread
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
```
**Symbols:**

```
ffffffff81081010-ffffffff8108114f: mmput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void mmput(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81087900)
Location: kernel/fork.c:944
Inline: False
Direct callers:
  - kernel/fork.c:mm_access
  - kernel/exit.c:do_exit
  - kernel/ptrace.c:ptrace_access_vm
  - kernel/ptrace.c:ptrace_access_vm
  - kernel/sys.c:getrusage
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/cgroup/cpuset.c:cpuset_migrate_mm
  - kernel/cgroup/cpuset.c:cpuset_migrate_mm_workfn
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/events/core.c:perf_event_addr_filters_apply
  - kernel/events/uprobes.c:register_for_each_vma
  - kernel/events/uprobes.c:register_for_each_vma
  - mm/util.c:get_cmdline
  - mm/memory.c:access_process_vm
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/mempolicy.c:SYSC_migrate_pages
  - mm/migrate.c:SYSC_move_pages
  - mm/memcontrol.c:mem_cgroup_clear_mc
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_release
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:vma_stop
  - fs/proc/base.c:proc_coredump_filter_write
  - fs/proc/base.c:proc_coredump_filter_read
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:environ_read
  - fs/proc/base.c:proc_mem_open
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - drivers/iommu/intel-svm.c:prq_event_thread
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
```
**Symbols:**

```
ffffffff81087900-ffffffff81087a37: mmput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void mmput(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8108b290)
Location: kernel/fork.c:1013
Inline: False
Direct callers:
  - kernel/fork.c:copy_mm
  - kernel/fork.c:mm_access
  - kernel/exit.c:do_exit
  - kernel/ptrace.c:ptrace_access_vm
  - kernel/ptrace.c:ptrace_access_vm
  - kernel/sys.c:getrusage
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/cgroup/cpuset.c:cpuset_migrate_mm
  - kernel/cgroup/cpuset.c:cpuset_migrate_mm_workfn
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/events/core.c:perf_event_addr_filters_apply
  - kernel/events/uprobes.c:register_for_each_vma
  - kernel/events/uprobes.c:register_for_each_vma
  - mm/util.c:get_cmdline
  - mm/memory.c:access_process_vm
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/migrate.c:kernel_move_pages
  - mm/memcontrol.c:mem_cgroup_clear_mc
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_release
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:vma_stop
  - fs/proc/base.c:proc_coredump_filter_write
  - fs/proc/base.c:proc_coredump_filter_read
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:environ_read
  - fs/proc/base.c:proc_mem_open
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - drivers/iommu/intel-svm.c:prq_event_thread
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
```
**Symbols:**

```
ffffffff8108b290-ffffffff8108b3b1: mmput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void mmput(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81093190)
Location: kernel/fork.c:1068
Inline: False
Direct callers:
  - kernel/fork.c:mm_access
  - kernel/exit.c:do_exit
  - kernel/ptrace.c:ptrace_access_vm
  - kernel/ptrace.c:ptrace_access_vm
  - kernel/sys.c:getrusage
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/cgroup/cpuset.c:cpuset_migrate_mm
  - kernel/cgroup/cpuset.c:cpuset_migrate_mm_workfn
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/events/core.c:perf_event_addr_filters_apply
  - kernel/events/uprobes.c:register_for_each_vma
  - kernel/events/uprobes.c:register_for_each_vma
  - mm/util.c:get_cmdline
  - mm/memory.c:access_process_vm
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/migrate.c:kernel_move_pages
  - mm/memcontrol.c:mem_cgroup_clear_mc
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_release
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:vma_stop
  - fs/proc/base.c:proc_coredump_filter_write
  - fs/proc/base.c:proc_coredump_filter_read
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:environ_read
  - fs/proc/base.c:proc_mem_open
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - drivers/iommu/intel-svm.c:prq_event_thread
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
```
**Symbols:**

```
ffffffff81093190-ffffffff810932b1: mmput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void mmput(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81097290)
Location: kernel/fork.c:1085
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mm
  - kernel/fork.c:mm_access
  - kernel/exit.c:do_exit
  - kernel/ptrace.c:ptrace_access_vm
  - kernel/ptrace.c:ptrace_access_vm
  - kernel/sys.c:getrusage
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/cgroup/cpuset.c:cpuset_migrate_mm
  - kernel/cgroup/cpuset.c:cpuset_migrate_mm_workfn
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/events/core.c:perf_event_addr_filters_apply
  - kernel/events/uprobes.c:register_for_each_vma
  - kernel/events/uprobes.c:register_for_each_vma
  - mm/util.c:get_cmdline
  - mm/memory.c:access_process_vm
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/migrate.c:kernel_move_pages
  - mm/memcontrol.c:mem_cgroup_clear_mc
  - mm/hmm.c:hmm_range_unregister
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
  - fs/proc/task_mmu.c:vma_stop
  - fs/proc/base.c:proc_coredump_filter_write
  - fs/proc/base.c:proc_coredump_filter_read
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:environ_read
  - fs/proc/base.c:proc_mem_open
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - drivers/iommu/intel-svm.c:prq_event_thread
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
```
**Symbols:**

```
ffffffff81097290-ffffffff810973c0: mmput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void mmput(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8109d930)
Location: kernel/fork.c:1100
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mm
  - kernel/fork.c:mm_access
  - kernel/exit.c:do_exit
  - kernel/ptrace.c:ptrace_access_vm
  - kernel/ptrace.c:ptrace_access_vm
  - kernel/sys.c:getrusage
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/cgroup/cpuset.c:cpuset_migrate_mm
  - kernel/cgroup/cpuset.c:cpuset_migrate_mm_workfn
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/events/core.c:perf_event_addr_filters_apply
  - kernel/events/uprobes.c:register_for_each_vma
  - kernel/events/uprobes.c:register_for_each_vma
  - mm/util.c:get_cmdline
  - mm/memory.c:access_process_vm
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/migrate.c:kernel_move_pages
  - mm/memcontrol.c:mem_cgroup_clear_mc
  - mm/hmm.c:hmm_range_unregister
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
  - fs/proc/task_mmu.c:vma_stop
  - fs/proc/base.c:proc_coredump_filter_write
  - fs/proc/base.c:proc_coredump_filter_read
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:environ_read
  - fs/proc/base.c:proc_mem_open
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - drivers/iommu/intel-svm.c:prq_event_thread
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
```
**Symbols:**

```
ffffffff8109d930-ffffffff8109da60: mmput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void mmput(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a4e20)
Location: kernel/fork.c:1114
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mm
  - kernel/fork.c:mm_access
  - kernel/exit.c:exit_mm
  - kernel/sys.c:getrusage
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/cgroup/cpuset.c:cpuset_migrate_mm
  - kernel/cgroup/cpuset.c:cpuset_migrate_mm_workfn
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/events/core.c:perf_event_addr_filters_apply
  - kernel/events/uprobes.c:register_for_each_vma
  - kernel/events/uprobes.c:build_map_info
  - mm/util.c:get_cmdline
  - mm/memory.c:access_process_vm
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/migrate.c:kernel_move_pages
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/memcontrol.c:mem_cgroup_cancel_attach
  - fs/exec.c:__do_execve_file
  - fs/exec.c:exec_mmap
  - fs/userfaultfd.c:userfaultfd_zeropage
  - fs/userfaultfd.c:userfaultfd_copy
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/io-wq.c:io_worker_handle_work
  - fs/io-wq.c:__io_worker_unuse
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_stop
  - fs/proc/task_mmu.c:m_start
  - fs/proc/base.c:proc_coredump_filter_write
  - fs/proc/base.c:proc_coredump_filter_read
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:environ_read
  - fs/proc/base.c:proc_mem_open
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - drivers/iommu/intel/svm.c:prq_event_thread
  - drivers/iommu/intel/svm.c:intel_svm_bind_gpasid
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dma_rw_chunk
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_page_external
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_zap_and_vma_lock
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_zap_and_vma_lock
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_zap_and_vma_lock
```
**Symbols:**

```
ffffffff810a4e20-ffffffff810a4f52: mmput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void mmput(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a0530)
Location: kernel/fork.c:1111
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mm
  - kernel/fork.c:mm_access
  - kernel/exit.c:exit_mm
  - kernel/sys.c:getrusage
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/cgroup/cpuset.c:cpuset_migrate_mm
  - kernel/cgroup/cpuset.c:cpuset_migrate_mm_workfn
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/events/core.c:perf_event_addr_filters_apply
  - kernel/events/uprobes.c:register_for_each_vma
  - kernel/events/uprobes.c:build_map_info
  - mm/util.c:get_cmdline
  - mm/memory.c:access_process_vm
  - mm/madvise.c:__do_sys_process_madvise
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/migrate.c:kernel_move_pages
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/memcontrol.c:mem_cgroup_cancel_attach
  - fs/exec.c:free_bprm
  - fs/exec.c:exec_mmap
  - fs/userfaultfd.c:userfaultfd_zeropage
  - fs/userfaultfd.c:userfaultfd_copy
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
  - fs/io_uring.c:io_sq_thread_drop_mm_files
  - fs/io-wq.c:io_impersonate_work
  - fs/io-wq.c:__io_worker_unuse
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_stop
  - fs/proc/task_mmu.c:m_start
  - fs/proc/base.c:proc_coredump_filter_write
  - fs/proc/base.c:proc_coredump_filter_read
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:environ_read
  - fs/proc/base.c:proc_mem_open
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - drivers/iommu/intel/svm.c:intel_svm_page_response
  - drivers/iommu/intel/svm.c:intel_svm_page_response
  - drivers/iommu/intel/svm.c:prq_event_thread
  - drivers/iommu/intel/svm.c:intel_svm_bind_gpasid
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dma_rw_chunk
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_page_external
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_zap_and_vma_lock
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_zap_and_vma_lock
```
**Symbols:**

```
ffffffff810a0530-ffffffff810a0662: mmput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void mmput(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a12f0)
Location: kernel/fork.c:1117
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mm
  - kernel/fork.c:mm_access
  - kernel/exit.c:exit_mm
  - kernel/sys.c:getrusage
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/cgroup/cpuset.c:cpuset_migrate_mm
  - kernel/cgroup/cpuset.c:cpuset_migrate_mm_workfn
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/events/core.c:perf_event_addr_filters_apply
  - kernel/events/uprobes.c:register_for_each_vma
  - kernel/events/uprobes.c:build_map_info
  - mm/util.c:get_cmdline
  - mm/memory.c:access_process_vm
  - mm/madvise.c:__do_sys_process_madvise
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/migrate.c:kernel_move_pages
  - mm/huge_memory.c:split_huge_pages_pid
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/memcontrol.c:mem_cgroup_cancel_attach
  - fs/exec.c:free_bprm
  - fs/exec.c:exec_mmap
  - fs/userfaultfd.c:userfaultfd_continue
  - fs/userfaultfd.c:userfaultfd_zeropage
  - fs/userfaultfd.c:userfaultfd_copy
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_stop
  - fs/proc/task_mmu.c:m_start
  - fs/proc/base.c:proc_coredump_filter_write
  - fs/proc/base.c:proc_coredump_filter_read
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:environ_read
  - fs/proc/base.c:proc_mem_open
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - drivers/iommu/intel/svm.c:intel_svm_page_response
  - drivers/iommu/intel/svm.c:intel_svm_page_response
  - drivers/iommu/intel/svm.c:prq_event_thread
  - drivers/iommu/intel/svm.c:intel_svm_bind_gpasid
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dma_rw_chunk
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_zap_and_vma_lock
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_zap_and_vma_lock
```
**Symbols:**

```
ffffffff810a12f0-ffffffff810a1422: mmput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void mmput(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810b2710)
Location: kernel/fork.c:1136
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mm
  - kernel/fork.c:mm_access
  - kernel/exit.c:exit_mm
  - kernel/sys.c:getrusage
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/cgroup/cpuset.c:cpuset_migrate_mm_workfn
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/events/core.c:perf_event_addr_filters_apply
  - kernel/events/uprobes.c:register_for_each_vma
  - kernel/events/uprobes.c:build_map_info
  - mm/oom_kill.c:__do_sys_process_mrelease
  - mm/util.c:get_cmdline
  - mm/memory.c:access_process_vm
  - mm/madvise.c:__do_sys_process_madvise
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/migrate.c:kernel_move_pages
  - mm/huge_memory.c:split_huge_pages_pid
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/memcontrol.c:mem_cgroup_cancel_attach
  - fs/exec.c:free_bprm
  - fs/exec.c:exec_mmap
  - fs/userfaultfd.c:userfaultfd_continue
  - fs/userfaultfd.c:userfaultfd_writeprotect
  - fs/userfaultfd.c:userfaultfd_zeropage
  - fs/userfaultfd.c:userfaultfd_copy
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_stop
  - fs/proc/task_mmu.c:m_start
  - fs/proc/base.c:proc_coredump_filter_write
  - fs/proc/base.c:proc_coredump_filter_read
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:environ_read
  - fs/proc/base.c:proc_mem_open
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - drivers/iommu/intel/svm.c:intel_svm_page_response
  - drivers/iommu/intel/svm.c:intel_svm_page_response
  - drivers/iommu/intel/svm.c:intel_svm_bind_gpasid
  - drivers/iommu/io-pgfault.c:iopf_handle_single
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dma_rw_chunk
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_zap_and_vma_lock
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_zap_and_vma_lock
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_zap_and_vma_lock
```
**Symbols:**

```
ffffffff810b2710-ffffffff810b284d: mmput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void mmput(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810c85a0)
Location: kernel/fork.c:1208
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mm
  - kernel/fork.c:mm_access
  - kernel/exit.c:exit_mm
  - kernel/sys.c:getrusage
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/cgroup/cpuset.c:cpuset_migrate_mm_workfn
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/events/core.c:perf_event_addr_filters_apply
  - kernel/events/uprobes.c:register_for_each_vma
  - kernel/events/uprobes.c:build_map_info
  - mm/util.c:get_cmdline
  - mm/memory.c:access_process_vm
  - mm/madvise.c:__do_sys_process_madvise
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/migrate.c:kernel_move_pages
  - mm/huge_memory.c:split_huge_pages_pid
  - mm/memcontrol.c:mem_cgroup_cancel_attach
  - mm/memcontrol.c:mem_cgroup_can_attach
  - mm/memcontrol.c:mem_cgroup_can_attach
  - fs/exec.c:free_bprm
  - fs/exec.c:exec_mmap
  - fs/userfaultfd.c:userfaultfd_continue
  - fs/userfaultfd.c:userfaultfd_writeprotect
  - fs/userfaultfd.c:userfaultfd_zeropage
  - fs/userfaultfd.c:userfaultfd_copy
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_stop
  - fs/proc/task_mmu.c:m_start
  - fs/proc/base.c:proc_pid_ksm_merging_pages
  - fs/proc/base.c:proc_coredump_filter_write
  - fs/proc/base.c:proc_coredump_filter_read
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:environ_read
  - fs/proc/base.c:proc_mem_open
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - drivers/iommu/io-pgfault.c:iopf_handle_single
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dma_rw_chunk
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_zap_and_vma_lock
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_zap_and_vma_lock
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_zap_and_vma_lock
```
**Symbols:**

```
ffffffff810c85a0-ffffffff810c86d5: mmput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void mmput(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810e740e)
Location: kernel/fork.c:1229
Inline: True
Inline callers:
  - kernel/fork.c:mm_access
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/exit.c:exit_mm
  - kernel/sys.c:getrusage
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/cgroup/cpuset.c:cpuset_migrate_mm_workfn
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
  - kernel/events/core.c:perf_event_addr_filters_apply
  - kernel/events/uprobes.c:register_for_each_vma
  - kernel/events/uprobes.c:build_map_info
  - mm/util.c:get_cmdline
  - mm/memory.c:access_process_vm
  - mm/madvise.c:__do_sys_process_madvise
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/migrate.c:kernel_move_pages
  - mm/huge_memory.c:split_huge_pages_pid
  - mm/memcontrol.c:mem_cgroup_cancel_attach
  - mm/memcontrol.c:mem_cgroup_can_attach
  - mm/memcontrol.c:mem_cgroup_can_attach
  - fs/exec.c:free_bprm
  - fs/exec.c:exec_mmap
  - fs/userfaultfd.c:userfaultfd_continue
  - fs/userfaultfd.c:userfaultfd_writeprotect
  - fs/userfaultfd.c:userfaultfd_zeropage
  - fs/userfaultfd.c:userfaultfd_copy
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_stop
  - fs/proc/task_mmu.c:m_start
  - fs/proc/base.c:proc_pid_ksm_stat
  - fs/proc/base.c:proc_pid_ksm_merging_pages
  - fs/proc/base.c:proc_coredump_filter_write
  - fs/proc/base.c:proc_coredump_filter_read
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:environ_read
  - fs/proc/base.c:proc_mem_open
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - drivers/iommu/iommu-sva.c:iommu_sva_handle_iopf
  - drivers/iommu/iommu-sva.c:iommu_sva_handle_iopf
```
**Symbols:**

```
ffffffff810e5a10-ffffffff810e5a4c: mmput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void mmput(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810f2f24)
Location: kernel/fork.c:1370
Inline: True
Inline callers:
  - kernel/fork.c:mm_access
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/exit.c:exit_mm
  - kernel/sys.c:getrusage
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/cgroup/cpuset.c:cpuset_migrate_mm_workfn
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
  - kernel/events/core.c:perf_event_addr_filters_apply
  - kernel/events/uprobes.c:register_for_each_vma
  - kernel/events/uprobes.c:build_map_info
  - mm/util.c:get_cmdline
  - mm/memory.c:access_process_vm
  - mm/madvise.c:__do_sys_process_madvise
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/migrate.c:kernel_move_pages
  - mm/huge_memory.c:split_huge_pages_pid
  - mm/memcontrol.c:mem_cgroup_cancel_attach
  - mm/memcontrol.c:mem_cgroup_can_attach
  - mm/memcontrol.c:mem_cgroup_can_attach
  - fs/exec.c:free_bprm
  - fs/exec.c:exec_mmap
  - fs/userfaultfd.c:userfaultfd_continue
  - fs/userfaultfd.c:userfaultfd_writeprotect
  - fs/userfaultfd.c:userfaultfd_zeropage
  - fs/userfaultfd.c:userfaultfd_copy
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_stop
  - fs/proc/task_mmu.c:m_start
  - fs/proc/base.c:proc_pid_ksm_stat
  - fs/proc/base.c:proc_pid_ksm_merging_pages
  - fs/proc/base.c:proc_coredump_filter_write
  - fs/proc/base.c:proc_coredump_filter_read
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:environ_read
  - fs/proc/base.c:proc_mem_open
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - drivers/iommu/iommu-sva.c:iommu_sva_handle_iopf
  - drivers/iommu/iommu-sva.c:iommu_sva_handle_iopf
```
**Symbols:**

```
ffffffff810f1080-ffffffff810f10bf: mmput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void mmput(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810fc2d4)
Location: kernel/fork.c:1365
Inline: True
Inline callers:
  - kernel/fork.c:mm_access
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/exit.c:exit_mm
  - kernel/sys.c:getrusage
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/cgroup/cpuset.c:cpuset_migrate_mm_workfn
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
  - kernel/events/core.c:perf_event_addr_filters_apply
  - kernel/events/uprobes.c:register_for_each_vma
  - kernel/events/uprobes.c:build_map_info
  - mm/util.c:get_cmdline
  - mm/memory.c:access_process_vm
  - mm/madvise.c:__do_sys_process_madvise
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/migrate.c:kernel_move_pages
  - mm/huge_memory.c:split_huge_pages_pid
  - mm/memcontrol.c:mem_cgroup_cancel_attach
  - mm/memcontrol.c:mem_cgroup_can_attach
  - mm/memcontrol.c:mem_cgroup_can_attach
  - fs/exec.c:free_bprm
  - fs/exec.c:exec_mmap
  - fs/userfaultfd.c:userfaultfd_move
  - fs/userfaultfd.c:userfaultfd_poison
  - fs/userfaultfd.c:userfaultfd_continue
  - fs/userfaultfd.c:userfaultfd_writeprotect
  - fs/userfaultfd.c:userfaultfd_zeropage
  - fs/userfaultfd.c:userfaultfd_copy
  - fs/userfaultfd.c:userfaultfd_unregister
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_stop
  - fs/proc/task_mmu.c:m_start
  - fs/proc/base.c:proc_pid_ksm_stat
  - fs/proc/base.c:proc_pid_ksm_merging_pages
  - fs/proc/base.c:proc_coredump_filter_write
  - fs/proc/base.c:proc_coredump_filter_read
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:environ_read
  - fs/proc/base.c:proc_mem_open
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - drivers/iommu/iommu-sva.c:iommu_sva_handle_iopf
  - drivers/iommu/iommu-sva.c:iommu_sva_handle_iopf
```
**Symbols:**

```
ffffffff810fa450-ffffffff810fa48f: mmput (STB_GLOBAL)
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
void mmput(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffff8000100f2220)
Location: kernel/fork.c:1100
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mm
  - kernel/fork.c:mm_access
  - kernel/exit.c:do_exit
  - kernel/ptrace.c:ptrace_access_vm
  - kernel/ptrace.c:ptrace_access_vm
  - kernel/sys.c:getrusage
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/cgroup/cpuset.c:cpuset_migrate_mm_workfn
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/events/core.c:perf_event_addr_filters_apply
  - kernel/events/uprobes.c:register_for_each_vma
  - kernel/events/uprobes.c:register_for_each_vma
  - mm/util.c:get_cmdline
  - mm/memory.c:access_process_vm
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/migrate.c:kernel_move_pages
  - mm/memcontrol.c:mem_cgroup_clear_mc
  - mm/hmm.c:hmm_range_unregister
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
  - fs/proc/task_mmu.c:vma_stop
  - fs/proc/base.c:proc_coredump_filter_write
  - fs/proc/base.c:proc_coredump_filter_read
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:environ_read
  - fs/proc/base.c:proc_mem_open
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
```
**Symbols:**

```
ffff8000100f2220-ffff8000100f23bc: mmput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void mmput(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (c0350438)
Location: kernel/fork.c:1100
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mm
  - kernel/fork.c:mm_access
  - kernel/exit.c:do_exit
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_access_vm
  - kernel/ptrace.c:ptrace_access_vm
  - kernel/sys.c:getrusage
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/cgroup/cpuset.c:cpuset_migrate_mm
  - kernel/cgroup/cpuset.c:cpuset_migrate_mm_workfn
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/events/core.c:perf_event_addr_filters_apply
  - kernel/events/uprobes.c:register_for_each_vma
  - kernel/events/uprobes.c:register_for_each_vma
  - mm/util.c:get_cmdline
  - mm/memory.c:access_process_vm
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/memcontrol.c:mem_cgroup_clear_mc
  - mm/hmm.c:hmm_range_unregister
  - fs/exec.c:__do_execve_file
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_unregister
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_stop
  - fs/proc/task_mmu.c:m_next
  - fs/proc/task_mmu.c:m_start
  - fs/proc/task_mmu.c:m_start
  - fs/proc/base.c:proc_coredump_filter_write
  - fs/proc/base.c:proc_coredump_filter_read
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:environ_read
  - fs/proc/base.c:mem_rw
  - fs/proc/base.c:proc_mem_open
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
```
**Symbols:**

```
c0350438-c0350568: mmput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void mmput(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (c0000000001378f0)
Location: kernel/fork.c:1100
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mm
  - kernel/fork.c:mm_access
  - kernel/exit.c:do_exit
  - kernel/ptrace.c:ptrace_access_vm
  - kernel/ptrace.c:ptrace_access_vm
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/cgroup/cpuset.c:cpuset_migrate_mm
  - kernel/cgroup/cpuset.c:cpuset_migrate_mm_workfn
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/events/core.c:perf_event_addr_filters_apply
  - kernel/events/uprobes.c:register_for_each_vma
  - kernel/events/uprobes.c:register_for_each_vma
  - mm/util.c:get_cmdline
  - mm/memory.c:access_process_vm
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/migrate.c:kernel_move_pages
  - mm/memcontrol.c:mem_cgroup_clear_mc
  - mm/hmm.c:hmm_range_unregister
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_unregister
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
  - fs/proc/task_mmu.c:vma_stop
  - fs/proc/base.c:proc_coredump_filter_write
  - fs/proc/base.c:proc_coredump_filter_read
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:environ_read
  - fs/proc/base.c:mem_rw
  - fs/proc/base.c:proc_mem_open
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
```
**Symbols:**

```
c0000000001378f0-c000000000137ae0: mmput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void mmput(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffe0000c0b46)
Location: kernel/fork.c:1100
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mm
  - kernel/fork.c:mm_access
Direct callers:
  - kernel/exit.c:do_exit
  - kernel/ptrace.c:ptrace_access_vm
  - kernel/ptrace.c:ptrace_access_vm
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/cgroup/cpuset.c:cpuset_migrate_mm_workfn
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/events/core.c:perf_event_addr_filters_apply
  - mm/util.c:get_cmdline
  - mm/memory.c:access_process_vm
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/memcontrol.c:mem_cgroup_clear_mc
  - mm/hmm.c:hmm_range_unregister
  - fs/exec.c:__do_execve_file
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_unregister
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_stop
  - fs/proc/task_mmu.c:m_next
  - fs/proc/task_mmu.c:m_start
  - fs/proc/task_mmu.c:m_start
  - fs/proc/base.c:proc_coredump_filter_write
  - fs/proc/base.c:proc_coredump_filter_read
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:environ_read
  - fs/proc/base.c:mem_rw
  - fs/proc/base.c:mem_rw
  - fs/proc/base.c:proc_mem_open
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
```
**Symbols:**

```
ffffffe0000bf168-ffffffe0000bf284: mmput (STB_GLOBAL)
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
void mmput(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81097250)
Location: kernel/fork.c:1100
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mm
  - kernel/fork.c:mm_access
  - kernel/exit.c:do_exit
  - kernel/ptrace.c:ptrace_access_vm
  - kernel/ptrace.c:ptrace_access_vm
  - kernel/sys.c:getrusage
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/cgroup/cpuset.c:cpuset_migrate_mm
  - kernel/cgroup/cpuset.c:cpuset_migrate_mm_workfn
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/events/core.c:perf_event_addr_filters_apply
  - kernel/events/uprobes.c:register_for_each_vma
  - kernel/events/uprobes.c:register_for_each_vma
  - mm/util.c:get_cmdline
  - mm/memory.c:access_process_vm
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/migrate.c:kernel_move_pages
  - mm/memcontrol.c:mem_cgroup_clear_mc
  - mm/hmm.c:hmm_range_unregister
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
  - fs/proc/task_mmu.c:vma_stop
  - fs/proc/base.c:proc_coredump_filter_write
  - fs/proc/base.c:proc_coredump_filter_read
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:environ_read
  - fs/proc/base.c:proc_mem_open
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - drivers/iommu/intel-svm.c:prq_event_thread
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
```
**Symbols:**

```
ffffffff81097250-ffffffff81097380: mmput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void mmput(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81085cd0)
Location: kernel/fork.c:1100
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mm
  - kernel/fork.c:mm_access
  - kernel/exit.c:do_exit
  - kernel/ptrace.c:ptrace_access_vm
  - kernel/ptrace.c:ptrace_access_vm
  - kernel/sys.c:getrusage
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/cgroup/cpuset.c:cpuset_migrate_mm
  - kernel/cgroup/cpuset.c:cpuset_migrate_mm_workfn
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/events/core.c:perf_event_addr_filters_apply
  - kernel/events/uprobes.c:register_for_each_vma
  - kernel/events/uprobes.c:register_for_each_vma
  - mm/util.c:get_cmdline
  - mm/memory.c:access_process_vm
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/migrate.c:kernel_move_pages
  - mm/memcontrol.c:mem_cgroup_clear_mc
  - mm/hmm.c:hmm_range_unregister
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
  - fs/proc/task_mmu.c:vma_stop
  - fs/proc/base.c:proc_coredump_filter_write
  - fs/proc/base.c:proc_coredump_filter_read
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:environ_read
  - fs/proc/base.c:proc_mem_open
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - drivers/iommu/intel-svm.c:prq_event_thread
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
```
**Symbols:**

```
ffffffff81085cd0-ffffffff81085e00: mmput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void mmput(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81097200)
Location: kernel/fork.c:1100
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mm
  - kernel/fork.c:mm_access
  - kernel/exit.c:do_exit
  - kernel/ptrace.c:ptrace_access_vm
  - kernel/ptrace.c:ptrace_access_vm
  - kernel/sys.c:getrusage
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/cgroup/cpuset.c:cpuset_migrate_mm
  - kernel/cgroup/cpuset.c:cpuset_migrate_mm_workfn
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/events/core.c:perf_event_addr_filters_apply
  - kernel/events/uprobes.c:register_for_each_vma
  - kernel/events/uprobes.c:register_for_each_vma
  - mm/util.c:get_cmdline
  - mm/memory.c:access_process_vm
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/migrate.c:kernel_move_pages
  - mm/memcontrol.c:mem_cgroup_clear_mc
  - mm/hmm.c:hmm_range_unregister
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
  - fs/proc/task_mmu.c:vma_stop
  - fs/proc/base.c:proc_coredump_filter_write
  - fs/proc/base.c:proc_coredump_filter_read
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:environ_read
  - fs/proc/base.c:proc_mem_open
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - drivers/iommu/intel-svm.c:prq_event_thread
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
```
**Symbols:**

```
ffffffff81097200-ffffffff81097330: mmput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void mmput(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8109e370)
Location: kernel/fork.c:1100
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mm
  - kernel/fork.c:mm_access
  - kernel/exit.c:do_exit
  - kernel/ptrace.c:ptrace_access_vm
  - kernel/ptrace.c:ptrace_access_vm
  - kernel/sys.c:getrusage
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/cgroup/cpuset.c:cpuset_migrate_mm
  - kernel/cgroup/cpuset.c:cpuset_migrate_mm_workfn
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/events/core.c:perf_event_addr_filters_apply
  - kernel/events/uprobes.c:register_for_each_vma
  - kernel/events/uprobes.c:register_for_each_vma
  - mm/util.c:get_cmdline
  - mm/memory.c:access_process_vm
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/migrate.c:kernel_move_pages
  - mm/memcontrol.c:mem_cgroup_clear_mc
  - mm/hmm.c:hmm_range_unregister
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
  - fs/proc/task_mmu.c:vma_stop
  - fs/proc/base.c:proc_coredump_filter_write
  - fs/proc/base.c:proc_coredump_filter_read
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:environ_read
  - fs/proc/base.c:proc_mem_open
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - drivers/iommu/intel-svm.c:prq_event_thread
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
```
**Symbols:**

```
ffffffff8109e370-ffffffff8109e48e: mmput (STB_GLOBAL)
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
