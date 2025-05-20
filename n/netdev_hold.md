# Function: <code>netdev_hold</code>

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
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81bedddd)
Location: include/linux/netdevice.h:4042
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
In net/core/dev.c (ffffffff81dd177a)
Location: include/linux/netdevice.h:4042
Inline: True
Inline callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:bpf_xdp_link_attach
  - net/core/dev.c:__netdev_adjacent_dev_insert
  - net/core/dev.c:dev_getfirstbyhwtype
  - net/core/dev.c:dev_get_by_name
```
```
In net/core/dst.c (ffffffff81dd4576)
Location: include/linux/netdevice.h:4042
Inline: True
Inline callers:
  - net/core/dst.c:dst_alloc
```
```
In net/core/neighbour.c (ffffffff81dd8c18)
Location: include/linux/netdevice.h:4042
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:pneigh_lookup
  - net/core/neighbour.c:___neigh_create
```
```
In net/core/link_watch.c (ffffffff81dea691)
Location: include/linux/netdevice.h:4042
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_fire_event
```
```
In net/core/dev_ioctl.c (ffffffff81e033ed)
Location: include/linux/netdevice.h:4042
Inline: True
Inline callers:
  - net/core/dev_ioctl.c:dev_ifsioc
```
```
In net/core/net-sysfs.c (ffffffff81e0e5cc)
Location: include/linux/netdevice.h:4042
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
```
In net/core/netpoll.c (ffffffff81e126c4)
Location: include/linux/netdevice.h:4042
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
```
```
In net/core/drop_monitor.c (ffffffff81e23e99)
Location: include/linux/netdevice.h:4042
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_trap_packet_probe
```
```
In net/core/lwt_bpf.c (ffffffff81e29615)
Location: include/linux/netdevice.h:4042
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_input_reroute
```
```
In net/sched/sch_generic.c (ffffffff81e52411)
Location: include/linux/netdevice.h:4042
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/netlink/af_netlink.c (ffffffff81e67e3e)
Location: include/linux/netdevice.h:4042
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_deliver_tap
```
```
In net/ethtool/ioctl.c (ffffffff81e77ff6)
Location: include/linux/netdevice.h:4042
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_phys_id
```
```
In net/ethtool/netlink.c (ffffffff81e7d440)
Location: include/linux/netdevice.h:4042
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_dumpit
```
```
In net/netfilter/nf_queue.c (ffffffff81e8b5a2)
Location: include/linux/netdevice.h:4042
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
```
```
In net/ipv4/route.c (ffffffff81e941ac)
Location: include/linux/netdevice.h:4042
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_blackhole_route
```
```
In net/ipv4/icmp.c (ffffffff81eed1b0)
Location: include/linux/netdevice.h:4042
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_build_probe
```
```
In net/ipv4/devinet.c (ffffffff81ef1d50)
Location: include/linux/netdevice.h:4042
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:__ip_dev_find
```
```
In net/ipv4/fib_semantics.c (ffffffff81f0256d)
Location: include/linux/netdevice.h:4042
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_check_nh
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_semantics.c:fib_check_nh_v6_gw
```
```
In net/ipv4/ipmr.c (ffffffff81f1d3bb)
Location: include/linux/netdevice.h:4042
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:ipmr_new_tunnel
```
```
In net/ipv4/xfrm4_policy.c (ffffffff81f2b146)
Location: include/linux/netdevice.h:4042
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_fill_dst
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f2d272)
Location: include/linux/netdevice.h:4042
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_ifdown
```
```
In net/xfrm/xfrm_input.c (ffffffff81f42aba)
Location: include/linux/netdevice.h:4042
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_device.c (ffffffff81f467aa)
Location: include/linux/netdevice.h:4042
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
```
```
In net/ipv6/addrconf.c (ffffffff81f6223d)
Location: include/linux/netdevice.h:4042
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_dev
```
```
In net/ipv6/route.c (ffffffff81f76cba)
Location: include/linux/netdevice.h:4042
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:ip6_route_check_nh
  - net/ipv6/route.c:rt6_probe
```
```
In net/ipv6/ip6mr.c (ffffffff81fabb7b)
Location: include/linux/netdevice.h:4042
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mif6_add
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81fb112d)
Location: include/linux/netdevice.h:4042
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
```
```
In net/packet/af_packet.c (ffffffff81fc7126)
Location: include/linux/netdevice.h:4042
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
```
```
In net/switchdev/switchdev.c (ffffffff81fe2f07)
Location: include/linux/netdevice.h:4042
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_deferred_enqueue
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81ff2791)
Location: include/linux/netdevice.h:4042
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_assign_dev
```
```
In net/mctp/device.c (ffffffff820115d0)
Location: include/linux/netdevice.h:4042
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
Location: include/linux/netdevice.h:4101
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
Location: include/linux/netdevice.h:4101
Inline: True
Inline callers:
  - drivers/net/net_failover.c:net_failover_slave_register
```
```
In net/core/dev.c (ffffffff81e42364)
Location: include/linux/netdevice.h:4101
Inline: True
Inline callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:bpf_xdp_link_attach
  - net/core/dev.c:__netdev_adjacent_dev_insert
  - net/core/dev.c:dev_getfirstbyhwtype
  - net/core/dev.c:netdev_get_by_index
  - net/core/dev.c:netdev_get_by_name
```
```
In net/core/dst.c (ffffffff81e45336)
Location: include/linux/netdevice.h:4101
Inline: True
Inline callers:
  - net/core/dst.c:dst_alloc
```
```
In net/core/neighbour.c (ffffffff81e49a80)
Location: include/linux/netdevice.h:4101
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:pneigh_lookup
  - net/core/neighbour.c:___neigh_create
```
```
In net/core/link_watch.c (ffffffff81e5be71)
Location: include/linux/netdevice.h:4101
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_fire_event
```
```
In net/core/dev_ioctl.c (ffffffff81e75c9c)
Location: include/linux/netdevice.h:4101
Inline: True
Inline callers:
  - net/core/dev_ioctl.c:dev_ifsioc
```
```
In net/core/net-sysfs.c (ffffffff81e81a0c)
Location: include/linux/netdevice.h:4101
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
```
In net/core/netpoll.c (ffffffff81e85f04)
Location: include/linux/netdevice.h:4101
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
```
```
In net/core/drop_monitor.c (ffffffff81e993d9)
Location: include/linux/netdevice.h:4101
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_trap_packet_probe
```
```
In net/core/lwt_bpf.c (ffffffff81e9ec45)
Location: include/linux/netdevice.h:4101
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_input_reroute
```
```
In net/core/failover.c (ffffffff81ea05b3)
Location: include/linux/netdevice.h:4101
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff81eadc81)
Location: include/linux/netdevice.h:4101
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/netlink/af_netlink.c (ffffffff81ec3c96)
Location: include/linux/netdevice.h:4101
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_deliver_tap
```
```
In net/ethtool/ioctl.c (ffffffff81ed4176)
Location: include/linux/netdevice.h:4101
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_phys_id
```
```
In net/ethtool/netlink.c (ffffffff81ed9a00)
Location: include/linux/netdevice.h:4101
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_dumpit
```
```
In net/netfilter/nf_queue.c (ffffffff81ee95ee)
Location: include/linux/netdevice.h:4101
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
```
```
In net/ipv4/route.c (ffffffff81ef295c)
Location: include/linux/netdevice.h:4101
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_blackhole_route
```
```
In net/ipv4/icmp.c (ffffffff81f4cb50)
Location: include/linux/netdevice.h:4101
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_build_probe
```
```
In net/ipv4/devinet.c (ffffffff81f51840)
Location: include/linux/netdevice.h:4101
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:__ip_dev_find
```
```
In net/ipv4/fib_semantics.c (ffffffff81f61fcd)
Location: include/linux/netdevice.h:4101
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_check_nh
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_semantics.c:fib_check_nh_v6_gw
```
```
In net/ipv4/ipmr.c (ffffffff81f7ce9a)
Location: include/linux/netdevice.h:4101
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:ipmr_new_tunnel
```
```
In net/ipv4/xfrm4_policy.c (ffffffff81f8ae19)
Location: include/linux/netdevice.h:4101
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_fill_dst
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f8cd72)
Location: include/linux/netdevice.h:4101
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_ifdown
```
```
In net/xfrm/xfrm_input.c (ffffffff81fa22ba)
Location: include/linux/netdevice.h:4101
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_device.c (ffffffff81fa60a2)
Location: include/linux/netdevice.h:4101
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
```
```
In net/ipv6/addrconf.c (ffffffff81fc202d)
Location: include/linux/netdevice.h:4101
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_dev
```
```
In net/ipv6/route.c (ffffffff81fd6cda)
Location: include/linux/netdevice.h:4101
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:rt6_probe
```
```
In net/ipv6/ip6mr.c (ffffffff8200c31b)
Location: include/linux/netdevice.h:4101
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mif6_add
```
```
In net/ipv6/xfrm6_policy.c (ffffffff820117dd)
Location: include/linux/netdevice.h:4101
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
```
```
In net/packet/af_packet.c (ffffffff82027e6b)
Location: include/linux/netdevice.h:4101
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
```
```
In net/switchdev/switchdev.c (ffffffff8205f227)
Location: include/linux/netdevice.h:4101
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_deferred_enqueue
```
```
In net/xdp/xsk_buff_pool.c (ffffffff8206e9b1)
Location: include/linux/netdevice.h:4101
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_assign_dev
```
```
In net/mctp/device.c (ffffffff8208e3b0)
Location: include/linux/netdevice.h:4101
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
Location: include/linux/netdevice.h:4168
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
Location: include/linux/netdevice.h:4168
Inline: True
Inline callers:
  - drivers/net/net_failover.c:net_failover_slave_register
```
```
In net/core/dev.c (ffffffff81f00f9c)
Location: include/linux/netdevice.h:4168
Inline: True
Inline callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:bpf_xdp_link_attach
  - net/core/dev.c:__netdev_adjacent_dev_insert
  - net/core/dev.c:dev_getfirstbyhwtype
  - net/core/dev.c:netdev_get_by_index
  - net/core/dev.c:netdev_get_by_name
```
```
In net/core/dst.c (ffffffff81f03fae)
Location: include/linux/netdevice.h:4168
Inline: True
Inline callers:
  - net/core/dst.c:dst_alloc
```
```
In net/core/neighbour.c (ffffffff81f0879d)
Location: include/linux/netdevice.h:4168
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:pneigh_enqueue
  - net/core/neighbour.c:pneigh_lookup
  - net/core/neighbour.c:___neigh_create
```
```
In net/core/link_watch.c (ffffffff81f1b234)
Location: include/linux/netdevice.h:4168
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_fire_event
```
```
In net/core/dev_ioctl.c (ffffffff81f35c23)
Location: include/linux/netdevice.h:4168
Inline: True
Inline callers:
  - net/core/dev_ioctl.c:dev_ifsioc
```
```
In net/core/net-sysfs.c (ffffffff81f429e9)
Location: include/linux/netdevice.h:4168
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_queue_update_kobjects
  - net/core/net-sysfs.c:net_rx_queue_update_kobjects
```
```
In net/core/netpoll.c (ffffffff81f47f04)
Location: include/linux/netdevice.h:4168
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
```
```
In net/core/drop_monitor.c (ffffffff81f5bac8)
Location: include/linux/netdevice.h:4168
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_trap_packet_probe
```
```
In net/core/lwt_bpf.c (ffffffff81f613b5)
Location: include/linux/netdevice.h:4168
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_input_reroute
```
```
In net/core/failover.c (ffffffff81f62d52)
Location: include/linux/netdevice.h:4168
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff81f70711)
Location: include/linux/netdevice.h:4168
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/netlink/af_netlink.c (ffffffff81f87056)
Location: include/linux/netdevice.h:4168
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_deliver_tap
```
```
In net/ethtool/ioctl.c (ffffffff81f97b86)
Location: include/linux/netdevice.h:4168
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_phys_id
```
```
In net/ethtool/netlink.c (ffffffff81f9d85c)
Location: include/linux/netdevice.h:4168
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_dumpit
```
```
In net/netfilter/nf_queue.c (ffffffff81fad35e)
Location: include/linux/netdevice.h:4168
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
```
```
In net/ipv4/route.c (ffffffff81fb68f6)
Location: include/linux/netdevice.h:4168
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_blackhole_route
```
```
In net/ipv4/icmp.c (ffffffff82012c60)
Location: include/linux/netdevice.h:4168
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_build_probe
```
```
In net/ipv4/devinet.c (ffffffff82017aff)
Location: include/linux/netdevice.h:4168
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:__ip_dev_find
```
```
In net/ipv4/fib_semantics.c (ffffffff8202859d)
Location: include/linux/netdevice.h:4168
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_check_nh
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/fib_semantics.c:fib_check_nh_v6_gw
```
```
In net/ipv4/ipmr.c (ffffffff8204359a)
Location: include/linux/netdevice.h:4168
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:ipmr_new_tunnel
```
```
In net/ipv4/xfrm4_policy.c (ffffffff820524f9)
Location: include/linux/netdevice.h:4168
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_fill_dst
```
```
In net/xfrm/xfrm_policy.c (ffffffff8205a702)
Location: include/linux/netdevice.h:4168
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_ifdown
```
```
In net/xfrm/xfrm_input.c (ffffffff8206f6a2)
Location: include/linux/netdevice.h:4168
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_device.c (ffffffff820733c8)
Location: include/linux/netdevice.h:4168
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
```
```
In net/ipv6/addrconf.c (ffffffff8208f5a7)
Location: include/linux/netdevice.h:4168
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_dev
```
```
In net/ipv6/route.c (ffffffff820a465a)
Location: include/linux/netdevice.h:4168
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:rt6_probe
```
```
In net/ipv6/ip6mr.c (ffffffff820db2eb)
Location: include/linux/netdevice.h:4168
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mif6_add
```
```
In net/ipv6/xfrm6_policy.c (ffffffff820e078d)
Location: include/linux/netdevice.h:4168
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
```
```
In net/packet/af_packet.c (ffffffff820f76cb)
Location: include/linux/netdevice.h:4168
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
```
```
In net/switchdev/switchdev.c (ffffffff82132177)
Location: include/linux/netdevice.h:4168
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_deferred_enqueue
```
```
In net/xdp/xsk_buff_pool.c (ffffffff82142a7e)
Location: include/linux/netdevice.h:4168
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_assign_dev
```
```
In net/mctp/device.c (ffffffff821648a3)
Location: include/linux/netdevice.h:4168
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
