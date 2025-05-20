# Function: <code>__dev_put</code>

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
In kernel/bpf/devmap.c (ffffffff812b9fb1)
Location: include/linux/netdevice.h:3947
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:__dev_map_alloc_node
  - kernel/bpf/devmap.c:__dev_map_entry_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/devmap.c:dev_map_free
```
```
In kernel/bpf/offload.c (ffffffff812bea36)
Location: include/linux/netdevice.h:3947
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_prog_offload_init
  - kernel/bpf/offload.c:bpf_prog_offload_init
```
```
In security/selinux/netif.c (ffffffff815d26e7)
Location: include/linux/netdevice.h:3947
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_sid_slow
```
```
In security/lsm_audit.c (ffffffff815f505e)
Location: include/linux/netdevice.h:3947
Inline: True
Inline callers:
  - security/lsm_audit.c:dump_common_audit_data
```
```
In drivers/net/tun.c (ffffffff81a62640)
Location: include/linux/netdevice.h:3947
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_show_fdinfo
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:tun_peek_len
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_chr_read_iter
  - drivers/net/tun.c:tun_chr_write_iter
  - drivers/net/tun.c:tun_chr_poll
```
```
In net/core/sock.c (ffffffff81bf06f1)
Location: include/linux/netdevice.h:3947
Inline: True
Inline callers:
  - net/core/sock.c:sock_set_timestamping
```
```
In net/core/dev.c (ffffffff81c16c16)
Location: include/linux/netdevice.h:3947
Inline: True
Inline callers:
  - net/core/dev.c:unregister_netdevice_many
  - net/core/dev.c:bpf_xdp_link_attach
  - net/core/dev.c:bpf_xdp_link_attach
  - net/core/dev.c:__netdev_adjacent_dev_remove
  - net/core/dev.c:__netdev_adjacent_dev_insert
```
```
In net/core/dst.c (ffffffff81c2188e)
Location: include/linux/netdevice.h:3947
Inline: True
Inline callers:
  - net/core/dst.c:dst_dev_put
  - net/core/dst.c:dst_destroy
```
```
In net/core/neighbour.c (ffffffff81c240ce)
Location: include/linux/netdevice.h:3947
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:pneigh_delete
  - net/core/neighbour.c:pneigh_lookup
  - net/core/neighbour.c:pneigh_queue_purge
```
```
In net/core/utils.c (ffffffff81c36b1d)
Location: include/linux/netdevice.h:3947
Inline: True
Inline callers:
  - net/core/utils.c:inet6_pton
```
```
In net/core/link_watch.c (ffffffff81c36e08)
Location: include/linux/netdevice.h:3947
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_do_dev
```
```
In net/core/filter.c (ffffffff81c4a9cd)
Location: include/linux/netdevice.h:3947
Inline: True
Inline callers:
  - net/core/filter.c:_bpf_setsockopt
```
```
In net/core/dev_ioctl.c (ffffffff81c4e41e)
Location: include/linux/netdevice.h:3947
Inline: True
Inline callers:
  - net/core/dev_ioctl.c:dev_ifsioc
```
```
In net/core/net-sysfs.c (ffffffff81c5590e)
Location: include/linux/netdevice.h:3947
Inline: True
Inline callers:
  - net/core/net-sysfs.c:rx_queue_release
```
```
In net/core/netpoll.c (ffffffff81c5bf18)
Location: include/linux/netdevice.h:3947
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_cleanup
  - net/core/netpoll.c:netpoll_setup
```
```
In net/core/drop_monitor.c (ffffffff81c6cd0c)
Location: include/linux/netdevice.h:3947
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_monitor_stop
  - net/core/drop_monitor.c:net_dm_hw_monitor_start
  - net/core/drop_monitor.c:net_dm_hw_trap_packet_probe
  - net/core/drop_monitor.c:net_dm_hw_packet_work
```
```
In net/core/netprio_cgroup.c (ffffffff81c6f671)
Location: include/linux/netdevice.h:3947
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:write_priomap
```
```
In net/core/lwt_bpf.c (ffffffff81c7158b)
Location: include/linux/netdevice.h:3947
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_input_reroute
```
```
In net/sched/sch_generic.c (ffffffff81c96e96)
Location: include/linux/netdevice.h:3947
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/sched/sch_api.c (ffffffff81c991b2)
Location: include/linux/netdevice.h:3947
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
```
```
In net/netlink/af_netlink.c (ffffffff81caad88)
Location: include/linux/netdevice.h:3947
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_deliver_tap
```
```
In net/bpf/test_run.c (ffffffff81cb5b82)
Location: include/linux/netdevice.h:3947
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ethtool/ioctl.c (ffffffff81cb9215)
Location: include/linux/netdevice.h:3947
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_phys_id
```
```
In net/ethtool/netlink.c (ffffffff81cbe632)
Location: include/linux/netdevice.h:3947
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_start
  - net/ethtool/netlink.c:ethnl_default_dumpit
  - net/ethtool/netlink.c:ethnl_default_doit
  - net/ethtool/netlink.c:ethnl_default_doit
  - net/ethtool/netlink.c:ethnl_parse_header_dev_get
```
```
In net/ethtool/linkinfo.c (ffffffff81cc1736)
Location: include/linux/netdevice.h:3947
Inline: True
Inline callers:
  - net/ethtool/linkinfo.c:ethnl_set_linkinfo
```
```
In net/ethtool/linkmodes.c (ffffffff81cc20b1)
Location: include/linux/netdevice.h:3947
Inline: True
Inline callers:
  - net/ethtool/linkmodes.c:ethnl_set_linkmodes
```
```
In net/ethtool/debug.c (ffffffff81cc2675)
Location: include/linux/netdevice.h:3947
Inline: True
Inline callers:
  - net/ethtool/debug.c:ethnl_set_debug
```
```
In net/ethtool/wol.c (ffffffff81cc29f4)
Location: include/linux/netdevice.h:3947
Inline: True
Inline callers:
  - net/ethtool/wol.c:ethnl_set_wol
```
```
In net/ethtool/features.c (ffffffff81cc305d)
Location: include/linux/netdevice.h:3947
Inline: True
Inline callers:
  - net/ethtool/features.c:ethnl_set_features
```
```
In net/ethtool/privflags.c (ffffffff81cc3690)
Location: include/linux/netdevice.h:3947
Inline: True
Inline callers:
  - net/ethtool/privflags.c:ethnl_set_privflags
```
```
In net/ethtool/rings.c (ffffffff81cc3c8f)
Location: include/linux/netdevice.h:3947
Inline: True
Inline callers:
  - net/ethtool/rings.c:ethnl_set_rings
```
```
In net/ethtool/channels.c (ffffffff81cc428b)
Location: include/linux/netdevice.h:3947
Inline: True
Inline callers:
  - net/ethtool/channels.c:ethnl_set_channels
```
```
In net/ethtool/coalesce.c (ffffffff81cc4d08)
Location: include/linux/netdevice.h:3947
Inline: True
Inline callers:
  - net/ethtool/coalesce.c:ethnl_set_coalesce
```
```
In net/ethtool/pause.c (ffffffff81cc51b6)
Location: include/linux/netdevice.h:3947
Inline: True
Inline callers:
  - net/ethtool/pause.c:ethnl_set_pause
```
```
In net/ethtool/eee.c (ffffffff81cc563e)
Location: include/linux/netdevice.h:3947
Inline: True
Inline callers:
  - net/ethtool/eee.c:ethnl_set_eee
```
```
In net/ethtool/cabletest.c (ffffffff81cc668d)
Location: include/linux/netdevice.h:3947
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_act_cable_test_tdr
  - net/ethtool/cabletest.c:ethnl_act_cable_test
```
```
In net/ethtool/tunnels.c (ffffffff81cc6dc5)
Location: include/linux/netdevice.h:3947
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_start
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
```
```
In net/ethtool/fec.c (ffffffff81cc777d)
Location: include/linux/netdevice.h:3947
Inline: True
Inline callers:
  - net/ethtool/fec.c:ethnl_set_fec
```
```
In net/ethtool/module.c (ffffffff81cc8ba8)
Location: include/linux/netdevice.h:3947
Inline: True
Inline callers:
  - net/ethtool/module.c:ethnl_set_module
```
```
In net/netfilter/nf_queue.c (ffffffff81ccb646)
Location: include/linux/netdevice.h:3947
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
```
```
In net/ipv4/route.c (ffffffff81cd1027)
Location: include/linux/netdevice.h:3947
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_flush_dev
```
```
In net/ipv4/ip_sockglue.c (ffffffff81ce0d1e)
Location: include/linux/netdevice.h:3947
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81d25815)
Location: include/linux/netdevice.h:3947
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_build_probe
```
```
In net/ipv4/devinet.c (ffffffff81d2639e)
Location: include/linux/netdevice.h:3947
Inline: True
Inline callers:
  - net/ipv4/devinet.c:in_dev_finish_destroy
```
```
In net/ipv4/fib_semantics.c (ffffffff81d37c11)
Location: include/linux/netdevice.h:3947
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nh_common_release
```
```
In net/ipv4/ipmr.c (ffffffff81d5362c)
Location: include/linux/netdevice.h:3947
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
  - net/ipv4/ipmr.c:ipmr_new_tunnel
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d62776)
Location: include/linux/netdevice.h:3947
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_ifdown
```
```
In net/xfrm/xfrm_state.c (ffffffff81d6d7f4)
Location: include/linux/netdevice.h:3947
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
```
```
In net/xfrm/xfrm_input.c (ffffffff81d760c5)
Location: include/linux/netdevice.h:3947
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_device.c (ffffffff81d799ac)
Location: include/linux/netdevice.h:3947
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
```
```
In net/ipv6/addrconf.c (ffffffff81d9931b)
Location: include/linux/netdevice.h:3947
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:ipv6_add_dev
```
```
In net/ipv6/route.c (ffffffff81da95bf)
Location: include/linux/netdevice.h:3947
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:rt6_probe_deferred
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81db23af)
Location: include/linux/netdevice.h:3947
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff81dbfc4c)
Location: include/linux/netdevice.h:3947
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ip6mr.c (ffffffff81dda08f)
Location: include/linux/netdevice.h:3947
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mif6_add
  - net/ipv6/ip6mr.c:mif6_add
  - net/ipv6/ip6mr.c:mif6_delete
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81ddf058)
Location: include/linux/netdevice.h:3947
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
```
```
In net/ipv6/addrconf_core.c (ffffffff81dec853)
Location: include/linux/netdevice.h:3947
Inline: True
Inline callers:
  - net/ipv6/addrconf_core.c:in6_dev_finish_destroy
```
```
In net/packet/af_packet.c (ffffffff81df2c72)
Location: include/linux/netdevice.h:3947
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81e016a6)
Location: include/linux/netdevice.h:3947
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
```
In net/switchdev/switchdev.c (ffffffff81e0c708)
Location: include/linux/netdevice.h:3947
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_deferred_process
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81e14c90)
Location: include/linux/netdevice.h:3947
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
```
```
In net/xdp/xsk.c (ffffffff81e17420)
Location: include/linux/netdevice.h:3947
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_notifier
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk.c:xsk_release
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81e1acbd)
Location: include/linux/netdevice.h:3947
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_release_deferred
  - net/xdp/xsk_buff_pool.c:xp_assign_dev
```
```
In net/mctp/device.c (ffffffff81e38765)
Location: include/linux/netdevice.h:3947
Inline: True
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
In kernel/bpf/devmap.c (ffffffff8131d301)
Location: include/linux/netdevice.h:3991
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:__dev_map_alloc_node
  - kernel/bpf/devmap.c:__dev_map_entry_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/devmap.c:dev_map_free
```
```
In kernel/bpf/offload.c (ffffffff81322066)
Location: include/linux/netdevice.h:3991
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_prog_offload_init
  - kernel/bpf/offload.c:bpf_prog_offload_init
```
```
In security/selinux/netif.c (ffffffff816805f7)
Location: include/linux/netdevice.h:3991
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_sid_slow
```
```
In security/lsm_audit.c (ffffffff816a5b2e)
Location: include/linux/netdevice.h:3991
Inline: True
Inline callers:
  - security/lsm_audit.c:dump_common_audit_data
```
```
In drivers/net/tun.c (ffffffff81bede10)
Location: include/linux/netdevice.h:3991
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_show_fdinfo
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:tun_peek_len
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_chr_read_iter
  - drivers/net/tun.c:tun_chr_write_iter
  - drivers/net/tun.c:tun_chr_poll
```
```
In net/core/sock.c (ffffffff81d9e845)
Location: include/linux/netdevice.h:3991
Inline: True
Inline callers:
  - net/core/sock.c:sock_set_timestamping
```
```
In net/core/dev.c (ffffffff81dd0f25)
Location: include/linux/netdevice.h:3991
Inline: True
Inline callers:
  - net/core/dev.c:unregister_netdevice_many_notify
  - net/core/dev.c:bpf_xdp_link_attach
  - net/core/dev.c:bpf_xdp_link_attach
  - net/core/dev.c:__netdev_adjacent_dev_remove
  - net/core/dev.c:__netdev_adjacent_dev_insert
```
```
In net/core/dst.c (ffffffff81dd3a4e)
Location: include/linux/netdevice.h:3991
Inline: True
Inline callers:
  - net/core/dst.c:dst_dev_put
  - net/core/dst.c:dst_destroy
```
```
In net/core/neighbour.c (ffffffff81dd8cc1)
Location: include/linux/netdevice.h:3991
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:pneigh_delete
  - net/core/neighbour.c:pneigh_lookup
  - net/core/neighbour.c:pneigh_queue_purge
```
```
In net/core/utils.c (ffffffff81dea2ae)
Location: include/linux/netdevice.h:3991
Inline: True
Inline callers:
  - net/core/utils.c:inet6_pton
```
```
In net/core/link_watch.c (ffffffff81dea7e0)
Location: include/linux/netdevice.h:3991
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_do_dev
```
```
In net/core/dev_ioctl.c (ffffffff81e0341d)
Location: include/linux/netdevice.h:3991
Inline: True
Inline callers:
  - net/core/dev_ioctl.c:dev_ifsioc
```
```
In net/core/net-sysfs.c (ffffffff81e0b34d)
Location: include/linux/netdevice.h:3991
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_queue_release
  - net/core/net-sysfs.c:rx_queue_release
```
```
In net/core/netpoll.c (ffffffff81e123a8)
Location: include/linux/netdevice.h:3991
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_cleanup
  - net/core/netpoll.c:netpoll_setup
```
```
In net/core/drop_monitor.c (ffffffff81e24903)
Location: include/linux/netdevice.h:3991
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_monitor_stop
  - net/core/drop_monitor.c:net_dm_hw_monitor_start
  - net/core/drop_monitor.c:net_dm_hw_trap_packet_probe
  - net/core/drop_monitor.c:net_dm_hw_packet_work
```
```
In net/core/netprio_cgroup.c (ffffffff81e274c1)
Location: include/linux/netdevice.h:3991
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:write_priomap
```
```
In net/core/lwt_bpf.c (ffffffff81e2964b)
Location: include/linux/netdevice.h:3991
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_input_reroute
```
```
In net/sched/sch_generic.c (ffffffff81e52c76)
Location: include/linux/netdevice.h:3991
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/sched/sch_api.c (ffffffff81e550a2)
Location: include/linux/netdevice.h:3991
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:qdisc_create
```
```
In net/netlink/af_netlink.c (ffffffff81e67ed5)
Location: include/linux/netdevice.h:3991
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_deliver_tap
```
```
In net/bpf/test_run.c (ffffffff81e74052)
Location: include/linux/netdevice.h:3991
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ethtool/ioctl.c (ffffffff81e78096)
Location: include/linux/netdevice.h:3991
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_phys_id
```
```
In net/ethtool/netlink.c (ffffffff81e7d112)
Location: include/linux/netdevice.h:3991
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_start
  - net/ethtool/netlink.c:ethnl_default_dumpit
  - net/ethtool/netlink.c:ethnl_default_doit
  - net/ethtool/netlink.c:ethnl_default_doit
  - net/ethtool/netlink.c:ethnl_parse_header_dev_get
```
```
In net/ethtool/linkinfo.c (ffffffff81e804b6)
Location: include/linux/netdevice.h:3991
Inline: True
Inline callers:
  - net/ethtool/linkinfo.c:ethnl_set_linkinfo
```
```
In net/ethtool/linkmodes.c (ffffffff81e80ea1)
Location: include/linux/netdevice.h:3991
Inline: True
Inline callers:
  - net/ethtool/linkmodes.c:ethnl_set_linkmodes
```
```
In net/ethtool/debug.c (ffffffff81e81895)
Location: include/linux/netdevice.h:3991
Inline: True
Inline callers:
  - net/ethtool/debug.c:ethnl_set_debug
```
```
In net/ethtool/wol.c (ffffffff81e81cc1)
Location: include/linux/netdevice.h:3991
Inline: True
Inline callers:
  - net/ethtool/wol.c:ethnl_set_wol
```
```
In net/ethtool/features.c (ffffffff81e8235d)
Location: include/linux/netdevice.h:3991
Inline: True
Inline callers:
  - net/ethtool/features.c:ethnl_set_features
```
```
In net/ethtool/privflags.c (ffffffff81e829f0)
Location: include/linux/netdevice.h:3991
Inline: True
Inline callers:
  - net/ethtool/privflags.c:ethnl_set_privflags
```
```
In net/ethtool/rings.c (ffffffff81e8302f)
Location: include/linux/netdevice.h:3991
Inline: True
Inline callers:
  - net/ethtool/rings.c:ethnl_set_rings
```
```
In net/ethtool/channels.c (ffffffff81e836c2)
Location: include/linux/netdevice.h:3991
Inline: True
Inline callers:
  - net/ethtool/channels.c:ethnl_set_channels
```
```
In net/ethtool/coalesce.c (ffffffff81e841de)
Location: include/linux/netdevice.h:3991
Inline: True
Inline callers:
  - net/ethtool/coalesce.c:ethnl_set_coalesce
```
```
In net/ethtool/pause.c (ffffffff81e846c6)
Location: include/linux/netdevice.h:3991
Inline: True
Inline callers:
  - net/ethtool/pause.c:ethnl_set_pause
```
```
In net/ethtool/eee.c (ffffffff81e84b8e)
Location: include/linux/netdevice.h:3991
Inline: True
Inline callers:
  - net/ethtool/eee.c:ethnl_set_eee
```
```
In net/ethtool/cabletest.c (ffffffff81e85ccd)
Location: include/linux/netdevice.h:3991
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_act_cable_test_tdr
  - net/ethtool/cabletest.c:ethnl_act_cable_test
```
```
In net/ethtool/tunnels.c (ffffffff81e86405)
Location: include/linux/netdevice.h:3991
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_start
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
```
```
In net/ethtool/fec.c (ffffffff81e86ded)
Location: include/linux/netdevice.h:3991
Inline: True
Inline callers:
  - net/ethtool/fec.c:ethnl_set_fec
```
```
In net/ethtool/module.c (ffffffff81e883b8)
Location: include/linux/netdevice.h:3991
Inline: True
Inline callers:
  - net/ethtool/module.c:ethnl_set_module
```
```
In net/ethtool/pse-pd.c (ffffffff81e88703)
Location: include/linux/netdevice.h:3991
Inline: True
Inline callers:
  - net/ethtool/pse-pd.c:ethnl_set_pse
```
```
In net/netfilter/nf_queue.c (ffffffff81e8b456)
Location: include/linux/netdevice.h:3991
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
```
```
In net/ipv4/route.c (ffffffff81e9129e)
Location: include/linux/netdevice.h:3991
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_flush_dev
```
```
In net/ipv4/ip_sockglue.c (ffffffff81ea1116)
Location: include/linux/netdevice.h:3991
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
```
```
In net/ipv4/icmp.c (ffffffff81eed0a5)
Location: include/linux/netdevice.h:3991
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_build_probe
```
```
In net/ipv4/devinet.c (ffffffff81eee05f)
Location: include/linux/netdevice.h:3991
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff81f00061)
Location: include/linux/netdevice.h:3991
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nh_common_release
```
```
In net/ipv4/ipmr.c (ffffffff81f1d2eb)
Location: include/linux/netdevice.h:3991
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
  - net/ipv4/ipmr.c:ipmr_new_tunnel
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f2d286)
Location: include/linux/netdevice.h:3991
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_ifdown
  - net/xfrm/xfrm_policy.c:xfrm_policy_destroy
```
```
In net/xfrm/xfrm_state.c (ffffffff81f40b90)
Location: include/linux/netdevice.h:3991
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
```
```
In net/xfrm/xfrm_input.c (ffffffff81f42805)
Location: include/linux/netdevice.h:3991
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_device.c (ffffffff81f46454)
Location: include/linux/netdevice.h:3991
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_policy_add
  - net/xfrm/xfrm_device.c:xfrm_dev_policy_add
  - net/xfrm/xfrm_device.c:xfrm_dev_policy_add
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
```
```
In net/ipv6/addrconf.c (ffffffff81f6803b)
Location: include/linux/netdevice.h:3991
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:ipv6_add_dev
```
```
In net/ipv6/route.c (ffffffff81f78d42)
Location: include/linux/netdevice.h:3991
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:rt6_probe_deferred
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81f80e01)
Location: include/linux/netdevice.h:3991
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
```
```
In net/ipv6/icmp.c (ffffffff81f9039b)
Location: include/linux/netdevice.h:3991
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ip6mr.c (ffffffff81fabd39)
Location: include/linux/netdevice.h:3991
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mif6_add
  - net/ipv6/ip6mr.c:mif6_add
  - net/ipv6/ip6mr.c:mif6_delete
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81fb1288)
Location: include/linux/netdevice.h:3991
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
```
```
In net/ipv6/addrconf_core.c (ffffffff81fc05e3)
Location: include/linux/netdevice.h:3991
Inline: True
Inline callers:
  - net/ipv6/addrconf_core.c:in6_dev_finish_destroy
```
```
In net/packet/af_packet.c (ffffffff81fc7062)
Location: include/linux/netdevice.h:3991
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81fd6506)
Location: include/linux/netdevice.h:3991
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
```
In net/switchdev/switchdev.c (ffffffff81fe2838)
Location: include/linux/netdevice.h:3991
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_deferred_process
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81febba0)
Location: include/linux/netdevice.h:3991
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
```
```
In net/xdp/xsk.c (ffffffff81fede51)
Location: include/linux/netdevice.h:3991
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_notifier
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk.c:xsk_release
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81ff21cd)
Location: include/linux/netdevice.h:3991
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_release_deferred
  - net/xdp/xsk_buff_pool.c:xp_assign_dev
```
```
In net/mctp/device.c (ffffffff82011a25)
Location: include/linux/netdevice.h:3991
Inline: True
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
In kernel/bpf/devmap.c (ffffffff8134d0b1)
Location: include/linux/netdevice.h:4050
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:__dev_map_alloc_node
  - kernel/bpf/devmap.c:__dev_map_entry_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/devmap.c:dev_map_free
```
```
In kernel/bpf/offload.c (ffffffff81351ed7)
Location: include/linux/netdevice.h:4050
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_prog_dev_bound_init
```
```
In security/selinux/netif.c (ffffffff816b86c7)
Location: include/linux/netdevice.h:4050
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_sid_slow
```
```
In security/lsm_audit.c (ffffffff816de425)
Location: include/linux/netdevice.h:4050
Inline: True
Inline callers:
  - security/lsm_audit.c:dump_common_audit_data
```
```
In drivers/net/tun.c (ffffffff81c46340)
Location: include/linux/netdevice.h:4050
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_show_fdinfo
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:tun_peek_len
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_chr_read_iter
  - drivers/net/tun.c:tun_chr_write_iter
  - drivers/net/tun.c:tun_chr_poll
```
```
In drivers/net/net_failover.c (ffffffff81c6ed05)
Location: include/linux/netdevice.h:4050
Inline: True
Inline callers:
  - drivers/net/net_failover.c:net_failover_slave_unregister
  - drivers/net/net_failover.c:net_failover_slave_register
```
```
In net/core/sock.c (ffffffff81e0d055)
Location: include/linux/netdevice.h:4050
Inline: True
Inline callers:
  - net/core/sock.c:sock_set_timestamping
```
```
In net/core/dev.c (ffffffff81e41b53)
Location: include/linux/netdevice.h:4050
Inline: True
Inline callers:
  - net/core/dev.c:unregister_netdevice_many_notify
  - net/core/dev.c:bpf_xdp_link_attach
  - net/core/dev.c:bpf_xdp_link_attach
  - net/core/dev.c:__netdev_adjacent_dev_remove
  - net/core/dev.c:__netdev_adjacent_dev_insert
```
```
In net/core/dst.c (ffffffff81e4480e)
Location: include/linux/netdevice.h:4050
Inline: True
Inline callers:
  - net/core/dst.c:dst_dev_put
  - net/core/dst.c:dst_destroy
```
```
In net/core/neighbour.c (ffffffff81e49b47)
Location: include/linux/netdevice.h:4050
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:pneigh_delete
  - net/core/neighbour.c:pneigh_lookup
  - net/core/neighbour.c:pneigh_queue_purge
```
```
In net/core/utils.c (ffffffff81e5ba9e)
Location: include/linux/netdevice.h:4050
Inline: True
Inline callers:
  - net/core/utils.c:inet6_pton
```
```
In net/core/link_watch.c (ffffffff81e5bfc0)
Location: include/linux/netdevice.h:4050
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_do_dev
```
```
In net/core/dev_ioctl.c (ffffffff81e75ccc)
Location: include/linux/netdevice.h:4050
Inline: True
Inline callers:
  - net/core/dev_ioctl.c:dev_ifsioc
```
```
In net/core/net-sysfs.c (ffffffff81e7e6fd)
Location: include/linux/netdevice.h:4050
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_queue_release
  - net/core/net-sysfs.c:rx_queue_release
```
```
In net/core/netpoll.c (ffffffff81e85be8)
Location: include/linux/netdevice.h:4050
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_cleanup
  - net/core/netpoll.c:netpoll_setup
```
```
In net/core/drop_monitor.c (ffffffff81e99b53)
Location: include/linux/netdevice.h:4050
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_monitor_stop
  - net/core/drop_monitor.c:net_dm_hw_monitor_start
  - net/core/drop_monitor.c:net_dm_hw_trap_packet_probe
  - net/core/drop_monitor.c:net_dm_hw_packet_work
```
```
In net/core/netprio_cgroup.c (ffffffff81e9cad1)
Location: include/linux/netdevice.h:4050
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:write_priomap
```
```
In net/core/lwt_bpf.c (ffffffff81e9ec7b)
Location: include/linux/netdevice.h:4050
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_input_reroute
```
```
In net/core/failover.c (ffffffff81e9ff76)
Location: include/linux/netdevice.h:4050
Inline: True
Inline callers:
  - net/core/failover.c:failover_unregister
```
```
In net/sched/sch_generic.c (ffffffff81eae512)
Location: include/linux/netdevice.h:4050
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:__qdisc_destroy
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/sched/sch_api.c (ffffffff81eb0952)
Location: include/linux/netdevice.h:4050
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:qdisc_create
```
```
In net/netlink/af_netlink.c (ffffffff81ec3d2d)
Location: include/linux/netdevice.h:4050
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_deliver_tap
```
```
In net/bpf/test_run.c (ffffffff81ecfdd9)
Location: include/linux/netdevice.h:4050
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ethtool/ioctl.c (ffffffff81ed4216)
Location: include/linux/netdevice.h:4050
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_phys_id
```
```
In net/ethtool/netlink.c (ffffffff81ed9514)
Location: include/linux/netdevice.h:4050
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_set_doit
  - net/ethtool/netlink.c:ethnl_default_start
  - net/ethtool/netlink.c:ethnl_default_dumpit
  - net/ethtool/netlink.c:ethnl_default_doit
  - net/ethtool/netlink.c:ethnl_default_doit
  - net/ethtool/netlink.c:ethnl_parse_header_dev_get
```
```
In net/ethtool/features.c (ffffffff81ede9bd)
Location: include/linux/netdevice.h:4050
Inline: True
Inline callers:
  - net/ethtool/features.c:ethnl_set_features
```
```
In net/ethtool/cabletest.c (ffffffff81ee25fd)
Location: include/linux/netdevice.h:4050
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_act_cable_test_tdr
  - net/ethtool/cabletest.c:ethnl_act_cable_test
```
```
In net/ethtool/tunnels.c (ffffffff81ee2de5)
Location: include/linux/netdevice.h:4050
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_start
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
```
```
In net/netfilter/nf_queue.c (ffffffff81ee94a6)
Location: include/linux/netdevice.h:4050
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
```
```
In net/ipv4/route.c (ffffffff81eefa2b)
Location: include/linux/netdevice.h:4050
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_flush_dev
```
```
In net/ipv4/ip_sockglue.c (ffffffff81eff8c2)
Location: include/linux/netdevice.h:4050
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
```
```
In net/ipv4/icmp.c (ffffffff81f4ca45)
Location: include/linux/netdevice.h:4050
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_build_probe
```
```
In net/ipv4/devinet.c (ffffffff81f4da1f)
Location: include/linux/netdevice.h:4050
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff81f5fae1)
Location: include/linux/netdevice.h:4050
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nh_common_release
```
```
In net/ipv4/ipmr.c (ffffffff81f7ccb9)
Location: include/linux/netdevice.h:4050
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
  - net/ipv4/ipmr.c:ipmr_new_tunnel
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f8cd86)
Location: include/linux/netdevice.h:4050
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_ifdown
  - net/xfrm/xfrm_policy.c:xfrm_policy_destroy
```
```
In net/xfrm/xfrm_state.c (ffffffff81fa03f5)
Location: include/linux/netdevice.h:4050
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
```
```
In net/xfrm/xfrm_input.c (ffffffff81fa2028)
Location: include/linux/netdevice.h:4050
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_device.c (ffffffff81fa5d74)
Location: include/linux/netdevice.h:4050
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_policy_add
  - net/xfrm/xfrm_device.c:xfrm_dev_policy_add
  - net/xfrm/xfrm_device.c:xfrm_dev_policy_add
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
```
```
In net/ipv6/addrconf.c (ffffffff81fc808a)
Location: include/linux/netdevice.h:4050
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:ipv6_add_dev
```
```
In net/ipv6/route.c (ffffffff81fd8f3a)
Location: include/linux/netdevice.h:4050
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:rt6_probe_deferred
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81fe1239)
Location: include/linux/netdevice.h:4050
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
```
```
In net/ipv6/icmp.c (ffffffff81ff0bec)
Location: include/linux/netdevice.h:4050
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ip6mr.c (ffffffff8200c4d9)
Location: include/linux/netdevice.h:4050
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mif6_add
  - net/ipv6/ip6mr.c:mif6_add
  - net/ipv6/ip6mr.c:mif6_delete
```
```
In net/ipv6/xfrm6_policy.c (ffffffff8201192f)
Location: include/linux/netdevice.h:4050
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
```
```
In net/ipv6/addrconf_core.c (ffffffff82021563)
Location: include/linux/netdevice.h:4050
Inline: True
Inline callers:
  - net/ipv6/addrconf_core.c:in6_dev_finish_destroy
```
```
In net/packet/af_packet.c (ffffffff82027d7f)
Location: include/linux/netdevice.h:4050
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff820521c6)
Location: include/linux/netdevice.h:4050
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
```
In net/switchdev/switchdev.c (ffffffff8205eb58)
Location: include/linux/netdevice.h:4050
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_deferred_process
```
```
In net/ncsi/ncsi-netlink.c (ffffffff82067e40)
Location: include/linux/netdevice.h:4050
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
```
```
In net/xdp/xsk.c (ffffffff82069fb1)
Location: include/linux/netdevice.h:4050
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_notifier
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk.c:xsk_release
```
```
In net/xdp/xsk_buff_pool.c (ffffffff8206e3fd)
Location: include/linux/netdevice.h:4050
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_release_deferred
  - net/xdp/xsk_buff_pool.c:xp_assign_dev
```
```
In net/mctp/device.c (ffffffff8208e815)
Location: include/linux/netdevice.h:4050
Inline: True
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
In kernel/bpf/devmap.c (ffffffff813745dd)
Location: include/linux/netdevice.h:4117
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:__dev_map_alloc_node
  - kernel/bpf/devmap.c:__dev_map_entry_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/devmap.c:dev_map_free
```
```
In kernel/bpf/offload.c (ffffffff813793c2)
Location: include/linux/netdevice.h:4117
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_prog_dev_bound_init
```
```
In security/selinux/netif.c (ffffffff816f50f1)
Location: include/linux/netdevice.h:4117
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_sid_slow
```
```
In security/lsm_audit.c (ffffffff8171afe9)
Location: include/linux/netdevice.h:4117
Inline: True
Inline callers:
  - security/lsm_audit.c:dump_common_audit_data
```
```
In drivers/net/tun.c (ffffffff81cfbc50)
Location: include/linux/netdevice.h:4117
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_show_fdinfo
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:tun_peek_len
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_chr_read_iter
  - drivers/net/tun.c:tun_chr_write_iter
  - drivers/net/tun.c:tun_chr_poll
```
```
In drivers/net/net_failover.c (ffffffff81d2359a)
Location: include/linux/netdevice.h:4117
Inline: True
Inline callers:
  - drivers/net/net_failover.c:net_failover_slave_unregister
  - drivers/net/net_failover.c:net_failover_slave_register
```
```
In net/core/sock.c (ffffffff81ec99f4)
Location: include/linux/netdevice.h:4117
Inline: True
Inline callers:
  - net/core/sock.c:sock_set_timestamping
```
```
In net/core/dev.c (ffffffff81f00555)
Location: include/linux/netdevice.h:4117
Inline: True
Inline callers:
  - net/core/dev.c:unregister_netdevice_many_notify
  - net/core/dev.c:bpf_xdp_link_attach
  - net/core/dev.c:bpf_xdp_link_attach
  - net/core/dev.c:__netdev_adjacent_dev_remove
  - net/core/dev.c:__netdev_adjacent_dev_insert
```
```
In net/core/dst.c (ffffffff81f03469)
Location: include/linux/netdevice.h:4117
Inline: True
Inline callers:
  - net/core/dst.c:dst_dev_put
  - net/core/dst.c:dst_destroy
```
```
In net/core/neighbour.c (ffffffff81f08864)
Location: include/linux/netdevice.h:4117
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:pneigh_delete
  - net/core/neighbour.c:pneigh_lookup
  - net/core/neighbour.c:pneigh_queue_purge
```
```
In net/core/utils.c (ffffffff81f1ae5e)
Location: include/linux/netdevice.h:4117
Inline: True
Inline callers:
  - net/core/utils.c:inet6_pton
```
```
In net/core/link_watch.c (ffffffff81f1b393)
Location: include/linux/netdevice.h:4117
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_do_dev
```
```
In net/core/dev_ioctl.c (ffffffff81f35c4b)
Location: include/linux/netdevice.h:4117
Inline: True
Inline callers:
  - net/core/dev_ioctl.c:dev_ifsioc
```
```
In net/core/net-sysfs.c (ffffffff81f3f60d)
Location: include/linux/netdevice.h:4117
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_queue_release
  - net/core/net-sysfs.c:rx_queue_release
```
```
In net/core/netpoll.c (ffffffff81f47bc8)
Location: include/linux/netdevice.h:4117
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_cleanup
  - net/core/netpoll.c:netpoll_setup
```
```
In net/core/drop_monitor.c (ffffffff81f5c283)
Location: include/linux/netdevice.h:4117
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_monitor_stop
  - net/core/drop_monitor.c:net_dm_hw_monitor_start
  - net/core/drop_monitor.c:net_dm_hw_trap_packet_probe
  - net/core/drop_monitor.c:net_dm_hw_packet_work
```
```
In net/core/netprio_cgroup.c (ffffffff81f5f1f1)
Location: include/linux/netdevice.h:4117
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:write_priomap
```
```
In net/core/lwt_bpf.c (ffffffff81f613eb)
Location: include/linux/netdevice.h:4117
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_input_reroute
```
```
In net/core/failover.c (ffffffff81f62707)
Location: include/linux/netdevice.h:4117
Inline: True
Inline callers:
  - net/core/failover.c:failover_unregister
```
```
In net/sched/sch_generic.c (ffffffff81f70f89)
Location: include/linux/netdevice.h:4117
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:__qdisc_destroy
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/sched/sch_api.c (ffffffff81f733c2)
Location: include/linux/netdevice.h:4117
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:qdisc_create
```
```
In net/netlink/af_netlink.c (ffffffff81f870ed)
Location: include/linux/netdevice.h:4117
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_deliver_tap
```
```
In net/bpf/test_run.c (ffffffff81f9372c)
Location: include/linux/netdevice.h:4117
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ethtool/ioctl.c (ffffffff81f97c26)
Location: include/linux/netdevice.h:4117
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_phys_id
```
```
In net/ethtool/netlink.c (ffffffff81f9d3e4)
Location: include/linux/netdevice.h:4117
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_set_doit
  - net/ethtool/netlink.c:ethnl_default_start
  - net/ethtool/netlink.c:ethnl_default_dumpit
  - net/ethtool/netlink.c:ethnl_default_doit
  - net/ethtool/netlink.c:ethnl_default_doit
  - net/ethtool/netlink.c:ethnl_parse_header_dev_get
```
```
In net/ethtool/features.c (ffffffff81fa282f)
Location: include/linux/netdevice.h:4117
Inline: True
Inline callers:
  - net/ethtool/features.c:ethnl_set_features
```
```
In net/ethtool/cabletest.c (ffffffff81fa648d)
Location: include/linux/netdevice.h:4117
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_act_cable_test_tdr
  - net/ethtool/cabletest.c:ethnl_act_cable_test
```
```
In net/ethtool/tunnels.c (ffffffff81fa6c75)
Location: include/linux/netdevice.h:4117
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_start
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
```
```
In net/netfilter/nf_queue.c (ffffffff81fad216)
Location: include/linux/netdevice.h:4117
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
```
```
In net/ipv4/route.c (ffffffff81fb3b7b)
Location: include/linux/netdevice.h:4117
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_flush_dev
```
```
In net/ipv4/ip_sockglue.c (ffffffff81fc3b52)
Location: include/linux/netdevice.h:4117
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
```
```
In net/ipv4/icmp.c (ffffffff82012b55)
Location: include/linux/netdevice.h:4117
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_build_probe
```
```
In net/ipv4/devinet.c (ffffffff82013b3f)
Location: include/linux/netdevice.h:4117
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff820260b1)
Location: include/linux/netdevice.h:4117
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nh_common_release
```
```
In net/ipv4/ipmr.c (ffffffff820433b9)
Location: include/linux/netdevice.h:4117
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
  - net/ipv4/ipmr.c:ipmr_new_tunnel
```
```
In net/xfrm/xfrm_policy.c (ffffffff8205a716)
Location: include/linux/netdevice.h:4117
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_ifdown
  - net/xfrm/xfrm_policy.c:xfrm_policy_destroy
```
```
In net/xfrm/xfrm_state.c (ffffffff8206d755)
Location: include/linux/netdevice.h:4117
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
```
```
In net/xfrm/xfrm_input.c (ffffffff8206f243)
Location: include/linux/netdevice.h:4117
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_device.c (ffffffff82073074)
Location: include/linux/netdevice.h:4117
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_policy_add
  - net/xfrm/xfrm_device.c:xfrm_dev_policy_add
  - net/xfrm/xfrm_device.c:xfrm_dev_policy_add
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
```
```
In net/ipv6/addrconf.c (ffffffff82095798)
Location: include/linux/netdevice.h:4117
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:ipv6_add_dev
```
```
In net/ipv6/route.c (ffffffff820a68ca)
Location: include/linux/netdevice.h:4117
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:rt6_probe_deferred
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff820ae706)
Location: include/linux/netdevice.h:4117
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
```
```
In net/ipv6/icmp.c (ffffffff820be7d9)
Location: include/linux/netdevice.h:4117
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ip6mr.c (ffffffff820db4a9)
Location: include/linux/netdevice.h:4117
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mif6_add
  - net/ipv6/ip6mr.c:mif6_add
  - net/ipv6/ip6mr.c:mif6_delete
```
```
In net/ipv6/xfrm6_policy.c (ffffffff820e08df)
Location: include/linux/netdevice.h:4117
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
```
```
In net/ipv6/addrconf_core.c (ffffffff820f0693)
Location: include/linux/netdevice.h:4117
Inline: True
Inline callers:
  - net/ipv6/addrconf_core.c:in6_dev_finish_destroy
```
```
In net/packet/af_packet.c (ffffffff820f75df)
Location: include/linux/netdevice.h:4117
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff82124946)
Location: include/linux/netdevice.h:4117
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
```
In net/switchdev/switchdev.c (ffffffff82131838)
Location: include/linux/netdevice.h:4117
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_deferred_process
```
```
In net/ncsi/ncsi-netlink.c (ffffffff8213b0c0)
Location: include/linux/netdevice.h:4117
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_set_channel_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_package_mask_nl
  - net/ncsi/ncsi-netlink.c:ncsi_send_cmd_nl
  - net/ncsi/ncsi-netlink.c:ncsi_clear_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_set_interface_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
```
```
In net/xdp/xsk.c (ffffffff8213d411)
Location: include/linux/netdevice.h:4117
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_notifier
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk.c:xsk_release
```
```
In net/xdp/xsk_buff_pool.c (ffffffff8214247d)
Location: include/linux/netdevice.h:4117
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_release_deferred
  - net/xdp/xsk_buff_pool.c:xp_assign_dev
```
```
In net/mctp/device.c (ffffffff82164d05)
Location: include/linux/netdevice.h:4117
Inline: True
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
