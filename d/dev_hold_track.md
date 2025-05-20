# Function: <code>dev_hold_track</code>

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
In drivers/net/tun.c (ffffffff81a6260d)
Location: include/linux/netdevice.h:3998
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
In net/core/dev.c (ffffffff81c1f34c)
Location: include/linux/netdevice.h:3998
Inline: True
Inline callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:bpf_xdp_link_attach
  - net/core/dev.c:__netdev_adjacent_dev_insert
  - net/core/dev.c:dev_getfirstbyhwtype
  - net/core/dev.c:dev_get_by_name
```
```
In net/core/dst.c (ffffffff81c221c6)
Location: include/linux/netdevice.h:3998
Inline: True
Inline callers:
  - net/core/dst.c:dst_alloc
```
```
In net/core/neighbour.c (ffffffff81c2400e)
Location: include/linux/netdevice.h:3998
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:pneigh_lookup
  - net/core/neighbour.c:___neigh_create
```
```
In net/core/link_watch.c (ffffffff81c37291)
Location: include/linux/netdevice.h:3998
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_fire_event
```
```
In net/core/dev_ioctl.c (ffffffff81c4e3ee)
Location: include/linux/netdevice.h:3998
Inline: True
Inline callers:
  - net/core/dev_ioctl.c:dev_ifsioc
```
```
In net/core/net-sysfs.c (ffffffff81c5871c)
Location: include/linux/netdevice.h:3998
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
```
In net/core/netpoll.c (ffffffff81c5c1dc)
Location: include/linux/netdevice.h:3998
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
```
```
In net/core/drop_monitor.c (ffffffff81c6c499)
Location: include/linux/netdevice.h:3998
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_trap_packet_probe
```
```
In net/core/lwt_bpf.c (ffffffff81c71555)
Location: include/linux/netdevice.h:3998
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_input_reroute
```
```
In net/sched/sch_generic.c (ffffffff81c96802)
Location: include/linux/netdevice.h:3998
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/netlink/af_netlink.c (ffffffff81caac98)
Location: include/linux/netdevice.h:3998
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_deliver_tap
```
```
In net/ethtool/ioctl.c (ffffffff81cb9176)
Location: include/linux/netdevice.h:3998
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_phys_id
```
```
In net/ethtool/netlink.c (ffffffff81cbe920)
Location: include/linux/netdevice.h:3998
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_dumpit
```
```
In net/netfilter/nf_queue.c (ffffffff81ccb762)
Location: include/linux/netdevice.h:3998
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
```
```
In net/ipv4/route.c (ffffffff81cd3f5c)
Location: include/linux/netdevice.h:3998
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_blackhole_route
```
```
In net/ipv4/icmp.c (ffffffff81d25920)
Location: include/linux/netdevice.h:3998
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_build_probe
```
```
In net/ipv4/devinet.c (ffffffff81d2a260)
Location: include/linux/netdevice.h:3998
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:__ip_dev_find
```
```
In net/ipv4/fib_semantics.c (ffffffff81d39c3d)
Location: include/linux/netdevice.h:3998
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_check_nh
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_semantics.c:fib_check_nh_v6_gw
```
```
In net/ipv4/ipmr.c (ffffffff81d536fc)
Location: include/linux/netdevice.h:3998
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:ipmr_new_tunnel
```
```
In net/ipv4/xfrm4_policy.c (ffffffff81d60a86)
Location: include/linux/netdevice.h:3998
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_fill_dst
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d62762)
Location: include/linux/netdevice.h:3998
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_ifdown
```
```
In net/xfrm/xfrm_input.c (ffffffff81d76358)
Location: include/linux/netdevice.h:3998
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_device.c (ffffffff81d79a51)
Location: include/linux/netdevice.h:3998
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
```
```
In net/ipv6/addrconf.c (ffffffff81d93a85)
Location: include/linux/netdevice.h:3998
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_dev
```
```
In net/ipv6/route.c (ffffffff81da767a)
Location: include/linux/netdevice.h:3998
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:ip6_route_check_nh
  - net/ipv6/route.c:rt6_probe
```
```
In net/ipv6/ip6mr.c (ffffffff81dd9ed5)
Location: include/linux/netdevice.h:3998
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mif6_add
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81ddeefd)
Location: include/linux/netdevice.h:3998
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
```
```
In net/packet/af_packet.c (ffffffff81df2d26)
Location: include/linux/netdevice.h:3998
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
```
```
In net/switchdev/switchdev.c (ffffffff81e0cd17)
Location: include/linux/netdevice.h:3998
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_deferred_enqueue
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81e1b221)
Location: include/linux/netdevice.h:3998
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_assign_dev
```
```
In net/mctp/device.c (ffffffff81e38370)
Location: include/linux/netdevice.h:3998
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_add_dev
```
</details>
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
