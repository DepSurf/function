# Function: <code>get_task_mm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct mm_struct *get_task_mm(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8107d5f0)
Location: kernel/fork.c:780
Inline: False
Direct callers:
  - kernel/fork.c:mm_access
  - kernel/sys.c:k_getrusage
  - kernel/cpuset.c:update_tasks_nodemask
  - kernel/cpuset.c:cpuset_attach
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/trace/trace_output.c:trace_user_stack_print
  - mm/util.c:get_cmdline
  - mm/memory.c:access_process_vm
  - mm/mempolicy.c:SyS_migrate_pages
  - mm/migrate.c:SyS_move_pages
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/memcontrol.c:mem_cgroup_can_attach
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/base.c:proc_exe_link
  - fs/proc/base.c:proc_coredump_filter_read
  - fs/proc/base.c:proc_map_files_get_link
  - fs/proc/base.c:proc_coredump_filter_write
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_statm
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
```
**Symbols:**

```
ffffffff8107d5f0-ffffffff8107d63d: get_task_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct mm_struct *get_task_mm(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8107f0e0)
Location: kernel/fork.c:838
Inline: False
Direct callers:
  - kernel/fork.c:mm_access
  - kernel/sys.c:k_getrusage
  - kernel/cpuset.c:cpuset_attach
  - kernel/cpuset.c:update_tasks_nodemask
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/events/core.c:perf_event_addr_filters_apply
  - mm/util.c:get_cmdline
  - mm/memory.c:access_process_vm
  - mm/mempolicy.c:SyS_migrate_pages
  - mm/migrate.c:SyS_move_pages
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/base.c:proc_coredump_filter_write
  - fs/proc/base.c:proc_coredump_filter_read
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
```
**Symbols:**

```
ffffffff8107f0e0-ffffffff8107f12d: get_task_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct mm_struct *get_task_mm(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81083790)
Location: kernel/fork.c:992
Inline: False
Direct callers:
  - kernel/fork.c:mm_access
  - kernel/ptrace.c:ptrace_access_vm
  - kernel/sys.c:k_getrusage
  - kernel/cpuset.c:cpuset_attach
  - kernel/cpuset.c:update_tasks_nodemask
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/events/core.c:perf_event_addr_filters_apply
  - mm/util.c:get_cmdline
  - mm/memory.c:access_process_vm
  - mm/mempolicy.c:SYSC_migrate_pages
  - mm/migrate.c:SYSC_move_pages
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/base.c:proc_coredump_filter_write
  - fs/proc/base.c:proc_coredump_filter_read
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
```
**Symbols:**

```
ffffffff81083790-ffffffff810837dd: get_task_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct mm_struct *get_task_mm(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81080660)
Location: kernel/fork.c:1039
Inline: False
Direct callers:
  - kernel/fork.c:mm_access
  - kernel/ptrace.c:ptrace_access_vm
  - kernel/sys.c:getrusage
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/events/core.c:perf_event_addr_filters_apply
  - mm/util.c:get_cmdline
  - mm/memory.c:access_process_vm
  - mm/mempolicy.c:SYSC_migrate_pages
  - mm/migrate.c:SYSC_move_pages
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/base.c:proc_coredump_filter_write
  - fs/proc/base.c:proc_coredump_filter_read
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
```
**Symbols:**

```
ffffffff81080660-ffffffff810806ad: get_task_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct mm_struct *get_task_mm(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81086f00)
Location: kernel/fork.c:1051
Inline: False
Direct callers:
  - kernel/fork.c:mm_access
  - kernel/ptrace.c:ptrace_access_vm
  - kernel/sys.c:getrusage
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/events/core.c:perf_event_addr_filters_apply
  - mm/util.c:get_cmdline
  - mm/memory.c:access_process_vm
  - mm/mempolicy.c:SYSC_migrate_pages
  - mm/migrate.c:SYSC_move_pages
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/base.c:proc_coredump_filter_write
  - fs/proc/base.c:proc_coredump_filter_read
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
```
**Symbols:**

```
ffffffff81086f00-ffffffff81086f4d: get_task_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct mm_struct *get_task_mm(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8108b090)
Location: kernel/fork.c:1120
Inline: False
Direct callers:
  - kernel/fork.c:mm_access
  - kernel/ptrace.c:ptrace_access_vm
  - kernel/sys.c:getrusage
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/events/core.c:perf_event_addr_filters_apply
  - mm/util.c:get_cmdline
  - mm/memory.c:access_process_vm
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/migrate.c:kernel_move_pages
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/base.c:proc_coredump_filter_write
  - fs/proc/base.c:proc_coredump_filter_read
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
```
**Symbols:**

```
ffffffff8108b090-ffffffff8108b0dd: get_task_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct mm_struct *get_task_mm(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81092eb0)
Location: kernel/fork.c:1176
Inline: False
Direct callers:
  - kernel/fork.c:mm_access
  - kernel/ptrace.c:ptrace_access_vm
  - kernel/sys.c:getrusage
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/events/core.c:perf_event_addr_filters_apply
  - mm/util.c:get_cmdline
  - mm/memory.c:access_process_vm
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/migrate.c:kernel_move_pages
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/base.c:proc_coredump_filter_write
  - fs/proc/base.c:proc_coredump_filter_read
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
```
**Symbols:**

```
ffffffff81092eb0-ffffffff81092efd: get_task_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct mm_struct *get_task_mm(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81096ff0)
Location: kernel/fork.c:1193
Inline: False
Direct callers:
  - kernel/fork.c:mm_access
  - kernel/ptrace.c:ptrace_access_vm
  - kernel/sys.c:getrusage
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/events/core.c:perf_event_addr_filters_apply
  - mm/util.c:get_cmdline
  - mm/memory.c:access_process_vm
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/migrate.c:kernel_move_pages
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/base.c:proc_coredump_filter_write
  - fs/proc/base.c:proc_coredump_filter_read
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
```
**Symbols:**

```
ffffffff81096ff0-ffffffff8109703c: get_task_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct mm_struct *get_task_mm(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8109d6f0)
Location: kernel/fork.c:1208
Inline: False
Direct callers:
  - kernel/fork.c:mm_access
  - kernel/ptrace.c:ptrace_access_vm
  - kernel/sys.c:getrusage
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/events/core.c:perf_event_addr_filters_apply
  - mm/util.c:get_cmdline
  - mm/memory.c:access_process_vm
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/migrate.c:kernel_move_pages
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/base.c:proc_coredump_filter_write
  - fs/proc/base.c:proc_coredump_filter_read
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
```
**Symbols:**

```
ffffffff8109d6f0-ffffffff8109d73c: get_task_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct mm_struct *get_task_mm(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a48b0)
Location: kernel/fork.c:1222
Inline: False
Direct callers:
  - kernel/fork.c:mm_access
  - kernel/sys.c:getrusage
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/events/core.c:perf_event_addr_filters_apply
  - mm/util.c:get_cmdline
  - mm/memory.c:access_process_vm
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/migrate.c:kernel_move_pages
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/base.c:proc_coredump_filter_write
  - fs/proc/base.c:proc_coredump_filter_read
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - drivers/iommu/intel/svm.c:intel_svm_bind_gpasid
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dma_rw_chunk
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_page_external
```
**Symbols:**

```
ffffffff810a48b0-ffffffff810a48fc: get_task_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct mm_struct *get_task_mm(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8109fcd0)
Location: kernel/fork.c:1219
Inline: False
Direct callers:
  - kernel/fork.c:mm_access
  - kernel/sys.c:getrusage
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/events/core.c:perf_event_addr_filters_apply
  - mm/util.c:get_cmdline
  - mm/memory.c:access_process_vm
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/migrate.c:find_mm_struct
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/base.c:proc_coredump_filter_write
  - fs/proc/base.c:proc_coredump_filter_read
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - drivers/iommu/intel/svm.c:intel_svm_page_response
  - drivers/iommu/intel/svm.c:intel_svm_bind_gpasid
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dma_rw_chunk
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_page_external
```
**Symbols:**

```
ffffffff8109fcd0-ffffffff8109fd1c: get_task_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct mm_struct *get_task_mm(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a0d80)
Location: kernel/fork.c:1225
Inline: False
Direct callers:
  - kernel/fork.c:mm_access
  - kernel/sys.c:getrusage
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/events/core.c:perf_event_addr_filters_apply
  - mm/util.c:get_cmdline
  - mm/memory.c:access_process_vm
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/migrate.c:find_mm_struct
  - mm/huge_memory.c:split_huge_pages_pid
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/base.c:proc_coredump_filter_write
  - fs/proc/base.c:proc_coredump_filter_read
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - drivers/iommu/intel/svm.c:intel_svm_page_response
  - drivers/iommu/intel/svm.c:intel_svm_bind_gpasid
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dma_rw_chunk
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
```
**Symbols:**

```
ffffffff810a0d80-ffffffff810a0dcc: get_task_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct mm_struct *get_task_mm(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810b2190)
Location: kernel/fork.c:1304
Inline: False
Direct callers:
  - kernel/fork.c:mm_access
  - kernel/sys.c:getrusage
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/events/core.c:perf_event_addr_filters_apply
  - mm/util.c:get_cmdline
  - mm/memory.c:access_process_vm
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/migrate.c:find_mm_struct
  - mm/huge_memory.c:split_huge_pages_pid
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/base.c:proc_coredump_filter_write
  - fs/proc/base.c:proc_coredump_filter_read
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - drivers/iommu/intel/svm.c:intel_svm_page_response
  - drivers/iommu/intel/svm.c:intel_svm_bind_gpasid
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dma_rw_chunk
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
```
**Symbols:**

```
ffffffff810b2190-ffffffff810b21dc: get_task_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct mm_struct *get_task_mm(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810c9d94)
Location: kernel/fork.c:1376
Inline: True
Inline callers:
  - kernel/fork.c:mm_access
Direct callers:
  - kernel/sys.c:getrusage
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/events/core.c:perf_event_addr_filters_apply
  - mm/util.c:get_cmdline
  - mm/memory.c:access_process_vm
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/migrate.c:find_mm_struct
  - mm/huge_memory.c:split_huge_pages_pid
  - mm/memcontrol.c:mem_cgroup_can_attach
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/base.c:proc_pid_ksm_merging_pages
  - fs/proc/base.c:proc_coredump_filter_write
  - fs/proc/base.c:proc_coredump_filter_read
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dma_rw_chunk
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
```
**Symbols:**

```
ffffffff810c6fe0-ffffffff810c7035: get_task_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct mm_struct *get_task_mm(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810e73b8)
Location: kernel/fork.c:1400
Inline: True
Inline callers:
  - kernel/fork.c:mm_access
Direct callers:
  - kernel/sys.c:getrusage
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
  - kernel/events/core.c:perf_event_addr_filters_apply
  - mm/util.c:get_cmdline
  - mm/memory.c:access_process_vm
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/migrate.c:find_mm_struct
  - mm/huge_memory.c:split_huge_pages_pid
  - mm/memcontrol.c:mem_cgroup_can_attach
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/base.c:proc_pid_ksm_stat
  - fs/proc/base.c:proc_pid_ksm_merging_pages
  - fs/proc/base.c:proc_coredump_filter_write
  - fs/proc/base.c:proc_coredump_filter_read
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
```
**Symbols:**

```
ffffffff810e4060-ffffffff810e40b5: get_task_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct mm_struct *get_task_mm(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810f2ec8)
Location: kernel/fork.c:1541
Inline: True
Inline callers:
  - kernel/fork.c:mm_access
Direct callers:
  - kernel/sys.c:getrusage
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
  - kernel/events/core.c:perf_event_addr_filters_apply
  - mm/util.c:get_cmdline
  - mm/memory.c:access_process_vm
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/migrate.c:find_mm_struct
  - mm/huge_memory.c:split_huge_pages_pid
  - mm/memcontrol.c:mem_cgroup_can_attach
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/base.c:proc_pid_ksm_stat
  - fs/proc/base.c:proc_pid_ksm_merging_pages
  - fs/proc/base.c:proc_coredump_filter_write
  - fs/proc/base.c:proc_coredump_filter_read
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
```
**Symbols:**

```
ffffffff810ef6f0-ffffffff810ef748: get_task_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct mm_struct *get_task_mm(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810fc278)
Location: kernel/fork.c:1537
Inline: True
Inline callers:
  - kernel/fork.c:mm_access
Direct callers:
  - kernel/sys.c:getrusage
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
  - kernel/events/core.c:perf_event_addr_filters_apply
  - mm/util.c:get_cmdline
  - mm/memory.c:access_process_vm
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/migrate.c:find_mm_struct
  - mm/huge_memory.c:split_huge_pages_pid
  - mm/memcontrol.c:mem_cgroup_can_attach
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/base.c:proc_pid_ksm_stat
  - fs/proc/base.c:proc_pid_ksm_merging_pages
  - fs/proc/base.c:proc_coredump_filter_write
  - fs/proc/base.c:proc_coredump_filter_read
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
```
**Symbols:**

```
ffffffff810f8b00-ffffffff810f8b58: get_task_mm (STB_GLOBAL)
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
struct mm_struct *get_task_mm(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffff8000100f1ab8)
Location: kernel/fork.c:1208
Inline: False
Direct callers:
  - kernel/fork.c:mm_access
  - kernel/ptrace.c:ptrace_access_vm
  - kernel/sys.c:getrusage
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/events/core.c:perf_event_addr_filters_apply
  - mm/util.c:get_cmdline
  - mm/memory.c:access_process_vm
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/migrate.c:kernel_move_pages
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/base.c:proc_coredump_filter_write
  - fs/proc/base.c:proc_coredump_filter_read
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
```
**Symbols:**

```
ffff8000100f1ab8-ffff8000100f1b90: get_task_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct mm_struct *get_task_mm(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (c034fc78)
Location: kernel/fork.c:1208
Inline: False
Direct callers:
  - kernel/fork.c:mm_access
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_access_vm
  - kernel/sys.c:getrusage
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/events/core.c:perf_event_addr_filters_apply
  - mm/util.c:get_cmdline
  - mm/memory.c:access_process_vm
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/base.c:proc_coredump_filter_write
  - fs/proc/base.c:proc_coredump_filter_read
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
```
**Symbols:**

```
c034fc78-c034fcf0: get_task_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct mm_struct *get_task_mm(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (c000000000137bc0)
Location: kernel/fork.c:1208
Inline: False
Direct callers:
  - kernel/fork.c:mm_access
  - kernel/ptrace.c:ptrace_access_vm
  - kernel/sys.c:getrusage
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/events/core.c:perf_event_addr_filters_apply
  - mm/util.c:get_cmdline
  - mm/memory.c:access_process_vm
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/migrate.c:kernel_move_pages
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/base.c:proc_coredump_filter_write
  - fs/proc/base.c:proc_coredump_filter_read
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
```
**Symbols:**

```
c000000000137bc0-c000000000137cac: get_task_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct mm_struct *get_task_mm(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffe0000bee2e)
Location: kernel/fork.c:1208
Inline: False
Direct callers:
  - kernel/fork.c:mm_access
  - kernel/ptrace.c:ptrace_access_vm
  - kernel/sys.c:getrusage
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/events/core.c:perf_event_addr_filters_apply
  - mm/util.c:get_cmdline
  - mm/memory.c:access_process_vm
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/base.c:proc_coredump_filter_write
  - fs/proc/base.c:proc_coredump_filter_read
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
```
**Symbols:**

```
ffffffe0000bee2e-ffffffe0000beeb8: get_task_mm (STB_GLOBAL)
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
struct mm_struct *get_task_mm(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81097010)
Location: kernel/fork.c:1208
Inline: False
Direct callers:
  - kernel/fork.c:mm_access
  - kernel/ptrace.c:ptrace_access_vm
  - kernel/sys.c:getrusage
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/events/core.c:perf_event_addr_filters_apply
  - mm/util.c:get_cmdline
  - mm/memory.c:access_process_vm
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/migrate.c:kernel_move_pages
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/base.c:proc_coredump_filter_write
  - fs/proc/base.c:proc_coredump_filter_read
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
```
**Symbols:**

```
ffffffff81097010-ffffffff8109705c: get_task_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct mm_struct *get_task_mm(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81085a90)
Location: kernel/fork.c:1208
Inline: False
Direct callers:
  - kernel/fork.c:mm_access
  - kernel/ptrace.c:ptrace_access_vm
  - kernel/sys.c:getrusage
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/events/core.c:perf_event_addr_filters_apply
  - mm/util.c:get_cmdline
  - mm/memory.c:access_process_vm
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/migrate.c:kernel_move_pages
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/base.c:proc_coredump_filter_write
  - fs/proc/base.c:proc_coredump_filter_read
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
```
**Symbols:**

```
ffffffff81085a90-ffffffff81085adc: get_task_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct mm_struct *get_task_mm(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81096fc0)
Location: kernel/fork.c:1208
Inline: False
Direct callers:
  - kernel/fork.c:mm_access
  - kernel/ptrace.c:ptrace_access_vm
  - kernel/sys.c:getrusage
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/events/core.c:perf_event_addr_filters_apply
  - mm/util.c:get_cmdline
  - mm/memory.c:access_process_vm
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/migrate.c:kernel_move_pages
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/base.c:proc_coredump_filter_write
  - fs/proc/base.c:proc_coredump_filter_read
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
```
**Symbols:**

```
ffffffff81096fc0-ffffffff8109700c: get_task_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct mm_struct *get_task_mm(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8109dc50)
Location: kernel/fork.c:1208
Inline: False
Direct callers:
  - kernel/fork.c:mm_access
  - kernel/ptrace.c:ptrace_access_vm
  - kernel/sys.c:getrusage
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/tsacct.c:xacct_add_tsk
  - kernel/trace/trace_output.c:trace_user_stack_print
  - kernel/events/core.c:perf_event_addr_filters_apply
  - mm/util.c:get_cmdline
  - mm/memory.c:access_process_vm
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/migrate.c:kernel_move_pages
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/base.c:proc_coredump_filter_write
  - fs/proc/base.c:proc_coredump_filter_read
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
```
**Symbols:**

```
ffffffff8109dc50-ffffffff8109dc9f: get_task_mm (STB_GLOBAL)
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
