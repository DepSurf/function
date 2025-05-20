# Function: <code>local_bh_enable</code>

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
In kernel/sched/core.c (ffffffff8182065d)
Location: include/linux/bottom_half.h:29
Inline: True
```
```
In kernel/irq/manage.c (ffffffff810dbb5b)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_forced_thread_fn
```
```
In kernel/rcu/srcu.c (ffffffff810e3f52)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - kernel/rcu/srcu.c:process_srcu
```
```
In kernel/padata.c (ffffffff811899d6)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_parallel_worker
  - kernel/padata.c:padata_serial_worker
```
```
In security/smack/smack_lsm.c (ffffffff8135e4fd)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_netlabel
```
```
In crypto/chainiv.c (ffffffff813a2353)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - crypto/chainiv.c:async_chainiv_do_postponed
```
```
In drivers/net/virtio_net.c (ffffffff815f197b)
Location: include/linux/bottom_half.h:29
Inline: True
```
```
In net/socket.c (ffffffff816fe020)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/socket.c:sock_poll
```
```
In net/core/sock.c (ffffffff81701021)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/core/sock.c:lock_sock_nested
```
```
In net/core/datagram.c (ffffffff8170cd5f)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_recv_datagram
```
```
In net/core/dev.c (ffffffff8171cfb5)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/dst.c (ffffffff8172388a)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/core/dst.c:dst_init
  - net/core/dst.c:dst_destroy
```
```
In net/core/neighbour.c (ffffffff817244d8)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_for_each
  - net/core/neighbour.c:neigh_seq_stop
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_lookup
  - net/core/neighbour.c:neigh_dump_info
```
```
In net/core/flow.c (ffffffff8173496e)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_lookup
  - net/core/flow.c:flow_cache_flush
```
```
In net/sched/sch_generic.c (ffffffff81741d1f)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
```
```
In net/netlink/af_netlink.c (ffffffff8174b727)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/netfilter/nf_log.c (ffffffff817525b8)
Location: include/linux/bottom_half.h:29
Inline: True
```
```
In net/netfilter/nf_queue.c (ffffffff81752a2c)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_reinject
```
```
In net/ipv4/route.c (ffffffff8175416f)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_cpu_seq_show
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/ip_fragment.c (ffffffff8175a699)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_mem
```
```
In net/ipv4/ip_output.c (ffffffff8175d118)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_hashtables.c (ffffffff81762488)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_put_port
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff817638d2)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81763e47)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/tcp.c (ffffffff81765952)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_init_sock
  - net/ipv4/tcp.c:tcp_prequeue_process
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff81770747)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8177ac40)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
```
```
In net/ipv4/icmp.c (ffffffff8178e895)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_send
```
```
In net/ipv4/fib_frontend.c (ffffffff8179a1a5)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
```
```
In net/ipv4/inet_fragment.c (ffffffff817a1b75)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_worker
  - net/ipv4/inet_fragment.c:inet_frags_exit_net
```
```
In net/ipv4/proc.c (ffffffff817a5fb6)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/ipv4/proc.c:sockstat_seq_show
```
```
In net/ipv4/xfrm4_policy.c (ffffffff817af434)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_garbage_collect
```
```
In net/unix/af_unix.c (ffffffff817be0b3)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/ipv6/ip6_output.c (ffffffff817c52aa)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/addrconf.c (ffffffff817c941a)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:if6_seq_stop
  - net/ipv6/addrconf.c:ipv6_regen_rndid
  - net/ipv6/addrconf.c:ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
```
```
In net/ipv6/route.c (ffffffff817d3ee2)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_dst_gc
  - net/ipv6/route.c:rt6_stats_seq_show
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ip6_fib.c (ffffffff817d9d38)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_stop
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff817dde17)
Location: include/linux/bottom_half.h:29
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff817e7f5f)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_echo_reply
```
```
In net/ipv6/tcp_ipv6.c (ffffffff817eed81)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff817f5e16)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_stop
  - net/ipv6/ip6_flowlabel.c:fl_lookup
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
```
```
In net/ipv6/proc.c (ffffffff817feaf5)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/ipv6/proc.c:sockstat6_seq_show
```
```
In net/ipv6/inet6_hashtables.c (ffffffff818022c1)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup
```
```
In net/packet/af_packet.c (ffffffff818037e2)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_direct_xmit
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
In kernel/sched/core.c (ffffffff8189aabe)
Location: include/linux/bottom_half.h:29
Inline: True
```
```
In kernel/irq/manage.c (ffffffff810e0e9b)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_forced_thread_fn
```
```
In kernel/rcu/update.c (ffffffff810e968d)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/srcu.c (ffffffff810ea23b)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - kernel/rcu/srcu.c:process_srcu
```
```
In kernel/padata.c (ffffffff8119c272)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_parallel_worker
```
```
In security/smack/smack_lsm.c (ffffffff8139463e)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_netlabel
```
```
In drivers/net/virtio_net.c (ffffffff8165128b)
Location: include/linux/bottom_half.h:29
Inline: True
```
```
In net/core/sock.c (ffffffff81767ba6)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/core/sock.c:lock_sock_nested
```
```
In net/core/dev.c (ffffffff8178341a)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/core/dev.c:sk_busy_loop
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/dst.c (ffffffff8178d9ae)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/core/dst.c:dst_destroy
  - net/core/dst.c:dst_init
```
```
In net/core/neighbour.c (ffffffff8178ded6)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_seq_stop
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_for_each
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/flow.c (ffffffff817a1465)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_flush
  - net/core/flow.c:flow_cache_lookup
```
```
In net/sched/sch_generic.c (ffffffff817aebd3)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
```
```
In net/netlink/af_netlink.c (ffffffff817ba23e)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_create
```
```
In net/netfilter/nf_log.c (ffffffff817be6c8)
Location: include/linux/bottom_half.h:29
Inline: True
```
```
In net/netfilter/nf_queue.c (ffffffff817beb3c)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_reinject
```
```
In net/ipv4/route.c (ffffffff817c367c)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:rt_cpu_seq_show
```
```
In net/ipv4/ip_fragment.c (ffffffff817c6a59)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_mem
```
```
In net/ipv4/ip_output.c (ffffffff817c9ed8)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_hashtables.c (ffffffff817cf441)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff817cfd08)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/inet_connection_sock.c (ffffffff817d1224)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
```
```
In net/ipv4/tcp.c (ffffffff817d6e5b)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_ipv4.c (ffffffff817ea486)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/icmp.c (ffffffff817fbed9)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_send
```
```
In net/ipv4/fib_frontend.c (ffffffff81808082)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
```
```
In net/ipv4/fib_semantics.c (ffffffff8180c033)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/inet_fragment.c (ffffffff8180fa81)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frags_exit_net
  - net/ipv4/inet_fragment.c:inet_frag_worker
```
```
In net/ipv4/proc.c (ffffffff81813c51)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/ipv4/proc.c:sockstat_seq_show
```
```
In net/ipv4/xfrm4_policy.c (ffffffff8181c334)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_garbage_collect
```
```
In net/unix/af_unix.c (ffffffff8182b047)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/ipv6/ip6_output.c (ffffffff81831e9a)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/addrconf.c (ffffffff818390da)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:if6_seq_stop
  - net/ipv6/addrconf.c:ipv6_regen_rndid
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
```
```
In net/ipv6/route.c (ffffffff81842ea7)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_stats_seq_show
  - net/ipv6/route.c:ip6_dst_gc
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ip6_fib.c (ffffffff81847e9b)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_stop
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff8184be9e)
Location: include/linux/bottom_half.h:29
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff81856aff)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8185d96d)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81864f16)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_stop
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In net/ipv6/proc.c (ffffffff8186e485)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/ipv6/proc.c:sockstat6_seq_show
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81872f8a)
Location: include/linux/bottom_half.h:29
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81874a22)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_direct_xmit
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
In kernel/sched/core.c (ffffffff818cf0ae)
Location: include/linux/bottom_half.h:29
Inline: True
```
```
In kernel/irq/manage.c (ffffffff810e7de8)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_forced_thread_fn
```
```
In kernel/rcu/update.c (ffffffff810f054c)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/srcu.c (ffffffff810f111b)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - kernel/rcu/srcu.c:process_srcu
```
```
In kernel/padata.c (ffffffff811abae2)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_parallel_worker
```
```
In security/smack/smack_lsm.c (ffffffff813ab17e)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_netlabel
```
```
In drivers/net/tun.c (ffffffff8167f9c5)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81685d54)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_channel_push
```
```
In net/core/sock.c (ffffffff81794bc6)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/core/sock.c:lock_sock_nested
```
```
In net/core/dev.c (ffffffff817aecfe)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/core/dev.c:sk_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:flush_backlog
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/dst.c (ffffffff817bb27e)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/core/dst.c:dst_destroy
  - net/core/dst.c:dst_init
```
```
In net/core/neighbour.c (ffffffff817bb886)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_seq_stop
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_for_each
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/flow.c (ffffffff817cfd82)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_flush
  - net/core/flow.c:flow_cache_lookup
```
```
In net/sched/sch_generic.c (ffffffff817de253)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
```
```
In net/netlink/af_netlink.c (ffffffff817e9c5c)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_create
```
```
In net/netfilter/nf_log.c (ffffffff817edf98)
Location: include/linux/bottom_half.h:29
Inline: True
```
```
In net/netfilter/nf_queue.c (ffffffff817ee484)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_reinject
```
```
In net/ipv4/route.c (ffffffff817f2c9f)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:rt_cpu_seq_show
```
```
In net/ipv4/ip_fragment.c (ffffffff817f6559)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_mem
```
```
In net/ipv4/ip_output.c (ffffffff817f91d2)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_hashtables.c (ffffffff817ff231)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff817ffaf8)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/inet_connection_sock.c (ffffffff818010e4)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
```
```
In net/ipv4/tcp.c (ffffffff81806e7b)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_input.c (ffffffff818109a5)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81818c7e)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/icmp.c (ffffffff8182ce29)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_send
```
```
In net/ipv4/fib_frontend.c (ffffffff81839152)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
```
```
In net/ipv4/fib_semantics.c (ffffffff8183d153)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/inet_fragment.c (ffffffff81840fd1)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frags_exit_net
  - net/ipv4/inet_fragment.c:inet_frag_worker
```
```
In net/ipv4/proc.c (ffffffff8184514e)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/ipv4/proc.c:sockstat_seq_show
```
```
In net/ipv4/xfrm4_policy.c (ffffffff8184dbf4)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_garbage_collect
```
```
In net/unix/af_unix.c (ffffffff8185ca77)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/ipv6/ip6_output.c (ffffffff81863e3e)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/addrconf.c (ffffffff8186aafa)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:if6_seq_stop
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
```
```
In net/ipv6/route.c (ffffffff81874c24)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_stats_seq_show
  - net/ipv6/route.c:ip6_dst_gc
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ip6_fib.c (ffffffff81879cd8)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_stop
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff8187dd51)
Location: include/linux/bottom_half.h:29
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff81888901)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8188f9c1)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff818975e6)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_stop
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In net/ipv6/proc.c (ffffffff818a1352)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/ipv6/proc.c:sockstat6_seq_show
```
```
In net/ipv6/seg6_hmac.c (ffffffff818a4ac5)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
```
```
In net/ipv6/inet6_hashtables.c (ffffffff818a75ad)
Location: include/linux/bottom_half.h:29
Inline: True
```
```
In net/packet/af_packet.c (ffffffff818a8f76)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_direct_xmit
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
In kernel/sched/core.c (ffffffff81906610)
Location: include/linux/bottom_half.h:29
Inline: True
```
```
In kernel/irq/manage.c (ffffffff810e6ca8)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_forced_thread_fn
```
```
In kernel/rcu/update.c (ffffffff810f0559)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/srcutree.c (ffffffff810f18cc)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
```
```
In kernel/padata.c (ffffffff811b2f42)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_parallel_worker
```
```
In security/smack/smack_lsm.c (ffffffff813c1a96)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_netlabel
```
```
In drivers/net/tun.c (ffffffff81694cf0)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8169b252)
Location: include/linux/bottom_half.h:29
Inline: True
```
```
In net/core/sock.c (ffffffff817b2db6)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/core/sock.c:lock_sock_nested
```
```
In net/core/dev.c (ffffffff817cd6e0)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:flush_backlog
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/neighbour.c (ffffffff817da016)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_seq_stop
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_for_each
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/flow.c (ffffffff817ef189)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_flush
  - net/core/flow.c:flow_cache_lookup
```
```
In net/sched/sch_generic.c (ffffffff817fd8a3)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
```
```
In net/netlink/af_netlink.c (ffffffff8180983a)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_create
```
```
In net/netfilter/nf_log.c (ffffffff8180e0c8)
Location: include/linux/bottom_half.h:29
Inline: True
```
```
In net/netfilter/nf_queue.c (ffffffff8180e512)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_reinject
```
```
In net/ipv4/route.c (ffffffff81810312)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff818195d1)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_hashtables.c (ffffffff8181f499)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff8181fd05)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81820e50)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/tcp.c (ffffffff81827560)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff81830bf8)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81838d54)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/icmp.c (ffffffff8184e0f7)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_send
```
```
In net/ipv4/fib_frontend.c (ffffffff8185a654)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
```
```
In net/ipv4/fib_semantics.c (ffffffff8185e808)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/inet_fragment.c (ffffffff81862861)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frags_exit_net
  - net/ipv4/inet_fragment.c:inet_frag_worker
```
```
In net/unix/af_unix.c (ffffffff81881205)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/ipv6/ip6_output.c (ffffffff818893d6)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/addrconf.c (ffffffff8188f06a)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:if6_seq_stop
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff81899c92)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ip6_fib.c (ffffffff8189f738)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_stop
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff818a32d3)
Location: include/linux/bottom_half.h:29
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff818aee45)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818b6064)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff818bd9f6)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_stop
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In net/ipv6/seg6_hmac.c (ffffffff818cb290)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
```
```
In net/ipv6/inet6_hashtables.c (ffffffff818cdea8)
Location: include/linux/bottom_half.h:29
Inline: True
```
```
In net/packet/af_packet.c (ffffffff818cf9aa)
Location: include/linux/bottom_half.h:29
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_direct_xmit
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
In kernel/sched/core.c (ffffffff819906a1)
Location: include/linux/bottom_half.h:30
Inline: True
```
```
In kernel/irq/manage.c (ffffffff810eef7e)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_forced_thread_fn
```
```
In kernel/rcu/update.c (ffffffff810fa220)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/srcutree.c (ffffffff810fb632)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
```
```
In kernel/bpf/cpumap.c (ffffffff811afd77)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In kernel/padata.c (ffffffff811c6b95)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:invoke_padata_reorder
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_parallel_worker
```
```
In security/smack/smack_lsm.c (ffffffff813e8136)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_netlabel
```
```
In drivers/net/tun.c (ffffffff816ff5f6)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81705a47)
Location: include/linux/bottom_half.h:30
Inline: True
```
```
In net/core/sock.c (ffffffff8182b0a6)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/core/sock.c:lock_sock_nested
```
```
In net/core/gen_estimator.c (ffffffff8183bdd3)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/dev.c (ffffffff81846e05)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:flush_backlog
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/neighbour.c (ffffffff818547b6)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_seq_stop
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_for_each
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
```
```
In net/sched/sch_generic.c (ffffffff8187b48b)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
```
```
In net/netlink/af_netlink.c (ffffffff81888780)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_create
```
```
In net/netfilter/nf_log.c (ffffffff8188d5a8)
Location: include/linux/bottom_half.h:30
Inline: True
```
```
In net/netfilter/nf_queue.c (ffffffff8188db1a)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_reinject
```
```
In net/ipv4/route.c (ffffffff8188f37d)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81897bf8)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_hashtables.c (ffffffff8189e3fc)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff8189eca5)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/inet_connection_sock.c (ffffffff818a02f8)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/tcp.c (ffffffff818a637b)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff818b0067)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
```
In net/ipv4/tcp_ipv4.c (ffffffff818b85ab)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/tcp_minisocks.c (ffffffff818bddfd)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/icmp.c (ffffffff818cde1d)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_send
```
```
In net/ipv4/fib_frontend.c (ffffffff818da574)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
```
```
In net/ipv4/fib_semantics.c (ffffffff818de87b)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/inet_fragment.c (ffffffff818e2981)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frags_exit_net
  - net/ipv4/inet_fragment.c:inet_frag_worker
```
```
In net/xfrm/xfrm_policy.c (ffffffff818f844b)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup
  - net/xfrm/xfrm_policy.c:xfrm_lookup
  - net/xfrm/xfrm_policy.c:xfrm_policy_cache_flush
  - net/xfrm/xfrm_policy.c:xfrm_pcpu_work_fn
```
```
In net/unix/af_unix.c (ffffffff81902395)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/ipv6/ip6_output.c (ffffffff8190984a)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/addrconf.c (ffffffff819106ba)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff8191dd60)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:rt6_age_exceptions
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ip6_fib.c (ffffffff81921d38)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_stop
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81925e88)
Location: include/linux/bottom_half.h:30
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff81931b48)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81938def)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81940a96)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_stop
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In net/ipv6/seg6_hmac.c (ffffffff81950030)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81952cc8)
Location: include/linux/bottom_half.h:30
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81954923)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_direct_xmit
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
In kernel/irq/manage.c (ffffffff810f76ae)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_forced_thread_fn
```
```
In kernel/rcu/update.c (ffffffff811027ae)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/srcutree.c (ffffffff81103aaf)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
```
```
In kernel/time/hrtimer.c (ffffffff81116def)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
```
```
In kernel/bpf/cpumap.c (ffffffff811cac45)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In kernel/padata.c (ffffffff811e7565)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:invoke_padata_reorder
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_parallel_worker
```
```
In security/smack/smack_lsm.c (ffffffff81418f6f)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_netlabel
```
```
In drivers/net/tun.c (ffffffff8173eded)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81744ef7)
Location: include/linux/bottom_half.h:30
Inline: True
```
```
In net/core/sock.c (ffffffff81877776)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/core/sock.c:lock_sock_nested
```
```
In net/core/gen_estimator.c (ffffffff81886553)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/dev.c (ffffffff8189045f)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:flush_backlog
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/neighbour.c (ffffffff8189ff15)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_seq_stop
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_for_each
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
```
```
In net/sched/sch_generic.c (ffffffff818cd93b)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
```
```
In net/netlink/af_netlink.c (ffffffff818dc1b4)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_create
```
```
In net/netfilter/nf_log.c (ffffffff818e120b)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/netfilter/nf_log.c:nf_log_buf_close
```
```
In net/netfilter/nf_queue.c (ffffffff818e17f6)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_reinject
```
```
In net/ipv4/route.c (ffffffff818e379b)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff818ebf56)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_hashtables.c (ffffffff818f2e89)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff818f37a2)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/inet_connection_sock.c (ffffffff818f5733)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/tcp.c (ffffffff818fb3ec)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff819055cc)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8190eb5f)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81912835)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/icmp.c (ffffffff819246dd)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_send
```
```
In net/ipv4/fib_frontend.c (ffffffff81930fc1)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
```
```
In net/ipv4/fib_semantics.c (ffffffff819353ff)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/xfrm/xfrm_policy.c (ffffffff8194ef4a)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup
  - net/xfrm/xfrm_policy.c:xfrm_lookup
  - net/xfrm/xfrm_policy.c:xfrm_policy_cache_flush
  - net/xfrm/xfrm_policy.c:xfrm_pcpu_work_fn
```
```
In net/unix/af_unix.c (ffffffff81959ce5)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/ipv6/ip6_output.c (ffffffff81960b6b)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/addrconf.c (ffffffff81967ada)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff819765a1)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:rt6_age_exceptions
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ip6_fib.c (ffffffff8197a128)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_stop
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff8197eb6c)
Location: include/linux/bottom_half.h:30
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff8198a602)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8199265e)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81999985)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_stop
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In net/ipv6/seg6_hmac.c (ffffffff819a9780)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
```
```
In net/ipv6/inet6_hashtables.c (ffffffff819ac274)
Location: include/linux/bottom_half.h:30
Inline: True
```
```
In net/xdp/xsk.c (ffffffff819cbf31)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
  - net/xdp/xsk.c:xsk_release
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
In arch/x86/kernel/fpu/signal.c (ffffffff8103cbc0)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
```
In kernel/irq/manage.c (ffffffff81102aec)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_forced_thread_fn
```
```
In kernel/rcu/update.c (ffffffff8110e1b6)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/srcutree.c (ffffffff8110f46f)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
```
```
In kernel/time/hrtimer.c (ffffffff8112242f)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
```
```
In kernel/bpf/cpumap.c (ffffffff811de53c)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In kernel/padata.c (ffffffff811f8485)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:invoke_padata_reorder
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_parallel_worker
```
```
In security/smack/smack_lsm.c (ffffffff81435656)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_netlabel
```
```
In drivers/net/tun.c (ffffffff817636f3)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81768fe7)
Location: include/linux/bottom_half.h:30
Inline: True
```
```
In net/core/sock.c (ffffffff81897da6)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/core/sock.c:lock_sock_nested
```
```
In net/core/gen_estimator.c (ffffffff818a6cd3)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/dev.c (ffffffff818b0d0f)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:flush_backlog
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/neighbour.c (ffffffff818c27d5)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_seq_stop
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_for_each
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
```
```
In net/sched/sch_generic.c (ffffffff818f8b7b)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
```
```
In net/netlink/af_netlink.c (ffffffff81908b83)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_create
```
```
In net/netfilter/nf_log.c (ffffffff8190dd7b)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/netfilter/nf_log.c:nf_log_buf_close
```
```
In net/netfilter/nf_queue.c (ffffffff8190e386)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_reinject
```
```
In net/ipv4/route.c (ffffffff8191064b)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81919cf6)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_hashtables.c (ffffffff81920b0d)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff819212c2)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81922a73)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/tcp.c (ffffffff81929330)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff81933772)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8193cf8f)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81941004)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/icmp.c (ffffffff819532f5)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/fib_frontend.c (ffffffff819608be)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
```
```
In net/ipv4/fib_semantics.c (ffffffff81964dff)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/unix/af_unix.c (ffffffff8198e866)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/ipv6/ip6_output.c (ffffffff81996e6b)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/addrconf.c (ffffffff8199d1ca)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff819ac181)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:rt6_age_exceptions
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ip6_fib.c (ffffffff819afd18)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_stop
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff819b5116)
Location: include/linux/bottom_half.h:30
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff819c0e9c)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819c8d9e)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff819d02d5)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_stop
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In net/ipv6/seg6_hmac.c (ffffffff819e0280)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
```
```
In net/ipv6/inet6_hashtables.c (ffffffff819e2e54)
Location: include/linux/bottom_half.h:30
Inline: True
```
```
In net/xdp/xsk.c (ffffffff81a05147)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
  - net/xdp/xsk.c:xsk_release
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
In arch/x86/kernel/fpu/core.c (ffffffff8103e465)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:fpu__save
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103f364)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8103fe7c)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/mm/pkeys.c (ffffffff8108dc0a)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:copy_init_pkru_to_fpregs
```
```
In kernel/irq/manage.c (ffffffff8110b4af)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_forced_thread_fn
```
```
In kernel/rcu/update.c (ffffffff811178cf)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/srcutree.c (ffffffff811191c2)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
```
```
In kernel/rcu/tree.c (ffffffff8111caf2)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_cpu_kthread
```
```
In kernel/time/hrtimer.c (ffffffff8112cd53)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
```
```
In kernel/bpf/cpumap.c (ffffffff811f3e35)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In kernel/bpf/offload.c (ffffffff811f4e9c)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In kernel/padata.c (ffffffff812109a5)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:invoke_padata_reorder
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_parallel_worker
```
```
In ipc/util.c (ffffffff8141cfea)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
  - ipc/util.c:ipc_addid
  - ipc/util.c:ipc_addid
```
```
In security/smack/smack_lsm.c (ffffffff814630c4)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_netlabel
```
```
In security/apparmor/policy_unpack.c (ffffffff81488e0f)
Location: include/linux/bottom_half.h:30
Inline: True
```
```
In lib/rhashtable.c (ffffffff8150d6b3)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In drivers/net/tun.c (ffffffff817a1428)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817a6ac7)
Location: include/linux/bottom_half.h:30
Inline: True
```
```
In net/core/sock.c (ffffffff818e22c1)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/core/sock.c:lock_sock_nested
```
```
In net/core/skbuff.c (ffffffff818e8c52)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:netdev_alloc_frag
```
```
In net/core/gen_estimator.c (ffffffff818f2163)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/dev.c (ffffffff818fdaad)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:flush_backlog
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/neighbour.c (ffffffff8190eeae)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_seq_stop
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_for_each
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/xdp.c (ffffffff819307f4)
Location: include/linux/bottom_half.h:30
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff8195834b)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
```
```
In net/sched/cls_api.c (ffffffff81962a47)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tc_indr_block_cb_register
  - net/sched/cls_api.c:__tc_indr_block_cb_register
  - net/sched/cls_api.c:__tc_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffff81969f97)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/netfilter/nf_log.c (ffffffff8196f8a0)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/netfilter/nf_log.c:nf_log_buf_close
```
```
In net/netfilter/nf_queue.c (ffffffff8196fe6e)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_reinject
```
```
In net/ipv4/route.c (ffffffff81973099)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff8197bdf8)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_hashtables.c (ffffffff819833b5)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81983c77)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819853a8)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/tcp.c (ffffffff8198c267)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff8199797c)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a13df)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819a5602)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/icmp.c (ffffffff819b7e41)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/fib_frontend.c (ffffffff819c4ea6)
Location: include/linux/bottom_half.h:30
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff819cab67)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/inet_fragment.c (ffffffff819cfb21)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/nexthop.c (ffffffff819d4d4a)
Location: include/linux/bottom_half.h:30
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff819dbbc5)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff819e9952)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/unix/af_unix.c (ffffffff819f9fca)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/ipv6/ip6_output.c (ffffffff81a00d00)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/addrconf.c (ffffffff81a0939a)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff81a19da3)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ip6_fib.c (ffffffff81a1de78)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_stop
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81a23619)
Location: include/linux/bottom_half.h:30
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff81a2fc2e)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a3774f)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81a3efd5)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_stop
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In net/ipv6/ip6mr.c (ffffffff81a443db)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a4f62c)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a51bd7)
Location: include/linux/bottom_half.h:30
Inline: True
```
```
In net/xdp/xsk.c (ffffffff81a74711)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
  - net/xdp/xsk.c:xsk_release
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
In arch/x86/kernel/fpu/core.c (ffffffff8103ec25)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:fpu__save
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103f8e8)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8104059c)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/mm/pkeys.c (ffffffff8108e86a)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:copy_init_pkru_to_fpregs
```
```
In kernel/irq/manage.c (ffffffff811177af)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_forced_thread_fn
```
```
In kernel/rcu/update.c (ffffffff81123ca3)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/srcutree.c (ffffffff81125592)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
```
```
In kernel/rcu/tree.c (ffffffff81129082)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_cpu_kthread
```
```
In kernel/time/hrtimer.c (ffffffff81138d33)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
```
```
In kernel/bpf/cpumap.c (ffffffff81200bd5)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In kernel/bpf/offload.c (ffffffff81201eac)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In kernel/padata.c (ffffffff8121d553)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:invoke_padata_reorder
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_parallel_worker
```
```
In ipc/util.c (ffffffff81436e3a)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
  - ipc/util.c:ipc_addid
  - ipc/util.c:ipc_addid
```
```
In security/smack/smack_lsm.c (ffffffff8147ce94)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_netlabel
```
```
In security/apparmor/policy_unpack.c (ffffffff814a2cbf)
Location: include/linux/bottom_half.h:30
Inline: True
```
```
In lib/rhashtable.c (ffffffff8152b503)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In drivers/net/tun.c (ffffffff817c63e8)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817ca527)
Location: include/linux/bottom_half.h:30
Inline: True
```
```
In net/core/sock.c (ffffffff81914471)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/core/sock.c:lock_sock_nested
```
```
In net/core/skbuff.c (ffffffff8191adb2)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:netdev_alloc_frag
```
```
In net/core/gen_estimator.c (ffffffff819240b3)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/dev.c (ffffffff81935833)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:flush_backlog
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/neighbour.c (ffffffff8194151e)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_seq_stop
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_for_each
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/xdp.c (ffffffff81962d07)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
  - net/core/xdp.c:mem_xa_remove
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff81963f43)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
  - net/core/flow_offload.c:__flow_indr_block_cb_register
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/sched/sch_generic.c (ffffffff8198e7fb)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
```
```
In net/netlink/af_netlink.c (ffffffff819a0a07)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/netfilter/nf_log.c (ffffffff819a62d0)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/netfilter/nf_log.c:nf_log_buf_close
```
```
In net/netfilter/nf_queue.c (ffffffff819a686e)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_reinject
```
```
In net/ipv4/route.c (ffffffff819a9a0c)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff819b279e)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_hashtables.c (ffffffff819b9c28)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff819ba457)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819bbbb8)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/tcp.c (ffffffff819c2bb7)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff819ce50c)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819d808f)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819dc2f1)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/icmp.c (ffffffff819eeb41)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/fib_frontend.c (ffffffff819fba46)
Location: include/linux/bottom_half.h:30
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff81a01757)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/inet_fragment.c (ffffffff81a066b1)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/nexthop.c (ffffffff81a0b8aa)
Location: include/linux/bottom_half.h:30
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81a12af5)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a2167a)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/unix/af_unix.c (ffffffff81a30c4a)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/ipv6/ip6_output.c (ffffffff81a378d3)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/addrconf.c (ffffffff81a4008a)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff81a50a13)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ip6_fib.c (ffffffff81a54ad8)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_stop
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81a5a3ee)
Location: include/linux/bottom_half.h:30
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff81a6677e)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a6e279)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81a75c45)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_stop
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In net/ipv6/ip6mr.c (ffffffff81a7afcb)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a862bc)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a887d7)
Location: include/linux/bottom_half.h:30
Inline: True
```
```
In net/xdp/xsk.c (ffffffff81aab0c0)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
  - net/xdp/xsk.c:xsk_release
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
In arch/x86/kernel/fpu/core.c (ffffffff81041a0d)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:fpu__save
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81042b4e)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81043940)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/mm/pkeys.c (ffffffff810949ed)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:copy_init_pkru_to_fpregs
```
```
In kernel/irq/manage.c (ffffffff8112341f)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_forced_thread_fn
```
```
In kernel/rcu/update.c (ffffffff811304fe)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/srcutree.c (ffffffff81133138)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
```
```
In kernel/rcu/tree.c (ffffffff81136f3b)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_cpu_kthread
```
```
In kernel/time/hrtimer.c (ffffffff81147c93)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
```
```
In kernel/bpf/cpumap.c (ffffffff81228571)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In kernel/bpf/offload.c (ffffffff81229372)
Location: include/linux/bottom_half.h:30
Inline: True
```
```
In kernel/padata.c (ffffffff81249843)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:invoke_padata_reorder
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_parallel_worker
```
```
In ipc/util.c (ffffffff814869f2)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - ipc/util.c:__rhashtable_remove_fast_one
  - ipc/util.c:__rhashtable_remove_fast_one
  - ipc/util.c:__rhashtable_remove_fast_one
```
```
In security/smack/smack_lsm.c (ffffffff814d2935)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_netlabel
```
```
In security/apparmor/policy_unpack.c (ffffffff814fcfa7)
Location: include/linux/bottom_half.h:30
Inline: True
```
```
In lib/rhashtable.c (ffffffff8158ea8b)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_chain
```
```
In drivers/net/tun.c (ffffffff8188e41f)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_build_skb
  - drivers/net/tun.c:tun_build_skb
  - drivers/net/tun.c:tun_napi_alloc_frags
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81895577)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
```
```
In net/core/sock.c (ffffffff819e57c1)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/core/sock.c:lock_sock_nested
```
```
In net/core/skbuff.c (ffffffff819ed392)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:netdev_alloc_frag
```
```
In net/core/gen_estimator.c (ffffffff819f7c63)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/dev.c (ffffffff81a0a518)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:flush_backlog
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/neighbour.c (ffffffff81a1203e)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_seq_stop
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_for_each
  - net/core/neighbour.c:neigh_dump_table
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/xdp.c (ffffffff81a360c2)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/core/xdp.c:__rhashtable_remove_fast_one
  - net/core/xdp.c:__rhashtable_remove_fast_one
  - net/core/xdp.c:__rhashtable_remove_fast_one
```
```
In net/sched/sch_generic.c (ffffffff81a665af)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
```
```
In net/netlink/af_netlink.c (ffffffff81a7a17f)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
```
```
In net/netfilter/nf_log.c (ffffffff81a8f594)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/netfilter/nf_log.c:nf_log_buf_close
```
```
In net/netfilter/nf_queue.c (ffffffff81a8fb9d)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_reinject
```
```
In net/ipv4/route.c (ffffffff81a92e58)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81a9be82)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_hashtables.c (ffffffff81aa452d)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81aa4f62)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81aa64e1)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/tcp.c (ffffffff81aae14f)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff81aba5f5)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac407f)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ac9451)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/icmp.c (ffffffff81adc8cb)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/fib_frontend.c (ffffffff81aeaaad)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_lookup
```
```
In net/ipv4/fib_semantics.c (ffffffff81af075e)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/inet_fragment.c (ffffffff81af5fb2)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/nexthop.c (ffffffff81afc320)
Location: include/linux/bottom_half.h:30
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81b01d9e)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:__rhashtable_remove_fast_one
  - net/ipv4/ipmr.c:__rhashtable_remove_fast_one
  - net/ipv4/ipmr.c:__rhashtable_remove_fast_one
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b1095b)
Location: include/linux/bottom_half.h:30
Inline: True
```
```
In net/xfrm/espintcp.c (ffffffff81b22843)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:handle_esp
```
```
In net/unix/af_unix.c (ffffffff81b24edf)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/ipv6/ip6_output.c (ffffffff81b2d3c5)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/addrconf.c (ffffffff81b3b41b)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:add_addr
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:manage_tempaddrs
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff81b47d0e)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:rt6_probe
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ip6_fib.c (ffffffff81b4c0cd)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_stop
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81b52692)
Location: include/linux/bottom_half.h:30
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff81b5f13f)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b67497)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81b6fe45)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_stop
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In net/ipv6/ip6mr.c (ffffffff81b7532e)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:__rhashtable_remove_fast_one
  - net/ipv6/ip6mr.c:__rhashtable_remove_fast_one
  - net/ipv6/ip6mr.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b80cea)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
  - net/ipv6/seg6_hmac.c:__rhashtable_remove_fast_one
  - net/ipv6/seg6_hmac.c:__rhashtable_remove_fast_one
  - net/ipv6/seg6_hmac.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81b83ce7)
Location: include/linux/bottom_half.h:30
Inline: True
```
```
In net/xdp/xsk.c (ffffffff81ba7060)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
  - net/xdp/xsk.c:xsk_release
```
```
In net/mptcp/protocol.c (ffffffff81bac831)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_accept
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
In arch/x86/kernel/fpu/core.c (ffffffff81041999)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:fpu__save
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81042a99)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff810439f0)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/mm/pkeys.c (ffffffff81093ddd)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:copy_init_pkru_to_fpregs
```
```
In kernel/irq/manage.c (ffffffff8111f26d)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_forced_thread_fn
```
```
In kernel/rcu/update.c (ffffffff8112c3ac)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/srcutree.c (ffffffff8112e918)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
```
```
In kernel/rcu/tree.c (ffffffff81132579)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_cpu_kthread
```
```
In kernel/time/hrtimer.c (ffffffff81144116)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
```
```
In kernel/bpf/cpumap.c (ffffffff8122f31e)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
```
```
In kernel/bpf/offload.c (ffffffff81230f02)
Location: include/linux/bottom_half.h:30
Inline: True
```
```
In kernel/padata.c (ffffffff812546d3)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:invoke_padata_reorder
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_parallel_worker
```
```
In ipc/util.c (ffffffff814a40a2)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - ipc/util.c:__rhashtable_remove_fast_one
  - ipc/util.c:__rhashtable_remove_fast_one
  - ipc/util.c:__rhashtable_remove_fast_one
```
```
In security/smack/smack_lsm.c (ffffffff814f39e9)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smk_ipv4_check
  - security/smack/smack_lsm.c:smack_netlbl_add
```
```
In security/apparmor/policy_unpack.c (ffffffff8151a1b7)
Location: include/linux/bottom_half.h:30
Inline: True
```
```
In lib/rhashtable.c (ffffffff815ab5eb)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_chain
```
```
In drivers/net/tun.c (ffffffff8189c98b)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_build_skb
  - drivers/net/tun.c:tun_build_skb
  - drivers/net/tun.c:tun_napi_alloc_frags
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff818a3ca7)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
```
```
In net/core/sock.c (ffffffff819e7bd1)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/core/sock.c:lock_sock_nested
```
```
In net/core/skbuff.c (ffffffff819ed057)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:netdev_alloc_frag
```
```
In net/core/gen_estimator.c (ffffffff819f76d5)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/dev.c (ffffffff81a0c84a)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:flush_backlog
  - net/core/dev.c:__dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/neighbour.c (ffffffff81a1239e)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_seq_stop
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_for_each
  - net/core/neighbour.c:neigh_dump_table
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/filter.c (ffffffff81a2ea7b)
Location: include/linux/bottom_half.h:30
Inline: True
```
```
In net/core/xdp.c (ffffffff81a38492)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/core/xdp.c:__rhashtable_remove_fast_one
  - net/core/xdp.c:__rhashtable_remove_fast_one
  - net/core/xdp.c:__rhashtable_remove_fast_one
```
```
In net/core/lwt_bpf.c (ffffffff81a52771)
Location: include/linux/bottom_half.h:30
Inline: True
```
```
In net/core/sock_map.c (ffffffff81a55988)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_update_elem
```
```
In net/sched/sch_generic.c (ffffffff81a6e68f)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
```
```
In net/netlink/af_netlink.c (ffffffff81a82fdf)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
```
```
In net/netfilter/nf_log.c (ffffffff81c323ef)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/netfilter/nf_log.c:nf_log_buf_close
```
```
In net/netfilter/nf_queue.c (ffffffff81a99b8c)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_reinject
```
```
In net/ipv4/route.c (ffffffff81a9ccf6)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81aa5ce2)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_hashtables.c (ffffffff81aaeb7d)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81aaf5cd)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ab0b31)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/tcp.c (ffffffff81ab83d2)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff81ac5a35)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81acfb0f)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ad53a1)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/icmp.c (ffffffff81ae95e6)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/fib_frontend.c (ffffffff81af7952)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_lookup
```
```
In net/ipv4/fib_semantics.c (ffffffff81afd74e)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/inet_fragment.c (ffffffff81b02e22)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/nexthop.c (ffffffff81b09b60)
Location: include/linux/bottom_half.h:30
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81b0fe7e)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:__rhashtable_remove_fast_one
  - net/ipv4/ipmr.c:__rhashtable_remove_fast_one
  - net/ipv4/ipmr.c:__rhashtable_remove_fast_one
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b1ec4b)
Location: include/linux/bottom_half.h:30
Inline: True
```
```
In net/xfrm/espintcp.c (ffffffff81b314f6)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:handle_esp
```
```
In net/unix/af_unix.c (ffffffff81b33a16)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/ipv6/ip6_output.c (ffffffff81b3bdd5)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/addrconf.c (ffffffff81b4a12b)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:add_addr
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:manage_tempaddrs
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff81b568a9)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:rt6_probe
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ip6_fib.c (ffffffff81b5ad0d)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_stop
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81b617b3)
Location: include/linux/bottom_half.h:30
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff81b6d8cf)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b75c97)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81b7e955)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_stop
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_renew
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_renew
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In net/ipv6/ip6mr.c (ffffffff81b8409e)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:__rhashtable_remove_fast_one
  - net/ipv6/ip6mr.c:__rhashtable_remove_fast_one
  - net/ipv6/ip6mr.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b9055a)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
  - net/ipv6/seg6_hmac.c:__rhashtable_remove_fast_one
  - net/ipv6/seg6_hmac.c:__rhashtable_remove_fast_one
  - net/ipv6/seg6_hmac.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81b93397)
Location: include/linux/bottom_half.h:30
Inline: True
```
```
In net/xdp/xsk.c (ffffffff81bb639f)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
  - net/xdp/xsk.c:xsk_release
```
```
In net/mptcp/protocol.c (ffffffff81bbdd42)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:mptcp_sendmsg
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
In arch/x86/kernel/fpu/core.c (ffffffff81043399)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:fpu__save
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81044487)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81045234)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/mm/pkeys.c (ffffffff8109479d)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:copy_init_pkru_to_fpregs
```
```
In kernel/irq/manage.c (ffffffff8111f78d)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_forced_thread_fn
```
```
In kernel/rcu/update.c (ffffffff8112c8dc)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/srcutree.c (ffffffff8112eba0)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
```
```
In kernel/rcu/tree.c (ffffffff81133899)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_do_batch
```
```
In kernel/time/hrtimer.c (ffffffff8114529e)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
```
```
In kernel/bpf/cpumap.c (ffffffff81234241)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
```
```
In kernel/bpf/offload.c (ffffffff81235098)
Location: include/linux/bottom_half.h:30
Inline: True
```
```
In kernel/padata.c (ffffffff81258c73)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:invoke_padata_reorder
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_parallel_worker
```
```
In ipc/util.c (ffffffff814a9fc9)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - ipc/util.c:__rhashtable_remove_fast_one
  - ipc/util.c:__rhashtable_remove_fast_one
  - ipc/util.c:__rhashtable_remove_fast_one
```
```
In security/smack/smack_lsm.c (ffffffff814fa9a9)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smk_ipv4_check
  - security/smack/smack_lsm.c:smack_netlbl_add
```
```
In security/apparmor/policy_unpack.c (ffffffff81520ac5)
Location: include/linux/bottom_half.h:30
Inline: True
```
```
In lib/rhashtable.c (ffffffff815b644f)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In drivers/net/tun.c (ffffffff8187eefb)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_build_skb
  - drivers/net/tun.c:tun_build_skb
  - drivers/net/tun.c:tun_napi_alloc_frags
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff818859b7)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
```
```
In net/core/sock.c (ffffffff819cdfea)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/core/sock.c:sock_set_priority
  - net/core/sock.c:sock_no_linger
  - net/core/sock.c:sock_set_reuseport
  - net/core/sock.c:sock_set_reuseaddr
```
```
In net/core/skbuff.c (ffffffff819d352c)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_frag_align
```
```
In net/core/gen_estimator.c (ffffffff819dd855)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/dev.c (ffffffff819f2f76)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/core/dev.c:napi_threaded_poll
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:flush_backlog
  - net/core/dev.c:__dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/neighbour.c (ffffffff819f8fce)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_seq_stop
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_for_each
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/filter.c (ffffffff81a160cd)
Location: include/linux/bottom_half.h:30
Inline: True
```
```
In net/core/xdp.c (ffffffff81a1f2c9)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/core/xdp.c:__rhashtable_remove_fast_one
  - net/core/xdp.c:__rhashtable_remove_fast_one
  - net/core/xdp.c:__rhashtable_remove_fast_one
```
```
In net/core/lwt_bpf.c (ffffffff81a37f41)
Location: include/linux/bottom_half.h:30
Inline: True
```
```
In net/core/sock_map.c (ffffffff81a51409)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_update_elem
```
```
In net/sched/sch_generic.c (ffffffff81a56f1f)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
```
```
In net/netlink/af_netlink.c (ffffffff81a6c0af)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
```
```
In net/netfilter/nf_log.c (ffffffff81c246d8)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/netfilter/nf_log.c:nf_log_buf_close
```
```
In net/netfilter/nf_queue.c (ffffffff81a84e9c)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_reinject
```
```
In net/ipv4/route.c (ffffffff81a87dc0)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81a90caf)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_hashtables.c (ffffffff81a99dbd)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81a9a8d5)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81a9bbdd)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/tcp.c (ffffffff81aa36cc)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff81ab0c41)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abac5f)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ac041e)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/icmp.c (ffffffff81ad4a71)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_reply
```
```
In net/ipv4/fib_frontend.c (ffffffff81ae3072)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_lookup
```
```
In net/ipv4/fib_semantics.c (ffffffff81ae8f89)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/inet_fragment.c (ffffffff81aee719)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/nexthop.c (ffffffff81af499b)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_select_path_hthr
  - net/ipv4/nexthop.c:nexthop_select_path_hthr
```
```
In net/ipv4/ipmr.c (ffffffff81afda6e)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:__rhashtable_remove_fast_one
  - net/ipv4/ipmr.c:__rhashtable_remove_fast_one
  - net/ipv4/ipmr.c:__rhashtable_remove_fast_one
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0c8d6)
Location: include/linux/bottom_half.h:30
Inline: True
```
```
In net/xfrm/espintcp.c (ffffffff81b1f3a0)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_rcv
```
```
In net/unix/af_unix.c (ffffffff81b2141a)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/ipv6/ip6_output.c (ffffffff81b2973d)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/addrconf.c (ffffffff81b372a4)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff81b444fd)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:rt6_probe
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ip6_fib.c (ffffffff81b48f8d)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_stop
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81b4fa7f)
Location: include/linux/bottom_half.h:30
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff81b5bc65)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b650ca)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81b6d555)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_stop
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In net/ipv6/ip6mr.c (ffffffff81b72d1e)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:__rhashtable_remove_fast_one
  - net/ipv6/ip6mr.c:__rhashtable_remove_fast_one
  - net/ipv6/ip6mr.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b7f79a)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
  - net/ipv6/seg6_hmac.c:__rhashtable_remove_fast_one
  - net/ipv6/seg6_hmac.c:__rhashtable_remove_fast_one
  - net/ipv6/seg6_hmac.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81b824c7)
Location: include/linux/bottom_half.h:30
Inline: True
```
```
In net/xdp/xsk.c (ffffffff81ba670b)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
  - net/xdp/xsk.c:xsk_release
```
```
In net/mptcp/protocol.c (ffffffff81bade74)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:mptcp_sendmsg
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
In arch/x86/kernel/fpu/core.c (ffffffff81049b0c)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu_flush_thread
  - arch/x86/kernel/fpu/core.c:fpu__clear_user_states
  - arch/x86/kernel/fpu/core.c:fpu_clone
  - arch/x86/kernel/fpu/core.c:fpu_sync_fpstate
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8104a997)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user
  - arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In kernel/irq/manage.c (ffffffff8113fc1d)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_forced_thread_fn
```
```
In kernel/rcu/update.c (ffffffff8114d5f4)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/srcutree.c (ffffffff8115008e)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
```
```
In kernel/rcu/tree.c (ffffffff81155c89)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_do_batch
```
```
In kernel/time/hrtimer.c (ffffffff81168aed)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
```
```
In kernel/bpf/cpumap.c (ffffffff8126e208)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In kernel/bpf/offload.c (ffffffff8126f1c8)
Location: include/linux/bottom_half.h:30
Inline: True
```
```
In kernel/padata.c (ffffffff8129489e)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:invoke_padata_reorder
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_parallel_worker
```
```
In ipc/util.c (ffffffff81502479)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - ipc/util.c:__rhashtable_remove_fast_one
  - ipc/util.c:__rhashtable_remove_fast_one
  - ipc/util.c:__rhashtable_remove_fast_one
```
```
In security/smack/smack_lsm.c (ffffffff81555619)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smk_ipv4_check
  - security/smack/smack_lsm.c:smack_netlbl_add
```
```
In security/apparmor/policy_unpack.c (ffffffff8157ec65)
Location: include/linux/bottom_half.h:30
Inline: True
```
```
In lib/rhashtable.c (ffffffff8161c992)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In drivers/net/tun.c (ffffffff81910705)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_build_skb
  - drivers/net/tun.c:tun_build_skb
  - drivers/net/tun.c:tun_napi_alloc_frags
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81917347)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
```
```
In drivers/net/xen-netfront.c (ffffffff8191f417)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:netfront_resume
```
```
In net/core/skbuff.c (ffffffff81a8327d)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_frag_align
```
```
In net/core/gen_estimator.c (ffffffff81a8db35)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/dev.c (ffffffff81aa3dcb)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/core/dev.c:napi_threaded_poll
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:flush_backlog
  - net/core/dev.c:__dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/neighbour.c (ffffffff81aaabae)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_seq_stop
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_for_each
  - net/core/neighbour.c:neigh_dump_table
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/filter.c (ffffffff81ac7753)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/core/filter.c:bpf_out_neigh_v6
  - net/core/filter.c:bpf_out_neigh_v6
```
```
In net/core/xdp.c (ffffffff81ad3559)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/core/xdp.c:__rhashtable_remove_fast_one
  - net/core/xdp.c:__rhashtable_remove_fast_one
  - net/core/xdp.c:__rhashtable_remove_fast_one
```
```
In net/core/lwt_bpf.c (ffffffff81aedd6b)
Location: include/linux/bottom_half.h:30
Inline: True
```
```
In net/core/sock_map.c (ffffffff81b0a19e)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_update_elem
```
```
In net/sched/sch_generic.c (ffffffff81b0fd54)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
```
```
In net/netlink/af_netlink.c (ffffffff81b256cc)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
```
```
In net/netfilter/nf_log.c (ffffffff81d39bce)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/netfilter/nf_log.c:nf_log_buf_close
```
```
In net/netfilter/nf_queue.c (ffffffff81b3f537)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_reinject
```
```
In net/ipv4/route.c (ffffffff81b42303)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81b4c111)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_hashtables.c (ffffffff81b5522d)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81b55d45)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81b572df)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/tcp.c (ffffffff81b5f857)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff81b6da85)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b77faf)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81b7f3af)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/icmp.c (ffffffff81b939d9)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_reply
```
```
In net/ipv4/fib_frontend.c (ffffffff81ba26a2)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_lookup
```
```
In net/ipv4/fib_semantics.c (ffffffff81ba8fc3)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/inet_fragment.c (ffffffff81baeac9)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/nexthop.c (ffffffff81bb522d)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_select_path_hthr
  - net/ipv4/nexthop.c:nexthop_select_path_hthr
```
```
In net/ipv4/ipmr.c (ffffffff81bbfb6e)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:__rhashtable_remove_fast_one
  - net/ipv4/ipmr.c:__rhashtable_remove_fast_one
  - net/ipv4/ipmr.c:__rhashtable_remove_fast_one
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bcfac6)
Location: include/linux/bottom_half.h:30
Inline: True
```
```
In net/xfrm/espintcp.c (ffffffff81be3fa8)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_rcv
```
```
In net/unix/af_unix.c (ffffffff81be6553)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/ipv6/ip6_output.c (ffffffff81bef10f)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/addrconf.c (ffffffff81bfda5b)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff81c0b42b)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:rt6_probe
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ip6_fib.c (ffffffff81c1029d)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_stop
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81c16dde)
Location: include/linux/bottom_half.h:30
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff81c23517)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2d30a)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81c353b5)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_stop
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In net/ipv6/ioam6.c (ffffffff81c3a204)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
  - net/ipv6/ioam6.c:ioam6_genl_addns
  - net/ipv6/ioam6.c:ioam6_genl_addns
  - net/ipv6/ioam6.c:__rhashtable_remove_fast_one
  - net/ipv6/ioam6.c:__rhashtable_remove_fast_one
  - net/ipv6/ioam6.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/ip6mr.c (ffffffff81c3d25e)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:__rhashtable_remove_fast_one
  - net/ipv6/ip6mr.c:__rhashtable_remove_fast_one
  - net/ipv6/ip6mr.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/seg6_hmac.c (ffffffff81c4b03a)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
  - net/ipv6/seg6_hmac.c:__rhashtable_remove_fast_one
  - net/ipv6/seg6_hmac.c:__rhashtable_remove_fast_one
  - net/ipv6/seg6_hmac.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81c4e577)
Location: include/linux/bottom_half.h:30
Inline: True
```
```
In net/xdp/xsk.c (ffffffff81c7425b)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
  - net/xdp/xsk.c:xsk_release
```
```
In net/mptcp/protocol.c (ffffffff81c7b09e)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:mptcp_sendmsg
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
In arch/x86/kernel/fpu/core.c (ffffffff810538df)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu_flush_thread
  - arch/x86/kernel/fpu/core.c:fpu__clear_user_states
  - arch/x86/kernel/fpu/core.c:fpu_clone
  - arch/x86/kernel/fpu/core.c:fpu_sync_fpstate
  - arch/x86/kernel/fpu/core.c:fpu_swap_kvm_fpstate
  - arch/x86/kernel/fpu/core.c:fpu_update_guest_xfd
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81054e73)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user
  - arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81055fde)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpstate_realloc
```
```
In kernel/irq/manage.c (ffffffff81162948)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_forced_thread_fn
```
```
In kernel/rcu/update.c (ffffffff81172fbe)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_invoke_cbs
```
```
In kernel/rcu/srcutree.c (ffffffff8117753b)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
```
```
In kernel/rcu/tree.c (ffffffff8117e752)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_do_batch
```
```
In kernel/time/hrtimer.c (ffffffff8119c64a)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
```
```
In kernel/bpf/cpumap.c (ffffffff812bd08c)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In kernel/bpf/offload.c (ffffffff812be09a)
Location: include/linux/bottom_half.h:31
Inline: True
```
```
In kernel/padata.c (ffffffff812e9adc)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:invoke_padata_reorder
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_parallel_worker
```
```
In ipc/util.c (ffffffff81593a33)
Location: include/linux/bottom_half.h:31
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffff815ef299)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smk_ipv4_check
  - security/smack/smack_lsm.c:smack_netlbl_add
```
```
In security/apparmor/policy_unpack.c (ffffffff8161d765)
Location: include/linux/bottom_half.h:31
Inline: True
```
```
In lib/rhashtable.c (ffffffff816ea1af)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In lib/irq_poll.c (ffffffff8176efc8)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_cpu_dead
```
```
In drivers/net/tun.c (ffffffff81a678dc)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_alloc_frags
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81a6b74b)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
```
```
In drivers/net/xen-netfront.c (ffffffff81a736e5)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:netfront_resume
```
```
In net/core/skbuff.c (ffffffff81bf80b1)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_frag_align
```
```
In net/core/gen_estimator.c (ffffffff81c0365b)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/dev.c (ffffffff81c1c7cd)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/core/dev.c:napi_threaded_poll
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:flush_backlog
  - net/core/dev.c:__dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/neighbour.c (ffffffff81c225fd)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_seq_stop
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_for_each
  - net/core/neighbour.c:neigh_dump_table
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/filter.c (ffffffff81c43fca)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/core/filter.c:bpf_out_neigh_v6
  - net/core/filter.c:bpf_out_neigh_v6
```
```
In net/core/xdp.c (ffffffff81c50f16)
Location: include/linux/bottom_half.h:31
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff81c70ac3)
Location: include/linux/bottom_half.h:31
Inline: True
```
```
In net/core/sock_map.c (ffffffff81c90419)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_update_elem
```
```
In net/sched/sch_generic.c (ffffffff81c96ee6)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
```
```
In net/netlink/af_netlink.c (ffffffff81cac1e3)
Location: include/linux/bottom_half.h:31
Inline: True
```
```
In net/bpf/test_run.c (ffffffff81cb3d27)
Location: include/linux/bottom_half.h:31
Inline: True
```
```
In net/netfilter/nf_log.c (ffffffff81f0630b)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/netfilter/nf_log.c:nf_log_buf_close
```
```
In net/netfilter/nf_queue.c (ffffffff81ccbca6)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_reinject
```
```
In net/ipv4/route.c (ffffffff81cced0f)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81cd9845)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_hashtables.c (ffffffff81ce2de4)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81ce3a68)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ce525d)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/tcp.c (ffffffff81ceefc6)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_abort
  - net/ipv4/tcp.c:tcp_abort
  - net/ipv4/tcp.c:__tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff81cfcf14)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d07bd0)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81d0ed58)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/icmp.c (ffffffff81d2480e)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_reply
```
```
In net/ipv4/fib_frontend.c (ffffffff81d34d4b)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_lookup
```
```
In net/ipv4/fib_semantics.c (ffffffff81d3ba2b)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/inet_fragment.c (ffffffff81d4195d)
Location: include/linux/bottom_half.h:31
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81d48d2d)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_select_path_hthr
  - net/ipv4/nexthop.c:nexthop_select_path_hthr
```
```
In net/ipv4/ipmr.c (ffffffff81d55f4f)
Location: include/linux/bottom_half.h:31
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d68359)
Location: include/linux/bottom_half.h:31
Inline: True
```
```
In net/xfrm/espintcp.c (ffffffff81d7af44)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff81d877c0)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/addrconf.c (ffffffff81d97425)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff81da6271)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:rt6_probe
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ip6_fib.c (ffffffff81dab4a5)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_stop
```
```
In net/ipv6/icmp.c (ffffffff81dc041d)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dca727)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81dd2d85)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_stop
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In net/ipv6/ioam6.c (ffffffff81dd7f78)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
  - net/ipv6/ioam6.c:ioam6_genl_addns
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/ip6mr.c (ffffffff81ddb694)
Location: include/linux/bottom_half.h:31
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff81dea8a9)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
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
In arch/x86/kernel/fpu/core.c (ffffffff81061680)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear_user_states
  - arch/x86/kernel/fpu/core.c:fpu_reset_fpregs
  - arch/x86/kernel/fpu/core.c:fpu_clone
  - arch/x86/kernel/fpu/core.c:fpu_sync_fpstate
  - arch/x86/kernel/fpu/core.c:fpu_swap_kvm_fpstate
  - arch/x86/kernel/fpu/core.c:fpu_update_guest_xfd
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff810629c9)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user
  - arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff810638aa)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpstate_realloc
```
```
In kernel/irq/manage.c (ffffffff811965b8)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_forced_thread_fn
```
```
In kernel/rcu/update.c (ffffffff811a95ee)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_invoke_cbs
```
```
In kernel/rcu/srcutree.c (ffffffff811aeb6b)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
```
```
In kernel/rcu/tree.c (ffffffff811b95eb)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_do_batch
```
```
In kernel/time/hrtimer.c (ffffffff811db01a)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
```
```
In kernel/bpf/cpumap.c (ffffffff813204ec)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In kernel/padata.c (ffffffff8135391c)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:invoke_padata_reorder
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_parallel_worker
```
```
In security/smack/smack_lsm.c (ffffffff8169f589)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smk_ipv4_check
  - security/smack/smack_lsm.c:smack_netlbl_add
```
```
In lib/irq_poll.c (ffffffff8189ea49)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_cpu_dead
```
```
In drivers/net/tun.c (ffffffff81bf337c)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_alloc_frags
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81bfe62b)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
```
```
In drivers/net/xen-netfront.c (ffffffff81c07975)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:netfront_resume
```
```
In net/core/skbuff.c (ffffffff81da6e68)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_frag_align
  - net/core/skbuff.c:napi_get_frags_check
```
```
In net/core/gen_estimator.c (ffffffff81db2c4b)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/dev.c (ffffffff81dcd84d)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/core/dev.c:napi_threaded_poll
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:flush_backlog
  - net/core/dev.c:__dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/neighbour.c (ffffffff81dd4a4d)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_seq_stop
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_for_each
  - net/core/neighbour.c:neigh_dump_table
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/filter.c (ffffffff81df831a)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/core/filter.c:bpf_out_neigh_v6
  - net/core/filter.c:bpf_out_neigh_v6
```
```
In net/core/lwt_bpf.c (ffffffff81e28af3)
Location: include/linux/bottom_half.h:31
Inline: True
```
```
In net/core/sock_map.c (ffffffff81e4b849)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_update_elem
```
```
In net/sched/sch_generic.c (ffffffff81e52cc6)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
```
```
In net/bpf/test_run.c (ffffffff81e71f6c)
Location: include/linux/bottom_half.h:31
Inline: True
```
```
In net/netfilter/nf_log.c (ffffffff81e8af5c)
Location: include/linux/bottom_half.h:31
Inline: True
```
```
In net/netfilter/nf_queue.c (ffffffff81e8bb15)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_reinject
```
```
In net/ipv4/route.c (ffffffff81e8ef7a)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81e99fc5)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_hashtables.c (ffffffff81ea51ad)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81ea6491)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ea844d)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/tcp.c (ffffffff81eb2324)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_abort
  - net/ipv4/tcp.c:tcp_abort
  - net/ipv4/tcp.c:tcp_abort
  - net/ipv4/tcp.c:__tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff81ec1ad4)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ecd530)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ed4848)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/icmp.c (ffffffff81eebfee)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_reply
```
```
In net/ipv4/fib_frontend.c (ffffffff81efd25b)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_lookup
```
```
In net/ipv4/fib_semantics.c (ffffffff81f0440b)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffffffff81f1231d)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_select_path_hthr
  - net/ipv4/nexthop.c:nexthop_select_path_hthr
```
```
In net/xfrm/xfrm_input.c (ffffffff81f41370)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/espintcp.c (ffffffff81f4801b)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:handle_esp
```
```
In net/ipv6/ip6_output.c (ffffffff81f55540)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/addrconf.c (ffffffff81f6611f)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff81f757e1)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:rt6_probe
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ip6_fib.c (ffffffff81f7ade5)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_stop
```
```
In net/ipv6/icmp.c (ffffffff81f90b8d)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f9b761)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81fa4265)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_stop
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In net/ipv6/seg6_hmac.c (ffffffff81fbe0f9)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
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
In arch/x86/kernel/fpu/core.c (ffffffff81062f54)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear_user_states
  - arch/x86/kernel/fpu/core.c:fpu_reset_fpregs
  - arch/x86/kernel/fpu/core.c:fpu_clone
  - arch/x86/kernel/fpu/core.c:fpu_sync_fpstate
  - arch/x86/kernel/fpu/core.c:fpu_swap_kvm_fpstate
  - arch/x86/kernel/fpu/core.c:fpu_update_guest_xfd
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff810643df)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user
  - arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81065216)
Location: include/linux/bottom_half.h:31
Inline: True
```
```
In kernel/irq/manage.c (ffffffff811a7f78)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_forced_thread_fn
```
```
In kernel/rcu/update.c (ffffffff811bb371)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_invoke_cbs
```
```
In kernel/rcu/srcutree.c (ffffffff811c0b6c)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
```
```
In kernel/rcu/tree.c (ffffffff811cb8fd)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_do_batch
```
```
In kernel/time/hrtimer.c (ffffffff811ef549)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
```
```
In kernel/bpf/cpumap.c (ffffffff8135038a)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In kernel/padata.c (ffffffff81384b1c)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:invoke_padata_reorder
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_parallel_worker
```
```
In security/smack/smack_lsm.c (ffffffff816d7c69)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smk_ipv4_check
  - security/smack/smack_lsm.c:smack_netlbl_add
```
```
In lib/irq_poll.c (ffffffff818e1019)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_cpu_dead
```
```
In drivers/net/tun.c (ffffffff81c4ba3f)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_alloc_frags
```
```
In drivers/net/virtio_net.c (ffffffff81c544c3)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_restore
  - drivers/net/virtio_net.c:virtnet_xdp_set
  - drivers/net/virtio_net.c:virtnet_xdp_set
  - drivers/net/virtio_net.c:virtnet_xdp_set
  - drivers/net/virtio_net.c:virtnet_xdp_set
  - drivers/net/virtio_net.c:virtnet_set_ringparam
  - drivers/net/virtio_net.c:virtnet_set_ringparam
  - drivers/net/virtio_net.c:virtnet_open
  - drivers/net/virtio_net.c:virtnet_open
  - drivers/net/virtio_net.c:refill_work
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81c63c6b)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
```
```
In drivers/net/xen-netfront.c (ffffffff81c6d095)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:netfront_resume
```
```
In drivers/net/net_failover.c (ffffffff81c6fe15)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - drivers/net/net_failover.c:net_failover_close
  - drivers/net/net_failover.c:net_failover_open
```
```
In net/core/sock.c (ffffffff81e08966)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/core/sock.c:sock_i_ino
```
```
In net/core/skbuff.c (ffffffff81e160ba)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_frag_align
  - net/core/skbuff.c:napi_get_frags_check
```
```
In net/core/gen_estimator.c (ffffffff81e2321b)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/dev.c (ffffffff81e3e44a)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/core/dev.c:napi_threaded_poll
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:flush_backlog
  - net/core/dev.c:__dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/neighbour.c (ffffffff81e4b666)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/core/filter.c (ffffffff81e6998c)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/core/filter.c:bpf_out_neigh_v6
  - net/core/filter.c:bpf_out_neigh_v6
```
```
In net/core/lwt_bpf.c (ffffffff81e9e113)
Location: include/linux/bottom_half.h:31
Inline: True
```
```
In net/core/sock_map.c (ffffffff81ea6f70)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_update_elem
```
```
In net/sched/sch_generic.c (ffffffff81eae55c)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
```
```
In net/bpf/test_run.c (ffffffff81ece6a6)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_test_run
```
```
In net/netfilter/nf_log.c (ffffffff81ee8fa8)
Location: include/linux/bottom_half.h:31
Inline: True
```
```
In net/netfilter/nf_queue.c (ffffffff81ee9bbf)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_reinject
```
```
In net/ipv4/inet_hashtables.c (ffffffff81f0393d)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81f04c69)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81f06ccd)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/tcp.c (ffffffff81f109bf)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_abort
  - net/ipv4/tcp.c:tcp_abort
  - net/ipv4/tcp.c:tcp_abort
  - net/ipv4/tcp.c:__tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff81f1ff5e)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f2c1f1)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81f326aa)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/icmp.c (ffffffff81f4bdee)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_reply
```
```
In net/ipv4/fib_frontend.c (ffffffff81f5cca2)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_lookup
```
```
In net/xfrm/xfrm_input.c (ffffffff81fa0c03)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/espintcp.c (ffffffff81fa7b1b)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:handle_esp
```
```
In net/ipv6/addrconf.c (ffffffff81fc622f)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
```
```
In net/ipv6/route.c (ffffffff81fd5886)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route
```
```
In net/ipv6/icmp.c (ffffffff81ff12b8)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffaeb8)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
```
```
In net/ipv6/seg6_hmac.c (ffffffff8201ee26)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
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
In arch/x86/kernel/fpu/core.c (ffffffff8106a240)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear_user_states
  - arch/x86/kernel/fpu/core.c:fpu_reset_fpregs
  - arch/x86/kernel/fpu/core.c:fpu_clone
  - arch/x86/kernel/fpu/core.c:fpu_sync_fpstate
  - arch/x86/kernel/fpu/core.c:fpu_swap_kvm_fpstate
  - arch/x86/kernel/fpu/core.c:fpu_update_guest_xfd
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8106b8c4)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user
  - arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8106c7ea)
Location: include/linux/bottom_half.h:31
Inline: True
```
```
In arch/x86/kernel/shstk.c (ffffffff810cadae)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - arch/x86/kernel/shstk.c:shstk_prctl
  - arch/x86/kernel/shstk.c:wrss_control
  - arch/x86/kernel/shstk.c:restore_signal_shadow_stack
  - arch/x86/kernel/shstk.c:restore_signal_shadow_stack
  - arch/x86/kernel/shstk.c:setup_signal_shadow_stack
  - arch/x86/kernel/shstk.c:setup_signal_shadow_stack
  - arch/x86/kernel/shstk.c:shstk_setup
```
```
In kernel/irq/manage.c (ffffffff811b7ad8)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_forced_thread_fn
```
```
In kernel/rcu/update.c (ffffffff811cb415)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_invoke_cbs
```
```
In kernel/rcu/srcutree.c (ffffffff811d1081)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
```
```
In kernel/rcu/tree.c (ffffffff811de4e4)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - kernel/rcu/tree.c:nocb_cb_wait
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_do_batch
```
```
In kernel/bpf/cpumap.c (ffffffff81377495)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In kernel/padata.c (ffffffff813adf2c)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:invoke_padata_reorder
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_parallel_worker
```
```
In security/smack/smack_lsm.c (ffffffff817147e4)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smk_ipv4_check
  - security/smack/smack_lsm.c:smack_netlbl_add
```
```
In lib/irq_poll.c (ffffffff81927b89)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_cpu_dead
```
```
In drivers/net/tun.c (ffffffff81d010cf)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_rx_batched
  - drivers/net/tun.c:tun_napi_alloc_frags
```
```
In drivers/net/virtio_net.c (ffffffff81d0abed)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_restore
  - drivers/net/virtio_net.c:virtnet_xdp_set
  - drivers/net/virtio_net.c:virtnet_xdp_set
  - drivers/net/virtio_net.c:virtnet_xdp_set
  - drivers/net/virtio_net.c:virtnet_xdp_set
  - drivers/net/virtio_net.c:virtnet_set_ringparam
  - drivers/net/virtio_net.c:virtnet_set_ringparam
  - drivers/net/virtio_net.c:virtnet_open
  - drivers/net/virtio_net.c:virtnet_open
  - drivers/net/virtio_net.c:refill_work
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81d1a684)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
```
```
In drivers/net/xen-netfront.c (ffffffff81d219d2)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:netfront_resume
```
```
In drivers/net/net_failover.c (ffffffff81d246d2)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - drivers/net/net_failover.c:net_failover_close
  - drivers/net/net_failover.c:net_failover_open
```
```
In net/core/sock.c (ffffffff81ec53d6)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/core/sock.c:sock_i_ino
```
```
In net/core/skbuff.c (ffffffff81ed34d3)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_frag_align
  - net/core/skbuff.c:napi_get_frags_check
```
```
In net/core/gen_estimator.c (ffffffff81ee1189)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/dev.c (ffffffff81efccfa)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/core/dev.c:napi_threaded_poll
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:flush_backlog
  - net/core/dev.c:__dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/neighbour.c (ffffffff81f0a386)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/core/filter.c (ffffffff81f28ff9)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/core/filter.c:bpf_out_neigh_v6
  - net/core/filter.c:bpf_out_neigh_v6
```
```
In net/core/lwt_bpf.c (ffffffff81f60893)
Location: include/linux/bottom_half.h:31
Inline: True
```
```
In net/core/sock_map.c (ffffffff81f69a67)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_update_elem
```
```
In net/sched/sch_generic.c (ffffffff81f70fcf)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
```
```
In net/bpf/test_run.c (ffffffff81f91edb)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_test_run
```
```
In net/netfilter/nf_log.c (ffffffff81facddc)
Location: include/linux/bottom_half.h:31
Inline: True
```
```
In net/netfilter/nf_queue.c (ffffffff81fad96f)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_reinject
```
```
In net/ipv4/inet_hashtables.c (ffffffff81fc7bba)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81fc8f71)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81fcafed)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/tcp.c (ffffffff81fd4b9f)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_abort
  - net/ipv4/tcp.c:tcp_abort
  - net/ipv4/tcp.c:tcp_abort
  - net/ipv4/tcp.c:__tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff81fe4637)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff3a04)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ff86bb)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/icmp.c (ffffffff82011baf)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_reply
```
```
In net/ipv4/fib_frontend.c (ffffffff8202321a)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_lookup
```
```
In net/ipv4/tcp_sigpool.c (ffffffff8204c5c3)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/ipv4/tcp_sigpool.c:tcp_sigpool_end
  - net/ipv4/tcp_sigpool.c:tcp_sigpool_start
  - net/ipv4/tcp_sigpool.c:tcp_sigpool_start
  - net/ipv4/tcp_sigpool.c:tcp_sigpool_start
```
```
In net/xfrm/xfrm_input.c (ffffffff8206df63)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/espintcp.c (ffffffff82074d9e)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:handle_esp
```
```
In net/ipv6/addrconf.c (ffffffff82093812)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
```
```
In net/ipv6/route.c (ffffffff820a31df)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route
```
```
In net/ipv6/icmp.c (ffffffff820bee96)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/seg6_hmac.c (ffffffff820edf54)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
```
```
In net/mptcp/protocol.c (ffffffff8214d75e)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_finish_join
```
```
In net/mptcp/subflow.c (ffffffff8214e505)
Location: include/linux/bottom_half.h:31
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_write_space
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
In kernel/irq/manage.c (ffff800010179c4c)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_forced_thread_fn
```
```
In kernel/rcu/update.c (ffff800010188f2c)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/srcutree.c (ffff80001018a8c4)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
```
```
In kernel/rcu/tree.c (ffff8000101905b4)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_cpu_kthread
```
```
In kernel/time/hrtimer.c (ffff8000101a2944)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
```
```
In kernel/bpf/cpumap.c (ffff80001028829c)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In kernel/bpf/offload.c (ffff80001028a268)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In kernel/padata.c (ffff8000102a9c48)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:invoke_padata_reorder
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_parallel_worker
```
```
In ipc/util.c (ffff80001051d52c)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
  - ipc/util.c:ipc_addid
  - ipc/util.c:ipc_addid
```
```
In security/smack/smack_lsm.c (ffff80001056f49c)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_netlabel
```
```
In security/apparmor/policy_unpack.c (ffff800010598a3c)
Location: include/linux/bottom_half.h:30
Inline: True
```
```
In lib/rhashtable.c (ffff800010636bf0)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In drivers/net/tun.c (ffff8000109e14f0)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ethernet/freescale/fec_main.c (ffff8000109ea82c)
Location: include/linux/bottom_half.h:30
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
In drivers/net/ppp/ppp_generic.c (ffff800010a021a0)
Location: include/linux/bottom_half.h:30
Inline: True
```
```
In net/core/sock.c (ffff800010babae8)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/core/sock.c:lock_sock_nested
```
```
In net/core/skbuff.c (ffff800010bb5110)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:netdev_alloc_frag
```
```
In net/core/gen_estimator.c (ffff800010bbf8f4)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/dev.c (ffff800010bd3be4)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:flush_backlog
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/neighbour.c (ffff800010be2ec4)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_seq_stop
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_for_each
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/xdp.c (ffff800010c0680c)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
  - net/core/xdp.c:mem_xa_remove
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffff800010c0880c)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
  - net/core/flow_offload.c:__flow_indr_block_cb_register
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/sched/sch_generic.c (ffff800010c3a12c)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
```
```
In net/netlink/af_netlink.c (ffff800010c4f16c)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/netfilter/nf_log.c (ffff800010c55a5c)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/netfilter/nf_log.c:nf_log_buf_close
```
```
In net/netfilter/nf_queue.c (ffff800010c560f4)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_reinject
```
```
In net/ipv4/route.c (ffff800010c595d4)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffff800010c6369c)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_hashtables.c (ffff800010c6b4b8)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffff800010c6bfc8)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/inet_connection_sock.c (ffff800010c6db00)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/tcp.c (ffff800010c759cc)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (ffff800010c80f6c)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8ad88)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/tcp_minisocks.c (ffff800010c901f8)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/icmp.c (ffff800010ca4d08)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/fib_frontend.c (ffff800010cb39ac)
Location: include/linux/bottom_half.h:30
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffff800010cb9d98)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/inet_fragment.c (ffff800010cbf4f0)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/nexthop.c (ffff800010cc4f54)
Location: include/linux/bottom_half.h:30
Inline: True
```
```
In net/ipv4/ipmr.c (ffff800010ccc248)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffff800010cdcdd0)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/unix/af_unix.c (ffff800010cf0f1c)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/ipv6/ip6_output.c (ffff800010cfa488)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/addrconf.c (ffff800010d012fc)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffff800010d14944)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ip6_fib.c (ffff800010d19cec)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_stop
```
```
In net/ipv6/ipv6_sockglue.c (ffff800010d1f4b8)
Location: include/linux/bottom_half.h:30
Inline: True
```
```
In net/ipv6/icmp.c (ffff800010d2c6dc)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d37c2c)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
```
```
In net/ipv6/ip6_flowlabel.c (ffff800010d3e6a8)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_stop
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In net/ipv6/ip6mr.c (ffff800010d44e94)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffff800010d51ee4)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
```
```
In net/ipv6/inet6_hashtables.c (ffff800010d553c4)
Location: include/linux/bottom_half.h:30
Inline: True
```
```
In net/xdp/xsk.c (ffff800010d7e748)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
  - net/xdp/xsk.c:xsk_release
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
In kernel/irq/manage.c (c03cb1d0)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_forced_thread_fn
```
```
In kernel/rcu/update.c (c03d7804)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/srcutree.c (c03d8300)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
```
```
In kernel/rcu/tree.c (c03de0f4)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_cpu_kthread
```
```
In kernel/time/hrtimer.c (c03ec620)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
```
```
In kernel/bpf/cpumap.c (c04b8590)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In kernel/bpf/offload.c (c04b990c)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In kernel/padata.c (c04d7e8c)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:invoke_padata_reorder
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_parallel_worker
```
```
In ipc/util.c (c06d9948)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
  - ipc/util.c:ipc_addid
  - ipc/util.c:ipc_addid
```
```
In security/smack/smack_lsm.c (c07214e8)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_netlabel
```
```
In security/apparmor/policy_unpack.c (c0749c94)
Location: include/linux/bottom_half.h:30
Inline: True
```
```
In lib/rhashtable.c (c07dc97c)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In drivers/net/tun.c (c0ac6d40)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ethernet/freescale/fec_main.c (c0accc50)
Location: include/linux/bottom_half.h:30
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
In drivers/net/ppp/ppp_generic.c (c0adf2c0)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
```
```
In net/core/sock.c (c0cc820c)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/core/sock.c:lock_sock_nested
```
```
In net/core/skbuff.c (c0cd21e8)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:netdev_alloc_frag
```
```
In net/core/gen_estimator.c (c0cdb3bc)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/dev.c (c0cee914)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:flush_backlog
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/neighbour.c (c0cfd0bc)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_seq_stop
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_for_each
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/xdp.c (c0d1f9bc)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
  - net/core/xdp.c:mem_xa_remove
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (c0d217f0)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
  - net/core/flow_offload.c:__flow_indr_block_cb_register
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/sched/sch_generic.c (c0d4c3ac)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
```
```
In net/netlink/af_netlink.c (c0d5f2d8)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/netfilter/nf_log.c (c0d6547c)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/netfilter/nf_log.c:nf_log_buf_close
```
```
In net/netfilter/nf_queue.c (c0d65b74)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_reinject
```
```
In net/ipv4/route.c (c0d66c04)
Location: include/linux/bottom_half.h:30
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
In net/ipv4/ip_input.c (c0d6db08)
Location: include/linux/bottom_half.h:30
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
In net/ipv4/ip_fragment.c (c0d6f550)
Location: include/linux/bottom_half.h:30
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
In net/ipv4/ip_forward.c (c0d6fd40)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward_finish
```
```
In net/ipv4/ip_output.c (c0d753a8)
Location: include/linux/bottom_half.h:30
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
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_hashtables.c (c0d7a574)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (c0d7adc4)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/inet_connection_sock.c (c0d7c040)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/tcp.c (c0d84064)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (c0d901d8)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
```
In net/ipv4/tcp_ipv4.c (c0d99668)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/tcp_minisocks.c (c0d9e434)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/datagram.c (c0da488c)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (c0da5bfc)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/udp.c (c0da941c)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/icmp.c (c0db0e50)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/fib_frontend.c (c0dbf3ac)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
```
```
In net/ipv4/fib_semantics.c (c0dc5618)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/inet_fragment.c (c0dcae9c)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ping.c (c0dccd28)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/nexthop.c (c0dd0a20)
Location: include/linux/bottom_half.h:30
Inline: True
```
```
In net/ipv4/ipmr.c (c0dd7508)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_delete
  - net/ipv4/ipmr.c:ipmr_mfc_delete
  - net/ipv4/ipmr.c:ipmr_mfc_delete
```
```
In net/xfrm/xfrm_policy.c (c0de7b04)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/unix/af_unix.c (c0df79d0)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/ipv6/ip6_output.c (c0dfeb2c)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:__ip6_flush_pending_frames
  - net/ipv6/ip6_output.c:ip6_send_skb
  - net/ipv6/ip6_output.c:ip6_send_skb
  - net/ipv6/ip6_output.c:__ip6_append_data
  - net/ipv6/ip6_output.c:__ip6_append_data
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
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
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_forward
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
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ip6_input.c (c0e0547c)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
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
In net/ipv6/addrconf.c (c0e08e84)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (c0e12d44)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_pkt_drop
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ip6_fib.c (c0e1ef40)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_stop
```
```
In net/ipv6/ipv6_sockglue.c (c0e2470c)
Location: include/linux/bottom_half.h:30
Inline: True
```
```
In net/ipv6/raw.c (c0e2dd9c)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/icmp.c (c0e305c0)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
```
```
In net/ipv6/mcast.c (c0e33b50)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
```
```
In net/ipv6/reassembly.c (c0e37af4)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_queue
  - net/ipv6/reassembly.c:ip6_frag_queue
  - net/ipv6/reassembly.c:ip6_frag_queue
  - net/ipv6/reassembly.c:ip6_frag_queue
  - net/ipv6/reassembly.c:ip6_frag_expire
  - net/ipv6/reassembly.c:ip6_frag_expire
  - net/ipv6/reassembly.c:ip6_frag_expire
  - net/ipv6/reassembly.c:ip6_frag_expire
```
```
In net/ipv6/tcp_ipv6.c (c0e38848)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
```
```
In net/ipv6/exthdrs.c (c0e3d108)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_hop_jumbo
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
```
```
In net/ipv6/ip6_flowlabel.c (c0e41998)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_stop
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In net/ipv6/ip6mr.c (c0e469cc)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_forward2
  - net/ipv6/ip6mr.c:ip6mr_forward2
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/netfilter.c (c0e4b7a8)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_hmac.c (c0e52fac)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
```
```
In net/ipv6/inet6_hashtables.c (c0e5598c)
Location: include/linux/bottom_half.h:30
Inline: True
```
```
In net/xdp/xsk.c (c0e79160)
Location: include/linux/bottom_half.h:30
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
In kernel/irq/manage.c (c0000000001d4608)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_forced_thread_fn
```
```
In kernel/rcu/update.c (c0000000001e3204)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/srcutree.c (c0000000001e598c)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
```
```
In kernel/rcu/tree.c (c0000000001eb938)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_cpu_kthread
```
```
In kernel/time/hrtimer.c (c000000000203e80)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
```
```
In kernel/bpf/cpumap.c (c000000000333974)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In kernel/bpf/offload.c (c00000000033569c)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In kernel/padata.c (c00000000035cdd0)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:invoke_padata_reorder
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_parallel_worker
```
```
In ipc/util.c (c0000000006666c8)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
  - ipc/util.c:ipc_addid
  - ipc/util.c:ipc_addid
```
```
In security/smack/smack_lsm.c (c0000000006d3484)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_netlabel
```
```
In security/apparmor/policy_unpack.c (c00000000070f9c4)
Location: include/linux/bottom_half.h:30
Inline: True
```
```
In lib/rhashtable.c (c0000000007dcb00)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In drivers/net/tun.c (c000000000aa3204)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (c000000000aaab44)
Location: include/linux/bottom_half.h:30
Inline: True
```
```
In net/core/sock.c (c000000000c7f1d4)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/core/sock.c:lock_sock_nested
```
```
In net/core/skbuff.c (c000000000c8c0b8)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:netdev_alloc_frag
```
```
In net/core/gen_estimator.c (c000000000c98ccc)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/dev.c (c000000000cb298c)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:flush_backlog
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/neighbour.c (c000000000cc296c)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_seq_stop
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_for_each
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/xdp.c (c000000000cf0e4c)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_allocator_disconnect
  - net/core/xdp.c:mem_allocator_disconnect
  - net/core/xdp.c:mem_allocator_disconnect
```
```
In net/core/flow_offload.c (c000000000cf2d2c)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
  - net/core/flow_offload.c:__flow_indr_block_cb_register
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/sched/sch_generic.c (c000000000d331a0)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
```
```
In net/netlink/af_netlink.c (c000000000d4d8ac)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/netfilter/nf_log.c (c000000000d56088)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/netfilter/nf_log.c:nf_log_buf_close
```
```
In net/netfilter/nf_queue.c (c000000000d56994)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_reinject
```
```
In net/ipv4/route.c (c000000000d5b3c4)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (c000000000d669fc)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_hashtables.c (c000000000d70928)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (c000000000d715cc)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/inet_connection_sock.c (c000000000d72f5c)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/tcp.c (c000000000d7d19c)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (c000000000d8be20)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
```
In net/ipv4/tcp_ipv4.c (c000000000d99858)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/tcp_minisocks.c (c000000000d9e1f0)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/icmp.c (c000000000db8130)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/fib_frontend.c (c000000000dca9f8)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_lookup
```
```
In net/ipv4/fib_semantics.c (c000000000dd2efc)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/inet_fragment.c (c000000000dda190)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/nexthop.c (c000000000de12e8)
Location: include/linux/bottom_half.h:30
Inline: True
```
```
In net/ipv4/ipmr.c (c000000000deb4f8)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (c000000000dfcdac)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/unix/af_unix.c (c000000000e148c8)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/ipv6/ip6_output.c (c000000000e1f4b8)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/addrconf.c (c000000000e2b260)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (c000000000e416b8)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ip6_fib.c (c000000000e46fc4)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_stop
```
```
In net/ipv6/ipv6_sockglue.c (c000000000e4dd34)
Location: include/linux/bottom_half.h:30
Inline: True
```
```
In net/ipv6/icmp.c (c000000000e5dfe4)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/tcp_ipv6.c (c000000000e6915c)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
```
```
In net/ipv6/ip6_flowlabel.c (c000000000e72fdc)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_stop
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In net/ipv6/ip6mr.c (c000000000e79728)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (c000000000e8ab3c)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
```
```
In net/ipv6/inet6_hashtables.c (c000000000e8e1d4)
Location: include/linux/bottom_half.h:30
Inline: True
```
```
In net/xdp/xsk.c (c000000000ebe770)
Location: include/linux/bottom_half.h:30
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
In kernel/rcu/update.c (ffffffe00011e29c)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/srcutree.c (ffffffe00011fc3a)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
```
```
In kernel/rcu/tree.c (ffffffe000122fda)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_cpu_kthread
```
```
In kernel/bpf/cpumap.c (ffffffe0001bcf36)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In kernel/bpf/offload.c (ffffffe0001be2ac)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In kernel/padata.c (ffffffe0001d2eee)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:invoke_padata_reorder
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_parallel_worker
```
```
In ipc/util.c (ffffffe000384de2)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
  - ipc/util.c:ipc_addid
  - ipc/util.c:ipc_addid
```
```
In security/smack/smack_lsm.c (ffffffe0003c262c)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_netlabel
```
```
In security/apparmor/policy_unpack.c (ffffffe0003e535a)
Location: include/linux/bottom_half.h:30
Inline: True
```
```
In lib/rhashtable.c (ffffffe0004640a8)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In drivers/net/tun.c (ffffffe00062b038)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (ffffffe00062ebe4)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
```
```
In net/core/sock.c (ffffffe00073f414)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/core/sock.c:lock_sock_nested
```
```
In net/core/skbuff.c (ffffffe0007451e0)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:netdev_alloc_frag
```
```
In net/core/gen_estimator.c (ffffffe00074d2b0)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/dev.c (ffffffe00075dcfe)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:flush_backlog
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/neighbour.c (ffffffe0007679ae)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_seq_stop
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_for_each
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/xdp.c (ffffffe000784cce)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_allocator_disconnect
  - net/core/xdp.c:mem_allocator_disconnect
  - net/core/xdp.c:mem_allocator_disconnect
```
```
In net/core/flow_offload.c (ffffffe0007864d6)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
  - net/core/flow_offload.c:__flow_indr_block_cb_register
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/sched/sch_generic.c (ffffffe0007ab36e)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
```
```
In net/netlink/af_netlink.c (ffffffe0007badf8)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/netfilter/nf_log.c (ffffffe0007bfda2)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/netfilter/nf_log.c:nf_log_buf_close
```
```
In net/netfilter/nf_queue.c (ffffffe0007c03f0)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_reinject
```
```
In net/ipv4/route.c (ffffffe0007c3288)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffe0007caca8)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_hashtables.c (ffffffe0007d10ee)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffe0007d196c)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/inet_connection_sock.c (ffffffe0007d2d68)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/tcp.c (ffffffe0007d8b60)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffe0007e2ebe)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
```
In net/ipv4/tcp_ipv4.c (ffffffe0007ec29e)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/tcp_minisocks.c (ffffffe0007ef6bc)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/icmp.c (ffffffe0007fff98)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/fib_frontend.c (ffffffe00080b79e)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_lookup
```
```
In net/ipv4/fib_semantics.c (ffffffe00081079e)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/inet_fragment.c (ffffffe0008152a6)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/nexthop.c (ffffffe00081a2b2)
Location: include/linux/bottom_half.h:30
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffe000820972)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffe00082c156)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/unix/af_unix.c (ffffffe00083d28a)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/ipv6/ip6_output.c (ffffffe000843e44)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/addrconf.c (ffffffe00084b21e)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffe00085a05a)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ip6_fib.c (ffffffe00085dcd8)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_stop
```
```
In net/ipv6/ipv6_sockglue.c (ffffffe000861bb2)
Location: include/linux/bottom_half.h:30
Inline: True
```
```
In net/ipv6/icmp.c (ffffffe00086c958)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/tcp_ipv6.c (ffffffe00087405a)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
```
```
In net/ipv6/ip6_flowlabel.c (ffffffe00087ac6c)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_stop
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In net/ipv6/ip6mr.c (ffffffe00087f5f2)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffe00088a4b8)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
```
```
In net/ipv6/inet6_hashtables.c (ffffffe00088cb90)
Location: include/linux/bottom_half.h:30
Inline: True
```
```
In net/xdp/xsk.c (ffffffe0008ac160)
Location: include/linux/bottom_half.h:30
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
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff8103eda5)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:fpu__save
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103fa68)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8104071c)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/mm/pkeys.c (ffffffff8108d82a)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:copy_init_pkru_to_fpregs
```
```
In kernel/irq/manage.c (ffffffff8110fd8f)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_forced_thread_fn
```
```
In kernel/rcu/update.c (ffffffff8111c283)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/srcutree.c (ffffffff8111db72)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
```
```
In kernel/rcu/tree.c (ffffffff81121662)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_cpu_kthread
```
```
In kernel/time/hrtimer.c (ffffffff811314e3)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
```
```
In kernel/bpf/cpumap.c (ffffffff811f91f5)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In kernel/bpf/offload.c (ffffffff811fa4cc)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In kernel/padata.c (ffffffff81215ba3)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:invoke_padata_reorder
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_parallel_worker
```
```
In ipc/util.c (ffffffff8142f41a)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
  - ipc/util.c:ipc_addid
  - ipc/util.c:ipc_addid
```
```
In security/smack/smack_lsm.c (ffffffff81475474)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_netlabel
```
```
In security/apparmor/policy_unpack.c (ffffffff8149b29f)
Location: include/linux/bottom_half.h:30
Inline: True
```
```
In lib/rhashtable.c (ffffffff81523ae3)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In drivers/net/tun.c (ffffffff8178aec8)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8178f007)
Location: include/linux/bottom_half.h:30
Inline: True
```
```
In net/core/sock.c (ffffffff818b4471)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/core/sock.c:lock_sock_nested
```
```
In net/core/skbuff.c (ffffffff818badb2)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:netdev_alloc_frag
```
```
In net/core/gen_estimator.c (ffffffff818c40b3)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/dev.c (ffffffff818d5803)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:flush_backlog
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/neighbour.c (ffffffff818e14ee)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_seq_stop
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_for_each
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/xdp.c (ffffffff81902cd7)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
  - net/core/xdp.c:mem_xa_remove
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff81903f13)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
  - net/core/flow_offload.c:__flow_indr_block_cb_register
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/sched/sch_generic.c (ffffffff8192e66b)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
```
```
In net/netlink/af_netlink.c (ffffffff81940877)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/netfilter/nf_log.c (ffffffff81946140)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/netfilter/nf_log.c:nf_log_buf_close
```
```
In net/netfilter/nf_queue.c (ffffffff819466de)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_reinject
```
```
In net/ipv4/route.c (ffffffff8194987c)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff8195260e)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_hashtables.c (ffffffff81959a98)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff8195a2c7)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8195ba28)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/tcp.c (ffffffff81962a27)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff8196e37c)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81977eff)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8197c161)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/icmp.c (ffffffff8198e8e1)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/fib_frontend.c (ffffffff8199b7e6)
Location: include/linux/bottom_half.h:30
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff819a14f7)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/inet_fragment.c (ffffffff819a6451)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/nexthop.c (ffffffff819ab64a)
Location: include/linux/bottom_half.h:30
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff819b23b5)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff819c0d0a)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/unix/af_unix.c (ffffffff819d02da)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/ipv6/ip6_output.c (ffffffff819d6f63)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/addrconf.c (ffffffff819df71a)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff819f00a3)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ip6_fib.c (ffffffff819f4168)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_stop
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff819f9a7e)
Location: include/linux/bottom_half.h:30
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff81a05e0e)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a0d909)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81a152d5)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_stop
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In net/ipv6/ip6mr.c (ffffffff81a1a65b)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a2594c)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a27e67)
Location: include/linux/bottom_half.h:30
Inline: True
```
```
In net/xdp/xsk.c (ffffffff81a4a450)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
  - net/xdp/xsk.c:xsk_release
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
In arch/x86/kernel/fpu/core.c (ffffffff8102e5a5)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:fpu__save
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8102f268)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8102fefc)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/mm/pkeys.c (ffffffff8107c35a)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:copy_init_pkru_to_fpregs
```
```
In kernel/irq/manage.c (ffffffff81100abf)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_forced_thread_fn
```
```
In kernel/rcu/update.c (ffffffff8110d300)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/srcutree.c (ffffffff8110ec06)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
```
```
In kernel/rcu/tree.c (ffffffff81112146)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_nocb_cb_kthread
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_do_batch
```
```
In kernel/time/hrtimer.c (ffffffff81123f47)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
```
```
In kernel/bpf/cpumap.c (ffffffff811ebf45)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In kernel/bpf/offload.c (ffffffff811ed21c)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In kernel/padata.c (ffffffff81208903)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:invoke_padata_reorder
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_parallel_worker
```
```
In ipc/util.c (ffffffff8141fe9a)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
  - ipc/util.c:ipc_addid
  - ipc/util.c:ipc_addid
```
```
In security/smack/smack_lsm.c (ffffffff81465e94)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_netlabel
```
```
In security/apparmor/policy_unpack.c (ffffffff8148bcbf)
Location: include/linux/bottom_half.h:30
Inline: True
```
```
In lib/rhashtable.c (ffffffff81513dc3)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In drivers/net/tun.c (ffffffff8176a818)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81777dd7)
Location: include/linux/bottom_half.h:30
Inline: True
```
```
In net/core/sock.c (ffffffff8186e3c1)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/core/sock.c:lock_sock_nested
```
```
In net/core/skbuff.c (ffffffff81874cfd)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:netdev_alloc_frag
```
```
In net/core/gen_estimator.c (ffffffff8187dff3)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/dev.c (ffffffff8188f673)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:flush_backlog
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/neighbour.c (ffffffff8189b32e)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_seq_stop
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_for_each
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/xdp.c (ffffffff818bcb07)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
  - net/core/xdp.c:mem_xa_remove
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff818bdd43)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
  - net/core/flow_offload.c:__flow_indr_block_cb_register
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/sched/sch_generic.c (ffffffff818e816b)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
```
```
In net/netlink/af_netlink.c (ffffffff818fa367)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/netfilter/nf_log.c (ffffffff818ffc30)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/netfilter/nf_log.c:nf_log_buf_close
```
```
In net/netfilter/nf_queue.c (ffffffff819001ce)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_reinject
```
```
In net/ipv4/route.c (ffffffff8190336c)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff8190c0fe)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_hashtables.c (ffffffff81913588)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81913db7)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81915518)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/tcp.c (ffffffff8191c517)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff81927e6c)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819319bf)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81935c21)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/icmp.c (ffffffff819483a1)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/fib_frontend.c (ffffffff819552a6)
Location: include/linux/bottom_half.h:30
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff8195afb7)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/inet_fragment.c (ffffffff8195ff11)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/nexthop.c (ffffffff8196510a)
Location: include/linux/bottom_half.h:30
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff8196e9e5)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197dafa)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/unix/af_unix.c (ffffffff8198d09a)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/ipv6/ip6_output.c (ffffffff81993d23)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/addrconf.c (ffffffff8199c4da)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff819ace63)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ip6_fib.c (ffffffff819b0f28)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_stop
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff819b683e)
Location: include/linux/bottom_half.h:30
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff819c2bce)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819ca6c9)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff819d2095)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_stop
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In net/ipv6/ip6mr.c (ffffffff819d741b)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff819e270c)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
```
```
In net/ipv6/inet6_hashtables.c (ffffffff819e4c27)
Location: include/linux/bottom_half.h:30
Inline: True
```
```
In net/xdp/xsk.c (ffffffff81a07040)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
  - net/xdp/xsk.c:xsk_release
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
In arch/x86/kernel/fpu/core.c (ffffffff8103ebe5)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:fpu__save
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103f8a8)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8104055c)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/mm/pkeys.c (ffffffff8108d7da)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:copy_init_pkru_to_fpregs
```
```
In kernel/irq/manage.c (ffffffff8110dc7f)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_forced_thread_fn
```
```
In kernel/rcu/update.c (ffffffff8111a173)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/srcutree.c (ffffffff8111ba62)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
```
```
In kernel/rcu/tree.c (ffffffff8111f552)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_cpu_kthread
```
```
In kernel/time/hrtimer.c (ffffffff8112f203)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
```
```
In kernel/bpf/cpumap.c (ffffffff811f6fc5)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In kernel/bpf/offload.c (ffffffff811f829c)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In kernel/padata.c (ffffffff81213943)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:invoke_padata_reorder
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_parallel_worker
```
```
In ipc/util.c (ffffffff8142b5ba)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
  - ipc/util.c:ipc_addid
  - ipc/util.c:ipc_addid
```
```
In security/smack/smack_lsm.c (ffffffff81471514)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_netlabel
```
```
In security/apparmor/policy_unpack.c (ffffffff8149733f)
Location: include/linux/bottom_half.h:30
Inline: True
```
```
In lib/rhashtable.c (ffffffff8151fb73)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In drivers/net/tun.c (ffffffff817bb268)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817bf3a7)
Location: include/linux/bottom_half.h:30
Inline: True
```
```
In net/core/sock.c (ffffffff81905471)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/core/sock.c:lock_sock_nested
```
```
In net/core/skbuff.c (ffffffff8190bdb2)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:netdev_alloc_frag
```
```
In net/core/gen_estimator.c (ffffffff819150b3)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/dev.c (ffffffff81926833)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:flush_backlog
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/neighbour.c (ffffffff8193251e)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_seq_stop
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_for_each
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/xdp.c (ffffffff81953d07)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
  - net/core/xdp.c:mem_xa_remove
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff81954f43)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
  - net/core/flow_offload.c:__flow_indr_block_cb_register
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/sched/sch_generic.c (ffffffff8197f7fb)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
```
```
In net/netlink/af_netlink.c (ffffffff81991a07)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/netfilter/nf_log.c (ffffffff819972d0)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/netfilter/nf_log.c:nf_log_buf_close
```
```
In net/netfilter/nf_queue.c (ffffffff8199786e)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_reinject
```
```
In net/netfilter/nfnetlink_log.c (ffffffff8199b3b5)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/netfilter/nfnetlink_log.c:seq_stop
  - net/netfilter/nfnetlink_log.c:instance_lookup_get
```
```
In net/netfilter/nf_conntrack_core.c (ffffffff819a080a)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_core.c:nf_conntrack_hash_resize
  - net/netfilter/nf_conntrack_core.c:nf_ct_iterate_cleanup
  - net/netfilter/nf_conntrack_core.c:nf_ct_iterate_cleanup
  - net/netfilter/nf_conntrack_core.c:__nf_conntrack_confirm
  - net/netfilter/nf_conntrack_core.c:__nf_conntrack_confirm
  - net/netfilter/nf_conntrack_core.c:__nf_conntrack_confirm
  - net/netfilter/nf_conntrack_core.c:nf_conntrack_hash_check_insert
  - net/netfilter/nf_conntrack_core.c:nf_conntrack_hash_check_insert
  - net/netfilter/nf_conntrack_core.c:nf_ct_delete_from_lists
  - net/netfilter/nf_conntrack_core.c:destroy_conntrack
```
```
In net/netfilter/nf_conntrack_ecache.c (ffffffff819a9326)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_ecache.c:ecache_work
```
```
In net/netfilter/nf_conntrack_netlink.c (ffffffff819b0af4)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_dump_table
```
```
In net/ipv4/route.c (ffffffff819b404c)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff819bcdde)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_hashtables.c (ffffffff819c4268)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff819c4a97)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819c61f8)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/tcp.c (ffffffff819cd1f7)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff819d8b4c)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819e26cf)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819e6931)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/icmp.c (ffffffff819f9181)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/fib_frontend.c (ffffffff81a06086)
Location: include/linux/bottom_half.h:30
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff81a0bd97)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/inet_fragment.c (ffffffff81a10cf1)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/nexthop.c (ffffffff81a15eea)
Location: include/linux/bottom_half.h:30
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81a1cc55)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/netfilter/nf_defrag_ipv4.c (ffffffff81a20c93)
Location: include/linux/bottom_half.h:30
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a2b78a)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/unix/af_unix.c (ffffffff81a3ad5a)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/ipv6/ip6_output.c (ffffffff81a419e3)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/addrconf.c (ffffffff81a4a19a)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff81a5ab23)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ip6_fib.c (ffffffff81a5ebe8)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_stop
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81a644fe)
Location: include/linux/bottom_half.h:30
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff81a7088e)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a78389)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81a7fd55)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_stop
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In net/ipv6/ip6mr.c (ffffffff81a850db)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a903cc)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a93a17)
Location: include/linux/bottom_half.h:30
Inline: True
```
```
In net/xdp/xsk.c (ffffffff81ab6300)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
  - net/xdp/xsk.c:xsk_release
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
In arch/x86/kernel/fpu/core.c (ffffffff8103fe90)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:fpu__save
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81040f18)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81041932)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/mm/pkeys.c (ffffffff8108fba1)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:copy_init_pkru_to_fpregs
```
```
In kernel/irq/manage.c (ffffffff81118f6f)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_forced_thread_fn
```
```
In kernel/rcu/update.c (ffffffff811258cb)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/srcutree.c (ffffffff81125fb0)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
```
```
In kernel/rcu/tree.c (ffffffff8112b6a6)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_cpu_kthread
```
```
In kernel/time/hrtimer.c (ffffffff8113bc1e)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
```
```
In kernel/bpf/cpumap.c (ffffffff812052a9)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In kernel/bpf/offload.c (ffffffff8120660f)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In kernel/padata.c (ffffffff81222901)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:invoke_padata_reorder
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_parallel_worker
```
```
In ipc/util.c (ffffffff8144255e)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
  - ipc/util.c:ipc_addid
  - ipc/util.c:ipc_addid
```
```
In security/smack/smack_lsm.c (ffffffff81488e02)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_netlabel
```
```
In security/apparmor/policy_unpack.c (ffffffff814af42b)
Location: include/linux/bottom_half.h:30
Inline: True
```
```
In lib/rhashtable.c (ffffffff8153946c)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In drivers/net/tun.c (ffffffff817d42a3)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817d9637)
Location: include/linux/bottom_half.h:30
Inline: True
```
```
In net/core/sock.c (ffffffff819240aa)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/core/sock.c:lock_sock_nested
```
```
In net/core/skbuff.c (ffffffff8192ced2)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:netdev_alloc_frag
```
```
In net/core/gen_estimator.c (ffffffff81936233)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/dev.c (ffffffff81947e3f)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:flush_backlog
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/neighbour.c (ffffffff81953bed)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_seq_stop
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_for_each
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/xdp.c (ffffffff8197549b)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/core/xdp.c:mem_xa_remove
  - net/core/xdp.c:mem_xa_remove
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff81976f40)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
  - net/core/flow_offload.c:__flow_indr_block_cb_register
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/sched/sch_generic.c (ffffffff819a1d57)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
```
```
In net/netlink/af_netlink.c (ffffffff819b44f7)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/netfilter/nf_log.c (ffffffff819b9fa0)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/netfilter/nf_log.c:nf_log_buf_close
```
```
In net/netfilter/nf_queue.c (ffffffff819ba54e)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_reinject
```
```
In net/ipv4/route.c (ffffffff819bd73c)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff819c66ee)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_hashtables.c (ffffffff819cdcd8)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff819ce530)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819cfdb6)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/tcp.c (ffffffff819d6d85)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff819e27a8)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819ec41f)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_hdr
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819f05f1)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/icmp.c (ffffffff81a03052)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/fib_frontend.c (ffffffff81a106ea)
Location: include/linux/bottom_half.h:30
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff81a16587)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/inet_fragment.c (ffffffff81a1b5e1)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/nexthop.c (ffffffff81a2092a)
Location: include/linux/bottom_half.h:30
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81a27bbc)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a36dea)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/unix/af_unix.c (ffffffff81a45fd8)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/ipv6/ip6_output.c (ffffffff81a4d643)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/addrconf.c (ffffffff81a560da)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff81a66dcf)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ip6_fib.c (ffffffff81a6b068)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_stop
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81a70a14)
Location: include/linux/bottom_half.h:30
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff81a7ceac)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a84af9)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81a8c615)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_stop
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In net/ipv6/ip6mr.c (ffffffff81a919f6)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a9cfdf)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a9fb67)
Location: include/linux/bottom_half.h:30
Inline: True
```
```
In net/xdp/xsk.c (ffffffff81ac2420)
Location: include/linux/bottom_half.h:30
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
  - net/xdp/xsk.c:xsk_release
```
</details>
</li>
</ul>

## Differences
