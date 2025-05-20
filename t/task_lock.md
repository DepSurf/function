# Function: <code>task_lock</code>

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
In init/main.c (ffffffff81f5a04c)
Location: include/linux/sched.h:2738
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In kernel/fork.c (ffffffff8107d5fc)
Location: include/linux/sched.h:2738
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
In kernel/exit.c (ffffffff8108373a)
Location: include/linux/sched.h:2738
Inline: True
Inline callers:
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
```
In kernel/ptrace.c (ffffffff8108ae5a)
Location: include/linux/sched.h:2738
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:ptrace_may_access
```
```
In kernel/sys.c (ffffffff8109258a)
Location: include/linux/sched.h:2738
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_auxv
  - kernel/sys.c:SyS_old_getrlimit
  - kernel/sys.c:do_prlimit
```
```
In kernel/kthread.c (ffffffff810a0d1b)
Location: include/linux/sched.h:2738
Inline: True
Inline callers:
  - kernel/kthread.c:kthreadd
```
```
In kernel/nsproxy.c (ffffffff810a1274)
Location: include/linux/sched.h:2738
Inline: True
Inline callers:
  - kernel/nsproxy.c:switch_task_namespaces
```
```
In kernel/sched/debug.c (ffffffff810c8968)
Location: include/linux/sched.h:2738
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
```
```
In kernel/kcmp.c (ffffffff810e971e)
Location: include/linux/sched.h:2738
Inline: True
Inline callers:
  - kernel/kcmp.c:get_file_raw_ptr
```
```
In kernel/cgroup.c (ffffffff81111fdc)
Location: include/linux/sched.h:2738
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroupns_get
```
```
In kernel/cpuset.c (ffffffff8111b663)
Location: include/linux/sched.h:2738
Inline: True
```
```
In kernel/utsname.c (ffffffff8111dafb)
Location: include/linux/sched.h:2738
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_get
```
```
In mm/oom_kill.c (ffffffff811907fc)
Location: include/linux/sched.h:2738
Inline: True
Inline callers:
  - mm/oom_kill.c:find_lock_task_mm
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/mmu_context.c (ffffffff811afba7)
Location: include/linux/sched.h:2738
Inline: True
Inline callers:
  - mm/mmu_context.c:unuse_mm
  - mm/mmu_context.c:use_mm
```
```
In mm/mempolicy.c (ffffffff811e0db9)
Location: include/linux/sched.h:2738
Inline: True
Inline callers:
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
In fs/exec.c (ffffffff8121270d)
Location: include/linux/sched.h:2738
Inline: True
Inline callers:
  - fs/exec.c:get_task_comm
  - fs/exec.c:__set_task_comm
```
```
In fs/file.c (ffffffff8122a53c)
Location: include/linux/sched.h:2738
Inline: True
Inline callers:
  - fs/file.c:get_files_struct
  - fs/file.c:reset_files_struct
  - fs/file.c:exit_files
```
```
In fs/namespace.c (ffffffff8122b65c)
Location: include/linux/sched.h:2738
Inline: True
Inline callers:
  - fs/namespace.c:mntns_get
```
```
In fs/fs_struct.c (ffffffff812414c2)
Location: include/linux/sched.h:2738
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:exit_fs
  - fs/fs_struct.c:unshare_fs_struct
```
```
In fs/proc_namespace.c (ffffffff8124f081)
Location: include/linux/sched.h:2738
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/proc/task_mmu.c (ffffffff81277fc2)
Location: include/linux/sched.h:2738
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (ffffffff8127ac18)
Location: include/linux/sched.h:2738
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
In fs/proc/array.c (ffffffff81280b66)
Location: include/linux/sched.h:2738
Inline: True
Inline callers:
  - fs/proc/array.c:proc_pid_status
```
```
In fs/proc/fd.c (ffffffff81281a33)
Location: include/linux/sched.h:2738
Inline: True
Inline callers:
  - fs/proc/fd.c:tid_fd_revalidate
```
```
In fs/proc/proc_net.c (ffffffff8128646c)
Location: include/linux/sched.h:2738
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_task_net
```
```
In fs/hugetlbfs/inode.c (ffffffff812f5283)
Location: include/linux/sched.h:2738
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
```
```
In ipc/namespace.c (ffffffff8132e94c)
Location: include/linux/sched.h:2738
Inline: True
Inline callers:
  - ipc/namespace.c:ipcns_get
```
```
In security/selinux/hooks.c (ffffffff81346b21)
Location: include/linux/sched.h:2738
Inline: True
```
```
In block/blk-ioc.c (ffffffff813befdc)
Location: include/linux/sched.h:2738
Inline: True
Inline callers:
  - block/blk-ioc.c:exit_io_context
  - block/blk-ioc.c:create_task_io_context
  - block/blk-ioc.c:get_task_io_context
```
```
In block/blk-cgroup.c (ffffffff813d7570)
Location: include/linux/sched.h:2738
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_can_attach
```
```
In drivers/tty/tty_io.c (ffffffff814e36dd)
Location: include/linux/sched.h:2738
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:__do_SAK
```
```
In net/core/net_namespace.c (ffffffff8170fa3c)
Location: include/linux/sched.h:2738
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_get
  - net/core/net_namespace.c:get_net_ns_by_pid
```
```
In net/core/netprio_cgroup.c (ffffffff8173da4b)
Location: include/linux/sched.h:2738
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:net_prio_attach
```
```
In net/core/netclassid_cgroup.c (ffffffff8173de8f)
Location: include/linux/sched.h:2738
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
In init/main.c (ffffffff81f8200f)
Location: include/linux/sched.h:3007
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In kernel/fork.c (ffffffff810827fc)
Location: include/linux/sched.h:3007
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
In kernel/exit.c (ffffffff81086c0c)
Location: include/linux/sched.h:3007
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:mm_update_next_owner
```
```
In kernel/ptrace.c (ffffffff8108de4a)
Location: include/linux/sched.h:3007
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:ptrace_may_access
```
```
In kernel/sys.c (ffffffff81095700)
Location: include/linux/sched.h:3007
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_auxv
  - kernel/sys.c:do_prlimit
  - kernel/sys.c:SyS_old_getrlimit
```
```
In kernel/kthread.c (ffffffff810a440b)
Location: include/linux/sched.h:3007
Inline: True
Inline callers:
  - kernel/kthread.c:kthreadd
```
```
In kernel/nsproxy.c (ffffffff810a49a4)
Location: include/linux/sched.h:3007
Inline: True
Inline callers:
  - kernel/nsproxy.c:switch_task_namespaces
```
```
In kernel/sched/debug.c (ffffffff810cc955)
Location: include/linux/sched.h:3007
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
```
```
In kernel/kcmp.c (ffffffff810f047e)
Location: include/linux/sched.h:3007
Inline: True
Inline callers:
  - kernel/kcmp.c:get_file_raw_ptr
```
```
In kernel/cgroup.c (ffffffff811196fc)
Location: include/linux/sched.h:3007
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroupns_get
```
```
In kernel/cpuset.c (ffffffff8112354b)
Location: include/linux/sched.h:3007
Inline: True
Inline callers:
  - kernel/cpuset.c:cpuset_change_task_nodemask
```
```
In kernel/utsname.c (ffffffff811259cb)
Location: include/linux/sched.h:3007
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_get
```
```
In mm/oom_kill.c (ffffffff811a497c)
Location: include/linux/sched.h:3007
Inline: True
Inline callers:
  - mm/oom_kill.c:find_lock_task_mm
```
```
In mm/mmu_context.c (ffffffff811c90d7)
Location: include/linux/sched.h:3007
Inline: True
Inline callers:
  - mm/mmu_context.c:unuse_mm
  - mm/mmu_context.c:use_mm
```
```
In mm/mempolicy.c (ffffffff81201b90)
Location: include/linux/sched.h:3007
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
```
```
In fs/exec.c (ffffffff8123aa6d)
Location: include/linux/sched.h:3007
Inline: True
Inline callers:
  - fs/exec.c:__set_task_comm
  - fs/exec.c:get_task_comm
```
```
In fs/file.c (ffffffff81252e2a)
Location: include/linux/sched.h:3007
Inline: True
Inline callers:
  - fs/file.c:exit_files
  - fs/file.c:reset_files_struct
  - fs/file.c:get_files_struct
```
```
In fs/namespace.c (ffffffff81253dcc)
Location: include/linux/sched.h:3007
Inline: True
Inline callers:
  - fs/namespace.c:mntns_get
```
```
In fs/fs_struct.c (ffffffff81269af7)
Location: include/linux/sched.h:3007
Inline: True
Inline callers:
  - fs/fs_struct.c:unshare_fs_struct
  - fs/fs_struct.c:exit_fs
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/proc_namespace.c (ffffffff81277801)
Location: include/linux/sched.h:3007
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/coredump.c (ffffffff8129aead)
Location: include/linux/sched.h:3007
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/task_mmu.c (ffffffff812a4322)
Location: include/linux/sched.h:3007
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (ffffffff812a8e8a)
Location: include/linux/sched.h:3007
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
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
```
```
In fs/proc/array.c (ffffffff812adbbd)
Location: include/linux/sched.h:3007
Inline: True
Inline callers:
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
```
```
In fs/proc/fd.c (ffffffff812aeae5)
Location: include/linux/sched.h:3007
Inline: True
Inline callers:
  - fs/proc/fd.c:tid_fd_revalidate
```
```
In fs/proc/proc_net.c (ffffffff812b360c)
Location: include/linux/sched.h:3007
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_task_net
```
```
In fs/hugetlbfs/inode.c (ffffffff81328c95)
Location: include/linux/sched.h:3007
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
```
```
In ipc/namespace.c (ffffffff813635dc)
Location: include/linux/sched.h:3007
Inline: True
Inline callers:
  - ipc/namespace.c:ipcns_get
```
```
In security/selinux/hooks.c (ffffffff8137c2ef)
Location: include/linux/sched.h:3007
Inline: True
```
```
In security/yama/yama_lsm.c (ffffffff813d11c8)
Location: include/linux/sched.h:3007
Inline: True
```
```
In block/blk-ioc.c (ffffffff814030fa)
Location: include/linux/sched.h:3007
Inline: True
Inline callers:
  - block/blk-ioc.c:get_task_io_context
  - block/blk-ioc.c:create_task_io_context
  - block/blk-ioc.c:exit_io_context
```
```
In block/ioprio.c (ffffffff81412081)
Location: include/linux/sched.h:3007
Inline: True
```
```
In block/blk-cgroup.c (ffffffff8141d235)
Location: include/linux/sched.h:3007
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_can_attach
```
```
In drivers/tty/tty_io.c (ffffffff815349db)
Location: include/linux/sched.h:3007
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:__do_SAK
```
```
In net/core/net_namespace.c (ffffffff8177736c)
Location: include/linux/sched.h:3007
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_get
  - net/core/net_namespace.c:get_net_ns_by_pid
```
```
In net/core/netprio_cgroup.c (ffffffff817aa214)
Location: include/linux/sched.h:3007
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:net_prio_attach
```
```
In net/core/netclassid_cgroup.c (ffffffff817aa6e8)
Location: include/linux/sched.h:3007
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
In init/main.c (ffffffff81fbe062)
Location: include/linux/sched.h:3121
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In kernel/fork.c (ffffffff8108725c)
Location: include/linux/sched.h:3121
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
In kernel/exit.c (ffffffff8108bb77)
Location: include/linux/sched.h:3121
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:mm_update_next_owner
```
```
In kernel/ptrace.c (ffffffff8109359a)
Location: include/linux/sched.h:3121
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:ptrace_may_access
```
```
In kernel/sys.c (ffffffff8109a6f0)
Location: include/linux/sched.h:3121
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_auxv
  - kernel/sys.c:do_prlimit
  - kernel/sys.c:SyS_old_getrlimit
```
```
In kernel/kthread.c (ffffffff810a9d5b)
Location: include/linux/sched.h:3121
Inline: True
Inline callers:
  - kernel/kthread.c:kthreadd
```
```
In kernel/nsproxy.c (ffffffff810aa604)
Location: include/linux/sched.h:3121
Inline: True
Inline callers:
  - kernel/nsproxy.c:switch_task_namespaces
```
```
In kernel/sched/debug.c (ffffffff810d2975)
Location: include/linux/sched.h:3121
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
```
```
In kernel/kcmp.c (ffffffff810f75de)
Location: include/linux/sched.h:3121
Inline: True
Inline callers:
  - kernel/kcmp.c:get_file_raw_ptr
```
```
In kernel/cgroup.c (ffffffff81120ecc)
Location: include/linux/sched.h:3121
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroupns_get
```
```
In kernel/cpuset.c (ffffffff8112b22d)
Location: include/linux/sched.h:3121
Inline: True
Inline callers:
  - kernel/cpuset.c:cpuset_change_task_nodemask
```
```
In kernel/utsname.c (ffffffff8112f3cb)
Location: include/linux/sched.h:3121
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_get
```
```
In mm/oom_kill.c (ffffffff811b5554)
Location: include/linux/sched.h:3121
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:find_lock_task_mm
```
```
In mm/mmu_context.c (ffffffff811d91b7)
Location: include/linux/sched.h:3121
Inline: True
Inline callers:
  - mm/mmu_context.c:unuse_mm
  - mm/mmu_context.c:use_mm
```
```
In mm/mempolicy.c (ffffffff81213699)
Location: include/linux/sched.h:3121
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
```
```
In fs/exec.c (ffffffff8124d81d)
Location: include/linux/sched.h:3121
Inline: True
Inline callers:
  - fs/exec.c:__set_task_comm
  - fs/exec.c:get_task_comm
```
```
In fs/file.c (ffffffff8126609a)
Location: include/linux/sched.h:3121
Inline: True
Inline callers:
  - fs/file.c:exit_files
  - fs/file.c:reset_files_struct
  - fs/file.c:get_files_struct
```
```
In fs/namespace.c (ffffffff8126709c)
Location: include/linux/sched.h:3121
Inline: True
Inline callers:
  - fs/namespace.c:mntns_get
```
```
In fs/fs_struct.c (ffffffff8127caa7)
Location: include/linux/sched.h:3121
Inline: True
Inline callers:
  - fs/fs_struct.c:unshare_fs_struct
  - fs/fs_struct.c:exit_fs
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/proc_namespace.c (ffffffff8128b4e1)
Location: include/linux/sched.h:3121
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/coredump.c (ffffffff812afa67)
Location: include/linux/sched.h:3121
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/task_mmu.c (ffffffff812b981f)
Location: include/linux/sched.h:3121
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (ffffffff812be995)
Location: include/linux/sched.h:3121
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
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
```
```
In fs/proc/array.c (ffffffff812c34c3)
Location: include/linux/sched.h:3121
Inline: True
Inline callers:
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
```
```
In fs/proc/fd.c (ffffffff812c44b5)
Location: include/linux/sched.h:3121
Inline: True
Inline callers:
  - fs/proc/fd.c:tid_fd_revalidate
```
```
In fs/proc/proc_net.c (ffffffff812c8e5c)
Location: include/linux/sched.h:3121
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_task_net
```
```
In fs/hugetlbfs/inode.c (ffffffff8133e9d5)
Location: include/linux/sched.h:3121
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
```
```
In ipc/namespace.c (ffffffff81379dac)
Location: include/linux/sched.h:3121
Inline: True
Inline callers:
  - ipc/namespace.c:ipcns_get
```
```
In security/selinux/hooks.c (ffffffff81392dab)
Location: include/linux/sched.h:3121
Inline: True
```
```
In security/yama/yama_lsm.c (ffffffff813e88f8)
Location: include/linux/sched.h:3121
Inline: True
```
```
In block/blk-ioc.c (ffffffff8141ce2a)
Location: include/linux/sched.h:3121
Inline: True
Inline callers:
  - block/blk-ioc.c:get_task_io_context
  - block/blk-ioc.c:create_task_io_context
  - block/blk-ioc.c:exit_io_context
```
```
In block/ioprio.c (ffffffff8142d4e1)
Location: include/linux/sched.h:3121
Inline: True
```
```
In block/blk-cgroup.c (ffffffff81438805)
Location: include/linux/sched.h:3121
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_can_attach
```
```
In drivers/tty/tty_io.c (ffffffff8156110b)
Location: include/linux/sched.h:3121
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:__do_SAK
```
```
In net/core/net_namespace.c (ffffffff817a435c)
Location: include/linux/sched.h:3121
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_get
  - net/core/net_namespace.c:get_net_ns_by_pid
```
```
In net/core/netprio_cgroup.c (ffffffff817d8d54)
Location: include/linux/sched.h:3121
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:net_prio_attach
```
```
In net/core/netclassid_cgroup.c (ffffffff817d923a)
Location: include/linux/sched.h:3121
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
In init/main.c (ffffffff8209e14c)
Location: include/linux/sched/task.h:129
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In kernel/fork.c (ffffffff810840db)
Location: include/linux/sched/task.h:129
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
In kernel/exit.c (ffffffff81088d10)
Location: include/linux/sched/task.h:129
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:mm_update_next_owner
```
```
In kernel/ptrace.c (ffffffff810906a8)
Location: include/linux/sched/task.h:129
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:ptrace_may_access
```
```
In kernel/sys.c (ffffffff8109795b)
Location: include/linux/sched/task.h:129
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_auxv
  - kernel/sys.c:do_prlimit
  - kernel/sys.c:compat_SyS_old_getrlimit
  - kernel/sys.c:SyS_old_getrlimit
```
```
In kernel/kthread.c (ffffffff810a697b)
Location: include/linux/sched/task.h:129
Inline: True
Inline callers:
  - kernel/kthread.c:kthreadd
```
```
In kernel/nsproxy.c (ffffffff810a7164)
Location: include/linux/sched/task.h:129
Inline: True
Inline callers:
  - kernel/nsproxy.c:switch_task_namespaces
```
```
In kernel/sched/debug.c (ffffffff810d1ac7)
Location: include/linux/sched/task.h:129
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
```
```
In kernel/kcmp.c (ffffffff810f93ce)
Location: include/linux/sched/task.h:129
Inline: True
Inline callers:
  - kernel/kcmp.c:get_file_raw_ptr
```
```
In kernel/cgroup/namespace.c (ffffffff81128c4c)
Location: include/linux/sched/task.h:129
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:cgroupns_get
```
```
In kernel/cgroup/cpuset.c (ffffffff8112c55b)
Location: include/linux/sched/task.h:129
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
```
In kernel/utsname.c (ffffffff81130a6c)
Location: include/linux/sched/task.h:129
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_get
```
```
In kernel/pid_namespace.c (ffffffff8113275b)
Location: include/linux/sched/task.h:129
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_for_children_get
```
```
In mm/oom_kill.c (ffffffff811bd264)
Location: include/linux/sched/task.h:129
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:find_lock_task_mm
```
```
In mm/mmu_context.c (ffffffff811e1fc7)
Location: include/linux/sched/task.h:129
Inline: True
Inline callers:
  - mm/mmu_context.c:unuse_mm
  - mm/mmu_context.c:use_mm
```
```
In mm/mempolicy.c (ffffffff8121e9af)
Location: include/linux/sched/task.h:129
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
```
```
In fs/exec.c (ffffffff812597df)
Location: include/linux/sched/task.h:129
Inline: True
Inline callers:
  - fs/exec.c:__set_task_comm
  - fs/exec.c:get_task_comm
```
```
In fs/file.c (ffffffff8127387a)
Location: include/linux/sched/task.h:129
Inline: True
Inline callers:
  - fs/file.c:exit_files
  - fs/file.c:reset_files_struct
  - fs/file.c:get_files_struct
```
```
In fs/namespace.c (ffffffff812748ec)
Location: include/linux/sched/task.h:129
Inline: True
Inline callers:
  - fs/namespace.c:mntns_get
```
```
In fs/fs_struct.c (ffffffff8128a157)
Location: include/linux/sched/task.h:129
Inline: True
Inline callers:
  - fs/fs_struct.c:unshare_fs_struct
  - fs/fs_struct.c:exit_fs
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/proc_namespace.c (ffffffff812982e1)
Location: include/linux/sched/task.h:129
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/coredump.c (ffffffff812bccab)
Location: include/linux/sched/task.h:129
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/task_mmu.c (ffffffff812c7119)
Location: include/linux/sched/task.h:129
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (ffffffff812cb8c5)
Location: include/linux/sched/task.h:129
Inline: True
Inline callers:
  - fs/proc/base.c:timerslack_ns_show
  - fs/proc/base.c:timerslack_ns_write
  - fs/proc/base.c:task_dump_owner
  - fs/proc/base.c:comm_show
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
```
```
In fs/proc/array.c (ffffffff812d0749)
Location: include/linux/sched/task.h:129
Inline: True
Inline callers:
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
```
```
In fs/proc/proc_net.c (ffffffff812d615c)
Location: include/linux/sched/task.h:129
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_task_net
```
```
In fs/hugetlbfs/inode.c (ffffffff813535aa)
Location: include/linux/sched/task.h:129
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
```
```
In ipc/namespace.c (ffffffff8138d9ac)
Location: include/linux/sched/task.h:129
Inline: True
Inline callers:
  - ipc/namespace.c:ipcns_get
```
```
In security/selinux/hooks.c (ffffffff813a8f84)
Location: include/linux/sched/task.h:129
Inline: True
```
```
In security/yama/yama_lsm.c (ffffffff813f4b08)
Location: include/linux/sched/task.h:129
Inline: True
```
```
In block/blk-ioc.c (ffffffff8142ae8a)
Location: include/linux/sched/task.h:129
Inline: True
Inline callers:
  - block/blk-ioc.c:get_task_io_context
  - block/blk-ioc.c:create_task_io_context
  - block/blk-ioc.c:exit_io_context
```
```
In block/ioprio.c (ffffffff8143a7c1)
Location: include/linux/sched/task.h:129
Inline: True
```
```
In block/blk-cgroup.c (ffffffff81445f93)
Location: include/linux/sched/task.h:129
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_can_attach
```
```
In drivers/tty/tty_io.c (ffffffff815743e0)
Location: include/linux/sched/task.h:129
Inline: True
```
```
In net/core/net_namespace.c (ffffffff817c24cc)
Location: include/linux/sched/task.h:129
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_get
  - net/core/net_namespace.c:get_net_ns_by_pid
```
```
In net/core/netprio_cgroup.c (ffffffff817f7f74)
Location: include/linux/sched/task.h:129
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:net_prio_attach
```
```
In net/core/netclassid_cgroup.c (ffffffff817f844a)
Location: include/linux/sched/task.h:129
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
In init/main.c (ffffffff826a4119)
Location: include/linux/sched/task.h:129
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In kernel/fork.c (ffffffff8108a9cb)
Location: include/linux/sched/task.h:129
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
In kernel/exit.c (ffffffff8108fa56)
Location: include/linux/sched/task.h:129
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:mm_update_next_owner
```
```
In kernel/ptrace.c (ffffffff81097518)
Location: include/linux/sched/task.h:129
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:ptrace_may_access
```
```
In kernel/sys.c (ffffffff8109e64b)
Location: include/linux/sched/task.h:129
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_auxv
  - kernel/sys.c:do_prlimit
  - kernel/sys.c:compat_SyS_old_getrlimit
  - kernel/sys.c:SyS_old_getrlimit
```
```
In kernel/kthread.c (ffffffff810ad06b)
Location: include/linux/sched/task.h:129
Inline: True
Inline callers:
  - kernel/kthread.c:kthreadd
```
```
In kernel/nsproxy.c (ffffffff810ad8e4)
Location: include/linux/sched/task.h:129
Inline: True
Inline callers:
  - kernel/nsproxy.c:switch_task_namespaces
```
```
In kernel/sched/debug.c (ffffffff810d9668)
Location: include/linux/sched/task.h:129
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
```
```
In kernel/kcmp.c (ffffffff81103e3d)
Location: include/linux/sched/task.h:129
Inline: True
Inline callers:
  - kernel/kcmp.c:get_file_raw_ptr
```
```
In kernel/cgroup/namespace.c (ffffffff81135a2c)
Location: include/linux/sched/task.h:129
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:cgroupns_get
```
```
In kernel/cgroup/cpuset.c (ffffffff8113938b)
Location: include/linux/sched/task.h:129
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
```
In kernel/utsname.c (ffffffff8113d9bc)
Location: include/linux/sched/task.h:129
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_get
```
```
In kernel/pid_namespace.c (ffffffff8113f79b)
Location: include/linux/sched/task.h:129
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_for_children_get
```
```
In mm/oom_kill.c (ffffffff811d1e74)
Location: include/linux/sched/task.h:129
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:find_lock_task_mm
```
```
In mm/mmu_context.c (ffffffff811f7f67)
Location: include/linux/sched/task.h:129
Inline: True
Inline callers:
  - mm/mmu_context.c:unuse_mm
  - mm/mmu_context.c:use_mm
```
```
In mm/mempolicy.c (ffffffff81239bcf)
Location: include/linux/sched/task.h:129
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
```
```
In fs/exec.c (ffffffff8127ba3f)
Location: include/linux/sched/task.h:129
Inline: True
Inline callers:
  - fs/exec.c:__set_task_comm
  - fs/exec.c:__get_task_comm
```
```
In fs/file.c (ffffffff812961aa)
Location: include/linux/sched/task.h:129
Inline: True
Inline callers:
  - fs/file.c:exit_files
  - fs/file.c:reset_files_struct
  - fs/file.c:get_files_struct
```
```
In fs/namespace.c (ffffffff8129721c)
Location: include/linux/sched/task.h:129
Inline: True
Inline callers:
  - fs/namespace.c:mntns_get
```
```
In fs/fs_struct.c (ffffffff812acc97)
Location: include/linux/sched/task.h:129
Inline: True
Inline callers:
  - fs/fs_struct.c:unshare_fs_struct
  - fs/fs_struct.c:exit_fs
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/proc_namespace.c (ffffffff812bb5e1)
Location: include/linux/sched/task.h:129
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/coredump.c (ffffffff812e0576)
Location: include/linux/sched/task.h:129
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/task_mmu.c (ffffffff812ead19)
Location: include/linux/sched/task.h:129
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (ffffffff812f02f5)
Location: include/linux/sched/task.h:129
Inline: True
Inline callers:
  - fs/proc/base.c:timerslack_ns_show
  - fs/proc/base.c:timerslack_ns_write
  - fs/proc/base.c:task_dump_owner
  - fs/proc/base.c:comm_show
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
```
```
In fs/proc/array.c (ffffffff812f4f7b)
Location: include/linux/sched/task.h:129
Inline: True
Inline callers:
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
```
```
In fs/proc/proc_net.c (ffffffff812fa99c)
Location: include/linux/sched/task.h:129
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_task_net
```
```
In fs/hugetlbfs/inode.c (ffffffff813781ca)
Location: include/linux/sched/task.h:129
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
```
```
In ipc/namespace.c (ffffffff813b2dcc)
Location: include/linux/sched/task.h:129
Inline: True
Inline callers:
  - ipc/namespace.c:ipcns_get
```
```
In security/selinux/hooks.c (ffffffff813ceeb4)
Location: include/linux/sched/task.h:129
Inline: True
```
```
In security/yama/yama_lsm.c (ffffffff8141cea8)
Location: include/linux/sched/task.h:129
Inline: True
```
```
In block/blk-ioc.c (ffffffff8145607a)
Location: include/linux/sched/task.h:129
Inline: True
Inline callers:
  - block/blk-ioc.c:get_task_io_context
  - block/blk-ioc.c:create_task_io_context
  - block/blk-ioc.c:exit_io_context
```
```
In block/ioprio.c (ffffffff814667e1)
Location: include/linux/sched/task.h:129
Inline: True
```
```
In block/blk-cgroup.c (ffffffff81472af3)
Location: include/linux/sched/task.h:129
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_can_attach
```
```
In drivers/tty/tty_io.c (ffffffff815d7560)
Location: include/linux/sched/task.h:129
Inline: True
```
```
In net/core/net_namespace.c (ffffffff8183bf1c)
Location: include/linux/sched/task.h:129
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_get
  - net/core/net_namespace.c:get_net_ns_by_pid
```
```
In net/core/netprio_cgroup.c (ffffffff81875834)
Location: include/linux/sched/task.h:129
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:net_prio_attach
```
```
In net/core/netclassid_cgroup.c (ffffffff81875d0f)
Location: include/linux/sched/task.h:129
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
In init/main.c (ffffffff826cd257)
Location: include/linux/sched/task.h:143
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff8108659a)
Location: include/linux/sched/task.h:143
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_switch_mm
```
```
In kernel/fork.c (ffffffff8108e22c)
Location: include/linux/sched/task.h:143
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
In kernel/exit.c (ffffffff810935bc)
Location: include/linux/sched/task.h:143
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:mm_update_next_owner
```
```
In kernel/ptrace.c (ffffffff8109a9e3)
Location: include/linux/sched/task.h:143
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:ptrace_may_access
```
```
In kernel/sys.c (ffffffff810a5215)
Location: include/linux/sched/task.h:143
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
In kernel/kthread.c (ffffffff810b3dfe)
Location: include/linux/sched/task.h:143
Inline: True
Inline callers:
  - kernel/kthread.c:kthreadd
```
```
In kernel/nsproxy.c (ffffffff810b4661)
Location: include/linux/sched/task.h:143
Inline: True
Inline callers:
  - kernel/nsproxy.c:switch_task_namespaces
```
```
In kernel/sched/debug.c (ffffffff810e067d)
Location: include/linux/sched/task.h:143
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
```
```
In kernel/kcmp.c (ffffffff8110e8d5)
Location: include/linux/sched/task.h:143
Inline: True
Inline callers:
  - kernel/kcmp.c:get_file_raw_ptr
```
```
In kernel/cgroup/namespace.c (ffffffff81144295)
Location: include/linux/sched/task.h:143
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:cgroupns_get
```
```
In kernel/cgroup/cpuset.c (ffffffff81148455)
Location: include/linux/sched/task.h:143
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
```
In kernel/utsname.c (ffffffff8114c355)
Location: include/linux/sched/task.h:143
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_get
```
```
In kernel/pid_namespace.c (ffffffff8114dfe5)
Location: include/linux/sched/task.h:143
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_for_children_get
```
```
In mm/oom_kill.c (ffffffff811f2c74)
Location: include/linux/sched/task.h:143
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:find_lock_task_mm
```
```
In mm/mmu_context.c (ffffffff8121921a)
Location: include/linux/sched/task.h:143
Inline: True
Inline callers:
  - mm/mmu_context.c:unuse_mm
  - mm/mmu_context.c:use_mm
```
```
In mm/mempolicy.c (ffffffff8125d1b0)
Location: include/linux/sched/task.h:143
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
```
```
In fs/exec.c (ffffffff812a18d8)
Location: include/linux/sched/task.h:143
Inline: True
Inline callers:
  - fs/exec.c:finalize_exec
  - fs/exec.c:__set_task_comm
  - fs/exec.c:__get_task_comm
```
```
In fs/file.c (ffffffff812bc644)
Location: include/linux/sched/task.h:143
Inline: True
Inline callers:
  - fs/file.c:exit_files
  - fs/file.c:reset_files_struct
  - fs/file.c:get_files_struct
```
```
In fs/namespace.c (ffffffff812bdca5)
Location: include/linux/sched/task.h:143
Inline: True
Inline callers:
  - fs/namespace.c:mntns_get
```
```
In fs/fs_struct.c (ffffffff812d4867)
Location: include/linux/sched/task.h:143
Inline: True
Inline callers:
  - fs/fs_struct.c:unshare_fs_struct
  - fs/fs_struct.c:exit_fs
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/proc_namespace.c (ffffffff812e418a)
Location: include/linux/sched/task.h:143
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/coredump.c (ffffffff8130c7ab)
Location: include/linux/sched/task.h:143
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/task_mmu.c (ffffffff813188cd)
Location: include/linux/sched/task.h:143
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (ffffffff8131d24d)
Location: include/linux/sched/task.h:143
Inline: True
Inline callers:
  - fs/proc/base.c:timerslack_ns_show
  - fs/proc/base.c:timerslack_ns_write
  - fs/proc/base.c:task_dump_owner
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
```
```
In fs/proc/array.c (ffffffff81322345)
Location: include/linux/sched/task.h:143
Inline: True
Inline callers:
  - fs/proc/array.c:proc_pid_status
```
```
In fs/proc/proc_net.c (ffffffff81327f7b)
Location: include/linux/sched/task.h:143
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_task_net
```
```
In fs/hugetlbfs/inode.c (ffffffff813a6bcd)
Location: include/linux/sched/task.h:143
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
```
```
In ipc/namespace.c (ffffffff813e3505)
Location: include/linux/sched/task.h:143
Inline: True
Inline callers:
  - ipc/namespace.c:ipcns_get
```
```
In security/selinux/hooks.c (ffffffff814024e8)
Location: include/linux/sched/task.h:143
Inline: True
```
```
In security/yama/yama_lsm.c (ffffffff8144f10a)
Location: include/linux/sched/task.h:143
Inline: True
```
```
In block/blk-ioc.c (ffffffff8148942a)
Location: include/linux/sched/task.h:143
Inline: True
Inline callers:
  - block/blk-ioc.c:create_task_io_context
  - block/blk-ioc.c:exit_io_context
```
```
In block/ioprio.c (ffffffff8149a131)
Location: include/linux/sched/task.h:143
Inline: True
```
```
In block/blk-cgroup.c (ffffffff814a7a83)
Location: include/linux/sched/task.h:143
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_can_attach
```
```
In drivers/tty/tty_io.c (ffffffff816109ec)
Location: include/linux/sched/task.h:143
Inline: True
```
```
In net/core/net_namespace.c (ffffffff81886fb5)
Location: include/linux/sched/task.h:143
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_get
  - net/core/net_namespace.c:get_net_ns_by_pid
```
```
In net/core/netprio_cgroup.c (ffffffff818c7349)
Location: include/linux/sched/task.h:143
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:net_prio_attach
```
```
In net/core/netclassid_cgroup.c (ffffffff818c760f)
Location: include/linux/sched/task.h:143
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
In init/main.c (ffffffff8288322d)
Location: include/linux/sched/task.h:145
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In kernel/fork.c (ffffffff810964bc)
Location: include/linux/sched/task.h:145
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
In kernel/exit.c (ffffffff8109b87b)
Location: include/linux/sched/task.h:145
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:mm_update_next_owner
```
```
In kernel/ptrace.c (ffffffff810a2c13)
Location: include/linux/sched/task.h:145
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:ptrace_may_access
```
```
In kernel/sys.c (ffffffff810adec5)
Location: include/linux/sched/task.h:145
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
In kernel/kthread.c (ffffffff810bcf4e)
Location: include/linux/sched/task.h:145
Inline: True
Inline callers:
  - kernel/kthread.c:kthreadd
```
```
In kernel/nsproxy.c (ffffffff810bd7b1)
Location: include/linux/sched/task.h:145
Inline: True
Inline callers:
  - kernel/nsproxy.c:switch_task_namespaces
```
```
In kernel/sched/debug.c (ffffffff810eae33)
Location: include/linux/sched/task.h:145
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
```
```
In kernel/kcmp.c (ffffffff81119e55)
Location: include/linux/sched/task.h:145
Inline: True
Inline callers:
  - kernel/kcmp.c:get_file_raw_ptr
```
```
In kernel/cgroup/namespace.c (ffffffff8114fda5)
Location: include/linux/sched/task.h:145
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:cgroupns_get
```
```
In kernel/cgroup/cpuset.c (ffffffff81153f75)
Location: include/linux/sched/task.h:145
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
```
In kernel/utsname.c (ffffffff81158f65)
Location: include/linux/sched/task.h:145
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_get
```
```
In kernel/pid_namespace.c (ffffffff8115ad95)
Location: include/linux/sched/task.h:145
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_for_children_get
```
```
In mm/oom_kill.c (ffffffff81204c94)
Location: include/linux/sched/task.h:145
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:find_lock_task_mm
```
```
In mm/mmu_context.c (ffffffff8122c17a)
Location: include/linux/sched/task.h:145
Inline: True
Inline callers:
  - mm/mmu_context.c:unuse_mm
  - mm/mmu_context.c:use_mm
```
```
In mm/mempolicy.c (ffffffff81271a70)
Location: include/linux/sched/task.h:145
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
```
```
In fs/exec.c (ffffffff812b6e48)
Location: include/linux/sched/task.h:145
Inline: True
Inline callers:
  - fs/exec.c:finalize_exec
  - fs/exec.c:__set_task_comm
  - fs/exec.c:__get_task_comm
```
```
In fs/file.c (ffffffff812d1904)
Location: include/linux/sched/task.h:145
Inline: True
Inline callers:
  - fs/file.c:exit_files
  - fs/file.c:reset_files_struct
  - fs/file.c:get_files_struct
```
```
In fs/namespace.c (ffffffff812d3235)
Location: include/linux/sched/task.h:145
Inline: True
Inline callers:
  - fs/namespace.c:mntns_get
```
```
In fs/fs_struct.c (ffffffff812e9c37)
Location: include/linux/sched/task.h:145
Inline: True
Inline callers:
  - fs/fs_struct.c:unshare_fs_struct
  - fs/fs_struct.c:exit_fs
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/proc_namespace.c (ffffffff812f8e0a)
Location: include/linux/sched/task.h:145
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/coredump.c (ffffffff813220e0)
Location: include/linux/sched/task.h:145
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/task_mmu.c (ffffffff8132f6e5)
Location: include/linux/sched/task.h:145
Inline: True
```
```
In fs/proc/base.c (ffffffff8133446b)
Location: include/linux/sched/task.h:145
Inline: True
Inline callers:
  - fs/proc/base.c:timerslack_ns_show
  - fs/proc/base.c:timerslack_ns_write
  - fs/proc/base.c:task_dump_owner
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
```
```
In fs/proc/array.c (ffffffff81339455)
Location: include/linux/sched/task.h:145
Inline: True
Inline callers:
  - fs/proc/array.c:proc_pid_status
```
```
In fs/proc/proc_net.c (ffffffff8133f15f)
Location: include/linux/sched/task.h:145
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_task_net
```
```
In fs/hugetlbfs/inode.c (ffffffff813bf9f3)
Location: include/linux/sched/task.h:145
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
```
```
In ipc/namespace.c (ffffffff813fde85)
Location: include/linux/sched/task.h:145
Inline: True
Inline callers:
  - ipc/namespace.c:ipcns_get
```
```
In security/selinux/hooks.c (ffffffff8141ad62)
Location: include/linux/sched/task.h:145
Inline: True
```
```
In security/yama/yama_lsm.c (ffffffff8146bf8a)
Location: include/linux/sched/task.h:145
Inline: True
```
```
In block/blk-ioc.c (ffffffff814a330a)
Location: include/linux/sched/task.h:145
Inline: True
Inline callers:
  - block/blk-ioc.c:get_task_io_context
  - block/blk-ioc.c:create_task_io_context
  - block/blk-ioc.c:exit_io_context
```
```
In block/ioprio.c (ffffffff814b4441)
Location: include/linux/sched/task.h:145
Inline: True
```
```
In block/blk-cgroup.c (ffffffff814c17b3)
Location: include/linux/sched/task.h:145
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_can_attach
```
```
In drivers/tty/tty_io.c (ffffffff8162d72c)
Location: include/linux/sched/task.h:145
Inline: True
```
```
In net/core/net_namespace.c (ffffffff818a76c5)
Location: include/linux/sched/task.h:145
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_get
  - net/core/net_namespace.c:get_net_ns_by_pid
```
```
In net/core/netprio_cgroup.c (ffffffff818f0489)
Location: include/linux/sched/task.h:145
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:net_prio_attach
```
```
In net/core/netclassid_cgroup.c (ffffffff818f074f)
Location: include/linux/sched/task.h:145
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
In init/main.c (ffffffff8289a283)
Location: include/linux/sched/task.h:162
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In kernel/fork.c (ffffffff8109aa07)
Location: include/linux/sched/task.h:162
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
In kernel/exit.c (ffffffff8109feea)
Location: include/linux/sched/task.h:162
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:mm_update_next_owner
```
```
In kernel/ptrace.c (ffffffff810a78db)
Location: include/linux/sched/task.h:162
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:ptrace_may_access
```
```
In kernel/sys.c (ffffffff810b3c15)
Location: include/linux/sched/task.h:162
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
In kernel/kthread.c (ffffffff810c2e1e)
Location: include/linux/sched/task.h:162
Inline: True
Inline callers:
  - kernel/kthread.c:kthreadd
```
```
In kernel/nsproxy.c (ffffffff810c3800)
Location: include/linux/sched/task.h:162
Inline: True
Inline callers:
  - kernel/nsproxy.c:switch_task_namespaces
```
```
In kernel/sched/debug.c (ffffffff810f1c51)
Location: include/linux/sched/task.h:162
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
```
```
In kernel/kcmp.c (ffffffff811248a5)
Location: include/linux/sched/task.h:162
Inline: True
Inline callers:
  - kernel/kcmp.c:get_file_raw_ptr
```
```
In kernel/cgroup/namespace.c (ffffffff8115bca5)
Location: include/linux/sched/task.h:162
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:cgroupns_get
```
```
In kernel/cgroup/cpuset.c (ffffffff811604c5)
Location: include/linux/sched/task.h:162
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
```
In kernel/utsname.c (ffffffff81165695)
Location: include/linux/sched/task.h:162
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_get
```
```
In kernel/pid_namespace.c (ffffffff81167455)
Location: include/linux/sched/task.h:162
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_for_children_get
```
```
In mm/oom_kill.c (ffffffff8121c2d7)
Location: include/linux/sched/task.h:162
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:find_lock_task_mm
```
```
In mm/mmu_context.c (ffffffff8123be8b)
Location: include/linux/sched/task.h:162
Inline: True
Inline callers:
  - mm/mmu_context.c:unuse_mm
  - mm/mmu_context.c:use_mm
```
```
In mm/mempolicy.c (ffffffff8128d08c)
Location: include/linux/sched/task.h:162
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
```
```
In fs/exec.c (ffffffff812d3ba8)
Location: include/linux/sched/task.h:162
Inline: True
Inline callers:
  - fs/exec.c:finalize_exec
  - fs/exec.c:__set_task_comm
  - fs/exec.c:__get_task_comm
```
```
In fs/file.c (ffffffff812ee904)
Location: include/linux/sched/task.h:162
Inline: True
Inline callers:
  - fs/file.c:exit_files
  - fs/file.c:reset_files_struct
  - fs/file.c:get_files_struct
```
```
In fs/namespace.c (ffffffff812f03f5)
Location: include/linux/sched/task.h:162
Inline: True
Inline callers:
  - fs/namespace.c:mntns_get
```
```
In fs/fs_struct.c (ffffffff81308637)
Location: include/linux/sched/task.h:162
Inline: True
Inline callers:
  - fs/fs_struct.c:unshare_fs_struct
  - fs/fs_struct.c:exit_fs
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/proc_namespace.c (ffffffff8131942a)
Location: include/linux/sched/task.h:162
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/coredump.c (ffffffff8134a003)
Location: include/linux/sched/task.h:162
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/task_mmu.c (ffffffff813574e5)
Location: include/linux/sched/task.h:162
Inline: True
```
```
In fs/proc/base.c (ffffffff8135c2ef)
Location: include/linux/sched/task.h:162
Inline: True
Inline callers:
  - fs/proc/base.c:timerslack_ns_show
  - fs/proc/base.c:timerslack_ns_write
  - fs/proc/base.c:task_dump_owner
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
```
```
In fs/proc/array.c (ffffffff81360451)
Location: include/linux/sched/task.h:162
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In fs/proc/proc_net.c (ffffffff81367490)
Location: include/linux/sched/task.h:162
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_task_net
```
```
In fs/hugetlbfs/inode.c (ffffffff813ea229)
Location: include/linux/sched/task.h:162
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
```
```
In ipc/namespace.c (ffffffff8142a4b5)
Location: include/linux/sched/task.h:162
Inline: True
Inline callers:
  - ipc/namespace.c:ipcns_get
```
```
In security/selinux/hooks.c (ffffffff81448852)
Location: include/linux/sched/task.h:162
Inline: True
```
```
In security/yama/yama_lsm.c (ffffffff81498f8b)
Location: include/linux/sched/task.h:162
Inline: True
```
```
In block/blk-ioc.c (ffffffff814d13da)
Location: include/linux/sched/task.h:162
Inline: True
Inline callers:
  - block/blk-ioc.c:get_task_io_context
  - block/blk-ioc.c:create_task_io_context
  - block/blk-ioc.c:exit_io_context
```
```
In block/ioprio.c (ffffffff814e2963)
Location: include/linux/sched/task.h:162
Inline: True
```
```
In block/blk-cgroup.c (ffffffff814f0170)
Location: include/linux/sched/task.h:162
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_can_attach
```
```
In drivers/tty/tty_io.c (ffffffff8166135a)
Location: include/linux/sched/task.h:162
Inline: True
```
```
In net/core/net_namespace.c (ffffffff818f2bb5)
Location: include/linux/sched/task.h:162
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_get
  - net/core/net_namespace.c:get_net_ns_by_pid
```
```
In net/core/netprio_cgroup.c (ffffffff81941ddf)
Location: include/linux/sched/task.h:162
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:net_prio_attach
```
```
In net/core/netclassid_cgroup.c (ffffffff819420a6)
Location: include/linux/sched/task.h:162
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
In init/main.c (ffffffff8289d268)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In kernel/fork.c (ffffffff810a0fc7)
Location: include/linux/sched/task.h:166
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
In kernel/exit.c (ffffffff810a6568)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:mm_update_next_owner
```
```
In kernel/ptrace.c (ffffffff810adefb)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:ptrace_may_access
```
```
In kernel/sys.c (ffffffff810ba205)
Location: include/linux/sched/task.h:166
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
In kernel/kthread.c (ffffffff810c93ee)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - kernel/kthread.c:kthreadd
```
```
In kernel/nsproxy.c (ffffffff810cc910)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - kernel/nsproxy.c:switch_task_namespaces
```
```
In kernel/sched/debug.c (ffffffff810fd911)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
```
```
In kernel/kcmp.c (ffffffff81130865)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - kernel/kcmp.c:get_file_raw_ptr
```
```
In kernel/cgroup/namespace.c (ffffffff811678c5)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:cgroupns_get
```
```
In kernel/cgroup/cpuset.c (ffffffff8116c195)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
```
In kernel/utsname.c (ffffffff81171555)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_get
```
```
In kernel/pid_namespace.c (ffffffff81173315)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_for_children_get
```
```
In mm/oom_kill.c (ffffffff81229ca7)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:find_lock_task_mm
```
```
In mm/mmu_context.c (ffffffff8124a2db)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - mm/mmu_context.c:unuse_mm
  - mm/mmu_context.c:use_mm
```
```
In mm/mempolicy.c (ffffffff8129ccbc)
Location: include/linux/sched/task.h:166
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
```
```
In fs/exec.c (ffffffff812e5738)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - fs/exec.c:finalize_exec
  - fs/exec.c:__set_task_comm
  - fs/exec.c:__get_task_comm
```
```
In fs/file.c (ffffffff813003c4)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - fs/file.c:exit_files
  - fs/file.c:reset_files_struct
  - fs/file.c:get_files_struct
```
```
In fs/namespace.c (ffffffff81301f95)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - fs/namespace.c:mntns_get
```
```
In fs/fs_struct.c (ffffffff8131b6d7)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - fs/fs_struct.c:unshare_fs_struct
  - fs/fs_struct.c:exit_fs
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/proc_namespace.c (ffffffff8132c25a)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/io_uring.c (ffffffff81342f61)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In fs/coredump.c (ffffffff813622a3)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/task_mmu.c (ffffffff8136f715)
Location: include/linux/sched/task.h:166
Inline: True
```
```
In fs/proc/base.c (ffffffff8137474f)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - fs/proc/base.c:timerslack_ns_show
  - fs/proc/base.c:timerslack_ns_write
  - fs/proc/base.c:task_dump_owner
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
```
```
In fs/proc/array.c (ffffffff813786b1)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In fs/proc/proc_net.c (ffffffff8137f710)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_task_net
```
```
In fs/hugetlbfs/inode.c (ffffffff814042c9)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
```
```
In ipc/namespace.c (ffffffff814441e5)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - ipc/namespace.c:ipcns_get
```
```
In security/selinux/hooks.c (ffffffff814623e2)
Location: include/linux/sched/task.h:166
Inline: True
```
```
In security/yama/yama_lsm.c (ffffffff814b2ebb)
Location: include/linux/sched/task.h:166
Inline: True
```
```
In block/blk-ioc.c (ffffffff814ea78a)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - block/blk-ioc.c:get_task_io_context
  - block/blk-ioc.c:create_task_io_context
  - block/blk-ioc.c:exit_io_context
```
```
In block/ioprio.c (ffffffff814fbd23)
Location: include/linux/sched/task.h:166
Inline: True
```
```
In block/blk-cgroup.c (ffffffff81509620)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_can_attach
```
```
In drivers/tty/tty_io.c (ffffffff816839aa)
Location: include/linux/sched/task.h:166
Inline: True
```
```
In net/core/net_namespace.c (ffffffff81924b15)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_get
  - net/core/net_namespace.c:get_net_ns_by_pid
```
```
In net/core/netprio_cgroup.c (ffffffff81976cef)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:net_prio_attach
```
```
In net/core/netclassid_cgroup.c (ffffffff81976f08)
Location: include/linux/sched/task.h:166
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
In init/main.c (ffffffff82cc38b2)
Location: include/linux/sched/task.h:173
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In kernel/fork.c (ffffffff810a7e56)
Location: include/linux/sched/task.h:173
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
In kernel/exit.c (ffffffff810adfd0)
Location: include/linux/sched/task.h:173
Inline: True
Inline callers:
  - kernel/exit.c:exit_mm
  - kernel/exit.c:mm_update_next_owner
```
```
In kernel/ptrace.c (ffffffff810b59db)
Location: include/linux/sched/task.h:173
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:ptrace_may_access
```
```
In kernel/sys.c (ffffffff810c1ed5)
Location: include/linux/sched/task.h:173
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
In kernel/kthread.c (ffffffff810d1097)
Location: include/linux/sched/task.h:173
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_unuse_mm
  - kernel/kthread.c:kthread_use_mm
  - kernel/kthread.c:kthreadd
```
```
In kernel/nsproxy.c (ffffffff810d5fb8)
Location: include/linux/sched/task.h:173
Inline: True
Inline callers:
  - kernel/nsproxy.c:validate_nsset
  - kernel/nsproxy.c:switch_task_namespaces
```
```
In kernel/sched/debug.c (ffffffff81105a49)
Location: include/linux/sched/task.h:173
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_show_numa
```
```
In kernel/kcmp.c (ffffffff8113fb25)
Location: include/linux/sched/task.h:173
Inline: True
Inline callers:
  - kernel/kcmp.c:get_file_raw_ptr
```
```
In kernel/time/namespace.c (ffffffff81159df5)
Location: include/linux/sched/task.h:173
Inline: True
Inline callers:
  - kernel/time/namespace.c:timens_for_children_get
  - kernel/time/namespace.c:timens_get
```
```
In kernel/cgroup/namespace.c (ffffffff81179175)
Location: include/linux/sched/task.h:173
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:cgroupns_get
```
```
In kernel/cgroup/cpuset.c (ffffffff8117e0c5)
Location: include/linux/sched/task.h:173
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
```
In kernel/utsname.c (ffffffff811833d5)
Location: include/linux/sched/task.h:173
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_get
```
```
In kernel/pid_namespace.c (ffffffff81185455)
Location: include/linux/sched/task.h:173
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_for_children_get
```
```
In mm/oom_kill.c (ffffffff81256b17)
Location: include/linux/sched/task.h:173
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/mempolicy.c (ffffffff812d084c)
Location: include/linux/sched/task.h:173
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
```
```
In fs/exec.c (ffffffff8131d0f8)
Location: include/linux/sched/task.h:173
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
In fs/file.c (ffffffff81339935)
Location: include/linux/sched/task.h:173
Inline: True
Inline callers:
  - fs/file.c:fget_task
  - fs/file.c:exit_files
  - fs/file.c:reset_files_struct
  - fs/file.c:get_files_struct
```
```
In fs/namespace.c (ffffffff8133afb5)
Location: include/linux/sched/task.h:173
Inline: True
Inline callers:
  - fs/namespace.c:mntns_get
```
```
In fs/fs_struct.c (ffffffff813553a1)
Location: include/linux/sched/task.h:173
Inline: True
Inline callers:
  - fs/fs_struct.c:unshare_fs_struct
  - fs/fs_struct.c:exit_fs
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/proc_namespace.c (ffffffff81365f2a)
Location: include/linux/sched/task.h:173
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/io-wq.c (ffffffff8138a567)
Location: include/linux/sched/task.h:173
Inline: True
Inline callers:
  - fs/io-wq.c:io_worker_handle_work
  - fs/io-wq.c:__io_worker_unuse
```
```
In fs/coredump.c (ffffffff813a830e)
Location: include/linux/sched/task.h:173
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/task_mmu.c (ffffffff813b7542)
Location: include/linux/sched/task.h:173
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:hold_task_mempolicy
```
```
In fs/proc/base.c (ffffffff813bc73f)
Location: include/linux/sched/task.h:173
Inline: True
Inline callers:
  - fs/proc/base.c:timerslack_ns_show
  - fs/proc/base.c:timerslack_ns_write
  - fs/proc/base.c:task_dump_owner
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
```
```
In fs/proc/array.c (ffffffff813c1792)
Location: include/linux/sched/task.h:173
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In fs/proc/proc_net.c (ffffffff813c99e0)
Location: include/linux/sched/task.h:173
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_task_net
```
```
In fs/hugetlbfs/inode.c (ffffffff81452109)
Location: include/linux/sched/task.h:173
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
```
```
In ipc/namespace.c (ffffffff81495135)
Location: include/linux/sched/task.h:173
Inline: True
Inline callers:
  - ipc/namespace.c:ipcns_get
```
```
In security/selinux/hooks.c (ffffffff814b6322)
Location: include/linux/sched/task.h:173
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committing_creds
```
```
In security/yama/yama_lsm.c (ffffffff8151235b)
Location: include/linux/sched/task.h:173
Inline: True
```
```
In block/blk-ioc.c (ffffffff8154972a)
Location: include/linux/sched/task.h:173
Inline: True
Inline callers:
  - block/blk-ioc.c:get_task_io_context
  - block/blk-ioc.c:create_task_io_context
  - block/blk-ioc.c:exit_io_context
```
```
In block/ioprio.c (ffffffff8155b9a5)
Location: include/linux/sched/task.h:173
Inline: True
```
```
In block/blk-cgroup.c (ffffffff8156a8c0)
Location: include/linux/sched/task.h:173
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_can_attach
```
```
In drivers/tty/tty_io.c (ffffffff817351db)
Location: include/linux/sched/task.h:173
Inline: True
```
```
In net/core/net_namespace.c (ffffffff819f8db5)
Location: include/linux/sched/task.h:173
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_get
  - net/core/net_namespace.c:get_net_ns_by_pid
```
```
In net/core/netprio_cgroup.c (ffffffff81a4ba69)
Location: include/linux/sched/task.h:173
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:net_prio_attach
```
```
In net/core/netclassid_cgroup.c (ffffffff81a4bcb8)
Location: include/linux/sched/task.h:173
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
In init/main.c (ffffffff82faf9bf)
Location: include/linux/sched/task.h:164
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In kernel/fork.c (ffffffff810a3bc8)
Location: include/linux/sched/task.h:164
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
In kernel/exit.c (ffffffff810a9661)
Location: include/linux/sched/task.h:164
Inline: True
Inline callers:
  - kernel/exit.c:exit_mm
  - kernel/exit.c:mm_update_next_owner
```
```
In kernel/ptrace.c (ffffffff810b0bcb)
Location: include/linux/sched/task.h:164
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:ptrace_may_access
```
```
In kernel/sys.c (ffffffff810bd1c5)
Location: include/linux/sched/task.h:164
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
In kernel/kthread.c (ffffffff810cb644)
Location: include/linux/sched/task.h:164
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_unuse_mm
  - kernel/kthread.c:kthread_use_mm
  - kernel/kthread.c:kthreadd
```
```
In kernel/nsproxy.c (ffffffff810d0ae8)
Location: include/linux/sched/task.h:164
Inline: True
Inline callers:
  - kernel/nsproxy.c:validate_nsset
  - kernel/nsproxy.c:switch_task_namespaces
```
```
In kernel/sched/debug.c (ffffffff81104099)
Location: include/linux/sched/task.h:164
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_show_numa
```
```
In kernel/time/namespace.c (ffffffff81155dd5)
Location: include/linux/sched/task.h:164
Inline: True
Inline callers:
  - kernel/time/namespace.c:timens_for_children_get
  - kernel/time/namespace.c:timens_get
```
```
In kernel/cgroup/namespace.c (ffffffff81175e95)
Location: include/linux/sched/task.h:164
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:cgroupns_get
```
```
In kernel/cgroup/cpuset.c (ffffffff8117af4b)
Location: include/linux/sched/task.h:164
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
```
In kernel/utsname.c (ffffffff811802d5)
Location: include/linux/sched/task.h:164
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_get
```
```
In kernel/pid_namespace.c (ffffffff81182555)
Location: include/linux/sched/task.h:164
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_for_children_get
```
```
In mm/oom_kill.c (ffffffff81261727)
Location: include/linux/sched/task.h:164
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:find_lock_task_mm
```
```
In mm/mempolicy.c (ffffffff812dc36c)
Location: include/linux/sched/task.h:164
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
In fs/exec.c (ffffffff81328b0c)
Location: include/linux/sched/task.h:164
Inline: True
Inline callers:
  - fs/exec.c:alloc_bprm
  - fs/exec.c:finalize_exec
  - fs/exec.c:__set_task_comm
  - fs/exec.c:__get_task_comm
  - fs/exec.c:exec_mmap
```
```
In fs/file.c (ffffffff81345652)
Location: include/linux/sched/task.h:164
Inline: True
Inline callers:
  - fs/file.c:task_lookup_next_fd_rcu
  - fs/file.c:task_lookup_fd_rcu
  - fs/file.c:fget_task
  - fs/file.c:__close_range
  - fs/file.c:exit_files
```
```
In fs/namespace.c (ffffffff813470c5)
Location: include/linux/sched/task.h:164
Inline: True
Inline callers:
  - fs/namespace.c:mntns_get
```
```
In fs/fs_struct.c (ffffffff81361cc1)
Location: include/linux/sched/task.h:164
Inline: True
Inline callers:
  - fs/fs_struct.c:unshare_fs_struct
  - fs/fs_struct.c:exit_fs
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/kernel_read_file.c (ffffffff81365f03)
Location: include/linux/sched/task.h:164
Inline: True
Inline callers:
  - fs/kernel_read_file.c:kernel_read_file_from_path_initns
```
```
In fs/proc_namespace.c (ffffffff81372dfa)
Location: include/linux/sched/task.h:164
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/io_uring.c (ffffffff81399dc8)
Location: include/linux/sched/task.h:164
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread_drop_mm_files
```
```
In fs/io-wq.c (ffffffff8139bcb6)
Location: include/linux/sched/task.h:164
Inline: True
Inline callers:
  - fs/io-wq.c:io_impersonate_work
  - fs/io-wq.c:__io_worker_unuse
```
```
In fs/coredump.c (ffffffff813b937f)
Location: include/linux/sched/task.h:164
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/task_mmu.c (ffffffff813c8e32)
Location: include/linux/sched/task.h:164
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:hold_task_mempolicy
```
```
In fs/proc/base.c (ffffffff813ce1dc)
Location: include/linux/sched/task.h:164
Inline: True
Inline callers:
  - fs/proc/base.c:timerslack_ns_show
  - fs/proc/base.c:timerslack_ns_write
  - fs/proc/base.c:task_dump_owner
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
```
```
In fs/proc/array.c (ffffffff813d3682)
Location: include/linux/sched/task.h:164
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In fs/proc/fd.c (ffffffff813d5b8b)
Location: include/linux/sched/task.h:164
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In fs/proc/proc_net.c (ffffffff813db650)
Location: include/linux/sched/task.h:164
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_task_net
```
```
In fs/hugetlbfs/inode.c (ffffffff8146e649)
Location: include/linux/sched/task.h:164
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
```
```
In ipc/namespace.c (ffffffff814b2c25)
Location: include/linux/sched/task.h:164
Inline: True
Inline callers:
  - ipc/namespace.c:ipcns_get
```
```
In security/selinux/hooks.c (ffffffff814d4002)
Location: include/linux/sched/task.h:164
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committing_creds
```
```
In security/yama/yama_lsm.c (ffffffff8152f1fb)
Location: include/linux/sched/task.h:164
Inline: True
```
```
In block/blk-ioc.c (ffffffff8156555a)
Location: include/linux/sched/task.h:164
Inline: True
Inline callers:
  - block/blk-ioc.c:get_task_io_context
  - block/blk-ioc.c:create_task_io_context
  - block/blk-ioc.c:exit_io_context
```
```
In block/ioprio.c (ffffffff81577b05)
Location: include/linux/sched/task.h:164
Inline: True
```
```
In block/blk-cgroup.c (ffffffff81585310)
Location: include/linux/sched/task.h:164
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_can_attach
```
```
In drivers/tty/tty_io.c (ffffffff81751ca5)
Location: include/linux/sched/task.h:164
Inline: True
```
```
In net/core/net_namespace.c (ffffffff819f8885)
Location: include/linux/sched/task.h:164
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_get
  - net/core/net_namespace.c:get_net_ns_by_pid
```
```
In net/core/netprio_cgroup.c (ffffffff81a516b9)
Location: include/linux/sched/task.h:164
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:net_prio_attach
```
```
In net/core/netclassid_cgroup.c (ffffffff81a518d8)
Location: include/linux/sched/task.h:164
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
In init/main.c (ffffffff831b99dd)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In kernel/fork.c (ffffffff810a4818)
Location: include/linux/sched/task.h:166
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
In kernel/exit.c (ffffffff810aa6a1)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - kernel/exit.c:exit_mm
  - kernel/exit.c:mm_update_next_owner
```
```
In kernel/ptrace.c (ffffffff810b216b)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:ptrace_may_access
```
```
In kernel/sys.c (ffffffff810bf581)
Location: include/linux/sched/task.h:166
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
In kernel/kthread.c (ffffffff810cd3a2)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_unuse_mm
  - kernel/kthread.c:kthread_use_mm
  - kernel/kthread.c:kthreadd
```
```
In kernel/nsproxy.c (ffffffff810d26c8)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - kernel/nsproxy.c:validate_nsset
  - kernel/nsproxy.c:switch_task_namespaces
```
```
In kernel/sched/debug.c (ffffffff81106db9)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_show_numa
```
```
In kernel/time/namespace.c (ffffffff81156fe5)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - kernel/time/namespace.c:timens_for_children_get
  - kernel/time/namespace.c:timens_get
```
```
In kernel/cgroup/namespace.c (ffffffff81176af5)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:cgroupns_get
```
```
In kernel/cgroup/cpuset.c (ffffffff8117c7cb)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
```
In kernel/utsname.c (ffffffff811811e5)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_get
```
```
In kernel/pid_namespace.c (ffffffff811836a5)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_for_children_get
```
```
In mm/oom_kill.c (ffffffff81265f57)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:find_lock_task_mm
```
```
In mm/mempolicy.c (ffffffff812e3bfc)
Location: include/linux/sched/task.h:166
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
In fs/exec.c (ffffffff8132e96c)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - fs/exec.c:alloc_bprm
  - fs/exec.c:finalize_exec
  - fs/exec.c:__set_task_comm
  - fs/exec.c:__get_task_comm
  - fs/exec.c:exec_mmap
```
```
In fs/file.c (ffffffff8134b9f2)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - fs/file.c:task_lookup_next_fd_rcu
  - fs/file.c:task_lookup_fd_rcu
  - fs/file.c:fget_task
  - fs/file.c:__close_range
  - fs/file.c:exit_files
```
```
In fs/namespace.c (ffffffff8134d875)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - fs/namespace.c:mntns_get
```
```
In fs/fs_struct.c (ffffffff813687a1)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - fs/fs_struct.c:unshare_fs_struct
  - fs/fs_struct.c:exit_fs
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/kernel_read_file.c (ffffffff8136c943)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - fs/kernel_read_file.c:kernel_read_file_from_path_initns
```
```
In fs/proc_namespace.c (ffffffff8137978a)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/coredump.c (ffffffff813c0272)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/task_mmu.c (ffffffff813cff02)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:hold_task_mempolicy
```
```
In fs/proc/base.c (ffffffff813d60ac)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - fs/proc/base.c:timerslack_ns_show
  - fs/proc/base.c:timerslack_ns_write
  - fs/proc/base.c:task_dump_owner
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
```
```
In fs/proc/array.c (ffffffff813da4b2)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In fs/proc/fd.c (ffffffff813dcb9b)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In fs/proc/proc_net.c (ffffffff813e2580)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_task_net
```
```
In fs/hugetlbfs/inode.c (ffffffff81473c89)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
```
```
In ipc/namespace.c (ffffffff814b87d5)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - ipc/namespace.c:ipcns_get
```
```
In security/selinux/hooks.c (ffffffff814da5b0)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committing_creds
```
```
In security/yama/yama_lsm.c (ffffffff8153518b)
Location: include/linux/sched/task.h:166
Inline: True
```
```
In block/blk-ioc.c (ffffffff8156dbca)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - block/blk-ioc.c:get_task_io_context
  - block/blk-ioc.c:create_task_io_context
  - block/blk-ioc.c:exit_io_context
```
```
In block/ioprio.c (ffffffff8157f845)
Location: include/linux/sched/task.h:166
Inline: True
```
```
In block/blk-cgroup.c (ffffffff8158bec0)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_can_attach
```
```
In drivers/tty/tty_io.c (ffffffff817358f1)
Location: include/linux/sched/task.h:166
Inline: True
```
```
In net/core/net_namespace.c (ffffffff819df0b5)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_get
  - net/core/net_namespace.c:get_net_ns_by_pid
```
```
In net/core/netprio_cgroup.c (ffffffff81a36f59)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:net_prio_attach
```
```
In net/core/netclassid_cgroup.c (ffffffff81a3726b)
Location: include/linux/sched/task.h:166
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
In init/main.c (ffffffff83299db2)
Location: include/linux/sched/task.h:167
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In kernel/fork.c (ffffffff810b6038)
Location: include/linux/sched/task.h:167
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
In kernel/exit.c (ffffffff810bc1cc)
Location: include/linux/sched/task.h:167
Inline: True
Inline callers:
  - kernel/exit.c:exit_mm
  - kernel/exit.c:mm_update_next_owner
```
```
In kernel/ptrace.c (ffffffff810c3f77)
Location: include/linux/sched/task.h:167
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:ptrace_may_access
```
```
In kernel/sys.c (ffffffff810d2001)
Location: include/linux/sched/task.h:167
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
In kernel/kthread.c (ffffffff810e0592)
Location: include/linux/sched/task.h:167
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_unuse_mm
  - kernel/kthread.c:kthread_use_mm
  - kernel/kthread.c:kthreadd
```
```
In kernel/nsproxy.c (ffffffff810e5808)
Location: include/linux/sched/task.h:167
Inline: True
Inline callers:
  - kernel/nsproxy.c:validate_nsset
  - kernel/nsproxy.c:switch_task_namespaces
```
```
In kernel/sched/debug.c (ffffffff8112499e)
Location: include/linux/sched/task.h:167
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_show_numa
```
```
In kernel/time/namespace.c (ffffffff8117be35)
Location: include/linux/sched/task.h:167
Inline: True
Inline callers:
  - kernel/time/namespace.c:timens_for_children_get
  - kernel/time/namespace.c:timens_get
```
```
In kernel/cgroup/namespace.c (ffffffff8119e375)
Location: include/linux/sched/task.h:167
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:cgroupns_get
```
```
In kernel/cgroup/cpuset.c (ffffffff811a435b)
Location: include/linux/sched/task.h:167
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
```
In kernel/utsname.c (ffffffff811a9155)
Location: include/linux/sched/task.h:167
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_get
```
```
In kernel/pid_namespace.c (ffffffff811ab785)
Location: include/linux/sched/task.h:167
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_for_children_get
```
```
In mm/oom_kill.c (ffffffff812a2777)
Location: include/linux/sched/task.h:167
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:find_lock_task_mm
```
```
In mm/mempolicy.c (ffffffff8132aedc)
Location: include/linux/sched/task.h:167
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
In fs/exec.c (ffffffff8137c17c)
Location: include/linux/sched/task.h:167
Inline: True
Inline callers:
  - fs/exec.c:alloc_bprm
  - fs/exec.c:finalize_exec
  - fs/exec.c:__set_task_comm
  - fs/exec.c:__get_task_comm
  - fs/exec.c:exec_mmap
```
```
In fs/file.c (ffffffff81399832)
Location: include/linux/sched/task.h:167
Inline: True
Inline callers:
  - fs/file.c:task_lookup_next_fd_rcu
  - fs/file.c:task_lookup_fd_rcu
  - fs/file.c:fget_task
  - fs/file.c:__close_range
  - fs/file.c:exit_files
```
```
In fs/namespace.c (ffffffff8139b845)
Location: include/linux/sched/task.h:167
Inline: True
Inline callers:
  - fs/namespace.c:mntns_get
```
```
In fs/fs_struct.c (ffffffff813b74a1)
Location: include/linux/sched/task.h:167
Inline: True
Inline callers:
  - fs/fs_struct.c:unshare_fs_struct
  - fs/fs_struct.c:exit_fs
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/kernel_read_file.c (ffffffff813bb613)
Location: include/linux/sched/task.h:167
Inline: True
Inline callers:
  - fs/kernel_read_file.c:kernel_read_file_from_path_initns
```
```
In fs/proc_namespace.c (ffffffff813c62ea)
Location: include/linux/sched/task.h:167
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/coredump.c (ffffffff814100a2)
Location: include/linux/sched/task.h:167
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/task_mmu.c (ffffffff81421522)
Location: include/linux/sched/task.h:167
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:hold_task_mempolicy
```
```
In fs/proc/base.c (ffffffff8142797c)
Location: include/linux/sched/task.h:167
Inline: True
Inline callers:
  - fs/proc/base.c:timerslack_ns_show
  - fs/proc/base.c:timerslack_ns_write
  - fs/proc/base.c:task_dump_owner
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
```
```
In fs/proc/array.c (ffffffff8142bbe2)
Location: include/linux/sched/task.h:167
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In fs/proc/fd.c (ffffffff8142e27b)
Location: include/linux/sched/task.h:167
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In fs/proc/proc_net.c (ffffffff81434090)
Location: include/linux/sched/task.h:167
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_task_net
```
```
In fs/hugetlbfs/inode.c (ffffffff814ca8d4)
Location: include/linux/sched/task.h:167
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
```
```
In ipc/shm.c (ffffffff8150b74a)
Location: include/linux/sched/task.h:167
Inline: True
Inline callers:
  - ipc/shm.c:newseg
  - ipc/shm.c:exit_shm
  - ipc/shm.c:shm_destroy
```
```
In ipc/namespace.c (ffffffff81511005)
Location: include/linux/sched/task.h:167
Inline: True
Inline callers:
  - ipc/namespace.c:ipcns_get
```
```
In security/selinux/hooks.c (ffffffff815334b0)
Location: include/linux/sched/task.h:167
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committing_creds
```
```
In security/yama/yama_lsm.c (ffffffff8159369b)
Location: include/linux/sched/task.h:167
Inline: True
```
```
In block/blk-ioc.c (ffffffff815d21ba)
Location: include/linux/sched/task.h:167
Inline: True
Inline callers:
  - block/blk-ioc.c:get_task_io_context
  - block/blk-ioc.c:create_task_io_context
  - block/blk-ioc.c:exit_io_context
```
```
In block/ioprio.c (ffffffff815e4ae5)
Location: include/linux/sched/task.h:167
Inline: True
```
```
In drivers/tty/tty_io.c (ffffffff817b62b1)
Location: include/linux/sched/task.h:167
Inline: True
```
```
In net/core/net_namespace.c (ffffffff81a8f495)
Location: include/linux/sched/task.h:167
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_get
  - net/core/net_namespace.c:get_net_ns_by_pid
```
```
In net/core/netprio_cgroup.c (ffffffff81aec8f9)
Location: include/linux/sched/task.h:167
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:net_prio_attach
```
```
In net/core/netclassid_cgroup.c (ffffffff81aecd88)
Location: include/linux/sched/task.h:167
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
In init/main.c (ffffffff81e43804)
Location: include/linux/sched/task.h:172
Inline: True
Inline callers:
  - init/main.c:set_mems_allowed
```
```
In kernel/fork.c (ffffffff810cc562)
Location: include/linux/sched/task.h:172
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
In kernel/exit.c (ffffffff810d2c5a)
Location: include/linux/sched/task.h:172
Inline: True
Inline callers:
  - kernel/exit.c:exit_mm
  - kernel/exit.c:mm_update_next_owner
```
```
In kernel/ptrace.c (ffffffff810db58e)
Location: include/linux/sched/task.h:172
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:ptrace_may_access
```
```
In kernel/sys.c (ffffffff810e8711)
Location: include/linux/sched/task.h:172
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
In kernel/kthread.c (ffffffff810f99ea)
Location: include/linux/sched/task.h:172
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_unuse_mm
  - kernel/kthread.c:kthread_use_mm
  - kernel/kthread.c:set_mems_allowed
```
```
In kernel/nsproxy.c (ffffffff810ff61f)
Location: include/linux/sched/task.h:172
Inline: True
Inline callers:
  - kernel/nsproxy.c:validate_nsset
  - kernel/nsproxy.c:switch_task_namespaces
```
```
In kernel/time/namespace.c (ffffffff811b1f5e)
Location: include/linux/sched/task.h:172
Inline: True
Inline callers:
  - kernel/time/namespace.c:proc_timens_set_offset
  - kernel/time/namespace.c:proc_timens_show_offsets
  - kernel/time/namespace.c:timens_get
```
```
In kernel/cgroup/namespace.c (ffffffff811ce685)
Location: include/linux/sched/task.h:172
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:cgroupns_get
```
```
In kernel/cgroup/cpuset.c (ffffffff811d3e0b)
Location: include/linux/sched/task.h:172
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
```
In kernel/utsname.c (ffffffff811da595)
Location: include/linux/sched/task.h:172
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_get
```
```
In kernel/pid_namespace.c (ffffffff811dce35)
Location: include/linux/sched/task.h:172
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_for_children_get
```
```
In mm/oom_kill.c (ffffffff812fb07e)
Location: include/linux/sched/task.h:172
Inline: True
Inline callers:
  - mm/oom_kill.c:__do_sys_process_mrelease
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:oom_badness
```
```
In mm/mempolicy.c (ffffffff8139a8e2)
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
In fs/exec.c (ffffffff813faf81)
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
In fs/file.c (ffffffff8141c1f3)
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
In fs/namespace.c (ffffffff8141e645)
Location: include/linux/sched/task.h:172
Inline: True
Inline callers:
  - fs/namespace.c:mntns_get
```
```
In fs/fs_struct.c (ffffffff8143cb61)
Location: include/linux/sched/task.h:172
Inline: True
Inline callers:
  - fs/fs_struct.c:unshare_fs_struct
  - fs/fs_struct.c:exit_fs
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/kernel_read_file.c (ffffffff81441565)
Location: include/linux/sched/task.h:172
Inline: True
Inline callers:
  - fs/kernel_read_file.c:kernel_read_file_from_path_initns
```
```
In fs/proc_namespace.c (ffffffff8144cb6c)
Location: include/linux/sched/task.h:172
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/coredump.c (ffffffff81485a52)
Location: include/linux/sched/task.h:172
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/task_mmu.c (ffffffff814979e2)
Location: include/linux/sched/task.h:172
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:hold_task_mempolicy
```
```
In fs/proc/base.c (ffffffff8149ff6f)
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
In fs/proc/array.c (ffffffff814a5849)
Location: include/linux/sched/task.h:172
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In fs/proc/fd.c (ffffffff814a79a4)
Location: include/linux/sched/task.h:172
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In fs/proc/proc_net.c (ffffffff814ae117)
Location: include/linux/sched/task.h:172
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_task_net
```
```
In ipc/shm.c (ffffffff8159d9a0)
Location: include/linux/sched/task.h:172
Inline: True
Inline callers:
  - ipc/shm.c:newseg
  - ipc/shm.c:exit_shm
  - ipc/shm.c:shm_destroy
```
```
In ipc/namespace.c (ffffffff815a35b5)
Location: include/linux/sched/task.h:172
Inline: True
Inline callers:
  - ipc/namespace.c:ipcns_get
```
```
In security/selinux/hooks.c (ffffffff815c4d5d)
Location: include/linux/sched/task.h:172
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committing_creds
```
```
In security/yama/yama_lsm.c (ffffffff8163597a)
Location: include/linux/sched/task.h:172
Inline: True
```
```
In block/blk-ioc.c (ffffffff8167ddda)
Location: include/linux/sched/task.h:172
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_find_get_icq
  - block/blk-ioc.c:set_task_ioprio
  - block/blk-ioc.c:set_task_ioprio
  - block/blk-ioc.c:exit_io_context
```
```
In block/ioprio.c (ffffffff81693be3)
Location: include/linux/sched/task.h:172
Inline: True
Inline callers:
  - block/ioprio.c:__do_sys_ioprio_get
  - block/ioprio.c:__do_sys_ioprio_get
  - block/ioprio.c:__do_sys_ioprio_get
```
```
In drivers/tty/tty_io.c (ffffffff818f4181)
Location: include/linux/sched/task.h:172
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:__do_SAK
```
```
In net/core/net_namespace.c (ffffffff81c05155)
Location: include/linux/sched/task.h:172
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_get
  - net/core/net_namespace.c:get_net_ns_by_pid
```
```
In net/core/netprio_cgroup.c (ffffffff81c6f411)
Location: include/linux/sched/task.h:172
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:net_prio_attach
```
```
In net/core/netclassid_cgroup.c (ffffffff81c6f98e)
Location: include/linux/sched/task.h:172
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
In init/main.c (ffffffff81000e5e)
Location: include/linux/sched/task.h:175
Inline: True
Inline callers:
  - init/main.c:set_mems_allowed
```
```
In kernel/fork.c (ffffffff810e9c42)
Location: include/linux/sched/task.h:175
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
In kernel/exit.c (ffffffff810f1762)
Location: include/linux/sched/task.h:175
Inline: True
Inline callers:
  - kernel/exit.c:exit_mm
  - kernel/exit.c:mm_update_next_owner
```
```
In kernel/ptrace.c (ffffffff810fb64e)
Location: include/linux/sched/task.h:175
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:ptrace_may_access
```
```
In kernel/sys.c (ffffffff81109aa1)
Location: include/linux/sched/task.h:175
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
In kernel/kthread.c (ffffffff8111c75a)
Location: include/linux/sched/task.h:175
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_unuse_mm
  - kernel/kthread.c:kthread_use_mm
  - kernel/kthread.c:set_mems_allowed
```
```
In kernel/nsproxy.c (ffffffff8112434f)
Location: include/linux/sched/task.h:175
Inline: True
Inline callers:
  - kernel/nsproxy.c:validate_nsset
  - kernel/nsproxy.c:switch_task_namespaces
```
```
In kernel/time/namespace.c (ffffffff811f2d8e)
Location: include/linux/sched/task.h:175
Inline: True
Inline callers:
  - kernel/time/namespace.c:proc_timens_set_offset
  - kernel/time/namespace.c:proc_timens_show_offsets
  - kernel/time/namespace.c:timens_get
```
```
In kernel/cgroup/namespace.c (ffffffff81211ee5)
Location: include/linux/sched/task.h:175
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:cgroupns_get
```
```
In kernel/cgroup/cpuset.c (ffffffff81217bcb)
Location: include/linux/sched/task.h:175
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
```
In kernel/utsname.c (ffffffff8121fb65)
Location: include/linux/sched/task.h:175
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_get
```
```
In kernel/pid_namespace.c (ffffffff812227c5)
Location: include/linux/sched/task.h:175
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_for_children_get
```
```
In mm/oom_kill.c (ffffffff813643ce)
Location: include/linux/sched/task.h:175
Inline: True
Inline callers:
  - mm/oom_kill.c:__do_sys_process_mrelease
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:oom_badness
```
```
In mm/mempolicy.c (ffffffff8141a922)
Location: include/linux/sched/task.h:175
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
In mm/memcontrol.c (ffffffff8144ebb3)
Location: include/linux/sched/task.h:175
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_attach
```
```
In fs/exec.c (ffffffff81484881)
Location: include/linux/sched/task.h:175
Inline: True
Inline callers:
  - fs/exec.c:alloc_bprm
  - fs/exec.c:finalize_exec
  - fs/exec.c:__set_task_comm
  - fs/exec.c:__get_task_comm
  - fs/exec.c:exec_mmap
```
```
In fs/file.c (ffffffff814a6d83)
Location: include/linux/sched/task.h:175
Inline: True
Inline callers:
  - fs/file.c:task_lookup_next_fd_rcu
  - fs/file.c:task_lookup_fd_rcu
  - fs/file.c:fget_task
  - fs/file.c:__close_range
  - fs/file.c:exit_files
```
```
In fs/namespace.c (ffffffff814aaf25)
Location: include/linux/sched/task.h:175
Inline: True
Inline callers:
  - fs/namespace.c:mntns_get
```
```
In fs/fs_struct.c (ffffffff814cb2c1)
Location: include/linux/sched/task.h:175
Inline: True
Inline callers:
  - fs/fs_struct.c:unshare_fs_struct
  - fs/fs_struct.c:exit_fs
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/kernel_read_file.c (ffffffff814d04f5)
Location: include/linux/sched/task.h:175
Inline: True
Inline callers:
  - fs/kernel_read_file.c:kernel_read_file_from_path_initns
```
```
In fs/proc_namespace.c (ffffffff814db0dc)
Location: include/linux/sched/task.h:175
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/coredump.c (ffffffff8151930f)
Location: include/linux/sched/task.h:175
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/task_mmu.c (ffffffff8152b992)
Location: include/linux/sched/task.h:175
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:hold_task_mempolicy
```
```
In fs/proc/base.c (ffffffff81534e3f)
Location: include/linux/sched/task.h:175
Inline: True
Inline callers:
  - fs/proc/base.c:timerslack_ns_show
  - fs/proc/base.c:timerslack_ns_write
  - fs/proc/base.c:task_dump_owner
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
```
```
In fs/proc/array.c (ffffffff8153ae59)
Location: include/linux/sched/task.h:175
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In fs/proc/fd.c (ffffffff8153d6af)
Location: include/linux/sched/task.h:175
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_count
  - fs/proc/fd.c:seq_show
```
```
In fs/proc/proc_net.c (ffffffff815446e7)
Location: include/linux/sched/task.h:175
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_task_net
```
```
In ipc/shm.c (ffffffff81646f70)
Location: include/linux/sched/task.h:175
Inline: True
Inline callers:
  - ipc/shm.c:newseg
  - ipc/shm.c:exit_shm
  - ipc/shm.c:shm_destroy
```
```
In ipc/namespace.c (ffffffff8164d1d5)
Location: include/linux/sched/task.h:175
Inline: True
Inline callers:
  - ipc/namespace.c:ipcns_get
```
```
In security/selinux/hooks.c (ffffffff8167185d)
Location: include/linux/sched/task.h:175
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committing_creds
```
```
In security/yama/yama_lsm.c (ffffffff816ec67a)
Location: include/linux/sched/task.h:175
Inline: True
```
```
In block/blk-ioc.c (ffffffff8173aa2a)
Location: include/linux/sched/task.h:175
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_find_get_icq
  - block/blk-ioc.c:set_task_ioprio
  - block/blk-ioc.c:set_task_ioprio
  - block/blk-ioc.c:exit_io_context
```
```
In block/ioprio.c (ffffffff81752c0d)
Location: include/linux/sched/task.h:175
Inline: True
Inline callers:
  - block/ioprio.c:__do_sys_ioprio_get
  - block/ioprio.c:__do_sys_ioprio_get
  - block/ioprio.c:__do_sys_ioprio_get
```
```
In drivers/tty/tty_io.c (ffffffff81a4c8b2)
Location: include/linux/sched/task.h:175
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:__do_SAK
```
```
In net/core/net_namespace.c (ffffffff81db49d5)
Location: include/linux/sched/task.h:175
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_get
  - net/core/net_namespace.c:get_net_ns_by_pid
```
```
In net/core/netprio_cgroup.c (ffffffff81e27221)
Location: include/linux/sched/task.h:175
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:net_prio_attach
```
```
In net/core/netclassid_cgroup.c (ffffffff81e2784e)
Location: include/linux/sched/task.h:175
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
In init/main.c (ffffffff81000bbe)
Location: include/linux/sched/task.h:183
Inline: True
Inline callers:
  - init/main.c:set_mems_allowed
```
```
In kernel/fork.c (ffffffff810f5842)
Location: include/linux/sched/task.h:183
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
In kernel/exit.c (ffffffff810fd6b4)
Location: include/linux/sched/task.h:183
Inline: True
Inline callers:
  - kernel/exit.c:exit_mm
  - kernel/exit.c:mm_update_next_owner
```
```
In kernel/ptrace.c (ffffffff811076ee)
Location: include/linux/sched/task.h:183
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:ptrace_may_access
```
```
In kernel/sys.c (ffffffff81115e31)
Location: include/linux/sched/task.h:183
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
In kernel/kthread.c (ffffffff8112a8ad)
Location: include/linux/sched/task.h:183
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_unuse_mm
  - kernel/kthread.c:kthread_use_mm
  - kernel/kthread.c:set_mems_allowed
```
```
In kernel/nsproxy.c (ffffffff8113164f)
Location: include/linux/sched/task.h:183
Inline: True
Inline callers:
  - kernel/nsproxy.c:validate_nsset
  - kernel/nsproxy.c:switch_task_namespaces
```
```
In kernel/time/namespace.c (ffffffff8120750e)
Location: include/linux/sched/task.h:183
Inline: True
Inline callers:
  - kernel/time/namespace.c:proc_timens_set_offset
  - kernel/time/namespace.c:proc_timens_show_offsets
  - kernel/time/namespace.c:timens_get
```
```
In kernel/cgroup/namespace.c (ffffffff81227845)
Location: include/linux/sched/task.h:183
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:cgroupns_get
```
```
In kernel/cgroup/cpuset.c (ffffffff8122d3eb)
Location: include/linux/sched/task.h:183
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
```
In kernel/utsname.c (ffffffff81235d55)
Location: include/linux/sched/task.h:183
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_get
```
```
In kernel/pid_namespace.c (ffffffff81238e25)
Location: include/linux/sched/task.h:183
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_for_children_get
```
```
In mm/oom_kill.c (ffffffff8139689e)
Location: include/linux/sched/task.h:183
Inline: True
Inline callers:
  - mm/oom_kill.c:__do_sys_process_mrelease
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:oom_badness
```
```
In mm/mempolicy.c (ffffffff8144de98)
Location: include/linux/sched/task.h:183
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
In mm/memcontrol.c (ffffffff81484673)
Location: include/linux/sched/task.h:183
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_attach
```
```
In fs/exec.c (ffffffff814b9461)
Location: include/linux/sched/task.h:183
Inline: True
Inline callers:
  - fs/exec.c:alloc_bprm
  - fs/exec.c:finalize_exec
  - fs/exec.c:__set_task_comm
  - fs/exec.c:__get_task_comm
  - fs/exec.c:exec_mmap
```
```
In fs/file.c (ffffffff814dbd63)
Location: include/linux/sched/task.h:183
Inline: True
Inline callers:
  - fs/file.c:task_lookup_next_fd_rcu
  - fs/file.c:task_lookup_fd_rcu
  - fs/file.c:fget_task
  - fs/file.c:__close_range
  - fs/file.c:exit_files
```
```
In fs/namespace.c (ffffffff814dfbf5)
Location: include/linux/sched/task.h:183
Inline: True
Inline callers:
  - fs/namespace.c:mntns_get
```
```
In fs/fs_struct.c (ffffffff81501501)
Location: include/linux/sched/task.h:183
Inline: True
Inline callers:
  - fs/fs_struct.c:unshare_fs_struct
  - fs/fs_struct.c:exit_fs
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/kernel_read_file.c (ffffffff815067a5)
Location: include/linux/sched/task.h:183
Inline: True
Inline callers:
  - fs/kernel_read_file.c:kernel_read_file_from_path_initns
```
```
In fs/proc_namespace.c (ffffffff8150f68c)
Location: include/linux/sched/task.h:183
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/coredump.c (ffffffff81550c17)
Location: include/linux/sched/task.h:183
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/task_mmu.c (ffffffff81563d12)
Location: include/linux/sched/task.h:183
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:hold_task_mempolicy
```
```
In fs/proc/base.c (ffffffff8156cfff)
Location: include/linux/sched/task.h:183
Inline: True
Inline callers:
  - fs/proc/base.c:timerslack_ns_show
  - fs/proc/base.c:timerslack_ns_write
  - fs/proc/base.c:task_dump_owner
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
```
```
In fs/proc/array.c (ffffffff81573166)
Location: include/linux/sched/task.h:183
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In fs/proc/fd.c (ffffffff8157598f)
Location: include/linux/sched/task.h:183
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_count
  - fs/proc/fd.c:seq_show
```
```
In fs/proc/proc_net.c (ffffffff8157c2e7)
Location: include/linux/sched/task.h:183
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_task_net
```
```
In ipc/shm.c (ffffffff8167f4b0)
Location: include/linux/sched/task.h:183
Inline: True
Inline callers:
  - ipc/shm.c:newseg
  - ipc/shm.c:exit_shm
  - ipc/shm.c:shm_destroy
```
```
In ipc/namespace.c (ffffffff81685975)
Location: include/linux/sched/task.h:183
Inline: True
Inline callers:
  - ipc/namespace.c:ipcns_get
```
```
In security/selinux/hooks.c (ffffffff816aa039)
Location: include/linux/sched/task.h:183
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committing_creds
```
```
In security/yama/yama_lsm.c (ffffffff81726aaa)
Location: include/linux/sched/task.h:183
Inline: True
```
```
In block/blk-ioc.c (ffffffff8177712d)
Location: include/linux/sched/task.h:183
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_find_get_icq
  - block/blk-ioc.c:set_task_ioprio
  - block/blk-ioc.c:set_task_ioprio
  - block/blk-ioc.c:exit_io_context
```
```
In block/ioprio.c (ffffffff8178ef66)
Location: include/linux/sched/task.h:183
Inline: True
Inline callers:
  - block/ioprio.c:__do_sys_ioprio_get
  - block/ioprio.c:__do_sys_ioprio_get
  - block/ioprio.c:__do_sys_ioprio_get
```
```
In drivers/tty/tty_io.c (ffffffff81a96ba2)
Location: include/linux/sched/task.h:183
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:__do_SAK
```
```
In net/core/net_namespace.c (ffffffff81e25075)
Location: include/linux/sched/task.h:183
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_get
  - net/core/net_namespace.c:get_net_ns_by_pid
```
```
In net/core/netprio_cgroup.c (ffffffff81e9c791)
Location: include/linux/sched/task.h:183
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:net_prio_attach
```
```
In net/core/netclassid_cgroup.c (ffffffff81e9ce5e)
Location: include/linux/sched/task.h:183
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
In init/main.c (ffffffff81000bce)
Location: include/linux/sched/task.h:221
Inline: True
Inline callers:
  - init/main.c:set_mems_allowed
```
```
In kernel/fork.c (ffffffff810febf2)
Location: include/linux/sched/task.h:221
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
In kernel/exit.c (ffffffff81106524)
Location: include/linux/sched/task.h:221
Inline: True
Inline callers:
  - kernel/exit.c:exit_mm
  - kernel/exit.c:mm_update_next_owner
```
```
In kernel/ptrace.c (ffffffff81111052)
Location: include/linux/sched/task.h:221
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:ptrace_may_access
```
```
In kernel/sys.c (ffffffff8111f821)
Location: include/linux/sched/task.h:221
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
In kernel/kthread.c (ffffffff81134f3d)
Location: include/linux/sched/task.h:221
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_unuse_mm
  - kernel/kthread.c:kthread_use_mm
  - kernel/kthread.c:set_mems_allowed
```
```
In kernel/nsproxy.c (ffffffff8113c3df)
Location: include/linux/sched/task.h:221
Inline: True
Inline callers:
  - kernel/nsproxy.c:validate_nsset
  - kernel/nsproxy.c:exec_task_namespaces
  - kernel/nsproxy.c:exit_task_namespaces
```
```
In kernel/time/namespace.c (ffffffff8121e71e)
Location: include/linux/sched/task.h:221
Inline: True
Inline callers:
  - kernel/time/namespace.c:proc_timens_set_offset
  - kernel/time/namespace.c:proc_timens_show_offsets
  - kernel/time/namespace.c:timens_get
```
```
In kernel/cgroup/namespace.c (ffffffff8123f655)
Location: include/linux/sched/task.h:221
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:cgroupns_get
```
```
In kernel/cgroup/cpuset.c (ffffffff812456bb)
Location: include/linux/sched/task.h:221
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
```
In kernel/utsname.c (ffffffff8124f9d5)
Location: include/linux/sched/task.h:221
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_get
```
```
In kernel/pid_namespace.c (ffffffff81252af5)
Location: include/linux/sched/task.h:221
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_for_children_get
```
```
In mm/oom_kill.c (ffffffff813c01ae)
Location: include/linux/sched/task.h:221
Inline: True
Inline callers:
  - mm/oom_kill.c:__do_sys_process_mrelease
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:oom_badness
```
```
In mm/mempolicy.c (ffffffff81487874)
Location: include/linux/sched/task.h:221
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
In mm/memcontrol.c (ffffffff814b3bf5)
Location: include/linux/sched/task.h:221
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_attach
```
```
In fs/exec.c (ffffffff814ebf68)
Location: include/linux/sched/task.h:221
Inline: True
Inline callers:
  - fs/exec.c:alloc_bprm
  - fs/exec.c:finalize_exec
  - fs/exec.c:__set_task_comm
  - fs/exec.c:__get_task_comm
  - fs/exec.c:exec_mmap
```
```
In fs/file.c (ffffffff8150e2d9)
Location: include/linux/sched/task.h:221
Inline: True
Inline callers:
  - fs/file.c:task_lookup_next_fdget_rcu
  - fs/file.c:task_lookup_fdget_rcu
  - fs/file.c:fget_task
  - fs/file.c:__close_range
  - fs/file.c:exit_files
```
```
In fs/namespace.c (ffffffff81512af5)
Location: include/linux/sched/task.h:221
Inline: True
Inline callers:
  - fs/namespace.c:mntns_get
```
```
In fs/fs_struct.c (ffffffff81536151)
Location: include/linux/sched/task.h:221
Inline: True
Inline callers:
  - fs/fs_struct.c:unshare_fs_struct
  - fs/fs_struct.c:exit_fs
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/kernel_read_file.c (ffffffff8153b4c5)
Location: include/linux/sched/task.h:221
Inline: True
Inline callers:
  - fs/kernel_read_file.c:kernel_read_file_from_path_initns
```
```
In fs/proc_namespace.c (ffffffff81543b8c)
Location: include/linux/sched/task.h:221
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/coredump.c (ffffffff81586aa8)
Location: include/linux/sched/task.h:221
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/task_mmu.c (ffffffff8159a5f2)
Location: include/linux/sched/task.h:221
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:hold_task_mempolicy
```
```
In fs/proc/base.c (ffffffff815a57ff)
Location: include/linux/sched/task.h:221
Inline: True
Inline callers:
  - fs/proc/base.c:timerslack_ns_show
  - fs/proc/base.c:timerslack_ns_write
  - fs/proc/base.c:task_dump_owner
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
```
```
In fs/proc/array.c (ffffffff815ab926)
Location: include/linux/sched/task.h:221
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In fs/proc/fd.c (ffffffff815ae2df)
Location: include/linux/sched/task.h:221
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_count
  - fs/proc/fd.c:seq_show
```
```
In fs/proc/proc_net.c (ffffffff815b4bf7)
Location: include/linux/sched/task.h:221
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_task_net
```
```
In ipc/shm.c (ffffffff816bb8a0)
Location: include/linux/sched/task.h:221
Inline: True
Inline callers:
  - ipc/shm.c:newseg
  - ipc/shm.c:exit_shm
  - ipc/shm.c:shm_destroy
```
```
In ipc/namespace.c (ffffffff816c1d95)
Location: include/linux/sched/task.h:221
Inline: True
Inline callers:
  - ipc/namespace.c:ipcns_get
```
```
In security/selinux/hooks.c (ffffffff816e684c)
Location: include/linux/sched/task.h:221
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committing_creds
```
```
In security/yama/yama_lsm.c (ffffffff81767cfa)
Location: include/linux/sched/task.h:221
Inline: True
```
```
In block/blk-ioc.c (ffffffff817b935a)
Location: include/linux/sched/task.h:221
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_find_get_icq
  - block/blk-ioc.c:set_task_ioprio
  - block/blk-ioc.c:set_task_ioprio
  - block/blk-ioc.c:exit_io_context
```
```
In block/ioprio.c (ffffffff817d16b8)
Location: include/linux/sched/task.h:221
Inline: True
Inline callers:
  - block/ioprio.c:__do_sys_ioprio_get
```
```
In drivers/tty/tty_io.c (ffffffff81ae95b3)
Location: include/linux/sched/task.h:221
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:__do_SAK
```
```
In net/core/net_namespace.c (ffffffff81ee2fd5)
Location: include/linux/sched/task.h:221
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_get
  - net/core/net_namespace.c:get_net_ns_by_pid
```
```
In net/core/netprio_cgroup.c (ffffffff81f5ef31)
Location: include/linux/sched/task.h:221
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:net_prio_attach
```
```
In net/core/netclassid_cgroup.c (ffffffff81f5f598)
Location: include/linux/sched/task.h:221
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
In init/main.c (ffff8000114311f4)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In kernel/fork.c (ffff8000100f5990)
Location: include/linux/sched/task.h:166
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
In kernel/exit.c (ffff8000100fd4dc)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:mm_update_next_owner
```
```
In kernel/ptrace.c (ffff800010107fe0)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:ptrace_may_access
```
```
In kernel/sys.c (ffff8000101158fc)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_auxv
  - kernel/sys.c:do_prlimit
```
```
In kernel/kthread.c (ffff8000101290cc)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - kernel/kthread.c:kthreadd
```
```
In kernel/nsproxy.c (ffff80001012b680)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - kernel/nsproxy.c:switch_task_namespaces
```
```
In kernel/sched/debug.c (ffff80001016310c)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
```
```
In kernel/kcmp.c (ffff80001019787c)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - kernel/kcmp.c:get_file_raw_ptr
```
```
In kernel/cgroup/namespace.c (ffff8000101d9f88)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:cgroupns_get
```
```
In kernel/cgroup/cpuset.c (ffff8000101e1064)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
```
In kernel/utsname.c (ffff8000101e5118)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_get
```
```
In kernel/pid_namespace.c (ffff8000101e75a8)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_for_children_get
```
```
In mm/oom_kill.c (ffff8000102b7b24)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:find_lock_task_mm
```
```
In mm/mmu_context.c (ffff8000102dfe68)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - mm/mmu_context.c:unuse_mm
  - mm/mmu_context.c:use_mm
```
```
In mm/mempolicy.c (ffff80001033bcb8)
Location: include/linux/sched/task.h:166
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
```
```
In fs/exec.c (ffff80001038c4e0)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - fs/exec.c:finalize_exec
  - fs/exec.c:__set_task_comm
  - fs/exec.c:__get_task_comm
```
```
In fs/file.c (ffff8000103b1f78)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - fs/file.c:exit_files
  - fs/file.c:reset_files_struct
  - fs/file.c:get_files_struct
```
```
In fs/namespace.c (ffff8000103b4da8)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - fs/namespace.c:mntns_get
```
```
In fs/fs_struct.c (ffff8000103d2c98)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - fs/fs_struct.c:unshare_fs_struct
  - fs/fs_struct.c:exit_fs
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/proc_namespace.c (ffff8000103e79dc)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/io_uring.c (ffff800010404afc)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In fs/coredump.c (ffff800010428a08)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/task_mmu.c (ffff80001043994c)
Location: include/linux/sched/task.h:166
Inline: True
```
```
In fs/proc/base.c (ffff80001043fb38)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - fs/proc/base.c:timerslack_ns_show
  - fs/proc/base.c:timerslack_ns_write
  - fs/proc/base.c:task_dump_owner
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
```
```
In fs/proc/array.c (ffff800010444d34)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In fs/proc/proc_net.c (ffff80001044d054)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_task_net
```
```
In fs/hugetlbfs/inode.c (ffff8000104e2b3c)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
```
```
In ipc/namespace.c (ffff80001052ca08)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - ipc/namespace.c:ipcns_get
```
```
In security/selinux/hooks.c (ffff8000105500f8)
Location: include/linux/sched/task.h:166
Inline: True
```
```
In security/yama/yama_lsm.c (ffff8000105aa728)
Location: include/linux/sched/task.h:166
Inline: True
```
```
In block/blk-ioc.c (ffff8000105e8e98)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - block/blk-ioc.c:get_task_io_context
  - block/blk-ioc.c:create_task_io_context
  - block/blk-ioc.c:exit_io_context
```
```
In block/ioprio.c (ffff8000105fdd58)
Location: include/linux/sched/task.h:166
Inline: True
```
```
In block/blk-cgroup.c (ffff80001060c3a0)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_can_attach
```
```
In drivers/tty/tty_io.c (ffff800010850140)
Location: include/linux/sched/task.h:166
Inline: True
```
```
In net/core/net_namespace.c (ffff800010bc1208)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_get
  - net/core/net_namespace.c:get_net_ns_by_pid
```
```
In net/core/netprio_cgroup.c (ffff800010c1d484)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:net_prio_attach
```
```
In net/core/netclassid_cgroup.c (ffff800010c1d7e0)
Location: include/linux/sched/task.h:166
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
In init/main.c (c1501228)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In kernel/fork.c (c035411c)
Location: include/linux/sched/task.h:166
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
In kernel/exit.c (c035a66c)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:mm_update_next_owner
```
```
In kernel/ptrace.c (c0362574)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - kernel/ptrace.c:__se_sys_ptrace
  - kernel/ptrace.c:ptrace_may_access
```
```
In kernel/sys.c (c036b2bc)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_auxv
  - kernel/sys.c:do_prlimit
```
```
In kernel/kthread.c (c037b634)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - kernel/kthread.c:kthreadd
```
```
In kernel/nsproxy.c (c037bc18)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - kernel/nsproxy.c:switch_task_namespaces
```
```
In kernel/kcmp.c (c03e2b00)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - kernel/kcmp.c:get_file_raw_ptr
```
```
In kernel/cgroup/namespace.c (c041c908)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:cgroupns_get
```
```
In kernel/cgroup/cpuset.c (c0421d0c)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
```
In kernel/utsname.c (c0425a1c)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_get
```
```
In kernel/pid_namespace.c (c0427a04)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_for_children_get
```
```
In mm/oom_kill.c (c04e4758)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:find_lock_task_mm
```
```
In mm/mmu_context.c (c0504984)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - mm/mmu_context.c:unuse_mm
  - mm/mmu_context.c:use_mm
```
```
In fs/exec.c (c0575924)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - fs/exec.c:__do_execve_file
  - fs/exec.c:finalize_exec
  - fs/exec.c:__set_task_comm
  - fs/exec.c:__get_task_comm
```
```
In fs/file.c (c0591434)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - fs/file.c:exit_files
  - fs/file.c:reset_files_struct
  - fs/file.c:get_files_struct
```
```
In fs/namespace.c (c05928cc)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - fs/namespace.c:mntns_get
```
```
In fs/fs_struct.c (c05ad7ac)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - fs/fs_struct.c:unshare_fs_struct
  - fs/fs_struct.c:exit_fs
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/proc_namespace.c (c05bf550)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/io_uring.c (c05d451c)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In fs/coredump.c (c05f1620)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/base.c (c0605814)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - fs/proc/base.c:timerslack_ns_show
  - fs/proc/base.c:timerslack_ns_write
  - fs/proc/base.c:task_dump_owner
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
```
```
In fs/proc/array.c (c0609930)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In fs/proc/proc_net.c (c0611610)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_task_net
```
```
In ipc/namespace.c (c06e5368)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - ipc/namespace.c:ipcns_get
```
```
In security/selinux/hooks.c (c07060c0)
Location: include/linux/sched/task.h:166
Inline: True
```
```
In security/yama/yama_lsm.c (c075a6a4)
Location: include/linux/sched/task.h:166
Inline: True
```
```
In block/blk-ioc.c (c07955b0)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - block/blk-ioc.c:get_task_io_context
  - block/blk-ioc.c:create_task_io_context
  - block/blk-ioc.c:exit_io_context
```
```
In block/ioprio.c (c07a8c70)
Location: include/linux/sched/task.h:166
Inline: True
```
```
In block/blk-cgroup.c (c07b6c04)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_can_attach
```
```
In drivers/tty/tty_io.c (c095c958)
Location: include/linux/sched/task.h:166
Inline: True
```
```
In net/core/net_namespace.c (c0cdba68)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_get
  - net/core/net_namespace.c:get_net_ns_by_pid
```
```
In net/core/netprio_cgroup.c (c0d34ed4)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:net_prio_attach
```
```
In net/core/netclassid_cgroup.c (c0d353bc)
Location: include/linux/sched/task.h:166
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
In init/main.c (c00000000134448c)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In kernel/fork.c (c00000000013bb50)
Location: include/linux/sched/task.h:166
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
In kernel/exit.c (c0000000001443c0)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:mm_update_next_owner
```
```
In kernel/ptrace.c (c00000000014f3cc)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:ptrace_may_access
```
```
In kernel/sys.c (c00000000015e1d4)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_auxv
  - kernel/sys.c:do_prlimit
  - kernel/sys.c:__se_compat_sys_old_getrlimit
  - kernel/sys.c:__se_sys_old_getrlimit
```
```
In kernel/kthread.c (c000000000173908)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - kernel/kthread.c:kthreadd
```
```
In kernel/nsproxy.c (c000000000174214)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - kernel/nsproxy.c:switch_task_namespaces
```
```
In kernel/sched/debug.c (c0000000001b9914)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
```
```
In kernel/kcmp.c (c0000000001f7734)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - kernel/kcmp.c:get_file_raw_ptr
```
```
In kernel/cgroup/namespace.c (c000000000247160)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:cgroupns_get
```
```
In kernel/cgroup/cpuset.c (c00000000024f014)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
```
In kernel/utsname.c (c0000000002554b0)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_get
```
```
In kernel/pid_namespace.c (c000000000257bb4)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_for_children_get
```
```
In mm/oom_kill.c (c00000000036f93c)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:find_lock_task_mm
```
```
In mm/mmu_context.c (c00000000039f8a8)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - mm/mmu_context.c:unuse_mm
  - mm/mmu_context.c:use_mm
```
```
In mm/mempolicy.c (c000000000416bbc)
Location: include/linux/sched/task.h:166
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
```
```
In fs/exec.c (c0000000004853a8)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - fs/exec.c:finalize_exec
  - fs/exec.c:__set_task_comm
  - fs/exec.c:__get_task_comm
```
```
In fs/file.c (c0000000004add54)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - fs/file.c:exit_files
  - fs/file.c:reset_files_struct
  - fs/file.c:get_files_struct
```
```
In fs/namespace.c (c0000000004b1310)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - fs/namespace.c:mntns_get
```
```
In fs/fs_struct.c (c0000000004d58c4)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - fs/fs_struct.c:unshare_fs_struct
  - fs/fs_struct.c:exit_fs
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/proc_namespace.c (c0000000004ee1a8)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/io_uring.c (c00000000050d480)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In fs/coredump.c (c000000000538be8)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/task_mmu.c (c00000000054ae44)
Location: include/linux/sched/task.h:166
Inline: True
```
```
In fs/proc/base.c (c0000000005537a4)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - fs/proc/base.c:timerslack_ns_show
  - fs/proc/base.c:timerslack_ns_write
  - fs/proc/base.c:task_dump_owner
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
```
```
In fs/proc/array.c (c00000000055a144)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In fs/proc/proc_net.c (c0000000005645d8)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_task_net
```
```
In fs/hugetlbfs/inode.c (c00000000061fd70)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
```
```
In ipc/namespace.c (c000000000678940)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - ipc/namespace.c:ipcns_get
```
```
In security/selinux/hooks.c (c0000000006aad64)
Location: include/linux/sched/task.h:166
Inline: True
```
```
In security/yama/yama_lsm.c (c000000000728570)
Location: include/linux/sched/task.h:166
Inline: True
```
```
In block/blk-ioc.c (c00000000077daa0)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - block/blk-ioc.c:get_task_io_context
  - block/blk-ioc.c:create_task_io_context
  - block/blk-ioc.c:exit_io_context
```
```
In block/ioprio.c (c000000000797840)
Location: include/linux/sched/task.h:166
Inline: True
```
```
In block/blk-cgroup.c (c0000000007a83a4)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_can_attach
```
```
In drivers/tty/tty_io.c (c0000000008f0680)
Location: include/linux/sched/task.h:166
Inline: True
```
```
In net/core/net_namespace.c (c000000000c99d30)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_get
  - net/core/net_namespace.c:get_net_ns_by_pid
```
```
In net/core/netprio_cgroup.c (c000000000d0e0c4)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:net_prio_attach
```
```
In net/core/netclassid_cgroup.c (c000000000d0eae0)
Location: include/linux/sched/task.h:166
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
In init/main.c (ffffffe000000f4a)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In kernel/fork.c (ffffffe0000c1cb0)
Location: include/linux/sched/task.h:166
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
In kernel/exit.c (ffffffe0000c5d3c)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:mm_update_next_owner
```
```
In kernel/ptrace.c (ffffffe0000cc402)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - kernel/ptrace.c:__se_sys_ptrace
  - kernel/ptrace.c:ptrace_may_access
```
```
In kernel/sys.c (ffffffe0000d27d2)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_auxv
  - kernel/sys.c:do_prlimit
```
```
In kernel/kthread.c (ffffffe0000dff3a)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - kernel/kthread.c:kthreadd
```
```
In kernel/nsproxy.c (ffffffe0000e046e)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - kernel/nsproxy.c:switch_task_namespaces
```
```
In kernel/kcmp.c (ffffffe00012893e)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - kernel/kcmp.c:get_file_raw_ptr
```
```
In kernel/cgroup/namespace.c (ffffffe000152934)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:cgroupns_get
```
```
In kernel/cgroup/cpuset.c (ffffffe000157db2)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
```
In kernel/utsname.c (ffffffe00015ad90)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_get
```
```
In kernel/pid_namespace.c (ffffffe00015cafe)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_for_children_get
```
```
In mm/oom_kill.c (ffffffe0001dbd7e)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:find_lock_task_mm
```
```
In mm/mmu_context.c (ffffffe0001f782a)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - mm/mmu_context.c:unuse_mm
  - mm/mmu_context.c:use_mm
```
```
In fs/exec.c (ffffffe00025eaea)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - fs/exec.c:__do_execve_file
  - fs/exec.c:finalize_exec
  - fs/exec.c:__set_task_comm
  - fs/exec.c:__get_task_comm
```
```
In fs/file.c (ffffffe000276058)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - fs/file.c:exit_files
  - fs/file.c:reset_files_struct
  - fs/file.c:get_files_struct
```
```
In fs/namespace.c (ffffffe000277ef2)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - fs/namespace.c:mntns_get
```
```
In fs/fs_struct.c (ffffffe00028debc)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - fs/fs_struct.c:unshare_fs_struct
  - fs/fs_struct.c:exit_fs
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/proc_namespace.c (ffffffe00029c84c)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/io_uring.c (ffffffe0002afecc)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In fs/coredump.c (ffffffe0002c6bb8)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/base.c (ffffffe0002d6dd4)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - fs/proc/base.c:timerslack_ns_show
  - fs/proc/base.c:timerslack_ns_write
  - fs/proc/base.c:task_dump_owner
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
```
```
In fs/proc/array.c (ffffffe0002dacdc)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In fs/proc/proc_net.c (ffffffe0002e1d4e)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_task_net
```
```
In fs/hugetlbfs/inode.c (ffffffe0003565fe)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
```
```
In ipc/namespace.c (ffffffe00038e960)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - ipc/namespace.c:ipcns_get
```
```
In security/selinux/hooks.c (ffffffe0003a89b6)
Location: include/linux/sched/task.h:166
Inline: True
```
```
In security/yama/yama_lsm.c (ffffffe0003f3834)
Location: include/linux/sched/task.h:166
Inline: True
```
```
In block/blk-ioc.c (ffffffe00042977c)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - block/blk-ioc.c:get_task_io_context
  - block/blk-ioc.c:create_task_io_context
  - block/blk-ioc.c:exit_io_context
```
```
In block/ioprio.c (ffffffe00043976e)
Location: include/linux/sched/task.h:166
Inline: True
```
```
In block/blk-cgroup.c (ffffffe000445320)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_can_attach
```
```
In drivers/tty/tty_io.c (ffffffe00052e5a2)
Location: include/linux/sched/task.h:166
Inline: True
```
```
In net/core/net_namespace.c (ffffffe00074e1d6)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_get
  - net/core/net_namespace.c:get_net_ns_by_pid
```
```
In net/core/netprio_cgroup.c (ffffffe000797116)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:net_prio_attach
```
```
In net/core/netclassid_cgroup.c (ffffffe00079739a)
Location: include/linux/sched/task.h:166
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
In init/main.c (ffffffff8288b268)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In kernel/fork.c (ffffffff8109a8e7)
Location: include/linux/sched/task.h:166
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
In kernel/exit.c (ffffffff8109fe88)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:mm_update_next_owner
```
```
In kernel/ptrace.c (ffffffff810a826b)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:ptrace_may_access
```
```
In kernel/sys.c (ffffffff810b4575)
Location: include/linux/sched/task.h:166
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
In kernel/kthread.c (ffffffff810c376e)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - kernel/kthread.c:kthreadd
```
```
In kernel/nsproxy.c (ffffffff810c6c90)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - kernel/nsproxy.c:switch_task_namespaces
```
```
In kernel/sched/debug.c (ffffffff810f6c31)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
```
```
In kernel/kcmp.c (ffffffff81129015)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - kernel/kcmp.c:get_file_raw_ptr
```
```
In kernel/cgroup/namespace.c (ffffffff8115fee5)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:cgroupns_get
```
```
In kernel/cgroup/cpuset.c (ffffffff811647b5)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
```
In kernel/utsname.c (ffffffff81169b75)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_get
```
```
In kernel/pid_namespace.c (ffffffff8116b935)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_for_children_get
```
```
In mm/oom_kill.c (ffffffff812222f7)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:find_lock_task_mm
```
```
In mm/mmu_context.c (ffffffff8124292b)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - mm/mmu_context.c:unuse_mm
  - mm/mmu_context.c:use_mm
```
```
In mm/mempolicy.c (ffffffff8129529c)
Location: include/linux/sched/task.h:166
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
```
```
In fs/exec.c (ffffffff812ddd18)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - fs/exec.c:finalize_exec
  - fs/exec.c:__set_task_comm
  - fs/exec.c:__get_task_comm
```
```
In fs/file.c (ffffffff812f89a4)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - fs/file.c:exit_files
  - fs/file.c:reset_files_struct
  - fs/file.c:get_files_struct
```
```
In fs/namespace.c (ffffffff812fa575)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - fs/namespace.c:mntns_get
```
```
In fs/fs_struct.c (ffffffff81313cb7)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - fs/fs_struct.c:unshare_fs_struct
  - fs/fs_struct.c:exit_fs
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/proc_namespace.c (ffffffff8132483a)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/io_uring.c (ffffffff8133b541)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In fs/coredump.c (ffffffff8135a883)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/task_mmu.c (ffffffff81367cf5)
Location: include/linux/sched/task.h:166
Inline: True
```
```
In fs/proc/base.c (ffffffff8136cd2f)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - fs/proc/base.c:timerslack_ns_show
  - fs/proc/base.c:timerslack_ns_write
  - fs/proc/base.c:task_dump_owner
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
```
```
In fs/proc/array.c (ffffffff81370c91)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In fs/proc/proc_net.c (ffffffff81377cf0)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_task_net
```
```
In fs/hugetlbfs/inode.c (ffffffff813fc8a9)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
```
```
In ipc/namespace.c (ffffffff8143c7c5)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - ipc/namespace.c:ipcns_get
```
```
In security/selinux/hooks.c (ffffffff8145a9c2)
Location: include/linux/sched/task.h:166
Inline: True
```
```
In security/yama/yama_lsm.c (ffffffff814ab49b)
Location: include/linux/sched/task.h:166
Inline: True
```
```
In block/blk-ioc.c (ffffffff814e2d6a)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - block/blk-ioc.c:get_task_io_context
  - block/blk-ioc.c:create_task_io_context
  - block/blk-ioc.c:exit_io_context
```
```
In block/ioprio.c (ffffffff814f4303)
Location: include/linux/sched/task.h:166
Inline: True
```
```
In block/blk-cgroup.c (ffffffff81501c00)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_can_attach
```
```
In drivers/tty/tty_io.c (ffffffff8164942a)
Location: include/linux/sched/task.h:166
Inline: True
```
```
In net/core/net_namespace.c (ffffffff818c4b15)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_get
  - net/core/net_namespace.c:get_net_ns_by_pid
```
```
In net/core/netprio_cgroup.c (ffffffff81916b5f)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:net_prio_attach
```
```
In net/core/netclassid_cgroup.c (ffffffff81916d78)
Location: include/linux/sched/task.h:166
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
In init/main.c (ffffffff828891f9)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In kernel/fork.c (ffffffff81089327)
Location: include/linux/sched/task.h:166
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
In kernel/exit.c (ffffffff8108e8b8)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:mm_update_next_owner
```
```
In kernel/ptrace.c (ffffffff81096c2b)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:ptrace_may_access
```
```
In kernel/sys.c (ffffffff810a2ea5)
Location: include/linux/sched/task.h:166
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
In kernel/kthread.c (ffffffff810b1f97)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - kernel/kthread.c:kthreadd
```
```
In kernel/nsproxy.c (ffffffff810b54b0)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - kernel/nsproxy.c:switch_task_namespaces
```
```
In kernel/sched/debug.c (ffffffff810e6e01)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
```
```
In kernel/kcmp.c (ffffffff8111b8a5)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - kernel/kcmp.c:get_file_raw_ptr
```
```
In kernel/cgroup/namespace.c (ffffffff81153155)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:cgroupns_get
```
```
In kernel/cgroup/cpuset.c (ffffffff81157a05)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
```
In kernel/utsname.c (ffffffff8115cd75)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_get
```
```
In kernel/pid_namespace.c (ffffffff8115eb35)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_for_children_get
```
```
In mm/oom_kill.c (ffffffff812154a7)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:find_lock_task_mm
```
```
In mm/mmu_context.c (ffffffff812358fb)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - mm/mmu_context.c:unuse_mm
  - mm/mmu_context.c:use_mm
```
```
In mm/mempolicy.c (ffffffff81286eac)
Location: include/linux/sched/task.h:166
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
```
```
In fs/exec.c (ffffffff812ce998)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - fs/exec.c:finalize_exec
  - fs/exec.c:__set_task_comm
  - fs/exec.c:__get_task_comm
```
```
In fs/file.c (ffffffff812e95c4)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - fs/file.c:exit_files
  - fs/file.c:reset_files_struct
  - fs/file.c:get_files_struct
```
```
In fs/namespace.c (ffffffff812eb195)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - fs/namespace.c:mntns_get
```
```
In fs/fs_struct.c (ffffffff813048c7)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - fs/fs_struct.c:unshare_fs_struct
  - fs/fs_struct.c:exit_fs
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/proc_namespace.c (ffffffff813153da)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/io_uring.c (ffffffff8132c221)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In fs/coredump.c (ffffffff8134b527)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/task_mmu.c (ffffffff81358ba5)
Location: include/linux/sched/task.h:166
Inline: True
```
```
In fs/proc/base.c (ffffffff8135d7bf)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - fs/proc/base.c:timerslack_ns_show
  - fs/proc/base.c:timerslack_ns_write
  - fs/proc/base.c:task_dump_owner
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
```
```
In fs/proc/array.c (ffffffff81361721)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In fs/proc/proc_net.c (ffffffff813687c0)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_task_net
```
```
In fs/hugetlbfs/inode.c (ffffffff813ed329)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
```
```
In ipc/namespace.c (ffffffff8142d235)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - ipc/namespace.c:ipcns_get
```
```
In security/selinux/hooks.c (ffffffff8144b3f2)
Location: include/linux/sched/task.h:166
Inline: True
```
```
In security/yama/yama_lsm.c (ffffffff8149bebb)
Location: include/linux/sched/task.h:166
Inline: True
```
```
In block/blk-ioc.c (ffffffff814d36fa)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - block/blk-ioc.c:get_task_io_context
  - block/blk-ioc.c:create_task_io_context
  - block/blk-ioc.c:exit_io_context
```
```
In block/ioprio.c (ffffffff814e4813)
Location: include/linux/sched/task.h:166
Inline: True
```
```
In block/blk-cgroup.c (ffffffff814f2110)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_can_attach
```
```
In drivers/tty/tty_io.c (ffffffff8162988a)
Location: include/linux/sched/task.h:166
Inline: True
```
```
In net/core/net_namespace.c (ffffffff8187ea55)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_get
  - net/core/net_namespace.c:get_net_ns_by_pid
```
```
In net/core/netprio_cgroup.c (ffffffff818d090f)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:net_prio_attach
```
```
In net/core/netclassid_cgroup.c (ffffffff818d0b28)
Location: include/linux/sched/task.h:166
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
In init/main.c (ffffffff8289e268)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In kernel/fork.c (ffffffff8109a897)
Location: include/linux/sched/task.h:166
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
In kernel/exit.c (ffffffff8109fe38)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:mm_update_next_owner
```
```
In kernel/ptrace.c (ffffffff810a77cb)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:ptrace_may_access
```
```
In kernel/sys.c (ffffffff810b3ad5)
Location: include/linux/sched/task.h:166
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
In kernel/kthread.c (ffffffff810c2cbe)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - kernel/kthread.c:kthreadd
```
```
In kernel/nsproxy.c (ffffffff810c61e0)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - kernel/nsproxy.c:switch_task_namespaces
```
```
In kernel/sched/debug.c (ffffffff810f3e41)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
```
```
In kernel/kcmp.c (ffffffff81126d35)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - kernel/kcmp.c:get_file_raw_ptr
```
```
In kernel/cgroup/namespace.c (ffffffff8115dcb5)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:cgroupns_get
```
```
In kernel/cgroup/cpuset.c (ffffffff81162585)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
```
In kernel/utsname.c (ffffffff81167945)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_get
```
```
In kernel/pid_namespace.c (ffffffff81169705)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_for_children_get
```
```
In mm/oom_kill.c (ffffffff81220097)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:find_lock_task_mm
```
```
In mm/mmu_context.c (ffffffff812406cb)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - mm/mmu_context.c:unuse_mm
  - mm/mmu_context.c:use_mm
```
```
In mm/mempolicy.c (ffffffff812930ac)
Location: include/linux/sched/task.h:166
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
```
```
In fs/exec.c (ffffffff812dbb28)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - fs/exec.c:finalize_exec
  - fs/exec.c:__set_task_comm
  - fs/exec.c:__get_task_comm
```
```
In fs/file.c (ffffffff812f67b4)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - fs/file.c:exit_files
  - fs/file.c:reset_files_struct
  - fs/file.c:get_files_struct
```
```
In fs/namespace.c (ffffffff812f8365)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - fs/namespace.c:mntns_get
```
```
In fs/fs_struct.c (ffffffff81311aa7)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - fs/fs_struct.c:unshare_fs_struct
  - fs/fs_struct.c:exit_fs
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/proc_namespace.c (ffffffff8132230a)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/io_uring.c (ffffffff81339011)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In fs/coredump.c (ffffffff81358353)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/task_mmu.c (ffffffff813657c5)
Location: include/linux/sched/task.h:166
Inline: True
```
```
In fs/proc/base.c (ffffffff8136a7ff)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - fs/proc/base.c:timerslack_ns_show
  - fs/proc/base.c:timerslack_ns_write
  - fs/proc/base.c:task_dump_owner
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
```
```
In fs/proc/array.c (ffffffff8136e761)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In fs/proc/proc_net.c (ffffffff813757c0)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_task_net
```
```
In fs/hugetlbfs/inode.c (ffffffff813f9c29)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
```
```
In ipc/namespace.c (ffffffff81438965)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - ipc/namespace.c:ipcns_get
```
```
In security/selinux/hooks.c (ffffffff81456a62)
Location: include/linux/sched/task.h:166
Inline: True
```
```
In security/yama/yama_lsm.c (ffffffff814a753b)
Location: include/linux/sched/task.h:166
Inline: True
```
```
In block/blk-ioc.c (ffffffff814dedfa)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - block/blk-ioc.c:get_task_io_context
  - block/blk-ioc.c:create_task_io_context
  - block/blk-ioc.c:exit_io_context
```
```
In block/ioprio.c (ffffffff814f0393)
Location: include/linux/sched/task.h:166
Inline: True
```
```
In block/blk-cgroup.c (ffffffff814fdc90)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_can_attach
```
```
In drivers/tty/tty_io.c (ffffffff816777ea)
Location: include/linux/sched/task.h:166
Inline: True
```
```
In net/core/net_namespace.c (ffffffff81915b15)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_get
  - net/core/net_namespace.c:get_net_ns_by_pid
```
```
In net/core/netprio_cgroup.c (ffffffff81967cef)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:net_prio_attach
```
```
In net/core/netclassid_cgroup.c (ffffffff81967f08)
Location: include/linux/sched/task.h:166
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
In init/main.c (ffffffff8289e26f)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In kernel/fork.c (ffffffff810a2517)
Location: include/linux/sched/task.h:166
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
In kernel/exit.c (ffffffff810a7da3)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:mm_update_next_owner
```
```
In kernel/ptrace.c (ffffffff810af8eb)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:ptrace_may_access
```
```
In kernel/sys.c (ffffffff810ba515)
Location: include/linux/sched/task.h:166
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
In kernel/kthread.c (ffffffff810cb0fe)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - kernel/kthread.c:kthreadd
```
```
In kernel/nsproxy.c (ffffffff810ce615)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - kernel/nsproxy.c:switch_task_namespaces
```
```
In kernel/sched/debug.c (ffffffff810fee31)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
```
```
In kernel/kcmp.c (ffffffff81133385)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - kernel/kcmp.c:get_file_raw_ptr
```
```
In kernel/cgroup/namespace.c (ffffffff8116af15)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:cgroupns_get
```
```
In kernel/cgroup/cpuset.c (ffffffff8116fb05)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
```
In kernel/utsname.c (ffffffff81175015)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_get
```
```
In kernel/pid_namespace.c (ffffffff81176e15)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_for_children_get
```
```
In mm/oom_kill.c (ffffffff8122f1a7)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:find_lock_task_mm
```
```
In mm/mmu_context.c (ffffffff8124fe4b)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - mm/mmu_context.c:unuse_mm
  - mm/mmu_context.c:use_mm
```
```
In mm/mempolicy.c (ffffffff812a2ed8)
Location: include/linux/sched/task.h:166
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
```
```
In fs/exec.c (ffffffff812eb258)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - fs/exec.c:finalize_exec
  - fs/exec.c:__set_task_comm
  - fs/exec.c:__get_task_comm
```
```
In fs/file.c (ffffffff813079e4)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - fs/file.c:exit_files
  - fs/file.c:reset_files_struct
  - fs/file.c:get_files_struct
```
```
In fs/namespace.c (ffffffff81308a45)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - fs/namespace.c:mntns_get
```
```
In fs/fs_struct.c (ffffffff813232ed)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - fs/fs_struct.c:unshare_fs_struct
  - fs/fs_struct.c:exit_fs
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/proc_namespace.c (ffffffff8133406c)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/io_uring.c (ffffffff8134b872)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In fs/coredump.c (ffffffff8136ba7c)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/task_mmu.c (ffffffff81378525)
Location: include/linux/sched/task.h:166
Inline: True
```
```
In fs/proc/base.c (ffffffff8137e0e1)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - fs/proc/base.c:timerslack_ns_show
  - fs/proc/base.c:timerslack_ns_write
  - fs/proc/base.c:task_dump_owner
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
```
```
In fs/proc/array.c (ffffffff813820b9)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In fs/proc/proc_net.c (ffffffff81389269)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_task_net
```
```
In fs/hugetlbfs/inode.c (ffffffff8140f879)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
```
```
In ipc/namespace.c (ffffffff8144fac5)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - ipc/namespace.c:ipcns_get
```
```
In security/selinux/hooks.c (ffffffff8146ea25)
Location: include/linux/sched/task.h:166
Inline: True
```
```
In security/yama/yama_lsm.c (ffffffff814bfe9b)
Location: include/linux/sched/task.h:166
Inline: True
```
```
In block/blk-ioc.c (ffffffff814f7c62)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - block/blk-ioc.c:get_task_io_context
  - block/blk-ioc.c:create_task_io_context
  - block/blk-ioc.c:exit_io_context
```
```
In block/ioprio.c (ffffffff81509437)
Location: include/linux/sched/task.h:166
Inline: True
```
```
In block/blk-cgroup.c (ffffffff81516735)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_can_attach
```
```
In drivers/tty/tty_io.c (ffffffff81691b17)
Location: include/linux/sched/task.h:166
Inline: True
```
```
In net/core/net_namespace.c (ffffffff81936d05)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_get
  - net/core/net_namespace.c:get_net_ns_by_pid
```
```
In net/core/netprio_cgroup.c (ffffffff81989c1f)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:net_prio_attach
```
```
In net/core/netclassid_cgroup.c (ffffffff8198a088)
Location: include/linux/sched/task.h:166
Inline: True
Inline callers:
  - net/core/netclassid_cgroup.c:update_classid_task
```
</details>
</li>
</ul>

## Differences
