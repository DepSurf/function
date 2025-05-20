# Function: <code>kvfree_call_rcu</code>

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
<summary>In <code>5.11</code>: ✅</summary>

```c
void kvfree_call_rcu(struct callback_head *head, rcu_callback_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81133230)
Location: kernel/rcu/tree.c:3518
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_free
  - kernel/sched/fair.c:task_numa_group
  - kernel/livepatch/shadow.c:klp_shadow_free_struct
  - kernel/acct.c:acct_process
  - kernel/acct.c:acct_pin_kill
  - kernel/acct.c:acct_get
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_put_tree
  - kernel/audit_tree.c:audit_trim_trees
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:audit_put_chunk
  - kernel/bpf/core.c:bpf_prog_array_free
  - kernel/bpf/lpm_trie.c:trie_delete_elem
  - kernel/bpf/lpm_trie.c:trie_delete_elem
  - kernel/bpf/lpm_trie.c:trie_delete_elem
  - kernel/bpf/lpm_trie.c:trie_update_elem
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
  - kernel/bpf/bpf_inode_storage.c:bpf_inode_storage_free
  - kernel/bpf/bpf_task_storage.c:bpf_task_storage_free
  - kernel/bpf/trampoline.c:__bpf_tramp_image_put_deferred
  - kernel/bpf/bpf_local_storage.c:__bpf_selem_unlink_storage
  - kernel/bpf/bpf_local_storage.c:bpf_selem_unlink_storage_nolock
  - kernel/events/core.c:swevent_hlist_put_cpu
  - kernel/watch_queue.c:__put_watch_queue
  - kernel/watch_queue.c:__put_watch_queue
  - kernel/watch_queue.c:watch_queue_set_filter
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/vmalloc.c:free_vmap_block
  - mm/memcontrol.c:obj_cgroup_release
  - fs/dcache.c:__d_move
  - fs/dcache.c:release_dentry_name_snapshot
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
  - fs/timerfd.c:timerfd_release
  - fs/aio.c:ioctx_add_table
  - fs/io-wq.c:io_worker_exit
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:posix_acl_xattr_set
  - fs/posix_acl.c:posix_acl_xattr_get
  - fs/posix_acl.c:posix_acl_from_xattr
  - fs/posix_acl.c:__posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_create
  - fs/posix_acl.c:__posix_acl_create
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_cached_acl
  - fs/posix_acl.c:set_cached_acl
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/proc/proc_sysctl.c:proc_sys_evict_inode
  - fs/ext4/ialloc.c:ext4_xattr_credits_for_new_inode
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_acl_from_disk
  - fs/fuse/inode.c:fuse_free_conn
  - ipc/sem.c:exit_sem
  - ipc/sem.c:freeary
  - security/keys/keyring.c:key_remove_domain
  - security/selinux/netif.c:sel_netif_netdev_notifier_handler
  - security/selinux/netif.c:sel_netif_flush
  - security/selinux/netnode.c:sel_netnode_flush
  - security/selinux/netnode.c:sel_netnode_sid
  - security/selinux/netport.c:sel_netport_flush
  - security/selinux/netport.c:sel_netport_sid_slow
  - security/selinux/ibpkey.c:sel_ib_pkey_flush
  - security/selinux/ibpkey.c:sel_ib_pkey_sid_slow
  - security/yama/yama_lsm.c:yama_ptracer_add
  - security/yama/yama_lsm.c:yama_relation_cleanup
  - security/device_cgroup.c:__dev_exception_clean
  - security/device_cgroup.c:dev_exception_rm
  - block/genhd.c:disk_release
  - block/genhd.c:disk_expand_part_tbl
  - drivers/iommu/intel/svm.c:intel_svm_unbind_gpasid
  - drivers/iommu/ioasid.c:ioasid_put
  - drivers/iommu/ioasid.c:ioasid_unregister_allocator
  - drivers/iommu/ioasid.c:default_free
  - drivers/dma-buf/dma-fence.c:dma_fence_free
  - drivers/dma-buf/dma-fence.c:dma_fence_release
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared
  - drivers/dma-buf/dma-resv.c:dma_resv_fini
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext
  - drivers/net/tun.c:tun_flow_flush
  - drivers/net/tun.c:tun_flow_delete
  - net/core/gen_estimator.c:gen_kill_estimator
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/net_namespace.c:net_assign_generic
  - net/core/dev.c:__netdev_adjacent_dev_remove
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:clean_xps_maps
  - net/core/dev.c:clean_xps_maps
  - net/core/dev.c:remove_xps_queue
  - net/core/dev.c:dev_set_alias
  - net/core/dev_addr_lists.c:dev_mc_flush
  - net/core/dev_addr_lists.c:dev_uc_flush
  - net/core/dev_addr_lists.c:dev_addr_flush
  - net/core/dev_addr_lists.c:__hw_addr_unsync_dev
  - net/core/dev_addr_lists.c:__hw_addr_ref_unsync_dev
  - net/core/dev_addr_lists.c:__hw_addr_del_entry
  - net/core/neighbour.c:neigh_destroy
  - net/core/rtnetlink.c:rtnl_unregister_all
  - net/core/rtnetlink.c:rtnl_unregister
  - net/core/rtnetlink.c:rtnl_register_internal
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/fib_notifier.c:fib_notifier_ops_unregister
  - net/core/net-sysfs.c:rx_queue_release
  - net/core/net-sysfs.c:store_rps_map
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_rules_unregister
  - net/core/fib_rules.c:fib_rules_cleanup_ops
  - net/core/drop_monitor.c:dropmon_net_event
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/netprio_cgroup.c:netprio_device_event
  - net/core/netprio_cgroup.c:extend_netdev_table
  - net/core/lwtunnel.c:lwtstate_free
  - net/core/sock_map.c:sock_map_remove_links
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
  - net/core/devlink.c:devlink_dpipe_table_unregister
  - net/core/bpf_sk_storage.c:bpf_sk_storage_free
  - net/sched/sch_api.c:qdisc_change
  - net/sched/sch_api.c:qdisc_create
  - net/sched/cls_api.c:__tcf_block_put
  - net/sched/cls_api.c:__tcf_chain_put
  - net/sched/cls_api.c:__tcf_chain_put
  - net/sched/cls_api.c:tcf_proto_destroy
  - net/netlink/af_netlink.c:__netlink_change_ngroups
  - net/netlink/af_netlink.c:netlink_release
  - net/ipv4/route.c:find_exception
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_flush_all
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/cipso_ipv4.c:cipso_v4_delopt
  - net/ipv4/cipso_ipv4.c:cipso_v4_req_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_sock_setattr
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_reinsert
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_reinsert
  - net/ipv6/af_inet6.c:inet6_destroy_sock
  - net/ipv6/addrconf.c:inet6_ifa_finish_destroy
  - net/ipv6/addrlabel.c:ip6addrlbl_net_exit
  - net/ipv6/addrlabel.c:ip6addrlbl_net_exit
  - net/ipv6/addrlabel.c:ip6addrlbl_net_init
  - net/ipv6/addrlabel.c:ip6addrlbl_net_init
  - net/ipv6/addrlabel.c:ip6addrlbl_del
  - net/ipv6/addrlabel.c:__ip6addrlbl_add
  - net/ipv6/ipv6_sockglue.c:ipv6_set_opt_hdr
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:fl6_free_socklist
  - net/ipv6/calipso.c:calipso_req_delattr
  - net/ipv6/calipso.c:calipso_req_setattr
  - net/ipv6/calipso.c:calipso_sock_delattr
  - net/ipv6/calipso.c:calipso_sock_setattr
  - net/ipv6/calipso.c:calipso_sock_getattr
  - net/ipv6/calipso.c:calipso_opt_update
  - net/ipv6/calipso.c:calipso_opt_update
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_free_hi
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove_addr6
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove_addr4
  - net/mptcp/protocol.c:__mptcp_close_ssk
  - net/mptcp/subflow.c:subflow_ulp_release
  - net/mptcp/subflow.c:subflow_drop_ctx
  - net/mptcp/pm_netlink.c:pm_nl_exit_net
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_flush_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr
```
**Symbols:**

```
ffffffff81133230-ffffffff81133448: kvfree_call_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void kvfree_call_rcu(struct callback_head *head, rcu_callback_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811332a0)
Location: kernel/rcu/tree.c:3565
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_free
  - kernel/sched/fair.c:task_numa_group
  - kernel/livepatch/shadow.c:klp_shadow_free_struct
  - kernel/acct.c:acct_process
  - kernel/acct.c:acct_process
  - kernel/acct.c:acct_pin_kill
  - kernel/audit_tree.c:audit_kill_trees
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:prune_tree_thread
  - kernel/audit_tree.c:audit_put_tree
  - kernel/audit_tree.c:audit_trim_trees
  - kernel/audit_tree.c:trim_marked
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:audit_put_chunk
  - kernel/bpf/core.c:bpf_prog_array_free
  - kernel/bpf/lpm_trie.c:trie_delete_elem
  - kernel/bpf/lpm_trie.c:trie_delete_elem
  - kernel/bpf/lpm_trie.c:trie_delete_elem
  - kernel/bpf/lpm_trie.c:trie_update_elem
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
  - kernel/bpf/bpf_local_storage.c:__bpf_selem_unlink_storage
  - kernel/bpf/bpf_local_storage.c:bpf_selem_unlink_storage_nolock
  - kernel/bpf/bpf_task_storage.c:bpf_task_storage_free
  - kernel/bpf/bpf_inode_storage.c:bpf_inode_storage_free
  - kernel/bpf/trampoline.c:__bpf_tramp_image_put_deferred
  - kernel/events/core.c:swevent_hlist_put_cpu
  - kernel/watch_queue.c:__put_watch_queue
  - kernel/watch_queue.c:__put_watch_queue
  - kernel/watch_queue.c:watch_queue_set_filter
  - mm/vmscan.c:expand_one_shrinker_info
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/vmalloc.c:free_vmap_block
  - mm/memcontrol.c:obj_cgroup_release
  - fs/dcache.c:__d_move
  - fs/dcache.c:release_dentry_name_snapshot
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
  - fs/timerfd.c:timerfd_release
  - fs/aio.c:ioctx_add_table
  - fs/io-wq.c:io_wqe_worker
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:posix_acl_xattr_set
  - fs/posix_acl.c:posix_acl_xattr_get
  - fs/posix_acl.c:posix_acl_from_xattr
  - fs/posix_acl.c:__posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_create
  - fs/posix_acl.c:__posix_acl_create
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_cached_acl
  - fs/posix_acl.c:set_cached_acl
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/proc/proc_sysctl.c:proc_sys_evict_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_acl_from_disk
  - fs/fuse/inode.c:fuse_free_conn
  - ipc/sem.c:exit_sem
  - ipc/sem.c:freeary
  - security/keys/keyring.c:key_remove_domain
  - security/selinux/netif.c:sel_netif_netdev_notifier_handler
  - security/selinux/netif.c:sel_netif_flush
  - security/selinux/netnode.c:sel_netnode_flush
  - security/selinux/netnode.c:sel_netnode_sid_slow
  - security/selinux/netport.c:sel_netport_flush
  - security/selinux/netport.c:sel_netport_sid
  - security/selinux/ibpkey.c:sel_ib_pkey_flush
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
  - security/yama/yama_lsm.c:yama_ptracer_add
  - security/yama/yama_lsm.c:yama_relation_cleanup
  - security/device_cgroup.c:__dev_exception_clean
  - security/device_cgroup.c:dev_exception_rm
  - security/landlock/object.c:landlock_put_object
  - drivers/iommu/intel/svm.c:intel_svm_unbind_gpasid
  - drivers/iommu/ioasid.c:ioasid_put
  - drivers/iommu/ioasid.c:ioasid_unregister_allocator
  - drivers/iommu/ioasid.c:default_free
  - drivers/dma-buf/dma-fence.c:dma_fence_free
  - drivers/dma-buf/dma-fence.c:dma_fence_release
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared
  - drivers/dma-buf/dma-resv.c:dma_resv_fini
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext
  - drivers/net/tun.c:tun_flow_flush
  - drivers/net/tun.c:tun_flow_delete
  - net/core/gen_estimator.c:gen_kill_estimator
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/net_namespace.c:ops_init
  - net/core/dev.c:__netdev_adjacent_dev_remove
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:clean_xps_maps
  - net/core/dev.c:clean_xps_maps
  - net/core/dev.c:remove_xps_queue
  - net/core/dev.c:dev_set_alias
  - net/core/dev_addr_lists.c:dev_mc_flush
  - net/core/dev_addr_lists.c:dev_uc_flush
  - net/core/dev_addr_lists.c:dev_addr_flush
  - net/core/dev_addr_lists.c:__hw_addr_unsync_dev
  - net/core/dev_addr_lists.c:__hw_addr_ref_unsync_dev
  - net/core/dev_addr_lists.c:__hw_addr_del_entry
  - net/core/neighbour.c:neigh_destroy
  - net/core/rtnetlink.c:rtnl_unregister_all
  - net/core/rtnetlink.c:rtnl_unregister
  - net/core/rtnetlink.c:rtnl_register_internal
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/fib_notifier.c:fib_notifier_ops_unregister
  - net/core/net-sysfs.c:rx_queue_release
  - net/core/net-sysfs.c:store_rps_map
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_rules_unregister
  - net/core/fib_rules.c:fib_rules_unregister
  - net/core/drop_monitor.c:dropmon_net_event
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/netprio_cgroup.c:netprio_device_event
  - net/core/netprio_cgroup.c:extend_netdev_table
  - net/core/lwtunnel.c:lwtstate_free
  - net/core/devlink.c:devlink_dpipe_table_unregister
  - net/core/sock_map.c:sock_map_remove_links
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
  - net/core/bpf_sk_storage.c:bpf_sk_storage_free
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_create
  - net/sched/cls_api.c:__tcf_block_put
  - net/sched/cls_api.c:__tcf_chain_put
  - net/sched/cls_api.c:__tcf_chain_put
  - net/sched/cls_api.c:tcf_proto_destroy
  - net/netlink/af_netlink.c:__netlink_change_ngroups
  - net/netlink/af_netlink.c:netlink_release
  - net/ipv4/route.c:find_exception
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_flush_all
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/cipso_ipv4.c:cipso_v4_delopt
  - net/ipv4/cipso_ipv4.c:cipso_v4_req_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_sock_setattr
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_merge
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_merge
  - net/ipv6/af_inet6.c:inet6_destroy_sock
  - net/ipv6/addrconf.c:inet6_ifa_finish_destroy
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_net_exit
  - net/ipv6/addrlabel.c:ip6addrlbl_net_exit
  - net/ipv6/addrlabel.c:ip6addrlbl_net_init
  - net/ipv6/addrlabel.c:ip6addrlbl_net_init
  - net/ipv6/addrlabel.c:ip6addrlbl_add
  - net/ipv6/ipv6_sockglue.c:ipv6_set_opt_hdr
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/mcast.c:ipv6_mc_destroy_dev
  - net/ipv6/mcast.c:ipv6_mc_destroy_dev
  - net/ipv6/mcast.c:sf_setstate
  - net/ipv6/mcast.c:ip6_mc_del1_src
  - net/ipv6/mcast.c:mld_send_cr
  - net/ipv6/mcast.c:mld_send_cr
  - net/ipv6/mcast.c:mld_send_cr
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:__ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_dev_mc_dec
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:mld_del_delrec
  - net/ipv6/mcast.c:mld_del_delrec
  - net/ipv6/mcast.c:mld_del_delrec
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:fl6_free_socklist
  - net/ipv6/calipso.c:calipso_req_delattr
  - net/ipv6/calipso.c:calipso_req_setattr
  - net/ipv6/calipso.c:calipso_sock_delattr
  - net/ipv6/calipso.c:calipso_sock_setattr
  - net/ipv6/calipso.c:calipso_sock_getattr
  - net/ipv6/calipso.c:calipso_opt_update
  - net/ipv6/calipso.c:calipso_opt_update
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_free_hi
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/mptcp/protocol.c:__mptcp_close_ssk
  - net/mptcp/subflow.c:subflow_ulp_release
  - net/mptcp/subflow.c:subflow_drop_ctx
```
**Symbols:**

```
ffffffff811332a0-ffffffff81133547: kvfree_call_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void kvfree_call_rcu(struct callback_head *head, rcu_callback_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:3522
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_free
  - kernel/sched/fair.c:task_numa_group
  - kernel/livepatch/shadow.c:klp_shadow_free_struct
  - kernel/acct.c:acct_process
  - kernel/acct.c:acct_process
  - kernel/acct.c:acct_pin_kill
  - kernel/audit_tree.c:audit_kill_trees
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:prune_tree_thread
  - kernel/audit_tree.c:audit_put_tree
  - kernel/audit_tree.c:audit_trim_trees
  - kernel/audit_tree.c:trim_marked
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:audit_put_chunk
  - kernel/bpf/core.c:bpf_prog_array_free
  - kernel/bpf/lpm_trie.c:trie_delete_elem
  - kernel/bpf/lpm_trie.c:trie_delete_elem
  - kernel/bpf/lpm_trie.c:trie_delete_elem
  - kernel/bpf/lpm_trie.c:trie_update_elem
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
  - kernel/bpf/bpf_local_storage.c:__bpf_selem_unlink_storage
  - kernel/bpf/bpf_local_storage.c:bpf_selem_unlink_storage_nolock
  - kernel/bpf/bpf_task_storage.c:bpf_task_storage_free
  - kernel/bpf/bpf_inode_storage.c:bpf_inode_storage_free
  - kernel/bpf/trampoline.c:__bpf_tramp_image_put_deferred
  - kernel/events/core.c:swevent_hlist_put_cpu
  - kernel/watch_queue.c:__put_watch_queue
  - kernel/watch_queue.c:__put_watch_queue
  - kernel/watch_queue.c:watch_queue_set_filter
  - mm/vmscan.c:expand_one_shrinker_info
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/vmalloc.c:free_vmap_block
  - mm/memcontrol.c:obj_cgroup_release
  - fs/dcache.c:__d_move
  - fs/dcache.c:release_dentry_name_snapshot
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
  - fs/timerfd.c:timerfd_release
  - fs/aio.c:ioctx_add_table
  - fs/io-wq.c:io_wqe_worker
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:posix_acl_xattr_set
  - fs/posix_acl.c:posix_acl_xattr_get
  - fs/posix_acl.c:posix_acl_from_xattr
  - fs/posix_acl.c:__posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_create
  - fs/posix_acl.c:__posix_acl_create
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_cached_acl
  - fs/posix_acl.c:set_cached_acl
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/proc/proc_sysctl.c:proc_sys_evict_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_acl_from_disk
  - fs/fuse/inode.c:fuse_free_conn
  - fs/fuse/inode.c:fuse_sync_fs_writes
  - ipc/sem.c:exit_sem
  - ipc/sem.c:freeary
  - security/keys/keyring.c:key_remove_domain
  - security/selinux/netif.c:sel_netif_netdev_notifier_handler
  - security/selinux/netif.c:sel_netif_flush
  - security/selinux/netnode.c:sel_netnode_flush
  - security/selinux/netnode.c:sel_netnode_sid
  - security/selinux/netport.c:sel_netport_flush
  - security/selinux/netport.c:sel_netport_sid
  - security/selinux/ibpkey.c:sel_ib_pkey_flush
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
  - security/yama/yama_lsm.c:yama_ptracer_add
  - security/yama/yama_lsm.c:yama_relation_cleanup
  - security/device_cgroup.c:__dev_exception_clean
  - security/device_cgroup.c:dev_exception_rm
  - security/landlock/object.c:landlock_put_object
  - security/integrity/evm/evm_main.c:evm_xattr_change
  - drivers/iommu/intel/svm.c:intel_svm_unbind_gpasid
  - drivers/iommu/ioasid.c:ioasid_put
  - drivers/iommu/ioasid.c:ioasid_unregister_allocator
  - drivers/iommu/ioasid.c:default_free
  - drivers/dma-buf/dma-fence.c:dma_fence_free
  - drivers/dma-buf/dma-fence.c:dma_fence_release
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared
  - drivers/dma-buf/dma-resv.c:dma_resv_fini
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext
  - drivers/net/tun.c:tun_flow_flush
  - drivers/net/tun.c:tun_flow_delete
  - net/core/gen_estimator.c:gen_kill_estimator
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/net_namespace.c:ops_init
  - net/core/dev.c:__netdev_adjacent_dev_remove
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:clean_xps_maps
  - net/core/dev.c:clean_xps_maps
  - net/core/dev.c:remove_xps_queue
  - net/core/dev.c:dev_set_alias
  - net/core/dev_addr_lists.c:dev_mc_flush
  - net/core/dev_addr_lists.c:dev_uc_flush
  - net/core/dev_addr_lists.c:dev_addr_flush
  - net/core/dev_addr_lists.c:__hw_addr_unsync_dev
  - net/core/dev_addr_lists.c:__hw_addr_del_entry
  - net/core/neighbour.c:neigh_destroy
  - net/core/rtnetlink.c:rtnl_unregister_all
  - net/core/rtnetlink.c:rtnl_unregister
  - net/core/rtnetlink.c:rtnl_register_internal
  - net/core/sock_reuseport.c:reuseport_grow
  - net/core/fib_notifier.c:fib_notifier_ops_unregister
  - net/core/net-sysfs.c:rx_queue_release
  - net/core/net-sysfs.c:store_rps_map
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_rules_unregister
  - net/core/fib_rules.c:fib_rules_unregister
  - net/core/drop_monitor.c:dropmon_net_event
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/netprio_cgroup.c:netprio_device_event
  - net/core/netprio_cgroup.c:extend_netdev_table
  - net/core/lwtunnel.c:lwtstate_free
  - net/core/devlink.c:devlink_dpipe_table_unregister
  - net/core/sock_map.c:sock_map_remove_links
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
  - net/core/bpf_sk_storage.c:bpf_sk_storage_free
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_create
  - net/sched/cls_api.c:__tcf_block_put
  - net/sched/cls_api.c:__tcf_chain_put
  - net/sched/cls_api.c:__tcf_chain_put
  - net/sched/cls_api.c:tcf_proto_destroy
  - net/netlink/af_netlink.c:__netlink_change_ngroups
  - net/netlink/af_netlink.c:netlink_release
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_flush_all
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/cipso_ipv4.c:cipso_v4_delopt
  - net/ipv4/cipso_ipv4.c:cipso_v4_req_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_sock_setattr
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_merge
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_merge
  - net/ipv6/af_inet6.c:inet6_destroy_sock
  - net/ipv6/addrconf.c:inet6_ifa_finish_destroy
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_net_exit
  - net/ipv6/addrlabel.c:ip6addrlbl_net_exit
  - net/ipv6/addrlabel.c:ip6addrlbl_net_init
  - net/ipv6/addrlabel.c:ip6addrlbl_net_init
  - net/ipv6/addrlabel.c:ip6addrlbl_add
  - net/ipv6/ipv6_sockglue.c:ipv6_set_opt_hdr
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/mcast.c:ipv6_mc_destroy_dev
  - net/ipv6/mcast.c:ipv6_mc_destroy_dev
  - net/ipv6/mcast.c:sf_setstate
  - net/ipv6/mcast.c:ip6_mc_del1_src
  - net/ipv6/mcast.c:mld_send_cr
  - net/ipv6/mcast.c:mld_send_cr
  - net/ipv6/mcast.c:mld_send_cr
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:__ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_dev_mc_dec
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:mld_del_delrec
  - net/ipv6/mcast.c:mld_del_delrec
  - net/ipv6/mcast.c:mld_del_delrec
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:fl6_free_socklist
  - net/ipv6/ioam6.c:ioam6_genl_delsc
  - net/ipv6/ioam6.c:ioam6_genl_delns
  - net/ipv6/calipso.c:calipso_req_delattr
  - net/ipv6/calipso.c:calipso_req_setattr
  - net/ipv6/calipso.c:calipso_sock_delattr
  - net/ipv6/calipso.c:calipso_sock_setattr
  - net/ipv6/calipso.c:calipso_sock_getattr
  - net/ipv6/calipso.c:calipso_opt_update
  - net/ipv6/calipso.c:calipso_opt_update
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_free_hi
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/mptcp/protocol.c:__mptcp_close_ssk
  - net/mptcp/subflow.c:subflow_ulp_release
  - net/mptcp/subflow.c:subflow_drop_ctx
```
**Symbols:**

```
ffffffff81caf486-ffffffff81caf4b5: kvfree_call_rcu.cold (STB_LOCAL)
ffffffff81155570-ffffffff81155956: kvfree_call_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void kvfree_call_rcu(struct callback_head *head, rcu_callback_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:3616
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_free
  - kernel/sched/fair.c:task_numa_group
  - kernel/acct.c:acct_process
  - kernel/acct.c:acct_process
  - kernel/acct.c:acct_pin_kill
  - kernel/audit_tree.c:audit_kill_trees
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:prune_tree_thread
  - kernel/audit_tree.c:audit_put_tree
  - kernel/audit_tree.c:audit_trim_trees
  - kernel/audit_tree.c:trim_marked
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:audit_put_chunk
  - kernel/trace/trace_probe.c:trace_probe_remove_file
  - kernel/bpf/core.c:bpf_prog_array_free
  - kernel/bpf/lpm_trie.c:trie_delete_elem
  - kernel/bpf/lpm_trie.c:trie_delete_elem
  - kernel/bpf/lpm_trie.c:trie_delete_elem
  - kernel/bpf/lpm_trie.c:trie_update_elem
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
  - kernel/bpf/bpf_local_storage.c:__bpf_selem_unlink_storage
  - kernel/bpf/bpf_local_storage.c:bpf_selem_unlink_storage_nolock
  - kernel/bpf/bpf_task_storage.c:bpf_task_storage_free
  - kernel/bpf/bpf_inode_storage.c:bpf_inode_storage_free
  - kernel/events/core.c:swevent_hlist_put_cpu
  - kernel/watch_queue.c:__put_watch_queue
  - kernel/watch_queue.c:__put_watch_queue
  - kernel/watch_queue.c:watch_queue_set_filter
  - mm/vmscan.c:expand_one_shrinker_info
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/list_lru.c:memcg_reparent_list_lrus
  - mm/memcontrol.c:obj_cgroup_release
  - fs/dcache.c:__d_move
  - fs/dcache.c:release_dentry_name_snapshot
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
  - fs/timerfd.c:timerfd_release
  - fs/aio.c:ioctx_add_table
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:posix_acl_xattr_set
  - fs/posix_acl.c:posix_acl_xattr_get
  - fs/posix_acl.c:posix_acl_from_xattr
  - fs/posix_acl.c:posix_acl_create
  - fs/posix_acl.c:posix_acl_create
  - fs/posix_acl.c:posix_acl_create
  - fs/posix_acl.c:posix_acl_create
  - fs/posix_acl.c:posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_create
  - fs/posix_acl.c:__posix_acl_create
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_cached_acl
  - fs/posix_acl.c:set_cached_acl
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/proc/proc_sysctl.c:proc_sys_evict_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/super.c:ext4_apply_options
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_acl_from_disk
  - fs/fuse/inode.c:fuse_sync_fs_writes
  - ipc/sem.c:exit_sem
  - ipc/sem.c:freeary
  - security/keys/keyring.c:key_remove_domain
  - security/selinux/netif.c:sel_netif_netdev_notifier_handler
  - security/selinux/netif.c:sel_netif_flush
  - security/selinux/netnode.c:sel_netnode_flush
  - security/selinux/netnode.c:sel_netnode_sid
  - security/selinux/netport.c:sel_netport_flush
  - security/selinux/netport.c:sel_netport_sid
  - security/selinux/ss/sidtab.c:sidtab_sid2str_put
  - security/selinux/ibpkey.c:sel_ib_pkey_flush
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
  - security/yama/yama_lsm.c:yama_ptracer_add
  - security/yama/yama_lsm.c:yama_relation_cleanup
  - security/device_cgroup.c:__dev_exception_clean
  - security/device_cgroup.c:dev_exception_rm
  - security/landlock/object.c:landlock_put_object
  - security/integrity/evm/evm_main.c:evm_xattr_change
  - io_uring/io-wq.c:io_wqe_worker
  - drivers/iommu/ioasid.c:ioasid_free
  - drivers/iommu/ioasid.c:ioasid_unregister_allocator
  - drivers/iommu/ioasid.c:default_free
  - drivers/dma-buf/dma-fence.c:dma_fence_release
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_fences
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext
  - drivers/net/tun.c:tun_flow_flush
  - drivers/net/tun.c:tun_flow_delete
  - net/core/gen_estimator.c:gen_kill_estimator
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/net_namespace.c:ops_init
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/dev.c:__netdev_adjacent_dev_remove
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:clean_xps_maps
  - net/core/dev.c:clean_xps_maps
  - net/core/dev.c:clean_xps_maps
  - net/core/dev.c:remove_xps_queue
  - net/core/dev.c:dev_set_alias
  - net/core/dev_addr_lists.c:dev_mc_flush
  - net/core/dev_addr_lists.c:dev_uc_flush
  - net/core/dev_addr_lists.c:dev_addr_flush
  - net/core/dev_addr_lists.c:__hw_addr_unsync_dev
  - net/core/dev_addr_lists.c:__hw_addr_del_entry
  - net/core/neighbour.c:neigh_destroy
  - net/core/rtnetlink.c:rtnl_unregister_all
  - net/core/rtnetlink.c:rtnl_unregister
  - net/core/rtnetlink.c:rtnl_register_internal
  - net/core/sock_reuseport.c:reuseport_grow
  - net/core/net-sysfs.c:rx_queue_release
  - net/core/net-sysfs.c:store_rps_map
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/drop_monitor.c:dropmon_net_event
  - net/core/netprio_cgroup.c:netprio_device_event
  - net/core/netprio_cgroup.c:extend_netdev_table
  - net/core/lwtunnel.c:lwtstate_free
  - net/core/devlink.c:devlink_dpipe_table_unregister
  - net/core/sock_map.c:sock_map_remove_links
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
  - net/core/bpf_sk_storage.c:bpf_sk_storage_free
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/cls_api.c:__tcf_block_put
  - net/sched/cls_api.c:__tcf_chain_put
  - net/sched/cls_api.c:__tcf_chain_put
  - net/sched/cls_api.c:tcf_proto_destroy
  - net/netlink/af_netlink.c:__netlink_change_ngroups
  - net/netlink/af_netlink.c:netlink_release
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_flush_all
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/cipso_ipv4.c:cipso_v4_delopt
  - net/ipv4/cipso_ipv4.c:cipso_v4_req_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_sock_setattr
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_merge
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_merge
  - net/ipv6/af_inet6.c:inet6_destroy_sock
  - net/ipv6/addrconf.c:inet6_ifa_finish_destroy
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_net_exit
  - net/ipv6/addrlabel.c:ip6addrlbl_net_exit
  - net/ipv6/addrlabel.c:ip6addrlbl_net_init
  - net/ipv6/addrlabel.c:ip6addrlbl_net_init
  - net/ipv6/addrlabel.c:__ip6addrlbl_add
  - net/ipv6/ipv6_sockglue.c:ipv6_set_opt_hdr
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/mcast.c:ipv6_mc_destroy_dev
  - net/ipv6/mcast.c:ipv6_mc_destroy_dev
  - net/ipv6/mcast.c:sf_setstate
  - net/ipv6/mcast.c:ip6_mc_del1_src
  - net/ipv6/mcast.c:mld_send_cr
  - net/ipv6/mcast.c:mld_send_cr
  - net/ipv6/mcast.c:mld_send_cr
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:__ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_dev_mc_dec
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:mld_del_delrec
  - net/ipv6/mcast.c:mld_del_delrec
  - net/ipv6/mcast.c:mld_del_delrec
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:fl6_free_socklist
  - net/ipv6/ioam6.c:ioam6_genl_delsc
  - net/ipv6/ioam6.c:ioam6_genl_delns
  - net/ipv6/calipso.c:calipso_req_delattr
  - net/ipv6/calipso.c:calipso_req_setattr
  - net/ipv6/calipso.c:calipso_sock_delattr
  - net/ipv6/calipso.c:calipso_sock_setattr
  - net/ipv6/calipso.c:calipso_sock_getattr
  - net/ipv6/calipso.c:calipso_opt_update
  - net/ipv6/calipso.c:calipso_opt_update
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_free_hi
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/mptcp/protocol.c:__mptcp_close_ssk
  - net/mptcp/subflow.c:subflow_ulp_release
  - net/mptcp/subflow.c:subflow_drop_ctx
```
**Symbols:**

```
ffffffff81e60237-ffffffff81e60269: kvfree_call_rcu.cold (STB_LOCAL)
ffffffff8117f0f0-ffffffff8117f4c9: kvfree_call_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void kvfree_call_rcu(struct callback_head *head, rcu_callback_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:3345
Inline: False
Direct callers:
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:do_set_cpus_allowed
  - kernel/sched/fair.c:task_numa_free
  - kernel/sched/fair.c:task_numa_group
  - kernel/acct.c:acct_process
  - kernel/acct.c:acct_process
  - kernel/acct.c:acct_pin_kill
  - kernel/audit_tree.c:audit_kill_trees
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:prune_tree_thread
  - kernel/audit_tree.c:audit_put_tree
  - kernel/audit_tree.c:audit_trim_trees
  - kernel/audit_tree.c:trim_marked
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:audit_put_chunk
  - kernel/trace/trace_probe.c:trace_probe_remove_file
  - kernel/bpf/core.c:bpf_prog_array_free
  - kernel/bpf/lpm_trie.c:trie_delete_elem
  - kernel/bpf/lpm_trie.c:trie_delete_elem
  - kernel/bpf/lpm_trie.c:trie_delete_elem
  - kernel/bpf/lpm_trie.c:trie_update_elem
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
  - kernel/bpf/bpf_local_storage.c:__bpf_selem_unlink_storage
  - kernel/bpf/bpf_local_storage.c:bpf_selem_unlink_storage_nolock
  - kernel/bpf/bpf_task_storage.c:bpf_task_storage_free
  - kernel/bpf/bpf_inode_storage.c:bpf_inode_storage_free
  - kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_free
  - kernel/events/core.c:swevent_hlist_put_cpu
  - kernel/watch_queue.c:__put_watch_queue
  - kernel/watch_queue.c:__put_watch_queue
  - kernel/watch_queue.c:watch_queue_set_filter
  - mm/vmscan.c:expand_one_shrinker_info
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/list_lru.c:memcg_reparent_list_lrus
  - mm/memcontrol.c:obj_cgroup_release
  - fs/dcache.c:copy_name
  - fs/dcache.c:release_dentry_name_snapshot
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
  - fs/timerfd.c:timerfd_release
  - fs/aio.c:ioctx_add_table
  - fs/posix_acl.c:do_get_acl
  - fs/posix_acl.c:do_set_acl
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:posix_acl_from_xattr
  - fs/posix_acl.c:posix_acl_create
  - fs/posix_acl.c:posix_acl_create
  - fs/posix_acl.c:posix_acl_create
  - fs/posix_acl.c:posix_acl_create
  - fs/posix_acl.c:posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_create
  - fs/posix_acl.c:__posix_acl_create
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_cached_acl
  - fs/posix_acl.c:set_cached_acl
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/proc/proc_sysctl.c:proc_sys_evict_inode
  - fs/kernfs/file.c:kernfs_unlink_open_file
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/super.c:ext4_apply_options
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_acl_from_disk
  - fs/fuse/inode.c:fuse_sync_fs_writes
  - ipc/sem.c:exit_sem
  - ipc/sem.c:freeary
  - security/keys/keyring.c:key_remove_domain
  - security/selinux/netif.c:sel_netif_netdev_notifier_handler
  - security/selinux/netif.c:sel_netif_flush
  - security/selinux/netnode.c:sel_netnode_flush
  - security/selinux/netnode.c:sel_netnode_sid
  - security/selinux/netport.c:sel_netport_flush
  - security/selinux/netport.c:sel_netport_sid
  - security/selinux/ss/sidtab.c:sidtab_sid2str_put
  - security/selinux/ibpkey.c:sel_ib_pkey_flush
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
  - security/yama/yama_lsm.c:yama_ptracer_add
  - security/yama/yama_lsm.c:yama_relation_cleanup
  - security/device_cgroup.c:__dev_exception_clean
  - security/device_cgroup.c:dev_exception_rm
  - security/landlock/object.c:landlock_put_object
  - io_uring/io-wq.c:io_wqe_worker
  - drivers/iommu/ioasid.c:ioasid_free
  - drivers/iommu/ioasid.c:ioasid_unregister_allocator
  - drivers/iommu/ioasid.c:default_free
  - drivers/dma-buf/dma-fence.c:dma_fence_release
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_fences
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release
  - drivers/net/tun.c:tun_flow_flush
  - drivers/net/tun.c:tun_flow_delete
  - net/core/gen_estimator.c:gen_kill_estimator
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/net_namespace.c:net_assign_generic
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/dev.c:__netdev_adjacent_dev_remove
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:clean_xps_maps
  - net/core/dev.c:clean_xps_maps
  - net/core/dev.c:clean_xps_maps
  - net/core/dev.c:remove_xps_queue
  - net/core/dev.c:dev_set_alias
  - net/core/dev_addr_lists.c:dev_mc_flush
  - net/core/dev_addr_lists.c:dev_uc_flush
  - net/core/dev_addr_lists.c:dev_addr_flush
  - net/core/dev_addr_lists.c:__hw_addr_unsync_dev
  - net/core/dev_addr_lists.c:__hw_addr_del_entry
  - net/core/neighbour.c:neigh_destroy
  - net/core/rtnetlink.c:rtnl_unregister_all
  - net/core/rtnetlink.c:rtnl_unregister
  - net/core/rtnetlink.c:rtnl_register_internal
  - net/core/sock_reuseport.c:reuseport_grow
  - net/core/net-sysfs.c:rx_queue_release
  - net/core/net-sysfs.c:store_rps_map
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/drop_monitor.c:dropmon_net_event
  - net/core/netprio_cgroup.c:netprio_device_event
  - net/core/netprio_cgroup.c:extend_netdev_table
  - net/core/lwtunnel.c:lwtstate_free
  - net/core/devlink.c:devl_dpipe_table_unregister
  - net/core/sock_map.c:sock_map_remove_links
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
  - net/core/bpf_sk_storage.c:bpf_sk_storage_free
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_create
  - net/sched/cls_api.c:__tcf_block_put
  - net/sched/cls_api.c:__tcf_chain_put
  - net/sched/cls_api.c:__tcf_chain_put
  - net/sched/cls_api.c:tcf_proto_destroy
  - net/netlink/af_netlink.c:__netlink_change_ngroups
  - net/netlink/af_netlink.c:netlink_release
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
  - net/ipv4/tcp_ipv4.c:tcp_md5_key_copy
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_add
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_flush_all
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/cipso_ipv4.c:cipso_v4_delopt
  - net/ipv4/cipso_ipv4.c:cipso_v4_req_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_sock_setattr
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_merge
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_merge
  - net/ipv6/af_inet6.c:inet6_cleanup_sock
  - net/ipv6/addrconf.c:inet6_ifa_finish_destroy
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_net_exit
  - net/ipv6/addrlabel.c:ip6addrlbl_net_exit
  - net/ipv6/addrlabel.c:ip6addrlbl_net_init
  - net/ipv6/addrlabel.c:ip6addrlbl_net_init
  - net/ipv6/addrlabel.c:__ip6addrlbl_add
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/ipv6_sockglue.c:ipv6_set_opt_hdr
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/mcast.c:ipv6_mc_destroy_dev
  - net/ipv6/mcast.c:ipv6_mc_destroy_dev
  - net/ipv6/mcast.c:sf_setstate
  - net/ipv6/mcast.c:ip6_mc_del1_src
  - net/ipv6/mcast.c:mld_send_cr
  - net/ipv6/mcast.c:mld_send_cr
  - net/ipv6/mcast.c:mld_send_cr
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:__ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_dev_mc_dec
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:mld_del_delrec
  - net/ipv6/mcast.c:mld_del_delrec
  - net/ipv6/mcast.c:mld_del_delrec
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:fl6_free_socklist
  - net/ipv6/ioam6.c:ioam6_genl_delsc
  - net/ipv6/ioam6.c:ioam6_genl_delns
  - net/ipv6/calipso.c:calipso_req_delattr
  - net/ipv6/calipso.c:calipso_req_setattr
  - net/ipv6/calipso.c:calipso_sock_delattr
  - net/ipv6/calipso.c:calipso_sock_setattr
  - net/ipv6/calipso.c:calipso_sock_getattr
  - net/ipv6/calipso.c:calipso_opt_update
  - net/ipv6/calipso.c:calipso_opt_update
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_free_hi
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/mptcp/protocol.c:__mptcp_close_ssk
  - net/mptcp/subflow.c:subflow_ulp_release
  - net/mptcp/subflow.c:subflow_drop_ctx
```
**Symbols:**

```
ffffffff8205a2ae-ffffffff8205a2c3: kvfree_call_rcu.cold (STB_LOCAL)
ffffffff811b8790-ffffffff811b8b75: kvfree_call_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void kvfree_call_rcu(struct callback_head *head, void *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:3342
Inline: False
Direct callers:
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:do_set_cpus_allowed
  - kernel/sched/fair.c:task_numa_free
  - kernel/sched/fair.c:task_numa_group
  - kernel/acct.c:acct_process
  - kernel/acct.c:acct_process
  - kernel/acct.c:acct_pin_kill
  - kernel/audit_tree.c:audit_kill_trees
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:prune_tree_thread
  - kernel/audit_tree.c:audit_put_tree
  - kernel/audit_tree.c:audit_trim_trees
  - kernel/audit_tree.c:trim_marked
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:audit_put_chunk
  - kernel/trace/trace_osnoise.c:osnoise_unregister_instance
  - kernel/trace/trace_events_user.c:user_events_ioctl_reg
  - kernel/trace/trace_probe.c:trace_probe_remove_file
  - kernel/bpf/core.c:bpf_prog_array_free
  - kernel/bpf/lpm_trie.c:trie_delete_elem
  - kernel/bpf/lpm_trie.c:trie_delete_elem
  - kernel/bpf/lpm_trie.c:trie_delete_elem
  - kernel/bpf/lpm_trie.c:trie_update_elem
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
  - kernel/bpf/trampoline.c:bpf_trampoline_update
  - kernel/bpf/trampoline.c:__bpf_tramp_image_put_deferred
  - kernel/events/core.c:swevent_hlist_put_cpu
  - kernel/watch_queue.c:__put_watch_queue
  - kernel/watch_queue.c:__put_watch_queue
  - kernel/watch_queue.c:watch_queue_set_filter
  - mm/vmscan.c:expand_one_shrinker_info
  - mm/list_lru.c:memcg_reparent_list_lrus
  - mm/vmalloc.c:free_vmap_block
  - mm/memcontrol.c:obj_cgroup_release
  - fs/dcache.c:copy_name
  - fs/dcache.c:release_dentry_name_snapshot
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
  - fs/timerfd.c:timerfd_release
  - fs/aio.c:ioctx_add_table
  - fs/posix_acl.c:do_get_acl
  - fs/posix_acl.c:do_set_acl
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:posix_acl_from_xattr
  - fs/posix_acl.c:posix_acl_create
  - fs/posix_acl.c:posix_acl_create
  - fs/posix_acl.c:posix_acl_create
  - fs/posix_acl.c:posix_acl_create
  - fs/posix_acl.c:posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_create
  - fs/posix_acl.c:__posix_acl_create
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_cached_acl
  - fs/posix_acl.c:set_cached_acl
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/proc/proc_sysctl.c:proc_sys_evict_inode
  - fs/kernfs/file.c:kernfs_unlink_open_file
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/super.c:ext4_apply_options
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_acl_from_disk
  - fs/fuse/inode.c:fuse_sync_fs_writes
  - ipc/sem.c:exit_sem
  - ipc/sem.c:freeary
  - security/keys/keyring.c:key_remove_domain
  - security/selinux/netif.c:sel_netif_netdev_notifier_handler
  - security/selinux/netif.c:sel_netif_flush
  - security/selinux/netnode.c:sel_netnode_flush
  - security/selinux/netnode.c:sel_netnode_sid
  - security/selinux/netport.c:sel_netport_flush
  - security/selinux/netport.c:sel_netport_sid
  - security/selinux/ss/sidtab.c:sidtab_sid2str_put
  - security/selinux/ibpkey.c:sel_ib_pkey_flush
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
  - security/yama/yama_lsm.c:yama_ptracer_add
  - security/yama/yama_lsm.c:yama_relation_cleanup
  - security/device_cgroup.c:__dev_exception_clean
  - security/device_cgroup.c:dev_exception_rm
  - security/landlock/object.c:landlock_put_object
  - io_uring/io-wq.c:io_wq_worker
  - drivers/dma-buf/dma-fence.c:dma_fence_release
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_fences
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release
  - drivers/net/tun.c:tun_flow_flush
  - drivers/net/tun.c:tun_flow_delete
  - net/core/gen_estimator.c:gen_kill_estimator
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/net_namespace.c:net_assign_generic
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/dev.c:__netdev_adjacent_dev_remove
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:clean_xps_maps
  - net/core/dev.c:clean_xps_maps
  - net/core/dev.c:clean_xps_maps
  - net/core/dev.c:remove_xps_queue
  - net/core/dev.c:dev_set_alias
  - net/core/dev_addr_lists.c:dev_mc_flush
  - net/core/dev_addr_lists.c:dev_uc_flush
  - net/core/dev_addr_lists.c:dev_addr_flush
  - net/core/dev_addr_lists.c:__hw_addr_unsync_dev
  - net/core/dev_addr_lists.c:__hw_addr_del_entry
  - net/core/neighbour.c:neigh_destroy
  - net/core/rtnetlink.c:rtnl_unregister_all
  - net/core/rtnetlink.c:rtnl_unregister
  - net/core/rtnetlink.c:rtnl_register_internal
  - net/core/sock_reuseport.c:reuseport_grow
  - net/core/net-sysfs.c:rx_queue_release
  - net/core/net-sysfs.c:netdev_rx_queue_set_rps_mask
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/drop_monitor.c:dropmon_net_event
  - net/core/netprio_cgroup.c:netprio_device_event
  - net/core/netprio_cgroup.c:extend_netdev_table
  - net/core/lwtunnel.c:lwtstate_free
  - net/core/sock_map.c:sock_map_remove_links
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_create
  - net/sched/cls_api.c:tcf_exts_destroy
  - net/sched/cls_api.c:__tcf_block_put
  - net/sched/cls_api.c:__tcf_chain_put
  - net/sched/cls_api.c:__tcf_chain_put
  - net/sched/cls_api.c:tcf_proto_destroy
  - net/netlink/af_netlink.c:__netlink_change_ngroups
  - net/netlink/af_netlink.c:netlink_release
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
  - net/ipv4/tcp_ipv4.c:tcp_md5_key_copy
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_add
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_flush_all
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/cipso_ipv4.c:cipso_v4_delopt
  - net/ipv4/cipso_ipv4.c:cipso_v4_req_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_sock_setattr
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_merge
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_merge
  - net/ipv6/af_inet6.c:inet6_cleanup_sock
  - net/ipv6/addrconf.c:inet6_ifa_finish_destroy
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_net_exit
  - net/ipv6/addrlabel.c:ip6addrlbl_net_exit
  - net/ipv6/addrlabel.c:ip6addrlbl_net_init
  - net/ipv6/addrlabel.c:ip6addrlbl_net_init
  - net/ipv6/addrlabel.c:__ip6addrlbl_add
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/ipv6_sockglue.c:ipv6_set_opt_hdr
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/mcast.c:ipv6_mc_destroy_dev
  - net/ipv6/mcast.c:ipv6_mc_destroy_dev
  - net/ipv6/mcast.c:sf_setstate
  - net/ipv6/mcast.c:ip6_mc_del1_src
  - net/ipv6/mcast.c:mld_send_cr
  - net/ipv6/mcast.c:mld_send_cr
  - net/ipv6/mcast.c:mld_send_cr
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:__ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_dev_mc_dec
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:mld_del_delrec
  - net/ipv6/mcast.c:mld_del_delrec
  - net/ipv6/mcast.c:mld_del_delrec
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:fl6_free_socklist
  - net/ipv6/ioam6.c:ioam6_genl_delsc
  - net/ipv6/ioam6.c:ioam6_genl_delns
  - net/ipv6/calipso.c:calipso_req_delattr
  - net/ipv6/calipso.c:calipso_req_setattr
  - net/ipv6/calipso.c:calipso_sock_delattr
  - net/ipv6/calipso.c:calipso_sock_setattr
  - net/ipv6/calipso.c:calipso_sock_getattr
  - net/ipv6/calipso.c:calipso_opt_update
  - net/ipv6/calipso.c:calipso_opt_update
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_free_hi
  - net/devlink/leftover.c:devl_dpipe_table_unregister
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/mptcp/protocol.c:__mptcp_close_ssk
  - net/mptcp/subflow.c:subflow_ulp_release
  - net/mptcp/subflow.c:mptcp_subflow_drop_ctx
```
**Symbols:**

```
ffffffff820d8ac7-ffffffff820d8adc: kvfree_call_rcu.cold (STB_LOCAL)
ffffffff811ca5a0-ffffffff811ca9d8: kvfree_call_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void kvfree_call_rcu(struct callback_head *head, void *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:3413
Inline: False
Direct callers:
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:do_set_cpus_allowed
  - kernel/sched/fair.c:task_numa_free
  - kernel/sched/fair.c:task_numa_group
  - kernel/acct.c:acct_process
  - kernel/acct.c:acct_process
  - kernel/acct.c:acct_pin_kill
  - kernel/cgroup/cgroup.c:cgroup_destroy_root
  - kernel/audit_tree.c:audit_kill_trees
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:prune_tree_thread
  - kernel/audit_tree.c:audit_put_tree
  - kernel/audit_tree.c:audit_trim_trees
  - kernel/audit_tree.c:trim_marked
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:audit_put_chunk
  - kernel/trace/trace_osnoise.c:osnoise_unregister_instance
  - kernel/trace/trace_events_user.c:user_events_ioctl_reg
  - kernel/trace/trace_probe.c:trace_probe_remove_file
  - kernel/bpf/core.c:bpf_prog_array_free
  - kernel/bpf/helpers.c:bpf_timer_cancel_and_free
  - kernel/bpf/lpm_trie.c:trie_delete_elem
  - kernel/bpf/lpm_trie.c:trie_delete_elem
  - kernel/bpf/lpm_trie.c:trie_delete_elem
  - kernel/bpf/lpm_trie.c:trie_update_elem
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
  - kernel/bpf/tcx.c:tcx_link_release
  - kernel/bpf/tcx.c:tcx_link_prog_attach
  - kernel/bpf/tcx.c:tcx_uninstall
  - kernel/bpf/tcx.c:tcx_prog_detach
  - kernel/bpf/tcx.c:tcx_prog_attach
  - kernel/events/core.c:swevent_hlist_put_cpu
  - kernel/watch_queue.c:__put_watch_queue
  - kernel/watch_queue.c:__put_watch_queue
  - kernel/watch_queue.c:watch_queue_set_filter
  - mm/shrinker.c:expand_one_shrinker_info
  - mm/list_lru.c:memcg_reparent_list_lrus
  - mm/vmalloc.c:free_vmap_block
  - mm/sparse.c:section_deactivate
  - mm/memcontrol.c:obj_cgroup_release
  - fs/dcache.c:copy_name
  - fs/dcache.c:release_dentry_name_snapshot
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
  - fs/timerfd.c:timerfd_release
  - fs/aio.c:ioctx_add_table
  - fs/posix_acl.c:do_get_acl
  - fs/posix_acl.c:do_set_acl
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:posix_acl_from_xattr
  - fs/posix_acl.c:posix_acl_create
  - fs/posix_acl.c:posix_acl_create
  - fs/posix_acl.c:posix_acl_create
  - fs/posix_acl.c:posix_acl_create
  - fs/posix_acl.c:posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_create
  - fs/posix_acl.c:__posix_acl_create
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_cached_acl
  - fs/posix_acl.c:set_cached_acl
  - fs/proc/root.c:proc_kill_sb
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/proc/proc_sysctl.c:proc_sys_evict_inode
  - fs/kernfs/file.c:kernfs_unlink_open_file
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/super.c:ext4_apply_options
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_acl_from_disk
  - fs/fuse/inode.c:fuse_kill_sb_blk
  - fs/fuse/inode.c:fuse_kill_sb_anon
  - fs/fuse/inode.c:fuse_get_tree
  - fs/fuse/inode.c:fuse_get_tree_submount
  - fs/fuse/inode.c:fuse_sync_fs_writes
  - fs/tracefs/event_inode.c:release_ei
  - ipc/sem.c:exit_sem
  - ipc/sem.c:freeary
  - security/keys/keyring.c:key_remove_domain
  - security/selinux/netif.c:sel_netif_netdev_notifier_handler
  - security/selinux/netif.c:sel_netif_flush
  - security/selinux/netnode.c:sel_netnode_flush
  - security/selinux/netnode.c:sel_netnode_sid
  - security/selinux/netport.c:sel_netport_flush
  - security/selinux/netport.c:sel_netport_sid
  - security/selinux/ss/sidtab.c:sidtab_sid2str_put
  - security/selinux/ibpkey.c:sel_ib_pkey_flush
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
  - security/yama/yama_lsm.c:yama_ptracer_add
  - security/yama/yama_lsm.c:yama_relation_cleanup
  - security/device_cgroup.c:__dev_exception_clean
  - security/device_cgroup.c:dev_exception_rm
  - security/landlock/object.c:landlock_put_object
  - io_uring/kbuf.c:io_unregister_pbuf_ring
  - io_uring/kbuf.c:io_register_pbuf_ring
  - io_uring/kbuf.c:io_provide_buffers
  - io_uring/kbuf.c:io_destroy_buffers
  - io_uring/io-wq.c:io_wq_worker
  - drivers/iommu/intel/svm.c:intel_svm_remove_dev_pasid
  - drivers/dma-buf/dma-fence.c:dma_fence_release
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_fences
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release
  - drivers/net/tun.c:tun_flow_flush
  - drivers/net/tun.c:tun_flow_delete
  - drivers/dpll/dpll_core.c:dpll_pin_put
  - net/core/gen_estimator.c:gen_kill_estimator
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/net_namespace.c:net_assign_generic
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/dev.c:__netdev_adjacent_dev_remove
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:clean_xps_maps
  - net/core/dev.c:clean_xps_maps
  - net/core/dev.c:clean_xps_maps
  - net/core/dev.c:remove_xps_queue
  - net/core/dev.c:dev_set_alias
  - net/core/dev_addr_lists.c:dev_mc_flush
  - net/core/dev_addr_lists.c:dev_uc_flush
  - net/core/dev_addr_lists.c:dev_addr_flush
  - net/core/dev_addr_lists.c:__hw_addr_unsync_dev
  - net/core/dev_addr_lists.c:__hw_addr_del_entry
  - net/core/neighbour.c:neigh_destroy
  - net/core/rtnetlink.c:rtnl_unregister_all
  - net/core/rtnetlink.c:rtnl_unregister
  - net/core/rtnetlink.c:rtnl_register_internal
  - net/core/sock_reuseport.c:reuseport_grow
  - net/core/net-sysfs.c:rx_queue_release
  - net/core/net-sysfs.c:netdev_rx_queue_set_rps_mask
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/drop_monitor.c:dropmon_net_event
  - net/core/netprio_cgroup.c:netprio_device_event
  - net/core/netprio_cgroup.c:extend_netdev_table
  - net/core/lwtunnel.c:lwtstate_free
  - net/core/sock_map.c:sock_map_remove_links
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_create
  - net/sched/cls_api.c:tcf_exts_destroy
  - net/sched/cls_api.c:__tcf_block_put
  - net/sched/cls_api.c:__tcf_chain_put
  - net/sched/cls_api.c:__tcf_chain_put
  - net/sched/cls_api.c:__tcf_chain_put
  - net/sched/cls_api.c:tcf_proto_destroy
  - net/netlink/af_netlink.c:__netlink_change_ngroups
  - net/netlink/af_netlink.c:netlink_release
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/tcp_ipv4.c:tcp_clear_md5_list
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
  - net/ipv4/tcp_ipv4.c:tcp_md5_key_copy
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_add
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_flush_all
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/cipso_ipv4.c:cipso_v4_delopt
  - net/ipv4/cipso_ipv4.c:cipso_v4_req_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_sock_setattr
  - net/ipv4/tcp_ao.c:tcp_ao_destroy_sock
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_merge
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_merge
  - net/ipv6/af_inet6.c:inet6_cleanup_sock
  - net/ipv6/addrconf.c:inet6_ifa_finish_destroy
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_net_exit
  - net/ipv6/addrlabel.c:ip6addrlbl_net_exit
  - net/ipv6/addrlabel.c:ip6addrlbl_net_init
  - net/ipv6/addrlabel.c:ip6addrlbl_net_init
  - net/ipv6/addrlabel.c:__ip6addrlbl_add
  - net/ipv6/ipv6_sockglue.c:ipv6_set_opt_hdr
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/mcast.c:ipv6_mc_destroy_dev
  - net/ipv6/mcast.c:ipv6_mc_destroy_dev
  - net/ipv6/mcast.c:sf_setstate
  - net/ipv6/mcast.c:ip6_mc_del1_src
  - net/ipv6/mcast.c:mld_send_cr
  - net/ipv6/mcast.c:mld_send_cr
  - net/ipv6/mcast.c:mld_send_cr
  - net/ipv6/mcast.c:add_grec
  - net/ipv6/mcast.c:__ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_dev_mc_dec
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:mld_del_delrec
  - net/ipv6/mcast.c:mld_del_delrec
  - net/ipv6/mcast.c:mld_del_delrec
  - net/ipv6/mcast.c:ip6_mc_msfilter
  - net/ipv6/mcast.c:ip6_mc_source
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:fl6_free_socklist
  - net/ipv6/ioam6.c:ioam6_genl_delsc
  - net/ipv6/ioam6.c:ioam6_genl_delns
  - net/ipv6/calipso.c:calipso_req_delattr
  - net/ipv6/calipso.c:calipso_req_setattr
  - net/ipv6/calipso.c:calipso_sock_delattr
  - net/ipv6/calipso.c:calipso_sock_setattr
  - net/ipv6/calipso.c:calipso_sock_getattr
  - net/ipv6/calipso.c:calipso_opt_update
  - net/ipv6/calipso.c:calipso_opt_update
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_free_hi
  - net/devlink/netlink.c:devlink_nl_notify_filter_set_doit
  - net/devlink/netlink.c:devlink_nl_sock_priv_destroy
  - net/devlink/dpipe.c:devl_dpipe_table_unregister
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/mptcp/protocol.c:__mptcp_close_ssk
  - net/mptcp/subflow.c:subflow_ulp_release
  - net/mptcp/subflow.c:mptcp_subflow_drop_ctx
```
**Symbols:**

```
ffffffff821b3df0-ffffffff821b3e05: kvfree_call_rcu.cold (STB_LOCAL)
ffffffff811dae40-ffffffff811db278: kvfree_call_rcu (STB_GLOBAL)
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
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>void *ptr</code>
</li>
<li>
<b>Param removed. </b>
<code>rcu_callback_t func</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
