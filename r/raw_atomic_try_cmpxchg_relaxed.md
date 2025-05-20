# Function: <code>raw_atomic_try_cmpxchg_relaxed</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
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
Location: include/linux/atomic/atomic-arch-fallback.h:2211
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__get_wchan
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81096e73)
Location: include/linux/atomic/atomic-arch-fallback.h:2211
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
```
```
In kernel/sched/core.c (ffffffff811400b7)
Location: include/linux/atomic/atomic-arch-fallback.h:2211
Inline: True
```
```
In kernel/sched/fair.c (ffffffff811551bb)
Location: include/linux/atomic/atomic-arch-fallback.h:2211
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_group
```
```
In kernel/locking/qspinlock.c (ffffffff82159cc3)
Location: include/linux/atomic/atomic-arch-fallback.h:2211
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:native_queued_spin_lock_slowpath
```
```
In kernel/stacktrace.c (ffffffff811e6cec)
Location: include/linux/atomic/atomic-arch-fallback.h:2211
Inline: True
Inline callers:
  - kernel/stacktrace.c:stack_trace_save_tsk_reliable
  - kernel/stacktrace.c:stack_trace_save_tsk
```
```
In kernel/futex/core.c (ffffffff81207a2b)
Location: include/linux/atomic/atomic-arch-fallback.h:2211
Inline: True
Inline callers:
  - kernel/futex/core.c:exit_pi_state_list
```
```
In kernel/futex/pi.c (ffffffff8120a416)
Location: include/linux/atomic/atomic-arch-fallback.h:2211
Inline: True
Inline callers:
  - kernel/futex/pi.c:get_pi_state
```
```
In kernel/bpf/helpers.c (ffffffff81321361)
Location: include/linux/atomic/atomic-arch-fallback.h:2211
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_task_acquire
  - kernel/bpf/helpers.c:bpf_refcount_acquire_impl
```
```
In kernel/bpf/btf.c (ffffffff81348c89)
Location: include/linux/atomic/atomic-arch-fallback.h:2211
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_fd_by_id
```
```
In kernel/bpf/stackmap.c (ffffffff813550f2)
Location: include/linux/atomic/atomic-arch-fallback.h:2211
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:bpf_get_task_stack
```
```
In kernel/events/core.c (ffffffff813745d2)
Location: include/linux/atomic/atomic-arch-fallback.h:2211
Inline: True
Inline callers:
  - kernel/events/core.c:ring_buffer_get
  - kernel/events/core.c:perf_lock_task_context
```
```
In kernel/events/ring_buffer.c (ffffffff8137cc57)
Location: include/linux/atomic/atomic-arch-fallback.h:2211
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_begin
```
```
In mm/zswap.c (ffffffff81436ce7)
Location: include/linux/atomic/atomic-arch-fallback.h:2211
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_release
```
```
In mm/memcontrol.c (ffffffff81484d31)
Location: include/linux/atomic/atomic-arch-fallback.h:2211
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_id_get_online
```
```
In fs/notify/mark.c (ffffffff81514d36)
Location: include/linux/atomic/atomic-arch-fallback.h:2211
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_prepare_user_wait
```
```
In fs/crypto/keyring.c (ffffffff81536480)
Location: include/linux/atomic/atomic-arch-fallback.h:2211
Inline: True
Inline callers:
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:fscrypt_find_master_key
  - fs/crypto/keyring.c:fscrypt_find_master_key
```
```
In fs/posix_acl.c (ffffffff8154d49c)
Location: include/linux/atomic/atomic-arch-fallback.h:2211
Inline: True
Inline callers:
  - fs/posix_acl.c:get_cached_acl
```
```
In fs/proc/array.c (ffffffff815743f3)
Location: include/linux/atomic/atomic-arch-fallback.h:2211
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In fs/proc/proc_net.c (ffffffff8157c847)
Location: include/linux/atomic/atomic-arch-fallback.h:2211
Inline: True
Inline callers:
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:seq_open_net
```
```
In fs/configfs/item.c (ffffffff8158d690)
Location: include/linux/atomic/atomic-arch-fallback.h:2211
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_get_unless_zero
```
```
In fs/debugfs/file.c (ffffffff8166dccb)
Location: include/linux/atomic/atomic-arch-fallback.h:2211
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In ipc/util.c (ffffffff816752db)
Location: include/linux/atomic/atomic-arch-fallback.h:2211
Inline: True
Inline callers:
  - ipc/util.c:ipc_rcu_getref
```
```
In ipc/shm.c (ffffffff81680023)
Location: include/linux/atomic/atomic-arch-fallback.h:2211
Inline: True
Inline callers:
  - ipc/shm.c:exit_shm
```
```
In security/keys/key.c (ffffffff816883b0)
Location: include/linux/atomic/atomic-arch-fallback.h:2211
Inline: True
Inline callers:
  - security/keys/key.c:key_lookup
```
```
In security/keys/keyring.c (ffffffff8168a28f)
Location: include/linux/atomic/atomic-arch-fallback.h:2211
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/apparmor/apparmorfs.c (ffffffff816f8183)
Location: include/linux/atomic/atomic-arch-fallback.h:2211
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
Location: include/linux/atomic/atomic-arch-fallback.h:2211
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_get_task_label
```
```
In security/apparmor/domain.c (ffffffff817049ac)
Location: include/linux/atomic/atomic-arch-fallback.h:2211
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
Location: include/linux/atomic/atomic-arch-fallback.h:2211
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
Location: include/linux/atomic/atomic-arch-fallback.h:2211
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff817136b4)
Location: include/linux/atomic/atomic-arch-fallback.h:2211
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
Location: include/linux/atomic/atomic-arch-fallback.h:2211
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff817170c1)
Location: include/linux/atomic/atomic-arch-fallback.h:2211
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:aa_file_perm
```
```
In security/apparmor/label.c (ffffffff8171a9e5)
Location: include/linux/atomic/atomic-arch-fallback.h:2211
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
Location: include/linux/atomic/atomic-arch-fallback.h:2211
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
```
```
In security/apparmor/net.c (ffffffff81720013)
Location: include/linux/atomic/atomic-arch-fallback.h:2211
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sk_perm
```
```
In security/apparmor/af_unix.c (ffffffff81721216)
Location: include/linux/atomic/atomic-arch-fallback.h:2211
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:begin_current_label_crit_section
```
```
In security/apparmor/notify.c (ffffffff81724263)
Location: include/linux/atomic/atomic-arch-fallback.h:2211
Inline: True
Inline callers:
  - security/apparmor/notify.c:aa_get_current_ns
```
```
In security/landlock/fs.c (ffffffff8172d9a9)
Location: include/linux/atomic/atomic-arch-fallback.h:2211
Inline: True
Inline callers:
  - security/landlock/fs.c:landlock_append_fs_rule
```
```
In crypto/ahash.c (ffffffff81744cae)
Location: include/linux/atomic/atomic-arch-fallback.h:2211
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_clone_ahash
```
```
In crypto/shash.c (ffffffff817461bd)
Location: include/linux/atomic/atomic-arch-fallback.h:2211
Inline: True
Inline callers:
  - crypto/shash.c:crypto_clone_shash
```
```
In block/bsg-lib.c (ffffffff8179e9e6)
Location: include/linux/atomic/atomic-arch-fallback.h:2211
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_job_get
```
```
In io_uring/io-wq.c (ffffffff817e72cb)
Location: include/linux/atomic/atomic-arch-fallback.h:2211
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_queue_worker_create
  - io_uring/io-wq.c:io_wq_activate_free_worker
```
```
In lib/syscall.c (ffffffff818ce957)
Location: include/linux/atomic/atomic-arch-fallback.h:2211
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
```
```
In drivers/dma/dmaengine.c (ffffffff81a4e2bf)
Location: include/linux/atomic/atomic-arch-fallback.h:2211
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_chan_get
```
```
In drivers/tty/vt/vt.c (ffffffff81ab63d0)
Location: include/linux/atomic/atomic-arch-fallback.h:2211
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:con_install
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81abae8f)
Location: include/linux/atomic/atomic-arch-fallback.h:2211
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_get_by_index
```
```
In drivers/char/hw_random/core.c (ffffffff81ae71cf)
Location: include/linux/atomic/atomic-arch-fallback.h:2211
Inline: True
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff81bc0a18)
Location: include/linux/atomic/atomic-arch-fallback.h:2211
Inline: True
```
```
In drivers/dma-buf/dma-resv.c (ffffffff81bc1f07)
Location: include/linux/atomic/atomic-arch-fallback.h:2211
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81bc5ce8)
Location: include/linux/atomic/atomic-arch-fallback.h:2211
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_pt_create
```
```
In drivers/scsi/scsi_scan.c (ffffffff81bd79b1)
Location: include/linux/atomic/atomic-arch-fallback.h:2211
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/edac/ghes_edac.c (ffffffff81d8ec43)
Location: include/linux/atomic/atomic-arch-fallback.h:2211
Inline: True
```
```
In net/core/sock.c (ffffffff81e09012)
Location: include/linux/atomic/atomic-arch-fallback.h:2211
Inline: True
Inline callers:
  - net/core/sock.c:skb_orphan_partial
```
```
In net/core/skbuff.c (ffffffff81e1972a)
Location: include/linux/atomic/atomic-arch-fallback.h:2211
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_complete_wifi_ack
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/core/skbuff.c:skb_clone_sk
```
```
In net/core/net_namespace.c (ffffffff81e23ad7)
Location: include/linux/atomic/atomic-arch-fallback.h:2211
Inline: True
Inline callers:
  - net/core/net_namespace.c:get_net_ns_by_id
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/neighbour.c (ffffffff81e47f12)
Location: include/linux/atomic/atomic-arch-fallback.h:2211
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/filter.c (ffffffff81e701d3)
Location: include/linux/atomic/atomic-arch-fallback.h:2211
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_assign
  - net/core/filter.c:sk_filter_charge
```
```
In net/core/sock_reuseport.c (ffffffff81e77290)
Location: include/linux/atomic/atomic-arch-fallback.h:2211
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_migrate_sock
```
```
In net/core/fib_rules.c (ffffffff81e8754d)
Location: include/linux/atomic/atomic-arch-fallback.h:2211
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_lookup
```
```
In net/core/sock_map.c (ffffffff81ea616c)
Location: include/linux/atomic/atomic-arch-fallback.h:2211
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
Location: include/linux/atomic/atomic-arch-fallback.h:2211
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
```
```
In net/sched/cls_api.c (ffffffff81eb6d36)
Location: include/linux/atomic/atomic-arch-fallback.h:2211
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_refcnt_get
```
```
In net/netfilter/nf_queue.c (ffffffff81ee9941)
Location: include/linux/atomic/atomic-arch-fallback.h:2211
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
```
```
In net/ipv4/route.c (ffffffff81eed666)
Location: include/linux/atomic/atomic-arch-fallback.h:2211
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/inetpeer.c (ffffffff81ef30df)
Location: include/linux/atomic/atomic-arch-fallback.h:2211
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/inet_hashtables.c (ffffffff81f013ee)
Location: include/linux/atomic/atomic-arch-fallback.h:2211
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81f04c0b)
Location: include/linux/atomic/atomic-arch-fallback.h:2211
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/tcp.c (ffffffff81f0b404)
Location: include/linux/atomic/atomic-arch-fallback.h:2211
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_read_skb
```
```
In net/ipv4/tcp_input.c (ffffffff81f14ad7)
Location: include/linux/atomic/atomic-arch-fallback.h:2211
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/udp.c (ffffffff81f459a3)
Location: include/linux/atomic/atomic-arch-fallback.h:2211
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp_read_skb
  - net/ipv4/udp.c:udp4_lib_lookup
```
```
In net/ipv4/fib_semantics.c (ffffffff81f62444)
Location: include/linux/atomic/atomic-arch-fallback.h:2211
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/inet_fragment.c (ffffffff81f6aae0)
Location: include/linux/atomic/atomic-arch-fallback.h:2211
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/ipv4/nexthop.c (ffffffff81f74e2e)
Location: include/linux/atomic/atomic-arch-fallback.h:2211
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_create_group
```
```
In net/ipv4/tcp_bpf.c (ffffffff81f8746d)
Location: include/linux/atomic/atomic-arch-fallback.h:2211
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
```
In net/ipv4/udp_bpf.c (ffffffff81f88320)
Location: include/linux/atomic/atomic-arch-fallback.h:2211
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81f89768)
Location: include/linux/atomic/atomic-arch-fallback.h:2211
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_getdef
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f9520c)
Location: include/linux/atomic/atomic-arch-fallback.h:2211
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_lookup
```
```
In net/xfrm/xfrm_state.c (ffffffff81f9f4f6)
Location: include/linux/atomic/atomic-arch-fallback.h:2211
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/unix/unix_bpf.c (ffffffff81fb0ae0)
Location: include/linux/atomic/atomic-arch-fallback.h:2211
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81fbd02d)
Location: include/linux/atomic/atomic-arch-fallback.h:2211
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
```
```
In net/ipv6/route.c (ffffffff81fd86c3)
Location: include/linux/atomic/atomic-arch-fallback.h:2211
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
Location: include/linux/atomic/atomic-arch-fallback.h:2211
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp6_lib_lookup
```
```
In net/ipv6/raw.c (ffffffff81fee83c)
Location: include/linux/atomic/atomic-arch-fallback.h:2211
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/calipso.c (ffffffff820189d1)
Location: include/linux/atomic/atomic-arch-fallback.h:2211
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
Location: include/linux/atomic/atomic-arch-fallback.h:2211
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In net/devlink/core.c (ffffffff82042271)
Location: include/linux/atomic/atomic-arch-fallback.h:2211
Inline: True
Inline callers:
  - net/devlink/core.c:devlink_try_get
```
```
In net/mptcp/token.c (ffffffff8207fbb3)
Location: include/linux/atomic/atomic-arch-fallback.h:2211
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_iter_next
  - net/mptcp/token.c:mptcp_token_get_sock
```
```
In net/mctp/device.c (ffffffff8208e884)
Location: include/linux/atomic/atomic-arch-fallback.h:2211
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_get_link_af_size
```
```
In net/mctp/route.c (ffffffff8209108e)
Location: include/linux/atomic/atomic-arch-fallback.h:2211
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_pkttype_receive
  - net/mctp/route.c:mctp_route_lookup
```
```
In lib/klist.c (ffffffff820a1d5b)
Location: include/linux/atomic/atomic-arch-fallback.h:2211
Inline: True
```
```
In lib/kobject.c (ffffffff820a286b)
Location: include/linux/atomic/atomic-arch-fallback.h:2211
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
Location: include/linux/atomic/atomic-arch-fallback.h:2220
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__get_wchan
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff8109e3e3)
Location: include/linux/atomic/atomic-arch-fallback.h:2220
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
```
```
In kernel/sched/core.c (ffffffff8114b017)
Location: include/linux/atomic/atomic-arch-fallback.h:2220
Inline: True
```
```
In kernel/sched/fair.c (ffffffff81161c1b)
Location: include/linux/atomic/atomic-arch-fallback.h:2220
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_group
```
```
In kernel/locking/qspinlock.c (ffffffff8223d543)
Location: include/linux/atomic/atomic-arch-fallback.h:2220
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:native_queued_spin_lock_slowpath
```
```
In kernel/stacktrace.c (ffffffff811fca3c)
Location: include/linux/atomic/atomic-arch-fallback.h:2220
Inline: True
Inline callers:
  - kernel/stacktrace.c:stack_trace_save_tsk_reliable
  - kernel/stacktrace.c:stack_trace_save_tsk
```
```
In kernel/futex/core.c (ffffffff8121ec3b)
Location: include/linux/atomic/atomic-arch-fallback.h:2220
Inline: True
Inline callers:
  - kernel/futex/core.c:exit_pi_state_list
```
```
In kernel/futex/pi.c (ffffffff81221976)
Location: include/linux/atomic/atomic-arch-fallback.h:2220
Inline: True
Inline callers:
  - kernel/futex/pi.c:get_pi_state
```
```
In kernel/bpf/helpers.c (ffffffff813439f1)
Location: include/linux/atomic/atomic-arch-fallback.h:2220
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_task_acquire
  - kernel/bpf/helpers.c:bpf_refcount_acquire_impl
```
```
In kernel/bpf/btf.c (ffffffff8136f3b9)
Location: include/linux/atomic/atomic-arch-fallback.h:2220
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_fd_by_id
```
```
In kernel/bpf/stackmap.c (ffffffff8137dac2)
Location: include/linux/atomic/atomic-arch-fallback.h:2220
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:bpf_get_task_stack
```
```
In kernel/events/core.c (ffffffff8139d902)
Location: include/linux/atomic/atomic-arch-fallback.h:2220
Inline: True
Inline callers:
  - kernel/events/core.c:ring_buffer_get
  - kernel/events/core.c:perf_lock_task_context
```
```
In kernel/events/ring_buffer.c (ffffffff813a5eb7)
Location: include/linux/atomic/atomic-arch-fallback.h:2220
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_begin
```
```
In mm/shrinker.c (ffffffff813e4dcb)
Location: include/linux/atomic/atomic-arch-fallback.h:2220
Inline: True
Inline callers:
  - mm/shrinker.c:shrink_slab
  - mm/shrinker.c:shrink_slab_memcg
```
```
In mm/zswap.c (ffffffff81470942)
Location: include/linux/atomic/atomic-arch-fallback.h:2220
Inline: True
Inline callers:
  - mm/zswap.c:zswap_store
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_release
  - mm/zswap.c:zswap_pool_current_get
```
```
In mm/memcontrol.c (ffffffff814b4261)
Location: include/linux/atomic/atomic-arch-fallback.h:2220
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_id_get_online
```
```
In fs/notify/mark.c (ffffffff81549116)
Location: include/linux/atomic/atomic-arch-fallback.h:2220
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_prepare_user_wait
```
```
In fs/crypto/keyring.c (ffffffff8156b4ae)
Location: include/linux/atomic/atomic-arch-fallback.h:2220
Inline: True
Inline callers:
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:fscrypt_find_master_key
  - fs/crypto/keyring.c:fscrypt_find_master_key
```
```
In fs/posix_acl.c (ffffffff815832cc)
Location: include/linux/atomic/atomic-arch-fallback.h:2220
Inline: True
Inline callers:
  - fs/posix_acl.c:get_cached_acl
```
```
In fs/proc/array.c (ffffffff815ace7f)
Location: include/linux/atomic/atomic-arch-fallback.h:2220
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In fs/proc/proc_net.c (ffffffff815b5167)
Location: include/linux/atomic/atomic-arch-fallback.h:2220
Inline: True
Inline callers:
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:seq_open_net
```
```
In fs/configfs/item.c (ffffffff815c63d0)
Location: include/linux/atomic/atomic-arch-fallback.h:2220
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_get_unless_zero
```
```
In fs/debugfs/file.c (ffffffff816a842e)
Location: include/linux/atomic/atomic-arch-fallback.h:2220
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In ipc/util.c (ffffffff816b169b)
Location: include/linux/atomic/atomic-arch-fallback.h:2220
Inline: True
Inline callers:
  - ipc/util.c:ipc_rcu_getref
```
```
In ipc/shm.c (ffffffff816bc413)
Location: include/linux/atomic/atomic-arch-fallback.h:2220
Inline: True
Inline callers:
  - ipc/shm.c:exit_shm
```
```
In security/keys/key.c (ffffffff816c2ec0)
Location: include/linux/atomic/atomic-arch-fallback.h:2220
Inline: True
Inline callers:
  - security/keys/key.c:key_lookup
```
```
In security/keys/keyring.c (ffffffff816c678f)
Location: include/linux/atomic/atomic-arch-fallback.h:2220
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/apparmor/apparmorfs.c (ffffffff81734ef9)
Location: include/linux/atomic/atomic-arch-fallback.h:2220
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
Location: include/linux/atomic/atomic-arch-fallback.h:2220
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
Location: include/linux/atomic/atomic-arch-fallback.h:2220
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
Location: include/linux/atomic/atomic-arch-fallback.h:2220
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
Location: include/linux/atomic/atomic-arch-fallback.h:2220
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff81752917)
Location: include/linux/atomic/atomic-arch-fallback.h:2220
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
Location: include/linux/atomic/atomic-arch-fallback.h:2220
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff81755c24)
Location: include/linux/atomic/atomic-arch-fallback.h:2220
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:aa_file_perm
```
```
In security/apparmor/label.c (ffffffff81759495)
Location: include/linux/atomic/atomic-arch-fallback.h:2220
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
Location: include/linux/atomic/atomic-arch-fallback.h:2220
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
```
```
In security/apparmor/net.c (ffffffff8175ea49)
Location: include/linux/atomic/atomic-arch-fallback.h:2220
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sk_perm
```
```
In security/apparmor/af_unix.c (ffffffff8175fd39)
Location: include/linux/atomic/atomic-arch-fallback.h:2220
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:begin_current_label_crit_section
```
```
In security/apparmor/af_inet.c (ffffffff817623d9)
Location: include/linux/atomic/atomic-arch-fallback.h:2220
Inline: True
Inline callers:
  - security/apparmor/af_inet.c:begin_current_label_crit_section
```
```
In security/apparmor/notify.c (ffffffff81765569)
Location: include/linux/atomic/atomic-arch-fallback.h:2220
Inline: True
Inline callers:
  - security/apparmor/notify.c:aa_get_current_ns
```
```
In security/landlock/fs.c (ffffffff8176e06f)
Location: include/linux/atomic/atomic-arch-fallback.h:2220
Inline: True
Inline callers:
  - security/landlock/fs.c:landlock_append_fs_rule
```
```
In crypto/ahash.c (ffffffff817874e4)
Location: include/linux/atomic/atomic-arch-fallback.h:2220
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_clone_ahash
```
```
In crypto/shash.c (ffffffff817887fd)
Location: include/linux/atomic/atomic-arch-fallback.h:2220
Inline: True
Inline callers:
  - crypto/shash.c:crypto_clone_shash
```
```
In block/bsg-lib.c (ffffffff817e2496)
Location: include/linux/atomic/atomic-arch-fallback.h:2220
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_job_get
```
```
In io_uring/io-wq.c (ffffffff8182d08b)
Location: include/linux/atomic/atomic-arch-fallback.h:2220
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_queue_worker_create
  - io_uring/io-wq.c:io_wq_activate_free_worker
```
```
In lib/syscall.c (ffffffff81920737)
Location: include/linux/atomic/atomic-arch-fallback.h:2220
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
```
```
In lib/stackdepot.c (ffffffff819289b7)
Location: include/linux/atomic/atomic-arch-fallback.h:2220
Inline: True
Inline callers:
  - lib/stackdepot.c:stack_depot_save_flags
  - lib/stackdepot.c:stack_depot_save_flags
```
```
In drivers/dma/dmaengine.c (ffffffff81a99f5f)
Location: include/linux/atomic/atomic-arch-fallback.h:2220
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_chan_get
```
```
In drivers/tty/vt/vt.c (ffffffff81b090b0)
Location: include/linux/atomic/atomic-arch-fallback.h:2220
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:con_install
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81b0dbff)
Location: include/linux/atomic/atomic-arch-fallback.h:2220
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_get_by_index
```
```
In drivers/char/hw_random/core.c (ffffffff81b3a59f)
Location: include/linux/atomic/atomic-arch-fallback.h:2220
Inline: True
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff81c15198)
Location: include/linux/atomic/atomic-arch-fallback.h:2220
Inline: True
```
```
In drivers/dma-buf/dma-resv.c (ffffffff81c16697)
Location: include/linux/atomic/atomic-arch-fallback.h:2220
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81c1a6f7)
Location: include/linux/atomic/atomic-arch-fallback.h:2220
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_pt_create
```
```
In drivers/scsi/scsi_scan.c (ffffffff81c2c651)
Location: include/linux/atomic/atomic-arch-fallback.h:2220
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/gpu/drm/drm_connector.c (ffffffff81c8746d)
Location: include/linux/atomic/atomic-arch-fallback.h:2220
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_connector.c:drm_mode_get_tile_group
  - drivers/gpu/drm/drm_connector.c:drm_connector_list_iter_next
```
```
In drivers/gpu/drm/drm_gem.c (ffffffff81c9c45a)
Location: include/linux/atomic/atomic-arch-fallback.h:2220
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_gem.c:drm_gem_lru_scan
  - drivers/gpu/drm/drm_gem.c:drm_gem_mmap
```
```
In drivers/gpu/drm/drm_mode_object.c (ffffffff81ca41b7)
Location: include/linux/atomic/atomic-arch-fallback.h:2220
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mode_object.c:__drm_mode_object_find
```
```
In drivers/gpu/drm/drm_syncobj.c (ffffffff81cb1fea)
Location: include/linux/atomic/atomic-arch-fallback.h:2220
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_query_ioctl
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_find_fence
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_add_point
```
```
In drivers/edac/ghes_edac.c (ffffffff81e46553)
Location: include/linux/atomic/atomic-arch-fallback.h:2220
Inline: True
```
```
In net/core/sock.c (ffffffff81ec5a82)
Location: include/linux/atomic/atomic-arch-fallback.h:2220
Inline: True
Inline callers:
  - net/core/sock.c:skb_orphan_partial
```
```
In net/core/skbuff.c (ffffffff81ed6b7a)
Location: include/linux/atomic/atomic-arch-fallback.h:2220
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_complete_wifi_ack
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/core/skbuff.c:skb_clone_sk
```
```
In net/core/net_namespace.c (ffffffff81ee1a37)
Location: include/linux/atomic/atomic-arch-fallback.h:2220
Inline: True
Inline callers:
  - net/core/net_namespace.c:get_net_ns_by_id
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/neighbour.c (ffffffff81f06bc2)
Location: include/linux/atomic/atomic-arch-fallback.h:2220
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/filter.c (ffffffff81f2a434)
Location: include/linux/atomic/atomic-arch-fallback.h:2220
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_assign
  - net/core/filter.c:sk_filter_charge
```
```
In net/core/sock_reuseport.c (ffffffff81f37250)
Location: include/linux/atomic/atomic-arch-fallback.h:2220
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_migrate_sock
```
```
In net/core/fib_rules.c (ffffffff81f4955d)
Location: include/linux/atomic/atomic-arch-fallback.h:2220
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_lookup
```
```
In net/core/sock_map.c (ffffffff81f68c2c)
Location: include/linux/atomic/atomic-arch-fallback.h:2220
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
Location: include/linux/atomic/atomic-arch-fallback.h:2220
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
```
```
In net/sched/cls_api.c (ffffffff81f79ad6)
Location: include/linux/atomic/atomic-arch-fallback.h:2220
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_refcnt_get
```
```
In net/sched/act_api.c (ffffffff81f80a0e)
Location: include/linux/atomic/atomic-arch-fallback.h:2220
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_idr_check_alloc
```
```
In net/netfilter/nf_queue.c (ffffffff81fad6e0)
Location: include/linux/atomic/atomic-arch-fallback.h:2220
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
```
```
In net/ipv4/route.c (ffffffff81fb16d6)
Location: include/linux/atomic/atomic-arch-fallback.h:2220
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/inetpeer.c (ffffffff81fb706f)
Location: include/linux/atomic/atomic-arch-fallback.h:2220
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/inet_hashtables.c (ffffffff81fc573e)
Location: include/linux/atomic/atomic-arch-fallback.h:2220
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81fc8f13)
Location: include/linux/atomic/atomic-arch-fallback.h:2220
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/tcp.c (ffffffff81fce438)
Location: include/linux/atomic/atomic-arch-fallback.h:2220
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff81fd9001)
Location: include/linux/atomic/atomic-arch-fallback.h:2220
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/udp.c (ffffffff8200baf3)
Location: include/linux/atomic/atomic-arch-fallback.h:2220
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp_read_skb
  - net/ipv4/udp.c:udp4_lib_lookup
```
```
In net/ipv4/igmp.c (ffffffff8201ee7b)
Location: include/linux/atomic/atomic-arch-fallback.h:2220
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_start_timer
```
```
In net/ipv4/fib_semantics.c (ffffffff82028a14)
Location: include/linux/atomic/atomic-arch-fallback.h:2220
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/inet_fragment.c (ffffffff82031190)
Location: include/linux/atomic/atomic-arch-fallback.h:2220
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/ipv4/nexthop.c (ffffffff8203b76b)
Location: include/linux/atomic/atomic-arch-fallback.h:2220
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_create_group
```
```
In net/ipv4/tcp_sigpool.c (ffffffff8204cfba)
Location: include/linux/atomic/atomic-arch-fallback.h:2220
Inline: True
Inline callers:
  - net/ipv4/tcp_sigpool.c:tcp_sigpool_alloc_ahash
```
```
In net/ipv4/tcp_bpf.c (ffffffff8204eaed)
Location: include/linux/atomic/atomic-arch-fallback.h:2220
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
```
In net/ipv4/udp_bpf.c (ffffffff8204fa40)
Location: include/linux/atomic/atomic-arch-fallback.h:2220
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (ffffffff82050ec8)
Location: include/linux/atomic/atomic-arch-fallback.h:2220
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_getdef
```
```
In net/xfrm/xfrm_policy.c (ffffffff820625fc)
Location: include/linux/atomic/atomic-arch-fallback.h:2220
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_lookup
```
```
In net/xfrm/xfrm_state.c (ffffffff8206c856)
Location: include/linux/atomic/atomic-arch-fallback.h:2220
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/unix/unix_bpf.c (ffffffff8207e180)
Location: include/linux/atomic/atomic-arch-fallback.h:2220
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff8208a45d)
Location: include/linux/atomic/atomic-arch-fallback.h:2220
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
```
```
In net/ipv6/route.c (ffffffff820a6043)
Location: include/linux/atomic/atomic-arch-fallback.h:2220
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
Location: include/linux/atomic/atomic-arch-fallback.h:2220
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp6_lib_lookup
```
```
In net/ipv6/raw.c (ffffffff820bc416)
Location: include/linux/atomic/atomic-arch-fallback.h:2220
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/calipso.c (ffffffff820e79a1)
Location: include/linux/atomic/atomic-arch-fallback.h:2220
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
Location: include/linux/atomic/atomic-arch-fallback.h:2220
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In net/devlink/core.c (ffffffff82100be1)
Location: include/linux/atomic/atomic-arch-fallback.h:2220
Inline: True
Inline callers:
  - net/devlink/core.c:devlink_try_get
```
```
In net/mptcp/token.c (ffffffff821550a3)
Location: include/linux/atomic/atomic-arch-fallback.h:2220
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_iter_next
  - net/mptcp/token.c:mptcp_token_get_sock
```
```
In net/mctp/device.c (ffffffff82164d74)
Location: include/linux/atomic/atomic-arch-fallback.h:2220
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_get_link_af_size
```
```
In net/mctp/route.c (ffffffff821675ac)
Location: include/linux/atomic/atomic-arch-fallback.h:2220
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_pkttype_receive
  - net/mctp/route.c:mctp_route_lookup
```
```
In lib/klist.c (ffffffff82179ddb)
Location: include/linux/atomic/atomic-arch-fallback.h:2220
Inline: True
```
```
In lib/kobject.c (ffffffff8217a8eb)
Location: include/linux/atomic/atomic-arch-fallback.h:2220
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
