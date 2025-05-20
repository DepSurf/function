# Function: <code>atomic_try_cmpxchg_relaxed</code>

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
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff81040fab)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:get_wchan
```
```
In kernel/sched/core.c (ffffffff810dcdc4)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
```
```
In kernel/sched/fair.c (ffffffff810ef267)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_group
```
```
In kernel/locking/qspinlock.c (ffffffff8110fcbb)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
```
```
In kernel/stacktrace.c (ffffffff81141472)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - kernel/stacktrace.c:stack_trace_save_tsk_reliable
  - kernel/stacktrace.c:stack_trace_save_tsk
```
```
In kernel/futex.c (ffffffff8115c399)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - kernel/futex.c:exit_pi_state_list
```
```
In kernel/bpf/btf.c (ffffffff812260e3)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_fd_by_id
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff8123014c)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_get
```
```
In kernel/events/core.c (ffffffff81234521)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_ctx_lock_double
  - kernel/events/core.c:ring_buffer_get
  - kernel/events/core.c:perf_lock_task_context
```
```
In kernel/events/ring_buffer.c (ffffffff81243e2a)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_begin
```
```
In mm/zswap.c (ffffffff812c232e)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_pool_release
  - mm/zswap.c:zswap_pool_find_get
  - mm/zswap.c:zswap_pool_last_get
```
```
In mm/memcontrol.c (ffffffff812f5e75)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_id_get_online
```
```
In fs/notify/mark.c (ffffffff81367b09)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_prepare_user_wait
```
```
In fs/io_uring.c (ffffffff81385e5d)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_cancel_files
  - fs/io_uring.c:io_link_timeout_fn
```
```
In fs/io-wq.c (ffffffff8138b63a)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - fs/io-wq.c:io_wq_get
```
```
In fs/crypto/keyring.c (ffffffff81392671)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - fs/crypto/keyring.c:do_add_master_key
```
```
In fs/posix_acl.c (ffffffff813a5d98)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - fs/posix_acl.c:get_cached_acl
```
```
In fs/proc/array.c (ffffffff813c2a6c)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In fs/proc/proc_net.c (ffffffff813c9a78)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_net
```
```
In fs/configfs/item.c (ffffffff813d78f0)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_get_unless_zero
```
```
In fs/debugfs/file.c (ffffffff8148250b)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In ipc/util.c (ffffffff8148716c)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - ipc/util.c:ipc_rcu_getref
```
```
In security/keys/key.c (ffffffff81497686)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - security/keys/key.c:key_lookup
```
```
In security/keys/keyring.c (ffffffff81498f04)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/apparmor/apparmorfs.c (ffffffff814ed7be)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_attach_show
  - security/apparmor/apparmorfs.c:seq_profile_mode_show
  - security/apparmor/apparmorfs.c:seq_profile_name_show
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:begin_current_label_crit_section
```
```
In security/apparmor/task.c (ffffffff814f15da)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_get_task_label
```
```
In security/apparmor/domain.c (ffffffff814f8fa9)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:find_attach
  - security/apparmor/domain.c:find_attach
  - security/apparmor/domain.c:find_attach
```
```
In security/apparmor/policy.c (ffffffff814fb734)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:update_to_newest_parent
  - security/apparmor/policy.c:update_to_newest_parent
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_find_child
```
```
In security/apparmor/procattr.c (ffffffff814ff348)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff8150143d)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_sock_graft
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_create
  - security/apparmor/lsm.c:apparmor_unix_may_send
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_setrlimit
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_sb_umount
  - security/apparmor/lsm.c:apparmor_sb_mount
  - security/apparmor/lsm.c:apparmor_file_mprotect
  - security/apparmor/lsm.c:apparmor_mmap_file
  - security/apparmor/lsm.c:apparmor_file_lock
  - security/apparmor/lsm.c:apparmor_file_permission
  - security/apparmor/lsm.c:apparmor_file_receive
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_inode_getattr
  - security/apparmor/lsm.c:apparmor_path_chown
  - security/apparmor/lsm.c:apparmor_path_chmod
  - security/apparmor/lsm.c:apparmor_path_symlink
  - security/apparmor/lsm.c:apparmor_path_truncate
  - security/apparmor/lsm.c:apparmor_path_mknod
  - security/apparmor/lsm.c:apparmor_path_rmdir
  - security/apparmor/lsm.c:apparmor_path_mkdir
  - security/apparmor/lsm.c:apparmor_path_unlink
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/lsm.c:apparmor_cred_transfer
  - security/apparmor/lsm.c:apparmor_cred_prepare
```
```
In security/apparmor/resource.c (ffffffff81505934)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff815074b8)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:aa_file_perm
```
```
In security/apparmor/label.c (ffffffff8150a497)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:labelset_next_stale
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:__label_find_merge
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:__vec_find
  - security/apparmor/label.c:__label_insert
```
```
In security/apparmor/mount.c (ffffffff8150dc79)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
```
```
In security/apparmor/net.c (ffffffff8150f3f9)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sk_perm
```
```
In security/apparmor/af_unix.c (ffffffff8150f9c9)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:begin_current_label_crit_section
```
```
In block/blk-mq.c (ffffffff8154f202)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
```
```
In block/bsg-lib.c (ffffffff815695c9)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_job_get
```
```
In lib/syscall.c (ffffffff815dc5d7)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
```
```
In lib/klist.c (ffffffff815ea0db)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
```
```
In lib/kobject.c (ffffffff815eaadb)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - lib/kobject.c:kobject_get_unless_zero
```
```
In drivers/dma/dmaengine.c (ffffffff81707811)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_chan_get
```
```
In drivers/tty/vt/vt.c (ffffffff81750fd8)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:con_install
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81754fe4)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_get_by_index
```
```
In drivers/char/hw_random/core.c (ffffffff817791bb)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:hwrng_init
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81825e09)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff81827b40)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
```
```
In drivers/dma-buf/dma-resv.c (ffffffff818296cc)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
```
```
In drivers/dma-buf/sw_sync.c (ffffffff8182bf3a)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_pt_create
```
```
In drivers/scsi/scsi_scan.c (ffffffff818398d4)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/edac/ghes_edac.c (ffffffff8198d4cf)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - drivers/edac/ghes_edac.c:ghes_edac_register
```
```
In net/core/sock.c (ffffffff819e6aea)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
```
```
In net/core/skbuff.c (ffffffff819ee2da)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_complete_wifi_ack
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/core/skbuff.c:skb_clone_sk
```
```
In net/core/net_namespace.c (ffffffff819f99c4)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - net/core/net_namespace.c:get_net_ns_by_id
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/neighbour.c (ffffffff81a11b7d)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/filter.c (ffffffff81a2d11e)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_assign
  - net/core/filter.c:sk_filter_charge
```
```
In net/core/fib_rules.c (ffffffff81a3f9bc)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_lookup
```
```
In net/core/sock_map.c (ffffffff81a4efe3)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_lookup
  - net/core/sock_map.c:sock_map_lookup
  - net/core/sock_map.c:sock_map_link_no_progs
  - net/core/sock_map.c:sock_map_link
```
```
In net/core/bpf_sk_storage.c (ffffffff81a6118d)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
```
```
In net/sched/cls_api.c (ffffffff81a6c91d)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_refcnt_get
```
```
In net/ipv4/route.c (ffffffff81a92e2c)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/inetpeer.c (ffffffff81a97571)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/inet_hashtables.c (ffffffff81aa3316)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81aa4f06)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/tcp_input.c (ffffffff81ab0b82)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/udp.c (ffffffff81ad7c3d)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp4_lib_lookup
```
```
In net/ipv4/fib_semantics.c (ffffffff81aef22b)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/inet_fragment.c (ffffffff81af6419)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81afcfa3)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_create_group
```
```
In net/ipv4/tcp_bpf.c (ffffffff81b09322)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81b0b256)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_getdef
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b1457f)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_lookup
```
```
In net/xfrm/xfrm_state.c (ffffffff81b1c83c)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/ipv6/addrconf.c (ffffffff81b332ba)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
```
```
In net/ipv6/route.c (ffffffff81b49c62)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - net/ipv6/route.c:__rt6_purge_dflt_routers
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_rt_pcpu_alloc
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/udp.c (ffffffff81b58af5)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp6_lib_lookup
```
```
In net/ipv6/raw.c (ffffffff81b5cbbb)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/calipso.c (ffffffff81b7d402)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_sock_delattr
  - net/ipv6/calipso.c:calipso_sock_setattr
  - net/ipv6/calipso.c:calipso_sock_getattr
  - net/ipv6/calipso.c:calipso_opt_update
  - net/ipv6/calipso.c:calipso_doi_getdef
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81b847a7)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
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
In arch/x86/kernel/process.c (ffffffff81040f0b)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:get_wchan
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff8106897f)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
```
```
In kernel/sched/core.c (ffffffff810d9644)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
```
```
In kernel/sched/fair.c (ffffffff810ed241)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_group
```
```
In kernel/locking/qspinlock.c (ffffffff8110ce7b)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
```
```
In kernel/stacktrace.c (ffffffff8113d712)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - kernel/stacktrace.c:stack_trace_save_tsk_reliable
  - kernel/stacktrace.c:stack_trace_save_tsk
```
```
In kernel/futex.c (ffffffff81158699)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - kernel/futex.c:exit_pi_state_list
```
```
In kernel/bpf/btf.c (ffffffff8122cc73)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_fd_by_id
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff812385fc)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_get
```
```
In kernel/events/core.c (ffffffff8123ee52)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_ctx_lock_double
  - kernel/events/core.c:ring_buffer_get
  - kernel/events/core.c:perf_lock_task_context
```
```
In kernel/events/ring_buffer.c (ffffffff8124e4ba)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_begin
```
```
In mm/zswap.c (ffffffff812ce027)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_pool_release
  - mm/zswap.c:zswap_pool_find_get
  - mm/zswap.c:zswap_pool_last_get
```
```
In mm/memcontrol.c (ffffffff81301275)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_id_get_online
```
```
In fs/notify/mark.c (ffffffff81374e89)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_prepare_user_wait
```
```
In fs/io_uring.c (ffffffff813919fa)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - fs/io_uring.c:io_link_timeout_fn
```
```
In fs/io-wq.c (ffffffff8139c81a)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - fs/io-wq.c:io_wq_get
```
```
In fs/crypto/keyring.c (ffffffff813a39f2)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - fs/crypto/keyring.c:do_add_master_key
```
```
In fs/posix_acl.c (ffffffff813b6ad9)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - fs/posix_acl.c:get_cached_acl
```
```
In fs/proc/array.c (ffffffff813d4bfa)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In fs/proc/proc_net.c (ffffffff813dbace)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:seq_open_net
```
```
In fs/configfs/item.c (ffffffff813e94f0)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_get_unless_zero
```
```
In fs/debugfs/file.c (ffffffff8149fb9b)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In ipc/util.c (ffffffff814a478c)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - ipc/util.c:ipc_rcu_getref
```
```
In security/keys/key.c (ffffffff814b5136)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - security/keys/key.c:key_lookup
```
```
In security/keys/keyring.c (ffffffff814b6984)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/apparmor/apparmorfs.c (ffffffff8150ae3e)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_attach_show
  - security/apparmor/apparmorfs.c:seq_profile_mode_show
  - security/apparmor/apparmorfs.c:seq_profile_name_show
  - security/apparmor/apparmorfs.c:begin_current_label_crit_section
```
```
In security/apparmor/task.c (ffffffff8150e87a)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_get_task_label
```
```
In security/apparmor/domain.c (ffffffff815160e9)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:find_attach
  - security/apparmor/domain.c:find_attach
  - security/apparmor/domain.c:find_attach
```
```
In security/apparmor/policy.c (ffffffff81518781)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_find_child
```
```
In security/apparmor/procattr.c (ffffffff8151c588)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff8152161d)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_sock_graft
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_create
  - security/apparmor/lsm.c:apparmor_unix_may_send
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_setrlimit
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_sb_umount
  - security/apparmor/lsm.c:apparmor_sb_mount
  - security/apparmor/lsm.c:apparmor_file_mprotect
  - security/apparmor/lsm.c:apparmor_mmap_file
  - security/apparmor/lsm.c:apparmor_file_lock
  - security/apparmor/lsm.c:apparmor_file_permission
  - security/apparmor/lsm.c:apparmor_file_receive
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_inode_getattr
  - security/apparmor/lsm.c:apparmor_path_chown
  - security/apparmor/lsm.c:apparmor_path_chmod
  - security/apparmor/lsm.c:apparmor_path_symlink
  - security/apparmor/lsm.c:apparmor_path_truncate
  - security/apparmor/lsm.c:apparmor_path_mknod
  - security/apparmor/lsm.c:apparmor_path_rmdir
  - security/apparmor/lsm.c:apparmor_path_mkdir
  - security/apparmor/lsm.c:apparmor_path_unlink
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/lsm.c:apparmor_cred_transfer
  - security/apparmor/lsm.c:apparmor_cred_prepare
```
```
In security/apparmor/resource.c (ffffffff81522a69)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff81524568)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:aa_file_perm
```
```
In security/apparmor/label.c (ffffffff8152730d)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:labelset_next_stale
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:__label_find_merge
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:__vec_find
  - security/apparmor/label.c:__label_insert
```
```
In security/apparmor/mount.c (ffffffff8152aadf)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
```
```
In security/apparmor/net.c (ffffffff8152c239)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sk_perm
```
```
In security/apparmor/af_unix.c (ffffffff8152c80d)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:begin_current_label_crit_section
```
```
In block/blk-mq.c (ffffffff8156b1b2)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
```
```
In block/bsg-lib.c (ffffffff81584049)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_job_get
```
```
In lib/syscall.c (ffffffff815fa257)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
```
```
In lib/klist.c (ffffffff8160ea1b)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
```
```
In lib/kobject.c (ffffffff8160f3fb)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - lib/kobject.c:kobject_get_unless_zero
```
```
In drivers/dma/dmaengine.c (ffffffff81724a61)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_chan_get
```
```
In drivers/tty/vt/vt.c (ffffffff8176ca08)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:con_install
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff817702e4)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_get_by_index
```
```
In drivers/char/hw_random/core.c (ffffffff817939cb)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:hwrng_init
```
```
In drivers/dma-buf/dma-buf.c (ffffffff818367fb)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff818385b5)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
```
```
In drivers/dma-buf/dma-resv.c (ffffffff818393bd)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
```
```
In drivers/dma-buf/sw_sync.c (ffffffff8183cf9a)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_pt_create
```
```
In drivers/scsi/scsi_scan.c (ffffffff8184a154)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/edac/ghes_edac.c (ffffffff8199109c)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - drivers/edac/ghes_edac.c:ghes_edac_register
```
```
In net/core/sock.c (ffffffff819e631a)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
```
```
In net/core/skbuff.c (ffffffff819edf7a)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_complete_wifi_ack
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/core/skbuff.c:skb_clone_sk
```
```
In net/core/net_namespace.c (ffffffff819f950a)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - net/core/net_namespace.c:get_net_ns_by_id
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/neighbour.c (ffffffff81a11edd)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/filter.c (ffffffff81a2eea2)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_assign
  - net/core/filter.c:sk_filter_charge
```
```
In net/core/fib_rules.c (ffffffff81a42682)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_lookup
```
```
In net/core/sock_map.c (ffffffff81a54bb1)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_lookup
  - net/core/sock_map.c:sock_map_lookup
  - net/core/sock_map.c:sock_map_link_no_progs
  - net/core/sock_map.c:sock_map_link
```
```
In net/core/bpf_sk_storage.c (ffffffff81a69fe5)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
```
```
In net/sched/cls_api.c (ffffffff81a752c7)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_refcnt_get
```
```
In net/ipv4/route.c (ffffffff81a9ccda)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/inetpeer.c (ffffffff81aa1531)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/inet_hashtables.c (ffffffff81aad846)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81aaf569)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/tcp_input.c (ffffffff81abbbd2)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/udp.c (ffffffff81ae428d)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp4_lib_lookup
```
```
In net/ipv4/fib_semantics.c (ffffffff81afc173)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/inet_fragment.c (ffffffff81b0328a)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81b0af5e)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_create_group
```
```
In net/ipv4/tcp_bpf.c (ffffffff81b17b45)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81b194f6)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_getdef
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b22923)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_lookup
```
```
In net/xfrm/xfrm_state.c (ffffffff81b2b018)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/ipv6/addrconf.c (ffffffff81b41be2)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
```
```
In net/ipv6/route.c (ffffffff81b58882)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - net/ipv6/route.c:__rt6_purge_dflt_routers
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_rt_pcpu_alloc
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/udp.c (ffffffff81b6712a)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp6_lib_lookup
```
```
In net/ipv6/raw.c (ffffffff81b6b3fd)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/calipso.c (ffffffff81b8c5a2)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_sock_delattr
  - net/ipv6/calipso.c:calipso_sock_setattr
  - net/ipv6/calipso.c:calipso_sock_getattr
  - net/ipv6/calipso.c:calipso_opt_update
  - net/ipv6/calipso.c:calipso_doi_getdef
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81b94107)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In net/mptcp/token.c (ffffffff81bc5ab0)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_iter_next
  - net/mptcp/token.c:mptcp_token_get_sock
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
In arch/x86/kernel/process.c (ffffffff8104290b)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:get_wchan
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81068bc7)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
```
```
In kernel/sched/core.c (ffffffff810daf06)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
```
```
In kernel/sched/fair.c (ffffffff810f099f)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_group
```
```
In kernel/locking/qspinlock.c (ffffffff8110ebc0)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
```
```
In kernel/stacktrace.c (ffffffff8113e962)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - kernel/stacktrace.c:stack_trace_save_tsk_reliable
  - kernel/stacktrace.c:stack_trace_save_tsk
```
```
In kernel/futex.c (ffffffff81159919)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - kernel/futex.c:exit_pi_state_list
```
```
In kernel/bpf/btf.c (ffffffff81231a23)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_fd_by_id
```
```
In kernel/bpf/stackmap.c (ffffffff81237c94)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:bpf_get_task_stack
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff8123cdec)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_get
```
```
In kernel/events/core.c (ffffffff8124de96)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:ring_buffer_get
  - kernel/events/core.c:perf_lock_task_context
```
```
In kernel/events/ring_buffer.c (ffffffff81252dba)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_begin
```
```
In mm/zswap.c (ffffffff812d4c58)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_release
```
```
In mm/memcontrol.c (ffffffff81307575)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_id_get_online
```
```
In fs/notify/mark.c (ffffffff8137b849)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_prepare_user_wait
```
```
In fs/io-wq.c (ffffffff813a2382)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - fs/io-wq.c:io_wqe_activate_free_worker
```
```
In fs/crypto/keyring.c (ffffffff813aac32)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - fs/crypto/keyring.c:do_add_master_key
```
```
In fs/posix_acl.c (ffffffff813bdb39)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - fs/posix_acl.c:get_cached_acl
```
```
In fs/proc/array.c (ffffffff813dba36)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In fs/proc/proc_net.c (ffffffff813e29ee)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:seq_open_net
```
```
In fs/configfs/item.c (ffffffff813f0060)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_get_unless_zero
```
```
In fs/debugfs/file.c (ffffffff814a5b9b)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In ipc/util.c (ffffffff814aa75c)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - ipc/util.c:ipc_rcu_getref
```
```
In security/keys/key.c (ffffffff814bafe6)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - security/keys/key.c:key_lookup
```
```
In security/keys/keyring.c (ffffffff814bc7d0)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/apparmor/apparmorfs.c (ffffffff815115ba)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_attach_show
  - security/apparmor/apparmorfs.c:seq_profile_mode_show
  - security/apparmor/apparmorfs.c:seq_profile_name_show
  - security/apparmor/apparmorfs.c:begin_current_label_crit_section
```
```
In security/apparmor/task.c (ffffffff81515276)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_get_task_label
```
```
In security/apparmor/domain.c (ffffffff8151ca6f)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:find_attach
  - security/apparmor/domain.c:find_attach
  - security/apparmor/domain.c:find_attach
```
```
In security/apparmor/policy.c (ffffffff8151efd9)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_find_child
```
```
In security/apparmor/procattr.c (ffffffff81522d5c)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff81527a0d)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_sock_graft
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_create
  - security/apparmor/lsm.c:apparmor_unix_may_send
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_setrlimit
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_sb_umount
  - security/apparmor/lsm.c:apparmor_sb_mount
  - security/apparmor/lsm.c:apparmor_file_mprotect
  - security/apparmor/lsm.c:apparmor_mmap_file
  - security/apparmor/lsm.c:apparmor_file_lock
  - security/apparmor/lsm.c:apparmor_file_permission
  - security/apparmor/lsm.c:apparmor_file_receive
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_path_symlink
  - security/apparmor/lsm.c:apparmor_path_mknod
  - security/apparmor/lsm.c:apparmor_path_rmdir
  - security/apparmor/lsm.c:apparmor_path_mkdir
  - security/apparmor/lsm.c:apparmor_path_unlink
  - security/apparmor/lsm.c:common_perm_cond
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/lsm.c:apparmor_cred_transfer
  - security/apparmor/lsm.c:apparmor_cred_prepare
```
```
In security/apparmor/resource.c (ffffffff81528c45)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff8152a742)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:aa_file_perm
```
```
In security/apparmor/label.c (ffffffff8152cfd9)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:__vec_find
  - security/apparmor/label.c:__label_insert
```
```
In security/apparmor/mount.c (ffffffff81530cec)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
```
```
In security/apparmor/net.c (ffffffff815324d9)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sk_perm
```
```
In security/apparmor/af_unix.c (ffffffff81532b49)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:begin_current_label_crit_section
```
```
In security/landlock/fs.c (ffffffff815390f0)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - security/landlock/fs.c:landlock_append_fs_rule
```
```
In block/blk-mq-tag.c (ffffffff81578ebf)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_find_and_get_req
```
```
In block/bsg-lib.c (ffffffff8158ae49)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_job_get
```
```
In lib/syscall.c (ffffffff815dce37)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
```
```
In lib/klist.c (ffffffff815f21ab)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
```
```
In lib/kobject.c (ffffffff815f2b3b)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - lib/kobject.c:kobject_get_unless_zero
```
```
In drivers/dma/dmaengine.c (ffffffff81705d21)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_chan_get
```
```
In drivers/tty/vt/vt.c (ffffffff81750598)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:con_install
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81753d94)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_get_by_index
```
```
In drivers/char/hw_random/core.c (ffffffff81776b81)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
```
```
In drivers/dma-buf/dma-buf.c (ffffffff818199cb)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff8181b895)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
```
```
In drivers/dma-buf/dma-resv.c (ffffffff8181c675)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
```
```
In drivers/dma-buf/sw_sync.c (ffffffff8181ff76)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_pt_create
```
```
In drivers/scsi/scsi_scan.c (ffffffff8182d8d4)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/vfio/vfio.c (ffffffff8188d92e)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_get_device_fd
  - drivers/vfio/vfio.c:vfio_group_get_device
```
```
In drivers/edac/ghes_edac.c (ffffffff8197560c)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - drivers/edac/ghes_edac.c:ghes_edac_register
```
```
In net/core/sock.c (ffffffff819cae81)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - net/core/sock.c:skb_orphan_partial
```
```
In net/core/skbuff.c (ffffffff819d773a)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_complete_wifi_ack
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/core/skbuff.c:skb_clone_sk
```
```
In net/core/net_namespace.c (ffffffff819df66a)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - net/core/net_namespace.c:get_net_ns_by_id
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/neighbour.c (ffffffff819f8b3d)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/filter.c (ffffffff81a16452)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_assign
  - net/core/filter.c:sk_filter_charge
```
```
In net/core/fib_rules.c (ffffffff81a2738e)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_lookup
```
```
In net/core/sock_map.c (ffffffff81a515a2)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_close
  - net/core/sock_map.c:sock_hash_lookup
  - net/core/sock_map.c:sock_map_lookup
  - net/core/sock_map.c:sock_map_link
```
```
In net/core/bpf_sk_storage.c (ffffffff81a524e5)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
```
```
In net/sched/cls_api.c (ffffffff81a5dc67)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_refcnt_get
```
```
In net/ipv4/route.c (ffffffff81a87d9c)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/inetpeer.c (ffffffff81a8c481)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/inet_hashtables.c (ffffffff81a98911)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81a9a879)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/tcp_input.c (ffffffff81aa6b92)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/udp.c (ffffffff81acf428)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp4_lib_lookup
```
```
In net/ipv4/fib_semantics.c (ffffffff81ae7883)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/inet_fragment.c (ffffffff81aeea32)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81af62fa)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_create_group
```
```
In net/ipv4/tcp_bpf.c (ffffffff81b0571d)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
```
In net/ipv4/udp_bpf.c (ffffffff81b05d1b)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - net/ipv4/udp_bpf.c:udp_bpf_recvmsg
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81b06f86)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_getdef
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b1051f)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_lookup
```
```
In net/xfrm/xfrm_state.c (ffffffff81b18c49)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/ipv6/addrconf.c (ffffffff81b2f8ce)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
```
```
In net/ipv6/route.c (ffffffff81b46b6d)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/udp.c (ffffffff81b55304)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp6_lib_lookup
```
```
In net/ipv6/raw.c (ffffffff81b59750)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/calipso.c (ffffffff81b7b5d8)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_sock_delattr
  - net/ipv6/calipso.c:calipso_sock_setattr
  - net/ipv6/calipso.c:calipso_sock_getattr
  - net/ipv6/calipso.c:calipso_opt_update
  - net/ipv6/calipso.c:calipso_doi_getdef
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81b83217)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In net/mptcp/token.c (ffffffff81bb662f)
Location: include/asm-generic/atomic-instrumented.h:725
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_iter_next
  - net/mptcp/token.c:mptcp_token_get_sock
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
In arch/x86/kernel/process.c (ffffffff81048c79)
Location: include/linux/atomic/atomic-instrumented.h:525
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:get_wchan
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81072f92)
Location: include/linux/atomic/atomic-instrumented.h:525
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
```
```
In kernel/sched/core.c (ffffffff810eebf7)
Location: include/linux/atomic/atomic-instrumented.h:525
Inline: True
```
```
In kernel/sched/fair.c (ffffffff8110941f)
Location: include/linux/atomic/atomic-instrumented.h:525
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_group
```
```
In kernel/locking/qspinlock.c (ffffffff8112e3f0)
Location: include/linux/atomic/atomic-instrumented.h:525
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
```
```
In kernel/stacktrace.c (ffffffff81161df2)
Location: include/linux/atomic/atomic-instrumented.h:525
Inline: True
Inline callers:
  - kernel/stacktrace.c:stack_trace_save_tsk_reliable
  - kernel/stacktrace.c:stack_trace_save_tsk
```
```
In kernel/futex.c (ffffffff8117e839)
Location: include/linux/atomic/atomic-instrumented.h:525
Inline: True
Inline callers:
  - kernel/futex.c:exit_pi_state_list
  - kernel/futex.c:get_pi_state
```
```
In kernel/bpf/btf.c (ffffffff8126a9c3)
Location: include/linux/atomic/atomic-instrumented.h:525
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_fd_by_id
```
```
In kernel/bpf/stackmap.c (ffffffff81272264)
Location: include/linux/atomic/atomic-instrumented.h:525
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:bpf_get_task_stack
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff8127786c)
Location: include/linux/atomic/atomic-instrumented.h:525
Inline: True
Inline callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_get
```
```
In kernel/events/core.c (ffffffff81288be7)
Location: include/linux/atomic/atomic-instrumented.h:525
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:ring_buffer_get
  - kernel/events/core.c:perf_lock_task_context
```
```
In kernel/events/ring_buffer.c (ffffffff8128e6aa)
Location: include/linux/atomic/atomic-instrumented.h:525
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_begin
```
```
In mm/zswap.c (ffffffff8131afc6)
Location: include/linux/atomic/atomic-instrumented.h:525
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_release
```
```
In mm/memcontrol.c (ffffffff813512e5)
Location: include/linux/atomic/atomic-instrumented.h:525
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_id_get_online
```
```
In fs/notify/mark.c (ffffffff813c8606)
Location: include/linux/atomic/atomic-instrumented.h:525
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_prepare_user_wait
```
```
In fs/io-wq.c (ffffffff813f18f3)
Location: include/linux/atomic/atomic-instrumented.h:525
Inline: True
Inline callers:
  - fs/io-wq.c:io_queue_worker_create
  - fs/io-wq.c:io_wqe_activate_free_worker
```
```
In fs/crypto/keyring.c (ffffffff813fa4c2)
Location: include/linux/atomic/atomic-instrumented.h:525
Inline: True
Inline callers:
  - fs/crypto/keyring.c:do_add_master_key
```
```
In fs/posix_acl.c (ffffffff8140d929)
Location: include/linux/atomic/atomic-instrumented.h:525
Inline: True
Inline callers:
  - fs/posix_acl.c:get_cached_acl
```
```
In fs/proc/array.c (ffffffff8142d0d0)
Location: include/linux/atomic/atomic-instrumented.h:525
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In fs/proc/proc_net.c (ffffffff814344fe)
Location: include/linux/atomic/atomic-instrumented.h:525
Inline: True
Inline callers:
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:seq_open_net
```
```
In fs/configfs/item.c (ffffffff81441f50)
Location: include/linux/atomic/atomic-instrumented.h:525
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_get_unless_zero
```
```
In fs/debugfs/file.c (ffffffff814fdd3b)
Location: include/linux/atomic/atomic-instrumented.h:525
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In ipc/util.c (ffffffff81502c1c)
Location: include/linux/atomic/atomic-instrumented.h:525
Inline: True
Inline callers:
  - ipc/util.c:ipc_rcu_getref
```
```
In ipc/shm.c (ffffffff8150c510)
Location: include/linux/atomic/atomic-instrumented.h:525
Inline: True
Inline callers:
  - ipc/shm.c:exit_shm
```
```
In security/keys/key.c (ffffffff81513816)
Location: include/linux/atomic/atomic-instrumented.h:525
Inline: True
Inline callers:
  - security/keys/key.c:key_lookup
```
```
In security/keys/keyring.c (ffffffff815151f0)
Location: include/linux/atomic/atomic-instrumented.h:525
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/apparmor/apparmorfs.c (ffffffff8156f1ba)
Location: include/linux/atomic/atomic-instrumented.h:525
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_attach_show
  - security/apparmor/apparmorfs.c:seq_profile_mode_show
  - security/apparmor/apparmorfs.c:seq_profile_name_show
  - security/apparmor/apparmorfs.c:begin_current_label_crit_section
```
```
In security/apparmor/task.c (ffffffff81573226)
Location: include/linux/atomic/atomic-instrumented.h:525
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_get_task_label
```
```
In security/apparmor/domain.c (ffffffff8157ab40)
Location: include/linux/atomic/atomic-instrumented.h:525
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:find_attach
  - security/apparmor/domain.c:find_attach
  - security/apparmor/domain.c:find_attach
```
```
In security/apparmor/policy.c (ffffffff8157d179)
Location: include/linux/atomic/atomic-instrumented.h:525
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_find_child
```
```
In security/apparmor/procattr.c (ffffffff81580fcc)
Location: include/linux/atomic/atomic-instrumented.h:525
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff81585c9d)
Location: include/linux/atomic/atomic-instrumented.h:525
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_sock_graft
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_create
  - security/apparmor/lsm.c:apparmor_unix_may_send
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_setrlimit
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_sb_umount
  - security/apparmor/lsm.c:apparmor_sb_mount
  - security/apparmor/lsm.c:apparmor_file_mprotect
  - security/apparmor/lsm.c:apparmor_mmap_file
  - security/apparmor/lsm.c:apparmor_file_lock
  - security/apparmor/lsm.c:apparmor_file_permission
  - security/apparmor/lsm.c:apparmor_file_receive
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_path_symlink
  - security/apparmor/lsm.c:apparmor_path_mknod
  - security/apparmor/lsm.c:apparmor_path_rmdir
  - security/apparmor/lsm.c:apparmor_path_mkdir
  - security/apparmor/lsm.c:apparmor_path_unlink
  - security/apparmor/lsm.c:common_perm_cond
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/lsm.c:apparmor_cred_transfer
  - security/apparmor/lsm.c:apparmor_cred_prepare
```
```
In security/apparmor/resource.c (ffffffff81586f6e)
Location: include/linux/atomic/atomic-instrumented.h:525
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff81588ae2)
Location: include/linux/atomic/atomic-instrumented.h:525
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:aa_file_perm
```
```
In security/apparmor/label.c (ffffffff8158b3c9)
Location: include/linux/atomic/atomic-instrumented.h:525
Inline: True
Inline callers:
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:__vec_find
  - security/apparmor/label.c:__label_insert
```
```
In security/apparmor/mount.c (ffffffff8158f12c)
Location: include/linux/atomic/atomic-instrumented.h:525
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
```
```
In security/apparmor/net.c (ffffffff81590a59)
Location: include/linux/atomic/atomic-instrumented.h:525
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sk_perm
```
```
In security/apparmor/af_unix.c (ffffffff815910c9)
Location: include/linux/atomic/atomic-instrumented.h:525
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:begin_current_label_crit_section
```
```
In security/landlock/fs.c (ffffffff81597930)
Location: include/linux/atomic/atomic-instrumented.h:525
Inline: True
Inline callers:
  - security/landlock/fs.c:landlock_append_fs_rule
```
```
In block/blk-mq-tag.c (ffffffff815de112)
Location: include/linux/atomic/atomic-instrumented.h:525
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_find_and_get_req
```
```
In block/bsg-lib.c (ffffffff815efe39)
Location: include/linux/atomic/atomic-instrumented.h:525
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_job_get
```
```
In lib/syscall.c (ffffffff81648797)
Location: include/linux/atomic/atomic-instrumented.h:525
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
```
```
In lib/klist.c (ffffffff8165f31b)
Location: include/linux/atomic/atomic-instrumented.h:525
Inline: True
```
```
In lib/kobject.c (ffffffff8165fd1b)
Location: include/linux/atomic/atomic-instrumented.h:525
Inline: True
Inline callers:
  - lib/kobject.c:kobject_get_unless_zero
```
```
In drivers/dma/dmaengine.c (ffffffff81781601)
Location: include/linux/atomic/atomic-instrumented.h:525
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_chan_get
```
```
In drivers/tty/vt/vt.c (ffffffff817d2e37)
Location: include/linux/atomic/atomic-instrumented.h:525
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:con_install
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff817d72d4)
Location: include/linux/atomic/atomic-instrumented.h:525
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_get_by_index
```
```
In drivers/char/hw_random/core.c (ffffffff817fc551)
Location: include/linux/atomic/atomic-instrumented.h:525
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:set_current_rng
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff818a5d25)
Location: include/linux/atomic/atomic-instrumented.h:525
Inline: True
```
```
In drivers/dma-buf/dma-resv.c (ffffffff818a6a3e)
Location: include/linux/atomic/atomic-instrumented.h:525
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
```
```
In drivers/dma-buf/sw_sync.c (ffffffff818aa636)
Location: include/linux/atomic/atomic-instrumented.h:525
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_pt_create
```
```
In drivers/scsi/scsi_scan.c (ffffffff818b9324)
Location: include/linux/atomic/atomic-instrumented.h:525
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/vfio/vfio.c (ffffffff81920f78)
Location: include/linux/atomic/atomic-instrumented.h:525
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_get_device_fd
  - drivers/vfio/vfio.c:vfio_group_get_device
```
```
In drivers/edac/ghes_edac.c (ffffffff81a1e318)
Location: include/linux/atomic/atomic-instrumented.h:525
Inline: True
Inline callers:
  - drivers/edac/ghes_edac.c:ghes_edac_register
```
```
In net/core/sock.c (ffffffff81a7a4b1)
Location: include/linux/atomic/atomic-instrumented.h:525
Inline: True
Inline callers:
  - net/core/sock.c:skb_orphan_partial
```
```
In net/core/skbuff.c (ffffffff81a85f7a)
Location: include/linux/atomic/atomic-instrumented.h:525
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_complete_wifi_ack
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/core/skbuff.c:skb_clone_sk
```
```
In net/core/net_namespace.c (ffffffff81a8fa4a)
Location: include/linux/atomic/atomic-instrumented.h:525
Inline: True
Inline callers:
  - net/core/net_namespace.c:get_net_ns_by_id
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/neighbour.c (ffffffff81aaa71c)
Location: include/linux/atomic/atomic-instrumented.h:525
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/filter.c (ffffffff81acccfc)
Location: include/linux/atomic/atomic-instrumented.h:525
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_assign
  - net/core/filter.c:sk_filter_charge
```
```
In net/core/sock_reuseport.c (ffffffff81ad1be6)
Location: include/linux/atomic/atomic-instrumented.h:525
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_migrate_sock
```
```
In net/core/fib_rules.c (ffffffff81adc121)
Location: include/linux/atomic/atomic-instrumented.h:525
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_lookup
```
```
In net/core/devlink.c (ffffffff81b027f6)
Location: include/linux/atomic/atomic-instrumented.h:525
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_pernet_pre_exit
  - net/core/devlink.c:devlink_nl_cmd_trap_policer_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_info_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_param_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_port_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_rate_get_dumpit
  - net/core/devlink.c:devlink_get_from_attrs
```
```
In net/core/sock_map.c (ffffffff81b09522)
Location: include/linux/atomic/atomic-instrumented.h:525
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_close
  - net/core/sock_map.c:sock_hash_lookup
  - net/core/sock_map.c:sock_map_lookup
  - net/core/sock_map.c:sock_map_link
```
```
In net/core/bpf_sk_storage.c (ffffffff81b0b5ee)
Location: include/linux/atomic/atomic-instrumented.h:525
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
```
```
In net/sched/cls_api.c (ffffffff81b16e27)
Location: include/linux/atomic/atomic-instrumented.h:525
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_refcnt_get
```
```
In net/netfilter/nf_queue.c (ffffffff81b3f349)
Location: include/linux/atomic/atomic-instrumented.h:525
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
```
```
In net/ipv4/route.c (ffffffff81b422db)
Location: include/linux/atomic/atomic-instrumented.h:525
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/inetpeer.c (ffffffff81b4749f)
Location: include/linux/atomic/atomic-instrumented.h:525
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/inet_hashtables.c (ffffffff81b53df1)
Location: include/linux/atomic/atomic-instrumented.h:525
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81b55ce9)
Location: include/linux/atomic/atomic-instrumented.h:525
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/tcp_input.c (ffffffff81b63192)
Location: include/linux/atomic/atomic-instrumented.h:525
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/udp.c (ffffffff81b8de48)
Location: include/linux/atomic/atomic-instrumented.h:525
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp4_lib_lookup
```
```
In net/ipv4/fib_semantics.c (ffffffff81ba779e)
Location: include/linux/atomic/atomic-instrumented.h:525
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/inet_fragment.c (ffffffff81baee02)
Location: include/linux/atomic/atomic-instrumented.h:525
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81bb7daa)
Location: include/linux/atomic/atomic-instrumented.h:525
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_create_group
```
```
In net/ipv4/tcp_bpf.c (ffffffff81bc826d)
Location: include/linux/atomic/atomic-instrumented.h:525
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
```
In net/ipv4/udp_bpf.c (ffffffff81bc8a09)
Location: include/linux/atomic/atomic-instrumented.h:525
Inline: True
Inline callers:
  - net/ipv4/udp_bpf.c:udp_bpf_recvmsg
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81bc9e06)
Location: include/linux/atomic/atomic-instrumented.h:525
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_getdef
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bd3e40)
Location: include/linux/atomic/atomic-instrumented.h:525
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_lookup
```
```
In net/xfrm/xfrm_state.c (ffffffff81bdd039)
Location: include/linux/atomic/atomic-instrumented.h:525
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/unix/unix_bpf.c (ffffffff81beb794)
Location: include/linux/atomic/atomic-instrumented.h:525
Inline: True
Inline callers:
  - net/unix/unix_bpf.c:unix_bpf_recvmsg
```
```
In net/ipv6/addrconf.c (ffffffff81bf5c4e)
Location: include/linux/atomic/atomic-instrumented.h:525
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
```
```
In net/ipv6/route.c (ffffffff81c0ddbd)
Location: include/linux/atomic/atomic-instrumented.h:525
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/udp.c (ffffffff81c1ddd1)
Location: include/linux/atomic/atomic-instrumented.h:525
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp6_lib_lookup
```
```
In net/ipv6/raw.c (ffffffff81c20d79)
Location: include/linux/atomic/atomic-instrumented.h:525
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/calipso.c (ffffffff81c46591)
Location: include/linux/atomic/atomic-instrumented.h:525
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_sock_delattr
  - net/ipv6/calipso.c:calipso_sock_setattr
  - net/ipv6/calipso.c:calipso_sock_getattr
  - net/ipv6/calipso.c:calipso_opt_update
  - net/ipv6/calipso.c:calipso_doi_getdef
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81c4f2e7)
Location: include/linux/atomic/atomic-instrumented.h:525
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In net/mptcp/token.c (ffffffff81c8563f)
Location: include/linux/atomic/atomic-instrumented.h:525
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_iter_next
  - net/mptcp/token.c:mptcp_token_get_sock
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
In arch/x86/kernel/process.c (ffffffff81051f7e)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__get_wchan
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff8108160a)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
```
```
In kernel/sched/core.c (ffffffff8110ba63)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
```
```
In kernel/sched/fair.c (ffffffff8111d8f9)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_group
```
```
In kernel/locking/qspinlock.c (ffffffff8114f603)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
```
```
In kernel/stacktrace.c (ffffffff81194cfc)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - kernel/stacktrace.c:stack_trace_save_tsk_reliable
  - kernel/stacktrace.c:stack_trace_save_tsk
```
```
In kernel/futex/core.c (ffffffff811b242b)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - kernel/futex/core.c:exit_pi_state_list
```
```
In kernel/futex/pi.c (ffffffff811b4b46)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - kernel/futex/pi.c:get_pi_state
```
```
In kernel/bpf/btf.c (ffffffff812b7809)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_fd_by_id
```
```
In kernel/bpf/stackmap.c (ffffffff812c1592)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:bpf_get_task_stack
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff812c750b)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_get
```
```
In kernel/events/core.c (ffffffff812dde96)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:ring_buffer_get
  - kernel/events/core.c:perf_lock_task_context
```
```
In kernel/events/ring_buffer.c (ffffffff812e3577)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_begin
```
```
In mm/zswap.c (ffffffff8138604e)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_release
```
```
In mm/memcontrol.c (ffffffff813c9d31)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_id_get_online
```
```
In fs/notify/mark.c (ffffffff8144fbd6)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_prepare_user_wait
```
```
In fs/crypto/keyring.c (ffffffff8146d642)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - fs/crypto/keyring.c:do_add_master_key
```
```
In fs/posix_acl.c (ffffffff81482c10)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - fs/posix_acl.c:get_cached_acl
```
```
In fs/proc/array.c (ffffffff814a6a88)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In fs/proc/proc_net.c (ffffffff814ae617)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:seq_open_net
```
```
In fs/configfs/item.c (ffffffff814bdbb0)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_get_unless_zero
```
```
In fs/debugfs/file.c (ffffffff8158e92b)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In ipc/util.c (ffffffff815941db)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - ipc/util.c:ipc_rcu_getref
```
```
In ipc/shm.c (ffffffff8159e480)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - ipc/shm.c:exit_shm
```
```
In security/keys/key.c (ffffffff815a5cb0)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - security/keys/key.c:key_lookup
```
```
In security/keys/keyring.c (ffffffff815a797f)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/apparmor/apparmorfs.c (ffffffff8160d6f3)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:policy_get_link
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_attach_show
  - security/apparmor/apparmorfs.c:seq_profile_mode_show
  - security/apparmor/apparmorfs.c:seq_profile_name_show
  - security/apparmor/apparmorfs.c:begin_current_label_crit_section
```
```
In security/apparmor/task.c (ffffffff81610529)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_get_task_label
```
```
In security/apparmor/domain.c (ffffffff81618dd7)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:find_attach
  - security/apparmor/domain.c:find_attach
  - security/apparmor/domain.c:find_attach
```
```
In security/apparmor/policy.c (ffffffff8161b7f7)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_current_policy_admin_capable
  - security/apparmor/policy.c:aa_current_policy_view_capable
  - security/apparmor/policy.c:aa_find_child
```
```
In security/apparmor/procattr.c (ffffffff81620183)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff81626824)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_sock_graft
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_unix_may_send
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_task_setrlimit
  - security/apparmor/lsm.c:apparmor_current_getsecid_subj
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_sb_umount
  - security/apparmor/lsm.c:apparmor_sb_mount
  - security/apparmor/lsm.c:apparmor_file_mprotect
  - security/apparmor/lsm.c:apparmor_mmap_file
  - security/apparmor/lsm.c:apparmor_file_lock
  - security/apparmor/lsm.c:apparmor_file_permission
  - security/apparmor/lsm.c:apparmor_file_receive
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_inode_init_security
  - security/apparmor/lsm.c:apparmor_path_symlink
  - security/apparmor/lsm.c:apparmor_path_mknod
  - security/apparmor/lsm.c:apparmor_path_rmdir
  - security/apparmor/lsm.c:apparmor_path_mkdir
  - security/apparmor/lsm.c:apparmor_path_unlink
  - security/apparmor/lsm.c:common_perm_cond
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/lsm.c:apparmor_cred_transfer
  - security/apparmor/lsm.c:apparmor_cred_prepare
  - security/apparmor/lsm.c:begin_current_label_crit_section
```
```
In security/apparmor/resource.c (ffffffff81627397)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff816291b3)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:aa_file_perm
```
```
In security/apparmor/label.c (ffffffff8162c935)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:__vec_find
  - security/apparmor/label.c:__label_insert
  - security/apparmor/label.c:aa_get_current_ns
```
```
In security/apparmor/mount.c (ffffffff81630161)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
```
```
In security/apparmor/net.c (ffffffff81631bb6)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sk_perm
```
```
In security/apparmor/af_unix.c (ffffffff81632c46)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:begin_current_label_crit_section
```
```
In security/landlock/fs.c (ffffffff8163c09f)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - security/landlock/fs.c:landlock_append_fs_rule
```
```
In block/bsg-lib.c (ffffffff816a0f36)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_job_get
```
```
In io_uring/io-wq.c (ffffffff816da2b2)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_queue_worker_create
  - io_uring/io-wq.c:io_wqe_activate_free_worker
```
```
In lib/syscall.c (ffffffff8175ebc7)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
```
```
In lib/klist.c (ffffffff81778eeb)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
```
```
In lib/kobject.c (ffffffff8177985b)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - lib/kobject.c:kobject_get_unless_zero
```
```
In drivers/dma/dmaengine.c (ffffffff818b7faf)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_chan_get
```
```
In drivers/tty/vt/vt.c (ffffffff81910df0)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:con_install
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81915420)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_get_by_index
```
```
In drivers/char/hw_random/core.c (ffffffff8193b1af)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:set_current_rng
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff819efc97)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
```
```
In drivers/dma-buf/dma-resv.c (ffffffff819f07b7)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (ffffffff819f4e28)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_pt_create
```
```
In drivers/scsi/scsi_scan.c (ffffffff81a04fa9)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/vfio/vfio.c (ffffffff81a786e1)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_fops_open
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
  - drivers/vfio/vfio.c:__vfio_register_dev
```
```
In drivers/edac/ghes_edac.c (ffffffff81b86a52)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - drivers/edac/ghes_edac.c:ghes_edac_register
```
```
In net/core/sock.c (ffffffff81bedee2)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - net/core/sock.c:skb_orphan_partial
```
```
In net/core/skbuff.c (ffffffff81bf880a)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_complete_wifi_ack
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/core/skbuff.c:skb_clone_sk
```
```
In net/core/net_namespace.c (ffffffff81c03d47)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - net/core/net_namespace.c:get_net_ns_by_id
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/neighbour.c (ffffffff81c23560)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/filter.c (ffffffff81c499dc)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_assign
  - net/core/filter.c:sk_filter_charge
```
```
In net/core/sock_reuseport.c (ffffffff81c4f459)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_migrate_sock
```
```
In net/core/fib_rules.c (ffffffff81c5d46b)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_lookup
```
```
In net/core/devlink.c (ffffffff81c86c51)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_try_get
```
```
In net/core/sock_map.c (ffffffff81c8f640)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_close
  - net/core/sock_map.c:sock_hash_lookup
  - net/core/sock_map.c:sock_map_lookup
  - net/core/sock_map.c:sock_map_link
```
```
In net/core/bpf_sk_storage.c (ffffffff81c91bee)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
```
```
In net/sched/cls_api.c (ffffffff81c9e7d6)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_refcnt_get
```
```
In net/netfilter/nf_queue.c (ffffffff81ccbaa7)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
```
```
In net/ipv4/route.c (ffffffff81ccece3)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/inetpeer.c (ffffffff81cd463f)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/inet_hashtables.c (ffffffff81ce1a0e)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81ce39ec)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/tcp_input.c (ffffffff81cf1e47)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/udp.c (ffffffff81d1f08b)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp4_lib_lookup
```
```
In net/ipv4/fib_semantics.c (ffffffff81d39fdb)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/inet_fragment.c (ffffffff81d42153)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/ipv4/nexthop.c (ffffffff81d4bb5e)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_create_group
```
```
In net/ipv4/tcp_bpf.c (ffffffff81d5dafc)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
```
In net/ipv4/udp_bpf.c (ffffffff81d5dfd0)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - net/ipv4/udp_bpf.c:udp_bpf_recvmsg
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81d5f4f8)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_getdef
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d6a31c)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_lookup
```
```
In net/xfrm/xfrm_state.c (ffffffff81d73e01)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/unix/unix_bpf.c (ffffffff81d8397c)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - net/unix/unix_bpf.c:unix_bpf_recvmsg
```
```
In net/ipv6/addrconf.c (ffffffff81d8ee1e)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
```
```
In net/ipv6/route.c (ffffffff81da8dc3)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/udp.c (ffffffff81dba366)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp6_lib_lookup
```
```
In net/ipv6/raw.c (ffffffff81dbdb41)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/calipso.c (ffffffff81de5a30)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_sock_delattr
  - net/ipv6/calipso.c:calipso_sock_setattr
  - net/ipv6/calipso.c:calipso_sock_getattr
  - net/ipv6/calipso.c:calipso_opt_update
  - net/ipv6/calipso.c:calipso_doi_getdef
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81defcef)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In net/mptcp/token.c (ffffffff81e2b853)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_iter_next
  - net/mptcp/token.c:mptcp_token_get_sock
```
```
In net/mctp/device.c (ffffffff81e387c4)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_get_link_af_size
```
```
In net/mctp/route.c (ffffffff81e3ac3c)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_pkttype_receive
  - net/mctp/route.c:mctp_route_lookup
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
In arch/x86/kernel/process.c (ffffffff8105f7ae)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__get_wchan
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81093eea)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
```
```
In kernel/sched/core.c (ffffffff81131e37)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
```
```
In kernel/sched/fair.c (ffffffff81144c9a)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_group
```
```
In kernel/locking/qspinlock.c (ffffffff820d68d3)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:native_queued_spin_lock_slowpath
```
```
In kernel/stacktrace.c (ffffffff811d29fc)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - kernel/stacktrace.c:stack_trace_save_tsk_reliable
  - kernel/stacktrace.c:stack_trace_save_tsk
```
```
In kernel/futex/core.c (ffffffff811f32ab)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - kernel/futex/core.c:exit_pi_state_list
```
```
In kernel/futex/pi.c (ffffffff811f5c16)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - kernel/futex/pi.c:get_pi_state
```
```
In kernel/bpf/btf.c (ffffffff81318e69)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_fd_by_id
```
```
In kernel/bpf/stackmap.c (ffffffff81324e92)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:bpf_get_task_stack
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff8132cedb)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_get
```
```
In kernel/events/core.c (ffffffff81343572)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - kernel/events/core.c:ring_buffer_get
  - kernel/events/core.c:perf_lock_task_context
```
```
In kernel/events/ring_buffer.c (ffffffff8134bc07)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_begin
```
```
In mm/zswap.c (ffffffff81403e7e)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_release
```
```
In mm/memcontrol.c (ffffffff8144f301)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_id_get_online
```
```
In fs/notify/mark.c (ffffffff814de506)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_prepare_user_wait
```
```
In fs/crypto/keyring.c (ffffffff814fee72)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:fscrypt_find_master_key
  - fs/crypto/keyring.c:fscrypt_find_master_key
```
```
In fs/posix_acl.c (ffffffff815159c0)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - fs/posix_acl.c:get_cached_acl
```
```
In fs/proc/array.c (ffffffff8153c0c8)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In fs/proc/proc_net.c (ffffffff81544c57)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:seq_open_net
```
```
In fs/configfs/item.c (ffffffff815558f0)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_get_unless_zero
```
```
In fs/debugfs/file.c (ffffffff816359bb)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In ipc/util.c (ffffffff8163cdcb)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - ipc/util.c:ipc_rcu_getref
```
```
In ipc/shm.c (ffffffff81647b00)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - ipc/shm.c:exit_shm
```
```
In security/keys/key.c (ffffffff8164fad0)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - security/keys/key.c:key_lookup
```
```
In security/keys/keyring.c (ffffffff816519df)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/apparmor/apparmorfs.c (ffffffff816bf673)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:policy_get_link
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:seq_profile_learning_count_show
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_attach_show
  - security/apparmor/apparmorfs.c:seq_profile_mode_show
  - security/apparmor/apparmorfs.c:seq_profile_name_show
  - security/apparmor/apparmorfs.c:begin_current_label_crit_section
```
```
In security/apparmor/task.c (ffffffff816c2f89)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_get_task_label
```
```
In security/apparmor/domain.c (ffffffff816cbc39)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:find_attach
  - security/apparmor/domain.c:find_attach
  - security/apparmor/domain.c:find_attach
```
```
In security/apparmor/policy.c (ffffffff816ce8cc)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_current_policy_admin_capable
  - security/apparmor/policy.c:aa_current_policy_view_capable
  - security/apparmor/policy.c:aa_find_child
```
```
In security/apparmor/procattr.c (ffffffff816d366d)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff816da6c4)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_sock_graft
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_unix_may_send
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_setrlimit
  - security/apparmor/lsm.c:apparmor_current_getsecid_subj
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_sb_umount
  - security/apparmor/lsm.c:apparmor_sb_mount
  - security/apparmor/lsm.c:apparmor_file_lock
  - security/apparmor/lsm.c:apparmor_file_permission
  - security/apparmor/lsm.c:apparmor_file_receive
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_inode_init_security
  - security/apparmor/lsm.c:apparmor_path_symlink
  - security/apparmor/lsm.c:apparmor_path_mknod
  - security/apparmor/lsm.c:apparmor_path_rmdir
  - security/apparmor/lsm.c:apparmor_path_mkdir
  - security/apparmor/lsm.c:apparmor_path_unlink
  - security/apparmor/lsm.c:common_perm_cond
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/lsm.c:apparmor_cred_transfer
  - security/apparmor/lsm.c:apparmor_cred_prepare
  - security/apparmor/lsm.c:begin_current_label_crit_section
```
```
In security/apparmor/resource.c (ffffffff816db3a2)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff816ddaa1)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:aa_file_perm
```
```
In security/apparmor/label.c (ffffffff816e13e5)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:__vec_find
  - security/apparmor/label.c:__label_insert
  - security/apparmor/label.c:aa_get_current_ns
```
```
In security/apparmor/mount.c (ffffffff816e4de3)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
```
```
In security/apparmor/net.c (ffffffff816e68de)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sk_perm
```
```
In security/apparmor/af_unix.c (ffffffff816e7a96)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:begin_current_label_crit_section
```
```
In security/apparmor/notify.c (ffffffff816ea013)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - security/apparmor/notify.c:aa_get_current_ns
```
```
In security/landlock/fs.c (ffffffff816f3879)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - security/landlock/fs.c:landlock_append_fs_rule
```
```
In block/bsg-lib.c (ffffffff8175fb06)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_job_get
```
```
In io_uring/io-wq.c (ffffffff817a6362)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_queue_worker_create
  - io_uring/io-wq.c:io_wqe_activate_free_worker
```
```
In lib/syscall.c (ffffffff8188c4e7)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
```
```
In drivers/dma/dmaengine.c (ffffffff81a0527f)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_chan_get
```
```
In drivers/tty/vt/vt.c (ffffffff81a6bcb0)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:con_install
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81a706d0)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_get_by_index
```
```
In drivers/char/hw_random/core.c (ffffffff81a9b86f)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff81b6d2e7)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
```
```
In drivers/dma-buf/dma-resv.c (ffffffff81b6e6f7)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81b722d8)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_pt_create
```
```
In drivers/scsi/scsi_scan.c (ffffffff81b83c59)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/edac/ghes_edac.c (ffffffff81d25a23)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
```
```
In net/core/sock.c (ffffffff81d9a7b2)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - net/core/sock.c:skb_orphan_partial
```
```
In net/core/skbuff.c (ffffffff81da768a)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_complete_wifi_ack
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/core/skbuff.c:skb_clone_sk
```
```
In net/core/net_namespace.c (ffffffff81db3417)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - net/core/net_namespace.c:get_net_ns_by_id
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/neighbour.c (ffffffff81dd5540)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/filter.c (ffffffff81dfec10)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_assign
  - net/core/filter.c:sk_filter_charge
```
```
In net/core/sock_reuseport.c (ffffffff81e04a40)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_migrate_sock
```
```
In net/core/fib_rules.c (ffffffff81e13c1b)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_lookup
```
```
In net/core/devlink.c (ffffffff81e418f1)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_try_get
```
```
In net/core/sock_map.c (ffffffff81e4aa6c)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_close
  - net/core/sock_map.c:sock_map_destroy
  - net/core/sock_map.c:sock_hash_lookup
  - net/core/sock_map.c:sock_map_lookup
  - net/core/sock_map.c:sock_map_link
```
```
In net/core/bpf_sk_storage.c (ffffffff81e4d1be)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
```
```
In net/sched/cls_api.c (ffffffff81e5af66)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_refcnt_get
```
```
In net/netfilter/nf_queue.c (ffffffff81e8b8f7)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
```
```
In net/ipv4/route.c (ffffffff81e8ef4e)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/inetpeer.c (ffffffff81e9490f)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/inet_hashtables.c (ffffffff81ea2bce)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81ea642b)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/tcp.c (ffffffff81eacc87)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_read_skb
```
```
In net/ipv4/tcp_input.c (ffffffff81eb66b7)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/udp.c (ffffffff81ee61a3)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp_read_skb
  - net/ipv4/udp.c:udp4_lib_lookup
```
```
In net/ipv4/fib_semantics.c (ffffffff81f0293b)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/inet_fragment.c (ffffffff81f0af93)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/ipv4/nexthop.c (ffffffff81f1516e)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_create_group
```
```
In net/ipv4/tcp_bpf.c (ffffffff81f277ac)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
```
In net/ipv4/udp_bpf.c (ffffffff81f287b9)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - net/ipv4/udp_bpf.c:udp_bpf_recvmsg
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81f29bb8)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_getdef
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f3565c)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_lookup
```
```
In net/xfrm/xfrm_state.c (ffffffff81f3fd79)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/unix/unix_bpf.c (ffffffff81f5117c)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - net/unix/unix_bpf.c:unix_bpf_recvmsg
```
```
In net/ipv6/addrconf.c (ffffffff81f5d30e)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
```
```
In net/ipv6/route.c (ffffffff81f784c3)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/udp.c (ffffffff81f8a42a)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp6_lib_lookup
```
```
In net/ipv6/raw.c (ffffffff81f8e050)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/calipso.c (ffffffff81fb8250)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_sock_delattr
  - net/ipv6/calipso.c:calipso_sock_setattr
  - net/ipv6/calipso.c:calipso_sock_getattr
  - net/ipv6/calipso.c:calipso_opt_update
  - net/ipv6/calipso.c:calipso_doi_getdef
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81fc3def)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In net/mptcp/token.c (ffffffff82003a23)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_iter_next
  - net/mptcp/token.c:mptcp_token_get_sock
```
```
In net/mctp/device.c (ffffffff82011a94)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_get_link_af_size
```
```
In net/mctp/route.c (ffffffff8201420c)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_pkttype_receive
  - net/mctp/route.c:mctp_route_lookup
```
```
In lib/klist.c (ffffffff82021d0b)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
```
```
In lib/kobject.c (ffffffff820227fb)
Location: include/linux/atomic/atomic-instrumented.h:556
Inline: True
Inline callers:
  - lib/kobject.c:kobject_get_unless_zero
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
In arch/x86/kernel/process.c (ffffffff81060f0e)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__get_wchan
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81096e73)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
```
```
In kernel/sched/core.c (ffffffff811400b7)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
```
```
In kernel/sched/fair.c (ffffffff811551bb)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_group
```
```
In kernel/locking/qspinlock.c (ffffffff82159cc3)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:native_queued_spin_lock_slowpath
```
```
In kernel/stacktrace.c (ffffffff811e6cec)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - kernel/stacktrace.c:stack_trace_save_tsk_reliable
  - kernel/stacktrace.c:stack_trace_save_tsk
```
```
In kernel/futex/core.c (ffffffff81207a2b)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - kernel/futex/core.c:exit_pi_state_list
```
```
In kernel/futex/pi.c (ffffffff8120a416)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - kernel/futex/pi.c:get_pi_state
```
```
In kernel/bpf/helpers.c (ffffffff81321361)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_task_acquire
  - kernel/bpf/helpers.c:bpf_refcount_acquire_impl
```
```
In kernel/bpf/btf.c (ffffffff81348c89)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_fd_by_id
```
```
In kernel/bpf/stackmap.c (ffffffff813550f2)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:bpf_get_task_stack
```
```
In kernel/events/core.c (ffffffff813745d2)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - kernel/events/core.c:ring_buffer_get
  - kernel/events/core.c:perf_lock_task_context
```
```
In kernel/events/ring_buffer.c (ffffffff8137cc57)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_begin
```
```
In mm/zswap.c (ffffffff81436ce7)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_release
```
```
In mm/memcontrol.c (ffffffff81484d31)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_id_get_online
```
```
In fs/notify/mark.c (ffffffff81514d36)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_prepare_user_wait
```
```
In fs/crypto/keyring.c (ffffffff81536480)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:fscrypt_find_master_key
  - fs/crypto/keyring.c:fscrypt_find_master_key
```
```
In fs/posix_acl.c (ffffffff8154d49c)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - fs/posix_acl.c:get_cached_acl
```
```
In fs/proc/array.c (ffffffff815743f3)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In fs/proc/proc_net.c (ffffffff8157c847)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:seq_open_net
```
```
In fs/configfs/item.c (ffffffff8158d690)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_get_unless_zero
```
```
In fs/debugfs/file.c (ffffffff8166dccb)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In ipc/util.c (ffffffff816752db)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - ipc/util.c:ipc_rcu_getref
```
```
In ipc/shm.c (ffffffff81680023)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - ipc/shm.c:exit_shm
```
```
In security/keys/key.c (ffffffff816883b0)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - security/keys/key.c:key_lookup
```
```
In security/keys/keyring.c (ffffffff8168a28f)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/apparmor/apparmorfs.c (ffffffff816f8183)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:policy_get_link
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:seq_profile_learning_count_show
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_attach_show
  - security/apparmor/apparmorfs.c:seq_profile_mode_show
  - security/apparmor/apparmorfs.c:seq_profile_name_show
  - security/apparmor/apparmorfs.c:begin_current_label_crit_section
```
```
In security/apparmor/task.c (ffffffff816fbb39)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_get_task_label
```
```
In security/apparmor/domain.c (ffffffff817049ac)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:find_attach
  - security/apparmor/domain.c:find_attach
  - security/apparmor/domain.c:find_attach
```
```
In security/apparmor/policy.c (ffffffff817074e7)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_current_policy_admin_capable
  - security/apparmor/policy.c:aa_current_policy_view_capable
  - security/apparmor/policy.c:aa_find_child
```
```
In security/apparmor/procattr.c (ffffffff8170c53d)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff817136b4)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_sock_graft
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_unix_may_send
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_setrlimit
  - security/apparmor/lsm.c:apparmor_current_getsecid_subj
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_sb_umount
  - security/apparmor/lsm.c:apparmor_move_mount
  - security/apparmor/lsm.c:apparmor_sb_mount
  - security/apparmor/lsm.c:apparmor_uring_sqpoll
  - security/apparmor/lsm.c:apparmor_uring_override_creds
  - security/apparmor/lsm.c:apparmor_file_mprotect
  - security/apparmor/lsm.c:apparmor_mmap_file
  - security/apparmor/lsm.c:apparmor_file_lock
  - security/apparmor/lsm.c:apparmor_file_permission
  - security/apparmor/lsm.c:apparmor_file_receive
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_inode_init_security
  - security/apparmor/lsm.c:apparmor_path_symlink
  - security/apparmor/lsm.c:apparmor_path_mknod
  - security/apparmor/lsm.c:apparmor_path_rmdir
  - security/apparmor/lsm.c:apparmor_path_mkdir
  - security/apparmor/lsm.c:apparmor_path_unlink
  - security/apparmor/lsm.c:common_perm_cond
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/lsm.c:apparmor_cred_transfer
  - security/apparmor/lsm.c:apparmor_cred_prepare
  - security/apparmor/lsm.c:begin_current_label_crit_section
```
```
In security/apparmor/resource.c (ffffffff81714a8a)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff817170c1)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:aa_file_perm
```
```
In security/apparmor/label.c (ffffffff8171a9e5)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:__vec_find
  - security/apparmor/label.c:__label_insert
  - security/apparmor/label.c:aa_get_current_ns
```
```
In security/apparmor/mount.c (ffffffff8171e44d)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
```
```
In security/apparmor/net.c (ffffffff81720013)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sk_perm
```
```
In security/apparmor/af_unix.c (ffffffff81721216)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:begin_current_label_crit_section
```
```
In security/apparmor/notify.c (ffffffff81724263)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - security/apparmor/notify.c:aa_get_current_ns
```
```
In security/landlock/fs.c (ffffffff8172d9a9)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - security/landlock/fs.c:landlock_append_fs_rule
```
```
In crypto/ahash.c (ffffffff81744cae)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_clone_ahash
```
```
In crypto/shash.c (ffffffff817461bd)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - crypto/shash.c:crypto_clone_shash
```
```
In block/bsg-lib.c (ffffffff8179e9e6)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_job_get
```
```
In io_uring/io-wq.c (ffffffff817e72cb)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_queue_worker_create
  - io_uring/io-wq.c:io_wq_activate_free_worker
```
```
In lib/syscall.c (ffffffff818ce957)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
```
```
In drivers/dma/dmaengine.c (ffffffff81a4e2bf)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_chan_get
```
```
In drivers/tty/vt/vt.c (ffffffff81ab63d0)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:con_install
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81abae8f)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_get_by_index
```
```
In drivers/char/hw_random/core.c (ffffffff81ae71cf)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff81bc0a18)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
```
```
In drivers/dma-buf/dma-resv.c (ffffffff81bc1f07)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81bc5ce8)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_pt_create
```
```
In drivers/scsi/scsi_scan.c (ffffffff81bd79b1)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/edac/ghes_edac.c (ffffffff81d8ec43)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
```
```
In net/core/sock.c (ffffffff81e09012)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - net/core/sock.c:skb_orphan_partial
```
```
In net/core/skbuff.c (ffffffff81e1972a)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_complete_wifi_ack
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/core/skbuff.c:skb_clone_sk
```
```
In net/core/net_namespace.c (ffffffff81e23ad7)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - net/core/net_namespace.c:get_net_ns_by_id
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/neighbour.c (ffffffff81e47f12)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/filter.c (ffffffff81e701d3)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_assign
  - net/core/filter.c:sk_filter_charge
```
```
In net/core/sock_reuseport.c (ffffffff81e77290)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_migrate_sock
```
```
In net/core/fib_rules.c (ffffffff81e8754d)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_lookup
```
```
In net/core/sock_map.c (ffffffff81ea616c)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_close
  - net/core/sock_map.c:sock_map_destroy
  - net/core/sock_map.c:sock_hash_lookup
  - net/core/sock_map.c:sock_map_lookup
  - net/core/sock_map.c:sock_map_link
```
```
In net/core/bpf_sk_storage.c (ffffffff81ea88da)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
```
```
In net/sched/cls_api.c (ffffffff81eb6d36)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_refcnt_get
```
```
In net/netfilter/nf_queue.c (ffffffff81ee9941)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
```
```
In net/ipv4/route.c (ffffffff81eed666)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/inetpeer.c (ffffffff81ef30df)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/inet_hashtables.c (ffffffff81f013ee)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81f04c0b)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/tcp.c (ffffffff81f0b404)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_read_skb
```
```
In net/ipv4/tcp_input.c (ffffffff81f14ad7)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/udp.c (ffffffff81f459a3)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp_read_skb
  - net/ipv4/udp.c:udp4_lib_lookup
```
```
In net/ipv4/fib_semantics.c (ffffffff81f62444)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/inet_fragment.c (ffffffff81f6aae0)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/ipv4/nexthop.c (ffffffff81f74e2e)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_create_group
```
```
In net/ipv4/tcp_bpf.c (ffffffff81f8746d)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
```
In net/ipv4/udp_bpf.c (ffffffff81f88320)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81f89768)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_getdef
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f9520c)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_lookup
```
```
In net/xfrm/xfrm_state.c (ffffffff81f9f4f6)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/unix/unix_bpf.c (ffffffff81fb0ae0)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81fbd02d)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
```
```
In net/ipv6/route.c (ffffffff81fd86c3)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/udp.c (ffffffff81fea033)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp6_lib_lookup
```
```
In net/ipv6/raw.c (ffffffff81fee83c)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/calipso.c (ffffffff820189d1)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_sock_delattr
  - net/ipv6/calipso.c:calipso_sock_setattr
  - net/ipv6/calipso.c:calipso_sock_getattr
  - net/ipv6/calipso.c:calipso_opt_update
  - net/ipv6/calipso.c:calipso_doi_getdef
```
```
In net/ipv6/inet6_hashtables.c (ffffffff82024e1f)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In net/devlink/core.c (ffffffff82042271)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - net/devlink/core.c:devlink_try_get
```
```
In net/mptcp/token.c (ffffffff8207fbb3)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_iter_next
  - net/mptcp/token.c:mptcp_token_get_sock
```
```
In net/mctp/device.c (ffffffff8208e884)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_get_link_af_size
```
```
In net/mctp/route.c (ffffffff8209108e)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_pkttype_receive
  - net/mctp/route.c:mctp_route_lookup
```
```
In lib/klist.c (ffffffff820a1d5b)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
```
```
In lib/kobject.c (ffffffff820a286b)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - lib/kobject.c:kobject_get_unless_zero
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
In arch/x86/kernel/process.c (ffffffff81067fbe)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__get_wchan
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff8109e3e3)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
```
```
In kernel/sched/core.c (ffffffff8114b017)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
```
```
In kernel/sched/fair.c (ffffffff81161c1b)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_group
```
```
In kernel/locking/qspinlock.c (ffffffff8223d543)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:native_queued_spin_lock_slowpath
```
```
In kernel/stacktrace.c (ffffffff811fca3c)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - kernel/stacktrace.c:stack_trace_save_tsk_reliable
  - kernel/stacktrace.c:stack_trace_save_tsk
```
```
In kernel/futex/core.c (ffffffff8121ec3b)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - kernel/futex/core.c:exit_pi_state_list
```
```
In kernel/futex/pi.c (ffffffff81221976)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - kernel/futex/pi.c:get_pi_state
```
```
In kernel/bpf/helpers.c (ffffffff813439f1)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_task_acquire
  - kernel/bpf/helpers.c:bpf_refcount_acquire_impl
```
```
In kernel/bpf/btf.c (ffffffff8136f3b9)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_fd_by_id
```
```
In kernel/bpf/stackmap.c (ffffffff8137dac2)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:bpf_get_task_stack
```
```
In kernel/events/core.c (ffffffff8139d902)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - kernel/events/core.c:ring_buffer_get
  - kernel/events/core.c:perf_lock_task_context
```
```
In kernel/events/ring_buffer.c (ffffffff813a5eb7)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_begin
```
```
In mm/shrinker.c (ffffffff813e4dcb)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - mm/shrinker.c:shrink_slab
  - mm/shrinker.c:shrink_slab_memcg
```
```
In mm/zswap.c (ffffffff81470942)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - mm/zswap.c:zswap_store
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_release
  - mm/zswap.c:zswap_pool_current_get
```
```
In mm/memcontrol.c (ffffffff814b4261)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_id_get_online
```
```
In fs/notify/mark.c (ffffffff81549116)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_prepare_user_wait
```
```
In fs/crypto/keyring.c (ffffffff8156b4ae)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:fscrypt_find_master_key
  - fs/crypto/keyring.c:fscrypt_find_master_key
```
```
In fs/posix_acl.c (ffffffff815832cc)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - fs/posix_acl.c:get_cached_acl
```
```
In fs/proc/array.c (ffffffff815ace7f)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In fs/proc/proc_net.c (ffffffff815b5167)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:seq_open_net
```
```
In fs/configfs/item.c (ffffffff815c63d0)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_get_unless_zero
```
```
In fs/debugfs/file.c (ffffffff816a842e)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In ipc/util.c (ffffffff816b169b)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - ipc/util.c:ipc_rcu_getref
```
```
In ipc/shm.c (ffffffff816bc413)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - ipc/shm.c:exit_shm
```
```
In security/keys/key.c (ffffffff816c2ec0)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - security/keys/key.c:key_lookup
```
```
In security/keys/keyring.c (ffffffff816c678f)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/apparmor/apparmorfs.c (ffffffff81734ef9)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:policy_get_link
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:seq_profile_learning_count_show
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_attach_show
  - security/apparmor/apparmorfs.c:seq_profile_mode_show
  - security/apparmor/apparmorfs.c:seq_profile_name_show
  - security/apparmor/apparmorfs.c:begin_current_label_crit_section
```
```
In security/apparmor/task.c (ffffffff81739234)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_profile_ns_perm
  - security/apparmor/task.c:aa_profile_ns_perm
  - security/apparmor/task.c:aa_profile_ns_perm
  - security/apparmor/task.c:aa_profile_ns_perm
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_get_task_label
```
```
In security/apparmor/domain.c (ffffffff81742264)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:find_attach
  - security/apparmor/domain.c:find_attach
  - security/apparmor/domain.c:find_attach
```
```
In security/apparmor/policy.c (ffffffff81744f77)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_current_policy_admin_capable
  - security/apparmor/policy.c:aa_current_policy_view_capable
  - security/apparmor/policy.c:aa_find_child
```
```
In security/apparmor/procattr.c (ffffffff8174a298)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff81752917)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_sock_graft
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_unix_may_send
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_setrlimit
  - security/apparmor/lsm.c:apparmor_current_getlsmblob_subj
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getselfattr
  - security/apparmor/lsm.c:apparmor_getselfattr
  - security/apparmor/lsm.c:apparmor_getselfattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_sb_umount
  - security/apparmor/lsm.c:apparmor_move_mount
  - security/apparmor/lsm.c:apparmor_sb_mount
  - security/apparmor/lsm.c:apparmor_uring_sqpoll
  - security/apparmor/lsm.c:apparmor_uring_override_creds
  - security/apparmor/lsm.c:apparmor_file_mprotect
  - security/apparmor/lsm.c:apparmor_mmap_file
  - security/apparmor/lsm.c:apparmor_file_lock
  - security/apparmor/lsm.c:apparmor_file_permission
  - security/apparmor/lsm.c:apparmor_file_receive
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_inode_create
  - security/apparmor/lsm.c:apparmor_inode_init_security
  - security/apparmor/lsm.c:apparmor_path_symlink
  - security/apparmor/lsm.c:apparmor_path_mknod
  - security/apparmor/lsm.c:apparmor_path_rmdir
  - security/apparmor/lsm.c:apparmor_path_mkdir
  - security/apparmor/lsm.c:apparmor_path_unlink
  - security/apparmor/lsm.c:common_perm_cond
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/lsm.c:apparmor_cred_transfer
  - security/apparmor/lsm.c:apparmor_cred_prepare
```
```
In security/apparmor/resource.c (ffffffff8175349d)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff81755c24)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:aa_file_perm
```
```
In security/apparmor/label.c (ffffffff81759495)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:__vec_find
  - security/apparmor/label.c:__label_insert
  - security/apparmor/label.c:aa_get_current_ns
```
```
In security/apparmor/mount.c (ffffffff8175ce8d)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
```
```
In security/apparmor/net.c (ffffffff8175ea49)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sk_perm
```
```
In security/apparmor/af_unix.c (ffffffff8175fd39)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:begin_current_label_crit_section
```
```
In security/apparmor/af_inet.c (ffffffff817623d9)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - security/apparmor/af_inet.c:begin_current_label_crit_section
```
```
In security/apparmor/notify.c (ffffffff81765569)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - security/apparmor/notify.c:aa_get_current_ns
```
```
In security/landlock/fs.c (ffffffff8176e06f)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - security/landlock/fs.c:landlock_append_fs_rule
```
```
In crypto/ahash.c (ffffffff817874e4)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_clone_ahash
```
```
In crypto/shash.c (ffffffff817887fd)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - crypto/shash.c:crypto_clone_shash
```
```
In block/bsg-lib.c (ffffffff817e2496)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_job_get
```
```
In io_uring/io-wq.c (ffffffff8182d08b)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_queue_worker_create
  - io_uring/io-wq.c:io_wq_activate_free_worker
```
```
In lib/syscall.c (ffffffff81920737)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
```
```
In lib/stackdepot.c (ffffffff819289b7)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - lib/stackdepot.c:stack_depot_save_flags
  - lib/stackdepot.c:stack_depot_save_flags
```
```
In drivers/dma/dmaengine.c (ffffffff81a99f5f)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_chan_get
```
```
In drivers/tty/vt/vt.c (ffffffff81b090b0)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:con_install
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81b0dbff)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_get_by_index
```
```
In drivers/char/hw_random/core.c (ffffffff81b3a59f)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff81c15198)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
```
```
In drivers/dma-buf/dma-resv.c (ffffffff81c16697)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81c1a6f7)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_pt_create
```
```
In drivers/scsi/scsi_scan.c (ffffffff81c2c651)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/gpu/drm/drm_connector.c (ffffffff81c8746d)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_connector.c:drm_mode_get_tile_group
  - drivers/gpu/drm/drm_connector.c:drm_connector_list_iter_next
```
```
In drivers/gpu/drm/drm_gem.c (ffffffff81c9c45a)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_gem.c:drm_gem_lru_scan
  - drivers/gpu/drm/drm_gem.c:drm_gem_mmap
```
```
In drivers/gpu/drm/drm_mode_object.c (ffffffff81ca41b7)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mode_object.c:__drm_mode_object_find
```
```
In drivers/gpu/drm/drm_syncobj.c (ffffffff81cb1fea)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_query_ioctl
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_find_fence
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_add_point
```
```
In drivers/edac/ghes_edac.c (ffffffff81e46553)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
```
```
In net/core/sock.c (ffffffff81ec5a82)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - net/core/sock.c:skb_orphan_partial
```
```
In net/core/skbuff.c (ffffffff81ed6b7a)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_complete_wifi_ack
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/core/skbuff.c:skb_clone_sk
```
```
In net/core/net_namespace.c (ffffffff81ee1a37)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - net/core/net_namespace.c:get_net_ns_by_id
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/neighbour.c (ffffffff81f06bc2)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/filter.c (ffffffff81f2a434)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_assign
  - net/core/filter.c:sk_filter_charge
```
```
In net/core/sock_reuseport.c (ffffffff81f37250)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_migrate_sock
```
```
In net/core/fib_rules.c (ffffffff81f4955d)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_lookup
```
```
In net/core/sock_map.c (ffffffff81f68c2c)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_close
  - net/core/sock_map.c:sock_map_destroy
  - net/core/sock_map.c:sock_hash_lookup
  - net/core/sock_map.c:sock_map_lookup
  - net/core/sock_map.c:sock_map_link
```
```
In net/core/bpf_sk_storage.c (ffffffff81f6b39a)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
```
```
In net/sched/cls_api.c (ffffffff81f79ad6)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_refcnt_get
```
```
In net/sched/act_api.c (ffffffff81f80a0e)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_idr_check_alloc
```
```
In net/netfilter/nf_queue.c (ffffffff81fad6e0)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
```
```
In net/ipv4/route.c (ffffffff81fb16d6)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/inetpeer.c (ffffffff81fb706f)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/inet_hashtables.c (ffffffff81fc573e)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81fc8f13)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/tcp.c (ffffffff81fce438)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff81fd9001)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/udp.c (ffffffff8200baf3)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp_read_skb
  - net/ipv4/udp.c:udp4_lib_lookup
```
```
In net/ipv4/igmp.c (ffffffff8201ee7b)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_start_timer
```
```
In net/ipv4/fib_semantics.c (ffffffff82028a14)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/inet_fragment.c (ffffffff82031190)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/ipv4/nexthop.c (ffffffff8203b76b)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_create_group
```
```
In net/ipv4/tcp_sigpool.c (ffffffff8204cfba)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - net/ipv4/tcp_sigpool.c:tcp_sigpool_alloc_ahash
```
```
In net/ipv4/tcp_bpf.c (ffffffff8204eaed)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
```
In net/ipv4/udp_bpf.c (ffffffff8204fa40)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (ffffffff82050ec8)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_getdef
```
```
In net/xfrm/xfrm_policy.c (ffffffff820625fc)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_lookup
```
```
In net/xfrm/xfrm_state.c (ffffffff8206c856)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/unix/unix_bpf.c (ffffffff8207e180)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff8208a45d)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
```
```
In net/ipv6/route.c (ffffffff820a6043)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/udp.c (ffffffff820b7c0f)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp6_lib_lookup
```
```
In net/ipv6/raw.c (ffffffff820bc416)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/calipso.c (ffffffff820e79a1)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_sock_delattr
  - net/ipv6/calipso.c:calipso_sock_setattr
  - net/ipv6/calipso.c:calipso_sock_getattr
  - net/ipv6/calipso.c:calipso_opt_update
  - net/ipv6/calipso.c:calipso_doi_getdef
```
```
In net/ipv6/inet6_hashtables.c (ffffffff820f40ff)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In net/devlink/core.c (ffffffff82100be1)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - net/devlink/core.c:devlink_try_get
```
```
In net/mptcp/token.c (ffffffff821550a3)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_iter_next
  - net/mptcp/token.c:mptcp_token_get_sock
```
```
In net/mctp/device.c (ffffffff82164d74)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_get_link_af_size
```
```
In net/mctp/route.c (ffffffff821675ac)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_pkttype_receive
  - net/mctp/route.c:mctp_route_lookup
```
```
In lib/klist.c (ffffffff82179ddb)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
```
```
In lib/kobject.c (ffffffff8217a8eb)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - lib/kobject.c:kobject_get_unless_zero
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
In kernel/locking/qspinlock.c (ffff80001016abf8)
Location: include/linux/atomic-fallback.h:954
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:queued_spin_lock_slowpath
```
```
In lib/refcount.c (ffff800010637ac8)
Location: include/linux/atomic-fallback.h:954
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/refcount.c (c07dd48c)
Location: include/linux/atomic-fallback.h:954
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/refcount.c (c0000000007dd800)
Location: include/linux/atomic-fallback.h:954
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/refcount.c (ffffffe000464a14)
Location: include/linux/atomic-fallback.h:954
Inline: True
```
</details>
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
