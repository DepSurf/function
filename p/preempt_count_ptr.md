# Function: <code>preempt_count_ptr</code>

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
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/main.c (c03036d0)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - init/main.c:do_one_initcall
```
```
In arch/arm/kernel/traps.c (0)
Location: include/asm-generic/preempt.h:14
Inline: True
```
```
In kernel/exit.c (c035ae74)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/softirq.c (c0302c48)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
```
```
In kernel/sched/core.c (c0e99a00)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
```
In kernel/locking/spinlock.c (c0e9f248)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_lock_bh
  - kernel/locking/spinlock.c:_raw_read_lock_bh
  - kernel/locking/spinlock.c:_raw_spin_trylock_bh
  - kernel/locking/spinlock.c:_raw_spin_lock_bh
```
```
In kernel/irq/manage.c (c03cb14c)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_forced_thread_fn
```
```
In kernel/rcu/update.c (c03d77f4)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/srcutree.c (c03d82ec)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
```
```
In kernel/rcu/tree.c (0)
Location: include/asm-generic/preempt.h:14
Inline: True
```
```
In kernel/time/timer.c (0)
Location: include/asm-generic/preempt.h:14
Inline: True
```
```
In kernel/time/hrtimer.c (c03ec444)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
```
```
In kernel/stop_machine.c (c0428378)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
  - kernel/stop_machine.c:cpu_stopper_thread
```
```
In kernel/bpf/cpumap.c (c04b840c)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In kernel/bpf/offload.c (c04b9878)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In kernel/padata.c (c04d7e00)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:invoke_padata_reorder
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_parallel_worker
```
```
In ipc/util.c (c06d9864)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/smack/smack_lsm.c (c0721490)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_netlabel
```
```
In security/apparmor/policy_unpack.c (c0749bb0)
Location: include/asm-generic/preempt.h:14
Inline: True
```
```
In lib/rhashtable.c (c07dc870)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In drivers/irqchip/irq-gic-v3.c (0)
Location: include/asm-generic/preempt.h:14
Inline: True
```
```
In drivers/net/tun.c (c0ac6cf0)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ethernet/freescale/fec_main.c (c0accb64)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_resume
  - drivers/net/ethernet/freescale/fec_main.c:fec_suspend
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_close
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_set_pauseparam
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_adjust_link
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_adjust_link
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_timeout_work
```
```
In drivers/net/ppp/ppp_generic.c (c0adf264)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
```
```
In net/core/skbuff.c (c0cd21b0)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:netdev_alloc_frag
```
```
In net/core/gen_estimator.c (c0cdb39c)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/dev.c (c0cee974)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:flush_backlog
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/neighbour.c (c0cfc64c)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_seq_start
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_for_each
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/xdp.c (c0d1f928)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (c0d2170c)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/sched/sch_generic.c (c0d4c2ac)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
```
```
In net/netlink/af_netlink.c (c0d5f2ac)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/netfilter/nf_log.c (c0d65380)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/netfilter/nf_log.c:nf_log_buf_open
```
```
In net/netfilter/nf_queue.c (c0d65b48)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_reinject
```
```
In net/ipv4/route.c (c0d66bb4)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:ip_error
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_input.c (c0d6dab8)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_rcv_core
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_fragment.c (c0d6f50c)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv4/ip_fragment.c:ip_expire
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_forward.c (c0d6fcf0)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward_finish
```
```
In net/ipv4/ip_output.c (c0d75358)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_skb
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_output
  - net/ipv4/ip_output.c:ip_mc_output
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_hashtables.c (c0d78b94)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (c0d7adb0)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/inet_connection_sock.c (c0d7bfe0)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/tcp.c (c0d83f88)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (c0d901a8)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
```
In net/ipv4/tcp_ipv4.c (c0d9be7c)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/tcp_minisocks.c (c0d9e3fc)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/datagram.c (c0da4838)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (c0da5ba8)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/udp.c (c0da93cc)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/icmp.c (c0db0be4)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/fib_frontend.c (c0dbf378)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
```
```
In net/ipv4/fib_semantics.c (c0dc567c)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/inet_fragment.c (c0dcade0)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ping.c (c0dcccd8)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/nexthop.c (c0dd09a4)
Location: include/asm-generic/preempt.h:14
Inline: True
```
```
In net/ipv4/ipmr.c (c0dd74b4)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_delete
```
```
In net/xfrm/xfrm_policy.c (c0de7a4c)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/unix/af_unix.c (c0df79a8)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/ipv6/ip6_output.c (c0dfe7a0)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (c0e04540)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
  - net/ipv6/ip6_input.c:ip6_rcv_core
```
```
In net/ipv6/addrconf.c (c0e08e58)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (c0e1a484)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ip6_fib.c (c0e1ee94)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_start
```
```
In net/ipv6/ipv6_sockglue.c (c0e246d0)
Location: include/asm-generic/preempt.h:14
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/asm-generic/preempt.h:14
Inline: True
```
```
In net/ipv6/icmp.c (c0e304c8)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (c0e33b00)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
```
```
In net/ipv6/reassembly.c (c0e37754)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_queue
  - net/ipv6/reassembly.c:ip6_frag_queue
  - net/ipv6/reassembly.c:ip6_frag_expire
  - net/ipv6/reassembly.c:ip6_frag_expire
```
```
In net/ipv6/exthdrs.c (c0e3f11c)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
```
In net/ipv6/ip6_flowlabel.c (c0e4182c)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In net/ipv6/ip6mr.c (c0e47000)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/netfilter.c (0)
Location: include/asm-generic/preempt.h:14
Inline: True
```
```
In net/ipv6/seg6_hmac.c (c0e52f18)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
```
```
In net/ipv6/inet6_hashtables.c (c0e55960)
Location: include/asm-generic/preempt.h:14
Inline: True
```
```
In net/xdp/xsk.c (c0e79134)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
  - net/xdp/xsk.c:xsk_release
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
In init/main.c (c000000000010198)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - init/main.c:do_one_initcall
```
```
In arch/powerpc/kernel/traps.c (c00000000002e570)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - arch/powerpc/kernel/traps.c:machine_check_exception
  - arch/powerpc/kernel/traps.c:machine_check_exception
  - arch/powerpc/kernel/traps.c:machine_check_exception
  - arch/powerpc/kernel/traps.c:system_reset_exception
  - arch/powerpc/kernel/traps.c:system_reset_exception
```
```
In arch/powerpc/kernel/watchdog.c (c000000000037ad4)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - arch/powerpc/kernel/watchdog.c:soft_nmi_interrupt
  - arch/powerpc/kernel/watchdog.c:soft_nmi_interrupt
```
```
In arch/powerpc/perf/core-book3s.c (c00000000012932c)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - arch/powerpc/perf/core-book3s.c:perf_event_interrupt
  - arch/powerpc/perf/core-book3s.c:perf_event_interrupt
```
```
In kernel/exit.c (c000000000144cac)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/softirq.c (c00000000014648c)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:irq_enter
  - kernel/softirq.c:irq_enter
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:_local_bh_enable
```
```
In kernel/sched/core.c (c000000000ee2b98)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:finish_task_switch
```
```
In kernel/locking/spinlock.c (c000000000eea3c0)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_lock_bh
  - kernel/locking/spinlock.c:_raw_read_lock_bh
  - kernel/locking/spinlock.c:_raw_spin_trylock_bh
  - kernel/locking/spinlock.c:_raw_spin_lock_bh
```
```
In kernel/irq/manage.c (c0000000001d4588)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_forced_thread_fn
```
```
In kernel/rcu/update.c (c0000000001e31ec)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/srcutree.c (c0000000001e5970)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
```
```
In kernel/rcu/tree.c (c0000000001eb7d4)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_cpu_kthread
```
```
In kernel/time/timer.c (c0000000001fe3dc)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - kernel/time/timer.c:call_timer_fn
```
```
In kernel/time/hrtimer.c (c000000000203cf8)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
```
```
In kernel/stop_machine.c (c000000000258c80)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
  - kernel/stop_machine.c:cpu_stopper_thread
```
```
In kernel/bpf/cpumap.c (c0000000003337d4)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In kernel/bpf/offload.c (c0000000003355b8)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In kernel/padata.c (c00000000035cd0c)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:invoke_padata_reorder
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_parallel_worker
```
```
In ipc/util.c (c0000000006665f0)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/smack/smack_lsm.c (c0000000006d340c)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_netlabel
```
```
In security/apparmor/policy_unpack.c (c00000000070f900)
Location: include/asm-generic/preempt.h:14
Inline: True
```
```
In lib/rhashtable.c (c0000000007dca38)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In drivers/net/tun.c (c000000000aa3060)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (c000000000aaaaf0)
Location: include/asm-generic/preempt.h:14
Inline: True
```
```
In net/core/skbuff.c (c000000000c8c080)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:netdev_alloc_frag
```
```
In net/core/gen_estimator.c (c000000000c98cb4)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/dev.c (c000000000cb29d4)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:flush_backlog
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/neighbour.c (c000000000cc3a74)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_seq_start
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_for_each
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/xdp.c (c000000000cf0d08)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_allocator_disconnect
```
```
In net/core/flow_offload.c (c000000000cf2c64)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/sched/sch_generic.c (c000000000d33084)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
```
```
In net/netlink/af_netlink.c (c000000000d4d888)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/netfilter/nf_log.c (c000000000d557f0)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/netfilter/nf_log.c:nf_log_buf_open
```
```
In net/netfilter/nf_queue.c (c000000000d56968)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_reinject
```
```
In net/ipv4/route.c (c000000000d5b2f0)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (c000000000d668b0)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_hashtables.c (c000000000d6e89c)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (c000000000d715bc)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/inet_connection_sock.c (c000000000d72ec4)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/tcp.c (c000000000d7d0b4)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (c000000000d8bdec)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
```
In net/ipv4/tcp_ipv4.c (c000000000d9aa4c)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/tcp_minisocks.c (c000000000d9e1b8)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/icmp.c (c000000000db7e1c)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/fib_frontend.c (c000000000dca94c)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_lookup
```
```
In net/ipv4/fib_semantics.c (c000000000dd2e48)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/inet_fragment.c (c000000000dda0e0)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/nexthop.c (c000000000de1250)
Location: include/asm-generic/preempt.h:14
Inline: True
```
```
In net/ipv4/ipmr.c (c000000000deb428)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (c000000000dfcd1c)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/unix/af_unix.c (c000000000e148a4)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/ipv6/ip6_output.c (c000000000e1f2ac)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/addrconf.c (c000000000e2b23c)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (c000000000e4155c)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ip6_fib.c (c000000000e46ef8)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_start
```
```
In net/ipv6/ipv6_sockglue.c (c000000000e4dcfc)
Location: include/asm-generic/preempt.h:14
Inline: True
```
```
In net/ipv6/icmp.c (c000000000e5deb4)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ip6_flowlabel.c (c000000000e72cb4)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In net/ipv6/ip6mr.c (c000000000e79650)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (c000000000e8aa3c)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
```
```
In net/ipv6/inet6_hashtables.c (c000000000e8e1a8)
Location: include/asm-generic/preempt.h:14
Inline: True
```
```
In net/xdp/xsk.c (c000000000ebe74c)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
  - net/xdp/xsk.c:xsk_release
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
In init/main.c (ffffffe0000b437e)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - init/main.c:do_one_initcall
```
```
In kernel/exit.c (ffffffe0000c637a)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/softirq.c (ffffffe0000c7096)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:irq_enter
  - kernel/softirq.c:irq_enter
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:_local_bh_enable
```
```
In kernel/sched/core.c (ffffffe0008c511c)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:finish_task_switch
```
```
In kernel/locking/spinlock.c (ffffffe0008c96a0)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_lock_bh
  - kernel/locking/spinlock.c:_raw_read_lock_bh
  - kernel/locking/spinlock.c:_raw_spin_trylock_bh
  - kernel/locking/spinlock.c:_raw_spin_lock_bh
```
```
In kernel/rcu/update.c (ffffffe00011e290)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/srcutree.c (ffffffe00011fc2a)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
```
```
In kernel/rcu/tree.c (ffffffe000122ffe)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_cpu_kthread
```
```
In kernel/time/timer.c (ffffffe00012c012)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - kernel/time/timer.c:call_timer_fn
```
```
In kernel/stop_machine.c (ffffffe00015d39a)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
  - kernel/stop_machine.c:cpu_stopper_thread
```
```
In kernel/bpf/cpumap.c (ffffffe0001bce16)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In kernel/bpf/offload.c (ffffffe0001be35a)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In kernel/padata.c (ffffffe0001d2e46)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:invoke_padata_reorder
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_parallel_worker
```
```
In ipc/util.c (ffffffe000384d74)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/smack/smack_lsm.c (ffffffe0003c25c6)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_netlabel
```
```
In security/apparmor/policy_unpack.c (ffffffe0003e52f8)
Location: include/asm-generic/preempt.h:14
Inline: True
```
```
In lib/rhashtable.c (ffffffe0004640f8)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In drivers/net/tun.c (ffffffe00062aefa)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (ffffffe00062eb9c)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
```
```
In net/core/skbuff.c (ffffffe0007451a4)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:netdev_alloc_frag
```
```
In net/core/gen_estimator.c (ffffffe00074d298)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/dev.c (ffffffe00075dc96)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:flush_backlog
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/neighbour.c (ffffffe000768326)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_seq_start
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_for_each
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/xdp.c (ffffffe000784d0e)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_allocator_disconnect
```
```
In net/core/flow_offload.c (ffffffe00078646c)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/sched/sch_generic.c (ffffffe0007ab25c)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
```
```
In net/netlink/af_netlink.c (ffffffe0007badd6)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/netfilter/nf_log.c (ffffffe0007bf85c)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/netfilter/nf_log.c:nf_log_buf_open
```
```
In net/netfilter/nf_queue.c (ffffffe0007c03d4)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_reinject
```
```
In net/ipv4/route.c (ffffffe0007c3204)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffe0007cabda)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_hashtables.c (ffffffe0007cfcc6)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffe0007d1958)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/inet_connection_sock.c (ffffffe0007d2d9e)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/tcp.c (ffffffe0007d8a92)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffe0007e2ea4)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
```
In net/ipv4/tcp_ipv4.c (ffffffe0007ed54c)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/tcp_minisocks.c (ffffffe0007ef690)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/icmp.c (ffffffe0007ffd88)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/fib_frontend.c (ffffffe00080b776)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_lookup
```
```
In net/ipv4/fib_semantics.c (ffffffe000810800)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/inet_fragment.c (ffffffe00081524a)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/nexthop.c (ffffffe00081a246)
Location: include/asm-generic/preempt.h:14
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffe000820904)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffe00082c0fe)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/unix/af_unix.c (ffffffe00083d270)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/ipv6/ip6_output.c (ffffffe000843cb2)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/addrconf.c (ffffffe00084b1fe)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffe00085a02c)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ip6_fib.c (ffffffe00085dc46)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_start
```
```
In net/ipv6/ipv6_sockglue.c (ffffffe000861b8a)
Location: include/asm-generic/preempt.h:14
Inline: True
```
```
In net/ipv6/icmp.c (ffffffe00086c84e)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ip6_flowlabel.c (ffffffe00087aa94)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In net/ipv6/ip6mr.c (ffffffe00087f584)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffe00088a55e)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
```
```
In net/ipv6/inet6_hashtables.c (ffffffe00088cb76)
Location: include/asm-generic/preempt.h:14
Inline: True
```
```
In net/xdp/xsk.c (ffffffe0008ac140)
Location: include/asm-generic/preempt.h:14
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
  - net/xdp/xsk.c:xsk_release
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
