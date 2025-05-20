# Function: <code>refcount_inc_checked</code>

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
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void refcount_inc_checked(refcount_t *r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/refcount.c (ffffffff814e21b0)
Location: lib/refcount.c:151
Inline: True
```
**Symbols:**

```
ffffffff814e21b0-ffffffff814e21df: refcount_inc_checked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void refcount_inc_checked(refcount_t *r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/refcount.c (ffffffff8150e040)
Location: lib/refcount.c:154
Inline: True
```
**Symbols:**

```
ffffffff8150e040-ffffffff8150e06f: refcount_inc_checked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void refcount_inc_checked(refcount_t *r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/refcount.c (ffffffff8152be90)
Location: lib/refcount.c:154
Inline: True
```
**Symbols:**

```
ffffffff8152be90-ffffffff8152bebf: refcount_inc_checked (STB_GLOBAL)
```
</details>
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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void refcount_inc_checked(refcount_t *r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/refcount.c (ffff800010637b60)
Location: lib/refcount.c:154
Inline: True
Direct callers:
  - virt/kvm/kvm_main.c:kvm_vm_ioctl
  - virt/kvm/kvm_main.c:kvm_vm_ioctl
  - virt/kvm/arm/vgic/vgic.c:vgic_queue_irq_unlock
  - virt/kvm/arm/vgic/vgic-its.c:vgic_its_resolve_lpi
  - kernel/fork.c:_do_fork
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/exit.c:kernel_waitid
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:mm_update_next_owner
  - kernel/signal.c:__sigqueue_alloc
  - kernel/sys.c:__arm64_sys_prlimit64
  - kernel/pid.c:__arm64_sys_pidfd_open
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:get_pid_task
  - kernel/pid.c:get_task_pid
  - kernel/pid.c:find_get_task_by_vpid
  - kernel/pid.c:alloc_pid
  - kernel/kthread.c:kthread_stop
  - kernel/kthread.c:kthread_stop
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__arm64_sys_sched_setattr
  - kernel/sched/core.c:do_sched_setscheduler
  - kernel/sched/core.c:wake_q_add
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/deadline.c:start_dl_timer
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:sched_autogroup_fork
  - kernel/sched/autogroup.c:sched_autogroup_fork
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_move_group
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/locking/rtmutex.c:rt_mutex_adjust_pi
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/kcmp.c:__arm64_sys_kcmp
  - kernel/kcmp.c:__arm64_sys_kcmp
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/posix-cpu-timers.c:__get_task_for_clock
  - kernel/futex.c:mark_wake_futex
  - kernel/cgroup/cgroup.c:cgroup_exit
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:css_task_iter_next
  - kernel/cgroup/cgroup.c:css_task_iter_advance_css_set
  - kernel/cgroup/cgroup.c:css_task_iter_advance_css_set
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
  - kernel/cgroup/cgroup.c:cgroup_enable_task_cg_lists
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/namespace.c:cgroupns_get
  - kernel/cgroup/namespace.c:cgroupns_install
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/utsname.c:utsns_install
  - kernel/utsname.c:utsns_get
  - kernel/utsname.c:copy_utsname
  - kernel/pid_namespace.c:pidns_get_parent
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:pidns_get
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/audit.c:audit_get_tty
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_send_queue
  - kernel/auditfilter.c:audit_list_rules_send
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:audit_trim_trees
  - kernel/audit_tree.c:replace_chunk
  - kernel/hung_task.c:watchdog
  - kernel/hung_task.c:watchdog
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/relay.c:relay_file_open
  - kernel/trace/trace.c:buffer_pipe_buf_get
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_map_charge_init
  - kernel/bpf/btf.c:btf_get_by_fd
  - kernel/bpf/offload.c:bpf_map_offload_info_fill_ns
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill_ns
  - kernel/events/core.c:perf_event_init_task
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
  - kernel/events/core.c:alloc_perf_context
  - kernel/events/uprobes.c:handler_chain
  - kernel/events/uprobes.c:uprobe_copy_process
  - kernel/events/uprobes.c:uprobe_mmap
  - kernel/events/uprobes.c:uprobe_mmap
  - kernel/events/uprobes.c:__find_uprobe
  - mm/oom_kill.c:__oom_kill_process
  - mm/backing-dev.c:bdi_get_by_id
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_congested_get_create
  - mm/backing-dev.c:wb_init
  - mm/mlock.c:user_shm_lock
  - mm/page_io.c:swap_readpage
  - mm/hugetlb.c:hugetlb_vm_op_open
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/migrate.c:kernel_move_pages
  - mm/memory-failure.c:add_to_kill
  - fs/super.c:set_bdev_super_fc
  - fs/pipe.c:alloc_pipe_info
  - fs/fcntl.c:f_modown
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/fs_context.c:alloc_fs_context
  - fs/block_dev.c:__blkdev_get
  - fs/notify/group.c:fsnotify_get_group
  - fs/notify/mark.c:fsnotify_get_mark
  - fs/notify/mark.c:fsnotify_get_mark
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify_user.c:__arm64_sys_fanotify_init
  - fs/eventpoll.c:do_epoll_create
  - fs/eventfd.c:eventfd_ctx_fdget
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_unmap_prep
  - fs/userfaultfd.c:userfaultfd_remove
  - fs/userfaultfd.c:mremap_userfaultfd_prep
  - fs/userfaultfd.c:dup_userfaultfd
  - fs/userfaultfd.c:handle_userfault
  - fs/io_uring.c:__arm64_sys_io_uring_register
  - fs/io_uring.c:io_uring_create
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
  - fs/posix_acl.c:set_cached_acl
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/proc/root.c:proc_init_fs_context
  - fs/proc/root.c:proc_fill_super
  - fs/proc/root.c:proc_fill_super
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:next_tgid
  - fs/proc/base.c:proc_pid_lookup
  - fs/proc/array.c:get_children_pid
  - fs/proc/proc_net.c:get_proc_task_net
  - fs/configfs/item.c:config_group_find_item
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_writepages_send
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_async_req_send
  - fs/fuse/inode.c:fuse_dev_install
  - fs/fuse/inode.c:fuse_conn_init
  - ipc/util.c:sysvipc_proc_open
  - ipc/util.c:sysvipc_proc_open
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/sem.c:exit_sem
  - ipc/sem.c:copy_semundo
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:perform_atomic_semop
  - ipc/sem.c:perform_atomic_semop
  - ipc/shm.c:do_shmat
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mq_create_mount
  - ipc/mqueue.c:mqueue_init_fs_context
  - ipc/mqueue.c:mqueue_get_inode
  - ipc/namespace.c:ipcns_install
  - ipc/namespace.c:ipcns_get
  - ipc/namespace.c:get_ipc_ns_exported
  - ipc/namespace.c:copy_ipcs
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_user_lookup
  - security/keys/keyring.c:keyring_gc_select_iterator
  - security/keys/keyring.c:__key_link
  - security/keys/keyring.c:find_key_to_update
  - security/keys/keyring.c:keyring_search_rcu
  - security/keys/keyctl.c:keyctl_change_reqkey_auth
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:install_session_keyring_to_cred
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:cache_requested_key
  - security/keys/request_key.c:check_cached_key
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
  - security/apparmor/apparmorfs.c:multi_transaction_read
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
  - security/apparmor/capability.c:aa_capable
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_set_current_onexec
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_get_task_label
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
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
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
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:do_loaddata_free
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_sock_graft
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - security/apparmor/lsm.c:apparmor_sk_clone_security
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
  - security/apparmor/resource.c:aa_task_setrlimit
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:__aa_find_or_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:aa_lookupn_ns
  - security/apparmor/policy_ns.c:aa_findn_ns
  - security/apparmor/policy_ns.c:alloc_ns
  - security/apparmor/policy_ns.c:alloc_ns
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:__label_insert
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/label.c:__proxy_share
  - security/apparmor/label.c:__aa_proxy_redirect
  - security/apparmor/label.c:aa_alloc_proxy
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/yama/yama_lsm.c:yama_task_prctl
  - security/yama/yama_lsm.c:report_access
  - security/yama/yama_lsm.c:report_access
  - crypto/api.c:crypto_mod_get
  - crypto/algapi.c:crypto_stats_get
  - crypto/algboss.c:cryptomgr_notify
  - block/bsg.c:bsg_open
  - lib/cpu_rmap.c:irq_cpu_rmap_add
  - drivers/pinctrl/core.c:pinctrl_get
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pmx_request
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context
  - drivers/acpi/ec.c:acpi_ec_query
  - drivers/soc/qcom/smem_state.c:qcom_smem_state_get
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/reset/core.c:__reset_control_get_internal
  - drivers/tty/tty_io.c:__tty_fasync
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:tty_standard_install
  - drivers/tty/tty_io.c:tty_find_polling_driver
  - drivers/tty/tty_port.c:tty_port_tty_set
  - drivers/tty/tty_port.c:tty_port_tty_get
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/tty_mutex.c:tty_lock
  - drivers/tty/tty_ldsem.c:ldsem_down_read
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_get_pgrp
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:get_current_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/pty.c:pty_common_install
  - drivers/tty/pty.c:pty_common_install
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/power/runtime.c:pm_runtime_get_suppliers
  - drivers/base/power/runtime.c:rpm_get_suppliers
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:assign_fw
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
  - drivers/nvdimm/dimm_devs.c:get_ndd
  - drivers/dax/bus.c:__devm_create_dev_dax
  - drivers/dax/bus.c:alloc_dax_region
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
  - drivers/dma-buf/sync_file.c:sync_file_get_fence
  - drivers/dma-buf/sync_file.c:sync_file_create
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_block_check_events
  - drivers/scsi/sr.c:sr_block_open
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
  - drivers/ata/libata-core.c:ata_host_get
  - drivers/net/phy/sfp-bus.c:sfp_bus_get
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_init
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/xen-netfront.c:xennet_make_one_txreq
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hcd.c:usb_get_hcd
  - drivers/usb/core/urb.c:usb_get_from_anchor
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
  - drivers/usb/core/urb.c:usb_anchor_urb
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:async_completed
  - drivers/media/cec/cec-notifier.c:cec_notifier_register
  - drivers/md/dm.c:dm_get_table_device
  - drivers/md/dm-table.c:dm_get_device
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_find_freq_floor
  - drivers/opp/core.c:_find_freq_ceil
  - drivers/opp/core.c:dev_pm_opp_find_level_exact
  - drivers/opp/core.c:dev_pm_opp_find_freq_exact
  - drivers/opp/core.c:_find_opp_table_unlocked
  - drivers/opp/of.c:dev_pm_opp_of_add_table_indexed
  - drivers/opp/of.c:dev_pm_opp_of_add_table
  - drivers/remoteproc/remoteproc_virtio.c:rproc_add_virtio_dev
  - drivers/nvmem/core.c:__nvmem_device_get
  - net/socket.c:get_net_ns
  - net/core/sock.c:sk_reset_timer
  - net/core/sock.c:skb_set_owner_w
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:sock_zerocopy_realloc
  - net/core/skbuff.c:sock_zerocopy_alloc
  - net/core/skbuff.c:__copy_skb_header
  - net/core/datagram.c:__skb_try_recv_from_queue
  - net/core/scm.c:scm_fp_dup
  - net/core/scm.c:__scm_send
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_get
  - net/core/net_namespace.c:get_net_ns_by_pid
  - net/core/net_namespace.c:get_net_ns_by_fd
  - net/core/net_namespace.c:copy_net_ns
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
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:___neigh_create
  - net/core/rtnetlink.c:rtnetlink_send
  - net/core/net-sysfs.c:net_grab_current_ns
  - net/core/page_pool.c:page_pool_use_xdp_mem
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_psock_init
  - net/core/skmsg.c:sk_psock_init
  - net/core/netpoll.c:__netpoll_setup
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_health_reporter_get_from_attrs
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:__tcf_block_find
  - net/sched/cls_api.c:__tcf_get_next_proto
  - net/sched/act_api.c:tcf_idr_check_alloc
  - net/sched/act_api.c:tcf_idr_search
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_getsockbyfilp
  - net/netlink/af_netlink.c:netlink_insert
  - net/netlink/af_netlink.c:netlink_lookup
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_sockglue.c:ip_ra_control
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_tsq_handler
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
  - net/ipv4/raw.c:raw_hash_sk
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/arp.c:arp_constructor
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/igmp.c:____ip_mc_inc_group
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_ifc_start_timer
  - net/ipv4/igmp.c:igmp_start_timer
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/inet_fragment.c:fqdir_init
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_get_port
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:__xfrm_policy_link
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:maybe_init_creds
  - net/unix/af_unix.c:unix_scm_to_skb
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
  - net/unix/af_unix.c:unix_peer_get
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:addrconf_mod_dad_work
  - net/ipv6/addrconf.c:addrconf_mod_rs_timer
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
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ipv6_sockglue.c:ip6_ra_control
  - net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change
  - net/ipv6/ndisc.c:ndisc_netdev_event
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_unsol_na
  - net/ipv6/ndisc.c:ndisc_constructor
  - net/ipv6/ndisc.c:ndisc_constructor
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:mld_dad_start_timer
  - net/ipv6/mcast.c:mld_ifc_start_timer
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/packet/af_packet.c:packet_create
  - net/packet/af_packet.c:tpacket_rcv
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/xdp/xsk.c:xsk_create
  - net/xdp/xdp_umem.c:xdp_umem_create
  - net/xdp/xdp_umem.c:xdp_get_umem
  - lib/klist.c:klist_next
  - lib/klist.c:klist_prev
  - lib/kobject.c:kobject_get
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffff800010637b60-ffff800010637ba8: refcount_inc_checked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void refcount_inc_checked(refcount_t *r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/refcount.c (c07dd614)
Location: lib/refcount.c:154
Inline: True
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/exit.c:kernel_waitid
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:mm_update_next_owner
  - kernel/user.c:uid_hash_find
  - kernel/signal.c:__sigqueue_alloc
  - kernel/sys.c:__se_sys_prlimit64
  - kernel/pid.c:__se_sys_pidfd_open
  - kernel/pid.c:find_get_pid
  - kernel/pid.c:get_pid_task
  - kernel/pid.c:get_task_pid
  - kernel/pid.c:find_get_task_by_vpid
  - kernel/pid.c:alloc_pid
  - kernel/kthread.c:kthread_stop
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__se_sys_sched_setattr
  - kernel/sched/core.c:do_sched_setscheduler
  - kernel/sched/core.c:wake_q_add
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/deadline.c:start_dl_timer
  - kernel/sched/deadline.c:task_non_contending
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:sched_autogroup_fork
  - kernel/sched/autogroup.c:sched_autogroup_fork
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/locking/rwsem.c:rwsem_mark_wake
  - kernel/locking/rtmutex.c:rt_mutex_adjust_pi
  - kernel/locking/rtmutex.c:remove_waiter
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/kcmp.c:__se_sys_kcmp
  - kernel/kcmp.c:__se_sys_kcmp
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/posix-cpu-timers.c:__get_task_for_clock
  - kernel/futex.c:mark_wake_futex
  - kernel/cgroup/cgroup.c:cgroup_exit
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:css_task_iter_next
  - kernel/cgroup/cgroup.c:css_task_iter_advance_css_set
  - kernel/cgroup/cgroup.c:css_task_iter_advance_css_set
  - kernel/cgroup/cgroup.c:cgroup_procs_write_start
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
  - kernel/cgroup/cgroup.c:cgroup_enable_task_cg_lists
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/namespace.c:cgroupns_get
  - kernel/cgroup/namespace.c:cgroupns_install
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/utsname.c:utsns_install
  - kernel/utsname.c:utsns_get
  - kernel/utsname.c:copy_utsname
  - kernel/pid_namespace.c:pidns_get_parent
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:pidns_get
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/audit.c:audit_get_tty
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_send_queue
  - kernel/auditfilter.c:audit_list_rules_send
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:audit_trim_trees
  - kernel/audit_tree.c:replace_chunk
  - kernel/hung_task.c:watchdog
  - kernel/hung_task.c:watchdog
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_attach_filter
  - kernel/relay.c:relay_file_open
  - kernel/trace/trace.c:buffer_pipe_buf_get
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_map_charge_init
  - kernel/bpf/btf.c:btf_get_by_fd
  - kernel/bpf/offload.c:bpf_map_offload_info_fill_ns
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill_ns
  - kernel/events/core.c:perf_event_init_task
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
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:uprobe_copy_process
  - kernel/events/uprobes.c:uprobe_mmap
  - kernel/events/uprobes.c:uprobe_mmap
  - kernel/events/uprobes.c:__find_uprobe
  - mm/oom_kill.c:__oom_kill_process
  - mm/backing-dev.c:bdi_get_by_id
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_congested_get_create
  - mm/backing-dev.c:wb_init
  - mm/mlock.c:user_shm_lock
  - mm/page_io.c:swap_readpage
  - fs/super.c:set_bdev_super_fc
  - fs/pipe.c:alloc_pipe_info
  - fs/fcntl.c:f_modown
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/fs_context.c:alloc_fs_context
  - fs/block_dev.c:__blkdev_get
  - fs/notify/group.c:fsnotify_get_group
  - fs/notify/mark.c:fsnotify_get_mark
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_init
  - fs/eventpoll.c:do_epoll_create
  - fs/eventfd.c:eventfd_ctx_fdget
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/userfaultfd.c:userfaultfd_unmap_prep
  - fs/userfaultfd.c:userfaultfd_remove
  - fs/userfaultfd.c:mremap_userfaultfd_prep
  - fs/userfaultfd.c:dup_userfaultfd
  - fs/userfaultfd.c:handle_userfault
  - fs/io_uring.c:__se_sys_io_uring_register
  - fs/io_uring.c:io_uring_create
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
  - fs/posix_acl.c:set_cached_acl
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/proc/root.c:proc_init_fs_context
  - fs/proc/root.c:proc_fill_super
  - fs/proc/root.c:proc_fill_super
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:next_tgid
  - fs/proc/base.c:proc_pid_lookup
  - fs/proc/array.c:get_children_pid
  - fs/proc/proc_net.c:get_proc_task_net
  - fs/configfs/item.c:config_group_find_item
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_writepages_send
  - fs/fuse/file.c:fuse_writepage_end
  - fs/fuse/file.c:fuse_send_readpages
  - fs/fuse/file.c:fuse_async_req_send
  - fs/fuse/inode.c:fuse_dev_install
  - fs/fuse/inode.c:fuse_conn_init
  - ipc/util.c:sysvipc_proc_open
  - ipc/util.c:sysvipc_proc_open
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgsnd
  - ipc/sem.c:exit_sem
  - ipc/sem.c:copy_semundo
  - ipc/sem.c:ksys_semctl
  - ipc/sem.c:semctl_main
  - ipc/sem.c:perform_atomic_semop
  - ipc/sem.c:perform_atomic_semop
  - ipc/shm.c:do_shmat
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_close
  - ipc/shm.c:__shm_open
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:mqueue_create_attr
  - ipc/mqueue.c:mqueue_evict_inode
  - ipc/mqueue.c:mq_create_mount
  - ipc/mqueue.c:mqueue_init_fs_context
  - ipc/mqueue.c:mqueue_get_inode
  - ipc/namespace.c:ipcns_install
  - ipc/namespace.c:ipcns_get
  - ipc/namespace.c:get_ipc_ns_exported
  - ipc/namespace.c:copy_ipcs
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_user_lookup
  - security/keys/keyring.c:keyring_gc_select_iterator
  - security/keys/keyring.c:__key_link
  - security/keys/keyring.c:find_key_to_update
  - security/keys/keyring.c:keyring_search_rcu
  - security/keys/keyctl.c:keyctl_change_reqkey_auth
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:install_session_keyring_to_cred
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:cache_requested_key
  - security/keys/request_key.c:check_cached_key
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
  - security/apparmor/apparmorfs.c:seq_profile_open
  - security/apparmor/apparmorfs.c:multi_transaction_read
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
  - security/apparmor/capability.c:aa_capable
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_set_current_onexec
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_get_task_label
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
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
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
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:do_loaddata_free
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_sock_graft
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - security/apparmor/lsm.c:apparmor_sk_clone_security
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
  - security/apparmor/resource.c:aa_task_setrlimit
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:__aa_find_or_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:aa_lookupn_ns
  - security/apparmor/policy_ns.c:aa_findn_ns
  - security/apparmor/policy_ns.c:alloc_ns
  - security/apparmor/policy_ns.c:alloc_ns
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:__label_insert
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/label.c:__proxy_share
  - security/apparmor/label.c:__aa_proxy_redirect
  - security/apparmor/label.c:aa_alloc_proxy
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/yama/yama_lsm.c:yama_task_prctl
  - security/yama/yama_lsm.c:report_access
  - security/yama/yama_lsm.c:report_access
  - crypto/api.c:crypto_mod_get
  - crypto/algapi.c:crypto_stats_get
  - crypto/algboss.c:cryptomgr_notify
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - block/bsg.c:bsg_open
  - lib/cpu_rmap.c:irq_cpu_rmap_add
  - drivers/soc/qcom/smem_state.c:qcom_smem_state_get
  - drivers/reset/core.c:__reset_control_get_internal
  - drivers/tty/tty_io.c:__tty_fasync
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:tty_standard_install
  - drivers/tty/tty_io.c:tty_find_polling_driver
  - drivers/tty/tty_port.c:tty_port_tty_set
  - drivers/tty/tty_port.c:tty_port_tty_get
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/tty_mutex.c:tty_lock
  - drivers/tty/tty_ldsem.c:ldsem_down_read
  - drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl
  - drivers/tty/tty_jobctrl.c:tty_get_pgrp
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:tty_signal_session_leader
  - drivers/tty/tty_jobctrl.c:get_current_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
  - drivers/tty/pty.c:pty_common_install
  - drivers/tty/pty.c:pty_common_install
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/power/runtime.c:pm_runtime_get_suppliers
  - drivers/base/power/runtime.c:rpm_get_suppliers
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:assign_fw
  - drivers/dax/bus.c:__devm_create_dev_dax
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
  - drivers/dma-buf/sync_file.c:sync_file_get_fence
  - drivers/dma-buf/sync_file.c:sync_file_create
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_block_check_events
  - drivers/scsi/sr.c:sr_block_open
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
  - drivers/ata/libata-core.c:ata_host_get
  - drivers/mtd/mtdsuper.c:mtd_set_super
  - drivers/mtd/mtd_blkdevs.c:blktrans_open
  - drivers/mtd/mtd_blkdevs.c:blktrans_dev_get
  - drivers/net/phy/sfp-bus.c:sfp_bus_get
  - drivers/net/tun.c:tun_attach
  - drivers/net/ethernet/ti/cpts.c:cpts_find_ts
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_init
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hcd.c:usb_get_hcd
  - drivers/usb/core/urb.c:usb_get_from_anchor
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
  - drivers/usb/core/urb.c:usb_anchor_urb
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:async_completed
  - drivers/media/cec/cec-notifier.c:cec_notifier_register
  - drivers/md/dm.c:dm_get_table_device
  - drivers/md/dm-table.c:dm_get_device
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_find_freq_floor
  - drivers/opp/core.c:_find_freq_ceil
  - drivers/opp/core.c:dev_pm_opp_find_level_exact
  - drivers/opp/core.c:dev_pm_opp_find_freq_exact
  - drivers/opp/core.c:_find_opp_table_unlocked
  - drivers/opp/of.c:dev_pm_opp_of_add_table_indexed
  - drivers/opp/of.c:dev_pm_opp_of_add_table
  - drivers/remoteproc/remoteproc_virtio.c:rproc_add_virtio_dev
  - drivers/nvmem/core.c:__nvmem_device_get
  - sound/core/pcm.c:snd_pcm_attach_substream
  - sound/core/pcm_native.c:snd_pcm_common_ioctl
  - sound/core/pcm_native.c:snd_pcm_stream_group_ref
  - net/socket.c:get_net_ns
  - net/core/sock.c:sk_reset_timer
  - net/core/sock.c:skb_set_owner_w
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:sock_zerocopy_realloc
  - net/core/skbuff.c:sock_zerocopy_alloc
  - net/core/skbuff.c:__copy_skb_header
  - net/core/datagram.c:__skb_try_recv_from_queue
  - net/core/scm.c:scm_fp_dup
  - net/core/scm.c:__scm_send
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_get
  - net/core/net_namespace.c:get_net_ns_by_pid
  - net/core/net_namespace.c:get_net_ns_by_fd
  - net/core/net_namespace.c:copy_net_ns
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
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:___neigh_create
  - net/core/rtnetlink.c:rtnetlink_send
  - net/core/net-sysfs.c:net_grab_current_ns
  - net/core/page_pool.c:page_pool_use_xdp_mem
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_psock_init
  - net/core/netpoll.c:__netpoll_setup
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_health_reporter_get_from_attrs
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_chain_tp_find
  - net/sched/cls_api.c:__tcf_block_find
  - net/sched/cls_api.c:__tcf_get_next_proto
  - net/sched/act_api.c:tcf_idr_check_alloc
  - net/sched/act_api.c:tcf_idr_search
  - net/netlink/af_netlink.c:nlmsg_notify
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_getsockbyfilp
  - net/netlink/af_netlink.c:netlink_insert
  - net/netlink/af_netlink.c:netlink_lookup
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/ip_sockglue.c:ip_ra_control
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_tsq_handler
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
  - net/ipv4/raw.c:raw_hash_sk
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/arp.c:arp_constructor
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/igmp.c:____ip_mc_inc_group
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_ifc_start_timer
  - net/ipv4/igmp.c:igmp_start_timer
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/inet_fragment.c:fqdir_init
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_get_port
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:__xfrm_policy_link
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_state.c:__xfrm_find_acq_byseq
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:xfrm_state_lookup_byspi
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_scm_to_skb
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
  - net/unix/af_unix.c:unix_peer_get
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/ip6_output.c:__ip6_append_data
  - net/ipv6/ip6_output.c:__ip6_append_data
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:addrconf_mod_dad_work
  - net/ipv6/addrconf.c:addrconf_mod_rs_timer
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
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ipv6_sockglue.c:ip6_ra_control
  - net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change
  - net/ipv6/ndisc.c:ndisc_netdev_event
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_unsol_na
  - net/ipv6/ndisc.c:ndisc_constructor
  - net/ipv6/ndisc.c:ndisc_constructor
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:mld_dad_start_timer
  - net/ipv6/mcast.c:mld_ifc_start_timer
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_req
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/packet/af_packet.c:packet_create
  - net/packet/af_packet.c:tpacket_rcv
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/xdp/xsk.c:xsk_create
  - net/xdp/xdp_umem.c:xdp_umem_create
  - net/xdp/xdp_umem.c:xdp_get_umem
  - lib/klist.c:klist_next
  - lib/klist.c:klist_prev
  - lib/kobject.c:kobject_get
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
c07dd614-c07dd668: refcount_inc_checked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void refcount_inc_checked(refcount_t *r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/refcount.c (c0000000007dda10)
Location: lib/refcount.c:154
Inline: True
```
**Symbols:**

```
c0000000007dda10-c0000000007dda74: refcount_inc_checked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void refcount_inc_checked(refcount_t *r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/refcount.c (ffffffe000464b36)
Location: lib/refcount.c:154
Inline: True
```
**Symbols:**

```
ffffffe000464b36-ffffffe000464b78: refcount_inc_checked (STB_GLOBAL)
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
void refcount_inc_checked(refcount_t *r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/refcount.c (ffffffff81524470)
Location: lib/refcount.c:154
Inline: True
```
**Symbols:**

```
ffffffff81524470-ffffffff8152449f: refcount_inc_checked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void refcount_inc_checked(refcount_t *r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/refcount.c (ffffffff81514750)
Location: lib/refcount.c:154
Inline: True
```
**Symbols:**

```
ffffffff81514750-ffffffff8151477f: refcount_inc_checked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void refcount_inc_checked(refcount_t *r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/refcount.c (ffffffff81520500)
Location: lib/refcount.c:154
Inline: True
```
**Symbols:**

```
ffffffff81520500-ffffffff8152052f: refcount_inc_checked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void refcount_inc_checked(refcount_t *r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/refcount.c (ffffffff81539e80)
Location: lib/refcount.c:154
Inline: True
```
**Symbols:**

```
ffffffff81539e80-ffffffff81539eaf: refcount_inc_checked (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
