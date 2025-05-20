# Function: <code>call_rcu_sched</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void call_rcu_sched(struct callback_head *head, rcu_callback_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810e7b10)
Location: kernel/rcu/tree.c:3111
Inline: False
Direct callers:
  - arch/x86/mm/kmmio.c:remove_kmmio_fault_pages
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - kernel/exit.c:release_task
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:pwq_unbound_release_workfn
  - kernel/workqueue.c:pwq_unbound_release_workfn
  - kernel/pid.c:free_pid
  - kernel/sched/core.c:cpu_cgroup_css_free
  - kernel/sched/core.c:rq_attach_root
  - kernel/sched/core.c:cpu_attach_domain
  - kernel/sched/core.c:cpu_attach_domain
  - kernel/sched/core.c:cpu_attach_domain
  - kernel/time/posix-timers.c:release_posix_timer
  - kernel/module.c:do_init_module
  - kernel/cgroup.c:css_release_work_fn
  - kernel/cgroup.c:create_css
  - kernel/pid_namespace.c:destroy_pid_namespace
  - kernel/auditfilter.c:audit_del_rule
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_watch_handle_event
  - kernel/audit_tree.c:audit_tree_destroy_watch
  - kernel/audit_tree.c:kill_rules
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_probe_register_prio
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/ftrace.c:__unregister_ftrace_function_probe
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/events/core.c:_free_event
  - kernel/events/ring_buffer.c:rb_irq_work
  - kernel/events/callchain.c:put_callchain_buffers
  - mm/shmem.c:shmem_destroy_inode
  - mm/zswap.c:__zswap_pool_empty
  - mm/slub.c:discard_slab
  - fs/file_table.c:get_empty_filp
  - fs/file_table.c:__fput
  - fs/super.c:destroy_super
  - fs/fcntl.c:fasync_remove_entry
  - fs/file.c:expand_files
  - fs/namespace.c:cleanup_mnt
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/block_dev.c:bdev_destroy_inode
  - fs/eventpoll.c:ep_remove
  - fs/proc/inode.c:proc_destroy_inode
  - fs/ext4/super.c:ext4_destroy_inode
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/hugetlbfs/inode.c:hugetlbfs_destroy_inode
  - fs/fat/inode.c:fat_put_super
  - fs/fat/inode.c:fat_destroy_inode
  - fs/ecryptfs/dentry.c:ecryptfs_d_release
  - ipc/util.c:ipc_rcu_putref
  - ipc/mqueue.c:mqueue_destroy_inode
  - security/keys/trusted.c:trusted_update
  - security/keys/encrypted-keys/encrypted.c:encrypted_update
  - security/selinux/avc.c:avc_node_delete
  - security/selinux/avc.c:avc_node_replace
  - security/selinux/hooks.c:selinux_inode_free_security
  - security/apparmor/label.c:aa_label_kref
  - block/blk-core.c:get_request
  - block/blk-sysfs.c:blk_release_queue
  - block/blk-ioc.c:ioc_destroy_icq
  - block/partition-generic.c:__delete_partition
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:__blkg_release_rcu
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-throttle.c:throtl_pop_queued
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/cfq-iosched.c:cfq_init_queue
  - block/cfq-iosched.c:cfq_put_queue
  - lib/idr.c:idr_remove
  - lib/idr.c:idr_remove
  - lib/idr.c:idr_remove
  - lib/idr.c:idr_destroy
  - lib/radix-tree.c:__radix_tree_delete_node
  - lib/radix-tree.c:__radix_tree_delete_node
  - lib/radix-tree.c:__radix_tree_delete_node
  - lib/rhashtable.c:rht_deferred_worker
  - lib/assoc_array.c:assoc_array_apply_edit
  - lib/assoc_array.c:assoc_array_apply_edit
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/md/dm-stats.c:dm_stats_message
  - net/core/dst.c:dst_release
  - net/core/neighbour.c:neigh_parms_release
  - net/core/neighbour.c:neigh_table_clear
  - net/core/neighbour.c:__neigh_create
  - net/core/filter.c:sk_filter_uncharge
  - net/core/net-sysfs.c:store_rps_dev_flow_table_cnt
  - net/core/net-sysfs.c:rx_queue_release
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/act_api.c:tcf_hash_cleanup
  - net/netlink/af_netlink.c:netlink_release
  - net/ipv4/route.c:fnhe_flush_routes
  - net/ipv4/route.c:fnhe_flush_routes
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:rt_set_nexthop
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
  - net/ipv4/ip_sockglue.c:ip_ra_control
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_reset_cipher
  - net/ipv4/udp_offload.c:udp_del_offload
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_del_ifa
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/fib_semantics.c:free_fib_info
  - net/ipv4/fib_trie.c:tnode_free
  - net/ipv4/fib_trie.c:resize
  - net/ipv4/fib_trie.c:fib_insert_alias
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_table_delete
  - net/ipv4/fib_trie.c:fib_table_delete
  - net/ipv4/fib_trie.c:fib_table_flush_external
  - net/ipv4/fib_trie.c:fib_table_flush_external
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_free_table
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_putdef
  - net/ipv6/addrlabel.c:ip6addrlbl_net_exit
  - net/ipv6/addrlabel.c:ip6addrlbl_add
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrconf_core.c:in6_dev_finish_destroy
  - net/8021q/vlan_core.c:vlan_vid_del
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_netdev_handler
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
**Symbols:**

```
ffffffff810e7b10-ffffffff810e7b29: call_rcu_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void call_rcu_sched(struct callback_head *head, rcu_callback_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810edd20)
Location: kernel/rcu/tree.c:3189
Inline: False
Direct callers:
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:remove_kmmio_fault_pages
  - kernel/exit.c:release_task
  - kernel/exit.c:release_task
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:pwq_unbound_release_workfn
  - kernel/workqueue.c:pwq_unbound_release_workfn
  - kernel/workqueue.c:put_unbound_pool
  - kernel/pid.c:free_pid
  - kernel/sched/core.c:sched_destroy_group
  - kernel/sched/core.c:cpu_attach_domain
  - kernel/sched/core.c:cpu_attach_domain
  - kernel/sched/core.c:cpu_attach_domain
  - kernel/sched/core.c:rq_attach_root
  - kernel/irq/irqdesc.c:free_desc
  - kernel/time/posix-timers.c:release_posix_timer
  - kernel/module.c:do_init_module
  - kernel/cgroup.c:css_release_work_fn
  - kernel/cgroup.c:cgroup_apply_control_enable
  - kernel/pid_namespace.c:destroy_pid_namespace
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/auditfilter.c:audit_del_rule
  - kernel/audit_watch.c:audit_watch_handle_event
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_tree.c:kill_rules
  - kernel/audit_tree.c:audit_tree_destroy_watch
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_probe_register_prio
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:__unregister_ftrace_function_probe
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/bpf/arraymap.c:perf_event_fd_array_put_ptr
  - kernel/events/core.c:_free_event
  - kernel/events/callchain.c:put_callchain_buffers
  - mm/shmem.c:shmem_destroy_inode
  - mm/slub.c:discard_slab
  - fs/file_table.c:__fput
  - fs/file_table.c:get_empty_filp
  - fs/super.c:destroy_super
  - fs/fcntl.c:fasync_remove_entry
  - fs/file.c:expand_files
  - fs/namespace.c:cleanup_mnt
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/block_dev.c:bdev_destroy_inode
  - fs/eventpoll.c:ep_remove
  - fs/proc/inode.c:proc_destroy_inode
  - fs/ext4/super.c:ext4_destroy_inode
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/squashfs/super.c:squashfs_destroy_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_destroy_inode
  - fs/fat/inode.c:fat_destroy_inode
  - fs/fat/inode.c:fat_put_super
  - fs/ecryptfs/dentry.c:ecryptfs_d_release
  - ipc/util.c:ipc_rcu_putref
  - ipc/mqueue.c:mqueue_destroy_inode
  - security/keys/trusted.c:trusted_update
  - security/keys/encrypted-keys/encrypted.c:encrypted_update
  - security/selinux/avc.c:avc_node_replace
  - security/selinux/avc.c:avc_node_delete
  - security/selinux/hooks.c:selinux_inode_free_security
  - security/apparmor/label.c:aa_label_kref
  - block/blk-core.c:get_request
  - block/blk-sysfs.c:blk_release_queue
  - block/blk-ioc.c:ioc_destroy_icq
  - block/partition-generic.c:__delete_partition
  - block/blk-cgroup.c:__blkg_release_rcu
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_create
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_pop_queued
  - block/cfq-iosched.c:cfq_init_queue
  - block/cfq-iosched.c:cfq_put_queue
  - lib/idr.c:idr_destroy
  - lib/idr.c:idr_remove
  - lib/idr.c:idr_remove
  - lib/idr.c:idr_remove
  - lib/radix-tree.c:__radix_tree_delete_node
  - lib/radix-tree.c:__radix_tree_delete_node
  - lib/radix-tree.c:__radix_tree_delete_node
  - lib/rhashtable.c:rht_deferred_worker
  - lib/assoc_array.c:assoc_array_apply_edit
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/md/dm-stats.c:dm_stats_message
  - net/core/sock.c:sk_destruct
  - net/core/dst.c:dst_release
  - net/core/neighbour.c:neigh_table_clear
  - net/core/neighbour.c:neigh_parms_release
  - net/core/neighbour.c:__neigh_create
  - net/core/filter.c:sk_filter_uncharge
  - net/core/sock_reuseport.c:reuseport_detach_sock
  - net/core/net-sysfs.c:rx_queue_release
  - net/core/net-sysfs.c:store_rps_dev_flow_table_cnt
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/act_api.c:tcf_hash_cleanup
  - net/netlink/af_netlink.c:netlink_release
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:fnhe_flush_routes
  - net/ipv4/route.c:fnhe_flush_routes
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
  - net/ipv4/ip_sockglue.c:ip_ra_control
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_reset_cipher
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
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
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_putdef
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_net_exit
  - net/ipv6/addrlabel.c:ip6addrlbl_add
  - net/ipv6/calipso.c:calipso_doi_remove
  - net/ipv6/addrconf_core.c:in6_dev_finish_destroy
  - net/8021q/vlan_core.c:vlan_vid_del
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_netdev_handler
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
**Symbols:**

```
ffffffff810edd20-ffffffff810edd39: call_rcu_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void call_rcu_sched(struct callback_head *head, rcu_callback_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810f4c90)
Location: kernel/rcu/tree.c:3187
Inline: False
Direct callers:
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:remove_kmmio_fault_pages
  - kernel/exit.c:release_task
  - kernel/exit.c:release_task
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:pwq_unbound_release_workfn
  - kernel/workqueue.c:pwq_unbound_release_workfn
  - kernel/workqueue.c:put_unbound_pool
  - kernel/pid.c:free_pid
  - kernel/sched/core.c:sched_destroy_group
  - kernel/sched/core.c:cpu_attach_domain
  - kernel/sched/core.c:rq_attach_root
  - kernel/irq/irqdesc.c:free_desc
  - kernel/time/posix-timers.c:release_posix_timer
  - kernel/module.c:do_init_module
  - kernel/cgroup.c:css_release_work_fn
  - kernel/cgroup.c:cgroup_apply_control_enable
  - kernel/pid_namespace.c:destroy_pid_namespace
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/auditfilter.c:audit_del_rule
  - kernel/audit_watch.c:audit_watch_handle_event
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_tree.c:kill_rules
  - kernel/audit_tree.c:audit_tree_destroy_watch
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_probe_register_prio
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:__unregister_ftrace_function_probe
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/bpf/arraymap.c:perf_event_fd_array_put_ptr
  - kernel/events/core.c:_free_event
  - kernel/events/callchain.c:put_callchain_buffers
  - mm/shmem.c:shmem_destroy_inode
  - mm/slub.c:discard_slab
  - fs/file_table.c:__fput
  - fs/file_table.c:get_empty_filp
  - fs/super.c:destroy_super
  - fs/fcntl.c:fasync_remove_entry
  - fs/file.c:expand_files
  - fs/namespace.c:cleanup_mnt
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/block_dev.c:bdev_destroy_inode
  - fs/eventpoll.c:ep_remove
  - fs/proc/inode.c:proc_destroy_inode
  - fs/ext4/super.c:ext4_destroy_inode
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/squashfs/super.c:squashfs_destroy_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_destroy_inode
  - fs/fat/inode.c:fat_destroy_inode
  - fs/fat/inode.c:fat_put_super
  - fs/ecryptfs/dentry.c:ecryptfs_d_release
  - ipc/util.c:ipc_rcu_putref
  - ipc/mqueue.c:mqueue_destroy_inode
  - security/keys/trusted.c:trusted_update
  - security/keys/encrypted-keys/encrypted.c:encrypted_update
  - security/selinux/avc.c:avc_node_replace
  - security/selinux/avc.c:avc_node_delete
  - security/selinux/hooks.c:selinux_inode_free_security
  - security/apparmor/label.c:aa_label_kref
  - block/blk-core.c:__blk_put_request
  - block/blk-core.c:get_request
  - block/blk-sysfs.c:blk_release_queue
  - block/blk-ioc.c:ioc_destroy_icq
  - block/partition-generic.c:__delete_partition
  - block/blk-cgroup.c:__blkg_release_rcu
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_create
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_pop_queued
  - block/cfq-iosched.c:cfq_init_queue
  - block/cfq-iosched.c:cfq_put_queue
  - lib/idr.c:idr_destroy
  - lib/idr.c:idr_remove
  - lib/idr.c:idr_remove
  - lib/idr.c:idr_remove
  - lib/radix-tree.c:radix_tree_free_nodes
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/rhashtable.c:rht_deferred_worker
  - lib/assoc_array.c:assoc_array_apply_edit
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/md/dm-stats.c:dm_stats_message
  - net/core/sock.c:sk_destruct
  - net/core/dst.c:dst_release
  - net/core/neighbour.c:neigh_table_clear
  - net/core/neighbour.c:neigh_parms_release
  - net/core/neighbour.c:__neigh_create
  - net/core/filter.c:sk_filter_uncharge
  - net/core/sock_reuseport.c:reuseport_detach_sock
  - net/core/net-sysfs.c:rx_queue_release
  - net/core/net-sysfs.c:store_rps_dev_flow_table_cnt
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/act_api.c:tcf_hash_cleanup
  - net/netlink/af_netlink.c:netlink_release
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:fnhe_flush_routes
  - net/ipv4/route.c:fnhe_flush_routes
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
  - net/ipv4/ip_sockglue.c:ip_ra_control
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_reset_cipher
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
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
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_putdef
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_net_exit
  - net/ipv6/addrlabel.c:ip6addrlbl_add
  - net/ipv6/calipso.c:calipso_doi_remove
  - net/ipv6/addrconf_core.c:in6_dev_finish_destroy
  - net/8021q/vlan_core.c:vlan_vid_del
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_netdev_handler
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
**Symbols:**

```
ffffffff810f4c90-ffffffff810f4ca9: call_rcu_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void call_rcu_sched(struct callback_head *head, rcu_callback_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810f59d0)
Location: kernel/rcu/tree.c:3195
Inline: False
Direct callers:
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:remove_kmmio_fault_pages
  - kernel/exit.c:release_task
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:pwq_unbound_release_workfn
  - kernel/workqueue.c:pwq_unbound_release_workfn
  - kernel/workqueue.c:put_unbound_pool
  - kernel/pid.c:free_pid
  - kernel/sched/core.c:sched_destroy_group
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:rq_attach_root
  - kernel/irq/irqdesc.c:free_desc
  - kernel/time/posix-timers.c:release_posix_timer
  - kernel/module.c:do_init_module
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/pid_namespace.c:put_pid_ns
  - kernel/audit.c:audit_receive_msg
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/auditfilter.c:audit_del_rule
  - kernel/audit_watch.c:audit_watch_handle_event
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_tree.c:kill_rules
  - kernel/audit_tree.c:audit_tree_destroy_watch
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_probe_register_prio
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/bpf/arraymap.c:perf_event_fd_array_put_ptr
  - kernel/events/core.c:_free_event
  - kernel/events/callchain.c:put_callchain_buffers
  - mm/shmem.c:shmem_destroy_inode
  - mm/slab_common.c:slab_deactivate_memcg_cache_rcu_sched
  - mm/slub.c:discard_slab
  - fs/file_table.c:__fput
  - fs/file_table.c:get_empty_filp
  - fs/super.c:destroy_super
  - fs/fcntl.c:fasync_remove_entry
  - fs/dcache.c:dentry_free
  - fs/dcache.c:dentry_free
  - fs/file.c:expand_files
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
  - ipc/util.c:ipc_rcu_putref
  - ipc/msg.c:newque
  - ipc/sem.c:newary
  - ipc/shm.c:newseg
  - ipc/mqueue.c:mqueue_destroy_inode
  - security/keys/user_defined.c:user_revoke
  - security/keys/trusted.c:trusted_update
  - security/keys/encrypted-keys/encrypted.c:encrypted_update
  - security/security.c:security_inode_free
  - security/selinux/avc.c:avc_node_replace
  - security/selinux/avc.c:avc_node_delete
  - security/apparmor/label.c:aa_label_kref
  - block/blk-core.c:__blk_put_request
  - block/blk-core.c:get_request
  - block/blk-core.c:get_request
  - block/blk-sysfs.c:__blk_release_queue
  - block/blk-ioc.c:ioc_destroy_icq
  - block/blk-stat.c:blk_stat_free_callback
  - block/partition-generic.c:__delete_partition
  - block/blk-cgroup.c:__blkg_release_rcu
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_create
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_pop_queued
  - block/cfq-iosched.c:cfq_init_queue
  - block/cfq-iosched.c:cfq_put_queue
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/rhashtable.c:rht_deferred_worker
  - lib/assoc_array.c:assoc_array_apply_edit
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/dax/super.c:dax_destroy_inode
  - drivers/md/dm-stats.c:dm_stats_message
  - net/core/sock.c:sk_destruct
  - net/core/dst.c:dst_release
  - net/core/neighbour.c:neigh_table_clear
  - net/core/neighbour.c:__neigh_create
  - net/core/filter.c:sk_filter_uncharge
  - net/core/sock_reuseport.c:reuseport_detach_sock
  - net/core/net-sysfs.c:rx_queue_release
  - net/core/net-sysfs.c:store_rps_dev_flow_table_cnt
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/act_api.c:tcf_hash_cleanup
  - net/netlink/af_netlink.c:netlink_release
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
  - net/ipv4/ip_sockglue.c:ip_ra_control
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_reset_cipher
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
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_putdef
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_net_exit
  - net/ipv6/addrlabel.c:ip6addrlbl_add
  - net/ipv6/ip6_fib.c:fib6_repair_tree
  - net/ipv6/calipso.c:calipso_doi_remove
  - net/ipv6/addrconf_core.c:in6_dev_finish_destroy
  - net/8021q/vlan_core.c:vlan_vid_del
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_netdev_handler
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - lib/radix-tree.c:radix_tree_free_nodes
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
```
**Symbols:**

```
ffffffff810f59d0-ffffffff810f59e9: call_rcu_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void call_rcu_sched(struct callback_head *head, rcu_callback_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810ff7d0)
Location: kernel/rcu/tree.c:3177
Inline: False
Direct callers:
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:remove_kmmio_fault_pages
  - kernel/exit.c:release_task
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:pwq_unbound_release_workfn
  - kernel/workqueue.c:pwq_unbound_release_workfn
  - kernel/workqueue.c:put_unbound_pool
  - kernel/pid.c:free_pid
  - kernel/cred.c:__put_cred
  - kernel/sched/core.c:sched_destroy_group
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:sched_put_rd
  - kernel/sched/topology.c:rq_attach_root
  - kernel/irq/irqdesc.c:free_desc
  - kernel/time/posix-timers.c:release_posix_timer
  - kernel/module.c:do_init_module
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:cgroup_apply_control_enable
  - kernel/pid_namespace.c:destroy_pid_namespace
  - kernel/audit.c:audit_receive_msg
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/auditfilter.c:audit_del_rule
  - kernel/audit_watch.c:audit_watch_handle_event
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_tree.c:kill_rules
  - kernel/audit_tree.c:audit_tree_destroy_watch
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_probe_register_prio
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/bpf/arraymap.c:perf_event_fd_array_put_ptr
  - kernel/bpf/devmap.c:dev_map_notification
  - kernel/bpf/devmap.c:dev_map_update_elem
  - kernel/bpf/devmap.c:dev_map_delete_elem
  - kernel/bpf/cpumap.c:__cpu_map_entry_replace
  - kernel/events/core.c:_free_event
  - kernel/events/callchain.c:put_callchain_buffers
  - mm/shmem.c:shmem_destroy_inode
  - mm/slab_common.c:slab_deactivate_memcg_cache_rcu_sched
  - mm/slab_common.c:memcg_update_all_caches
  - mm/memory.c:tlb_remove_table
  - mm/slub.c:discard_slab
  - fs/file_table.c:__fput
  - fs/file_table.c:get_empty_filp
  - fs/fcntl.c:fasync_remove_entry
  - fs/dcache.c:dentry_free
  - fs/dcache.c:dentry_free
  - fs/file.c:expand_files
  - fs/namespace.c:cleanup_mnt
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/block_dev.c:bdev_destroy_inode
  - fs/eventpoll.c:ep_remove
  - fs/aio.c:free_ioctx_reqs
  - fs/proc/inode.c:proc_destroy_inode
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/super.c:ext4_destroy_inode
  - fs/squashfs/super.c:squashfs_destroy_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_destroy_inode
  - fs/fat/inode.c:fat_destroy_inode
  - fs/fat/inode.c:fat_put_super
  - fs/ecryptfs/dentry.c:ecryptfs_d_release
  - ipc/util.c:ipc_rcu_putref
  - ipc/msg.c:newque
  - ipc/sem.c:newary
  - ipc/shm.c:newseg
  - ipc/mqueue.c:mqueue_destroy_inode
  - security/keys/user_defined.c:user_revoke
  - security/keys/trusted.c:trusted_update
  - security/keys/encrypted-keys/encrypted.c:encrypted_update
  - security/security.c:security_inode_free
  - security/selinux/avc.c:avc_node_replace
  - security/selinux/avc.c:avc_node_delete
  - security/apparmor/label.c:aa_label_kref
  - block/blk-core.c:__blk_put_request
  - block/blk-core.c:get_request
  - block/blk-core.c:get_request
  - block/blk-sysfs.c:__blk_release_queue
  - block/blk-ioc.c:ioc_destroy_icq
  - block/blk-mq.c:blk_mq_free_request
  - block/blk-stat.c:blk_stat_free_callback
  - block/partition-generic.c:__delete_partition
  - block/blk-cgroup.c:__blkg_release_rcu
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_create
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_pop_queued
  - block/cfq-iosched.c:cfq_init_queue
  - block/cfq-iosched.c:cfq_put_queue
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/rhashtable.c:rht_deferred_worker
  - lib/assoc_array.c:assoc_array_apply_edit
  - lib/assoc_array.c:assoc_array_apply_edit
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
  - drivers/dax/super.c:dax_destroy_inode
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
  - drivers/md/dm-stats.c:dm_stats_message
  - net/core/sock.c:sk_destruct
  - net/core/dst.c:dst_release
  - net/core/neighbour.c:neigh_table_clear
  - net/core/neighbour.c:__neigh_create
  - net/core/filter.c:sk_filter_release
  - net/core/sock_reuseport.c:reuseport_detach_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/net-sysfs.c:rx_queue_release
  - net/core/net-sysfs.c:store_rps_dev_flow_table_cnt
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
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_putdef
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove
  - net/ipv6/calipso.c:calipso_doi_remove
  - net/ipv6/addrconf_core.c:in6_dev_finish_destroy
  - net/8021q/vlan_core.c:vlan_vid_del
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_entry
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_netdev_handler
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - lib/radix-tree.c:radix_tree_free_nodes
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
```
**Symbols:**

```
ffffffff810ff7d0-ffffffff810ff7e9: call_rcu_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void call_rcu_sched(struct callback_head *head, rcu_callback_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81106700)
Location: kernel/rcu/tree.c:2983
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
  - kernel/audit_tree.c:kill_rules
  - kernel/audit_tree.c:audit_tree_destroy_watch
  - kernel/tracepoint.c:tracepoint_probe_unregister
  - kernel/tracepoint.c:tracepoint_probe_register_prio
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/bpf/arraymap.c:perf_event_fd_array_put_ptr
  - kernel/bpf/devmap.c:dev_map_notification
  - kernel/bpf/devmap.c:dev_map_update_elem
  - kernel/bpf/devmap.c:dev_map_delete_elem
  - kernel/bpf/sockmap.c:sock_hash_free
  - kernel/events/core.c:_free_event
  - kernel/events/callchain.c:put_callchain_buffers
  - mm/shmem.c:shmem_destroy_inode
  - mm/slab_common.c:slab_deactivate_memcg_cache_rcu_sched
  - mm/slab_common.c:memcg_update_all_caches
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/slub.c:discard_slab
  - fs/file_table.c:__fput
  - fs/file_table.c:get_empty_filp
  - fs/fcntl.c:fasync_remove_entry
  - fs/dcache.c:__d_move
  - fs/dcache.c:dentry_free
  - fs/dcache.c:dentry_free
  - fs/dcache.c:release_dentry_name_snapshot
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
  - ipc/util.c:ipc_rcu_putref
  - ipc/msg.c:newque
  - ipc/sem.c:newary
  - ipc/shm.c:newseg
  - ipc/shm.c:newseg
  - ipc/mqueue.c:mqueue_destroy_inode
  - security/keys/user_defined.c:user_revoke
  - security/keys/user_defined.c:user_update
  - security/keys/trusted.c:trusted_update
  - security/keys/encrypted-keys/encrypted.c:encrypted_update
  - security/selinux/avc.c:avc_node_replace
  - security/selinux/avc.c:avc_node_delete
  - security/selinux/hooks.c:selinux_inode_free_security
  - security/smack/smack_lsm.c:smack_inode_free_security
  - security/apparmor/label.c:aa_label_kref
  - block/blk-core.c:__blk_put_request
  - block/blk-core.c:get_request
  - block/blk-core.c:get_request
  - block/blk-sysfs.c:__blk_release_queue
  - block/blk-ioc.c:ioc_destroy_icq
  - block/blk-mq.c:blk_mq_free_request
  - block/blk-stat.c:blk_stat_free_callback
  - block/partition-generic.c:__delete_partition
  - block/blk-cgroup.c:__blkg_release_rcu
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_create
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_pop_queued
  - block/cfq-iosched.c:cfq_init_queue
  - block/cfq-iosched.c:cfq_put_queue
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
  - net/core/neighbour.c:__neigh_create
  - net/core/filter.c:sk_filter_release
  - net/core/sock_reuseport.c:reuseport_detach_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/xdp.c:xdp_rxq_info_unreg
  - net/core/net-sysfs.c:rx_queue_release
  - net/core/net-sysfs.c:store_rps_dev_flow_table_cnt
  - net/core/page_pool.c:page_pool_destroy
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
  - lib/radix-tree.c:radix_tree_free_nodes
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
```
**Symbols:**

```
ffffffff81106700-ffffffff81106719: call_rcu_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810e5ae0)
Location: include/linux/rcupdate.h:932
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_put_rd
  - kernel/sched/topology.c:rq_attach_root
```
</details>
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
</ul>
