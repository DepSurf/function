# Function: <code>__preempt_count_add</code>

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
In arch/x86/kernel/traps.c (ffffffff8102f22f)
Location: arch/x86/include/asm/preempt.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_debug
  - arch/x86/kernel/traps.c:do_debug
  - arch/x86/kernel/traps.c:ist_end_non_atomic
  - arch/x86/kernel/traps.c:do_double_fault
```
```
In arch/x86/kernel/nmi.c (ffffffff81032a01)
Location: arch/x86/include/asm/preempt.h:67
Inline: True
```
```
In kernel/softirq.c (ffffffff810858bd)
Location: arch/x86/include/asm/preempt.h:67
Inline: True
Inline callers:
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:irq_enter
  - kernel/softirq.c:irq_enter
```
```
In kernel/sched/core.c (ffffffff81820676)
Location: arch/x86/include/asm/preempt.h:67
Inline: True
```
```
In kernel/locking/spinlock.c (ffffffff81823fe6)
Location: arch/x86/include/asm/preempt.h:67
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_spin_lock_bh
  - kernel/locking/spinlock.c:_raw_spin_trylock_bh
  - kernel/locking/spinlock.c:_raw_write_lock_bh
  - kernel/locking/spinlock.c:_raw_read_lock_bh
```
```
In kernel/irq/manage.c (ffffffff810dbb16)
Location: arch/x86/include/asm/preempt.h:67
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_forced_thread_fn
```
```
In kernel/rcu/srcu.c (ffffffff810e3f41)
Location: arch/x86/include/asm/preempt.h:67
Inline: True
Inline callers:
  - kernel/rcu/srcu.c:process_srcu
```
```
In kernel/padata.c (ffffffff811898e6)
Location: arch/x86/include/asm/preempt.h:67
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_parallel_worker
  - kernel/padata.c:padata_serial_worker
```
```
In security/smack/smack_lsm.c (ffffffff8135e4a6)
Location: arch/x86/include/asm/preempt.h:67
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_netlabel
```
```
In crypto/chainiv.c (ffffffff813a2340)
Location: arch/x86/include/asm/preempt.h:67
Inline: True
Inline callers:
  - crypto/chainiv.c:async_chainiv_do_postponed
```
```
In drivers/net/virtio_net.c (ffffffff815f1967)
Location: arch/x86/include/asm/preempt.h:67
Inline: True
```
```
In net/socket.c (ffffffff816fdfc8)
Location: arch/x86/include/asm/preempt.h:67
Inline: True
Inline callers:
  - net/socket.c:sock_poll
```
```
In net/core/datagram.c (ffffffff8170cc65)
Location: arch/x86/include/asm/preempt.h:67
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_recv_datagram
```
```
In net/core/dev.c (ffffffff8171cd9f)
Location: arch/x86/include/asm/preempt.h:67
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/dst.c (ffffffff81723865)
Location: arch/x86/include/asm/preempt.h:67
Inline: True
Inline callers:
  - net/core/dst.c:dst_init
  - net/core/dst.c:dst_destroy
```
```
In net/core/neighbour.c (ffffffff81724460)
Location: arch/x86/include/asm/preempt.h:67
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
Location: arch/x86/include/asm/preempt.h:67
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_lookup
  - net/core/flow.c:flow_cache_flush
```
```
In net/sched/sch_generic.c (ffffffff81741c3e)
Location: arch/x86/include/asm/preempt.h:67
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
```
```
In net/netlink/af_netlink.c (ffffffff8174b708)
Location: arch/x86/include/asm/preempt.h:67
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/netfilter/nf_log.c (ffffffff817522bc)
Location: arch/x86/include/asm/preempt.h:67
Inline: True
Inline callers:
  - net/netfilter/nf_log.c:nf_log_buf_open
```
```
In net/netfilter/nf_queue.c (ffffffff81752a13)
Location: arch/x86/include/asm/preempt.h:67
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_reinject
```
```
In net/ipv4/route.c (ffffffff81754153)
Location: arch/x86/include/asm/preempt.h:67
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_cpu_seq_show
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/ip_fragment.c (ffffffff8175a676)
Location: arch/x86/include/asm/preempt.h:67
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_mem
```
```
In net/ipv4/ip_output.c (ffffffff8175d053)
Location: arch/x86/include/asm/preempt.h:67
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_hashtables.c (ffffffff817623f6)
Location: arch/x86/include/asm/preempt.h:67
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_put_port
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff817638c2)
Location: arch/x86/include/asm/preempt.h:67
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81763bc0)
Location: arch/x86/include/asm/preempt.h:67
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_get_port
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/tcp.c (ffffffff8176590d)
Location: arch/x86/include/asm/preempt.h:67
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_init_sock
  - net/ipv4/tcp.c:tcp_prequeue_process
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff81770791)
Location: arch/x86/include/asm/preempt.h:67
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
```
In net/ipv4/icmp.c (ffffffff8178e5b1)
Location: arch/x86/include/asm/preempt.h:67
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_send
```
```
In net/ipv4/fib_frontend.c (ffffffff8179a163)
Location: arch/x86/include/asm/preempt.h:67
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
```
```
In net/ipv4/inet_fragment.c (ffffffff817a1b19)
Location: arch/x86/include/asm/preempt.h:67
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_worker
  - net/ipv4/inet_fragment.c:inet_frags_exit_net
```
```
In net/ipv4/proc.c (ffffffff817a5f80)
Location: arch/x86/include/asm/preempt.h:67
Inline: True
Inline callers:
  - net/ipv4/proc.c:sockstat_seq_show
```
```
In net/ipv4/xfrm4_policy.c (ffffffff817af417)
Location: arch/x86/include/asm/preempt.h:67
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_garbage_collect
```
```
In net/unix/af_unix.c (ffffffff817be096)
Location: arch/x86/include/asm/preempt.h:67
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/ipv6/ip6_output.c (ffffffff817c517a)
Location: arch/x86/include/asm/preempt.h:67
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/addrconf.c (ffffffff817c9381)
Location: arch/x86/include/asm/preempt.h:67
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
Location: arch/x86/include/asm/preempt.h:67
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_dst_gc
  - net/ipv6/route.c:rt6_stats_seq_show
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ip6_fib.c (ffffffff817d9c8f)
Location: arch/x86/include/asm/preempt.h:67
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_start
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff817ddde7)
Location: arch/x86/include/asm/preempt.h:67
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff817e79e3)
Location: arch/x86/include/asm/preempt.h:67
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_echo_reply
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff817f5c76)
Location: arch/x86/include/asm/preempt.h:67
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
Location: arch/x86/include/asm/preempt.h:67
Inline: True
Inline callers:
  - net/ipv6/proc.c:sockstat6_seq_show
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81802293)
Location: arch/x86/include/asm/preempt.h:67
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup
```
```
In net/packet/af_packet.c (ffffffff818037b5)
Location: arch/x86/include/asm/preempt.h:67
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
In arch/x86/kernel/nmi.c (ffffffff81031b86)
Location: arch/x86/include/asm/preempt.h:67
Inline: True
```
```
In kernel/softirq.c (ffffffff81088a1f)
Location: arch/x86/include/asm/preempt.h:67
Inline: True
Inline callers:
  - kernel/softirq.c:irq_enter
  - kernel/softirq.c:irq_enter
  - kernel/softirq.c:__do_softirq
```
```
In kernel/sched/core.c (ffffffff8189aad7)
Location: arch/x86/include/asm/preempt.h:67
Inline: True
```
```
In kernel/locking/spinlock.c (ffffffff8189ee35)
Location: arch/x86/include/asm/preempt.h:67
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_lock_bh
  - kernel/locking/spinlock.c:_raw_read_lock_bh
  - kernel/locking/spinlock.c:_raw_spin_trylock_bh
  - kernel/locking/spinlock.c:_raw_spin_lock_bh
```
```
In kernel/irq/manage.c (ffffffff810e0e56)
Location: arch/x86/include/asm/preempt.h:67
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_forced_thread_fn
```
```
In kernel/rcu/update.c (ffffffff810e967b)
Location: arch/x86/include/asm/preempt.h:67
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/srcu.c (ffffffff810ea249)
Location: arch/x86/include/asm/preempt.h:67
Inline: True
Inline callers:
  - kernel/rcu/srcu.c:process_srcu
```
```
In kernel/stop_machine.c (ffffffff81128208)
Location: arch/x86/include/asm/preempt.h:67
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
```
```
In kernel/padata.c (ffffffff8119c1f2)
Location: arch/x86/include/asm/preempt.h:67
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_parallel_worker
```
```
In security/smack/smack_lsm.c (ffffffff813945fd)
Location: arch/x86/include/asm/preempt.h:67
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_netlabel
```
```
In drivers/net/virtio_net.c (ffffffff81651278)
Location: arch/x86/include/asm/preempt.h:67
Inline: True
```
```
In net/core/dev.c (ffffffff817833f0)
Location: arch/x86/include/asm/preempt.h:67
Inline: True
Inline callers:
  - net/core/dev.c:sk_busy_loop
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/dst.c (ffffffff8178d991)
Location: arch/x86/include/asm/preempt.h:67
Inline: True
Inline callers:
  - net/core/dst.c:dst_destroy
  - net/core/dst.c:dst_init
```
```
In net/core/neighbour.c (ffffffff8178f039)
Location: arch/x86/include/asm/preempt.h:67
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
Location: arch/x86/include/asm/preempt.h:67
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_flush
  - net/core/flow.c:flow_cache_lookup
```
```
In net/sched/sch_generic.c (ffffffff817aeaee)
Location: arch/x86/include/asm/preempt.h:67
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
```
```
In net/netlink/af_netlink.c (ffffffff817ba21e)
Location: arch/x86/include/asm/preempt.h:67
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_create
```
```
In net/netfilter/nf_log.c (ffffffff817be2cc)
Location: arch/x86/include/asm/preempt.h:67
Inline: True
Inline callers:
  - net/netfilter/nf_log.c:nf_log_buf_open
```
```
In net/netfilter/nf_queue.c (ffffffff817beb23)
Location: arch/x86/include/asm/preempt.h:67
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_reinject
```
```
In net/ipv4/route.c (ffffffff817c3650)
Location: arch/x86/include/asm/preempt.h:67
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:rt_cpu_seq_show
```
```
In net/ipv4/ip_fragment.c (ffffffff817c6a36)
Location: arch/x86/include/asm/preempt.h:67
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_mem
```
```
In net/ipv4/ip_output.c (ffffffff817c9e13)
Location: arch/x86/include/asm/preempt.h:67
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_hashtables.c (ffffffff817ce7a1)
Location: arch/x86/include/asm/preempt.h:67
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff817cfd96)
Location: arch/x86/include/asm/preempt.h:67
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/inet_connection_sock.c (ffffffff817d11dd)
Location: arch/x86/include/asm/preempt.h:67
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
```
```
In net/ipv4/tcp.c (ffffffff817d6db2)
Location: arch/x86/include/asm/preempt.h:67
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_ipv4.c (ffffffff817ea45e)
Location: arch/x86/include/asm/preempt.h:67
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/icmp.c (ffffffff817fbbbd)
Location: arch/x86/include/asm/preempt.h:67
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_send
```
```
In net/ipv4/fib_frontend.c (ffffffff81808040)
Location: arch/x86/include/asm/preempt.h:67
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
```
```
In net/ipv4/fib_semantics.c (ffffffff8180bfd6)
Location: arch/x86/include/asm/preempt.h:67
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/inet_fragment.c (ffffffff8180fa52)
Location: arch/x86/include/asm/preempt.h:67
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frags_exit_net
  - net/ipv4/inet_fragment.c:inet_frag_worker
```
```
In net/ipv4/proc.c (ffffffff81813c20)
Location: arch/x86/include/asm/preempt.h:67
Inline: True
Inline callers:
  - net/ipv4/proc.c:sockstat_seq_show
```
```
In net/ipv4/xfrm4_policy.c (ffffffff8181c317)
Location: arch/x86/include/asm/preempt.h:67
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_garbage_collect
```
```
In net/unix/af_unix.c (ffffffff8182b02a)
Location: arch/x86/include/asm/preempt.h:67
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/ipv6/ip6_output.c (ffffffff81831d6a)
Location: arch/x86/include/asm/preempt.h:67
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/addrconf.c (ffffffff818390b6)
Location: arch/x86/include/asm/preempt.h:67
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
Location: arch/x86/include/asm/preempt.h:67
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_stats_seq_show
  - net/ipv6/route.c:ip6_dst_gc
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ip6_fib.c (ffffffff81847df9)
Location: arch/x86/include/asm/preempt.h:67
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_start
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff8184be6f)
Location: arch/x86/include/asm/preempt.h:67
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff8185683e)
Location: arch/x86/include/asm/preempt.h:67
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81864d56)
Location: arch/x86/include/asm/preempt.h:67
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
Location: arch/x86/include/asm/preempt.h:67
Inline: True
Inline callers:
  - net/ipv6/proc.c:sockstat6_seq_show
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81872f6e)
Location: arch/x86/include/asm/preempt.h:67
Inline: True
```
```
In net/packet/af_packet.c (ffffffff818749f5)
Location: arch/x86/include/asm/preempt.h:67
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
In arch/x86/kernel/nmi.c (ffffffff810317e3)
Location: arch/x86/include/asm/preempt.h:73
Inline: True
```
```
In kernel/softirq.c (ffffffff8108d96b)
Location: arch/x86/include/asm/preempt.h:73
Inline: True
Inline callers:
  - kernel/softirq.c:irq_enter
  - kernel/softirq.c:irq_enter
  - kernel/softirq.c:__do_softirq
```
```
In kernel/sched/core.c (ffffffff818cf0dd)
Location: arch/x86/include/asm/preempt.h:73
Inline: True
```
```
In kernel/locking/spinlock.c (ffffffff818d42f5)
Location: arch/x86/include/asm/preempt.h:73
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_lock_bh
  - kernel/locking/spinlock.c:_raw_read_lock_bh
  - kernel/locking/spinlock.c:_raw_spin_trylock_bh
  - kernel/locking/spinlock.c:_raw_spin_lock_bh
```
```
In kernel/irq/manage.c (ffffffff810e7da6)
Location: arch/x86/include/asm/preempt.h:73
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_forced_thread_fn
```
```
In kernel/rcu/update.c (ffffffff810f053a)
Location: arch/x86/include/asm/preempt.h:73
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/srcu.c (ffffffff810f1129)
Location: arch/x86/include/asm/preempt.h:73
Inline: True
Inline callers:
  - kernel/rcu/srcu.c:process_srcu
```
```
In kernel/stop_machine.c (ffffffff81131e08)
Location: arch/x86/include/asm/preempt.h:73
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
```
```
In kernel/padata.c (ffffffff811aba62)
Location: arch/x86/include/asm/preempt.h:73
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_parallel_worker
```
```
In security/smack/smack_lsm.c (ffffffff813ab13d)
Location: arch/x86/include/asm/preempt.h:73
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_netlabel
```
```
In drivers/net/tun.c (ffffffff8167f9b2)
Location: arch/x86/include/asm/preempt.h:73
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81685ce6)
Location: arch/x86/include/asm/preempt.h:73
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_channel_push
```
```
In net/core/dev.c (ffffffff817aed49)
Location: arch/x86/include/asm/preempt.h:73
Inline: True
Inline callers:
  - net/core/dev.c:sk_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:flush_backlog
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/dst.c (ffffffff817bb261)
Location: arch/x86/include/asm/preempt.h:73
Inline: True
Inline callers:
  - net/core/dst.c:dst_destroy
  - net/core/dst.c:dst_init
```
```
In net/core/neighbour.c (ffffffff817bc8f6)
Location: arch/x86/include/asm/preempt.h:73
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
Location: arch/x86/include/asm/preempt.h:73
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_flush
  - net/core/flow.c:flow_cache_lookup
```
```
In net/sched/sch_generic.c (ffffffff817de16e)
Location: arch/x86/include/asm/preempt.h:73
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
```
```
In net/netlink/af_netlink.c (ffffffff817e9c3c)
Location: arch/x86/include/asm/preempt.h:73
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_create
```
```
In net/netfilter/nf_log.c (ffffffff817edc0c)
Location: arch/x86/include/asm/preempt.h:73
Inline: True
Inline callers:
  - net/netfilter/nf_log.c:nf_log_buf_open
```
```
In net/netfilter/nf_queue.c (ffffffff817ee467)
Location: arch/x86/include/asm/preempt.h:73
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_reinject
```
```
In net/ipv4/route.c (ffffffff817f2c78)
Location: arch/x86/include/asm/preempt.h:73
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:rt_cpu_seq_show
```
```
In net/ipv4/ip_fragment.c (ffffffff817f6536)
Location: arch/x86/include/asm/preempt.h:73
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_mem
```
```
In net/ipv4/ip_output.c (ffffffff817f90fb)
Location: arch/x86/include/asm/preempt.h:73
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_hashtables.c (ffffffff817fe5b1)
Location: arch/x86/include/asm/preempt.h:73
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff817ffb86)
Location: arch/x86/include/asm/preempt.h:73
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8180109d)
Location: arch/x86/include/asm/preempt.h:73
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
```
```
In net/ipv4/tcp.c (ffffffff81806dd2)
Location: arch/x86/include/asm/preempt.h:73
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_input.c (ffffffff81810990)
Location: arch/x86/include/asm/preempt.h:73
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81818c56)
Location: arch/x86/include/asm/preempt.h:73
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/icmp.c (ffffffff8182cb0d)
Location: arch/x86/include/asm/preempt.h:73
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_send
```
```
In net/ipv4/fib_frontend.c (ffffffff81839110)
Location: arch/x86/include/asm/preempt.h:73
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
```
```
In net/ipv4/fib_semantics.c (ffffffff8183d0f6)
Location: arch/x86/include/asm/preempt.h:73
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/inet_fragment.c (ffffffff81840fa2)
Location: arch/x86/include/asm/preempt.h:73
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frags_exit_net
  - net/ipv4/inet_fragment.c:inet_frag_worker
```
```
In net/ipv4/proc.c (ffffffff8184511d)
Location: arch/x86/include/asm/preempt.h:73
Inline: True
Inline callers:
  - net/ipv4/proc.c:sockstat_seq_show
```
```
In net/ipv4/xfrm4_policy.c (ffffffff8184dbd7)
Location: arch/x86/include/asm/preempt.h:73
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_garbage_collect
```
```
In net/unix/af_unix.c (ffffffff8185ca5a)
Location: arch/x86/include/asm/preempt.h:73
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/ipv6/ip6_output.c (ffffffff81863d0e)
Location: arch/x86/include/asm/preempt.h:73
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/addrconf.c (ffffffff8186aad6)
Location: arch/x86/include/asm/preempt.h:73
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
Location: arch/x86/include/asm/preempt.h:73
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_stats_seq_show
  - net/ipv6/route.c:ip6_dst_gc
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ip6_fib.c (ffffffff81879c36)
Location: arch/x86/include/asm/preempt.h:73
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_start
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff8187dd22)
Location: arch/x86/include/asm/preempt.h:73
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff81888640)
Location: arch/x86/include/asm/preempt.h:73
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81897436)
Location: arch/x86/include/asm/preempt.h:73
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
Location: arch/x86/include/asm/preempt.h:73
Inline: True
Inline callers:
  - net/ipv6/proc.c:sockstat6_seq_show
```
```
In net/ipv6/seg6_hmac.c (ffffffff818a4a2e)
Location: arch/x86/include/asm/preempt.h:73
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
```
```
In net/ipv6/inet6_hashtables.c (ffffffff818a7594)
Location: arch/x86/include/asm/preempt.h:73
Inline: True
```
```
In net/packet/af_packet.c (ffffffff818a8f45)
Location: arch/x86/include/asm/preempt.h:73
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
In arch/x86/kernel/nmi.c (ffffffff8102f9f3)
Location: arch/x86/include/asm/preempt.h:73
Inline: True
```
```
In kernel/softirq.c (ffffffff8108a99b)
Location: arch/x86/include/asm/preempt.h:73
Inline: True
Inline callers:
  - kernel/softirq.c:irq_enter
  - kernel/softirq.c:irq_enter
  - kernel/softirq.c:__do_softirq
```
```
In kernel/sched/core.c (ffffffff8190663f)
Location: arch/x86/include/asm/preempt.h:73
Inline: True
```
```
In kernel/locking/spinlock.c (ffffffff8190b495)
Location: arch/x86/include/asm/preempt.h:73
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_lock_bh
  - kernel/locking/spinlock.c:_raw_read_lock_bh
  - kernel/locking/spinlock.c:_raw_spin_trylock_bh
  - kernel/locking/spinlock.c:_raw_spin_lock_bh
```
```
In kernel/irq/manage.c (ffffffff810e6c66)
Location: arch/x86/include/asm/preempt.h:73
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_forced_thread_fn
```
```
In kernel/rcu/update.c (ffffffff810f0546)
Location: arch/x86/include/asm/preempt.h:73
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/srcutree.c (ffffffff810f18bb)
Location: arch/x86/include/asm/preempt.h:73
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
```
```
In kernel/stop_machine.c (ffffffff811333c4)
Location: arch/x86/include/asm/preempt.h:73
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
```
```
In kernel/padata.c (ffffffff811b2ec2)
Location: arch/x86/include/asm/preempt.h:73
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_parallel_worker
```
```
In security/smack/smack_lsm.c (ffffffff813c1a54)
Location: arch/x86/include/asm/preempt.h:73
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_netlabel
```
```
In drivers/net/tun.c (ffffffff81694c9e)
Location: arch/x86/include/asm/preempt.h:73
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8169b206)
Location: arch/x86/include/asm/preempt.h:73
Inline: True
```
```
In net/core/dev.c (ffffffff817cd697)
Location: arch/x86/include/asm/preempt.h:73
Inline: True
Inline callers:
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:flush_backlog
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/neighbour.c (ffffffff817dafc6)
Location: arch/x86/include/asm/preempt.h:73
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
Location: arch/x86/include/asm/preempt.h:73
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_flush
  - net/core/flow.c:flow_cache_lookup
```
```
In net/sched/sch_generic.c (ffffffff817fd7be)
Location: arch/x86/include/asm/preempt.h:73
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
```
```
In net/netlink/af_netlink.c (ffffffff8180981a)
Location: arch/x86/include/asm/preempt.h:73
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_create
```
```
In net/netfilter/nf_log.c (ffffffff8180dc3c)
Location: arch/x86/include/asm/preempt.h:73
Inline: True
Inline callers:
  - net/netfilter/nf_log.c:nf_log_buf_open
```
```
In net/netfilter/nf_queue.c (ffffffff8180e4f9)
Location: arch/x86/include/asm/preempt.h:73
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_reinject
```
```
In net/ipv4/route.c (ffffffff818102ba)
Location: arch/x86/include/asm/preempt.h:73
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81819513)
Location: arch/x86/include/asm/preempt.h:73
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_hashtables.c (ffffffff8181ebf1)
Location: arch/x86/include/asm/preempt.h:73
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff8181fd71)
Location: arch/x86/include/asm/preempt.h:73
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81820e09)
Location: arch/x86/include/asm/preempt.h:73
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/tcp.c (ffffffff818274b7)
Location: arch/x86/include/asm/preempt.h:73
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff81830be3)
Location: arch/x86/include/asm/preempt.h:73
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8183b374)
Location: arch/x86/include/asm/preempt.h:73
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/icmp.c (ffffffff8184df25)
Location: arch/x86/include/asm/preempt.h:73
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_send
```
```
In net/ipv4/fib_frontend.c (ffffffff8185a612)
Location: arch/x86/include/asm/preempt.h:73
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
```
```
In net/ipv4/fib_semantics.c (ffffffff8185e7ab)
Location: arch/x86/include/asm/preempt.h:73
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/inet_fragment.c (ffffffff81862832)
Location: arch/x86/include/asm/preempt.h:73
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frags_exit_net
  - net/ipv4/inet_fragment.c:inet_frag_worker
```
```
In net/unix/af_unix.c (ffffffff818811e8)
Location: arch/x86/include/asm/preempt.h:73
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/ipv6/ip6_output.c (ffffffff818892c6)
Location: arch/x86/include/asm/preempt.h:73
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/addrconf.c (ffffffff8188f046)
Location: arch/x86/include/asm/preempt.h:73
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
Location: arch/x86/include/asm/preempt.h:73
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ip6_fib.c (ffffffff8189f696)
Location: arch/x86/include/asm/preempt.h:73
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_start
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff818a32a2)
Location: arch/x86/include/asm/preempt.h:73
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff818aed98)
Location: arch/x86/include/asm/preempt.h:73
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff818bd846)
Location: arch/x86/include/asm/preempt.h:73
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
Location: arch/x86/include/asm/preempt.h:73
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
```
```
In net/ipv6/inet6_hashtables.c (ffffffff818cde96)
Location: arch/x86/include/asm/preempt.h:73
Inline: True
```
```
In net/packet/af_packet.c (ffffffff818cf92c)
Location: arch/x86/include/asm/preempt.h:73
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
In arch/x86/kernel/nmi.c (ffffffff81031a03)
Location: arch/x86/include/asm/preempt.h:74
Inline: True
```
```
In kernel/softirq.c (ffffffff8109166b)
Location: arch/x86/include/asm/preempt.h:74
Inline: True
Inline callers:
  - kernel/softirq.c:irq_enter
  - kernel/softirq.c:irq_enter
  - kernel/softirq.c:__do_softirq
```
```
In kernel/sched/core.c (ffffffff819906cc)
Location: arch/x86/include/asm/preempt.h:74
Inline: True
```
```
In kernel/locking/spinlock.c (ffffffff81995816)
Location: arch/x86/include/asm/preempt.h:74
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_lock_bh
  - kernel/locking/spinlock.c:_raw_read_lock_bh
  - kernel/locking/spinlock.c:_raw_spin_trylock_bh
  - kernel/locking/spinlock.c:_raw_spin_lock_bh
```
```
In kernel/irq/manage.c (ffffffff810eef36)
Location: arch/x86/include/asm/preempt.h:74
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_forced_thread_fn
```
```
In kernel/rcu/update.c (ffffffff810fa20c)
Location: arch/x86/include/asm/preempt.h:74
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/srcutree.c (ffffffff810fb61b)
Location: arch/x86/include/asm/preempt.h:74
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
```
```
In kernel/stop_machine.c (ffffffff81140074)
Location: arch/x86/include/asm/preempt.h:74
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
```
```
In kernel/bpf/cpumap.c (ffffffff811afcd8)
Location: arch/x86/include/asm/preempt.h:74
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In kernel/padata.c (ffffffff811c6b12)
Location: arch/x86/include/asm/preempt.h:74
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:invoke_padata_reorder
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_parallel_worker
```
```
In security/smack/smack_lsm.c (ffffffff813e80f4)
Location: arch/x86/include/asm/preempt.h:74
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_netlabel
```
```
In drivers/net/tun.c (ffffffff816ff5db)
Location: arch/x86/include/asm/preempt.h:74
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817059f6)
Location: arch/x86/include/asm/preempt.h:74
Inline: True
```
```
In net/core/gen_estimator.c (ffffffff8183bdbc)
Location: arch/x86/include/asm/preempt.h:74
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/dev.c (ffffffff81846dba)
Location: arch/x86/include/asm/preempt.h:74
Inline: True
Inline callers:
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:flush_backlog
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/neighbour.c (ffffffff81855776)
Location: arch/x86/include/asm/preempt.h:74
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
Location: arch/x86/include/asm/preempt.h:74
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
```
```
In net/netlink/af_netlink.c (ffffffff81888760)
Location: arch/x86/include/asm/preempt.h:74
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_create
```
```
In net/netfilter/nf_log.c (ffffffff8188d11c)
Location: arch/x86/include/asm/preempt.h:74
Inline: True
Inline callers:
  - net/netfilter/nf_log.c:nf_log_buf_open
```
```
In net/netfilter/nf_queue.c (ffffffff8188dafb)
Location: arch/x86/include/asm/preempt.h:74
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_reinject
```
```
In net/ipv4/route.c (ffffffff8188f30e)
Location: arch/x86/include/asm/preempt.h:74
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81897b23)
Location: arch/x86/include/asm/preempt.h:74
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_hashtables.c (ffffffff8189dba1)
Location: arch/x86/include/asm/preempt.h:74
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff8189ed3e)
Location: arch/x86/include/asm/preempt.h:74
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/inet_connection_sock.c (ffffffff818a0377)
Location: arch/x86/include/asm/preempt.h:74
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/tcp.c (ffffffff818a62c3)
Location: arch/x86/include/asm/preempt.h:74
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff818b004c)
Location: arch/x86/include/asm/preempt.h:74
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
```
In net/ipv4/tcp_ipv4.c (ffffffff818bb084)
Location: arch/x86/include/asm/preempt.h:74
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/tcp_minisocks.c (ffffffff818bddce)
Location: arch/x86/include/asm/preempt.h:74
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/icmp.c (ffffffff818cdc45)
Location: arch/x86/include/asm/preempt.h:74
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_send
```
```
In net/ipv4/fib_frontend.c (ffffffff818da532)
Location: arch/x86/include/asm/preempt.h:74
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
```
```
In net/ipv4/fib_semantics.c (ffffffff818de80f)
Location: arch/x86/include/asm/preempt.h:74
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/inet_fragment.c (ffffffff818e2952)
Location: arch/x86/include/asm/preempt.h:74
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frags_exit_net
  - net/ipv4/inet_fragment.c:inet_frag_worker
```
```
In net/xfrm/xfrm_policy.c (ffffffff818f842c)
Location: arch/x86/include/asm/preempt.h:74
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup
  - net/xfrm/xfrm_policy.c:xfrm_lookup
  - net/xfrm/xfrm_policy.c:xfrm_policy_cache_flush
  - net/xfrm/xfrm_policy.c:xfrm_pcpu_work_fn
```
```
In net/unix/af_unix.c (ffffffff81902378)
Location: arch/x86/include/asm/preempt.h:74
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/ipv6/ip6_output.c (ffffffff81909706)
Location: arch/x86/include/asm/preempt.h:74
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/addrconf.c (ffffffff81910696)
Location: arch/x86/include/asm/preempt.h:74
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff8191dcee)
Location: arch/x86/include/asm/preempt.h:74
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
Location: arch/x86/include/asm/preempt.h:74
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_start
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81925e57)
Location: arch/x86/include/asm/preempt.h:74
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff81931a9b)
Location: arch/x86/include/asm/preempt.h:74
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff819408e6)
Location: arch/x86/include/asm/preempt.h:74
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
Location: arch/x86/include/asm/preempt.h:74
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81952cb6)
Location: arch/x86/include/asm/preempt.h:74
Inline: True
```
```
In net/packet/af_packet.c (ffffffff8195489f)
Location: arch/x86/include/asm/preempt.h:74
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
In arch/x86/kernel/nmi.c (ffffffff81032b73)
Location: arch/x86/include/asm/preempt.h:74
Inline: True
```
```
In kernel/softirq.c (ffffffff8109513b)
Location: arch/x86/include/asm/preempt.h:74
Inline: True
Inline callers:
  - kernel/softirq.c:irq_enter
  - kernel/softirq.c:irq_enter
  - kernel/softirq.c:__do_softirq
```
```
In kernel/locking/spinlock.c (ffffffff819f1d55)
Location: arch/x86/include/asm/preempt.h:74
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_lock_bh
  - kernel/locking/spinlock.c:_raw_read_lock_bh
  - kernel/locking/spinlock.c:_raw_spin_trylock_bh
  - kernel/locking/spinlock.c:_raw_spin_lock_bh
```
```
In kernel/irq/manage.c (ffffffff810f7665)
Location: arch/x86/include/asm/preempt.h:74
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_forced_thread_fn
```
```
In kernel/rcu/update.c (ffffffff8110279a)
Location: arch/x86/include/asm/preempt.h:74
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/srcutree.c (ffffffff81103a98)
Location: arch/x86/include/asm/preempt.h:74
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
```
```
In kernel/time/hrtimer.c (ffffffff81116c8b)
Location: arch/x86/include/asm/preempt.h:74
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
```
```
In kernel/stop_machine.c (ffffffff8114ea7a)
Location: arch/x86/include/asm/preempt.h:74
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
```
```
In kernel/bpf/cpumap.c (ffffffff811cab18)
Location: arch/x86/include/asm/preempt.h:74
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In kernel/padata.c (ffffffff811e74e2)
Location: arch/x86/include/asm/preempt.h:74
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:invoke_padata_reorder
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_parallel_worker
```
```
In security/smack/smack_lsm.c (ffffffff81418f2d)
Location: arch/x86/include/asm/preempt.h:74
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_netlabel
```
```
In drivers/net/tun.c (ffffffff8173edc4)
Location: arch/x86/include/asm/preempt.h:74
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
Location: arch/x86/include/asm/preempt.h:74
Inline: True
```
```
In net/core/gen_estimator.c (ffffffff8188653c)
Location: arch/x86/include/asm/preempt.h:74
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/dev.c (ffffffff818904a4)
Location: arch/x86/include/asm/preempt.h:74
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
Location: arch/x86/include/asm/preempt.h:74
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
Location: arch/x86/include/asm/preempt.h:74
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
```
```
In net/netlink/af_netlink.c (ffffffff818dc193)
Location: arch/x86/include/asm/preempt.h:74
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_create
```
```
In net/netfilter/nf_log.c (ffffffff818e0b5c)
Location: arch/x86/include/asm/preempt.h:74
Inline: True
Inline callers:
  - net/netfilter/nf_log.c:nf_log_buf_open
```
```
In net/netfilter/nf_queue.c (ffffffff818e17d7)
Location: arch/x86/include/asm/preempt.h:74
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_reinject
```
```
In net/ipv4/route.c (ffffffff818e36ef)
Location: arch/x86/include/asm/preempt.h:74
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff818ebe53)
Location: arch/x86/include/asm/preempt.h:74
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_hashtables.c (ffffffff818f1d45)
Location: arch/x86/include/asm/preempt.h:74
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff818f3792)
Location: arch/x86/include/asm/preempt.h:74
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/inet_connection_sock.c (ffffffff818f56d1)
Location: arch/x86/include/asm/preempt.h:74
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/tcp.c (ffffffff818fb334)
Location: arch/x86/include/asm/preempt.h:74
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff819055a3)
Location: arch/x86/include/asm/preempt.h:74
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8191067c)
Location: arch/x86/include/asm/preempt.h:74
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8191280e)
Location: arch/x86/include/asm/preempt.h:74
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/icmp.c (ffffffff819243df)
Location: arch/x86/include/asm/preempt.h:74
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_send
```
```
In net/ipv4/fib_frontend.c (ffffffff81930f95)
Location: arch/x86/include/asm/preempt.h:74
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
```
```
In net/ipv4/fib_semantics.c (ffffffff8193537f)
Location: arch/x86/include/asm/preempt.h:74
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/xfrm/xfrm_policy.c (ffffffff8194ef17)
Location: arch/x86/include/asm/preempt.h:74
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup
  - net/xfrm/xfrm_policy.c:xfrm_lookup
  - net/xfrm/xfrm_policy.c:xfrm_policy_cache_flush
  - net/xfrm/xfrm_policy.c:xfrm_pcpu_work_fn
```
```
In net/unix/af_unix.c (ffffffff81959cc8)
Location: arch/x86/include/asm/preempt.h:74
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/ipv6/ip6_output.c (ffffffff81960a19)
Location: arch/x86/include/asm/preempt.h:74
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/addrconf.c (ffffffff81967ab5)
Location: arch/x86/include/asm/preempt.h:74
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff8197655c)
Location: arch/x86/include/asm/preempt.h:74
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
Location: arch/x86/include/asm/preempt.h:74
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_start
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff8197eb2a)
Location: arch/x86/include/asm/preempt.h:74
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff8198a552)
Location: arch/x86/include/asm/preempt.h:74
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff819997df)
Location: arch/x86/include/asm/preempt.h:74
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
Location: arch/x86/include/asm/preempt.h:74
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
```
```
In net/ipv6/inet6_hashtables.c (ffffffff819ac254)
Location: arch/x86/include/asm/preempt.h:74
Inline: True
```
```
In net/xdp/xsk.c (ffffffff819cbf12)
Location: arch/x86/include/asm/preempt.h:74
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
In arch/x86/kernel/nmi.c (ffffffff81033f23)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103cba5)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
```
In kernel/softirq.c (ffffffff8109d4ab)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/softirq.c:irq_enter
  - kernel/softirq.c:irq_enter
  - kernel/softirq.c:__do_softirq
```
```
In kernel/locking/spinlock.c (ffffffff81a2d305)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_lock_bh
  - kernel/locking/spinlock.c:_raw_read_lock_bh
  - kernel/locking/spinlock.c:_raw_spin_trylock_bh
  - kernel/locking/spinlock.c:_raw_spin_lock_bh
```
```
In kernel/irq/manage.c (ffffffff81102a95)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_forced_thread_fn
```
```
In kernel/rcu/update.c (ffffffff8110e1a2)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/srcutree.c (ffffffff8110f458)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
```
```
In kernel/time/hrtimer.c (ffffffff811222cb)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
```
```
In kernel/stop_machine.c (ffffffff8115b65a)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
```
```
In kernel/bpf/cpumap.c (ffffffff811de418)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In kernel/padata.c (ffffffff811f8402)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:invoke_padata_reorder
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_parallel_worker
```
```
In security/smack/smack_lsm.c (ffffffff8143561f)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_netlabel
```
```
In drivers/net/tun.c (ffffffff81763571)
Location: arch/x86/include/asm/preempt.h:77
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
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In net/core/gen_estimator.c (ffffffff818a6cbc)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/dev.c (ffffffff818b0d54)
Location: arch/x86/include/asm/preempt.h:77
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
Location: arch/x86/include/asm/preempt.h:77
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
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
```
```
In net/netlink/af_netlink.c (ffffffff81908b62)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_create
```
```
In net/netfilter/nf_log.c (ffffffff8190d6cc)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/netfilter/nf_log.c:nf_log_buf_open
```
```
In net/netfilter/nf_queue.c (ffffffff8190e367)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_reinject
```
```
In net/ipv4/route.c (ffffffff8191059f)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81919bf3)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_hashtables.c (ffffffff8191f8d5)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff819212b2)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81922a11)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/tcp.c (ffffffff8192927e)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff81933749)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8193e01c)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81940fdd)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/icmp.c (ffffffff81952fba)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/fib_frontend.c (ffffffff81960892)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
```
```
In net/ipv4/fib_semantics.c (ffffffff81964d7f)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/unix/af_unix.c (ffffffff8198e849)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/ipv6/ip6_output.c (ffffffff81996d19)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/addrconf.c (ffffffff8199d1a5)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff819ac13c)
Location: arch/x86/include/asm/preempt.h:77
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
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_start
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff819b50d2)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff819c0dec)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff819d012f)
Location: arch/x86/include/asm/preempt.h:77
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
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
```
```
In net/ipv6/inet6_hashtables.c (ffffffff819e2e34)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In net/xdp/xsk.c (ffffffff81a05128)
Location: arch/x86/include/asm/preempt.h:77
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
In arch/x86/kernel/nmi.c (ffffffff81035cc6)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103e433)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:fpu__save
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103f447)
Location: arch/x86/include/asm/preempt.h:77
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
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/mm/pkeys.c (ffffffff8108dbe8)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:copy_init_pkru_to_fpregs
```
```
In kernel/softirq.c (ffffffff810a1a8b)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/softirq.c:irq_enter
  - kernel/softirq.c:irq_enter
  - kernel/softirq.c:__do_softirq
```
```
In kernel/locking/spinlock.c (ffffffff81a9d455)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_lock_bh
  - kernel/locking/spinlock.c:_raw_read_lock_bh
  - kernel/locking/spinlock.c:_raw_spin_trylock_bh
  - kernel/locking/spinlock.c:_raw_spin_lock_bh
```
```
In kernel/irq/manage.c (ffffffff8110b455)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_forced_thread_fn
```
```
In kernel/rcu/update.c (ffffffff811178bb)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/srcutree.c (ffffffff811191ae)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
```
```
In kernel/rcu/tree.c (ffffffff8111cabf)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_cpu_kthread
```
```
In kernel/time/hrtimer.c (ffffffff8112cbfb)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
```
```
In kernel/stop_machine.c (ffffffff81167da8)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
```
```
In kernel/bpf/cpumap.c (ffffffff811f3caf)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In kernel/bpf/offload.c (ffffffff811f4e37)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In kernel/padata.c (ffffffff81210922)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:invoke_padata_reorder
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_parallel_worker
```
```
In ipc/util.c (ffffffff8141cf6e)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/smack/smack_lsm.c (ffffffff8146308f)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_netlabel
```
```
In security/apparmor/policy_unpack.c (ffffffff81488d90)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In lib/rhashtable.c (ffffffff8150d5fb)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In drivers/net/tun.c (ffffffff817a12ac)
Location: arch/x86/include/asm/preempt.h:77
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
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In net/core/skbuff.c (ffffffff818e8c16)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:netdev_alloc_frag
```
```
In net/core/gen_estimator.c (ffffffff818f214c)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/dev.c (ffffffff818fdaed)
Location: arch/x86/include/asm/preempt.h:77
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
Location: arch/x86/include/asm/preempt.h:77
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
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff8195826a)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
```
```
In net/sched/cls_api.c (ffffffff819629c1)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tc_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffff81969f77)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/netfilter/nf_log.c (ffffffff8196f2fc)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/netfilter/nf_log.c:nf_log_buf_open
```
```
In net/netfilter/nf_queue.c (ffffffff8196fe4c)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_reinject
```
```
In net/ipv4/route.c (ffffffff81973003)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff8197bcef)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_hashtables.c (ffffffff819821f5)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81983c67)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8198541d)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/tcp.c (ffffffff8198c1a8)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff81997953)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a243f)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819a55db)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/icmp.c (ffffffff819b7aec)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/fib_frontend.c (ffffffff819c4e35)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff819caad6)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/inet_fragment.c (ffffffff819cfa95)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/nexthop.c (ffffffff819d4c79)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff819db92c)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff819e98ed)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/unix/af_unix.c (ffffffff819f9fab)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/ipv6/ip6_output.c (ffffffff81a00b19)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/addrconf.c (ffffffff81a09375)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff81a19c83)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ip6_fib.c (ffffffff81a1ddea)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_start
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81a235d6)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff81a2fb27)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81a3ee4f)
Location: arch/x86/include/asm/preempt.h:77
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
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a4f5cb)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a51bb6)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In net/xdp/xsk.c (ffffffff81a746f2)
Location: arch/x86/include/asm/preempt.h:77
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
In arch/x86/kernel/nmi.c (ffffffff810364dd)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103ebf3)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:fpu__save
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103faed)
Location: arch/x86/include/asm/preempt.h:77
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
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/mm/pkeys.c (ffffffff8108e848)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:copy_init_pkru_to_fpregs
```
```
In kernel/softirq.c (ffffffff810a804b)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/softirq.c:irq_enter
  - kernel/softirq.c:irq_enter
  - kernel/softirq.c:__do_softirq
```
```
In kernel/locking/spinlock.c (ffffffff81ad4c35)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_lock_bh
  - kernel/locking/spinlock.c:_raw_read_lock_bh
  - kernel/locking/spinlock.c:_raw_spin_trylock_bh
  - kernel/locking/spinlock.c:_raw_spin_lock_bh
```
```
In kernel/irq/manage.c (ffffffff81117755)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_forced_thread_fn
```
```
In kernel/rcu/update.c (ffffffff81123c8f)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/srcutree.c (ffffffff8112557e)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
```
```
In kernel/rcu/tree.c (ffffffff8112904f)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_cpu_kthread
```
```
In kernel/time/hrtimer.c (ffffffff81138bdb)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
```
```
In kernel/stop_machine.c (ffffffff81173c68)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
```
```
In kernel/bpf/cpumap.c (ffffffff81200a4f)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In kernel/bpf/offload.c (ffffffff81201e47)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In kernel/padata.c (ffffffff8121d4d2)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:invoke_padata_reorder
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_parallel_worker
```
```
In ipc/util.c (ffffffff81436dbe)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/smack/smack_lsm.c (ffffffff8147ce5f)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_netlabel
```
```
In security/apparmor/policy_unpack.c (ffffffff814a2c40)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In lib/rhashtable.c (ffffffff8152b44b)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In drivers/net/tun.c (ffffffff817c626c)
Location: arch/x86/include/asm/preempt.h:77
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
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In net/core/skbuff.c (ffffffff8191ad76)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:netdev_alloc_frag
```
```
In net/core/gen_estimator.c (ffffffff8192409c)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/dev.c (ffffffff81935873)
Location: arch/x86/include/asm/preempt.h:77
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
Location: arch/x86/include/asm/preempt.h:77
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
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff81963eb9)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/sched/sch_generic.c (ffffffff8198e71a)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
```
```
In net/netlink/af_netlink.c (ffffffff819a09e7)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/netfilter/nf_log.c (ffffffff819a5d2c)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/netfilter/nf_log.c:nf_log_buf_open
```
```
In net/netfilter/nf_queue.c (ffffffff819a684c)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_reinject
```
```
In net/ipv4/route.c (ffffffff819a9976)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff819b268f)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_hashtables.c (ffffffff819b8a55)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff819ba447)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819bbc32)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/tcp.c (ffffffff819c2af8)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff819ce4e3)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819d900f)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819dc2ca)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/icmp.c (ffffffff819ee7ec)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/fib_frontend.c (ffffffff819fb9d5)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff81a016c6)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/inet_fragment.c (ffffffff81a06625)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/nexthop.c (ffffffff81a0b7d9)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81a1285c)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a21602)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/unix/af_unix.c (ffffffff81a30c2b)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/ipv6/ip6_output.c (ffffffff81a376e9)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/addrconf.c (ffffffff81a40065)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff81a508f3)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ip6_fib.c (ffffffff81a54a3a)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_start
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81a5a3ab)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff81a66677)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81a75abf)
Location: arch/x86/include/asm/preempt.h:77
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
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a8625b)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a887b6)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In net/xdp/xsk.c (ffffffff81aab0a1)
Location: arch/x86/include/asm/preempt.h:77
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
In arch/x86/kernel/traps.c (ffffffff81bbd71b)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:exc_debug
  - arch/x86/kernel/traps.c:exc_int3
  - arch/x86/kernel/traps.c:exc_double_fault
```
```
In arch/x86/kernel/irq.c (ffffffff81bbdc68)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_ipi
```
```
In arch/x86/kernel/nmi.c (ffffffff81bbdea5)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:exc_nmi
```
```
In arch/x86/kernel/fpu/core.c (ffffffff810419a6)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:fpu__save
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81042e3c)
Location: arch/x86/include/asm/preempt.h:77
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
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81bbea3d)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:exc_machine_check
```
```
In arch/x86/kernel/smp.c (ffffffff81bbef9b)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:sysvec_reschedule_ipi
```
```
In arch/x86/mm/pkeys.c (ffffffff810949cb)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:copy_init_pkru_to_fpregs
```
```
In kernel/softirq.c (ffffffff810af85b)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/softirq.c:irq_enter
  - kernel/softirq.c:irq_enter
  - kernel/softirq.c:__do_softirq
```
```
In kernel/locking/spinlock.c (ffffffff81bccbc5)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_lock_bh
  - kernel/locking/spinlock.c:_raw_read_lock_bh
  - kernel/locking/spinlock.c:_raw_spin_trylock_bh
  - kernel/locking/spinlock.c:_raw_spin_lock_bh
```
```
In kernel/irq/manage.c (ffffffff811233c5)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_forced_thread_fn
```
```
In kernel/rcu/update.c (ffffffff811304ea)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/srcutree.c (ffffffff81133124)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
```
```
In kernel/rcu/tree.c (ffffffff81136f0b)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_cpu_kthread
```
```
In kernel/time/hrtimer.c (ffffffff81147abb)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
```
```
In kernel/stop_machine.c (ffffffff81185af4)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
```
```
In kernel/bpf/cpumap.c (ffffffff812284fd)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In kernel/bpf/offload.c (ffffffff8122925b)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In kernel/padata.c (ffffffff812497c2)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:invoke_padata_reorder
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_parallel_worker
```
```
In ipc/util.c (ffffffff814868c8)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - ipc/util.c:__rhashtable_remove_fast_one
```
```
In security/smack/smack_lsm.c (ffffffff814d28ff)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_netlabel
```
```
In security/apparmor/policy_unpack.c (ffffffff814fcf27)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In lib/rhashtable.c (ffffffff8158e9d7)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_chain
```
```
In drivers/net/tun.c (ffffffff8188e3b9)
Location: arch/x86/include/asm/preempt.h:77
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
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
```
```
In net/core/skbuff.c (ffffffff819ed356)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:netdev_alloc_frag
```
```
In net/core/gen_estimator.c (ffffffff819f7c4c)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/dev.c (ffffffff81a0a558)
Location: arch/x86/include/asm/preempt.h:77
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
Location: arch/x86/include/asm/preempt.h:77
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
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/core/xdp.c:__rhashtable_remove_fast_one
```
```
In net/sched/sch_generic.c (ffffffff81a664ce)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
```
```
In net/netlink/af_netlink.c (ffffffff81a7a15f)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
```
```
In net/netfilter/nf_log.c (ffffffff81a8f0cc)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/netfilter/nf_log.c:nf_log_buf_open
```
```
In net/netfilter/nf_queue.c (ffffffff81a8fb7b)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_reinject
```
```
In net/ipv4/route.c (ffffffff81a92da9)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81a9bd88)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_hashtables.c (ffffffff81aa3765)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81aa4f42)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81aa644a)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/tcp.c (ffffffff81aae0d1)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff81aba5cc)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac5b4a)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ac942a)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/icmp.c (ffffffff81adc568)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/fib_frontend.c (ffffffff81aeaa39)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_lookup
```
```
In net/ipv4/fib_semantics.c (ffffffff81af06cd)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/inet_fragment.c (ffffffff81af5e88)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/nexthop.c (ffffffff81afc24f)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81b01cc0)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:__rhashtable_remove_fast_one
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b108de)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In net/xfrm/espintcp.c (ffffffff81b227e5)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:handle_esp
```
```
In net/unix/af_unix.c (ffffffff81b24ec0)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/ipv6/ip6_output.c (ffffffff81b2d224)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/addrconf.c (ffffffff81b3b3e0)
Location: arch/x86/include/asm/preempt.h:77
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
Location: arch/x86/include/asm/preempt.h:77
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
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_start
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81b5264d)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff81b5f026)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81b70145)
Location: arch/x86/include/asm/preempt.h:77
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
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b80c5f)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
  - net/ipv6/seg6_hmac.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81b83cc6)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In net/xdp/xsk.c (ffffffff81ba7041)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
  - net/xdp/xsk.c:xsk_release
```
```
In net/mptcp/protocol.c (ffffffff81bac7b9)
Location: arch/x86/include/asm/preempt.h:77
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
In arch/x86/kernel/irq.c (ffffffff81c363ba)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_ipi
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81041954)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:fpu__save
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81042d7a)
Location: arch/x86/include/asm/preempt.h:77
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
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/kernel/smp.c (ffffffff81c3779a)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:sysvec_reschedule_ipi
```
```
In arch/x86/mm/pkeys.c (ffffffff81093dbb)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:copy_init_pkru_to_fpregs
```
```
In kernel/softirq.c (ffffffff810aafce)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/softirq.c:irq_enter
  - kernel/softirq.c:__do_softirq
```
```
In kernel/locking/spinlock.c (ffffffff81c45785)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_lock_bh
  - kernel/locking/spinlock.c:_raw_read_lock_bh
  - kernel/locking/spinlock.c:_raw_spin_trylock_bh
  - kernel/locking/spinlock.c:_raw_spin_lock_bh
```
```
In kernel/irq/manage.c (ffffffff8111f205)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_forced_thread_fn
```
```
In kernel/rcu/update.c (ffffffff8112c398)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/srcutree.c (ffffffff8112e904)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
```
```
In kernel/rcu/tree.c (ffffffff81132549)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_cpu_kthread
```
```
In kernel/entry/common.c (ffffffff81c3888c)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/entry/common.c:irqentry_nmi_enter
```
```
In kernel/time/hrtimer.c (ffffffff81143f4b)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
```
```
In kernel/stop_machine.c (ffffffff81182c23)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
```
```
In kernel/bpf/cpumap.c (ffffffff8122f2ba)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
```
```
In kernel/bpf/offload.c (ffffffff81230deb)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In kernel/padata.c (ffffffff81254652)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:invoke_padata_reorder
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_parallel_worker
```
```
In ipc/util.c (ffffffff814a3f78)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - ipc/util.c:__rhashtable_remove_fast_one
```
```
In security/smack/smack_lsm.c (ffffffff814f39bc)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smk_ipv4_check
  - security/smack/smack_lsm.c:smack_netlbl_add
```
```
In security/apparmor/policy_unpack.c (ffffffff8151a137)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In lib/rhashtable.c (ffffffff815ab537)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_chain
```
```
In drivers/net/tun.c (ffffffff8189c921)
Location: arch/x86/include/asm/preempt.h:77
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
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
```
```
In net/core/skbuff.c (ffffffff819ed01b)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:netdev_alloc_frag
```
```
In net/core/gen_estimator.c (ffffffff819f76be)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/dev.c (ffffffff81a0d8ee)
Location: arch/x86/include/asm/preempt.h:77
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
Location: arch/x86/include/asm/preempt.h:77
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
Location: arch/x86/include/asm/preempt.h:77
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
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_fdb_dump
```
```
In net/core/filter.c (ffffffff81a2e934)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In net/core/xdp.c (ffffffff81a38368)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/core/xdp.c:__rhashtable_remove_fast_one
```
```
In net/core/net-procfs.c (ffffffff81a3de97)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff81a5265e)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In net/core/sock_map.c (ffffffff81a55929)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_update_elem
```
```
In net/sched/sch_generic.c (ffffffff81a6e5ae)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
```
```
In net/netlink/af_netlink.c (ffffffff81a82fbf)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
```
```
In net/netfilter/nf_log.c (ffffffff81a9913c)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/netfilter/nf_log.c:nf_log_buf_open
```
```
In net/netfilter/nf_queue.c (ffffffff81a99b6a)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_reinject
```
```
In net/ipv4/route.c (ffffffff81a9cc5a)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81aa5be8)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_hashtables.c (ffffffff81aadda5)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81aaf5ad)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ab0a9a)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/tcp.c (ffffffff81ab8354)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff81ac5a0c)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad17ba)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ad537a)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/icmp.c (ffffffff81ae928b)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/fib_frontend.c (ffffffff81af78d9)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_lookup
```
```
In net/ipv4/fib_semantics.c (ffffffff81afd6bd)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/inet_fragment.c (ffffffff81b02cf8)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/nexthop.c (ffffffff81b09a8f)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81b0fda0)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:__rhashtable_remove_fast_one
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b1ebce)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In net/xfrm/espintcp.c (ffffffff81b31493)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:handle_esp
```
```
In net/unix/af_unix.c (ffffffff81b339f7)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/ipv6/ip6_output.c (ffffffff81b3bc34)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/addrconf.c (ffffffff81b4a0f0)
Location: arch/x86/include/asm/preempt.h:77
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
Location: arch/x86/include/asm/preempt.h:77
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
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_start
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81b6176f)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff81b6d7b6)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81b7ec75)
Location: arch/x86/include/asm/preempt.h:77
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
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b904cf)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
  - net/ipv6/seg6_hmac.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81b93376)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In net/xdp/xsk.c (ffffffff81bb6380)
Location: arch/x86/include/asm/preempt.h:77
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
In arch/x86/kernel/irq.c (ffffffff81c287ba)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_ipi
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81043351)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:fpu__save
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81044733)
Location: arch/x86/include/asm/preempt.h:78
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
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/kernel/smp.c (ffffffff81c29e6a)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:sysvec_reschedule_ipi
```
```
In arch/x86/mm/pkeys.c (ffffffff8109477b)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:copy_init_pkru_to_fpregs
```
```
In kernel/softirq.c (ffffffff810ac1be)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/softirq.c:irq_enter
  - kernel/softirq.c:__do_softirq
```
```
In kernel/locking/spinlock.c (ffffffff81c389f5)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_lock_bh
  - kernel/locking/spinlock.c:_raw_read_lock_bh
  - kernel/locking/spinlock.c:_raw_spin_trylock_bh
  - kernel/locking/spinlock.c:_raw_spin_lock_bh
```
```
In kernel/irq/manage.c (ffffffff8111f725)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_forced_thread_fn
```
```
In kernel/rcu/update.c (ffffffff8112c8c8)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/srcutree.c (ffffffff8112eb8c)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
```
```
In kernel/rcu/tree.c (ffffffff81133869)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_do_batch
```
```
In kernel/entry/common.c (ffffffff81c2ac8c)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/entry/common.c:irqentry_nmi_enter
```
```
In kernel/time/hrtimer.c (ffffffff811450db)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
```
```
In kernel/stop_machine.c (ffffffff81183d73)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
```
```
In kernel/bpf/cpumap.c (ffffffff812341dc)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
```
```
In kernel/bpf/offload.c (ffffffff81234f8e)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In kernel/padata.c (ffffffff81258bf2)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:invoke_padata_reorder
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_parallel_worker
```
```
In ipc/util.c (ffffffff814a9eac)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - ipc/util.c:__rhashtable_remove_fast_one
```
```
In security/smack/smack_lsm.c (ffffffff814fa97c)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smk_ipv4_check
  - security/smack/smack_lsm.c:smack_netlbl_add
```
```
In security/apparmor/policy_unpack.c (ffffffff81520a46)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In lib/rhashtable.c (ffffffff815b6399)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In drivers/net/tun.c (ffffffff8187ee91)
Location: arch/x86/include/asm/preempt.h:78
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
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
```
```
In net/core/skbuff.c (ffffffff819d34ec)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_frag_align
```
```
In net/core/gen_estimator.c (ffffffff819dd83e)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/dev.c (ffffffff819f458b)
Location: arch/x86/include/asm/preempt.h:78
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
Location: arch/x86/include/asm/preempt.h:78
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
Location: arch/x86/include/asm/preempt.h:78
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
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_fdb_dump
```
```
In net/core/filter.c (ffffffff81a15f86)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In net/core/xdp.c (ffffffff81a1f1ac)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/core/xdp.c:__rhashtable_remove_fast_one
```
```
In net/core/net-procfs.c (ffffffff81a24f67)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff81a37d43)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In net/core/sock_map.c (ffffffff81a513a7)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_update_elem
```
```
In net/sched/sch_generic.c (ffffffff81a56e3e)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
```
```
In net/netlink/af_netlink.c (ffffffff81a6c08f)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
```
```
In net/netfilter/nf_log.c (ffffffff81a8446c)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/netfilter/nf_log.c:nf_log_buf_open
```
```
In net/netfilter/nf_queue.c (ffffffff81a84e7a)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_reinject
```
```
In net/ipv4/route.c (ffffffff81a87d1f)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81a90bb8)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_hashtables.c (ffffffff81a98f45)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81a9a8b5)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81a9bb4a)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/tcp.c (ffffffff81aa364e)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff81ab0c18)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abc7db)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ac03f7)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/icmp.c (ffffffff81ad48ad)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_reply
```
```
In net/ipv4/fib_frontend.c (ffffffff81ae2ff9)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_lookup
```
```
In net/ipv4/fib_semantics.c (ffffffff81ae8efc)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/inet_fragment.c (ffffffff81aee5fc)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/nexthop.c (ffffffff81af48d1)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_select_path_hthr
  - net/ipv4/nexthop.c:nexthop_select_path_hthr
```
```
In net/ipv4/ipmr.c (ffffffff81afd992)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:__rhashtable_remove_fast_one
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0c859)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In net/xfrm/espintcp.c (ffffffff81b1f29f)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_rcv
```
```
In net/unix/af_unix.c (ffffffff81b213fb)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/ipv6/ip6_output.c (ffffffff81b29597)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/addrconf.c (ffffffff81b37305)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff81b444c8)
Location: arch/x86/include/asm/preempt.h:78
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
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_start
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81b4fa3a)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff81b5bb4e)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81b6d875)
Location: arch/x86/include/asm/preempt.h:78
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
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b7f70f)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
  - net/ipv6/seg6_hmac.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81b824a6)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In net/xdp/xsk.c (ffffffff81ba66ec)
Location: arch/x86/include/asm/preempt.h:78
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
In arch/x86/kernel/irq.c (ffffffff81d4692a)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_ipi
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81049aa5)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu_flush_thread
  - arch/x86/kernel/fpu/core.c:fpu__clear_user_states
  - arch/x86/kernel/fpu/core.c:fpu_clone
  - arch/x86/kernel/fpu/core.c:fpu_sync_fpstate
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8104a926)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In arch/x86/kernel/smp.c (ffffffff81d483da)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:sysvec_reschedule_ipi
```
```
In kernel/softirq.c (ffffffff810bd83e)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/softirq.c:irq_enter
  - kernel/softirq.c:__do_softirq
```
```
In kernel/locking/spinlock.c (ffffffff81d572d5)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_lock_bh
  - kernel/locking/spinlock.c:_raw_read_lock_bh
  - kernel/locking/spinlock.c:_raw_spin_trylock_bh
  - kernel/locking/spinlock.c:_raw_spin_lock_bh
```
```
In kernel/irq/manage.c (ffffffff8113fbb5)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_forced_thread_fn
```
```
In kernel/rcu/update.c (ffffffff8114d5e0)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/srcutree.c (ffffffff8115007a)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
```
```
In kernel/rcu/tree.c (ffffffff81155c59)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_do_batch
```
```
In kernel/entry/common.c (ffffffff81d49223)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/entry/common.c:irqentry_nmi_enter
```
```
In kernel/time/hrtimer.c (ffffffff8116896b)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
```
```
In kernel/stop_machine.c (ffffffff811abf00)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
```
```
In kernel/bpf/cpumap.c (ffffffff8126defa)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In kernel/bpf/offload.c (ffffffff8126f0be)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In kernel/padata.c (ffffffff81294812)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:invoke_padata_reorder
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_parallel_worker
```
```
In ipc/util.c (ffffffff8150235c)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - ipc/util.c:__rhashtable_remove_fast_one
```
```
In security/smack/smack_lsm.c (ffffffff815555ec)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smk_ipv4_check
  - security/smack/smack_lsm.c:smack_netlbl_add
```
```
In security/apparmor/policy_unpack.c (ffffffff8157ebe6)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In lib/rhashtable.c (ffffffff8161c8c9)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In drivers/net/tun.c (ffffffff8191069b)
Location: arch/x86/include/asm/preempt.h:78
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
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
```
```
In drivers/net/xen-netfront.c (ffffffff8191f33b)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:netfront_resume
```
```
In net/core/skbuff.c (ffffffff81a8322f)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_frag_align
```
```
In net/core/gen_estimator.c (ffffffff81a8db1e)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/dev.c (ffffffff81aa5eab)
Location: arch/x86/include/asm/preempt.h:78
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
Location: arch/x86/include/asm/preempt.h:78
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
Location: arch/x86/include/asm/preempt.h:78
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
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_fdb_dump
```
```
In net/core/filter.c (ffffffff81ac75ed)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/core/filter.c:bpf_out_neigh_v6
```
```
In net/core/xdp.c (ffffffff81ad343c)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/core/xdp.c:__rhashtable_remove_fast_one
```
```
In net/core/net-procfs.c (ffffffff81ad9a9c)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In net/core/lwt_bpf.c (ffffffff81aedb53)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In net/core/sock_map.c (ffffffff81b0a13d)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_update_elem
```
```
In net/sched/sch_generic.c (ffffffff81b0fc6e)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
```
```
In net/netlink/af_netlink.c (ffffffff81b256ac)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
```
```
In net/netfilter/nf_log.c (ffffffff81b3e72c)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/netfilter/nf_log.c:nf_log_buf_open
```
```
In net/netfilter/nf_queue.c (ffffffff81b3f515)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_reinject
```
```
In net/ipv4/route.c (ffffffff81b42250)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81b4c00f)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_hashtables.c (ffffffff81b543c5)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81b55d25)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81b5721a)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/tcp.c (ffffffff81b5f7ee)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff81b6da5c)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b7a424)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81b7f388)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/icmp.c (ffffffff81b935dc)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_reply
```
```
In net/ipv4/fib_frontend.c (ffffffff81ba2629)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_lookup
```
```
In net/ipv4/fib_semantics.c (ffffffff81ba8f1c)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/inet_fragment.c (ffffffff81bae9ac)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/nexthop.c (ffffffff81bb515e)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_select_path_hthr
  - net/ipv4/nexthop.c:nexthop_select_path_hthr
```
```
In net/ipv4/ipmr.c (ffffffff81bbfa92)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:__rhashtable_remove_fast_one
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bcfa49)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In net/xfrm/espintcp.c (ffffffff81be3e8b)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_rcv
```
```
In net/unix/af_unix.c (ffffffff81be6534)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/ipv6/ip6_output.c (ffffffff81beefc8)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/addrconf.c (ffffffff81bfdabc)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff81c0b463)
Location: arch/x86/include/asm/preempt.h:78
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
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_start
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81c16d99)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff81c23285)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81c356ff)
Location: arch/x86/include/asm/preempt.h:78
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
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
  - net/ipv6/ioam6.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/ip6mr.c (ffffffff81c3d182)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/seg6_hmac.c (ffffffff81c4afaf)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
  - net/ipv6/seg6_hmac.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81c4e556)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In net/xdp/xsk.c (ffffffff81c7423c)
Location: arch/x86/include/asm/preempt.h:78
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
In init/main.c (ffffffff81001664)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - init/main.c:do_one_initcall
  - init/main.c:do_one_initcall
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81004b53)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
```
```
In arch/x86/events/amd/ibs.c (ffffffff8100c1c3)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
```
```
In arch/x86/events/intel/ds.c (ffffffff810137ae)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:ds_clear_cea
  - arch/x86/events/intel/ds.c:ds_update_cea
```
```
In arch/x86/events/intel/p4.c (ffffffff8101a835)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_hw_config
```
```
In arch/x86/xen/time.c (ffffffff8102be4e)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_restore_time_memory_area
  - arch/x86/xen/time.c:xen_save_time_memory_area
  - arch/x86/xen/time.c:xen_vcpuop_set_next_event
  - arch/x86/xen/time.c:xen_timerop_set_next_event
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
  - arch/x86/xen/time.c:xen_get_wallclock
  - arch/x86/xen/time.c:xen_sched_clock
  - arch/x86/xen/time.c:xen_clocksource_get_cycles
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff81030ef2)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_cr0
  - arch/x86/xen/enlighten_pv.c:xen_load_sp0
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry
  - arch/x86/xen/enlighten_pv.c:xen_load_idt
  - arch/x86/xen/enlighten_pv.c:xen_write_idt_entry
  - arch/x86/xen/enlighten_pv.c:xen_write_idt_entry
  - arch/x86/xen/enlighten_pv.c:xen_write_ldt_entry
  - arch/x86/xen/enlighten_pv.c:xen_write_ldt_entry
  - arch/x86/xen/enlighten_pv.c:load_TLS_descriptor
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
  - arch/x86/xen/enlighten_pv.c:xen_mc_batch
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81032575)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_all
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_all
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_leave_lazy_mmu
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:__xen_write_cr3
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
  - arch/x86/xen/mmu_pv.c:xen_set_p4d_hyper
  - arch/x86/xen/mmu_pv.c:xen_set_pud
  - arch/x86/xen/mmu_pv.c:xen_set_pud_hyper
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_start
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pmd
  - arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper
  - arch/x86/xen/mmu_pv.c:xen_extend_mmuext_op
  - arch/x86/xen/mmu_pv.c:xen_extend_mmu_update
  - arch/x86/xen/mmu_pv.c:xen_mc_batch
```
```
In arch/x86/xen/multicalls.c (ffffffff81035f6f)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/xen/multicalls.c:xen_mc_callback
  - arch/x86/xen/multicalls.c:xen_mc_callback
  - arch/x86/xen/multicalls.c:xen_mc_extend_args
  - arch/x86/xen/multicalls.c:xen_mc_extend_args
  - arch/x86/xen/multicalls.c:xen_mc_extend_args
  - arch/x86/xen/multicalls.c:__xen_mc_entry
  - arch/x86/xen/multicalls.c:__xen_mc_entry
  - arch/x86/xen/multicalls.c:xen_mc_flush
```
```
In arch/x86/hyperv/hv_init.c (ffffffff8103c499)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:set_hv_tscchange_cb
```
```
In arch/x86/hyperv/mmu.c (ffffffff8103df3e)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
```
```
In arch/x86/hyperv/nested.c (ffffffff8103e400)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8104004a)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_one
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
```
```
In arch/x86/kernel/process_64.c (ffffffff810416e4)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/signal.c (ffffffff810420f9)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:handle_signal
```
```
In arch/x86/kernel/irq.c (ffffffff81045556)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:__sysvec_thermal
  - arch/x86/kernel/irq.c:__sysvec_thermal
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:__sysvec_x86_platform_ipi
  - arch/x86/kernel/irq.c:__sysvec_x86_platform_ipi
```
```
In arch/x86/kernel/ioport.c (ffffffff81046bbe)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In arch/x86/kernel/nmi.c (ffffffff81047a11)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:nmi_handle
```
```
In arch/x86/kernel/irq_work.c (ffffffff8104963c)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:__sysvec_irq_work
  - arch/x86/kernel/irq_work.c:__sysvec_irq_work
```
```
In arch/x86/kernel/tsc.c (ffffffff8104fcf1)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:native_sched_clock_from_tsc
  - arch/x86/kernel/tsc.c:native_sched_clock
  - arch/x86/kernel/tsc.c:__set_cyc2ns_scale
```
```
In arch/x86/kernel/process.c (ffffffff810520da)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:do_arch_prctl_common
  - arch/x86/kernel/process.c:speculation_ctrl_update_current
  - arch/x86/kernel/process.c:enable_cpuid
  - arch/x86/kernel/process.c:set_tsc_mode
  - arch/x86/kernel/process.c:disable_TSC
```
```
In arch/x86/kernel/fpu/core.c (ffffffff810539f2)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpregs_mark_activate
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
  - arch/x86/kernel/fpu/core.c:fpu_flush_thread
  - arch/x86/kernel/fpu/core.c:fpu__clear_user_states
  - arch/x86/kernel/fpu/core.c:fpu__drop
  - arch/x86/kernel/fpu/core.c:fpu__drop
  - arch/x86/kernel/fpu/core.c:fpu__drop
  - arch/x86/kernel/fpu/core.c:fpu_clone
  - arch/x86/kernel/fpu/core.c:fpu_clone
  - arch/x86/kernel/fpu/core.c:fpu_clone
  - arch/x86/kernel/fpu/core.c:fpu_sync_fpstate
  - arch/x86/kernel/fpu/core.c:fpu_sync_fpstate
  - arch/x86/kernel/fpu/core.c:fpu_sync_fpstate
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin_mask
  - arch/x86/kernel/fpu/core.c:fpu_swap_kvm_fpstate
  - arch/x86/kernel/fpu/core.c:fpu_update_guest_xfd
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81054de6)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
  - arch/x86/kernel/fpu/signal.c:fpregs_restore_userregs
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81055ea8)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpstate_realloc
  - arch/x86/kernel/fpu/xstate.c:fpregs_restore_userregs
```
```
In arch/x86/kernel/tls.c (ffffffff81059297)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:set_tls_desc
```
```
In arch/x86/kernel/cpu/aperfmperf.c (0)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81062fa3)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:split_lock_warn
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81066fd5)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:wait_for_panic
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8106b0ad)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:__sysvec_deferred_error
  - arch/x86/kernel/cpu/mce/amd.c:__sysvec_deferred_error
```
```
In arch/x86/kernel/cpu/mce/threshold.c (ffffffff8106cc6d)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/threshold.c:__sysvec_threshold
  - arch/x86/kernel/cpu/mce/threshold.c:__sysvec_threshold
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff8106fdc5)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_get_mtrr
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81075566)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:update_closid_rmid
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff81079e08)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:add_rmid_to_limbo
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff8107a7e1)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:resctrl_arch_update_domains
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8107c827)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_l3_residency
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_l2_residency
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8107dd07)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff8107fa94)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_init
  - arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81080cd9)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_encl_ewb
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_encl_ewb
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff810823b1)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_virt_einit
```
```
In arch/x86/kernel/smp.c (ffffffff810855cc)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:__sysvec_call_function_single
  - arch/x86/kernel/smp.c:__sysvec_call_function_single
  - arch/x86/kernel/smp.c:__sysvec_call_function
  - arch/x86/kernel/smp.c:__sysvec_call_function
  - arch/x86/kernel/smp.c:sysvec_reschedule_ipi
  - arch/x86/kernel/smp.c:sysvec_reschedule_ipi
  - arch/x86/kernel/smp.c:sysvec_reschedule_ipi
```
```
In arch/x86/kernel/smpboot.c (ffffffff83465e58)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:smp_sanity_check
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81089d1f)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:__sysvec_error_interrupt
  - arch/x86/kernel/apic/apic.c:__sysvec_error_interrupt
  - arch/x86/kernel/apic/apic.c:handle_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:handle_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:__sysvec_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:__sysvec_apic_timer_interrupt
```
```
In arch/x86/kernel/apic/vector.c (ffffffff834693c9)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/vector.c:free_moved_vector
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_deactivate
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
  - arch/x86/kernel/apic/vector.c:assign_vector_locked
  - arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked
  - arch/x86/kernel/apic/vector.c:apic_update_vector
  - arch/x86/kernel/apic/vector.c:apic_update_irq_cfg
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff810927ee)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_one
```
```
In arch/x86/kernel/ftrace.c (ffffffff810950d1)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/ftrace.c:prepare_ftrace_return
```
```
In arch/x86/kernel/kprobes/opt.c (ffffffff8109a24f)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In arch/x86/kernel/kprobes/ftrace.c (ffffffff8109aa38)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
```
In arch/x86/kernel/kvmclock.c (ffffffff83470284)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/kernel/kvmclock.c:kvm_sched_clock_read
  - arch/x86/kernel/kvmclock.c:kvm_clock_get_cycles
  - arch/x86/kernel/kvmclock.c:kvm_get_wallclock
```
```
In arch/x86/kernel/paravirt.c (ffffffff810a0b65)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu
```
```
In arch/x86/mm/fault.c (ffffffff81f1834d)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:exc_page_fault
  - arch/x86/mm/fault.c:exc_page_fault
```
```
In arch/x86/mm/tlb.c (ffffffff810af445)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:arch_tlbbatch_flush
  - arch/x86/mm/tlb.c:flush_tlb_kernel_range
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
  - arch/x86/mm/tlb.c:native_flush_tlb_multi
  - arch/x86/mm/tlb.c:native_flush_tlb_multi
  - arch/x86/mm/tlb.c:flush_tlb_func
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/mm/kmmio.c (ffffffff810b7124)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:kmmio_handler
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810b7cc5)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:post
  - arch/x86/mm/mmio-mod.c:post
  - arch/x86/mm/mmio-mod.c:pre
  - arch/x86/mm/mmio-mod.c:pre
  - arch/x86/mm/mmio-mod.c:pre
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff810bd14e)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
```
```
In arch/x86/platform/uv/bios_uv.c (ffffffff810bf084)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/platform/uv/bios_uv.c:__uv_bios_call
```
```
In kernel/fork.c (ffffffff810cb792)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/fork.c:kernel_clone
  - kernel/fork.c:copy_process
```
```
In kernel/panic.c (ffffffff81e5357f)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/panic.c:__warn
  - kernel/panic.c:panic
```
```
In kernel/cpu.c (ffffffff810cf206)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
  - kernel/cpu.c:__cpuhp_state_add_instance
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:cpuhp_kick_ap_work
  - kernel/cpu.c:cpuhp_kick_ap_work
  - kernel/cpu.c:cpus_read_trylock
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
```
```
In kernel/exit.c (ffffffff810d2335)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:delayed_put_task_struct
```
```
In kernel/softirq.c (ffffffff810d4a40)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/softirq.c:__raise_softirq_irqoff
  - kernel/softirq.c:irq_enter
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
```
```
In kernel/signal.c (ffffffff810e4a92)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:exit_signals
  - kernel/signal.c:exit_signals
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:__send_signal_locked
```
```
In kernel/workqueue.c (ffffffff810ef76c)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_congested
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:pwq_activate_inactive_work
  - kernel/workqueue.c:wq_worker_running
```
```
In kernel/kthread.c (ffffffff810fabf1)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_stop
  - kernel/kthread.c:kthread_stop
  - kernel/kthread.c:kthread
  - kernel/kthread.c:__kthread_parkme
```
```
In kernel/smpboot.c (ffffffff81103cd6)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/smpboot.c:smpboot_thread_fn
```
```
In kernel/kmod.c (ffffffff81105c06)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
```
```
In kernel/sched/core.c (ffffffff8111ab57)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/sched/core.c:call_trace_sched_update_nr_running
  - kernel/sched/core.c:migrate_task_to
  - kernel/sched/core.c:__cond_resched
  - kernel/sched/core.c:do_sched_yield
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:preempt_schedule_irq
  - kernel/sched/core.c:preempt_schedule_notrace
  - kernel/sched/core.c:preempt_schedule
  - kernel/sched/core.c:schedule_preempt_disabled
  - kernel/sched/core.c:schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:sched_core_balance
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:send_call_function_single_ipi
  - kernel/sched/core.c:ttwu_do_wakeup
  - kernel/sched/core.c:kick_process
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:migrate_swap
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:migrate_enable
  - kernel/sched/core.c:migrate_disable
  - kernel/sched/core.c:wake_up_nohz_cpu
  - kernel/sched/core.c:resched_curr
  - kernel/sched/core.c:raw_spin_rq_trylock
```
```
In kernel/sched/fair.c (ffffffff81121623)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:update_group_capacity
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/build_policy.c (ffffffff8113b0c5)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:dl_cpu_busy
  - kernel/sched/build_policy.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/build_policy.c:sched_dl_do_global
  - kernel/sched/build_policy.c:sched_dl_global_validate
  - kernel/sched/build_policy.c:update_curr_dl
  - kernel/sched/build_policy.c:update_dl_rq_load_avg
  - kernel/sched/build_policy.c:update_rt_rq_load_avg
  - kernel/sched/build_policy.c:__update_load_avg_cfs_rq
  - kernel/sched/build_policy.c:__update_load_avg_se
  - kernel/sched/build_policy.c:__update_load_avg_blocked_se
  - kernel/sched/build_policy.c:update_curr_rt
  - kernel/sched/build_policy.c:play_idle_precise
  - kernel/sched/build_policy.c:default_idle_call
  - kernel/sched/build_policy.c:default_idle_call
```
```
In kernel/sched/build_utility.c (ffffffff81141979)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:membarrier_private_expedited
  - kernel/sched/build_utility.c:membarrier_global_expedited
  - kernel/sched/build_utility.c:__update_stats_enqueue_sleeper
  - kernel/sched/build_utility.c:__update_stats_enqueue_sleeper
  - kernel/sched/build_utility.c:__update_stats_enqueue_sleeper
  - kernel/sched/build_utility.c:__update_stats_wait_end
  - kernel/sched/build_utility.c:sched_clock_cpu
  - kernel/sched/build_utility.c:__sched_clock_work
```
```
In kernel/locking/mutex.c (ffffffff81f23771)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In kernel/locking/semaphore.c (ffffffff81f24e17)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/locking/semaphore.c:__down_common
  - kernel/locking/semaphore.c:__down_common
```
```
In kernel/locking/rwsem.c (ffffffff81f258f1)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
```
```
In kernel/locking/percpu-rwsem.c (ffffffff81f25ec4)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_down_write
  - kernel/locking/percpu-rwsem.c:percpu_down_write
  - kernel/locking/percpu-rwsem.c:__percpu_down_read
  - kernel/locking/percpu-rwsem.c:__percpu_down_read
  - kernel/locking/percpu-rwsem.c:__percpu_down_read
```
```
In kernel/locking/spinlock.c (ffffffff8114ed24)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:__raw_write_lock_irqsave
  - kernel/locking/spinlock.c:__raw_read_lock_irqsave
  - kernel/locking/spinlock.c:_raw_write_trylock
  - kernel/locking/spinlock.c:_raw_read_trylock
  - kernel/locking/spinlock.c:_raw_write_lock_irq
  - kernel/locking/spinlock.c:_raw_read_lock_irq
  - kernel/locking/spinlock.c:_raw_write_lock_bh
  - kernel/locking/spinlock.c:_raw_read_lock_bh
  - kernel/locking/spinlock.c:_raw_write_lock_nested
  - kernel/locking/spinlock.c:_raw_write_lock
  - kernel/locking/spinlock.c:_raw_read_lock
  - kernel/locking/spinlock.c:__raw_spin_lock_irqsave
  - kernel/locking/spinlock.c:_raw_spin_trylock_bh
  - kernel/locking/spinlock.c:_raw_spin_trylock
  - kernel/locking/spinlock.c:_raw_spin_lock_irq
  - kernel/locking/spinlock.c:_raw_spin_lock_bh
  - kernel/locking/spinlock.c:_raw_spin_lock
```
```
In kernel/locking/qspinlock.c (ffffffff8114f56a)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
```
```
In kernel/locking/rtmutex_api.c (ffffffff81f26042)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:mark_wakeup_next_waiter
```
```
In kernel/locking/qrwlock.c (ffffffff8114face)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/power/qos.c (ffffffff81150375)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/power/qos.c:cpu_latency_qos_remove_request
  - kernel/power/qos.c:pm_qos_update_flags
  - kernel/power/qos.c:pm_qos_update_target
```
```
In kernel/power/process.c (ffffffff81152312)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:thaw_processes
```
```
In kernel/power/suspend.c (ffffffff8115314e)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:s2idle_loop
  - kernel/power/suspend.c:s2idle_loop
```
```
In kernel/power/hibernate.c (ffffffff811540eb)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/power/hibernate.c:create_image
  - kernel/power/hibernate.c:create_image
```
```
In kernel/power/snapshot.c (0)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In kernel/printk/printk.c (ffffffff8347ee08)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_init
  - kernel/printk/printk.c:console_init
  - kernel/printk/printk.c:console_init
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:printk_sprint
```
```
In kernel/irq/handle.c (ffffffff811620ef)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/manage.c (ffffffff811628e5)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_forced_thread_fn
```
```
In kernel/irq/chip.c (ffffffff81167e15)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi
  - kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_fasteoi_nmi
  - kernel/irq/chip.c:handle_fasteoi_nmi
```
```
In kernel/irq/matrix.c (ffffffff811721ac)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_free
  - kernel/irq/matrix.c:irq_matrix_alloc
  - kernel/irq/matrix.c:irq_matrix_remove_reserved
  - kernel/irq/matrix.c:irq_matrix_reserve
  - kernel/irq/matrix.c:irq_matrix_assign
  - kernel/irq/matrix.c:irq_matrix_alloc_managed
  - kernel/irq/matrix.c:irq_matrix_remove_managed
  - kernel/irq/matrix.c:irq_matrix_reserve_managed
  - kernel/irq/matrix.c:irq_matrix_assign_system
  - kernel/irq/matrix.c:irq_matrix_offline
  - kernel/irq/matrix.c:irq_matrix_online
```
```
In kernel/rcu/update.c (ffffffff81175093)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/rcu/update.c:exit_tasks_rcu_finish
  - kernel/rcu/update.c:exit_tasks_rcu_start
  - kernel/rcu/update.c:rcu_tasks_invoke_cbs
```
```
In kernel/rcu/srcutree.c (ffffffff81177527)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
```
```
In kernel/rcu/tree.c (ffffffff8117e26c)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_note_context_switch
  - kernel/rcu/tree.c:rcu_note_context_switch
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:__sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:call_rcu
  - kernel/rcu/tree.c:call_rcu
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_do_batch
```
```
In kernel/livepatch/core.c (ffffffff8118246a)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_init_object
```
```
In kernel/livepatch/patch.c (ffffffff81182d7e)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_ftrace_handler
```
```
In kernel/livepatch/transition.c (ffffffff81184235)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_update_patch_state
```
```
In kernel/dma/swiotlb.c (ffffffff81189165)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_map
```
```
In kernel/entry/common.c (ffffffff8118a1ee)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/entry/common.c:syscall_exit_work
  - kernel/entry/common.c:irqentry_nmi_enter
```
```
In kernel/module/main.c (ffffffff81e61aa4)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/module/main.c:print_modules
  - kernel/module/main.c:is_module_text_address
  - kernel/module/main.c:is_module_address
  - kernel/module/main.c:search_module_extables
  - kernel/module/main.c:load_module
  - kernel/module/main.c:__symbol_get
  - kernel/module/main.c:free_module
  - kernel/module/main.c:module_put
  - kernel/module/main.c:module_put
  - kernel/module/main.c:try_module_get
  - kernel/module/main.c:try_module_get
  - kernel/module/main.c:symbol_put_addr
  - kernel/module/main.c:__symbol_put
  - kernel/module/main.c:__is_module_percpu_address
```
```
In kernel/module/kallsyms.c (ffffffff81191d62)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/module/kallsyms.c:module_kallsyms_on_each_symbol
  - kernel/module/kallsyms.c:module_kallsyms_lookup_name
  - kernel/module/kallsyms.c:module_get_kallsym
  - kernel/module/kallsyms.c:lookup_module_symbol_attrs
  - kernel/module/kallsyms.c:lookup_module_symbol_name
  - kernel/module/kallsyms.c:module_address_lookup
```
```
In kernel/module/version.c (ffffffff81192fc9)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/module/version.c:check_modstruct_version
```
```
In kernel/profile.c (ffffffff81193cc5)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/profile.c:write_profile
  - kernel/profile.c:read_profile
```
```
In kernel/time/timer.c (ffffffff8119a12b)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:__run_timers
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:detach_if_pending
  - kernel/time/timer.c:enqueue_timer
```
```
In kernel/time/hrtimer.c (ffffffff8119c4bb)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_nanosleep_restart
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_init
  - kernel/time/hrtimer.c:hrtimer_try_to_cancel
  - kernel/time/hrtimer.c:__hrtimer_start_range_ns
  - kernel/time/hrtimer.c:enqueue_hrtimer
  - kernel/time/hrtimer.c:clock_was_set
```
```
In kernel/time/timekeeping.c (0)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In kernel/time/clocksource.c (ffffffff811a1a33)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In kernel/time/alarmtimer.c (ffffffff811a3eb9)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_try_to_cancel
  - kernel/time/alarmtimer.c:alarm_start
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - kernel/time/alarmtimer.c:alarmtimer_fired
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811a8b95)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:check_cpu_itimer
```
```
In kernel/time/itimer.c (ffffffff811abdd2)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:it_real_fn
```
```
In kernel/time/tick-common.c (ffffffff811ae124)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_unfreeze
  - kernel/time/tick-common.c:tick_freeze
```
```
In kernel/time/tick-sched.c (ffffffff811b01c4)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_stop_tick
```
```
In kernel/smp.c (ffffffff811b7c73)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/smp.c:wake_up_all_idle_cpus
  - kernel/smp.c:kick_all_cpus_sync
  - kernel/smp.c:on_each_cpu_cond_mask
  - kernel/smp.c:smp_call_function_any
  - kernel/smp.c:smp_call_function_single_async
  - kernel/smp.c:smp_call_function_single
```
```
In kernel/acct.c (ffffffff811bb651)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
  - kernel/acct.c:do_acct_process
```
```
In kernel/cgroup/cgroup.c (ffffffff811ccf28)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_rmdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:cgroup_destroy_root
  - kernel/cgroup/cgroup.c:cgroup_update_populated
```
```
In kernel/cgroup/rstat.c (ffffffff811ce365)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:__cgroup_account_cputime_field
  - kernel/cgroup/rstat.c:__cgroup_account_cputime
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff811d0cde)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
```
In kernel/cgroup/freezer.c (ffffffff811d17ec)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_propagate_frozen
  - kernel/cgroup/freezer.c:cgroup_propagate_frozen
```
```
In kernel/cgroup/cpuset.c (ffffffff811d9345)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_read_unlock
  - kernel/cgroup/cpuset.c:cpuset_read_lock
```
```
In kernel/stop_machine.c (ffffffff811dd916)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
  - kernel/stop_machine.c:cpu_stop_queue_two_works
  - kernel/stop_machine.c:cpu_stop_queue_work
```
```
In kernel/kprobes.c (ffffffff811ef3df)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/kprobes.c:show_kprobe_addr
  - kernel/kprobes.c:check_kprobe_address_safe
  - kernel/kprobes.c:kprobe_busy_begin
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff811fcae9)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/hung_task.c (ffffffff811ff416)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/hung_task.c:check_hung_task
```
```
In kernel/relay.c (ffffffff81204b20)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/relay.c:relay_late_setup_files
```
```
In kernel/trace/trace_clock.c (ffffffff812087d0)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_local
```
```
In kernel/trace/ftrace.c (ffffffff81209d5a)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:fnpid_start
  - kernel/trace/ftrace.c:fpid_start
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:arch_ftrace_ops_list_func
  - kernel/trace/ftrace.c:ftrace_mod_get_kallsym
  - kernel/trace/ftrace.c:ftrace_mod_address_lookup
  - kernel/trace/ftrace.c:function_trace_probe_call
  - kernel/trace/ftrace.c:ftrace_ops_trampoline
```
```
In kernel/trace/ring_buffer.c (ffffffff81217d2b)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_consume
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_nest_start
  - kernel/trace/ring_buffer.c:ring_buffer_time_stamp
```
```
In kernel/trace/trace.c (ffffffff8121da40)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/trace/trace.c:saved_cmdlines_start
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_buffered_event_enable
  - kernel/trace/trace.c:trace_find_cmdline
  - kernel/trace/trace.c:ftrace_exports
```
```
In kernel/trace/trace_functions.c (ffffffff8122e0b3)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8122f7bc)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
  - kernel/trace/trace_sched_wakeup.c:func_prolog_preempt_disable
```
```
In kernel/trace/trace_stack.c (ffffffff81231430)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:stack_trace_call
```
```
In kernel/trace/trace_mmiotrace.c (ffffffff81232037)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
```
```
In kernel/trace/trace_functions_graph.c (ffffffff81232bb5)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/blktrace.c (ffffffff812368a6)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/blktrace.c:trace_note
```
```
In kernel/trace/trace_events.c (ffffffff8123a7ca)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:np_start
  - kernel/trace/trace_events.c:p_start
```
```
In kernel/trace/trace_event_perf.c (ffffffff8123ef39)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_ftrace_function_call
```
```
In kernel/trace/trace_events_inject.c (ffffffff8124789f)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/trace/trace_events_inject.c:event_inject_write
```
```
In kernel/trace/bpf_trace.c (ffffffff81259b30)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_put_raw_tracepoint
  - kernel/trace/bpf_trace.c:bpf_trace_vprintk
  - kernel/trace/bpf_trace.c:bpf_trace_printk
```
```
In kernel/trace/trace_kprobe.c (ffffffff8125cf0d)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:append_trace_kprobe
```
```
In kernel/trace/trace_uprobe.c (ffffffff812656fa)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:__uprobe_perf_func
  - kernel/trace/trace_uprobe.c:__uprobe_perf_func
```
```
In kernel/trace/fprobe.c (ffffffff812685dd)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In kernel/trace/rethook.c (ffffffff8126922a)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/trace/rethook.c:rethook_trampoline_handler
  - kernel/trace/rethook.c:rethook_flush_task
```
```
In kernel/irq_work.c (ffffffff812694c5)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_queue_on
```
```
In kernel/bpf/core.c (ffffffff8126e5f5)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_user_rnd_u32
```
```
In kernel/bpf/helpers.c (ffffffff81297f72)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_bprintf_prepare
  - kernel/bpf/helpers.c:copy_map_value_locked
```
```
In kernel/bpf/trampoline.c (ffffffff812aa0af)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_update
```
```
In kernel/bpf/devmap.c (ffffffff812bba1a)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_generic_redirect
  - kernel/bpf/devmap.c:bq_xmit_all
  - kernel/bpf/devmap.c:dev_map_bpf_prog_run
```
```
In kernel/bpf/cpumap.c (ffffffff812bd638)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_generic_redirect
  - kernel/bpf/cpumap.c:bq_flush_to_queue
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_skb
```
```
In kernel/bpf/offload.c (ffffffff812be007)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In kernel/static_call_inline.c (ffffffff812cbf98)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/static_call_inline.c:static_call_text_reserved
```
```
In kernel/events/core.c (ffffffff812e0f95)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:perf_event_read
```
```
In kernel/events/ring_buffer.c (ffffffff812e2d79)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
```
```
In kernel/events/uprobes.c (ffffffff812e8145)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_end_dup_mmap
  - kernel/events/uprobes.c:uprobe_start_dup_mmap
  - kernel/events/uprobes.c:__update_ref_ctr
  - kernel/events/uprobes.c:copy_to_page
  - kernel/events/uprobes.c:copy_from_page
```
```
In kernel/user-return-notifier.c (ffffffff812e94a5)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/user-return-notifier.c:fire_user_return_notifiers
```
```
In kernel/padata.c (ffffffff812e9a52)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:invoke_padata_reorder
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_parallel_worker
```
```
In kernel/jump_label.c (ffffffff812eadfd)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_update
  - kernel/jump_label.c:jump_label_text_reserved
  - kernel/jump_label.c:jump_label_add_module
```
```
In kernel/rseq.c (ffffffff812ec956)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/rseq.c:rseq_ip_fixup
  - kernel/rseq.c:rseq_ip_fixup
  - kernel/rseq.c:rseq_update_cpu_id
```
```
In kernel/watch_queue.c (ffffffff812ecfc1)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In mm/filemap.c (ffffffff812f1b26)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:file_check_and_advance_wb_err
  - mm/filemap.c:__filemap_set_wb_err
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__filemap_remove_folio
```
```
In mm/oom_kill.c (ffffffff812f9523)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - mm/oom_kill.c:mark_oom_victim
  - mm/oom_kill.c:wake_oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
```
```
In mm/page-writeback.c (ffffffff812fcae7)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - mm/page-writeback.c:folio_wait_writeback_killable
  - mm/page-writeback.c:folio_wait_writeback
  - mm/page-writeback.c:folio_account_dirtied
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:wb_update_dirty_ratelimit
  - mm/page-writeback.c:domain_dirty_limits
```
```
In mm/swap.c (ffffffff8130344b)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:__pagevec_release
  - mm/swap.c:lru_add_drain_per_cpu
  - mm/swap.c:lru_add_drain_cpu_zone
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:deactivate_file_folio
  - mm/swap.c:folio_add_lru
  - mm/swap.c:folio_mark_accessed
  - mm/swap.c:folio_mark_accessed
  - mm/swap.c:__folio_activate
```
```
In mm/vmscan.c (ffffffff81312c3f)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - mm/vmscan.c:__node_reclaim
  - mm/vmscan.c:__node_reclaim
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:mem_cgroup_shrink_node
  - mm/vmscan.c:mem_cgroup_shrink_node
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:pageout
  - mm/vmscan.c:reclaim_throttle
  - mm/vmscan.c:do_shrink_slab
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/shmem.c (ffffffff8131cba8)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/util.c (ffffffff8131e555)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - mm/util.c:memcmp_pages
  - mm/util.c:memcmp_pages
```
```
In mm/backing-dev.c (ffffffff813245ee)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_register_va
```
```
In mm/percpu.c (ffffffff813275d6)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_free
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_create_chunk
```
```
In mm/slab_common.c (ffffffff8132c3f0)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_order_trace
```
```
In mm/compaction.c (ffffffff81333100)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
  - mm/compaction.c:wakeup_kcompactd
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compaction_suitable
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:compaction_defer_reset
  - mm/compaction.c:compaction_deferred
  - mm/compaction.c:defer_compaction
```
```
In mm/mmap_lock.c (ffffffff8133c665)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - mm/mmap_lock.c:__mmap_lock_do_trace_released
  - mm/mmap_lock.c:__mmap_lock_do_trace_released
  - mm/mmap_lock.c:__mmap_lock_do_trace_acquire_returned
  - mm/mmap_lock.c:__mmap_lock_do_trace_acquire_returned
  - mm/mmap_lock.c:__mmap_lock_do_trace_start_locking
  - mm/mmap_lock.c:__mmap_lock_do_trace_start_locking
```
```
In mm/memory.c (ffffffff81348b2e)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:do_set_pmd
  - mm/memory.c:wp_page_copy
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:add_mm_counter_fast
  - mm/memory.c:sync_mm_rss
```
```
In mm/mlock.c (ffffffff8134c435)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - mm/mlock.c:munlock_page
  - mm/mlock.c:mlock_new_page
  - mm/mlock.c:mlock_folio
  - mm/mlock.c:mlock_page_drain_local
```
```
In mm/mmap.c (ffffffff8134f683)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - mm/mmap.c:vm_unmapped_area
```
```
In mm/rmap.c (ffffffff8135e734)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff81362973)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In mm/page_alloc.c (ffffffff8137037d)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:rmqueue_bulk
  - mm/page_alloc.c:rmqueue_bulk
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/memory_hotplug.c (ffffffff81373ab2)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
```
```
In mm/swapfile.c (ffffffff8137e2bd)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:swp_swapcount
```
```
In mm/zswap.c (ffffffff81385663)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/hugetlb.c (0)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In mm/mempolicy.c (ffffffff81395140)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_page_interleave
```
```
In mm/ksm.c (ffffffff8139e435)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - mm/ksm.c:calc_checksum
```
```
In mm/page_poison.c (ffffffff813a37e1)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - mm/page_poison.c:__kernel_unpoison_pages
  - mm/page_poison.c:__kernel_poison_pages
```
```
In mm/slub.c (ffffffff813a736d)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - mm/slub.c:validate_slab
  - mm/slub.c:validate_slab
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:kfree
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc_lru
  - mm/slub.c:kmem_cache_alloc_lru
  - mm/slub.c:kmem_cache_alloc
  - mm/slub.c:kmem_cache_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:__unfreeze_partials
  - mm/slub.c:free_debug_processing
```
```
In mm/kfence/core.c (ffffffff813aea89)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_protect_page
```
```
In mm/kfence/report.c (ffffffff81e74896)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - mm/kfence/report.c:kfence_report_error
```
```
In mm/migrate.c (ffffffff813b5707)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff813c1eee)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
```
```
In mm/khugepaged.c (ffffffff813c7374)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (ffffffff813d4a94)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_flush_foreign
  - mm/memcontrol.c:mem_cgroup_track_foreign_dirty_slowpath
```
```
In mm/memory-failure.c (ffffffff813d8d83)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure_queue
  - mm/memory-failure.c:action_result
```
```
In mm/page_isolation.c (ffffffff813deb8b)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
```
```
In mm/zsmalloc.c (ffffffff813e2496)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - mm/zsmalloc.c:__zs_compact
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:obj_free
  - mm/zsmalloc.c:obj_malloc
  - mm/zsmalloc.c:zs_map_object
  - mm/zsmalloc.c:zs_map_object
  - mm/zsmalloc.c:__zs_map_object
  - mm/zsmalloc.c:__zs_map_object
  - mm/zsmalloc.c:alloc_zspage
```
```
In mm/userfaultfd.c (ffffffff813e470f)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In fs/open.c (ffffffff813ec24e)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
  - fs/open.c:vfs_fallocate
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:do_sys_ftruncate
```
```
In fs/read_write.c (ffffffff813f30d9)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_write
  - fs/read_write.c:vfs_write
```
```
In fs/exec.c (ffffffff813fa662)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/exec.c:exec_binprm
  - fs/exec.c:remove_arg_zero
  - fs/exec.c:__set_task_comm
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/exec.c:copy_string_kernel
```
```
In fs/pipe.c (ffffffff813fdd4d)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
```
```
In fs/dcache.c (ffffffff81413192)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
```
```
In fs/inode.c (ffffffff814195d7)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/inode.c:touch_atime
  - fs/inode.c:touch_atime
  - fs/inode.c:get_next_ino
```
```
In fs/file.c (ffffffff8141ab27)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/file.c:fd_install
```
```
In fs/namespace.c (ffffffff8141e729)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write
  - fs/namespace.c:mnt_drop_write
  - fs/namespace.c:mnt_want_write
  - fs/namespace.c:mnt_want_write
  - fs/namespace.c:__mnt_want_write
```
```
In fs/fs-writeback.c (ffffffff814334b7)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_do_writeback
  - fs/fs-writeback.c:wb_writeback
  - fs/fs-writeback.c:wb_writeback
  - fs/fs-writeback.c:wb_writeback
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fs-writeback.c:write_inode
  - fs/fs-writeback.c:write_inode
  - fs/fs-writeback.c:queue_io
  - fs/fs-writeback.c:sb_clear_inode_writeback
  - fs/fs-writeback.c:sb_mark_inode_writeback
  - fs/fs-writeback.c:wb_start_background_writeback
  - fs/fs-writeback.c:wbc_detach_inode
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:wb_queue_work
```
```
In fs/splice.c (ffffffff814392e6)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
```
```
In fs/fs_struct.c (0)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In fs/remap_range.c (ffffffff81442617)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_clone_file_range
  - fs/remap_range.c:vfs_clone_file_range
```
```
In fs/buffer.c (ffffffff81442e95)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/buffer.c:free_buffer_head
  - fs/buffer.c:alloc_buffer_head
  - fs/buffer.c:invalidate_bh_lru
  - fs/buffer.c:mark_buffer_dirty
```
```
In fs/userfaultfd.c (0)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In fs/aio.c (ffffffff81465366)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_write
  - fs/aio.c:aio_complete_rw
  - fs/aio.c:aio_read_events_ring
  - fs/aio.c:aio_read_events_ring
  - fs/aio.c:aio_complete
  - fs/aio.c:aio_complete
  - fs/aio.c:ioctx_add_table
  - fs/aio.c:aio_setup_ring
```
```
In fs/dax.c (ffffffff8146990e)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pte_fault
  - fs/dax.c:dax_iomap_pte_fault
  - fs/dax.c:dax_fault_iter
  - fs/dax.c:dax_fault_cow_page
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_one
```
```
In fs/verity/verify.c (ffffffff814743f9)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/verity/verify.c:extract_hash
```
```
In fs/locks.c (ffffffff8147b471)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/locks.c:locks_remove_file
  - fs/locks.c:locks_remove_file
  - fs/locks.c:locks_remove_posix
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:generic_setlease
  - fs/locks.c:generic_setlease
  - fs/locks.c:generic_setlease
  - fs/locks.c:generic_add_lease
  - fs/locks.c:generic_add_lease
  - fs/locks.c:generic_add_lease
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:leases_conflict
  - fs/locks.c:time_out_leases
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:locks_get_lock_context
```
```
In fs/mbcache.c (ffffffff81481cf2)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete_or_get
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/coredump.c (ffffffff81485ec9)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
```
```
In fs/iomap/iter.c (ffffffff81487d75)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/iomap/iter.c:iomap_iter
  - fs/iomap/iter.c:iomap_iter_done
  - fs/iomap/iter.c:iomap_iter_done
```
```
In fs/iomap/buffered-io.c (ffffffff8148a690)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_do_writepage
  - fs/iomap/buffered-io.c:iomap_invalidate_folio
  - fs/iomap/buffered-io.c:iomap_release_folio
  - fs/iomap/buffered-io.c:iomap_readahead
  - fs/iomap/buffered-io.c:iomap_read_folio
```
```
In fs/iomap/direct-io.c (ffffffff8148d818)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:__iomap_dio_rw
```
```
In fs/proc/base.c (ffffffff814a1638)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In fs/ext4/balloc.c (ffffffff814c01dc)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ext4_jbd2.c (ffffffff814c2e11)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb
```
```
In fs/ext4/extents.c (ffffffff814c9e5a)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/extents_status.c (ffffffff814d0bfd)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_insert_delayed_block
  - fs/ext4/extents_status.c:ext4_es_scan
  - fs/ext4/extents_status.c:ext4_es_scan
  - fs/ext4/extents_status.c:ext4_es_count
  - fs/ext4/extents_status.c:__es_shrink
  - fs/ext4/extents_status.c:ext4_es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_cache_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_find_extent_range
  - fs/ext4/extents_status.c:ext4_es_find_extent_range
```
```
In fs/ext4/file.c (ffffffff814d0f3c)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_sample_last_mounted
  - fs/ext4/file.c:ext4_sample_last_mounted
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/fsmap.c (ffffffff814d36f0)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/fsmap.c:ext4_getfsmap_logdev
  - fs/ext4/fsmap.c:ext4_getfsmap_logdev
  - fs/ext4/fsmap.c:ext4_getfsmap_helper
  - fs/ext4/fsmap.c:ext4_getfsmap_helper
```
```
In fs/ext4/fsync.c (ffffffff814d3cd8)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/ialloc.c (ffffffff814d6949)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff814d954c)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inline.c (ffffffff814dd7b1)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff814ebf85)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_update_other_inode_time
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_release_folio
  - fs/ext4/inode.c:__ext4_journalled_invalidate_folio
  - fs/ext4/inode.c:ext4_invalidate_folio
  - fs/ext4/inode.c:ext4_read_folio
  - fs/ext4/inode.c:ext4_alloc_da_blocks
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_map_one_extent
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_da_reserve_space
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (ffffffff814ed2b5)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioc_getfsmap
  - fs/ext4/ioctl.c:ext4_ioc_getfsmap
  - fs/ext4/ioctl.c:ext4_getfsmap_format
  - fs/ext4/ioctl.c:ext4_shutdown
  - fs/ext4/ioctl.c:ext4_update_backup_sb
  - fs/ext4/ioctl.c:ext4_update_primary_sb
```
```
In fs/ext4/mballoc.c (ffffffff814f6a0b)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_preallocations_should_retry
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_collect_stats
  - fs/ext4/mballoc.c:ext4_mb_collect_stats
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/mmp.c (ffffffff814fda50)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/namei.c (ffffffff8150823b)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_unlink
  - fs/ext4/namei.c:ext4_unlink
```
```
In fs/ext4/super.c (ffffffff8152356c)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:ext4_run_li_request
  - fs/ext4/super.c:ext4_run_li_request
  - fs/ext4/super.c:ext4_nfs_commit_metadata
  - fs/ext4/super.c:ext4_drop_inode
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
```
```
In fs/ext4/fast_commit.c (ffffffff815396f0)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay_create
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
  - fs/ext4/fast_commit.c:ext4_fc_commit
  - fs/ext4/fast_commit.c:ext4_fc_update_stats
  - fs/ext4/fast_commit.c:ext4_fc_track_range
  - fs/ext4/fast_commit.c:ext4_fc_track_inode
  - fs/ext4/fast_commit.c:__ext4_fc_track_create
  - fs/ext4/fast_commit.c:__ext4_fc_track_link
  - fs/ext4/fast_commit.c:__ext4_fc_track_unlink
```
```
In fs/jbd2/transaction.c (ffffffff8153e879)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
  - fs/jbd2/transaction.c:jbd2__journal_start
```
```
In fs/jbd2/commit.c (ffffffff81540e58)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_data_buffers
```
```
In fs/jbd2/checkpoint.c (ffffffff81543780)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_drop_transaction
  - fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_journal_shrink_checkpoint_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff8154c154)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_journal_shrink_count
  - fs/jbd2/journal.c:jbd2_journal_shrink_scan
  - fs/jbd2/journal.c:jbd2_journal_shrink_scan
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/squashfs/file.c (ffffffff8154eac9)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_read_folio
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (ffffffff81550c98)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_read_folio
```
```
In fs/squashfs/file_direct.c (ffffffff815516b5)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/squashfs/page_actor.c (ffffffff81551858)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/squashfs/page_actor.c:direct_next_page
  - fs/squashfs/page_actor.c:direct_first_page
```
```
In fs/squashfs/decompressor_multi_percpu.c (ffffffff81551c75)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/squashfs/decompressor_multi_percpu.c:squashfs_decompress
```
```
In fs/ecryptfs/mmap.c (ffffffff81568b76)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
```
In fs/ecryptfs/read_write.c (ffffffff815699a9)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dax.c (ffffffff8158abde)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/fuse/dax.c:__fuse_dax_fault
  - fs/fuse/dax.c:__fuse_dax_fault
```
```
In ipc/util.c (ffffffff815939a7)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In security/selinux/avc.c (ffffffff815bf80a)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_audit_post_callback
```
```
In security/smack/smack_lsm.c (ffffffff815ef26f)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smk_ipv4_check
  - security/smack/smack_lsm.c:smack_netlbl_add
```
```
In security/tomoyo/domain.c (ffffffff81600932)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In security/apparmor/capability.c (ffffffff8160f695)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - security/apparmor/capability.c:audit_caps
```
```
In security/apparmor/policy_unpack.c (ffffffff8161d6d9)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In crypto/scatterwalk.c (ffffffff8164e72d)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/skcipher.c (0)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In crypto/ahash.c (ffffffff81651366)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - crypto/ahash.c:hash_walk_next
```
```
In crypto/shash.c (ffffffff81653343)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_digest
```
```
In block/bio.c (ffffffff816727d7)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - block/bio.c:bio_endio
  - block/bio.c:bio_put
  - block/bio.c:bio_alloc_bioset
```
```
In block/blk-core.c (ffffffff81679bfc)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - block/blk-core.c:bdev_end_io_acct
  - block/blk-core.c:bdev_start_io_acct
  - block/blk-core.c:submit_bio_noacct
  - block/blk-core.c:submit_bio_noacct
```
```
In block/blk-flush.c (ffffffff8167c13c)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-merge.c (ffffffff81681381)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_front_merge
  - block/blk-merge.c:bio_attempt_back_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:__blk_queue_split
```
```
In block/blk-mq.c (ffffffff8168804a)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - block/blk-mq.c:blk_insert_cloned_request
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:blk_mq_commit_rqs
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:__blk_mq_insert_request
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:blk_execute_rq
  - block/blk-mq.c:blk_execute_rq_nowait
  - block/blk-mq.c:blk_add_rq_to_plug
  - block/blk-mq.c:blk_mq_start_request
  - block/blk-mq.c:blk_mq_complete_request_remote
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:__blk_account_io_done
  - block/blk-mq.c:blk_update_request
  - block/blk-mq.c:blk_update_request
```
```
In block/blk-stat.c (ffffffff8168ddcb)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_add
```
```
In block/genhd.c (ffffffff816925e3)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - block/genhd.c:diskstats_show
  - block/genhd.c:part_stat_show
```
```
In block/blk-cgroup.c (ffffffff816a4d5e)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - block/blk-cgroup.c:blk_cgroup_bio_start
```
```
In block/blk-iocost.c (ffffffff816b2313)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:adjust_inuse_and_calc_cost
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_forgive_debts
  - block/blk-iocost.c:transfer_surpluses
  - block/blk-iocost.c:iocg_wake_fn
  - block/blk-iocost.c:iocg_incur_debt
  - block/blk-iocost.c:iocg_activate
```
```
In block/mq-deadline.c (ffffffff816b44e1)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In block/blk-wbt.c (ffffffff816bab08)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:rwb_trace_step
```
```
In io_uring/io_uring.c (ffffffff816d8ce6)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - io_uring/io_uring.c:__ia32_sys_io_uring_register
  - io_uring/io_uring.c:__x64_sys_io_uring_register
  - io_uring/io_uring.c:io_uring_create
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/io_uring.c:io_submit_sqes
  - io_uring/io_uring.c:io_submit_sqes
  - io_uring/io_uring.c:io_submit_fail_init
  - io_uring/io_uring.c:io_file_get_normal
  - io_uring/io_uring.c:io_drain_req
  - io_uring/io_uring.c:io_arm_poll_handler
  - io_uring/io_uring.c:io_write
  - io_uring/io_uring.c:io_fail_links
  - io_uring/io_uring.c:io_fill_cqe_aux
  - io_uring/io_uring.c:io_cqring_event_overflow
  - io_uring/io_uring.c:io_queue_iowq
```
```
In io_uring/io-wq.c (ffffffff816db33c)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wqe_worker
```
```
In lib/scatterlist.c (ffffffff816df423)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In lib/iov_iter.c (ffffffff816e2d1a)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - lib/iov_iter.c:copy_page_from_iter_atomic
```
```
In lib/rhashtable.c (ffffffff816ea0d3)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In lib/percpu_counter.c (ffffffff8175e5c0)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - lib/percpu_counter.c:percpu_counter_add_batch
```
```
In lib/irq_poll.c (ffffffff8176ef50)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_cpu_dead
```
```
In arch/x86/lib/msr-smp.c (ffffffff81774f76)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:wrmsr_on_cpus
  - arch/x86/lib/msr-smp.c:rdmsr_on_cpus
```
```
In arch/x86/lib/msr.c (ffffffff817758a9)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:do_trace_rdpmc
  - arch/x86/lib/msr.c:do_trace_read_msr
  - arch/x86/lib/msr.c:do_trace_write_msr
```
```
In lib/bug.c (ffffffff81776320)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - lib/bug.c:generic_bug_clear_once
  - lib/bug.c:find_bug
```
```
In lib/buildid.c (ffffffff817765b5)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - lib/buildid.c:build_id_parse
```
```
In lib/flex_proportions.c (0)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In lib/nmi_backtrace.c (ffffffff8177c6a0)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
```
In lib/radix-tree.c (ffffffff8177cbe7)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - lib/radix-tree.c:__radix_tree_preload
  - lib/radix-tree.c:__radix_tree_preload
```
```
In arch/x86/lib/delay.c (ffffffff8178eac5)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/lib/delay.c:delay_tsc
  - arch/x86/lib/delay.c:delay_tsc
```
```
In arch/x86/lib/usercopy_64.c (ffffffff81792195)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:memcpy_page_flushcache
```
```
In drivers/gpio/gpiolib.c (ffffffff817a798b)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_source_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_drain_value_commit
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_input
```
```
In drivers/pwm/core.c (ffffffff817b5630)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwm_apply_state
  - drivers/pwm/core.c:pwm_device_request
```
```
In drivers/pci/pcie/aer.c (ffffffff817dae0c)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_print_error
```
```
In drivers/acpi/sleep.c (ffffffff81826bec)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_suspend_enter
  - drivers/acpi/sleep.c:acpi_suspend_enter
```
```
In drivers/acpi/prmt.c (ffffffff81842e0b)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/acpi/prmt.c:acpi_platformrt_space_handler
```
```
In drivers/clk/clk.c (ffffffff818ad68f)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_set_duty_cycle_nolock
  - drivers/clk/clk.c:clk_core_set_duty_cycle_nolock
  - drivers/clk/clk.c:clk_core_set_phase_nolock
  - drivers/clk/clk.c:clk_core_set_phase_nolock
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_unprepare_unused_subtree
  - drivers/clk/clk.c:clk_unprepare_unused_subtree
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/clk/clk.c:clk_core_prepare
  - drivers/clk/clk.c:clk_core_prepare
  - drivers/clk/clk.c:clk_core_unprepare
  - drivers/clk/clk.c:clk_core_unprepare
```
```
In drivers/xen/events/events_2l.c (ffffffff818d1088)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
```
```
In drivers/xen/swiotlb-xen.c (ffffffff818ddba6)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
```
```
In drivers/regulator/core.c (ffffffff818e65f3)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
```
```
In drivers/char/virtio_console.c (ffffffff81936518)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/iommu/intel/dmar.c (ffffffff81957486)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:qi_submit_sync
```
```
In drivers/iommu/intel/svm.c (ffffffff81961704)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:prq_event_thread
```
```
In drivers/iommu/iommu.c (ffffffff81965cce)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:report_iommu_fault
  - drivers/iommu/iommu.c:__iommu_unmap
  - drivers/iommu/iommu.c:__iommu_map
  - drivers/iommu/iommu.c:iommu_group_do_detach_device
  - drivers/iommu/iommu.c:__iommu_attach_device
  - drivers/iommu/iommu.c:iommu_group_remove_device
  - drivers/iommu/iommu.c:iommu_group_add_device
```
```
In drivers/connector/cn_proc.c (ffffffff81972bb1)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/connector/cn_proc.c:proc_exit_connector
  - drivers/connector/cn_proc.c:proc_coredump_connector
  - drivers/connector/cn_proc.c:proc_comm_connector
  - drivers/connector/cn_proc.c:proc_ptrace_connector
  - drivers/connector/cn_proc.c:proc_sid_connector
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/connector/cn_proc.c:proc_exec_connector
  - drivers/connector/cn_proc.c:proc_fork_connector
```
```
In drivers/base/syscore.c (ffffffff8197e8b5)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
```
```
In drivers/base/devres.c (ffffffff81983b93)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/base/devres.c:__devm_alloc_percpu
  - drivers/base/devres.c:devm_krealloc
  - drivers/base/devres.c:devm_add_action
  - drivers/base/devres.c:devres_remove_group
  - drivers/base/devres.c:devres_close_group
  - drivers/base/devres.c:devres_open_group
  - drivers/base/devres.c:release_nodes
  - drivers/base/devres.c:devres_remove
  - drivers/base/devres.c:devres_get
```
```
In drivers/base/power/qos.c (ffffffff8198e301)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/base/power/qos.c:__dev_pm_qos_remove_request
  - drivers/base/power/qos.c:__dev_pm_qos_update_request
  - drivers/base/power/qos.c:__dev_pm_qos_add_request
```
```
In drivers/base/power/runtime.c (ffffffff819916e0)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:update_autosuspend
  - drivers/base/power/runtime.c:pm_runtime_allow
  - drivers/base/power/runtime.c:pm_runtime_get_if_active
  - drivers/base/power/runtime.c:__pm_runtime_suspend
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
```
```
In drivers/base/power/main.c (ffffffff819967e6)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/base/power/main.c:dpm_run_callback
  - drivers/base/power/main.c:dpm_run_callback
```
```
In drivers/base/power/wakeup.c (ffffffff81997117)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_activate
```
```
In drivers/base/regmap/regmap.c (ffffffff819a797c)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_async_complete_cb
  - drivers/base/regmap/regmap.c:_regmap_read
  - drivers/base/regmap/regmap.c:_regmap_raw_read
  - drivers/base/regmap/regmap.c:_regmap_raw_read
  - drivers/base/regmap/regmap.c:_regmap_raw_multi_reg_write
  - drivers/base/regmap/regmap.c:_regmap_raw_multi_reg_write
  - drivers/base/regmap/regmap.c:_regmap_write
  - drivers/base/regmap/regmap.c:_regmap_bus_formatted_write
  - drivers/base/regmap/regmap.c:_regmap_bus_formatted_write
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
```
```
In drivers/base/regmap/regcache.c (ffffffff819acc3e)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/base/regmap/regcache.c:regcache_cache_bypass
  - drivers/base/regmap/regcache.c:regcache_cache_only
  - drivers/base/regmap/regcache.c:regcache_drop_region
  - drivers/base/regmap/regcache.c:regcache_sync_region
  - drivers/base/regmap/regcache.c:regcache_sync_region
  - drivers/base/regmap/regcache.c:regcache_sync
  - drivers/base/regmap/regcache.c:regcache_sync
  - drivers/base/regmap/regcache.c:regcache_read
```
```
In drivers/block/loop.c (ffffffff819b6daf)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In drivers/block/xen-blkfront.c (ffffffff819bb697)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_completion
  - drivers/block/xen-blkfront.c:blkif_copy_from_grant
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/nvdimm/region_devs.c (ffffffff819d9a20)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_release_lane
  - drivers/nvdimm/region_devs.c:nd_region_acquire_lane
```
```
In drivers/dma-buf/dma-fence.c (ffffffff819eeada)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:__dma_fence_enable_signaling
  - drivers/dma-buf/dma-fence.c:dma_fence_release
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_signal_timestamp_locked
```
```
In drivers/dma-buf/sw_sync.c (ffffffff819f47e2)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
```
```
In drivers/scsi/scsi_error.c (ffffffff819fd74d)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
```
```
In drivers/scsi/scsi_lib.c (ffffffff819ff9bf)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
  - drivers/scsi/scsi_lib.c:scsi_done_internal
  - drivers/scsi/scsi_lib.c:scsi_dispatch_cmd
  - drivers/scsi/scsi_lib.c:scsi_dispatch_cmd
```
```
In drivers/ata/libata-core.c (ffffffff81a2594a)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-core.c:ata_qc_complete
  - drivers/ata/libata-core.c:ata_qc_complete
  - drivers/ata/libata-core.c:ata_qc_complete
```
```
In drivers/ata/libata-eh.c (ffffffff81a351e3)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_done
  - drivers/ata/libata-eh.c:ata_eh_about_to_do
  - drivers/ata/libata-eh.c:__ata_port_freeze
```
```
In drivers/ata/libata-sff.c (ffffffff81a3c7c4)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_bmdma_post_internal_cmd
  - drivers/ata/libata-sff.c:ata_bmdma_error_handler
  - drivers/ata/libata-sff.c:ata_bmdma_error_handler
  - drivers/ata/libata-sff.c:ata_bmdma_port_intr
  - drivers/ata/libata-sff.c:ata_bmdma_port_intr
  - drivers/ata/libata-sff.c:ata_bmdma_qc_issue
  - drivers/ata/libata-sff.c:ata_bmdma_qc_issue
  - drivers/ata/libata-sff.c:ata_bmdma_qc_issue
  - drivers/ata/libata-sff.c:ata_bmdma_qc_issue
  - drivers/ata/libata-sff.c:ata_bmdma_qc_issue
  - drivers/ata/libata-sff.c:__ata_sff_port_intr
  - drivers/ata/libata-sff.c:ata_sff_flush_pio_task
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:__atapi_pio_bytes
  - drivers/ata/libata-sff.c:__atapi_pio_bytes
  - drivers/ata/libata-sff.c:ata_pio_sector
  - drivers/ata/libata-sff.c:ata_tf_to_host
  - drivers/ata/libata-sff.c:ata_tf_to_host
```
```
In drivers/ata/ata_piix.c (ffffffff81a42607)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/ata/ata_piix.c:piix_irq_check
```
```
In drivers/spi/spi.c (ffffffff81a4f8c3)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_sync
  - drivers/spi/spi.c:__spi_async
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_set_cs
```
```
In drivers/net/phy/mdio_bus.c (ffffffff81a5be49)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:__mdiobus_write
  - drivers/net/phy/mdio_bus.c:__mdiobus_write
  - drivers/net/phy/mdio_bus.c:__mdiobus_read
  - drivers/net/phy/mdio_bus.c:__mdiobus_read
```
```
In drivers/net/tun.c (ffffffff81a67837)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_xdp_act
  - drivers/net/tun.c:tun_napi_alloc_frags
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81a6b6f5)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
```
```
In drivers/net/xen-netfront.c (ffffffff81a736bd)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:netfront_resume
```
```
In drivers/usb/host/xhci.c (ffffffff81af166a)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81af4f59)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_ring_alloc
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81af8529)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:queue_trb
  - drivers/usb/host/xhci-ring.c:xhci_handle_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_port_status
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_ring_ep_doorbell
  - drivers/usb/host/xhci-ring.c:inc_enq
  - drivers/usb/host/xhci-ring.c:inc_deq
```
```
In drivers/usb/host/xhci-hub.c (ffffffff81b01a63)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81b0827a)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events
  - drivers/usb/host/xhci-dbgcap.c:dbc_handle_xfer_event
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_queue_bulk_tx
  - drivers/usb/host/xhci-dbgcap.c:dbc_free_request
  - drivers/usb/host/xhci-dbgcap.c:dbc_alloc_request
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
```
```
In drivers/rtc/interface.c (ffffffff81b298a7)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_set_offset
  - drivers/rtc/interface.c:rtc_read_offset
  - drivers/rtc/interface.c:rtc_timer_cancel
  - drivers/rtc/interface.c:rtc_timer_start
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_alarm_disable
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_irq_set_freq
  - drivers/rtc/interface.c:rtc_irq_set_state
  - drivers/rtc/interface.c:rtc_alarm_irq_enable
  - drivers/rtc/interface.c:rtc_initialize_alarm
  - drivers/rtc/interface.c:__rtc_set_alarm
  - drivers/rtc/interface.c:rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:rtc_read_time
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81b30a67)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff81b33f21)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In drivers/hwmon/hwmon.c (ffffffff81b449af)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:hwmon_attr_store
  - drivers/hwmon/hwmon.c:hwmon_attr_show_string
  - drivers/hwmon/hwmon.c:hwmon_attr_show
```
```
In drivers/thermal/thermal_core.c (ffffffff81b47dbf)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:handle_thermal_trip
```
```
In drivers/thermal/thermal_helpers.c (ffffffff81b4c0e4)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/thermal/thermal_helpers.c:__thermal_cdev_update
```
```
In drivers/thermal/gov_fair_share.c (ffffffff81b4e426)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/thermal/gov_fair_share.c:get_trip_level
```
```
In drivers/thermal/gov_step_wise.c (ffffffff81b4ec87)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/thermal/gov_step_wise.c:thermal_zone_trip_update
```
```
In drivers/thermal/gov_power_allocator.c (ffffffff81b50379)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/thermal/gov_power_allocator.c:allocate_power
  - drivers/thermal/gov_power_allocator.c:pid_controller
```
```
In drivers/thermal/devfreq_cooling.c (ffffffff81b510cb)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_power2state
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power
```
```
In drivers/thermal/intel/therm_throt.c (ffffffff81b518f4)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_package_throttle_total_time_ms
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_core_throttle_total_time_ms
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_package_throttle_max_time_ms
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_core_throttle_max_time_ms
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_package_power_limit_count
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_package_throttle_count
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_core_power_limit_count
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_core_throttle_count
```
```
In drivers/md/md.c (ffffffff81b5a1b3)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/md/md.c:md_submit_discard_bio
```
```
In drivers/md/md-bitmap.c (ffffffff81b6cade)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_file_clear_bit
  - drivers/md/md-bitmap.c:md_bitmap_file_set_bit
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_new_disk_sb
  - drivers/md/md-bitmap.c:md_bitmap_print_sb
```
```
In drivers/md/dm.c (ffffffff81b72bbc)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_split_and_process_bio
  - drivers/md/dm.c:dm_submit_bio_remap
```
```
In drivers/md/dm-stats.c (ffffffff81b7f400)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stat_for_entry
```
```
In drivers/md/dm-rq.c (ffffffff81b8107c)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:map_request
```
```
In drivers/edac/edac_mc.c (ffffffff81b824a6)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
  - drivers/edac/edac_mc.c:edac_mc_scrub_block
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81b8ff85)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_driver_fast_switch
  - drivers/cpufreq/cpufreq.c:cpufreq_notify_transition
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81b936d1)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_init
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81b959f6)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target
```
```
In drivers/cpufreq/amd-pstate.c (ffffffff81b97552)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/cpufreq/amd-pstate.c:amd_pstate_update
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81b9ddf0)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_adjust_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_adjust_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_pstate
```
```
In drivers/cpuidle/cpuidle.c (ffffffff81ba01f3)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_use_deepest_state
```
```
In drivers/cpuidle/driver.c (ffffffff81ba0915)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In drivers/mmc/core/core.c (ffffffff81ba5b5c)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_cqe_request_done
  - drivers/mmc/core/core.c:mmc_cqe_start_req
  - drivers/mmc/core/core.c:__mmc_start_request
  - drivers/mmc/core/core.c:mmc_request_done
```
```
In drivers/firmware/efi/capsule.c (ffffffff81bbf5bc)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/firmware/efi/capsule.c:efi_capsule_update
```
```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff81bc3241)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
```
```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff81bc88fc)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_proto.c:send_command
  - drivers/platform/chrome/cros_ec_proto.c:send_command
  - drivers/platform/chrome/cros_ec_proto.c:send_command
  - drivers/platform/chrome/cros_ec_proto.c:send_command
```
```
In drivers/devfreq/devfreq.c (ffffffff81bd457e)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_monitor
  - drivers/devfreq/devfreq.c:devfreq_set_target
```
```
In drivers/ras/ras.c (ffffffff81bdebf5)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/ras/ras.c:log_arm_hw_error
  - drivers/ras/ras.c:log_non_standard_event
```
```
In drivers/interconnect/core.c (ffffffff81be3a09)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/interconnect/core.c:icc_set_bw
  - drivers/interconnect/core.c:icc_set_bw
```
```
In net/core/sock.c (ffffffff81bed7e2)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:sk_error_report
```
```
In net/core/skbuff.c (ffffffff81bf77b5)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:__consume_stateless_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_frag_align
```
```
In net/core/datagram.c (ffffffff81c00227)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_datagram_iter
```
```
In net/core/gen_estimator.c (ffffffff81c03643)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/net_namespace.c (ffffffff81c0457c)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/core/dev.c (ffffffff81c1d95d)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:__dev_set_allmulti
  - net/core/dev.c:dev_set_promiscuity
  - net/core/dev.c:napi_threaded_poll
  - net/core/dev.c:__napi_poll
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:flush_backlog
  - net/core/dev.c:netif_receive_skb
  - net/core/dev.c:netif_receive_skb
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__netif_rx
  - net/core/dev.c:__netif_rx
  - net/core/dev.c:netif_rx_internal
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:__dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_qdisc_enqueue
  - net/core/dev.c:dev_hard_start_xmit
  - net/core/dev.c:dev_hard_start_xmit
  - net/core/dev.c:__dev_open
```
```
In net/core/dev_addr_lists.c (ffffffff81c21275)
Location: arch/x86/include/asm/preempt.h:78
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
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_seq_start
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_for_each
  - net/core/neighbour.c:neigh_dump_table
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
  - net/core/neighbour.c:neigh_cleanup_and_release
```
```
In net/core/rtnetlink.c (ffffffff81c317fe)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_fdb_dump
```
```
In net/core/filter.c (ffffffff81c3db1c)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_socket_ptr_cookie
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_redirect_frame
  - net/core/filter.c:xdp_do_redirect_frame
  - net/core/filter.c:xdp_do_redirect_frame
  - net/core/filter.c:xdp_do_redirect_frame
  - net/core/filter.c:xdp_do_redirect
  - net/core/filter.c:xdp_do_redirect
  - net/core/filter.c:xdp_do_redirect
  - net/core/filter.c:xdp_do_redirect
  - net/core/filter.c:bpf_out_neigh_v6
```
```
In net/core/sock_diag.c (ffffffff81c4dfc5)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_save_cookie
  - net/core/sock_diag.c:sock_diag_check_cookie
```
```
In net/core/xdp.c (ffffffff81c51078)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/core/xdp.c:mem_allocator_disconnect
```
```
In net/core/gro.c (ffffffff81c54602)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/core/gro.c:napi_gro_frags
  - net/core/gro.c:napi_gro_frags
  - net/core/gro.c:napi_gro_receive
  - net/core/gro.c:napi_gro_receive
```
```
In net/core/page_pool.c (ffffffff81c5909a)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_update_nid
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_release_page
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
```
```
In net/core/net-procfs.c (ffffffff81c5aecc)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In net/core/netpoll.c (ffffffff81c5b475)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
  - net/core/netpoll.c:poll_one_napi
```
```
In net/core/net-traces.c (ffffffff81c6623d)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:perf_trace_tcp_event_sk
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk
```
```
In net/core/lwt_bpf.c (ffffffff81c70a3e)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In net/core/devlink.c (ffffffff81c727dc)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_trap_report
  - net/core/devlink.c:devlink_health_report
  - net/core/devlink.c:devlink_health_report
```
```
In net/core/sock_map.c (ffffffff81c903bc)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_update_elem
  - net/core/sock_map.c:sock_map_update_elem_sys
```
```
In net/sched/sch_generic.c (ffffffff81c96e5d)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:qdisc_reset
  - net/sched/sch_generic.c:qdisc_create_dflt
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/sched/sch_api.c (ffffffff81c9b668)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In net/sched/act_api.c (ffffffff81ca53c7)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_update_hw_stats
```
```
In net/netlink/af_netlink.c (ffffffff81ca9c45)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:do_trace_netlink_extack
```
```
In net/bpf/test_run.c (ffffffff81cb6139)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_sk_lookup
  - net/bpf/test_run.c:bpf_prog_test_run_sk_lookup
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_prog_test_run_raw_tp
  - net/bpf/test_run.c:bpf_prog_test_run_tracing
  - net/bpf/test_run.c:bpf_test_timer_continue
```
```
In net/netfilter/nf_log.c (ffffffff81ccad76)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/netfilter/nf_log.c:nf_log_buf_open
```
```
In net/netfilter/nf_queue.c (ffffffff81ccbc87)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_reinject
```
```
In net/ipv4/route.c (ffffffff81ccec58)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81cd974e)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_hashtables.c (ffffffff81ce2c20)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81ce3a31)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ce51a3)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/tcp.c (ffffffff81ceefaf)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_abort
  - net/ipv4/tcp.c:tcp_abort
  - net/ipv4/tcp.c:__tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff81cfcee5)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_reset
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
```
```
In net/ipv4/tcp_output.c (ffffffff81cfef15)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_rtx_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d09652)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81d0ed31)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/tcp_cong.c (ffffffff81d0fc04)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_set_ca_state
```
```
In net/ipv4/udp.c (ffffffff81d1c9ee)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/icmp.c (ffffffff81d24436)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_reply
```
```
In net/ipv4/af_inet.c (ffffffff81d2e1c2)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sk_state_store
  - net/ipv4/af_inet.c:inet_sk_set_state
```
```
In net/ipv4/fib_frontend.c (ffffffff81d34d1a)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_lookup
```
```
In net/ipv4/fib_semantics.c (ffffffff81d3b986)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/fib_trie.c (ffffffff81d3f1a1)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv4/inet_fragment.c (ffffffff81d418b8)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81d44c71)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/nexthop.c (ffffffff81d48c5e)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_select_path_hthr
  - net/ipv4/nexthop.c:nexthop_select_path_hthr
```
```
In net/ipv4/ipmr.c (ffffffff81d55df5)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d68133)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In net/xfrm/xfrm_state.c (0)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In net/xfrm/espintcp.c (ffffffff81d7ae40)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_rcv
```
```
In net/ipv6/ip6_output.c (ffffffff81d87695)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/addrconf.c (ffffffff81d9747d)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff81da21ff)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:fib6_table_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:rt6_probe
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ip6_fib.c (ffffffff81dabc97)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_start
```
```
In net/ipv6/icmp.c (ffffffff81dc018e)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dcce8a)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81dd312f)
Location: arch/x86/include/asm/preempt.h:78
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
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/ip6mr.c (ffffffff81ddb50a)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81de7161)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
```
```
In net/ipv6/seg6_local.c (ffffffff81dea207)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
```
```
In net/ipv6/seg6_hmac.c (ffffffff81dea81b)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff81dec3ff)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
```
```
In net/mptcp/protocol.c (ffffffff81e2170c)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_subflow_get_send
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
```
```
In net/mptcp/subflow.c (ffffffff81e26d29)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:get_mapping_status
```
```
In net/mptcp/options.c (ffffffff81e29c3f)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/mptcp/options.c:ack_update_msk
```
```
In net/mctp/af_mctp.c (ffffffff81e37588)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In net/mctp/route.c (ffffffff81e3a927)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_alloc_local_tag
  - net/mctp/route.c:mctp_route_input
  - net/mctp/route.c:__mctp_key_done_in
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
In init/main.c (ffffffff83e61a6b)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
  - init/main.c:do_initcalls
  - init/main.c:do_one_initcall
  - init/main.c:do_one_initcall
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff810055c3)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
```
```
In arch/x86/events/amd/ibs.c (ffffffff83e65ac0)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
```
```
In arch/x86/events/intel/ds.c (ffffffff8101786e)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:ds_clear_cea
  - arch/x86/events/intel/ds.c:ds_update_cea
```
```
In arch/x86/events/intel/p4.c (ffffffff8101e9a5)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_hw_config
```
```
In arch/x86/xen/time.c (ffffffff83e6af45)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_hvm_init_time_ops
  - arch/x86/xen/time.c:xen_init_time_ops
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_restore_time_memory_area
  - arch/x86/xen/time.c:xen_save_time_memory_area
  - arch/x86/xen/time.c:xen_vcpuop_set_next_event
  - arch/x86/xen/time.c:xen_timerop_set_next_event
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
  - arch/x86/xen/time.c:xen_get_wallclock
  - arch/x86/xen/time.c:xen_sched_clock
  - arch/x86/xen/time.c:xen_clocksource_get_cycles
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff81038342)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_cr0
  - arch/x86/xen/enlighten_pv.c:xen_load_sp0
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry
  - arch/x86/xen/enlighten_pv.c:xen_load_idt
  - arch/x86/xen/enlighten_pv.c:xen_write_idt_entry
  - arch/x86/xen/enlighten_pv.c:xen_write_idt_entry
  - arch/x86/xen/enlighten_pv.c:xen_write_ldt_entry
  - arch/x86/xen/enlighten_pv.c:xen_write_ldt_entry
  - arch/x86/xen/enlighten_pv.c:load_TLS_descriptor
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
  - arch/x86/xen/enlighten_pv.c:xen_mc_batch
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81039f75)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_all
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_all
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_leave_lazy_mmu
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:__xen_write_cr3
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
  - arch/x86/xen/mmu_pv.c:xen_set_p4d_hyper
  - arch/x86/xen/mmu_pv.c:xen_set_pud
  - arch/x86/xen/mmu_pv.c:xen_set_pud_hyper
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_start
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pmd
  - arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper
  - arch/x86/xen/mmu_pv.c:xen_extend_mmuext_op
  - arch/x86/xen/mmu_pv.c:xen_extend_mmu_update
  - arch/x86/xen/mmu_pv.c:xen_mc_batch
```
```
In arch/x86/xen/multicalls.c (ffffffff8103dd5f)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/xen/multicalls.c:xen_mc_callback
  - arch/x86/xen/multicalls.c:xen_mc_callback
  - arch/x86/xen/multicalls.c:xen_mc_extend_args
  - arch/x86/xen/multicalls.c:xen_mc_extend_args
  - arch/x86/xen/multicalls.c:xen_mc_extend_args
  - arch/x86/xen/multicalls.c:__xen_mc_entry
  - arch/x86/xen/multicalls.c:__xen_mc_entry
  - arch/x86/xen/multicalls.c:xen_mc_flush
```
```
In arch/x86/hyperv/hv_init.c (ffffffff81045039)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:set_hv_tscchange_cb
```
```
In arch/x86/hyperv/mmu.c (ffffffff81046ca6)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
```
```
In arch/x86/hyperv/nested.c (ffffffff810472c4)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8104927a)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_one
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
```
```
In arch/x86/kernel/process_64.c (ffffffff8104ae44)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/signal.c (ffffffff8104b185)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:handle_signal
```
```
In arch/x86/kernel/irq.c (ffffffff8104f5b7)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:__sysvec_thermal
  - arch/x86/kernel/irq.c:__sysvec_thermal
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:__sysvec_x86_platform_ipi
  - arch/x86/kernel/irq.c:__sysvec_x86_platform_ipi
```
```
In arch/x86/kernel/ioport.c (ffffffff81050cce)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In arch/x86/kernel/nmi.c (ffffffff8105247d)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:nmi_handle
```
```
In arch/x86/kernel/irq_work.c (ffffffff810546bc)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:__sysvec_irq_work
  - arch/x86/kernel/irq_work.c:__sysvec_irq_work
```
```
In arch/x86/kernel/tsc.c (ffffffff8105d071)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:native_sched_clock_from_tsc
  - arch/x86/kernel/tsc.c:native_sched_clock
  - arch/x86/kernel/tsc.c:__set_cyc2ns_scale
```
```
In arch/x86/kernel/process.c (ffffffff8105f91a)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:do_arch_prctl_common
  - arch/x86/kernel/process.c:speculation_ctrl_update_current
  - arch/x86/kernel/process.c:enable_cpuid
  - arch/x86/kernel/process.c:set_tsc_mode
  - arch/x86/kernel/process.c:disable_TSC
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81061462)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpregs_mark_activate
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
  - arch/x86/kernel/fpu/core.c:fpu__clear_user_states
  - arch/x86/kernel/fpu/core.c:fpu_reset_fpregs
  - arch/x86/kernel/fpu/core.c:fpu__drop
  - arch/x86/kernel/fpu/core.c:fpu__drop
  - arch/x86/kernel/fpu/core.c:fpu__drop
  - arch/x86/kernel/fpu/core.c:fpu_clone
  - arch/x86/kernel/fpu/core.c:fpu_clone
  - arch/x86/kernel/fpu/core.c:fpu_clone
  - arch/x86/kernel/fpu/core.c:fpu_clone
  - arch/x86/kernel/fpu/core.c:fpu_sync_fpstate
  - arch/x86/kernel/fpu/core.c:fpu_sync_fpstate
  - arch/x86/kernel/fpu/core.c:fpu_sync_fpstate
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin_mask
  - arch/x86/kernel/fpu/core.c:fpu_swap_kvm_fpstate
  - arch/x86/kernel/fpu/core.c:fpu_update_guest_xfd
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8106294d)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8106377d)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpstate_realloc
  - arch/x86/kernel/fpu/xstate.c:fpstate_realloc
```
```
In arch/x86/kernel/tls.c (ffffffff81066bd9)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:set_tls_desc
```
```
In arch/x86/kernel/cpu/aperfmperf.c (0)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81071e13)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:split_lock_warn
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81076655)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:wait_for_panic
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8107b00d)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:__sysvec_deferred_error
  - arch/x86/kernel/cpu/mce/amd.c:__sysvec_deferred_error
```
```
In arch/x86/kernel/cpu/mce/threshold.c (ffffffff8107cd6d)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/threshold.c:__sysvec_threshold
  - arch/x86/kernel/cpu/mce/threshold.c:__sysvec_threshold
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff81080045)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_get_mtrr
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81085fd2)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:update_closid_rmid
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8108aeb3)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:add_rmid_to_limbo
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff8108ba3e)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:resctrl_arch_update_domains
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8108db57)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_l3_residency
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_l2_residency
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff81091b84)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_init
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff81094e11)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_virt_einit
```
```
In arch/x86/kernel/smp.c (ffffffff810987fc)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:__sysvec_call_function_single
  - arch/x86/kernel/smp.c:__sysvec_call_function_single
  - arch/x86/kernel/smp.c:__sysvec_call_function
  - arch/x86/kernel/smp.c:__sysvec_call_function
  - arch/x86/kernel/smp.c:sysvec_reschedule_ipi
  - arch/x86/kernel/smp.c:sysvec_reschedule_ipi
  - arch/x86/kernel/smp.c:sysvec_reschedule_ipi
```
```
In arch/x86/kernel/smpboot.c (ffffffff83e896a5)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:smp_sanity_check
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8109dc6c)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:__sysvec_error_interrupt
  - arch/x86/kernel/apic/apic.c:__sysvec_error_interrupt
  - arch/x86/kernel/apic/apic.c:handle_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:handle_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:__sysvec_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:__sysvec_apic_timer_interrupt
```
```
In arch/x86/kernel/apic/vector.c (ffffffff83e8e5b6)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/vector.c:free_moved_vector
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_deactivate
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
  - arch/x86/kernel/apic/vector.c:assign_vector_locked
  - arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked
  - arch/x86/kernel/apic/vector.c:apic_update_vector
  - arch/x86/kernel/apic/vector.c:apic_update_irq_cfg
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff810a78ff)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_one
```
```
In arch/x86/kernel/ftrace.c (ffffffff810aabb1)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/ftrace.c:prepare_ftrace_return
```
```
In arch/x86/kernel/kprobes/opt.c (ffffffff810b0bef)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In arch/x86/kernel/kprobes/ftrace.c (ffffffff810b1478)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
```
In arch/x86/kernel/kvmclock.c (ffffffff83e96d35)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/kernel/kvmclock.c:kvm_sched_clock_read
  - arch/x86/kernel/kvmclock.c:kvm_clock_get_cycles
  - arch/x86/kernel/kvmclock.c:kvm_get_wallclock
```
```
In arch/x86/kernel/paravirt.c (ffffffff810b88c5)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu
```
```
In arch/x86/kernel/callthunks.c (ffffffff810bebe9)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/callthunks.c:is_coretext
```
```
In arch/x86/mm/fault.c (ffffffff820bfae6)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:exc_page_fault
  - arch/x86/mm/fault.c:exc_page_fault
```
```
In arch/x86/mm/tlb.c (ffffffff810c98a5)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:arch_tlbbatch_flush
  - arch/x86/mm/tlb.c:flush_tlb_kernel_range
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
  - arch/x86/mm/tlb.c:native_flush_tlb_multi
  - arch/x86/mm/tlb.c:native_flush_tlb_multi
  - arch/x86/mm/tlb.c:flush_tlb_func
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/mm/kmmio.c (ffffffff810d25f4)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:kmmio_handler
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810d3305)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:post
  - arch/x86/mm/mmio-mod.c:post
  - arch/x86/mm/mmio-mod.c:pre
  - arch/x86/mm/mmio-mod.c:pre
  - arch/x86/mm/mmio-mod.c:pre
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff810d875e)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
```
```
In arch/x86/platform/uv/bios_uv.c (ffffffff810dadb4)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/platform/uv/bios_uv.c:__uv_bios_call
```
```
In kernel/fork.c (ffffffff810e8d70)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/fork.c:kernel_clone
  - kernel/fork.c:copy_process
```
```
In kernel/panic.c (ffffffff810e9f0e)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/panic.c:__warn_printk
  - kernel/panic.c:__warn
  - kernel/panic.c:panic
```
```
In kernel/cpu.c (ffffffff810ed676)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
  - kernel/cpu.c:__cpuhp_state_add_instance
  - kernel/cpu.c:thaw_secondary_cpus
  - kernel/cpu.c:thaw_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:cpuhp_kick_ap_work
  - kernel/cpu.c:cpuhp_kick_ap_work
  - kernel/cpu.c:cpus_read_trylock
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
```
```
In kernel/exit.c (ffffffff810f0da5)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:delayed_put_task_struct
```
```
In kernel/softirq.c (ffffffff810f39d0)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/softirq.c:__raise_softirq_irqoff
  - kernel/softirq.c:irq_enter
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
```
```
In kernel/signal.c (ffffffff811050e2)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:exit_signals
  - kernel/signal.c:exit_signals
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:__send_signal_locked
```
```
In kernel/workqueue.c (ffffffff81110efc)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_congested
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:pwq_activate_inactive_work
  - kernel/workqueue.c:wq_worker_running
```
```
In kernel/kthread.c (ffffffff8111da3c)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_stop
  - kernel/kthread.c:kthread_stop
  - kernel/kthread.c:kthread
  - kernel/kthread.c:__kthread_parkme
```
```
In kernel/smpboot.c (ffffffff81129446)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/smpboot.c:smpboot_thread_fn
```
```
In kernel/kmod.c (ffffffff8112b726)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
```
```
In kernel/sched/core.c (ffffffff811425a7)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/sched/core.c:call_trace_sched_update_nr_running
  - kernel/sched/core.c:migrate_task_to
  - kernel/sched/core.c:do_sched_yield
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:preempt_schedule_irq
  - kernel/sched/core.c:preempt_schedule_notrace
  - kernel/sched/core.c:preempt_schedule_common
  - kernel/sched/core.c:schedule_preempt_disabled
  - kernel/sched/core.c:schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:sched_core_balance
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:send_call_function_single_ipi
  - kernel/sched/core.c:ttwu_do_wakeup
  - kernel/sched/core.c:kick_process
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:migrate_swap
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:migrate_enable
  - kernel/sched/core.c:migrate_disable
  - kernel/sched/core.c:wake_up_nohz_cpu
  - kernel/sched/core.c:resched_curr
  - kernel/sched/core.c:raw_spin_rq_trylock
```
```
In kernel/sched/fair.c (ffffffff8114ce40)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:update_cpu_capacity
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:detach_entity_load_avg
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/build_policy.c (ffffffff81165a65)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:dl_cpu_busy
  - kernel/sched/build_policy.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/build_policy.c:sched_dl_do_global
  - kernel/sched/build_policy.c:sched_dl_global_validate
  - kernel/sched/build_policy.c:update_curr_dl
  - kernel/sched/build_policy.c:update_dl_rq_load_avg
  - kernel/sched/build_policy.c:update_rt_rq_load_avg
  - kernel/sched/build_policy.c:__update_load_avg_cfs_rq
  - kernel/sched/build_policy.c:__update_load_avg_se
  - kernel/sched/build_policy.c:__update_load_avg_blocked_se
  - kernel/sched/build_policy.c:update_curr_rt
  - kernel/sched/build_policy.c:play_idle_precise
  - kernel/sched/build_policy.c:default_idle_call
  - kernel/sched/build_policy.c:default_idle_call
```
```
In kernel/sched/build_utility.c (ffffffff8116e377)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:membarrier_private_expedited
  - kernel/sched/build_utility.c:membarrier_global_expedited
  - kernel/sched/build_utility.c:__update_stats_enqueue_sleeper
  - kernel/sched/build_utility.c:__update_stats_enqueue_sleeper
  - kernel/sched/build_utility.c:__update_stats_enqueue_sleeper
  - kernel/sched/build_utility.c:__update_stats_wait_end
  - kernel/sched/build_utility.c:sched_clock_cpu
  - kernel/sched/build_utility.c:__sched_clock_work
```
```
In kernel/locking/mutex.c (ffffffff820cec51)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In kernel/locking/semaphore.c (ffffffff820d0543)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/locking/semaphore.c:__down_common
  - kernel/locking/semaphore.c:__down_common
```
```
In kernel/locking/rwsem.c (ffffffff8117d465)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:up_write
  - kernel/locking/rwsem.c:up_read
  - kernel/locking/rwsem.c:down_write_trylock
  - kernel/locking/rwsem.c:down_write_killable
  - kernel/locking/rwsem.c:down_write
  - kernel/locking/rwsem.c:down_read_trylock
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read_interruptible
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
```
```
In kernel/locking/percpu-rwsem.c (ffffffff820d1946)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_down_write
  - kernel/locking/percpu-rwsem.c:percpu_down_write
  - kernel/locking/percpu-rwsem.c:__percpu_down_read
  - kernel/locking/percpu-rwsem.c:__percpu_down_read
  - kernel/locking/percpu-rwsem.c:__percpu_down_read
```
```
In kernel/locking/spinlock.c (ffffffff8117df37)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:__raw_write_lock_irqsave
  - kernel/locking/spinlock.c:__raw_read_lock_irqsave
  - kernel/locking/spinlock.c:_raw_write_trylock
  - kernel/locking/spinlock.c:_raw_read_trylock
  - kernel/locking/spinlock.c:_raw_write_lock_irq
  - kernel/locking/spinlock.c:_raw_read_lock_irq
  - kernel/locking/spinlock.c:_raw_write_lock_bh
  - kernel/locking/spinlock.c:_raw_read_lock_bh
  - kernel/locking/spinlock.c:_raw_write_lock_nested
  - kernel/locking/spinlock.c:_raw_write_lock
  - kernel/locking/spinlock.c:_raw_read_lock
  - kernel/locking/spinlock.c:__raw_spin_lock_irqsave
  - kernel/locking/spinlock.c:_raw_spin_trylock_bh
  - kernel/locking/spinlock.c:_raw_spin_trylock
  - kernel/locking/spinlock.c:_raw_spin_lock_irq
  - kernel/locking/spinlock.c:_raw_spin_lock_bh
  - kernel/locking/spinlock.c:_raw_spin_lock
```
```
In kernel/locking/qspinlock.c (ffffffff820d683a)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:native_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:native_queued_spin_lock_slowpath
```
```
In kernel/locking/rtmutex_api.c (ffffffff820d1af2)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:mark_wakeup_next_waiter
```
```
In kernel/locking/qrwlock.c (ffffffff820d6e2e)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/power/qos.c (ffffffff8117ecb5)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/power/qos.c:cpu_latency_qos_remove_request
  - kernel/power/qos.c:pm_qos_update_flags
  - kernel/power/qos.c:pm_qos_update_target
```
```
In kernel/power/process.c (ffffffff8118135f)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:thaw_processes
```
```
In kernel/power/suspend.c (ffffffff8118255d)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:s2idle_loop
  - kernel/power/suspend.c:s2idle_loop
```
```
In kernel/power/hibernate.c (ffffffff8118381f)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/power/hibernate.c:create_image
  - kernel/power/hibernate.c:create_image
```
```
In kernel/power/snapshot.c (0)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In kernel/printk/printk.c (ffffffff83eab067)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_init
  - kernel/printk/printk.c:console_init
  - kernel/printk/printk.c:console_init
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:printk_sprint
```
```
In kernel/irq/handle.c (ffffffff81195b5f)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/manage.c (ffffffff81196555)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_forced_thread_fn
```
```
In kernel/irq/chip.c (ffffffff8119c2a5)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi
  - kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_fasteoi_nmi
  - kernel/irq/chip.c:handle_fasteoi_nmi
```
```
In kernel/irq/matrix.c (ffffffff811a88bc)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_free
  - kernel/irq/matrix.c:irq_matrix_alloc
  - kernel/irq/matrix.c:irq_matrix_remove_reserved
  - kernel/irq/matrix.c:irq_matrix_reserve
  - kernel/irq/matrix.c:irq_matrix_assign
  - kernel/irq/matrix.c:irq_matrix_alloc_managed
  - kernel/irq/matrix.c:irq_matrix_remove_managed
  - kernel/irq/matrix.c:irq_matrix_reserve_managed
  - kernel/irq/matrix.c:irq_matrix_assign_system
  - kernel/irq/matrix.c:irq_matrix_offline
  - kernel/irq/matrix.c:irq_matrix_online
```
```
In kernel/rcu/update.c (ffffffff811a95da)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_invoke_cbs
```
```
In kernel/rcu/srcutree.c (ffffffff811aeb57)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
```
```
In kernel/rcu/tree.c (ffffffff811b8dbc)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_note_context_switch
  - kernel/rcu/tree.c:rcu_note_context_switch
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:__sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:print_cpu_stall
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_do_batch
```
```
In kernel/livepatch/core.c (ffffffff811bd13a)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_init_object
```
```
In kernel/livepatch/patch.c (ffffffff811bddce)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_ftrace_handler
```
```
In kernel/livepatch/transition.c (ffffffff811bf4c5)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_update_patch_state
```
```
In kernel/dma/swiotlb.c (ffffffff811c5545)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_map
```
```
In kernel/entry/common.c (ffffffff811c672e)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/entry/common.c:syscall_exit_work
  - kernel/entry/common.c:irqentry_nmi_enter
```
```
In kernel/module/main.c (ffffffff811cd891)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/module/main.c:print_modules
  - kernel/module/main.c:is_module_text_address
  - kernel/module/main.c:is_module_address
  - kernel/module/main.c:search_module_extables
  - kernel/module/main.c:load_module
  - kernel/module/main.c:__symbol_get
  - kernel/module/main.c:free_module
  - kernel/module/main.c:module_put
  - kernel/module/main.c:module_put
  - kernel/module/main.c:try_module_get
  - kernel/module/main.c:try_module_get
  - kernel/module/main.c:symbol_put_addr
  - kernel/module/main.c:__symbol_put
  - kernel/module/main.c:__is_module_percpu_address
```
```
In kernel/module/kallsyms.c (ffffffff811cf452)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/module/kallsyms.c:module_kallsyms_on_each_symbol
  - kernel/module/kallsyms.c:module_kallsyms_lookup_name
  - kernel/module/kallsyms.c:module_get_kallsym
  - kernel/module/kallsyms.c:lookup_module_symbol_attrs
  - kernel/module/kallsyms.c:lookup_module_symbol_name
  - kernel/module/kallsyms.c:module_address_lookup
```
```
In kernel/module/version.c (ffffffff811d07e9)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/module/version.c:check_modstruct_version
```
```
In kernel/profile.c (ffffffff811d2199)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/profile.c:profile_discard_flip_buffers
  - kernel/profile.c:profile_flip_buffers
```
```
In kernel/time/timer.c (ffffffff811d8968)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:__run_timers
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:detach_if_pending
  - kernel/time/timer.c:enqueue_timer
```
```
In kernel/time/hrtimer.c (ffffffff811dae8b)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_nanosleep_restart
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_init
  - kernel/time/hrtimer.c:hrtimer_try_to_cancel
  - kernel/time/hrtimer.c:__hrtimer_start_range_ns
  - kernel/time/hrtimer.c:enqueue_hrtimer
  - kernel/time/hrtimer.c:clock_was_set
```
```
In kernel/time/timekeeping.c (0)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In kernel/time/clocksource.c (ffffffff811e0c13)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In kernel/time/alarmtimer.c (ffffffff811e3749)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_try_to_cancel
  - kernel/time/alarmtimer.c:alarm_start
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - kernel/time/alarmtimer.c:alarmtimer_fired
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811e89b5)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:check_cpu_itimer
```
```
In kernel/time/itimer.c (ffffffff811ec072)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:it_real_fn
```
```
In kernel/time/tick-common.c (ffffffff811ee7d4)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_unfreeze
  - kernel/time/tick-common.c:tick_freeze
```
```
In kernel/time/tick-sched.c (ffffffff811f0c64)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_stop_tick
```
```
In kernel/smp.c (ffffffff811f8f0c)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/smp.c:wake_up_all_idle_cpus
  - kernel/smp.c:kick_all_cpus_sync
  - kernel/smp.c:on_each_cpu_cond_mask
  - kernel/smp.c:smp_call_function_any
  - kernel/smp.c:smp_call_function_single_async
  - kernel/smp.c:smp_call_function_single
```
```
In kernel/acct.c (ffffffff811fd471)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
  - kernel/acct.c:do_acct_process
```
```
In kernel/cgroup/cgroup.c (ffffffff812104e8)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_rmdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:cgroup_destroy_root
  - kernel/cgroup/cgroup.c:cgroup_update_populated
```
```
In kernel/cgroup/rstat.c (ffffffff81211b35)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:__cgroup_account_cputime_field
  - kernel/cgroup/rstat.c:__cgroup_account_cputime
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81214826)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
```
In kernel/cgroup/freezer.c (ffffffff812153d9)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_propagate_frozen
  - kernel/cgroup/freezer.c:cgroup_propagate_frozen
```
```
In kernel/cgroup/cpuset.c (ffffffff8121e5d5)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_read_unlock
  - kernel/cgroup/cpuset.c:cpuset_read_lock
```
```
In kernel/stop_machine.c (ffffffff81223386)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
  - kernel/stop_machine.c:cpu_stop_queue_two_works
  - kernel/stop_machine.c:cpu_stop_queue_work
```
```
In kernel/kprobes.c (ffffffff81235c2f)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/kprobes.c:show_kprobe_addr
  - kernel/kprobes.c:check_kprobe_address_safe
  - kernel/kprobes.c:kprobe_busy_begin
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81244211)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/hung_task.c (ffffffff81246e0c)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/hung_task.c:check_hung_task
```
```
In kernel/relay.c (ffffffff8124c850)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/relay.c:relay_late_setup_files
```
```
In kernel/trace/trace_clock.c (ffffffff81250cb0)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_local
```
```
In kernel/trace/ftrace.c (ffffffff812523aa)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:fnpid_start
  - kernel/trace/ftrace.c:fpid_start
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:arch_ftrace_ops_list_func
  - kernel/trace/ftrace.c:ftrace_mod_get_kallsym
  - kernel/trace/ftrace.c:ftrace_mod_address_lookup
  - kernel/trace/ftrace.c:function_trace_probe_call
  - kernel/trace/ftrace.c:ftrace_ops_trampoline
```
```
In kernel/trace/ring_buffer.c (ffffffff8126124b)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_consume
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_nest_start
  - kernel/trace/ring_buffer.c:ring_buffer_time_stamp
```
```
In kernel/trace/trace.c (ffffffff81268c93)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_write
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_read
  - kernel/trace/trace.c:saved_cmdlines_start
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_buffered_event_enable
  - kernel/trace/trace.c:trace_find_cmdline
  - kernel/trace/trace.c:ftrace_exports
```
```
In kernel/trace/trace_functions.c (ffffffff81279f73)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8127b93c)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
  - kernel/trace/trace_sched_wakeup.c:func_prolog_preempt_disable
```
```
In kernel/trace/trace_stack.c (ffffffff8127d9a0)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:stack_trace_call
```
```
In kernel/trace/trace_mmiotrace.c (ffffffff8127e687)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
```
```
In kernel/trace/trace_functions_graph.c (ffffffff8127f30c)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/blktrace.c (ffffffff81283594)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/blktrace.c:trace_note
```
```
In kernel/trace/trace_events.c (ffffffff812879aa)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:np_start
  - kernel/trace/trace_events.c:p_start
```
```
In kernel/trace/trace_event_perf.c (ffffffff8128c9a9)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_ftrace_function_call
```
```
In kernel/trace/trace_events_inject.c (ffffffff812959bd)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/trace/trace_events_inject.c:trace_inject_entry
```
```
In kernel/trace/bpf_trace.c (ffffffff812a9da0)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_put_raw_tracepoint
  - kernel/trace/bpf_trace.c:bpf_trace_vprintk
  - kernel/trace/bpf_trace.c:bpf_trace_printk
```
```
In kernel/trace/trace_kprobe.c (ffffffff812abecc)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:append_trace_kprobe
```
```
In kernel/trace/trace_uprobe.c (ffffffff812b8080)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:__uprobe_perf_func
```
```
In kernel/trace/fprobe.c (ffffffff812ba81d)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In kernel/trace/rethook.c (ffffffff812bb58a)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/trace/rethook.c:rethook_trampoline_handler
  - kernel/trace/rethook.c:rethook_flush_task
```
```
In kernel/trace/rv/monitors/wwnr/wwnr.c (ffffffff812bd083)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/trace/rv/monitors/wwnr/wwnr.c:da_event_wwnr
  - kernel/trace/rv/monitors/wwnr/wwnr.c:da_event_wwnr
```
```
In kernel/irq_work.c (ffffffff812be34a)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_queue_on
```
```
In kernel/bpf/core.c (ffffffff812c3c95)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_user_rnd_u32
```
```
In kernel/bpf/helpers.c (ffffffff812f3111)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_bprintf_prepare
  - kernel/bpf/helpers.c:copy_map_value_locked
```
```
In kernel/bpf/hashtab.c (ffffffff812fbd63)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_elem
  - kernel/bpf/hashtab.c:htab_lru_map_delete_elem
  - kernel/bpf/hashtab.c:htab_map_delete_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_delete_node
```
```
In kernel/bpf/trampoline.c (ffffffff81309166)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_update
```
```
In kernel/bpf/devmap.c (ffffffff8131edaa)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_generic_redirect
  - kernel/bpf/devmap.c:bq_xmit_all
  - kernel/bpf/devmap.c:dev_map_bpf_prog_run
```
```
In kernel/bpf/cpumap.c (ffffffff81320ad3)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_generic_redirect
  - kernel/bpf/cpumap.c:bq_flush_to_queue
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_skb
```
```
In kernel/bpf/offload.c (ffffffff813216a4)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In kernel/static_call_inline.c (ffffffff81333988)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/static_call_inline.c:static_call_text_reserved
```
```
In kernel/events/core.c (ffffffff81342ae5)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_cgroup_move
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_pending_task
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:perf_event_read
```
```
In kernel/events/ring_buffer.c (ffffffff8134b3c9)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
```
```
In kernel/events/hw_breakpoint.c (ffffffff8134cd92)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff81351e95)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_end_dup_mmap
  - kernel/events/uprobes.c:uprobe_start_dup_mmap
  - kernel/events/uprobes.c:__update_ref_ctr
  - kernel/events/uprobes.c:copy_to_page
  - kernel/events/uprobes.c:copy_from_page
```
```
In kernel/user-return-notifier.c (ffffffff81353235)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/user-return-notifier.c:fire_user_return_notifiers
```
```
In kernel/padata.c (ffffffff81353892)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:invoke_padata_reorder
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_parallel_worker
```
```
In kernel/jump_label.c (ffffffff81354e0d)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_update
  - kernel/jump_label.c:jump_label_text_reserved
  - kernel/jump_label.c:jump_label_add_module
```
```
In kernel/rseq.c (ffffffff81357031)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/rseq.c:__rseq_handle_notify_resume
  - kernel/rseq.c:rseq_ip_fixup
  - kernel/rseq.c:rseq_ip_fixup
```
```
In kernel/watch_queue.c (ffffffff81357341)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In mm/filemap.c (ffffffff8135cbe0)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:file_check_and_advance_wb_err
  - mm/filemap.c:__filemap_set_wb_err
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__filemap_remove_folio
```
```
In mm/oom_kill.c (ffffffff813632a3)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - mm/oom_kill.c:mark_oom_victim
  - mm/oom_kill.c:wake_oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
```
```
In mm/page-writeback.c (ffffffff81366e47)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - mm/page-writeback.c:folio_wait_writeback_killable
  - mm/page-writeback.c:folio_wait_writeback
  - mm/page-writeback.c:folio_account_dirtied
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:balance_dirty_pages_ratelimited_flags
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:wb_update_dirty_ratelimit
  - mm/page-writeback.c:domain_dirty_limits
```
```
In mm/swap.c (ffffffff81370d60)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_release
  - mm/swap.c:lru_add_drain_per_cpu
  - mm/swap.c:lru_add_drain_cpu_zone
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:deactivate_file_folio
  - mm/swap.c:folio_add_lru
  - mm/swap.c:folio_mark_accessed
  - mm/swap.c:lru_add_fn
```
```
In mm/vmscan.c (ffffffff81386088)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - mm/vmscan.c:__node_reclaim
  - mm/vmscan.c:__node_reclaim
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:mem_cgroup_shrink_node
  - mm/vmscan.c:mem_cgroup_shrink_node
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:isolate_lru_folios
  - mm/vmscan.c:pageout
  - mm/vmscan.c:reclaim_throttle
  - mm/vmscan.c:do_shrink_slab
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/shmem.c (ffffffff81389b66)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In mm/util.c (ffffffff81392035)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - mm/util.c:memcmp_pages
  - mm/util.c:memcmp_pages
```
```
In mm/backing-dev.c (ffffffff81398f1e)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_register_va
```
```
In mm/percpu.c (ffffffff8139bdfd)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_free
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
```
```
In mm/slab_common.c (ffffffff813a1a7d)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_large_node
  - mm/slab_common.c:kmalloc_large
  - mm/slab_common.c:kmalloc_node_trace
  - mm/slab_common.c:kmalloc_trace
  - mm/slab_common.c:kfree
  - mm/slab_common.c:__kmalloc_node_track_caller
  - mm/slab_common.c:__kmalloc_node_track_caller
  - mm/slab_common.c:__kmalloc
  - mm/slab_common.c:__kmalloc
  - mm/slab_common.c:__kmalloc_node
  - mm/slab_common.c:__kmalloc_node
```
```
In mm/compaction.c (ffffffff813a9cbd)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
  - mm/compaction.c:wakeup_kcompactd
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compaction_suitable
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:compaction_defer_reset
  - mm/compaction.c:compaction_deferred
  - mm/compaction.c:defer_compaction
```
```
In mm/mmap_lock.c (ffffffff813b40d5)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - mm/mmap_lock.c:__mmap_lock_do_trace_released
  - mm/mmap_lock.c:__mmap_lock_do_trace_released
  - mm/mmap_lock.c:__mmap_lock_do_trace_acquire_returned
  - mm/mmap_lock.c:__mmap_lock_do_trace_acquire_returned
  - mm/mmap_lock.c:__mmap_lock_do_trace_start_locking
  - mm/mmap_lock.c:__mmap_lock_do_trace_start_locking
```
```
In mm/memory.c (ffffffff813c0f9b)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:do_set_pte
  - mm/memory.c:wp_page_copy
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mlock.c (ffffffff813c4fc5)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - mm/mlock.c:munlock_page
  - mm/mlock.c:mlock_new_page
  - mm/mlock.c:mlock_folio
  - mm/mlock.c:mlock_page_drain_local
```
```
In mm/mmap.c (ffffffff813ca0bc)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:vm_unmapped_area
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:vma_mas_remove
  - mm/mmap.c:vma_mas_store
```
```
In mm/rmap.c (ffffffff813d9b54)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff813dc6b5)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:alloc_vmap_area
```
```
In mm/page_alloc.c (ffffffff813eca1d)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:free_unref_page
  - mm/page_alloc.c:rmqueue_bulk
  - mm/page_alloc.c:rmqueue_bulk
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/memory_hotplug.c (ffffffff813f11e2)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
```
```
In mm/swapfile.c (ffffffff813fbecd)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:swp_swapcount
```
```
In mm/zswap.c (ffffffff814033cc)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/hugetlb.c (0)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In mm/mempolicy.c (ffffffff81414ce0)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_page_interleave
```
```
In mm/ksm.c (ffffffff8141db55)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - mm/ksm.c:calc_checksum
```
```
In mm/page_poison.c (ffffffff81423571)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - mm/page_poison.c:__kernel_unpoison_pages
  - mm/page_poison.c:__kernel_poison_pages
```
```
In mm/slub.c (ffffffff8142c984)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:__kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_lru
  - mm/slub.c:kmem_cache_alloc_lru
  - mm/slub.c:kmem_cache_alloc
  - mm/slub.c:kmem_cache_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:__unfreeze_partials
```
```
In mm/kfence/core.c (ffffffff8142efbd)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_protect_page
```
```
In mm/kfence/report.c (ffffffff81430ffd)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - mm/kfence/report.c:kfence_report_error
```
```
In mm/migrate.c (ffffffff81435707)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff814440ee)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:mm_get_huge_zero_page
```
```
In mm/khugepaged.c (ffffffff8144ab19)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:hpage_collapse_scan_pmd
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (ffffffff8145a4d4)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_flush_foreign
  - mm/memcontrol.c:mem_cgroup_track_foreign_dirty_slowpath
```
```
In mm/memory-failure.c (ffffffff8145e825)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure_queue
  - mm/memory-failure.c:action_result
```
```
In mm/page_isolation.c (ffffffff8146584b)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
```
```
In mm/zsmalloc.c (ffffffff8146824c)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - mm/zsmalloc.c:restore_freelist
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:find_tagged_obj
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:obj_free
  - mm/zsmalloc.c:obj_malloc
  - mm/zsmalloc.c:zs_map_object
  - mm/zsmalloc.c:zs_map_object
  - mm/zsmalloc.c:__zs_map_object
  - mm/zsmalloc.c:__zs_map_object
  - mm/zsmalloc.c:alloc_zspage
```
```
In fs/open.c (ffffffff8147471e)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
  - fs/open.c:vfs_fallocate
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:do_sys_ftruncate
```
```
In fs/read_write.c (ffffffff8147bdc7)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_write
  - fs/read_write.c:vfs_write
```
```
In fs/exec.c (ffffffff81484192)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/exec.c:exec_binprm
  - fs/exec.c:__set_task_comm
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
```
```
In fs/pipe.c (ffffffff8148796d)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
```
```
In fs/dcache.c (ffffffff8149e44c)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_unhash
  - fs/dcache.c:__d_lookup_unhash
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
```
```
In fs/inode.c (ffffffff814a5017)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/inode.c:touch_atime
  - fs/inode.c:touch_atime
  - fs/inode.c:get_next_ino
```
```
In fs/file.c (ffffffff814a66f7)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/file.c:fd_install
```
```
In fs/namespace.c (ffffffff814aae39)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write
  - fs/namespace.c:mnt_drop_write
  - fs/namespace.c:mnt_want_write
  - fs/namespace.c:mnt_want_write
  - fs/namespace.c:__mnt_want_write
```
```
In fs/fs-writeback.c (ffffffff814c1801)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_do_writeback
  - fs/fs-writeback.c:wb_writeback
  - fs/fs-writeback.c:wb_writeback
  - fs/fs-writeback.c:wb_writeback
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fs-writeback.c:write_inode
  - fs/fs-writeback.c:write_inode
  - fs/fs-writeback.c:queue_io
  - fs/fs-writeback.c:sb_clear_inode_writeback
  - fs/fs-writeback.c:sb_mark_inode_writeback
  - fs/fs-writeback.c:wb_start_background_writeback
  - fs/fs-writeback.c:wbc_detach_inode
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:wb_queue_work
```
```
In fs/splice.c (ffffffff814c75d6)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
```
```
In fs/fs_struct.c (0)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In fs/remap_range.c (ffffffff814d1307)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_clone_file_range
  - fs/remap_range.c:vfs_clone_file_range
```
```
In fs/buffer.c (ffffffff814d1fb5)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/buffer.c:free_buffer_head
  - fs/buffer.c:alloc_buffer_head
  - fs/buffer.c:invalidate_bh_lru
  - fs/buffer.c:mark_buffer_dirty
```
```
In fs/userfaultfd.c (0)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In fs/aio.c (ffffffff814f539f)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_write
  - fs/aio.c:aio_complete_rw
  - fs/aio.c:aio_read_events_ring
  - fs/aio.c:aio_read_events_ring
  - fs/aio.c:aio_complete
  - fs/aio.c:aio_complete
  - fs/aio.c:ioctx_add_table
  - fs/aio.c:aio_setup_ring
```
```
In fs/dax.c (ffffffff814fa6db)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pte_fault
  - fs/dax.c:dax_iomap_pte_fault
  - fs/dax.c:dax_fault_iter
  - fs/dax.c:dax_fault_cow_page
  - fs/dax.c:dax_pmd_load_hole
  - fs/dax.c:dax_pmd_load_hole
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_one
```
```
In fs/locks.c (ffffffff8150e001)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/locks.c:locks_remove_file
  - fs/locks.c:locks_remove_file
  - fs/locks.c:locks_remove_posix
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:generic_setlease
  - fs/locks.c:generic_setlease
  - fs/locks.c:generic_setlease
  - fs/locks.c:generic_add_lease
  - fs/locks.c:generic_add_lease
  - fs/locks.c:generic_add_lease
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:leases_conflict
  - fs/locks.c:time_out_leases
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:locks_get_lock_context
```
```
In fs/mbcache.c (ffffffff81514f5b)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:__mb_cache_entry_free
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/coredump.c (ffffffff81519758)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
```
```
In fs/iomap/iter.c (ffffffff8151b9c3)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/iomap/iter.c:iomap_iter
  - fs/iomap/iter.c:iomap_iter_done
  - fs/iomap/iter.c:iomap_iter_done
```
```
In fs/iomap/buffered-io.c (ffffffff8151e01f)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_do_writepage
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/iomap/buffered-io.c:iomap_invalidate_folio
  - fs/iomap/buffered-io.c:iomap_release_folio
  - fs/iomap/buffered-io.c:iomap_readahead
  - fs/iomap/buffered-io.c:iomap_read_folio
```
```
In fs/iomap/direct-io.c (ffffffff81520dd9)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:__iomap_dio_rw
```
```
In fs/proc/base.c (ffffffff81536658)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In fs/ext4/balloc.c (ffffffff81558227)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ext4_jbd2.c (ffffffff8155b181)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb
```
```
In fs/ext4/extents.c (ffffffff815624f0)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/extents_status.c (ffffffff815695fd)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_insert_delayed_block
  - fs/ext4/extents_status.c:ext4_es_scan
  - fs/ext4/extents_status.c:ext4_es_scan
  - fs/ext4/extents_status.c:ext4_es_count
  - fs/ext4/extents_status.c:__es_shrink
  - fs/ext4/extents_status.c:ext4_es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_cache_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_find_extent_range
  - fs/ext4/extents_status.c:ext4_es_find_extent_range
```
```
In fs/ext4/file.c (ffffffff8156997c)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_sample_last_mounted
  - fs/ext4/file.c:ext4_sample_last_mounted
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/fsmap.c (ffffffff8156c2f1)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/fsmap.c:ext4_getfsmap_logdev
  - fs/ext4/fsmap.c:ext4_getfsmap_logdev
  - fs/ext4/fsmap.c:ext4_getfsmap_helper
  - fs/ext4/fsmap.c:ext4_getfsmap_helper
```
```
In fs/ext4/fsync.c (ffffffff8156c928)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/ialloc.c (ffffffff8156f70d)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff8157271a)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inline.c (ffffffff815767e1)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff81585cf2)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_update_other_inode_time
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_release_folio
  - fs/ext4/inode.c:__ext4_journalled_invalidate_folio
  - fs/ext4/inode.c:ext4_invalidate_folio
  - fs/ext4/inode.c:ext4_read_folio
  - fs/ext4/inode.c:ext4_alloc_da_blocks
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_do_writepages
  - fs/ext4/inode.c:ext4_do_writepages
  - fs/ext4/inode.c:ext4_do_writepages
  - fs/ext4/inode.c:mpage_map_one_extent
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_da_reserve_space
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (ffffffff81587159)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioc_getfsmap
  - fs/ext4/ioctl.c:ext4_ioc_getfsmap
  - fs/ext4/ioctl.c:ext4_getfsmap_format
  - fs/ext4/ioctl.c:ext4_shutdown
  - fs/ext4/ioctl.c:ext4_update_backup_sb
  - fs/ext4/ioctl.c:ext4_update_primary_sb
```
```
In fs/ext4/mballoc.c (ffffffff81590ee4)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_preallocations_should_retry
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_collect_stats
  - fs/ext4/mballoc.c:ext4_mb_collect_stats
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/mmp.c (ffffffff81598240)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/namei.c (ffffffff815a2d20)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_unlink
  - fs/ext4/namei.c:ext4_unlink
```
```
In fs/ext4/super.c (ffffffff815c073c)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:ext4_run_li_request
  - fs/ext4/super.c:ext4_run_li_request
  - fs/ext4/super.c:ext4_nfs_commit_metadata
  - fs/ext4/super.c:ext4_drop_inode
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
```
```
In fs/ext4/fast_commit.c (ffffffff815d7afb)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
  - fs/ext4/fast_commit.c:ext4_fc_commit
  - fs/ext4/fast_commit.c:ext4_fc_update_stats
  - fs/ext4/fast_commit.c:ext4_fc_track_range
  - fs/ext4/fast_commit.c:ext4_fc_track_inode
  - fs/ext4/fast_commit.c:__ext4_fc_track_create
  - fs/ext4/fast_commit.c:__ext4_fc_track_link
  - fs/ext4/fast_commit.c:__ext4_fc_track_unlink
```
```
In fs/jbd2/transaction.c (ffffffff815dd26c)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:jbd2_freeze_jh_data
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
  - fs/jbd2/transaction.c:jbd2__journal_start
```
```
In fs/jbd2/commit.c (ffffffff815dffab)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_data_buffers
```
```
In fs/jbd2/checkpoint.c (ffffffff815e26d0)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_drop_transaction
  - fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_journal_shrink_checkpoint_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff815ebf34)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_journal_shrink_count
  - fs/jbd2/journal.c:jbd2_journal_shrink_scan
  - fs/jbd2/journal.c:jbd2_journal_shrink_scan
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/squashfs/file.c (ffffffff815ef54a)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_read_folio
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (ffffffff815f1970)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_read_folio
```
```
In fs/squashfs/decompressor_multi_percpu.c (ffffffff815f2e76)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/squashfs/decompressor_multi_percpu.c:squashfs_decompress
```
```
In fs/ecryptfs/mmap.c (ffffffff8160c4a6)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
```
In fs/ecryptfs/read_write.c (ffffffff8160d5da)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dax.c (ffffffff8163133b)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/fuse/dax.c:__fuse_dax_fault
  - fs/fuse/dax.c:__fuse_dax_fault
```
```
In ipc/util.c (ffffffff8163c547)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In security/selinux/avc.c (ffffffff8166bb6a)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_audit_post_callback
```
```
In security/smack/smack_lsm.c (ffffffff8169f55f)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smk_ipv4_check
  - security/smack/smack_lsm.c:smack_netlbl_add
```
```
In security/tomoyo/domain.c (ffffffff816b1882)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In security/apparmor/capability.c (ffffffff816c2093)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - security/apparmor/capability.c:audit_caps
```
```
In security/apparmor/policy_unpack.c (ffffffff816d1199)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In security/apparmor/lsm.c (ffffffff816dae98)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - security/apparmor/lsm.c:aa_put_buffer
  - security/apparmor/lsm.c:aa_put_buffer
  - security/apparmor/lsm.c:aa_put_buffer
  - security/apparmor/lsm.c:aa_get_buffer
  - security/apparmor/lsm.c:aa_get_buffer
  - security/apparmor/lsm.c:aa_get_buffer
```
```
In crypto/scatterwalk.c (ffffffff81707b8d)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/skcipher.c (0)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In crypto/ahash.c (ffffffff8170abf6)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - crypto/ahash.c:hash_walk_next
```
```
In crypto/shash.c (ffffffff8170d063)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_digest
```
```
In block/bio.c (ffffffff8172e155)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - block/bio.c:bio_endio
  - block/bio.c:bio_put_percpu_cache
  - block/bio.c:bio_alloc_bioset
```
```
In block/blk-core.c (ffffffff8173605c)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - block/blk-core.c:bdev_end_io_acct
  - block/blk-core.c:bdev_start_io_acct
  - block/blk-core.c:submit_bio_noacct
  - block/blk-core.c:submit_bio_noacct_nocheck
```
```
In block/blk-flush.c (ffffffff817389bc)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-merge.c (ffffffff8173e90f)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_front_merge
  - block/blk-merge.c:bio_attempt_back_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:__bio_split_to_limits
```
```
In block/blk-mq.c (ffffffff81746428)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - block/blk-mq.c:blk_insert_cloned_request
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:blk_mq_commit_rqs
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:__blk_mq_insert_request
  - block/blk-mq.c:blk_execute_rq
  - block/blk-mq.c:blk_execute_rq_nowait
  - block/blk-mq.c:blk_add_rq_to_plug
  - block/blk-mq.c:blk_add_rq_to_plug
  - block/blk-mq.c:blk_mq_start_request
  - block/blk-mq.c:blk_mq_complete_request_remote
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:__blk_account_io_done
  - block/blk-mq.c:blk_update_request
  - block/blk-mq.c:blk_update_request
```
```
In block/blk-stat.c (ffffffff8174c6bb)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_add
```
```
In block/genhd.c (ffffffff817518e3)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - block/genhd.c:diskstats_show
  - block/genhd.c:part_stat_show
```
```
In block/blk-cgroup.c (ffffffff81763b33)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - block/blk-cgroup.c:blk_cgroup_bio_start
```
```
In block/blk-iocost.c (ffffffff81771843)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:adjust_inuse_and_calc_cost
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_forgive_debts
  - block/blk-iocost.c:transfer_surpluses
  - block/blk-iocost.c:iocg_wake_fn
  - block/blk-iocost.c:iocg_incur_debt
  - block/blk-iocost.c:iocg_activate
```
```
In block/mq-deadline.c (ffffffff81773ee1)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In block/blk-wbt.c (ffffffff8177b10b)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:rwb_trace_step
```
```
In io_uring/io_uring.c (ffffffff8178c89d)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - io_uring/io_uring.c:__ia32_sys_io_uring_register
  - io_uring/io_uring.c:__x64_sys_io_uring_register
  - io_uring/io_uring.c:io_uring_create
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/io_uring.c:io_submit_sqes
  - io_uring/io_uring.c:io_submit_sqes
  - io_uring/io_uring.c:io_submit_fail_init
  - io_uring/io_uring.c:io_file_get_normal
  - io_uring/io_uring.c:io_drain_req
  - io_uring/io_uring.c:__io_run_local_work
  - io_uring/io_uring.c:tctx_task_work
  - io_uring/io_uring.c:io_fill_cqe_aux
  - io_uring/io_uring.c:io_cqring_event_overflow
  - io_uring/io_uring.c:io_queue_iowq
  - io_uring/io_uring.c:__io_fill_cqe_req
```
```
In io_uring/timeout.c (ffffffff817995a8)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - io_uring/timeout.c:io_disarm_next
```
```
In io_uring/poll.c (ffffffff8179db3f)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - io_uring/poll.c:io_arm_poll_handler
  - io_uring/poll.c:__io_poll_execute
```
```
In io_uring/rw.c (ffffffff817a4b6b)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - io_uring/rw.c:io_write
  - io_uring/rw.c:io_write
  - io_uring/rw.c:__io_fill_cqe_req
```
```
In io_uring/io-wq.c (ffffffff817a7418)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wqe_worker
```
```
In lib/scatterlist.c (ffffffff817cf653)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In lib/iov_iter.c (ffffffff817d54b9)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - lib/iov_iter.c:copy_page_from_iter_atomic
```
```
In lib/rhashtable.c (ffffffff817da301)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In lib/percpu_counter.c (ffffffff8188bb30)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - lib/percpu_counter.c:percpu_counter_add_batch
```
```
In lib/irq_poll.c (ffffffff8189e9d0)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_cpu_dead
```
```
In arch/x86/lib/msr-smp.c (ffffffff818a5ac6)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:wrmsr_on_cpus
  - arch/x86/lib/msr-smp.c:rdmsr_on_cpus
```
```
In arch/x86/lib/msr.c (ffffffff818a6559)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:do_trace_rdpmc
  - arch/x86/lib/msr.c:do_trace_read_msr
  - arch/x86/lib/msr.c:do_trace_write_msr
```
```
In drivers/gpio/gpiolib.c (ffffffff818bff3f)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_source_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_drain_value_commit
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_input
```
```
In drivers/pwm/core.c (ffffffff818cf977)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwm_apply_state
  - drivers/pwm/core.c:pwm_device_request
```
```
In drivers/pci/pcie/aer.c (ffffffff818fcc79)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:cper_print_aer
  - drivers/pci/pcie/aer.c:aer_print_error
```
```
In drivers/acpi/sleep.c (ffffffff81958b14)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_suspend_enter
  - drivers/acpi/sleep.c:acpi_suspend_enter
```
```
In drivers/acpi/prmt.c (ffffffff81979f0b)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/acpi/prmt.c:acpi_platformrt_space_handler
```
```
In drivers/clk/clk.c (ffffffff819f8e4f)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_set_duty_cycle_nolock
  - drivers/clk/clk.c:clk_core_set_duty_cycle_nolock
  - drivers/clk/clk.c:clk_core_set_phase_nolock
  - drivers/clk/clk.c:clk_core_set_phase_nolock
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_calc_new_rates
  - drivers/clk/clk.c:clk_calc_new_rates
  - drivers/clk/clk.c:clk_round_rate
  - drivers/clk/clk.c:clk_round_rate
  - drivers/clk/clk.c:clk_hw_round_rate
  - drivers/clk/clk.c:clk_hw_round_rate
  - drivers/clk/clk.c:clk_core_round_rate_nolock
  - drivers/clk/clk.c:clk_core_round_rate_nolock
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_unprepare_unused_subtree
  - drivers/clk/clk.c:clk_unprepare_unused_subtree
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/clk/clk.c:clk_core_prepare
  - drivers/clk/clk.c:clk_core_prepare
  - drivers/clk/clk.c:clk_core_unprepare
  - drivers/clk/clk.c:clk_core_unprepare
  - drivers/clk/clk.c:clk_mux_determine_rate_flags
  - drivers/clk/clk.c:clk_mux_determine_rate_flags
  - drivers/clk/clk.c:clk_mux_determine_rate_flags
  - drivers/clk/clk.c:clk_mux_determine_rate_flags
```
```
In drivers/xen/events/events_2l.c (ffffffff81a2299a)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81a31096)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
```
```
In drivers/regulator/core.c (ffffffff81a3b38f)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
```
```
In drivers/char/random.c (ffffffff81a94e8f)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/char/random.c:try_to_generate_entropy
```
```
In drivers/char/virtio_console.c (ffffffff81a96358)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/iommu/intel/dmar.c (ffffffff81abe397)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:qi_submit_sync
```
```
In drivers/iommu/intel/svm.c (ffffffff81aca18c)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:prq_event_thread
```
```
In drivers/iommu/iommu.c (ffffffff81acf28e)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:report_iommu_fault
  - drivers/iommu/iommu.c:__iommu_unmap
  - drivers/iommu/iommu.c:__iommu_map
  - drivers/iommu/iommu.c:iommu_group_do_detach_device
  - drivers/iommu/iommu.c:iommu_group_remove_device
  - drivers/iommu/iommu.c:iommu_group_add_device
```
```
In drivers/connector/cn_proc.c (ffffffff81addee1)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/connector/cn_proc.c:proc_exit_connector
  - drivers/connector/cn_proc.c:proc_coredump_connector
  - drivers/connector/cn_proc.c:proc_comm_connector
  - drivers/connector/cn_proc.c:proc_ptrace_connector
  - drivers/connector/cn_proc.c:proc_sid_connector
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/connector/cn_proc.c:proc_exec_connector
  - drivers/connector/cn_proc.c:proc_fork_connector
```
```
In drivers/base/syscore.c (ffffffff81aebea6)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
```
```
In drivers/base/devres.c (ffffffff81af1c43)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/base/devres.c:__devm_alloc_percpu
  - drivers/base/devres.c:devm_krealloc
  - drivers/base/devres.c:devm_add_action
  - drivers/base/devres.c:devres_remove_group
  - drivers/base/devres.c:devres_close_group
  - drivers/base/devres.c:devres_open_group
  - drivers/base/devres.c:release_nodes
  - drivers/base/devres.c:devres_remove
  - drivers/base/devres.c:devres_get
```
```
In drivers/base/power/qos.c (ffffffff81afe511)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/base/power/qos.c:__dev_pm_qos_remove_request
  - drivers/base/power/qos.c:__dev_pm_qos_update_request
  - drivers/base/power/qos.c:__dev_pm_qos_add_request
```
```
In drivers/base/power/runtime.c (ffffffff81b01ab0)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:update_autosuspend
  - drivers/base/power/runtime.c:pm_runtime_allow
  - drivers/base/power/runtime.c:pm_runtime_get_if_active
  - drivers/base/power/runtime.c:__pm_runtime_suspend
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
```
```
In drivers/base/power/main.c (ffffffff81b07562)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/base/power/main.c:dpm_run_callback
  - drivers/base/power/main.c:dpm_run_callback
```
```
In drivers/base/power/wakeup.c (ffffffff81b087f7)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_activate
```
```
In drivers/base/regmap/regmap.c (ffffffff81b1a9ec)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_async_complete_cb
  - drivers/base/regmap/regmap.c:regmap_bulk_read
  - drivers/base/regmap/regmap.c:_regmap_read
  - drivers/base/regmap/regmap.c:_regmap_raw_read
  - drivers/base/regmap/regmap.c:_regmap_raw_read
  - drivers/base/regmap/regmap.c:_regmap_raw_multi_reg_write
  - drivers/base/regmap/regmap.c:_regmap_raw_multi_reg_write
  - drivers/base/regmap/regmap.c:regmap_bulk_write
  - drivers/base/regmap/regmap.c:_regmap_write
  - drivers/base/regmap/regmap.c:_regmap_bus_formatted_write
  - drivers/base/regmap/regmap.c:_regmap_bus_formatted_write
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
```
```
In drivers/base/regmap/regcache.c (ffffffff81b203fe)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/base/regmap/regcache.c:regcache_cache_bypass
  - drivers/base/regmap/regcache.c:regcache_cache_only
  - drivers/base/regmap/regcache.c:regcache_drop_region
  - drivers/base/regmap/regcache.c:regcache_sync_region
  - drivers/base/regmap/regcache.c:regcache_sync_region
  - drivers/base/regmap/regcache.c:regcache_sync
  - drivers/base/regmap/regcache.c:regcache_sync
  - drivers/base/regmap/regcache.c:regcache_read
```
```
In drivers/block/loop.c (ffffffff81b2c00b)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In drivers/block/xen-blkfront.c (ffffffff81b30be7)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_completion
  - drivers/block/xen-blkfront.c:blkif_copy_from_grant
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/nvdimm/region_devs.c (ffffffff81b54b80)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_release_lane
  - drivers/nvdimm/region_devs.c:nd_region_acquire_lane
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81b6c1ea)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:__dma_fence_enable_signaling
  - drivers/dma-buf/dma-fence.c:dma_fence_release
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_signal_timestamp_locked
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81b71c12)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
```
```
In drivers/scsi/scsi_error.c (ffffffff81b7bb68)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_timeout
```
```
In drivers/scsi/scsi_lib.c (ffffffff81b7e014)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
  - drivers/scsi/scsi_lib.c:scsi_done_internal
  - drivers/scsi/scsi_lib.c:scsi_dispatch_cmd
  - drivers/scsi/scsi_lib.c:scsi_dispatch_cmd
```
```
In drivers/scsi/sd_zbc.c (ffffffff81b962ab)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_zone_wp_update
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
```
```
In drivers/ata/libata-core.c (ffffffff81ba7b0a)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-core.c:ata_qc_complete
  - drivers/ata/libata-core.c:ata_qc_complete
  - drivers/ata/libata-core.c:ata_qc_complete
```
```
In drivers/ata/libata-eh.c (ffffffff81bb9ac8)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_done
  - drivers/ata/libata-eh.c:ata_eh_about_to_do
  - drivers/ata/libata-eh.c:__ata_port_freeze
```
```
In drivers/ata/libata-sff.c (ffffffff81bc1a64)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_bmdma_post_internal_cmd
  - drivers/ata/libata-sff.c:ata_bmdma_error_handler
  - drivers/ata/libata-sff.c:ata_bmdma_error_handler
  - drivers/ata/libata-sff.c:ata_bmdma_port_intr
  - drivers/ata/libata-sff.c:ata_bmdma_port_intr
  - drivers/ata/libata-sff.c:ata_bmdma_qc_issue
  - drivers/ata/libata-sff.c:ata_bmdma_qc_issue
  - drivers/ata/libata-sff.c:ata_bmdma_qc_issue
  - drivers/ata/libata-sff.c:ata_bmdma_qc_issue
  - drivers/ata/libata-sff.c:ata_bmdma_qc_issue
  - drivers/ata/libata-sff.c:__ata_sff_port_intr
  - drivers/ata/libata-sff.c:ata_sff_flush_pio_task
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:__atapi_pio_bytes
  - drivers/ata/libata-sff.c:__atapi_pio_bytes
  - drivers/ata/libata-sff.c:ata_pio_sector
  - drivers/ata/libata-sff.c:ata_tf_to_host
  - drivers/ata/libata-sff.c:ata_tf_to_host
```
```
In drivers/ata/ata_piix.c (ffffffff81bc8a57)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/ata/ata_piix.c:piix_irq_check
```
```
In drivers/spi/spi.c (ffffffff81bd700f)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_sync
  - drivers/spi/spi.c:__spi_sync
  - drivers/spi/spi.c:__spi_sync
  - drivers/spi/spi.c:__spi_sync
  - drivers/spi/spi.c:__spi_sync
  - drivers/spi/spi.c:__spi_async
  - drivers/spi/spi.c:__spi_async
  - drivers/spi/spi.c:__spi_async
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:spi_split_transfers_maxsize
  - drivers/spi/spi.c:spi_split_transfers_maxsize
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_transfer_message
  - drivers/spi/spi.c:__spi_pump_transfer_message
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_transfer_wait
  - drivers/spi/spi.c:spi_transfer_wait
  - drivers/spi/spi.c:spi_set_cs
  - drivers/spi/spi.c:spi_statistics_add_transfer_stats
```
```
In drivers/net/phy/mdio_bus.c (ffffffff81be6279)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:__mdiobus_write
  - drivers/net/phy/mdio_bus.c:__mdiobus_write
  - drivers/net/phy/mdio_bus.c:__mdiobus_read
  - drivers/net/phy/mdio_bus.c:__mdiobus_read
```
```
In drivers/net/tun.c (ffffffff81bf32d7)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_xdp_act
  - drivers/net/tun.c:tun_napi_alloc_frags
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81bfe5d5)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
```
```
In drivers/net/xen-netfront.c (ffffffff81c0794d)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:netfront_resume
```
```
In drivers/usb/host/xhci.c (ffffffff81c7e5b6)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81c827a2)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_ring_alloc
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81c86439)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:queue_trb
  - drivers/usb/host/xhci-ring.c:xhci_handle_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_port_status
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_ring_ep_doorbell
  - drivers/usb/host/xhci-ring.c:inc_enq
  - drivers/usb/host/xhci-ring.c:inc_deq
```
```
In drivers/usb/host/xhci-hub.c (ffffffff81c90a64)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81c98063)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events
  - drivers/usb/host/xhci-dbgcap.c:dbc_handle_xfer_event
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_queue_bulk_tx
  - drivers/usb/host/xhci-dbgcap.c:dbc_free_request
  - drivers/usb/host/xhci-dbgcap.c:dbc_alloc_request
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
```
```
In drivers/rtc/interface.c (ffffffff81cbd497)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_set_offset
  - drivers/rtc/interface.c:rtc_read_offset
  - drivers/rtc/interface.c:rtc_timer_cancel
  - drivers/rtc/interface.c:rtc_timer_start
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_alarm_disable
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_irq_set_freq
  - drivers/rtc/interface.c:rtc_irq_set_state
  - drivers/rtc/interface.c:rtc_alarm_irq_enable
  - drivers/rtc/interface.c:rtc_initialize_alarm
  - drivers/rtc/interface.c:__rtc_set_alarm
  - drivers/rtc/interface.c:rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:rtc_read_time
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81cc532f)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff81cc8ede)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In drivers/hwmon/hwmon.c (ffffffff81cdba7f)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:hwmon_attr_store
  - drivers/hwmon/hwmon.c:hwmon_attr_show_string
  - drivers/hwmon/hwmon.c:hwmon_attr_show
```
```
In drivers/thermal/thermal_core.c (ffffffff81cddcb1)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:handle_thermal_trip
```
```
In drivers/thermal/thermal_helpers.c (ffffffff81ce3cc4)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/thermal/thermal_helpers.c:__thermal_cdev_update
```
```
In drivers/thermal/gov_fair_share.c (ffffffff81ce6356)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/thermal/gov_fair_share.c:get_trip_level
```
```
In drivers/thermal/gov_step_wise.c (ffffffff81ce6a9b)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/thermal/gov_step_wise.c:thermal_zone_trip_update
```
```
In drivers/thermal/gov_power_allocator.c (ffffffff81ce82b8)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/thermal/gov_power_allocator.c:allocate_power
  - drivers/thermal/gov_power_allocator.c:pid_controller
```
```
In drivers/thermal/devfreq_cooling.c (ffffffff81ce90db)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_power2state
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power
```
```
In drivers/thermal/intel/therm_throt.c (ffffffff81ce9a14)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_package_throttle_total_time_ms
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_core_throttle_total_time_ms
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_package_throttle_max_time_ms
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_core_throttle_max_time_ms
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_package_power_limit_count
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_package_throttle_count
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_core_power_limit_count
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_core_throttle_count
```
```
In drivers/watchdog/watchdog_core.c (ffffffff81ceb363)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_core.c:watchdog_reboot_notifier
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81ced522)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_stop
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
```
```
In drivers/md/md.c (ffffffff81cf2933)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/md/md.c:md_submit_discard_bio
```
```
In drivers/md/md-bitmap.c (ffffffff81d08bee)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_file_clear_bit
  - drivers/md/md-bitmap.c:md_bitmap_file_set_bit
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_new_disk_sb
  - drivers/md/md-bitmap.c:md_bitmap_print_sb
```
```
In drivers/md/dm.c (ffffffff81d0f9d0)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_split_and_process_bio
  - drivers/md/dm.c:dm_submit_bio_remap
```
```
In drivers/md/dm-stats.c (ffffffff81d1ccd0)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stat_for_entry
```
```
In drivers/md/dm-rq.c (ffffffff81d1f38c)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:map_request
```
```
In drivers/edac/edac_mc.c (ffffffff81d20e01)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
  - drivers/edac/edac_mc.c:edac_mc_scrub_block
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81d301ec)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_driver_fast_switch
  - drivers/cpufreq/cpufreq.c:cpufreq_notify_transition
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81d33d91)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_init
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81d362d6)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target
```
```
In drivers/cpufreq/amd-pstate.c (ffffffff81d3841a)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/cpufreq/amd-pstate.c:amd_pstate_update
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81d3fc76)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_adjust_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_adjust_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_pstate
```
```
In drivers/cpuidle/cpuidle.c (ffffffff81d41fd5)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_use_deepest_state
```
```
In drivers/cpuidle/driver.c (ffffffff81d42585)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In drivers/cpuidle/governors/haltpoll.c (ffffffff81d45ca6)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In drivers/mmc/core/core.c (ffffffff81d47e6c)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_cqe_request_done
  - drivers/mmc/core/core.c:mmc_cqe_start_req
  - drivers/mmc/core/core.c:__mmc_start_request
  - drivers/mmc/core/core.c:mmc_request_done
```
```
In drivers/firmware/efi/capsule.c (ffffffff81d63ddc)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/firmware/efi/capsule.c:efi_capsule_update
```
```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff81d678b0)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
```
```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff81d71887)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In drivers/devfreq/devfreq.c (ffffffff81d8058e)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_monitor
  - drivers/devfreq/devfreq.c:devfreq_set_target
```
```
In drivers/ras/ras.c (ffffffff81d8a055)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/ras/ras.c:log_arm_hw_error
  - drivers/ras/ras.c:log_non_standard_event
```
```
In drivers/interconnect/core.c (ffffffff81d8f702)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/interconnect/core.c:icc_set_bw
  - drivers/interconnect/core.c:icc_set_bw
```
```
In net/core/sock.c (ffffffff81d9e335)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_reduce_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:sk_error_report
```
```
In net/core/skbuff.c (ffffffff81da5865)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:__consume_stateless_skb
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:kfree_skb_reason
  - net/core/skbuff.c:kfree_skb_reason
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_frag_align
  - net/core/skbuff.c:napi_get_frags_check
```
```
In net/core/datagram.c (ffffffff81daf637)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_datagram_iter
```
```
In net/core/gen_estimator.c (ffffffff81db2c33)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/net_namespace.c (ffffffff81db404c)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/core/dev.c (ffffffff81dcec4d)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:__dev_set_allmulti
  - net/core/dev.c:dev_set_promiscuity
  - net/core/dev.c:napi_threaded_poll
  - net/core/dev.c:__napi_poll
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:flush_backlog
  - net/core/dev.c:netif_receive_skb_list
  - net/core/dev.c:netif_receive_skb_list
  - net/core/dev.c:netif_receive_skb
  - net/core/dev.c:netif_receive_skb
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__netif_rx
  - net/core/dev.c:__netif_rx
  - net/core/dev.c:netif_rx_internal
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:__dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_qdisc_enqueue
  - net/core/dev.c:dev_hard_start_xmit
  - net/core/dev.c:dev_hard_start_xmit
  - net/core/dev.c:__dev_open
```
```
In net/core/dev_addr_lists.c (ffffffff81dd3345)
Location: arch/x86/include/asm/preempt.h:78
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
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_seq_start
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_for_each
  - net/core/neighbour.c:neigh_dump_table
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
  - net/core/neighbour.c:neigh_cleanup_and_release
```
```
In net/core/rtnetlink.c (ffffffff81de4b9e)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_fdb_dump
```
```
In net/core/filter.c (ffffffff81df1a5c)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_socket_ptr_cookie
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_redirect_frame
  - net/core/filter.c:xdp_do_redirect_frame
  - net/core/filter.c:xdp_do_redirect_frame
  - net/core/filter.c:xdp_do_redirect_frame
  - net/core/filter.c:xdp_do_redirect
  - net/core/filter.c:xdp_do_redirect
  - net/core/filter.c:xdp_do_redirect
  - net/core/filter.c:xdp_do_redirect
  - net/core/filter.c:bpf_out_neigh_v6
```
```
In net/core/sock_diag.c (ffffffff81e02fd5)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_save_cookie
  - net/core/sock_diag.c:sock_diag_check_cookie
```
```
In net/core/xdp.c (ffffffff81e062d4)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_rxq_info_reg_mem_model
  - net/core/xdp.c:mem_allocator_disconnect
```
```
In net/core/gro.c (ffffffff81e09d52)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/core/gro.c:napi_gro_frags
  - net/core/gro.c:napi_gro_frags
  - net/core/gro.c:napi_gro_receive
  - net/core/gro.c:napi_gro_receive
```
```
In net/core/page_pool.c (ffffffff81e0effa)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_update_nid
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_release_page
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
  - net/core/page_pool.c:__page_pool_alloc_page_order
```
```
In net/core/net-procfs.c (ffffffff81e1111c)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In net/core/netpoll.c (ffffffff81e11735)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
  - net/core/netpoll.c:poll_one_napi
```
```
In net/core/net-traces.c (ffffffff81e1cf9a)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:perf_trace_tcp_event_sk
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk
```
```
In net/core/lwt_bpf.c (ffffffff81e28a6e)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In net/core/devlink.c (ffffffff81e2abc8)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_trap_report
  - net/core/devlink.c:devlink_health_report
  - net/core/devlink.c:devlink_health_report
```
```
In net/core/sock_map.c (ffffffff81e4b7ec)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_update_elem
  - net/core/sock_map.c:sock_map_update_elem_sys
```
```
In net/sched/sch_generic.c (ffffffff81e52c3d)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:qdisc_reset
  - net/sched/sch_generic.c:qdisc_create_dflt
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/sched/sch_api.c (ffffffff81e57b73)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_create
```
```
In net/sched/act_api.c (ffffffff81e61ea7)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_update_hw_stats
```
```
In net/netlink/af_netlink.c (ffffffff81e66c35)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:do_trace_netlink_extack
```
```
In net/bpf/test_run.c (ffffffff81e7460e)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_sk_lookup
  - net/bpf/test_run.c:bpf_prog_test_run_sk_lookup
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_prog_test_run_raw_tp
  - net/bpf/test_run.c:bpf_prog_test_run_tracing
  - net/bpf/test_run.c:bpf_test_timer_continue
```
```
In net/netfilter/nf_log.c (ffffffff81e8aab6)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/netfilter/nf_log.c:nf_log_buf_open
```
```
In net/netfilter/nf_queue.c (ffffffff81e8baf6)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_reinject
```
```
In net/ipv4/route.c (ffffffff81e8eec3)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81e99ece)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_hashtables.c (ffffffff81ea5183)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81ea646d)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ea8393)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/tcp.c (ffffffff81eb230d)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_abort
  - net/ipv4/tcp.c:tcp_abort
  - net/ipv4/tcp.c:tcp_abort
  - net/ipv4/tcp.c:__tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff81ec1aa5)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_reset
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
```
```
In net/ipv4/tcp_output.c (ffffffff81ec3f65)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_rtx_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ece910)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ed4821)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/tcp_cong.c (ffffffff81ed5864)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_set_ca_state
```
```
In net/ipv4/udp.c (ffffffff81ee3a87)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/icmp.c (ffffffff81eebc16)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_reply
```
```
In net/ipv4/af_inet.c (ffffffff81ef6112)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sk_state_store
  - net/ipv4/af_inet.c:inet_sk_set_state
```
```
In net/ipv4/fib_frontend.c (ffffffff81efd22a)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_lookup
```
```
In net/ipv4/fib_semantics.c (ffffffff81f04366)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/fib_trie.c (ffffffff81f07d65)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv4/inet_fragment.c (ffffffff81f0a6e2)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f0df11)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/nexthop.c (ffffffff81f1224e)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_select_path_hthr
  - net/ipv4/nexthop.c:nexthop_select_path_hthr
```
```
In net/ipv4/ipmr.c (ffffffff81f20534)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f331d2)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In net/xfrm/xfrm_state.c (0)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In net/xfrm/xfrm_input.c (ffffffff81f41315)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/espintcp.c (ffffffff81f47fa8)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:handle_esp
```
```
In net/ipv6/ip6_output.c (ffffffff81f55415)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/addrconf.c (ffffffff81f66181)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff81f7159f)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:fib6_table_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:rt6_probe
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ip6_fib.c (ffffffff81f7b627)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_start
```
```
In net/ipv6/icmp.c (ffffffff81f908fe)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f9df99)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81fa46b4)
Location: arch/x86/include/asm/preempt.h:78
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
In net/ipv6/ioam6.c (ffffffff81fa98f0)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/ip6mr.c (ffffffff81fae119)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81fb9ff1)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
```
```
In net/ipv6/seg6_local.c (ffffffff81fbdac7)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
```
```
In net/ipv6/seg6_hmac.c (ffffffff81fbe06b)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff81fc004f)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
```
```
In net/mptcp/protocol.c (ffffffff81ff8bdc)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_subflow_get_send
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
```
```
In net/mptcp/subflow.c (ffffffff81ffe4ba)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:get_mapping_status
```
```
In net/mptcp/options.c (ffffffff82001d3f)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/mptcp/options.c:ack_update_msk
```
```
In net/mctp/af_mctp.c (ffffffff820103d6)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In net/mctp/route.c (ffffffff82013ed1)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_alloc_local_tag
  - net/mctp/route.c:mctp_route_input
  - net/mctp/route.c:__mctp_key_done_in
```
```
In lib/bug.c (ffffffff8201ed50)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - lib/bug.c:generic_bug_clear_once
  - lib/bug.c:report_bug
  - lib/bug.c:find_bug
```
```
In lib/buildid.c (ffffffff8201f002)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - lib/buildid.c:build_id_parse
```
```
In lib/flex_proportions.c (0)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In lib/maple_tree.c (ffffffff82030c23)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - lib/maple_tree.c:mt_find
  - lib/maple_tree.c:mtree_erase
  - lib/maple_tree.c:mtree_store_range
  - lib/maple_tree.c:mtree_load
  - lib/maple_tree.c:mas_store_prealloc
  - lib/maple_tree.c:mas_store_gfp
  - lib/maple_tree.c:mas_store
  - lib/maple_tree.c:mas_wr_bnode
  - lib/maple_tree.c:mas_wr_slot_store
  - lib/maple_tree.c:mas_wr_node_store
  - lib/maple_tree.c:mas_is_span_wr
```
```
In lib/nmi_backtrace.c (ffffffff82039170)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
```
In lib/radix-tree.c (ffffffff820396b7)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - lib/radix-tree.c:__radix_tree_preload
  - lib/radix-tree.c:__radix_tree_preload
```
```
In arch/x86/lib/delay.c (ffffffff8204c475)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/lib/delay.c:delay_tsc
  - arch/x86/lib/delay.c:delay_tsc
```
```
In arch/x86/lib/usercopy_64.c (ffffffff8204ff65)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:memcpy_page_flushcache
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
In init/main.c (ffffffff83681e8b)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
  - init/main.c:do_initcalls
  - init/main.c:do_one_initcall
  - init/main.c:do_one_initcall
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81004dd2)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
```
```
In arch/x86/events/amd/ibs.c (ffffffff83686140)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
```
```
In arch/x86/events/intel/ds.c (ffffffff8101720e)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:ds_clear_cea
  - arch/x86/events/intel/ds.c:ds_update_cea
```
```
In arch/x86/events/intel/p4.c (ffffffff8101e695)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_hw_config
```
```
In arch/x86/xen/time.c (ffffffff8368b9e5)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_hvm_init_time_ops
  - arch/x86/xen/time.c:xen_init_time_ops
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_restore_time_memory_area
  - arch/x86/xen/time.c:xen_save_time_memory_area
  - arch/x86/xen/time.c:xen_vcpuop_set_next_event
  - arch/x86/xen/time.c:xen_timerop_set_next_event
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
  - arch/x86/xen/time.c:xen_get_wallclock
  - arch/x86/xen/time.c:xen_clocksource_get_cycles
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff810382a2)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_cr0
  - arch/x86/xen/enlighten_pv.c:xen_load_sp0
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry
  - arch/x86/xen/enlighten_pv.c:xen_load_idt
  - arch/x86/xen/enlighten_pv.c:xen_write_idt_entry
  - arch/x86/xen/enlighten_pv.c:xen_write_idt_entry
  - arch/x86/xen/enlighten_pv.c:xen_write_ldt_entry
  - arch/x86/xen/enlighten_pv.c:xen_write_ldt_entry
  - arch/x86/xen/enlighten_pv.c:load_TLS_descriptor
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
  - arch/x86/xen/enlighten_pv.c:xen_mc_batch
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8103a005)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_all
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_all
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_leave_lazy_mmu
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:__xen_write_cr3
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
  - arch/x86/xen/mmu_pv.c:xen_set_p4d_hyper
  - arch/x86/xen/mmu_pv.c:xen_set_pud
  - arch/x86/xen/mmu_pv.c:xen_set_pud_hyper
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_start
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pmd
  - arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper
  - arch/x86/xen/mmu_pv.c:xen_extend_mmuext_op
  - arch/x86/xen/mmu_pv.c:xen_extend_mmu_update
  - arch/x86/xen/mmu_pv.c:xen_mc_batch
```
```
In arch/x86/xen/multicalls.c (ffffffff8103dc13)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/xen/multicalls.c:xen_mc_callback
  - arch/x86/xen/multicalls.c:xen_mc_callback
  - arch/x86/xen/multicalls.c:xen_mc_extend_args
  - arch/x86/xen/multicalls.c:xen_mc_extend_args
  - arch/x86/xen/multicalls.c:xen_mc_extend_args
  - arch/x86/xen/multicalls.c:__xen_mc_entry
  - arch/x86/xen/multicalls.c:__xen_mc_entry
  - arch/x86/xen/multicalls.c:xen_mc_flush
```
```
In arch/x86/hyperv/hv_init.c (ffffffff81045179)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:set_hv_tscchange_cb
```
```
In arch/x86/hyperv/mmu.c (ffffffff8104704b)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
```
```
In arch/x86/hyperv/nested.c (ffffffff81047644)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff810494da)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_one
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
```
```
In arch/x86/kernel/process_64.c (ffffffff8104b65d)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/signal.c (ffffffff8104ba25)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:handle_signal
```
```
In arch/x86/kernel/irq.c (ffffffff81050267)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:__sysvec_thermal
  - arch/x86/kernel/irq.c:__sysvec_thermal
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:__sysvec_x86_platform_ipi
  - arch/x86/kernel/irq.c:__sysvec_x86_platform_ipi
```
```
In arch/x86/kernel/ioport.c (ffffffff810519fe)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In arch/x86/kernel/nmi.c (ffffffff8105330d)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:nmi_handle
```
```
In arch/x86/kernel/irq_work.c (ffffffff8105571c)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:__sysvec_irq_work
  - arch/x86/kernel/irq_work.c:__sysvec_irq_work
```
```
In arch/x86/kernel/tsc.c (ffffffff8105e965)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state
  - arch/x86/kernel/tsc.c:tsc_save_sched_clock_state
  - arch/x86/kernel/tsc.c:native_sched_clock_from_tsc
  - arch/x86/kernel/tsc.c:__set_cyc2ns_scale
  - arch/x86/kernel/tsc.c:cyc2ns_read_begin
```
```
In arch/x86/kernel/process.c (ffffffff8106106a)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:do_arch_prctl_common
  - arch/x86/kernel/process.c:speculation_ctrl_update_current
  - arch/x86/kernel/process.c:enable_cpuid
  - arch/x86/kernel/process.c:set_tsc_mode
  - arch/x86/kernel/process.c:disable_TSC
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81062d32)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpregs_mark_activate
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
  - arch/x86/kernel/fpu/core.c:fpu__clear_user_states
  - arch/x86/kernel/fpu/core.c:fpu_reset_fpregs
  - arch/x86/kernel/fpu/core.c:fpu__drop
  - arch/x86/kernel/fpu/core.c:fpu__drop
  - arch/x86/kernel/fpu/core.c:fpu__drop
  - arch/x86/kernel/fpu/core.c:fpu_clone
  - arch/x86/kernel/fpu/core.c:fpu_clone
  - arch/x86/kernel/fpu/core.c:fpu_clone
  - arch/x86/kernel/fpu/core.c:fpu_clone
  - arch/x86/kernel/fpu/core.c:fpu_sync_fpstate
  - arch/x86/kernel/fpu/core.c:fpu_sync_fpstate
  - arch/x86/kernel/fpu/core.c:fpu_sync_fpstate
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin_mask
  - arch/x86/kernel/fpu/core.c:fpu_swap_kvm_fpstate
  - arch/x86/kernel/fpu/core.c:fpu_update_guest_xfd
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8106438b)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
  - arch/x86/kernel/fpu/signal.c:check_xstate_in_sigframe
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff810650cf)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In arch/x86/kernel/tls.c (ffffffff81068300)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:set_tls_desc
```
```
In arch/x86/kernel/cpu/aperfmperf.c (0)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81073a03)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:split_lock_warn
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff810788d5)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:wait_for_panic
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8107d2ad)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:__sysvec_deferred_error
  - arch/x86/kernel/cpu/mce/amd.c:__sysvec_deferred_error
```
```
In arch/x86/kernel/cpu/mce/threshold.c (ffffffff8107f11d)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/threshold.c:__sysvec_threshold
  - arch/x86/kernel/cpu/mce/threshold.c:__sysvec_threshold
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff810823d5)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_get_mtrr
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8108df53)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:add_rmid_to_limbo
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81090a07)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_l3_residency
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_l2_residency
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff81094a8e)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_init
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff81097d01)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_virt_einit
```
```
In arch/x86/kernel/smp.c (ffffffff8109b70c)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:__sysvec_call_function_single
  - arch/x86/kernel/smp.c:__sysvec_call_function_single
  - arch/x86/kernel/smp.c:__sysvec_call_function
  - arch/x86/kernel/smp.c:__sysvec_call_function
  - arch/x86/kernel/smp.c:sysvec_reschedule_ipi
  - arch/x86/kernel/smp.c:sysvec_reschedule_ipi
  - arch/x86/kernel/smp.c:sysvec_reschedule_ipi
```
```
In arch/x86/kernel/smpboot.c (ffffffff836acbc5)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:smp_sanity_check
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
```
```
In arch/x86/kernel/apic/apic.c (ffffffff810a0c48)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:__sysvec_error_interrupt
  - arch/x86/kernel/apic/apic.c:__sysvec_error_interrupt
  - arch/x86/kernel/apic/apic.c:handle_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:handle_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:__sysvec_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:__sysvec_apic_timer_interrupt
```
```
In arch/x86/kernel/apic/vector.c (ffffffff836b1e56)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/vector.c:free_moved_vector
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_deactivate
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
  - arch/x86/kernel/apic/vector.c:assign_vector_locked
  - arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked
  - arch/x86/kernel/apic/vector.c:apic_update_vector
  - arch/x86/kernel/apic/vector.c:apic_update_irq_cfg
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff810aab5f)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_one
```
```
In arch/x86/kernel/ftrace.c (ffffffff810adf7a)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/ftrace.c:prepare_ftrace_return
```
```
In arch/x86/kernel/kprobes/opt.c (ffffffff810b398f)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In arch/x86/kernel/kprobes/ftrace.c (ffffffff810b443a)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
```
In arch/x86/kernel/kvmclock.c (ffffffff836ba8e5)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/kernel/kvmclock.c:kvm_clock_get_cycles
  - arch/x86/kernel/kvmclock.c:kvm_get_wallclock
```
```
In arch/x86/kernel/paravirt.c (ffffffff810bba95)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu
```
```
In arch/x86/kernel/callthunks.c (ffffffff810c22a1)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/callthunks.c:is_coretext
```
```
In arch/x86/mm/fault.c (ffffffff82141816)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:exc_page_fault
  - arch/x86/mm/fault.c:exc_page_fault
```
```
In arch/x86/mm/tlb.c (ffffffff810ccf25)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:arch_tlbbatch_flush
  - arch/x86/mm/tlb.c:flush_tlb_kernel_range
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
  - arch/x86/mm/tlb.c:native_flush_tlb_multi
  - arch/x86/mm/tlb.c:native_flush_tlb_multi
  - arch/x86/mm/tlb.c:flush_tlb_func
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/mm/kmmio.c (ffffffff810d5a64)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:kmmio_handler
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810d66e5)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:post
  - arch/x86/mm/mmio-mod.c:post
  - arch/x86/mm/mmio-mod.c:pre
  - arch/x86/mm/mmio-mod.c:pre
  - arch/x86/mm/mmio-mod.c:pre
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff810e3cee)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
```
```
In arch/x86/platform/uv/bios_uv.c (ffffffff810e6344)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/platform/uv/bios_uv.c:__uv_bios_call
```
```
In kernel/fork.c (ffffffff810f497f)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/fork.c:kernel_clone
  - kernel/fork.c:copy_process
```
```
In kernel/panic.c (ffffffff810f5b0e)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/panic.c:__warn_printk
  - kernel/panic.c:__warn
  - kernel/panic.c:panic
```
```
In kernel/cpu.c (ffffffff810f9206)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
  - kernel/cpu.c:__cpuhp_state_add_instance
  - kernel/cpu.c:thaw_secondary_cpus
  - kernel/cpu.c:thaw_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:cpuhp_kick_ap_work
  - kernel/cpu.c:cpuhp_kick_ap_work
  - kernel/cpu.c:cpus_read_trylock
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
```
```
In kernel/exit.c (ffffffff810fcd55)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:delayed_put_task_struct
```
```
In kernel/softirq.c (ffffffff810ffd20)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/softirq.c:__raise_softirq_irqoff
  - kernel/softirq.c:irq_enter
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
```
```
In kernel/signal.c (ffffffff81111362)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:exit_signals
  - kernel/signal.c:exit_signals
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:__send_signal_locked
```
```
In kernel/workqueue.c (ffffffff8111d0fc)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_congested
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:pwq_activate_inactive_work
  - kernel/workqueue.c:wq_worker_running
```
```
In kernel/kthread.c (ffffffff8112ac2c)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_stop
  - kernel/kthread.c:kthread_stop
  - kernel/kthread.c:kthread
  - kernel/kthread.c:__kthread_parkme
```
```
In kernel/notifier.c (ffffffff811327c1)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/notifier.c:notifier_call_chain
  - kernel/notifier.c:notifier_chain_unregister
```
```
In kernel/smpboot.c (ffffffff811368e6)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/smpboot.c:smpboot_thread_fn
```
```
In kernel/sched/core.c (ffffffff811523f5)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_mm_cid_after_execve
  - kernel/sched/core.c:sched_mm_cid_before_execve
  - kernel/sched/core.c:call_trace_sched_update_nr_running
  - kernel/sched/core.c:migrate_task_to
  - kernel/sched/core.c:klp_cond_resched
  - kernel/sched/core.c:do_sched_yield
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:preempt_schedule_irq
  - kernel/sched/core.c:preempt_schedule_notrace
  - kernel/sched/core.c:preempt_schedule
  - kernel/sched/core.c:schedule_preempt_disabled
  - kernel/sched/core.c:schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:sched_core_balance
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:call_function_single_prep_ipi
  - kernel/sched/core.c:ttwu_do_activate
  - kernel/sched/core.c:kick_process
  - kernel/sched/core.c:kick_process
  - kernel/sched/core.c:migrate_swap
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:migrate_enable
  - kernel/sched/core.c:migrate_disable
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:wake_up_nohz_cpu
  - kernel/sched/core.c:wake_up_nohz_cpu
  - kernel/sched/core.c:resched_curr
  - kernel/sched/core.c:resched_curr
  - kernel/sched/core.c:raw_spin_rq_trylock
```
```
In kernel/sched/fair.c (ffffffff8115b285)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:update_group_capacity
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:detach_entity_load_avg
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/build_policy.c (ffffffff8116d099)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:dl_bw_manage
  - kernel/sched/build_policy.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/build_policy.c:sched_dl_do_global
  - kernel/sched/build_policy.c:sched_dl_global_validate
  - kernel/sched/build_policy.c:update_curr_dl
  - kernel/sched/build_policy.c:update_dl_rq_load_avg
  - kernel/sched/build_policy.c:update_rt_rq_load_avg
  - kernel/sched/build_policy.c:__update_load_avg_cfs_rq
  - kernel/sched/build_policy.c:__update_load_avg_se
  - kernel/sched/build_policy.c:__update_load_avg_blocked_se
  - kernel/sched/build_policy.c:update_curr_rt
  - kernel/sched/build_policy.c:play_idle_precise
  - kernel/sched/build_policy.c:default_idle_call
  - kernel/sched/build_policy.c:default_idle_call
```
```
In kernel/sched/build_utility.c (ffffffff8117e99d)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:membarrier_private_expedited
  - kernel/sched/build_utility.c:membarrier_global_expedited
  - kernel/sched/build_utility.c:__update_stats_enqueue_sleeper
  - kernel/sched/build_utility.c:__update_stats_enqueue_sleeper
  - kernel/sched/build_utility.c:__update_stats_enqueue_sleeper
  - kernel/sched/build_utility.c:__update_stats_wait_end
  - kernel/sched/build_utility.c:sched_debug_header
  - kernel/sched/build_utility.c:running_clock
  - kernel/sched/build_utility.c:sched_clock_cpu
  - kernel/sched/build_utility.c:__sched_clock_work
```
```
In kernel/locking/mutex.c (ffffffff821530aa)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In kernel/locking/semaphore.c (ffffffff821548d3)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/locking/semaphore.c:__down_common
  - kernel/locking/semaphore.c:__down_common
```
```
In kernel/locking/rwsem.c (ffffffff8118dfa3)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:downgrade_write
  - kernel/locking/rwsem.c:up_write
  - kernel/locking/rwsem.c:up_read
  - kernel/locking/rwsem.c:down_write_trylock
  - kernel/locking/rwsem.c:down_write_killable
  - kernel/locking/rwsem.c:down_write
  - kernel/locking/rwsem.c:down_read_trylock
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read_interruptible
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/locking/percpu-rwsem.c (ffffffff82155cb6)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_down_write
  - kernel/locking/percpu-rwsem.c:percpu_down_write
  - kernel/locking/percpu-rwsem.c:__percpu_down_read
  - kernel/locking/percpu-rwsem.c:__percpu_down_read
  - kernel/locking/percpu-rwsem.c:__percpu_down_read
```
```
In kernel/locking/spinlock.c (ffffffff8118ebd7)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:__raw_write_lock_irqsave
  - kernel/locking/spinlock.c:__raw_read_lock_irqsave
  - kernel/locking/spinlock.c:_raw_write_trylock
  - kernel/locking/spinlock.c:_raw_read_trylock
  - kernel/locking/spinlock.c:_raw_write_lock_irq
  - kernel/locking/spinlock.c:_raw_read_lock_irq
  - kernel/locking/spinlock.c:_raw_write_lock_bh
  - kernel/locking/spinlock.c:_raw_read_lock_bh
  - kernel/locking/spinlock.c:_raw_write_lock_nested
  - kernel/locking/spinlock.c:_raw_write_lock
  - kernel/locking/spinlock.c:_raw_read_lock
  - kernel/locking/spinlock.c:__raw_spin_lock_irqsave
  - kernel/locking/spinlock.c:_raw_spin_trylock_bh
  - kernel/locking/spinlock.c:_raw_spin_trylock
  - kernel/locking/spinlock.c:_raw_spin_lock_irq
  - kernel/locking/spinlock.c:_raw_spin_lock_bh
  - kernel/locking/spinlock.c:_raw_spin_lock
```
```
In kernel/locking/qspinlock.c (ffffffff82159c29)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:native_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:native_queued_spin_lock_slowpath
```
```
In kernel/locking/rtmutex_api.c (ffffffff82155e5e)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:mark_wakeup_next_waiter
```
```
In kernel/locking/qrwlock.c (ffffffff8215a1be)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/power/qos.c (ffffffff8118f905)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/power/qos.c:cpu_latency_qos_remove_request
  - kernel/power/qos.c:pm_qos_update_flags
  - kernel/power/qos.c:pm_qos_update_target
```
```
In kernel/power/process.c (ffffffff8119225f)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:thaw_processes
```
```
In kernel/power/suspend.c (ffffffff81193416)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:s2idle_loop
  - kernel/power/suspend.c:s2idle_loop
```
```
In kernel/power/hibernate.c (ffffffff8119468f)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/power/hibernate.c:create_image
  - kernel/power/hibernate.c:create_image
```
```
In kernel/power/snapshot.c (0)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In kernel/printk/printk.c (ffffffff836d0027)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_init
  - kernel/printk/printk.c:console_init
  - kernel/printk/printk.c:console_init
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:printk_sprint
```
```
In kernel/irq/handle.c (ffffffff811a752f)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/manage.c (ffffffff811a7f15)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_forced_thread_fn
```
```
In kernel/irq/chip.c (ffffffff811ae105)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi
  - kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_fasteoi_nmi
  - kernel/irq/chip.c:handle_fasteoi_nmi
```
```
In kernel/irq/matrix.c (ffffffff811ba593)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_free
  - kernel/irq/matrix.c:irq_matrix_alloc
  - kernel/irq/matrix.c:irq_matrix_remove_reserved
  - kernel/irq/matrix.c:irq_matrix_reserve
  - kernel/irq/matrix.c:irq_matrix_assign
  - kernel/irq/matrix.c:irq_matrix_alloc_managed
  - kernel/irq/matrix.c:irq_matrix_remove_managed
  - kernel/irq/matrix.c:irq_matrix_reserve_managed
  - kernel/irq/matrix.c:irq_matrix_assign_system
  - kernel/irq/matrix.c:irq_matrix_offline
  - kernel/irq/matrix.c:irq_matrix_online
```
```
In kernel/rcu/update.c (ffffffff811bb35d)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_invoke_cbs
```
```
In kernel/rcu/srcutree.c (ffffffff811c0b58)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
```
```
In kernel/rcu/tree.c (ffffffff811cb3fc)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_note_context_switch
  - kernel/rcu/tree.c:rcu_note_context_switch
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:__sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:print_cpu_stall
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_do_batch
```
```
In kernel/livepatch/core.c (ffffffff811cf94a)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_init_object
```
```
In kernel/livepatch/patch.c (ffffffff811d07c5)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_ftrace_handler
```
```
In kernel/livepatch/transition.c (ffffffff811d1fa5)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_update_patch_state
```
```
In kernel/dma/swiotlb.c (ffffffff811d8115)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_map
```
```
In kernel/entry/common.c (ffffffff811d934e)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/entry/common.c:syscall_exit_work
  - kernel/entry/common.c:irqentry_nmi_enter
```
```
In kernel/module/main.c (ffffffff811e1231)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/module/main.c:print_modules
  - kernel/module/main.c:is_module_text_address
  - kernel/module/main.c:is_module_address
  - kernel/module/main.c:search_module_extables
  - kernel/module/main.c:load_module
  - kernel/module/main.c:__symbol_get
  - kernel/module/main.c:free_module
  - kernel/module/main.c:module_put
  - kernel/module/main.c:try_module_get
  - kernel/module/main.c:symbol_put_addr
  - kernel/module/main.c:__symbol_put
  - kernel/module/main.c:__is_module_percpu_address
```
```
In kernel/module/kmod.c (ffffffff811e186c)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/module/kmod.c:__request_module
```
```
In kernel/module/kallsyms.c (ffffffff811e35d4)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/module/kallsyms.c:module_kallsyms_on_each_symbol
  - kernel/module/kallsyms.c:find_kallsyms_symbol_value
  - kernel/module/kallsyms.c:module_kallsyms_lookup_name
  - kernel/module/kallsyms.c:module_get_kallsym
  - kernel/module/kallsyms.c:lookup_module_symbol_name
  - kernel/module/kallsyms.c:module_address_lookup
```
```
In kernel/module/version.c (ffffffff811e4a69)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/module/version.c:check_modstruct_version
```
```
In kernel/profile.c (ffffffff811e6487)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/profile.c:profile_discard_flip_buffers
  - kernel/profile.c:profile_flip_buffers
```
```
In kernel/time/timer.c (ffffffff811ecd93)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:__run_timers
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:detach_if_pending
  - kernel/time/timer.c:enqueue_timer
```
```
In kernel/time/hrtimer.c (ffffffff811ef3ab)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_nanosleep_restart
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_init
  - kernel/time/hrtimer.c:__hrtimer_start_range_ns
  - kernel/time/hrtimer.c:enqueue_hrtimer
  - kernel/time/hrtimer.c:clock_was_set
```
```
In kernel/time/timekeeping.c (0)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In kernel/time/clocksource.c (ffffffff811f5173)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In kernel/time/alarmtimer.c (ffffffff811f7db9)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_try_to_cancel
  - kernel/time/alarmtimer.c:alarm_start
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - kernel/time/alarmtimer.c:alarmtimer_fired
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811fcfc5)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:check_cpu_itimer
```
```
In kernel/time/itimer.c (ffffffff812007a2)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:it_real_fn
```
```
In kernel/time/tick-common.c (ffffffff81202f04)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_unfreeze
  - kernel/time/tick-common.c:tick_freeze
```
```
In kernel/time/tick-sched.c (ffffffff81205687)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_stop_tick
```
```
In kernel/smp.c (ffffffff8120dbbc)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/smp.c:wake_up_all_idle_cpus
  - kernel/smp.c:kick_all_cpus_sync
  - kernel/smp.c:on_each_cpu_cond_mask
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_any
  - kernel/smp.c:smp_call_function_single_async
  - kernel/smp.c:smp_call_function_single
  - kernel/smp.c:__flush_smp_call_function_queue
  - kernel/smp.c:__flush_smp_call_function_queue
  - kernel/smp.c:__flush_smp_call_function_queue
  - kernel/smp.c:__flush_smp_call_function_queue
  - kernel/smp.c:__flush_smp_call_function_queue
  - kernel/smp.c:__flush_smp_call_function_queue
  - kernel/smp.c:generic_exec_single
  - kernel/smp.c:generic_exec_single
  - kernel/smp.c:__smp_call_single_queue
  - kernel/smp.c:__smp_call_single_queue
```
```
In kernel/acct.c (ffffffff812125fe)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
  - kernel/acct.c:do_acct_process
```
```
In kernel/cgroup/cgroup.c (ffffffff8121ee1b)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_css_set_put_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_rmdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:cgroup_destroy_root
  - kernel/cgroup/cgroup.c:cgroup_update_populated
```
```
In kernel/cgroup/rstat.c (ffffffff81227495)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:__cgroup_account_cputime_field
  - kernel/cgroup/rstat.c:__cgroup_account_cputime
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8122a146)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
```
In kernel/cgroup/freezer.c (ffffffff8122ad09)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_propagate_frozen
  - kernel/cgroup/freezer.c:cgroup_propagate_frozen
```
```
In kernel/cgroup/cpuset.c (0)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In kernel/stop_machine.c (ffffffff81239bb6)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
  - kernel/stop_machine.c:cpu_stop_queue_two_works
  - kernel/stop_machine.c:cpu_stop_queue_work
```
```
In kernel/kprobes.c (ffffffff8124ca4f)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/kprobes.c:show_kprobe_addr
  - kernel/kprobes.c:check_kprobe_address_safe
  - kernel/kprobes.c:kprobe_busy_begin
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff8125b2f1)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/hung_task.c (ffffffff8125de8a)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/hung_task.c:check_hung_task
```
```
In kernel/relay.c (ffffffff81263bb7)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/relay.c:relay_late_setup_files
```
```
In kernel/trace/trace_clock.c (ffffffff81268040)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_local
```
```
In kernel/trace/ftrace.c (ffffffff8126967a)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:fnpid_start
  - kernel/trace/ftrace.c:fpid_start
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:arch_ftrace_ops_list_func
  - kernel/trace/ftrace.c:ftrace_mod_get_kallsym
  - kernel/trace/ftrace.c:ftrace_mod_address_lookup
  - kernel/trace/ftrace.c:function_trace_probe_call
  - kernel/trace/ftrace.c:ftrace_ops_trampoline
```
```
In kernel/trace/ring_buffer.c (ffffffff812782db)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_consume
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_nest_start
  - kernel/trace/ring_buffer.c:ring_buffer_time_stamp
```
```
In kernel/trace/trace.c (ffffffff8127fdd3)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_write
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_read
  - kernel/trace/trace.c:saved_cmdlines_start
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_buffered_event_enable
  - kernel/trace/trace.c:trace_find_cmdline
  - kernel/trace/trace.c:ftrace_exports
```
```
In kernel/trace/trace_functions.c (ffffffff812919c5)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8129345c)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
  - kernel/trace/trace_sched_wakeup.c:func_prolog_preempt_disable
```
```
In kernel/trace/trace_osnoise.c (ffffffff8129790f)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/trace/trace_osnoise.c:trace_sched_switch_callback
  - kernel/trace/trace_osnoise.c:trace_softirq_exit_callback
  - kernel/trace/trace_osnoise.c:osnoise_trace_irq_exit
  - kernel/trace/trace_osnoise.c:trace_osnoise_callback
```
```
In kernel/trace/trace_stack.c (ffffffff8129a420)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:stack_trace_call
```
```
In kernel/trace/trace_mmiotrace.c (ffffffff8129b107)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
```
```
In kernel/trace/trace_functions_graph.c (ffffffff8129be9c)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/blktrace.c (ffffffff812a023f)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/blktrace.c:trace_note
```
```
In kernel/trace/trace_events.c (ffffffff812a469a)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:np_start
  - kernel/trace/trace_events.c:p_start
```
```
In kernel/trace/trace_event_perf.c (ffffffff812a98f9)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_ftrace_function_call
```
```
In kernel/trace/trace_events_inject.c (ffffffff812b28cd)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/trace/trace_events_inject.c:trace_inject_entry
```
```
In kernel/trace/trace_events_user.c (ffffffff812c5fea)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/trace/trace_events_user.c:update_enable_bit_for
```
```
In kernel/trace/bpf_trace.c (ffffffff812ca492)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:get_modules_for_addrs
  - kernel/trace/bpf_trace.c:bpf_put_raw_tracepoint
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_tp
  - kernel/trace/bpf_trace.c:bpf_event_output
  - kernel/trace/bpf_trace.c:bpf_perf_event_output
  - kernel/trace/bpf_trace.c:bpf_trace_vprintk
  - kernel/trace/bpf_trace.c:bpf_trace_printk
```
```
In kernel/trace/trace_kprobe.c (ffffffff812ce6cc)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:append_trace_kprobe
```
```
In kernel/trace/trace_uprobe.c (ffffffff812db6af)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:__uprobe_perf_func
```
```
In kernel/trace/fprobe.c (ffffffff812ddd6b)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In kernel/trace/rethook.c (ffffffff812df1aa)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/trace/rethook.c:rethook_trampoline_handler
  - kernel/trace/rethook.c:rethook_flush_task
```
```
In kernel/trace/rv/monitors/wwnr/wwnr.c (ffffffff812e3c53)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/trace/rv/monitors/wwnr/wwnr.c:da_event_wwnr
  - kernel/trace/rv/monitors/wwnr/wwnr.c:da_event_wwnr
```
```
In kernel/irq_work.c (ffffffff812e4f8a)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_queue_on
```
```
In kernel/bpf/core.c (ffffffff812eaae5)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_user_rnd_u32
```
```
In kernel/bpf/helpers.c (ffffffff8131fe1a)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_bprintf_prepare
  - kernel/bpf/helpers.c:copy_map_value_locked
```
```
In kernel/bpf/hashtab.c (ffffffff8132a5f0)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_elem
  - kernel/bpf/hashtab.c:htab_lru_map_delete_elem
  - kernel/bpf/hashtab.c:htab_map_delete_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:__htab_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_delete_node
```
```
In kernel/bpf/devmap.c (ffffffff8134ebca)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_generic_redirect
  - kernel/bpf/devmap.c:bq_xmit_all
  - kernel/bpf/devmap.c:dev_map_bpf_prog_run
```
```
In kernel/bpf/cpumap.c (ffffffff81350983)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_generic_redirect
  - kernel/bpf/cpumap.c:bq_flush_to_queue
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_skb
```
```
In kernel/bpf/offload.c (ffffffff81351245)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In kernel/static_call_inline.c (ffffffff813646ae)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/static_call_inline.c:static_call_text_reserved
```
```
In kernel/events/core.c (ffffffff81373b45)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_cgroup_move
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_task
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:perf_event_read
```
```
In kernel/events/ring_buffer.c (ffffffff8137c419)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
```
```
In kernel/events/hw_breakpoint.c (ffffffff8137dbe2)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff813830a5)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_end_dup_mmap
  - kernel/events/uprobes.c:uprobe_start_dup_mmap
  - kernel/events/uprobes.c:__update_ref_ctr
  - kernel/events/uprobes.c:copy_to_page
  - kernel/events/uprobes.c:copy_from_page
```
```
In kernel/user-return-notifier.c (ffffffff81384435)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/user-return-notifier.c:fire_user_return_notifiers
```
```
In kernel/padata.c (ffffffff81384a92)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:invoke_padata_reorder
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_parallel_worker
```
```
In kernel/jump_label.c (ffffffff813862fd)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_update
  - kernel/jump_label.c:jump_label_text_reserved
  - kernel/jump_label.c:jump_label_add_module
```
```
In kernel/rseq.c (ffffffff81388790)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/rseq.c:rseq_ip_fixup
  - kernel/rseq.c:rseq_ip_fixup
  - kernel/rseq.c:rseq_update_cpu_node_id
```
```
In kernel/watch_queue.c (ffffffff81388bbc)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In mm/filemap.c (ffffffff8138ec13)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:file_check_and_advance_wb_err
  - mm/filemap.c:__filemap_set_wb_err
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__filemap_remove_folio
```
```
In mm/oom_kill.c (ffffffff813956d3)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - mm/oom_kill.c:mark_oom_victim
  - mm/oom_kill.c:wake_oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
```
```
In mm/page-writeback.c (ffffffff813994c7)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - mm/page-writeback.c:folio_wait_writeback_killable
  - mm/page-writeback.c:folio_wait_writeback
  - mm/page-writeback.c:folio_account_dirtied
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:balance_dirty_pages_ratelimited_flags
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:wb_update_dirty_ratelimit
  - mm/page-writeback.c:domain_dirty_limits
```
```
In mm/swap.c (ffffffff813a2f40)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - mm/swap.c:__folio_batch_release
  - mm/swap.c:lru_add_drain_per_cpu
  - mm/swap.c:lru_add_drain_cpu_zone
  - mm/swap.c:folio_mark_lazyfree
  - mm/swap.c:folio_deactivate
  - mm/swap.c:deactivate_file_folio
  - mm/swap.c:folio_add_lru
  - mm/swap.c:folio_mark_accessed
  - mm/swap.c:lru_add_fn
```
```
In mm/vmscan.c (ffffffff813b9355)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - mm/vmscan.c:__node_reclaim
  - mm/vmscan.c:__node_reclaim
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:mem_cgroup_shrink_node
  - mm/vmscan.c:mem_cgroup_shrink_node
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:isolate_lru_folios
  - mm/vmscan.c:pageout
  - mm/vmscan.c:reclaim_throttle
  - mm/vmscan.c:do_shrink_slab
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/shmem.c (ffffffff813bbd26)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In mm/util.c (ffffffff813c4a35)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - mm/util.c:memcmp_pages
  - mm/util.c:memcmp_pages
```
```
In mm/backing-dev.c (ffffffff813cbe7e)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_register_va
```
```
In mm/percpu.c (ffffffff813ceddd)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_free
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
```
```
In mm/slab_common.c (ffffffff813d4d4d)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_large_node
  - mm/slab_common.c:kmalloc_large
  - mm/slab_common.c:kmalloc_node_trace
  - mm/slab_common.c:kmalloc_trace
  - mm/slab_common.c:kfree
  - mm/slab_common.c:__kmalloc_node_track_caller
  - mm/slab_common.c:__kmalloc_node_track_caller
  - mm/slab_common.c:__kmalloc
  - mm/slab_common.c:__kmalloc
  - mm/slab_common.c:__kmalloc_node
  - mm/slab_common.c:__kmalloc_node
```
```
In mm/compaction.c (ffffffff813dcf78)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
  - mm/compaction.c:wakeup_kcompactd
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compaction_suitable
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:compaction_defer_reset
  - mm/compaction.c:compaction_deferred
  - mm/compaction.c:defer_compaction
```
```
In mm/mmap_lock.c (ffffffff813e8d55)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - mm/mmap_lock.c:__mmap_lock_do_trace_released
  - mm/mmap_lock.c:__mmap_lock_do_trace_released
  - mm/mmap_lock.c:__mmap_lock_do_trace_acquire_returned
  - mm/mmap_lock.c:__mmap_lock_do_trace_acquire_returned
  - mm/mmap_lock.c:__mmap_lock_do_trace_start_locking
  - mm/mmap_lock.c:__mmap_lock_do_trace_start_locking
```
```
In mm/memory.c (ffffffff813efe27)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - mm/memory.c:do_set_pte
  - mm/memory.c:do_set_pmd
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:__wp_page_copy_user
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mlock.c (ffffffff813f9455)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - mm/mlock.c:munlock_folio
  - mm/mlock.c:mlock_new_folio
  - mm/mlock.c:mlock_folio
  - mm/mlock.c:mlock_drain_local
```
```
In mm/mmap.c (ffffffff813fe611)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:vm_unmapped_area
```
```
In mm/rmap.c (ffffffff8140e37d)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
```
```
In mm/vmalloc.c (ffffffff81410fa3)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:alloc_vmap_area
```
```
In mm/page_alloc.c (ffffffff8142198f)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:free_unref_page
  - mm/page_alloc.c:free_unref_page_prepare
  - mm/page_alloc.c:rmqueue_bulk
  - mm/page_alloc.c:rmqueue_bulk
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcppages_bulk
```
```
In mm/memory_hotplug.c (ffffffff81424c22)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
```
```
In mm/swapfile.c (ffffffff8142efdd)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:swp_swapcount
```
```
In mm/zswap.c (ffffffff81436893)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/hugetlb.c (0)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In mm/mempolicy.c (ffffffff81448270)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_page_interleave
```
```
In mm/ksm.c (ffffffff81457c51)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:__ksm_enter
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:calc_checksum
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:remove_node_from_stable_tree
```
```
In mm/page_poison.c (ffffffff81458811)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - mm/page_poison.c:__kernel_unpoison_pages
  - mm/page_poison.c:__kernel_poison_pages
```
```
In mm/slub.c (ffffffff81461f54)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:__kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_lru
  - mm/slub.c:kmem_cache_alloc_lru
  - mm/slub.c:kmem_cache_alloc
  - mm/slub.c:kmem_cache_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:__unfreeze_partials
```
```
In mm/kfence/core.c (ffffffff814647f5)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_init_pool
```
```
In mm/kfence/report.c (ffffffff81466902)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - mm/kfence/report.c:kfence_report_error
```
```
In mm/migrate.c (ffffffff8146b517)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff81479684)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:mm_get_huge_zero_page
```
```
In mm/khugepaged.c (ffffffff81480d1f)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:hpage_collapse_scan_pmd
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (ffffffff81490134)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_flush_foreign
  - mm/memcontrol.c:mem_cgroup_track_foreign_dirty_slowpath
```
```
In mm/memory-failure.c (ffffffff81494675)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure_queue
  - mm/memory-failure.c:action_result
```
```
In mm/page_isolation.c (ffffffff8149b2d0)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
```
```
In mm/zsmalloc.c (ffffffff8149e127)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:obj_free
  - mm/zsmalloc.c:obj_malloc
  - mm/zsmalloc.c:zs_map_object
  - mm/zsmalloc.c:zs_map_object
  - mm/zsmalloc.c:__zs_map_object
  - mm/zsmalloc.c:__zs_map_object
  - mm/zsmalloc.c:alloc_zspage
```
```
In fs/open.c (ffffffff814a90fb)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
  - fs/open.c:vfs_fallocate
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:do_sys_ftruncate
```
```
In fs/read_write.c (ffffffff814b098e)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_write
  - fs/read_write.c:vfs_write
```
```
In fs/exec.c (ffffffff814b8aa5)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/exec.c:exec_binprm
  - fs/exec.c:__set_task_comm
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
```
```
In fs/pipe.c (ffffffff814bc7dd)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
```
```
In fs/dcache.c (ffffffff814d376c)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_unhash
  - fs/dcache.c:__d_lookup_unhash
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
```
```
In fs/inode.c (ffffffff814da297)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/inode.c:touch_atime
  - fs/inode.c:touch_atime
  - fs/inode.c:get_next_ino
```
```
In fs/file.c (ffffffff814db6b7)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/file.c:fd_install
```
```
In fs/namespace.c (ffffffff814dfcef)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write
  - fs/namespace.c:mnt_drop_write
  - fs/namespace.c:mnt_want_write
  - fs/namespace.c:mnt_want_write
  - fs/namespace.c:__mnt_want_write
```
```
In fs/fs-writeback.c (ffffffff814f6b97)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_do_writeback
  - fs/fs-writeback.c:wb_writeback
  - fs/fs-writeback.c:wb_writeback
  - fs/fs-writeback.c:wb_writeback
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fs-writeback.c:write_inode
  - fs/fs-writeback.c:write_inode
  - fs/fs-writeback.c:queue_io
  - fs/fs-writeback.c:sb_clear_inode_writeback
  - fs/fs-writeback.c:sb_mark_inode_writeback
  - fs/fs-writeback.c:wb_start_background_writeback
  - fs/fs-writeback.c:wbc_detach_inode
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:wb_queue_work
```
```
In fs/splice.c (ffffffff814fd4ec)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
```
```
In fs/fs_struct.c (0)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In fs/remap_range.c (ffffffff815075fd)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_clone_file_range
  - fs/remap_range.c:vfs_clone_file_range
```
```
In fs/buffer.c (ffffffff815088b5)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/buffer.c:free_buffer_head
  - fs/buffer.c:alloc_buffer_head
  - fs/buffer.c:invalidate_bh_lru
  - fs/buffer.c:mark_buffer_dirty
```
```
In fs/userfaultfd.c (0)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In fs/aio.c (ffffffff81528543)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/aio.c:aio_write
  - fs/aio.c:aio_complete_rw
```
```
In fs/dax.c (ffffffff81531b45)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pte_fault
  - fs/dax.c:dax_iomap_pte_fault
  - fs/dax.c:dax_fault_iter
  - fs/dax.c:dax_fault_cow_page
  - fs/dax.c:dax_pmd_load_hole
  - fs/dax.c:dax_pmd_load_hole
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_one
```
```
In fs/locks.c (ffffffff815457d4)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/locks.c:locks_remove_file
  - fs/locks.c:locks_remove_file
  - fs/locks.c:locks_remove_posix
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:generic_setlease
  - fs/locks.c:generic_setlease
  - fs/locks.c:generic_setlease
  - fs/locks.c:generic_add_lease
  - fs/locks.c:generic_add_lease
  - fs/locks.c:generic_add_lease
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:leases_conflict
  - fs/locks.c:time_out_leases
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:locks_get_lock_context
```
```
In fs/mbcache.c (ffffffff8154c95b)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:__mb_cache_entry_free
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/coredump.c (ffffffff81551030)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
```
```
In fs/iomap/iter.c (ffffffff81553c83)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/iomap/iter.c:iomap_iter
  - fs/iomap/iter.c:iomap_iter_done
  - fs/iomap/iter.c:iomap_iter_done
```
```
In fs/iomap/buffered-io.c (ffffffff81556180)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_do_writepage
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/iomap/buffered-io.c:iomap_release_folio
  - fs/iomap/buffered-io.c:iomap_readahead
  - fs/iomap/buffered-io.c:iomap_read_folio
```
```
In fs/iomap/direct-io.c (ffffffff8155897d)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:__iomap_dio_rw
  - fs/iomap/direct-io.c:__iomap_dio_rw
  - fs/iomap/direct-io.c:__iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_complete
```
```
In fs/quota/quota.c (ffffffff8156094e)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/quota/quota.c:quotactl_block
  - fs/quota/quota.c:quotactl_block
```
```
In fs/proc/base.c (ffffffff8156e817)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In fs/ext4/balloc.c (ffffffff8158ff49)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ext4_jbd2.c (ffffffff81593014)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb
```
```
In fs/ext4/extents.c (ffffffff8159a250)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/extents_status.c (ffffffff815a137a)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_insert_delayed_block
  - fs/ext4/extents_status.c:ext4_es_scan
  - fs/ext4/extents_status.c:ext4_es_scan
  - fs/ext4/extents_status.c:ext4_es_count
  - fs/ext4/extents_status.c:ext4_es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_cache_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_find_extent_range
  - fs/ext4/extents_status.c:ext4_es_find_extent_range
```
```
In fs/ext4/file.c (ffffffff815a176c)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_sample_last_mounted
  - fs/ext4/file.c:ext4_sample_last_mounted
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/fsmap.c (ffffffff815a412f)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/fsmap.c:ext4_getfsmap_logdev
  - fs/ext4/fsmap.c:ext4_getfsmap_logdev
  - fs/ext4/fsmap.c:ext4_getfsmap_helper
  - fs/ext4/fsmap.c:ext4_getfsmap_helper
```
```
In fs/ext4/fsync.c (ffffffff815a47d5)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/ialloc.c (ffffffff815a7555)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff815aa4bc)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inode.c (ffffffff815bc5a9)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_update_other_inode_time
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_release_folio
  - fs/ext4/inode.c:__ext4_journalled_invalidate_folio
  - fs/ext4/inode.c:ext4_invalidate_folio
  - fs/ext4/inode.c:ext4_read_folio
  - fs/ext4/inode.c:ext4_alloc_da_blocks
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_do_writepages
  - fs/ext4/inode.c:ext4_do_writepages
  - fs/ext4/inode.c:ext4_do_writepages
  - fs/ext4/inode.c:mpage_map_one_extent
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_da_reserve_space
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (ffffffff815bd6b9)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioc_getfsmap
  - fs/ext4/ioctl.c:ext4_ioc_getfsmap
  - fs/ext4/ioctl.c:ext4_getfsmap_format
  - fs/ext4/ioctl.c:ext4_force_shutdown
  - fs/ext4/ioctl.c:ext4_update_backup_sb
  - fs/ext4/ioctl.c:ext4_update_primary_sb
```
```
In fs/ext4/mballoc.c (ffffffff815c7f3b)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_preallocations_should_retry
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_collect_stats
  - fs/ext4/mballoc.c:ext4_mb_collect_stats
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/mmp.c (ffffffff815cee07)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/namei.c (ffffffff815d9700)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_unlink
  - fs/ext4/namei.c:ext4_unlink
```
```
In fs/ext4/super.c (ffffffff815f7ecc)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:ext4_run_li_request
  - fs/ext4/super.c:ext4_run_li_request
  - fs/ext4/super.c:ext4_nfs_commit_metadata
  - fs/ext4/super.c:ext4_drop_inode
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
```
```
In fs/ext4/fast_commit.c (ffffffff8160f64a)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
  - fs/ext4/fast_commit.c:ext4_fc_commit
  - fs/ext4/fast_commit.c:ext4_fc_update_stats
  - fs/ext4/fast_commit.c:ext4_fc_track_range
  - fs/ext4/fast_commit.c:ext4_fc_track_inode
  - fs/ext4/fast_commit.c:__ext4_fc_track_create
  - fs/ext4/fast_commit.c:__ext4_fc_track_link
  - fs/ext4/fast_commit.c:__ext4_fc_track_unlink
```
```
In fs/jbd2/transaction.c (ffffffff81614d0c)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:jbd2_freeze_jh_data
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
  - fs/jbd2/transaction.c:jbd2__journal_start
```
```
In fs/jbd2/commit.c (ffffffff816172c7)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (ffffffff8161a020)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_drop_transaction
  - fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_journal_shrink_checkpoint_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff81623a14)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_journal_shrink_count
  - fs/jbd2/journal.c:jbd2_journal_shrink_scan
  - fs/jbd2/journal.c:jbd2_journal_shrink_scan
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/squashfs/file.c (ffffffff8162752a)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_read_folio
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (ffffffff81629a60)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_read_folio
```
```
In fs/squashfs/decompressor_multi_percpu.c (ffffffff8162af66)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/squashfs/decompressor_multi_percpu.c:squashfs_decompress
```
```
In fs/ecryptfs/mmap.c (ffffffff81644396)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
```
In fs/ecryptfs/read_write.c (ffffffff81645495)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dax.c (ffffffff81669571)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - fs/fuse/dax.c:__fuse_dax_fault
  - fs/fuse/dax.c:__fuse_dax_fault
```
```
In ipc/util.c (ffffffff81674a00)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In security/selinux/avc.c (ffffffff816a42da)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_audit_post_callback
```
```
In security/smack/smack_lsm.c (ffffffff816d7c3f)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smk_ipv4_check
  - security/smack/smack_lsm.c:smack_netlbl_add
```
```
In security/tomoyo/domain.c (ffffffff816ea285)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In security/apparmor/capability.c (ffffffff816faca7)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - security/apparmor/capability.c:audit_caps
```
```
In security/apparmor/policy_unpack.c (ffffffff8170a0a9)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In security/apparmor/lsm.c (ffffffff817145b8)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - security/apparmor/lsm.c:aa_put_buffer
  - security/apparmor/lsm.c:aa_put_buffer
  - security/apparmor/lsm.c:aa_put_buffer
  - security/apparmor/lsm.c:aa_get_buffer
  - security/apparmor/lsm.c:aa_get_buffer
  - security/apparmor/lsm.c:aa_get_buffer
```
```
In block/bio.c (ffffffff8176a418)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - block/bio.c:bio_endio
  - block/bio.c:bio_put_percpu_cache
  - block/bio.c:bio_alloc_bioset
```
```
In block/blk-core.c (ffffffff81772595)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - block/blk-core.c:bdev_end_io_acct
  - block/blk-core.c:bio_start_io_acct
  - block/blk-core.c:submit_bio_noacct
  - block/blk-core.c:submit_bio_noacct_nocheck
```
```
In block/blk-flush.c (ffffffff81774ffc)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-merge.c (ffffffff8177ae6f)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_front_merge
  - block/blk-merge.c:bio_attempt_back_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:__bio_split_to_limits
```
```
In block/blk-mq.c (ffffffff81783892)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - block/blk-mq.c:blk_insert_cloned_request
  - block/blk-mq.c:blk_insert_cloned_request
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_dispatch_plug_list
  - block/blk-mq.c:blk_mq_insert_request
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:blk_execute_rq
  - block/blk-mq.c:blk_execute_rq
  - block/blk-mq.c:blk_execute_rq_nowait
  - block/blk-mq.c:blk_execute_rq_nowait
  - block/blk-mq.c:blk_add_rq_to_plug
  - block/blk-mq.c:blk_add_rq_to_plug
  - block/blk-mq.c:blk_mq_start_request
  - block/blk-mq.c:blk_mq_complete_request_remote
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:blk_account_io_done
  - block/blk-mq.c:blk_account_io_done
  - block/blk-mq.c:blk_update_request
  - block/blk-mq.c:blk_update_request
```
```
In block/blk-stat.c (ffffffff81788dfb)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_add
```
```
In block/genhd.c (ffffffff8178de60)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - block/genhd.c:diskstats_show
  - block/genhd.c:part_stat_show
```
```
In block/blk-cgroup.c (ffffffff817a2bdc)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - block/blk-cgroup.c:blk_cgroup_bio_start
```
```
In block/blk-iocost.c (ffffffff817b0b2b)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:adjust_inuse_and_calc_cost
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_forgive_debts
  - block/blk-iocost.c:transfer_surpluses
  - block/blk-iocost.c:iocg_wake_fn
  - block/blk-iocost.c:iocg_incur_debt
  - block/blk-iocost.c:iocg_activate
```
```
In block/mq-deadline.c (ffffffff817b40d6)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In block/blk-wbt.c (ffffffff817bac86)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:rwb_trace_step
```
```
In io_uring/io_uring.c (ffffffff817cda53)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - io_uring/io_uring.c:__do_sys_io_uring_register
  - io_uring/io_uring.c:io_uring_create
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/io_uring.c:io_submit_sqes
  - io_uring/io_uring.c:io_submit_sqes
  - io_uring/io_uring.c:io_submit_fail_init
  - io_uring/io_uring.c:io_file_get_normal
  - io_uring/io_uring.c:io_drain_req
  - io_uring/io_uring.c:__io_run_local_work
  - io_uring/io_uring.c:tctx_task_work
  - io_uring/io_uring.c:io_fill_cqe_aux
  - io_uring/io_uring.c:io_cqring_event_overflow
  - io_uring/io_uring.c:io_queue_iowq
  - io_uring/io_uring.c:__io_fill_cqe_req
```
```
In io_uring/timeout.c (ffffffff817da675)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - io_uring/timeout.c:io_disarm_next
```
```
In io_uring/poll.c (ffffffff817ded41)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - io_uring/poll.c:io_arm_poll_handler
  - io_uring/poll.c:__io_poll_execute
```
```
In io_uring/rw.c (ffffffff817e5b6e)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - io_uring/rw.c:io_write
  - io_uring/rw.c:io_write
  - io_uring/rw.c:__io_fill_cqe_req
```
```
In lib/scatterlist.c (ffffffff8180db03)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In lib/iov_iter.c (ffffffff81813ee9)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - lib/iov_iter.c:copy_page_from_iter_atomic
```
```
In lib/rhashtable.c (ffffffff81819682)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In lib/irq_poll.c (ffffffff818e0fa0)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_cpu_dead
```
```
In arch/x86/lib/msr-smp.c (ffffffff818e88e6)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:wrmsr_on_cpus
  - arch/x86/lib/msr-smp.c:rdmsr_on_cpus
```
```
In arch/x86/lib/msr.c (ffffffff818e93c9)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:do_trace_rdpmc
  - arch/x86/lib/msr.c:do_trace_read_msr
  - arch/x86/lib/msr.c:do_trace_write_msr
```
```
In drivers/gpio/gpiolib.c (ffffffff81902f1f)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_source_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_drain_value_commit
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_input
```
```
In drivers/pwm/core.c (ffffffff819129b4)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwm_apply_state
  - drivers/pwm/core.c:pwm_device_request
```
```
In drivers/pci/pcie/aer.c (ffffffff819400f8)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:cper_print_aer
  - drivers/pci/pcie/aer.c:aer_print_error
```
```
In drivers/acpi/sleep.c (ffffffff8199eedc)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_suspend_enter
  - drivers/acpi/sleep.c:acpi_suspend_enter
```
```
In drivers/acpi/prmt.c (ffffffff819c096b)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/acpi/prmt.c:acpi_platformrt_space_handler
```
```
In drivers/clk/clk.c (ffffffff81a4190f)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_set_duty_cycle_nolock
  - drivers/clk/clk.c:clk_core_set_duty_cycle_nolock
  - drivers/clk/clk.c:clk_core_set_phase_nolock
  - drivers/clk/clk.c:clk_core_set_phase_nolock
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_calc_new_rates
  - drivers/clk/clk.c:clk_calc_new_rates
  - drivers/clk/clk.c:clk_round_rate
  - drivers/clk/clk.c:clk_round_rate
  - drivers/clk/clk.c:clk_hw_round_rate
  - drivers/clk/clk.c:clk_hw_round_rate
  - drivers/clk/clk.c:clk_core_round_rate_nolock
  - drivers/clk/clk.c:clk_core_round_rate_nolock
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_unprepare_unused_subtree
  - drivers/clk/clk.c:clk_unprepare_unused_subtree
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/clk/clk.c:clk_core_prepare
  - drivers/clk/clk.c:clk_core_prepare
  - drivers/clk/clk.c:clk_core_unprepare
  - drivers/clk/clk.c:clk_core_unprepare
  - drivers/clk/clk.c:clk_mux_determine_rate_flags
  - drivers/clk/clk.c:clk_mux_determine_rate_flags
```
```
In drivers/xen/events/events_2l.c (ffffffff81a6bd2a)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81a7a8a6)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
```
```
In drivers/regulator/core.c (ffffffff81a8520f)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
```
```
In drivers/char/random.c (ffffffff81ae06af)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/char/random.c:try_to_generate_entropy
```
```
In drivers/char/virtio_console.c (ffffffff81ae1b68)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/iommu/intel/dmar.c (ffffffff81b0ad27)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:qi_submit_sync
```
```
In drivers/iommu/intel/svm.c (ffffffff81b16d04)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:prq_event_thread
```
```
In drivers/iommu/iommu.c (ffffffff81b1dc9e)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:report_iommu_fault
  - drivers/iommu/iommu.c:__iommu_unmap
  - drivers/iommu/iommu.c:__iommu_map
  - drivers/iommu/iommu.c:iommu_group_add_device
  - drivers/iommu/iommu.c:__iommu_group_release_device
```
```
In drivers/connector/cn_proc.c (ffffffff81b2c151)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/connector/cn_proc.c:proc_exit_connector
  - drivers/connector/cn_proc.c:proc_coredump_connector
  - drivers/connector/cn_proc.c:proc_comm_connector
  - drivers/connector/cn_proc.c:proc_ptrace_connector
  - drivers/connector/cn_proc.c:proc_sid_connector
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/connector/cn_proc.c:proc_exec_connector
  - drivers/connector/cn_proc.c:proc_fork_connector
```
```
In drivers/base/syscore.c (ffffffff81b3a09d)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
```
```
In drivers/base/devres.c (ffffffff81b3fdc3)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/base/devres.c:__devm_alloc_percpu
  - drivers/base/devres.c:devm_krealloc
  - drivers/base/devres.c:__devm_add_action
  - drivers/base/devres.c:devres_remove_group
  - drivers/base/devres.c:devres_close_group
  - drivers/base/devres.c:devres_open_group
  - drivers/base/devres.c:release_nodes
  - drivers/base/devres.c:devres_remove
  - drivers/base/devres.c:devres_get
```
```
In drivers/base/power/qos.c (ffffffff81b4c8d1)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/base/power/qos.c:__dev_pm_qos_remove_request
  - drivers/base/power/qos.c:__dev_pm_qos_update_request
  - drivers/base/power/qos.c:__dev_pm_qos_add_request
```
```
In drivers/base/power/runtime.c (ffffffff81b4fbcc)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:update_autosuspend
  - drivers/base/power/runtime.c:pm_runtime_allow
  - drivers/base/power/runtime.c:pm_runtime_get_if_active
  - drivers/base/power/runtime.c:__pm_runtime_suspend
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
```
```
In drivers/base/power/main.c (ffffffff81b555b2)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/base/power/main.c:dpm_run_callback
  - drivers/base/power/main.c:dpm_run_callback
```
```
In drivers/base/power/wakeup.c (ffffffff81b56827)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_activate
```
```
In drivers/base/regmap/regmap.c (ffffffff81b695fc)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_async_complete_cb
  - drivers/base/regmap/regmap.c:regmap_bulk_read
  - drivers/base/regmap/regmap.c:_regmap_read
  - drivers/base/regmap/regmap.c:_regmap_raw_read
  - drivers/base/regmap/regmap.c:_regmap_raw_read
  - drivers/base/regmap/regmap.c:_regmap_raw_multi_reg_write
  - drivers/base/regmap/regmap.c:_regmap_raw_multi_reg_write
  - drivers/base/regmap/regmap.c:regmap_bulk_write
  - drivers/base/regmap/regmap.c:_regmap_write
  - drivers/base/regmap/regmap.c:_regmap_bus_formatted_write
  - drivers/base/regmap/regmap.c:_regmap_bus_formatted_write
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
```
```
In drivers/base/regmap/regcache.c (ffffffff81b6f64e)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/base/regmap/regcache.c:regcache_cache_bypass
  - drivers/base/regmap/regcache.c:regcache_cache_only
  - drivers/base/regmap/regcache.c:regcache_drop_region
  - drivers/base/regmap/regcache.c:regcache_sync_region
  - drivers/base/regmap/regcache.c:regcache_sync_region
  - drivers/base/regmap/regcache.c:regcache_sync
  - drivers/base/regmap/regcache.c:regcache_sync
  - drivers/base/regmap/regcache.c:regcache_read
```
```
In drivers/block/loop.c (ffffffff81b7c340)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In drivers/block/xen-blkfront.c (ffffffff81b842a7)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_completion
  - drivers/block/xen-blkfront.c:blkif_copy_from_grant
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/nvdimm/region_devs.c (ffffffff81ba80d0)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_release_lane
  - drivers/nvdimm/region_devs.c:nd_region_acquire_lane
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81bbf9ca)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:__dma_fence_enable_signaling
  - drivers/dma-buf/dma-fence.c:dma_fence_release
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_signal_timestamp_locked
  - drivers/dma-buf/dma-fence.c:dma_fence_allocate_private_stub
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81bc58e9)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
```
```
In drivers/scsi/scsi_error.c (ffffffff81bcf88b)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_timeout
```
```
In drivers/scsi/scsi_lib.c (ffffffff81bd1df4)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
  - drivers/scsi/scsi_lib.c:scsi_done_internal
  - drivers/scsi/scsi_lib.c:scsi_dispatch_cmd
  - drivers/scsi/scsi_lib.c:scsi_dispatch_cmd
```
```
In drivers/scsi/sd_zbc.c (ffffffff81becaa5)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_zone_wp_update
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
```
```
In drivers/ata/libata-core.c (ffffffff81bfe7b0)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-core.c:ata_qc_complete
  - drivers/ata/libata-core.c:ata_qc_complete
  - drivers/ata/libata-core.c:ata_qc_complete
```
```
In drivers/ata/libata-eh.c (ffffffff81c11300)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_done
  - drivers/ata/libata-eh.c:ata_eh_about_to_do
  - drivers/ata/libata-eh.c:__ata_port_freeze
```
```
In drivers/ata/libata-sff.c (ffffffff81c19c34)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_bmdma_post_internal_cmd
  - drivers/ata/libata-sff.c:ata_bmdma_error_handler
  - drivers/ata/libata-sff.c:ata_bmdma_error_handler
  - drivers/ata/libata-sff.c:ata_bmdma_port_intr
  - drivers/ata/libata-sff.c:ata_bmdma_port_intr
  - drivers/ata/libata-sff.c:ata_bmdma_qc_issue
  - drivers/ata/libata-sff.c:ata_bmdma_qc_issue
  - drivers/ata/libata-sff.c:ata_bmdma_qc_issue
  - drivers/ata/libata-sff.c:ata_bmdma_qc_issue
  - drivers/ata/libata-sff.c:ata_bmdma_qc_issue
  - drivers/ata/libata-sff.c:__ata_sff_port_intr
  - drivers/ata/libata-sff.c:ata_sff_flush_pio_task
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:__atapi_pio_bytes
  - drivers/ata/libata-sff.c:__atapi_pio_bytes
  - drivers/ata/libata-sff.c:ata_pio_sector
  - drivers/ata/libata-sff.c:ata_tf_to_host
  - drivers/ata/libata-sff.c:ata_tf_to_host
```
```
In drivers/ata/ata_piix.c (ffffffff81c205e7)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/ata/ata_piix.c:piix_irq_check
```
```
In drivers/spi/spi.c (ffffffff81c2da3f)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_sync
  - drivers/spi/spi.c:__spi_sync
  - drivers/spi/spi.c:__spi_sync
  - drivers/spi/spi.c:__spi_sync
  - drivers/spi/spi.c:__spi_sync
  - drivers/spi/spi.c:__spi_async
  - drivers/spi/spi.c:__spi_async
  - drivers/spi/spi.c:__spi_async
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:__spi_split_transfer_maxsize
  - drivers/spi/spi.c:__spi_split_transfer_maxsize
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_transfer_message
  - drivers/spi/spi.c:__spi_pump_transfer_message
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_set_cs
  - drivers/spi/spi.c:spi_statistics_add_transfer_stats
```
```
In drivers/net/phy/mdio_bus.c (ffffffff81c3ebf4)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:__mdiobus_c45_write
  - drivers/net/phy/mdio_bus.c:__mdiobus_c45_write
  - drivers/net/phy/mdio_bus.c:__mdiobus_c45_read
  - drivers/net/phy/mdio_bus.c:__mdiobus_c45_read
  - drivers/net/phy/mdio_bus.c:__mdiobus_write
  - drivers/net/phy/mdio_bus.c:__mdiobus_write
  - drivers/net/phy/mdio_bus.c:__mdiobus_read
  - drivers/net/phy/mdio_bus.c:__mdiobus_read
```
```
In drivers/net/tun.c (ffffffff81c4b997)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_xdp_act
  - drivers/net/tun.c:tun_napi_alloc_frags
```
```
In drivers/net/virtio_net.c (ffffffff81c544a1)
Location: arch/x86/include/asm/preempt.h:78
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
  - drivers/net/virtio_net.c:virtnet_xdp_handler
  - drivers/net/virtio_net.c:virtnet_xdp_handler
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81c63c15)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
```
```
In drivers/net/xen-netfront.c (ffffffff81c6d06d)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:netfront_resume
```
```
In drivers/net/net_failover.c (ffffffff81c6fb3e)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/net/net_failover.c:net_failover_slave_register
  - drivers/net/net_failover.c:net_failover_close
  - drivers/net/net_failover.c:net_failover_open
```
```
In drivers/usb/host/xhci.c (ffffffff81ce5922)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81ce945a)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_ring_alloc
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81ced269)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:queue_trb
  - drivers/usb/host/xhci-ring.c:xhci_handle_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_port_status
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_ring_ep_doorbell
  - drivers/usb/host/xhci-ring.c:inc_enq
  - drivers/usb/host/xhci-ring.c:inc_deq
```
```
In drivers/usb/host/xhci-hub.c (ffffffff81cf720a)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81cff3c4)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events
  - drivers/usb/host/xhci-dbgcap.c:dbc_handle_xfer_event
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_queue_bulk_tx
  - drivers/usb/host/xhci-dbgcap.c:dbc_free_request
  - drivers/usb/host/xhci-dbgcap.c:dbc_alloc_request
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
```
```
In drivers/rtc/interface.c (ffffffff81d24da7)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_set_offset
  - drivers/rtc/interface.c:rtc_read_offset
  - drivers/rtc/interface.c:rtc_timer_cancel
  - drivers/rtc/interface.c:rtc_timer_start
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_alarm_disable
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_irq_set_freq
  - drivers/rtc/interface.c:rtc_irq_set_state
  - drivers/rtc/interface.c:rtc_update_irq_enable
  - drivers/rtc/interface.c:rtc_alarm_irq_enable
  - drivers/rtc/interface.c:rtc_initialize_alarm
  - drivers/rtc/interface.c:__rtc_set_alarm
  - drivers/rtc/interface.c:rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:rtc_read_time
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81d2cf1b)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff81d30bf8)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In drivers/hwmon/hwmon.c (ffffffff81d43ddf)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:hwmon_attr_store
  - drivers/hwmon/hwmon.c:hwmon_attr_show_string
  - drivers/hwmon/hwmon.c:hwmon_attr_show
```
```
In drivers/thermal/thermal_core.c (ffffffff81d47656)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In drivers/thermal/thermal_helpers.c (ffffffff81d4c2f4)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/thermal/thermal_helpers.c:__thermal_cdev_update
```
```
In drivers/thermal/gov_fair_share.c (ffffffff81d4ec42)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/thermal/gov_fair_share.c:fair_share_throttle
```
```
In drivers/thermal/gov_step_wise.c (ffffffff81d4f260)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/thermal/gov_step_wise.c:thermal_zone_trip_update
```
```
In drivers/thermal/gov_power_allocator.c (ffffffff81d50a98)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/thermal/gov_power_allocator.c:allocate_power
  - drivers/thermal/gov_power_allocator.c:pid_controller
```
```
In drivers/thermal/devfreq_cooling.c (ffffffff81d5189b)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_power2state
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power
```
```
In drivers/thermal/intel/therm_throt.c (ffffffff81d51da4)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_package_throttle_total_time_ms
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_core_throttle_total_time_ms
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_package_throttle_max_time_ms
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_core_throttle_max_time_ms
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_package_power_limit_count
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_package_throttle_count
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_core_power_limit_count
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_core_throttle_count
```
```
In drivers/watchdog/watchdog_core.c (ffffffff81d53fab)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_core.c:watchdog_reboot_notifier
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81d56276)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_stop
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
```
```
In drivers/md/md.c (ffffffff81d5a7f3)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/md/md.c:md_submit_discard_bio
```
```
In drivers/md/md-bitmap.c (ffffffff81d71d61)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_file_clear_bit
  - drivers/md/md-bitmap.c:md_bitmap_file_set_bit
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_new_disk_sb
  - drivers/md/md-bitmap.c:md_bitmap_print_sb
```
```
In drivers/md/dm.c (ffffffff81d78df2)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_split_and_process_bio
  - drivers/md/dm.c:dm_submit_bio_remap
```
```
In drivers/md/dm-stats.c (ffffffff81d85ef0)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stat_for_entry
```
```
In drivers/md/dm-rq.c (ffffffff81d8856f)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:map_request
```
```
In drivers/edac/edac_mc.c (ffffffff81d8a00b)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
  - drivers/edac/edac_mc.c:edac_mc_scrub_block
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81d994cc)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_driver_fast_switch
  - drivers/cpufreq/cpufreq.c:cpufreq_notify_transition
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81d9d111)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_init
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81d9f646)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target
```
```
In drivers/cpufreq/amd-pstate.c (ffffffff81da2815)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/cpufreq/amd-pstate.c:amd_pstate_update
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81daa7e6)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_adjust_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_adjust_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_pstate
```
```
In drivers/cpuidle/cpuidle.c (ffffffff82142774)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_use_deepest_state
```
```
In drivers/cpuidle/driver.c (ffffffff81dac765)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In drivers/cpuidle/governors/haltpoll.c (ffffffff81db0436)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In drivers/mmc/core/core.c (ffffffff81db26cc)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_cqe_request_done
  - drivers/mmc/core/core.c:mmc_cqe_start_req
  - drivers/mmc/core/core.c:__mmc_start_request
  - drivers/mmc/core/core.c:mmc_request_done
```
```
In drivers/firmware/efi/capsule.c (ffffffff81dcef2c)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/firmware/efi/capsule.c:efi_capsule_update
```
```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff81dd2a5d)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
```
```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff81ddf567)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In drivers/devfreq/devfreq.c (ffffffff81dee91e)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_monitor
  - drivers/devfreq/devfreq.c:devfreq_set_target
```
```
In drivers/ras/ras.c (ffffffff81df8655)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/ras/ras.c:log_arm_hw_error
  - drivers/ras/ras.c:log_non_standard_event
```
```
In drivers/interconnect/core.c (ffffffff81dfdce2)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - drivers/interconnect/core.c:icc_set_bw
  - drivers/interconnect/core.c:icc_set_bw
```
```
In net/socket.c (ffffffff81e013b9)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/socket.c:call_trace_sock_recv_length
```
```
In net/core/sock.c (ffffffff81e09527)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/core/sock.c:sock_def_readable
  - net/core/sock.c:__sk_mem_reduce_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:sock_i_ino
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:sk_error_report
```
```
In net/core/skbuff.c (ffffffff81e13d74)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:__consume_stateless_skb
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:kfree_skb_list_reason
  - net/core/skbuff.c:kfree_skb_list_reason
  - net/core/skbuff.c:kfree_skb_reason
  - net/core/skbuff.c:kfree_skb_reason
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_frag_align
  - net/core/skbuff.c:napi_get_frags_check
```
```
In net/core/datagram.c (ffffffff81e1f877)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_datagram_iter
```
```
In net/core/gen_estimator.c (ffffffff81e23203)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/net_namespace.c (ffffffff81e246fc)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/core/dev.c (ffffffff81e3f87d)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:__dev_set_allmulti
  - net/core/dev.c:dev_set_promiscuity
  - net/core/dev.c:napi_threaded_poll
  - net/core/dev.c:__napi_poll
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:flush_backlog
  - net/core/dev.c:netif_receive_skb_list
  - net/core/dev.c:netif_receive_skb_list
  - net/core/dev.c:netif_receive_skb
  - net/core/dev.c:netif_receive_skb
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__netif_rx
  - net/core/dev.c:__netif_rx
  - net/core/dev.c:netif_rx_internal
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:__dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_qdisc_enqueue
  - net/core/dev.c:dev_hard_start_xmit
  - net/core/dev.c:dev_hard_start_xmit
  - net/core/dev.c:__dev_open
```
```
In net/core/dev_addr_lists.c (ffffffff81e43f15)
Location: arch/x86/include/asm/preempt.h:78
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
In net/core/dst.c (ffffffff81e45135)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/core/dst.c:dst_destroy
```
```
In net/core/neighbour.c (ffffffff81e4c266)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_cleanup_and_release
```
```
In net/core/rtnetlink.c (ffffffff81e565ae)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_fdb_dump
```
```
In net/core/filter.c (ffffffff81e639ec)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_socket_ptr_cookie
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_redirect_frame
  - net/core/filter.c:xdp_do_redirect_frame
  - net/core/filter.c:xdp_do_redirect_frame
  - net/core/filter.c:xdp_do_redirect_frame
  - net/core/filter.c:xdp_do_redirect
  - net/core/filter.c:xdp_do_redirect
  - net/core/filter.c:xdp_do_redirect
  - net/core/filter.c:xdp_do_redirect
  - net/core/filter.c:bpf_out_neigh_v6
```
```
In net/core/sock_diag.c (ffffffff81e75575)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_save_cookie
  - net/core/sock_diag.c:sock_diag_check_cookie
```
```
In net/core/xdp.c (ffffffff81e78a14)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_rxq_info_reg_mem_model
  - net/core/xdp.c:mem_allocator_disconnect
```
```
In net/core/gro.c (ffffffff81e7c517)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/core/gro.c:napi_gro_frags
  - net/core/gro.c:napi_gro_frags
  - net/core/gro.c:napi_gro_receive
  - net/core/gro.c:napi_gro_receive
```
```
In net/core/page_pool.c (ffffffff81e827ba)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_update_nid
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_release_page
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
  - net/core/page_pool.c:__page_pool_alloc_page_order
```
```
In net/core/net-procfs.c (ffffffff81e84a2c)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In net/core/netpoll.c (ffffffff81e85045)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
  - net/core/netpoll.c:poll_one_napi
```
```
In net/core/net-traces.c (ffffffff81e9189a)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:perf_trace_tcp_event_sk
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk
```
```
In net/core/lwt_bpf.c (ffffffff81e9e08e)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In net/core/skmsg.c (ffffffff81ea1a3a)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_data_ready
```
```
In net/core/sock_map.c (ffffffff81ea6f11)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_update_elem
```
```
In net/sched/sch_generic.c (ffffffff81eae4db)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:__qdisc_destroy
  - net/sched/sch_generic.c:qdisc_reset
  - net/sched/sch_generic.c:qdisc_create_dflt
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/sched/sch_api.c (ffffffff81eb1eb9)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_create
```
```
In net/sched/act_api.c (ffffffff81ebdd53)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_update_hw_stats
```
```
In net/netlink/af_netlink.c (ffffffff81ec29f5)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:do_trace_netlink_extack
```
```
In net/bpf/test_run.c (ffffffff81ed03be)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_sk_lookup
  - net/bpf/test_run.c:bpf_prog_test_run_sk_lookup
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_prog_test_run_raw_tp
  - net/bpf/test_run.c:bpf_prog_test_run_tracing
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_timer_continue
```
```
In net/netfilter/nf_log.c (ffffffff81ee8ae6)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/netfilter/nf_log.c:nf_log_buf_open
```
```
In net/netfilter/nf_queue.c (ffffffff81ee9ba0)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_reinject
```
```
In net/ipv4/inet_hashtables.c (ffffffff81f03913)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81f04c45)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81f06c13)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/tcp.c (ffffffff81f109a8)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_abort
  - net/ipv4/tcp.c:tcp_abort
  - net/ipv4/tcp.c:tcp_abort
  - net/ipv4/tcp.c:__tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff81f1ff2f)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_reset
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
```
```
In net/ipv4/tcp_output.c (ffffffff81f22275)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_rtx_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f2dcc6)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81f32683)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/tcp_cong.c (ffffffff81f34544)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_set_ca_state
```
```
In net/ipv4/udp.c (ffffffff81f43337)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/icmp.c (ffffffff81f4b9f9)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_reply
```
```
In net/ipv4/af_inet.c (ffffffff81f55b72)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sk_state_store
  - net/ipv4/af_inet.c:inet_sk_set_state
```
```
In net/ipv4/fib_frontend.c (ffffffff81f5cc71)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_lookup
```
```
In net/ipv4/fib_trie.c (ffffffff81f67850)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv4/inet_fragment.c (ffffffff81f6a212)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f6dbc1)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff81f80030)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f92552)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In net/xfrm/xfrm_state.c (0)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In net/xfrm/xfrm_input.c (ffffffff81fa0ba5)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/espintcp.c (ffffffff81fa75be)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_data_ready
  - net/xfrm/espintcp.c:handle_esp
```
```
In net/ipv6/addrconf.c (ffffffff81fc6291)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
```
```
In net/ipv6/route.c (ffffffff81fd166d)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:fib6_table_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
```
```
In net/ipv6/udp.c (ffffffff81fe861b)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/icmp.c (ffffffff81ff117e)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffe9f8)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
```
```
In net/ipv6/ioam6.c (ffffffff8200a270)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/ip6mr.c (ffffffff8200e8c4)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff8201a724)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
```
```
In net/ipv6/seg6_local.c (ffffffff8201eae7)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
```
```
In net/ipv6/seg6_hmac.c (ffffffff8201eda1)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff82020fcd)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
```
```
In net/devlink/leftover.c (ffffffff8202eae8)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/devlink/leftover.c:devlink_trap_report
```
```
In net/devlink/health.c (ffffffff82047da8)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/devlink/health.c:devlink_health_report
  - net/devlink/health.c:devlink_health_report
```
```
In net/mptcp/protocol.c (ffffffff820750ab)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_subflow_get_send
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
```
```
In net/mptcp/subflow.c (ffffffff8207be3b)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_data_ready
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:get_mapping_status
```
```
In net/mptcp/options.c (ffffffff8207e1ff)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/mptcp/options.c:ack_update_msk
```
```
In net/mctp/af_mctp.c (ffffffff8208d7a6)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In net/mctp/route.c (ffffffff82090d53)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_alloc_local_tag
  - net/mctp/route.c:mctp_route_input
  - net/mctp/route.c:__mctp_key_done_in
```
```
In net/handshake/netlink.c (ffffffff820928d5)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/handshake/netlink.c:handshake_nl_done_doit
  - net/handshake/netlink.c:handshake_nl_done_doit
  - net/handshake/netlink.c:handshake_nl_accept_doit
  - net/handshake/netlink.c:handshake_nl_accept_doit
```
```
In net/handshake/request.c (ffffffff82093890)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - net/handshake/request.c:handshake_req_cancel
  - net/handshake/request.c:handshake_req_cancel
  - net/handshake/request.c:handshake_req_cancel
  - net/handshake/request.c:handshake_complete
  - net/handshake/request.c:handshake_req_submit
  - net/handshake/request.c:handshake_req_submit
  - net/handshake/request.c:handshake_req_submit
  - net/handshake/request.c:handshake_sk_destruct
```
```
In lib/bug.c (ffffffff8209ed60)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - lib/bug.c:generic_bug_clear_once
  - lib/bug.c:report_bug
  - lib/bug.c:find_bug
```
```
In lib/buildid.c (ffffffff8209f015)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - lib/buildid.c:build_id_parse
```
```
In lib/flex_proportions.c (0)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In lib/maple_tree.c (ffffffff820ac5d0)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - lib/maple_tree.c:mt_find
  - lib/maple_tree.c:mtree_erase
  - lib/maple_tree.c:mtree_store_range
  - lib/maple_tree.c:mtree_load
  - lib/maple_tree.c:mas_store_prealloc
  - lib/maple_tree.c:mas_store_gfp
  - lib/maple_tree.c:mas_store
  - lib/maple_tree.c:mas_wr_modify
  - lib/maple_tree.c:mas_wr_bnode
  - lib/maple_tree.c:mas_wr_node_store
  - lib/maple_tree.c:mas_is_span_wr
```
```
In lib/nmi_backtrace.c (ffffffff820b7480)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
```
In lib/radix-tree.c (ffffffff820b79d7)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - lib/radix-tree.c:__radix_tree_preload
  - lib/radix-tree.c:__radix_tree_preload
```
```
In arch/x86/lib/delay.c (ffffffff820cad85)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - arch/x86/lib/delay.c:delay_tsc
  - arch/x86/lib/delay.c:delay_tsc
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
In init/main.c (ffffffff838b0ec0)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
  - init/main.c:do_initcalls
  - init/main.c:do_one_initcall
  - init/main.c:do_one_initcall
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff810076e2)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
```
```
In arch/x86/events/amd/ibs.c (ffffffff838b52d0)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
```
```
In arch/x86/events/intel/ds.c (ffffffff8101cd4e)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:ds_clear_cea
  - arch/x86/events/intel/ds.c:ds_update_cea
```
```
In arch/x86/events/intel/p4.c (ffffffff810244d5)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_hw_config
```
```
In arch/x86/xen/time.c (ffffffff838bb5a5)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_hvm_init_time_ops
  - arch/x86/xen/time.c:xen_init_time_ops
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_restore_time_memory_area
  - arch/x86/xen/time.c:xen_save_time_memory_area
  - arch/x86/xen/time.c:xen_vcpuop_set_next_event
  - arch/x86/xen/time.c:xen_timerop_set_next_event
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
  - arch/x86/xen/time.c:xen_get_wallclock
  - arch/x86/xen/time.c:xen_clocksource_get_cycles
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff8103e612)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_cr0
  - arch/x86/xen/enlighten_pv.c:xen_load_sp0
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry_boot
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry
  - arch/x86/xen/enlighten_pv.c:xen_write_gdt_entry
  - arch/x86/xen/enlighten_pv.c:xen_load_idt
  - arch/x86/xen/enlighten_pv.c:xen_write_idt_entry
  - arch/x86/xen/enlighten_pv.c:xen_write_idt_entry
  - arch/x86/xen/enlighten_pv.c:xen_write_ldt_entry
  - arch/x86/xen/enlighten_pv.c:xen_write_ldt_entry
  - arch/x86/xen/enlighten_pv.c:load_TLS_descriptor
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
  - arch/x86/xen/enlighten_pv.c:xen_mc_batch
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810404c5)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_all
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_all
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_leave_lazy_mmu
  - arch/x86/xen/mmu_pv.c:xen_flush_lazy_mmu
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:__xen_write_cr3
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_multi
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
  - arch/x86/xen/mmu_pv.c:xen_set_p4d_hyper
  - arch/x86/xen/mmu_pv.c:xen_set_pud
  - arch/x86/xen/mmu_pv.c:xen_set_pud_hyper
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_start
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pmd
  - arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper
  - arch/x86/xen/mmu_pv.c:xen_extend_mmuext_op
  - arch/x86/xen/mmu_pv.c:xen_extend_mmu_update
  - arch/x86/xen/mmu_pv.c:xen_mc_batch
```
```
In arch/x86/xen/multicalls.c (ffffffff810440d3)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/xen/multicalls.c:xen_mc_callback
  - arch/x86/xen/multicalls.c:xen_mc_callback
  - arch/x86/xen/multicalls.c:xen_mc_extend_args
  - arch/x86/xen/multicalls.c:xen_mc_extend_args
  - arch/x86/xen/multicalls.c:xen_mc_extend_args
  - arch/x86/xen/multicalls.c:__xen_mc_entry
  - arch/x86/xen/multicalls.c:__xen_mc_entry
  - arch/x86/xen/multicalls.c:xen_mc_flush
```
```
In arch/x86/hyperv/hv_init.c (ffffffff8104b759)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:set_hv_tscchange_cb
```
```
In arch/x86/hyperv/mmu.c (ffffffff8104d700)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
```
```
In arch/x86/hyperv/nested.c (ffffffff8104dd7b)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8105043e)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_one
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
```
```
In arch/x86/kernel/process_64.c (ffffffff81052909)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/signal.c (ffffffff81052ca5)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:handle_signal
```
```
In arch/x86/kernel/irq.c (ffffffff81057496)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:__sysvec_thermal
  - arch/x86/kernel/irq.c:__sysvec_thermal
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:__sysvec_x86_platform_ipi
  - arch/x86/kernel/irq.c:__sysvec_x86_platform_ipi
```
```
In arch/x86/kernel/ioport.c (ffffffff81058c1e)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In arch/x86/kernel/nmi.c (ffffffff8105a52d)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:nmi_handle
```
```
In arch/x86/kernel/irq_work.c (ffffffff8105c97b)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:__sysvec_irq_work
  - arch/x86/kernel/irq_work.c:__sysvec_irq_work
```
```
In arch/x86/kernel/tsc.c (ffffffff81065a15)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state
  - arch/x86/kernel/tsc.c:tsc_save_sched_clock_state
  - arch/x86/kernel/tsc.c:native_sched_clock_from_tsc
  - arch/x86/kernel/tsc.c:__set_cyc2ns_scale
  - arch/x86/kernel/tsc.c:cyc2ns_read_begin
```
```
In arch/x86/kernel/process.c (ffffffff8106813a)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:do_arch_prctl_common
  - arch/x86/kernel/process.c:speculation_ctrl_update_current
  - arch/x86/kernel/process.c:enable_cpuid
  - arch/x86/kernel/process.c:set_tsc_mode
  - arch/x86/kernel/process.c:disable_TSC
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8106a022)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpregs_mark_activate
  - arch/x86/kernel/fpu/core.c:fpregs_lock_and_load
  - arch/x86/kernel/fpu/core.c:fpregs_lock_and_load
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
  - arch/x86/kernel/fpu/core.c:fpu__clear_user_states
  - arch/x86/kernel/fpu/core.c:fpu_reset_fpregs
  - arch/x86/kernel/fpu/core.c:fpu__drop
  - arch/x86/kernel/fpu/core.c:fpu__drop
  - arch/x86/kernel/fpu/core.c:fpu__drop
  - arch/x86/kernel/fpu/core.c:fpu_clone
  - arch/x86/kernel/fpu/core.c:fpu_clone
  - arch/x86/kernel/fpu/core.c:fpu_clone
  - arch/x86/kernel/fpu/core.c:fpu_clone
  - arch/x86/kernel/fpu/core.c:fpu_sync_fpstate
  - arch/x86/kernel/fpu/core.c:fpu_sync_fpstate
  - arch/x86/kernel/fpu/core.c:fpu_sync_fpstate
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin_mask
  - arch/x86/kernel/fpu/core.c:fpu_swap_kvm_fpstate
  - arch/x86/kernel/fpu/core.c:fpu_update_guest_xfd
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8106b861)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
  - arch/x86/kernel/fpu/signal.c:check_xstate_in_sigframe
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8106c77f)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In arch/x86/kernel/tls.c (ffffffff8106f780)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:set_tls_desc
```
```
In arch/x86/kernel/cpu/aperfmperf.c (0)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8107af43)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:split_lock_warn
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8107fd85)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:wait_for_panic
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81084778)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:__sysvec_deferred_error
  - arch/x86/kernel/cpu/mce/amd.c:__sysvec_deferred_error
```
```
In arch/x86/kernel/cpu/mce/threshold.c (ffffffff810865f8)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/threshold.c:__sysvec_threshold
  - arch/x86/kernel/cpu/mce/threshold.c:__sysvec_threshold
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff81089ee5)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_get_mtrr
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff810952e3)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:add_rmid_to_limbo
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81097d97)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_l3_residency
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_l2_residency
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff8109bf6e)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_init
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff8109f271)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_virt_einit
```
```
In arch/x86/kernel/smp.c (ffffffff810a2cbb)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:__sysvec_call_function_single
  - arch/x86/kernel/smp.c:__sysvec_call_function_single
  - arch/x86/kernel/smp.c:__sysvec_call_function
  - arch/x86/kernel/smp.c:__sysvec_call_function
  - arch/x86/kernel/smp.c:sysvec_reschedule_ipi
  - arch/x86/kernel/smp.c:sysvec_reschedule_ipi
  - arch/x86/kernel/smp.c:sysvec_reschedule_ipi
```
```
In arch/x86/kernel/smpboot.c (ffffffff810a36b5)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
```
```
In arch/x86/kernel/apic/apic.c (ffffffff810a7e4e)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:__sysvec_error_interrupt
  - arch/x86/kernel/apic/apic.c:__sysvec_error_interrupt
  - arch/x86/kernel/apic/apic.c:handle_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:handle_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:__sysvec_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:__sysvec_apic_timer_interrupt
```
```
In arch/x86/kernel/apic/vector.c (ffffffff838e1c91)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/vector.c:free_moved_vector
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_deactivate
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
  - arch/x86/kernel/apic/vector.c:assign_vector_locked
  - arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked
  - arch/x86/kernel/apic/vector.c:apic_update_vector
  - arch/x86/kernel/apic/vector.c:apic_update_irq_cfg
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff810b1b34)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_one
```
```
In arch/x86/kernel/ftrace.c (ffffffff810b4afa)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/ftrace.c:prepare_ftrace_return
```
```
In arch/x86/kernel/kprobes/opt.c (ffffffff810badef)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In arch/x86/kernel/kprobes/ftrace.c (ffffffff810bb89a)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
```
In arch/x86/kernel/kvmclock.c (ffffffff838eb2ea)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvmclock_init
  - arch/x86/kernel/kvmclock.c:kvm_clock_get_cycles
  - arch/x86/kernel/kvmclock.c:kvm_get_wallclock
```
```
In arch/x86/kernel/callthunks.c (ffffffff810c9711)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/callthunks.c:is_coretext
```
```
In arch/x86/mm/fault.c (ffffffff82223796)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:exc_page_fault
  - arch/x86/mm/fault.c:exc_page_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff810d0dc7)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_check_ram
```
```
In arch/x86/mm/mmap.c (ffffffff810d2776)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_modify_allowed
```
```
In arch/x86/mm/physaddr.c (ffffffff810d3d99)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
```
In arch/x86/mm/tlb.c (ffffffff810d55f5)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:arch_tlbbatch_flush
  - arch/x86/mm/tlb.c:flush_tlb_kernel_range
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
  - arch/x86/mm/tlb.c:native_flush_tlb_multi
  - arch/x86/mm/tlb.c:native_flush_tlb_multi
  - arch/x86/mm/tlb.c:flush_tlb_func
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/mm/kmmio.c (ffffffff810de294)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:kmmio_handler
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810def15)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:post
  - arch/x86/mm/mmio-mod.c:post
  - arch/x86/mm/mmio-mod.c:pre
  - arch/x86/mm/mmio-mod.c:pre
  - arch/x86/mm/mmio-mod.c:pre
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff810ebd98)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:arch_efi_call_virt_setup
```
```
In kernel/fork.c (ffffffff810fdd1f)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/fork.c:kernel_clone
  - kernel/fork.c:copy_process
```
```
In kernel/panic.c (ffffffff810feebe)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/panic.c:__warn_printk
  - kernel/panic.c:__warn
  - kernel/panic.c:panic
```
```
In kernel/cpu.c (ffffffff81102616)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
  - kernel/cpu.c:__cpuhp_state_add_instance
  - kernel/cpu.c:thaw_secondary_cpus
  - kernel/cpu.c:thaw_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:cpuhp_kick_ap_work
  - kernel/cpu.c:cpuhp_kick_ap_work
  - kernel/cpu.c:cpus_read_trylock
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
```
```
In kernel/exit.c (ffffffff81107265)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:delayed_put_task_struct
```
```
In kernel/softirq.c (ffffffff81109440)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/softirq.c:__raise_softirq_irqoff
  - kernel/softirq.c:irq_enter_rcu
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
```
```
In kernel/signal.c (ffffffff8111acf2)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:exit_signals
  - kernel/signal.c:exit_signals
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:__send_signal_locked
```
```
In kernel/workqueue.c (ffffffff81126b76)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_congested
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:pwq_activate_inactive_work
  - kernel/workqueue.c:wq_worker_running
```
```
In kernel/kthread.c (ffffffff8113534c)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_stop
  - kernel/kthread.c:kthread_stop
  - kernel/kthread.c:kthread
  - kernel/kthread.c:__kthread_parkme
```
```
In kernel/notifier.c (ffffffff8113d6d1)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/notifier.c:notifier_call_chain
  - kernel/notifier.c:notifier_chain_unregister
```
```
In kernel/smpboot.c (ffffffff81141ae6)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/smpboot.c:smpboot_thread_fn
```
```
In kernel/sched/core.c (ffffffff8115e2b5)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_mm_cid_after_execve
  - kernel/sched/core.c:sched_mm_cid_before_execve
  - kernel/sched/core.c:call_trace_sched_update_nr_running
  - kernel/sched/core.c:balance_push
  - kernel/sched/core.c:migrate_task_to
  - kernel/sched/core.c:klp_cond_resched
  - kernel/sched/core.c:do_sched_yield
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_schedule
  - kernel/sched/core.c:preempt_schedule_irq
  - kernel/sched/core.c:preempt_schedule_notrace
  - kernel/sched/core.c:preempt_schedule
  - kernel/sched/core.c:schedule_preempt_disabled
  - kernel/sched/core.c:schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:sched_core_balance
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:call_function_single_prep_ipi
  - kernel/sched/core.c:ttwu_do_activate
  - kernel/sched/core.c:kick_process
  - kernel/sched/core.c:kick_process
  - kernel/sched/core.c:migrate_swap
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:affine_move_task
  - kernel/sched/core.c:migration_cpu_stop
  - kernel/sched/core.c:migrate_enable
  - kernel/sched/core.c:migrate_disable
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:wake_up_nohz_cpu
  - kernel/sched/core.c:wake_up_nohz_cpu
  - kernel/sched/core.c:resched_curr
  - kernel/sched/core.c:resched_curr
  - kernel/sched/core.c:raw_spin_rq_trylock
```
```
In kernel/sched/fair.c (ffffffff8116c4a2)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_group_capacity
  - kernel/sched/fair.c:compute_energy
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:detach_entity_load_avg
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:update_curr
  - kernel/sched/fair.c:update_curr_common
```
```
In kernel/sched/build_policy.c (ffffffff81179ad9)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:dl_bw_manage
  - kernel/sched/build_policy.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/build_policy.c:sched_dl_do_global
  - kernel/sched/build_policy.c:sched_dl_global_validate
  - kernel/sched/build_policy.c:pull_dl_task
  - kernel/sched/build_policy.c:update_dl_rq_load_avg
  - kernel/sched/build_policy.c:update_rt_rq_load_avg
  - kernel/sched/build_policy.c:__update_load_avg_cfs_rq
  - kernel/sched/build_policy.c:__update_load_avg_se
  - kernel/sched/build_policy.c:__update_load_avg_blocked_se
  - kernel/sched/build_policy.c:pull_rt_task
  - kernel/sched/build_policy.c:push_rt_task
  - kernel/sched/build_policy.c:play_idle_precise
  - kernel/sched/build_policy.c:default_idle_call
  - kernel/sched/build_policy.c:default_idle_call
```
```
In kernel/sched/build_utility.c (ffffffff8118fc5d)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:__do_sys_membarrier
  - kernel/sched/build_utility.c:membarrier_private_expedited
  - kernel/sched/build_utility.c:__update_stats_enqueue_sleeper
  - kernel/sched/build_utility.c:__update_stats_enqueue_sleeper
  - kernel/sched/build_utility.c:__update_stats_enqueue_sleeper
  - kernel/sched/build_utility.c:__update_stats_wait_end
  - kernel/sched/build_utility.c:sched_debug_header
  - kernel/sched/build_utility.c:running_clock
  - kernel/sched/build_utility.c:sched_clock_cpu
  - kernel/sched/build_utility.c:__sched_clock_work
```
```
In kernel/locking/mutex.c (ffffffff82235eea)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In kernel/locking/semaphore.c (ffffffff82237713)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/locking/semaphore.c:__down_common
  - kernel/locking/semaphore.c:__down_common
```
```
In kernel/locking/rwsem.c (ffffffff8119c953)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:downgrade_write
  - kernel/locking/rwsem.c:up_write
  - kernel/locking/rwsem.c:up_read
  - kernel/locking/rwsem.c:down_write_trylock
  - kernel/locking/rwsem.c:down_write_killable
  - kernel/locking/rwsem.c:down_write
  - kernel/locking/rwsem.c:down_read_trylock
  - kernel/locking/rwsem.c:down_read_killable
  - kernel/locking/rwsem.c:down_read_interruptible
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/locking/percpu-rwsem.c (ffffffff82238af6)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_down_write
  - kernel/locking/percpu-rwsem.c:percpu_down_write
  - kernel/locking/percpu-rwsem.c:__percpu_down_read
  - kernel/locking/percpu-rwsem.c:__percpu_down_read
  - kernel/locking/percpu-rwsem.c:__percpu_down_read
```
```
In kernel/locking/spinlock.c (ffffffff8119d587)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:__raw_write_lock_irqsave
  - kernel/locking/spinlock.c:__raw_read_lock_irqsave
  - kernel/locking/spinlock.c:_raw_write_trylock
  - kernel/locking/spinlock.c:_raw_read_trylock
  - kernel/locking/spinlock.c:_raw_write_lock_irq
  - kernel/locking/spinlock.c:_raw_read_lock_irq
  - kernel/locking/spinlock.c:_raw_write_lock_bh
  - kernel/locking/spinlock.c:_raw_read_lock_bh
  - kernel/locking/spinlock.c:_raw_write_lock_nested
  - kernel/locking/spinlock.c:_raw_write_lock
  - kernel/locking/spinlock.c:_raw_read_lock
  - kernel/locking/spinlock.c:__raw_spin_lock_irqsave
  - kernel/locking/spinlock.c:_raw_spin_trylock_bh
  - kernel/locking/spinlock.c:_raw_spin_trylock
  - kernel/locking/spinlock.c:_raw_spin_lock_irq
  - kernel/locking/spinlock.c:_raw_spin_lock_bh
  - kernel/locking/spinlock.c:_raw_spin_lock
```
```
In kernel/locking/qspinlock.c (ffffffff8223d4a9)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:native_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:native_queued_spin_lock_slowpath
```
```
In kernel/locking/rtmutex_api.c (ffffffff82238c9e)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:mark_wakeup_next_waiter
```
```
In kernel/locking/qrwlock.c (ffffffff8223da3e)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
  - kernel/locking/qrwlock.c:queued_read_lock_slowpath
```
```
In kernel/power/qos.c (ffffffff8119e2c5)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/power/qos.c:cpu_latency_qos_remove_request
  - kernel/power/qos.c:pm_qos_update_flags
  - kernel/power/qos.c:pm_qos_update_target
```
```
In kernel/power/process.c (ffffffff811a0c4f)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:thaw_processes
```
```
In kernel/power/suspend.c (ffffffff811a1e06)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:s2idle_loop
  - kernel/power/suspend.c:s2idle_loop
```
```
In kernel/power/hibernate.c (ffffffff811a307f)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/power/hibernate.c:create_image
  - kernel/power/hibernate.c:create_image
```
```
In kernel/power/snapshot.c (ffffffff811a7ad2)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:saveable_page
  - kernel/power/snapshot.c:clear_or_poison_free_pages
  - kernel/power/snapshot.c:create_basic_memory_bitmaps
```
```
In kernel/printk/printk.c (ffffffff83901437)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_init
  - kernel/printk/printk.c:console_init
  - kernel/printk/printk.c:console_init
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:printk_sprint
```
```
In kernel/irq/handle.c (ffffffff811b708f)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/manage.c (ffffffff811b7a75)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_forced_thread_fn
```
```
In kernel/irq/chip.c (ffffffff811bdd05)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi
  - kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_fasteoi_nmi
  - kernel/irq/chip.c:handle_fasteoi_nmi
```
```
In kernel/irq/matrix.c (ffffffff811ca453)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_free
  - kernel/irq/matrix.c:irq_matrix_alloc
  - kernel/irq/matrix.c:irq_matrix_remove_reserved
  - kernel/irq/matrix.c:irq_matrix_reserve
  - kernel/irq/matrix.c:irq_matrix_assign
  - kernel/irq/matrix.c:irq_matrix_alloc_managed
  - kernel/irq/matrix.c:irq_matrix_remove_managed
  - kernel/irq/matrix.c:irq_matrix_reserve_managed
  - kernel/irq/matrix.c:irq_matrix_assign_system
  - kernel/irq/matrix.c:irq_matrix_offline
  - kernel/irq/matrix.c:irq_matrix_online
```
```
In kernel/rcu/update.c (ffffffff811cb401)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_invoke_cbs
```
```
In kernel/rcu/srcutree.c (ffffffff811d106d)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
```
```
In kernel/rcu/tree.c (ffffffff811dd70c)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_note_context_switch
  - kernel/rcu/tree.c:rcu_note_context_switch
  - kernel/rcu/tree.c:nocb_cb_wait
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:__sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:print_cpu_stall
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:__call_rcu_common
  - kernel/rcu/tree.c:__call_rcu_common
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_do_batch
```
```
In kernel/livepatch/core.c (ffffffff811e459a)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_init_object
```
```
In kernel/livepatch/patch.c (ffffffff811e5415)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_ftrace_handler
```
```
In kernel/livepatch/transition.c (ffffffff811e6c25)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_update_patch_state
```
```
In kernel/dma/swiotlb.c (ffffffff811edb4a)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_map
```
```
In kernel/entry/common.c (ffffffff811eed55)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/entry/common.c:syscall_exit_to_user_mode_prepare
  - kernel/entry/common.c:syscall_exit_work
  - kernel/entry/common.c:syscall_trace_enter
  - kernel/entry/common.c:irqentry_nmi_enter
```
```
In kernel/module/main.c (ffffffff811f6f61)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/module/main.c:print_modules
  - kernel/module/main.c:is_module_text_address
  - kernel/module/main.c:is_module_address
  - kernel/module/main.c:search_module_extables
  - kernel/module/main.c:load_module
  - kernel/module/main.c:__symbol_get
  - kernel/module/main.c:free_module
  - kernel/module/main.c:module_put
  - kernel/module/main.c:try_module_get
  - kernel/module/main.c:symbol_put_addr
  - kernel/module/main.c:__symbol_put
  - kernel/module/main.c:__is_module_percpu_address
```
```
In kernel/module/kmod.c (ffffffff811f75c0)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/module/kmod.c:__request_module
```
```
In kernel/module/kallsyms.c (ffffffff811f9334)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/module/kallsyms.c:module_kallsyms_on_each_symbol
  - kernel/module/kallsyms.c:find_kallsyms_symbol_value
  - kernel/module/kallsyms.c:module_kallsyms_lookup_name
  - kernel/module/kallsyms.c:module_get_kallsym
  - kernel/module/kallsyms.c:lookup_module_symbol_name
  - kernel/module/kallsyms.c:module_address_lookup
```
```
In kernel/module/version.c (ffffffff811fa7b9)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/module/version.c:check_modstruct_version
```
```
In kernel/profile.c (ffffffff811fc1d7)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/profile.c:profile_discard_flip_buffers
  - kernel/profile.c:profile_flip_buffers
```
```
In kernel/time/timer.c (ffffffff81202eed)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:__run_timers
  - kernel/time/timer.c:timer_clear_idle
  - kernel/time/timer.c:get_next_timer_interrupt
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:detach_if_pending
  - kernel/time/timer.c:enqueue_timer
```
```
In kernel/time/hrtimer.c (ffffffff81205602)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_cpu_dying
  - kernel/time/hrtimer.c:hrtimer_nanosleep
  - kernel/time/hrtimer.c:hrtimer_nanosleep_restart
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_init
  - kernel/time/hrtimer.c:__hrtimer_start_range_ns
  - kernel/time/hrtimer.c:enqueue_hrtimer
  - kernel/time/hrtimer.c:clock_was_set
```
```
In kernel/time/timekeeping.c (0)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In kernel/time/clocksource.c (ffffffff8120b313)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In kernel/time/alarmtimer.c (ffffffff8120df59)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_try_to_cancel
  - kernel/time/alarmtimer.c:alarm_start
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - kernel/time/alarmtimer.c:alarmtimer_fired
```
```
In kernel/time/posix-cpu-timers.c (ffffffff812131b5)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:check_cpu_itimer
```
```
In kernel/time/itimer.c (ffffffff81216c42)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:it_real_fn
```
```
In kernel/time/tick-common.c (ffffffff812194c4)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_unfreeze
  - kernel/time/tick-common.c:tick_freeze
```
```
In kernel/time/tick-sched.c (ffffffff8121c0e7)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_stop_tick
  - kernel/time/tick-sched.c:tick_nohz_dep_set_cpu
  - kernel/time/tick-sched.c:tick_nohz_dep_set
  - kernel/time/tick-sched.c:check_tick_dependency
  - kernel/time/tick-sched.c:check_tick_dependency
  - kernel/time/tick-sched.c:check_tick_dependency
  - kernel/time/tick-sched.c:check_tick_dependency
  - kernel/time/tick-sched.c:check_tick_dependency
  - kernel/time/tick-sched.c:check_tick_dependency
```
```
In kernel/smp.c (ffffffff8122534c)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/smp.c:wake_up_all_idle_cpus
  - kernel/smp.c:kick_all_cpus_sync
  - kernel/smp.c:on_each_cpu_cond_mask
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_any
  - kernel/smp.c:smp_call_function_single_async
  - kernel/smp.c:smp_call_function_single
  - kernel/smp.c:__flush_smp_call_function_queue
  - kernel/smp.c:__flush_smp_call_function_queue
  - kernel/smp.c:__flush_smp_call_function_queue
  - kernel/smp.c:__flush_smp_call_function_queue
  - kernel/smp.c:__flush_smp_call_function_queue
  - kernel/smp.c:__flush_smp_call_function_queue
  - kernel/smp.c:generic_exec_single
  - kernel/smp.c:generic_exec_single
  - kernel/smp.c:__smp_call_single_queue
  - kernel/smp.c:__smp_call_single_queue
```
```
In kernel/acct.c (ffffffff81229c7e)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
  - kernel/acct.c:do_acct_process
```
```
In kernel/cgroup/cgroup.c (ffffffff81236aab)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_css_set_put_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_rmdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:cgroup_destroy_root
  - kernel/cgroup/cgroup.c:cgroup_update_populated
```
```
In kernel/cgroup/rstat.c (ffffffff8123f2a5)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:__cgroup_account_cputime_field
  - kernel/cgroup/rstat.c:__cgroup_account_cputime
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81241fe6)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
```
In kernel/cgroup/freezer.c (ffffffff81242cc9)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_propagate_frozen
  - kernel/cgroup/freezer.c:cgroup_propagate_frozen
```
```
In kernel/cgroup/cpuset.c (0)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In kernel/stop_machine.c (ffffffff81253886)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
  - kernel/stop_machine.c:cpu_stop_queue_two_works
  - kernel/stop_machine.c:cpu_stop_queue_work
```
```
In kernel/kprobes.c (ffffffff8126694f)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/kprobes.c:show_kprobe_addr
  - kernel/kprobes.c:check_kprobe_address_safe
  - kernel/kprobes.c:kprobe_busy_begin
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff8127519e)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/hung_task.c (ffffffff81277dcb)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/hung_task.c:check_hung_task
```
```
In kernel/relay.c (ffffffff8127d9a7)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/relay.c:relay_late_setup_files
```
```
In kernel/trace/trace_clock.c (ffffffff812822b0)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_local
```
```
In kernel/trace/ftrace.c (ffffffff812837da)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:fnpid_start
  - kernel/trace/ftrace.c:fpid_start
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:arch_ftrace_ops_list_func
  - kernel/trace/ftrace.c:ftrace_mod_get_kallsym
  - kernel/trace/ftrace.c:ftrace_mod_address_lookup
  - kernel/trace/ftrace.c:function_trace_probe_call
  - kernel/trace/ftrace.c:ftrace_ops_trampoline
```
```
In kernel/trace/ring_buffer.c (ffffffff81292ddb)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_consume
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_nest_start
  - kernel/trace/ring_buffer.c:ring_buffer_time_stamp
```
```
In kernel/trace/trace.c (ffffffff8129bd8f)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_write
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_read
  - kernel/trace/trace.c:saved_cmdlines_start
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_buffered_event_enable
  - kernel/trace/trace.c:trace_find_cmdline
  - kernel/trace/trace.c:ftrace_exports
```
```
In kernel/trace/trace_functions.c (ffffffff812acfd5)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_no_repeats_trace_call
  - kernel/trace/trace_functions.c:function_trace_call
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff812ae43c)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
  - kernel/trace/trace_sched_wakeup.c:func_prolog_preempt_disable
```
```
In kernel/trace/trace_osnoise.c (ffffffff812b2f61)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/trace/trace_osnoise.c:trace_sched_switch_callback
  - kernel/trace/trace_osnoise.c:trace_softirq_exit_callback
  - kernel/trace/trace_osnoise.c:osnoise_trace_irq_exit
  - kernel/trace/trace_osnoise.c:trace_osnoise_callback
```
```
In kernel/trace/trace_stack.c (ffffffff812b5aa0)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:stack_trace_call
```
```
In kernel/trace/trace_mmiotrace.c (ffffffff812b67b7)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
```
```
In kernel/trace/trace_functions_graph.c (ffffffff812b757c)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/blktrace.c (ffffffff812bb96f)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/blktrace.c:trace_note
```
```
In kernel/trace/trace_events.c (ffffffff812bfffa)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:np_start
  - kernel/trace/trace_events.c:p_start
```
```
In kernel/trace/trace_event_perf.c (ffffffff812c5609)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_ftrace_function_call
```
```
In kernel/trace/trace_events_inject.c (ffffffff812cee7d)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/trace/trace_events_inject.c:trace_inject_entry
```
```
In kernel/trace/trace_events_user.c (ffffffff812e285a)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/trace/trace_events_user.c:update_enable_bit_for
```
```
In kernel/trace/bpf_trace.c (ffffffff812e7732)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:get_modules_for_addrs
  - kernel/trace/bpf_trace.c:bpf_put_raw_tracepoint
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_raw_tp
  - kernel/trace/bpf_trace.c:bpf_perf_event_output_tp
  - kernel/trace/bpf_trace.c:bpf_event_output
  - kernel/trace/bpf_trace.c:bpf_perf_event_output
  - kernel/trace/bpf_trace.c:bpf_trace_vprintk
  - kernel/trace/bpf_trace.c:bpf_trace_printk
```
```
In kernel/trace/trace_kprobe.c (ffffffff812ec0cc)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:append_trace_kprobe
```
```
In kernel/trace/trace_uprobe.c (ffffffff812f978e)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:__uprobe_perf_func
```
```
In kernel/trace/fprobe.c (ffffffff812fbe5b)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In kernel/trace/rethook.c (ffffffff812fd0ea)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/trace/rethook.c:rethook_trampoline_handler
  - kernel/trace/rethook.c:rethook_flush_task
```
```
In kernel/trace/rv/monitors/wwnr/wwnr.c (ffffffff81301cd3)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/trace/rv/monitors/wwnr/wwnr.c:da_event_wwnr
  - kernel/trace/rv/monitors/wwnr/wwnr.c:da_event_wwnr
```
```
In kernel/irq_work.c (ffffffff8130303a)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_queue_on
```
```
In kernel/bpf/core.c (ffffffff81309005)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_user_rnd_u32
```
```
In kernel/bpf/helpers.c (ffffffff8134230a)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_bprintf_prepare
  - kernel/bpf/helpers.c:copy_map_value_locked
  - kernel/bpf/helpers.c:__bpf_spin_lock_irqsave
```
```
In kernel/bpf/hashtab.c (ffffffff8134a526)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_lock_bucket
```
```
In kernel/bpf/devmap.c (ffffffff813760c7)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_generic_redirect
  - kernel/bpf/devmap.c:bq_xmit_all
  - kernel/bpf/devmap.c:dev_map_bpf_prog_run
```
```
In kernel/bpf/cpumap.c (ffffffff81377db3)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_generic_redirect
  - kernel/bpf/cpumap.c:bq_flush_to_queue
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_skb
```
```
In kernel/bpf/offload.c (ffffffff813786a5)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In kernel/static_call_inline.c (ffffffff8138d5de)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/static_call_inline.c:static_call_text_reserved
```
```
In kernel/events/core.c (ffffffff8139c9e5)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_cgroup_move
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_pending_task
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:perf_event_read
```
```
In kernel/events/ring_buffer.c (ffffffff813a5668)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
```
```
In kernel/events/hw_breakpoint.c (ffffffff813a6e42)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff813ac475)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_end_dup_mmap
  - kernel/events/uprobes.c:uprobe_start_dup_mmap
  - kernel/events/uprobes.c:__update_ref_ctr
  - kernel/events/uprobes.c:copy_to_page
  - kernel/events/uprobes.c:copy_from_page
```
```
In kernel/user-return-notifier.c (ffffffff813ad845)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/user-return-notifier.c:fire_user_return_notifiers
```
```
In kernel/padata.c (ffffffff813adea2)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:invoke_padata_reorder
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_parallel_worker
```
```
In kernel/jump_label.c (ffffffff813af7bd)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_update
  - kernel/jump_label.c:jump_label_text_reserved
  - kernel/jump_label.c:jump_label_add_module
```
```
In kernel/context_tracking.c (ffffffff822245b2)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/context_tracking.c:__ct_user_exit
  - kernel/context_tracking.c:__ct_user_enter
```
```
In kernel/iomem.c (ffffffff813b0db7)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/iomem.c:try_ram_remap
```
```
In kernel/rseq.c (ffffffff813b21f0)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/rseq.c:rseq_ip_fixup
  - kernel/rseq.c:rseq_ip_fixup
  - kernel/rseq.c:rseq_update_cpu_node_id
```
```
In kernel/watch_queue.c (ffffffff813b261c)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In mm/filemap.c (ffffffff813b8003)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:file_check_and_advance_wb_err
  - mm/filemap.c:__filemap_set_wb_err
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__filemap_remove_folio
```
```
In mm/oom_kill.c (ffffffff813bf493)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - mm/oom_kill.c:mark_oom_victim
  - mm/oom_kill.c:wake_oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
```
```
In mm/page-writeback.c (ffffffff813c32c6)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - mm/page-writeback.c:folio_wait_writeback_killable
  - mm/page-writeback.c:folio_wait_writeback
  - mm/page-writeback.c:folio_account_dirtied
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:balance_dirty_pages_ratelimited_flags
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:wb_update_dirty_ratelimit
  - mm/page-writeback.c:domain_dirty_limits
```
```
In mm/swap.c (ffffffff813ccbc0)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - mm/swap.c:__folio_batch_release
  - mm/swap.c:lru_add_drain_per_cpu
  - mm/swap.c:lru_add_drain_cpu_zone
  - mm/swap.c:folio_mark_lazyfree
  - mm/swap.c:folio_deactivate
  - mm/swap.c:deactivate_file_folio
  - mm/swap.c:folio_add_lru
  - mm/swap.c:folio_mark_accessed
  - mm/swap.c:lru_add_fn
```
```
In mm/vmscan.c (ffffffff813e2380)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - mm/vmscan.c:__node_reclaim
  - mm/vmscan.c:__node_reclaim
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:mem_cgroup_shrink_node
  - mm/vmscan.c:mem_cgroup_shrink_node
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:evict_folios
  - mm/vmscan.c:scan_folios
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:isolate_lru_folios
  - mm/vmscan.c:pageout
  - mm/vmscan.c:reclaim_throttle
```
```
In mm/shrinker.c (ffffffff813e40fd)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - mm/shrinker.c:do_shrink_slab
  - mm/shrinker.c:do_shrink_slab
```
```
In mm/shmem.c (ffffffff813e67d6)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In mm/backing-dev.c (ffffffff813f67ee)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_register_va
```
```
In mm/mm_init.c (ffffffff83912d7f)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - mm/mm_init.c:init_unavailable_range
  - mm/mm_init.c:reserve_bootmem_region
```
```
In mm/percpu.c (ffffffff813f993d)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_free
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
```
```
In mm/compaction.c (ffffffff81406ed8)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
  - mm/compaction.c:wakeup_kcompactd
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compaction_suitable
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:compaction_defer_reset
  - mm/compaction.c:compaction_deferred
  - mm/compaction.c:defer_compaction
```
```
In mm/mmap_lock.c (ffffffff814139c5)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - mm/mmap_lock.c:__mmap_lock_do_trace_released
  - mm/mmap_lock.c:__mmap_lock_do_trace_released
  - mm/mmap_lock.c:__mmap_lock_do_trace_acquire_returned
  - mm/mmap_lock.c:__mmap_lock_do_trace_acquire_returned
  - mm/mmap_lock.c:__mmap_lock_do_trace_start_locking
  - mm/mmap_lock.c:__mmap_lock_do_trace_start_locking
```
```
In mm/memory.c (ffffffff8141b3c1)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - mm/memory.c:set_pte_range
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mlock.c (ffffffff81424ff5)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - mm/mlock.c:munlock_folio
  - mm/mlock.c:mlock_new_folio
  - mm/mlock.c:mlock_folio
  - mm/mlock.c:mlock_drain_local
```
```
In mm/mmap.c (ffffffff8142aa44)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:vm_unmapped_area
```
```
In mm/rmap.c (ffffffff8143aa61)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff8143ee9f)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_pfn_apply
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:vmap_pages_pud_range
```
```
In mm/page_alloc.c (ffffffff8144e7bf)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:free_unref_page
  - mm/page_alloc.c:free_unref_page_prepare
  - mm/page_alloc.c:rmqueue_bulk
  - mm/page_alloc.c:rmqueue_bulk
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcppages_bulk
```
```
In mm/memory_hotplug.c (ffffffff8222a08d)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
```
```
In mm/slub.c (ffffffff8145e3f2)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_alloc_bulk
  - mm/slub.c:kfree
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmalloc_node_trace
  - mm/slub.c:kmalloc_node_trace
  - mm/slub.c:kmalloc_trace
  - mm/slub.c:kmalloc_trace
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc
  - mm/slub.c:__kmalloc
  - mm/slub.c:__kmalloc
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:kmalloc_large
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_lru
  - mm/slub.c:kmem_cache_alloc_lru
  - mm/slub.c:kmem_cache_alloc
  - mm/slub.c:kmem_cache_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
```
```
In mm/hugetlb.c (0)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In mm/mempolicy.c (ffffffff81485ac0)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_pages_mpol
```
```
In mm/ksm.c (ffffffff81492721)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:__ksm_enter
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:scan_time_advisor
```
```
In mm/kfence/core.c (ffffffff8149391d)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In mm/kfence/report.c (ffffffff81495b13)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - mm/kfence/report.c:kfence_report_error
```
```
In mm/migrate.c (ffffffff8149a4be)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff814a8c19)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:mm_get_huge_zero_page
```
```
In mm/khugepaged.c (ffffffff814aecf9)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:hpage_collapse_scan_pmd
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (ffffffff814bf944)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_flush_foreign
  - mm/memcontrol.c:mem_cgroup_track_foreign_dirty_slowpath
```
```
In mm/memory-failure.c (ffffffff814c9242)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure_queue
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:action_result
```
```
In mm/page_isolation.c (ffffffff814ca9a9)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
```
```
In mm/zsmalloc.c (ffffffff814cd278)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:migrate_zspage
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:zs_object_copy
  - mm/zsmalloc.c:obj_free
  - mm/zsmalloc.c:obj_malloc
  - mm/zsmalloc.c:zs_map_object
  - mm/zsmalloc.c:zs_map_object
  - mm/zsmalloc.c:__zs_map_object
  - mm/zsmalloc.c:__zs_map_object
  - mm/zsmalloc.c:alloc_zspage
```
```
In mm/bootmem_info.c (ffffffff839206b5)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - mm/bootmem_info.c:register_page_bootmem_info_node
```
```
In fs/open.c (ffffffff814da14d)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
  - fs/open.c:vfs_fallocate
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:do_sys_ftruncate
```
```
In fs/read_write.c (ffffffff814e214f)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_iter_write
  - fs/read_write.c:vfs_iter_write
  - fs/read_write.c:vfs_iocb_iter_write
  - fs/read_write.c:vfs_iocb_iter_write
  - fs/read_write.c:vfs_write
  - fs/read_write.c:vfs_write
```
```
In fs/exec.c (ffffffff814eafb5)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - fs/exec.c:exec_binprm
  - fs/exec.c:__set_task_comm
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
```
```
In fs/pipe.c (ffffffff814eed18)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
```
```
In fs/dcache.c (ffffffff81505eec)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_unhash
  - fs/dcache.c:__d_lookup_unhash
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:___d_drop
```
```
In fs/inode.c (ffffffff8150c886)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - fs/inode.c:touch_atime
  - fs/inode.c:touch_atime
  - fs/inode.c:get_next_ino
```
```
In fs/file.c (ffffffff8150ddcd)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - fs/file.c:fd_install
```
```
In fs/namespace.c (ffffffff81512bef)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write
  - fs/namespace.c:mnt_drop_write
  - fs/namespace.c:mnt_want_write
  - fs/namespace.c:mnt_want_write
  - fs/namespace.c:mnt_get_write_access
```
```
In fs/fs-writeback.c (ffffffff8152b2d7)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_do_writeback
  - fs/fs-writeback.c:wb_writeback
  - fs/fs-writeback.c:wb_writeback
  - fs/fs-writeback.c:wb_writeback
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fs-writeback.c:write_inode
  - fs/fs-writeback.c:write_inode
  - fs/fs-writeback.c:queue_io
  - fs/fs-writeback.c:sb_clear_inode_writeback
  - fs/fs-writeback.c:sb_mark_inode_writeback
  - fs/fs-writeback.c:wb_start_background_writeback
  - fs/fs-writeback.c:wbc_detach_inode
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:wb_queue_work
```
```
In fs/splice.c (ffffffff8153213f)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:direct_splice_actor
  - fs/splice.c:direct_splice_actor
```
```
In fs/fs_struct.c (0)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In fs/remap_range.c (ffffffff8153c82f)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_clone_file_range
  - fs/remap_range.c:vfs_clone_file_range
```
```
In fs/buffer.c (ffffffff8153d765)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - fs/buffer.c:free_buffer_head
  - fs/buffer.c:alloc_buffer_head
  - fs/buffer.c:invalidate_bh_lru
  - fs/buffer.c:mark_buffer_dirty
```
```
In fs/userfaultfd.c (0)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In fs/aio.c (ffffffff8155d5c3)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - fs/aio.c:aio_write
  - fs/aio.c:aio_complete_rw
```
```
In fs/dax.c (ffffffff81566a29)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_insert_pfn_mkwrite
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pte_fault
  - fs/dax.c:dax_iomap_pte_fault
  - fs/dax.c:dax_fault_iter
  - fs/dax.c:dax_fault_cow_page
  - fs/dax.c:dax_pmd_load_hole
  - fs/dax.c:dax_pmd_load_hole
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_one
```
```
In fs/locks.c (ffffffff8157ad34)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - fs/locks.c:locks_remove_file
  - fs/locks.c:locks_remove_file
  - fs/locks.c:locks_remove_posix
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:generic_setlease
  - fs/locks.c:generic_setlease
  - fs/locks.c:generic_setlease
  - fs/locks.c:generic_add_lease
  - fs/locks.c:generic_add_lease
  - fs/locks.c:generic_add_lease
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:leases_conflict
  - fs/locks.c:time_out_leases
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:locks_get_lock_context
```
```
In fs/backing-file.c (ffffffff81581c7c)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - fs/backing-file.c:backing_aio_rw_complete
```
```
In fs/mbcache.c (ffffffff8158278b)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:__mb_cache_entry_free
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/coredump.c (ffffffff81586ec1)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
```
```
In fs/iomap/iter.c (ffffffff81589c43)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - fs/iomap/iter.c:iomap_iter
  - fs/iomap/iter.c:iomap_iter_done
  - fs/iomap/iter.c:iomap_iter_done
```
```
In fs/iomap/buffered-io.c (ffffffff8158c65b)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_do_writepage
  - fs/iomap/buffered-io.c:iomap_writepage_map
  - fs/iomap/buffered-io.c:iomap_release_folio
  - fs/iomap/buffered-io.c:iomap_readahead
  - fs/iomap/buffered-io.c:iomap_read_folio
```
```
In fs/iomap/direct-io.c (ffffffff8158f0aa)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:__iomap_dio_rw
  - fs/iomap/direct-io.c:__iomap_dio_rw
  - fs/iomap/direct-io.c:__iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_complete
```
```
In fs/quota/quota.c (ffffffff8159703e)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - fs/quota/quota.c:quotactl_block
  - fs/quota/quota.c:quotactl_block
```
```
In fs/proc/base.c (ffffffff815a71d7)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In fs/proc/kcore.c (ffffffff815b59c7)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - fs/proc/kcore.c:kclist_add_private
```
```
In fs/ext4/balloc.c (ffffffff815c8ad8)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ext4_jbd2.c (ffffffff815cbd04)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb
```
```
In fs/ext4/extents.c (ffffffff815d30a0)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/extents_status.c (ffffffff815da13f)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_insert_delayed_block
  - fs/ext4/extents_status.c:ext4_es_scan
  - fs/ext4/extents_status.c:ext4_es_scan
  - fs/ext4/extents_status.c:ext4_es_count
  - fs/ext4/extents_status.c:ext4_es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_cache_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_find_extent_range
  - fs/ext4/extents_status.c:ext4_es_find_extent_range
```
```
In fs/ext4/file.c (ffffffff815da51c)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_sample_last_mounted
  - fs/ext4/file.c:ext4_sample_last_mounted
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_huge_fault
  - fs/ext4/file.c:ext4_dax_huge_fault
```
```
In fs/ext4/fsmap.c (ffffffff815dcf6f)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/fsmap.c:ext4_getfsmap_logdev
  - fs/ext4/fsmap.c:ext4_getfsmap_logdev
  - fs/ext4/fsmap.c:ext4_getfsmap_helper
  - fs/ext4/fsmap.c:ext4_getfsmap_helper
```
```
In fs/ext4/fsync.c (ffffffff815dd619)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/ialloc.c (ffffffff815e038e)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff815e325c)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inode.c (ffffffff815f5389)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_update_other_inode_time
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_release_folio
  - fs/ext4/inode.c:__ext4_journalled_invalidate_folio
  - fs/ext4/inode.c:ext4_invalidate_folio
  - fs/ext4/inode.c:ext4_read_folio
  - fs/ext4/inode.c:ext4_alloc_da_blocks
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_do_writepages
  - fs/ext4/inode.c:ext4_do_writepages
  - fs/ext4/inode.c:ext4_do_writepages
  - fs/ext4/inode.c:mpage_map_one_extent
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_da_reserve_space
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (ffffffff815f6479)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioc_getfsmap
  - fs/ext4/ioctl.c:ext4_ioc_getfsmap
  - fs/ext4/ioctl.c:ext4_getfsmap_format
  - fs/ext4/ioctl.c:ext4_force_shutdown
  - fs/ext4/ioctl.c:ext4_update_backup_sb
  - fs/ext4/ioctl.c:ext4_update_primary_sb
```
```
In fs/ext4/mballoc.c (ffffffff815ffb8b)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_preallocations_should_retry
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_release_group_pa
  - fs/ext4/mballoc.c:ext4_mb_release_group_pa
  - fs/ext4/mballoc.c:ext4_mb_release_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_release_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_collect_stats
  - fs/ext4/mballoc.c:ext4_mb_collect_stats
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/mmp.c (ffffffff81607697)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/namei.c (ffffffff81611db0)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_unlink
  - fs/ext4/namei.c:ext4_unlink
```
```
In fs/ext4/super.c (ffffffff81630a7c)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:ext4_run_li_request
  - fs/ext4/super.c:ext4_run_li_request
  - fs/ext4/super.c:ext4_nfs_commit_metadata
  - fs/ext4/super.c:ext4_drop_inode
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
```
```
In fs/ext4/fast_commit.c (ffffffff8164840a)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
  - fs/ext4/fast_commit.c:ext4_fc_commit
  - fs/ext4/fast_commit.c:ext4_fc_update_stats
  - fs/ext4/fast_commit.c:ext4_fc_track_range
  - fs/ext4/fast_commit.c:ext4_fc_track_inode
  - fs/ext4/fast_commit.c:__ext4_fc_track_create
  - fs/ext4/fast_commit.c:__ext4_fc_track_link
  - fs/ext4/fast_commit.c:__ext4_fc_track_unlink
```
```
In fs/jbd2/transaction.c (ffffffff8164dafc)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:jbd2__journal_restart
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
  - fs/jbd2/transaction.c:jbd2__journal_start
```
```
In fs/jbd2/commit.c (ffffffff8165020c)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/checkpoint.c (ffffffff81652f7d)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_drop_transaction
  - fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_journal_shrink_checkpoint_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff8165cab4)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_journal_shrink_count
  - fs/jbd2/journal.c:jbd2_journal_shrink_scan
  - fs/jbd2/journal.c:jbd2_journal_shrink_scan
```
```
In fs/squashfs/file.c (ffffffff8166068a)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_read_folio
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (ffffffff81662cb0)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_read_folio
```
```
In fs/squashfs/decompressor_multi_percpu.c (ffffffff81664336)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - fs/squashfs/decompressor_multi_percpu.c:squashfs_decompress
```
```
In fs/fuse/dax.c (ffffffff816a3871)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - fs/fuse/dax.c:__fuse_dax_fault
  - fs/fuse/dax.c:__fuse_dax_fault
```
```
In ipc/util.c (ffffffff816b0dc0)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In security/selinux/avc.c (ffffffff816e0d3a)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_audit_post_callback
```
```
In security/smack/smack_lsm.c (ffffffff817147ba)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smk_ipv4_check
  - security/smack/smack_lsm.c:smack_netlbl_add
```
```
In security/tomoyo/domain.c (ffffffff81726f95)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In security/apparmor/capability.c (ffffffff817378b7)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - security/apparmor/capability.c:audit_caps
```
```
In security/apparmor/policy_unpack.c (ffffffff81747ba9)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In security/apparmor/lsm.c (ffffffff81752f98)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - security/apparmor/lsm.c:aa_put_buffer
  - security/apparmor/lsm.c:aa_put_buffer
  - security/apparmor/lsm.c:aa_put_buffer
  - security/apparmor/lsm.c:aa_get_buffer
  - security/apparmor/lsm.c:aa_get_buffer
  - security/apparmor/lsm.c:aa_get_buffer
```
```
In block/bio.c (ffffffff817ac87b)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - block/bio.c:bio_endio
  - block/bio.c:bio_put_percpu_cache
  - block/bio.c:bio_alloc_bioset
```
```
In block/blk-core.c (ffffffff817b4935)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - block/blk-core.c:bdev_end_io_acct
  - block/blk-core.c:bio_start_io_acct
  - block/blk-core.c:submit_bio_noacct
  - block/blk-core.c:submit_bio_noacct_nocheck
```
```
In block/blk-flush.c (ffffffff817b731e)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-merge.c (ffffffff817bd257)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_front_merge
  - block/blk-merge.c:bio_attempt_back_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:__bio_split_to_limits
```
```
In block/blk-mq.c (ffffffff817c5c02)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - block/blk-mq.c:blk_insert_cloned_request
  - block/blk-mq.c:blk_insert_cloned_request
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_dispatch_plug_list
  - block/blk-mq.c:blk_mq_insert_request
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:blk_execute_rq
  - block/blk-mq.c:blk_execute_rq
  - block/blk-mq.c:blk_execute_rq_nowait
  - block/blk-mq.c:blk_execute_rq_nowait
  - block/blk-mq.c:blk_add_rq_to_plug
  - block/blk-mq.c:blk_add_rq_to_plug
  - block/blk-mq.c:blk_mq_start_request
  - block/blk-mq.c:blk_mq_complete_request_remote
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:blk_account_io_done
  - block/blk-mq.c:blk_account_io_done
  - block/blk-mq.c:blk_update_request
  - block/blk-mq.c:blk_update_request
```
```
In block/blk-stat.c (ffffffff817cb51b)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_add
```
```
In block/genhd.c (ffffffff817d06c0)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - block/genhd.c:diskstats_show
  - block/genhd.c:part_stat_show
```
```
In block/blk-cgroup.c (ffffffff817e671c)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - block/blk-cgroup.c:blk_cgroup_bio_start
```
```
In block/blk-iocost.c (ffffffff817f493b)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_merge
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:adjust_inuse_and_calc_cost
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_check_iocgs
  - block/blk-iocost.c:ioc_forgive_debts
  - block/blk-iocost.c:transfer_surpluses
  - block/blk-iocost.c:iocg_wake_fn
  - block/blk-iocost.c:iocg_incur_debt
  - block/blk-iocost.c:iocg_activate
```
```
In block/mq-deadline.c (ffffffff817f806c)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In block/blk-wbt.c (ffffffff817ff3f3)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:rwb_trace_step
```
```
In io_uring/io_uring.c (ffffffff81816b86)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_create
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/io_uring.c:io_submit_sqes
  - io_uring/io_uring.c:io_submit_sqes
  - io_uring/io_uring.c:io_submit_fail_init
  - io_uring/io_uring.c:io_file_get_normal
  - io_uring/io_uring.c:io_drain_req
  - io_uring/io_uring.c:__io_submit_flush_completions
  - io_uring/io_uring.c:__io_run_local_work
  - io_uring/io_uring.c:tctx_task_work
  - io_uring/io_uring.c:__io_req_complete_post
  - io_uring/io_uring.c:io_fill_cqe_aux
  - io_uring/io_uring.c:io_cqring_event_overflow
  - io_uring/io_uring.c:io_queue_iowq
```
```
In io_uring/timeout.c (ffffffff8181e965)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - io_uring/timeout.c:io_disarm_next
```
```
In io_uring/poll.c (ffffffff81823118)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - io_uring/poll.c:io_arm_poll_handler
  - io_uring/poll.c:__io_poll_execute
```
```
In io_uring/rw.c (ffffffff81829e30)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - io_uring/rw.c:io_write
  - io_uring/rw.c:io_write
```
```
In io_uring/register.c (ffffffff8182bf6f)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - io_uring/register.c:__do_sys_io_uring_register
```
```
In lib/scatterlist.c (ffffffff818537b3)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In lib/iov_iter.c (ffffffff818582fe)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - lib/iov_iter.c:copy_page_from_iter_atomic
```
```
In lib/rhashtable.c (ffffffff8185e9d2)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In lib/irq_poll.c (ffffffff81927b10)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_cpu_dead
```
```
In lib/stackdepot.c (ffffffff81928960)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - lib/stackdepot.c:stack_depot_save_flags
  - lib/stackdepot.c:stack_depot_save_flags
```
```
In arch/x86/lib/msr-smp.c (ffffffff8192fd86)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:wrmsr_on_cpus
  - arch/x86/lib/msr-smp.c:rdmsr_on_cpus
```
```
In arch/x86/lib/msr.c (ffffffff81930869)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:do_trace_rdpmc
  - arch/x86/lib/msr.c:do_trace_read_msr
  - arch/x86/lib/msr.c:do_trace_write_msr
```
```
In drivers/gpio/gpiolib.c (ffffffff8194aaf0)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_source_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_drain_value_commit
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_input
```
```
In drivers/pwm/core.c (ffffffff8195a6dd)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/pwm/core.c:__pwm_apply
  - drivers/pwm/core.c:pwm_device_request
```
```
In drivers/pci/pcie/aer.c (ffffffff81988948)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:pci_print_aer
  - drivers/pci/pcie/aer.c:aer_print_error
```
```
In drivers/acpi/sleep.c (ffffffff819e757c)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_suspend_enter
  - drivers/acpi/sleep.c:acpi_suspend_enter
```
```
In drivers/acpi/apei/ghes.c (ffffffff81a7b350)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In drivers/clk/clk.c (ffffffff81a8d31f)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_set_duty_cycle_nolock
  - drivers/clk/clk.c:clk_core_set_duty_cycle_nolock
  - drivers/clk/clk.c:clk_core_set_phase_nolock
  - drivers/clk/clk.c:clk_core_set_phase_nolock
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_calc_new_rates
  - drivers/clk/clk.c:clk_calc_new_rates
  - drivers/clk/clk.c:clk_round_rate
  - drivers/clk/clk.c:clk_round_rate
  - drivers/clk/clk.c:clk_hw_round_rate
  - drivers/clk/clk.c:clk_hw_round_rate
  - drivers/clk/clk.c:clk_core_round_rate_nolock
  - drivers/clk/clk.c:clk_core_round_rate_nolock
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_unprepare_unused_subtree
  - drivers/clk/clk.c:clk_unprepare_unused_subtree
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/clk/clk.c:clk_core_prepare
  - drivers/clk/clk.c:clk_core_prepare
  - drivers/clk/clk.c:clk_core_unprepare
  - drivers/clk/clk.c:clk_core_unprepare
  - drivers/clk/clk.c:clk_mux_determine_rate_flags
  - drivers/clk/clk.c:clk_mux_determine_rate_flags
```
```
In drivers/xen/events/events_2l.c (ffffffff81abddca)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81acca0d)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/regulator/core.c (ffffffff81ad79ef)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
```
```
In drivers/tty/sysrq.c (0)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In drivers/char/random.c (ffffffff81b33aaf)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/char/random.c:try_to_generate_entropy
```
```
In drivers/char/virtio_console.c (ffffffff81b34f58)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/iommu/intel/dmar.c (ffffffff81b5ed77)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:qi_submit_sync
```
```
In drivers/iommu/intel/svm.c (ffffffff81b6c3e4)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:prq_event_thread
```
```
In drivers/iommu/iommu.c (ffffffff81b7492e)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:report_iommu_fault
  - drivers/iommu/iommu.c:__iommu_unmap
  - drivers/iommu/iommu.c:__iommu_map
  - drivers/iommu/iommu.c:iommu_group_alloc_device
```
```
In drivers/iommu/dma-iommu.c (ffffffff81b7b159)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_map_page
```
```
In drivers/connector/cn_proc.c (ffffffff81b838b9)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/connector/cn_proc.c:proc_exit_connector
  - drivers/connector/cn_proc.c:proc_coredump_connector
  - drivers/connector/cn_proc.c:proc_comm_connector
  - drivers/connector/cn_proc.c:proc_ptrace_connector
  - drivers/connector/cn_proc.c:proc_sid_connector
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/connector/cn_proc.c:proc_exec_connector
  - drivers/connector/cn_proc.c:proc_fork_connector
```
```
In drivers/base/syscore.c (ffffffff81b91b5d)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
```
```
In drivers/base/devres.c (ffffffff81b97c43)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/base/devres.c:__devm_alloc_percpu
  - drivers/base/devres.c:devm_krealloc
  - drivers/base/devres.c:__devm_add_action
  - drivers/base/devres.c:devres_remove_group
  - drivers/base/devres.c:devres_close_group
  - drivers/base/devres.c:devres_open_group
  - drivers/base/devres.c:release_nodes
  - drivers/base/devres.c:devres_remove
  - drivers/base/devres.c:devres_get
```
```
In drivers/base/power/qos.c (ffffffff81ba4da1)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/base/power/qos.c:__dev_pm_qos_remove_request
  - drivers/base/power/qos.c:__dev_pm_qos_update_request
  - drivers/base/power/qos.c:__dev_pm_qos_add_request
```
```
In drivers/base/power/runtime.c (ffffffff81ba814c)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:update_autosuspend
  - drivers/base/power/runtime.c:pm_runtime_allow
  - drivers/base/power/runtime.c:pm_runtime_get_if_active
  - drivers/base/power/runtime.c:__pm_runtime_suspend
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
```
```
In drivers/base/power/main.c (ffffffff81badb72)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_noirq_suspend_devices
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/base/power/main.c:dpm_run_callback
  - drivers/base/power/main.c:dpm_run_callback
```
```
In drivers/base/power/wakeup.c (ffffffff81baee17)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_activate
```
```
In drivers/base/regmap/regmap.c (ffffffff81bbd2bc)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_async_complete_cb
  - drivers/base/regmap/regmap.c:regmap_bulk_read
  - drivers/base/regmap/regmap.c:_regmap_read
  - drivers/base/regmap/regmap.c:_regmap_raw_read
  - drivers/base/regmap/regmap.c:_regmap_raw_read
  - drivers/base/regmap/regmap.c:_regmap_raw_multi_reg_write
  - drivers/base/regmap/regmap.c:_regmap_raw_multi_reg_write
  - drivers/base/regmap/regmap.c:regmap_bulk_write
  - drivers/base/regmap/regmap.c:_regmap_write
  - drivers/base/regmap/regmap.c:_regmap_bus_formatted_write
  - drivers/base/regmap/regmap.c:_regmap_bus_formatted_write
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
```
```
In drivers/base/regmap/regcache.c (ffffffff81bc321e)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/base/regmap/regcache.c:regcache_cache_bypass
  - drivers/base/regmap/regcache.c:regcache_cache_only
  - drivers/base/regmap/regcache.c:regcache_drop_region
  - drivers/base/regmap/regcache.c:regcache_sync_region
  - drivers/base/regmap/regcache.c:regcache_sync_region
  - drivers/base/regmap/regcache.c:regcache_sync
  - drivers/base/regmap/regcache.c:regcache_sync
  - drivers/base/regmap/regcache.c:regcache_read
```
```
In drivers/block/xen-blkfront.c (ffffffff81bd81d7)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_completion
  - drivers/block/xen-blkfront.c:blkif_copy_from_grant
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81c1414a)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:__dma_fence_enable_signaling
  - drivers/dma-buf/dma-fence.c:dma_fence_release
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_signal_timestamp_locked
  - drivers/dma-buf/dma-fence.c:dma_fence_allocate_private_stub
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81c1a2c9)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
```
```
In drivers/scsi/scsi_error.c (ffffffff81c244eb)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_timeout
```
```
In drivers/scsi/scsi_lib.c (ffffffff81c26a64)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
  - drivers/scsi/scsi_lib.c:scsi_done_internal
  - drivers/scsi/scsi_lib.c:scsi_dispatch_cmd
  - drivers/scsi/scsi_lib.c:scsi_dispatch_cmd
```
```
In drivers/scsi/sd_zbc.c (ffffffff81c42179)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_zone_wp_update
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
```
```
In drivers/ata/libata-core.c (ffffffff81c544a1)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-core.c:ata_qc_complete
  - drivers/ata/libata-core.c:ata_qc_complete
  - drivers/ata/libata-core.c:ata_qc_complete
```
```
In drivers/ata/libata-eh.c (ffffffff81c664d9)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_done
  - drivers/ata/libata-eh.c:ata_eh_about_to_do
  - drivers/ata/libata-eh.c:ata_eh_thaw_port
  - drivers/ata/libata-eh.c:__ata_port_freeze
```
```
In drivers/ata/libata-sff.c (ffffffff81c6ed24)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_bmdma_post_internal_cmd
  - drivers/ata/libata-sff.c:ata_bmdma_error_handler
  - drivers/ata/libata-sff.c:ata_bmdma_error_handler
  - drivers/ata/libata-sff.c:ata_bmdma_port_intr
  - drivers/ata/libata-sff.c:ata_bmdma_port_intr
  - drivers/ata/libata-sff.c:ata_bmdma_qc_issue
  - drivers/ata/libata-sff.c:ata_bmdma_qc_issue
  - drivers/ata/libata-sff.c:ata_bmdma_qc_issue
  - drivers/ata/libata-sff.c:ata_bmdma_qc_issue
  - drivers/ata/libata-sff.c:ata_bmdma_qc_issue
  - drivers/ata/libata-sff.c:__ata_sff_port_intr
  - drivers/ata/libata-sff.c:ata_sff_flush_pio_task
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:__atapi_pio_bytes
  - drivers/ata/libata-sff.c:__atapi_pio_bytes
  - drivers/ata/libata-sff.c:ata_pio_sector
  - drivers/ata/libata-sff.c:ata_tf_to_host
  - drivers/ata/libata-sff.c:ata_tf_to_host
```
```
In drivers/ata/ata_piix.c (ffffffff81c757a7)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/ata/ata_piix.c:piix_irq_check
```
```
In drivers/gpu/drm/drm_cache.c (ffffffff81c81271)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_cache.c:drm_clflush_page
```
```
In drivers/gpu/drm/drm_vblank.c (ffffffff81cb69c2)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_vblank.c:drm_handle_vblank_events
  - drivers/gpu/drm/drm_vblank.c:drm_queue_vblank_event
  - drivers/gpu/drm/drm_vblank.c:send_vblank_event
```
```
In drivers/spi/spi.c (ffffffff81ce043e)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_sync
  - drivers/spi/spi.c:__spi_sync
  - drivers/spi/spi.c:__spi_sync
  - drivers/spi/spi.c:__spi_sync
  - drivers/spi/spi.c:__spi_sync
  - drivers/spi/spi.c:__spi_async
  - drivers/spi/spi.c:__spi_async
  - drivers/spi/spi.c:__spi_async
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:__spi_split_transfer_maxsize
  - drivers/spi/spi.c:__spi_split_transfer_maxsize
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_transfer_message
  - drivers/spi/spi.c:__spi_pump_transfer_message
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_transfer_wait
  - drivers/spi/spi.c:spi_transfer_wait
  - drivers/spi/spi.c:spi_set_cs
  - drivers/spi/spi.c:spi_statistics_add_transfer_stats
```
```
In drivers/net/phy/mdio_bus.c (ffffffff81cf36d4)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:__mdiobus_c45_write
  - drivers/net/phy/mdio_bus.c:__mdiobus_c45_write
  - drivers/net/phy/mdio_bus.c:__mdiobus_c45_read
  - drivers/net/phy/mdio_bus.c:__mdiobus_c45_read
  - drivers/net/phy/mdio_bus.c:__mdiobus_write
  - drivers/net/phy/mdio_bus.c:__mdiobus_write
  - drivers/net/phy/mdio_bus.c:__mdiobus_read
  - drivers/net/phy/mdio_bus.c:__mdiobus_read
```
```
In drivers/net/tun.c (ffffffff81d01027)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_xdp_act
  - drivers/net/tun.c:tun_rx_batched
  - drivers/net/tun.c:tun_rx_batched
  - drivers/net/tun.c:tun_napi_alloc_frags
```
```
In drivers/net/virtio_net.c (ffffffff81d0abcb)
Location: arch/x86/include/asm/preempt.h:77
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
  - drivers/net/virtio_net.c:virtnet_xdp_handler
  - drivers/net/virtio_net.c:virtnet_xdp_handler
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81d1a635)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
```
```
In drivers/net/xen-netfront.c (ffffffff81d219aa)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:netfront_resume
```
```
In drivers/net/net_failover.c (ffffffff81d243eb)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/net/net_failover.c:net_failover_slave_register
  - drivers/net/net_failover.c:net_failover_close
  - drivers/net/net_failover.c:net_failover_open
```
```
In drivers/usb/host/xhci.c (ffffffff81d9a9a0)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81d9ec4a)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_ring_alloc
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81da2759)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:queue_trb
  - drivers/usb/host/xhci-ring.c:xhci_handle_event
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_ring_ep_doorbell
  - drivers/usb/host/xhci-ring.c:inc_enq
  - drivers/usb/host/xhci-ring.c:inc_deq
```
```
In drivers/usb/host/xhci-hub.c (ffffffff81dacb3a)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81db44c4)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events
  - drivers/usb/host/xhci-dbgcap.c:dbc_handle_xfer_event
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_queue_bulk_tx
  - drivers/usb/host/xhci-dbgcap.c:dbc_free_request
  - drivers/usb/host/xhci-dbgcap.c:dbc_alloc_request
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
```
```
In drivers/rtc/interface.c (ffffffff81ddab07)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_set_offset
  - drivers/rtc/interface.c:rtc_read_offset
  - drivers/rtc/interface.c:rtc_timer_cancel
  - drivers/rtc/interface.c:rtc_timer_start
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_alarm_disable
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_irq_set_freq
  - drivers/rtc/interface.c:rtc_irq_set_state
  - drivers/rtc/interface.c:rtc_update_irq_enable
  - drivers/rtc/interface.c:rtc_alarm_irq_enable
  - drivers/rtc/interface.c:rtc_initialize_alarm
  - drivers/rtc/interface.c:__rtc_set_alarm
  - drivers/rtc/interface.c:rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:rtc_read_time
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81de2dfc)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff81de6bb4)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In drivers/hwmon/hwmon.c (ffffffff81dfa7af)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:hwmon_attr_store
  - drivers/hwmon/hwmon.c:hwmon_attr_show_string
  - drivers/hwmon/hwmon.c:hwmon_attr_show
```
```
In drivers/thermal/thermal_core.c (ffffffff81dfdc55)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In drivers/thermal/thermal_helpers.c (ffffffff81e03073)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/thermal/thermal_helpers.c:__thermal_cdev_update
```
```
In drivers/thermal/gov_fair_share.c (ffffffff81e056e6)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/thermal/gov_fair_share.c:fair_share_throttle
```
```
In drivers/thermal/gov_step_wise.c (ffffffff81e05c81)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/thermal/gov_step_wise.c:thermal_zone_trip_update
```
```
In drivers/thermal/gov_power_allocator.c (ffffffff81e07311)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/thermal/gov_power_allocator.c:pid_controller
```
```
In drivers/thermal/devfreq_cooling.c (ffffffff81e0861b)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_power2state
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power
```
```
In drivers/thermal/intel/therm_throt.c (ffffffff81e08b14)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_package_throttle_total_time_ms
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_core_throttle_total_time_ms
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_package_throttle_max_time_ms
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_core_throttle_max_time_ms
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_package_power_limit_count
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_package_throttle_count
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_core_power_limit_count
  - drivers/thermal/intel/therm_throt.c:therm_throt_device_show_core_throttle_count
```
```
In drivers/watchdog/watchdog_core.c (ffffffff81e0ae7b)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_core.c:watchdog_reboot_notifier
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81e0d186)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_stop
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
```
```
In drivers/md/md.c (ffffffff81e11c23)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/md/md.c:md_submit_discard_bio
```
```
In drivers/md/md-bitmap.c (ffffffff81e28e31)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_file_clear_bit
  - drivers/md/md-bitmap.c:md_bitmap_file_set_bit
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_new_disk_sb
  - drivers/md/md-bitmap.c:md_bitmap_print_sb
```
```
In drivers/md/dm.c (ffffffff81e2ff83)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_split_and_process_bio
  - drivers/md/dm.c:dm_submit_bio_remap
```
```
In drivers/md/dm-stats.c (ffffffff81e3d630)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stat_for_entry
```
```
In drivers/md/dm-rq.c (ffffffff81e3fc7f)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:map_request
```
```
In drivers/edac/edac_mc.c (ffffffff81e4175b)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
  - drivers/edac/edac_mc.c:edac_mc_scrub_block
  - drivers/edac/edac_mc.c:edac_mc_scrub_block
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81e5114c)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_driver_fast_switch
  - drivers/cpufreq/cpufreq.c:cpufreq_notify_transition
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81e54e30)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_init
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81e57456)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target
```
```
In drivers/cpufreq/amd-pstate.c (ffffffff81e5a924)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/cpufreq/amd-pstate.c:amd_pstate_update
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81e6292a)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_adjust_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_adjust_pstate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_pstate
```
```
In drivers/cpuidle/cpuidle.c (ffffffff82224e64)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_use_deepest_state
```
```
In drivers/cpuidle/driver.c (ffffffff81e64805)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In drivers/cpuidle/governors/haltpoll.c (ffffffff81e687c6)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In drivers/mmc/core/core.c (ffffffff81e6aa5c)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_cqe_request_done
  - drivers/mmc/core/core.c:mmc_cqe_start_req
  - drivers/mmc/core/core.c:__mmc_start_request
  - drivers/mmc/core/core.c:mmc_request_done
```
```
In drivers/firmware/efi/capsule.c (ffffffff81e87c5c)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/firmware/efi/capsule.c:efi_capsule_update
```
```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff81e95497)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In drivers/devfreq/devfreq.c (ffffffff81ea4e9a)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_monitor
  - drivers/devfreq/devfreq.c:devfreq_set_target
```
```
In drivers/ras/ras.c (ffffffff81eaed65)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/ras/ras.c:log_arm_hw_error
  - drivers/ras/ras.c:log_non_standard_event
```
```
In drivers/ras/cec.c (ffffffff81eaf3bd)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/ras/cec.c:cec_add_elem
```
```
In drivers/interconnect/core.c (ffffffff81eb4742)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/interconnect/core.c:icc_set_bw
  - drivers/interconnect/core.c:icc_set_bw
```
```
In net/socket.c (ffffffff81ebdd69)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/socket.c:call_trace_sock_recv_length
```
```
In net/core/sock.c (ffffffff81ec5f17)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/core/sock.c:sock_def_readable
  - net/core/sock.c:__sk_mem_reduce_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:sock_i_ino
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:__sock_queue_rcv_skb
  - net/core/sock.c:sk_error_report
```
```
In net/core/skbuff.c (ffffffff81ed0f34)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:__consume_stateless_skb
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:kfree_skb_list_reason
  - net/core/skbuff.c:kfree_skb_list_reason
  - net/core/skbuff.c:kfree_skb_reason
  - net/core/skbuff.c:kfree_skb_reason
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_frag_align
  - net/core/skbuff.c:napi_get_frags_check
```
```
In net/core/datagram.c (ffffffff81edcf27)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_datagram_iter
```
```
In net/core/gen_estimator.c (ffffffff81ee1171)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/net_namespace.c (ffffffff81ee234c)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/core/dev.c (ffffffff81efecd2)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/core/dev.c:bpf_xdp_link_attach
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:__dev_set_allmulti
  - net/core/dev.c:dev_set_promiscuity
  - net/core/dev.c:napi_threaded_poll
  - net/core/dev.c:__napi_poll
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:flush_backlog
  - net/core/dev.c:netif_receive_skb_list
  - net/core/dev.c:netif_receive_skb_list
  - net/core/dev.c:netif_receive_skb
  - net/core/dev.c:netif_receive_skb
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:__netif_rx
  - net/core/dev.c:__netif_rx
  - net/core/dev.c:netif_rx_internal
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:__dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_qdisc_enqueue
  - net/core/dev.c:dev_hard_start_xmit
  - net/core/dev.c:dev_hard_start_xmit
  - net/core/dev.c:__dev_open
```
```
In net/core/dev_addr_lists.c (ffffffff81f02b65)
Location: arch/x86/include/asm/preempt.h:77
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
In net/core/dst.c (ffffffff81f03db5)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/core/dst.c:dst_destroy
```
```
In net/core/neighbour.c (ffffffff81f0af73)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_cleanup_and_release
```
```
In net/core/rtnetlink.c (ffffffff81f1590e)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_fdb_dump
```
```
In net/core/filter.c (ffffffff81f22bcc)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_socket_ptr_cookie
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_redirect_frame
  - net/core/filter.c:xdp_do_redirect_frame
  - net/core/filter.c:xdp_do_redirect_frame
  - net/core/filter.c:xdp_do_redirect_frame
  - net/core/filter.c:xdp_do_redirect
  - net/core/filter.c:xdp_do_redirect
  - net/core/filter.c:xdp_do_redirect
  - net/core/filter.c:xdp_do_redirect
  - net/core/filter.c:bpf_out_neigh_v6
```
```
In net/core/sock_diag.c (ffffffff81f34e25)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_save_cookie
  - net/core/sock_diag.c:sock_diag_check_cookie
```
```
In net/core/xdp.c (ffffffff81f388e4)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_rxq_info_reg_mem_model
  - net/core/xdp.c:mem_allocator_disconnect
```
```
In net/core/gro.c (ffffffff81f3c867)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/core/gro.c:napi_gro_frags
  - net/core/gro.c:napi_gro_frags
  - net/core/gro.c:napi_gro_receive
  - net/core/gro.c:napi_gro_receive
```
```
In net/core/page_pool.c (ffffffff81f43a51)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_update_nid
  - net/core/page_pool.c:page_pool_return_page
  - net/core/page_pool.c:page_pool_inflight
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
  - net/core/page_pool.c:__page_pool_alloc_page_order
```
```
In net/core/net-procfs.c (ffffffff81f469f1)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In net/core/netpoll.c (ffffffff81f47035)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
  - net/core/netpoll.c:poll_one_napi
```
```
In net/core/net-traces.c (ffffffff81f53c5a)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/core/net-traces.c:perf_trace_tcp_probe
  - net/core/net-traces.c:perf_trace_tcp_event_sk
  - net/core/net-traces.c:trace_event_raw_event_tcp_probe
  - net/core/net-traces.c:trace_event_raw_event_tcp_event_sk
```
```
In net/core/lwt_bpf.c (ffffffff81f6080e)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In net/core/skmsg.c (ffffffff81f6424a)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_data_ready
```
```
In net/core/sock_map.c (ffffffff81f69a2c)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_update_elem
```
```
In net/sched/sch_generic.c (ffffffff81f70f52)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:__qdisc_destroy
  - net/sched/sch_generic.c:qdisc_reset
  - net/sched/sch_generic.c:qdisc_create_dflt
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/sched/sch_api.c (ffffffff81f74968)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_create
```
```
In net/sched/act_api.c (ffffffff81f80d53)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_update_hw_stats
```
```
In net/netlink/af_netlink.c (ffffffff81f85d45)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:do_trace_netlink_extack
```
```
In net/bpf/test_run.c (ffffffff81f93d1e)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_sk_lookup
  - net/bpf/test_run.c:bpf_prog_test_run_sk_lookup
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_prog_test_run_raw_tp
  - net/bpf/test_run.c:bpf_prog_test_run_tracing
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_timer_continue
```
```
In net/netfilter/nf_log.c (ffffffff81fac925)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/netfilter/nf_log.c:nf_log_buf_open
```
```
In net/netfilter/nf_queue.c (ffffffff81fad950)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_reinject
```
```
In net/ipv4/inet_hashtables.c (ffffffff81fc7ba0)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81fc8f4d)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81fcaf33)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/tcp.c (ffffffff81fd4b88)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_abort
  - net/ipv4/tcp.c:tcp_abort
  - net/ipv4/tcp.c:tcp_abort
  - net/ipv4/tcp.c:__tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff81fe460f)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_reset
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
```
```
In net/ipv4/tcp_output.c (ffffffff81fe5f35)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_rtx_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff7559)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ff8694)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/tcp_cong.c (ffffffff81ffa6c4)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_set_ca_state
```
```
In net/ipv4/udp.c (ffffffff820092a2)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/icmp.c (ffffffff82011b09)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_reply
```
```
In net/ipv4/af_inet.c (ffffffff8201c052)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sk_state_store
  - net/ipv4/af_inet.c:inet_sk_set_state
```
```
In net/ipv4/fib_frontend.c (ffffffff820231f2)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_lookup
```
```
In net/ipv4/fib_trie.c (ffffffff8202de32)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv4/inet_fragment.c (ffffffff820308c2)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff8203434e)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff820466b0)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In net/ipv4/tcp_sigpool.c (ffffffff8204c935)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/tcp_sigpool.c:tcp_sigpool_start
```
```
In net/xfrm/xfrm_policy.c (ffffffff820602c2)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In net/xfrm/xfrm_state.c (0)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In net/xfrm/xfrm_input.c (ffffffff8206df05)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/espintcp.c (ffffffff8207486e)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_data_ready
  - net/xfrm/espintcp.c:handle_esp
```
```
In net/ipv6/addrconf.c (ffffffff82093874)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
```
```
In net/ipv6/route.c (ffffffff8209ed2d)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:fib6_table_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
```
```
In net/ipv6/udp.c (ffffffff820b7171)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/icmp.c (ffffffff820bed5c)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820cd707)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
```
```
In net/ipv6/ioam6.c (ffffffff820d9211)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/ip6mr.c (ffffffff820dd854)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff820e96de)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
```
```
In net/ipv6/seg6_local.c (ffffffff820edc17)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
```
```
In net/ipv6/seg6_hmac.c (ffffffff820eded1)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff820f00fa)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
```
```
In net/devlink/health.c (ffffffff82113dff)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/devlink/health.c:devlink_health_report
  - net/devlink/health.c:devlink_health_report
```
```
In net/devlink/trap.c (ffffffff82114918)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/devlink/trap.c:devlink_trap_report
```
```
In net/mptcp/protocol.c (ffffffff8214d6a1)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_finish_join
  - net/mptcp/protocol.c:mptcp_subflow_get_send
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
```
```
In net/mptcp/subflow.c (ffffffff8214e43c)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_write_space
  - net/mptcp/subflow.c:subflow_data_ready
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:get_mapping_status
```
```
In net/mptcp/options.c (ffffffff821536ef)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/mptcp/options.c:ack_update_msk
```
```
In net/mctp/af_mctp.c (ffffffff82163c66)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In net/mctp/route.c (ffffffff82167293)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_alloc_local_tag
  - net/mctp/route.c:mctp_route_input
  - net/mctp/route.c:__mctp_key_done_in
```
```
In net/handshake/alert.c (ffffffff82168898)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/handshake/alert.c:tls_alert_recv
  - net/handshake/alert.c:tls_alert_send
```
```
In net/handshake/netlink.c (ffffffff821691cd)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/handshake/netlink.c:handshake_nl_done_doit
  - net/handshake/netlink.c:handshake_nl_done_doit
  - net/handshake/netlink.c:handshake_nl_accept_doit
  - net/handshake/netlink.c:handshake_nl_accept_doit
```
```
In net/handshake/request.c (ffffffff8216a140)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/handshake/request.c:handshake_req_cancel
  - net/handshake/request.c:handshake_req_cancel
  - net/handshake/request.c:handshake_req_cancel
  - net/handshake/request.c:handshake_complete
  - net/handshake/request.c:handshake_req_submit
  - net/handshake/request.c:handshake_req_submit
  - net/handshake/request.c:handshake_req_submit
  - net/handshake/request.c:handshake_sk_destruct
```
```
In lib/bug.c (ffffffff82176d60)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - lib/bug.c:generic_bug_clear_once
  - lib/bug.c:report_bug
  - lib/bug.c:find_bug
```
```
In lib/buildid.c (ffffffff82177015)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - lib/buildid.c:build_id_parse
```
```
In lib/flex_proportions.c (0)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In lib/maple_tree.c (ffffffff8218defb)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - lib/maple_tree.c:mt_find
  - lib/maple_tree.c:mtree_erase
  - lib/maple_tree.c:mtree_store_range
  - lib/maple_tree.c:mtree_load
  - lib/maple_tree.c:mas_store_prealloc
  - lib/maple_tree.c:mas_store_gfp
  - lib/maple_tree.c:mas_store
  - lib/maple_tree.c:mas_wr_bnode
  - lib/maple_tree.c:mas_wr_append
  - lib/maple_tree.c:mas_wr_slot_store
  - lib/maple_tree.c:mas_wr_walk
```
```
In lib/nmi_backtrace.c (ffffffff82191630)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
```
In lib/radix-tree.c (ffffffff821922e7)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - lib/radix-tree.c:__radix_tree_preload
  - lib/radix-tree.c:__radix_tree_preload
```
```
In arch/x86/lib/delay.c (ffffffff821a55b5)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/lib/delay.c:delay_tsc
  - arch/x86/lib/delay.c:delay_tsc
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
In arch/arm64/kernel/irq.c (ffff800010086ea0)
Location: arch/arm64/include/asm/preempt.h:44
Inline: True
```
```
In arch/arm64/kernel/traps.c (ffff800010095790)
Location: arch/arm64/include/asm/preempt.h:44
Inline: True
Inline callers:
  - arch/arm64/kernel/traps.c:do_serror
```
```
In arch/arm64/kernel/acpi.c (ffff8000100a94f4)
Location: arch/arm64/include/asm/preempt.h:44
Inline: True
Inline callers:
  - arch/arm64/kernel/acpi.c:apei_claim_sea
```
```
In arch/arm64/kernel/sdei.c (ffff800010da7d30)
Location: arch/arm64/include/asm/preempt.h:44
Inline: True
Inline callers:
  - arch/arm64/kernel/sdei.c:__sdei_handler
```
```
In kernel/softirq.c (ffff8000100ff11c)
Location: arch/arm64/include/asm/preempt.h:44
Inline: True
Inline callers:
  - kernel/softirq.c:irq_enter
  - kernel/softirq.c:irq_enter
  - kernel/softirq.c:__do_softirq
```
```
In kernel/irq/manage.c (ffff800010179bf8)
Location: arch/arm64/include/asm/preempt.h:44
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_forced_thread_fn
```
```
In kernel/rcu/update.c (ffff800010188f1c)
Location: arch/arm64/include/asm/preempt.h:44
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/srcutree.c (ffff80001018a8b0)
Location: arch/arm64/include/asm/preempt.h:44
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
```
```
In kernel/rcu/tree.c (ffff8000101904c4)
Location: arch/arm64/include/asm/preempt.h:44
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_cpu_kthread
```
```
In kernel/time/hrtimer.c (ffff8000101a2768)
Location: arch/arm64/include/asm/preempt.h:44
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
```
```
In kernel/cgroup/cgroup.c (ffff8000101d0d78)
Location: arch/arm64/include/asm/preempt.h:44
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_idr_remove
  - kernel/cgroup/cgroup.c:cgroup_idr_replace
```
```
In kernel/stop_machine.c (ffff8000101e8064)
Location: arch/arm64/include/asm/preempt.h:44
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
```
```
In kernel/bpf/core.c (ffff80001025e1cc)
Location: arch/arm64/include/asm/preempt.h:44
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
```
```
In kernel/bpf/syscall.c (ffff8000102654fc)
Location: arch/arm64/include/asm/preempt.h:44
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
Location: arch/arm64/include/asm/preempt.h:44
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
Location: arch/arm64/include/asm/preempt.h:44
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
```
```
In kernel/bpf/cpumap.c (ffff800010288144)
Location: arch/arm64/include/asm/preempt.h:44
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In kernel/bpf/xskmap.c (ffff800010289618)
Location: arch/arm64/include/asm/preempt.h:44
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
Location: arch/arm64/include/asm/preempt.h:44
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In kernel/bpf/reuseport_array.c (ffff800010290808)
Location: arch/arm64/include/asm/preempt.h:44
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
Location: arch/arm64/include/asm/preempt.h:44
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
Location: arch/arm64/include/asm/preempt.h:44
Inline: True
Inline callers:
  - mm/page-writeback.c:bdi_set_max_ratio
  - mm/page-writeback.c:bdi_set_min_ratio
```
```
In mm/backing-dev.c (ffff8000102debf4)
Location: arch/arm64/include/asm/preempt.h:44
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:bdi_register_va
  - mm/backing-dev.c:bdi_get_by_id
  - mm/backing-dev.c:wb_wakeup_delayed
```
```
In fs/fs-writeback.c (ffff8000103cb148)
Location: arch/arm64/include/asm/preempt.h:44
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_queue_work
  - fs/fs-writeback.c:wb_wakeup
```
```
In ipc/util.c (ffff80001051d480)
Location: arch/arm64/include/asm/preempt.h:44
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/selinux/netif.c (ffff800010557e3c)
Location: arch/arm64/include/asm/preempt.h:44
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_netdev_notifier_handler
  - security/selinux/netif.c:sel_netif_flush
  - security/selinux/netif.c:sel_netif_sid
```
```
In security/selinux/netnode.c (ffff8000105586a8)
Location: arch/arm64/include/asm/preempt.h:44
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_flush
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (ffff800010558ab8)
Location: arch/arm64/include/asm/preempt.h:44
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_flush
  - security/selinux/netport.c:sel_netport_sid
```
```
In security/smack/smack_lsm.c (ffff80001056f438)
Location: arch/arm64/include/asm/preempt.h:44
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_netlabel
```
```
In security/apparmor/policy_unpack.c (ffff80001059897c)
Location: arch/arm64/include/asm/preempt.h:44
Inline: True
```
```
In block/genhd.c (ffff8000105fa3c4)
Location: arch/arm64/include/asm/preempt.h:44
Inline: True
Inline callers:
  - block/genhd.c:get_gendisk
```
```
In block/blk-cgroup.c (ffff80001060e700)
Location: arch/arm64/include/asm/preempt.h:44
Inline: True
Inline callers:
  - block/blk-cgroup.c:__blkcg_punt_bio_submit
  - block/blk-cgroup.c:blkg_async_bio_workfn
```
```
In lib/rhashtable.c (ffff800010636b48)
Location: arch/arm64/include/asm/preempt.h:44
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In drivers/irqchip/irq-gic-v3.c (ffff800010081abc)
Location: arch/arm64/include/asm/preempt.h:44
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3.c:gic_handle_irq
```
```
In drivers/dma/dmaengine.c (ffff8000107fcfb0)
Location: arch/arm64/include/asm/preempt.h:44
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_run_dependencies
```
```
In drivers/dma/mv_xor.c (ffff800010806cc0)
Location: arch/arm64/include/asm/preempt.h:44
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
Location: arch/arm64/include/asm/preempt.h:44
Inline: True
Inline callers:
  - drivers/dma/mv_xor_v2.c:mv_xor_v2_tasklet
  - drivers/dma/mv_xor_v2.c:mv_xor_v2_issue_pending
  - drivers/dma/mv_xor_v2.c:mv_xor_v2_prep_sw_desc
  - drivers/dma/mv_xor_v2.c:mv_xor_v2_tx_submit
```
```
In drivers/connector/cn_queue.c (ffff8000108dd6a4)
Location: arch/arm64/include/asm/preempt.h:44
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_free_dev
  - drivers/connector/cn_queue.c:cn_queue_del_callback
  - drivers/connector/cn_queue.c:cn_queue_add_callback
```
```
In drivers/connector/connector.c (ffff8000108ddc24)
Location: arch/arm64/include/asm/preempt.h:44
Inline: True
Inline callers:
  - drivers/connector/connector.c:cn_proc_show
  - drivers/connector/connector.c:cn_netlink_send_mult
```
```
In drivers/net/tun.c (ffff8000109e13a4)
Location: arch/arm64/include/asm/preempt.h:44
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
Location: arch/arm64/include/asm/preempt.h:44
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
Location: arch/arm64/include/asm/preempt.h:44
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
Location: arch/arm64/include/asm/preempt.h:44
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:netback_changed
  - drivers/net/xen-netfront.c:xennet_open
```
```
In net/core/sock.c (ffff800010bada38)
Location: arch/arm64/include/asm/preempt.h:44
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
Location: arch/arm64/include/asm/preempt.h:44
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/core/skbuff.c (ffff800010bb50d8)
Location: arch/arm64/include/asm/preempt.h:44
Inline: True
Inline callers:
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:netdev_alloc_frag
```
```
In net/core/datagram.c (ffff800010bbc90c)
Location: arch/arm64/include/asm/preempt.h:44
Inline: True
Inline callers:
  - net/core/datagram.c:__sk_queue_drop_skb
```
```
In net/core/gen_stats.c (ffff800010bbf2f8)
Location: arch/arm64/include/asm/preempt.h:44
Inline: True
Inline callers:
  - net/core/gen_stats.c:gnet_stats_start_copy_compat
```
```
In net/core/gen_estimator.c (ffff800010bbf8dc)
Location: arch/arm64/include/asm/preempt.h:44
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/net_namespace.c (ffff800010bc1960)
Location: arch/arm64/include/asm/preempt.h:44
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
Location: arch/arm64/include/asm/preempt.h:44
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
Location: arch/arm64/include/asm/preempt.h:44
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
Location: arch/arm64/include/asm/preempt.h:44
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
Location: arch/arm64/include/asm/preempt.h:44
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_fdb_dump
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:set_operstate
```
```
In net/core/link_watch.c (ffff800010bf3764)
Location: arch/arm64/include/asm/preempt.h:44
Inline: True
Inline callers:
  - net/core/link_watch.c:rfc2863_policy
```
```
In net/core/sock_reuseport.c (ffff800010c0529c)
Location: arch/arm64/include/asm/preempt.h:44
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_attach_prog
  - net/core/sock_reuseport.c:reuseport_detach_sock
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_alloc
```
```
In net/core/xdp.c (ffff800010c06798)
Location: arch/arm64/include/asm/preempt.h:44
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffff800010c08620)
Location: arch/arm64/include/asm/preempt.h:44
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/core/page_pool.c (ffff800010c0cabc)
Location: arch/arm64/include/asm/preempt.h:44
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
```
```
In net/core/net-procfs.c (ffff800010c0dfe0)
Location: arch/arm64/include/asm/preempt.h:44
Inline: True
```
```
In net/core/skmsg.c (ffff800010c0f6f8)
Location: arch/arm64/include/asm/preempt.h:44
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_data_ready
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_link_pop
```
```
In net/core/netpoll.c (ffff800010c11898)
Location: arch/arm64/include/asm/preempt.h:44
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
```
```
In net/core/sock_map.c (ffff800010c21c98)
Location: arch/arm64/include/asm/preempt.h:44
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
Location: arch/arm64/include/asm/preempt.h:44
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_port_type_set
  - net/core/devlink.c:devlink_nl_port_fill
```
```
In net/core/bpf_sk_storage.c (ffff800010c32184)
Location: arch/arm64/include/asm/preempt.h:44
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
Location: arch/arm64/include/asm/preempt.h:44
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_graft_qdisc
```
```
In net/sched/sch_mq.c (ffff800010c3b0e4)
Location: arch/arm64/include/asm/preempt.h:44
Inline: True
Inline callers:
  - net/sched/sch_mq.c:mq_dump
```
```
In net/sched/sch_api.c (ffff800010c3d094)
Location: arch/arm64/include/asm/preempt.h:44
Inline: True
Inline callers:
  - net/sched/sch_api.c:tcf_node_bind
  - net/sched/sch_api.c:qdisc_class_hash_grow
```
```
In net/netlink/af_netlink.c (ffff800010c4f038)
Location: arch/arm64/include/asm/preempt.h:44
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
Location: arch/arm64/include/asm/preempt.h:44
Inline: True
Inline callers:
  - net/netfilter/nf_log.c:nf_log_buf_open
```
```
In net/netfilter/nf_queue.c (ffff800010c560d4)
Location: arch/arm64/include/asm/preempt.h:44
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_reinject
```
```
In net/ipv4/route.c (ffff800010c5a8c8)
Location: arch/arm64/include/asm/preempt.h:44
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
Location: arch/arm64/include/asm/preempt.h:44
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/ip_output.c (ffff800010c6359c)
Location: arch/arm64/include/asm/preempt.h:44
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_hashtables.c (ffff800010c6b30c)
Location: arch/arm64/include/asm/preempt.h:44
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffff800010c6bfb4)
Location: arch/arm64/include/asm/preempt.h:44
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/inet_connection_sock.c (ffff800010c6da90)
Location: arch/arm64/include/asm/preempt.h:44
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
Location: arch/arm64/include/asm/preempt.h:44
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (ffff800010c80f44)
Location: arch/arm64/include/asm/preempt.h:44
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8c51c)
Location: arch/arm64/include/asm/preempt.h:44
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/tcp_minisocks.c (ffff800010c901c8)
Location: arch/arm64/include/asm/preempt.h:44
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/tcp_metrics.c (ffff800010c925d4)
Location: arch/arm64/include/asm/preempt.h:44
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_del
  - net/ipv4/tcp_metrics.c:tcp_metrics_flush_all
  - net/ipv4/tcp_metrics.c:tcp_fastopen_cache_set
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv4/raw.c (ffff800010c97310)
Location: arch/arm64/include/asm/preempt.h:44
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_ioctl
  - net/ipv4/raw.c:raw_unhash_sk
  - net/ipv4/raw.c:raw_hash_sk
```
```
In net/ipv4/udp.c (ffff800010c9bad4)
Location: arch/arm64/include/asm/preempt.h:44
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
Location: arch/arm64/include/asm/preempt.h:44
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_req_delete
```
```
In net/ipv4/icmp.c (ffff800010ca4aa0)
Location: arch/arm64/include/asm/preempt.h:44
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/af_inet.c (ffff800010cabc24)
Location: arch/arm64/include/asm/preempt.h:44
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_register_protosw
  - net/ipv4/af_inet.c:inet_accept
```
```
In net/ipv4/igmp.c (ffff800010cb0388)
Location: arch/arm64/include/asm/preempt.h:44
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
Location: arch/arm64/include/asm/preempt.h:44
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffff800010cb9d14)
Location: arch/arm64/include/asm/preempt.h:44
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_release_info
```
```
In net/ipv4/inet_fragment.c (ffff800010cbf46c)
Location: arch/arm64/include/asm/preempt.h:44
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/inet_fragment.c:inet_frags_free_cb
```
```
In net/ipv4/ping.c (ffff800010cc0b40)
Location: arch/arm64/include/asm/preempt.h:44
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_seq_start
  - net/ipv4/ping.c:ping_lookup
  - net/ipv4/ping.c:ping_unhash
  - net/ipv4/ping.c:ping_get_port
```
```
In net/ipv4/nexthop.c (ffff800010cc4edc)
Location: arch/arm64/include/asm/preempt.h:44
Inline: True
```
```
In net/ipv4/sysctl_net_ipv4.c (ffff800010cc745c)
Location: arch/arm64/include/asm/preempt.h:44
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_local_port_range
```
```
In net/ipv4/ipmr.c (ffff800010ccbf2c)
Location: arch/arm64/include/asm/preempt.h:44
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
Location: arch/arm64/include/asm/preempt.h:44
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_table_dump
  - net/ipv4/ipmr_base.c:mr_mfc_seq_next
```
```
In net/ipv4/tcp_bpf.c (ffff800010cd477c)
Location: arch/arm64/include/asm/preempt.h:44
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_init
```
```
In net/ipv4/cipso_ipv4.c (ffff800010cd5414)
Location: arch/arm64/include/asm/preempt.h:44
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_invalidate
```
```
In net/xfrm/xfrm_policy.c (ffff800010cdd5a0)
Location: arch/arm64/include/asm/preempt.h:44
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
Location: arch/arm64/include/asm/preempt.h:44
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
Location: arch/arm64/include/asm/preempt.h:44
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input_unregister_afinfo
  - net/xfrm/xfrm_input.c:xfrm_input_register_afinfo
```
```
In net/xfrm/xfrm_output.c (ffff800010cebfd4)
Location: arch/arm64/include/asm/preempt.h:44
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/unix/af_unix.c (ffff800010cf1594)
Location: arch/arm64/include/asm/preempt.h:44
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_accept
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/ipv6/af_inet6.c (ffff800010cf6444)
Location: arch/arm64/include/asm/preempt.h:44
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_register_protosw
```
```
In net/ipv6/anycast.c (ffff800010cf6ef0)
Location: arch/arm64/include/asm/preempt.h:44
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
Location: arch/arm64/include/asm/preempt.h:44
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/addrconf.c (ffff800010d0ab18)
Location: arch/arm64/include/asm/preempt.h:44
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
Location: arch/arm64/include/asm/preempt.h:44
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
Location: arch/arm64/include/asm/preempt.h:44
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
Location: arch/arm64/include/asm/preempt.h:44
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ip6_ra_control
```
```
In net/ipv6/ndisc.c (ffff800010d230d0)
Location: arch/arm64/include/asm/preempt.h:44
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_unsol_na
```
```
In net/ipv6/raw.c (ffff800010d292d0)
Location: arch/arm64/include/asm/preempt.h:44
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_ioctl
```
```
In net/ipv6/icmp.c (ffff800010d2c5dc)
Location: arch/arm64/include/asm/preempt.h:44
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffff800010d30874)
Location: arch/arm64/include/asm/preempt.h:44
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
Location: arch/arm64/include/asm/preempt.h:44
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
Location: arch/arm64/include/asm/preempt.h:44
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
Location: arch/arm64/include/asm/preempt.h:44
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
  - net/ipv6/calipso.c:calipso_cache_invalidate
```
```
In net/ipv6/seg6_hmac.c (ffff800010d51e70)
Location: arch/arm64/include/asm/preempt.h:44
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
```
```
In net/ipv6/inet6_hashtables.c (ffff800010d553a4)
Location: arch/arm64/include/asm/preempt.h:44
Inline: True
```
```
In net/packet/af_packet.c (ffff800010d5bd38)
Location: arch/arm64/include/asm/preempt.h:44
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
Location: arch/arm64/include/asm/preempt.h:44
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
Location: arch/arm64/include/asm/preempt.h:44
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_deferred_process
```
```
In net/xdp/xsk.c (ffff800010d7e728)
Location: arch/arm64/include/asm/preempt.h:44
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
Location: arch/arm64/include/asm/preempt.h:44
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
In arch/arm/kernel/traps.c (c030223c)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - arch/arm/kernel/traps.c:handle_fiq_as_nmi
```
```
In kernel/softirq.c (c035be34)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - kernel/softirq.c:irq_enter
  - kernel/softirq.c:irq_enter
  - kernel/softirq.c:__do_softirq
```
```
In kernel/locking/spinlock.c (c0e9f248)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_lock_bh
  - kernel/locking/spinlock.c:_raw_read_lock_bh
  - kernel/locking/spinlock.c:_raw_spin_trylock_bh
  - kernel/locking/spinlock.c:_raw_spin_lock_bh
```
```
In kernel/irq/manage.c (c03cb14c)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_forced_thread_fn
```
```
In kernel/rcu/update.c (c03d77f4)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/srcutree.c (c03d82ec)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
```
```
In kernel/rcu/tree.c (c03de0c0)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_cpu_kthread
```
```
In kernel/time/hrtimer.c (c03ec444)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
```
```
In kernel/stop_machine.c (c0428378)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
```
```
In kernel/bpf/cpumap.c (c04b840c)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In kernel/bpf/offload.c (c04b9878)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In kernel/padata.c (c04d7e00)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:invoke_padata_reorder
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_parallel_worker
```
```
In ipc/util.c (c06d9864)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/smack/smack_lsm.c (c0721490)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_netlabel
```
```
In security/apparmor/policy_unpack.c (c0749bb0)
Location: include/asm-generic/preempt.h:52
Inline: True
```
```
In lib/rhashtable.c (c07dc870)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In drivers/irqchip/irq-gic-v3.c (0)
Location: include/asm-generic/preempt.h:52
Inline: True
```
```
In drivers/net/tun.c (c0ac6cf0)
Location: include/asm-generic/preempt.h:52
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
Location: include/asm-generic/preempt.h:52
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
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
```
```
In net/core/skbuff.c (c0cd21b0)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:netdev_alloc_frag
```
```
In net/core/gen_estimator.c (c0cdb39c)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/dev.c (c0cee974)
Location: include/asm-generic/preempt.h:52
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
Location: include/asm-generic/preempt.h:52
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
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (c0d2170c)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/sched/sch_generic.c (c0d4c2ac)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
```
```
In net/netlink/af_netlink.c (c0d5f2ac)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/netfilter/nf_log.c (c0d65380)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - net/netfilter/nf_log.c:nf_log_buf_open
```
```
In net/netfilter/nf_queue.c (c0d65b48)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_reinject
```
```
In net/ipv4/route.c (c0d66bb4)
Location: include/asm-generic/preempt.h:52
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
Location: include/asm-generic/preempt.h:52
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
Location: include/asm-generic/preempt.h:52
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
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward_finish
```
```
In net/ipv4/ip_output.c (c0d75358)
Location: include/asm-generic/preempt.h:52
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
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (c0d7adb0)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/inet_connection_sock.c (c0d7bfe0)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_route_child_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_route_req
```
```
In net/ipv4/tcp.c (c0d83f88)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (c0d901a8)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
```
In net/ipv4/tcp_ipv4.c (c0d9be7c)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/tcp_minisocks.c (c0d9e3fc)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/datagram.c (c0da4838)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (c0da5ba8)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/udp.c (c0da93cc)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/icmp.c (c0db0be4)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/fib_frontend.c (c0dbf378)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
```
```
In net/ipv4/fib_semantics.c (c0dc567c)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/inet_fragment.c (c0dcade0)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ping.c (c0dcccd8)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
```
```
In net/ipv4/nexthop.c (c0dd09a4)
Location: include/asm-generic/preempt.h:52
Inline: True
```
```
In net/ipv4/ipmr.c (c0dd74b4)
Location: include/asm-generic/preempt.h:52
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
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/unix/af_unix.c (c0df79a8)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/ipv6/ip6_output.c (c0dfeae8)
Location: include/asm-generic/preempt.h:52
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
Location: include/asm-generic/preempt.h:52
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
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (c0e12d00)
Location: include/asm-generic/preempt.h:52
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
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_start
```
```
In net/ipv6/ipv6_sockglue.c (c0e246d0)
Location: include/asm-generic/preempt.h:52
Inline: True
```
```
In net/ipv6/raw.c (c0e2dd58)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_send_hdrinc
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/ipv6/icmp.c (c0e304c8)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
```
```
In net/ipv6/mcast.c (c0e33b00)
Location: include/asm-generic/preempt.h:52
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
Location: include/asm-generic/preempt.h:52
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
Location: include/asm-generic/preempt.h:52
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
Location: include/asm-generic/preempt.h:52
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
Location: include/asm-generic/preempt.h:52
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
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
```
In net/ipv6/seg6_hmac.c (c0e52f18)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
```
```
In net/ipv6/inet6_hashtables.c (c0e55960)
Location: include/asm-generic/preempt.h:52
Inline: True
```
```
In net/xdp/xsk.c (c0e79134)
Location: include/asm-generic/preempt.h:52
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
In arch/powerpc/kernel/traps.c (c00000000002e5f0)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - arch/powerpc/kernel/traps.c:machine_check_exception
  - arch/powerpc/kernel/traps.c:system_reset_exception
```
```
In arch/powerpc/kernel/watchdog.c (c000000000037ad4)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - arch/powerpc/kernel/watchdog.c:soft_nmi_interrupt
```
```
In arch/powerpc/perf/core-book3s.c (c00000000012932c)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - arch/powerpc/perf/core-book3s.c:perf_event_interrupt
```
```
In kernel/softirq.c (c000000000146410)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - kernel/softirq.c:irq_enter
  - kernel/softirq.c:irq_enter
  - kernel/softirq.c:__do_softirq
```
```
In kernel/locking/spinlock.c (c000000000eea3c0)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_lock_bh
  - kernel/locking/spinlock.c:_raw_read_lock_bh
  - kernel/locking/spinlock.c:_raw_spin_trylock_bh
  - kernel/locking/spinlock.c:_raw_spin_lock_bh
```
```
In kernel/irq/manage.c (c0000000001d4588)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_forced_thread_fn
```
```
In kernel/rcu/update.c (c0000000001e31ec)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/srcutree.c (c0000000001e5970)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
```
```
In kernel/rcu/tree.c (c0000000001eb7d4)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_cpu_kthread
```
```
In kernel/time/hrtimer.c (c000000000203cf8)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
```
```
In kernel/stop_machine.c (c000000000258c80)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
```
```
In kernel/bpf/cpumap.c (c0000000003337d4)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In kernel/bpf/offload.c (c0000000003355b8)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In kernel/padata.c (c00000000035cd0c)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:invoke_padata_reorder
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_parallel_worker
```
```
In ipc/util.c (c0000000006665f0)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/smack/smack_lsm.c (c0000000006d340c)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_netlabel
```
```
In security/apparmor/policy_unpack.c (c00000000070f900)
Location: include/asm-generic/preempt.h:52
Inline: True
```
```
In lib/rhashtable.c (c0000000007dca38)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In drivers/net/tun.c (c000000000aa3060)
Location: include/asm-generic/preempt.h:52
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
Location: include/asm-generic/preempt.h:52
Inline: True
```
```
In net/core/skbuff.c (c000000000c8c080)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:netdev_alloc_frag
```
```
In net/core/gen_estimator.c (c000000000c98cb4)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/dev.c (c000000000cb29d4)
Location: include/asm-generic/preempt.h:52
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
Location: include/asm-generic/preempt.h:52
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
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_allocator_disconnect
```
```
In net/core/flow_offload.c (c000000000cf2c64)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/sched/sch_generic.c (c000000000d33084)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
```
```
In net/netlink/af_netlink.c (c000000000d4d888)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/netfilter/nf_log.c (c000000000d557f0)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - net/netfilter/nf_log.c:nf_log_buf_open
```
```
In net/netfilter/nf_queue.c (c000000000d56968)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_reinject
```
```
In net/ipv4/route.c (c000000000d5b2f0)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (c000000000d668b0)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_hashtables.c (c000000000d6e89c)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (c000000000d715bc)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/inet_connection_sock.c (c000000000d72ec4)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/tcp.c (c000000000d7d0b4)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (c000000000d8bdec)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
```
In net/ipv4/tcp_ipv4.c (c000000000d9aa4c)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/tcp_minisocks.c (c000000000d9e1b8)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/icmp.c (c000000000db7e1c)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/fib_frontend.c (c000000000dca94c)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_lookup
```
```
In net/ipv4/fib_semantics.c (c000000000dd2e48)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/inet_fragment.c (c000000000dda0e0)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/nexthop.c (c000000000de1250)
Location: include/asm-generic/preempt.h:52
Inline: True
```
```
In net/ipv4/ipmr.c (c000000000deb428)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (c000000000dfcd1c)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/unix/af_unix.c (c000000000e148a4)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/ipv6/ip6_output.c (c000000000e1f2ac)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/addrconf.c (c000000000e2b23c)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (c000000000e4155c)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ip6_fib.c (c000000000e46ef8)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_start
```
```
In net/ipv6/ipv6_sockglue.c (c000000000e4dcfc)
Location: include/asm-generic/preempt.h:52
Inline: True
```
```
In net/ipv6/icmp.c (c000000000e5deb4)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ip6_flowlabel.c (c000000000e72cb4)
Location: include/asm-generic/preempt.h:52
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
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (c000000000e8aa3c)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
```
```
In net/ipv6/inet6_hashtables.c (c000000000e8e1a8)
Location: include/asm-generic/preempt.h:52
Inline: True
```
```
In net/xdp/xsk.c (c000000000ebe74c)
Location: include/asm-generic/preempt.h:52
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
In kernel/softirq.c (ffffffe0000c703c)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - kernel/softirq.c:irq_enter
  - kernel/softirq.c:irq_enter
  - kernel/softirq.c:__do_softirq
```
```
In kernel/locking/spinlock.c (ffffffe0008c96a0)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_lock_bh
  - kernel/locking/spinlock.c:_raw_read_lock_bh
  - kernel/locking/spinlock.c:_raw_spin_trylock_bh
  - kernel/locking/spinlock.c:_raw_spin_lock_bh
```
```
In kernel/rcu/update.c (ffffffe00011e286)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/srcutree.c (ffffffe00011fc2a)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
```
```
In kernel/rcu/tree.c (ffffffe000122ffe)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_cpu_kthread
```
```
In kernel/stop_machine.c (ffffffe00015d3f6)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
```
```
In kernel/bpf/cpumap.c (ffffffe0001bce16)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In kernel/bpf/offload.c (ffffffe0001be35a)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In kernel/padata.c (ffffffe0001d2e46)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:invoke_padata_reorder
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_parallel_worker
```
```
In ipc/util.c (ffffffe000384d74)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/smack/smack_lsm.c (ffffffe0003c25b0)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_netlabel
```
```
In security/apparmor/policy_unpack.c (ffffffe0003e52f8)
Location: include/asm-generic/preempt.h:52
Inline: True
```
```
In lib/rhashtable.c (ffffffe0004640f8)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In drivers/net/tun.c (ffffffe00062aefa)
Location: include/asm-generic/preempt.h:52
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
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
```
```
In net/core/skbuff.c (ffffffe0007451a4)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:netdev_alloc_frag
```
```
In net/core/gen_estimator.c (ffffffe00074d298)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/dev.c (ffffffe00075dc96)
Location: include/asm-generic/preempt.h:52
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
Location: include/asm-generic/preempt.h:52
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
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_allocator_disconnect
```
```
In net/core/flow_offload.c (ffffffe00078646c)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/sched/sch_generic.c (ffffffe0007ab25c)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
```
```
In net/netlink/af_netlink.c (ffffffe0007badd6)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/netfilter/nf_log.c (ffffffe0007bf85c)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - net/netfilter/nf_log.c:nf_log_buf_open
```
```
In net/netfilter/nf_queue.c (ffffffe0007c03d4)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_reinject
```
```
In net/ipv4/route.c (ffffffe0007c31f8)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffe0007cabda)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_hashtables.c (ffffffe0007cfcc6)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffe0007d1958)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/inet_connection_sock.c (ffffffe0007d2d96)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/tcp.c (ffffffe0007d8a92)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffe0007e2ea4)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
```
In net/ipv4/tcp_ipv4.c (ffffffe0007ed54c)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/tcp_minisocks.c (ffffffe0007ef690)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/icmp.c (ffffffe0007ffd88)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/fib_frontend.c (ffffffe00080b776)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_lookup
```
```
In net/ipv4/fib_semantics.c (ffffffe000810800)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/inet_fragment.c (ffffffe00081524a)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/nexthop.c (ffffffe00081a246)
Location: include/asm-generic/preempt.h:52
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffe000820904)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffe00082c0fe)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/unix/af_unix.c (ffffffe00083d270)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/ipv6/ip6_output.c (ffffffe000843cb2)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/addrconf.c (ffffffe00084b1fe)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffe00085a02c)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ip6_fib.c (ffffffe00085dc36)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_start
```
```
In net/ipv6/ipv6_sockglue.c (ffffffe000861b8a)
Location: include/asm-generic/preempt.h:52
Inline: True
```
```
In net/ipv6/icmp.c (ffffffe00086c84e)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ip6_flowlabel.c (ffffffe00087aa94)
Location: include/asm-generic/preempt.h:52
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
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffe00088a55e)
Location: include/asm-generic/preempt.h:52
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
```
```
In net/ipv6/inet6_hashtables.c (ffffffe00088cb76)
Location: include/asm-generic/preempt.h:52
Inline: True
```
```
In net/xdp/xsk.c (ffffffe0008ac140)
Location: include/asm-generic/preempt.h:52
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
In arch/x86/kernel/nmi.c (ffffffff8103663d)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103ed73)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:fpu__save
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103fc6d)
Location: arch/x86/include/asm/preempt.h:77
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
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/mm/pkeys.c (ffffffff8108d808)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:copy_init_pkru_to_fpregs
```
```
In kernel/softirq.c (ffffffff810a196b)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/softirq.c:irq_enter
  - kernel/softirq.c:irq_enter
  - kernel/softirq.c:__do_softirq
```
```
In kernel/locking/spinlock.c (ffffffff81a73aa5)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_lock_bh
  - kernel/locking/spinlock.c:_raw_read_lock_bh
  - kernel/locking/spinlock.c:_raw_spin_trylock_bh
  - kernel/locking/spinlock.c:_raw_spin_lock_bh
```
```
In kernel/irq/manage.c (ffffffff8110fd35)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_forced_thread_fn
```
```
In kernel/rcu/update.c (ffffffff8111c26f)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/srcutree.c (ffffffff8111db5e)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
```
```
In kernel/rcu/tree.c (ffffffff8112162f)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_cpu_kthread
```
```
In kernel/time/hrtimer.c (ffffffff8113138b)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
```
```
In kernel/stop_machine.c (ffffffff8116c288)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
```
```
In kernel/bpf/cpumap.c (ffffffff811f906f)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In kernel/bpf/offload.c (ffffffff811fa467)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In kernel/padata.c (ffffffff81215b22)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:invoke_padata_reorder
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_parallel_worker
```
```
In ipc/util.c (ffffffff8142f39e)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/smack/smack_lsm.c (ffffffff8147543f)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_netlabel
```
```
In security/apparmor/policy_unpack.c (ffffffff8149b220)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In lib/rhashtable.c (ffffffff81523a2b)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In drivers/net/tun.c (ffffffff8178ad4c)
Location: arch/x86/include/asm/preempt.h:77
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
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In net/core/skbuff.c (ffffffff818bad76)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:netdev_alloc_frag
```
```
In net/core/gen_estimator.c (ffffffff818c409c)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/dev.c (ffffffff818d5843)
Location: arch/x86/include/asm/preempt.h:77
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
Location: arch/x86/include/asm/preempt.h:77
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
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff81903e89)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/sched/sch_generic.c (ffffffff8192e58a)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
```
```
In net/netlink/af_netlink.c (ffffffff81940857)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/netfilter/nf_log.c (ffffffff81945b9c)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/netfilter/nf_log.c:nf_log_buf_open
```
```
In net/netfilter/nf_queue.c (ffffffff819466bc)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_reinject
```
```
In net/ipv4/route.c (ffffffff819497e6)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff819524ff)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_hashtables.c (ffffffff819588c5)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff8195a2b7)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8195baa2)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/tcp.c (ffffffff81962968)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff8196e353)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81978e7f)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8197c13a)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/icmp.c (ffffffff8198e58c)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/fib_frontend.c (ffffffff8199b775)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff819a1466)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/inet_fragment.c (ffffffff819a63c5)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/nexthop.c (ffffffff819ab579)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff819b211c)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff819c0c92)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/unix/af_unix.c (ffffffff819d02bb)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/ipv6/ip6_output.c (ffffffff819d6d79)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/addrconf.c (ffffffff819df6f5)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff819eff83)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ip6_fib.c (ffffffff819f40ca)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_start
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff819f9a3b)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff81a05d07)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81a1514f)
Location: arch/x86/include/asm/preempt.h:77
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
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a258eb)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a27e46)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In net/xdp/xsk.c (ffffffff81a4a431)
Location: arch/x86/include/asm/preempt.h:77
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
In arch/x86/kernel/nmi.c (ffffffff81025f89)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8102e573)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:fpu__save
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8102f46d)
Location: arch/x86/include/asm/preempt.h:77
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
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/mm/pkeys.c (ffffffff8107c338)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:copy_init_pkru_to_fpregs
```
```
In kernel/softirq.c (ffffffff8109032b)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/softirq.c:irq_enter
  - kernel/softirq.c:irq_enter
  - kernel/softirq.c:__do_softirq
```
```
In kernel/locking/spinlock.c (ffffffff81a2feb5)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_lock_bh
  - kernel/locking/spinlock.c:_raw_read_lock_bh
  - kernel/locking/spinlock.c:_raw_spin_trylock_bh
  - kernel/locking/spinlock.c:_raw_spin_lock_bh
```
```
In kernel/irq/manage.c (ffffffff81100a65)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_forced_thread_fn
```
```
In kernel/rcu/update.c (ffffffff8110d2ec)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/srcutree.c (ffffffff8110ebf2)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
```
```
In kernel/rcu/tree.c (ffffffff81112133)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_nocb_cb_kthread
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_do_batch
```
```
In kernel/time/hrtimer.c (ffffffff81123dfb)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
```
```
In kernel/stop_machine.c (ffffffff8115f488)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
```
```
In kernel/bpf/cpumap.c (ffffffff811ebdbf)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In kernel/bpf/offload.c (ffffffff811ed1b7)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In kernel/padata.c (ffffffff81208882)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:invoke_padata_reorder
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_parallel_worker
```
```
In ipc/util.c (ffffffff8141fe1e)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/smack/smack_lsm.c (ffffffff81465e5f)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_netlabel
```
```
In security/apparmor/policy_unpack.c (ffffffff8148bc40)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In lib/rhashtable.c (ffffffff81513d0b)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In drivers/net/tun.c (ffffffff8176a69c)
Location: arch/x86/include/asm/preempt.h:77
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
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In net/core/skbuff.c (ffffffff81874cc1)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:netdev_alloc_frag
```
```
In net/core/gen_estimator.c (ffffffff8187dfdc)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/dev.c (ffffffff8188f6b3)
Location: arch/x86/include/asm/preempt.h:77
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
Location: arch/x86/include/asm/preempt.h:77
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
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff818bdcb9)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/sched/sch_generic.c (ffffffff818e808a)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
```
```
In net/netlink/af_netlink.c (ffffffff818fa347)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/netfilter/nf_log.c (ffffffff818ff68c)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/netfilter/nf_log.c:nf_log_buf_open
```
```
In net/netfilter/nf_queue.c (ffffffff819001ac)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_reinject
```
```
In net/ipv4/route.c (ffffffff819032d6)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff8190bfef)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_hashtables.c (ffffffff819123b5)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81913da7)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81915592)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/tcp.c (ffffffff8191c458)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff81927e43)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8193293f)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81935bfa)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/icmp.c (ffffffff8194804c)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/fib_frontend.c (ffffffff81955235)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff8195af26)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/inet_fragment.c (ffffffff8195fe85)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/nexthop.c (ffffffff81965039)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff8196e74c)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197da82)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/unix/af_unix.c (ffffffff8198d07b)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/ipv6/ip6_output.c (ffffffff81993b39)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/addrconf.c (ffffffff8199c4b5)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff819acd43)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ip6_fib.c (ffffffff819b0e8a)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_start
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff819b67fb)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff819c2ac7)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff819d1f0f)
Location: arch/x86/include/asm/preempt.h:77
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
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff819e26ab)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
```
```
In net/ipv6/inet6_hashtables.c (ffffffff819e4c06)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In net/xdp/xsk.c (ffffffff81a07021)
Location: arch/x86/include/asm/preempt.h:77
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
In arch/x86/kernel/nmi.c (ffffffff8103649d)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103ebb3)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:fpu__save
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103faad)
Location: arch/x86/include/asm/preempt.h:77
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
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/mm/pkeys.c (ffffffff8108d7b8)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:copy_init_pkru_to_fpregs
```
```
In kernel/softirq.c (ffffffff810a191b)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/softirq.c:irq_enter
  - kernel/softirq.c:irq_enter
  - kernel/softirq.c:__do_softirq
```
```
In kernel/locking/spinlock.c (ffffffff81adfeb5)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_lock_bh
  - kernel/locking/spinlock.c:_raw_read_lock_bh
  - kernel/locking/spinlock.c:_raw_spin_trylock_bh
  - kernel/locking/spinlock.c:_raw_spin_lock_bh
```
```
In kernel/irq/manage.c (ffffffff8110dc25)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_forced_thread_fn
```
```
In kernel/rcu/update.c (ffffffff8111a15f)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/srcutree.c (ffffffff8111ba4e)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
```
```
In kernel/rcu/tree.c (ffffffff8111f51f)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_cpu_kthread
```
```
In kernel/time/hrtimer.c (ffffffff8112f0ab)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
```
```
In kernel/stop_machine.c (ffffffff8116a058)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
```
```
In kernel/bpf/cpumap.c (ffffffff811f6e3f)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In kernel/bpf/offload.c (ffffffff811f8237)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In kernel/padata.c (ffffffff812138c2)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:invoke_padata_reorder
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_parallel_worker
```
```
In ipc/util.c (ffffffff8142b53e)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/smack/smack_lsm.c (ffffffff814714df)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_netlabel
```
```
In security/apparmor/policy_unpack.c (ffffffff814972c0)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In lib/rhashtable.c (ffffffff8151fabb)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In drivers/net/tun.c (ffffffff817bb0ec)
Location: arch/x86/include/asm/preempt.h:77
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
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In net/core/skbuff.c (ffffffff8190bd76)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:netdev_alloc_frag
```
```
In net/core/gen_estimator.c (ffffffff8191509c)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/dev.c (ffffffff81926873)
Location: arch/x86/include/asm/preempt.h:77
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
Location: arch/x86/include/asm/preempt.h:77
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
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff81954eb9)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/sched/sch_generic.c (ffffffff8197f71a)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
```
```
In net/netlink/af_netlink.c (ffffffff819919e7)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/netfilter/nf_log.c (ffffffff81996d2c)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/netfilter/nf_log.c:nf_log_buf_open
```
```
In net/netfilter/nf_queue.c (ffffffff8199784c)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_reinject
```
```
In net/netfilter/nfnetlink_log.c (ffffffff8199b205)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/netfilter/nfnetlink_log.c:seq_start
  - net/netfilter/nfnetlink_log.c:instance_lookup_get
```
```
In net/netfilter/nf_conntrack_core.c (ffffffff819a06ca)
Location: arch/x86/include/asm/preempt.h:77
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
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_ecache.c:ecache_work
```
```
In net/netfilter/nf_conntrack_netlink.c (ffffffff819b083a)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_dump_table
```
```
In net/ipv4/route.c (ffffffff819b3fb6)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff819bcccf)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_hashtables.c (ffffffff819c3095)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff819c4a87)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819c6272)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/tcp.c (ffffffff819cd138)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff819d8b23)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819e364f)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819e690a)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/icmp.c (ffffffff819f8e2c)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/fib_frontend.c (ffffffff81a06015)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff81a0bd06)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/inet_fragment.c (ffffffff81a10c65)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/nexthop.c (ffffffff81a15e19)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81a1c9bc)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/netfilter/nf_defrag_ipv4.c (ffffffff81a20c6e)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a2b712)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/unix/af_unix.c (ffffffff81a3ad3b)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/ipv6/ip6_output.c (ffffffff81a417f9)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/addrconf.c (ffffffff81a4a175)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff81a5aa03)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ip6_fib.c (ffffffff81a5eb4a)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_start
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81a644bb)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff81a70787)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81a7fbcf)
Location: arch/x86/include/asm/preempt.h:77
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
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a9036b)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a939f6)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In net/xdp/xsk.c (ffffffff81ab62e1)
Location: arch/x86/include/asm/preempt.h:77
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
In init/main.c (ffffffff81002935)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - init/main.c:do_one_initcall
  - init/main.c:do_one_initcall
  - init/main.c:start_kernel
```
```
In arch/x86/entry/common.c (ffffffff81004339)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/entry/common.c:syscall_slow_exit_work
  - arch/x86/entry/common.c:syscall_trace_enter
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81005481)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
```
```
In arch/x86/events/amd/ibs.c (ffffffff828a1334)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:amd_ibs_init
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
  - arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup
```
```
In arch/x86/events/intel/ds.c (ffffffff8100fa35)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:ds_clear_cea
  - arch/x86/events/intel/ds.c:ds_update_cea
```
```
In arch/x86/events/intel/p4.c (ffffffff81013dc5)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_hw_config
```
```
In arch/x86/xen/time.c (ffffffff8101e359)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_read_wallclock
  - arch/x86/xen/time.c:xen_clocksource_read
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff81023097)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_cr0
  - arch/x86/xen/enlighten_pv.c:xen_write_cr0
  - arch/x86/xen/enlighten_pv.c:xen_write_cr0
  - arch/x86/xen/enlighten_pv.c:xen_load_sp0
  - arch/x86/xen/enlighten_pv.c:xen_load_sp0
  - arch/x86/xen/enlighten_pv.c:xen_load_sp0
  - arch/x86/xen/enlighten_pv.c:xen_write_idt_entry
  - arch/x86/xen/enlighten_pv.c:xen_write_idt_entry
  - arch/x86/xen/enlighten_pv.c:xen_load_tls
  - arch/x86/xen/enlighten_pv.c:xen_load_tls
  - arch/x86/xen/enlighten_pv.c:load_TLS_descriptor
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
  - arch/x86/xen/enlighten_pv.c:xen_set_ldt
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810243d5)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_all
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_all
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_all
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_all
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_remap_exchanged_ptes
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_zap_pfn_range
  - arch/x86/xen/mmu_pv.c:xen_leave_lazy_mmu
  - arch/x86/xen/mmu_pv.c:xen_release_pud
  - arch/x86/xen/mmu_pv.c:xen_release_pud
  - arch/x86/xen/mmu_pv.c:xen_release_pud
  - arch/x86/xen/mmu_pv.c:xen_release_pud
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_release_pmd
  - arch/x86/xen/mmu_pv.c:xen_release_pmd
  - arch/x86/xen/mmu_pv.c:xen_release_pmd
  - arch/x86/xen/mmu_pv.c:xen_release_pmd
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_others
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb_one_user
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
  - arch/x86/xen/mmu_pv.c:xen_flush_tlb
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
  - arch/x86/xen/mmu_pv.c:xen_set_p4d_hyper
  - arch/x86/xen/mmu_pv.c:xen_set_pud
  - arch/x86/xen/mmu_pv.c:xen_set_pud_hyper
  - arch/x86/xen/mmu_pv.c:xen_set_pud_hyper
  - arch/x86/xen/mmu_pv.c:xen_set_pud_hyper
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_start
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pmd
  - arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper
  - arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper
  - arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper
  - arch/x86/xen/mmu_pv.c:xen_extend_mmuext_op
```
```
In arch/x86/xen/irq.c (ffffffff810293d0)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/xen/irq.c:xen_irq_enable
  - arch/x86/xen/irq.c:xen_irq_disable
  - arch/x86/xen/irq.c:xen_restore_fl
```
```
In arch/x86/xen/multicalls.c (ffffffff81029a2e)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/xen/multicalls.c:xen_mc_callback
  - arch/x86/xen/multicalls.c:xen_mc_callback
  - arch/x86/xen/multicalls.c:xen_mc_extend_args
  - arch/x86/xen/multicalls.c:xen_mc_extend_args
  - arch/x86/xen/multicalls.c:xen_mc_extend_args
  - arch/x86/xen/multicalls.c:__xen_mc_entry
  - arch/x86/xen/multicalls.c:__xen_mc_entry
  - arch/x86/xen/multicalls.c:xen_mc_flush
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102d86a)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_bringup
```
```
In arch/x86/hyperv/mmu.c (ffffffff8102f5c7)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/hyperv/nested.c (ffffffff8102fee0)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range
  - arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81030383)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
```
```
In arch/x86/kernel/process_64.c (ffffffff8103114f)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/signal.c (ffffffff81031e79)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
```
```
In arch/x86/kernel/traps.c (ffffffff810329df)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_debug
  - arch/x86/kernel/traps.c:do_bounds
  - arch/x86/kernel/traps.c:do_double_fault
  - arch/x86/kernel/traps.c:ist_end_non_atomic
```
```
In arch/x86/kernel/irq.c (ffffffff81c0200d)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
```
```
In arch/x86/kernel/ioport.c (ffffffff810362f6)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In arch/x86/kernel/nmi.c (ffffffff8103711a)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:nmi_handle
```
```
In arch/x86/kernel/irq_work.c (ffffffff81c02111)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:smp_irq_work_interrupt
  - arch/x86/kernel/irq_work.c:smp_irq_work_interrupt
```
```
In arch/x86/kernel/hw_breakpoint.c (ffffffff8103c886)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_exceptions_notify
```
```
In arch/x86/kernel/tsc.c (ffffffff8103d640)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:native_sched_clock_from_tsc
  - arch/x86/kernel/tsc.c:native_sched_clock
  - arch/x86/kernel/tsc.c:__set_cyc2ns_scale
```
```
In arch/x86/kernel/process.c (ffffffff8103f0d0)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:do_arch_prctl_common
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:default_idle
  - arch/x86/kernel/process.c:default_idle
  - arch/x86/kernel/process.c:speculation_ctrl_update_current
  - arch/x86/kernel/process.c:enable_cpuid
  - arch/x86/kernel/process.c:set_tsc_mode
  - arch/x86/kernel/process.c:disable_TSC
  - arch/x86/kernel/process.c:exit_thread
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103f773)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpregs_mark_activate
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/core.c:fpu__drop
  - arch/x86/kernel/fpu/core.c:fpu__drop
  - arch/x86/kernel/fpu/core.c:fpu__drop
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:fpu__save
  - arch/x86/kernel/fpu/core.c:fpu__save
  - arch/x86/kernel/fpu/core.c:fpu__save
  - arch/x86/kernel/fpu/core.c:fpu__save
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81040f30)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81041909)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
```
```
In arch/x86/kernel/tls.c (ffffffff81044317)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:set_tls_desc
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104e7b5)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81c0221c)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:smp_deferred_error_interrupt
  - arch/x86/kernel/cpu/mce/amd.c:smp_deferred_error_interrupt
```
```
In arch/x86/kernel/cpu/mce/threshold.c (ffffffff81c0232c)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/threshold.c:smp_threshold_interrupt
  - arch/x86/kernel/cpu/mce/threshold.c:smp_threshold_interrupt
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81c0243c)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:smp_thermal_interrupt
  - arch/x86/kernel/cpu/mce/therm_throt.c:smp_thermal_interrupt
  - arch/x86/kernel/cpu/mce/therm_throt.c:therm_throt_device_show_package_power_limit_count
  - arch/x86/kernel/cpu/mce/therm_throt.c:therm_throt_device_show_package_throttle_count
  - arch/x86/kernel/cpu/mce/therm_throt.c:therm_throt_device_show_core_power_limit_count
  - arch/x86/kernel/cpu/mce/therm_throt.c:therm_throt_device_show_core_throttle_count
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff81056af5)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_get_mtrr
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105cc14)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:move_myself
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:update_closid_rmid
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105f847)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff8106049f)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:update_domains
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81062113)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_l3_residency
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_l2_residency
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn
```
```
In arch/x86/kernel/smp.c (ffffffff81c028b1)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_call_function_single_interrupt
  - arch/x86/kernel/smp.c:smp_call_function_single_interrupt
  - arch/x86/kernel/smp.c:smp_call_function_interrupt
  - arch/x86/kernel/smp.c:smp_call_function_interrupt
  - arch/x86/kernel/smp.c:smp_reschedule_interrupt
  - arch/x86/kernel/smp.c:smp_reschedule_interrupt
```
```
In arch/x86/kernel/smpboot.c (ffffffff828b723c)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:do_boot_cpu
  - arch/x86/kernel/smpboot.c:start_secondary
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81c02ce4)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_error_interrupt
  - arch/x86/kernel/apic/apic.c:smp_error_interrupt
  - arch/x86/kernel/apic/apic.c:smp_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:smp_spurious_interrupt
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
```
```
In arch/x86/kernel/apic/vector.c (ffffffff828b9f2a)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/vector.c:free_moved_vector
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
  - arch/x86/kernel/apic/vector.c:x86_vector_deactivate
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
  - arch/x86/kernel/apic/vector.c:assign_managed_vector
  - arch/x86/kernel/apic/vector.c:assign_vector_locked
  - arch/x86/kernel/apic/vector.c:reserve_irq_vector_locked
  - arch/x86/kernel/apic/vector.c:apic_update_vector
  - arch/x86/kernel/apic/vector.c:apic_update_irq_cfg
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff8106e419)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_one
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff81073a38)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:trampoline_handler
```
```
In arch/x86/kernel/kprobes/opt.c (ffffffff81074bdb)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In arch/x86/kernel/kvmclock.c (ffffffff81079330)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/kvmclock.c:kvm_clock_read
  - arch/x86/kernel/kvmclock.c:kvm_get_wallclock
```
```
In arch/x86/kernel/paravirt.c (ffffffff81079e55)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:paravirt_flush_lazy_mmu
```
```
In arch/x86/mm/fault.c (ffffffff810821bd)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_page_fault
  - arch/x86/mm/fault.c:do_page_fault
```
```
In arch/x86/mm/pageattr.c (ffffffff81086862)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__kernel_map_pages
```
```
In arch/x86/mm/tlb.c (ffffffff8108a315)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:arch_tlbbatch_flush
  - arch/x86/mm/tlb.c:flush_tlb_kernel_range
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
  - arch/x86/mm/tlb.c:native_flush_tlb_others
  - arch/x86/mm/tlb.c:native_flush_tlb_others
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/mm/kmmio.c (ffffffff8108c937)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:kmmio_die_notifier
  - arch/x86/mm/kmmio.c:kmmio_handler
  - arch/x86/mm/kmmio.c:kmmio_handler
```
```
In arch/x86/mm/mmio-mod.c (ffffffff8108d67f)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:pre
  - arch/x86/mm/mmio-mod.c:pre
  - arch/x86/mm/mmio-mod.c:pre
```
```
In arch/x86/mm/mpx.c (ffffffff8108ef30)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_unmap_tables
  - arch/x86/mm/mpx.c:zap_bt_entries_mapping
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
  - arch/x86/mm/mpx.c:mpx_fault_info
```
```
In arch/x86/mm/pkeys.c (ffffffff8108fb78)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:copy_init_pkru_to_fpregs
  - arch/x86/mm/pkeys.c:copy_init_pkru_to_fpregs
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81093978)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
```
```
In arch/x86/platform/uv/tlb_uv.c (ffffffff81096b57)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:tunables_write
```
```
In arch/x86/platform/uv/bios_uv.c (ffffffff810993f8)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/platform/uv/bios_uv.c:__uv_bios_call
```
```
In kernel/fork.c (ffffffff810a1a07)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/panic.c (ffffffff810a2d32)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/panic.c:panic
```
```
In kernel/cpu.c (ffffffff810a4f15)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
  - kernel/cpu.c:__cpuhp_state_add_instance
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:cpuhp_kick_ap_work
  - kernel/cpu.c:cpuhp_kick_ap_work
  - kernel/cpu.c:cpus_read_trylock
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
  - kernel/cpu.c:cpuhp_invoke_callback
```
```
In kernel/exit.c (ffffffff810a7306)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:delayed_put_task_struct
```
```
In kernel/softirq.c (ffffffff810a981b)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:takeover_tasklets
  - kernel/softirq.c:__tasklet_schedule_common
  - kernel/softirq.c:raise_softirq
  - kernel/softirq.c:irq_enter
  - kernel/softirq.c:irq_enter
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__do_softirq
```
```
In kernel/signal.c (ffffffff810b5631)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:exit_signals
  - kernel/signal.c:exit_signals
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:__send_signal
```
```
In kernel/workqueue.c (ffffffff810c1ab6)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_congested
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:pwq_activate_delayed_work
```
```
In kernel/kthread.c (ffffffff810cad88)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_stop
  - kernel/kthread.c:kthread_stop
```
```
In kernel/smpboot.c (ffffffff810d1041)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/smpboot.c:smpboot_thread_fn
```
```
In kernel/kmod.c (ffffffff810d1f47)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
```
```
In kernel/sched/core.c (ffffffff810df133)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/sched/core.c:migrate_task_to
  - kernel/sched/core.c:do_sched_yield
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:rt_mutex_setprio
  - kernel/sched/core.c:preempt_schedule_irq
  - kernel/sched/core.c:preempt_schedule_notrace
  - kernel/sched/core.c:preempt_schedule_common
  - kernel/sched/core.c:schedule_preempt_disabled
  - kernel/sched/core.c:schedule
  - kernel/sched/core.c:schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:kick_process
  - kernel/sched/core.c:wait_task_inactive
  - kernel/sched/core.c:migrate_swap
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:wake_up_nohz_cpu
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/clock.c (ffffffff810e0fb0)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/sched/clock.c:__sched_clock_work
```
```
In kernel/sched/idle.c (ffffffff810e200b)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/sched/idle.c:play_idle
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/sched/idle.c:cpu_idle_poll
```
```
In kernel/sched/fair.c (ffffffff810ea1b3)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_entity_cfs_rq
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:set_next_entity
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:attach_entity_load_avg
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:update_stats_enqueue_sleeper
  - kernel/sched/fair.c:update_stats_enqueue_sleeper
  - kernel/sched/fair.c:update_stats_enqueue_sleeper
  - kernel/sched/fair.c:update_curr
```
```
In kernel/sched/deadline.c (ffffffff810f6595)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_cpu_busy
  - kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:sched_dl_do_global
  - kernel/sched/deadline.c:sched_dl_global_validate
```
```
In kernel/sched/pelt.c (ffffffff810fba67)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/sched/pelt.c:update_dl_rq_load_avg
  - kernel/sched/pelt.c:update_rt_rq_load_avg
  - kernel/sched/pelt.c:__update_load_avg_cfs_rq
  - kernel/sched/pelt.c:__update_load_avg_se
  - kernel/sched/pelt.c:__update_load_avg_blocked_se
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff81101bdf)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_fast_switch
```
```
In kernel/sched/membarrier.c (ffffffff81102aa7)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:membarrier_private_expedited
  - kernel/sched/membarrier.c:membarrier_global_expedited
```
```
In kernel/locking/mutex.c (ffffffff81ae8c52)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In kernel/locking/rwsem.c (ffffffff8110570a)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
```
```
In kernel/locking/percpu-rwsem.c (ffffffff81105dea)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In kernel/locking/spinlock.c (ffffffff81aec5a5)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/locking/spinlock.c:_raw_write_trylock
  - kernel/locking/spinlock.c:_raw_read_trylock
  - kernel/locking/spinlock.c:_raw_write_lock_irqsave
  - kernel/locking/spinlock.c:_raw_read_lock_irqsave
  - kernel/locking/spinlock.c:_raw_write_lock_irq
  - kernel/locking/spinlock.c:_raw_read_lock_irq
  - kernel/locking/spinlock.c:_raw_write_lock_bh
  - kernel/locking/spinlock.c:_raw_read_lock_bh
  - kernel/locking/spinlock.c:_raw_write_lock
  - kernel/locking/spinlock.c:_raw_read_lock
  - kernel/locking/spinlock.c:_raw_spin_trylock_bh
  - kernel/locking/spinlock.c:_raw_spin_trylock
  - kernel/locking/spinlock.c:_raw_spin_lock_irqsave
  - kernel/locking/spinlock.c:_raw_spin_lock_irq
  - kernel/locking/spinlock.c:_raw_spin_lock_bh
  - kernel/locking/spinlock.c:_raw_spin_lock
```
```
In kernel/locking/rtmutex.c (ffffffff81106994)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:mark_wakeup_next_waiter
```
```
In kernel/power/qos.c (ffffffff81108930)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_update_request_timeout
  - kernel/power/qos.c:pm_qos_work_fn
  - kernel/power/qos.c:pm_qos_update_flags
  - kernel/power/qos.c:pm_qos_update_target
```
```
In kernel/power/process.c (ffffffff8110a071)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/power/process.c:thaw_processes
  - kernel/power/process.c:thaw_processes
```
```
In kernel/power/suspend.c (ffffffff8110af71)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
```
```
In kernel/power/hibernate.c (ffffffff8110bdb9)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/hibernate.c:hibernation_snapshot
```
```
In kernel/power/snapshot.c (ffffffff8110dc06)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/power/snapshot.c:clear_free_pages
```
```
In kernel/printk/printk.c (ffffffff81116805)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/printk/printk.c:defer_console_output
  - kernel/printk/printk.c:wake_up_klogd
  - kernel/printk/printk.c:console_init
  - kernel/printk/printk.c:console_init
  - kernel/printk/printk.c:console_init
  - kernel/printk/printk.c:vprintk_emit
```
```
In kernel/irq/handle.c (ffffffff8111811c)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/irq/handle.c:__handle_irq_event_percpu
  - kernel/irq/handle.c:__handle_irq_event_percpu
```
```
In kernel/irq/manage.c (ffffffff81118f15)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_forced_thread_fn
```
```
In kernel/irq/chip.c (ffffffff8111d57c)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi
  - kernel/irq/chip.c:handle_percpu_devid_fasteoi_nmi
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_percpu_devid_irq
  - kernel/irq/chip.c:handle_fasteoi_nmi
  - kernel/irq/chip.c:handle_fasteoi_nmi
```
```
In kernel/irq/matrix.c (ffffffff81125004)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_matrix_free
  - kernel/irq/matrix.c:irq_matrix_alloc
  - kernel/irq/matrix.c:irq_matrix_remove_reserved
  - kernel/irq/matrix.c:irq_matrix_reserve
  - kernel/irq/matrix.c:irq_matrix_assign
  - kernel/irq/matrix.c:irq_matrix_alloc_managed
  - kernel/irq/matrix.c:irq_matrix_remove_managed
  - kernel/irq/matrix.c:irq_matrix_reserve_managed
  - kernel/irq/matrix.c:irq_matrix_assign_system
  - kernel/irq/matrix.c:irq_matrix_offline
  - kernel/irq/matrix.c:irq_matrix_online
```
```
In kernel/rcu/update.c (ffffffff81125a15)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/rcu/update.c:exit_tasks_rcu_finish
  - kernel/rcu/update.c:exit_tasks_rcu_start
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/srcutree.c (ffffffff81125f9c)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
```
```
In kernel/rcu/tree.c (ffffffff8112af13)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_note_context_switch
  - kernel/rcu/tree.c:rcu_note_context_switch
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:rcu_report_dead
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
```
In kernel/livepatch/patch.c (ffffffff8112fa47)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_ftrace_handler
```
```
In kernel/livepatch/transition.c (ffffffff81130985)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_update_patch_state
```
```
In kernel/dma/swiotlb.c (ffffffff8113311b)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_map
```
```
In kernel/profile.c (ffffffff81133f88)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/profile.c:write_profile
  - kernel/profile.c:read_profile
```
```
In kernel/time/timer.c (ffffffff81139da2)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:schedule_timeout
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:call_timer_fn
  - kernel/time/timer.c:detach_if_pending
  - kernel/time/timer.c:enqueue_timer
```
```
In kernel/time/hrtimer.c (ffffffff8113baab)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:hrtimers_dead_cpu
  - kernel/time/hrtimer.c:hrtimer_init_sleeper
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:__hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_init
  - kernel/time/hrtimer.c:hrtimer_start_range_ns
  - kernel/time/hrtimer.c:enqueue_hrtimer
```
```
In kernel/time/alarmtimer.c (ffffffff81142a77)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_try_to_cancel
  - kernel/time/alarmtimer.c:alarm_start
  - kernel/time/alarmtimer.c:alarmtimer_suspend
  - kernel/time/alarmtimer.c:alarmtimer_fired
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8114641e)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In kernel/time/itimer.c (ffffffff8114861c)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/time/itimer.c:do_setitimer
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:it_real_fn
```
```
In kernel/time/tick-common.c (ffffffff8114a28f)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/time/tick-common.c:tick_unfreeze
  - kernel/time/tick-common.c:tick_freeze
```
```
In kernel/time/tick-sched.c (ffffffff8114c16a)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_idle_stop_tick
```
```
In kernel/smp.c (ffffffff81151bf5)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/smp.c:wake_up_all_idle_cpus
  - kernel/smp.c:on_each_cpu_cond_mask
  - kernel/smp.c:on_each_cpu_cond_mask
  - kernel/smp.c:on_each_cpu_mask
  - kernel/smp.c:on_each_cpu
  - kernel/smp.c:smp_call_function
  - kernel/smp.c:smp_call_function_any
  - kernel/smp.c:smp_call_function_single_async
  - kernel/smp.c:smp_call_function_single
```
```
In kernel/module.c (ffffffff8115a3fe)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/module.c:print_modules
  - kernel/module.c:is_module_text_address
  - kernel/module.c:is_module_address
  - kernel/module.c:search_module_extables
  - kernel/module.c:module_kallsyms_lookup_name
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_name
  - kernel/module.c:module_address_lookup
  - kernel/module.c:load_module
  - kernel/module.c:__symbol_get
  - kernel/module.c:free_module
  - kernel/module.c:try_module_get
  - kernel/module.c:try_module_get
  - kernel/module.c:__is_module_percpu_address
```
```
In kernel/kexec_core.c (ffffffff8115c78b)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/cgroup/cgroup.c (ffffffff8116a53f)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/cgroup/cgroup.c:css_tryget_online_from_dir
  - kernel/cgroup/cgroup.c:cgroup_rmdir
  - kernel/cgroup/cgroup.c:kill_css
  - kernel/cgroup/cgroup.c:css_killed_work_fn
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:init_and_link_css
  - kernel/cgroup/cgroup.c:css_release_work_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:cgroup_kn_lock_live
  - kernel/cgroup/cgroup.c:cgroup_kn_unlock
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:cgroup_update_populated
  - kernel/cgroup/cgroup.c:cgroup_get_live
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
  - kernel/cgroup/cgroup.c:cgroup_get_e_css
```
```
In kernel/cgroup/rstat.c (ffffffff8116acf5)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/cgroup/rstat.c:__cgroup_account_cputime_field
  - kernel/cgroup/rstat.c:__cgroup_account_cputime
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8116cbc2)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
  - kernel/cgroup/cgroup-v1.c:cgroup1_rename
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
```
In kernel/cgroup/freezer.c (ffffffff8116d8d4)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_update_frozen
  - kernel/cgroup/freezer.c:cgroup_update_frozen
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8116e0d2)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (ffffffff8116f0ae)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_try_charge
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
```
In kernel/cgroup/cpuset.c (ffffffff81174e5a)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:cpuset_read_unlock
  - kernel/cgroup/cpuset.c:cpuset_read_lock
```
```
In kernel/stop_machine.c (ffffffff811777a7)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
  - kernel/stop_machine.c:queue_stop_cpus_work
  - kernel/stop_machine.c:stop_two_cpus
  - kernel/stop_machine.c:cpu_stop_queue_work
```
```
In kernel/kprobes.c (ffffffff81185754)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/kprobes.c:show_kprobe_addr
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81190668)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/hung_task.c (ffffffff81193692)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
```
```
In kernel/seccomp.c (ffffffff811954dc)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In kernel/relay.c (ffffffff81196d08)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/relay.c:relay_late_setup_files
```
```
In kernel/trace/trace_clock.c (ffffffff8119a8b0)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/trace/trace_clock.c:trace_clock_local
```
```
In kernel/trace/ftrace.c (ffffffff8119b38a)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:fpid_start
  - kernel/trace/ftrace.c:ftrace_ops_assist_func
  - kernel/trace/ftrace.c:ftrace_ops_list_func
  - kernel/trace/ftrace.c:ftrace_mod_get_kallsym
  - kernel/trace/ftrace.c:ftrace_mod_address_lookup
  - kernel/trace/ftrace.c:function_trace_probe_call
  - kernel/trace/ftrace.c:ftrace_ops_trampoline
```
```
In kernel/trace/ring_buffer.c (ffffffff811a59a7)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_consume
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_nest_start
  - kernel/trace/ring_buffer.c:ring_buffer_time_stamp
```
```
In kernel/trace/trace.c (ffffffff811a6ec0)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/trace/trace.c:saved_cmdlines_start
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
  - kernel/trace/trace.c:trace_buffered_event_enable
  - kernel/trace/trace.c:trace_find_cmdline
```
```
In kernel/trace/trace_functions.c (ffffffff811b5c85)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:function_trace_call
  - kernel/trace/trace_functions.c:function_trace_init
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811b69ea)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
  - kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry
```
```
In kernel/trace/trace_stack.c (ffffffff811b8260)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/trace/trace_stack.c:stack_trace_call
```
```
In kernel/trace/trace_mmiotrace.c (ffffffff811b8dd7)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
```
```
In kernel/trace/trace_functions_graph.c (ffffffff811b93f1)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
  - kernel/trace/trace_functions_graph.c:trace_graph_entry
```
```
In kernel/trace/blktrace.c (ffffffff811bcc62)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:__blk_add_trace
```
```
In kernel/trace/trace_events.c (ffffffff811bfbfa)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:p_start
```
```
In kernel/trace/bpf_trace.c (ffffffff811d0e5e)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_trace_run12
  - kernel/trace/bpf_trace.c:bpf_trace_run11
  - kernel/trace/bpf_trace.c:bpf_trace_run10
  - kernel/trace/bpf_trace.c:bpf_trace_run9
  - kernel/trace/bpf_trace.c:bpf_trace_run8
  - kernel/trace/bpf_trace.c:bpf_trace_run7
  - kernel/trace/bpf_trace.c:bpf_trace_run6
  - kernel/trace/bpf_trace.c:bpf_trace_run5
  - kernel/trace/bpf_trace.c:bpf_trace_run4
  - kernel/trace/bpf_trace.c:bpf_trace_run3
  - kernel/trace/bpf_trace.c:bpf_trace_run2
  - kernel/trace/bpf_trace.c:bpf_trace_run1
```
```
In kernel/trace/trace_uprobe.c (ffffffff811dcd67)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In kernel/irq_work.c (ffffffff811df10d)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_queue_on
```
```
In kernel/bpf/core.c (ffffffff811e2af5)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_user_rnd_u32
```
```
In kernel/bpf/syscall.c (ffffffff811e72a6)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
```
```
In kernel/bpf/helpers.c (ffffffff811f7680)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:copy_map_value_locked
```
```
In kernel/bpf/hashtab.c (ffffffff811f82e3)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_elem_free_rcu
```
```
In kernel/bpf/arraymap.c (ffffffff811fb46c)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/bpf/devmap.c (ffffffff81203955)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:bq_xmit_all
```
```
In kernel/bpf/cpumap.c (ffffffff81204a3d)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:bq_flush_to_queue
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In kernel/bpf/offload.c (ffffffff81206596)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In kernel/bpf/stackmap.c (ffffffff8120829f)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/bpf/cgroup.c (ffffffff81209f54)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/bpf/cgroup.c:__cgroup_bpf_check_dev_permission
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_query
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
```
In kernel/events/core.c (ffffffff81214daa)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:bpf_overflow_handler
  - kernel/events/core.c:__perf_sw_event
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_event_update_userpage
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:perf_event_read
```
```
In kernel/events/ring_buffer.c (ffffffff8121cf9a)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
```
```
In kernel/events/uprobes.c (ffffffff81220f05)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_end_dup_mmap
  - kernel/events/uprobes.c:uprobe_start_dup_mmap
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__update_ref_ctr
  - kernel/events/uprobes.c:copy_to_page
  - kernel/events/uprobes.c:copy_from_page
```
```
In kernel/user-return-notifier.c (ffffffff812222c5)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/user-return-notifier.c:fire_user_return_notifiers
```
```
In kernel/padata.c (ffffffff81222882)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
  - kernel/padata.c:invoke_padata_reorder
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_parallel_worker
```
```
In kernel/jump_label.c (ffffffff812246b7)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_text_reserved
  - kernel/jump_label.c:jump_label_module_notify
```
```
In kernel/rseq.c (ffffffff81225544)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - kernel/rseq.c:__rseq_handle_notify_resume
  - kernel/rseq.c:rseq_ip_fixup
  - kernel/rseq.c:rseq_ip_fixup
```
```
In mm/filemap.c (ffffffff81228ae3)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:file_check_and_advance_wb_err
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/oom_kill.c (ffffffff8122f268)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:mark_oom_victim
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
```
```
In mm/page-writeback.c (ffffffff81234610)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - mm/page-writeback.c:account_page_dirtied
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:balance_dirty_pages
  - mm/page-writeback.c:wb_update_dirty_ratelimit
  - mm/page-writeback.c:domain_dirty_limits
```
```
In mm/swap.c (ffffffff81237b7d)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_drain
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:deactivate_file_page
  - mm/swap.c:__lru_cache_add
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:activate_page
```
```
In mm/truncate.c (ffffffff81239ba6)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff81241f1e)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:mem_cgroup_shrink_node
  - mm/vmscan.c:mem_cgroup_shrink_node
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:inactive_list_is_low
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:do_shrink_slab
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/shmem.c (ffffffff81245bdb)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/util.c (ffffffff8124b725)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - mm/util.c:memcmp_pages
  - mm/util.c:memcmp_pages
```
```
In mm/backing-dev.c (ffffffff8124e688)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - mm/backing-dev.c:wait_iff_congested
  - mm/backing-dev.c:congestion_wait
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/percpu.c (ffffffff81252038)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_create_chunk
```
```
In mm/slab_common.c (ffffffff812549c5)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_order_trace
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:destroy_memcg_params
```
```
In mm/compaction.c (ffffffff8125ba15)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
  - mm/compaction.c:wakeup_kcompactd
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:try_to_compact_pages
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compaction_suitable
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:compaction_deferred
  - mm/compaction.c:defer_compaction
```
```
In mm/gup.c (ffffffff8125f205)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page
```
```
In mm/memory.c (ffffffff8126b691)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_user_huge_page
  - mm/memory.c:copy_subpage
  - mm/memory.c:copy_subpage
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_subpage
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
```
```
In mm/rmap.c (ffffffff81279e6e)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff8127d360)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - mm/vmalloc.c:vwrite
  - mm/vmalloc.c:vread
  - mm/vmalloc.c:vm_map_ram
  - mm/vmalloc.c:vm_map_ram
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:alloc_vmap_area
```
```
In mm/page_alloc.c (ffffffff81287193)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:drain_local_pages_wq
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcp_prepare
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/swapfile.c (ffffffff8128ddf2)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:swap_count_continued
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:swp_swapcount
```
```
In mm/zswap.c (ffffffff812950a0)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/mempolicy.c (ffffffff8129e3c3)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_page_interleave
```
```
In mm/ksm.c (ffffffff812a879f)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/ksm.c:calc_checksum
```
```
In mm/page_poison.c (ffffffff812a8c39)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - mm/page_poison.c:kernel_poison_pages
  - mm/page_poison.c:kernel_poison_pages
```
```
In mm/slub.c (ffffffff812ae205)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - mm/slub.c:validate_slab_slab
  - mm/slub.c:validate_slab_slab
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:kfree
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:__slab_free
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:put_cpu_partial
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:free_debug_processing
```
```
In mm/memory_hotplug.c (ffffffff812b23f5)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:restore_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
  - mm/memory_hotplug.c:set_online_page_callback
```
```
In mm/migrate.c (ffffffff812b7e50)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff812ba722)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff812c2ccc)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (ffffffff812cf347)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_sk_free
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_event_remove
  - mm/memcontrol.c:mem_cgroup_flush_foreign
  - mm/memcontrol.c:mem_cgroup_track_foreign_dirty_slowpath
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:__memcg_kmem_uncharge
  - mm/memcontrol.c:__memcg_kmem_charge
  - mm/memcontrol.c:__memcg_kmem_charge
  - mm/memcontrol.c:memcg_kmem_put_cache
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:memcg_kmem_cache_create_func
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:get_mem_cgroup_from_page
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
```
```
In mm/hugetlb_cgroup.c (ffffffff812d0d1a)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup
```
```
In mm/memory-failure.c (ffffffff812d1105)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure_queue
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:action_result
```
```
In mm/page_isolation.c (ffffffff812d4bb9)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
```
```
In mm/zsmalloc.c (ffffffff812d79f1)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:zs_map_object
  - mm/zsmalloc.c:zs_map_object
  - mm/zsmalloc.c:zs_map_object
```
```
In mm/cma.c (ffffffff812d8a26)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - mm/cma.c:cma_release
  - mm/cma.c:cma_alloc
```
```
In mm/userfaultfd.c (ffffffff812d9941)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/memremap.c (ffffffff812db4ae)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - mm/memremap.c:get_dev_pagemap
  - mm/memremap.c:get_dev_pagemap
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memremap_pages
```
```
In mm/hmm.c (ffffffff812ddb34)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/open.c (ffffffff812e0fe1)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - fs/open.c:do_sys_open
```
```
In fs/read_write.c (ffffffff812e2956)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
```
```
In fs/super.c (ffffffff812e6c33)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - fs/super.c:__sb_end_write
```
```
In fs/exec.c (ffffffff812edf84)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - fs/exec.c:__set_task_comm
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
  - fs/exec.c:do_open_execat
```
```
In fs/dcache.c (ffffffff813004b5)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
```
```
In fs/inode.c (ffffffff813036a5)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - fs/inode.c:get_next_ino
  - fs/inode.c:__destroy_inode
```
```
In fs/file.c (ffffffff81307ba5)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In fs/namespace.c (ffffffff81308d3a)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write
  - fs/namespace.c:mnt_clone_write
  - fs/namespace.c:__mnt_want_write
```
```
In fs/libfs.c (ffffffff81313cec)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
  - fs/libfs.c:simple_write_begin
  - fs/libfs.c:simple_readpage
```
```
In fs/fs-writeback.c (ffffffff81319ff1)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_writeback
  - fs/fs-writeback.c:wb_writeback
  - fs/fs-writeback.c:wb_writeback
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/fs-writeback.c:queue_io
  - fs/fs-writeback.c:sb_clear_inode_writeback
  - fs/fs-writeback.c:sb_mark_inode_writeback
  - fs/fs-writeback.c:wb_start_background_writeback
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_detach_inode
  - fs/fs-writeback.c:wbc_detach_inode
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:wb_queue_work
```
```
In fs/buffer.c (ffffffff813282d5)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - fs/buffer.c:alloc_buffer_head
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_writepage
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:cont_write_begin
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:invalidate_bh_lru
  - fs/buffer.c:alloc_page_buffers
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_read
```
```
In fs/block_dev.c (ffffffff8132ea92)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_evict_inode
```
```
In fs/direct-io.c (ffffffff81330b48)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - fs/direct-io.c:do_direct_IO
```
```
In fs/mpage.c (ffffffff81332b6f)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/notify/group.c (ffffffff81334f2b)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_put_group
```
```
In fs/aio.c (ffffffff81345d3a)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - fs/aio.c:do_io_getevents
  - fs/aio.c:__ia32_sys_io_cancel
  - fs/aio.c:__x64_sys_io_cancel
  - fs/aio.c:__x32_compat_sys_io_submit
  - fs/aio.c:__ia32_compat_sys_io_submit
  - fs/aio.c:__ia32_sys_io_submit
  - fs/aio.c:__x64_sys_io_submit
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_poll_put_work
  - fs/aio.c:aio_poll_put_work
  - fs/aio.c:aio_poll_put_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_complete_rw
  - fs/aio.c:aio_complete_rw
  - fs/aio.c:aio_complete_rw
  - fs/aio.c:__ia32_sys_io_destroy
  - fs/aio.c:__x64_sys_io_destroy
  - fs/aio.c:__x32_compat_sys_io_setup
  - fs/aio.c:__ia32_compat_sys_io_setup
  - fs/aio.c:__ia32_sys_io_setup
  - fs/aio.c:__x64_sys_io_setup
  - fs/aio.c:aio_read_events
  - fs/aio.c:aio_read_events
  - fs/aio.c:lookup_ioctx
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:ioctx_alloc
  - fs/aio.c:free_ioctx_users
  - fs/aio.c:aio_setup_ring
```
```
In fs/io_uring.c (ffffffff8134d750)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - fs/io_uring.c:__ia32_sys_io_uring_enter
  - fs/io_uring.c:__ia32_sys_io_uring_enter
  - fs/io_uring.c:__x64_sys_io_uring_enter
  - fs/io_uring.c:__x64_sys_io_uring_enter
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:__io_free_req
  - fs/io_uring.c:io_get_req
  - fs/io_uring.c:io_get_req
```
```
In fs/dax.c (ffffffff8135127e)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - fs/dax.c:dax_finish_sync_fault
  - fs/dax.c:dax_finish_sync_fault
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
```
```
In fs/verity/verify.c (ffffffff8135a455)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - fs/verity/verify.c:extract_hash
```
```
In fs/locks.c (ffffffff813603cc)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - fs/locks.c:locks_remove_file
  - fs/locks.c:locks_remove_file
  - fs/locks.c:locks_remove_posix
  - fs/locks.c:fcntl_setlk
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:fcntl_getlease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:__break_lease
  - fs/locks.c:leases_conflict
  - fs/locks.c:time_out_leases
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:locks_get_lock_context
```
```
In fs/mbcache.c (ffffffff81368d21)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/iomap/buffered-io.c (ffffffff8136dfec)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_read_page_sync
  - fs/iomap/buffered-io.c:iomap_readpage_actor
```
```
In fs/proc/base.c (ffffffff8137ee0a)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - fs/proc/base.c:__set_oom_adj
```
```
In fs/ext4/balloc.c (ffffffff81398693)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ext4_jbd2.c (ffffffff8139acf2)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_forget
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb
```
```
In fs/ext4/extents.c (ffffffff813a3a4a)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:get_implied_cluster_alloc
  - fs/ext4/extents.c:get_implied_cluster_alloc
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/extents.c:ext4_remove_blocks
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:__read_extent_tree_block
```
```
In fs/ext4/extents_status.c (ffffffff813a71ae)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_insert_delayed_block
  - fs/ext4/extents_status.c:ext4_es_scan
  - fs/ext4/extents_status.c:ext4_es_scan
  - fs/ext4/extents_status.c:ext4_es_count
  - fs/ext4/extents_status.c:__es_shrink
  - fs/ext4/extents_status.c:ext4_es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:ext4_es_cache_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_find_extent_range
  - fs/ext4/extents_status.c:ext4_es_find_extent_range
```
```
In fs/ext4/fsmap.c (ffffffff813a90ac)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/fsmap.c:ext4_getfsmap_logdev
  - fs/ext4/fsmap.c:ext4_getfsmap_logdev
  - fs/ext4/fsmap.c:ext4_getfsmap_helper
  - fs/ext4/fsmap.c:ext4_getfsmap_helper
```
```
In fs/ext4/fsync.c (ffffffff813a960f)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/ialloc.c (ffffffff813abec6)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/indirect.c (ffffffff813ae366)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
```
In fs/ext4/inline.c (ffffffff813b17cd)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_journalled_write_inline_data
  - fs/ext4/inline.c:ext4_write_inline_data_end
  - fs/ext4/inline.c:ext4_readpage_inline
  - fs/ext4/inline.c:ext4_read_inline_page
  - fs/ext4/inline.c:ext4_read_inline_page
```
```
In fs/ext4/inode.c (ffffffff813ba1cb)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_releasepage
  - fs/ext4/inode.c:__ext4_journalled_invalidatepage
  - fs/ext4/inode.c:ext4_alloc_da_blocks
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_dax_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_da_reserve_space
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_journalled_zero_new_buffers
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_block_write_begin
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
```
```
In fs/ext4/ioctl.c (ffffffff813c19a3)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioc_getfsmap
  - fs/ext4/ioctl.c:ext4_ioc_getfsmap
  - fs/ext4/ioctl.c:ext4_getfsmap_format
```
```
In fs/ext4/mballoc.c (ffffffff813c7d83)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_release_group_pa
  - fs/ext4/mballoc.c:ext4_mb_release_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/move_extent.c (ffffffff813cd03a)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_page_mkuptodate
```
```
In fs/ext4/namei.c (ffffffff813d5430)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In fs/ext4/page-io.c (ffffffff813d6bf7)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (ffffffff813d7374)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/super.c (ffffffff813e4a6b)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:ext4_nfs_commit_metadata
  - fs/ext4/super.c:ext4_drop_inode
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
```
```
In fs/ext4/verity.c (ffffffff813f9b54)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In fs/jbd2/transaction.c (ffffffff813fd43b)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_refile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_unfile_buffer
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_create_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:jbd2_journal_extend
  - fs/jbd2/transaction.c:jbd2_journal_start_reserved
```
```
In fs/jbd2/commit.c (ffffffff813fde9a)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_data_buffers
```
```
In fs/jbd2/checkpoint.c (ffffffff81400901)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - fs/jbd2/checkpoint.c:__jbd2_journal_drop_transaction
  - fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
```
In fs/jbd2/journal.c (ffffffff81406b10)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_grab_journal_head
  - fs/jbd2/journal.c:jbd2_journal_add_journal_head
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
```
In fs/squashfs/file.c (ffffffff814092f5)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_fill_page
```
```
In fs/squashfs/symlink.c (ffffffff8140b1eb)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - fs/squashfs/symlink.c:squashfs_symlink_readpage
```
```
In fs/squashfs/file_direct.c (ffffffff8140b937)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/squashfs/page_actor.c (ffffffff8140bc7f)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - fs/squashfs/page_actor.c:direct_next_page
  - fs/squashfs/page_actor.c:direct_first_page
```
```
In fs/ecryptfs/mmap.c (ffffffff8142008c)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
```
In fs/ecryptfs/read_write.c (ffffffff81420632)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffff8142c270)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_do
```
```
In fs/fuse/file.c (ffffffff81433c48)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_locked
```
```
In fs/fuse/readdir.c (ffffffff8143b6ce)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_emit
```
```
In ipc/util.c (ffffffff814424d0)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
  - ipc/util.c:ipc_addid
```
```
In security/smack/smack_lsm.c (ffffffff81488dcf)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_netlabel
```
```
In security/tomoyo/domain.c (ffffffff81498f5b)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In security/apparmor/capability.c (ffffffff814a4dca)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - security/apparmor/capability.c:aa_capable
```
```
In security/apparmor/domain.c (ffffffff814aad65)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:profile_transition
```
```
In security/apparmor/policy_unpack.c (ffffffff814af398)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In security/apparmor/file.c (ffffffff814b6321)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/file.c:aa_path_link
  - security/apparmor/file.c:aa_path_perm
```
```
In security/apparmor/mount.c (ffffffff814bc1c1)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_mount_change_type
  - security/apparmor/mount.c:aa_bind_mount
  - security/apparmor/mount.c:aa_remount
```
```
In crypto/scatterwalk.c (ffffffff814cdf08)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/blkcipher.c (ffffffff814cfb14)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (0)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In crypto/ahash.c (ffffffff814d2348)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - crypto/ahash.c:hash_walk_next
```
```
In crypto/shash.c (ffffffff814d3add)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_digest
```
```
In block/bio.c (ffffffff814ec513)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - block/bio.c:bio_endio
  - block/bio.c:generic_end_io_acct
  - block/bio.c:generic_start_io_acct
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_truncate
```
```
In block/blk-core.c (ffffffff814f3966)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_account_io_done
  - block/blk-core.c:blk_account_io_done
  - block/blk-core.c:direct_make_request
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:blk_queue_enter
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-merge.c (ffffffff814f9204)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_queue_split
```
```
In block/blk-mq.c (ffffffff814ff14a)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:__blk_mq_insert_request
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:blk_mq_start_request
  - block/blk-mq.c:blk_mq_complete_request
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-tag.c (ffffffff81501f04)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
```
In block/blk-stat.c (ffffffff81502738)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_add
```
```
In block/blk-mq-sched.c (ffffffff81504096)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
  - block/blk-mq-sched.c:blk_mq_sched_request_inserted
```
```
In block/bounce.c (ffffffff815138e7)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - block/bounce.c:__blk_queue_bounce
  - block/bounce.c:__blk_queue_bounce
```
```
In block/blk-cgroup.c (ffffffff8151873e)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:__blkg_release
  - block/blk-cgroup.c:__blkg_release
```
```
In block/blk-throttle.c (ffffffff8151b724)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_pop_queued
  - block/blk-throttle.c:throtl_qnode_add_bio
```
```
In block/blk-iocost.c (ffffffff8151f647)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_rqos_throttle
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
  - block/blk-iocost.c:ioc_timer_fn
```
```
In block/bio-integrity.c (ffffffff81523c6a)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_process
```
```
In block/t10-pi.c (ffffffff81525470)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In block/blk-wbt.c (ffffffff815280c7)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
  - block/blk-wbt.c:wb_timer_fn
```
```
In lib/random32.c (ffffffff8152ea30)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - lib/random32.c:prandom_bytes
  - lib/random32.c:prandom_u32
```
```
In lib/scatterlist.c (ffffffff81530ae6)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In lib/iov_iter.c (ffffffff8153639a)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:memcpy_mcsafe_to_page
  - lib/iov_iter.c:memzero_page
  - lib/iov_iter.c:memcpy_to_page
  - lib/iov_iter.c:memcpy_from_page
```
```
In lib/percpu-refcount.c (ffffffff81538218)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_resurrect
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In lib/rhashtable.c (ffffffff815393a0)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
  - lib/rhashtable.c:rhashtable_rehash_table
```
```
In lib/percpu_counter.c (ffffffff81560d70)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - lib/percpu_counter.c:percpu_counter_add_batch
```
```
In arch/x86/lib/msr-smp.c (ffffffff8156b225)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:__rwmsr_on_cpus
```
```
In arch/x86/lib/msr.c (ffffffff8156b84e)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/lib/msr.c:do_trace_rdpmc
  - arch/x86/lib/msr.c:do_trace_read_msr
  - arch/x86/lib/msr.c:do_trace_write_msr
```
```
In drivers/gpio/gpiolib.c (ffffffff8157c67b)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_source_value_commit
  - drivers/gpio/gpiolib.c:gpio_set_open_drain_value_commit
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_raw_value_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_output_raw_commit
  - drivers/gpio/gpiolib.c:gpiod_direction_input
```
```
In drivers/pci/pcie/aer.c (ffffffff815ab4f0)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In drivers/acpi/sleep.c (ffffffff815e7b84)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_suspend_enter
  - drivers/acpi/sleep.c:acpi_suspend_enter
```
```
In drivers/clk/clk.c (ffffffff8165b31f)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_set_duty_cycle_nolock
  - drivers/clk/clk.c:clk_core_set_duty_cycle_nolock
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/clk/clk.c:clk_core_prepare
  - drivers/clk/clk.c:clk_core_prepare
  - drivers/clk/clk.c:clk_core_unprepare
  - drivers/clk/clk.c:clk_core_unprepare
```
```
In drivers/xen/grant-table.c (ffffffff816713f0)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff81672e1f)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/xen/events/events_base.c (ffffffff816748c6)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:__xen_evtchn_do_upcall
```
```
In drivers/xen/events/events_2l.c (ffffffff81677298)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_unmask
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81681594)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
```
```
In drivers/regulator/core.c (ffffffff81687621)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:_regulator_do_enable
```
```
In drivers/char/random.c (ffffffff816cdc2d)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/char/random.c:urandom_read
  - drivers/char/random.c:get_random_bytes_arch
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:_xfer_secondary_pool
  - drivers/char/random.c:add_disk_randomness
  - drivers/char/random.c:add_device_randomness
  - drivers/char/random.c:credit_entropy_bits
  - drivers/char/random.c:mix_pool_bytes
  - drivers/char/random.c:__mix_pool_bytes
```
```
In drivers/char/virtio_console.c (ffffffff816d00d9)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/iommu/iommu.c (ffffffff816e7991)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_aux_detach_device
  - drivers/iommu/iommu.c:iommu_aux_attach_device
  - drivers/iommu/iommu.c:report_iommu_fault
  - drivers/iommu/iommu.c:__iommu_unmap
  - drivers/iommu/iommu.c:iommu_map
  - drivers/iommu/iommu.c:__iommu_attach_device
  - drivers/iommu/iommu.c:iommu_group_remove_device
  - drivers/iommu/iommu.c:iommu_group_add_device
```
```
In drivers/iommu/intel-iommu.c (ffffffff816fbfec)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:bounce_unmap_single
  - drivers/iommu/intel-iommu.c:bounce_map_single
  - drivers/iommu/intel-iommu.c:intel_unmap_sg
  - drivers/iommu/intel-iommu.c:intel_unmap
  - drivers/iommu/intel-iommu.c:__intel_map_single
```
```
In drivers/connector/cn_proc.c (ffffffff81703852)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/connector/cn_proc.c:proc_exit_connector
  - drivers/connector/cn_proc.c:proc_coredump_connector
  - drivers/connector/cn_proc.c:proc_comm_connector
  - drivers/connector/cn_proc.c:proc_ptrace_connector
  - drivers/connector/cn_proc.c:proc_sid_connector
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/connector/cn_proc.c:proc_exec_connector
  - drivers/connector/cn_proc.c:proc_fork_connector
```
```
In drivers/base/syscore.c (ffffffff8170eac0)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_resume
  - drivers/base/syscore.c:syscore_suspend
  - drivers/base/syscore.c:syscore_suspend
```
```
In drivers/base/power/qos.c (ffffffff81719884)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/base/power/qos.c:__dev_pm_qos_remove_request
  - drivers/base/power/qos.c:__dev_pm_qos_update_request
  - drivers/base/power/qos.c:__dev_pm_qos_add_request
```
```
In drivers/base/power/runtime.c (ffffffff8171aca9)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
```
```
In drivers/base/power/main.c (ffffffff81720a1b)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/power/main.c:dpm_run_callback
  - drivers/base/power/main.c:dpm_run_callback
```
```
In drivers/base/power/wakeup.c (ffffffff817216b8)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In drivers/base/regmap/regmap.c (ffffffff8172ce6e)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_async_complete_cb
  - drivers/base/regmap/regmap.c:_regmap_read
  - drivers/base/regmap/regmap.c:_regmap_raw_read
  - drivers/base/regmap/regmap.c:_regmap_raw_read
  - drivers/base/regmap/regmap.c:_regmap_raw_multi_reg_write
  - drivers/base/regmap/regmap.c:_regmap_raw_multi_reg_write
  - drivers/base/regmap/regmap.c:_regmap_write
  - drivers/base/regmap/regmap.c:_regmap_bus_formatted_write
  - drivers/base/regmap/regmap.c:_regmap_bus_formatted_write
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
  - drivers/base/regmap/regmap.c:_regmap_raw_write_impl
```
```
In drivers/base/regmap/regcache.c (ffffffff81731fd6)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/base/regmap/regcache.c:regcache_cache_bypass
  - drivers/base/regmap/regcache.c:regcache_cache_only
  - drivers/base/regmap/regcache.c:regcache_drop_region
  - drivers/base/regmap/regcache.c:regcache_sync_region
  - drivers/base/regmap/regcache.c:regcache_sync_region
  - drivers/base/regmap/regcache.c:regcache_sync
  - drivers/base/regmap/regcache.c:regcache_sync
```
```
In drivers/block/loop.c (ffffffff8173ad06)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_rq
  - drivers/block/loop.c:lo_rw_aio_complete
  - drivers/block/loop.c:transfer_xor
  - drivers/block/loop.c:transfer_xor
```
```
In drivers/block/xen-blkfront.c (ffffffff8173cfef)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_copy_from_grant
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/nvdimm/region_devs.c (ffffffff81762f77)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_release_lane
  - drivers/nvdimm/region_devs.c:nd_region_acquire_lane
```
```
In drivers/dax/super.c (ffffffff817722be)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81775029)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_add_callback
  - drivers/dma-buf/dma-fence.c:dma_fence_release
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_signal_locked
```
```
In drivers/dma-buf/dma-resv.c (ffffffff8177735d)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81778495)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
```
```
In drivers/scsi/scsi_error.c (ffffffff8177f19d)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
```
```
In drivers/scsi/scsi_lib.c (ffffffff81781bbd)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_done
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/scsi/sd.c (ffffffff8179321f)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
  - drivers/scsi/sd.c:sd_setup_write_same10_cmnd
  - drivers/scsi/sd.c:sd_setup_write_same16_cmnd
```
```
In drivers/ata/libata-core.c (ffffffff8179f5b5)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-core.c:ata_qc_complete
  - drivers/ata/libata-core.c:ata_qc_complete
  - drivers/ata/libata-core.c:ata_qc_complete
```
```
In drivers/ata/libata-eh.c (ffffffff817ad351)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
```
In drivers/ata/libata-sff.c (ffffffff817b4cf3)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_pio_sector
```
```
In drivers/spi/spi.c (ffffffff817c4d5c)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_sync
  - drivers/spi/spi.c:__spi_async
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_transfer_one_message
```
```
In drivers/net/phy/mdio_bus.c (ffffffff817cd291)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:__mdiobus_write
  - drivers/net/phy/mdio_bus.c:__mdiobus_read
```
```
In drivers/net/tun.c (ffffffff817d411d)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817d95e5)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In drivers/usb/host/xhci.c (ffffffff81847220)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
```
In drivers/usb/host/xhci-mem.c (ffffffff8184a760)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_free_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_ring_alloc
```
```
In drivers/usb/host/xhci-ring.c (ffffffff8184e5f4)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:queue_command
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_ctrl_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:inc_enq
  - drivers/usb/host/xhci-ring.c:inc_deq
```
```
In drivers/usb/host/xhci-hub.c (ffffffff81856ac2)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_status_data
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8185b643)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
  - drivers/usb/host/xhci-dbgcap.c:dbc_free_request
  - drivers/usb/host/xhci-dbgcap.c:dbc_alloc_request
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
```
```
In drivers/usb/host/xhci-pci.c (ffffffff8185f5c9)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In drivers/rtc/interface.c (ffffffff818777b6)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_set_offset
  - drivers/rtc/interface.c:rtc_read_offset
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_do_work
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_irq_set_freq
  - drivers/rtc/interface.c:rtc_irq_set_state
  - drivers/rtc/interface.c:rtc_alarm_irq_enable
  - drivers/rtc/interface.c:__rtc_set_alarm
  - drivers/rtc/interface.c:rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:rtc_read_time
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8187cf81)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffff8187ff80)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In drivers/hwmon/hwmon.c (ffffffff81895243)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:hwmon_attr_store
  - drivers/hwmon/hwmon.c:hwmon_attr_show_string
  - drivers/hwmon/hwmon.c:hwmon_attr_show
```
```
In drivers/thermal/thermal_core.c (ffffffff81897079)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In drivers/thermal/thermal_helpers.c (ffffffff8189bb2a)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/thermal/thermal_helpers.c:thermal_cdev_update
```
```
In drivers/thermal/fair_share.c (ffffffff8189c422)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/thermal/fair_share.c:fair_share_throttle
```
```
In drivers/thermal/step_wise.c (ffffffff8189ca5c)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/thermal/step_wise.c:thermal_zone_trip_update
```
```
In drivers/thermal/power_allocator.c (ffffffff8189db09)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:allocate_power
  - drivers/thermal/power_allocator.c:allocate_power
```
```
In drivers/thermal/devfreq_cooling.c (ffffffff8189e434)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_power2state
  - drivers/thermal/devfreq_cooling.c:devfreq_cooling_get_requested_power
```
```
In drivers/md/md.c (ffffffff818aa125)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/md/md.c:md_write_end
  - drivers/md/md.c:md_make_request
```
```
In drivers/md/md-bitmap.c (ffffffff818b784f)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_file_clear_bit
  - drivers/md/md-bitmap.c:md_bitmap_file_set_bit
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_print_sb
```
```
In drivers/md/dm.c (ffffffff818bafb0)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_process_bio
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:__map_bio
```
```
In drivers/md/dm-stats.c (ffffffff818c7482)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_account_io
```
```
In drivers/md/dm-rq.c (ffffffff818c81bd)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:map_request
```
```
In drivers/edac/edac_mc.c (ffffffff818c96c1)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_handle_error
  - drivers/edac/edac_mc.c:edac_raw_mc_handle_error
```
```
In drivers/edac/ghes_edac.c (ffffffff818cd986)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/edac/ghes_edac.c:ghes_edac_report_mem_error
```
```
In drivers/cpufreq/cpufreq.c (ffffffff818d4d49)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_set_policy
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff818d7201)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_init
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff818d9955)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff818dec7e)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_util
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_pstate
```
```
In drivers/cpuidle/cpuidle.c (ffffffff818e0a4d)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_use_deepest_state
```
```
In drivers/cpuidle/driver.c (ffffffff818e13b5)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/cpuidle/driver.c:cpuidle_driver_unref
  - drivers/cpuidle/driver.c:cpuidle_driver_ref
```
```
In drivers/mmc/core/core.c (ffffffff818e4c79)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_cqe_request_done
  - drivers/mmc/core/core.c:mmc_cqe_start_req
  - drivers/mmc/core/core.c:__mmc_start_request
  - drivers/mmc/core/core.c:mmc_request_done
```
```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff818ff858)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
```
```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff8190270d)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_proto.c:send_command
```
```
In drivers/devfreq/devfreq.c (ffffffff81909962)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_monitor
```
```
In drivers/ras/ras.c (ffffffff81913e4e)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - drivers/ras/ras.c:log_arm_hw_error
  - drivers/ras/ras.c:log_non_standard_event
```
```
In net/core/sock.c (ffffffff8192469b)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff8192982c)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:__consume_stateless_skb
  - net/core/skbuff.c:consume_skb
  - net/core/skbuff.c:skb_dump
  - net/core/skbuff.c:kfree_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/skbuff.c:netdev_alloc_frag
```
```
In net/core/datagram.c (ffffffff819338b2)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_datagram_iter
```
```
In net/core/gen_estimator.c (ffffffff8193621c)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/flow_dissector.c (ffffffff81939265)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/core/flow_dissector.c:bpf_flow_dissect
```
```
In net/core/dev.c (ffffffff819485c6)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_receive
  - net/core/dev.c:napi_gro_receive
  - net/core/dev.c:flush_backlog
  - net/core/dev.c:netif_receive_skb_list
  - net/core/dev.c:netif_receive_skb_list
  - net/core/dev.c:netif_receive_skb
  - net/core/dev.c:netif_receive_skb
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:netif_rx_ni
  - net/core/dev.c:netif_rx_ni
  - net/core/dev.c:netif_rx_ni
  - net/core/dev.c:netif_rx
  - net/core/dev.c:netif_rx
  - net/core/dev.c:netif_rx_internal
  - net/core/dev.c:netif_rx_internal
  - net/core/dev.c:netif_rx_internal
  - net/core/dev.c:generic_xdp_tx
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_hard_start_xmit
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/core/neighbour.c (ffffffff81954745)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_seq_start
  - net/core/neighbour.c:neigh_xmit
  - net/core/neighbour.c:neigh_for_each
  - net/core/neighbour.c:neigh_dump_info
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:__neigh_event_send
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_lookup_nodev
  - net/core/neighbour.c:neigh_lookup
  - net/core/neighbour.c:neigh_cleanup_and_release
```
```
In net/core/filter.c (ffffffff8196d5a4)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_redirect
  - net/core/filter.c:xdp_do_redirect
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/core/sock_reuseport.c (ffffffff81973eeb)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/core/xdp.c (ffffffff81975c52)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
  - net/core/xdp.c:mem_xa_remove
  - net/core/xdp.c:mem_xa_remove
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff81976e94)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/core/page_pool.c (ffffffff8197a7f9)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:__page_pool_clean_page
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
```
```
In net/core/skmsg.c (ffffffff8197b485)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
```
```
In net/core/netpoll.c (ffffffff8197dd15)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
  - net/core/netpoll.c:netpoll_poll_dev
```
```
In net/core/lwt_bpf.c (ffffffff8198ac9e)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In net/core/sock_map.c (ffffffff8198d085)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_elem
  - net/core/sock_map.c:sock_map_update_elem
```
```
In net/core/devlink.c (ffffffff81990d88)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_health_report
  - net/core/devlink.c:devlink_health_report
```
```
In net/sched/sch_generic.c (ffffffff819a1c7a)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/netlink/af_netlink.c (ffffffff819b44d7)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/bpf/test_run.c (ffffffff819b8218)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
```
```
In net/netfilter/nf_log.c (ffffffff819b99ec)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/netfilter/nf_log.c:nf_log_buf_open
```
```
In net/netfilter/nf_queue.c (ffffffff819ba52c)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_reinject
```
```
In net/ipv4/route.c (ffffffff819bd6a6)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_confirm_neigh
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff819c65df)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/inet_hashtables.c (ffffffff819cc5a5)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff819ce51d)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819cfd58)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
```
```
In net/ipv4/tcp.c (ffffffff819d6cc8)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffff819e2778)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
```
```
In net/ipv4/tcp_output.c (ffffffff819e910c)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819eb7f5)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819f05ca)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
```
In net/ipv4/udp.c (ffffffff819fd0b1)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/icmp.c (ffffffff81a02dab)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/af_inet.c (ffffffff81a0ad56)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sk_state_store
  - net/ipv4/af_inet.c:inet_sk_set_state
```
```
In net/ipv4/fib_frontend.c (ffffffff81a10666)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff81a164f6)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_multipath
```
```
In net/ipv4/fib_trie.c (ffffffff81a18ba2)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
```
```
In net/ipv4/inet_fragment.c (ffffffff81a1b542)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81a1e2a2)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/nexthop.c (ffffffff81a20859)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81a27978)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a36d5a)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/unix/af_unix.c (ffffffff81a45fb9)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/ipv6/ip6_output.c (ffffffff81a4d459)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/addrconf.c (ffffffff81a560b5)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff81a6443b)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv6/route.c:__ip6_route_redirect
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:fib6_table_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:rt6_score_route
  - net/ipv6/route.c:ip6_confirm_neigh
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ip6_fib.c (ffffffff81a6afca)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_start
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81a709d1)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff81a7cda7)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a86939)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81a8c48f)
Location: arch/x86/include/asm/preempt.h:77
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
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a9ad41)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_input
  - net/ipv6/seg6_iptunnel.c:seg6_input
```
```
In net/ipv6/seg6_local.c (ffffffff81a9c5e4)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_bpf
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a9cf65)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a9fb46)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81aa20c4)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_fanout
```
```
In net/xdp/xsk.c (ffffffff81ac2401)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
  - net/xdp/xsk.c:xsk_release
```
```
In lib/bug.c (ffffffff81ac4f70)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - lib/bug.c:generic_bug_clear_once
  - lib/bug.c:module_find_bug
```
```
In lib/nmi_backtrace.c (ffffffff81aca370)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
```
In lib/radix-tree.c (ffffffff81acaee2)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_preload
  - lib/radix-tree.c:__radix_tree_preload
  - lib/radix-tree.c:__radix_tree_preload
```
```
In arch/x86/lib/delay.c (ffffffff81ad8765)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/lib/delay.c:delay_tsc
  - arch/x86/lib/delay.c:delay_tsc
```
```
In arch/x86/lib/usercopy_64.c (ffffffff81adaed5)
Location: arch/x86/include/asm/preempt.h:77
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:memcpy_page_flushcache
```
</details>
</li>
</ul>

## Differences
