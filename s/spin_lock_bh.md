# Function: <code>spin_lock_bh</code>

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
In kernel/cgroup.c (ffffffff81112a62)
Location: include/linux/spinlock.h:305
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
In mm/page-writeback.c (ffffffff81197e6c)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - mm/page-writeback.c:bdi_set_max_ratio
  - mm/page-writeback.c:bdi_set_min_ratio
```
```
In mm/backing-dev.c (ffffffff811ae17b)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_shutdown
  - mm/backing-dev.c:bdi_register
  - mm/backing-dev.c:wb_wakeup_delayed
  - mm/backing-dev.c:bdi_unregister
```
```
In fs/fs-writeback.c (ffffffff81235cab)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_wakeup
  - fs/fs-writeback.c:wb_queue_work
  - fs/fs-writeback.c:wb_workfn
```
```
In security/selinux/netif.c (ffffffff8134cdef)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_netdev_notifier_handler
  - security/selinux/netif.c:sel_netif_sid
  - security/selinux/netif.c:sel_netif_flush
```
```
In security/selinux/netnode.c (ffffffff8134d17f)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_sid
  - security/selinux/netnode.c:sel_netnode_flush
```
```
In security/selinux/netport.c (ffffffff8134d43c)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_sid
  - security/selinux/netport.c:sel_netport_flush
```
```
In crypto/chainiv.c (ffffffff813a1eea)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - crypto/chainiv.c:chainiv_givencrypt
  - crypto/chainiv.c:async_chainiv_givencrypt
  - crypto/chainiv.c:async_chainiv_do_postponed
```
```
In block/genhd.c (ffffffff813caae2)
Location: include/linux/spinlock.h:305
Inline: True
```
```
In lib/rhashtable.c (ffffffff8140053a)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - lib/rhashtable.c:rht_deferred_worker
```
```
In drivers/connector/cn_queue.c (ffffffff815417d0)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_add_callback
  - drivers/connector/cn_queue.c:cn_queue_del_callback
  - drivers/connector/cn_queue.c:cn_queue_free_dev
```
```
In drivers/connector/connector.c (ffffffff81541af1)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_proc_show
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/net/tun.c (ffffffff815ee01b)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_flow_flush
  - drivers/net/tun.c:tun_flow_cleanup
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:__tun_detach
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff815f4b8b)
Location: include/linux/spinlock.h:305
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
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
```
In drivers/net/xen-netfront.c (ffffffff815fc2fe)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:netback_changed
  - drivers/net/xen-netfront.c:xennet_open
```
```
In net/core/sock.c (ffffffff81700f9d)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/core/sock.c:__lock_sock
  - net/core/sock.c:lock_sock_nested
  - net/core/sock.c:release_sock
```
```
In net/core/request_sock.c (ffffffff81704c25)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/core/datagram.c (ffffffff8170dda0)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/core/datagram.c:skb_kill_datagram
```
```
In net/core/gen_stats.c (ffffffff8170ef5d)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/core/gen_stats.c:gnet_stats_start_copy_compat
```
```
In net/core/gen_estimator.c (ffffffff8170f643)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_kill_estimator
  - net/core/gen_estimator.c:gen_estimator_active
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/dev.c (ffffffff81715ac9)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:dev_set_rx_mode
```
```
In net/core/dev_addr_lists.c (ffffffff8172283b)
Location: include/linux/spinlock.h:305
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
In net/core/dst.c (ffffffff817239b1)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/core/dst.c:dst_dev_event
  - net/core/dst.c:__dst_free
  - net/core/dst.c:dst_gc_task
```
```
In net/core/neighbour.c (ffffffff81728848)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_update
```
```
In net/core/rtnetlink.c (ffffffff8172d8bf)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_fdb_dump
```
```
In net/core/flow.c (ffffffff81734580)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_gc_task
```
```
In net/core/net-procfs.c (ffffffff81737970)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/core/net-procfs.c:dev_mc_seq_show
```
```
In net/sched/sch_generic.c (ffffffff81740cda)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_graft_qdisc
  - net/sched/sch_generic.c:dev_deactivate_many
```
```
In net/sched/sch_mq.c (ffffffff81742217)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump
```
```
In net/sched/sch_api.c (ffffffff8174463e)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_grow
```
```
In net/sched/cls_api.c (ffffffff81745ea3)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_change
```
```
In net/sched/act_api.c (ffffffff81746c2b)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_hash_lookup
  - net/sched/act_api.c:tcf_hash_insert
```
```
In net/netlink/af_netlink.c (ffffffff8174a695)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_set_ring
  - net/netlink/af_netlink.c:__netlink_sendskb
  - net/netlink/af_netlink.c:__netlink_alloc_skb
  - net/netlink/af_netlink.c:netlink_poll
  - net/netlink/af_netlink.c:netlink_poll
  - net/netlink/af_netlink.c:netlink_insert
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/route.c (ffffffff81752fa5)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_add_uncached_list
  - net/ipv4/route.c:ipv4_dst_destroy
  - net/ipv4/route.c:rt_set_nexthop
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:rt_flush_dev
```
```
In net/ipv4/inetpeer.c (ffffffff81757d26)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inetpeer_gc_worker
  - net/ipv4/inetpeer.c:inetpeer_gc_worker
  - net/ipv4/inetpeer.c:inetpeer_inval_rcu
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
```
```
In net/ipv4/ip_sockglue.c (ffffffff817607a3)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_ra_control
```
```
In net/ipv4/inet_hashtables.c (ffffffff81762037)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81764cd3)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8177b99f)
Location: include/linux/spinlock.h:305
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff81780dd3)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_flush_all
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
```
```
In net/ipv4/raw.c (ffffffff81784bb4)
Location: include/linux/spinlock.h:305
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81785e5f)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_unhash
  - net/ipv4/udp.c:first_packet_length
```
```
In net/ipv4/af_inet.c (ffffffff81792eb3)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_register_protosw
```
```
In net/ipv4/igmp.c (ffffffff817951ab)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
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
```
```
In net/ipv4/fib_semantics.c (ffffffff8179c42d)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/inet_fragment.c (ffffffff817a1bb9)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_worker
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff817a55ec)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
```
In net/ipv4/ipmr.c (ffffffff817a7af6)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_seq_next
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
```
```
In net/ipv4/cipso_ipv4.c (ffffffff817ad84e)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_invalidate
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff817b387d)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
```
```
In net/xfrm/xfrm_state.c (ffffffff817b6c0b)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_sad_getinfo
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
In net/xfrm/xfrm_input.c (ffffffff817bb6a3)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input_register_afinfo
  - net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo
```
```
In net/xfrm/xfrm_output.c (ffffffff817bc45b)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/af_inet6.c (ffffffff817c3063)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_register_protosw
```
```
In net/ipv6/addrconf.c (ffffffff817c96c9)
Location: include/linux/spinlock.h:305
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
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_cleanup
```
```
In net/ipv6/route.c (ffffffff817d52cf)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_dst_destroy
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:icmp6_dst_gc
  - net/ipv6/route.c:rt6_ifdown
  - net/ipv6/route.c:rt6_ifdown
```
```
In net/ipv6/ip6_fib.c (ffffffff817dbfd4)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_run_gc
```
```
In net/ipv6/raw.c (ffffffff817e5ac4)
Location: include/linux/spinlock.h:305
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff817e9380)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mcf_seq_next
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
In net/ipv6/ip6_flowlabel.c (ffffffff817f5e3d)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:fl_release
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6_flowlabel.c:fl6_renew
  - net/ipv6/ip6_flowlabel.c:fl6_free_socklist
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
```
```
In net/ipv6/ip6mr.c (ffffffff817f88c4)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ipmr_mfc_seq_next
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
```
In net/packet/af_packet.c (ffffffff818031e4)
Location: include/linux/spinlock.h:305
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
In net/dcb/dcbnl.c (ffffffff81812a9f)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_getapp
  - net/dcb/dcbnl.c:dcb_ieee_getapp_mask
  - net/dcb/dcbnl.c:dcb_setapp
  - net/dcb/dcbnl.c:dcb_ieee_setapp
  - net/dcb/dcbnl.c:dcb_ieee_delapp
  - net/dcb/dcbnl.c:dcbnl_cee_fill
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
In kernel/cgroup.c (ffffffff8111a2b5)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - kernel/cgroup.c:css_release_work_fn
  - kernel/cgroup.c:css_free_work_fn
  - kernel/cgroup.c:cgroup_idr_replace
```
```
In mm/page-writeback.c (ffffffff811acdcc)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - mm/page-writeback.c:bdi_set_max_ratio
  - mm/page-writeback.c:bdi_set_min_ratio
```
```
In mm/backing-dev.c (ffffffff811c8bf3)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:bdi_register
  - mm/backing-dev.c:wb_wakeup_delayed
```
```
In fs/fs-writeback.c (ffffffff8126466f)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_queue_work
  - fs/fs-writeback.c:wb_wakeup
```
```
In security/selinux/netif.c (ffffffff81382d9f)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_netdev_notifier_handler
  - security/selinux/netif.c:sel_netif_flush
  - security/selinux/netif.c:sel_netif_sid
```
```
In security/selinux/netnode.c (ffffffff81383306)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_flush
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (ffffffff81383586)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_flush
  - security/selinux/netport.c:sel_netport_sid
```
```
In security/apparmor/policy_unpack.c (ffffffff813bc0af)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In block/genhd.c (ffffffff8140edb2)
Location: include/linux/spinlock.h:305
Inline: True
```
```
In lib/rhashtable.c (ffffffff81447fe6)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - lib/rhashtable.c:rht_deferred_worker
```
```
In drivers/connector/cn_queue.c (ffffffff815932fd)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_free_dev
  - drivers/connector/cn_queue.c:cn_queue_del_callback
  - drivers/connector/cn_queue.c:cn_queue_add_callback
```
```
In drivers/connector/connector.c (ffffffff81593438)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_proc_show
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/net/tun.c (ffffffff8164df92)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_flow_cleanup
  - drivers/net/tun.c:tun_flow_flush
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81655757)
Location: include/linux/spinlock.h:305
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
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_poll
  - drivers/net/ppp/ppp_generic.c:ppp_read
```
```
In drivers/net/xen-netfront.c (ffffffff8165d1e7)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:netback_changed
  - drivers/net/xen-netfront.c:xennet_open
```
```
In net/core/sock.c (ffffffff8176950b)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/core/sock.c:release_sock
  - net/core/sock.c:lock_sock_nested
  - net/core/sock.c:__sk_flush_backlog
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__lock_sock
```
```
In net/core/request_sock.c (ffffffff8176b815)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/core/datagram.c (ffffffff817754c0)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/core/datagram.c:skb_kill_datagram
```
```
In net/core/gen_stats.c (ffffffff817767d2)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/core/gen_stats.c:gnet_stats_start_copy_compat
```
```
In net/core/gen_estimator.c (ffffffff81776ffb)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_estimator_active
  - net/core/gen_estimator.c:gen_kill_estimator
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/dev.c (ffffffff817862bc)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/core/dev.c:dev_set_rx_mode
  - net/core/dev.c:netif_set_real_num_tx_queues
```
```
In net/core/dev_addr_lists.c (ffffffff8178c2cb)
Location: include/linux/spinlock.h:305
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
In net/core/dst.c (ffffffff8178d409)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/core/dst.c:dst_dev_event
  - net/core/dst.c:__dst_free
  - net/core/dst.c:dst_gc_task
```
```
In net/core/neighbour.c (ffffffff81792398)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_update
```
```
In net/core/rtnetlink.c (ffffffff8179713d)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_fdb_dump
```
```
In net/core/sock_reuseport.c (ffffffff8179feaf)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_attach_prog
  - net/core/sock_reuseport.c:reuseport_detach_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_alloc
```
```
In net/core/flow.c (ffffffff817a0e15)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_gc_task
```
```
In net/core/net-procfs.c (ffffffff817a3c20)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/core/net-procfs.c:dev_mc_seq_show
```
```
In net/sched/sch_generic.c (ffffffff817aec5a)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_graft_qdisc
```
```
In net/sched/sch_mq.c (ffffffff817af0a7)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump
```
```
In net/sched/sch_api.c (ffffffff817b09ae)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_grow
```
```
In net/sched/cls_api.c (ffffffff817b2ef8)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_change
```
```
In net/sched/act_api.c (ffffffff817b4036)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_hash_insert
  - net/sched/act_api.c:tcf_hash_lookup
```
```
In net/netlink/af_netlink.c (ffffffff817ba013)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/ipv4/route.c (ffffffff817c3d16)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_flush_dev
  - net/ipv4/route.c:ipv4_dst_destroy
  - net/ipv4/route.c:rt_add_uncached_list
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/inetpeer.c (ffffffff817c423b)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
  - net/ipv4/inetpeer.c:inetpeer_inval_rcu
  - net/ipv4/inetpeer.c:inetpeer_gc_worker
  - net/ipv4/inetpeer.c:inetpeer_gc_worker
```
```
In net/ipv4/ip_sockglue.c (ffffffff817ccac3)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_ra_control
```
```
In net/ipv4/inet_hashtables.c (ffffffff817cf3fb)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_unhash
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff817cf821)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:__inet_twsk_hashdance
```
```
In net/ipv4/inet_connection_sock.c (ffffffff817d124b)
Location: include/linux/spinlock.h:305
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
In net/ipv4/tcp_ipv4.c (ffffffff817e9209)
Location: include/linux/spinlock.h:305
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff817ee4ce)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_flush_all
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/raw.c (ffffffff817f2134)
Location: include/linux/spinlock.h:305
Inline: True
```
```
In net/ipv4/udp.c (ffffffff817f3f1a)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_lib_unhash
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/af_inet.c (ffffffff81800673)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_register_protosw
```
```
In net/ipv4/igmp.c (ffffffff818035c3)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
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
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:igmp_stop_timer
```
```
In net/ipv4/fib_semantics.c (ffffffff8180a4e0)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_release_info
```
```
In net/ipv4/inet_fragment.c (ffffffff8180f879)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_worker
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff8181327c)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
```
In net/ipv4/ipmr.c (ffffffff81815948)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_seq_next
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
```
```
In net/ipv4/cipso_ipv4.c (ffffffff8181aab2)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_invalidate
```
```
In net/xfrm/xfrm_policy.c (ffffffff8182108d)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
```
```
In net/xfrm/xfrm_state.c (ffffffff818281bb)
Location: include/linux/spinlock.h:305
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
In net/xfrm/xfrm_input.c (ffffffff81828635)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo
  - net/xfrm/xfrm_input.c:xfrm_input_register_afinfo
```
```
In net/xfrm/xfrm_output.c (ffffffff8182936f)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/af_inet6.c (ffffffff818300d3)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_register_protosw
```
```
In net/ipv6/addrconf.c (ffffffff8183fe3e)
Location: include/linux/spinlock.h:305
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
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/route.c (ffffffff81846e9a)
Location: include/linux/spinlock.h:305
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
In net/ipv6/ip6_fib.c (ffffffff81849f8e)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_run_gc
```
```
In net/ipv6/raw.c (ffffffff81853cb4)
Location: include/linux/spinlock.h:305
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff81857cc2)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mcf_seq_next
  - net/ipv6/mcast.c:igmp6_mcf_seq_start
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:ip6_mc_add_src
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
In net/ipv6/ip6_flowlabel.c (ffffffff818651ba)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
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
In net/ipv6/ip6mr.c (ffffffff81868d5f)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ipmr_mfc_seq_next
```
```
In net/ipv6/calipso.c (ffffffff81870787)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_cache_invalidate
```
```
In net/packet/af_packet.c (ffffffff81875db0)
Location: include/linux/spinlock.h:305
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
In net/dcb/dcbnl.c (ffffffff818864eb)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_ieee_delapp
  - net/dcb/dcbnl.c:dcb_ieee_setapp
  - net/dcb/dcbnl.c:dcb_ieee_getapp_mask
  - net/dcb/dcbnl.c:dcb_setapp
  - net/dcb/dcbnl.c:dcb_getapp
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
```
```
In net/switchdev/switchdev.c (ffffffff8188a7cb)
Location: include/linux/spinlock.h:305
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
In kernel/cgroup.c (ffffffff8112216a)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - kernel/cgroup.c:css_release_work_fn
  - kernel/cgroup.c:css_free_work_fn
  - kernel/cgroup.c:cgroup_idr_replace
```
```
In mm/page-writeback.c (ffffffff811bd32c)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - mm/page-writeback.c:bdi_set_max_ratio
  - mm/page-writeback.c:bdi_set_min_ratio
```
```
In mm/backing-dev.c (ffffffff811d8d13)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:bdi_register
  - mm/backing-dev.c:wb_wakeup_delayed
```
```
In fs/fs-writeback.c (ffffffff81277aaf)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_queue_work
  - fs/fs-writeback.c:wb_wakeup
```
```
In security/selinux/netif.c (ffffffff8139981f)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_netdev_notifier_handler
  - security/selinux/netif.c:sel_netif_flush
  - security/selinux/netif.c:sel_netif_sid
```
```
In security/selinux/netnode.c (ffffffff81399d86)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_flush
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (ffffffff8139a006)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_flush
  - security/selinux/netport.c:sel_netport_sid
```
```
In security/apparmor/policy_unpack.c (ffffffff813d3579)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In block/genhd.c (ffffffff8142a152)
Location: include/linux/spinlock.h:305
Inline: True
```
```
In lib/rhashtable.c (ffffffff81466898)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rht_deferred_worker
```
```
In drivers/connector/cn_queue.c (ffffffff815c0bbd)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_free_dev
  - drivers/connector/cn_queue.c:cn_queue_del_callback
  - drivers/connector/cn_queue.c:cn_queue_add_callback
```
```
In drivers/connector/connector.c (ffffffff815c0cf8)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_proc_show
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/net/tun.c (ffffffff8167fcbe)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_flow_cleanup
  - drivers/net/tun.c:tun_flow_flush
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81683437)
Location: include/linux/spinlock.h:305
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
  - drivers/net/ppp/ppp_generic.c:ppp_poll
  - drivers/net/ppp/ppp_generic.c:ppp_read
```
```
In drivers/net/xen-netfront.c (ffffffff8168a9ac)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:xennet_open
```
```
In net/core/sock.c (ffffffff8179641b)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/core/sock.c:release_sock
  - net/core/sock.c:lock_sock_nested
  - net/core/sock.c:__sk_flush_backlog
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__lock_sock
```
```
In net/core/request_sock.c (ffffffff817988e5)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/core/datagram.c (ffffffff817a1356)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/core/datagram.c:__sk_queue_drop_skb
```
```
In net/core/gen_stats.c (ffffffff817a3a52)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/core/gen_stats.c:gnet_stats_start_copy_compat
```
```
In net/core/net_namespace.c (ffffffff817a4404)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:get_net_ns_by_id
  - net/core/net_namespace.c:peernet2id
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/dev.c (ffffffff817b387c)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/core/dev.c:dev_set_rx_mode
  - net/core/dev.c:netif_set_real_num_tx_queues
```
```
In net/core/dev_addr_lists.c (ffffffff817b9b9b)
Location: include/linux/spinlock.h:305
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
In net/core/dst.c (ffffffff817bacd9)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/core/dst.c:dst_dev_event
  - net/core/dst.c:__dst_free
  - net/core/dst.c:dst_gc_task
```
```
In net/core/neighbour.c (ffffffff817bfc68)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_update
```
```
In net/core/rtnetlink.c (ffffffff817c4321)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_fdb_dump
```
```
In net/core/sock_reuseport.c (ffffffff817ce87f)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_attach_prog
  - net/core/sock_reuseport.c:reuseport_detach_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_alloc
```
```
In net/core/flow.c (ffffffff817cfa3f)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_gc_task
```
```
In net/core/net-procfs.c (ffffffff817d26b0)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/core/net-procfs.c:dev_mc_seq_show
```
```
In net/sched/sch_generic.c (ffffffff817de2d5)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_graft_qdisc
```
```
In net/sched/sch_mq.c (ffffffff817de727)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump
```
```
In net/sched/sch_api.c (ffffffff817e00ee)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_grow
```
```
In net/sched/cls_api.c (ffffffff817e2778)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_change
```
```
In net/sched/act_api.c (ffffffff817e38b6)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_hash_insert
  - net/sched/act_api.c:tcf_hash_lookup
```
```
In net/netlink/af_netlink.c (ffffffff817e9995)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/ipv4/route.c (ffffffff817f3838)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_flush_dev
  - net/ipv4/route.c:ipv4_dst_destroy
  - net/ipv4/route.c:rt_add_uncached_list
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/inetpeer.c (ffffffff817f3d5b)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
  - net/ipv4/inetpeer.c:inetpeer_inval_rcu
  - net/ipv4/inetpeer.c:inetpeer_gc_worker
  - net/ipv4/inetpeer.c:inetpeer_gc_worker
```
```
In net/ipv4/ip_sockglue.c (ffffffff817fc7e3)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_ra_control
```
```
In net/ipv4/inet_hashtables.c (ffffffff817ff1eb)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_unhash
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff817ff611)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:__inet_twsk_hashdance
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8180110b)
Location: include/linux/spinlock.h:305
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
In net/ipv4/tcp_ipv4.c (ffffffff818194b6)
Location: include/linux/spinlock.h:305
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff8181eece)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_flush_all
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/raw.c (ffffffff81822f14)
Location: include/linux/spinlock.h:305
Inline: True
```
```
In net/ipv4/udp.c (ffffffff8182512a)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_lib_unhash
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/af_inet.c (ffffffff818315c3)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_register_protosw
```
```
In net/ipv4/igmp.c (ffffffff8183455d)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
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
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:igmp_stop_timer
```
```
In net/ipv4/fib_semantics.c (ffffffff8183b5f0)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_release_info
```
```
In net/ipv4/inet_fragment.c (ffffffff81840dc9)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_worker
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff8184478c)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
```
In net/ipv4/ipmr.c (ffffffff81847102)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_seq_next
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
```
```
In net/ipv4/cipso_ipv4.c (ffffffff8184c372)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_invalidate
```
```
In net/xfrm/xfrm_policy.c (ffffffff8185289d)
Location: include/linux/spinlock.h:305
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
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff81859bdb)
Location: include/linux/spinlock.h:305
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
In net/xfrm/xfrm_input.c (ffffffff8185a015)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo
  - net/xfrm/xfrm_input.c:xfrm_input_register_afinfo
```
```
In net/xfrm/xfrm_output.c (ffffffff8185ad44)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/af_inet6.c (ffffffff81861b53)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_register_protosw
```
```
In net/ipv6/addrconf.c (ffffffff81871abe)
Location: include/linux/spinlock.h:305
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
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/route.c (ffffffff81878cda)
Location: include/linux/spinlock.h:305
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
In net/ipv6/ip6_fib.c (ffffffff8187be1e)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_run_gc
```
```
In net/ipv6/raw.c (ffffffff818859c4)
Location: include/linux/spinlock.h:305
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff81889aac)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mcf_seq_next
  - net/ipv6/mcast.c:igmp6_mcf_seq_start
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:ip6_mc_add_src
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
In net/ipv6/ip6_flowlabel.c (ffffffff8189788a)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
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
In net/ipv6/ip6mr.c (ffffffff8189bbaf)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ipmr_mfc_seq_next
```
```
In net/ipv6/calipso.c (ffffffff818a36f7)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_cache_invalidate
```
```
In net/ipv6/seg6_hmac.c (ffffffff818a513e)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
```
In net/packet/af_packet.c (ffffffff818aa298)
Location: include/linux/spinlock.h:305
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
In net/dcb/dcbnl.c (ffffffff818bad5b)
Location: include/linux/spinlock.h:305
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_ieee_delapp
  - net/dcb/dcbnl.c:dcb_ieee_setapp
  - net/dcb/dcbnl.c:dcb_ieee_getapp_mask
  - net/dcb/dcbnl.c:dcb_setapp
  - net/dcb/dcbnl.c:dcb_getapp
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
```
```
In net/switchdev/switchdev.c (ffffffff818beb7b)
Location: include/linux/spinlock.h:305
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
In kernel/cgroup/cgroup.c (ffffffff81121cba)
Location: include/linux/spinlock.h:302
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_free_work_fn
  - kernel/cgroup/cgroup.c:cgroup_idr_replace
```
```
In kernel/bpf/core.c (ffffffff8118f2a2)
Location: include/linux/spinlock.h:302
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_del
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
```
```
In kernel/bpf/syscall.c (ffffffff8119266e)
Location: include/linux/spinlock.h:302
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:bpf_obj_get_next_id
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In mm/page-writeback.c (ffffffff811c55a6)
Location: include/linux/spinlock.h:302
Inline: True
Inline callers:
  - mm/page-writeback.c:bdi_set_max_ratio
  - mm/page-writeback.c:bdi_set_min_ratio
```
```
In mm/backing-dev.c (ffffffff811e1203)
Location: include/linux/spinlock.h:302
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:wb_shutdown
  - mm/backing-dev.c:wb_wakeup_delayed
```
```
In fs/fs-writeback.c (ffffffff81284e51)
Location: include/linux/spinlock.h:302
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_queue_work
  - fs/fs-writeback.c:wb_wakeup
```
```
In security/selinux/netif.c (ffffffff813afc2f)
Location: include/linux/spinlock.h:302
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_netdev_notifier_handler
  - security/selinux/netif.c:sel_netif_flush
  - security/selinux/netif.c:sel_netif_sid
```
```
In security/selinux/netnode.c (ffffffff813b0226)
Location: include/linux/spinlock.h:302
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_flush
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (ffffffff813b04e6)
Location: include/linux/spinlock.h:302
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_flush
  - security/selinux/netport.c:sel_netport_sid
```
```
In security/apparmor/policy_unpack.c (ffffffff813e6682)
Location: include/linux/spinlock.h:302
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In block/genhd.c (ffffffff8143848b)
Location: include/linux/spinlock.h:302
Inline: True
```
```
In lib/rhashtable.c (ffffffff8146c2b3)
Location: include/linux/spinlock.h:302
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rht_deferred_worker
  - lib/rhashtable.c:rhashtable_rehash_alloc
```
```
In drivers/connector/cn_queue.c (ffffffff815d66fd)
Location: include/linux/spinlock.h:302
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_free_dev
  - drivers/connector/cn_queue.c:cn_queue_del_callback
  - drivers/connector/cn_queue.c:cn_queue_add_callback
```
```
In drivers/connector/connector.c (ffffffff815d6838)
Location: include/linux/spinlock.h:302
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_proc_show
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/net/tun.c (ffffffff81694f27)
Location: include/linux/spinlock.h:302
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_flow_cleanup
  - drivers/net/tun.c:tun_flow_flush
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8169886b)
Location: include/linux/spinlock.h:302
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
  - drivers/net/ppp/ppp_generic.c:ppp_poll
  - drivers/net/ppp/ppp_generic.c:ppp_read
```
```
In drivers/net/xen-netfront.c (ffffffff816a0224)
Location: include/linux/spinlock.h:302
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:netback_changed
  - drivers/net/xen-netfront.c:xennet_open
```
```
In net/core/sock.c (ffffffff817b45db)
Location: include/linux/spinlock.h:302
Inline: True
Inline callers:
  - net/core/sock.c:release_sock
  - net/core/sock.c:lock_sock_nested
  - net/core/sock.c:__sk_flush_backlog
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__lock_sock
```
```
In net/core/request_sock.c (ffffffff817b6ec5)
Location: include/linux/spinlock.h:302
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/core/datagram.c (ffffffff817bf45a)
Location: include/linux/spinlock.h:302
Inline: True
Inline callers:
  - net/core/datagram.c:__sk_queue_drop_skb
```
```
In net/core/gen_stats.c (ffffffff817c1c92)
Location: include/linux/spinlock.h:302
Inline: True
```
```
In net/core/net_namespace.c (ffffffff817c2574)
Location: include/linux/spinlock.h:302
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:get_net_ns_by_id
  - net/core/net_namespace.c:peernet2id
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/dev.c (ffffffff817d21fc)
Location: include/linux/spinlock.h:302
Inline: True
Inline callers:
  - net/core/dev.c:dev_set_rx_mode
  - net/core/dev.c:netif_set_real_num_tx_queues
```
```
In net/core/dev_addr_lists.c (ffffffff817d86eb)
Location: include/linux/spinlock.h:302
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
In net/core/neighbour.c (ffffffff817de2fa)
Location: include/linux/spinlock.h:302
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_update
```
```
In net/core/rtnetlink.c (ffffffff817e2691)
Location: include/linux/spinlock.h:302
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_fdb_dump
```
```
In net/core/sock_reuseport.c (ffffffff817edd1f)
Location: include/linux/spinlock.h:302
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_attach_prog
  - net/core/sock_reuseport.c:reuseport_detach_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_alloc
```
```
In net/core/flow.c (ffffffff817eee4f)
Location: include/linux/spinlock.h:302
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_gc_task
```
```
In net/core/net-procfs.c (ffffffff817f1d10)
Location: include/linux/spinlock.h:302
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff817fd929)
Location: include/linux/spinlock.h:302
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_graft_qdisc
```
```
In net/sched/sch_mq.c (ffffffff817fdd57)
Location: include/linux/spinlock.h:302
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump
```
```
In net/sched/sch_api.c (ffffffff817ff28a)
Location: include/linux/spinlock.h:302
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_grow
```
```
In net/sched/cls_api.c (ffffffff81802058)
Location: include/linux/spinlock.h:302
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_change
```
```
In net/sched/act_api.c (ffffffff818032a6)
Location: include/linux/spinlock.h:302
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_hash_insert
  - net/sched/act_api.c:tcf_hash_lookup
```
```
In net/netlink/af_netlink.c (ffffffff81809681)
Location: include/linux/spinlock.h:302
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/ipv4/route.c (ffffffff81811477)
Location: include/linux/spinlock.h:302
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_flush_dev
  - net/ipv4/route.c:rt_add_uncached_list
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/inetpeer.c (ffffffff8181413b)
Location: include/linux/spinlock.h:302
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
  - net/ipv4/inetpeer.c:inetpeer_inval_rcu
  - net/ipv4/inetpeer.c:inetpeer_gc_worker
  - net/ipv4/inetpeer.c:inetpeer_gc_worker
```
```
In net/ipv4/inet_hashtables.c (ffffffff8181f455)
Location: include/linux/spinlock.h:302
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_unhash
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff8181f841)
Location: include/linux/spinlock.h:302
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:__inet_twsk_hashdance
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81820e77)
Location: include/linux/spinlock.h:302
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
In net/ipv4/tcp_ipv4.c (ffffffff8183a67f)
Location: include/linux/spinlock.h:302
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff8183fb09)
Location: include/linux/spinlock.h:302
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_flush_all
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/raw.c (ffffffff81843a78)
Location: include/linux/spinlock.h:302
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81845eba)
Location: include/linux/spinlock.h:302
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/af_inet.c (ffffffff81852b73)
Location: include/linux/spinlock.h:302
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_register_protosw
```
```
In net/ipv4/igmp.c (ffffffff81856029)
Location: include/linux/spinlock.h:302
Inline: True
Inline callers:
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
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:igmp_stop_timer
```
```
In net/ipv4/fib_semantics.c (ffffffff8185cf04)
Location: include/linux/spinlock.h:302
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_release_info
```
```
In net/ipv4/inet_fragment.c (ffffffff81862669)
Location: include/linux/spinlock.h:302
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_worker
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81866144)
Location: include/linux/spinlock.h:302
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
```
In net/ipv4/ipmr.c (ffffffff8186a841)
Location: include/linux/spinlock.h:302
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
```
```
In net/ipv4/cipso_ipv4.c (ffffffff8186fe04)
Location: include/linux/spinlock.h:302
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_invalidate
```
```
In net/xfrm/xfrm_policy.c (ffffffff818759c5)
Location: include/linux/spinlock.h:302
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
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff81879a78)
Location: include/linux/spinlock.h:302
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
In net/xfrm/xfrm_input.c (ffffffff8187ddef)
Location: include/linux/spinlock.h:302
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo
  - net/xfrm/xfrm_input.c:xfrm_input_register_afinfo
```
```
In net/xfrm/xfrm_output.c (ffffffff8187ec54)
Location: include/linux/spinlock.h:302
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/af_inet6.c (ffffffff81886274)
Location: include/linux/spinlock.h:302
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_register_protosw
```
```
In net/ipv6/addrconf.c (ffffffff81896835)
Location: include/linux/spinlock.h:302
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
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/route.c (ffffffff8189e004)
Location: include/linux/spinlock.h:302
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_ifdown
  - net/ipv6/route.c:ip6_dst_destroy
  - net/ipv6/route.c:rt6_uncached_list_add
```
```
In net/ipv6/ip6_fib.c (ffffffff818a17d8)
Location: include/linux/spinlock.h:302
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_run_gc
```
```
In net/ipv6/raw.c (ffffffff818abf08)
Location: include/linux/spinlock.h:302
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff818b02d8)
Location: include/linux/spinlock.h:302
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mcf_seq_next
  - net/ipv6/mcast.c:igmp6_mcf_seq_start
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:ip6_mc_add_src
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
In net/ipv6/ip6_flowlabel.c (ffffffff818bdc91)
Location: include/linux/spinlock.h:302
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
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
In net/ipv6/ip6mr.c (ffffffff818c1fa0)
Location: include/linux/spinlock.h:302
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ipmr_mfc_seq_next
```
```
In net/ipv6/calipso.c (ffffffff818c9cc2)
Location: include/linux/spinlock.h:302
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_cache_invalidate
```
```
In net/ipv6/seg6_hmac.c (ffffffff818cbb99)
Location: include/linux/spinlock.h:302
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
```
In net/packet/af_packet.c (ffffffff818d0dc6)
Location: include/linux/spinlock.h:302
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
In net/dcb/dcbnl.c (ffffffff818e176b)
Location: include/linux/spinlock.h:302
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_ieee_delapp
  - net/dcb/dcbnl.c:dcb_ieee_setapp
  - net/dcb/dcbnl.c:dcb_ieee_getapp_mask
  - net/dcb/dcbnl.c:dcb_setapp
  - net/dcb/dcbnl.c:dcb_getapp
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
```
```
In net/switchdev/switchdev.c (ffffffff818e5693)
Location: include/linux/spinlock.h:302
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
In kernel/cgroup/cgroup.c (ffffffff8112d3b1)
Location: include/linux/spinlock.h:313
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_idr_remove
  - kernel/cgroup/cgroup.c:cgroup_idr_replace
```
```
In kernel/bpf/core.c (ffffffff8119d712)
Location: include/linux/spinlock.h:313
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_del
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
```
```
In kernel/bpf/syscall.c (ffffffff811a0d9c)
Location: include/linux/spinlock.h:313
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:bpf_obj_get_next_id
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In mm/page-writeback.c (ffffffff811da3a6)
Location: include/linux/spinlock.h:313
Inline: True
Inline callers:
  - mm/page-writeback.c:bdi_set_max_ratio
  - mm/page-writeback.c:bdi_set_min_ratio
```
```
In mm/backing-dev.c (ffffffff811f7213)
Location: include/linux/spinlock.h:313
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:wb_shutdown
  - mm/backing-dev.c:wb_wakeup_delayed
```
```
In fs/fs-writeback.c (ffffffff812a78d1)
Location: include/linux/spinlock.h:313
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_queue_work
  - fs/fs-writeback.c:wb_wakeup
```
```
In ipc/util.c (ffffffff813a7273)
Location: include/linux/spinlock.h:313
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/selinux/netif.c (ffffffff813d5cdf)
Location: include/linux/spinlock.h:313
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_netdev_notifier_handler
  - security/selinux/netif.c:sel_netif_flush
  - security/selinux/netif.c:sel_netif_sid
```
```
In security/selinux/netnode.c (ffffffff813d62c6)
Location: include/linux/spinlock.h:313
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_flush
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (ffffffff813d6586)
Location: include/linux/spinlock.h:313
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_flush
  - security/selinux/netport.c:sel_netport_sid
```
```
In security/apparmor/policy_unpack.c (ffffffff8140d866)
Location: include/linux/spinlock.h:313
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In block/genhd.c (ffffffff81463bf0)
Location: include/linux/spinlock.h:313
Inline: True
Inline callers:
  - block/genhd.c:get_gendisk
```
```
In lib/rhashtable.c (ffffffff814985b2)
Location: include/linux/spinlock.h:313
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rht_deferred_worker
  - lib/rhashtable.c:rhashtable_rehash_alloc
```
```
In drivers/connector/cn_queue.c (ffffffff8163d4cd)
Location: include/linux/spinlock.h:313
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_free_dev
  - drivers/connector/cn_queue.c:cn_queue_del_callback
  - drivers/connector/cn_queue.c:cn_queue_add_callback
```
```
In drivers/connector/connector.c (ffffffff8163d608)
Location: include/linux/spinlock.h:313
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_proc_show
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/net/tun.c (ffffffff816ff0d3)
Location: include/linux/spinlock.h:313
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_flow_flush
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8170373b)
Location: include/linux/spinlock.h:313
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
  - drivers/net/ppp/ppp_generic.c:ppp_poll
  - drivers/net/ppp/ppp_generic.c:ppp_read
```
```
In drivers/net/xen-netfront.c (ffffffff8170b3ea)
Location: include/linux/spinlock.h:313
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:netback_changed
  - drivers/net/xen-netfront.c:xennet_open
```
```
In net/core/sock.c (ffffffff8182c83b)
Location: include/linux/spinlock.h:313
Inline: True
Inline callers:
  - net/core/sock.c:release_sock
  - net/core/sock.c:lock_sock_nested
  - net/core/sock.c:__sk_flush_backlog
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__lock_sock
```
```
In net/core/request_sock.c (ffffffff8182f4b5)
Location: include/linux/spinlock.h:313
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/core/datagram.c (ffffffff81838dda)
Location: include/linux/spinlock.h:313
Inline: True
Inline callers:
  - net/core/datagram.c:__sk_queue_drop_skb
```
```
In net/core/gen_stats.c (ffffffff8183b6b2)
Location: include/linux/spinlock.h:313
Inline: True
```
```
In net/core/net_namespace.c (ffffffff8183bfc4)
Location: include/linux/spinlock.h:313
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:get_net_ns_by_id
  - net/core/net_namespace.c:peernet2id
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/dev.c (ffffffff8184c48c)
Location: include/linux/spinlock.h:313
Inline: True
Inline callers:
  - net/core/dev.c:dev_set_rx_mode
  - net/core/dev.c:netif_set_real_num_tx_queues
```
```
In net/core/dev_addr_lists.c (ffffffff81852deb)
Location: include/linux/spinlock.h:313
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
In net/core/neighbour.c (ffffffff81858b5a)
Location: include/linux/spinlock.h:313
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_update
```
```
In net/core/rtnetlink.c (ffffffff8185d551)
Location: include/linux/spinlock.h:313
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_fdb_dump
```
```
In net/core/sock_reuseport.c (ffffffff81869f5f)
Location: include/linux/spinlock.h:313
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_attach_prog
  - net/core/sock_reuseport.c:reuseport_detach_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_alloc
```
```
In net/core/net-procfs.c (ffffffff8186d2d0)
Location: include/linux/spinlock.h:313
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff8187b500)
Location: include/linux/spinlock.h:313
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_graft_qdisc
```
```
In net/sched/sch_mq.c (ffffffff8187b977)
Location: include/linux/spinlock.h:313
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump
```
```
In net/sched/sch_api.c (ffffffff8187cff8)
Location: include/linux/spinlock.h:313
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_grow
```
```
In net/sched/act_api.c (ffffffff81882b34)
Location: include/linux/spinlock.h:313
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_setup_cb_egdev_register
  - net/sched/act_api.c:tcf_idr_insert
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_idr_check
  - net/sched/act_api.c:tcf_idr_search
```
```
In net/netlink/af_netlink.c (ffffffff818885d2)
Location: include/linux/spinlock.h:313
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/ipv4/route.c (ffffffff81890a51)
Location: include/linux/spinlock.h:313
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_flush_dev
  - net/ipv4/route.c:ipv4_dst_destroy
  - net/ipv4/route.c:rt_add_uncached_list
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/inetpeer.c (ffffffff818936f8)
Location: include/linux/spinlock.h:313
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/inet_hashtables.c (ffffffff8189e3b5)
Location: include/linux/spinlock.h:313
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_unhash
```
```
In net/ipv4/inet_connection_sock.c (ffffffff818a0326)
Location: include/linux/spinlock.h:313
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
In net/ipv4/tcp_ipv4.c (ffffffff818ba17f)
Location: include/linux/spinlock.h:313
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff818beea9)
Location: include/linux/spinlock.h:313
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_flush_all
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/raw.c (ffffffff818c3478)
Location: include/linux/spinlock.h:313
Inline: True
```
```
In net/ipv4/udp.c (ffffffff818c58ea)
Location: include/linux/spinlock.h:313
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/af_inet.c (ffffffff818d2983)
Location: include/linux/spinlock.h:313
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_register_protosw
```
```
In net/ipv4/igmp.c (ffffffff818d5eb9)
Location: include/linux/spinlock.h:313
Inline: True
Inline callers:
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
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:igmp_stop_timer
```
```
In net/ipv4/fib_semantics.c (ffffffff818dcf24)
Location: include/linux/spinlock.h:313
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_release_info
```
```
In net/ipv4/inet_fragment.c (ffffffff818e2789)
Location: include/linux/spinlock.h:313
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_worker
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff818e6574)
Location: include/linux/spinlock.h:313
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
```
In net/ipv4/ipmr.c (ffffffff818eafd1)
Location: include/linux/spinlock.h:313
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
```
```
In net/ipv4/cipso_ipv4.c (ffffffff818f07b1)
Location: include/linux/spinlock.h:313
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_invalidate
```
```
In net/xfrm/xfrm_policy.c (ffffffff818f60b6)
Location: include/linux/spinlock.h:313
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
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff818fa4c8)
Location: include/linux/spinlock.h:313
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
In net/xfrm/xfrm_input.c (ffffffff818fec7f)
Location: include/linux/spinlock.h:313
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo
  - net/xfrm/xfrm_input.c:xfrm_input_register_afinfo
```
```
In net/xfrm/xfrm_output.c (ffffffff818ffd50)
Location: include/linux/spinlock.h:313
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/af_inet6.c (ffffffff81907484)
Location: include/linux/spinlock.h:313
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_register_protosw
```
```
In net/ipv6/addrconf.c (ffffffff81917c05)
Location: include/linux/spinlock.h:313
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
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/route.c (ffffffff8191a49b)
Location: include/linux/spinlock.h:313
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
In net/ipv6/ip6_fib.c (ffffffff81921b7d)
Location: include/linux/spinlock.h:313
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
In net/ipv6/raw.c (ffffffff8192e9b8)
Location: include/linux/spinlock.h:313
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff819330e8)
Location: include/linux/spinlock.h:313
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mcf_seq_next
  - net/ipv6/mcast.c:igmp6_mcf_seq_start
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:ip6_mc_add_src
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
In net/ipv6/ip6_flowlabel.c (ffffffff81940d31)
Location: include/linux/spinlock.h:313
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
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
In net/ipv6/ip6mr.c (ffffffff819458db)
Location: include/linux/spinlock.h:313
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:ipmr_mfc_seq_next
```
```
In net/ipv6/calipso.c (ffffffff8194d3a7)
Location: include/linux/spinlock.h:313
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_cache_invalidate
```
```
In net/ipv6/seg6_hmac.c (ffffffff8195093e)
Location: include/linux/spinlock.h:313
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
```
In net/packet/af_packet.c (ffffffff81955cd7)
Location: include/linux/spinlock.h:313
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
In net/dcb/dcbnl.c (ffffffff819674ee)
Location: include/linux/spinlock.h:313
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_ieee_delapp
  - net/dcb/dcbnl.c:dcb_ieee_setapp
  - net/dcb/dcbnl.c:dcb_ieee_getapp_mask
  - net/dcb/dcbnl.c:dcb_setapp
  - net/dcb/dcbnl.c:dcb_getapp
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
```
```
In net/switchdev/switchdev.c (ffffffff8196add1)
Location: include/linux/spinlock.h:313
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
In kernel/cgroup/cgroup.c (ffffffff8113c025)
Location: include/linux/spinlock.h:313
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_idr_remove
  - kernel/cgroup/cgroup.c:cgroup_idr_replace
```
```
In kernel/bpf/core.c (ffffffff811b1cb6)
Location: include/linux/spinlock.h:313
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
```
```
In kernel/bpf/syscall.c (ffffffff811b5531)
Location: include/linux/spinlock.h:313
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_get_fd_by_id
  - kernel/bpf/syscall.c:bpf_prog_get_fd_by_id
  - kernel/bpf/syscall.c:bpf_obj_get_next_id
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
```
```
In kernel/bpf/btf.c (ffffffff811c8b12)
Location: include/linux/spinlock.h:313
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
```
```
In kernel/bpf/sockmap.c (ffffffff811cc605)
Location: include/linux/spinlock.h:313
Inline: True
Inline callers:
  - kernel/bpf/sockmap.c:smap_list_hash_remove
  - kernel/bpf/sockmap.c:smap_list_map_remove
  - kernel/bpf/sockmap.c:bpf_tcp_init
```
```
In mm/page-writeback.c (ffffffff811fb896)
Location: include/linux/spinlock.h:313
Inline: True
Inline callers:
  - mm/page-writeback.c:bdi_set_max_ratio
  - mm/page-writeback.c:bdi_set_min_ratio
```
```
In mm/backing-dev.c (ffffffff8121845f)
Location: include/linux/spinlock.h:313
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:wb_wakeup_delayed
```
```
In fs/fs-writeback.c (ffffffff812ce49e)
Location: include/linux/spinlock.h:313
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_queue_work
  - fs/fs-writeback.c:wb_wakeup
```
```
In ipc/util.c (ffffffff813d67a3)
Location: include/linux/spinlock.h:313
Inline: True
Inline callers:
  - ipc/util.c:ipc_set_key_private
  - ipc/util.c:ipc_rmid
  - ipc/util.c:ipc_addid
```
```
In security/selinux/netif.c (ffffffff8140630d)
Location: include/linux/spinlock.h:313
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_netdev_notifier_handler
  - security/selinux/netif.c:sel_netif_flush
  - security/selinux/netif.c:sel_netif_sid
```
```
In security/selinux/netnode.c (ffffffff814068e5)
Location: include/linux/spinlock.h:313
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_flush
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (ffffffff81406b95)
Location: include/linux/spinlock.h:313
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_flush
  - security/selinux/netport.c:sel_netport_sid
```
```
In security/apparmor/policy_unpack.c (ffffffff8143ef8c)
Location: include/linux/spinlock.h:313
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In block/genhd.c (ffffffff814977ae)
Location: include/linux/spinlock.h:313
Inline: True
Inline callers:
  - block/genhd.c:get_gendisk
```
```
In lib/rhashtable.c (ffffffff814cd795)
Location: include/linux/spinlock.h:313
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rht_deferred_worker
  - lib/rhashtable.c:rhashtable_rehash_alloc
```
```
In drivers/connector/cn_queue.c (ffffffff81678ac5)
Location: include/linux/spinlock.h:313
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_free_dev
  - drivers/connector/cn_queue.c:cn_queue_del_callback
  - drivers/connector/cn_queue.c:cn_queue_add_callback
```
```
In drivers/connector/connector.c (ffffffff81678c11)
Location: include/linux/spinlock.h:313
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_proc_show
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/net/tun.c (ffffffff8173bfe0)
Location: include/linux/spinlock.h:313
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_set_ebpf
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_flow_flush
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81742067)
Location: include/linux/spinlock.h:313
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
  - drivers/net/ppp/ppp_generic.c:ppp_poll
  - drivers/net/ppp/ppp_generic.c:ppp_read
```
```
In drivers/net/xen-netfront.c (ffffffff81749e65)
Location: include/linux/spinlock.h:313
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:netback_changed
```
```
In net/core/sock.c (ffffffff81876995)
Location: include/linux/spinlock.h:313
Inline: True
Inline callers:
  - net/core/sock.c:release_sock
  - net/core/sock.c:lock_sock_nested
  - net/core/sock.c:__sk_flush_backlog
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__lock_sock
```
```
In net/core/request_sock.c (ffffffff81879945)
Location: include/linux/spinlock.h:313
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/core/datagram.c (ffffffff81883538)
Location: include/linux/spinlock.h:313
Inline: True
Inline callers:
  - net/core/datagram.c:__sk_queue_drop_skb
```
```
In net/core/gen_stats.c (ffffffff81886112)
Location: include/linux/spinlock.h:313
Inline: True
```
```
In net/core/net_namespace.c (ffffffff818866eb)
Location: include/linux/spinlock.h:313
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:peernet2id
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/dev.c (ffffffff818966d5)
Location: include/linux/spinlock.h:313
Inline: True
Inline callers:
  - net/core/dev.c:dev_set_rx_mode
  - net/core/dev.c:netif_set_real_num_tx_queues
```
```
In net/core/dev_addr_lists.c (ffffffff8189e4f5)
Location: include/linux/spinlock.h:313
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
In net/core/neighbour.c (ffffffff818a4496)
Location: include/linux/spinlock.h:313
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_update
```
```
In net/core/rtnetlink.c (ffffffff818a90c5)
Location: include/linux/spinlock.h:313
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_fdb_dump
```
```
In net/core/sock_reuseport.c (ffffffff818b9c35)
Location: include/linux/spinlock.h:313
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_attach_prog
  - net/core/sock_reuseport.c:reuseport_detach_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_alloc
```
```
In net/core/xdp.c (ffffffff818bad6a)
Location: include/linux/spinlock.h:313
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_rxq_info_unreg
```
```
In net/core/page_pool.c (ffffffff818bdade)
Location: include/linux/spinlock.h:313
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_empty_ring
```
```
In net/core/net-procfs.c (ffffffff818be526)
Location: include/linux/spinlock.h:313
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff818cd9b2)
Location: include/linux/spinlock.h:313
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_graft_qdisc
```
```
In net/sched/sch_mq.c (ffffffff818ce104)
Location: include/linux/spinlock.h:313
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump
```
```
In net/sched/sch_api.c (ffffffff818cfa96)
Location: include/linux/spinlock.h:313
Inline: True
Inline callers:
  - net/sched/sch_api.c:tcf_node_bind
  - net/sched/sch_api.c:qdisc_class_hash_grow
```
```
In net/sched/act_api.c (ffffffff818d655e)
Location: include/linux/spinlock.h:313
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_setup_cb_egdev_register
```
```
In net/netlink/af_netlink.c (ffffffff818dbfe4)
Location: include/linux/spinlock.h:313
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/ipv4/route.c (ffffffff818e4661)
Location: include/linux/spinlock.h:313
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_flush_dev
  - net/ipv4/route.c:ipv4_dst_destroy
  - net/ipv4/route.c:rt_add_uncached_list
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/inetpeer.c (ffffffff818e7a53)
Location: include/linux/spinlock.h:313
Inline: True
```
```
In net/ipv4/inet_hashtables.c (ffffffff818f2e1d)
Location: include/linux/spinlock.h:313
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_unhash
```
```
In net/ipv4/inet_connection_sock.c (ffffffff818f575d)
Location: include/linux/spinlock.h:313
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
In net/ipv4/tcp_ipv4.c (ffffffff8190ee3b)
Location: include/linux/spinlock.h:313
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff81914a8c)
Location: include/linux/spinlock.h:313
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_flush_all
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/raw.c (ffffffff81919114)
Location: include/linux/spinlock.h:313
Inline: True
```
```
In net/ipv4/udp.c (ffffffff8191d946)
Location: include/linux/spinlock.h:313
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/af_inet.c (ffffffff81928f43)
Location: include/linux/spinlock.h:313
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_register_protosw
```
```
In net/ipv4/igmp.c (ffffffff8192dc95)
Location: include/linux/spinlock.h:313
Inline: True
Inline callers:
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
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:igmp_stop_timer
```
```
In net/ipv4/fib_semantics.c (ffffffff81933ae2)
Location: include/linux/spinlock.h:313
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_release_info
```
```
In net/ipv4/inet_fragment.c (ffffffff81939169)
Location: include/linux/spinlock.h:313
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff8193d0a0)
Location: include/linux/spinlock.h:313
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
```
In net/ipv4/ipmr.c (ffffffff819421d7)
Location: include/linux/spinlock.h:313
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
```
```
In net/ipv4/ipmr_base.c (ffffffff819442bb)
Location: include/linux/spinlock.h:313
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_rtm_dumproute
  - net/ipv4/ipmr_base.c:mr_mfc_seq_next
```
```
In net/ipv4/cipso_ipv4.c (ffffffff819470bd)
Location: include/linux/spinlock.h:313
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_invalidate
```
```
In net/xfrm/xfrm_policy.c (ffffffff8194c2a6)
Location: include/linux/spinlock.h:313
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
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff81950fd8)
Location: include/linux/spinlock.h:313
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
In net/xfrm/xfrm_input.c (ffffffff81955745)
Location: include/linux/spinlock.h:313
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo
  - net/xfrm/xfrm_input.c:xfrm_input_register_afinfo
```
```
In net/xfrm/xfrm_output.c (ffffffff81956611)
Location: include/linux/spinlock.h:313
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/af_inet6.c (ffffffff8195e064)
Location: include/linux/spinlock.h:313
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_register_protosw
```
```
In net/ipv6/addrconf.c (ffffffff8196f325)
Location: include/linux/spinlock.h:313
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
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/route.c (ffffffff81972b1a)
Location: include/linux/spinlock.h:313
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
In net/ipv6/ip6_fib.c (ffffffff81979f7a)
Location: include/linux/spinlock.h:313
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
In net/ipv6/raw.c (ffffffff81987344)
Location: include/linux/spinlock.h:313
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff8198d058)
Location: include/linux/spinlock.h:313
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mcf_seq_next
  - net/ipv6/mcast.c:igmp6_mcf_seq_start
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:ip6_mc_add_src
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
In net/ipv6/ip6_flowlabel.c (ffffffff81999c05)
Location: include/linux/spinlock.h:313
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
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
In net/ipv6/ip6mr.c (ffffffff8199e92a)
Location: include/linux/spinlock.h:313
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
```
```
In net/ipv6/calipso.c (ffffffff819a5b45)
Location: include/linux/spinlock.h:313
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_cache_invalidate
```
```
In net/ipv6/seg6_hmac.c (ffffffff819a9e33)
Location: include/linux/spinlock.h:313
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
```
In net/packet/af_packet.c (ffffffff819b12f3)
Location: include/linux/spinlock.h:313
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
In net/dcb/dcbnl.c (ffffffff819c108e)
Location: include/linux/spinlock.h:313
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_ieee_delapp
  - net/dcb/dcbnl.c:dcb_ieee_setapp
  - net/dcb/dcbnl.c:dcb_ieee_getapp_mask
  - net/dcb/dcbnl.c:dcb_setapp
  - net/dcb/dcbnl.c:dcb_getapp
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
```
```
In net/switchdev/switchdev.c (ffffffff819c48bb)
Location: include/linux/spinlock.h:313
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
In kernel/cgroup/cgroup.c (ffffffff811478b5)
Location: include/linux/spinlock.h:332
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_idr_remove
  - kernel/cgroup/cgroup.c:cgroup_idr_replace
```
```
In kernel/bpf/core.c (ffffffff811c0566)
Location: include/linux/spinlock.h:332
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
```
```
In kernel/bpf/syscall.c (ffffffff811c53cb)
Location: include/linux/spinlock.h:332
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_obj_get_next_id
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In kernel/bpf/local_storage.c (ffffffff811d887a)
Location: include/linux/spinlock.h:332
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_unlink
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_link
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_release
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_assign
  - kernel/bpf/local_storage.c:cgroup_storage_get_next_key
  - kernel/bpf/local_storage.c:cgroup_storage_lookup
```
```
In kernel/bpf/btf.c (ffffffff811dc812)
Location: include/linux/spinlock.h:332
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
```
```
In kernel/bpf/offload.c (ffffffff811df435)
Location: include/linux/spinlock.h:332
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In kernel/bpf/reuseport_array.c (ffffffff811e2a80)
Location: include/linux/spinlock.h:332
Inline: True
Inline callers:
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem
  - kernel/bpf/reuseport_array.c:reuseport_array_delete_elem
```
```
In mm/page-writeback.c (ffffffff8120e176)
Location: include/linux/spinlock.h:332
Inline: True
Inline callers:
  - mm/page-writeback.c:bdi_set_max_ratio
  - mm/page-writeback.c:bdi_set_min_ratio
```
```
In mm/backing-dev.c (ffffffff8122b3af)
Location: include/linux/spinlock.h:332
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:wb_wakeup_delayed
```
```
In fs/fs-writeback.c (ffffffff812e379e)
Location: include/linux/spinlock.h:332
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_queue_work
  - fs/fs-writeback.c:wb_wakeup
```
```
In ipc/util.c (ffffffff813f0e2c)
Location: include/linux/spinlock.h:332
Inline: True
Inline callers:
  - ipc/util.c:ipc_set_key_private
  - ipc/util.c:ipc_rmid
  - ipc/util.c:ipc_addid
```
```
In security/selinux/netif.c (ffffffff81421e5d)
Location: include/linux/spinlock.h:332
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_netdev_notifier_handler
  - security/selinux/netif.c:sel_netif_flush
  - security/selinux/netif.c:sel_netif_sid
```
```
In security/selinux/netnode.c (ffffffff81422445)
Location: include/linux/spinlock.h:332
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_flush
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (ffffffff81422705)
Location: include/linux/spinlock.h:332
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_flush
  - security/selinux/netport.c:sel_netport_sid
```
```
In security/apparmor/policy_unpack.c (ffffffff8145be9b)
Location: include/linux/spinlock.h:332
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In block/genhd.c (ffffffff814b16ce)
Location: include/linux/spinlock.h:332
Inline: True
Inline callers:
  - block/genhd.c:get_gendisk
```
```
In lib/rhashtable.c (ffffffff814e17f5)
Location: include/linux/spinlock.h:332
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rht_deferred_worker
```
```
In drivers/connector/cn_queue.c (ffffffff81697bb5)
Location: include/linux/spinlock.h:332
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_free_dev
  - drivers/connector/cn_queue.c:cn_queue_del_callback
  - drivers/connector/cn_queue.c:cn_queue_add_callback
```
```
In drivers/connector/connector.c (ffffffff81697d01)
Location: include/linux/spinlock.h:332
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_proc_show
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/net/tun.c (ffffffff8175f920)
Location: include/linux/spinlock.h:332
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_set_ebpf
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_flow_update
  - drivers/net/tun.c:tun_flow_flush
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81766177)
Location: include/linux/spinlock.h:332
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
  - drivers/net/ppp/ppp_generic.c:ppp_poll
  - drivers/net/ppp/ppp_generic.c:ppp_read
```
```
In drivers/net/xen-netfront.c (ffffffff8176dfef)
Location: include/linux/spinlock.h:332
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:netback_changed
```
```
In net/core/sock.c (ffffffff81898825)
Location: include/linux/spinlock.h:332
Inline: True
Inline callers:
  - net/core/sock.c:release_sock
  - net/core/sock.c:lock_sock_nested
  - net/core/sock.c:__sk_flush_backlog
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__lock_sock
```
```
In net/core/request_sock.c (ffffffff8189a595)
Location: include/linux/spinlock.h:332
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/core/datagram.c (ffffffff818a3f88)
Location: include/linux/spinlock.h:332
Inline: True
Inline callers:
  - net/core/datagram.c:__sk_queue_drop_skb
```
```
In net/core/gen_stats.c (ffffffff818a65f2)
Location: include/linux/spinlock.h:332
Inline: True
```
```
In net/core/gen_estimator.c (ffffffff818a6cf5)
Location: include/linux/spinlock.h:332
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/net_namespace.c (ffffffff818a7a65)
Location: include/linux/spinlock.h:332
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:peernet2id
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/dev.c (ffffffff818b8945)
Location: include/linux/spinlock.h:332
Inline: True
Inline callers:
  - net/core/dev.c:dev_set_rx_mode
  - net/core/dev.c:netif_set_real_num_tx_queues
```
```
In net/core/dev_addr_lists.c (ffffffff818c0d15)
Location: include/linux/spinlock.h:332
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
In net/core/neighbour.c (ffffffff818c79ff)
Location: include/linux/spinlock.h:332
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/core/rtnetlink.c (ffffffff818cd74b)
Location: include/linux/spinlock.h:332
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_fdb_dump
```
```
In net/core/sock_reuseport.c (ffffffff818e0dc5)
Location: include/linux/spinlock.h:332
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_attach_prog
  - net/core/sock_reuseport.c:reuseport_detach_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_alloc
```
```
In net/core/xdp.c (ffffffff818e1e02)
Location: include/linux/spinlock.h:332
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
```
```
In net/core/page_pool.c (ffffffff818e4ebe)
Location: include/linux/spinlock.h:332
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_empty_ring
```
```
In net/core/net-procfs.c (ffffffff818e59a6)
Location: include/linux/spinlock.h:332
Inline: True
```
```
In net/core/skmsg.c (ffffffff818e7195)
Location: include/linux/spinlock.h:332
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_link_pop
```
```
In net/core/sock_map.c (ffffffff818f28d2)
Location: include/linux/spinlock.h:332
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_unref
```
```
In net/sched/sch_generic.c (ffffffff818f8bf2)
Location: include/linux/spinlock.h:332
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_graft_qdisc
```
```
In net/sched/sch_mq.c (ffffffff818f929d)
Location: include/linux/spinlock.h:332
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump
```
```
In net/sched/sch_api.c (ffffffff818fb766)
Location: include/linux/spinlock.h:332
Inline: True
Inline callers:
  - net/sched/sch_api.c:tcf_node_bind
  - net/sched/sch_api.c:qdisc_class_hash_grow
```
```
In net/sched/cls_api.c (ffffffff81901947)
Location: include/linux/spinlock.h:332
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tc_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffff819089ad)
Location: include/linux/spinlock.h:332
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/ipv4/route.c (ffffffff81911591)
Location: include/linux/spinlock.h:332
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_flush_dev
  - net/ipv4/route.c:ipv4_dst_destroy
  - net/ipv4/route.c:rt_add_uncached_list
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/inetpeer.c (ffffffff81914903)
Location: include/linux/spinlock.h:332
Inline: True
```
```
In net/ipv4/inet_hashtables.c (ffffffff819209a0)
Location: include/linux/spinlock.h:332
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_unhash
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81922a9d)
Location: include/linux/spinlock.h:332
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
In net/ipv4/tcp_ipv4.c (ffffffff8193d26b)
Location: include/linux/spinlock.h:332
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff8194323c)
Location: include/linux/spinlock.h:332
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_flush_all
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/raw.c (ffffffff819478e4)
Location: include/linux/spinlock.h:332
Inline: True
```
```
In net/ipv4/udp.c (ffffffff8194c1f6)
Location: include/linux/spinlock.h:332
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/af_inet.c (ffffffff81958233)
Location: include/linux/spinlock.h:332
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_register_protosw
```
```
In net/ipv4/igmp.c (ffffffff8195b725)
Location: include/linux/spinlock.h:332
Inline: True
Inline callers:
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
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:igmp_stop_timer
```
```
In net/ipv4/fib_semantics.c (ffffffff81962fea)
Location: include/linux/spinlock.h:332
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_release_info
```
```
In net/ipv4/inet_fragment.c (ffffffff81968d36)
Location: include/linux/spinlock.h:332
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff8196cf30)
Location: include/linux/spinlock.h:332
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
```
In net/ipv4/ipmr.c (ffffffff81971fd0)
Location: include/linux/spinlock.h:332
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
```
```
In net/ipv4/ipmr_base.c (ffffffff81974426)
Location: include/linux/spinlock.h:332
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_table_dump
  - net/ipv4/ipmr_base.c:mr_mfc_seq_next
```
```
In net/ipv4/tcp_bpf.c (ffffffff81978179)
Location: include/linux/spinlock.h:332
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_init
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81978c64)
Location: include/linux/spinlock.h:332
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_invalidate
```
```
In net/xfrm/xfrm_policy.c (ffffffff8198031b)
Location: include/linux/spinlock.h:332
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
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff81984528)
Location: include/linux/spinlock.h:332
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
In net/xfrm/xfrm_input.c (ffffffff8198a355)
Location: include/linux/spinlock.h:332
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo
  - net/xfrm/xfrm_input.c:xfrm_input_register_afinfo
```
```
In net/xfrm/xfrm_output.c (ffffffff8198b40a)
Location: include/linux/spinlock.h:332
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/af_inet6.c (ffffffff81992bc4)
Location: include/linux/spinlock.h:332
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_register_protosw
```
```
In net/ipv6/addrconf.c (ffffffff819a4ed5)
Location: include/linux/spinlock.h:332
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
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/route.c (ffffffff819a84ba)
Location: include/linux/spinlock.h:332
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
In net/ipv6/ip6_fib.c (ffffffff819afb6a)
Location: include/linux/spinlock.h:332
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:__fib6_clean_all
  - net/ipv6/ip6_fib.c:fib6_tables_dump
```
```
In net/ipv6/raw.c (ffffffff819bdf84)
Location: include/linux/spinlock.h:332
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff819c2228)
Location: include/linux/spinlock.h:332
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mcf_seq_next
  - net/ipv6/mcast.c:igmp6_mcf_seq_start
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:ip6_mc_add_src
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
In net/ipv6/ip6_flowlabel.c (ffffffff819d07d5)
Location: include/linux/spinlock.h:332
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
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
In net/ipv6/ip6mr.c (ffffffff819d52c5)
Location: include/linux/spinlock.h:332
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
```
```
In net/ipv6/calipso.c (ffffffff819dccf3)
Location: include/linux/spinlock.h:332
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_cache_invalidate
```
```
In net/ipv6/seg6_hmac.c (ffffffff819e0954)
Location: include/linux/spinlock.h:332
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
```
In net/packet/af_packet.c (ffffffff819e86dc)
Location: include/linux/spinlock.h:332
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
In net/dcb/dcbnl.c (ffffffff819f7482)
Location: include/linux/spinlock.h:332
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
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
```
```
In net/switchdev/switchdev.c (ffffffff819fbd5b)
Location: include/linux/spinlock.h:332
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_deferred_process
```
```
In lib/xarray.c (ffffffff81a17d60)
Location: include/linux/spinlock.h:332
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
In kernel/cgroup/cgroup.c (ffffffff81152b25)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_idr_remove
  - kernel/cgroup/cgroup.c:cgroup_idr_replace
```
```
In kernel/bpf/core.c (ffffffff811d1074)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
```
```
In kernel/bpf/syscall.c (ffffffff811d5aad)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_obj_get_next_id
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
```
```
In kernel/bpf/local_storage.c (ffffffff811ed36a)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_unlink
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_link
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_release
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_assign
  - kernel/bpf/local_storage.c:cgroup_storage_get_next_key
  - kernel/bpf/local_storage.c:cgroup_storage_lookup
```
```
In kernel/bpf/btf.c (ffffffff811f1f73)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
```
```
In kernel/bpf/reuseport_array.c (ffffffff811f9c03)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem
  - kernel/bpf/reuseport_array.c:reuseport_array_delete_elem
```
```
In mm/page-writeback.c (ffffffff8121dacf)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - mm/page-writeback.c:bdi_set_max_ratio
  - mm/page-writeback.c:bdi_set_min_ratio
```
```
In mm/backing-dev.c (ffffffff8123affd)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:wb_wakeup_delayed
```
```
In fs/fs-writeback.c (ffffffff81301ede)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_queue_work
  - fs/fs-writeback.c:wb_wakeup
```
```
In security/selinux/netif.c (ffffffff8144fa56)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_netdev_notifier_handler
  - security/selinux/netif.c:sel_netif_flush
  - security/selinux/netif.c:sel_netif_sid
```
```
In security/selinux/netnode.c (ffffffff81450075)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_flush
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (ffffffff81450385)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_flush
  - security/selinux/netport.c:sel_netport_sid
```
```
In block/genhd.c (ffffffff814dfa7f)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - block/genhd.c:get_gendisk
```
```
In block/blk-cgroup.c (ffffffff814f184e)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - block/blk-cgroup.c:__blkcg_punt_bio_submit
  - block/blk-cgroup.c:blkg_async_bio_workfn
```
```
In drivers/connector/cn_queue.c (ffffffff816d0735)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_free_dev
  - drivers/connector/cn_queue.c:cn_queue_del_callback
  - drivers/connector/cn_queue.c:cn_queue_add_callback
```
```
In drivers/connector/connector.c (ffffffff816d087f)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_proc_show
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/net/tun.c (ffffffff8179d150)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_set_ebpf
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_flow_update
  - drivers/net/tun.c:tun_flow_flush
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817a3885)
Location: include/linux/spinlock.h:341
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
  - drivers/net/ppp/ppp_generic.c:ppp_poll
  - drivers/net/ppp/ppp_generic.c:ppp_read
```
```
In drivers/net/xen-netfront.c (ffffffff817ac20f)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:netback_changed
```
```
In net/core/sock.c (ffffffff818e2dc5)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/sock.c:release_sock
  - net/core/sock.c:lock_sock_nested
  - net/core/sock.c:__sk_flush_backlog
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__lock_sock
```
```
In net/core/request_sock.c (ffffffff818e4c75)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/core/datagram.c (ffffffff818ef26d)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/datagram.c:__sk_queue_drop_skb
```
```
In net/core/gen_stats.c (ffffffff818f1932)
Location: include/linux/spinlock.h:341
Inline: True
```
```
In net/core/gen_estimator.c (ffffffff818f2185)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/net_namespace.c (ffffffff818f373a)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:peernet2id
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/dev.c (ffffffff81904b05)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/dev.c:dev_set_rx_mode
  - net/core/dev.c:netif_set_real_num_tx_queues
```
```
In net/core/dev_addr_lists.c (ffffffff8190d425)
Location: include/linux/spinlock.h:341
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
In net/core/neighbour.c (ffffffff81914117)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/core/rtnetlink.c (ffffffff8191a42d)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_fdb_dump
```
```
In net/core/sock_reuseport.c (ffffffff8192f597)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_attach_prog
  - net/core/sock_reuseport.c:reuseport_detach_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_alloc
```
```
In net/core/page_pool.c (ffffffff81934766)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_request_shutdown
```
```
In net/core/net-procfs.c (ffffffff8193520b)
Location: include/linux/spinlock.h:341
Inline: True
```
```
In net/core/skmsg.c (ffffffff81936b25)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_link_pop
```
```
In net/core/sock_map.c (ffffffff81944a1d)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_unref
```
```
In net/sched/sch_generic.c (ffffffff819583c2)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_graft_qdisc
```
```
In net/sched/sch_mq.c (ffffffff81958ae1)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump
```
```
In net/sched/sch_api.c (ffffffff8195b683)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_grow
```
```
In net/ipv4/route.c (ffffffff81973bd8)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_flush_dev
  - net/ipv4/route.c:ipv4_dst_destroy
  - net/ipv4/route.c:rt_add_uncached_list
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/inetpeer.c (ffffffff81976d26)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/inet_hashtables.c (ffffffff819832e5)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_unhash
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819853d6)
Location: include/linux/spinlock.h:341
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
In net/ipv4/tcp_ipv4.c (ffffffff819a16a3)
Location: include/linux/spinlock.h:341
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff819a77f8)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_flush_all
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/raw.c (ffffffff819abf8a)
Location: include/linux/spinlock.h:341
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819b0c22)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/af_inet.c (ffffffff819bcd53)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_register_protosw
```
```
In net/ipv4/igmp.c (ffffffff819c03fc)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
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
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:igmp_stop_timer
```
```
In net/ipv4/fib_semantics.c (ffffffff819c90cf)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_release_info
```
```
In net/ipv4/inet_fragment.c (ffffffff819cef39)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frags_free_cb
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff819d6830)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
```
In net/ipv4/ipmr.c (ffffffff819db9d5)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
```
```
In net/ipv4/ipmr_base.c (ffffffff819ddf57)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_table_dump
  - net/ipv4/ipmr_base.c:mr_mfc_seq_next
```
```
In net/ipv4/tcp_bpf.c (ffffffff819e1c61)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_init
```
```
In net/ipv4/cipso_ipv4.c (ffffffff819e2721)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_invalidate
```
```
In net/xfrm/xfrm_policy.c (ffffffff819ea063)
Location: include/linux/spinlock.h:341
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
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff819ee255)
Location: include/linux/spinlock.h:341
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
In net/xfrm/xfrm_input.c (ffffffff819f4665)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo
  - net/xfrm/xfrm_input.c:xfrm_input_register_afinfo
```
```
In net/xfrm/xfrm_output.c (ffffffff819f699c)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/af_inet6.c (ffffffff819fe624)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_register_protosw
```
```
In net/ipv6/addrconf.c (ffffffff81a111ec)
Location: include/linux/spinlock.h:341
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
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/route.c (ffffffff81a148a1)
Location: include/linux/spinlock.h:341
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
In net/ipv6/ip6_fib.c (ffffffff81a1dcee)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:__fib6_clean_all
  - net/ipv6/ip6_fib.c:fib6_update_sernum_stub
  - net/ipv6/ip6_fib.c:fib6_tables_dump
```
```
In net/ipv6/raw.c (ffffffff81a2ca8a)
Location: include/linux/spinlock.h:341
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff81a3102b)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mcf_seq_next
  - net/ipv6/mcast.c:igmp6_mcf_seq_start
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:ip6_mc_add_src
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
In net/ipv6/ip6_flowlabel.c (ffffffff81a3f245)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
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
In net/ipv6/ip6mr.c (ffffffff81a441e8)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
```
```
In net/ipv6/calipso.c (ffffffff81a4b8f7)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_cache_invalidate
```
```
In net/packet/af_packet.c (ffffffff81a58ab6)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_getsockopt
```
```
In net/dcb/dcbnl.c (ffffffff81a669b2)
Location: include/linux/spinlock.h:341
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
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
```
```
In net/switchdev/switchdev.c (ffffffff81a6b35d)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_deferred_process
```
```
In net/xdp/xsk.c (ffffffff81a7521f)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_generic_rcv
```
```
In lib/xarray.c (ffffffff81a86cdd)
Location: include/linux/spinlock.h:341
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
In kernel/cgroup/cgroup.c (ffffffff8115e775)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_idr_remove
  - kernel/cgroup/cgroup.c:cgroup_idr_replace
```
```
In kernel/bpf/core.c (ffffffff811dd604)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
```
```
In kernel/bpf/syscall.c (ffffffff811e1f1f)
Location: include/linux/spinlock.h:341
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
In kernel/bpf/local_storage.c (ffffffff811f9aba)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_unlink
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_link
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_release
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_assign
  - kernel/bpf/local_storage.c:cgroup_storage_get_next_key
  - kernel/bpf/local_storage.c:cgroup_storage_lookup
```
```
In kernel/bpf/btf.c (ffffffff811fe683)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
```
```
In kernel/bpf/xskmap.c (ffffffff81201655)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - kernel/bpf/xskmap.c:xsk_map_try_sock_delete
  - kernel/bpf/xskmap.c:xsk_map_delete_elem
  - kernel/bpf/xskmap.c:xsk_map_update_elem
  - kernel/bpf/xskmap.c:xsk_map_update_elem
  - kernel/bpf/xskmap.c:xsk_map_sock_delete
```
```
In kernel/bpf/reuseport_array.c (ffffffff81206cd3)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem
  - kernel/bpf/reuseport_array.c:reuseport_array_delete_elem
```
```
In mm/page-writeback.c (ffffffff8122b56f)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - mm/page-writeback.c:bdi_set_max_ratio
  - mm/page-writeback.c:bdi_set_min_ratio
```
```
In mm/backing-dev.c (ffffffff8124950d)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:bdi_get_by_id
  - mm/backing-dev.c:wb_wakeup_delayed
```
```
In fs/fs-writeback.c (ffffffff81314fde)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_queue_work
  - fs/fs-writeback.c:wb_wakeup
```
```
In security/selinux/netif.c (ffffffff814698c6)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_netdev_notifier_handler
  - security/selinux/netif.c:sel_netif_flush
  - security/selinux/netif.c:sel_netif_sid
```
```
In security/selinux/netnode.c (ffffffff81469e95)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_flush
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (ffffffff8146a145)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_flush
  - security/selinux/netport.c:sel_netport_sid
```
```
In block/genhd.c (ffffffff814f8eaf)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - block/genhd.c:get_gendisk
```
```
In block/blk-cgroup.c (ffffffff8150ae3e)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - block/blk-cgroup.c:__blkcg_punt_bio_submit
  - block/blk-cgroup.c:blkg_async_bio_workfn
```
```
In drivers/connector/cn_queue.c (ffffffff816f4555)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_free_dev
  - drivers/connector/cn_queue.c:cn_queue_del_callback
  - drivers/connector/cn_queue.c:cn_queue_add_callback
```
```
In drivers/connector/connector.c (ffffffff816f469f)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_proc_show
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/net/tun.c (ffffffff817c0bf0)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_set_ebpf
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_flow_update
  - drivers/net/tun.c:tun_flow_flush
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817c72d5)
Location: include/linux/spinlock.h:341
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
  - drivers/net/ppp/ppp_generic.c:ppp_poll
  - drivers/net/ppp/ppp_generic.c:ppp_read
```
```
In drivers/net/xen-netfront.c (ffffffff817cfc4f)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:netback_changed
```
```
In net/core/sock.c (ffffffff81914fa5)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/sock.c:release_sock
  - net/core/sock.c:lock_sock_nested
  - net/core/sock.c:__sk_flush_backlog
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__lock_sock
```
```
In net/core/request_sock.c (ffffffff81916e05)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/core/datagram.c (ffffffff8192121d)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/datagram.c:__sk_queue_drop_skb
```
```
In net/core/gen_stats.c (ffffffff81923882)
Location: include/linux/spinlock.h:341
Inline: True
```
```
In net/core/gen_estimator.c (ffffffff819240d5)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/net_namespace.c (ffffffff819256ea)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:peernet2id
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/dev.c (ffffffff81937175)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/dev.c:dev_set_rx_mode
  - net/core/dev.c:netif_set_real_num_tx_queues
```
```
In net/core/dev_addr_lists.c (ffffffff8193fb25)
Location: include/linux/spinlock.h:341
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
In net/core/neighbour.c (ffffffff81946787)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/core/rtnetlink.c (ffffffff8194ca4d)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_fdb_dump
```
```
In net/core/sock_reuseport.c (ffffffff81961807)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_attach_prog
  - net/core/sock_reuseport.c:reuseport_detach_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_alloc
```
```
In net/core/page_pool.c (ffffffff81967515)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
```
```
In net/core/net-procfs.c (ffffffff81967fcb)
Location: include/linux/spinlock.h:341
Inline: True
```
```
In net/core/skmsg.c (ffffffff819699f5)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_link_pop
```
```
In net/core/sock_map.c (ffffffff81979a1d)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_unref
```
```
In net/core/devlink.c (ffffffff81982ca5)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_port_type_set
  - net/core/devlink.c:devlink_nl_port_fill
```
```
In net/sched/sch_generic.c (ffffffff8198e872)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_graft_qdisc
```
```
In net/sched/sch_mq.c (ffffffff8198ef81)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump
```
```
In net/sched/sch_api.c (ffffffff81990ba9)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/sched/sch_api.c:tcf_node_bind
  - net/sched/sch_api.c:qdisc_class_hash_grow
```
```
In net/ipv4/route.c (ffffffff819aa5f8)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_flush_dev
  - net/ipv4/route.c:ipv4_dst_destroy
  - net/ipv4/route.c:rt_add_uncached_list
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/inetpeer.c (ffffffff819ad6b6)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/inet_hashtables.c (ffffffff819b9b58)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_unhash
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819bbbe6)
Location: include/linux/spinlock.h:341
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
In net/ipv4/tcp_ipv4.c (ffffffff819d8353)
Location: include/linux/spinlock.h:341
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff819de87b)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_flush_all
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/raw.c (ffffffff819e2c3a)
Location: include/linux/spinlock.h:341
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819e7b72)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/af_inet.c (ffffffff819f3963)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_register_protosw
```
```
In net/ipv4/igmp.c (ffffffff819f6f9c)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
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
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:igmp_stop_timer
```
```
In net/ipv4/fib_semantics.c (ffffffff819ffc8d)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_release_info
```
```
In net/ipv4/inet_fragment.c (ffffffff81a05ad9)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frags_free_cb
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81a0d320)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
```
In net/ipv4/ipmr.c (ffffffff81a12905)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
```
```
In net/ipv4/ipmr_base.c (ffffffff81a14ff7)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_table_dump
  - net/ipv4/ipmr_base.c:mr_mfc_seq_next
```
```
In net/ipv4/tcp_bpf.c (ffffffff81a18c51)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_init
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81a19711)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_invalidate
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a210ab)
Location: include/linux/spinlock.h:341
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
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff81a250c1)
Location: include/linux/spinlock.h:341
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
In net/xfrm/xfrm_input.c (ffffffff81a2b315)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo
  - net/xfrm/xfrm_input.c:xfrm_input_register_afinfo
```
```
In net/xfrm/xfrm_output.c (ffffffff81a2d604)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/af_inet6.c (ffffffff81a35214)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_register_protosw
```
```
In net/ipv6/addrconf.c (ffffffff81a47f45)
Location: include/linux/spinlock.h:341
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
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/route.c (ffffffff81a4b491)
Location: include/linux/spinlock.h:341
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
In net/ipv6/ip6_fib.c (ffffffff81a5491e)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:__fib6_clean_all
  - net/ipv6/ip6_fib.c:fib6_update_sernum_stub
  - net/ipv6/ip6_fib.c:fib6_tables_dump
```
```
In net/ipv6/raw.c (ffffffff81a6375a)
Location: include/linux/spinlock.h:341
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff81a67b7b)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mcf_seq_next
  - net/ipv6/mcast.c:igmp6_mcf_seq_start
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:ip6_mc_add_src
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
In net/ipv6/ip6_flowlabel.c (ffffffff81a75eb5)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
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
In net/ipv6/ip6mr.c (ffffffff81a7add8)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
```
```
In net/ipv6/calipso.c (ffffffff81a824c7)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_cache_invalidate
```
```
In net/packet/af_packet.c (ffffffff81a8ebb3)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_getsockopt
```
```
In net/dcb/dcbnl.c (ffffffff81a9d4d2)
Location: include/linux/spinlock.h:341
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
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
```
```
In net/switchdev/switchdev.c (ffffffff81aa1d4d)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_deferred_process
```
```
In net/xdp/xsk.c (ffffffff81aab23c)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xsk.c:xsk_generic_rcv
```
```
In lib/xarray.c (ffffffff81abdf4d)
Location: include/linux/spinlock.h:341
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
In kernel/cgroup/cgroup.c (ffffffff8117032d)
Location: include/linux/spinlock.h:356
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_create
  - kernel/cgroup/cgroup.c:css_create
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
```
```
In kernel/bpf/core.c (ffffffff811fa095)
Location: include/linux/spinlock.h:356
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_ksym_del
  - kernel/bpf/core.c:bpf_ksym_add
```
```
In kernel/bpf/syscall.c (ffffffff81201af8)
Location: include/linux/spinlock.h:356
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
In kernel/bpf/local_storage.c (ffffffff8121d92a)
Location: include/linux/spinlock.h:356
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_unlink
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_link
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_release
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_assign
  - kernel/bpf/local_storage.c:cgroup_storage_get_next_key
  - kernel/bpf/local_storage.c:cgroup_storage_lookup_elem
```
```
In kernel/bpf/btf.c (ffffffff81225deb)
Location: include/linux/spinlock.h:356
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
```
```
In kernel/bpf/reuseport_array.c (ffffffff8122f2a3)
Location: include/linux/spinlock.h:356
Inline: True
Inline callers:
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem
  - kernel/bpf/reuseport_array.c:reuseport_array_delete_elem
```
```
In kernel/watch_queue.c (ffffffff8124d399)
Location: include/linux/spinlock.h:356
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_clear
  - kernel/watch_queue.c:watch_queue_clear
  - kernel/watch_queue.c:remove_watch_from_object
  - kernel/watch_queue.c:add_watch_to_object
```
```
In mm/page-writeback.c (ffffffff8125847f)
Location: include/linux/spinlock.h:356
Inline: True
Inline callers:
  - mm/page-writeback.c:bdi_set_max_ratio
  - mm/page-writeback.c:bdi_set_min_ratio
```
```
In mm/backing-dev.c (ffffffff81277855)
Location: include/linux/spinlock.h:356
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:bdi_get_by_id
  - mm/backing-dev.c:wb_shutdown
  - mm/backing-dev.c:wb_wakeup_delayed
```
```
In fs/fs-writeback.c (ffffffff8134914b)
Location: include/linux/spinlock.h:356
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
In security/selinux/netif.c (ffffffff814bda66)
Location: include/linux/spinlock.h:356
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_netdev_notifier_handler
  - security/selinux/netif.c:sel_netif_flush
  - security/selinux/netif.c:sel_netif_sid_slow
```
```
In security/selinux/netnode.c (ffffffff814be0a5)
Location: include/linux/spinlock.h:356
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_flush
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (ffffffff814be395)
Location: include/linux/spinlock.h:356
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_flush
  - security/selinux/netport.c:sel_netport_sid_slow
```
```
In block/genhd.c (ffffffff81559dd8)
Location: include/linux/spinlock.h:356
Inline: True
Inline callers:
  - block/genhd.c:disk_release
  - block/genhd.c:get_gendisk
  - block/genhd.c:del_gendisk
```
```
In block/blk-cgroup.c (ffffffff8156bebe)
Location: include/linux/spinlock.h:356
Inline: True
Inline callers:
  - block/blk-cgroup.c:__blkcg_punt_bio_submit
  - block/blk-cgroup.c:blkg_async_bio_workfn
```
```
In lib/xarray.c (ffffffff815fb89a)
Location: include/linux/spinlock.h:356
Inline: True
Inline callers:
  - lib/xarray.c:__xas_nomem
```
```
In drivers/connector/cn_queue.c (ffffffff817acc95)
Location: include/linux/spinlock.h:356
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_free_dev
  - drivers/connector/cn_queue.c:cn_queue_del_callback
  - drivers/connector/cn_queue.c:cn_queue_add_callback
```
```
In drivers/connector/connector.c (ffffffff817acddf)
Location: include/linux/spinlock.h:356
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_proc_show
  - drivers/connector/connector.c:cn_call_callback
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/scsi/sd_zbc.c (ffffffff81848b64)
Location: include/linux/spinlock.h:356
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_zone_wp_update
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
  - drivers/scsi/sd_zbc.c:sd_zbc_update_wp_offset_workfn
  - drivers/scsi/sd_zbc.c:sd_zbc_update_wp_offset_workfn
```
```
In drivers/net/tun.c (ffffffff8188b2ed)
Location: include/linux/spinlock.h:356
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
In drivers/net/ppp/ppp_generic.c (ffffffff81891db5)
Location: include/linux/spinlock.h:356
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_disconnect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_disconnect_channel
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
```
```
In drivers/net/xen-netfront.c (ffffffff8189a47f)
Location: include/linux/spinlock.h:356
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:xennet_release_rx_bufs
  - drivers/net/xen-netfront.c:xennet_open
```
```
In net/core/sock.c (ffffffff819e80c5)
Location: include/linux/spinlock.h:356
Inline: True
Inline callers:
  - net/core/sock.c:release_sock
  - net/core/sock.c:lock_sock_nested
  - net/core/sock.c:__sk_flush_backlog
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__lock_sock
```
```
In net/core/request_sock.c (ffffffff819e9785)
Location: include/linux/spinlock.h:356
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/core/datagram.c (ffffffff819f4b5d)
Location: include/linux/spinlock.h:356
Inline: True
Inline callers:
  - net/core/datagram.c:__sk_queue_drop_skb
```
```
In net/core/gen_stats.c (ffffffff819f7674)
Location: include/linux/spinlock.h:356
Inline: True
Inline callers:
  - net/core/gen_stats.c:gnet_stats_start_copy_compat
```
```
In net/core/gen_estimator.c (ffffffff819f7c87)
Location: include/linux/spinlock.h:356
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/net_namespace.c (ffffffff819f900f)
Location: include/linux/spinlock.h:356
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:unhash_nsid
  - net/core/net_namespace.c:unhash_nsid
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/dev.c (ffffffff81a0c21f)
Location: include/linux/spinlock.h:356
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
In net/core/dev_addr_lists.c (ffffffff81a10225)
Location: include/linux/spinlock.h:356
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
In net/core/neighbour.c (ffffffff81a16c0e)
Location: include/linux/spinlock.h:356
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/core/rtnetlink.c (ffffffff81a1e67d)
Location: include/linux/spinlock.h:356
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_fdb_dump
```
```
In net/core/sock_reuseport.c (ffffffff81a34e37)
Location: include/linux/spinlock.h:356
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_attach_prog
  - net/core/sock_reuseport.c:reuseport_detach_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_alloc
```
```
In net/core/page_pool.c (ffffffff81a3a968)
Location: include/linux/spinlock.h:356
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_empty_ring
  - net/core/page_pool.c:page_pool_put_page
```
```
In net/core/net-procfs.c (ffffffff81a3b7ab)
Location: include/linux/spinlock.h:356
Inline: True
```
```
In net/core/skmsg.c (ffffffff81a3d4c5)
Location: include/linux/spinlock.h:356
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_link_pop
```
```
In net/core/sock_map.c (ffffffff81a4f80d)
Location: include/linux/spinlock.h:356
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_del_link
```
```
In net/core/devlink.c (ffffffff81a5ad45)
Location: include/linux/spinlock.h:356
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_port_type_set
  - net/core/devlink.c:devlink_nl_port_fill
```
```
In net/sched/sch_generic.c (ffffffff81a666a9)
Location: include/linux/spinlock.h:356
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_reset_queue
  - net/sched/sch_generic.c:dev_reset_queue
  - net/sched/sch_generic.c:dev_graft_qdisc
```
```
In net/sched/sch_mq.c (ffffffff81a672a0)
Location: include/linux/spinlock.h:356
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump
```
```
In net/sched/sch_api.c (ffffffff81a686d9)
Location: include/linux/spinlock.h:356
Inline: True
Inline callers:
  - net/sched/sch_api.c:tcf_node_bind
  - net/sched/sch_api.c:qdisc_class_hash_grow
```
```
In net/sched/cls_api.c (ffffffff81a71937)
Location: include/linux/spinlock.h:356
Inline: True
```
```
In net/ipv4/route.c (ffffffff81a956a3)
Location: include/linux/spinlock.h:356
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
In net/ipv4/inetpeer.c (ffffffff81a97646)
Location: include/linux/spinlock.h:356
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/inet_hashtables.c (ffffffff81aa44be)
Location: include/linux/spinlock.h:356
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_unhash
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81aa6516)
Location: include/linux/spinlock.h:356
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
In net/ipv4/tcp_ipv4.c (ffffffff81ac42f8)
Location: include/linux/spinlock.h:356
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:established_get_first
```
```
In net/ipv4/tcp_metrics.c (ffffffff81acb961)
Location: include/linux/spinlock.h:356
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_flush_all
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
  - net/ipv4/tcp_metrics.c:tcpm_new
```
```
In net/ipv4/raw.c (ffffffff81ad021a)
Location: include/linux/spinlock.h:356
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81ad2564)
Location: include/linux/spinlock.h:356
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_get_first
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/af_inet.c (ffffffff81ae1c23)
Location: include/linux/spinlock.h:356
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_register_protosw
```
```
In net/ipv4/igmp.c (ffffffff81ae69fc)
Location: include/linux/spinlock.h:356
Inline: True
Inline callers:
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
  - net/ipv4/igmp.c:igmpv3_send_cr
  - net/ipv4/igmp.c:igmpv3_send_cr
```
```
In net/ipv4/fib_semantics.c (ffffffff81aef63c)
Location: include/linux/spinlock.h:356
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_info_hash_move
  - net/ipv4/fib_semantics.c:fib_release_info
```
```
In net/ipv4/inet_fragment.c (ffffffff81af51c9)
Location: include/linux/spinlock.h:356
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frags_free_cb
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81afe280)
Location: include/linux/spinlock.h:356
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
```
In net/ipv4/ipmr.c (ffffffff81b03fef)
Location: include/linux/spinlock.h:356
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
```
```
In net/ipv4/ipmr_base.c (ffffffff81b0697b)
Location: include/linux/spinlock.h:356
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_table_dump
  - net/ipv4/ipmr_base.c:mr_mfc_seq_next
  - net/ipv4/ipmr_base.c:mr_mfc_seq_next
```
```
In net/ipv4/tcp_bpf.c (ffffffff81b09b9a)
Location: include/linux/spinlock.h:356
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_get_proto
```
```
In net/ipv4/udp_bpf.c (ffffffff81b09cee)
Location: include/linux/spinlock.h:356
Inline: True
Inline callers:
  - net/ipv4/udp_bpf.c:udp_bpf_get_proto
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81b0adc2)
Location: include/linux/spinlock.h:356
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_check
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_invalidate
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b13fc7)
Location: include/linux/spinlock.h:356
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
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_bydst_resize
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
```
```
In net/xfrm/xfrm_state.c (ffffffff81b1851a)
Location: include/linux/spinlock.h:356
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
In net/xfrm/xfrm_input.c (ffffffff81b1d525)
Location: include/linux/spinlock.h:356
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo
  - net/xfrm/xfrm_input.c:xfrm_input_register_afinfo
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1fe03)
Location: include/linux/spinlock.h:356
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/af_inet6.c (ffffffff81b2a1c4)
Location: include/linux/spinlock.h:356
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_register_protosw
```
```
In net/ipv6/addrconf.c (ffffffff81b3ea25)
Location: include/linux/spinlock.h:356
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
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/route.c (ffffffff81b4ab54)
Location: include/linux/spinlock.h:356
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
In net/ipv6/ip6_fib.c (ffffffff81b4ca25)
Location: include/linux/spinlock.h:356
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:__fib6_clean_all
  - net/ipv6/ip6_fib.c:fib6_update_sernum_stub
  - net/ipv6/ip6_fib.c:fib6_tables_dump
```
```
In net/ipv6/raw.c (ffffffff81b5bbba)
Location: include/linux/spinlock.h:356
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff81b61cfb)
Location: include/linux/spinlock.h:356
Inline: True
Inline callers:
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
In net/ipv6/ip6_flowlabel.c (ffffffff81b70755)
Location: include/linux/spinlock.h:356
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
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
In net/ipv6/ip6mr.c (ffffffff81b756dd)
Location: include/linux/spinlock.h:356
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
```
```
In net/ipv6/calipso.c (ffffffff81b7c533)
Location: include/linux/spinlock.h:356
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_cache_check
  - net/ipv6/calipso.c:calipso_cache_invalidate
```
```
In net/packet/af_packet.c (ffffffff81b89c26)
Location: include/linux/spinlock.h:356
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
In net/dcb/dcbnl.c (ffffffff81b98dd2)
Location: include/linux/spinlock.h:356
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
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
```
```
In net/switchdev/switchdev.c (ffffffff81b9d71d)
Location: include/linux/spinlock.h:356
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_deferred_process
```
```
In net/xdp/xsk.c (ffffffff81ba6d7d)
Location: include/linux/spinlock.h:356
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_delete_from_maps
  - net/xdp/xsk.c:xsk_generic_rcv
```
```
In net/xdp/xskmap.c (ffffffff81ba93e5)
Location: include/linux/spinlock.h:356
Inline: True
Inline callers:
  - net/xdp/xskmap.c:xsk_map_try_sock_delete
  - net/xdp/xskmap.c:xsk_map_delete_elem
  - net/xdp/xskmap.c:xsk_map_update_elem
  - net/xdp/xskmap.c:xsk_map_update_elem
  - net/xdp/xskmap.c:xsk_map_sock_delete
```
```
In net/mptcp/protocol.c (ffffffff81bacacf)
Location: include/linux/spinlock.h:356
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_shutdown
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_finish_join
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:mptcp_sendmsg
```
```
In net/mptcp/subflow.c (ffffffff81bafec8)
Location: include/linux/spinlock.h:356
Inline: True
Inline callers:
  - net/mptcp/subflow.c:__mptcp_subflow_connect
```
```
In net/mptcp/token.c (ffffffff81bb1d45)
Location: include/linux/spinlock.h:356
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_destroy
  - net/mptcp/token.c:mptcp_token_destroy_request
  - net/mptcp/token.c:mptcp_token_get_sock
  - net/mptcp/token.c:mptcp_token_new_accept
  - net/mptcp/token.c:mptcp_token_new_connect
  - net/mptcp/token.c:mptcp_token_new_request
```
```
In net/mptcp/pm.c (ffffffff81bb2356)
Location: include/linux/spinlock.h:356
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
In net/mptcp/pm_netlink.c (ffffffff81bb37d6)
Location: include/linux/spinlock.h:356
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_limits
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_dump_addrs
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
In kernel/cgroup/cgroup.c (ffffffff8116ce60)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_create
  - kernel/cgroup/cgroup.c:css_create
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
```
```
In kernel/bpf/core.c (ffffffff811f90c5)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_ksym_del
  - kernel/bpf/core.c:bpf_ksym_add
```
```
In kernel/bpf/syscall.c (ffffffff812010b4)
Location: include/linux/spinlock.h:357
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
In kernel/bpf/local_storage.c (ffffffff8122061c)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_link
  - kernel/bpf/local_storage.c:cgroup_storage_map_free
  - kernel/bpf/local_storage.c:cgroup_storage_get_next_key
  - kernel/bpf/local_storage.c:cgroup_storage_lookup
```
```
In kernel/bpf/btf.c (ffffffff81223389)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_alloc_id
```
```
In kernel/bpf/reuseport_array.c (ffffffff812377d3)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem
  - kernel/bpf/reuseport_array.c:reuseport_array_delete_elem
```
```
In kernel/watch_queue.c (ffffffff812577f9)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_clear
  - kernel/watch_queue.c:watch_queue_clear
  - kernel/watch_queue.c:remove_watch_from_object
  - kernel/watch_queue.c:add_watch_to_object
```
```
In mm/page-writeback.c (ffffffff81262bff)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - mm/page-writeback.c:bdi_set_max_ratio
  - mm/page-writeback.c:bdi_set_min_ratio
```
```
In mm/backing-dev.c (ffffffff81281f0d)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:bdi_get_by_id
  - mm/backing-dev.c:wb_shutdown
  - mm/backing-dev.c:wb_wakeup_delayed
```
```
In fs/fs-writeback.c (ffffffff813560ab)
Location: include/linux/spinlock.h:357
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
In fs/io_uring.c (ffffffff8138f03a)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - fs/io_uring.c:__io_sqe_files_update
  - fs/io_uring.c:io_sqe_files_register
  - fs/io_uring.c:io_file_data_ref_zero
  - fs/io_uring.c:io_sqe_files_unregister
  - fs/io_uring.c:io_sqe_files_unregister
```
```
In security/selinux/netif.c (ffffffff814db4c6)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_netdev_notifier_handler
  - security/selinux/netif.c:sel_netif_flush
  - security/selinux/netif.c:sel_netif_sid_slow
```
```
In security/selinux/netnode.c (ffffffff814dbaf5)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_flush
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (ffffffff814dbdd5)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_flush
  - security/selinux/netport.c:sel_netport_sid_slow
```
```
In block/blk-cgroup.c (ffffffff81586bce)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - block/blk-cgroup.c:__blkcg_punt_bio_submit
  - block/blk-cgroup.c:blkg_async_bio_workfn
```
```
In lib/xarray.c (ffffffff81620427)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - lib/xarray.c:__xas_nomem
```
```
In drivers/connector/cn_queue.c (ffffffff817c1865)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_free_dev
  - drivers/connector/cn_queue.c:cn_queue_del_callback
  - drivers/connector/cn_queue.c:cn_queue_add_callback
```
```
In drivers/connector/connector.c (ffffffff817c196f)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_proc_show
  - drivers/connector/connector.c:cn_call_callback
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/scsi/sd_zbc.c (ffffffff8185903c)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_zone_wp_update
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
  - drivers/scsi/sd_zbc.c:sd_zbc_update_wp_offset_workfn
  - drivers/scsi/sd_zbc.c:sd_zbc_update_wp_offset_workfn
```
```
In drivers/net/tun.c (ffffffff8189948d)
Location: include/linux/spinlock.h:357
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
In drivers/net/ppp/ppp_generic.c (ffffffff818a00f5)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_disconnect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_disconnect_channel
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
```
```
In drivers/net/xen-netfront.c (ffffffff818a845c)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:xennet_release_rx_bufs
  - drivers/net/xen-netfront.c:xennet_open
```
```
In net/core/sock.c (ffffffff819e7d35)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - net/core/sock.c:release_sock
  - net/core/sock.c:lock_sock_nested
  - net/core/sock.c:__sk_flush_backlog
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__lock_sock
```
```
In net/core/request_sock.c (ffffffff819e9525)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/core/datagram.c (ffffffff819f484d)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - net/core/datagram.c:__sk_queue_drop_skb
```
```
In net/core/gen_stats.c (ffffffff819f70e4)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - net/core/gen_stats.c:gnet_stats_start_copy_compat
```
```
In net/core/gen_estimator.c (ffffffff819f76f9)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/net_namespace.c (ffffffff819f8aee)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:unhash_nsid
  - net/core/net_namespace.c:unhash_nsid
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/dev.c (ffffffff81a06ba4)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - net/core/dev.c:netif_set_real_num_tx_queues
```
```
In net/core/neighbour.c (ffffffff81a16b21)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/core/sock_reuseport.c (ffffffff81a37177)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_attach_prog
  - net/core/sock_reuseport.c:reuseport_detach_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_alloc
```
```
In net/core/page_pool.c (ffffffff81a3ce88)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_empty_ring
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_page
```
```
In net/core/skmsg.c (ffffffff81a400a5)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_link_pop
```
```
In net/core/sock_map.c (ffffffff81a556a5)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_del_link
```
```
In net/core/devlink.c (ffffffff81a6668a)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_port_type_set
  - net/core/devlink.c:devlink_nl_port_fill
```
```
In net/sched/sch_generic.c (ffffffff81a6e789)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_reset_queue
  - net/sched/sch_generic.c:dev_reset_queue
  - net/sched/sch_generic.c:dev_graft_qdisc
```
```
In net/sched/sch_mq.c (ffffffff81a6f250)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump
```
```
In net/sched/sch_api.c (ffffffff81a70de9)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - net/sched/sch_api.c:tcf_node_bind
  - net/sched/sch_api.c:qdisc_class_hash_grow
```
```
In net/sched/cls_api.c (ffffffff81a7a3b7)
Location: include/linux/spinlock.h:357
Inline: True
```
```
In net/ipv4/route.c (ffffffff81a9f733)
Location: include/linux/spinlock.h:357
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
In net/ipv4/inetpeer.c (ffffffff81aa1612)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/inet_hashtables.c (ffffffff81aaeb0e)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_unhash
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ab0b66)
Location: include/linux/spinlock.h:357
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
In net/ipv4/tcp_ipv4.c (ffffffff81ad0d77)
Location: include/linux/spinlock.h:357
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ad7922)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_flush_all
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
  - net/ipv4/tcp_metrics.c:tcpm_new
```
```
In net/ipv4/raw.c (ffffffff81adc190)
Location: include/linux/spinlock.h:357
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81ae1033)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/af_inet.c (ffffffff81aeeaa3)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_register_protosw
```
```
In net/ipv4/igmp.c (ffffffff81af38cc)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
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
  - net/ipv4/igmp.c:igmpv3_send_cr
  - net/ipv4/igmp.c:igmpv3_send_cr
```
```
In net/ipv4/fib_semantics.c (ffffffff81afc539)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_info_hash_move
  - net/ipv4/fib_semantics.c:fib_release_info
```
```
In net/ipv4/inet_fragment.c (ffffffff81b02589)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frags_free_cb
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81b0c2f0)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
```
In net/ipv4/ipmr.c (ffffffff81b12164)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
```
```
In net/ipv4/ipmr_base.c (ffffffff81b14b6b)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_table_dump
  - net/ipv4/ipmr_base.c:mr_mfc_seq_next
  - net/ipv4/ipmr_base.c:mr_mfc_seq_next
```
```
In net/ipv4/tcp_bpf.c (ffffffff81b17fa3)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_get_proto
```
```
In net/ipv4/udp_bpf.c (ffffffff81b180da)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - net/ipv4/udp_bpf.c:udp_bpf_get_proto
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81b191a2)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_check
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_invalidate
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b22367)
Location: include/linux/spinlock.h:357
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
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_bydst_resize
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
```
```
In net/xfrm/xfrm_state.c (ffffffff81b2710a)
Location: include/linux/spinlock.h:357
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
In net/xfrm/xfrm_input.c (ffffffff81b2bd35)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo
  - net/xfrm/xfrm_input.c:xfrm_input_register_afinfo
```
```
In net/xfrm/xfrm_output.c (ffffffff81b2e713)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/af_inet6.c (ffffffff81b38b24)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_register_protosw
```
```
In net/ipv6/addrconf.c (ffffffff81b4d5b5)
Location: include/linux/spinlock.h:357
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
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/route.c (ffffffff81b597e4)
Location: include/linux/spinlock.h:357
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
In net/ipv6/ip6_fib.c (ffffffff81b5b675)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:__fib6_clean_all
  - net/ipv6/ip6_fib.c:fib6_update_sernum_stub
  - net/ipv6/ip6_fib.c:fib6_tables_dump
```
```
In net/ipv6/raw.c (ffffffff81b6a3f0)
Location: include/linux/spinlock.h:357
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff81b7049b)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
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
In net/ipv6/ip6_flowlabel.c (ffffffff81b7f08e)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
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
In net/ipv6/ip6mr.c (ffffffff81b84452)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
```
```
In net/ipv6/calipso.c (ffffffff81b8b573)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_cache_check
  - net/ipv6/calipso.c:calipso_cache_invalidate
```
```
In net/packet/af_packet.c (ffffffff81b99741)
Location: include/linux/spinlock.h:357
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
In net/dcb/dcbnl.c (ffffffff81ba8aa2)
Location: include/linux/spinlock.h:357
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
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
```
```
In net/switchdev/switchdev.c (ffffffff81bad02d)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_deferred_process
```
```
In net/xdp/xsk.c (ffffffff81bb6540)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xsk.c:xsk_generic_rcv
```
```
In net/xdp/xskmap.c (ffffffff81bb8bb5)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - net/xdp/xskmap.c:xsk_map_try_sock_delete
  - net/xdp/xskmap.c:xsk_map_delete_elem
  - net/xdp/xskmap.c:xsk_map_update_elem
  - net/xdp/xskmap.c:xsk_map_update_elem
  - net/xdp/xskmap.c:xsk_map_sock_delete
```
```
In net/mptcp/protocol.c (ffffffff81bbe613)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_finish_join
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:mptcp_disconnect
  - net/mptcp/protocol.c:__mptcp_destroy_sock
  - net/mptcp/protocol.c:__mptcp_check_send_data_fin
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:pm_work
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:__mptcp_move_skbs
  - net/mptcp/protocol.c:__mptcp_move_skbs
  - net/mptcp/protocol.c:__mptcp_move_skbs
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:__mptcp_push_pending
  - net/mptcp/protocol.c:mptcp_alloc_tx_skb
  - net/mptcp/protocol.c:mptcp_data_ready
```
```
In net/mptcp/subflow.c (ffffffff81bc3a5b)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - net/mptcp/subflow.c:__mptcp_subflow_connect
  - net/mptcp/subflow.c:__mptcp_subflow_connect
  - net/mptcp/subflow.c:subflow_error_report
```
```
In net/mptcp/options.c (ffffffff81bc522b)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_incoming_options
  - net/mptcp/options.c:ack_update_msk
```
```
In net/mptcp/token.c (ffffffff81bc6111)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_destroy
  - net/mptcp/token.c:mptcp_token_destroy_request
  - net/mptcp/token.c:mptcp_token_accept
  - net/mptcp/token.c:mptcp_token_new_connect
  - net/mptcp/token.c:mptcp_token_new_request
```
```
In net/mptcp/pm.c (ffffffff81bc6d35)
Location: include/linux/spinlock.h:357
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
In net/mptcp/pm_netlink.c (ffffffff81bc7c2b)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_limits
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_dump_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_addr
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_flush_addrs
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
In net/mptcp/syncookies.c (ffffffff81bc9511)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
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
In kernel/cgroup/cgroup.c (ffffffff8116dac0)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_create
  - kernel/cgroup/cgroup.c:css_create
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
```
```
In kernel/bpf/core.c (ffffffff811f9ea5)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_ksym_del
  - kernel/bpf/core.c:bpf_ksym_add
```
```
In kernel/bpf/syscall.c (ffffffff812019d5)
Location: include/linux/spinlock.h:357
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
In kernel/bpf/local_storage.c (ffffffff812240ac)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_link
  - kernel/bpf/local_storage.c:cgroup_storage_map_free
  - kernel/bpf/local_storage.c:cgroup_storage_get_next_key
  - kernel/bpf/local_storage.c:cgroup_storage_lookup
```
```
In kernel/bpf/btf.c (ffffffff81227e39)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_alloc_id
```
```
In kernel/bpf/reuseport_array.c (ffffffff8123bff6)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem
  - kernel/bpf/reuseport_array.c:reuseport_array_delete_elem
```
```
In kernel/watch_queue.c (ffffffff8125bc59)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_clear
  - kernel/watch_queue.c:watch_queue_clear
  - kernel/watch_queue.c:remove_watch_from_object
  - kernel/watch_queue.c:add_watch_to_object
```
```
In mm/page-writeback.c (ffffffff8126761f)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - mm/page-writeback.c:bdi_set_max_ratio
  - mm/page-writeback.c:bdi_set_min_ratio
```
```
In mm/backing-dev.c (ffffffff81286eed)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:bdi_get_by_id
  - mm/backing-dev.c:wb_shutdown
  - mm/backing-dev.c:wb_wakeup_delayed
```
```
In fs/fs-writeback.c (ffffffff8135cc9b)
Location: include/linux/spinlock.h:357
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
In security/selinux/netif.c (ffffffff814e1e46)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_netdev_notifier_handler
  - security/selinux/netif.c:sel_netif_flush
  - security/selinux/netif.c:sel_netif_sid_slow
```
```
In security/selinux/netnode.c (ffffffff814e2495)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_flush
  - security/selinux/netnode.c:sel_netnode_sid_slow
```
```
In security/selinux/netport.c (ffffffff814e2735)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_flush
  - security/selinux/netport.c:sel_netport_sid
```
```
In block/blk-cgroup.c (ffffffff8158d8de)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - block/blk-cgroup.c:__blkcg_punt_bio_submit
  - block/blk-cgroup.c:blkg_async_bio_workfn
```
```
In lib/xarray.c (ffffffff81604639)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - lib/xarray.c:__xas_nomem
```
```
In drivers/connector/cn_queue.c (ffffffff817a4d85)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_free_dev
  - drivers/connector/cn_queue.c:cn_queue_del_callback
  - drivers/connector/cn_queue.c:cn_queue_add_callback
```
```
In drivers/connector/connector.c (ffffffff817a4e8f)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_proc_show
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/net/tun.c (ffffffff8187b86d)
Location: include/linux/spinlock.h:357
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
In drivers/net/ppp/ppp_generic.c (ffffffff81882c05)
Location: include/linux/spinlock.h:357
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
  - drivers/net/ppp/ppp_generic.c:ppp_poll
  - drivers/net/ppp/ppp_generic.c:ppp_read
```
```
In drivers/net/xen-netfront.c (ffffffff8188b915)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:xennet_open
```
```
In net/core/sock.c (ffffffff819cdd05)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - net/core/sock.c:release_sock
  - net/core/sock.c:__sk_flush_backlog
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__lock_sock
  - net/core/sock.c:sock_set_priority
  - net/core/sock.c:sock_no_linger
  - net/core/sock.c:sock_set_reuseport
  - net/core/sock.c:sock_set_reuseaddr
```
```
In net/core/request_sock.c (ffffffff819cf645)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/core/datagram.c (ffffffff819da91d)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - net/core/datagram.c:__sk_queue_drop_skb
```
```
In net/core/gen_stats.c (ffffffff819dd274)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - net/core/gen_stats.c:gnet_stats_start_copy_compat
```
```
In net/core/gen_estimator.c (ffffffff819dd879)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/net_namespace.c (ffffffff819df31e)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/dev.c (ffffffff819ecbe4)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - net/core/dev.c:netif_set_real_num_tx_queues
```
```
In net/core/neighbour.c (ffffffff819fd79f)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/core/sock_reuseport.c (ffffffff81a1e2d7)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_attach_prog
  - net/core/sock_reuseport.c:reuseport_detach_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_alloc
```
```
In net/core/page_pool.c (ffffffff81a23cce)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_page
```
```
In net/core/devlink.c (ffffffff81a46bda)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_port_type_set
  - net/core/devlink.c:devlink_nl_port_fill
```
```
In net/core/skmsg.c (ffffffff81a4e3aa)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_verdict_apply
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
In net/core/sock_map.c (ffffffff81a50e9a)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_unref
```
```
In net/sched/sch_generic.c (ffffffff81a57019)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_reset_queue
  - net/sched/sch_generic.c:dev_reset_queue
  - net/sched/sch_generic.c:dev_graft_qdisc
```
```
In net/sched/sch_mq.c (ffffffff81a57b10)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump
```
```
In net/sched/sch_api.c (ffffffff81a59740)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - net/sched/sch_api.c:tcf_node_bind
  - net/sched/sch_api.c:tcf_node_bind
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/sched/sch_api.c:qdisc_class_hash_grow
```
```
In net/sched/cls_api.c (ffffffff81a60147)
Location: include/linux/spinlock.h:357
Inline: True
```
```
In net/ipv4/route.c (ffffffff81a8a669)
Location: include/linux/spinlock.h:357
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
In net/ipv4/inetpeer.c (ffffffff81a8c56c)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/inet_hashtables.c (ffffffff81a99d4e)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_unhash
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81a9bc12)
Location: include/linux/spinlock.h:357
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
In net/ipv4/tcp_ipv4.c (ffffffff81abbd84)
Location: include/linux/spinlock.h:357
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ac2abc)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_flush_all
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/raw.c (ffffffff81ac7030)
Location: include/linux/spinlock.h:357
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81accf93)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/af_inet.c (ffffffff81ada1d3)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_register_protosw
```
```
In net/ipv4/igmp.c (ffffffff81adef2c)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
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
  - net/ipv4/igmp.c:igmpv3_send_cr
  - net/ipv4/igmp.c:igmpv3_send_cr
```
```
In net/ipv4/fib_semantics.c (ffffffff81ae7d4a)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_info_hash_move
  - net/ipv4/fib_semantics.c:fib_release_info
```
```
In net/ipv4/inet_fragment.c (ffffffff81aede99)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frags_free_cb
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81af9f50)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
```
In net/ipv4/ipmr.c (ffffffff81aff8b3)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
```
```
In net/ipv4/ipmr_base.c (ffffffff81b0296b)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_table_dump
  - net/ipv4/ipmr_base.c:mr_mfc_seq_next
  - net/ipv4/ipmr_base.c:mr_mfc_seq_next
```
```
In net/ipv4/tcp_bpf.c (ffffffff81b04994)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_update_proto
```
```
In net/ipv4/udp_bpf.c (ffffffff81b05bdf)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - net/ipv4/udp_bpf.c:udp_bpf_update_proto
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81b06c1e)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_check
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_invalidate
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0ff67)
Location: include/linux/spinlock.h:357
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
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
```
```
In net/xfrm/xfrm_state.c (ffffffff81b14d2a)
Location: include/linux/spinlock.h:357
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
In net/xfrm/xfrm_input.c (ffffffff81b199a5)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo
  - net/xfrm/xfrm_input.c:xfrm_input_register_afinfo
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1c420)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/af_inet6.c (ffffffff81b26814)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_register_protosw
```
```
In net/ipv6/addrconf.c (ffffffff81b3b465)
Location: include/linux/spinlock.h:357
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
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/route.c (ffffffff81b47942)
Location: include/linux/spinlock.h:357
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
In net/ipv6/ip6_fib.c (ffffffff81b49b35)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:__fib6_clean_all
  - net/ipv6/ip6_fib.c:fib6_update_sernum_stub
  - net/ipv6/ip6_fib.c:fib6_tables_dump
```
```
In net/ipv6/raw.c (ffffffff81b58720)
Location: include/linux/spinlock.h:357
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff81b625ae)
Location: include/linux/spinlock.h:357
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
In net/ipv6/ip6_flowlabel.c (ffffffff81b6dece)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
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
In net/ipv6/ip6mr.c (ffffffff81b730ed)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
```
```
In net/ipv6/calipso.c (ffffffff81b7a3c3)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_cache_check
  - net/ipv6/calipso.c:calipso_cache_invalidate
```
```
In net/packet/af_packet.c (ffffffff81b88af2)
Location: include/linux/spinlock.h:357
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
In net/dcb/dcbnl.c (ffffffff81b97c32)
Location: include/linux/spinlock.h:357
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
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
```
```
In net/switchdev/switchdev.c (ffffffff81b9c9fd)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_deferred_enqueue
  - net/switchdev/switchdev.c:switchdev_deferred_process
```
```
In net/xdp/xsk.c (ffffffff81ba5500)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xsk.c:xsk_generic_rcv
```
```
In net/xdp/xskmap.c (ffffffff81ba7dd5)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - net/xdp/xskmap.c:xsk_map_try_sock_delete
  - net/xdp/xskmap.c:xsk_map_delete_elem
  - net/xdp/xskmap.c:xsk_map_update_elem
  - net/xdp/xskmap.c:xsk_map_update_elem
  - net/xdp/xskmap.c:xsk_map_sock_delete
```
```
In net/mptcp/protocol.c (ffffffff81bb0e54)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_finish_join
  - net/mptcp/protocol.c:mptcp_subflow_process_delegated
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:__mptcp_destroy_sock
  - net/mptcp/protocol.c:__mptcp_retrans
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:__mptcp_move_skbs
  - net/mptcp/protocol.c:__mptcp_move_skbs
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:mptcp_alloc_tx_skb
  - net/mptcp/protocol.c:__mptcp_flush_join_list
  - net/mptcp/protocol.c:mptcp_data_ready
```
```
In net/mptcp/subflow.c (ffffffff81bb40c1)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - net/mptcp/subflow.c:__mptcp_subflow_connect
  - net/mptcp/subflow.c:__mptcp_subflow_connect
  - net/mptcp/subflow.c:subflow_error_report
  - net/mptcp/subflow.c:mptcp_set_connected
```
```
In net/mptcp/options.c (ffffffff81bb5a55)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_incoming_options
  - net/mptcp/options.c:mptcp_incoming_options
```
```
In net/mptcp/token.c (ffffffff81bb6c71)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_destroy
  - net/mptcp/token.c:mptcp_token_destroy_request
  - net/mptcp/token.c:mptcp_token_accept
  - net/mptcp/token.c:mptcp_token_new_connect
  - net/mptcp/token.c:mptcp_token_new_request
```
```
In net/mptcp/pm.c (ffffffff81bb7a35)
Location: include/linux/spinlock.h:357
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
In net/mptcp/pm_netlink.c (ffffffff81bbb03e)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_flags
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_limits
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_dump_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_addr
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_flush_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_remove_addrs_list
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr
  - net/mptcp/pm_netlink.c:mptcp_nl_remove_id_zero_address
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_add_addr
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
In net/mptcp/syncookies.c (ffffffff81bbce4d)
Location: include/linux/spinlock.h:357
Inline: True
Inline callers:
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
In kernel/cgroup/cgroup.c (ffffffff8119339d)
Location: include/linux/spinlock.h:366
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_create
  - kernel/cgroup/cgroup.c:css_create
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
```
```
In kernel/bpf/core.c (ffffffff8122b575)
Location: include/linux/spinlock.h:366
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_ksym_del
  - kernel/bpf/core.c:bpf_ksym_add
```
```
In kernel/bpf/syscall.c (ffffffff8123397b)
Location: include/linux/spinlock.h:366
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
In kernel/bpf/local_storage.c (ffffffff8125bfec)
Location: include/linux/spinlock.h:366
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_link
  - kernel/bpf/local_storage.c:cgroup_storage_map_free
  - kernel/bpf/local_storage.c:cgroup_storage_get_next_key
  - kernel/bpf/local_storage.c:cgroup_storage_lookup
```
```
In kernel/bpf/btf.c (ffffffff8126669c)
Location: include/linux/spinlock.h:366
Inline: True
Inline callers:
  - kernel/bpf/btf.c:bpf_btf_find_by_name_kind
  - kernel/bpf/btf.c:bpf_btf_find_by_name_kind
  - kernel/bpf/btf.c:btf_alloc_id
```
```
In kernel/bpf/reuseport_array.c (ffffffff81276986)
Location: include/linux/spinlock.h:366
Inline: True
Inline callers:
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem
  - kernel/bpf/reuseport_array.c:reuseport_array_delete_elem
```
```
In kernel/watch_queue.c (ffffffff81297b09)
Location: include/linux/spinlock.h:366
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_clear
  - kernel/watch_queue.c:watch_queue_clear
  - kernel/watch_queue.c:remove_watch_from_object
  - kernel/watch_queue.c:add_watch_to_object
```
```
In mm/page-writeback.c (ffffffff812a405f)
Location: include/linux/spinlock.h:366
Inline: True
Inline callers:
  - mm/page-writeback.c:bdi_set_max_ratio
  - mm/page-writeback.c:bdi_set_min_ratio
```
```
In mm/backing-dev.c (ffffffff812c64a2)
Location: include/linux/spinlock.h:366
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:bdi_get_by_id
  - mm/backing-dev.c:wb_shutdown
  - mm/backing-dev.c:wb_wakeup_delayed
```
```
In fs/fs-writeback.c (ffffffff813ab07b)
Location: include/linux/spinlock.h:366
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
In security/selinux/netif.c (ffffffff8153ae46)
Location: include/linux/spinlock.h:366
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_netdev_notifier_handler
  - security/selinux/netif.c:sel_netif_flush
  - security/selinux/netif.c:sel_netif_sid_slow
```
```
In security/selinux/netnode.c (ffffffff8153b4e5)
Location: include/linux/spinlock.h:366
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_flush
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (ffffffff8153b835)
Location: include/linux/spinlock.h:366
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_flush
  - security/selinux/netport.c:sel_netport_sid
```
```
In block/blk-cgroup.c (ffffffff815f334e)
Location: include/linux/spinlock.h:366
Inline: True
Inline callers:
  - block/blk-cgroup.c:__blkcg_punt_bio_submit
  - block/blk-cgroup.c:blkg_async_bio_workfn
```
```
In lib/xarray.c (ffffffff81672f29)
Location: include/linux/spinlock.h:366
Inline: True
Inline callers:
  - lib/xarray.c:__xas_nomem
```
```
In drivers/connector/cn_queue.c (ffffffff81830705)
Location: include/linux/spinlock.h:366
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_free_dev
  - drivers/connector/cn_queue.c:cn_queue_del_callback
  - drivers/connector/cn_queue.c:cn_queue_add_callback
```
```
In drivers/connector/connector.c (ffffffff8183080f)
Location: include/linux/spinlock.h:366
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_proc_show
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/net/tun.c (ffffffff8190cd92)
Location: include/linux/spinlock.h:366
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
In drivers/net/ppp/ppp_generic.c (ffffffff819145a5)
Location: include/linux/spinlock.h:366
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
  - drivers/net/ppp/ppp_generic.c:ppp_poll
  - drivers/net/ppp/ppp_generic.c:ppp_read
```
```
In drivers/net/xen-netfront.c (ffffffff8191f4a5)
Location: include/linux/spinlock.h:366
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:xennet_open
```
```
In net/core/sock.c (ffffffff81a7d3db)
Location: include/linux/spinlock.h:366
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
In net/core/request_sock.c (ffffffff81a7f185)
Location: include/linux/spinlock.h:366
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/core/datagram.c (ffffffff81a8af9d)
Location: include/linux/spinlock.h:366
Inline: True
Inline callers:
  - net/core/datagram.c:__sk_queue_drop_skb
```
```
In net/core/gen_stats.c (ffffffff81a8d504)
Location: include/linux/spinlock.h:366
Inline: True
Inline callers:
  - net/core/gen_stats.c:gnet_stats_start_copy_compat
```
```
In net/core/gen_estimator.c (ffffffff81a8db59)
Location: include/linux/spinlock.h:366
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/net_namespace.c (ffffffff81a8f6fe)
Location: include/linux/spinlock.h:366
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/dev.c (ffffffff81a9dc2e)
Location: include/linux/spinlock.h:366
Inline: True
Inline callers:
  - net/core/dev.c:netif_set_real_num_tx_queues
```
```
In net/core/neighbour.c (ffffffff81aafdc3)
Location: include/linux/spinlock.h:366
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/core/sock_reuseport.c (ffffffff81ad1835)
Location: include/linux/spinlock.h:366
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_detach_prog
  - net/core/sock_reuseport.c:reuseport_attach_prog
  - net/core/sock_reuseport.c:reuseport_stop_listen_sock
  - net/core/sock_reuseport.c:reuseport_detach_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_alloc
```
```
In net/core/page_pool.c (ffffffff81ad8379)
Location: include/linux/spinlock.h:366
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_page
```
```
In net/core/devlink.c (ffffffff81b019db)
Location: include/linux/spinlock.h:366
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_port_type_set
  - net/core/devlink.c:devlink_nl_port_fill
```
```
In net/core/skmsg.c (ffffffff81b070c0)
Location: include/linux/spinlock.h:366
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_verdict_apply
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
In net/core/sock_map.c (ffffffff81b09f47)
Location: include/linux/spinlock.h:366
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_unref
```
```
In net/sched/sch_generic.c (ffffffff81b0fe4e)
Location: include/linux/spinlock.h:366
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_reset_queue
  - net/sched/sch_generic.c:dev_reset_queue
  - net/sched/sch_generic.c:dev_graft_qdisc
```
```
In net/sched/sch_mq.c (ffffffff81b10a80)
Location: include/linux/spinlock.h:366
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump
```
```
In net/sched/sch_api.c (ffffffff81b127f4)
Location: include/linux/spinlock.h:366
Inline: True
Inline callers:
  - net/sched/sch_api.c:tcf_node_bind
  - net/sched/sch_api.c:tcf_node_bind
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/sched/sch_api.c:qdisc_class_hash_grow
```
```
In net/sched/cls_api.c (ffffffff81b193c7)
Location: include/linux/spinlock.h:366
Inline: True
```
```
In net/ipv4/route.c (ffffffff81b45515)
Location: include/linux/spinlock.h:366
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
In net/ipv4/inetpeer.c (ffffffff81b476ac)
Location: include/linux/spinlock.h:366
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/inet_hashtables.c (ffffffff81b551be)
Location: include/linux/spinlock.h:366
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_unhash
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81b57315)
Location: include/linux/spinlock.h:366
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
In net/ipv4/tcp_ipv4.c (ffffffff81b79b1b)
Location: include/linux/spinlock.h:366
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:established_get_first
```
```
In net/ipv4/tcp_metrics.c (ffffffff81b8149c)
Location: include/linux/spinlock.h:366
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_flush_all
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/raw.c (ffffffff81b85850)
Location: include/linux/spinlock.h:366
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81b8b913)
Location: include/linux/spinlock.h:366
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/af_inet.c (ffffffff81b9936f)
Location: include/linux/spinlock.h:366
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_register_protosw
```
```
In net/ipv4/igmp.c (ffffffff81b9e40c)
Location: include/linux/spinlock.h:366
Inline: True
Inline callers:
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
  - net/ipv4/igmp.c:igmpv3_send_cr
  - net/ipv4/igmp.c:igmpv3_send_cr
```
```
In net/ipv4/fib_semantics.c (ffffffff81ba7bed)
Location: include/linux/spinlock.h:366
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_info_hash_move
  - net/ipv4/fib_semantics.c:fib_release_info
```
```
In net/ipv4/inet_fragment.c (ffffffff81bae249)
Location: include/linux/spinlock.h:366
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frags_free_cb
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81bbad18)
Location: include/linux/spinlock.h:366
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
```
In net/ipv4/ipmr.c (ffffffff81bc1688)
Location: include/linux/spinlock.h:366
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
```
```
In net/ipv4/ipmr_base.c (ffffffff81bc4971)
Location: include/linux/spinlock.h:366
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_table_dump
  - net/ipv4/ipmr_base.c:mr_mfc_seq_next
  - net/ipv4/ipmr_base.c:mr_mfc_seq_next
```
```
In net/ipv4/tcp_bpf.c (ffffffff81bc6d3b)
Location: include/linux/spinlock.h:366
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_update_proto
```
```
In net/ipv4/udp_bpf.c (ffffffff81bc873f)
Location: include/linux/spinlock.h:366
Inline: True
Inline callers:
  - net/ipv4/udp_bpf.c:udp_bpf_update_proto
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81bc9a7e)
Location: include/linux/spinlock.h:366
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_check
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_invalidate
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bd3590)
Location: include/linux/spinlock.h:366
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
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
```
```
In net/xfrm/xfrm_state.c (ffffffff81bd8d5a)
Location: include/linux/spinlock.h:366
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
In net/xfrm/xfrm_input.c (ffffffff81bde165)
Location: include/linux/spinlock.h:366
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo
  - net/xfrm/xfrm_input.c:xfrm_input_register_afinfo
```
```
In net/xfrm/xfrm_output.c (ffffffff81be0e86)
Location: include/linux/spinlock.h:366
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/unix/unix_bpf.c (ffffffff81beba25)
Location: include/linux/spinlock.h:366
Inline: True
Inline callers:
  - net/unix/unix_bpf.c:unix_stream_bpf_update_proto
  - net/unix/unix_bpf.c:unix_dgram_bpf_update_proto
```
```
In net/ipv6/af_inet6.c (ffffffff81bec277)
Location: include/linux/spinlock.h:366
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_register_protosw
```
```
In net/ipv6/addrconf.c (ffffffff81c01c69)
Location: include/linux/spinlock.h:366
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
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/route.c (ffffffff81c0ebc5)
Location: include/linux/spinlock.h:366
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
In net/ipv6/ip6_fib.c (ffffffff81c10995)
Location: include/linux/spinlock.h:366
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:__fib6_clean_all
  - net/ipv6/ip6_fib.c:fib6_update_sernum_stub
  - net/ipv6/ip6_fib.c:fib6_tables_dump
```
```
In net/ipv6/raw.c (ffffffff81c1fab0)
Location: include/linux/spinlock.h:366
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff81c2a03e)
Location: include/linux/spinlock.h:366
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
In net/ipv6/ip6_flowlabel.c (ffffffff81c35dbe)
Location: include/linux/spinlock.h:366
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
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
In net/ipv6/ip6mr.c (ffffffff81c3d67b)
Location: include/linux/spinlock.h:366
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
```
```
In net/ipv6/calipso.c (ffffffff81c45083)
Location: include/linux/spinlock.h:366
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_cache_check
  - net/ipv6/calipso.c:calipso_cache_invalidate
```
```
In net/packet/af_packet.c (ffffffff81c54bf4)
Location: include/linux/spinlock.h:366
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
In net/dcb/dcbnl.c (ffffffff81c64c6a)
Location: include/linux/spinlock.h:366
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
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
```
```
In net/switchdev/switchdev.c (ffffffff81c69bf2)
Location: include/linux/spinlock.h:366
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_deferred_enqueue
  - net/switchdev/switchdev.c:switchdev_deferred_process
```
```
In net/xdp/xsk.c (ffffffff81c73080)
Location: include/linux/spinlock.h:366
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xsk.c:xsk_generic_rcv
```
```
In net/xdp/xskmap.c (ffffffff81c75a65)
Location: include/linux/spinlock.h:366
Inline: True
Inline callers:
  - net/xdp/xskmap.c:xsk_map_try_sock_delete
  - net/xdp/xskmap.c:xsk_map_delete_elem
  - net/xdp/xskmap.c:xsk_map_update_elem
  - net/xdp/xskmap.c:xsk_map_update_elem
  - net/xdp/xskmap.c:xsk_map_sock_delete
```
```
In net/mptcp/protocol.c (ffffffff81c7ef39)
Location: include/linux/spinlock.h:366
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_finish_join
  - net/mptcp/protocol.c:mptcp_subflow_process_delegated
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:__mptcp_destroy_sock
  - net/mptcp/protocol.c:__mptcp_retrans
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:__mptcp_move_skbs
  - net/mptcp/protocol.c:__mptcp_move_skbs
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:mptcp_alloc_tx_skb
  - net/mptcp/protocol.c:mptcp_data_ready
```
```
In net/mptcp/subflow.c (ffffffff81c8281e)
Location: include/linux/spinlock.h:366
Inline: True
Inline callers:
  - net/mptcp/subflow.c:__mptcp_subflow_connect
  - net/mptcp/subflow.c:__mptcp_subflow_connect
  - net/mptcp/subflow.c:subflow_error_report
  - net/mptcp/subflow.c:mptcp_set_connected
```
```
In net/mptcp/options.c (ffffffff81c84770)
Location: include/linux/spinlock.h:366
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_incoming_options
  - net/mptcp/options.c:mptcp_incoming_options
```
```
In net/mptcp/token.c (ffffffff81c85ca1)
Location: include/linux/spinlock.h:366
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_destroy
  - net/mptcp/token.c:mptcp_token_destroy_request
  - net/mptcp/token.c:mptcp_token_accept
  - net/mptcp/token.c:mptcp_token_new_connect
  - net/mptcp/token.c:mptcp_token_new_request
```
```
In net/mptcp/pm.c (ffffffff81c86f05)
Location: include/linux/spinlock.h:366
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
In net/mptcp/pm_netlink.c (ffffffff81c8a9f5)
Location: include/linux/spinlock.h:366
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_flags
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_flags
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_limits
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_dump_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_addr
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_flush_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_remove_addrs_list
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr
  - net/mptcp/pm_netlink.c:mptcp_nl_remove_id_zero_address
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_add_addr
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
In net/mptcp/syncookies.c (ffffffff81c8cd13)
Location: include/linux/spinlock.h:366
Inline: True
Inline callers:
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
In kernel/cgroup/cgroup.c (ffffffff811c4667)
Location: include/linux/spinlock.h:352
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_create
  - kernel/cgroup/cgroup.c:css_create
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
```
```
In kernel/bpf/core.c (ffffffff8126cfd5)
Location: include/linux/spinlock.h:352
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_ksym_del
  - kernel/bpf/core.c:bpf_ksym_add
```
```
In kernel/bpf/syscall.c (ffffffff8127754c)
Location: include/linux/spinlock.h:352
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
In kernel/bpf/local_storage.c (ffffffff812a5bbc)
Location: include/linux/spinlock.h:352
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_link
  - kernel/bpf/local_storage.c:cgroup_storage_map_free
  - kernel/bpf/local_storage.c:cgroup_storage_get_next_key
  - kernel/bpf/local_storage.c:cgroup_storage_lookup
```
```
In kernel/bpf/btf.c (ffffffff812aa9d9)
Location: include/linux/spinlock.h:352
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_alloc_id
  - kernel/bpf/btf.c:bpf_find_btf_id
  - kernel/bpf/btf.c:bpf_find_btf_id
```
```
In kernel/bpf/reuseport_array.c (ffffffff812c6477)
Location: include/linux/spinlock.h:352
Inline: True
Inline callers:
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem
  - kernel/bpf/reuseport_array.c:reuseport_array_delete_elem
```
```
In kernel/watch_queue.c (ffffffff812edde8)
Location: include/linux/spinlock.h:352
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_clear
  - kernel/watch_queue.c:watch_queue_clear
  - kernel/watch_queue.c:remove_watch_from_object
  - kernel/watch_queue.c:add_watch_to_object
```
```
In mm/page-writeback.c (ffffffff812fc12f)
Location: include/linux/spinlock.h:352
Inline: True
Inline callers:
  - mm/page-writeback.c:bdi_set_max_ratio
  - mm/page-writeback.c:bdi_set_min_ratio
```
```
In mm/backing-dev.c (ffffffff81323132)
Location: include/linux/spinlock.h:352
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:bdi_register_va
  - mm/backing-dev.c:bdi_get_by_id
```
```
In security/selinux/netif.c (ffffffff815d25a5)
Location: include/linux/spinlock.h:352
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_netdev_notifier_handler
  - security/selinux/netif.c:sel_netif_flush
  - security/selinux/netif.c:sel_netif_sid_slow
```
```
In security/selinux/netnode.c (ffffffff815d2cc5)
Location: include/linux/spinlock.h:352
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_flush
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (ffffffff815d3065)
Location: include/linux/spinlock.h:352
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_flush
  - security/selinux/netport.c:sel_netport_sid
```
```
In block/blk-cgroup.c (ffffffff816a48ee)
Location: include/linux/spinlock.h:352
Inline: True
Inline callers:
  - block/blk-cgroup.c:__blkcg_punt_bio_submit
  - block/blk-cgroup.c:blkg_async_bio_workfn
```
```
In lib/xarray.c (ffffffff8178c3bd)
Location: include/linux/spinlock.h:352
Inline: True
Inline callers:
  - lib/xarray.c:__xas_nomem
```
```
In drivers/connector/cn_queue.c (ffffffff81971a25)
Location: include/linux/spinlock.h:352
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_free_dev
  - drivers/connector/cn_queue.c:cn_queue_del_callback
  - drivers/connector/cn_queue.c:cn_queue_add_callback
```
```
In drivers/connector/connector.c (ffffffff81971b5f)
Location: include/linux/spinlock.h:352
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_proc_show
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/net/tun.c (ffffffff81a61792)
Location: include/linux/spinlock.h:352
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
In drivers/net/ppp/ppp_generic.c (ffffffff81a69b97)
Location: include/linux/spinlock.h:352
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
  - drivers/net/ppp/ppp_generic.c:ppp_poll
  - drivers/net/ppp/ppp_generic.c:ppp_read
```
```
In drivers/net/xen-netfront.c (ffffffff81a73770)
Location: include/linux/spinlock.h:352
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:xennet_open
```
```
In net/core/sock.c (ffffffff81bf0a2b)
Location: include/linux/spinlock.h:352
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
In net/core/request_sock.c (ffffffff81bf3435)
Location: include/linux/spinlock.h:352
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/core/datagram.c (ffffffff81c00732)
Location: include/linux/spinlock.h:352
Inline: True
Inline callers:
  - net/core/datagram.c:__sk_queue_drop_skb
```
```
In net/core/gen_stats.c (ffffffff81c02ee4)
Location: include/linux/spinlock.h:352
Inline: True
Inline callers:
  - net/core/gen_stats.c:gnet_stats_start_copy_compat
```
```
In net/core/gen_estimator.c (ffffffff81c03681)
Location: include/linux/spinlock.h:352
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/net_namespace.c (ffffffff81c0552c)
Location: include/linux/spinlock.h:352
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/dev.c (ffffffff81c1705f)
Location: include/linux/spinlock.h:352
Inline: True
Inline callers:
  - net/core/dev.c:netif_set_real_num_tx_queues
```
```
In net/core/neighbour.c (ffffffff81c28d57)
Location: include/linux/spinlock.h:352
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/core/sock_reuseport.c (ffffffff81c4f145)
Location: include/linux/spinlock.h:352
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_detach_prog
  - net/core/sock_reuseport.c:reuseport_attach_prog
  - net/core/sock_reuseport.c:reuseport_stop_listen_sock
  - net/core/sock_reuseport.c:reuseport_detach_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_alloc
```
```
In net/core/page_pool.c (ffffffff81c59189)
Location: include/linux/spinlock.h:352
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_defragged_page
```
```
In net/core/devlink.c (ffffffff81c80ffc)
Location: include/linux/spinlock.h:352
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_port_type_set
  - net/core/devlink.c:devlink_nl_port_fill
```
```
In net/core/skmsg.c (ffffffff81c8bc9f)
Location: include/linux/spinlock.h:352
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_verdict_apply
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
In net/core/sock_map.c (ffffffff81c901a8)
Location: include/linux/spinlock.h:352
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_unref
```
```
In net/sched/sch_generic.c (ffffffff81c96fd9)
Location: include/linux/spinlock.h:352
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_reset_queue
  - net/sched/sch_generic.c:dev_reset_queue
  - net/sched/sch_generic.c:dev_graft_qdisc
```
```
In net/sched/sch_mq.c (ffffffff81c97602)
Location: include/linux/spinlock.h:352
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump
```
```
In net/sched/sch_api.c (ffffffff81c9ab34)
Location: include/linux/spinlock.h:352
Inline: True
Inline callers:
  - net/sched/sch_api.c:tcf_node_bind
  - net/sched/sch_api.c:tcf_node_bind
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/sched/sch_api.c:qdisc_class_hash_grow
```
```
In net/sched/cls_api.c (ffffffff81ca4053)
Location: include/linux/spinlock.h:352
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_setup_action
```
```
In net/sched/act_api.c (ffffffff81ca550d)
Location: include/linux/spinlock.h:352
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_offload_del_ex
  - net/sched/act_api.c:tcf_action_update_hw_stats
  - net/sched/act_api.c:tcf_action_offload_add_ex
```
```
In net/ipv4/route.c (ffffffff81cd2237)
Location: include/linux/spinlock.h:352
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
In net/ipv4/inetpeer.c (ffffffff81cd48c5)
Location: include/linux/spinlock.h:352
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/inet_hashtables.c (ffffffff81ce2d7a)
Location: include/linux/spinlock.h:352
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_unhash
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ce5291)
Location: include/linux/spinlock.h:352
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d09b6d)
Location: include/linux/spinlock.h:352
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:established_get_first
```
```
In net/ipv4/tcp_metrics.c (ffffffff81d118e7)
Location: include/linux/spinlock.h:352
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_flush_all
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/raw.c (ffffffff81d165c2)
Location: include/linux/spinlock.h:352
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81d18cb2)
Location: include/linux/spinlock.h:352
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/af_inet.c (ffffffff81d2b1af)
Location: include/linux/spinlock.h:352
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_register_protosw
```
```
In net/ipv4/igmp.c (ffffffff81d30722)
Location: include/linux/spinlock.h:352
Inline: True
Inline callers:
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
  - net/ipv4/igmp.c:igmpv3_send_cr
  - net/ipv4/igmp.c:igmpv3_send_cr
```
```
In net/ipv4/fib_semantics.c (ffffffff81d3a591)
Location: include/linux/spinlock.h:352
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_info_hash_move
  - net/ipv4/fib_semantics.c:fib_release_info
```
```
In net/ipv4/inet_fragment.c (ffffffff81d413ba)
Location: include/linux/spinlock.h:352
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frags_free_cb
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81d4ee82)
Location: include/linux/spinlock.h:352
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
```
In net/ipv4/ipmr.c (ffffffff81d56bda)
Location: include/linux/spinlock.h:352
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
```
```
In net/ipv4/ipmr_base.c (ffffffff81d599e1)
Location: include/linux/spinlock.h:352
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_table_dump
  - net/ipv4/ipmr_base.c:mr_mfc_seq_next
  - net/ipv4/ipmr_base.c:mr_mfc_seq_next
```
```
In net/ipv4/tcp_bpf.c (ffffffff81d5be88)
Location: include/linux/spinlock.h:352
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_update_proto
```
```
In net/ipv4/udp_bpf.c (ffffffff81d5de5a)
Location: include/linux/spinlock.h:352
Inline: True
Inline callers:
  - net/ipv4/udp_bpf.c:udp_bpf_update_proto
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81d5f120)
Location: include/linux/spinlock.h:352
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_check
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_invalidate
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d68b04)
Location: include/linux/spinlock.h:352
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
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
```
```
In net/xfrm/xfrm_state.c (ffffffff81d6f83e)
Location: include/linux/spinlock.h:352
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
In net/xfrm/xfrm_input.c (ffffffff81d74da5)
Location: include/linux/spinlock.h:352
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo
  - net/xfrm/xfrm_input.c:xfrm_input_register_afinfo
```
```
In net/xfrm/xfrm_output.c (ffffffff81d77d6b)
Location: include/linux/spinlock.h:352
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/unix/unix_bpf.c (ffffffff81d83edd)
Location: include/linux/spinlock.h:352
Inline: True
Inline callers:
  - net/unix/unix_bpf.c:unix_stream_bpf_update_proto
  - net/unix/unix_bpf.c:unix_dgram_bpf_update_proto
```
```
In net/ipv6/af_inet6.c (ffffffff81d847d7)
Location: include/linux/spinlock.h:352
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_register_protosw
```
```
In net/ipv6/addrconf.c (ffffffff81d910d0)
Location: include/linux/spinlock.h:352
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
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/route.c (ffffffff81da9df8)
Location: include/linux/spinlock.h:352
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
In net/ipv6/ip6_fib.c (ffffffff81dabb26)
Location: include/linux/spinlock.h:352
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:__fib6_clean_all
  - net/ipv6/ip6_fib.c:fib6_update_sernum_stub
  - net/ipv6/ip6_fib.c:fib6_tables_dump
```
```
In net/ipv6/raw.c (ffffffff81dbc772)
Location: include/linux/spinlock.h:352
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff81dc74ae)
Location: include/linux/spinlock.h:352
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
In net/ipv6/ip6_flowlabel.c (ffffffff81dd383e)
Location: include/linux/spinlock.h:352
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
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
In net/ipv6/ip6mr.c (ffffffff81ddc002)
Location: include/linux/spinlock.h:352
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
```
```
In net/ipv6/calipso.c (ffffffff81de45f7)
Location: include/linux/spinlock.h:352
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_cache_add
  - net/ipv6/calipso.c:calipso_cache_check
  - net/ipv6/calipso.c:calipso_cache_invalidate
```
```
In net/packet/af_packet.c (ffffffff81df4dee)
Location: include/linux/spinlock.h:352
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
In net/dcb/dcbnl.c (ffffffff81e07806)
Location: include/linux/spinlock.h:352
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
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
```
```
In net/switchdev/switchdev.c (ffffffff81e0cd26)
Location: include/linux/spinlock.h:352
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_deferred_enqueue
  - net/switchdev/switchdev.c:switchdev_deferred_process
```
```
In net/xdp/xsk.c (ffffffff81e16def)
Location: include/linux/spinlock.h:352
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xsk.c:xsk_generic_rcv
```
```
In net/xdp/xskmap.c (ffffffff81e19cb5)
Location: include/linux/spinlock.h:352
Inline: True
Inline callers:
  - net/xdp/xskmap.c:xsk_map_try_sock_delete
  - net/xdp/xskmap.c:xsk_map_delete_elem
  - net/xdp/xskmap.c:xsk_map_update_elem
  - net/xdp/xskmap.c:xsk_map_update_elem
  - net/xdp/xskmap.c:xsk_map_sock_delete
```
```
In net/mptcp/protocol.c (ffffffff81e2465b)
Location: include/linux/spinlock.h:352
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_finish_join
  - net/mptcp/protocol.c:mptcp_subflow_process_delegated
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:mptcp_destroy_common
  - net/mptcp/protocol.c:__mptcp_retrans
  - net/mptcp/protocol.c:__mptcp_retransmit_pending_data
  - net/mptcp/protocol.c:__mptcp_move_skbs
  - net/mptcp/protocol.c:__mptcp_move_skbs
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:mptcp_data_ready
```
```
In net/mptcp/subflow.c (ffffffff81e28735)
Location: include/linux/spinlock.h:352
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_queue_clean
  - net/mptcp/subflow.c:subflow_state_change
  - net/mptcp/subflow.c:__mptcp_subflow_connect
  - net/mptcp/subflow.c:subflow_data_ready
  - net/mptcp/subflow.c:mptcp_set_connected
```
```
In net/mptcp/options.c (ffffffff81e2aa11)
Location: include/linux/spinlock.h:352
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_incoming_options
  - net/mptcp/options.c:ack_update_msk
```
```
In net/mptcp/token.c (ffffffff81e2bf85)
Location: include/linux/spinlock.h:352
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_destroy
  - net/mptcp/token.c:mptcp_token_destroy_request
  - net/mptcp/token.c:mptcp_token_accept
  - net/mptcp/token.c:mptcp_token_new_connect
  - net/mptcp/token.c:mptcp_token_new_request
```
```
In net/mptcp/pm.c (ffffffff81e2d5f5)
Location: include/linux/spinlock.h:352
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
In net/mptcp/pm_netlink.c (ffffffff81e3189e)
Location: include/linux/spinlock.h:352
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_flags
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_flags
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_limits
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_dump_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_addr
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_flush_addrs
  - net/mptcp/pm_netlink.c:mptcp_pm_remove_addrs_and_subflows
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr
  - net/mptcp/pm_netlink.c:mptcp_nl_remove_id_zero_address
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_add_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_append_new_local_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_work
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_rm_addr_or_subflow
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_addr_send_ack
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_free_anno_list
  - net/mptcp/pm_netlink.c:mptcp_pm_del_add_timer
  - net/mptcp/pm_netlink.c:mptcp_pm_add_timer
  - net/mptcp/pm_netlink.c:mptcp_pm_sport_in_anno_list
```
```
In net/mptcp/pm_userspace.c (ffffffff81e356a2)
Location: include/linux/spinlock.h:352
Inline: True
Inline callers:
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_announce
  - net/mptcp/pm_userspace.c:mptcp_userspace_pm_get_flags_and_ifindex_by_id
  - net/mptcp/pm_userspace.c:mptcp_userspace_pm_append_new_local_addr
  - net/mptcp/pm_userspace.c:mptcp_free_local_addr_list
```
```
In net/mptcp/syncookies.c (ffffffff81e363e3)
Location: include/linux/spinlock.h:352
Inline: True
Inline callers:
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
In kernel/cgroup/cgroup.c (ffffffff83eb0791)
Location: include/linux/spinlock.h:353
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
In kernel/bpf/core.c (ffffffff812c2115)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_ksym_del
  - kernel/bpf/core.c:bpf_ksym_add
```
```
In kernel/bpf/syscall.c (ffffffff812cd790)
Location: include/linux/spinlock.h:353
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
In kernel/bpf/local_storage.c (ffffffff81303c3c)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_link
  - kernel/bpf/local_storage.c:cgroup_storage_map_free
  - kernel/bpf/local_storage.c:cgroup_storage_get_next_key
  - kernel/bpf/local_storage.c:cgroup_storage_lookup
```
```
In kernel/bpf/btf.c (ffffffff8130a229)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_alloc_id
  - kernel/bpf/btf.c:bpf_find_btf_id
  - kernel/bpf/btf.c:bpf_find_btf_id
```
```
In kernel/bpf/reuseport_array.c (ffffffff8132bc27)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem
  - kernel/bpf/reuseport_array.c:reuseport_array_delete_elem
```
```
In kernel/watch_queue.c (ffffffff81358208)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_clear
  - kernel/watch_queue.c:watch_queue_clear
  - kernel/watch_queue.c:remove_watch_from_object
  - kernel/watch_queue.c:add_watch_to_object
```
```
In mm/page-writeback.c (ffffffff8136a3ad)
Location: include/linux/spinlock.h:353
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
In mm/backing-dev.c (ffffffff81397942)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:bdi_register_va
  - mm/backing-dev.c:bdi_get_by_id
```
```
In security/selinux/netif.c (ffffffff816804a5)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_netdev_notifier_handler
  - security/selinux/netif.c:sel_netif_flush
  - security/selinux/netif.c:sel_netif_sid_slow
```
```
In security/selinux/netnode.c (ffffffff81680c75)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_flush
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (ffffffff81681065)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_flush
  - security/selinux/netport.c:sel_netport_sid
```
```
In block/blk-cgroup.c (ffffffff8176366e)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - block/blk-cgroup.c:__blkcg_punt_bio_submit
  - block/blk-cgroup.c:blkg_async_bio_workfn
```
```
In drivers/connector/cn_queue.c (ffffffff81adcc25)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_free_dev
  - drivers/connector/cn_queue.c:cn_queue_del_callback
  - drivers/connector/cn_queue.c:cn_queue_add_callback
```
```
In drivers/connector/connector.c (ffffffff81adcdaf)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_proc_show
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/net/tun.c (ffffffff81beca72)
Location: include/linux/spinlock.h:353
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
In drivers/net/ppp/ppp_generic.c (ffffffff81bfc757)
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
  - drivers/net/ppp/ppp_generic.c:ppp_poll
  - drivers/net/ppp/ppp_generic.c:ppp_read
```
```
In drivers/net/xen-netfront.c (ffffffff81c079cf)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:xennet_open
```
```
In net/core/sock.c (ffffffff81d9d00b)
Location: include/linux/spinlock.h:353
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
In net/core/request_sock.c (ffffffff81da1195)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/core/datagram.c (ffffffff81db044a)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/core/datagram.c:skb_kill_datagram
```
```
In net/core/gen_stats.c (ffffffff81db2534)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/core/gen_stats.c:gnet_stats_start_copy_compat
```
```
In net/core/gen_estimator.c (ffffffff81db2c71)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/net_namespace.c (ffffffff81db4dec)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/dev.c (ffffffff81dc800f)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/core/dev.c:netif_set_real_num_tx_queues
```
```
In net/core/neighbour.c (ffffffff81ddb9c1)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/core/sock_reuseport.c (ffffffff81e042b5)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_detach_prog
  - net/core/sock_reuseport.c:reuseport_attach_prog
  - net/core/sock_reuseport.c:reuseport_stop_listen_sock
  - net/core/sock_reuseport.c:reuseport_detach_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_alloc
  - net/core/sock_reuseport.c:reuseport_update_incoming_cpu
```
```
In net/core/page_pool.c (ffffffff81e0f0f9)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_defragged_page
```
```
In net/core/devlink.c (ffffffff81e3e0be)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_port_type_set
  - net/core/devlink.c:devlink_nl_port_fill
```
```
In net/core/skmsg.c (ffffffff81e48029)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_verdict_apply
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
In net/core/sock_map.c (ffffffff81e4b5db)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_unref
```
```
In net/sched/sch_generic.c (ffffffff81e52db9)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_reset_queue
  - net/sched/sch_generic.c:dev_reset_queue
  - net/sched/sch_generic.c:dev_graft_qdisc
```
```
In net/sched/sch_mq.c (ffffffff81e534a2)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump
```
```
In net/sched/sch_api.c (ffffffff81e5718c)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/sched/sch_api.c:qdisc_class_hash_grow
```
```
In net/sched/cls_api.c (ffffffff81e60993)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_setup_action
```
```
In net/sched/act_api.c (ffffffff81e61ffd)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_offload_del_ex
  - net/sched/act_api.c:tcf_action_update_hw_stats
  - net/sched/act_api.c:tcf_action_offload_add_ex
```
```
In net/ipv4/route.c (ffffffff81e92761)
Location: include/linux/spinlock.h:353
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
In net/ipv4/inetpeer.c (ffffffff81e94ba5)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/inet_hashtables.c (ffffffff81ea52ed)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_bhash2_update_saddr
  - net/ipv4/inet_hashtables.c:inet_unhash
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ea8481)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ecf3ce)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:established_get_first
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ed76a7)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_flush_all
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/raw.c (ffffffff81edc8c2)
Location: include/linux/spinlock.h:353
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81edf3bd)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_lib_unhash
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/af_inet.c (ffffffff81ef2d9f)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_register_protosw
```
```
In net/ipv4/igmp.c (ffffffff81ef8882)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
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
  - net/ipv4/igmp.c:igmpv3_send_cr
  - net/ipv4/igmp.c:igmpv3_send_cr
```
```
In net/ipv4/fib_semantics.c (ffffffff81f02ef1)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_info_hash_move
  - net/ipv4/fib_semantics.c:fib_release_info
```
```
In net/ipv4/inet_fragment.c (ffffffff81f0a17a)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frags_free_cb
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81f18a82)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
```
In net/ipv4/ipmr.c (ffffffff81f214aa)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
```
```
In net/ipv4/ipmr_base.c (ffffffff81f23e35)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_table_dump
  - net/ipv4/ipmr_base.c:mr_mfc_seq_next
  - net/ipv4/ipmr_base.c:mr_mfc_seq_next
```
```
In net/ipv4/tcp_bpf.c (ffffffff81f268f5)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_update_proto
```
```
In net/ipv4/udp_bpf.c (ffffffff81f284da)
Location: include/linux/spinlock.h:353
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81f297b0)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_check
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_invalidate
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f33da4)
Location: include/linux/spinlock.h:353
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
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff81f3afde)
Location: include/linux/spinlock.h:353
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
In net/xfrm/xfrm_input.c (ffffffff81f417a7)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue_net
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
  - net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo
  - net/xfrm/xfrm_input.c:xfrm_input_register_afinfo
```
```
In net/xfrm/xfrm_output.c (ffffffff81f44519)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/unix/unix_bpf.c (ffffffff81f5173f)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/unix/unix_bpf.c:unix_stream_bpf_update_proto
  - net/unix/unix_bpf.c:unix_dgram_bpf_update_proto
```
```
In net/ipv6/af_inet6.c (ffffffff81f52107)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_register_protosw
```
```
In net/ipv6/addrconf.c (ffffffff81f5f820)
Location: include/linux/spinlock.h:353
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
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/route.c (ffffffff81f795c8)
Location: include/linux/spinlock.h:353
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
In net/ipv6/ip6_fib.c (ffffffff81f7b4a6)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:__fib6_clean_all
  - net/ipv6/ip6_fib.c:fib6_update_sernum_stub
  - net/ipv6/ip6_fib.c:fib6_tables_dump
```
```
In net/ipv6/raw.c (ffffffff81f8c842)
Location: include/linux/spinlock.h:353
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff81f9818e)
Location: include/linux/spinlock.h:353
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
In net/ipv6/ip6_flowlabel.c (ffffffff81fa4e1e)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
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
In net/ipv6/ip6mr.c (ffffffff81faf212)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
```
```
In net/ipv6/calipso.c (ffffffff81fb6d47)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_cache_add
  - net/ipv6/calipso.c:calipso_cache_check
  - net/ipv6/calipso.c:calipso_cache_invalidate
```
```
In net/packet/af_packet.c (ffffffff81fc777b)
Location: include/linux/spinlock.h:353
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
In net/dcb/dcbnl.c (ffffffff81fdcb66)
Location: include/linux/spinlock.h:353
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
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
```
```
In net/switchdev/switchdev.c (ffffffff81fe2f16)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_deferred_enqueue
  - net/switchdev/switchdev.c:switchdev_deferred_process
```
```
In net/xdp/xsk.c (ffffffff81fee7bf)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xsk.c:xsk_generic_rcv
```
```
In net/xdp/xskmap.c (ffffffff81ff1085)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/xdp/xskmap.c:xsk_map_try_sock_delete
  - net/xdp/xskmap.c:xsk_map_delete_elem
  - net/xdp/xskmap.c:xsk_map_update_elem
  - net/xdp/xskmap.c:xsk_map_update_elem
  - net/xdp/xskmap.c:xsk_map_sock_delete
```
```
In net/mptcp/protocol.c (ffffffff81ffc10b)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_finish_join
  - net/mptcp/protocol.c:mptcp_subflow_process_delegated
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:mptcp_destroy_common
  - net/mptcp/protocol.c:__mptcp_retrans
  - net/mptcp/protocol.c:__mptcp_retransmit_pending_data
  - net/mptcp/protocol.c:__mptcp_move_skbs
  - net/mptcp/protocol.c:__mptcp_move_skbs
  - net/mptcp/protocol.c:mptcp_data_ready
```
```
In net/mptcp/subflow.c (ffffffff820006b5)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_queue_clean
  - net/mptcp/subflow.c:subflow_state_change
  - net/mptcp/subflow.c:__mptcp_subflow_connect
  - net/mptcp/subflow.c:subflow_data_ready
  - net/mptcp/subflow.c:mptcp_set_connected
```
```
In net/mptcp/options.c (ffffffff82002ba1)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_incoming_options
  - net/mptcp/options.c:ack_update_msk
```
```
In net/mptcp/token.c (ffffffff820041c5)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_destroy
  - net/mptcp/token.c:mptcp_token_destroy_request
  - net/mptcp/token.c:mptcp_token_accept
  - net/mptcp/token.c:mptcp_token_new_connect
  - net/mptcp/token.c:mptcp_token_new_request
```
```
In net/mptcp/pm.c (ffffffff82005a55)
Location: include/linux/spinlock.h:353
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
In net/mptcp/pm_netlink.c (ffffffff82009ede)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_flags
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_flags
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_limits
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_dump_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_addr
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_flush_addrs
  - net/mptcp/pm_netlink.c:mptcp_pm_remove_addrs_and_subflows
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr
  - net/mptcp/pm_netlink.c:mptcp_nl_remove_id_zero_address
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_add_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_append_new_local_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_work
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_rm_addr_or_subflow
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_addr_send_ack
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_free_anno_list
  - net/mptcp/pm_netlink.c:mptcp_pm_del_add_timer
  - net/mptcp/pm_netlink.c:mptcp_pm_add_timer
  - net/mptcp/pm_netlink.c:mptcp_pm_sport_in_anno_list
```
```
In net/mptcp/pm_userspace.c (ffffffff8200e352)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_announce
  - net/mptcp/pm_userspace.c:mptcp_userspace_pm_get_flags_and_ifindex_by_id
  - net/mptcp/pm_userspace.c:mptcp_userspace_pm_append_new_local_addr
  - net/mptcp/pm_userspace.c:mptcp_free_local_addr_list
```
```
In net/mptcp/fastopen.c (ffffffff8200f045)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/mptcp/fastopen.c:mptcp_fastopen_gen_msk_ackseq
  - net/mptcp/fastopen.c:mptcp_fastopen_subflow_synack_set_params
```
```
In net/mptcp/syncookies.c (ffffffff8200f3d3)
Location: include/linux/spinlock.h:353
Inline: True
Inline callers:
  - net/mptcp/syncookies.c:mptcp_token_join_cookie_init_state
  - net/mptcp/syncookies.c:subflow_init_req_cookie_join_save
```
```
In lib/xarray.c (ffffffff82049a3d)
Location: include/linux/spinlock.h:353
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
In kernel/cgroup/cgroup.c (ffffffff836d5781)
Location: include/linux/spinlock.h:354
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
In kernel/bpf/core.c (ffffffff812e8fd5)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_ksym_del
  - kernel/bpf/core.c:bpf_ksym_add
```
```
In kernel/bpf/syscall.c (ffffffff812f4f88)
Location: include/linux/spinlock.h:354
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
In kernel/bpf/local_storage.c (ffffffff813325cc)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_link
  - kernel/bpf/local_storage.c:cgroup_storage_map_free
  - kernel/bpf/local_storage.c:cgroup_storage_get_next_key
  - kernel/bpf/local_storage.c:cgroup_storage_lookup
```
```
In kernel/bpf/btf.c (ffffffff81339739)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_alloc_id
  - kernel/bpf/btf.c:bpf_find_btf_id
  - kernel/bpf/btf.c:bpf_find_btf_id
```
```
In kernel/bpf/reuseport_array.c (ffffffff8135bd97)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem
  - kernel/bpf/reuseport_array.c:reuseport_array_delete_elem
```
```
In kernel/watch_queue.c (ffffffff81389a82)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_clear
  - kernel/watch_queue.c:watch_queue_clear
  - kernel/watch_queue.c:remove_watch_from_object
  - kernel/watch_queue.c:add_watch_to_object
```
```
In mm/page-writeback.c (ffffffff8139c53d)
Location: include/linux/spinlock.h:354
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
In mm/backing-dev.c (ffffffff813ca8d2)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:bdi_register_va
  - mm/backing-dev.c:bdi_get_by_id
```
```
In security/selinux/netif.c (ffffffff816b8585)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_netdev_notifier_handler
  - security/selinux/netif.c:sel_netif_flush
  - security/selinux/netif.c:sel_netif_sid_slow
```
```
In security/selinux/netnode.c (ffffffff816b8d25)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_flush
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (ffffffff816b9115)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_flush
  - security/selinux/netport.c:sel_netport_sid
```
```
In drivers/connector/cn_queue.c (ffffffff81b2ae95)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_free_dev
  - drivers/connector/cn_queue.c:cn_queue_del_callback
  - drivers/connector/cn_queue.c:cn_queue_add_callback
```
```
In drivers/connector/connector.c (ffffffff81b2b01f)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_proc_show
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/net/tun.c (ffffffff81c44f72)
Location: include/linux/spinlock.h:354
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
In drivers/net/virtio_net.c (ffffffff81c5447a)
Location: include/linux/spinlock.h:354
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
In drivers/net/ppp/ppp_generic.c (ffffffff81c61dd7)
Location: include/linux/spinlock.h:354
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
  - drivers/net/ppp/ppp_generic.c:ppp_poll
  - drivers/net/ppp/ppp_generic.c:ppp_read
```
```
In drivers/net/xen-netfront.c (ffffffff81c6d0ef)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:xennet_open
```
```
In net/core/sock.c (ffffffff81e0b85b)
Location: include/linux/spinlock.h:354
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
In net/core/request_sock.c (ffffffff81e0fa65)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/core/skbuff.c (ffffffff81e1f29e)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_attempt_defer_free
```
```
In net/core/datagram.c (ffffffff81e208fa)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - net/core/datagram.c:skb_kill_datagram
```
```
In net/core/gen_stats.c (ffffffff81e22b04)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - net/core/gen_stats.c:gnet_stats_start_copy_compat
```
```
In net/core/gen_estimator.c (ffffffff81e23241)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/net_namespace.c (ffffffff81e253bc)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/dev.c (ffffffff81e36e10)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - net/core/dev.c:netif_set_real_num_tx_queues
```
```
In net/core/neighbour.c (ffffffff81e4c728)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/core/sock_reuseport.c (ffffffff81e76b05)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_detach_prog
  - net/core/sock_reuseport.c:reuseport_attach_prog
  - net/core/sock_reuseport.c:reuseport_stop_listen_sock
  - net/core/sock_reuseport.c:reuseport_detach_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_alloc
  - net/core/sock_reuseport.c:reuseport_update_incoming_cpu
```
```
In net/core/page_pool.c (ffffffff81e828b9)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_defragged_page
```
```
In net/core/skmsg.c (ffffffff81ea314f)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_verdict_apply
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
In net/core/sock_map.c (ffffffff81ea6cfb)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_unref
```
```
In net/sched/sch_generic.c (ffffffff81eae645)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_reset_queue
  - net/sched/sch_generic.c:dev_reset_queue
  - net/sched/sch_generic.c:dev_graft_qdisc
```
```
In net/sched/sch_mq.c (ffffffff81eaed1f)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump
```
```
In net/sched/sch_api.c (ffffffff81eb188c)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/sched/sch_api.c:qdisc_class_hash_grow
```
```
In net/sched/cls_api.c (ffffffff81ebc8e8)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_setup_action
```
```
In net/sched/act_api.c (ffffffff81ebcbdd)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - net/sched/act_api.c:offload_action_init
```
```
In net/ipv4/route.c (ffffffff81ef0eff)
Location: include/linux/spinlock.h:354
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
In net/ipv4/inetpeer.c (ffffffff81ef3375)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/inet_hashtables.c (ffffffff81f03a7c)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_bhash2_update_saddr
  - net/ipv4/inet_hashtables.c:inet_unhash
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81f06d01)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f2e08e)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:established_get_first
```
```
In net/ipv4/tcp_metrics.c (ffffffff81f36a8d)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_flush_all
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/raw.c (ffffffff81f3b46a)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_ioctl
```
```
In net/ipv4/udp.c (ffffffff81f402c8)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - net/ipv4/udp.c:bpf_iter_udp_batch
  - net/ipv4/udp.c:udp_get_first
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_lib_unhash
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/af_inet.c (ffffffff81f5284f)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_register_protosw
```
```
In net/ipv4/igmp.c (ffffffff81f582f2)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
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
  - net/ipv4/igmp.c:igmpv3_send_cr
  - net/ipv4/igmp.c:igmpv3_send_cr
```
```
In net/ipv4/fib_semantics.c (ffffffff81f628e8)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_info_hash_move
  - net/ipv4/fib_semantics.c:fib_release_info
```
```
In net/ipv4/inet_fragment.c (ffffffff81f69caa)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frags_free_cb
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81f786e2)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
```
In net/ipv4/ipmr.c (ffffffff81f806f4)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
```
```
In net/ipv4/ipmr_base.c (ffffffff81f839c5)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_table_dump
  - net/ipv4/ipmr_base.c:mr_mfc_seq_next
  - net/ipv4/ipmr_base.c:mr_mfc_seq_next
```
```
In net/ipv4/tcp_bpf.c (ffffffff81f865c0)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_update_proto
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
```
```
In net/ipv4/udp_bpf.c (ffffffff81f8803f)
Location: include/linux/spinlock.h:354
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81f89350)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_check
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_invalidate
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f93164)
Location: include/linux/spinlock.h:354
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
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff81f9a9fe)
Location: include/linux/spinlock.h:354
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
In net/xfrm/xfrm_input.c (ffffffff81fa1047)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue_net
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
  - net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo
  - net/xfrm/xfrm_input.c:xfrm_input_register_afinfo
```
```
In net/xfrm/xfrm_output.c (ffffffff81fa3cff)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/unix/unix_bpf.c (ffffffff81fb10bf)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - net/unix/unix_bpf.c:unix_stream_bpf_update_proto
  - net/unix/unix_bpf.c:unix_dgram_bpf_update_proto
```
```
In net/ipv6/af_inet6.c (ffffffff81fb1b17)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_register_protosw
```
```
In net/ipv6/addrconf.c (ffffffff81fbf550)
Location: include/linux/spinlock.h:354
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
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff81fd97d8)
Location: include/linux/spinlock.h:354
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
In net/ipv6/ip6_fib.c (ffffffff81fdb7b5)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:__fib6_clean_all
  - net/ipv6/ip6_fib.c:fib6_update_sernum_stub
  - net/ipv6/ip6_fib.c:fib6_tables_dump
```
```
In net/ipv6/raw.c (ffffffff81fecd5a)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_ioctl
```
```
In net/ipv6/mcast.c (ffffffff81ff8b7e)
Location: include/linux/spinlock.h:354
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
In net/ipv6/ip6_flowlabel.c (ffffffff820056de)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
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
In net/ipv6/ip6mr.c (ffffffff8200ef93)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
```
```
In net/ipv6/calipso.c (ffffffff82017447)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_cache_add
  - net/ipv6/calipso.c:calipso_cache_check
  - net/ipv6/calipso.c:calipso_cache_invalidate
```
```
In net/packet/af_packet.c (ffffffff82028721)
Location: include/linux/spinlock.h:354
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
In net/devlink/leftover.c (ffffffff8203dc9a)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - net/devlink/leftover.c:__devlink_port_type_set
  - net/devlink/leftover.c:devlink_nl_port_fill
```
```
In net/dcb/dcbnl.c (ffffffff820589f6)
Location: include/linux/spinlock.h:354
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
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
```
```
In net/switchdev/switchdev.c (ffffffff8205f236)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_deferred_enqueue
  - net/switchdev/switchdev.c:switchdev_deferred_process
```
```
In net/xdp/xsk.c (ffffffff8206a8cf)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xsk.c:xsk_generic_rcv
```
```
In net/xdp/xskmap.c (ffffffff8206d2b5)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - net/xdp/xskmap.c:xsk_map_try_sock_delete
  - net/xdp/xskmap.c:xsk_map_delete_elem
  - net/xdp/xskmap.c:xsk_map_update_elem
  - net/xdp/xskmap.c:xsk_map_update_elem
  - net/xdp/xskmap.c:xsk_map_sock_delete
```
```
In net/mptcp/protocol.c (ffffffff820784ec)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_finish_join
  - net/mptcp/protocol.c:mptcp_subflow_process_delegated
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:mptcp_destroy_common
  - net/mptcp/protocol.c:__mptcp_retrans
  - net/mptcp/protocol.c:__mptcp_retransmit_pending_data
  - net/mptcp/protocol.c:__mptcp_move_skbs
  - net/mptcp/protocol.c:__mptcp_move_skbs
  - net/mptcp/protocol.c:mptcp_data_ready
```
```
In net/mptcp/subflow.c (ffffffff8207c8a5)
Location: include/linux/spinlock.h:354
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
In net/mptcp/options.c (ffffffff8207ed7b)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_incoming_options
  - net/mptcp/options.c:ack_update_msk
```
```
In net/mptcp/token.c (ffffffff820803bd)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_destroy
  - net/mptcp/token.c:mptcp_token_destroy_request
  - net/mptcp/token.c:mptcp_token_accept
  - net/mptcp/token.c:mptcp_token_new_connect
  - net/mptcp/token.c:mptcp_token_new_request
```
```
In net/mptcp/pm.c (ffffffff82081c45)
Location: include/linux/spinlock.h:354
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
In net/mptcp/pm_netlink.c (ffffffff82086c08)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_set_flags
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_set_flags
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_limits
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_dump_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_addr
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_flush_addrs
  - net/mptcp/pm_netlink.c:mptcp_pm_remove_addrs_and_subflows
  - net/mptcp/pm_netlink.c:mptcp_pm_remove_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr
  - net/mptcp/pm_netlink.c:mptcp_nl_remove_id_zero_address
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_add_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_append_new_local_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_work
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_rm_addr_or_subflow
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_addr_send_ack
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_free_anno_list
  - net/mptcp/pm_netlink.c:mptcp_pm_del_add_timer
  - net/mptcp/pm_netlink.c:mptcp_pm_add_timer
  - net/mptcp/pm_netlink.c:mptcp_pm_sport_in_anno_list
```
```
In net/mptcp/sockopt.c (ffffffff820887d4)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:mptcp_diag_fill_info
```
```
In net/mptcp/pm_userspace.c (ffffffff8208b891)
Location: include/linux/spinlock.h:354
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
In net/mptcp/fastopen.c (ffffffff8208bc35)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - net/mptcp/fastopen.c:mptcp_fastopen_gen_msk_ackseq
  - net/mptcp/fastopen.c:mptcp_fastopen_subflow_synack_set_params
```
```
In net/mptcp/syncookies.c (ffffffff8208bfc3)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - net/mptcp/syncookies.c:mptcp_token_join_cookie_init_state
  - net/mptcp/syncookies.c:subflow_init_req_cookie_join_save
```
```
In lib/xarray.c (ffffffff820c84ad)
Location: include/linux/spinlock.h:354
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
In kernel/cgroup/cgroup.c (ffffffff83907af1)
Location: include/linux/spinlock.h:354
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
In kernel/bpf/core.c (ffffffff81307345)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_ksym_del
  - kernel/bpf/core.c:bpf_ksym_add
```
```
In kernel/bpf/syscall.c (ffffffff81313e0d)
Location: include/linux/spinlock.h:354
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
In kernel/bpf/local_storage.c (ffffffff81356b9c)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_link
  - kernel/bpf/local_storage.c:cgroup_storage_map_free
  - kernel/bpf/local_storage.c:cgroup_storage_get_next_key
  - kernel/bpf/local_storage.c:cgroup_storage_lookup
```
```
In kernel/bpf/btf.c (ffffffff8135f869)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_alloc_id
  - kernel/bpf/btf.c:bpf_find_btf_id
  - kernel/bpf/btf.c:bpf_find_btf_id
```
```
In kernel/bpf/reuseport_array.c (ffffffff81384a27)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem
  - kernel/bpf/reuseport_array.c:reuseport_array_delete_elem
```
```
In kernel/watch_queue.c (ffffffff813b34d2)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_clear
  - kernel/watch_queue.c:watch_queue_clear
  - kernel/watch_queue.c:remove_watch_from_object
  - kernel/watch_queue.c:add_watch_to_object
```
```
In mm/page-writeback.c (ffffffff813c621d)
Location: include/linux/spinlock.h:354
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
In mm/backing-dev.c (ffffffff813f5342)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:bdi_register_va
  - mm/backing-dev.c:bdi_get_by_id
```
```
In security/selinux/netif.c (ffffffff816f4fb5)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_netdev_notifier_handler
  - security/selinux/netif.c:sel_netif_flush
  - security/selinux/netif.c:sel_netif_sid_slow
```
```
In security/selinux/netnode.c (ffffffff816f57a5)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_flush
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (ffffffff816f5bc5)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_flush
  - security/selinux/netport.c:sel_netport_sid
```
```
In drivers/connector/cn_queue.c (ffffffff81b82175)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_free_dev
  - drivers/connector/cn_queue.c:cn_queue_del_callback
  - drivers/connector/cn_queue.c:cn_queue_add_callback
```
```
In drivers/connector/connector.c (ffffffff81b822ff)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_proc_show
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/net/tun.c (ffffffff81cfaad2)
Location: include/linux/spinlock.h:354
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
In drivers/net/virtio_net.c (ffffffff81d0ab98)
Location: include/linux/spinlock.h:354
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
In drivers/net/ppp/ppp_generic.c (ffffffff81d187d7)
Location: include/linux/spinlock.h:354
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
  - drivers/net/ppp/ppp_generic.c:ppp_poll
  - drivers/net/ppp/ppp_generic.c:ppp_read
```
```
In drivers/net/xen-netfront.c (ffffffff81d21a2c)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/net/xen-netfront.c:xennet_open
```
```
In net/core/sock.c (ffffffff81ec824b)
Location: include/linux/spinlock.h:354
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
In net/core/request_sock.c (ffffffff81ecc515)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/core/skbuff.c (ffffffff81edc8fe)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_attempt_defer_free
```
```
In net/core/datagram.c (ffffffff81ede7ca)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - net/core/datagram.c:skb_kill_datagram
```
```
In net/core/gen_stats.c (ffffffff81ee0a44)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - net/core/gen_stats.c:gnet_stats_start_copy_compat
```
```
In net/core/gen_estimator.c (ffffffff81ee11af)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/net_namespace.c (ffffffff81ee331c)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/dev.c (ffffffff81ef4e4e)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - net/core/dev.c:netif_set_real_num_tx_queues
```
```
In net/core/neighbour.c (ffffffff81f0b43c)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/core/sock_reuseport.c (ffffffff81f36ac5)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_detach_prog
  - net/core/sock_reuseport.c:reuseport_attach_prog
  - net/core/sock_reuseport.c:reuseport_stop_listen_sock
  - net/core/sock_reuseport.c:reuseport_detach_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_alloc
  - net/core/sock_reuseport.c:reuseport_update_incoming_cpu
```
```
In net/core/page_pool.c (ffffffff81f44ade)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_put_page_bulk
  - net/core/page_pool.c:page_pool_put_unrefed_page
```
```
In net/core/skmsg.c (ffffffff81f6546f)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_verdict_apply
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
In net/core/sock_map.c (ffffffff81f68668)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_remove_links
  - net/core/sock_map.c:sock_map_remove_links
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_delete_elem
  - net/core/sock_map.c:sock_map_unref
```
```
In net/sched/sch_generic.c (ffffffff81f710c0)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_reset_queue
  - net/sched/sch_generic.c:dev_reset_queue
  - net/sched/sch_generic.c:dev_graft_qdisc
```
```
In net/sched/sch_mq.c (ffffffff81f717bc)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump
```
```
In net/sched/sch_api.c (ffffffff81f7433c)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_grow
  - net/sched/sch_api.c:qdisc_class_hash_grow
```
```
In net/sched/cls_api.c (ffffffff81f7fae8)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_setup_action
```
```
In net/sched/act_api.c (ffffffff81f7fddd)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - net/sched/act_api.c:offload_action_init
```
```
In net/ipv4/route.c (ffffffff81fb5052)
Location: include/linux/spinlock.h:354
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
In net/ipv4/inetpeer.c (ffffffff81fb7305)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/inet_hashtables.c (ffffffff81fc7d2c)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_bhash2_update_saddr
  - net/ipv4/inet_hashtables.c:inet_unhash
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81fcb021)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff2c49)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:established_get_first
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ffcbad)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_flush_all
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
  - net/ipv4/tcp_metrics.c:tcpm_new
```
```
In net/ipv4/raw.c (ffffffff8200158a)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_ioctl
```
```
In net/ipv4/udp.c (ffffffff82005c45)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - net/ipv4/udp.c:bpf_iter_udp_batch
  - net/ipv4/udp.c:udp_get_first
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_lib_unhash
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/af_inet.c (ffffffff82018b2f)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_register_protosw
```
```
In net/ipv4/igmp.c (ffffffff8201e7b5)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
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
  - net/ipv4/igmp.c:igmpv3_send_cr
  - net/ipv4/igmp.c:igmpv3_send_cr
```
```
In net/ipv4/fib_semantics.c (ffffffff82028eb8)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_info_hash_move
  - net/ipv4/fib_semantics.c:fib_release_info
```
```
In net/ipv4/inet_fragment.c (ffffffff8203032a)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frags_free_cb
```
```
In net/ipv4/ipmr.c (ffffffff82046d74)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
```
```
In net/ipv4/ipmr_base.c (ffffffff8204a075)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_table_dump
  - net/ipv4/ipmr_base.c:mr_mfc_seq_next
  - net/ipv4/ipmr_base.c:mr_mfc_seq_next
```
```
In net/ipv4/tcp_bpf.c (ffffffff8204dbc5)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_update_proto
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
```
```
In net/ipv4/udp_bpf.c (ffffffff8204f75f)
Location: include/linux/spinlock.h:354
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (ffffffff82050aaf)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_check
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_invalidate
```
```
In net/xfrm/xfrm_policy.c (ffffffff82060b74)
Location: include/linux/spinlock.h:354
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
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff82067d5e)
Location: include/linux/spinlock.h:354
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
In net/xfrm/xfrm_input.c (ffffffff8206e367)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue_net
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
  - net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo
  - net/xfrm/xfrm_input.c:xfrm_input_register_afinfo
```
```
In net/xfrm/xfrm_output.c (ffffffff8207102c)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/unix/unix_bpf.c (ffffffff8207e7b3)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - net/unix/unix_bpf.c:unix_stream_bpf_update_proto
  - net/unix/unix_bpf.c:unix_dgram_bpf_update_proto
```
```
In net/ipv6/af_inet6.c (ffffffff8207f237)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_register_protosw
```
```
In net/ipv6/addrconf.c (ffffffff8208c9f0)
Location: include/linux/spinlock.h:354
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
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff820a7161)
Location: include/linux/spinlock.h:354
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
In net/ipv6/ip6_fib.c (ffffffff820a92e5)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:__fib6_clean_all
  - net/ipv6/ip6_fib.c:fib6_update_sernum_stub
  - net/ipv6/ip6_fib.c:fib6_tables_dump
```
```
In net/ipv6/raw.c (ffffffff820ba95a)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_ioctl
```
```
In net/ipv6/mcast.c (ffffffff820c67ee)
Location: include/linux/spinlock.h:354
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
In net/ipv6/ip6_flowlabel.c (ffffffff820d44ee)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
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
In net/ipv6/ip6mr.c (ffffffff820ddf23)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
```
```
In net/ipv6/calipso.c (ffffffff820e6416)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_cache_add
  - net/ipv6/calipso.c:calipso_cache_check
  - net/ipv6/calipso.c:calipso_cache_invalidate
```
```
In net/packet/af_packet.c (ffffffff820f8153)
Location: include/linux/spinlock.h:354
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
In net/devlink/port.c (ffffffff8210751c)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - net/devlink/port.c:__devlink_port_type_set
  - net/devlink/port.c:devlink_nl_port_fill
```
```
In net/dcb/dcbnl.c (ffffffff8212b546)
Location: include/linux/spinlock.h:354
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
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
```
```
In net/switchdev/switchdev.c (ffffffff82131936)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_port_obj_act_is_deferred
  - net/switchdev/switchdev.c:switchdev_deferred_enqueue
  - net/switchdev/switchdev.c:switchdev_deferred_process
```
```
In net/xdp/xsk.c (ffffffff8213e500)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xsk.c:xsk_generic_rcv
```
```
In net/xdp/xskmap.c (ffffffff82141155)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - net/xdp/xskmap.c:xsk_map_try_sock_delete
  - net/xdp/xskmap.c:xsk_map_delete_elem
  - net/xdp/xskmap.c:xsk_map_update_elem
  - net/xdp/xskmap.c:xsk_map_update_elem
  - net/xdp/xskmap.c:xsk_map_sock_delete
```
```
In net/mptcp/protocol.c (ffffffff8214d780)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_finish_join
  - net/mptcp/protocol.c:mptcp_subflow_process_delegated
  - net/mptcp/protocol.c:mptcp_subflow_process_delegated
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:mptcp_destroy_common
  - net/mptcp/protocol.c:__mptcp_retrans
  - net/mptcp/protocol.c:__mptcp_retrans
  - net/mptcp/protocol.c:__mptcp_retransmit_pending_data
  - net/mptcp/protocol.c:__mptcp_move_skbs
  - net/mptcp/protocol.c:__mptcp_move_skbs
  - net/mptcp/protocol.c:mptcp_data_ready
```
```
In net/mptcp/subflow.c (ffffffff82151da5)
Location: include/linux/spinlock.h:354
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
In net/mptcp/options.c (ffffffff8215426b)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_incoming_options
  - net/mptcp/options.c:ack_update_msk
  - net/mptcp/options.c:check_fully_established
```
```
In net/mptcp/token.c (ffffffff821558ad)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_destroy
  - net/mptcp/token.c:mptcp_token_destroy_request
  - net/mptcp/token.c:mptcp_token_accept
  - net/mptcp/token.c:mptcp_token_new_connect
  - net/mptcp/token.c:mptcp_token_new_request
```
```
In net/mptcp/pm.c (ffffffff82157235)
Location: include/linux/spinlock.h:354
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
In net/mptcp/pm_netlink.c (ffffffff8215c3b8)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_set_flags
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_set_flags
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_set_limits_doit
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_get_addr_dumpit
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_get_addr_doit
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_flush_addrs_doit
  - net/mptcp/pm_netlink.c:mptcp_pm_remove_addrs_and_subflows
  - net/mptcp/pm_netlink.c:mptcp_pm_remove_addrs
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_del_addr_doit
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_del_addr_doit
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_del_addr_doit
  - net/mptcp/pm_netlink.c:mptcp_nl_remove_id_zero_address
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_doit
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_append_new_local_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_work
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_rm_addr_or_subflow
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_addr_send_ack
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_free_anno_list
  - net/mptcp/pm_netlink.c:mptcp_pm_del_add_timer
  - net/mptcp/pm_netlink.c:mptcp_pm_add_timer
  - net/mptcp/pm_netlink.c:mptcp_pm_sport_in_anno_list
```
```
In net/mptcp/sockopt.c (ffffffff8215e3d2)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:mptcp_diag_fill_info
```
```
In net/mptcp/pm_userspace.c (ffffffff82161692)
Location: include/linux/spinlock.h:354
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
In net/mptcp/fastopen.c (ffffffff82161973)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - net/mptcp/fastopen.c:mptcp_fastopen_subflow_synack_set_params
```
```
In net/mptcp/syncookies.c (ffffffff82162483)
Location: include/linux/spinlock.h:354
Inline: True
Inline callers:
  - net/mptcp/syncookies.c:mptcp_token_join_cookie_init_state
  - net/mptcp/syncookies.c:subflow_init_req_cookie_join_save
```
```
In lib/xarray.c (ffffffff821a2e2d)
Location: include/linux/spinlock.h:354
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
In kernel/cgroup/cgroup.c (ffff8000101d0d78)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_idr_remove
  - kernel/cgroup/cgroup.c:cgroup_idr_replace
```
```
In kernel/bpf/core.c (ffff80001025e1cc)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
```
```
In kernel/bpf/syscall.c (ffff8000102654fc)
Location: include/linux/spinlock.h:341
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
In kernel/bpf/local_storage.c (ffff80001027f510)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_unlink
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_link
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_release
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_assign
  - kernel/bpf/local_storage.c:cgroup_storage_get_next_key
  - kernel/bpf/local_storage.c:cgroup_storage_lookup
```
```
In kernel/bpf/btf.c (ffff800010285618)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
```
```
In kernel/bpf/xskmap.c (ffff800010289618)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - kernel/bpf/xskmap.c:xsk_map_try_sock_delete
  - kernel/bpf/xskmap.c:xsk_map_delete_elem
  - kernel/bpf/xskmap.c:xsk_map_update_elem
  - kernel/bpf/xskmap.c:xsk_map_update_elem
  - kernel/bpf/xskmap.c:xsk_map_sock_delete
```
```
In kernel/bpf/reuseport_array.c (ffff800010290808)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem
  - kernel/bpf/reuseport_array.c:reuseport_array_delete_elem
```
```
In mm/page-writeback.c (ffff8000102ba700)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - mm/page-writeback.c:bdi_set_max_ratio
  - mm/page-writeback.c:bdi_set_min_ratio
```
```
In mm/backing-dev.c (ffff8000102debf4)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:bdi_register_va
  - mm/backing-dev.c:bdi_get_by_id
  - mm/backing-dev.c:wb_wakeup_delayed
```
```
In fs/fs-writeback.c (ffff8000103cb148)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_queue_work
  - fs/fs-writeback.c:wb_wakeup
```
```
In security/selinux/netif.c (ffff800010557e3c)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_netdev_notifier_handler
  - security/selinux/netif.c:sel_netif_flush
  - security/selinux/netif.c:sel_netif_sid
```
```
In security/selinux/netnode.c (ffff8000105586a8)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_flush
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (ffff800010558ab8)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_flush
  - security/selinux/netport.c:sel_netport_sid
```
```
In block/genhd.c (ffff8000105fa3c4)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - block/genhd.c:get_gendisk
```
```
In block/blk-cgroup.c (ffff80001060e700)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - block/blk-cgroup.c:__blkcg_punt_bio_submit
  - block/blk-cgroup.c:blkg_async_bio_workfn
```
```
In drivers/dma/dmaengine.c (ffff8000107fcfb0)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_run_dependencies
```
```
In drivers/dma/mv_xor.c (ffff800010806cc0)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - drivers/dma/mv_xor.c:mv_xor_status
  - drivers/dma/mv_xor.c:mv_xor_free_chan_resources
  - drivers/dma/mv_xor.c:mv_xor_prep_dma_xor
  - drivers/dma/mv_xor.c:mv_xor_alloc_chan_resources
  - drivers/dma/mv_xor.c:mv_xor_tx_submit
```
```
In drivers/dma/mv_xor_v2.c (ffff800010808568)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - drivers/dma/mv_xor_v2.c:mv_xor_v2_tasklet
  - drivers/dma/mv_xor_v2.c:mv_xor_v2_issue_pending
  - drivers/dma/mv_xor_v2.c:mv_xor_v2_prep_sw_desc
  - drivers/dma/mv_xor_v2.c:mv_xor_v2_tx_submit
```
```
In drivers/connector/cn_queue.c (ffff8000108dd6a4)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_free_dev
  - drivers/connector/cn_queue.c:cn_queue_del_callback
  - drivers/connector/cn_queue.c:cn_queue_add_callback
```
```
In drivers/connector/connector.c (ffff8000108ddc24)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_proc_show
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/net/tun.c (ffff8000109dbfe0)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_set_ebpf
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_flow_update
  - drivers/net/tun.c:tun_flow_flush
```
```
In drivers/net/ppp/ppp_generic.c (ffff8000109ffed4)
Location: include/linux/spinlock.h:341
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
  - drivers/net/ppp/ppp_generic.c:ppp_poll
  - drivers/net/ppp/ppp_generic.c:ppp_read
```
```
In drivers/net/xen-netfront.c (ffff800010a091d8)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:netback_changed
  - drivers/net/xen-netfront.c:xennet_open
```
```
In net/core/sock.c (ffff800010baddfc)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/sock.c:release_sock
  - net/core/sock.c:lock_sock_nested
  - net/core/sock.c:__sk_flush_backlog
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__lock_sock
```
```
In net/core/request_sock.c (ffff800010bb034c)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/core/datagram.c (ffff800010bbc90c)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/datagram.c:__sk_queue_drop_skb
```
```
In net/core/gen_stats.c (ffff800010bbf2f8)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/gen_stats.c:gnet_stats_start_copy_compat
```
```
In net/core/gen_estimator.c (ffff800010bbf914)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/net_namespace.c (ffff800010bc1960)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:peernet2id
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/dev.c (ffff800010bd5ab4)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/dev.c:dev_set_rx_mode
  - net/core/dev.c:netif_set_real_num_tx_queues
```
```
In net/core/dev_addr_lists.c (ffff800010bdf6b4)
Location: include/linux/spinlock.h:341
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
In net/core/neighbour.c (ffff800010be6500)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/core/rtnetlink.c (ffff800010beebec)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_fdb_dump
```
```
In net/core/sock_reuseport.c (ffff800010c0529c)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_attach_prog
  - net/core/sock_reuseport.c:reuseport_detach_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_alloc
```
```
In net/core/page_pool.c (ffff800010c0cabc)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
```
```
In net/core/net-procfs.c (ffff800010c0dfe0)
Location: include/linux/spinlock.h:341
Inline: True
```
```
In net/core/skmsg.c (ffff800010c0fb98)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_link_pop
```
```
In net/core/sock_map.c (ffff800010c20e88)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_unref
```
```
In net/core/devlink.c (ffff800010c2add8)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_port_type_set
  - net/core/devlink.c:devlink_nl_port_fill
```
```
In net/sched/sch_generic.c (ffff800010c3a1a4)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_graft_qdisc
```
```
In net/sched/sch_mq.c (ffff800010c3b0e4)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump
```
```
In net/sched/sch_api.c (ffff800010c3d094)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/sched/sch_api.c:tcf_node_bind
  - net/sched/sch_api.c:qdisc_class_hash_grow
```
```
In net/ipv4/route.c (ffff800010c5a8c8)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_flush_dev
  - net/ipv4/route.c:rt_add_uncached_list
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/inetpeer.c (ffff800010c5da24)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/inet_hashtables.c (ffff800010c6b30c)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_unhash
```
```
In net/ipv4/inet_connection_sock.c (ffff800010c6da18)
Location: include/linux/spinlock.h:341
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
In net/ipv4/tcp_ipv4.c (ffff800010c8b938)
Location: include/linux/spinlock.h:341
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffff800010c925d4)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_flush_all
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/raw.c (ffff800010c97310)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_ioctl
```
```
In net/ipv4/udp.c (ffff800010c9bad4)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/af_inet.c (ffff800010cabc24)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_register_protosw
```
```
In net/ipv4/igmp.c (ffff800010cb0388)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
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
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:igmp_stop_timer
```
```
In net/ipv4/fib_semantics.c (ffff800010cb82c8)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_release_info
```
```
In net/ipv4/inet_fragment.c (ffff800010cbeb00)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frags_free_cb
```
```
In net/ipv4/sysctl_net_ipv4.c (ffff800010cc745c)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
```
In net/ipv4/ipmr.c (ffff800010ccc124)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
```
```
In net/ipv4/ipmr_base.c (ffff800010cd0f30)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_table_dump
  - net/ipv4/ipmr_base.c:mr_mfc_seq_next
```
```
In net/ipv4/tcp_bpf.c (ffff800010cd477c)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_init
```
```
In net/ipv4/cipso_ipv4.c (ffff800010cd5414)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_invalidate
```
```
In net/xfrm/xfrm_policy.c (ffff800010cdd5a0)
Location: include/linux/spinlock.h:341
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
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffff800010ce5048)
Location: include/linux/spinlock.h:341
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
In net/xfrm/xfrm_input.c (ffff800010ce9dd8)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo
  - net/xfrm/xfrm_input.c:xfrm_input_register_afinfo
```
```
In net/xfrm/xfrm_output.c (ffff800010cebfd4)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/af_inet6.c (ffff800010cf6444)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_register_protosw
```
```
In net/ipv6/addrconf.c (ffff800010d0ab18)
Location: include/linux/spinlock.h:341
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
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/route.c (ffff800010d119d0)
Location: include/linux/spinlock.h:341
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
In net/ipv6/ip6_fib.c (ffff800010d19de0)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:__fib6_clean_all
  - net/ipv6/ip6_fib.c:fib6_update_sernum_stub
  - net/ipv6/ip6_fib.c:fib6_tables_dump
```
```
In net/ipv6/raw.c (ffff800010d292d0)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_ioctl
```
```
In net/ipv6/mcast.c (ffff800010d308b4)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mcf_seq_next
  - net/ipv6/mcast.c:igmp6_mcf_seq_start
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:ip6_mc_add_src
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
In net/ipv6/ip6_flowlabel.c (ffff800010d3eef0)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
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
In net/ipv6/ip6mr.c (ffff800010d44d44)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
```
```
In net/ipv6/calipso.c (ffff800010d4e7c4)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_cache_invalidate
```
```
In net/packet/af_packet.c (ffff800010d5bd38)
Location: include/linux/spinlock.h:341
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
In net/dcb/dcbnl.c (ffff800010d6fbdc)
Location: include/linux/spinlock.h:341
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
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
```
```
In net/switchdev/switchdev.c (ffff800010d74080)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_deferred_process
```
```
In net/xdp/xsk.c (ffff800010d7f0e0)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xsk.c:xsk_generic_rcv
```
```
In lib/xarray.c (ffff800010d9b358)
Location: include/linux/spinlock.h:341
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
In kernel/cgroup/cgroup.c (c0412a28)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_idr_remove
  - kernel/cgroup/cgroup.c:cgroup_idr_replace
```
```
In kernel/bpf/core.c (c0491898)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
```
```
In kernel/bpf/syscall.c (c049751c)
Location: include/linux/spinlock.h:341
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
In kernel/bpf/local_storage.c (c04b0888)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_unlink
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_link
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_release
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_assign
  - kernel/bpf/local_storage.c:cgroup_storage_get_next_key
  - kernel/bpf/local_storage.c:cgroup_storage_lookup
```
```
In kernel/bpf/btf.c (c04b5c3c)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
```
```
In kernel/bpf/xskmap.c (c04b8fa8)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - kernel/bpf/xskmap.c:xsk_map_try_sock_delete
  - kernel/bpf/xskmap.c:xsk_map_delete_elem
  - kernel/bpf/xskmap.c:xsk_map_update_elem
  - kernel/bpf/xskmap.c:xsk_map_update_elem
  - kernel/bpf/xskmap.c:xsk_map_sock_delete
```
```
In kernel/bpf/reuseport_array.c (c04bfb24)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem
  - kernel/bpf/reuseport_array.c:reuseport_array_delete_elem
```
```
In mm/page-writeback.c (c04e6278)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - mm/page-writeback.c:bdi_set_max_ratio
  - mm/page-writeback.c:bdi_set_min_ratio
```
```
In mm/backing-dev.c (c0503bbc)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:bdi_register_va
  - mm/backing-dev.c:bdi_get_by_id
  - mm/backing-dev.c:wb_wakeup_delayed
```
```
In fs/fs-writeback.c (c05a75d0)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_queue_work
  - fs/fs-writeback.c:wb_wakeup
```
```
In security/selinux/netif.c (c070cd14)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_netdev_notifier_handler
  - security/selinux/netif.c:sel_netif_flush
  - security/selinux/netif.c:sel_netif_sid
```
```
In security/selinux/netnode.c (c070d324)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_flush
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (c070d5dc)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_flush
  - security/selinux/netport.c:sel_netport_sid
```
```
In block/genhd.c (c07a5414)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - block/genhd.c:get_gendisk
```
```
In block/blk-cgroup.c (c07b8f68)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - block/blk-cgroup.c:__blkcg_punt_bio_submit
  - block/blk-cgroup.c:blkg_async_bio_workfn
```
```
In drivers/dma/dmaengine.c (c091d8b8)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_run_dependencies
```
```
In drivers/dma/mv_xor.c (c0924990)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - drivers/dma/mv_xor.c:mv_xor_status
  - drivers/dma/mv_xor.c:mv_xor_free_chan_resources
  - drivers/dma/mv_xor.c:mv_xor_prep_dma_xor
  - drivers/dma/mv_xor.c:mv_xor_alloc_chan_resources
  - drivers/dma/mv_xor.c:mv_xor_tx_submit
```
```
In drivers/connector/cn_queue.c (c09cc940)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_free_dev
  - drivers/connector/cn_queue.c:cn_queue_del_callback
  - drivers/connector/cn_queue.c:cn_queue_add_callback
```
```
In drivers/connector/connector.c (c09cca94)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_proc_show
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/net/tun.c (c0ac2378)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_set_ebpf
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_flow_update
  - drivers/net/tun.c:tun_flow_flush
```
```
In drivers/net/ppp/ppp_generic.c (c0adc034)
Location: include/linux/spinlock.h:341
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
  - drivers/net/ppp/ppp_generic.c:ppp_poll
  - drivers/net/ppp/ppp_generic.c:ppp_read
```
```
In net/core/sock.c (c0ccb8e8)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/sock.c:release_sock
  - net/core/sock.c:lock_sock_nested
  - net/core/sock.c:__sk_flush_backlog
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__lock_sock
```
```
In net/core/request_sock.c (c0ccd784)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/core/datagram.c (c0cd7df8)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/datagram.c:__sk_queue_drop_skb
```
```
In net/core/gen_stats.c (c0cda95c)
Location: include/linux/spinlock.h:341
Inline: True
```
```
In net/core/gen_estimator.c (c0cdb3dc)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/net_namespace.c (c0cdc8e8)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:peernet2id
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/dev.c (c0cf0714)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/dev.c:dev_set_rx_mode
  - net/core/dev.c:netif_set_real_num_tx_queues
```
```
In net/core/dev_addr_lists.c (c0cf9814)
Location: include/linux/spinlock.h:341
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
In net/core/neighbour.c (c0cfeebc)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/core/rtnetlink.c (c0d07094)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_fdb_dump
```
```
In net/core/sock_reuseport.c (c0d1e5a8)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_attach_prog
  - net/core/sock_reuseport.c:reuseport_detach_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_alloc
```
```
In net/core/page_pool.c (c0d251f8)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
```
```
In net/core/net-procfs.c (c0d25eb8)
Location: include/linux/spinlock.h:341
Inline: True
```
```
In net/core/skmsg.c (c0d27a34)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_link_pop
```
```
In net/core/sock_map.c (c0d38774)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_unref
```
```
In net/core/devlink.c (c0d42218)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_port_type_set
  - net/core/devlink.c:devlink_nl_port_fill
```
```
In net/sched/sch_generic.c (c0d4c43c)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_graft_qdisc
```
```
In net/sched/sch_mq.c (c0d4cb84)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump
```
```
In net/sched/sch_api.c (c0d4eba0)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/sched/sch_api.c:tcf_node_bind
  - net/sched/sch_api.c:qdisc_class_hash_grow
```
```
In net/ipv4/route.c (c0d69e50)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_flush_dev
  - net/ipv4/route.c:ipv4_dst_destroy
  - net/ipv4/route.c:rt_add_uncached_list
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/inetpeer.c (c0d6cdf0)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/inet_hashtables.c (c0d7a404)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_unhash
```
```
In net/ipv4/inet_connection_sock.c (c0d7c060)
Location: include/linux/spinlock.h:341
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
In net/ipv4/tcp_ipv4.c (c0d9a048)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:established_get_first
```
```
In net/ipv4/tcp_metrics.c (c0da06e4)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_flush_all
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/raw.c (c0da4d58)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_ioctl
```
```
In net/ipv4/udp.c (c0da7dc8)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_get_first
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/af_inet.c (c0db63cc)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_register_protosw
```
```
In net/ipv4/igmp.c (c0db95e4)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
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
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:igmp_stop_timer
```
```
In net/ipv4/fib_semantics.c (c0dc3674)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_release_info
```
```
In net/ipv4/inet_fragment.c (c0dca214)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frags_free_cb
```
```
In net/ipv4/sysctl_net_ipv4.c (c0dd2308)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
```
In net/ipv4/ipmr.c (c0dd7e14)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
```
```
In net/ipv4/ipmr_base.c (c0dda994)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_table_dump
  - net/ipv4/ipmr_base.c:mr_mfc_seq_next
```
```
In net/ipv4/tcp_bpf.c (c0dde8c0)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_init
```
```
In net/ipv4/cipso_ipv4.c (c0ddf40c)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_invalidate
```
```
In net/xfrm/xfrm_policy.c (c0de74a8)
Location: include/linux/spinlock.h:341
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
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (c0deba38)
Location: include/linux/spinlock.h:341
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
In net/xfrm/xfrm_input.c (c0df1d30)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo
  - net/xfrm/xfrm_input.c:xfrm_input_register_afinfo
```
```
In net/xfrm/xfrm_output.c (c0df3f98)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/af_inet6.c (c0dfc5a8)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_register_protosw
```
```
In net/ipv6/addrconf.c (c0e111dc)
Location: include/linux/spinlock.h:341
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
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/route.c (c0e14e28)
Location: include/linux/spinlock.h:341
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
In net/ipv6/ip6_fib.c (c0e1ed70)
Location: include/linux/spinlock.h:341
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
In net/ipv6/raw.c (c0e2ccc4)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_ioctl
```
```
In net/ipv6/mcast.c (c0e31440)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mcf_seq_next
  - net/ipv6/mcast.c:igmp6_mcf_seq_start
  - net/ipv6/mcast.c:igmp6_mcf_get_next
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:ip6_mc_add_src
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
In net/ipv6/ip6_flowlabel.c (c0e41fec)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
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
In net/ipv6/ip6mr.c (c0e4721c)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
```
```
In net/ipv6/calipso.c (c0e4f100)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_cache_invalidate
```
```
In net/packet/af_packet.c (c0e5be70)
Location: include/linux/spinlock.h:341
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
In net/dcb/dcbnl.c (c0e6bae4)
Location: include/linux/spinlock.h:341
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
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
```
```
In net/switchdev/switchdev.c (c0e70278)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_deferred_enqueue
  - net/switchdev/switchdev.c:switchdev_deferred_process
```
```
In net/xdp/xsk.c (c0e792ec)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xsk.c:xsk_generic_rcv
```
```
In lib/xarray.c (c0e96c44)
Location: include/linux/spinlock.h:341
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
In kernel/cgroup/cgroup.c (c000000000239184)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_idr_remove
  - kernel/cgroup/cgroup.c:cgroup_idr_replace
```
```
In kernel/bpf/core.c (c000000000302ec4)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
```
```
In kernel/bpf/syscall.c (c00000000030a090)
Location: include/linux/spinlock.h:341
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
In kernel/bpf/local_storage.c (c000000000329704)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_unlink
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_link
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_release
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_assign
  - kernel/bpf/local_storage.c:cgroup_storage_get_next_key
  - kernel/bpf/local_storage.c:cgroup_storage_lookup
```
```
In kernel/bpf/btf.c (c0000000003304a4)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
```
```
In kernel/bpf/xskmap.c (c000000000334ce8)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - kernel/bpf/xskmap.c:xsk_map_try_sock_delete
  - kernel/bpf/xskmap.c:xsk_map_delete_elem
  - kernel/bpf/xskmap.c:xsk_map_update_elem
  - kernel/bpf/xskmap.c:xsk_map_update_elem
  - kernel/bpf/xskmap.c:xsk_map_sock_delete
```
```
In kernel/bpf/reuseport_array.c (c00000000033d428)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem
  - kernel/bpf/reuseport_array.c:reuseport_array_delete_elem
```
```
In mm/page-writeback.c (c000000000372040)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - mm/page-writeback.c:bdi_set_max_ratio
  - mm/page-writeback.c:bdi_set_min_ratio
```
```
In mm/backing-dev.c (c00000000039e534)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:bdi_get_by_id
  - mm/backing-dev.c:wb_shutdown
  - mm/backing-dev.c:wb_wakeup_delayed
```
```
In fs/fs-writeback.c (c0000000004ccd54)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_queue_work
  - fs/fs-writeback.c:wb_wakeup
```
```
In security/selinux/netif.c (c0000000006b5e68)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_netdev_notifier_handler
  - security/selinux/netif.c:sel_netif_flush
  - security/selinux/netif.c:sel_netif_sid
```
```
In security/selinux/netnode.c (c0000000006b6714)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_flush
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (c0000000006b6af4)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_flush
  - security/selinux/netport.c:sel_netport_sid
```
```
In block/genhd.c (c000000000793430)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - block/genhd.c:get_gendisk
```
```
In block/blk-cgroup.c (c0000000007abc60)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - block/blk-cgroup.c:__blkcg_punt_bio_submit
  - block/blk-cgroup.c:blkg_async_bio_workfn
```
```
In drivers/connector/cn_queue.c (c000000000970ee0)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_free_dev
  - drivers/connector/cn_queue.c:cn_queue_del_callback
  - drivers/connector/cn_queue.c:cn_queue_add_callback
```
```
In drivers/connector/connector.c (c0000000009710e8)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_proc_show
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/net/tun.c (c000000000a9da64)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_set_ebpf
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_flow_update
  - drivers/net/tun.c:tun_flow_flush
```
```
In drivers/net/ppp/ppp_generic.c (c000000000aa61e8)
Location: include/linux/spinlock.h:341
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
  - drivers/net/ppp/ppp_generic.c:ppp_poll
  - drivers/net/ppp/ppp_generic.c:ppp_read
```
```
In net/core/sock.c (c000000000c837f4)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/sock.c:release_sock
  - net/core/sock.c:lock_sock_nested
  - net/core/sock.c:__sk_flush_backlog
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__lock_sock
```
```
In net/core/request_sock.c (c000000000c85da8)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/core/datagram.c (c000000000c944f4)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/datagram.c:__sk_queue_drop_skb
```
```
In net/core/gen_stats.c (c000000000c980b0)
Location: include/linux/spinlock.h:341
Inline: True
```
```
In net/core/gen_estimator.c (c000000000c98cf4)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/net_namespace.c (c000000000c9a7c4)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:peernet2id
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/dev.c (c000000000cb51a4)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/dev.c:dev_set_rx_mode
  - net/core/dev.c:netif_set_real_num_tx_queues
```
```
In net/core/dev_addr_lists.c (c000000000cbf5f4)
Location: include/linux/spinlock.h:341
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
In net/core/neighbour.c (c000000000cc8070)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/core/rtnetlink.c (c000000000cd2944)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_fdb_dump
```
```
In net/core/sock_reuseport.c (c000000000cef474)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_attach_prog
  - net/core/sock_reuseport.c:reuseport_detach_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_alloc
```
```
In net/core/page_pool.c (c000000000cf840c)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
```
```
In net/core/net-procfs.c (c000000000cf9628)
Location: include/linux/spinlock.h:341
Inline: True
```
```
In net/core/skmsg.c (c000000000cfbd70)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_link_pop
```
```
In net/core/sock_map.c (c000000000d13018)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_unref
```
```
In net/core/devlink.c (c000000000d20394)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_port_type_set
  - net/core/devlink.c:devlink_nl_port_fill
```
```
In net/sched/sch_generic.c (c000000000d3326c)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_graft_qdisc
```
```
In net/sched/sch_mq.c (c000000000d33bf0)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump
```
```
In net/sched/sch_api.c (c000000000d38020)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_grow
```
```
In net/ipv4/route.c (c000000000d5c4f4)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_flush_dev
  - net/ipv4/route.c:ipv4_dst_destroy
  - net/ipv4/route.c:rt_add_uncached_list
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/inetpeer.c (c000000000d5ff48)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/inet_hashtables.c (c000000000d70848)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_unhash
```
```
In net/ipv4/inet_connection_sock.c (c000000000d72f9c)
Location: include/linux/spinlock.h:341
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
In net/ipv4/tcp_ipv4.c (c000000000d98270)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:established_get_first
```
```
In net/ipv4/tcp_metrics.c (c000000000da1eb8)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_flush_all
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/raw.c (c000000000da8894)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_ioctl
```
```
In net/ipv4/udp.c (c000000000dab948)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_get_first
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/af_inet.c (c000000000dbf238)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_register_protosw
```
```
In net/ipv4/igmp.c (c000000000dc4308)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
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
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:igmp_stop_timer
```
```
In net/ipv4/fib_semantics.c (c000000000dd0c08)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_release_info
```
```
In net/ipv4/inet_fragment.c (c000000000dd9064)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frags_free_cb
```
```
In net/ipv4/sysctl_net_ipv4.c (c000000000de3920)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
```
In net/ipv4/ipmr.c (c000000000deb20c)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
```
```
In net/ipv4/ipmr_base.c (c000000000dee750)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_table_dump
  - net/ipv4/ipmr_base.c:mr_mfc_seq_next
```
```
In net/ipv4/tcp_bpf.c (c000000000df3ad8)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_init
```
```
In net/ipv4/cipso_ipv4.c (c000000000df4aec)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_invalidate
```
```
In net/xfrm/xfrm_policy.c (c000000000dfda98)
Location: include/linux/spinlock.h:341
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
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:xfrm_bydst_resize
```
```
In net/xfrm/xfrm_state.c (c000000000e054f8)
Location: include/linux/spinlock.h:341
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
In net/xfrm/xfrm_input.c (c000000000e0d604)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo
  - net/xfrm/xfrm_input.c:xfrm_input_register_afinfo
```
```
In net/xfrm/xfrm_output.c (c000000000e100b4)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/af_inet6.c (c000000000e1c050)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_register_protosw
```
```
In net/ipv6/addrconf.c (c000000000e35874)
Location: include/linux/spinlock.h:341
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
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/route.c (c000000000e3b504)
Location: include/linux/spinlock.h:341
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
In net/ipv6/ip6_fib.c (c000000000e46d7c)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:__fib6_clean_all
  - net/ipv6/ip6_fib.c:fib6_update_sernum_stub
  - net/ipv6/ip6_fib.c:fib6_tables_dump
```
```
In net/ipv6/raw.c (c000000000e5a4c4)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_ioctl
```
```
In net/ipv6/mcast.c (c000000000e602b8)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mcf_seq_next
  - net/ipv6/mcast.c:igmp6_mcf_seq_start
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:ip6_mc_add_src
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
In net/ipv6/ip6_flowlabel.c (c000000000e73598)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
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
In net/ipv6/ip6mr.c (c000000000e7937c)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
```
```
In net/ipv6/calipso.c (c000000000e850b8)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_cache_invalidate
```
```
In net/packet/af_packet.c (c000000000e97730)
Location: include/linux/spinlock.h:341
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
In net/dcb/dcbnl.c (c000000000eac138)
Location: include/linux/spinlock.h:341
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
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
```
```
In net/switchdev/switchdev.c (c000000000eb2618)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_deferred_process
```
```
In net/xdp/xsk.c (c000000000ebf3bc)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xsk.c:xsk_generic_rcv
```
```
In lib/xarray.c (c000000000eded44)
Location: include/linux/spinlock.h:341
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
In kernel/cgroup/cgroup.c (ffffffe00014980c)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_idr_remove
  - kernel/cgroup/cgroup.c:cgroup_idr_replace
```
```
In kernel/bpf/core.c (ffffffe00019c6a6)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
```
```
In kernel/bpf/syscall.c (ffffffe0001a0dd4)
Location: include/linux/spinlock.h:341
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
In kernel/bpf/local_storage.c (ffffffe0001b613c)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_unlink
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_link
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_release
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_assign
  - kernel/bpf/local_storage.c:cgroup_storage_get_next_key
  - kernel/bpf/local_storage.c:cgroup_storage_lookup
```
```
In kernel/bpf/btf.c (ffffffe0001baa80)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
```
```
In kernel/bpf/xskmap.c (ffffffe0001bd9e2)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - kernel/bpf/xskmap.c:xsk_map_try_sock_delete
  - kernel/bpf/xskmap.c:xsk_map_delete_elem
  - kernel/bpf/xskmap.c:xsk_map_update_elem
  - kernel/bpf/xskmap.c:xsk_map_update_elem
  - kernel/bpf/xskmap.c:xsk_map_sock_delete
```
```
In kernel/bpf/reuseport_array.c (ffffffe0001c3026)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem
  - kernel/bpf/reuseport_array.c:reuseport_array_delete_elem
```
```
In mm/page-writeback.c (ffffffe0001dd320)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - mm/page-writeback.c:bdi_set_max_ratio
  - mm/page-writeback.c:bdi_set_min_ratio
```
```
In mm/backing-dev.c (ffffffe0001f6ab6)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:bdi_get_by_id
  - mm/backing-dev.c:wb_wakeup_delayed
```
```
In fs/fs-writeback.c (ffffffe0002890fa)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_queue_work
  - fs/fs-writeback.c:wb_wakeup
```
```
In security/selinux/netif.c (ffffffe0003af72a)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_netdev_notifier_handler
  - security/selinux/netif.c:sel_netif_flush
  - security/selinux/netif.c:sel_netif_sid
```
```
In security/selinux/netnode.c (ffffffe0003afca6)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_flush
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (ffffffe0003aff02)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_flush
  - security/selinux/netport.c:sel_netport_sid
```
```
In block/genhd.c (ffffffe000436a16)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - block/genhd.c:get_gendisk
```
```
In block/blk-cgroup.c (ffffffe000446c14)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - block/blk-cgroup.c:__blkcg_punt_bio_submit
  - block/blk-cgroup.c:blkg_async_bio_workfn
```
```
In drivers/connector/cn_queue.c (ffffffe000573eec)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_free_dev
  - drivers/connector/cn_queue.c:cn_queue_del_callback
  - drivers/connector/cn_queue.c:cn_queue_add_callback
```
```
In drivers/connector/connector.c (ffffffe000574034)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_proc_show
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/net/tun.c (ffffffe0006260c6)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_set_ebpf
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_flow_update
  - drivers/net/tun.c:tun_flow_flush
```
```
In drivers/net/ppp/ppp_generic.c (ffffffe00062bdde)
Location: include/linux/spinlock.h:341
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
  - drivers/net/ppp/ppp_generic.c:ppp_poll
  - drivers/net/ppp/ppp_generic.c:ppp_read
```
```
In net/core/sock.c (ffffffe00073fe8e)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/sock.c:release_sock
  - net/core/sock.c:lock_sock_nested
  - net/core/sock.c:__sk_flush_backlog
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__lock_sock
```
```
In net/core/request_sock.c (ffffffe000741224)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/core/datagram.c (ffffffe00074a658)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/datagram.c:__sk_queue_drop_skb
```
```
In net/core/gen_stats.c (ffffffe00074cb50)
Location: include/linux/spinlock.h:341
Inline: True
```
```
In net/core/gen_estimator.c (ffffffe00074d2c8)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/net_namespace.c (ffffffe00074e3c6)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:peernet2id
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/dev.c (ffffffe00075f3f8)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/dev.c:dev_set_rx_mode
  - net/core/dev.c:netif_set_real_num_tx_queues
```
```
In net/core/dev_addr_lists.c (ffffffe000765a98)
Location: include/linux/spinlock.h:341
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
In net/core/neighbour.c (ffffffe00076b07c)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/core/rtnetlink.c (ffffffe00077128c)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_fdb_dump
```
```
In net/core/sock_reuseport.c (ffffffe000783c82)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_attach_prog
  - net/core/sock_reuseport.c:reuseport_detach_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_alloc
```
```
In net/core/page_pool.c (ffffffe000789c6a)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
```
```
In net/core/net-procfs.c (ffffffe00078a97a)
Location: include/linux/spinlock.h:341
Inline: True
```
```
In net/core/skmsg.c (ffffffe00078c1c2)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_link_pop
```
```
In net/core/sock_map.c (ffffffe000799c50)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_unref
```
```
In net/core/devlink.c (ffffffe0007a23e8)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_port_type_set
  - net/core/devlink.c:devlink_nl_port_fill
```
```
In net/sched/sch_generic.c (ffffffe0007ab3ba)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_graft_qdisc
```
```
In net/sched/sch_mq.c (ffffffe0007abf3c)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump
```
```
In net/sched/sch_api.c (ffffffe0007ad612)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/sched/sch_api.c:tcf_node_bind
  - net/sched/sch_api.c:qdisc_class_hash_grow
```
```
In net/ipv4/route.c (ffffffe0007c3d4a)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_flush_dev
  - net/ipv4/route.c:ipv4_dst_destroy
  - net/ipv4/route.c:rt_add_uncached_list
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/inetpeer.c (ffffffe0007c62be)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/inet_hashtables.c (ffffffe0007d0fa4)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_unhash
```
```
In net/ipv4/inet_connection_sock.c (ffffffe0007d2e28)
Location: include/linux/spinlock.h:341
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
In net/ipv4/tcp_ipv4.c (ffffffe0007eb4d2)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:established_get_first
```
```
In net/ipv4/tcp_metrics.c (ffffffe0007f1a96)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_flush_all
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/raw.c (ffffffe0007f5922)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_ioctl
```
```
In net/ipv4/udp.c (ffffffe0007f7492)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_get_first
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/af_inet.c (ffffffe000804734)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_register_protosw
```
```
In net/ipv4/igmp.c (ffffffe000807f5a)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
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
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:igmp_stop_timer
```
```
In net/ipv4/fib_semantics.c (ffffffe00080f270)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_release_info
```
```
In net/ipv4/inet_fragment.c (ffffffe000814894)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frags_free_cb
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffe00081b41a)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
```
In net/ipv4/ipmr.c (ffffffe000820b4c)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
```
```
In net/ipv4/ipmr_base.c (ffffffe000822292)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_table_dump
  - net/ipv4/ipmr_base.c:mr_mfc_seq_next
```
```
In net/ipv4/tcp_bpf.c (ffffffe000825622)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_init
```
```
In net/ipv4/cipso_ipv4.c (ffffffe00082618c)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_invalidate
```
```
In net/xfrm/xfrm_policy.c (ffffffe00082af62)
Location: include/linux/spinlock.h:341
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
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffe000830f62)
Location: include/linux/spinlock.h:341
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
In net/xfrm/xfrm_input.c (ffffffe000837a72)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo
  - net/xfrm/xfrm_input.c:xfrm_input_register_afinfo
```
```
In net/xfrm/xfrm_output.c (ffffffe0008398f4)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/af_inet6.c (ffffffe0008415cc)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_register_protosw
```
```
In net/ipv6/addrconf.c (ffffffe00085250a)
Location: include/linux/spinlock.h:341
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
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/route.c (ffffffe0008563e6)
Location: include/linux/spinlock.h:341
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
In net/ipv6/ip6_fib.c (ffffffe00085db4c)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:__fib6_clean_all
  - net/ipv6/ip6_fib.c:fib6_update_sernum_stub
  - net/ipv6/ip6_fib.c:fib6_tables_dump
```
```
In net/ipv6/raw.c (ffffffe000869ae0)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_ioctl
```
```
In net/ipv6/mcast.c (ffffffe00086e2b2)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mcf_seq_next
  - net/ipv6/mcast.c:igmp6_mcf_seq_start
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:ip6_mc_add_src
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
In net/ipv6/ip6_flowlabel.c (ffffffe00087b196)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
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
In net/ipv6/ip6mr.c (ffffffe00087f7d4)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
```
```
In net/ipv6/calipso.c (ffffffe000886fb6)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_cache_invalidate
```
```
In net/packet/af_packet.c (ffffffe0008920a4)
Location: include/linux/spinlock.h:341
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
In net/dcb/dcbnl.c (ffffffe00089fe30)
Location: include/linux/spinlock.h:341
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
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
```
```
In net/switchdev/switchdev.c (ffffffe0008a366a)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_deferred_process
```
```
In net/xdp/xsk.c (ffffffe0008ac2ac)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xsk.c:xsk_generic_rcv
```
```
In lib/xarray.c (ffffffe0008c366a)
Location: include/linux/spinlock.h:341
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
In kernel/cgroup/cgroup.c (ffffffff81156d95)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_idr_remove
  - kernel/cgroup/cgroup.c:cgroup_idr_replace
```
```
In kernel/bpf/core.c (ffffffff811d5c24)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
```
```
In kernel/bpf/syscall.c (ffffffff811da53f)
Location: include/linux/spinlock.h:341
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
In kernel/bpf/local_storage.c (ffffffff811f20da)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_unlink
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_link
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_release
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_assign
  - kernel/bpf/local_storage.c:cgroup_storage_get_next_key
  - kernel/bpf/local_storage.c:cgroup_storage_lookup
```
```
In kernel/bpf/btf.c (ffffffff811f6ca3)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
```
```
In kernel/bpf/xskmap.c (ffffffff811f9c75)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - kernel/bpf/xskmap.c:xsk_map_try_sock_delete
  - kernel/bpf/xskmap.c:xsk_map_delete_elem
  - kernel/bpf/xskmap.c:xsk_map_update_elem
  - kernel/bpf/xskmap.c:xsk_map_update_elem
  - kernel/bpf/xskmap.c:xsk_map_sock_delete
```
```
In kernel/bpf/reuseport_array.c (ffffffff811ff2f3)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem
  - kernel/bpf/reuseport_array.c:reuseport_array_delete_elem
```
```
In mm/page-writeback.c (ffffffff81223bbf)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - mm/page-writeback.c:bdi_set_max_ratio
  - mm/page-writeback.c:bdi_set_min_ratio
```
```
In mm/backing-dev.c (ffffffff81241b5d)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:bdi_get_by_id
  - mm/backing-dev.c:wb_wakeup_delayed
```
```
In fs/fs-writeback.c (ffffffff8130d5be)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_queue_work
  - fs/fs-writeback.c:wb_wakeup
```
```
In security/selinux/netif.c (ffffffff81461ea6)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_netdev_notifier_handler
  - security/selinux/netif.c:sel_netif_flush
  - security/selinux/netif.c:sel_netif_sid
```
```
In security/selinux/netnode.c (ffffffff81462475)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_flush
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (ffffffff81462725)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_flush
  - security/selinux/netport.c:sel_netport_sid
```
```
In block/genhd.c (ffffffff814f148f)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - block/genhd.c:get_gendisk
```
```
In block/blk-cgroup.c (ffffffff8150341e)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - block/blk-cgroup.c:__blkcg_punt_bio_submit
  - block/blk-cgroup.c:blkg_async_bio_workfn
```
```
In drivers/connector/cn_queue.c (ffffffff816b9d45)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_free_dev
  - drivers/connector/cn_queue.c:cn_queue_del_callback
  - drivers/connector/cn_queue.c:cn_queue_add_callback
```
```
In drivers/connector/connector.c (ffffffff816b9e8f)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_proc_show
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/net/tun.c (ffffffff817856c0)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_set_ebpf
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_flow_update
  - drivers/net/tun.c:tun_flow_flush
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8178bdb5)
Location: include/linux/spinlock.h:341
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
  - drivers/net/ppp/ppp_generic.c:ppp_poll
  - drivers/net/ppp/ppp_generic.c:ppp_read
```
```
In drivers/net/xen-netfront.c (ffffffff8179488f)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:netback_changed
```
```
In net/core/sock.c (ffffffff818b4fa5)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/sock.c:release_sock
  - net/core/sock.c:lock_sock_nested
  - net/core/sock.c:__sk_flush_backlog
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__lock_sock
```
```
In net/core/request_sock.c (ffffffff818b6e05)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/core/datagram.c (ffffffff818c121d)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/datagram.c:__sk_queue_drop_skb
```
```
In net/core/gen_stats.c (ffffffff818c3882)
Location: include/linux/spinlock.h:341
Inline: True
```
```
In net/core/gen_estimator.c (ffffffff818c40d5)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/net_namespace.c (ffffffff818c56ea)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:peernet2id
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/dev.c (ffffffff818d7145)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/dev.c:dev_set_rx_mode
  - net/core/dev.c:netif_set_real_num_tx_queues
```
```
In net/core/dev_addr_lists.c (ffffffff818dfaf5)
Location: include/linux/spinlock.h:341
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
In net/core/neighbour.c (ffffffff818e6757)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/core/rtnetlink.c (ffffffff818eca1d)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_fdb_dump
```
```
In net/core/sock_reuseport.c (ffffffff819017d7)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_attach_prog
  - net/core/sock_reuseport.c:reuseport_detach_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_alloc
```
```
In net/core/page_pool.c (ffffffff819074e5)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
```
```
In net/core/net-procfs.c (ffffffff81907f9b)
Location: include/linux/spinlock.h:341
Inline: True
```
```
In net/core/skmsg.c (ffffffff819099c5)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_link_pop
```
```
In net/core/sock_map.c (ffffffff8191988d)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_unref
```
```
In net/core/devlink.c (ffffffff81922b15)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_port_type_set
  - net/core/devlink.c:devlink_nl_port_fill
```
```
In net/sched/sch_generic.c (ffffffff8192e6e2)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_graft_qdisc
```
```
In net/sched/sch_mq.c (ffffffff8192edf1)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump
```
```
In net/sched/sch_api.c (ffffffff81930a19)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/sched/sch_api.c:tcf_node_bind
  - net/sched/sch_api.c:qdisc_class_hash_grow
```
```
In net/ipv4/route.c (ffffffff8194a468)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_flush_dev
  - net/ipv4/route.c:ipv4_dst_destroy
  - net/ipv4/route.c:rt_add_uncached_list
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/inetpeer.c (ffffffff8194d526)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/inet_hashtables.c (ffffffff819599c8)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_unhash
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8195ba56)
Location: include/linux/spinlock.h:341
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
In net/ipv4/tcp_ipv4.c (ffffffff819781c3)
Location: include/linux/spinlock.h:341
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff8197e6eb)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_flush_all
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/raw.c (ffffffff81982aaa)
Location: include/linux/spinlock.h:341
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819879e2)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/af_inet.c (ffffffff81993703)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_register_protosw
```
```
In net/ipv4/igmp.c (ffffffff81996d3c)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
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
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:igmp_stop_timer
```
```
In net/ipv4/fib_semantics.c (ffffffff8199fa2d)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_release_info
```
```
In net/ipv4/inet_fragment.c (ffffffff819a5879)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frags_free_cb
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff819ad0c0)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
```
In net/ipv4/ipmr.c (ffffffff819b21c5)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
```
```
In net/ipv4/ipmr_base.c (ffffffff819b4687)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_table_dump
  - net/ipv4/ipmr_base.c:mr_mfc_seq_next
```
```
In net/ipv4/tcp_bpf.c (ffffffff819b82e1)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_init
```
```
In net/ipv4/cipso_ipv4.c (ffffffff819b8da1)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_invalidate
```
```
In net/xfrm/xfrm_policy.c (ffffffff819c073b)
Location: include/linux/spinlock.h:341
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
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff819c4751)
Location: include/linux/spinlock.h:341
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
In net/xfrm/xfrm_input.c (ffffffff819ca9a5)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo
  - net/xfrm/xfrm_input.c:xfrm_input_register_afinfo
```
```
In net/xfrm/xfrm_output.c (ffffffff819ccc94)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/af_inet6.c (ffffffff819d48a4)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_register_protosw
```
```
In net/ipv6/addrconf.c (ffffffff819e75d5)
Location: include/linux/spinlock.h:341
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
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/route.c (ffffffff819eab21)
Location: include/linux/spinlock.h:341
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
In net/ipv6/ip6_fib.c (ffffffff819f3fae)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:__fib6_clean_all
  - net/ipv6/ip6_fib.c:fib6_update_sernum_stub
  - net/ipv6/ip6_fib.c:fib6_tables_dump
```
```
In net/ipv6/raw.c (ffffffff81a02dea)
Location: include/linux/spinlock.h:341
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff81a0720b)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mcf_seq_next
  - net/ipv6/mcast.c:igmp6_mcf_seq_start
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:ip6_mc_add_src
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
In net/ipv6/ip6_flowlabel.c (ffffffff81a15545)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
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
In net/ipv6/ip6mr.c (ffffffff81a1a468)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
```
```
In net/ipv6/calipso.c (ffffffff81a21b57)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_cache_invalidate
```
```
In net/packet/af_packet.c (ffffffff81a2e243)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_getsockopt
```
```
In net/dcb/dcbnl.c (ffffffff81a3c862)
Location: include/linux/spinlock.h:341
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
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
```
```
In net/switchdev/switchdev.c (ffffffff81a410dd)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_deferred_process
```
```
In net/xdp/xsk.c (ffffffff81a4a5cc)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xsk.c:xsk_generic_rcv
```
```
In lib/xarray.c (ffffffff81a5cd9d)
Location: include/linux/spinlock.h:341
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
In kernel/cgroup/cgroup.c (ffffffff8114a0b5)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_idr_remove
  - kernel/cgroup/cgroup.c:cgroup_idr_replace
```
```
In kernel/bpf/core.c (ffffffff811c89e4)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
```
```
In kernel/bpf/syscall.c (ffffffff811cd2ff)
Location: include/linux/spinlock.h:341
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
In kernel/bpf/local_storage.c (ffffffff811e4e2a)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_unlink
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_link
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_release
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_assign
  - kernel/bpf/local_storage.c:cgroup_storage_get_next_key
  - kernel/bpf/local_storage.c:cgroup_storage_lookup
```
```
In kernel/bpf/btf.c (ffffffff811e99f3)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
```
```
In kernel/bpf/xskmap.c (ffffffff811ec9c5)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - kernel/bpf/xskmap.c:xsk_map_try_sock_delete
  - kernel/bpf/xskmap.c:xsk_map_delete_elem
  - kernel/bpf/xskmap.c:xsk_map_update_elem
  - kernel/bpf/xskmap.c:xsk_map_update_elem
  - kernel/bpf/xskmap.c:xsk_map_sock_delete
```
```
In kernel/bpf/reuseport_array.c (ffffffff811f2043)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem
  - kernel/bpf/reuseport_array.c:reuseport_array_delete_elem
```
```
In mm/page-writeback.c (ffffffff81216d6f)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - mm/page-writeback.c:bdi_set_max_ratio
  - mm/page-writeback.c:bdi_set_min_ratio
```
```
In mm/backing-dev.c (ffffffff81234b4d)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:bdi_get_by_id
  - mm/backing-dev.c:wb_wakeup_delayed
```
```
In fs/fs-writeback.c (ffffffff812fe1ce)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_queue_work
  - fs/fs-writeback.c:wb_wakeup
```
```
In security/selinux/netif.c (ffffffff814528d6)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_netdev_notifier_handler
  - security/selinux/netif.c:sel_netif_flush
  - security/selinux/netif.c:sel_netif_sid
```
```
In security/selinux/netnode.c (ffffffff81452ea5)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_flush
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (ffffffff81453155)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_flush
  - security/selinux/netport.c:sel_netport_sid
```
```
In block/genhd.c (ffffffff814e19cf)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - block/genhd.c:get_gendisk
```
```
In block/blk-cgroup.c (ffffffff814f38de)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - block/blk-cgroup.c:__blkcg_punt_bio_submit
  - block/blk-cgroup.c:blkg_async_bio_workfn
```
```
In drivers/connector/cn_queue.c (ffffffff81697985)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_free_dev
  - drivers/connector/cn_queue.c:cn_queue_del_callback
  - drivers/connector/cn_queue.c:cn_queue_add_callback
```
```
In drivers/connector/connector.c (ffffffff81697acf)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_proc_show
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/net/tun.c (ffffffff81765010)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_set_ebpf
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_flow_update
  - drivers/net/tun.c:tun_flow_flush
```
```
In drivers/net/vxlan.c (ffffffff8176f76e)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - drivers/net/vxlan.c:vxlan_switchdev_event
  - drivers/net/vxlan.c:vxlan_switchdev_event
  - drivers/net/vxlan.c:vxlan_fdb_offloaded_set
  - drivers/net/vxlan.c:vxlan_changelink
  - drivers/net/vxlan.c:vxlan_flush
  - drivers/net/vxlan.c:vxlan_uninit
  - drivers/net/vxlan.c:vxlan_fdb_delete
  - drivers/net/vxlan.c:vxlan_fdb_add
  - drivers/net/vxlan.c:vxlan_fdb_replay
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81774b85)
Location: include/linux/spinlock.h:341
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
  - drivers/net/ppp/ppp_generic.c:ppp_poll
  - drivers/net/ppp/ppp_generic.c:ppp_read
```
```
In net/core/sock.c (ffffffff8186eef5)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/sock.c:release_sock
  - net/core/sock.c:lock_sock_nested
  - net/core/sock.c:__sk_flush_backlog
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__lock_sock
```
```
In net/core/request_sock.c (ffffffff81870d55)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/core/datagram.c (ffffffff8187b15d)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/datagram.c:__sk_queue_drop_skb
```
```
In net/core/gen_stats.c (ffffffff8187d7c2)
Location: include/linux/spinlock.h:341
Inline: True
```
```
In net/core/gen_estimator.c (ffffffff8187e015)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/net_namespace.c (ffffffff8187f62a)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:peernet2id
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/dev.c (ffffffff81890f85)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/dev.c:dev_set_rx_mode
  - net/core/dev.c:netif_set_real_num_tx_queues
```
```
In net/core/dev_addr_lists.c (ffffffff81899935)
Location: include/linux/spinlock.h:341
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
In net/core/neighbour.c (ffffffff818a0597)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/core/rtnetlink.c (ffffffff818a685d)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_fdb_dump
```
```
In net/core/sock_reuseport.c (ffffffff818bb607)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_attach_prog
  - net/core/sock_reuseport.c:reuseport_detach_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_alloc
```
```
In net/core/page_pool.c (ffffffff818c12f5)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
```
```
In net/core/net-procfs.c (ffffffff818c1dab)
Location: include/linux/spinlock.h:341
Inline: True
```
```
In net/core/skmsg.c (ffffffff818c37d5)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_link_pop
```
```
In net/core/sock_map.c (ffffffff818d363d)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_unref
```
```
In net/core/devlink.c (ffffffff818dc8c5)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_port_type_set
  - net/core/devlink.c:devlink_nl_port_fill
```
```
In net/sched/sch_generic.c (ffffffff818e81e2)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_graft_qdisc
```
```
In net/sched/sch_mq.c (ffffffff818e88f1)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump
```
```
In net/sched/sch_api.c (ffffffff818ea519)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/sched/sch_api.c:tcf_node_bind
  - net/sched/sch_api.c:qdisc_class_hash_grow
```
```
In net/ipv4/route.c (ffffffff81903f58)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_flush_dev
  - net/ipv4/route.c:ipv4_dst_destroy
  - net/ipv4/route.c:rt_add_uncached_list
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/inetpeer.c (ffffffff81907016)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/inet_hashtables.c (ffffffff819134b8)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_unhash
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81915546)
Location: include/linux/spinlock.h:341
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
In net/ipv4/tcp_ipv4.c (ffffffff81931c83)
Location: include/linux/spinlock.h:341
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff819381ab)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_flush_all
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/raw.c (ffffffff8193c56a)
Location: include/linux/spinlock.h:341
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819414a2)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/af_inet.c (ffffffff8194d1c3)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_register_protosw
```
```
In net/ipv4/igmp.c (ffffffff819507fc)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
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
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:igmp_stop_timer
```
```
In net/ipv4/fib_semantics.c (ffffffff819594ed)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_release_info
```
```
In net/ipv4/inet_fragment.c (ffffffff8195f339)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frags_free_cb
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff819696f0)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
```
In net/ipv4/ipmr.c (ffffffff8196e7f5)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
```
```
In net/ipv4/ipmr_base.c (ffffffff81970cb7)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_table_dump
  - net/ipv4/ipmr_base.c:mr_mfc_seq_next
```
```
In net/ipv4/tcp_bpf.c (ffffffff819750d1)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_init
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81975b91)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_invalidate
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197d52b)
Location: include/linux/spinlock.h:341
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
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff81981541)
Location: include/linux/spinlock.h:341
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
In net/xfrm/xfrm_input.c (ffffffff81987795)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo
  - net/xfrm/xfrm_input.c:xfrm_input_register_afinfo
```
```
In net/xfrm/xfrm_output.c (ffffffff81989a84)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/af_inet6.c (ffffffff81991664)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_register_protosw
```
```
In net/ipv6/addrconf.c (ffffffff819a4395)
Location: include/linux/spinlock.h:341
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
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/route.c (ffffffff819a78e1)
Location: include/linux/spinlock.h:341
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
In net/ipv6/ip6_fib.c (ffffffff819b0d6e)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:__fib6_clean_all
  - net/ipv6/ip6_fib.c:fib6_update_sernum_stub
  - net/ipv6/ip6_fib.c:fib6_tables_dump
```
```
In net/ipv6/raw.c (ffffffff819bfbaa)
Location: include/linux/spinlock.h:341
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff819c3fcb)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mcf_seq_next
  - net/ipv6/mcast.c:igmp6_mcf_seq_start
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:ip6_mc_add_src
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
In net/ipv6/ip6_flowlabel.c (ffffffff819d2305)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
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
In net/ipv6/ip6mr.c (ffffffff819d7228)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
```
```
In net/ipv6/calipso.c (ffffffff819de917)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_cache_invalidate
```
```
In net/packet/af_packet.c (ffffffff819eb433)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_getsockopt
```
```
In net/dcb/dcbnl.c (ffffffff819f9452)
Location: include/linux/spinlock.h:341
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
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
```
```
In net/switchdev/switchdev.c (ffffffff819fdccd)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_deferred_process
```
```
In net/xdp/xsk.c (ffffffff81a071bc)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xsk.c:xsk_generic_rcv
```
```
In lib/xarray.c (ffffffff81a19e7d)
Location: include/linux/spinlock.h:341
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
In kernel/cgroup/cgroup.c (ffffffff81154b65)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_idr_remove
  - kernel/cgroup/cgroup.c:cgroup_idr_replace
```
```
In kernel/bpf/core.c (ffffffff811d39f4)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
```
```
In kernel/bpf/syscall.c (ffffffff811d830f)
Location: include/linux/spinlock.h:341
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
In kernel/bpf/local_storage.c (ffffffff811efeaa)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_unlink
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_link
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_release
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_assign
  - kernel/bpf/local_storage.c:cgroup_storage_get_next_key
  - kernel/bpf/local_storage.c:cgroup_storage_lookup
```
```
In kernel/bpf/btf.c (ffffffff811f4a73)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
```
```
In kernel/bpf/xskmap.c (ffffffff811f7a45)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - kernel/bpf/xskmap.c:xsk_map_try_sock_delete
  - kernel/bpf/xskmap.c:xsk_map_delete_elem
  - kernel/bpf/xskmap.c:xsk_map_update_elem
  - kernel/bpf/xskmap.c:xsk_map_update_elem
  - kernel/bpf/xskmap.c:xsk_map_sock_delete
```
```
In kernel/bpf/reuseport_array.c (ffffffff811fd0c3)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem
  - kernel/bpf/reuseport_array.c:reuseport_array_delete_elem
```
```
In mm/page-writeback.c (ffffffff8122195f)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - mm/page-writeback.c:bdi_set_max_ratio
  - mm/page-writeback.c:bdi_set_min_ratio
```
```
In mm/backing-dev.c (ffffffff8123f8fd)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:bdi_get_by_id
  - mm/backing-dev.c:wb_wakeup_delayed
```
```
In fs/fs-writeback.c (ffffffff8130b3ae)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_queue_work
  - fs/fs-writeback.c:wb_wakeup
```
```
In security/selinux/netif.c (ffffffff8145df46)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_netdev_notifier_handler
  - security/selinux/netif.c:sel_netif_flush
  - security/selinux/netif.c:sel_netif_sid
```
```
In security/selinux/netnode.c (ffffffff8145e515)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_flush
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (ffffffff8145e7c5)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_flush
  - security/selinux/netport.c:sel_netport_sid
```
```
In block/genhd.c (ffffffff814ed51f)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - block/genhd.c:get_gendisk
```
```
In block/blk-cgroup.c (ffffffff814ff4ae)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - block/blk-cgroup.c:__blkcg_punt_bio_submit
  - block/blk-cgroup.c:blkg_async_bio_workfn
```
```
In drivers/connector/cn_queue.c (ffffffff816e8215)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_free_dev
  - drivers/connector/cn_queue.c:cn_queue_del_callback
  - drivers/connector/cn_queue.c:cn_queue_add_callback
```
```
In drivers/connector/connector.c (ffffffff816e835f)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_proc_show
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/net/tun.c (ffffffff817b5a70)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_set_ebpf
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_flow_update
  - drivers/net/tun.c:tun_flow_flush
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817bc155)
Location: include/linux/spinlock.h:341
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
  - drivers/net/ppp/ppp_generic.c:ppp_poll
  - drivers/net/ppp/ppp_generic.c:ppp_read
```
```
In drivers/net/xen-netfront.c (ffffffff817c4acf)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:netback_changed
```
```
In net/core/sock.c (ffffffff81905fa5)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/sock.c:release_sock
  - net/core/sock.c:lock_sock_nested
  - net/core/sock.c:__sk_flush_backlog
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__lock_sock
```
```
In net/core/request_sock.c (ffffffff81907e05)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/core/datagram.c (ffffffff8191221d)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/datagram.c:__sk_queue_drop_skb
```
```
In net/core/gen_stats.c (ffffffff81914882)
Location: include/linux/spinlock.h:341
Inline: True
```
```
In net/core/gen_estimator.c (ffffffff819150d5)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/net_namespace.c (ffffffff819166ea)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:peernet2id
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/dev.c (ffffffff81928175)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/dev.c:dev_set_rx_mode
  - net/core/dev.c:netif_set_real_num_tx_queues
```
```
In net/core/dev_addr_lists.c (ffffffff81930b25)
Location: include/linux/spinlock.h:341
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
In net/core/neighbour.c (ffffffff81937787)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/core/rtnetlink.c (ffffffff8193da4d)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_fdb_dump
```
```
In net/core/sock_reuseport.c (ffffffff81952807)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_attach_prog
  - net/core/sock_reuseport.c:reuseport_detach_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_alloc
```
```
In net/core/page_pool.c (ffffffff81958515)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
```
```
In net/core/net-procfs.c (ffffffff81958fcb)
Location: include/linux/spinlock.h:341
Inline: True
```
```
In net/core/skmsg.c (ffffffff8195a9f5)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_link_pop
```
```
In net/core/sock_map.c (ffffffff8196aa1d)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_unref
```
```
In net/core/devlink.c (ffffffff81973ca5)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_port_type_set
  - net/core/devlink.c:devlink_nl_port_fill
```
```
In net/sched/sch_generic.c (ffffffff8197f872)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_graft_qdisc
```
```
In net/sched/sch_mq.c (ffffffff8197ff81)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump
```
```
In net/sched/sch_api.c (ffffffff81981ba9)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/sched/sch_api.c:tcf_node_bind
  - net/sched/sch_api.c:qdisc_class_hash_grow
```
```
In net/netfilter/nfnetlink_queue.c (ffffffff8199ae2e)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/netfilter/nfnetlink_queue.c:nfqnl_recv_config
  - net/netfilter/nfnetlink_queue.c:nfqnl_recv_config
  - net/netfilter/nfnetlink_queue.c:nfqnl_recv_config
  - net/netfilter/nfnetlink_queue.c:nfqnl_recv_verdict
  - net/netfilter/nfnetlink_queue.c:nfqnl_recv_verdict_batch
  - net/netfilter/nfnetlink_queue.c:__nfqnl_enqueue_packet
  - net/netfilter/nfnetlink_queue.c:nfqnl_flush
```
```
In net/netfilter/nfnetlink_log.c (ffffffff8199b97b)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
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
In net/netfilter/nf_conntrack_core.c (ffffffff8199cf58)
Location: include/linux/spinlock.h:341
Inline: True
```
```
In net/netfilter/nf_conntrack_expect.c (ffffffff819a2385)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_expect.c:nf_ct_expect_iterate_net
  - net/netfilter/nf_conntrack_expect.c:nf_ct_expect_iterate_destroy
  - net/netfilter/nf_conntrack_expect.c:nf_ct_expect_related_report
  - net/netfilter/nf_conntrack_expect.c:nf_ct_unexpect_related
  - net/netfilter/nf_conntrack_expect.c:nf_ct_remove_expectations
  - net/netfilter/nf_conntrack_expect.c:nf_ct_expectation_timed_out
```
```
In net/netfilter/nf_conntrack_helper.c (ffffffff819a30b5)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_helper.c:nf_ct_helper_expectfn_unregister
  - net/netfilter/nf_conntrack_helper.c:nf_ct_helper_expectfn_register
```
```
In net/netfilter/nf_conntrack_proto_tcp.c (ffffffff819a53df)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_proto_tcp.c:nlattr_to_tcp
  - net/netfilter/nf_conntrack_proto_tcp.c:tcp_to_nlattr
  - net/netfilter/nf_conntrack_proto_tcp.c:nf_conntrack_tcp_packet
```
```
In net/netfilter/nf_conntrack_seqadj.c (ffffffff819a8137)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_seqadj.c:nf_ct_seq_adjust
  - net/netfilter/nf_conntrack_seqadj.c:nf_ct_seqadj_set
```
```
In net/netfilter/nf_conntrack_ecache.c (ffffffff819a9057)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_ecache.c:nf_ct_deliver_cached_events
  - net/netfilter/nf_conntrack_ecache.c:nf_conntrack_eventmask_report
```
```
In net/netfilter/nf_conntrack_proto_dccp.c (ffffffff819a99ca)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_proto_dccp.c:nlattr_to_dccp
  - net/netfilter/nf_conntrack_proto_dccp.c:dccp_to_nlattr
  - net/netfilter/nf_conntrack_proto_dccp.c:nf_conntrack_dccp_packet
```
```
In net/netfilter/nf_conntrack_proto_sctp.c (ffffffff819aa7e9)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_proto_sctp.c:nlattr_to_sctp
  - net/netfilter/nf_conntrack_proto_sctp.c:sctp_to_nlattr
  - net/netfilter/nf_conntrack_proto_sctp.c:nf_conntrack_sctp_packet
```
```
In net/netfilter/nf_conntrack_proto_gre.c (ffffffff819ab4d6)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_proto_gre.c:nf_ct_gre_keymap_destroy
  - net/netfilter/nf_conntrack_proto_gre.c:nf_ct_gre_keymap_add
  - net/netfilter/nf_conntrack_proto_gre.c:nf_ct_gre_keymap_flush
```
```
In net/netfilter/nf_conntrack_netlink.c (ffffffff819b1052)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_new_expect
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_del_expect
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_change_seq_adj
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_dump_list
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_dump_ct_seq_adj
```
```
In net/ipv4/route.c (ffffffff819b4c38)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_flush_dev
  - net/ipv4/route.c:ipv4_dst_destroy
  - net/ipv4/route.c:rt_add_uncached_list
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/inetpeer.c (ffffffff819b7cf6)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/inet_hashtables.c (ffffffff819c4198)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_unhash
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819c6226)
Location: include/linux/spinlock.h:341
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
In net/ipv4/tcp_ipv4.c (ffffffff819e2993)
Location: include/linux/spinlock.h:341
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff819e8ebb)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_flush_all
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/raw.c (ffffffff819ed27a)
Location: include/linux/spinlock.h:341
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819f21b2)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/af_inet.c (ffffffff819fdfa3)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_register_protosw
```
```
In net/ipv4/igmp.c (ffffffff81a015dc)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
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
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:igmp_stop_timer
```
```
In net/ipv4/fib_semantics.c (ffffffff81a0a2cd)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_release_info
```
```
In net/ipv4/inet_fragment.c (ffffffff81a10119)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frags_free_cb
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81a17960)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
```
In net/ipv4/ipmr.c (ffffffff81a1ca65)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
```
```
In net/ipv4/ipmr_base.c (ffffffff81a1ef27)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_table_dump
  - net/ipv4/ipmr_base.c:mr_mfc_seq_next
```
```
In net/ipv4/tcp_bpf.c (ffffffff81a22d61)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_init
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81a23821)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_invalidate
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a2b1bb)
Location: include/linux/spinlock.h:341
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
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff81a2f1d1)
Location: include/linux/spinlock.h:341
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
In net/xfrm/xfrm_input.c (ffffffff81a35425)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo
  - net/xfrm/xfrm_input.c:xfrm_input_register_afinfo
```
```
In net/xfrm/xfrm_output.c (ffffffff81a37714)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/af_inet6.c (ffffffff81a3f324)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_register_protosw
```
```
In net/ipv6/addrconf.c (ffffffff81a52055)
Location: include/linux/spinlock.h:341
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
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/route.c (ffffffff81a555a1)
Location: include/linux/spinlock.h:341
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
In net/ipv6/ip6_fib.c (ffffffff81a5ea2e)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:__fib6_clean_all
  - net/ipv6/ip6_fib.c:fib6_update_sernum_stub
  - net/ipv6/ip6_fib.c:fib6_tables_dump
```
```
In net/ipv6/raw.c (ffffffff81a6d86a)
Location: include/linux/spinlock.h:341
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff81a71c8b)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mcf_seq_next
  - net/ipv6/mcast.c:igmp6_mcf_seq_start
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:ip6_mc_add_src
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
In net/ipv6/ip6_flowlabel.c (ffffffff81a7ffc5)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
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
In net/ipv6/ip6mr.c (ffffffff81a84ee8)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
```
```
In net/ipv6/calipso.c (ffffffff81a8c5d7)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_cache_invalidate
```
```
In net/ipv6/netfilter/nf_conntrack_reasm.c (ffffffff81a912ff)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv6/netfilter/nf_conntrack_reasm.c:nf_ct_frag6_gather
```
```
In net/packet/af_packet.c (ffffffff81a99df3)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_getsockopt
```
```
In net/dcb/dcbnl.c (ffffffff81aa8712)
Location: include/linux/spinlock.h:341
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
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
```
```
In net/switchdev/switchdev.c (ffffffff81aacf8d)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_deferred_process
```
```
In net/xdp/xsk.c (ffffffff81ab647c)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xsk.c:xsk_generic_rcv
```
```
In lib/xarray.c (ffffffff81ac918d)
Location: include/linux/spinlock.h:341
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
In kernel/cgroup/cgroup.c (ffffffff81161f45)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_idr_remove
  - kernel/cgroup/cgroup.c:cgroup_idr_replace
```
```
In kernel/bpf/core.c (ffffffff811e1ce4)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
```
```
In kernel/bpf/syscall.c (ffffffff811e66bf)
Location: include/linux/spinlock.h:341
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
In kernel/bpf/local_storage.c (ffffffff811fe3ba)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_unlink
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_link
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_release
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_assign
  - kernel/bpf/local_storage.c:cgroup_storage_get_next_key
  - kernel/bpf/local_storage.c:cgroup_storage_lookup
```
```
In kernel/bpf/btf.c (ffffffff81202f83)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
```
```
In kernel/bpf/xskmap.c (ffffffff81205fc5)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - kernel/bpf/xskmap.c:xsk_map_try_sock_delete
  - kernel/bpf/xskmap.c:xsk_map_delete_elem
  - kernel/bpf/xskmap.c:xsk_map_update_elem
  - kernel/bpf/xskmap.c:xsk_map_update_elem
  - kernel/bpf/xskmap.c:xsk_map_sock_delete
```
```
In kernel/bpf/reuseport_array.c (ffffffff8120bd93)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem
  - kernel/bpf/reuseport_array.c:reuseport_array_delete_elem
```
```
In mm/page-writeback.c (ffffffff81230b1f)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - mm/page-writeback.c:bdi_set_max_ratio
  - mm/page-writeback.c:bdi_set_min_ratio
```
```
In mm/backing-dev.c (ffffffff8124f07d)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:bdi_get_by_id
  - mm/backing-dev.c:wb_wakeup_delayed
```
```
In fs/fs-writeback.c (ffffffff8131cb6e)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_queue_work
  - fs/fs-writeback.c:wb_wakeup
```
```
In security/selinux/netif.c (ffffffff814756eb)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_netdev_notifier_handler
  - security/selinux/netif.c:sel_netif_flush
  - security/selinux/netif.c:sel_netif_sid
```
```
In security/selinux/netnode.c (ffffffff81475cd5)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_flush
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (ffffffff81475fa5)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_flush
  - security/selinux/netport.c:sel_netport_sid
```
```
In block/genhd.c (ffffffff8150672f)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - block/genhd.c:get_gendisk
```
```
In block/blk-cgroup.c (ffffffff8151862e)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - block/blk-cgroup.c:__blkcg_punt_bio_submit
  - block/blk-cgroup.c:blkg_async_bio_workfn
```
```
In drivers/connector/cn_queue.c (ffffffff81702915)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_free_dev
  - drivers/connector/cn_queue.c:cn_queue_del_callback
  - drivers/connector/cn_queue.c:cn_queue_add_callback
```
```
In drivers/connector/connector.c (ffffffff81702a5f)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_proc_show
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/net/tun.c (ffffffff817cfe10)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_set_ebpf
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_flow_update
  - drivers/net/tun.c:tun_flow_flush
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817d6455)
Location: include/linux/spinlock.h:341
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
  - drivers/net/ppp/ppp_generic.c:ppp_poll
  - drivers/net/ppp/ppp_generic.c:ppp_read
```
```
In drivers/net/xen-netfront.c (ffffffff817ded84)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:netback_changed
```
```
In net/core/sock.c (ffffffff81926fd5)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/sock.c:release_sock
  - net/core/sock.c:lock_sock_nested
  - net/core/sock.c:__sk_flush_backlog
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__lock_sock
```
```
In net/core/request_sock.c (ffffffff81928e45)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/core/datagram.c (ffffffff819333bd)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/datagram.c:__sk_queue_drop_skb
```
```
In net/core/gen_stats.c (ffffffff81935a52)
Location: include/linux/spinlock.h:341
Inline: True
```
```
In net/core/gen_estimator.c (ffffffff81936255)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/net_namespace.c (ffffffff819378ea)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:peernet2id
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/dev.c (ffffffff81949845)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/dev.c:dev_set_rx_mode
  - net/core/dev.c:netif_set_real_num_tx_queues
```
```
In net/core/dev_addr_lists.c (ffffffff819521f5)
Location: include/linux/spinlock.h:341
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
In net/core/neighbour.c (ffffffff81958f5e)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
```
```
In net/core/rtnetlink.c (ffffffff8195f2dd)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_fdb_dump
```
```
In net/core/sock_reuseport.c (ffffffff81974277)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_attach_prog
  - net/core/sock_reuseport.c:reuseport_detach_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_alloc
```
```
In net/core/page_pool.c (ffffffff8197a645)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
```
```
In net/core/net-procfs.c (ffffffff8197b13b)
Location: include/linux/spinlock.h:341
Inline: True
```
```
In net/core/skmsg.c (ffffffff8197cc15)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_link_pop
```
```
In net/core/sock_map.c (ffffffff8198ce8d)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_unref
```
```
In net/core/devlink.c (ffffffff81996195)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_port_type_set
  - net/core/devlink.c:devlink_nl_port_fill
```
```
In net/sched/sch_generic.c (ffffffff819a1dce)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_graft_qdisc
```
```
In net/sched/sch_mq.c (ffffffff819a24e1)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump
```
```
In net/sched/sch_api.c (ffffffff819a4109)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/sched/sch_api.c:tcf_node_bind
  - net/sched/sch_api.c:qdisc_class_hash_grow
```
```
In net/ipv4/route.c (ffffffff819be378)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_flush_dev
  - net/ipv4/route.c:ipv4_dst_destroy
  - net/ipv4/route.c:rt_add_uncached_list
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:update_or_create_fnhe
```
```
In net/ipv4/inetpeer.c (ffffffff819c1579)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/inet_hashtables.c (ffffffff819cdc0a)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_unhash
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819cfd0c)
Location: include/linux/spinlock.h:341
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
In net/ipv4/tcp_ipv4.c (ffffffff819ec803)
Location: include/linux/spinlock.h:341
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff819f2c1b)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_flush_all
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/raw.c (ffffffff819f715a)
Location: include/linux/spinlock.h:341
Inline: True
```
```
In net/ipv4/udp.c (ffffffff819f95a2)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/af_inet.c (ffffffff81a08333)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_register_protosw
```
```
In net/ipv4/igmp.c (ffffffff81a0bacc)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
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
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:igmp_stop_timer
```
```
In net/ipv4/fib_semantics.c (ffffffff81a14aad)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_release_info
```
```
In net/ipv4/inet_fragment.c (ffffffff81a1a969)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frags_free_cb
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff81a22400)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
```
In net/ipv4/ipmr.c (ffffffff81a27c96)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
```
```
In net/ipv4/ipmr_base.c (ffffffff81a2a3e7)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_table_dump
  - net/ipv4/ipmr_base.c:mr_mfc_seq_next
```
```
In net/ipv4/tcp_bpf.c (ffffffff81a2e140)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_init
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81a2ec01)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_invalidate
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a367eb)
Location: include/linux/spinlock.h:341
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
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff81a3ab21)
Location: include/linux/spinlock.h:341
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
In net/xfrm/xfrm_input.c (ffffffff81a40d05)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo
  - net/xfrm/xfrm_input.c:xfrm_input_register_afinfo
```
```
In net/xfrm/xfrm_output.c (ffffffff81a430c4)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/af_inet6.c (ffffffff81a4ae24)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_register_protosw
```
```
In net/ipv6/addrconf.c (ffffffff81a5dfa5)
Location: include/linux/spinlock.h:341
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
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/route.c (ffffffff81a615a1)
Location: include/linux/spinlock.h:341
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
In net/ipv6/ip6_fib.c (ffffffff81a6aeae)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:__fib6_clean_all
  - net/ipv6/ip6_fib.c:fib6_update_sernum_stub
  - net/ipv6/ip6_fib.c:fib6_tables_dump
```
```
In net/ipv6/raw.c (ffffffff81a79e8a)
Location: include/linux/spinlock.h:341
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff81a7e2ab)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mcf_seq_next
  - net/ipv6/mcast.c:igmp6_mcf_seq_start
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:ip6_mc_add_src
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
In net/ipv6/ip6_flowlabel.c (ffffffff81a8c975)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
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
In net/ipv6/ip6mr.c (ffffffff81a91ad3)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
```
```
In net/ipv6/calipso.c (ffffffff81a9936a)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_cache_invalidate
```
```
In net/packet/af_packet.c (ffffffff81aa6b20)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_getsockopt
```
```
In net/dcb/dcbnl.c (ffffffff81ab4a82)
Location: include/linux/spinlock.h:341
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
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
```
```
In net/switchdev/switchdev.c (ffffffff81ab92fd)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_deferred_process
```
```
In net/xdp/xsk.c (ffffffff81ac259c)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xsk.c:xsk_generic_rcv
```
```
In lib/xarray.c (ffffffff81ad566e)
Location: include/linux/spinlock.h:341
Inline: True
Inline callers:
  - lib/xarray.c:__xas_nomem
```
</details>
</li>
</ul>

## Differences
