# Function: <code>__local_bh_disable_ip</code>

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
In kernel/softirq.c (ffffffff810858bd)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:irq_enter
```
```
In kernel/sched/core.c (ffffffff81820676)
Location: include/linux/bottom_half.h:9
Inline: True
```
```
In kernel/locking/spinlock.c (ffffffff81823fe6)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_spin_lock_bh
  - kernel/locking/spinlock.c:_raw_spin_trylock_bh
  - kernel/locking/spinlock.c:_raw_write_lock_bh
  - kernel/locking/spinlock.c:_raw_read_lock_bh
```
```
In kernel/irq/manage.c (ffffffff810dbb16)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_forced_thread_fn
```
```
In kernel/rcu/srcu.c (ffffffff810e3f41)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - kernel/rcu/srcu.c:process_srcu
```
```
In kernel/padata.c (ffffffff811898e6)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_parallel_worker
  - kernel/padata.c:padata_serial_worker
```
```
In security/smack/smack_lsm.c (ffffffff8135e4a6)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_netlabel
```
```
In crypto/chainiv.c (ffffffff813a2340)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - crypto/chainiv.c:async_chainiv_do_postponed
```
```
In drivers/net/virtio_net.c (ffffffff815f1967)
Location: include/linux/bottom_half.h:9
Inline: True
```
```
In net/socket.c (ffffffff816fdfc8)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/socket.c:sock_poll
```
```
In net/core/datagram.c (ffffffff8170cc65)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_recv_datagram
```
```
In net/core/dev.c (ffffffff8171cd9f)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/dst.c (ffffffff81723865)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/core/dst.c:dst_init
  - net/core/dst.c:dst_destroy
```
```
In net/core/neighbour.c (ffffffff81724460)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_for_each
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_seq_start
  - net/core/neighbour.c:neigh_lookup
  - net/core/neighbour.c:neigh_dump_info
```
```
In net/core/flow.c (ffffffff81734779)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_lookup
  - net/core/flow.c:flow_cache_flush
```
```
In net/sched/sch_generic.c (ffffffff81741c3e)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
```
```
In net/netlink/af_netlink.c (ffffffff8174b708)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/netfilter/nf_log.c (ffffffff817522bc)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/netfilter/nf_log.c:nf_log_buf_open
```
```
In net/netfilter/nf_queue.c (ffffffff81752a13)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_reinject
```
```
In net/ipv4/route.c (ffffffff81754153)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_cpu_seq_show
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/ip_fragment.c (ffffffff8175a676)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_mem
```
```
In net/ipv4/ip_output.c (ffffffff8175d053)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_hashtables.c (ffffffff817623f6)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_put_port
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff817638c2)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81763bc0)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/tcp.c (ffffffff8176590d)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_init_sock
  - net/ipv4/tcp.c:tcp_prequeue_process
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff81770791)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
```
In net/ipv4/icmp.c (ffffffff8178e5b1)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_send
```
```
In net/ipv4/fib_frontend.c (ffffffff8179a163)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
```
```
In net/ipv4/inet_fragment.c (ffffffff817a1b19)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_worker
  - net/ipv4/inet_fragment.c:inet_frags_exit_net
```
```
In net/ipv4/proc.c (ffffffff817a5f80)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/ipv4/proc.c:sockstat_seq_show
```
```
In net/ipv4/xfrm4_policy.c (ffffffff817af417)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_garbage_collect
```
```
In net/unix/af_unix.c (ffffffff817be096)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/ipv6/ip6_output.c (ffffffff817c517a)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/addrconf.c (ffffffff817c9381)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:if6_seq_start
  - net/ipv6/addrconf.c:ipv6_regen_rndid
  - net/ipv6/addrconf.c:ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
```
```
In net/ipv6/route.c (ffffffff817d3ec5)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_dst_gc
  - net/ipv6/route.c:rt6_stats_seq_show
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ip6_fib.c (ffffffff817d9c8f)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_start
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff817ddde7)
Location: include/linux/bottom_half.h:9
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff817e79e3)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_echo_reply
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff817f5c76)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
  - net/ipv6/ip6_flowlabel.c:fl_lookup
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
```
```
In net/ipv6/proc.c (ffffffff817feac6)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/ipv6/proc.c:sockstat6_seq_show
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81802293)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup
```
```
In net/packet/af_packet.c (ffffffff818037b5)
Location: include/linux/bottom_half.h:9
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
In kernel/softirq.c (ffffffff81088a2c)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - kernel/softirq.c:irq_enter
  - kernel/softirq.c:__do_softirq
```
```
In kernel/sched/core.c (ffffffff8189aad7)
Location: include/linux/bottom_half.h:9
Inline: True
```
```
In kernel/locking/spinlock.c (ffffffff8189ee35)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_lock_bh
  - kernel/locking/spinlock.c:_raw_read_lock_bh
  - kernel/locking/spinlock.c:_raw_spin_trylock_bh
  - kernel/locking/spinlock.c:_raw_spin_lock_bh
```
```
In kernel/irq/manage.c (ffffffff810e0e56)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_forced_thread_fn
```
```
In kernel/rcu/update.c (ffffffff810e967b)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/srcu.c (ffffffff810ea249)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - kernel/rcu/srcu.c:process_srcu
```
```
In kernel/padata.c (ffffffff8119c1f2)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_parallel_worker
```
```
In security/smack/smack_lsm.c (ffffffff813945fd)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_netlabel
```
```
In drivers/net/virtio_net.c (ffffffff81651278)
Location: include/linux/bottom_half.h:9
Inline: True
```
```
In net/core/dev.c (ffffffff817833f0)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/core/dev.c:sk_busy_loop
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/dst.c (ffffffff8178d991)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/core/dst.c:dst_destroy
  - net/core/dst.c:dst_init
```
```
In net/core/neighbour.c (ffffffff8178f039)
Location: include/linux/bottom_half.h:9
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
In net/core/flow.c (ffffffff817a142e)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_flush
  - net/core/flow.c:flow_cache_lookup
```
```
In net/sched/sch_generic.c (ffffffff817aeaee)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
```
```
In net/netlink/af_netlink.c (ffffffff817ba21e)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_create
```
```
In net/netfilter/nf_log.c (ffffffff817be2cc)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/netfilter/nf_log.c:nf_log_buf_open
```
```
In net/netfilter/nf_queue.c (ffffffff817beb23)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_reinject
```
```
In net/ipv4/route.c (ffffffff817c3650)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:rt_cpu_seq_show
```
```
In net/ipv4/ip_fragment.c (ffffffff817c6a36)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_mem
```
```
In net/ipv4/ip_output.c (ffffffff817c9e13)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_hashtables.c (ffffffff817ce7a1)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff817cfd96)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/inet_connection_sock.c (ffffffff817d11dd)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
```
```
In net/ipv4/tcp.c (ffffffff817d6db2)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_ipv4.c (ffffffff817ea45e)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/icmp.c (ffffffff817fbbbd)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_send
```
```
In net/ipv4/fib_frontend.c (ffffffff81808040)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
```
```
In net/ipv4/fib_semantics.c (ffffffff8180bfd6)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/inet_fragment.c (ffffffff8180fa52)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frags_exit_net
  - net/ipv4/inet_fragment.c:inet_frag_worker
```
```
In net/ipv4/proc.c (ffffffff81813c20)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/ipv4/proc.c:sockstat_seq_show
```
```
In net/ipv4/xfrm4_policy.c (ffffffff8181c317)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_garbage_collect
```
```
In net/unix/af_unix.c (ffffffff8182b02a)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/ipv6/ip6_output.c (ffffffff81831d6a)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/addrconf.c (ffffffff818390b6)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:if6_seq_start
  - net/ipv6/addrconf.c:ipv6_regen_rndid
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
```
```
In net/ipv6/route.c (ffffffff81842e7e)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_stats_seq_show
  - net/ipv6/route.c:ip6_dst_gc
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ip6_fib.c (ffffffff81847df9)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_start
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff8184be6f)
Location: include/linux/bottom_half.h:9
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff8185683e)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81864d56)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In net/ipv6/proc.c (ffffffff8186e456)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/ipv6/proc.c:sockstat6_seq_show
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81872f6e)
Location: include/linux/bottom_half.h:9
Inline: True
```
```
In net/packet/af_packet.c (ffffffff818749f5)
Location: include/linux/bottom_half.h:9
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
In kernel/softirq.c (ffffffff8108d978)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - kernel/softirq.c:irq_enter
  - kernel/softirq.c:__do_softirq
```
```
In kernel/sched/core.c (ffffffff818cf0dd)
Location: include/linux/bottom_half.h:9
Inline: True
```
```
In kernel/locking/spinlock.c (ffffffff818d42f5)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_lock_bh
  - kernel/locking/spinlock.c:_raw_read_lock_bh
  - kernel/locking/spinlock.c:_raw_spin_trylock_bh
  - kernel/locking/spinlock.c:_raw_spin_lock_bh
```
```
In kernel/irq/manage.c (ffffffff810e7da6)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_forced_thread_fn
```
```
In kernel/rcu/update.c (ffffffff810f053a)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/srcu.c (ffffffff810f1129)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - kernel/rcu/srcu.c:process_srcu
```
```
In kernel/padata.c (ffffffff811aba62)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_parallel_worker
```
```
In security/smack/smack_lsm.c (ffffffff813ab13d)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_netlabel
```
```
In drivers/net/tun.c (ffffffff8167f9b2)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81685ce6)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_channel_push
```
```
In net/core/dev.c (ffffffff817aed49)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/core/dev.c:sk_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:flush_backlog
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/dst.c (ffffffff817bb261)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/core/dst.c:dst_destroy
  - net/core/dst.c:dst_init
```
```
In net/core/neighbour.c (ffffffff817bc8f6)
Location: include/linux/bottom_half.h:9
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
In net/core/flow.c (ffffffff817cfd48)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_flush
  - net/core/flow.c:flow_cache_lookup
```
```
In net/sched/sch_generic.c (ffffffff817de16e)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
```
```
In net/netlink/af_netlink.c (ffffffff817e9c3c)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_create
```
```
In net/netfilter/nf_log.c (ffffffff817edc0c)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/netfilter/nf_log.c:nf_log_buf_open
```
```
In net/netfilter/nf_queue.c (ffffffff817ee467)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_reinject
```
```
In net/ipv4/route.c (ffffffff817f2c78)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:rt_cpu_seq_show
```
```
In net/ipv4/ip_fragment.c (ffffffff817f6536)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_mem
```
```
In net/ipv4/ip_output.c (ffffffff817f90fb)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_hashtables.c (ffffffff817fe5b1)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff817ffb86)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8180109d)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
```
```
In net/ipv4/tcp.c (ffffffff81806dd2)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_input.c (ffffffff81810990)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81818c56)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/icmp.c (ffffffff8182cb0d)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_send
```
```
In net/ipv4/fib_frontend.c (ffffffff81839110)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
```
```
In net/ipv4/fib_semantics.c (ffffffff8183d0f6)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/inet_fragment.c (ffffffff81840fa2)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frags_exit_net
  - net/ipv4/inet_fragment.c:inet_frag_worker
```
```
In net/ipv4/proc.c (ffffffff8184511d)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/ipv4/proc.c:sockstat_seq_show
```
```
In net/ipv4/xfrm4_policy.c (ffffffff8184dbd7)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_garbage_collect
```
```
In net/unix/af_unix.c (ffffffff8185ca5a)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/ipv6/ip6_output.c (ffffffff81863d0e)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/addrconf.c (ffffffff8186aad6)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:if6_seq_start
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
```
```
In net/ipv6/route.c (ffffffff81874bfb)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_stats_seq_show
  - net/ipv6/route.c:ip6_dst_gc
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ip6_fib.c (ffffffff81879c36)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_start
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff8187dd22)
Location: include/linux/bottom_half.h:9
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff81888640)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81897436)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In net/ipv6/proc.c (ffffffff818a1326)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/ipv6/proc.c:sockstat6_seq_show
```
```
In net/ipv6/seg6_hmac.c (ffffffff818a4a2e)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
```
```
In net/ipv6/inet6_hashtables.c (ffffffff818a7594)
Location: include/linux/bottom_half.h:9
Inline: True
```
```
In net/packet/af_packet.c (ffffffff818a8f45)
Location: include/linux/bottom_half.h:9
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
In kernel/softirq.c (ffffffff8108a9a8)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - kernel/softirq.c:irq_enter
  - kernel/softirq.c:__do_softirq
```
```
In kernel/sched/core.c (ffffffff8190663f)
Location: include/linux/bottom_half.h:9
Inline: True
```
```
In kernel/locking/spinlock.c (ffffffff8190b495)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_lock_bh
  - kernel/locking/spinlock.c:_raw_read_lock_bh
  - kernel/locking/spinlock.c:_raw_spin_trylock_bh
  - kernel/locking/spinlock.c:_raw_spin_lock_bh
```
```
In kernel/irq/manage.c (ffffffff810e6c66)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_forced_thread_fn
```
```
In kernel/rcu/update.c (ffffffff810f0546)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/srcutree.c (ffffffff810f18bb)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
```
```
In kernel/padata.c (ffffffff811b2ec2)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_parallel_worker
```
```
In security/smack/smack_lsm.c (ffffffff813c1a54)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_netlabel
```
```
In drivers/net/tun.c (ffffffff81694c9e)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8169b206)
Location: include/linux/bottom_half.h:9
Inline: True
```
```
In net/core/dev.c (ffffffff817cd697)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:flush_backlog
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/neighbour.c (ffffffff817dafc6)
Location: include/linux/bottom_half.h:9
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
In net/core/flow.c (ffffffff817ef146)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_flush
  - net/core/flow.c:flow_cache_lookup
```
```
In net/sched/sch_generic.c (ffffffff817fd7be)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
```
```
In net/netlink/af_netlink.c (ffffffff8180981a)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_create
```
```
In net/netfilter/nf_log.c (ffffffff8180dc3c)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/netfilter/nf_log.c:nf_log_buf_open
```
```
In net/netfilter/nf_queue.c (ffffffff8180e4f9)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_reinject
```
```
In net/ipv4/route.c (ffffffff818102ba)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81819513)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_hashtables.c (ffffffff8181ebf1)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff8181fd71)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81820e09)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/tcp.c (ffffffff818274b7)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff81830be3)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8183b374)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/icmp.c (ffffffff8184df25)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_send
```
```
In net/ipv4/fib_frontend.c (ffffffff8185a612)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
```
```
In net/ipv4/fib_semantics.c (ffffffff8185e7ab)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/inet_fragment.c (ffffffff81862832)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frags_exit_net
  - net/ipv4/inet_fragment.c:inet_frag_worker
```
```
In net/unix/af_unix.c (ffffffff818811e8)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/ipv6/ip6_output.c (ffffffff818892c6)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/addrconf.c (ffffffff8188f046)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:if6_seq_start
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff81899bda)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ip6_fib.c (ffffffff8189f696)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_start
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff818a32a2)
Location: include/linux/bottom_half.h:9
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff818aed98)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff818bd846)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In net/ipv6/seg6_hmac.c (ffffffff818cb209)
Location: include/linux/bottom_half.h:9
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
```
```
In net/ipv6/inet6_hashtables.c (ffffffff818cde96)
Location: include/linux/bottom_half.h:9
Inline: True
```
```
In net/packet/af_packet.c (ffffffff818cf92c)
Location: include/linux/bottom_half.h:9
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
In kernel/softirq.c (ffffffff81091678)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/softirq.c:irq_enter
  - kernel/softirq.c:__do_softirq
```
```
In kernel/sched/core.c (ffffffff819906cc)
Location: include/linux/bottom_half.h:10
Inline: True
```
```
In kernel/locking/spinlock.c (ffffffff81995816)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_lock_bh
  - kernel/locking/spinlock.c:_raw_read_lock_bh
  - kernel/locking/spinlock.c:_raw_spin_trylock_bh
  - kernel/locking/spinlock.c:_raw_spin_lock_bh
```
```
In kernel/irq/manage.c (ffffffff810eef36)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_forced_thread_fn
```
```
In kernel/rcu/update.c (ffffffff810fa20c)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/srcutree.c (ffffffff810fb61b)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
```
```
In kernel/bpf/cpumap.c (ffffffff811afcd8)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In kernel/padata.c (ffffffff811c6b12)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:invoke_padata_reorder
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_parallel_worker
```
```
In security/smack/smack_lsm.c (ffffffff813e80f4)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_netlabel
```
```
In drivers/net/tun.c (ffffffff816ff5db)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817059f6)
Location: include/linux/bottom_half.h:10
Inline: True
```
```
In net/core/gen_estimator.c (ffffffff8183bdbc)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/dev.c (ffffffff81846dba)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:flush_backlog
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/neighbour.c (ffffffff81855776)
Location: include/linux/bottom_half.h:10
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
In net/sched/sch_generic.c (ffffffff8187b3aa)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
```
```
In net/netlink/af_netlink.c (ffffffff81888760)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_create
```
```
In net/netfilter/nf_log.c (ffffffff8188d11c)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/netfilter/nf_log.c:nf_log_buf_open
```
```
In net/netfilter/nf_queue.c (ffffffff8188dafb)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_reinject
```
```
In net/ipv4/route.c (ffffffff8188f30e)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81897b23)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_hashtables.c (ffffffff8189dba1)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff8189ed3e)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/inet_connection_sock.c (ffffffff818a0377)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/tcp.c (ffffffff818a62c3)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff818b004c)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
```
In net/ipv4/tcp_ipv4.c (ffffffff818bb084)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/tcp_minisocks.c (ffffffff818bddce)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/icmp.c (ffffffff818cdc45)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_send
```
```
In net/ipv4/fib_frontend.c (ffffffff818da532)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
```
```
In net/ipv4/fib_semantics.c (ffffffff818de80f)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/inet_fragment.c (ffffffff818e2952)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frags_exit_net
  - net/ipv4/inet_fragment.c:inet_frag_worker
```
```
In net/xfrm/xfrm_policy.c (ffffffff818f842c)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup
  - net/xfrm/xfrm_policy.c:xfrm_lookup
  - net/xfrm/xfrm_policy.c:xfrm_policy_cache_flush
  - net/xfrm/xfrm_policy.c:xfrm_pcpu_work_fn
```
```
In net/unix/af_unix.c (ffffffff81902378)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/ipv6/ip6_output.c (ffffffff81909706)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/addrconf.c (ffffffff81910696)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff8191dcee)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:rt6_age_exceptions
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ip6_fib.c (ffffffff81921c96)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_start
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81925e57)
Location: include/linux/bottom_half.h:10
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff81931a9b)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff819408e6)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In net/ipv6/seg6_hmac.c (ffffffff8194ffa9)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81952cb6)
Location: include/linux/bottom_half.h:10
Inline: True
```
```
In net/packet/af_packet.c (ffffffff8195489f)
Location: include/linux/bottom_half.h:10
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
In kernel/softirq.c (ffffffff81095148)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/softirq.c:irq_enter
  - kernel/softirq.c:__do_softirq
```
```
In kernel/locking/spinlock.c (ffffffff819f1d55)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_lock_bh
  - kernel/locking/spinlock.c:_raw_read_lock_bh
  - kernel/locking/spinlock.c:_raw_spin_trylock_bh
  - kernel/locking/spinlock.c:_raw_spin_lock_bh
```
```
In kernel/irq/manage.c (ffffffff810f7665)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_forced_thread_fn
```
```
In kernel/rcu/update.c (ffffffff8110279a)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/srcutree.c (ffffffff81103a98)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
```
```
In kernel/time/hrtimer.c (ffffffff81116c8b)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
```
```
In kernel/bpf/cpumap.c (ffffffff811cab18)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In kernel/padata.c (ffffffff811e74e2)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:invoke_padata_reorder
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_parallel_worker
```
```
In security/smack/smack_lsm.c (ffffffff81418f2d)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_netlabel
```
```
In drivers/net/tun.c (ffffffff8173edc4)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81744ea5)
Location: include/linux/bottom_half.h:10
Inline: True
```
```
In net/core/gen_estimator.c (ffffffff8188653c)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/dev.c (ffffffff818904a4)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:flush_backlog
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/neighbour.c (ffffffff818a0d2f)
Location: include/linux/bottom_half.h:10
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
In net/sched/sch_generic.c (ffffffff818cd85a)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
```
```
In net/netlink/af_netlink.c (ffffffff818dc193)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_create
```
```
In net/netfilter/nf_log.c (ffffffff818e0b5c)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/netfilter/nf_log.c:nf_log_buf_open
```
```
In net/netfilter/nf_queue.c (ffffffff818e17d7)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_reinject
```
```
In net/ipv4/route.c (ffffffff818e36ef)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff818ebe53)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_hashtables.c (ffffffff818f1d45)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff818f3792)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/inet_connection_sock.c (ffffffff818f56d1)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/tcp.c (ffffffff818fb334)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff819055a3)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8191067c)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8191280e)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/icmp.c (ffffffff819243df)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_send
```
```
In net/ipv4/fib_frontend.c (ffffffff81930f95)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
```
```
In net/ipv4/fib_semantics.c (ffffffff8193537f)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/xfrm/xfrm_policy.c (ffffffff8194ef17)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup
  - net/xfrm/xfrm_policy.c:xfrm_lookup
  - net/xfrm/xfrm_policy.c:xfrm_policy_cache_flush
  - net/xfrm/xfrm_policy.c:xfrm_pcpu_work_fn
```
```
In net/unix/af_unix.c (ffffffff81959cc8)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/ipv6/ip6_output.c (ffffffff81960a19)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/addrconf.c (ffffffff81967ab5)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff8197655c)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:rt6_age_exceptions
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ip6_fib.c (ffffffff8197a086)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_start
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff8197eb2a)
Location: include/linux/bottom_half.h:10
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff8198a552)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff819997df)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In net/ipv6/seg6_hmac.c (ffffffff819a96e2)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
```
```
In net/ipv6/inet6_hashtables.c (ffffffff819ac254)
Location: include/linux/bottom_half.h:10
Inline: True
```
```
In net/xdp/xsk.c (ffffffff819cbf12)
Location: include/linux/bottom_half.h:10
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
In arch/x86/kernel/fpu/signal.c (ffffffff8103cba5)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
```
In kernel/softirq.c (ffffffff8109d4b8)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/softirq.c:irq_enter
  - kernel/softirq.c:__do_softirq
```
```
In kernel/locking/spinlock.c (ffffffff81a2d305)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_lock_bh
  - kernel/locking/spinlock.c:_raw_read_lock_bh
  - kernel/locking/spinlock.c:_raw_spin_trylock_bh
  - kernel/locking/spinlock.c:_raw_spin_lock_bh
```
```
In kernel/irq/manage.c (ffffffff81102a95)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_forced_thread_fn
```
```
In kernel/rcu/update.c (ffffffff8110e1a2)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/srcutree.c (ffffffff8110f458)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
```
```
In kernel/time/hrtimer.c (ffffffff811222cb)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
```
```
In kernel/bpf/cpumap.c (ffffffff811de418)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In kernel/padata.c (ffffffff811f8402)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:invoke_padata_reorder
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_parallel_worker
```
```
In security/smack/smack_lsm.c (ffffffff8143561f)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_netlabel
```
```
In drivers/net/tun.c (ffffffff81763571)
Location: include/linux/bottom_half.h:10
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
In drivers/net/ppp/ppp_generic.c (ffffffff81768f95)
Location: include/linux/bottom_half.h:10
Inline: True
```
```
In net/core/gen_estimator.c (ffffffff818a6cbc)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/dev.c (ffffffff818b0d54)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:flush_backlog
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/neighbour.c (ffffffff818c36af)
Location: include/linux/bottom_half.h:10
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
In net/sched/sch_generic.c (ffffffff818f8a9a)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
```
```
In net/netlink/af_netlink.c (ffffffff81908b62)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_create
```
```
In net/netfilter/nf_log.c (ffffffff8190d6cc)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/netfilter/nf_log.c:nf_log_buf_open
```
```
In net/netfilter/nf_queue.c (ffffffff8190e367)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_reinject
```
```
In net/ipv4/route.c (ffffffff8191059f)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81919bf3)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_hashtables.c (ffffffff8191f8d5)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff819212b2)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81922a11)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/tcp.c (ffffffff8192927e)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff81933749)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8193e01c)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81940fdd)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/icmp.c (ffffffff81952fba)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/fib_frontend.c (ffffffff81960892)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
```
```
In net/ipv4/fib_semantics.c (ffffffff81964d7f)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/unix/af_unix.c (ffffffff8198e849)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/ipv6/ip6_output.c (ffffffff81996d19)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/addrconf.c (ffffffff8199d1a5)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff819ac13c)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:rt6_age_exceptions
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ip6_fib.c (ffffffff819afc76)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_start
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff819b50d2)
Location: include/linux/bottom_half.h:10
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff819c0dec)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff819d012f)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In net/ipv6/seg6_hmac.c (ffffffff819e01e2)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
```
```
In net/ipv6/inet6_hashtables.c (ffffffff819e2e34)
Location: include/linux/bottom_half.h:10
Inline: True
```
```
In net/xdp/xsk.c (ffffffff81a05128)
Location: include/linux/bottom_half.h:10
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
In arch/x86/kernel/fpu/core.c (ffffffff8103e433)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:fpu__save
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103f447)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8103fe5a)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/mm/pkeys.c (ffffffff8108dbe8)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:copy_init_pkru_to_fpregs
```
```
In kernel/softirq.c (ffffffff810a1a98)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/softirq.c:irq_enter
  - kernel/softirq.c:__do_softirq
```
```
In kernel/locking/spinlock.c (ffffffff81a9d455)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_lock_bh
  - kernel/locking/spinlock.c:_raw_read_lock_bh
  - kernel/locking/spinlock.c:_raw_spin_trylock_bh
  - kernel/locking/spinlock.c:_raw_spin_lock_bh
```
```
In kernel/irq/manage.c (ffffffff8110b455)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_forced_thread_fn
```
```
In kernel/rcu/update.c (ffffffff811178bb)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/srcutree.c (ffffffff811191ae)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
```
```
In kernel/rcu/tree.c (ffffffff8111cabf)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_cpu_kthread
```
```
In kernel/time/hrtimer.c (ffffffff8112cbfb)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
```
```
In kernel/bpf/cpumap.c (ffffffff811f3caf)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In kernel/bpf/offload.c (ffffffff811f4e37)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In kernel/padata.c (ffffffff81210922)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:invoke_padata_reorder
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_parallel_worker
```
```
In ipc/util.c (ffffffff8141cf6e)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/smack/smack_lsm.c (ffffffff8146308f)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_netlabel
```
```
In security/apparmor/policy_unpack.c (ffffffff81488d90)
Location: include/linux/bottom_half.h:10
Inline: True
```
```
In lib/rhashtable.c (ffffffff8150d5fb)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In drivers/net/tun.c (ffffffff817a12ac)
Location: include/linux/bottom_half.h:10
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
In drivers/net/ppp/ppp_generic.c (ffffffff817a6a75)
Location: include/linux/bottom_half.h:10
Inline: True
```
```
In net/core/skbuff.c (ffffffff818e8c16)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:netdev_alloc_frag
```
```
In net/core/gen_estimator.c (ffffffff818f214c)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/dev.c (ffffffff818fdaed)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:flush_backlog
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/neighbour.c (ffffffff8190f7a5)
Location: include/linux/bottom_half.h:10
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
In net/core/xdp.c (ffffffff81930798)
Location: include/linux/bottom_half.h:10
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff8195826a)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
```
```
In net/sched/cls_api.c (ffffffff819629c1)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tc_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffff81969f77)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/netfilter/nf_log.c (ffffffff8196f2fc)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/netfilter/nf_log.c:nf_log_buf_open
```
```
In net/netfilter/nf_queue.c (ffffffff8196fe4c)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_reinject
```
```
In net/ipv4/route.c (ffffffff81973003)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff8197bcef)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_hashtables.c (ffffffff819821f5)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81983c67)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8198541d)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/tcp.c (ffffffff8198c1a8)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff81997953)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a243f)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819a55db)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/icmp.c (ffffffff819b7aec)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/fib_frontend.c (ffffffff819c4e35)
Location: include/linux/bottom_half.h:10
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff819caad6)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/inet_fragment.c (ffffffff819cfa95)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/nexthop.c (ffffffff819d4c79)
Location: include/linux/bottom_half.h:10
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff819db92c)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff819e98ed)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/unix/af_unix.c (ffffffff819f9fab)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/ipv6/ip6_output.c (ffffffff81a00b19)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/addrconf.c (ffffffff81a09375)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff81a19c83)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ip6_fib.c (ffffffff81a1ddea)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_start
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81a235d6)
Location: include/linux/bottom_half.h:10
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff81a2fb27)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81a3ee4f)
Location: include/linux/bottom_half.h:10
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
In net/ipv6/ip6mr.c (ffffffff81a44106)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a4f5cb)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a51bb6)
Location: include/linux/bottom_half.h:10
Inline: True
```
```
In net/xdp/xsk.c (ffffffff81a746f2)
Location: include/linux/bottom_half.h:10
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
In arch/x86/kernel/fpu/core.c (ffffffff8103ebf3)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:fpu__save
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103faed)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8104057a)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/mm/pkeys.c (ffffffff8108e848)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:copy_init_pkru_to_fpregs
```
```
In kernel/softirq.c (ffffffff810a8058)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/softirq.c:irq_enter
  - kernel/softirq.c:__do_softirq
```
```
In kernel/locking/spinlock.c (ffffffff81ad4c35)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_lock_bh
  - kernel/locking/spinlock.c:_raw_read_lock_bh
  - kernel/locking/spinlock.c:_raw_spin_trylock_bh
  - kernel/locking/spinlock.c:_raw_spin_lock_bh
```
```
In kernel/irq/manage.c (ffffffff81117755)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_forced_thread_fn
```
```
In kernel/rcu/update.c (ffffffff81123c8f)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/srcutree.c (ffffffff8112557e)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
```
```
In kernel/rcu/tree.c (ffffffff8112904f)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_cpu_kthread
```
```
In kernel/time/hrtimer.c (ffffffff81138bdb)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
```
```
In kernel/bpf/cpumap.c (ffffffff81200a4f)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In kernel/bpf/offload.c (ffffffff81201e47)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In kernel/padata.c (ffffffff8121d4d2)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:invoke_padata_reorder
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_parallel_worker
```
```
In ipc/util.c (ffffffff81436dbe)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/smack/smack_lsm.c (ffffffff8147ce5f)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_netlabel
```
```
In security/apparmor/policy_unpack.c (ffffffff814a2c40)
Location: include/linux/bottom_half.h:10
Inline: True
```
```
In lib/rhashtable.c (ffffffff8152b44b)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In drivers/net/tun.c (ffffffff817c626c)
Location: include/linux/bottom_half.h:10
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
In drivers/net/ppp/ppp_generic.c (ffffffff817ca4d5)
Location: include/linux/bottom_half.h:10
Inline: True
```
```
In net/core/skbuff.c (ffffffff8191ad76)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:netdev_alloc_frag
```
```
In net/core/gen_estimator.c (ffffffff8192409c)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/dev.c (ffffffff81935873)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:flush_backlog
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/neighbour.c (ffffffff81941e15)
Location: include/linux/bottom_half.h:10
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
In net/core/xdp.c (ffffffff81962ca1)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff81963eb9)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/sched/sch_generic.c (ffffffff8198e71a)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
```
```
In net/netlink/af_netlink.c (ffffffff819a09e7)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/netfilter/nf_log.c (ffffffff819a5d2c)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/netfilter/nf_log.c:nf_log_buf_open
```
```
In net/netfilter/nf_queue.c (ffffffff819a684c)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_reinject
```
```
In net/ipv4/route.c (ffffffff819a9976)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff819b268f)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_hashtables.c (ffffffff819b8a55)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff819ba447)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819bbc32)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/tcp.c (ffffffff819c2af8)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff819ce4e3)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819d900f)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819dc2ca)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/icmp.c (ffffffff819ee7ec)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/fib_frontend.c (ffffffff819fb9d5)
Location: include/linux/bottom_half.h:10
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff81a016c6)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/inet_fragment.c (ffffffff81a06625)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/nexthop.c (ffffffff81a0b7d9)
Location: include/linux/bottom_half.h:10
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81a1285c)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a21602)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/unix/af_unix.c (ffffffff81a30c2b)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/ipv6/ip6_output.c (ffffffff81a376e9)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/addrconf.c (ffffffff81a40065)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff81a508f3)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ip6_fib.c (ffffffff81a54a3a)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_start
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81a5a3ab)
Location: include/linux/bottom_half.h:10
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff81a66677)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81a75abf)
Location: include/linux/bottom_half.h:10
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
In net/ipv6/ip6mr.c (ffffffff81a7acf6)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a8625b)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a887b6)
Location: include/linux/bottom_half.h:10
Inline: True
```
```
In net/xdp/xsk.c (ffffffff81aab0a1)
Location: include/linux/bottom_half.h:10
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
In arch/x86/kernel/fpu/core.c (ffffffff810419a6)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:fpu__save
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81042e3c)
Location: include/linux/bottom_half.h:10
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
In arch/x86/kernel/fpu/xstate.c (ffffffff8104391e)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/mm/pkeys.c (ffffffff810949cb)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:copy_init_pkru_to_fpregs
```
```
In kernel/softirq.c (ffffffff810af868)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/softirq.c:irq_enter
  - kernel/softirq.c:__do_softirq
```
```
In kernel/locking/spinlock.c (ffffffff81bccbc5)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_lock_bh
  - kernel/locking/spinlock.c:_raw_read_lock_bh
  - kernel/locking/spinlock.c:_raw_spin_trylock_bh
  - kernel/locking/spinlock.c:_raw_spin_lock_bh
```
```
In kernel/irq/manage.c (ffffffff811233c5)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_forced_thread_fn
```
```
In kernel/rcu/update.c (ffffffff811304ea)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/srcutree.c (ffffffff81133124)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
```
```
In kernel/rcu/tree.c (ffffffff81136f0b)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_cpu_kthread
```
```
In kernel/time/hrtimer.c (ffffffff81147abb)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
```
```
In kernel/bpf/cpumap.c (ffffffff812284fd)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In kernel/bpf/offload.c (ffffffff8122925b)
Location: include/linux/bottom_half.h:10
Inline: True
```
```
In kernel/padata.c (ffffffff812497c2)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:invoke_padata_reorder
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_parallel_worker
```
```
In ipc/util.c (ffffffff814868c8)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - ipc/util.c:__rhashtable_remove_fast_one
```
```
In security/smack/smack_lsm.c (ffffffff814d28ff)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_netlabel
```
```
In security/apparmor/policy_unpack.c (ffffffff814fcf27)
Location: include/linux/bottom_half.h:10
Inline: True
```
```
In lib/rhashtable.c (ffffffff8158e9d7)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_chain
```
```
In drivers/net/tun.c (ffffffff8188e3b9)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_build_skb
  - drivers/net/tun.c:tun_napi_alloc_frags
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81895525)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
```
```
In net/core/skbuff.c (ffffffff819ed356)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:netdev_alloc_frag
```
```
In net/core/gen_estimator.c (ffffffff819f7c4c)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/dev.c (ffffffff81a0a558)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:flush_backlog
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/neighbour.c (ffffffff81a11fe2)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_seq_start
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_for_each
  - net/core/neighbour.c:neigh_dump_table
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/xdp.c (ffffffff81a35f98)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/core/xdp.c:__rhashtable_remove_fast_one
```
```
In net/sched/sch_generic.c (ffffffff81a664ce)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
```
```
In net/netlink/af_netlink.c (ffffffff81a7a15f)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
```
```
In net/netfilter/nf_log.c (ffffffff81a8f0cc)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/netfilter/nf_log.c:nf_log_buf_open
```
```
In net/netfilter/nf_queue.c (ffffffff81a8fb7b)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_reinject
```
```
In net/ipv4/route.c (ffffffff81a92da9)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81a9bd88)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_hashtables.c (ffffffff81aa3765)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81aa4f42)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81aa644a)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/tcp.c (ffffffff81aae0d1)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff81aba5cc)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac5b4a)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ac942a)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/icmp.c (ffffffff81adc568)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/fib_frontend.c (ffffffff81aeaa39)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_lookup
```
```
In net/ipv4/fib_semantics.c (ffffffff81af06cd)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/inet_fragment.c (ffffffff81af5e88)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/nexthop.c (ffffffff81afc24f)
Location: include/linux/bottom_half.h:10
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81b01cc0)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:__rhashtable_remove_fast_one
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b108de)
Location: include/linux/bottom_half.h:10
Inline: True
```
```
In net/xfrm/espintcp.c (ffffffff81b227e5)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:handle_esp
```
```
In net/unix/af_unix.c (ffffffff81b24ec0)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/ipv6/ip6_output.c (ffffffff81b2d224)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/addrconf.c (ffffffff81b3b3e0)
Location: include/linux/bottom_half.h:10
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
```
```
In net/ipv6/route.c (ffffffff81b47ce3)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:rt6_probe
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ip6_fib.c (ffffffff81b4cb7a)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_start
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81b5264d)
Location: include/linux/bottom_half.h:10
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff81b5f026)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81b70145)
Location: include/linux/bottom_half.h:10
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
In net/ipv6/ip6mr.c (ffffffff81b75250)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b80c5f)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
  - net/ipv6/seg6_hmac.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81b83cc6)
Location: include/linux/bottom_half.h:10
Inline: True
```
```
In net/xdp/xsk.c (ffffffff81ba7041)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
  - net/xdp/xsk.c:xsk_release
```
```
In net/mptcp/protocol.c (ffffffff81bac7b9)
Location: include/linux/bottom_half.h:10
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
In arch/x86/kernel/fpu/core.c (ffffffff81041954)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:fpu__save
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81042d7a)
Location: include/linux/bottom_half.h:10
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
In arch/x86/kernel/fpu/xstate.c (ffffffff810439ce)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/mm/pkeys.c (ffffffff81093dbb)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:copy_init_pkru_to_fpregs
```
```
In kernel/softirq.c (ffffffff8200004c)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/softirq.c:__do_softirq
```
```
In kernel/locking/spinlock.c (ffffffff81c45785)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_lock_bh
  - kernel/locking/spinlock.c:_raw_read_lock_bh
  - kernel/locking/spinlock.c:_raw_spin_trylock_bh
  - kernel/locking/spinlock.c:_raw_spin_lock_bh
```
```
In kernel/irq/manage.c (ffffffff8111f205)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_forced_thread_fn
```
```
In kernel/rcu/update.c (ffffffff8112c398)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/srcutree.c (ffffffff8112e904)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
```
```
In kernel/rcu/tree.c (ffffffff81132549)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_cpu_kthread
```
```
In kernel/time/hrtimer.c (ffffffff81143f4b)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
```
```
In kernel/bpf/cpumap.c (ffffffff8122f2ba)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
```
```
In kernel/bpf/offload.c (ffffffff81230deb)
Location: include/linux/bottom_half.h:10
Inline: True
```
```
In kernel/padata.c (ffffffff81254652)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:invoke_padata_reorder
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_parallel_worker
```
```
In ipc/util.c (ffffffff814a3f78)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - ipc/util.c:__rhashtable_remove_fast_one
```
```
In security/smack/smack_lsm.c (ffffffff814f39bc)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smk_ipv4_check
  - security/smack/smack_lsm.c:smack_netlbl_add
```
```
In security/apparmor/policy_unpack.c (ffffffff8151a137)
Location: include/linux/bottom_half.h:10
Inline: True
```
```
In lib/rhashtable.c (ffffffff815ab537)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_chain
```
```
In drivers/net/tun.c (ffffffff8189c921)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_build_skb
  - drivers/net/tun.c:tun_napi_alloc_frags
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff818a3c55)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
```
```
In net/core/skbuff.c (ffffffff819ed01b)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:netdev_alloc_frag
```
```
In net/core/gen_estimator.c (ffffffff819f76be)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/dev.c (ffffffff81a0d8ee)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:__dev_set_allmulti
  - net/core/dev.c:dev_set_promiscuity
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:flush_backlog
  - net/core/dev.c:__dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_open
```
```
In net/core/dev_addr_lists.c (ffffffff81a105e5)
Location: include/linux/bottom_half.h:10
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
In net/core/neighbour.c (ffffffff81a12342)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_seq_start
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_for_each
  - net/core/neighbour.c:neigh_dump_table
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/rtnetlink.c (ffffffff81a1e9b0)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_fdb_dump
```
```
In net/core/filter.c (ffffffff81a2e934)
Location: include/linux/bottom_half.h:10
Inline: True
```
```
In net/core/xdp.c (ffffffff81a38368)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/core/xdp.c:__rhashtable_remove_fast_one
```
```
In net/core/net-procfs.c (ffffffff81a3de97)
Location: include/linux/bottom_half.h:10
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff81a5265e)
Location: include/linux/bottom_half.h:10
Inline: True
```
```
In net/core/sock_map.c (ffffffff81a55929)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_update_elem
```
```
In net/sched/sch_generic.c (ffffffff81a6e5ae)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
```
```
In net/netlink/af_netlink.c (ffffffff81a82fbf)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
```
```
In net/netfilter/nf_log.c (ffffffff81a9913c)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/netfilter/nf_log.c:nf_log_buf_open
```
```
In net/netfilter/nf_queue.c (ffffffff81a99b6a)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_reinject
```
```
In net/ipv4/route.c (ffffffff81a9cc5a)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81aa5be8)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_hashtables.c (ffffffff81aadda5)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81aaf5ad)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ab0a9a)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/tcp.c (ffffffff81ab8354)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff81ac5a0c)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad17ba)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ad537a)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/icmp.c (ffffffff81ae928b)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/fib_frontend.c (ffffffff81af78d9)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_lookup
```
```
In net/ipv4/fib_semantics.c (ffffffff81afd6bd)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/inet_fragment.c (ffffffff81b02cf8)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/nexthop.c (ffffffff81b09a8f)
Location: include/linux/bottom_half.h:10
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81b0fda0)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:__rhashtable_remove_fast_one
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b1ebce)
Location: include/linux/bottom_half.h:10
Inline: True
```
```
In net/xfrm/espintcp.c (ffffffff81b31493)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:handle_esp
```
```
In net/unix/af_unix.c (ffffffff81b339f7)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/ipv6/ip6_output.c (ffffffff81b3bc34)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/addrconf.c (ffffffff81b4a0f0)
Location: include/linux/bottom_half.h:10
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
```
```
In net/ipv6/route.c (ffffffff81b568ed)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:rt6_probe
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ip6_fib.c (ffffffff81b5b7d8)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_start
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81b6176f)
Location: include/linux/bottom_half.h:10
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff81b6d7b6)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81b7ec75)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_renew
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In net/ipv6/ip6mr.c (ffffffff81b83fc0)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b904cf)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
  - net/ipv6/seg6_hmac.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81b93376)
Location: include/linux/bottom_half.h:10
Inline: True
```
```
In net/xdp/xsk.c (ffffffff81bb6380)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
  - net/xdp/xsk.c:xsk_release
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
In arch/x86/kernel/fpu/core.c (ffffffff81043351)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:fpu__save
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81044733)
Location: include/linux/bottom_half.h:10
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
In arch/x86/kernel/fpu/xstate.c (ffffffff81045212)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/mm/pkeys.c (ffffffff8109477b)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:copy_init_pkru_to_fpregs
```
```
In kernel/softirq.c (ffffffff8200004c)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/softirq.c:__do_softirq
```
```
In kernel/locking/spinlock.c (ffffffff81c389f5)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_lock_bh
  - kernel/locking/spinlock.c:_raw_read_lock_bh
  - kernel/locking/spinlock.c:_raw_spin_trylock_bh
  - kernel/locking/spinlock.c:_raw_spin_lock_bh
```
```
In kernel/irq/manage.c (ffffffff8111f725)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_forced_thread_fn
```
```
In kernel/rcu/update.c (ffffffff8112c8c8)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/srcutree.c (ffffffff8112eb8c)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
```
```
In kernel/rcu/tree.c (ffffffff81133869)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_do_batch
```
```
In kernel/time/hrtimer.c (ffffffff811450db)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
```
```
In kernel/bpf/cpumap.c (ffffffff812341dc)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
```
```
In kernel/bpf/offload.c (ffffffff81234f8e)
Location: include/linux/bottom_half.h:10
Inline: True
```
```
In kernel/padata.c (ffffffff81258bf2)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:invoke_padata_reorder
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_parallel_worker
```
```
In ipc/util.c (ffffffff814a9eac)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - ipc/util.c:__rhashtable_remove_fast_one
```
```
In security/smack/smack_lsm.c (ffffffff814fa97c)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smk_ipv4_check
  - security/smack/smack_lsm.c:smack_netlbl_add
```
```
In security/apparmor/policy_unpack.c (ffffffff81520a46)
Location: include/linux/bottom_half.h:10
Inline: True
```
```
In lib/rhashtable.c (ffffffff815b6399)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In drivers/net/tun.c (ffffffff8187ee91)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_build_skb
  - drivers/net/tun.c:tun_napi_alloc_frags
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81885965)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
```
```
In net/core/skbuff.c (ffffffff819d34ec)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_frag_align
```
```
In net/core/gen_estimator.c (ffffffff819dd83e)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/dev.c (ffffffff819f458b)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:__dev_set_allmulti
  - net/core/dev.c:dev_set_promiscuity
  - net/core/dev.c:napi_threaded_poll
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:flush_backlog
  - net/core/dev.c:__dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_open
```
```
In net/core/dev_addr_lists.c (ffffffff819f7455)
Location: include/linux/bottom_half.h:10
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
In net/core/neighbour.c (ffffffff819f8ec5)
Location: include/linux/bottom_half.h:10
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
In net/core/rtnetlink.c (ffffffff81a057b0)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_fdb_dump
```
```
In net/core/filter.c (ffffffff81a15f86)
Location: include/linux/bottom_half.h:10
Inline: True
```
```
In net/core/xdp.c (ffffffff81a1f1ac)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/core/xdp.c:__rhashtable_remove_fast_one
```
```
In net/core/net-procfs.c (ffffffff81a24f67)
Location: include/linux/bottom_half.h:10
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff81a37d43)
Location: include/linux/bottom_half.h:10
Inline: True
```
```
In net/core/sock_map.c (ffffffff81a513a7)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_update_elem
```
```
In net/sched/sch_generic.c (ffffffff81a56e3e)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
```
```
In net/netlink/af_netlink.c (ffffffff81a6c08f)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
```
```
In net/netfilter/nf_log.c (ffffffff81a8446c)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/netfilter/nf_log.c:nf_log_buf_open
```
```
In net/netfilter/nf_queue.c (ffffffff81a84e7a)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_reinject
```
```
In net/ipv4/route.c (ffffffff81a87d1f)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81a90bb8)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_hashtables.c (ffffffff81a98f45)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81a9a8b5)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81a9bb4a)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/tcp.c (ffffffff81aa364e)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff81ab0c18)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abc7db)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ac03f7)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/icmp.c (ffffffff81ad48ad)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_reply
```
```
In net/ipv4/fib_frontend.c (ffffffff81ae2ff9)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_lookup
```
```
In net/ipv4/fib_semantics.c (ffffffff81ae8efc)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/inet_fragment.c (ffffffff81aee5fc)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/nexthop.c (ffffffff81af48d1)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_select_path_hthr
  - net/ipv4/nexthop.c:nexthop_select_path_hthr
```
```
In net/ipv4/ipmr.c (ffffffff81afd992)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:__rhashtable_remove_fast_one
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0c859)
Location: include/linux/bottom_half.h:10
Inline: True
```
```
In net/xfrm/espintcp.c (ffffffff81b1f29f)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_rcv
```
```
In net/unix/af_unix.c (ffffffff81b213fb)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/ipv6/ip6_output.c (ffffffff81b29597)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/addrconf.c (ffffffff81b37305)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff81b444c8)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:rt6_probe
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ip6_fib.c (ffffffff81b49c98)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_start
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81b4fa3a)
Location: include/linux/bottom_half.h:10
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff81b5bb4e)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81b6d875)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In net/ipv6/ip6mr.c (ffffffff81b72c42)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b7f70f)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
  - net/ipv6/seg6_hmac.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81b824a6)
Location: include/linux/bottom_half.h:10
Inline: True
```
```
In net/xdp/xsk.c (ffffffff81ba66ec)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
  - net/xdp/xsk.c:xsk_release
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
In arch/x86/kernel/fpu/core.c (ffffffff81049aa5)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu_flush_thread
  - arch/x86/kernel/fpu/core.c:fpu__clear_user_states
  - arch/x86/kernel/fpu/core.c:fpu_clone
  - arch/x86/kernel/fpu/core.c:fpu_sync_fpstate
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8104a926)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In kernel/softirq.c (ffffffff8200004c)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/softirq.c:__do_softirq
```
```
In kernel/locking/spinlock.c (ffffffff81d572d5)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_lock_bh
  - kernel/locking/spinlock.c:_raw_read_lock_bh
  - kernel/locking/spinlock.c:_raw_spin_trylock_bh
  - kernel/locking/spinlock.c:_raw_spin_lock_bh
```
```
In kernel/irq/manage.c (ffffffff8113fbb5)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_forced_thread_fn
```
```
In kernel/rcu/update.c (ffffffff8114d5e0)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/srcutree.c (ffffffff8115007a)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
```
```
In kernel/rcu/tree.c (ffffffff81155c59)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_do_batch
```
```
In kernel/time/hrtimer.c (ffffffff8116896b)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
```
```
In kernel/bpf/cpumap.c (ffffffff8126defa)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In kernel/bpf/offload.c (ffffffff8126f0be)
Location: include/linux/bottom_half.h:10
Inline: True
```
```
In kernel/padata.c (ffffffff81294812)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:invoke_padata_reorder
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_parallel_worker
```
```
In ipc/util.c (ffffffff8150235c)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - ipc/util.c:__rhashtable_remove_fast_one
```
```
In security/smack/smack_lsm.c (ffffffff815555ec)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smk_ipv4_check
  - security/smack/smack_lsm.c:smack_netlbl_add
```
```
In security/apparmor/policy_unpack.c (ffffffff8157ebe6)
Location: include/linux/bottom_half.h:10
Inline: True
```
```
In lib/rhashtable.c (ffffffff8161c8c9)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In drivers/net/tun.c (ffffffff8191069b)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_build_skb
  - drivers/net/tun.c:tun_napi_alloc_frags
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff819172f5)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
```
```
In drivers/net/xen-netfront.c (ffffffff8191f33b)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:netfront_resume
```
```
In net/core/skbuff.c (ffffffff81a8322f)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_frag_align
```
```
In net/core/gen_estimator.c (ffffffff81a8db1e)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/dev.c (ffffffff81aa5eab)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:__dev_set_allmulti
  - net/core/dev.c:dev_set_promiscuity
  - net/core/dev.c:napi_threaded_poll
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:flush_backlog
  - net/core/dev.c:__dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_open
```
```
In net/core/dev_addr_lists.c (ffffffff81aa90c5)
Location: include/linux/bottom_half.h:10
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
In net/core/neighbour.c (ffffffff81aaaaa5)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_seq_start
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_for_each
  - net/core/neighbour.c:neigh_dump_table
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/rtnetlink.c (ffffffff81ab7bf0)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_fdb_dump
```
```
In net/core/filter.c (ffffffff81ac75ed)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/core/filter.c:bpf_out_neigh_v6
```
```
In net/core/xdp.c (ffffffff81ad343c)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/core/xdp.c:__rhashtable_remove_fast_one
```
```
In net/core/net-procfs.c (ffffffff81ad9a9c)
Location: include/linux/bottom_half.h:10
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff81aedb53)
Location: include/linux/bottom_half.h:10
Inline: True
```
```
In net/core/sock_map.c (ffffffff81b0a13d)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_update_elem
```
```
In net/sched/sch_generic.c (ffffffff81b0fc6e)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
```
```
In net/netlink/af_netlink.c (ffffffff81b256ac)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
```
```
In net/netfilter/nf_log.c (ffffffff81b3e72c)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/netfilter/nf_log.c:nf_log_buf_open
```
```
In net/netfilter/nf_queue.c (ffffffff81b3f515)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_reinject
```
```
In net/ipv4/route.c (ffffffff81b42250)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81b4c00f)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_hashtables.c (ffffffff81b543c5)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81b55d25)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81b5721a)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/tcp.c (ffffffff81b5f7ee)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff81b6da5c)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b7a424)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81b7f388)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/icmp.c (ffffffff81b935dc)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_reply
```
```
In net/ipv4/fib_frontend.c (ffffffff81ba2629)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_lookup
```
```
In net/ipv4/fib_semantics.c (ffffffff81ba8f1c)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/inet_fragment.c (ffffffff81bae9ac)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/nexthop.c (ffffffff81bb515e)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_select_path_hthr
  - net/ipv4/nexthop.c:nexthop_select_path_hthr
```
```
In net/ipv4/ipmr.c (ffffffff81bbfa92)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:__rhashtable_remove_fast_one
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bcfa49)
Location: include/linux/bottom_half.h:10
Inline: True
```
```
In net/xfrm/espintcp.c (ffffffff81be3e8b)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_rcv
```
```
In net/unix/af_unix.c (ffffffff81be6534)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/ipv6/ip6_output.c (ffffffff81beefc8)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/addrconf.c (ffffffff81bfdabc)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff81c0b463)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:rt6_probe
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ip6_fib.c (ffffffff81c10af8)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_start
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81c16d99)
Location: include/linux/bottom_half.h:10
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff81c23285)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81c356ff)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In net/ipv6/ioam6.c (ffffffff81c3a192)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
  - net/ipv6/ioam6.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/ip6mr.c (ffffffff81c3d182)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/seg6_hmac.c (ffffffff81c4afaf)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
  - net/ipv6/seg6_hmac.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81c4e556)
Location: include/linux/bottom_half.h:10
Inline: True
```
```
In net/xdp/xsk.c (ffffffff81c7423c)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
  - net/xdp/xsk.c:xsk_release
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
In arch/x86/kernel/fpu/core.c (ffffffff81053886)
Location: include/linux/bottom_half.h:11
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
In arch/x86/kernel/fpu/signal.c (ffffffff81054e31)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81055ea8)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpstate_realloc
```
```
In kernel/softirq.c (ffffffff82200046)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - kernel/softirq.c:__do_softirq
```
```
In kernel/locking/spinlock.c (ffffffff81f29f15)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_lock_bh
  - kernel/locking/spinlock.c:_raw_read_lock_bh
  - kernel/locking/spinlock.c:_raw_spin_trylock_bh
  - kernel/locking/spinlock.c:_raw_spin_lock_bh
```
```
In kernel/irq/manage.c (ffffffff811628e5)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_forced_thread_fn
```
```
In kernel/rcu/update.c (ffffffff81172faa)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_invoke_cbs
```
```
In kernel/rcu/srcutree.c (ffffffff81177527)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
```
```
In kernel/rcu/tree.c (ffffffff8117e72f)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_do_batch
```
```
In kernel/time/hrtimer.c (ffffffff8119c4bb)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
```
```
In kernel/bpf/cpumap.c (ffffffff812bcd3d)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In kernel/bpf/offload.c (ffffffff812be007)
Location: include/linux/bottom_half.h:11
Inline: True
```
```
In kernel/padata.c (ffffffff812e9a52)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:invoke_padata_reorder
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_parallel_worker
```
```
In ipc/util.c (ffffffff815939a7)
Location: include/linux/bottom_half.h:11
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffff815ef26f)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smk_ipv4_check
  - security/smack/smack_lsm.c:smack_netlbl_add
```
```
In security/apparmor/policy_unpack.c (ffffffff8161d6d9)
Location: include/linux/bottom_half.h:11
Inline: True
```
```
In lib/rhashtable.c (ffffffff816ea0d3)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In lib/irq_poll.c (ffffffff8176ef50)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_cpu_dead
```
```
In drivers/net/tun.c (ffffffff81a67837)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_alloc_frags
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81a6b6f5)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
```
```
In drivers/net/xen-netfront.c (ffffffff81a736bd)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:netfront_resume
```
```
In net/core/skbuff.c (ffffffff81bf8063)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_frag_align
```
```
In net/core/gen_estimator.c (ffffffff81c03643)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/dev.c (ffffffff81c1d95d)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:__dev_set_allmulti
  - net/core/dev.c:dev_set_promiscuity
  - net/core/dev.c:napi_threaded_poll
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:flush_backlog
  - net/core/dev.c:__dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_open
```
```
In net/core/dev_addr_lists.c (ffffffff81c21275)
Location: include/linux/bottom_half.h:11
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
In net/core/neighbour.c (ffffffff81c23955)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_seq_start
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_for_each
  - net/core/neighbour.c:neigh_dump_table
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/rtnetlink.c (ffffffff81c317fe)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_fdb_dump
```
```
In net/core/filter.c (ffffffff81c43e78)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/core/filter.c:bpf_out_neigh_v6
```
```
In net/core/xdp.c (ffffffff81c50ce7)
Location: include/linux/bottom_half.h:11
Inline: True
```
```
In net/core/net-procfs.c (ffffffff81c5aecc)
Location: include/linux/bottom_half.h:11
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff81c70a3e)
Location: include/linux/bottom_half.h:11
Inline: True
```
```
In net/core/sock_map.c (ffffffff81c903bc)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_update_elem
```
```
In net/sched/sch_generic.c (ffffffff81c96e5d)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
```
```
In net/netlink/af_netlink.c (ffffffff81cabfdb)
Location: include/linux/bottom_half.h:11
Inline: True
```
```
In net/bpf/test_run.c (ffffffff81cb399c)
Location: include/linux/bottom_half.h:11
Inline: True
```
```
In net/netfilter/nf_log.c (ffffffff81ccad76)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/netfilter/nf_log.c:nf_log_buf_open
```
```
In net/netfilter/nf_queue.c (ffffffff81ccbc87)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_reinject
```
```
In net/ipv4/route.c (ffffffff81ccec58)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81cd974e)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_hashtables.c (ffffffff81ce2c20)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81ce3a31)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ce51a3)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/tcp.c (ffffffff81ceefaf)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_abort
  - net/ipv4/tcp.c:tcp_abort
  - net/ipv4/tcp.c:__tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff81cfcee5)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d0a5fb)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81d0ed31)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/icmp.c (ffffffff81d24436)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_reply
```
```
In net/ipv4/fib_frontend.c (ffffffff81d34d1a)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_lookup
```
```
In net/ipv4/fib_semantics.c (ffffffff81d3b986)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/inet_fragment.c (ffffffff81d418b8)
Location: include/linux/bottom_half.h:11
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81d48c5e)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_select_path_hthr
  - net/ipv4/nexthop.c:nexthop_select_path_hthr
```
```
In net/ipv4/ipmr.c (ffffffff81d55df5)
Location: include/linux/bottom_half.h:11
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d68133)
Location: include/linux/bottom_half.h:11
Inline: True
```
```
In net/xfrm/espintcp.c (ffffffff81d7ae40)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff81d87695)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/addrconf.c (ffffffff81d9747d)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff81da6237)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:rt6_probe
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ip6_fib.c (ffffffff81dabc97)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_start
```
```
In net/ipv6/icmp.c (ffffffff81dc018e)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81dd312f)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In net/ipv6/ioam6.c (ffffffff81dd7eef)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/ip6mr.c (ffffffff81ddb50a)
Location: include/linux/bottom_half.h:11
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff81dea81b)
Location: include/linux/bottom_half.h:11
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
In arch/x86/kernel/fpu/core.c (ffffffff81061601)
Location: include/linux/bottom_half.h:11
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
In arch/x86/kernel/fpu/signal.c (ffffffff81062987)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8106377d)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpstate_realloc
```
```
In kernel/softirq.c (ffffffff820d6f26)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - kernel/softirq.c:__do_softirq
```
```
In kernel/locking/spinlock.c (ffffffff820d5ed5)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_lock_bh
  - kernel/locking/spinlock.c:_raw_read_lock_bh
  - kernel/locking/spinlock.c:_raw_spin_trylock_bh
  - kernel/locking/spinlock.c:_raw_spin_lock_bh
```
```
In kernel/irq/manage.c (ffffffff81196555)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_forced_thread_fn
```
```
In kernel/rcu/update.c (ffffffff811a95da)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_invoke_cbs
```
```
In kernel/rcu/srcutree.c (ffffffff811aeb57)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
```
```
In kernel/rcu/tree.c (ffffffff811b95bb)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_do_batch
```
```
In kernel/time/hrtimer.c (ffffffff811dae8b)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
```
```
In kernel/bpf/cpumap.c (ffffffff8132019d)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In kernel/padata.c (ffffffff81353892)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:invoke_padata_reorder
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_parallel_worker
```
```
In security/smack/smack_lsm.c (ffffffff8169f55f)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smk_ipv4_check
  - security/smack/smack_lsm.c:smack_netlbl_add
```
```
In lib/irq_poll.c (ffffffff8189e9d0)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_cpu_dead
```
```
In drivers/net/tun.c (ffffffff81bf32d7)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_alloc_frags
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81bfe5d5)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
```
```
In drivers/net/xen-netfront.c (ffffffff81c0794d)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:netfront_resume
```
```
In net/core/skbuff.c (ffffffff81da6e19)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_frag_align
  - net/core/skbuff.c:napi_get_frags_check
```
```
In net/core/gen_estimator.c (ffffffff81db2c33)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/dev.c (ffffffff81dcec4d)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:__dev_set_allmulti
  - net/core/dev.c:dev_set_promiscuity
  - net/core/dev.c:napi_threaded_poll
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:flush_backlog
  - net/core/dev.c:__dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_open
```
```
In net/core/dev_addr_lists.c (ffffffff81dd3345)
Location: include/linux/bottom_half.h:11
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
In net/core/neighbour.c (ffffffff81dd598a)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_seq_start
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_for_each
  - net/core/neighbour.c:neigh_dump_table
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
```
```
In net/core/rtnetlink.c (ffffffff81de4b9e)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_fdb_dump
```
```
In net/core/filter.c (ffffffff81df81c8)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/core/filter.c:bpf_out_neigh_v6
```
```
In net/core/net-procfs.c (ffffffff81e1111c)
Location: include/linux/bottom_half.h:11
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff81e28a6e)
Location: include/linux/bottom_half.h:11
Inline: True
```
```
In net/core/sock_map.c (ffffffff81e4b7ec)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_update_elem
```
```
In net/sched/sch_generic.c (ffffffff81e52c3d)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
```
```
In net/bpf/test_run.c (ffffffff81e71bec)
Location: include/linux/bottom_half.h:11
Inline: True
```
```
In net/netfilter/nf_log.c (ffffffff81e8aab6)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/netfilter/nf_log.c:nf_log_buf_open
```
```
In net/netfilter/nf_queue.c (ffffffff81e8baf6)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_reinject
```
```
In net/ipv4/route.c (ffffffff81e8eec3)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81e99ece)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_hashtables.c (ffffffff81ea5183)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81ea646d)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ea8393)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/tcp.c (ffffffff81eb230d)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_abort
  - net/ipv4/tcp.c:tcp_abort
  - net/ipv4/tcp.c:tcp_abort
  - net/ipv4/tcp.c:__tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff81ec1aa5)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ecfe8b)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ed4821)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/icmp.c (ffffffff81eebc16)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_reply
```
```
In net/ipv4/fib_frontend.c (ffffffff81efd22a)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_lookup
```
```
In net/ipv4/fib_semantics.c (ffffffff81f04366)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/nexthop.c (ffffffff81f1224e)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_select_path_hthr
  - net/ipv4/nexthop.c:nexthop_select_path_hthr
```
```
In net/xfrm/xfrm_input.c (ffffffff81f41315)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/espintcp.c (ffffffff81f47fa8)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:handle_esp
```
```
In net/ipv6/ip6_output.c (ffffffff81f55415)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/addrconf.c (ffffffff81f66181)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff81f757a7)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:rt6_probe
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ip6_fib.c (ffffffff81f7b627)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_start
```
```
In net/ipv6/icmp.c (ffffffff81f908fe)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81fa46b4)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In net/ipv6/seg6_hmac.c (ffffffff81fbe06b)
Location: include/linux/bottom_half.h:11
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
In arch/x86/kernel/fpu/core.c (ffffffff81062ed1)
Location: include/linux/bottom_half.h:11
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
In arch/x86/kernel/fpu/signal.c (ffffffff8106438b)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff810650cf)
Location: include/linux/bottom_half.h:11
Inline: True
```
```
In kernel/softirq.c (ffffffff8215a2b6)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - kernel/softirq.c:__do_softirq
```
```
In kernel/locking/spinlock.c (ffffffff82159355)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_lock_bh
  - kernel/locking/spinlock.c:_raw_read_lock_bh
  - kernel/locking/spinlock.c:_raw_spin_trylock_bh
  - kernel/locking/spinlock.c:_raw_spin_lock_bh
```
```
In kernel/irq/manage.c (ffffffff811a7f15)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_forced_thread_fn
```
```
In kernel/rcu/update.c (ffffffff811bb35d)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_invoke_cbs
```
```
In kernel/rcu/srcutree.c (ffffffff811c0b58)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
```
```
In kernel/rcu/tree.c (ffffffff811cb8cd)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_do_batch
```
```
In kernel/time/hrtimer.c (ffffffff811ef3ab)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
```
```
In kernel/bpf/cpumap.c (ffffffff8135000f)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In kernel/padata.c (ffffffff81384a92)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:invoke_padata_reorder
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_parallel_worker
```
```
In security/smack/smack_lsm.c (ffffffff816d7c3f)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smk_ipv4_check
  - security/smack/smack_lsm.c:smack_netlbl_add
```
```
In lib/irq_poll.c (ffffffff818e0fa0)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_cpu_dead
```
```
In drivers/net/tun.c (ffffffff81c4b997)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_alloc_frags
```
```
In drivers/net/virtio_net.c (ffffffff81c544a1)
Location: include/linux/bottom_half.h:11
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
In drivers/net/ppp/ppp_generic.c (ffffffff81c63c15)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
```
```
In drivers/net/xen-netfront.c (ffffffff81c6d06d)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:netfront_resume
```
```
In drivers/net/net_failover.c (ffffffff81c6fb3e)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - drivers/net/net_failover.c:net_failover_slave_register
  - drivers/net/net_failover.c:net_failover_close
  - drivers/net/net_failover.c:net_failover_open
```
```
In net/core/sock.c (ffffffff81e08925)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/core/sock.c:sock_i_ino
```
```
In net/core/skbuff.c (ffffffff81e1606b)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_frag_align
  - net/core/skbuff.c:napi_get_frags_check
```
```
In net/core/gen_estimator.c (ffffffff81e23203)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/dev.c (ffffffff81e3f87d)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:__dev_set_allmulti
  - net/core/dev.c:dev_set_promiscuity
  - net/core/dev.c:napi_threaded_poll
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:flush_backlog
  - net/core/dev.c:__dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_open
```
```
In net/core/dev_addr_lists.c (ffffffff81e43f15)
Location: include/linux/bottom_half.h:11
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
In net/core/rtnetlink.c (ffffffff81e565ae)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_fdb_dump
```
```
In net/core/filter.c (ffffffff81e69949)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/core/filter.c:bpf_out_neigh_v6
```
```
In net/core/net-procfs.c (ffffffff81e84a2c)
Location: include/linux/bottom_half.h:11
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff81e9e08e)
Location: include/linux/bottom_half.h:11
Inline: True
```
```
In net/core/sock_map.c (ffffffff81ea6f11)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_update_elem
```
```
In net/sched/sch_generic.c (ffffffff81eae4db)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
```
```
In net/bpf/test_run.c (ffffffff81ece6e2)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_test_run
```
```
In net/netfilter/nf_log.c (ffffffff81ee8ae6)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/netfilter/nf_log.c:nf_log_buf_open
```
```
In net/netfilter/nf_queue.c (ffffffff81ee9ba0)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_reinject
```
```
In net/ipv4/inet_hashtables.c (ffffffff81f03913)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81f04c45)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81f06c13)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/tcp.c (ffffffff81f109a8)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_abort
  - net/ipv4/tcp.c:tcp_abort
  - net/ipv4/tcp.c:tcp_abort
  - net/ipv4/tcp.c:__tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff81f1ff2f)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f2eb37)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81f32683)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/icmp.c (ffffffff81f4b9f9)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_reply
```
```
In net/ipv4/fib_frontend.c (ffffffff81f5cc71)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_lookup
```
```
In net/xfrm/xfrm_input.c (ffffffff81fa0ba5)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/espintcp.c (ffffffff81fa7aa8)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:handle_esp
```
```
In net/ipv6/addrconf.c (ffffffff81fc6291)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
```
```
In net/ipv6/route.c (ffffffff81fd5849)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route
```
```
In net/ipv6/icmp.c (ffffffff81ff117e)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/seg6_hmac.c (ffffffff8201eda1)
Location: include/linux/bottom_half.h:11
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
In arch/x86/kernel/fpu/core.c (ffffffff81069e92)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpregs_lock_and_load
  - arch/x86/kernel/fpu/core.c:fpu__clear_user_states
  - arch/x86/kernel/fpu/core.c:fpu_reset_fpregs
  - arch/x86/kernel/fpu/core.c:fpu_clone
  - arch/x86/kernel/fpu/core.c:fpu_sync_fpstate
  - arch/x86/kernel/fpu/core.c:fpu_swap_kvm_fpstate
  - arch/x86/kernel/fpu/core.c:fpu_update_guest_xfd
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8106b861)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8106c77f)
Location: include/linux/bottom_half.h:11
Inline: True
```
```
In kernel/softirq.c (ffffffff8223db32)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - kernel/softirq.c:__do_softirq
```
```
In kernel/locking/spinlock.c (ffffffff8223cbd5)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_lock_bh
  - kernel/locking/spinlock.c:_raw_read_lock_bh
  - kernel/locking/spinlock.c:_raw_spin_trylock_bh
  - kernel/locking/spinlock.c:_raw_spin_lock_bh
```
```
In kernel/irq/manage.c (ffffffff811b7a75)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_forced_thread_fn
```
```
In kernel/rcu/update.c (ffffffff811cb401)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_invoke_cbs
```
```
In kernel/rcu/srcutree.c (ffffffff811d106d)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
```
```
In kernel/rcu/tree.c (ffffffff811de4d1)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - kernel/rcu/tree.c:nocb_cb_wait
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_do_batch
```
```
In kernel/bpf/cpumap.c (ffffffff81377448)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In kernel/padata.c (ffffffff813adea2)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:invoke_padata_reorder
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_parallel_worker
```
```
In security/smack/smack_lsm.c (ffffffff817147ba)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smk_ipv4_check
  - security/smack/smack_lsm.c:smack_netlbl_add
```
```
In lib/irq_poll.c (ffffffff81927b10)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_cpu_dead
```
```
In drivers/net/tun.c (ffffffff81d01027)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_rx_batched
  - drivers/net/tun.c:tun_rx_batched
  - drivers/net/tun.c:tun_napi_alloc_frags
```
```
In drivers/net/virtio_net.c (ffffffff81d0abcb)
Location: include/linux/bottom_half.h:11
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
In drivers/net/ppp/ppp_generic.c (ffffffff81d1a635)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
```
```
In drivers/net/xen-netfront.c (ffffffff81d219aa)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:netfront_resume
```
```
In drivers/net/net_failover.c (ffffffff81d243eb)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - drivers/net/net_failover.c:net_failover_slave_register
  - drivers/net/net_failover.c:net_failover_close
  - drivers/net/net_failover.c:net_failover_open
```
```
In net/core/sock.c (ffffffff81ec5395)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/core/sock.c:sock_i_ino
```
```
In net/core/skbuff.c (ffffffff81ed348b)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_frag_align
  - net/core/skbuff.c:napi_get_frags_check
```
```
In net/core/gen_estimator.c (ffffffff81ee1171)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/dev.c (ffffffff81efe1d3)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:__dev_set_allmulti
  - net/core/dev.c:dev_set_promiscuity
  - net/core/dev.c:napi_threaded_poll
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:flush_backlog
  - net/core/dev.c:__dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_open
```
```
In net/core/dev_addr_lists.c (ffffffff81f02b65)
Location: include/linux/bottom_half.h:11
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
In net/core/rtnetlink.c (ffffffff81f1590e)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_fdb_dump
```
```
In net/core/filter.c (ffffffff81f28fb6)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/core/filter.c:bpf_out_neigh_v6
```
```
In net/core/net-procfs.c (ffffffff81f469f1)
Location: include/linux/bottom_half.h:11
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff81f6080e)
Location: include/linux/bottom_half.h:11
Inline: True
```
```
In net/core/sock_map.c (ffffffff81f69a2c)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_update_elem
```
```
In net/sched/sch_generic.c (ffffffff81f70f52)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
```
```
In net/bpf/test_run.c (ffffffff81f91f18)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_test_run
```
```
In net/netfilter/nf_log.c (ffffffff81fac925)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/netfilter/nf_log.c:nf_log_buf_open
```
```
In net/netfilter/nf_queue.c (ffffffff81fad950)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_reinject
```
```
In net/ipv4/inet_hashtables.c (ffffffff81fc7ba0)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81fc8f4d)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81fcaf33)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/tcp.c (ffffffff81fd4b88)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_abort
  - net/ipv4/tcp.c:tcp_abort
  - net/ipv4/tcp.c:tcp_abort
  - net/ipv4/tcp.c:__tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff81fe460f)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff3951)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ff8694)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/icmp.c (ffffffff82011b09)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_reply
```
```
In net/ipv4/fib_frontend.c (ffffffff820231f2)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_lookup
```
```
In net/ipv4/tcp_sigpool.c (ffffffff8204c935)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/ipv4/tcp_sigpool.c:tcp_sigpool_start
```
```
In net/xfrm/xfrm_input.c (ffffffff8206df05)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/espintcp.c (ffffffff82074d68)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:handle_esp
```
```
In net/ipv6/addrconf.c (ffffffff82093874)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
```
```
In net/ipv6/route.c (ffffffff820a31a9)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route
```
```
In net/ipv6/icmp.c (ffffffff820bed5c)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/seg6_hmac.c (ffffffff820eded1)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
```
```
In net/mptcp/protocol.c (ffffffff8214d6a1)
Location: include/linux/bottom_half.h:11
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_finish_join
```
```
In net/mptcp/subflow.c (ffffffff8214e43c)
Location: include/linux/bottom_half.h:11
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
In kernel/softirq.c (ffff8000100ff134)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/softirq.c:irq_enter
  - kernel/softirq.c:__do_softirq
```
```
In kernel/irq/manage.c (ffff800010179bf8)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_forced_thread_fn
```
```
In kernel/rcu/update.c (ffff800010188f1c)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/srcutree.c (ffff80001018a8b0)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
```
```
In kernel/rcu/tree.c (ffff8000101904c4)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_cpu_kthread
```
```
In kernel/time/hrtimer.c (ffff8000101a2768)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
```
```
In kernel/cgroup/cgroup.c (ffff8000101d0d78)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_idr_remove
  - kernel/cgroup/cgroup.c:cgroup_idr_replace
```
```
In kernel/bpf/core.c (ffff80001025e1cc)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
```
```
In kernel/bpf/syscall.c (ffff8000102654fc)
Location: include/linux/bottom_half.h:10
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
Location: include/linux/bottom_half.h:10
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
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
```
```
In kernel/bpf/cpumap.c (ffff800010288144)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In kernel/bpf/xskmap.c (ffff800010289618)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/bpf/xskmap.c:xsk_map_try_sock_delete
  - kernel/bpf/xskmap.c:xsk_map_delete_elem
  - kernel/bpf/xskmap.c:xsk_map_update_elem
  - kernel/bpf/xskmap.c:xsk_map_update_elem
  - kernel/bpf/xskmap.c:xsk_map_sock_delete
```
```
In kernel/bpf/offload.c (ffff80001028a1f4)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In kernel/bpf/reuseport_array.c (ffff800010290808)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem
  - kernel/bpf/reuseport_array.c:reuseport_array_free
  - kernel/bpf/reuseport_array.c:reuseport_array_delete_elem
  - kernel/bpf/reuseport_array.c:reuseport_array_delete_elem
  - kernel/bpf/reuseport_array.c:bpf_sk_reuseport_detach
```
```
In kernel/padata.c (ffff8000102a9b9c)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:invoke_padata_reorder
  - kernel/padata.c:padata_reorder
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_parallel_worker
```
```
In mm/page-writeback.c (ffff8000102ba700)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - mm/page-writeback.c:bdi_set_max_ratio
  - mm/page-writeback.c:bdi_set_min_ratio
```
```
In mm/backing-dev.c (ffff8000102debf4)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:bdi_register_va
  - mm/backing-dev.c:bdi_get_by_id
  - mm/backing-dev.c:wb_wakeup_delayed
```
```
In fs/fs-writeback.c (ffff8000103cb148)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_queue_work
  - fs/fs-writeback.c:wb_wakeup
```
```
In ipc/util.c (ffff80001051d480)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/selinux/netif.c (ffff800010557e3c)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_netdev_notifier_handler
  - security/selinux/netif.c:sel_netif_flush
  - security/selinux/netif.c:sel_netif_sid
```
```
In security/selinux/netnode.c (ffff8000105586a8)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_flush
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (ffff800010558ab8)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_flush
  - security/selinux/netport.c:sel_netport_sid
```
```
In security/smack/smack_lsm.c (ffff80001056f438)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_netlabel
```
```
In security/apparmor/policy_unpack.c (ffff80001059897c)
Location: include/linux/bottom_half.h:10
Inline: True
```
```
In block/genhd.c (ffff8000105fa3c4)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - block/genhd.c:get_gendisk
```
```
In block/blk-cgroup.c (ffff80001060e700)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - block/blk-cgroup.c:__blkcg_punt_bio_submit
  - block/blk-cgroup.c:blkg_async_bio_workfn
```
```
In lib/rhashtable.c (ffff800010636b48)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In drivers/dma/dmaengine.c (ffff8000107fcfb0)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_run_dependencies
```
```
In drivers/dma/mv_xor.c (ffff800010806cc0)
Location: include/linux/bottom_half.h:10
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
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - drivers/dma/mv_xor_v2.c:mv_xor_v2_tasklet
  - drivers/dma/mv_xor_v2.c:mv_xor_v2_issue_pending
  - drivers/dma/mv_xor_v2.c:mv_xor_v2_prep_sw_desc
  - drivers/dma/mv_xor_v2.c:mv_xor_v2_tx_submit
```
```
In drivers/connector/cn_queue.c (ffff8000108dd6a4)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_free_dev
  - drivers/connector/cn_queue.c:cn_queue_del_callback
  - drivers/connector/cn_queue.c:cn_queue_add_callback
```
```
In drivers/connector/connector.c (ffff8000108ddc24)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_proc_show
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/net/tun.c (ffff8000109e13a4)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:__tun_set_ebpf
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_flow_update
  - drivers/net/tun.c:tun_flow_flush
```
```
In drivers/net/ethernet/freescale/fec_main.c (ffff8000109ea6ec)
Location: include/linux/bottom_half.h:10
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
In drivers/net/ppp/ppp_generic.c (ffff8000109ffe78)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_disconnect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_disconnect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_disconnect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_ccp_closed
  - drivers/net/ppp/ppp_generic.c:ppp_ccp_closed
  - drivers/net/ppp/ppp_generic.c:ppp_set_compress
  - drivers/net/ppp/ppp_generic.c:ppp_set_compress
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_name
  - drivers/net/ppp/ppp_generic.c:ppp_unit_number
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_input_error
  - drivers/net/ppp/ppp_generic.c:ppp_input_error
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_input
  - drivers/net/ppp/ppp_generic.c:ppp_channel_push
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
In drivers/net/xen-netfront.c (ffff800010a091d8)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:netback_changed
  - drivers/net/xen-netfront.c:xennet_open
```
```
In net/core/sock.c (ffff800010bada38)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:release_sock
  - net/core/sock.c:lock_sock_nested
  - net/core/sock.c:__sk_flush_backlog
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__lock_sock
  - net/core/sock.c:sock_i_ino
  - net/core/sock.c:sock_i_uid
```
```
In net/core/request_sock.c (ffff800010bb034c)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/core/skbuff.c (ffff800010bb50d8)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:netdev_alloc_frag
```
```
In net/core/datagram.c (ffff800010bbc90c)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/core/datagram.c:__sk_queue_drop_skb
```
```
In net/core/gen_stats.c (ffff800010bbf2f8)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/core/gen_stats.c:gnet_stats_start_copy_compat
```
```
In net/core/gen_estimator.c (ffff800010bbf8dc)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/net_namespace.c (ffff800010bc1960)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:peernet2id
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/dev.c (ffff800010bd5ab4)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/core/dev.c:dev_set_rx_mode
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:flush_backlog
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:netif_set_real_num_tx_queues
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:list_netdevice
```
```
In net/core/dev_addr_lists.c (ffff800010bdf6b4)
Location: include/linux/bottom_half.h:10
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
In net/core/neighbour.c (ffff800010be2700)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_seq_start
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_for_each
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:neigh_fill_info
  - net/core/neighbour.c:neightbl_dump_info
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:pneigh_delete
  - net/core/neighbour.c:pneigh_lookup
  - net/core/neighbour.c:pneigh_lookup
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
  - net/core/neighbour.c:__neigh_ifdown
  - net/core/neighbour.c:neigh_changeaddr
```
```
In net/core/rtnetlink.c (ffff800010beebec)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_fdb_dump
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:set_operstate
```
```
In net/core/link_watch.c (ffff800010bf3764)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/core/link_watch.c:rfc2863_policy
```
```
In net/core/sock_reuseport.c (ffff800010c0529c)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_attach_prog
  - net/core/sock_reuseport.c:reuseport_detach_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_alloc
```
```
In net/core/xdp.c (ffff800010c06798)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffff800010c08620)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/core/page_pool.c (ffff800010c0cabc)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
```
```
In net/core/net-procfs.c (ffff800010c0dfe0)
Location: include/linux/bottom_half.h:10
Inline: True
```
```
In net/core/skmsg.c (ffff800010c0f6f8)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_data_ready
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_link_pop
```
```
In net/core/netpoll.c (ffff800010c11898)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
```
```
In net/core/sock_map.c (ffff800010c21c98)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/core/sock_map.c:sk_psock_unlink
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:__sock_map_delete
  - net/core/sock_map.c:sock_map_unref
  - net/core/sock_map.c:sock_map_unref
```
```
In net/core/devlink.c (ffff800010c2add8)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_port_type_set
  - net/core/devlink.c:devlink_nl_port_fill
```
```
In net/core/bpf_sk_storage.c (ffff800010c32184)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_free
  - net/core/bpf_sk_storage.c:sk_storage_update
  - net/core/bpf_sk_storage.c:__sk_storage_lookup
  - net/core/bpf_sk_storage.c:selem_link_map
  - net/core/bpf_sk_storage.c:selem_unlink_map
  - net/core/bpf_sk_storage.c:selem_unlink_sk
```
```
In net/sched/sch_generic.c (ffff800010c3a010)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_graft_qdisc
```
```
In net/sched/sch_mq.c (ffff800010c3b0e4)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump
```
```
In net/sched/sch_api.c (ffff800010c3d094)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/sched/sch_api.c:tcf_node_bind
  - net/sched/sch_api.c:qdisc_class_hash_grow
```
```
In net/netlink/af_netlink.c (ffff800010c4f038)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/netfilter/nf_log.c (ffff800010c55954)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/netfilter/nf_log.c:nf_log_buf_open
```
```
In net/netfilter/nf_queue.c (ffff800010c560d4)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_reinject
```
```
In net/ipv4/route.c (ffff800010c5a8c8)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_flush_dev
  - net/ipv4/route.c:rt_add_uncached_list
  - net/ipv4/route.c:find_exception
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/inetpeer.c (ffff800010c5da24)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/ip_output.c (ffff800010c6359c)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_hashtables.c (ffff800010c6b30c)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffff800010c6bfb4)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/inet_connection_sock.c (ffff800010c6da90)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_child_forget
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
```
```
In net/ipv4/tcp.c (ffff800010c75884)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (ffff800010c80f44)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8c51c)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/tcp_minisocks.c (ffff800010c901c8)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/tcp_metrics.c (ffff800010c925d4)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_flush_all
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/raw.c (ffff800010c97310)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_ioctl
  - net/ipv4/raw.c:raw_unhash_sk
  - net/ipv4/raw.c:raw_hash_sk
```
```
In net/ipv4/udp.c (ffff800010c9bad4)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/arp.c (ffff800010ca3204)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_req_delete
```
```
In net/ipv4/icmp.c (ffff800010ca4aa0)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/af_inet.c (ffff800010cabc24)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_register_protosw
  - net/ipv4/af_inet.c:inet_accept
```
```
In net/ipv4/igmp.c (ffff800010cb0388)
Location: include/linux/bottom_half.h:10
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
In net/ipv4/fib_frontend.c (ffff800010cb3944)
Location: include/linux/bottom_half.h:10
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffff800010cb9d14)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_release_info
```
```
In net/ipv4/inet_fragment.c (ffff800010cbf46c)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/inet_fragment.c:inet_frags_free_cb
```
```
In net/ipv4/ping.c (ffff800010cc0b40)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_seq_start
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_unhash
  - net/ipv4/ping.c:ping_get_port
```
```
In net/ipv4/nexthop.c (ffff800010cc4edc)
Location: include/linux/bottom_half.h:10
Inline: True
```
```
In net/ipv4/sysctl_net_ipv4.c (ffff800010cc745c)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
```
In net/ipv4/ipmr.c (ffff800010ccbf2c)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
```
```
In net/ipv4/ipmr_base.c (ffff800010cd0f30)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_table_dump
  - net/ipv4/ipmr_base.c:mr_mfc_seq_next
```
```
In net/ipv4/tcp_bpf.c (ffff800010cd477c)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_init
```
```
In net/ipv4/cipso_ipv4.c (ffff800010cd5414)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_invalidate
```
```
In net/xfrm/xfrm_policy.c (ffff800010cdd5a0)
Location: include/linux/bottom_half.h:10
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
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
```
```
In net/xfrm/xfrm_state.c (ffff800010ce5048)
Location: include/linux/bottom_half.h:10
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
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo
  - net/xfrm/xfrm_input.c:xfrm_input_register_afinfo
```
```
In net/xfrm/xfrm_output.c (ffff800010cebfd4)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/unix/af_unix.c (ffff800010cf1594)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_accept
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/ipv6/af_inet6.c (ffff800010cf6444)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_register_protosw
```
```
In net/ipv6/anycast.c (ffff800010cf6ef0)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ac6_seq_start
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/ip6_output.c (ffff800010cfa2e0)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/addrconf.c (ffff800010d0ab18)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_disable_policy_idev
  - net/ipv6/addrconf.c:ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_dad_run
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_start
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:ipv6_generate_stable_address
  - net/ipv6/addrconf.c:add_addr
  - net/ipv6/addrconf.c:inet6_addr_del
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:manage_tempaddrs
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:ipv6_get_lladdr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffff800010d119d0)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_del_rt
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:fib6_table_lookup
  - net/ipv6/route.c:fib6_nh_remove_exception
  - net/ipv6/route.c:fib6_nh_flush_exceptions
  - net/ipv6/route.c:rt6_insert_exception
  - net/ipv6/route.c:rt6_insert_exception
  - net/ipv6/route.c:__ip6_ins_rt
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
  - net/ipv6/route.c:rt6_uncached_list_add
```
```
In net/ipv6/ip6_fib.c (ffff800010d19f78)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_start
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:__fib6_clean_all
  - net/ipv6/ip6_fib.c:fib6_update_sernum_stub
  - net/ipv6/ip6_fib.c:fib6_tables_dump
  - net/ipv6/ip6_fib.c:fib6_walker_unlink
  - net/ipv6/ip6_fib.c:fib6_walker_link
```
```
In net/ipv6/ipv6_sockglue.c (ffff800010d1dcb0)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ip6_ra_control
```
```
In net/ipv6/ndisc.c (ffff800010d230d0)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_unsol_na
```
```
In net/ipv6/raw.c (ffff800010d292d0)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_ioctl
```
```
In net/ipv6/icmp.c (ffff800010d2c5dc)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffff800010d30874)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mcf_seq_next
  - net/ipv6/mcast.c:igmp6_mcf_seq_next
  - net/ipv6/mcast.c:igmp6_mcf_seq_start
  - net/ipv6/mcast.c:igmp6_mcf_seq_start
  - net/ipv6/mcast.c:igmp6_mc_seq_start
  - net/ipv6/mcast.c:ipv6_mc_netdev_event
  - net/ipv6/mcast.c:ipv6_mc_destroy_dev
  - net/ipv6/mcast.c:ipv6_mc_destroy_dev
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:ipv6_mc_up
  - net/ipv6/mcast.c:ipv6_mc_down
  - net/ipv6/mcast.c:ipv6_mc_unmap
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:ip6_mc_leave_src
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:ip6_mc_del_src
  - net/ipv6/mcast.c:ip6_mc_del_src
  - net/ipv6/mcast.c:mld_send_report
  - net/ipv6/mcast.c:mld_send_report
  - net/ipv6/mcast.c:mld_send_report
  - net/ipv6/mcast.c:igmp6_event_report
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:ipv6_chk_mcast_addr
  - net/ipv6/mcast.c:__ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:mld_del_delrec
  - net/ipv6/mcast.c:mld_del_delrec
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/mcast.c:igmp6_group_dropped
  - net/ipv6/mcast.c:igmp6_group_added
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
```
```
In net/ipv6/ip6_flowlabel.c (ffff800010d3eef0)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt_get
  - net/ipv6/ip6_flowlabel.c:fl6_renew
  - net/ipv6/ip6_flowlabel.c:fl6_free_socklist
  - net/ipv6/ip6_flowlabel.c:fl6_free_socklist
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:fl_release
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In net/ipv6/ip6mr.c (ffff800010d466b8)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
  - net/ipv6/ip6mr.c:mif6_delete
```
```
In net/ipv6/calipso.c (ffff800010d4e7c4)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_cache_invalidate
```
```
In net/ipv6/seg6_hmac.c (ffff800010d51e70)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
```
```
In net/ipv6/inet6_hashtables.c (ffff800010d553a4)
Location: include/linux/bottom_half.h:10
Inline: True
```
```
In net/packet/af_packet.c (ffff800010d5bd38)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_poll
  - net/packet/af_packet.c:packet_ioctl
  - net/packet/af_packet.c:packet_getsockopt
  - net/packet/af_packet.c:packet_release
```
```
In net/dcb/dcbnl.c (ffff800010d6fbdc)
Location: include/linux/bottom_half.h:10
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
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_deferred_process
```
```
In net/xdp/xsk.c (ffff800010d7e728)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xsk.c:xsk_generic_rcv
```
```
In lib/xarray.c (ffff800010d9b358)
Location: include/linux/bottom_half.h:10
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
In kernel/softirq.c (c035be44)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/softirq.c:irq_enter
  - kernel/softirq.c:__do_softirq
```
```
In kernel/locking/spinlock.c (c0e9f248)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_lock_bh
  - kernel/locking/spinlock.c:_raw_read_lock_bh
  - kernel/locking/spinlock.c:_raw_spin_trylock_bh
  - kernel/locking/spinlock.c:_raw_spin_lock_bh
```
```
In kernel/irq/manage.c (c03cb14c)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_forced_thread_fn
```
```
In kernel/rcu/update.c (c03d77f4)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/srcutree.c (c03d82ec)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
```
```
In kernel/rcu/tree.c (c03de0c0)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_cpu_kthread
```
```
In kernel/time/hrtimer.c (c03ec444)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
```
```
In kernel/bpf/cpumap.c (c04b840c)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In kernel/bpf/offload.c (c04b9878)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In kernel/padata.c (c04d7e00)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:invoke_padata_reorder
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_parallel_worker
```
```
In ipc/util.c (c06d9864)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/smack/smack_lsm.c (c0721490)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_netlabel
```
```
In security/apparmor/policy_unpack.c (c0749bb0)
Location: include/linux/bottom_half.h:10
Inline: True
```
```
In lib/rhashtable.c (c07dc870)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In drivers/net/tun.c (c0ac6cf0)
Location: include/linux/bottom_half.h:10
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
Location: include/linux/bottom_half.h:10
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
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
```
```
In net/core/skbuff.c (c0cd21b0)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:netdev_alloc_frag
```
```
In net/core/gen_estimator.c (c0cdb39c)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/dev.c (c0cee974)
Location: include/linux/bottom_half.h:10
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
Location: include/linux/bottom_half.h:10
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
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (c0d2170c)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/sched/sch_generic.c (c0d4c2ac)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
```
```
In net/netlink/af_netlink.c (c0d5f2ac)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/netfilter/nf_log.c (c0d65380)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/netfilter/nf_log.c:nf_log_buf_open
```
```
In net/netfilter/nf_queue.c (c0d65b48)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_reinject
```
```
In net/ipv4/route.c (c0d66bb4)
Location: include/linux/bottom_half.h:10
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
Location: include/linux/bottom_half.h:10
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
Location: include/linux/bottom_half.h:10
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
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward_finish
```
```
In net/ipv4/ip_output.c (c0d75358)
Location: include/linux/bottom_half.h:10
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
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (c0d7adb0)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/inet_connection_sock.c (c0d7bfe0)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/tcp.c (c0d83f88)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (c0d901a8)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
```
In net/ipv4/tcp_ipv4.c (c0d9be7c)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/tcp_minisocks.c (c0d9e3fc)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/datagram.c (c0da4838)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (c0da5ba8)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/udp.c (c0da93cc)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/icmp.c (c0db0be4)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/fib_frontend.c (c0dbf378)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
```
```
In net/ipv4/fib_semantics.c (c0dc567c)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/inet_fragment.c (c0dcade0)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ping.c (c0dcccd8)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/nexthop.c (c0dd09a4)
Location: include/linux/bottom_half.h:10
Inline: True
```
```
In net/ipv4/ipmr.c (c0dd74b4)
Location: include/linux/bottom_half.h:10
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
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/unix/af_unix.c (c0df79a8)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/ipv6/ip6_output.c (c0dfeae8)
Location: include/linux/bottom_half.h:10
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
```
```
In net/ipv6/ip6_input.c (c0e05434)
Location: include/linux/bottom_half.h:10
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
In net/ipv6/addrconf.c (c0e08e58)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (c0e12d00)
Location: include/linux/bottom_half.h:10
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
In net/ipv6/ip6_fib.c (c0e1ee94)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_start
```
```
In net/ipv6/ipv6_sockglue.c (c0e246d0)
Location: include/linux/bottom_half.h:10
Inline: True
```
```
In net/ipv6/raw.c (c0e2dd58)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/icmp.c (c0e304c8)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
```
```
In net/ipv6/mcast.c (c0e33b00)
Location: include/linux/bottom_half.h:10
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
In net/ipv6/reassembly.c (c0e37ab0)
Location: include/linux/bottom_half.h:10
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
In net/ipv6/exthdrs.c (c0e3d0c4)
Location: include/linux/bottom_half.h:10
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
In net/ipv6/ip6_flowlabel.c (c0e4182c)
Location: include/linux/bottom_half.h:10
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
In net/ipv6/ip6mr.c (c0e46988)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_forward2
  - net/ipv6/ip6mr.c:ip6mr_forward2
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/netfilter.c (c0e4b764)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_hmac.c (c0e52f18)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
```
```
In net/ipv6/inet6_hashtables.c (c0e55960)
Location: include/linux/bottom_half.h:10
Inline: True
```
```
In net/xdp/xsk.c (c0e79134)
Location: include/linux/bottom_half.h:10
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
In kernel/softirq.c (c000000000146430)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/softirq.c:irq_enter
  - kernel/softirq.c:__do_softirq
```
```
In kernel/locking/spinlock.c (c000000000eea3c0)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_lock_bh
  - kernel/locking/spinlock.c:_raw_read_lock_bh
  - kernel/locking/spinlock.c:_raw_spin_trylock_bh
  - kernel/locking/spinlock.c:_raw_spin_lock_bh
```
```
In kernel/irq/manage.c (c0000000001d4588)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_forced_thread_fn
```
```
In kernel/rcu/update.c (c0000000001e31ec)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/srcutree.c (c0000000001e5970)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
```
```
In kernel/rcu/tree.c (c0000000001eb7d4)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_cpu_kthread
```
```
In kernel/time/hrtimer.c (c000000000203cf8)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
```
```
In kernel/bpf/cpumap.c (c0000000003337d4)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In kernel/bpf/offload.c (c0000000003355b8)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In kernel/padata.c (c00000000035cd0c)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:invoke_padata_reorder
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_parallel_worker
```
```
In ipc/util.c (c0000000006665f0)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/smack/smack_lsm.c (c0000000006d340c)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_netlabel
```
```
In security/apparmor/policy_unpack.c (c00000000070f900)
Location: include/linux/bottom_half.h:10
Inline: True
```
```
In lib/rhashtable.c (c0000000007dca38)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In drivers/net/tun.c (c000000000aa3060)
Location: include/linux/bottom_half.h:10
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
Location: include/linux/bottom_half.h:10
Inline: True
```
```
In net/core/skbuff.c (c000000000c8c080)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:netdev_alloc_frag
```
```
In net/core/gen_estimator.c (c000000000c98cb4)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/dev.c (c000000000cb29d4)
Location: include/linux/bottom_half.h:10
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
Location: include/linux/bottom_half.h:10
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
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_allocator_disconnect
```
```
In net/core/flow_offload.c (c000000000cf2c64)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/sched/sch_generic.c (c000000000d33084)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
```
```
In net/netlink/af_netlink.c (c000000000d4d888)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/netfilter/nf_log.c (c000000000d557f0)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/netfilter/nf_log.c:nf_log_buf_open
```
```
In net/netfilter/nf_queue.c (c000000000d56968)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_reinject
```
```
In net/ipv4/route.c (c000000000d5b2f0)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (c000000000d668b0)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_hashtables.c (c000000000d6e89c)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (c000000000d715bc)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/inet_connection_sock.c (c000000000d72ec4)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/tcp.c (c000000000d7d0b4)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (c000000000d8bdec)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
```
In net/ipv4/tcp_ipv4.c (c000000000d9aa4c)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/tcp_minisocks.c (c000000000d9e1b8)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/icmp.c (c000000000db7e1c)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/fib_frontend.c (c000000000dca94c)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_lookup
```
```
In net/ipv4/fib_semantics.c (c000000000dd2e48)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/inet_fragment.c (c000000000dda0e0)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/nexthop.c (c000000000de1250)
Location: include/linux/bottom_half.h:10
Inline: True
```
```
In net/ipv4/ipmr.c (c000000000deb428)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (c000000000dfcd1c)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/unix/af_unix.c (c000000000e148a4)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/ipv6/ip6_output.c (c000000000e1f2ac)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/addrconf.c (c000000000e2b23c)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (c000000000e4155c)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ip6_fib.c (c000000000e46ef8)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_start
```
```
In net/ipv6/ipv6_sockglue.c (c000000000e4dcfc)
Location: include/linux/bottom_half.h:10
Inline: True
```
```
In net/ipv6/icmp.c (c000000000e5deb4)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ip6_flowlabel.c (c000000000e72cb4)
Location: include/linux/bottom_half.h:10
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
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (c000000000e8aa3c)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
```
```
In net/ipv6/inet6_hashtables.c (c000000000e8e1a8)
Location: include/linux/bottom_half.h:10
Inline: True
```
```
In net/xdp/xsk.c (c000000000ebe74c)
Location: include/linux/bottom_half.h:10
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
In kernel/softirq.c (ffffffe0000c7050)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/softirq.c:irq_enter
  - kernel/softirq.c:__do_softirq
```
```
In kernel/locking/spinlock.c (ffffffe0008c96a0)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_lock_bh
  - kernel/locking/spinlock.c:_raw_read_lock_bh
  - kernel/locking/spinlock.c:_raw_spin_trylock_bh
  - kernel/locking/spinlock.c:_raw_spin_lock_bh
```
```
In kernel/rcu/update.c (ffffffe00011e286)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/srcutree.c (ffffffe00011fc2a)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
```
```
In kernel/rcu/tree.c (ffffffe000122ffe)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_cpu_kthread
```
```
In kernel/bpf/cpumap.c (ffffffe0001bce16)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In kernel/bpf/offload.c (ffffffe0001be35a)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In kernel/padata.c (ffffffe0001d2e46)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:invoke_padata_reorder
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_parallel_worker
```
```
In ipc/util.c (ffffffe000384d74)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/smack/smack_lsm.c (ffffffe0003c25b0)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_netlabel
```
```
In security/apparmor/policy_unpack.c (ffffffe0003e52f8)
Location: include/linux/bottom_half.h:10
Inline: True
```
```
In lib/rhashtable.c (ffffffe0004640f8)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In drivers/net/tun.c (ffffffe00062aefa)
Location: include/linux/bottom_half.h:10
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
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
```
```
In net/core/skbuff.c (ffffffe0007451a4)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:netdev_alloc_frag
```
```
In net/core/gen_estimator.c (ffffffe00074d298)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/dev.c (ffffffe00075dc96)
Location: include/linux/bottom_half.h:10
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
Location: include/linux/bottom_half.h:10
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
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_allocator_disconnect
```
```
In net/core/flow_offload.c (ffffffe00078646c)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/sched/sch_generic.c (ffffffe0007ab25c)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
```
```
In net/netlink/af_netlink.c (ffffffe0007badd6)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/netfilter/nf_log.c (ffffffe0007bf85c)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/netfilter/nf_log.c:nf_log_buf_open
```
```
In net/netfilter/nf_queue.c (ffffffe0007c03d4)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_reinject
```
```
In net/ipv4/route.c (ffffffe0007c31f8)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffe0007cabda)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_hashtables.c (ffffffe0007cfcc6)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffe0007d1958)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/inet_connection_sock.c (ffffffe0007d2d96)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/tcp.c (ffffffe0007d8a92)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffe0007e2ea4)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
```
In net/ipv4/tcp_ipv4.c (ffffffe0007ed54c)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/tcp_minisocks.c (ffffffe0007ef690)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/icmp.c (ffffffe0007ffd88)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/fib_frontend.c (ffffffe00080b776)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_lookup
```
```
In net/ipv4/fib_semantics.c (ffffffe000810800)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/inet_fragment.c (ffffffe00081524a)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/nexthop.c (ffffffe00081a246)
Location: include/linux/bottom_half.h:10
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffe000820904)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffe00082c0fe)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/unix/af_unix.c (ffffffe00083d270)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/ipv6/ip6_output.c (ffffffe000843cb2)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/addrconf.c (ffffffe00084b1fe)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffe00085a02c)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ip6_fib.c (ffffffe00085dc36)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_start
```
```
In net/ipv6/ipv6_sockglue.c (ffffffe000861b8a)
Location: include/linux/bottom_half.h:10
Inline: True
```
```
In net/ipv6/icmp.c (ffffffe00086c84e)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ip6_flowlabel.c (ffffffe00087aa94)
Location: include/linux/bottom_half.h:10
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
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffe00088a55e)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
```
```
In net/ipv6/inet6_hashtables.c (ffffffe00088cb76)
Location: include/linux/bottom_half.h:10
Inline: True
```
```
In net/xdp/xsk.c (ffffffe0008ac140)
Location: include/linux/bottom_half.h:10
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
In arch/x86/kernel/fpu/core.c (ffffffff8103ed73)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:fpu__save
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103fc6d)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff810406fa)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/mm/pkeys.c (ffffffff8108d808)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:copy_init_pkru_to_fpregs
```
```
In kernel/softirq.c (ffffffff810a1978)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/softirq.c:irq_enter
  - kernel/softirq.c:__do_softirq
```
```
In kernel/locking/spinlock.c (ffffffff81a73aa5)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_lock_bh
  - kernel/locking/spinlock.c:_raw_read_lock_bh
  - kernel/locking/spinlock.c:_raw_spin_trylock_bh
  - kernel/locking/spinlock.c:_raw_spin_lock_bh
```
```
In kernel/irq/manage.c (ffffffff8110fd35)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_forced_thread_fn
```
```
In kernel/rcu/update.c (ffffffff8111c26f)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/srcutree.c (ffffffff8111db5e)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
```
```
In kernel/rcu/tree.c (ffffffff8112162f)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_cpu_kthread
```
```
In kernel/time/hrtimer.c (ffffffff8113138b)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
```
```
In kernel/bpf/cpumap.c (ffffffff811f906f)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In kernel/bpf/offload.c (ffffffff811fa467)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In kernel/padata.c (ffffffff81215b22)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:invoke_padata_reorder
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_parallel_worker
```
```
In ipc/util.c (ffffffff8142f39e)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/smack/smack_lsm.c (ffffffff8147543f)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_netlabel
```
```
In security/apparmor/policy_unpack.c (ffffffff8149b220)
Location: include/linux/bottom_half.h:10
Inline: True
```
```
In lib/rhashtable.c (ffffffff81523a2b)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In drivers/net/tun.c (ffffffff8178ad4c)
Location: include/linux/bottom_half.h:10
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
In drivers/net/ppp/ppp_generic.c (ffffffff8178efb5)
Location: include/linux/bottom_half.h:10
Inline: True
```
```
In net/core/skbuff.c (ffffffff818bad76)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:netdev_alloc_frag
```
```
In net/core/gen_estimator.c (ffffffff818c409c)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/dev.c (ffffffff818d5843)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:flush_backlog
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/neighbour.c (ffffffff818e1de5)
Location: include/linux/bottom_half.h:10
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
In net/core/xdp.c (ffffffff81902c71)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff81903e89)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/sched/sch_generic.c (ffffffff8192e58a)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
```
```
In net/netlink/af_netlink.c (ffffffff81940857)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/netfilter/nf_log.c (ffffffff81945b9c)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/netfilter/nf_log.c:nf_log_buf_open
```
```
In net/netfilter/nf_queue.c (ffffffff819466bc)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_reinject
```
```
In net/ipv4/route.c (ffffffff819497e6)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff819524ff)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_hashtables.c (ffffffff819588c5)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff8195a2b7)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8195baa2)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/tcp.c (ffffffff81962968)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff8196e353)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81978e7f)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8197c13a)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/icmp.c (ffffffff8198e58c)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/fib_frontend.c (ffffffff8199b775)
Location: include/linux/bottom_half.h:10
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff819a1466)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/inet_fragment.c (ffffffff819a63c5)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/nexthop.c (ffffffff819ab579)
Location: include/linux/bottom_half.h:10
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff819b211c)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff819c0c92)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/unix/af_unix.c (ffffffff819d02bb)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/ipv6/ip6_output.c (ffffffff819d6d79)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/addrconf.c (ffffffff819df6f5)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff819eff83)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ip6_fib.c (ffffffff819f40ca)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_start
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff819f9a3b)
Location: include/linux/bottom_half.h:10
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff81a05d07)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81a1514f)
Location: include/linux/bottom_half.h:10
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
In net/ipv6/ip6mr.c (ffffffff81a1a386)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a258eb)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a27e46)
Location: include/linux/bottom_half.h:10
Inline: True
```
```
In net/xdp/xsk.c (ffffffff81a4a431)
Location: include/linux/bottom_half.h:10
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
In arch/x86/kernel/fpu/core.c (ffffffff8102e573)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:fpu__save
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8102f46d)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8102feda)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/mm/pkeys.c (ffffffff8107c338)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:copy_init_pkru_to_fpregs
```
```
In kernel/softirq.c (ffffffff81090338)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/softirq.c:irq_enter
  - kernel/softirq.c:__do_softirq
```
```
In kernel/locking/spinlock.c (ffffffff81a2feb5)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_lock_bh
  - kernel/locking/spinlock.c:_raw_read_lock_bh
  - kernel/locking/spinlock.c:_raw_spin_trylock_bh
  - kernel/locking/spinlock.c:_raw_spin_lock_bh
```
```
In kernel/irq/manage.c (ffffffff81100a65)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_forced_thread_fn
```
```
In kernel/rcu/update.c (ffffffff8110d2ec)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/srcutree.c (ffffffff8110ebf2)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
```
```
In kernel/rcu/tree.c (ffffffff81112133)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_nocb_cb_kthread
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_do_batch
```
```
In kernel/time/hrtimer.c (ffffffff81123dfb)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
```
```
In kernel/bpf/cpumap.c (ffffffff811ebdbf)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In kernel/bpf/offload.c (ffffffff811ed1b7)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In kernel/padata.c (ffffffff81208882)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:invoke_padata_reorder
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_parallel_worker
```
```
In ipc/util.c (ffffffff8141fe1e)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/smack/smack_lsm.c (ffffffff81465e5f)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_netlabel
```
```
In security/apparmor/policy_unpack.c (ffffffff8148bc40)
Location: include/linux/bottom_half.h:10
Inline: True
```
```
In lib/rhashtable.c (ffffffff81513d0b)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In drivers/net/tun.c (ffffffff8176a69c)
Location: include/linux/bottom_half.h:10
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
In drivers/net/ppp/ppp_generic.c (ffffffff81777d85)
Location: include/linux/bottom_half.h:10
Inline: True
```
```
In net/core/skbuff.c (ffffffff81874cc1)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:netdev_alloc_frag
```
```
In net/core/gen_estimator.c (ffffffff8187dfdc)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/dev.c (ffffffff8188f6b3)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:flush_backlog
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/neighbour.c (ffffffff8189bc25)
Location: include/linux/bottom_half.h:10
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
In net/core/xdp.c (ffffffff818bcaa1)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff818bdcb9)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/sched/sch_generic.c (ffffffff818e808a)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
```
```
In net/netlink/af_netlink.c (ffffffff818fa347)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/netfilter/nf_log.c (ffffffff818ff68c)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/netfilter/nf_log.c:nf_log_buf_open
```
```
In net/netfilter/nf_queue.c (ffffffff819001ac)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_reinject
```
```
In net/ipv4/route.c (ffffffff819032d6)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff8190bfef)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_hashtables.c (ffffffff819123b5)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81913da7)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81915592)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/tcp.c (ffffffff8191c458)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff81927e43)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8193293f)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81935bfa)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/icmp.c (ffffffff8194804c)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/fib_frontend.c (ffffffff81955235)
Location: include/linux/bottom_half.h:10
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff8195af26)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/inet_fragment.c (ffffffff8195fe85)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/nexthop.c (ffffffff81965039)
Location: include/linux/bottom_half.h:10
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff8196e74c)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197da82)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/unix/af_unix.c (ffffffff8198d07b)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/ipv6/ip6_output.c (ffffffff81993b39)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/addrconf.c (ffffffff8199c4b5)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff819acd43)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ip6_fib.c (ffffffff819b0e8a)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_start
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff819b67fb)
Location: include/linux/bottom_half.h:10
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff819c2ac7)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff819d1f0f)
Location: include/linux/bottom_half.h:10
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
In net/ipv6/ip6mr.c (ffffffff819d7146)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff819e26ab)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
```
```
In net/ipv6/inet6_hashtables.c (ffffffff819e4c06)
Location: include/linux/bottom_half.h:10
Inline: True
```
```
In net/xdp/xsk.c (ffffffff81a07021)
Location: include/linux/bottom_half.h:10
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
In arch/x86/kernel/fpu/core.c (ffffffff8103ebb3)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:fpu__save
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103faad)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8104053a)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/mm/pkeys.c (ffffffff8108d7b8)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:copy_init_pkru_to_fpregs
```
```
In kernel/softirq.c (ffffffff810a1928)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/softirq.c:irq_enter
  - kernel/softirq.c:__do_softirq
```
```
In kernel/locking/spinlock.c (ffffffff81adfeb5)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_lock_bh
  - kernel/locking/spinlock.c:_raw_read_lock_bh
  - kernel/locking/spinlock.c:_raw_spin_trylock_bh
  - kernel/locking/spinlock.c:_raw_spin_lock_bh
```
```
In kernel/irq/manage.c (ffffffff8110dc25)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_forced_thread_fn
```
```
In kernel/rcu/update.c (ffffffff8111a15f)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/srcutree.c (ffffffff8111ba4e)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
```
```
In kernel/rcu/tree.c (ffffffff8111f51f)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_cpu_kthread
```
```
In kernel/time/hrtimer.c (ffffffff8112f0ab)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
```
```
In kernel/bpf/cpumap.c (ffffffff811f6e3f)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In kernel/bpf/offload.c (ffffffff811f8237)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In kernel/padata.c (ffffffff812138c2)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:invoke_padata_reorder
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_parallel_worker
```
```
In ipc/util.c (ffffffff8142b53e)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/smack/smack_lsm.c (ffffffff814714df)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_netlabel
```
```
In security/apparmor/policy_unpack.c (ffffffff814972c0)
Location: include/linux/bottom_half.h:10
Inline: True
```
```
In lib/rhashtable.c (ffffffff8151fabb)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In drivers/net/tun.c (ffffffff817bb0ec)
Location: include/linux/bottom_half.h:10
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
In drivers/net/ppp/ppp_generic.c (ffffffff817bf355)
Location: include/linux/bottom_half.h:10
Inline: True
```
```
In net/core/skbuff.c (ffffffff8190bd76)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:netdev_alloc_frag
```
```
In net/core/gen_estimator.c (ffffffff8191509c)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/dev.c (ffffffff81926873)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:flush_backlog
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/neighbour.c (ffffffff81932e15)
Location: include/linux/bottom_half.h:10
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
In net/core/xdp.c (ffffffff81953ca1)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff81954eb9)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/sched/sch_generic.c (ffffffff8197f71a)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
```
```
In net/netlink/af_netlink.c (ffffffff819919e7)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/netfilter/nf_log.c (ffffffff81996d2c)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/netfilter/nf_log.c:nf_log_buf_open
```
```
In net/netfilter/nf_queue.c (ffffffff8199784c)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_reinject
```
```
In net/netfilter/nfnetlink_log.c (ffffffff8199b205)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/netfilter/nfnetlink_log.c:seq_start
  - net/netfilter/nfnetlink_log.c:instance_lookup_get
```
```
In net/netfilter/nf_conntrack_core.c (ffffffff819a06ca)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_core.c:nf_conntrack_hash_resize
  - net/netfilter/nf_conntrack_core.c:nf_ct_iterate_cleanup
  - net/netfilter/nf_conntrack_core.c:__nf_conntrack_confirm
  - net/netfilter/nf_conntrack_core.c:nf_conntrack_hash_check_insert
  - net/netfilter/nf_conntrack_core.c:nf_ct_delete_from_lists
  - net/netfilter/nf_conntrack_core.c:destroy_conntrack
```
```
In net/netfilter/nf_conntrack_ecache.c (ffffffff819a92b5)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_ecache.c:ecache_work
```
```
In net/netfilter/nf_conntrack_netlink.c (ffffffff819b083a)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_dump_table
```
```
In net/ipv4/route.c (ffffffff819b3fb6)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff819bcccf)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_hashtables.c (ffffffff819c3095)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff819c4a87)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819c6272)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/tcp.c (ffffffff819cd138)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff819d8b23)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819e364f)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819e690a)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/icmp.c (ffffffff819f8e2c)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/fib_frontend.c (ffffffff81a06015)
Location: include/linux/bottom_half.h:10
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff81a0bd06)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/inet_fragment.c (ffffffff81a10c65)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/nexthop.c (ffffffff81a15e19)
Location: include/linux/bottom_half.h:10
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81a1c9bc)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/netfilter/nf_defrag_ipv4.c (ffffffff81a20c6e)
Location: include/linux/bottom_half.h:10
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a2b712)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/unix/af_unix.c (ffffffff81a3ad3b)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/ipv6/ip6_output.c (ffffffff81a417f9)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/addrconf.c (ffffffff81a4a175)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff81a5aa03)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ip6_fib.c (ffffffff81a5eb4a)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_start
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81a644bb)
Location: include/linux/bottom_half.h:10
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff81a70787)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81a7fbcf)
Location: include/linux/bottom_half.h:10
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
In net/ipv6/ip6mr.c (ffffffff81a84e06)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a9036b)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a939f6)
Location: include/linux/bottom_half.h:10
Inline: True
```
```
In net/xdp/xsk.c (ffffffff81ab62e1)
Location: include/linux/bottom_half.h:10
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
In arch/x86/kernel/fpu/core.c (ffffffff8103fe5a)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:fpu__save
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81040dd5)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81041910)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/mm/pkeys.c (ffffffff8108fb7f)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:copy_init_pkru_to_fpregs
```
```
In kernel/softirq.c (ffffffff810a9918)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/softirq.c:irq_enter
  - kernel/softirq.c:__do_softirq
```
```
In kernel/locking/spinlock.c (ffffffff81aec805)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_lock_bh
  - kernel/locking/spinlock.c:_raw_read_lock_bh
  - kernel/locking/spinlock.c:_raw_spin_trylock_bh
  - kernel/locking/spinlock.c:_raw_spin_lock_bh
```
```
In kernel/irq/manage.c (ffffffff81118f15)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_forced_thread_fn
```
```
In kernel/rcu/update.c (ffffffff811258b7)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/srcutree.c (ffffffff81125f9c)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
```
```
In kernel/rcu/tree.c (ffffffff8112b673)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_cpu_kthread
```
```
In kernel/time/hrtimer.c (ffffffff8113baab)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
```
```
In kernel/bpf/cpumap.c (ffffffff81205122)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In kernel/bpf/offload.c (ffffffff81206596)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In kernel/padata.c (ffffffff81222882)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:invoke_padata_reorder
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_parallel_worker
```
```
In ipc/util.c (ffffffff814424d0)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/smack/smack_lsm.c (ffffffff81488dcf)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_netlabel
```
```
In security/apparmor/policy_unpack.c (ffffffff814af398)
Location: include/linux/bottom_half.h:10
Inline: True
```
```
In lib/rhashtable.c (ffffffff815393a0)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In drivers/net/tun.c (ffffffff817d411d)
Location: include/linux/bottom_half.h:10
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
In drivers/net/ppp/ppp_generic.c (ffffffff817d95e5)
Location: include/linux/bottom_half.h:10
Inline: True
```
```
In net/core/skbuff.c (ffffffff8192ce96)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:netdev_alloc_frag
```
```
In net/core/gen_estimator.c (ffffffff8193621c)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/dev.c (ffffffff81947e7f)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:flush_backlog
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/neighbour.c (ffffffff81954745)
Location: include/linux/bottom_half.h:10
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
In net/core/xdp.c (ffffffff81975424)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff81976e94)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/sched/sch_generic.c (ffffffff819a1c7a)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
```
```
In net/netlink/af_netlink.c (ffffffff819b44d7)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/netfilter/nf_log.c (ffffffff819b99ec)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/netfilter/nf_log.c:nf_log_buf_open
```
```
In net/netfilter/nf_queue.c (ffffffff819ba52c)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_reinject
```
```
In net/ipv4/route.c (ffffffff819bd6a6)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff819c65df)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_hashtables.c (ffffffff819cc5a5)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff819ce51d)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819cfd58)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/tcp.c (ffffffff819d6cc8)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff819e2778)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819ed76f)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819f05ca)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/icmp.c (ffffffff81a02dab)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/fib_frontend.c (ffffffff81a10666)
Location: include/linux/bottom_half.h:10
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff81a164f6)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/inet_fragment.c (ffffffff81a1b542)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/nexthop.c (ffffffff81a20859)
Location: include/linux/bottom_half.h:10
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81a27978)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a36d5a)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/unix/af_unix.c (ffffffff81a45fb9)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/ipv6/ip6_output.c (ffffffff81a4d459)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/addrconf.c (ffffffff81a560b5)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff81a66c9f)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ip6_fib.c (ffffffff81a6afca)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_start
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81a709d1)
Location: include/linux/bottom_half.h:10
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff81a7cda7)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81a8c48f)
Location: include/linux/bottom_half.h:10
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
In net/ipv6/ip6mr.c (ffffffff81a91782)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a9cf65)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a9fb46)
Location: include/linux/bottom_half.h:10
Inline: True
```
```
In net/xdp/xsk.c (ffffffff81ac2401)
Location: include/linux/bottom_half.h:10
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
  - net/xdp/xsk.c:xsk_release
```
</details>
</li>
</ul>

## Differences
