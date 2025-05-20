# Function: <code>__refcount_add_not_zero</code>

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
In arch/x86/kernel/process.c (ffffffff81040f04)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:get_wchan
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81068978)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
```
```
In kernel/sched/core.c (ffffffff810d9635)
Location: include/linux/refcount.h:150
Inline: True
```
```
In kernel/sched/fair.c (ffffffff810ed232)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_group
```
```
In kernel/stacktrace.c (ffffffff8113d708)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - kernel/stacktrace.c:stack_trace_save_tsk_reliable
  - kernel/stacktrace.c:stack_trace_save_tsk
```
```
In kernel/futex.c (ffffffff8115868e)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - kernel/futex.c:exit_pi_state_list
```
```
In kernel/bpf/btf.c (ffffffff8122cc6c)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_fd_by_id
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff812385ed)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_get
```
```
In kernel/events/core.c (ffffffff8123ee4b)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_ctx_lock_double
  - kernel/events/core.c:ring_buffer_get
  - kernel/events/core.c:perf_lock_task_context
```
```
In kernel/events/ring_buffer.c (ffffffff8124e4af)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_begin
```
```
In mm/zswap.c (ffffffff812ce01c)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_pool_release
  - mm/zswap.c:zswap_pool_find_get
  - mm/zswap.c:zswap_pool_last_get
```
```
In mm/memcontrol.c (ffffffff8130126e)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_id_get_online
```
```
In fs/notify/mark.c (ffffffff81374e82)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_prepare_user_wait
```
```
In fs/io_uring.c (ffffffff813919ef)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - fs/io_uring.c:io_link_timeout_fn
```
```
In fs/io-wq.c (ffffffff8139c813)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - fs/io-wq.c:io_wq_get
```
```
In fs/crypto/keyring.c (ffffffff813a39e7)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - fs/crypto/keyring.c:do_add_master_key
```
```
In fs/posix_acl.c (ffffffff813b6ace)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - fs/posix_acl.c:get_cached_acl
```
```
In fs/proc/array.c (ffffffff813d4bef)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In fs/proc/proc_net.c (ffffffff813dbac3)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:seq_open_net
```
```
In fs/configfs/item.c (ffffffff813e94e6)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_get_unless_zero
```
```
In fs/debugfs/file.c (ffffffff8149fb90)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In ipc/util.c (ffffffff814a477d)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - ipc/util.c:ipc_rcu_getref
```
```
In security/keys/key.c (ffffffff814b512f)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - security/keys/key.c:key_lookup
```
```
In security/keys/keyring.c (ffffffff814b697a)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/apparmor/apparmorfs.c (ffffffff8150ae33)
Location: include/linux/refcount.h:150
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
In security/apparmor/task.c (ffffffff8150e871)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_get_task_label
```
```
In security/apparmor/domain.c (ffffffff815160de)
Location: include/linux/refcount.h:150
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
In security/apparmor/policy.c (ffffffff81518776)
Location: include/linux/refcount.h:150
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
In security/apparmor/procattr.c (ffffffff8151c57d)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff81521612)
Location: include/linux/refcount.h:150
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
In security/apparmor/resource.c (ffffffff81522a5f)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff8152455d)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:aa_file_perm
```
```
In security/apparmor/label.c (ffffffff81527304)
Location: include/linux/refcount.h:150
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
In security/apparmor/mount.c (ffffffff8152aad4)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
```
```
In security/apparmor/net.c (ffffffff8152c22e)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sk_perm
```
```
In security/apparmor/af_unix.c (ffffffff8152c802)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:begin_current_label_crit_section
```
```
In block/blk-mq.c (ffffffff8156b19c)
Location: include/linux/refcount.h:150
Inline: True
```
```
In block/bsg-lib.c (ffffffff8158403c)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_job_get
```
```
In lib/syscall.c (ffffffff815fa240)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
```
```
In lib/klist.c (ffffffff8160ea11)
Location: include/linux/refcount.h:150
Inline: True
```
```
In lib/kobject.c (ffffffff8160f3f1)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - lib/kobject.c:kobject_get_unless_zero
```
```
In drivers/dma/dmaengine.c (ffffffff81724a54)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_chan_get
```
```
In drivers/tty/vt/vt.c (ffffffff8176ca01)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:con_install
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff817702dd)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_get_by_index
```
```
In drivers/char/hw_random/core.c (ffffffff817939c1)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:hwrng_init
```
```
In drivers/dma-buf/dma-buf.c (ffffffff818367f0)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff818385ae)
Location: include/linux/refcount.h:150
Inline: True
```
```
In drivers/dma-buf/dma-resv.c (ffffffff818393b2)
Location: include/linux/refcount.h:150
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
In drivers/dma-buf/sw_sync.c (ffffffff8183cf8f)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_pt_create
```
```
In drivers/scsi/scsi_scan.c (ffffffff8184a14d)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/edac/ghes_edac.c (ffffffff8199108b)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - drivers/edac/ghes_edac.c:ghes_edac_register
```
```
In net/core/sock.c (ffffffff819e6313)
Location: include/linux/refcount.h:150
Inline: True
```
```
In net/core/skbuff.c (ffffffff819edf6c)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_complete_wifi_ack
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/core/skbuff.c:skb_clone_sk
```
```
In net/core/net_namespace.c (ffffffff819f9503)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/core/net_namespace.c:get_net_ns_by_id
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/neighbour.c (ffffffff81a11ed6)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/filter.c (ffffffff81a2ee97)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_assign
  - net/core/filter.c:sk_filter_charge
```
```
In net/core/fib_rules.c (ffffffff81a42677)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_lookup
```
```
In net/core/sock_map.c (ffffffff81a54baa)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_lookup
  - net/core/sock_map.c:sock_map_lookup
  - net/core/sock_map.c:sock_map_link_no_progs
  - net/core/sock_map.c:sock_map_link
```
```
In net/core/bpf_sk_storage.c (ffffffff81a69fda)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
```
```
In net/sched/cls_api.c (ffffffff81a752c0)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_refcnt_get
```
```
In net/ipv4/route.c (ffffffff81a9cccf)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/inetpeer.c (ffffffff81aa152a)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/inet_hashtables.c (ffffffff81aad83e)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81aaf55e)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/tcp_input.c (ffffffff81abbbcb)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/udp.c (ffffffff81ae4286)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp4_lib_lookup
```
```
In net/ipv4/fib_semantics.c (ffffffff81afc168)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/inet_fragment.c (ffffffff81b0327f)
Location: include/linux/refcount.h:150
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81b0af52)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_create_group
```
```
In net/ipv4/tcp_bpf.c (ffffffff81b17b3e)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81b194ef)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_getdef
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b2291c)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_lookup
```
```
In net/xfrm/xfrm_state.c (ffffffff81b2b00d)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/ipv6/addrconf.c (ffffffff81b41bdb)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
```
```
In net/ipv6/route.c (ffffffff81b5887b)
Location: include/linux/refcount.h:150
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
In net/ipv6/udp.c (ffffffff81b6711c)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp6_lib_lookup
```
```
In net/ipv6/raw.c (ffffffff81b6b3ee)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/calipso.c (ffffffff81b8c597)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_sock_delattr
  - net/ipv6/calipso.c:calipso_sock_setattr
  - net/ipv6/calipso.c:calipso_sock_getattr
  - net/ipv6/calipso.c:calipso_opt_update
  - net/ipv6/calipso.c:calipso_doi_getdef
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81b94100)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In net/mptcp/token.c (ffffffff81bc5aa9)
Location: include/linux/refcount.h:150
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
In arch/x86/kernel/process.c (ffffffff81042904)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:get_wchan
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81068bc0)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
```
```
In kernel/sched/core.c (ffffffff810daef7)
Location: include/linux/refcount.h:150
Inline: True
```
```
In kernel/sched/fair.c (ffffffff810f0995)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_group
```
```
In kernel/stacktrace.c (ffffffff8113e958)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - kernel/stacktrace.c:stack_trace_save_tsk_reliable
  - kernel/stacktrace.c:stack_trace_save_tsk
```
```
In kernel/futex.c (ffffffff8115990e)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - kernel/futex.c:exit_pi_state_list
```
```
In kernel/bpf/btf.c (ffffffff81231a1c)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_fd_by_id
```
```
In kernel/bpf/stackmap.c (ffffffff81237c81)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:bpf_get_task_stack
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff8123cddd)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_get
```
```
In kernel/events/core.c (ffffffff8124de8b)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:ring_buffer_get
  - kernel/events/core.c:perf_lock_task_context
```
```
In kernel/events/ring_buffer.c (ffffffff81252daf)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_begin
```
```
In mm/zswap.c (ffffffff812d4c51)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_release
```
```
In mm/memcontrol.c (ffffffff8130756e)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_id_get_online
```
```
In fs/notify/mark.c (ffffffff8137b842)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_prepare_user_wait
```
```
In fs/io-wq.c (ffffffff813a237b)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - fs/io-wq.c:io_wqe_activate_free_worker
```
```
In fs/crypto/keyring.c (ffffffff813aac27)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - fs/crypto/keyring.c:do_add_master_key
```
```
In fs/posix_acl.c (ffffffff813bdb2e)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - fs/posix_acl.c:get_cached_acl
```
```
In fs/proc/array.c (ffffffff813dba2b)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In fs/proc/proc_net.c (ffffffff813e29e3)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:seq_open_net
```
```
In fs/configfs/item.c (ffffffff813f0056)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_get_unless_zero
```
```
In fs/debugfs/file.c (ffffffff814a5b90)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In ipc/util.c (ffffffff814aa74d)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - ipc/util.c:ipc_rcu_getref
```
```
In security/keys/key.c (ffffffff814bafdf)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - security/keys/key.c:key_lookup
```
```
In security/keys/keyring.c (ffffffff814bc7c6)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/apparmor/apparmorfs.c (ffffffff815115af)
Location: include/linux/refcount.h:150
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
In security/apparmor/task.c (ffffffff8151526d)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_get_task_label
```
```
In security/apparmor/domain.c (ffffffff8151ca64)
Location: include/linux/refcount.h:150
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
In security/apparmor/policy.c (ffffffff8151efce)
Location: include/linux/refcount.h:150
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
In security/apparmor/procattr.c (ffffffff81522d51)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff81527a02)
Location: include/linux/refcount.h:150
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
In security/apparmor/resource.c (ffffffff81528c3b)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff8152a737)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:aa_file_perm
```
```
In security/apparmor/label.c (ffffffff8152cfca)
Location: include/linux/refcount.h:150
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
In security/apparmor/mount.c (ffffffff81530ce1)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
```
```
In security/apparmor/net.c (ffffffff815324ce)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sk_perm
```
```
In security/apparmor/af_unix.c (ffffffff81532b3e)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:begin_current_label_crit_section
```
```
In security/landlock/fs.c (ffffffff815390e1)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - security/landlock/fs.c:landlock_append_fs_rule
```
```
In block/blk-mq-tag.c (ffffffff81578eb8)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_find_and_get_req
```
```
In block/bsg-lib.c (ffffffff8158ae3c)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_job_get
```
```
In lib/syscall.c (ffffffff815dce20)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
```
```
In lib/klist.c (ffffffff815f21a1)
Location: include/linux/refcount.h:150
Inline: True
```
```
In lib/kobject.c (ffffffff815f2b31)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - lib/kobject.c:kobject_get_unless_zero
```
```
In drivers/dma/dmaengine.c (ffffffff81705d14)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_chan_get
```
```
In drivers/tty/vt/vt.c (ffffffff81750591)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:con_install
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81753d8d)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_get_by_index
```
```
In drivers/char/hw_random/core.c (ffffffff81776b7a)
Location: include/linux/refcount.h:150
Inline: True
```
```
In drivers/dma-buf/dma-buf.c (ffffffff818199c0)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff8181b88e)
Location: include/linux/refcount.h:150
Inline: True
```
```
In drivers/dma-buf/dma-resv.c (ffffffff8181c66a)
Location: include/linux/refcount.h:150
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
In drivers/dma-buf/sw_sync.c (ffffffff8181ff6b)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_pt_create
```
```
In drivers/scsi/scsi_scan.c (ffffffff8182d8cd)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/vfio/vfio.c (ffffffff8188d922)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_get_device_fd
  - drivers/vfio/vfio.c:vfio_group_get_device
```
```
In drivers/edac/ghes_edac.c (ffffffff819755fb)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - drivers/edac/ghes_edac.c:ghes_edac_register
```
```
In net/core/sock.c (ffffffff819cae7a)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/core/sock.c:skb_orphan_partial
```
```
In net/core/skbuff.c (ffffffff819d772c)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_complete_wifi_ack
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/core/skbuff.c:skb_clone_sk
```
```
In net/core/net_namespace.c (ffffffff819df663)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/core/net_namespace.c:get_net_ns_by_id
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/neighbour.c (ffffffff819f8b36)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/filter.c (ffffffff81a16447)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_assign
  - net/core/filter.c:sk_filter_charge
```
```
In net/core/fib_rules.c (ffffffff81a27383)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_lookup
```
```
In net/core/sock_map.c (ffffffff81a5159b)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_close
  - net/core/sock_map.c:sock_hash_lookup
  - net/core/sock_map.c:sock_map_lookup
  - net/core/sock_map.c:sock_map_link
```
```
In net/core/bpf_sk_storage.c (ffffffff81a524da)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
```
```
In net/sched/cls_api.c (ffffffff81a5dc60)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_refcnt_get
```
```
In net/ipv4/route.c (ffffffff81a87d91)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/inetpeer.c (ffffffff81a8c47a)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/inet_hashtables.c (ffffffff81a9890a)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81a9a86e)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/tcp_input.c (ffffffff81aa6b8b)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/udp.c (ffffffff81acf41d)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp4_lib_lookup
```
```
In net/ipv4/fib_semantics.c (ffffffff81ae7878)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/inet_fragment.c (ffffffff81aeea27)
Location: include/linux/refcount.h:150
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81af62ee)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_create_group
```
```
In net/ipv4/tcp_bpf.c (ffffffff81b0570f)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
```
In net/ipv4/udp_bpf.c (ffffffff81b05d14)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/ipv4/udp_bpf.c:udp_bpf_recvmsg
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81b06f7f)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_getdef
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b10518)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_lookup
```
```
In net/xfrm/xfrm_state.c (ffffffff81b18c3e)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/ipv6/addrconf.c (ffffffff81b2f8c7)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
```
```
In net/ipv6/route.c (ffffffff81b46b62)
Location: include/linux/refcount.h:150
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
In net/ipv6/udp.c (ffffffff81b552f6)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp6_lib_lookup
```
```
In net/ipv6/raw.c (ffffffff81b59741)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/calipso.c (ffffffff81b7b5cd)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_sock_delattr
  - net/ipv6/calipso.c:calipso_sock_setattr
  - net/ipv6/calipso.c:calipso_sock_getattr
  - net/ipv6/calipso.c:calipso_opt_update
  - net/ipv6/calipso.c:calipso_doi_getdef
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81b83210)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In net/mptcp/token.c (ffffffff81bb6628)
Location: include/linux/refcount.h:150
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
In arch/x86/kernel/process.c (ffffffff81048c72)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:get_wchan
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81072f8b)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
```
```
In kernel/sched/core.c (ffffffff810eebe7)
Location: include/linux/refcount.h:150
Inline: True
```
```
In kernel/sched/fair.c (ffffffff81109415)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_group
```
```
In kernel/stacktrace.c (ffffffff81161de8)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - kernel/stacktrace.c:stack_trace_save_tsk_reliable
  - kernel/stacktrace.c:stack_trace_save_tsk
```
```
In kernel/futex.c (ffffffff8117e82e)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - kernel/futex.c:exit_pi_state_list
  - kernel/futex.c:get_pi_state
```
```
In kernel/bpf/btf.c (ffffffff8126a9bc)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_fd_by_id
```
```
In kernel/bpf/stackmap.c (ffffffff81272255)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:bpf_get_task_stack
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff8127785d)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_get
```
```
In kernel/events/core.c (ffffffff81288bdc)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:ring_buffer_get
  - kernel/events/core.c:perf_lock_task_context
```
```
In kernel/events/ring_buffer.c (ffffffff8128e69f)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_begin
```
```
In mm/zswap.c (ffffffff8131afbf)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_release
```
```
In mm/memcontrol.c (ffffffff813512de)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_id_get_online
```
```
In fs/notify/mark.c (ffffffff813c85ff)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_prepare_user_wait
```
```
In fs/io-wq.c (ffffffff813f18e7)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - fs/io-wq.c:io_queue_worker_create
  - fs/io-wq.c:io_wqe_activate_free_worker
```
```
In fs/crypto/keyring.c (ffffffff813fa4b7)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - fs/crypto/keyring.c:do_add_master_key
```
```
In fs/posix_acl.c (ffffffff8140d91e)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - fs/posix_acl.c:get_cached_acl
```
```
In fs/proc/array.c (ffffffff8142d0c5)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In fs/proc/proc_net.c (ffffffff814344f3)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:seq_open_net
```
```
In fs/configfs/item.c (ffffffff81441f46)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_get_unless_zero
```
```
In fs/debugfs/file.c (ffffffff814fdd30)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In ipc/util.c (ffffffff81502c0d)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - ipc/util.c:ipc_rcu_getref
```
```
In ipc/shm.c (ffffffff8150c505)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - ipc/shm.c:exit_shm
```
```
In security/keys/key.c (ffffffff8151380f)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - security/keys/key.c:key_lookup
```
```
In security/keys/keyring.c (ffffffff815151e6)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/apparmor/apparmorfs.c (ffffffff8156f1af)
Location: include/linux/refcount.h:150
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
In security/apparmor/task.c (ffffffff8157321d)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_get_task_label
```
```
In security/apparmor/domain.c (ffffffff8157ab35)
Location: include/linux/refcount.h:150
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
In security/apparmor/policy.c (ffffffff8157d16e)
Location: include/linux/refcount.h:150
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
In security/apparmor/procattr.c (ffffffff81580fc1)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff81585c92)
Location: include/linux/refcount.h:150
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
In security/apparmor/resource.c (ffffffff81586f64)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff81588ad7)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:aa_file_perm
```
```
In security/apparmor/label.c (ffffffff8158b3ba)
Location: include/linux/refcount.h:150
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
In security/apparmor/mount.c (ffffffff8158f121)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
```
```
In security/apparmor/net.c (ffffffff81590a4e)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sk_perm
```
```
In security/apparmor/af_unix.c (ffffffff815910be)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:begin_current_label_crit_section
```
```
In security/landlock/fs.c (ffffffff81597921)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - security/landlock/fs.c:landlock_append_fs_rule
```
```
In block/blk-mq-tag.c (ffffffff815de10b)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_find_and_get_req
```
```
In block/bsg-lib.c (ffffffff815efe2c)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_job_get
```
```
In lib/syscall.c (ffffffff81648780)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
```
```
In lib/klist.c (ffffffff8165f311)
Location: include/linux/refcount.h:150
Inline: True
```
```
In lib/kobject.c (ffffffff8165fd11)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - lib/kobject.c:kobject_get_unless_zero
```
```
In drivers/dma/dmaengine.c (ffffffff817815f4)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_chan_get
```
```
In drivers/tty/vt/vt.c (ffffffff817d2e30)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:con_install
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff817d72cd)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_get_by_index
```
```
In drivers/char/hw_random/core.c (ffffffff817fc54a)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:set_current_rng
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff818a5d1e)
Location: include/linux/refcount.h:150
Inline: True
```
```
In drivers/dma-buf/dma-resv.c (ffffffff818a6a33)
Location: include/linux/refcount.h:150
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
In drivers/dma-buf/sw_sync.c (ffffffff818aa62b)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_pt_create
```
```
In drivers/scsi/scsi_scan.c (ffffffff818b931d)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/vfio/vfio.c (ffffffff81920f6c)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_get_device_fd
  - drivers/vfio/vfio.c:vfio_group_get_device
```
```
In drivers/edac/ghes_edac.c (ffffffff81a1e307)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - drivers/edac/ghes_edac.c:ghes_edac_register
```
```
In net/core/sock.c (ffffffff81a7a4aa)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/core/sock.c:skb_orphan_partial
```
```
In net/core/skbuff.c (ffffffff81a85f6c)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_complete_wifi_ack
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/core/skbuff.c:skb_clone_sk
```
```
In net/core/net_namespace.c (ffffffff81a8fa43)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/core/net_namespace.c:get_net_ns_by_id
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/neighbour.c (ffffffff81aaa715)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/filter.c (ffffffff81acccf1)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_assign
  - net/core/filter.c:sk_filter_charge
```
```
In net/core/sock_reuseport.c (ffffffff81ad1bdf)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_migrate_sock
```
```
In net/core/fib_rules.c (ffffffff81adc116)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_lookup
```
```
In net/core/devlink.c (ffffffff81b027ef)
Location: include/linux/refcount.h:150
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
In net/core/sock_map.c (ffffffff81b0951b)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_close
  - net/core/sock_map.c:sock_hash_lookup
  - net/core/sock_map.c:sock_map_lookup
  - net/core/sock_map.c:sock_map_link
```
```
In net/core/bpf_sk_storage.c (ffffffff81b0b5e3)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
```
```
In net/sched/cls_api.c (ffffffff81b16e20)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_refcnt_get
```
```
In net/netfilter/nf_queue.c (ffffffff81b3f342)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
```
```
In net/ipv4/route.c (ffffffff81b422d0)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/inetpeer.c (ffffffff81b47498)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/inet_hashtables.c (ffffffff81b53dea)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81b55cde)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/tcp_input.c (ffffffff81b6318b)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/udp.c (ffffffff81b8de3d)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp4_lib_lookup
```
```
In net/ipv4/fib_semantics.c (ffffffff81ba7793)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/inet_fragment.c (ffffffff81baedf7)
Location: include/linux/refcount.h:150
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81bb7d9e)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_create_group
```
```
In net/ipv4/tcp_bpf.c (ffffffff81bc825f)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
```
In net/ipv4/udp_bpf.c (ffffffff81bc8a02)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/ipv4/udp_bpf.c:udp_bpf_recvmsg
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81bc9dff)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_getdef
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bd3e39)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_lookup
```
```
In net/xfrm/xfrm_state.c (ffffffff81bdd02e)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/unix/unix_bpf.c (ffffffff81beb789)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/unix/unix_bpf.c:unix_bpf_recvmsg
```
```
In net/ipv6/addrconf.c (ffffffff81bf5c47)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
```
```
In net/ipv6/route.c (ffffffff81c0ddb2)
Location: include/linux/refcount.h:150
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
In net/ipv6/udp.c (ffffffff81c1ddc3)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp6_lib_lookup
```
```
In net/ipv6/raw.c (ffffffff81c20d6a)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/calipso.c (ffffffff81c46586)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_sock_delattr
  - net/ipv6/calipso.c:calipso_sock_setattr
  - net/ipv6/calipso.c:calipso_sock_getattr
  - net/ipv6/calipso.c:calipso_opt_update
  - net/ipv6/calipso.c:calipso_doi_getdef
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81c4f2e0)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In net/mptcp/token.c (ffffffff81c85638)
Location: include/linux/refcount.h:150
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
In arch/x86/kernel/process.c (ffffffff81051f73)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__get_wchan
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81081603)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
```
```
In kernel/sched/core.c (ffffffff8110ba56)
Location: include/linux/refcount.h:150
Inline: True
```
```
In kernel/sched/fair.c (ffffffff8111d8ef)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_group
```
```
In kernel/stacktrace.c (ffffffff81194cef)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - kernel/stacktrace.c:stack_trace_save_tsk_reliable
  - kernel/stacktrace.c:stack_trace_save_tsk
```
```
In kernel/futex/core.c (ffffffff811b2420)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - kernel/futex/core.c:exit_pi_state_list
```
```
In kernel/futex/pi.c (ffffffff811b4b3c)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - kernel/futex/pi.c:get_pi_state
```
```
In kernel/bpf/btf.c (ffffffff812b7802)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_fd_by_id
```
```
In kernel/bpf/stackmap.c (ffffffff812c1585)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:bpf_get_task_stack
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff812c74fd)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_get
```
```
In kernel/events/core.c (ffffffff812dde8f)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:ring_buffer_get
  - kernel/events/core.c:perf_lock_task_context
```
```
In kernel/events/ring_buffer.c (ffffffff812e356c)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_begin
```
```
In mm/zswap.c (ffffffff81386043)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_release
```
```
In mm/memcontrol.c (ffffffff813c9d2a)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_id_get_online
```
```
In fs/notify/mark.c (ffffffff8144fbcf)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_prepare_user_wait
```
```
In fs/crypto/keyring.c (ffffffff8146d637)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - fs/crypto/keyring.c:do_add_master_key
```
```
In fs/posix_acl.c (ffffffff81482c07)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - fs/posix_acl.c:get_cached_acl
```
```
In fs/proc/array.c (ffffffff814a6a7d)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In fs/proc/proc_net.c (ffffffff814ae610)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:seq_open_net
```
```
In fs/configfs/item.c (ffffffff814bdba6)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_get_unless_zero
```
```
In fs/debugfs/file.c (ffffffff8158e920)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In ipc/util.c (ffffffff815941cd)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - ipc/util.c:ipc_rcu_getref
```
```
In ipc/shm.c (ffffffff8159e475)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - ipc/shm.c:exit_shm
```
```
In security/keys/key.c (ffffffff815a5ca9)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - security/keys/key.c:key_lookup
```
```
In security/keys/keyring.c (ffffffff815a7976)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/apparmor/apparmorfs.c (ffffffff8160d6ea)
Location: include/linux/refcount.h:150
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
In security/apparmor/task.c (ffffffff81610520)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_get_task_label
```
```
In security/apparmor/domain.c (ffffffff81618dcc)
Location: include/linux/refcount.h:150
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
In security/apparmor/policy.c (ffffffff8161b7ec)
Location: include/linux/refcount.h:150
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
In security/apparmor/procattr.c (ffffffff8162017a)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff81626819)
Location: include/linux/refcount.h:150
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
In security/apparmor/resource.c (ffffffff8162738d)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff816291aa)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:aa_file_perm
```
```
In security/apparmor/label.c (ffffffff8162c926)
Location: include/linux/refcount.h:150
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
In security/apparmor/mount.c (ffffffff81630158)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
```
```
In security/apparmor/net.c (ffffffff81631bad)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sk_perm
```
```
In security/apparmor/af_unix.c (ffffffff81632c3d)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:begin_current_label_crit_section
```
```
In security/landlock/fs.c (ffffffff8163c091)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - security/landlock/fs.c:landlock_append_fs_rule
```
```
In block/bsg-lib.c (ffffffff816a0f2c)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_job_get
```
```
In io_uring/io-wq.c (ffffffff816da2ab)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_queue_worker_create
  - io_uring/io-wq.c:io_wqe_activate_free_worker
```
```
In lib/syscall.c (ffffffff8175ebb0)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
```
```
In lib/klist.c (ffffffff81778ee1)
Location: include/linux/refcount.h:150
Inline: True
```
```
In lib/kobject.c (ffffffff81779851)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - lib/kobject.c:kobject_get_unless_zero
```
```
In drivers/dma/dmaengine.c (ffffffff818b7fa2)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_chan_get
```
```
In drivers/tty/vt/vt.c (ffffffff81910de9)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:con_install
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81915419)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_get_by_index
```
```
In drivers/char/hw_random/core.c (ffffffff8193b1a8)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:set_current_rng
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff819efc90)
Location: include/linux/refcount.h:150
Inline: True
```
```
In drivers/dma-buf/dma-resv.c (ffffffff819f07b0)
Location: include/linux/refcount.h:150
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (ffffffff819f4e1d)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_pt_create
```
```
In drivers/scsi/scsi_scan.c (ffffffff81a04fa2)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/vfio/vfio.c (ffffffff81a786d6)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_fops_open
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
  - drivers/vfio/vfio.c:__vfio_register_dev
```
```
In drivers/edac/ghes_edac.c (ffffffff81b86a42)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - drivers/edac/ghes_edac.c:ghes_edac_register
```
```
In net/core/sock.c (ffffffff81bededb)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/core/sock.c:skb_orphan_partial
```
```
In net/core/skbuff.c (ffffffff81bf87fb)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_complete_wifi_ack
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/core/skbuff.c:skb_clone_sk
```
```
In net/core/net_namespace.c (ffffffff81c03d40)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/core/net_namespace.c:get_net_ns_by_id
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/neighbour.c (ffffffff81c23559)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/filter.c (ffffffff81c499d1)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_assign
  - net/core/filter.c:sk_filter_charge
```
```
In net/core/sock_reuseport.c (ffffffff81c4f452)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_migrate_sock
```
```
In net/core/fib_rules.c (ffffffff81c5d460)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_lookup
```
```
In net/core/devlink.c (ffffffff81c86c44)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_try_get
```
```
In net/core/sock_map.c (ffffffff81c8f639)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_close
  - net/core/sock_map.c:sock_hash_lookup
  - net/core/sock_map.c:sock_map_lookup
  - net/core/sock_map.c:sock_map_link
```
```
In net/core/bpf_sk_storage.c (ffffffff81c91be3)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
```
```
In net/sched/cls_api.c (ffffffff81c9e7cf)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_refcnt_get
```
```
In net/netfilter/nf_queue.c (ffffffff81ccbaa0)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
```
```
In net/ipv4/route.c (ffffffff81ccecd8)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/inetpeer.c (ffffffff81cd4638)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/inet_hashtables.c (ffffffff81ce1a07)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81ce39e1)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/tcp_input.c (ffffffff81cf1e40)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/udp.c (ffffffff81d1f080)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp4_lib_lookup
```
```
In net/ipv4/fib_semantics.c (ffffffff81d39fd0)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/inet_fragment.c (ffffffff81d42148)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/ipv4/nexthop.c (ffffffff81d4bb53)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_create_group
```
```
In net/ipv4/tcp_bpf.c (ffffffff81d5daee)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
```
In net/ipv4/udp_bpf.c (ffffffff81d5dfc9)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/ipv4/udp_bpf.c:udp_bpf_recvmsg
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81d5f4f1)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_getdef
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d6a315)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_lookup
```
```
In net/xfrm/xfrm_state.c (ffffffff81d73dfa)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/unix/unix_bpf.c (ffffffff81d83975)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/unix/unix_bpf.c:unix_bpf_recvmsg
```
```
In net/ipv6/addrconf.c (ffffffff81d8ee17)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
```
```
In net/ipv6/route.c (ffffffff81da8db8)
Location: include/linux/refcount.h:150
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
In net/ipv6/udp.c (ffffffff81dba358)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp6_lib_lookup
```
```
In net/ipv6/raw.c (ffffffff81dbdb33)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/calipso.c (ffffffff81de5a23)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_sock_delattr
  - net/ipv6/calipso.c:calipso_sock_setattr
  - net/ipv6/calipso.c:calipso_sock_getattr
  - net/ipv6/calipso.c:calipso_opt_update
  - net/ipv6/calipso.c:calipso_doi_getdef
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81defce8)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In net/mptcp/token.c (ffffffff81e2b84c)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_iter_next
  - net/mptcp/token.c:mptcp_token_get_sock
```
```
In net/mctp/device.c (ffffffff81e387bd)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_get_link_af_size
```
```
In net/mctp/route.c (ffffffff81e3ac35)
Location: include/linux/refcount.h:150
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
In arch/x86/kernel/process.c (ffffffff8105f7a3)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__get_wchan
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81093ee3)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
```
```
In kernel/sched/core.c (ffffffff81131e26)
Location: include/linux/refcount.h:150
Inline: True
```
```
In kernel/sched/fair.c (ffffffff81144c90)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_group
```
```
In kernel/stacktrace.c (ffffffff811d29ef)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - kernel/stacktrace.c:stack_trace_save_tsk_reliable
  - kernel/stacktrace.c:stack_trace_save_tsk
```
```
In kernel/futex/core.c (ffffffff811f32a0)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - kernel/futex/core.c:exit_pi_state_list
```
```
In kernel/futex/pi.c (ffffffff811f5c0c)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - kernel/futex/pi.c:get_pi_state
```
```
In kernel/bpf/btf.c (ffffffff81318e62)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_fd_by_id
```
```
In kernel/bpf/stackmap.c (ffffffff81324e85)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:bpf_get_task_stack
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff8132cecd)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_get
```
```
In kernel/events/core.c (ffffffff81343569)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - kernel/events/core.c:ring_buffer_get
  - kernel/events/core.c:perf_lock_task_context
```
```
In kernel/events/ring_buffer.c (ffffffff8134bbfc)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_begin
```
```
In mm/zswap.c (ffffffff81403e73)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_release
```
```
In mm/memcontrol.c (ffffffff8144f2fa)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_id_get_online
```
```
In fs/notify/mark.c (ffffffff814de4ff)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_prepare_user_wait
```
```
In fs/crypto/keyring.c (ffffffff814fee67)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:fscrypt_find_master_key
  - fs/crypto/keyring.c:fscrypt_find_master_key
```
```
In fs/posix_acl.c (ffffffff815159b7)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - fs/posix_acl.c:get_cached_acl
```
```
In fs/proc/array.c (ffffffff8153c0bd)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In fs/proc/proc_net.c (ffffffff81544c50)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:seq_open_net
```
```
In fs/configfs/item.c (ffffffff815558e6)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_get_unless_zero
```
```
In fs/debugfs/file.c (ffffffff816359b0)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In ipc/util.c (ffffffff8163cdbd)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - ipc/util.c:ipc_rcu_getref
```
```
In ipc/shm.c (ffffffff81647af5)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - ipc/shm.c:exit_shm
```
```
In security/keys/key.c (ffffffff8164fac9)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - security/keys/key.c:key_lookup
```
```
In security/keys/keyring.c (ffffffff816519d6)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/apparmor/apparmorfs.c (ffffffff816bf66a)
Location: include/linux/refcount.h:150
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
In security/apparmor/task.c (ffffffff816c2f80)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_get_task_label
```
```
In security/apparmor/domain.c (ffffffff816cbc2f)
Location: include/linux/refcount.h:150
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
In security/apparmor/policy.c (ffffffff816ce8c3)
Location: include/linux/refcount.h:150
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
In security/apparmor/procattr.c (ffffffff816d3664)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff816da6b9)
Location: include/linux/refcount.h:150
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
In security/apparmor/resource.c (ffffffff816db398)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff816dda96)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:aa_file_perm
```
```
In security/apparmor/label.c (ffffffff816e13d6)
Location: include/linux/refcount.h:150
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
In security/apparmor/mount.c (ffffffff816e4dda)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
```
```
In security/apparmor/net.c (ffffffff816e68d5)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sk_perm
```
```
In security/apparmor/af_unix.c (ffffffff816e7a8d)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:begin_current_label_crit_section
```
```
In security/apparmor/notify.c (ffffffff816ea00a)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - security/apparmor/notify.c:aa_get_current_ns
```
```
In security/landlock/fs.c (ffffffff816f386b)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - security/landlock/fs.c:landlock_append_fs_rule
```
```
In block/bsg-lib.c (ffffffff8175fafc)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_job_get
```
```
In io_uring/io-wq.c (ffffffff817a635b)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_queue_worker_create
  - io_uring/io-wq.c:io_wqe_activate_free_worker
```
```
In lib/syscall.c (ffffffff8188c4d0)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
```
```
In drivers/dma/dmaengine.c (ffffffff81a05272)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_chan_get
```
```
In drivers/tty/vt/vt.c (ffffffff81a6bca9)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:con_install
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81a706c9)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_get_by_index
```
```
In drivers/char/hw_random/core.c (ffffffff81a9b868)
Location: include/linux/refcount.h:150
Inline: True
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff81b6d2e0)
Location: include/linux/refcount.h:150
Inline: True
```
```
In drivers/dma-buf/dma-resv.c (ffffffff81b6e6f0)
Location: include/linux/refcount.h:150
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81b722cd)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_pt_create
```
```
In drivers/scsi/scsi_scan.c (ffffffff81b83c52)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/edac/ghes_edac.c (ffffffff81d25a13)
Location: include/linux/refcount.h:150
Inline: True
```
```
In net/core/sock.c (ffffffff81d9a7ab)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/core/sock.c:skb_orphan_partial
```
```
In net/core/skbuff.c (ffffffff81da767b)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_complete_wifi_ack
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/core/skbuff.c:skb_clone_sk
```
```
In net/core/net_namespace.c (ffffffff81db3410)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/core/net_namespace.c:get_net_ns_by_id
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/neighbour.c (ffffffff81dd5539)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/filter.c (ffffffff81dfec05)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_assign
  - net/core/filter.c:sk_filter_charge
```
```
In net/core/sock_reuseport.c (ffffffff81e04a39)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_migrate_sock
```
```
In net/core/fib_rules.c (ffffffff81e13c10)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_lookup
```
```
In net/core/devlink.c (ffffffff81e418e4)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_try_get
```
```
In net/core/sock_map.c (ffffffff81e4aa65)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_close
  - net/core/sock_map.c:sock_map_destroy
  - net/core/sock_map.c:sock_hash_lookup
  - net/core/sock_map.c:sock_map_lookup
  - net/core/sock_map.c:sock_map_link
```
```
In net/core/bpf_sk_storage.c (ffffffff81e4d1b3)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
```
```
In net/sched/cls_api.c (ffffffff81e5af5f)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_refcnt_get
```
```
In net/netfilter/nf_queue.c (ffffffff81e8b8f0)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
```
```
In net/ipv4/route.c (ffffffff81e8ef43)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/inetpeer.c (ffffffff81e94908)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/inet_hashtables.c (ffffffff81ea2bc7)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81ea6423)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/tcp.c (ffffffff81eacc7c)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_read_skb
```
```
In net/ipv4/tcp_input.c (ffffffff81eb66b0)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/udp.c (ffffffff81ee6198)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp_read_skb
  - net/ipv4/udp.c:udp4_lib_lookup
```
```
In net/ipv4/fib_semantics.c (ffffffff81f02930)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/inet_fragment.c (ffffffff81f0af88)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/ipv4/nexthop.c (ffffffff81f15163)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_create_group
```
```
In net/ipv4/tcp_bpf.c (ffffffff81f2779e)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
```
In net/ipv4/udp_bpf.c (ffffffff81f287b2)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/ipv4/udp_bpf.c:udp_bpf_recvmsg
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81f29bb1)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_getdef
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f35655)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_lookup
```
```
In net/xfrm/xfrm_state.c (ffffffff81f3fd6e)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/unix/unix_bpf.c (ffffffff81f51175)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/unix/unix_bpf.c:unix_bpf_recvmsg
```
```
In net/ipv6/addrconf.c (ffffffff81f5d307)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
```
```
In net/ipv6/route.c (ffffffff81f784b8)
Location: include/linux/refcount.h:150
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
In net/ipv6/udp.c (ffffffff81f8a41c)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp6_lib_lookup
```
```
In net/ipv6/raw.c (ffffffff81f8e042)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/calipso.c (ffffffff81fb8243)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_sock_delattr
  - net/ipv6/calipso.c:calipso_sock_setattr
  - net/ipv6/calipso.c:calipso_sock_getattr
  - net/ipv6/calipso.c:calipso_opt_update
  - net/ipv6/calipso.c:calipso_doi_getdef
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81fc3de8)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In net/mptcp/token.c (ffffffff82003a1c)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_iter_next
  - net/mptcp/token.c:mptcp_token_get_sock
```
```
In net/mctp/device.c (ffffffff82011a8d)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_get_link_af_size
```
```
In net/mctp/route.c (ffffffff82014205)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_pkttype_receive
  - net/mctp/route.c:mctp_route_lookup
```
```
In lib/klist.c (ffffffff82021d01)
Location: include/linux/refcount.h:150
Inline: True
```
```
In lib/kobject.c (ffffffff820227f1)
Location: include/linux/refcount.h:150
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
In arch/x86/kernel/process.c (ffffffff81060f03)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__get_wchan
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81096e6c)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
```
```
In kernel/sched/core.c (ffffffff811400a6)
Location: include/linux/refcount.h:150
Inline: True
```
```
In kernel/sched/fair.c (ffffffff811551b1)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_group
```
```
In kernel/stacktrace.c (ffffffff811e6cdf)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - kernel/stacktrace.c:stack_trace_save_tsk_reliable
  - kernel/stacktrace.c:stack_trace_save_tsk
```
```
In kernel/futex/core.c (ffffffff81207a20)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - kernel/futex/core.c:exit_pi_state_list
```
```
In kernel/futex/pi.c (ffffffff8120a40c)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - kernel/futex/pi.c:get_pi_state
```
```
In kernel/bpf/helpers.c (ffffffff81321354)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_task_acquire
  - kernel/bpf/helpers.c:bpf_refcount_acquire_impl
```
```
In kernel/bpf/btf.c (ffffffff81348c82)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_fd_by_id
```
```
In kernel/bpf/stackmap.c (ffffffff813550e5)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:bpf_get_task_stack
```
```
In kernel/events/core.c (ffffffff813745c9)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - kernel/events/core.c:ring_buffer_get
  - kernel/events/core.c:perf_lock_task_context
```
```
In kernel/events/ring_buffer.c (ffffffff8137cc4c)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_begin
```
```
In mm/zswap.c (ffffffff81436cdc)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_release
```
```
In mm/memcontrol.c (ffffffff81484d2a)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_id_get_online
```
```
In fs/notify/mark.c (ffffffff81514d2f)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_prepare_user_wait
```
```
In fs/crypto/keyring.c (ffffffff81536475)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:fscrypt_find_master_key
  - fs/crypto/keyring.c:fscrypt_find_master_key
```
```
In fs/posix_acl.c (ffffffff8154d493)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - fs/posix_acl.c:get_cached_acl
```
```
In fs/proc/array.c (ffffffff815743e8)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In fs/proc/proc_net.c (ffffffff8157c840)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:seq_open_net
```
```
In fs/configfs/item.c (ffffffff8158d686)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_get_unless_zero
```
```
In fs/debugfs/file.c (ffffffff8166dcc0)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In ipc/util.c (ffffffff816752cd)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - ipc/util.c:ipc_rcu_getref
```
```
In ipc/shm.c (ffffffff81680018)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - ipc/shm.c:exit_shm
```
```
In security/keys/key.c (ffffffff816883a9)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - security/keys/key.c:key_lookup
```
```
In security/keys/keyring.c (ffffffff8168a286)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/apparmor/apparmorfs.c (ffffffff816f817a)
Location: include/linux/refcount.h:150
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
In security/apparmor/task.c (ffffffff816fbb30)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_get_task_label
```
```
In security/apparmor/domain.c (ffffffff817049a1)
Location: include/linux/refcount.h:150
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
In security/apparmor/policy.c (ffffffff817074de)
Location: include/linux/refcount.h:150
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
In security/apparmor/procattr.c (ffffffff8170c534)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff817136a9)
Location: include/linux/refcount.h:150
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
In security/apparmor/resource.c (ffffffff81714a80)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff817170b6)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:aa_file_perm
```
```
In security/apparmor/label.c (ffffffff8171a9d6)
Location: include/linux/refcount.h:150
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
In security/apparmor/mount.c (ffffffff8171e444)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
```
```
In security/apparmor/net.c (ffffffff8172000a)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sk_perm
```
```
In security/apparmor/af_unix.c (ffffffff8172120d)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:begin_current_label_crit_section
```
```
In security/apparmor/notify.c (ffffffff8172425a)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - security/apparmor/notify.c:aa_get_current_ns
```
```
In security/landlock/fs.c (ffffffff8172d99b)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - security/landlock/fs.c:landlock_append_fs_rule
```
```
In crypto/ahash.c (ffffffff81744c9e)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_clone_ahash
```
```
In crypto/shash.c (ffffffff817461b3)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - crypto/shash.c:crypto_clone_shash
```
```
In block/bsg-lib.c (ffffffff8179e9dc)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_job_get
```
```
In io_uring/io-wq.c (ffffffff817e72c4)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_queue_worker_create
  - io_uring/io-wq.c:io_wq_activate_free_worker
```
```
In lib/syscall.c (ffffffff818ce940)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
```
```
In drivers/dma/dmaengine.c (ffffffff81a4e2b2)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_chan_get
```
```
In drivers/tty/vt/vt.c (ffffffff81ab63c9)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:con_install
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81abae88)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_get_by_index
```
```
In drivers/char/hw_random/core.c (ffffffff81ae71c8)
Location: include/linux/refcount.h:150
Inline: True
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff81bc0a11)
Location: include/linux/refcount.h:150
Inline: True
```
```
In drivers/dma-buf/dma-resv.c (ffffffff81bc1f00)
Location: include/linux/refcount.h:150
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81bc5cdd)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_pt_create
```
```
In drivers/scsi/scsi_scan.c (ffffffff81bd79aa)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/edac/ghes_edac.c (ffffffff81d8ec33)
Location: include/linux/refcount.h:150
Inline: True
```
```
In net/core/sock.c (ffffffff81e0900b)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/core/sock.c:skb_orphan_partial
```
```
In net/core/skbuff.c (ffffffff81e1971b)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_complete_wifi_ack
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/core/skbuff.c:skb_clone_sk
```
```
In net/core/net_namespace.c (ffffffff81e23ad0)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/core/net_namespace.c:get_net_ns_by_id
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/neighbour.c (ffffffff81e47f0b)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/filter.c (ffffffff81e701c8)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_assign
  - net/core/filter.c:sk_filter_charge
```
```
In net/core/sock_reuseport.c (ffffffff81e77289)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_migrate_sock
```
```
In net/core/fib_rules.c (ffffffff81e87542)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_lookup
```
```
In net/core/sock_map.c (ffffffff81ea6165)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_close
  - net/core/sock_map.c:sock_map_destroy
  - net/core/sock_map.c:sock_hash_lookup
  - net/core/sock_map.c:sock_map_lookup
  - net/core/sock_map.c:sock_map_link
```
```
In net/core/bpf_sk_storage.c (ffffffff81ea88cf)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
```
```
In net/sched/cls_api.c (ffffffff81eb6d2f)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_refcnt_get
```
```
In net/netfilter/nf_queue.c (ffffffff81ee9934)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
```
```
In net/ipv4/route.c (ffffffff81eed65b)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/inetpeer.c (ffffffff81ef30d8)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/inet_hashtables.c (ffffffff81f013e7)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81f04c03)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/tcp.c (ffffffff81f0b3f9)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_read_skb
```
```
In net/ipv4/tcp_input.c (ffffffff81f14ad0)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/udp.c (ffffffff81f45998)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp_read_skb
  - net/ipv4/udp.c:udp4_lib_lookup
```
```
In net/ipv4/fib_semantics.c (ffffffff81f62439)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/inet_fragment.c (ffffffff81f6aad5)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/ipv4/nexthop.c (ffffffff81f74e23)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_create_group
```
```
In net/ipv4/tcp_bpf.c (ffffffff81f87466)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
```
In net/ipv4/udp_bpf.c (ffffffff81f88319)
Location: include/linux/refcount.h:150
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81f89761)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_getdef
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f95205)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_lookup
```
```
In net/xfrm/xfrm_state.c (ffffffff81f9f4eb)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/unix/unix_bpf.c (ffffffff81fb0ad9)
Location: include/linux/refcount.h:150
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81fbd026)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
```
```
In net/ipv6/route.c (ffffffff81fd86b8)
Location: include/linux/refcount.h:150
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
In net/ipv6/udp.c (ffffffff81fea025)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp6_lib_lookup
```
```
In net/ipv6/raw.c (ffffffff81fee82e)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/calipso.c (ffffffff820189c4)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_sock_delattr
  - net/ipv6/calipso.c:calipso_sock_setattr
  - net/ipv6/calipso.c:calipso_sock_getattr
  - net/ipv6/calipso.c:calipso_opt_update
  - net/ipv6/calipso.c:calipso_doi_getdef
```
```
In net/ipv6/inet6_hashtables.c (ffffffff82024e18)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In net/devlink/core.c (ffffffff82042264)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/devlink/core.c:devlink_try_get
```
```
In net/mptcp/token.c (ffffffff8207fbac)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_iter_next
  - net/mptcp/token.c:mptcp_token_get_sock
```
```
In net/mctp/device.c (ffffffff8208e87d)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_get_link_af_size
```
```
In net/mctp/route.c (ffffffff82091084)
Location: include/linux/refcount.h:150
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_pkttype_receive
  - net/mctp/route.c:mctp_route_lookup
```
```
In lib/klist.c (ffffffff820a1d51)
Location: include/linux/refcount.h:150
Inline: True
```
```
In lib/kobject.c (ffffffff820a2861)
Location: include/linux/refcount.h:150
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
In arch/x86/kernel/process.c (ffffffff81067fb3)
Location: include/linux/refcount.h:139
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__get_wchan
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff8109e3dc)
Location: include/linux/refcount.h:139
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
```
```
In kernel/sched/core.c (ffffffff8114b006)
Location: include/linux/refcount.h:139
Inline: True
```
```
In kernel/sched/fair.c (ffffffff81161c11)
Location: include/linux/refcount.h:139
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_group
```
```
In kernel/stacktrace.c (ffffffff811fca2f)
Location: include/linux/refcount.h:139
Inline: True
Inline callers:
  - kernel/stacktrace.c:stack_trace_save_tsk_reliable
  - kernel/stacktrace.c:stack_trace_save_tsk
```
```
In kernel/futex/core.c (ffffffff8121ec30)
Location: include/linux/refcount.h:139
Inline: True
Inline callers:
  - kernel/futex/core.c:exit_pi_state_list
```
```
In kernel/futex/pi.c (ffffffff8122196c)
Location: include/linux/refcount.h:139
Inline: True
Inline callers:
  - kernel/futex/pi.c:get_pi_state
```
```
In kernel/bpf/helpers.c (ffffffff813439e4)
Location: include/linux/refcount.h:139
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_task_acquire
  - kernel/bpf/helpers.c:bpf_refcount_acquire_impl
```
```
In kernel/bpf/btf.c (ffffffff8136f3b2)
Location: include/linux/refcount.h:139
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_fd_by_id
```
```
In kernel/bpf/stackmap.c (ffffffff8137dab5)
Location: include/linux/refcount.h:139
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:bpf_get_task_stack
```
```
In kernel/events/core.c (ffffffff8139d8f9)
Location: include/linux/refcount.h:139
Inline: True
Inline callers:
  - kernel/events/core.c:ring_buffer_get
  - kernel/events/core.c:perf_lock_task_context
```
```
In kernel/events/ring_buffer.c (ffffffff813a5eac)
Location: include/linux/refcount.h:139
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_begin
```
```
In mm/shrinker.c (ffffffff813e4dc4)
Location: include/linux/refcount.h:139
Inline: True
Inline callers:
  - mm/shrinker.c:shrink_slab
  - mm/shrinker.c:shrink_slab_memcg
```
```
In mm/zswap.c (ffffffff81470937)
Location: include/linux/refcount.h:139
Inline: True
Inline callers:
  - mm/zswap.c:zswap_store
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_release
  - mm/zswap.c:zswap_pool_current_get
```
```
In mm/memcontrol.c (ffffffff814b425a)
Location: include/linux/refcount.h:139
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_id_get_online
```
```
In fs/notify/mark.c (ffffffff8154910f)
Location: include/linux/refcount.h:139
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_prepare_user_wait
```
```
In fs/crypto/keyring.c (ffffffff8156b4a3)
Location: include/linux/refcount.h:139
Inline: True
Inline callers:
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:fscrypt_find_master_key
  - fs/crypto/keyring.c:fscrypt_find_master_key
```
```
In fs/posix_acl.c (ffffffff815832c3)
Location: include/linux/refcount.h:139
Inline: True
Inline callers:
  - fs/posix_acl.c:get_cached_acl
```
```
In fs/proc/array.c (ffffffff815ace74)
Location: include/linux/refcount.h:139
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In fs/proc/proc_net.c (ffffffff815b5160)
Location: include/linux/refcount.h:139
Inline: True
Inline callers:
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:seq_open_net
```
```
In fs/configfs/item.c (ffffffff815c63c6)
Location: include/linux/refcount.h:139
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_get_unless_zero
```
```
In fs/debugfs/file.c (ffffffff816a8423)
Location: include/linux/refcount.h:139
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In ipc/util.c (ffffffff816b168d)
Location: include/linux/refcount.h:139
Inline: True
Inline callers:
  - ipc/util.c:ipc_rcu_getref
```
```
In ipc/shm.c (ffffffff816bc408)
Location: include/linux/refcount.h:139
Inline: True
Inline callers:
  - ipc/shm.c:exit_shm
```
```
In security/keys/key.c (ffffffff816c2eb9)
Location: include/linux/refcount.h:139
Inline: True
Inline callers:
  - security/keys/key.c:key_lookup
```
```
In security/keys/keyring.c (ffffffff816c6786)
Location: include/linux/refcount.h:139
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/apparmor/apparmorfs.c (ffffffff81734ef0)
Location: include/linux/refcount.h:139
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
In security/apparmor/task.c (ffffffff8173922a)
Location: include/linux/refcount.h:139
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
In security/apparmor/domain.c (ffffffff8174225a)
Location: include/linux/refcount.h:139
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
In security/apparmor/policy.c (ffffffff81744f6e)
Location: include/linux/refcount.h:139
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
In security/apparmor/procattr.c (ffffffff8174a28f)
Location: include/linux/refcount.h:139
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff8175290c)
Location: include/linux/refcount.h:139
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
In security/apparmor/resource.c (ffffffff81753493)
Location: include/linux/refcount.h:139
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff81755c19)
Location: include/linux/refcount.h:139
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:aa_file_perm
```
```
In security/apparmor/label.c (ffffffff81759486)
Location: include/linux/refcount.h:139
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
In security/apparmor/mount.c (ffffffff8175ce84)
Location: include/linux/refcount.h:139
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
```
```
In security/apparmor/net.c (ffffffff8175ea40)
Location: include/linux/refcount.h:139
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sk_perm
```
```
In security/apparmor/af_unix.c (ffffffff8175fd30)
Location: include/linux/refcount.h:139
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:begin_current_label_crit_section
```
```
In security/apparmor/af_inet.c (ffffffff817623d0)
Location: include/linux/refcount.h:139
Inline: True
Inline callers:
  - security/apparmor/af_inet.c:begin_current_label_crit_section
```
```
In security/apparmor/notify.c (ffffffff81765560)
Location: include/linux/refcount.h:139
Inline: True
Inline callers:
  - security/apparmor/notify.c:aa_get_current_ns
```
```
In security/landlock/fs.c (ffffffff8176e061)
Location: include/linux/refcount.h:139
Inline: True
Inline callers:
  - security/landlock/fs.c:landlock_append_fs_rule
```
```
In crypto/ahash.c (ffffffff817874d4)
Location: include/linux/refcount.h:139
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_clone_ahash
```
```
In crypto/shash.c (ffffffff817887f3)
Location: include/linux/refcount.h:139
Inline: True
Inline callers:
  - crypto/shash.c:crypto_clone_shash
```
```
In block/bsg-lib.c (ffffffff817e248c)
Location: include/linux/refcount.h:139
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_job_get
```
```
In io_uring/io-wq.c (ffffffff8182d084)
Location: include/linux/refcount.h:139
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_queue_worker_create
  - io_uring/io-wq.c:io_wq_activate_free_worker
```
```
In lib/syscall.c (ffffffff81920720)
Location: include/linux/refcount.h:139
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
```
```
In lib/stackdepot.c (ffffffff819289af)
Location: include/linux/refcount.h:139
Inline: True
Inline callers:
  - lib/stackdepot.c:stack_depot_save_flags
  - lib/stackdepot.c:stack_depot_save_flags
```
```
In drivers/dma/dmaengine.c (ffffffff81a99f52)
Location: include/linux/refcount.h:139
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_chan_get
```
```
In drivers/tty/vt/vt.c (ffffffff81b090a9)
Location: include/linux/refcount.h:139
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:con_install
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81b0dbf8)
Location: include/linux/refcount.h:139
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_get_by_index
```
```
In drivers/char/hw_random/core.c (ffffffff81b3a598)
Location: include/linux/refcount.h:139
Inline: True
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff81c15191)
Location: include/linux/refcount.h:139
Inline: True
```
```
In drivers/dma-buf/dma-resv.c (ffffffff81c16690)
Location: include/linux/refcount.h:139
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81c1a6ec)
Location: include/linux/refcount.h:139
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_pt_create
```
```
In drivers/scsi/scsi_scan.c (ffffffff81c2c64a)
Location: include/linux/refcount.h:139
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/gpu/drm/drm_connector.c (ffffffff81c87464)
Location: include/linux/refcount.h:139
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_connector.c:drm_mode_get_tile_group
  - drivers/gpu/drm/drm_connector.c:drm_connector_list_iter_next
```
```
In drivers/gpu/drm/drm_gem.c (ffffffff81c9c44c)
Location: include/linux/refcount.h:139
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_gem.c:drm_gem_lru_scan
  - drivers/gpu/drm/drm_gem.c:drm_gem_mmap
```
```
In drivers/gpu/drm/drm_mode_object.c (ffffffff81ca41b0)
Location: include/linux/refcount.h:139
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mode_object.c:__drm_mode_object_find
```
```
In drivers/gpu/drm/drm_syncobj.c (ffffffff81cb1fe3)
Location: include/linux/refcount.h:139
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_query_ioctl
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_find_fence
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_add_point
```
```
In drivers/edac/ghes_edac.c (ffffffff81e46543)
Location: include/linux/refcount.h:139
Inline: True
```
```
In net/core/sock.c (ffffffff81ec5a7b)
Location: include/linux/refcount.h:139
Inline: True
Inline callers:
  - net/core/sock.c:skb_orphan_partial
```
```
In net/core/skbuff.c (ffffffff81ed6b6b)
Location: include/linux/refcount.h:139
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_complete_wifi_ack
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/core/skbuff.c:skb_clone_sk
```
```
In net/core/net_namespace.c (ffffffff81ee1a30)
Location: include/linux/refcount.h:139
Inline: True
Inline callers:
  - net/core/net_namespace.c:get_net_ns_by_id
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/neighbour.c (ffffffff81f06bbb)
Location: include/linux/refcount.h:139
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/filter.c (ffffffff81f2a429)
Location: include/linux/refcount.h:139
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_assign
  - net/core/filter.c:sk_filter_charge
```
```
In net/core/sock_reuseport.c (ffffffff81f37249)
Location: include/linux/refcount.h:139
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_migrate_sock
```
```
In net/core/fib_rules.c (ffffffff81f49552)
Location: include/linux/refcount.h:139
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_lookup
```
```
In net/core/sock_map.c (ffffffff81f68c25)
Location: include/linux/refcount.h:139
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_close
  - net/core/sock_map.c:sock_map_destroy
  - net/core/sock_map.c:sock_hash_lookup
  - net/core/sock_map.c:sock_map_lookup
  - net/core/sock_map.c:sock_map_link
```
```
In net/core/bpf_sk_storage.c (ffffffff81f6b38f)
Location: include/linux/refcount.h:139
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
```
```
In net/sched/cls_api.c (ffffffff81f79acf)
Location: include/linux/refcount.h:139
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_refcnt_get
```
```
In net/sched/act_api.c (ffffffff81f80a03)
Location: include/linux/refcount.h:139
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_idr_check_alloc
```
```
In net/netfilter/nf_queue.c (ffffffff81fad6d3)
Location: include/linux/refcount.h:139
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
```
```
In net/ipv4/route.c (ffffffff81fb16cb)
Location: include/linux/refcount.h:139
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/inetpeer.c (ffffffff81fb7068)
Location: include/linux/refcount.h:139
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/inet_hashtables.c (ffffffff81fc5737)
Location: include/linux/refcount.h:139
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81fc8f0b)
Location: include/linux/refcount.h:139
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/tcp.c (ffffffff81fce431)
Location: include/linux/refcount.h:139
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff81fd8ffa)
Location: include/linux/refcount.h:139
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/udp.c (ffffffff8200bae8)
Location: include/linux/refcount.h:139
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp_read_skb
  - net/ipv4/udp.c:udp4_lib_lookup
```
```
In net/ipv4/igmp.c (ffffffff8201ee74)
Location: include/linux/refcount.h:139
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_start_timer
```
```
In net/ipv4/fib_semantics.c (ffffffff82028a09)
Location: include/linux/refcount.h:139
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/inet_fragment.c (ffffffff82031185)
Location: include/linux/refcount.h:139
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/ipv4/nexthop.c (ffffffff8203b760)
Location: include/linux/refcount.h:139
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_create_group
```
```
In net/ipv4/tcp_sigpool.c (ffffffff8204cfb3)
Location: include/linux/refcount.h:139
Inline: True
Inline callers:
  - net/ipv4/tcp_sigpool.c:tcp_sigpool_alloc_ahash
```
```
In net/ipv4/tcp_bpf.c (ffffffff8204eae6)
Location: include/linux/refcount.h:139
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
```
In net/ipv4/udp_bpf.c (ffffffff8204fa39)
Location: include/linux/refcount.h:139
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (ffffffff82050ec1)
Location: include/linux/refcount.h:139
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_getdef
```
```
In net/xfrm/xfrm_policy.c (ffffffff820625f5)
Location: include/linux/refcount.h:139
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_lookup
```
```
In net/xfrm/xfrm_state.c (ffffffff8206c84b)
Location: include/linux/refcount.h:139
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/unix/unix_bpf.c (ffffffff8207e179)
Location: include/linux/refcount.h:139
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff8208a456)
Location: include/linux/refcount.h:139
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
```
```
In net/ipv6/route.c (ffffffff820a6038)
Location: include/linux/refcount.h:139
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
In net/ipv6/udp.c (ffffffff820b7c01)
Location: include/linux/refcount.h:139
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp6_lib_lookup
```
```
In net/ipv6/raw.c (ffffffff820bc408)
Location: include/linux/refcount.h:139
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/calipso.c (ffffffff820e7994)
Location: include/linux/refcount.h:139
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_sock_delattr
  - net/ipv6/calipso.c:calipso_sock_setattr
  - net/ipv6/calipso.c:calipso_sock_getattr
  - net/ipv6/calipso.c:calipso_opt_update
  - net/ipv6/calipso.c:calipso_doi_getdef
```
```
In net/ipv6/inet6_hashtables.c (ffffffff820f40f8)
Location: include/linux/refcount.h:139
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In net/devlink/core.c (ffffffff82100bd4)
Location: include/linux/refcount.h:139
Inline: True
Inline callers:
  - net/devlink/core.c:devlink_try_get
```
```
In net/mptcp/token.c (ffffffff8215509c)
Location: include/linux/refcount.h:139
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_iter_next
  - net/mptcp/token.c:mptcp_token_get_sock
```
```
In net/mctp/device.c (ffffffff82164d6d)
Location: include/linux/refcount.h:139
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_get_link_af_size
```
```
In net/mctp/route.c (ffffffff821675a2)
Location: include/linux/refcount.h:139
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_pkttype_receive
  - net/mctp/route.c:mctp_route_lookup
```
```
In lib/klist.c (ffffffff82179dd1)
Location: include/linux/refcount.h:139
Inline: True
```
```
In lib/kobject.c (ffffffff8217a8e1)
Location: include/linux/refcount.h:139
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
