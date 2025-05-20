# Function: <code>netif_carrier_ok</code>

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
In drivers/net/xen-netfront.c (ffffffff815fa94d)
Location: include/linux/netdevice.h:3147
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
  - drivers/net/xen-netfront.c:xennet_rx_interrupt
  - drivers/net/xen-netfront.c:xennet_open
```
```
In net/core/dev.c (ffffffff81713afc)
Location: include/linux/netdevice.h:3147
Inline: True
Inline callers:
  - net/core/dev.c:dev_get_flags
```
```
In net/core/ethtool.c (ffffffff8171f145)
Location: include/linux/netdevice.h:3147
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_op_get_link
```
```
In net/core/rtnetlink.c (ffffffff8172e350)
Location: include/linux/netdevice.h:3147
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/link_watch.c (ffffffff817304bc)
Location: include/linux/netdevice.h:3147
Inline: True
Inline callers:
  - net/core/link_watch.c:rfc2863_policy
  - net/core/link_watch.c:linkwatch_do_dev
  - net/core/link_watch.c:linkwatch_init_dev
```
```
In net/core/net-sysfs.c (ffffffff817356a8)
Location: include/linux/netdevice.h:3147
Inline: True
Inline callers:
  - net/core/net-sysfs.c:carrier_show
```
```
In net/core/netpoll.c (ffffffff8173884e)
Location: include/linux/netdevice.h:3147
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
```
```
In net/sched/sch_generic.c (ffffffff8174112c)
Location: include/linux/netdevice.h:3147
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/ipv4/fib_semantics.c (ffffffff8179d7cc)
Location: include/linux/netdevice.h:3147
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv6/route.c (ffffffff817d55ce)
Location: include/linux/netdevice.h:3147
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81803763)
Location: include/linux/netdevice.h:3147
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
In drivers/net/xen-netfront.c (ffffffff8165d26d)
Location: include/linux/netdevice.h:3375
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_rx_interrupt
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_open
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
```
In net/core/dev.c (ffffffff8177b8fc)
Location: include/linux/netdevice.h:3375
Inline: True
Inline callers:
  - net/core/dev.c:dev_get_flags
```
```
In net/core/ethtool.c (ffffffff81787a65)
Location: include/linux/netdevice.h:3375
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_op_get_link
```
```
In net/core/rtnetlink.c (ffffffff81797c79)
Location: include/linux/netdevice.h:3375
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/link_watch.c (ffffffff8179acd0)
Location: include/linux/netdevice.h:3375
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_do_dev
  - net/core/link_watch.c:linkwatch_init_dev
  - net/core/link_watch.c:rfc2863_policy
```
```
In net/core/net-sysfs.c (ffffffff817a17f8)
Location: include/linux/netdevice.h:3375
Inline: True
Inline callers:
  - net/core/net-sysfs.c:carrier_show
```
```
In net/core/netpoll.c (ffffffff817a4b43)
Location: include/linux/netdevice.h:3375
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
```
```
In net/sched/sch_generic.c (ffffffff817adf4c)
Location: include/linux/netdevice.h:3375
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/ipv4/fib_semantics.c (ffffffff8180b03d)
Location: include/linux/netdevice.h:3375
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv6/route.c (ffffffff8184217f)
Location: include/linux/netdevice.h:3375
Inline: True
```
```
In net/packet/af_packet.c (ffffffff818749a3)
Location: include/linux/netdevice.h:3375
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
In drivers/net/xen-netfront.c (ffffffff8168b06d)
Location: include/linux/netdevice.h:3329
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_rx_interrupt
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_open
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
```
In net/core/dev.c (ffffffff817a909c)
Location: include/linux/netdevice.h:3329
Inline: True
Inline callers:
  - net/core/dev.c:dev_get_flags
```
```
In net/core/ethtool.c (ffffffff817b5025)
Location: include/linux/netdevice.h:3329
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_op_get_link
```
```
In net/core/rtnetlink.c (ffffffff817c59fd)
Location: include/linux/netdevice.h:3329
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/link_watch.c (ffffffff817c8a70)
Location: include/linux/netdevice.h:3329
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_do_dev
  - net/core/link_watch.c:linkwatch_init_dev
  - net/core/link_watch.c:rfc2863_policy
```
```
In net/core/net-sysfs.c (ffffffff817d0118)
Location: include/linux/netdevice.h:3329
Inline: True
Inline callers:
  - net/core/net-sysfs.c:carrier_show
```
```
In net/core/netpoll.c (ffffffff817d35b3)
Location: include/linux/netdevice.h:3329
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
```
```
In net/sched/sch_generic.c (ffffffff817dd5cc)
Location: include/linux/netdevice.h:3329
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/ipv4/fib_semantics.c (ffffffff8183c14b)
Location: include/linux/netdevice.h:3329
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv6/route.c (ffffffff81873ecf)
Location: include/linux/netdevice.h:3329
Inline: True
```
```
In net/packet/af_packet.c (ffffffff818a8eff)
Location: include/linux/netdevice.h:3329
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
In drivers/net/xen-netfront.c (ffffffff816a02bd)
Location: include/linux/netdevice.h:3375
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_rx_interrupt
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_open
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
```
In net/core/dev.c (ffffffff817ca072)
Location: include/linux/netdevice.h:3375
Inline: True
Inline callers:
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:dev_get_flags
```
```
In net/core/ethtool.c (ffffffff817d3b95)
Location: include/linux/netdevice.h:3375
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_op_get_link
```
```
In net/core/rtnetlink.c (ffffffff817e4386)
Location: include/linux/netdevice.h:3375
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/link_watch.c (ffffffff817e7640)
Location: include/linux/netdevice.h:3375
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_do_dev
  - net/core/link_watch.c:linkwatch_init_dev
  - net/core/link_watch.c:rfc2863_policy
```
```
In net/core/net-sysfs.c (ffffffff817ef848)
Location: include/linux/netdevice.h:3375
Inline: True
Inline callers:
  - net/core/net-sysfs.c:carrier_show
```
```
In net/core/netpoll.c (ffffffff817f28e3)
Location: include/linux/netdevice.h:3375
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
```
```
In net/sched/sch_generic.c (ffffffff817fcc0b)
Location: include/linux/netdevice.h:3375
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/ipv4/fib_semantics.c (ffffffff8185c907)
Location: include/linux/netdevice.h:3375
Inline: True
```
```
In net/ipv6/route.c (ffffffff81897ef6)
Location: include/linux/netdevice.h:3375
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_nexthop_info
```
```
In net/packet/af_packet.c (ffffffff818cf88f)
Location: include/linux/netdevice.h:3375
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
In drivers/net/xen-netfront.c (ffffffff8170b47d)
Location: include/linux/netdevice.h:3404
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_rx_interrupt
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_open
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
```
In net/core/dev.c (ffffffff81843992)
Location: include/linux/netdevice.h:3404
Inline: True
Inline callers:
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:dev_get_flags
```
```
In net/core/ethtool.c (ffffffff8184e085)
Location: include/linux/netdevice.h:3404
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_op_get_link
```
```
In net/core/rtnetlink.c (ffffffff8185f46d)
Location: include/linux/netdevice.h:3404
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/link_watch.c (ffffffff81862580)
Location: include/linux/netdevice.h:3404
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_do_dev
  - net/core/link_watch.c:linkwatch_init_dev
  - net/core/link_watch.c:rfc2863_policy
```
```
In net/core/net-sysfs.c (ffffffff8186ade8)
Location: include/linux/netdevice.h:3404
Inline: True
Inline callers:
  - net/core/net-sysfs.c:carrier_show
```
```
In net/core/netpoll.c (ffffffff8186dea3)
Location: include/linux/netdevice.h:3404
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
```
```
In net/sched/sch_generic.c (ffffffff8187a75b)
Location: include/linux/netdevice.h:3404
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/ipv4/fib_semantics.c (ffffffff818dc7f7)
Location: include/linux/netdevice.h:3404
Inline: True
```
```
In net/ipv6/route.c (ffffffff8191927f)
Location: include/linux/netdevice.h:3404
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_nexthop_info
  - net/ipv6/route.c:rt6_multipath_select
```
```
In net/ipv6/seg6_local.c (ffffffff8194fcf0)
Location: include/linux/netdevice.h:3404
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
```
```
In net/packet/af_packet.c (ffffffff819547ff)
Location: include/linux/netdevice.h:3404
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
In drivers/net/xen-netfront.c (ffffffff8174a16d)
Location: include/linux/netdevice.h:3510
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_rx_interrupt
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
```
In net/core/dev.c (ffffffff8188dd44)
Location: include/linux/netdevice.h:3510
Inline: True
Inline callers:
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:dev_get_flags
  - net/core/dev.c:dev_direct_xmit
```
```
In net/core/ethtool.c (ffffffff818992a5)
Location: include/linux/netdevice.h:3510
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_op_get_link
```
```
In net/core/rtnetlink.c (ffffffff818ab5c6)
Location: include/linux/netdevice.h:3510
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/link_watch.c (ffffffff818ae230)
Location: include/linux/netdevice.h:3510
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_do_dev
  - net/core/link_watch.c:linkwatch_init_dev
  - net/core/link_watch.c:rfc2863_policy
```
```
In net/core/net-sysfs.c (ffffffff818bb6b8)
Location: include/linux/netdevice.h:3510
Inline: True
Inline callers:
  - net/core/net-sysfs.c:carrier_show
```
```
In net/core/netpoll.c (ffffffff818bfe60)
Location: include/linux/netdevice.h:3510
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
```
```
In net/sched/sch_generic.c (ffffffff818cc73b)
Location: include/linux/netdevice.h:3510
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/ipv4/fib_semantics.c (ffffffff8193337c)
Location: include/linux/netdevice.h:3510
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_check_nh
  - net/ipv4/fib_semantics.c:fib_check_nh
  - net/ipv4/fib_semantics.c:fib_check_nh
```
```
In net/ipv6/route.c (ffffffff819787f0)
Location: include/linux/netdevice.h:3510
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_sync_up
  - net/ipv6/route.c:ip6_route_info_create
```
```
In net/ipv6/seg6_local.c (ffffffff819a8b92)
Location: include/linux/netdevice.h:3510
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
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
In drivers/net/xen-netfront.c (ffffffff8176e2fd)
Location: include/linux/netdevice.h:3736
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_rx_interrupt
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
```
In net/core/dev.c (ffffffff818aebd4)
Location: include/linux/netdevice.h:3736
Inline: True
Inline callers:
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:dev_get_flags
  - net/core/dev.c:dev_direct_xmit
```
```
In net/core/ethtool.c (ffffffff818bb755)
Location: include/linux/netdevice.h:3736
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_op_get_link
```
```
In net/core/rtnetlink.c (ffffffff818cf055)
Location: include/linux/netdevice.h:3736
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/link_watch.c (ffffffff818d24a8)
Location: include/linux/netdevice.h:3736
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_do_dev
  - net/core/link_watch.c:linkwatch_init_dev
  - net/core/link_watch.c:rfc2863_policy
```
```
In net/core/net-sysfs.c (ffffffff818e2448)
Location: include/linux/netdevice.h:3736
Inline: True
Inline callers:
  - net/core/net-sysfs.c:carrier_show
```
```
In net/core/netpoll.c (ffffffff818e8c7b)
Location: include/linux/netdevice.h:3736
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
```
```
In net/sched/sch_generic.c (ffffffff818f7a8b)
Location: include/linux/netdevice.h:3736
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/ipv4/arp.c (ffffffff8195059f)
Location: include/linux/netdevice.h:3736
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_netdev_event
```
```
In net/ipv4/fib_semantics.c (ffffffff819639c4)
Location: include/linux/netdevice.h:3736
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv6/route.c (ffffffff819ae3f0)
Location: include/linux/netdevice.h:3736
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_sync_up
  - net/ipv6/route.c:ip6_route_info_create
```
```
In net/ipv6/ndisc.c (ffffffff819b6b99)
Location: include/linux/netdevice.h:3736
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_netdev_event
```
```
In net/ipv6/seg6_local.c (ffffffff819df6bc)
Location: include/linux/netdevice.h:3736
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
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
In drivers/net/xen-netfront.c (ffffffff817ab2ed)
Location: include/linux/netdevice.h:3757
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_rx_interrupt
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
```
In net/core/dev.c (ffffffff818fa7a4)
Location: include/linux/netdevice.h:3757
Inline: True
Inline callers:
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:dev_get_flags
  - net/core/dev.c:dev_direct_xmit
```
```
In net/core/ethtool.c (ffffffff81907715)
Location: include/linux/netdevice.h:3757
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_op_get_link
```
```
In net/core/rtnetlink.c (ffffffff8191bdc4)
Location: include/linux/netdevice.h:3757
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/link_watch.c (ffffffff8191f748)
Location: include/linux/netdevice.h:3757
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_do_dev
  - net/core/link_watch.c:linkwatch_init_dev
  - net/core/link_watch.c:rfc2863_policy
```
```
In net/core/net-sysfs.c (ffffffff81931df4)
Location: include/linux/netdevice.h:3757
Inline: True
Inline callers:
  - net/core/net-sysfs.c:carrier_show
```
```
In net/core/netpoll.c (ffffffff81938656)
Location: include/linux/netdevice.h:3757
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
```
```
In net/sched/sch_generic.c (ffffffff819571cd)
Location: include/linux/netdevice.h:3757
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/ipv4/arp.c (ffffffff819b4e52)
Location: include/linux/netdevice.h:3757
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_netdev_event
```
```
In net/ipv4/fib_semantics.c (ffffffff819c8cda)
Location: include/linux/netdevice.h:3757
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_check_nh
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
```
```
In net/ipv4/nexthop.c (ffffffff819d435b)
Location: include/linux/netdevice.h:3757
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv6/route.c (ffffffff81a1c24b)
Location: include/linux/netdevice.h:3757
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_sync_up
  - net/ipv6/route.c:fib6_nh_init
```
```
In net/ipv6/ndisc.c (ffffffff81a2561b)
Location: include/linux/netdevice.h:3757
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_netdev_event
```
```
In net/ipv6/seg6_local.c (ffffffff81a4e253)
Location: include/linux/netdevice.h:3757
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
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
In drivers/net/xen-netfront.c (ffffffff817ced2d)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_rx_interrupt
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
```
In net/core/dev.c (ffffffff8192c8e4)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:dev_get_flags
  - net/core/dev.c:dev_direct_xmit
```
```
In net/core/ethtool.c (ffffffff81939cc5)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_op_get_link
```
```
In net/core/rtnetlink.c (ffffffff8194e3ed)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/link_watch.c (ffffffff81951988)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_do_dev
  - net/core/link_watch.c:linkwatch_init_dev
  - net/core/link_watch.c:rfc2863_policy
```
```
In net/core/net-sysfs.c (ffffffff81964934)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/core/net-sysfs.c:carrier_show
```
```
In net/core/netpoll.c (ffffffff8196b516)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
```
```
In net/sched/sch_generic.c (ffffffff8198d66d)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/ipv4/arp.c (ffffffff819ebb82)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_netdev_event
```
```
In net/ipv4/fib_semantics.c (ffffffff819ff89a)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_check_nh
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
```
```
In net/ipv4/nexthop.c (ffffffff81a0aecb)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv6/route.c (ffffffff81a52ecb)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_sync_up
  - net/ipv6/route.c:fib6_nh_init
```
```
In net/ipv6/ndisc.c (ffffffff81a5c09b)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_netdev_event
```
```
In net/ipv6/seg6_local.c (ffffffff81a84eb3)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
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
In drivers/net/xen-netfront.c (ffffffff8189a4ed)
Location: include/linux/netdevice.h:3886
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:xennet_poll_controller
  - drivers/net/xen-netfront.c:xennet_rx_interrupt
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_open
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
```
In net/core/dev.c (ffffffff819fffb7)
Location: include/linux/netdevice.h:3886
Inline: True
Inline callers:
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:dev_get_flags
  - net/core/dev.c:dev_direct_xmit
```
```
In net/core/rtnetlink.c (ffffffff81a1ff74)
Location: include/linux/netdevice.h:3886
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/link_watch.c (ffffffff81a229e8)
Location: include/linux/netdevice.h:3886
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_do_dev
  - net/core/link_watch.c:linkwatch_init_dev
  - net/core/link_watch.c:rfc2863_policy
```
```
In net/core/net-sysfs.c (ffffffff81a37424)
Location: include/linux/netdevice.h:3886
Inline: True
Inline callers:
  - net/core/net-sysfs.c:carrier_show
```
```
In net/core/netpoll.c (ffffffff81a3f0ae)
Location: include/linux/netdevice.h:3886
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
```
```
In net/sched/sch_generic.c (ffffffff81a65360)
Location: include/linux/netdevice.h:3886
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/ethtool/ioctl.c (ffffffff81a7f415)
Location: include/linux/netdevice.h:3886
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_op_get_link
```
```
In net/ipv4/arp.c (ffffffff81ad9484)
Location: include/linux/netdevice.h:3886
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_netdev_event
```
```
In net/ipv4/fib_semantics.c (ffffffff81aeedea)
Location: include/linux/netdevice.h:3886
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_check_nh
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
```
```
In net/ipv4/nexthop.c (ffffffff81afb89c)
Location: include/linux/netdevice.h:3886
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv6/route.c (ffffffff81b4a52b)
Location: include/linux/netdevice.h:3886
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_sync_up
  - net/ipv6/route.c:fib6_nh_init
```
```
In net/ipv6/ndisc.c (ffffffff81b55e7d)
Location: include/linux/netdevice.h:3886
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_netdev_event
```
```
In net/ipv6/seg6_local.c (ffffffff81b7ff33)
Location: include/linux/netdevice.h:3886
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
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
In drivers/net/xen-netfront.c (ffffffff818a84ca)
Location: include/linux/netdevice.h:4054
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:xennet_poll_controller
  - drivers/net/xen-netfront.c:xennet_rx_interrupt
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_xdp_xmit_one
  - drivers/net/xen-netfront.c:xennet_open
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
```
In net/core/dev.c (ffffffff819ffff7)
Location: include/linux/netdevice.h:4054
Inline: True
Inline callers:
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:dev_get_flags
  - net/core/dev.c:__dev_direct_xmit
```
```
In net/core/rtnetlink.c (ffffffff81a208f4)
Location: include/linux/netdevice.h:4054
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/link_watch.c (ffffffff81a22d48)
Location: include/linux/netdevice.h:4054
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_do_dev
  - net/core/link_watch.c:linkwatch_init_dev
  - net/core/link_watch.c:rfc2863_policy
```
```
In net/core/net-sysfs.c (ffffffff81a39804)
Location: include/linux/netdevice.h:4054
Inline: True
Inline callers:
  - net/core/net-sysfs.c:carrier_show
```
```
In net/core/netpoll.c (ffffffff81c31abe)
Location: include/linux/netdevice.h:4054
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
```
```
In net/sched/sch_generic.c (ffffffff81a6d490)
Location: include/linux/netdevice.h:4054
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/ethtool/ioctl.c (ffffffff81a88eb5)
Location: include/linux/netdevice.h:4054
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_op_get_link
```
```
In net/ipv4/arp.c (ffffffff81ae5ee4)
Location: include/linux/netdevice.h:4054
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_netdev_event
```
```
In net/ipv4/fib_semantics.c (ffffffff81afbd4c)
Location: include/linux/netdevice.h:4054
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_check_nh
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
```
```
In net/ipv4/nexthop.c (ffffffff81b08f6c)
Location: include/linux/netdevice.h:4054
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv6/route.c (ffffffff81b591ab)
Location: include/linux/netdevice.h:4054
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_sync_up
  - net/ipv6/route.c:fib6_nh_init
```
```
In net/ipv6/ndisc.c (ffffffff81b64492)
Location: include/linux/netdevice.h:4054
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_netdev_event
```
```
In net/ipv6/seg6_local.c (ffffffff81b8f3b3)
Location: include/linux/netdevice.h:4054
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
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
In drivers/net/xen-netfront.c (ffffffff8188ab8d)
Location: include/linux/netdevice.h:4184
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_rx_interrupt
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_open
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
```
In net/core/dev.c (ffffffff819e6557)
Location: include/linux/netdevice.h:4184
Inline: True
Inline callers:
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:dev_get_flags
  - net/core/dev.c:__dev_direct_xmit
```
```
In net/core/rtnetlink.c (ffffffff81a079c2)
Location: include/linux/netdevice.h:4184
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/link_watch.c (ffffffff81a09fb0)
Location: include/linux/netdevice.h:4184
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_do_dev
  - net/core/link_watch.c:linkwatch_init_dev
  - net/core/link_watch.c:rfc2863_policy
```
```
In net/core/net-sysfs.c (ffffffff81a20a37)
Location: include/linux/netdevice.h:4184
Inline: True
Inline callers:
  - net/core/net-sysfs.c:carrier_show
```
```
In net/core/netpoll.c (ffffffff81c23d86)
Location: include/linux/netdevice.h:4184
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
```
```
In net/core/selftests.c (ffffffff81a35f65)
Location: include/linux/netdevice.h:4184
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_netif_carrier
```
```
In net/sched/sch_generic.c (ffffffff81a55d10)
Location: include/linux/netdevice.h:4184
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/ethtool/ioctl.c (ffffffff81a72525)
Location: include/linux/netdevice.h:4184
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_op_get_link
```
```
In net/ipv4/arp.c (ffffffff81ad11c4)
Location: include/linux/netdevice.h:4184
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_netdev_event
```
```
In net/ipv4/fib_semantics.c (ffffffff81ae74ac)
Location: include/linux/netdevice.h:4184
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_check_nh
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
```
```
In net/ipv4/nexthop.c (ffffffff81af565b)
Location: include/linux/netdevice.h:4184
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv6/route.c (ffffffff81b4709b)
Location: include/linux/netdevice.h:4184
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_sync_up
  - net/ipv6/route.c:fib6_nh_init
```
```
In net/ipv6/ndisc.c (ffffffff81b5275e)
Location: include/linux/netdevice.h:4184
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_netdev_event
```
```
In net/ipv6/seg6_local.c (ffffffff81b7e123)
Location: include/linux/netdevice.h:4184
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
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
In drivers/net/xen-netfront.c (ffffffff8191e1f4)
Location: include/linux/netdevice.h:4207
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_handle_rx
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_tx_buf_gc
  - drivers/net/xen-netfront.c:xennet_open
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
```
In net/core/dev.c (ffffffff81a96a87)
Location: include/linux/netdevice.h:4207
Inline: True
Inline callers:
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:dev_get_flags
  - net/core/dev.c:__dev_direct_xmit
```
```
In net/core/rtnetlink.c (ffffffff81ab9e2d)
Location: include/linux/netdevice.h:4207
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/link_watch.c (ffffffff81abc4b0)
Location: include/linux/netdevice.h:4207
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_do_dev
  - net/core/link_watch.c:linkwatch_init_dev
  - net/core/link_watch.c:rfc2863_policy
```
```
In net/core/net-sysfs.c (ffffffff81ad4eb7)
Location: include/linux/netdevice.h:4207
Inline: True
Inline callers:
  - net/core/net-sysfs.c:carrier_show
```
```
In net/core/netpoll.c (ffffffff81d37bee)
Location: include/linux/netdevice.h:4207
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
```
```
In net/core/selftests.c (ffffffff81aebbb5)
Location: include/linux/netdevice.h:4207
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_netif_carrier
```
```
In net/sched/sch_generic.c (ffffffff81b0eaa2)
Location: include/linux/netdevice.h:4207
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/ethtool/ioctl.c (ffffffff81b2c0c5)
Location: include/linux/netdevice.h:4207
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_op_get_link
```
```
In net/ipv4/arp.c (ffffffff81b8fbe4)
Location: include/linux/netdevice.h:4207
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_netdev_event
```
```
In net/ipv4/fib_semantics.c (ffffffff81ba72f1)
Location: include/linux/netdevice.h:4207
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_check_nh
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
```
```
In net/ipv4/nexthop.c (ffffffff81bb5f5b)
Location: include/linux/netdevice.h:4207
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv6/route.c (ffffffff81c0e2eb)
Location: include/linux/netdevice.h:4207
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_sync_up
  - net/ipv6/route.c:fib6_nh_init
```
```
In net/ipv6/ndisc.c (ffffffff81c19c6e)
Location: include/linux/netdevice.h:4207
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_netdev_event
```
```
In net/ipv6/seg6_local.c (ffffffff81c49743)
Location: include/linux/netdevice.h:4207
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
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
In drivers/net/xen-netfront.c (ffffffff81a726d7)
Location: include/linux/netdevice.h:4071
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_handle_rx
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_tx_buf_gc
  - drivers/net/xen-netfront.c:xennet_open
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
```
In net/core/dev.c (ffffffff81c0d958)
Location: include/linux/netdevice.h:4071
Inline: True
Inline callers:
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:dev_get_flags
  - net/core/dev.c:__dev_direct_xmit
```
```
In net/core/rtnetlink.c (ffffffff81c3444e)
Location: include/linux/netdevice.h:4071
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/link_watch.c (ffffffff81c36df0)
Location: include/linux/netdevice.h:4071
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_do_dev
  - net/core/link_watch.c:linkwatch_init_dev
  - net/core/link_watch.c:rfc2863_policy
```
```
In net/core/net-sysfs.c (ffffffff81c550f7)
Location: include/linux/netdevice.h:4071
Inline: True
Inline callers:
  - net/core/net-sysfs.c:carrier_show
```
```
In net/core/netpoll.c (ffffffff81f045d1)
Location: include/linux/netdevice.h:4071
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
```
```
In net/core/selftests.c (ffffffff81c6e4f5)
Location: include/linux/netdevice.h:4071
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_netif_carrier
```
```
In net/sched/sch_generic.c (ffffffff81c96c6e)
Location: include/linux/netdevice.h:4071
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_activate
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/ethtool/ioctl.c (ffffffff81cb6b85)
Location: include/linux/netdevice.h:4071
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_op_get_link
```
```
In net/ipv4/arp.c (ffffffff81d20f7d)
Location: include/linux/netdevice.h:4071
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_netdev_event
```
```
In net/ipv4/fib_semantics.c (ffffffff81d39c53)
Location: include/linux/netdevice.h:4071
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_check_nh
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
```
```
In net/ipv4/nexthop.c (ffffffff81d49807)
Location: include/linux/netdevice.h:4071
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv6/route.c (ffffffff81da93c2)
Location: include/linux/netdevice.h:4071
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_sync_up
  - net/ipv6/route.c:fib6_nh_init
```
```
In net/ipv6/ndisc.c (ffffffff81db61ce)
Location: include/linux/netdevice.h:4071
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_netdev_event
```
```
In net/ipv6/seg6_local.c (ffffffff81de8f2d)
Location: include/linux/netdevice.h:4071
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
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
In drivers/net/xen-netfront.c (ffffffff81c06107)
Location: include/linux/netdevice.h:4115
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_handle_rx
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_tx_buf_gc
  - drivers/net/xen-netfront.c:xennet_open
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
```
In net/core/dev.c (ffffffff81dc10c8)
Location: include/linux/netdevice.h:4115
Inline: True
Inline callers:
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:dev_get_flags
  - net/core/dev.c:__dev_direct_xmit
```
```
In net/core/rtnetlink.c (ffffffff81de78fd)
Location: include/linux/netdevice.h:4115
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/link_watch.c (ffffffff81dea7fd)
Location: include/linux/netdevice.h:4115
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_do_dev
  - net/core/link_watch.c:linkwatch_init_dev
  - net/core/link_watch.c:rfc2863_policy
  - net/core/link_watch.c:rfc2863_policy
```
```
In net/core/net-sysfs.c (ffffffff81e0a987)
Location: include/linux/netdevice.h:4115
Inline: True
Inline callers:
  - net/core/net-sysfs.c:carrier_show
```
```
In net/core/netpoll.c (ffffffff81e127f5)
Location: include/linux/netdevice.h:4115
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
```
```
In net/core/selftests.c (ffffffff81e26285)
Location: include/linux/netdevice.h:4115
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_netif_carrier
```
```
In net/sched/sch_generic.c (ffffffff81e52a2e)
Location: include/linux/netdevice.h:4115
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_activate
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/ethtool/ioctl.c (ffffffff81e75355)
Location: include/linux/netdevice.h:4115
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_op_get_link
```
```
In net/ipv4/arp.c (ffffffff81ee82fd)
Location: include/linux/netdevice.h:4115
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_netdev_event
```
```
In net/ipv4/fib_semantics.c (ffffffff81f02583)
Location: include/linux/netdevice.h:4115
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_check_nh
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
```
```
In net/ipv4/nexthop.c (ffffffff81f12e47)
Location: include/linux/netdevice.h:4115
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv6/route.c (ffffffff81f78b56)
Location: include/linux/netdevice.h:4115
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_sync_up
  - net/ipv6/route.c:fib6_nh_init
```
```
In net/ipv6/ndisc.c (ffffffff81f85e2e)
Location: include/linux/netdevice.h:4115
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_netdev_event
```
```
In net/ipv6/seg6_local.c (ffffffff81fbc65d)
Location: include/linux/netdevice.h:4115
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
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
In drivers/net/xen-netfront.c (ffffffff81c6b7f7)
Location: include/linux/netdevice.h:4174
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_handle_rx
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_tx_buf_gc
  - drivers/net/xen-netfront.c:xennet_open
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
```
In drivers/net/net_failover.c (ffffffff81c6f970)
Location: include/linux/netdevice.h:4174
Inline: True
Inline callers:
  - drivers/net/net_failover.c:net_failover_lower_state_changed
  - drivers/net/net_failover.c:net_failover_xmit_ready
```
```
In net/core/dev.c (ffffffff81e30d18)
Location: include/linux/netdevice.h:4174
Inline: True
Inline callers:
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:dev_get_flags
  - net/core/dev.c:__dev_direct_xmit
```
```
In net/core/rtnetlink.c (ffffffff81e59394)
Location: include/linux/netdevice.h:4174
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/link_watch.c (ffffffff81e5bfdd)
Location: include/linux/netdevice.h:4174
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_do_dev
  - net/core/link_watch.c:linkwatch_init_dev
  - net/core/link_watch.c:rfc2863_policy
  - net/core/link_watch.c:rfc2863_policy
```
```
In net/core/net-sysfs.c (ffffffff81e7dd17)
Location: include/linux/netdevice.h:4174
Inline: True
Inline callers:
  - net/core/net-sysfs.c:carrier_show
```
```
In net/core/netpoll.c (ffffffff81e8602b)
Location: include/linux/netdevice.h:4174
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
```
```
In net/core/selftests.c (ffffffff81e9b825)
Location: include/linux/netdevice.h:4174
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_netif_carrier
```
```
In net/sched/sch_generic.c (ffffffff81eae28e)
Location: include/linux/netdevice.h:4174
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_activate
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/ethtool/ioctl.c (ffffffff81ed1535)
Location: include/linux/netdevice.h:4174
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_op_get_link
```
```
In net/ipv4/arp.c (ffffffff81f47bcf)
Location: include/linux/netdevice.h:4174
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_netdev_event
```
```
In net/ipv4/fib_semantics.c (ffffffff81f61fe3)
Location: include/linux/netdevice.h:4174
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_check_nh
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
```
```
In net/ipv4/nexthop.c (ffffffff81f72b0e)
Location: include/linux/netdevice.h:4174
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv6/route.c (ffffffff81fd8d46)
Location: include/linux/netdevice.h:4174
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_sync_up
  - net/ipv6/route.c:fib6_nh_init
```
```
In net/ipv6/ndisc.c (ffffffff81fe61ee)
Location: include/linux/netdevice.h:4174
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_netdev_event
```
```
In net/ipv6/seg6_local.c (ffffffff8201cf4d)
Location: include/linux/netdevice.h:4174
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
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
In drivers/net/xen-netfront.c (ffffffff81d201c7)
Location: include/linux/netdevice.h:4250
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_handle_rx
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_tx_buf_gc
  - drivers/net/xen-netfront.c:xennet_open
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
```
In drivers/net/net_failover.c (ffffffff81d24220)
Location: include/linux/netdevice.h:4250
Inline: True
Inline callers:
  - drivers/net/net_failover.c:net_failover_lower_state_changed
  - drivers/net/net_failover.c:net_failover_xmit_ready
```
```
In net/core/dev.c (ffffffff81eef2ae)
Location: include/linux/netdevice.h:4250
Inline: True
Inline callers:
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:dev_get_flags
  - net/core/dev.c:__dev_direct_xmit
```
```
In net/core/rtnetlink.c (ffffffff81f186be)
Location: include/linux/netdevice.h:4250
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/link_watch.c (ffffffff81f1b3b0)
Location: include/linux/netdevice.h:4250
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_do_dev
  - net/core/link_watch.c:linkwatch_init_dev
  - net/core/link_watch.c:rfc2863_policy
  - net/core/link_watch.c:rfc2863_policy
```
```
In net/core/net-sysfs.c (ffffffff81f413a4)
Location: include/linux/netdevice.h:4250
Inline: True
Inline callers:
  - net/core/net-sysfs.c:carrier_show
```
```
In net/core/netpoll.c (ffffffff81f4802e)
Location: include/linux/netdevice.h:4250
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
```
```
In net/core/selftests.c (ffffffff81f5df95)
Location: include/linux/netdevice.h:4250
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_netif_carrier
```
```
In net/sched/sch_generic.c (ffffffff81f70cfe)
Location: include/linux/netdevice.h:4250
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_activate
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/ethtool/ioctl.c (ffffffff81f95012)
Location: include/linux/netdevice.h:4250
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_op_get_link
```
```
In net/ipv4/arp.c (ffffffff8200dd0f)
Location: include/linux/netdevice.h:4250
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_netdev_event
```
```
In net/ipv4/fib_semantics.c (ffffffff820285b3)
Location: include/linux/netdevice.h:4250
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_check_nh
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
```
```
In net/ipv4/nexthop.c (ffffffff82038cb1)
Location: include/linux/netdevice.h:4250
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv6/route.c (ffffffff820a66d6)
Location: include/linux/netdevice.h:4250
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_sync_up
  - net/ipv6/route.c:fib6_nh_init
```
```
In net/ipv6/ndisc.c (ffffffff820b404e)
Location: include/linux/netdevice.h:4250
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_netdev_event
```
```
In net/ipv6/seg6_local.c (ffffffff820ebf2d)
Location: include/linux/netdevice.h:4250
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
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
In drivers/net/mii.c (ffff8000109cf7b8)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - drivers/net/mii.c:mii_check_link
```
```
In drivers/net/ethernet/smsc/smc91x.c (ffff8000109f9c58)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - drivers/net/ethernet/smsc/smc91x.c:smc_10bt_check_media
```
```
In drivers/net/xen-netfront.c (ffff800010a07250)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_rx_interrupt
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_open
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
```
In net/core/dev.c (ffff800010bcd9a8)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:dev_get_flags
  - net/core/dev.c:dev_direct_xmit
```
```
In net/core/ethtool.c (ffff800010bd8a48)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_op_get_link
```
```
In net/core/rtnetlink.c (ffff800010bf030c)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/link_watch.c (ffff800010bf38b4)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_do_dev
  - net/core/link_watch.c:linkwatch_init_dev
  - net/core/link_watch.c:rfc2863_policy
```
```
In net/core/net-sysfs.c (ffff800010c09008)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/core/net-sysfs.c:carrier_show
```
```
In net/core/netpoll.c (ffff800010c11b08)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
```
```
In net/sched/sch_generic.c (ffff800010c38b08)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/ipv4/arp.c (ffff800010ca1570)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_netdev_event
```
```
In net/ipv4/fib_semantics.c (ffff800010cb7e08)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_check_nh
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
```
```
In net/ipv4/nexthop.c (ffff800010cc4380)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv6/route.c (ffff800010d16f40)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_sync_up
  - net/ipv6/route.c:fib6_nh_init
```
```
In net/ipv6/ndisc.c (ffff800010d21450)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_netdev_event
```
```
In net/ipv6/seg6_local.c (ffff800010d50f5c)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
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
In net/core/dev.c (c0ce5100)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:dev_get_flags
  - net/core/dev.c:dev_direct_xmit
```
```
In net/core/ethtool.c (c0cf32cc)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_op_get_link
```
```
In net/core/rtnetlink.c (c0d08964)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/link_watch.c (c0d0bec4)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_do_dev
  - net/core/link_watch.c:linkwatch_init_dev
  - net/core/link_watch.c:rfc2863_policy
```
```
In net/core/net-sysfs.c (c0d21f10)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/core/net-sysfs.c:carrier_show
```
```
In net/core/netpoll.c (c0d28774)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
```
```
In net/sched/sch_generic.c (c0d4a668)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/ipv4/arp.c (c0dae43c)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_netdev_event
```
```
In net/ipv4/fib_semantics.c (c0dc2ef0)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_check_nh
  - net/ipv4/fib_semantics.c:fib_check_nh
  - net/ipv4/fib_semantics.c:fib_check_nh
```
```
In net/ipv4/nexthop.c (c0dcfe94)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv6/route.c (c0e1cb48)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_sync_up
  - net/ipv6/route.c:fib6_nh_init
```
```
In net/ipv6/ndisc.c (c0e25e70)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_netdev_event
```
```
In net/ipv6/seg6_local.c (c0e51acc)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
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
In net/core/dev.c (c000000000ca59ac)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:dev_get_flags
  - net/core/dev.c:dev_direct_xmit
```
```
In net/core/ethtool.c (c000000000cb8508)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_op_get_link
```
```
In net/core/rtnetlink.c (c000000000cd4898)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/link_watch.c (c000000000cd88ec)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_do_dev
  - net/core/link_watch.c:linkwatch_init_dev
  - net/core/link_watch.c:rfc2863_policy
```
```
In net/core/net-sysfs.c (c000000000cf3a8c)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/core/net-sysfs.c:carrier_show
```
```
In net/core/netpoll.c (c000000000cfd0ac)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
```
```
In net/sched/sch_generic.c (c000000000d30bdc)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/ipv4/arp.c (c000000000db46fc)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_netdev_event
```
```
In net/ipv4/fib_semantics.c (c000000000dd063c)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_check_nh
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
```
```
In net/ipv4/nexthop.c (c000000000de0484)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv6/route.c (c000000000e447bc)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_sync_up
  - net/ipv6/route.c:fib6_nh_init
```
```
In net/ipv6/ndisc.c (c000000000e5096c)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_netdev_event
```
```
In net/ipv6/seg6_local.c (c000000000e88e60)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
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
In net/core/dev.c (ffffffe0007555fe)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:dev_get_flags
  - net/core/dev.c:dev_direct_xmit
```
```
In net/core/ethtool.c (ffffffe000761648)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_op_get_link
```
```
In net/core/rtnetlink.c (ffffffe00077247c)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/link_watch.c (ffffffe000774ef4)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_do_dev
  - net/core/link_watch.c:linkwatch_init_dev
  - net/core/link_watch.c:rfc2863_policy
```
```
In net/core/net-sysfs.c (ffffffe000786cc6)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/core/net-sysfs.c:carrier_show
```
```
In net/core/netpoll.c (ffffffe00078cdce)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
```
```
In net/sched/sch_generic.c (ffffffe0007aa0da)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/ipv4/arp.c (ffffffe0007fdc9e)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_netdev_event
```
```
In net/ipv4/fib_semantics.c (ffffffe00080ee76)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_check_nh
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
```
```
In net/ipv4/nexthop.c (ffffffe00081991e)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv6/route.c (ffffffe00085c196)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_sync_up
  - net/ipv6/route.c:fib6_nh_init
```
```
In net/ipv6/ndisc.c (ffffffe00086326c)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_netdev_event
```
```
In net/ipv6/seg6_local.c (ffffffe000889216)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
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
In drivers/net/xen-netfront.c (ffffffff8179394d)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_rx_interrupt
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
```
In net/core/dev.c (ffffffff818cc8e4)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:dev_get_flags
  - net/core/dev.c:dev_direct_xmit
```
```
In net/core/ethtool.c (ffffffff818d9c95)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_op_get_link
```
```
In net/core/rtnetlink.c (ffffffff818ee3bd)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/link_watch.c (ffffffff818f1958)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_do_dev
  - net/core/link_watch.c:linkwatch_init_dev
  - net/core/link_watch.c:rfc2863_policy
```
```
In net/core/net-sysfs.c (ffffffff81904904)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/core/net-sysfs.c:carrier_show
```
```
In net/core/netpoll.c (ffffffff8190b4e6)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
```
```
In net/sched/sch_generic.c (ffffffff8192d4dd)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/ipv4/arp.c (ffffffff8198b9b2)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_netdev_event
```
```
In net/ipv4/fib_semantics.c (ffffffff8199f63a)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_check_nh
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
```
```
In net/ipv4/nexthop.c (ffffffff819aac6b)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv6/route.c (ffffffff819f255b)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_sync_up
  - net/ipv6/route.c:fib6_nh_init
```
```
In net/ipv6/ndisc.c (ffffffff819fb72b)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_netdev_event
```
```
In net/ipv6/seg6_local.c (ffffffff81a24543)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
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
In net/core/dev.c (ffffffff81886974)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:dev_get_flags
  - net/core/dev.c:dev_direct_xmit
```
```
In net/core/ethtool.c (ffffffff81893ad5)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_op_get_link
```
```
In net/core/rtnetlink.c (ffffffff818a81fd)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/link_watch.c (ffffffff818ab798)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_do_dev
  - net/core/link_watch.c:linkwatch_init_dev
  - net/core/link_watch.c:rfc2863_policy
```
```
In net/core/net-sysfs.c (ffffffff818be734)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/core/net-sysfs.c:carrier_show
```
```
In net/core/netpoll.c (ffffffff818c52a3)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
```
```
In net/sched/sch_generic.c (ffffffff818e6fdd)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/ipv4/arp.c (ffffffff81945472)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_netdev_event
```
```
In net/ipv4/fib_semantics.c (ffffffff819590fa)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_check_nh
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
```
```
In net/ipv4/nexthop.c (ffffffff8196472b)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv6/route.c (ffffffff819af31b)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_sync_up
  - net/ipv6/route.c:fib6_nh_init
```
```
In net/ipv6/ndisc.c (ffffffff819b84eb)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_netdev_event
```
```
In net/ipv6/seg6_local.c (ffffffff819e1303)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
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
In drivers/net/xen-netfront.c (ffffffff817c3bad)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_rx_interrupt
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
```
In net/core/dev.c (ffffffff8191d8e4)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:dev_get_flags
  - net/core/dev.c:dev_direct_xmit
```
```
In net/core/ethtool.c (ffffffff8192acc5)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_op_get_link
```
```
In net/core/rtnetlink.c (ffffffff8193f3ed)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/link_watch.c (ffffffff81942988)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_do_dev
  - net/core/link_watch.c:linkwatch_init_dev
  - net/core/link_watch.c:rfc2863_policy
```
```
In net/core/net-sysfs.c (ffffffff81955934)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/core/net-sysfs.c:carrier_show
```
```
In net/core/netpoll.c (ffffffff8195c516)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
```
```
In net/sched/sch_generic.c (ffffffff8197e66d)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/ipv4/arp.c (ffffffff819f61c2)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_netdev_event
```
```
In net/ipv4/fib_semantics.c (ffffffff81a09eda)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_check_nh
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
```
```
In net/ipv4/nexthop.c (ffffffff81a1550b)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv6/route.c (ffffffff81a5cfdb)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_sync_up
  - net/ipv6/route.c:fib6_nh_init
```
```
In net/ipv6/ndisc.c (ffffffff81a661ab)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_netdev_event
```
```
In net/ipv6/seg6_local.c (ffffffff81a8efc3)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
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
In drivers/net/xen-netfront.c (ffffffff817dde5d)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_rx_interrupt
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
```
In net/core/dev.c (ffffffff8193edf4)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/core/dev.c:netif_stacked_transfer_operstate
  - net/core/dev.c:dev_get_flags
  - net/core/dev.c:dev_direct_xmit
```
```
In net/core/ethtool.c (ffffffff8194c395)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_op_get_link
```
```
In net/core/rtnetlink.c (ffffffff81960ccb)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/link_watch.c (ffffffff81964288)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_do_dev
  - net/core/link_watch.c:linkwatch_init_dev
  - net/core/link_watch.c:rfc2863_policy
```
```
In net/core/net-sysfs.c (ffffffff81977994)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/core/net-sysfs.c:carrier_show
```
```
In net/core/netpoll.c (ffffffff8197e736)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
```
```
In net/sched/sch_generic.c (ffffffff819a0379)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/ipv4/arp.c (ffffffff81a003c2)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_netdev_event
```
```
In net/ipv4/fib_semantics.c (ffffffff81a14699)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_check_nh
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
```
```
In net/ipv4/nexthop.c (ffffffff81a1ff4b)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv6/route.c (ffffffff81a693bb)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_sync_up
  - net/ipv6/route.c:fib6_nh_init
```
```
In net/ipv6/ndisc.c (ffffffff81a72770)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_netdev_event
```
```
In net/ipv6/seg6_local.c (ffffffff81a9bd43)
Location: include/linux/netdevice.h:3773
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx2
```
</details>
</li>
</ul>

## Differences
