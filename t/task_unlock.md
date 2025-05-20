# Function: <code>task_unlock</code>

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
In init/main.c (ffffffff81f5a0ab)
Location: include/linux/sched.h:2743
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In kernel/fork.c (ffffffff8107d627)
Location: include/linux/sched.h:2743
Inline: True
Inline callers:
  - kernel/fork.c:get_task_mm
  - kernel/fork.c:mm_release
  - kernel/fork.c:copy_process
  - kernel/fork.c:_do_fork
  - kernel/fork.c:SyS_unshare
  - kernel/fork.c:unshare_files
```
```
In kernel/cpu.c (ffffffff81081af8)
Location: include/linux/sched.h:2743
Inline: True
Inline callers:
  - kernel/cpu.c:clear_tasks_mm_cpumask
```
```
In kernel/exit.c (ffffffff81083763)
Location: include/linux/sched.h:2743
Inline: True
Inline callers:
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
```
In kernel/ptrace.c (ffffffff8108ae76)
Location: include/linux/sched.h:2743
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:ptrace_may_access
```
```
In kernel/sys.c (ffffffff810925bf)
Location: include/linux/sched.h:2743
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_auxv
  - kernel/sys.c:SyS_old_getrlimit
  - kernel/sys.c:do_prlimit
```
```
In kernel/kthread.c (ffffffff810a0d8b)
Location: include/linux/sched.h:2743
Inline: True
Inline callers:
  - kernel/kthread.c:kthreadd
```
```
In kernel/nsproxy.c (ffffffff810a1291)
Location: include/linux/sched.h:2743
Inline: True
Inline callers:
  - kernel/nsproxy.c:switch_task_namespaces
```
```
In kernel/sched/debug.c (ffffffff810c8993)
Location: include/linux/sched.h:2743
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
```
```
In kernel/kcmp.c (ffffffff810e9755)
Location: include/linux/sched.h:2743
Inline: True
Inline callers:
  - kernel/kcmp.c:get_file_raw_ptr
```
```
In kernel/cgroup.c (ffffffff81112007)
Location: include/linux/sched.h:2743
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroupns_get
```
```
In kernel/cpuset.c (ffffffff8111b6d7)
Location: include/linux/sched.h:2743
Inline: True
```
```
In kernel/utsname.c (ffffffff8111db31)
Location: include/linux/sched.h:2743
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_get
```
```
In mm/oom_kill.c (ffffffff8119081f)
Location: include/linux/sched.h:2743
Inline: True
Inline callers:
  - mm/oom_kill.c:find_lock_task_mm
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/mmu_context.c (ffffffff811afbe5)
Location: include/linux/sched.h:2743
Inline: True
Inline callers:
  - mm/mmu_context.c:unuse_mm
  - mm/mmu_context.c:use_mm
```
```
In mm/mempolicy.c (ffffffff811e0e01)
Location: include/linux/sched.h:2743
Inline: True
Inline callers:
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:mempolicy_nodemask_intersects
  - mm/mempolicy.c:__mpol_dup
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:mpol_shared_policy_init
```
```
In mm/memcontrol.c (ffffffff811fef41)
Location: include/linux/sched.h:2743
Inline: True
Inline callers:
  - mm/memcontrol.c:task_in_mem_cgroup
```
```
In fs/exec.c (ffffffff81212737)
Location: include/linux/sched.h:2743
Inline: True
Inline callers:
  - fs/exec.c:get_task_comm
  - fs/exec.c:__set_task_comm
```
```
In fs/file.c (ffffffff8122a55e)
Location: include/linux/sched.h:2743
Inline: True
Inline callers:
  - fs/file.c:get_files_struct
  - fs/file.c:reset_files_struct
  - fs/file.c:exit_files
```
```
In fs/namespace.c (ffffffff8122b686)
Location: include/linux/sched.h:2743
Inline: True
Inline callers:
  - fs/namespace.c:mntns_get
```
```
In fs/fs_struct.c (ffffffff81241543)
Location: include/linux/sched.h:2743
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:exit_fs
  - fs/fs_struct.c:unshare_fs_struct
```
```
In fs/proc_namespace.c (ffffffff8124f100)
Location: include/linux/sched.h:2743
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/proc/task_mmu.c (ffffffff81277ff5)
Location: include/linux/sched.h:2743
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (ffffffff8127acc7)
Location: include/linux/sched.h:2743
Inline: True
Inline callers:
  - fs/proc/base.c:oom_score_adj_write
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:comm_show
  - fs/proc/base.c:proc_cwd_link
  - fs/proc/base.c:pid_revalidate
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:oom_adj_write
  - fs/proc/base.c:proc_pid_make_inode
```
```
In fs/proc/array.c (ffffffff81280b9f)
Location: include/linux/sched.h:2743
Inline: True
Inline callers:
  - fs/proc/array.c:proc_pid_status
```
```
In fs/proc/fd.c (ffffffff81281a68)
Location: include/linux/sched.h:2743
Inline: True
Inline callers:
  - fs/proc/fd.c:tid_fd_revalidate
```
```
In fs/proc/proc_net.c (ffffffff81286492)
Location: include/linux/sched.h:2743
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_task_net
```
```
In fs/hugetlbfs/inode.c (ffffffff812f52b1)
Location: include/linux/sched.h:2743
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
```
```
In ipc/namespace.c (ffffffff8132e977)
Location: include/linux/sched.h:2743
Inline: True
Inline callers:
  - ipc/namespace.c:ipcns_get
```
```
In security/selinux/hooks.c (ffffffff81346b6c)
Location: include/linux/sched.h:2743
Inline: True
```
```
In block/blk-ioc.c (ffffffff813beff6)
Location: include/linux/sched.h:2743
Inline: True
Inline callers:
  - block/blk-ioc.c:exit_io_context
  - block/blk-ioc.c:create_task_io_context
  - block/blk-ioc.c:get_task_io_context
  - block/blk-ioc.c:get_task_io_context
```
```
In block/blk-cgroup.c (ffffffff813d754e)
Location: include/linux/sched.h:2743
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_can_attach
```
```
In drivers/tty/tty_io.c (ffffffff814e36b0)
Location: include/linux/sched.h:2743
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:__do_SAK
```
```
In net/core/net_namespace.c (ffffffff8170fa63)
Location: include/linux/sched.h:2743
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_get
  - net/core/net_namespace.c:get_net_ns_by_pid
```
```
In net/core/netprio_cgroup.c (ffffffff8173da7c)
Location: include/linux/sched.h:2743
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:net_prio_attach
```
```
In net/core/netclassid_cgroup.c (ffffffff8173deb6)
Location: include/linux/sched.h:2743
Inline: True
Inline callers:
  - net/core/netclassid_cgroup.c:update_classid
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
In init/main.c (ffffffff81f8205f)
Location: include/linux/sched.h:3012
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In kernel/fork.c (ffffffff81082810)
Location: include/linux/sched.h:3012
Inline: True
Inline callers:
  - kernel/fork.c:unshare_files
  - kernel/fork.c:SyS_unshare
  - kernel/fork.c:_do_fork
  - kernel/fork.c:mm_release
  - kernel/fork.c:get_task_mm
  - kernel/fork.c:get_task_exe_file
```
```
In kernel/cpu.c (ffffffff81084b14)
Location: include/linux/sched.h:3012
Inline: True
Inline callers:
  - kernel/cpu.c:clear_tasks_mm_cpumask
```
```
In kernel/exit.c (ffffffff81086c3e)
Location: include/linux/sched.h:3012
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:mm_update_next_owner
```
```
In kernel/ptrace.c (ffffffff8108de66)
Location: include/linux/sched.h:3012
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:ptrace_may_access
```
```
In kernel/sys.c (ffffffff81095735)
Location: include/linux/sched.h:3012
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_auxv
  - kernel/sys.c:do_prlimit
  - kernel/sys.c:SyS_old_getrlimit
```
```
In kernel/kthread.c (ffffffff810a446c)
Location: include/linux/sched.h:3012
Inline: True
Inline callers:
  - kernel/kthread.c:kthreadd
```
```
In kernel/nsproxy.c (ffffffff810a49c1)
Location: include/linux/sched.h:3012
Inline: True
Inline callers:
  - kernel/nsproxy.c:switch_task_namespaces
```
```
In kernel/sched/debug.c (ffffffff810cc982)
Location: include/linux/sched.h:3012
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
```
```
In kernel/kcmp.c (ffffffff810f04b3)
Location: include/linux/sched.h:3012
Inline: True
Inline callers:
  - kernel/kcmp.c:get_file_raw_ptr
```
```
In kernel/cgroup.c (ffffffff81119727)
Location: include/linux/sched.h:3012
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroupns_get
```
```
In kernel/cpuset.c (ffffffff811235bf)
Location: include/linux/sched.h:3012
Inline: True
Inline callers:
  - kernel/cpuset.c:cpuset_change_task_nodemask
```
```
In kernel/utsname.c (ffffffff81125a01)
Location: include/linux/sched.h:3012
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_get
```
```
In mm/oom_kill.c (ffffffff811a50e4)
Location: include/linux/sched.h:3012
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:__oom_reap_task
  - mm/oom_kill.c:find_lock_task_mm
```
```
In mm/mmu_context.c (ffffffff811c9115)
Location: include/linux/sched.h:3012
Inline: True
Inline callers:
  - mm/mmu_context.c:unuse_mm
  - mm/mmu_context.c:use_mm
```
```
In mm/mempolicy.c (ffffffff81201bb5)
Location: include/linux/sched.h:3012
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_put_task_policy
  - mm/mempolicy.c:__mpol_dup
  - mm/mempolicy.c:mempolicy_nodemask_intersects
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
```
```
In mm/memcontrol.c (ffffffff81222cd5)
Location: include/linux/sched.h:3012
Inline: True
Inline callers:
  - mm/memcontrol.c:task_in_mem_cgroup
```
```
In fs/exec.c (ffffffff8123aaa4)
Location: include/linux/sched.h:3012
Inline: True
Inline callers:
  - fs/exec.c:__set_task_comm
  - fs/exec.c:get_task_comm
```
```
In fs/file.c (ffffffff81252e47)
Location: include/linux/sched.h:3012
Inline: True
Inline callers:
  - fs/file.c:exit_files
  - fs/file.c:reset_files_struct
  - fs/file.c:get_files_struct
```
```
In fs/namespace.c (ffffffff81253df6)
Location: include/linux/sched.h:3012
Inline: True
Inline callers:
  - fs/namespace.c:mntns_get
```
```
In fs/fs_struct.c (ffffffff81269b33)
Location: include/linux/sched.h:3012
Inline: True
Inline callers:
  - fs/fs_struct.c:unshare_fs_struct
  - fs/fs_struct.c:exit_fs
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/proc_namespace.c (ffffffff81277880)
Location: include/linux/sched.h:3012
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/coredump.c (ffffffff8129aef2)
Location: include/linux/sched.h:3012
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/task_mmu.c (ffffffff812a4355)
Location: include/linux/sched.h:3012
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (ffffffff812a8eaf)
Location: include/linux/sched.h:3012
Inline: True
Inline callers:
  - fs/proc/base.c:timerslack_ns_show
  - fs/proc/base.c:timerslack_ns_write
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:pid_revalidate
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/base.c:comm_show
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
```
```
In fs/proc/array.c (ffffffff812adc07)
Location: include/linux/sched.h:3012
Inline: True
Inline callers:
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
```
```
In fs/proc/fd.c (ffffffff812aeb1a)
Location: include/linux/sched.h:3012
Inline: True
Inline callers:
  - fs/proc/fd.c:tid_fd_revalidate
```
```
In fs/proc/proc_net.c (ffffffff812b3633)
Location: include/linux/sched.h:3012
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_task_net
```
```
In fs/hugetlbfs/inode.c (ffffffff81328cc3)
Location: include/linux/sched.h:3012
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
```
```
In ipc/namespace.c (ffffffff81363607)
Location: include/linux/sched.h:3012
Inline: True
Inline callers:
  - ipc/namespace.c:ipcns_get
```
```
In security/selinux/hooks.c (ffffffff8137c337)
Location: include/linux/sched.h:3012
Inline: True
```
```
In security/yama/yama_lsm.c (ffffffff813d11e9)
Location: include/linux/sched.h:3012
Inline: True
```
```
In block/blk-ioc.c (ffffffff81403116)
Location: include/linux/sched.h:3012
Inline: True
Inline callers:
  - block/blk-ioc.c:get_task_io_context
  - block/blk-ioc.c:get_task_io_context
  - block/blk-ioc.c:create_task_io_context
  - block/blk-ioc.c:exit_io_context
```
```
In block/ioprio.c (ffffffff814120a0)
Location: include/linux/sched.h:3012
Inline: True
```
```
In block/blk-cgroup.c (ffffffff8141d255)
Location: include/linux/sched.h:3012
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_can_attach
```
```
In drivers/tty/tty_io.c (ffffffff815349aa)
Location: include/linux/sched.h:3012
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:__do_SAK
```
```
In net/core/net_namespace.c (ffffffff81777393)
Location: include/linux/sched.h:3012
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_get
  - net/core/net_namespace.c:get_net_ns_by_pid
```
```
In net/core/netprio_cgroup.c (ffffffff817aa243)
Location: include/linux/sched.h:3012
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:net_prio_attach
```
```
In net/core/netclassid_cgroup.c (ffffffff817aa70d)
Location: include/linux/sched.h:3012
Inline: True
Inline callers:
  - net/core/netclassid_cgroup.c:update_classid
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
In init/main.c (ffffffff81fbe0e7)
Location: include/linux/sched.h:3126
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In kernel/fork.c (ffffffff81087270)
Location: include/linux/sched.h:3126
Inline: True
Inline callers:
  - kernel/fork.c:unshare_files
  - kernel/fork.c:SyS_unshare
  - kernel/fork.c:_do_fork
  - kernel/fork.c:mm_release
  - kernel/fork.c:get_task_mm
  - kernel/fork.c:get_task_exe_file
```
```
In kernel/cpu.c (ffffffff81089aa7)
Location: include/linux/sched.h:3126
Inline: True
Inline callers:
  - kernel/cpu.c:clear_tasks_mm_cpumask
```
```
In kernel/exit.c (ffffffff8108bba9)
Location: include/linux/sched.h:3126
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:mm_update_next_owner
```
```
In kernel/ptrace.c (ffffffff810935b6)
Location: include/linux/sched.h:3126
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:ptrace_may_access
```
```
In kernel/sys.c (ffffffff8109a725)
Location: include/linux/sched.h:3126
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_auxv
  - kernel/sys.c:do_prlimit
  - kernel/sys.c:SyS_old_getrlimit
```
```
In kernel/kthread.c (ffffffff810a9e88)
Location: include/linux/sched.h:3126
Inline: True
Inline callers:
  - kernel/kthread.c:kthreadd
```
```
In kernel/nsproxy.c (ffffffff810aa621)
Location: include/linux/sched.h:3126
Inline: True
Inline callers:
  - kernel/nsproxy.c:switch_task_namespaces
```
```
In kernel/sched/debug.c (ffffffff810d29a2)
Location: include/linux/sched.h:3126
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
```
```
In kernel/kcmp.c (ffffffff810f7613)
Location: include/linux/sched.h:3126
Inline: True
Inline callers:
  - kernel/kcmp.c:get_file_raw_ptr
```
```
In kernel/cgroup.c (ffffffff81120ef7)
Location: include/linux/sched.h:3126
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroupns_get
```
```
In kernel/cpuset.c (ffffffff8112b368)
Location: include/linux/sched.h:3126
Inline: True
Inline callers:
  - kernel/cpuset.c:cpuset_change_task_nodemask
```
```
In kernel/utsname.c (ffffffff8112f401)
Location: include/linux/sched.h:3126
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_get
```
```
In mm/oom_kill.c (ffffffff811b557f)
Location: include/linux/sched.h:3126
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:find_lock_task_mm
```
```
In mm/mmu_context.c (ffffffff811d91f5)
Location: include/linux/sched.h:3126
Inline: True
Inline callers:
  - mm/mmu_context.c:unuse_mm
  - mm/mmu_context.c:use_mm
```
```
In mm/mempolicy.c (ffffffff812136c4)
Location: include/linux/sched.h:3126
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_put_task_policy
  - mm/mempolicy.c:__mpol_dup
  - mm/mempolicy.c:mempolicy_nodemask_intersects
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:SYSC_get_mempolicy
  - mm/mempolicy.c:SYSC_get_mempolicy
  - mm/mempolicy.c:SYSC_mbind
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
```
```
In mm/memcontrol.c (ffffffff812350c5)
Location: include/linux/sched.h:3126
Inline: True
Inline callers:
  - mm/memcontrol.c:task_in_mem_cgroup
```
```
In fs/exec.c (ffffffff8124d854)
Location: include/linux/sched.h:3126
Inline: True
Inline callers:
  - fs/exec.c:__set_task_comm
  - fs/exec.c:get_task_comm
```
```
In fs/file.c (ffffffff812660b7)
Location: include/linux/sched.h:3126
Inline: True
Inline callers:
  - fs/file.c:exit_files
  - fs/file.c:reset_files_struct
  - fs/file.c:get_files_struct
```
```
In fs/namespace.c (ffffffff812670c6)
Location: include/linux/sched.h:3126
Inline: True
Inline callers:
  - fs/namespace.c:mntns_get
```
```
In fs/fs_struct.c (ffffffff8127cae3)
Location: include/linux/sched.h:3126
Inline: True
Inline callers:
  - fs/fs_struct.c:unshare_fs_struct
  - fs/fs_struct.c:exit_fs
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/proc_namespace.c (ffffffff8128b560)
Location: include/linux/sched.h:3126
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/coredump.c (ffffffff812afaac)
Location: include/linux/sched.h:3126
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/task_mmu.c (ffffffff812b9852)
Location: include/linux/sched.h:3126
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (ffffffff812be9ba)
Location: include/linux/sched.h:3126
Inline: True
Inline callers:
  - fs/proc/base.c:timerslack_ns_show
  - fs/proc/base.c:timerslack_ns_write
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:pid_revalidate
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_pid_make_inode
  - fs/proc/base.c:comm_show
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
```
```
In fs/proc/array.c (ffffffff812c350d)
Location: include/linux/sched.h:3126
Inline: True
Inline callers:
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
```
```
In fs/proc/fd.c (ffffffff812c44ea)
Location: include/linux/sched.h:3126
Inline: True
Inline callers:
  - fs/proc/fd.c:tid_fd_revalidate
```
```
In fs/proc/proc_net.c (ffffffff812c8e83)
Location: include/linux/sched.h:3126
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_task_net
```
```
In fs/hugetlbfs/inode.c (ffffffff8133ea03)
Location: include/linux/sched.h:3126
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
```
```
In ipc/namespace.c (ffffffff81379dd7)
Location: include/linux/sched.h:3126
Inline: True
Inline callers:
  - ipc/namespace.c:ipcns_get
```
```
In security/selinux/hooks.c (ffffffff81392df3)
Location: include/linux/sched.h:3126
Inline: True
```
```
In security/yama/yama_lsm.c (ffffffff813e8919)
Location: include/linux/sched.h:3126
Inline: True
```
```
In block/blk-ioc.c (ffffffff8141ce46)
Location: include/linux/sched.h:3126
Inline: True
Inline callers:
  - block/blk-ioc.c:get_task_io_context
  - block/blk-ioc.c:get_task_io_context
  - block/blk-ioc.c:create_task_io_context
  - block/blk-ioc.c:exit_io_context
```
```
In block/ioprio.c (ffffffff8142d500)
Location: include/linux/sched.h:3126
Inline: True
```
```
In block/blk-cgroup.c (ffffffff81438825)
Location: include/linux/sched.h:3126
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_can_attach
```
```
In drivers/tty/tty_io.c (ffffffff815610da)
Location: include/linux/sched.h:3126
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:__do_SAK
```
```
In net/core/net_namespace.c (ffffffff817a4383)
Location: include/linux/sched.h:3126
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_get
  - net/core/net_namespace.c:get_net_ns_by_pid
```
```
In net/core/netprio_cgroup.c (ffffffff817d8d83)
Location: include/linux/sched.h:3126
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:net_prio_attach
```
```
In net/core/netclassid_cgroup.c (ffffffff817d9263)
Location: include/linux/sched.h:3126
Inline: True
Inline callers:
  - net/core/netclassid_cgroup.c:write_classid
  - net/core/netclassid_cgroup.c:cgrp_attach
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
In init/main.c (ffffffff8209e1d1)
Location: include/linux/sched/task.h:134
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In kernel/fork.c (ffffffff810840ee)
Location: include/linux/sched/task.h:134
Inline: True
Inline callers:
  - kernel/fork.c:unshare_files
  - kernel/fork.c:SyS_unshare
  - kernel/fork.c:_do_fork
  - kernel/fork.c:mm_release
  - kernel/fork.c:get_task_mm
  - kernel/fork.c:get_task_exe_file
```
```
In kernel/cpu.c (ffffffff810869b7)
Location: include/linux/sched/task.h:134
Inline: True
Inline callers:
  - kernel/cpu.c:clear_tasks_mm_cpumask
```
```
In kernel/exit.c (ffffffff81088d4f)
Location: include/linux/sched/task.h:134
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:mm_update_next_owner
```
```
In kernel/ptrace.c (ffffffff810906c4)
Location: include/linux/sched/task.h:134
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:ptrace_may_access
```
```
In kernel/sys.c (ffffffff81097990)
Location: include/linux/sched/task.h:134
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_auxv
  - kernel/sys.c:do_prlimit
  - kernel/sys.c:compat_SyS_old_getrlimit
  - kernel/sys.c:SyS_old_getrlimit
```
```
In kernel/kthread.c (ffffffff810a6aa8)
Location: include/linux/sched/task.h:134
Inline: True
Inline callers:
  - kernel/kthread.c:kthreadd
```
```
In kernel/nsproxy.c (ffffffff810a7181)
Location: include/linux/sched/task.h:134
Inline: True
Inline callers:
  - kernel/nsproxy.c:switch_task_namespaces
```
```
In kernel/sched/debug.c (ffffffff810d1af0)
Location: include/linux/sched/task.h:134
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
```
```
In kernel/kcmp.c (ffffffff810f9403)
Location: include/linux/sched/task.h:134
Inline: True
Inline callers:
  - kernel/kcmp.c:get_file_raw_ptr
```
```
In kernel/cgroup/namespace.c (ffffffff81128c79)
Location: include/linux/sched/task.h:134
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:cgroupns_get
```
```
In kernel/cgroup/cpuset.c (ffffffff8112c670)
Location: include/linux/sched/task.h:134
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
```
In kernel/utsname.c (ffffffff81130a94)
Location: include/linux/sched/task.h:134
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_get
```
```
In kernel/pid_namespace.c (ffffffff8113278c)
Location: include/linux/sched/task.h:134
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_for_children_get
```
```
In mm/oom_kill.c (ffffffff811bd28f)
Location: include/linux/sched/task.h:134
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:find_lock_task_mm
```
```
In mm/mmu_context.c (ffffffff811e2005)
Location: include/linux/sched/task.h:134
Inline: True
Inline callers:
  - mm/mmu_context.c:unuse_mm
  - mm/mmu_context.c:use_mm
```
```
In mm/mempolicy.c (ffffffff8121e9db)
Location: include/linux/sched/task.h:134
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_put_task_policy
  - mm/mempolicy.c:__mpol_dup
  - mm/mempolicy.c:mempolicy_nodemask_intersects
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:SYSC_get_mempolicy
  - mm/mempolicy.c:SYSC_get_mempolicy
  - mm/mempolicy.c:SYSC_mbind
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
```
```
In mm/memcontrol.c (ffffffff81240b05)
Location: include/linux/sched/task.h:134
Inline: True
Inline callers:
  - mm/memcontrol.c:task_in_mem_cgroup
```
```
In fs/exec.c (ffffffff81259814)
Location: include/linux/sched/task.h:134
Inline: True
Inline callers:
  - fs/exec.c:__set_task_comm
  - fs/exec.c:get_task_comm
```
```
In fs/file.c (ffffffff81273897)
Location: include/linux/sched/task.h:134
Inline: True
Inline callers:
  - fs/file.c:exit_files
  - fs/file.c:reset_files_struct
  - fs/file.c:get_files_struct
```
```
In fs/namespace.c (ffffffff81274916)
Location: include/linux/sched/task.h:134
Inline: True
Inline callers:
  - fs/namespace.c:mntns_get
```
```
In fs/fs_struct.c (ffffffff8128a193)
Location: include/linux/sched/task.h:134
Inline: True
Inline callers:
  - fs/fs_struct.c:unshare_fs_struct
  - fs/fs_struct.c:exit_fs
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/proc_namespace.c (ffffffff81298363)
Location: include/linux/sched/task.h:134
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/coredump.c (ffffffff812bccf6)
Location: include/linux/sched/task.h:134
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/task_mmu.c (ffffffff812c714c)
Location: include/linux/sched/task.h:134
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (ffffffff812cb8ea)
Location: include/linux/sched/task.h:134
Inline: True
Inline callers:
  - fs/proc/base.c:timerslack_ns_show
  - fs/proc/base.c:timerslack_ns_write
  - fs/proc/base.c:task_dump_owner
  - fs/proc/base.c:comm_show
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
```
```
In fs/proc/array.c (ffffffff812d078f)
Location: include/linux/sched/task.h:134
Inline: True
Inline callers:
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
```
```
In fs/proc/proc_net.c (ffffffff812d6185)
Location: include/linux/sched/task.h:134
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_task_net
```
```
In fs/hugetlbfs/inode.c (ffffffff813535d0)
Location: include/linux/sched/task.h:134
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
```
```
In ipc/namespace.c (ffffffff8138d9d9)
Location: include/linux/sched/task.h:134
Inline: True
Inline callers:
  - ipc/namespace.c:ipcns_get
```
```
In security/selinux/hooks.c (ffffffff813a8fce)
Location: include/linux/sched/task.h:134
Inline: True
```
```
In security/yama/yama_lsm.c (ffffffff813f4b29)
Location: include/linux/sched/task.h:134
Inline: True
```
```
In block/blk-ioc.c (ffffffff8142aea6)
Location: include/linux/sched/task.h:134
Inline: True
Inline callers:
  - block/blk-ioc.c:get_task_io_context
  - block/blk-ioc.c:get_task_io_context
  - block/blk-ioc.c:create_task_io_context
  - block/blk-ioc.c:exit_io_context
```
```
In block/ioprio.c (ffffffff8143a7e5)
Location: include/linux/sched/task.h:134
Inline: True
```
```
In block/blk-cgroup.c (ffffffff81445fbc)
Location: include/linux/sched/task.h:134
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_can_attach
```
```
In drivers/tty/tty_io.c (ffffffff8157440f)
Location: include/linux/sched/task.h:134
Inline: True
```
```
In net/core/net_namespace.c (ffffffff817c24f5)
Location: include/linux/sched/task.h:134
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_get
  - net/core/net_namespace.c:get_net_ns_by_pid
```
```
In net/core/netprio_cgroup.c (ffffffff817f7fa3)
Location: include/linux/sched/task.h:134
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:net_prio_attach
```
```
In net/core/netclassid_cgroup.c (ffffffff817f8473)
Location: include/linux/sched/task.h:134
Inline: True
Inline callers:
  - net/core/netclassid_cgroup.c:write_classid
  - net/core/netclassid_cgroup.c:cgrp_attach
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
In init/main.c (ffffffff826a419c)
Location: include/linux/sched/task.h:134
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In kernel/fork.c (ffffffff8108a9de)
Location: include/linux/sched/task.h:134
Inline: True
Inline callers:
  - kernel/fork.c:unshare_files
  - kernel/fork.c:SyS_unshare
  - kernel/fork.c:_do_fork
  - kernel/fork.c:mm_release
  - kernel/fork.c:get_task_mm
  - kernel/fork.c:get_task_exe_file
```
```
In kernel/cpu.c (ffffffff8108d767)
Location: include/linux/sched/task.h:134
Inline: True
Inline callers:
  - kernel/cpu.c:clear_tasks_mm_cpumask
```
```
In kernel/exit.c (ffffffff8108fa87)
Location: include/linux/sched/task.h:134
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:mm_update_next_owner
```
```
In kernel/ptrace.c (ffffffff81097534)
Location: include/linux/sched/task.h:134
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:ptrace_may_access
```
```
In kernel/sys.c (ffffffff8109e680)
Location: include/linux/sched/task.h:134
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_auxv
  - kernel/sys.c:do_prlimit
  - kernel/sys.c:compat_SyS_old_getrlimit
  - kernel/sys.c:SyS_old_getrlimit
```
```
In kernel/kthread.c (ffffffff810ad216)
Location: include/linux/sched/task.h:134
Inline: True
Inline callers:
  - kernel/kthread.c:kthreadd
```
```
In kernel/nsproxy.c (ffffffff810ad901)
Location: include/linux/sched/task.h:134
Inline: True
Inline callers:
  - kernel/nsproxy.c:switch_task_namespaces
```
```
In kernel/sched/debug.c (ffffffff810d9691)
Location: include/linux/sched/task.h:134
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
```
```
In kernel/kcmp.c (ffffffff81103e7f)
Location: include/linux/sched/task.h:134
Inline: True
Inline callers:
  - kernel/kcmp.c:get_file_raw_ptr
```
```
In kernel/cgroup/namespace.c (ffffffff81135a5f)
Location: include/linux/sched/task.h:134
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:cgroupns_get
```
```
In kernel/cgroup/cpuset.c (ffffffff811394a0)
Location: include/linux/sched/task.h:134
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
```
In kernel/utsname.c (ffffffff8113d9ea)
Location: include/linux/sched/task.h:134
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_get
```
```
In kernel/pid_namespace.c (ffffffff8113f7d2)
Location: include/linux/sched/task.h:134
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_for_children_get
```
```
In mm/oom_kill.c (ffffffff811d1eaa)
Location: include/linux/sched/task.h:134
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:find_lock_task_mm
```
```
In mm/mmu_context.c (ffffffff811f7f99)
Location: include/linux/sched/task.h:134
Inline: True
Inline callers:
  - mm/mmu_context.c:unuse_mm
  - mm/mmu_context.c:use_mm
```
```
In mm/mempolicy.c (ffffffff81239bfb)
Location: include/linux/sched/task.h:134
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_put_task_policy
  - mm/mempolicy.c:__mpol_dup
  - mm/mempolicy.c:mempolicy_nodemask_intersects
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:SYSC_get_mempolicy
  - mm/mempolicy.c:SYSC_get_mempolicy
  - mm/mempolicy.c:SYSC_mbind
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
```
```
In mm/memcontrol.c (ffffffff81260845)
Location: include/linux/sched/task.h:134
Inline: True
Inline callers:
  - mm/memcontrol.c:task_in_mem_cgroup
```
```
In fs/exec.c (ffffffff8127ba74)
Location: include/linux/sched/task.h:134
Inline: True
Inline callers:
  - fs/exec.c:__set_task_comm
  - fs/exec.c:__get_task_comm
```
```
In fs/file.c (ffffffff812961c7)
Location: include/linux/sched/task.h:134
Inline: True
Inline callers:
  - fs/file.c:exit_files
  - fs/file.c:reset_files_struct
  - fs/file.c:get_files_struct
```
```
In fs/namespace.c (ffffffff81297246)
Location: include/linux/sched/task.h:134
Inline: True
Inline callers:
  - fs/namespace.c:mntns_get
```
```
In fs/fs_struct.c (ffffffff812accd3)
Location: include/linux/sched/task.h:134
Inline: True
Inline callers:
  - fs/fs_struct.c:unshare_fs_struct
  - fs/fs_struct.c:exit_fs
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/proc_namespace.c (ffffffff812bb663)
Location: include/linux/sched/task.h:134
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/coredump.c (ffffffff812e05c1)
Location: include/linux/sched/task.h:134
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/task_mmu.c (ffffffff812ead4c)
Location: include/linux/sched/task.h:134
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (ffffffff812f031a)
Location: include/linux/sched/task.h:134
Inline: True
Inline callers:
  - fs/proc/base.c:timerslack_ns_show
  - fs/proc/base.c:timerslack_ns_write
  - fs/proc/base.c:task_dump_owner
  - fs/proc/base.c:comm_show
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
```
```
In fs/proc/array.c (ffffffff812f4fc1)
Location: include/linux/sched/task.h:134
Inline: True
Inline callers:
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
```
```
In fs/proc/proc_net.c (ffffffff812fa9c5)
Location: include/linux/sched/task.h:134
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_task_net
```
```
In fs/hugetlbfs/inode.c (ffffffff813781f0)
Location: include/linux/sched/task.h:134
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
```
```
In ipc/namespace.c (ffffffff813b2dff)
Location: include/linux/sched/task.h:134
Inline: True
Inline callers:
  - ipc/namespace.c:ipcns_get
```
```
In security/selinux/hooks.c (ffffffff813cef06)
Location: include/linux/sched/task.h:134
Inline: True
```
```
In security/yama/yama_lsm.c (ffffffff8141cec9)
Location: include/linux/sched/task.h:134
Inline: True
```
```
In block/blk-ioc.c (ffffffff81456096)
Location: include/linux/sched/task.h:134
Inline: True
Inline callers:
  - block/blk-ioc.c:get_task_io_context
  - block/blk-ioc.c:get_task_io_context
  - block/blk-ioc.c:create_task_io_context
  - block/blk-ioc.c:exit_io_context
```
```
In block/ioprio.c (ffffffff81466805)
Location: include/linux/sched/task.h:134
Inline: True
```
```
In block/blk-cgroup.c (ffffffff81472b1c)
Location: include/linux/sched/task.h:134
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_can_attach
```
```
In drivers/tty/tty_io.c (ffffffff815d758f)
Location: include/linux/sched/task.h:134
Inline: True
```
```
In net/core/net_namespace.c (ffffffff8183bf45)
Location: include/linux/sched/task.h:134
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_get
  - net/core/net_namespace.c:get_net_ns_by_pid
```
```
In net/core/netprio_cgroup.c (ffffffff81875863)
Location: include/linux/sched/task.h:134
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:net_prio_attach
```
```
In net/core/netclassid_cgroup.c (ffffffff81875d38)
Location: include/linux/sched/task.h:134
Inline: True
Inline callers:
  - net/core/netclassid_cgroup.c:write_classid
  - net/core/netclassid_cgroup.c:cgrp_attach
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
In init/main.c (ffffffff826cd296)
Location: include/linux/sched/task.h:148
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff810865cb)
Location: include/linux/sched/task.h:148
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_switch_mm
```
```
In kernel/fork.c (ffffffff8108e24b)
Location: include/linux/sched/task.h:148
Inline: True
Inline callers:
  - kernel/fork.c:unshare_files
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:_do_fork
  - kernel/fork.c:mm_release
  - kernel/fork.c:get_task_mm
  - kernel/fork.c:get_task_exe_file
```
```
In kernel/cpu.c (ffffffff810912f7)
Location: include/linux/sched/task.h:148
Inline: True
Inline callers:
  - kernel/cpu.c:clear_tasks_mm_cpumask
```
```
In kernel/exit.c (ffffffff810935ed)
Location: include/linux/sched/task.h:148
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:mm_update_next_owner
```
```
In kernel/ptrace.c (ffffffff8109aa05)
Location: include/linux/sched/task.h:148
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:ptrace_may_access
```
```
In kernel/sys.c (ffffffff810a5230)
Location: include/linux/sched/task.h:148
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_auxv
  - kernel/sys.c:do_prlimit
  - kernel/sys.c:__x32_compat_sys_old_getrlimit
  - kernel/sys.c:__ia32_compat_sys_old_getrlimit
  - kernel/sys.c:__ia32_sys_old_getrlimit
  - kernel/sys.c:__x64_sys_old_getrlimit
```
```
In kernel/kthread.c (ffffffff810b3f86)
Location: include/linux/sched/task.h:148
Inline: True
Inline callers:
  - kernel/kthread.c:kthreadd
```
```
In kernel/nsproxy.c (ffffffff810b467c)
Location: include/linux/sched/task.h:148
Inline: True
Inline callers:
  - kernel/nsproxy.c:switch_task_namespaces
```
```
In kernel/sched/debug.c (ffffffff810e06a6)
Location: include/linux/sched/task.h:148
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
```
```
In kernel/kcmp.c (ffffffff8110e925)
Location: include/linux/sched/task.h:148
Inline: True
Inline callers:
  - kernel/kcmp.c:get_file_raw_ptr
```
```
In kernel/cgroup/namespace.c (ffffffff811442cf)
Location: include/linux/sched/task.h:148
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:cgroupns_get
```
```
In kernel/cgroup/cpuset.c (ffffffff81148570)
Location: include/linux/sched/task.h:148
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
```
In kernel/utsname.c (ffffffff8114c38a)
Location: include/linux/sched/task.h:148
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_get
```
```
In kernel/pid_namespace.c (ffffffff8114e022)
Location: include/linux/sched/task.h:148
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_for_children_get
```
```
In mm/oom_kill.c (ffffffff811f2caa)
Location: include/linux/sched/task.h:148
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:find_lock_task_mm
```
```
In mm/mmu_context.c (ffffffff81219249)
Location: include/linux/sched/task.h:148
Inline: True
Inline callers:
  - mm/mmu_context.c:unuse_mm
  - mm/mmu_context.c:use_mm
```
```
In mm/mempolicy.c (ffffffff8125d1dc)
Location: include/linux/sched/task.h:148
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_put_task_policy
  - mm/mempolicy.c:__mpol_dup
  - mm/mempolicy.c:mempolicy_nodemask_intersects
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
```
```
In mm/memcontrol.c (ffffffff81284a1b)
Location: include/linux/sched/task.h:148
Inline: True
Inline callers:
  - mm/memcontrol.c:task_in_mem_cgroup
```
```
In fs/exec.c (ffffffff812a1909)
Location: include/linux/sched/task.h:148
Inline: True
Inline callers:
  - fs/exec.c:finalize_exec
  - fs/exec.c:__set_task_comm
  - fs/exec.c:__get_task_comm
```
```
In fs/file.c (ffffffff812bc65a)
Location: include/linux/sched/task.h:148
Inline: True
Inline callers:
  - fs/file.c:exit_files
  - fs/file.c:reset_files_struct
  - fs/file.c:get_files_struct
```
```
In fs/namespace.c (ffffffff812bdcd6)
Location: include/linux/sched/task.h:148
Inline: True
Inline callers:
  - fs/namespace.c:mntns_get
```
```
In fs/fs_struct.c (ffffffff812d48a3)
Location: include/linux/sched/task.h:148
Inline: True
Inline callers:
  - fs/fs_struct.c:unshare_fs_struct
  - fs/fs_struct.c:exit_fs
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/proc_namespace.c (ffffffff812e4207)
Location: include/linux/sched/task.h:148
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/coredump.c (ffffffff8130c7f6)
Location: include/linux/sched/task.h:148
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/task_mmu.c (ffffffff813188f8)
Location: include/linux/sched/task.h:148
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (ffffffff8131d272)
Location: include/linux/sched/task.h:148
Inline: True
Inline callers:
  - fs/proc/base.c:timerslack_ns_show
  - fs/proc/base.c:timerslack_ns_write
  - fs/proc/base.c:task_dump_owner
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
```
```
In fs/proc/array.c (ffffffff81322391)
Location: include/linux/sched/task.h:148
Inline: True
Inline callers:
  - fs/proc/array.c:proc_pid_status
```
```
In fs/proc/proc_net.c (ffffffff81327f9f)
Location: include/linux/sched/task.h:148
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_task_net
```
```
In fs/hugetlbfs/inode.c (ffffffff813a6bf3)
Location: include/linux/sched/task.h:148
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
```
```
In ipc/namespace.c (ffffffff813e353f)
Location: include/linux/sched/task.h:148
Inline: True
Inline callers:
  - ipc/namespace.c:ipcns_get
```
```
In security/selinux/hooks.c (ffffffff81402539)
Location: include/linux/sched/task.h:148
Inline: True
```
```
In security/yama/yama_lsm.c (ffffffff8144f12b)
Location: include/linux/sched/task.h:148
Inline: True
```
```
In block/blk-ioc.c (ffffffff81489455)
Location: include/linux/sched/task.h:148
Inline: True
Inline callers:
  - block/blk-ioc.c:create_task_io_context
  - block/blk-ioc.c:exit_io_context
```
```
In block/ioprio.c (ffffffff8149a155)
Location: include/linux/sched/task.h:148
Inline: True
```
```
In block/blk-cgroup.c (ffffffff814a7aac)
Location: include/linux/sched/task.h:148
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_can_attach
```
```
In drivers/tty/tty_io.c (ffffffff81610a1b)
Location: include/linux/sched/task.h:148
Inline: True
```
```
In net/core/net_namespace.c (ffffffff81886feb)
Location: include/linux/sched/task.h:148
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_get
  - net/core/net_namespace.c:get_net_ns_by_pid
```
```
In net/core/netprio_cgroup.c (ffffffff818c7363)
Location: include/linux/sched/task.h:148
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:net_prio_attach
```
```
In net/core/netclassid_cgroup.c (ffffffff818c7638)
Location: include/linux/sched/task.h:148
Inline: True
Inline callers:
  - net/core/netclassid_cgroup.c:write_classid
  - net/core/netclassid_cgroup.c:cgrp_attach
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
In init/main.c (ffffffff8288326c)
Location: include/linux/sched/task.h:150
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In kernel/fork.c (ffffffff810964db)
Location: include/linux/sched/task.h:150
Inline: True
Inline callers:
  - kernel/fork.c:unshare_files
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:_do_fork
  - kernel/fork.c:mm_release
  - kernel/fork.c:get_task_mm
  - kernel/fork.c:get_task_exe_file
```
```
In kernel/cpu.c (ffffffff810995d4)
Location: include/linux/sched/task.h:150
Inline: True
Inline callers:
  - kernel/cpu.c:clear_tasks_mm_cpumask
```
```
In kernel/exit.c (ffffffff8109b8ac)
Location: include/linux/sched/task.h:150
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:mm_update_next_owner
```
```
In kernel/ptrace.c (ffffffff810a2c35)
Location: include/linux/sched/task.h:150
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:ptrace_may_access
```
```
In kernel/sys.c (ffffffff810adee0)
Location: include/linux/sched/task.h:150
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_auxv
  - kernel/sys.c:do_prlimit
  - kernel/sys.c:__x32_compat_sys_old_getrlimit
  - kernel/sys.c:__ia32_compat_sys_old_getrlimit
  - kernel/sys.c:__ia32_sys_old_getrlimit
  - kernel/sys.c:__x64_sys_old_getrlimit
```
```
In kernel/kthread.c (ffffffff810bd0d6)
Location: include/linux/sched/task.h:150
Inline: True
Inline callers:
  - kernel/kthread.c:kthreadd
```
```
In kernel/nsproxy.c (ffffffff810bd7cc)
Location: include/linux/sched/task.h:150
Inline: True
Inline callers:
  - kernel/nsproxy.c:switch_task_namespaces
```
```
In kernel/sched/debug.c (ffffffff810eae5c)
Location: include/linux/sched/task.h:150
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
```
```
In kernel/kcmp.c (ffffffff81119ea5)
Location: include/linux/sched/task.h:150
Inline: True
Inline callers:
  - kernel/kcmp.c:get_file_raw_ptr
```
```
In kernel/cgroup/namespace.c (ffffffff8114fddd)
Location: include/linux/sched/task.h:150
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:cgroupns_get
```
```
In kernel/cgroup/cpuset.c (ffffffff81154090)
Location: include/linux/sched/task.h:150
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
```
In kernel/utsname.c (ffffffff81158f98)
Location: include/linux/sched/task.h:150
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_get
```
```
In kernel/pid_namespace.c (ffffffff8115add2)
Location: include/linux/sched/task.h:150
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_for_children_get
```
```
In mm/oom_kill.c (ffffffff81204cbf)
Location: include/linux/sched/task.h:150
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:find_lock_task_mm
```
```
In mm/mmu_context.c (ffffffff8122c1a9)
Location: include/linux/sched/task.h:150
Inline: True
Inline callers:
  - mm/mmu_context.c:unuse_mm
  - mm/mmu_context.c:use_mm
```
```
In mm/mempolicy.c (ffffffff81271a9c)
Location: include/linux/sched/task.h:150
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_put_task_policy
  - mm/mempolicy.c:__mpol_dup
  - mm/mempolicy.c:mempolicy_nodemask_intersects
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
```
```
In mm/memcontrol.c (ffffffff81299930)
Location: include/linux/sched/task.h:150
Inline: True
Inline callers:
  - mm/memcontrol.c:task_in_mem_cgroup
```
```
In fs/exec.c (ffffffff812b6e79)
Location: include/linux/sched/task.h:150
Inline: True
Inline callers:
  - fs/exec.c:finalize_exec
  - fs/exec.c:__set_task_comm
  - fs/exec.c:__get_task_comm
```
```
In fs/file.c (ffffffff812d191a)
Location: include/linux/sched/task.h:150
Inline: True
Inline callers:
  - fs/file.c:exit_files
  - fs/file.c:reset_files_struct
  - fs/file.c:get_files_struct
```
```
In fs/namespace.c (ffffffff812d3266)
Location: include/linux/sched/task.h:150
Inline: True
Inline callers:
  - fs/namespace.c:mntns_get
```
```
In fs/fs_struct.c (ffffffff812e9c73)
Location: include/linux/sched/task.h:150
Inline: True
Inline callers:
  - fs/fs_struct.c:unshare_fs_struct
  - fs/fs_struct.c:exit_fs
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/proc_namespace.c (ffffffff812f8e87)
Location: include/linux/sched/task.h:150
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/coredump.c (ffffffff8132212b)
Location: include/linux/sched/task.h:150
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/task_mmu.c (ffffffff8132f717)
Location: include/linux/sched/task.h:150
Inline: True
```
```
In fs/proc/base.c (ffffffff81334490)
Location: include/linux/sched/task.h:150
Inline: True
Inline callers:
  - fs/proc/base.c:timerslack_ns_show
  - fs/proc/base.c:timerslack_ns_write
  - fs/proc/base.c:task_dump_owner
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
```
```
In fs/proc/array.c (ffffffff813394a1)
Location: include/linux/sched/task.h:150
Inline: True
Inline callers:
  - fs/proc/array.c:proc_pid_status
```
```
In fs/proc/proc_net.c (ffffffff8133f188)
Location: include/linux/sched/task.h:150
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_task_net
```
```
In fs/hugetlbfs/inode.c (ffffffff813bfa15)
Location: include/linux/sched/task.h:150
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
```
```
In ipc/namespace.c (ffffffff813fdebd)
Location: include/linux/sched/task.h:150
Inline: True
Inline callers:
  - ipc/namespace.c:ipcns_get
```
```
In security/selinux/hooks.c (ffffffff8141adb4)
Location: include/linux/sched/task.h:150
Inline: True
```
```
In security/yama/yama_lsm.c (ffffffff8146bfab)
Location: include/linux/sched/task.h:150
Inline: True
```
```
In block/blk-ioc.c (ffffffff814a3326)
Location: include/linux/sched/task.h:150
Inline: True
Inline callers:
  - block/blk-ioc.c:get_task_io_context
  - block/blk-ioc.c:get_task_io_context
  - block/blk-ioc.c:create_task_io_context
  - block/blk-ioc.c:exit_io_context
```
```
In block/ioprio.c (ffffffff814b4465)
Location: include/linux/sched/task.h:150
Inline: True
```
```
In block/blk-cgroup.c (ffffffff814c17dc)
Location: include/linux/sched/task.h:150
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_can_attach
```
```
In drivers/tty/tty_io.c (ffffffff8162d75b)
Location: include/linux/sched/task.h:150
Inline: True
```
```
In net/core/net_namespace.c (ffffffff818a76f9)
Location: include/linux/sched/task.h:150
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_get
  - net/core/net_namespace.c:get_net_ns_by_pid
```
```
In net/core/netprio_cgroup.c (ffffffff818f04a3)
Location: include/linux/sched/task.h:150
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:net_prio_attach
```
```
In net/core/netclassid_cgroup.c (ffffffff818f0778)
Location: include/linux/sched/task.h:150
Inline: True
Inline callers:
  - net/core/netclassid_cgroup.c:write_classid
  - net/core/netclassid_cgroup.c:cgrp_attach
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
In init/main.c (ffffffff8289a2c2)
Location: include/linux/sched/task.h:167
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In kernel/fork.c (ffffffff8109aa1a)
Location: include/linux/sched/task.h:167
Inline: True
Inline callers:
  - kernel/fork.c:unshare_files
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:_do_fork
  - kernel/fork.c:copy_process
  - kernel/fork.c:mm_release
  - kernel/fork.c:get_task_mm
  - kernel/fork.c:get_task_exe_file
```
```
In kernel/cpu.c (ffffffff8109d8ef)
Location: include/linux/sched/task.h:167
Inline: True
Inline callers:
  - kernel/cpu.c:clear_tasks_mm_cpumask
```
```
In kernel/exit.c (ffffffff8109ff1b)
Location: include/linux/sched/task.h:167
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:mm_update_next_owner
```
```
In kernel/ptrace.c (ffffffff810a78fe)
Location: include/linux/sched/task.h:167
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:ptrace_may_access
```
```
In kernel/sys.c (ffffffff810b3c30)
Location: include/linux/sched/task.h:167
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_auxv
  - kernel/sys.c:do_prlimit
  - kernel/sys.c:__x32_compat_sys_old_getrlimit
  - kernel/sys.c:__ia32_compat_sys_old_getrlimit
  - kernel/sys.c:__ia32_sys_old_getrlimit
  - kernel/sys.c:__x64_sys_old_getrlimit
```
```
In kernel/kthread.c (ffffffff810c2fa6)
Location: include/linux/sched/task.h:167
Inline: True
Inline callers:
  - kernel/kthread.c:kthreadd
```
```
In kernel/nsproxy.c (ffffffff810c3819)
Location: include/linux/sched/task.h:167
Inline: True
Inline callers:
  - kernel/nsproxy.c:switch_task_namespaces
```
```
In kernel/sched/debug.c (ffffffff810f1c7c)
Location: include/linux/sched/task.h:167
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
```
```
In kernel/kcmp.c (ffffffff811248f0)
Location: include/linux/sched/task.h:167
Inline: True
Inline callers:
  - kernel/kcmp.c:get_file_raw_ptr
```
```
In kernel/cgroup/namespace.c (ffffffff8115bcdd)
Location: include/linux/sched/task.h:167
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:cgroupns_get
```
```
In kernel/cgroup/cpuset.c (ffffffff811605e0)
Location: include/linux/sched/task.h:167
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
```
In kernel/utsname.c (ffffffff811656c8)
Location: include/linux/sched/task.h:167
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_get
```
```
In kernel/pid_namespace.c (ffffffff81167490)
Location: include/linux/sched/task.h:167
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_for_children_get
```
```
In mm/oom_kill.c (ffffffff8121c2f6)
Location: include/linux/sched/task.h:167
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:find_lock_task_mm
```
```
In mm/mmu_context.c (ffffffff8123beb8)
Location: include/linux/sched/task.h:167
Inline: True
Inline callers:
  - mm/mmu_context.c:unuse_mm
  - mm/mmu_context.c:use_mm
```
```
In mm/mempolicy.c (ffffffff8128d0b8)
Location: include/linux/sched/task.h:167
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_put_task_policy
  - mm/mempolicy.c:__mpol_dup
  - mm/mempolicy.c:mempolicy_nodemask_intersects
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
```
```
In fs/exec.c (ffffffff812d3bdd)
Location: include/linux/sched/task.h:167
Inline: True
Inline callers:
  - fs/exec.c:finalize_exec
  - fs/exec.c:__set_task_comm
  - fs/exec.c:__get_task_comm
```
```
In fs/file.c (ffffffff812ee91a)
Location: include/linux/sched/task.h:167
Inline: True
Inline callers:
  - fs/file.c:exit_files
  - fs/file.c:reset_files_struct
  - fs/file.c:get_files_struct
```
```
In fs/namespace.c (ffffffff812f0425)
Location: include/linux/sched/task.h:167
Inline: True
Inline callers:
  - fs/namespace.c:mntns_get
```
```
In fs/fs_struct.c (ffffffff81308673)
Location: include/linux/sched/task.h:167
Inline: True
Inline callers:
  - fs/fs_struct.c:unshare_fs_struct
  - fs/fs_struct.c:exit_fs
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/proc_namespace.c (ffffffff813194aa)
Location: include/linux/sched/task.h:167
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/coredump.c (ffffffff8134a05c)
Location: include/linux/sched/task.h:167
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/task_mmu.c (ffffffff81357516)
Location: include/linux/sched/task.h:167
Inline: True
```
```
In fs/proc/base.c (ffffffff8135c316)
Location: include/linux/sched/task.h:167
Inline: True
Inline callers:
  - fs/proc/base.c:timerslack_ns_show
  - fs/proc/base.c:timerslack_ns_write
  - fs/proc/base.c:task_dump_owner
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
```
```
In fs/proc/array.c (ffffffff81360488)
Location: include/linux/sched/task.h:167
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In fs/proc/proc_net.c (ffffffff813674bd)
Location: include/linux/sched/task.h:167
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_task_net
```
```
In fs/hugetlbfs/inode.c (ffffffff813ea24b)
Location: include/linux/sched/task.h:167
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
```
```
In ipc/namespace.c (ffffffff8142a4ed)
Location: include/linux/sched/task.h:167
Inline: True
Inline callers:
  - ipc/namespace.c:ipcns_get
```
```
In security/selinux/hooks.c (ffffffff8144889c)
Location: include/linux/sched/task.h:167
Inline: True
```
```
In security/yama/yama_lsm.c (ffffffff81498fac)
Location: include/linux/sched/task.h:167
Inline: True
```
```
In block/blk-ioc.c (ffffffff814d13f6)
Location: include/linux/sched/task.h:167
Inline: True
Inline callers:
  - block/blk-ioc.c:get_task_io_context
  - block/blk-ioc.c:get_task_io_context
  - block/blk-ioc.c:create_task_io_context
  - block/blk-ioc.c:exit_io_context
```
```
In block/ioprio.c (ffffffff814e2989)
Location: include/linux/sched/task.h:167
Inline: True
```
```
In block/blk-cgroup.c (ffffffff814f019e)
Location: include/linux/sched/task.h:167
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_can_attach
```
```
In drivers/tty/tty_io.c (ffffffff81661389)
Location: include/linux/sched/task.h:167
Inline: True
```
```
In net/core/net_namespace.c (ffffffff818f2be9)
Location: include/linux/sched/task.h:167
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_get
  - net/core/net_namespace.c:get_net_ns_by_pid
```
```
In net/core/netprio_cgroup.c (ffffffff81941dfc)
Location: include/linux/sched/task.h:167
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:net_prio_attach
```
```
In net/core/netclassid_cgroup.c (ffffffff819420d1)
Location: include/linux/sched/task.h:167
Inline: True
Inline callers:
  - net/core/netclassid_cgroup.c:write_classid
  - net/core/netclassid_cgroup.c:cgrp_attach
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
In init/main.c (ffffffff8289d2a7)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In kernel/fork.c (ffffffff810a0fda)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/fork.c:unshare_files
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:_do_fork
  - kernel/fork.c:copy_process
  - kernel/fork.c:mm_release
  - kernel/fork.c:get_task_mm
  - kernel/fork.c:get_task_exe_file
```
```
In kernel/cpu.c (ffffffff810a3e2b)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/cpu.c:clear_tasks_mm_cpumask
```
```
In kernel/exit.c (ffffffff810a6595)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:mm_update_next_owner
```
```
In kernel/ptrace.c (ffffffff810adf1e)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:ptrace_may_access
```
```
In kernel/sys.c (ffffffff810ba220)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_auxv
  - kernel/sys.c:do_prlimit
  - kernel/sys.c:__x32_compat_sys_old_getrlimit
  - kernel/sys.c:__ia32_compat_sys_old_getrlimit
  - kernel/sys.c:__ia32_sys_old_getrlimit
  - kernel/sys.c:__x64_sys_old_getrlimit
```
```
In kernel/kthread.c (ffffffff810c9576)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/kthread.c:kthreadd
```
```
In kernel/nsproxy.c (ffffffff810cc929)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/nsproxy.c:switch_task_namespaces
```
```
In kernel/sched/debug.c (ffffffff810fd93c)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
```
```
In kernel/kcmp.c (ffffffff811308b0)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/kcmp.c:get_file_raw_ptr
```
```
In kernel/cgroup/namespace.c (ffffffff811678fd)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:cgroupns_get
```
```
In kernel/cgroup/cpuset.c (ffffffff8116c2b0)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
```
In kernel/utsname.c (ffffffff81171588)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_get
```
```
In kernel/pid_namespace.c (ffffffff81173350)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_for_children_get
```
```
In mm/oom_kill.c (ffffffff81229cc6)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:find_lock_task_mm
```
```
In mm/mmu_context.c (ffffffff8124a308)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - mm/mmu_context.c:unuse_mm
  - mm/mmu_context.c:use_mm
```
```
In mm/mempolicy.c (ffffffff8129cce8)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_put_task_policy
  - mm/mempolicy.c:__mpol_dup
  - mm/mempolicy.c:mempolicy_nodemask_intersects
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
```
```
In fs/exec.c (ffffffff812e576d)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - fs/exec.c:finalize_exec
  - fs/exec.c:__set_task_comm
  - fs/exec.c:__get_task_comm
```
```
In fs/file.c (ffffffff813003da)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - fs/file.c:exit_files
  - fs/file.c:reset_files_struct
  - fs/file.c:get_files_struct
```
```
In fs/namespace.c (ffffffff81301fc5)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - fs/namespace.c:mntns_get
```
```
In fs/fs_struct.c (ffffffff8131b713)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - fs/fs_struct.c:unshare_fs_struct
  - fs/fs_struct.c:exit_fs
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/proc_namespace.c (ffffffff8132c2da)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/io_uring.c (ffffffff81342f88)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In fs/coredump.c (ffffffff813622fc)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/task_mmu.c (ffffffff8136f746)
Location: include/linux/sched/task.h:171
Inline: True
```
```
In fs/proc/base.c (ffffffff81374776)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - fs/proc/base.c:timerslack_ns_show
  - fs/proc/base.c:timerslack_ns_write
  - fs/proc/base.c:task_dump_owner
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
```
```
In fs/proc/array.c (ffffffff813786e8)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In fs/proc/proc_net.c (ffffffff8137f73d)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_task_net
```
```
In fs/hugetlbfs/inode.c (ffffffff814042eb)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
```
```
In ipc/namespace.c (ffffffff8144421d)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - ipc/namespace.c:ipcns_get
```
```
In security/selinux/hooks.c (ffffffff8146242c)
Location: include/linux/sched/task.h:171
Inline: True
```
```
In security/yama/yama_lsm.c (ffffffff814b2edc)
Location: include/linux/sched/task.h:171
Inline: True
```
```
In block/blk-ioc.c (ffffffff814ea7a6)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - block/blk-ioc.c:get_task_io_context
  - block/blk-ioc.c:get_task_io_context
  - block/blk-ioc.c:create_task_io_context
  - block/blk-ioc.c:exit_io_context
```
```
In block/ioprio.c (ffffffff814fbd49)
Location: include/linux/sched/task.h:171
Inline: True
```
```
In block/blk-cgroup.c (ffffffff8150964e)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_can_attach
```
```
In drivers/tty/tty_io.c (ffffffff816839d9)
Location: include/linux/sched/task.h:171
Inline: True
```
```
In net/core/net_namespace.c (ffffffff81924b49)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_get
  - net/core/net_namespace.c:get_net_ns_by_pid
```
```
In net/core/netprio_cgroup.c (ffffffff81976d0c)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:net_prio_attach
```
```
In net/core/netclassid_cgroup.c (ffffffff81976f30)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - net/core/netclassid_cgroup.c:update_classid_task
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
In init/main.c (ffffffff82cc38ef)
Location: include/linux/sched/task.h:178
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In kernel/fork.c (ffffffff810a7e63)
Location: include/linux/sched/task.h:178
Inline: True
Inline callers:
  - kernel/fork.c:unshare_files
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:copy_signal
  - kernel/fork.c:mm_release
  - kernel/fork.c:wait_for_vfork_done
  - kernel/fork.c:get_task_mm
  - kernel/fork.c:get_task_exe_file
```
```
In kernel/cpu.c (ffffffff810aaecc)
Location: include/linux/sched/task.h:178
Inline: True
Inline callers:
  - kernel/cpu.c:clear_tasks_mm_cpumask
```
```
In kernel/exit.c (ffffffff810adffd)
Location: include/linux/sched/task.h:178
Inline: True
Inline callers:
  - kernel/exit.c:exit_mm
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:mm_update_next_owner
```
```
In kernel/ptrace.c (ffffffff810b59fe)
Location: include/linux/sched/task.h:178
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:ptrace_may_access
```
```
In kernel/sys.c (ffffffff810c1ef0)
Location: include/linux/sched/task.h:178
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_auxv
  - kernel/sys.c:do_prlimit
  - kernel/sys.c:__x32_compat_sys_old_getrlimit
  - kernel/sys.c:__ia32_compat_sys_old_getrlimit
  - kernel/sys.c:__ia32_sys_old_getrlimit
  - kernel/sys.c:__x64_sys_old_getrlimit
```
```
In kernel/kthread.c (ffffffff810d10d4)
Location: include/linux/sched/task.h:178
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_unuse_mm
  - kernel/kthread.c:kthread_use_mm
  - kernel/kthread.c:kthreadd
```
```
In kernel/nsproxy.c (ffffffff810d5fd9)
Location: include/linux/sched/task.h:178
Inline: True
Inline callers:
  - kernel/nsproxy.c:validate_nsset
  - kernel/nsproxy.c:switch_task_namespaces
```
```
In kernel/sched/debug.c (ffffffff81105a75)
Location: include/linux/sched/task.h:178
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_show_numa
```
```
In kernel/kcmp.c (ffffffff8113fb71)
Location: include/linux/sched/task.h:178
Inline: True
Inline callers:
  - kernel/kcmp.c:get_file_raw_ptr
```
```
In kernel/time/namespace.c (ffffffff81159e37)
Location: include/linux/sched/task.h:178
Inline: True
Inline callers:
  - kernel/time/namespace.c:timens_for_children_get
  - kernel/time/namespace.c:timens_get
```
```
In kernel/cgroup/namespace.c (ffffffff811791bc)
Location: include/linux/sched/task.h:178
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:cgroupns_get
```
```
In kernel/cgroup/cpuset.c (ffffffff8117e1e0)
Location: include/linux/sched/task.h:178
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
```
In kernel/utsname.c (ffffffff81183417)
Location: include/linux/sched/task.h:178
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_get
```
```
In kernel/pid_namespace.c (ffffffff811854a0)
Location: include/linux/sched/task.h:178
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_for_children_get
```
```
In mm/oom_kill.c (ffffffff81256b36)
Location: include/linux/sched/task.h:178
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/mempolicy.c (ffffffff812d0878)
Location: include/linux/sched/task.h:178
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_put_task_policy
  - mm/mempolicy.c:__mpol_dup
  - mm/mempolicy.c:mempolicy_nodemask_intersects
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
```
```
In fs/exec.c (ffffffff8131d129)
Location: include/linux/sched/task.h:178
Inline: True
Inline callers:
  - fs/exec.c:finalize_exec
  - fs/exec.c:__set_task_comm
  - fs/exec.c:__get_task_comm
  - fs/exec.c:exec_mmap
  - fs/exec.c:kernel_read_file_from_path_initns
  - fs/exec.c:bprm_mm_init
```
```
In fs/file.c (ffffffff81339974)
Location: include/linux/sched/task.h:178
Inline: True
Inline callers:
  - fs/file.c:fget_task
  - fs/file.c:exit_files
  - fs/file.c:reset_files_struct
  - fs/file.c:get_files_struct
```
```
In fs/namespace.c (ffffffff8133afe5)
Location: include/linux/sched/task.h:178
Inline: True
Inline callers:
  - fs/namespace.c:mntns_get
```
```
In fs/fs_struct.c (ffffffff813553d4)
Location: include/linux/sched/task.h:178
Inline: True
Inline callers:
  - fs/fs_struct.c:unshare_fs_struct
  - fs/fs_struct.c:exit_fs
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/proc_namespace.c (ffffffff81365fb4)
Location: include/linux/sched/task.h:178
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/io-wq.c (ffffffff8138a57f)
Location: include/linux/sched/task.h:178
Inline: True
Inline callers:
  - fs/io-wq.c:io_worker_handle_work
  - fs/io-wq.c:__io_worker_unuse
```
```
In fs/coredump.c (ffffffff813a8367)
Location: include/linux/sched/task.h:178
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/task_mmu.c (ffffffff813b7568)
Location: include/linux/sched/task.h:178
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:hold_task_mempolicy
```
```
In fs/proc/base.c (ffffffff813bc766)
Location: include/linux/sched/task.h:178
Inline: True
Inline callers:
  - fs/proc/base.c:timerslack_ns_show
  - fs/proc/base.c:timerslack_ns_write
  - fs/proc/base.c:task_dump_owner
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
```
```
In fs/proc/array.c (ffffffff813c17c9)
Location: include/linux/sched/task.h:178
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In fs/proc/proc_net.c (ffffffff813c9a1d)
Location: include/linux/sched/task.h:178
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_task_net
```
```
In fs/hugetlbfs/inode.c (ffffffff8145212b)
Location: include/linux/sched/task.h:178
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
```
```
In ipc/namespace.c (ffffffff8149517c)
Location: include/linux/sched/task.h:178
Inline: True
Inline callers:
  - ipc/namespace.c:ipcns_get
```
```
In security/selinux/hooks.c (ffffffff814b636c)
Location: include/linux/sched/task.h:178
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committing_creds
```
```
In security/yama/yama_lsm.c (ffffffff8151237c)
Location: include/linux/sched/task.h:178
Inline: True
```
```
In block/blk-ioc.c (ffffffff81549746)
Location: include/linux/sched/task.h:178
Inline: True
Inline callers:
  - block/blk-ioc.c:get_task_io_context
  - block/blk-ioc.c:get_task_io_context
  - block/blk-ioc.c:create_task_io_context
  - block/blk-ioc.c:exit_io_context
```
```
In block/ioprio.c (ffffffff8155b9d5)
Location: include/linux/sched/task.h:178
Inline: True
```
```
In block/blk-cgroup.c (ffffffff8156a8ee)
Location: include/linux/sched/task.h:178
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_can_attach
```
```
In drivers/tty/tty_io.c (ffffffff8173520a)
Location: include/linux/sched/task.h:178
Inline: True
```
```
In net/core/net_namespace.c (ffffffff819f8dfd)
Location: include/linux/sched/task.h:178
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_get
  - net/core/net_namespace.c:get_net_ns_by_pid
```
```
In net/core/netprio_cgroup.c (ffffffff81a4ba86)
Location: include/linux/sched/task.h:178
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:net_prio_attach
```
```
In net/core/netclassid_cgroup.c (ffffffff81a4bce0)
Location: include/linux/sched/task.h:178
Inline: True
Inline callers:
  - net/core/netclassid_cgroup.c:update_classid_task
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
In init/main.c (ffffffff82faf9fc)
Location: include/linux/sched/task.h:169
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In kernel/fork.c (ffffffff810a3bd7)
Location: include/linux/sched/task.h:169
Inline: True
Inline callers:
  - kernel/fork.c:unshare_files
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:copy_signal
  - kernel/fork.c:mm_release
  - kernel/fork.c:wait_for_vfork_done
  - kernel/fork.c:get_task_mm
  - kernel/fork.c:get_task_exe_file
```
```
In kernel/cpu.c (ffffffff810a675c)
Location: include/linux/sched/task.h:169
Inline: True
Inline callers:
  - kernel/cpu.c:clear_tasks_mm_cpumask
```
```
In kernel/exit.c (ffffffff810a9699)
Location: include/linux/sched/task.h:169
Inline: True
Inline callers:
  - kernel/exit.c:exit_mm
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:mm_update_next_owner
```
```
In kernel/ptrace.c (ffffffff810b0bee)
Location: include/linux/sched/task.h:169
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:ptrace_may_access
```
```
In kernel/sys.c (ffffffff810bd1e0)
Location: include/linux/sched/task.h:169
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_auxv
  - kernel/sys.c:do_prlimit
  - kernel/sys.c:__x32_compat_sys_old_getrlimit
  - kernel/sys.c:__ia32_compat_sys_old_getrlimit
  - kernel/sys.c:__ia32_sys_old_getrlimit
  - kernel/sys.c:__x64_sys_old_getrlimit
```
```
In kernel/kthread.c (ffffffff810cb688)
Location: include/linux/sched/task.h:169
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_unuse_mm
  - kernel/kthread.c:kthread_use_mm
  - kernel/kthread.c:kthreadd
```
```
In kernel/nsproxy.c (ffffffff810d0b07)
Location: include/linux/sched/task.h:169
Inline: True
Inline callers:
  - kernel/nsproxy.c:validate_nsset
  - kernel/nsproxy.c:switch_task_namespaces
```
```
In kernel/sched/debug.c (ffffffff811040c5)
Location: include/linux/sched/task.h:169
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_show_numa
```
```
In kernel/time/namespace.c (ffffffff81155e1d)
Location: include/linux/sched/task.h:169
Inline: True
Inline callers:
  - kernel/time/namespace.c:timens_for_children_get
  - kernel/time/namespace.c:timens_get
```
```
In kernel/cgroup/namespace.c (ffffffff81175ee2)
Location: include/linux/sched/task.h:169
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:cgroupns_get
```
```
In kernel/cgroup/cpuset.c (ffffffff8117b050)
Location: include/linux/sched/task.h:169
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
```
In kernel/utsname.c (ffffffff81180323)
Location: include/linux/sched/task.h:169
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_get
```
```
In kernel/pid_namespace.c (ffffffff811825ac)
Location: include/linux/sched/task.h:169
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_for_children_get
```
```
In mm/oom_kill.c (ffffffff81261746)
Location: include/linux/sched/task.h:169
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:find_lock_task_mm
```
```
In mm/mempolicy.c (ffffffff812dc398)
Location: include/linux/sched/task.h:169
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_put_task_policy
  - mm/mempolicy.c:__mpol_dup
  - mm/mempolicy.c:mempolicy_nodemask_intersects
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
```
```
In fs/exec.c (ffffffff81328b3c)
Location: include/linux/sched/task.h:169
Inline: True
Inline callers:
  - fs/exec.c:alloc_bprm
  - fs/exec.c:finalize_exec
  - fs/exec.c:__set_task_comm
  - fs/exec.c:__get_task_comm
  - fs/exec.c:exec_mmap
```
```
In fs/file.c (ffffffff813456a0)
Location: include/linux/sched/task.h:169
Inline: True
Inline callers:
  - fs/file.c:task_lookup_next_fd_rcu
  - fs/file.c:task_lookup_fd_rcu
  - fs/file.c:fget_task
  - fs/file.c:__close_range
  - fs/file.c:exit_files
```
```
In fs/namespace.c (ffffffff8134710d)
Location: include/linux/sched/task.h:169
Inline: True
Inline callers:
  - fs/namespace.c:mntns_get
```
```
In fs/fs_struct.c (ffffffff81361cf4)
Location: include/linux/sched/task.h:169
Inline: True
Inline callers:
  - fs/fs_struct.c:unshare_fs_struct
  - fs/fs_struct.c:exit_fs
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/kernel_read_file.c (ffffffff81365f53)
Location: include/linux/sched/task.h:169
Inline: True
Inline callers:
  - fs/kernel_read_file.c:kernel_read_file_from_path_initns
```
```
In fs/proc_namespace.c (ffffffff81372ea6)
Location: include/linux/sched/task.h:169
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/io_uring.c (ffffffff81399de8)
Location: include/linux/sched/task.h:169
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread_drop_mm_files
```
```
In fs/io-wq.c (ffffffff8139bce5)
Location: include/linux/sched/task.h:169
Inline: True
Inline callers:
  - fs/io-wq.c:io_impersonate_work
  - fs/io-wq.c:__io_worker_unuse
```
```
In fs/coredump.c (ffffffff813b93d8)
Location: include/linux/sched/task.h:169
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/task_mmu.c (ffffffff813c8e58)
Location: include/linux/sched/task.h:169
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:hold_task_mempolicy
```
```
In fs/proc/base.c (ffffffff813ce203)
Location: include/linux/sched/task.h:169
Inline: True
Inline callers:
  - fs/proc/base.c:timerslack_ns_show
  - fs/proc/base.c:timerslack_ns_write
  - fs/proc/base.c:task_dump_owner
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
```
```
In fs/proc/array.c (ffffffff813d36bc)
Location: include/linux/sched/task.h:169
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In fs/proc/fd.c (ffffffff813d5c2d)
Location: include/linux/sched/task.h:169
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In fs/proc/proc_net.c (ffffffff813db693)
Location: include/linux/sched/task.h:169
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_task_net
```
```
In fs/hugetlbfs/inode.c (ffffffff8146e66b)
Location: include/linux/sched/task.h:169
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
```
```
In ipc/namespace.c (ffffffff814b2c78)
Location: include/linux/sched/task.h:169
Inline: True
Inline callers:
  - ipc/namespace.c:ipcns_get
```
```
In security/selinux/hooks.c (ffffffff814d404c)
Location: include/linux/sched/task.h:169
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committing_creds
```
```
In security/yama/yama_lsm.c (ffffffff8152f21c)
Location: include/linux/sched/task.h:169
Inline: True
```
```
In block/blk-ioc.c (ffffffff81565576)
Location: include/linux/sched/task.h:169
Inline: True
Inline callers:
  - block/blk-ioc.c:get_task_io_context
  - block/blk-ioc.c:get_task_io_context
  - block/blk-ioc.c:create_task_io_context
  - block/blk-ioc.c:exit_io_context
```
```
In block/ioprio.c (ffffffff81577b35)
Location: include/linux/sched/task.h:169
Inline: True
```
```
In block/blk-cgroup.c (ffffffff8158533e)
Location: include/linux/sched/task.h:169
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_can_attach
```
```
In drivers/tty/tty_io.c (ffffffff81751cd4)
Location: include/linux/sched/task.h:169
Inline: True
```
```
In net/core/net_namespace.c (ffffffff819f88d3)
Location: include/linux/sched/task.h:169
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_get
  - net/core/net_namespace.c:get_net_ns_by_pid
```
```
In net/core/netprio_cgroup.c (ffffffff81a516d6)
Location: include/linux/sched/task.h:169
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:net_prio_attach
```
```
In net/core/netclassid_cgroup.c (ffffffff81a51900)
Location: include/linux/sched/task.h:169
Inline: True
Inline callers:
  - net/core/netclassid_cgroup.c:update_classid_task
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
In init/main.c (ffffffff831b9a25)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In kernel/fork.c (ffffffff810a4827)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/fork.c:unshare_files
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:kernel_clone
  - kernel/fork.c:copy_signal
  - kernel/fork.c:mm_release
  - kernel/fork.c:get_task_mm
  - kernel/fork.c:get_task_exe_file
```
```
In kernel/cpu.c (ffffffff810a77cc)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/cpu.c:clear_tasks_mm_cpumask
```
```
In kernel/exit.c (ffffffff810aa6d9)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/exit.c:exit_mm
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:mm_update_next_owner
```
```
In kernel/ptrace.c (ffffffff810b218e)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:ptrace_may_access
```
```
In kernel/sys.c (ffffffff810bf598)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_auxv
  - kernel/sys.c:do_prlimit
  - kernel/sys.c:__x32_compat_sys_old_getrlimit
  - kernel/sys.c:__ia32_compat_sys_old_getrlimit
  - kernel/sys.c:__ia32_sys_old_getrlimit
  - kernel/sys.c:__x64_sys_old_getrlimit
```
```
In kernel/kthread.c (ffffffff810cd3e6)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_unuse_mm
  - kernel/kthread.c:kthread_use_mm
  - kernel/kthread.c:kthreadd
```
```
In kernel/nsproxy.c (ffffffff810d26e7)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/nsproxy.c:validate_nsset
  - kernel/nsproxy.c:switch_task_namespaces
```
```
In kernel/sched/debug.c (ffffffff81106de5)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_show_numa
```
```
In kernel/time/namespace.c (ffffffff8115702d)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/time/namespace.c:timens_for_children_get
  - kernel/time/namespace.c:timens_get
```
```
In kernel/cgroup/namespace.c (ffffffff81176b42)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:cgroupns_get
```
```
In kernel/cgroup/cpuset.c (ffffffff8117c8d0)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
```
In kernel/utsname.c (ffffffff81181233)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_get
```
```
In kernel/pid_namespace.c (ffffffff811836fc)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_for_children_get
```
```
In mm/oom_kill.c (ffffffff81265f76)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:find_lock_task_mm
```
```
In mm/mempolicy.c (ffffffff812e3c28)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_put_task_policy
  - mm/mempolicy.c:__mpol_dup
  - mm/mempolicy.c:mempolicy_nodemask_intersects
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
```
```
In fs/exec.c (ffffffff8132e99c)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - fs/exec.c:alloc_bprm
  - fs/exec.c:finalize_exec
  - fs/exec.c:__set_task_comm
  - fs/exec.c:__get_task_comm
  - fs/exec.c:exec_mmap
```
```
In fs/file.c (ffffffff8134ba40)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - fs/file.c:task_lookup_next_fd_rcu
  - fs/file.c:task_lookup_fd_rcu
  - fs/file.c:fget_task
  - fs/file.c:__close_range
  - fs/file.c:exit_files
```
```
In fs/namespace.c (ffffffff8134d8bd)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - fs/namespace.c:mntns_get
```
```
In fs/fs_struct.c (ffffffff813687d4)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - fs/fs_struct.c:unshare_fs_struct
  - fs/fs_struct.c:exit_fs
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/kernel_read_file.c (ffffffff8136c990)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - fs/kernel_read_file.c:kernel_read_file_from_path_initns
```
```
In fs/proc_namespace.c (ffffffff8137982f)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/coredump.c (ffffffff813c02cb)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/task_mmu.c (ffffffff813cff28)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:hold_task_mempolicy
```
```
In fs/proc/base.c (ffffffff813d60d3)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - fs/proc/base.c:timerslack_ns_show
  - fs/proc/base.c:timerslack_ns_write
  - fs/proc/base.c:task_dump_owner
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
```
```
In fs/proc/array.c (ffffffff813da4ec)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In fs/proc/fd.c (ffffffff813dcc3d)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In fs/proc/proc_net.c (ffffffff813e25c3)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_task_net
```
```
In fs/hugetlbfs/inode.c (ffffffff81473cab)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
```
```
In ipc/namespace.c (ffffffff814b8828)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - ipc/namespace.c:ipcns_get
```
```
In security/selinux/hooks.c (ffffffff814da5f8)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committing_creds
```
```
In security/yama/yama_lsm.c (ffffffff815351ac)
Location: include/linux/sched/task.h:171
Inline: True
```
```
In block/blk-ioc.c (ffffffff8156dbe6)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - block/blk-ioc.c:get_task_io_context
  - block/blk-ioc.c:get_task_io_context
  - block/blk-ioc.c:create_task_io_context
  - block/blk-ioc.c:exit_io_context
```
```
In block/ioprio.c (ffffffff8157f875)
Location: include/linux/sched/task.h:171
Inline: True
```
```
In block/blk-cgroup.c (ffffffff8158beec)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_can_attach
```
```
In drivers/tty/tty_io.c (ffffffff81735920)
Location: include/linux/sched/task.h:171
Inline: True
```
```
In net/core/net_namespace.c (ffffffff819df103)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_get
  - net/core/net_namespace.c:get_net_ns_by_pid
```
```
In net/core/netprio_cgroup.c (ffffffff81a36f76)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:net_prio_attach
```
```
In net/core/netclassid_cgroup.c (ffffffff81a37296)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - net/core/netclassid_cgroup.c:write_classid
  - net/core/netclassid_cgroup.c:cgrp_attach
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
In init/main.c (ffffffff83299e01)
Location: include/linux/sched/task.h:172
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In kernel/fork.c (ffffffff810b6047)
Location: include/linux/sched/task.h:172
Inline: True
Inline callers:
  - kernel/fork.c:unshare_files
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:kernel_clone
  - kernel/fork.c:copy_signal
  - kernel/fork.c:mm_release
  - kernel/fork.c:get_task_mm
  - kernel/fork.c:get_task_exe_file
```
```
In kernel/cpu.c (ffffffff810b921c)
Location: include/linux/sched/task.h:172
Inline: True
Inline callers:
  - kernel/cpu.c:clear_tasks_mm_cpumask
```
```
In kernel/exit.c (ffffffff810bc204)
Location: include/linux/sched/task.h:172
Inline: True
Inline callers:
  - kernel/exit.c:exit_mm
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:mm_update_next_owner
```
```
In kernel/ptrace.c (ffffffff810c3f9f)
Location: include/linux/sched/task.h:172
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:ptrace_may_access
```
```
In kernel/sys.c (ffffffff810d2018)
Location: include/linux/sched/task.h:172
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_auxv
  - kernel/sys.c:do_prlimit
  - kernel/sys.c:__x64_compat_sys_old_getrlimit
  - kernel/sys.c:__ia32_compat_sys_old_getrlimit
  - kernel/sys.c:__ia32_sys_old_getrlimit
  - kernel/sys.c:__x64_sys_old_getrlimit
```
```
In kernel/kthread.c (ffffffff810e05d6)
Location: include/linux/sched/task.h:172
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_unuse_mm
  - kernel/kthread.c:kthread_use_mm
  - kernel/kthread.c:kthreadd
```
```
In kernel/nsproxy.c (ffffffff810e5827)
Location: include/linux/sched/task.h:172
Inline: True
Inline callers:
  - kernel/nsproxy.c:validate_nsset
  - kernel/nsproxy.c:switch_task_namespaces
```
```
In kernel/sched/debug.c (ffffffff811249ca)
Location: include/linux/sched/task.h:172
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_show_numa
```
```
In kernel/time/namespace.c (ffffffff8117be7d)
Location: include/linux/sched/task.h:172
Inline: True
Inline callers:
  - kernel/time/namespace.c:timens_for_children_get
  - kernel/time/namespace.c:timens_get
```
```
In kernel/cgroup/namespace.c (ffffffff8119e3c2)
Location: include/linux/sched/task.h:172
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:cgroupns_get
```
```
In kernel/cgroup/cpuset.c (ffffffff811a4460)
Location: include/linux/sched/task.h:172
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
```
In kernel/utsname.c (ffffffff811a91a3)
Location: include/linux/sched/task.h:172
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_get
```
```
In kernel/pid_namespace.c (ffffffff811ab7dc)
Location: include/linux/sched/task.h:172
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_for_children_get
```
```
In mm/oom_kill.c (ffffffff812a31ff)
Location: include/linux/sched/task.h:172
Inline: True
Inline callers:
  - mm/oom_kill.c:__do_sys_process_mrelease
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:find_lock_task_mm
```
```
In mm/mempolicy.c (ffffffff8132af10)
Location: include/linux/sched/task.h:172
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_put_task_policy
  - mm/mempolicy.c:__mpol_dup
  - mm/mempolicy.c:mempolicy_in_oom_domain
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
```
```
In fs/exec.c (ffffffff8137c1ac)
Location: include/linux/sched/task.h:172
Inline: True
Inline callers:
  - fs/exec.c:alloc_bprm
  - fs/exec.c:finalize_exec
  - fs/exec.c:__set_task_comm
  - fs/exec.c:__get_task_comm
  - fs/exec.c:exec_mmap
```
```
In fs/file.c (ffffffff8139987c)
Location: include/linux/sched/task.h:172
Inline: True
Inline callers:
  - fs/file.c:task_lookup_next_fd_rcu
  - fs/file.c:task_lookup_fd_rcu
  - fs/file.c:fget_task
  - fs/file.c:__close_range
  - fs/file.c:exit_files
```
```
In fs/namespace.c (ffffffff8139b88d)
Location: include/linux/sched/task.h:172
Inline: True
Inline callers:
  - fs/namespace.c:mntns_get
```
```
In fs/fs_struct.c (ffffffff813b74d4)
Location: include/linux/sched/task.h:172
Inline: True
Inline callers:
  - fs/fs_struct.c:unshare_fs_struct
  - fs/fs_struct.c:exit_fs
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/kernel_read_file.c (ffffffff813bb660)
Location: include/linux/sched/task.h:172
Inline: True
Inline callers:
  - fs/kernel_read_file.c:kernel_read_file_from_path_initns
```
```
In fs/proc_namespace.c (ffffffff813c638f)
Location: include/linux/sched/task.h:172
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/coredump.c (ffffffff814100fb)
Location: include/linux/sched/task.h:172
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/task_mmu.c (ffffffff81421548)
Location: include/linux/sched/task.h:172
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:hold_task_mempolicy
```
```
In fs/proc/base.c (ffffffff814279a3)
Location: include/linux/sched/task.h:172
Inline: True
Inline callers:
  - fs/proc/base.c:timerslack_ns_show
  - fs/proc/base.c:timerslack_ns_write
  - fs/proc/base.c:task_dump_owner
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
```
```
In fs/proc/array.c (ffffffff8142bc1c)
Location: include/linux/sched/task.h:172
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In fs/proc/fd.c (ffffffff8142e31d)
Location: include/linux/sched/task.h:172
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In fs/proc/proc_net.c (ffffffff814340d3)
Location: include/linux/sched/task.h:172
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_task_net
```
```
In fs/hugetlbfs/inode.c (ffffffff814ca905)
Location: include/linux/sched/task.h:172
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
```
```
In ipc/shm.c (ffffffff8150b783)
Location: include/linux/sched/task.h:172
Inline: True
Inline callers:
  - ipc/shm.c:newseg
  - ipc/shm.c:exit_shm
  - ipc/shm.c:exit_shm
  - ipc/shm.c:exit_shm
  - ipc/shm.c:shm_destroy
```
```
In ipc/namespace.c (ffffffff81511058)
Location: include/linux/sched/task.h:172
Inline: True
Inline callers:
  - ipc/namespace.c:ipcns_get
```
```
In security/selinux/hooks.c (ffffffff815334f8)
Location: include/linux/sched/task.h:172
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committing_creds
```
```
In security/yama/yama_lsm.c (ffffffff815936bc)
Location: include/linux/sched/task.h:172
Inline: True
```
```
In block/blk-ioc.c (ffffffff815d21dc)
Location: include/linux/sched/task.h:172
Inline: True
Inline callers:
  - block/blk-ioc.c:get_task_io_context
  - block/blk-ioc.c:get_task_io_context
  - block/blk-ioc.c:create_task_io_context
  - block/blk-ioc.c:exit_io_context
```
```
In block/ioprio.c (ffffffff815e4b15)
Location: include/linux/sched/task.h:172
Inline: True
```
```
In drivers/tty/tty_io.c (ffffffff817b62e0)
Location: include/linux/sched/task.h:172
Inline: True
```
```
In net/core/net_namespace.c (ffffffff81a8f4e3)
Location: include/linux/sched/task.h:172
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_get
  - net/core/net_namespace.c:get_net_ns_by_pid
```
```
In net/core/netprio_cgroup.c (ffffffff81aec916)
Location: include/linux/sched/task.h:172
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:net_prio_attach
```
```
In net/core/netclassid_cgroup.c (ffffffff81aecdb0)
Location: include/linux/sched/task.h:172
Inline: True
Inline callers:
  - net/core/netclassid_cgroup.c:update_classid_task
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
In init/main.c (ffffffff81e43852)
Location: include/linux/sched/task.h:177
Inline: True
Inline callers:
  - init/main.c:set_mems_allowed
```
```
In kernel/fork.c (ffffffff810cc571)
Location: include/linux/sched/task.h:177
Inline: True
Inline callers:
  - kernel/fork.c:unshare_files
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:kernel_clone
  - kernel/fork.c:copy_signal
  - kernel/fork.c:mm_release
  - kernel/fork.c:mm_access
  - kernel/fork.c:get_task_exe_file
```
```
In kernel/cpu.c (ffffffff810cfbd1)
Location: include/linux/sched/task.h:177
Inline: True
Inline callers:
  - kernel/cpu.c:clear_tasks_mm_cpumask
```
```
In kernel/exit.c (ffffffff810d2c92)
Location: include/linux/sched/task.h:177
Inline: True
Inline callers:
  - kernel/exit.c:exit_mm
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:mm_update_next_owner
```
```
In kernel/ptrace.c (ffffffff810db5b0)
Location: include/linux/sched/task.h:177
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:ptrace_may_access
```
```
In kernel/sys.c (ffffffff810e8728)
Location: include/linux/sched/task.h:177
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_auxv
  - kernel/sys.c:__ia32_compat_sys_old_getrlimit
  - kernel/sys.c:__ia32_sys_old_getrlimit
  - kernel/sys.c:__x64_sys_old_getrlimit
  - kernel/sys.c:__ia32_compat_sys_getrlimit
  - kernel/sys.c:__ia32_sys_getrlimit
  - kernel/sys.c:__x64_sys_getrlimit
```
```
In kernel/kthread.c (ffffffff810f9a2a)
Location: include/linux/sched/task.h:177
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_unuse_mm
  - kernel/kthread.c:kthread_use_mm
  - kernel/kthread.c:set_mems_allowed
```
```
In kernel/nsproxy.c (ffffffff810ff643)
Location: include/linux/sched/task.h:177
Inline: True
Inline callers:
  - kernel/nsproxy.c:validate_nsset
  - kernel/nsproxy.c:switch_task_namespaces
```
```
In kernel/time/namespace.c (ffffffff811b1f9c)
Location: include/linux/sched/task.h:177
Inline: True
Inline callers:
  - kernel/time/namespace.c:proc_timens_set_offset
  - kernel/time/namespace.c:proc_timens_show_offsets
  - kernel/time/namespace.c:timens_get
```
```
In kernel/cgroup/namespace.c (ffffffff811ce6cc)
Location: include/linux/sched/task.h:177
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:cgroupns_get
```
```
In kernel/cgroup/cpuset.c (ffffffff811d3f0e)
Location: include/linux/sched/task.h:177
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
```
In kernel/utsname.c (ffffffff811da5dd)
Location: include/linux/sched/task.h:177
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_get
```
```
In kernel/pid_namespace.c (ffffffff811dce86)
Location: include/linux/sched/task.h:177
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_for_children_get
```
```
In mm/oom_kill.c (ffffffff812fb120)
Location: include/linux/sched/task.h:177
Inline: True
Inline callers:
  - mm/oom_kill.c:__do_sys_process_mrelease
  - mm/oom_kill.c:__do_sys_process_mrelease
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:oom_badness
  - mm/oom_kill.c:oom_badness
  - mm/oom_kill.c:oom_badness
```
```
In mm/mempolicy.c (ffffffff8139a920)
Location: include/linux/sched/task.h:177
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_put_task_policy
  - mm/mempolicy.c:__mpol_dup
  - mm/mempolicy.c:mempolicy_in_oom_domain
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
```
```
In fs/exec.c (ffffffff813fafb2)
Location: include/linux/sched/task.h:177
Inline: True
Inline callers:
  - fs/exec.c:alloc_bprm
  - fs/exec.c:finalize_exec
  - fs/exec.c:__set_task_comm
  - fs/exec.c:__get_task_comm
  - fs/exec.c:exec_mmap
```
```
In fs/file.c (ffffffff8141c23a)
Location: include/linux/sched/task.h:177
Inline: True
Inline callers:
  - fs/file.c:task_lookup_next_fd_rcu
  - fs/file.c:task_lookup_fd_rcu
  - fs/file.c:fget_task
  - fs/file.c:__close_range
  - fs/file.c:exit_files
```
```
In fs/namespace.c (ffffffff8141e687)
Location: include/linux/sched/task.h:177
Inline: True
Inline callers:
  - fs/namespace.c:mntns_get
```
```
In fs/fs_struct.c (ffffffff8143cb8f)
Location: include/linux/sched/task.h:177
Inline: True
Inline callers:
  - fs/fs_struct.c:unshare_fs_struct
  - fs/fs_struct.c:exit_fs
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/kernel_read_file.c (ffffffff814415a7)
Location: include/linux/sched/task.h:177
Inline: True
Inline callers:
  - fs/kernel_read_file.c:kernel_read_file_from_path_initns
```
```
In fs/proc_namespace.c (ffffffff8144cc0c)
Location: include/linux/sched/task.h:177
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/coredump.c (ffffffff81485aa2)
Location: include/linux/sched/task.h:177
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/task_mmu.c (ffffffff81497a08)
Location: include/linux/sched/task.h:177
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:hold_task_mempolicy
```
```
In fs/proc/base.c (ffffffff8149ff94)
Location: include/linux/sched/task.h:177
Inline: True
Inline callers:
  - fs/proc/base.c:timerslack_ns_show
  - fs/proc/base.c:timerslack_ns_write
  - fs/proc/base.c:task_dump_owner
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
```
```
In fs/proc/array.c (ffffffff814a5886)
Location: include/linux/sched/task.h:177
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In fs/proc/fd.c (ffffffff814a7a44)
Location: include/linux/sched/task.h:177
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In fs/proc/proc_net.c (ffffffff814ae155)
Location: include/linux/sched/task.h:177
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_task_net
```
```
In ipc/shm.c (ffffffff8159d9e4)
Location: include/linux/sched/task.h:177
Inline: True
Inline callers:
  - ipc/shm.c:newseg
  - ipc/shm.c:exit_shm
  - ipc/shm.c:exit_shm
  - ipc/shm.c:exit_shm
  - ipc/shm.c:shm_destroy
```
```
In ipc/namespace.c (ffffffff815a3602)
Location: include/linux/sched/task.h:177
Inline: True
Inline callers:
  - ipc/namespace.c:ipcns_get
```
```
In security/selinux/hooks.c (ffffffff815c4da3)
Location: include/linux/sched/task.h:177
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committing_creds
```
```
In security/yama/yama_lsm.c (ffffffff8163599b)
Location: include/linux/sched/task.h:177
Inline: True
```
```
In block/blk-ioc.c (ffffffff8167de1d)
Location: include/linux/sched/task.h:177
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_find_get_icq
  - block/blk-ioc.c:set_task_ioprio
  - block/blk-ioc.c:set_task_ioprio
  - block/blk-ioc.c:exit_io_context
```
```
In block/ioprio.c (ffffffff81693c08)
Location: include/linux/sched/task.h:177
Inline: True
Inline callers:
  - block/ioprio.c:__do_sys_ioprio_get
  - block/ioprio.c:__do_sys_ioprio_get
  - block/ioprio.c:__do_sys_ioprio_get
```
```
In drivers/tty/tty_io.c (ffffffff818f41b0)
Location: include/linux/sched/task.h:177
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:__do_SAK
```
```
In net/core/net_namespace.c (ffffffff81c0519d)
Location: include/linux/sched/task.h:177
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_get
  - net/core/net_namespace.c:get_net_ns_by_pid
```
```
In net/core/netprio_cgroup.c (ffffffff81c6f42e)
Location: include/linux/sched/task.h:177
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:net_prio_attach
```
```
In net/core/netclassid_cgroup.c (ffffffff81c6f9b7)
Location: include/linux/sched/task.h:177
Inline: True
Inline callers:
  - net/core/netclassid_cgroup.c:write_classid
  - net/core/netclassid_cgroup.c:cgrp_attach
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
In init/main.c (ffffffff81000f55)
Location: include/linux/sched/task.h:180
Inline: True
Inline callers:
  - init/main.c:set_mems_allowed
```
```
In kernel/fork.c (ffffffff810e9c51)
Location: include/linux/sched/task.h:180
Inline: True
Inline callers:
  - kernel/fork.c:unshare_files
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:kernel_clone
  - kernel/fork.c:kernel_clone
  - kernel/fork.c:copy_signal
  - kernel/fork.c:mm_release
  - kernel/fork.c:mm_access
  - kernel/fork.c:get_task_exe_file
```
```
In kernel/cpu.c (ffffffff810edfe1)
Location: include/linux/sched/task.h:180
Inline: True
Inline callers:
  - kernel/cpu.c:clear_tasks_mm_cpumask
```
```
In kernel/exit.c (ffffffff810f179a)
Location: include/linux/sched/task.h:180
Inline: True
Inline callers:
  - kernel/exit.c:exit_mm
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:mm_update_next_owner
```
```
In kernel/ptrace.c (ffffffff810fb670)
Location: include/linux/sched/task.h:180
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:ptrace_may_access
```
```
In kernel/sys.c (ffffffff81109ab8)
Location: include/linux/sched/task.h:180
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_auxv
  - kernel/sys.c:__ia32_compat_sys_old_getrlimit
  - kernel/sys.c:__ia32_sys_old_getrlimit
  - kernel/sys.c:__x64_sys_old_getrlimit
  - kernel/sys.c:__ia32_compat_sys_getrlimit
  - kernel/sys.c:__ia32_sys_getrlimit
  - kernel/sys.c:__x64_sys_getrlimit
```
```
In kernel/kthread.c (ffffffff8111c792)
Location: include/linux/sched/task.h:180
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_unuse_mm
  - kernel/kthread.c:kthread_use_mm
  - kernel/kthread.c:set_mems_allowed
```
```
In kernel/nsproxy.c (ffffffff81124373)
Location: include/linux/sched/task.h:180
Inline: True
Inline callers:
  - kernel/nsproxy.c:validate_nsset
  - kernel/nsproxy.c:switch_task_namespaces
```
```
In kernel/time/namespace.c (ffffffff811f2dcc)
Location: include/linux/sched/task.h:180
Inline: True
Inline callers:
  - kernel/time/namespace.c:proc_timens_set_offset
  - kernel/time/namespace.c:proc_timens_show_offsets
  - kernel/time/namespace.c:timens_get
```
```
In kernel/cgroup/namespace.c (ffffffff81211f2c)
Location: include/linux/sched/task.h:180
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:cgroupns_get
```
```
In kernel/cgroup/cpuset.c (ffffffff81217cce)
Location: include/linux/sched/task.h:180
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
```
In kernel/utsname.c (ffffffff8121fbad)
Location: include/linux/sched/task.h:180
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_get
```
```
In kernel/pid_namespace.c (ffffffff81222816)
Location: include/linux/sched/task.h:180
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_for_children_get
```
```
In mm/oom_kill.c (ffffffff813644e7)
Location: include/linux/sched/task.h:180
Inline: True
Inline callers:
  - mm/oom_kill.c:__do_sys_process_mrelease
  - mm/oom_kill.c:__do_sys_process_mrelease
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:oom_badness
  - mm/oom_kill.c:oom_badness
  - mm/oom_kill.c:oom_badness
```
```
In mm/mempolicy.c (ffffffff8141a960)
Location: include/linux/sched/task.h:180
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_put_task_policy
  - mm/mempolicy.c:__mpol_dup
  - mm/mempolicy.c:mempolicy_in_oom_domain
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
```
```
In mm/memcontrol.c (ffffffff8144ebe2)
Location: include/linux/sched/task.h:180
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_attach
```
```
In fs/exec.c (ffffffff814848b2)
Location: include/linux/sched/task.h:180
Inline: True
Inline callers:
  - fs/exec.c:alloc_bprm
  - fs/exec.c:finalize_exec
  - fs/exec.c:__set_task_comm
  - fs/exec.c:__get_task_comm
  - fs/exec.c:exec_mmap
```
```
In fs/file.c (ffffffff814a6dca)
Location: include/linux/sched/task.h:180
Inline: True
Inline callers:
  - fs/file.c:task_lookup_next_fd_rcu
  - fs/file.c:task_lookup_fd_rcu
  - fs/file.c:fget_task
  - fs/file.c:__close_range
  - fs/file.c:exit_files
```
```
In fs/namespace.c (ffffffff814aaf67)
Location: include/linux/sched/task.h:180
Inline: True
Inline callers:
  - fs/namespace.c:mntns_get
```
```
In fs/fs_struct.c (ffffffff814cb2ef)
Location: include/linux/sched/task.h:180
Inline: True
Inline callers:
  - fs/fs_struct.c:unshare_fs_struct
  - fs/fs_struct.c:exit_fs
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/kernel_read_file.c (ffffffff814d0537)
Location: include/linux/sched/task.h:180
Inline: True
Inline callers:
  - fs/kernel_read_file.c:kernel_read_file_from_path_initns
```
```
In fs/proc_namespace.c (ffffffff814db17c)
Location: include/linux/sched/task.h:180
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/coredump.c (ffffffff8151935f)
Location: include/linux/sched/task.h:180
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/task_mmu.c (ffffffff8152b9b8)
Location: include/linux/sched/task.h:180
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:hold_task_mempolicy
```
```
In fs/proc/base.c (ffffffff81534e64)
Location: include/linux/sched/task.h:180
Inline: True
Inline callers:
  - fs/proc/base.c:timerslack_ns_show
  - fs/proc/base.c:timerslack_ns_write
  - fs/proc/base.c:task_dump_owner
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
```
```
In fs/proc/array.c (ffffffff8153ae96)
Location: include/linux/sched/task.h:180
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In fs/proc/fd.c (ffffffff8153d6e7)
Location: include/linux/sched/task.h:180
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_count
  - fs/proc/fd.c:seq_show
```
```
In fs/proc/proc_net.c (ffffffff81544725)
Location: include/linux/sched/task.h:180
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_task_net
```
```
In ipc/shm.c (ffffffff81646fb4)
Location: include/linux/sched/task.h:180
Inline: True
Inline callers:
  - ipc/shm.c:newseg
  - ipc/shm.c:exit_shm
  - ipc/shm.c:exit_shm
  - ipc/shm.c:exit_shm
  - ipc/shm.c:shm_destroy
```
```
In ipc/namespace.c (ffffffff8164d222)
Location: include/linux/sched/task.h:180
Inline: True
Inline callers:
  - ipc/namespace.c:ipcns_get
```
```
In security/selinux/hooks.c (ffffffff816718a3)
Location: include/linux/sched/task.h:180
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committing_creds
```
```
In security/yama/yama_lsm.c (ffffffff816ec69b)
Location: include/linux/sched/task.h:180
Inline: True
```
```
In block/blk-ioc.c (ffffffff8173aa6d)
Location: include/linux/sched/task.h:180
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_find_get_icq
  - block/blk-ioc.c:set_task_ioprio
  - block/blk-ioc.c:set_task_ioprio
  - block/blk-ioc.c:exit_io_context
```
```
In block/ioprio.c (ffffffff81752c29)
Location: include/linux/sched/task.h:180
Inline: True
Inline callers:
  - block/ioprio.c:__do_sys_ioprio_get
  - block/ioprio.c:__do_sys_ioprio_get
  - block/ioprio.c:__do_sys_ioprio_get
```
```
In drivers/tty/tty_io.c (ffffffff81a4c92f)
Location: include/linux/sched/task.h:180
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:__do_SAK
```
```
In net/core/net_namespace.c (ffffffff81db4a1d)
Location: include/linux/sched/task.h:180
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_get
  - net/core/net_namespace.c:get_net_ns_by_pid
```
```
In net/core/netprio_cgroup.c (ffffffff81e2723e)
Location: include/linux/sched/task.h:180
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:net_prio_attach
```
```
In net/core/netclassid_cgroup.c (ffffffff81e27877)
Location: include/linux/sched/task.h:180
Inline: True
Inline callers:
  - net/core/netclassid_cgroup.c:write_classid
  - net/core/netclassid_cgroup.c:cgrp_attach
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
In init/main.c (ffffffff81000cb5)
Location: include/linux/sched/task.h:188
Inline: True
Inline callers:
  - init/main.c:set_mems_allowed
```
```
In kernel/fork.c (ffffffff810f5851)
Location: include/linux/sched/task.h:188
Inline: True
Inline callers:
  - kernel/fork.c:unshare_files
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:kernel_clone
  - kernel/fork.c:kernel_clone
  - kernel/fork.c:copy_signal
  - kernel/fork.c:mm_release
  - kernel/fork.c:mm_access
  - kernel/fork.c:get_task_exe_file
```
```
In kernel/cpu.c (ffffffff810fa071)
Location: include/linux/sched/task.h:188
Inline: True
Inline callers:
  - kernel/cpu.c:clear_tasks_mm_cpumask
```
```
In kernel/exit.c (ffffffff810fd6ec)
Location: include/linux/sched/task.h:188
Inline: True
Inline callers:
  - kernel/exit.c:exit_mm
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:mm_update_next_owner
```
```
In kernel/ptrace.c (ffffffff81107710)
Location: include/linux/sched/task.h:188
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:ptrace_may_access
```
```
In kernel/sys.c (ffffffff81115e48)
Location: include/linux/sched/task.h:188
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_auxv
  - kernel/sys.c:__ia32_compat_sys_old_getrlimit
  - kernel/sys.c:__ia32_sys_old_getrlimit
  - kernel/sys.c:__x64_sys_old_getrlimit
  - kernel/sys.c:__ia32_compat_sys_getrlimit
  - kernel/sys.c:__ia32_sys_getrlimit
  - kernel/sys.c:__x64_sys_getrlimit
```
```
In kernel/kthread.c (ffffffff8112a8ea)
Location: include/linux/sched/task.h:188
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_unuse_mm
  - kernel/kthread.c:kthread_use_mm
  - kernel/kthread.c:set_mems_allowed
```
```
In kernel/nsproxy.c (ffffffff81131673)
Location: include/linux/sched/task.h:188
Inline: True
Inline callers:
  - kernel/nsproxy.c:validate_nsset
  - kernel/nsproxy.c:switch_task_namespaces
```
```
In kernel/time/namespace.c (ffffffff8120754c)
Location: include/linux/sched/task.h:188
Inline: True
Inline callers:
  - kernel/time/namespace.c:proc_timens_set_offset
  - kernel/time/namespace.c:proc_timens_show_offsets
  - kernel/time/namespace.c:timens_get
```
```
In kernel/cgroup/namespace.c (ffffffff8122788c)
Location: include/linux/sched/task.h:188
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:cgroupns_get
```
```
In kernel/cgroup/cpuset.c (ffffffff8122d4ee)
Location: include/linux/sched/task.h:188
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
```
In kernel/utsname.c (ffffffff81235d9d)
Location: include/linux/sched/task.h:188
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_get
```
```
In kernel/pid_namespace.c (ffffffff81238e76)
Location: include/linux/sched/task.h:188
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_for_children_get
```
```
In mm/oom_kill.c (ffffffff813969b8)
Location: include/linux/sched/task.h:188
Inline: True
Inline callers:
  - mm/oom_kill.c:__do_sys_process_mrelease
  - mm/oom_kill.c:__do_sys_process_mrelease
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:oom_badness
  - mm/oom_kill.c:oom_badness
  - mm/oom_kill.c:oom_badness
```
```
In mm/mempolicy.c (ffffffff8144ded2)
Location: include/linux/sched/task.h:188
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_put_task_policy
  - mm/mempolicy.c:__mpol_dup
  - mm/mempolicy.c:mempolicy_in_oom_domain
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
```
```
In mm/memcontrol.c (ffffffff814846a2)
Location: include/linux/sched/task.h:188
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_attach
```
```
In fs/exec.c (ffffffff814b9492)
Location: include/linux/sched/task.h:188
Inline: True
Inline callers:
  - fs/exec.c:alloc_bprm
  - fs/exec.c:finalize_exec
  - fs/exec.c:__set_task_comm
  - fs/exec.c:__get_task_comm
  - fs/exec.c:exec_mmap
```
```
In fs/file.c (ffffffff814dbdaa)
Location: include/linux/sched/task.h:188
Inline: True
Inline callers:
  - fs/file.c:task_lookup_next_fd_rcu
  - fs/file.c:task_lookup_fd_rcu
  - fs/file.c:fget_task
  - fs/file.c:__close_range
  - fs/file.c:exit_files
```
```
In fs/namespace.c (ffffffff814dfc37)
Location: include/linux/sched/task.h:188
Inline: True
Inline callers:
  - fs/namespace.c:mntns_get
```
```
In fs/fs_struct.c (ffffffff8150152f)
Location: include/linux/sched/task.h:188
Inline: True
Inline callers:
  - fs/fs_struct.c:unshare_fs_struct
  - fs/fs_struct.c:exit_fs
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/kernel_read_file.c (ffffffff815067e7)
Location: include/linux/sched/task.h:188
Inline: True
Inline callers:
  - fs/kernel_read_file.c:kernel_read_file_from_path_initns
```
```
In fs/proc_namespace.c (ffffffff8150f722)
Location: include/linux/sched/task.h:188
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/coredump.c (ffffffff81550c67)
Location: include/linux/sched/task.h:188
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/task_mmu.c (ffffffff81563d38)
Location: include/linux/sched/task.h:188
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:hold_task_mempolicy
```
```
In fs/proc/base.c (ffffffff8156d024)
Location: include/linux/sched/task.h:188
Inline: True
Inline callers:
  - fs/proc/base.c:timerslack_ns_show
  - fs/proc/base.c:timerslack_ns_write
  - fs/proc/base.c:task_dump_owner
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
```
```
In fs/proc/array.c (ffffffff815731a3)
Location: include/linux/sched/task.h:188
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In fs/proc/fd.c (ffffffff815759c7)
Location: include/linux/sched/task.h:188
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_count
  - fs/proc/fd.c:seq_show
```
```
In fs/proc/proc_net.c (ffffffff8157c325)
Location: include/linux/sched/task.h:188
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_task_net
```
```
In ipc/shm.c (ffffffff8167f4f4)
Location: include/linux/sched/task.h:188
Inline: True
Inline callers:
  - ipc/shm.c:newseg
  - ipc/shm.c:exit_shm
  - ipc/shm.c:exit_shm
  - ipc/shm.c:exit_shm
  - ipc/shm.c:shm_destroy
```
```
In ipc/namespace.c (ffffffff816859c2)
Location: include/linux/sched/task.h:188
Inline: True
Inline callers:
  - ipc/namespace.c:ipcns_get
```
```
In security/selinux/hooks.c (ffffffff816aa07f)
Location: include/linux/sched/task.h:188
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committing_creds
```
```
In security/yama/yama_lsm.c (ffffffff81726acb)
Location: include/linux/sched/task.h:188
Inline: True
```
```
In block/blk-ioc.c (ffffffff81777170)
Location: include/linux/sched/task.h:188
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_find_get_icq
  - block/blk-ioc.c:set_task_ioprio
  - block/blk-ioc.c:set_task_ioprio
  - block/blk-ioc.c:exit_io_context
```
```
In block/ioprio.c (ffffffff8178ef82)
Location: include/linux/sched/task.h:188
Inline: True
Inline callers:
  - block/ioprio.c:__do_sys_ioprio_get
  - block/ioprio.c:__do_sys_ioprio_get
  - block/ioprio.c:__do_sys_ioprio_get
```
```
In drivers/tty/tty_io.c (ffffffff81a96c1f)
Location: include/linux/sched/task.h:188
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:__do_SAK
```
```
In net/core/net_namespace.c (ffffffff81e250bd)
Location: include/linux/sched/task.h:188
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_get
  - net/core/net_namespace.c:get_net_ns_by_pid
```
```
In net/core/netprio_cgroup.c (ffffffff81e9c7ae)
Location: include/linux/sched/task.h:188
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:net_prio_attach
```
```
In net/core/netclassid_cgroup.c (ffffffff81e9ce87)
Location: include/linux/sched/task.h:188
Inline: True
Inline callers:
  - net/core/netclassid_cgroup.c:write_classid
  - net/core/netclassid_cgroup.c:cgrp_attach
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
In init/main.c (ffffffff81000cc5)
Location: include/linux/sched/task.h:226
Inline: True
Inline callers:
  - init/main.c:set_mems_allowed
```
```
In kernel/fork.c (ffffffff810fec01)
Location: include/linux/sched/task.h:226
Inline: True
Inline callers:
  - kernel/fork.c:unshare_files
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:kernel_clone
  - kernel/fork.c:kernel_clone
  - kernel/fork.c:copy_signal
  - kernel/fork.c:mm_release
  - kernel/fork.c:mm_access
  - kernel/fork.c:get_task_exe_file
```
```
In kernel/cpu.c (ffffffff81103491)
Location: include/linux/sched/task.h:226
Inline: True
Inline callers:
  - kernel/cpu.c:clear_tasks_mm_cpumask
```
```
In kernel/exit.c (ffffffff8110655c)
Location: include/linux/sched/task.h:226
Inline: True
Inline callers:
  - kernel/exit.c:exit_mm
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:mm_update_next_owner
```
```
In kernel/ptrace.c (ffffffff8111107d)
Location: include/linux/sched/task.h:226
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:ptrace_may_access
```
```
In kernel/sys.c (ffffffff8111f838)
Location: include/linux/sched/task.h:226
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_auxv
  - kernel/sys.c:__ia32_compat_sys_old_getrlimit
  - kernel/sys.c:__ia32_sys_old_getrlimit
  - kernel/sys.c:__x64_sys_old_getrlimit
  - kernel/sys.c:__ia32_compat_sys_getrlimit
  - kernel/sys.c:__ia32_sys_getrlimit
  - kernel/sys.c:__x64_sys_getrlimit
```
```
In kernel/kthread.c (ffffffff81134f7a)
Location: include/linux/sched/task.h:226
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_unuse_mm
  - kernel/kthread.c:kthread_use_mm
  - kernel/kthread.c:set_mems_allowed
```
```
In kernel/nsproxy.c (ffffffff8113c41c)
Location: include/linux/sched/task.h:226
Inline: True
Inline callers:
  - kernel/nsproxy.c:validate_nsset
  - kernel/nsproxy.c:exec_task_namespaces
  - kernel/nsproxy.c:exit_task_namespaces
```
```
In kernel/time/namespace.c (ffffffff8121e75c)
Location: include/linux/sched/task.h:226
Inline: True
Inline callers:
  - kernel/time/namespace.c:proc_timens_set_offset
  - kernel/time/namespace.c:proc_timens_show_offsets
  - kernel/time/namespace.c:timens_get
```
```
In kernel/cgroup/namespace.c (ffffffff8123f69c)
Location: include/linux/sched/task.h:226
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:cgroupns_get
```
```
In kernel/cgroup/cpuset.c (ffffffff812457be)
Location: include/linux/sched/task.h:226
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
```
In kernel/utsname.c (ffffffff8124fa1d)
Location: include/linux/sched/task.h:226
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_get
```
```
In kernel/pid_namespace.c (ffffffff81252b46)
Location: include/linux/sched/task.h:226
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_for_children_get
```
```
In mm/oom_kill.c (ffffffff813c02c8)
Location: include/linux/sched/task.h:226
Inline: True
Inline callers:
  - mm/oom_kill.c:__do_sys_process_mrelease
  - mm/oom_kill.c:__do_sys_process_mrelease
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:oom_badness
  - mm/oom_kill.c:oom_badness
  - mm/oom_kill.c:oom_badness
```
```
In mm/mempolicy.c (ffffffff814878ad)
Location: include/linux/sched/task.h:226
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_put_task_policy
  - mm/mempolicy.c:__mpol_dup
  - mm/mempolicy.c:mempolicy_in_oom_domain
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
```
```
In mm/memcontrol.c (ffffffff814b3c24)
Location: include/linux/sched/task.h:226
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_attach
```
```
In fs/exec.c (ffffffff814ebf99)
Location: include/linux/sched/task.h:226
Inline: True
Inline callers:
  - fs/exec.c:alloc_bprm
  - fs/exec.c:finalize_exec
  - fs/exec.c:__set_task_comm
  - fs/exec.c:__get_task_comm
  - fs/exec.c:exec_mmap
```
```
In fs/file.c (ffffffff8150e350)
Location: include/linux/sched/task.h:226
Inline: True
Inline callers:
  - fs/file.c:task_lookup_next_fdget_rcu
  - fs/file.c:task_lookup_fdget_rcu
  - fs/file.c:fget_task
  - fs/file.c:__close_range
  - fs/file.c:exit_files
```
```
In fs/namespace.c (ffffffff81512b37)
Location: include/linux/sched/task.h:226
Inline: True
Inline callers:
  - fs/namespace.c:mntns_get
```
```
In fs/fs_struct.c (ffffffff8153617f)
Location: include/linux/sched/task.h:226
Inline: True
Inline callers:
  - fs/fs_struct.c:unshare_fs_struct
  - fs/fs_struct.c:exit_fs
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/kernel_read_file.c (ffffffff8153b507)
Location: include/linux/sched/task.h:226
Inline: True
Inline callers:
  - fs/kernel_read_file.c:kernel_read_file_from_path_initns
```
```
In fs/proc_namespace.c (ffffffff81543c22)
Location: include/linux/sched/task.h:226
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/coredump.c (ffffffff81586af8)
Location: include/linux/sched/task.h:226
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/task_mmu.c (ffffffff8159a618)
Location: include/linux/sched/task.h:226
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:hold_task_mempolicy
```
```
In fs/proc/base.c (ffffffff815a5824)
Location: include/linux/sched/task.h:226
Inline: True
Inline callers:
  - fs/proc/base.c:timerslack_ns_show
  - fs/proc/base.c:timerslack_ns_write
  - fs/proc/base.c:task_dump_owner
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
```
```
In fs/proc/array.c (ffffffff815ab963)
Location: include/linux/sched/task.h:226
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In fs/proc/fd.c (ffffffff815ae317)
Location: include/linux/sched/task.h:226
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_count
  - fs/proc/fd.c:seq_show
```
```
In fs/proc/proc_net.c (ffffffff815b4c35)
Location: include/linux/sched/task.h:226
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_task_net
```
```
In ipc/shm.c (ffffffff816bb8e4)
Location: include/linux/sched/task.h:226
Inline: True
Inline callers:
  - ipc/shm.c:newseg
  - ipc/shm.c:exit_shm
  - ipc/shm.c:exit_shm
  - ipc/shm.c:exit_shm
  - ipc/shm.c:shm_destroy
```
```
In ipc/namespace.c (ffffffff816c1de2)
Location: include/linux/sched/task.h:226
Inline: True
Inline callers:
  - ipc/namespace.c:ipcns_get
```
```
In security/selinux/hooks.c (ffffffff816e6892)
Location: include/linux/sched/task.h:226
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committing_creds
```
```
In security/yama/yama_lsm.c (ffffffff81767d1b)
Location: include/linux/sched/task.h:226
Inline: True
```
```
In block/blk-ioc.c (ffffffff817b939d)
Location: include/linux/sched/task.h:226
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_find_get_icq
  - block/blk-ioc.c:set_task_ioprio
  - block/blk-ioc.c:set_task_ioprio
  - block/blk-ioc.c:exit_io_context
```
```
In block/ioprio.c (ffffffff817d16db)
Location: include/linux/sched/task.h:226
Inline: True
Inline callers:
  - block/ioprio.c:__do_sys_ioprio_get
```
```
In drivers/tty/tty_io.c (ffffffff81ae9630)
Location: include/linux/sched/task.h:226
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:__do_SAK
```
```
In net/core/net_namespace.c (ffffffff81ee301d)
Location: include/linux/sched/task.h:226
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_get
  - net/core/net_namespace.c:get_net_ns_by_pid
```
```
In net/core/netprio_cgroup.c (ffffffff81f5ef4e)
Location: include/linux/sched/task.h:226
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:net_prio_attach
```
```
In net/core/netclassid_cgroup.c (ffffffff81f5f5bf)
Location: include/linux/sched/task.h:226
Inline: True
Inline callers:
  - net/core/netclassid_cgroup.c:update_classid_task
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
In init/main.c (ffff800011431278)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In kernel/fork.c (ffff8000100f59c4)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/fork.c:unshare_files
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:_do_fork
  - kernel/fork.c:copy_process
  - kernel/fork.c:mm_release
  - kernel/fork.c:get_task_mm
  - kernel/fork.c:get_task_exe_file
```
```
In kernel/cpu.c (ffff8000100f98b0)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/cpu.c:clear_tasks_mm_cpumask
```
```
In kernel/exit.c (ffff8000100fd518)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:mm_update_next_owner
```
```
In kernel/ptrace.c (ffff800010108018)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:ptrace_may_access
```
```
In kernel/sys.c (ffff800010115940)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_auxv
  - kernel/sys.c:do_prlimit
```
```
In kernel/kthread.c (ffff800010129100)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/kthread.c:kthreadd
```
```
In kernel/nsproxy.c (ffff80001012b6b8)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/nsproxy.c:switch_task_namespaces
```
```
In kernel/sched/debug.c (ffff800010163158)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
```
```
In kernel/kcmp.c (ffff8000101978e0)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/kcmp.c:get_file_raw_ptr
```
```
In kernel/cgroup/namespace.c (ffff8000101d9fc8)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:cgroupns_get
```
```
In kernel/cgroup/cpuset.c (ffff8000101e10e4)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
```
In kernel/utsname.c (ffff8000101e5154)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_get
```
```
In kernel/pid_namespace.c (ffff8000101e75f4)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_for_children_get
```
```
In mm/oom_kill.c (ffff8000102b7b5c)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:find_lock_task_mm
```
```
In mm/mmu_context.c (ffff8000102dfec0)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - mm/mmu_context.c:unuse_mm
  - mm/mmu_context.c:use_mm
```
```
In mm/mempolicy.c (ffff80001033bcfc)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_put_task_policy
  - mm/mempolicy.c:__mpol_dup
  - mm/mempolicy.c:mempolicy_nodemask_intersects
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
```
```
In fs/exec.c (ffff80001038c524)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - fs/exec.c:finalize_exec
  - fs/exec.c:__set_task_comm
  - fs/exec.c:__get_task_comm
```
```
In fs/file.c (ffff8000103b1fac)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - fs/file.c:exit_files
  - fs/file.c:reset_files_struct
  - fs/file.c:get_files_struct
```
```
In fs/namespace.c (ffff8000103b4df0)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - fs/namespace.c:mntns_get
```
```
In fs/fs_struct.c (ffff8000103d2d08)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - fs/fs_struct.c:unshare_fs_struct
  - fs/fs_struct.c:exit_fs
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/proc_namespace.c (ffff8000103e7a78)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/io_uring.c (ffff800010404b34)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In fs/coredump.c (ffff800010428a88)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/task_mmu.c (ffff800010439994)
Location: include/linux/sched/task.h:171
Inline: True
```
```
In fs/proc/base.c (ffff80001043fb78)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - fs/proc/base.c:timerslack_ns_show
  - fs/proc/base.c:timerslack_ns_write
  - fs/proc/base.c:task_dump_owner
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
```
```
In fs/proc/array.c (ffff800010444d80)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In fs/proc/proc_net.c (ffff80001044d090)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_task_net
```
```
In fs/hugetlbfs/inode.c (ffff8000104e2b78)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
```
```
In ipc/namespace.c (ffff80001052ca48)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - ipc/namespace.c:ipcns_get
```
```
In security/selinux/hooks.c (ffff800010550164)
Location: include/linux/sched/task.h:171
Inline: True
```
```
In security/yama/yama_lsm.c (ffff8000105aa768)
Location: include/linux/sched/task.h:171
Inline: True
```
```
In block/blk-ioc.c (ffff8000105e8f10)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - block/blk-ioc.c:get_task_io_context
  - block/blk-ioc.c:get_task_io_context
  - block/blk-ioc.c:create_task_io_context
  - block/blk-ioc.c:exit_io_context
```
```
In block/ioprio.c (ffff8000105fdd90)
Location: include/linux/sched/task.h:171
Inline: True
```
```
In block/blk-cgroup.c (ffff80001060c3dc)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_can_attach
```
```
In drivers/tty/tty_io.c (ffff800010850180)
Location: include/linux/sched/task.h:171
Inline: True
```
```
In net/core/net_namespace.c (ffff800010bc1244)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_get
  - net/core/net_namespace.c:get_net_ns_by_pid
```
```
In net/core/netprio_cgroup.c (ffff800010c1d4bc)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:net_prio_attach
```
```
In net/core/netclassid_cgroup.c (ffff800010c1d81c)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - net/core/netclassid_cgroup.c:update_classid_task
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
In init/main.c (c1501290)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In kernel/fork.c (c0354128)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/fork.c:unshare_files
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:_do_fork
  - kernel/fork.c:copy_process
  - kernel/fork.c:mm_release
  - kernel/fork.c:get_task_mm
  - kernel/fork.c:get_task_exe_file
```
```
In kernel/cpu.c (c0357b04)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/cpu.c:clear_tasks_mm_cpumask
```
```
In kernel/exit.c (c035a69c)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:mm_update_next_owner
```
```
In kernel/ptrace.c (c0362590)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/ptrace.c:__se_sys_ptrace
  - kernel/ptrace.c:ptrace_may_access
```
```
In kernel/sys.c (c036b2e4)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_auxv
  - kernel/sys.c:do_prlimit
```
```
In kernel/kthread.c (c037b690)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/kthread.c:kthreadd
```
```
In kernel/nsproxy.c (c037bc28)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/nsproxy.c:switch_task_namespaces
```
```
In kernel/kcmp.c (c03e2b4c)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/kcmp.c:get_file_raw_ptr
```
```
In kernel/cgroup/namespace.c (c041c938)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:cgroupns_get
```
```
In kernel/cgroup/cpuset.c (c0421d60)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
```
In kernel/utsname.c (c0425a44)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_get
```
```
In kernel/pid_namespace.c (c0427a3c)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_for_children_get
```
```
In mm/oom_kill.c (c04e477c)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:find_lock_task_mm
```
```
In mm/mmu_context.c (c05049a0)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - mm/mmu_context.c:unuse_mm
  - mm/mmu_context.c:use_mm
```
```
In fs/exec.c (c057596c)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - fs/exec.c:__do_execve_file
  - fs/exec.c:finalize_exec
  - fs/exec.c:__set_task_comm
  - fs/exec.c:__get_task_comm
```
```
In fs/file.c (c0591448)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - fs/file.c:exit_files
  - fs/file.c:reset_files_struct
  - fs/file.c:get_files_struct
```
```
In fs/namespace.c (c0592908)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - fs/namespace.c:mntns_get
```
```
In fs/fs_struct.c (c05ad800)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - fs/fs_struct.c:unshare_fs_struct
  - fs/fs_struct.c:exit_fs
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/proc_namespace.c (c05bf5d0)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/io_uring.c (c05d4544)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In fs/coredump.c (c05f1668)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/base.c (c0605838)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - fs/proc/base.c:timerslack_ns_show
  - fs/proc/base.c:timerslack_ns_write
  - fs/proc/base.c:task_dump_owner
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
```
```
In fs/proc/array.c (c0609954)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In fs/proc/proc_net.c (c0611634)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_task_net
```
```
In ipc/namespace.c (c06e5398)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - ipc/namespace.c:ipcns_get
```
```
In security/selinux/hooks.c (c0706130)
Location: include/linux/sched/task.h:171
Inline: True
```
```
In security/yama/yama_lsm.c (c075a6e8)
Location: include/linux/sched/task.h:171
Inline: True
```
```
In block/blk-ioc.c (c07955cc)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - block/blk-ioc.c:get_task_io_context
  - block/blk-ioc.c:get_task_io_context
  - block/blk-ioc.c:create_task_io_context
  - block/blk-ioc.c:exit_io_context
```
```
In block/ioprio.c (c07a8c8c)
Location: include/linux/sched/task.h:171
Inline: True
```
```
In block/blk-cgroup.c (c07b6c2c)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_can_attach
```
```
In drivers/tty/tty_io.c (c095c980)
Location: include/linux/sched/task.h:171
Inline: True
```
```
In net/core/net_namespace.c (c0cdba90)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_get
  - net/core/net_namespace.c:get_net_ns_by_pid
```
```
In net/core/netprio_cgroup.c (c0d34eec)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:net_prio_attach
```
```
In net/core/netclassid_cgroup.c (c0d353dc)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - net/core/netclassid_cgroup.c:update_classid_task
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
In init/main.c (c0000000013444f4)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In kernel/fork.c (c00000000013bb64)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/fork.c:unshare_files
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:_do_fork
  - kernel/fork.c:copy_process
  - kernel/fork.c:mm_release
  - kernel/fork.c:get_task_mm
  - kernel/fork.c:get_task_exe_file
```
```
In kernel/cpu.c (c0000000001407a0)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/cpu.c:clear_tasks_mm_cpumask
```
```
In kernel/exit.c (c0000000001443e4)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:mm_update_next_owner
```
```
In kernel/ptrace.c (c00000000014f3f0)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:ptrace_may_access
```
```
In kernel/sys.c (c00000000015e1f8)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_auxv
  - kernel/sys.c:do_prlimit
  - kernel/sys.c:__se_compat_sys_old_getrlimit
  - kernel/sys.c:__se_sys_old_getrlimit
```
```
In kernel/kthread.c (c00000000017396c)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/kthread.c:kthreadd
```
```
In kernel/nsproxy.c (c000000000174228)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/nsproxy.c:switch_task_namespaces
```
```
In kernel/sched/debug.c (c0000000001b9940)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
```
```
In kernel/kcmp.c (c0000000001f778c)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/kcmp.c:get_file_raw_ptr
```
```
In kernel/cgroup/namespace.c (c000000000247198)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:cgroupns_get
```
```
In kernel/cgroup/cpuset.c (c00000000024f0a4)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
```
In kernel/utsname.c (c0000000002554e4)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_get
```
```
In kernel/pid_namespace.c (c000000000257bf8)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_for_children_get
```
```
In mm/oom_kill.c (c00000000036f960)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:find_lock_task_mm
```
```
In mm/mmu_context.c (c00000000039f8cc)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - mm/mmu_context.c:unuse_mm
  - mm/mmu_context.c:use_mm
```
```
In mm/mempolicy.c (c000000000416bec)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_put_task_policy
  - mm/mempolicy.c:__mpol_dup
  - mm/mempolicy.c:mempolicy_nodemask_intersects
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
```
```
In fs/exec.c (c0000000004853dc)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - fs/exec.c:finalize_exec
  - fs/exec.c:__set_task_comm
  - fs/exec.c:__get_task_comm
```
```
In fs/file.c (c0000000004add78)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - fs/file.c:exit_files
  - fs/file.c:reset_files_struct
  - fs/file.c:get_files_struct
```
```
In fs/namespace.c (c0000000004b1344)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - fs/namespace.c:mntns_get
```
```
In fs/fs_struct.c (c0000000004d5924)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - fs/fs_struct.c:unshare_fs_struct
  - fs/fs_struct.c:exit_fs
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/proc_namespace.c (c0000000004ee23c)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/io_uring.c (c00000000050d49c)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In fs/coredump.c (c000000000538c54)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/task_mmu.c (c00000000054ae80)
Location: include/linux/sched/task.h:171
Inline: True
```
```
In fs/proc/base.c (c0000000005537c8)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - fs/proc/base.c:timerslack_ns_show
  - fs/proc/base.c:timerslack_ns_write
  - fs/proc/base.c:task_dump_owner
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
```
```
In fs/proc/array.c (c00000000055a178)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In fs/proc/proc_net.c (c000000000564608)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_task_net
```
```
In fs/hugetlbfs/inode.c (c00000000061fd98)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
```
```
In ipc/namespace.c (c000000000678978)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - ipc/namespace.c:ipcns_get
```
```
In security/selinux/hooks.c (c0000000006aadd0)
Location: include/linux/sched/task.h:171
Inline: True
```
```
In security/yama/yama_lsm.c (c000000000728590)
Location: include/linux/sched/task.h:171
Inline: True
```
```
In block/blk-ioc.c (c00000000077db40)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - block/blk-ioc.c:get_task_io_context
  - block/blk-ioc.c:get_task_io_context
  - block/blk-ioc.c:create_task_io_context
  - block/blk-ioc.c:exit_io_context
```
```
In block/ioprio.c (c000000000797860)
Location: include/linux/sched/task.h:171
Inline: True
```
```
In block/blk-cgroup.c (c0000000007a83d0)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_can_attach
```
```
In drivers/tty/tty_io.c (c0000000008f06ac)
Location: include/linux/sched/task.h:171
Inline: True
```
```
In net/core/net_namespace.c (c000000000c99d68)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_get
  - net/core/net_namespace.c:get_net_ns_by_pid
```
```
In net/core/netprio_cgroup.c (c000000000d0e0e4)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:net_prio_attach
```
```
In net/core/netclassid_cgroup.c (c000000000d0eb10)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - net/core/netclassid_cgroup.c:update_classid_task
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
In init/main.c (ffffffe000000f94)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In kernel/fork.c (ffffffe0000c1cc8)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/fork.c:unshare_files
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:_do_fork
  - kernel/fork.c:copy_process
  - kernel/fork.c:mm_release
  - kernel/fork.c:get_task_mm
  - kernel/fork.c:get_task_exe_file
```
```
In kernel/exit.c (ffffffe0000c5d56)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:mm_update_next_owner
```
```
In kernel/ptrace.c (ffffffe0000cc41a)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/ptrace.c:__se_sys_ptrace
  - kernel/ptrace.c:ptrace_may_access
```
```
In kernel/sys.c (ffffffe0000d27f8)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_auxv
  - kernel/sys.c:do_prlimit
```
```
In kernel/kthread.c (ffffffe0000dff7c)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/kthread.c:kthreadd
```
```
In kernel/nsproxy.c (ffffffe0000e0482)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/nsproxy.c:switch_task_namespaces
```
```
In kernel/kcmp.c (ffffffe000128980)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/kcmp.c:get_file_raw_ptr
```
```
In kernel/cgroup/namespace.c (ffffffe000152950)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:cgroupns_get
```
```
In kernel/cgroup/cpuset.c (ffffffe000157dfc)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
```
In kernel/utsname.c (ffffffe00015adaa)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_get
```
```
In kernel/pid_namespace.c (ffffffe00015cb24)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_for_children_get
```
```
In mm/oom_kill.c (ffffffe0001dbd96)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:find_lock_task_mm
```
```
In mm/mmu_context.c (ffffffe0001f7846)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - mm/mmu_context.c:unuse_mm
  - mm/mmu_context.c:use_mm
```
```
In fs/exec.c (ffffffe00025eaee)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - fs/exec.c:__do_execve_file
  - fs/exec.c:finalize_exec
  - fs/exec.c:__set_task_comm
  - fs/exec.c:__get_task_comm
```
```
In fs/file.c (ffffffe000276068)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - fs/file.c:exit_files
  - fs/file.c:reset_files_struct
  - fs/file.c:get_files_struct
```
```
In fs/namespace.c (ffffffe000277f10)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - fs/namespace.c:mntns_get
```
```
In fs/fs_struct.c (ffffffe00028df18)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - fs/fs_struct.c:unshare_fs_struct
  - fs/fs_struct.c:exit_fs
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/proc_namespace.c (ffffffe00029c8d6)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/io_uring.c (ffffffe0002afe86)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In fs/coredump.c (ffffffe0002c6c22)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/base.c (ffffffe0002d6dfa)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - fs/proc/base.c:timerslack_ns_show
  - fs/proc/base.c:timerslack_ns_write
  - fs/proc/base.c:task_dump_owner
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
```
```
In fs/proc/array.c (ffffffe0002dad00)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In fs/proc/proc_net.c (ffffffe0002e1d6c)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_task_net
```
```
In fs/hugetlbfs/inode.c (ffffffe000356618)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
```
```
In ipc/namespace.c (ffffffe00038e97c)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - ipc/namespace.c:ipcns_get
```
```
In security/selinux/hooks.c (ffffffe0003a89f6)
Location: include/linux/sched/task.h:171
Inline: True
```
```
In security/yama/yama_lsm.c (ffffffe0003f3854)
Location: include/linux/sched/task.h:171
Inline: True
```
```
In block/blk-ioc.c (ffffffe00042976c)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - block/blk-ioc.c:get_task_io_context
  - block/blk-ioc.c:get_task_io_context
  - block/blk-ioc.c:create_task_io_context
  - block/blk-ioc.c:exit_io_context
```
```
In block/ioprio.c (ffffffe000439786)
Location: include/linux/sched/task.h:171
Inline: True
```
```
In block/blk-cgroup.c (ffffffe0004452e6)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_can_attach
```
```
In drivers/tty/tty_io.c (ffffffe00052e568)
Location: include/linux/sched/task.h:171
Inline: True
```
```
In net/core/net_namespace.c (ffffffe00074e1f4)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_get
  - net/core/net_namespace.c:get_net_ns_by_pid
```
```
In net/core/netprio_cgroup.c (ffffffe00079710a)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:net_prio_attach
```
```
In net/core/netclassid_cgroup.c (ffffffe000797392)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - net/core/netclassid_cgroup.c:update_classid_task
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
In init/main.c (ffffffff8288b2a7)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In kernel/fork.c (ffffffff8109a8fa)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/fork.c:unshare_files
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:_do_fork
  - kernel/fork.c:copy_process
  - kernel/fork.c:mm_release
  - kernel/fork.c:get_task_mm
  - kernel/fork.c:get_task_exe_file
```
```
In kernel/cpu.c (ffffffff8109d74b)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/cpu.c:clear_tasks_mm_cpumask
```
```
In kernel/exit.c (ffffffff8109feb5)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:mm_update_next_owner
```
```
In kernel/ptrace.c (ffffffff810a828e)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:ptrace_may_access
```
```
In kernel/sys.c (ffffffff810b4590)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_auxv
  - kernel/sys.c:do_prlimit
  - kernel/sys.c:__x32_compat_sys_old_getrlimit
  - kernel/sys.c:__ia32_compat_sys_old_getrlimit
  - kernel/sys.c:__ia32_sys_old_getrlimit
  - kernel/sys.c:__x64_sys_old_getrlimit
```
```
In kernel/kthread.c (ffffffff810c38f6)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/kthread.c:kthreadd
```
```
In kernel/nsproxy.c (ffffffff810c6ca9)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/nsproxy.c:switch_task_namespaces
```
```
In kernel/sched/debug.c (ffffffff810f6c5c)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
```
```
In kernel/kcmp.c (ffffffff81129060)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/kcmp.c:get_file_raw_ptr
```
```
In kernel/cgroup/namespace.c (ffffffff8115ff1d)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:cgroupns_get
```
```
In kernel/cgroup/cpuset.c (ffffffff811648d0)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
```
In kernel/utsname.c (ffffffff81169ba8)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_get
```
```
In kernel/pid_namespace.c (ffffffff8116b970)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_for_children_get
```
```
In mm/oom_kill.c (ffffffff81222316)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:find_lock_task_mm
```
```
In mm/mmu_context.c (ffffffff81242958)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - mm/mmu_context.c:unuse_mm
  - mm/mmu_context.c:use_mm
```
```
In mm/mempolicy.c (ffffffff812952c8)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_put_task_policy
  - mm/mempolicy.c:__mpol_dup
  - mm/mempolicy.c:mempolicy_nodemask_intersects
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
```
```
In fs/exec.c (ffffffff812ddd4d)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - fs/exec.c:finalize_exec
  - fs/exec.c:__set_task_comm
  - fs/exec.c:__get_task_comm
```
```
In fs/file.c (ffffffff812f89ba)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - fs/file.c:exit_files
  - fs/file.c:reset_files_struct
  - fs/file.c:get_files_struct
```
```
In fs/namespace.c (ffffffff812fa5a5)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - fs/namespace.c:mntns_get
```
```
In fs/fs_struct.c (ffffffff81313cf3)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - fs/fs_struct.c:unshare_fs_struct
  - fs/fs_struct.c:exit_fs
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/proc_namespace.c (ffffffff813248ba)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/io_uring.c (ffffffff8133b568)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In fs/coredump.c (ffffffff8135a8dc)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/task_mmu.c (ffffffff81367d26)
Location: include/linux/sched/task.h:171
Inline: True
```
```
In fs/proc/base.c (ffffffff8136cd56)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - fs/proc/base.c:timerslack_ns_show
  - fs/proc/base.c:timerslack_ns_write
  - fs/proc/base.c:task_dump_owner
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
```
```
In fs/proc/array.c (ffffffff81370cc8)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In fs/proc/proc_net.c (ffffffff81377d1d)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_task_net
```
```
In fs/hugetlbfs/inode.c (ffffffff813fc8cb)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
```
```
In ipc/namespace.c (ffffffff8143c7fd)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - ipc/namespace.c:ipcns_get
```
```
In security/selinux/hooks.c (ffffffff8145aa0c)
Location: include/linux/sched/task.h:171
Inline: True
```
```
In security/yama/yama_lsm.c (ffffffff814ab4bc)
Location: include/linux/sched/task.h:171
Inline: True
```
```
In block/blk-ioc.c (ffffffff814e2d86)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - block/blk-ioc.c:get_task_io_context
  - block/blk-ioc.c:get_task_io_context
  - block/blk-ioc.c:create_task_io_context
  - block/blk-ioc.c:exit_io_context
```
```
In block/ioprio.c (ffffffff814f4329)
Location: include/linux/sched/task.h:171
Inline: True
```
```
In block/blk-cgroup.c (ffffffff81501c2e)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_can_attach
```
```
In drivers/tty/tty_io.c (ffffffff81649459)
Location: include/linux/sched/task.h:171
Inline: True
```
```
In net/core/net_namespace.c (ffffffff818c4b49)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_get
  - net/core/net_namespace.c:get_net_ns_by_pid
```
```
In net/core/netprio_cgroup.c (ffffffff81916b7c)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:net_prio_attach
```
```
In net/core/netclassid_cgroup.c (ffffffff81916da0)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - net/core/netclassid_cgroup.c:update_classid_task
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
In init/main.c (ffffffff82889224)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In kernel/fork.c (ffffffff8108933a)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/fork.c:unshare_files
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:_do_fork
  - kernel/fork.c:copy_process
  - kernel/fork.c:mm_release
  - kernel/fork.c:get_task_mm
  - kernel/fork.c:get_task_exe_file
```
```
In kernel/cpu.c (ffffffff8108c16b)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/cpu.c:clear_tasks_mm_cpumask
```
```
In kernel/exit.c (ffffffff8108e8e5)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:mm_update_next_owner
```
```
In kernel/ptrace.c (ffffffff81096c4e)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:ptrace_may_access
```
```
In kernel/sys.c (ffffffff810a2ec0)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_auxv
  - kernel/sys.c:do_prlimit
  - kernel/sys.c:__x32_compat_sys_old_getrlimit
  - kernel/sys.c:__ia32_compat_sys_old_getrlimit
  - kernel/sys.c:__ia32_sys_old_getrlimit
  - kernel/sys.c:__x64_sys_old_getrlimit
```
```
In kernel/kthread.c (ffffffff810b210c)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/kthread.c:kthreadd
```
```
In kernel/nsproxy.c (ffffffff810b54c9)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/nsproxy.c:switch_task_namespaces
```
```
In kernel/sched/debug.c (ffffffff810e6e2c)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
```
```
In kernel/kcmp.c (ffffffff8111b8f0)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/kcmp.c:get_file_raw_ptr
```
```
In kernel/cgroup/namespace.c (ffffffff8115318d)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:cgroupns_get
```
```
In kernel/cgroup/cpuset.c (ffffffff81157b14)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
```
In kernel/utsname.c (ffffffff8115cda8)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_get
```
```
In kernel/pid_namespace.c (ffffffff8115eb70)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_for_children_get
```
```
In mm/oom_kill.c (ffffffff812154c6)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:find_lock_task_mm
```
```
In mm/mmu_context.c (ffffffff81235928)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - mm/mmu_context.c:unuse_mm
  - mm/mmu_context.c:use_mm
```
```
In mm/mempolicy.c (ffffffff81286ed8)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_put_task_policy
  - mm/mempolicy.c:__mpol_dup
  - mm/mempolicy.c:mempolicy_nodemask_intersects
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
```
```
In fs/exec.c (ffffffff812ce9cd)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - fs/exec.c:finalize_exec
  - fs/exec.c:__set_task_comm
  - fs/exec.c:__get_task_comm
```
```
In fs/file.c (ffffffff812e95da)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - fs/file.c:exit_files
  - fs/file.c:reset_files_struct
  - fs/file.c:get_files_struct
```
```
In fs/namespace.c (ffffffff812eb1c5)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - fs/namespace.c:mntns_get
```
```
In fs/fs_struct.c (ffffffff81304903)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - fs/fs_struct.c:unshare_fs_struct
  - fs/fs_struct.c:exit_fs
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/proc_namespace.c (ffffffff8131545a)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/io_uring.c (ffffffff8132c248)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In fs/coredump.c (ffffffff8134b580)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/task_mmu.c (ffffffff81358bd6)
Location: include/linux/sched/task.h:171
Inline: True
```
```
In fs/proc/base.c (ffffffff8135d7e6)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - fs/proc/base.c:timerslack_ns_show
  - fs/proc/base.c:timerslack_ns_write
  - fs/proc/base.c:task_dump_owner
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
```
```
In fs/proc/array.c (ffffffff81361758)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In fs/proc/proc_net.c (ffffffff813687ed)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_task_net
```
```
In fs/hugetlbfs/inode.c (ffffffff813ed34b)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
```
```
In ipc/namespace.c (ffffffff8142d26d)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - ipc/namespace.c:ipcns_get
```
```
In security/selinux/hooks.c (ffffffff8144b43c)
Location: include/linux/sched/task.h:171
Inline: True
```
```
In security/yama/yama_lsm.c (ffffffff8149bedc)
Location: include/linux/sched/task.h:171
Inline: True
```
```
In block/blk-ioc.c (ffffffff814d3716)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - block/blk-ioc.c:get_task_io_context
  - block/blk-ioc.c:get_task_io_context
  - block/blk-ioc.c:create_task_io_context
  - block/blk-ioc.c:exit_io_context
```
```
In block/ioprio.c (ffffffff814e4839)
Location: include/linux/sched/task.h:171
Inline: True
```
```
In block/blk-cgroup.c (ffffffff814f213e)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_can_attach
```
```
In drivers/tty/tty_io.c (ffffffff816298b9)
Location: include/linux/sched/task.h:171
Inline: True
```
```
In net/core/net_namespace.c (ffffffff8187ea89)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_get
  - net/core/net_namespace.c:get_net_ns_by_pid
```
```
In net/core/netprio_cgroup.c (ffffffff818d092c)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:net_prio_attach
```
```
In net/core/netclassid_cgroup.c (ffffffff818d0b50)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - net/core/netclassid_cgroup.c:update_classid_task
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
In init/main.c (ffffffff8289e2a7)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In kernel/fork.c (ffffffff8109a8aa)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/fork.c:unshare_files
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:_do_fork
  - kernel/fork.c:copy_process
  - kernel/fork.c:mm_release
  - kernel/fork.c:get_task_mm
  - kernel/fork.c:get_task_exe_file
```
```
In kernel/cpu.c (ffffffff8109d6fb)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/cpu.c:clear_tasks_mm_cpumask
```
```
In kernel/exit.c (ffffffff8109fe65)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:mm_update_next_owner
```
```
In kernel/ptrace.c (ffffffff810a77ee)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:ptrace_may_access
```
```
In kernel/sys.c (ffffffff810b3af0)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_auxv
  - kernel/sys.c:do_prlimit
  - kernel/sys.c:__x32_compat_sys_old_getrlimit
  - kernel/sys.c:__ia32_compat_sys_old_getrlimit
  - kernel/sys.c:__ia32_sys_old_getrlimit
  - kernel/sys.c:__x64_sys_old_getrlimit
```
```
In kernel/kthread.c (ffffffff810c2e46)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/kthread.c:kthreadd
```
```
In kernel/nsproxy.c (ffffffff810c61f9)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/nsproxy.c:switch_task_namespaces
```
```
In kernel/sched/debug.c (ffffffff810f3e6c)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
```
```
In kernel/kcmp.c (ffffffff81126d80)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/kcmp.c:get_file_raw_ptr
```
```
In kernel/cgroup/namespace.c (ffffffff8115dced)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:cgroupns_get
```
```
In kernel/cgroup/cpuset.c (ffffffff811626a0)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
```
In kernel/utsname.c (ffffffff81167978)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_get
```
```
In kernel/pid_namespace.c (ffffffff81169740)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_for_children_get
```
```
In mm/oom_kill.c (ffffffff812200b6)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:find_lock_task_mm
```
```
In mm/mmu_context.c (ffffffff812406f8)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - mm/mmu_context.c:unuse_mm
  - mm/mmu_context.c:use_mm
```
```
In mm/mempolicy.c (ffffffff812930d8)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_put_task_policy
  - mm/mempolicy.c:__mpol_dup
  - mm/mempolicy.c:mempolicy_nodemask_intersects
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
```
```
In fs/exec.c (ffffffff812dbb5d)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - fs/exec.c:finalize_exec
  - fs/exec.c:__set_task_comm
  - fs/exec.c:__get_task_comm
```
```
In fs/file.c (ffffffff812f67ca)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - fs/file.c:exit_files
  - fs/file.c:reset_files_struct
  - fs/file.c:get_files_struct
```
```
In fs/namespace.c (ffffffff812f8395)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - fs/namespace.c:mntns_get
```
```
In fs/fs_struct.c (ffffffff81311ae3)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - fs/fs_struct.c:unshare_fs_struct
  - fs/fs_struct.c:exit_fs
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/proc_namespace.c (ffffffff8132238a)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/io_uring.c (ffffffff81339038)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In fs/coredump.c (ffffffff813583ac)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/task_mmu.c (ffffffff813657f6)
Location: include/linux/sched/task.h:171
Inline: True
```
```
In fs/proc/base.c (ffffffff8136a826)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - fs/proc/base.c:timerslack_ns_show
  - fs/proc/base.c:timerslack_ns_write
  - fs/proc/base.c:task_dump_owner
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
```
```
In fs/proc/array.c (ffffffff8136e798)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In fs/proc/proc_net.c (ffffffff813757ed)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_task_net
```
```
In fs/hugetlbfs/inode.c (ffffffff813f9c4b)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
```
```
In ipc/namespace.c (ffffffff8143899d)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - ipc/namespace.c:ipcns_get
```
```
In security/selinux/hooks.c (ffffffff81456aac)
Location: include/linux/sched/task.h:171
Inline: True
```
```
In security/yama/yama_lsm.c (ffffffff814a755c)
Location: include/linux/sched/task.h:171
Inline: True
```
```
In block/blk-ioc.c (ffffffff814dee16)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - block/blk-ioc.c:get_task_io_context
  - block/blk-ioc.c:get_task_io_context
  - block/blk-ioc.c:create_task_io_context
  - block/blk-ioc.c:exit_io_context
```
```
In block/ioprio.c (ffffffff814f03b9)
Location: include/linux/sched/task.h:171
Inline: True
```
```
In block/blk-cgroup.c (ffffffff814fdcbe)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_can_attach
```
```
In drivers/tty/tty_io.c (ffffffff81677819)
Location: include/linux/sched/task.h:171
Inline: True
```
```
In net/core/net_namespace.c (ffffffff81915b49)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_get
  - net/core/net_namespace.c:get_net_ns_by_pid
```
```
In net/core/netprio_cgroup.c (ffffffff81967d0c)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:net_prio_attach
```
```
In net/core/netclassid_cgroup.c (ffffffff81967f30)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - net/core/netclassid_cgroup.c:update_classid_task
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
In init/main.c (ffffffff8289e2ae)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In kernel/fork.c (ffffffff810a252a)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/fork.c:unshare_files
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:_do_fork
  - kernel/fork.c:copy_process
  - kernel/fork.c:mm_release
  - kernel/fork.c:get_task_mm
  - kernel/fork.c:get_task_exe_file
```
```
In kernel/cpu.c (ffffffff810a5581)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/cpu.c:clear_tasks_mm_cpumask
```
```
In kernel/exit.c (ffffffff810a7dd0)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:mm_update_next_owner
```
```
In kernel/ptrace.c (ffffffff810af90e)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:ptrace_may_access
```
```
In kernel/sys.c (ffffffff810ba530)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_auxv
  - kernel/sys.c:do_prlimit
  - kernel/sys.c:__x32_compat_sys_old_getrlimit
  - kernel/sys.c:__ia32_compat_sys_old_getrlimit
  - kernel/sys.c:__ia32_sys_old_getrlimit
  - kernel/sys.c:__x64_sys_old_getrlimit
```
```
In kernel/kthread.c (ffffffff810cb286)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/kthread.c:kthreadd
```
```
In kernel/nsproxy.c (ffffffff810ce646)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/nsproxy.c:switch_task_namespaces
```
```
In kernel/sched/debug.c (ffffffff810fee61)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
```
```
In kernel/kcmp.c (ffffffff811333dc)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/kcmp.c:get_file_raw_ptr
```
```
In kernel/cgroup/namespace.c (ffffffff8116af51)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:cgroupns_get
```
```
In kernel/cgroup/cpuset.c (ffffffff8116fc20)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
```
In kernel/utsname.c (ffffffff8117504c)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_get
```
```
In kernel/pid_namespace.c (ffffffff81176e59)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_for_children_get
```
```
In mm/oom_kill.c (ffffffff8122f1c6)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:find_lock_task_mm
```
```
In mm/mmu_context.c (ffffffff8124fe78)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - mm/mmu_context.c:unuse_mm
  - mm/mmu_context.c:use_mm
```
```
In mm/mempolicy.c (ffffffff812a2f18)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:mpol_put_task_policy
  - mm/mempolicy.c:__mpol_dup
  - mm/mempolicy.c:mempolicy_nodemask_intersects
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:do_set_mempolicy
```
```
In fs/exec.c (ffffffff812eb28d)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - fs/exec.c:finalize_exec
  - fs/exec.c:__set_task_comm
  - fs/exec.c:__get_task_comm
```
```
In fs/file.c (ffffffff813079fa)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - fs/file.c:exit_files
  - fs/file.c:reset_files_struct
  - fs/file.c:get_files_struct
```
```
In fs/namespace.c (ffffffff81308a78)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - fs/namespace.c:mntns_get
```
```
In fs/fs_struct.c (ffffffff8132331e)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - fs/fs_struct.c:unshare_fs_struct
  - fs/fs_struct.c:exit_fs
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/proc_namespace.c (ffffffff813340df)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/io_uring.c (ffffffff8134b899)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In fs/coredump.c (ffffffff8136bad3)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/task_mmu.c (ffffffff81378556)
Location: include/linux/sched/task.h:171
Inline: True
```
```
In fs/proc/base.c (ffffffff8137e108)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - fs/proc/base.c:timerslack_ns_show
  - fs/proc/base.c:timerslack_ns_write
  - fs/proc/base.c:task_dump_owner
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
```
```
In fs/proc/array.c (ffffffff813820f2)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In fs/proc/proc_net.c (ffffffff81389296)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_task_net
```
```
In fs/hugetlbfs/inode.c (ffffffff8140f89b)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
```
```
In ipc/namespace.c (ffffffff8144fb01)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - ipc/namespace.c:ipcns_get
```
```
In security/selinux/hooks.c (ffffffff8146ea6f)
Location: include/linux/sched/task.h:171
Inline: True
```
```
In security/yama/yama_lsm.c (ffffffff814bfebc)
Location: include/linux/sched/task.h:171
Inline: True
```
```
In block/blk-ioc.c (ffffffff814f7c7e)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - block/blk-ioc.c:get_task_io_context
  - block/blk-ioc.c:get_task_io_context
  - block/blk-ioc.c:create_task_io_context
  - block/blk-ioc.c:exit_io_context
```
```
In block/ioprio.c (ffffffff8150945d)
Location: include/linux/sched/task.h:171
Inline: True
```
```
In block/blk-cgroup.c (ffffffff8151675b)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_can_attach
```
```
In drivers/tty/tty_io.c (ffffffff81691b46)
Location: include/linux/sched/task.h:171
Inline: True
```
```
In net/core/net_namespace.c (ffffffff81936d3d)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_get
  - net/core/net_namespace.c:get_net_ns_by_pid
```
```
In net/core/netprio_cgroup.c (ffffffff81989c3c)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:net_prio_attach
```
```
In net/core/netclassid_cgroup.c (ffffffff8198a0b0)
Location: include/linux/sched/task.h:171
Inline: True
Inline callers:
  - net/core/netclassid_cgroup.c:update_classid_task
```
</details>
</li>
</ul>

## Differences
