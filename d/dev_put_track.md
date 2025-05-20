# Function: <code>dev_put_track</code>

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
In kernel/bpf/devmap.c (ffffffff812b9fac)
Location: include/linux/netdevice.h:4007
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:__dev_map_alloc_node
  - kernel/bpf/devmap.c:__dev_map_entry_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/devmap.c:dev_map_free
```
```
In kernel/bpf/offload.c (ffffffff812bea31)
Location: include/linux/netdevice.h:4007
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_prog_offload_init
  - kernel/bpf/offload.c:bpf_prog_offload_init
```
```
In security/selinux/netif.c (ffffffff815d26e7)
Location: include/linux/netdevice.h:4007
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_sid_slow
```
```
In security/lsm_audit.c (ffffffff815f505e)
Location: include/linux/netdevice.h:4007
Inline: True
Inline callers:
  - security/lsm_audit.c:dump_common_audit_data
```
```
In drivers/net/tun.c (ffffffff81a6263b)
Location: include/linux/netdevice.h:4007
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
Location: include/linux/netdevice.h:4007
Inline: True
Inline callers:
  - net/core/sock.c:sock_set_timestamping
```
```
In net/core/dev.c (ffffffff81c16c11)
Location: include/linux/netdevice.h:4007
Inline: True
Inline callers:
  - net/core/dev.c:unregister_netdevice_many
  - net/core/dev.c:bpf_xdp_link_attach
  - net/core/dev.c:bpf_xdp_link_attach
  - net/core/dev.c:__netdev_adjacent_dev_remove
  - net/core/dev.c:__netdev_adjacent_dev_insert
```
```
In net/core/dst.c (ffffffff81c21ded)
Location: include/linux/netdevice.h:4007
Inline: True
Inline callers:
  - net/core/dst.c:dst_destroy
```
```
In net/core/neighbour.c (ffffffff81c240c9)
Location: include/linux/netdevice.h:4007
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
Location: include/linux/netdevice.h:4007
Inline: True
Inline callers:
  - net/core/utils.c:inet6_pton
```
```
In net/core/filter.c (ffffffff81c4a9cd)
Location: include/linux/netdevice.h:4007
Inline: True
Inline callers:
  - net/core/filter.c:_bpf_setsockopt
```
```
In net/core/dev_ioctl.c (ffffffff81c4e41e)
Location: include/linux/netdevice.h:4007
Inline: True
Inline callers:
  - net/core/dev_ioctl.c:dev_ifsioc
```
```
In net/core/net-sysfs.c (ffffffff81c55909)
Location: include/linux/netdevice.h:4007
Inline: True
Inline callers:
  - net/core/net-sysfs.c:rx_queue_release
```
```
In net/core/netpoll.c (ffffffff81c5bf13)
Location: include/linux/netdevice.h:4007
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_cleanup
  - net/core/netpoll.c:netpoll_setup
```
```
In net/core/drop_monitor.c (ffffffff81c6cd07)
Location: include/linux/netdevice.h:4007
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_monitor_stop
  - net/core/drop_monitor.c:net_dm_hw_monitor_start
  - net/core/drop_monitor.c:net_dm_hw_trap_packet_probe
  - net/core/drop_monitor.c:net_dm_hw_packet_work
```
```
In net/core/netprio_cgroup.c (ffffffff81c6f671)
Location: include/linux/netdevice.h:4007
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:write_priomap
```
```
In net/core/lwt_bpf.c (ffffffff81c7158b)
Location: include/linux/netdevice.h:4007
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_input_reroute
```
```
In net/sched/sch_generic.c (ffffffff81c96e8d)
Location: include/linux/netdevice.h:4007
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/sched/sch_api.c (ffffffff81c991b2)
Location: include/linux/netdevice.h:4007
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
```
```
In net/netlink/af_netlink.c (ffffffff81caad83)
Location: include/linux/netdevice.h:4007
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_deliver_tap
```
```
In net/bpf/test_run.c (ffffffff81cb5b82)
Location: include/linux/netdevice.h:4007
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ethtool/ioctl.c (ffffffff81cb9210)
Location: include/linux/netdevice.h:4007
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_phys_id
```
```
In net/ethtool/netlink.c (ffffffff81cbe632)
Location: include/linux/netdevice.h:4007
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_start
  - net/ethtool/netlink.c:ethnl_default_dumpit
  - net/ethtool/netlink.c:ethnl_default_doit
  - net/ethtool/netlink.c:ethnl_default_doit
  - net/ethtool/netlink.c:ethnl_parse_header_dev_get
```
```
In net/ethtool/linkinfo.c (ffffffff81cc1731)
Location: include/linux/netdevice.h:4007
Inline: True
Inline callers:
  - net/ethtool/linkinfo.c:ethnl_set_linkinfo
```
```
In net/ethtool/linkmodes.c (ffffffff81cc20a8)
Location: include/linux/netdevice.h:4007
Inline: True
Inline callers:
  - net/ethtool/linkmodes.c:ethnl_set_linkmodes
```
```
In net/ethtool/debug.c (ffffffff81cc2670)
Location: include/linux/netdevice.h:4007
Inline: True
Inline callers:
  - net/ethtool/debug.c:ethnl_set_debug
```
```
In net/ethtool/wol.c (ffffffff81cc29ef)
Location: include/linux/netdevice.h:4007
Inline: True
Inline callers:
  - net/ethtool/wol.c:ethnl_set_wol
```
```
In net/ethtool/features.c (ffffffff81cc3058)
Location: include/linux/netdevice.h:4007
Inline: True
Inline callers:
  - net/ethtool/features.c:ethnl_set_features
```
```
In net/ethtool/privflags.c (ffffffff81cc368b)
Location: include/linux/netdevice.h:4007
Inline: True
Inline callers:
  - net/ethtool/privflags.c:ethnl_set_privflags
```
```
In net/ethtool/rings.c (ffffffff81cc3c4d)
Location: include/linux/netdevice.h:4007
Inline: True
Inline callers:
  - net/ethtool/rings.c:ethnl_set_rings
```
```
In net/ethtool/channels.c (ffffffff81cc4286)
Location: include/linux/netdevice.h:4007
Inline: True
Inline callers:
  - net/ethtool/channels.c:ethnl_set_channels
```
```
In net/ethtool/coalesce.c (ffffffff81cc4cc3)
Location: include/linux/netdevice.h:4007
Inline: True
Inline callers:
  - net/ethtool/coalesce.c:ethnl_set_coalesce
```
```
In net/ethtool/pause.c (ffffffff81cc51b1)
Location: include/linux/netdevice.h:4007
Inline: True
Inline callers:
  - net/ethtool/pause.c:ethnl_set_pause
```
```
In net/ethtool/eee.c (ffffffff81cc5639)
Location: include/linux/netdevice.h:4007
Inline: True
Inline callers:
  - net/ethtool/eee.c:ethnl_set_eee
```
```
In net/ethtool/cabletest.c (ffffffff81cc6688)
Location: include/linux/netdevice.h:4007
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_act_cable_test_tdr
  - net/ethtool/cabletest.c:ethnl_act_cable_test
```
```
In net/ethtool/tunnels.c (ffffffff81cc6dc5)
Location: include/linux/netdevice.h:4007
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_start
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
```
```
In net/ethtool/fec.c (ffffffff81cc7778)
Location: include/linux/netdevice.h:4007
Inline: True
Inline callers:
  - net/ethtool/fec.c:ethnl_set_fec
```
```
In net/ethtool/module.c (ffffffff81cc8ba3)
Location: include/linux/netdevice.h:4007
Inline: True
Inline callers:
  - net/ethtool/module.c:ethnl_set_module
```
```
In net/netfilter/nf_queue.c (ffffffff81ccb63e)
Location: include/linux/netdevice.h:4007
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
```
```
In net/ipv4/ip_sockglue.c (ffffffff81ce0d1e)
Location: include/linux/netdevice.h:4007
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81d25815)
Location: include/linux/netdevice.h:4007
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_build_probe
```
```
In net/ipv4/devinet.c (ffffffff81d26399)
Location: include/linux/netdevice.h:4007
Inline: True
Inline callers:
  - net/ipv4/devinet.c:in_dev_finish_destroy
```
```
In net/ipv4/fib_semantics.c (ffffffff81d37c0c)
Location: include/linux/netdevice.h:4007
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nh_common_release
```
```
In net/ipv4/ipmr.c (ffffffff81d5382c)
Location: include/linux/netdevice.h:4007
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
  - net/ipv4/ipmr.c:ipmr_new_tunnel
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d62771)
Location: include/linux/netdevice.h:4007
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_ifdown
```
```
In net/xfrm/xfrm_state.c (ffffffff81d6d7f4)
Location: include/linux/netdevice.h:4007
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
```
```
In net/xfrm/xfrm_input.c (ffffffff81d760c0)
Location: include/linux/netdevice.h:4007
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_device.c (ffffffff81d799a7)
Location: include/linux/netdevice.h:4007
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
```
```
In net/ipv6/addrconf.c (ffffffff81d99316)
Location: include/linux/netdevice.h:4007
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:ipv6_add_dev
```
```
In net/ipv6/route.c (ffffffff81da796c)
Location: include/linux/netdevice.h:4007
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:rt6_probe_deferred
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81db23af)
Location: include/linux/netdevice.h:4007
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff81dbfc4c)
Location: include/linux/netdevice.h:4007
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ip6mr.c (ffffffff81dda08f)
Location: include/linux/netdevice.h:4007
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mif6_add
  - net/ipv6/ip6mr.c:mif6_add
  - net/ipv6/ip6mr.c:mif6_delete
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81ddf058)
Location: include/linux/netdevice.h:4007
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
```
```
In net/ipv6/addrconf_core.c (ffffffff81dec84e)
Location: include/linux/netdevice.h:4007
Inline: True
Inline callers:
  - net/ipv6/addrconf_core.c:in6_dev_finish_destroy
```
```
In net/packet/af_packet.c (ffffffff81df2c6d)
Location: include/linux/netdevice.h:4007
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
Location: include/linux/netdevice.h:4007
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
```
In net/switchdev/switchdev.c (ffffffff81e0c703)
Location: include/linux/netdevice.h:4007
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_deferred_process
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81e14c90)
Location: include/linux/netdevice.h:4007
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
In net/xdp/xsk.c (ffffffff81e1741b)
Location: include/linux/netdevice.h:4007
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_notifier
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk.c:xsk_release
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81e1acb8)
Location: include/linux/netdevice.h:4007
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_release_deferred
  - net/xdp/xsk_buff_pool.c:xp_assign_dev
```
```
In net/mctp/device.c (ffffffff81e38760)
Location: include/linux/netdevice.h:4007
Inline: True
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
