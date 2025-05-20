# Function: <code>refcount_add_not_zero</code>

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
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/zswap.c (ffffffff8122d6d7)
Location: arch/x86/include/asm/refcount.h:80
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_release
```
```
In fs/notify/mark.c (ffffffff812bcb13)
Location: arch/x86/include/asm/refcount.h:80
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_get_mark_safe
```
```
In fs/configfs/item.c (ffffffff8130655a)
Location: arch/x86/include/asm/refcount.h:80
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_get_unless_zero
```
```
In fs/debugfs/file.c (ffffffff813a24d6)
Location: arch/x86/include/asm/refcount.h:80
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In ipc/util.c (ffffffff813a74f5)
Location: arch/x86/include/asm/refcount.h:80
Inline: True
Inline callers:
  - ipc/util.c:ipc_rcu_getref
```
```
In security/keys/key.c (ffffffff813b4919)
Location: arch/x86/include/asm/refcount.h:80
Inline: True
Inline callers:
  - security/keys/key.c:key_lookup
```
```
In security/keys/keyring.c (ffffffff813b61da)
Location: arch/x86/include/asm/refcount.h:80
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/apparmor/apparmorfs.c (ffffffff81400e59)
Location: arch/x86/include/asm/refcount.h:80
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:policy_readlink
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:seq_ns_name_show
  - security/apparmor/apparmorfs.c:seq_ns_level_show
  - security/apparmor/apparmorfs.c:seq_ns_nsstacked_show
  - security/apparmor/apparmorfs.c:seq_ns_stacked_show
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_attach_show
  - security/apparmor/apparmorfs.c:seq_profile_mode_show
  - security/apparmor/apparmorfs.c:seq_profile_name_show
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
```
```
In security/apparmor/context.c (ffffffff81403ad0)
Location: arch/x86/include/asm/refcount.h:80
Inline: True
Inline callers:
  - security/apparmor/context.c:aa_restore_previous_label
  - security/apparmor/context.c:aa_set_current_hat
  - security/apparmor/context.c:aa_get_task_label
```
```
In security/apparmor/domain.c (ffffffff81409d73)
Location: arch/x86/include/asm/refcount.h:80
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
```
```
In security/apparmor/policy.c (ffffffff8140b93c)
Location: arch/x86/include/asm/refcount.h:80
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
In security/apparmor/procattr.c (ffffffff8140e55f)
Location: arch/x86/include/asm/refcount.h:80
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff8140fd29)
Location: arch/x86/include/asm/refcount.h:80
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_sock_graft
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_create
  - security/apparmor/lsm.c:apparmor_unix_may_send
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_task_setrlimit
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_sb_umount
  - security/apparmor/lsm.c:apparmor_sb_mount
  - security/apparmor/lsm.c:common_file_perm
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:common_perm
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
```
```
In security/apparmor/resource.c (ffffffff8141202a)
Location: arch/x86/include/asm/refcount.h:80
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff8141361f)
Location: arch/x86/include/asm/refcount.h:80
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
```
```
In security/apparmor/label.c (ffffffff8141743a)
Location: arch/x86/include/asm/refcount.h:80
Inline: True
Inline callers:
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:__vec_find
  - security/apparmor/label.c:__label_insert
```
```
In security/apparmor/mount.c (ffffffff8141858c)
Location: arch/x86/include/asm/refcount.h:80
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
```
```
In security/apparmor/net.c (ffffffff81419bd2)
Location: arch/x86/include/asm/refcount.h:80
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sk_perm
```
```
In security/apparmor/af_unix.c (ffffffff8141b912)
Location: arch/x86/include/asm/refcount.h:80
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_sock_perm
```
```
In block/bsg-lib.c (ffffffff81471ff5)
Location: arch/x86/include/asm/refcount.h:80
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_job_get
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff815f39d7)
Location: arch/x86/include/asm/refcount.h:80
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_get_by_index
```
```
In drivers/char/hw_random/core.c (ffffffff816148ff)
Location: arch/x86/include/asm/refcount.h:80
Inline: True
```
```
In drivers/dma-buf/dma-buf.c (ffffffff816a726e)
Location: arch/x86/include/asm/refcount.h:80
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/reservation.c (ffffffff816a940d)
Location: arch/x86/include/asm/refcount.h:80
Inline: True
Inline callers:
  - drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu
  - drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
  - drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu
  - drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu
  - drivers/dma-buf/reservation.c:reservation_object_copy_fences
  - drivers/dma-buf/reservation.c:reservation_object_copy_fences
```
```
In drivers/dma-buf/sw_sync.c (ffffffff816aacde)
Location: arch/x86/include/asm/refcount.h:80
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
```
In drivers/scsi/scsi_scan.c (ffffffff816b8963)
Location: arch/x86/include/asm/refcount.h:80
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In net/core/sock.c (ffffffff8182b613)
Location: arch/x86/include/asm/refcount.h:80
Inline: True
```
```
In net/core/skbuff.c (ffffffff81833a53)
Location: arch/x86/include/asm/refcount.h:80
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_complete_wifi_ack
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/core/skbuff.c:skb_clone_sk
```
```
In net/core/neighbour.c (ffffffff81854945)
Location: arch/x86/include/asm/refcount.h:80
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/filter.c (ffffffff818681f5)
Location: arch/x86/include/asm/refcount.h:80
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_charge
```
```
In net/core/fib_rules.c (ffffffff8186f499)
Location: arch/x86/include/asm/refcount.h:80
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_lookup
```
```
In net/ipv4/route.c (ffffffff81890203)
Location: arch/x86/include/asm/refcount.h:80
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/inetpeer.c (ffffffff818935eb)
Location: arch/x86/include/asm/refcount.h:80
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/inet_hashtables.c (ffffffff8189daa6)
Location: arch/x86/include/asm/refcount.h:80
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff8189ece6)
Location: arch/x86/include/asm/refcount.h:80
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/tcp_input.c (ffffffff818a78be)
Location: arch/x86/include/asm/refcount.h:80
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_output.c (ffffffff818b1e8c)
Location: arch/x86/include/asm/refcount.h:80
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_pace_kick
```
```
In net/ipv4/udp.c (ffffffff818c9e69)
Location: arch/x86/include/asm/refcount.h:80
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp4_lib_lookup
```
```
In net/ipv4/cipso_ipv4.c (ffffffff818f0bee)
Location: arch/x86/include/asm/refcount.h:80
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_getdef
```
```
In net/xfrm/xfrm_policy.c (ffffffff818f7b2f)
Location: arch/x86/include/asm/refcount.h:80
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_lookup
```
```
In net/xfrm/xfrm_state.c (ffffffff818fe024)
Location: arch/x86/include/asm/refcount.h:80
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup
```
```
In net/ipv6/route.c (ffffffff8191ad18)
Location: arch/x86/include/asm/refcount.h:80
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/udp.c (ffffffff8192bad3)
Location: arch/x86/include/asm/refcount.h:80
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp6_lib_lookup
```
```
In net/ipv6/raw.c (ffffffff8192ed20)
Location: arch/x86/include/asm/refcount.h:80
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/calipso.c (ffffffff8194d146)
Location: arch/x86/include/asm/refcount.h:80
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_sock_delattr
  - net/ipv6/calipso.c:calipso_sock_setattr
  - net/ipv6/calipso.c:calipso_sock_getattr
  - net/ipv6/calipso.c:calipso_opt_update
  - net/ipv6/calipso.c:calipso_doi_getdef
```
```
In net/ipv6/inet6_hashtables.c (ffffffff819532ef)
Location: arch/x86/include/asm/refcount.h:80
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In lib/klist.c (ffffffff81973a10)
Location: arch/x86/include/asm/refcount.h:80
Inline: True
```
```
In lib/kobject.c (ffffffff81974288)
Location: arch/x86/include/asm/refcount.h:80
Inline: True
Inline callers:
  - lib/kobject.c:kset_find_obj
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
In kernel/bpf/btf.c (ffffffff811c967b)
Location: arch/x86/include/asm/refcount.h:80
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_fd_by_id
```
```
In kernel/bpf/sockmap.c (ffffffff811cf790)
Location: arch/x86/include/asm/refcount.h:80
Inline: True
Inline callers:
  - kernel/bpf/sockmap.c:bpf_tcp_sendpage
  - kernel/bpf/sockmap.c:bpf_tcp_sendmsg
  - kernel/bpf/sockmap.c:bpf_tcp_recvmsg
  - kernel/bpf/sockmap.c:bpf_exec_tx_verdict
```
```
In mm/zswap.c (ffffffff812507aa)
Location: arch/x86/include/asm/refcount.h:80
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_release
```
```
In fs/notify/mark.c (ffffffff812e5820)
Location: arch/x86/include/asm/refcount.h:80
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_prepare_user_wait
```
```
In fs/posix_acl.c (ffffffff8130aecb)
Location: arch/x86/include/asm/refcount.h:80
Inline: True
Inline callers:
  - fs/posix_acl.c:get_cached_acl
```
```
In fs/proc/proc_net.c (ffffffff8132830a)
Location: arch/x86/include/asm/refcount.h:80
Inline: True
Inline callers:
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:seq_open_net
```
```
In fs/configfs/item.c (ffffffff81334341)
Location: arch/x86/include/asm/refcount.h:80
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_get_unless_zero
```
```
In fs/debugfs/file.c (ffffffff813d18d9)
Location: arch/x86/include/asm/refcount.h:80
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In ipc/util.c (ffffffff813d6895)
Location: arch/x86/include/asm/refcount.h:80
Inline: True
Inline callers:
  - ipc/util.c:ipc_rcu_getref
```
```
In security/keys/key.c (ffffffff813e50f9)
Location: arch/x86/include/asm/refcount.h:80
Inline: True
Inline callers:
  - security/keys/key.c:key_lookup
```
```
In security/keys/keyring.c (ffffffff813e6a16)
Location: arch/x86/include/asm/refcount.h:80
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/apparmor/apparmorfs.c (ffffffff814321cb)
Location: arch/x86/include/asm/refcount.h:80
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:seq_ns_name_show
  - security/apparmor/apparmorfs.c:seq_ns_level_show
  - security/apparmor/apparmorfs.c:seq_ns_nsstacked_show
  - security/apparmor/apparmorfs.c:seq_ns_stacked_show
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_attach_show
  - security/apparmor/apparmorfs.c:seq_profile_mode_show
  - security/apparmor/apparmorfs.c:seq_profile_name_show
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
```
```
In security/apparmor/task.c (ffffffff81434c08)
Location: arch/x86/include/asm/refcount.h:80
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_get_task_label
```
```
In security/apparmor/domain.c (ffffffff8143b51b)
Location: arch/x86/include/asm/refcount.h:80
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
```
```
In security/apparmor/policy.c (ffffffff8143d1e4)
Location: arch/x86/include/asm/refcount.h:80
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
```
```
In security/apparmor/procattr.c (ffffffff81440146)
Location: arch/x86/include/asm/refcount.h:80
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff81442316)
Location: arch/x86/include/asm/refcount.h:80
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_sock_graft
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_create
  - security/apparmor/lsm.c:apparmor_unix_may_send
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_task_setrlimit
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_sb_umount
  - security/apparmor/lsm.c:apparmor_sb_mount
  - security/apparmor/lsm.c:common_file_perm
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:common_perm
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/lsm.c:apparmor_cred_transfer
  - security/apparmor/lsm.c:apparmor_cred_prepare
```
```
In security/apparmor/resource.c (ffffffff814441d7)
Location: arch/x86/include/asm/refcount.h:80
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff81445968)
Location: arch/x86/include/asm/refcount.h:80
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
```
```
In security/apparmor/label.c (ffffffff814498b2)
Location: arch/x86/include/asm/refcount.h:80
Inline: True
Inline callers:
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:__vec_find
  - security/apparmor/label.c:__label_insert
```
```
In security/apparmor/mount.c (ffffffff8144aa2b)
Location: arch/x86/include/asm/refcount.h:80
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
```
```
In security/apparmor/net.c (ffffffff8144c01a)
Location: arch/x86/include/asm/refcount.h:80
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sk_perm
```
```
In security/apparmor/af_unix.c (ffffffff8144d7f2)
Location: arch/x86/include/asm/refcount.h:80
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_sock_perm
```
```
In block/blk-mq.c (ffffffff8148f663)
Location: arch/x86/include/asm/refcount.h:80
Inline: True
```
```
In block/bsg-lib.c (ffffffff814a6355)
Location: arch/x86/include/asm/refcount.h:80
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_job_get
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff8162d844)
Location: arch/x86/include/asm/refcount.h:80
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_get_by_index
```
```
In drivers/char/hw_random/core.c (ffffffff8164e529)
Location: arch/x86/include/asm/refcount.h:80
Inline: True
```
```
In drivers/dma-buf/dma-buf.c (ffffffff816e34d1)
Location: arch/x86/include/asm/refcount.h:80
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/reservation.c (ffffffff816e5489)
Location: arch/x86/include/asm/refcount.h:80
Inline: True
Inline callers:
  - drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu
  - drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
  - drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu
  - drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu
  - drivers/dma-buf/reservation.c:reservation_object_copy_fences
  - drivers/dma-buf/reservation.c:reservation_object_copy_fences
```
```
In drivers/dma-buf/sw_sync.c (ffffffff816e71cf)
Location: arch/x86/include/asm/refcount.h:80
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
```
In drivers/scsi/scsi_scan.c (ffffffff816f3acd)
Location: arch/x86/include/asm/refcount.h:80
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In net/core/sock.c (ffffffff81875b51)
Location: arch/x86/include/asm/refcount.h:80
Inline: True
```
```
In net/core/skbuff.c (ffffffff8187decf)
Location: arch/x86/include/asm/refcount.h:80
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_complete_wifi_ack
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/core/skbuff.c:skb_clone_sk
```
```
In net/core/net_namespace.c (ffffffff81887a98)
Location: arch/x86/include/asm/refcount.h:80
Inline: True
Inline callers:
  - net/core/net_namespace.c:get_net_ns_by_id
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/neighbour.c (ffffffff818a00ac)
Location: arch/x86/include/asm/refcount.h:80
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/filter.c (ffffffff818b8355)
Location: arch/x86/include/asm/refcount.h:80
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_charge
```
```
In net/core/fib_rules.c (ffffffff818c0538)
Location: arch/x86/include/asm/refcount.h:80
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_lookup
```
```
In net/ipv4/route.c (ffffffff818e3765)
Location: arch/x86/include/asm/refcount.h:80
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/inetpeer.c (ffffffff818e782a)
Location: arch/x86/include/asm/refcount.h:80
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/inet_hashtables.c (ffffffff818f1c55)
Location: arch/x86/include/asm/refcount.h:80
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff818f375b)
Location: arch/x86/include/asm/refcount.h:80
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/tcp_input.c (ffffffff818fca1b)
Location: arch/x86/include/asm/refcount.h:80
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/udp.c (ffffffff8191fe2a)
Location: arch/x86/include/asm/refcount.h:80
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp4_lib_lookup
```
```
In net/ipv4/inet_fragment.c (ffffffff81939375)
Location: arch/x86/include/asm/refcount.h:80
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81947515)
Location: arch/x86/include/asm/refcount.h:80
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_getdef
```
```
In net/xfrm/xfrm_policy.c (ffffffff8194e4c7)
Location: arch/x86/include/asm/refcount.h:80
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_lookup
```
```
In net/xfrm/xfrm_state.c (ffffffff81954b14)
Location: arch/x86/include/asm/refcount.h:80
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup
```
```
In net/ipv6/route.c (ffffffff81975650)
Location: arch/x86/include/asm/refcount.h:80
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/udp.c (ffffffff81983dc8)
Location: arch/x86/include/asm/refcount.h:80
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp6_lib_lookup
```
```
In net/ipv6/raw.c (ffffffff819879cc)
Location: arch/x86/include/asm/refcount.h:80
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/calipso.c (ffffffff819a6806)
Location: arch/x86/include/asm/refcount.h:80
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_sock_delattr
  - net/ipv6/calipso.c:calipso_sock_setattr
  - net/ipv6/calipso.c:calipso_sock_getattr
  - net/ipv6/calipso.c:calipso_opt_update
  - net/ipv6/calipso.c:calipso_doi_getdef
```
```
In net/ipv6/inet6_hashtables.c (ffffffff819acd34)
Location: arch/x86/include/asm/refcount.h:80
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In lib/klist.c (ffffffff819cfdf7)
Location: arch/x86/include/asm/refcount.h:80
Inline: True
```
```
In lib/kobject.c (ffffffff819d0b7f)
Location: arch/x86/include/asm/refcount.h:80
Inline: True
Inline callers:
  - lib/kobject.c:kset_find_obj
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
In kernel/bpf/btf.c (ffffffff811dcf7b)
Location: arch/x86/include/asm/refcount.h:83
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_fd_by_id
```
```
In mm/zswap.c (ffffffff81264c7f)
Location: arch/x86/include/asm/refcount.h:83
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_release
```
```
In mm/memcontrol.c (ffffffff81292e76)
Location: arch/x86/include/asm/refcount.h:83
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_id_get_online
```
```
In fs/notify/mark.c (ffffffff812fa412)
Location: arch/x86/include/asm/refcount.h:83
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_prepare_user_wait
```
```
In fs/posix_acl.c (ffffffff8132070b)
Location: arch/x86/include/asm/refcount.h:83
Inline: True
Inline callers:
  - fs/posix_acl.c:get_cached_acl
```
```
In fs/proc/proc_net.c (ffffffff8133f4ea)
Location: arch/x86/include/asm/refcount.h:83
Inline: True
Inline callers:
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:seq_open_net
```
```
In fs/configfs/item.c (ffffffff8134b6b1)
Location: arch/x86/include/asm/refcount.h:83
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_get_unless_zero
```
```
In fs/debugfs/file.c (ffffffff813ebfd9)
Location: arch/x86/include/asm/refcount.h:83
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In ipc/util.c (ffffffff813f0f25)
Location: arch/x86/include/asm/refcount.h:83
Inline: True
Inline callers:
  - ipc/util.c:ipc_rcu_getref
```
```
In security/keys/key.c (ffffffff813ff8c9)
Location: arch/x86/include/asm/refcount.h:83
Inline: True
Inline callers:
  - security/keys/key.c:key_lookup
```
```
In security/keys/keyring.c (ffffffff81401216)
Location: arch/x86/include/asm/refcount.h:83
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/apparmor/apparmorfs.c (ffffffff8144df47)
Location: arch/x86/include/asm/refcount.h:83
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:seq_ns_name_show
  - security/apparmor/apparmorfs.c:seq_ns_level_show
  - security/apparmor/apparmorfs.c:seq_ns_nsstacked_show
  - security/apparmor/apparmorfs.c:seq_ns_stacked_show
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_attach_show
  - security/apparmor/apparmorfs.c:seq_profile_mode_show
  - security/apparmor/apparmorfs.c:seq_profile_name_show
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
```
```
In security/apparmor/task.c (ffffffff814517eb)
Location: arch/x86/include/asm/refcount.h:83
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_get_task_label
```
```
In security/apparmor/domain.c (ffffffff81458257)
Location: arch/x86/include/asm/refcount.h:83
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
```
```
In security/apparmor/policy.c (ffffffff8145a048)
Location: arch/x86/include/asm/refcount.h:83
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
```
```
In security/apparmor/procattr.c (ffffffff8145d02e)
Location: arch/x86/include/asm/refcount.h:83
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff8145f248)
Location: arch/x86/include/asm/refcount.h:83
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_sock_graft
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_create
  - security/apparmor/lsm.c:apparmor_unix_may_send
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_task_setrlimit
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_sb_umount
  - security/apparmor/lsm.c:apparmor_sb_mount
  - security/apparmor/lsm.c:common_file_perm
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:common_perm
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/lsm.c:apparmor_cred_transfer
  - security/apparmor/lsm.c:apparmor_cred_prepare
```
```
In security/apparmor/resource.c (ffffffff81461292)
Location: arch/x86/include/asm/refcount.h:83
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff81462883)
Location: arch/x86/include/asm/refcount.h:83
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
```
```
In security/apparmor/label.c (ffffffff81466842)
Location: arch/x86/include/asm/refcount.h:83
Inline: True
Inline callers:
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:__vec_find
  - security/apparmor/label.c:__label_insert
```
```
In security/apparmor/mount.c (ffffffff8146799b)
Location: arch/x86/include/asm/refcount.h:83
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
```
```
In security/apparmor/net.c (ffffffff81468ff3)
Location: arch/x86/include/asm/refcount.h:83
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sk_perm
```
```
In security/apparmor/af_unix.c (ffffffff8146a7ae)
Location: arch/x86/include/asm/refcount.h:83
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_sock_perm
```
```
In block/blk-mq.c (ffffffff814a90e5)
Location: arch/x86/include/asm/refcount.h:83
Inline: True
```
```
In block/bsg-lib.c (ffffffff814c0355)
Location: arch/x86/include/asm/refcount.h:83
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_job_get
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff8164aca4)
Location: arch/x86/include/asm/refcount.h:83
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_get_by_index
```
```
In drivers/char/hw_random/core.c (ffffffff8166c7b9)
Location: arch/x86/include/asm/refcount.h:83
Inline: True
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81706851)
Location: arch/x86/include/asm/refcount.h:83
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/reservation.c (ffffffff81708479)
Location: arch/x86/include/asm/refcount.h:83
Inline: True
Inline callers:
  - drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu
  - drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
  - drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu
  - drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu
  - drivers/dma-buf/reservation.c:reservation_object_copy_fences
  - drivers/dma-buf/reservation.c:reservation_object_copy_fences
```
```
In drivers/dma-buf/sw_sync.c (ffffffff8170a55f)
Location: arch/x86/include/asm/refcount.h:83
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
```
In drivers/scsi/scsi_scan.c (ffffffff81717665)
Location: arch/x86/include/asm/refcount.h:83
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In net/core/sock.c (ffffffff81896341)
Location: arch/x86/include/asm/refcount.h:83
Inline: True
```
```
In net/core/skbuff.c (ffffffff8189ea9f)
Location: arch/x86/include/asm/refcount.h:83
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_complete_wifi_ack
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/core/skbuff.c:skb_clone_sk
```
```
In net/core/net_namespace.c (ffffffff818a8308)
Location: arch/x86/include/asm/refcount.h:83
Inline: True
Inline callers:
  - net/core/net_namespace.c:get_net_ns_by_id
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/neighbour.c (ffffffff818c296c)
Location: arch/x86/include/asm/refcount.h:83
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/filter.c (ffffffff818dedb5)
Location: arch/x86/include/asm/refcount.h:83
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_charge
```
```
In net/core/fib_rules.c (ffffffff818e9488)
Location: arch/x86/include/asm/refcount.h:83
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_lookup
```
```
In net/core/sock_map.c (ffffffff818f1ff6)
Location: arch/x86/include/asm/refcount.h:83
Inline: True
```
```
In net/sched/cls_api.c (ffffffff818fdb34)
Location: arch/x86/include/asm/refcount.h:83
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_refcnt_get
```
```
In net/ipv4/route.c (ffffffff81910615)
Location: arch/x86/include/asm/refcount.h:83
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/inetpeer.c (ffffffff819146da)
Location: arch/x86/include/asm/refcount.h:83
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/inet_hashtables.c (ffffffff8191f7f9)
Location: arch/x86/include/asm/refcount.h:83
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff8192127b)
Location: arch/x86/include/asm/refcount.h:83
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/tcp_input.c (ffffffff8192ab8b)
Location: arch/x86/include/asm/refcount.h:83
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/udp.c (ffffffff8194ea88)
Location: arch/x86/include/asm/refcount.h:83
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp4_lib_lookup
```
```
In net/ipv4/inet_fragment.c (ffffffff81968f4f)
Location: arch/x86/include/asm/refcount.h:83
Inline: True
```
```
In net/ipv4/tcp_bpf.c (ffffffff819776e9)
Location: arch/x86/include/asm/refcount.h:83
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/ipv4/cipso_ipv4.c (ffffffff819790e5)
Location: arch/x86/include/asm/refcount.h:83
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_getdef
```
```
In net/xfrm/xfrm_policy.c (ffffffff819817e4)
Location: arch/x86/include/asm/refcount.h:83
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_lookup
```
```
In net/xfrm/xfrm_state.c (ffffffff81989376)
Location: arch/x86/include/asm/refcount.h:83
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup
```
```
In net/ipv6/route.c (ffffffff819ab290)
Location: arch/x86/include/asm/refcount.h:83
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/udp.c (ffffffff819ba30c)
Location: arch/x86/include/asm/refcount.h:83
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp6_lib_lookup
```
```
In net/ipv6/raw.c (ffffffff819be30e)
Location: arch/x86/include/asm/refcount.h:83
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/calipso.c (ffffffff819dd366)
Location: arch/x86/include/asm/refcount.h:83
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_sock_delattr
  - net/ipv6/calipso.c:calipso_sock_setattr
  - net/ipv6/calipso.c:calipso_sock_getattr
  - net/ipv6/calipso.c:calipso_opt_update
  - net/ipv6/calipso.c:calipso_doi_getdef
```
```
In net/ipv6/inet6_hashtables.c (ffffffff819e36f4)
Location: arch/x86/include/asm/refcount.h:83
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In lib/klist.c (ffffffff81a09437)
Location: arch/x86/include/asm/refcount.h:83
Inline: True
```
```
In lib/kobject.c (ffffffff81a09e1f)
Location: arch/x86/include/asm/refcount.h:83
Inline: True
Inline callers:
  - lib/kobject.c:kset_find_obj
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
In arch/x86/kernel/process.c (ffffffff8103d722)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:get_wchan
```
```
In kernel/sched/core.c (ffffffff810c9f08)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
```
```
In kernel/sched/fair.c (ffffffff810debbf)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_fault
```
```
In kernel/stacktrace.c (ffffffff81126067)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - kernel/stacktrace.c:stack_trace_save_tsk_reliable
  - kernel/stacktrace.c:stack_trace_save_tsk
```
```
In kernel/futex.c (ffffffff81141e68)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - kernel/futex.c:exit_pi_state_list
  - kernel/futex.c:get_pi_state
```
```
In kernel/bpf/btf.c (ffffffff811f25d9)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_fd_by_id
```
```
In kernel/events/core.c (ffffffff8120658a)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:ring_buffer_get
  - kernel/events/core.c:perf_lock_task_context
```
```
In kernel/events/ring_buffer.c (ffffffff8120afdf)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_begin
```
```
In mm/zswap.c (ffffffff8127f89b)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_release
```
```
In mm/memcontrol.c (ffffffff812adb7a)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_id_get_online
```
```
In mm/hmm.c (ffffffff812c4107)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - mm/hmm.c:hmm_mirror_register
  - mm/hmm.c:hmm_invalidate_range_end
  - mm/hmm.c:hmm_invalidate_range_start
  - mm/hmm.c:hmm_release
```
```
In fs/notify/mark.c (ffffffff8131ae10)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_prepare_user_wait
```
```
In fs/posix_acl.c (ffffffff81347fb8)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - fs/posix_acl.c:get_cached_acl
```
```
In fs/proc/array.c (ffffffff81361750)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In fs/proc/proc_net.c (ffffffff8136781b)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:seq_open_net
```
```
In fs/configfs/item.c (ffffffff81374275)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_get_unless_zero
```
```
In fs/debugfs/file.c (ffffffff8141822c)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In ipc/util.c (ffffffff8141d1fd)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - ipc/util.c:ipc_rcu_getref
```
```
In security/keys/key.c (ffffffff8142c009)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - security/keys/key.c:key_lookup
```
```
In security/keys/keyring.c (ffffffff8142da32)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/apparmor/apparmorfs.c (ffffffff8147b8b8)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:seq_ns_name_show
  - security/apparmor/apparmorfs.c:seq_ns_level_show
  - security/apparmor/apparmorfs.c:seq_ns_nsstacked_show
  - security/apparmor/apparmorfs.c:seq_ns_stacked_show
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_attach_show
  - security/apparmor/apparmorfs.c:seq_profile_mode_show
  - security/apparmor/apparmorfs.c:seq_profile_name_show
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
```
```
In security/apparmor/task.c (ffffffff8147f223)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_get_task_label
```
```
In security/apparmor/domain.c (ffffffff81485a0d)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
```
```
In security/apparmor/policy.c (ffffffff814876c1)
Location: arch/x86/include/asm/refcount.h:97
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
In security/apparmor/procattr.c (ffffffff8148a5ce)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff8148c6c9)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_sock_graft
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_create
  - security/apparmor/lsm.c:apparmor_unix_may_send
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_task_setrlimit
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_sb_umount
  - security/apparmor/lsm.c:apparmor_sb_mount
  - security/apparmor/lsm.c:common_file_perm
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:common_perm
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/lsm.c:apparmor_cred_transfer
  - security/apparmor/lsm.c:apparmor_cred_prepare
```
```
In security/apparmor/resource.c (ffffffff8148e587)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff8148fb4e)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
```
```
In security/apparmor/label.c (ffffffff814918e8)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:__vec_find
  - security/apparmor/label.c:__label_insert
```
```
In security/apparmor/mount.c (ffffffff81494a14)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
```
```
In security/apparmor/net.c (ffffffff8149604e)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sk_perm
```
```
In security/apparmor/af_unix.c (ffffffff814977cf)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_sock_perm
```
```
In block/blk-mq.c (ffffffff814d6a97)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
```
```
In block/bsg-lib.c (ffffffff814eeb5d)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_job_get
```
```
In lib/syscall.c (ffffffff815323ad)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff8167f7f9)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_get_by_index
```
```
In drivers/char/hw_random/core.c (ffffffff816a23a9)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
```
```
In drivers/dma-buf/dma-buf.c (ffffffff817419b9)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff817434d0)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
```
```
In drivers/dma-buf/reservation.c (ffffffff81744025)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu
  - drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
  - drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu
  - drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu
  - drivers/dma-buf/reservation.c:reservation_object_copy_fences
  - drivers/dma-buf/reservation.c:reservation_object_copy_fences
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81745e65)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
```
In drivers/scsi/scsi_scan.c (ffffffff81752361)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In net/core/sock.c (ffffffff818e15f8)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
```
```
In net/core/skbuff.c (ffffffff818e931a)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_complete_wifi_ack
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/core/skbuff.c:skb_clone_sk
```
```
In net/core/net_namespace.c (ffffffff818f3885)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/core/net_namespace.c:get_net_ns_by_id
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/neighbour.c (ffffffff8190f056)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/filter.c (ffffffff8192ccf5)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_charge
```
```
In net/core/fib_rules.c (ffffffff81938ec1)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_lookup
```
```
In net/core/sock_map.c (ffffffff81944579)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
```
```
In net/core/bpf_sk_storage.c (ffffffff8195371d)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
```
```
In net/sched/cls_api.c (ffffffff8195d471)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_refcnt_get
```
```
In net/ipv4/route.c (ffffffff81973079)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/inetpeer.c (ffffffff81976c3c)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/inet_hashtables.c (ffffffff8198214f)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81983c37)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/tcp_input.c (ffffffff8198dddb)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/udp.c (ffffffff819b3268)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp4_lib_lookup
```
```
In net/ipv4/fib_semantics.c (ffffffff819c8f55)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/inet_fragment.c (ffffffff819cfe57)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff819d4f8e)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
```
```
In net/ipv4/tcp_bpf.c (ffffffff819e121c)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/ipv4/cipso_ipv4.c (ffffffff819e2bf8)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_getdef
```
```
In net/xfrm/xfrm_policy.c (ffffffff819eb58f)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_lookup
```
```
In net/xfrm/xfrm_state.c (ffffffff819f31a2)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup
```
```
In net/ipv6/addrconf.c (ffffffff81a06893)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
```
```
In net/ipv6/route.c (ffffffff81a1bd58)
Location: arch/x86/include/asm/refcount.h:97
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
In net/ipv6/udp.c (ffffffff81a29488)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp6_lib_lookup
```
```
In net/ipv6/raw.c (ffffffff81a2d5d7)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/calipso.c (ffffffff81a4c366)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_sock_delattr
  - net/ipv6/calipso.c:calipso_sock_setattr
  - net/ipv6/calipso.c:calipso_sock_getattr
  - net/ipv6/calipso.c:calipso_opt_update
  - net/ipv6/calipso.c:calipso_doi_getdef
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a5241a)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In lib/klist.c (ffffffff81a78dd7)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
```
```
In lib/kobject.c (ffffffff81a79694)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - lib/kobject.c:kset_find_obj
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
In arch/x86/kernel/process.c (ffffffff8103dee2)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:get_wchan
```
```
In kernel/sched/core.c (ffffffff810d3118)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
```
```
In kernel/sched/fair.c (ffffffff810e910f)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_fault
```
```
In kernel/stacktrace.c (ffffffff81132037)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - kernel/stacktrace.c:stack_trace_save_tsk_reliable
  - kernel/stacktrace.c:stack_trace_save_tsk
```
```
In kernel/futex.c (ffffffff8114c0af)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:get_pi_state
```
```
In kernel/bpf/btf.c (ffffffff811fecf9)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_fd_by_id
```
```
In kernel/events/core.c (ffffffff8121392d)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:ring_buffer_get
  - kernel/events/core.c:perf_lock_task_context
```
```
In kernel/events/ring_buffer.c (ffffffff812182bf)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_begin
```
```
In mm/zswap.c (ffffffff8128f68b)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_release
```
```
In mm/memcontrol.c (ffffffff812bf6ca)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_id_get_online
```
```
In fs/notify/mark.c (ffffffff8132da00)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_prepare_user_wait
```
```
In fs/crypto/keyring.c (ffffffff8134c6ab)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - fs/crypto/keyring.c:add_master_key
```
```
In fs/posix_acl.c (ffffffff81360258)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - fs/posix_acl.c:get_cached_acl
```
```
In fs/proc/array.c (ffffffff813799b0)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In fs/proc/proc_net.c (ffffffff8137fa9b)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:seq_open_net
```
```
In fs/configfs/item.c (ffffffff8138c4f5)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_get_unless_zero
```
```
In fs/debugfs/file.c (ffffffff814320ec)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In ipc/util.c (ffffffff8143704d)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - ipc/util.c:ipc_rcu_getref
```
```
In security/keys/key.c (ffffffff81445d59)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - security/keys/key.c:key_lookup
```
```
In security/keys/keyring.c (ffffffff81447782)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/apparmor/apparmorfs.c (ffffffff81495588)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:seq_ns_name_show
  - security/apparmor/apparmorfs.c:seq_ns_level_show
  - security/apparmor/apparmorfs.c:seq_ns_nsstacked_show
  - security/apparmor/apparmorfs.c:seq_ns_stacked_show
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_attach_show
  - security/apparmor/apparmorfs.c:seq_profile_mode_show
  - security/apparmor/apparmorfs.c:seq_profile_name_show
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
```
```
In security/apparmor/task.c (ffffffff81498f23)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_get_task_label
```
```
In security/apparmor/domain.c (ffffffff8149f8f4)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:apparmor_bprm_set_creds
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
In security/apparmor/policy.c (ffffffff814a1571)
Location: arch/x86/include/asm/refcount.h:97
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
In security/apparmor/procattr.c (ffffffff814a448e)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff814a6589)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_sock_graft
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_create
  - security/apparmor/lsm.c:apparmor_unix_may_send
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_task_setrlimit
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_sb_umount
  - security/apparmor/lsm.c:apparmor_sb_mount
  - security/apparmor/lsm.c:common_file_perm
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:common_perm
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/lsm.c:apparmor_cred_transfer
  - security/apparmor/lsm.c:apparmor_cred_prepare
```
```
In security/apparmor/resource.c (ffffffff814a8447)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff814a9a0e)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
```
```
In security/apparmor/label.c (ffffffff814ab818)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:__vec_find
  - security/apparmor/label.c:__label_insert
```
```
In security/apparmor/mount.c (ffffffff814ae944)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
```
```
In security/apparmor/net.c (ffffffff814aff7e)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sk_perm
```
```
In security/apparmor/af_unix.c (ffffffff814b16ff)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_sock_perm
```
```
In block/blk-mq.c (ffffffff814efdfc)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
```
```
In block/bsg-lib.c (ffffffff81507fbd)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_job_get
```
```
In lib/syscall.c (ffffffff815531ed)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
```
```
In drivers/tty/vt/vt.c (ffffffff8169e158)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:con_install
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff816a1ea9)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_get_by_index
```
```
In drivers/char/hw_random/core.c (ffffffff816c514a)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81765b41)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff8176747c)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
```
```
In drivers/dma-buf/dma-resv.c (ffffffff8176817f)
Location: arch/x86/include/asm/refcount.h:97
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
In drivers/dma-buf/sw_sync.c (ffffffff81769fc1)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
```
In drivers/scsi/scsi_scan.c (ffffffff817765e1)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/edac/ghes_edac.c (ffffffff818bce72)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - drivers/edac/ghes_edac.c:ghes_edac_register
```
```
In net/core/sock.c (ffffffff819137e8)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
```
```
In net/core/skbuff.c (ffffffff8191b47a)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_complete_wifi_ack
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/core/skbuff.c:skb_clone_sk
```
```
In net/core/net_namespace.c (ffffffff81925835)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/core/net_namespace.c:get_net_ns_by_id
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/neighbour.c (ffffffff819416c6)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/filter.c (ffffffff8195eff5)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_charge
```
```
In net/core/fib_rules.c (ffffffff8196bd81)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_lookup
```
```
In net/core/sock_map.c (ffffffff81979579)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
```
```
In net/core/bpf_sk_storage.c (ffffffff81989abd)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
```
```
In net/sched/cls_api.c (ffffffff81993971)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_refcnt_get
```
```
In net/ipv4/route.c (ffffffff819a99ec)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/inetpeer.c (ffffffff819ad5cc)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/inet_hashtables.c (ffffffff819b89af)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff819ba417)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/tcp_input.c (ffffffff819c49ab)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/udp.c (ffffffff819e9feb)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp4_lib_lookup
```
```
In net/ipv4/fib_semantics.c (ffffffff819ffb15)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/inet_fragment.c (ffffffff81a069e7)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81a0baee)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
```
```
In net/ipv4/tcp_bpf.c (ffffffff81a185dc)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81a19be8)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_getdef
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a2258f)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_lookup
```
```
In net/xfrm/xfrm_state.c (ffffffff81a2a072)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup
```
```
In net/ipv6/addrconf.c (ffffffff81a3d403)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
```
```
In net/ipv6/route.c (ffffffff81a529d8)
Location: arch/x86/include/asm/refcount.h:97
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
In net/ipv6/udp.c (ffffffff81a5ffe4)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp6_lib_lookup
```
```
In net/ipv6/raw.c (ffffffff81a6413d)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/calipso.c (ffffffff81a82f36)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_sock_delattr
  - net/ipv6/calipso.c:calipso_sock_setattr
  - net/ipv6/calipso.c:calipso_sock_getattr
  - net/ipv6/calipso.c:calipso_opt_update
  - net/ipv6/calipso.c:calipso_doi_getdef
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a8902a)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In lib/klist.c (ffffffff81ab0187)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
```
```
In lib/kobject.c (ffffffff81ab09f4)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - lib/kobject.c:kset_find_obj
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
In arch/x86/kernel/process.c (ffffffff81040fa4)
Location: include/linux/refcount.h:168
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:get_wchan
```
```
In kernel/sched/core.c (ffffffff810dcdb5)
Location: include/linux/refcount.h:168
Inline: True
```
```
In kernel/sched/fair.c (ffffffff810ef258)
Location: include/linux/refcount.h:168
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_group
```
```
In kernel/stacktrace.c (ffffffff81141468)
Location: include/linux/refcount.h:168
Inline: True
Inline callers:
  - kernel/stacktrace.c:stack_trace_save_tsk_reliable
  - kernel/stacktrace.c:stack_trace_save_tsk
```
```
In kernel/futex.c (ffffffff8115c38e)
Location: include/linux/refcount.h:168
Inline: True
Inline callers:
  - kernel/futex.c:exit_pi_state_list
```
```
In kernel/bpf/btf.c (ffffffff812260dc)
Location: include/linux/refcount.h:168
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_fd_by_id
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff8123013d)
Location: include/linux/refcount.h:168
Inline: True
Inline callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_get
```
```
In kernel/events/core.c (ffffffff8123451a)
Location: include/linux/refcount.h:168
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_ctx_lock_double
  - kernel/events/core.c:ring_buffer_get
  - kernel/events/core.c:perf_lock_task_context
```
```
In kernel/events/ring_buffer.c (ffffffff81243e1f)
Location: include/linux/refcount.h:168
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_begin
```
```
In mm/zswap.c (ffffffff812c2323)
Location: include/linux/refcount.h:168
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_pool_release
  - mm/zswap.c:zswap_pool_find_get
  - mm/zswap.c:zswap_pool_last_get
```
```
In mm/memcontrol.c (ffffffff812f5e6e)
Location: include/linux/refcount.h:168
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_id_get_online
```
```
In fs/notify/mark.c (ffffffff81367b02)
Location: include/linux/refcount.h:168
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_prepare_user_wait
```
```
In fs/io_uring.c (ffffffff81385e4e)
Location: include/linux/refcount.h:168
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_cancel_files
  - fs/io_uring.c:io_link_timeout_fn
```
```
In fs/io-wq.c (ffffffff8138b633)
Location: include/linux/refcount.h:168
Inline: True
Inline callers:
  - fs/io-wq.c:io_wq_get
```
```
In fs/crypto/keyring.c (ffffffff81392666)
Location: include/linux/refcount.h:168
Inline: True
Inline callers:
  - fs/crypto/keyring.c:do_add_master_key
```
```
In fs/posix_acl.c (ffffffff813a5d8d)
Location: include/linux/refcount.h:168
Inline: True
Inline callers:
  - fs/posix_acl.c:get_cached_acl
```
```
In fs/proc/array.c (ffffffff813c2a61)
Location: include/linux/refcount.h:168
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In fs/proc/proc_net.c (ffffffff813c9a71)
Location: include/linux/refcount.h:168
Inline: True
Inline callers:
  - fs/proc/proc_net.c:get_proc_net
```
```
In fs/configfs/item.c (ffffffff813d78e6)
Location: include/linux/refcount.h:168
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_get_unless_zero
```
```
In fs/debugfs/file.c (ffffffff81482500)
Location: include/linux/refcount.h:168
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In ipc/util.c (ffffffff8148715d)
Location: include/linux/refcount.h:168
Inline: True
Inline callers:
  - ipc/util.c:ipc_rcu_getref
```
```
In security/keys/key.c (ffffffff8149767f)
Location: include/linux/refcount.h:168
Inline: True
Inline callers:
  - security/keys/key.c:key_lookup
```
```
In security/keys/keyring.c (ffffffff81498efa)
Location: include/linux/refcount.h:168
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/apparmor/apparmorfs.c (ffffffff814ed7b3)
Location: include/linux/refcount.h:168
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
In security/apparmor/task.c (ffffffff814f15d1)
Location: include/linux/refcount.h:168
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_get_task_label
```
```
In security/apparmor/domain.c (ffffffff814f8f9e)
Location: include/linux/refcount.h:168
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
In security/apparmor/policy.c (ffffffff814fb729)
Location: include/linux/refcount.h:168
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
In security/apparmor/procattr.c (ffffffff814ff33d)
Location: include/linux/refcount.h:168
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff81501432)
Location: include/linux/refcount.h:168
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
In security/apparmor/resource.c (ffffffff8150592a)
Location: include/linux/refcount.h:168
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff815074ad)
Location: include/linux/refcount.h:168
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:aa_file_perm
```
```
In security/apparmor/label.c (ffffffff8150a48c)
Location: include/linux/refcount.h:168
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
In security/apparmor/mount.c (ffffffff8150dc6e)
Location: include/linux/refcount.h:168
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
```
```
In security/apparmor/net.c (ffffffff8150f3ee)
Location: include/linux/refcount.h:168
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sk_perm
```
```
In security/apparmor/af_unix.c (ffffffff8150f9be)
Location: include/linux/refcount.h:168
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:begin_current_label_crit_section
```
```
In block/blk-mq.c (ffffffff8154f1ec)
Location: include/linux/refcount.h:168
Inline: True
```
```
In block/bsg-lib.c (ffffffff815695bc)
Location: include/linux/refcount.h:168
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_job_get
```
```
In lib/syscall.c (ffffffff815dc5c0)
Location: include/linux/refcount.h:168
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
```
```
In lib/klist.c (ffffffff815ea0d1)
Location: include/linux/refcount.h:168
Inline: True
```
```
In lib/kobject.c (ffffffff815eaad1)
Location: include/linux/refcount.h:168
Inline: True
Inline callers:
  - lib/kobject.c:kobject_get_unless_zero
```
```
In drivers/dma/dmaengine.c (ffffffff81707804)
Location: include/linux/refcount.h:168
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_chan_get
```
```
In drivers/tty/vt/vt.c (ffffffff81750fd1)
Location: include/linux/refcount.h:168
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:con_install
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81754fdd)
Location: include/linux/refcount.h:168
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_get_by_index
```
```
In drivers/char/hw_random/core.c (ffffffff817791b1)
Location: include/linux/refcount.h:168
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:hwrng_init
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81825dfe)
Location: include/linux/refcount.h:168
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff81827b39)
Location: include/linux/refcount.h:168
Inline: True
```
```
In drivers/dma-buf/dma-resv.c (ffffffff818296c1)
Location: include/linux/refcount.h:168
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
In drivers/dma-buf/sw_sync.c (ffffffff8182bf2f)
Location: include/linux/refcount.h:168
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_pt_create
```
```
In drivers/scsi/scsi_scan.c (ffffffff818398cd)
Location: include/linux/refcount.h:168
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/edac/ghes_edac.c (ffffffff8198d4c2)
Location: include/linux/refcount.h:168
Inline: True
Inline callers:
  - drivers/edac/ghes_edac.c:ghes_edac_register
```
```
In net/core/sock.c (ffffffff819e6ae3)
Location: include/linux/refcount.h:168
Inline: True
```
```
In net/core/skbuff.c (ffffffff819ee2cc)
Location: include/linux/refcount.h:168
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_complete_wifi_ack
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/core/skbuff.c:skb_clone_sk
```
```
In net/core/net_namespace.c (ffffffff819f99bd)
Location: include/linux/refcount.h:168
Inline: True
Inline callers:
  - net/core/net_namespace.c:get_net_ns_by_id
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/neighbour.c (ffffffff81a11b76)
Location: include/linux/refcount.h:168
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/filter.c (ffffffff81a2d113)
Location: include/linux/refcount.h:168
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_assign
  - net/core/filter.c:sk_filter_charge
```
```
In net/core/fib_rules.c (ffffffff81a3f9b1)
Location: include/linux/refcount.h:168
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_lookup
```
```
In net/core/sock_map.c (ffffffff81a4efdc)
Location: include/linux/refcount.h:168
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_lookup
  - net/core/sock_map.c:sock_map_lookup
  - net/core/sock_map.c:sock_map_link_no_progs
  - net/core/sock_map.c:sock_map_link
```
```
In net/core/bpf_sk_storage.c (ffffffff81a61177)
Location: include/linux/refcount.h:168
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
```
```
In net/sched/cls_api.c (ffffffff81a6c916)
Location: include/linux/refcount.h:168
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_refcnt_get
```
```
In net/ipv4/route.c (ffffffff81a92e21)
Location: include/linux/refcount.h:168
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/inetpeer.c (ffffffff81a9756a)
Location: include/linux/refcount.h:168
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/inet_hashtables.c (ffffffff81aa330e)
Location: include/linux/refcount.h:168
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81aa4efb)
Location: include/linux/refcount.h:168
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/tcp_input.c (ffffffff81ab0b7b)
Location: include/linux/refcount.h:168
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/udp.c (ffffffff81ad7c36)
Location: include/linux/refcount.h:168
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp4_lib_lookup
```
```
In net/ipv4/fib_semantics.c (ffffffff81aef220)
Location: include/linux/refcount.h:168
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/inet_fragment.c (ffffffff81af640e)
Location: include/linux/refcount.h:168
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81afcf97)
Location: include/linux/refcount.h:168
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_create_group
```
```
In net/ipv4/tcp_bpf.c (ffffffff81b0931b)
Location: include/linux/refcount.h:168
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81b0b24f)
Location: include/linux/refcount.h:168
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_getdef
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b14578)
Location: include/linux/refcount.h:168
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_lookup
```
```
In net/xfrm/xfrm_state.c (ffffffff81b1c831)
Location: include/linux/refcount.h:168
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/ipv6/addrconf.c (ffffffff81b332b3)
Location: include/linux/refcount.h:168
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
```
```
In net/ipv6/route.c (ffffffff81b49c5b)
Location: include/linux/refcount.h:168
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
In net/ipv6/udp.c (ffffffff81b58ae7)
Location: include/linux/refcount.h:168
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp6_lib_lookup
```
```
In net/ipv6/raw.c (ffffffff81b5cbac)
Location: include/linux/refcount.h:168
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/calipso.c (ffffffff81b7d3f7)
Location: include/linux/refcount.h:168
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_sock_delattr
  - net/ipv6/calipso.c:calipso_sock_setattr
  - net/ipv6/calipso.c:calipso_sock_getattr
  - net/ipv6/calipso.c:calipso_opt_update
  - net/ipv6/calipso.c:calipso_doi_getdef
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81b847a0)
Location: include/linux/refcount.h:168
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
</details>
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
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff8103e062)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:get_wchan
```
```
In kernel/sched/core.c (ffffffff810cd438)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
```
```
In kernel/sched/fair.c (ffffffff810e32bf)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_fault
```
```
In kernel/stacktrace.c (ffffffff8112a7e7)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - kernel/stacktrace.c:stack_trace_save_tsk_reliable
  - kernel/stacktrace.c:stack_trace_save_tsk
```
```
In kernel/futex.c (ffffffff811446cf)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:get_pi_state
```
```
In kernel/bpf/btf.c (ffffffff811f7319)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_fd_by_id
```
```
In kernel/events/core.c (ffffffff8120bf7d)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:ring_buffer_get
  - kernel/events/core.c:perf_lock_task_context
```
```
In kernel/events/ring_buffer.c (ffffffff8121090f)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_begin
```
```
In mm/zswap.c (ffffffff81287c6b)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_release
```
```
In mm/memcontrol.c (ffffffff812b7caa)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_id_get_online
```
```
In fs/notify/mark.c (ffffffff81325fe0)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_prepare_user_wait
```
```
In fs/crypto/keyring.c (ffffffff81344c8b)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - fs/crypto/keyring.c:add_master_key
```
```
In fs/posix_acl.c (ffffffff81358838)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - fs/posix_acl.c:get_cached_acl
```
```
In fs/proc/array.c (ffffffff81371f90)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In fs/proc/proc_net.c (ffffffff8137807b)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:seq_open_net
```
```
In fs/configfs/item.c (ffffffff81384ad5)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_get_unless_zero
```
```
In fs/debugfs/file.c (ffffffff8142a6cc)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In ipc/util.c (ffffffff8142f62d)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - ipc/util.c:ipc_rcu_getref
```
```
In security/keys/key.c (ffffffff8143e339)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - security/keys/key.c:key_lookup
```
```
In security/keys/keyring.c (ffffffff8143fd62)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/apparmor/apparmorfs.c (ffffffff8148db68)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:seq_ns_name_show
  - security/apparmor/apparmorfs.c:seq_ns_level_show
  - security/apparmor/apparmorfs.c:seq_ns_nsstacked_show
  - security/apparmor/apparmorfs.c:seq_ns_stacked_show
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_attach_show
  - security/apparmor/apparmorfs.c:seq_profile_mode_show
  - security/apparmor/apparmorfs.c:seq_profile_name_show
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
```
```
In security/apparmor/task.c (ffffffff81491503)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_get_task_label
```
```
In security/apparmor/domain.c (ffffffff81497ed4)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:apparmor_bprm_set_creds
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
In security/apparmor/policy.c (ffffffff81499b51)
Location: arch/x86/include/asm/refcount.h:97
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
In security/apparmor/procattr.c (ffffffff8149ca6e)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff8149eb69)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_sock_graft
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_create
  - security/apparmor/lsm.c:apparmor_unix_may_send
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_task_setrlimit
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_sb_umount
  - security/apparmor/lsm.c:apparmor_sb_mount
  - security/apparmor/lsm.c:common_file_perm
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:common_perm
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/lsm.c:apparmor_cred_transfer
  - security/apparmor/lsm.c:apparmor_cred_prepare
```
```
In security/apparmor/resource.c (ffffffff814a0a27)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff814a1fee)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
```
```
In security/apparmor/label.c (ffffffff814a3df8)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:__vec_find
  - security/apparmor/label.c:__label_insert
```
```
In security/apparmor/mount.c (ffffffff814a6f24)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
```
```
In security/apparmor/net.c (ffffffff814a855e)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sk_perm
```
```
In security/apparmor/af_unix.c (ffffffff814a9cdf)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_sock_perm
```
```
In block/blk-mq.c (ffffffff814e83dc)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
```
```
In block/bsg-lib.c (ffffffff8150059d)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_job_get
```
```
In lib/syscall.c (ffffffff8154b7cd)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
```
```
In drivers/tty/vt/vt.c (ffffffff81663bb8)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:con_install
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81667909)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_get_by_index
```
```
In drivers/char/hw_random/core.c (ffffffff8168ab9a)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
```
```
In drivers/dma-buf/dma-buf.c (ffffffff8171a231)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff8171bb6c)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
```
```
In drivers/dma-buf/dma-resv.c (ffffffff8171c86f)
Location: arch/x86/include/asm/refcount.h:97
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
In drivers/dma-buf/sw_sync.c (ffffffff8171e6b1)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
```
In drivers/scsi/scsi_scan.c (ffffffff8172acd1)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/nvme/host/core.c (ffffffff81746f9e)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:nvme_alloc_ns
  - drivers/nvme/host/core.c:nvme_find_get_ns
  - drivers/nvme/host/core.c:nvme_init_subsystem
  - drivers/nvme/host/core.c:nvme_ns_head_open
  - drivers/nvme/host/core.c:nvme_open
```
```
In net/core/sock.c (ffffffff818b37e8)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
```
```
In net/core/skbuff.c (ffffffff818bb47a)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_complete_wifi_ack
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/core/skbuff.c:skb_clone_sk
```
```
In net/core/net_namespace.c (ffffffff818c5835)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/core/net_namespace.c:get_net_ns_by_id
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/neighbour.c (ffffffff818e1696)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/filter.c (ffffffff818fefc5)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_charge
```
```
In net/core/fib_rules.c (ffffffff8190bd51)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_lookup
```
```
In net/core/sock_map.c (ffffffff819193e9)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
```
```
In net/core/bpf_sk_storage.c (ffffffff8192992d)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
```
```
In net/sched/cls_api.c (ffffffff819337e1)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_refcnt_get
```
```
In net/ipv4/route.c (ffffffff8194985c)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/inetpeer.c (ffffffff8194d43c)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/inet_hashtables.c (ffffffff8195881f)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff8195a287)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/tcp_input.c (ffffffff8196481b)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/udp.c (ffffffff81989e5b)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp4_lib_lookup
```
```
In net/ipv4/fib_semantics.c (ffffffff8199f8b5)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/inet_fragment.c (ffffffff819a6787)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff819ab88e)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
```
```
In net/ipv4/tcp_bpf.c (ffffffff819b7c6c)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/ipv4/cipso_ipv4.c (ffffffff819b9278)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_getdef
```
```
In net/xfrm/xfrm_policy.c (ffffffff819c1c1f)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_lookup
```
```
In net/xfrm/xfrm_state.c (ffffffff819c9702)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup
```
```
In net/ipv6/addrconf.c (ffffffff819dca93)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
```
```
In net/ipv6/route.c (ffffffff819f2068)
Location: arch/x86/include/asm/refcount.h:97
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
In net/ipv6/udp.c (ffffffff819ff674)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp6_lib_lookup
```
```
In net/ipv6/raw.c (ffffffff81a037cd)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/calipso.c (ffffffff81a225c6)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_sock_delattr
  - net/ipv6/calipso.c:calipso_sock_setattr
  - net/ipv6/calipso.c:calipso_sock_getattr
  - net/ipv6/calipso.c:calipso_opt_update
  - net/ipv6/calipso.c:calipso_doi_getdef
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a286ba)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In lib/klist.c (ffffffff81a4efd7)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
```
```
In lib/kobject.c (ffffffff81a4f844)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - lib/kobject.c:kset_find_obj
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
In arch/x86/kernel/process.c (ffffffff8102d872)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:get_wchan
```
```
In kernel/sched/core.c (ffffffff810bbc98)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
```
```
In kernel/sched/fair.c (ffffffff810d23cf)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_fault
```
```
In kernel/stacktrace.c (ffffffff8111d057)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - kernel/stacktrace.c:stack_trace_save_tsk_reliable
  - kernel/stacktrace.c:stack_trace_save_tsk
```
```
In kernel/futex.c (ffffffff81136eff)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:get_pi_state
```
```
In kernel/bpf/btf.c (ffffffff811ea069)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_fd_by_id
```
```
In kernel/events/core.c (ffffffff811fed4d)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:ring_buffer_get
  - kernel/events/core.c:perf_lock_task_context
```
```
In kernel/events/ring_buffer.c (ffffffff8120369f)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_begin
```
```
In mm/zswap.c (ffffffff81279acb)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_release
```
```
In mm/memcontrol.c (ffffffff812a8e7a)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_id_get_online
```
```
In fs/notify/mark.c (ffffffff81316b80)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_prepare_user_wait
```
```
In fs/crypto/keyring.c (ffffffff8133596b)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - fs/crypto/keyring.c:add_master_key
```
```
In fs/posix_acl.c (ffffffff813494e8)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - fs/posix_acl.c:get_cached_acl
```
```
In fs/proc/array.c (ffffffff81362a69)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In fs/proc/proc_net.c (ffffffff81368b4b)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:seq_open_net
```
```
In fs/configfs/item.c (ffffffff81375565)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_get_unless_zero
```
```
In fs/debugfs/file.c (ffffffff8141b14c)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In ipc/util.c (ffffffff814200ad)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - ipc/util.c:ipc_rcu_getref
```
```
In security/keys/key.c (ffffffff8142eda9)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - security/keys/key.c:key_lookup
```
```
In security/keys/keyring.c (ffffffff814307d2)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/apparmor/apparmorfs.c (ffffffff8147e588)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:seq_ns_name_show
  - security/apparmor/apparmorfs.c:seq_ns_level_show
  - security/apparmor/apparmorfs.c:seq_ns_nsstacked_show
  - security/apparmor/apparmorfs.c:seq_ns_stacked_show
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_attach_show
  - security/apparmor/apparmorfs.c:seq_profile_mode_show
  - security/apparmor/apparmorfs.c:seq_profile_name_show
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
```
```
In security/apparmor/task.c (ffffffff81481f23)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_get_task_label
```
```
In security/apparmor/domain.c (ffffffff814888f4)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:apparmor_bprm_set_creds
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
In security/apparmor/policy.c (ffffffff8148a571)
Location: arch/x86/include/asm/refcount.h:97
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
In security/apparmor/procattr.c (ffffffff8148d48e)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff8148f589)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_sock_graft
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_create
  - security/apparmor/lsm.c:apparmor_unix_may_send
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_task_setrlimit
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_sb_umount
  - security/apparmor/lsm.c:apparmor_sb_mount
  - security/apparmor/lsm.c:common_file_perm
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:common_perm
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/lsm.c:apparmor_cred_transfer
  - security/apparmor/lsm.c:apparmor_cred_prepare
```
```
In security/apparmor/resource.c (ffffffff81491447)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff81492a0e)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
```
```
In security/apparmor/label.c (ffffffff81494818)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:__vec_find
  - security/apparmor/label.c:__label_insert
```
```
In security/apparmor/mount.c (ffffffff81497944)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
```
```
In security/apparmor/net.c (ffffffff81498f7e)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sk_perm
```
```
In security/apparmor/af_unix.c (ffffffff8149a6ff)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_sock_perm
```
```
In block/blk-mq.c (ffffffff814d894c)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
```
```
In block/bsg-lib.c (ffffffff814f0aad)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_job_get
```
```
In lib/syscall.c (ffffffff8153baad)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
```
```
In drivers/tty/vt/vt.c (ffffffff81643f38)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:con_install
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81647c89)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_get_by_index
```
```
In drivers/char/hw_random/core.c (ffffffff8166859a)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
```
```
In drivers/dma-buf/dma-buf.c (ffffffff816f369b)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff816f4fcc)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
```
```
In drivers/dma-buf/dma-resv.c (ffffffff816f5ccf)
Location: arch/x86/include/asm/refcount.h:97
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
In drivers/dma-buf/sw_sync.c (ffffffff816f7afb)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
```
In drivers/scsi/scsi_scan.c (ffffffff817040f1)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/nvme/host/core.c (ffffffff81728c19)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:nvme_alloc_ns
  - drivers/nvme/host/core.c:nvme_find_get_ns
  - drivers/nvme/host/core.c:nvme_init_subsystem
  - drivers/nvme/host/core.c:nvme_ns_head_open
  - drivers/nvme/host/core.c:nvme_open
```
```
In drivers/net/vxlan.c (ffffffff81770d57)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - drivers/net/vxlan.c:__vxlan_sock_add
```
```
In net/core/sock.c (ffffffff8186d738)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
```
```
In net/core/skbuff.c (ffffffff818753ba)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_complete_wifi_ack
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/core/skbuff.c:skb_clone_sk
```
```
In net/core/net_namespace.c (ffffffff8187f775)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/core/net_namespace.c:get_net_ns_by_id
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/neighbour.c (ffffffff8189b4d6)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/filter.c (ffffffff818b8df5)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_charge
```
```
In net/core/fib_rules.c (ffffffff818c5b11)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_lookup
```
```
In net/core/sock_map.c (ffffffff818d3199)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
```
```
In net/core/bpf_sk_storage.c (ffffffff818e36dd)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
```
```
In net/sched/cls_api.c (ffffffff818ed2e1)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_refcnt_get
```
```
In net/ipv4/route.c (ffffffff8190334c)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/inetpeer.c (ffffffff81906f2c)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/inet_hashtables.c (ffffffff8191230f)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81913d77)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/tcp_input.c (ffffffff8191e30b)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/udp.c (ffffffff8194391b)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp4_lib_lookup
```
```
In net/ipv4/fib_semantics.c (ffffffff81959375)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/inet_fragment.c (ffffffff81960247)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff8196534e)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
```
```
In net/ipv4/tcp_bpf.c (ffffffff81974a5c)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81976068)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_getdef
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197ea0f)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_lookup
```
```
In net/xfrm/xfrm_state.c (ffffffff819864f2)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup
```
```
In net/ipv6/addrconf.c (ffffffff81999853)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
```
```
In net/ipv6/route.c (ffffffff819aee28)
Location: arch/x86/include/asm/refcount.h:97
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
In net/ipv6/udp.c (ffffffff819bc434)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp6_lib_lookup
```
```
In net/ipv6/raw.c (ffffffff819c058d)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/calipso.c (ffffffff819df386)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_sock_delattr
  - net/ipv6/calipso.c:calipso_sock_setattr
  - net/ipv6/calipso.c:calipso_sock_getattr
  - net/ipv6/calipso.c:calipso_opt_update
  - net/ipv6/calipso.c:calipso_doi_getdef
```
```
In net/ipv6/inet6_hashtables.c (ffffffff819e547a)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In lib/klist.c (ffffffff81a0c0d7)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
```
```
In lib/kobject.c (ffffffff81a0c944)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - lib/kobject.c:kset_find_obj
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
In arch/x86/kernel/process.c (ffffffff8103dea2)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:get_wchan
```
```
In kernel/sched/core.c (ffffffff810cc918)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
```
```
In kernel/sched/fair.c (ffffffff810df63f)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_fault
```
```
In kernel/stacktrace.c (ffffffff81128507)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - kernel/stacktrace.c:stack_trace_save_tsk_reliable
  - kernel/stacktrace.c:stack_trace_save_tsk
```
```
In kernel/futex.c (ffffffff8114257f)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:get_pi_state
```
```
In kernel/bpf/btf.c (ffffffff811f50e9)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_fd_by_id
```
```
In kernel/events/core.c (ffffffff81209d1d)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:ring_buffer_get
  - kernel/events/core.c:perf_lock_task_context
```
```
In kernel/events/ring_buffer.c (ffffffff8120e6af)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_begin
```
```
In mm/zswap.c (ffffffff81285a7b)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_release
```
```
In mm/memcontrol.c (ffffffff812b5aba)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_id_get_online
```
```
In fs/notify/mark.c (ffffffff81323ab0)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_prepare_user_wait
```
```
In fs/crypto/keyring.c (ffffffff8134275b)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - fs/crypto/keyring.c:add_master_key
```
```
In fs/posix_acl.c (ffffffff81356308)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - fs/posix_acl.c:get_cached_acl
```
```
In fs/proc/array.c (ffffffff8136fa60)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In fs/proc/proc_net.c (ffffffff81375b4b)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:seq_open_net
```
```
In fs/configfs/item.c (ffffffff813825a5)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_get_unless_zero
```
```
In fs/debugfs/file.c (ffffffff8142686c)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In ipc/util.c (ffffffff8142b7cd)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - ipc/util.c:ipc_rcu_getref
```
```
In security/keys/key.c (ffffffff8143a4d9)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - security/keys/key.c:key_lookup
```
```
In security/keys/keyring.c (ffffffff8143bf02)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/apparmor/apparmorfs.c (ffffffff81489c08)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:seq_ns_name_show
  - security/apparmor/apparmorfs.c:seq_ns_level_show
  - security/apparmor/apparmorfs.c:seq_ns_nsstacked_show
  - security/apparmor/apparmorfs.c:seq_ns_stacked_show
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_attach_show
  - security/apparmor/apparmorfs.c:seq_profile_mode_show
  - security/apparmor/apparmorfs.c:seq_profile_name_show
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
```
```
In security/apparmor/task.c (ffffffff8148d5a3)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_get_task_label
```
```
In security/apparmor/domain.c (ffffffff81493f74)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:apparmor_bprm_set_creds
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
In security/apparmor/policy.c (ffffffff81495bf1)
Location: arch/x86/include/asm/refcount.h:97
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
In security/apparmor/procattr.c (ffffffff81498b0e)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff8149ac09)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_sock_graft
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_create
  - security/apparmor/lsm.c:apparmor_unix_may_send
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_task_setrlimit
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_sb_umount
  - security/apparmor/lsm.c:apparmor_sb_mount
  - security/apparmor/lsm.c:common_file_perm
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:common_perm
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/lsm.c:apparmor_cred_transfer
  - security/apparmor/lsm.c:apparmor_cred_prepare
```
```
In security/apparmor/resource.c (ffffffff8149cac7)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff8149e08e)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
```
```
In security/apparmor/label.c (ffffffff8149fe98)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:__vec_find
  - security/apparmor/label.c:__label_insert
```
```
In security/apparmor/mount.c (ffffffff814a2fc4)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
```
```
In security/apparmor/net.c (ffffffff814a45fe)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sk_perm
```
```
In security/apparmor/af_unix.c (ffffffff814a5d7f)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_sock_perm
```
```
In block/blk-mq.c (ffffffff814e446c)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
```
```
In block/bsg-lib.c (ffffffff814fc62d)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_job_get
```
```
In lib/syscall.c (ffffffff8154750d)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
```
```
In drivers/tty/vt/vt.c (ffffffff81691f98)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:con_install
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81695ce9)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_get_by_index
```
```
In drivers/char/hw_random/core.c (ffffffff816b8e0a)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81759001)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff8175a93c)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
```
```
In drivers/dma-buf/dma-resv.c (ffffffff8175b63f)
Location: arch/x86/include/asm/refcount.h:97
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
In drivers/dma-buf/sw_sync.c (ffffffff8175d481)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
```
In drivers/scsi/scsi_scan.c (ffffffff81769aa1)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/edac/ghes_edac.c (ffffffff818b2322)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - drivers/edac/ghes_edac.c:ghes_edac_register
```
```
In net/core/sock.c (ffffffff819047e8)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
```
```
In net/core/skbuff.c (ffffffff8190c47a)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_complete_wifi_ack
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/core/skbuff.c:skb_clone_sk
```
```
In net/core/net_namespace.c (ffffffff81916835)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/core/net_namespace.c:get_net_ns_by_id
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/neighbour.c (ffffffff819326c6)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/filter.c (ffffffff8194fff5)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_charge
```
```
In net/core/fib_rules.c (ffffffff8195cd81)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_lookup
```
```
In net/core/sock_map.c (ffffffff8196a579)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
```
```
In net/core/bpf_sk_storage.c (ffffffff8197aabd)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
```
```
In net/sched/cls_api.c (ffffffff81984971)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_refcnt_get
```
```
In net/netfilter/nfnetlink_log.c (ffffffff8199b365)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/netfilter/nfnetlink_log.c:instance_lookup_get
```
```
In net/netfilter/nf_conntrack_expect.c (ffffffff819a2cbd)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_expect.c:nf_ct_expect_find_get
```
```
In net/netfilter/nf_conntrack_helper.c (ffffffff819a3357)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_helper.c:nf_conntrack_helper_try_module_get
```
```
In net/netfilter/nf_conntrack_netlink.c (ffffffff819b0031)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_exp_ct_dump_table
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_exp_dump_table
```
```
In net/ipv4/route.c (ffffffff819b402c)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/inetpeer.c (ffffffff819b7c0c)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/inet_hashtables.c (ffffffff819c2fef)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff819c4a57)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/tcp_input.c (ffffffff819cefeb)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/udp.c (ffffffff819f462b)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp4_lib_lookup
```
```
In net/ipv4/fib_semantics.c (ffffffff81a0a155)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/inet_fragment.c (ffffffff81a11027)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81a1612e)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
```
```
In net/ipv4/tcp_bpf.c (ffffffff81a226ec)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81a23cf8)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_getdef
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a2c69f)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_lookup
```
```
In net/xfrm/xfrm_state.c (ffffffff81a34182)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup
```
```
In net/ipv6/addrconf.c (ffffffff81a47513)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
```
```
In net/ipv6/route.c (ffffffff81a5cae8)
Location: arch/x86/include/asm/refcount.h:97
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
In net/ipv6/udp.c (ffffffff81a6a0f4)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp6_lib_lookup
```
```
In net/ipv6/raw.c (ffffffff81a6e24d)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/calipso.c (ffffffff81a8d046)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_sock_delattr
  - net/ipv6/calipso.c:calipso_sock_setattr
  - net/ipv6/calipso.c:calipso_sock_getattr
  - net/ipv6/calipso.c:calipso_opt_update
  - net/ipv6/calipso.c:calipso_doi_getdef
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a9426a)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In lib/klist.c (ffffffff81abb3c7)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
```
```
In lib/kobject.c (ffffffff81abbc34)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - lib/kobject.c:kset_find_obj
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
In arch/x86/kernel/process.c (ffffffff8103f002)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:get_wchan
```
```
In kernel/sched/core.c (ffffffff810d52aa)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
```
```
In kernel/sched/fair.c (ffffffff810eb1e7)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_fault
```
```
In kernel/stacktrace.c (ffffffff81134b97)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - kernel/stacktrace.c:stack_trace_save_tsk_reliable
  - kernel/stacktrace.c:stack_trace_save_tsk
```
```
In kernel/futex.c (ffffffff8114e5f7)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:get_pi_state
```
```
In kernel/bpf/btf.c (ffffffff81203612)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_fd_by_id
```
```
In kernel/events/core.c (ffffffff81218aea)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:ring_buffer_get
  - kernel/events/core.c:perf_lock_task_context
```
```
In kernel/events/ring_buffer.c (ffffffff8121d5bf)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_begin
```
```
In mm/zswap.c (ffffffff812957b4)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:__zswap_pool_release
```
```
In mm/memcontrol.c (ffffffff812c5fda)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_id_get_online
```
```
In fs/notify/mark.c (ffffffff813357f0)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_prepare_user_wait
```
```
In fs/crypto/keyring.c (ffffffff81355a5b)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - fs/crypto/keyring.c:add_master_key
```
```
In fs/posix_acl.c (ffffffff81369a13)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - fs/posix_acl.c:get_cached_acl
```
```
In fs/proc/array.c (ffffffff813833f0)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In fs/proc/proc_net.c (ffffffff813895fb)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:seq_open_net
```
```
In fs/configfs/item.c (ffffffff813960c5)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_get_unless_zero
```
```
In fs/debugfs/file.c (ffffffff8143d72c)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In ipc/util.c (ffffffff814427dd)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - ipc/util.c:ipc_rcu_getref
```
```
In security/keys/key.c (ffffffff8145160b)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - security/keys/key.c:key_lookup
```
```
In security/keys/keyring.c (ffffffff81453082)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - security/keys/keyring.c:find_keyring_by_name
```
```
In security/apparmor/apparmorfs.c (ffffffff814a1892)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:seq_ns_name_show
  - security/apparmor/apparmorfs.c:seq_ns_level_show
  - security/apparmor/apparmorfs.c:seq_ns_nsstacked_show
  - security/apparmor/apparmorfs.c:seq_ns_stacked_show
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_attach_show
  - security/apparmor/apparmorfs.c:seq_profile_mode_show
  - security/apparmor/apparmorfs.c:seq_profile_name_show
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
```
```
In security/apparmor/task.c (ffffffff814a550e)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_get_task_label
```
```
In security/apparmor/domain.c (ffffffff814abf9b)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:apparmor_bprm_set_creds
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
In security/apparmor/policy.c (ffffffff814adc81)
Location: arch/x86/include/asm/refcount.h:97
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
In security/apparmor/procattr.c (ffffffff814b0c76)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff814b3462)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_sock_graft
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_create
  - security/apparmor/lsm.c:apparmor_unix_may_send
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_task_setrlimit
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_sb_umount
  - security/apparmor/lsm.c:apparmor_sb_mount
  - security/apparmor/lsm.c:common_file_perm
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:common_perm
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/lsm.c:apparmor_cred_transfer
  - security/apparmor/lsm.c:apparmor_cred_prepare
```
```
In security/apparmor/resource.c (ffffffff814b5196)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff814b67a5)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
```
```
In security/apparmor/label.c (ffffffff814b8561)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:__vec_find
  - security/apparmor/label.c:__label_insert
```
```
In security/apparmor/mount.c (ffffffff814bb89f)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
```
```
In security/apparmor/net.c (ffffffff814bce90)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sk_perm
```
```
In security/apparmor/af_unix.c (ffffffff814be61e)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_sock_perm
```
```
In block/blk-mq.c (ffffffff814fd9ec)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
```
```
In block/bsg-lib.c (ffffffff815156dd)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_job_get
```
```
In lib/syscall.c (ffffffff8156135d)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
```
```
In drivers/tty/vt/vt.c (ffffffff816ac588)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:con_install
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff816b02b9)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_get_by_index
```
```
In drivers/char/hw_random/core.c (ffffffff816d33da)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
```
```
In drivers/dma-buf/dma-buf.c (ffffffff817745d2)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff81775f01)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
```
```
In drivers/dma-buf/dma-resv.c (ffffffff817768f9)
Location: arch/x86/include/asm/refcount.h:97
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
In drivers/dma-buf/sw_sync.c (ffffffff81778b14)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
```
In drivers/scsi/scsi_scan.c (ffffffff817851f1)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/edac/ghes_edac.c (ffffffff818ce5d2)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - drivers/edac/ghes_edac.c:ghes_edac_register
```
```
In net/core/sock.c (ffffffff81925888)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
```
```
In net/core/skbuff.c (ffffffff8192d5aa)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_complete_wifi_ack
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/core/skbuff.c:skb_clone_sk
```
```
In net/core/net_namespace.c (ffffffff81937a47)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/core/net_namespace.c:get_net_ns_by_id
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/neighbour.c (ffffffff81953d86)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/filter.c (ffffffff819719c5)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_charge
```
```
In net/core/fib_rules.c (ffffffff8197efd5)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_lookup
```
```
In net/core/sock_map.c (ffffffff8198c9ad)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
```
```
In net/core/bpf_sk_storage.c (ffffffff8199cfed)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
```
```
In net/sched/cls_api.c (ffffffff819a714c)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_refcnt_get
```
```
In net/ipv4/route.c (ffffffff819bd71c)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/inetpeer.c (ffffffff819c147c)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:lookup
```
```
In net/ipv4/inet_hashtables.c (ffffffff819ccabf)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff819ce4e4)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/tcp_input.c (ffffffff819d8b7b)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/udp.c (ffffffff819fe7eb)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:udp4_lib_lookup
```
```
In net/ipv4/fib_semantics.c (ffffffff81a14935)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/inet_fragment.c (ffffffff81a1b988)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81a20b6e)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
```
```
In net/ipv4/tcp_bpf.c (ffffffff81a2dae2)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81a2f117)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_getdef
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a37d77)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_lookup
```
```
In net/xfrm/xfrm_state.c (ffffffff81a3fade)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup
```
```
In net/ipv6/addrconf.c (ffffffff81a532dd)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
```
```
In net/ipv6/route.c (ffffffff81a68ec6)
Location: arch/x86/include/asm/refcount.h:97
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
In net/ipv6/udp.c (ffffffff81a76709)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:udp6_lib_lookup
```
```
In net/ipv6/raw.c (ffffffff81a7a7fd)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/calipso.c (ffffffff81a99d0f)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_sock_delattr
  - net/ipv6/calipso.c:calipso_sock_setattr
  - net/ipv6/calipso.c:calipso_sock_getattr
  - net/ipv6/calipso.c:calipso_opt_update
  - net/ipv6/calipso.c:calipso_doi_getdef
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81aa03ba)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
```
```
In lib/klist.c (ffffffff81ac7837)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
```
```
In lib/kobject.c (ffffffff81ac8072)
Location: arch/x86/include/asm/refcount.h:97
Inline: True
Inline callers:
  - lib/kobject.c:kset_find_obj
```
</details>
</li>
</ul>

## Differences
