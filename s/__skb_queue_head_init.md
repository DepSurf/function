# Function: <code>__skb_queue_head_init</code>

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
In kernel/audit.c (ffffffff81f82324)
Location: include/linux/skbuff.h:1447
Inline: True
```
```
In kernel/auditfilter.c (ffffffff8112539e)
Location: include/linux/skbuff.h:1447
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff815f6208)
Location: include/linux/skbuff.h:1447
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
```
In drivers/net/xen-netfront.c (ffffffff815fb3e1)
Location: include/linux/skbuff.h:1447
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/sock.c (ffffffff81700cd7)
Location: include/linux/skbuff.h:1447
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
```
```
In net/core/dev.c (ffffffff81fbb0a7)
Location: include/linux/skbuff.h:1447
Inline: True
Inline callers:
  - net/core/dev.c:process_backlog
```
```
In net/core/neighbour.c (ffffffff81728577)
Location: include/linux/skbuff.h:1447
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:__neigh_create
```
```
In net/core/netpoll.c (ffffffff81fbb43b)
Location: include/linux/skbuff.h:1447
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_init
  - net/core/netpoll.c:__netpoll_setup
```
```
In net/sched/sch_generic.c (ffffffff81740b4d)
Location: include/linux/skbuff.h:1447
Inline: True
Inline callers:
  - net/sched/sch_generic.c:pfifo_fast_init
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/ipv4/ip_output.c (ffffffff8175f4fe)
Location: include/linux/skbuff.h:1447
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_make_skb
```
```
In net/ipv4/tcp.c (ffffffff817657c8)
Location: include/linux/skbuff.h:1447
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_init_sock
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8177ee89)
Location: include/linux/skbuff.h:1447
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
```
In net/ipv4/udp.c (ffffffff817887c6)
Location: include/linux/skbuff.h:1447
Inline: True
Inline callers:
  - net/ipv4/udp.c:first_packet_length
```
```
In net/ipv4/ipmr.c (ffffffff817a8f90)
Location: include/linux/skbuff.h:1447
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
```
```
In net/xfrm/xfrm_policy.c (ffffffff817b1685)
Location: include/linux/skbuff.h:1447
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/unix/garbage.c (ffffffff817c26ec)
Location: include/linux/skbuff.h:1447
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/ip6_output.c (ffffffff817c838f)
Location: include/linux/skbuff.h:1447
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_make_skb
```
```
In net/ipv6/ip6mr.c (ffffffff817f9cdb)
Location: include/linux/skbuff.h:1447
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
```
```
In net/wireless/wext-core.c (ffffffff81809857)
Location: include/linux/skbuff.h:1447
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wext_pernet_init
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
In kernel/audit.c (ffffffff81fab8a7)
Location: include/linux/skbuff.h:1548
Inline: True
```
```
In kernel/auditfilter.c (ffffffff8112d43d)
Location: include/linux/skbuff.h:1548
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8165637c)
Location: include/linux/skbuff.h:1548
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/net/xen-netfront.c (ffffffff8165b301)
Location: include/linux/skbuff.h:1548
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/sock.c (ffffffff81767857)
Location: include/linux/skbuff.h:1548
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
```
```
In net/core/dev.c (ffffffff81784227)
Location: include/linux/skbuff.h:1548
Inline: True
Inline callers:
  - net/core/dev.c:process_backlog
```
```
In net/core/neighbour.c (ffffffff817920c9)
Location: include/linux/skbuff.h:1548
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:__neigh_create
```
```
In net/core/netpoll.c (ffffffff81fe9051)
Location: include/linux/skbuff.h:1548
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_init
  - net/core/netpoll.c:__netpoll_setup
```
```
In net/sched/sch_generic.c (ffffffff817ae75f)
Location: include/linux/skbuff.h:1548
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_generic.c:pfifo_fast_init
  - net/sched/sch_generic.c:pfifo_fast_reset
```
```
In net/sched/sch_fifo.c (ffffffff817b6019)
Location: include/linux/skbuff.h:1548
Inline: True
Inline callers:
  - net/sched/sch_fifo.c:qdisc_reset_queue
```
```
In net/ipv4/ip_output.c (ffffffff817cb79e)
Location: include/linux/skbuff.h:1548
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_make_skb
```
```
In net/ipv4/tcp.c (ffffffff817d1d44)
Location: include/linux/skbuff.h:1548
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_init_sock
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffff817ec339)
Location: include/linux/skbuff.h:1548
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
```
In net/ipv4/udp.c (ffffffff817f6116)
Location: include/linux/skbuff.h:1548
Inline: True
Inline callers:
  - net/ipv4/udp.c:first_packet_length
```
```
In net/ipv4/ipmr.c (ffffffff818167a2)
Location: include/linux/skbuff.h:1548
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
```
```
In net/xfrm/xfrm_policy.c (ffffffff81822f07)
Location: include/linux/skbuff.h:1548
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/unix/garbage.c (ffffffff8182f718)
Location: include/linux/skbuff.h:1548
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/ip6_output.c (ffffffff818354a3)
Location: include/linux/skbuff.h:1548
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_make_skb
```
```
In net/ipv6/ip6mr.c (ffffffff81869566)
Location: include/linux/skbuff.h:1548
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
```
```
In net/wireless/wext-core.c (ffffffff8187b357)
Location: include/linux/skbuff.h:1548
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wext_pernet_init
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
In kernel/audit.c (ffffffff81fe7b9b)
Location: include/linux/skbuff.h:1563
Inline: True
```
```
In kernel/auditfilter.c (ffffffff8113716d)
Location: include/linux/skbuff.h:1563
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81684066)
Location: include/linux/skbuff.h:1563
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/net/xen-netfront.c (ffffffff81689121)
Location: include/linux/skbuff.h:1563
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/sock.c (ffffffff81794857)
Location: include/linux/skbuff.h:1563
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
```
```
In net/core/dev.c (ffffffff817b182f)
Location: include/linux/skbuff.h:1563
Inline: True
Inline callers:
  - net/core/dev.c:process_backlog
```
```
In net/core/neighbour.c (ffffffff817bf249)
Location: include/linux/skbuff.h:1563
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:__neigh_create
```
```
In net/core/netpoll.c (ffffffff8202793e)
Location: include/linux/skbuff.h:1563
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_init
  - net/core/netpoll.c:__netpoll_setup
```
```
In net/ipv4/ip_output.c (ffffffff817fb3fe)
Location: include/linux/skbuff.h:1563
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_make_skb
```
```
In net/ipv4/tcp.c (ffffffff81801ce2)
Location: include/linux/skbuff.h:1563
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_input.c (ffffffff81808eec)
Location: include/linux/skbuff.h:1563
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8181cc09)
Location: include/linux/skbuff.h:1563
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
```
In net/ipv4/ipmr.c (ffffffff81847f52)
Location: include/linux/skbuff.h:1563
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
```
```
In net/xfrm/xfrm_policy.c (ffffffff81854847)
Location: include/linux/skbuff.h:1563
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/unix/garbage.c (ffffffff8186114e)
Location: include/linux/skbuff.h:1563
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/ip6_output.c (ffffffff81866fd3)
Location: include/linux/skbuff.h:1563
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_make_skb
```
```
In net/ipv6/ip6mr.c (ffffffff8189c3b6)
Location: include/linux/skbuff.h:1563
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
```
```
In net/wireless/wext-core.c (ffffffff818afc17)
Location: include/linux/skbuff.h:1563
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wext_pernet_init
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
In kernel/audit.c (ffffffff820c81e0)
Location: include/linux/skbuff.h:1556
Inline: True
```
```
In kernel/auditfilter.c (ffffffff81138447)
Location: include/linux/skbuff.h:1556
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In drivers/net/tun.c (ffffffff81694c74)
Location: include/linux/skbuff.h:1556
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81699096)
Location: include/linux/skbuff.h:1556
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/net/xen-netfront.c (ffffffff8169e861)
Location: include/linux/skbuff.h:1556
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/sock.c (ffffffff817b2a77)
Location: include/linux/skbuff.h:1556
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
```
```
In net/core/dev.c (ffffffff817cf2ab)
Location: include/linux/skbuff.h:1556
Inline: True
Inline callers:
  - net/core/dev.c:process_backlog
```
```
In net/core/neighbour.c (ffffffff817dc0c0)
Location: include/linux/skbuff.h:1556
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:__neigh_create
```
```
In net/core/netpoll.c (ffffffff8210ae5a)
Location: include/linux/skbuff.h:1556
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_init
  - net/core/netpoll.c:__netpoll_setup
```
```
In net/core/gro_cells.c (ffffffff817f9a6f)
Location: include/linux/skbuff.h:1556
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff8181b7f2)
Location: include/linux/skbuff.h:1556
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_make_skb
```
```
In net/ipv4/tcp.c (ffffffff81821e3f)
Location: include/linux/skbuff.h:1556
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_init_sock
```
```
In net/ipv4/tcp_input.c (ffffffff818291a8)
Location: include/linux/skbuff.h:1556
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8183d458)
Location: include/linux/skbuff.h:1556
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
```
In net/ipv4/udp.c (ffffffff81845d42)
Location: include/linux/skbuff.h:1556
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_init_sock
  - net/ipv4/udp.c:udp_destruct_sock
  - net/ipv4/udp.c:udp_rmem_release
```
```
In net/ipv4/ipmr.c (ffffffff8186a526)
Location: include/linux/skbuff.h:1556
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
```
```
In net/xfrm/xfrm_policy.c (ffffffff81878308)
Location: include/linux/skbuff.h:1556
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/unix/garbage.c (ffffffff81885894)
Location: include/linux/skbuff.h:1556
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/ip6_output.c (ffffffff8188b780)
Location: include/linux/skbuff.h:1556
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_make_skb
```
```
In net/ipv6/ip6mr.c (ffffffff818c276d)
Location: include/linux/skbuff.h:1556
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
```
```
In net/wireless/wext-core.c (ffffffff818d640d)
Location: include/linux/skbuff.h:1556
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wext_pernet_init
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
In kernel/audit.c (ffffffff826d084f)
Location: include/linux/skbuff.h:1638
Inline: True
```
```
In kernel/auditfilter.c (ffffffff81145157)
Location: include/linux/skbuff.h:1638
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In kernel/bpf/sockmap.c (ffffffff811b122f)
Location: include/linux/skbuff.h:1638
Inline: True
```
```
In drivers/net/tun.c (ffffffff816ff507)
Location: include/linux/skbuff.h:1638
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
  - drivers/net/tun.c:tun_napi_poll
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81705e86)
Location: include/linux/skbuff.h:1638
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/net/xen-netfront.c (ffffffff81709a01)
Location: include/linux/skbuff.h:1638
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/sock.c (ffffffff8182ad4a)
Location: include/linux/skbuff.h:1638
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
```
```
In net/core/dev.c (ffffffff81848c06)
Location: include/linux/skbuff.h:1638
Inline: True
Inline callers:
  - net/core/dev.c:process_backlog
```
```
In net/core/neighbour.c (ffffffff8185652c)
Location: include/linux/skbuff.h:1638
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:__neigh_create
```
```
In net/core/netpoll.c (ffffffff82714801)
Location: include/linux/skbuff.h:1638
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_init
  - net/core/netpoll.c:__netpoll_setup
```
```
In net/core/gro_cells.c (ffffffff81877386)
Location: include/linux/skbuff.h:1638
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff8189a722)
Location: include/linux/skbuff.h:1638
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_make_skb
```
```
In net/ipv4/tcp_input.c (ffffffff818ae1de)
Location: include/linux/skbuff.h:1638
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
```
```
In net/ipv4/udp.c (ffffffff818c5769)
Location: include/linux/skbuff.h:1638
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_init_sock
  - net/ipv4/udp.c:udp_destruct_sock
  - net/ipv4/udp.c:udp_rmem_release
```
```
In net/ipv4/ipmr.c (ffffffff818eaca6)
Location: include/linux/skbuff.h:1638
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
```
```
In net/xfrm/xfrm_policy.c (ffffffff818f8c18)
Location: include/linux/skbuff.h:1638
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_input.c (ffffffff82717ba8)
Location: include/linux/skbuff.h:1638
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input_init
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/unix/garbage.c (ffffffff81906a44)
Location: include/linux/skbuff.h:1638
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/ip6_output.c (ffffffff8190ca20)
Location: include/linux/skbuff.h:1638
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_make_skb
```
```
In net/ipv6/ip6mr.c (ffffffff819460ad)
Location: include/linux/skbuff.h:1638
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
```
```
In net/wireless/wext-core.c (ffffffff8195bfcd)
Location: include/linux/skbuff.h:1638
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wext_pernet_init
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
In kernel/audit.c (ffffffff826fafd5)
Location: include/linux/skbuff.h:1649
Inline: True
Inline callers:
  - kernel/audit.c:audit_init
  - kernel/audit.c:audit_init
  - kernel/audit.c:audit_init
```
```
In kernel/auditfilter.c (ffffffff81153b01)
Location: include/linux/skbuff.h:1649
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In kernel/bpf/sockmap.c (ffffffff811cd2a0)
Location: include/linux/skbuff.h:1649
Inline: True
```
```
In drivers/net/tun.c (ffffffff8173ee92)
Location: include/linux/skbuff.h:1649
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
  - drivers/net/tun.c:tun_napi_poll
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81743bac)
Location: include/linux/skbuff.h:1649
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/net/xen-netfront.c (ffffffff817484a1)
Location: include/linux/skbuff.h:1649
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/sock.c (ffffffff81874e2d)
Location: include/linux/skbuff.h:1649
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
```
```
In net/core/dev.c (ffffffff8273e61d)
Location: include/linux/skbuff.h:1649
Inline: True
Inline callers:
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:process_backlog
```
```
In net/core/neighbour.c (ffffffff818a52e0)
Location: include/linux/skbuff.h:1649
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:__neigh_create
```
```
In net/core/netpoll.c (ffffffff8273e9f2)
Location: include/linux/skbuff.h:1649
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_init
  - net/core/netpoll.c:__netpoll_setup
```
```
In net/core/gro_cells.c (ffffffff818c8aa2)
Location: include/linux/skbuff.h:1649
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff818cdc3d)
Location: include/linux/skbuff.h:1649
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_init_scheduler
  - net/sched/sch_generic.c:dev_init_scheduler
  - net/sched/sch_generic.c:dev_init_scheduler
  - net/sched/sch_generic.c:dev_init_scheduler
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/ipv4/ip_output.c (ffffffff818eec04)
Location: include/linux/skbuff.h:1649
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_make_skb
```
```
In net/ipv4/tcp_input.c (ffffffff8190388d)
Location: include/linux/skbuff.h:1649
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
```
```
In net/ipv4/udp.c (ffffffff8191d0a7)
Location: include/linux/skbuff.h:1649
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_init_sock
  - net/ipv4/udp.c:udp_destruct_sock
  - net/ipv4/udp.c:udp_rmem_release
```
```
In net/ipv4/ipmr.c (ffffffff8194144c)
Location: include/linux/skbuff.h:1649
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
```
```
In net/xfrm/xfrm_policy.c (ffffffff8194f645)
Location: include/linux/skbuff.h:1649
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_input.c (ffffffff82741f9e)
Location: include/linux/skbuff.h:1649
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input_init
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (ffffffff81958488)
Location: include/linux/skbuff.h:1649
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
```
```
In net/unix/garbage.c (ffffffff8195da50)
Location: include/linux/skbuff.h:1649
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/ip6_output.c (ffffffff81963e3e)
Location: include/linux/skbuff.h:1649
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_make_skb
```
```
In net/ipv6/ip6mr.c (ffffffff8199db85)
Location: include/linux/skbuff.h:1649
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
```
```
In net/wireless/wext-core.c (ffffffff819b583d)
Location: include/linux/skbuff.h:1649
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wext_pernet_init
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
In kernel/audit.c (ffffffff828b1f01)
Location: include/linux/skbuff.h:1729
Inline: True
Inline callers:
  - kernel/audit.c:audit_init
  - kernel/audit.c:audit_init
  - kernel/audit.c:audit_init
```
```
In kernel/auditfilter.c (ffffffff81160891)
Location: include/linux/skbuff.h:1729
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In drivers/net/tun.c (ffffffff8176308f)
Location: include/linux/skbuff.h:1729
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
  - drivers/net/tun.c:tun_napi_poll
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8176685c)
Location: include/linux/skbuff.h:1729
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/net/xen-netfront.c (ffffffff8176c551)
Location: include/linux/skbuff.h:1729
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/sock.c (ffffffff818956ed)
Location: include/linux/skbuff.h:1729
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
```
```
In net/core/dev.c (ffffffff828f867c)
Location: include/linux/skbuff.h:1729
Inline: True
Inline callers:
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:process_backlog
```
```
In net/core/neighbour.c (ffffffff818c4ae5)
Location: include/linux/skbuff.h:1729
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:___neigh_create
```
```
In net/core/skmsg.c (ffffffff818e6304)
Location: include/linux/skbuff.h:1729
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_init
```
```
In net/core/netpoll.c (ffffffff828f8a8f)
Location: include/linux/skbuff.h:1729
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_init
  - net/core/netpoll.c:__netpoll_setup
```
```
In net/core/gro_cells.c (ffffffff818f39c2)
Location: include/linux/skbuff.h:1729
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff818f853b)
Location: include/linux/skbuff.h:1729
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/ipv4/ip_output.c (ffffffff8191c3a4)
Location: include/linux/skbuff.h:1729
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_make_skb
```
```
In net/ipv4/tcp_input.c (ffffffff81931a2a)
Location: include/linux/skbuff.h:1729
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
```
```
In net/ipv4/udp.c (ffffffff8194b657)
Location: include/linux/skbuff.h:1729
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_init_sock
  - net/ipv4/udp.c:udp_destruct_sock
  - net/ipv4/udp.c:udp_rmem_release
```
```
In net/ipv4/ipmr.c (ffffffff81971c0c)
Location: include/linux/skbuff.h:1729
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
```
```
In net/xfrm/xfrm_policy.c (ffffffff81982c7f)
Location: include/linux/skbuff.h:1729
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_input.c (ffffffff828fc257)
Location: include/linux/skbuff.h:1729
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input_init
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (ffffffff8198d088)
Location: include/linux/skbuff.h:1729
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
```
```
In net/unix/garbage.c (ffffffff81992590)
Location: include/linux/skbuff.h:1729
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/ip6_output.c (ffffffff81998dd6)
Location: include/linux/skbuff.h:1729
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_make_skb
```
```
In net/ipv6/ip6mr.c (ffffffff819d474d)
Location: include/linux/skbuff.h:1729
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
```
```
In net/wireless/wext-core.c (ffffffff819ecafd)
Location: include/linux/skbuff.h:1729
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wext_pernet_init
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
In kernel/audit.c (ffffffff828cac9d)
Location: include/linux/skbuff.h:1819
Inline: True
Inline callers:
  - kernel/audit.c:audit_init
  - kernel/audit.c:audit_init
  - kernel/audit.c:audit_init
```
```
In kernel/auditfilter.c (ffffffff8116cf0b)
Location: include/linux/skbuff.h:1819
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In drivers/net/tun.c (ffffffff817a0c00)
Location: include/linux/skbuff.h:1819
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
  - drivers/net/tun.c:tun_napi_poll
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817a56ad)
Location: include/linux/skbuff.h:1819
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/net/xen-netfront.c (ffffffff817aa373)
Location: include/linux/skbuff.h:1819
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/sock.c (ffffffff818dfc0d)
Location: include/linux/skbuff.h:1819
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
```
```
In net/core/dev.c (ffffffff829140ed)
Location: include/linux/skbuff.h:1819
Inline: True
Inline callers:
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:process_backlog
```
```
In net/core/neighbour.c (ffffffff819144fb)
Location: include/linux/skbuff.h:1819
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:___neigh_create
```
```
In net/core/skmsg.c (ffffffff81935ca4)
Location: include/linux/skbuff.h:1819
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_init
```
```
In net/core/netpoll.c (ffffffff82914504)
Location: include/linux/skbuff.h:1819
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_init
  - net/core/netpoll.c:__netpoll_setup
```
```
In net/core/gro_cells.c (ffffffff81952855)
Location: include/linux/skbuff.h:1819
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff81957cec)
Location: include/linux/skbuff.h:1819
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/ipv4/ip_output.c (ffffffff8197e6d5)
Location: include/linux/skbuff.h:1819
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_make_skb
```
```
In net/ipv4/tcp_input.c (ffffffff81995127)
Location: include/linux/skbuff.h:1819
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
```
```
In net/ipv4/udp.c (ffffffff819afd74)
Location: include/linux/skbuff.h:1819
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_init_sock
  - net/ipv4/udp.c:udp_destruct_sock
  - net/ipv4/udp.c:udp_rmem_release
```
```
In net/ipv4/ipmr.c (ffffffff819db3a1)
Location: include/linux/skbuff.h:1819
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
```
```
In net/xfrm/xfrm_policy.c (ffffffff819ec96c)
Location: include/linux/skbuff.h:1819
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_input.c (ffffffff82918d5f)
Location: include/linux/skbuff.h:1819
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input_init
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (ffffffff819f88f8)
Location: include/linux/skbuff.h:1819
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
```
```
In net/unix/garbage.c (ffffffff819fdb80)
Location: include/linux/skbuff.h:1819
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/ip6_output.c (ffffffff81a04c26)
Location: include/linux/skbuff.h:1819
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_make_skb
```
```
In net/ipv6/ip6mr.c (ffffffff81a435cd)
Location: include/linux/skbuff.h:1819
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
```
```
In net/wireless/wext-core.c (ffffffff81a5bccd)
Location: include/linux/skbuff.h:1819
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wext_pernet_init
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
In kernel/audit.c (ffffffff828d317f)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - kernel/audit.c:audit_init
  - kernel/audit.c:audit_init
  - kernel/audit.c:audit_init
```
```
In kernel/auditfilter.c (ffffffff81178dab)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In drivers/net/tun.c (ffffffff817c5bd0)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
  - drivers/net/tun.c:tun_napi_poll
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817c7d0d)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/net/xen-netfront.c (ffffffff817cddd3)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/sock.c (ffffffff81911dbd)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
```
```
In net/core/dev.c (ffffffff8291de70)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:process_backlog
```
```
In net/core/neighbour.c (ffffffff81946b6b)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:___neigh_create
```
```
In net/core/skmsg.c (ffffffff81968d64)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_init
```
```
In net/core/netpoll.c (ffffffff8291e299)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_init
  - net/core/netpoll.c:__netpoll_setup
```
```
In net/core/drop_monitor.c (ffffffff82920af8)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/gro_cells.c (ffffffff81988ba5)
Location: include/linux/skbuff.h:1829
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff8198e18c)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/ipv4/ip_output.c (ffffffff819b5075)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_make_skb
```
```
In net/ipv4/tcp_input.c (ffffffff819cbc77)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
```
```
In net/ipv4/udp.c (ffffffff819e6a0a)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_init_sock
  - net/ipv4/udp.c:udp_destruct_sock
  - net/ipv4/udp.c:udp_rmem_release
```
```
In net/ipv4/ipmr.c (ffffffff81a12275)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a2397c)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_input.c (ffffffff82922bce)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input_init
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (ffffffff81a2f558)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
```
```
In net/unix/garbage.c (ffffffff81a34770)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/ip6_output.c (ffffffff81a3b826)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_make_skb
```
```
In net/ipv6/ip6mr.c (ffffffff81a7a12f)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
```
```
In net/wireless/wext-core.c (ffffffff81a928fd)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wext_pernet_init
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
In kernel/audit.c (ffffffff82cf3c10)
Location: include/linux/skbuff.h:1852
Inline: True
Inline callers:
  - kernel/audit.c:audit_init
  - kernel/audit.c:audit_init
  - kernel/audit.c:audit_init
```
```
In kernel/auditfilter.c (ffffffff8118c005)
Location: include/linux/skbuff.h:1852
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In fs/io_uring.c (ffffffff8137fed8)
Location: include/linux/skbuff.h:1852
Inline: True
```
```
In drivers/net/tun.c (ffffffff8188e526)
Location: include/linux/skbuff.h:1852
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_receive
  - drivers/net/tun.c:tun_napi_receive
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81892450)
Location: include/linux/skbuff.h:1852
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/net/xen-netfront.c (ffffffff81899eea)
Location: include/linux/skbuff.h:1852
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/sock.c (ffffffff819e3d6d)
Location: include/linux/skbuff.h:1852
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
```
```
In net/core/dev.c (ffffffff82d2cf75)
Location: include/linux/skbuff.h:1852
Inline: True
Inline callers:
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:process_backlog
```
```
In net/core/neighbour.c (ffffffff81a132b2)
Location: include/linux/skbuff.h:1852
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_alloc
```
```
In net/core/skmsg.c (ffffffff81a3cb28)
Location: include/linux/skbuff.h:1852
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_init
```
```
In net/core/netpoll.c (ffffffff82d2d3b1)
Location: include/linux/skbuff.h:1852
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_init
  - net/core/netpoll.c:__netpoll_setup
```
```
In net/core/drop_monitor.c (ffffffff82d2d54a)
Location: include/linux/skbuff.h:1852
Inline: True
Inline callers:
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/gro_cells.c (ffffffff81a607fc)
Location: include/linux/skbuff.h:1852
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff81a65e16)
Location: include/linux/skbuff.h:1852
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/ipv4/ip_output.c (ffffffff81a9f2f5)
Location: include/linux/skbuff.h:1852
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_make_skb
```
```
In net/ipv4/tcp_input.c (ffffffff81ab1eef)
Location: include/linux/skbuff.h:1852
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
```
```
In net/ipv4/udp.c (ffffffff81ad4193)
Location: include/linux/skbuff.h:1852
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_init_sock
  - net/ipv4/udp.c:udp_destruct_sock
  - net/ipv4/udp.c:udp_rmem_release
```
```
In net/ipv4/ipmr.c (ffffffff81b046c5)
Location: include/linux/skbuff.h:1852
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b15892)
Location: include/linux/skbuff.h:1852
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_input.c (ffffffff82d2f1bd)
Location: include/linux/skbuff.h:1852
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input_init
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (ffffffff81b22168)
Location: include/linux/skbuff.h:1852
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
```
```
In net/xfrm/espintcp.c (ffffffff81b231db)
Location: include/linux/skbuff.h:1852
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_release
  - net/xfrm/espintcp.c:espintcp_release
  - net/xfrm/espintcp.c:espintcp_init_sk
  - net/xfrm/espintcp.c:espintcp_init_sk
```
```
In net/unix/garbage.c (ffffffff81b29583)
Location: include/linux/skbuff.h:1852
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/ip6_output.c (ffffffff81b30df4)
Location: include/linux/skbuff.h:1852
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_make_skb
```
```
In net/ipv6/ip6mr.c (ffffffff81b74a7f)
Location: include/linux/skbuff.h:1852
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
```
```
In net/wireless/wext-core.c (ffffffff81b8ddad)
Location: include/linux/skbuff.h:1852
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wext_pernet_init
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
In kernel/audit.c (ffffffff82fe06e7)
Location: include/linux/skbuff.h:1873
Inline: True
Inline callers:
  - kernel/audit.c:audit_init
  - kernel/audit.c:audit_init
  - kernel/audit.c:audit_init
```
```
In kernel/auditfilter.c (ffffffff8118921b)
Location: include/linux/skbuff.h:1873
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In fs/io_uring.c (ffffffff8138e9f8)
Location: include/linux/skbuff.h:1873
Inline: True
```
```
In drivers/net/tun.c (ffffffff8189cab6)
Location: include/linux/skbuff.h:1873
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_receive
  - drivers/net/tun.c:tun_napi_receive
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff818a096b)
Location: include/linux/skbuff.h:1873
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/net/xen-netfront.c (ffffffff818a9034)
Location: include/linux/skbuff.h:1873
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/sock.c (ffffffff819e36ad)
Location: include/linux/skbuff.h:1873
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
```
```
In net/core/dev.c (ffffffff8301ba59)
Location: include/linux/skbuff.h:1873
Inline: True
Inline callers:
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:process_backlog
```
```
In net/core/neighbour.c (ffffffff81a13692)
Location: include/linux/skbuff.h:1873
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_alloc
```
```
In net/core/skmsg.c (ffffffff81a3e6f5)
Location: include/linux/skbuff.h:1873
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_init
```
```
In net/core/netpoll.c (ffffffff8301be99)
Location: include/linux/skbuff.h:1873
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_init
  - net/core/netpoll.c:__netpoll_setup
```
```
In net/core/drop_monitor.c (ffffffff8301c032)
Location: include/linux/skbuff.h:1873
Inline: True
Inline callers:
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/gro_cells.c (ffffffff81a6909c)
Location: include/linux/skbuff.h:1873
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff81a6df1d)
Location: include/linux/skbuff.h:1873
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/ipv4/ip_output.c (ffffffff81aa9235)
Location: include/linux/skbuff.h:1873
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_make_skb
```
```
In net/ipv4/tcp_input.c (ffffffff81abceb3)
Location: include/linux/skbuff.h:1873
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
```
```
In net/ipv4/udp.c (ffffffff81ae06d3)
Location: include/linux/skbuff.h:1873
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_init_sock
  - net/ipv4/udp.c:udp_destruct_sock
  - net/ipv4/udp.c:udp_rmem_release
```
```
In net/ipv4/ipmr.c (ffffffff81b12835)
Location: include/linux/skbuff.h:1873
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b23ced)
Location: include/linux/skbuff.h:1873
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_input.c (ffffffff8301ddaf)
Location: include/linux/skbuff.h:1873
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input_init
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (ffffffff81b30b68)
Location: include/linux/skbuff.h:1873
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
```
```
In net/xfrm/espintcp.c (ffffffff81b31bcb)
Location: include/linux/skbuff.h:1873
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_release
  - net/xfrm/espintcp.c:espintcp_release
  - net/xfrm/espintcp.c:espintcp_init_sk
  - net/xfrm/espintcp.c:espintcp_init_sk
```
```
In net/unix/garbage.c (ffffffff81b37eb3)
Location: include/linux/skbuff.h:1873
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/ip6_output.c (ffffffff81b3fa24)
Location: include/linux/skbuff.h:1873
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_make_skb
```
```
In net/ipv6/ip6mr.c (ffffffff81b837ef)
Location: include/linux/skbuff.h:1873
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
```
```
In net/wireless/wext-core.c (ffffffff81b9da5d)
Location: include/linux/skbuff.h:1873
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wext_pernet_init
```
```
In net/mptcp/protocol.c (ffffffff81bc0962)
Location: include/linux/skbuff.h:1873
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_destroy_common
  - net/mptcp/protocol.c:__mptcp_init_sock
  - net/mptcp/protocol.c:__mptcp_init_sock
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:__mptcp_move_skbs
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
In kernel/audit.c (ffffffff831eb2cc)
Location: include/linux/skbuff.h:1889
Inline: True
Inline callers:
  - kernel/audit.c:audit_init
  - kernel/audit.c:audit_init
  - kernel/audit.c:audit_init
```
```
In kernel/auditfilter.c (ffffffff81189fe0)
Location: include/linux/skbuff.h:1889
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In fs/io_uring.c (ffffffff8139b802)
Location: include/linux/skbuff.h:1889
Inline: True
Inline callers:
  - fs/io_uring.c:io_rsrc_file_put
```
```
In drivers/net/tun.c (ffffffff8187f6d3)
Location: include/linux/skbuff.h:1889
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_poll
  - drivers/net/tun.c:tun_napi_poll
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81882ff7)
Location: include/linux/skbuff.h:1889
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/net/wwan/wwan_core.c (ffffffff81888192)
Location: include/linux/skbuff.h:1889
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff8188c2b2)
Location: include/linux/skbuff.h:1889
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/sock.c (ffffffff819c972d)
Location: include/linux/skbuff.h:1889
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
```
```
In net/core/dev.c (ffffffff83226b95)
Location: include/linux/skbuff.h:1889
Inline: True
Inline callers:
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:process_backlog
```
```
In net/core/neighbour.c (ffffffff819f97a2)
Location: include/linux/skbuff.h:1889
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_alloc
```
```
In net/core/netpoll.c (ffffffff83226fda)
Location: include/linux/skbuff.h:1889
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_init
  - net/core/netpoll.c:__netpoll_setup
```
```
In net/core/drop_monitor.c (ffffffff83227173)
Location: include/linux/skbuff.h:1889
Inline: True
Inline callers:
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/gro_cells.c (ffffffff81a4c473)
Location: include/linux/skbuff.h:1889
Inline: True
```
```
In net/core/skmsg.c (ffffffff81a4c902)
Location: include/linux/skbuff.h:1889
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_init
```
```
In net/sched/sch_generic.c (ffffffff81a56791)
Location: include/linux/skbuff.h:1889
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/ipv4/ip_output.c (ffffffff81a943d5)
Location: include/linux/skbuff.h:1889
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_make_skb
```
```
In net/ipv4/tcp_input.c (ffffffff81aa7d04)
Location: include/linux/skbuff.h:1889
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
```
```
In net/ipv4/udp.c (ffffffff81acc6bf)
Location: include/linux/skbuff.h:1889
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_init_sock
  - net/ipv4/udp.c:udp_destruct_sock
  - net/ipv4/udp.c:udp_rmem_release
```
```
In net/ipv4/ipmr.c (ffffffff81afff55)
Location: include/linux/skbuff.h:1889
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b118ed)
Location: include/linux/skbuff.h:1889
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_input.c (ffffffff83228ea2)
Location: include/linux/skbuff.h:1889
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input_init
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (ffffffff81b1e898)
Location: include/linux/skbuff.h:1889
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
```
```
In net/xfrm/espintcp.c (ffffffff81b1f8fd)
Location: include/linux/skbuff.h:1889
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_release
  - net/xfrm/espintcp.c:espintcp_release
  - net/xfrm/espintcp.c:espintcp_init_sk
  - net/xfrm/espintcp.c:espintcp_init_sk
```
```
In net/unix/garbage.c (ffffffff81b25b4b)
Location: include/linux/skbuff.h:1889
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/ip6_output.c (ffffffff81b2d8b4)
Location: include/linux/skbuff.h:1889
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_make_skb
```
```
In net/ipv6/mcast.c (ffffffff81b624a2)
Location: include/linux/skbuff.h:1889
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:mld_query_work
```
```
In net/ipv6/ip6mr.c (ffffffff81b7246f)
Location: include/linux/skbuff.h:1889
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
```
```
In net/wireless/wext-core.c (ffffffff81b8cb5d)
Location: include/linux/skbuff.h:1889
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wext_pernet_init
```
```
In net/mptcp/protocol.c (ffffffff81bb0722)
Location: include/linux/skbuff.h:1889
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_destroy_common
  - net/mptcp/protocol.c:__mptcp_init_sock
  - net/mptcp/protocol.c:__mptcp_init_sock
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:__mptcp_move_skbs
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
In kernel/audit.c (ffffffff832cfc0a)
Location: include/linux/skbuff.h:1918
Inline: True
Inline callers:
  - kernel/audit.c:audit_init
  - kernel/audit.c:audit_init
  - kernel/audit.c:audit_init
```
```
In kernel/auditfilter.c (ffffffff811b2a34)
Location: include/linux/skbuff.h:1918
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In fs/io_uring.c (ffffffff813e4842)
Location: include/linux/skbuff.h:1918
Inline: True
Inline callers:
  - fs/io_uring.c:io_rsrc_file_put
```
```
In drivers/net/tun.c (ffffffff81910843)
Location: include/linux/skbuff.h:1918
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_poll
  - drivers/net/tun.c:tun_napi_poll
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81914997)
Location: include/linux/skbuff.h:1918
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/net/wwan/wwan_core.c (ffffffff8191a597)
Location: include/linux/skbuff.h:1918
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff8191f670)
Location: include/linux/skbuff.h:1918
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/sock.c (ffffffff81a78aad)
Location: include/linux/skbuff.h:1918
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
```
```
In net/core/dev.c (ffffffff83310ea4)
Location: include/linux/skbuff.h:1918
Inline: True
Inline callers:
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:process_backlog
```
```
In net/core/neighbour.c (ffffffff81aac7f2)
Location: include/linux/skbuff.h:1918
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_alloc
```
```
In net/core/netpoll.c (ffffffff83311335)
Location: include/linux/skbuff.h:1918
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_init
  - net/core/netpoll.c:__netpoll_setup
```
```
In net/core/drop_monitor.c (ffffffff833114db)
Location: include/linux/skbuff.h:1918
Inline: True
Inline callers:
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/gro_cells.c (ffffffff81b04930)
Location: include/linux/skbuff.h:1918
Inline: True
```
```
In net/core/skmsg.c (ffffffff81b060a2)
Location: include/linux/skbuff.h:1918
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_init
```
```
In net/sched/sch_generic.c (ffffffff81b0f591)
Location: include/linux/skbuff.h:1918
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/ipv4/ip_output.c (ffffffff81b4f855)
Location: include/linux/skbuff.h:1918
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_make_skb
```
```
In net/ipv4/tcp_input.c (ffffffff81b640fd)
Location: include/linux/skbuff.h:1918
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
```
```
In net/ipv4/udp.c (ffffffff81b8af4f)
Location: include/linux/skbuff.h:1918
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_init_sock
  - net/ipv4/udp.c:udp_destruct_sock
  - net/ipv4/udp.c:udp_rmem_release
```
```
In net/ipv4/ipmr.c (ffffffff81bc1085)
Location: include/linux/skbuff.h:1918
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bd53dd)
Location: include/linux/skbuff.h:1918
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_input.c (ffffffff8331336e)
Location: include/linux/skbuff.h:1918
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input_init
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (ffffffff81be33d8)
Location: include/linux/skbuff.h:1918
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
```
```
In net/xfrm/espintcp.c (ffffffff81be459d)
Location: include/linux/skbuff.h:1918
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_release
  - net/xfrm/espintcp.c:espintcp_release
  - net/xfrm/espintcp.c:espintcp_init_sk
  - net/xfrm/espintcp.c:espintcp_init_sk
```
```
In net/unix/garbage.c (ffffffff81beb277)
Location: include/linux/skbuff.h:1918
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/ip6_output.c (ffffffff81bf3af4)
Location: include/linux/skbuff.h:1918
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_make_skb
```
```
In net/ipv6/mcast.c (ffffffff81c29f32)
Location: include/linux/skbuff.h:1918
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:mld_query_work
```
```
In net/ipv6/ip6mr.c (ffffffff81c3c93f)
Location: include/linux/skbuff.h:1918
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
```
```
In net/wireless/wext-core.c (ffffffff81c58f1d)
Location: include/linux/skbuff.h:1918
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wext_pernet_init
```
```
In net/mptcp/protocol.c (ffffffff81c7e6d9)
Location: include/linux/skbuff.h:1918
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_destroy_common
  - net/mptcp/protocol.c:__mptcp_init_sock
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:__mptcp_move_skbs
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
In kernel/audit.c (ffffffff811dfb6b)
Location: include/linux/skbuff.h:2269
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_start
  - kernel/audit.c:audit_init
  - kernel/audit.c:audit_init
  - kernel/audit.c:audit_init
```
```
In kernel/auditfilter.c (ffffffff811e4d94)
Location: include/linux/skbuff.h:2269
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In io_uring/io_uring.c (ffffffff816c8b39)
Location: include/linux/skbuff.h:2269
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_rsrc_file_put
```
```
In drivers/net/tun.c (ffffffff81a66efd)
Location: include/linux/skbuff.h:2269
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
  - drivers/net/tun.c:tun_napi_poll
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81a69fad)
Location: include/linux/skbuff.h:2269
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/net/wwan/wwan_core.c (ffffffff81a6f90d)
Location: include/linux/skbuff.h:2269
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_create_port
```
```
In drivers/net/xen-netfront.c (ffffffff81a746c8)
Location: include/linux/skbuff.h:2269
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/sock.c (ffffffff81bec51d)
Location: include/linux/skbuff.h:2269
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
```
```
In net/core/dev.c (ffffffff834cac00)
Location: include/linux/skbuff.h:2269
Inline: True
Inline callers:
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:process_backlog
```
```
In net/core/neighbour.c (ffffffff81c2572c)
Location: include/linux/skbuff.h:2269
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_alloc
  - net/core/neighbour.c:pneigh_queue_purge
```
```
In net/core/netpoll.c (ffffffff834cb105)
Location: include/linux/skbuff.h:2269
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_init
  - net/core/netpoll.c:__netpoll_setup
```
```
In net/core/drop_monitor.c (ffffffff834cb2b6)
Location: include/linux/skbuff.h:2269
Inline: True
Inline callers:
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/gro_cells.c (ffffffff81c8a246)
Location: include/linux/skbuff.h:2269
Inline: True
```
```
In net/core/skmsg.c (ffffffff81c8b3f7)
Location: include/linux/skbuff.h:2269
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_init
```
```
In net/sched/sch_generic.c (ffffffff81c96764)
Location: include/linux/skbuff.h:2269
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/ipv4/ip_output.c (ffffffff81cdd25c)
Location: include/linux/skbuff.h:2269
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_make_skb
```
```
In net/ipv4/tcp_input.c (ffffffff81cf2f79)
Location: include/linux/skbuff.h:2269
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
```
```
In net/ipv4/udp.c (ffffffff81d1ad32)
Location: include/linux/skbuff.h:2269
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_init_sock
  - net/ipv4/udp.c:udp_destruct_sock
  - net/ipv4/udp.c:udp_rmem_release
```
```
In net/ipv4/ipmr.c (ffffffff81d55a18)
Location: include/linux/skbuff.h:2269
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d6bbf7)
Location: include/linux/skbuff.h:2269
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_input.c (ffffffff834cd680)
Location: include/linux/skbuff.h:2269
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input_init
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (ffffffff81d7a607)
Location: include/linux/skbuff.h:2269
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
```
```
In net/xfrm/espintcp.c (ffffffff81d7ba0a)
Location: include/linux/skbuff.h:2269
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_release
  - net/xfrm/espintcp.c:espintcp_release
  - net/xfrm/espintcp.c:espintcp_init_sk
  - net/xfrm/espintcp.c:espintcp_init_sk
```
```
In net/unix/garbage.c (ffffffff81d83663)
Location: include/linux/skbuff.h:2269
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/ip6_output.c (ffffffff81d8c742)
Location: include/linux/skbuff.h:2269
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_make_skb
```
```
In net/ipv6/mcast.c (ffffffff81dc7392)
Location: include/linux/skbuff.h:2269
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:mld_query_work
```
```
In net/ipv6/ip6mr.c (ffffffff81ddaecf)
Location: include/linux/skbuff.h:2269
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
```
```
In net/wireless/wext-core.c (ffffffff81dfa5ed)
Location: include/linux/skbuff.h:2269
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wext_pernet_init
```
```
In net/mptcp/protocol.c (ffffffff81e23a73)
Location: include/linux/skbuff.h:2269
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_destroy_common
  - net/mptcp/protocol.c:__mptcp_init_sock
  - net/mptcp/protocol.c:__mptcp_move_skbs
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
In kernel/audit.c (ffffffff8122587b)
Location: include/linux/skbuff.h:2127
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_start
  - kernel/audit.c:audit_init
  - kernel/audit.c:audit_init
  - kernel/audit.c:audit_init
```
```
In kernel/auditfilter.c (ffffffff8122adb4)
Location: include/linux/skbuff.h:2127
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In io_uring/rsrc.c (ffffffff817a0319)
Location: include/linux/skbuff.h:2127
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_rsrc_file_put
```
```
In drivers/net/tun.c (ffffffff81bf252d)
Location: include/linux/skbuff.h:2127
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
  - drivers/net/tun.c:tun_napi_poll
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81bfcbad)
Location: include/linux/skbuff.h:2127
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/net/wwan/wwan_core.c (ffffffff81c0274d)
Location: include/linux/skbuff.h:2127
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_create_port
```
```
In drivers/net/xen-netfront.c (ffffffff81c08928)
Location: include/linux/skbuff.h:2127
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/sock.c (ffffffff81d9a39d)
Location: include/linux/skbuff.h:2127
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data_uid
  - net/core/sock.c:sock_init_data_uid
  - net/core/sock.c:sock_init_data_uid
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
```
```
In net/core/dev.c (ffffffff83f0caaf)
Location: include/linux/skbuff.h:2127
Inline: True
Inline callers:
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:process_backlog
```
```
In net/core/neighbour.c (ffffffff81dd8ac0)
Location: include/linux/skbuff.h:2127
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_alloc
  - net/core/neighbour.c:pneigh_queue_purge
```
```
In net/core/netpoll.c (ffffffff83f0d395)
Location: include/linux/skbuff.h:2127
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_init
  - net/core/netpoll.c:__netpoll_setup
```
```
In net/core/drop_monitor.c (ffffffff83f0d561)
Location: include/linux/skbuff.h:2127
Inline: True
Inline callers:
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/gro_cells.c (ffffffff81e44fd2)
Location: include/linux/skbuff.h:2127
Inline: True
```
```
In net/core/skmsg.c (ffffffff81e47802)
Location: include/linux/skbuff.h:2127
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_init
```
```
In net/sched/sch_generic.c (ffffffff81e52394)
Location: include/linux/skbuff.h:2127
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/ipv4/ip_output.c (ffffffff81e9dd0c)
Location: include/linux/skbuff.h:2127
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_make_skb
```
```
In net/ipv4/tcp_input.c (ffffffff81eb75a9)
Location: include/linux/skbuff.h:2127
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
```
```
In net/ipv4/udp.c (ffffffff81ee22d2)
Location: include/linux/skbuff.h:2127
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_init_sock
  - net/ipv4/udp.c:udp_destruct_common
  - net/ipv4/udp.c:udp_rmem_release
```
```
In net/ipv4/ipmr.c (ffffffff81f1fd78)
Location: include/linux/skbuff.h:2127
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f36f37)
Location: include/linux/skbuff.h:2127
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_input.c (ffffffff83f10473)
Location: include/linux/skbuff.h:2127
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input_init
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (ffffffff81f47517)
Location: include/linux/skbuff.h:2127
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
```
```
In net/xfrm/espintcp.c (ffffffff81f48aba)
Location: include/linux/skbuff.h:2127
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_release
  - net/xfrm/espintcp.c:espintcp_release
  - net/xfrm/espintcp.c:espintcp_init_sk
  - net/xfrm/espintcp.c:espintcp_init_sk
```
```
In net/unix/garbage.c (ffffffff81f50d2e)
Location: include/linux/skbuff.h:2127
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/ip6_output.c (ffffffff81f5a732)
Location: include/linux/skbuff.h:2127
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_make_skb
```
```
In net/ipv6/udp.c (ffffffff81f8747c)
Location: include/linux/skbuff.h:2127
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_init_sock
```
```
In net/ipv6/mcast.c (ffffffff81f98062)
Location: include/linux/skbuff.h:2127
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:mld_query_work
```
```
In net/ipv6/ip6mr.c (ffffffff81facbdf)
Location: include/linux/skbuff.h:2127
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
```
```
In net/wireless/wext-core.c (ffffffff81fced1d)
Location: include/linux/skbuff.h:2127
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wext_pernet_init
```
```
In net/mptcp/protocol.c (ffffffff81ffb1b3)
Location: include/linux/skbuff.h:2127
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_destroy_common
  - net/mptcp/protocol.c:__mptcp_init_sock
  - net/mptcp/protocol.c:__mptcp_move_skbs
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
In kernel/audit.c (ffffffff8123be6b)
Location: include/linux/skbuff.h:2163
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_start
  - kernel/audit.c:audit_init
  - kernel/audit.c:audit_init
  - kernel/audit.c:audit_init
```
```
In kernel/auditfilter.c (ffffffff812413b4)
Location: include/linux/skbuff.h:2163
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In io_uring/rsrc.c (ffffffff817e1305)
Location: include/linux/skbuff.h:2163
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_rsrc_file_scm_put
```
```
In drivers/net/tun.c (ffffffff81c4b1c1)
Location: include/linux/skbuff.h:2163
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
  - drivers/net/tun.c:tun_napi_poll
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81c6222d)
Location: include/linux/skbuff.h:2163
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/net/wwan/wwan_core.c (ffffffff81c67cd6)
Location: include/linux/skbuff.h:2163
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_create_port
```
```
In drivers/net/xen-netfront.c (ffffffff81c6e088)
Location: include/linux/skbuff.h:2163
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/sock.c (ffffffff81e08bfd)
Location: include/linux/skbuff.h:2163
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data_uid
  - net/core/sock.c:sock_init_data_uid
  - net/core/sock.c:sock_init_data_uid
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
```
```
In net/core/dev.c (ffffffff83732e4f)
Location: include/linux/skbuff.h:2163
Inline: True
Inline callers:
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:process_backlog
```
```
In net/core/neighbour.c (ffffffff81e49820)
Location: include/linux/skbuff.h:2163
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_alloc
  - net/core/neighbour.c:pneigh_queue_purge
```
```
In net/core/netpoll.c (ffffffff837339a5)
Location: include/linux/skbuff.h:2163
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_init
  - net/core/netpoll.c:__netpoll_setup
```
```
In net/core/drop_monitor.c (ffffffff83733b71)
Location: include/linux/skbuff.h:2163
Inline: True
Inline callers:
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/gro_cells.c (ffffffff81e9fdd2)
Location: include/linux/skbuff.h:2163
Inline: True
```
```
In net/core/skmsg.c (ffffffff81ea1c92)
Location: include/linux/skbuff.h:2163
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_init
```
```
In net/sched/sch_generic.c (ffffffff81eadc04)
Location: include/linux/skbuff.h:2163
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/ipv4/ip_output.c (ffffffff81efc4cc)
Location: include/linux/skbuff.h:2163
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_make_skb
```
```
In net/ipv4/tcp_input.c (ffffffff81f15c88)
Location: include/linux/skbuff.h:2163
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
```
```
In net/ipv4/udp.c (ffffffff81f41dd2)
Location: include/linux/skbuff.h:2163
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_init_sock
  - net/ipv4/udp.c:udp_destruct_common
  - net/ipv4/udp.c:udp_rmem_release
```
```
In net/ipv4/ipmr.c (ffffffff81f7f878)
Location: include/linux/skbuff.h:2163
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f968bd)
Location: include/linux/skbuff.h:2163
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_input.c (ffffffff83736aa3)
Location: include/linux/skbuff.h:2163
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input_init
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (ffffffff81fa6fe7)
Location: include/linux/skbuff.h:2163
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
```
```
In net/xfrm/espintcp.c (ffffffff81fa892a)
Location: include/linux/skbuff.h:2163
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_release
  - net/xfrm/espintcp.c:espintcp_release
  - net/xfrm/espintcp.c:espintcp_init_sk
  - net/xfrm/espintcp.c:espintcp_init_sk
```
```
In net/unix/garbage.c (ffffffff81fb068f)
Location: include/linux/skbuff.h:2163
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/ip6_output.c (ffffffff81fba48f)
Location: include/linux/skbuff.h:2163
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_make_skb
```
```
In net/ipv6/udp.c (ffffffff81fe77fc)
Location: include/linux/skbuff.h:2163
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_init_sock
```
```
In net/ipv6/mcast.c (ffffffff81ff8a52)
Location: include/linux/skbuff.h:2163
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:mld_query_work
```
```
In net/ipv6/ip6mr.c (ffffffff8200d20f)
Location: include/linux/skbuff.h:2163
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
```
```
In net/wireless/wext-core.c (ffffffff8204a67d)
Location: include/linux/skbuff.h:2163
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wext_pernet_init
```
```
In net/mptcp/protocol.c (ffffffff82077533)
Location: include/linux/skbuff.h:2163
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_destroy_common
  - net/mptcp/protocol.c:__mptcp_init_sock
  - net/mptcp/protocol.c:__mptcp_move_skbs
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
In kernel/audit.c (ffffffff81255d3b)
Location: include/linux/skbuff.h:2170
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_start
  - kernel/audit.c:audit_init
  - kernel/audit.c:audit_init
  - kernel/audit.c:audit_init
```
```
In kernel/auditfilter.c (ffffffff8125b1e3)
Location: include/linux/skbuff.h:2170
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In drivers/net/tun.c (ffffffff81cf8dc5)
Location: include/linux/skbuff.h:2170
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_rx_batched
  - drivers/net/tun.c:tun_rx_batched
  - drivers/net/tun.c:tun_napi_poll
  - drivers/net/tun.c:tun_napi_poll
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81d18c5c)
Location: include/linux/skbuff.h:2170
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/net/xen-netfront.c (ffffffff81d22978)
Location: include/linux/skbuff.h:2170
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/sock.c (ffffffff81ec566d)
Location: include/linux/skbuff.h:2170
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data_uid
  - net/core/sock.c:sock_init_data_uid
  - net/core/sock.c:sock_init_data_uid
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
```
```
In net/core/skbuff.c (ffffffff81ed6edc)
Location: include/linux/skbuff.h:2170
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_errqueue_purge
  - net/core/skbuff.c:skb_queue_purge_reason
  - net/core/skbuff.c:skb_queue_purge_reason
```
```
In net/core/dev.c (ffffffff8396732f)
Location: include/linux/skbuff.h:2170
Inline: True
Inline callers:
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:process_backlog
```
```
In net/core/neighbour.c (ffffffff81f0853f)
Location: include/linux/skbuff.h:2170
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_alloc
  - net/core/neighbour.c:pneigh_queue_purge
```
```
In net/core/netpoll.c (ffffffff83967ee5)
Location: include/linux/skbuff.h:2170
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_init
  - net/core/netpoll.c:__netpoll_setup
```
```
In net/core/drop_monitor.c (ffffffff839680b1)
Location: include/linux/skbuff.h:2170
Inline: True
Inline callers:
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/gro_cells.c (ffffffff81f62562)
Location: include/linux/skbuff.h:2170
Inline: True
```
```
In net/core/skmsg.c (ffffffff81f65f45)
Location: include/linux/skbuff.h:2170
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_init
```
```
In net/sched/sch_generic.c (ffffffff81f70694)
Location: include/linux/skbuff.h:2170
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/ipv4/ip_output.c (ffffffff81fc040c)
Location: include/linux/skbuff.h:2170
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_make_skb
```
```
In net/ipv4/tcp_input.c (ffffffff81fda05c)
Location: include/linux/skbuff.h:2170
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
```
```
In net/ipv4/udp.c (ffffffff82007c62)
Location: include/linux/skbuff.h:2170
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_init_sock
  - net/ipv4/udp.c:udp_destruct_common
  - net/ipv4/udp.c:udp_rmem_release
```
```
In net/ipv4/ipmr.c (ffffffff82045ef8)
Location: include/linux/skbuff.h:2170
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
```
```
In net/xfrm/xfrm_policy.c (ffffffff82063cbc)
Location: include/linux/skbuff.h:2170
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_input.c (ffffffff8396b113)
Location: include/linux/skbuff.h:2170
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input_init
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (ffffffff82074297)
Location: include/linux/skbuff.h:2170
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
```
```
In net/xfrm/espintcp.c (ffffffff82075c1a)
Location: include/linux/skbuff.h:2170
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_release
  - net/xfrm/espintcp.c:espintcp_release
  - net/xfrm/espintcp.c:espintcp_init_sk
  - net/xfrm/espintcp.c:espintcp_init_sk
```
```
In net/unix/garbage.c (ffffffff8207dcfe)
Location: include/linux/skbuff.h:2170
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/ip6_output.c (ffffffff820878d9)
Location: include/linux/skbuff.h:2170
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_make_skb
```
```
In net/ipv6/udp.c (ffffffff820b565c)
Location: include/linux/skbuff.h:2170
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_init_sock
```
```
In net/ipv6/mcast.c (ffffffff820c66c2)
Location: include/linux/skbuff.h:2170
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:ipv6_mc_init_dev
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:mld_query_work
```
```
In net/ipv6/ip6mr.c (ffffffff820dc1df)
Location: include/linux/skbuff.h:2170
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
```
```
In net/wireless/wext-core.c (ffffffff8211caed)
Location: include/linux/skbuff.h:2170
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wext_pernet_init
```
```
In net/mptcp/protocol.c (ffffffff8214c563)
Location: include/linux/skbuff.h:2170
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_destroy_common
  - net/mptcp/protocol.c:__mptcp_init_sock
  - net/mptcp/protocol.c:__mptcp_move_skbs
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
In kernel/audit.c (ffff80001144b764)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - kernel/audit.c:audit_init
  - kernel/audit.c:audit_init
  - kernel/audit.c:audit_init
```
```
In kernel/auditfilter.c (ffff8000101edee0)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In drivers/net/tun.c (ffff8000109e1038)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
  - drivers/net/tun.c:tun_napi_poll
```
```
In drivers/net/ppp/ppp_generic.c (ffff800010a00358)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/net/xen-netfront.c (ffff800010a08688)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/sock.c (ffff800010ba9958)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
```
```
In net/core/dev.c (ffff8000114ae888)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:process_backlog
```
```
In net/core/neighbour.c (ffff800010be25cc)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:___neigh_create
```
```
In net/core/skmsg.c (ffff800010c0f7fc)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_init
```
```
In net/core/netpoll.c (ffff8000114aed40)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_init
  - net/core/netpoll.c:__netpoll_setup
```
```
In net/core/drop_monitor.c (ffff8000114b1478)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/gro_cells.c (ffff800010c30d38)
Location: include/linux/skbuff.h:1829
Inline: True
```
```
In net/sched/sch_generic.c (ffff800010c399bc)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/ipv4/ip_output.c (ffff800010c65830)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_make_skb
```
```
In net/ipv4/tcp_input.c (ffff800010c7e8fc)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
```
```
In net/ipv4/udp.c (ffff800010c99e38)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_init_sock
  - net/ipv4/udp.c:udp_destruct_sock
  - net/ipv4/udp.c:udp_rmem_release
```
```
In net/ipv4/ipmr.c (ffff800010ccbae0)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
```
```
In net/xfrm/xfrm_policy.c (ffff800010ce0afc)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_input.c (ffff8000114b3a14)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input_init
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (ffff800010cee704)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
```
```
In net/unix/garbage.c (ffff800010cf4d48)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/ip6_output.c (ffff800010cfca0c)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_make_skb
```
```
In net/ipv6/ip6mr.c (ffff800010d447dc)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
```
```
In net/wireless/wext-core.c (ffff800010d60614)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wext_pernet_init
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
In kernel/audit.c (c1525c90)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - kernel/audit.c:audit_init
  - kernel/audit.c:audit_init
  - kernel/audit.c:audit_init
```
```
In kernel/auditfilter.c (c042e00c)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In drivers/net/tun.c (c0ac4e24)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
  - drivers/net/tun.c:tun_napi_poll
```
```
In drivers/net/ethernet/ti/cpts.c (c0ad0edc)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/cpts.c:cpts_register
```
```
In drivers/net/ppp/ppp_generic.c (c0add754)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In net/core/sock.c (c0cc7f00)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
```
```
In net/core/dev.c (c15b3510)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:process_backlog
```
```
In net/core/neighbour.c (c0d01090)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:___neigh_create
```
```
In net/core/skmsg.c (c0d264e0)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_init
```
```
In net/core/netpoll.c (c15b3a0c)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_init
  - net/core/netpoll.c:__netpoll_setup
```
```
In net/core/drop_monitor.c (c15b66dc)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/gro_cells.c (c0d47bc0)
Location: include/linux/skbuff.h:1829
Inline: True
```
```
In net/sched/sch_generic.c (c0d4bcfc)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/ipv4/ip_output.c (c0d75484)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_make_skb
```
```
In net/ipv4/tcp_input.c (c0d8d8d8)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
```
```
In net/ipv4/udp.c (c0daa438)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_init_sock
  - net/ipv4/udp.c:udp_destruct_sock
  - net/ipv4/udp.c:udp_rmem_release
```
```
In net/ipv4/ipmr.c (c0dd6898)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
```
```
In net/xfrm/xfrm_policy.c (c0de9e94)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_input.c (c15b8cf4)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input_init
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (c0df654c)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
```
```
In net/unix/garbage.c (c0dfb9c0)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/ip6_output.c (c0e03ecc)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_make_skb
```
```
In net/ipv6/ip6mr.c (c0e460a0)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
```
```
In net/wireless/wext-core.c (c0e60154)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wext_pernet_init
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
In kernel/audit.c (c00000000137128c)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - kernel/audit.c:audit_init
  - kernel/audit.c:audit_init
  - kernel/audit.c:audit_init
```
```
In kernel/auditfilter.c (c0000000002609d0)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In drivers/net/tun.c (c000000000aa217c)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
  - drivers/net/tun.c:tun_napi_poll
```
```
In drivers/net/ppp/ppp_generic.c (c000000000aa8110)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In net/core/sock.c (c000000000c7ee4c)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
```
```
In net/core/dev.c (c0000000013be868)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:process_backlog
```
```
In net/core/neighbour.c (c000000000cca1cc)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:___neigh_create
```
```
In net/core/skmsg.c (c000000000cfa610)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_init
```
```
In net/core/netpoll.c (c0000000013bee4c)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_init
  - net/core/netpoll.c:__netpoll_setup
```
```
In net/core/drop_monitor.c (c0000000013c1f6c)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/gro_cells.c (c000000000d29c14)
Location: include/linux/skbuff.h:1829
Inline: True
```
```
In net/sched/sch_generic.c (c000000000d327f4)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/ipv4/ip_output.c (c000000000d69ee8)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_make_skb
```
```
In net/ipv4/tcp_input.c (c000000000d88c80)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
```
```
In net/ipv4/udp.c (c000000000dab4a4)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_init_sock
  - net/ipv4/udp.c:udp_destruct_sock
  - net/ipv4/udp.c:udp_rmem_release
```
```
In net/ipv4/ipmr.c (c000000000dec094)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
```
```
In net/xfrm/xfrm_policy.c (c000000000e02e6c)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_input.c (c0000000013c5150)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input_init
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (c000000000e13374)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
```
```
In net/unix/garbage.c (c000000000e1ae00)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/ip6_output.c (c000000000e246e4)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_make_skb
```
```
In net/ipv6/ip6mr.c (c000000000e790b8)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
```
```
In net/wireless/wext-core.c (c000000000e9b79c)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wext_pernet_init
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
In kernel/audit.c (ffffffe00000caa6)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - kernel/audit.c:audit_init
  - kernel/audit.c:audit_init
  - kernel/audit.c:audit_init
```
```
In kernel/auditfilter.c (ffffffe000162336)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In drivers/net/tun.c (ffffffe00062aa76)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
  - drivers/net/tun.c:tun_napi_poll
```
```
In drivers/net/ppp/ppp_generic.c (ffffffe00062cb18)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In net/core/sock.c (ffffffe00073ce94)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
```
```
In net/core/dev.c (ffffffe00003db0a)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:process_backlog
```
```
In net/core/neighbour.c (ffffffe000769d06)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:___neigh_create
```
```
In net/core/skmsg.c (ffffffe00078b380)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_init
```
```
In net/core/netpoll.c (ffffffe00003df9e)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_init
  - net/core/netpoll.c:__netpoll_setup
```
```
In net/core/drop_monitor.c (ffffffe0000401fa)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/gro_cells.c (ffffffe0007a6c98)
Location: include/linux/skbuff.h:1829
Inline: True
```
```
In net/sched/sch_generic.c (ffffffe0007aad58)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/ipv4/ip_output.c (ffffffe0007ccfe4)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_make_skb
```
```
In net/ipv4/tcp_input.c (ffffffe0007e0be8)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
```
```
In net/ipv4/udp.c (ffffffe0007f8fc8)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_init_sock
  - net/ipv4/udp.c:udp_destruct_sock
  - net/ipv4/udp.c:udp_rmem_release
```
```
In net/ipv4/ipmr.c (ffffffe00082117c)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
```
```
In net/xfrm/xfrm_policy.c (ffffffe00082f7d2)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_input.c (ffffffe0000427f8)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input_init
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (ffffffe00083b888)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
```
```
In net/unix/garbage.c (ffffffe000840a0a)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/ip6_output.c (ffffffe00084720e)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_make_skb
```
```
In net/ipv6/ip6mr.c (ffffffe00087eeee)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
```
```
In net/wireless/wext-core.c (ffffffe000895a2c)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wext_pernet_init
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
In kernel/audit.c (ffffffff828bc030)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - kernel/audit.c:audit_init
  - kernel/audit.c:audit_init
  - kernel/audit.c:audit_init
```
```
In kernel/auditfilter.c (ffffffff811713cb)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In drivers/net/tun.c (ffffffff8178a6b0)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
  - drivers/net/tun.c:tun_napi_poll
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8178c7ed)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/net/xen-netfront.c (ffffffff817929f3)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/sock.c (ffffffff818b1dbd)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
```
```
In net/core/dev.c (ffffffff82902b74)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:process_backlog
```
```
In net/core/neighbour.c (ffffffff818e6b3b)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:___neigh_create
```
```
In net/core/skmsg.c (ffffffff81908d34)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_init
```
```
In net/core/netpoll.c (ffffffff82902f9d)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_init
  - net/core/netpoll.c:__netpoll_setup
```
```
In net/core/drop_monitor.c (ffffffff829057fc)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/gro_cells.c (ffffffff81928a15)
Location: include/linux/skbuff.h:1829
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff8192dffc)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/ipv4/ip_output.c (ffffffff81954ee5)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_make_skb
```
```
In net/ipv4/tcp_input.c (ffffffff8196bae7)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
```
```
In net/ipv4/udp.c (ffffffff8198687a)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_init_sock
  - net/ipv4/udp.c:udp_destruct_sock
  - net/ipv4/udp.c:udp_rmem_release
```
```
In net/ipv4/ipmr.c (ffffffff819b1b95)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
```
```
In net/xfrm/xfrm_policy.c (ffffffff819c300c)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_input.c (ffffffff829078d2)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input_init
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (ffffffff819cebe8)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
```
```
In net/unix/garbage.c (ffffffff819d3e00)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/ip6_output.c (ffffffff819daeb6)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_make_skb
```
```
In net/ipv6/ip6mr.c (ffffffff81a197bf)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
```
```
In net/wireless/wext-core.c (ffffffff81a31f8d)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wext_pernet_init
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
In kernel/audit.c (ffffffff828b46c3)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - kernel/audit.c:audit_init
  - kernel/audit.c:audit_init
  - kernel/audit.c:audit_init
```
```
In kernel/auditfilter.c (ffffffff8116456b)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In drivers/net/tun.c (ffffffff8176a000)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
  - drivers/net/tun.c:tun_napi_poll
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817755bd)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In net/core/sock.c (ffffffff8186bd0d)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
```
```
In net/core/dev.c (ffffffff828faec2)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:process_backlog
```
```
In net/core/neighbour.c (ffffffff818a097b)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:___neigh_create
```
```
In net/core/skmsg.c (ffffffff818c2b44)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_init
```
```
In net/core/netpoll.c (ffffffff828fb2eb)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_init
  - net/core/netpoll.c:__netpoll_setup
```
```
In net/core/drop_monitor.c (ffffffff828fdb4a)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/gro_cells.c (ffffffff818e27c5)
Location: include/linux/skbuff.h:1829
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff818e7afc)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/ipv4/ip_output.c (ffffffff8190e9d5)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_make_skb
```
```
In net/ipv4/tcp_input.c (ffffffff819255d7)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
```
```
In net/ipv4/udp.c (ffffffff8194033a)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_init_sock
  - net/ipv4/udp.c:udp_destruct_sock
  - net/ipv4/udp.c:udp_rmem_release
```
```
In net/ipv4/ipmr.c (ffffffff8196e1c5)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197fdfc)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_input.c (ffffffff828ffc20)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input_init
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (ffffffff8198b9a8)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
```
```
In net/unix/garbage.c (ffffffff81990bc0)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/ip6_output.c (ffffffff81997c76)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_make_skb
```
```
In net/ipv6/ip6mr.c (ffffffff819d657f)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
```
```
In net/wireless/wext-core.c (ffffffff819ef17d)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wext_pernet_init
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
In kernel/audit.c (ffffffff828cedb3)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - kernel/audit.c:audit_init
  - kernel/audit.c:audit_init
  - kernel/audit.c:audit_init
```
```
In kernel/auditfilter.c (ffffffff8116f19b)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In drivers/net/tun.c (ffffffff817baa50)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
  - drivers/net/tun.c:tun_napi_poll
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817bcb8d)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/net/xen-netfront.c (ffffffff817c2c53)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/sock.c (ffffffff81902dbd)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
```
```
In net/core/dev.c (ffffffff8291817b)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:process_backlog
```
```
In net/core/neighbour.c (ffffffff81937b6b)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:___neigh_create
```
```
In net/core/skmsg.c (ffffffff81959d64)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_init
```
```
In net/core/netpoll.c (ffffffff829185a4)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_init
  - net/core/netpoll.c:__netpoll_setup
```
```
In net/core/drop_monitor.c (ffffffff8291ae03)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/gro_cells.c (ffffffff81979ba5)
Location: include/linux/skbuff.h:1829
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff8197f18c)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/ipv4/ip_output.c (ffffffff819bf6b5)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_make_skb
```
```
In net/ipv4/tcp_input.c (ffffffff819d62b7)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
```
```
In net/ipv4/udp.c (ffffffff819f104a)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_init_sock
  - net/ipv4/udp.c:udp_destruct_sock
  - net/ipv4/udp.c:udp_rmem_release
```
```
In net/ipv4/ipmr.c (ffffffff81a1c435)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a2da8c)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_input.c (ffffffff8291d1cc)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input_init
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (ffffffff81a39668)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
```
```
In net/unix/garbage.c (ffffffff81a3e880)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/ip6_output.c (ffffffff81a45936)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_make_skb
```
```
In net/ipv6/ip6mr.c (ffffffff81a8423f)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
```
```
In net/wireless/wext-core.c (ffffffff81a9db3d)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wext_pernet_init
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
In kernel/audit.c (ffffffff828d41ad)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - kernel/audit.c:audit_init
  - kernel/audit.c:audit_init
  - kernel/audit.c:audit_init
```
```
In kernel/auditfilter.c (ffffffff8117c98b)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
```
```
In drivers/net/tun.c (ffffffff817d2e9f)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
  - drivers/net/tun.c:tun_napi_poll
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817d7798)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/net/xen-netfront.c (ffffffff817dcf13)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_poll
```
```
In net/core/sock.c (ffffffff81923d2d)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
```
```
In net/core/dev.c (ffffffff8291eed2)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:process_backlog
```
```
In net/core/neighbour.c (ffffffff8195933b)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:___neigh_create
```
```
In net/core/skmsg.c (ffffffff8197bf84)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_init
```
```
In net/core/netpoll.c (ffffffff8291f2fb)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_init
  - net/core/netpoll.c:__netpoll_setup
```
```
In net/core/drop_monitor.c (ffffffff82921b5a)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/gro_cells.c (ffffffff8199c0d5)
Location: include/linux/skbuff.h:1829
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff819a16ec)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/ipv4/ip_output.c (ffffffff819c9035)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_make_skb
```
```
In net/ipv4/tcp_input.c (ffffffff819dfed7)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
```
```
In net/ipv4/udp.c (ffffffff819f9432)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_init_sock
  - net/ipv4/udp.c:udp_destruct_sock
  - net/ipv4/udp.c:udp_rmem_release
```
```
In net/ipv4/ipmr.c (ffffffff81a27385)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_unresolved
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a3924a)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_input.c (ffffffff82923c30)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input_init
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
  - net/xfrm/xfrm_input.c:xfrm_trans_reinject
```
```
In net/xfrm/xfrm_device.c (ffffffff81a45098)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
  - net/xfrm/xfrm_device.c:xfrm_dev_backlog
```
```
In net/unix/garbage.c (ffffffff81a4a405)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
```
```
In net/ipv6/ip6_output.c (ffffffff81a51606)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_make_skb
```
```
In net/ipv6/ip6mr.c (ffffffff81a90b6f)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_unresolved
```
```
In net/wireless/wext-core.c (ffffffff81aa9d3d)
Location: include/linux/skbuff.h:1829
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wext_pernet_init
```
</details>
</li>
</ul>

## Differences
