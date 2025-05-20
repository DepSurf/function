# Function: <code>__refcount_inc</code>

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
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ioport.c (ffffffff810381a0)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:io_bitmap_share
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81055563)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105ebfb)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_init_fs_context
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff810659bf)
Location: include/linux/refcount.h:248
Inline: True
```
```
In kernel/fork.c (ffffffff810a3109)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/fork.c:kernel_clone
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_sighand
  - kernel/fork.c:mm_init
```
```
In kernel/exit.c (ffffffff810a7b24)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_continued
  - kernel/exit.c:wait_task_stopped
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:release_task
```
```
In kernel/user.c (ffffffff810b20fb)
Location: include/linux/refcount.h:248
Inline: True
```
```
In kernel/signal.c (ffffffff810b2bf7)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/sys.c (ffffffff810bf3be)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_prlimit64
```
```
In kernel/pid.c (ffffffff810c8402)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/pid.c:pidfd_getfd
  - kernel/pid.c:pidfd_create
  - kernel/pid.c:pidfd_get_pid
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:get_task_pid
  - kernel/pid.c:find_get_task_by_vpid
  - kernel/pid.c:alloc_pid
```
```
In kernel/kthread.c (ffffffff810cb2bd)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_stop
```
```
In kernel/nsproxy.c (ffffffff810d0b5c)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/nsproxy.c:validate_nsset
  - kernel/nsproxy.c:validate_nsset
  - kernel/nsproxy.c:create_new_namespaces
```
```
In kernel/cred.c (ffffffff810d29d0)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
```
```
In kernel/smpboot.c (ffffffff810d4471)
Location: include/linux/refcount.h:248
Inline: True
```
```
In kernel/usermode_driver.c (ffffffff810d556d)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/usermode_driver.c:umd_setup
```
```
In kernel/sched/core.c (ffffffff810dc831)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/sched/core.c:balance_push
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__ia32_sys_sched_setattr
  - kernel/sched/core.c:__x64_sys_sched_setattr
  - kernel/sched/core.c:do_sched_setscheduler
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:wake_q_add
```
```
In kernel/sched/fair.c (ffffffff810e981c)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_assign
```
```
In kernel/sched/rt.c (ffffffff810f796b)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
```
```
In kernel/sched/deadline.c (ffffffff810fb8dd)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:start_dl_timer
  - kernel/sched/deadline.c:task_non_contending
```
```
In kernel/sched/autogroup.c (ffffffff811036e2)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:sched_autogroup_fork
  - kernel/sched/autogroup.c:sched_autogroup_fork
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_move_group
```
```
In kernel/sched/psi.c (ffffffff8110a496)
Location: include/linux/refcount.h:248
Inline: True
```
```
In kernel/locking/rwsem.c (ffffffff8110b899)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
```
```
In kernel/locking/percpu-rwsem.c (ffffffff8110c6b5)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wake_function
```
```
In kernel/locking/rtmutex.c (ffffffff8110df9c)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_pi
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
```
In kernel/irq/manage.c (ffffffff8111ecd3)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/irq/manage.c:setup_irq_thread
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/rcu/update.c (ffffffff8112c7a7)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_trace_postgp
```
```
In kernel/kcmp.c (ffffffff8113c07c)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
```
```
In kernel/time/posix-timers.c (ffffffff8114cd91)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8114eb14)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_create
```
```
In kernel/time/namespace.c (ffffffff811562e3)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/time/namespace.c:timens_on_fork
  - kernel/time/namespace.c:timens_install
  - kernel/time/namespace.c:timens_install
  - kernel/time/namespace.c:timens_for_children_get
  - kernel/time/namespace.c:timens_get
  - kernel/time/namespace.c:copy_time_ns
  - kernel/time/namespace.c:clone_time_ns
```
```
In kernel/futex.c (ffffffff81156ec5)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/futex.c:mark_wake_futex
```
```
In kernel/cgroup/cgroup.c (ffffffff811745bf)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:css_task_iter_next
  - kernel/cgroup/cgroup.c:css_task_iter_advance_css_set
  - kernel/cgroup/cgroup.c:css_task_iter_advance_css_set
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/cgroup/namespace.c (ffffffff81175ecb)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:cgroupns_get
  - kernel/cgroup/namespace.c:cgroupns_install
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8117684f)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_find_create
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
```
In kernel/utsname.c (ffffffff81180554)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_install
  - kernel/utsname.c:utsns_get
  - kernel/utsname.c:copy_utsname
  - kernel/utsname.c:clone_uts_ns
```
```
In kernel/user_namespace.c (ffffffff81181404)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/user_namespace.c:ns_get_owner
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_get
```
```
In kernel/pid_namespace.c (ffffffff8118250c)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_get_parent
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:pidns_get
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/pid_namespace.c:create_pid_namespace
  - kernel/pid_namespace.c:create_pid_namespace
```
```
In kernel/audit.c (ffffffff811858e5)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/audit.c:audit_get_tty
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_send_queue
  - kernel/audit.c:auditd_set
  - kernel/audit.c:auditd_set
```
```
In kernel/auditfilter.c (ffffffff811891de)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In kernel/audit_watch.c (ffffffff8118f182)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_add_to_parent
  - kernel/audit_watch.c:audit_add_to_parent
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_tree.c (ffffffff8119166f)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_trim_trees
  - kernel/audit_tree.c:tag_chunk
  - kernel/audit_tree.c:create_chunk
  - kernel/audit_tree.c:replace_chunk
```
```
In kernel/hung_task.c (ffffffff811a1407)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
```
```
In kernel/seccomp.c (ffffffff811a3b33)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/seccomp.c:init_listener
  - kernel/seccomp.c:seccomp_attach_filter
  - kernel/seccomp.c:seccomp_attach_filter
```
```
In kernel/relay.c (ffffffff811a6174)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_open
  - kernel/relay.c:relay_create_buf
```
```
In kernel/trace/trace.c (ffffffff811b918b)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/trace/trace.c:buffer_pipe_buf_get
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811c8702)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/bpf/syscall.c (ffffffff811ff60a)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In kernel/bpf/task_iter.c (ffffffff8121836f)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:init_seq_pidns
```
```
In kernel/bpf/trampoline.c (ffffffff81222568)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_lookup
```
```
In kernel/bpf/btf.c (ffffffff8122c965)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_by_fd
  - kernel/bpf/btf.c:btf_get
```
```
In kernel/bpf/dispatcher.c (ffffffff8122ceda)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog
```
```
In kernel/bpf/offload.c (ffffffff81230d1c)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_map_offload_info_fill_ns
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill_ns
```
```
In kernel/events/core.c (ffffffff81248523)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_context
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:find_get_context
  - kernel/events/core.c:find_get_context
  - kernel/events/core.c:alloc_perf_context
```
```
In kernel/events/uprobes.c (ffffffff81253202)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/events/uprobes.c:prepare_uretprobe
  - kernel/events/uprobes.c:dup_utask
  - kernel/events/uprobes.c:build_probe_list
  - kernel/events/uprobes.c:build_probe_list
  - kernel/events/uprobes.c:alloc_uprobe
  - kernel/events/uprobes.c:__find_uprobe
```
```
In kernel/watch_queue.c (ffffffff81256ab6)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/watch_queue.c:get_watch_queue
  - kernel/watch_queue.c:add_watch_to_object
  - kernel/watch_queue.c:add_watch_to_object
```
```
In mm/oom_kill.c (ffffffff812613ca)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/backing-dev.c (ffffffff81281e56)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_get_by_id
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:wb_init
```
```
In mm/mlock.c (ffffffff812a2f25)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - mm/mlock.c:user_shm_lock
```
```
In mm/page_io.c (ffffffff812c3e79)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In mm/hugetlb.c (ffffffff812cf96f)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_vm_op_open
```
```
In mm/mempolicy.c (ffffffff812d9a23)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_migrate_pages
```
```
In mm/migrate.c (ffffffff812ed05c)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - mm/migrate.c:find_mm_struct
```
```
In mm/memory-failure.c (ffffffff8130cb6d)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - mm/memory-failure.c:add_to_kill
```
```
In fs/super.c (ffffffff813221a1)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/super.c:set_bdev_super_fc
  - fs/super.c:alloc_super
```
```
In fs/exec.c (ffffffff81326f13)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/exec.c:would_dump
```
```
In fs/pipe.c (ffffffff8132afd7)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/pipe.c:alloc_pipe_info
```
```
In fs/fcntl.c (ffffffff81335271)
Location: include/linux/refcount.h:248
Inline: True
```
```
In fs/namespace.c (ffffffff8134ceb7)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_get
  - fs/namespace.c:init_mount_tree
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/fs_context.c (ffffffff813640d3)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/fs_context.c:alloc_fs_context
  - fs/fs_context.c:alloc_fs_context
  - fs/fs_context.c:alloc_fs_context
  - fs/fs_context.c:alloc_fs_context
```
```
In fs/block_dev.c (ffffffff8136deda)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
```
```
In fs/proc_namespace.c (ffffffff81372e24)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/notify/group.c (ffffffff813740ba)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_get_group
```
```
In fs/notify/mark.c (ffffffff81374cd4)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_get_mark
```
```
In fs/notify/fanotify/fanotify.c (ffffffff81377d0c)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff813789dc)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:__do_sys_fanotify_init
```
```
In fs/eventpoll.c (ffffffff8137a748)
Location: include/linux/refcount.h:248
Inline: True
```
```
In fs/eventfd.c (ffffffff8137f625)
Location: include/linux/refcount.h:248
Inline: True
```
```
In fs/userfaultfd.c (ffffffff81381fe2)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_unmap_prep
  - fs/userfaultfd.c:userfaultfd_remove
  - fs/userfaultfd.c:mremap_userfaultfd_prep
  - fs/userfaultfd.c:dup_userfaultfd
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/io_uring.c (ffffffff813967d4)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_sq_offload_create
  - fs/io_uring.c:__io_sqe_files_scm
  - fs/io_uring.c:io_init_req
  - fs/io_uring.c:io_file_get
  - fs/io_uring.c:io_wq_submit_work
  - fs/io_uring.c:__io_queue_proc
  - fs/io_uring.c:io_openat2
  - fs/io_uring.c:__io_splice_prep
  - fs/io_uring.c:io_async_buf_func
  - fs/io_uring.c:io_iopoll_queue
  - fs/io_uring.c:__io_cqring_fill_event
  - fs/io_uring.c:io_prep_async_work
  - fs/io_uring.c:io_identity_cow
```
```
In fs/io-wq.c (ffffffff8139b635)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/io-wq.c:create_io_worker
```
```
In fs/crypto/keysetup.c (ffffffff813a518e)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_setup_encryption_info
  - fs/crypto/keysetup.c:fscrypt_setup_encryption_info
```
```
In fs/crypto/keysetup_v1.c (ffffffff813a58c4)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
```
```
In fs/posix_acl.c (ffffffff813b6d2e)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/posix_acl.c:set_cached_acl
```
```
In fs/proc/root.c (ffffffff813cc343)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/proc/root.c:proc_init_fs_context
  - fs/proc/root.c:proc_init_fs_context
  - fs/proc/root.c:proc_fill_super
  - fs/proc/root.c:proc_fill_super
```
```
In fs/proc/base.c (ffffffff813d1682)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:next_tgid
  - fs/proc/base.c:proc_pid_lookup
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_open
```
```
In fs/proc/generic.c (ffffffff813d26d3)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_lookup_de
```
```
In fs/proc/array.c (ffffffff813d3dff)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
```
```
In fs/proc/proc_net.c (ffffffff813db67e)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_task_net
  - fs/proc/proc_net.c:bpf_iter_init_seq_net
```
```
In fs/sysfs/mount.c (ffffffff813e434b)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/sysfs/mount.c:sysfs_init_fs_context
```
```
In fs/configfs/item.c (ffffffff813e95e9)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/configfs/item.c:config_group_find_item
```
```
In fs/ecryptfs/keystore.c (ffffffff8148189e)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
```
```
In fs/fuse/dev.c (ffffffff8148974a)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:__fuse_request_send
```
```
In fs/fuse/file.c (ffffffff81495255)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_send
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_write_inode
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_send_readpages
  - fs/fuse/file.c:fuse_async_req_send
```
```
In fs/fuse/inode.c (ffffffff81499426)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_fill_super_common
  - fs/fuse/inode.c:fuse_fill_super_submount
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_conn_init
```
```
In fs/fuse/dax.c (ffffffff8149d987)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_iomap_begin
```
```
In ipc/util.c (ffffffff814a3e5e)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_open
  - ipc/util.c:sysvipc_proc_open
```
```
In ipc/msg.c (ffffffff814a6e6d)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:expunge_all
```
```
In ipc/sem.c (ffffffff814abe36)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:copy_semundo
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:update_queue
  - ipc/sem.c:wake_const_ops
  - ipc/sem.c:perform_atomic_semop
  - ipc/sem.c:perform_atomic_semop_slow
```
```
In ipc/shm.c (ffffffff814ae4c6)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
```
```
In ipc/mqueue.c (ffffffff814b2653)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - ipc/mqueue.c:mq_init_ns
  - ipc/mqueue.c:mq_init_ns
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_init_fs_context
  - ipc/mqueue.c:mqueue_init_fs_context
  - ipc/mqueue.c:mqueue_get_inode
```
```
In ipc/namespace.c (ffffffff814b2d36)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - ipc/namespace.c:ipcns_install
  - ipc/namespace.c:ipcns_get
  - ipc/namespace.c:get_ipc_ns_exported
  - ipc/namespace.c:copy_ipcs
```
```
In security/keys/key.c (ffffffff814b489d)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_user_lookup
```
```
In security/keys/keyring.c (ffffffff814b607a)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_gc_select_iterator
  - security/keys/keyring.c:__key_link
  - security/keys/keyring.c:find_key_to_update
  - security/keys/keyring.c:keyring_search_rcu
```
```
In security/keys/keyctl.c (ffffffff814b72a6)
Location: include/linux/refcount.h:248
Inline: True
```
```
In security/keys/process_keys.c (ffffffff814bad40)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:install_session_keyring_to_cred
```
```
In security/keys/request_key.c (ffffffff814bb927)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:cache_requested_key
  - security/keys/request_key.c:check_cached_key
```
```
In security/keys/request_key_auth.c (ffffffff814bc272)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
```
```
In security/apparmor/apparmorfs.c (ffffffff8150abb2)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
  - security/apparmor/apparmorfs.c:seq_profile_hash_open
  - security/apparmor/apparmorfs.c:seq_profile_attach_open
  - security/apparmor/apparmorfs.c:seq_profile_mode_open
  - security/apparmor/apparmorfs.c:seq_profile_name_open
  - security/apparmor/apparmorfs.c:multi_transaction_read
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
```
```
In security/apparmor/capability.c (ffffffff8150de7a)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/apparmor/capability.c:audit_caps
```
```
In security/apparmor/task.c (ffffffff8150e7c1)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_set_current_onexec
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_get_task_label
```
```
In security/apparmor/domain.c (ffffffff81516190)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:find_attach
  - security/apparmor/domain.c:find_attach
```
```
In security/apparmor/policy.c (ffffffff81519547)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_alloc_profile
  - security/apparmor/policy.c:__add_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff8151a501)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:do_loaddata_free
```
```
In security/apparmor/procattr.c (ffffffff8151c42a)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff82ff3b35)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_sock_graft
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_task_alloc
  - security/apparmor/lsm.c:apparmor_task_alloc
  - security/apparmor/lsm.c:apparmor_task_alloc
  - security/apparmor/lsm.c:apparmor_cred_transfer
  - security/apparmor/lsm.c:apparmor_cred_prepare
```
```
In security/apparmor/resource.c (ffffffff815228f6)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff815243fc)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:aa_file_perm
```
```
In security/apparmor/policy_ns.c (ffffffff81524fcf)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:__aa_find_or_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:aa_lookupn_ns
  - security/apparmor/policy_ns.c:aa_findn_ns
  - security/apparmor/policy_ns.c:alloc_ns
  - security/apparmor/policy_ns.c:alloc_ns
```
```
In security/apparmor/label.c (ffffffff81527224)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:__label_insert
  - security/apparmor/label.c:__label_insert
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/label.c:__proxy_share
  - security/apparmor/label.c:__aa_proxy_redirect
  - security/apparmor/label.c:aa_alloc_proxy
```
```
In security/apparmor/mount.c (ffffffff8152b64c)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:build_pivotroot
```
```
In security/apparmor/net.c (0)
Location: include/linux/refcount.h:248
Inline: True
```
```
In security/apparmor/af_unix.c (ffffffff8152e1c5)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
```
```
In security/yama/yama_lsm.c (ffffffff8152ed53)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_task_prctl
  - security/yama/yama_lsm.c:report_access
  - security/yama/yama_lsm.c:report_access
```
```
In crypto/api.c (ffffffff8153b557)
Location: include/linux/refcount.h:248
Inline: True
```
```
In crypto/algapi.c (ffffffff8153d07a)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_stats_get
  - crypto/algapi.c:crypto_spawn_alg
```
```
In crypto/algboss.c (ffffffff81545dec)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - crypto/algboss.c:cryptomgr_schedule_probe
```
```
In crypto/asymmetric_keys/restrict.c (ffffffff815557ed)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
```
```
In block/bsg.c (ffffffff81583729)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - block/bsg.c:bsg_open
```
```
In block/blk-cgroup.c (ffffffff81584d79)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_online
```
```
In lib/cpu_rmap.c (ffffffff815fce15)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
```
```
In lib/klist.c (ffffffff8160f02b)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - lib/klist.c:klist_next
  - lib/klist.c:klist_prev
```
```
In lib/kobject.c (ffffffff8160f389)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - lib/kobject.c:kobject_get
```
```
In lib/kobject_uevent.c (ffffffff81610a90)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_broadcast_untagged
```
```
In drivers/pinctrl/core.c (ffffffff81628516)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_get
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff816756b2)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context
```
```
In drivers/acpi/ec.c (ffffffff816ae9d5)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_query
```
```
In drivers/acpi/thermal.c (ffffffff81704acf)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/acpi/thermal.c:acpi_thermal_check_fn
```
```
In drivers/clk/clk.c (ffffffff8171a59b)
Location: include/linux/refcount.h:248
Inline: True
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff8173d1a6)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
```
```
In drivers/reset/core.c (ffffffff8174ea73)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/reset/core.c:__reset_control_get_internal
```
```
In drivers/tty/tty_io.c (ffffffff8175283d)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_fasync
  - drivers/tty/tty_io.c:tty_open_by_driver
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:tty_find_polling_driver
```
```
In drivers/tty/tty_port.c (ffffffff8175b8e6)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_tty_get
```
```
In drivers/tty/tty_mutex.c (ffffffff8175c254)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/tty_mutex.c:tty_lock
```
```
In drivers/tty/tty_ldsem.c (ffffffff81c44ca4)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:down_read_failed
```
```
In drivers/tty/tty_jobctrl.c (ffffffff8175c981)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_get_pgrp
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:get_current_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
```
```
In drivers/tty/pty.c (ffffffff8175e35a)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/tty/pty.c:pty_common_install
  - drivers/tty/pty.c:pty_common_install
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff81760277)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_setactivate
  - drivers/tty/vt/vt_ioctl.c:vt_k_ioctl
```
```
In drivers/char/virtio_console.c (ffffffff8178f61b)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:find_port_by_devt
```
```
In drivers/char/hw_random/core.c (ffffffff817944c0)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:hwrng_register
  - drivers/char/hw_random/core.c:hwrng_fillfn
```
```
In drivers/iommu/ioasid.c (ffffffff817bf8a3)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/iommu/ioasid.c:ioasid_get
```
```
In drivers/connector/connector.c (ffffffff817c1d5d)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_call_callback
```
```
In drivers/lightnvm/core.c (ffffffff817c4f41)
Location: include/linux/refcount.h:248
Inline: True
```
```
In drivers/base/core.c (ffffffff817c9d0a)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/power/runtime.c (ffffffff817de997)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_get_suppliers
  - drivers/base/power/runtime.c:rpm_get_suppliers
```
```
In drivers/base/firmware_loader/main.c (ffffffff817ea7ce)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:assign_fw
```
```
In drivers/nvdimm/core.c (ffffffff8181dddf)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff8182190a)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:get_ndd
```
```
In drivers/dax/bus.c (ffffffff81834aee)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:alloc_dax_region
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81837b8d)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff818381c1)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff81838a42)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
```
```
In drivers/dma-buf/dma-resv.c (ffffffff81839592)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
```
```
In drivers/dma-buf/sync_file.c (ffffffff8183b8ed)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_get_fence
  - drivers/dma-buf/sync_file.c:sync_file_create
```
```
In drivers/dma-buf/sw_sync.c (ffffffff8183ce4e)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_pt_create
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff8184dfde)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
```
```
In drivers/scsi/sr.c (ffffffff8185aca7)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_block_check_events
  - drivers/scsi/sr.c:sr_block_open
```
```
In drivers/scsi/sg.c (ffffffff8185f788)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_sfp
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/ata/libata-core.c (ffffffff8186901a)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_get
```
```
In drivers/net/phy/phy_device.c (ffffffff81892fd3)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_package_join
```
```
In drivers/net/phy/sfp-bus.c (ffffffff81896c25)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_get
```
```
In drivers/net/tun.c (ffffffff8189d7b5)
Location: include/linux/refcount.h:248
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff818a2266)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_connect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_init
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_bridge_channels
  - drivers/net/ppp/ppp_generic.c:ppp_bridge_channels
```
```
In drivers/net/xen-netfront.c (ffffffff818a68d5)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_make_one_txreq
```
```
In drivers/vfio/vfio.c (ffffffff818abae4)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_get_external_user
  - drivers/vfio/vfio.c:vfio_group_fops_open
  - drivers/vfio/vfio.c:vfio_group_set_container
  - drivers/vfio/vfio.c:vfio_del_group_dev
  - drivers/vfio/vfio.c:vfio_device_get_from_name
  - drivers/vfio/vfio.c:vfio_device_get_from_name
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_iommu_group_notifier
  - drivers/vfio/vfio.c:vfio_group_get_device
  - drivers/vfio/vfio.c:vfio_group_get_device
  - drivers/vfio/vfio.c:vfio_group_get_from_iommu
  - drivers/vfio/vfio.c:vfio_create_group
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff818af5d7)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff818b2235)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_reflck_find
```
```
In drivers/usb/core/hub.c (ffffffff818c3152)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/hcd.c (ffffffff818c8d85)
Location: include/linux/refcount.h:248
Inline: True
```
```
In drivers/usb/core/urb.c (ffffffff818cbd45)
Location: include/linux/refcount.h:248
Inline: True
```
```
In drivers/usb/core/message.c (ffffffff818cf423)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_set_configuration
```
```
In drivers/usb/core/file.c (ffffffff818d3637)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/usb/core/file.c:init_usb_class
```
```
In drivers/usb/core/devio.c (ffffffff818d7f52)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:async_completed
```
```
In drivers/md/dm.c (ffffffff8197c1d5)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_get_table_device
```
```
In drivers/md/dm-table.c (ffffffff81980e56)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_get_device
```
```
In drivers/opp/core.c (ffffffff8199318f)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_adjust_voltage
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_find_freq_ceil_by_volt
  - drivers/opp/core.c:dev_pm_opp_find_freq_floor
  - drivers/opp/core.c:_find_freq_ceil
  - drivers/opp/core.c:dev_pm_opp_find_level_exact
  - drivers/opp/core.c:dev_pm_opp_find_freq_exact
  - drivers/opp/core.c:_find_opp_table_unlocked
```
```
In drivers/remoteproc/remoteproc_virtio.c (ffffffff819cccd0)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_add_virtio_dev
```
```
In drivers/nvmem/core.c (ffffffff819d938a)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/nvmem/core.c:__nvmem_device_get
```
```
In net/socket.c (ffffffff819de727)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/socket.c:get_net_ns
```
```
In net/core/sock.c (ffffffff819e5380)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/core/sock.c:skb_set_owner_w
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
```
In net/core/skbuff.c (ffffffff819f43a7)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:sock_zerocopy_realloc
  - net/core/skbuff.c:sock_zerocopy_alloc
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/core/datagram.c (ffffffff819f55ca)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_from_queue
```
```
In net/core/scm.c (ffffffff819f6c85)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
  - net/core/scm.c:__scm_send
```
```
In net/core/net_namespace.c (ffffffff819f87f7)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_get
  - net/core/net_namespace.c:get_net_ns_by_pid
  - net/core/net_namespace.c:get_net_ns_by_fd
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:copy_net_ns
```
```
In net/core/dev.c (ffffffff81a0a5f4)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/neighbour.c (ffffffff81a15ebe)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_alloc
```
```
In net/core/rtnetlink.c (ffffffff81a21c5e)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_send
```
```
In net/core/flow_offload.c (ffffffff81a390da)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_dev_register
```
```
In net/core/net-sysfs.c (ffffffff81a39f2e)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/core/net-sysfs.c:net_grab_current_ns
```
```
In net/core/page_pool.c (ffffffff81a3d9ee)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_use_xdp_mem
```
```
In net/core/skmsg.c (ffffffff81a40013)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_psock_init
```
```
In net/core/netpoll.c (ffffffff81a40f0e)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_setup
```
```
In net/core/sock_map.c (ffffffff81a54557)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_free
```
```
In net/core/devlink.c (ffffffff81a59f07)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_health_reporter_get_from_attrs
  - net/core/devlink.c:devlink_health_reporter_get_from_attrs
```
```
In net/sched/sch_generic.c (ffffffff81a6e320)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/sched/sch_generic.c:attach_default_qdiscs
  - net/sched/sch_generic.c:attach_default_qdiscs
```
```
In net/sched/sch_api.c (ffffffff81a7393c)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
```
```
In net/sched/cls_api.c (ffffffff81a755c0)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_chain_tp_find
  - net/sched/cls_api.c:tcf_chain_tp_insert_unique
  - net/sched/cls_api.c:__tcf_block_find
  - net/sched/cls_api.c:__tcf_get_next_proto
```
```
In net/sched/act_api.c (ffffffff81a7b38a)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_idr_check_alloc
  - net/sched/act_api.c:tcf_idr_search
```
```
In net/netlink/af_netlink.c (ffffffff81a840e7)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_getsockbyfilp
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/netfilter/nf_queue.c (ffffffff81a99723)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
```
```
In net/ipv4/route.c (ffffffff81a9d676)
Location: include/linux/refcount.h:248
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff81aa2e50)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_reinit
```
```
In net/ipv4/ip_output.c (ffffffff81aa769a)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/ip_sockglue.c (ffffffff81aab52e)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_ra_control
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ab0ace)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/tcp.c (ffffffff81ab82f7)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff81abc814)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (ffffffff81aca591)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tso_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_tsq_handler
```
```
In net/ipv4/tcp_timer.c (ffffffff81acdc8c)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad4c09)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
```
```
In net/ipv4/raw.c (ffffffff81adc2c0)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_hash_sk
```
```
In net/ipv4/udp.c (ffffffff81ae3440)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/arp.c (ffffffff81ae7e36)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_constructor
```
```
In net/ipv4/devinet.c (ffffffff81aee83c)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:rtm_to_ifaddr
```
```
In net/ipv4/igmp.c (ffffffff81af46a0)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv4/igmp.c:____ip_mc_inc_group
  - net/ipv4/igmp.c:igmpv3_add_delrec
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_ifc_event
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
```
```
In net/ipv4/fib_trie.c (ffffffff81b00be1)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv4/inet_fragment.c (ffffffff81b02658)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:fqdir_init
```
```
In net/ipv4/ping.c (ffffffff81b04b26)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_get_port
```
```
In net/ipv4/nexthop.c (ffffffff81b087aa)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:__remove_nexthop_fib
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81b19163)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_check
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b1f2bd)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:__xfrm_policy_link
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
```
```
In net/xfrm/xfrm_state.c (ffffffff81b299db)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:xfrm_state_lookup_byspi
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
```
```
In net/xfrm/xfrm_output.c (ffffffff81b2eca6)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
```
```
In net/unix/af_unix.c (ffffffff81b33b0a)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:maybe_init_creds
  - net/unix/af_unix.c:unix_getname
  - net/unix/af_unix.c:unix_getname
  - net/unix/af_unix.c:unix_socketpair
  - net/unix/af_unix.c:unix_socketpair
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:copy_peercred
  - net/unix/af_unix.c:init_peercred
  - net/unix/af_unix.c:__unix_insert_socket
```
```
In net/ipv6/anycast.c (ffffffff81b3a153)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/ip6_output.c (ffffffff81b3c7ce)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/addrconf.c (ffffffff81b4d459)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_set_iftoken
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_begin
  - net/ipv6/addrconf.c:addrconf_dad_kick
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_add_linklocal
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/route.c (ffffffff81b53244)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:ip6_route_check_nh
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_rt_copy_init
  - net/ipv6/route.c:ip6_rt_copy_init
  - net/ipv6/route.c:ip6_dst_ifdown
```
```
In net/ipv6/ip6_fib.c (ffffffff81b5da96)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_purge_rt
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81b5fbc8)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ip6_ra_control
```
```
In net/ipv6/ndisc.c (ffffffff81b62b17)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change
  - net/ipv6/ndisc.c:ndisc_netdev_event
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_unsol_na
  - net/ipv6/ndisc.c:ndisc_constructor
  - net/ipv6/ndisc.c:ndisc_constructor
```
```
In net/ipv6/mcast.c (ffffffff81b71739)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_dad_timer_expire
  - net/ipv6/mcast.c:ipv6_mc_dad_complete
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:mld_add_delrec
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b79308)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_req
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81b8712d)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
```
```
In net/ipv6/syncookies.c (ffffffff81b8ac60)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/calipso.c (ffffffff81b8b5fe)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_cache_check
```
```
In net/packet/af_packet.c (ffffffff81b98cc7)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/ncsi/ncsi-cmd.c (ffffffff81bae74a)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81bb4a7b)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
```
```
In net/xdp/xsk.c (ffffffff81bb631e)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
```
```
In net/xdp/xdp_umem.c (ffffffff81bb82b1)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
  - net/xdp/xdp_umem.c:xdp_get_umem
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81bb9bba)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_get_pool
```
```
In net/mptcp/protocol.c (ffffffff81bbe35d)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_finish_join
  - net/mptcp/protocol.c:mptcp_accept
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:mptcp_retransmit_timer
```
```
In net/mptcp/subflow.c (ffffffff81bc366a)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
  - net/mptcp/subflow.c:__mptcp_subflow_connect
  - net/mptcp/subflow.c:get_mapping_status
  - net/mptcp/subflow.c:mptcp_subflow_reset
```
```
In net/mptcp/options.c (ffffffff81bc5350)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_incoming_options
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
In init/main.c (ffffffff831b9a3f)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In arch/x86/kernel/ioport.c (ffffffff81039ce0)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:io_bitmap_share
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81056c5b)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105f41b)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_init_fs_context
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8106633c)
Location: include/linux/refcount.h:248
Inline: True
```
```
In kernel/fork.c (ffffffff810a3c8b)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/fork.c:kernel_clone
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_sighand
  - kernel/fork.c:mm_init
```
```
In kernel/exit.c (ffffffff810a9968)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_stopped
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:release_task
```
```
In kernel/user.c (ffffffff810b373b)
Location: include/linux/refcount.h:248
Inline: True
```
```
In kernel/signal.c (ffffffff810b4239)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/sys.c (ffffffff810c0d9a)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_prlimit64
```
```
In kernel/pid.c (ffffffff810c9eb2)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/pid.c:pidfd_getfd
  - kernel/pid.c:pidfd_create
  - kernel/pid.c:pidfd_get_pid
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:get_task_pid
  - kernel/pid.c:find_get_task_by_vpid
  - kernel/pid.c:alloc_pid
```
```
In kernel/kthread.c (ffffffff810ccced)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_stop
```
```
In kernel/nsproxy.c (ffffffff810d273c)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/nsproxy.c:validate_nsset
  - kernel/nsproxy.c:validate_nsset
  - kernel/nsproxy.c:create_new_namespaces
```
```
In kernel/cred.c (ffffffff810d45f0)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
```
```
In kernel/smpboot.c (ffffffff810d60b1)
Location: include/linux/refcount.h:248
Inline: True
```
```
In kernel/usermode_driver.c (ffffffff810d722d)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/usermode_driver.c:umd_setup
```
```
In kernel/sched/core.c (ffffffff810de418)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/sched/core.c:balance_push
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__ia32_sys_sched_setattr
  - kernel/sched/core.c:__x64_sys_sched_setattr
  - kernel/sched/core.c:do_sched_setscheduler
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:wake_q_add
```
```
In kernel/sched/fair.c (ffffffff810ea0ed)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_assign
```
```
In kernel/sched/rt.c (ffffffff810f972b)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
```
```
In kernel/sched/deadline.c (ffffffff810fdc0d)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:start_dl_timer
  - kernel/sched/deadline.c:task_non_contending
```
```
In kernel/sched/autogroup.c (ffffffff811059e2)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:sched_autogroup_fork
  - kernel/sched/autogroup.c:sched_autogroup_fork
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_move_group
```
```
In kernel/sched/psi.c (ffffffff8110d040)
Location: include/linux/refcount.h:248
Inline: True
```
```
In kernel/locking/rwsem.c (ffffffff8110d6b8)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
```
```
In kernel/locking/percpu-rwsem.c (ffffffff8110e4e5)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wake_function
```
```
In kernel/locking/rtmutex.c (ffffffff81c37324)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_pi
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
```
In kernel/irq/manage.c (ffffffff8111ef53)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/irq/manage.c:setup_irq_thread
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/rcu/update.c (ffffffff8112cd07)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_trace_postgp
```
```
In kernel/kcmp.c (ffffffff8113d22b)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
```
```
In kernel/time/posix-timers.c (ffffffff8114f267)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8114ffa4)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_create
```
```
In kernel/time/namespace.c (ffffffff811576e3)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/time/namespace.c:timens_on_fork
  - kernel/time/namespace.c:timens_install
  - kernel/time/namespace.c:timens_install
  - kernel/time/namespace.c:timens_for_children_get
  - kernel/time/namespace.c:timens_get
  - kernel/time/namespace.c:copy_time_ns
  - kernel/time/namespace.c:copy_time_ns
```
```
In kernel/futex.c (ffffffff811582d5)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/futex.c:mark_wake_futex
```
```
In kernel/cgroup/cgroup.c (ffffffff8117518e)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:css_task_iter_next
  - kernel/cgroup/cgroup.c:css_task_iter_advance_css_set
  - kernel/cgroup/cgroup.c:css_task_iter_advance_css_set
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/cgroup/namespace.c (ffffffff81176b2b)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:cgroupns_get
  - kernel/cgroup/namespace.c:cgroupns_install
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81177547)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
```
In kernel/utsname.c (ffffffff811815b4)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_install
  - kernel/utsname.c:utsns_get
  - kernel/utsname.c:copy_utsname
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (ffffffff811824a7)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/user_namespace.c:ns_get_owner
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_get
```
```
In kernel/pid_namespace.c (ffffffff81183659)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_get_parent
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:pidns_get
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/pid_namespace.c:create_pid_namespace
  - kernel/pid_namespace.c:create_pid_namespace
```
```
In kernel/audit.c (ffffffff811868d5)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/audit.c:audit_get_tty
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_send_queue
```
```
In kernel/auditfilter.c (ffffffff81189fa4)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In kernel/audit_watch.c (ffffffff8118ffb3)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_tree.c (ffffffff811925af)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_trim_trees
  - kernel/audit_tree.c:tag_chunk
  - kernel/audit_tree.c:create_chunk
  - kernel/audit_tree.c:replace_chunk
```
```
In kernel/hung_task.c (ffffffff811a2067)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
```
```
In kernel/seccomp.c (ffffffff811a552d)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_attach_filter
  - kernel/seccomp.c:seccomp_attach_filter
```
```
In kernel/relay.c (ffffffff811a70a4)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_open
  - kernel/relay.c:relay_create_buf
```
```
In kernel/trace/trace.c (ffffffff811b9a55)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/trace/trace.c:buffer_pipe_buf_get
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811c99b7)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/bpf/syscall.c (ffffffff811fffbc)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In kernel/bpf/task_iter.c (ffffffff8121b7bf)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:init_seq_pidns
```
```
In kernel/bpf/trampoline.c (ffffffff81226fed)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_get
```
```
In kernel/bpf/btf.c (ffffffff81231725)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_by_fd
  - kernel/bpf/btf.c:btf_get
```
```
In kernel/bpf/dispatcher.c (ffffffff81231d3a)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog
```
```
In kernel/bpf/offload.c (ffffffff81234ebc)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_map_offload_info_fill_ns
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill_ns
```
```
In kernel/events/core.c (ffffffff8124c42d)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_context
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_remove_from_owner
  - kernel/events/core.c:find_get_context
  - kernel/events/core.c:find_get_context
  - kernel/events/core.c:alloc_perf_context
```
```
In kernel/events/uprobes.c (ffffffff812573f2)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/events/uprobes.c:prepare_uretprobe
  - kernel/events/uprobes.c:uprobe_copy_process
  - kernel/events/uprobes.c:uprobe_mmap
  - kernel/events/uprobes.c:uprobe_mmap
  - kernel/events/uprobes.c:alloc_uprobe
  - kernel/events/uprobes.c:find_uprobe
```
```
In kernel/watch_queue.c (ffffffff8125af56)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/watch_queue.c:get_watch_queue
  - kernel/watch_queue.c:add_watch_to_object
  - kernel/watch_queue.c:add_watch_to_object
```
```
In mm/oom_kill.c (ffffffff81265c0a)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/backing-dev.c (ffffffff81286e16)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_get_by_id
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:wb_init
```
```
In mm/mlock.c (ffffffff812a8785)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - mm/mlock.c:user_shm_lock
```
```
In mm/page_io.c (ffffffff812cac79)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In mm/hugetlb.c (ffffffff812d66cf)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_vm_op_open
```
```
In mm/mempolicy.c (ffffffff812e12a3)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_migrate_pages
```
```
In mm/migrate.c (ffffffff812f33fc)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - mm/migrate.c:find_mm_struct
```
```
In mm/huge_memory.c (ffffffff81300596)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_pid
```
```
In mm/memory-failure.c (ffffffff813132ca)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - mm/memory-failure.c:add_to_kill
```
```
In fs/super.c (ffffffff81328261)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/super.c:set_bdev_super_fc
  - fs/super.c:alloc_super
```
```
In fs/exec.c (ffffffff8132cfc5)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/exec.c:would_dump
```
```
In fs/pipe.c (ffffffff81330fe7)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/pipe.c:alloc_pipe_info
```
```
In fs/fcntl.c (ffffffff8133b341)
Location: include/linux/refcount.h:248
Inline: True
```
```
In fs/namespace.c (ffffffff81353a97)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_get
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:alloc_mnt_ns
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:mnt_init
```
```
In fs/fs_context.c (ffffffff8136ab4e)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/fs_context.c:alloc_fs_context
  - fs/fs_context.c:alloc_fs_context
  - fs/fs_context.c:alloc_fs_context
  - fs/fs_context.c:alloc_fs_context
```
```
In fs/block_dev.c (ffffffff81374874)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
```
```
In fs/proc_namespace.c (ffffffff813797b4)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/notify/group.c (ffffffff8137acfa)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_get_group
```
```
In fs/notify/mark.c (ffffffff8137b694)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_get_mark
```
```
In fs/notify/fanotify/fanotify.c (ffffffff8137e7d3)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/eventpoll.c (ffffffff81381b75)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_create
```
```
In fs/eventfd.c (ffffffff813862a5)
Location: include/linux/refcount.h:248
Inline: True
```
```
In fs/userfaultfd.c (ffffffff81389050)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_unmap_prep
  - fs/userfaultfd.c:userfaultfd_remove
  - fs/userfaultfd.c:mremap_userfaultfd_prep
  - fs/userfaultfd.c:dup_userfaultfd
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/io_uring.c (ffffffff81399e8e)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:__io_sqe_files_scm
  - fs/io_uring.c:io_get_sq_data
```
```
In fs/io-wq.c (ffffffff813a370d)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/io-wq.c:io_wq_create
  - fs/io-wq.c:io_wq_create
```
```
In fs/crypto/keysetup.c (ffffffff813ac27e)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_setup_encryption_info
  - fs/crypto/keysetup.c:fscrypt_setup_encryption_info
```
```
In fs/crypto/keysetup_v1.c (ffffffff813ac924)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
```
```
In fs/posix_acl.c (ffffffff813bdd91)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/posix_acl.c:set_cached_acl
```
```
In fs/proc/root.c (ffffffff813d3303)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/proc/root.c:proc_init_fs_context
  - fs/proc/root.c:proc_init_fs_context
  - fs/proc/root.c:proc_fill_super
  - fs/proc/root.c:proc_fill_super
```
```
In fs/proc/base.c (ffffffff813d857c)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:next_tgid
  - fs/proc/base.c:proc_pid_lookup
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_open
```
```
In fs/proc/generic.c (ffffffff813d94d3)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_lookup_de
```
```
In fs/proc/array.c (ffffffff813dac2f)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
```
```
In fs/proc/proc_net.c (ffffffff813e25ae)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_task_net
  - fs/proc/proc_net.c:bpf_iter_init_seq_net
```
```
In fs/sysfs/mount.c (ffffffff813eaf4b)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/sysfs/mount.c:sysfs_init_fs_context
```
```
In fs/configfs/item.c (ffffffff813f0149)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/configfs/item.c:config_group_find_item
```
```
In fs/ecryptfs/keystore.c (ffffffff814872fe)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
```
```
In fs/fuse/dev.c (ffffffff8148efd0)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:fuse_simple_request
```
```
In fs/fuse/file.c (ffffffff8149a2ad)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_send
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_write_inode
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_readahead
  - fs/fuse/file.c:fuse_async_req_send
```
```
In fs/fuse/inode.c (ffffffff8149e666)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_fill_super_common
  - fs/fuse/inode.c:fuse_fill_super_submount
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_conn_init
```
```
In fs/fuse/dax.c (ffffffff814a3bba)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_iomap_begin
```
```
In ipc/util.c (ffffffff814a9d8e)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_open
  - ipc/util.c:sysvipc_proc_open
```
```
In ipc/msg.c (ffffffff814acdc5)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:expunge_all
```
```
In ipc/sem.c (ffffffff814b1cee)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:copy_semundo
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:update_queue
  - ipc/sem.c:wake_const_ops
  - ipc/sem.c:perform_atomic_semop
  - ipc/sem.c:perform_atomic_semop_slow
```
```
In ipc/shm.c (ffffffff814b42f3)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
```
```
In ipc/mqueue.c (ffffffff814b84c3)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - ipc/mqueue.c:mq_init_ns
  - ipc/mqueue.c:mq_init_ns
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_init_fs_context
  - ipc/mqueue.c:mqueue_init_fs_context
  - ipc/mqueue.c:mqueue_get_inode
```
```
In ipc/namespace.c (ffffffff814b89c6)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - ipc/namespace.c:ipcns_install
  - ipc/namespace.c:ipcns_get
  - ipc/namespace.c:get_ipc_ns_exported
  - ipc/namespace.c:copy_ipcs
  - ipc/namespace.c:copy_ipcs
```
```
In security/keys/key.c (ffffffff814ba64f)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_user_lookup
```
```
In security/keys/keyring.c (ffffffff814bbeea)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_gc_select_iterator
  - security/keys/keyring.c:__key_link
  - security/keys/keyring.c:find_key_to_update
  - security/keys/keyring.c:keyring_search_rcu
```
```
In security/keys/keyctl.c (ffffffff814bd106)
Location: include/linux/refcount.h:248
Inline: True
```
```
In security/keys/process_keys.c (ffffffff814c0c16)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:install_session_keyring_to_cred
```
```
In security/keys/request_key.c (ffffffff814c17f3)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:cache_requested_key
  - security/keys/request_key.c:check_cached_key
```
```
In security/keys/request_key_auth.c (ffffffff814c213f)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
```
```
In security/apparmor/apparmorfs.c (ffffffff81511332)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
  - security/apparmor/apparmorfs.c:seq_profile_hash_open
  - security/apparmor/apparmorfs.c:seq_profile_attach_open
  - security/apparmor/apparmorfs.c:seq_profile_mode_open
  - security/apparmor/apparmorfs.c:seq_profile_name_open
  - security/apparmor/apparmorfs.c:multi_transaction_read
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
```
```
In security/apparmor/capability.c (ffffffff8151482b)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/apparmor/capability.c:audit_caps
```
```
In security/apparmor/task.c (ffffffff815151c1)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_set_current_onexec
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_get_task_label
```
```
In security/apparmor/domain.c (ffffffff8151cb0d)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:change_hat
  - security/apparmor/domain.c:change_hat
  - security/apparmor/domain.c:change_hat
  - security/apparmor/domain.c:change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:find_attach
  - security/apparmor/domain.c:find_attach
```
```
In security/apparmor/policy.c (ffffffff8151fe57)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_alloc_profile
  - security/apparmor/policy.c:__add_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff81520e01)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:do_loaddata_free
```
```
In security/apparmor/procattr.c (ffffffff81522c09)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff831fe652)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_sock_graft
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_task_alloc
  - security/apparmor/lsm.c:apparmor_task_alloc
  - security/apparmor/lsm.c:apparmor_task_alloc
  - security/apparmor/lsm.c:apparmor_cred_transfer
  - security/apparmor/lsm.c:apparmor_cred_prepare
```
```
In security/apparmor/resource.c (ffffffff81528ad6)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff8152a5dc)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:aa_file_perm
```
```
In security/apparmor/policy_ns.c (ffffffff8152b17f)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:__aa_find_or_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:aa_lookupn_ns
  - security/apparmor/policy_ns.c:aa_findn_ns
  - security/apparmor/policy_ns.c:alloc_ns
  - security/apparmor/policy_ns.c:alloc_ns
```
```
In security/apparmor/label.c (ffffffff8152cba4)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:__label_insert
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/label.c:__proxy_share
  - security/apparmor/label.c:__aa_proxy_redirect
  - security/apparmor/label.c:aa_alloc_proxy
```
```
In security/apparmor/mount.c (ffffffff81531979)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:build_pivotroot
```
```
In security/apparmor/net.c (0)
Location: include/linux/refcount.h:248
Inline: True
```
```
In security/apparmor/af_unix.c (ffffffff815344f4)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
```
```
In security/yama/yama_lsm.c (ffffffff815354f3)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_task_prctl
  - security/yama/yama_lsm.c:report_access
  - security/yama/yama_lsm.c:report_access
```
```
In security/landlock/syscalls.c (ffffffff815372cf)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/landlock/syscalls.c:get_ruleset_from_fd
```
```
In security/landlock/ruleset.c (ffffffff81537e3f)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/landlock/ruleset.c:inherit_ruleset
  - security/landlock/ruleset.c:create_rule
```
```
In security/landlock/cred.c (ffffffff8153843c)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/landlock/cred.c:hook_cred_prepare
```
```
In crypto/api.c (ffffffff81543c47)
Location: include/linux/refcount.h:248
Inline: True
```
```
In crypto/algapi.c (ffffffff8154575a)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_stats_get
  - crypto/algapi.c:crypto_spawn_alg
```
```
In crypto/algboss.c (ffffffff8154e47a)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - crypto/algboss.c:cryptomgr_schedule_probe
```
```
In crypto/asymmetric_keys/restrict.c (ffffffff8155df6d)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
```
```
In block/bsg.c (ffffffff8158a539)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - block/bsg.c:bsg_open
```
```
In block/blk-cgroup.c (ffffffff8158ba39)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_online
```
```
In lib/cpu_rmap.c (ffffffff815dfb85)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
```
```
In lib/klist.c (ffffffff815f27ab)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - lib/klist.c:klist_next
  - lib/klist.c:klist_prev
```
```
In lib/kobject.c (ffffffff815f2ac9)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - lib/kobject.c:kobject_get
```
```
In lib/kobject_uevent.c (ffffffff815f417e)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - lib/kobject_uevent.c:kobject_uevent_net_broadcast
```
```
In drivers/pinctrl/core.c (ffffffff8160bff6)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_get
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff81657be2)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context
```
```
In drivers/acpi/ec.c (ffffffff81690ff4)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_query
```
```
In drivers/acpi/thermal.c (ffffffff816e610f)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/acpi/thermal.c:acpi_thermal_check_fn
```
```
In drivers/clk/clk.c (ffffffff81700a50)
Location: include/linux/refcount.h:248
Inline: True
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff81720d16)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
```
```
In drivers/reset/core.c (ffffffff817326f3)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/reset/core.c:__reset_control_get_internal
```
```
In drivers/tty/tty_io.c (ffffffff8173607d)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_fasync
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:tty_find_polling_driver
```
```
In drivers/tty/tty_port.c (ffffffff8173f786)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_tty_get
```
```
In drivers/tty/tty_mutex.c (ffffffff817400f4)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/tty_mutex.c:tty_lock
```
```
In drivers/tty/tty_ldsem.c (ffffffff81c37f19)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:down_read_failed
```
```
In drivers/tty/tty_jobctrl.c (ffffffff817415fe)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_get_pgrp
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:get_current_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
```
```
In drivers/tty/pty.c (ffffffff81742145)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/tty/pty.c:pty_common_install
  - drivers/tty/pty.c:pty_common_install
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff81744bfe)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_k_ioctl
```
```
In drivers/char/virtio_console.c (ffffffff81774ed4)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:port_fops_open
```
```
In drivers/char/hw_random/core.c (ffffffff81777190)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:hwrng_register
  - drivers/char/hw_random/core.c:hwrng_fillfn
```
```
In drivers/iommu/ioasid.c (ffffffff817a2ac3)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/iommu/ioasid.c:ioasid_get
```
```
In drivers/connector/connector.c (ffffffff817a5236)
Location: include/linux/refcount.h:248
Inline: True
```
```
In drivers/lightnvm/core.c (ffffffff817a7dec)
Location: include/linux/refcount.h:248
Inline: True
```
```
In drivers/base/core.c (ffffffff817ad526)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/power/runtime.c (ffffffff817c2d97)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_get_suppliers
  - drivers/base/power/runtime.c:rpm_get_suppliers
```
```
In drivers/base/firmware_loader/main.c (ffffffff817ceec6)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:assign_fw
```
```
In drivers/nvdimm/core.c (ffffffff8180104e)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81804c2a)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:get_ndd
```
```
In drivers/dax/bus.c (ffffffff81817cbe)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:alloc_dax_region
```
```
In drivers/dma-buf/dma-fence.c (ffffffff8181a8bd)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff8181b49e)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff8181bd02)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
```
```
In drivers/dma-buf/dma-resv.c (ffffffff8181c822)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
```
```
In drivers/dma-buf/sync_file.c (ffffffff8181ec0d)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_get_fence
  - drivers/dma-buf/sync_file.c:sync_file_create
```
```
In drivers/dma-buf/sw_sync.c (ffffffff8181fe2e)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_pt_create
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff81831490)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
```
```
In drivers/scsi/sr.c (ffffffff8183dc97)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_block_check_events
  - drivers/scsi/sr.c:sr_block_open
```
```
In drivers/scsi/sg.c (ffffffff81842782)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_sfp
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/ata/libata-core.c (ffffffff8184ba4a)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_get
```
```
In drivers/net/phy/phy_device.c (ffffffff81875463)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_package_join
```
```
In drivers/net/phy/sfp-bus.c (ffffffff818790d6)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_get
```
```
In drivers/net/tun.c (ffffffff81880005)
Location: include/linux/refcount.h:248
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81882f9b)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_init
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
```
In drivers/net/xen-netfront.c (ffffffff81889ffb)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_make_one_txreq
```
```
In drivers/vfio/vfio.c (ffffffff8188ea64)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_get_external_user
  - drivers/vfio/vfio.c:vfio_group_fops_open
  - drivers/vfio/vfio.c:vfio_group_set_container
  - drivers/vfio/vfio.c:vfio_iommu_group_notifier
  - drivers/vfio/vfio.c:vfio_group_get_from_iommu
  - drivers/vfio/vfio.c:vfio_create_group
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81893da5)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff818956da)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_reflck_find
```
```
In drivers/usb/core/hub.c (ffffffff818a6222)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/hcd.c (ffffffff818ac335)
Location: include/linux/refcount.h:248
Inline: True
```
```
In drivers/usb/core/urb.c (ffffffff818af365)
Location: include/linux/refcount.h:248
Inline: True
```
```
In drivers/usb/core/message.c (ffffffff818b2a53)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_set_configuration
```
```
In drivers/usb/core/file.c (ffffffff818b6a9d)
Location: include/linux/refcount.h:248
Inline: True
```
```
In drivers/usb/core/devio.c (ffffffff818bae45)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:async_completed
```
```
In drivers/md/dm.c (ffffffff81962f25)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_get_table_device
```
```
In drivers/md/dm-table.c (ffffffff81965066)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_get_device
```
```
In drivers/opp/core.c (ffffffff81977a7f)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_adjust_voltage
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_xlate_required_opp
  - drivers/opp/core.c:_set_opp
  - drivers/opp/core.c:_set_opp
  - drivers/opp/core.c:dev_pm_opp_find_freq_ceil_by_volt
  - drivers/opp/core.c:dev_pm_opp_find_freq_floor
  - drivers/opp/core.c:_find_freq_ceil
  - drivers/opp/core.c:dev_pm_opp_find_level_ceil
  - drivers/opp/core.c:dev_pm_opp_find_level_exact
  - drivers/opp/core.c:dev_pm_opp_find_freq_exact
  - drivers/opp/core.c:_find_opp_table_unlocked
```
```
In drivers/remoteproc/remoteproc_virtio.c (ffffffff819b1e80)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_add_virtio_dev
```
```
In drivers/nvmem/core.c (ffffffff819bf45a)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/nvmem/core.c:__nvmem_device_get
```
```
In net/core/sock.c (ffffffff819cb3a8)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/core/sock.c:skb_set_owner_w
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
```
In net/core/skbuff.c (ffffffff819da565)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:msg_zerocopy_realloc
  - net/core/skbuff.c:msg_zerocopy_alloc
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/core/datagram.c (ffffffff819db771)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_from_queue
```
```
In net/core/scm.c (ffffffff819dcdf4)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
  - net/core/scm.c:__scm_send
```
```
In net/core/net_namespace.c (ffffffff819df027)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_get
  - net/core/net_namespace.c:get_net_ns_by_pid
  - net/core/net_namespace.c:get_net_ns_by_fd
  - net/core/net_namespace.c:get_net_ns
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:copy_net_ns
```
```
In net/core/dev.c (ffffffff819ea106)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/neighbour.c (ffffffff819fca27)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_alloc
```
```
In net/core/rtnetlink.c (ffffffff81a08f9e)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_send
```
```
In net/core/flow_offload.c (ffffffff81a2038a)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_dev_register
```
```
In net/core/net-sysfs.c (ffffffff81a212ee)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/core/net-sysfs.c:net_grab_current_ns
```
```
In net/core/page_pool.c (ffffffff81a24abe)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_use_xdp_mem
```
```
In net/core/netpoll.c (ffffffff81a25bce)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_setup
```
```
In net/core/devlink.c (ffffffff81a3d057)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_health_reporter_get_from_attrs
  - net/core/devlink.c:devlink_health_reporter_get_from_attrs
```
```
In net/core/skmsg.c (ffffffff81a4e8a8)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_psock_init
```
```
In net/core/sock_map.c (ffffffff81a503c2)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_free
```
```
In net/sched/sch_generic.c (ffffffff81a56bba)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/sched/sch_generic.c:attach_default_qdiscs
  - net/sched/sch_generic.c:attach_default_qdiscs
```
```
In net/sched/sch_api.c (ffffffff81a5c3a5)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
```
```
In net/sched/cls_api.c (ffffffff81a5dd00)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_chain_tp_find
  - net/sched/cls_api.c:tcf_chain_tp_insert_unique
  - net/sched/cls_api.c:__tcf_block_find
  - net/sched/cls_api.c:__tcf_get_next_proto
```
```
In net/sched/act_api.c (ffffffff81a6410a)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_idr_check_alloc
  - net/sched/act_api.c:tcf_idr_search
```
```
In net/netlink/af_netlink.c (ffffffff81a6d226)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_getsockbyfilp
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/netfilter/nf_queue.c (ffffffff81a84a33)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
```
```
In net/ipv4/route.c (ffffffff81a88606)
Location: include/linux/refcount.h:248
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff81a8e339)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/ip_output.c (ffffffff81a9287e)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/ip_sockglue.c (ffffffff81a96753)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_ra_control
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81a9bb7e)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/tcp.c (ffffffff81aa35f5)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff81aa7920)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (ffffffff81ab5410)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tso_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_tsq_handler
```
```
In net/ipv4/tcp_timer.c (ffffffff81ab8ffc)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abfca4)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
```
```
In net/ipv4/raw.c (ffffffff81ac7230)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_hash_sk
```
```
In net/ipv4/udp.c (ffffffff81ace34c)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/arp.c (ffffffff81ad30f5)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_constructor
```
```
In net/ipv4/devinet.c (ffffffff81ad9f38)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:rtm_to_ifaddr
```
```
In net/ipv4/igmp.c (ffffffff81adfce0)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv4/igmp.c:____ip_mc_inc_group
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_ifc_event
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
```
```
In net/ipv4/fib_trie.c (ffffffff81aec267)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv4/inet_fragment.c (ffffffff81aedf68)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:fqdir_init
```
```
In net/ipv4/ping.c (ffffffff81af038e)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_get_port
```
```
In net/ipv4/nexthop.c (ffffffff81af7f7c)
Location: include/linux/refcount.h:248
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81b06be3)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_check
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0cf3d)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:__xfrm_policy_link
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
```
```
In net/xfrm/xfrm_state.c (ffffffff81b17601)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:xfrm_state_lookup_byspi
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1ca64)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
```
```
In net/unix/af_unix.c (ffffffff81b2165b)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:maybe_init_creds
  - net/unix/af_unix.c:unix_getname
  - net/unix/af_unix.c:unix_getname
  - net/unix/af_unix.c:unix_socketpair
  - net/unix/af_unix.c:unix_socketpair
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:init_peercred
  - net/unix/af_unix.c:__unix_insert_socket
```
```
In net/ipv6/anycast.c (ffffffff81b27e43)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/ip6_output.c (ffffffff81b29c2e)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/addrconf.c (ffffffff81b3b284)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_set_iftoken
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_begin
  - net/ipv6/addrconf.c:addrconf_dad_kick
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_add_linklocal
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/route.c (ffffffff81b40bd4)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:ip6_route_check_nh
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_rt_copy_init
  - net/ipv6/route.c:ip6_rt_copy_init
  - net/ipv6/route.c:ip6_dst_ifdown
```
```
In net/ipv6/ip6_fib.c (ffffffff81b4bdbd)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_purge_rt
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81b4dead)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ip6_ra_control
```
```
In net/ipv6/ndisc.c (ffffffff81b50e2e)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change
  - net/ipv6/ndisc.c:ndisc_netdev_event
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_unsol_na
  - net/ipv6/ndisc.c:ndisc_constructor
  - net/ipv6/ndisc.c:ndisc_constructor
```
```
In net/ipv6/mcast.c (ffffffff81b5f4a3)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_ifc_work
  - net/ipv6/mcast.c:mld_dad_work
  - net/ipv6/mcast.c:ipv6_mc_dad_complete
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:igmp6_group_dropped
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b67e3e)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_route_req
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81b75dfd)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
```
```
In net/ipv6/syncookies.c (ffffffff81b79ace)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/calipso.c (ffffffff81b7a44e)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_cache_check
```
```
In net/packet/af_packet.c (ffffffff81b87bcf)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/ncsi/ncsi-cmd.c (ffffffff81b9d863)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81ba3a5b)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
```
```
In net/xdp/xsk.c (ffffffff81ba668e)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
```
```
In net/xdp/xdp_umem.c (ffffffff81ba7473)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
  - net/xdp/xdp_umem.c:xdp_get_umem
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81ba8d5a)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_get_pool
```
```
In net/mptcp/protocol.c (ffffffff81badadf)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_finish_join
  - net/mptcp/protocol.c:__mptcp_check_push
  - net/mptcp/protocol.c:mptcp_accept
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:__mptcp_subflow_push_pending
```
```
In net/mptcp/subflow.c (ffffffff81bb3cda)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
  - net/mptcp/subflow.c:__mptcp_subflow_connect
  - net/mptcp/subflow.c:get_mapping_status
  - net/mptcp/subflow.c:mptcp_subflow_reset
```
```
In net/mptcp/options.c (ffffffff81bb5b8c)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_incoming_options
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
In init/main.c (ffffffff83299e1b)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In arch/x86/kernel/ioport.c (ffffffff8103f690)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:io_bitmap_share
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8105f888)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81068d6b)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_init_fs_context
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8107045c)
Location: include/linux/refcount.h:248
Inline: True
```
```
In kernel/fork.c (ffffffff810b54a8)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/fork.c:kernel_clone
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_sighand
  - kernel/fork.c:mm_init
```
```
In kernel/exit.c (ffffffff810bb474)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_stopped
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:release_task
```
```
In kernel/user.c (ffffffff810c58db)
Location: include/linux/refcount.h:248
Inline: True
```
```
In kernel/sys.c (ffffffff810d388a)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_prlimit64
```
```
In kernel/pid.c (ffffffff810dcca2)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/pid.c:pidfd_getfd
  - kernel/pid.c:pidfd_create
  - kernel/pid.c:pidfd_get_pid
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:get_task_pid
  - kernel/pid.c:find_get_task_by_vpid
  - kernel/pid.c:alloc_pid
```
```
In kernel/kthread.c (ffffffff810dfe2d)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_stop
```
```
In kernel/nsproxy.c (ffffffff810e587c)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/nsproxy.c:validate_nsset
  - kernel/nsproxy.c:validate_nsset
  - kernel/nsproxy.c:create_new_namespaces
```
```
In kernel/cred.c (ffffffff810e77d0)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
```
```
In kernel/smpboot.c (ffffffff810e9301)
Location: include/linux/refcount.h:248
Inline: True
```
```
In kernel/ucount.c (ffffffff810ea0fd)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/ucount.c:alloc_ucounts
```
```
In kernel/usermode_driver.c (ffffffff810eaadd)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/usermode_driver.c:umd_setup
```
```
In kernel/sched/core.c (ffffffff810f2817)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/sched/core.c:balance_push
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__do_sys_sched_setattr
  - kernel/sched/core.c:do_sched_setscheduler
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:wake_q_add
```
```
In kernel/sched/fair.c (ffffffff81101874)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_assign
```
```
In kernel/sched/rt.c (ffffffff81112f1b)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
```
```
In kernel/sched/deadline.c (ffffffff81116122)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/sched/deadline.c:pull_dl_task
  - kernel/sched/deadline.c:start_dl_timer
  - kernel/sched/deadline.c:task_non_contending
```
```
In kernel/sched/autogroup.c (ffffffff81123672)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:sched_autogroup_fork
  - kernel/sched/autogroup.c:sched_autogroup_fork
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_move_group
```
```
In kernel/sched/core_sched.c (ffffffff8112c799)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/sched/core_sched.c:sched_core_share_pid
  - kernel/sched/core_sched.c:sched_core_share_pid
  - kernel/sched/core_sched.c:sched_core_fork
```
```
In kernel/locking/rwsem.c (ffffffff8112cf0b)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
```
```
In kernel/locking/percpu-rwsem.c (ffffffff8112dc45)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wake_function
```
```
In kernel/locking/rtmutex_api.c (ffffffff81d55ff4)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_pi
  - kernel/locking/rtmutex_api.c:remove_waiter
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
```
```
In kernel/irq/manage.c (ffffffff8113f213)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/irq/manage.c:setup_irq_thread
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/rcu/update.c (ffffffff8114da07)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_trace_postgp
```
```
In kernel/kcmp.c (ffffffff811603ab)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
```
```
In kernel/time/posix-timers.c (ffffffff8117341b)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81174194)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_create
```
```
In kernel/time/namespace.c (ffffffff8117c553)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/time/namespace.c:timens_on_fork
  - kernel/time/namespace.c:timens_install
  - kernel/time/namespace.c:timens_install
  - kernel/time/namespace.c:timens_for_children_get
  - kernel/time/namespace.c:timens_get
  - kernel/time/namespace.c:copy_time_ns
  - kernel/time/namespace.c:copy_time_ns
```
```
In kernel/futex.c (ffffffff8117d1e5)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/futex.c:mark_wake_futex
```
```
In kernel/cgroup/cgroup.c (ffffffff8119c62d)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:css_task_iter_next
  - kernel/cgroup/cgroup.c:css_task_iter_advance_css_set
  - kernel/cgroup/cgroup.c:css_task_iter_advance_css_set
  - kernel/cgroup/cgroup.c:cgroup_file_open
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/cgroup/namespace.c (ffffffff8119e3ab)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:cgroupns_get
  - kernel/cgroup/namespace.c:cgroupns_install
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8119ecb7)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
```
In kernel/utsname.c (ffffffff811a9524)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_install
  - kernel/utsname.c:utsns_get
  - kernel/utsname.c:copy_utsname
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (ffffffff811aa477)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/user_namespace.c:ns_get_owner
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_get
```
```
In kernel/pid_namespace.c (ffffffff811ab739)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_get_parent
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:pidns_get
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/pid_namespace.c:create_pid_namespace
  - kernel/pid_namespace.c:create_pid_namespace
```
```
In kernel/audit.c (ffffffff811aed05)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/audit.c:audit_get_tty
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_send_queue
```
```
In kernel/auditfilter.c (ffffffff811b29e4)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In kernel/audit_watch.c (ffffffff811b8e93)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_tree.c (ffffffff811bb452)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_trim_trees
  - kernel/audit_tree.c:tag_chunk
  - kernel/audit_tree.c:create_chunk
  - kernel/audit_tree.c:replace_chunk
```
```
In kernel/hung_task.c (ffffffff811cb81c)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
```
```
In kernel/seccomp.c (ffffffff811cec7d)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_attach_filter
  - kernel/seccomp.c:seccomp_attach_filter
```
```
In kernel/relay.c (ffffffff811d0904)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_open
  - kernel/relay.c:relay_create_buf
```
```
In kernel/trace/trace.c (ffffffff811e4255)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/trace/trace.c:buffer_pipe_buf_get
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811f5495)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/bpf/syscall.c (ffffffff81231ce8)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In kernel/bpf/task_iter.c (ffffffff812526bf)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:init_seq_pidns
```
```
In kernel/bpf/trampoline.c (ffffffff8125f0ed)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_get
```
```
In kernel/bpf/btf.c (ffffffff812666e7)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/bpf/btf.c:bpf_btf_find_by_name_kind
  - kernel/bpf/btf.c:btf_get_by_fd
```
```
In kernel/bpf/dispatcher.c (ffffffff8126adaa)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog
```
```
In kernel/bpf/offload.c (ffffffff8126efec)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_map_offload_info_fill_ns
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill_ns
```
```
In kernel/events/core.c (ffffffff81287d33)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_context
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_remove_from_owner
  - kernel/events/core.c:find_get_context
  - kernel/events/core.c:find_get_context
  - kernel/events/core.c:alloc_perf_context
```
```
In kernel/events/uprobes.c (ffffffff81293182)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/events/uprobes.c:prepare_uretprobe
  - kernel/events/uprobes.c:uprobe_copy_process
  - kernel/events/uprobes.c:uprobe_mmap
  - kernel/events/uprobes.c:uprobe_mmap
  - kernel/events/uprobes.c:alloc_uprobe
  - kernel/events/uprobes.c:find_uprobe
```
```
In kernel/padata.c (ffffffff812949ba)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_parallel
```
```
In kernel/watch_queue.c (ffffffff81296d56)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/watch_queue.c:get_watch_queue
  - kernel/watch_queue.c:add_watch_to_object
  - kernel/watch_queue.c:add_watch_to_object
```
```
In mm/oom_kill.c (ffffffff812a3780)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - mm/oom_kill.c:out_of_memory
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/backing-dev.c (ffffffff812c63c6)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_get_by_id
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:wb_init
```
```
In mm/page_io.c (ffffffff8130fc7e)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In mm/hugetlb.c (ffffffff8131c949)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_vm_op_open
```
```
In mm/mempolicy.c (ffffffff81328573)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_migrate_pages
```
```
In mm/migrate.c (ffffffff8133d86c)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - mm/migrate.c:find_mm_struct
```
```
In mm/huge_memory.c (ffffffff8134a236)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_pid
```
```
In mm/memory-failure.c (ffffffff8135fd8a)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - mm/memory-failure.c:add_to_kill
```
```
In fs/super.c (ffffffff81375838)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/super.c:set_bdev_super_fc
  - fs/super.c:alloc_super
```
```
In fs/exec.c (ffffffff8137a6c5)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/exec.c:would_dump
```
```
In fs/pipe.c (ffffffff8137e767)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/pipe.c:alloc_pipe_info
```
```
In fs/fcntl.c (ffffffff81388f81)
Location: include/linux/refcount.h:248
Inline: True
```
```
In fs/namespace.c (ffffffff813a1ee7)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_get
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:alloc_mnt_ns
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:mnt_init
```
```
In fs/fs_context.c (ffffffff813b980e)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/fs_context.c:alloc_fs_context
  - fs/fs_context.c:alloc_fs_context
  - fs/fs_context.c:alloc_fs_context
  - fs/fs_context.c:alloc_fs_context
```
```
In fs/proc_namespace.c (ffffffff813c6314)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/notify/group.c (ffffffff813c76ca)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_get_group
```
```
In fs/notify/mark.c (ffffffff813c8444)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_get_mark
```
```
In fs/notify/fanotify/fanotify.c (ffffffff813cb8b3)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/eventpoll.c (ffffffff813cedc5)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_create
```
```
In fs/eventfd.c (ffffffff813d3575)
Location: include/linux/refcount.h:248
Inline: True
```
```
In fs/userfaultfd.c (ffffffff813d6345)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_unmap_prep
  - fs/userfaultfd.c:userfaultfd_remove
  - fs/userfaultfd.c:mremap_userfaultfd_prep
  - fs/userfaultfd.c:dup_userfaultfd
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/io_uring.c (ffffffff813e2ca4)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/io_uring.c:io_register_iowq_max_workers
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:__io_sqe_files_scm
  - fs/io_uring.c:io_get_sq_data
```
```
In fs/io-wq.c (ffffffff813f2be5)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/io-wq.c:io_wq_create
  - fs/io-wq.c:io_wq_create
```
```
In fs/crypto/keysetup.c (ffffffff813fbbb8)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_setup_encryption_info
  - fs/crypto/keysetup.c:fscrypt_setup_encryption_info
```
```
In fs/crypto/keysetup_v1.c (ffffffff813fc2a5)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
```
```
In fs/posix_acl.c (ffffffff8140dbc1)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/posix_acl.c:set_cached_acl
```
```
In fs/proc/root.c (ffffffff81424853)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/proc/root.c:proc_init_fs_context
  - fs/proc/root.c:proc_init_fs_context
  - fs/proc/root.c:proc_fill_super
  - fs/proc/root.c:proc_fill_super
```
```
In fs/proc/base.c (ffffffff81429cac)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:next_tgid
  - fs/proc/base.c:proc_pid_lookup
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_open
```
```
In fs/proc/generic.c (ffffffff8142ac03)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_lookup_de
```
```
In fs/proc/array.c (ffffffff8142c3cf)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
```
```
In fs/proc/proc_net.c (ffffffff814340be)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_task_net
  - fs/proc/proc_net.c:bpf_iter_init_seq_net
```
```
In fs/sysfs/mount.c (ffffffff8143cccb)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/sysfs/mount.c:sysfs_init_fs_context
```
```
In fs/configfs/item.c (ffffffff81442039)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/configfs/item.c:config_group_find_item
```
```
In fs/ecryptfs/keystore.c (ffffffff814dea9e)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
```
```
In fs/fuse/dev.c (ffffffff814e6a40)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:fuse_simple_request
```
```
In fs/fuse/file.c (ffffffff814f1d33)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_writepages_send
  - fs/fuse/file.c:fuse_write_inode
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_readahead
  - fs/fuse/file.c:fuse_async_req_send
```
```
In fs/fuse/inode.c (ffffffff814f6996)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_fill_super_common
  - fs/fuse/inode.c:fuse_get_tree_submount
  - fs/fuse/inode.c:fuse_fill_super_submount
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_conn_init
```
```
In fs/fuse/dax.c (ffffffff814fbc36)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_iomap_begin
```
```
In ipc/util.c (ffffffff8150223e)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_open
  - ipc/util.c:sysvipc_proc_open
```
```
In ipc/msg.c (ffffffff815052b0)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:expunge_all
```
```
In ipc/sem.c (ffffffff8150a2ac)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:copy_semundo
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:update_queue
  - ipc/sem.c:wake_const_ops
  - ipc/sem.c:perform_atomic_semop
  - ipc/sem.c:perform_atomic_semop_slow
```
```
In ipc/shm.c (ffffffff8150c98d)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
```
```
In ipc/mqueue.c (ffffffff81510cf3)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - ipc/mqueue.c:mq_init_ns
  - ipc/mqueue.c:mq_init_ns
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_init_fs_context
  - ipc/mqueue.c:mqueue_init_fs_context
```
```
In ipc/namespace.c (ffffffff815111f6)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - ipc/namespace.c:ipcns_install
  - ipc/namespace.c:ipcns_get
  - ipc/namespace.c:get_ipc_ns_exported
  - ipc/namespace.c:copy_ipcs
  - ipc/namespace.c:copy_ipcs
```
```
In security/keys/key.c (ffffffff81512e7f)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_user_lookup
```
```
In security/keys/keyring.c (ffffffff8151475f)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_gc_select_iterator
  - security/keys/keyring.c:__key_link
  - security/keys/keyring.c:find_key_to_update
  - security/keys/keyring.c:keyring_search_rcu
```
```
In security/keys/keyctl.c (ffffffff81515b86)
Location: include/linux/refcount.h:248
Inline: True
```
```
In security/keys/process_keys.c (ffffffff8151964c)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:install_session_keyring_to_cred
```
```
In security/keys/request_key.c (ffffffff8151a263)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:cache_requested_key
  - security/keys/request_key.c:check_cached_key
```
```
In security/keys/request_key_auth.c (ffffffff8151ab2f)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
```
```
In security/apparmor/apparmorfs.c (ffffffff8156ef32)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
  - security/apparmor/apparmorfs.c:seq_profile_hash_open
  - security/apparmor/apparmorfs.c:seq_profile_attach_open
  - security/apparmor/apparmorfs.c:seq_profile_mode_open
  - security/apparmor/apparmorfs.c:seq_profile_name_open
  - security/apparmor/apparmorfs.c:multi_transaction_read
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
```
```
In security/apparmor/capability.c (ffffffff81572701)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/apparmor/capability.c:audit_caps
```
```
In security/apparmor/task.c (ffffffff81573171)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_set_current_onexec
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_get_task_label
```
```
In security/apparmor/domain.c (ffffffff8157abde)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:change_hat
  - security/apparmor/domain.c:change_hat
  - security/apparmor/domain.c:change_hat
  - security/apparmor/domain.c:change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:find_attach
  - security/apparmor/domain.c:find_attach
```
```
In security/apparmor/policy.c (ffffffff8157dff7)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_alloc_profile
  - security/apparmor/policy.c:__add_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff8157efa1)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:do_loaddata_free
```
```
In security/apparmor/procattr.c (ffffffff81580e79)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff832e5964)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_sock_graft
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_task_alloc
  - security/apparmor/lsm.c:apparmor_task_alloc
  - security/apparmor/lsm.c:apparmor_task_alloc
  - security/apparmor/lsm.c:apparmor_cred_transfer
  - security/apparmor/lsm.c:apparmor_cred_prepare
```
```
In security/apparmor/resource.c (ffffffff81586dc6)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff8158897c)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:aa_file_perm
```
```
In security/apparmor/policy_ns.c (ffffffff8158951f)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:__aa_find_or_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:aa_lookupn_ns
  - security/apparmor/policy_ns.c:aa_findn_ns
  - security/apparmor/policy_ns.c:alloc_ns
  - security/apparmor/policy_ns.c:alloc_ns
```
```
In security/apparmor/label.c (ffffffff8158af94)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:__label_insert
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/label.c:__proxy_share
  - security/apparmor/label.c:__aa_proxy_redirect
  - security/apparmor/label.c:aa_alloc_proxy
```
```
In security/apparmor/mount.c (ffffffff8158fdcc)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:build_pivotroot
```
```
In security/apparmor/net.c (0)
Location: include/linux/refcount.h:248
Inline: True
```
```
In security/apparmor/af_unix.c (ffffffff81592a74)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
```
```
In security/yama/yama_lsm.c (ffffffff81593ac3)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_task_prctl
  - security/yama/yama_lsm.c:report_access
  - security/yama/yama_lsm.c:report_access
```
```
In security/landlock/syscalls.c (ffffffff81595a4f)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/landlock/syscalls.c:get_ruleset_from_fd
```
```
In security/landlock/ruleset.c (ffffffff81596a33)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/landlock/ruleset.c:landlock_merge_ruleset
  - security/landlock/ruleset.c:create_rule
```
```
In security/landlock/cred.c (ffffffff81596c2c)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/landlock/cred.c:hook_cred_prepare
```
```
In crypto/api.c (ffffffff815a43e7)
Location: include/linux/refcount.h:248
Inline: True
```
```
In crypto/algapi.c (ffffffff815a5f2a)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_stats_get
  - crypto/algapi.c:crypto_spawn_alg
```
```
In crypto/algboss.c (ffffffff815aece8)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - crypto/algboss.c:cryptomgr_schedule_probe
```
```
In crypto/asymmetric_keys/restrict.c (ffffffff815bf27d)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
```
```
In block/blk-cgroup.c (ffffffff815f0dc9)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_online
```
```
In lib/cpu_rmap.c (ffffffff8164b695)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
```
```
In lib/klist.c (ffffffff8165f68b)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - lib/klist.c:klist_next
  - lib/klist.c:klist_prev
```
```
In lib/kobject.c (ffffffff8165fca9)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - lib/kobject.c:kobject_get
```
```
In lib/kobject_uevent.c (ffffffff816614ee)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - lib/kobject_uevent.c:kobject_uevent_net_broadcast
```
```
In drivers/pinctrl/core.c (ffffffff8167ad03)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_get
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff816c9c11)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff816de51e)
Location: include/linux/refcount.h:248
Inline: True
```
```
In drivers/acpi/ec.c (ffffffff81706a6c)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_query
```
```
In drivers/acpi/thermal.c (ffffffff8175f43f)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/acpi/thermal.c:acpi_thermal_check_fn
```
```
In drivers/clk/clk.c (ffffffff8177b260)
Location: include/linux/refcount.h:248
Inline: True
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff8179fb36)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
```
```
In drivers/reset/core.c (ffffffff817b3089)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/reset/core.c:__reset_control_get_internal
```
```
In drivers/tty/tty_io.c (ffffffff817b6a3d)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_fasync
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:tty_find_polling_driver
```
```
In drivers/tty/tty_port.c (ffffffff817bffe6)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_tty_get
```
```
In drivers/tty/tty_mutex.c (ffffffff817c0894)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/tty_mutex.c:tty_lock
```
```
In drivers/tty/tty_ldsem.c (ffffffff81d567f3)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:down_read_failed
```
```
In drivers/tty/tty_jobctrl.c (ffffffff817c205e)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_get_pgrp
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:get_current_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
```
```
In drivers/tty/pty.c (ffffffff817c2c05)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/tty/pty.c:pty_common_install
  - drivers/tty/pty.c:pty_common_install
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff817c5a55)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_k_ioctl
```
```
In drivers/char/virtio_console.c (ffffffff817fac14)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:port_fops_open
```
```
In drivers/char/hw_random/core.c (ffffffff817fcf20)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:hwrng_register
  - drivers/char/hw_random/core.c:hwrng_fillfn
```
```
In drivers/iommu/ioasid.c (ffffffff8182be03)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/iommu/ioasid.c:ioasid_get
```
```
In drivers/connector/connector.c (ffffffff81830bb6)
Location: include/linux/refcount.h:248
Inline: True
```
```
In drivers/base/core.c (ffffffff8183688c)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/power/runtime.c (ffffffff8184d127)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_get_suppliers
  - drivers/base/power/runtime.c:rpm_get_suppliers
```
```
In drivers/base/firmware_loader/main.c (ffffffff81859647)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:assign_fw
```
```
In drivers/nvdimm/core.c (ffffffff8188b45e)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff8188f33a)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:get_ndd
```
```
In drivers/dax/bus.c (ffffffff818a230e)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/dax/bus.c:devm_create_dev_dax
```
```
In drivers/dma-buf/dma-buf.c (ffffffff818a418e)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll_excl
```
```
In drivers/dma-buf/dma-fence.c (ffffffff818a4d5d)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff818a590e)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff818a6192)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
```
```
In drivers/dma-buf/dma-resv.c (ffffffff818a6c62)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
```
```
In drivers/dma-buf/sync_file.c (ffffffff818a929d)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_get_fence
  - drivers/dma-buf/sync_file.c:sync_file_create
```
```
In drivers/dma-buf/sw_sync.c (ffffffff818aa4ee)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_pt_create
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff818bd4e0)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
```
```
In drivers/scsi/sr.c (ffffffff818ca757)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_block_check_events
  - drivers/scsi/sr.c:sr_block_open
```
```
In drivers/scsi/sg.c (ffffffff818cf892)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_sfp
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/ata/libata-core.c (ffffffff818d8f1a)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_get
```
```
In drivers/net/phy/phy_device.c (ffffffff81905f33)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_package_join
```
```
In drivers/net/phy/sfp-bus.c (ffffffff81909f26)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_get
```
```
In drivers/net/tun.c (ffffffff819118b4)
Location: include/linux/refcount.h:248
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8191493b)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_init
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
```
In drivers/net/xen-netfront.c (ffffffff8191cbbb)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_make_one_txreq
```
```
In drivers/vfio/vfio.c (ffffffff819220b4)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_get_external_user
  - drivers/vfio/vfio.c:vfio_group_fops_open
  - drivers/vfio/vfio.c:vfio_group_set_container
  - drivers/vfio/vfio.c:vfio_iommu_group_notifier
  - drivers/vfio/vfio.c:vfio_group_get_from_iommu
  - drivers/vfio/vfio.c:vfio_create_group
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81927975)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map
```
```
In drivers/usb/core/hub.c (ffffffff8193b082)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/hcd.c (ffffffff81941385)
Location: include/linux/refcount.h:248
Inline: True
```
```
In drivers/usb/core/urb.c (ffffffff819444b5)
Location: include/linux/refcount.h:248
Inline: True
```
```
In drivers/usb/core/message.c (ffffffff81947d56)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_set_configuration
```
```
In drivers/usb/core/file.c (ffffffff8194c41d)
Location: include/linux/refcount.h:248
Inline: True
```
```
In drivers/usb/core/devio.c (ffffffff819515d1)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:async_completed
```
```
In drivers/md/dm.c (ffffffff81a09f55)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_get_table_device
```
```
In drivers/md/dm-table.c (ffffffff81a0cfe6)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_get_device
```
```
In drivers/opp/core.c (ffffffff81a2097f)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_adjust_voltage
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_xlate_required_opp
  - drivers/opp/core.c:_set_opp
  - drivers/opp/core.c:_set_opp
  - drivers/opp/core.c:dev_pm_opp_find_freq_ceil_by_volt
  - drivers/opp/core.c:dev_pm_opp_find_freq_floor
  - drivers/opp/core.c:_find_freq_ceil
  - drivers/opp/core.c:dev_pm_opp_find_level_ceil
  - drivers/opp/core.c:dev_pm_opp_find_level_exact
  - drivers/opp/core.c:dev_pm_opp_find_freq_exact
  - drivers/opp/core.c:_find_opp_table_unlocked
```
```
In drivers/remoteproc/remoteproc_virtio.c (ffffffff81a605e0)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_add_virtio_dev
```
```
In drivers/nvmem/core.c (ffffffff81a6eaea)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/nvmem/core.c:__nvmem_device_get
```
```
In net/core/sock.c (ffffffff81a7aa2d)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/core/sock.c:skb_set_owner_w
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
```
In net/core/skbuff.c (ffffffff81a8a584)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:msg_zerocopy_realloc
  - net/core/skbuff.c:msg_zerocopy_alloc
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/core/datagram.c (ffffffff81a8b9c1)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_from_queue
```
```
In net/core/scm.c (ffffffff81a8d034)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
  - net/core/scm.c:__scm_send
```
```
In net/core/net_namespace.c (ffffffff81a8f407)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_get
  - net/core/net_namespace.c:get_net_ns_by_pid
  - net/core/net_namespace.c:get_net_ns_by_fd
  - net/core/net_namespace.c:get_net_ns
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:copy_net_ns
```
```
In net/core/dev.c (ffffffff81a9adf0)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/neighbour.c (ffffffff81aaea64)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_alloc
```
```
In net/core/rtnetlink.c (ffffffff81ab37a8)
Location: include/linux/refcount.h:248
Inline: True
```
```
In net/core/flow_offload.c (ffffffff81ad4533)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_dev_register
```
```
In net/core/net-sysfs.c (ffffffff81ad586e)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/core/net-sysfs.c:net_grab_current_ns
```
```
In net/core/page_pool.c (ffffffff81ad95fe)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_use_xdp_mem
```
```
In net/core/netpoll.c (ffffffff81ada92e)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_setup
```
```
In net/core/devlink.c (ffffffff81af5357)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_health_reporter_get_from_attrs
  - net/core/devlink.c:devlink_health_reporter_get_from_attrs
  - net/core/devlink.c:devlink_nl_rate_parent_node_set
```
```
In net/core/skmsg.c (ffffffff81b05258)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_psock_init
```
```
In net/core/sock_map.c (ffffffff81b08fc2)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_free
```
```
In net/sched/sch_generic.c (ffffffff81b0f9f0)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/sched/sch_generic.c:attach_default_qdiscs
  - net/sched/sch_generic.c:attach_default_qdiscs
```
```
In net/sched/sch_api.c (ffffffff81b15555)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
```
```
In net/sched/cls_api.c (ffffffff81b16ec0)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_chain_tp_find
  - net/sched/cls_api.c:tcf_chain_tp_insert_unique
  - net/sched/cls_api.c:__tcf_block_find
  - net/sched/cls_api.c:__tcf_get_next_proto
```
```
In net/sched/act_api.c (ffffffff81b1d4aa)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_idr_check_alloc
  - net/sched/act_api.c:tcf_idr_search
```
```
In net/netlink/af_netlink.c (ffffffff81b26899)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_getsockbyfilp
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/ipv4/route.c (ffffffff81b42d66)
Location: include/linux/refcount.h:248
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff81b49529)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/ip_output.c (ffffffff81b4dc82)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/ip_sockglue.c (ffffffff81b51bd3)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_ra_control
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81b57251)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_complete_hashdance
```
```
In net/ipv4/tcp.c (ffffffff81b5f795)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff81b63009)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (ffffffff81b72408)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tso_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_tsq_handler
```
```
In net/ipv4/tcp_timer.c (ffffffff81b763fc)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b7b913)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
```
```
In net/ipv4/raw.c (ffffffff81b85a50)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_hash_sk
```
```
In net/ipv4/udp.c (ffffffff81b8cd15)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/arp.c (ffffffff81b91d45)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_constructor
```
```
In net/ipv4/devinet.c (ffffffff81b99078)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:rtm_to_ifaddr
```
```
In net/ipv4/igmp.c (ffffffff81b9f273)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv4/igmp.c:____ip_mc_inc_group
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_ifc_event
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
```
```
In net/ipv4/fib_semantics.c (ffffffff81ba79d6)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/fib_trie.c (ffffffff81bac4ae)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv4/inet_fragment.c (ffffffff81bae318)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:fqdir_init
```
```
In net/ipv4/ping.c (ffffffff81bb0398)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_get_port
```
```
In net/ipv4/nexthop.c (ffffffff81bb8cdc)
Location: include/linux/refcount.h:248
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81bc9a43)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_check
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bd0135)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:__xfrm_policy_link
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
```
```
In net/xfrm/xfrm_state.c (ffffffff81bdb9b1)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:xfrm_state_lookup_byspi
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
```
```
In net/xfrm/xfrm_output.c (ffffffff81be13da)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
```
```
In net/unix/af_unix.c (ffffffff81be67fb)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:__unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:maybe_init_creds
  - net/unix/af_unix.c:unix_getname
  - net/unix/af_unix.c:unix_getname
  - net/unix/af_unix.c:unix_socketpair
  - net/unix/af_unix.c:unix_socketpair
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:init_peercred
```
```
In net/ipv6/anycast.c (ffffffff81bedd83)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/ip6_output.c (ffffffff81bef802)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/addrconf.c (ffffffff81c01a91)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_set_iftoken
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_begin
  - net/ipv6/addrconf.c:addrconf_dad_kick
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_permanent_addr
  - net/ipv6/addrconf.c:addrconf_add_linklocal
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/route.c (ffffffff81c07204)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:ip6_route_check_nh
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_rt_copy_init
  - net/ipv6/route.c:ip6_rt_copy_init
  - net/ipv6/route.c:ip6_dst_ifdown
```
```
In net/ipv6/ip6_fib.c (ffffffff81c130fa)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_purge_rt
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81c151bd)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ip6_ra_control
```
```
In net/ipv6/ndisc.c (ffffffff81c181de)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change
  - net/ipv6/ndisc.c:ndisc_netdev_event
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_unsol_na
  - net/ipv6/ndisc.c:ndisc_constructor
  - net/ipv6/ndisc.c:ndisc_constructor
```
```
In net/ipv6/mcast.c (ffffffff81c26c63)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_ifc_work
  - net/ipv6/mcast.c:mld_dad_work
  - net/ipv6/mcast.c:ipv6_mc_dad_complete
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:igmp6_group_dropped
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2fac9)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_route_req
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81c40872)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
```
```
In net/ipv6/syncookies.c (ffffffff81c44778)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/calipso.c (ffffffff81c4510e)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_cache_check
```
```
In net/packet/af_packet.c (ffffffff81c540fc)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/ncsi/ncsi-cmd.c (ffffffff81c6adf6)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81c7105b)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
```
```
In net/xdp/xsk.c (ffffffff81c741de)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
```
```
In net/xdp/xdp_umem.c (ffffffff81c7508d)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
  - net/xdp/xdp_umem.c:xdp_get_umem
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81c76b1a)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_get_pool
```
```
In net/mptcp/protocol.c (ffffffff81c7a51c)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_finish_join
  - net/mptcp/protocol.c:__mptcp_check_push
  - net/mptcp/protocol.c:mptcp_accept
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:__mptcp_subflow_push_pending
```
```
In net/mptcp/subflow.c (ffffffff81c82419)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
  - net/mptcp/subflow.c:__mptcp_subflow_connect
  - net/mptcp/subflow.c:get_mapping_status
  - net/mptcp/subflow.c:mptcp_subflow_reset
```
```
In net/mptcp/options.c (ffffffff81c849fc)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_incoming_options
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
In init/main.c (ffffffff8344801e)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In arch/x86/kernel/ioport.c (ffffffff81046d90)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:io_bitmap_share
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8106c159)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81075edb)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_init_fs_context
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8107e654)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_mm_add
```
```
In kernel/fork.c (ffffffff810cb815)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/fork.c:kernel_clone
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:mm_init
  - kernel/fork.c:vm_area_dup
```
```
In kernel/exit.c (ffffffff810d1e43)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_stopped
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:make_task_dead
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:release_task
```
```
In kernel/user.c (ffffffff810dced1)
Location: include/linux/refcount.h:248
Inline: True
```
```
In kernel/sys.c (ffffffff810e9a0c)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_prlimit64
```
```
In kernel/pid.c (ffffffff810f651a)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/pid.c:pidfd_getfd
  - kernel/pid.c:__ia32_sys_pidfd_open
  - kernel/pid.c:__x64_sys_pidfd_open
  - kernel/pid.c:pidfd_create
  - kernel/pid.c:pidfd_get_task
  - kernel/pid.c:pidfd_get_pid
  - kernel/pid.c:get_task_pid
  - kernel/pid.c:find_get_task_by_vpid
  - kernel/pid.c:alloc_pid
```
```
In kernel/kthread.c (ffffffff810fa92a)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_stop
```
```
In kernel/nsproxy.c (ffffffff810ff7ea)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/nsproxy.c:validate_nsset
  - kernel/nsproxy.c:validate_nsset
  - kernel/nsproxy.c:create_new_namespaces
```
```
In kernel/cred.c (ffffffff81101a5a)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
```
```
In kernel/smpboot.c (ffffffff811040c9)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/smpboot.c:__smpboot_create_thread
```
```
In kernel/ucount.c (ffffffff81104d60)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/ucount.c:alloc_ucounts
```
```
In kernel/usermode_driver.c (ffffffff811058c5)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/usermode_driver.c:umd_setup
```
```
In kernel/sched/core.c (ffffffff8110e745)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/sched/core.c:balance_push
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__do_sys_sched_setattr
  - kernel/sched/core.c:do_sched_setscheduler
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:wake_q_add
```
```
In kernel/sched/fair.c (ffffffff8111bd94)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_assign
```
```
In kernel/sched/build_policy.c (ffffffff8112fd77)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:pull_dl_task
  - kernel/sched/build_policy.c:push_dl_task
  - kernel/sched/build_policy.c:start_dl_timer
  - kernel/sched/build_policy.c:task_non_contending
  - kernel/sched/build_policy.c:pull_rt_task
  - kernel/sched/build_policy.c:push_rt_task
  - kernel/sched/build_policy.c:push_rt_task
```
```
In kernel/sched/build_utility.c (ffffffff8114d24a)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:proc_sched_autogroup_show_task
  - kernel/sched/build_utility.c:proc_sched_autogroup_show_task
  - kernel/sched/build_utility.c:proc_sched_autogroup_set_nice
  - kernel/sched/build_utility.c:proc_sched_autogroup_set_nice
  - kernel/sched/build_utility.c:sched_autogroup_fork
  - kernel/sched/build_utility.c:sched_autogroup_fork
  - kernel/sched/build_utility.c:sched_autogroup_create_attach
  - kernel/sched/build_utility.c:autogroup_move_group
  - kernel/sched/build_utility.c:sched_core_share_pid
  - kernel/sched/build_utility.c:__sched_core_set
  - kernel/sched/build_utility.c:sched_core_fork
```
```
In kernel/locking/rwsem.c (ffffffff8114e1dc)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
```
```
In kernel/locking/percpu-rwsem.c (ffffffff8114ea19)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wake_function
```
```
In kernel/locking/rtmutex_api.c (ffffffff81f27f8f)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_pi
  - kernel/locking/rtmutex_api.c:remove_waiter
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
```
```
In kernel/irq/manage.c (ffffffff81162cab)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/irq/manage.c:setup_irq_thread
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/rcu/update.c (ffffffff81174789)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_trace_postgp
```
```
In kernel/rcu/tree.c (ffffffff81e5f4a4)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_print_task_stall
```
```
In kernel/kcmp.c (ffffffff81193104)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
```
```
In kernel/time/posix-timers.c (ffffffff811a6784)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811a8ecb)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_create
```
```
In kernel/time/namespace.c (ffffffff811b1f7f)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/time/namespace.c:proc_timens_set_offset
  - kernel/time/namespace.c:proc_timens_show_offsets
  - kernel/time/namespace.c:timens_on_fork
  - kernel/time/namespace.c:timens_install
  - kernel/time/namespace.c:timens_install
  - kernel/time/namespace.c:timens_get
  - kernel/time/namespace.c:copy_time_ns
  - kernel/time/namespace.c:copy_time_ns
```
```
In kernel/futex/waitwake.c (ffffffff811b6c61)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/futex/waitwake.c:futex_wake_mark
```
```
In kernel/cgroup/cgroup.c (ffffffff811cc90e)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:css_task_iter_next
  - kernel/cgroup/cgroup.c:css_task_iter_advance_css_set
  - kernel/cgroup/cgroup.c:css_task_iter_advance_css_set
  - kernel/cgroup/cgroup.c:cgroup_file_open
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/cgroup/namespace.c (ffffffff811ce6b7)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:cgroupns_get
  - kernel/cgroup/namespace.c:cgroupns_install
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff811cf469)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
```
In kernel/utsname.c (ffffffff811da868)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_install
  - kernel/utsname.c:utsns_get
  - kernel/utsname.c:copy_utsname
  - kernel/utsname.c:clone_uts_ns
```
```
In kernel/user_namespace.c (ffffffff811dba61)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/user_namespace.c:ns_get_owner
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_get
```
```
In kernel/pid_namespace.c (ffffffff811dcf73)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_get_parent
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:pidns_get
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/pid_namespace.c:create_pid_namespace
  - kernel/pid_namespace.c:create_pid_namespace
```
```
In kernel/audit.c (ffffffff811e0f40)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/audit.c:audit_get_tty
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_send_queue
```
```
In kernel/auditfilter.c (ffffffff811e4d44)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In kernel/audit_watch.c (ffffffff811ebec8)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_tree.c (ffffffff811ee8aa)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_trim_trees
  - kernel/audit_tree.c:tag_chunk
  - kernel/audit_tree.c:create_chunk
  - kernel/audit_tree.c:replace_chunk
```
```
In kernel/hung_task.c (ffffffff811ff5dd)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
```
```
In kernel/seccomp.c (ffffffff81202dd6)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_attach_filter
  - kernel/seccomp.c:seccomp_attach_filter
```
```
In kernel/relay.c (ffffffff81204d54)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_open
  - kernel/relay.c:relay_create_buf
```
```
In kernel/trace/trace.c (ffffffff8121b533)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/trace/trace.c:buffer_pipe_buf_get
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8122ecf2)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/trace/rethook.c (ffffffff81269129)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/trace/rethook.c:rethook_add_node
```
```
In kernel/bpf/syscall.c (ffffffff81274fa7)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In kernel/bpf/task_iter.c (ffffffff8129a68f)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:init_seq_pidns
```
```
In kernel/bpf/trampoline.c (ffffffff812a972a)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_get
```
```
In kernel/bpf/btf.c (ffffffff812b751b)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_by_fd
  - kernel/bpf/btf.c:bpf_find_btf_id
  - kernel/bpf/btf.c:bpf_find_btf_id
```
```
In kernel/bpf/dispatcher.c (ffffffff812b9ade)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog
```
```
In kernel/bpf/offload.c (ffffffff812bdf4c)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_map_offload_info_fill_ns
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill_ns
```
```
In kernel/events/core.c (ffffffff812dc552)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_context
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_remove_from_owner
  - kernel/events/core.c:find_get_context
  - kernel/events/core.c:find_get_context
  - kernel/events/core.c:alloc_perf_context
```
```
In kernel/events/uprobes.c (ffffffff812e8c11)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/events/uprobes.c:prepare_uretprobe
  - kernel/events/uprobes.c:uprobe_copy_process
  - kernel/events/uprobes.c:uprobe_mmap
  - kernel/events/uprobes.c:uprobe_mmap
  - kernel/events/uprobes.c:alloc_uprobe
  - kernel/events/uprobes.c:__find_uprobe
```
```
In kernel/padata.c (ffffffff812ea3c9)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_parallel
```
```
In kernel/watch_queue.c (ffffffff812ece6e)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/watch_queue.c:get_watch_queue
  - kernel/watch_queue.c:add_watch_to_object
  - kernel/watch_queue.c:add_watch_to_object
```
```
In mm/oom_kill.c (ffffffff812fb6ca)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - mm/oom_kill.c:out_of_memory
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:oom_evaluate_task
```
```
In mm/backing-dev.c (ffffffff813243d1)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_get_by_id
  - mm/backing-dev.c:cgwb_create
```
```
In mm/madvise.c (ffffffff81378302)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - mm/madvise.c:madvise_vma_behavior
  - mm/madvise.c:madvise_update_vma
```
```
In mm/page_io.c (ffffffff8137a6cc)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In mm/hugetlb.c (ffffffff81388b90)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_vm_op_open
```
```
In mm/mempolicy.c (ffffffff813977dc)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_migrate_pages
```
```
In mm/migrate.c (ffffffff813b0b27)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - mm/migrate.c:find_mm_struct
```
```
In mm/huge_memory.c (ffffffff813c0dde)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_pid
```
```
In mm/memory-failure.c (ffffffff813da9ec)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - mm/memory-failure.c:add_to_kill
```
```
In fs/super.c (ffffffff813f4d68)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/super.c:set_bdev_super_fc
  - fs/super.c:alloc_super
```
```
In fs/exec.c (ffffffff813fa441)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/exec.c:would_dump
```
```
In fs/pipe.c (ffffffff813fe807)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/pipe.c:alloc_pipe_info
```
```
In fs/fcntl.c (ffffffff81409ed3)
Location: include/linux/refcount.h:248
Inline: True
```
```
In fs/namespace.c (ffffffff81425985)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_get
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:alloc_mnt_ns
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
  - fs/namespace.c:mnt_init
```
```
In fs/fs_context.c (ffffffff8143f278)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/fs_context.c:alloc_fs_context
  - fs/fs_context.c:alloc_fs_context
  - fs/fs_context.c:alloc_fs_context
  - fs/fs_context.c:alloc_fs_context
```
```
In fs/proc_namespace.c (ffffffff8144cb95)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/notify/group.c (ffffffff8144ee3a)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_get_group
```
```
In fs/notify/mark.c (ffffffff8144f9b4)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_get_mark
```
```
In fs/notify/fanotify/fanotify.c (ffffffff81453fea)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/eventpoll.c (ffffffff81457994)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_create
```
```
In fs/eventfd.c (ffffffff8145cb55)
Location: include/linux/refcount.h:248
Inline: True
```
```
In fs/userfaultfd.c (ffffffff8145df19)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_unmap_prep
  - fs/userfaultfd.c:userfaultfd_remove
  - fs/userfaultfd.c:mremap_userfaultfd_prep
  - fs/userfaultfd.c:dup_userfaultfd
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/crypto/keysetup.c (ffffffff8146ef93)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_setup_encryption_info
  - fs/crypto/keysetup.c:fscrypt_setup_encryption_info
```
```
In fs/crypto/keysetup_v1.c (ffffffff8146f71d)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
```
```
In fs/posix_acl.c (ffffffff8148315b)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/posix_acl.c:set_cached_acl
```
```
In fs/proc/root.c (ffffffff8149d463)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/proc/root.c:proc_init_fs_context
  - fs/proc/root.c:proc_init_fs_context
  - fs/proc/root.c:proc_fill_super
  - fs/proc/root.c:proc_fill_super
```
```
In fs/proc/base.c (ffffffff814a3127)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:next_tgid
  - fs/proc/base.c:proc_pid_lookup
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_open
```
```
In fs/proc/generic.c (ffffffff814a4ce3)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_readdir_de
  - fs/proc/generic.c:proc_lookup_de
```
```
In fs/proc/array.c (ffffffff814a56b9)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
```
```
In fs/proc/proc_net.c (ffffffff814ae142)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_task_net
  - fs/proc/proc_net.c:bpf_iter_init_seq_net
```
```
In fs/sysfs/mount.c (ffffffff814b84eb)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/sysfs/mount.c:sysfs_init_fs_context
```
```
In fs/configfs/item.c (ffffffff814bdd05)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/configfs/item.c:config_group_find_item
```
```
In fs/ext4/page-io.c (ffffffff81509555)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ecryptfs/keystore.c (ffffffff8156ca9b)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
```
```
In fs/fuse/dev.c (ffffffff815747d8)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:fuse_simple_request
```
```
In fs/fuse/file.c (ffffffff81581794)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_writepages_send
  - fs/fuse/file.c:fuse_write_inode
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_readahead
  - fs/fuse/file.c:fuse_async_req_send
```
```
In fs/fuse/inode.c (ffffffff815867d3)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_fill_super_common
  - fs/fuse/inode.c:fuse_get_tree_submount
  - fs/fuse/inode.c:fuse_fill_super_submount
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_conn_init
```
```
In fs/fuse/dax.c (ffffffff8158c165)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_iomap_begin
```
```
In ipc/util.c (ffffffff815938ab)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_open
  - ipc/util.c:sysvipc_proc_open
```
```
In ipc/msg.c (ffffffff81596c74)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:expunge_all
```
```
In ipc/sem.c (ffffffff8159c019)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:copy_semundo
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:update_queue
  - ipc/sem.c:wake_const_ops
  - ipc/sem.c:perform_atomic_semop
  - ipc/sem.c:perform_atomic_semop_slow
```
```
In ipc/shm.c (ffffffff8159e927)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
```
```
In ipc/mqueue.c (ffffffff815a2ef8)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - ipc/mqueue.c:mq_init_ns
  - ipc/mqueue.c:mq_init_ns
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_init_fs_context
  - ipc/mqueue.c:mqueue_init_fs_context
```
```
In ipc/namespace.c (ffffffff815a355f)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - ipc/namespace.c:ipcns_install
  - ipc/namespace.c:ipcns_get
  - ipc/namespace.c:get_ipc_ns_exported
  - ipc/namespace.c:copy_ipcs
```
```
In security/keys/key.c (ffffffff815a5291)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_user_lookup
```
```
In security/keys/keyring.c (ffffffff815a6dd8)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_gc_select_iterator
  - security/keys/keyring.c:__key_link
  - security/keys/keyring.c:find_key_to_update
  - security/keys/keyring.c:keyring_search_rcu
```
```
In security/keys/keyctl.c (ffffffff815a8397)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/keys/keyctl.c:get_instantiation_keyring
```
```
In security/keys/process_keys.c (ffffffff815ac21c)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:install_session_keyring_to_cred
```
```
In security/keys/request_key.c (ffffffff815acfeb)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:cache_requested_key
  - security/keys/request_key.c:check_cached_key
```
```
In security/keys/request_key_auth.c (ffffffff815ada17)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
```
```
In security/apparmor/apparmorfs.c (ffffffff8160d5d8)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:policy_get_link
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
  - security/apparmor/apparmorfs.c:seq_profile_hash_open
  - security/apparmor/apparmorfs.c:seq_profile_attach_open
  - security/apparmor/apparmorfs.c:seq_profile_mode_open
  - security/apparmor/apparmorfs.c:seq_profile_name_open
  - security/apparmor/apparmorfs.c:multi_transaction_read
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
```
```
In security/apparmor/capability.c (ffffffff8160f6ed)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/apparmor/capability.c:audit_caps
```
```
In security/apparmor/task.c (ffffffff81610461)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_set_current_onexec
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_get_task_label
```
```
In security/apparmor/domain.c (ffffffff81618a91)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:find_attach
  - security/apparmor/domain.c:find_attach
```
```
In security/apparmor/policy.c (ffffffff8161c765)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_alloc_profile
  - security/apparmor/policy.c:__add_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff8161d451)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:do_loaddata_free
```
```
In security/apparmor/procattr.c (ffffffff81620017)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff8349c6d0)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_sock_graft
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - security/apparmor/lsm.c:apparmor_current_getsecid_subj
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_inode_init_security
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_task_alloc
  - security/apparmor/lsm.c:apparmor_task_alloc
  - security/apparmor/lsm.c:apparmor_task_alloc
  - security/apparmor/lsm.c:apparmor_cred_transfer
  - security/apparmor/lsm.c:apparmor_cred_prepare
```
```
In security/apparmor/resource.c (ffffffff816271be)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff81629036)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:aa_file_perm
```
```
In security/apparmor/policy_ns.c (ffffffff81629d71)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:__aa_find_or_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:aa_lookupn_ns
  - security/apparmor/policy_ns.c:aa_findn_ns
  - security/apparmor/policy_ns.c:alloc_unconfined
  - security/apparmor/policy_ns.c:alloc_unconfined
```
```
In security/apparmor/label.c (ffffffff8162c4e2)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:__label_insert
  - security/apparmor/label.c:__label_insert
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/label.c:__proxy_share
  - security/apparmor/label.c:__aa_proxy_redirect
  - security/apparmor/label.c:aa_alloc_proxy
  - security/apparmor/label.c:aa_get_current_ns
```
```
In security/apparmor/mount.c (ffffffff81630d03)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:build_pivotroot
```
```
In security/apparmor/net.c (0)
Location: include/linux/refcount.h:248
Inline: True
```
```
In security/apparmor/af_unix.c (ffffffff8163486c)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
```
```
In security/yama/yama_lsm.c (ffffffff81635592)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_task_prctl
  - security/yama/yama_lsm.c:report_access
  - security/yama/yama_lsm.c:report_access
```
```
In security/landlock/syscalls.c (ffffffff81637d30)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/landlock/syscalls.c:get_ruleset_from_fd
```
```
In security/landlock/ruleset.c (ffffffff816389df)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/landlock/ruleset.c:inherit_ruleset
  - security/landlock/ruleset.c:create_rule
```
```
In security/landlock/cred.c (ffffffff8163904c)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/landlock/cred.c:hook_cred_prepare
```
```
In crypto/api.c (ffffffff8164adb6)
Location: include/linux/refcount.h:248
Inline: True
```
```
In crypto/algapi.c (ffffffff8164d28a)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_stats_get
  - crypto/algapi.c:crypto_spawn_alg
```
```
In crypto/algboss.c (ffffffff8165734c)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - crypto/algboss.c:cryptomgr_schedule_probe
```
```
In crypto/asymmetric_keys/restrict.c (ffffffff81669088)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
```
```
In block/blk-cgroup.c (ffffffff816a2297)
Location: include/linux/refcount.h:248
Inline: True
```
```
In io_uring/io_uring.c (ffffffff81e8f900)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_register_iowq_max_workers
  - io_uring/io_uring.c:io_uring_create
  - io_uring/io_uring.c:io_get_sq_data
```
```
In io_uring/io-wq.c (ffffffff816db75b)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_create
  - io_uring/io-wq.c:io_wq_create
```
```
In lib/cpu_rmap.c (ffffffff81762125)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
```
```
In lib/klist.c (ffffffff81778ddb)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - lib/klist.c:klist_next
  - lib/klist.c:klist_prev
```
```
In lib/kobject.c (ffffffff817797d7)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - lib/kobject.c:kobject_get
```
```
In lib/kobject_uevent.c (ffffffff8177b29b)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - lib/kobject_uevent.c:kobject_uevent_net_broadcast
```
```
In drivers/pinctrl/core.c (ffffffff817963bf)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_get
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff817efef4)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff81808b4e)
Location: include/linux/refcount.h:248
Inline: True
```
```
In drivers/acpi/ec.c (ffffffff81834c0a)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_submit_query
```
```
In drivers/acpi/thermal.c (ffffffff81892d5b)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/acpi/thermal.c:acpi_thermal_check_fn
```
```
In drivers/clk/clk.c (ffffffff818b1a59)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_hw_create_clk
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff818d95ea)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
```
```
In drivers/reset/core.c (ffffffff818eeadf)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/reset/core.c:__reset_control_get_internal
```
```
In drivers/tty/tty_io.c (ffffffff818f40f8)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:__do_SAK
  - drivers/tty/tty_io.c:tty_fasync
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:tty_lookup_driver
  - drivers/tty/tty_io.c:tty_lookup_driver
  - drivers/tty/tty_io.c:tty_lookup_driver
  - drivers/tty/tty_io.c:tty_find_polling_driver
```
```
In drivers/tty/tty_port.c (ffffffff818fc723)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_tty_get
```
```
In drivers/tty/tty_mutex.c (ffffffff818fd0f2)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/tty_mutex.c:tty_lock
```
```
In drivers/tty/tty_ldsem.c (ffffffff81f2899d)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:down_read_failed
```
```
In drivers/tty/tty_jobctrl.c (ffffffff818feadb)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_get_pgrp
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:get_current_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
```
```
In drivers/tty/pty.c (ffffffff818ffc35)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/tty/pty.c:pty_common_install
  - drivers/tty/pty.c:pty_common_install
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff81902940)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_k_ioctl
```
```
In drivers/char/virtio_console.c (ffffffff81939ba8)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:port_fops_open
```
```
In drivers/char/hw_random/core.c (ffffffff8193bdfb)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:hwrng_register
  - drivers/char/hw_random/core.c:hwrng_fillfn
```
```
In drivers/connector/connector.c (ffffffff81971fd0)
Location: include/linux/refcount.h:248
Inline: True
```
```
In drivers/base/core.c (ffffffff8197889b)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/power/runtime.c (ffffffff819912f3)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_get_suppliers
```
```
In drivers/base/firmware_loader/main.c (ffffffff819a013c)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:assign_fw
  - drivers/base/firmware_loader/main.c:alloc_lookup_fw_priv
```
```
In drivers/nvdimm/core.c (ffffffff819d47bb)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff819d888a)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:get_ndd
```
```
In drivers/dax/bus.c (ffffffff819ebb18)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:alloc_dax_region
```
```
In drivers/dma-buf/dma-buf.c (ffffffff819ed43c)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll_add_cb
```
```
In drivers/dma-buf/dma-fence.c (ffffffff819ee70b)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff819ef833)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff819f0143)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_find_seqno
```
```
In drivers/dma-buf/dma-resv.c (ffffffff819f145e)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_replace_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_add_fence
```
```
In drivers/dma-buf/sync_file.c (ffffffff819f3dd9)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sync_file.c:sync_file_get_fence
  - drivers/dma-buf/sync_file.c:sync_file_create
```
```
In drivers/dma-buf/sw_sync.c (ffffffff819f4cde)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_pt_create
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff81a09661)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
```
```
In drivers/scsi/sg.c (ffffffff81a1e0a9)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_sfp
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/ata/libata-core.c (ffffffff81a2a0aa)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_get
```
```
In drivers/net/phy/phy_device.c (ffffffff81a58cf1)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_package_join
```
```
In drivers/net/phy/sfp-bus.c (ffffffff81a5e1f5)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_add_upstream
  - drivers/net/phy/sfp-bus.c:sfp_bus_get
```
```
In drivers/net/tun.c (ffffffff81a647c8)
Location: include/linux/refcount.h:248
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81a69f51)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_init
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
```
In drivers/net/xen-netfront.c (ffffffff81a7216a)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_make_one_txreq
```
```
In drivers/vfio/vfio.c (ffffffff81a76a33)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_set_container
  - drivers/vfio/vfio.c:__vfio_group_get_from_iommu
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81a7ccba)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map
```
```
In drivers/usb/core/hub.c (ffffffff81a92ca1)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/hcd.c (ffffffff81a99af5)
Location: include/linux/refcount.h:248
Inline: True
```
```
In drivers/usb/core/urb.c (ffffffff81a9cae5)
Location: include/linux/refcount.h:248
Inline: True
```
```
In drivers/usb/core/message.c (ffffffff81aa07e7)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_set_configuration
```
```
In drivers/usb/core/file.c (ffffffff81aa4f04)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_register_dev
```
```
In drivers/usb/core/devio.c (ffffffff81aaa24d)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:async_completed
```
```
In drivers/md/dm.c (ffffffff81b73415)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_get_table_device
```
```
In drivers/md/dm-table.c (ffffffff81b75933)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_get_device
```
```
In drivers/opp/core.c (ffffffff81b895c3)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_adjust_voltage
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_xlate_required_opp
  - drivers/opp/core.c:_set_opp
  - drivers/opp/core.c:_set_opp
  - drivers/opp/core.c:dev_pm_opp_find_bw_floor
  - drivers/opp/core.c:dev_pm_opp_find_bw_ceil
  - drivers/opp/core.c:dev_pm_opp_find_level_ceil
  - drivers/opp/core.c:dev_pm_opp_find_level_exact
  - drivers/opp/core.c:dev_pm_opp_find_freq_ceil_by_volt
  - drivers/opp/core.c:dev_pm_opp_find_freq_floor
  - drivers/opp/core.c:_find_freq_ceil
  - drivers/opp/core.c:dev_pm_opp_find_freq_exact
  - drivers/opp/core.c:_find_opp_table_unlocked
```
```
In drivers/remoteproc/remoteproc_virtio.c (ffffffff81bd0b00)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_add_virtio_dev
```
```
In drivers/nvmem/core.c (ffffffff81bdfb07)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/nvmem/core.c:__nvmem_device_get
```
```
In net/core/sock.c (ffffffff81bef9d9)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
```
In net/core/skbuff.c (ffffffff81bff9e4)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:msg_zerocopy_realloc
  - net/core/skbuff.c:msg_zerocopy_realloc
  - net/core/skbuff.c:mm_account_pinned_pages
  - net/core/skbuff.c:__copy_skb_header
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/core/datagram.c (ffffffff81c0125d)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_from_queue
```
```
In net/core/scm.c (ffffffff81c02924)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
  - net/core/scm.c:__scm_send
```
```
In net/core/net_namespace.c (ffffffff81c05267)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_get
  - net/core/net_namespace.c:get_net_ns_by_pid
  - net/core/net_namespace.c:get_net_ns_by_fd
  - net/core/net_namespace.c:get_net_ns
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:copy_net_ns
```
```
In net/core/dev.c (ffffffff81c13aa5)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/neighbour.c (ffffffff81c27800)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_alloc
```
```
In net/core/rtnetlink.c (ffffffff81c2c3c5)
Location: include/linux/refcount.h:248
Inline: True
```
```
In net/core/flow_offload.c (ffffffff81c52ac3)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_dev_register
```
```
In net/core/net-sysfs.c (ffffffff81c562be)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/core/net-sysfs.c:net_grab_current_ns
```
```
In net/core/page_pool.c (ffffffff81c5a8b3)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_use_xdp_mem
```
```
In net/core/netpoll.c (ffffffff81c5c02e)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_setup
```
```
In net/core/devlink.c (ffffffff81c7982d)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_health_reporter_get_from_attrs
  - net/core/devlink.c:devlink_health_reporter_get_from_attrs
  - net/core/devlink.c:devlink_nl_rate_parent_node_set
  - net/core/devlink.c:devlink_nl_pre_doit
```
```
In net/core/skmsg.c (ffffffff81c8d538)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_psock_init
```
```
In net/core/sock_map.c (ffffffff81c8f01c)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_free
```
```
In net/sched/sch_generic.c (ffffffff81c96bf9)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/sched/sch_generic.c:attach_default_qdiscs
  - net/sched/sch_generic.c:attach_default_qdiscs
```
```
In net/sched/sch_api.c (ffffffff81c9c9e5)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
```
```
In net/sched/cls_api.c (ffffffff81c9e8a0)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_chain_tp_find
  - net/sched/cls_api.c:tcf_chain_tp_insert_unique
  - net/sched/cls_api.c:__tcf_block_find
  - net/sched/cls_api.c:__tcf_get_next_proto
```
```
In net/sched/act_api.c (ffffffff81ca4e76)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_idr_check_alloc
  - net/sched/act_api.c:tcf_idr_search
```
```
In net/netlink/af_netlink.c (ffffffff81caf5ac)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_getsockbyfilp
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/bpf/test_run.c (ffffffff81cb4aa2)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_kfunc_call_test_kptr_get
  - net/bpf/test_run.c:bpf_kfunc_call_test_acquire
```
```
In net/ipv4/route.c (ffffffff81ccf7c5)
Location: include/linux/refcount.h:248
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff81cd6b8a)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/ip_output.c (ffffffff81cdb87f)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/ip_sockglue.c (ffffffff81cdf77e)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_ra_control
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81ce35c7)
Location: include/linux/refcount.h:248
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ce51d6)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_complete_hashdance
```
```
In net/ipv4/tcp.c (ffffffff81cee250)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff81cf1cca)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (ffffffff81d01b7c)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tso_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_tsq_handler
```
```
In net/ipv4/tcp_timer.c (ffffffff81d05bd8)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d0ab55)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
```
```
In net/ipv4/udp.c (ffffffff81d1b417)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/arp.c (ffffffff81d2323a)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_constructor
```
```
In net/ipv4/devinet.c (ffffffff81d2af97)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
```
```
In net/ipv4/igmp.c (ffffffff81d31683)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv4/igmp.c:____ip_mc_inc_group
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_ifc_event
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
```
```
In net/ipv4/fib_semantics.c (ffffffff81d3a074)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/fib_trie.c (ffffffff81d3f332)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv4/inet_fragment.c (ffffffff81d414bc)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:fqdir_init
```
```
In net/ipv4/ping.c (ffffffff81d439b2)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_get_port
```
```
In net/ipv4/nexthop.c (ffffffff81d4cc03)
Location: include/linux/refcount.h:248
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81d5f0e8)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_check
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d663b5)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:__xfrm_policy_link
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
```
```
In net/xfrm/xfrm_state.c (ffffffff81d72727)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:xfrm_state_lookup_byspi
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
```
```
In net/xfrm/xfrm_output.c (ffffffff81d78310)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
```
```
In net/unix/af_unix.c (ffffffff81d7dd76)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/unix/af_unix.c:bpf_iter_unix_batch
  - net/unix/af_unix.c:bpf_iter_unix_batch
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:__unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:maybe_init_creds
  - net/unix/af_unix.c:unix_getname
  - net/unix/af_unix.c:unix_getname
  - net/unix/af_unix.c:unix_socketpair
  - net/unix/af_unix.c:unix_socketpair
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:init_peercred
```
```
In net/ipv6/anycast.c (ffffffff81d862da)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/ip6_output.c (ffffffff81d8829c)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/addrconf.c (ffffffff81d9b7ad)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_set_iftoken
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_kick
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_permanent_addr
  - net/ipv6/addrconf.c:addrconf_add_linklocal
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/route.c (ffffffff81da18a3)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:ip6_route_check_nh
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_rt_copy_init
  - net/ipv6/route.c:ip6_rt_copy_init
  - net/ipv6/route.c:ip6_dst_ifdown
```
```
In net/ipv6/ip6_fib.c (ffffffff81dae60c)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_purge_rt
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81db09a9)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ip6_ra_control
```
```
In net/ipv6/ndisc.c (ffffffff81db4214)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change
  - net/ipv6/ndisc.c:ndisc_netdev_event
  - net/ipv6/ndisc.c:ndisc_netdev_event
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_unsol_na
  - net/ipv6/ndisc.c:ndisc_constructor
  - net/ipv6/ndisc.c:ndisc_constructor
```
```
In net/ipv6/mcast.c (ffffffff81dc46dc)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_ifc_work
  - net/ipv6/mcast.c:mld_dad_work
  - net/ipv6/mcast.c:ipv6_mc_dad_complete
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:igmp6_group_dropped
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dccefd)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_route_req
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81ddef2f)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
```
```
In net/ipv6/syncookies.c (ffffffff81de3777)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/calipso.c (ffffffff81de45bf)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_cache_add
  - net/ipv6/calipso.c:calipso_cache_check
```
```
In net/packet/af_packet.c (ffffffff81df348f)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/ncsi/ncsi-cmd.c (ffffffff81e0e556)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81e14c4a)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
```
```
In net/xdp/xsk.c (ffffffff81e17a8e)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
```
```
In net/xdp/xdp_umem.c (ffffffff81e19231)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
  - net/xdp/xdp_umem.c:xdp_get_umem
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81e1a572)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_dma_map
  - net/xdp/xsk_buff_pool.c:xp_get_pool
```
```
In net/mptcp/protocol.c (ffffffff81e1ec10)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_finish_join
  - net/mptcp/protocol.c:mptcp_finish_join
  - net/mptcp/protocol.c:__mptcp_check_push
  - net/mptcp/protocol.c:mptcp_accept
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:__mptcp_subflow_push_pending
```
```
In net/mptcp/subflow.c (ffffffff81e2814b)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
  - net/mptcp/subflow.c:__mptcp_subflow_connect
  - net/mptcp/subflow.c:get_mapping_status
  - net/mptcp/subflow.c:mptcp_subflow_reset
```
```
In net/mptcp/options.c (ffffffff81e2ab18)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_incoming_options
```
```
In net/mctp/af_mctp.c (ffffffff81e37b06)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_sk_hash
```
```
In net/mctp/device.c (ffffffff81e38b4b)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_dev_set_key
```
```
In net/mctp/route.c (ffffffff81e3b03f)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_local_output
  - net/mctp/route.c:mctp_alloc_local_tag
  - net/mctp/route.c:mctp_route_input
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
In init/main.c (ffffffff83e61962)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In arch/x86/kernel/ioport.c (ffffffff81050ed0)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:io_bitmap_share
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8107c177)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8108610b)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_init_fs_context
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8108fb84)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_mm_add
```
```
In kernel/fork.c (ffffffff810e8ddd)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/fork.c:kernel_clone
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_sighand
  - kernel/fork.c:mm_init
  - kernel/fork.c:vm_area_dup
```
```
In kernel/exit.c (ffffffff810f08a3)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_stopped
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:make_task_dead
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:release_task
```
```
In kernel/user.c (ffffffff810fd291)
Location: include/linux/refcount.h:248
Inline: True
```
```
In kernel/sys.c (ffffffff8110b6ac)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_prlimit64
```
```
In kernel/pid.c (ffffffff81118baa)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/pid.c:pidfd_getfd
  - kernel/pid.c:__ia32_sys_pidfd_open
  - kernel/pid.c:__x64_sys_pidfd_open
  - kernel/pid.c:pidfd_create
  - kernel/pid.c:pidfd_get_task
  - kernel/pid.c:pidfd_get_pid
  - kernel/pid.c:get_task_pid
  - kernel/pid.c:find_get_task_by_vpid
  - kernel/pid.c:alloc_pid
```
```
In kernel/kthread.c (ffffffff8111d77a)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_stop
```
```
In kernel/nsproxy.c (ffffffff8112451a)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/nsproxy.c:validate_nsset
  - kernel/nsproxy.c:validate_nsset
  - kernel/nsproxy.c:create_new_namespaces
```
```
In kernel/cred.c (ffffffff81126c2a)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
```
```
In kernel/smpboot.c (ffffffff81129879)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/smpboot.c:__smpboot_create_thread
```
```
In kernel/ucount.c (ffffffff8112a670)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/ucount.c:alloc_ucounts
```
```
In kernel/usermode_driver.c (ffffffff8112b3b5)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/usermode_driver.c:umd_setup
```
```
In kernel/sched/core.c (ffffffff811354e5)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/sched/core.c:balance_push
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__do_sys_sched_setattr
  - kernel/sched/core.c:do_sched_setscheduler
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:wake_q_add
```
```
In kernel/sched/fair.c (ffffffff811452a7)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_assign
```
```
In kernel/sched/build_policy.c (ffffffff81159e3b)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:pull_dl_task
  - kernel/sched/build_policy.c:push_dl_task
  - kernel/sched/build_policy.c:start_dl_timer
  - kernel/sched/build_policy.c:task_non_contending
  - kernel/sched/build_policy.c:pull_rt_task
  - kernel/sched/build_policy.c:push_rt_task
  - kernel/sched/build_policy.c:push_rt_task
```
```
In kernel/sched/build_utility.c (ffffffff8117c2ea)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:proc_sched_autogroup_show_task
  - kernel/sched/build_utility.c:proc_sched_autogroup_show_task
  - kernel/sched/build_utility.c:proc_sched_autogroup_set_nice
  - kernel/sched/build_utility.c:proc_sched_autogroup_set_nice
  - kernel/sched/build_utility.c:sched_autogroup_fork
  - kernel/sched/build_utility.c:sched_autogroup_fork
  - kernel/sched/build_utility.c:sched_autogroup_create_attach
  - kernel/sched/build_utility.c:autogroup_move_group
  - kernel/sched/build_utility.c:sched_core_share_pid
  - kernel/sched/build_utility.c:__sched_core_set
  - kernel/sched/build_utility.c:sched_core_fork
```
```
In kernel/locking/rwsem.c (ffffffff8117d15c)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
```
```
In kernel/locking/percpu-rwsem.c (ffffffff8117dbb9)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wake_function
```
```
In kernel/locking/rtmutex_api.c (ffffffff820d3b3f)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_pi
  - kernel/locking/rtmutex_api.c:remove_waiter
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
```
```
In kernel/irq/manage.c (ffffffff8119687b)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/irq/manage.c:setup_irq_thread
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/rcu/update.c (ffffffff811aba3d)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_trace_pregp_step
  - kernel/rcu/update.c:trc_inspect_reader
```
```
In kernel/rcu/tree.c (ffffffff811b139c)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_print_task_stall
```
```
In kernel/kcmp.c (ffffffff811d0944)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
```
```
In kernel/time/posix-timers.c (ffffffff811e6324)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811e8d3b)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_create
```
```
In kernel/time/namespace.c (ffffffff811f2daf)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/time/namespace.c:proc_timens_set_offset
  - kernel/time/namespace.c:proc_timens_show_offsets
  - kernel/time/namespace.c:timens_on_fork
  - kernel/time/namespace.c:timens_install
  - kernel/time/namespace.c:timens_install
  - kernel/time/namespace.c:timens_get
  - kernel/time/namespace.c:copy_time_ns
  - kernel/time/namespace.c:copy_time_ns
```
```
In kernel/futex/waitwake.c (ffffffff811f7dd1)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/futex/waitwake.c:futex_wake_mark
```
```
In kernel/cgroup/cgroup.c (ffffffff8120fe8f)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:css_task_iter_next
  - kernel/cgroup/cgroup.c:css_task_iter_advance_css_set
  - kernel/cgroup/cgroup.c:css_task_iter_advance_css_set
  - kernel/cgroup/cgroup.c:cgroup_file_open
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/cgroup/namespace.c (ffffffff81211f17)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:cgroupns_get
  - kernel/cgroup/namespace.c:cgroupns_install
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81212df9)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
```
In kernel/utsname.c (ffffffff8121fe78)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_install
  - kernel/utsname.c:utsns_get
  - kernel/utsname.c:copy_utsname
  - kernel/utsname.c:clone_uts_ns
```
```
In kernel/user_namespace.c (ffffffff81221271)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/user_namespace.c:ns_get_owner
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_get
```
```
In kernel/pid_namespace.c (ffffffff81222913)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_get_parent
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:pidns_get
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/pid_namespace.c:create_pid_namespace
  - kernel/pid_namespace.c:create_pid_namespace
```
```
In kernel/audit.c (ffffffff81226d7c)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/audit.c:audit_get_tty
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_send_queue
```
```
In kernel/auditfilter.c (ffffffff8122ad64)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In kernel/audit_watch.c (ffffffff81232328)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_tree.c (ffffffff81234f6a)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_trim_trees
  - kernel/audit_tree.c:tag_chunk
  - kernel/audit_tree.c:create_chunk
  - kernel/audit_tree.c:replace_chunk
```
```
In kernel/hung_task.c (ffffffff81246ff2)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
```
```
In kernel/seccomp.c (ffffffff8124ac36)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_attach_filter
  - kernel/seccomp.c:seccomp_attach_filter
```
```
In kernel/relay.c (ffffffff8124cba4)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_open
  - kernel/relay.c:relay_create_buf
```
```
In kernel/trace/trace.c (ffffffff81265083)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/trace/trace.c:buffer_pipe_buf_get
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8127ad14)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/trace/bpf_trace.c (ffffffff812a6c69)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_send_signal_common
```
```
In kernel/trace/rethook.c (ffffffff812bb469)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/trace/rethook.c:rethook_add_node
```
```
In kernel/bpf/syscall.c (ffffffff812ca45c)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In kernel/bpf/helpers.c (ffffffff812f453b)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_task_from_pid
```
```
In kernel/bpf/task_iter.c (ffffffff812f6814)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:init_seq_pidns
  - kernel/bpf/task_iter.c:task_group_seq_get_next
```
```
In kernel/bpf/trampoline.c (ffffffff813085c5)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_lookup
```
```
In kernel/bpf/btf.c (ffffffff81318b4b)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_by_fd
  - kernel/bpf/btf.c:bpf_find_btf_id
  - kernel/bpf/btf.c:bpf_find_btf_id
```
```
In kernel/bpf/dispatcher.c (ffffffff8131ccf7)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog
```
```
In kernel/bpf/offload.c (ffffffff813215cc)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_map_offload_info_fill_ns
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill_ns
```
```
In kernel/events/core.c (ffffffff8134480d)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_context
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_remove_from_owner
  - kernel/events/core.c:find_get_context
  - kernel/events/core.c:find_get_context
  - kernel/events/core.c:alloc_perf_context
```
```
In kernel/events/uprobes.c (ffffffff813529a1)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/events/uprobes.c:prepare_uretprobe
  - kernel/events/uprobes.c:uprobe_copy_process
  - kernel/events/uprobes.c:uprobe_mmap
  - kernel/events/uprobes.c:uprobe_mmap
  - kernel/events/uprobes.c:alloc_uprobe
  - kernel/events/uprobes.c:__find_uprobe
```
```
In kernel/padata.c (ffffffff813542b9)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_parallel
```
```
In kernel/watch_queue.c (ffffffff813571de)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/watch_queue.c:get_watch_queue
  - kernel/watch_queue.c:add_watch_to_object
  - kernel/watch_queue.c:add_watch_to_object
```
```
In mm/oom_kill.c (ffffffff813657bb)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - mm/oom_kill.c:out_of_memory
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:oom_evaluate_task
```
```
In mm/backing-dev.c (ffffffff81398cf1)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_get_by_id
  - mm/backing-dev.c:cgwb_create
```
```
In mm/madvise.c (ffffffff813f5d9c)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - mm/madvise.c:madvise_vma_behavior
  - mm/madvise.c:madvise_update_vma
```
```
In mm/page_io.c (ffffffff813f81ba)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
```
```
In mm/hugetlb.c (ffffffff81406c1b)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_vm_op_open
```
```
In mm/mempolicy.c (ffffffff814173bc)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_migrate_pages
```
```
In mm/migrate.c (ffffffff81431677)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - mm/migrate.c:find_mm_struct
```
```
In mm/memory-tiers.c (ffffffff814376ef)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - mm/memory-tiers.c:init_node_memory_type
  - mm/memory-tiers.c:set_node_memory_tier
```
```
In mm/huge_memory.c (ffffffff81442cae)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_pid
```
```
In mm/memory-failure.c (ffffffff81460bea)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - mm/memory-failure.c:add_to_kill
```
```
In fs/super.c (ffffffff8147deb8)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/super.c:set_bdev_super_fc
  - fs/super.c:alloc_super
```
```
In fs/exec.c (ffffffff81483f45)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/exec.c:would_dump
```
```
In fs/pipe.c (ffffffff81488507)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/pipe.c:alloc_pipe_info
```
```
In fs/fcntl.c (ffffffff81494643)
Location: include/linux/refcount.h:248
Inline: True
```
```
In fs/namespace.c (ffffffff814b2155)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_get
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:alloc_mnt_ns
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:mnt_init
```
```
In fs/fs_context.c (ffffffff814ce140)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/fs_context.c:alloc_fs_context
  - fs/fs_context.c:alloc_fs_context
  - fs/fs_context.c:alloc_fs_context
  - fs/fs_context.c:alloc_fs_context
```
```
In fs/proc_namespace.c (ffffffff814db105)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/notify/group.c (ffffffff814dd60a)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_get_group
```
```
In fs/notify/mark.c (ffffffff814de2a4)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_get_mark
```
```
In fs/notify/fanotify/fanotify.c (ffffffff814e2e9a)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/eventpoll.c (ffffffff814e6c74)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_create
```
```
In fs/eventfd.c (ffffffff814ec285)
Location: include/linux/refcount.h:248
Inline: True
```
```
In fs/userfaultfd.c (ffffffff814ed970)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_unmap_prep
  - fs/userfaultfd.c:userfaultfd_remove
  - fs/userfaultfd.c:mremap_userfaultfd_prep
  - fs/userfaultfd.c:dup_userfaultfd
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/crypto/keysetup.c (ffffffff815005f3)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_setup_encryption_info
```
```
In fs/crypto/keysetup_v1.c (ffffffff81500f03)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
```
```
In fs/posix_acl.c (ffffffff815163fb)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/posix_acl.c:set_cached_acl
```
```
In fs/proc/root.c (ffffffff81531f63)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/proc/root.c:proc_init_fs_context
  - fs/proc/root.c:proc_init_fs_context
  - fs/proc/root.c:proc_fill_super
  - fs/proc/root.c:proc_fill_super
```
```
In fs/proc/base.c (ffffffff815383a7)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:next_tgid
  - fs/proc/base.c:proc_pid_lookup
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_open
```
```
In fs/proc/generic.c (ffffffff8153a213)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_readdir_de
  - fs/proc/generic.c:proc_lookup_de
```
```
In fs/proc/array.c (ffffffff8153ac99)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
```
```
In fs/proc/proc_net.c (ffffffff81544712)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_task_net
  - fs/proc/proc_net.c:bpf_iter_init_seq_net
```
```
In fs/sysfs/mount.c (ffffffff8154fafb)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/sysfs/mount.c:sysfs_init_fs_context
```
```
In fs/configfs/item.c (ffffffff81555a65)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/configfs/item.c:config_group_find_item
```
```
In fs/ext4/page-io.c (ffffffff815a4143)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/hugetlbfs/inode.c (ffffffff815f67f6)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlb_unmap_file_folio
```
```
In fs/ecryptfs/keystore.c (ffffffff81610ea9)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
```
```
In fs/fuse/dev.c (ffffffff8161a5dc)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:fuse_simple_request
```
```
In fs/fuse/file.c (ffffffff816275f4)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_writepages_send
  - fs/fuse/file.c:fuse_write_inode
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_readahead
  - fs/fuse/file.c:fuse_async_req_send
```
```
In fs/fuse/inode.c (ffffffff8162ca4b)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_fill_super_common
  - fs/fuse/inode.c:fuse_get_tree_submount
  - fs/fuse/inode.c:fuse_fill_super_submount
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_conn_init
```
```
In fs/fuse/dax.c (ffffffff816329b5)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_iomap_begin
```
```
In ipc/util.c (ffffffff8163c42b)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_open
  - ipc/util.c:sysvipc_proc_open
```
```
In ipc/msg.c (ffffffff8163fb79)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:expunge_all
```
```
In ipc/sem.c (ffffffff81645419)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:copy_semundo
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:update_queue
  - ipc/sem.c:wake_const_ops
  - ipc/sem.c:perform_atomic_semop
  - ipc/sem.c:perform_atomic_semop_slow
```
```
In ipc/shm.c (ffffffff81647fe7)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:newseg
  - ipc/shm.c:__shm_close
  - ipc/shm.c:__shm_open
```
```
In ipc/mqueue.c (ffffffff8164ca58)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - ipc/mqueue.c:mq_init_ns
  - ipc/mqueue.c:mq_init_ns
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_init_fs_context
  - ipc/mqueue.c:mqueue_init_fs_context
```
```
In ipc/namespace.c (ffffffff8164d16f)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - ipc/namespace.c:ipcns_install
  - ipc/namespace.c:ipcns_get
  - ipc/namespace.c:get_ipc_ns_exported
  - ipc/namespace.c:copy_ipcs
```
```
In security/keys/key.c (ffffffff8164f081)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_user_lookup
```
```
In security/keys/keyring.c (ffffffff81650d98)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_gc_select_iterator
  - security/keys/keyring.c:__key_link
  - security/keys/keyring.c:find_key_to_update
  - security/keys/keyring.c:keyring_search_rcu
```
```
In security/keys/keyctl.c (ffffffff816524a7)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/keys/keyctl.c:get_instantiation_keyring
```
```
In security/keys/process_keys.c (ffffffff816566ac)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:install_session_keyring_to_cred
```
```
In security/keys/request_key.c (ffffffff8165751b)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:cache_requested_key
  - security/keys/request_key.c:check_cached_key
```
```
In security/keys/request_key_auth.c (ffffffff81658077)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
```
```
In security/apparmor/apparmorfs.c (ffffffff816bf558)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:policy_get_link
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
  - security/apparmor/apparmorfs.c:multi_transaction_read
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
```
```
In security/apparmor/audit.c (ffffffff816c1b7b)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/apparmor/audit.c:aa_dup_audit_data
  - security/apparmor/audit.c:aa_dup_audit_data
```
```
In security/apparmor/capability.c (ffffffff816c20eb)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/apparmor/capability.c:audit_caps
```
```
In security/apparmor/task.c (ffffffff816c2ec1)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_set_current_onexec
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_get_task_label
```
```
In security/apparmor/domain.c (ffffffff816cbd6d)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:find_attach
  - security/apparmor/domain.c:find_attach
```
```
In security/apparmor/policy.c (ffffffff816cfa05)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:aa_new_learning_profile
  - security/apparmor/policy.c:aa_alloc_null
  - security/apparmor/policy.c:aa_alloc_null
  - security/apparmor/policy.c:aa_alloc_null
  - security/apparmor/policy.c:aa_alloc_null
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_alloc_profile
  - security/apparmor/policy.c:__add_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff816d07f1)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:do_loaddata_free
```
```
In security/apparmor/procattr.c (ffffffff816d3514)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff83ed3c09)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_sock_graft
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_current_getsecid_subj
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_inode_init_security
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_task_alloc
  - security/apparmor/lsm.c:apparmor_task_alloc
  - security/apparmor/lsm.c:apparmor_task_alloc
  - security/apparmor/lsm.c:apparmor_cred_transfer
  - security/apparmor/lsm.c:apparmor_cred_prepare
```
```
In security/apparmor/resource.c (ffffffff816db1d2)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff816dd8fb)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:aa_file_perm
```
```
In security/apparmor/policy_ns.c (ffffffff83ed3e74)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_alloc_root_ns
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:__aa_find_or_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:aa_lookupn_ns
  - security/apparmor/policy_ns.c:aa_find_ns
```
```
In security/apparmor/label.c (ffffffff816e0f82)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:__label_insert
  - security/apparmor/label.c:__label_insert
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/label.c:__proxy_share
  - security/apparmor/label.c:__aa_proxy_redirect
  - security/apparmor/label.c:aa_alloc_proxy
  - security/apparmor/label.c:aa_get_current_ns
```
```
In security/apparmor/mount.c (ffffffff816e5a3f)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:build_pivotroot
```
```
In security/apparmor/net.c (0)
Location: include/linux/refcount.h:248
Inline: True
```
```
In security/apparmor/af_unix.c (ffffffff816e97a0)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
```
```
In security/apparmor/notify.c (ffffffff816ea1b9)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/apparmor/notify.c:build_unotif
  - security/apparmor/notify.c:aa_do_notification
  - security/apparmor/notify.c:aa_do_notification
  - security/apparmor/notify.c:aa_new_listener
  - security/apparmor/notify.c:aa_register_listener_proxy
  - security/apparmor/notify.c:aa_get_current_ns
```
```
In security/yama/yama_lsm.c (ffffffff816ec272)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_task_prctl
  - security/yama/yama_lsm.c:report_access
  - security/yama/yama_lsm.c:report_access
```
```
In security/landlock/syscalls.c (ffffffff816ef130)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/landlock/syscalls.c:get_ruleset_from_fd
```
```
In security/landlock/ruleset.c (ffffffff816f001f)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/landlock/ruleset.c:inherit_ruleset
  - security/landlock/ruleset.c:create_rule
```
```
In security/landlock/cred.c (ffffffff816f059c)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/landlock/cred.c:hook_cred_prepare
```
```
In crypto/api.c (ffffffff81703f86)
Location: include/linux/refcount.h:248
Inline: True
```
```
In crypto/algapi.c (ffffffff817062ca)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_stats_get
  - crypto/algapi.c:crypto_spawn_alg
```
```
In crypto/algboss.c (ffffffff81711772)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - crypto/algboss.c:cryptomgr_schedule_probe
```
```
In crypto/asymmetric_keys/restrict.c (ffffffff817238d8)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
```
```
In block/blk-core.c (ffffffff817347d5)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - block/blk-core.c:blk_get_queue
```
```
In block/blk-cgroup.c (ffffffff81760c59)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_online
```
```
In io_uring/io_uring.c (ffffffff8178c6a6)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - io_uring/io_uring.c:__io_uring_register
  - io_uring/io_uring.c:io_register_iowq_max_workers
  - io_uring/io_uring.c:io_uring_create
  - io_uring/io_uring.c:io_uring_create
```
```
In io_uring/sqpoll.c (ffffffff8179a16d)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - io_uring/sqpoll.c:io_get_sq_data
```
```
In io_uring/rsrc.c (ffffffff817a1517)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - io_uring/rsrc.c:__io_scm_file_account
```
```
In io_uring/io-wq.c (ffffffff817a7841)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_create
  - io_uring/io-wq.c:io_wq_create
```
```
In lib/cpu_rmap.c (ffffffff81890e45)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
```
```
In drivers/pinctrl/core.c (ffffffff818abadf)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_get
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff819180a4)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff819374be)
Location: include/linux/refcount.h:248
Inline: True
```
```
In drivers/acpi/ec.c (ffffffff819687ca)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_submit_query
```
```
In drivers/acpi/thermal.c (ffffffff819da69b)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/acpi/thermal.c:acpi_thermal_check_fn
```
```
In drivers/clk/clk.c (ffffffff819fe059)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_hw_create_clk
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff81a2c0aa)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
```
```
In drivers/reset/core.c (ffffffff81a4673f)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/reset/core.c:__reset_control_get_internal
```
```
In drivers/tty/tty_io.c (ffffffff81a4c7cf)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:__do_SAK
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:tty_lookup_driver
  - drivers/tty/tty_io.c:tty_lookup_driver
  - drivers/tty/tty_io.c:tty_lookup_driver
  - drivers/tty/tty_io.c:tty_find_polling_driver
```
```
In drivers/tty/tty_port.c (ffffffff81a55d5f)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_tty_get
```
```
In drivers/tty/tty_mutex.c (ffffffff81a567a6)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/tty_mutex.c:tty_lock
```
```
In drivers/tty/tty_ldsem.c (ffffffff820d45fd)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:down_read_failed
```
```
In drivers/tty/tty_jobctrl.c (ffffffff81a5831b)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_get_pgrp
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:get_current_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
```
```
In drivers/tty/pty.c (ffffffff81a59661)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/tty/pty.c:pty_common_install
  - drivers/tty/pty.c:pty_common_install
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff81a5c910)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_k_ioctl
```
```
In drivers/char/virtio_console.c (ffffffff81a99e38)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:port_fops_open
```
```
In drivers/char/hw_random/core.c (ffffffff81a9c63f)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:hwrng_register
  - drivers/char/hw_random/core.c:hwrng_fillfn
```
```
In drivers/connector/connector.c (ffffffff81add270)
Location: include/linux/refcount.h:248
Inline: True
```
```
In drivers/base/core.c (ffffffff81ae5178)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/power/runtime.c (ffffffff81b01673)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_get_suppliers
```
```
In drivers/base/firmware_loader/main.c (ffffffff81b11c9c)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:assign_fw
  - drivers/base/firmware_loader/main.c:alloc_lookup_fw_priv
```
```
In drivers/nvdimm/core.c (ffffffff81b4f05b)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81b537ca)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:get_ndd
```
```
In drivers/dax/bus.c (ffffffff81b686e4)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:alloc_dax_region
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81b6a49c)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll_add_cb
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81b6bddb)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff81b6ce23)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff81b6d7c3)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_find_seqno
```
```
In drivers/dma-buf/dma-fence-unwrap.c (ffffffff81b6dee4)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-unwrap.c:__dma_fence_unwrap_merge
  - drivers/dma-buf/dma-fence-unwrap.c:dma_fence_unwrap_first
```
```
In drivers/dma-buf/dma-resv.c (ffffffff81b6f0be)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_replace_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_add_fence
```
```
In drivers/dma-buf/sync_file.c (ffffffff81b710ba)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_get_fence
  - drivers/dma-buf/sync_file.c:sync_file_create
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81b7218e)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_pt_create
```
```
In drivers/scsi/scsi_scan.c (ffffffff81b8396d)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff81b88b10)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
```
```
In drivers/scsi/sg.c (ffffffff81b9f3d9)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_sfp
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/ata/libata-core.c (ffffffff81baccea)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_get
```
```
In drivers/net/phy/phy_device.c (ffffffff81be2a71)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_package_join
```
```
In drivers/net/phy/sfp-bus.c (ffffffff81be8f35)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_add_upstream
  - drivers/net/phy/sfp-bus.c:sfp_bus_get
```
```
In drivers/net/pse-pd/pse_core.c (0)
Location: include/linux/refcount.h:248
Inline: True
```
```
In drivers/net/tun.c (ffffffff81befa38)
Location: include/linux/refcount.h:248
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81bfcb51)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_init
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
```
In drivers/net/xen-netfront.c (ffffffff81c04a1a)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_make_one_txreq
```
```
In drivers/usb/core/hub.c (ffffffff81c14e51)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/hcd.c (ffffffff81c1dc85)
Location: include/linux/refcount.h:248
Inline: True
```
```
In drivers/usb/core/urb.c (ffffffff81c21ad5)
Location: include/linux/refcount.h:248
Inline: True
```
```
In drivers/usb/core/message.c (ffffffff81c25d22)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_set_configuration
```
```
In drivers/usb/core/file.c (ffffffff81c2b8a4)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_register_dev
```
```
In drivers/usb/core/devio.c (ffffffff81c315cd)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:async_completed
```
```
In drivers/md/dm.c (ffffffff81d0ff71)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_get_table_device
```
```
In drivers/md/dm-table.c (ffffffff81d12c63)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_get_device
```
```
In drivers/opp/core.c (ffffffff81d28dd3)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_adjust_voltage
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_xlate_required_opp
  - drivers/opp/core.c:_set_opp
  - drivers/opp/core.c:_set_opp
  - drivers/opp/core.c:_opp_table_find_key
  - drivers/opp/core.c:_find_opp_table_unlocked
```
```
In drivers/nvmem/core.c (ffffffff81d8b276)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/nvmem/core.c:__nvmem_device_get
```
```
In net/core/sock.c (ffffffff81d9c826)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
```
In net/core/skbuff.c (ffffffff81da4f33)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_ext_maybe_cow
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:msg_zerocopy_realloc
  - net/core/skbuff.c:msg_zerocopy_realloc
  - net/core/skbuff.c:mm_account_pinned_pages
  - net/core/skbuff.c:__copy_skb_header
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/core/datagram.c (ffffffff81db059d)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_from_queue
```
```
In net/core/scm.c (ffffffff81db1dc4)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
  - net/core/scm.c:__scm_send
```
```
In net/core/net_namespace.c (ffffffff81db4af7)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_get
  - net/core/net_namespace.c:get_net_ns_by_pid
  - net/core/net_namespace.c:get_net_ns_by_fd
  - net/core/net_namespace.c:get_net_ns
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:copy_net_ns
```
```
In net/core/dev.c (ffffffff81dc3125)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/neighbour.c (ffffffff81dda3b0)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_alloc
  - net/core/neighbour.c:neigh_add_timer
```
```
In net/core/rtnetlink.c (ffffffff81ddf495)
Location: include/linux/refcount.h:248
Inline: True
```
```
In net/core/flow_offload.c (ffffffff81e08083)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_dev_register
```
```
In net/core/net-sysfs.c (ffffffff81e0beae)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/core/net-sysfs.c:net_grab_current_ns
```
```
In net/core/page_pool.c (ffffffff81e10a23)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_use_xdp_mem
```
```
In net/core/netpoll.c (ffffffff81e124d8)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_setup
```
```
In net/core/devlink.c (ffffffff81e3c22c)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/core/devlink.c:devl_rate_leaf_create
  - net/core/devlink.c:devlink_health_reporter_get_from_attrs
  - net/core/devlink.c:devlink_health_reporter_get_from_attrs
  - net/core/devlink.c:devlink_nl_rate_parent_node_set
  - net/core/devlink.c:devlink_nl_pre_doit
```
```
In net/core/skmsg.c (ffffffff81e4829c)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_verdict_recv
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_psock_init
```
```
In net/core/sock_map.c (ffffffff81e4a26c)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_map_free
```
```
In net/sched/sch_generic.c (ffffffff81e5280c)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/sched/sch_generic.c:attach_default_qdiscs
  - net/sched/sch_generic.c:attach_default_qdiscs
```
```
In net/sched/sch_api.c (ffffffff81e58ea9)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
```
```
In net/sched/cls_api.c (ffffffff81e5b040)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_chain_tp_find
  - net/sched/cls_api.c:tcf_chain_tp_insert_unique
  - net/sched/cls_api.c:__tcf_block_find
  - net/sched/cls_api.c:__tcf_get_next_proto
```
```
In net/sched/act_api.c (ffffffff81e61636)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_idr_check_alloc
  - net/sched/act_api.c:tcf_idr_search
```
```
In net/netlink/af_netlink.c (ffffffff81e6cbbc)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_getsockbyfilp
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/bpf/test_run.c (ffffffff81e72f02)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_kfunc_call_test_kptr_get
  - net/bpf/test_run.c:bpf_kfunc_call_test_acquire
```
```
In net/ipv4/route.c (ffffffff81e8f9d5)
Location: include/linux/refcount.h:248
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff81e97101)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/ip_output.c (ffffffff81e9c232)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/ip_sockglue.c (ffffffff81e9fc5e)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_ra_control
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81ea5aa7)
Location: include/linux/refcount.h:248
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ea83c6)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_complete_hashdance
```
```
In net/ipv4/tcp.c (ffffffff81eb2296)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_abort
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/tcp_input.c (ffffffff81eb652a)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (ffffffff81ec6cec)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tso_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_tsq_handler
```
```
In net/ipv4/tcp_timer.c (ffffffff81ecad28)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ed042a)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
```
```
In net/ipv4/udp.c (ffffffff81ee1e04)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/arp.c (ffffffff81eea73c)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_constructor
```
```
In net/ipv4/devinet.c (ffffffff81ef2bb2)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
```
```
In net/ipv4/igmp.c (ffffffff81ef9e62)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv4/igmp.c:____ip_mc_inc_group
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_ifc_event
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
```
```
In net/ipv4/fib_semantics.c (ffffffff81f029d4)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/fib_trie.c (ffffffff81f07f1d)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv4/inet_fragment.c (ffffffff81f0a28c)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:fqdir_init
```
```
In net/ipv4/ping.c (ffffffff81f0c9f2)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_get_port
```
```
In net/ipv4/nexthop.c (ffffffff81f164a3)
Location: include/linux/refcount.h:248
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81f29778)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_check
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f31145)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:__xfrm_policy_link
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
```
```
In net/xfrm/xfrm_state.c (ffffffff81f3e414)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:xfrm_state_lookup_byspi
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
```
```
In net/xfrm/xfrm_output.c (ffffffff81f44b89)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
```
```
In net/unix/af_unix.c (ffffffff81f4b12e)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/unix/af_unix.c:bpf_iter_unix_batch
  - net/unix/af_unix.c:bpf_iter_unix_batch
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:__unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:queue_oob
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:maybe_init_creds
  - net/unix/af_unix.c:unix_getname
  - net/unix/af_unix.c:unix_getname
  - net/unix/af_unix.c:unix_socketpair
  - net/unix/af_unix.c:unix_socketpair
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:init_peercred
  - net/unix/af_unix.c:__unix_set_addr_hash
```
```
In net/ipv6/anycast.c (ffffffff81f53e2a)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/ip6_output.c (ffffffff81f5604c)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/addrconf.c (ffffffff81f6a3ed)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_set_iftoken
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_kick
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_permanent_addr
  - net/ipv6/addrconf.c:addrconf_add_linklocal
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/route.c (ffffffff83f11001)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_init_special_entries
  - net/ipv6/route.c:ip6_route_init_special_entries
  - net/ipv6/route.c:ip6_route_init_special_entries
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:ip6_route_check_nh
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_rt_copy_init
  - net/ipv6/route.c:ip6_rt_copy_init
  - net/ipv6/route.c:ip6_dst_ifdown
```
```
In net/ipv6/ip6_fib.c (ffffffff81f7e118)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_purge_rt
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81f7f949)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ip6_ra_control
```
```
In net/ipv6/ndisc.c (ffffffff81f83d01)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change
  - net/ipv6/ndisc.c:ndisc_netdev_event
  - net/ipv6/ndisc.c:ndisc_netdev_event
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_unsol_na
  - net/ipv6/ndisc.c:ndisc_constructor
  - net/ipv6/ndisc.c:ndisc_constructor
```
```
In net/ipv6/mcast.c (ffffffff81f9532a)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_ifc_work
  - net/ipv6/mcast.c:mld_dad_work
  - net/ipv6/mcast.c:ipv6_mc_dad_complete
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:igmp6_group_dropped
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f9e020)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_route_req
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81fb115f)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
```
```
In net/ipv6/syncookies.c (ffffffff81fb5df7)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/calipso.c (ffffffff81fb6d0f)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_cache_add
  - net/ipv6/calipso.c:calipso_cache_check
```
```
In net/packet/af_packet.c (ffffffff81fc824f)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/ncsi/ncsi-cmd.c (ffffffff81fe496a)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81febb5a)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
```
```
In net/xdp/xsk.c (ffffffff81feea3e)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
```
```
In net/xdp/xdp_umem.c (ffffffff81ff0487)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
  - net/xdp/xdp_umem.c:xdp_get_umem
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81ff1a93)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_dma_map
  - net/xdp/xsk_buff_pool.c:xp_get_pool
```
```
In net/mptcp/protocol.c (ffffffff81ff55ad)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_finish_join
  - net/mptcp/protocol.c:mptcp_finish_join
  - net/mptcp/protocol.c:mptcp_accept
  - net/mptcp/protocol.c:__mptcp_close
  - net/mptcp/protocol.c:__mptcp_subflow_push_pending
```
```
In net/mptcp/subflow.c (ffffffff820007a4)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_queue_clean
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
  - net/mptcp/subflow.c:__mptcp_subflow_connect
  - net/mptcp/subflow.c:get_mapping_status
  - net/mptcp/subflow.c:mptcp_subflow_reset
```
```
In net/mptcp/options.c (ffffffff82002ca8)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_incoming_options
```
```
In net/mctp/af_mctp.c (ffffffff82010d76)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_sk_hash
```
```
In net/mctp/device.c (ffffffff82011e2b)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_dev_set_key
```
```
In net/mctp/route.c (ffffffff8201461f)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_local_output
  - net/mctp/route.c:mctp_alloc_local_tag
  - net/mctp/route.c:mctp_key_add
  - net/mctp/route.c:mctp_key_alloc
```
```
In lib/klist.c (ffffffff82021beb)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - lib/klist.c:klist_next
  - lib/klist.c:klist_prev
```
```
In lib/kobject.c (ffffffff82022767)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - lib/kobject.c:kobject_get
```
```
In lib/kobject_uevent.c (ffffffff820244ab)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - lib/kobject_uevent.c:kobject_uevent_net_broadcast
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
In init/main.c (ffffffff83681d82)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In arch/x86/kernel/ioport.c (ffffffff81051c00)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:io_bitmap_share
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8107e48a)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81088beb)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_init_fs_context
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81092a94)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_mm_add
```
```
In kernel/fork.c (ffffffff810f49ef)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/fork.c:kernel_clone
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:__pidfd_prepare
  - kernel/fork.c:copy_sighand
  - kernel/fork.c:mm_init
  - kernel/fork.c:vm_area_dup
```
```
In kernel/exit.c (ffffffff810fc860)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_stopped
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:make_task_dead
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:release_task
```
```
In kernel/user.c (ffffffff81109288)
Location: include/linux/refcount.h:248
Inline: True
```
```
In kernel/sys.c (ffffffff81117a3c)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_prlimit64
```
```
In kernel/pid.c (ffffffff8112606a)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/pid.c:pidfd_getfd
  - kernel/pid.c:__ia32_sys_pidfd_open
  - kernel/pid.c:__x64_sys_pidfd_open
  - kernel/pid.c:pidfd_get_task
  - kernel/pid.c:pidfd_get_pid
  - kernel/pid.c:get_task_pid
  - kernel/pid.c:find_get_task_by_vpid
  - kernel/pid.c:alloc_pid
```
```
In kernel/kthread.c (ffffffff8112a96a)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_stop
```
```
In kernel/nsproxy.c (ffffffff8113181a)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/nsproxy.c:validate_nsset
  - kernel/nsproxy.c:validate_nsset
  - kernel/nsproxy.c:create_new_namespaces
```
```
In kernel/cred.c (ffffffff811340ca)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
```
```
In kernel/smpboot.c (ffffffff81136d19)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/smpboot.c:__smpboot_create_thread
```
```
In kernel/ucount.c (ffffffff811376bf)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/ucount.c:alloc_ucounts
```
```
In kernel/usermode_driver.c (ffffffff811386a5)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/usermode_driver.c:umd_setup
```
```
In kernel/sched/core.c (ffffffff81144665)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/sched/core.c:balance_push
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__do_sys_sched_setattr
  - kernel/sched/core.c:do_sched_setscheduler
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:wake_q_add
```
```
In kernel/sched/fair.c (ffffffff811557b7)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_assign
```
```
In kernel/sched/build_policy.c (ffffffff8116a04b)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:pull_dl_task
  - kernel/sched/build_policy.c:push_dl_task
  - kernel/sched/build_policy.c:start_dl_timer
  - kernel/sched/build_policy.c:task_non_contending
  - kernel/sched/build_policy.c:pull_rt_task
  - kernel/sched/build_policy.c:push_rt_task
  - kernel/sched/build_policy.c:push_rt_task
```
```
In kernel/sched/build_utility.c (ffffffff8118cf90)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:proc_sched_autogroup_show_task
  - kernel/sched/build_utility.c:proc_sched_autogroup_show_task
  - kernel/sched/build_utility.c:proc_sched_autogroup_set_nice
  - kernel/sched/build_utility.c:proc_sched_autogroup_set_nice
  - kernel/sched/build_utility.c:sched_autogroup_fork
  - kernel/sched/build_utility.c:sched_autogroup_fork
  - kernel/sched/build_utility.c:sched_autogroup_create_attach
  - kernel/sched/build_utility.c:autogroup_move_group
  - kernel/sched/build_utility.c:sched_core_share_pid
  - kernel/sched/build_utility.c:__sched_core_set
  - kernel/sched/build_utility.c:sched_core_fork
```
```
In kernel/locking/rwsem.c (ffffffff8118de0c)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
```
```
In kernel/locking/percpu-rwsem.c (ffffffff8118e859)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wake_function
```
```
In kernel/locking/rtmutex_api.c (ffffffff82157dbf)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_pi
  - kernel/locking/rtmutex_api.c:remove_waiter
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
```
```
In kernel/irq/manage.c (ffffffff811a823b)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/irq/manage.c:setup_irq_thread
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/rcu/update.c (ffffffff811bd95d)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_trace_pregp_step
  - kernel/rcu/update.c:trc_inspect_reader
```
```
In kernel/rcu/tree.c (ffffffff811c307c)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_print_task_stall
```
```
In kernel/kcmp.c (ffffffff811e4bc4)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
```
```
In kernel/time/posix-timers.c (ffffffff811fa917)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811fd32e)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_wait_running
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_create
```
```
In kernel/time/namespace.c (ffffffff8120752f)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/time/namespace.c:proc_timens_set_offset
  - kernel/time/namespace.c:proc_timens_show_offsets
  - kernel/time/namespace.c:timens_on_fork
  - kernel/time/namespace.c:timens_install
  - kernel/time/namespace.c:timens_install
  - kernel/time/namespace.c:timens_get
  - kernel/time/namespace.c:copy_time_ns
  - kernel/time/namespace.c:copy_time_ns
```
```
In kernel/futex/waitwake.c (ffffffff8120c571)
Location: include/linux/refcount.h:248
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff8122587d)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:css_task_iter_next
  - kernel/cgroup/cgroup.c:css_task_iter_advance_css_set
  - kernel/cgroup/cgroup.c:css_task_iter_advance_css_set
  - kernel/cgroup/cgroup.c:cgroup_file_open
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/cgroup/namespace.c (ffffffff81227877)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:cgroupns_get
  - kernel/cgroup/namespace.c:cgroupns_install
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81228709)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
```
In kernel/utsname.c (ffffffff81236068)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_install
  - kernel/utsname.c:utsns_get
  - kernel/utsname.c:copy_utsname
  - kernel/utsname.c:clone_uts_ns
```
```
In kernel/user_namespace.c (ffffffff81237721)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/user_namespace.c:ns_get_owner
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_get
```
```
In kernel/pid_namespace.c (ffffffff81238f73)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_get_parent
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:pidns_get
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/pid_namespace.c:create_pid_namespace
  - kernel/pid_namespace.c:create_pid_namespace
```
```
In kernel/audit.c (ffffffff8123d39c)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/audit.c:audit_get_tty
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_send_queue
```
```
In kernel/auditfilter.c (ffffffff81241364)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In kernel/audit_watch.c (ffffffff81248fb8)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_tree.c (ffffffff8124bc5a)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_trim_trees
  - kernel/audit_tree.c:tag_chunk
  - kernel/audit_tree.c:create_chunk
  - kernel/audit_tree.c:replace_chunk
```
```
In kernel/hung_task.c (ffffffff8125e082)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
```
```
In kernel/seccomp.c (ffffffff81261f36)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_attach_filter
  - kernel/seccomp.c:seccomp_attach_filter
```
```
In kernel/relay.c (ffffffff81263f24)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_open
  - kernel/relay.c:relay_create_buf
```
```
In kernel/trace/trace.c (ffffffff8127c143)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/trace/trace.c:buffer_pipe_buf_get
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff81292834)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/trace/trace_osnoise.c (ffffffff812967df)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/trace/trace_osnoise.c:timerlat_fd_open
```
```
In kernel/trace/trace_events_user.c (ffffffff812c6f62)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/trace/trace_events_user.c:user_events_ioctl_reg
  - kernel/trace/trace_events_user.c:user_events_ioctl_reg
  - kernel/trace/trace_events_user.c:user_event_reg
  - kernel/trace/trace_events_user.c:update_enable_bit_for
  - kernel/trace/trace_events_user.c:find_user_event
  - kernel/trace/trace_events_user.c:user_event_mm_dup
  - kernel/trace/trace_events_user.c:current_user_event_mm
  - kernel/trace/trace_events_user.c:user_event_enabler_write
```
```
In kernel/trace/bpf_trace.c (ffffffff812c8d29)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_send_signal_common
```
```
In kernel/trace/rethook.c (ffffffff812df089)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/trace/rethook.c:rethook_add_node
```
```
In kernel/bpf/syscall.c (ffffffff812f1b7c)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In kernel/bpf/task_iter.c (ffffffff813246e4)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:init_seq_pidns
  - kernel/bpf/task_iter.c:task_group_seq_get_next
```
```
In kernel/bpf/trampoline.c (ffffffff813373a5)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_lookup
```
```
In kernel/bpf/btf.c (ffffffff8134896e)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_by_fd
  - kernel/bpf/btf.c:btf_parse_kptr
  - kernel/bpf/btf.c:bpf_find_btf_id
  - kernel/bpf/btf.c:bpf_find_btf_id
```
```
In kernel/bpf/dispatcher.c (ffffffff8134ca02)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog
```
```
In kernel/bpf/offload.c (ffffffff8135112c)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_map_offload_info_fill_ns
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill_ns
```
```
In kernel/bpf/cpumask.c (ffffffff8135d5c9)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/bpf/cpumask.c:bpf_cpumask_acquire
```
```
In kernel/events/core.c (ffffffff813758ad)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_context
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_remove_from_owner
  - kernel/events/core.c:find_get_context
  - kernel/events/core.c:find_get_context
  - kernel/events/core.c:alloc_perf_context
```
```
In kernel/events/uprobes.c (ffffffff81383bb1)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/events/uprobes.c:prepare_uretprobe
  - kernel/events/uprobes.c:uprobe_copy_process
  - kernel/events/uprobes.c:uprobe_mmap
  - kernel/events/uprobes.c:uprobe_mmap
  - kernel/events/uprobes.c:alloc_uprobe
  - kernel/events/uprobes.c:__find_uprobe
```
```
In kernel/padata.c (ffffffff813854b9)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_parallel
```
```
In kernel/watch_queue.c (ffffffff81388a5e)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - kernel/watch_queue.c:get_watch_queue
  - kernel/watch_queue.c:add_watch_to_object
  - kernel/watch_queue.c:add_watch_to_object
```
```
In mm/oom_kill.c (ffffffff81397c5e)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - mm/oom_kill.c:out_of_memory
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:oom_evaluate_task
```
```
In mm/backing-dev.c (ffffffff813cbc51)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_get_by_id
  - mm/backing-dev.c:cgwb_create
```
```
In mm/madvise.c (ffffffff814289da)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - mm/madvise.c:madvise_vma_behavior
  - mm/madvise.c:madvise_update_vma
```
```
In mm/page_io.c (ffffffff8142a28d)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage_bdev_sync
```
```
In mm/hugetlb.c (ffffffff8143a27e)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_vm_op_open
```
```
In mm/mempolicy.c (ffffffff8144a94c)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_migrate_pages
```
```
In mm/migrate.c (ffffffff814670b7)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - mm/migrate.c:find_mm_struct
```
```
In mm/memory-tiers.c (ffffffff8146d3af)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - mm/memory-tiers.c:init_node_memory_type
  - mm/memory-tiers.c:set_node_memory_tier
```
```
In mm/huge_memory.c (ffffffff8147856e)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_pid
```
```
In mm/memory-failure.c (ffffffff81495fe4)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - mm/memory-failure.c:__add_to_kill
```
```
In fs/super.c (ffffffff814b2c45)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/super.c:set_bdev_super_fc
  - fs/super.c:alloc_super
```
```
In fs/exec.c (ffffffff814b8787)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/exec.c:would_dump
```
```
In fs/pipe.c (ffffffff814bd417)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/pipe.c:alloc_pipe_info
```
```
In fs/fcntl.c (ffffffff814c96b3)
Location: include/linux/refcount.h:248
Inline: True
```
```
In fs/namespace.c (ffffffff814e71a5)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_get
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:alloc_mnt_ns
  - fs/namespace.c:mnt_init
```
```
In fs/fs_context.c (ffffffff81504340)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/fs_context.c:alloc_fs_context
  - fs/fs_context.c:alloc_fs_context
  - fs/fs_context.c:alloc_fs_context
  - fs/fs_context.c:alloc_fs_context
```
```
In fs/mnt_idmapping.c (ffffffff81506d48)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/mnt_idmapping.c:alloc_mnt_idmap
```
```
In fs/proc_namespace.c (ffffffff8150f6b5)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/notify/group.c (ffffffff81513e6a)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_get_group
```
```
In fs/notify/mark.c (ffffffff81514ad4)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_get_mark
```
```
In fs/notify/fanotify/fanotify.c (ffffffff8151968f)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/eventpoll.c (ffffffff8151e784)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_create
  - fs/eventpoll.c:ep_insert
```
```
In fs/eventfd.c (ffffffff81523445)
Location: include/linux/refcount.h:248
Inline: True
```
```
In fs/userfaultfd.c (ffffffff81524980)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_unmap_prep
  - fs/userfaultfd.c:userfaultfd_remove
  - fs/userfaultfd.c:mremap_userfaultfd_prep
  - fs/userfaultfd.c:dup_userfaultfd
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/crypto/keysetup.c (ffffffff81537d4a)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_setup_encryption_info
```
```
In fs/crypto/keysetup_v1.c (ffffffff81538593)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
```
```
In fs/posix_acl.c (ffffffff8154dd7b)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/posix_acl.c:set_cached_acl
```
```
In fs/proc/root.c (ffffffff8156a133)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/proc/root.c:proc_init_fs_context
  - fs/proc/root.c:proc_init_fs_context
  - fs/proc/root.c:proc_fill_super
  - fs/proc/root.c:proc_fill_super
```
```
In fs/proc/base.c (ffffffff815705ea)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:next_tgid
  - fs/proc/base.c:proc_pid_lookup
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_open
```
```
In fs/proc/generic.c (ffffffff815724b9)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_readdir_de
  - fs/proc/generic.c:proc_lookup_de
```
```
In fs/proc/array.c (ffffffff81572f97)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
```
```
In fs/proc/proc_net.c (ffffffff8157c312)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_task_net
  - fs/proc/proc_net.c:bpf_iter_init_seq_net
```
```
In fs/sysfs/mount.c (ffffffff8158775b)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/sysfs/mount.c:sysfs_init_fs_context
```
```
In fs/configfs/item.c (ffffffff8158d805)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/configfs/item.c:config_group_find_item
```
```
In fs/ext4/page-io.c (ffffffff815dabc4)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_folio
```
```
In fs/hugetlbfs/inode.c (ffffffff8162e8b9)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlb_unmap_file_folio
```
```
In fs/ecryptfs/keystore.c (ffffffff81648d59)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
```
```
In fs/fuse/dev.c (ffffffff816528d8)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:fuse_simple_request
```
```
In fs/fuse/file.c (ffffffff8165f9b7)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_writepages_send
  - fs/fuse/file.c:fuse_write_inode
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_readahead
  - fs/fuse/file.c:fuse_async_req_send
```
```
In fs/fuse/inode.c (ffffffff81664c7f)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_fill_super_common
  - fs/fuse/inode.c:fuse_get_tree_submount
  - fs/fuse/inode.c:fuse_fill_super_submount
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_conn_init
```
```
In fs/fuse/dax.c (ffffffff8166a905)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_iomap_begin
```
```
In ipc/util.c (ffffffff816748ab)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_open
  - ipc/util.c:sysvipc_proc_open
```
```
In ipc/msg.c (ffffffff816780a2)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:expunge_all
```
```
In ipc/sem.c (ffffffff8167d90a)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:copy_semundo
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:update_queue
  - ipc/sem.c:wake_const_ops
  - ipc/sem.c:perform_atomic_semop
  - ipc/sem.c:perform_atomic_semop_slow
```
```
In ipc/shm.c (ffffffff8168050b)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:newseg
  - ipc/shm.c:__shm_close
  - ipc/shm.c:__shm_open
```
```
In ipc/mqueue.c (ffffffff816851b8)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - ipc/mqueue.c:mq_init_ns
  - ipc/mqueue.c:mq_init_ns
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_init_fs_context
  - ipc/mqueue.c:mqueue_init_fs_context
```
```
In ipc/namespace.c (ffffffff8168590f)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - ipc/namespace.c:ipcns_install
  - ipc/namespace.c:ipcns_get
  - ipc/namespace.c:get_ipc_ns_exported
  - ipc/namespace.c:copy_ipcs
```
```
In security/keys/key.c (ffffffff816878ea)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_user_lookup
```
```
In security/keys/keyring.c (ffffffff81689678)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_gc_select_iterator
  - security/keys/keyring.c:__key_link
  - security/keys/keyring.c:find_key_to_update
  - security/keys/keyring.c:keyring_search_rcu
```
```
In security/keys/keyctl.c (ffffffff8168acc7)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/keys/keyctl.c:get_instantiation_keyring
```
```
In security/keys/process_keys.c (ffffffff8168eeec)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:install_session_keyring_to_cred
```
```
In security/keys/request_key.c (ffffffff8168fe17)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:cache_requested_key
  - security/keys/request_key.c:check_cached_key
```
```
In security/keys/request_key_auth.c (ffffffff816908f5)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
```
```
In security/apparmor/apparmorfs.c (ffffffff816f8068)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:policy_get_link
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
  - security/apparmor/apparmorfs.c:multi_transaction_read
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
```
```
In security/apparmor/audit.c (ffffffff816fa9ed)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/apparmor/audit.c:aa_audit_cache_insert
  - security/apparmor/audit.c:aa_audit_cache_find
  - security/apparmor/audit.c:aa_dup_audit_data
  - security/apparmor/audit.c:aa_dup_audit_data
```
```
In security/apparmor/capability.c (ffffffff816fad02)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/apparmor/capability.c:audit_caps
```
```
In security/apparmor/task.c (ffffffff816fba71)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_set_current_onexec
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_get_task_label
```
```
In security/apparmor/domain.c (ffffffff8170454a)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:find_attach
  - security/apparmor/domain.c:find_attach
```
```
In security/apparmor/policy.c (ffffffff81708625)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:aa_new_learning_profile
  - security/apparmor/policy.c:aa_alloc_null
  - security/apparmor/policy.c:aa_alloc_null
  - security/apparmor/policy.c:aa_alloc_null
  - security/apparmor/policy.c:aa_alloc_null
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_alloc_profile
  - security/apparmor/policy.c:__add_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff81709671)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:do_loaddata_free
```
```
In security/apparmor/procattr.c (ffffffff8170c3e4)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff836f8a6e)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_sock_graft
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_current_getsecid_subj
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_inode_init_security
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_task_alloc
  - security/apparmor/lsm.c:apparmor_task_alloc
  - security/apparmor/lsm.c:apparmor_task_alloc
  - security/apparmor/lsm.c:apparmor_cred_transfer
  - security/apparmor/lsm.c:apparmor_cred_prepare
```
```
In security/apparmor/resource.c (ffffffff817148c2)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff81716f1b)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:aa_file_perm
```
```
In security/apparmor/policy_ns.c (ffffffff836f8fb4)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_alloc_root_ns
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:__aa_find_or_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:aa_lookupn_ns
  - security/apparmor/policy_ns.c:aa_find_ns
```
```
In security/apparmor/label.c (ffffffff8171a582)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:__label_insert
  - security/apparmor/label.c:__label_insert
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/label.c:__proxy_share
  - security/apparmor/label.c:__aa_proxy_redirect
  - security/apparmor/label.c:aa_alloc_proxy
  - security/apparmor/label.c:aa_get_current_ns
```
```
In security/apparmor/mount.c (ffffffff8171f150)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:build_pivotroot
```
```
In security/apparmor/net.c (0)
Location: include/linux/refcount.h:248
Inline: True
```
```
In security/apparmor/af_unix.c (ffffffff81722f90)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
```
```
In security/apparmor/notify.c (ffffffff817236cc)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/apparmor/notify.c:build_v3_unotif
  - security/apparmor/notify.c:aa_clone_ruleset
  - security/apparmor/notify.c:aa_clone_ruleset
  - security/apparmor/notify.c:aa_do_notification
  - security/apparmor/notify.c:aa_do_notification
  - security/apparmor/notify.c:aa_do_notification
  - security/apparmor/notify.c:aa_new_listener
  - security/apparmor/notify.c:aa_register_listener_proxy
  - security/apparmor/notify.c:aa_get_current_ns
```
```
In security/yama/yama_lsm.c (ffffffff817266a2)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_task_prctl
  - security/yama/yama_lsm.c:report_access
  - security/yama/yama_lsm.c:report_access
```
```
In security/landlock/syscalls.c (ffffffff817295d3)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/landlock/syscalls.c:get_ruleset_from_fd
```
```
In security/landlock/ruleset.c (ffffffff8172a3bf)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/landlock/ruleset.c:inherit_ruleset
  - security/landlock/ruleset.c:create_rule
```
```
In security/landlock/cred.c (ffffffff8172aa3c)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - security/landlock/cred.c:hook_cred_prepare
```
```
In crypto/api.c (ffffffff8173df16)
Location: include/linux/refcount.h:248
Inline: True
```
```
In crypto/algapi.c (ffffffff8173fe78)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_spawn_alg
```
```
In crypto/algboss.c (ffffffff8174c384)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - crypto/algboss.c:cryptomgr_schedule_probe
```
```
In crypto/asymmetric_keys/restrict.c (ffffffff8175fbd8)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
```
```
In block/blk-core.c (ffffffff81770c28)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - block/blk-core.c:blk_get_queue
```
```
In block/blk-cgroup.c (ffffffff8179fae9)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_online
```
```
In io_uring/io_uring.c (ffffffff817cd8c9)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - io_uring/io_uring.c:__io_uring_register
  - io_uring/io_uring.c:io_register_iowq_max_workers
  - io_uring/io_uring.c:io_uring_create
  - io_uring/io_uring.c:io_uring_create
```
```
In io_uring/sqpoll.c (ffffffff817db1cd)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - io_uring/sqpoll.c:io_get_sq_data
```
```
In io_uring/rsrc.c (ffffffff817e2717)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - io_uring/rsrc.c:__io_scm_file_account
```
```
In io_uring/io-wq.c (ffffffff817e8830)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_create
  - io_uring/io-wq.c:io_wq_create
```
```
In rust/helpers.c (ffffffff81805c7a)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - rust/helpers.c:rust_helper_get_task_struct
  - rust/helpers.c:rust_helper_refcount_inc
```
```
In lib/cpu_rmap.c (ffffffff818d3935)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
```
```
In drivers/pinctrl/core.c (ffffffff818eea1f)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_get
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8195b6c8)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff8197b55e)
Location: include/linux/refcount.h:248
Inline: True
```
```
In drivers/acpi/ec.c (ffffffff819aedaa)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_submit_query
```
```
In drivers/acpi/thermal.c (ffffffff81a2228b)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/acpi/thermal.c:acpi_thermal_check_fn
```
```
In drivers/clk/clk.c (ffffffff81a46cd9)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_hw_create_clk
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff81a7584a)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
```
```
In drivers/reset/core.c (ffffffff81a908e7)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/reset/core.c:__reset_control_get_internal
```
```
In drivers/tty/tty_io.c (ffffffff81a96abf)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:__do_SAK
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:tty_lookup_driver
  - drivers/tty/tty_io.c:tty_lookup_driver
  - drivers/tty/tty_io.c:tty_lookup_driver
  - drivers/tty/tty_io.c:tty_find_polling_driver
```
```
In drivers/tty/tty_port.c (ffffffff81aa033f)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_tty_get
```
```
In drivers/tty/tty_mutex.c (ffffffff81aa0d86)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/tty_mutex.c:tty_lock
```
```
In drivers/tty/tty_ldsem.c (ffffffff8215880d)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:down_read_failed
```
```
In drivers/tty/tty_jobctrl.c (ffffffff81aa2944)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_get_pgrp
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:get_current_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
```
```
In drivers/tty/pty.c (ffffffff81aa3c91)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/tty/pty.c:pty_common_install
  - drivers/tty/pty.c:pty_common_install
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff81aa7073)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_k_ioctl
```
```
In drivers/char/virtio_console.c (ffffffff81ae56a8)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:port_fops_open
```
```
In drivers/char/hw_random/core.c (ffffffff81ae7f9f)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:hwrng_register
  - drivers/char/hw_random/core.c:hwrng_fillfn
```
```
In drivers/connector/connector.c (ffffffff81b2b4e0)
Location: include/linux/refcount.h:248
Inline: True
```
```
In drivers/base/core.c (ffffffff81b334cb)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/power/runtime.c (ffffffff81b4f7a3)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_get_suppliers
```
```
In drivers/base/firmware_loader/main.c (ffffffff81b5ff8c)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:assign_fw
  - drivers/base/firmware_loader/main.c:alloc_lookup_fw_priv
```
```
In drivers/nvdimm/core.c (ffffffff81ba24ab)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81ba6cca)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:get_ndd
```
```
In drivers/dax/bus.c (ffffffff81bbbc02)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/dax/bus.c:devm_create_dev_dax
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81bbd8ec)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll_add_cb
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81bbf49b)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff81bc055b)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff81bc0ff0)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_set_deadline
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_find_seqno
```
```
In drivers/dma-buf/dma-fence-unwrap.c (ffffffff81bc16da)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-unwrap.c:__dma_fence_unwrap_merge
  - drivers/dma-buf/dma-fence-unwrap.c:dma_fence_unwrap_first
```
```
In drivers/dma-buf/dma-resv.c (ffffffff81bc298e)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_replace_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_add_fence
```
```
In drivers/dma-buf/sync_file.c (ffffffff81bc48ed)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_get_fence
  - drivers/dma-buf/sync_file.c:sync_file_create
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81bc5b9e)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_pt_create
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
```
```
In drivers/scsi/scsi_scan.c (ffffffff81bd76cd)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff81bdc9f0)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
```
```
In drivers/scsi/sg.c (ffffffff81bf5af4)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_sfp
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/ata/libata-core.c (ffffffff81c03e9a)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_get
```
```
In drivers/net/phy/phy_device.c (ffffffff81c3a6bb)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_package_join
```
```
In drivers/net/phy/sfp-bus.c (ffffffff81c41365)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_add_upstream
  - drivers/net/phy/sfp-bus.c:sfp_bus_get
```
```
In drivers/net/pse-pd/pse_core.c (0)
Location: include/linux/refcount.h:248
Inline: True
```
```
In drivers/net/tun.c (ffffffff81c47fbc)
Location: include/linux/refcount.h:248
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81c621d1)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_init
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
```
In drivers/net/xen-netfront.c (ffffffff81c6a12a)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_make_one_txreq
```
```
In drivers/usb/core/hub.c (ffffffff81c7bc51)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/hcd.c (ffffffff81c84b85)
Location: include/linux/refcount.h:248
Inline: True
```
```
In drivers/usb/core/urb.c (ffffffff81c88a55)
Location: include/linux/refcount.h:248
Inline: True
```
```
In drivers/usb/core/message.c (ffffffff81c8ccc5)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_set_configuration
```
```
In drivers/usb/core/file.c (ffffffff81c92854)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_register_dev
```
```
In drivers/usb/core/devio.c (ffffffff81c9885b)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:async_completed
```
```
In drivers/md/dm.c (ffffffff81d793f5)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_get_table_device
```
```
In drivers/md/dm-table.c (ffffffff82148840)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_get_device
```
```
In drivers/opp/core.c (ffffffff81d91f73)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_adjust_voltage
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_xlate_required_opp
  - drivers/opp/core.c:_set_opp
  - drivers/opp/core.c:_set_opp
  - drivers/opp/core.c:_opp_table_find_key
  - drivers/opp/core.c:_find_opp_table_unlocked
```
```
In drivers/nvmem/core.c (ffffffff81df99f6)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - drivers/nvmem/core.c:__nvmem_device_get
```
```
In net/core/sock.c (ffffffff81e0b082)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sk_getsockopt
```
```
In net/core/skbuff.c (ffffffff81e13af3)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_ext_maybe_cow
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:msg_zerocopy_realloc
  - net/core/skbuff.c:msg_zerocopy_realloc
  - net/core/skbuff.c:mm_account_pinned_pages
  - net/core/skbuff.c:__copy_skb_header
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/core/datagram.c (ffffffff81e20a4d)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_from_queue
```
```
In net/core/scm.c (ffffffff81e2236a)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
  - net/core/scm.c:__scm_send
```
```
In net/core/net_namespace.c (ffffffff81e25197)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_get
  - net/core/net_namespace.c:get_net_ns_by_pid
  - net/core/net_namespace.c:get_net_ns_by_fd
  - net/core/net_namespace.c:get_net_ns
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:copy_net_ns
```
```
In net/core/dev.c (ffffffff81e32695)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/neighbour.c (ffffffff81e4b11d)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_alloc
  - net/core/neighbour.c:neigh_add_timer
```
```
In net/core/rtnetlink.c (ffffffff81e507b5)
Location: include/linux/refcount.h:248
Inline: True
```
```
In net/core/flow_offload.c (ffffffff81e7a9a3)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_dev_register
```
```
In net/core/net-sysfs.c (ffffffff81e7eb8e)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/core/net-sysfs.c:net_grab_current_ns
```
```
In net/core/page_pool.c (ffffffff81e84323)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_use_xdp_mem
```
```
In net/core/netpoll.c (ffffffff81e85d18)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_setup
```
```
In net/core/skmsg.c (ffffffff81ea11b5)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_psock_init
```
```
In net/core/sock_map.c (ffffffff81ea597c)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_map_free
```
```
In net/sched/sch_generic.c (ffffffff81eae079)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/sched/sch_generic.c:attach_default_qdiscs
  - net/sched/sch_generic.c:attach_default_qdiscs
```
```
In net/sched/sch_api.c (ffffffff81eb43cd)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
```
```
In net/sched/cls_api.c (ffffffff81eb6e00)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_chain_tp_find
  - net/sched/cls_api.c:tcf_chain_tp_insert_unique
  - net/sched/cls_api.c:__tcf_block_find
  - net/sched/cls_api.c:__tcf_get_next_proto
```
```
In net/sched/act_api.c (ffffffff81ebd736)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_idr_check_alloc
  - net/sched/act_api.c:tcf_idr_search
```
```
In net/netlink/af_netlink.c (ffffffff81ec8c29)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_getsockbyfilp
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/ipv4/route.c (ffffffff81eee0d5)
Location: include/linux/refcount.h:248
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff81ef5938)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/ip_output.c (ffffffff81efad04)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/ip_sockglue.c (ffffffff81efe4ae)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_ra_control
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81f04216)
Location: include/linux/refcount.h:248
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81f06c46)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_complete_hashdance
```
```
In net/ipv4/tcp.c (ffffffff81f109f0)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_abort
  - net/ipv4/tcp.c:__tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff81f1494c)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (ffffffff81f254f3)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_tsq_handler
```
```
In net/ipv4/tcp_timer.c (ffffffff81f29863)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f2f0c2)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
```
```
In net/ipv4/raw.c (ffffffff81f3bc1f)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_hash_sk
```
```
In net/ipv4/udp.c (ffffffff81f403b9)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv4/udp.c:bpf_iter_udp_batch
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/arp.c (ffffffff81f4a08c)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_constructor
```
```
In net/ipv4/devinet.c (ffffffff81f52764)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
```
```
In net/ipv4/igmp.c (ffffffff81f59902)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv4/igmp.c:____ip_mc_inc_group
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_ifc_event
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
```
```
In net/ipv4/fib_semantics.c (ffffffff81f624d0)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/fib_trie.c (ffffffff81f67a04)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv4/inet_fragment.c (ffffffff81f69dbc)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:fqdir_init
```
```
In net/ipv4/ping.c (ffffffff81f6c548)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_get_port
```
```
In net/ipv4/nexthop.c (ffffffff81f76153)
Location: include/linux/refcount.h:248
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81f89318)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_check
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f918ac)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:__xfrm_policy_link
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
```
```
In net/xfrm/xfrm_state.c (ffffffff81f9dbcd)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:xfrm_state_lookup_byspi
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
```
```
In net/xfrm/xfrm_output.c (ffffffff81fa43bf)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
```
```
In net/unix/af_unix.c (ffffffff81faaece)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/unix/af_unix.c:bpf_iter_unix_batch
  - net/unix/af_unix.c:bpf_iter_unix_batch
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:__unix_dgram_recvmsg
  - net/unix/af_unix.c:queue_oob
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_getname
  - net/unix/af_unix.c:unix_getname
  - net/unix/af_unix.c:unix_socketpair
  - net/unix/af_unix.c:unix_socketpair
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:init_peercred
  - net/unix/af_unix.c:__unix_set_addr_hash
```
```
In net/ipv6/anycast.c (ffffffff81fb381a)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/ip6_output.c (ffffffff81fb5a18)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/addrconf.c (ffffffff81fca423)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_set_iftoken
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_kick
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_permanent_addr
  - net/ipv6/addrconf.c:addrconf_add_linklocal
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/route.c (ffffffff83737651)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_init_special_entries
  - net/ipv6/route.c:ip6_route_init_special_entries
  - net/ipv6/route.c:ip6_route_init_special_entries
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_rt_copy_init
  - net/ipv6/route.c:ip6_rt_copy_init
  - net/ipv6/route.c:ip6_dst_ifdown
```
```
In net/ipv6/ip6_fib.c (ffffffff81fde32a)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_purge_rt
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81fdfba9)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ip6_ra_control
```
```
In net/ipv6/ndisc.c (ffffffff81fe4051)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change
  - net/ipv6/ndisc.c:ndisc_netdev_event
  - net/ipv6/ndisc.c:ndisc_netdev_event
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_unsol_na
  - net/ipv6/ndisc.c:ndisc_constructor
  - net/ipv6/ndisc.c:ndisc_constructor
```
```
In net/ipv6/mcast.c (ffffffff81ff5cd1)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_ifc_work
  - net/ipv6/mcast.c:mld_dad_work
  - net/ipv6/mcast.c:ipv6_mc_dad_complete
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:igmp6_group_dropped
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffea92)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_route_req
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/xfrm6_policy.c (ffffffff8201180f)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
```
```
In net/ipv6/syncookies.c (ffffffff82016510)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/calipso.c (ffffffff8201740f)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_cache_add
  - net/ipv6/calipso.c:calipso_cache_check
```
```
In net/packet/af_packet.c (ffffffff82028374)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/devlink/leftover.c (ffffffff8203e704)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/devlink/leftover.c:devl_rate_leaf_create
  - net/devlink/leftover.c:devlink_nl_rate_parent_node_set
```
```
In net/ncsi/ncsi-cmd.c (ffffffff82060c7a)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
```
In net/ncsi/ncsi-netlink.c (ffffffff82067dfa)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
```
```
In net/xdp/xsk.c (ffffffff8206ab66)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
```
```
In net/xdp/xdp_umem.c (ffffffff8206c635)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
  - net/xdp/xdp_umem.c:xdp_get_umem
```
```
In net/xdp/xsk_buff_pool.c (ffffffff8206dc91)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_dma_map
  - net/xdp/xsk_buff_pool.c:xp_get_pool
```
```
In net/mptcp/protocol.c (ffffffff8207854c)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_finish_join
  - net/mptcp/protocol.c:mptcp_finish_join
  - net/mptcp/protocol.c:mptcp_sk_clone_init
  - net/mptcp/protocol.c:__mptcp_close
  - net/mptcp/protocol.c:__mptcp_subflow_push_pending
```
```
In net/mptcp/subflow.c (ffffffff8207c957)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_queue_clean
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
  - net/mptcp/subflow.c:__mptcp_subflow_connect
  - net/mptcp/subflow.c:mptcp_subflow_reset
```
```
In net/mptcp/options.c (ffffffff8207dc8c)
Location: include/linux/refcount.h:248
Inline: True
```
```
In net/mctp/af_mctp.c (ffffffff8208d5dc)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_sk_hash
```
```
In net/mctp/device.c (ffffffff8208ec0b)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_dev_set_key
```
```
In net/mctp/route.c (ffffffff8209146f)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_local_output
  - net/mctp/route.c:mctp_alloc_local_tag
  - net/mctp/route.c:mctp_key_add
  - net/mctp/route.c:mctp_key_alloc
```
```
In net/handshake/request.c (ffffffff820933b3)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - net/handshake/request.c:handshake_req_submit
```
```
In lib/klist.c (ffffffff820a1c2b)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - lib/klist.c:klist_next
  - lib/klist.c:klist_prev
```
```
In lib/kobject.c (ffffffff820a27d7)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - lib/kobject.c:kobject_get
```
```
In lib/kobject_uevent.c (ffffffff820a45bb)
Location: include/linux/refcount.h:248
Inline: True
Inline callers:
  - lib/kobject_uevent.c:kobject_uevent_net_broadcast
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
In init/main.c (ffffffff838b0db2)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In arch/x86/kernel/ioport.c (ffffffff81058e20)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:io_bitmap_share
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81085998)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8108ec30)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_init_fs_context
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81099ed3)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_mm_add
```
```
In kernel/fork.c (ffffffff810fdd8f)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - kernel/fork.c:kernel_clone
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:__pidfd_prepare
  - kernel/fork.c:copy_sighand
  - kernel/fork.c:mm_init
  - kernel/fork.c:vm_area_dup
```
```
In kernel/exit.c (ffffffff81105f60)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_stopped
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:make_task_dead
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:release_task
```
```
In kernel/user.c (ffffffff81112c18)
Location: include/linux/refcount.h:237
Inline: True
```
```
In kernel/sys.c (ffffffff8112142c)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_prlimit64
```
```
In kernel/pid.c (ffffffff8113066a)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - kernel/pid.c:pidfd_getfd
  - kernel/pid.c:__ia32_sys_pidfd_open
  - kernel/pid.c:__x64_sys_pidfd_open
  - kernel/pid.c:pidfd_get_task
  - kernel/pid.c:pidfd_get_pid
  - kernel/pid.c:get_task_pid
  - kernel/pid.c:find_get_task_by_vpid
  - kernel/pid.c:alloc_pid
```
```
In kernel/kthread.c (ffffffff81134ffa)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_stop
```
```
In kernel/nsproxy.c (ffffffff8113c400)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - kernel/nsproxy.c:validate_nsset
  - kernel/nsproxy.c:validate_nsset
  - kernel/nsproxy.c:validate_nsset
  - kernel/nsproxy.c:copy_namespaces
  - kernel/nsproxy.c:create_new_namespaces
```
```
In kernel/cred.c (ffffffff8113f06b)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
```
```
In kernel/smpboot.c (ffffffff81141dba)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - kernel/smpboot.c:__smpboot_create_thread
```
```
In kernel/ucount.c (ffffffff811428ce)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - kernel/ucount.c:alloc_ucounts
```
```
In kernel/groups.c (ffffffff8114379b)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - kernel/groups.c:set_groups
```
```
In kernel/sched/core.c (ffffffff8114fb89)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - kernel/sched/core.c:balance_push
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:do_sched_setscheduler
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:wake_q_add
```
```
In kernel/sched/fair.c (ffffffff81163407)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_assign
```
```
In kernel/sched/build_policy.c (ffffffff81177703)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:pull_dl_task
  - kernel/sched/build_policy.c:push_dl_task
  - kernel/sched/build_policy.c:start_dl_timer
  - kernel/sched/build_policy.c:task_non_contending
  - kernel/sched/build_policy.c:pull_rt_task
  - kernel/sched/build_policy.c:push_rt_task
  - kernel/sched/build_policy.c:push_rt_task
```
```
In kernel/sched/build_utility.c (ffffffff8119b940)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:proc_sched_autogroup_show_task
  - kernel/sched/build_utility.c:proc_sched_autogroup_show_task
  - kernel/sched/build_utility.c:proc_sched_autogroup_set_nice
  - kernel/sched/build_utility.c:proc_sched_autogroup_set_nice
  - kernel/sched/build_utility.c:sched_autogroup_fork
  - kernel/sched/build_utility.c:sched_autogroup_fork
  - kernel/sched/build_utility.c:sched_autogroup_create_attach
  - kernel/sched/build_utility.c:autogroup_move_group
  - kernel/sched/build_utility.c:sched_core_share_pid
  - kernel/sched/build_utility.c:__sched_core_set
  - kernel/sched/build_utility.c:sched_core_fork
```
```
In kernel/locking/rwsem.c (ffffffff8119c7bc)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
```
```
In kernel/locking/percpu-rwsem.c (ffffffff8119d209)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wake_function
```
```
In kernel/locking/rtmutex_api.c (ffffffff8223ac2f)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_pi
  - kernel/locking/rtmutex_api.c:remove_waiter
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
```
```
In kernel/irq/manage.c (ffffffff811b7cbb)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - kernel/irq/manage.c:setup_irq_thread
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/rcu/update.c (ffffffff811cde7d)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_trace_pregp_step
  - kernel/rcu/update.c:trc_inspect_reader
```
```
In kernel/rcu/tree.c (ffffffff811d32bc)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_print_task_stall
```
```
In kernel/kcmp.c (ffffffff811fa914)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
```
```
In kernel/time/posix-timers.c (ffffffff81210b07)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8121352e)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_wait_running
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_create
```
```
In kernel/time/namespace.c (ffffffff8121e73f)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - kernel/time/namespace.c:proc_timens_set_offset
  - kernel/time/namespace.c:proc_timens_show_offsets
  - kernel/time/namespace.c:timens_on_fork
  - kernel/time/namespace.c:timens_install
  - kernel/time/namespace.c:timens_install
  - kernel/time/namespace.c:timens_get
  - kernel/time/namespace.c:copy_time_ns
  - kernel/time/namespace.c:copy_time_ns
```
```
In kernel/futex/waitwake.c (ffffffff812238b3)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - kernel/futex/waitwake.c:futex_wake_mark
```
```
In kernel/cgroup/cgroup.c (ffffffff8123d50d)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:css_task_iter_next
  - kernel/cgroup/cgroup.c:css_task_iter_advance_css_set
  - kernel/cgroup/cgroup.c:css_task_iter_advance_css_set
  - kernel/cgroup/cgroup.c:cgroup_file_open
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/cgroup/namespace.c (ffffffff8123f687)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:cgroupns_get
  - kernel/cgroup/namespace.c:cgroupns_install
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8124051d)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
```
In kernel/utsname.c (ffffffff8124fce8)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_install
  - kernel/utsname.c:utsns_get
  - kernel/utsname.c:copy_utsname
  - kernel/utsname.c:clone_uts_ns
```
```
In kernel/user_namespace.c (ffffffff81250f51)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - kernel/user_namespace.c:ns_get_owner
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_get
```
```
In kernel/pid_namespace.c (ffffffff81252c43)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_get_parent
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:pidns_get
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/pid_namespace.c:create_pid_namespace
  - kernel/pid_namespace.c:create_pid_namespace
```
```
In kernel/audit.c (ffffffff812572cc)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - kernel/audit.c:audit_get_tty
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_send_queue
  - kernel/audit.c:auditd_set
  - kernel/audit.c:auditd_set
```
```
In kernel/auditfilter.c (ffffffff8125b193)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In kernel/audit_watch.c (ffffffff81262e48)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_update_watch
```
```
In kernel/audit_tree.c (ffffffff81265b5a)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_trim_trees
  - kernel/audit_tree.c:tag_chunk
  - kernel/audit_tree.c:create_chunk
  - kernel/audit_tree.c:replace_chunk
```
```
In kernel/hung_task.c (ffffffff81277fc2)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
```
```
In kernel/seccomp.c (ffffffff8127c181)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_attach_filter
  - kernel/seccomp.c:seccomp_attach_filter
```
```
In kernel/relay.c (ffffffff8127dd14)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_open
  - kernel/relay.c:relay_create_buf
```
```
In kernel/trace/trace.c (ffffffff81296e33)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - kernel/trace/trace.c:buffer_pipe_buf_get
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff812adf1a)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In kernel/trace/trace_osnoise.c (ffffffff812b1ddf)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - kernel/trace/trace_osnoise.c:timerlat_fd_open
```
```
In kernel/trace/trace_events_user.c (ffffffff812e3937)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - kernel/trace/trace_events_user.c:user_events_ioctl_reg
  - kernel/trace/trace_events_user.c:user_event_reg
  - kernel/trace/trace_events_user.c:update_enable_bit_for
  - kernel/trace/trace_events_user.c:find_user_event
  - kernel/trace/trace_events_user.c:user_event_enabler_create
  - kernel/trace/trace_events_user.c:user_event_mm_dup
  - kernel/trace/trace_events_user.c:current_user_event_mm
  - kernel/trace/trace_events_user.c:user_event_enabler_write
```
```
In kernel/trace/bpf_trace.c (ffffffff812e5cf9)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_send_signal_common
```
```
In kernel/bpf/syscall.c (ffffffff813109ee)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In kernel/bpf/task_iter.c (ffffffff8134977e)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:bpf_iter_task_vma_new
  - kernel/bpf/task_iter.c:init_seq_pidns
  - kernel/bpf/task_iter.c:task_seq_get_next
```
```
In kernel/bpf/trampoline.c (ffffffff8135d225)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_lookup
```
```
In kernel/bpf/btf.c (ffffffff8136f09e)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_by_fd
  - kernel/bpf/btf.c:btf_parse_kptr
  - kernel/bpf/btf.c:bpf_find_btf_id
  - kernel/bpf/btf.c:bpf_find_btf_id
```
```
In kernel/bpf/dispatcher.c (ffffffff81373f36)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog
```
```
In kernel/bpf/offload.c (ffffffff8137858c)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_map_offload_info_fill_ns
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill_ns
```
```
In kernel/bpf/cpumask.c (ffffffff81386329)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - kernel/bpf/cpumask.c:bpf_cpumask_acquire
```
```
In kernel/events/core.c (ffffffff8139ebdd)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_context
  - kernel/events/core.c:__perf_pmu_install_event
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_remove_from_owner
  - kernel/events/core.c:find_get_context
  - kernel/events/core.c:find_get_context
  - kernel/events/core.c:alloc_perf_context
```
```
In kernel/events/uprobes.c (ffffffff813ad02a)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - kernel/events/uprobes.c:prepare_uretprobe
  - kernel/events/uprobes.c:uprobe_copy_process
  - kernel/events/uprobes.c:uprobe_mmap
  - kernel/events/uprobes.c:uprobe_mmap
  - kernel/events/uprobes.c:alloc_uprobe
  - kernel/events/uprobes.c:__find_uprobe
```
```
In kernel/padata.c (ffffffff813ae859)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_parallel
```
```
In kernel/watch_queue.c (ffffffff813b24be)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - kernel/watch_queue.c:get_watch_queue
  - kernel/watch_queue.c:add_watch_to_object
  - kernel/watch_queue.c:add_watch_to_object
```
```
In mm/oom_kill.c (ffffffff813c1a8a)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - mm/oom_kill.c:out_of_memory
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:oom_evaluate_task
```
```
In mm/backing-dev.c (ffffffff813f65c1)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_get_by_id
  - mm/backing-dev.c:cgwb_create
```
```
In mm/madvise.c (ffffffff8146220a)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - mm/madvise.c:madvise_vma_behavior
  - mm/madvise.c:madvise_update_vma
```
```
In mm/page_io.c (ffffffff81463653)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - mm/page_io.c:swap_read_folio_bdev_sync
```
```
In mm/hugetlb.c (ffffffff8147488e)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_vm_op_open
```
```
In mm/mempolicy.c (ffffffff8148438b)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_migrate_pages
```
```
In mm/migrate.c (ffffffff814962f7)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - mm/migrate.c:find_mm_struct
```
```
In mm/memory-tiers.c (ffffffff8149c51f)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - mm/memory-tiers.c:init_node_memory_type
  - mm/memory-tiers.c:set_node_memory_tier
```
```
In mm/huge_memory.c (ffffffff814a7c9e)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_pid
```
```
In mm/memory-failure.c (ffffffff814c5690)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - mm/memory-failure.c:__add_to_kill
```
```
In fs/super.c (ffffffff814e40ed)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - fs/super.c:setup_bdev_super
  - fs/super.c:alloc_super
```
```
In fs/exec.c (ffffffff814eac97)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - fs/exec.c:would_dump
```
```
In fs/pipe.c (ffffffff814ef8b7)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - fs/pipe.c:alloc_pipe_info
```
```
In fs/fcntl.c (ffffffff814fbf73)
Location: include/linux/refcount.h:237
Inline: True
```
```
In fs/namespace.c (ffffffff8151b035)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_get
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:alloc_mnt_ns
  - fs/namespace.c:mnt_init
```
```
In fs/fs_context.c (ffffffff81539002)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - fs/fs_context.c:alloc_fs_context
  - fs/fs_context.c:alloc_fs_context
  - fs/fs_context.c:alloc_fs_context
  - fs/fs_context.c:alloc_fs_context
```
```
In fs/mnt_idmapping.c (ffffffff8153ba59)
Location: include/linux/refcount.h:237
Inline: True
```
```
In fs/proc_namespace.c (ffffffff81543bb5)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/notify/group.c (ffffffff8154833a)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_get_group
```
```
In fs/notify/mark.c (ffffffff81548eb4)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_get_mark
```
```
In fs/notify/fanotify/fanotify.c (ffffffff8154da6f)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/eventpoll.c (ffffffff81552e25)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_create
  - fs/eventpoll.c:ep_insert
```
```
In fs/eventfd.c (ffffffff81557b75)
Location: include/linux/refcount.h:237
Inline: True
```
```
In fs/userfaultfd.c (ffffffff8155b470)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_unmap_prep
  - fs/userfaultfd.c:userfaultfd_remove
  - fs/userfaultfd.c:mremap_userfaultfd_prep
  - fs/userfaultfd.c:dup_userfaultfd
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/crypto/keysetup.c (ffffffff8156ce99)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_setup_encryption_info
```
```
In fs/crypto/keysetup_v1.c (ffffffff8156d6e3)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
```
```
In fs/posix_acl.c (ffffffff81583bcb)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - fs/posix_acl.c:set_cached_acl
```
```
In fs/proc/root.c (ffffffff815a27b2)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - fs/proc/root.c:proc_init_fs_context
  - fs/proc/root.c:proc_init_fs_context
  - fs/proc/root.c:proc_fill_super
  - fs/proc/root.c:proc_fill_super
```
```
In fs/proc/base.c (ffffffff815a90ac)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:next_tgid
  - fs/proc/base.c:proc_pid_lookup
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_open
```
```
In fs/proc/generic.c (ffffffff815aae69)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - fs/proc/generic.c:proc_readdir_de
  - fs/proc/generic.c:proc_lookup_de
```
```
In fs/proc/array.c (ffffffff815abec7)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - fs/proc/array.c:get_children_pid
```
```
In fs/proc/proc_net.c (ffffffff815b4c22)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_task_net
  - fs/proc/proc_net.c:bpf_iter_init_seq_net
```
```
In fs/sysfs/mount.c (ffffffff815c031a)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - fs/sysfs/mount.c:sysfs_init_fs_context
```
```
In fs/configfs/item.c (ffffffff815c6545)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - fs/configfs/item.c:config_group_find_item
```
```
In fs/ext4/page-io.c (ffffffff816133ea)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_folio
```
```
In fs/hugetlbfs/inode.c (ffffffff81667d89)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlb_unmap_file_folio
```
```
In fs/ecryptfs/keystore.c (ffffffff81682229)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
```
```
In fs/fuse/dev.c (ffffffff8168bee8)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:fuse_simple_request
```
```
In fs/fuse/file.c (ffffffff81699826)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_writepages_send
  - fs/fuse/file.c:fuse_write_inode
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_readahead
  - fs/fuse/file.c:fuse_async_req_send
```
```
In fs/fuse/inode.c (ffffffff8169ef78)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_fill_super_common
  - fs/fuse/inode.c:fuse_get_tree_submount
  - fs/fuse/inode.c:fuse_fill_super_submount
  - fs/fuse/inode.c:fuse_fill_super_submount
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_conn_init
```
```
In fs/fuse/dax.c (ffffffff816a4c45)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_iomap_begin
```
```
In fs/tracefs/event_inode.c (ffffffff816abedf)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - fs/tracefs/event_inode.c:eventfs_create_events_dir
  - fs/tracefs/event_inode.c:eventfs_root_lookup
  - fs/tracefs/event_inode.c:eventfs_root_lookup
```
```
In ipc/util.c (ffffffff816b0c6b)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_open
  - ipc/util.c:sysvipc_proc_open
```
```
In ipc/msg.c (ffffffff816b4462)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:expunge_all
```
```
In ipc/sem.c (ffffffff816b9cd6)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:copy_semundo
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:freeary
  - ipc/sem.c:update_queue
  - ipc/sem.c:wake_const_ops
  - ipc/sem.c:perform_atomic_semop
  - ipc/sem.c:perform_atomic_semop
```
```
In ipc/shm.c (ffffffff816bc92a)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:newseg
  - ipc/shm.c:__shm_close
  - ipc/shm.c:__shm_open
```
```
In ipc/mqueue.c (ffffffff816c15d8)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - ipc/mqueue.c:mq_init_ns
  - ipc/mqueue.c:mq_init_ns
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mqueue_init_fs_context
  - ipc/mqueue.c:mqueue_init_fs_context
```
```
In ipc/namespace.c (ffffffff816c1d2f)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - ipc/namespace.c:ipcns_install
  - ipc/namespace.c:ipcns_get
  - ipc/namespace.c:get_ipc_ns_exported
  - ipc/namespace.c:copy_ipcs
```
```
In security/keys/key.c (ffffffff816c3e08)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_user_lookup
```
```
In security/keys/keyring.c (ffffffff816c5b89)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_gc_select_iterator
  - security/keys/keyring.c:__key_link
  - security/keys/keyring.c:find_key_to_update
  - security/keys/keyring.c:keyring_search_rcu
```
```
In security/keys/keyctl.c (ffffffff816c71c7)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - security/keys/keyctl.c:get_instantiation_keyring
```
```
In security/keys/process_keys.c (ffffffff816cb43f)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:install_session_keyring_to_cred
```
```
In security/keys/request_key.c (ffffffff816cc3a7)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:cache_requested_key
  - security/keys/request_key.c:check_cached_key
```
```
In security/keys/request_key_auth.c (ffffffff816cceb3)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
```
```
In security/apparmor/apparmorfs.c (ffffffff81734ddb)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:policy_get_link
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
  - security/apparmor/apparmorfs.c:multi_transaction_read
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
```
```
In security/apparmor/audit.c (ffffffff817375fd)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - security/apparmor/audit.c:aa_audit_cache_insert
  - security/apparmor/audit.c:aa_audit_cache_find
  - security/apparmor/audit.c:aa_dup_audit_data
  - security/apparmor/audit.c:aa_dup_audit_data
```
```
In security/apparmor/capability.c (ffffffff81737912)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - security/apparmor/capability.c:audit_caps
```
```
In security/apparmor/task.c (ffffffff817390f9)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_profile_ns_perm
  - security/apparmor/task.c:aa_profile_ns_perm
  - security/apparmor/task.c:aa_profile_ns_perm
  - security/apparmor/task.c:aa_profile_ns_perm
  - security/apparmor/task.c:aa_profile_ns_perm
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_set_current_onexec
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_get_task_label
```
```
In security/apparmor/domain.c (ffffffff81741db3)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:find_attach
  - security/apparmor/domain.c:find_attach
```
```
In security/apparmor/policy.c (ffffffff817460b5)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:aa_new_learning_profile
  - security/apparmor/policy.c:aa_alloc_null
  - security/apparmor/policy.c:aa_alloc_null
  - security/apparmor/policy.c:aa_alloc_null
  - security/apparmor/policy.c:aa_alloc_null
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_alloc_profile
  - security/apparmor/policy.c:__add_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff81747191)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:do_loaddata_free
```
```
In security/apparmor/procattr.c (ffffffff8174a12a)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff8392c05e)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:aa_setup_dfa_engine
  - security/apparmor/lsm.c:apparmor_sock_graft
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - security/apparmor/lsm.c:apparmor_userns_create
  - security/apparmor/lsm.c:apparmor_userns_create
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getselfattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_inode_init_security
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_task_alloc
  - security/apparmor/lsm.c:apparmor_task_alloc
  - security/apparmor/lsm.c:apparmor_task_alloc
  - security/apparmor/lsm.c:apparmor_cred_transfer
  - security/apparmor/lsm.c:apparmor_cred_prepare
```
```
In security/apparmor/resource.c (ffffffff817532d5)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff81755a7e)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:aa_file_perm
```
```
In security/apparmor/policy_ns.c (ffffffff8392c3c4)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_alloc_root_ns
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:__aa_find_or_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:aa_lookupn_ns
```
```
In security/apparmor/label.c (ffffffff81759032)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:__label_insert
  - security/apparmor/label.c:__label_insert
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/label.c:__proxy_share
  - security/apparmor/label.c:__aa_proxy_redirect
  - security/apparmor/label.c:aa_alloc_proxy
  - security/apparmor/label.c:aa_get_current_ns
```
```
In security/apparmor/mount.c (ffffffff8175db80)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:build_pivotroot
```
```
In security/apparmor/net.c (0)
Location: include/linux/refcount.h:237
Inline: True
```
```
In security/apparmor/af_unix.c (ffffffff81761a30)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
```
```
In security/apparmor/af_inet.c (0)
Location: include/linux/refcount.h:237
Inline: True
```
```
In security/apparmor/notify.c (ffffffff817649cb)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - security/apparmor/notify.c:build_v3_unotif
  - security/apparmor/notify.c:aa_clone_ruleset
  - security/apparmor/notify.c:aa_clone_ruleset
  - security/apparmor/notify.c:aa_do_notification
  - security/apparmor/notify.c:aa_do_notification
  - security/apparmor/notify.c:aa_do_notification
  - security/apparmor/notify.c:aa_new_listener
  - security/apparmor/notify.c:aa_register_listener_proxy
  - security/apparmor/notify.c:aa_get_current_ns
```
```
In security/yama/yama_lsm.c (ffffffff817678c2)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_task_prctl
  - security/yama/yama_lsm.c:report_access
  - security/yama/yama_lsm.c:report_access
```
```
In security/safesetid/lsm.c (ffffffff8176813c)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - security/safesetid/lsm.c:safesetid_task_fix_setgroups
```
```
In security/landlock/syscalls.c (ffffffff8176ac23)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - security/landlock/syscalls.c:get_ruleset_from_fd
```
```
In security/landlock/ruleset.c (ffffffff8176b93a)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - security/landlock/ruleset.c:inherit_ruleset
```
```
In security/landlock/cred.c (ffffffff8176c41f)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - security/landlock/cred.c:hook_cred_prepare
```
```
In crypto/api.c (ffffffff8177ed76)
Location: include/linux/refcount.h:237
Inline: True
```
```
In crypto/algapi.c (ffffffff81780cf8)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_spawn_alg
```
```
In crypto/algboss.c (ffffffff8178e292)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - crypto/algboss.c:cryptomgr_schedule_probe
```
```
In crypto/asymmetric_keys/restrict.c (ffffffff817a1468)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
```
```
In block/blk-core.c (ffffffff817b2e82)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - block/blk-core.c:blk_get_queue
```
```
In block/blk-cgroup.c (ffffffff817e35b9)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_online
```
```
In io_uring/io_uring.c (ffffffff81816999)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_create
  - io_uring/io_uring.c:io_uring_create
```
```
In io_uring/sqpoll.c (ffffffff8181f4ec)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - io_uring/sqpoll.c:io_get_sq_data
```
```
In io_uring/register.c (ffffffff8182bdea)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - io_uring/register.c:__io_uring_register
  - io_uring/register.c:io_register_iowq_max_workers
```
```
In io_uring/io-wq.c (ffffffff8182e5a9)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_create
  - io_uring/io-wq.c:io_wq_create
```
```
In rust/helpers.c (ffffffff818429ea)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - rust/helpers.c:rust_helper_get_task_struct
  - rust/helpers.c:rust_helper_refcount_inc
```
```
In lib/cpu_rmap.c (ffffffff81925a44)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
```
```
In drivers/pinctrl/core.c (ffffffff819361df)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_get
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff819a4cb0)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff819c444d)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:get_fb_info
```
```
In drivers/acpi/ec.c (ffffffff819f9259)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_submit_query
```
```
In drivers/acpi/thermal.c (ffffffff81a6c62b)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - drivers/acpi/thermal.c:acpi_thermal_check_fn
```
```
In drivers/clk/clk.c (ffffffff81a92790)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_hw_create_clk
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff81ac7a3a)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
```
```
In drivers/reset/core.c (ffffffff81ae3359)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - drivers/reset/core.c:__reset_control_get_internal
```
```
In drivers/tty/tty_io.c (ffffffff81ae94af)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:__do_SAK
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:tty_lookup_driver
  - drivers/tty/tty_io.c:tty_lookup_driver
  - drivers/tty/tty_io.c:tty_lookup_driver
  - drivers/tty/tty_io.c:tty_find_polling_driver
```
```
In drivers/tty/tty_port.c (ffffffff81af2d8f)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_tty_get
```
```
In drivers/tty/tty_mutex.c (ffffffff81af37e6)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/tty_mutex.c:tty_lock
```
```
In drivers/tty/tty_ldsem.c (ffffffff8223c08d)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:down_read_failed
```
```
In drivers/tty/tty_jobctrl.c (ffffffff81af5324)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_get_pgrp
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:get_current_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
```
```
In drivers/tty/pty.c (ffffffff81af665f)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - drivers/tty/pty.c:pty_common_install
  - drivers/tty/pty.c:pty_common_install
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff81af9b03)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_k_ioctl
```
```
In drivers/char/virtio_console.c (ffffffff81b38a38)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:port_fops_open
```
```
In drivers/char/hw_random/core.c (ffffffff81b3b40f)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:hwrng_register
  - drivers/char/hw_random/core.c:hwrng_fillfn
```
```
In drivers/iommu/iommu-sva.c (ffffffff81b80f8e)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - drivers/iommu/iommu-sva.c:iommu_sva_bind_device
```
```
In drivers/connector/connector.c (ffffffff81b82880)
Location: include/linux/refcount.h:237
Inline: True
```
```
In drivers/base/core.c (ffffffff81b8ae0a)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/power/runtime.c (ffffffff81ba7d23)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_get_suppliers
```
```
In drivers/base/firmware_loader/main.c (ffffffff81bb399c)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:assign_fw
  - drivers/base/firmware_loader/main.c:alloc_lookup_fw_priv
```
```
In drivers/nvdimm/core.c (ffffffff81bf666b)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81bfaf7a)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:get_ndd
```
```
In drivers/dax/bus.c (ffffffff81c1038b)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - drivers/dax/bus.c:devm_create_dev_dax
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81c1203c)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll_add_cb
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81c13c1b)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff81c14cdb)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff81c15770)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_set_deadline
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_find_seqno
```
```
In drivers/dma-buf/dma-fence-unwrap.c (ffffffff81c15e65)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-unwrap.c:__dma_fence_unwrap_merge
  - drivers/dma-buf/dma-fence-unwrap.c:dma_fence_unwrap_first
```
```
In drivers/dma-buf/dma-resv.c (ffffffff81c1711e)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_replace_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_add_fence
```
```
In drivers/dma-buf/sync_file.c (ffffffff81c1909d)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_get_fence
  - drivers/dma-buf/sync_file.c:sync_file_create
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81c1a5ad)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_pt_create
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
```
```
In drivers/scsi/scsi_scan.c (ffffffff81c2c36d)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff81c31720)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
```
```
In drivers/scsi/sg.c (ffffffff81c4b493)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_sfp
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/ata/libata-core.c (ffffffff81c5967a)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_get
```
```
In drivers/gpu/drm/drm_auth.c (ffffffff81c7e5a4)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_auth.c:drm_file_get_master
  - drivers/gpu/drm/drm_auth.c:drm_master_open
  - drivers/gpu/drm/drm_auth.c:drm_setmaster_ioctl
  - drivers/gpu/drm/drm_auth.c:drm_new_set_master
```
```
In drivers/gpu/drm/drm_drv.c (ffffffff81c8c578)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_drv.c:drm_minor_acquire
```
```
In drivers/gpu/drm/drm_file.c (ffffffff81c97ff9)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_file.c:drm_file_update_pid
  - drivers/gpu/drm/drm_file.c:drm_file_alloc
```
```
In drivers/gpu/drm/drm_gem.c (ffffffff81c9cfe3)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_gem.c:drm_gem_mmap_obj
  - drivers/gpu/drm/drm_gem.c:drm_gem_vm_open
  - drivers/gpu/drm/drm_gem.c:drm_gem_open_ioctl
  - drivers/gpu/drm/drm_gem.c:objects_lookup
  - drivers/gpu/drm/drm_gem.c:drm_gem_handle_create_tail
```
```
In drivers/gpu/drm/drm_mode_object.c (ffffffff81ca38ce)
Location: include/linux/refcount.h:237
Inline: True
```
```
In drivers/gpu/drm/drm_prime.c (ffffffff81cac9f6)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_prime.c:drm_gem_prime_mmap
  - drivers/gpu/drm/drm_prime.c:drm_gem_dmabuf_export
```
```
In drivers/gpu/drm/drm_syncobj.c (ffffffff81cb206f)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_query_ioctl
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_query_ioctl
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_query_ioctl
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_fd_to_handle_ioctl
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_get_fd
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_get_handle
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_replace_fence
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_add_point
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_add_point
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_fence_add_wait
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_find
```
```
In drivers/gpu/drm/drm_atomic_helper.c (ffffffff81cc2f46)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_commit_hw_done
  - drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_setup_commit
  - drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_setup_commit
  - drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_setup_commit
  - drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_setup_commit
  - drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_setup_commit
  - drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_commit
```
```
In drivers/gpu/drm/drm_gem_atomic_helper.c (ffffffff81ccb096)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_gem_atomic_helper.c:drm_gem_plane_helper_prepare_fb
```
```
In drivers/net/phy/phy_device.c (ffffffff81cf030b)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_package_join
```
```
In drivers/net/phy/sfp-bus.c (ffffffff81cf69d5)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_add_upstream
  - drivers/net/phy/sfp-bus.c:sfp_bus_get
```
```
In drivers/net/pse-pd/pse_core.c (0)
Location: include/linux/refcount.h:237
Inline: True
```
```
In drivers/net/tun.c (ffffffff81cfd93c)
Location: include/linux/refcount.h:237
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81d18c00)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_init
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
```
In drivers/net/xen-netfront.c (ffffffff81d1eb0a)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_make_one_txreq
```
```
In drivers/usb/core/hub.c (ffffffff81d308a1)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/hcd.c (ffffffff81d39585)
Location: include/linux/refcount.h:237
Inline: True
```
```
In drivers/usb/core/urb.c (ffffffff81d3d4a5)
Location: include/linux/refcount.h:237
Inline: True
```
```
In drivers/usb/core/message.c (ffffffff81d417e6)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_set_configuration
```
```
In drivers/usb/core/devio.c (ffffffff81d4d39a)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:async_completed
```
```
In drivers/md/dm.c (ffffffff81e30565)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_get_table_device
```
```
In drivers/md/dm-table.c (ffffffff8222b215)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_get_device
```
```
In drivers/opp/core.c (ffffffff81e498a3)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_adjust_voltage
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_xlate_required_opp
  - drivers/opp/core.c:_set_opp
  - drivers/opp/core.c:_set_opp
  - drivers/opp/core.c:_opp_table_find_key
  - drivers/opp/core.c:_find_opp_table_unlocked
```
```
In drivers/nvmem/core.c (ffffffff81eb0306)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - drivers/nvmem/core.c:__nvmem_device_get
```
```
In drivers/dpll/dpll_core.c (ffffffff81eb7e25)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - drivers/dpll/dpll_core.c:dpll_pin_on_pin_register
  - drivers/dpll/dpll_core.c:dpll_pin_get
  - drivers/dpll/dpll_core.c:dpll_device_get
  - drivers/dpll/dpll_core.c:dpll_xa_ref_dpll_add
  - drivers/dpll/dpll_core.c:dpll_xa_ref_dpll_add
  - drivers/dpll/dpll_core.c:dpll_xa_ref_pin_add
  - drivers/dpll/dpll_core.c:dpll_xa_ref_pin_add
```
```
In net/core/sock.c (ffffffff81ec7a72)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sk_getsockopt
```
```
In net/core/skbuff.c (ffffffff81ed0cb3)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_ext_maybe_cow
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:msg_zerocopy_realloc
  - net/core/skbuff.c:msg_zerocopy_realloc
  - net/core/skbuff.c:mm_account_pinned_pages
  - net/core/skbuff.c:__copy_skb_header
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/core/datagram.c (ffffffff81ede91d)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_from_queue
```
```
In net/core/scm.c (ffffffff81ee02aa)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
  - net/core/scm.c:__scm_send
```
```
In net/core/net_namespace.c (ffffffff81ee30f7)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_get
  - net/core/net_namespace.c:get_net_ns_by_pid
  - net/core/net_namespace.c:get_net_ns_by_fd
  - net/core/net_namespace.c:get_net_ns
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:copy_net_ns
```
```
In net/core/dev.c (ffffffff81ef0b55)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/neighbour.c (ffffffff81f09e3d)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_alloc
  - net/core/neighbour.c:neigh_add_timer
```
```
In net/core/rtnetlink.c (ffffffff81f0f855)
Location: include/linux/refcount.h:237
Inline: True
```
```
In net/core/flow_offload.c (ffffffff81f3ab43)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_dev_register
```
```
In net/core/net-sysfs.c (ffffffff81f3fa9e)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - net/core/net-sysfs.c:net_grab_current_ns
```
```
In net/core/page_pool.c (ffffffff81f44ee3)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_use_xdp_mem
```
```
In net/core/netpoll.c (ffffffff81f47cfb)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_setup
```
```
In net/core/skmsg.c (ffffffff81f63895)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_psock_init
  - net/core/skmsg.c:sk_psock_backlog
```
```
In net/core/sock_map.c (ffffffff81f6843c)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_map_free
```
```
In net/sched/sch_generic.c (ffffffff81f70afb)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - net/sched/sch_generic.c:attach_default_qdiscs
  - net/sched/sch_generic.c:attach_default_qdiscs
```
```
In net/sched/sch_api.c (ffffffff81f7709d)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
```
```
In net/sched/cls_api.c (ffffffff81f79ba0)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_chain_tp_find
  - net/sched/cls_api.c:tcf_chain_tp_insert_unique
  - net/sched/cls_api.c:__tcf_block_find
  - net/sched/cls_api.c:__tcf_get_next_proto
```
```
In net/sched/act_api.c (ffffffff81f8090e)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_idr_search
```
```
In net/netlink/af_netlink.c (ffffffff81f8beb0)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:do_one_broadcast
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_getsockbyfilp
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/ipv4/route.c (ffffffff81fb2235)
Location: include/linux/refcount.h:237
Inline: True
```
```
In net/ipv4/ip_fragment.c (ffffffff81fb98e8)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
```
In net/ipv4/ip_output.c (ffffffff81fbebfe)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/ip_sockglue.c (ffffffff81fc268e)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_ra_control
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81fc8566)
Location: include/linux/refcount.h:237
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81fcaf66)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_complete_hashdance
```
```
In net/ipv4/tcp.c (ffffffff81fd4bd0)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_abort
  - net/ipv4/tcp.c:__tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff81fd8e77)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (ffffffff81fe9db5)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/tcp_output.c:tcp_tsq_handler
```
```
In net/ipv4/tcp_timer.c (ffffffff81fee3dc)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff4612)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
```
```
In net/ipv4/raw.c (ffffffff82001d3f)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_hash_sk
```
```
In net/ipv4/udp.c (ffffffff82005d50)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - net/ipv4/udp.c:bpf_iter_udp_batch
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/arp.c (ffffffff820101ac)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_constructor
```
```
In net/ipv4/devinet.c (ffffffff82018a3b)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
```
```
In net/ipv4/igmp.c (ffffffff8201fdf2)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - net/ipv4/igmp.c:____ip_mc_inc_group
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_ifc_event
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
```
```
In net/ipv4/fib_semantics.c (ffffffff82028aa0)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/fib_trie.c (ffffffff8202dfe6)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv4/inet_fragment.c (ffffffff8203046b)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:fqdir_init
```
```
In net/ipv4/ping.c (ffffffff82032a42)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
  - net/ipv4/ping.c:ping_get_port
```
```
In net/ipv4/nexthop.c (ffffffff8203c923)
Location: include/linux/refcount.h:237
Inline: True
```
```
In net/ipv4/tcp_sigpool.c (ffffffff8204cafc)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - net/ipv4/tcp_sigpool.c:tcp_sigpool_get
```
```
In net/ipv4/cipso_ipv4.c (ffffffff82050a77)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_check
```
```
In net/ipv4/tcp_ao.c (ffffffff82056547)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - net/ipv4/tcp_ao.c:tcp_ao_time_wait
```
```
In net/xfrm/xfrm_policy.c (ffffffff8205f60c)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:__xfrm_policy_link
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
```
```
In net/xfrm/xfrm_state.c (ffffffff8206af2d)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:xfrm_state_lookup_byspi
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
```
```
In net/xfrm/xfrm_output.c (ffffffff82071736)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
```
```
In net/unix/af_unix.c (ffffffff820782be)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - net/unix/af_unix.c:bpf_iter_unix_batch
  - net/unix/af_unix.c:bpf_iter_unix_batch
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:__unix_dgram_recvmsg
  - net/unix/af_unix.c:queue_oob
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_getname
  - net/unix/af_unix.c:unix_getname
  - net/unix/af_unix.c:unix_socketpair
  - net/unix/af_unix.c:unix_socketpair
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:init_peercred
  - net/unix/af_unix.c:__unix_set_addr_hash
```
```
In net/unix/unix_bpf.c (ffffffff8207e78e)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - net/unix/unix_bpf.c:unix_stream_bpf_update_proto
```
```
In net/ipv6/anycast.c (ffffffff820810bf)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/ip6_output.c (ffffffff820830e8)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/addrconf.c (ffffffff82097bc3)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_set_iftoken
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_kick
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_permanent_addr
  - net/ipv6/addrconf.c:addrconf_add_linklocal
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/route.c (ffffffff8396bd01)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_init_special_entries
  - net/ipv6/route.c:ip6_route_init_special_entries
  - net/ipv6/route.c:ip6_route_init_special_entries
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_rt_copy_init
  - net/ipv6/route.c:ip6_rt_copy_init
  - net/ipv6/route.c:ip6_dst_ifdown
```
```
In net/ipv6/ip6_fib.c (ffffffff820abeaa)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_purge_rt
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff820ad9b9)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ip6_ra_control
```
```
In net/ipv6/ndisc.c (ffffffff820b1f58)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change
  - net/ipv6/ndisc.c:ndisc_netdev_event
  - net/ipv6/ndisc.c:ndisc_netdev_event
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_unsol_na
  - net/ipv6/ndisc.c:ndisc_constructor
  - net/ipv6/ndisc.c:ndisc_constructor
```
```
In net/ipv6/mcast.c (ffffffff820c38e1)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_ifc_work
  - net/ipv6/mcast.c:mld_dad_work
  - net/ipv6/mcast.c:ipv6_mc_dad_complete
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:igmp6_group_dropped
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820cd7ec)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_route_req
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/xfrm6_policy.c (ffffffff820e09e2)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_ifdown
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_ifdown
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
```
```
In net/ipv6/syncookies.c (ffffffff820e561c)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/calipso.c (ffffffff820e63de)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_cache_add
  - net/ipv6/calipso.c:calipso_cache_check
```
```
In net/packet/af_packet.c (ffffffff820f7bd4)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
  - net/packet/af_packet.c:tpacket_rcv
```
```
In net/devlink/core.c (ffffffff82100716)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - net/devlink/core.c:devlink_rel_nested_in_notify_work_schedule
```
```
In net/devlink/rate.c (ffffffff82118ce3)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - net/devlink/rate.c:devl_rate_leaf_create
  - net/devlink/rate.c:devlink_nl_rate_parent_node_set
```
```
In net/ncsi/ncsi-cmd.c (ffffffff82133b97)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
```
In net/ncsi/ncsi-netlink.c (ffffffff8213b07a)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
```
```
In net/xdp/xsk.c (ffffffff8213e276)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
```
```
In net/xdp/xdp_umem.c (ffffffff82140433)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
  - net/xdp/xdp_umem.c:xdp_get_umem
```
```
In net/xdp/xsk_buff_pool.c (ffffffff82141ce1)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_dma_map
  - net/xdp/xsk_buff_pool.c:xp_get_pool
```
```
In net/mptcp/protocol.c (ffffffff8214d73a)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_finish_join
  - net/mptcp/protocol.c:mptcp_finish_join
  - net/mptcp/protocol.c:mptcp_finish_join
  - net/mptcp/protocol.c:mptcp_sk_clone_init
  - net/mptcp/protocol.c:__mptcp_close
  - net/mptcp/protocol.c:__mptcp_subflow_push_pending
```
```
In net/mptcp/subflow.c (ffffffff82151e57)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_queue_clean
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
  - net/mptcp/subflow.c:__mptcp_subflow_connect
  - net/mptcp/subflow.c:subflow_write_space
  - net/mptcp/subflow.c:mptcp_subflow_reset
```
```
In net/mptcp/options.c (ffffffff82152f65)
Location: include/linux/refcount.h:237
Inline: True
```
```
In net/mctp/af_mctp.c (ffffffff82163a9c)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_sk_hash
```
```
In net/mctp/device.c (ffffffff821650fb)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_dev_set_key
```
```
In net/mctp/route.c (ffffffff821679da)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_local_output
  - net/mctp/route.c:mctp_alloc_local_tag
  - net/mctp/route.c:mctp_key_add
  - net/mctp/route.c:mctp_key_alloc
```
```
In net/handshake/request.c (ffffffff82169c63)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - net/handshake/request.c:handshake_req_submit
```
```
In lib/klist.c (ffffffff82179cab)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - lib/klist.c:klist_next
  - lib/klist.c:klist_prev
```
```
In lib/kobject.c (ffffffff8217a857)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - lib/kobject.c:kobject_get
```
```
In lib/kobject_uevent.c (ffffffff8217c68b)
Location: include/linux/refcount.h:237
Inline: True
Inline callers:
  - lib/kobject_uevent.c:kobject_uevent_net_broadcast
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
