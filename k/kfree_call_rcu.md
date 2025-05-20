# Function: <code>kfree_call_rcu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void kfree_call_rcu(struct callback_head *head, rcu_callback_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810e7ad0)
Location: kernel/rcu/tree.c:3133
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_free
  - kernel/sched/fair.c:task_numa_fault
  - kernel/acct.c:acct_put
  - kernel/audit_tree.c:free_chunk
  - kernel/audit_tree.c:untag_chunk
  - kernel/audit_tree.c:prune_one
  - kernel/audit_tree.c:audit_trim_trees
  - kernel/audit_tree.c:audit_put_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_delete_elem
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/slab_common.c:memcg_update_all_caches
  - mm/vmalloc.c:__free_vmap_area
  - fs/dcache.c:__d_move
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
  - fs/timerfd.c:timerfd_release
  - fs/aio.c:SyS_io_setup
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_cached_acl
  - fs/posix_acl.c:__posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_chmod
  - fs/posix_acl.c:set_cached_acl
  - fs/posix_acl.c:posix_acl_xattr_get
  - fs/posix_acl.c:__posix_acl_create
  - fs/posix_acl.c:__posix_acl_create
  - fs/posix_acl.c:posix_acl_from_xattr
  - fs/posix_acl.c:posix_acl_xattr_set
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:simple_acl_create
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/proc/proc_sysctl.c:sysctl_head_put
  - fs/ext4/acl.c:ext4_get_acl
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_init_acl
  - fs/fuse/inode.c:fuse_free_conn
  - ipc/sem.c:freeary
  - ipc/sem.c:exit_sem
  - security/keys/user_defined.c:user_update
  - security/keys/user_defined.c:user_revoke
  - security/selinux/netif.c:sel_netif_destroy
  - security/selinux/netnode.c:sel_netnode_sid
  - security/selinux/netnode.c:sel_netnode_flush
  - security/selinux/netport.c:sel_netport_sid
  - security/selinux/netport.c:sel_netport_flush
  - security/yama/yama_lsm.c:yama_relation_cleanup
  - security/yama/yama_lsm.c:yama_ptracer_add
  - security/device_cgroup.c:__dev_exception_clean
  - security/device_cgroup.c:dev_exception_rm
  - block/genhd.c:disk_release
  - block/genhd.c:disk_expand_part_tbl
  - drivers/iommu/intel-svm.c:intel_svm_unbind_mm
  - net/socket.c:sock_destroy_inode
  - net/core/gen_estimator.c:gen_kill_estimator
  - net/core/net_namespace.c:ops_init
  - net/core/dev.c:remove_xps_queue
  - net/core/dev.c:netif_reset_xps_queues_gt
  - net/core/dev.c:__netdev_adjacent_dev_remove
  - net/core/dev.c:netif_set_xps_queue
  - net/core/dev.c:netif_set_xps_queue
  - net/core/dev.c:netif_set_xps_queue
  - net/core/dev_addr_lists.c:__hw_addr_flush
  - net/core/neighbour.c:neigh_destroy
  - net/core/net-sysfs.c:rx_queue_release
  - net/core/net-sysfs.c:store_rps_map
  - net/core/fib_rules.c:fib_rules_unregister
  - net/core/fib_rules.c:fib_rules_unregister
  - net/core/netprio_cgroup.c:netprio_device_event
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:__netlink_change_ngroups
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_minisocks.c:tcp_twsk_destructor
  - net/ipv4/tcp_metrics.c:tcp_metrics_flush_all
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/cipso_ipv4.c:cipso_v4_delopt
  - net/ipv4/cipso_ipv4.c:cipso_v4_sock_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_req_setattr
  - net/ipv6/af_inet6.c:inet6_destroy_sock
  - net/ipv6/addrconf.c:inet6_ifa_finish_destroy
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/mcast.c:ipv6_sock_mc_close
  - net/ipv6/ip6_flowlabel.c:fl_free
  - net/ipv6/ip6_flowlabel.c:fl6_free_socklist
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/packet/af_packet.c:packet_release
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
**Symbols:**

```
ffffffff810e7ad0-ffffffff810e7aec: kfree_call_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void kfree_call_rcu(struct callback_head *head, rcu_callback_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810edce0)
Location: kernel/rcu/tree.c:3211
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_free
  - kernel/acct.c:acct_put
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_put_tree
  - kernel/audit_tree.c:audit_trim_trees
  - kernel/audit_tree.c:prune_one
  - kernel/audit_tree.c:untag_chunk
  - kernel/audit_tree.c:free_chunk
  - kernel/events/core.c:swevent_hlist_put_cpu
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/slab_common.c:memcg_update_all_caches
  - mm/vmalloc.c:__free_vmap_area
  - fs/dcache.c:__d_move
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
  - fs/timerfd.c:timerfd_release
  - fs/aio.c:SyS_io_setup
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
  - fs/proc/proc_sysctl.c:sysctl_head_put
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_get_acl
  - fs/fuse/inode.c:fuse_free_conn
  - ipc/sem.c:exit_sem
  - ipc/sem.c:freeary
  - security/keys/user_defined.c:user_revoke
  - security/keys/user_defined.c:user_update
  - security/selinux/netif.c:sel_netif_destroy
  - security/selinux/netnode.c:sel_netnode_flush
  - security/selinux/netnode.c:sel_netnode_sid
  - security/selinux/netport.c:sel_netport_flush
  - security/selinux/netport.c:sel_netport_sid
  - security/yama/yama_lsm.c:yama_ptracer_add
  - security/yama/yama_lsm.c:yama_relation_cleanup
  - security/device_cgroup.c:__dev_exception_clean
  - security/device_cgroup.c:dev_exception_rm
  - block/genhd.c:disk_release
  - block/genhd.c:disk_expand_part_tbl
  - drivers/iommu/intel-svm.c:intel_svm_unbind_mm
  - net/socket.c:sock_destroy_inode
  - net/core/gen_estimator.c:gen_kill_estimator
  - net/core/net_namespace.c:ops_init
  - net/core/dev.c:__netdev_adjacent_dev_remove
  - net/core/dev.c:netif_set_xps_queue
  - net/core/dev.c:netif_set_xps_queue
  - net/core/dev.c:netif_set_xps_queue
  - net/core/dev.c:netif_reset_xps_queues_gt
  - net/core/dev.c:remove_xps_queue
  - net/core/dev_addr_lists.c:__hw_addr_flush
  - net/core/neighbour.c:neigh_destroy
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/net-sysfs.c:rx_queue_release
  - net/core/net-sysfs.c:store_rps_map
  - net/core/fib_rules.c:fib_rules_unregister
  - net/core/fib_rules.c:fib_rules_unregister
  - net/core/netprio_cgroup.c:netprio_device_event
  - net/netlink/af_netlink.c:__netlink_change_ngroups
  - net/netlink/af_netlink.c:netlink_release
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
  - net/ipv4/tcp_minisocks.c:tcp_twsk_destructor
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_flush_all
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/cipso_ipv4.c:cipso_v4_delopt
  - net/ipv4/cipso_ipv4.c:cipso_v4_req_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_sock_setattr
  - net/ipv6/af_inet6.c:inet6_destroy_sock
  - net/ipv6/addrconf.c:inet6_ifa_finish_destroy
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/mcast.c:ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:fl6_free_socklist
  - net/ipv6/ip6_flowlabel.c:fl_free
  - net/ipv6/calipso.c:calipso_req_delattr
  - net/ipv6/calipso.c:calipso_req_setattr
  - net/ipv6/calipso.c:calipso_sock_delattr
  - net/ipv6/calipso.c:calipso_sock_setattr
  - net/ipv6/calipso.c:calipso_sock_getattr
  - net/ipv6/calipso.c:calipso_opt_update
  - net/ipv6/calipso.c:calipso_opt_update
  - net/packet/af_packet.c:packet_release
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
**Symbols:**

```
ffffffff810edce0-ffffffff810edcfc: kfree_call_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void kfree_call_rcu(struct callback_head *head, rcu_callback_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810f4c50)
Location: kernel/rcu/tree.c:3209
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_free
  - kernel/acct.c:acct_put
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_put_tree
  - kernel/audit_tree.c:audit_trim_trees
  - kernel/audit_tree.c:prune_one
  - kernel/audit_tree.c:untag_chunk
  - kernel/audit_tree.c:free_chunk
  - kernel/events/core.c:swevent_hlist_put_cpu
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/slab_common.c:memcg_update_all_caches
  - mm/vmalloc.c:__free_vmap_area
  - fs/dcache.c:__d_move
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
  - fs/timerfd.c:timerfd_release
  - fs/aio.c:ioctx_alloc
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
  - fs/proc/proc_sysctl.c:sysctl_head_put
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_get_acl
  - fs/fuse/dir.c:fuse_dentry_release
  - fs/fuse/inode.c:fuse_free_conn
  - ipc/sem.c:exit_sem
  - ipc/sem.c:freeary
  - security/keys/user_defined.c:user_revoke
  - security/keys/user_defined.c:user_update
  - security/selinux/netif.c:sel_netif_destroy
  - security/selinux/netnode.c:sel_netnode_flush
  - security/selinux/netnode.c:sel_netnode_sid
  - security/selinux/netport.c:sel_netport_flush
  - security/selinux/netport.c:sel_netport_sid
  - security/yama/yama_lsm.c:yama_ptracer_add
  - security/yama/yama_lsm.c:yama_relation_cleanup
  - security/device_cgroup.c:__dev_exception_clean
  - security/device_cgroup.c:dev_exception_rm
  - block/genhd.c:disk_release
  - block/genhd.c:disk_expand_part_tbl
  - drivers/iommu/intel-svm.c:intel_svm_unbind_mm
  - net/socket.c:sock_destroy_inode
  - net/core/gen_estimator.c:gen_kill_estimator
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/net_namespace.c:ops_init
  - net/core/dev.c:netif_set_xps_queue
  - net/core/dev.c:netif_set_xps_queue
  - net/core/dev.c:netif_set_xps_queue
  - net/core/dev.c:netif_reset_xps_queues
  - net/core/dev.c:remove_xps_queue
  - net/core/dev_addr_lists.c:__hw_addr_flush
  - net/core/neighbour.c:neigh_destroy
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/net-sysfs.c:rx_queue_release
  - net/core/net-sysfs.c:store_rps_map
  - net/core/fib_rules.c:fib_rules_unregister
  - net/core/fib_rules.c:fib_rules_unregister
  - net/core/netprio_cgroup.c:netprio_device_event
  - net/core/lwtunnel.c:lwtstate_free
  - net/netlink/af_netlink.c:__netlink_change_ngroups
  - net/netlink/af_netlink.c:netlink_release
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
  - net/ipv4/tcp_minisocks.c:tcp_twsk_destructor
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_flush_all
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/cipso_ipv4.c:cipso_v4_delopt
  - net/ipv4/cipso_ipv4.c:cipso_v4_req_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_sock_setattr
  - net/ipv6/af_inet6.c:inet6_destroy_sock
  - net/ipv6/addrconf.c:inet6_ifa_finish_destroy
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:fl6_free_socklist
  - net/ipv6/ip6_flowlabel.c:fl_free
  - net/ipv6/calipso.c:calipso_req_delattr
  - net/ipv6/calipso.c:calipso_req_setattr
  - net/ipv6/calipso.c:calipso_sock_delattr
  - net/ipv6/calipso.c:calipso_sock_setattr
  - net/ipv6/calipso.c:calipso_sock_getattr
  - net/ipv6/calipso.c:calipso_opt_update
  - net/ipv6/calipso.c:calipso_opt_update
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_free_hi
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_release
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
**Symbols:**

```
ffffffff810f4c50-ffffffff810f4c6c: kfree_call_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void kfree_call_rcu(struct callback_head *head, rcu_callback_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810f5990)
Location: kernel/rcu/tree.c:3235
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_free
  - kernel/acct.c:acct_put
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_put_tree
  - kernel/audit_tree.c:audit_trim_trees
  - kernel/audit_tree.c:prune_one
  - kernel/audit_tree.c:untag_chunk
  - kernel/audit_tree.c:audit_put_chunk
  - kernel/bpf/lpm_trie.c:trie_update_elem
  - kernel/events/core.c:swevent_hlist_put_cpu
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/slab_common.c:memcg_update_all_caches
  - mm/vmalloc.c:__free_vmap_area
  - fs/dcache.c:__d_move
  - fs/dcache.c:release_dentry_name_snapshot
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
  - fs/timerfd.c:timerfd_release
  - fs/aio.c:ioctx_alloc
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
  - fs/proc/proc_sysctl.c:proc_sys_evict_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_get_acl
  - fs/fuse/dir.c:fuse_dentry_release
  - fs/fuse/inode.c:fuse_free_conn
  - fs/fuse/inode.c:fuse_free_conn
  - ipc/sem.c:exit_sem
  - ipc/sem.c:freeary
  - security/selinux/netif.c:sel_netif_destroy
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
  - block/genhd.c:disk_release
  - block/genhd.c:disk_expand_part_tbl
  - drivers/iommu/intel-svm.c:intel_svm_unbind_mm
  - net/socket.c:sock_destroy_inode
  - net/core/gen_estimator.c:gen_kill_estimator
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/net_namespace.c:ops_init
  - net/core/dev.c:netif_set_xps_queue
  - net/core/dev.c:netif_set_xps_queue
  - net/core/dev.c:netif_set_xps_queue
  - net/core/dev.c:netif_reset_xps_queues
  - net/core/dev.c:remove_xps_queue
  - net/core/dev_addr_lists.c:__hw_addr_flush
  - net/core/neighbour.c:neigh_destroy
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/net-sysfs.c:rx_queue_release
  - net/core/net-sysfs.c:store_rps_map
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_rules_unregister
  - net/core/fib_rules.c:fib_rules_unregister
  - net/core/netprio_cgroup.c:netprio_device_event
  - net/core/lwtunnel.c:lwtstate_free
  - net/sched/cls_api.c:tcf_proto_destroy
  - net/netlink/af_netlink.c:__netlink_change_ngroups
  - net/netlink/af_netlink.c:netlink_release
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
  - net/ipv4/tcp_minisocks.c:tcp_twsk_destructor
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_flush_all
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/cipso_ipv4.c:cipso_v4_delopt
  - net/ipv4/cipso_ipv4.c:cipso_v4_req_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_sock_setattr
  - net/ipv6/af_inet6.c:inet6_destroy_sock
  - net/ipv6/addrconf.c:inet6_ifa_finish_destroy
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:fl6_free_socklist
  - net/ipv6/ip6_flowlabel.c:fl_free
  - net/ipv6/calipso.c:calipso_req_delattr
  - net/ipv6/calipso.c:calipso_req_setattr
  - net/ipv6/calipso.c:calipso_sock_delattr
  - net/ipv6/calipso.c:calipso_sock_setattr
  - net/ipv6/calipso.c:calipso_sock_getattr
  - net/ipv6/calipso.c:calipso_opt_update
  - net/ipv6/calipso.c:calipso_opt_update
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_free_hi
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_release
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
**Symbols:**

```
ffffffff810f5990-ffffffff810f59ac: kfree_call_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void kfree_call_rcu(struct callback_head *head, rcu_callback_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810ff790)
Location: kernel/rcu/tree.c:3218
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_free
  - kernel/livepatch/shadow.c:klp_shadow_free_all
  - kernel/livepatch/shadow.c:klp_shadow_free
  - kernel/acct.c:acct_put
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_put_tree
  - kernel/audit_tree.c:audit_trim_trees
  - kernel/audit_tree.c:prune_one
  - kernel/audit_tree.c:untag_chunk
  - kernel/audit_tree.c:audit_put_chunk
  - kernel/bpf/core.c:bpf_prog_array_free
  - kernel/bpf/lpm_trie.c:trie_delete_elem
  - kernel/bpf/lpm_trie.c:trie_delete_elem
  - kernel/bpf/lpm_trie.c:trie_delete_elem
  - kernel/bpf/lpm_trie.c:trie_update_elem
  - kernel/events/core.c:swevent_hlist_put_cpu
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/vmalloc.c:free_vmap_block
  - mm/vmalloc.c:__free_vmap_area
  - fs/dcache.c:__d_move
  - fs/dcache.c:release_dentry_name_snapshot
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
  - fs/timerfd.c:timerfd_release
  - fs/aio.c:ioctx_alloc
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
  - fs/proc/proc_sysctl.c:proc_sys_evict_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_get_acl
  - fs/fuse/dir.c:fuse_dentry_release
  - fs/fuse/inode.c:fuse_free_conn
  - fs/fuse/inode.c:fuse_free_conn
  - ipc/sem.c:exit_sem
  - ipc/sem.c:freeary
  - security/selinux/netif.c:sel_netif_destroy
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
  - block/genhd.c:disk_release
  - block/genhd.c:disk_expand_part_tbl
  - drivers/iommu/intel-svm.c:intel_svm_unbind_mm
  - drivers/dma-buf/dma-fence.c:dma_fence_release
  - drivers/dma-buf/reservation.c:reservation_object_copy_fences
  - drivers/scsi/scsi.c:scsi_update_vpd_page
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext
  - net/socket.c:sock_destroy_inode
  - net/core/gen_estimator.c:gen_kill_estimator
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/net_namespace.c:ops_init
  - net/core/dev.c:netif_set_xps_queue
  - net/core/dev.c:netif_set_xps_queue
  - net/core/dev.c:netif_set_xps_queue
  - net/core/dev.c:netif_reset_xps_queues
  - net/core/dev.c:remove_xps_queue
  - net/core/dev.c:dev_set_alias
  - net/core/dev_addr_lists.c:__hw_addr_flush
  - net/core/neighbour.c:neigh_destroy
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/fib_notifier.c:fib_notifier_ops_unregister
  - net/core/net-sysfs.c:rx_queue_release
  - net/core/net-sysfs.c:store_rps_map
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_rules_unregister
  - net/core/fib_rules.c:fib_rules_unregister
  - net/core/netprio_cgroup.c:netprio_device_event
  - net/core/lwtunnel.c:lwtstate_free
  - net/sched/cls_api.c:tcf_proto_destroy
  - net/netlink/af_netlink.c:__netlink_change_ngroups
  - net/netlink/af_netlink.c:netlink_release
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
  - net/ipv4/tcp_minisocks.c:tcp_twsk_destructor
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_flush_all
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/cipso_ipv4.c:cipso_v4_delopt
  - net/ipv4/cipso_ipv4.c:cipso_v4_req_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_sock_setattr
  - net/ipv6/af_inet6.c:inet6_destroy_sock
  - net/ipv6/addrconf.c:inet6_ifa_finish_destroy
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_net_exit
  - net/ipv6/addrlabel.c:ip6addrlbl_net_exit
  - net/ipv6/addrlabel.c:ip6addrlbl_add
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:fl6_free_socklist
  - net/ipv6/ip6_flowlabel.c:fl_free
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
```
**Symbols:**

```
ffffffff810ff790-ffffffff810ff7ac: kfree_call_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void kfree_call_rcu(struct callback_head *head, rcu_callback_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811066c0)
Location: kernel/rcu/tree.c:3024
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_free
  - kernel/livepatch/shadow.c:klp_shadow_free_struct
  - kernel/acct.c:acct_put
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_put_tree
  - kernel/audit_tree.c:audit_trim_trees
  - kernel/audit_tree.c:prune_one
  - kernel/audit_tree.c:untag_chunk
  - kernel/audit_tree.c:audit_put_chunk
  - kernel/bpf/core.c:bpf_prog_array_free
  - kernel/bpf/lpm_trie.c:trie_delete_elem
  - kernel/bpf/lpm_trie.c:trie_delete_elem
  - kernel/bpf/lpm_trie.c:trie_delete_elem
  - kernel/bpf/lpm_trie.c:trie_update_elem
  - kernel/bpf/sockmap.c:sock_hash_delete_elem
  - kernel/bpf/sockmap.c:sock_hash_free
  - kernel/bpf/sockmap.c:bpf_tcp_close
  - kernel/events/core.c:swevent_hlist_put_cpu
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/vmalloc.c:__free_vmap_area
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
  - fs/timerfd.c:timerfd_release
  - fs/aio.c:ioctx_alloc
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
  - fs/proc/proc_sysctl.c:proc_sys_evict_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_get_acl
  - fs/fuse/dir.c:fuse_dentry_release
  - fs/fuse/inode.c:fuse_free_conn
  - ipc/sem.c:exit_sem
  - ipc/sem.c:freeary
  - security/selinux/netif.c:sel_netif_destroy
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
  - block/genhd.c:disk_release
  - block/genhd.c:disk_expand_part_tbl
  - drivers/iommu/intel-svm.c:intel_svm_unbind_mm
  - drivers/dma-buf/dma-fence.c:dma_fence_release
  - drivers/dma-buf/reservation.c:reservation_object_copy_fences
  - drivers/dma-buf/reservation.c:reservation_object_add_shared_fence
  - drivers/scsi/scsi.c:scsi_update_vpd_page
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext
  - net/socket.c:sock_destroy_inode
  - net/core/gen_estimator.c:gen_kill_estimator
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/net_namespace.c:ops_init
  - net/core/dev.c:netif_set_xps_queue
  - net/core/dev.c:netif_set_xps_queue
  - net/core/dev.c:netif_set_xps_queue
  - net/core/dev.c:netif_reset_xps_queues
  - net/core/dev.c:remove_xps_queue
  - net/core/dev.c:dev_set_alias
  - net/core/dev_addr_lists.c:__hw_addr_flush
  - net/core/neighbour.c:neigh_destroy
  - net/core/rtnetlink.c:rtnl_register_internal
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/fib_notifier.c:fib_notifier_ops_unregister
  - net/core/net-sysfs.c:rx_queue_release
  - net/core/net-sysfs.c:store_rps_map
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_rules_unregister
  - net/core/fib_rules.c:fib_rules_unregister
  - net/core/netprio_cgroup.c:netprio_device_event
  - net/core/lwtunnel.c:lwtstate_free
  - net/sched/cls_api.c:tcf_proto_destroy
  - net/netlink/af_netlink.c:__netlink_change_ngroups
  - net/netlink/af_netlink.c:netlink_release
  - net/ipv4/route.c:find_exception
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
  - net/ipv4/tcp_minisocks.c:tcp_twsk_destructor
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_flush_all
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_msfilter
  - net/ipv4/igmp.c:ip_mc_source
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/cipso_ipv4.c:cipso_v4_delopt
  - net/ipv4/cipso_ipv4.c:cipso_v4_req_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_sock_setattr
  - net/ipv6/af_inet6.c:inet6_destroy_sock
  - net/ipv6/addrconf.c:inet6_ifa_finish_destroy
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_net_exit
  - net/ipv6/addrlabel.c:ip6addrlbl_net_exit
  - net/ipv6/addrlabel.c:ip6addrlbl_add
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:fl6_free_socklist
  - net/ipv6/ip6_flowlabel.c:fl_free
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
```
**Symbols:**

```
ffffffff811066c0-ffffffff811066dc: kfree_call_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void kfree_call_rcu(struct callback_head *head, rcu_callback_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81112360)
Location: kernel/rcu/tree.c:2967
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_free
  - kernel/livepatch/shadow.c:klp_shadow_free_struct
  - kernel/acct.c:acct_put
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
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
  - kernel/events/core.c:swevent_hlist_put_cpu
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/vmalloc.c:__free_vmap_area
  - fs/dcache.c:__d_move
  - fs/dcache.c:release_dentry_name_snapshot
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
  - fs/timerfd.c:timerfd_release
  - fs/aio.c:ioctx_alloc
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
  - fs/proc/proc_sysctl.c:proc_sys_evict_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_get_acl
  - fs/fuse/dir.c:fuse_dentry_release
  - fs/fuse/inode.c:fuse_free_conn
  - ipc/sem.c:exit_sem
  - ipc/sem.c:freeary
  - security/selinux/netif.c:sel_netif_destroy
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
  - block/genhd.c:disk_release
  - block/genhd.c:disk_expand_part_tbl
  - drivers/iommu/intel-svm.c:intel_svm_unbind_mm
  - drivers/dma-buf/dma-fence.c:dma_fence_release
  - drivers/dma-buf/reservation.c:reservation_object_copy_fences
  - drivers/dma-buf/reservation.c:reservation_object_reserve_shared
  - drivers/scsi/scsi.c:scsi_update_vpd_page
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext
  - net/socket.c:sock_destroy_inode
  - net/core/gen_estimator.c:gen_kill_estimator
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/net_namespace.c:ops_init
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:remove_xps_queue
  - net/core/dev.c:dev_set_alias
  - net/core/dev_addr_lists.c:__hw_addr_flush
  - net/core/neighbour.c:neigh_destroy
  - net/core/rtnetlink.c:rtnl_register_internal
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/fib_notifier.c:fib_notifier_ops_unregister
  - net/core/net-sysfs.c:rx_queue_release
  - net/core/net-sysfs.c:store_rps_map
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_rules_unregister
  - net/core/fib_rules.c:fib_rules_unregister
  - net/core/netprio_cgroup.c:netprio_device_event
  - net/core/lwtunnel.c:lwtstate_free
  - net/core/sock_map.c:sk_psock_unlink
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
  - net/sched/cls_api.c:__tcf_block_put
  - net/sched/cls_api.c:tcf_proto_destroy
  - net/netlink/af_netlink.c:__netlink_change_ngroups
  - net/netlink/af_netlink.c:netlink_release
  - net/ipv4/route.c:find_exception
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
  - net/ipv4/tcp_minisocks.c:tcp_twsk_destructor
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
  - net/ipv6/af_inet6.c:inet6_destroy_sock
  - net/ipv6/addrconf.c:inet6_ifa_finish_destroy
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_net_exit
  - net/ipv6/addrlabel.c:ip6addrlbl_net_exit
  - net/ipv6/addrlabel.c:ip6addrlbl_add
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:fl6_free_socklist
  - net/ipv6/ip6_flowlabel.c:fl_free
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
```
**Symbols:**

```
ffffffff81112360-ffffffff81112375: kfree_call_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void kfree_call_rcu(struct callback_head *head, rcu_callback_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8111bc30)
Location: kernel/rcu/tree.c:2603
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_free
  - kernel/livepatch/shadow.c:klp_shadow_free_struct
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
  - kernel/events/core.c:swevent_hlist_put_cpu
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/vmalloc.c:free_vmap_block
  - fs/dcache.c:__d_move
  - fs/dcache.c:release_dentry_name_snapshot
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
  - fs/timerfd.c:timerfd_release
  - fs/aio.c:ioctx_alloc
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
  - fs/ext4/acl.c:ext4_get_acl
  - fs/fuse/dir.c:fuse_dentry_release
  - fs/fuse/inode.c:fuse_free_conn
  - ipc/sem.c:exit_sem
  - ipc/sem.c:freeary
  - security/selinux/netif.c:sel_netif_destroy
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
  - block/genhd.c:disk_release
  - block/genhd.c:disk_expand_part_tbl
  - drivers/iommu/intel-svm.c:intel_svm_unbind_mm
  - drivers/dma-buf/dma-fence.c:dma_fence_free
  - drivers/dma-buf/dma-fence.c:dma_fence_release
  - drivers/dma-buf/reservation.c:reservation_object_copy_fences
  - drivers/dma-buf/reservation.c:reservation_object_reserve_shared
  - drivers/scsi/scsi.c:scsi_update_vpd_page
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext
  - net/core/gen_estimator.c:gen_kill_estimator
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/net_namespace.c:ops_init
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:remove_xps_queue
  - net/core/dev.c:dev_set_alias
  - net/core/dev_addr_lists.c:__hw_addr_flush
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
  - net/core/netprio_cgroup.c:netprio_device_event
  - net/core/lwtunnel.c:lwtstate_free
  - net/core/sock_map.c:sock_hash_free_elem
  - net/core/devlink.c:devlink_dpipe_table_unregister
  - net/core/bpf_sk_storage.c:bpf_sk_storage_free
  - net/core/bpf_sk_storage.c:selem_unlink_sk
  - net/core/bpf_sk_storage.c:__selem_unlink_sk
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
  - net/ipv4/igmp.c:ip_mc_leave_src
  - net/ipv4/cipso_ipv4.c:cipso_v4_delopt
  - net/ipv4/cipso_ipv4.c:cipso_v4_req_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_sock_setattr
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree
  - net/ipv6/af_inet6.c:inet6_destroy_sock
  - net/ipv6/addrconf.c:inet6_ifa_finish_destroy
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_net_exit
  - net/ipv6/addrlabel.c:ip6addrlbl_net_exit
  - net/ipv6/addrlabel.c:ip6addrlbl_add
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
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
**Symbols:**

```
ffffffff8111bc30-ffffffff8111bc45: kfree_call_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void kfree_call_rcu(struct callback_head *head, rcu_callback_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811283c0)
Location: kernel/rcu/tree.c:2663
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_free
  - kernel/livepatch/shadow.c:klp_shadow_free_struct
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
  - kernel/events/core.c:swevent_hlist_put_cpu
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/vmalloc.c:free_vmap_block
  - fs/dcache.c:__d_move
  - fs/dcache.c:release_dentry_name_snapshot
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
  - fs/timerfd.c:timerfd_release
  - fs/aio.c:ioctx_alloc
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
  - fs/ext4/acl.c:ext4_get_acl
  - fs/fuse/inode.c:fuse_free_conn
  - ipc/sem.c:exit_sem
  - ipc/sem.c:freeary
  - security/selinux/netif.c:sel_netif_destroy
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
  - block/genhd.c:disk_release
  - block/genhd.c:disk_expand_part_tbl
  - drivers/iommu/intel-svm.c:intel_svm_unbind_mm
  - drivers/dma-buf/dma-fence.c:dma_fence_free
  - drivers/dma-buf/dma-fence.c:dma_fence_release
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared
  - drivers/scsi/scsi.c:scsi_update_vpd_page
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext
  - net/core/gen_estimator.c:gen_kill_estimator
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/net_namespace.c:ops_init
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:remove_xps_queue
  - net/core/dev.c:dev_set_alias
  - net/core/dev_addr_lists.c:__hw_addr_flush
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
  - net/core/lwtunnel.c:lwtstate_free
  - net/core/sock_map.c:sock_hash_free_elem
  - net/core/devlink.c:devlink_dpipe_table_unregister
  - net/core/bpf_sk_storage.c:bpf_sk_storage_free
  - net/core/bpf_sk_storage.c:selem_unlink_sk
  - net/core/bpf_sk_storage.c:__selem_unlink_sk
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
  - net/ipv4/igmp.c:ip_mc_leave_src
  - net/ipv4/cipso_ipv4.c:cipso_v4_delopt
  - net/ipv4/cipso_ipv4.c:cipso_v4_req_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_sock_setattr
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree
  - net/ipv6/af_inet6.c:inet6_destroy_sock
  - net/ipv6/addrconf.c:inet6_ifa_finish_destroy
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_net_exit
  - net/ipv6/addrlabel.c:ip6addrlbl_net_exit
  - net/ipv6/addrlabel.c:ip6addrlbl_add
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
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
**Symbols:**

```
ffffffff811283c0-ffffffff811283d5: kfree_call_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void kfree_call_rcu(struct callback_head *head, rcu_callback_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811367e0)
Location: kernel/rcu/tree.c:3250
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
  - kernel/events/core.c:swevent_hlist_put_cpu
  - kernel/watch_queue.c:__put_watch_queue
  - kernel/watch_queue.c:__put_watch_queue
  - kernel/watch_queue.c:watch_queue_set_filter
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/vmalloc.c:free_vmap_block
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
  - drivers/iommu/ioasid.c:ioasid_free
  - drivers/iommu/ioasid.c:ioasid_unregister_allocator
  - drivers/iommu/ioasid.c:default_free
  - drivers/iommu/intel/svm.c:intel_svm_unbind_gpasid
  - drivers/dma-buf/dma-fence.c:dma_fence_free
  - drivers/dma-buf/dma-fence.c:dma_fence_release
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
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
  - net/core/bpf_sk_storage.c:selem_unlink_sk
  - net/core/bpf_sk_storage.c:__selem_unlink_sk
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
  - net/ipv4/igmp.c:ip_mc_destroy_dev
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
  - net/ipv6/addrlabel.c:ip6addrlbl_del
  - net/ipv6/addrlabel.c:__ip6addrlbl_add
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
  - net/mptcp/subflow.c:subflow_ulp_release
  - net/mptcp/subflow.c:subflow_drop_ctx
  - net/mptcp/pm_netlink.c:pm_nl_exit_net
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_flush_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr
```
**Symbols:**

```
ffffffff811367e0-ffffffff81136956: kfree_call_rcu (STB_GLOBAL)
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void kfree_call_rcu(struct callback_head *head, rcu_callback_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffff80001018f178)
Location: kernel/rcu/tree.c:2663
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_free
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
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
  - kernel/bpf/lpm_trie.c:trie_update_elem
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
  - kernel/events/core.c:swevent_hlist_put_cpu
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/vmalloc.c:free_vmap_block
  - fs/dcache.c:__d_move
  - fs/dcache.c:release_dentry_name_snapshot
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
  - fs/timerfd.c:timerfd_release
  - fs/aio.c:ioctx_alloc
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:posix_acl_xattr_set
  - fs/posix_acl.c:posix_acl_xattr_get
  - fs/posix_acl.c:posix_acl_from_xattr
  - fs/posix_acl.c:__posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_create
  - fs/posix_acl.c:__posix_acl_create
  - fs/posix_acl.c:__forget_cached_acl
  - fs/posix_acl.c:set_cached_acl
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/proc/proc_sysctl.c:proc_sys_evict_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_get_acl
  - fs/fuse/inode.c:fuse_free_conn
  - ipc/sem.c:exit_sem
  - ipc/sem.c:freeary
  - security/selinux/netif.c:sel_netif_destroy
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
  - block/genhd.c:disk_release
  - block/genhd.c:disk_expand_part_tbl
  - drivers/dma-buf/dma-fence.c:dma_fence_free
  - drivers/dma-buf/dma-fence.c:dma_fence_release
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared
  - drivers/scsi/scsi.c:scsi_update_vpd_page
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext
  - net/core/gen_estimator.c:gen_kill_estimator
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/net_namespace.c:ops_init
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:remove_xps_queue
  - net/core/dev.c:dev_set_alias
  - net/core/dev_addr_lists.c:__hw_addr_flush
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
  - net/core/lwtunnel.c:lwtstate_free
  - net/core/sock_map.c:sock_hash_free_elem
  - net/core/devlink.c:devlink_dpipe_table_unregister
  - net/core/bpf_sk_storage.c:bpf_sk_storage_free
  - net/core/bpf_sk_storage.c:selem_unlink_sk
  - net/core/bpf_sk_storage.c:__selem_unlink_sk
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
  - net/ipv4/igmp.c:ip_mc_leave_src
  - net/ipv4/cipso_ipv4.c:cipso_v4_delopt
  - net/ipv4/cipso_ipv4.c:cipso_v4_req_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_sock_setattr
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree
  - net/ipv6/af_inet6.c:inet6_destroy_sock
  - net/ipv6/addrconf.c:inet6_ifa_finish_destroy
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_net_exit
  - net/ipv6/addrlabel.c:ip6addrlbl_net_exit
  - net/ipv6/addrlabel.c:ip6addrlbl_add
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
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
**Symbols:**

```
ffff80001018f178-ffff80001018f1b0: kfree_call_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void kfree_call_rcu(struct callback_head *head, rcu_callback_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (c03dc610)
Location: kernel/rcu/tree.c:2663
Inline: False
Direct callers:
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
  - kernel/events/core.c:swevent_hlist_put_cpu
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/vmalloc.c:free_vmap_block
  - fs/dcache.c:__d_move
  - fs/dcache.c:release_dentry_name_snapshot
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
  - fs/timerfd.c:timerfd_release
  - fs/aio.c:__se_sys_io_setup
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:posix_acl_xattr_set
  - fs/posix_acl.c:posix_acl_xattr_get
  - fs/posix_acl.c:posix_acl_from_xattr
  - fs/posix_acl.c:__posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_create
  - fs/posix_acl.c:__posix_acl_create
  - fs/posix_acl.c:__forget_cached_acl
  - fs/posix_acl.c:set_cached_acl
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/proc/proc_sysctl.c:proc_sys_evict_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_get_acl
  - fs/fuse/dir.c:fuse_dentry_release
  - fs/fuse/inode.c:fuse_free_conn
  - ipc/sem.c:exit_sem
  - ipc/sem.c:freeary
  - security/selinux/netif.c:sel_netif_destroy
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
  - block/genhd.c:disk_release
  - block/genhd.c:disk_expand_part_tbl
  - drivers/dma-buf/dma-fence.c:dma_fence_free
  - drivers/dma-buf/dma-fence.c:dma_fence_release
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared
  - drivers/scsi/scsi.c:scsi_update_vpd_page
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext
  - drivers/net/tun.c:tun_flow_delete
  - net/core/gen_estimator.c:gen_kill_estimator
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/net_namespace.c:ops_init
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:clean_xps_maps
  - net/core/dev.c:remove_xps_queue
  - net/core/dev.c:dev_set_alias
  - net/core/dev_addr_lists.c:__hw_addr_flush
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
  - net/core/netprio_cgroup.c:netprio_set_prio
  - net/core/lwtunnel.c:lwtstate_free
  - net/core/sock_map.c:sock_hash_free_elem
  - net/core/devlink.c:devlink_dpipe_table_unregister
  - net/core/bpf_sk_storage.c:bpf_sk_storage_free
  - net/core/bpf_sk_storage.c:selem_unlink_sk
  - net/core/bpf_sk_storage.c:__selem_unlink_sk
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
  - net/ipv4/igmp.c:ip_mc_leave_src
  - net/ipv4/cipso_ipv4.c:cipso_v4_delopt
  - net/ipv4/cipso_ipv4.c:cipso_v4_req_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_sock_setattr
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree
  - net/ipv6/af_inet6.c:inet6_destroy_sock
  - net/ipv6/addrconf.c:inet6_ifa_finish_destroy
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_net_exit
  - net/ipv6/addrlabel.c:ip6addrlbl_net_exit
  - net/ipv6/addrlabel.c:ip6addrlbl_add
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
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
**Symbols:**

```
c03dc610-c03dc630: kfree_call_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void kfree_call_rcu(struct callback_head *head, rcu_callback_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (c0000000001e9ab0)
Location: kernel/rcu/tree.c:2663
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_free
  - kernel/livepatch/shadow.c:klp_shadow_free_struct
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
  - kernel/events/core.c:swevent_hlist_put_cpu
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/vmalloc.c:free_vmap_block
  - fs/dcache.c:__d_move
  - fs/dcache.c:release_dentry_name_snapshot
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
  - fs/timerfd.c:timerfd_release
  - fs/aio.c:ioctx_alloc
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
  - fs/ext4/acl.c:ext4_get_acl
  - fs/fuse/inode.c:fuse_free_conn
  - ipc/sem.c:exit_sem
  - ipc/sem.c:freeary
  - security/selinux/netif.c:sel_netif_destroy
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
  - block/genhd.c:disk_release
  - block/genhd.c:disk_expand_part_tbl
  - drivers/dma-buf/dma-fence.c:dma_fence_free
  - drivers/dma-buf/dma-fence.c:dma_fence_release
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared
  - drivers/scsi/scsi.c:scsi_update_vpd_page
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext
  - drivers/net/tun.c:tun_flow_delete
  - net/core/gen_estimator.c:gen_kill_estimator
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/net_namespace.c:ops_init
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:remove_xps_queue
  - net/core/dev.c:dev_set_alias
  - net/core/dev_addr_lists.c:__hw_addr_flush
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
  - net/core/lwtunnel.c:lwtstate_free
  - net/core/sock_map.c:sk_psock_unlink
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
  - net/core/devlink.c:devlink_dpipe_table_unregister
  - net/core/bpf_sk_storage.c:bpf_sk_storage_free
  - net/core/bpf_sk_storage.c:selem_unlink_sk
  - net/core/bpf_sk_storage.c:__selem_unlink_sk
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
  - net/ipv4/igmp.c:ip_mc_leave_src
  - net/ipv4/cipso_ipv4.c:cipso_v4_delopt
  - net/ipv4/cipso_ipv4.c:cipso_v4_req_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_sock_setattr
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree
  - net/ipv6/af_inet6.c:inet6_destroy_sock
  - net/ipv6/addrconf.c:inet6_ifa_finish_destroy
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_net_exit
  - net/ipv6/addrlabel.c:ip6addrlbl_net_exit
  - net/ipv6/addrlabel.c:ip6addrlbl_add
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
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
```
**Symbols:**

```
c0000000001e9ab0-c0000000001e9ac8: kfree_call_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void kfree_call_rcu(struct callback_head *head, rcu_callback_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffe000123366)
Location: kernel/rcu/tree.c:2663
Inline: False
Direct callers:
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
  - kernel/audit_tree.c:free_chunk
  - kernel/bpf/core.c:bpf_prog_array_free
  - kernel/bpf/lpm_trie.c:trie_delete_elem
  - kernel/bpf/lpm_trie.c:trie_delete_elem
  - kernel/bpf/lpm_trie.c:trie_delete_elem
  - kernel/bpf/lpm_trie.c:trie_update_elem
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
  - kernel/events/core.c:swevent_hlist_put_cpu
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/vmalloc.c:free_vmap_block
  - fs/dcache.c:__d_move
  - fs/dcache.c:release_dentry_name_snapshot
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
  - fs/timerfd.c:timerfd_release
  - fs/aio.c:__se_sys_io_setup
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:posix_acl_xattr_set
  - fs/posix_acl.c:posix_acl_xattr_get
  - fs/posix_acl.c:posix_acl_from_xattr
  - fs/posix_acl.c:__posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_create
  - fs/posix_acl.c:__posix_acl_create
  - fs/posix_acl.c:__forget_cached_acl
  - fs/posix_acl.c:set_cached_acl
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/proc/proc_sysctl.c:proc_sys_evict_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_get_acl
  - fs/fuse/inode.c:fuse_free_conn
  - ipc/sem.c:exit_sem
  - ipc/sem.c:freeary
  - security/keys/keyring.c:key_remove_domain
  - security/selinux/netif.c:sel_netif_destroy
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
  - block/genhd.c:disk_release
  - block/genhd.c:disk_expand_part_tbl
  - drivers/dma-buf/dma-fence.c:dma_fence_free
  - drivers/dma-buf/dma-fence.c:dma_fence_release
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared
  - drivers/scsi/scsi.c:scsi_update_vpd_page
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext
  - drivers/net/tun.c:tun_flow_delete
  - net/core/gen_estimator.c:gen_kill_estimator
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/net_namespace.c:ops_init
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:clean_xps_maps
  - net/core/dev.c:remove_xps_queue
  - net/core/dev.c:dev_set_alias
  - net/core/dev_addr_lists.c:__hw_addr_flush
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
  - net/core/lwtunnel.c:lwtstate_free
  - net/core/sock_map.c:sk_psock_unlink
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
  - net/core/devlink.c:devlink_dpipe_table_unregister
  - net/core/bpf_sk_storage.c:bpf_sk_storage_free
  - net/core/bpf_sk_storage.c:selem_unlink_sk
  - net/core/bpf_sk_storage.c:__selem_unlink_sk
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
  - net/ipv4/igmp.c:ip_mc_leave_src
  - net/ipv4/cipso_ipv4.c:cipso_v4_delopt
  - net/ipv4/cipso_ipv4.c:cipso_v4_req_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_sock_setattr
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree
  - net/ipv6/af_inet6.c:inet6_destroy_sock
  - net/ipv6/addrconf.c:inet6_ifa_finish_destroy
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_net_exit
  - net/ipv6/addrlabel.c:ip6addrlbl_net_exit
  - net/ipv6/addrlabel.c:ip6addrlbl_add
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:__ipv6_sock_mc_close
  - net/ipv6/mcast.c:ipv6_sock_mc_drop
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
```
**Symbols:**

```
ffffffe000123366-ffffffe00012339a: kfree_call_rcu (STB_GLOBAL)
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
void kfree_call_rcu(struct callback_head *head, rcu_callback_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811209a0)
Location: kernel/rcu/tree.c:2663
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_free
  - kernel/livepatch/shadow.c:klp_shadow_free_struct
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
  - kernel/events/core.c:swevent_hlist_put_cpu
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/vmalloc.c:free_vmap_block
  - fs/dcache.c:__d_move
  - fs/dcache.c:release_dentry_name_snapshot
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
  - fs/timerfd.c:timerfd_release
  - fs/aio.c:ioctx_alloc
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
  - fs/ext4/acl.c:ext4_get_acl
  - fs/fuse/inode.c:fuse_free_conn
  - ipc/sem.c:exit_sem
  - ipc/sem.c:freeary
  - security/selinux/netif.c:sel_netif_destroy
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
  - block/genhd.c:disk_release
  - block/genhd.c:disk_expand_part_tbl
  - drivers/iommu/intel-svm.c:intel_svm_unbind_mm
  - drivers/dma-buf/dma-fence.c:dma_fence_free
  - drivers/dma-buf/dma-fence.c:dma_fence_release
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared
  - drivers/scsi/scsi.c:scsi_update_vpd_page
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext
  - net/core/gen_estimator.c:gen_kill_estimator
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/net_namespace.c:ops_init
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:remove_xps_queue
  - net/core/dev.c:dev_set_alias
  - net/core/dev_addr_lists.c:__hw_addr_flush
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
  - net/core/lwtunnel.c:lwtstate_free
  - net/core/sock_map.c:sock_hash_free_elem
  - net/core/devlink.c:devlink_dpipe_table_unregister
  - net/core/bpf_sk_storage.c:bpf_sk_storage_free
  - net/core/bpf_sk_storage.c:selem_unlink_sk
  - net/core/bpf_sk_storage.c:__selem_unlink_sk
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
  - net/ipv4/igmp.c:ip_mc_leave_src
  - net/ipv4/cipso_ipv4.c:cipso_v4_delopt
  - net/ipv4/cipso_ipv4.c:cipso_v4_req_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_sock_setattr
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree
  - net/ipv6/af_inet6.c:inet6_destroy_sock
  - net/ipv6/addrconf.c:inet6_ifa_finish_destroy
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_net_exit
  - net/ipv6/addrlabel.c:ip6addrlbl_net_exit
  - net/ipv6/addrlabel.c:ip6addrlbl_add
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
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
**Symbols:**

```
ffffffff811209a0-ffffffff811209b5: kfree_call_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void kfree_call_rcu(struct callback_head *head, rcu_callback_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81113ea0)
Location: kernel/rcu/tree.c:2663
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_free
  - kernel/livepatch/shadow.c:klp_shadow_free_struct
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
  - kernel/events/core.c:swevent_hlist_put_cpu
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/vmalloc.c:free_vmap_block
  - fs/dcache.c:__d_move
  - fs/dcache.c:release_dentry_name_snapshot
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
  - fs/timerfd.c:timerfd_release
  - fs/aio.c:ioctx_alloc
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
  - fs/ext4/acl.c:ext4_get_acl
  - fs/fuse/inode.c:fuse_free_conn
  - ipc/sem.c:exit_sem
  - ipc/sem.c:freeary
  - security/selinux/netif.c:sel_netif_destroy
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
  - block/genhd.c:disk_release
  - block/genhd.c:disk_expand_part_tbl
  - drivers/iommu/intel-svm.c:intel_svm_unbind_mm
  - drivers/dma-buf/dma-fence.c:dma_fence_free
  - drivers/dma-buf/dma-fence.c:dma_fence_release
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared
  - drivers/scsi/scsi.c:scsi_update_vpd_page
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext
  - drivers/net/vxlan.c:vxlan_nl2conf
  - drivers/net/vxlan.c:vxlan_nl2conf
  - drivers/hv/vmbus_drv.c:vmbus_chan_release
  - net/core/gen_estimator.c:gen_kill_estimator
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/net_namespace.c:ops_init
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:remove_xps_queue
  - net/core/dev.c:dev_set_alias
  - net/core/dev_addr_lists.c:__hw_addr_flush
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
  - net/core/lwtunnel.c:lwtstate_free
  - net/core/sock_map.c:sock_hash_free_elem
  - net/core/devlink.c:devlink_dpipe_table_unregister
  - net/core/bpf_sk_storage.c:bpf_sk_storage_free
  - net/core/bpf_sk_storage.c:selem_unlink_sk
  - net/core/bpf_sk_storage.c:__selem_unlink_sk
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
  - net/ipv4/igmp.c:ip_mc_leave_src
  - net/ipv4/cipso_ipv4.c:cipso_v4_delopt
  - net/ipv4/cipso_ipv4.c:cipso_v4_req_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_sock_setattr
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree
  - net/ipv6/af_inet6.c:inet6_destroy_sock
  - net/ipv6/addrconf.c:inet6_ifa_finish_destroy
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_net_exit
  - net/ipv6/addrlabel.c:ip6addrlbl_net_exit
  - net/ipv6/addrlabel.c:ip6addrlbl_add
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
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
**Symbols:**

```
ffffffff81113ea0-ffffffff81113eb5: kfree_call_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void kfree_call_rcu(struct callback_head *head, rcu_callback_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8111e890)
Location: kernel/rcu/tree.c:2663
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_free
  - kernel/livepatch/shadow.c:klp_shadow_free_struct
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
  - kernel/events/core.c:swevent_hlist_put_cpu
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/vmalloc.c:free_vmap_block
  - fs/dcache.c:__d_move
  - fs/dcache.c:release_dentry_name_snapshot
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
  - fs/timerfd.c:timerfd_release
  - fs/aio.c:ioctx_alloc
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
  - fs/ext4/acl.c:ext4_get_acl
  - fs/fuse/inode.c:fuse_free_conn
  - ipc/sem.c:exit_sem
  - ipc/sem.c:freeary
  - security/selinux/netif.c:sel_netif_destroy
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
  - block/genhd.c:disk_release
  - block/genhd.c:disk_expand_part_tbl
  - drivers/iommu/intel-svm.c:intel_svm_unbind_mm
  - drivers/dma-buf/dma-fence.c:dma_fence_free
  - drivers/dma-buf/dma-fence.c:dma_fence_release
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared
  - drivers/scsi/scsi.c:scsi_update_vpd_page
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext
  - net/core/gen_estimator.c:gen_kill_estimator
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/net_namespace.c:ops_init
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:remove_xps_queue
  - net/core/dev.c:dev_set_alias
  - net/core/dev_addr_lists.c:__hw_addr_flush
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
  - net/core/lwtunnel.c:lwtstate_free
  - net/core/sock_map.c:sock_hash_free_elem
  - net/core/devlink.c:devlink_dpipe_table_unregister
  - net/core/bpf_sk_storage.c:bpf_sk_storage_free
  - net/core/bpf_sk_storage.c:selem_unlink_sk
  - net/core/bpf_sk_storage.c:__selem_unlink_sk
  - net/sched/cls_api.c:__tcf_chain_put
  - net/sched/cls_api.c:__tcf_chain_put
  - net/sched/cls_api.c:tcf_proto_destroy
  - net/netlink/af_netlink.c:__netlink_change_ngroups
  - net/netlink/af_netlink.c:netlink_release
  - net/netfilter/nf_conntrack_core.c:nf_conntrack_free
  - net/netfilter/nf_conntrack_core.c:nf_ct_tmpl_free
  - net/netfilter/nf_conntrack_extend.c:nf_ct_ext_add
  - net/netfilter/nf_conntrack_proto_gre.c:nf_ct_gre_keymap_destroy
  - net/netfilter/nf_conntrack_proto_gre.c:nf_ct_gre_keymap_flush
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
  - net/ipv4/igmp.c:ip_mc_leave_src
  - net/ipv4/cipso_ipv4.c:cipso_v4_delopt
  - net/ipv4/cipso_ipv4.c:cipso_v4_req_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_sock_setattr
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree
  - net/ipv6/af_inet6.c:inet6_destroy_sock
  - net/ipv6/addrconf.c:inet6_ifa_finish_destroy
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_net_exit
  - net/ipv6/addrlabel.c:ip6addrlbl_net_exit
  - net/ipv6/addrlabel.c:ip6addrlbl_add
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
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
**Symbols:**

```
ffffffff8111e890-ffffffff8111e8a5: kfree_call_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void kfree_call_rcu(struct callback_head *head, rcu_callback_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8112abc0)
Location: kernel/rcu/tree.c:2663
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_free
  - kernel/livepatch/shadow.c:klp_shadow_free_struct
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
  - kernel/events/core.c:swevent_hlist_put_cpu
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/vmalloc.c:free_vmap_block
  - fs/dcache.c:__d_move
  - fs/dcache.c:release_dentry_name_snapshot
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
  - fs/timerfd.c:timerfd_release
  - fs/aio.c:ioctx_alloc
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
  - fs/ext4/acl.c:ext4_get_acl
  - fs/fuse/inode.c:fuse_free_conn
  - ipc/sem.c:exit_sem
  - ipc/sem.c:freeary
  - security/selinux/netif.c:sel_netif_destroy
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
  - block/genhd.c:disk_release
  - block/genhd.c:disk_expand_part_tbl
  - drivers/iommu/intel-svm.c:intel_svm_unbind_mm
  - drivers/dma-buf/dma-fence.c:dma_fence_free
  - drivers/dma-buf/dma-fence.c:dma_fence_release
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared
  - drivers/scsi/scsi.c:scsi_update_vpd_page
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext
  - net/core/gen_estimator.c:gen_kill_estimator
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/net_namespace.c:ops_init
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:remove_xps_queue
  - net/core/dev.c:dev_set_alias
  - net/core/dev_addr_lists.c:__hw_addr_flush
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
  - net/core/lwtunnel.c:lwtstate_free
  - net/core/sock_map.c:sock_hash_free_elem
  - net/core/devlink.c:devlink_dpipe_table_unregister
  - net/core/bpf_sk_storage.c:bpf_sk_storage_free
  - net/core/bpf_sk_storage.c:selem_unlink_sk
  - net/core/bpf_sk_storage.c:__selem_unlink_sk
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
  - net/ipv4/igmp.c:ip_mc_leave_src
  - net/ipv4/cipso_ipv4.c:cipso_v4_delopt
  - net/ipv4/cipso_ipv4.c:cipso_v4_req_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_sock_setattr
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_gc_tree
  - net/ipv6/af_inet6.c:inet6_destroy_sock
  - net/ipv6/addrconf.c:inet6_ifa_finish_destroy
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_net_exit
  - net/ipv6/addrlabel.c:ip6addrlbl_net_exit
  - net/ipv6/addrlabel.c:ip6addrlbl_add
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
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
**Symbols:**

```
ffffffff8112abc0-ffffffff8112abd5: kfree_call_rcu (STB_GLOBAL)
```
</details>
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
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
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
