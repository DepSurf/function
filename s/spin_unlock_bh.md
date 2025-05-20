# Function: <code>spin_unlock_bh</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff81112a79)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_idr_remove
  - kernel/cgroup.c:cgroup_idr_replace
  - kernel/cgroup.c:cgroup_path_ns
  - kernel/cgroup.c:task_cgroup_path
  - kernel/cgroup.c:cgroup_release_agent
  - kernel/cgroup.c:rebind_subsystems
  - kernel/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup.c:css_free_work_fn
  - kernel/cgroup.c:find_css_set
  - kernel/cgroup.c:find_css_set
  - kernel/cgroup.c:cgroup_taskset_migrate
  - kernel/cgroup.c:cgroup_taskset_migrate
  - kernel/cgroup.c:cgroup_migrate
  - kernel/cgroup.c:cgroup_attach_task
  - kernel/cgroup.c:cgroup_attach_task_all
  - kernel/cgroup.c:__cgroup_procs_write
  - kernel/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup.c:cgroup_update_dfl_csses
  - kernel/cgroup.c:cgroup_setup_root
  - kernel/cgroup.c:cgroup_mount
  - kernel/cgroup.c:cgroup_mount
  - kernel/cgroup.c:css_task_iter_start
  - kernel/cgroup.c:css_task_iter_next
  - kernel/cgroup.c:css_task_iter_end
  - kernel/cgroup.c:pidlist_array_load
  - kernel/cgroup.c:cgroup_transfer_tasks
  - kernel/cgroup.c:proc_cgroup_show
  - kernel/cgroup.c:cgroup_post_fork
  - kernel/cgroup.c:cgroup_exit
  - kernel/cgroup.c:copy_cgroup_ns
```
```
In kernel/padata.c (ffffffff81189cfd)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - kernel/padata.c:padata_reorder
  - kernel/padata.c:padata_reorder
```
```
In mm/page-writeback.c (ffffffff81197e80)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - mm/page-writeback.c:bdi_set_max_ratio
  - mm/page-writeback.c:bdi_set_min_ratio
```
```
In mm/backing-dev.c (ffffffff811ae196)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_shutdown
  - mm/backing-dev.c:wb_shutdown
  - mm/backing-dev.c:bdi_register
  - mm/backing-dev.c:wb_wakeup_delayed
  - mm/backing-dev.c:bdi_unregister
```
```
In fs/fs-writeback.c (ffffffff81235ce0)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_wakeup
  - fs/fs-writeback.c:wb_queue_work
  - fs/fs-writeback.c:wb_workfn
```
```
In security/selinux/netif.c (ffffffff8134ce50)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_netdev_notifier_handler
  - security/selinux/netif.c:sel_netif_sid
  - security/selinux/netif.c:sel_netif_flush
```
```
In security/selinux/netnode.c (ffffffff8134d19e)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_sid
  - security/selinux/netnode.c:sel_netnode_sid
  - security/selinux/netnode.c:sel_netnode_flush
```
```
In security/selinux/netport.c (ffffffff8134d48a)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_sid
  - security/selinux/netport.c:sel_netport_sid
  - security/selinux/netport.c:sel_netport_flush
```
```
In crypto/chainiv.c (ffffffff813a1f8d)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - crypto/chainiv.c:chainiv_givencrypt
  - crypto/chainiv.c:async_chainiv_givencrypt
  - crypto/chainiv.c:async_chainiv_do_postponed
```
```
In block/genhd.c (ffffffff813caafc)
Location: include/linux/spinlock.h:350
Inline: True
```
```
In lib/rhashtable.c (ffffffff81400553)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - lib/rhashtable.c:rht_deferred_worker
```
```
In drivers/connector/cn_queue.c (ffffffff8154180c)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_add_callback
  - drivers/connector/cn_queue.c:cn_queue_del_callback
  - drivers/connector/cn_queue.c:cn_queue_free_dev
```
```
In drivers/connector/connector.c (ffffffff81541b32)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_proc_show
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/net/tun.c (ffffffff815ee070)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_flow_flush
  - drivers/net/tun.c:tun_flow_cleanup
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:__tun_detach
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff815f4baa)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_get_stats64
  - drivers/net/ppp/ppp_generic.c:ppp_get_stats64
  - drivers/net/ppp/ppp_generic.c:ppp_ccp_closed
  - drivers/net/ppp/ppp_generic.c:ppp_ccp_closed
  - drivers/net/ppp/ppp_generic.c:ppp_set_compress
  - drivers/net/ppp/ppp_generic.c:ppp_set_compress
  - drivers/net/ppp/ppp_generic.c:ppp_disconnect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_disconnect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_push
  - drivers/net/ppp/ppp_generic.c:ppp_push
  - drivers/net/ppp/ppp_generic.c:ppp_push
  - drivers/net/ppp/ppp_generic.c:ppp_push
  - drivers/net/ppp/ppp_generic.c:ppp_push
  - drivers/net/ppp/ppp_generic.c:ppp_dev_uninit
  - drivers/net/ppp/ppp_generic.c:ppp_dev_uninit
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_input_error
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
```
In drivers/net/xen-netfront.c (ffffffff815fc3b3)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:netback_changed
  - drivers/net/xen-netfront.c:xennet_open
```
```
In net/core/sock.c (ffffffff81700f90)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/core/sock.c:__lock_sock
  - net/core/sock.c:release_sock
```
```
In net/core/request_sock.c (ffffffff81704c4f)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/core/datagram.c (ffffffff8170d07d)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/core/datagram.c:skb_free_datagram_locked
  - net/core/datagram.c:skb_kill_datagram
```
```
In net/core/gen_stats.c (ffffffff8170efcd)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/core/gen_stats.c:gnet_stats_start_copy_compat
  - net/core/gen_stats.c:gnet_stats_copy_basic
  - net/core/gen_stats.c:gnet_stats_copy_queue
  - net/core/gen_stats.c:gnet_stats_finish_copy
  - net/core/gen_stats.c:gnet_stats_finish_copy
```
```
In net/core/gen_estimator.c (ffffffff8170f66d)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_kill_estimator
  - net/core/gen_estimator.c:gen_estimator_active
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/dev.c (ffffffff81715ae0)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:dev_set_rx_mode
```
```
In net/core/dev_addr_lists.c (ffffffff8172285a)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:dev_uc_flush
  - net/core/dev_addr_lists.c:dev_mc_flush
  - net/core/dev_addr_lists.c:dev_uc_add_excl
  - net/core/dev_addr_lists.c:dev_uc_add
  - net/core/dev_addr_lists.c:dev_mc_add_excl
  - net/core/dev_addr_lists.c:__dev_mc_add
  - net/core/dev_addr_lists.c:dev_uc_del
  - net/core/dev_addr_lists.c:__dev_mc_del
```
```
In net/core/dst.c (ffffffff817239c4)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/core/dst.c:dst_dev_event
  - net/core/dst.c:__dst_free
  - net/core/dst.c:dst_gc_task
  - net/core/dst.c:dst_gc_task
```
```
In net/core/neighbour.c (ffffffff81728886)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_update
```
```
In net/core/rtnetlink.c (ffffffff8172d916)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_fdb_dump
```
```
In net/core/flow.c (ffffffff817345c2)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_gc_task
```
```
In net/core/net-procfs.c (ffffffff81737a1f)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/core/net-procfs.c:dev_mc_seq_show
```
```
In net/sched/sch_generic.c (ffffffff81740d12)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_graft_qdisc
  - net/sched/sch_generic.c:dev_deactivate_many
```
```
In net/sched/sch_mq.c (ffffffff81742235)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump
```
```
In net/sched/sch_api.c (ffffffff817446da)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_grow
```
```
In net/sched/cls_api.c (ffffffff81745f1d)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_change
```
```
In net/sched/act_api.c (ffffffff81746c63)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_hash_lookup
  - net/sched/act_api.c:tcf_hash_insert
```
```
In net/netlink/af_netlink.c (ffffffff8174a733)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_set_ring
  - net/netlink/af_netlink.c:__netlink_sendskb
  - net/netlink/af_netlink.c:__netlink_sendskb
  - net/netlink/af_netlink.c:__netlink_alloc_skb
  - net/netlink/af_netlink.c:__netlink_alloc_skb
  - net/netlink/af_netlink.c:__netlink_alloc_skb
  - net/netlink/af_netlink.c:netlink_poll
  - net/netlink/af_netlink.c:netlink_poll
  - net/netlink/af_netlink.c:netlink_insert
  - net/netlink/af_netlink.c:netlink_insert
  - net/netlink/af_netlink.c:netlink_insert
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/route.c (ffffffff81752fbd)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_add_uncached_list
  - net/ipv4/route.c:ipv4_dst_destroy
  - net/ipv4/route.c:rt_set_nexthop
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:rt_flush_dev
```
```
In net/ipv4/inetpeer.c (ffffffff81757d58)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inetpeer_gc_worker
  - net/ipv4/inetpeer.c:inetpeer_gc_worker
  - net/ipv4/inetpeer.c:inetpeer_inval_rcu
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
```
```
In net/ipv4/ip_sockglue.c (ffffffff81760803)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_ra_control
  - net/ipv4/ip_sockglue.c:ip_ra_control
  - net/ipv4/ip_sockglue.c:ip_ra_control
  - net/ipv4/ip_sockglue.c:ip_ra_control
```
```
In net/ipv4/inet_hashtables.c (ffffffff8176206e)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81764c5e)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffff81765b21)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_ioctl
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8177a9a1)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_seq_stop
  - net/ipv4/tcp_ipv4.c:tcp_seq_stop
  - net/ipv4/tcp_ipv4.c:established_get_next
```
```
In net/ipv4/tcp_metrics.c (ffffffff81780dfc)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_flush_all
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
```
```
In net/ipv4/raw.c (ffffffff81784be1)
Location: include/linux/spinlock.h:350
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81785ef4)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_seq_stop
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_unhash
  - net/ipv4/udp.c:udp_get_next
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:first_packet_length
```
```
In net/ipv4/icmp.c (ffffffff8178e6e5)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_send
```
```
In net/ipv4/af_inet.c (ffffffff81792f15)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_register_protosw
```
```
In net/ipv4/igmp.c (ffffffff8179516a)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_mcf_seq_stop
  - net/ipv4/igmp.c:igmp_stop_timer
  - net/ipv4/igmp.c:igmp_mcf_seq_next
  - net/ipv4/igmp.c:ip_mc_del_src
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:ip_mc_add_src
  - net/ipv4/igmp.c:ip_mc_inc_group
  - net/ipv4/igmp.c:igmp_group_dropped
  - net/ipv4/igmp.c:igmp_group_dropped
  - net/ipv4/igmp.c:igmpv3_clear_delrec
  - net/ipv4/igmp.c:igmpv3_clear_delrec
  - net/ipv4/igmp.c:igmp_mcf_seq_start
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
```
```
In net/ipv4/fib_semantics.c (ffffffff8179c50a)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/inet_fragment.c (ffffffff817a1be7)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_worker
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff817a561a)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
```
In net/ipv4/ipmr.c (ffffffff817a710c)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_seq_stop
  - net/ipv4/ipmr.c:ipmr_mfc_seq_next
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
```
```
In net/ipv4/cipso_ipv4.c (ffffffff817ad8d6)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_invalidate
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff817b3905)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
```
```
In net/xfrm/xfrm_state.c (ffffffff817b6c2b)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_sad_getinfo
  - net/xfrm/xfrm_state.c:xfrm_state_lookup_byspi
  - net/xfrm/xfrm_state.c:xfrm_state_lookup_byspi
  - net/xfrm/xfrm_state.c:xfrm_register_km
  - net/xfrm/xfrm_state.c:xfrm_state_register_afinfo
  - net/xfrm/xfrm_state.c:xfrm_register_type
  - net/xfrm/xfrm_state.c:xfrm_unregister_type
  - net/xfrm/xfrm_state.c:xfrm_register_mode
  - net/xfrm/xfrm_state.c:xfrm_unregister_mode
  - net/xfrm/xfrm_state.c:__xfrm_state_destroy
  - net/xfrm/xfrm_state.c:xfrm_state_walk_done
  - net/xfrm/xfrm_state.c:xfrm_unregister_km
  - net/xfrm/xfrm_state.c:xfrm_state_unregister_afinfo
  - net/xfrm/xfrm_state.c:xfrm_state_gc_task
  - net/xfrm/xfrm_state.c:xfrm_find_acq_byseq
  - net/xfrm/xfrm_state.c:xfrm_state_walk
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
  - net/xfrm/xfrm_state.c:xfrm_state_delete
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_lookup
  - net/xfrm/xfrm_state.c:xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_find_acq
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_mtu
```
```
In net/xfrm/xfrm_input.c (ffffffff817bb6cf)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input_register_afinfo
  - net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo
```
```
In net/xfrm/xfrm_output.c (ffffffff817bc24f)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/af_inet6.c (ffffffff817c30bf)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_register_protosw
```
```
In net/ipv6/addrconf.c (ffffffff817c978b)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_generate_stable_address
  - net/ipv6/addrconf.c:addrconf_dad_start
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:add_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_cleanup
```
```
In net/ipv6/route.c (ffffffff817d52ec)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_dst_destroy
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:icmp6_dst_gc
  - net/ipv6/route.c:rt6_ifdown
  - net/ipv6/route.c:rt6_ifdown
```
```
In net/ipv6/ip6_fib.c (ffffffff817dc034)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_run_gc
```
```
In net/ipv6/udp.c (ffffffff817e2d4d)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff817e5afc)
Location: include/linux/spinlock.h:350
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff817e7ada)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_echo_reply
```
```
In net/ipv6/mcast.c (ffffffff817e8c6a)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mcf_seq_stop
  - net/ipv6/mcast.c:igmp6_mcf_seq_next
  - net/ipv6/mcast.c:ip6_mc_del_src
  - net/ipv6/mcast.c:ip6_mc_del_src
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:mld_send_report
  - net/ipv6/mcast.c:mld_send_report
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/mcast.c:igmp6_group_added
  - net/ipv6/mcast.c:igmp6_group_added
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:igmp6_mcf_seq_start
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:ipv6_dev_mc_inc
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff817f5e5e)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:fl_release
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6_flowlabel.c:fl6_renew
  - net/ipv6/ip6_flowlabel.c:fl6_free_socklist
  - net/ipv6/ip6_flowlabel.c:fl6_free_socklist
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
```
```
In net/ipv6/ip6mr.c (ffffffff817f88f7)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ipmr_mfc_seq_next
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
```
In net/packet/af_packet.c (ffffffff81803215)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_ioctl
  - net/packet/af_packet.c:packet_getsockopt
  - net/packet/af_packet.c:packet_rcv_has_room
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_poll
```
```
In net/dcb/dcbnl.c (ffffffff81812b00)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_getapp
  - net/dcb/dcbnl.c:dcb_ieee_getapp_mask
  - net/dcb/dcbnl.c:dcb_setapp
  - net/dcb/dcbnl.c:dcb_ieee_setapp
  - net/dcb/dcbnl.c:dcb_ieee_delapp
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff8111a2d3)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - kernel/cgroup.c:css_release_work_fn
  - kernel/cgroup.c:css_free_work_fn
  - kernel/cgroup.c:cgroup_idr_replace
```
```
In kernel/padata.c (ffffffff8119c3fd)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - kernel/padata.c:padata_reorder
  - kernel/padata.c:padata_reorder
```
```
In mm/page-writeback.c (ffffffff811acde1)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - mm/page-writeback.c:bdi_set_max_ratio
  - mm/page-writeback.c:bdi_set_min_ratio
```
```
In mm/backing-dev.c (ffffffff811c8c1a)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:bdi_register
  - mm/backing-dev.c:wb_wakeup_delayed
```
```
In fs/fs-writeback.c (ffffffff81264691)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_queue_work
  - fs/fs-writeback.c:wb_wakeup
```
```
In security/selinux/netif.c (ffffffff81382e00)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_netdev_notifier_handler
  - security/selinux/netif.c:sel_netif_flush
  - security/selinux/netif.c:sel_netif_sid
```
```
In security/selinux/netnode.c (ffffffff81383388)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_flush
  - security/selinux/netnode.c:sel_netnode_sid
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (ffffffff81383608)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_flush
  - security/selinux/netport.c:sel_netport_sid
  - security/selinux/netport.c:sel_netport_sid
```
```
In security/apparmor/policy_unpack.c (ffffffff813bc0c5)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In block/genhd.c (ffffffff8140edcc)
Location: include/linux/spinlock.h:350
Inline: True
```
```
In lib/rhashtable.c (ffffffff81448196)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - lib/rhashtable.c:rht_deferred_worker
```
```
In drivers/connector/cn_queue.c (ffffffff81593357)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_free_dev
  - drivers/connector/cn_queue.c:cn_queue_del_callback
  - drivers/connector/cn_queue.c:cn_queue_add_callback
```
```
In drivers/connector/connector.c (ffffffff81593476)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_proc_show
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/net/tun.c (ffffffff8164dfe9)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_flow_cleanup
  - drivers/net/tun.c:tun_flow_flush
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff816557b3)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_disconnect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_disconnect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_ccp_closed
  - drivers/net/ppp/ppp_generic.c:ppp_ccp_closed
  - drivers/net/ppp/ppp_generic.c:ppp_set_compress
  - drivers/net/ppp/ppp_generic.c:ppp_set_compress
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_input_error
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_push
  - drivers/net/ppp/ppp_generic.c:ppp_push
  - drivers/net/ppp/ppp_generic.c:ppp_push
  - drivers/net/ppp/ppp_generic.c:ppp_push
  - drivers/net/ppp/ppp_generic.c:ppp_push
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_dev_uninit
  - drivers/net/ppp/ppp_generic.c:ppp_dev_uninit
  - drivers/net/ppp/ppp_generic.c:ppp_get_stats64
  - drivers/net/ppp/ppp_generic.c:ppp_get_stats64
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_poll
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - drivers/net/ppp/ppp_generic.c:ppp_read
```
```
In drivers/net/xen-netfront.c (ffffffff8165d205)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:netback_changed
  - drivers/net/xen-netfront.c:xennet_open
```
```
In net/core/sock.c (ffffffff81769584)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/core/sock.c:release_sock
  - net/core/sock.c:__sk_flush_backlog
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__lock_sock
```
```
In net/core/request_sock.c (ffffffff8176b83f)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/core/datagram.c (ffffffff817754f4)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/core/datagram.c:skb_kill_datagram
  - net/core/datagram.c:__skb_free_datagram_locked
```
```
In net/core/gen_stats.c (ffffffff81776bb3)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/core/gen_stats.c:gnet_stats_finish_copy
  - net/core/gen_stats.c:gnet_stats_finish_copy
  - net/core/gen_stats.c:gnet_stats_copy_queue
  - net/core/gen_stats.c:gnet_stats_copy_basic
  - net/core/gen_stats.c:gnet_stats_start_copy_compat
```
```
In net/core/gen_estimator.c (ffffffff81777024)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_estimator_active
  - net/core/gen_estimator.c:gen_kill_estimator
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/dev.c (ffffffff817862d6)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/core/dev.c:dev_set_rx_mode
  - net/core/dev.c:netif_set_real_num_tx_queues
```
```
In net/core/dev_addr_lists.c (ffffffff8178c2ea)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:dev_mc_flush
  - net/core/dev_addr_lists.c:__dev_mc_del
  - net/core/dev_addr_lists.c:__dev_mc_add
  - net/core/dev_addr_lists.c:dev_mc_add_excl
  - net/core/dev_addr_lists.c:dev_uc_flush
  - net/core/dev_addr_lists.c:dev_uc_del
  - net/core/dev_addr_lists.c:dev_uc_add
  - net/core/dev_addr_lists.c:dev_uc_add_excl
```
```
In net/core/dst.c (ffffffff8178d41c)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/core/dst.c:dst_dev_event
  - net/core/dst.c:__dst_free
  - net/core/dst.c:dst_gc_task
  - net/core/dst.c:dst_gc_task
```
```
In net/core/neighbour.c (ffffffff817923dc)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_update
```
```
In net/core/rtnetlink.c (ffffffff8179719d)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_fdb_dump
```
```
In net/core/sock_reuseport.c (ffffffff8179fec9)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_attach_prog
  - net/core/sock_reuseport.c:reuseport_detach_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_alloc
  - net/core/sock_reuseport.c:reuseport_alloc
```
```
In net/core/flow.c (ffffffff817a0e7a)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_gc_task
```
```
In net/core/net-procfs.c (ffffffff817a3ce1)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/core/net-procfs.c:dev_mc_seq_show
```
```
In net/sched/sch_generic.c (ffffffff817aec29)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_graft_qdisc
```
```
In net/sched/sch_mq.c (ffffffff817af0c5)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump
```
```
In net/sched/sch_api.c (ffffffff817b0a54)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_grow
```
```
In net/sched/cls_api.c (ffffffff817b2f30)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_change
```
```
In net/sched/act_api.c (ffffffff817b406a)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_hash_insert
  - net/sched/act_api.c:tcf_hash_lookup
```
```
In net/netlink/af_netlink.c (ffffffff817ba057)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_insert
  - net/netlink/af_netlink.c:netlink_insert
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/ipv4/route.c (ffffffff817c3d6f)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_flush_dev
  - net/ipv4/route.c:ipv4_dst_destroy
  - net/ipv4/route.c:rt_add_uncached_list
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/inetpeer.c (ffffffff817c427d)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
  - net/ipv4/inetpeer.c:inetpeer_inval_rcu
  - net/ipv4/inetpeer.c:inetpeer_gc_worker
  - net/ipv4/inetpeer.c:inetpeer_gc_worker
```
```
In net/ipv4/ip_sockglue.c (ffffffff817ccb23)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_ra_control
  - net/ipv4/ip_sockglue.c:ip_ra_control
  - net/ipv4/ip_sockglue.c:ip_ra_control
  - net/ipv4/ip_sockglue.c:ip_ra_control
```
```
In net/ipv4/inet_hashtables.c (ffffffff817cf678)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_unhash
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff817cf8ce)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:__inet_twsk_hashdance
```
```
In net/ipv4/inet_connection_sock.c (ffffffff817d11ce)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp.c (ffffffff817d202b)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_ioctl
```
```
In net/ipv4/tcp_ipv4.c (ffffffff817e7c85)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_seq_stop
  - net/ipv4/tcp_ipv4.c:tcp_seq_stop
  - net/ipv4/tcp_ipv4.c:established_get_next
```
```
In net/ipv4/tcp_metrics.c (ffffffff817ee577)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_flush_all
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/raw.c (ffffffff817f2161)
Location: include/linux/spinlock.h:350
Inline: True
```
```
In net/ipv4/udp.c (ffffffff817f3497)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_seq_stop
  - net/ipv4/udp.c:udp_get_next
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_lib_unhash
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/icmp.c (ffffffff817fbd17)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_send
```
```
In net/ipv4/af_inet.c (ffffffff818006d6)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_register_protosw
```
```
In net/ipv4/igmp.c (ffffffff81802b4a)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_mcf_seq_stop
  - net/ipv4/igmp.c:igmp_mcf_seq_next
  - net/ipv4/igmp.c:igmp_mcf_seq_start
  - net/ipv4/igmp.c:ip_mc_add_src
  - net/ipv4/igmp.c:ip_mc_del_src
  - net/ipv4/igmp.c:ip_mc_inc_group
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:igmp_group_dropped
  - net/ipv4/igmp.c:igmp_group_dropped
  - net/ipv4/igmp.c:igmpv3_clear_delrec
  - net/ipv4/igmp.c:igmpv3_clear_delrec
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:igmp_stop_timer
```
```
In net/ipv4/fib_semantics.c (ffffffff8180a694)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_release_info
```
```
In net/ipv4/inet_fragment.c (ffffffff8180f8a7)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_worker
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff818132aa)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
```
In net/ipv4/ipmr.c (ffffffff81814dec)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_seq_stop
  - net/ipv4/ipmr.c:ipmr_mfc_seq_next
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
```
```
In net/ipv4/cipso_ipv4.c (ffffffff8181aaec)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_invalidate
```
```
In net/xfrm/xfrm_policy.c (ffffffff81821115)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
```
```
In net/xfrm/xfrm_state.c (ffffffff818281e0)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_mtu
  - net/xfrm/xfrm_state.c:xfrm_state_unregister_afinfo
  - net/xfrm/xfrm_state.c:xfrm_state_register_afinfo
  - net/xfrm/xfrm_state.c:xfrm_unregister_km
  - net/xfrm/xfrm_state.c:xfrm_register_km
  - net/xfrm/xfrm_state.c:xfrm_state_walk_done
  - net/xfrm/xfrm_state.c:xfrm_state_walk
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_find_acq_byseq
  - net/xfrm/xfrm_state.c:xfrm_find_acq
  - net/xfrm/xfrm_state.c:xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:xfrm_state_lookup
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_state_lookup_byspi
  - net/xfrm/xfrm_state.c:xfrm_state_lookup_byspi
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_sad_getinfo
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_destroy
  - net/xfrm/xfrm_state.c:xfrm_state_gc_task
  - net/xfrm/xfrm_state.c:xfrm_unregister_mode
  - net/xfrm/xfrm_state.c:xfrm_register_mode
  - net/xfrm/xfrm_state.c:xfrm_unregister_type
  - net/xfrm/xfrm_state.c:xfrm_register_type
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_input.c (ffffffff8182866a)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo
  - net/xfrm/xfrm_input.c:xfrm_input_register_afinfo
```
```
In net/xfrm/xfrm_output.c (ffffffff81829170)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/af_inet6.c (ffffffff8183013a)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_register_protosw
```
```
In net/ipv6/addrconf.c (ffffffff8183fe73)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_start
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:ipv6_generate_stable_address
  - net/ipv6/addrconf.c:add_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/route.c (ffffffff81846ee4)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_ifdown
  - net/ipv6/route.c:rt6_ifdown
  - net/ipv6/route.c:icmp6_dst_gc
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_dst_destroy
```
```
In net/ipv6/ip6_fib.c (ffffffff8184a005)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_run_gc
```
```
In net/ipv6/udp.c (ffffffff818511d2)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_recvmsg
```
```
In net/ipv6/raw.c (ffffffff81853cee)
Location: include/linux/spinlock.h:350
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff818568ce)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff818574aa)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mcf_seq_stop
  - net/ipv6/mcast.c:igmp6_mcf_seq_next
  - net/ipv6/mcast.c:igmp6_mcf_seq_start
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:ip6_mc_del_src
  - net/ipv6/mcast.c:ip6_mc_del_src
  - net/ipv6/mcast.c:mld_send_report
  - net/ipv6/mcast.c:mld_send_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:ipv6_dev_mc_inc
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/mcast.c:igmp6_group_added
  - net/ipv6/mcast.c:igmp6_group_added
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff8186520d)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:fl6_renew
  - net/ipv6/ip6_flowlabel.c:fl6_free_socklist
  - net/ipv6/ip6_flowlabel.c:fl6_free_socklist
  - net/ipv6/ip6_flowlabel.c:fl_release
```
```
In net/ipv6/ip6mr.c (ffffffff81868dbf)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ipmr_mfc_seq_next
```
```
In net/ipv6/calipso.c (ffffffff81870890)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_cache_invalidate
```
```
In net/packet/af_packet.c (ffffffff81875dc7)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_ioctl
  - net/packet/af_packet.c:packet_getsockopt
  - net/packet/af_packet.c:packet_rcv_has_room
```
```
In net/dcb/dcbnl.c (ffffffff81886543)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_ieee_delapp
  - net/dcb/dcbnl.c:dcb_ieee_setapp
  - net/dcb/dcbnl.c:dcb_ieee_getapp_mask
  - net/dcb/dcbnl.c:dcb_setapp
  - net/dcb/dcbnl.c:dcb_getapp
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
```
```
In net/switchdev/switchdev.c (ffffffff8188a7ef)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_deferred_enqueue
  - net/switchdev/switchdev.c:switchdev_deferred_process
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff81122188)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - kernel/cgroup.c:css_release_work_fn
  - kernel/cgroup.c:css_free_work_fn
  - kernel/cgroup.c:cgroup_idr_replace
```
```
In kernel/padata.c (ffffffff811ac1e6)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - kernel/padata.c:padata_reorder
  - kernel/padata.c:padata_reorder
```
```
In mm/page-writeback.c (ffffffff811bd341)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - mm/page-writeback.c:bdi_set_max_ratio
  - mm/page-writeback.c:bdi_set_min_ratio
```
```
In mm/backing-dev.c (ffffffff811d8d3a)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:bdi_register
  - mm/backing-dev.c:wb_wakeup_delayed
```
```
In fs/fs-writeback.c (ffffffff81277ad1)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_queue_work
  - fs/fs-writeback.c:wb_wakeup
```
```
In security/selinux/netif.c (ffffffff81399880)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_netdev_notifier_handler
  - security/selinux/netif.c:sel_netif_flush
  - security/selinux/netif.c:sel_netif_sid
```
```
In security/selinux/netnode.c (ffffffff81399e08)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_flush
  - security/selinux/netnode.c:sel_netnode_sid
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (ffffffff8139a088)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_flush
  - security/selinux/netport.c:sel_netport_sid
  - security/selinux/netport.c:sel_netport_sid
```
```
In security/apparmor/policy_unpack.c (ffffffff813d3606)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In block/genhd.c (ffffffff8142a16c)
Location: include/linux/spinlock.h:350
Inline: True
```
```
In lib/rhashtable.c (ffffffff814668ad)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rht_deferred_worker
```
```
In drivers/connector/cn_queue.c (ffffffff815c0c17)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_free_dev
  - drivers/connector/cn_queue.c:cn_queue_del_callback
  - drivers/connector/cn_queue.c:cn_queue_add_callback
```
```
In drivers/connector/connector.c (ffffffff815c0d36)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_proc_show
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/net/tun.c (ffffffff8167fd05)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_flow_cleanup
  - drivers/net/tun.c:tun_flow_flush
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81683493)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_disconnect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_disconnect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_ccp_closed
  - drivers/net/ppp/ppp_generic.c:ppp_ccp_closed
  - drivers/net/ppp/ppp_generic.c:ppp_set_compress
  - drivers/net/ppp/ppp_generic.c:ppp_set_compress
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_input_error
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_channel_push
  - drivers/net/ppp/ppp_generic.c:ppp_push
  - drivers/net/ppp/ppp_generic.c:ppp_push
  - drivers/net/ppp/ppp_generic.c:ppp_push
  - drivers/net/ppp/ppp_generic.c:ppp_push
  - drivers/net/ppp/ppp_generic.c:ppp_push
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_dev_uninit
  - drivers/net/ppp/ppp_generic.c:ppp_dev_uninit
  - drivers/net/ppp/ppp_generic.c:ppp_get_stats64
  - drivers/net/ppp/ppp_generic.c:ppp_get_stats64
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_poll
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - drivers/net/ppp/ppp_generic.c:ppp_read
```
```
In drivers/net/xen-netfront.c (ffffffff8168a9cb)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:xennet_open
```
```
In net/core/sock.c (ffffffff81796494)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/core/sock.c:release_sock
  - net/core/sock.c:__sk_flush_backlog
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__lock_sock
```
```
In net/core/request_sock.c (ffffffff8179890f)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/core/datagram.c (ffffffff817a1395)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/core/datagram.c:__sk_queue_drop_skb
  - net/core/datagram.c:__skb_free_datagram_locked
```
```
In net/core/gen_stats.c (ffffffff817a3f23)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/core/gen_stats.c:gnet_stats_finish_copy
  - net/core/gen_stats.c:gnet_stats_finish_copy
  - net/core/gen_stats.c:gnet_stats_copy_queue
  - net/core/gen_stats.c:gnet_stats_copy_rate_est
  - net/core/gen_stats.c:gnet_stats_copy_basic
  - net/core/gen_stats.c:gnet_stats_start_copy_compat
```
```
In net/core/net_namespace.c (ffffffff817a442b)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:get_net_ns_by_id
  - net/core/net_namespace.c:peernet2id
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/dev.c (ffffffff817b3896)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/core/dev.c:dev_set_rx_mode
  - net/core/dev.c:netif_set_real_num_tx_queues
```
```
In net/core/dev_addr_lists.c (ffffffff817b9bba)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:dev_mc_flush
  - net/core/dev_addr_lists.c:__dev_mc_del
  - net/core/dev_addr_lists.c:__dev_mc_add
  - net/core/dev_addr_lists.c:dev_mc_add_excl
  - net/core/dev_addr_lists.c:dev_uc_flush
  - net/core/dev_addr_lists.c:dev_uc_del
  - net/core/dev_addr_lists.c:dev_uc_add
  - net/core/dev_addr_lists.c:dev_uc_add_excl
```
```
In net/core/dst.c (ffffffff817bacec)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/core/dst.c:dst_dev_event
  - net/core/dst.c:__dst_free
  - net/core/dst.c:dst_gc_task
  - net/core/dst.c:dst_gc_task
```
```
In net/core/neighbour.c (ffffffff817bfcac)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_update
```
```
In net/core/rtnetlink.c (ffffffff817c4375)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_fdb_dump
```
```
In net/core/sock_reuseport.c (ffffffff817ce899)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_attach_prog
  - net/core/sock_reuseport.c:reuseport_detach_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_alloc
  - net/core/sock_reuseport.c:reuseport_alloc
```
```
In net/core/flow.c (ffffffff817cfaa7)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_gc_task
```
```
In net/core/net-procfs.c (ffffffff817d2771)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/core/net-procfs.c:dev_mc_seq_show
```
```
In net/sched/sch_generic.c (ffffffff817de2a4)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_graft_qdisc
```
```
In net/sched/sch_mq.c (ffffffff817de745)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump
```
```
In net/sched/sch_api.c (ffffffff817e0194)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_grow
```
```
In net/sched/cls_api.c (ffffffff817e27b0)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_change
```
```
In net/sched/act_api.c (ffffffff817e38ea)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_hash_insert
  - net/sched/act_api.c:tcf_hash_lookup
```
```
In net/netlink/af_netlink.c (ffffffff817e99bc)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:netlink_insert
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/ipv4/route.c (ffffffff817f3891)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_flush_dev
  - net/ipv4/route.c:ipv4_dst_destroy
  - net/ipv4/route.c:rt_add_uncached_list
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/inetpeer.c (ffffffff817f3d9d)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
  - net/ipv4/inetpeer.c:inetpeer_inval_rcu
  - net/ipv4/inetpeer.c:inetpeer_gc_worker
  - net/ipv4/inetpeer.c:inetpeer_gc_worker
```
```
In net/ipv4/ip_sockglue.c (ffffffff817fc843)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_ra_control
  - net/ipv4/ip_sockglue.c:ip_ra_control
  - net/ipv4/ip_sockglue.c:ip_ra_control
  - net/ipv4/ip_sockglue.c:ip_ra_control
```
```
In net/ipv4/inet_hashtables.c (ffffffff817ff468)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_unhash
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff817ff6be)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:__inet_twsk_hashdance
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8180108e)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp.c (ffffffff81802a08)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_info
  - net/ipv4/tcp.c:tcp_ioctl
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81818442)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_seq_stop
  - net/ipv4/tcp_ipv4.c:established_get_next
```
```
In net/ipv4/tcp_metrics.c (ffffffff8181ef77)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_flush_all
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/raw.c (ffffffff81822f41)
Location: include/linux/spinlock.h:350
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81824294)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_seq_stop
  - net/ipv4/udp.c:udp_get_next
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_lib_unhash
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:skb_consume_udp
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/icmp.c (ffffffff8182cc67)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_send
```
```
In net/ipv4/af_inet.c (ffffffff81831626)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_register_protosw
```
```
In net/ipv4/igmp.c (ffffffff81833af7)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_mcf_seq_stop
  - net/ipv4/igmp.c:igmp_mcf_seq_next
  - net/ipv4/igmp.c:igmp_mcf_seq_start
  - net/ipv4/igmp.c:ip_mc_add_src
  - net/ipv4/igmp.c:ip_mc_del_src
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:igmp_group_dropped
  - net/ipv4/igmp.c:igmp_group_dropped
  - net/ipv4/igmp.c:igmpv3_clear_delrec
  - net/ipv4/igmp.c:igmpv3_clear_delrec
  - net/ipv4/igmp.c:igmpv3_del_delrec
  - net/ipv4/igmp.c:igmpv3_del_delrec
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:igmp_stop_timer
```
```
In net/ipv4/fib_semantics.c (ffffffff8183b7a4)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_release_info
```
```
In net/ipv4/inet_fragment.c (ffffffff81840df7)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_worker
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff818447ba)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
```
In net/ipv4/ipmr.c (ffffffff818465a9)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_seq_stop
  - net/ipv4/ipmr.c:ipmr_mfc_seq_next
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
```
```
In net/ipv4/cipso_ipv4.c (ffffffff8184c3ac)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_invalidate
```
```
In net/xfrm/xfrm_policy.c (ffffffff81852925)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:__xfrm_sk_clone_policy
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_policy_walk_done
  - net/xfrm/xfrm_policy.c:xfrm_policy_walk
  - net/xfrm/xfrm_policy.c:xfrm_policy_flush
  - net/xfrm/xfrm_policy.c:xfrm_policy_flush
  - net/xfrm/xfrm_policy.c:xfrm_policy_flush
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff81859c00)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_mtu
  - net/xfrm/xfrm_state.c:xfrm_state_unregister_afinfo
  - net/xfrm/xfrm_state.c:xfrm_state_register_afinfo
  - net/xfrm/xfrm_state.c:xfrm_unregister_km
  - net/xfrm/xfrm_state.c:xfrm_register_km
  - net/xfrm/xfrm_state.c:xfrm_state_walk_done
  - net/xfrm/xfrm_state.c:xfrm_state_walk
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_find_acq_byseq
  - net/xfrm/xfrm_state.c:xfrm_find_acq
  - net/xfrm/xfrm_state.c:xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_state_lookup_byspi
  - net/xfrm/xfrm_state.c:xfrm_state_lookup_byspi
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_sad_getinfo
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_destroy
  - net/xfrm/xfrm_state.c:xfrm_state_gc_task
  - net/xfrm/xfrm_state.c:xfrm_unregister_mode
  - net/xfrm/xfrm_state.c:xfrm_register_mode
  - net/xfrm/xfrm_state.c:xfrm_unregister_type
  - net/xfrm/xfrm_state.c:xfrm_register_type
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_input.c (ffffffff8185a04a)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo
  - net/xfrm/xfrm_input.c:xfrm_input_register_afinfo
```
```
In net/xfrm/xfrm_output.c (ffffffff8185ab50)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/af_inet6.c (ffffffff81861bba)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_register_protosw
```
```
In net/ipv6/addrconf.c (ffffffff81871af3)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_start
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:ipv6_generate_stable_address
  - net/ipv6/addrconf.c:add_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/route.c (ffffffff81878d24)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_ifdown
  - net/ipv6/route.c:rt6_ifdown
  - net/ipv6/route.c:icmp6_dst_gc
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_dst_destroy
```
```
In net/ipv6/ip6_fib.c (ffffffff8187be95)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_run_gc
```
```
In net/ipv6/raw.c (ffffffff818859fe)
Location: include/linux/spinlock.h:350
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff818886d0)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff818892a7)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mcf_seq_stop
  - net/ipv6/mcast.c:igmp6_mcf_seq_next
  - net/ipv6/mcast.c:igmp6_mcf_seq_start
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:ip6_mc_del_src
  - net/ipv6/mcast.c:ip6_mc_del_src
  - net/ipv6/mcast.c:mld_send_report
  - net/ipv6/mcast.c:mld_send_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:mld_del_delrec
  - net/ipv6/mcast.c:mld_del_delrec
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/mcast.c:igmp6_group_added
  - net/ipv6/mcast.c:igmp6_group_added
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff818978dd)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:fl6_renew
  - net/ipv6/ip6_flowlabel.c:fl6_free_socklist
  - net/ipv6/ip6_flowlabel.c:fl6_free_socklist
  - net/ipv6/ip6_flowlabel.c:fl_release
```
```
In net/ipv6/ip6mr.c (ffffffff8189bc0f)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ipmr_mfc_seq_next
```
```
In net/ipv6/calipso.c (ffffffff818a3800)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_cache_invalidate
```
```
In net/ipv6/seg6_hmac.c (ffffffff818a5165)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
```
In net/packet/af_packet.c (ffffffff818aa2b6)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_ioctl
  - net/packet/af_packet.c:packet_getsockopt
  - net/packet/af_packet.c:packet_rcv_has_room
```
```
In net/dcb/dcbnl.c (ffffffff818badb3)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_ieee_delapp
  - net/dcb/dcbnl.c:dcb_ieee_setapp
  - net/dcb/dcbnl.c:dcb_ieee_getapp_mask
  - net/dcb/dcbnl.c:dcb_setapp
  - net/dcb/dcbnl.c:dcb_getapp
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
```
```
In net/switchdev/switchdev.c (ffffffff818beb9f)
Location: include/linux/spinlock.h:350
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_deferred_enqueue
  - net/switchdev/switchdev.c:switchdev_deferred_process
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81121cd8)
Location: include/linux/spinlock.h:342
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_free_work_fn
  - kernel/cgroup/cgroup.c:cgroup_idr_replace
```
```
In kernel/bpf/core.c (ffffffff8118f30a)
Location: include/linux/spinlock.h:342
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_del
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
```
```
In kernel/bpf/syscall.c (ffffffff811926cd)
Location: include/linux/spinlock.h:342
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:bpf_obj_get_next_id
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In kernel/padata.c (ffffffff811b3822)
Location: include/linux/spinlock.h:342
Inline: True
Inline callers:
  - kernel/padata.c:padata_reorder
  - kernel/padata.c:padata_reorder
```
```
In mm/page-writeback.c (ffffffff811c55c1)
Location: include/linux/spinlock.h:342
Inline: True
Inline callers:
  - mm/page-writeback.c:bdi_set_max_ratio
  - mm/page-writeback.c:bdi_set_min_ratio
```
```
In mm/backing-dev.c (ffffffff811e122b)
Location: include/linux/spinlock.h:342
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:wb_shutdown
  - mm/backing-dev.c:wb_shutdown
  - mm/backing-dev.c:wb_wakeup_delayed
```
```
In fs/fs-writeback.c (ffffffff81284e6c)
Location: include/linux/spinlock.h:342
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_queue_work
  - fs/fs-writeback.c:wb_wakeup
```
```
In security/selinux/netif.c (ffffffff813afc90)
Location: include/linux/spinlock.h:342
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_netdev_notifier_handler
  - security/selinux/netif.c:sel_netif_flush
  - security/selinux/netif.c:sel_netif_sid
```
```
In security/selinux/netnode.c (ffffffff813b02a8)
Location: include/linux/spinlock.h:342
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_flush
  - security/selinux/netnode.c:sel_netnode_sid
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (ffffffff813b0568)
Location: include/linux/spinlock.h:342
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_flush
  - security/selinux/netport.c:sel_netport_sid
  - security/selinux/netport.c:sel_netport_sid
```
```
In security/apparmor/policy_unpack.c (ffffffff813e6550)
Location: include/linux/spinlock.h:342
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In block/genhd.c (ffffffff814384f3)
Location: include/linux/spinlock.h:342
Inline: True
```
```
In lib/rhashtable.c (ffffffff8146c2c9)
Location: include/linux/spinlock.h:342
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rht_deferred_worker
  - lib/rhashtable.c:rhashtable_rehash_alloc
  - lib/rhashtable.c:rhashtable_rehash_alloc
```
```
In drivers/connector/cn_queue.c (ffffffff815d6754)
Location: include/linux/spinlock.h:342
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_free_dev
  - drivers/connector/cn_queue.c:cn_queue_del_callback
  - drivers/connector/cn_queue.c:cn_queue_add_callback
```
```
In drivers/connector/connector.c (ffffffff815d6877)
Location: include/linux/spinlock.h:342
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_proc_show
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/net/tun.c (ffffffff8169509f)
Location: include/linux/spinlock.h:342
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_flow_cleanup
  - drivers/net/tun.c:tun_flow_flush
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff816988c3)
Location: include/linux/spinlock.h:342
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_disconnect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_disconnect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_ccp_closed
  - drivers/net/ppp/ppp_generic.c:ppp_ccp_closed
  - drivers/net/ppp/ppp_generic.c:ppp_set_compress
  - drivers/net/ppp/ppp_generic.c:ppp_set_compress
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_input_error
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_dev_uninit
  - drivers/net/ppp/ppp_generic.c:ppp_dev_uninit
  - drivers/net/ppp/ppp_generic.c:ppp_get_stats64
  - drivers/net/ppp/ppp_generic.c:ppp_get_stats64
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_poll
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - drivers/net/ppp/ppp_generic.c:ppp_read
```
```
In drivers/net/xen-netfront.c (ffffffff816a0242)
Location: include/linux/spinlock.h:342
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:netback_changed
  - drivers/net/xen-netfront.c:xennet_open
```
```
In net/core/sock.c (ffffffff817b4654)
Location: include/linux/spinlock.h:342
Inline: True
Inline callers:
  - net/core/sock.c:release_sock
  - net/core/sock.c:__sk_flush_backlog
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__lock_sock
```
```
In net/core/request_sock.c (ffffffff817b6eef)
Location: include/linux/spinlock.h:342
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/core/datagram.c (ffffffff817bf4c1)
Location: include/linux/spinlock.h:342
Inline: True
Inline callers:
  - net/core/datagram.c:__sk_queue_drop_skb
```
```
In net/core/gen_stats.c (ffffffff817c2073)
Location: include/linux/spinlock.h:342
Inline: True
Inline callers:
  - net/core/gen_stats.c:gnet_stats_finish_copy
  - net/core/gen_stats.c:gnet_stats_finish_copy
  - net/core/gen_stats.c:gnet_stats_copy_queue
  - net/core/gen_stats.c:gnet_stats_copy_rate_est
  - net/core/gen_stats.c:gnet_stats_copy_basic
```
```
In net/core/net_namespace.c (ffffffff817c259b)
Location: include/linux/spinlock.h:342
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:get_net_ns_by_id
  - net/core/net_namespace.c:peernet2id
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/dev.c (ffffffff817d2216)
Location: include/linux/spinlock.h:342
Inline: True
Inline callers:
  - net/core/dev.c:dev_set_rx_mode
  - net/core/dev.c:netif_set_real_num_tx_queues
```
```
In net/core/dev_addr_lists.c (ffffffff817d870a)
Location: include/linux/spinlock.h:342
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:dev_mc_flush
  - net/core/dev_addr_lists.c:__dev_mc_del
  - net/core/dev_addr_lists.c:__dev_mc_add
  - net/core/dev_addr_lists.c:dev_mc_add_excl
  - net/core/dev_addr_lists.c:dev_uc_flush
  - net/core/dev_addr_lists.c:dev_uc_del
  - net/core/dev_addr_lists.c:dev_uc_add
  - net/core/dev_addr_lists.c:dev_uc_add_excl
```
```
In net/core/neighbour.c (ffffffff817de332)
Location: include/linux/spinlock.h:342
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_update
```
```
In net/core/rtnetlink.c (ffffffff817e26e5)
Location: include/linux/spinlock.h:342
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_fdb_dump
```
```
In net/core/sock_reuseport.c (ffffffff817edd39)
Location: include/linux/spinlock.h:342
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_attach_prog
  - net/core/sock_reuseport.c:reuseport_detach_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_alloc
  - net/core/sock_reuseport.c:reuseport_alloc
```
```
In net/core/flow.c (ffffffff817eeeb7)
Location: include/linux/spinlock.h:342
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_gc_task
```
```
In net/core/net-procfs.c (ffffffff817f1d89)
Location: include/linux/spinlock.h:342
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff817fd8f8)
Location: include/linux/spinlock.h:342
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_graft_qdisc
```
```
In net/sched/sch_mq.c (ffffffff817fdd75)
Location: include/linux/spinlock.h:342
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump
```
```
In net/sched/sch_api.c (ffffffff817ff335)
Location: include/linux/spinlock.h:342
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_grow
```
```
In net/sched/cls_api.c (ffffffff81802090)
Location: include/linux/spinlock.h:342
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_change
```
```
In net/sched/act_api.c (ffffffff818032da)
Location: include/linux/spinlock.h:342
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_hash_insert
  - net/sched/act_api.c:tcf_hash_lookup
```
```
In net/netlink/af_netlink.c (ffffffff818096c8)
Location: include/linux/spinlock.h:342
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_insert
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/ipv4/route.c (ffffffff818114ca)
Location: include/linux/spinlock.h:342
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_flush_dev
  - net/ipv4/route.c:rt_add_uncached_list
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/inetpeer.c (ffffffff8181417d)
Location: include/linux/spinlock.h:342
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
  - net/ipv4/inetpeer.c:inetpeer_inval_rcu
  - net/ipv4/inetpeer.c:inetpeer_gc_worker
  - net/ipv4/inetpeer.c:inetpeer_gc_worker
```
```
In net/ipv4/inet_hashtables.c (ffffffff8181f690)
Location: include/linux/spinlock.h:342
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_unhash
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff8181f8ec)
Location: include/linux/spinlock.h:342
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:__inet_twsk_hashdance
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81820dfa)
Location: include/linux/spinlock.h:342
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp.c (ffffffff81822ddb)
Location: include/linux/spinlock.h:342
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_ioctl
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81838912)
Location: include/linux/spinlock.h:342
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_seq_stop
  - net/ipv4/tcp_ipv4.c:established_get_next
```
```
In net/ipv4/tcp_metrics.c (ffffffff8183fb93)
Location: include/linux/spinlock.h:342
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_flush_all
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/raw.c (ffffffff81843aa5)
Location: include/linux/spinlock.h:342
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81844fa5)
Location: include/linux/spinlock.h:342
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_seq_stop
  - net/ipv4/udp.c:udp_get_next
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/af_inet.c (ffffffff81852bd4)
Location: include/linux/spinlock.h:342
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_register_protosw
```
```
In net/ipv4/igmp.c (ffffffff81855097)
Location: include/linux/spinlock.h:342
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_mcf_seq_stop
  - net/ipv4/igmp.c:igmp_mcf_seq_next
  - net/ipv4/igmp.c:igmp_mcf_seq_start
  - net/ipv4/igmp.c:ip_mc_clear_src
  - net/ipv4/igmp.c:ip_mc_add_src
  - net/ipv4/igmp.c:ip_mc_del_src
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:igmp_group_dropped
  - net/ipv4/igmp.c:igmp_group_dropped
  - net/ipv4/igmp.c:igmpv3_clear_delrec
  - net/ipv4/igmp.c:igmpv3_clear_delrec
  - net/ipv4/igmp.c:igmpv3_del_delrec
  - net/ipv4/igmp.c:igmpv3_del_delrec
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:igmp_stop_timer
```
```
In net/ipv4/fib_semantics.c (ffffffff8185d0ad)
Location: include/linux/spinlock.h:342
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_release_info
```
```
In net/ipv4/inet_fragment.c (ffffffff81862697)
Location: include/linux/spinlock.h:342
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_worker
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81866172)
Location: include/linux/spinlock.h:342
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
```
In net/ipv4/ipmr.c (ffffffff8186838a)
Location: include/linux/spinlock.h:342
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_seq_stop
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
```
```
In net/ipv4/cipso_ipv4.c (ffffffff8186fe3e)
Location: include/linux/spinlock.h:342
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_invalidate
```
```
In net/xfrm/xfrm_policy.c (ffffffff81875a4d)
Location: include/linux/spinlock.h:342
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:__xfrm_sk_clone_policy
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_policy_walk
  - net/xfrm/xfrm_policy.c:xfrm_policy_flush
  - net/xfrm/xfrm_policy.c:xfrm_policy_flush
  - net/xfrm/xfrm_policy.c:xfrm_policy_flush
  - net/xfrm/xfrm_policy.c:xfrm_policy_byid
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff81879aa4)
Location: include/linux/spinlock.h:342
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_unregister_afinfo
  - net/xfrm/xfrm_state.c:xfrm_state_register_afinfo
  - net/xfrm/xfrm_state.c:xfrm_unregister_km
  - net/xfrm/xfrm_state.c:xfrm_register_km
  - net/xfrm/xfrm_state.c:xfrm_state_walk
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_find_acq_byseq
  - net/xfrm/xfrm_state.c:xfrm_find_acq
  - net/xfrm/xfrm_state.c:xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_state_lookup_byspi
  - net/xfrm/xfrm_state.c:xfrm_state_lookup_byspi
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_sad_getinfo
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_destroy
  - net/xfrm/xfrm_state.c:xfrm_state_gc_task
  - net/xfrm/xfrm_state.c:xfrm_unregister_mode
  - net/xfrm/xfrm_state.c:xfrm_register_mode
  - net/xfrm/xfrm_state.c:xfrm_unregister_type_offload
  - net/xfrm/xfrm_state.c:xfrm_register_type_offload
  - net/xfrm/xfrm_state.c:xfrm_unregister_type
  - net/xfrm/xfrm_state.c:xfrm_register_type
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_input.c (ffffffff8187de24)
Location: include/linux/spinlock.h:342
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo
  - net/xfrm/xfrm_input.c:xfrm_input_register_afinfo
```
```
In net/xfrm/xfrm_output.c (ffffffff8187ecab)
Location: include/linux/spinlock.h:342
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/af_inet6.c (ffffffff818862d6)
Location: include/linux/spinlock.h:342
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_register_protosw
```
```
In net/ipv6/addrconf.c (ffffffff8189686d)
Location: include/linux/spinlock.h:342
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_start
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:ipv6_generate_stable_address
  - net/ipv6/addrconf.c:add_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/route.c (ffffffff8189e0c4)
Location: include/linux/spinlock.h:342
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_ifdown
  - net/ipv6/route.c:ip6_dst_destroy
  - net/ipv6/route.c:rt6_uncached_list_add
```
```
In net/ipv6/ip6_fib.c (ffffffff818a1839)
Location: include/linux/spinlock.h:342
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_run_gc
```
```
In net/ipv6/raw.c (ffffffff818abf35)
Location: include/linux/spinlock.h:342
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff818af937)
Location: include/linux/spinlock.h:342
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mcf_seq_stop
  - net/ipv6/mcast.c:igmp6_mcf_seq_next
  - net/ipv6/mcast.c:igmp6_mcf_seq_start
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:ip6_mc_del_src
  - net/ipv6/mcast.c:ip6_mc_del_src
  - net/ipv6/mcast.c:mld_send_report
  - net/ipv6/mcast.c:mld_send_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:mld_del_delrec
  - net/ipv6/mcast.c:mld_del_delrec
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/mcast.c:igmp6_group_added
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff818bdce1)
Location: include/linux/spinlock.h:342
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:fl6_renew
  - net/ipv6/ip6_flowlabel.c:fl6_free_socklist
  - net/ipv6/ip6_flowlabel.c:fl6_free_socklist
  - net/ipv6/ip6_flowlabel.c:fl_release
```
```
In net/ipv6/ip6mr.c (ffffffff818c2005)
Location: include/linux/spinlock.h:342
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ipmr_mfc_seq_next
```
```
In net/ipv6/calipso.c (ffffffff818c9dbd)
Location: include/linux/spinlock.h:342
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_cache_invalidate
```
```
In net/ipv6/seg6_hmac.c (ffffffff818cbbd6)
Location: include/linux/spinlock.h:342
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
```
In net/packet/af_packet.c (ffffffff818d0de4)
Location: include/linux/spinlock.h:342
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_ioctl
  - net/packet/af_packet.c:packet_getsockopt
  - net/packet/af_packet.c:packet_rcv_has_room
```
```
In net/dcb/dcbnl.c (ffffffff818e17c0)
Location: include/linux/spinlock.h:342
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_ieee_delapp
  - net/dcb/dcbnl.c:dcb_ieee_setapp
  - net/dcb/dcbnl.c:dcb_ieee_getapp_mask
  - net/dcb/dcbnl.c:dcb_setapp
  - net/dcb/dcbnl.c:dcb_getapp
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
```
```
In net/switchdev/switchdev.c (ffffffff818e56b8)
Location: include/linux/spinlock.h:342
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_deferred_enqueue
  - net/switchdev/switchdev.c:switchdev_deferred_process
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8112d3ca)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_idr_remove
  - kernel/cgroup/cgroup.c:cgroup_idr_replace
```
```
In kernel/bpf/core.c (ffffffff8119d77a)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_del
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
```
```
In kernel/bpf/syscall.c (ffffffff811a0dd6)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:bpf_obj_get_next_id
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In kernel/padata.c (ffffffff811c7492)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - kernel/padata.c:padata_reorder
  - kernel/padata.c:padata_reorder
```
```
In mm/page-writeback.c (ffffffff811da3c1)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - mm/page-writeback.c:bdi_set_max_ratio
  - mm/page-writeback.c:bdi_set_min_ratio
```
```
In mm/backing-dev.c (ffffffff811f723b)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:wb_shutdown
  - mm/backing-dev.c:wb_shutdown
  - mm/backing-dev.c:wb_wakeup_delayed
```
```
In fs/fs-writeback.c (ffffffff812a78ec)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_queue_work
  - fs/fs-writeback.c:wb_wakeup
```
```
In ipc/util.c (ffffffff813a72fc)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
  - ipc/util.c:ipc_addid
```
```
In security/selinux/netif.c (ffffffff813d5d40)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_netdev_notifier_handler
  - security/selinux/netif.c:sel_netif_flush
  - security/selinux/netif.c:sel_netif_sid
```
```
In security/selinux/netnode.c (ffffffff813d6348)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_flush
  - security/selinux/netnode.c:sel_netnode_sid
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (ffffffff813d6608)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_flush
  - security/selinux/netport.c:sel_netport_sid
  - security/selinux/netport.c:sel_netport_sid
```
```
In security/apparmor/policy_unpack.c (ffffffff8140d732)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In block/genhd.c (ffffffff81463c50)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - block/genhd.c:get_gendisk
```
```
In lib/rhashtable.c (ffffffff814985c8)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rht_deferred_worker
  - lib/rhashtable.c:rhashtable_rehash_alloc
  - lib/rhashtable.c:rhashtable_rehash_alloc
```
```
In drivers/connector/cn_queue.c (ffffffff8163d524)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_free_dev
  - drivers/connector/cn_queue.c:cn_queue_del_callback
  - drivers/connector/cn_queue.c:cn_queue_add_callback
```
```
In drivers/connector/connector.c (ffffffff8163d647)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_proc_show
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/net/tun.c (ffffffff816ff1f5)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_flow_flush
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81703793)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_disconnect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_disconnect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_ccp_closed
  - drivers/net/ppp/ppp_generic.c:ppp_ccp_closed
  - drivers/net/ppp/ppp_generic.c:ppp_set_compress
  - drivers/net/ppp/ppp_generic.c:ppp_set_compress
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_input_error
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_dev_uninit
  - drivers/net/ppp/ppp_generic.c:ppp_dev_uninit
  - drivers/net/ppp/ppp_generic.c:ppp_get_stats64
  - drivers/net/ppp/ppp_generic.c:ppp_get_stats64
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_poll
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - drivers/net/ppp/ppp_generic.c:ppp_read
```
```
In drivers/net/xen-netfront.c (ffffffff8170b408)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:netback_changed
  - drivers/net/xen-netfront.c:xennet_open
```
```
In net/core/sock.c (ffffffff8182c8b7)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/core/sock.c:release_sock
  - net/core/sock.c:__sk_flush_backlog
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__lock_sock
```
```
In net/core/request_sock.c (ffffffff8182f4df)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/core/datagram.c (ffffffff81838e4f)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/core/datagram.c:__sk_queue_drop_skb
```
```
In net/core/gen_stats.c (ffffffff8183ba73)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/core/gen_stats.c:gnet_stats_finish_copy
  - net/core/gen_stats.c:gnet_stats_finish_copy
  - net/core/gen_stats.c:gnet_stats_copy_queue
  - net/core/gen_stats.c:gnet_stats_copy_rate_est
  - net/core/gen_stats.c:gnet_stats_copy_basic
```
```
In net/core/net_namespace.c (ffffffff8183bfeb)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:get_net_ns_by_id
  - net/core/net_namespace.c:peernet2id
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/dev.c (ffffffff8184c4a6)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/core/dev.c:dev_set_rx_mode
  - net/core/dev.c:netif_set_real_num_tx_queues
```
```
In net/core/dev_addr_lists.c (ffffffff81852e0a)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:dev_mc_flush
  - net/core/dev_addr_lists.c:__dev_mc_del
  - net/core/dev_addr_lists.c:__dev_mc_add
  - net/core/dev_addr_lists.c:dev_mc_add_excl
  - net/core/dev_addr_lists.c:dev_uc_flush
  - net/core/dev_addr_lists.c:dev_uc_del
  - net/core/dev_addr_lists.c:dev_uc_add
  - net/core/dev_addr_lists.c:dev_uc_add_excl
```
```
In net/core/neighbour.c (ffffffff81858b94)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_update
```
```
In net/core/rtnetlink.c (ffffffff8185d5a5)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_fdb_dump
```
```
In net/core/sock_reuseport.c (ffffffff81869f79)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_attach_prog
  - net/core/sock_reuseport.c:reuseport_detach_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_alloc
  - net/core/sock_reuseport.c:reuseport_alloc
```
```
In net/core/net-procfs.c (ffffffff8186d349)
Location: include/linux/spinlock.h:353
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff8187b4cb)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_graft_qdisc
```
```
In net/sched/sch_mq.c (ffffffff8187b995)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump
```
```
In net/sched/sch_api.c (ffffffff8187d0a0)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_grow
```
```
In net/sched/act_api.c (ffffffff81882bb9)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_setup_cb_egdev_register
  - net/sched/act_api.c:tc_setup_cb_egdev_register
  - net/sched/act_api.c:tcf_idr_insert
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_idr_check
  - net/sched/act_api.c:tcf_idr_search
```
```
In net/netlink/af_netlink.c (ffffffff81888619)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_insert
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/ipv4/route.c (ffffffff81890aa4)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_flush_dev
  - net/ipv4/route.c:ipv4_dst_destroy
  - net/ipv4/route.c:rt_add_uncached_list
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/inetpeer.c (ffffffff81893816)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/inet_hashtables.c (ffffffff8189e5f3)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_unhash
```
```
In net/ipv4/inet_connection_sock.c (ffffffff818a0368)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp.c (ffffffff818a1efb)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_ioctl
```
```
In net/ipv4/tcp_ipv4.c (ffffffff818b8062)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_seq_stop
  - net/ipv4/tcp_ipv4.c:established_get_next
```
```
In net/ipv4/tcp_metrics.c (ffffffff818bef33)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_flush_all
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/raw.c (ffffffff818c34a5)
Location: include/linux/spinlock.h:353
Inline: True
```
```
In net/ipv4/udp.c (ffffffff818c4a35)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_seq_stop
  - net/ipv4/udp.c:udp_get_next
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/af_inet.c (ffffffff818d29e4)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_register_protosw
```
```
In net/ipv4/igmp.c (ffffffff818d4f37)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_mcf_seq_stop
  - net/ipv4/igmp.c:igmp_mcf_seq_next
  - net/ipv4/igmp.c:igmp_mcf_seq_start
  - net/ipv4/igmp.c:ip_mc_clear_src
  - net/ipv4/igmp.c:ip_mc_add_src
  - net/ipv4/igmp.c:ip_mc_del_src
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:igmp_group_dropped
  - net/ipv4/igmp.c:igmp_group_dropped
  - net/ipv4/igmp.c:igmpv3_clear_delrec
  - net/ipv4/igmp.c:igmpv3_clear_delrec
  - net/ipv4/igmp.c:igmpv3_del_delrec
  - net/ipv4/igmp.c:igmpv3_del_delrec
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:igmp_stop_timer
```
```
In net/ipv4/fib_semantics.c (ffffffff818dd0cd)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_release_info
```
```
In net/ipv4/inet_fragment.c (ffffffff818e27b7)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_worker
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff818e65a2)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
```
In net/ipv4/ipmr.c (ffffffff818e841a)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_seq_stop
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
```
```
In net/ipv4/cipso_ipv4.c (ffffffff818f07ee)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_invalidate
```
```
In net/xfrm/xfrm_policy.c (ffffffff818f613a)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:__xfrm_sk_clone_policy
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_policy_walk
  - net/xfrm/xfrm_policy.c:xfrm_policy_flush
  - net/xfrm/xfrm_policy.c:xfrm_policy_flush
  - net/xfrm/xfrm_policy.c:xfrm_policy_flush
  - net/xfrm/xfrm_policy.c:xfrm_policy_byid
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff818fa4f4)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_unregister_afinfo
  - net/xfrm/xfrm_state.c:xfrm_state_register_afinfo
  - net/xfrm/xfrm_state.c:xfrm_unregister_km
  - net/xfrm/xfrm_state.c:xfrm_register_km
  - net/xfrm/xfrm_state.c:xfrm_state_walk
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_find_acq_byseq
  - net/xfrm/xfrm_state.c:xfrm_find_acq
  - net/xfrm/xfrm_state.c:xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_state_lookup_byspi
  - net/xfrm/xfrm_state.c:xfrm_state_lookup_byspi
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_sad_getinfo
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_destroy
  - net/xfrm/xfrm_state.c:xfrm_state_gc_task
  - net/xfrm/xfrm_state.c:xfrm_unregister_mode
  - net/xfrm/xfrm_state.c:xfrm_register_mode
  - net/xfrm/xfrm_state.c:xfrm_unregister_type_offload
  - net/xfrm/xfrm_state.c:xfrm_register_type_offload
  - net/xfrm/xfrm_state.c:xfrm_unregister_type
  - net/xfrm/xfrm_state.c:xfrm_register_type
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_input.c (ffffffff818fecb4)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo
  - net/xfrm/xfrm_input.c:xfrm_input_register_afinfo
```
```
In net/xfrm/xfrm_output.c (ffffffff818ffdad)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/af_inet6.c (ffffffff819074e6)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_register_protosw
```
```
In net/ipv6/addrconf.c (ffffffff81917c3d)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_start
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:ipv6_generate_stable_address
  - net/ipv6/addrconf.c:add_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/route.c (ffffffff8191a579)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_mtu_change_route
  - net/ipv6/route.c:rt6_ifdown
  - net/ipv6/route.c:fib6_clean_tohost
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_del_rt
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:rt6_remove_exception_rt
  - net/ipv6/route.c:rt6_flush_exceptions
  - net/ipv6/route.c:rt6_insert_exception
  - net/ipv6/route.c:__ip6_ins_rt
  - net/ipv6/route.c:ip6_dst_destroy
  - net/ipv6/route.c:rt6_uncached_list_add
```
```
In net/ipv6/ip6_fib.c (ffffffff81921b95)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:__fib6_clean_all
  - net/ipv6/ip6_fib.c:inet6_dump_fib
  - net/ipv6/ip6_fib.c:inet6_dump_fib
  - net/ipv6/ip6_fib.c:fib6_tables_dump
  - net/ipv6/ip6_fib.c:fib6_update_sernum
```
```
In net/ipv6/raw.c (ffffffff8192e9e5)
Location: include/linux/spinlock.h:353
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff81932667)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mcf_seq_stop
  - net/ipv6/mcast.c:igmp6_mcf_seq_next
  - net/ipv6/mcast.c:igmp6_mcf_seq_start
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:ip6_mc_del_src
  - net/ipv6/mcast.c:ip6_mc_del_src
  - net/ipv6/mcast.c:mld_send_report
  - net/ipv6/mcast.c:mld_send_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:mld_del_delrec
  - net/ipv6/mcast.c:mld_del_delrec
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/mcast.c:igmp6_group_added
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81940d81)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:fl6_renew
  - net/ipv6/ip6_flowlabel.c:fl6_free_socklist
  - net/ipv6/ip6_flowlabel.c:fl6_free_socklist
  - net/ipv6/ip6_flowlabel.c:fl_release
```
```
In net/ipv6/ip6mr.c (ffffffff81945941)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ipmr_mfc_seq_next
```
```
In net/ipv6/calipso.c (ffffffff8194d4a8)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_cache_invalidate
```
```
In net/ipv6/seg6_hmac.c (ffffffff8195097b)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
```
In net/packet/af_packet.c (ffffffff81955cf5)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_ioctl
  - net/packet/af_packet.c:packet_getsockopt
  - net/packet/af_packet.c:packet_rcv_has_room
```
```
In net/dcb/dcbnl.c (ffffffff81967543)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_ieee_delapp
  - net/dcb/dcbnl.c:dcb_ieee_setapp
  - net/dcb/dcbnl.c:dcb_ieee_getapp_mask
  - net/dcb/dcbnl.c:dcb_setapp
  - net/dcb/dcbnl.c:dcb_getapp
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
```
```
In net/switchdev/switchdev.c (ffffffff8196aded)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_deferred_process
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
In kernel/cgroup/cgroup.c (ffffffff8113c048)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_idr_remove
  - kernel/cgroup/cgroup.c:cgroup_idr_replace
```
```
In kernel/bpf/core.c (ffffffff811b1e14)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
```
```
In kernel/bpf/syscall.c (ffffffff811b5594)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_get_fd_by_id
  - kernel/bpf/syscall.c:bpf_prog_get_fd_by_id
  - kernel/bpf/syscall.c:bpf_obj_get_next_id
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
```
```
In kernel/bpf/btf.c (ffffffff811c8b47)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
```
```
In kernel/bpf/sockmap.c (ffffffff811cc68e)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - kernel/bpf/sockmap.c:smap_list_hash_remove
  - kernel/bpf/sockmap.c:smap_list_map_remove
  - kernel/bpf/sockmap.c:bpf_tcp_init
```
```
In kernel/padata.c (ffffffff811e76e2)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - kernel/padata.c:padata_reorder
  - kernel/padata.c:padata_reorder
```
```
In mm/page-writeback.c (ffffffff811fb8b1)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - mm/page-writeback.c:bdi_set_max_ratio
  - mm/page-writeback.c:bdi_set_min_ratio
```
```
In mm/backing-dev.c (ffffffff81218487)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:wb_wakeup_delayed
```
```
In fs/fs-writeback.c (ffffffff812ce476)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_queue_work
  - fs/fs-writeback.c:wb_wakeup
```
```
In ipc/util.c (ffffffff813d67ee)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - ipc/util.c:ipc_set_key_private
  - ipc/util.c:ipc_rmid
  - ipc/util.c:ipc_addid
  - ipc/util.c:ipc_addid
```
```
In security/selinux/netif.c (ffffffff81406330)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_netdev_notifier_handler
  - security/selinux/netif.c:sel_netif_flush
  - security/selinux/netif.c:sel_netif_sid
```
```
In security/selinux/netnode.c (ffffffff81406968)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_flush
  - security/selinux/netnode.c:sel_netnode_sid
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (ffffffff81406c18)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_flush
  - security/selinux/netport.c:sel_netport_sid
  - security/selinux/netport.c:sel_netport_sid
```
```
In security/apparmor/policy_unpack.c (ffffffff8143f077)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In block/genhd.c (ffffffff81497813)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - block/genhd.c:get_gendisk
```
```
In lib/rhashtable.c (ffffffff814cd7af)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rht_deferred_worker
  - lib/rhashtable.c:rhashtable_rehash_alloc
  - lib/rhashtable.c:rhashtable_rehash_alloc
```
```
In drivers/connector/cn_queue.c (ffffffff81678b24)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_free_dev
  - drivers/connector/cn_queue.c:cn_queue_del_callback
  - drivers/connector/cn_queue.c:cn_queue_add_callback
```
```
In drivers/connector/connector.c (ffffffff81678c47)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_proc_show
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/net/tun.c (ffffffff8173bff7)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_set_ebpf
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_flow_flush
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817420bf)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_disconnect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_disconnect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_ccp_closed
  - drivers/net/ppp/ppp_generic.c:ppp_ccp_closed
  - drivers/net/ppp/ppp_generic.c:ppp_set_compress
  - drivers/net/ppp/ppp_generic.c:ppp_set_compress
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_input_error
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_dev_uninit
  - drivers/net/ppp/ppp_generic.c:ppp_dev_uninit
  - drivers/net/ppp/ppp_generic.c:ppp_get_stats64
  - drivers/net/ppp/ppp_generic.c:ppp_get_stats64
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_poll
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - drivers/net/ppp/ppp_generic.c:ppp_read
```
```
In drivers/net/xen-netfront.c (ffffffff81749e83)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:netback_changed
```
```
In net/core/sock.c (ffffffff81876a17)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/core/sock.c:release_sock
  - net/core/sock.c:__sk_flush_backlog
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__lock_sock
```
```
In net/core/request_sock.c (ffffffff8187996f)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/core/datagram.c (ffffffff8188359f)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/core/datagram.c:__sk_queue_drop_skb
```
```
In net/core/gen_stats.c (ffffffff818861f3)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/core/gen_stats.c:gnet_stats_finish_copy
  - net/core/gen_stats.c:gnet_stats_finish_copy
  - net/core/gen_stats.c:gnet_stats_copy_queue
  - net/core/gen_stats.c:gnet_stats_copy_rate_est
  - net/core/gen_stats.c:gnet_stats_copy_basic
```
```
In net/core/net_namespace.c (ffffffff8188670b)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:peernet2id
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/dev.c (ffffffff818966f6)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/core/dev.c:dev_set_rx_mode
  - net/core/dev.c:netif_set_real_num_tx_queues
```
```
In net/core/dev_addr_lists.c (ffffffff8189e51a)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:dev_mc_flush
  - net/core/dev_addr_lists.c:__dev_mc_del
  - net/core/dev_addr_lists.c:__dev_mc_add
  - net/core/dev_addr_lists.c:dev_mc_add_excl
  - net/core/dev_addr_lists.c:dev_uc_flush
  - net/core/dev_addr_lists.c:dev_uc_del
  - net/core/dev_addr_lists.c:dev_uc_add
  - net/core/dev_addr_lists.c:dev_uc_add_excl
```
```
In net/core/neighbour.c (ffffffff818a44c7)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_update
```
```
In net/core/rtnetlink.c (ffffffff818a912b)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_fdb_dump
```
```
In net/core/sock_reuseport.c (ffffffff818b9c5d)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_attach_prog
  - net/core/sock_reuseport.c:reuseport_detach_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_alloc
  - net/core/sock_reuseport.c:reuseport_alloc
```
```
In net/core/xdp.c (ffffffff818badb5)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_rxq_info_unreg
```
```
In net/core/page_pool.c (ffffffff818bdabd)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_empty_ring
```
```
In net/core/net-procfs.c (ffffffff818be579)
Location: include/linux/spinlock.h:353
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff818cd97b)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_graft_qdisc
```
```
In net/sched/sch_mq.c (ffffffff818ce0d0)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump
```
```
In net/sched/sch_api.c (ffffffff818cfacd)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/sched/sch_api.c:tcf_node_bind
  - net/sched/sch_api.c:qdisc_class_hash_grow
```
```
In net/sched/act_api.c (ffffffff818d65fd)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_setup_cb_egdev_register
  - net/sched/act_api.c:tc_setup_cb_egdev_register
```
```
In net/netlink/af_netlink.c (ffffffff818dc036)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_insert
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/ipv4/route.c (ffffffff818e46b4)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_flush_dev
  - net/ipv4/route.c:ipv4_dst_destroy
  - net/ipv4/route.c:rt_add_uncached_list
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/inetpeer.c (ffffffff818e7ac3)
Location: include/linux/spinlock.h:353
Inline: True
```
```
In net/ipv4/inet_hashtables.c (ffffffff818f30f0)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_unhash
```
```
In net/ipv4/inet_connection_sock.c (ffffffff818f56c2)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp.c (ffffffff818f984f)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_ioctl
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81910ede)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_seq_stop
  - net/ipv4/tcp_ipv4.c:established_get_next
```
```
In net/ipv4/tcp_metrics.c (ffffffff81914aff)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_flush_all
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/raw.c (ffffffff81919147)
Location: include/linux/spinlock.h:353
Inline: True
```
```
In net/ipv4/udp.c (ffffffff8191b17d)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_seq_stop
  - net/ipv4/udp.c:udp_get_next
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/af_inet.c (ffffffff81928fb2)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_register_protosw
```
```
In net/ipv4/igmp.c (ffffffff8192b897)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_mcf_seq_stop
  - net/ipv4/igmp.c:igmp_mcf_seq_next
  - net/ipv4/igmp.c:igmp_mcf_seq_start
  - net/ipv4/igmp.c:ip_mc_clear_src
  - net/ipv4/igmp.c:ip_mc_add_src
  - net/ipv4/igmp.c:ip_mc_del_src
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:igmp_group_dropped
  - net/ipv4/igmp.c:igmp_group_dropped
  - net/ipv4/igmp.c:igmpv3_clear_delrec
  - net/ipv4/igmp.c:igmpv3_clear_delrec
  - net/ipv4/igmp.c:igmpv3_del_delrec
  - net/ipv4/igmp.c:igmpv3_del_delrec
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:igmp_stop_timer
```
```
In net/ipv4/fib_semantics.c (ffffffff81933c70)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_release_info
```
```
In net/ipv4/inet_fragment.c (ffffffff819391ba)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff8193d0ce)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
```
In net/ipv4/ipmr.c (ffffffff81942246)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:mr_mfc_seq_stop
```
```
In net/ipv4/ipmr_base.c (ffffffff8194432f)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_rtm_dumproute
  - net/ipv4/ipmr_base.c:mr_rtm_dumproute
  - net/ipv4/ipmr_base.c:mr_mfc_seq_next
```
```
In net/ipv4/cipso_ipv4.c (ffffffff819470fd)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_invalidate
```
```
In net/xfrm/xfrm_policy.c (ffffffff8194c32a)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:__xfrm_sk_clone_policy
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_policy_walk
  - net/xfrm/xfrm_policy.c:xfrm_policy_flush
  - net/xfrm/xfrm_policy.c:xfrm_policy_flush
  - net/xfrm/xfrm_policy.c:xfrm_policy_flush
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff81951004)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_unregister_afinfo
  - net/xfrm/xfrm_state.c:xfrm_state_register_afinfo
  - net/xfrm/xfrm_state.c:xfrm_unregister_km
  - net/xfrm/xfrm_state.c:xfrm_register_km
  - net/xfrm/xfrm_state.c:xfrm_state_walk
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_find_acq_byseq
  - net/xfrm/xfrm_state.c:xfrm_find_acq
  - net/xfrm/xfrm_state.c:xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_state_lookup_byspi
  - net/xfrm/xfrm_state.c:xfrm_state_lookup_byspi
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_sad_getinfo
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_destroy
  - net/xfrm/xfrm_state.c:xfrm_state_gc_task
  - net/xfrm/xfrm_state.c:xfrm_unregister_mode
  - net/xfrm/xfrm_state.c:xfrm_register_mode
  - net/xfrm/xfrm_state.c:xfrm_unregister_type_offload
  - net/xfrm/xfrm_state.c:xfrm_register_type_offload
  - net/xfrm/xfrm_state.c:xfrm_unregister_type
  - net/xfrm/xfrm_state.c:xfrm_register_type
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_input.c (ffffffff81955784)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo
  - net/xfrm/xfrm_input.c:xfrm_input_register_afinfo
```
```
In net/xfrm/xfrm_output.c (ffffffff819568bd)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/af_inet6.c (ffffffff8195e0ca)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_register_protosw
```
```
In net/ipv6/addrconf.c (ffffffff8196f35d)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_start
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:ipv6_generate_stable_address
  - net/ipv6/addrconf.c:add_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/route.c (ffffffff81972be2)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_mtu_change_route
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:fib6_clean_tohost
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_del_rt
  - net/ipv6/route.c:fib6_table_lookup
  - net/ipv6/route.c:rt6_remove_exception_rt
  - net/ipv6/route.c:rt6_flush_exceptions
  - net/ipv6/route.c:rt6_insert_exception
  - net/ipv6/route.c:rt6_insert_exception
  - net/ipv6/route.c:__ip6_ins_rt
  - net/ipv6/route.c:rt6_uncached_list_add
```
```
In net/ipv6/ip6_fib.c (ffffffff81979f92)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:__fib6_clean_all
  - net/ipv6/ip6_fib.c:inet6_dump_fib
  - net/ipv6/ip6_fib.c:inet6_dump_fib
  - net/ipv6/ip6_fib.c:fib6_tables_dump
```
```
In net/ipv6/raw.c (ffffffff81987377)
Location: include/linux/spinlock.h:353
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff8198b197)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mcf_seq_stop
  - net/ipv6/mcast.c:igmp6_mcf_seq_next
  - net/ipv6/mcast.c:igmp6_mcf_seq_start
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:ip6_mc_del_src
  - net/ipv6/mcast.c:ip6_mc_del_src
  - net/ipv6/mcast.c:mld_send_report
  - net/ipv6/mcast.c:mld_send_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:mld_del_delrec
  - net/ipv6/mcast.c:mld_del_delrec
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/mcast.c:igmp6_group_added
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81999c6f)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:fl6_renew
  - net/ipv6/ip6_flowlabel.c:fl6_free_socklist
  - net/ipv6/ip6_flowlabel.c:fl6_free_socklist
  - net/ipv6/ip6_flowlabel.c:fl_release
```
```
In net/ipv6/ip6mr.c (ffffffff8199e999)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:mr_mfc_seq_stop
```
```
In net/ipv6/calipso.c (ffffffff819a5c52)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_cache_invalidate
```
```
In net/ipv6/seg6_hmac.c (ffffffff819a9e82)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
```
In net/packet/af_packet.c (ffffffff819b1338)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_ioctl
  - net/packet/af_packet.c:packet_getsockopt
  - net/packet/af_packet.c:packet_rcv_has_room
```
```
In net/dcb/dcbnl.c (ffffffff819c10ea)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_ieee_delapp
  - net/dcb/dcbnl.c:dcb_ieee_setapp
  - net/dcb/dcbnl.c:dcb_ieee_getapp_mask
  - net/dcb/dcbnl.c:dcb_setapp
  - net/dcb/dcbnl.c:dcb_getapp
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
```
```
In net/switchdev/switchdev.c (ffffffff819c488a)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_deferred_process
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
In kernel/cgroup/cgroup.c (ffffffff811478d8)
Location: include/linux/spinlock.h:372
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_idr_remove
  - kernel/cgroup/cgroup.c:cgroup_idr_replace
```
```
In kernel/bpf/core.c (ffffffff811c06c4)
Location: include/linux/spinlock.h:372
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
```
```
In kernel/bpf/syscall.c (ffffffff811c5401)
Location: include/linux/spinlock.h:372
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_obj_get_next_id
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In kernel/bpf/local_storage.c (ffffffff811d88c5)
Location: include/linux/spinlock.h:372
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_unlink
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_link
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_release
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_assign
  - kernel/bpf/local_storage.c:cgroup_storage_get_next_key
  - kernel/bpf/local_storage.c:cgroup_storage_get_next_key
  - kernel/bpf/local_storage.c:cgroup_storage_lookup
  - kernel/bpf/local_storage.c:cgroup_storage_lookup
```
```
In kernel/bpf/btf.c (ffffffff811dc847)
Location: include/linux/spinlock.h:372
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
```
```
In kernel/bpf/offload.c (ffffffff811df481)
Location: include/linux/spinlock.h:372
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In kernel/bpf/reuseport_array.c (ffffffff811e2acb)
Location: include/linux/spinlock.h:372
Inline: True
Inline callers:
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem
  - kernel/bpf/reuseport_array.c:reuseport_array_delete_elem
```
```
In kernel/padata.c (ffffffff811f8602)
Location: include/linux/spinlock.h:372
Inline: True
Inline callers:
  - kernel/padata.c:padata_reorder
  - kernel/padata.c:padata_reorder
```
```
In mm/page-writeback.c (ffffffff8120e191)
Location: include/linux/spinlock.h:372
Inline: True
Inline callers:
  - mm/page-writeback.c:bdi_set_max_ratio
  - mm/page-writeback.c:bdi_set_min_ratio
```
```
In mm/backing-dev.c (ffffffff8122b3d7)
Location: include/linux/spinlock.h:372
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:wb_wakeup_delayed
```
```
In fs/fs-writeback.c (ffffffff812e3776)
Location: include/linux/spinlock.h:372
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_queue_work
  - fs/fs-writeback.c:wb_wakeup
```
```
In ipc/util.c (ffffffff813f0e7b)
Location: include/linux/spinlock.h:372
Inline: True
Inline callers:
  - ipc/util.c:ipc_set_key_private
  - ipc/util.c:ipc_rmid
  - ipc/util.c:ipc_addid
  - ipc/util.c:ipc_addid
```
```
In security/selinux/netif.c (ffffffff81421e80)
Location: include/linux/spinlock.h:372
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_netdev_notifier_handler
  - security/selinux/netif.c:sel_netif_flush
  - security/selinux/netif.c:sel_netif_sid
```
```
In security/selinux/netnode.c (ffffffff814224c8)
Location: include/linux/spinlock.h:372
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_flush
  - security/selinux/netnode.c:sel_netnode_sid
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (ffffffff81422788)
Location: include/linux/spinlock.h:372
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_flush
  - security/selinux/netport.c:sel_netport_sid
  - security/selinux/netport.c:sel_netport_sid
```
```
In security/apparmor/policy_unpack.c (ffffffff8145bf8c)
Location: include/linux/spinlock.h:372
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In block/genhd.c (ffffffff814b1733)
Location: include/linux/spinlock.h:372
Inline: True
Inline callers:
  - block/genhd.c:get_gendisk
```
```
In lib/rhashtable.c (ffffffff814e17a8)
Location: include/linux/spinlock.h:372
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rht_deferred_worker
```
```
In drivers/connector/cn_queue.c (ffffffff81697c14)
Location: include/linux/spinlock.h:372
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_free_dev
  - drivers/connector/cn_queue.c:cn_queue_del_callback
  - drivers/connector/cn_queue.c:cn_queue_add_callback
```
```
In drivers/connector/connector.c (ffffffff81697d37)
Location: include/linux/spinlock.h:372
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_proc_show
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/net/tun.c (ffffffff8175f937)
Location: include/linux/spinlock.h:372
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_set_ebpf
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_flow_update
  - drivers/net/tun.c:tun_flow_flush
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817661cf)
Location: include/linux/spinlock.h:372
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_disconnect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_disconnect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_ccp_closed
  - drivers/net/ppp/ppp_generic.c:ppp_ccp_closed
  - drivers/net/ppp/ppp_generic.c:ppp_set_compress
  - drivers/net/ppp/ppp_generic.c:ppp_set_compress
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_input_error
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_dev_uninit
  - drivers/net/ppp/ppp_generic.c:ppp_dev_uninit
  - drivers/net/ppp/ppp_generic.c:ppp_get_stats64
  - drivers/net/ppp/ppp_generic.c:ppp_get_stats64
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_poll
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - drivers/net/ppp/ppp_generic.c:ppp_read
```
```
In drivers/net/xen-netfront.c (ffffffff8176e00d)
Location: include/linux/spinlock.h:372
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:netback_changed
```
```
In net/core/sock.c (ffffffff818988a7)
Location: include/linux/spinlock.h:372
Inline: True
Inline callers:
  - net/core/sock.c:release_sock
  - net/core/sock.c:__sk_flush_backlog
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__lock_sock
```
```
In net/core/request_sock.c (ffffffff8189a5bf)
Location: include/linux/spinlock.h:372
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/core/datagram.c (ffffffff818a3fef)
Location: include/linux/spinlock.h:372
Inline: True
Inline callers:
  - net/core/datagram.c:__sk_queue_drop_skb
```
```
In net/core/gen_stats.c (ffffffff818a6973)
Location: include/linux/spinlock.h:372
Inline: True
Inline callers:
  - net/core/gen_stats.c:gnet_stats_finish_copy
  - net/core/gen_stats.c:gnet_stats_finish_copy
  - net/core/gen_stats.c:gnet_stats_copy_queue
  - net/core/gen_stats.c:gnet_stats_copy_rate_est
  - net/core/gen_stats.c:___gnet_stats_copy_basic
```
```
In net/core/gen_estimator.c (ffffffff818a6d65)
Location: include/linux/spinlock.h:372
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/net_namespace.c (ffffffff818a7a99)
Location: include/linux/spinlock.h:372
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:peernet2id
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/dev.c (ffffffff818b8966)
Location: include/linux/spinlock.h:372
Inline: True
Inline callers:
  - net/core/dev.c:dev_set_rx_mode
  - net/core/dev.c:netif_set_real_num_tx_queues
```
```
In net/core/dev_addr_lists.c (ffffffff818c0d3a)
Location: include/linux/spinlock.h:372
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:dev_mc_flush
  - net/core/dev_addr_lists.c:__dev_mc_del
  - net/core/dev_addr_lists.c:__dev_mc_add
  - net/core/dev_addr_lists.c:dev_mc_add_excl
  - net/core/dev_addr_lists.c:dev_uc_flush
  - net/core/dev_addr_lists.c:dev_uc_del
  - net/core/dev_addr_lists.c:dev_uc_add
  - net/core/dev_addr_lists.c:dev_uc_add_excl
```
```
In net/core/neighbour.c (ffffffff818c7a2c)
Location: include/linux/spinlock.h:372
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/core/rtnetlink.c (ffffffff818cd77d)
Location: include/linux/spinlock.h:372
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_fdb_dump
```
```
In net/core/sock_reuseport.c (ffffffff818e0de0)
Location: include/linux/spinlock.h:372
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_attach_prog
  - net/core/sock_reuseport.c:reuseport_detach_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_alloc
  - net/core/sock_reuseport.c:reuseport_alloc
```
```
In net/core/xdp.c (ffffffff818e1e4c)
Location: include/linux/spinlock.h:372
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
```
```
In net/core/page_pool.c (ffffffff818e4e9d)
Location: include/linux/spinlock.h:372
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_empty_ring
```
```
In net/core/net-procfs.c (ffffffff818e59f9)
Location: include/linux/spinlock.h:372
Inline: True
```
```
In net/core/skmsg.c (ffffffff818e71ee)
Location: include/linux/spinlock.h:372
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_link_pop
```
```
In net/core/sock_map.c (ffffffff818f28ec)
Location: include/linux/spinlock.h:372
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_unref
```
```
In net/sched/sch_generic.c (ffffffff818f8bbb)
Location: include/linux/spinlock.h:372
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_graft_qdisc
```
```
In net/sched/sch_mq.c (ffffffff818f9270)
Location: include/linux/spinlock.h:372
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump
```
```
In net/sched/sch_api.c (ffffffff818fb79d)
Location: include/linux/spinlock.h:372
Inline: True
Inline callers:
  - net/sched/sch_api.c:tcf_node_bind
  - net/sched/sch_api.c:qdisc_class_hash_grow
```
```
In net/sched/cls_api.c (ffffffff819019e7)
Location: include/linux/spinlock.h:372
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tc_indr_block_cb_register
  - net/sched/cls_api.c:__tc_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffff81908a03)
Location: include/linux/spinlock.h:372
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_insert
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/ipv4/route.c (ffffffff819115e4)
Location: include/linux/spinlock.h:372
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_flush_dev
  - net/ipv4/route.c:ipv4_dst_destroy
  - net/ipv4/route.c:rt_add_uncached_list
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/inetpeer.c (ffffffff81914973)
Location: include/linux/spinlock.h:372
Inline: True
```
```
In net/ipv4/inet_hashtables.c (ffffffff81920a43)
Location: include/linux/spinlock.h:372
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_unhash
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81922a02)
Location: include/linux/spinlock.h:372
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp.c (ffffffff8192777f)
Location: include/linux/spinlock.h:372
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_ioctl
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8193f3ae)
Location: include/linux/spinlock.h:372
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_seq_stop
  - net/ipv4/tcp_ipv4.c:established_get_next
```
```
In net/ipv4/tcp_metrics.c (ffffffff819432af)
Location: include/linux/spinlock.h:372
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_flush_all
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/raw.c (ffffffff81947914)
Location: include/linux/spinlock.h:372
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819496fd)
Location: include/linux/spinlock.h:372
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_seq_stop
  - net/ipv4/udp.c:udp_get_next
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/af_inet.c (ffffffff819582a2)
Location: include/linux/spinlock.h:372
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_register_protosw
```
```
In net/ipv4/igmp.c (ffffffff8195ad27)
Location: include/linux/spinlock.h:372
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_mcf_seq_stop
  - net/ipv4/igmp.c:igmp_mcf_seq_next
  - net/ipv4/igmp.c:igmp_mcf_seq_start
  - net/ipv4/igmp.c:ip_mc_clear_src
  - net/ipv4/igmp.c:ip_mc_add_src
  - net/ipv4/igmp.c:ip_mc_del_src
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:igmp_group_dropped
  - net/ipv4/igmp.c:igmp_group_dropped
  - net/ipv4/igmp.c:igmpv3_clear_delrec
  - net/ipv4/igmp.c:igmpv3_clear_delrec
  - net/ipv4/igmp.c:igmpv3_del_delrec
  - net/ipv4/igmp.c:igmpv3_del_delrec
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:igmp_stop_timer
```
```
In net/ipv4/fib_semantics.c (ffffffff81963193)
Location: include/linux/spinlock.h:372
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_release_info
```
```
In net/ipv4/inet_fragment.c (ffffffff81968d87)
Location: include/linux/spinlock.h:372
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff8196cf5e)
Location: include/linux/spinlock.h:372
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
```
In net/ipv4/ipmr.c (ffffffff81972043)
Location: include/linux/spinlock.h:372
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:mr_mfc_seq_stop
```
```
In net/ipv4/ipmr_base.c (ffffffff81974509)
Location: include/linux/spinlock.h:372
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_table_dump
  - net/ipv4/ipmr_base.c:mr_table_dump
  - net/ipv4/ipmr_base.c:mr_mfc_seq_next
```
```
In net/ipv4/tcp_bpf.c (ffffffff819781fb)
Location: include/linux/spinlock.h:372
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_init
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81978ca4)
Location: include/linux/spinlock.h:372
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_invalidate
```
```
In net/xfrm/xfrm_policy.c (ffffffff81980364)
Location: include/linux/spinlock.h:372
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:__xfrm_sk_clone_policy
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_policy_walk
  - net/xfrm/xfrm_policy.c:xfrm_policy_flush
  - net/xfrm/xfrm_policy.c:xfrm_policy_flush
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff81984554)
Location: include/linux/spinlock.h:372
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_unregister_afinfo
  - net/xfrm/xfrm_state.c:xfrm_state_register_afinfo
  - net/xfrm/xfrm_state.c:xfrm_unregister_km
  - net/xfrm/xfrm_state.c:xfrm_register_km
  - net/xfrm/xfrm_state.c:xfrm_state_walk
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_find_acq_byseq
  - net/xfrm/xfrm_state.c:xfrm_find_acq
  - net/xfrm/xfrm_state.c:xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_state_lookup_byspi
  - net/xfrm/xfrm_state.c:xfrm_state_lookup_byspi
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_sad_getinfo
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_delete
  - net/xfrm/xfrm_state.c:xfrm_state_gc_task
  - net/xfrm/xfrm_state.c:xfrm_unregister_mode
  - net/xfrm/xfrm_state.c:xfrm_register_mode
  - net/xfrm/xfrm_state.c:xfrm_unregister_type_offload
  - net/xfrm/xfrm_state.c:xfrm_register_type_offload
  - net/xfrm/xfrm_state.c:xfrm_unregister_type
  - net/xfrm/xfrm_state.c:xfrm_register_type
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_input.c (ffffffff8198a394)
Location: include/linux/spinlock.h:372
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo
  - net/xfrm/xfrm_input.c:xfrm_input_register_afinfo
```
```
In net/xfrm/xfrm_output.c (ffffffff8198b522)
Location: include/linux/spinlock.h:372
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/af_inet6.c (ffffffff81992c2a)
Location: include/linux/spinlock.h:372
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_register_protosw
```
```
In net/ipv6/addrconf.c (ffffffff819a4f0d)
Location: include/linux/spinlock.h:372
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_start
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:ipv6_generate_stable_address
  - net/ipv6/addrconf.c:add_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/route.c (ffffffff819a8582)
Location: include/linux/spinlock.h:372
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_mtu_change_route
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:fib6_clean_tohost
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_del_rt
  - net/ipv6/route.c:fib6_table_lookup
  - net/ipv6/route.c:rt6_remove_exception_rt
  - net/ipv6/route.c:rt6_flush_exceptions
  - net/ipv6/route.c:rt6_insert_exception
  - net/ipv6/route.c:rt6_insert_exception
  - net/ipv6/route.c:__ip6_ins_rt
  - net/ipv6/route.c:rt6_uncached_list_add
```
```
In net/ipv6/ip6_fib.c (ffffffff819afb82)
Location: include/linux/spinlock.h:372
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:__fib6_clean_all
  - net/ipv6/ip6_fib.c:fib6_tables_dump
```
```
In net/ipv6/raw.c (ffffffff819bdfb4)
Location: include/linux/spinlock.h:372
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff819c1ab7)
Location: include/linux/spinlock.h:372
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mcf_seq_stop
  - net/ipv6/mcast.c:igmp6_mcf_seq_next
  - net/ipv6/mcast.c:igmp6_mcf_seq_start
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:ip6_mc_del_src
  - net/ipv6/mcast.c:ip6_mc_del_src
  - net/ipv6/mcast.c:mld_send_report
  - net/ipv6/mcast.c:mld_send_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:mld_del_delrec
  - net/ipv6/mcast.c:mld_del_delrec
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/mcast.c:igmp6_group_added
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff819d083f)
Location: include/linux/spinlock.h:372
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:fl6_renew
  - net/ipv6/ip6_flowlabel.c:fl6_free_socklist
  - net/ipv6/ip6_flowlabel.c:fl6_free_socklist
  - net/ipv6/ip6_flowlabel.c:fl_release
```
```
In net/ipv6/ip6mr.c (ffffffff819d5338)
Location: include/linux/spinlock.h:372
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:mr_mfc_seq_stop
```
```
In net/ipv6/calipso.c (ffffffff819dce00)
Location: include/linux/spinlock.h:372
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_cache_invalidate
```
```
In net/ipv6/seg6_hmac.c (ffffffff819e09a5)
Location: include/linux/spinlock.h:372
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
```
In net/packet/af_packet.c (ffffffff819e8721)
Location: include/linux/spinlock.h:372
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_ioctl
  - net/packet/af_packet.c:packet_getsockopt
  - net/packet/af_packet.c:packet_rcv_has_room
```
```
In net/dcb/dcbnl.c (ffffffff819f74de)
Location: include/linux/spinlock.h:372
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_ieee_getapp_default_prio_mask
  - net/dcb/dcbnl.c:dcb_ieee_getapp_dscp_prio_mask_map
  - net/dcb/dcbnl.c:dcb_ieee_getapp_prio_dscp_mask_map
  - net/dcb/dcbnl.c:dcb_ieee_delapp
  - net/dcb/dcbnl.c:dcb_ieee_setapp
  - net/dcb/dcbnl.c:dcb_ieee_getapp_mask
  - net/dcb/dcbnl.c:dcb_setapp
  - net/dcb/dcbnl.c:dcb_getapp
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
```
```
In net/switchdev/switchdev.c (ffffffff819fbd2a)
Location: include/linux/spinlock.h:372
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_deferred_process
```
```
In lib/xarray.c (ffffffff81a17d45)
Location: include/linux/spinlock.h:372
Inline: True
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
In kernel/cgroup/cgroup.c (ffffffff81152b48)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_idr_remove
  - kernel/cgroup/cgroup.c:cgroup_idr_replace
```
```
In kernel/bpf/core.c (ffffffff811d11da)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
```
```
In kernel/bpf/syscall.c (ffffffff811d5ae2)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_obj_get_next_id
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
```
```
In kernel/bpf/local_storage.c (ffffffff811ed3b3)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_unlink
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_link
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_release
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_assign
  - kernel/bpf/local_storage.c:cgroup_storage_get_next_key
  - kernel/bpf/local_storage.c:cgroup_storage_get_next_key
  - kernel/bpf/local_storage.c:cgroup_storage_lookup
  - kernel/bpf/local_storage.c:cgroup_storage_lookup
```
```
In kernel/bpf/btf.c (ffffffff811f1fa9)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
```
```
In kernel/bpf/reuseport_array.c (ffffffff811f9c51)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem
  - kernel/bpf/reuseport_array.c:reuseport_array_delete_elem
```
```
In kernel/padata.c (ffffffff812100e0)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - kernel/padata.c:padata_reorder
  - kernel/padata.c:padata_reorder
```
```
In mm/page-writeback.c (ffffffff8121dae1)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - mm/page-writeback.c:bdi_set_max_ratio
  - mm/page-writeback.c:bdi_set_min_ratio
```
```
In mm/backing-dev.c (ffffffff8123b025)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:wb_wakeup_delayed
```
```
In fs/fs-writeback.c (ffffffff81301eb6)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_queue_work
  - fs/fs-writeback.c:wb_wakeup
```
```
In security/selinux/netif.c (ffffffff8144fa80)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_netdev_notifier_handler
  - security/selinux/netif.c:sel_netif_flush
  - security/selinux/netif.c:sel_netif_sid
```
```
In security/selinux/netnode.c (ffffffff81450103)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_flush
  - security/selinux/netnode.c:sel_netnode_sid
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (ffffffff81450413)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_flush
  - security/selinux/netport.c:sel_netport_sid
  - security/selinux/netport.c:sel_netport_sid
```
```
In block/genhd.c (ffffffff814dfae2)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - block/genhd.c:get_gendisk
```
```
In block/blk-cgroup.c (ffffffff814f1875)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - block/blk-cgroup.c:__blkcg_punt_bio_submit
  - block/blk-cgroup.c:blkg_async_bio_workfn
```
```
In drivers/connector/cn_queue.c (ffffffff816d078f)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_free_dev
  - drivers/connector/cn_queue.c:cn_queue_del_callback
  - drivers/connector/cn_queue.c:cn_queue_add_callback
```
```
In drivers/connector/connector.c (ffffffff816d08b2)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_proc_show
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/net/tun.c (ffffffff8179d167)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_set_ebpf
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_flow_update
  - drivers/net/tun.c:tun_flow_flush
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817a38db)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_disconnect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_disconnect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_ccp_closed
  - drivers/net/ppp/ppp_generic.c:ppp_ccp_closed
  - drivers/net/ppp/ppp_generic.c:ppp_set_compress
  - drivers/net/ppp/ppp_generic.c:ppp_set_compress
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_input_error
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_dev_uninit
  - drivers/net/ppp/ppp_generic.c:ppp_dev_uninit
  - drivers/net/ppp/ppp_generic.c:ppp_get_stats64
  - drivers/net/ppp/ppp_generic.c:ppp_get_stats64
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_poll
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - drivers/net/ppp/ppp_generic.c:ppp_read
```
```
In drivers/net/xen-netfront.c (ffffffff817ac22d)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:netback_changed
```
```
In net/core/sock.c (ffffffff818e2e47)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/sock.c:release_sock
  - net/core/sock.c:__sk_flush_backlog
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__lock_sock
```
```
In net/core/request_sock.c (ffffffff818e4c9f)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/core/datagram.c (ffffffff818ef2e6)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/datagram.c:__sk_queue_drop_skb
```
```
In net/core/gen_stats.c (ffffffff818f1de3)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/gen_stats.c:gnet_stats_finish_copy
  - net/core/gen_stats.c:gnet_stats_finish_copy
  - net/core/gen_stats.c:gnet_stats_copy_queue
  - net/core/gen_stats.c:gnet_stats_copy_rate_est
  - net/core/gen_stats.c:___gnet_stats_copy_basic
```
```
In net/core/gen_estimator.c (ffffffff818f21f5)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/net_namespace.c (ffffffff818f376e)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:peernet2id
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/dev.c (ffffffff81904b27)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/dev.c:dev_set_rx_mode
  - net/core/dev.c:netif_set_real_num_tx_queues
```
```
In net/core/dev_addr_lists.c (ffffffff8190d44a)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:dev_mc_flush
  - net/core/dev_addr_lists.c:__dev_mc_del
  - net/core/dev_addr_lists.c:__dev_mc_add
  - net/core/dev_addr_lists.c:dev_mc_add_excl
  - net/core/dev_addr_lists.c:dev_uc_flush
  - net/core/dev_addr_lists.c:dev_uc_del
  - net/core/dev_addr_lists.c:dev_uc_add
  - net/core/dev_addr_lists.c:dev_uc_add_excl
```
```
In net/core/neighbour.c (ffffffff81914144)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/core/rtnetlink.c (ffffffff8191a463)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_fdb_dump
```
```
In net/core/sock_reuseport.c (ffffffff8192f5b2)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_attach_prog
  - net/core/sock_reuseport.c:reuseport_detach_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_alloc
  - net/core/sock_reuseport.c:reuseport_alloc
```
```
In net/core/page_pool.c (ffffffff819347d0)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_request_shutdown
```
```
In net/core/net-procfs.c (ffffffff81935262)
Location: include/linux/spinlock.h:381
Inline: True
```
```
In net/core/skmsg.c (ffffffff81936b7f)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_link_pop
```
```
In net/core/sock_map.c (ffffffff81944a38)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_unref
```
```
In net/sched/sch_generic.c (ffffffff8195838b)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_graft_qdisc
```
```
In net/sched/sch_mq.c (ffffffff81958aad)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump
```
```
In net/sched/sch_api.c (ffffffff8195b720)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_grow
```
```
In net/ipv4/route.c (ffffffff81973c2a)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_flush_dev
  - net/ipv4/route.c:ipv4_dst_destroy
  - net/ipv4/route.c:rt_add_uncached_list
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/inetpeer.c (ffffffff81976d94)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/inet_hashtables.c (ffffffff81983522)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_unhash
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8198540d)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp.c (ffffffff81988a89)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_ioctl
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a2fde)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_seq_stop
  - net/ipv4/tcp_ipv4.c:established_get_next
```
```
In net/ipv4/tcp_metrics.c (ffffffff819a786a)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_flush_all
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/raw.c (ffffffff819abfbb)
Location: include/linux/spinlock.h:381
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819add70)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_seq_stop
  - net/ipv4/udp.c:udp_get_next
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/af_inet.c (ffffffff819bcdc6)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_register_protosw
```
```
In net/ipv4/igmp.c (ffffffff819bf9c7)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_mcf_seq_stop
  - net/ipv4/igmp.c:igmp_mcf_seq_next
  - net/ipv4/igmp.c:igmp_mcf_seq_start
  - net/ipv4/igmp.c:ip_mc_clear_src
  - net/ipv4/igmp.c:ip_mc_add_src
  - net/ipv4/igmp.c:ip_mc_del_src
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:igmpv3_clear_delrec
  - net/ipv4/igmp.c:igmpv3_clear_delrec
  - net/ipv4/igmp.c:igmpv3_del_delrec
  - net/ipv4/igmp.c:igmpv3_del_delrec
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:igmp_stop_timer
```
```
In net/ipv4/fib_semantics.c (ffffffff819c92d7)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_release_info
```
```
In net/ipv4/inet_fragment.c (ffffffff819cef59)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frags_free_cb
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff819d685e)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
```
In net/ipv4/ipmr.c (ffffffff819dba53)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:mr_mfc_seq_stop
```
```
In net/ipv4/ipmr_base.c (ffffffff819de035)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_table_dump
  - net/ipv4/ipmr_base.c:mr_table_dump
  - net/ipv4/ipmr_base.c:mr_mfc_seq_next
```
```
In net/ipv4/tcp_bpf.c (ffffffff819e1ce3)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_init
```
```
In net/ipv4/cipso_ipv4.c (ffffffff819e2765)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_invalidate
```
```
In net/xfrm/xfrm_policy.c (ffffffff819ea0ac)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:__xfrm_sk_clone_policy
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_policy_walk
  - net/xfrm/xfrm_policy.c:xfrm_policy_flush
  - net/xfrm/xfrm_policy.c:xfrm_policy_flush
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff819ee27e)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_unregister_afinfo
  - net/xfrm/xfrm_state.c:xfrm_state_register_afinfo
  - net/xfrm/xfrm_state.c:xfrm_unregister_km
  - net/xfrm/xfrm_state.c:xfrm_register_km
  - net/xfrm/xfrm_state.c:xfrm_state_walk
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_find_acq_byseq
  - net/xfrm/xfrm_state.c:xfrm_find_acq
  - net/xfrm/xfrm_state.c:xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_state_lookup_byspi
  - net/xfrm/xfrm_state.c:xfrm_state_lookup_byspi
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_sad_getinfo
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_delete
  - net/xfrm/xfrm_state.c:xfrm_state_gc_task
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_input.c (ffffffff819f469e)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo
  - net/xfrm/xfrm_input.c:xfrm_input_register_afinfo
```
```
In net/xfrm/xfrm_output.c (ffffffff819f69f7)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/af_inet6.c (ffffffff819fe68b)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_register_protosw
```
```
In net/ipv6/addrconf.c (ffffffff81a11211)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_start
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:ipv6_generate_stable_address
  - net/ipv6/addrconf.c:add_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/route.c (ffffffff81a14974)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_del_rt
  - net/ipv6/route.c:fib6_table_lookup
  - net/ipv6/route.c:fib6_nh_remove_exception
  - net/ipv6/route.c:fib6_nh_flush_exceptions
  - net/ipv6/route.c:rt6_insert_exception
  - net/ipv6/route.c:rt6_insert_exception
  - net/ipv6/route.c:__ip6_ins_rt
  - net/ipv6/route.c:rt6_uncached_list_add
```
```
In net/ipv6/ip6_fib.c (ffffffff81a1dd06)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:__fib6_clean_all
  - net/ipv6/ip6_fib.c:fib6_update_sernum_stub
  - net/ipv6/ip6_fib.c:fib6_tables_dump
```
```
In net/ipv6/raw.c (ffffffff81a2cabb)
Location: include/linux/spinlock.h:381
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff81a30887)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mcf_seq_stop
  - net/ipv6/mcast.c:igmp6_mcf_seq_next
  - net/ipv6/mcast.c:igmp6_mcf_seq_start
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:ip6_mc_del_src
  - net/ipv6/mcast.c:ip6_mc_del_src
  - net/ipv6/mcast.c:mld_send_report
  - net/ipv6/mcast.c:mld_send_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:mld_del_delrec
  - net/ipv6/mcast.c:mld_del_delrec
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/mcast.c:igmp6_group_added
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81a3f2ad)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:fl6_renew
  - net/ipv6/ip6_flowlabel.c:fl6_free_socklist
  - net/ipv6/ip6_flowlabel.c:fl6_free_socklist
  - net/ipv6/ip6_flowlabel.c:fl_release
```
```
In net/ipv6/ip6mr.c (ffffffff81a4426b)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:mr_mfc_seq_stop
```
```
In net/ipv6/calipso.c (ffffffff81a4ba0c)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_cache_invalidate
```
```
In net/packet/af_packet.c (ffffffff81a58afe)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_getsockopt
```
```
In net/dcb/dcbnl.c (ffffffff81a66a0b)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_ieee_getapp_default_prio_mask
  - net/dcb/dcbnl.c:dcb_ieee_getapp_dscp_prio_mask_map
  - net/dcb/dcbnl.c:dcb_ieee_getapp_prio_dscp_mask_map
  - net/dcb/dcbnl.c:dcb_ieee_delapp
  - net/dcb/dcbnl.c:dcb_ieee_setapp
  - net/dcb/dcbnl.c:dcb_ieee_getapp_mask
  - net/dcb/dcbnl.c:dcb_setapp
  - net/dcb/dcbnl.c:dcb_getapp
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
```
```
In net/switchdev/switchdev.c (ffffffff81a6b328)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_deferred_process
```
```
In net/xdp/xsk.c (ffffffff81a75234)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_generic_rcv
  - net/xdp/xsk.c:xsk_generic_rcv
```
```
In lib/xarray.c (ffffffff81a86cc2)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - lib/xarray.c:__xas_nomem
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
In kernel/cgroup/cgroup.c (ffffffff8115e798)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_idr_remove
  - kernel/cgroup/cgroup.c:cgroup_idr_replace
```
```
In kernel/bpf/core.c (ffffffff811dd76a)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
```
```
In kernel/bpf/syscall.c (ffffffff811e1f59)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_obj_get_next_id
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_map_inc_not_zero
  - kernel/bpf/syscall.c:map_create
```
```
In kernel/bpf/local_storage.c (ffffffff811f9b03)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_unlink
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_link
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_release
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_assign
  - kernel/bpf/local_storage.c:cgroup_storage_get_next_key
  - kernel/bpf/local_storage.c:cgroup_storage_get_next_key
  - kernel/bpf/local_storage.c:cgroup_storage_lookup
  - kernel/bpf/local_storage.c:cgroup_storage_lookup
```
```
In kernel/bpf/btf.c (ffffffff811fe6b9)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
```
```
In kernel/bpf/xskmap.c (ffffffff8120167d)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - kernel/bpf/xskmap.c:xsk_map_try_sock_delete
  - kernel/bpf/xskmap.c:xsk_map_delete_elem
  - kernel/bpf/xskmap.c:xsk_map_update_elem
  - kernel/bpf/xskmap.c:xsk_map_update_elem
  - kernel/bpf/xskmap.c:xsk_map_update_elem
  - kernel/bpf/xskmap.c:xsk_map_sock_delete
```
```
In kernel/bpf/reuseport_array.c (ffffffff81206d21)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem
  - kernel/bpf/reuseport_array.c:reuseport_array_delete_elem
```
```
In kernel/padata.c (ffffffff8121e1c0)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - kernel/padata.c:padata_reorder
```
```
In mm/page-writeback.c (ffffffff8122b581)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - mm/page-writeback.c:bdi_set_max_ratio
  - mm/page-writeback.c:bdi_set_min_ratio
```
```
In mm/backing-dev.c (ffffffff81249546)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:bdi_get_by_id
  - mm/backing-dev.c:wb_wakeup_delayed
```
```
In fs/fs-writeback.c (ffffffff81314fb9)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_queue_work
  - fs/fs-writeback.c:wb_wakeup
```
```
In security/selinux/netif.c (ffffffff814698f0)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_netdev_notifier_handler
  - security/selinux/netif.c:sel_netif_flush
  - security/selinux/netif.c:sel_netif_sid
```
```
In security/selinux/netnode.c (ffffffff81469f23)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_flush
  - security/selinux/netnode.c:sel_netnode_sid
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (ffffffff8146a1d3)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_flush
  - security/selinux/netport.c:sel_netport_sid
  - security/selinux/netport.c:sel_netport_sid
```
```
In block/genhd.c (ffffffff814f8f12)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - block/genhd.c:get_gendisk
```
```
In block/blk-cgroup.c (ffffffff8150ae65)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - block/blk-cgroup.c:__blkcg_punt_bio_submit
  - block/blk-cgroup.c:blkg_async_bio_workfn
```
```
In drivers/connector/cn_queue.c (ffffffff816f45af)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_free_dev
  - drivers/connector/cn_queue.c:cn_queue_del_callback
  - drivers/connector/cn_queue.c:cn_queue_add_callback
```
```
In drivers/connector/connector.c (ffffffff816f46d2)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_proc_show
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/net/tun.c (ffffffff817c0c07)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_set_ebpf
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_flow_update
  - drivers/net/tun.c:tun_flow_flush
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817c732b)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_disconnect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_disconnect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_ccp_closed
  - drivers/net/ppp/ppp_generic.c:ppp_ccp_closed
  - drivers/net/ppp/ppp_generic.c:ppp_set_compress
  - drivers/net/ppp/ppp_generic.c:ppp_set_compress
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_input_error
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_dev_uninit
  - drivers/net/ppp/ppp_generic.c:ppp_dev_uninit
  - drivers/net/ppp/ppp_generic.c:ppp_get_stats64
  - drivers/net/ppp/ppp_generic.c:ppp_get_stats64
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_poll
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - drivers/net/ppp/ppp_generic.c:ppp_read
```
```
In drivers/net/xen-netfront.c (ffffffff817cfc6d)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:netback_changed
```
```
In net/core/sock.c (ffffffff81915027)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/sock.c:release_sock
  - net/core/sock.c:__sk_flush_backlog
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__lock_sock
```
```
In net/core/request_sock.c (ffffffff81916e2f)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/core/datagram.c (ffffffff81921296)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/datagram.c:__sk_queue_drop_skb
```
```
In net/core/gen_stats.c (ffffffff81923d33)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/gen_stats.c:gnet_stats_finish_copy
  - net/core/gen_stats.c:gnet_stats_finish_copy
  - net/core/gen_stats.c:gnet_stats_copy_queue
  - net/core/gen_stats.c:gnet_stats_copy_rate_est
  - net/core/gen_stats.c:___gnet_stats_copy_basic
```
```
In net/core/gen_estimator.c (ffffffff81924145)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/net_namespace.c (ffffffff8192571e)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:peernet2id
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/dev.c (ffffffff81937197)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/dev.c:dev_set_rx_mode
  - net/core/dev.c:netif_set_real_num_tx_queues
```
```
In net/core/dev_addr_lists.c (ffffffff8193fb4a)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:dev_mc_flush
  - net/core/dev_addr_lists.c:__dev_mc_del
  - net/core/dev_addr_lists.c:__dev_mc_add
  - net/core/dev_addr_lists.c:dev_mc_add_excl
  - net/core/dev_addr_lists.c:dev_uc_flush
  - net/core/dev_addr_lists.c:dev_uc_del
  - net/core/dev_addr_lists.c:dev_uc_add
  - net/core/dev_addr_lists.c:dev_uc_add_excl
```
```
In net/core/neighbour.c (ffffffff819467b4)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/core/rtnetlink.c (ffffffff8194ca83)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_fdb_dump
```
```
In net/core/sock_reuseport.c (ffffffff81961822)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_attach_prog
  - net/core/sock_reuseport.c:reuseport_detach_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_alloc
  - net/core/sock_reuseport.c:reuseport_alloc
```
```
In net/core/page_pool.c (ffffffff8196757f)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
```
```
In net/core/net-procfs.c (ffffffff81968022)
Location: include/linux/spinlock.h:381
Inline: True
```
```
In net/core/skmsg.c (ffffffff81969a4f)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_link_pop
```
```
In net/core/sock_map.c (ffffffff81979a38)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_unref
```
```
In net/core/devlink.c (ffffffff81982cbf)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_port_type_set
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
```
```
In net/sched/sch_generic.c (ffffffff8198e83b)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_graft_qdisc
```
```
In net/sched/sch_mq.c (ffffffff8198ef4d)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump
```
```
In net/sched/sch_api.c (ffffffff81990beb)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/sched/sch_api.c:tcf_node_bind
  - net/sched/sch_api.c:qdisc_class_hash_grow
```
```
In net/ipv4/route.c (ffffffff819aa64a)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_flush_dev
  - net/ipv4/route.c:ipv4_dst_destroy
  - net/ipv4/route.c:rt_add_uncached_list
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/inetpeer.c (ffffffff819ad724)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/inet_hashtables.c (ffffffff819b9d98)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_unhash
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819bbc22)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp.c (ffffffff819bfee4)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_ioctl
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819d9bde)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_seq_stop
  - net/ipv4/tcp_ipv4.c:established_get_next
```
```
In net/ipv4/tcp_metrics.c (ffffffff819de8ed)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_flush_all
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/raw.c (ffffffff819e2c6b)
Location: include/linux/spinlock.h:381
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819e4a80)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_seq_stop
  - net/ipv4/udp.c:udp_get_next
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/af_inet.c (ffffffff819f39d6)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_register_protosw
```
```
In net/ipv4/igmp.c (ffffffff819f6567)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_mcf_seq_stop
  - net/ipv4/igmp.c:igmp_mcf_seq_next
  - net/ipv4/igmp.c:igmp_mcf_seq_start
  - net/ipv4/igmp.c:ip_mc_clear_src
  - net/ipv4/igmp.c:ip_mc_add_src
  - net/ipv4/igmp.c:ip_mc_del_src
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:igmpv3_clear_delrec
  - net/ipv4/igmp.c:igmpv3_clear_delrec
  - net/ipv4/igmp.c:igmpv3_del_delrec
  - net/ipv4/igmp.c:igmpv3_del_delrec
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:igmp_stop_timer
```
```
In net/ipv4/fib_semantics.c (ffffffff819ffe90)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_release_info
```
```
In net/ipv4/inet_fragment.c (ffffffff81a05af9)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frags_free_cb
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81a0d34e)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
```
In net/ipv4/ipmr.c (ffffffff81a12983)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:mr_mfc_seq_stop
```
```
In net/ipv4/ipmr_base.c (ffffffff81a150d5)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_table_dump
  - net/ipv4/ipmr_base.c:mr_table_dump
  - net/ipv4/ipmr_base.c:mr_mfc_seq_next
```
```
In net/ipv4/tcp_bpf.c (ffffffff81a18cd3)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_init
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81a19755)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_invalidate
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a210f4)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:__xfrm_sk_clone_policy
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_policy_walk
  - net/xfrm/xfrm_policy.c:xfrm_policy_flush
  - net/xfrm/xfrm_policy.c:xfrm_policy_flush
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff81a250ea)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_unregister_afinfo
  - net/xfrm/xfrm_state.c:xfrm_state_register_afinfo
  - net/xfrm/xfrm_state.c:xfrm_unregister_km
  - net/xfrm/xfrm_state.c:xfrm_register_km
  - net/xfrm/xfrm_state.c:xfrm_state_walk
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_find_acq_byseq
  - net/xfrm/xfrm_state.c:xfrm_find_acq
  - net/xfrm/xfrm_state.c:xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_state_lookup_byspi
  - net/xfrm/xfrm_state.c:xfrm_state_lookup_byspi
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_sad_getinfo
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_delete
  - net/xfrm/xfrm_state.c:xfrm_state_gc_task
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_input.c (ffffffff81a2b34e)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo
  - net/xfrm/xfrm_input.c:xfrm_input_register_afinfo
```
```
In net/xfrm/xfrm_output.c (ffffffff81a2d65f)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/af_inet6.c (ffffffff81a3527b)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_register_protosw
```
```
In net/ipv6/addrconf.c (ffffffff81a47f7c)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_start
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:ipv6_generate_stable_address
  - net/ipv6/addrconf.c:add_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/route.c (ffffffff81a4b564)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_del_rt
  - net/ipv6/route.c:fib6_table_lookup
  - net/ipv6/route.c:fib6_nh_remove_exception
  - net/ipv6/route.c:fib6_nh_flush_exceptions
  - net/ipv6/route.c:rt6_insert_exception
  - net/ipv6/route.c:rt6_insert_exception
  - net/ipv6/route.c:__ip6_ins_rt
  - net/ipv6/route.c:rt6_uncached_list_add
```
```
In net/ipv6/ip6_fib.c (ffffffff81a54936)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:__fib6_clean_all
  - net/ipv6/ip6_fib.c:fib6_update_sernum_stub
  - net/ipv6/ip6_fib.c:fib6_tables_dump
```
```
In net/ipv6/raw.c (ffffffff81a6378b)
Location: include/linux/spinlock.h:381
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff81a673d7)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mcf_seq_stop
  - net/ipv6/mcast.c:igmp6_mcf_seq_next
  - net/ipv6/mcast.c:igmp6_mcf_seq_start
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:ip6_mc_del_src
  - net/ipv6/mcast.c:ip6_mc_del_src
  - net/ipv6/mcast.c:mld_send_report
  - net/ipv6/mcast.c:mld_send_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:mld_del_delrec
  - net/ipv6/mcast.c:mld_del_delrec
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/mcast.c:igmp6_group_added
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81a75f1d)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:fl6_renew
  - net/ipv6/ip6_flowlabel.c:fl6_free_socklist
  - net/ipv6/ip6_flowlabel.c:fl6_free_socklist
  - net/ipv6/ip6_flowlabel.c:fl_release
```
```
In net/ipv6/ip6mr.c (ffffffff81a7ae5b)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:mr_mfc_seq_stop
```
```
In net/ipv6/calipso.c (ffffffff81a825dc)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_cache_invalidate
```
```
In net/packet/af_packet.c (ffffffff81a8ec20)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_getsockopt
```
```
In net/dcb/dcbnl.c (ffffffff81a9d52b)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_ieee_getapp_default_prio_mask
  - net/dcb/dcbnl.c:dcb_ieee_getapp_dscp_prio_mask_map
  - net/dcb/dcbnl.c:dcb_ieee_getapp_prio_dscp_mask_map
  - net/dcb/dcbnl.c:dcb_ieee_delapp
  - net/dcb/dcbnl.c:dcb_ieee_setapp
  - net/dcb/dcbnl.c:dcb_ieee_getapp_mask
  - net/dcb/dcbnl.c:dcb_setapp
  - net/dcb/dcbnl.c:dcb_getapp
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
```
```
In net/switchdev/switchdev.c (ffffffff81aa1d18)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_deferred_process
```
```
In net/xdp/xsk.c (ffffffff81aab21c)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xsk.c:xsk_generic_rcv
  - net/xdp/xsk.c:xsk_generic_rcv
```
```
In lib/xarray.c (ffffffff81abdf32)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - lib/xarray.c:__xas_nomem
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
In kernel/cgroup/cgroup.c (ffffffff81170359)
Location: include/linux/spinlock.h:396
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_create
  - kernel/cgroup/cgroup.c:css_create
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
```
```
In kernel/bpf/core.c (ffffffff811fa116)
Location: include/linux/spinlock.h:396
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_ksym_del
  - kernel/bpf/core.c:bpf_ksym_add
```
```
In kernel/bpf/syscall.c (ffffffff81201b2d)
Location: include/linux/spinlock.h:396
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_link_get_fd_by_id
  - kernel/bpf/syscall.c:bpf_map_get_fd_by_id
  - kernel/bpf/syscall.c:bpf_map_get_curr_or_next
  - kernel/bpf/syscall.c:bpf_obj_get_next_id
  - kernel/bpf/syscall.c:bpf_raw_tracepoint_open
  - kernel/bpf/syscall.c:bpf_raw_tracepoint_open
  - kernel/bpf/syscall.c:bpf_raw_tracepoint_open
  - kernel/bpf/syscall.c:bpf_link_prime
  - kernel/bpf/syscall.c:bpf_link_prime
  - kernel/bpf/syscall.c:bpf_link_free
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_map_inc_not_zero
  - kernel/bpf/syscall.c:map_create
```
```
In kernel/bpf/local_storage.c (ffffffff8121d973)
Location: include/linux/spinlock.h:396
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_unlink
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_link
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_release
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_assign
  - kernel/bpf/local_storage.c:cgroup_storage_get_next_key
  - kernel/bpf/local_storage.c:cgroup_storage_get_next_key
  - kernel/bpf/local_storage.c:cgroup_storage_lookup_elem
  - kernel/bpf/local_storage.c:cgroup_storage_lookup_elem
```
```
In kernel/bpf/btf.c (ffffffff81225e21)
Location: include/linux/spinlock.h:396
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
```
```
In kernel/bpf/reuseport_array.c (ffffffff8122f35a)
Location: include/linux/spinlock.h:396
Inline: True
Inline callers:
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem
  - kernel/bpf/reuseport_array.c:reuseport_array_delete_elem
```
```
In kernel/padata.c (ffffffff8124a6d0)
Location: include/linux/spinlock.h:396
Inline: True
Inline callers:
  - kernel/padata.c:padata_reorder
```
```
In kernel/watch_queue.c (ffffffff8124d403)
Location: include/linux/spinlock.h:396
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_clear
  - kernel/watch_queue.c:watch_queue_clear
  - kernel/watch_queue.c:remove_watch_from_object
  - kernel/watch_queue.c:add_watch_to_object
```
```
In mm/page-writeback.c (ffffffff81258491)
Location: include/linux/spinlock.h:396
Inline: True
Inline callers:
  - mm/page-writeback.c:bdi_set_max_ratio
  - mm/page-writeback.c:bdi_set_min_ratio
```
```
In mm/backing-dev.c (ffffffff8127789d)
Location: include/linux/spinlock.h:396
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:bdi_get_by_id
  - mm/backing-dev.c:wb_shutdown
  - mm/backing-dev.c:wb_shutdown
  - mm/backing-dev.c:wb_wakeup_delayed
```
```
In fs/fs-writeback.c (ffffffff81349123)
Location: include/linux/spinlock.h:396
Inline: True
Inline callers:
  - fs/fs-writeback.c:wakeup_dirtytime_writeback
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:wakeup_flusher_threads_bdi
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_do_writeback
  - fs/fs-writeback.c:wb_start_background_writeback
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:wb_queue_work
```
```
In security/selinux/netif.c (ffffffff814bda94)
Location: include/linux/spinlock.h:396
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_netdev_notifier_handler
  - security/selinux/netif.c:sel_netif_flush
  - security/selinux/netif.c:sel_netif_sid_slow
```
```
In security/selinux/netnode.c (ffffffff814be133)
Location: include/linux/spinlock.h:396
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_flush
  - security/selinux/netnode.c:sel_netnode_sid
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (ffffffff814be423)
Location: include/linux/spinlock.h:396
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_flush
  - security/selinux/netport.c:sel_netport_sid_slow
  - security/selinux/netport.c:sel_netport_sid_slow
```
```
In block/genhd.c (ffffffff81559df9)
Location: include/linux/spinlock.h:396
Inline: True
Inline callers:
  - block/genhd.c:disk_release
  - block/genhd.c:get_gendisk
  - block/genhd.c:del_gendisk
```
```
In block/blk-cgroup.c (ffffffff8156bee5)
Location: include/linux/spinlock.h:396
Inline: True
Inline callers:
  - block/blk-cgroup.c:__blkcg_punt_bio_submit
  - block/blk-cgroup.c:blkg_async_bio_workfn
```
```
In lib/xarray.c (ffffffff815fb87f)
Location: include/linux/spinlock.h:396
Inline: True
Inline callers:
  - lib/xarray.c:__xas_nomem
```
```
In drivers/connector/cn_queue.c (ffffffff817accef)
Location: include/linux/spinlock.h:396
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_free_dev
  - drivers/connector/cn_queue.c:cn_queue_del_callback
  - drivers/connector/cn_queue.c:cn_queue_add_callback
```
```
In drivers/connector/connector.c (ffffffff817ace12)
Location: include/linux/spinlock.h:396
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_proc_show
  - drivers/connector/connector.c:cn_call_callback
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/scsi/sd_zbc.c (ffffffff81848ba7)
Location: include/linux/spinlock.h:396
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_zone_wp_update
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
  - drivers/scsi/sd_zbc.c:sd_zbc_update_wp_offset_workfn
  - drivers/scsi/sd_zbc.c:sd_zbc_update_wp_offset_workfn
```
```
In drivers/net/tun.c (ffffffff8188b307)
Location: include/linux/spinlock.h:396
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_free_netdev
  - drivers/net/tun.c:tun_free_netdev
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_flow_update
  - drivers/net/tun.c:tun_flow_flush
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81891e0b)
Location: include/linux/spinlock.h:396
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_disconnect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_disconnect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_connect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_connect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_connect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_connect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_connect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_connect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_ccp_closed
  - drivers/net/ppp/ppp_generic.c:ppp_ccp_closed
  - drivers/net/ppp/ppp_generic.c:ppp_set_compress
  - drivers/net/ppp/ppp_generic.c:ppp_set_compress
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_input_error
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_dev_uninit
  - drivers/net/ppp/ppp_generic.c:ppp_dev_uninit
  - drivers/net/ppp/ppp_generic.c:ppp_get_stats64
  - drivers/net/ppp/ppp_generic.c:ppp_get_stats64
  - drivers/net/ppp/ppp_generic.c:ppp_compat_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_compat_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_poll
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - drivers/net/ppp/ppp_generic.c:ppp_read
```
```
In drivers/net/xen-netfront.c (ffffffff8189a49d)
Location: include/linux/spinlock.h:396
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:xennet_release_rx_bufs
  - drivers/net/xen-netfront.c:xennet_open
```
```
In net/core/sock.c (ffffffff819e8147)
Location: include/linux/spinlock.h:396
Inline: True
Inline callers:
  - net/core/sock.c:release_sock
  - net/core/sock.c:__sk_flush_backlog
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__lock_sock
```
```
In net/core/request_sock.c (ffffffff819e97af)
Location: include/linux/spinlock.h:396
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/core/datagram.c (ffffffff819f4be7)
Location: include/linux/spinlock.h:396
Inline: True
Inline callers:
  - net/core/datagram.c:__sk_queue_drop_skb
```
```
In net/core/gen_stats.c (ffffffff819f7763)
Location: include/linux/spinlock.h:396
Inline: True
Inline callers:
  - net/core/gen_stats.c:gnet_stats_finish_copy
  - net/core/gen_stats.c:gnet_stats_finish_copy
  - net/core/gen_stats.c:gnet_stats_copy_app
  - net/core/gen_stats.c:gnet_stats_copy_app
  - net/core/gen_stats.c:gnet_stats_copy_queue
  - net/core/gen_stats.c:gnet_stats_copy_rate_est
  - net/core/gen_stats.c:___gnet_stats_copy_basic
  - net/core/gen_stats.c:gnet_stats_start_copy_compat
```
```
In net/core/gen_estimator.c (ffffffff819f7cf7)
Location: include/linux/spinlock.h:396
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/net_namespace.c (ffffffff819f904a)
Location: include/linux/spinlock.h:396
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:unhash_nsid
  - net/core/net_namespace.c:unhash_nsid
  - net/core/net_namespace.c:peernet2id_alloc
  - net/core/net_namespace.c:peernet2id_alloc
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/dev.c (ffffffff81a0c22f)
Location: include/linux/spinlock.h:396
Inline: True
Inline callers:
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:__dev_set_allmulti
  - net/core/dev.c:dev_set_promiscuity
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:__dev_open
```
```
In net/core/dev_addr_lists.c (ffffffff81a102a4)
Location: include/linux/spinlock.h:396
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:dev_mc_flush
  - net/core/dev_addr_lists.c:dev_mc_del_global
  - net/core/dev_addr_lists.c:dev_mc_del
  - net/core/dev_addr_lists.c:dev_mc_add_global
  - net/core/dev_addr_lists.c:dev_mc_add
  - net/core/dev_addr_lists.c:dev_mc_add_excl
  - net/core/dev_addr_lists.c:dev_uc_flush
  - net/core/dev_addr_lists.c:dev_uc_del
  - net/core/dev_addr_lists.c:dev_uc_add
  - net/core/dev_addr_lists.c:dev_uc_add_excl
```
```
In net/core/neighbour.c (ffffffff81a16c3e)
Location: include/linux/spinlock.h:396
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/core/rtnetlink.c (ffffffff81a1e6b3)
Location: include/linux/spinlock.h:396
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_fdb_dump
```
```
In net/core/sock_reuseport.c (ffffffff81a34e52)
Location: include/linux/spinlock.h:396
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_attach_prog
  - net/core/sock_reuseport.c:reuseport_detach_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_alloc
```
```
In net/core/page_pool.c (ffffffff81a3a9ca)
Location: include/linux/spinlock.h:396
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_empty_ring
  - net/core/page_pool.c:page_pool_put_page
```
```
In net/core/net-procfs.c (ffffffff81a3b802)
Location: include/linux/spinlock.h:396
Inline: True
```
```
In net/core/skmsg.c (ffffffff81a3d51f)
Location: include/linux/spinlock.h:396
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_link_pop
```
```
In net/core/sock_map.c (ffffffff81a4f839)
Location: include/linux/spinlock.h:396
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_del_link
```
```
In net/core/devlink.c (ffffffff81a5ad5f)
Location: include/linux/spinlock.h:396
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_port_type_set
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
```
```
In net/sched/sch_generic.c (ffffffff81a66676)
Location: include/linux/spinlock.h:396
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_reset_queue
  - net/sched/sch_generic.c:dev_reset_queue
  - net/sched/sch_generic.c:dev_graft_qdisc
```
```
In net/sched/sch_mq.c (ffffffff81a6726c)
Location: include/linux/spinlock.h:396
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump
```
```
In net/sched/sch_api.c (ffffffff81a6871b)
Location: include/linux/spinlock.h:396
Inline: True
Inline callers:
  - net/sched/sch_api.c:tcf_node_bind
  - net/sched/sch_api.c:qdisc_class_hash_grow
```
```
In net/sched/cls_api.c (ffffffff81a71a96)
Location: include/linux/spinlock.h:396
Inline: True
```
```
In net/ipv4/route.c (ffffffff81a956d5)
Location: include/linux/spinlock.h:396
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:rt_flush_dev
  - net/ipv4/route.c:ipv4_dst_destroy
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/inetpeer.c (ffffffff81a976bb)
Location: include/linux/spinlock.h:396
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/inet_hashtables.c (ffffffff81aa46ef)
Location: include/linux/spinlock.h:396
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_unhash
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81aa643b)
Location: include/linux/spinlock.h:396
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_find_open_port
```
```
In net/ipv4/tcp.c (ffffffff81aa8d7a)
Location: include/linux/spinlock.h:396
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_ioctl
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac6e3e)
Location: include/linux/spinlock.h:396
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_seq_stop
  - net/ipv4/tcp_ipv4.c:established_get_next
  - net/ipv4/tcp_ipv4.c:established_get_first
```
```
In net/ipv4/tcp_metrics.c (ffffffff81acb9f5)
Location: include/linux/spinlock.h:396
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_flush_all
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
  - net/ipv4/tcp_metrics.c:tcpm_new
```
```
In net/ipv4/raw.c (ffffffff81ad024b)
Location: include/linux/spinlock.h:396
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81ad26f3)
Location: include/linux/spinlock.h:396
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_seq_stop
  - net/ipv4/udp.c:udp_get_next
  - net/ipv4/udp.c:udp_get_first
  - net/ipv4/udp.c:udp_destroy_sock
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:skb_consume_udp
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/af_inet.c (ffffffff81ae1c96)
Location: include/linux/spinlock.h:396
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_register_protosw
```
```
In net/ipv4/igmp.c (ffffffff81ae49c7)
Location: include/linux/spinlock.h:396
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_mcf_seq_stop
  - net/ipv4/igmp.c:igmp_mcf_seq_next
  - net/ipv4/igmp.c:igmp_mcf_seq_start
  - net/ipv4/igmp.c:ip_mc_clear_src
  - net/ipv4/igmp.c:ip_mc_add_src
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:igmpv3_clear_delrec
  - net/ipv4/igmp.c:igmpv3_clear_delrec
  - net/ipv4/igmp.c:igmpv3_del_delrec
  - net/ipv4/igmp.c:igmpv3_del_delrec
  - net/ipv4/igmp.c:igmpv3_add_delrec
  - net/ipv4/igmp.c:igmpv3_add_delrec
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmpv3_send_cr
  - net/ipv4/igmp.c:igmpv3_send_cr
```
```
In net/ipv4/fib_semantics.c (ffffffff81aef726)
Location: include/linux/spinlock.h:396
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_info_hash_move
  - net/ipv4/fib_semantics.c:fib_release_info
```
```
In net/ipv4/inet_fragment.c (ffffffff81af51e9)
Location: include/linux/spinlock.h:396
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frags_free_cb
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81afe2ae)
Location: include/linux/spinlock.h:396
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
```
In net/ipv4/ipmr.c (ffffffff81b04070)
Location: include/linux/spinlock.h:396
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:mr_mfc_seq_stop
```
```
In net/ipv4/ipmr_base.c (ffffffff81b06a21)
Location: include/linux/spinlock.h:396
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_table_dump
  - net/ipv4/ipmr_base.c:mr_table_dump
  - net/ipv4/ipmr_base.c:mr_mfc_seq_next
```
```
In net/ipv4/tcp_bpf.c (ffffffff81b09c2a)
Location: include/linux/spinlock.h:396
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_get_proto
```
```
In net/ipv4/udp_bpf.c (ffffffff81b09d39)
Location: include/linux/spinlock.h:396
Inline: True
Inline callers:
  - net/ipv4/udp_bpf.c:udp_bpf_get_proto
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81b0ae02)
Location: include/linux/spinlock.h:396
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_check
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_check
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_invalidate
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b14010)
Location: include/linux/spinlock.h:396
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:clone_policy
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_walk
  - net/xfrm/xfrm_policy.c:xfrm_policy_flush
  - net/xfrm/xfrm_policy.c:xfrm_policy_flush
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_bydst_resize
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
```
```
In net/xfrm/xfrm_state.c (ffffffff81b1852f)
Location: include/linux/spinlock.h:396
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel
  - net/xfrm/xfrm_state.c:xfrm_state_unregister_afinfo
  - net/xfrm/xfrm_state.c:xfrm_state_register_afinfo
  - net/xfrm/xfrm_state.c:xfrm_unregister_km
  - net/xfrm/xfrm_state.c:xfrm_register_km
  - net/xfrm/xfrm_state.c:xfrm_state_walk
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_find_acq_byseq
  - net/xfrm/xfrm_state.c:xfrm_find_acq
  - net/xfrm/xfrm_state.c:xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_state_lookup_byspi
  - net/xfrm/xfrm_state.c:xfrm_state_lookup_byspi
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_sad_getinfo
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_gc_task
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_input.c (ffffffff81b1d55e)
Location: include/linux/spinlock.h:396
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo
  - net/xfrm/xfrm_input.c:xfrm_input_register_afinfo
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1fe67)
Location: include/linux/spinlock.h:396
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/af_inet6.c (ffffffff81b2a22b)
Location: include/linux/spinlock.h:396
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_register_protosw
```
```
In net/ipv6/addrconf.c (ffffffff81b3ea5b)
Location: include/linux/spinlock.h:396
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:ipv6_generate_stable_address
  - net/ipv6/addrconf.c:addrconf_add_linklocal
  - net/ipv6/addrconf.c:add_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/route.c (ffffffff81b4ab84)
Location: include/linux/spinlock.h:396
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/route.c:fib6_remove_prefsrc
  - net/ipv6/route.c:__ip6_del_rt_siblings
  - net/ipv6/route.c:ip6_del_rt
  - net/ipv6/route.c:ip6_route_add
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:fib6_table_lookup
  - net/ipv6/route.c:fib6_nh_remove_exception
  - net/ipv6/route.c:fib6_nh_flush_exceptions
  - net/ipv6/route.c:ip6_ins_rt
```
```
In net/ipv6/ip6_fib.c (ffffffff81b4ca3d)
Location: include/linux/spinlock.h:396
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:__fib6_clean_all
  - net/ipv6/ip6_fib.c:fib6_update_sernum_stub
  - net/ipv6/ip6_fib.c:fib6_tables_dump
```
```
In net/ipv6/raw.c (ffffffff81b5bbeb)
Location: include/linux/spinlock.h:396
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff81b5fe57)
Location: include/linux/spinlock.h:396
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mcf_seq_stop
  - net/ipv6/mcast.c:igmp6_mcf_seq_next
  - net/ipv6/mcast.c:igmp6_mcf_seq_start
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:mld_send_cr
  - net/ipv6/mcast.c:mld_send_report
  - net/ipv6/mcast.c:mld_send_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:mld_del_delrec
  - net/ipv6/mcast.c:mld_del_delrec
  - net/ipv6/mcast.c:mld_add_delrec
  - net/ipv6/mcast.c:mld_add_delrec
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/mcast.c:igmp6_group_added
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81b707fb)
Location: include/linux/spinlock.h:396
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:fl6_renew
  - net/ipv6/ip6_flowlabel.c:fl6_free_socklist
  - net/ipv6/ip6_flowlabel.c:fl6_free_socklist
  - net/ipv6/ip6_flowlabel.c:fl_release
```
```
In net/ipv6/ip6mr.c (ffffffff81b75760)
Location: include/linux/spinlock.h:396
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:mr_mfc_seq_stop
```
```
In net/ipv6/calipso.c (ffffffff81b7c651)
Location: include/linux/spinlock.h:396
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_cache_check
  - net/ipv6/calipso.c:calipso_cache_check
  - net/ipv6/calipso.c:calipso_cache_invalidate
```
```
In net/packet/af_packet.c (ffffffff81b89c3d)
Location: include/linux/spinlock.h:396
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_ioctl
  - net/packet/af_packet.c:packet_getsockopt
```
```
In net/dcb/dcbnl.c (ffffffff81b98e2b)
Location: include/linux/spinlock.h:396
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_ieee_getapp_default_prio_mask
  - net/dcb/dcbnl.c:dcb_ieee_getapp_dscp_prio_mask_map
  - net/dcb/dcbnl.c:dcb_ieee_getapp_prio_dscp_mask_map
  - net/dcb/dcbnl.c:dcb_ieee_delapp
  - net/dcb/dcbnl.c:dcb_ieee_setapp
  - net/dcb/dcbnl.c:dcb_ieee_getapp_mask
  - net/dcb/dcbnl.c:dcb_setapp
  - net/dcb/dcbnl.c:dcb_getapp
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
```
```
In net/switchdev/switchdev.c (ffffffff81b9d6e8)
Location: include/linux/spinlock.h:396
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_deferred_process
```
```
In net/xdp/xsk.c (ffffffff81ba6d5d)
Location: include/linux/spinlock.h:396
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_delete_from_maps
  - net/xdp/xsk.c:xsk_generic_rcv
```
```
In net/xdp/xskmap.c (ffffffff81ba940c)
Location: include/linux/spinlock.h:396
Inline: True
Inline callers:
  - net/xdp/xskmap.c:xsk_map_try_sock_delete
  - net/xdp/xskmap.c:xsk_map_delete_elem
  - net/xdp/xskmap.c:xsk_map_update_elem
  - net/xdp/xskmap.c:xsk_map_update_elem
  - net/xdp/xskmap.c:xsk_map_update_elem
  - net/xdp/xskmap.c:xsk_map_sock_delete
```
```
In net/mptcp/protocol.c (ffffffff81bacb2e)
Location: include/linux/spinlock.h:396
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_shutdown
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_finish_join
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:move_skbs_to_msk
```
```
In net/mptcp/subflow.c (ffffffff81bafef3)
Location: include/linux/spinlock.h:396
Inline: True
Inline callers:
  - net/mptcp/subflow.c:__mptcp_subflow_connect
```
```
In net/mptcp/token.c (ffffffff81bb1d66)
Location: include/linux/spinlock.h:396
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_destroy
  - net/mptcp/token.c:mptcp_token_destroy_request
  - net/mptcp/token.c:mptcp_token_get_sock
  - net/mptcp/token.c:mptcp_token_new_accept
  - net/mptcp/token.c:mptcp_token_new_connect
  - net/mptcp/token.c:mptcp_token_new_connect
  - net/mptcp/token.c:mptcp_token_new_request
  - net/mptcp/token.c:mptcp_token_new_request
```
```
In net/mptcp/pm.c (ffffffff81bb2377)
Location: include/linux/spinlock.h:396
Inline: True
Inline callers:
  - net/mptcp/pm.c:pm_worker
  - net/mptcp/pm.c:mptcp_pm_addr_signal
  - net/mptcp/pm.c:mptcp_pm_add_addr_received
  - net/mptcp/pm.c:mptcp_pm_subflow_established
  - net/mptcp/pm.c:mptcp_pm_fully_established
  - net/mptcp/pm.c:mptcp_pm_allow_new_subflow
```
```
In net/mptcp/pm_netlink.c (ffffffff81bb381b)
Location: include/linux/spinlock.h:396
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_limits
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_dump_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_addr
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_addr
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_flush_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_append_new_local_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
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
In kernel/cgroup/cgroup.c (ffffffff8116ce8d)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_create
  - kernel/cgroup/cgroup.c:css_create
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
```
```
In kernel/bpf/core.c (ffffffff811f9146)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_ksym_del
  - kernel/bpf/core.c:bpf_ksym_add
```
```
In kernel/bpf/syscall.c (ffffffff812010e9)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_map_get_fd_by_id
  - kernel/bpf/syscall.c:bpf_prog_get_curr_or_next
  - kernel/bpf/syscall.c:bpf_map_get_curr_or_next
  - kernel/bpf/syscall.c:bpf_obj_get_next_id
  - kernel/bpf/syscall.c:bpf_raw_tracepoint_open
  - kernel/bpf/syscall.c:bpf_raw_tracepoint_open
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/syscall.c:bpf_link_prime
  - kernel/bpf/syscall.c:bpf_link_prime
  - kernel/bpf/syscall.c:bpf_link_free
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_map_inc_not_zero
  - kernel/bpf/syscall.c:map_create
```
```
In kernel/bpf/local_storage.c (ffffffff812206a5)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_link
  - kernel/bpf/local_storage.c:cgroup_storage_map_free
  - kernel/bpf/local_storage.c:cgroup_storage_get_next_key
  - kernel/bpf/local_storage.c:cgroup_storage_get_next_key
  - kernel/bpf/local_storage.c:cgroup_storage_lookup
  - kernel/bpf/local_storage.c:cgroup_storage_lookup
```
```
In kernel/bpf/btf.c (ffffffff812233bf)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_alloc_id
```
```
In kernel/bpf/reuseport_array.c (ffffffff8123788a)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem
  - kernel/bpf/reuseport_array.c:reuseport_array_delete_elem
```
```
In kernel/padata.c (ffffffff81254a80)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - kernel/padata.c:padata_reorder
```
```
In kernel/watch_queue.c (ffffffff81257863)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_clear
  - kernel/watch_queue.c:watch_queue_clear
  - kernel/watch_queue.c:remove_watch_from_object
  - kernel/watch_queue.c:add_watch_to_object
```
```
In mm/page-writeback.c (ffffffff81262c11)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - mm/page-writeback.c:bdi_set_max_ratio
  - mm/page-writeback.c:bdi_set_min_ratio
```
```
In mm/backing-dev.c (ffffffff81281f4d)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:bdi_get_by_id
  - mm/backing-dev.c:wb_shutdown
  - mm/backing-dev.c:wb_shutdown
  - mm/backing-dev.c:wb_wakeup_delayed
```
```
In fs/fs-writeback.c (ffffffff81356083)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - fs/fs-writeback.c:wakeup_dirtytime_writeback
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:wakeup_flusher_threads_bdi
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_do_writeback
  - fs/fs-writeback.c:wb_start_background_writeback
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:wb_queue_work
```
```
In fs/io_uring.c (ffffffff8138f068)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - fs/io_uring.c:__io_sqe_files_update
  - fs/io_uring.c:io_sqe_files_register
  - fs/io_uring.c:io_file_data_ref_zero
  - fs/io_uring.c:io_sqe_files_unregister
  - fs/io_uring.c:io_sqe_files_unregister
```
```
In security/selinux/netif.c (ffffffff814db4f4)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_netdev_notifier_handler
  - security/selinux/netif.c:sel_netif_flush
  - security/selinux/netif.c:sel_netif_sid_slow
```
```
In security/selinux/netnode.c (ffffffff814dbb83)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_flush
  - security/selinux/netnode.c:sel_netnode_sid
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (ffffffff814dbe63)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_flush
  - security/selinux/netport.c:sel_netport_sid_slow
  - security/selinux/netport.c:sel_netport_sid_slow
```
```
In block/blk-cgroup.c (ffffffff81586bf5)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - block/blk-cgroup.c:__blkcg_punt_bio_submit
  - block/blk-cgroup.c:blkg_async_bio_workfn
```
```
In lib/xarray.c (ffffffff8162040a)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - lib/xarray.c:__xas_nomem
```
```
In drivers/connector/cn_queue.c (ffffffff817c18bf)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_free_dev
  - drivers/connector/cn_queue.c:cn_queue_del_callback
  - drivers/connector/cn_queue.c:cn_queue_add_callback
```
```
In drivers/connector/connector.c (ffffffff817c19a2)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_proc_show
  - drivers/connector/connector.c:cn_call_callback
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/scsi/sd_zbc.c (ffffffff81859088)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_zone_wp_update
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
  - drivers/scsi/sd_zbc.c:sd_zbc_update_wp_offset_workfn
  - drivers/scsi/sd_zbc.c:sd_zbc_update_wp_offset_workfn
```
```
In drivers/net/tun.c (ffffffff818994a7)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_free_netdev
  - drivers/net/tun.c:tun_free_netdev
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_flow_update
  - drivers/net/tun.c:tun_flow_flush
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff818a014b)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_disconnect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_disconnect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_connect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_connect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_connect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_connect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_connect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_connect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_ccp_closed
  - drivers/net/ppp/ppp_generic.c:ppp_ccp_closed
  - drivers/net/ppp/ppp_generic.c:ppp_set_compress
  - drivers/net/ppp/ppp_generic.c:ppp_set_compress
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_input_error
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_dev_uninit
  - drivers/net/ppp/ppp_generic.c:ppp_dev_uninit
  - drivers/net/ppp/ppp_generic.c:ppp_get_stats64
  - drivers/net/ppp/ppp_generic.c:ppp_get_stats64
  - drivers/net/ppp/ppp_generic.c:ppp_compat_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_compat_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_poll
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - drivers/net/ppp/ppp_generic.c:ppp_read
```
```
In drivers/net/xen-netfront.c (ffffffff818a847a)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:xennet_release_rx_bufs
  - drivers/net/xen-netfront.c:xennet_open
```
```
In net/core/sock.c (ffffffff819e7db7)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/core/sock.c:release_sock
  - net/core/sock.c:__sk_flush_backlog
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__lock_sock
```
```
In net/core/request_sock.c (ffffffff819e954f)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/core/datagram.c (ffffffff819f48d7)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/core/datagram.c:__sk_queue_drop_skb
```
```
In net/core/gen_stats.c (ffffffff819f71d3)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/core/gen_stats.c:gnet_stats_finish_copy
  - net/core/gen_stats.c:gnet_stats_finish_copy
  - net/core/gen_stats.c:gnet_stats_copy_app
  - net/core/gen_stats.c:gnet_stats_copy_app
  - net/core/gen_stats.c:gnet_stats_copy_queue
  - net/core/gen_stats.c:gnet_stats_copy_rate_est
  - net/core/gen_stats.c:___gnet_stats_copy_basic
  - net/core/gen_stats.c:gnet_stats_start_copy_compat
```
```
In net/core/gen_estimator.c (ffffffff819f776a)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/net_namespace.c (ffffffff819f8b29)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:unhash_nsid
  - net/core/net_namespace.c:unhash_nsid
  - net/core/net_namespace.c:peernet2id_alloc
  - net/core/net_namespace.c:peernet2id_alloc
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/dev.c (ffffffff81a0d909)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:__dev_set_allmulti
  - net/core/dev.c:dev_set_promiscuity
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:__dev_open
```
```
In net/core/dev_addr_lists.c (ffffffff81a1066f)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:dev_mc_flush
  - net/core/dev_addr_lists.c:dev_mc_del_global
  - net/core/dev_addr_lists.c:dev_mc_del
  - net/core/dev_addr_lists.c:__dev_mc_add
  - net/core/dev_addr_lists.c:dev_mc_add_excl
  - net/core/dev_addr_lists.c:dev_uc_flush
  - net/core/dev_addr_lists.c:dev_uc_del
  - net/core/dev_addr_lists.c:dev_uc_add
  - net/core/dev_addr_lists.c:dev_uc_add_excl
```
```
In net/core/neighbour.c (ffffffff81a16b50)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/core/rtnetlink.c (ffffffff81a1e9f2)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_fdb_dump
```
```
In net/core/sock_reuseport.c (ffffffff81a37192)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_attach_prog
  - net/core/sock_reuseport.c:reuseport_detach_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_alloc
```
```
In net/core/page_pool.c (ffffffff81a3ceea)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_empty_ring
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_page
```
```
In net/core/net-procfs.c (ffffffff81a3defd)
Location: include/linux/spinlock.h:397
Inline: True
```
```
In net/core/skmsg.c (ffffffff81a400ff)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_link_pop
```
```
In net/core/sock_map.c (ffffffff81a556cd)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_del_link
```
```
In net/core/devlink.c (ffffffff81a666a4)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_port_type_set
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
```
```
In net/sched/sch_generic.c (ffffffff81a6e756)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_reset_queue
  - net/sched/sch_generic.c:dev_reset_queue
  - net/sched/sch_generic.c:dev_graft_qdisc
```
```
In net/sched/sch_mq.c (ffffffff81a6f21c)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump
```
```
In net/sched/sch_api.c (ffffffff81a70e2b)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/sched/sch_api.c:tcf_node_bind
  - net/sched/sch_api.c:qdisc_class_hash_grow
```
```
In net/sched/cls_api.c (ffffffff81a7a527)
Location: include/linux/spinlock.h:397
Inline: True
```
```
In net/ipv4/route.c (ffffffff81a9f765)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:rt_flush_dev
  - net/ipv4/route.c:ipv4_dst_destroy
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/inetpeer.c (ffffffff81aa167c)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/inet_hashtables.c (ffffffff81aaed3f)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_unhash
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ab0a8b)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_find_open_port
```
```
In net/ipv4/tcp.c (ffffffff81ab322b)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_ioctl
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad310c)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_stop
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ad79b4)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_flush_all
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
  - net/ipv4/tcp_metrics.c:tcpm_new
```
```
In net/ipv4/raw.c (ffffffff81adc1bb)
Location: include/linux/spinlock.h:397
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81adf8db)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/ipv4/udp.c:bpf_iter_udp_seq_stop
  - net/ipv4/udp.c:udp_destroy_sock
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:skb_consume_udp
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/af_inet.c (ffffffff81aeeb16)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_register_protosw
```
```
In net/ipv4/igmp.c (ffffffff81af18e7)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_mcf_seq_stop
  - net/ipv4/igmp.c:igmp_mcf_seq_next
  - net/ipv4/igmp.c:igmp_mcf_seq_start
  - net/ipv4/igmp.c:ip_mc_clear_src
  - net/ipv4/igmp.c:ip_mc_add_src
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:igmpv3_clear_delrec
  - net/ipv4/igmp.c:igmpv3_clear_delrec
  - net/ipv4/igmp.c:igmpv3_del_delrec
  - net/ipv4/igmp.c:igmpv3_del_delrec
  - net/ipv4/igmp.c:igmpv3_add_delrec
  - net/ipv4/igmp.c:igmpv3_add_delrec
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmpv3_send_cr
  - net/ipv4/igmp.c:igmpv3_send_cr
```
```
In net/ipv4/fib_semantics.c (ffffffff81afc62f)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_info_hash_move
  - net/ipv4/fib_semantics.c:fib_release_info
```
```
In net/ipv4/inet_fragment.c (ffffffff81b025a9)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frags_free_cb
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81b0c31e)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
```
In net/ipv4/ipmr.c (ffffffff81b121e5)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:mr_mfc_seq_stop
```
```
In net/ipv4/ipmr_base.c (ffffffff81b14c11)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_table_dump
  - net/ipv4/ipmr_base.c:mr_table_dump
  - net/ipv4/ipmr_base.c:mr_mfc_seq_next
```
```
In net/ipv4/tcp_bpf.c (ffffffff81b18025)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_get_proto
```
```
In net/ipv4/udp_bpf.c (ffffffff81b1811e)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/ipv4/udp_bpf.c:udp_bpf_get_proto
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81b191e2)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_check
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_check
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_invalidate
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b223b0)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:clone_policy
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_walk
  - net/xfrm/xfrm_policy.c:xfrm_policy_flush
  - net/xfrm/xfrm_policy.c:xfrm_policy_flush
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_bydst_resize
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
```
```
In net/xfrm/xfrm_state.c (ffffffff81b2711f)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel
  - net/xfrm/xfrm_state.c:xfrm_state_unregister_afinfo
  - net/xfrm/xfrm_state.c:xfrm_state_register_afinfo
  - net/xfrm/xfrm_state.c:xfrm_unregister_km
  - net/xfrm/xfrm_state.c:xfrm_register_km
  - net/xfrm/xfrm_state.c:xfrm_unregister_translator
  - net/xfrm/xfrm_state.c:xfrm_register_translator
  - net/xfrm/xfrm_state.c:xfrm_state_walk
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_find_acq_byseq
  - net/xfrm/xfrm_state.c:xfrm_find_acq
  - net/xfrm/xfrm_state.c:xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_state_lookup_byspi
  - net/xfrm/xfrm_state.c:xfrm_state_lookup_byspi
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_sad_getinfo
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_gc_task
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_input.c (ffffffff81b2bd7e)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo
  - net/xfrm/xfrm_input.c:xfrm_input_register_afinfo
```
```
In net/xfrm/xfrm_output.c (ffffffff81b2e777)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/af_inet6.c (ffffffff81b38b8b)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_register_protosw
```
```
In net/ipv6/addrconf.c (ffffffff81b4d5eb)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:ipv6_generate_stable_address
  - net/ipv6/addrconf.c:addrconf_add_linklocal
  - net/ipv6/addrconf.c:add_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/route.c (ffffffff81b59814)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/route.c:fib6_remove_prefsrc
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_del_rt_siblings
  - net/ipv6/route.c:ip6_del_rt
  - net/ipv6/route.c:ip6_route_add
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:fib6_table_lookup
  - net/ipv6/route.c:fib6_nh_remove_exception
  - net/ipv6/route.c:fib6_nh_flush_exceptions
  - net/ipv6/route.c:ip6_ins_rt
```
```
In net/ipv6/ip6_fib.c (ffffffff81b5b68d)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:__fib6_clean_all
  - net/ipv6/ip6_fib.c:fib6_update_sernum_stub
  - net/ipv6/ip6_fib.c:fib6_tables_dump
```
```
In net/ipv6/raw.c (ffffffff81b6a41b)
Location: include/linux/spinlock.h:397
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff81b6e5c7)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mcf_seq_stop
  - net/ipv6/mcast.c:igmp6_mcf_seq_next
  - net/ipv6/mcast.c:igmp6_mcf_seq_start
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:mld_send_cr
  - net/ipv6/mcast.c:mld_send_report
  - net/ipv6/mcast.c:mld_send_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:mld_del_delrec
  - net/ipv6/mcast.c:mld_del_delrec
  - net/ipv6/mcast.c:mld_add_delrec
  - net/ipv6/mcast.c:mld_add_delrec
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/mcast.c:igmp6_group_added
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81b7f131)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:fl6_renew
  - net/ipv6/ip6_flowlabel.c:fl6_free_socklist
  - net/ipv6/ip6_flowlabel.c:fl6_free_socklist
  - net/ipv6/ip6_flowlabel.c:fl_release
```
```
In net/ipv6/ip6mr.c (ffffffff81b844d5)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:mr_mfc_seq_stop
```
```
In net/ipv6/calipso.c (ffffffff81b8b691)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_cache_check
  - net/ipv6/calipso.c:calipso_cache_check
  - net/ipv6/calipso.c:calipso_cache_invalidate
```
```
In net/packet/af_packet.c (ffffffff81b99758)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_ioctl
  - net/packet/af_packet.c:packet_getsockopt
```
```
In net/dcb/dcbnl.c (ffffffff81ba8afb)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_ieee_getapp_default_prio_mask
  - net/dcb/dcbnl.c:dcb_ieee_getapp_dscp_prio_mask_map
  - net/dcb/dcbnl.c:dcb_ieee_getapp_prio_dscp_mask_map
  - net/dcb/dcbnl.c:dcb_ieee_delapp
  - net/dcb/dcbnl.c:dcb_ieee_setapp
  - net/dcb/dcbnl.c:dcb_ieee_getapp_mask
  - net/dcb/dcbnl.c:dcb_setapp
  - net/dcb/dcbnl.c:dcb_getapp
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
```
```
In net/switchdev/switchdev.c (ffffffff81bacff8)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_deferred_process
```
```
In net/xdp/xsk.c (ffffffff81bb6520)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xsk.c:xsk_generic_rcv
```
```
In net/xdp/xskmap.c (ffffffff81bb8bdc)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/xdp/xskmap.c:xsk_map_try_sock_delete
  - net/xdp/xskmap.c:xsk_map_delete_elem
  - net/xdp/xskmap.c:xsk_map_update_elem
  - net/xdp/xskmap.c:xsk_map_update_elem
  - net/xdp/xskmap.c:xsk_map_update_elem
  - net/xdp/xskmap.c:xsk_map_sock_delete
```
```
In net/mptcp/protocol.c (ffffffff81bbe66c)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_finish_join
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:mptcp_disconnect
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:__mptcp_destroy_sock
  - net/mptcp/protocol.c:__mptcp_check_send_data_fin
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:pm_work
  - net/mptcp/protocol.c:__mptcp_move_skbs
  - net/mptcp/protocol.c:__mptcp_move_skbs
  - net/mptcp/protocol.c:__mptcp_move_skbs
  - net/mptcp/protocol.c:__mptcp_move_skbs
  - net/mptcp/protocol.c:mptcp_rcv_space_adjust
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:__mptcp_push_pending
  - net/mptcp/protocol.c:mptcp_alloc_tx_skb
  - net/mptcp/protocol.c:mptcp_data_ready
```
```
In net/mptcp/subflow.c (ffffffff81bc3a90)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/mptcp/subflow.c:__mptcp_subflow_connect
  - net/mptcp/subflow.c:__mptcp_subflow_connect
  - net/mptcp/subflow.c:subflow_error_report
```
```
In net/mptcp/options.c (ffffffff81bc5291)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_incoming_options
  - net/mptcp/options.c:ack_update_msk
```
```
In net/mptcp/token.c (ffffffff81bc6151)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_destroy
  - net/mptcp/token.c:mptcp_token_destroy_request
  - net/mptcp/token.c:mptcp_token_accept
  - net/mptcp/token.c:mptcp_token_new_connect
  - net/mptcp/token.c:mptcp_token_new_connect
  - net/mptcp/token.c:mptcp_token_new_request
  - net/mptcp/token.c:mptcp_token_new_request
```
```
In net/mptcp/pm.c (ffffffff81bc6d85)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/mptcp/pm.c:mptcp_pm_rm_addr_signal
  - net/mptcp/pm.c:mptcp_pm_add_addr_signal
  - net/mptcp/pm.c:mptcp_pm_rm_addr_received
  - net/mptcp/pm.c:mptcp_pm_add_addr_received
  - net/mptcp/pm.c:mptcp_pm_subflow_established
  - net/mptcp/pm.c:mptcp_pm_fully_established
  - net/mptcp/pm.c:mptcp_pm_allow_new_subflow
  - net/mptcp/pm.c:mptcp_pm_remove_subflow
```
```
In net/mptcp/pm_netlink.c (ffffffff81bc7c70)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_limits
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_dump_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_addr
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_addr
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_flush_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_append_new_local_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_rm_subflow_received
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_rm_addr_received
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_free_anno_list
  - net/mptcp/pm_netlink.c:mptcp_pm_del_add_timer
  - net/mptcp/pm_netlink.c:mptcp_pm_add_timer
```
```
In net/mptcp/syncookies.c (ffffffff81bc9565)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/mptcp/syncookies.c:mptcp_token_join_cookie_init_state
  - net/mptcp/syncookies.c:mptcp_token_join_cookie_init_state
  - net/mptcp/syncookies.c:mptcp_token_join_cookie_init_state
  - net/mptcp/syncookies.c:subflow_init_req_cookie_join_save
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
In kernel/cgroup/cgroup.c (ffffffff8116daed)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_create
  - kernel/cgroup/cgroup.c:css_create
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
```
```
In kernel/bpf/core.c (ffffffff811f9f26)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_ksym_del
  - kernel/bpf/core.c:bpf_ksym_add
```
```
In kernel/bpf/syscall.c (ffffffff81201a0a)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_prog_get_curr_or_next
  - kernel/bpf/syscall.c:bpf_map_get_curr_or_next
  - kernel/bpf/syscall.c:bpf_obj_get_next_id
  - kernel/bpf/syscall.c:bpf_raw_tracepoint_open
  - kernel/bpf/syscall.c:bpf_raw_tracepoint_open
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/syscall.c:bpf_link_prime
  - kernel/bpf/syscall.c:bpf_link_prime
  - kernel/bpf/syscall.c:bpf_link_free
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_map_inc_not_zero
  - kernel/bpf/syscall.c:map_create
```
```
In kernel/bpf/local_storage.c (ffffffff81224135)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_link
  - kernel/bpf/local_storage.c:cgroup_storage_map_free
  - kernel/bpf/local_storage.c:cgroup_storage_get_next_key
  - kernel/bpf/local_storage.c:cgroup_storage_get_next_key
  - kernel/bpf/local_storage.c:cgroup_storage_lookup
  - kernel/bpf/local_storage.c:cgroup_storage_lookup
```
```
In kernel/bpf/btf.c (ffffffff81227e6f)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_alloc_id
```
```
In kernel/bpf/reuseport_array.c (ffffffff8123c0ab)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem
  - kernel/bpf/reuseport_array.c:reuseport_array_delete_elem
```
```
In kernel/padata.c (ffffffff8125902c)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - kernel/padata.c:padata_reorder
```
```
In kernel/watch_queue.c (ffffffff8125bcc3)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_clear
  - kernel/watch_queue.c:watch_queue_clear
  - kernel/watch_queue.c:remove_watch_from_object
  - kernel/watch_queue.c:add_watch_to_object
```
```
In mm/page-writeback.c (ffffffff81267631)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - mm/page-writeback.c:bdi_set_max_ratio
  - mm/page-writeback.c:bdi_set_min_ratio
```
```
In mm/backing-dev.c (ffffffff81286f2a)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:bdi_get_by_id
  - mm/backing-dev.c:wb_shutdown
  - mm/backing-dev.c:wb_shutdown
  - mm/backing-dev.c:wb_wakeup_delayed
```
```
In fs/fs-writeback.c (ffffffff8135cc73)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - fs/fs-writeback.c:wakeup_dirtytime_writeback
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:wakeup_flusher_threads_bdi
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_do_writeback
  - fs/fs-writeback.c:wb_start_background_writeback
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:wb_queue_work
```
```
In security/selinux/netif.c (ffffffff814e1e74)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_netdev_notifier_handler
  - security/selinux/netif.c:sel_netif_flush
  - security/selinux/netif.c:sel_netif_sid_slow
```
```
In security/selinux/netnode.c (ffffffff814e2523)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_flush
  - security/selinux/netnode.c:sel_netnode_sid_slow
  - security/selinux/netnode.c:sel_netnode_sid_slow
```
```
In security/selinux/netport.c (ffffffff814e27c3)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_flush
  - security/selinux/netport.c:sel_netport_sid
  - security/selinux/netport.c:sel_netport_sid
```
```
In block/blk-cgroup.c (ffffffff8158d905)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - block/blk-cgroup.c:__blkcg_punt_bio_submit
  - block/blk-cgroup.c:blkg_async_bio_workfn
```
```
In lib/xarray.c (ffffffff8160461c)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - lib/xarray.c:__xas_nomem
```
```
In drivers/connector/cn_queue.c (ffffffff817a4ddf)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_free_dev
  - drivers/connector/cn_queue.c:cn_queue_del_callback
  - drivers/connector/cn_queue.c:cn_queue_add_callback
```
```
In drivers/connector/connector.c (ffffffff817a4ec2)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_proc_show
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/net/tun.c (ffffffff8187b887)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_free_netdev
  - drivers/net/tun.c:tun_free_netdev
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_flow_update
  - drivers/net/tun.c:tun_flow_flush
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81882c5b)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_disconnect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_disconnect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_ccp_closed
  - drivers/net/ppp/ppp_generic.c:ppp_ccp_closed
  - drivers/net/ppp/ppp_generic.c:ppp_set_compress
  - drivers/net/ppp/ppp_generic.c:ppp_set_compress
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_input_error
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_dev_uninit
  - drivers/net/ppp/ppp_generic.c:ppp_dev_uninit
  - drivers/net/ppp/ppp_generic.c:ppp_get_stats64
  - drivers/net/ppp/ppp_generic.c:ppp_get_stats64
  - drivers/net/ppp/ppp_generic.c:ppp_compat_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_compat_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_poll
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - drivers/net/ppp/ppp_generic.c:ppp_read
```
```
In drivers/net/xen-netfront.c (ffffffff8188b934)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:xennet_open
```
```
In net/core/sock.c (ffffffff819cdd87)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/core/sock.c:release_sock
  - net/core/sock.c:__sk_flush_backlog
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__lock_sock
```
```
In net/core/request_sock.c (ffffffff819cf66f)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/core/datagram.c (ffffffff819da9a7)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/core/datagram.c:__sk_queue_drop_skb
```
```
In net/core/gen_stats.c (ffffffff819dd363)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/core/gen_stats.c:gnet_stats_finish_copy
  - net/core/gen_stats.c:gnet_stats_finish_copy
  - net/core/gen_stats.c:gnet_stats_copy_app
  - net/core/gen_stats.c:gnet_stats_copy_app
  - net/core/gen_stats.c:gnet_stats_copy_queue
  - net/core/gen_stats.c:gnet_stats_copy_rate_est
  - net/core/gen_stats.c:___gnet_stats_copy_basic
  - net/core/gen_stats.c:gnet_stats_start_copy_compat
```
```
In net/core/gen_estimator.c (ffffffff819dd8ea)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/net_namespace.c (ffffffff819df359)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:peernet2id_alloc
  - net/core/net_namespace.c:peernet2id_alloc
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/dev.c (ffffffff819f45a6)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:__dev_set_allmulti
  - net/core/dev.c:dev_set_promiscuity
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:__dev_open
```
```
In net/core/dev_addr_lists.c (ffffffff819f74df)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:dev_mc_flush
  - net/core/dev_addr_lists.c:dev_mc_del_global
  - net/core/dev_addr_lists.c:dev_mc_del
  - net/core/dev_addr_lists.c:__dev_mc_add
  - net/core/dev_addr_lists.c:dev_mc_add_excl
  - net/core/dev_addr_lists.c:dev_uc_flush
  - net/core/dev_addr_lists.c:dev_uc_del
  - net/core/dev_addr_lists.c:dev_uc_add
  - net/core/dev_addr_lists.c:dev_uc_add_excl
```
```
In net/core/neighbour.c (ffffffff819fd7cb)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/core/rtnetlink.c (ffffffff81a057f2)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_fdb_dump
```
```
In net/core/sock_reuseport.c (ffffffff81a1e2f2)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_attach_prog
  - net/core/sock_reuseport.c:reuseport_detach_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_alloc
```
```
In net/core/page_pool.c (ffffffff81a23d38)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_page
```
```
In net/core/net-procfs.c (ffffffff81a24fcd)
Location: include/linux/spinlock.h:397
Inline: True
```
```
In net/core/devlink.c (ffffffff81a46bf4)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_port_type_set
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
```
```
In net/core/skmsg.c (ffffffff81a4e3c4)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_verdict_apply
  - net/core/skmsg.c:sk_psock_skb_redirect
  - net/core/skmsg.c:sk_psock_skb_redirect
  - net/core/skmsg.c:sk_psock_stop
  - net/core/skmsg.c:sk_psock_link_pop
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_psock_skb_ingress_enqueue
  - net/core/skmsg.c:sk_msg_recvmsg
  - net/core/skmsg.c:sk_msg_recvmsg
  - net/core/skmsg.c:sk_msg_recvmsg
  - net/core/skmsg.c:sk_msg_recvmsg
```
```
In net/core/sock_map.c (ffffffff81a50ec3)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_unref
```
```
In net/sched/sch_generic.c (ffffffff81a56fe6)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_reset_queue
  - net/sched/sch_generic.c:dev_reset_queue
  - net/sched/sch_generic.c:dev_graft_qdisc
```
```
In net/sched/sch_mq.c (ffffffff81a57adc)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump
```
```
In net/sched/sch_api.c (ffffffff81a59778)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/sched/sch_api.c:tcf_node_bind
  - net/sched/sch_api.c:tcf_node_bind
  - net/sched/sch_api.c:qdisc_class_hash_grow
```
```
In net/sched/cls_api.c (ffffffff81a602b7)
Location: include/linux/spinlock.h:397
Inline: True
```
```
In net/ipv4/route.c (ffffffff81a8a69b)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:rt_flush_dev
  - net/ipv4/route.c:ipv4_dst_destroy
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/inetpeer.c (ffffffff81a8c5dc)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/inet_hashtables.c (ffffffff81a99fd3)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_unhash
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81a9bb3b)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_find_open_port
```
```
In net/ipv4/tcp.c (ffffffff81a9e489)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_ioctl
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abe19c)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_stop
  - net/ipv4/tcp_ipv4.c:established_get_next
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ac2b4e)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_flush_all
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/raw.c (ffffffff81ac705b)
Location: include/linux/spinlock.h:397
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81aca7db)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/ipv4/udp.c:bpf_iter_udp_seq_stop
  - net/ipv4/udp.c:udp_get_next
  - net/ipv4/udp.c:udp_destroy_sock
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:skb_consume_udp
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/af_inet.c (ffffffff81ada246)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_register_protosw
```
```
In net/ipv4/igmp.c (ffffffff81add0d7)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_mcf_seq_stop
  - net/ipv4/igmp.c:igmp_mcf_seq_next
  - net/ipv4/igmp.c:igmp_mcf_seq_start
  - net/ipv4/igmp.c:ip_mc_clear_src
  - net/ipv4/igmp.c:ip_mc_add_src
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:igmpv3_clear_delrec
  - net/ipv4/igmp.c:igmpv3_clear_delrec
  - net/ipv4/igmp.c:igmpv3_del_delrec
  - net/ipv4/igmp.c:igmpv3_del_delrec
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmpv3_send_cr
  - net/ipv4/igmp.c:igmpv3_send_cr
```
```
In net/ipv4/fib_semantics.c (ffffffff81ae7e2f)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_info_hash_move
  - net/ipv4/fib_semantics.c:fib_release_info
```
```
In net/ipv4/inet_fragment.c (ffffffff81aedeb9)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frags_free_cb
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81af9f7e)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
```
In net/ipv4/ipmr.c (ffffffff81aff934)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:mr_mfc_seq_stop
```
```
In net/ipv4/ipmr_base.c (ffffffff81b02a11)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_table_dump
  - net/ipv4/ipmr_base.c:mr_table_dump
  - net/ipv4/ipmr_base.c:mr_mfc_seq_next
```
```
In net/ipv4/tcp_bpf.c (ffffffff81b04a16)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_update_proto
```
```
In net/ipv4/udp_bpf.c (ffffffff81b05c2e)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/ipv4/udp_bpf.c:udp_bpf_update_proto
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81b06c5e)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_check
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_check
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_invalidate
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0ffb0)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:clone_policy
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_walk
  - net/xfrm/xfrm_policy.c:xfrm_policy_flush
  - net/xfrm/xfrm_policy.c:xfrm_policy_flush
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
```
```
In net/xfrm/xfrm_state.c (ffffffff81b14d3f)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel
  - net/xfrm/xfrm_state.c:xfrm_state_unregister_afinfo
  - net/xfrm/xfrm_state.c:xfrm_state_register_afinfo
  - net/xfrm/xfrm_state.c:xfrm_unregister_km
  - net/xfrm/xfrm_state.c:xfrm_register_km
  - net/xfrm/xfrm_state.c:xfrm_unregister_translator
  - net/xfrm/xfrm_state.c:xfrm_register_translator
  - net/xfrm/xfrm_state.c:xfrm_state_walk
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_find_acq_byseq
  - net/xfrm/xfrm_state.c:xfrm_find_acq
  - net/xfrm/xfrm_state.c:xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_state_lookup_byspi
  - net/xfrm/xfrm_state.c:xfrm_state_lookup_byspi
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_sad_getinfo
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_gc_task
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_input.c (ffffffff81b199ee)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo
  - net/xfrm/xfrm_input.c:xfrm_input_register_afinfo
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1c484)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/af_inet6.c (ffffffff81b2687b)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_register_protosw
```
```
In net/ipv6/addrconf.c (ffffffff81b3b49b)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:ipv6_generate_stable_address
  - net/ipv6/addrconf.c:addrconf_add_linklocal
  - net/ipv6/addrconf.c:add_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/route.c (ffffffff81b47968)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:fib6_remove_prefsrc
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_del_rt_siblings
  - net/ipv6/route.c:ip6_route_add
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:fib6_table_lookup
  - net/ipv6/route.c:fib6_nh_remove_exception
  - net/ipv6/route.c:fib6_nh_flush_exceptions
  - net/ipv6/route.c:rt6_insert_exception
  - net/ipv6/route.c:rt6_insert_exception
  - net/ipv6/route.c:ip6_ins_rt
```
```
In net/ipv6/ip6_fib.c (ffffffff81b49b4d)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:__fib6_clean_all
  - net/ipv6/ip6_fib.c:fib6_update_sernum_stub
  - net/ipv6/ip6_fib.c:fib6_tables_dump
```
```
In net/ipv6/raw.c (ffffffff81b5874b)
Location: include/linux/spinlock.h:397
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff81b62612)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_destroy_dev
  - net/ipv6/mcast.c:ipv6_mc_destroy_dev
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:mld_query_work
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81b6df71)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:fl6_renew
  - net/ipv6/ip6_flowlabel.c:fl6_free_socklist
  - net/ipv6/ip6_flowlabel.c:fl6_free_socklist
  - net/ipv6/ip6_flowlabel.c:fl_release
```
```
In net/ipv6/ip6mr.c (ffffffff81b73170)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:mr_mfc_seq_stop
```
```
In net/ipv6/calipso.c (ffffffff81b7a4dd)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_cache_check
  - net/ipv6/calipso.c:calipso_cache_check
  - net/ipv6/calipso.c:calipso_cache_invalidate
```
```
In net/packet/af_packet.c (ffffffff81b88b46)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_ioctl
  - net/packet/af_packet.c:packet_getsockopt
```
```
In net/dcb/dcbnl.c (ffffffff81b97c8b)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_ieee_getapp_default_prio_mask
  - net/dcb/dcbnl.c:dcb_ieee_getapp_dscp_prio_mask_map
  - net/dcb/dcbnl.c:dcb_ieee_getapp_prio_dscp_mask_map
  - net/dcb/dcbnl.c:dcb_ieee_delapp
  - net/dcb/dcbnl.c:dcb_ieee_setapp
  - net/dcb/dcbnl.c:dcb_ieee_getapp_mask
  - net/dcb/dcbnl.c:dcb_setapp
  - net/dcb/dcbnl.c:dcb_getapp
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
```
```
In net/switchdev/switchdev.c (ffffffff81b9ca2e)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_deferred_enqueue
  - net/switchdev/switchdev.c:switchdev_deferred_process
```
```
In net/xdp/xsk.c (ffffffff81ba54e0)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xsk.c:xsk_generic_rcv
```
```
In net/xdp/xskmap.c (ffffffff81ba7dfc)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/xdp/xskmap.c:xsk_map_try_sock_delete
  - net/xdp/xskmap.c:xsk_map_delete_elem
  - net/xdp/xskmap.c:xsk_map_update_elem
  - net/xdp/xskmap.c:xsk_map_update_elem
  - net/xdp/xskmap.c:xsk_map_update_elem
  - net/xdp/xskmap.c:xsk_map_sock_delete
```
```
In net/mptcp/protocol.c (ffffffff81bb0e0f)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_finish_join
  - net/mptcp/protocol.c:mptcp_subflow_process_delegated
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:__mptcp_destroy_sock
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:__mptcp_retrans
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:__mptcp_move_skbs
  - net/mptcp/protocol.c:__mptcp_move_skbs
  - net/mptcp/protocol.c:__mptcp_move_skbs
  - net/mptcp/protocol.c:mptcp_rcv_space_adjust
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:mptcp_alloc_tx_skb
  - net/mptcp/protocol.c:__mptcp_flush_join_list
  - net/mptcp/protocol.c:mptcp_data_ready
  - net/mptcp/protocol.c:mptcp_send_ack
```
```
In net/mptcp/subflow.c (ffffffff81bb40f6)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/mptcp/subflow.c:__mptcp_subflow_connect
  - net/mptcp/subflow.c:__mptcp_subflow_connect
  - net/mptcp/subflow.c:subflow_error_report
  - net/mptcp/subflow.c:mptcp_set_connected
```
```
In net/mptcp/options.c (ffffffff81bb5ab9)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_incoming_options
  - net/mptcp/options.c:mptcp_incoming_options
```
```
In net/mptcp/token.c (ffffffff81bb6cb1)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_destroy
  - net/mptcp/token.c:mptcp_token_destroy_request
  - net/mptcp/token.c:mptcp_token_accept
  - net/mptcp/token.c:mptcp_token_new_connect
  - net/mptcp/token.c:mptcp_token_new_connect
  - net/mptcp/token.c:mptcp_token_new_request
  - net/mptcp/token.c:mptcp_token_new_request
```
```
In net/mptcp/pm.c (ffffffff81bb7aab)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/mptcp/pm.c:mptcp_pm_rm_addr_signal
  - net/mptcp/pm.c:mptcp_pm_add_addr_signal
  - net/mptcp/pm.c:mptcp_pm_rm_addr_received
  - net/mptcp/pm.c:mptcp_pm_add_addr_echoed
  - net/mptcp/pm.c:mptcp_pm_add_addr_received
  - net/mptcp/pm.c:mptcp_pm_subflow_established
  - net/mptcp/pm.c:mptcp_pm_fully_established
  - net/mptcp/pm.c:mptcp_pm_allow_new_subflow
  - net/mptcp/pm.c:mptcp_pm_remove_subflow
```
```
In net/mptcp/pm_netlink.c (ffffffff81bbb05c)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_flags
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_limits
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_dump_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_addr
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_addr
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_flush_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_remove_addrs_list
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr
  - net/mptcp/pm_netlink.c:mptcp_nl_remove_id_zero_address
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_add_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_append_new_local_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_work
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_rm_addr_or_subflow
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_mp_prio_send_ack
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_mp_prio_send_ack
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_addr_send_ack
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_addr_send_ack
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_free_anno_list
  - net/mptcp/pm_netlink.c:mptcp_pm_del_add_timer
  - net/mptcp/pm_netlink.c:mptcp_pm_add_timer
  - net/mptcp/pm_netlink.c:mptcp_pm_sport_in_anno_list
```
```
In net/mptcp/sockopt.c (ffffffff81bbcc4f)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:mptcp_sockopt_sync_all
  - net/mptcp/sockopt.c:mptcp_sockopt_sync
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_linger
  - net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval
```
```
In net/mptcp/syncookies.c (ffffffff81bbce9d)
Location: include/linux/spinlock.h:397
Inline: True
Inline callers:
  - net/mptcp/syncookies.c:mptcp_token_join_cookie_init_state
  - net/mptcp/syncookies.c:mptcp_token_join_cookie_init_state
  - net/mptcp/syncookies.c:mptcp_token_join_cookie_init_state
  - net/mptcp/syncookies.c:subflow_init_req_cookie_join_save
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
In kernel/cgroup/cgroup.c (ffffffff811933ca)
Location: include/linux/spinlock.h:406
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_create
  - kernel/cgroup/cgroup.c:css_create
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
```
```
In kernel/bpf/core.c (ffffffff8122b5f6)
Location: include/linux/spinlock.h:406
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_ksym_del
  - kernel/bpf/core.c:bpf_ksym_add
```
```
In kernel/bpf/syscall.c (ffffffff812339b0)
Location: include/linux/spinlock.h:406
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:link_create
  - kernel/bpf/syscall.c:link_create
  - kernel/bpf/syscall.c:bpf_prog_get_curr_or_next
  - kernel/bpf/syscall.c:bpf_map_get_curr_or_next
  - kernel/bpf/syscall.c:bpf_obj_get_next_id
  - kernel/bpf/syscall.c:bpf_raw_tracepoint_open
  - kernel/bpf/syscall.c:bpf_raw_tracepoint_open
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/syscall.c:bpf_link_prime
  - kernel/bpf/syscall.c:bpf_link_prime
  - kernel/bpf/syscall.c:bpf_link_free
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_map_inc_not_zero
  - kernel/bpf/syscall.c:map_create
```
```
In kernel/bpf/local_storage.c (ffffffff8125c075)
Location: include/linux/spinlock.h:406
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_link
  - kernel/bpf/local_storage.c:cgroup_storage_map_free
  - kernel/bpf/local_storage.c:cgroup_storage_get_next_key
  - kernel/bpf/local_storage.c:cgroup_storage_get_next_key
  - kernel/bpf/local_storage.c:cgroup_storage_lookup
  - kernel/bpf/local_storage.c:cgroup_storage_lookup
```
```
In kernel/bpf/btf.c (ffffffff812666fc)
Location: include/linux/spinlock.h:406
Inline: True
Inline callers:
  - kernel/bpf/btf.c:bpf_btf_find_by_name_kind
  - kernel/bpf/btf.c:bpf_btf_find_by_name_kind
  - kernel/bpf/btf.c:btf_alloc_id
```
```
In kernel/bpf/reuseport_array.c (ffffffff81276a3b)
Location: include/linux/spinlock.h:406
Inline: True
Inline callers:
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem
  - kernel/bpf/reuseport_array.c:reuseport_array_delete_elem
```
```
In kernel/padata.c (ffffffff81294cdd)
Location: include/linux/spinlock.h:406
Inline: True
Inline callers:
  - kernel/padata.c:padata_reorder
```
```
In kernel/watch_queue.c (ffffffff81297b73)
Location: include/linux/spinlock.h:406
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_clear
  - kernel/watch_queue.c:watch_queue_clear
  - kernel/watch_queue.c:remove_watch_from_object
  - kernel/watch_queue.c:add_watch_to_object
```
```
In mm/page-writeback.c (ffffffff812a4071)
Location: include/linux/spinlock.h:406
Inline: True
Inline callers:
  - mm/page-writeback.c:bdi_set_max_ratio
  - mm/page-writeback.c:bdi_set_min_ratio
```
```
In mm/backing-dev.c (ffffffff812c64e6)
Location: include/linux/spinlock.h:406
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:bdi_get_by_id
  - mm/backing-dev.c:wb_shutdown
  - mm/backing-dev.c:wb_shutdown
  - mm/backing-dev.c:wb_wakeup_delayed
```
```
In fs/fs-writeback.c (ffffffff813ab053)
Location: include/linux/spinlock.h:406
Inline: True
Inline callers:
  - fs/fs-writeback.c:wakeup_dirtytime_writeback
  - fs/fs-writeback.c:wakeup_flusher_threads
  - fs/fs-writeback.c:wakeup_flusher_threads_bdi
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_do_writeback
  - fs/fs-writeback.c:wb_start_background_writeback
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:wb_queue_work
```
```
In security/selinux/netif.c (ffffffff8153ae72)
Location: include/linux/spinlock.h:406
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_netdev_notifier_handler
  - security/selinux/netif.c:sel_netif_flush
  - security/selinux/netif.c:sel_netif_sid_slow
```
```
In security/selinux/netnode.c (ffffffff8153b5bd)
Location: include/linux/spinlock.h:406
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_flush
  - security/selinux/netnode.c:sel_netnode_sid
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (ffffffff8153b90d)
Location: include/linux/spinlock.h:406
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_flush
  - security/selinux/netport.c:sel_netport_sid
  - security/selinux/netport.c:sel_netport_sid
```
```
In block/blk-cgroup.c (ffffffff815f3375)
Location: include/linux/spinlock.h:406
Inline: True
Inline callers:
  - block/blk-cgroup.c:__blkcg_punt_bio_submit
  - block/blk-cgroup.c:blkg_async_bio_workfn
```
```
In lib/xarray.c (ffffffff81672f0c)
Location: include/linux/spinlock.h:406
Inline: True
Inline callers:
  - lib/xarray.c:__xas_nomem
```
```
In drivers/connector/cn_queue.c (ffffffff8183075f)
Location: include/linux/spinlock.h:406
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_free_dev
  - drivers/connector/cn_queue.c:cn_queue_del_callback
  - drivers/connector/cn_queue.c:cn_queue_add_callback
```
```
In drivers/connector/connector.c (ffffffff81830842)
Location: include/linux/spinlock.h:406
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_proc_show
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/net/tun.c (ffffffff8190cdac)
Location: include/linux/spinlock.h:406
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_free_netdev
  - drivers/net/tun.c:tun_free_netdev
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_flow_update
  - drivers/net/tun.c:tun_flow_flush
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff819145fb)
Location: include/linux/spinlock.h:406
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_disconnect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_disconnect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_ccp_closed
  - drivers/net/ppp/ppp_generic.c:ppp_ccp_closed
  - drivers/net/ppp/ppp_generic.c:ppp_set_compress
  - drivers/net/ppp/ppp_generic.c:ppp_set_compress
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_input_error
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_dev_uninit
  - drivers/net/ppp/ppp_generic.c:ppp_dev_uninit
  - drivers/net/ppp/ppp_generic.c:ppp_get_stats64
  - drivers/net/ppp/ppp_generic.c:ppp_get_stats64
  - drivers/net/ppp/ppp_generic.c:ppp_compat_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_compat_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_poll
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - drivers/net/ppp/ppp_generic.c:ppp_read
```
```
In drivers/net/xen-netfront.c (ffffffff8191f4c3)
Location: include/linux/spinlock.h:406
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:xennet_open
```
```
In net/core/sock.c (ffffffff81a7d409)
Location: include/linux/spinlock.h:406
Inline: True
Inline callers:
  - net/core/sock.c:__lock_sock_fast
  - net/core/sock.c:release_sock
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:__sk_flush_backlog
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__lock_sock
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_set_mark
  - net/core/sock.c:sock_set_rcvbuf
  - net/core/sock.c:sock_set_keepalive
  - net/core/sock.c:sock_enable_timestamps
  - net/core/sock.c:sock_set_sndtimeo
  - net/core/sock.c:sock_set_priority
  - net/core/sock.c:sock_no_linger
  - net/core/sock.c:sock_set_reuseport
  - net/core/sock.c:sock_set_reuseaddr
```
```
In net/core/request_sock.c (ffffffff81a7f1af)
Location: include/linux/spinlock.h:406
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/core/datagram.c (ffffffff81a8b027)
Location: include/linux/spinlock.h:406
Inline: True
Inline callers:
  - net/core/datagram.c:__sk_queue_drop_skb
```
```
In net/core/gen_stats.c (ffffffff81a8d5f3)
Location: include/linux/spinlock.h:406
Inline: True
Inline callers:
  - net/core/gen_stats.c:gnet_stats_finish_copy
  - net/core/gen_stats.c:gnet_stats_finish_copy
  - net/core/gen_stats.c:gnet_stats_copy_app
  - net/core/gen_stats.c:gnet_stats_copy_app
  - net/core/gen_stats.c:gnet_stats_copy_queue
  - net/core/gen_stats.c:gnet_stats_copy_rate_est
  - net/core/gen_stats.c:___gnet_stats_copy_basic
  - net/core/gen_stats.c:gnet_stats_start_copy_compat
```
```
In net/core/gen_estimator.c (ffffffff81a8dbd4)
Location: include/linux/spinlock.h:406
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/net_namespace.c (ffffffff81a8f739)
Location: include/linux/spinlock.h:406
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:peernet2id_alloc
  - net/core/net_namespace.c:peernet2id_alloc
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/dev.c (ffffffff81aa5ec6)
Location: include/linux/spinlock.h:406
Inline: True
Inline callers:
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:__dev_set_allmulti
  - net/core/dev.c:dev_set_promiscuity
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:__dev_open
```
```
In net/core/dev_addr_lists.c (ffffffff81aa915b)
Location: include/linux/spinlock.h:406
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:dev_mc_flush
  - net/core/dev_addr_lists.c:dev_mc_del_global
  - net/core/dev_addr_lists.c:dev_mc_del
  - net/core/dev_addr_lists.c:__dev_mc_add
  - net/core/dev_addr_lists.c:dev_mc_add_excl
  - net/core/dev_addr_lists.c:dev_uc_flush
  - net/core/dev_addr_lists.c:dev_uc_del
  - net/core/dev_addr_lists.c:dev_uc_add
  - net/core/dev_addr_lists.c:dev_uc_add_excl
```
```
In net/core/neighbour.c (ffffffff81aafdf3)
Location: include/linux/spinlock.h:406
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/core/rtnetlink.c (ffffffff81ab7c32)
Location: include/linux/spinlock.h:406
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_fdb_dump
```
```
In net/core/sock_reuseport.c (ffffffff81ad186a)
Location: include/linux/spinlock.h:406
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_detach_prog
  - net/core/sock_reuseport.c:reuseport_detach_prog
  - net/core/sock_reuseport.c:reuseport_detach_prog
  - net/core/sock_reuseport.c:reuseport_attach_prog
  - net/core/sock_reuseport.c:reuseport_stop_listen_sock
  - net/core/sock_reuseport.c:reuseport_stop_listen_sock
  - net/core/sock_reuseport.c:reuseport_detach_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_alloc
```
```
In net/core/page_pool.c (ffffffff81ad83e3)
Location: include/linux/spinlock.h:406
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_page
```
```
In net/core/net-procfs.c (ffffffff81ad9b1f)
Location: include/linux/spinlock.h:406
Inline: True
```
```
In net/core/devlink.c (ffffffff81b019f5)
Location: include/linux/spinlock.h:406
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_port_type_set
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
```
```
In net/core/skmsg.c (ffffffff81b070da)
Location: include/linux/spinlock.h:406
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_verdict_apply
  - net/core/skmsg.c:sk_psock_skb_redirect
  - net/core/skmsg.c:sk_psock_skb_redirect
  - net/core/skmsg.c:sk_psock_stop
  - net/core/skmsg.c:sk_psock_link_pop
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_psock_skb_ingress_enqueue
  - net/core/skmsg.c:sk_msg_recvmsg
  - net/core/skmsg.c:sk_msg_recvmsg
  - net/core/skmsg.c:sk_msg_recvmsg
  - net/core/skmsg.c:sk_msg_recvmsg
```
```
In net/core/sock_map.c (ffffffff81b09f70)
Location: include/linux/spinlock.h:406
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_unref
```
```
In net/sched/sch_generic.c (ffffffff81b0fe1b)
Location: include/linux/spinlock.h:406
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_reset_queue
  - net/sched/sch_generic.c:dev_reset_queue
  - net/sched/sch_generic.c:dev_graft_qdisc
```
```
In net/sched/sch_mq.c (ffffffff81b10a4c)
Location: include/linux/spinlock.h:406
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump
```
```
In net/sched/sch_api.c (ffffffff81b1282c)
Location: include/linux/spinlock.h:406
Inline: True
Inline callers:
  - net/sched/sch_api.c:tcf_node_bind
  - net/sched/sch_api.c:tcf_node_bind
  - net/sched/sch_api.c:qdisc_class_hash_grow
```
```
In net/sched/cls_api.c (ffffffff81b1954f)
Location: include/linux/spinlock.h:406
Inline: True
```
```
In net/ipv4/route.c (ffffffff81b45547)
Location: include/linux/spinlock.h:406
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:rt_flush_dev
  - net/ipv4/route.c:ipv4_dst_destroy
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/inetpeer.c (ffffffff81b4771c)
Location: include/linux/spinlock.h:406
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/inet_hashtables.c (ffffffff81b55443)
Location: include/linux/spinlock.h:406
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_unhash
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81b5720b)
Location: include/linux/spinlock.h:406
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_find_open_port
```
```
In net/ipv4/tcp.c (ffffffff81b59ada)
Location: include/linux/spinlock.h:406
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_ioctl
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b7a1fc)
Location: include/linux/spinlock.h:406
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_show
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
  - net/ipv4/tcp_ipv4.c:tcp_seq_stop
  - net/ipv4/tcp_ipv4.c:established_get_next
  - net/ipv4/tcp_ipv4.c:established_get_first
```
```
In net/ipv4/tcp_metrics.c (ffffffff81b81581)
Location: include/linux/spinlock.h:406
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_flush_all
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/raw.c (ffffffff81b8587b)
Location: include/linux/spinlock.h:406
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81b890bb)
Location: include/linux/spinlock.h:406
Inline: True
Inline callers:
  - net/ipv4/udp.c:bpf_iter_udp_seq_stop
  - net/ipv4/udp.c:udp_get_next
  - net/ipv4/udp.c:udp_destroy_sock
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:skb_consume_udp
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/af_inet.c (ffffffff81b9940f)
Location: include/linux/spinlock.h:406
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_register_protosw
```
```
In net/ipv4/igmp.c (ffffffff81b9c4c7)
Location: include/linux/spinlock.h:406
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_mcf_seq_stop
  - net/ipv4/igmp.c:igmp_mcf_seq_next
  - net/ipv4/igmp.c:igmp_mcf_seq_start
  - net/ipv4/igmp.c:ip_check_mc_rcu
  - net/ipv4/igmp.c:ip_mc_clear_src
  - net/ipv4/igmp.c:ip_mc_add_src
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:igmpv3_clear_delrec
  - net/ipv4/igmp.c:igmpv3_clear_delrec
  - net/ipv4/igmp.c:igmpv3_del_delrec
  - net/ipv4/igmp.c:igmpv3_del_delrec
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmpv3_send_cr
  - net/ipv4/igmp.c:igmpv3_send_cr
```
```
In net/ipv4/fib_semantics.c (ffffffff81ba7cd4)
Location: include/linux/spinlock.h:406
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_info_hash_move
  - net/ipv4/fib_semantics.c:fib_release_info
```
```
In net/ipv4/inet_fragment.c (ffffffff81bae269)
Location: include/linux/spinlock.h:406
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frags_free_cb
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81bbad55)
Location: include/linux/spinlock.h:406
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
```
In net/ipv4/ipmr.c (ffffffff81bc170b)
Location: include/linux/spinlock.h:406
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:mr_mfc_seq_stop
```
```
In net/ipv4/ipmr_base.c (ffffffff81bc4a36)
Location: include/linux/spinlock.h:406
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_table_dump
  - net/ipv4/ipmr_base.c:mr_table_dump
  - net/ipv4/ipmr_base.c:mr_mfc_seq_next
```
```
In net/ipv4/tcp_bpf.c (ffffffff81bc6de3)
Location: include/linux/spinlock.h:406
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_update_proto
```
```
In net/ipv4/udp_bpf.c (ffffffff81bc878e)
Location: include/linux/spinlock.h:406
Inline: True
Inline callers:
  - net/ipv4/udp_bpf.c:udp_bpf_update_proto
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81bc9abe)
Location: include/linux/spinlock.h:406
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_check
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_check
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_invalidate
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bd35d9)
Location: include/linux/spinlock.h:406
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:clone_policy
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_walk
  - net/xfrm/xfrm_policy.c:xfrm_policy_flush
  - net/xfrm/xfrm_policy.c:xfrm_policy_flush
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
```
```
In net/xfrm/xfrm_state.c (ffffffff81bd8d6f)
Location: include/linux/spinlock.h:406
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel
  - net/xfrm/xfrm_state.c:xfrm_state_unregister_afinfo
  - net/xfrm/xfrm_state.c:xfrm_state_register_afinfo
  - net/xfrm/xfrm_state.c:xfrm_unregister_km
  - net/xfrm/xfrm_state.c:xfrm_register_km
  - net/xfrm/xfrm_state.c:xfrm_unregister_translator
  - net/xfrm/xfrm_state.c:xfrm_register_translator
  - net/xfrm/xfrm_state.c:xfrm_state_walk
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_find_acq_byseq
  - net/xfrm/xfrm_state.c:xfrm_find_acq
  - net/xfrm/xfrm_state.c:xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_state_lookup_byspi
  - net/xfrm/xfrm_state.c:xfrm_state_lookup_byspi
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_sad_getinfo
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_gc_task
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_input.c (ffffffff81bde244)
Location: include/linux/spinlock.h:406
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo
  - net/xfrm/xfrm_input.c:xfrm_input_register_afinfo
```
```
In net/xfrm/xfrm_output.c (ffffffff81be0d83)
Location: include/linux/spinlock.h:406
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/unix/unix_bpf.c (ffffffff81beba7f)
Location: include/linux/spinlock.h:406
Inline: True
Inline callers:
  - net/unix/unix_bpf.c:unix_stream_bpf_update_proto
  - net/unix/unix_bpf.c:unix_dgram_bpf_update_proto
```
```
In net/ipv6/af_inet6.c (ffffffff81bec2fd)
Location: include/linux/spinlock.h:406
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_register_protosw
```
```
In net/ipv6/addrconf.c (ffffffff81c01ca8)
Location: include/linux/spinlock.h:406
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:ipv6_generate_stable_address
  - net/ipv6/addrconf.c:addrconf_add_linklocal
  - net/ipv6/addrconf.c:add_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/route.c (ffffffff81c0ebeb)
Location: include/linux/spinlock.h:406
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:fib6_remove_prefsrc
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_del_rt_siblings
  - net/ipv6/route.c:ip6_route_add
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:fib6_table_lookup
  - net/ipv6/route.c:fib6_nh_remove_exception
  - net/ipv6/route.c:fib6_nh_flush_exceptions
  - net/ipv6/route.c:rt6_insert_exception
  - net/ipv6/route.c:rt6_insert_exception
  - net/ipv6/route.c:ip6_ins_rt
```
```
In net/ipv6/ip6_fib.c (ffffffff81c109ad)
Location: include/linux/spinlock.h:406
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:__fib6_clean_all
  - net/ipv6/ip6_fib.c:fib6_update_sernum_stub
  - net/ipv6/ip6_fib.c:fib6_tables_dump
```
```
In net/ipv6/raw.c (ffffffff81c1fadb)
Location: include/linux/spinlock.h:406
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff81c2a0a2)
Location: include/linux/spinlock.h:406
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_destroy_dev
  - net/ipv6/mcast.c:ipv6_mc_destroy_dev
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:mld_query_work
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81c35e76)
Location: include/linux/spinlock.h:406
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:fl6_renew
  - net/ipv6/ip6_flowlabel.c:fl6_free_socklist
  - net/ipv6/ip6_flowlabel.c:fl6_free_socklist
  - net/ipv6/ip6_flowlabel.c:fl_release
```
```
In net/ipv6/ip6mr.c (ffffffff81c3d6fe)
Location: include/linux/spinlock.h:406
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:mr_mfc_seq_stop
```
```
In net/ipv6/calipso.c (ffffffff81c4519d)
Location: include/linux/spinlock.h:406
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_cache_check
  - net/ipv6/calipso.c:calipso_cache_check
  - net/ipv6/calipso.c:calipso_cache_invalidate
```
```
In net/packet/af_packet.c (ffffffff81c54c47)
Location: include/linux/spinlock.h:406
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_ioctl
  - net/packet/af_packet.c:packet_getsockopt
```
```
In net/dcb/dcbnl.c (ffffffff81c64cea)
Location: include/linux/spinlock.h:406
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_netdevice_event
  - net/dcb/dcbnl.c:dcb_ieee_getapp_default_prio_mask
  - net/dcb/dcbnl.c:dcb_ieee_getapp_dscp_prio_mask_map
  - net/dcb/dcbnl.c:dcb_ieee_getapp_prio_dscp_mask_map
  - net/dcb/dcbnl.c:dcb_ieee_delapp
  - net/dcb/dcbnl.c:dcb_ieee_setapp
  - net/dcb/dcbnl.c:dcb_ieee_getapp_mask
  - net/dcb/dcbnl.c:dcb_setapp
  - net/dcb/dcbnl.c:dcb_getapp
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
```
```
In net/switchdev/switchdev.c (ffffffff81c69c23)
Location: include/linux/spinlock.h:406
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_deferred_enqueue
  - net/switchdev/switchdev.c:switchdev_deferred_process
```
```
In net/xdp/xsk.c (ffffffff81c73060)
Location: include/linux/spinlock.h:406
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xsk.c:xsk_generic_rcv
```
```
In net/xdp/xskmap.c (ffffffff81c75a8c)
Location: include/linux/spinlock.h:406
Inline: True
Inline callers:
  - net/xdp/xskmap.c:xsk_map_try_sock_delete
  - net/xdp/xskmap.c:xsk_map_delete_elem
  - net/xdp/xskmap.c:xsk_map_update_elem
  - net/xdp/xskmap.c:xsk_map_update_elem
  - net/xdp/xskmap.c:xsk_map_update_elem
  - net/xdp/xskmap.c:xsk_map_sock_delete
```
```
In net/mptcp/protocol.c (ffffffff81c7eef4)
Location: include/linux/spinlock.h:406
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_finish_join
  - net/mptcp/protocol.c:mptcp_subflow_process_delegated
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:__mptcp_destroy_sock
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:__mptcp_retrans
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:__mptcp_move_skbs
  - net/mptcp/protocol.c:__mptcp_move_skbs
  - net/mptcp/protocol.c:__mptcp_move_skbs
  - net/mptcp/protocol.c:mptcp_rcv_space_adjust
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:mptcp_alloc_tx_skb
  - net/mptcp/protocol.c:mptcp_data_ready
  - net/mptcp/protocol.c:mptcp_subflow_send_ack
```
```
In net/mptcp/subflow.c (ffffffff81c8285e)
Location: include/linux/spinlock.h:406
Inline: True
Inline callers:
  - net/mptcp/subflow.c:__mptcp_subflow_connect
  - net/mptcp/subflow.c:__mptcp_subflow_connect
  - net/mptcp/subflow.c:subflow_error_report
  - net/mptcp/subflow.c:mptcp_set_connected
```
```
In net/mptcp/options.c (ffffffff81c847d3)
Location: include/linux/spinlock.h:406
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_incoming_options
  - net/mptcp/options.c:mptcp_incoming_options
```
```
In net/mptcp/token.c (ffffffff81c85ce1)
Location: include/linux/spinlock.h:406
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_destroy
  - net/mptcp/token.c:mptcp_token_destroy_request
  - net/mptcp/token.c:mptcp_token_accept
  - net/mptcp/token.c:mptcp_token_new_connect
  - net/mptcp/token.c:mptcp_token_new_connect
  - net/mptcp/token.c:mptcp_token_new_request
  - net/mptcp/token.c:mptcp_token_new_request
```
```
In net/mptcp/pm.c (ffffffff81c86f84)
Location: include/linux/spinlock.h:406
Inline: True
Inline callers:
  - net/mptcp/pm.c:mptcp_pm_rm_addr_signal
  - net/mptcp/pm.c:mptcp_pm_add_addr_signal
  - net/mptcp/pm.c:mptcp_pm_rm_addr_received
  - net/mptcp/pm.c:mptcp_pm_add_addr_echoed
  - net/mptcp/pm.c:mptcp_pm_add_addr_received
  - net/mptcp/pm.c:mptcp_pm_subflow_established
  - net/mptcp/pm.c:mptcp_pm_fully_established
  - net/mptcp/pm.c:mptcp_pm_allow_new_subflow
  - net/mptcp/pm.c:mptcp_pm_remove_subflow
```
```
In net/mptcp/pm_netlink.c (ffffffff81c8aaa8)
Location: include/linux/spinlock.h:406
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_flags
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_flags
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_flags
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_limits
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_dump_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_addr
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_addr
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_flush_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_remove_addrs_list
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr
  - net/mptcp/pm_netlink.c:mptcp_nl_remove_id_zero_address
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_add_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_subflow_chk_stale
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_append_new_local_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_work
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_rm_addr_or_subflow
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_mp_prio_send_ack
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_addr_send_ack
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_free_anno_list
  - net/mptcp/pm_netlink.c:mptcp_pm_del_add_timer
  - net/mptcp/pm_netlink.c:mptcp_pm_add_timer
  - net/mptcp/pm_netlink.c:mptcp_pm_sport_in_anno_list
```
```
In net/mptcp/sockopt.c (ffffffff81c8caaf)
Location: include/linux/spinlock.h:406
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:mptcp_sockopt_sync_all
  - net/mptcp/sockopt.c:mptcp_sockopt_sync
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_int
  - net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval
```
```
In net/mptcp/syncookies.c (ffffffff81c8cdc9)
Location: include/linux/spinlock.h:406
Inline: True
Inline callers:
  - net/mptcp/syncookies.c:mptcp_token_join_cookie_init_state
  - net/mptcp/syncookies.c:mptcp_token_join_cookie_init_state
  - net/mptcp/syncookies.c:mptcp_token_join_cookie_init_state
  - net/mptcp/syncookies.c:subflow_init_req_cookie_join_save
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
In kernel/cgroup/cgroup.c (ffffffff811c4694)
Location: include/linux/spinlock.h:392
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_create
  - kernel/cgroup/cgroup.c:css_create
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
```
```
In kernel/bpf/core.c (ffffffff8126d056)
Location: include/linux/spinlock.h:392
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_ksym_del
  - kernel/bpf/core.c:bpf_ksym_add
```
```
In kernel/bpf/syscall.c (ffffffff81277581)
Location: include/linux/spinlock.h:392
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:bpf_link_get_curr_or_next
  - kernel/bpf/syscall.c:bpf_prog_get_curr_or_next
  - kernel/bpf/syscall.c:bpf_map_get_curr_or_next
  - kernel/bpf/syscall.c:bpf_obj_get_next_id
  - kernel/bpf/syscall.c:bpf_raw_tp_link_attach
  - kernel/bpf/syscall.c:bpf_raw_tp_link_attach
  - kernel/bpf/syscall.c:bpf_perf_link_attach
  - kernel/bpf/syscall.c:bpf_perf_link_attach
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/syscall.c:bpf_link_prime
  - kernel/bpf/syscall.c:bpf_link_prime
  - kernel/bpf/syscall.c:bpf_link_free
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_map_inc_not_zero
  - kernel/bpf/syscall.c:map_create
```
```
In kernel/bpf/local_storage.c (ffffffff812a5c54)
Location: include/linux/spinlock.h:392
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_link
  - kernel/bpf/local_storage.c:cgroup_storage_map_free
  - kernel/bpf/local_storage.c:cgroup_storage_get_next_key
  - kernel/bpf/local_storage.c:cgroup_storage_get_next_key
  - kernel/bpf/local_storage.c:cgroup_storage_lookup
  - kernel/bpf/local_storage.c:cgroup_storage_lookup
```
```
In kernel/bpf/btf.c (ffffffff812aaa0f)
Location: include/linux/spinlock.h:392
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_alloc_id
  - kernel/bpf/btf.c:bpf_find_btf_id
  - kernel/bpf/btf.c:bpf_find_btf_id
```
```
In kernel/bpf/reuseport_array.c (ffffffff812c6520)
Location: include/linux/spinlock.h:392
Inline: True
Inline callers:
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem
  - kernel/bpf/reuseport_array.c:reuseport_array_delete_elem
```
```
In kernel/padata.c (ffffffff812e9738)
Location: include/linux/spinlock.h:392
Inline: True
Inline callers:
  - kernel/padata.c:padata_reorder
```
```
In kernel/watch_queue.c (ffffffff812ede43)
Location: include/linux/spinlock.h:392
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_clear
  - kernel/watch_queue.c:watch_queue_clear
  - kernel/watch_queue.c:remove_watch_from_object
  - kernel/watch_queue.c:add_watch_to_object
  - kernel/watch_queue.c:add_watch_to_object
```
```
In mm/page-writeback.c (ffffffff812fc141)
Location: include/linux/spinlock.h:392
Inline: True
Inline callers:
  - mm/page-writeback.c:bdi_set_max_ratio
  - mm/page-writeback.c:bdi_set_min_ratio
```
```
In mm/backing-dev.c (ffffffff81323176)
Location: include/linux/spinlock.h:392
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:bdi_register_va
  - mm/backing-dev.c:bdi_get_by_id
```
```
In security/selinux/netif.c (ffffffff815d25d1)
Location: include/linux/spinlock.h:392
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_netdev_notifier_handler
  - security/selinux/netif.c:sel_netif_flush
  - security/selinux/netif.c:sel_netif_sid_slow
```
```
In security/selinux/netnode.c (ffffffff815d2d9d)
Location: include/linux/spinlock.h:392
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_flush
  - security/selinux/netnode.c:sel_netnode_sid
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (ffffffff815d313d)
Location: include/linux/spinlock.h:392
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_flush
  - security/selinux/netport.c:sel_netport_sid
  - security/selinux/netport.c:sel_netport_sid
```
```
In block/blk-cgroup.c (ffffffff816a4915)
Location: include/linux/spinlock.h:392
Inline: True
Inline callers:
  - block/blk-cgroup.c:__blkcg_punt_bio_submit
  - block/blk-cgroup.c:blkg_async_bio_workfn
```
```
In lib/xarray.c (ffffffff8178c39c)
Location: include/linux/spinlock.h:392
Inline: True
Inline callers:
  - lib/xarray.c:__xas_nomem
```
```
In drivers/connector/cn_queue.c (ffffffff81971a7c)
Location: include/linux/spinlock.h:392
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_free_dev
  - drivers/connector/cn_queue.c:cn_queue_del_callback
  - drivers/connector/cn_queue.c:cn_queue_add_callback
```
```
In drivers/connector/connector.c (ffffffff81971b92)
Location: include/linux/spinlock.h:392
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_proc_show
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/net/tun.c (ffffffff81a617ac)
Location: include/linux/spinlock.h:392
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_free_netdev
  - drivers/net/tun.c:tun_free_netdev
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_flow_update
  - drivers/net/tun.c:tun_flow_flush
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81a69bed)
Location: include/linux/spinlock.h:392
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_disconnect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_disconnect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_ccp_closed
  - drivers/net/ppp/ppp_generic.c:ppp_ccp_closed
  - drivers/net/ppp/ppp_generic.c:ppp_set_compress
  - drivers/net/ppp/ppp_generic.c:ppp_set_compress
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_input_error
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_dev_uninit
  - drivers/net/ppp/ppp_generic.c:ppp_dev_uninit
  - drivers/net/ppp/ppp_generic.c:ppp_get_stats64
  - drivers/net/ppp/ppp_generic.c:ppp_get_stats64
  - drivers/net/ppp/ppp_generic.c:ppp_compat_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_compat_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_poll
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - drivers/net/ppp/ppp_generic.c:ppp_read
```
```
In drivers/net/xen-netfront.c (ffffffff81a73780)
Location: include/linux/spinlock.h:392
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:xennet_open
```
```
In net/core/sock.c (ffffffff81bf0a5f)
Location: include/linux/spinlock.h:392
Inline: True
Inline callers:
  - net/core/sock.c:__lock_sock_fast
  - net/core/sock.c:release_sock
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:__sk_flush_backlog
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__lock_sock
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_set_mark
  - net/core/sock.c:sock_set_rcvbuf
  - net/core/sock.c:sock_set_keepalive
  - net/core/sock.c:sock_enable_timestamps
  - net/core/sock.c:sock_set_sndtimeo
  - net/core/sock.c:sock_set_priority
  - net/core/sock.c:sock_no_linger
  - net/core/sock.c:sock_set_reuseport
  - net/core/sock.c:sock_set_reuseaddr
```
```
In net/core/request_sock.c (ffffffff81bf345f)
Location: include/linux/spinlock.h:392
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/core/datagram.c (ffffffff81c007a7)
Location: include/linux/spinlock.h:392
Inline: True
Inline callers:
  - net/core/datagram.c:__sk_queue_drop_skb
```
```
In net/core/gen_stats.c (ffffffff81c02ff3)
Location: include/linux/spinlock.h:392
Inline: True
Inline callers:
  - net/core/gen_stats.c:gnet_stats_finish_copy
  - net/core/gen_stats.c:gnet_stats_finish_copy
  - net/core/gen_stats.c:gnet_stats_copy_app
  - net/core/gen_stats.c:gnet_stats_copy_app
  - net/core/gen_stats.c:gnet_stats_copy_queue
  - net/core/gen_stats.c:gnet_stats_copy_rate_est
  - net/core/gen_stats.c:gnet_stats_start_copy_compat
```
```
In net/core/gen_estimator.c (ffffffff81c036fc)
Location: include/linux/spinlock.h:392
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/net_namespace.c (ffffffff81c05557)
Location: include/linux/spinlock.h:392
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:peernet2id_alloc
  - net/core/net_namespace.c:peernet2id_alloc
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/dev.c (ffffffff81c1d978)
Location: include/linux/spinlock.h:392
Inline: True
Inline callers:
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:__dev_set_allmulti
  - net/core/dev.c:dev_set_promiscuity
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:__dev_open
```
```
In net/core/dev_addr_lists.c (ffffffff81c2130b)
Location: include/linux/spinlock.h:392
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:dev_mc_flush
  - net/core/dev_addr_lists.c:dev_mc_del_global
  - net/core/dev_addr_lists.c:dev_mc_del
  - net/core/dev_addr_lists.c:__dev_mc_add
  - net/core/dev_addr_lists.c:dev_mc_add_excl
  - net/core/dev_addr_lists.c:dev_uc_flush
  - net/core/dev_addr_lists.c:dev_uc_del
  - net/core/dev_addr_lists.c:dev_uc_add
  - net/core/dev_addr_lists.c:dev_uc_add_excl
```
```
In net/core/neighbour.c (ffffffff81c28d8e)
Location: include/linux/spinlock.h:392
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/core/rtnetlink.c (ffffffff81c3184c)
Location: include/linux/spinlock.h:392
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_fdb_dump
```
```
In net/core/sock_reuseport.c (ffffffff81c4f178)
Location: include/linux/spinlock.h:392
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_detach_prog
  - net/core/sock_reuseport.c:reuseport_detach_prog
  - net/core/sock_reuseport.c:reuseport_detach_prog
  - net/core/sock_reuseport.c:reuseport_attach_prog
  - net/core/sock_reuseport.c:reuseport_stop_listen_sock
  - net/core/sock_reuseport.c:reuseport_stop_listen_sock
  - net/core/sock_reuseport.c:reuseport_detach_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_alloc
```
```
In net/core/page_pool.c (ffffffff81c591ea)
Location: include/linux/spinlock.h:392
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_defragged_page
```
```
In net/core/net-procfs.c (ffffffff81c5af4f)
Location: include/linux/spinlock.h:392
Inline: True
```
```
In net/core/devlink.c (ffffffff81c81013)
Location: include/linux/spinlock.h:392
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_port_type_set
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
```
```
In net/core/skmsg.c (ffffffff81c8bcbb)
Location: include/linux/spinlock.h:392
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_verdict_apply
  - net/core/skmsg.c:sk_psock_skb_redirect
  - net/core/skmsg.c:sk_psock_skb_redirect
  - net/core/skmsg.c:sk_psock_stop
  - net/core/skmsg.c:sk_psock_link_pop
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_psock_skb_ingress_enqueue
  - net/core/skmsg.c:sk_msg_recvmsg
  - net/core/skmsg.c:sk_msg_recvmsg
  - net/core/skmsg.c:sk_msg_recvmsg
  - net/core/skmsg.c:sk_msg_recvmsg
```
```
In net/core/sock_map.c (ffffffff81c901c4)
Location: include/linux/spinlock.h:392
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_unref
```
```
In net/sched/sch_generic.c (ffffffff81c96fa3)
Location: include/linux/spinlock.h:392
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_reset_queue
  - net/sched/sch_generic.c:dev_reset_queue
  - net/sched/sch_generic.c:dev_graft_qdisc
```
```
In net/sched/sch_mq.c (ffffffff81c9764c)
Location: include/linux/spinlock.h:392
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump
```
```
In net/sched/sch_api.c (ffffffff81c9ab6c)
Location: include/linux/spinlock.h:392
Inline: True
Inline callers:
  - net/sched/sch_api.c:tcf_node_bind
  - net/sched/sch_api.c:tcf_node_bind
  - net/sched/sch_api.c:qdisc_class_hash_grow
```
```
In net/sched/cls_api.c (ffffffff81ca4120)
Location: include/linux/spinlock.h:392
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_setup_action
  - net/sched/cls_api.c:tc_setup_action
```
```
In net/sched/act_api.c (ffffffff81ca5542)
Location: include/linux/spinlock.h:392
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_offload_del_ex
  - net/sched/act_api.c:tcf_action_update_hw_stats
  - net/sched/act_api.c:tcf_action_offload_add_ex
```
```
In net/ipv4/route.c (ffffffff81cd2269)
Location: include/linux/spinlock.h:392
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:rt_flush_dev
  - net/ipv4/route.c:ipv4_dst_destroy
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/inetpeer.c (ffffffff81cd4934)
Location: include/linux/spinlock.h:392
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/inet_hashtables.c (ffffffff81ce314a)
Location: include/linux/spinlock.h:392
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_unhash
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ce5192)
Location: include/linux/spinlock.h:392
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp.c (ffffffff81ce7acb)
Location: include/linux/spinlock.h:392
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_info
  - net/ipv4/tcp.c:tcp_ioctl
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d0a394)
Location: include/linux/spinlock.h:392
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_show
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
  - net/ipv4/tcp_ipv4.c:tcp_seq_stop
  - net/ipv4/tcp_ipv4.c:established_get_next
  - net/ipv4/tcp_ipv4.c:established_get_first
```
```
In net/ipv4/tcp_metrics.c (ffffffff81d119b7)
Location: include/linux/spinlock.h:392
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_flush_all
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/raw.c (ffffffff81d165e8)
Location: include/linux/spinlock.h:392
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81d1ab7d)
Location: include/linux/spinlock.h:392
Inline: True
Inline callers:
  - net/ipv4/udp.c:bpf_iter_udp_seq_stop
  - net/ipv4/udp.c:udp_get_next
  - net/ipv4/udp.c:udp_destroy_sock
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:skb_consume_udp
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/af_inet.c (ffffffff81d2b24f)
Location: include/linux/spinlock.h:392
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_register_protosw
```
```
In net/ipv4/igmp.c (ffffffff81d2e4e7)
Location: include/linux/spinlock.h:392
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_mcf_seq_stop
  - net/ipv4/igmp.c:igmp_mcf_seq_next
  - net/ipv4/igmp.c:igmp_mcf_seq_start
  - net/ipv4/igmp.c:ip_check_mc_rcu
  - net/ipv4/igmp.c:ip_mc_clear_src
  - net/ipv4/igmp.c:ip_mc_add_src
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:igmpv3_clear_delrec
  - net/ipv4/igmp.c:igmpv3_clear_delrec
  - net/ipv4/igmp.c:igmpv3_del_delrec
  - net/ipv4/igmp.c:igmpv3_del_delrec
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmpv3_send_cr
  - net/ipv4/igmp.c:igmpv3_send_cr
```
```
In net/ipv4/fib_semantics.c (ffffffff81d3a646)
Location: include/linux/spinlock.h:392
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_info_hash_move
  - net/ipv4/fib_semantics.c:fib_release_info
```
```
In net/ipv4/inet_fragment.c (ffffffff81d413d7)
Location: include/linux/spinlock.h:392
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frags_free_cb
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81d4eebf)
Location: include/linux/spinlock.h:392
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
```
In net/ipv4/ipmr.c (ffffffff81d56c56)
Location: include/linux/spinlock.h:392
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:mr_mfc_seq_stop
```
```
In net/ipv4/ipmr_base.c (ffffffff81d59ac4)
Location: include/linux/spinlock.h:392
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_table_dump
  - net/ipv4/ipmr_base.c:mr_table_dump
  - net/ipv4/ipmr_base.c:mr_mfc_seq_next
```
```
In net/ipv4/tcp_bpf.c (ffffffff81d5bf30)
Location: include/linux/spinlock.h:392
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_update_proto
```
```
In net/ipv4/udp_bpf.c (ffffffff81d5dea9)
Location: include/linux/spinlock.h:392
Inline: True
Inline callers:
  - net/ipv4/udp_bpf.c:udp_bpf_update_proto
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81d5f158)
Location: include/linux/spinlock.h:392
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_check
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_check
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_invalidate
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d68b4d)
Location: include/linux/spinlock.h:392
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:clone_policy
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_walk
  - net/xfrm/xfrm_policy.c:xfrm_policy_flush
  - net/xfrm/xfrm_policy.c:xfrm_policy_flush
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
```
```
In net/xfrm/xfrm_state.c (ffffffff81d6f852)
Location: include/linux/spinlock.h:392
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel
  - net/xfrm/xfrm_state.c:xfrm_state_unregister_afinfo
  - net/xfrm/xfrm_state.c:xfrm_state_register_afinfo
  - net/xfrm/xfrm_state.c:xfrm_unregister_km
  - net/xfrm/xfrm_state.c:xfrm_register_km
  - net/xfrm/xfrm_state.c:xfrm_unregister_translator
  - net/xfrm/xfrm_state.c:xfrm_register_translator
  - net/xfrm/xfrm_state.c:xfrm_state_walk
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_find_acq_byseq
  - net/xfrm/xfrm_state.c:xfrm_find_acq
  - net/xfrm/xfrm_state.c:xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_state_lookup_byspi
  - net/xfrm/xfrm_state.c:xfrm_state_lookup_byspi
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_sad_getinfo
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_gc_task
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_input.c (ffffffff81d74e7f)
Location: include/linux/spinlock.h:392
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo
  - net/xfrm/xfrm_input.c:xfrm_input_register_afinfo
```
```
In net/xfrm/xfrm_output.c (ffffffff81d77c4a)
Location: include/linux/spinlock.h:392
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/unix/af_unix.c (ffffffff81d7ca58)
Location: include/linux/spinlock.h:392
Inline: True
Inline callers:
  - net/unix/af_unix.c:bpf_iter_unix_seq_show
```
```
In net/unix/unix_bpf.c (ffffffff81d83f37)
Location: include/linux/spinlock.h:392
Inline: True
Inline callers:
  - net/unix/unix_bpf.c:unix_stream_bpf_update_proto
  - net/unix/unix_bpf.c:unix_dgram_bpf_update_proto
```
```
In net/ipv6/af_inet6.c (ffffffff81d8485c)
Location: include/linux/spinlock.h:392
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_register_protosw
```
```
In net/ipv6/addrconf.c (ffffffff81d910fc)
Location: include/linux/spinlock.h:392
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:ipv6_generate_stable_address
  - net/ipv6/addrconf.c:addrconf_add_linklocal
  - net/ipv6/addrconf.c:add_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/route.c (ffffffff81da9e20)
Location: include/linux/spinlock.h:392
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:fib6_clean_tohost
  - net/ipv6/route.c:fib6_remove_prefsrc
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_del_rt_siblings
  - net/ipv6/route.c:ip6_route_add
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:fib6_table_lookup
  - net/ipv6/route.c:fib6_nh_remove_exception
  - net/ipv6/route.c:fib6_nh_flush_exceptions
  - net/ipv6/route.c:rt6_insert_exception
  - net/ipv6/route.c:rt6_insert_exception
  - net/ipv6/route.c:ip6_ins_rt
  - net/ipv6/route.c:ip6_dst_destroy
```
```
In net/ipv6/ip6_fib.c (ffffffff81dabb3f)
Location: include/linux/spinlock.h:392
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:__fib6_clean_all
  - net/ipv6/ip6_fib.c:fib6_update_sernum_stub
  - net/ipv6/ip6_fib.c:fib6_tables_dump
```
```
In net/ipv6/raw.c (ffffffff81dbc798)
Location: include/linux/spinlock.h:392
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff81dc7517)
Location: include/linux/spinlock.h:392
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_destroy_dev
  - net/ipv6/mcast.c:ipv6_mc_destroy_dev
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:mld_query_work
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81dd38f6)
Location: include/linux/spinlock.h:392
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:fl6_renew
  - net/ipv6/ip6_flowlabel.c:fl6_free_socklist
  - net/ipv6/ip6_flowlabel.c:fl6_free_socklist
  - net/ipv6/ip6_flowlabel.c:fl_release
```
```
In net/ipv6/ip6mr.c (ffffffff81ddc07e)
Location: include/linux/spinlock.h:392
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:mr_mfc_seq_stop
```
```
In net/ipv6/calipso.c (ffffffff81de4634)
Location: include/linux/spinlock.h:392
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_cache_add
  - net/ipv6/calipso.c:calipso_cache_check
  - net/ipv6/calipso.c:calipso_cache_check
  - net/ipv6/calipso.c:calipso_cache_invalidate
```
```
In net/packet/af_packet.c (ffffffff81df4e41)
Location: include/linux/spinlock.h:392
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_ioctl
  - net/packet/af_packet.c:packet_getsockopt
```
```
In net/dcb/dcbnl.c (ffffffff81e07886)
Location: include/linux/spinlock.h:392
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_netdevice_event
  - net/dcb/dcbnl.c:dcb_ieee_getapp_default_prio_mask
  - net/dcb/dcbnl.c:dcb_ieee_getapp_dscp_prio_mask_map
  - net/dcb/dcbnl.c:dcb_ieee_getapp_prio_dscp_mask_map
  - net/dcb/dcbnl.c:dcb_ieee_delapp
  - net/dcb/dcbnl.c:dcb_ieee_setapp
  - net/dcb/dcbnl.c:dcb_ieee_getapp_mask
  - net/dcb/dcbnl.c:dcb_setapp
  - net/dcb/dcbnl.c:dcb_getapp
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
```
```
In net/switchdev/switchdev.c (ffffffff81e0cd57)
Location: include/linux/spinlock.h:392
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_deferred_enqueue
  - net/switchdev/switchdev.c:switchdev_deferred_process
```
```
In net/xdp/xsk.c (ffffffff81e16dcf)
Location: include/linux/spinlock.h:392
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xsk.c:xsk_generic_rcv
```
```
In net/xdp/xskmap.c (ffffffff81e19cdc)
Location: include/linux/spinlock.h:392
Inline: True
Inline callers:
  - net/xdp/xskmap.c:xsk_map_try_sock_delete
  - net/xdp/xskmap.c:xsk_map_delete_elem
  - net/xdp/xskmap.c:xsk_map_update_elem
  - net/xdp/xskmap.c:xsk_map_update_elem
  - net/xdp/xskmap.c:xsk_map_update_elem
  - net/xdp/xskmap.c:xsk_map_sock_delete
```
```
In net/mptcp/protocol.c (ffffffff81e20a8b)
Location: include/linux/spinlock.h:392
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_ioctl
  - net/mptcp/protocol.c:mptcp_finish_join
  - net/mptcp/protocol.c:mptcp_subflow_process_delegated
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:mptcp_destroy_common
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:__mptcp_retrans
  - net/mptcp/protocol.c:__mptcp_retrans
  - net/mptcp/protocol.c:__mptcp_retransmit_pending_data
  - net/mptcp/protocol.c:__mptcp_retransmit_pending_data
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:__mptcp_move_skbs
  - net/mptcp/protocol.c:__mptcp_move_skbs
  - net/mptcp/protocol.c:__mptcp_move_skbs
  - net/mptcp/protocol.c:mptcp_rcv_space_adjust
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:mptcp_data_ready
```
```
In net/mptcp/subflow.c (ffffffff81e2881d)
Location: include/linux/spinlock.h:392
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_queue_clean
  - net/mptcp/subflow.c:mptcp_subflow_queue_clean
  - net/mptcp/subflow.c:subflow_state_change
  - net/mptcp/subflow.c:__mptcp_subflow_connect
  - net/mptcp/subflow.c:subflow_data_ready
  - net/mptcp/subflow.c:mptcp_set_connected
```
```
In net/mptcp/options.c (ffffffff81e2aa74)
Location: include/linux/spinlock.h:392
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_incoming_options
  - net/mptcp/options.c:ack_update_msk
```
```
In net/mptcp/token.c (ffffffff81e2bfc5)
Location: include/linux/spinlock.h:392
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_destroy
  - net/mptcp/token.c:mptcp_token_destroy_request
  - net/mptcp/token.c:mptcp_token_accept
  - net/mptcp/token.c:mptcp_token_new_connect
  - net/mptcp/token.c:mptcp_token_new_connect
  - net/mptcp/token.c:mptcp_token_new_request
  - net/mptcp/token.c:mptcp_token_new_request
```
```
In net/mptcp/pm.c (ffffffff81e2d66e)
Location: include/linux/spinlock.h:392
Inline: True
Inline callers:
  - net/mptcp/pm.c:mptcp_pm_rm_addr_signal
  - net/mptcp/pm.c:mptcp_pm_add_addr_signal
  - net/mptcp/pm.c:mptcp_pm_mp_prio_received
  - net/mptcp/pm.c:mptcp_pm_rm_addr_received
  - net/mptcp/pm.c:mptcp_pm_add_addr_echoed
  - net/mptcp/pm.c:mptcp_pm_add_addr_received
  - net/mptcp/pm.c:mptcp_pm_subflow_check_next
  - net/mptcp/pm.c:mptcp_pm_subflow_established
  - net/mptcp/pm.c:mptcp_pm_fully_established
  - net/mptcp/pm.c:mptcp_pm_allow_new_subflow
  - net/mptcp/pm.c:mptcp_pm_remove_subflow
```
```
In net/mptcp/pm_netlink.c (ffffffff81e31972)
Location: include/linux/spinlock.h:392
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_flags
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_flags
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_flags
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_limits
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_dump_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_addr
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_addr
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_flush_addrs
  - net/mptcp/pm_netlink.c:mptcp_pm_remove_addrs_and_subflows
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr
  - net/mptcp/pm_netlink.c:mptcp_nl_remove_id_zero_address
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_add_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_subflow_chk_stale
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_append_new_local_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_work
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_rm_addr_or_subflow
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_mp_prio_send_ack
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_addr_send_ack
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_free_anno_list
  - net/mptcp/pm_netlink.c:mptcp_pm_del_add_timer
  - net/mptcp/pm_netlink.c:mptcp_pm_add_timer
  - net/mptcp/pm_netlink.c:mptcp_pm_sport_in_anno_list
```
```
In net/mptcp/sockopt.c (ffffffff81e35094)
Location: include/linux/spinlock.h:392
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:mptcp_sockopt_sync
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_int
  - net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval
```
```
In net/mptcp/pm_userspace.c (ffffffff81e356b9)
Location: include/linux/spinlock.h:392
Inline: True
Inline callers:
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_announce
  - net/mptcp/pm_userspace.c:mptcp_userspace_pm_get_flags_and_ifindex_by_id
  - net/mptcp/pm_userspace.c:mptcp_userspace_pm_append_new_local_addr
  - net/mptcp/pm_userspace.c:mptcp_userspace_pm_append_new_local_addr
  - net/mptcp/pm_userspace.c:mptcp_free_local_addr_list
```
```
In net/mptcp/syncookies.c (ffffffff81e3648c)
Location: include/linux/spinlock.h:392
Inline: True
Inline callers:
  - net/mptcp/syncookies.c:mptcp_token_join_cookie_init_state
  - net/mptcp/syncookies.c:mptcp_token_join_cookie_init_state
  - net/mptcp/syncookies.c:mptcp_token_join_cookie_init_state
  - net/mptcp/syncookies.c:subflow_init_req_cookie_join_save
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
In kernel/cgroup/cgroup.c (ffffffff83eb07c6)
Location: include/linux/spinlock.h:393
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init_subsys
  - kernel/cgroup/cgroup.c:css_create
  - kernel/cgroup/cgroup.c:css_create
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
```
```
In kernel/bpf/core.c (ffffffff812c2196)
Location: include/linux/spinlock.h:393
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_ksym_del
  - kernel/bpf/core.c:bpf_ksym_add
```
```
In kernel/bpf/syscall.c (ffffffff812cd7c5)
Location: include/linux/spinlock.h:393
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:bpf_link_get_curr_or_next
  - kernel/bpf/syscall.c:bpf_prog_get_curr_or_next
  - kernel/bpf/syscall.c:bpf_map_get_curr_or_next
  - kernel/bpf/syscall.c:bpf_obj_get_next_id
  - kernel/bpf/syscall.c:bpf_raw_tp_link_attach
  - kernel/bpf/syscall.c:bpf_raw_tp_link_attach
  - kernel/bpf/syscall.c:bpf_perf_link_attach
  - kernel/bpf/syscall.c:bpf_perf_link_attach
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/syscall.c:bpf_link_prime
  - kernel/bpf/syscall.c:bpf_link_prime
  - kernel/bpf/syscall.c:bpf_link_free
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_map_inc_not_zero
  - kernel/bpf/syscall.c:map_create
```
```
In kernel/bpf/local_storage.c (ffffffff81303cd4)
Location: include/linux/spinlock.h:393
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_link
  - kernel/bpf/local_storage.c:cgroup_storage_map_free
  - kernel/bpf/local_storage.c:cgroup_storage_get_next_key
  - kernel/bpf/local_storage.c:cgroup_storage_get_next_key
  - kernel/bpf/local_storage.c:cgroup_storage_lookup
  - kernel/bpf/local_storage.c:cgroup_storage_lookup
```
```
In kernel/bpf/btf.c (ffffffff8130a25f)
Location: include/linux/spinlock.h:393
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_alloc_id
  - kernel/bpf/btf.c:bpf_find_btf_id
  - kernel/bpf/btf.c:bpf_find_btf_id
```
```
In kernel/bpf/reuseport_array.c (ffffffff8132bcd0)
Location: include/linux/spinlock.h:393
Inline: True
Inline callers:
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem
  - kernel/bpf/reuseport_array.c:reuseport_array_delete_elem
```
```
In kernel/padata.c (ffffffff81353508)
Location: include/linux/spinlock.h:393
Inline: True
Inline callers:
  - kernel/padata.c:padata_reorder
```
```
In kernel/watch_queue.c (ffffffff81358263)
Location: include/linux/spinlock.h:393
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_clear
  - kernel/watch_queue.c:watch_queue_clear
  - kernel/watch_queue.c:remove_watch_from_object
  - kernel/watch_queue.c:add_watch_to_object
  - kernel/watch_queue.c:add_watch_to_object
```
```
In mm/page-writeback.c (ffffffff8136a3c3)
Location: include/linux/spinlock.h:393
Inline: True
Inline callers:
  - mm/page-writeback.c:bdi_set_strict_limit
  - mm/page-writeback.c:bdi_set_max_bytes
  - mm/page-writeback.c:bdi_set_max_ratio
  - mm/page-writeback.c:bdi_set_min_ratio
  - mm/page-writeback.c:bdi_set_max_ratio_no_scale
  - mm/page-writeback.c:bdi_set_min_ratio_no_scale
```
```
In mm/backing-dev.c (ffffffff81397986)
Location: include/linux/spinlock.h:393
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:bdi_register_va
  - mm/backing-dev.c:bdi_get_by_id
```
```
In security/selinux/netif.c (ffffffff816804d1)
Location: include/linux/spinlock.h:393
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_netdev_notifier_handler
  - security/selinux/netif.c:sel_netif_flush
  - security/selinux/netif.c:sel_netif_sid_slow
```
```
In security/selinux/netnode.c (ffffffff81680d4d)
Location: include/linux/spinlock.h:393
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_flush
  - security/selinux/netnode.c:sel_netnode_sid
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (ffffffff8168113d)
Location: include/linux/spinlock.h:393
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_flush
  - security/selinux/netport.c:sel_netport_sid
  - security/selinux/netport.c:sel_netport_sid
```
```
In block/blk-cgroup.c (ffffffff81763695)
Location: include/linux/spinlock.h:393
Inline: True
Inline callers:
  - block/blk-cgroup.c:__blkcg_punt_bio_submit
  - block/blk-cgroup.c:blkg_async_bio_workfn
```
```
In drivers/connector/cn_queue.c (ffffffff81adcc7c)
Location: include/linux/spinlock.h:393
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_free_dev
  - drivers/connector/cn_queue.c:cn_queue_del_callback
  - drivers/connector/cn_queue.c:cn_queue_add_callback
```
```
In drivers/connector/connector.c (ffffffff81adcde2)
Location: include/linux/spinlock.h:393
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_proc_show
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/net/tun.c (ffffffff81beca8c)
Location: include/linux/spinlock.h:393
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_free_netdev
  - drivers/net/tun.c:tun_free_netdev
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_flow_update
  - drivers/net/tun.c:tun_flow_flush
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81bfc7ad)
Location: include/linux/spinlock.h:393
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_disconnect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_disconnect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_ccp_closed
  - drivers/net/ppp/ppp_generic.c:ppp_ccp_closed
  - drivers/net/ppp/ppp_generic.c:ppp_set_compress
  - drivers/net/ppp/ppp_generic.c:ppp_set_compress
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_input_error
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_dev_uninit
  - drivers/net/ppp/ppp_generic.c:ppp_dev_uninit
  - drivers/net/ppp/ppp_generic.c:ppp_get_stats64
  - drivers/net/ppp/ppp_generic.c:ppp_get_stats64
  - drivers/net/ppp/ppp_generic.c:ppp_compat_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_compat_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_poll
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - drivers/net/ppp/ppp_generic.c:ppp_read
```
```
In drivers/net/xen-netfront.c (ffffffff81c079ed)
Location: include/linux/spinlock.h:393
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:xennet_open
```
```
In net/core/sock.c (ffffffff81d9d03f)
Location: include/linux/spinlock.h:393
Inline: True
Inline callers:
  - net/core/sock.c:__lock_sock_fast
  - net/core/sock.c:release_sock
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:__sk_flush_backlog
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__lock_sock
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sock_set_mark
  - net/core/sock.c:sock_set_rcvbuf
  - net/core/sock.c:sock_set_keepalive
  - net/core/sock.c:sock_enable_timestamps
  - net/core/sock.c:sock_set_sndtimeo
  - net/core/sock.c:sock_set_priority
  - net/core/sock.c:sock_no_linger
  - net/core/sock.c:sock_set_reuseport
  - net/core/sock.c:sock_set_reuseaddr
  - net/core/sock.c:sock_bindtoindex
```
```
In net/core/request_sock.c (ffffffff81da11bf)
Location: include/linux/spinlock.h:393
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/core/datagram.c (ffffffff81db04b1)
Location: include/linux/spinlock.h:393
Inline: True
Inline callers:
  - net/core/datagram.c:skb_kill_datagram
```
```
In net/core/gen_stats.c (ffffffff81db2663)
Location: include/linux/spinlock.h:393
Inline: True
Inline callers:
  - net/core/gen_stats.c:gnet_stats_finish_copy
  - net/core/gen_stats.c:gnet_stats_finish_copy
  - net/core/gen_stats.c:gnet_stats_copy_app
  - net/core/gen_stats.c:gnet_stats_copy_app
  - net/core/gen_stats.c:gnet_stats_copy_queue
  - net/core/gen_stats.c:gnet_stats_copy_rate_est
  - net/core/gen_stats.c:gnet_stats_start_copy_compat
```
```
In net/core/gen_estimator.c (ffffffff81db2cec)
Location: include/linux/spinlock.h:393
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/net_namespace.c (ffffffff81db4e17)
Location: include/linux/spinlock.h:393
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:peernet2id_alloc
  - net/core/net_namespace.c:peernet2id_alloc
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/dev.c (ffffffff81dcec68)
Location: include/linux/spinlock.h:393
Inline: True
Inline callers:
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:__dev_set_allmulti
  - net/core/dev.c:dev_set_promiscuity
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:__dev_open
```
```
In net/core/dev_addr_lists.c (ffffffff81dd33db)
Location: include/linux/spinlock.h:393
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:dev_mc_flush
  - net/core/dev_addr_lists.c:dev_mc_del_global
  - net/core/dev_addr_lists.c:dev_mc_del
  - net/core/dev_addr_lists.c:__dev_mc_add
  - net/core/dev_addr_lists.c:dev_mc_add_excl
  - net/core/dev_addr_lists.c:dev_uc_flush
  - net/core/dev_addr_lists.c:dev_uc_del
  - net/core/dev_addr_lists.c:dev_uc_add
  - net/core/dev_addr_lists.c:dev_uc_add_excl
```
```
In net/core/neighbour.c (ffffffff81ddb9f8)
Location: include/linux/spinlock.h:393
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/core/rtnetlink.c (ffffffff81de4bec)
Location: include/linux/spinlock.h:393
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_fdb_dump
```
```
In net/core/sock_reuseport.c (ffffffff81e042e8)
Location: include/linux/spinlock.h:393
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_detach_prog
  - net/core/sock_reuseport.c:reuseport_detach_prog
  - net/core/sock_reuseport.c:reuseport_detach_prog
  - net/core/sock_reuseport.c:reuseport_attach_prog
  - net/core/sock_reuseport.c:reuseport_stop_listen_sock
  - net/core/sock_reuseport.c:reuseport_stop_listen_sock
  - net/core/sock_reuseport.c:reuseport_detach_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_alloc
  - net/core/sock_reuseport.c:reuseport_update_incoming_cpu
```
```
In net/core/page_pool.c (ffffffff81e0f15a)
Location: include/linux/spinlock.h:393
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_defragged_page
```
```
In net/core/net-procfs.c (ffffffff81e1119f)
Location: include/linux/spinlock.h:393
Inline: True
```
```
In net/core/devlink.c (ffffffff81e3e0cd)
Location: include/linux/spinlock.h:393
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_port_type_set
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
```
```
In net/core/skmsg.c (ffffffff81e4804a)
Location: include/linux/spinlock.h:393
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_verdict_apply
  - net/core/skmsg.c:sk_psock_skb_redirect
  - net/core/skmsg.c:sk_psock_skb_redirect
  - net/core/skmsg.c:sk_psock_stop
  - net/core/skmsg.c:sk_psock_link_pop
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_psock_skb_ingress_enqueue
  - net/core/skmsg.c:sk_msg_recvmsg
  - net/core/skmsg.c:sk_msg_recvmsg
  - net/core/skmsg.c:sk_msg_recvmsg
  - net/core/skmsg.c:sk_msg_recvmsg
```
```
In net/core/sock_map.c (ffffffff81e4b5f7)
Location: include/linux/spinlock.h:393
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_unref
```
```
In net/sched/sch_generic.c (ffffffff81e52d83)
Location: include/linux/spinlock.h:393
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_reset_queue
  - net/sched/sch_generic.c:dev_reset_queue
  - net/sched/sch_generic.c:dev_graft_qdisc
```
```
In net/sched/sch_mq.c (ffffffff81e534ec)
Location: include/linux/spinlock.h:393
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump
```
```
In net/sched/sch_api.c (ffffffff81e57213)
Location: include/linux/spinlock.h:393
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_grow
```
```
In net/sched/cls_api.c (ffffffff81e60a60)
Location: include/linux/spinlock.h:393
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_setup_action
  - net/sched/cls_api.c:tc_setup_action
```
```
In net/sched/act_api.c (ffffffff81e62032)
Location: include/linux/spinlock.h:393
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_offload_del_ex
  - net/sched/act_api.c:tcf_action_update_hw_stats
  - net/sched/act_api.c:tcf_action_offload_add_ex
```
```
In net/ipv4/route.c (ffffffff81e92793)
Location: include/linux/spinlock.h:393
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:rt_flush_dev
  - net/ipv4/route.c:ipv4_dst_destroy
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/inetpeer.c (ffffffff81e94c14)
Location: include/linux/spinlock.h:393
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/inet_hashtables.c (ffffffff81ea55eb)
Location: include/linux/spinlock.h:393
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_bhash2_update_saddr
  - net/ipv4/inet_hashtables.c:inet_unhash
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ea8382)
Location: include/linux/spinlock.h:393
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp.c (ffffffff81eab380)
Location: include/linux/spinlock.h:393
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_info
  - net/ipv4/tcp.c:tcp_ioctl
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ecfc14)
Location: include/linux/spinlock.h:393
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_show
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
  - net/ipv4/tcp_ipv4.c:tcp_seq_stop
  - net/ipv4/tcp_ipv4.c:established_get_next
  - net/ipv4/tcp_ipv4.c:established_get_first
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ed7777)
Location: include/linux/spinlock.h:393
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_flush_all
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/raw.c (ffffffff81edc8e8)
Location: include/linux/spinlock.h:393
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81ee2565)
Location: include/linux/spinlock.h:393
Inline: True
Inline callers:
  - net/ipv4/udp.c:bpf_iter_udp_seq_stop
  - net/ipv4/udp.c:udp_get_next
  - net/ipv4/udp.c:udp_destroy_sock
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_lib_unhash
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:skb_consume_udp
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/af_inet.c (ffffffff81ef2e3f)
Location: include/linux/spinlock.h:393
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_register_protosw
```
```
In net/ipv4/igmp.c (ffffffff81ef6487)
Location: include/linux/spinlock.h:393
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_mcf_seq_stop
  - net/ipv4/igmp.c:igmp_mcf_seq_next
  - net/ipv4/igmp.c:igmp_mcf_seq_start
  - net/ipv4/igmp.c:ip_check_mc_rcu
  - net/ipv4/igmp.c:ip_mc_clear_src
  - net/ipv4/igmp.c:ip_mc_add_src
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:igmpv3_clear_delrec
  - net/ipv4/igmp.c:igmpv3_clear_delrec
  - net/ipv4/igmp.c:igmpv3_del_delrec
  - net/ipv4/igmp.c:igmpv3_del_delrec
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmpv3_send_cr
  - net/ipv4/igmp.c:igmpv3_send_cr
```
```
In net/ipv4/fib_semantics.c (ffffffff81f02fa6)
Location: include/linux/spinlock.h:393
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_info_hash_move
  - net/ipv4/fib_semantics.c:fib_release_info
```
```
In net/ipv4/inet_fragment.c (ffffffff81f0a1a2)
Location: include/linux/spinlock.h:393
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frags_free_cb
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81f18abf)
Location: include/linux/spinlock.h:393
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
```
In net/ipv4/ipmr.c (ffffffff81f21526)
Location: include/linux/spinlock.h:393
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:mr_mfc_seq_stop
```
```
In net/ipv4/ipmr_base.c (ffffffff81f23ef2)
Location: include/linux/spinlock.h:393
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_table_dump
  - net/ipv4/ipmr_base.c:mr_table_dump
  - net/ipv4/ipmr_base.c:mr_mfc_seq_next
```
```
In net/ipv4/tcp_bpf.c (ffffffff81f269a8)
Location: include/linux/spinlock.h:393
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_update_proto
```
```
In net/ipv4/udp_bpf.c (ffffffff81f28529)
Location: include/linux/spinlock.h:393
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81f297e8)
Location: include/linux/spinlock.h:393
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_check
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_check
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_invalidate
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f33ded)
Location: include/linux/spinlock.h:393
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:clone_policy
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_policy_walk
  - net/xfrm/xfrm_policy.c:xfrm_dev_policy_flush
  - net/xfrm/xfrm_policy.c:xfrm_dev_policy_flush
  - net/xfrm/xfrm_policy.c:xfrm_policy_flush
  - net/xfrm/xfrm_policy.c:xfrm_policy_flush
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff81f3aff2)
Location: include/linux/spinlock.h:393
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel
  - net/xfrm/xfrm_state.c:xfrm_state_unregister_afinfo
  - net/xfrm/xfrm_state.c:xfrm_state_register_afinfo
  - net/xfrm/xfrm_state.c:xfrm_unregister_km
  - net/xfrm/xfrm_state.c:xfrm_register_km
  - net/xfrm/xfrm_state.c:xfrm_unregister_translator
  - net/xfrm/xfrm_state.c:xfrm_register_translator
  - net/xfrm/xfrm_state.c:xfrm_state_walk
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_find_acq_byseq
  - net/xfrm/xfrm_state.c:xfrm_find_acq
  - net/xfrm/xfrm_state.c:xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_state_lookup_byspi
  - net/xfrm/xfrm_state.c:xfrm_state_lookup_byspi
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_sad_getinfo
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_gc_task
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_input.c (ffffffff81f417d3)
Location: include/linux/spinlock.h:393
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue_net
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
  - net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo
  - net/xfrm/xfrm_input.c:xfrm_input_register_afinfo
```
```
In net/xfrm/xfrm_output.c (ffffffff81f44551)
Location: include/linux/spinlock.h:393
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/unix/af_unix.c (ffffffff81f49ad8)
Location: include/linux/spinlock.h:393
Inline: True
Inline callers:
  - net/unix/af_unix.c:bpf_iter_unix_seq_show
```
```
In net/unix/unix_bpf.c (ffffffff81f51799)
Location: include/linux/spinlock.h:393
Inline: True
Inline callers:
  - net/unix/unix_bpf.c:unix_stream_bpf_update_proto
  - net/unix/unix_bpf.c:unix_dgram_bpf_update_proto
```
```
In net/ipv6/af_inet6.c (ffffffff81f52190)
Location: include/linux/spinlock.h:393
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_register_protosw
```
```
In net/ipv6/addrconf.c (ffffffff81f5f84c)
Location: include/linux/spinlock.h:393
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:ipv6_generate_stable_address
  - net/ipv6/addrconf.c:addrconf_add_linklocal
  - net/ipv6/addrconf.c:add_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/route.c (ffffffff81f795f0)
Location: include/linux/spinlock.h:393
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:fib6_clean_tohost
  - net/ipv6/route.c:fib6_remove_prefsrc
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_del_rt_siblings
  - net/ipv6/route.c:ip6_route_add
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:fib6_table_lookup
  - net/ipv6/route.c:fib6_nh_remove_exception
  - net/ipv6/route.c:fib6_nh_flush_exceptions
  - net/ipv6/route.c:rt6_insert_exception
  - net/ipv6/route.c:rt6_insert_exception
  - net/ipv6/route.c:ip6_ins_rt
  - net/ipv6/route.c:ip6_dst_destroy
```
```
In net/ipv6/ip6_fib.c (ffffffff81f7b4bf)
Location: include/linux/spinlock.h:393
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:__fib6_clean_all
  - net/ipv6/ip6_fib.c:fib6_update_sernum_stub
  - net/ipv6/ip6_fib.c:fib6_tables_dump
```
```
In net/ipv6/raw.c (ffffffff81f8c868)
Location: include/linux/spinlock.h:393
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff81f981f7)
Location: include/linux/spinlock.h:393
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_destroy_dev
  - net/ipv6/mcast.c:ipv6_mc_destroy_dev
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:mld_query_work
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81fa4ed6)
Location: include/linux/spinlock.h:393
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:fl6_renew
  - net/ipv6/ip6_flowlabel.c:fl6_free_socklist
  - net/ipv6/ip6_flowlabel.c:fl6_free_socklist
  - net/ipv6/ip6_flowlabel.c:fl_release
```
```
In net/ipv6/ip6mr.c (ffffffff81faf28e)
Location: include/linux/spinlock.h:393
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:mr_mfc_seq_stop
```
```
In net/ipv6/calipso.c (ffffffff81fb6d84)
Location: include/linux/spinlock.h:393
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_cache_add
  - net/ipv6/calipso.c:calipso_cache_check
  - net/ipv6/calipso.c:calipso_cache_check
  - net/ipv6/calipso.c:calipso_cache_invalidate
```
```
In net/packet/af_packet.c (ffffffff81fc77cf)
Location: include/linux/spinlock.h:393
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_ioctl
  - net/packet/af_packet.c:packet_getsockopt
```
```
In net/dcb/dcbnl.c (ffffffff81fdcbe6)
Location: include/linux/spinlock.h:393
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_netdevice_event
  - net/dcb/dcbnl.c:dcb_ieee_getapp_default_prio_mask
  - net/dcb/dcbnl.c:dcb_ieee_getapp_dscp_prio_mask_map
  - net/dcb/dcbnl.c:dcb_ieee_getapp_prio_dscp_mask_map
  - net/dcb/dcbnl.c:dcb_ieee_delapp
  - net/dcb/dcbnl.c:dcb_ieee_setapp
  - net/dcb/dcbnl.c:dcb_ieee_getapp_mask
  - net/dcb/dcbnl.c:dcb_setapp
  - net/dcb/dcbnl.c:dcb_getapp
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
```
```
In net/switchdev/switchdev.c (ffffffff81fe2f47)
Location: include/linux/spinlock.h:393
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_deferred_enqueue
  - net/switchdev/switchdev.c:switchdev_deferred_process
```
```
In net/xdp/xsk.c (ffffffff81fee79f)
Location: include/linux/spinlock.h:393
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xsk.c:xsk_generic_rcv
```
```
In net/xdp/xskmap.c (ffffffff81ff10ac)
Location: include/linux/spinlock.h:393
Inline: True
Inline callers:
  - net/xdp/xskmap.c:xsk_map_try_sock_delete
  - net/xdp/xskmap.c:xsk_map_delete_elem
  - net/xdp/xskmap.c:xsk_map_update_elem
  - net/xdp/xskmap.c:xsk_map_update_elem
  - net/xdp/xskmap.c:xsk_map_update_elem
  - net/xdp/xskmap.c:xsk_map_sock_delete
```
```
In net/mptcp/protocol.c (ffffffff81ff7f1b)
Location: include/linux/spinlock.h:393
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_ioctl
  - net/mptcp/protocol.c:mptcp_finish_join
  - net/mptcp/protocol.c:mptcp_subflow_process_delegated
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:mptcp_destroy_common
  - net/mptcp/protocol.c:__mptcp_close
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:__mptcp_retrans
  - net/mptcp/protocol.c:__mptcp_retrans
  - net/mptcp/protocol.c:__mptcp_retransmit_pending_data
  - net/mptcp/protocol.c:__mptcp_retransmit_pending_data
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:__mptcp_move_skbs
  - net/mptcp/protocol.c:__mptcp_move_skbs
  - net/mptcp/protocol.c:__mptcp_move_skbs
  - net/mptcp/protocol.c:mptcp_rcv_space_adjust
  - net/mptcp/protocol.c:mptcp_data_ready
```
```
In net/mptcp/subflow.c (ffffffff82000754)
Location: include/linux/spinlock.h:393
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_queue_clean
  - net/mptcp/subflow.c:subflow_state_change
  - net/mptcp/subflow.c:__mptcp_subflow_connect
  - net/mptcp/subflow.c:subflow_data_ready
  - net/mptcp/subflow.c:mptcp_set_connected
```
```
In net/mptcp/options.c (ffffffff82002c04)
Location: include/linux/spinlock.h:393
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_incoming_options
  - net/mptcp/options.c:ack_update_msk
```
```
In net/mptcp/token.c (ffffffff82004205)
Location: include/linux/spinlock.h:393
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_destroy
  - net/mptcp/token.c:mptcp_token_destroy_request
  - net/mptcp/token.c:mptcp_token_accept
  - net/mptcp/token.c:mptcp_token_new_connect
  - net/mptcp/token.c:mptcp_token_new_connect
  - net/mptcp/token.c:mptcp_token_new_request
  - net/mptcp/token.c:mptcp_token_new_request
```
```
In net/mptcp/pm.c (ffffffff82005ace)
Location: include/linux/spinlock.h:393
Inline: True
Inline callers:
  - net/mptcp/pm.c:mptcp_pm_rm_addr_signal
  - net/mptcp/pm.c:mptcp_pm_add_addr_signal
  - net/mptcp/pm.c:mptcp_pm_mp_prio_received
  - net/mptcp/pm.c:mptcp_pm_rm_addr_received
  - net/mptcp/pm.c:mptcp_pm_add_addr_echoed
  - net/mptcp/pm.c:mptcp_pm_add_addr_received
  - net/mptcp/pm.c:mptcp_pm_subflow_check_next
  - net/mptcp/pm.c:mptcp_pm_subflow_established
  - net/mptcp/pm.c:mptcp_pm_fully_established
  - net/mptcp/pm.c:mptcp_pm_allow_new_subflow
  - net/mptcp/pm.c:mptcp_pm_remove_subflow
```
```
In net/mptcp/pm_netlink.c (ffffffff82009fb7)
Location: include/linux/spinlock.h:393
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_flags
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_flags
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_flags
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_limits
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_dump_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_addr
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_addr
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_flush_addrs
  - net/mptcp/pm_netlink.c:mptcp_pm_remove_addrs_and_subflows
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr
  - net/mptcp/pm_netlink.c:mptcp_nl_remove_id_zero_address
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_add_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_subflow_chk_stale
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_append_new_local_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_work
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_rm_addr_or_subflow
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_addr_send_ack
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:__mptcp_pm_send_ack
  - net/mptcp/pm_netlink.c:mptcp_pm_free_anno_list
  - net/mptcp/pm_netlink.c:mptcp_pm_del_add_timer
  - net/mptcp/pm_netlink.c:mptcp_pm_add_timer
  - net/mptcp/pm_netlink.c:mptcp_pm_sport_in_anno_list
```
```
In net/mptcp/sockopt.c (ffffffff8200dd04)
Location: include/linux/spinlock.h:393
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:mptcp_sockopt_sync
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_linger
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_int
  - net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval
```
```
In net/mptcp/pm_userspace.c (ffffffff8200e369)
Location: include/linux/spinlock.h:393
Inline: True
Inline callers:
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_announce
  - net/mptcp/pm_userspace.c:mptcp_userspace_pm_get_flags_and_ifindex_by_id
  - net/mptcp/pm_userspace.c:mptcp_userspace_pm_append_new_local_addr
  - net/mptcp/pm_userspace.c:mptcp_userspace_pm_append_new_local_addr
  - net/mptcp/pm_userspace.c:mptcp_free_local_addr_list
```
```
In net/mptcp/fastopen.c (ffffffff8200f0a2)
Location: include/linux/spinlock.h:393
Inline: True
Inline callers:
  - net/mptcp/fastopen.c:mptcp_fastopen_gen_msk_ackseq
  - net/mptcp/fastopen.c:mptcp_fastopen_subflow_synack_set_params
```
```
In net/mptcp/syncookies.c (ffffffff8200f47c)
Location: include/linux/spinlock.h:393
Inline: True
Inline callers:
  - net/mptcp/syncookies.c:mptcp_token_join_cookie_init_state
  - net/mptcp/syncookies.c:mptcp_token_join_cookie_init_state
  - net/mptcp/syncookies.c:mptcp_token_join_cookie_init_state
  - net/mptcp/syncookies.c:subflow_init_req_cookie_join_save
```
```
In lib/xarray.c (ffffffff82049a1c)
Location: include/linux/spinlock.h:393
Inline: True
Inline callers:
  - lib/xarray.c:__xas_nomem
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
In kernel/cgroup/cgroup.c (ffffffff836d57b6)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init_subsys
  - kernel/cgroup/cgroup.c:css_create
  - kernel/cgroup/cgroup.c:css_create
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
```
```
In kernel/bpf/core.c (ffffffff812e9056)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_ksym_del
  - kernel/bpf/core.c:bpf_ksym_add
```
```
In kernel/bpf/syscall.c (ffffffff812f4fbd)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:bpf_link_get_curr_or_next
  - kernel/bpf/syscall.c:bpf_map_get_fd_by_id
  - kernel/bpf/syscall.c:bpf_prog_get_curr_or_next
  - kernel/bpf/syscall.c:bpf_map_get_curr_or_next
  - kernel/bpf/syscall.c:bpf_obj_get_next_id
  - kernel/bpf/syscall.c:bpf_raw_tp_link_attach
  - kernel/bpf/syscall.c:bpf_raw_tp_link_attach
  - kernel/bpf/syscall.c:bpf_perf_link_attach
  - kernel/bpf/syscall.c:bpf_perf_link_attach
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/syscall.c:bpf_link_prime
  - kernel/bpf/syscall.c:bpf_link_prime
  - kernel/bpf/syscall.c:bpf_link_free
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_map_inc_not_zero
  - kernel/bpf/syscall.c:map_create
```
```
In kernel/bpf/local_storage.c (ffffffff81332662)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_link
  - kernel/bpf/local_storage.c:cgroup_storage_map_free
  - kernel/bpf/local_storage.c:cgroup_storage_get_next_key
  - kernel/bpf/local_storage.c:cgroup_storage_get_next_key
  - kernel/bpf/local_storage.c:cgroup_storage_lookup
  - kernel/bpf/local_storage.c:cgroup_storage_lookup
```
```
In kernel/bpf/btf.c (ffffffff8133976f)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_alloc_id
  - kernel/bpf/btf.c:bpf_find_btf_id
  - kernel/bpf/btf.c:bpf_find_btf_id
```
```
In kernel/bpf/reuseport_array.c (ffffffff8135be40)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem
  - kernel/bpf/reuseport_array.c:reuseport_array_delete_elem
```
```
In kernel/padata.c (ffffffff81384708)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - kernel/padata.c:padata_reorder
```
```
In kernel/watch_queue.c (ffffffff81389b73)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_clear
  - kernel/watch_queue.c:watch_queue_clear
  - kernel/watch_queue.c:remove_watch_from_object
  - kernel/watch_queue.c:remove_watch_from_object
  - kernel/watch_queue.c:add_watch_to_object
  - kernel/watch_queue.c:add_watch_to_object
```
```
In mm/page-writeback.c (ffffffff8139c553)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - mm/page-writeback.c:bdi_set_strict_limit
  - mm/page-writeback.c:bdi_set_max_bytes
  - mm/page-writeback.c:bdi_set_max_ratio
  - mm/page-writeback.c:bdi_set_min_ratio
  - mm/page-writeback.c:bdi_set_max_ratio_no_scale
  - mm/page-writeback.c:bdi_set_min_ratio_no_scale
```
```
In mm/backing-dev.c (ffffffff813ca916)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:bdi_register_va
  - mm/backing-dev.c:bdi_get_by_id
```
```
In security/selinux/netif.c (ffffffff816b85b1)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_netdev_notifier_handler
  - security/selinux/netif.c:sel_netif_flush
  - security/selinux/netif.c:sel_netif_sid_slow
```
```
In security/selinux/netnode.c (ffffffff816b8dfb)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_flush
  - security/selinux/netnode.c:sel_netnode_sid
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (ffffffff816b91eb)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_flush
  - security/selinux/netport.c:sel_netport_sid
  - security/selinux/netport.c:sel_netport_sid
```
```
In drivers/connector/cn_queue.c (ffffffff81b2aeec)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_free_dev
  - drivers/connector/cn_queue.c:cn_queue_del_callback
  - drivers/connector/cn_queue.c:cn_queue_add_callback
```
```
In drivers/connector/connector.c (ffffffff81b2b052)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_proc_show
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/net/tun.c (ffffffff81c44f8c)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_free_netdev
  - drivers/net/tun.c:tun_free_netdev
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_flow_update
  - drivers/net/tun.c:tun_flow_flush
```
```
In drivers/net/virtio_net.c (ffffffff81c54489)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_restore
  - drivers/net/virtio_net.c:virtnet_set_ringparam
  - drivers/net/virtio_net.c:virtnet_set_ringparam
  - drivers/net/virtio_net.c:virtnet_close
  - drivers/net/virtio_net.c:virtnet_open
  - drivers/net/virtio_net.c:virtnet_open
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81c61e2d)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_disconnect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_disconnect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_ccp_closed
  - drivers/net/ppp/ppp_generic.c:ppp_ccp_closed
  - drivers/net/ppp/ppp_generic.c:ppp_set_compress
  - drivers/net/ppp/ppp_generic.c:ppp_set_compress
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_input_error
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_dev_uninit
  - drivers/net/ppp/ppp_generic.c:ppp_dev_uninit
  - drivers/net/ppp/ppp_generic.c:ppp_get_stats64
  - drivers/net/ppp/ppp_generic.c:ppp_get_stats64
  - drivers/net/ppp/ppp_generic.c:ppp_compat_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_compat_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_poll
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - drivers/net/ppp/ppp_generic.c:ppp_read
```
```
In drivers/net/xen-netfront.c (ffffffff81c6d10d)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:xennet_open
```
```
In drivers/net/net_failover.c (ffffffff81c6fb6f)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - drivers/net/net_failover.c:net_failover_slave_register
```
```
In net/core/sock.c (ffffffff81e0b88f)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/core/sock.c:__lock_sock_fast
  - net/core/sock.c:release_sock
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:__sk_flush_backlog
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__lock_sock
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sock_set_mark
  - net/core/sock.c:sock_set_rcvbuf
  - net/core/sock.c:sock_set_keepalive
  - net/core/sock.c:sock_enable_timestamps
  - net/core/sock.c:sock_set_sndtimeo
  - net/core/sock.c:sock_set_priority
  - net/core/sock.c:sock_no_linger
  - net/core/sock.c:sock_set_reuseport
  - net/core/sock.c:sock_set_reuseaddr
  - net/core/sock.c:sock_bindtoindex
```
```
In net/core/request_sock.c (ffffffff81e0fa8f)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/core/skbuff.c (ffffffff81e1f2dd)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_attempt_defer_free
```
```
In net/core/datagram.c (ffffffff81e20961)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/core/datagram.c:skb_kill_datagram
```
```
In net/core/gen_stats.c (ffffffff81e22c33)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/core/gen_stats.c:gnet_stats_finish_copy
  - net/core/gen_stats.c:gnet_stats_finish_copy
  - net/core/gen_stats.c:gnet_stats_copy_app
  - net/core/gen_stats.c:gnet_stats_copy_app
  - net/core/gen_stats.c:gnet_stats_copy_queue
  - net/core/gen_stats.c:gnet_stats_copy_rate_est
  - net/core/gen_stats.c:gnet_stats_start_copy_compat
```
```
In net/core/gen_estimator.c (ffffffff81e232bc)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/net_namespace.c (ffffffff81e253e7)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:peernet2id_alloc
  - net/core/net_namespace.c:peernet2id_alloc
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/dev.c (ffffffff81e3f898)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:__dev_set_allmulti
  - net/core/dev.c:dev_set_promiscuity
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:__dev_open
```
```
In net/core/dev_addr_lists.c (ffffffff81e43fa2)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:dev_mc_flush
  - net/core/dev_addr_lists.c:dev_mc_del_global
  - net/core/dev_addr_lists.c:dev_mc_del
  - net/core/dev_addr_lists.c:__dev_mc_add
  - net/core/dev_addr_lists.c:dev_mc_add_excl
  - net/core/dev_addr_lists.c:dev_uc_flush
  - net/core/dev_addr_lists.c:dev_uc_del
  - net/core/dev_addr_lists.c:dev_uc_add
  - net/core/dev_addr_lists.c:dev_uc_add_excl
```
```
In net/core/neighbour.c (ffffffff81e4c75c)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/core/rtnetlink.c (ffffffff81e565fc)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_fdb_dump
```
```
In net/core/sock_reuseport.c (ffffffff81e76b38)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_detach_prog
  - net/core/sock_reuseport.c:reuseport_detach_prog
  - net/core/sock_reuseport.c:reuseport_detach_prog
  - net/core/sock_reuseport.c:reuseport_attach_prog
  - net/core/sock_reuseport.c:reuseport_stop_listen_sock
  - net/core/sock_reuseport.c:reuseport_stop_listen_sock
  - net/core/sock_reuseport.c:reuseport_detach_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_alloc
  - net/core/sock_reuseport.c:reuseport_update_incoming_cpu
```
```
In net/core/page_pool.c (ffffffff81e8291a)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_defragged_page
```
```
In net/core/net-procfs.c (ffffffff81e84aaf)
Location: include/linux/spinlock.h:394
Inline: True
```
```
In net/core/skmsg.c (ffffffff81ea316b)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_verdict_apply
  - net/core/skmsg.c:sk_psock_skb_redirect
  - net/core/skmsg.c:sk_psock_skb_redirect
  - net/core/skmsg.c:sk_psock_stop
  - net/core/skmsg.c:sk_psock_link_pop
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_psock_skb_ingress_enqueue
  - net/core/skmsg.c:sk_msg_recvmsg
  - net/core/skmsg.c:sk_msg_recvmsg
  - net/core/skmsg.c:sk_msg_recvmsg
  - net/core/skmsg.c:sk_msg_recvmsg
```
```
In net/core/sock_map.c (ffffffff81ea6d17)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_unref
```
```
In net/sched/sch_generic.c (ffffffff81eae612)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_reset_queue
  - net/sched/sch_generic.c:dev_reset_queue
  - net/sched/sch_generic.c:dev_graft_qdisc
```
```
In net/sched/sch_mq.c (ffffffff81eaed69)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump
```
```
In net/sched/sch_api.c (ffffffff81eb1913)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_grow
```
```
In net/sched/cls_api.c (ffffffff81ebc9e7)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_setup_action
  - net/sched/cls_api.c:tc_setup_action
```
```
In net/sched/act_api.c (ffffffff81ebcc06)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/sched/act_api.c:offload_action_init
```
```
In net/ipv4/route.c (ffffffff81ef0f28)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:rt_flush_dev
  - net/ipv4/route.c:ipv4_dst_destroy
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/inetpeer.c (ffffffff81ef33e4)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/inet_hashtables.c (ffffffff81f03d72)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_bhash2_update_saddr
  - net/ipv4/inet_hashtables.c:inet_unhash
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81f06c02)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp.c (ffffffff81f09a90)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_info
  - net/ipv4/tcp.c:tcp_ioctl
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f2f2a6)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
  - net/ipv4/tcp_ipv4.c:tcp_seq_stop
  - net/ipv4/tcp_ipv4.c:established_get_next
  - net/ipv4/tcp_ipv4.c:established_get_first
```
```
In net/ipv4/tcp_metrics.c (ffffffff81f36b5d)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_flush_all
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/raw.c (ffffffff81f3b498)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_ioctl
```
```
In net/ipv4/udp.c (ffffffff81f4034a)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/ipv4/udp.c:bpf_iter_udp_batch
  - net/ipv4/udp.c:udp_seq_stop
  - net/ipv4/udp.c:udp_get_next
  - net/ipv4/udp.c:udp_get_first
  - net/ipv4/udp.c:udp_destroy_sock
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_lib_unhash
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:skb_consume_udp
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/af_inet.c (ffffffff81f528ef)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_register_protosw
```
```
In net/ipv4/igmp.c (ffffffff81f55ef7)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_mcf_seq_stop
  - net/ipv4/igmp.c:igmp_mcf_seq_next
  - net/ipv4/igmp.c:igmp_mcf_seq_start
  - net/ipv4/igmp.c:ip_check_mc_rcu
  - net/ipv4/igmp.c:ip_mc_clear_src
  - net/ipv4/igmp.c:ip_mc_add_src
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:igmpv3_clear_delrec
  - net/ipv4/igmp.c:igmpv3_clear_delrec
  - net/ipv4/igmp.c:igmpv3_del_delrec
  - net/ipv4/igmp.c:igmpv3_del_delrec
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmpv3_send_cr
  - net/ipv4/igmp.c:igmpv3_send_cr
```
```
In net/ipv4/fib_semantics.c (ffffffff81f6299d)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_info_hash_move
  - net/ipv4/fib_semantics.c:fib_release_info
```
```
In net/ipv4/inet_fragment.c (ffffffff81f69cd2)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frags_free_cb
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81f7871f)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
```
In net/ipv4/ipmr.c (ffffffff81f80770)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:mr_mfc_seq_stop
```
```
In net/ipv4/ipmr_base.c (ffffffff81f83a82)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_table_dump
  - net/ipv4/ipmr_base.c:mr_table_dump
  - net/ipv4/ipmr_base.c:mr_mfc_seq_next
```
```
In net/ipv4/tcp_bpf.c (ffffffff81f86668)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_update_proto
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
```
```
In net/ipv4/udp_bpf.c (ffffffff81f88095)
Location: include/linux/spinlock.h:394
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81f89388)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_check
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_check
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_invalidate
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f931ad)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:clone_policy
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_policy_walk
  - net/xfrm/xfrm_policy.c:xfrm_dev_policy_flush
  - net/xfrm/xfrm_policy.c:xfrm_dev_policy_flush
  - net/xfrm/xfrm_policy.c:xfrm_policy_flush
  - net/xfrm/xfrm_policy.c:xfrm_policy_flush
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff81f9aa12)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel
  - net/xfrm/xfrm_state.c:xfrm_state_unregister_afinfo
  - net/xfrm/xfrm_state.c:xfrm_state_register_afinfo
  - net/xfrm/xfrm_state.c:xfrm_unregister_km
  - net/xfrm/xfrm_state.c:xfrm_register_km
  - net/xfrm/xfrm_state.c:xfrm_unregister_translator
  - net/xfrm/xfrm_state.c:xfrm_register_translator
  - net/xfrm/xfrm_state.c:xfrm_state_walk
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_find_acq_byseq
  - net/xfrm/xfrm_state.c:xfrm_find_acq
  - net/xfrm/xfrm_state.c:xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_state_lookup_byspi
  - net/xfrm/xfrm_state.c:xfrm_state_lookup_byspi
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_sad_getinfo
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_gc_task
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_input.c (ffffffff81fa1073)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue_net
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
  - net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo
  - net/xfrm/xfrm_input.c:xfrm_input_register_afinfo
```
```
In net/xfrm/xfrm_output.c (ffffffff81fa3d37)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/unix/af_unix.c (ffffffff81fa9735)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/unix/af_unix.c:bpf_iter_unix_seq_show
```
```
In net/unix/unix_bpf.c (ffffffff81fb1119)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/unix/unix_bpf.c:unix_stream_bpf_update_proto
  - net/unix/unix_bpf.c:unix_dgram_bpf_update_proto
```
```
In net/ipv6/af_inet6.c (ffffffff81fb1ba0)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_register_protosw
```
```
In net/ipv6/addrconf.c (ffffffff81fbf57c)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:ipv6_generate_stable_address
  - net/ipv6/addrconf.c:addrconf_add_linklocal
  - net/ipv6/addrconf.c:add_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff81fd9800)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:fib6_clean_tohost
  - net/ipv6/route.c:fib6_remove_prefsrc
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_del_rt_siblings
  - net/ipv6/route.c:ip6_route_add
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:fib6_table_lookup
  - net/ipv6/route.c:fib6_nh_remove_exception
  - net/ipv6/route.c:fib6_nh_flush_exceptions
  - net/ipv6/route.c:rt6_insert_exception
  - net/ipv6/route.c:rt6_insert_exception
  - net/ipv6/route.c:ip6_ins_rt
  - net/ipv6/route.c:ip6_dst_destroy
```
```
In net/ipv6/ip6_fib.c (ffffffff81fdb7ce)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:__fib6_clean_all
  - net/ipv6/ip6_fib.c:fib6_update_sernum_stub
  - net/ipv6/ip6_fib.c:fib6_tables_dump
```
```
In net/ipv6/raw.c (ffffffff81fecd88)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_ioctl
```
```
In net/ipv6/mcast.c (ffffffff81ff8be7)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_destroy_dev
  - net/ipv6/mcast.c:ipv6_mc_destroy_dev
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:mld_query_work
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff82005796)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:fl6_renew
  - net/ipv6/ip6_flowlabel.c:fl6_free_socklist
  - net/ipv6/ip6_flowlabel.c:fl6_free_socklist
  - net/ipv6/ip6_flowlabel.c:fl_release
```
```
In net/ipv6/ip6mr.c (ffffffff8200f00f)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:mr_mfc_seq_stop
```
```
In net/ipv6/calipso.c (ffffffff82017484)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_cache_add
  - net/ipv6/calipso.c:calipso_cache_check
  - net/ipv6/calipso.c:calipso_cache_check
  - net/ipv6/calipso.c:calipso_cache_invalidate
```
```
In net/packet/af_packet.c (ffffffff82028775)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_ioctl
  - net/packet/af_packet.c:packet_getsockopt
```
```
In net/devlink/leftover.c (ffffffff8203dcad)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/devlink/leftover.c:__devlink_port_type_set
  - net/devlink/leftover.c:devlink_nl_port_fill
  - net/devlink/leftover.c:devlink_nl_port_fill
```
```
In net/dcb/dcbnl.c (ffffffff82058a76)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_netdevice_event
  - net/dcb/dcbnl.c:dcb_ieee_getapp_default_prio_mask
  - net/dcb/dcbnl.c:dcb_ieee_getapp_dscp_prio_mask_map
  - net/dcb/dcbnl.c:dcb_ieee_getapp_prio_dscp_mask_map
  - net/dcb/dcbnl.c:dcb_getrewr_prio_dscp_mask_map
  - net/dcb/dcbnl.c:dcb_getrewr_prio_pcp_mask_map
  - net/dcb/dcbnl.c:dcb_ieee_delapp
  - net/dcb/dcbnl.c:dcb_ieee_setapp
  - net/dcb/dcbnl.c:dcb_delrewr
  - net/dcb/dcbnl.c:dcb_setrewr
  - net/dcb/dcbnl.c:dcb_getrewr
  - net/dcb/dcbnl.c:dcb_ieee_getapp_mask
  - net/dcb/dcbnl.c:dcb_setapp
  - net/dcb/dcbnl.c:dcb_getapp
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
```
```
In net/switchdev/switchdev.c (ffffffff8205f267)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_deferred_enqueue
  - net/switchdev/switchdev.c:switchdev_deferred_process
```
```
In net/xdp/xsk.c (ffffffff8206a8af)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xsk.c:xsk_generic_rcv
```
```
In net/xdp/xskmap.c (ffffffff8206d2dc)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/xdp/xskmap.c:xsk_map_try_sock_delete
  - net/xdp/xskmap.c:xsk_map_delete_elem
  - net/xdp/xskmap.c:xsk_map_update_elem
  - net/xdp/xskmap.c:xsk_map_update_elem
  - net/xdp/xskmap.c:xsk_map_update_elem
  - net/xdp/xskmap.c:xsk_map_sock_delete
```
```
In net/mptcp/protocol.c (ffffffff82074407)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_ioctl
  - net/mptcp/protocol.c:mptcp_finish_join
  - net/mptcp/protocol.c:mptcp_subflow_process_delegated
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:mptcp_destroy_common
  - net/mptcp/protocol.c:__mptcp_close
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:__mptcp_retrans
  - net/mptcp/protocol.c:__mptcp_retransmit_pending_data
  - net/mptcp/protocol.c:__mptcp_retransmit_pending_data
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:__mptcp_move_skbs
  - net/mptcp/protocol.c:__mptcp_move_skbs
  - net/mptcp/protocol.c:__mptcp_move_skbs
  - net/mptcp/protocol.c:mptcp_rcv_space_adjust
  - net/mptcp/protocol.c:mptcp_data_ready
  - net/mptcp/protocol.c:mptcp_send_ack
```
```
In net/mptcp/subflow.c (ffffffff8207c8f3)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_queue_clean
  - net/mptcp/subflow.c:mptcp_subflow_queue_clean
  - net/mptcp/subflow.c:subflow_state_change
  - net/mptcp/subflow.c:__mptcp_subflow_connect
  - net/mptcp/subflow.c:subflow_data_ready
  - net/mptcp/subflow.c:mptcp_set_connected
```
```
In net/mptcp/options.c (ffffffff8207ee02)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_incoming_options
  - net/mptcp/options.c:ack_update_msk
```
```
In net/mptcp/token.c (ffffffff820803fd)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_destroy
  - net/mptcp/token.c:mptcp_token_destroy_request
  - net/mptcp/token.c:mptcp_token_accept
  - net/mptcp/token.c:mptcp_token_new_connect
  - net/mptcp/token.c:mptcp_token_new_connect
  - net/mptcp/token.c:mptcp_token_new_request
  - net/mptcp/token.c:mptcp_token_new_request
```
```
In net/mptcp/pm.c (ffffffff82081cc0)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/mptcp/pm.c:mptcp_pm_rm_addr_signal
  - net/mptcp/pm.c:mptcp_pm_add_addr_signal
  - net/mptcp/pm.c:mptcp_pm_mp_prio_received
  - net/mptcp/pm.c:mptcp_pm_rm_addr_received
  - net/mptcp/pm.c:mptcp_pm_add_addr_echoed
  - net/mptcp/pm.c:mptcp_pm_add_addr_received
  - net/mptcp/pm.c:mptcp_pm_subflow_check_next
  - net/mptcp/pm.c:mptcp_pm_subflow_check_next
  - net/mptcp/pm.c:mptcp_pm_subflow_established
  - net/mptcp/pm.c:mptcp_pm_fully_established
  - net/mptcp/pm.c:mptcp_pm_allow_new_subflow
  - net/mptcp/pm.c:mptcp_pm_allow_new_subflow
  - net/mptcp/pm.c:mptcp_pm_remove_subflow
```
```
In net/mptcp/pm_netlink.c (ffffffff82086cb8)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_set_flags
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_set_flags
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_set_flags
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_limits
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_dump_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_addr
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_addr
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_flush_addrs
  - net/mptcp/pm_netlink.c:mptcp_pm_remove_addrs_and_subflows
  - net/mptcp/pm_netlink.c:mptcp_pm_remove_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr
  - net/mptcp/pm_netlink.c:mptcp_nl_remove_id_zero_address
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_add_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_subflow_chk_stale
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_append_new_local_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_work
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_rm_addr_or_subflow
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_addr_send_ack
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:__mptcp_pm_send_ack
  - net/mptcp/pm_netlink.c:mptcp_pm_free_anno_list
  - net/mptcp/pm_netlink.c:mptcp_pm_del_add_timer
  - net/mptcp/pm_netlink.c:mptcp_pm_add_timer
  - net/mptcp/pm_netlink.c:mptcp_pm_sport_in_anno_list
```
```
In net/mptcp/sockopt.c (ffffffff8208a6f4)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:mptcp_sockopt_sync
  - net/mptcp/sockopt.c:mptcp_diag_fill_info
  - net/mptcp/sockopt.c:mptcp_diag_fill_info
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_linger
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_int
  - net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval
```
```
In net/mptcp/pm_userspace.c (ffffffff8208b8a3)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_destroy
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_create
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_announce
  - net/mptcp/pm_userspace.c:mptcp_userspace_pm_get_flags_and_ifindex_by_id
  - net/mptcp/pm_userspace.c:mptcp_userspace_pm_append_new_local_addr
  - net/mptcp/pm_userspace.c:mptcp_free_local_addr_list
```
```
In net/mptcp/fastopen.c (ffffffff8208bc92)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/mptcp/fastopen.c:mptcp_fastopen_gen_msk_ackseq
  - net/mptcp/fastopen.c:mptcp_fastopen_subflow_synack_set_params
```
```
In net/mptcp/syncookies.c (ffffffff8208c06c)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/mptcp/syncookies.c:mptcp_token_join_cookie_init_state
  - net/mptcp/syncookies.c:mptcp_token_join_cookie_init_state
  - net/mptcp/syncookies.c:mptcp_token_join_cookie_init_state
  - net/mptcp/syncookies.c:subflow_init_req_cookie_join_save
```
```
In lib/xarray.c (ffffffff820c848c)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - lib/xarray.c:__xas_nomem
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
In kernel/cgroup/cgroup.c (ffffffff83907b26)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init_subsys
  - kernel/cgroup/cgroup.c:css_create
  - kernel/cgroup/cgroup.c:css_create
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
```
```
In kernel/bpf/core.c (ffffffff813073c6)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_ksym_del
  - kernel/bpf/core.c:bpf_ksym_add
```
```
In kernel/bpf/syscall.c (ffffffff81313e33)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:bpf_link_get_curr_or_next
  - kernel/bpf/syscall.c:bpf_map_get_fd_by_id
  - kernel/bpf/syscall.c:bpf_prog_get_curr_or_next
  - kernel/bpf/syscall.c:bpf_map_get_curr_or_next
  - kernel/bpf/syscall.c:bpf_obj_get_next_id
  - kernel/bpf/syscall.c:bpf_raw_tp_link_attach
  - kernel/bpf/syscall.c:bpf_raw_tp_link_attach
  - kernel/bpf/syscall.c:bpf_perf_link_attach
  - kernel/bpf/syscall.c:bpf_perf_link_attach
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/syscall.c:bpf_link_prime
  - kernel/bpf/syscall.c:bpf_link_prime
  - kernel/bpf/syscall.c:bpf_link_free
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_map_inc_not_zero
  - kernel/bpf/syscall.c:map_create
```
```
In kernel/bpf/local_storage.c (ffffffff81356c32)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_link
  - kernel/bpf/local_storage.c:cgroup_storage_map_free
  - kernel/bpf/local_storage.c:cgroup_storage_get_next_key
  - kernel/bpf/local_storage.c:cgroup_storage_get_next_key
  - kernel/bpf/local_storage.c:cgroup_storage_lookup
  - kernel/bpf/local_storage.c:cgroup_storage_lookup
```
```
In kernel/bpf/btf.c (ffffffff8135f89f)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_alloc_id
  - kernel/bpf/btf.c:bpf_find_btf_id
  - kernel/bpf/btf.c:bpf_find_btf_id
```
```
In kernel/bpf/reuseport_array.c (ffffffff81384ad0)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem
  - kernel/bpf/reuseport_array.c:reuseport_array_delete_elem
```
```
In kernel/padata.c (ffffffff813adb18)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - kernel/padata.c:padata_reorder
```
```
In kernel/watch_queue.c (ffffffff813b35c3)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_clear
  - kernel/watch_queue.c:watch_queue_clear
  - kernel/watch_queue.c:remove_watch_from_object
  - kernel/watch_queue.c:remove_watch_from_object
  - kernel/watch_queue.c:add_watch_to_object
  - kernel/watch_queue.c:add_watch_to_object
```
```
In mm/page-writeback.c (ffffffff813c6233)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - mm/page-writeback.c:bdi_set_strict_limit
  - mm/page-writeback.c:bdi_set_max_bytes
  - mm/page-writeback.c:bdi_set_max_ratio
  - mm/page-writeback.c:bdi_set_min_ratio
  - mm/page-writeback.c:bdi_set_max_ratio_no_scale
  - mm/page-writeback.c:bdi_set_min_ratio_no_scale
```
```
In mm/backing-dev.c (ffffffff813f5386)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:bdi_register_va
  - mm/backing-dev.c:bdi_get_by_id
```
```
In security/selinux/netif.c (ffffffff816f4fe4)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_netdev_notifier_handler
  - security/selinux/netif.c:sel_netif_flush
  - security/selinux/netif.c:sel_netif_sid_slow
```
```
In security/selinux/netnode.c (ffffffff816f587b)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_flush
  - security/selinux/netnode.c:sel_netnode_sid
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (ffffffff816f5c9b)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_flush
  - security/selinux/netport.c:sel_netport_sid
  - security/selinux/netport.c:sel_netport_sid
```
```
In drivers/connector/cn_queue.c (ffffffff81b821cc)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_free_dev
  - drivers/connector/cn_queue.c:cn_queue_del_callback
  - drivers/connector/cn_queue.c:cn_queue_add_callback
```
```
In drivers/connector/connector.c (ffffffff81b82332)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_proc_show
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/net/tun.c (ffffffff81cfaaec)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_free_netdev
  - drivers/net/tun.c:tun_free_netdev
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_flow_update
  - drivers/net/tun.c:tun_flow_flush
```
```
In drivers/net/virtio_net.c (ffffffff81d0aba7)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_restore
  - drivers/net/virtio_net.c:virtnet_set_ringparam
  - drivers/net/virtio_net.c:virtnet_set_ringparam
  - drivers/net/virtio_net.c:virtnet_close
  - drivers/net/virtio_net.c:virtnet_open
  - drivers/net/virtio_net.c:virtnet_open
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81d1882d)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_disconnect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_disconnect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_ccp_closed
  - drivers/net/ppp/ppp_generic.c:ppp_ccp_closed
  - drivers/net/ppp/ppp_generic.c:ppp_set_compress
  - drivers/net/ppp/ppp_generic.c:ppp_set_compress
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_input_error
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_dev_uninit
  - drivers/net/ppp/ppp_generic.c:ppp_dev_uninit
  - drivers/net/ppp/ppp_generic.c:ppp_get_stats64
  - drivers/net/ppp/ppp_generic.c:ppp_get_stats64
  - drivers/net/ppp/ppp_generic.c:ppp_compat_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_compat_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_poll
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - drivers/net/ppp/ppp_generic.c:ppp_read
```
```
In drivers/net/xen-netfront.c (ffffffff81d21a4a)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:xennet_open
```
```
In drivers/net/net_failover.c (ffffffff81d2441c)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - drivers/net/net_failover.c:net_failover_slave_register
```
```
In net/core/sock.c (ffffffff81ec827f)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/core/sock.c:__lock_sock_fast
  - net/core/sock.c:release_sock
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:__sk_flush_backlog
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__lock_sock
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sock_set_mark
  - net/core/sock.c:sock_set_rcvbuf
  - net/core/sock.c:sock_set_keepalive
  - net/core/sock.c:sock_enable_timestamps
  - net/core/sock.c:sock_set_sndtimeo
  - net/core/sock.c:sock_no_linger
  - net/core/sock.c:sock_set_reuseport
  - net/core/sock.c:sock_set_reuseaddr
  - net/core/sock.c:sock_bindtoindex
```
```
In net/core/request_sock.c (ffffffff81ecc53f)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/core/skbuff.c (ffffffff81edc93d)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_attempt_defer_free
```
```
In net/core/datagram.c (ffffffff81ede831)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/core/datagram.c:skb_kill_datagram
```
```
In net/core/gen_stats.c (ffffffff81ee0b73)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/core/gen_stats.c:gnet_stats_finish_copy
  - net/core/gen_stats.c:gnet_stats_finish_copy
  - net/core/gen_stats.c:gnet_stats_copy_app
  - net/core/gen_stats.c:gnet_stats_copy_app
  - net/core/gen_stats.c:gnet_stats_copy_queue
  - net/core/gen_stats.c:gnet_stats_copy_rate_est
  - net/core/gen_stats.c:gnet_stats_start_copy_compat
```
```
In net/core/gen_estimator.c (ffffffff81ee1229)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/net_namespace.c (ffffffff81ee3347)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:peernet2id_alloc
  - net/core/net_namespace.c:peernet2id_alloc
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/dev.c (ffffffff81efe1ee)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:__dev_set_allmulti
  - net/core/dev.c:dev_set_promiscuity
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:__dev_open
```
```
In net/core/dev_addr_lists.c (ffffffff81f02bf2)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:dev_mc_flush
  - net/core/dev_addr_lists.c:dev_mc_del_global
  - net/core/dev_addr_lists.c:dev_mc_del
  - net/core/dev_addr_lists.c:__dev_mc_add
  - net/core/dev_addr_lists.c:dev_mc_add_excl
  - net/core/dev_addr_lists.c:dev_uc_flush
  - net/core/dev_addr_lists.c:dev_uc_del
  - net/core/dev_addr_lists.c:dev_uc_add
  - net/core/dev_addr_lists.c:dev_uc_add_excl
```
```
In net/core/neighbour.c (ffffffff81f0b470)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/core/rtnetlink.c (ffffffff81f1595c)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_fdb_dump
```
```
In net/core/sock_reuseport.c (ffffffff81f36af8)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_detach_prog
  - net/core/sock_reuseport.c:reuseport_detach_prog
  - net/core/sock_reuseport.c:reuseport_detach_prog
  - net/core/sock_reuseport.c:reuseport_attach_prog
  - net/core/sock_reuseport.c:reuseport_stop_listen_sock
  - net/core/sock_reuseport.c:reuseport_stop_listen_sock
  - net/core/sock_reuseport.c:reuseport_detach_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_alloc
  - net/core/sock_reuseport.c:reuseport_update_incoming_cpu
```
```
In net/core/page_pool.c (ffffffff81f44aab)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_unrefed_page
```
```
In net/core/net-procfs.c (ffffffff81f46a77)
Location: include/linux/spinlock.h:394
Inline: True
```
```
In net/core/skmsg.c (ffffffff81f6548b)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_verdict_apply
  - net/core/skmsg.c:sk_psock_skb_redirect
  - net/core/skmsg.c:sk_psock_skb_redirect
  - net/core/skmsg.c:sk_psock_stop
  - net/core/skmsg.c:sk_psock_link_pop
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_psock_skb_ingress_enqueue
  - net/core/skmsg.c:sk_msg_recvmsg
  - net/core/skmsg.c:sk_msg_recvmsg
  - net/core/skmsg.c:sk_msg_recvmsg
  - net/core/skmsg.c:sk_msg_recvmsg
```
```
In net/core/sock_map.c (ffffffff81f686d8)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_remove_links
  - net/core/sock_map.c:sock_map_remove_links
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_delete_elem
  - net/core/sock_map.c:sock_map_unref
```
```
In net/sched/sch_generic.c (ffffffff81f71090)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_reset_queue
  - net/sched/sch_generic.c:dev_reset_queue
  - net/sched/sch_generic.c:dev_graft_qdisc
```
```
In net/sched/sch_mq.c (ffffffff81f71806)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump
```
```
In net/sched/sch_api.c (ffffffff81f743c3)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_grow
```
```
In net/sched/cls_api.c (ffffffff81f7fbe7)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_setup_action
  - net/sched/cls_api.c:tc_setup_action
```
```
In net/sched/act_api.c (ffffffff81f7fe06)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/sched/act_api.c:offload_action_init
```
```
In net/ipv4/route.c (ffffffff81fb507b)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:rt_flush_dev
  - net/ipv4/route.c:ipv4_dst_destroy
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/inetpeer.c (ffffffff81fb7374)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/inet_hashtables.c (ffffffff81fc7ff7)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_bhash2_update_saddr
  - net/ipv4/inet_hashtables.c:inet_unhash
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81fcaf22)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp.c (ffffffff81fcdda0)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_info
  - net/ipv4/tcp.c:tcp_ioctl
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff47f6)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
  - net/ipv4/tcp_ipv4.c:tcp_seq_stop
  - net/ipv4/tcp_ipv4.c:established_get_next
  - net/ipv4/tcp_ipv4.c:established_get_first
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ffcc76)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_flush_all
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
  - net/ipv4/tcp_metrics.c:tcpm_new
```
```
In net/ipv4/raw.c (ffffffff820015b8)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_ioctl
```
```
In net/ipv4/udp.c (ffffffff82005cce)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/ipv4/udp.c:bpf_iter_udp_batch
  - net/ipv4/udp.c:udp_seq_stop
  - net/ipv4/udp.c:udp_get_next
  - net/ipv4/udp.c:udp_get_first
  - net/ipv4/udp.c:udp_destroy_sock
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_lib_unhash
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/af_inet.c (ffffffff82018bcf)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_register_protosw
```
```
In net/ipv4/igmp.c (ffffffff8201c367)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_mcf_seq_stop
  - net/ipv4/igmp.c:igmp_mcf_seq_next
  - net/ipv4/igmp.c:igmp_mcf_seq_start
  - net/ipv4/igmp.c:ip_check_mc_rcu
  - net/ipv4/igmp.c:ip_mc_clear_src
  - net/ipv4/igmp.c:ip_mc_add_src
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:igmpv3_clear_delrec
  - net/ipv4/igmp.c:igmpv3_clear_delrec
  - net/ipv4/igmp.c:igmpv3_del_delrec
  - net/ipv4/igmp.c:igmpv3_del_delrec
  - net/ipv4/igmp.c:igmp_rcv
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmpv3_send_cr
  - net/ipv4/igmp.c:igmpv3_send_cr
```
```
In net/ipv4/fib_semantics.c (ffffffff82028f6d)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_info_hash_move
  - net/ipv4/fib_semantics.c:fib_release_info
```
```
In net/ipv4/inet_fragment.c (ffffffff82030352)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frags_free_cb
```
```
In net/ipv4/ipmr.c (ffffffff82046df0)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:mr_mfc_seq_stop
```
```
In net/ipv4/ipmr_base.c (ffffffff8204a132)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_table_dump
  - net/ipv4/ipmr_base.c:mr_table_dump
  - net/ipv4/ipmr_base.c:mr_mfc_seq_next
```
```
In net/ipv4/tcp_bpf.c (ffffffff8204dc6d)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_update_proto
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
```
```
In net/ipv4/udp_bpf.c (ffffffff8204f7b5)
Location: include/linux/spinlock.h:394
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (ffffffff82050ae7)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_check
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_check
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_invalidate
```
```
In net/xfrm/xfrm_policy.c (ffffffff82060bbd)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:clone_policy
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_policy_walk
  - net/xfrm/xfrm_policy.c:xfrm_dev_policy_flush
  - net/xfrm/xfrm_policy.c:xfrm_dev_policy_flush
  - net/xfrm/xfrm_policy.c:xfrm_policy_flush
  - net/xfrm/xfrm_policy.c:xfrm_policy_flush
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff82067d72)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel
  - net/xfrm/xfrm_state.c:xfrm_state_unregister_afinfo
  - net/xfrm/xfrm_state.c:xfrm_state_register_afinfo
  - net/xfrm/xfrm_state.c:xfrm_unregister_km
  - net/xfrm/xfrm_state.c:xfrm_register_km
  - net/xfrm/xfrm_state.c:xfrm_unregister_translator
  - net/xfrm/xfrm_state.c:xfrm_register_translator
  - net/xfrm/xfrm_state.c:xfrm_state_walk
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_find_acq_byseq
  - net/xfrm/xfrm_state.c:xfrm_find_acq
  - net/xfrm/xfrm_state.c:xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_state_lookup_byspi
  - net/xfrm/xfrm_state.c:xfrm_state_lookup_byspi
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_sad_getinfo
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_gc_task
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_input.c (ffffffff8206e393)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue_net
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
  - net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo
  - net/xfrm/xfrm_input.c:xfrm_input_register_afinfo
```
```
In net/xfrm/xfrm_output.c (ffffffff82071064)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/unix/af_unix.c (ffffffff82076bc5)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/unix/af_unix.c:bpf_iter_unix_seq_show
```
```
In net/unix/unix_bpf.c (ffffffff8207e80d)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/unix/unix_bpf.c:unix_stream_bpf_update_proto
  - net/unix/unix_bpf.c:unix_dgram_bpf_update_proto
```
```
In net/ipv6/af_inet6.c (ffffffff8207f2c0)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_register_protosw
```
```
In net/ipv6/addrconf.c (ffffffff8208ca1c)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:ipv6_generate_stable_address
  - net/ipv6/addrconf.c:addrconf_add_linklocal
  - net/ipv6/addrconf.c:add_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff820a7192)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:fib6_clean_tohost
  - net/ipv6/route.c:fib6_remove_prefsrc
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_del_rt_siblings
  - net/ipv6/route.c:ip6_route_add
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:fib6_table_lookup
  - net/ipv6/route.c:fib6_nh_remove_exception
  - net/ipv6/route.c:fib6_nh_flush_exceptions
  - net/ipv6/route.c:rt6_insert_exception
  - net/ipv6/route.c:rt6_insert_exception
  - net/ipv6/route.c:ip6_ins_rt
  - net/ipv6/route.c:ip6_dst_destroy
```
```
In net/ipv6/ip6_fib.c (ffffffff820a92fe)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:__fib6_clean_all
  - net/ipv6/ip6_fib.c:fib6_update_sernum_stub
  - net/ipv6/ip6_fib.c:fib6_tables_dump
```
```
In net/ipv6/raw.c (ffffffff820ba988)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_ioctl
```
```
In net/ipv6/mcast.c (ffffffff820c6857)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_destroy_dev
  - net/ipv6/mcast.c:ipv6_mc_destroy_dev
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:mld_query_work
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff820d45a6)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:fl6_renew
  - net/ipv6/ip6_flowlabel.c:fl6_free_socklist
  - net/ipv6/ip6_flowlabel.c:fl6_free_socklist
  - net/ipv6/ip6_flowlabel.c:fl_release
```
```
In net/ipv6/ip6mr.c (ffffffff820ddf9f)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:mr_mfc_seq_stop
```
```
In net/ipv6/calipso.c (ffffffff820e6453)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_cache_add
  - net/ipv6/calipso.c:calipso_cache_check
  - net/ipv6/calipso.c:calipso_cache_check
  - net/ipv6/calipso.c:calipso_cache_invalidate
```
```
In net/packet/af_packet.c (ffffffff820f81a7)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_ioctl
  - net/packet/af_packet.c:packet_getsockopt
```
```
In net/devlink/port.c (ffffffff8210752f)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/devlink/port.c:__devlink_port_type_set
  - net/devlink/port.c:devlink_nl_port_fill
  - net/devlink/port.c:devlink_nl_port_fill
```
```
In net/dcb/dcbnl.c (ffffffff8212b5c6)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_netdevice_event
  - net/dcb/dcbnl.c:dcb_ieee_getapp_default_prio_mask
  - net/dcb/dcbnl.c:dcb_ieee_getapp_dscp_prio_mask_map
  - net/dcb/dcbnl.c:dcb_ieee_getapp_prio_dscp_mask_map
  - net/dcb/dcbnl.c:dcb_getrewr_prio_dscp_mask_map
  - net/dcb/dcbnl.c:dcb_getrewr_prio_pcp_mask_map
  - net/dcb/dcbnl.c:dcb_ieee_delapp
  - net/dcb/dcbnl.c:dcb_ieee_setapp
  - net/dcb/dcbnl.c:dcb_delrewr
  - net/dcb/dcbnl.c:dcb_setrewr
  - net/dcb/dcbnl.c:dcb_getrewr
  - net/dcb/dcbnl.c:dcb_ieee_getapp_mask
  - net/dcb/dcbnl.c:dcb_setapp
  - net/dcb/dcbnl.c:dcb_getapp
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
```
```
In net/switchdev/switchdev.c (ffffffff821319d0)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_port_obj_act_is_deferred
  - net/switchdev/switchdev.c:switchdev_deferred_enqueue
  - net/switchdev/switchdev.c:switchdev_deferred_process
```
```
In net/xdp/xsk.c (ffffffff8213e4e0)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xsk.c:xsk_generic_rcv
```
```
In net/xdp/xskmap.c (ffffffff8214117c)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/xdp/xskmap.c:xsk_map_try_sock_delete
  - net/xdp/xskmap.c:xsk_map_delete_elem
  - net/xdp/xskmap.c:xsk_map_update_elem
  - net/xdp/xskmap.c:xsk_map_update_elem
  - net/xdp/xskmap.c:xsk_map_update_elem
  - net/xdp/xskmap.c:xsk_map_sock_delete
```
```
In net/mptcp/protocol.c (ffffffff82147f67)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_ioctl
  - net/mptcp/protocol.c:mptcp_finish_join
  - net/mptcp/protocol.c:mptcp_subflow_process_delegated
  - net/mptcp/protocol.c:mptcp_subflow_process_delegated
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:mptcp_destroy_common
  - net/mptcp/protocol.c:__mptcp_close
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:__mptcp_retrans
  - net/mptcp/protocol.c:__mptcp_retrans
  - net/mptcp/protocol.c:__mptcp_retransmit_pending_data
  - net/mptcp/protocol.c:__mptcp_retransmit_pending_data
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:__mptcp_move_skbs
  - net/mptcp/protocol.c:__mptcp_move_skbs
  - net/mptcp/protocol.c:__mptcp_move_skbs
  - net/mptcp/protocol.c:mptcp_rcv_space_adjust
  - net/mptcp/protocol.c:mptcp_data_ready
  - net/mptcp/protocol.c:mptcp_send_ack
```
```
In net/mptcp/subflow.c (ffffffff82151df3)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_queue_clean
  - net/mptcp/subflow.c:mptcp_subflow_queue_clean
  - net/mptcp/subflow.c:subflow_state_change
  - net/mptcp/subflow.c:subflow_state_change
  - net/mptcp/subflow.c:__mptcp_subflow_connect
  - net/mptcp/subflow.c:subflow_data_ready
  - net/mptcp/subflow.c:subflow_finish_connect
```
```
In net/mptcp/options.c (ffffffff821542f2)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_incoming_options
  - net/mptcp/options.c:ack_update_msk
  - net/mptcp/options.c:check_fully_established
```
```
In net/mptcp/token.c (ffffffff821558ed)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_destroy
  - net/mptcp/token.c:mptcp_token_destroy_request
  - net/mptcp/token.c:mptcp_token_accept
  - net/mptcp/token.c:mptcp_token_new_connect
  - net/mptcp/token.c:mptcp_token_new_connect
  - net/mptcp/token.c:mptcp_token_new_request
  - net/mptcp/token.c:mptcp_token_new_request
```
```
In net/mptcp/pm.c (ffffffff821572b0)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/mptcp/pm.c:mptcp_pm_rm_addr_signal
  - net/mptcp/pm.c:mptcp_pm_add_addr_signal
  - net/mptcp/pm.c:mptcp_pm_rm_addr_received
  - net/mptcp/pm.c:mptcp_pm_add_addr_echoed
  - net/mptcp/pm.c:mptcp_pm_add_addr_received
  - net/mptcp/pm.c:mptcp_pm_subflow_check_next
  - net/mptcp/pm.c:mptcp_pm_subflow_check_next
  - net/mptcp/pm.c:mptcp_pm_subflow_established
  - net/mptcp/pm.c:mptcp_pm_fully_established
  - net/mptcp/pm.c:mptcp_pm_allow_new_subflow
  - net/mptcp/pm.c:mptcp_pm_allow_new_subflow
  - net/mptcp/pm.c:mptcp_pm_remove_subflow
```
```
In net/mptcp/diag.c (ffffffff8215790f)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/mptcp/diag.c:subflow_get_info
  - net/mptcp/diag.c:subflow_get_info
```
```
In net/mptcp/pm_netlink.c (ffffffff8215c468)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_set_flags
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_set_flags
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_set_flags
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_set_limits_doit
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_get_addr_dumpit
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_get_addr_doit
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_get_addr_doit
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_flush_addrs_doit
  - net/mptcp/pm_netlink.c:mptcp_pm_remove_addrs_and_subflows
  - net/mptcp/pm_netlink.c:mptcp_pm_remove_addrs
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_del_addr_doit
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_del_addr_doit
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_del_addr_doit
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_del_addr_doit
  - net/mptcp/pm_netlink.c:mptcp_nl_remove_id_zero_address
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_doit
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_subflow_chk_stale
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_append_new_local_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_work
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_rm_addr_or_subflow
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_addr_send_ack
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:__mptcp_pm_send_ack
  - net/mptcp/pm_netlink.c:mptcp_pm_free_anno_list
  - net/mptcp/pm_netlink.c:mptcp_pm_del_add_timer
  - net/mptcp/pm_netlink.c:mptcp_pm_add_timer
  - net/mptcp/pm_netlink.c:mptcp_pm_sport_in_anno_list
```
```
In net/mptcp/sockopt.c (ffffffff82160275)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:mptcp_set_rcvlowat
  - net/mptcp/sockopt.c:mptcp_diag_fill_info
  - net/mptcp/sockopt.c:mptcp_diag_fill_info
  - net/mptcp/sockopt.c:mptcp_setsockopt
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_linger
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_int
  - net/mptcp/sockopt.c:mptcp_sol_socket_sync_intval
```
```
In net/mptcp/pm_userspace.c (ffffffff821616a4)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/mptcp/pm_userspace.c:mptcp_pm_nl_subflow_destroy_doit
  - net/mptcp/pm_userspace.c:mptcp_pm_nl_subflow_create_doit
  - net/mptcp/pm_userspace.c:mptcp_pm_nl_remove_doit
  - net/mptcp/pm_userspace.c:mptcp_pm_nl_announce_doit
  - net/mptcp/pm_userspace.c:mptcp_userspace_pm_get_local_id
  - net/mptcp/pm_userspace.c:mptcp_userspace_pm_get_flags_and_ifindex_by_id
  - net/mptcp/pm_userspace.c:mptcp_userspace_pm_append_new_local_addr
  - net/mptcp/pm_userspace.c:mptcp_free_local_addr_list
```
```
In net/mptcp/fastopen.c (ffffffff821619cc)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/mptcp/fastopen.c:mptcp_fastopen_subflow_synack_set_params
```
```
In net/mptcp/syncookies.c (ffffffff8216252c)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - net/mptcp/syncookies.c:mptcp_token_join_cookie_init_state
  - net/mptcp/syncookies.c:mptcp_token_join_cookie_init_state
  - net/mptcp/syncookies.c:mptcp_token_join_cookie_init_state
  - net/mptcp/syncookies.c:subflow_init_req_cookie_join_save
```
```
In lib/xarray.c (ffffffff821a2e0c)
Location: include/linux/spinlock.h:394
Inline: True
Inline callers:
  - lib/xarray.c:__xas_nomem
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
In kernel/cgroup/cgroup.c (ffff8000101d0dc0)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_idr_remove
  - kernel/cgroup/cgroup.c:cgroup_idr_replace
```
```
In kernel/bpf/core.c (ffff80001025e340)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
```
```
In kernel/bpf/syscall.c (ffff80001026555c)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_obj_get_next_id
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_map_inc_not_zero
  - kernel/bpf/syscall.c:map_create
```
```
In kernel/bpf/local_storage.c (ffff80001027f574)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_unlink
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_link
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_release
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_assign
  - kernel/bpf/local_storage.c:cgroup_storage_get_next_key
  - kernel/bpf/local_storage.c:cgroup_storage_get_next_key
  - kernel/bpf/local_storage.c:cgroup_storage_lookup
  - kernel/bpf/local_storage.c:cgroup_storage_lookup
```
```
In kernel/bpf/btf.c (ffff800010285680)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
```
```
In kernel/bpf/xskmap.c (ffff80001028965c)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - kernel/bpf/xskmap.c:xsk_map_try_sock_delete
  - kernel/bpf/xskmap.c:xsk_map_delete_elem
  - kernel/bpf/xskmap.c:xsk_map_update_elem
  - kernel/bpf/xskmap.c:xsk_map_update_elem
  - kernel/bpf/xskmap.c:xsk_map_update_elem
  - kernel/bpf/xskmap.c:xsk_map_sock_delete
```
```
In kernel/bpf/reuseport_array.c (ffff80001029092c)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem
  - kernel/bpf/reuseport_array.c:reuseport_array_delete_elem
```
```
In kernel/padata.c (ffff8000102a9dec)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - kernel/padata.c:padata_reorder
```
```
In mm/page-writeback.c (ffff8000102ba76c)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - mm/page-writeback.c:bdi_set_max_ratio
  - mm/page-writeback.c:bdi_set_min_ratio
```
```
In mm/backing-dev.c (ffff8000102dec5c)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:bdi_register_va
  - mm/backing-dev.c:bdi_get_by_id
  - mm/backing-dev.c:wb_wakeup_delayed
```
```
In fs/fs-writeback.c (ffff8000103cb1b0)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_queue_work
  - fs/fs-writeback.c:wb_wakeup
```
```
In security/selinux/netif.c (ffff800010557ec4)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_netdev_notifier_handler
  - security/selinux/netif.c:sel_netif_flush
  - security/selinux/netif.c:sel_netif_sid
```
```
In security/selinux/netnode.c (ffff800010558768)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_flush
  - security/selinux/netnode.c:sel_netnode_sid
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (ffff800010558b78)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_flush
  - security/selinux/netport.c:sel_netport_sid
  - security/selinux/netport.c:sel_netport_sid
```
```
In block/genhd.c (ffff8000105fa448)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - block/genhd.c:get_gendisk
```
```
In block/blk-cgroup.c (ffff80001060e754)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - block/blk-cgroup.c:__blkcg_punt_bio_submit
  - block/blk-cgroup.c:blkg_async_bio_workfn
```
```
In drivers/dma/dmaengine.c (ffff8000107fd000)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_run_dependencies
```
```
In drivers/dma/mv_xor.c (ffff800010806d04)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - drivers/dma/mv_xor.c:mv_xor_status
  - drivers/dma/mv_xor.c:mv_xor_free_chan_resources
  - drivers/dma/mv_xor.c:mv_xor_prep_dma_xor
  - drivers/dma/mv_xor.c:mv_xor_prep_dma_xor
  - drivers/dma/mv_xor.c:mv_xor_alloc_chan_resources
  - drivers/dma/mv_xor.c:mv_xor_tx_submit
```
```
In drivers/dma/mv_xor_v2.c (ffff8000108085ac)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - drivers/dma/mv_xor_v2.c:mv_xor_v2_tasklet
  - drivers/dma/mv_xor_v2.c:mv_xor_v2_issue_pending
  - drivers/dma/mv_xor_v2.c:mv_xor_v2_prep_sw_desc
  - drivers/dma/mv_xor_v2.c:mv_xor_v2_prep_sw_desc
  - drivers/dma/mv_xor_v2.c:mv_xor_v2_prep_sw_desc
  - drivers/dma/mv_xor_v2.c:mv_xor_v2_tx_submit
```
```
In drivers/connector/cn_queue.c (ffff8000108dd720)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_free_dev
  - drivers/connector/cn_queue.c:cn_queue_del_callback
  - drivers/connector/cn_queue.c:cn_queue_add_callback
```
```
In drivers/connector/connector.c (ffff8000108ddc98)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_proc_show
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/net/tun.c (ffff8000109dc020)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_set_ebpf
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_flow_update
  - drivers/net/tun.c:tun_flow_flush
```
```
In drivers/net/ppp/ppp_generic.c (ffff8000109fff74)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_disconnect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_disconnect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_ccp_closed
  - drivers/net/ppp/ppp_generic.c:ppp_ccp_closed
  - drivers/net/ppp/ppp_generic.c:ppp_set_compress
  - drivers/net/ppp/ppp_generic.c:ppp_set_compress
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_input_error
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_dev_uninit
  - drivers/net/ppp/ppp_generic.c:ppp_dev_uninit
  - drivers/net/ppp/ppp_generic.c:ppp_get_stats64
  - drivers/net/ppp/ppp_generic.c:ppp_get_stats64
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_poll
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - drivers/net/ppp/ppp_generic.c:ppp_read
```
```
In drivers/net/xen-netfront.c (ffff800010a0921c)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:netback_changed
  - drivers/net/xen-netfront.c:xennet_open
```
```
In net/core/sock.c (ffff800010bade88)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/sock.c:release_sock
  - net/core/sock.c:__sk_flush_backlog
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__lock_sock
```
```
In net/core/request_sock.c (ffff800010bb03a0)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/core/datagram.c (ffff800010bbc98c)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/datagram.c:__sk_queue_drop_skb
```
```
In net/core/gen_stats.c (ffff800010bbf4a4)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/gen_stats.c:gnet_stats_finish_copy
  - net/core/gen_stats.c:gnet_stats_finish_copy
  - net/core/gen_stats.c:gnet_stats_copy_queue
  - net/core/gen_stats.c:gnet_stats_copy_rate_est
  - net/core/gen_stats.c:___gnet_stats_copy_basic
  - net/core/gen_stats.c:gnet_stats_start_copy_compat
```
```
In net/core/gen_estimator.c (ffff800010bbf9b0)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/net_namespace.c (ffff800010bc1a10)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:peernet2id
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/dev.c (ffff800010bd5af4)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/dev.c:dev_set_rx_mode
  - net/core/dev.c:netif_set_real_num_tx_queues
```
```
In net/core/dev_addr_lists.c (ffff800010bdf6f4)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:dev_mc_flush
  - net/core/dev_addr_lists.c:__dev_mc_del
  - net/core/dev_addr_lists.c:__dev_mc_add
  - net/core/dev_addr_lists.c:dev_mc_add_excl
  - net/core/dev_addr_lists.c:dev_uc_flush
  - net/core/dev_addr_lists.c:dev_uc_del
  - net/core/dev_addr_lists.c:dev_uc_add
  - net/core/dev_addr_lists.c:dev_uc_add_excl
```
```
In net/core/neighbour.c (ffff800010be6574)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/core/rtnetlink.c (ffff800010beec60)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_fdb_dump
```
```
In net/core/sock_reuseport.c (ffff800010c052e4)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_attach_prog
  - net/core/sock_reuseport.c:reuseport_detach_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_alloc
  - net/core/sock_reuseport.c:reuseport_alloc
```
```
In net/core/page_pool.c (ffff800010c0cb38)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
```
```
In net/core/net-procfs.c (ffff800010c0e060)
Location: include/linux/spinlock.h:381
Inline: True
```
```
In net/core/skmsg.c (ffff800010c0fc04)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_link_pop
```
```
In net/core/sock_map.c (ffff800010c20ed8)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_unref
```
```
In net/core/devlink.c (ffff800010c2ae20)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_port_type_set
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
```
```
In net/sched/sch_generic.c (ffff800010c3a1f4)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_graft_qdisc
```
```
In net/sched/sch_mq.c (ffff800010c3b194)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump
```
```
In net/sched/sch_api.c (ffff800010c3d0f8)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/sched/sch_api.c:tcf_node_bind
  - net/sched/sch_api.c:qdisc_class_hash_grow
```
```
In net/ipv4/route.c (ffff800010c5a988)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_flush_dev
  - net/ipv4/route.c:rt_add_uncached_list
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/inetpeer.c (ffff800010c5dab8)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/inet_hashtables.c (ffff800010c6b5e8)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_unhash
```
```
In net/ipv4/inet_connection_sock.c (ffff800010c6da6c)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp.c (ffff800010c71690)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_ioctl
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8b2fc)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_seq_stop
  - net/ipv4/tcp_ipv4.c:established_get_next
```
```
In net/ipv4/tcp_metrics.c (ffff800010c92654)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_flush_all
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/raw.c (ffff800010c97364)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_ioctl
```
```
In net/ipv4/udp.c (ffff800010c9912c)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_seq_stop
  - net/ipv4/udp.c:udp_get_next
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/af_inet.c (ffff800010cabcc0)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_register_protosw
```
```
In net/ipv4/igmp.c (ffff800010cae2c0)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_mcf_seq_stop
  - net/ipv4/igmp.c:igmp_mcf_seq_next
  - net/ipv4/igmp.c:igmp_mcf_seq_start
  - net/ipv4/igmp.c:ip_mc_clear_src
  - net/ipv4/igmp.c:ip_mc_add_src
  - net/ipv4/igmp.c:ip_mc_del_src
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:igmpv3_clear_delrec
  - net/ipv4/igmp.c:igmpv3_clear_delrec
  - net/ipv4/igmp.c:igmpv3_del_delrec
  - net/ipv4/igmp.c:igmpv3_del_delrec
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:igmp_stop_timer
```
```
In net/ipv4/fib_semantics.c (ffff800010cb8a4c)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_release_info
```
```
In net/ipv4/inet_fragment.c (ffff800010cbeb44)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frags_free_cb
```
```
In net/ipv4/sysctl_net_ipv4.c (ffff800010cc74cc)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
```
In net/ipv4/ipmr.c (ffff800010ccc1cc)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:mr_mfc_seq_stop
```
```
In net/ipv4/ipmr_base.c (ffff800010cd1040)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_table_dump
  - net/ipv4/ipmr_base.c:mr_table_dump
  - net/ipv4/ipmr_base.c:mr_mfc_seq_next
```
```
In net/ipv4/tcp_bpf.c (ffff800010cd4838)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_init
```
```
In net/ipv4/cipso_ipv4.c (ffff800010cd5490)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_invalidate
```
```
In net/xfrm/xfrm_policy.c (ffff800010cdd618)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:__xfrm_sk_clone_policy
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_policy_walk
  - net/xfrm/xfrm_policy.c:xfrm_policy_flush
  - net/xfrm/xfrm_policy.c:xfrm_policy_flush
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffff800010ce50a0)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_unregister_afinfo
  - net/xfrm/xfrm_state.c:xfrm_state_register_afinfo
  - net/xfrm/xfrm_state.c:xfrm_unregister_km
  - net/xfrm/xfrm_state.c:xfrm_register_km
  - net/xfrm/xfrm_state.c:xfrm_state_walk
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_find_acq_byseq
  - net/xfrm/xfrm_state.c:xfrm_find_acq
  - net/xfrm/xfrm_state.c:xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_sad_getinfo
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_delete
  - net/xfrm/xfrm_state.c:xfrm_state_gc_task
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_input.c (ffff800010ce9e30)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo
  - net/xfrm/xfrm_input.c:xfrm_input_register_afinfo
```
```
In net/xfrm/xfrm_output.c (ffff800010cec2bc)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/af_inet6.c (ffff800010cf64e0)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_register_protosw
```
```
In net/ipv6/addrconf.c (ffff800010d0ab84)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_start
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:ipv6_generate_stable_address
  - net/ipv6/addrconf.c:add_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/route.c (ffff800010d11ab4)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_del_rt
  - net/ipv6/route.c:fib6_table_lookup
  - net/ipv6/route.c:fib6_nh_remove_exception
  - net/ipv6/route.c:fib6_nh_flush_exceptions
  - net/ipv6/route.c:rt6_insert_exception
  - net/ipv6/route.c:rt6_insert_exception
  - net/ipv6/route.c:__ip6_ins_rt
  - net/ipv6/route.c:rt6_uncached_list_add
```
```
In net/ipv6/ip6_fib.c (ffff800010d19e1c)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:__fib6_clean_all
  - net/ipv6/ip6_fib.c:fib6_update_sernum_stub
  - net/ipv6/ip6_fib.c:fib6_tables_dump
```
```
In net/ipv6/raw.c (ffff800010d29324)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_ioctl
```
```
In net/ipv6/mcast.c (ffff800010d2e740)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mcf_seq_stop
  - net/ipv6/mcast.c:igmp6_mcf_seq_next
  - net/ipv6/mcast.c:igmp6_mcf_seq_start
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:ip6_mc_del_src
  - net/ipv6/mcast.c:ip6_mc_del_src
  - net/ipv6/mcast.c:mld_send_report
  - net/ipv6/mcast.c:mld_send_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:mld_del_delrec
  - net/ipv6/mcast.c:mld_del_delrec
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/mcast.c:igmp6_group_added
```
```
In net/ipv6/ip6_flowlabel.c (ffff800010d3ef78)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:fl6_renew
  - net/ipv6/ip6_flowlabel.c:fl6_free_socklist
  - net/ipv6/ip6_flowlabel.c:fl6_free_socklist
  - net/ipv6/ip6_flowlabel.c:fl_release
```
```
In net/ipv6/ip6mr.c (ffff800010d44dec)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:mr_mfc_seq_stop
```
```
In net/ipv6/calipso.c (ffff800010d4e8fc)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_cache_invalidate
```
```
In net/packet/af_packet.c (ffff800010d5bdbc)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_ioctl
  - net/packet/af_packet.c:packet_getsockopt
```
```
In net/dcb/dcbnl.c (ffff800010d6fc80)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_ieee_getapp_default_prio_mask
  - net/dcb/dcbnl.c:dcb_ieee_getapp_dscp_prio_mask_map
  - net/dcb/dcbnl.c:dcb_ieee_getapp_prio_dscp_mask_map
  - net/dcb/dcbnl.c:dcb_ieee_delapp
  - net/dcb/dcbnl.c:dcb_ieee_setapp
  - net/dcb/dcbnl.c:dcb_ieee_getapp_mask
  - net/dcb/dcbnl.c:dcb_setapp
  - net/dcb/dcbnl.c:dcb_getapp
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
```
```
In net/switchdev/switchdev.c (ffff800010d740dc)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_deferred_process
```
```
In net/xdp/xsk.c (ffff800010d7f138)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xsk.c:xsk_generic_rcv
  - net/xdp/xsk.c:xsk_generic_rcv
```
```
In lib/xarray.c (ffff800010d9b334)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - lib/xarray.c:__xas_nomem
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c0412a48)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_idr_remove
  - kernel/cgroup/cgroup.c:cgroup_idr_replace
```
```
In kernel/bpf/core.c (c0491a4c)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
```
```
In kernel/bpf/syscall.c (c0497550)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_obj_get_next_id
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_map_inc_not_zero
  - kernel/bpf/syscall.c:map_create
```
```
In kernel/bpf/local_storage.c (c04b08c0)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_unlink
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_link
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_release
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_assign
  - kernel/bpf/local_storage.c:cgroup_storage_get_next_key
  - kernel/bpf/local_storage.c:cgroup_storage_get_next_key
  - kernel/bpf/local_storage.c:cgroup_storage_lookup
  - kernel/bpf/local_storage.c:cgroup_storage_lookup
```
```
In kernel/bpf/btf.c (c04b5c70)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
```
```
In kernel/bpf/xskmap.c (c04b8fc8)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - kernel/bpf/xskmap.c:xsk_map_try_sock_delete
  - kernel/bpf/xskmap.c:xsk_map_delete_elem
  - kernel/bpf/xskmap.c:xsk_map_update_elem
  - kernel/bpf/xskmap.c:xsk_map_update_elem
  - kernel/bpf/xskmap.c:xsk_map_update_elem
  - kernel/bpf/xskmap.c:xsk_map_sock_delete
```
```
In kernel/bpf/reuseport_array.c (c04bfb74)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem
  - kernel/bpf/reuseport_array.c:reuseport_array_delete_elem
```
```
In kernel/padata.c (c04d7b4c)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - kernel/padata.c:padata_reorder
```
```
In mm/page-writeback.c (c04e62a8)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - mm/page-writeback.c:bdi_set_max_ratio
  - mm/page-writeback.c:bdi_set_min_ratio
```
```
In mm/backing-dev.c (c0503be4)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:bdi_register_va
  - mm/backing-dev.c:bdi_get_by_id
  - mm/backing-dev.c:wb_wakeup_delayed
```
```
In fs/fs-writeback.c (c05a7598)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_queue_work
  - fs/fs-writeback.c:wb_wakeup
```
```
In security/selinux/netif.c (c070cd38)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_netdev_notifier_handler
  - security/selinux/netif.c:sel_netif_flush
  - security/selinux/netif.c:sel_netif_sid
```
```
In security/selinux/netnode.c (c070d39c)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_flush
  - security/selinux/netnode.c:sel_netnode_sid
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (c070d654)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_flush
  - security/selinux/netport.c:sel_netport_sid
  - security/selinux/netport.c:sel_netport_sid
```
```
In block/genhd.c (c07a546c)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - block/genhd.c:get_gendisk
```
```
In block/blk-cgroup.c (c07b8f94)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - block/blk-cgroup.c:__blkcg_punt_bio_submit
  - block/blk-cgroup.c:blkg_async_bio_workfn
```
```
In drivers/dma/dmaengine.c (c091d8e0)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_run_dependencies
```
```
In drivers/dma/mv_xor.c (c09249a4)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - drivers/dma/mv_xor.c:mv_xor_status
  - drivers/dma/mv_xor.c:mv_xor_free_chan_resources
  - drivers/dma/mv_xor.c:mv_xor_prep_dma_xor
  - drivers/dma/mv_xor.c:mv_xor_prep_dma_xor
  - drivers/dma/mv_xor.c:mv_xor_alloc_chan_resources
  - drivers/dma/mv_xor.c:mv_xor_tx_submit
```
```
In drivers/connector/cn_queue.c (c09cc99c)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_free_dev
  - drivers/connector/cn_queue.c:cn_queue_del_callback
  - drivers/connector/cn_queue.c:cn_queue_add_callback
```
```
In drivers/connector/connector.c (c09ccadc)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_proc_show
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/net/tun.c (c0ac2398)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_set_ebpf
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_flow_update
  - drivers/net/tun.c:tun_flow_flush
```
```
In drivers/net/ppp/ppp_generic.c (c0adc078)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_disconnect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_disconnect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_ccp_closed
  - drivers/net/ppp/ppp_generic.c:ppp_ccp_closed
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_input_error
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_dev_uninit
  - drivers/net/ppp/ppp_generic.c:ppp_dev_uninit
  - drivers/net/ppp/ppp_generic.c:ppp_get_stats64
  - drivers/net/ppp/ppp_generic.c:ppp_get_stats64
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_poll
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - drivers/net/ppp/ppp_generic.c:ppp_read
```
```
In net/core/sock.c (c0ccb958)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/sock.c:release_sock
  - net/core/sock.c:__sk_flush_backlog
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__lock_sock
```
```
In net/core/request_sock.c (c0ccd7b4)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/core/datagram.c (c0cd7e58)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/datagram.c:__sk_queue_drop_skb
```
```
In net/core/gen_stats.c (c0cdaf58)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/gen_stats.c:gnet_stats_finish_copy
  - net/core/gen_stats.c:gnet_stats_finish_copy
  - net/core/gen_stats.c:gnet_stats_copy_queue
  - net/core/gen_stats.c:gnet_stats_copy_rate_est
  - net/core/gen_stats.c:gnet_stats_copy_rate_est
  - net/core/gen_stats.c:___gnet_stats_copy_basic
```
```
In net/core/gen_estimator.c (c0cdb458)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/net_namespace.c (c0cdc944)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:peernet2id
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/dev.c (c0cf072c)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/dev.c:dev_set_rx_mode
  - net/core/dev.c:netif_set_real_num_tx_queues
```
```
In net/core/dev_addr_lists.c (c0cf982c)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:dev_mc_flush
  - net/core/dev_addr_lists.c:__dev_mc_del
  - net/core/dev_addr_lists.c:__dev_mc_add
  - net/core/dev_addr_lists.c:dev_mc_add_excl
  - net/core/dev_addr_lists.c:dev_uc_flush
  - net/core/dev_addr_lists.c:dev_uc_del
  - net/core/dev_addr_lists.c:dev_uc_add
  - net/core/dev_addr_lists.c:dev_uc_add_excl
```
```
In net/core/neighbour.c (c0cfef00)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/core/rtnetlink.c (c0d070c4)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_fdb_dump
```
```
In net/core/sock_reuseport.c (c0d1e5c8)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_attach_prog
  - net/core/sock_reuseport.c:reuseport_detach_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_alloc
  - net/core/sock_reuseport.c:reuseport_alloc
```
```
In net/core/page_pool.c (c0d25250)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
```
```
In net/core/net-procfs.c (c0d25f1c)
Location: include/linux/spinlock.h:381
Inline: True
```
```
In net/core/skmsg.c (c0d27a7c)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_link_pop
```
```
In net/core/sock_map.c (c0d38790)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_unref
```
```
In net/core/devlink.c (c0d42230)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_port_type_set
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
```
```
In net/sched/sch_generic.c (c0d4c410)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_graft_qdisc
```
```
In net/sched/sch_mq.c (c0d4cb60)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump
```
```
In net/sched/sch_api.c (c0d4ebe0)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/sched/sch_api.c:tcf_node_bind
  - net/sched/sch_api.c:qdisc_class_hash_grow
```
```
In net/ipv4/route.c (c0d69ed4)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_flush_dev
  - net/ipv4/route.c:ipv4_dst_destroy
  - net/ipv4/route.c:rt_add_uncached_list
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/inetpeer.c (c0d6ce78)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/inet_hashtables.c (c0d7a4a8)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_unhash
```
```
In net/ipv4/inet_connection_sock.c (c0d7bfc8)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp.c (c0d7f480)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_ioctl
```
```
In net/ipv4/tcp_ipv4.c (c0d98e54)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_seq_stop
  - net/ipv4/tcp_ipv4.c:established_get_next
  - net/ipv4/tcp_ipv4.c:established_get_first
```
```
In net/ipv4/tcp_metrics.c (c0da0770)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_flush_all
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/raw.c (c0da4d7c)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_ioctl
```
```
In net/ipv4/udp.c (c0da8028)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_seq_stop
  - net/ipv4/udp.c:udp_get_next
  - net/ipv4/udp.c:udp_get_first
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/af_inet.c (c0db6448)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_register_protosw
```
```
In net/ipv4/igmp.c (c0db9668)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_mcf_seq_stop
  - net/ipv4/igmp.c:igmp_mcf_seq_next
  - net/ipv4/igmp.c:igmp_mcf_seq_start
  - net/ipv4/igmp.c:igmp_mcf_get_next
  - net/ipv4/igmp.c:ip_mc_clear_src
  - net/ipv4/igmp.c:ip_mc_add_src
  - net/ipv4/igmp.c:ip_mc_del_src
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:igmpv3_clear_delrec
  - net/ipv4/igmp.c:igmpv3_clear_delrec
  - net/ipv4/igmp.c:igmpv3_del_delrec
  - net/ipv4/igmp.c:igmpv3_del_delrec
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:igmp_stop_timer
```
```
In net/ipv4/fib_semantics.c (c0dc3878)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_release_info
```
```
In net/ipv4/inet_fragment.c (c0dca230)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frags_free_cb
```
```
In net/ipv4/sysctl_net_ipv4.c (c0dd2360)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
```
In net/ipv4/ipmr.c (c0dd7e88)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:mr_mfc_seq_stop
```
```
In net/ipv4/ipmr_base.c (c0ddaa7c)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_table_dump
  - net/ipv4/ipmr_base.c:mr_table_dump
  - net/ipv4/ipmr_base.c:mr_mfc_seq_next
```
```
In net/ipv4/tcp_bpf.c (c0dde948)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_init
```
```
In net/ipv4/cipso_ipv4.c (c0ddf450)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_invalidate
```
```
In net/xfrm/xfrm_policy.c (c0de74e8)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:__xfrm_sk_clone_policy
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_policy_walk
  - net/xfrm/xfrm_policy.c:xfrm_policy_flush
  - net/xfrm/xfrm_policy.c:xfrm_policy_flush
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (c0deba84)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_unregister_afinfo
  - net/xfrm/xfrm_state.c:xfrm_state_register_afinfo
  - net/xfrm/xfrm_state.c:xfrm_unregister_km
  - net/xfrm/xfrm_state.c:xfrm_register_km
  - net/xfrm/xfrm_state.c:xfrm_state_walk
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_find_acq_byseq
  - net/xfrm/xfrm_state.c:xfrm_find_acq
  - net/xfrm/xfrm_state.c:xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_state_lookup_byspi
  - net/xfrm/xfrm_state.c:xfrm_state_lookup_byspi
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_sad_getinfo
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_delete
  - net/xfrm/xfrm_state.c:xfrm_state_gc_task
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_input.c (c0df1d68)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo
  - net/xfrm/xfrm_input.c:xfrm_input_register_afinfo
```
```
In net/xfrm/xfrm_output.c (c0df4010)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/af_inet6.c (c0dfc618)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_register_protosw
```
```
In net/ipv6/addrconf.c (c0e1122c)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_start
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:ipv6_generate_stable_address
  - net/ipv6/addrconf.c:add_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/route.c (c0e14f00)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_del_rt
  - net/ipv6/route.c:fib6_table_lookup
  - net/ipv6/route.c:fib6_nh_remove_exception
  - net/ipv6/route.c:fib6_nh_flush_exceptions
  - net/ipv6/route.c:rt6_insert_exception
  - net/ipv6/route.c:rt6_insert_exception
  - net/ipv6/route.c:__ip6_ins_rt
  - net/ipv6/route.c:rt6_uncached_list_add
```
```
In net/ipv6/ip6_fib.c (c0e1ed8c)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:__fib6_clean_all
  - net/ipv6/ip6_fib.c:fib6_update_sernum_stub
  - net/ipv6/ip6_fib.c:fib6_dump_table
  - net/ipv6/ip6_fib.c:fib6_dump_table
  - net/ipv6/ip6_fib.c:fib6_tables_dump
```
```
In net/ipv6/raw.c (c0e2cce8)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_ioctl
```
```
In net/ipv6/mcast.c (c0e314c0)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mcf_seq_stop
  - net/ipv6/mcast.c:igmp6_mcf_seq_next
  - net/ipv6/mcast.c:igmp6_mcf_seq_start
  - net/ipv6/mcast.c:igmp6_mcf_get_next
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:ip6_mc_del_src
  - net/ipv6/mcast.c:ip6_mc_del_src
  - net/ipv6/mcast.c:mld_send_report
  - net/ipv6/mcast.c:mld_send_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:mld_del_delrec
  - net/ipv6/mcast.c:mld_del_delrec
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/mcast.c:igmp6_group_added
```
```
In net/ipv6/ip6_flowlabel.c (c0e42078)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:fl6_renew
  - net/ipv6/ip6_flowlabel.c:fl6_free_socklist
  - net/ipv6/ip6_flowlabel.c:fl6_free_socklist
  - net/ipv6/ip6_flowlabel.c:fl_release
```
```
In net/ipv6/ip6mr.c (c0e47290)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:mr_mfc_seq_stop
```
```
In net/ipv6/calipso.c (c0e4f224)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_cache_invalidate
```
```
In net/packet/af_packet.c (c0e5bec4)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_ioctl
  - net/packet/af_packet.c:packet_getsockopt
```
```
In net/dcb/dcbnl.c (c0e6bb54)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_ieee_getapp_default_prio_mask
  - net/dcb/dcbnl.c:dcb_ieee_getapp_dscp_prio_mask_map
  - net/dcb/dcbnl.c:dcb_ieee_getapp_prio_dscp_mask_map
  - net/dcb/dcbnl.c:dcb_ieee_delapp
  - net/dcb/dcbnl.c:dcb_ieee_setapp
  - net/dcb/dcbnl.c:dcb_ieee_getapp_mask
  - net/dcb/dcbnl.c:dcb_setapp
  - net/dcb/dcbnl.c:dcb_getapp
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
```
```
In net/switchdev/switchdev.c (c0e702a8)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_deferred_enqueue
  - net/switchdev/switchdev.c:switchdev_deferred_process
```
```
In net/xdp/xsk.c (c0e792c8)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xsk.c:xsk_generic_rcv
  - net/xdp/xsk.c:xsk_generic_rcv
```
```
In lib/xarray.c (c0e96c1c)
Location: include/linux/spinlock.h:381
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c0000000002391b0)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_idr_remove
  - kernel/cgroup/cgroup.c:cgroup_idr_replace
```
```
In kernel/bpf/core.c (c0000000003030e8)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
```
```
In kernel/bpf/syscall.c (c00000000030a0e0)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_obj_get_next_id
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_map_inc_not_zero
  - kernel/bpf/syscall.c:map_create
```
```
In kernel/bpf/local_storage.c (c000000000329768)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_unlink
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_link
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_release
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_assign
  - kernel/bpf/local_storage.c:cgroup_storage_get_next_key
  - kernel/bpf/local_storage.c:cgroup_storage_get_next_key
  - kernel/bpf/local_storage.c:cgroup_storage_lookup
  - kernel/bpf/local_storage.c:cgroup_storage_lookup
```
```
In kernel/bpf/btf.c (c0000000003304e4)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
```
```
In kernel/bpf/xskmap.c (c000000000334d0c)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - kernel/bpf/xskmap.c:xsk_map_try_sock_delete
  - kernel/bpf/xskmap.c:xsk_map_delete_elem
  - kernel/bpf/xskmap.c:xsk_map_update_elem
  - kernel/bpf/xskmap.c:xsk_map_update_elem
  - kernel/bpf/xskmap.c:xsk_map_update_elem
  - kernel/bpf/xskmap.c:xsk_map_sock_delete
```
```
In kernel/bpf/reuseport_array.c (c00000000033d47c)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem
  - kernel/bpf/reuseport_array.c:reuseport_array_delete_elem
```
```
In kernel/padata.c (c00000000035c8c0)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - kernel/padata.c:padata_reorder
```
```
In mm/page-writeback.c (c000000000372070)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - mm/page-writeback.c:bdi_set_max_ratio
  - mm/page-writeback.c:bdi_set_min_ratio
```
```
In mm/backing-dev.c (c00000000039e584)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:bdi_get_by_id
  - mm/backing-dev.c:wb_shutdown
  - mm/backing-dev.c:wb_shutdown
  - mm/backing-dev.c:wb_wakeup_delayed
```
```
In fs/fs-writeback.c (c0000000004ccd24)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_queue_work
  - fs/fs-writeback.c:wb_wakeup
```
```
In security/selinux/netif.c (c0000000006b5ea0)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_netdev_notifier_handler
  - security/selinux/netif.c:sel_netif_flush
  - security/selinux/netif.c:sel_netif_sid
```
```
In security/selinux/netnode.c (c0000000006b67c0)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_flush
  - security/selinux/netnode.c:sel_netnode_sid
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (c0000000006b6ba0)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_flush
  - security/selinux/netport.c:sel_netport_sid
  - security/selinux/netport.c:sel_netport_sid
```
```
In block/genhd.c (c0000000007934a8)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - block/genhd.c:get_gendisk
```
```
In block/blk-cgroup.c (c0000000007abc94)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - block/blk-cgroup.c:__blkcg_punt_bio_submit
  - block/blk-cgroup.c:blkg_async_bio_workfn
```
```
In drivers/connector/cn_queue.c (c000000000970f64)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_free_dev
  - drivers/connector/cn_queue.c:cn_queue_del_callback
  - drivers/connector/cn_queue.c:cn_queue_add_callback
```
```
In drivers/connector/connector.c (c00000000097114c)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_proc_show
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/net/tun.c (c000000000a9da84)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_set_ebpf
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_flow_update
  - drivers/net/tun.c:tun_flow_flush
```
```
In drivers/net/ppp/ppp_generic.c (c000000000aa6264)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_disconnect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_disconnect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_ccp_closed
  - drivers/net/ppp/ppp_generic.c:ppp_ccp_closed
  - drivers/net/ppp/ppp_generic.c:ppp_set_compress
  - drivers/net/ppp/ppp_generic.c:ppp_set_compress
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_input_error
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_dev_uninit
  - drivers/net/ppp/ppp_generic.c:ppp_dev_uninit
  - drivers/net/ppp/ppp_generic.c:ppp_get_stats64
  - drivers/net/ppp/ppp_generic.c:ppp_get_stats64
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_poll
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - drivers/net/ppp/ppp_generic.c:ppp_read
```
```
In net/core/sock.c (c000000000c8387c)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/sock.c:release_sock
  - net/core/sock.c:__sk_flush_backlog
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__lock_sock
```
```
In net/core/request_sock.c (c000000000c85de0)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/core/datagram.c (c000000000c94578)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/datagram.c:__sk_queue_drop_skb
  - net/core/datagram.c:__skb_free_datagram_locked
```
```
In net/core/gen_stats.c (c000000000c987ac)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/gen_stats.c:gnet_stats_finish_copy
  - net/core/gen_stats.c:gnet_stats_finish_copy
  - net/core/gen_stats.c:gnet_stats_copy_queue
  - net/core/gen_stats.c:gnet_stats_copy_rate_est
  - net/core/gen_stats.c:___gnet_stats_copy_basic
```
```
In net/core/gen_estimator.c (c000000000c98d84)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/net_namespace.c (c000000000c9a814)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:peernet2id
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/dev.c (c000000000cb51c0)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/dev.c:dev_set_rx_mode
  - net/core/dev.c:netif_set_real_num_tx_queues
```
```
In net/core/dev_addr_lists.c (c000000000cbf610)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:dev_mc_flush
  - net/core/dev_addr_lists.c:__dev_mc_del
  - net/core/dev_addr_lists.c:__dev_mc_add
  - net/core/dev_addr_lists.c:dev_mc_add_excl
  - net/core/dev_addr_lists.c:dev_uc_flush
  - net/core/dev_addr_lists.c:dev_uc_del
  - net/core/dev_addr_lists.c:dev_uc_add
  - net/core/dev_addr_lists.c:dev_uc_add_excl
```
```
In net/core/neighbour.c (c000000000cc80c0)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/core/rtnetlink.c (c000000000cd29a0)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_fdb_dump
```
```
In net/core/sock_reuseport.c (c000000000cef49c)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_attach_prog
  - net/core/sock_reuseport.c:reuseport_detach_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_alloc
  - net/core/sock_reuseport.c:reuseport_alloc
```
```
In net/core/page_pool.c (c000000000cf8468)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
```
```
In net/core/net-procfs.c (c000000000cf9684)
Location: include/linux/spinlock.h:381
Inline: True
```
```
In net/core/skmsg.c (c000000000cfbde4)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_link_pop
```
```
In net/core/sock_map.c (c000000000d13040)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_unref
```
```
In net/core/devlink.c (c000000000d203b0)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_port_type_set
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
```
```
In net/sched/sch_generic.c (c000000000d33238)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_graft_qdisc
```
```
In net/sched/sch_mq.c (c000000000d33bc4)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump
```
```
In net/sched/sch_api.c (c000000000d380e0)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_grow
```
```
In net/ipv4/route.c (c000000000d5c5a4)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_flush_dev
  - net/ipv4/route.c:ipv4_dst_destroy
  - net/ipv4/route.c:rt_add_uncached_list
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/inetpeer.c (c000000000d5ffc4)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/inet_hashtables.c (c000000000d70adc)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_unhash
```
```
In net/ipv4/inet_connection_sock.c (c000000000d72eb0)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp.c (c000000000d77340)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_ioctl
```
```
In net/ipv4/tcp_ipv4.c (c000000000d9754c)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_seq_stop
  - net/ipv4/tcp_ipv4.c:established_get_next
  - net/ipv4/tcp_ipv4.c:established_get_first
```
```
In net/ipv4/tcp_metrics.c (c000000000da1f20)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_flush_all
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/raw.c (c000000000da88bc)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_ioctl
```
```
In net/ipv4/udp.c (c000000000dabd00)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_seq_stop
  - net/ipv4/udp.c:udp_get_next
  - net/ipv4/udp.c:udp_get_first
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:skb_consume_udp
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/af_inet.c (c000000000dbf2c8)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_register_protosw
```
```
In net/ipv4/igmp.c (c000000000dc30c8)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_mcf_seq_stop
  - net/ipv4/igmp.c:igmp_mcf_seq_next
  - net/ipv4/igmp.c:igmp_mcf_seq_start
  - net/ipv4/igmp.c:ip_mc_clear_src
  - net/ipv4/igmp.c:ip_mc_add_src
  - net/ipv4/igmp.c:ip_mc_del_src
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:igmpv3_clear_delrec
  - net/ipv4/igmp.c:igmpv3_clear_delrec
  - net/ipv4/igmp.c:igmpv3_del_delrec
  - net/ipv4/igmp.c:igmpv3_del_delrec
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:igmp_stop_timer
```
```
In net/ipv4/fib_semantics.c (c000000000dd0e24)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_release_info
```
```
In net/ipv4/inet_fragment.c (c000000000dd9088)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frags_free_cb
```
```
In net/ipv4/sysctl_net_ipv4.c (c000000000de3980)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
```
In net/ipv4/ipmr.c (c000000000deb2bc)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:mr_mfc_seq_stop
```
```
In net/ipv4/ipmr_base.c (c000000000dee880)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_table_dump
  - net/ipv4/ipmr_base.c:mr_table_dump
  - net/ipv4/ipmr_base.c:mr_mfc_seq_next
```
```
In net/ipv4/tcp_bpf.c (c000000000df3b9c)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_init
```
```
In net/ipv4/cipso_ipv4.c (c000000000df4b3c)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_invalidate
```
```
In net/xfrm/xfrm_policy.c (c000000000dfdae0)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:__xfrm_sk_clone_policy
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_policy_walk
  - net/xfrm/xfrm_policy.c:xfrm_policy_flush
  - net/xfrm/xfrm_policy.c:xfrm_policy_flush
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:xfrm_bydst_resize
```
```
In net/xfrm/xfrm_state.c (c000000000e0555c)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_unregister_afinfo
  - net/xfrm/xfrm_state.c:xfrm_state_register_afinfo
  - net/xfrm/xfrm_state.c:xfrm_unregister_km
  - net/xfrm/xfrm_state.c:xfrm_register_km
  - net/xfrm/xfrm_state.c:xfrm_state_walk
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_find_acq_byseq
  - net/xfrm/xfrm_state.c:xfrm_find_acq
  - net/xfrm/xfrm_state.c:xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_state_lookup_byspi
  - net/xfrm/xfrm_state.c:xfrm_state_lookup_byspi
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_sad_getinfo
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_delete
  - net/xfrm/xfrm_state.c:xfrm_state_gc_task
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_input.c (c000000000e0d64c)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo
  - net/xfrm/xfrm_input.c:xfrm_input_register_afinfo
```
```
In net/xfrm/xfrm_output.c (c000000000e10128)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/af_inet6.c (c000000000e1c0d4)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_register_protosw
```
```
In net/ipv6/addrconf.c (c000000000e358a8)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_start
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:ipv6_generate_stable_address
  - net/ipv6/addrconf.c:add_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/route.c (c000000000e3b624)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_del_rt
  - net/ipv6/route.c:fib6_table_lookup
  - net/ipv6/route.c:fib6_nh_remove_exception
  - net/ipv6/route.c:fib6_nh_flush_exceptions
  - net/ipv6/route.c:rt6_insert_exception
  - net/ipv6/route.c:rt6_insert_exception
  - net/ipv6/route.c:__ip6_ins_rt
  - net/ipv6/route.c:rt6_uncached_list_add
```
```
In net/ipv6/ip6_fib.c (c000000000e46d9c)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:__fib6_clean_all
  - net/ipv6/ip6_fib.c:fib6_update_sernum_stub
  - net/ipv6/ip6_fib.c:fib6_tables_dump
```
```
In net/ipv6/raw.c (c000000000e5a4ec)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_ioctl
```
```
In net/ipv6/mcast.c (c000000000e5f1e0)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mcf_seq_stop
  - net/ipv6/mcast.c:igmp6_mcf_seq_next
  - net/ipv6/mcast.c:igmp6_mcf_seq_start
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:ip6_mc_del_src
  - net/ipv6/mcast.c:ip6_mc_del_src
  - net/ipv6/mcast.c:mld_send_report
  - net/ipv6/mcast.c:mld_send_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:mld_del_delrec
  - net/ipv6/mcast.c:mld_del_delrec
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/mcast.c:igmp6_group_added
```
```
In net/ipv6/ip6_flowlabel.c (c000000000e73638)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:fl6_renew
  - net/ipv6/ip6_flowlabel.c:fl6_free_socklist
  - net/ipv6/ip6_flowlabel.c:fl6_free_socklist
  - net/ipv6/ip6_flowlabel.c:fl_release
```
```
In net/ipv6/ip6mr.c (c000000000e79430)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:mr_mfc_seq_stop
```
```
In net/ipv6/calipso.c (c000000000e851d8)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_cache_invalidate
```
```
In net/packet/af_packet.c (c000000000e97780)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_ioctl
  - net/packet/af_packet.c:packet_getsockopt
```
```
In net/dcb/dcbnl.c (c000000000eac1d8)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_ieee_getapp_default_prio_mask
  - net/dcb/dcbnl.c:dcb_ieee_getapp_dscp_prio_mask_map
  - net/dcb/dcbnl.c:dcb_ieee_getapp_prio_dscp_mask_map
  - net/dcb/dcbnl.c:dcb_ieee_delapp
  - net/dcb/dcbnl.c:dcb_ieee_setapp
  - net/dcb/dcbnl.c:dcb_ieee_getapp_mask
  - net/dcb/dcbnl.c:dcb_setapp
  - net/dcb/dcbnl.c:dcb_getapp
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
```
```
In net/switchdev/switchdev.c (c000000000eb25bc)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_deferred_process
```
```
In net/xdp/xsk.c (c000000000ebf38c)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xsk.c:xsk_generic_rcv
  - net/xdp/xsk.c:xsk_generic_rcv
```
```
In lib/xarray.c (c000000000eded10)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - lib/xarray.c:__xas_nomem
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffe000149828)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_idr_remove
  - kernel/cgroup/cgroup.c:cgroup_idr_replace
```
```
In kernel/bpf/core.c (ffffffe00019c77e)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
```
```
In kernel/bpf/syscall.c (ffffffe0001a0e08)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_obj_get_next_id
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_map_inc_not_zero
  - kernel/bpf/syscall.c:map_create
```
```
In kernel/bpf/local_storage.c (ffffffe0001b615e)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_unlink
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_link
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_release
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_assign
  - kernel/bpf/local_storage.c:cgroup_storage_get_next_key
  - kernel/bpf/local_storage.c:cgroup_storage_get_next_key
  - kernel/bpf/local_storage.c:cgroup_storage_lookup
  - kernel/bpf/local_storage.c:cgroup_storage_lookup
```
```
In kernel/bpf/btf.c (ffffffe0001baaba)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
```
```
In kernel/bpf/xskmap.c (ffffffe0001bda00)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - kernel/bpf/xskmap.c:xsk_map_try_sock_delete
  - kernel/bpf/xskmap.c:xsk_map_delete_elem
  - kernel/bpf/xskmap.c:xsk_map_update_elem
  - kernel/bpf/xskmap.c:xsk_map_update_elem
  - kernel/bpf/xskmap.c:xsk_map_update_elem
  - kernel/bpf/xskmap.c:xsk_map_sock_delete
```
```
In kernel/bpf/reuseport_array.c (ffffffe0001c306c)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem
  - kernel/bpf/reuseport_array.c:reuseport_array_delete_elem
```
```
In kernel/padata.c (ffffffe0001d3328)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - kernel/padata.c:padata_reorder
```
```
In mm/page-writeback.c (ffffffe0001dd33a)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - mm/page-writeback.c:bdi_set_max_ratio
  - mm/page-writeback.c:bdi_set_min_ratio
```
```
In mm/backing-dev.c (ffffffe0001f6ade)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:bdi_get_by_id
  - mm/backing-dev.c:wb_wakeup_delayed
```
```
In fs/fs-writeback.c (ffffffe0002890b8)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_queue_work
  - fs/fs-writeback.c:wb_wakeup
```
```
In security/selinux/netif.c (ffffffe0003af756)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_netdev_notifier_handler
  - security/selinux/netif.c:sel_netif_flush
  - security/selinux/netif.c:sel_netif_sid
```
```
In security/selinux/netnode.c (ffffffe0003afd12)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_flush
  - security/selinux/netnode.c:sel_netnode_sid
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (ffffffe0003aff6c)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_flush
  - security/selinux/netport.c:sel_netport_sid
  - security/selinux/netport.c:sel_netport_sid
```
```
In block/genhd.c (ffffffe000436a5c)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - block/genhd.c:get_gendisk
```
```
In block/blk-cgroup.c (ffffffe000446c2e)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - block/blk-cgroup.c:__blkcg_punt_bio_submit
  - block/blk-cgroup.c:blkg_async_bio_workfn
```
```
In drivers/connector/cn_queue.c (ffffffe000573f22)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_free_dev
  - drivers/connector/cn_queue.c:cn_queue_del_callback
  - drivers/connector/cn_queue.c:cn_queue_add_callback
```
```
In drivers/connector/connector.c (ffffffe000574070)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_proc_show
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/net/tun.c (ffffffe0006260e0)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_set_ebpf
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_flow_update
  - drivers/net/tun.c:tun_flow_flush
```
```
In drivers/net/ppp/ppp_generic.c (ffffffe00062be1c)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_disconnect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_disconnect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_ccp_closed
  - drivers/net/ppp/ppp_generic.c:ppp_ccp_closed
  - drivers/net/ppp/ppp_generic.c:ppp_set_compress
  - drivers/net/ppp/ppp_generic.c:ppp_set_compress
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_input_error
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_dev_uninit
  - drivers/net/ppp/ppp_generic.c:ppp_dev_uninit
  - drivers/net/ppp/ppp_generic.c:ppp_get_stats64
  - drivers/net/ppp/ppp_generic.c:ppp_get_stats64
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_poll
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - drivers/net/ppp/ppp_generic.c:ppp_read
```
```
In net/core/sock.c (ffffffe00073feda)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/sock.c:release_sock
  - net/core/sock.c:__sk_flush_backlog
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__lock_sock
```
```
In net/core/request_sock.c (ffffffe000741248)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/core/datagram.c (ffffffe00074a6a2)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/datagram.c:__sk_queue_drop_skb
```
```
In net/core/gen_stats.c (ffffffe00074cf2a)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/gen_stats.c:gnet_stats_finish_copy
  - net/core/gen_stats.c:gnet_stats_finish_copy
  - net/core/gen_stats.c:gnet_stats_copy_queue
  - net/core/gen_stats.c:gnet_stats_copy_rate_est
  - net/core/gen_stats.c:___gnet_stats_copy_basic
```
```
In net/core/gen_estimator.c (ffffffe00074d342)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/net_namespace.c (ffffffe00074e406)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:peernet2id
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/dev.c (ffffffe00075f410)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/dev.c:dev_set_rx_mode
  - net/core/dev.c:netif_set_real_num_tx_queues
```
```
In net/core/dev_addr_lists.c (ffffffe000765ab2)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:dev_mc_flush
  - net/core/dev_addr_lists.c:__dev_mc_del
  - net/core/dev_addr_lists.c:__dev_mc_add
  - net/core/dev_addr_lists.c:dev_mc_add_excl
  - net/core/dev_addr_lists.c:dev_uc_flush
  - net/core/dev_addr_lists.c:dev_uc_del
  - net/core/dev_addr_lists.c:dev_uc_add
  - net/core/dev_addr_lists.c:dev_uc_add_excl
```
```
In net/core/neighbour.c (ffffffe00076b0b0)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/core/rtnetlink.c (ffffffe0007712b2)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_fdb_dump
```
```
In net/core/sock_reuseport.c (ffffffe000783c9c)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_attach_prog
  - net/core/sock_reuseport.c:reuseport_detach_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_alloc
  - net/core/sock_reuseport.c:reuseport_alloc
```
```
In net/core/page_pool.c (ffffffe000789cb0)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
```
```
In net/core/net-procfs.c (ffffffe00078a9c2)
Location: include/linux/spinlock.h:381
Inline: True
```
```
In net/core/skmsg.c (ffffffe00078c1fc)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_link_pop
```
```
In net/core/sock_map.c (ffffffe000799c7e)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_unref
```
```
In net/core/devlink.c (ffffffe0007a23f6)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_port_type_set
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
```
```
In net/sched/sch_generic.c (ffffffe0007ab3e6)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_graft_qdisc
```
```
In net/sched/sch_mq.c (ffffffe0007abeee)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump
```
```
In net/sched/sch_api.c (ffffffe0007ad644)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/sched/sch_api.c:tcf_node_bind
  - net/sched/sch_api.c:qdisc_class_hash_grow
```
```
In net/ipv4/route.c (ffffffe0007c3db8)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_flush_dev
  - net/ipv4/route.c:ipv4_dst_destroy
  - net/ipv4/route.c:rt_add_uncached_list
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/inetpeer.c (ffffffe0007c630e)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/inet_hashtables.c (ffffffe0007d101e)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_unhash
```
```
In net/ipv4/inet_connection_sock.c (ffffffe0007d2d8c)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp.c (ffffffe0007d5e6e)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_ioctl
```
```
In net/ipv4/tcp_ipv4.c (ffffffe0007edd40)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_seq_stop
  - net/ipv4/tcp_ipv4.c:established_get_next
  - net/ipv4/tcp_ipv4.c:established_get_first
```
```
In net/ipv4/tcp_metrics.c (ffffffe0007f1afc)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_flush_all
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/raw.c (ffffffe0007f5942)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_ioctl
```
```
In net/ipv4/udp.c (ffffffe0007f76be)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_seq_stop
  - net/ipv4/udp.c:udp_get_next
  - net/ipv4/udp.c:udp_get_first
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:skb_consume_udp
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/af_inet.c (ffffffe0008047a4)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_register_protosw
```
```
In net/ipv4/igmp.c (ffffffe000806d64)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_mcf_seq_stop
  - net/ipv4/igmp.c:igmp_mcf_seq_next
  - net/ipv4/igmp.c:igmp_mcf_seq_start
  - net/ipv4/igmp.c:ip_mc_clear_src
  - net/ipv4/igmp.c:ip_mc_add_src
  - net/ipv4/igmp.c:ip_mc_del_src
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:igmpv3_clear_delrec
  - net/ipv4/igmp.c:igmpv3_clear_delrec
  - net/ipv4/igmp.c:igmpv3_del_delrec
  - net/ipv4/igmp.c:igmpv3_del_delrec
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:igmp_stop_timer
```
```
In net/ipv4/fib_semantics.c (ffffffe00080f550)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_release_info
```
```
In net/ipv4/inet_fragment.c (ffffffe0008148c2)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frags_free_cb
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffe00081b45c)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
```
In net/ipv4/ipmr.c (ffffffe000820bb4)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:mr_mfc_seq_stop
```
```
In net/ipv4/ipmr_base.c (ffffffe0008222ee)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_table_dump
  - net/ipv4/ipmr_base.c:mr_table_dump
  - net/ipv4/ipmr_base.c:mr_mfc_seq_next
```
```
In net/ipv4/tcp_bpf.c (ffffffe000825702)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_init
```
```
In net/ipv4/cipso_ipv4.c (ffffffe0008261c8)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_invalidate
```
```
In net/xfrm/xfrm_policy.c (ffffffe00082afb0)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:__xfrm_sk_clone_policy
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_policy_walk
  - net/xfrm/xfrm_policy.c:xfrm_policy_flush
  - net/xfrm/xfrm_policy.c:xfrm_policy_flush
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffe000830f94)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_unregister_afinfo
  - net/xfrm/xfrm_state.c:xfrm_state_register_afinfo
  - net/xfrm/xfrm_state.c:xfrm_unregister_km
  - net/xfrm/xfrm_state.c:xfrm_register_km
  - net/xfrm/xfrm_state.c:xfrm_state_walk
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_find_acq_byseq
  - net/xfrm/xfrm_state.c:xfrm_find_acq
  - net/xfrm/xfrm_state.c:xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_state_lookup_byspi
  - net/xfrm/xfrm_state.c:xfrm_state_lookup_byspi
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_sad_getinfo
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_delete
  - net/xfrm/xfrm_state.c:xfrm_state_gc_task
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_input.c (ffffffe000837aa2)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo
  - net/xfrm/xfrm_input.c:xfrm_input_register_afinfo
```
```
In net/xfrm/xfrm_output.c (ffffffe00083993a)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/af_inet6.c (ffffffe000841630)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_register_protosw
```
```
In net/ipv6/addrconf.c (ffffffe00085253e)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_start
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:ipv6_generate_stable_address
  - net/ipv6/addrconf.c:add_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/route.c (ffffffe00085646e)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_del_rt
  - net/ipv6/route.c:fib6_table_lookup
  - net/ipv6/route.c:fib6_nh_remove_exception
  - net/ipv6/route.c:fib6_nh_flush_exceptions
  - net/ipv6/route.c:rt6_insert_exception
  - net/ipv6/route.c:rt6_insert_exception
  - net/ipv6/route.c:__ip6_ins_rt
  - net/ipv6/route.c:rt6_uncached_list_add
```
```
In net/ipv6/ip6_fib.c (ffffffe00085db64)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:__fib6_clean_all
  - net/ipv6/ip6_fib.c:fib6_update_sernum_stub
  - net/ipv6/ip6_fib.c:fib6_tables_dump
```
```
In net/ipv6/raw.c (ffffffe000869b00)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_ioctl
```
```
In net/ipv6/mcast.c (ffffffe00086d53e)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mcf_seq_stop
  - net/ipv6/mcast.c:igmp6_mcf_seq_next
  - net/ipv6/mcast.c:igmp6_mcf_seq_start
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:ip6_mc_del_src
  - net/ipv6/mcast.c:ip6_mc_del_src
  - net/ipv6/mcast.c:mld_send_report
  - net/ipv6/mcast.c:mld_send_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:mld_del_delrec
  - net/ipv6/mcast.c:mld_del_delrec
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/mcast.c:igmp6_group_added
```
```
In net/ipv6/ip6_flowlabel.c (ffffffe00087b1da)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:fl6_renew
  - net/ipv6/ip6_flowlabel.c:fl6_free_socklist
  - net/ipv6/ip6_flowlabel.c:fl6_free_socklist
  - net/ipv6/ip6_flowlabel.c:fl_release
```
```
In net/ipv6/ip6mr.c (ffffffe00087f83c)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:mr_mfc_seq_stop
```
```
In net/ipv6/calipso.c (ffffffe00088708a)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_cache_invalidate
```
```
In net/packet/af_packet.c (ffffffe0008920ee)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_ioctl
  - net/packet/af_packet.c:packet_getsockopt
```
```
In net/dcb/dcbnl.c (ffffffe00089fe9e)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_ieee_getapp_default_prio_mask
  - net/dcb/dcbnl.c:dcb_ieee_getapp_dscp_prio_mask_map
  - net/dcb/dcbnl.c:dcb_ieee_getapp_prio_dscp_mask_map
  - net/dcb/dcbnl.c:dcb_ieee_delapp
  - net/dcb/dcbnl.c:dcb_ieee_setapp
  - net/dcb/dcbnl.c:dcb_ieee_getapp_mask
  - net/dcb/dcbnl.c:dcb_setapp
  - net/dcb/dcbnl.c:dcb_getapp
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
```
```
In net/switchdev/switchdev.c (ffffffe0008a3698)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_deferred_process
```
```
In net/xdp/xsk.c (ffffffe0008ac282)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xsk.c:xsk_generic_rcv
  - net/xdp/xsk.c:xsk_generic_rcv
```
```
In lib/xarray.c (ffffffe0008c3648)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - lib/xarray.c:__xas_nomem
```
</details>
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
In kernel/cgroup/cgroup.c (ffffffff81156db8)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_idr_remove
  - kernel/cgroup/cgroup.c:cgroup_idr_replace
```
```
In kernel/bpf/core.c (ffffffff811d5d8a)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
```
```
In kernel/bpf/syscall.c (ffffffff811da579)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_obj_get_next_id
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_map_inc_not_zero
  - kernel/bpf/syscall.c:map_create
```
```
In kernel/bpf/local_storage.c (ffffffff811f2123)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_unlink
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_link
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_release
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_assign
  - kernel/bpf/local_storage.c:cgroup_storage_get_next_key
  - kernel/bpf/local_storage.c:cgroup_storage_get_next_key
  - kernel/bpf/local_storage.c:cgroup_storage_lookup
  - kernel/bpf/local_storage.c:cgroup_storage_lookup
```
```
In kernel/bpf/btf.c (ffffffff811f6cd9)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
```
```
In kernel/bpf/xskmap.c (ffffffff811f9c9d)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - kernel/bpf/xskmap.c:xsk_map_try_sock_delete
  - kernel/bpf/xskmap.c:xsk_map_delete_elem
  - kernel/bpf/xskmap.c:xsk_map_update_elem
  - kernel/bpf/xskmap.c:xsk_map_update_elem
  - kernel/bpf/xskmap.c:xsk_map_update_elem
  - kernel/bpf/xskmap.c:xsk_map_sock_delete
```
```
In kernel/bpf/reuseport_array.c (ffffffff811ff341)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem
  - kernel/bpf/reuseport_array.c:reuseport_array_delete_elem
```
```
In kernel/padata.c (ffffffff81216810)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - kernel/padata.c:padata_reorder
```
```
In mm/page-writeback.c (ffffffff81223bd1)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - mm/page-writeback.c:bdi_set_max_ratio
  - mm/page-writeback.c:bdi_set_min_ratio
```
```
In mm/backing-dev.c (ffffffff81241b96)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:bdi_get_by_id
  - mm/backing-dev.c:wb_wakeup_delayed
```
```
In fs/fs-writeback.c (ffffffff8130d599)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_queue_work
  - fs/fs-writeback.c:wb_wakeup
```
```
In security/selinux/netif.c (ffffffff81461ed0)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_netdev_notifier_handler
  - security/selinux/netif.c:sel_netif_flush
  - security/selinux/netif.c:sel_netif_sid
```
```
In security/selinux/netnode.c (ffffffff81462503)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_flush
  - security/selinux/netnode.c:sel_netnode_sid
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (ffffffff814627b3)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_flush
  - security/selinux/netport.c:sel_netport_sid
  - security/selinux/netport.c:sel_netport_sid
```
```
In block/genhd.c (ffffffff814f14f2)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - block/genhd.c:get_gendisk
```
```
In block/blk-cgroup.c (ffffffff81503445)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - block/blk-cgroup.c:__blkcg_punt_bio_submit
  - block/blk-cgroup.c:blkg_async_bio_workfn
```
```
In drivers/connector/cn_queue.c (ffffffff816b9d9f)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_free_dev
  - drivers/connector/cn_queue.c:cn_queue_del_callback
  - drivers/connector/cn_queue.c:cn_queue_add_callback
```
```
In drivers/connector/connector.c (ffffffff816b9ec2)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_proc_show
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/net/tun.c (ffffffff817856d7)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_set_ebpf
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_flow_update
  - drivers/net/tun.c:tun_flow_flush
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8178be0b)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_disconnect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_disconnect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_ccp_closed
  - drivers/net/ppp/ppp_generic.c:ppp_ccp_closed
  - drivers/net/ppp/ppp_generic.c:ppp_set_compress
  - drivers/net/ppp/ppp_generic.c:ppp_set_compress
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_input_error
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_dev_uninit
  - drivers/net/ppp/ppp_generic.c:ppp_dev_uninit
  - drivers/net/ppp/ppp_generic.c:ppp_get_stats64
  - drivers/net/ppp/ppp_generic.c:ppp_get_stats64
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_poll
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - drivers/net/ppp/ppp_generic.c:ppp_read
```
```
In drivers/net/xen-netfront.c (ffffffff817948ad)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:netback_changed
```
```
In net/core/sock.c (ffffffff818b5027)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/sock.c:release_sock
  - net/core/sock.c:__sk_flush_backlog
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__lock_sock
```
```
In net/core/request_sock.c (ffffffff818b6e2f)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/core/datagram.c (ffffffff818c1296)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/datagram.c:__sk_queue_drop_skb
```
```
In net/core/gen_stats.c (ffffffff818c3d33)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/gen_stats.c:gnet_stats_finish_copy
  - net/core/gen_stats.c:gnet_stats_finish_copy
  - net/core/gen_stats.c:gnet_stats_copy_queue
  - net/core/gen_stats.c:gnet_stats_copy_rate_est
  - net/core/gen_stats.c:___gnet_stats_copy_basic
```
```
In net/core/gen_estimator.c (ffffffff818c4145)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/net_namespace.c (ffffffff818c571e)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:peernet2id
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/dev.c (ffffffff818d7167)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/dev.c:dev_set_rx_mode
  - net/core/dev.c:netif_set_real_num_tx_queues
```
```
In net/core/dev_addr_lists.c (ffffffff818dfb1a)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:dev_mc_flush
  - net/core/dev_addr_lists.c:__dev_mc_del
  - net/core/dev_addr_lists.c:__dev_mc_add
  - net/core/dev_addr_lists.c:dev_mc_add_excl
  - net/core/dev_addr_lists.c:dev_uc_flush
  - net/core/dev_addr_lists.c:dev_uc_del
  - net/core/dev_addr_lists.c:dev_uc_add
  - net/core/dev_addr_lists.c:dev_uc_add_excl
```
```
In net/core/neighbour.c (ffffffff818e6784)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/core/rtnetlink.c (ffffffff818eca53)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_fdb_dump
```
```
In net/core/sock_reuseport.c (ffffffff819017f2)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_attach_prog
  - net/core/sock_reuseport.c:reuseport_detach_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_alloc
  - net/core/sock_reuseport.c:reuseport_alloc
```
```
In net/core/page_pool.c (ffffffff8190754f)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
```
```
In net/core/net-procfs.c (ffffffff81907ff2)
Location: include/linux/spinlock.h:381
Inline: True
```
```
In net/core/skmsg.c (ffffffff81909a1f)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_link_pop
```
```
In net/core/sock_map.c (ffffffff819198a8)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_unref
```
```
In net/core/devlink.c (ffffffff81922b2f)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_port_type_set
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
```
```
In net/sched/sch_generic.c (ffffffff8192e6ab)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_graft_qdisc
```
```
In net/sched/sch_mq.c (ffffffff8192edbd)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump
```
```
In net/sched/sch_api.c (ffffffff81930a5b)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/sched/sch_api.c:tcf_node_bind
  - net/sched/sch_api.c:qdisc_class_hash_grow
```
```
In net/ipv4/route.c (ffffffff8194a4ba)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_flush_dev
  - net/ipv4/route.c:ipv4_dst_destroy
  - net/ipv4/route.c:rt_add_uncached_list
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/inetpeer.c (ffffffff8194d594)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/inet_hashtables.c (ffffffff81959c08)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_unhash
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8195ba92)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp.c (ffffffff8195fd54)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_ioctl
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81979a4e)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_seq_stop
  - net/ipv4/tcp_ipv4.c:established_get_next
```
```
In net/ipv4/tcp_metrics.c (ffffffff8197e75d)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_flush_all
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/raw.c (ffffffff81982adb)
Location: include/linux/spinlock.h:381
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819848f0)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_seq_stop
  - net/ipv4/udp.c:udp_get_next
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/af_inet.c (ffffffff81993776)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_register_protosw
```
```
In net/ipv4/igmp.c (ffffffff81996307)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_mcf_seq_stop
  - net/ipv4/igmp.c:igmp_mcf_seq_next
  - net/ipv4/igmp.c:igmp_mcf_seq_start
  - net/ipv4/igmp.c:ip_mc_clear_src
  - net/ipv4/igmp.c:ip_mc_add_src
  - net/ipv4/igmp.c:ip_mc_del_src
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:igmpv3_clear_delrec
  - net/ipv4/igmp.c:igmpv3_clear_delrec
  - net/ipv4/igmp.c:igmpv3_del_delrec
  - net/ipv4/igmp.c:igmpv3_del_delrec
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:igmp_stop_timer
```
```
In net/ipv4/fib_semantics.c (ffffffff8199fc30)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_release_info
```
```
In net/ipv4/inet_fragment.c (ffffffff819a5899)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frags_free_cb
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff819ad0ee)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
```
In net/ipv4/ipmr.c (ffffffff819b2243)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:mr_mfc_seq_stop
```
```
In net/ipv4/ipmr_base.c (ffffffff819b4765)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_table_dump
  - net/ipv4/ipmr_base.c:mr_table_dump
  - net/ipv4/ipmr_base.c:mr_mfc_seq_next
```
```
In net/ipv4/tcp_bpf.c (ffffffff819b8363)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_init
```
```
In net/ipv4/cipso_ipv4.c (ffffffff819b8de5)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_invalidate
```
```
In net/xfrm/xfrm_policy.c (ffffffff819c0784)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:__xfrm_sk_clone_policy
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_policy_walk
  - net/xfrm/xfrm_policy.c:xfrm_policy_flush
  - net/xfrm/xfrm_policy.c:xfrm_policy_flush
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff819c477a)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_unregister_afinfo
  - net/xfrm/xfrm_state.c:xfrm_state_register_afinfo
  - net/xfrm/xfrm_state.c:xfrm_unregister_km
  - net/xfrm/xfrm_state.c:xfrm_register_km
  - net/xfrm/xfrm_state.c:xfrm_state_walk
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_find_acq_byseq
  - net/xfrm/xfrm_state.c:xfrm_find_acq
  - net/xfrm/xfrm_state.c:xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_state_lookup_byspi
  - net/xfrm/xfrm_state.c:xfrm_state_lookup_byspi
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_sad_getinfo
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_delete
  - net/xfrm/xfrm_state.c:xfrm_state_gc_task
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_input.c (ffffffff819ca9de)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo
  - net/xfrm/xfrm_input.c:xfrm_input_register_afinfo
```
```
In net/xfrm/xfrm_output.c (ffffffff819cccef)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/af_inet6.c (ffffffff819d490b)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_register_protosw
```
```
In net/ipv6/addrconf.c (ffffffff819e760c)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_start
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:ipv6_generate_stable_address
  - net/ipv6/addrconf.c:add_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/route.c (ffffffff819eabf4)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_del_rt
  - net/ipv6/route.c:fib6_table_lookup
  - net/ipv6/route.c:fib6_nh_remove_exception
  - net/ipv6/route.c:fib6_nh_flush_exceptions
  - net/ipv6/route.c:rt6_insert_exception
  - net/ipv6/route.c:rt6_insert_exception
  - net/ipv6/route.c:__ip6_ins_rt
  - net/ipv6/route.c:rt6_uncached_list_add
```
```
In net/ipv6/ip6_fib.c (ffffffff819f3fc6)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:__fib6_clean_all
  - net/ipv6/ip6_fib.c:fib6_update_sernum_stub
  - net/ipv6/ip6_fib.c:fib6_tables_dump
```
```
In net/ipv6/raw.c (ffffffff81a02e1b)
Location: include/linux/spinlock.h:381
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff81a06a67)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mcf_seq_stop
  - net/ipv6/mcast.c:igmp6_mcf_seq_next
  - net/ipv6/mcast.c:igmp6_mcf_seq_start
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:ip6_mc_del_src
  - net/ipv6/mcast.c:ip6_mc_del_src
  - net/ipv6/mcast.c:mld_send_report
  - net/ipv6/mcast.c:mld_send_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:mld_del_delrec
  - net/ipv6/mcast.c:mld_del_delrec
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/mcast.c:igmp6_group_added
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81a155ad)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:fl6_renew
  - net/ipv6/ip6_flowlabel.c:fl6_free_socklist
  - net/ipv6/ip6_flowlabel.c:fl6_free_socklist
  - net/ipv6/ip6_flowlabel.c:fl_release
```
```
In net/ipv6/ip6mr.c (ffffffff81a1a4eb)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:mr_mfc_seq_stop
```
```
In net/ipv6/calipso.c (ffffffff81a21c6c)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_cache_invalidate
```
```
In net/packet/af_packet.c (ffffffff81a2e2b0)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_getsockopt
```
```
In net/dcb/dcbnl.c (ffffffff81a3c8bb)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_ieee_getapp_default_prio_mask
  - net/dcb/dcbnl.c:dcb_ieee_getapp_dscp_prio_mask_map
  - net/dcb/dcbnl.c:dcb_ieee_getapp_prio_dscp_mask_map
  - net/dcb/dcbnl.c:dcb_ieee_delapp
  - net/dcb/dcbnl.c:dcb_ieee_setapp
  - net/dcb/dcbnl.c:dcb_ieee_getapp_mask
  - net/dcb/dcbnl.c:dcb_setapp
  - net/dcb/dcbnl.c:dcb_getapp
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
```
```
In net/switchdev/switchdev.c (ffffffff81a410a8)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_deferred_process
```
```
In net/xdp/xsk.c (ffffffff81a4a5ac)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xsk.c:xsk_generic_rcv
  - net/xdp/xsk.c:xsk_generic_rcv
```
```
In lib/xarray.c (ffffffff81a5cd82)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - lib/xarray.c:__xas_nomem
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
In kernel/cgroup/cgroup.c (ffffffff8114a0d8)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_idr_remove
  - kernel/cgroup/cgroup.c:cgroup_idr_replace
```
```
In kernel/bpf/core.c (ffffffff811c8b4a)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
```
```
In kernel/bpf/syscall.c (ffffffff811cd339)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_obj_get_next_id
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_map_inc_not_zero
  - kernel/bpf/syscall.c:map_create
```
```
In kernel/bpf/local_storage.c (ffffffff811e4e73)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_unlink
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_link
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_release
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_assign
  - kernel/bpf/local_storage.c:cgroup_storage_get_next_key
  - kernel/bpf/local_storage.c:cgroup_storage_get_next_key
  - kernel/bpf/local_storage.c:cgroup_storage_lookup
  - kernel/bpf/local_storage.c:cgroup_storage_lookup
```
```
In kernel/bpf/btf.c (ffffffff811e9a29)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
```
```
In kernel/bpf/xskmap.c (ffffffff811ec9ed)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - kernel/bpf/xskmap.c:xsk_map_try_sock_delete
  - kernel/bpf/xskmap.c:xsk_map_delete_elem
  - kernel/bpf/xskmap.c:xsk_map_update_elem
  - kernel/bpf/xskmap.c:xsk_map_update_elem
  - kernel/bpf/xskmap.c:xsk_map_update_elem
  - kernel/bpf/xskmap.c:xsk_map_sock_delete
```
```
In kernel/bpf/reuseport_array.c (ffffffff811f2091)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem
  - kernel/bpf/reuseport_array.c:reuseport_array_delete_elem
```
```
In kernel/padata.c (ffffffff81209570)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - kernel/padata.c:padata_reorder
```
```
In mm/page-writeback.c (ffffffff81216d81)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - mm/page-writeback.c:bdi_set_max_ratio
  - mm/page-writeback.c:bdi_set_min_ratio
```
```
In mm/backing-dev.c (ffffffff81234b86)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:bdi_get_by_id
  - mm/backing-dev.c:wb_wakeup_delayed
```
```
In fs/fs-writeback.c (ffffffff812fe1a9)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_queue_work
  - fs/fs-writeback.c:wb_wakeup
```
```
In security/selinux/netif.c (ffffffff81452900)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_netdev_notifier_handler
  - security/selinux/netif.c:sel_netif_flush
  - security/selinux/netif.c:sel_netif_sid
```
```
In security/selinux/netnode.c (ffffffff81452f33)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_flush
  - security/selinux/netnode.c:sel_netnode_sid
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (ffffffff814531e3)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_flush
  - security/selinux/netport.c:sel_netport_sid
  - security/selinux/netport.c:sel_netport_sid
```
```
In block/genhd.c (ffffffff814e1a32)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - block/genhd.c:get_gendisk
```
```
In block/blk-cgroup.c (ffffffff814f3905)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - block/blk-cgroup.c:__blkcg_punt_bio_submit
  - block/blk-cgroup.c:blkg_async_bio_workfn
```
```
In drivers/connector/cn_queue.c (ffffffff816979df)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_free_dev
  - drivers/connector/cn_queue.c:cn_queue_del_callback
  - drivers/connector/cn_queue.c:cn_queue_add_callback
```
```
In drivers/connector/connector.c (ffffffff81697b02)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_proc_show
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/net/tun.c (ffffffff81765027)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_set_ebpf
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_flow_update
  - drivers/net/tun.c:tun_flow_flush
```
```
In drivers/net/vxlan.c (ffffffff8176f7a1)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - drivers/net/vxlan.c:vxlan_switchdev_event
  - drivers/net/vxlan.c:vxlan_switchdev_event
  - drivers/net/vxlan.c:vxlan_fdb_offloaded_set
  - drivers/net/vxlan.c:vxlan_changelink
  - drivers/net/vxlan.c:vxlan_changelink
  - drivers/net/vxlan.c:vxlan_flush
  - drivers/net/vxlan.c:vxlan_uninit
  - drivers/net/vxlan.c:vxlan_fdb_delete
  - drivers/net/vxlan.c:vxlan_fdb_add
  - drivers/net/vxlan.c:vxlan_fdb_replay
  - drivers/net/vxlan.c:vxlan_fdb_replay
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81774bdb)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_disconnect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_disconnect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_ccp_closed
  - drivers/net/ppp/ppp_generic.c:ppp_ccp_closed
  - drivers/net/ppp/ppp_generic.c:ppp_set_compress
  - drivers/net/ppp/ppp_generic.c:ppp_set_compress
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_input_error
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_dev_uninit
  - drivers/net/ppp/ppp_generic.c:ppp_dev_uninit
  - drivers/net/ppp/ppp_generic.c:ppp_get_stats64
  - drivers/net/ppp/ppp_generic.c:ppp_get_stats64
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_poll
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - drivers/net/ppp/ppp_generic.c:ppp_read
```
```
In net/core/sock.c (ffffffff8186ef77)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/sock.c:release_sock
  - net/core/sock.c:__sk_flush_backlog
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__lock_sock
```
```
In net/core/request_sock.c (ffffffff81870d7f)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/core/datagram.c (ffffffff8187b1d6)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/datagram.c:__sk_queue_drop_skb
```
```
In net/core/gen_stats.c (ffffffff8187dc73)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/gen_stats.c:gnet_stats_finish_copy
  - net/core/gen_stats.c:gnet_stats_finish_copy
  - net/core/gen_stats.c:gnet_stats_copy_queue
  - net/core/gen_stats.c:gnet_stats_copy_rate_est
  - net/core/gen_stats.c:___gnet_stats_copy_basic
```
```
In net/core/gen_estimator.c (ffffffff8187e085)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/net_namespace.c (ffffffff8187f65e)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:peernet2id
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/dev.c (ffffffff81890fa7)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/dev.c:dev_set_rx_mode
  - net/core/dev.c:netif_set_real_num_tx_queues
```
```
In net/core/dev_addr_lists.c (ffffffff8189995a)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:dev_mc_flush
  - net/core/dev_addr_lists.c:__dev_mc_del
  - net/core/dev_addr_lists.c:__dev_mc_add
  - net/core/dev_addr_lists.c:dev_mc_add_excl
  - net/core/dev_addr_lists.c:dev_uc_flush
  - net/core/dev_addr_lists.c:dev_uc_del
  - net/core/dev_addr_lists.c:dev_uc_add
  - net/core/dev_addr_lists.c:dev_uc_add_excl
```
```
In net/core/neighbour.c (ffffffff818a05c4)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/core/rtnetlink.c (ffffffff818a6893)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_fdb_dump
```
```
In net/core/sock_reuseport.c (ffffffff818bb622)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_attach_prog
  - net/core/sock_reuseport.c:reuseport_detach_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_alloc
  - net/core/sock_reuseport.c:reuseport_alloc
```
```
In net/core/page_pool.c (ffffffff818c135f)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
```
```
In net/core/net-procfs.c (ffffffff818c1e02)
Location: include/linux/spinlock.h:381
Inline: True
```
```
In net/core/skmsg.c (ffffffff818c382f)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_link_pop
```
```
In net/core/sock_map.c (ffffffff818d3658)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_unref
```
```
In net/core/devlink.c (ffffffff818dc8df)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_port_type_set
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
```
```
In net/sched/sch_generic.c (ffffffff818e81ab)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_graft_qdisc
```
```
In net/sched/sch_mq.c (ffffffff818e88bd)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump
```
```
In net/sched/sch_api.c (ffffffff818ea55b)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/sched/sch_api.c:tcf_node_bind
  - net/sched/sch_api.c:qdisc_class_hash_grow
```
```
In net/ipv4/route.c (ffffffff81903faa)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_flush_dev
  - net/ipv4/route.c:ipv4_dst_destroy
  - net/ipv4/route.c:rt_add_uncached_list
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/inetpeer.c (ffffffff81907084)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/inet_hashtables.c (ffffffff819136f8)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_unhash
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81915582)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp.c (ffffffff81919844)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_ioctl
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8193350e)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_seq_stop
  - net/ipv4/tcp_ipv4.c:established_get_next
```
```
In net/ipv4/tcp_metrics.c (ffffffff8193821d)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_flush_all
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/raw.c (ffffffff8193c59b)
Location: include/linux/spinlock.h:381
Inline: True
```
```
In net/ipv4/udp.c (ffffffff8193e3b0)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_seq_stop
  - net/ipv4/udp.c:udp_get_next
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/af_inet.c (ffffffff8194d236)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_register_protosw
```
```
In net/ipv4/igmp.c (ffffffff8194fdc7)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_mcf_seq_stop
  - net/ipv4/igmp.c:igmp_mcf_seq_next
  - net/ipv4/igmp.c:igmp_mcf_seq_start
  - net/ipv4/igmp.c:ip_mc_clear_src
  - net/ipv4/igmp.c:ip_mc_add_src
  - net/ipv4/igmp.c:ip_mc_del_src
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:igmpv3_clear_delrec
  - net/ipv4/igmp.c:igmpv3_clear_delrec
  - net/ipv4/igmp.c:igmpv3_del_delrec
  - net/ipv4/igmp.c:igmpv3_del_delrec
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:igmp_stop_timer
```
```
In net/ipv4/fib_semantics.c (ffffffff819596f0)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_release_info
```
```
In net/ipv4/inet_fragment.c (ffffffff8195f359)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frags_free_cb
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff8196971e)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
```
In net/ipv4/ipmr.c (ffffffff8196e873)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:mr_mfc_seq_stop
```
```
In net/ipv4/ipmr_base.c (ffffffff81970d95)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_table_dump
  - net/ipv4/ipmr_base.c:mr_table_dump
  - net/ipv4/ipmr_base.c:mr_mfc_seq_next
```
```
In net/ipv4/tcp_bpf.c (ffffffff81975153)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_init
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81975bd5)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_invalidate
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197d574)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:__xfrm_sk_clone_policy
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_policy_walk
  - net/xfrm/xfrm_policy.c:xfrm_policy_flush
  - net/xfrm/xfrm_policy.c:xfrm_policy_flush
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff8198156a)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_unregister_afinfo
  - net/xfrm/xfrm_state.c:xfrm_state_register_afinfo
  - net/xfrm/xfrm_state.c:xfrm_unregister_km
  - net/xfrm/xfrm_state.c:xfrm_register_km
  - net/xfrm/xfrm_state.c:xfrm_state_walk
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_find_acq_byseq
  - net/xfrm/xfrm_state.c:xfrm_find_acq
  - net/xfrm/xfrm_state.c:xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_state_lookup_byspi
  - net/xfrm/xfrm_state.c:xfrm_state_lookup_byspi
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_sad_getinfo
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_delete
  - net/xfrm/xfrm_state.c:xfrm_state_gc_task
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_input.c (ffffffff819877ce)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo
  - net/xfrm/xfrm_input.c:xfrm_input_register_afinfo
```
```
In net/xfrm/xfrm_output.c (ffffffff81989adf)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/af_inet6.c (ffffffff819916cb)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_register_protosw
```
```
In net/ipv6/addrconf.c (ffffffff819a43cc)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_start
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:ipv6_generate_stable_address
  - net/ipv6/addrconf.c:add_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/route.c (ffffffff819a79b4)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_del_rt
  - net/ipv6/route.c:fib6_table_lookup
  - net/ipv6/route.c:fib6_nh_remove_exception
  - net/ipv6/route.c:fib6_nh_flush_exceptions
  - net/ipv6/route.c:rt6_insert_exception
  - net/ipv6/route.c:rt6_insert_exception
  - net/ipv6/route.c:__ip6_ins_rt
  - net/ipv6/route.c:rt6_uncached_list_add
```
```
In net/ipv6/ip6_fib.c (ffffffff819b0d86)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:__fib6_clean_all
  - net/ipv6/ip6_fib.c:fib6_update_sernum_stub
  - net/ipv6/ip6_fib.c:fib6_tables_dump
```
```
In net/ipv6/raw.c (ffffffff819bfbdb)
Location: include/linux/spinlock.h:381
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff819c3827)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mcf_seq_stop
  - net/ipv6/mcast.c:igmp6_mcf_seq_next
  - net/ipv6/mcast.c:igmp6_mcf_seq_start
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:ip6_mc_del_src
  - net/ipv6/mcast.c:ip6_mc_del_src
  - net/ipv6/mcast.c:mld_send_report
  - net/ipv6/mcast.c:mld_send_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:mld_del_delrec
  - net/ipv6/mcast.c:mld_del_delrec
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/mcast.c:igmp6_group_added
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff819d236d)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:fl6_renew
  - net/ipv6/ip6_flowlabel.c:fl6_free_socklist
  - net/ipv6/ip6_flowlabel.c:fl6_free_socklist
  - net/ipv6/ip6_flowlabel.c:fl_release
```
```
In net/ipv6/ip6mr.c (ffffffff819d72ab)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:mr_mfc_seq_stop
```
```
In net/ipv6/calipso.c (ffffffff819dea2c)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_cache_invalidate
```
```
In net/packet/af_packet.c (ffffffff819eb4a0)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_getsockopt
```
```
In net/dcb/dcbnl.c (ffffffff819f94ab)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_ieee_getapp_default_prio_mask
  - net/dcb/dcbnl.c:dcb_ieee_getapp_dscp_prio_mask_map
  - net/dcb/dcbnl.c:dcb_ieee_getapp_prio_dscp_mask_map
  - net/dcb/dcbnl.c:dcb_ieee_delapp
  - net/dcb/dcbnl.c:dcb_ieee_setapp
  - net/dcb/dcbnl.c:dcb_ieee_getapp_mask
  - net/dcb/dcbnl.c:dcb_setapp
  - net/dcb/dcbnl.c:dcb_getapp
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
```
```
In net/switchdev/switchdev.c (ffffffff819fdc98)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_deferred_process
```
```
In net/xdp/xsk.c (ffffffff81a0719c)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xsk.c:xsk_generic_rcv
  - net/xdp/xsk.c:xsk_generic_rcv
```
```
In lib/xarray.c (ffffffff81a19e62)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - lib/xarray.c:__xas_nomem
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
In kernel/cgroup/cgroup.c (ffffffff81154b88)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_idr_remove
  - kernel/cgroup/cgroup.c:cgroup_idr_replace
```
```
In kernel/bpf/core.c (ffffffff811d3b5a)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
```
```
In kernel/bpf/syscall.c (ffffffff811d8349)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_obj_get_next_id
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_map_inc_not_zero
  - kernel/bpf/syscall.c:map_create
```
```
In kernel/bpf/local_storage.c (ffffffff811efef3)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_unlink
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_link
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_release
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_assign
  - kernel/bpf/local_storage.c:cgroup_storage_get_next_key
  - kernel/bpf/local_storage.c:cgroup_storage_get_next_key
  - kernel/bpf/local_storage.c:cgroup_storage_lookup
  - kernel/bpf/local_storage.c:cgroup_storage_lookup
```
```
In kernel/bpf/btf.c (ffffffff811f4aa9)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
```
```
In kernel/bpf/xskmap.c (ffffffff811f7a6d)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - kernel/bpf/xskmap.c:xsk_map_try_sock_delete
  - kernel/bpf/xskmap.c:xsk_map_delete_elem
  - kernel/bpf/xskmap.c:xsk_map_update_elem
  - kernel/bpf/xskmap.c:xsk_map_update_elem
  - kernel/bpf/xskmap.c:xsk_map_update_elem
  - kernel/bpf/xskmap.c:xsk_map_sock_delete
```
```
In kernel/bpf/reuseport_array.c (ffffffff811fd111)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem
  - kernel/bpf/reuseport_array.c:reuseport_array_delete_elem
```
```
In kernel/padata.c (ffffffff812145b0)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - kernel/padata.c:padata_reorder
```
```
In mm/page-writeback.c (ffffffff81221971)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - mm/page-writeback.c:bdi_set_max_ratio
  - mm/page-writeback.c:bdi_set_min_ratio
```
```
In mm/backing-dev.c (ffffffff8123f936)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:bdi_get_by_id
  - mm/backing-dev.c:wb_wakeup_delayed
```
```
In fs/fs-writeback.c (ffffffff8130b389)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_queue_work
  - fs/fs-writeback.c:wb_wakeup
```
```
In security/selinux/netif.c (ffffffff8145df70)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_netdev_notifier_handler
  - security/selinux/netif.c:sel_netif_flush
  - security/selinux/netif.c:sel_netif_sid
```
```
In security/selinux/netnode.c (ffffffff8145e5a3)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_flush
  - security/selinux/netnode.c:sel_netnode_sid
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (ffffffff8145e853)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_flush
  - security/selinux/netport.c:sel_netport_sid
  - security/selinux/netport.c:sel_netport_sid
```
```
In block/genhd.c (ffffffff814ed582)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - block/genhd.c:get_gendisk
```
```
In block/blk-cgroup.c (ffffffff814ff4d5)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - block/blk-cgroup.c:__blkcg_punt_bio_submit
  - block/blk-cgroup.c:blkg_async_bio_workfn
```
```
In drivers/connector/cn_queue.c (ffffffff816e826f)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_free_dev
  - drivers/connector/cn_queue.c:cn_queue_del_callback
  - drivers/connector/cn_queue.c:cn_queue_add_callback
```
```
In drivers/connector/connector.c (ffffffff816e8392)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_proc_show
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/net/tun.c (ffffffff817b5a87)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_set_ebpf
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_flow_update
  - drivers/net/tun.c:tun_flow_flush
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817bc1ab)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_disconnect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_disconnect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_ccp_closed
  - drivers/net/ppp/ppp_generic.c:ppp_ccp_closed
  - drivers/net/ppp/ppp_generic.c:ppp_set_compress
  - drivers/net/ppp/ppp_generic.c:ppp_set_compress
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_input_error
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_dev_uninit
  - drivers/net/ppp/ppp_generic.c:ppp_dev_uninit
  - drivers/net/ppp/ppp_generic.c:ppp_get_stats64
  - drivers/net/ppp/ppp_generic.c:ppp_get_stats64
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_poll
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - drivers/net/ppp/ppp_generic.c:ppp_read
```
```
In drivers/net/xen-netfront.c (ffffffff817c4aed)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:netback_changed
```
```
In net/core/sock.c (ffffffff81906027)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/sock.c:release_sock
  - net/core/sock.c:__sk_flush_backlog
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__lock_sock
```
```
In net/core/request_sock.c (ffffffff81907e2f)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/core/datagram.c (ffffffff81912296)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/datagram.c:__sk_queue_drop_skb
```
```
In net/core/gen_stats.c (ffffffff81914d33)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/gen_stats.c:gnet_stats_finish_copy
  - net/core/gen_stats.c:gnet_stats_finish_copy
  - net/core/gen_stats.c:gnet_stats_copy_queue
  - net/core/gen_stats.c:gnet_stats_copy_rate_est
  - net/core/gen_stats.c:___gnet_stats_copy_basic
```
```
In net/core/gen_estimator.c (ffffffff81915145)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/net_namespace.c (ffffffff8191671e)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:peernet2id
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/dev.c (ffffffff81928197)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/dev.c:dev_set_rx_mode
  - net/core/dev.c:netif_set_real_num_tx_queues
```
```
In net/core/dev_addr_lists.c (ffffffff81930b4a)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:dev_mc_flush
  - net/core/dev_addr_lists.c:__dev_mc_del
  - net/core/dev_addr_lists.c:__dev_mc_add
  - net/core/dev_addr_lists.c:dev_mc_add_excl
  - net/core/dev_addr_lists.c:dev_uc_flush
  - net/core/dev_addr_lists.c:dev_uc_del
  - net/core/dev_addr_lists.c:dev_uc_add
  - net/core/dev_addr_lists.c:dev_uc_add_excl
```
```
In net/core/neighbour.c (ffffffff819377b4)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/core/rtnetlink.c (ffffffff8193da83)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_fdb_dump
```
```
In net/core/sock_reuseport.c (ffffffff81952822)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_attach_prog
  - net/core/sock_reuseport.c:reuseport_detach_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_alloc
  - net/core/sock_reuseport.c:reuseport_alloc
```
```
In net/core/page_pool.c (ffffffff8195857f)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
```
```
In net/core/net-procfs.c (ffffffff81959022)
Location: include/linux/spinlock.h:381
Inline: True
```
```
In net/core/skmsg.c (ffffffff8195aa4f)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_link_pop
```
```
In net/core/sock_map.c (ffffffff8196aa38)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_unref
```
```
In net/core/devlink.c (ffffffff81973cbf)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_port_type_set
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
```
```
In net/sched/sch_generic.c (ffffffff8197f83b)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_graft_qdisc
```
```
In net/sched/sch_mq.c (ffffffff8197ff4d)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump
```
```
In net/sched/sch_api.c (ffffffff81981beb)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/sched/sch_api.c:tcf_node_bind
  - net/sched/sch_api.c:qdisc_class_hash_grow
```
```
In net/netfilter/nfnetlink_queue.c (ffffffff8199ae78)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/netfilter/nfnetlink_queue.c:nfqnl_recv_config
  - net/netfilter/nfnetlink_queue.c:nfqnl_recv_config
  - net/netfilter/nfnetlink_queue.c:nfqnl_recv_config
  - net/netfilter/nfnetlink_queue.c:nfqnl_recv_verdict
  - net/netfilter/nfnetlink_queue.c:nfqnl_recv_verdict_batch
  - net/netfilter/nfnetlink_queue.c:__nfqnl_enqueue_packet
  - net/netfilter/nfnetlink_queue.c:__nfqnl_enqueue_packet
  - net/netfilter/nfnetlink_queue.c:nfqnl_flush
```
```
In net/netfilter/nfnetlink_log.c (ffffffff8199b9a1)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/netfilter/nfnetlink_log.c:nfulnl_recv_config
  - net/netfilter/nfnetlink_log.c:nfulnl_recv_config
  - net/netfilter/nfnetlink_log.c:nfulnl_recv_config
  - net/netfilter/nfnetlink_log.c:nfulnl_recv_config
  - net/netfilter/nfnetlink_log.c:nfulnl_recv_config
  - net/netfilter/nfnetlink_log.c:nfulnl_recv_config
  - net/netfilter/nfnetlink_log.c:nfulnl_recv_config
  - net/netfilter/nfnetlink_log.c:nfulnl_recv_config
  - net/netfilter/nfnetlink_log.c:nfulnl_rcv_nl_event
  - net/netfilter/nfnetlink_log.c:nfulnl_log_packet
  - net/netfilter/nfnetlink_log.c:nfulnl_timer
```
```
In net/netfilter/nf_conntrack_core.c (ffffffff8199cf99)
Location: include/linux/spinlock.h:381
Inline: True
```
```
In net/netfilter/nf_conntrack_expect.c (ffffffff819a244e)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_expect.c:nf_ct_expect_iterate_net
  - net/netfilter/nf_conntrack_expect.c:nf_ct_expect_iterate_destroy
  - net/netfilter/nf_conntrack_expect.c:nf_ct_expect_related_report
  - net/netfilter/nf_conntrack_expect.c:nf_ct_expect_related_report
  - net/netfilter/nf_conntrack_expect.c:nf_ct_unexpect_related
  - net/netfilter/nf_conntrack_expect.c:nf_ct_remove_expectations
  - net/netfilter/nf_conntrack_expect.c:nf_ct_expectation_timed_out
```
```
In net/netfilter/nf_conntrack_helper.c (ffffffff819a30ec)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_helper.c:nf_ct_helper_expectfn_unregister
  - net/netfilter/nf_conntrack_helper.c:nf_ct_helper_expectfn_register
```
```
In net/netfilter/nf_conntrack_proto_tcp.c (ffffffff819a546d)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_proto_tcp.c:nlattr_to_tcp
  - net/netfilter/nf_conntrack_proto_tcp.c:tcp_to_nlattr
  - net/netfilter/nf_conntrack_proto_tcp.c:tcp_to_nlattr
  - net/netfilter/nf_conntrack_proto_tcp.c:nf_conntrack_tcp_packet
  - net/netfilter/nf_conntrack_proto_tcp.c:nf_conntrack_tcp_packet
  - net/netfilter/nf_conntrack_proto_tcp.c:nf_conntrack_tcp_packet
  - net/netfilter/nf_conntrack_proto_tcp.c:nf_conntrack_tcp_packet
  - net/netfilter/nf_conntrack_proto_tcp.c:nf_conntrack_tcp_packet
  - net/netfilter/nf_conntrack_proto_tcp.c:nf_conntrack_tcp_packet
  - net/netfilter/nf_conntrack_proto_tcp.c:nf_conntrack_tcp_packet
  - net/netfilter/nf_conntrack_proto_tcp.c:nf_conntrack_tcp_packet
```
```
In net/netfilter/nf_conntrack_seqadj.c (ffffffff819a82d4)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_seqadj.c:nf_ct_seq_adjust
  - net/netfilter/nf_conntrack_seqadj.c:nf_ct_seqadj_set
```
```
In net/netfilter/nf_conntrack_ecache.c (ffffffff819a9076)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_ecache.c:nf_ct_deliver_cached_events
  - net/netfilter/nf_conntrack_ecache.c:nf_conntrack_eventmask_report
```
```
In net/netfilter/nf_conntrack_proto_dccp.c (ffffffff819a9a1f)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_proto_dccp.c:nlattr_to_dccp
  - net/netfilter/nf_conntrack_proto_dccp.c:dccp_to_nlattr
  - net/netfilter/nf_conntrack_proto_dccp.c:dccp_to_nlattr
  - net/netfilter/nf_conntrack_proto_dccp.c:nf_conntrack_dccp_packet
  - net/netfilter/nf_conntrack_proto_dccp.c:nf_conntrack_dccp_packet
  - net/netfilter/nf_conntrack_proto_dccp.c:nf_conntrack_dccp_packet
```
```
In net/netfilter/nf_conntrack_proto_sctp.c (ffffffff819aa820)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_proto_sctp.c:nlattr_to_sctp
  - net/netfilter/nf_conntrack_proto_sctp.c:sctp_to_nlattr
  - net/netfilter/nf_conntrack_proto_sctp.c:sctp_to_nlattr
  - net/netfilter/nf_conntrack_proto_sctp.c:nf_conntrack_sctp_packet
  - net/netfilter/nf_conntrack_proto_sctp.c:nf_conntrack_sctp_packet
```
```
In net/netfilter/nf_conntrack_proto_gre.c (ffffffff819ab53a)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_proto_gre.c:nf_ct_gre_keymap_destroy
  - net/netfilter/nf_conntrack_proto_gre.c:nf_ct_gre_keymap_add
  - net/netfilter/nf_conntrack_proto_gre.c:nf_ct_gre_keymap_flush
```
```
In net/netfilter/nf_conntrack_netlink.c (ffffffff819b1083)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_new_expect
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_new_expect
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_del_expect
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_change_seq_adj
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_change_seq_adj
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_dump_list
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_dump_list
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_dump_ct_seq_adj
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_dump_ct_seq_adj
```
```
In net/ipv4/route.c (ffffffff819b4c8a)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_flush_dev
  - net/ipv4/route.c:ipv4_dst_destroy
  - net/ipv4/route.c:rt_add_uncached_list
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/inetpeer.c (ffffffff819b7d64)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/inet_hashtables.c (ffffffff819c43d8)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_unhash
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819c6262)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp.c (ffffffff819ca524)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_ioctl
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819e421e)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_seq_stop
  - net/ipv4/tcp_ipv4.c:established_get_next
```
```
In net/ipv4/tcp_metrics.c (ffffffff819e8f2d)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_flush_all
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/raw.c (ffffffff819ed2ab)
Location: include/linux/spinlock.h:381
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819ef0c0)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_seq_stop
  - net/ipv4/udp.c:udp_get_next
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/af_inet.c (ffffffff819fe016)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_register_protosw
```
```
In net/ipv4/igmp.c (ffffffff81a00ba7)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_mcf_seq_stop
  - net/ipv4/igmp.c:igmp_mcf_seq_next
  - net/ipv4/igmp.c:igmp_mcf_seq_start
  - net/ipv4/igmp.c:ip_mc_clear_src
  - net/ipv4/igmp.c:ip_mc_add_src
  - net/ipv4/igmp.c:ip_mc_del_src
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:igmpv3_clear_delrec
  - net/ipv4/igmp.c:igmpv3_clear_delrec
  - net/ipv4/igmp.c:igmpv3_del_delrec
  - net/ipv4/igmp.c:igmpv3_del_delrec
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:igmp_stop_timer
```
```
In net/ipv4/fib_semantics.c (ffffffff81a0a4d0)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_release_info
```
```
In net/ipv4/inet_fragment.c (ffffffff81a10139)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frags_free_cb
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81a1798e)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
```
In net/ipv4/ipmr.c (ffffffff81a1cae3)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:mr_mfc_seq_stop
```
```
In net/ipv4/ipmr_base.c (ffffffff81a1f005)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_table_dump
  - net/ipv4/ipmr_base.c:mr_table_dump
  - net/ipv4/ipmr_base.c:mr_mfc_seq_next
```
```
In net/ipv4/tcp_bpf.c (ffffffff81a22de3)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_init
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81a23865)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_invalidate
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a2b204)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:__xfrm_sk_clone_policy
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_policy_walk
  - net/xfrm/xfrm_policy.c:xfrm_policy_flush
  - net/xfrm/xfrm_policy.c:xfrm_policy_flush
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff81a2f1fa)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_unregister_afinfo
  - net/xfrm/xfrm_state.c:xfrm_state_register_afinfo
  - net/xfrm/xfrm_state.c:xfrm_unregister_km
  - net/xfrm/xfrm_state.c:xfrm_register_km
  - net/xfrm/xfrm_state.c:xfrm_state_walk
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_find_acq_byseq
  - net/xfrm/xfrm_state.c:xfrm_find_acq
  - net/xfrm/xfrm_state.c:xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_state_lookup_byspi
  - net/xfrm/xfrm_state.c:xfrm_state_lookup_byspi
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_sad_getinfo
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_delete
  - net/xfrm/xfrm_state.c:xfrm_state_gc_task
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_input.c (ffffffff81a3545e)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo
  - net/xfrm/xfrm_input.c:xfrm_input_register_afinfo
```
```
In net/xfrm/xfrm_output.c (ffffffff81a3776f)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/af_inet6.c (ffffffff81a3f38b)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_register_protosw
```
```
In net/ipv6/addrconf.c (ffffffff81a5208c)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_start
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:ipv6_generate_stable_address
  - net/ipv6/addrconf.c:add_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/route.c (ffffffff81a55674)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_del_rt
  - net/ipv6/route.c:fib6_table_lookup
  - net/ipv6/route.c:fib6_nh_remove_exception
  - net/ipv6/route.c:fib6_nh_flush_exceptions
  - net/ipv6/route.c:rt6_insert_exception
  - net/ipv6/route.c:rt6_insert_exception
  - net/ipv6/route.c:__ip6_ins_rt
  - net/ipv6/route.c:rt6_uncached_list_add
```
```
In net/ipv6/ip6_fib.c (ffffffff81a5ea46)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:__fib6_clean_all
  - net/ipv6/ip6_fib.c:fib6_update_sernum_stub
  - net/ipv6/ip6_fib.c:fib6_tables_dump
```
```
In net/ipv6/raw.c (ffffffff81a6d89b)
Location: include/linux/spinlock.h:381
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff81a714e7)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mcf_seq_stop
  - net/ipv6/mcast.c:igmp6_mcf_seq_next
  - net/ipv6/mcast.c:igmp6_mcf_seq_start
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:ip6_mc_del_src
  - net/ipv6/mcast.c:ip6_mc_del_src
  - net/ipv6/mcast.c:mld_send_report
  - net/ipv6/mcast.c:mld_send_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:mld_del_delrec
  - net/ipv6/mcast.c:mld_del_delrec
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/mcast.c:igmp6_group_added
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81a8002d)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:fl6_renew
  - net/ipv6/ip6_flowlabel.c:fl6_free_socklist
  - net/ipv6/ip6_flowlabel.c:fl6_free_socklist
  - net/ipv6/ip6_flowlabel.c:fl_release
```
```
In net/ipv6/ip6mr.c (ffffffff81a84f6b)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:mr_mfc_seq_stop
```
```
In net/ipv6/calipso.c (ffffffff81a8c6ec)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_cache_invalidate
```
```
In net/ipv6/netfilter/nf_conntrack_reasm.c (ffffffff81a91334)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv6/netfilter/nf_conntrack_reasm.c:nf_ct_frag6_gather
```
```
In net/packet/af_packet.c (ffffffff81a99e60)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_getsockopt
```
```
In net/dcb/dcbnl.c (ffffffff81aa876b)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_ieee_getapp_default_prio_mask
  - net/dcb/dcbnl.c:dcb_ieee_getapp_dscp_prio_mask_map
  - net/dcb/dcbnl.c:dcb_ieee_getapp_prio_dscp_mask_map
  - net/dcb/dcbnl.c:dcb_ieee_delapp
  - net/dcb/dcbnl.c:dcb_ieee_setapp
  - net/dcb/dcbnl.c:dcb_ieee_getapp_mask
  - net/dcb/dcbnl.c:dcb_setapp
  - net/dcb/dcbnl.c:dcb_getapp
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
```
```
In net/switchdev/switchdev.c (ffffffff81aacf58)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_deferred_process
```
```
In net/xdp/xsk.c (ffffffff81ab645c)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xsk.c:xsk_generic_rcv
  - net/xdp/xsk.c:xsk_generic_rcv
```
```
In lib/xarray.c (ffffffff81ac9172)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - lib/xarray.c:__xas_nomem
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
In kernel/cgroup/cgroup.c (ffffffff81161f68)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_idr_remove
  - kernel/cgroup/cgroup.c:cgroup_idr_replace
```
```
In kernel/bpf/core.c (ffffffff811e1e4a)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
```
```
In kernel/bpf/syscall.c (ffffffff811e66f9)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_obj_get_next_id
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_map_inc_not_zero
  - kernel/bpf/syscall.c:map_create
```
```
In kernel/bpf/local_storage.c (ffffffff811fe403)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_unlink
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_link
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_release
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_assign
  - kernel/bpf/local_storage.c:cgroup_storage_get_next_key
  - kernel/bpf/local_storage.c:cgroup_storage_get_next_key
  - kernel/bpf/local_storage.c:cgroup_storage_lookup
  - kernel/bpf/local_storage.c:cgroup_storage_lookup
```
```
In kernel/bpf/btf.c (ffffffff81202fb9)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
```
```
In kernel/bpf/xskmap.c (ffffffff81205fed)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - kernel/bpf/xskmap.c:xsk_map_try_sock_delete
  - kernel/bpf/xskmap.c:xsk_map_delete_elem
  - kernel/bpf/xskmap.c:xsk_map_update_elem
  - kernel/bpf/xskmap.c:xsk_map_update_elem
  - kernel/bpf/xskmap.c:xsk_map_update_elem
  - kernel/bpf/xskmap.c:xsk_map_sock_delete
```
```
In kernel/bpf/reuseport_array.c (ffffffff8120bde1)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem
  - kernel/bpf/reuseport_array.c:reuseport_array_delete_elem
```
```
In kernel/padata.c (ffffffff812225ec)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - kernel/padata.c:padata_reorder
```
```
In mm/page-writeback.c (ffffffff81230b31)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - mm/page-writeback.c:bdi_set_max_ratio
  - mm/page-writeback.c:bdi_set_min_ratio
```
```
In mm/backing-dev.c (ffffffff8124f0b6)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:bdi_get_by_id
  - mm/backing-dev.c:wb_wakeup_delayed
```
```
In fs/fs-writeback.c (ffffffff8131cb49)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_queue_work
  - fs/fs-writeback.c:wb_wakeup
```
```
In security/selinux/netif.c (ffffffff81475715)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_netdev_notifier_handler
  - security/selinux/netif.c:sel_netif_flush
  - security/selinux/netif.c:sel_netif_sid
```
```
In security/selinux/netnode.c (ffffffff81475d63)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_flush
  - security/selinux/netnode.c:sel_netnode_sid
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (ffffffff81476033)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_flush
  - security/selinux/netport.c:sel_netport_sid
  - security/selinux/netport.c:sel_netport_sid
```
```
In block/genhd.c (ffffffff81506792)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - block/genhd.c:get_gendisk
```
```
In block/blk-cgroup.c (ffffffff81518655)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - block/blk-cgroup.c:__blkcg_punt_bio_submit
  - block/blk-cgroup.c:blkg_async_bio_workfn
```
```
In drivers/connector/cn_queue.c (ffffffff8170296f)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_free_dev
  - drivers/connector/cn_queue.c:cn_queue_del_callback
  - drivers/connector/cn_queue.c:cn_queue_add_callback
```
```
In drivers/connector/connector.c (ffffffff81702a92)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_proc_show
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/net/tun.c (ffffffff817cfe27)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_set_ebpf
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_flow_update
  - drivers/net/tun.c:tun_flow_flush
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817d64ab)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_disconnect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_disconnect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_ccp_closed
  - drivers/net/ppp/ppp_generic.c:ppp_ccp_closed
  - drivers/net/ppp/ppp_generic.c:ppp_set_compress
  - drivers/net/ppp/ppp_generic.c:ppp_set_compress
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_input_error
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_dev_uninit
  - drivers/net/ppp/ppp_generic.c:ppp_dev_uninit
  - drivers/net/ppp/ppp_generic.c:ppp_get_stats64
  - drivers/net/ppp/ppp_generic.c:ppp_get_stats64
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_poll
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - drivers/net/ppp/ppp_generic.c:ppp_read
```
```
In drivers/net/xen-netfront.c (ffffffff817ded94)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:netback_changed
```
```
In net/core/sock.c (ffffffff81927057)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/sock.c:release_sock
  - net/core/sock.c:__sk_flush_backlog
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__lock_sock
```
```
In net/core/request_sock.c (ffffffff81928e6f)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/core/datagram.c (ffffffff81933436)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/datagram.c:__sk_queue_drop_skb
```
```
In net/core/gen_stats.c (ffffffff81935f03)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/gen_stats.c:gnet_stats_finish_copy
  - net/core/gen_stats.c:gnet_stats_finish_copy
  - net/core/gen_stats.c:gnet_stats_copy_queue
  - net/core/gen_stats.c:gnet_stats_copy_rate_est
  - net/core/gen_stats.c:___gnet_stats_copy_basic
```
```
In net/core/gen_estimator.c (ffffffff819362c5)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/net_namespace.c (ffffffff8193791e)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:peernet2id
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/dev.c (ffffffff81949867)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/dev.c:dev_set_rx_mode
  - net/core/dev.c:netif_set_real_num_tx_queues
```
```
In net/core/dev_addr_lists.c (ffffffff8195221a)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:dev_mc_flush
  - net/core/dev_addr_lists.c:__dev_mc_del
  - net/core/dev_addr_lists.c:__dev_mc_add
  - net/core/dev_addr_lists.c:dev_mc_add_excl
  - net/core/dev_addr_lists.c:dev_uc_flush
  - net/core/dev_addr_lists.c:dev_uc_del
  - net/core/dev_addr_lists.c:dev_uc_add
  - net/core/dev_addr_lists.c:dev_uc_add_excl
```
```
In net/core/neighbour.c (ffffffff81958f92)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/core/rtnetlink.c (ffffffff8195f313)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_fdb_dump
```
```
In net/core/sock_reuseport.c (ffffffff81974292)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_attach_prog
  - net/core/sock_reuseport.c:reuseport_detach_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_alloc
  - net/core/sock_reuseport.c:reuseport_alloc
```
```
In net/core/page_pool.c (ffffffff8197a6af)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
```
```
In net/core/net-procfs.c (ffffffff8197b192)
Location: include/linux/spinlock.h:381
Inline: True
```
```
In net/core/skmsg.c (ffffffff8197cc6f)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_link_pop
```
```
In net/core/sock_map.c (ffffffff8198cea8)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_unref
```
```
In net/core/devlink.c (ffffffff819961af)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_port_type_set
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
```
```
In net/sched/sch_generic.c (ffffffff819a1d97)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_graft_qdisc
```
```
In net/sched/sch_mq.c (ffffffff819a24ad)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump
```
```
In net/sched/sch_api.c (ffffffff819a414b)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/sched/sch_api.c:tcf_node_bind
  - net/sched/sch_api.c:qdisc_class_hash_grow
```
```
In net/ipv4/route.c (ffffffff819be3ca)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_flush_dev
  - net/ipv4/route.c:ipv4_dst_destroy
  - net/ipv4/route.c:rt_add_uncached_list
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/inetpeer.c (ffffffff819c15e9)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/inet_hashtables.c (ffffffff819cde61)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_unhash
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819cfd48)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp.c (ffffffff819d4094)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_ioctl
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819eb0fe)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_seq_stop
  - net/ipv4/tcp_ipv4.c:established_get_next
```
```
In net/ipv4/tcp_metrics.c (ffffffff819f2c8d)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_flush_all
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/raw.c (ffffffff819f718b)
Location: include/linux/spinlock.h:381
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819f98b0)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_seq_stop
  - net/ipv4/udp.c:udp_get_next
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/af_inet.c (ffffffff81a083a6)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_register_protosw
```
```
In net/ipv4/igmp.c (ffffffff81a0b1f7)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_mcf_seq_stop
  - net/ipv4/igmp.c:igmp_mcf_seq_next
  - net/ipv4/igmp.c:igmp_mcf_seq_start
  - net/ipv4/igmp.c:ip_mc_clear_src
  - net/ipv4/igmp.c:ip_mc_add_src
  - net/ipv4/igmp.c:ip_mc_del_src
  - net/ipv4/igmp.c:igmp_group_added
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:__igmp_group_dropped
  - net/ipv4/igmp.c:igmpv3_clear_delrec
  - net/ipv4/igmp.c:igmpv3_clear_delrec
  - net/ipv4/igmp.c:igmpv3_del_delrec
  - net/ipv4/igmp.c:igmpv3_del_delrec
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_heard_query
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:igmp_stop_timer
```
```
In net/ipv4/fib_semantics.c (ffffffff81a14cb0)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_release_info
```
```
In net/ipv4/inet_fragment.c (ffffffff81a1a989)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frags_free_cb
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81a2242e)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
```
In net/ipv4/ipmr.c (ffffffff81a27d14)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:mr_mfc_seq_stop
```
```
In net/ipv4/ipmr_base.c (ffffffff81a2a4c5)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_table_dump
  - net/ipv4/ipmr_base.c:mr_table_dump
  - net/ipv4/ipmr_base.c:mr_mfc_seq_next
```
```
In net/ipv4/tcp_bpf.c (ffffffff81a2e1c2)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_init
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81a2ec45)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_invalidate
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a36834)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:__xfrm_sk_clone_policy
  - net/xfrm/xfrm_policy.c:xfrm_sk_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_policy_walk
  - net/xfrm/xfrm_policy.c:xfrm_policy_flush
  - net/xfrm/xfrm_policy.c:xfrm_policy_flush
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff81a3ab4a)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_unregister_afinfo
  - net/xfrm/xfrm_state.c:xfrm_state_register_afinfo
  - net/xfrm/xfrm_state.c:xfrm_unregister_km
  - net/xfrm/xfrm_state.c:xfrm_register_km
  - net/xfrm/xfrm_state.c:xfrm_state_walk
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_find_acq_byseq
  - net/xfrm/xfrm_state.c:xfrm_find_acq
  - net/xfrm/xfrm_state.c:xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_state_lookup_byspi
  - net/xfrm/xfrm_state.c:xfrm_state_lookup_byspi
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_sad_getinfo
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_delete
  - net/xfrm/xfrm_state.c:xfrm_state_gc_task
  - net/xfrm/xfrm_state.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_input.c (ffffffff81a40d3e)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo
  - net/xfrm/xfrm_input.c:xfrm_input_register_afinfo
```
```
In net/xfrm/xfrm_output.c (ffffffff81a4311f)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/af_inet6.c (ffffffff81a4ae8b)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_register_protosw
```
```
In net/ipv6/addrconf.c (ffffffff81a5dfdc)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_start
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:ipv6_generate_stable_address
  - net/ipv6/addrconf.c:add_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/route.c (ffffffff81a61674)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_del_rt
  - net/ipv6/route.c:fib6_table_lookup
  - net/ipv6/route.c:fib6_nh_remove_exception
  - net/ipv6/route.c:fib6_nh_flush_exceptions
  - net/ipv6/route.c:rt6_insert_exception
  - net/ipv6/route.c:rt6_insert_exception
  - net/ipv6/route.c:__ip6_ins_rt
  - net/ipv6/route.c:rt6_uncached_list_add
```
```
In net/ipv6/ip6_fib.c (ffffffff81a6aec6)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:__fib6_clean_all
  - net/ipv6/ip6_fib.c:fib6_update_sernum_stub
  - net/ipv6/ip6_fib.c:fib6_tables_dump
```
```
In net/ipv6/raw.c (ffffffff81a79ebb)
Location: include/linux/spinlock.h:381
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff81a7daf7)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mcf_seq_stop
  - net/ipv6/mcast.c:igmp6_mcf_seq_next
  - net/ipv6/mcast.c:igmp6_mcf_seq_start
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:ip6_mc_del_src
  - net/ipv6/mcast.c:ip6_mc_del_src
  - net/ipv6/mcast.c:mld_send_report
  - net/ipv6/mcast.c:mld_send_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:mld_del_delrec
  - net/ipv6/mcast.c:mld_del_delrec
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/mcast.c:igmp6_group_added
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81a8c9dd)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:fl6_renew
  - net/ipv6/ip6_flowlabel.c:fl6_free_socklist
  - net/ipv6/ip6_flowlabel.c:fl6_free_socklist
  - net/ipv6/ip6_flowlabel.c:fl_release
```
```
In net/ipv6/ip6mr.c (ffffffff81a91b56)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:mr_mfc_seq_stop
```
```
In net/ipv6/calipso.c (ffffffff81a9947a)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_cache_invalidate
```
```
In net/packet/af_packet.c (ffffffff81aa6b8f)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_getsockopt
```
```
In net/dcb/dcbnl.c (ffffffff81ab4adb)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_ieee_getapp_default_prio_mask
  - net/dcb/dcbnl.c:dcb_ieee_getapp_dscp_prio_mask_map
  - net/dcb/dcbnl.c:dcb_ieee_getapp_prio_dscp_mask_map
  - net/dcb/dcbnl.c:dcb_ieee_delapp
  - net/dcb/dcbnl.c:dcb_ieee_setapp
  - net/dcb/dcbnl.c:dcb_ieee_getapp_mask
  - net/dcb/dcbnl.c:dcb_setapp
  - net/dcb/dcbnl.c:dcb_getapp
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
```
```
In net/switchdev/switchdev.c (ffffffff81ab92c8)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_deferred_process
```
```
In net/xdp/xsk.c (ffffffff81ac257c)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xsk.c:xsk_generic_rcv
  - net/xdp/xsk.c:xsk_generic_rcv
```
```
In lib/xarray.c (ffffffff81ad5653)
Location: include/linux/spinlock.h:381
Inline: True
Inline callers:
  - lib/xarray.c:__xas_nomem
```
</details>
</li>
</ul>

## Differences
