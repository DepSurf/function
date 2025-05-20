# Function: <code>__dev_hold</code>

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
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81a62612)
Location: include/linux/netdevice.h:3958
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
In net/core/dev.c (ffffffff81c12a6b)
Location: include/linux/netdevice.h:3958
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
In net/core/dst.c (ffffffff81c2187f)
Location: include/linux/netdevice.h:3958
Inline: True
Inline callers:
  - net/core/dst.c:dst_dev_put
  - net/core/dst.c:dst_alloc
```
```
In net/core/neighbour.c (ffffffff81c24013)
Location: include/linux/netdevice.h:3958
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:pneigh_lookup
  - net/core/neighbour.c:___neigh_create
```
```
In net/core/link_watch.c (ffffffff81c37296)
Location: include/linux/netdevice.h:3958
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_fire_event
```
```
In net/core/dev_ioctl.c (ffffffff81c4e3ee)
Location: include/linux/netdevice.h:3958
Inline: True
Inline callers:
  - net/core/dev_ioctl.c:dev_ifsioc
```
```
In net/core/net-sysfs.c (ffffffff81c58721)
Location: include/linux/netdevice.h:3958
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
```
In net/core/netpoll.c (ffffffff81c5c1dc)
Location: include/linux/netdevice.h:3958
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
```
```
In net/core/drop_monitor.c (ffffffff81c6c49e)
Location: include/linux/netdevice.h:3958
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_trap_packet_probe
```
```
In net/core/lwt_bpf.c (ffffffff81c7155a)
Location: include/linux/netdevice.h:3958
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_input_reroute
```
```
In net/sched/sch_generic.c (ffffffff81c96807)
Location: include/linux/netdevice.h:3958
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/netlink/af_netlink.c (ffffffff81caac9d)
Location: include/linux/netdevice.h:3958
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_deliver_tap
```
```
In net/ethtool/ioctl.c (ffffffff81cb917b)
Location: include/linux/netdevice.h:3958
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_phys_id
```
```
In net/ethtool/netlink.c (ffffffff81cbe920)
Location: include/linux/netdevice.h:3958
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_dumpit
```
```
In net/netfilter/nf_queue.c (ffffffff81ccb767)
Location: include/linux/netdevice.h:3958
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
```
```
In net/ipv4/route.c (ffffffff81cd3f61)
Location: include/linux/netdevice.h:3958
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/route.c:rt_flush_dev
```
```
In net/ipv4/icmp.c (ffffffff81d25929)
Location: include/linux/netdevice.h:3958
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_build_probe
```
```
In net/ipv4/devinet.c (ffffffff81d2a265)
Location: include/linux/netdevice.h:3958
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:__ip_dev_find
```
```
In net/ipv4/fib_semantics.c (ffffffff81d39c42)
Location: include/linux/netdevice.h:3958
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_check_nh
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_semantics.c:fib_check_nh_v6_gw
```
```
In net/ipv4/ipmr.c (ffffffff81d536fc)
Location: include/linux/netdevice.h:3958
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:ipmr_new_tunnel
```
```
In net/ipv4/xfrm4_policy.c (ffffffff81d60a8e)
Location: include/linux/netdevice.h:3958
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_fill_dst
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d62767)
Location: include/linux/netdevice.h:3958
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_ifdown
```
```
In net/xfrm/xfrm_input.c (ffffffff81d7635d)
Location: include/linux/netdevice.h:3958
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_device.c (ffffffff81d79a56)
Location: include/linux/netdevice.h:3958
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
```
```
In net/ipv6/addrconf.c (ffffffff81d93a8a)
Location: include/linux/netdevice.h:3958
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_dev
```
```
In net/ipv6/route.c (ffffffff81da95b0)
Location: include/linux/netdevice.h:3958
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:ip6_route_check_nh
  - net/ipv6/route.c:rt6_probe
```
```
In net/ipv6/ip6mr.c (ffffffff81dd9ed5)
Location: include/linux/netdevice.h:3958
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mif6_add
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81ddef10)
Location: include/linux/netdevice.h:3958
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
```
```
In net/packet/af_packet.c (ffffffff81df2d26)
Location: include/linux/netdevice.h:3958
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
```
```
In net/switchdev/switchdev.c (ffffffff81e0cd1c)
Location: include/linux/netdevice.h:3958
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_deferred_enqueue
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81e1b226)
Location: include/linux/netdevice.h:3958
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_assign_dev
```
```
In net/mctp/device.c (ffffffff81e38375)
Location: include/linux/netdevice.h:3958
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
In drivers/net/tun.c (ffffffff81bedde2)
Location: include/linux/netdevice.h:4002
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
In net/core/dev.c (ffffffff81dc2b8e)
Location: include/linux/netdevice.h:4002
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
In net/core/dst.c (ffffffff81dd3a3f)
Location: include/linux/netdevice.h:4002
Inline: True
Inline callers:
  - net/core/dst.c:dst_dev_put
  - net/core/dst.c:dst_alloc
```
```
In net/core/neighbour.c (ffffffff81dd8c1d)
Location: include/linux/netdevice.h:4002
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:pneigh_lookup
  - net/core/neighbour.c:___neigh_create
```
```
In net/core/link_watch.c (ffffffff81dea696)
Location: include/linux/netdevice.h:4002
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_fire_event
```
```
In net/core/dev_ioctl.c (ffffffff81e033ed)
Location: include/linux/netdevice.h:4002
Inline: True
Inline callers:
  - net/core/dev_ioctl.c:dev_ifsioc
```
```
In net/core/net-sysfs.c (ffffffff81e0e5d1)
Location: include/linux/netdevice.h:4002
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
```
In net/core/netpoll.c (ffffffff81e126c4)
Location: include/linux/netdevice.h:4002
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
```
```
In net/core/drop_monitor.c (ffffffff81e23e9e)
Location: include/linux/netdevice.h:4002
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_trap_packet_probe
```
```
In net/core/lwt_bpf.c (ffffffff81e2961a)
Location: include/linux/netdevice.h:4002
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_input_reroute
```
```
In net/sched/sch_generic.c (ffffffff81e52416)
Location: include/linux/netdevice.h:4002
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/netlink/af_netlink.c (ffffffff81e67e43)
Location: include/linux/netdevice.h:4002
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_deliver_tap
```
```
In net/ethtool/ioctl.c (ffffffff81e77ffb)
Location: include/linux/netdevice.h:4002
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_phys_id
```
```
In net/ethtool/netlink.c (ffffffff81e7d440)
Location: include/linux/netdevice.h:4002
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_dumpit
```
```
In net/netfilter/nf_queue.c (ffffffff81e8b5a7)
Location: include/linux/netdevice.h:4002
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
```
```
In net/ipv4/route.c (ffffffff81e941b1)
Location: include/linux/netdevice.h:4002
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/route.c:rt_flush_dev
```
```
In net/ipv4/icmp.c (ffffffff81eed1b9)
Location: include/linux/netdevice.h:4002
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_build_probe
```
```
In net/ipv4/devinet.c (ffffffff81ef1d55)
Location: include/linux/netdevice.h:4002
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:__ip_dev_find
```
```
In net/ipv4/fib_semantics.c (ffffffff81f02572)
Location: include/linux/netdevice.h:4002
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_check_nh
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_semantics.c:fib_check_nh_v6_gw
```
```
In net/ipv4/ipmr.c (ffffffff81f1d3bb)
Location: include/linux/netdevice.h:4002
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:ipmr_new_tunnel
```
```
In net/ipv4/xfrm4_policy.c (ffffffff81f2b14e)
Location: include/linux/netdevice.h:4002
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_fill_dst
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f2d277)
Location: include/linux/netdevice.h:4002
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_ifdown
```
```
In net/xfrm/xfrm_input.c (ffffffff81f42abf)
Location: include/linux/netdevice.h:4002
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_device.c (ffffffff81f467b3)
Location: include/linux/netdevice.h:4002
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
```
```
In net/ipv6/addrconf.c (ffffffff81f62242)
Location: include/linux/netdevice.h:4002
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_dev
```
```
In net/ipv6/route.c (ffffffff81f78d33)
Location: include/linux/netdevice.h:4002
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:ip6_route_check_nh
  - net/ipv6/route.c:rt6_probe
```
```
In net/ipv6/ip6mr.c (ffffffff81fabb7b)
Location: include/linux/netdevice.h:4002
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mif6_add
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81fb1140)
Location: include/linux/netdevice.h:4002
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
```
```
In net/packet/af_packet.c (ffffffff81fc7126)
Location: include/linux/netdevice.h:4002
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
```
```
In net/switchdev/switchdev.c (ffffffff81fe2f0c)
Location: include/linux/netdevice.h:4002
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_deferred_enqueue
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81ff2796)
Location: include/linux/netdevice.h:4002
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_assign_dev
```
```
In net/mctp/device.c (ffffffff820115d5)
Location: include/linux/netdevice.h:4002
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
In drivers/net/tun.c (ffffffff81c46312)
Location: include/linux/netdevice.h:4061
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
In drivers/net/net_failover.c (ffffffff81c6fb27)
Location: include/linux/netdevice.h:4061
Inline: True
Inline callers:
  - drivers/net/net_failover.c:net_failover_slave_register
```
```
In net/core/dev.c (ffffffff81e32033)
Location: include/linux/netdevice.h:4061
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:bpf_xdp_link_attach
  - net/core/dev.c:__netdev_adjacent_dev_insert
  - net/core/dev.c:dev_getfirstbyhwtype
  - net/core/dev.c:netdev_get_by_index
  - net/core/dev.c:netdev_get_by_name
```
```
In net/core/dst.c (ffffffff81e447ff)
Location: include/linux/netdevice.h:4061
Inline: True
Inline callers:
  - net/core/dst.c:dst_dev_put
  - net/core/dst.c:dst_alloc
```
```
In net/core/neighbour.c (ffffffff81e49a85)
Location: include/linux/netdevice.h:4061
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:pneigh_lookup
  - net/core/neighbour.c:___neigh_create
```
```
In net/core/link_watch.c (ffffffff81e5be76)
Location: include/linux/netdevice.h:4061
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_fire_event
```
```
In net/core/dev_ioctl.c (ffffffff81e75c9c)
Location: include/linux/netdevice.h:4061
Inline: True
Inline callers:
  - net/core/dev_ioctl.c:dev_ifsioc
```
```
In net/core/net-sysfs.c (ffffffff81e81a11)
Location: include/linux/netdevice.h:4061
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
```
In net/core/netpoll.c (ffffffff81e85f04)
Location: include/linux/netdevice.h:4061
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
```
```
In net/core/drop_monitor.c (ffffffff81e993de)
Location: include/linux/netdevice.h:4061
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_trap_packet_probe
```
```
In net/core/lwt_bpf.c (ffffffff81e9ec4a)
Location: include/linux/netdevice.h:4061
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_input_reroute
```
```
In net/core/failover.c (ffffffff81ea05b8)
Location: include/linux/netdevice.h:4061
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff81eadc86)
Location: include/linux/netdevice.h:4061
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/netlink/af_netlink.c (ffffffff81ec3c9b)
Location: include/linux/netdevice.h:4061
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_deliver_tap
```
```
In net/ethtool/ioctl.c (ffffffff81ed417b)
Location: include/linux/netdevice.h:4061
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_phys_id
```
```
In net/ethtool/netlink.c (ffffffff81ed9a00)
Location: include/linux/netdevice.h:4061
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_dumpit
```
```
In net/netfilter/nf_queue.c (ffffffff81ee95f3)
Location: include/linux/netdevice.h:4061
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
```
```
In net/ipv4/route.c (ffffffff81ef2961)
Location: include/linux/netdevice.h:4061
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/route.c:rt_flush_dev
```
```
In net/ipv4/icmp.c (ffffffff81f4cb59)
Location: include/linux/netdevice.h:4061
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_build_probe
```
```
In net/ipv4/devinet.c (ffffffff81f51845)
Location: include/linux/netdevice.h:4061
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:__ip_dev_find
```
```
In net/ipv4/fib_semantics.c (ffffffff81f61fd2)
Location: include/linux/netdevice.h:4061
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_check_nh
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_semantics.c:fib_check_nh_v6_gw
```
```
In net/ipv4/ipmr.c (ffffffff81f7ce9a)
Location: include/linux/netdevice.h:4061
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:ipmr_new_tunnel
```
```
In net/ipv4/xfrm4_policy.c (ffffffff81f8ae21)
Location: include/linux/netdevice.h:4061
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_fill_dst
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f8cd77)
Location: include/linux/netdevice.h:4061
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_ifdown
```
```
In net/xfrm/xfrm_input.c (ffffffff81fa22bf)
Location: include/linux/netdevice.h:4061
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_device.c (ffffffff81fa60ab)
Location: include/linux/netdevice.h:4061
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
```
```
In net/ipv6/addrconf.c (ffffffff81fc2032)
Location: include/linux/netdevice.h:4061
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_dev
```
```
In net/ipv6/route.c (ffffffff81fd8f2b)
Location: include/linux/netdevice.h:4061
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:rt6_probe
```
```
In net/ipv6/ip6mr.c (ffffffff8200c31b)
Location: include/linux/netdevice.h:4061
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mif6_add
```
```
In net/ipv6/xfrm6_policy.c (ffffffff820117f0)
Location: include/linux/netdevice.h:4061
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
```
```
In net/packet/af_packet.c (ffffffff82027e6b)
Location: include/linux/netdevice.h:4061
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
```
```
In net/switchdev/switchdev.c (ffffffff8205f22c)
Location: include/linux/netdevice.h:4061
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_deferred_enqueue
```
```
In net/xdp/xsk_buff_pool.c (ffffffff8206e9b6)
Location: include/linux/netdevice.h:4061
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_assign_dev
```
```
In net/mctp/device.c (ffffffff8208e3b5)
Location: include/linux/netdevice.h:4061
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
In drivers/net/tun.c (ffffffff81cfbc22)
Location: include/linux/netdevice.h:4128
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
In drivers/net/net_failover.c (ffffffff81d243d1)
Location: include/linux/netdevice.h:4128
Inline: True
Inline callers:
  - drivers/net/net_failover.c:net_failover_slave_register
```
```
In net/core/dev.c (ffffffff81ef04bf)
Location: include/linux/netdevice.h:4128
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:bpf_xdp_link_attach
  - net/core/dev.c:__netdev_adjacent_dev_insert
  - net/core/dev.c:dev_getfirstbyhwtype
  - net/core/dev.c:netdev_get_by_index
  - net/core/dev.c:netdev_get_by_name
```
```
In net/core/dst.c (ffffffff81f0345a)
Location: include/linux/netdevice.h:4128
Inline: True
Inline callers:
  - net/core/dst.c:dst_dev_put
  - net/core/dst.c:dst_alloc
```
```
In net/core/neighbour.c (ffffffff81f087a2)
Location: include/linux/netdevice.h:4128
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:pneigh_lookup
  - net/core/neighbour.c:___neigh_create
```
```
In net/core/link_watch.c (ffffffff81f1b239)
Location: include/linux/netdevice.h:4128
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_fire_event
```
```
In net/core/dev_ioctl.c (ffffffff81f35c23)
Location: include/linux/netdevice.h:4128
Inline: True
Inline callers:
  - net/core/dev_ioctl.c:dev_ifsioc
```
```
In net/core/net-sysfs.c (ffffffff81f429ee)
Location: include/linux/netdevice.h:4128
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
```
In net/core/netpoll.c (ffffffff81f47f04)
Location: include/linux/netdevice.h:4128
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
```
```
In net/core/drop_monitor.c (ffffffff81f5bacd)
Location: include/linux/netdevice.h:4128
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_trap_packet_probe
```
```
In net/core/lwt_bpf.c (ffffffff81f613ba)
Location: include/linux/netdevice.h:4128
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_input_reroute
```
```
In net/core/failover.c (ffffffff81f62d57)
Location: include/linux/netdevice.h:4128
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff81f70716)
Location: include/linux/netdevice.h:4128
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/netlink/af_netlink.c (ffffffff81f8705b)
Location: include/linux/netdevice.h:4128
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_deliver_tap
```
```
In net/ethtool/ioctl.c (ffffffff81f97b8b)
Location: include/linux/netdevice.h:4128
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_phys_id
```
```
In net/ethtool/netlink.c (ffffffff81f9d85c)
Location: include/linux/netdevice.h:4128
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_dumpit
```
```
In net/netfilter/nf_queue.c (ffffffff81fad363)
Location: include/linux/netdevice.h:4128
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
```
```
In net/ipv4/route.c (ffffffff81fb68fb)
Location: include/linux/netdevice.h:4128
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/route.c:rt_flush_dev
```
```
In net/ipv4/icmp.c (ffffffff82012c69)
Location: include/linux/netdevice.h:4128
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_build_probe
```
```
In net/ipv4/devinet.c (ffffffff82017b04)
Location: include/linux/netdevice.h:4128
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:__ip_dev_find
```
```
In net/ipv4/fib_semantics.c (ffffffff820285a2)
Location: include/linux/netdevice.h:4128
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_check_nh
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_semantics.c:fib_check_nh_v6_gw
```
```
In net/ipv4/ipmr.c (ffffffff8204359a)
Location: include/linux/netdevice.h:4128
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:ipmr_new_tunnel
```
```
In net/ipv4/xfrm4_policy.c (ffffffff82052501)
Location: include/linux/netdevice.h:4128
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_fill_dst
```
```
In net/xfrm/xfrm_policy.c (ffffffff8205a707)
Location: include/linux/netdevice.h:4128
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_ifdown
```
```
In net/xfrm/xfrm_input.c (ffffffff8206f6a7)
Location: include/linux/netdevice.h:4128
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_device.c (ffffffff820733d1)
Location: include/linux/netdevice.h:4128
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
```
```
In net/ipv6/addrconf.c (ffffffff8208f5ac)
Location: include/linux/netdevice.h:4128
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_dev
```
```
In net/ipv6/route.c (ffffffff820a68bb)
Location: include/linux/netdevice.h:4128
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:rt6_probe
```
```
In net/ipv6/ip6mr.c (ffffffff820db2eb)
Location: include/linux/netdevice.h:4128
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mif6_add
```
```
In net/ipv6/xfrm6_policy.c (ffffffff820e07a0)
Location: include/linux/netdevice.h:4128
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
```
```
In net/packet/af_packet.c (ffffffff820f76cb)
Location: include/linux/netdevice.h:4128
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
```
```
In net/switchdev/switchdev.c (ffffffff8213217c)
Location: include/linux/netdevice.h:4128
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_deferred_enqueue
```
```
In net/xdp/xsk_buff_pool.c (ffffffff82142a83)
Location: include/linux/netdevice.h:4128
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_assign_dev
```
```
In net/mctp/device.c (ffffffff821648a8)
Location: include/linux/netdevice.h:4128
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
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
