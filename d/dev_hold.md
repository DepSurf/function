# Function: <code>dev_hold</code>

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
In drivers/net/tun.c (ffffffff815eda52)
Location: include/linux/netdevice.h:3123
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
  - drivers/net/tun.c:tun_chr_show_fdinfo
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_chr_read_iter
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_chr_write_iter
  - drivers/net/tun.c:__tun_chr_ioctl
```
```
In net/core/dev.c (ffffffff817136c8)
Location: include/linux/netdevice.h:3123
Inline: True
Inline callers:
  - net/core/dev.c:dev_get_by_index
  - net/core/dev.c:dev_getfirstbyhwtype
  - net/core/dev.c:dev_get_by_name
  - net/core/dev.c:register_netdevice
```
```
In net/core/ethtool.c (ffffffff8172147c)
Location: include/linux/netdevice.h:3123
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
```
```
In net/core/dst.c (ffffffff81723742)
Location: include/linux/netdevice.h:3123
Inline: True
Inline callers:
  - net/core/dst.c:dst_ifdown
  - net/core/dst.c:dst_init
```
```
In net/core/neighbour.c (ffffffff81724b37)
Location: include/linux/netdevice.h:3123
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_lookup
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:__neigh_create
```
```
In net/core/link_watch.c (ffffffff8173075b)
Location: include/linux/netdevice.h:3123
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_fire_event
```
```
In net/core/net-sysfs.c (ffffffff817373a0)
Location: include/linux/netdevice.h:3123
Inline: True
Inline callers:
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
```
```
In net/core/netpoll.c (ffffffff8173866d)
Location: include/linux/netdevice.h:3123
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
```
```
In net/sched/sch_generic.c (ffffffff817411a9)
Location: include/linux/netdevice.h:3123
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:__netdev_watchdog_up
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/netlink/af_netlink.c (ffffffff8174b2fc)
Location: include/linux/netdevice.h:3123
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_deliver_tap
```
```
In net/netfilter/nf_queue.c (ffffffff81752649)
Location: include/linux/netdevice.h:3123
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
```
```
In net/ipv4/route.c (ffffffff81757ab0)
Location: include/linux/netdevice.h:3123
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_flush_dev
  - net/ipv4/route.c:ipv4_blackhole_route
```
```
In net/ipv4/devinet.c (ffffffff8178f6b8)
Location: include/linux/netdevice.h:3123
Inline: True
Inline callers:
  - net/ipv4/devinet.c:__ip_dev_find
  - net/ipv4/devinet.c:inetdev_init
```
```
In net/ipv4/fib_semantics.c (ffffffff8179d7e3)
Location: include/linux/netdevice.h:3123
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/ipmr.c (ffffffff817a7e13)
Location: include/linux/netdevice.h:3123
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
```
```
In net/ipv4/xfrm4_policy.c (ffffffff817af254)
Location: include/linux/netdevice.h:3123
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_fill_dst
```
```
In net/xfrm/xfrm_policy.c (ffffffff817b0f07)
Location: include/linux/netdevice.h:3123
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_ifdown
```
```
In net/ipv6/addrconf.c (ffffffff817cbcc0)
Location: include/linux/netdevice.h:3123
Inline: True
```
```
In net/ipv6/route.c (ffffffff817d57dd)
Location: include/linux/netdevice.h:3123
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:rt6_ifdown
```
```
In net/ipv6/ip6mr.c (ffffffff817f8df9)
Location: include/linux/netdevice.h:3123
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
```
In net/ipv6/xfrm6_policy.c (ffffffff817fbd48)
Location: include/linux/netdevice.h:3123
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
```
```
In net/packet/af_packet.c (ffffffff81804d91)
Location: include/linux/netdevice.h:3123
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg
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
In drivers/net/tun.c (ffffffff8164ca5f)
Location: include/linux/netdevice.h:3351
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_show_fdinfo
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:tun_peek_len
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_chr_read_iter
  - drivers/net/tun.c:tun_chr_write_iter
  - drivers/net/tun.c:tun_chr_poll
```
```
In net/core/dev.c (ffffffff81787485)
Location: include/linux/netdevice.h:3351
Inline: True
Inline callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:dev_getfirstbyhwtype
  - net/core/dev.c:dev_get_by_index
  - net/core/dev.c:dev_get_by_name
```
```
In net/core/ethtool.c (ffffffff8178a838)
Location: include/linux/netdevice.h:3351
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
```
```
In net/core/dst.c (ffffffff8178d1a2)
Location: include/linux/netdevice.h:3351
Inline: True
Inline callers:
  - net/core/dst.c:dst_ifdown
  - net/core/dst.c:dst_init
```
```
In net/core/neighbour.c (ffffffff8178f1e9)
Location: include/linux/netdevice.h:3351
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:pneigh_lookup
  - net/core/neighbour.c:__neigh_create
```
```
In net/core/link_watch.c (ffffffff8179aecb)
Location: include/linux/netdevice.h:3351
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_fire_event
```
```
In net/core/net-sysfs.c (ffffffff817a3766)
Location: include/linux/netdevice.h:3351
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
```
In net/core/netpoll.c (ffffffff817a495d)
Location: include/linux/netdevice.h:3351
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
```
```
In net/sched/sch_generic.c (ffffffff817ae7b9)
Location: include/linux/netdevice.h:3351
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_generic.c:__netdev_watchdog_up
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/netlink/af_netlink.c (ffffffff817b7e31)
Location: include/linux/netdevice.h:3351
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_deliver_tap
```
```
In net/netfilter/nf_queue.c (ffffffff817be7bc)
Location: include/linux/netdevice.h:3351
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
```
```
In net/ipv4/route.c (ffffffff817c3df6)
Location: include/linux/netdevice.h:3351
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/route.c:rt_flush_dev
```
```
In net/ipv4/devinet.c (ffffffff817ffac9)
Location: include/linux/netdevice.h:3351
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:__ip_dev_find
```
```
In net/ipv4/fib_semantics.c (ffffffff8180b054)
Location: include/linux/netdevice.h:3351
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/ipmr.c (ffffffff81890726)
Location: include/linux/netdevice.h:3351
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
```
```
In net/ipv4/xfrm4_policy.c (ffffffff8181c154)
Location: include/linux/netdevice.h:3351
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_fill_dst
```
```
In net/xfrm/xfrm_policy.c (ffffffff8181de57)
Location: include/linux/netdevice.h:3351
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_ifdown
```
```
In net/xfrm/xfrm_input.c (ffffffff81828bbf)
Location: include/linux/netdevice.h:3351
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/ipv6/addrconf.c (ffffffff8183a30d)
Location: include/linux/netdevice.h:3351
Inline: True
```
```
In net/ipv6/route.c (ffffffff81846fde)
Location: include/linux/netdevice.h:3351
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_ifdown
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
```
```
In net/ipv6/ip6mr.c (ffffffff8186a1a4)
Location: include/linux/netdevice.h:3351
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_policy.c (ffffffff8186b618)
Location: include/linux/netdevice.h:3351
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
```
```
In net/packet/af_packet.c (ffffffff818799a9)
Location: include/linux/netdevice.h:3351
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
```
```
In net/switchdev/switchdev.c (ffffffff8188a7d9)
Location: include/linux/netdevice.h:3351
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_deferred_enqueue
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
In drivers/net/tun.c (ffffffff8167e78f)
Location: include/linux/netdevice.h:3305
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_show_fdinfo
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:tun_peek_len
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_chr_read_iter
  - drivers/net/tun.c:tun_chr_write_iter
  - drivers/net/tun.c:tun_chr_poll
```
```
In net/core/dev.c (ffffffff817b4a45)
Location: include/linux/netdevice.h:3305
Inline: True
Inline callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:dev_getfirstbyhwtype
  - net/core/dev.c:dev_get_by_index
  - net/core/dev.c:dev_get_by_name
```
```
In net/core/ethtool.c (ffffffff817b7f56)
Location: include/linux/netdevice.h:3305
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
```
```
In net/core/dst.c (ffffffff817baa72)
Location: include/linux/netdevice.h:3305
Inline: True
Inline callers:
  - net/core/dst.c:dst_ifdown
  - net/core/dst.c:dst_init
```
```
In net/core/neighbour.c (ffffffff817bca99)
Location: include/linux/netdevice.h:3305
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:pneigh_lookup
  - net/core/neighbour.c:__neigh_create
```
```
In net/core/link_watch.c (ffffffff817c8c6b)
Location: include/linux/netdevice.h:3305
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_fire_event
```
```
In net/core/net-sysfs.c (ffffffff817d21da)
Location: include/linux/netdevice.h:3305
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
```
In net/core/netpoll.c (ffffffff817d33cd)
Location: include/linux/netdevice.h:3305
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
```
```
In net/sched/sch_generic.c (ffffffff817dde3e)
Location: include/linux/netdevice.h:3305
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_generic.c:__netdev_watchdog_up
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/netlink/af_netlink.c (ffffffff817e7911)
Location: include/linux/netdevice.h:3305
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_deliver_tap
```
```
In net/netfilter/nf_queue.c (ffffffff817ee08c)
Location: include/linux/netdevice.h:3305
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
```
```
In net/ipv4/route.c (ffffffff817f3916)
Location: include/linux/netdevice.h:3305
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/route.c:rt_flush_dev
```
```
In net/ipv4/devinet.c (ffffffff81830a29)
Location: include/linux/netdevice.h:3305
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:__ip_dev_find
```
```
In net/ipv4/fib_semantics.c (ffffffff8183c162)
Location: include/linux/netdevice.h:3305
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/ipmr.c (ffffffff818c4d40)
Location: include/linux/netdevice.h:3305
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
```
```
In net/ipv4/xfrm4_policy.c (ffffffff8184da14)
Location: include/linux/netdevice.h:3305
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_fill_dst
```
```
In net/xfrm/xfrm_policy.c (ffffffff8184f6d7)
Location: include/linux/netdevice.h:3305
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_ifdown
```
```
In net/xfrm/xfrm_input.c (ffffffff8185a59f)
Location: include/linux/netdevice.h:3305
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/ipv6/addrconf.c (ffffffff8186bd39)
Location: include/linux/netdevice.h:3305
Inline: True
```
```
In net/ipv6/route.c (ffffffff81878e20)
Location: include/linux/netdevice.h:3305
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_ifdown
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
```
```
In net/ipv6/ip6mr.c (ffffffff8189cff4)
Location: include/linux/netdevice.h:3305
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_policy.c (ffffffff8189e478)
Location: include/linux/netdevice.h:3305
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
```
```
In net/packet/af_packet.c (ffffffff818ae089)
Location: include/linux/netdevice.h:3305
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
```
```
In net/switchdev/switchdev.c (ffffffff818beb89)
Location: include/linux/netdevice.h:3305
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_deferred_enqueue
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
In drivers/net/tun.c (ffffffff81694069)
Location: include/linux/netdevice.h:3351
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_show_fdinfo
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:tun_peek_len
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_chr_read_iter
  - drivers/net/tun.c:tun_chr_write_iter
  - drivers/net/tun.c:tun_chr_poll
```
```
In net/core/dev.c (ffffffff817d35e5)
Location: include/linux/netdevice.h:3351
Inline: True
Inline callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:dev_getfirstbyhwtype
  - net/core/dev.c:dev_get_by_index
  - net/core/dev.c:dev_get_by_name
```
```
In net/core/ethtool.c (ffffffff817d6fd4)
Location: include/linux/netdevice.h:3351
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
```
```
In net/core/dst.c (ffffffff817d957d)
Location: include/linux/netdevice.h:3351
Inline: True
Inline callers:
  - net/core/dst.c:dst_dev_put
```
```
In net/core/neighbour.c (ffffffff817db169)
Location: include/linux/netdevice.h:3351
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:pneigh_lookup
  - net/core/neighbour.c:__neigh_create
```
```
In net/core/link_watch.c (ffffffff817e781a)
Location: include/linux/netdevice.h:3351
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_fire_event
```
```
In net/core/net-sysfs.c (ffffffff817f15ba)
Location: include/linux/netdevice.h:3351
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
```
In net/core/netpoll.c (ffffffff817f2703)
Location: include/linux/netdevice.h:3351
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
```
```
In net/sched/sch_generic.c (ffffffff817fd41c)
Location: include/linux/netdevice.h:3351
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_generic.c:__netdev_watchdog_up
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/netlink/af_netlink.c (ffffffff8180761f)
Location: include/linux/netdevice.h:3351
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_deliver_tap
```
```
In net/netfilter/nf_queue.c (ffffffff8180e1bc)
Location: include/linux/netdevice.h:3351
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
```
```
In net/ipv4/route.c (ffffffff81813d28)
Location: include/linux/netdevice.h:3351
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/route.c:rt_flush_dev
```
```
In net/ipv4/devinet.c (ffffffff81851fee)
Location: include/linux/netdevice.h:3351
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:__ip_dev_find
```
```
In net/ipv4/fib_semantics.c (ffffffff8185c91d)
Location: include/linux/netdevice.h:3351
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81868f3c)
Location: include/linux/netdevice.h:3351
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
```
```
In net/ipv4/xfrm4_policy.c (ffffffff81871473)
Location: include/linux/netdevice.h:3351
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_fill_dst
```
```
In net/xfrm/xfrm_policy.c (ffffffff818731a4)
Location: include/linux/netdevice.h:3351
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_ifdown
```
```
In net/xfrm/xfrm_input.c (ffffffff8187e4fc)
Location: include/linux/netdevice.h:3351
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_device.c (ffffffff818803bf)
Location: include/linux/netdevice.h:3351
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81890868)
Location: include/linux/netdevice.h:3351
Inline: True
```
```
In net/ipv6/route.c (ffffffff8189e097)
Location: include/linux/netdevice.h:3351
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_ifdown
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
```
```
In net/ipv6/ip6mr.c (ffffffff818c34ec)
Location: include/linux/netdevice.h:3351
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_policy.c (ffffffff818c49a6)
Location: include/linux/netdevice.h:3351
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
```
```
In net/packet/af_packet.c (ffffffff818cfe74)
Location: include/linux/netdevice.h:3351
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
```
```
In net/switchdev/switchdev.c (ffffffff818e56a1)
Location: include/linux/netdevice.h:3351
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_deferred_enqueue
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
In drivers/net/tun.c (ffffffff816fe066)
Location: include/linux/netdevice.h:3380
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_show_fdinfo
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:tun_peek_len
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_chr_read_iter
  - drivers/net/tun.c:tun_chr_write_iter
  - drivers/net/tun.c:tun_chr_poll
```
```
In net/core/dev.c (ffffffff8184dae7)
Location: include/linux/netdevice.h:3380
Inline: True
Inline callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:dev_getfirstbyhwtype
  - net/core/dev.c:dev_get_by_index
  - net/core/dev.c:dev_get_by_name
```
```
In net/core/ethtool.c (ffffffff81850e30)
Location: include/linux/netdevice.h:3380
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
```
```
In net/core/dst.c (ffffffff81853c90)
Location: include/linux/netdevice.h:3380
Inline: True
Inline callers:
  - net/core/dst.c:dst_dev_put
```
```
In net/core/neighbour.c (ffffffff81855919)
Location: include/linux/netdevice.h:3380
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:pneigh_lookup
  - net/core/neighbour.c:__neigh_create
```
```
In net/core/link_watch.c (ffffffff8186275a)
Location: include/linux/netdevice.h:3380
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_fire_event
```
```
In net/core/net-sysfs.c (ffffffff8186cb82)
Location: include/linux/netdevice.h:3380
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
```
In net/core/netpoll.c (ffffffff8186dcc3)
Location: include/linux/netdevice.h:3380
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
```
```
In net/sched/sch_generic.c (ffffffff8187aea0)
Location: include/linux/netdevice.h:3380
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_generic.c:__netdev_watchdog_up
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/netlink/af_netlink.c (ffffffff8188603b)
Location: include/linux/netdevice.h:3380
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_deliver_tap
```
```
In net/netfilter/nf_queue.c (ffffffff8188d6a2)
Location: include/linux/netdevice.h:3380
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
```
```
In net/ipv4/route.c (ffffffff8189338b)
Location: include/linux/netdevice.h:3380
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/route.c:rt_flush_dev
```
```
In net/ipv4/devinet.c (ffffffff818d1dde)
Location: include/linux/netdevice.h:3380
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:__ip_dev_find
```
```
In net/ipv4/fib_semantics.c (ffffffff818dc80d)
Location: include/linux/netdevice.h:3380
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff818e9610)
Location: include/linux/netdevice.h:3380
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:ipmr_new_tunnel
```
```
In net/ipv4/xfrm4_policy.c (ffffffff818f1e63)
Location: include/linux/netdevice.h:3380
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_fill_dst
```
```
In net/xfrm/xfrm_policy.c (ffffffff818f3bb4)
Location: include/linux/netdevice.h:3380
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_ifdown
```
```
In net/xfrm/xfrm_input.c (ffffffff818ff47d)
Location: include/linux/netdevice.h:3380
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_device.c (ffffffff81901560)
Location: include/linux/netdevice.h:3380
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81911fae)
Location: include/linux/netdevice.h:3380
Inline: True
```
```
In net/ipv6/route.c (ffffffff81920631)
Location: include/linux/netdevice.h:3380
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_ifdown
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
```
```
In net/ipv6/ip6mr.c (ffffffff81946782)
Location: include/linux/netdevice.h:3380
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_policy.c (ffffffff8194804c)
Location: include/linux/netdevice.h:3380
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
```
```
In net/packet/af_packet.c (ffffffff81954d4f)
Location: include/linux/netdevice.h:3380
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
```
```
In net/switchdev/switchdev.c (ffffffff8196b7dc)
Location: include/linux/netdevice.h:3380
Inline: True
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
In drivers/net/tun.c (ffffffff8173c26f)
Location: include/linux/netdevice.h:3486
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_show_fdinfo
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:tun_peek_len
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_chr_read_iter
  - drivers/net/tun.c:tun_chr_write_iter
  - drivers/net/tun.c:tun_chr_poll
```
```
In net/core/dev.c (ffffffff8189884e)
Location: include/linux/netdevice.h:3486
Inline: True
Inline callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:dev_getfirstbyhwtype
  - net/core/dev.c:dev_get_by_index
  - net/core/dev.c:dev_get_by_name
```
```
In net/core/ethtool.c (ffffffff8189c667)
Location: include/linux/netdevice.h:3486
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
```
```
In net/core/dst.c (ffffffff8189f413)
Location: include/linux/netdevice.h:3486
Inline: True
Inline callers:
  - net/core/dst.c:dst_dev_put
```
```
In net/core/neighbour.c (ffffffff818a0eb9)
Location: include/linux/netdevice.h:3486
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:pneigh_lookup
  - net/core/neighbour.c:__neigh_create
```
```
In net/core/link_watch.c (ffffffff818ae43c)
Location: include/linux/netdevice.h:3486
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_fire_event
```
```
In net/core/net-sysfs.c (ffffffff818bd3e1)
Location: include/linux/netdevice.h:3486
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
```
In net/core/netpoll.c (ffffffff818bee11)
Location: include/linux/netdevice.h:3486
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
```
```
In net/sched/sch_generic.c (ffffffff818cd27c)
Location: include/linux/netdevice.h:3486
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_generic.c:__netdev_watchdog_up
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/netlink/af_netlink.c (ffffffff818d9946)
Location: include/linux/netdevice.h:3486
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_deliver_tap
```
```
In net/netfilter/nf_queue.c (ffffffff818e12d2)
Location: include/linux/netdevice.h:3486
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
```
```
In net/ipv4/route.c (ffffffff818e7558)
Location: include/linux/netdevice.h:3486
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/route.c:rt_flush_dev
```
```
In net/ipv4/devinet.c (ffffffff819282e2)
Location: include/linux/netdevice.h:3486
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:__ip_dev_find
```
```
In net/ipv4/fib_semantics.c (ffffffff81933392)
Location: include/linux/netdevice.h:3486
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_check_nh
  - net/ipv4/fib_semantics.c:fib_check_nh
  - net/ipv4/fib_semantics.c:fib_check_nh
```
```
In net/ipv4/ipmr.c (ffffffff8193fb43)
Location: include/linux/netdevice.h:3486
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:ipmr_new_tunnel
```
```
In net/ipv4/xfrm4_policy.c (ffffffff81948a1d)
Location: include/linux/netdevice.h:3486
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_fill_dst
```
```
In net/xfrm/xfrm_policy.c (ffffffff8194a4c0)
Location: include/linux/netdevice.h:3486
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_ifdown
```
```
In net/xfrm/xfrm_input.c (ffffffff81955fae)
Location: include/linux/netdevice.h:3486
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_device.c (ffffffff81958090)
Location: include/linux/netdevice.h:3486
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
```
```
In net/ipv6/addrconf.c (ffffffff819693d9)
Location: include/linux/netdevice.h:3486
Inline: True
```
```
In net/ipv6/route.c (ffffffff8197897f)
Location: include/linux/netdevice.h:3486
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:addrconf_f6i_alloc
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
```
```
In net/ipv6/ip6mr.c (ffffffff8199fc04)
Location: include/linux/netdevice.h:3486
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_policy.c (ffffffff819a10d7)
Location: include/linux/netdevice.h:3486
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
```
```
In net/packet/af_packet.c (ffffffff819b0b3f)
Location: include/linux/netdevice.h:3486
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
```
```
In net/switchdev/switchdev.c (ffffffff819c523c)
Location: include/linux/netdevice.h:3486
Inline: True
```
```
In net/xdp/xdp_umem.c (ffffffff819cce11)
Location: include/linux/netdevice.h:3486
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_assign_dev
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
In drivers/net/tun.c (ffffffff8175fbaf)
Location: include/linux/netdevice.h:3712
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_show_fdinfo
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:tun_peek_len
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_chr_read_iter
  - drivers/net/tun.c:tun_chr_write_iter
  - drivers/net/tun.c:tun_chr_poll
```
```
In net/core/dev.c (ffffffff818bacae)
Location: include/linux/netdevice.h:3712
Inline: True
Inline callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:dev_getfirstbyhwtype
  - net/core/dev.c:dev_get_by_index
  - net/core/dev.c:dev_get_by_name
```
```
In net/core/ethtool.c (ffffffff818bfc5b)
Location: include/linux/netdevice.h:3712
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
```
```
In net/core/dst.c (ffffffff818c1dd3)
Location: include/linux/netdevice.h:3712
Inline: True
Inline callers:
  - net/core/dst.c:dst_dev_put
```
```
In net/core/neighbour.c (ffffffff818c3d79)
Location: include/linux/netdevice.h:3712
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:pneigh_lookup
  - net/core/neighbour.c:___neigh_create
```
```
In net/core/link_watch.c (ffffffff818d26bc)
Location: include/linux/netdevice.h:3712
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_fire_event
```
```
In net/core/net-sysfs.c (ffffffff818e478b)
Location: include/linux/netdevice.h:3712
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
```
In net/core/netpoll.c (ffffffff818e7c0e)
Location: include/linux/netdevice.h:3712
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
```
```
In net/sched/sch_generic.c (ffffffff818f85dc)
Location: include/linux/netdevice.h:3712
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_generic.c:__netdev_watchdog_up
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/netlink/af_netlink.c (ffffffff81906397)
Location: include/linux/netdevice.h:3712
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_deliver_tap
```
```
In net/netfilter/nf_queue.c (ffffffff8190de29)
Location: include/linux/netdevice.h:3712
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
```
```
In net/ipv4/route.c (ffffffff81914408)
Location: include/linux/netdevice.h:3712
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/route.c:rt_flush_dev
```
```
In net/ipv4/devinet.c (ffffffff81957542)
Location: include/linux/netdevice.h:3712
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:__ip_dev_find
```
```
In net/ipv4/fib_semantics.c (ffffffff819639dc)
Location: include/linux/netdevice.h:3712
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/ipmr.c (ffffffff8196fb85)
Location: include/linux/netdevice.h:3712
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:ipmr_new_tunnel
```
```
In net/ipv4/xfrm4_policy.c (ffffffff8197a6ed)
Location: include/linux/netdevice.h:3712
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_fill_dst
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197c480)
Location: include/linux/netdevice.h:3712
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_ifdown
```
```
In net/xfrm/xfrm_input.c (ffffffff8198ab93)
Location: include/linux/netdevice.h:3712
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_device.c (ffffffff8198ca21)
Location: include/linux/netdevice.h:3712
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
```
```
In net/ipv6/addrconf.c (ffffffff8199ecae)
Location: include/linux/netdevice.h:3712
Inline: True
```
```
In net/ipv6/route.c (ffffffff819ae566)
Location: include/linux/netdevice.h:3712
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:addrconf_f6i_alloc
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
```
```
In net/ipv6/ip6mr.c (ffffffff819d6889)
Location: include/linux/netdevice.h:3712
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_policy.c (ffffffff819d7df7)
Location: include/linux/netdevice.h:3712
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
```
```
In net/packet/af_packet.c (ffffffff819e5f2f)
Location: include/linux/netdevice.h:3712
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
```
```
In net/switchdev/switchdev.c (ffffffff819fc88c)
Location: include/linux/netdevice.h:3712
Inline: True
```
```
In net/xdp/xdp_umem.c (ffffffff81a06137)
Location: include/linux/netdevice.h:3712
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_assign_dev
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
In drivers/net/tun.c (ffffffff8179c8ab)
Location: include/linux/netdevice.h:3733
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_show_fdinfo
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:tun_peek_len
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_chr_read_iter
  - drivers/net/tun.c:tun_chr_write_iter
  - drivers/net/tun.c:tun_chr_poll
```
```
In net/core/dev.c (ffffffff819065f2)
Location: include/linux/netdevice.h:3733
Inline: True
Inline callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:dev_getfirstbyhwtype
  - net/core/dev.c:dev_get_by_index
  - net/core/dev.c:dev_get_by_name
```
```
In net/core/ethtool.c (ffffffff8190b6dd)
Location: include/linux/netdevice.h:3733
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
```
```
In net/core/dst.c (ffffffff8190e516)
Location: include/linux/netdevice.h:3733
Inline: True
Inline callers:
  - net/core/dst.c:dst_dev_put
```
```
In net/core/neighbour.c (ffffffff8190fedb)
Location: include/linux/netdevice.h:3733
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:pneigh_lookup
  - net/core/neighbour.c:___neigh_create
```
```
In net/core/link_watch.c (ffffffff8191f94c)
Location: include/linux/netdevice.h:3733
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_fire_event
```
```
In net/core/net-sysfs.c (ffffffff81933dc1)
Location: include/linux/netdevice.h:3733
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
```
In net/core/netpoll.c (ffffffff8193758e)
Location: include/linux/netdevice.h:3733
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
```
```
In net/core/devlink.c (ffffffff81951d0d)
Location: include/linux/netdevice.h:3733
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_flash_update
  - net/core/devlink.c:devlink_compat_running_version
```
```
In net/sched/sch_generic.c (ffffffff81957dab)
Location: include/linux/netdevice.h:3733
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_generic.c:__netdev_watchdog_up
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/netlink/af_netlink.c (ffffffff8196763b)
Location: include/linux/netdevice.h:3733
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_deliver_tap
```
```
In net/netfilter/nf_queue.c (ffffffff8196fa09)
Location: include/linux/netdevice.h:3733
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
```
```
In net/ipv4/route.c (ffffffff81976618)
Location: include/linux/netdevice.h:3733
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/route.c:rt_flush_dev
```
```
In net/ipv4/devinet.c (ffffffff819bbf65)
Location: include/linux/netdevice.h:3733
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:__ip_dev_find
```
```
In net/ipv4/fib_semantics.c (ffffffff819c8ccd)
Location: include/linux/netdevice.h:3733
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_check_nh
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_semantics.c:fib_check_nh_v6_gw
```
```
In net/ipv4/ipmr.c (ffffffff819d948e)
Location: include/linux/netdevice.h:3733
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:ipmr_new_tunnel
```
```
In net/ipv4/xfrm4_policy.c (ffffffff819e41ed)
Location: include/linux/netdevice.h:3733
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_fill_dst
```
```
In net/xfrm/xfrm_policy.c (ffffffff819e57a0)
Location: include/linux/netdevice.h:3733
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_ifdown
```
```
In net/xfrm/xfrm_input.c (ffffffff819f590a)
Location: include/linux/netdevice.h:3733
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_device.c (ffffffff819f8037)
Location: include/linux/netdevice.h:3733
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
```
```
In net/ipv6/addrconf.c (ffffffff81a0ad90)
Location: include/linux/netdevice.h:3733
Inline: True
```
```
In net/ipv6/route.c (ffffffff81a1c3d1)
Location: include/linux/netdevice.h:3733
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:ip6_route_check_nh
```
```
In net/ipv6/ip6mr.c (ffffffff81a4594a)
Location: include/linux/netdevice.h:3733
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81a46df7)
Location: include/linux/netdevice.h:3733
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
```
```
In net/packet/af_packet.c (ffffffff81a55970)
Location: include/linux/netdevice.h:3733
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
```
```
In net/switchdev/switchdev.c (ffffffff81a6bbd6)
Location: include/linux/netdevice.h:3733
Inline: True
```
```
In net/xdp/xdp_umem.c (ffffffff81a75729)
Location: include/linux/netdevice.h:3733
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_assign_dev
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
In drivers/net/tun.c (ffffffff817c035b)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_show_fdinfo
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:tun_peek_len
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_chr_read_iter
  - drivers/net/tun.c:tun_chr_write_iter
  - drivers/net/tun.c:tun_chr_poll
```
```
In net/core/dev.c (ffffffff81938dba)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:dev_getfirstbyhwtype
  - net/core/dev.c:dev_get_by_index
  - net/core/dev.c:dev_get_by_name
```
```
In net/core/ethtool.c (ffffffff8193dd0b)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
```
```
In net/core/dst.c (ffffffff81940b56)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/core/dst.c:dst_dev_put
```
```
In net/core/neighbour.c (ffffffff8194254b)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:pneigh_lookup
  - net/core/neighbour.c:___neigh_create
```
```
In net/core/link_watch.c (ffffffff81951b8c)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_fire_event
```
```
In net/core/net-sysfs.c (ffffffff819668fd)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
```
In net/core/netpoll.c (ffffffff8196a44e)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
```
```
In net/core/drop_monitor.c (ffffffff819747bd)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
```
```
In net/core/lwt_bpf.c (ffffffff81977bc6)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_input
```
```
In net/core/devlink.c (ffffffff8198874d)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_flash_update
  - net/core/devlink.c:devlink_compat_running_version
```
```
In net/sched/sch_generic.c (ffffffff8198e24b)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_generic.c:__netdev_watchdog_up
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/netlink/af_netlink.c (ffffffff8199e0cb)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_deliver_tap
```
```
In net/netfilter/nf_queue.c (ffffffff819a6379)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
```
```
In net/ipv4/route.c (ffffffff819ad028)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/route.c:rt_flush_dev
```
```
In net/ipv4/devinet.c (ffffffff819f2c65)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:__ip_dev_find
```
```
In net/ipv4/fib_semantics.c (ffffffff819ff88d)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_check_nh
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_semantics.c:fib_check_nh_v6_gw
```
```
In net/ipv4/ipmr.c (ffffffff81a101fe)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:ipmr_new_tunnel
```
```
In net/ipv4/xfrm4_policy.c (ffffffff81a1b1ed)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_fill_dst
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a1c7d0)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_ifdown
```
```
In net/xfrm/xfrm_input.c (ffffffff81a2c5b2)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_device.c (ffffffff81a2ec87)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
```
```
In net/ipv6/addrconf.c (ffffffff81a41a40)
Location: include/linux/netdevice.h:3749
Inline: True
```
```
In net/ipv6/route.c (ffffffff81a53051)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:ip6_route_check_nh
```
```
In net/ipv6/ip6mr.c (ffffffff81a7c53a)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81a7d9a7)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
```
```
In net/packet/af_packet.c (ffffffff81a8ca40)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
```
```
In net/switchdev/switchdev.c (ffffffff81aa25b6)
Location: include/linux/netdevice.h:3749
Inline: True
```
```
In net/xdp/xdp_umem.c (ffffffff81aac58f)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_assign_dev
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
In drivers/net/tun.c (ffffffff81889d74)
Location: include/linux/netdevice.h:3862
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_show_fdinfo
  - drivers/net/tun.c:tun_peek_len
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_chr_read_iter
  - drivers/net/tun.c:tun_chr_write_iter
  - drivers/net/tun.c:tun_chr_poll
```
```
In net/core/dev.c (ffffffff81a0df39)
Location: include/linux/netdevice.h:3862
Inline: True
Inline callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__netdev_adjacent_dev_insert
  - net/core/dev.c:dev_getfirstbyhwtype
  - net/core/dev.c:dev_get_by_index
  - net/core/dev.c:dev_get_by_name
```
```
In net/core/dst.c (ffffffff81a106ef)
Location: include/linux/netdevice.h:3862
Inline: True
Inline callers:
  - net/core/dst.c:dst_dev_put
  - net/core/dst.c:dst_alloc
```
```
In net/core/neighbour.c (ffffffff81a126ec)
Location: include/linux/netdevice.h:3862
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:pneigh_lookup
  - net/core/neighbour.c:___neigh_create
```
```
In net/core/link_watch.c (ffffffff81a229ad)
Location: include/linux/netdevice.h:3862
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_fire_event
```
```
In net/core/net-sysfs.c (ffffffff81a3a026)
Location: include/linux/netdevice.h:3862
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
```
In net/core/netpoll.c (ffffffff81a3e307)
Location: include/linux/netdevice.h:3862
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
```
```
In net/core/drop_monitor.c (ffffffff81a498b6)
Location: include/linux/netdevice.h:3862
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_metadata_clone
```
```
In net/core/lwt_bpf.c (ffffffff81a4d33d)
Location: include/linux/netdevice.h:3862
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_input
```
```
In net/core/devlink.c (ffffffff81a60435)
Location: include/linux/netdevice.h:3862
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_flash_update
  - net/core/devlink.c:devlink_compat_running_version
```
```
In net/sched/sch_generic.c (ffffffff81a65eca)
Location: include/linux/netdevice.h:3862
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_generic.c:__netdev_watchdog_up
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/netlink/af_netlink.c (ffffffff81a76da5)
Location: include/linux/netdevice.h:3862
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_deliver_tap_skb
```
```
In net/ethtool/ioctl.c (ffffffff81a81567)
Location: include/linux/netdevice.h:3862
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_phys_id
```
```
In net/ethtool/netlink.c (ffffffff81a85c68)
Location: include/linux/netdevice.h:3862
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_dumpit
```
```
In net/netfilter/nf_queue.c (ffffffff81a8f706)
Location: include/linux/netdevice.h:3862
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
```
```
In net/ipv4/route.c (ffffffff81a96eb1)
Location: include/linux/netdevice.h:3862
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/route.c:rt_flush_dev
```
```
In net/ipv4/devinet.c (ffffffff81ae0d64)
Location: include/linux/netdevice.h:3862
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:__ip_dev_find
```
```
In net/ipv4/fib_semantics.c (ffffffff81aeedd6)
Location: include/linux/netdevice.h:3862
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_check_nh
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_semantics.c:fib_check_nh_v6_gw
```
```
In net/ipv4/ipmr.c (ffffffff81b011b0)
Location: include/linux/netdevice.h:3862
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:ipmr_new_tunnel
```
```
In net/ipv4/xfrm4_policy.c (ffffffff81b0c1a6)
Location: include/linux/netdevice.h:3862
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_fill_dst
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0db89)
Location: include/linux/netdevice.h:3862
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_ifdown
```
```
In net/xfrm/xfrm_input.c (ffffffff81b1eaae)
Location: include/linux/netdevice.h:3862
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_device.c (ffffffff81b2176f)
Location: include/linux/netdevice.h:3862
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
```
```
In net/ipv6/addrconf.c (ffffffff81b37424)
Location: include/linux/netdevice.h:3862
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_dev
```
```
In net/ipv6/route.c (ffffffff81b49066)
Location: include/linux/netdevice.h:3862
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:ip6_route_check_nh
  - net/ipv6/route.c:rt6_probe
```
```
In net/ipv6/ip6mr.c (ffffffff81b73d17)
Location: include/linux/netdevice.h:3862
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mif6_add
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81b781c0)
Location: include/linux/netdevice.h:3862
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
```
```
In net/packet/af_packet.c (ffffffff81b89469)
Location: include/linux/netdevice.h:3862
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
```
```
In net/switchdev/switchdev.c (ffffffff81b9df8f)
Location: include/linux/netdevice.h:3862
Inline: True
```
```
In net/xdp/xdp_umem.c (ffffffff81ba883a)
Location: include/linux/netdevice.h:3862
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_assign_dev
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
In drivers/net/tun.c (ffffffff81899914)
Location: include/linux/netdevice.h:4030
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_show_fdinfo
  - drivers/net/tun.c:tun_peek_len
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_chr_read_iter
  - drivers/net/tun.c:tun_chr_write_iter
  - drivers/net/tun.c:tun_chr_poll
```
```
In net/core/dev.c (ffffffff81a0ed19)
Location: include/linux/netdevice.h:4030
Inline: True
Inline callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:bpf_xdp_link_attach
  - net/core/dev.c:__netdev_adjacent_dev_insert
  - net/core/dev.c:dev_getfirstbyhwtype
  - net/core/dev.c:dev_get_by_name
```
```
In net/core/dst.c (ffffffff81a10abf)
Location: include/linux/netdevice.h:4030
Inline: True
Inline callers:
  - net/core/dst.c:dst_dev_put
  - net/core/dst.c:dst_alloc
```
```
In net/core/neighbour.c (ffffffff81a12a3c)
Location: include/linux/netdevice.h:4030
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:pneigh_lookup
  - net/core/neighbour.c:___neigh_create
```
```
In net/core/link_watch.c (ffffffff81a22d0d)
Location: include/linux/netdevice.h:4030
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_fire_event
```
```
In net/core/net-sysfs.c (ffffffff81a3c5a6)
Location: include/linux/netdevice.h:4030
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
```
In net/core/netpoll.c (ffffffff81a410bf)
Location: include/linux/netdevice.h:4030
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
```
```
In net/core/drop_monitor.c (ffffffff81a4f086)
Location: include/linux/netdevice.h:4030
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_metadata_copy
```
```
In net/core/lwt_bpf.c (ffffffff81a52ffd)
Location: include/linux/netdevice.h:4030
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_input
```
```
In net/core/devlink.c (ffffffff81a68c68)
Location: include/linux/netdevice.h:4030
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_flash_update
  - net/core/devlink.c:devlink_compat_running_version
```
```
In net/sched/sch_generic.c (ffffffff81a6dfce)
Location: include/linux/netdevice.h:4030
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_generic.c:__netdev_watchdog_up
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/netlink/af_netlink.c (ffffffff81a7fb25)
Location: include/linux/netdevice.h:4030
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_deliver_tap_skb
```
```
In net/ethtool/ioctl.c (ffffffff81a8b16a)
Location: include/linux/netdevice.h:4030
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_phys_id
```
```
In net/ethtool/netlink.c (ffffffff81a8f5f8)
Location: include/linux/netdevice.h:4030
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_dumpit
```
```
In net/netfilter/nf_queue.c (ffffffff81a996f6)
Location: include/linux/netdevice.h:4030
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
```
```
In net/ipv4/route.c (ffffffff81aa0fa1)
Location: include/linux/netdevice.h:4030
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/route.c:rt_flush_dev
```
```
In net/ipv4/devinet.c (ffffffff81aedbe4)
Location: include/linux/netdevice.h:4030
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:__ip_dev_find
```
```
In net/ipv4/fib_semantics.c (ffffffff81afbd38)
Location: include/linux/netdevice.h:4030
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_check_nh
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_semantics.c:fib_check_nh_v6_gw
```
```
In net/ipv4/ipmr.c (ffffffff81b0f290)
Location: include/linux/netdevice.h:4030
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:ipmr_new_tunnel
```
```
In net/ipv4/xfrm4_policy.c (ffffffff81b1a526)
Location: include/linux/netdevice.h:4030
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_fill_dst
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b1bd99)
Location: include/linux/netdevice.h:4030
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_ifdown
```
```
In net/xfrm/xfrm_input.c (ffffffff81b2d18c)
Location: include/linux/netdevice.h:4030
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_device.c (ffffffff81b3013a)
Location: include/linux/netdevice.h:4030
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
```
```
In net/ipv6/addrconf.c (ffffffff81b46154)
Location: include/linux/netdevice.h:4030
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_dev
```
```
In net/ipv6/route.c (ffffffff81b57c86)
Location: include/linux/netdevice.h:4030
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:ip6_route_check_nh
  - net/ipv6/route.c:rt6_probe
```
```
In net/ipv6/ip6mr.c (ffffffff81b82a87)
Location: include/linux/netdevice.h:4030
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mif6_add
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81b87110)
Location: include/linux/netdevice.h:4030
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
```
```
In net/packet/af_packet.c (ffffffff81b98f69)
Location: include/linux/netdevice.h:4030
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
```
```
In net/switchdev/switchdev.c (ffffffff81bad8af)
Location: include/linux/netdevice.h:4030
Inline: True
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81bb8efe)
Location: include/linux/netdevice.h:4030
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:__xp_assign_dev
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
In drivers/net/tun.c (ffffffff8187bd9d)
Location: include/linux/netdevice.h:4156
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_show_fdinfo
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:tun_peek_len
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_chr_read_iter
  - drivers/net/tun.c:tun_chr_write_iter
  - drivers/net/tun.c:tun_chr_poll
```
```
In net/core/dev.c (ffffffff819ed02f)
Location: include/linux/netdevice.h:4156
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:bpf_xdp_link_attach
  - net/core/dev.c:__netdev_adjacent_dev_insert
  - net/core/dev.c:dev_getfirstbyhwtype
  - net/core/dev.c:dev_get_by_name
```
```
In net/core/dst.c (ffffffff819f792f)
Location: include/linux/netdevice.h:4156
Inline: True
Inline callers:
  - net/core/dst.c:dst_dev_put
  - net/core/dst.c:dst_alloc
```
```
In net/core/neighbour.c (ffffffff819f941c)
Location: include/linux/netdevice.h:4156
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:pneigh_lookup
  - net/core/neighbour.c:___neigh_create
```
```
In net/core/link_watch.c (ffffffff81a0a08d)
Location: include/linux/netdevice.h:4156
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_fire_event
```
```
In net/core/net-sysfs.c (ffffffff81a233b6)
Location: include/linux/netdevice.h:4156
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
```
In net/core/netpoll.c (ffffffff81a25d77)
Location: include/linux/netdevice.h:4156
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
```
```
In net/core/drop_monitor.c (ffffffff81a3413e)
Location: include/linux/netdevice.h:4156
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_trap_packet_probe
```
```
In net/core/lwt_bpf.c (ffffffff81a3881c)
Location: include/linux/netdevice.h:4156
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_input
```
```
In net/core/devlink.c (ffffffff81a4c028)
Location: include/linux/netdevice.h:4156
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_flash_update
  - net/core/devlink.c:devlink_compat_running_version
```
```
In net/sched/sch_generic.c (ffffffff81a5683e)
Location: include/linux/netdevice.h:4156
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_generic.c:__netdev_watchdog_up
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/netlink/af_netlink.c (ffffffff81a68a9a)
Location: include/linux/netdevice.h:4156
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_deliver_tap
```
```
In net/ethtool/ioctl.c (ffffffff81a7449a)
Location: include/linux/netdevice.h:4156
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_phys_id
```
```
In net/ethtool/netlink.c (ffffffff81a78b85)
Location: include/linux/netdevice.h:4156
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_dumpit
```
```
In net/netfilter/nf_queue.c (ffffffff81a84a06)
Location: include/linux/netdevice.h:4156
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
```
```
In net/ipv4/route.c (ffffffff81a8bf21)
Location: include/linux/netdevice.h:4156
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/route.c:rt_flush_dev
```
```
In net/ipv4/icmp.c (ffffffff81ad51b0)
Location: include/linux/netdevice.h:4156
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_echo
```
```
In net/ipv4/devinet.c (ffffffff81ad93b4)
Location: include/linux/netdevice.h:4156
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:__ip_dev_find
```
```
In net/ipv4/fib_semantics.c (ffffffff81ae7498)
Location: include/linux/netdevice.h:4156
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_check_nh
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_semantics.c:fib_check_nh_v6_gw
```
```
In net/ipv4/ipmr.c (ffffffff81afcf96)
Location: include/linux/netdevice.h:4156
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:ipmr_new_tunnel
```
```
In net/ipv4/xfrm4_policy.c (ffffffff81b081c6)
Location: include/linux/netdevice.h:4156
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_fill_dst
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b09a89)
Location: include/linux/netdevice.h:4156
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_ifdown
```
```
In net/xfrm/xfrm_input.c (ffffffff81b1adcb)
Location: include/linux/netdevice.h:4156
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_device.c (ffffffff81b1de75)
Location: include/linux/netdevice.h:4156
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
```
```
In net/ipv6/addrconf.c (ffffffff81b33fa4)
Location: include/linux/netdevice.h:4156
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_dev
```
```
In net/ipv6/route.c (ffffffff81b47253)
Location: include/linux/netdevice.h:4156
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:ip6_route_check_nh
  - net/ipv6/route.c:rt6_probe
```
```
In net/ipv6/ip6mr.c (ffffffff81b716f1)
Location: include/linux/netdevice.h:4156
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mif6_add
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81b75de0)
Location: include/linux/netdevice.h:4156
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
```
```
In net/packet/af_packet.c (ffffffff81b88559)
Location: include/linux/netdevice.h:4156
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
```
```
In net/switchdev/switchdev.c (ffffffff81b9c9f3)
Location: include/linux/netdevice.h:4156
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_deferred_enqueue
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81ba8b7e)
Location: include/linux/netdevice.h:4156
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_assign_dev
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
In drivers/net/tun.c (ffffffff8190d414)
Location: include/linux/netdevice.h:4177
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_show_fdinfo
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:tun_peek_len
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_chr_read_iter
  - drivers/net/tun.c:tun_chr_write_iter
  - drivers/net/tun.c:tun_chr_poll
```
```
In net/core/dev.c (ffffffff81a9e246)
Location: include/linux/netdevice.h:4177
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:bpf_xdp_link_attach
  - net/core/dev.c:__netdev_adjacent_dev_insert
  - net/core/dev.c:dev_getfirstbyhwtype
  - net/core/dev.c:dev_get_by_name
```
```
In net/core/dst.c (ffffffff81aa950f)
Location: include/linux/netdevice.h:4177
Inline: True
Inline callers:
  - net/core/dst.c:dst_dev_put
  - net/core/dst.c:dst_alloc
```
```
In net/core/neighbour.c (ffffffff81aab05c)
Location: include/linux/netdevice.h:4177
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:pneigh_lookup
  - net/core/neighbour.c:___neigh_create
```
```
In net/core/link_watch.c (ffffffff81abc59d)
Location: include/linux/netdevice.h:4177
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_fire_event
```
```
In net/core/dev_ioctl.c (ffffffff81ad0c0c)
Location: include/linux/netdevice.h:4177
Inline: True
Inline callers:
  - net/core/dev_ioctl.c:dev_ifsioc
```
```
In net/core/net-sysfs.c (ffffffff81ad79b6)
Location: include/linux/netdevice.h:4177
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
```
In net/core/netpoll.c (ffffffff81adaad7)
Location: include/linux/netdevice.h:4177
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
```
```
In net/core/drop_monitor.c (ffffffff81ae9c39)
Location: include/linux/netdevice.h:4177
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_trap_packet_probe
```
```
In net/core/lwt_bpf.c (ffffffff81aee641)
Location: include/linux/netdevice.h:4177
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_input_reroute
```
```
In net/core/devlink.c (ffffffff81b04471)
Location: include/linux/netdevice.h:4177
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_flash_update
  - net/core/devlink.c:devlink_compat_running_version
```
```
In net/sched/sch_generic.c (ffffffff81b0f635)
Location: include/linux/netdevice.h:4177
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/netlink/af_netlink.c (ffffffff81b22029)
Location: include/linux/netdevice.h:4177
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_deliver_tap
```
```
In net/ethtool/ioctl.c (ffffffff81b2e6dc)
Location: include/linux/netdevice.h:4177
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_phys_id
```
```
In net/ethtool/netlink.c (ffffffff81b32d55)
Location: include/linux/netdevice.h:4177
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_dumpit
```
```
In net/netfilter/nf_queue.c (ffffffff81b3f02a)
Location: include/linux/netdevice.h:4177
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
```
```
In net/ipv4/route.c (ffffffff81b46eac)
Location: include/linux/netdevice.h:4177
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/route.c:rt_flush_dev
```
```
In net/ipv4/icmp.c (ffffffff81b9327c)
Location: include/linux/netdevice.h:4177
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_build_probe
```
```
In net/ipv4/devinet.c (ffffffff81b98414)
Location: include/linux/netdevice.h:4177
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:__ip_dev_find
```
```
In net/ipv4/fib_semantics.c (ffffffff81ba72d8)
Location: include/linux/netdevice.h:4177
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_check_nh
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_semantics.c:fib_check_nh_v6_gw
```
```
In net/ipv4/ipmr.c (ffffffff81bbe74b)
Location: include/linux/netdevice.h:4177
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:ipmr_new_tunnel
```
```
In net/ipv4/xfrm4_policy.c (ffffffff81bcb0c6)
Location: include/linux/netdevice.h:4177
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_fill_dst
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bcca49)
Location: include/linux/netdevice.h:4177
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_ifdown
```
```
In net/xfrm/xfrm_input.c (ffffffff81bdf6ff)
Location: include/linux/netdevice.h:4177
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_device.c (ffffffff81be291c)
Location: include/linux/netdevice.h:4177
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
```
```
In net/ipv6/addrconf.c (ffffffff81bfa627)
Location: include/linux/netdevice.h:4177
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_dev
```
```
In net/ipv6/route.c (ffffffff81c0e48a)
Location: include/linux/netdevice.h:4177
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:ip6_route_check_nh
  - net/ipv6/route.c:rt6_probe
```
```
In net/ipv6/ip6mr.c (ffffffff81c3bb67)
Location: include/linux/netdevice.h:4177
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mif6_add
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81c40850)
Location: include/linux/netdevice.h:4177
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
```
```
In net/packet/af_packet.c (ffffffff81c54669)
Location: include/linux/netdevice.h:4177
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
```
```
In net/switchdev/switchdev.c (ffffffff81c69be3)
Location: include/linux/netdevice.h:4177
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_deferred_enqueue
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81c768ce)
Location: include/linux/netdevice.h:4177
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_assign_dev
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
In drivers/net/tun.c (ffffffff81a6260d)
Location: include/linux/netdevice.h:4023
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_show_fdinfo
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:tun_peek_len
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_chr_read_iter
  - drivers/net/tun.c:tun_chr_write_iter
  - drivers/net/tun.c:tun_chr_poll
```
```
In net/core/dev.c (ffffffff81c1e18b)
Location: include/linux/netdevice.h:4023
Inline: True
Inline callers:
  - net/core/dev.c:bpf_xdp_link_attach
  - net/core/dev.c:dev_getfirstbyhwtype
  - net/core/dev.c:dev_get_by_name
```
```
In net/core/neighbour.c (ffffffff81c22bc6)
Location: include/linux/netdevice.h:4023
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
```
```
In net/core/netpoll.c (ffffffff81c5c1dc)
Location: include/linux/netdevice.h:4023
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
```
```
In net/core/lwt_bpf.c (ffffffff81c71555)
Location: include/linux/netdevice.h:4023
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_input_reroute
```
```
In net/netlink/af_netlink.c (ffffffff81caac98)
Location: include/linux/netdevice.h:4023
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_deliver_tap
```
```
In net/ethtool/netlink.c (ffffffff81cbe920)
Location: include/linux/netdevice.h:4023
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_dumpit
```
```
In net/netfilter/nf_queue.c (ffffffff81ccb762)
Location: include/linux/netdevice.h:4023
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
```
```
In net/ipv4/icmp.c (ffffffff81d25920)
Location: include/linux/netdevice.h:4023
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_build_probe
```
```
In net/ipv4/devinet.c (ffffffff81d28c79)
Location: include/linux/netdevice.h:4023
Inline: True
Inline callers:
  - net/ipv4/devinet.c:__ip_dev_find
```
```
In net/ipv4/ipmr.c (ffffffff81d536fc)
Location: include/linux/netdevice.h:4023
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:ipmr_new_tunnel
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d62762)
Location: include/linux/netdevice.h:4023
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_ifdown
```
```
In net/xfrm/xfrm_input.c (ffffffff81d76358)
Location: include/linux/netdevice.h:4023
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_device.c (ffffffff81d79a51)
Location: include/linux/netdevice.h:4023
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
```
```
In net/ipv6/route.c (ffffffff81da767a)
Location: include/linux/netdevice.h:4023
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:ip6_route_check_nh
```
```
In net/ipv6/ip6mr.c (ffffffff81dd9ed5)
Location: include/linux/netdevice.h:4023
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mif6_add
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/packet/af_packet.c (ffffffff81df2d26)
Location: include/linux/netdevice.h:4023
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81e1b221)
Location: include/linux/netdevice.h:4023
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_assign_dev
```
```
In net/mctp/device.c (ffffffff81e38370)
Location: include/linux/netdevice.h:4023
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_add_dev
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
In drivers/net/tun.c (ffffffff81bedddd)
Location: include/linux/netdevice.h:4067
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_show_fdinfo
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:tun_peek_len
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_chr_read_iter
  - drivers/net/tun.c:tun_chr_write_iter
  - drivers/net/tun.c:tun_chr_poll
```
```
In net/core/dev.c (ffffffff81dcf5cb)
Location: include/linux/netdevice.h:4067
Inline: True
Inline callers:
  - net/core/dev.c:bpf_xdp_link_attach
  - net/core/dev.c:dev_getfirstbyhwtype
  - net/core/dev.c:dev_get_by_name
```
```
In net/core/neighbour.c (ffffffff81dd81c5)
Location: include/linux/netdevice.h:4067
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
```
```
In net/core/netpoll.c (ffffffff81e126c4)
Location: include/linux/netdevice.h:4067
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
```
```
In net/core/lwt_bpf.c (ffffffff81e29615)
Location: include/linux/netdevice.h:4067
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_input_reroute
```
```
In net/netlink/af_netlink.c (ffffffff81e67e3e)
Location: include/linux/netdevice.h:4067
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_deliver_tap
```
```
In net/ethtool/netlink.c (ffffffff81e7d440)
Location: include/linux/netdevice.h:4067
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_dumpit
```
```
In net/netfilter/nf_queue.c (ffffffff81e8b5a2)
Location: include/linux/netdevice.h:4067
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
```
```
In net/ipv4/icmp.c (ffffffff81eed1b0)
Location: include/linux/netdevice.h:4067
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_build_probe
```
```
In net/ipv4/devinet.c (ffffffff81ef06d9)
Location: include/linux/netdevice.h:4067
Inline: True
Inline callers:
  - net/ipv4/devinet.c:__ip_dev_find
```
```
In net/ipv4/ipmr.c (ffffffff81f1d3bb)
Location: include/linux/netdevice.h:4067
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:ipmr_new_tunnel
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f2d272)
Location: include/linux/netdevice.h:4067
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_ifdown
```
```
In net/xfrm/xfrm_input.c (ffffffff81f42aba)
Location: include/linux/netdevice.h:4067
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_device.c (ffffffff81f467aa)
Location: include/linux/netdevice.h:4067
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
```
```
In net/ipv6/route.c (ffffffff81f76cba)
Location: include/linux/netdevice.h:4067
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:ip6_route_check_nh
```
```
In net/ipv6/ip6mr.c (ffffffff81fabb7b)
Location: include/linux/netdevice.h:4067
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mif6_add
```
```
In net/packet/af_packet.c (ffffffff81fc7126)
Location: include/linux/netdevice.h:4067
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81ff2791)
Location: include/linux/netdevice.h:4067
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_assign_dev
```
```
In net/mctp/device.c (ffffffff820115d0)
Location: include/linux/netdevice.h:4067
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_add_dev
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
In drivers/net/tun.c (ffffffff81c4630d)
Location: include/linux/netdevice.h:4126
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_show_fdinfo
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:tun_peek_len
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_chr_read_iter
  - drivers/net/tun.c:tun_chr_write_iter
  - drivers/net/tun.c:tun_chr_poll
```
```
In drivers/net/net_failover.c (ffffffff81c6fb22)
Location: include/linux/netdevice.h:4126
Inline: True
Inline callers:
  - drivers/net/net_failover.c:net_failover_slave_register
```
```
In net/core/dev.c (ffffffff81e40220)
Location: include/linux/netdevice.h:4126
Inline: True
Inline callers:
  - net/core/dev.c:bpf_xdp_link_attach
  - net/core/dev.c:dev_getfirstbyhwtype
  - net/core/dev.c:netdev_get_by_index
  - net/core/dev.c:netdev_get_by_name
```
```
In net/core/neighbour.c (ffffffff81e494e2)
Location: include/linux/netdevice.h:4126
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
```
```
In net/core/lwt_bpf.c (ffffffff81e9ec45)
Location: include/linux/netdevice.h:4126
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_input_reroute
```
```
In net/netlink/af_netlink.c (ffffffff81ec3c96)
Location: include/linux/netdevice.h:4126
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_deliver_tap
```
```
In net/ethtool/netlink.c (ffffffff81ed9a00)
Location: include/linux/netdevice.h:4126
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_dumpit
```
```
In net/netfilter/nf_queue.c (ffffffff81ee95ee)
Location: include/linux/netdevice.h:4126
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
```
```
In net/ipv4/icmp.c (ffffffff81f4cb50)
Location: include/linux/netdevice.h:4126
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_build_probe
```
```
In net/ipv4/devinet.c (ffffffff81f5013b)
Location: include/linux/netdevice.h:4126
Inline: True
Inline callers:
  - net/ipv4/devinet.c:__ip_dev_find
```
```
In net/ipv4/ipmr.c (ffffffff81f7ce9a)
Location: include/linux/netdevice.h:4126
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:ipmr_new_tunnel
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f8cd72)
Location: include/linux/netdevice.h:4126
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_ifdown
```
```
In net/xfrm/xfrm_input.c (ffffffff81fa22ba)
Location: include/linux/netdevice.h:4126
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_device.c (ffffffff81fa60a2)
Location: include/linux/netdevice.h:4126
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
```
```
In net/ipv6/ip6mr.c (ffffffff8200c31b)
Location: include/linux/netdevice.h:4126
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mif6_add
```
```
In net/packet/af_packet.c (ffffffff82027e6b)
Location: include/linux/netdevice.h:4126
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
```
```
In net/xdp/xsk_buff_pool.c (ffffffff8206e9b1)
Location: include/linux/netdevice.h:4126
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_assign_dev
```
```
In net/mctp/device.c (ffffffff8208e3b0)
Location: include/linux/netdevice.h:4126
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_add_dev
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
In drivers/net/tun.c (ffffffff81cfbc1d)
Location: include/linux/netdevice.h:4193
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_show_fdinfo
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:tun_peek_len
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_chr_read_iter
  - drivers/net/tun.c:tun_chr_write_iter
  - drivers/net/tun.c:tun_chr_poll
```
```
In drivers/net/net_failover.c (ffffffff81d243cc)
Location: include/linux/netdevice.h:4193
Inline: True
Inline callers:
  - drivers/net/net_failover.c:net_failover_slave_register
```
```
In net/core/dev.c (ffffffff81efeba8)
Location: include/linux/netdevice.h:4193
Inline: True
Inline callers:
  - net/core/dev.c:bpf_xdp_link_attach
  - net/core/dev.c:dev_getfirstbyhwtype
  - net/core/dev.c:netdev_get_by_index
  - net/core/dev.c:netdev_get_by_name
```
```
In net/core/neighbour.c (ffffffff81f081d2)
Location: include/linux/netdevice.h:4193
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_enqueue
```
```
In net/core/lwt_bpf.c (ffffffff81f613b5)
Location: include/linux/netdevice.h:4193
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_input_reroute
```
```
In net/netlink/af_netlink.c (ffffffff81f87056)
Location: include/linux/netdevice.h:4193
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_deliver_tap
```
```
In net/ethtool/netlink.c (ffffffff81f9d85c)
Location: include/linux/netdevice.h:4193
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_dumpit
```
```
In net/netfilter/nf_queue.c (ffffffff81fad35e)
Location: include/linux/netdevice.h:4193
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
```
```
In net/ipv4/icmp.c (ffffffff82012c60)
Location: include/linux/netdevice.h:4193
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_build_probe
```
```
In net/ipv4/devinet.c (ffffffff820162eb)
Location: include/linux/netdevice.h:4193
Inline: True
Inline callers:
  - net/ipv4/devinet.c:__ip_dev_find
```
```
In net/ipv4/ipmr.c (ffffffff8204359a)
Location: include/linux/netdevice.h:4193
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:ipmr_new_tunnel
```
```
In net/xfrm/xfrm_policy.c (ffffffff8205a702)
Location: include/linux/netdevice.h:4193
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_ifdown
```
```
In net/xfrm/xfrm_input.c (ffffffff8206f6a2)
Location: include/linux/netdevice.h:4193
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_device.c (ffffffff820733c8)
Location: include/linux/netdevice.h:4193
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
```
```
In net/ipv6/ip6mr.c (ffffffff820db2eb)
Location: include/linux/netdevice.h:4193
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mif6_add
```
```
In net/packet/af_packet.c (ffffffff820f76cb)
Location: include/linux/netdevice.h:4193
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
```
```
In net/xdp/xsk_buff_pool.c (ffffffff82142a7e)
Location: include/linux/netdevice.h:4193
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_assign_dev
```
```
In net/mctp/device.c (ffffffff821648a3)
Location: include/linux/netdevice.h:4193
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_add_dev
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
In drivers/net/tun.c (ffff8000109dcd28)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_show_fdinfo
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:tun_peek_len
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_chr_read_iter
  - drivers/net/tun.c:tun_chr_write_iter
  - drivers/net/tun.c:tun_chr_poll
```
```
In net/core/dev.c (ffff800010bd772c)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:dev_getfirstbyhwtype
  - net/core/dev.c:dev_get_by_index
  - net/core/dev.c:dev_get_by_name
```
```
In net/core/ethtool.c (ffff800010bdcb90)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
```
```
In net/core/dst.c (ffff800010be096c)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/core/dst.c:dst_dev_put
```
```
In net/core/neighbour.c (ffff800010be4ccc)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:pneigh_lookup
  - net/core/neighbour.c:___neigh_create
```
```
In net/core/link_watch.c (ffff800010bf3a28)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_fire_event
```
```
In net/core/net-sysfs.c (ffff800010c0c040)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
```
In net/core/netpoll.c (ffff800010c11850)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
```
```
In net/core/drop_monitor.c (ffff800010c1b904)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
```
```
In net/core/lwt_bpf.c (ffff800010c1f198)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_input
```
```
In net/core/devlink.c (ffff800010c306ac)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_flash_update
  - net/core/devlink.c:devlink_compat_running_version
```
```
In net/sched/sch_generic.c (ffff800010c39a14)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_generic.c:__netdev_watchdog_up
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/netlink/af_netlink.c (ffff800010c4b604)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_deliver_tap
```
```
In net/netfilter/nf_queue.c (ffff800010c55b44)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
```
```
In net/ipv4/route.c (ffff800010c5d098)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/route.c:rt_flush_dev
```
```
In net/ipv4/devinet.c (ffff800010ca8f48)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:__ip_dev_find
```
```
In net/ipv4/fib_semantics.c (ffff800010cb7ddc)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_check_nh
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_semantics.c:fib_check_nh_v6_gw
```
```
In net/ipv4/ipmr.c (ffff800010ccd6c0)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:ipmr_new_tunnel
```
```
In net/ipv4/xfrm4_policy.c (ffff800010cd757c)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_fill_dst
```
```
In net/xfrm/xfrm_policy.c (ffff800010cda854)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_ifdown
```
```
In net/xfrm/xfrm_input.c (ffff800010ceaba4)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_device.c (ffff800010cee0f8)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
```
```
In net/ipv6/addrconf.c (ffff800010d034ac)
Location: include/linux/netdevice.h:3749
Inline: True
```
```
In net/ipv6/route.c (ffff800010d17194)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:ip6_route_check_nh
```
```
In net/ipv6/ip6mr.c (ffff800010d46648)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_policy.c (ffff800010d48bc8)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
```
```
In net/packet/af_packet.c (ffff800010d5a76c)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
```
```
In net/switchdev/switchdev.c (ffff800010d73d04)
Location: include/linux/netdevice.h:3749
Inline: True
```
```
In net/xdp/xdp_umem.c (ffff800010d80e70)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_assign_dev
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
In drivers/net/tun.c (c0ac1554)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_show_fdinfo
  - drivers/net/tun.c:tun_peek_len
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_chr_read_iter
  - drivers/net/tun.c:tun_chr_write_iter
  - drivers/net/tun.c:tun_chr_poll
```
```
In net/core/dev.c (c0cf26d8)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:dev_getfirstbyhwtype
  - net/core/dev.c:dev_get_by_index
  - net/core/dev.c:dev_get_by_name
```
```
In net/core/ethtool.c (c0cf7498)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
```
```
In net/core/dst.c (c0cfa92c)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/core/dst.c:dst_dev_put
```
```
In net/core/neighbour.c (c0cfcf70)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:pneigh_lookup
  - net/core/neighbour.c:___neigh_create
```
```
In net/core/link_watch.c (c0d0c370)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_fire_event
```
```
In net/core/net-sysfs.c (c0d24598)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
```
In net/core/netpoll.c (c0d28570)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
```
```
In net/core/drop_monitor.c (c0d3276c)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
```
```
In net/core/lwt_bpf.c (c0d363dc)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_input
```
```
In net/core/devlink.c (c0d4769c)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_flash_update
  - net/core/devlink.c:devlink_compat_running_version
```
```
In net/sched/sch_generic.c (c0d4bd6c)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/netlink/af_netlink.c (c0d5c010)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_deliver_tap
```
```
In net/netfilter/nf_queue.c (c0d6554c)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
```
```
In net/ipv4/route.c (c0d6c820)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/route.c:rt_flush_dev
```
```
In net/ipv4/devinet.c (c0db56ec)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:__ip_dev_find
```
```
In net/ipv4/fib_semantics.c (c0dc2ec4)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_check_nh
  - net/ipv4/fib_semantics.c:fib_check_nh
  - net/ipv4/fib_semantics.c:fib_check_nh
  - net/ipv4/fib_semantics.c:fib_check_nh_v6_gw
```
```
In net/ipv4/ipmr.c (c0dd544c)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:ipmr_new_tunnel
```
```
In net/ipv4/xfrm4_policy.c (c0de0f18)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_fill_dst
```
```
In net/xfrm/xfrm_policy.c (c0de2610)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_ifdown
```
```
In net/xfrm/xfrm_input.c (c0df2e30)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_device.c (c0df5b8c)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
```
```
In net/ipv6/addrconf.c (c0e0a93c)
Location: include/linux/netdevice.h:3749
Inline: True
```
```
In net/ipv6/route.c (c0e1cd54)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:ip6_route_check_nh
```
```
In net/ipv6/ip6mr.c (c0e48c50)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_policy.c (c0e49e38)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
```
```
In net/packet/af_packet.c (c0e57c7c)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
```
```
In net/switchdev/switchdev.c (c0e70258)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_deferred_enqueue
```
```
In net/xdp/xdp_umem.c (c0e7b36c)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_assign_dev
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
In drivers/net/tun.c (c000000000aa2c30)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_show_fdinfo
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:tun_peek_len
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_chr_read_iter
  - drivers/net/tun.c:tun_chr_write_iter
  - drivers/net/tun.c:tun_chr_poll
```
```
In net/core/dev.c (c000000000cb76d0)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:dev_getfirstbyhwtype
  - net/core/dev.c:dev_get_by_index
  - net/core/dev.c:dev_get_by_name
```
```
In net/core/ethtool.c (c000000000cbce80)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
```
```
In net/core/dst.c (c000000000cc1fec)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/core/dst.c:dst_dev_put
```
```
In net/core/neighbour.c (c000000000cc6768)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:pneigh_lookup
  - net/core/neighbour.c:___neigh_create
```
```
In net/core/link_watch.c (c000000000cd8ce8)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_fire_event
```
```
In net/core/net-sysfs.c (c000000000cf7290)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
```
In net/core/netpoll.c (c000000000cfcdb8)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
```
```
In net/core/drop_monitor.c (c000000000d0abb4)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
```
```
In net/core/lwt_bpf.c (c000000000d10150)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_input
```
```
In net/core/devlink.c (c000000000d294f8)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_flash_update
  - net/core/devlink.c:devlink_compat_running_version
```
```
In net/sched/sch_generic.c (c000000000d3286c)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_generic.c:__netdev_watchdog_up
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/netlink/af_netlink.c (c000000000d49808)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_deliver_tap
```
```
In net/netfilter/nf_queue.c (c000000000d56340)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
```
```
In net/ipv4/route.c (c000000000d5f7b8)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/route.c:rt_flush_dev
```
```
In net/ipv4/devinet.c (c000000000dbe168)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:__ip_dev_find
```
```
In net/ipv4/fib_semantics.c (c000000000dd0608)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_check_nh
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_semantics.c:fib_check_nh_v6_gw
```
```
In net/ipv4/ipmr.c (c000000000dec9ac)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:ipmr_new_tunnel
```
```
In net/ipv4/xfrm4_policy.c (c000000000df715c)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_fill_dst
```
```
In net/xfrm/xfrm_policy.c (c000000000df9ad0)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_ifdown
```
```
In net/xfrm/xfrm_input.c (c000000000e0e87c)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_device.c (c000000000e12de0)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
```
```
In net/ipv6/addrconf.c (c000000000e2ced8)
Location: include/linux/netdevice.h:3749
Inline: True
```
```
In net/ipv6/route.c (c000000000e44a50)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:ip6_route_check_nh
```
```
In net/ipv6/ip6mr.c (c000000000e7c0c4)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_policy.c (c000000000e7dbac)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
```
```
In net/packet/af_packet.c (c000000000e918e0)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
```
```
In net/switchdev/switchdev.c (c000000000eb33c0)
Location: include/linux/netdevice.h:3749
Inline: True
```
```
In net/xdp/xdp_umem.c (c000000000ec0b30)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_assign_dev
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
In drivers/net/tun.c (ffffffe0006254c6)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get
```
```
In net/core/dev.c (ffffffe000760d26)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:dev_getfirstbyhwtype
  - net/core/dev.c:dev_get_by_index
  - net/core/dev.c:dev_get_by_name
```
```
In net/core/ethtool.c (ffffffe00076400c)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
```
```
In net/core/dst.c (ffffffe000766b06)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/core/dst.c:dst_dev_put
  - net/core/dst.c:dst_init
```
```
In net/core/neighbour.c (ffffffe0007684a2)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:pneigh_lookup
  - net/core/neighbour.c:___neigh_create
```
```
In net/core/link_watch.c (ffffffe000775140)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_fire_event
```
```
In net/core/net-sysfs.c (ffffffe000789430)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
```
In net/core/netpoll.c (ffffffe00078cbb6)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
```
```
In net/core/drop_monitor.c (ffffffe000794cb0)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
```
```
In net/core/lwt_bpf.c (ffffffe0007980d6)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_input
```
```
In net/core/devlink.c (ffffffe0007a6854)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_flash_update
  - net/core/devlink.c:devlink_compat_running_version
```
```
In net/sched/sch_generic.c (ffffffe0007aadae)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/netlink/af_netlink.c (ffffffe0007b8d04)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_deliver_tap
```
```
In net/netfilter/nf_queue.c (ffffffe0007bffaa)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
```
```
In net/ipv4/route.c (ffffffe0007c5ddc)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/route.c:rt_flush_dev
```
```
In net/ipv4/devinet.c (ffffffe000803c50)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:__ip_dev_find
```
```
In net/ipv4/fib_semantics.c (ffffffe00080ee42)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_check_nh
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_semantics.c:fib_check_nh_v6_gw
```
```
In net/ipv4/ipmr.c (ffffffe00081e09a)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:ipmr_new_tunnel
```
```
In net/ipv4/xfrm4_policy.c (ffffffe000827b38)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_fill_dst
```
```
In net/xfrm/xfrm_policy.c (ffffffe000828efe)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_ifdown
```
```
In net/xfrm/xfrm_input.c (ffffffe000838c6e)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_device.c (ffffffe00083b068)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
```
```
In net/ipv6/addrconf.c (ffffffe00084c772)
Location: include/linux/netdevice.h:3749
Inline: True
```
```
In net/ipv6/route.c (ffffffe00085c394)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:ip6_route_check_nh
```
```
In net/ipv6/ip6mr.c (ffffffe000881126)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_policy.c (ffffffe000881f52)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
```
```
In net/packet/af_packet.c (ffffffe000890d70)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
```
```
In net/switchdev/switchdev.c (ffffffe0008a3f92)
Location: include/linux/netdevice.h:3749
Inline: True
```
```
In net/xdp/xdp_umem.c (ffffffe0008ad3a0)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_assign_dev
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
In drivers/net/tun.c (ffffffff81784e2b)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_show_fdinfo
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:tun_peek_len
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_chr_read_iter
  - drivers/net/tun.c:tun_chr_write_iter
  - drivers/net/tun.c:tun_chr_poll
```
```
In net/core/dev.c (ffffffff818d8d8a)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:dev_getfirstbyhwtype
  - net/core/dev.c:dev_get_by_index
  - net/core/dev.c:dev_get_by_name
```
```
In net/core/ethtool.c (ffffffff818ddcdb)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
```
```
In net/core/dst.c (ffffffff818e0b26)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/core/dst.c:dst_dev_put
```
```
In net/core/neighbour.c (ffffffff818e251b)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:pneigh_lookup
  - net/core/neighbour.c:___neigh_create
```
```
In net/core/link_watch.c (ffffffff818f1b5c)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_fire_event
```
```
In net/core/net-sysfs.c (ffffffff819068cd)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
```
In net/core/netpoll.c (ffffffff8190a41e)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
```
```
In net/core/drop_monitor.c (ffffffff8191478d)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
```
```
In net/core/lwt_bpf.c (ffffffff81917a36)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_input
```
```
In net/core/devlink.c (ffffffff819285bd)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_flash_update
  - net/core/devlink.c:devlink_compat_running_version
```
```
In net/sched/sch_generic.c (ffffffff8192e0bb)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_generic.c:__netdev_watchdog_up
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/netlink/af_netlink.c (ffffffff8193df3b)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_deliver_tap
```
```
In net/netfilter/nf_queue.c (ffffffff819461e9)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
```
```
In net/ipv4/route.c (ffffffff8194ce98)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/route.c:rt_flush_dev
```
```
In net/ipv4/devinet.c (ffffffff81992a05)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:__ip_dev_find
```
```
In net/ipv4/fib_semantics.c (ffffffff8199f62d)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_check_nh
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_semantics.c:fib_check_nh_v6_gw
```
```
In net/ipv4/ipmr.c (ffffffff819afc1e)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:ipmr_new_tunnel
```
```
In net/ipv4/xfrm4_policy.c (ffffffff819ba87d)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_fill_dst
```
```
In net/xfrm/xfrm_policy.c (ffffffff819bbe60)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_ifdown
```
```
In net/xfrm/xfrm_input.c (ffffffff819cbc42)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_device.c (ffffffff819ce317)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
```
```
In net/ipv6/addrconf.c (ffffffff819e10d0)
Location: include/linux/netdevice.h:3749
Inline: True
```
```
In net/ipv6/route.c (ffffffff819f26e1)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:ip6_route_check_nh
```
```
In net/ipv6/ip6mr.c (ffffffff81a1bbca)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81a1d037)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
```
```
In net/packet/af_packet.c (ffffffff81a2c0d0)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
```
```
In net/switchdev/switchdev.c (ffffffff81a41946)
Location: include/linux/netdevice.h:3749
Inline: True
```
```
In net/xdp/xdp_umem.c (ffffffff81a4b91f)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_assign_dev
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
In drivers/net/tun.c (ffffffff8176477b)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_show_fdinfo
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:tun_peek_len
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_chr_read_iter
  - drivers/net/tun.c:tun_chr_write_iter
  - drivers/net/tun.c:tun_chr_poll
```
```
In net/core/dev.c (ffffffff81892bca)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:dev_getfirstbyhwtype
  - net/core/dev.c:dev_get_by_index
  - net/core/dev.c:dev_get_by_name
```
```
In net/core/ethtool.c (ffffffff81897b1b)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
```
```
In net/core/dst.c (ffffffff8189a966)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/core/dst.c:dst_dev_put
```
```
In net/core/neighbour.c (ffffffff8189c35b)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:pneigh_lookup
  - net/core/neighbour.c:___neigh_create
```
```
In net/core/link_watch.c (ffffffff818ab99c)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_fire_event
```
```
In net/core/net-sysfs.c (ffffffff818c06fd)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
```
In net/core/netpoll.c (ffffffff818c42ce)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
```
```
In net/core/drop_monitor.c (ffffffff818ce54d)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
```
```
In net/core/lwt_bpf.c (ffffffff818d17e6)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_input
```
```
In net/core/devlink.c (ffffffff818e236d)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_flash_update
  - net/core/devlink.c:devlink_compat_running_version
```
```
In net/sched/sch_generic.c (ffffffff818e7bbb)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_generic.c:__netdev_watchdog_up
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/netlink/af_netlink.c (ffffffff818f7a3b)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_deliver_tap
```
```
In net/netfilter/nf_queue.c (ffffffff818ffcd9)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
```
```
In net/ipv4/route.c (ffffffff81906988)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/route.c:rt_flush_dev
```
```
In net/ipv4/devinet.c (ffffffff8194c4c5)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:__ip_dev_find
```
```
In net/ipv4/fib_semantics.c (ffffffff819590ed)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_check_nh
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_semantics.c:fib_check_nh_v6_gw
```
```
In net/ipv4/ipmr.c (ffffffff8196c24e)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:ipmr_new_tunnel
```
```
In net/ipv4/xfrm4_policy.c (ffffffff8197766d)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_fill_dst
```
```
In net/xfrm/xfrm_policy.c (ffffffff81978c50)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_ifdown
```
```
In net/xfrm/xfrm_input.c (ffffffff81988a32)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_device.c (ffffffff8198b107)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
```
```
In net/ipv6/addrconf.c (ffffffff8199de90)
Location: include/linux/netdevice.h:3749
Inline: True
```
```
In net/ipv6/route.c (ffffffff819af4a1)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:ip6_route_check_nh
```
```
In net/ipv6/ip6mr.c (ffffffff819d898a)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_policy.c (ffffffff819d9df7)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
```
```
In net/packet/af_packet.c (ffffffff819e92c0)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
```
```
In net/switchdev/switchdev.c (ffffffff819fe536)
Location: include/linux/netdevice.h:3749
Inline: True
```
```
In net/xdp/xdp_umem.c (ffffffff81a0850f)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_assign_dev
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
In drivers/net/tun.c (ffffffff817b51db)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_show_fdinfo
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:tun_peek_len
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_chr_read_iter
  - drivers/net/tun.c:tun_chr_write_iter
  - drivers/net/tun.c:tun_chr_poll
```
```
In net/core/dev.c (ffffffff81929dba)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:dev_getfirstbyhwtype
  - net/core/dev.c:dev_get_by_index
  - net/core/dev.c:dev_get_by_name
```
```
In net/core/ethtool.c (ffffffff8192ed0b)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
```
```
In net/core/dst.c (ffffffff81931b56)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/core/dst.c:dst_dev_put
```
```
In net/core/neighbour.c (ffffffff8193354b)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:pneigh_lookup
  - net/core/neighbour.c:___neigh_create
```
```
In net/core/link_watch.c (ffffffff81942b8c)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_fire_event
```
```
In net/core/net-sysfs.c (ffffffff819578fd)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
```
In net/core/netpoll.c (ffffffff8195b44e)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
```
```
In net/core/drop_monitor.c (ffffffff819657bd)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
```
```
In net/core/lwt_bpf.c (ffffffff81968bc6)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_input
```
```
In net/core/devlink.c (ffffffff8197974d)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_flash_update
  - net/core/devlink.c:devlink_compat_running_version
```
```
In net/sched/sch_generic.c (ffffffff8197f24b)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_generic.c:__netdev_watchdog_up
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/netlink/af_netlink.c (ffffffff8198f0cb)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_deliver_tap
```
```
In net/netfilter/nf_queue.c (ffffffff81997379)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
```
```
In net/ipv4/route.c (ffffffff819b7668)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/route.c:rt_flush_dev
```
```
In net/ipv4/devinet.c (ffffffff819fd2a5)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:__ip_dev_find
```
```
In net/ipv4/fib_semantics.c (ffffffff81a09ecd)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_check_nh
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_semantics.c:fib_check_nh_v6_gw
```
```
In net/ipv4/ipmr.c (ffffffff81a1a4be)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:ipmr_new_tunnel
```
```
In net/ipv4/xfrm4_policy.c (ffffffff81a252fd)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_fill_dst
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a268e0)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_ifdown
```
```
In net/xfrm/xfrm_input.c (ffffffff81a366c2)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_device.c (ffffffff81a38d97)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
```
```
In net/ipv6/addrconf.c (ffffffff81a4bb50)
Location: include/linux/netdevice.h:3749
Inline: True
```
```
In net/ipv6/route.c (ffffffff81a5d161)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:ip6_route_check_nh
```
```
In net/ipv6/ip6mr.c (ffffffff81a8664a)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81a87ab7)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
```
```
In net/packet/af_packet.c (ffffffff81a97c80)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
```
```
In net/switchdev/switchdev.c (ffffffff81aad7f6)
Location: include/linux/netdevice.h:3749
Inline: True
```
```
In net/xdp/xdp_umem.c (ffffffff81ab77cf)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_assign_dev
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
In drivers/net/tun.c (ffffffff817cf11f)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get
```
```
In net/core/dev.c (ffffffff8194b485)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:dev_getfirstbyhwtype
  - net/core/dev.c:dev_get_by_index
  - net/core/dev.c:dev_get_by_name
```
```
In net/core/ethtool.c (ffffffff819503db)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
```
```
In net/core/dst.c (ffffffff81953226)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/core/dst.c:dst_dev_put
```
```
In net/core/neighbour.c (ffffffff81954e7b)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:pneigh_lookup
  - net/core/neighbour.c:___neigh_create
```
```
In net/core/link_watch.c (ffffffff819646bc)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_fire_event
```
```
In net/core/net-sysfs.c (ffffffff819799dd)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
```
In net/core/netpoll.c (ffffffff8197d66e)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
```
```
In net/core/drop_monitor.c (ffffffff819879fd)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
```
```
In net/core/lwt_bpf.c (ffffffff8198afa6)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_input
```
```
In net/core/devlink.c (ffffffff8199bc3d)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_flash_update
  - net/core/devlink.c:devlink_compat_running_version
```
```
In net/sched/sch_generic.c (ffffffff819a17ab)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_generic.c:__netdev_watchdog_up
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/netlink/af_netlink.c (ffffffff819b19b3)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_deliver_tap
```
```
In net/netfilter/nf_queue.c (ffffffff819ba059)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
```
```
In net/ipv4/route.c (ffffffff819c0ef8)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/route.c:rt_flush_dev
```
```
In net/ipv4/devinet.c (ffffffff81a07635)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:__ip_dev_find
```
```
In net/ipv4/fib_semantics.c (ffffffff81a1468c)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_check_nh
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_semantics.c:fib_check_nh_v6_gw
```
```
In net/ipv4/ipmr.c (ffffffff81a252ee)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:ipmr_new_tunnel
```
```
In net/ipv4/xfrm4_policy.c (ffffffff81a3076d)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_fill_dst
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a31d90)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_ifdown
```
```
In net/xfrm/xfrm_input.c (ffffffff81a41ffe)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_device.c (ffffffff81a447b7)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
```
```
In net/ipv6/addrconf.c (ffffffff81a57ac0)
Location: include/linux/netdevice.h:3749
Inline: True
```
```
In net/ipv6/route.c (ffffffff81a6954a)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:ip6_route_check_nh
```
```
In net/ipv6/ip6mr.c (ffffffff81a9320a)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81a946b7)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
```
```
In net/packet/af_packet.c (ffffffff81aa1bd5)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
```
```
In net/switchdev/switchdev.c (ffffffff81ab9b66)
Location: include/linux/netdevice.h:3749
Inline: True
```
```
In net/xdp/xdp_umem.c (ffffffff81ac3bef)
Location: include/linux/netdevice.h:3749
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_assign_dev
```
</details>
</li>
</ul>

## Differences
