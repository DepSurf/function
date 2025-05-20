# Function: <code>call_rcu</code>

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
<summary>In <code>5.0</code>: ✅</summary>

```c
void call_rcu(struct callback_head *head, rcu_callback_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81112380)
Location: kernel/rcu/tree.c:2954
Inline: False
Direct callers:
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:remove_kmmio_fault_pages
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:pwq_unbound_release_workfn
  - kernel/workqueue.c:pwq_unbound_release_workfn
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:queue_rcu_work
  - kernel/pid.c:free_pid
  - kernel/cred.c:__put_cred
  - kernel/sched/core.c:sched_destroy_group
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:sched_put_rd
  - kernel/sched/topology.c:rq_attach_root
  - kernel/irq/irqdesc.c:free_desc
  - kernel/time/posix-timers.c:release_posix_timer
  - kernel/module.c:do_init_module
  - kernel/pid_namespace.c:destroy_pid_namespace
  - kernel/audit.c:audit_receive_msg
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/auditfilter.c:audit_del_rule
  - kernel/audit_watch.c:audit_watch_handle_event
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:kill_rules
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_probe_register_prio
  - kernel/tracepoint.c:release_early_probes
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/bpf/arraymap.c:perf_event_fd_array_put_ptr
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_free
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_free
  - kernel/bpf/devmap.c:dev_map_notification
  - kernel/bpf/devmap.c:dev_map_update_elem
  - kernel/bpf/devmap.c:dev_map_delete_elem
  - kernel/events/core.c:_free_event
  - kernel/events/callchain.c:put_callchain_buffers
  - mm/shmem.c:shmem_destroy_inode
  - mm/slab_common.c:slab_deactivate_memcg_cache_rcu_sched
  - mm/slab_common.c:memcg_update_all_caches
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/mmu_gather.c:tlb_table_flush
  - mm/slub.c:discard_slab
  - mm/memcontrol.c:memcg_expand_shrinker_maps
  - fs/file_table.c:__fput
  - fs/fcntl.c:fasync_remove_entry
  - fs/dcache.c:dentry_free
  - fs/dcache.c:dentry_free
  - fs/namespace.c:cleanup_mnt
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/block_dev.c:bdev_destroy_inode
  - fs/eventpoll.c:ep_remove
  - fs/proc/inode.c:proc_destroy_inode
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/super.c:ext4_destroy_inode
  - fs/squashfs/super.c:squashfs_destroy_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_destroy_inode
  - fs/fat/inode.c:fat_destroy_inode
  - fs/fat/inode.c:fat_put_super
  - fs/ecryptfs/dentry.c:ecryptfs_d_release
  - fs/fuse/inode.c:fuse_destroy_inode
  - ipc/util.c:ipc_rcu_putref
  - ipc/shm.c:newseg
  - ipc/mqueue.c:mqueue_destroy_inode
  - security/keys/user_defined.c:user_revoke
  - security/keys/user_defined.c:user_update
  - security/keys/trusted.c:trusted_update
  - security/keys/encrypted-keys/encrypted.c:encrypted_update
  - security/security.c:security_inode_free
  - security/selinux/avc.c:avc_node_replace
  - security/selinux/avc.c:avc_node_delete
  - security/apparmor/label.c:aa_label_kref
  - block/blk-sysfs.c:__blk_release_queue
  - block/blk-ioc.c:ioc_destroy_icq
  - block/blk-stat.c:blk_stat_free_callback
  - block/blk-cgroup.c:blkg_release
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/rhashtable.c:rht_deferred_worker
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/dax/super.c:dax_destroy_inode
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
  - drivers/net/tun.c:__tun_set_ebpf
  - drivers/md/dm-stats.c:dm_stats_message
  - net/core/sock.c:sk_destruct
  - net/core/dst.c:dst_release
  - net/core/neighbour.c:neigh_table_clear
  - net/core/neighbour.c:___neigh_create
  - net/core/filter.c:sk_filter_release
  - net/core/sock_reuseport.c:reuseport_detach_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
  - net/core/net-sysfs.c:rx_queue_release
  - net/core/net-sysfs.c:store_rps_dev_flow_table_cnt
  - net/core/page_pool.c:page_pool_destroy
  - net/core/skmsg.c:sk_psock_drop
  - net/core/netpoll.c:__netpoll_cleanup
  - net/sched/sch_generic.c:mini_qdisc_pair_swap
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_cleanup
  - net/netlink/af_netlink.c:netlink_release
  - net/ipv4/inetpeer.c:inet_putpeer
  - net/ipv4/ip_sockglue.c:ip_ra_control
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_reset_cipher
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_ctx_destroy
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_destroy_cipher
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/fib_semantics.c:free_fib_info
  - net/ipv4/fib_trie.c:fib_free_table
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_flush_external
  - net/ipv4/fib_trie.c:fib_table_flush_external
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_table_delete
  - net/ipv4/fib_trie.c:fib_table_delete
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_insert_alias
  - net/ipv4/fib_trie.c:resize
  - net/ipv4/fib_trie.c:tnode_free
  - net/ipv4/inet_fragment.c:inet_frag_destroy
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_putdef
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:aca_put
  - net/ipv6/anycast.c:aca_free_rcu
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:cleanup_prefix_route
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_del_rt
  - net/ipv6/route.c:ip6_route_add
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/route.c:ip6_dst_destroy
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/calipso.c:calipso_doi_remove
  - net/ipv6/addrconf_core.c:in6_dev_finish_destroy
  - net/8021q/vlan_core.c:vlan_vid_del
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_netdev_handler
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - lib/radix-tree.c:idr_destroy
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_free_nodes
```
**Symbols:**

```
ffffffff81112380-ffffffff81112392: call_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void call_rcu(struct callback_head *head, rcu_callback_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8111bc50)
Location: kernel/rcu/tree.c:2590
Inline: False
Direct callers:
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:remove_kmmio_fault_pages
  - kernel/fork.c:copy_process
  - kernel/exit.c:release_task
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:pwq_unbound_release_workfn
  - kernel/workqueue.c:pwq_unbound_release_workfn
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:queue_rcu_work
  - kernel/pid.c:free_pid
  - kernel/cred.c:__put_cred
  - kernel/sched/core.c:sched_destroy_group
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:sched_put_rd
  - kernel/sched/topology.c:rq_attach_root
  - kernel/irq/irqdesc.c:free_desc
  - kernel/rcu/sync.c:rcu_sync_exit
  - kernel/rcu/sync.c:rcu_sync_func
  - kernel/time/posix-timers.c:release_posix_timer
  - kernel/pid_namespace.c:destroy_pid_namespace
  - kernel/audit.c:audit_receive_msg
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/auditfilter.c:audit_del_rule
  - kernel/audit_watch.c:audit_watch_handle_event
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:kill_rules
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_probe_register_prio
  - kernel/tracepoint.c:release_early_probes
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/bpf/arraymap.c:perf_event_fd_array_put_ptr
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_free
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_free
  - kernel/bpf/devmap.c:dev_map_notification
  - kernel/bpf/devmap.c:dev_map_update_elem
  - kernel/bpf/devmap.c:dev_map_delete_elem
  - kernel/events/core.c:_free_event
  - kernel/events/callchain.c:put_callchain_buffers
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:memcg_update_all_caches
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/mmu_gather.c:tlb_table_flush
  - mm/slub.c:discard_slab
  - mm/memcontrol.c:memcg_expand_shrinker_maps
  - fs/file_table.c:__fput
  - fs/fcntl.c:fasync_remove_entry
  - fs/dcache.c:dentry_free
  - fs/dcache.c:dentry_free
  - fs/file.c:expand_files
  - fs/namespace.c:cleanup_mnt
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/eventpoll.c:ep_remove
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/fat/inode.c:fat_put_super
  - fs/ecryptfs/dentry.c:ecryptfs_d_release
  - ipc/util.c:ipc_rcu_putref
  - ipc/shm.c:newseg
  - security/keys/request_key_auth.c:request_key_auth_destroy
  - security/keys/request_key_auth.c:request_key_auth_revoke
  - security/keys/user_defined.c:user_revoke
  - security/keys/user_defined.c:user_update
  - security/keys/trusted.c:trusted_update
  - security/keys/encrypted-keys/encrypted.c:encrypted_update
  - security/security.c:security_inode_free
  - security/selinux/avc.c:avc_node_replace
  - security/selinux/avc.c:avc_node_delete
  - security/apparmor/label.c:aa_label_kref
  - security/safesetid/securityfs.c:safesetid_file_write
  - block/blk-sysfs.c:__blk_release_queue
  - block/blk-ioc.c:ioc_destroy_icq
  - block/blk-stat.c:blk_stat_free_callback
  - block/blk-cgroup.c:blkg_release
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/assoc_array.c:assoc_array_apply_edit
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
  - drivers/net/tun.c:__tun_set_ebpf
  - drivers/md/dm-stats.c:dm_stats_message
  - net/core/sock.c:sk_destruct
  - net/core/dst.c:dst_release
  - net/core/neighbour.c:neigh_table_clear
  - net/core/neighbour.c:___neigh_create
  - net/core/sock_reuseport.c:reuseport_detach_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/xdp.c:__mem_id_disconnect
  - net/core/net-sysfs.c:rx_queue_release
  - net/core/net-sysfs.c:store_rps_dev_flow_table_cnt
  - net/core/skmsg.c:sk_psock_drop
  - net/core/netpoll.c:__netpoll_cleanup
  - net/sched/sch_generic.c:mini_qdisc_pair_swap
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_cleanup
  - net/netlink/af_netlink.c:netlink_release
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/ip_sockglue.c:ip_ra_control
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_reset_cipher
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_ctx_destroy
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_destroy_cipher
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/fib_semantics.c:free_fib_info
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/ipv4/fib_trie.c:fib_free_table
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_flush_external
  - net/ipv4/fib_trie.c:fib_table_flush_external
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_table_delete
  - net/ipv4/fib_trie.c:fib_table_delete
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_insert_alias
  - net/ipv4/fib_trie.c:resize
  - net/ipv4/fib_trie.c:tnode_free
  - net/ipv4/inet_fragment.c:inet_frag_destroy
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:remove_nexthop
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_putdef
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:aca_free_rcu
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:cleanup_prefix_route
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_del_rt
  - net/ipv6/route.c:ip6_route_add
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/route.c:ip6_dst_destroy
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_info_destroy_rcu
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ip6_flowlabel.c:fl_free
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/calipso.c:calipso_doi_remove
  - net/ipv6/addrconf_core.c:in6_dev_finish_destroy
  - net/8021q/vlan_core.c:vlan_vid_del
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_netdev_handler
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - lib/radix-tree.c:idr_destroy
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_free_nodes
```
**Symbols:**

```
ffffffff8111bc50-ffffffff8111bc62: call_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void call_rcu(struct callback_head *head, rcu_callback_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811283a0)
Location: kernel/rcu/tree.c:2650
Inline: False
Direct callers:
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:remove_kmmio_fault_pages
  - kernel/fork.c:copy_process
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:pwq_unbound_release_workfn
  - kernel/workqueue.c:pwq_unbound_release_workfn
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:queue_rcu_work
  - kernel/pid.c:free_pid
  - kernel/sched/core.c:sched_destroy_group
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:sched_put_rd
  - kernel/sched/topology.c:rq_attach_root
  - kernel/irq/irqdesc.c:free_desc
  - kernel/rcu/sync.c:rcu_sync_exit
  - kernel/rcu/sync.c:rcu_sync_func
  - kernel/time/posix-timers.c:release_posix_timer
  - kernel/pid_namespace.c:destroy_pid_namespace
  - kernel/audit.c:audit_receive_msg
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/auditfilter.c:audit_del_rule
  - kernel/audit_watch.c:audit_watch_handle_event
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:kill_rules
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_probe_register_prio
  - kernel/tracepoint.c:release_early_probes
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/bpf/arraymap.c:perf_event_fd_array_put_ptr
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_free
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_free
  - kernel/bpf/devmap.c:dev_map_notification
  - kernel/bpf/devmap.c:dev_map_notification
  - kernel/bpf/devmap.c:dev_map_hash_update_elem
  - kernel/bpf/devmap.c:dev_map_hash_update_elem
  - kernel/bpf/devmap.c:dev_map_update_elem
  - kernel/bpf/devmap.c:dev_map_hash_delete_elem
  - kernel/bpf/devmap.c:dev_map_delete_elem
  - kernel/events/core.c:_free_event
  - kernel/events/callchain.c:put_callchain_buffers
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:memcg_update_all_caches
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/mmu_gather.c:tlb_table_flush
  - mm/slub.c:discard_slab
  - mm/memcontrol.c:memcg_expand_shrinker_maps
  - fs/file_table.c:__fput
  - fs/fcntl.c:fasync_remove_entry
  - fs/dcache.c:dentry_free
  - fs/file.c:expand_files
  - fs/namespace.c:cleanup_mnt
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/eventpoll.c:ep_remove
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/resize.c:ext4_kvfree_array_rcu
  - fs/fat/inode.c:fat_put_super
  - fs/ecryptfs/dentry.c:ecryptfs_d_release
  - ipc/util.c:ipc_rcu_putref
  - ipc/shm.c:newseg
  - security/keys/request_key_auth.c:request_key_auth_destroy
  - security/keys/request_key_auth.c:request_key_auth_revoke
  - security/keys/user_defined.c:user_revoke
  - security/keys/user_defined.c:user_update
  - security/keys/trusted.c:trusted_update
  - security/keys/encrypted-keys/encrypted.c:encrypted_update
  - security/security.c:security_inode_free
  - security/selinux/avc.c:avc_node_replace
  - security/selinux/avc.c:avc_node_delete
  - security/apparmor/label.c:aa_label_kref
  - security/safesetid/securityfs.c:safesetid_file_write
  - block/blk-sysfs.c:__blk_release_queue
  - block/blk-ioc.c:ioc_destroy_icq
  - block/blk-stat.c:blk_stat_free_callback
  - block/blk-cgroup.c:blkg_release
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/assoc_array.c:assoc_array_apply_edit
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
  - drivers/net/tun.c:__tun_set_ebpf
  - drivers/md/dm-stats.c:dm_stats_message
  - net/core/sock.c:sk_destruct
  - net/core/dst.c:dst_release
  - net/core/neighbour.c:neigh_table_clear
  - net/core/neighbour.c:___neigh_create
  - net/core/sock_reuseport.c:reuseport_detach_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
  - net/core/net-sysfs.c:rx_queue_release
  - net/core/net-sysfs.c:store_rps_dev_flow_table_cnt
  - net/core/skmsg.c:sk_psock_drop
  - net/core/netpoll.c:__netpoll_cleanup
  - net/sched/sch_generic.c:mini_qdisc_pair_swap
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_cleanup
  - net/netlink/af_netlink.c:netlink_release
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/ip_sockglue.c:ip_ra_control
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_reset_cipher
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_ctx_destroy
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_destroy_cipher
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/fib_semantics.c:free_fib_info
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/ipv4/fib_trie.c:fib_free_table
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_flush_external
  - net/ipv4/fib_trie.c:fib_table_flush_external
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_table_delete
  - net/ipv4/fib_trie.c:fib_table_delete
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_insert_alias
  - net/ipv4/fib_trie.c:resize
  - net/ipv4/fib_trie.c:tnode_free
  - net/ipv4/inet_fragment.c:inet_frag_destroy
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:remove_nexthop
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_putdef
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:aca_free_rcu
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:cleanup_prefix_route
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_del_rt
  - net/ipv6/route.c:ip6_route_add
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/route.c:ip6_dst_destroy
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_info_destroy_rcu
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ip6_flowlabel.c:fl_free
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/calipso.c:calipso_doi_remove
  - net/ipv6/addrconf_core.c:in6_dev_finish_destroy
  - net/8021q/vlan_core.c:vlan_vid_del
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_netdev_handler
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - lib/radix-tree.c:idr_destroy
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_free_nodes
```
**Symbols:**

```
ffffffff811283a0-ffffffff811283b2: call_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void call_rcu(struct callback_head *head, rcu_callback_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81136c20)
Location: kernel/rcu/tree.c:2950
Inline: False
Direct callers:
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:remove_kmmio_fault_pages
  - kernel/fork.c:copy_process
  - kernel/exit.c:put_task_struct_rcu_user
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:pwq_unbound_release_workfn
  - kernel/workqueue.c:pwq_unbound_release_workfn
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:queue_rcu_work
  - kernel/pid.c:free_pid
  - kernel/cred.c:__put_cred
  - kernel/sched/core.c:sched_destroy_group
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:sched_put_rd
  - kernel/sched/topology.c:rq_attach_root
  - kernel/sched/topology.c:build_perf_domains
  - kernel/sched/topology.c:build_perf_domains
  - kernel/irq/irqdesc.c:free_desc
  - kernel/rcu/sync.c:rcu_sync_exit
  - kernel/rcu/sync.c:rcu_sync_func
  - kernel/time/posix-timers.c:release_posix_timer
  - kernel/pid_namespace.c:put_pid_ns
  - kernel/audit.c:audit_receive_msg
  - kernel/auditfilter.c:update_lsm_rules
  - kernel/auditfilter.c:audit_del_rule
  - kernel/audit_watch.c:audit_remove_parent_watches
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_tree.c:audit_tree_freeing_mark
  - kernel/audit_tree.c:kill_rules
  - kernel/audit_tree.c:tag_chunk
  - kernel/audit_tree.c:untag_chunk
  - kernel/audit_tree.c:untag_chunk
  - kernel/tracepoint.c:tracepoint_probe_register_prio
  - kernel/tracepoint.c:tracepoint_remove_func
  - kernel/tracepoint.c:release_early_probes
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/arraymap.c:perf_event_fd_array_put_ptr
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_free
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_free
  - kernel/bpf/devmap.c:dev_map_notification
  - kernel/bpf/devmap.c:dev_map_hash_remove_netdev
  - kernel/bpf/devmap.c:__dev_map_hash_update_elem
  - kernel/bpf/devmap.c:__dev_map_hash_update_elem
  - kernel/bpf/devmap.c:dev_map_update_elem
  - kernel/bpf/devmap.c:dev_map_hash_delete_elem
  - kernel/bpf/devmap.c:dev_map_delete_elem
  - kernel/bpf/cpumap.c:cpu_map_delete_elem
  - kernel/events/core.c:_free_event
  - kernel/events/callchain.c:put_callchain_buffers
  - kernel/watch_queue.c:watch_queue_clear
  - kernel/watch_queue.c:watch_queue_clear
  - kernel/watch_queue.c:remove_watch_from_object
  - kernel/watch_queue.c:remove_watch_from_object
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:memcg_update_all_caches
  - mm/list_lru.c:memcg_update_list_lru_node
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_remove_table
  - mm/slub.c:discard_slab
  - mm/memcontrol.c:memcg_expand_one_shrinker_map
  - fs/file_table.c:__fput
  - fs/fcntl.c:fasync_remove_entry
  - fs/dcache.c:dentry_free
  - fs/dcache.c:dentry_free
  - fs/inode.c:destroy_inode
  - fs/file.c:expand_fdtable
  - fs/namespace.c:cleanup_mnt
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/eventpoll.c:ep_remove
  - fs/ext4/block_validity.c:ext4_release_system_zone
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/resize.c:add_new_gdb_meta_bg
  - fs/ext4/resize.c:add_new_gdb
  - fs/fat/inode.c:fat_put_super
  - fs/ecryptfs/dentry.c:ecryptfs_d_release
  - ipc/util.c:ipc_rcu_putref
  - ipc/shm.c:newseg
  - security/keys/request_key_auth.c:request_key_auth_destroy
  - security/keys/request_key_auth.c:request_key_auth_revoke
  - security/keys/user_defined.c:user_revoke
  - security/keys/user_defined.c:user_update
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_update
  - security/keys/encrypted-keys/encrypted.c:encrypted_update
  - security/security.c:security_inode_free
  - security/selinux/avc.c:avc_flush
  - security/selinux/avc.c:avc_node_replace
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_destroy
  - security/apparmor/label.c:aa_vec_unique
  - security/apparmor/label.c:aa_vec_unique
  - security/apparmor/label.c:aa_proxy_kref
  - security/safesetid/securityfs.c:handle_policy_update
  - block/blk-sysfs.c:__blk_release_queue
  - block/blk-ioc.c:ioc_destroy_icq
  - block/blk-stat.c:blk_stat_free_callback
  - block/blk-cgroup.c:blkg_release
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/rhashtable.c:rht_deferred_worker
  - lib/assoc_array.c:assoc_array_apply_edit
  - lib/radix-tree.c:radix_tree_free_nodes
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_free_nodes
  - lib/xarray.c:xas_shrink
  - lib/xarray.c:xas_shrink
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
  - drivers/net/tun.c:tun_free_netdev
  - drivers/net/tun.c:tun_free_netdev
  - drivers/md/dm-stats.c:dm_stats_delete
  - net/core/sock.c:__sk_free
  - net/core/dst.c:dst_release
  - net/core/neighbour.c:neigh_table_clear
  - net/core/neighbour.c:neigh_hash_grow
  - net/core/filter.c:sk_filter_charge
  - net/core/filter.c:sk_filter_uncharge
  - net/core/sock_reuseport.c:reuseport_detach_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/xdp.c:mem_xa_remove
  - net/core/net-sysfs.c:rx_queue_release
  - net/core/net-sysfs.c:store_rps_dev_flow_table_cnt
  - net/core/skmsg.c:sk_psock_drop
  - net/core/netpoll.c:__netpoll_cleanup
  - net/sched/sch_generic.c:mini_qdisc_pair_swap
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_cleanup
  - net/netlink/af_netlink.c:netlink_release
  - net/netfilter/core.c:nf_hook_entries_delete_raw
  - net/netfilter/core.c:__nf_unregister_net_hook
  - net/netfilter/core.c:__nf_register_net_hook
  - net/ipv4/inetpeer.c:inet_putpeer
  - net/ipv4/inetpeer.c:inet_peer_gc
  - net/ipv4/ip_sockglue.c:ip_ra_control
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_reset_cipher
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_ctx_destroy
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_destroy_cipher
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:rtm_to_ifaddr
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:inetdev_destroy
  - net/ipv4/devinet.c:inetdev_destroy
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/ipv4/fib_trie.c:fib_free_table
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_flush_external
  - net/ipv4/fib_trie.c:fib_table_flush_external
  - net/ipv4/fib_trie.c:fib_trie_free
  - net/ipv4/fib_trie.c:fib_trie_free
  - net/ipv4/fib_trie.c:fib_trie_free
  - net/ipv4/fib_trie.c:fib_trie_free
  - net/ipv4/fib_trie.c:fib_table_delete
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_insert_node
  - net/ipv4/fib_trie.c:resize
  - net/ipv4/fib_trie.c:tnode_free
  - net/ipv4/inet_fragment.c:inet_frag_destroy
  - net/ipv4/nexthop.c:nexthop_net_exit
  - net/ipv4/nexthop.c:nexthop_add
  - net/ipv4/nexthop.c:nexthop_create_group
  - net/ipv4/nexthop.c:replace_nexthop
  - net/ipv4/nexthop.c:remove_nh_grp_entry
  - net/ipv4/nexthop.c:nexthop_free_rcu
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_delete
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_putdef
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove
  - net/xfrm/xfrm_policy.c:xfrm_policy_destroy
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:aca_put
  - net/ipv6/anycast.c:aca_free_rcu
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:fixup_permanent_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:cleanup_prefix_route
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:__ip6_del_rt_siblings
  - net/ipv6/route.c:ip6_del_rt
  - net/ipv6/route.c:ip6_route_add
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_rt_pcpu_alloc
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/route.c:ip6_dst_destroy
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_purge_rt
  - net/ipv6/ip6_fib.c:fib6_info_destroy_rcu
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ip6_fl_gc
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/calipso.c:calipso_doi_remove
  - net/ipv6/addrconf_core.c:in6_dev_finish_destroy
  - net/8021q/vlan_core.c:vlan_vid_del
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_netdev_handler
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_condremove_iface
```
**Symbols:**

```
ffffffff81136c20-ffffffff81136c30: call_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void call_rcu(struct callback_head *head, rcu_callback_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81132280)
Location: kernel/rcu/tree.c:3087
Inline: False
Direct callers:
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:remove_kmmio_fault_pages
  - kernel/fork.c:copy_process
  - kernel/exit.c:put_task_struct_rcu_user
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:pwq_unbound_release_workfn
  - kernel/workqueue.c:pwq_unbound_release_workfn
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:queue_rcu_work
  - kernel/pid.c:free_pid
  - kernel/cred.c:__put_cred
  - kernel/sched/core.c:sched_destroy_group
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:sched_put_rd
  - kernel/sched/topology.c:rq_attach_root
  - kernel/sched/topology.c:build_perf_domains
  - kernel/sched/topology.c:build_perf_domains
  - kernel/irq/irqdesc.c:free_desc
  - kernel/rcu/sync.c:rcu_sync_exit
  - kernel/rcu/sync.c:rcu_sync_func
  - kernel/time/posix-timers.c:release_posix_timer
  - kernel/pid_namespace.c:put_pid_ns
  - kernel/audit.c:auditd_set
  - kernel/auditfilter.c:update_lsm_rules
  - kernel/auditfilter.c:audit_del_rule
  - kernel/audit_watch.c:audit_remove_parent_watches
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_tree.c:audit_tree_freeing_mark
  - kernel/audit_tree.c:kill_rules
  - kernel/audit_tree.c:tag_chunk
  - kernel/audit_tree.c:untag_chunk
  - kernel/audit_tree.c:untag_chunk
  - kernel/kprobes.c:kprobe_flush_task
  - kernel/tracepoint.c:tracepoint_remove_func
  - kernel/tracepoint.c:tracepoint_add_func
  - kernel/tracepoint.c:release_early_probes
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/bpf/arraymap.c:perf_event_fd_array_put_ptr
  - kernel/bpf/local_storage.c:cgroup_storage_map_free
  - kernel/bpf/local_storage.c:cgroup_storage_map_free
  - kernel/bpf/trampoline.c:__bpf_tramp_image_put_rcu_tasks
  - kernel/bpf/trampoline.c:__bpf_tramp_image_release
  - kernel/bpf/devmap.c:dev_map_notification
  - kernel/bpf/devmap.c:dev_map_hash_remove_netdev
  - kernel/bpf/devmap.c:__dev_map_hash_update_elem
  - kernel/bpf/devmap.c:__dev_map_hash_update_elem
  - kernel/bpf/devmap.c:dev_map_update_elem
  - kernel/bpf/devmap.c:dev_map_hash_delete_elem
  - kernel/bpf/devmap.c:dev_map_delete_elem
  - kernel/bpf/cpumap.c:cpu_map_delete_elem
  - kernel/events/core.c:_free_event
  - kernel/events/callchain.c:put_callchain_buffers
  - kernel/watch_queue.c:watch_queue_clear
  - kernel/watch_queue.c:watch_queue_clear
  - kernel/watch_queue.c:remove_watch_from_object
  - kernel/watch_queue.c:remove_watch_from_object
  - mm/list_lru.c:memcg_update_list_lru_node
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_remove_table
  - mm/slub.c:discard_slab
  - mm/memcontrol.c:memcg_expand_one_shrinker_map
  - fs/file_table.c:__fput
  - fs/fcntl.c:fasync_remove_entry
  - fs/dcache.c:dentry_free
  - fs/dcache.c:dentry_free
  - fs/inode.c:destroy_inode
  - fs/file.c:expand_fdtable
  - fs/namespace.c:cleanup_mnt
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/eventpoll.c:ep_remove
  - fs/ext4/block_validity.c:ext4_release_system_zone
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/resize.c:add_new_gdb_meta_bg
  - fs/ext4/resize.c:add_new_gdb
  - fs/fat/inode.c:fat_put_super
  - fs/ecryptfs/dentry.c:ecryptfs_d_release
  - ipc/util.c:ipc_rcu_putref
  - ipc/shm.c:newseg
  - security/keys/request_key_auth.c:request_key_auth_destroy
  - security/keys/request_key_auth.c:request_key_auth_revoke
  - security/keys/user_defined.c:user_revoke
  - security/keys/user_defined.c:user_update
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_update
  - security/keys/encrypted-keys/encrypted.c:encrypted_update
  - security/security.c:security_inode_free
  - security/selinux/avc.c:avc_flush
  - security/selinux/avc.c:avc_node_replace
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_destroy
  - security/apparmor/label.c:aa_vec_unique
  - security/apparmor/label.c:aa_vec_unique
  - security/apparmor/label.c:__aa_proxy_redirect
  - security/apparmor/label.c:aa_proxy_kref
  - security/safesetid/securityfs.c:handle_policy_update
  - block/blk-sysfs.c:blk_release_queue
  - block/blk-ioc.c:ioc_destroy_icq
  - block/blk-stat.c:blk_stat_free_callback
  - block/blk-cgroup.c:blkg_release
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/rhashtable.c:rht_deferred_worker
  - lib/assoc_array.c:assoc_array_apply_edit
  - lib/radix-tree.c:radix_tree_free_nodes
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_free_nodes
  - lib/xarray.c:xas_shrink
  - lib/xarray.c:xas_shrink
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
  - drivers/net/tun.c:tun_free_netdev
  - drivers/net/tun.c:tun_free_netdev
  - drivers/md/dm-stats.c:dm_stats_delete
  - net/core/sock.c:__sk_free
  - net/core/dst.c:dst_release
  - net/core/neighbour.c:neigh_table_clear
  - net/core/neighbour.c:neigh_hash_grow
  - net/core/filter.c:sk_filter_charge
  - net/core/filter.c:sk_filter_uncharge
  - net/core/sock_reuseport.c:reuseport_detach_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/xdp.c:mem_xa_remove
  - net/core/net-sysfs.c:rx_queue_release
  - net/core/net-sysfs.c:store_rps_dev_flow_table_cnt
  - net/core/skmsg.c:sk_psock_drop
  - net/core/netpoll.c:__netpoll_cleanup
  - net/sched/sch_generic.c:mini_qdisc_pair_swap
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_cleanup
  - net/netlink/af_netlink.c:netlink_release
  - net/netfilter/core.c:nf_hook_entries_delete_raw
  - net/netfilter/core.c:__nf_unregister_net_hook
  - net/netfilter/core.c:__nf_register_net_hook
  - net/ipv4/inetpeer.c:inet_putpeer
  - net/ipv4/inetpeer.c:inet_peer_gc
  - net/ipv4/ip_sockglue.c:ip_ra_control
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_reset_cipher
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_ctx_destroy
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_destroy_cipher
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:rtm_to_ifaddr
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:inetdev_destroy
  - net/ipv4/devinet.c:inetdev_destroy
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/ipv4/fib_trie.c:fib_free_table
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_flush_external
  - net/ipv4/fib_trie.c:fib_table_flush_external
  - net/ipv4/fib_trie.c:fib_trie_free
  - net/ipv4/fib_trie.c:fib_trie_free
  - net/ipv4/fib_trie.c:fib_trie_free
  - net/ipv4/fib_trie.c:fib_trie_free
  - net/ipv4/fib_trie.c:fib_table_delete
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_insert_node
  - net/ipv4/fib_trie.c:resize
  - net/ipv4/fib_trie.c:tnode_free
  - net/ipv4/inet_fragment.c:inet_frag_destroy
  - net/ipv4/nexthop.c:nexthop_net_exit
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:nexthop_create_group
  - net/ipv4/nexthop.c:replace_nexthop
  - net/ipv4/nexthop.c:remove_nh_grp_entry
  - net/ipv4/nexthop.c:nexthop_free_rcu
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_delete
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/xfrm/xfrm_policy.c:xfrm_policy_destroy
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:aca_put
  - net/ipv6/anycast.c:aca_free_rcu
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:fixup_permanent_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:cleanup_prefix_route
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_del_rt_siblings
  - net/ipv6/route.c:ip6_del_rt
  - net/ipv6/route.c:ip6_route_add
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_rt_pcpu_alloc
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/route.c:ip6_dst_destroy
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_purge_rt
  - net/ipv6/ip6_fib.c:fib6_info_destroy_rcu
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:ip6_fl_gc
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/addrconf_core.c:in6_dev_finish_destroy
  - net/8021q/vlan_core.c:vlan_vid_del
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_netdev_handler
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_condremove_iface
```
**Symbols:**

```
ffffffff81132280-ffffffff81132290: call_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void call_rcu(struct callback_head *head, rcu_callback_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81132ac0)
Location: kernel/rcu/tree.c:3110
Inline: False
Direct callers:
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:remove_kmmio_fault_pages
  - kernel/fork.c:copy_process
  - kernel/exit.c:put_task_struct_rcu_user
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:pwq_unbound_release_workfn
  - kernel/workqueue.c:pwq_unbound_release_workfn
  - kernel/workqueue.c:pwq_unbound_release_workfn
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:queue_rcu_work
  - kernel/pid.c:free_pid
  - kernel/cred.c:__put_cred
  - kernel/sched/core.c:sched_destroy_group
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:sched_put_rd
  - kernel/sched/topology.c:rq_attach_root
  - kernel/sched/topology.c:build_perf_domains
  - kernel/sched/topology.c:build_perf_domains
  - kernel/irq/irqdesc.c:free_desc
  - kernel/rcu/sync.c:rcu_sync_exit
  - kernel/rcu/sync.c:rcu_sync_func
  - kernel/time/posix-timers.c:release_posix_timer
  - kernel/pid_namespace.c:put_pid_ns
  - kernel/audit.c:audit_receive_msg
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/auditfilter.c:audit_del_rule
  - kernel/audit_watch.c:audit_remove_parent_watches
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_tree.c:audit_tree_freeing_mark
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:kill_rules
  - kernel/audit_tree.c:tag_chunk
  - kernel/kprobes.c:kprobe_flush_task
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_add_func
  - kernel/tracepoint.c:release_early_probes
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/bpf/syscall.c:__bpf_prog_put_noref
  - kernel/bpf/arraymap.c:perf_event_fd_array_put_ptr
  - kernel/bpf/local_storage.c:cgroup_storage_map_free
  - kernel/bpf/local_storage.c:cgroup_storage_map_free
  - kernel/bpf/trampoline.c:__bpf_tramp_image_put_rcu_tasks
  - kernel/bpf/trampoline.c:__bpf_tramp_image_release
  - kernel/bpf/devmap.c:dev_map_notification
  - kernel/bpf/devmap.c:dev_map_notification
  - kernel/bpf/devmap.c:__dev_map_hash_update_elem
  - kernel/bpf/devmap.c:__dev_map_hash_update_elem
  - kernel/bpf/devmap.c:dev_map_update_elem
  - kernel/bpf/devmap.c:dev_map_hash_delete_elem
  - kernel/bpf/devmap.c:dev_map_delete_elem
  - kernel/bpf/cpumap.c:cpu_map_delete_elem
  - kernel/events/core.c:_free_event
  - kernel/events/callchain.c:put_callchain_buffers
  - kernel/watch_queue.c:watch_queue_clear
  - kernel/watch_queue.c:watch_queue_clear
  - kernel/watch_queue.c:remove_watch_from_object
  - kernel/watch_queue.c:remove_watch_from_object
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_remove_table
  - mm/slub.c:discard_slab
  - fs/file_table.c:__fput
  - fs/fcntl.c:fasync_remove_entry
  - fs/dcache.c:dentry_free
  - fs/dcache.c:dentry_free
  - fs/inode.c:destroy_inode
  - fs/file.c:expand_files
  - fs/namespace.c:cleanup_mnt
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/eventpoll.c:ep_remove
  - fs/ext4/block_validity.c:ext4_release_system_zone
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/resize.c:ext4_kvfree_array_rcu
  - fs/fat/inode.c:fat_put_super
  - fs/ecryptfs/dentry.c:ecryptfs_d_release
  - ipc/util.c:ipc_rcu_putref
  - ipc/shm.c:newseg
  - security/keys/request_key_auth.c:request_key_auth_destroy
  - security/keys/request_key_auth.c:request_key_auth_revoke
  - security/keys/user_defined.c:user_revoke
  - security/keys/user_defined.c:user_update
  - security/keys/trusted-keys/trusted_core.c:trusted_update
  - security/keys/encrypted-keys/encrypted.c:encrypted_update
  - security/security.c:security_inode_free
  - security/selinux/avc.c:avc_flush
  - security/selinux/avc.c:avc_node_replace
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_destroy
  - security/apparmor/label.c:aa_vec_unique
  - security/apparmor/label.c:aa_vec_unique
  - security/apparmor/label.c:__aa_proxy_redirect
  - security/apparmor/label.c:aa_proxy_kref
  - security/safesetid/securityfs.c:handle_policy_update
  - block/blk-sysfs.c:blk_release_queue
  - block/blk-ioc.c:ioc_destroy_icq
  - block/blk-stat.c:blk_stat_free_callback
  - block/blk-cgroup.c:blkg_release
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/assoc_array.c:assoc_array_apply_edit
  - lib/radix-tree.c:idr_destroy
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_free_nodes
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
  - drivers/net/tun.c:tun_free_netdev
  - drivers/net/tun.c:tun_free_netdev
  - drivers/md/dm-stats.c:dm_stats_message
  - net/core/sock.c:__sk_free
  - net/core/dst.c:dst_release
  - net/core/neighbour.c:neigh_table_clear
  - net/core/neighbour.c:___neigh_create
  - net/core/filter.c:sk_filter_charge
  - net/core/filter.c:sk_filter_uncharge
  - net/core/sock_reuseport.c:reuseport_detach_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/xdp.c:mem_xa_remove
  - net/core/net-sysfs.c:rx_queue_release
  - net/core/net-sysfs.c:store_rps_dev_flow_table_cnt
  - net/core/netpoll.c:__netpoll_cleanup
  - net/sched/sch_generic.c:mini_qdisc_pair_swap
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_cleanup
  - net/netlink/af_netlink.c:netlink_release
  - net/netfilter/core.c:nf_hook_entries_delete_raw
  - net/netfilter/core.c:__nf_unregister_net_hook
  - net/netfilter/core.c:__nf_register_net_hook
  - net/ipv4/inetpeer.c:inet_putpeer
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/ip_sockglue.c:ip_ra_control
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_reset_cipher
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_ctx_destroy
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_destroy_cipher
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:rtm_to_ifaddr
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/ipv4/fib_trie.c:fib_free_table
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_flush_external
  - net/ipv4/fib_trie.c:fib_table_flush_external
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_table_delete
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_insert_alias
  - net/ipv4/fib_trie.c:resize
  - net/ipv4/fib_trie.c:tnode_free
  - net/ipv4/inet_fragment.c:inet_frag_destroy
  - net/ipv4/nexthop.c:nexthop_net_exit
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:nexthop_create_group
  - net/ipv4/nexthop.c:replace_nexthop
  - net/ipv4/nexthop.c:remove_nh_grp_entry
  - net/ipv4/nexthop.c:nexthop_free_rcu
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_delete
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/xfrm/xfrm_policy.c:xfrm_policy_destroy
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:aca_put
  - net/ipv6/anycast.c:aca_free_rcu
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:cleanup_prefix_route
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_del_rt_siblings
  - net/ipv6/route.c:ip6_route_add
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/route.c:ip6_dst_destroy
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_purge_rt
  - net/ipv6/ip6_fib.c:fib6_info_destroy_rcu
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:ip6_fl_gc
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/addrconf_core.c:in6_dev_finish_destroy
  - net/8021q/vlan_core.c:vlan_vid_del
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_netdev_handler
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
**Symbols:**

```
ffffffff81132ac0-ffffffff81132ad0: call_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void call_rcu(struct callback_head *head, rcu_callback_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81154cf0)
Location: kernel/rcu/tree.c:3066
Inline: False
Direct callers:
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:remove_kmmio_fault_pages
  - kernel/fork.c:copy_process
  - kernel/exit.c:put_task_struct_rcu_user
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:pwq_unbound_release_workfn
  - kernel/workqueue.c:pwq_unbound_release_workfn
  - kernel/workqueue.c:pwq_unbound_release_workfn
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:queue_rcu_work
  - kernel/pid.c:free_pid
  - kernel/cred.c:__put_cred
  - kernel/sched/core.c:cpu_cgroup_css_free
  - kernel/sched/core.c:sched_destroy_group
  - kernel/sched/core.c:sched_unregister_group_rcu
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:sched_put_rd
  - kernel/sched/topology.c:rq_attach_root
  - kernel/sched/topology.c:build_perf_domains
  - kernel/sched/topology.c:build_perf_domains
  - kernel/irq/irqdesc.c:free_desc
  - kernel/rcu/sync.c:rcu_sync_exit
  - kernel/rcu/sync.c:rcu_sync_func
  - kernel/time/posix-timers.c:release_posix_timer
  - kernel/pid_namespace.c:put_pid_ns
  - kernel/audit.c:audit_receive_msg
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/auditfilter.c:audit_del_rule
  - kernel/audit_watch.c:audit_remove_parent_watches
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_tree.c:audit_tree_freeing_mark
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:kill_rules
  - kernel/audit_tree.c:tag_chunk
  - kernel/kprobes.c:kprobe_flush_task
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_add_func
  - kernel/tracepoint.c:release_early_probes
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/bpf/syscall.c:__bpf_prog_put_noref
  - kernel/bpf/arraymap.c:perf_event_fd_array_put_ptr
  - kernel/bpf/local_storage.c:cgroup_storage_map_free
  - kernel/bpf/local_storage.c:cgroup_storage_map_free
  - kernel/bpf/trampoline.c:__bpf_tramp_image_put_rcu_tasks
  - kernel/bpf/trampoline.c:__bpf_tramp_image_release
  - kernel/bpf/devmap.c:dev_map_notification
  - kernel/bpf/devmap.c:dev_map_notification
  - kernel/bpf/devmap.c:__dev_map_hash_update_elem
  - kernel/bpf/devmap.c:__dev_map_hash_update_elem
  - kernel/bpf/devmap.c:dev_map_update_elem
  - kernel/bpf/devmap.c:dev_map_hash_delete_elem
  - kernel/bpf/devmap.c:dev_map_delete_elem
  - kernel/bpf/cpumap.c:cpu_map_delete_elem
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_put
  - kernel/events/core.c:_free_event
  - kernel/events/callchain.c:put_callchain_buffers
  - kernel/watch_queue.c:watch_queue_clear
  - kernel/watch_queue.c:watch_queue_clear
  - kernel/watch_queue.c:remove_watch_from_object
  - kernel/watch_queue.c:remove_watch_from_object
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_remove_table
  - mm/slub.c:discard_slab
  - mm/kfence/core.c:__kfence_free
  - fs/file_table.c:__fput
  - fs/fcntl.c:fasync_remove_entry
  - fs/dcache.c:dentry_free
  - fs/dcache.c:dentry_free
  - fs/inode.c:destroy_inode
  - fs/file.c:expand_files
  - fs/namespace.c:cleanup_mnt
  - fs/eventpoll.c:ep_remove
  - fs/ext4/block_validity.c:ext4_release_system_zone
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/resize.c:ext4_kvfree_array_rcu
  - fs/fat/inode.c:fat_put_super
  - fs/ecryptfs/dentry.c:ecryptfs_d_release
  - ipc/util.c:ipc_rcu_putref
  - ipc/shm.c:newseg
  - security/keys/request_key_auth.c:request_key_auth_destroy
  - security/keys/request_key_auth.c:request_key_auth_revoke
  - security/keys/user_defined.c:user_revoke
  - security/keys/user_defined.c:user_update
  - security/keys/trusted-keys/trusted_core.c:trusted_update
  - security/keys/encrypted-keys/encrypted.c:encrypted_update
  - security/security.c:security_inode_free
  - security/selinux/avc.c:avc_flush
  - security/selinux/avc.c:avc_node_replace
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_destroy
  - security/apparmor/label.c:aa_vec_unique
  - security/apparmor/label.c:aa_vec_unique
  - security/apparmor/label.c:__aa_proxy_redirect
  - security/apparmor/label.c:aa_proxy_kref
  - security/safesetid/securityfs.c:handle_policy_update
  - block/blk-sysfs.c:blk_release_queue
  - block/blk-ioc.c:ioc_destroy_icq
  - block/blk-stat.c:blk_stat_free_callback
  - block/blk-cgroup.c:blkg_release
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/assoc_array.c:assoc_array_apply_edit
  - lib/radix-tree.c:idr_destroy
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_free_nodes
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
  - drivers/net/tun.c:tun_free_netdev
  - drivers/net/tun.c:tun_free_netdev
  - drivers/md/dm-stats.c:dm_stats_message
  - net/core/sock.c:__sk_free
  - net/core/dst.c:dst_release
  - net/core/neighbour.c:neigh_table_clear
  - net/core/neighbour.c:___neigh_create
  - net/core/filter.c:sk_filter_charge
  - net/core/filter.c:sk_filter_uncharge
  - net/core/sock_reuseport.c:reuseport_detach_sock
  - net/core/sock_reuseport.c:reuseport_resurrect
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/xdp.c:mem_xa_remove
  - net/core/net-sysfs.c:rx_queue_release
  - net/core/net-sysfs.c:store_rps_dev_flow_table_cnt
  - net/core/netpoll.c:__netpoll_cleanup
  - net/sched/sch_generic.c:mini_qdisc_pair_swap
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_cleanup
  - net/netlink/af_netlink.c:netlink_release
  - net/netfilter/core.c:nf_hook_entries_delete_raw
  - net/netfilter/core.c:__nf_unregister_net_hook
  - net/netfilter/core.c:__nf_register_net_hook
  - net/netfilter/core.c:nf_hook_entries_insert_raw
  - net/ipv4/inetpeer.c:inet_putpeer
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/ip_sockglue.c:ip_ra_control
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_ctx_destroy
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_destroy_cipher
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_init_key_once
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:rtm_to_ifaddr
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/ipv4/fib_trie.c:fib_free_table
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_flush_external
  - net/ipv4/fib_trie.c:fib_table_flush_external
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_table_delete
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_insert_alias
  - net/ipv4/fib_trie.c:resize
  - net/ipv4/fib_trie.c:tnode_free
  - net/ipv4/inet_fragment.c:inet_frag_destroy
  - net/ipv4/nexthop.c:nexthop_net_exit
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:nexthop_create_group
  - net/ipv4/nexthop.c:replace_nexthop
  - net/ipv4/nexthop.c:remove_nh_grp_entry
  - net/ipv4/nexthop.c:nexthop_free_rcu
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_delete
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/xfrm/xfrm_policy.c:xfrm_policy_destroy
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:aca_put
  - net/ipv6/anycast.c:aca_free_rcu
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:addrconf_permanent_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:cleanup_prefix_route
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_del_rt_siblings
  - net/ipv6/route.c:ip6_route_add
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/route.c:ip6_dst_destroy
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_purge_rt
  - net/ipv6/ip6_fib.c:fib6_info_destroy_rcu
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:ip6_fl_gc
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/addrconf_core.c:in6_dev_finish_destroy
  - net/8021q/vlan_core.c:vlan_vid_del
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_netdev_handler
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
**Symbols:**

```
ffffffff81154cf0-ffffffff81154d00: call_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void call_rcu(struct callback_head *head, rcu_callback_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8117dda0)
Location: kernel/rcu/tree.c:3101
Inline: False
Direct callers:
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:remove_kmmio_fault_pages
  - kernel/fork.c:copy_process
  - kernel/fork.c:put_task_stack
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:pwq_unbound_release_workfn
  - kernel/workqueue.c:pwq_unbound_release_workfn
  - kernel/workqueue.c:pwq_unbound_release_workfn
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:queue_rcu_work
  - kernel/pid.c:free_pid
  - kernel/cred.c:__put_cred
  - kernel/sched/core.c:cpu_cgroup_css_free
  - kernel/sched/core.c:sched_destroy_group
  - kernel/sched/core.c:sched_unregister_group_rcu
  - kernel/sched/build_utility.c:cpu_attach_domain
  - kernel/sched/build_utility.c:sched_put_rd
  - kernel/sched/build_utility.c:rq_attach_root
  - kernel/sched/build_utility.c:build_perf_domains
  - kernel/sched/build_utility.c:build_perf_domains
  - kernel/irq/irqdesc.c:free_desc
  - kernel/rcu/sync.c:rcu_sync_exit
  - kernel/rcu/sync.c:rcu_sync_func
  - kernel/time/posix-timers.c:release_posix_timer
  - kernel/pid_namespace.c:put_pid_ns
  - kernel/audit.c:audit_receive_msg
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/auditfilter.c:audit_del_rule
  - kernel/audit_watch.c:audit_remove_parent_watches
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_tree.c:audit_tree_freeing_mark
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:kill_rules
  - kernel/audit_tree.c:tag_chunk
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_add_func
  - kernel/tracepoint.c:release_early_probes
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/rethook.c:rethook_free
  - kernel/trace/rethook.c:rethook_flush_task
  - kernel/bpf/syscall.c:__bpf_prog_put_noref
  - kernel/bpf/arraymap.c:perf_event_fd_array_put_ptr
  - kernel/bpf/local_storage.c:cgroup_storage_map_free
  - kernel/bpf/local_storage.c:cgroup_storage_map_free
  - kernel/bpf/devmap.c:dev_map_notification
  - kernel/bpf/devmap.c:dev_map_notification
  - kernel/bpf/devmap.c:__dev_map_hash_update_elem
  - kernel/bpf/devmap.c:__dev_map_hash_update_elem
  - kernel/bpf/devmap.c:dev_map_update_elem
  - kernel/bpf/devmap.c:dev_map_hash_delete_elem
  - kernel/bpf/devmap.c:dev_map_delete_elem
  - kernel/bpf/cpumap.c:cpu_map_delete_elem
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_put
  - kernel/events/core.c:_free_event
  - kernel/events/callchain.c:put_callchain_buffers
  - kernel/watch_queue.c:watch_queue_clear
  - kernel/watch_queue.c:watch_queue_clear
  - kernel/watch_queue.c:remove_watch_from_object
  - kernel/watch_queue.c:remove_watch_from_object
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_remove_table
  - mm/slub.c:discard_slab
  - mm/kfence/core.c:__kfence_free
  - fs/file_table.c:__fput
  - fs/fcntl.c:fasync_remove_entry
  - fs/dcache.c:dentry_free
  - fs/dcache.c:dentry_free
  - fs/inode.c:destroy_inode
  - fs/file.c:expand_files
  - fs/namespace.c:cleanup_mnt
  - fs/eventpoll.c:ep_remove
  - fs/ext4/block_validity.c:ext4_release_system_zone
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/fat/inode.c:fat_put_super
  - fs/ecryptfs/dentry.c:ecryptfs_d_release
  - ipc/util.c:ipc_rcu_putref
  - ipc/shm.c:newseg
  - security/keys/request_key_auth.c:request_key_auth_destroy
  - security/keys/request_key_auth.c:request_key_auth_revoke
  - security/keys/user_defined.c:user_revoke
  - security/keys/user_defined.c:user_update
  - security/keys/trusted-keys/trusted_core.c:trusted_update
  - security/keys/encrypted-keys/encrypted.c:encrypted_update
  - security/security.c:security_inode_free
  - security/selinux/avc.c:avc_flush
  - security/selinux/avc.c:avc_node_replace
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_destroy
  - security/apparmor/label.c:aa_vec_unique
  - security/apparmor/label.c:aa_vec_unique
  - security/apparmor/label.c:__aa_proxy_redirect
  - security/apparmor/label.c:aa_proxy_kref
  - security/apparmor/label.c:aa_get_current_ns
  - security/safesetid/securityfs.c:handle_policy_update
  - block/blk-sysfs.c:blk_release_queue
  - block/blk-ioc.c:ioc_destroy_icq
  - block/blk-stat.c:blk_stat_free_callback
  - block/blk-cgroup.c:blkg_release
  - io_uring/io_uring.c:__io_uring_register
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/assoc_array.c:assoc_array_apply_edit
  - lib/radix-tree.c:idr_destroy
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_free_nodes
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
  - drivers/net/tun.c:tun_free_netdev
  - drivers/net/tun.c:tun_free_netdev
  - drivers/md/dm-stats.c:message_stats_delete
  - net/core/sock.c:__sk_free
  - net/core/dst.c:dst_release
  - net/core/neighbour.c:neigh_table_clear
  - net/core/neighbour.c:___neigh_create
  - net/core/filter.c:sk_filter_charge
  - net/core/filter.c:sk_filter_uncharge
  - net/core/sock_reuseport.c:reuseport_detach_sock
  - net/core/sock_reuseport.c:reuseport_resurrect
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/xdp.c:mem_allocator_disconnect
  - net/core/net-sysfs.c:rx_queue_release
  - net/core/net-sysfs.c:store_rps_dev_flow_table_cnt
  - net/core/netpoll.c:__netpoll_cleanup
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_cleanup
  - net/netlink/af_netlink.c:netlink_release
  - net/netfilter/core.c:nf_hook_entries_delete_raw
  - net/netfilter/core.c:__nf_unregister_net_hook
  - net/netfilter/core.c:__nf_register_net_hook
  - net/netfilter/core.c:nf_hook_entries_insert_raw
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/ip_sockglue.c:ip_ra_control
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_ctx_destroy
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_destroy_cipher
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_init_key_once
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/ipv4/fib_trie.c:fib_free_table
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_flush_external
  - net/ipv4/fib_trie.c:fib_table_flush_external
  - net/ipv4/fib_trie.c:fib_table_flush_external
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_table_delete
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_insert_alias
  - net/ipv4/fib_trie.c:resize
  - net/ipv4/inet_fragment.c:inet_frag_destroy
  - net/ipv4/nexthop.c:nexthop_net_exit_batch
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:nexthop_create_group
  - net/ipv4/nexthop.c:replace_nexthop
  - net/ipv4/nexthop.c:remove_nh_grp_entry
  - net/ipv4/nexthop.c:nexthop_free_rcu
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_delete
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/xfrm/xfrm_policy.c:xfrm_policy_destroy
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:aca_free_rcu
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:addrconf_permanent_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:cleanup_prefix_route
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_del_rt_siblings
  - net/ipv6/route.c:ip6_route_add
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/route.c:ip6_dst_destroy
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_purge_rt
  - net/ipv6/ip6_fib.c:fib6_info_destroy_rcu
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:ip6_fl_gc
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/addrconf_core.c:in6_dev_finish_destroy
  - net/8021q/vlan_core.c:vlan_vid_del
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_netdev_handler
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/mctp/neigh.c:mctp_neigh_net_exit
  - net/mctp/neigh.c:mctp_rtm_delneigh
  - net/mctp/neigh.c:mctp_neigh_remove_dev
```
**Symbols:**

```
ffffffff8117dda0-ffffffff8117e04a: call_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void call_rcu(struct callback_head *head, rcu_callback_t func);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811b9150)
Location: kernel/rcu/tree.c:2866
Inline: True
Inline callers:
  - kernel/rcu/tree.c:call_rcu_hurry
Direct callers:
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:remove_kmmio_fault_pages
  - kernel/fork.c:copy_process
  - kernel/fork.c:put_task_stack
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:pwq_unbound_release_workfn
  - kernel/workqueue.c:pwq_unbound_release_workfn
  - kernel/workqueue.c:pwq_unbound_release_workfn
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:queue_rcu_work
  - kernel/pid.c:free_pid
  - kernel/cred.c:__put_cred
  - kernel/sched/core.c:cpu_cgroup_css_free
  - kernel/sched/core.c:sched_destroy_group
  - kernel/sched/core.c:sched_unregister_group_rcu
  - kernel/sched/build_utility.c:cpu_attach_domain
  - kernel/sched/build_utility.c:sched_put_rd
  - kernel/sched/build_utility.c:rq_attach_root
  - kernel/sched/build_utility.c:build_perf_domains
  - kernel/sched/build_utility.c:build_perf_domains
  - kernel/irq/irqdesc.c:free_desc
  - kernel/rcu/sync.c:rcu_sync_exit
  - kernel/rcu/sync.c:rcu_sync_func
  - kernel/time/posix-timers.c:release_posix_timer
  - kernel/pid_namespace.c:put_pid_ns
  - kernel/audit.c:audit_receive_msg
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/auditfilter.c:audit_del_rule
  - kernel/audit_watch.c:audit_remove_parent_watches
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_tree.c:audit_tree_freeing_mark
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:kill_rules
  - kernel/audit_tree.c:tag_chunk
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_add_func
  - kernel/tracepoint.c:release_early_probes
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/rethook.c:rethook_free
  - kernel/trace/rethook.c:rethook_flush_task
  - kernel/bpf/syscall.c:__bpf_prog_put_noref
  - kernel/bpf/arraymap.c:perf_event_fd_array_put_ptr
  - kernel/bpf/local_storage.c:cgroup_storage_map_free
  - kernel/bpf/local_storage.c:cgroup_storage_map_free
  - kernel/bpf/devmap.c:dev_map_notification
  - kernel/bpf/devmap.c:dev_map_notification
  - kernel/bpf/devmap.c:__dev_map_hash_update_elem
  - kernel/bpf/devmap.c:__dev_map_hash_update_elem
  - kernel/bpf/devmap.c:dev_map_update_elem
  - kernel/bpf/devmap.c:dev_map_hash_delete_elem
  - kernel/bpf/devmap.c:dev_map_delete_elem
  - kernel/bpf/cpumap.c:cpu_map_delete_elem
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_put
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:put_pmu_ctx
  - kernel/events/callchain.c:put_callchain_buffers
  - kernel/watch_queue.c:watch_queue_clear
  - kernel/watch_queue.c:watch_queue_clear
  - kernel/watch_queue.c:remove_watch_from_object
  - kernel/watch_queue.c:remove_watch_from_object
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_remove_table
  - mm/slub.c:free_slab
  - mm/kfence/core.c:__kfence_free
  - fs/file_table.c:__fput
  - fs/fcntl.c:fasync_remove_entry
  - fs/dcache.c:dentry_free
  - fs/dcache.c:dentry_free
  - fs/inode.c:destroy_inode
  - fs/file.c:expand_files
  - fs/namespace.c:cleanup_mnt
  - fs/eventpoll.c:ep_remove
  - fs/ext4/block_validity.c:ext4_release_system_zone
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/fat/inode.c:fat_put_super
  - fs/ecryptfs/dentry.c:ecryptfs_d_release
  - ipc/util.c:ipc_rcu_putref
  - ipc/shm.c:newseg
  - security/keys/request_key_auth.c:request_key_auth_destroy
  - security/keys/request_key_auth.c:request_key_auth_revoke
  - security/keys/user_defined.c:user_revoke
  - security/keys/user_defined.c:user_update
  - security/keys/trusted-keys/trusted_core.c:trusted_update
  - security/keys/encrypted-keys/encrypted.c:encrypted_update
  - security/security.c:security_inode_free
  - security/selinux/avc.c:avc_flush
  - security/selinux/avc.c:avc_node_replace
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_destroy
  - security/apparmor/label.c:aa_vec_unique
  - security/apparmor/label.c:aa_vec_unique
  - security/apparmor/label.c:__aa_proxy_redirect
  - security/apparmor/label.c:aa_proxy_kref
  - security/apparmor/label.c:aa_get_current_ns
  - security/safesetid/securityfs.c:handle_policy_update
  - block/blk-core.c:blk_put_queue
  - block/blk-ioc.c:ioc_destroy_icq
  - block/blk-stat.c:blk_stat_free_callback
  - block/blk-cgroup.c:blkg_release
  - io_uring/io_uring.c:io_eventfd_unregister
  - io_uring/io_uring.c:io_eventfd_signal
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/assoc_array.c:assoc_array_apply_edit
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
  - drivers/net/tun.c:tun_free_netdev
  - drivers/net/tun.c:tun_free_netdev
  - drivers/md/dm-stats.c:message_stats_delete
  - net/core/sock.c:sk_destruct
  - net/core/dst.c:dst_release
  - net/core/neighbour.c:neigh_table_clear
  - net/core/neighbour.c:___neigh_create
  - net/core/filter.c:sk_filter_charge
  - net/core/filter.c:sk_filter_uncharge
  - net/core/sock_reuseport.c:reuseport_detach_sock
  - net/core/sock_reuseport.c:reuseport_resurrect
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/xdp.c:mem_allocator_disconnect
  - net/core/net-sysfs.c:rx_queue_release
  - net/core/net-sysfs.c:store_rps_dev_flow_table_cnt
  - net/core/netpoll.c:__netpoll_cleanup
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_cleanup
  - net/netlink/af_netlink.c:netlink_release
  - net/netfilter/core.c:nf_hook_entries_delete_raw
  - net/netfilter/core.c:__nf_unregister_net_hook
  - net/netfilter/core.c:__nf_register_net_hook
  - net/netfilter/core.c:nf_hook_entries_insert_raw
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/ip_sockglue.c:ip_ra_control
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_ctx_destroy
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_destroy_cipher
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_init_key_once
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:inetdev_destroy
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/ipv4/fib_trie.c:fib_free_table
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_flush_external
  - net/ipv4/fib_trie.c:fib_table_flush_external
  - net/ipv4/fib_trie.c:fib_table_flush_external
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_table_delete
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_insert_alias
  - net/ipv4/fib_trie.c:resize
  - net/ipv4/inet_fragment.c:inet_frag_destroy
  - net/ipv4/nexthop.c:nexthop_net_exit_batch
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:nexthop_create_group
  - net/ipv4/nexthop.c:replace_nexthop
  - net/ipv4/nexthop.c:remove_nh_grp_entry
  - net/ipv4/nexthop.c:nexthop_free_rcu
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_delete
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/xfrm/xfrm_policy.c:xfrm_policy_destroy
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:aca_free_rcu
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:addrconf_permanent_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:cleanup_prefix_route
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_del_rt_siblings
  - net/ipv6/route.c:ip6_route_add
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/route.c:ip6_dst_destroy
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_purge_rt
  - net/ipv6/ip6_fib.c:fib6_info_destroy_rcu
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:ip6_fl_gc
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/addrconf_core.c:in6_dev_finish_destroy
  - net/8021q/vlan_core.c:vlan_vid_del
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_netdev_handler
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/mctp/neigh.c:mctp_neigh_net_exit
  - net/mctp/neigh.c:mctp_rtm_delneigh
  - net/mctp/neigh.c:mctp_neigh_remove_dev
  - lib/maple_tree.c:mtree_destroy
  - lib/maple_tree.c:mas_replace
  - lib/radix-tree.c:idr_destroy
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_free_nodes
```
**Symbols:**

```
ffffffff811b9180-ffffffff811b9198: call_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void call_rcu(struct callback_head *head, rcu_callback_t func);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811cb170)
Location: kernel/rcu/tree.c:2761
Inline: True
Inline callers:
  - kernel/rcu/tree.c:call_rcu_hurry
Direct callers:
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:remove_kmmio_fault_pages
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mmap
  - kernel/fork.c:put_task_stack
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:pwq_unbound_release_workfn
  - kernel/workqueue.c:pwq_unbound_release_workfn
  - kernel/workqueue.c:pwq_unbound_release_workfn
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:queue_rcu_work
  - kernel/pid.c:free_pid
  - kernel/cred.c:__put_cred
  - kernel/sched/core.c:cpu_cgroup_css_free
  - kernel/sched/core.c:sched_destroy_group
  - kernel/sched/core.c:sched_unregister_group_rcu
  - kernel/sched/build_utility.c:cpu_attach_domain
  - kernel/sched/build_utility.c:sched_put_rd
  - kernel/sched/build_utility.c:rq_attach_root
  - kernel/sched/build_utility.c:build_perf_domains
  - kernel/sched/build_utility.c:build_perf_domains
  - kernel/irq/irqdesc.c:free_desc
  - kernel/rcu/sync.c:rcu_sync_exit
  - kernel/rcu/sync.c:rcu_sync_func
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/posix-timers.c:posix_timer_unhash_and_free
  - kernel/pid_namespace.c:put_pid_ns
  - kernel/audit.c:audit_receive_msg
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/auditfilter.c:audit_del_rule
  - kernel/audit_watch.c:audit_remove_parent_watches
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_tree.c:audit_tree_freeing_mark
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:kill_rules
  - kernel/audit_tree.c:tag_chunk
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_add_func
  - kernel/tracepoint.c:release_early_probes
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/rethook.c:rethook_free
  - kernel/trace/rethook.c:rethook_flush_task
  - kernel/bpf/syscall.c:__bpf_prog_put_noref
  - kernel/bpf/arraymap.c:perf_event_fd_array_put_ptr
  - kernel/bpf/local_storage.c:cgroup_storage_map_free
  - kernel/bpf/local_storage.c:cgroup_storage_map_free
  - kernel/bpf/devmap.c:dev_map_notification
  - kernel/bpf/devmap.c:dev_map_notification
  - kernel/bpf/devmap.c:__dev_map_hash_update_elem
  - kernel/bpf/devmap.c:__dev_map_hash_update_elem
  - kernel/bpf/devmap.c:__dev_map_update_elem
  - kernel/bpf/devmap.c:dev_map_hash_delete_elem
  - kernel/bpf/devmap.c:dev_map_delete_elem
  - kernel/bpf/cpumap.c:cpu_map_delete_elem
  - kernel/bpf/cpumask.c:bpf_cpumask_release
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:put_pmu_ctx
  - kernel/events/callchain.c:put_callchain_buffers
  - kernel/watch_queue.c:watch_queue_clear
  - kernel/watch_queue.c:watch_queue_clear
  - kernel/watch_queue.c:remove_watch_from_object
  - kernel/watch_queue.c:remove_watch_from_object
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_remove_table
  - mm/slub.c:free_slab
  - mm/kfence/core.c:__kfence_free
  - fs/file_table.c:__fput
  - fs/fcntl.c:fasync_remove_entry
  - fs/dcache.c:dentry_free
  - fs/dcache.c:dentry_free
  - fs/inode.c:destroy_inode
  - fs/file.c:expand_files
  - fs/namespace.c:cleanup_mnt
  - fs/eventpoll.c:__ep_remove
  - fs/ext4/block_validity.c:ext4_release_system_zone
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/fat/inode.c:fat_put_super
  - fs/ecryptfs/dentry.c:ecryptfs_d_release
  - ipc/util.c:ipc_rcu_putref
  - ipc/shm.c:newseg
  - security/keys/request_key_auth.c:request_key_auth_destroy
  - security/keys/request_key_auth.c:request_key_auth_revoke
  - security/keys/user_defined.c:user_revoke
  - security/keys/user_defined.c:user_update
  - security/keys/trusted-keys/trusted_core.c:trusted_update
  - security/keys/encrypted-keys/encrypted.c:encrypted_update
  - security/security.c:security_inode_free
  - security/selinux/avc.c:avc_ss_reset
  - security/selinux/avc.c:avc_node_replace
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_destroy
  - security/apparmor/label.c:aa_vec_unique
  - security/apparmor/label.c:aa_vec_unique
  - security/apparmor/label.c:__aa_proxy_redirect
  - security/apparmor/label.c:aa_proxy_kref
  - security/apparmor/label.c:aa_get_current_ns
  - security/safesetid/securityfs.c:handle_policy_update
  - block/blk-core.c:blk_put_queue
  - block/blk-ioc.c:ioc_destroy_icq
  - block/blk-stat.c:blk_stat_free_callback
  - block/blk-cgroup.c:blkg_release
  - io_uring/io_uring.c:io_eventfd_unregister
  - io_uring/io_uring.c:io_eventfd_signal
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/assoc_array.c:assoc_array_apply_edit
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
  - drivers/net/tun.c:tun_free_netdev
  - drivers/net/tun.c:tun_free_netdev
  - drivers/md/dm-stats.c:message_stats_delete
  - net/core/sock.c:sk_destruct
  - net/core/neighbour.c:neigh_table_clear
  - net/core/neighbour.c:___neigh_create
  - net/core/filter.c:sk_filter_charge
  - net/core/filter.c:sk_filter_uncharge
  - net/core/sock_reuseport.c:reuseport_detach_sock
  - net/core/sock_reuseport.c:reuseport_resurrect
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/xdp.c:mem_allocator_disconnect
  - net/core/net-sysfs.c:rx_queue_release
  - net/core/net-sysfs.c:store_rps_dev_flow_table_cnt
  - net/core/netpoll.c:__netpoll_cleanup
  - net/sched/sch_generic.c:__qdisc_destroy
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_cleanup
  - net/netlink/af_netlink.c:netlink_release
  - net/netfilter/core.c:nf_hook_entries_delete_raw
  - net/netfilter/core.c:__nf_unregister_net_hook
  - net/netfilter/core.c:__nf_register_net_hook
  - net/netfilter/core.c:nf_hook_entries_insert_raw
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/ip_sockglue.c:ip_ra_control
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_ctx_destroy
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_destroy_cipher
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_init_key_once
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:inetdev_destroy
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/ipv4/fib_trie.c:fib_free_table
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_flush_external
  - net/ipv4/fib_trie.c:fib_table_flush_external
  - net/ipv4/fib_trie.c:fib_table_flush_external
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_table_delete
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_insert_alias
  - net/ipv4/fib_trie.c:resize
  - net/ipv4/inet_fragment.c:inet_frag_destroy
  - net/ipv4/nexthop.c:nexthop_net_exit_batch
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:nexthop_create_group
  - net/ipv4/nexthop.c:replace_nexthop
  - net/ipv4/nexthop.c:remove_nh_grp_entry
  - net/ipv4/nexthop.c:nexthop_free_rcu
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_delete
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/xfrm/xfrm_policy.c:xfrm_policy_destroy
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:aca_free_rcu
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:addrconf_permanent_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:cleanup_prefix_route
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_del_rt_siblings
  - net/ipv6/route.c:ip6_route_add
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/route.c:ip6_dst_destroy
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_purge_rt
  - net/ipv6/ip6_fib.c:fib6_info_destroy_rcu
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:ip6_fl_gc
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/addrconf_core.c:in6_dev_finish_destroy
  - net/8021q/vlan_core.c:vlan_vid_del
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_netdev_handler
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/mctp/neigh.c:mctp_neigh_net_exit
  - net/mctp/neigh.c:mctp_rtm_delneigh
  - net/mctp/neigh.c:mctp_neigh_remove_dev
  - lib/maple_tree.c:mtree_destroy
  - lib/maple_tree.c:mas_wmb_replace
  - lib/maple_tree.c:mas_wmb_replace
  - lib/maple_tree.c:mas_replace
  - lib/radix-tree.c:idr_destroy
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_free_nodes
```
**Symbols:**

```
ffffffff811cb1a0-ffffffff811cb1b8: call_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void call_rcu(struct callback_head *head, rcu_callback_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:2832
Inline: False
Direct callers:
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:remove_kmmio_fault_pages
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mmap
  - kernel/fork.c:put_task_stack
  - kernel/workqueue.c:pwq_release_workfn
  - kernel/workqueue.c:pwq_release_workfn
  - kernel/workqueue.c:pwq_release_workfn
  - kernel/workqueue.c:put_unbound_pool
  - kernel/pid.c:free_pid
  - kernel/cred.c:__put_cred
  - kernel/sched/core.c:cpu_cgroup_css_free
  - kernel/sched/core.c:sched_destroy_group
  - kernel/sched/core.c:sched_unregister_group_rcu
  - kernel/sched/build_utility.c:cpu_attach_domain
  - kernel/sched/build_utility.c:sched_put_rd
  - kernel/sched/build_utility.c:rq_attach_root
  - kernel/sched/build_utility.c:build_perf_domains
  - kernel/sched/build_utility.c:build_perf_domains
  - kernel/irq/irqdesc.c:free_desc
  - kernel/dma/swiotlb.c:swiotlb_tbl_unmap_single
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/posix-timers.c:posix_timer_unhash_and_free
  - kernel/pid_namespace.c:put_pid_ns
  - kernel/audit.c:auditd_set
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/auditfilter.c:audit_del_rule
  - kernel/audit_watch.c:audit_remove_parent_watches
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_tree.c:audit_tree_freeing_mark
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:kill_rules
  - kernel/audit_tree.c:tag_chunk
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_add_func
  - kernel/tracepoint.c:release_early_probes
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/rethook.c:rethook_trampoline_handler
  - kernel/trace/rethook.c:rethook_free
  - kernel/trace/rethook.c:rethook_flush_task
  - kernel/bpf/syscall.c:__bpf_prog_put_noref
  - kernel/bpf/arraymap.c:perf_event_fd_array_put_ptr
  - kernel/bpf/local_storage.c:cgroup_storage_map_free
  - kernel/bpf/local_storage.c:cgroup_storage_map_free
  - kernel/bpf/devmap.c:dev_map_notification
  - kernel/bpf/devmap.c:dev_map_notification
  - kernel/bpf/devmap.c:__dev_map_hash_update_elem
  - kernel/bpf/devmap.c:__dev_map_hash_update_elem
  - kernel/bpf/devmap.c:__dev_map_update_elem
  - kernel/bpf/devmap.c:dev_map_hash_delete_elem
  - kernel/bpf/devmap.c:dev_map_delete_elem
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:put_pmu_ctx
  - kernel/events/callchain.c:put_callchain_buffers
  - kernel/watch_queue.c:watch_queue_clear
  - kernel/watch_queue.c:watch_queue_clear
  - kernel/watch_queue.c:remove_watch_from_object
  - kernel/watch_queue.c:remove_watch_from_object
  - mm/shrinker.c:shrinker_free
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_remove_table
  - mm/pgtable-generic.c:pte_free_defer
  - mm/slub.c:free_slab
  - mm/kfence/core.c:__kfence_free
  - fs/fcntl.c:fasync_remove_entry
  - fs/dcache.c:dentry_free
  - fs/dcache.c:dentry_free
  - fs/inode.c:destroy_inode
  - fs/file.c:expand_files
  - fs/namespace.c:cleanup_mnt
  - fs/eventpoll.c:__ep_remove
  - fs/ext4/block_validity.c:ext4_release_system_zone
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/fat/inode.c:fat_put_super
  - fs/ecryptfs/dentry.c:ecryptfs_d_release
  - ipc/util.c:ipc_rcu_putref
  - ipc/shm.c:newseg
  - security/keys/request_key_auth.c:request_key_auth_destroy
  - security/keys/request_key_auth.c:request_key_auth_revoke
  - security/keys/user_defined.c:user_revoke
  - security/keys/user_defined.c:user_update
  - security/keys/trusted-keys/trusted_core.c:trusted_update
  - security/keys/encrypted-keys/encrypted.c:encrypted_update
  - security/security.c:security_inode_free
  - security/selinux/avc.c:avc_ss_reset
  - security/selinux/avc.c:avc_node_replace
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_destroy
  - security/apparmor/label.c:aa_vec_unique
  - security/apparmor/label.c:aa_vec_unique
  - security/apparmor/label.c:__aa_proxy_redirect
  - security/apparmor/label.c:aa_proxy_kref
  - security/apparmor/label.c:aa_get_current_ns
  - security/safesetid/securityfs.c:handle_policy_update
  - block/blk-core.c:blk_put_queue
  - block/blk-ioc.c:ioc_destroy_icq
  - block/blk-stat.c:blk_stat_free_callback
  - block/blk-cgroup.c:blkg_release
  - io_uring/register.c:io_eventfd_unregister
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/assoc_array.c:assoc_array_apply_edit
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/net/tun.c:tun_free_netdev
  - drivers/net/tun.c:tun_free_netdev
  - drivers/md/dm-stats.c:message_stats_delete
  - net/core/sock.c:sk_destruct
  - net/core/neighbour.c:neigh_table_clear
  - net/core/neighbour.c:___neigh_create
  - net/core/filter.c:sk_filter_charge
  - net/core/filter.c:sk_filter_uncharge
  - net/core/sock_reuseport.c:reuseport_detach_sock
  - net/core/sock_reuseport.c:reuseport_resurrect
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/xdp.c:mem_allocator_disconnect
  - net/core/net-sysfs.c:rx_queue_release
  - net/core/net-sysfs.c:store_rps_dev_flow_table_cnt
  - net/core/netpoll.c:__netpoll_cleanup
  - net/sched/sch_generic.c:__qdisc_destroy
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_cleanup
  - net/netlink/af_netlink.c:netlink_release
  - net/netfilter/core.c:nf_hook_entries_delete_raw
  - net/netfilter/core.c:__nf_unregister_net_hook
  - net/netfilter/core.c:__nf_register_net_hook
  - net/netfilter/core.c:nf_hook_entries_insert_raw
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/ip_sockglue.c:ip_ra_control
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_minisocks.c:tcp_twsk_destructor
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_reset_cipher
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_ctx_destroy
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_destroy_cipher
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:inetdev_destroy
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/ipv4/fib_trie.c:fib_free_table
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_flush_external
  - net/ipv4/fib_trie.c:fib_table_flush_external
  - net/ipv4/fib_trie.c:fib_table_flush_external
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_table_delete
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_insert_alias
  - net/ipv4/fib_trie.c:resize
  - net/ipv4/inet_fragment.c:inet_frag_destroy
  - net/ipv4/nexthop.c:nexthop_net_exit_batch
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:nexthop_create_group
  - net/ipv4/nexthop.c:replace_nexthop
  - net/ipv4/nexthop.c:remove_nh_grp_entry
  - net/ipv4/nexthop.c:nexthop_free_rcu
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_delete
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv4/tcp_sigpool.c:sigpool_reserve_scratch
  - net/ipv4/tcp_ao.c:tcp_ao_del_cmd
  - net/ipv4/tcp_ao.c:tcp_ao_connect_init
  - net/ipv4/tcp_ao.c:tcp_ao_destroy_sock
  - net/ipv4/tcp_ao.c:tcp_ao_destroy_sock
  - net/ipv4/tcp_ao.c:tcp_ao_destroy_sock
  - net/xfrm/xfrm_policy.c:xfrm_policy_destroy
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:aca_free_rcu
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:addrconf_permanent_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:cleanup_prefix_route
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_del_rt_siblings
  - net/ipv6/route.c:ip6_route_add
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/route.c:ip6_dst_destroy
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_purge_rt
  - net/ipv6/ip6_fib.c:fib6_info_destroy_rcu
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:ip6_fl_gc
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/addrconf_core.c:in6_dev_finish_destroy
  - net/8021q/vlan_core.c:vlan_vid_del
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_netdev_handler
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/mctp/neigh.c:mctp_neigh_net_exit
  - net/mctp/neigh.c:mctp_rtm_delneigh
  - net/mctp/neigh.c:mctp_neigh_remove_dev
  - lib/maple_tree.c:mtree_destroy
  - lib/maple_tree.c:mas_wr_bnode
  - lib/maple_tree.c:mas_wr_node_store
  - lib/maple_tree.c:mas_destroy_rebalance
  - lib/maple_tree.c:mas_topiary_replace
  - lib/maple_tree.c:mas_topiary_replace
  - lib/maple_tree.c:mas_topiary_replace
  - lib/maple_tree.c:mas_topiary_replace
  - lib/radix-tree.c:idr_destroy
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_free_nodes
```
**Symbols:**

```
ffffffff821b423a-ffffffff821b4255: call_rcu.cold (STB_LOCAL)
ffffffff811e0bf0-ffffffff811e0c37: call_rcu (STB_GLOBAL)
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
void call_rcu(struct callback_head *head, rcu_callback_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffff80001018f140)
Location: kernel/rcu/tree.c:2650
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/exit.c:put_task_struct_rcu_user
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:pwq_unbound_release_workfn
  - kernel/workqueue.c:pwq_unbound_release_workfn
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:queue_rcu_work
  - kernel/pid.c:free_pid
  - kernel/cred.c:__put_cred
  - kernel/sched/core.c:sched_destroy_group
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:sched_put_rd
  - kernel/sched/topology.c:rq_attach_root
  - kernel/irq/irqdesc.c:free_desc
  - kernel/rcu/sync.c:rcu_sync_exit
  - kernel/rcu/sync.c:rcu_sync_func
  - kernel/time/posix-timers.c:release_posix_timer
  - kernel/pid_namespace.c:put_pid_ns
  - kernel/audit.c:audit_receive_msg
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/auditfilter.c:audit_del_rule
  - kernel/audit_watch.c:audit_watch_handle_event
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:kill_rules
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_probe_register_prio
  - kernel/tracepoint.c:release_early_probes
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/bpf/arraymap.c:perf_event_fd_array_put_ptr
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_free
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_free
  - kernel/bpf/devmap.c:dev_map_notification
  - kernel/bpf/devmap.c:dev_map_notification
  - kernel/bpf/devmap.c:dev_map_hash_update_elem
  - kernel/bpf/devmap.c:dev_map_hash_update_elem
  - kernel/bpf/devmap.c:dev_map_update_elem
  - kernel/bpf/devmap.c:dev_map_hash_delete_elem
  - kernel/bpf/devmap.c:dev_map_delete_elem
  - kernel/events/core.c:_free_event
  - kernel/events/callchain.c:put_callchain_buffers
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:memcg_update_all_caches
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/mmu_gather.c:tlb_table_flush
  - mm/slub.c:discard_slab
  - mm/memcontrol.c:memcg_expand_shrinker_maps
  - fs/file_table.c:__fput
  - fs/fcntl.c:fasync_remove_entry
  - fs/dcache.c:dentry_free
  - fs/dcache.c:dentry_free
  - fs/file.c:expand_files
  - fs/namespace.c:cleanup_mnt
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/eventpoll.c:ep_remove
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/resize.c:ext4_kvfree_array_rcu
  - fs/fat/inode.c:fat_put_super
  - fs/ecryptfs/dentry.c:ecryptfs_d_release
  - ipc/util.c:ipc_rcu_putref
  - ipc/shm.c:newseg
  - security/keys/request_key_auth.c:request_key_auth_destroy
  - security/keys/request_key_auth.c:request_key_auth_revoke
  - security/keys/user_defined.c:user_revoke
  - security/keys/user_defined.c:user_update
  - security/keys/trusted.c:trusted_update
  - security/keys/encrypted-keys/encrypted.c:encrypted_update
  - security/security.c:security_inode_free
  - security/selinux/avc.c:avc_compute_av
  - security/selinux/avc.c:avc_node_delete
  - security/apparmor/label.c:aa_label_kref
  - security/safesetid/securityfs.c:safesetid_file_write
  - block/blk-sysfs.c:__blk_release_queue
  - block/blk-ioc.c:ioc_destroy_icq
  - block/blk-stat.c:blk_stat_free_callback
  - block/blk-cgroup.c:blkg_release
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/assoc_array.c:assoc_array_apply_edit
  - lib/assoc_array.c:assoc_array_apply_edit
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
  - drivers/net/tun.c:__tun_set_ebpf
  - drivers/md/dm-stats.c:dm_stats_message
  - net/core/sock.c:sk_destruct
  - net/core/neighbour.c:neigh_table_clear
  - net/core/neighbour.c:___neigh_create
  - net/core/filter.c:sk_filter_release
  - net/core/sock_reuseport.c:reuseport_detach_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
  - net/core/net-sysfs.c:rx_queue_release
  - net/core/net-sysfs.c:store_rps_dev_flow_table_cnt
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_drop
  - net/core/netpoll.c:__netpoll_cleanup
  - net/sched/sch_generic.c:mini_qdisc_pair_swap
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/act_api.c:tcf_set_action_cookie
  - net/netlink/af_netlink.c:netlink_release
  - net/ipv4/inetpeer.c:inet_putpeer
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/ip_sockglue.c:ip_ra_control
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_reset_cipher
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_ctx_destroy
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_destroy_cipher
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/fib_semantics.c:free_fib_info
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/ipv4/fib_trie.c:fib_free_table
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_flush_external
  - net/ipv4/fib_trie.c:fib_table_flush_external
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_table_delete
  - net/ipv4/fib_trie.c:fib_table_delete
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_insert_alias
  - net/ipv4/fib_trie.c:resize
  - net/ipv4/fib_trie.c:tnode_free
  - net/ipv4/inet_fragment.c:inet_frag_destroy
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:remove_nexthop
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_putdef
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:aca_put
  - net/ipv6/anycast.c:aca_free_rcu
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:cleanup_prefix_route
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_del_rt
  - net/ipv6/route.c:ip6_route_add
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/route.c:ip6_dst_destroy
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_info_destroy_rcu
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ip6_flowlabel.c:fl_free
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/calipso.c:calipso_doi_remove
  - net/ipv6/addrconf_core.c:in6_dev_finish_destroy
  - net/8021q/vlan_core.c:vlan_vid_del
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_netdev_handler
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - lib/radix-tree.c:idr_destroy
  - lib/radix-tree.c:idr_destroy
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_free_nodes
```
**Symbols:**

```
ffff80001018f140-ffff80001018f178: call_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void call_rcu(struct callback_head *head, rcu_callback_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (c03dc5f0)
Location: kernel/rcu/tree.c:2650
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/exit.c:put_task_struct_rcu_user
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:pwq_unbound_release_workfn
  - kernel/workqueue.c:pwq_unbound_release_workfn
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:queue_rcu_work
  - kernel/pid.c:free_pid
  - kernel/cred.c:__put_cred
  - kernel/sched/core.c:sched_destroy_group
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:sched_put_rd
  - kernel/sched/topology.c:rq_attach_root
  - kernel/irq/irqdesc.c:free_desc
  - kernel/rcu/sync.c:rcu_sync_exit
  - kernel/rcu/sync.c:rcu_sync_func
  - kernel/time/posix-timers.c:release_posix_timer
  - kernel/pid_namespace.c:put_pid_ns
  - kernel/audit.c:audit_receive_msg
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/auditfilter.c:audit_del_rule
  - kernel/audit_watch.c:audit_watch_handle_event
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_tree.c:audit_tree_freeing_mark
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:kill_rules
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_probe_register_prio
  - kernel/tracepoint.c:release_early_probes
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/bpf/arraymap.c:perf_event_fd_array_put_ptr
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_free
  - kernel/bpf/devmap.c:dev_map_notification
  - kernel/bpf/devmap.c:dev_map_notification
  - kernel/bpf/devmap.c:dev_map_hash_update_elem
  - kernel/bpf/devmap.c:dev_map_hash_update_elem
  - kernel/bpf/devmap.c:dev_map_update_elem
  - kernel/bpf/devmap.c:dev_map_hash_delete_elem
  - kernel/bpf/devmap.c:dev_map_delete_elem
  - kernel/bpf/cpumap.c:__cpu_map_entry_replace
  - kernel/events/core.c:_free_event
  - kernel/events/callchain.c:put_callchain_buffers
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:memcg_update_all_caches
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/slub.c:discard_slab
  - mm/memcontrol.c:memcg_expand_shrinker_maps
  - fs/file_table.c:__fput
  - fs/fcntl.c:fasync_remove_entry
  - fs/dcache.c:dentry_free
  - fs/dcache.c:dentry_free
  - fs/file.c:expand_files
  - fs/namespace.c:cleanup_mnt
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/eventpoll.c:ep_remove
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/resize.c:ext4_kvfree_array_rcu
  - fs/fat/inode.c:fat_put_super
  - fs/ecryptfs/dentry.c:ecryptfs_d_release
  - ipc/util.c:ipc_rcu_putref
  - ipc/shm.c:newseg
  - security/keys/request_key_auth.c:request_key_auth_destroy
  - security/keys/request_key_auth.c:request_key_auth_revoke
  - security/keys/user_defined.c:user_revoke
  - security/keys/user_defined.c:user_update
  - security/keys/trusted.c:trusted_update
  - security/keys/encrypted-keys/encrypted.c:encrypted_update
  - security/security.c:security_inode_free
  - security/selinux/avc.c:avc_node_replace
  - security/selinux/avc.c:avc_node_delete
  - security/apparmor/label.c:aa_label_kref
  - security/safesetid/securityfs.c:safesetid_file_write
  - block/blk-sysfs.c:__blk_release_queue
  - block/blk-ioc.c:ioc_destroy_icq
  - block/blk-stat.c:blk_stat_free_callback
  - block/blk-cgroup.c:blkg_release
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/assoc_array.c:assoc_array_apply_edit
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
  - drivers/net/tun.c:__tun_set_ebpf
  - drivers/md/dm-stats.c:dm_stats_message
  - net/core/sock.c:sk_destruct
  - net/core/dst.c:dst_release
  - net/core/neighbour.c:neigh_table_clear
  - net/core/neighbour.c:___neigh_create
  - net/core/filter.c:sk_filter_release
  - net/core/sock_reuseport.c:reuseport_detach_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
  - net/core/net-sysfs.c:rx_queue_release
  - net/core/net-sysfs.c:store_rps_dev_flow_table_cnt
  - net/core/skmsg.c:sk_psock_drop
  - net/core/netpoll.c:__netpoll_cleanup
  - net/sched/sch_generic.c:mini_qdisc_pair_swap
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/act_api.c:tcf_set_action_cookie
  - net/netlink/af_netlink.c:netlink_release
  - net/ipv4/inetpeer.c:inet_putpeer
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/ip_sockglue.c:ip_ra_control
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_reset_cipher
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_ctx_destroy
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_destroy_cipher
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/fib_semantics.c:free_fib_info
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/ipv4/fib_trie.c:fib_free_table
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_flush_external
  - net/ipv4/fib_trie.c:fib_table_flush_external
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_table_delete
  - net/ipv4/fib_trie.c:fib_table_delete
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_insert_alias
  - net/ipv4/fib_trie.c:resize
  - net/ipv4/fib_trie.c:tnode_free
  - net/ipv4/inet_fragment.c:inet_frag_destroy
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:nexthop_create_group
  - net/ipv4/nexthop.c:remove_nexthop
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_delete
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_putdef
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:aca_put
  - net/ipv6/anycast.c:aca_free_rcu
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:cleanup_prefix_route
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_del_rt
  - net/ipv6/route.c:ip6_route_add
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/route.c:ip6_dst_destroy
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_info_destroy_rcu
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ip6_flowlabel.c:fl_free
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/calipso.c:calipso_doi_remove
  - net/ipv6/addrconf_core.c:in6_dev_finish_destroy
  - net/8021q/vlan_core.c:vlan_vid_del
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_netdev_handler
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - lib/radix-tree.c:idr_destroy
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_free_nodes
```
**Symbols:**

```
c03dc5f0-c03dc610: call_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void call_rcu(struct callback_head *head, rcu_callback_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (c0000000001e9a90)
Location: kernel/rcu/tree.c:2650
Inline: False
Direct callers:
  - arch/powerpc/mm/book3s64/iommu_api.c:mm_iommu_put
  - arch/powerpc/platforms/powernv/pci-ioda-tce.c:pnv_pci_unlink_table_and_group
  - kernel/fork.c:copy_process
  - kernel/exit.c:put_task_struct_rcu_user
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:pwq_unbound_release_workfn
  - kernel/workqueue.c:pwq_unbound_release_workfn
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:queue_rcu_work
  - kernel/pid.c:free_pid
  - kernel/cred.c:__put_cred
  - kernel/sched/core.c:sched_destroy_group
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:sched_put_rd
  - kernel/sched/topology.c:rq_attach_root
  - kernel/irq/irqdesc.c:free_desc
  - kernel/rcu/sync.c:rcu_sync_exit
  - kernel/rcu/sync.c:rcu_sync_func
  - kernel/time/posix-timers.c:release_posix_timer
  - kernel/time/posix-timers.c:release_posix_timer
  - kernel/pid_namespace.c:put_pid_ns
  - kernel/audit.c:audit_receive_msg
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/auditfilter.c:audit_del_rule
  - kernel/audit_watch.c:audit_watch_handle_event
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_tree.c:audit_tree_freeing_mark
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:kill_rules
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_probe_register_prio
  - kernel/tracepoint.c:release_early_probes
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/bpf/arraymap.c:perf_event_fd_array_put_ptr
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_free
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_free
  - kernel/bpf/devmap.c:dev_map_notification
  - kernel/bpf/devmap.c:dev_map_notification
  - kernel/bpf/devmap.c:dev_map_hash_update_elem
  - kernel/bpf/devmap.c:dev_map_hash_update_elem
  - kernel/bpf/devmap.c:dev_map_update_elem
  - kernel/bpf/devmap.c:dev_map_hash_delete_elem
  - kernel/bpf/devmap.c:dev_map_delete_elem
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:_free_event
  - kernel/events/callchain.c:put_callchain_buffers
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:memcg_update_all_caches
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/mmu_gather.c:tlb_flush_mmu
  - mm/mmu_gather.c:tlb_remove_table
  - mm/slub.c:discard_slab
  - mm/memcontrol.c:memcg_expand_shrinker_maps
  - fs/file_table.c:__fput
  - fs/file_table.c:__fput
  - fs/fcntl.c:fasync_remove_entry
  - fs/dcache.c:dentry_free
  - fs/dcache.c:dentry_free
  - fs/inode.c:destroy_inode
  - fs/file.c:expand_files
  - fs/namespace.c:cleanup_mnt
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/eventpoll.c:ep_remove
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/resize.c:ext4_kvfree_array_rcu
  - fs/fat/inode.c:fat_put_super
  - fs/ecryptfs/dentry.c:ecryptfs_d_release
  - ipc/util.c:ipc_rcu_putref
  - ipc/shm.c:newseg
  - security/keys/request_key_auth.c:request_key_auth_destroy
  - security/keys/request_key_auth.c:request_key_auth_revoke
  - security/keys/user_defined.c:user_revoke
  - security/keys/user_defined.c:user_update
  - security/keys/trusted.c:trusted_update
  - security/keys/encrypted-keys/encrypted.c:encrypted_update
  - security/security.c:security_inode_free
  - security/selinux/avc.c:avc_node_replace
  - security/selinux/avc.c:avc_node_delete
  - security/apparmor/label.c:aa_label_kref
  - security/safesetid/securityfs.c:safesetid_file_write
  - block/blk-sysfs.c:__blk_release_queue
  - block/blk-ioc.c:ioc_destroy_icq
  - block/blk-stat.c:blk_stat_free_callback
  - block/blk-cgroup.c:blkg_release
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/assoc_array.c:assoc_array_apply_edit
  - lib/assoc_array.c:assoc_array_apply_edit
  - lib/assoc_array.c:assoc_array_apply_edit
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
  - drivers/net/tun.c:__tun_set_ebpf
  - drivers/md/dm-stats.c:dm_stats_message
  - net/core/sock.c:sk_destruct
  - net/core/sock.c:sk_destruct
  - net/core/dst.c:dst_release
  - net/core/neighbour.c:neigh_table_clear
  - net/core/neighbour.c:___neigh_create
  - net/core/filter.c:sk_filter_release
  - net/core/sock_reuseport.c:reuseport_detach_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_allocator_disconnect
  - net/core/net-sysfs.c:rx_queue_release
  - net/core/net-sysfs.c:store_rps_dev_flow_table_cnt
  - net/core/skmsg.c:sk_psock_drop
  - net/core/netpoll.c:__netpoll_cleanup
  - net/sched/sch_generic.c:mini_qdisc_pair_swap
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_cleanup
  - net/netlink/af_netlink.c:netlink_release
  - net/ipv4/inetpeer.c:inet_putpeer
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/ip_sockglue.c:ip_ra_control
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_reset_cipher
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_ctx_destroy
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_destroy_cipher
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/fib_semantics.c:free_fib_info
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/ipv4/fib_trie.c:fib_free_table
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_flush_external
  - net/ipv4/fib_trie.c:fib_table_flush_external
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_table_delete
  - net/ipv4/fib_trie.c:fib_table_delete
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_insert_alias
  - net/ipv4/fib_trie.c:resize
  - net/ipv4/fib_trie.c:tnode_free
  - net/ipv4/inet_fragment.c:inet_frag_destroy
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:remove_nexthop
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_putdef
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:aca_put
  - net/ipv6/anycast.c:aca_free_rcu
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:cleanup_prefix_route
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_del_rt
  - net/ipv6/route.c:ip6_route_add
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/route.c:ip6_dst_destroy
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_info_destroy_rcu
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ip6_flowlabel.c:fl_free
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/calipso.c:calipso_doi_remove
  - net/ipv6/addrconf_core.c:in6_dev_finish_destroy
  - net/8021q/vlan_core.c:vlan_vid_del
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_netdev_handler
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - lib/radix-tree.c:idr_destroy
  - lib/radix-tree.c:idr_destroy
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_free_nodes
```
**Symbols:**

```
c0000000001e9a90-c0000000001e9aa8: call_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void call_rcu(struct callback_head *head, rcu_callback_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffe000123332)
Location: kernel/rcu/tree.c:2650
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/exit.c:release_task
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:pwq_unbound_release_workfn
  - kernel/workqueue.c:pwq_unbound_release_workfn
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:queue_rcu_work
  - kernel/pid.c:free_pid
  - kernel/cred.c:__put_cred
  - kernel/sched/core.c:sched_destroy_group
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:sched_put_rd
  - kernel/sched/topology.c:rq_attach_root
  - kernel/irq/irqdesc.c:free_desc
  - kernel/rcu/sync.c:rcu_sync_exit
  - kernel/rcu/sync.c:rcu_sync_func
  - kernel/time/posix-timers.c:release_posix_timer
  - kernel/pid_namespace.c:destroy_pid_namespace
  - kernel/audit.c:audit_receive_msg
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/auditfilter.c:audit_del_rule
  - kernel/audit_watch.c:audit_watch_handle_event
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:kill_rules
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_probe_register_prio
  - kernel/tracepoint.c:release_early_probes
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/bpf/arraymap.c:perf_event_fd_array_put_ptr
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_free
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_free
  - kernel/bpf/devmap.c:dev_map_notification
  - kernel/bpf/devmap.c:dev_map_notification
  - kernel/bpf/devmap.c:dev_map_hash_update_elem
  - kernel/bpf/devmap.c:dev_map_hash_update_elem
  - kernel/bpf/devmap.c:dev_map_update_elem
  - kernel/bpf/devmap.c:dev_map_hash_delete_elem
  - kernel/bpf/devmap.c:dev_map_delete_elem
  - kernel/events/core.c:_free_event
  - kernel/events/callchain.c:put_callchain_buffers
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:memcg_update_all_caches
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/slub.c:free_slab
  - mm/memcontrol.c:memcg_expand_shrinker_maps
  - fs/file_table.c:__fput
  - fs/fcntl.c:fasync_remove_entry
  - fs/dcache.c:dentry_free
  - fs/file.c:expand_files
  - fs/namespace.c:cleanup_mnt
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/eventpoll.c:ep_remove
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/resize.c:ext4_kvfree_array_rcu
  - fs/fat/inode.c:fat_put_super
  - fs/ecryptfs/dentry.c:ecryptfs_d_release
  - ipc/util.c:ipc_rcu_putref
  - ipc/shm.c:newseg
  - security/keys/request_key_auth.c:request_key_auth_destroy
  - security/keys/request_key_auth.c:request_key_auth_revoke
  - security/keys/user_defined.c:user_revoke
  - security/keys/user_defined.c:user_update
  - security/keys/trusted.c:trusted_update
  - security/keys/encrypted-keys/encrypted.c:encrypted_update
  - security/security.c:security_inode_free
  - security/selinux/avc.c:avc_compute_av
  - security/selinux/avc.c:avc_flush
  - security/selinux/avc.c:avc_alloc_node
  - security/apparmor/label.c:aa_label_kref
  - security/safesetid/securityfs.c:safesetid_file_write
  - block/blk-sysfs.c:__blk_release_queue
  - block/blk-ioc.c:ioc_destroy_icq
  - block/blk-stat.c:blk_stat_free_callback
  - block/blk-cgroup.c:blkg_release
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/assoc_array.c:assoc_array_apply_edit
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
  - drivers/net/tun.c:__tun_set_ebpf
  - drivers/md/dm-stats.c:dm_stats_message
  - net/core/sock.c:sk_destruct
  - net/core/dst.c:dst_release
  - net/core/neighbour.c:neigh_table_clear
  - net/core/neighbour.c:___neigh_create
  - net/core/filter.c:sk_filter_charge
  - net/core/filter.c:sk_filter_uncharge
  - net/core/sock_reuseport.c:reuseport_detach_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_allocator_disconnect
  - net/core/net-sysfs.c:rx_queue_release
  - net/core/net-sysfs.c:store_rps_dev_flow_table_cnt
  - net/core/skmsg.c:sk_psock_drop
  - net/core/netpoll.c:__netpoll_cleanup
  - net/sched/sch_generic.c:mini_qdisc_pair_swap
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_cleanup
  - net/netlink/af_netlink.c:netlink_release
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/ip_sockglue.c:ip_ra_control
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_reset_cipher
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_ctx_destroy
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_destroy_cipher
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/fib_semantics.c:free_fib_info
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/ipv4/fib_trie.c:fib_free_table
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_flush_external
  - net/ipv4/fib_trie.c:fib_table_flush_external
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_table_delete
  - net/ipv4/fib_trie.c:fib_table_delete
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_insert_alias
  - net/ipv4/fib_trie.c:resize
  - net/ipv4/fib_trie.c:tnode_free
  - net/ipv4/inet_fragment.c:inet_frag_destroy
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:remove_nexthop
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_putdef
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:aca_free_rcu
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:cleanup_prefix_route
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_del_rt
  - net/ipv6/route.c:ip6_route_add
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/route.c:ip6_dst_destroy
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_info_destroy_rcu
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ip6_flowlabel.c:fl_free
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/calipso.c:calipso_doi_remove
  - net/ipv6/addrconf_core.c:in6_dev_finish_destroy
  - net/8021q/vlan_core.c:vlan_vid_del
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_netdev_handler
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - lib/radix-tree.c:idr_destroy
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_free_nodes
```
**Symbols:**

```
ffffffe000123332-ffffffe000123366: call_rcu (STB_GLOBAL)
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
void call_rcu(struct callback_head *head, rcu_callback_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81120980)
Location: kernel/rcu/tree.c:2650
Inline: False
Direct callers:
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:remove_kmmio_fault_pages
  - kernel/fork.c:copy_process
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:pwq_unbound_release_workfn
  - kernel/workqueue.c:pwq_unbound_release_workfn
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:queue_rcu_work
  - kernel/pid.c:free_pid
  - kernel/sched/core.c:sched_destroy_group
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:sched_put_rd
  - kernel/sched/topology.c:rq_attach_root
  - kernel/irq/irqdesc.c:free_desc
  - kernel/rcu/sync.c:rcu_sync_exit
  - kernel/rcu/sync.c:rcu_sync_func
  - kernel/time/posix-timers.c:release_posix_timer
  - kernel/pid_namespace.c:destroy_pid_namespace
  - kernel/audit.c:audit_receive_msg
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/auditfilter.c:audit_del_rule
  - kernel/audit_watch.c:audit_watch_handle_event
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:kill_rules
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_probe_register_prio
  - kernel/tracepoint.c:release_early_probes
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/bpf/arraymap.c:perf_event_fd_array_put_ptr
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_free
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_free
  - kernel/bpf/devmap.c:dev_map_notification
  - kernel/bpf/devmap.c:dev_map_notification
  - kernel/bpf/devmap.c:dev_map_hash_update_elem
  - kernel/bpf/devmap.c:dev_map_hash_update_elem
  - kernel/bpf/devmap.c:dev_map_update_elem
  - kernel/bpf/devmap.c:dev_map_hash_delete_elem
  - kernel/bpf/devmap.c:dev_map_delete_elem
  - kernel/events/core.c:_free_event
  - kernel/events/callchain.c:put_callchain_buffers
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:memcg_update_all_caches
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/mmu_gather.c:tlb_table_flush
  - mm/slub.c:discard_slab
  - mm/memcontrol.c:memcg_expand_shrinker_maps
  - fs/file_table.c:__fput
  - fs/fcntl.c:fasync_remove_entry
  - fs/dcache.c:dentry_free
  - fs/file.c:expand_files
  - fs/namespace.c:cleanup_mnt
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/eventpoll.c:ep_remove
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/resize.c:ext4_kvfree_array_rcu
  - fs/fat/inode.c:fat_put_super
  - fs/ecryptfs/dentry.c:ecryptfs_d_release
  - ipc/util.c:ipc_rcu_putref
  - ipc/shm.c:newseg
  - security/keys/request_key_auth.c:request_key_auth_destroy
  - security/keys/request_key_auth.c:request_key_auth_revoke
  - security/keys/user_defined.c:user_revoke
  - security/keys/user_defined.c:user_update
  - security/keys/trusted.c:trusted_update
  - security/keys/encrypted-keys/encrypted.c:encrypted_update
  - security/security.c:security_inode_free
  - security/selinux/avc.c:avc_node_replace
  - security/selinux/avc.c:avc_node_delete
  - security/apparmor/label.c:aa_label_kref
  - security/safesetid/securityfs.c:safesetid_file_write
  - block/blk-sysfs.c:__blk_release_queue
  - block/blk-ioc.c:ioc_destroy_icq
  - block/blk-stat.c:blk_stat_free_callback
  - block/blk-cgroup.c:blkg_release
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/assoc_array.c:assoc_array_apply_edit
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
  - drivers/net/tun.c:__tun_set_ebpf
  - drivers/md/dm-stats.c:dm_stats_message
  - net/core/sock.c:sk_destruct
  - net/core/dst.c:dst_release
  - net/core/neighbour.c:neigh_table_clear
  - net/core/neighbour.c:___neigh_create
  - net/core/sock_reuseport.c:reuseport_detach_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
  - net/core/net-sysfs.c:rx_queue_release
  - net/core/net-sysfs.c:store_rps_dev_flow_table_cnt
  - net/core/skmsg.c:sk_psock_drop
  - net/core/netpoll.c:__netpoll_cleanup
  - net/sched/sch_generic.c:mini_qdisc_pair_swap
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_cleanup
  - net/netlink/af_netlink.c:netlink_release
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/ip_sockglue.c:ip_ra_control
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_reset_cipher
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_ctx_destroy
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_destroy_cipher
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/fib_semantics.c:free_fib_info
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/ipv4/fib_trie.c:fib_free_table
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_flush_external
  - net/ipv4/fib_trie.c:fib_table_flush_external
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_table_delete
  - net/ipv4/fib_trie.c:fib_table_delete
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_insert_alias
  - net/ipv4/fib_trie.c:resize
  - net/ipv4/fib_trie.c:tnode_free
  - net/ipv4/inet_fragment.c:inet_frag_destroy
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:remove_nexthop
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_putdef
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:aca_free_rcu
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:cleanup_prefix_route
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_del_rt
  - net/ipv6/route.c:ip6_route_add
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/route.c:ip6_dst_destroy
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_info_destroy_rcu
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ip6_flowlabel.c:fl_free
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/calipso.c:calipso_doi_remove
  - net/ipv6/addrconf_core.c:in6_dev_finish_destroy
  - net/8021q/vlan_core.c:vlan_vid_del
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_netdev_handler
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - lib/radix-tree.c:idr_destroy
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_free_nodes
```
**Symbols:**

```
ffffffff81120980-ffffffff81120992: call_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void call_rcu(struct callback_head *head, rcu_callback_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81113e80)
Location: kernel/rcu/tree.c:2650
Inline: False
Direct callers:
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:remove_kmmio_fault_pages
  - kernel/fork.c:copy_process
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:pwq_unbound_release_workfn
  - kernel/workqueue.c:pwq_unbound_release_workfn
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:queue_rcu_work
  - kernel/pid.c:free_pid
  - kernel/sched/core.c:sched_destroy_group
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:sched_put_rd
  - kernel/sched/topology.c:rq_attach_root
  - kernel/irq/irqdesc.c:free_desc
  - kernel/rcu/sync.c:rcu_sync_exit
  - kernel/rcu/sync.c:rcu_sync_func
  - kernel/time/posix-timers.c:release_posix_timer
  - kernel/pid_namespace.c:destroy_pid_namespace
  - kernel/audit.c:audit_receive_msg
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/auditfilter.c:audit_del_rule
  - kernel/audit_watch.c:audit_watch_handle_event
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:kill_rules
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_probe_register_prio
  - kernel/tracepoint.c:release_early_probes
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/bpf/arraymap.c:perf_event_fd_array_put_ptr
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_free
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_free
  - kernel/bpf/devmap.c:dev_map_notification
  - kernel/bpf/devmap.c:dev_map_notification
  - kernel/bpf/devmap.c:dev_map_hash_update_elem
  - kernel/bpf/devmap.c:dev_map_hash_update_elem
  - kernel/bpf/devmap.c:dev_map_update_elem
  - kernel/bpf/devmap.c:dev_map_hash_delete_elem
  - kernel/bpf/devmap.c:dev_map_delete_elem
  - kernel/events/core.c:_free_event
  - kernel/events/callchain.c:put_callchain_buffers
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:memcg_update_all_caches
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/mmu_gather.c:tlb_table_flush
  - mm/slub.c:discard_slab
  - mm/memcontrol.c:memcg_expand_shrinker_maps
  - fs/file_table.c:__fput
  - fs/fcntl.c:fasync_remove_entry
  - fs/dcache.c:dentry_free
  - fs/file.c:expand_files
  - fs/namespace.c:cleanup_mnt
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/eventpoll.c:ep_remove
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/resize.c:ext4_kvfree_array_rcu
  - fs/fat/inode.c:fat_put_super
  - fs/ecryptfs/dentry.c:ecryptfs_d_release
  - ipc/util.c:ipc_rcu_putref
  - ipc/shm.c:newseg
  - security/keys/request_key_auth.c:request_key_auth_destroy
  - security/keys/request_key_auth.c:request_key_auth_revoke
  - security/keys/user_defined.c:user_revoke
  - security/keys/user_defined.c:user_update
  - security/keys/trusted.c:trusted_update
  - security/keys/encrypted-keys/encrypted.c:encrypted_update
  - security/security.c:security_inode_free
  - security/selinux/avc.c:avc_node_replace
  - security/selinux/avc.c:avc_node_delete
  - security/apparmor/label.c:aa_label_kref
  - security/safesetid/securityfs.c:safesetid_file_write
  - block/blk-sysfs.c:__blk_release_queue
  - block/blk-ioc.c:ioc_destroy_icq
  - block/blk-stat.c:blk_stat_free_callback
  - block/blk-cgroup.c:blkg_release
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/assoc_array.c:assoc_array_apply_edit
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
  - drivers/net/tun.c:__tun_set_ebpf
  - drivers/net/vxlan.c:__vxlan_fdb_delete
  - drivers/net/vxlan.c:vxlan_fdb_update_existing
  - drivers/net/vxlan.c:vxlan_fdb_destroy
  - drivers/md/dm-stats.c:dm_stats_message
  - net/core/sock.c:sk_destruct
  - net/core/dst.c:dst_release
  - net/core/neighbour.c:neigh_table_clear
  - net/core/neighbour.c:___neigh_create
  - net/core/sock_reuseport.c:reuseport_detach_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
  - net/core/net-sysfs.c:rx_queue_release
  - net/core/net-sysfs.c:store_rps_dev_flow_table_cnt
  - net/core/skmsg.c:sk_psock_drop
  - net/core/netpoll.c:__netpoll_cleanup
  - net/sched/sch_generic.c:mini_qdisc_pair_swap
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_cleanup
  - net/netlink/af_netlink.c:netlink_release
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/ip_sockglue.c:ip_ra_control
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_reset_cipher
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_ctx_destroy
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_destroy_cipher
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/fib_semantics.c:free_fib_info
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/ipv4/fib_trie.c:fib_free_table
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_flush_external
  - net/ipv4/fib_trie.c:fib_table_flush_external
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_table_delete
  - net/ipv4/fib_trie.c:fib_table_delete
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_insert_alias
  - net/ipv4/fib_trie.c:resize
  - net/ipv4/fib_trie.c:tnode_free
  - net/ipv4/inet_fragment.c:inet_frag_destroy
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:remove_nexthop
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_putdef
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:aca_free_rcu
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:cleanup_prefix_route
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_del_rt
  - net/ipv6/route.c:ip6_route_add
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/route.c:ip6_dst_destroy
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_info_destroy_rcu
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ip6_flowlabel.c:fl_free
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/calipso.c:calipso_doi_remove
  - net/ipv6/addrconf_core.c:in6_dev_finish_destroy
  - net/8021q/vlan_core.c:vlan_vid_del
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_netdev_handler
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - lib/radix-tree.c:idr_destroy
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_free_nodes
```
**Symbols:**

```
ffffffff81113e80-ffffffff81113e92: call_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void call_rcu(struct callback_head *head, rcu_callback_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8111e870)
Location: kernel/rcu/tree.c:2650
Inline: False
Direct callers:
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:remove_kmmio_fault_pages
  - kernel/fork.c:copy_process
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:pwq_unbound_release_workfn
  - kernel/workqueue.c:pwq_unbound_release_workfn
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:queue_rcu_work
  - kernel/pid.c:free_pid
  - kernel/sched/core.c:sched_destroy_group
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:sched_put_rd
  - kernel/sched/topology.c:rq_attach_root
  - kernel/irq/irqdesc.c:free_desc
  - kernel/rcu/sync.c:rcu_sync_exit
  - kernel/rcu/sync.c:rcu_sync_func
  - kernel/time/posix-timers.c:release_posix_timer
  - kernel/pid_namespace.c:destroy_pid_namespace
  - kernel/audit.c:audit_receive_msg
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/auditfilter.c:audit_del_rule
  - kernel/audit_watch.c:audit_watch_handle_event
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:kill_rules
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_probe_register_prio
  - kernel/tracepoint.c:release_early_probes
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/bpf/arraymap.c:perf_event_fd_array_put_ptr
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_free
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_free
  - kernel/bpf/devmap.c:dev_map_notification
  - kernel/bpf/devmap.c:dev_map_notification
  - kernel/bpf/devmap.c:dev_map_hash_update_elem
  - kernel/bpf/devmap.c:dev_map_hash_update_elem
  - kernel/bpf/devmap.c:dev_map_update_elem
  - kernel/bpf/devmap.c:dev_map_hash_delete_elem
  - kernel/bpf/devmap.c:dev_map_delete_elem
  - kernel/events/core.c:_free_event
  - kernel/events/callchain.c:put_callchain_buffers
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:memcg_update_all_caches
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/mmu_gather.c:tlb_table_flush
  - mm/slub.c:discard_slab
  - mm/memcontrol.c:memcg_expand_shrinker_maps
  - fs/file_table.c:__fput
  - fs/fcntl.c:fasync_remove_entry
  - fs/dcache.c:dentry_free
  - fs/file.c:expand_files
  - fs/namespace.c:cleanup_mnt
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/eventpoll.c:ep_remove
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/resize.c:ext4_kvfree_array_rcu
  - fs/fat/inode.c:fat_put_super
  - fs/ecryptfs/dentry.c:ecryptfs_d_release
  - ipc/util.c:ipc_rcu_putref
  - ipc/shm.c:newseg
  - security/keys/request_key_auth.c:request_key_auth_destroy
  - security/keys/request_key_auth.c:request_key_auth_revoke
  - security/keys/user_defined.c:user_revoke
  - security/keys/user_defined.c:user_update
  - security/keys/trusted.c:trusted_update
  - security/keys/encrypted-keys/encrypted.c:encrypted_update
  - security/security.c:security_inode_free
  - security/selinux/avc.c:avc_node_replace
  - security/selinux/avc.c:avc_node_delete
  - security/apparmor/label.c:aa_label_kref
  - security/safesetid/securityfs.c:safesetid_file_write
  - block/blk-sysfs.c:__blk_release_queue
  - block/blk-ioc.c:ioc_destroy_icq
  - block/blk-stat.c:blk_stat_free_callback
  - block/blk-cgroup.c:blkg_release
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/assoc_array.c:assoc_array_apply_edit
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
  - drivers/net/tun.c:__tun_set_ebpf
  - drivers/md/dm-stats.c:dm_stats_message
  - net/core/sock.c:sk_destruct
  - net/core/dst.c:dst_release
  - net/core/neighbour.c:neigh_table_clear
  - net/core/neighbour.c:___neigh_create
  - net/core/sock_reuseport.c:reuseport_detach_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
  - net/core/net-sysfs.c:rx_queue_release
  - net/core/net-sysfs.c:store_rps_dev_flow_table_cnt
  - net/core/skmsg.c:sk_psock_drop
  - net/core/netpoll.c:__netpoll_cleanup
  - net/sched/sch_generic.c:mini_qdisc_pair_swap
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_cleanup
  - net/netlink/af_netlink.c:netlink_release
  - net/netfilter/nfnetlink_queue.c:nfqnl_recv_config
  - net/netfilter/nfnetlink_queue.c:nfqnl_rcv_nl_event
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/ip_sockglue.c:ip_ra_control
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_reset_cipher
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_ctx_destroy
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_destroy_cipher
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/fib_semantics.c:free_fib_info
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/ipv4/fib_trie.c:fib_free_table
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_flush_external
  - net/ipv4/fib_trie.c:fib_table_flush_external
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_table_delete
  - net/ipv4/fib_trie.c:fib_table_delete
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_insert_alias
  - net/ipv4/fib_trie.c:resize
  - net/ipv4/fib_trie.c:tnode_free
  - net/ipv4/inet_fragment.c:inet_frag_destroy
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:remove_nexthop
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_putdef
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:aca_free_rcu
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:cleanup_prefix_route
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_del_rt
  - net/ipv6/route.c:ip6_route_add
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/route.c:ip6_dst_destroy
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_info_destroy_rcu
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ip6_flowlabel.c:fl_free
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/calipso.c:calipso_doi_remove
  - net/ipv6/addrconf_core.c:in6_dev_finish_destroy
  - net/8021q/vlan_core.c:vlan_vid_del
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_netdev_handler
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - lib/radix-tree.c:idr_destroy
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_free_nodes
```
**Symbols:**

```
ffffffff8111e870-ffffffff8111e882: call_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void call_rcu(struct callback_head *head, rcu_callback_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8112aba0)
Location: kernel/rcu/tree.c:2650
Inline: False
Direct callers:
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:remove_kmmio_fault_pages
  - kernel/fork.c:copy_process
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:pwq_unbound_release_workfn
  - kernel/workqueue.c:pwq_unbound_release_workfn
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:queue_rcu_work
  - kernel/pid.c:free_pid
  - kernel/sched/core.c:sched_destroy_group
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:sched_put_rd
  - kernel/sched/topology.c:rq_attach_root
  - kernel/irq/irqdesc.c:free_desc
  - kernel/rcu/sync.c:rcu_sync_exit
  - kernel/rcu/sync.c:rcu_sync_func
  - kernel/time/posix-timers.c:release_posix_timer
  - kernel/pid_namespace.c:destroy_pid_namespace
  - kernel/audit.c:audit_receive_msg
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/auditfilter.c:audit_del_rule
  - kernel/audit_watch.c:audit_watch_handle_event
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:kill_rules
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_probe_register_prio
  - kernel/tracepoint.c:release_early_probes
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/bpf/arraymap.c:perf_event_fd_array_put_ptr
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_free
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_free
  - kernel/bpf/devmap.c:dev_map_notification
  - kernel/bpf/devmap.c:dev_map_notification
  - kernel/bpf/devmap.c:dev_map_hash_update_elem
  - kernel/bpf/devmap.c:dev_map_hash_update_elem
  - kernel/bpf/devmap.c:dev_map_update_elem
  - kernel/bpf/devmap.c:dev_map_hash_delete_elem
  - kernel/bpf/devmap.c:dev_map_delete_elem
  - kernel/events/core.c:_free_event
  - kernel/events/callchain.c:put_callchain_buffers
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:memcg_update_all_caches
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/mmu_gather.c:tlb_table_flush
  - mm/slub.c:discard_slab
  - mm/memcontrol.c:memcg_expand_shrinker_maps
  - fs/file_table.c:__fput
  - fs/fcntl.c:fasync_remove_entry
  - fs/dcache.c:dentry_free
  - fs/file.c:expand_files
  - fs/namespace.c:cleanup_mnt
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/eventpoll.c:ep_remove
  - fs/ext4/block_validity.c:ext4_setup_system_zone
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/resize.c:ext4_kvfree_array_rcu
  - fs/fat/inode.c:fat_put_super
  - fs/ecryptfs/dentry.c:ecryptfs_d_release
  - ipc/util.c:ipc_rcu_putref
  - ipc/shm.c:newseg
  - security/keys/request_key_auth.c:request_key_auth_destroy
  - security/keys/request_key_auth.c:request_key_auth_revoke
  - security/keys/user_defined.c:user_revoke
  - security/keys/user_defined.c:user_update
  - security/keys/trusted.c:trusted_update
  - security/keys/encrypted-keys/encrypted.c:encrypted_update
  - security/security.c:security_inode_free
  - security/selinux/avc.c:avc_node_replace
  - security/selinux/avc.c:avc_node_delete
  - security/apparmor/label.c:aa_label_kref
  - security/safesetid/securityfs.c:safesetid_file_write
  - block/blk-sysfs.c:__blk_release_queue
  - block/blk-ioc.c:ioc_destroy_icq
  - block/blk-stat.c:blk_stat_free_callback
  - block/blk-cgroup.c:blkg_release
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/assoc_array.c:assoc_array_apply_edit
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
  - drivers/net/tun.c:__tun_set_ebpf
  - drivers/md/dm-stats.c:dm_stats_message
  - net/core/sock.c:sk_destruct
  - net/core/dst.c:dst_release
  - net/core/neighbour.c:neigh_table_clear
  - net/core/neighbour.c:___neigh_create
  - net/core/sock_reuseport.c:reuseport_detach_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
  - net/core/xdp.c:mem_xa_remove
  - net/core/net-sysfs.c:rx_queue_release
  - net/core/net-sysfs.c:store_rps_dev_flow_table_cnt
  - net/core/skmsg.c:sk_psock_drop
  - net/core/netpoll.c:__netpoll_cleanup
  - net/sched/sch_generic.c:mini_qdisc_pair_swap
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_cleanup
  - net/netlink/af_netlink.c:netlink_release
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/ip_sockglue.c:ip_ra_control
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_reset_cipher
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_ctx_destroy
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_destroy_cipher
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/fib_semantics.c:free_fib_info
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/ipv4/fib_trie.c:fib_free_table
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_flush_external
  - net/ipv4/fib_trie.c:fib_table_flush_external
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_table_delete
  - net/ipv4/fib_trie.c:fib_table_delete
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_insert_alias
  - net/ipv4/fib_trie.c:resize
  - net/ipv4/fib_trie.c:tnode_free
  - net/ipv4/inet_fragment.c:inet_frag_destroy
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:remove_nexthop
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_putdef
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:aca_free_rcu
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:cleanup_prefix_route
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_del_rt
  - net/ipv6/route.c:ip6_route_add
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/route.c:ip6_dst_destroy
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_info_destroy_rcu
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ip6_flowlabel.c:fl_free
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/calipso.c:calipso_doi_remove
  - net/ipv6/addrconf_core.c:in6_dev_finish_destroy
  - net/8021q/vlan_core.c:vlan_vid_del
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_netdev_handler
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - lib/radix-tree.c:idr_destroy
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_free_nodes
```
**Symbols:**

```
ffffffff8112aba0-ffffffff8112abb2: call_rcu (STB_GLOBAL)
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
