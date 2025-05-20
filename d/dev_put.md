# Function: <code>dev_put</code>

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
In kernel/sysctl_binary.c (ffffffff81089ddc)
Location: include/linux/netdevice.h:3112
Inline: True
Inline callers:
  - kernel/sysctl_binary.c:do_sysctl
```
```
In security/selinux/netif.c (ffffffff8134cf45)
Location: include/linux/netdevice.h:3112
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_sid
```
```
In security/lsm_audit.c (ffffffff813665a7)
Location: include/linux/netdevice.h:3112
Inline: True
Inline callers:
  - security/lsm_audit.c:common_lsm_audit
```
```
In drivers/net/tun.c (ffffffff815edacd)
Location: include/linux/netdevice.h:3112
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
In net/core/dev.c (ffffffff817160aa)
Location: include/linux/netdevice.h:3112
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_adjacent_dev_remove
  - net/core/dev.c:rollback_registered_many
```
```
In net/core/ethtool.c (ffffffff817214bf)
Location: include/linux/netdevice.h:3112
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
```
```
In net/core/dst.c (ffffffff8172374d)
Location: include/linux/netdevice.h:3112
Inline: True
Inline callers:
  - net/core/dst.c:dst_ifdown
  - net/core/dst.c:dst_destroy
```
```
In net/core/neighbour.c (ffffffff8172435d)
Location: include/linux/netdevice.h:3112
Inline: True
Inline callers:
  - net/core/neighbour.c:pneigh_queue_purge
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:neigh_parms_release
  - net/core/neighbour.c:pneigh_lookup
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:neigh_ifdown
  - net/core/neighbour.c:pneigh_delete
```
```
In net/core/link_watch.c (ffffffff8173057f)
Location: include/linux/netdevice.h:3112
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_do_dev
```
```
In net/core/net-sysfs.c (ffffffff81735def)
Location: include/linux/netdevice.h:3112
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_queue_release
  - net/core/net-sysfs.c:rx_queue_release
```
```
In net/core/netpoll.c (ffffffff8173876e)
Location: include/linux/netdevice.h:3112
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_cleanup
```
```
In net/core/netprio_cgroup.c (ffffffff8173dce5)
Location: include/linux/netdevice.h:3112
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:write_priomap
```
```
In net/sched/sch_generic.c (ffffffff81740f6f)
Location: include/linux/netdevice.h:3112
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:dev_watchdog
  - net/sched/sch_generic.c:dev_deactivate_many
```
```
In net/sched/sch_api.c (ffffffff8174374a)
Location: include/linux/netdevice.h:3112
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:qdisc_create
```
```
In net/netlink/af_netlink.c (ffffffff8174b2d6)
Location: include/linux/netdevice.h:3112
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_deliver_tap
```
```
In net/netfilter/nf_queue.c (ffffffff8175273d)
Location: include/linux/netdevice.h:3112
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
```
```
In net/ipv4/route.c (ffffffff81757aba)
Location: include/linux/netdevice.h:3112
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_flush_dev
```
```
In net/ipv4/ip_sockglue.c (ffffffff81761507)
Location: include/linux/netdevice.h:3112
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff8178f711)
Location: include/linux/netdevice.h:3112
Inline: True
Inline callers:
  - net/ipv4/devinet.c:in_dev_finish_destroy
```
```
In net/ipv4/fib_semantics.c (ffffffff8179c1a7)
Location: include/linux/netdevice.h:3112
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
```
In net/ipv4/ipmr.c (ffffffff817a7765)
Location: include/linux/netdevice.h:3112
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_delete
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff817b0f11)
Location: include/linux/netdevice.h:3112
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_ifdown
```
```
In net/ipv6/addrconf.c (ffffffff817cbfdf)
Location: include/linux/netdevice.h:3112
Inline: True
```
```
In net/ipv6/route.c (ffffffff817d369e)
Location: include/linux/netdevice.h:3112
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_probe_deferred
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:rt6_ifdown
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff817ddc8c)
Location: include/linux/netdevice.h:3112
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff817f80a3)
Location: include/linux/netdevice.h:3112
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mif6_delete
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
```
In net/ipv6/xfrm6_policy.c (ffffffff817fbe68)
Location: include/linux/netdevice.h:3112
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
```
```
In net/ipv6/addrconf_core.c (ffffffff817ff915)
Location: include/linux/netdevice.h:3112
Inline: True
Inline callers:
  - net/ipv6/addrconf_core.c:in6_dev_finish_destroy
```
```
In net/packet/af_packet.c (ffffffff81803f0f)
Location: include/linux/netdevice.h:3112
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:packet_sendmsg
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff8180e840)
Location: include/linux/netdevice.h:3112
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
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
In kernel/sysctl_binary.c (ffffffff8108cd1a)
Location: include/linux/netdevice.h:3340
Inline: True
Inline callers:
  - kernel/sysctl_binary.c:do_sysctl
```
```
In security/selinux/netif.c (ffffffff81382f0c)
Location: include/linux/netdevice.h:3340
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_sid
```
```
In security/lsm_audit.c (ffffffff8139c6ce)
Location: include/linux/netdevice.h:3340
Inline: True
Inline callers:
  - security/lsm_audit.c:common_lsm_audit
```
```
In drivers/net/tun.c (ffffffff8164ca91)
Location: include/linux/netdevice.h:3340
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
In net/core/dev.c (ffffffff8177e8c6)
Location: include/linux/netdevice.h:3340
Inline: True
Inline callers:
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:__netdev_adjacent_dev_remove
```
```
In net/core/ethtool.c (ffffffff8178a87b)
Location: include/linux/netdevice.h:3340
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
```
```
In net/core/dst.c (ffffffff8178d1ad)
Location: include/linux/netdevice.h:3340
Inline: True
Inline callers:
  - net/core/dst.c:dst_ifdown
  - net/core/dst.c:dst_destroy
```
```
In net/core/neighbour.c (ffffffff8178e3aa)
Location: include/linux/netdevice.h:3340
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_parms_release
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:pneigh_delete
  - net/core/neighbour.c:pneigh_lookup
  - net/core/neighbour.c:neigh_ifdown
  - net/core/neighbour.c:pneigh_queue_purge
```
```
In net/core/link_watch.c (ffffffff8179acef)
Location: include/linux/netdevice.h:3340
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_do_dev
```
```
In net/core/net-sysfs.c (ffffffff817a1f9f)
Location: include/linux/netdevice.h:3340
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_queue_release
  - net/core/net-sysfs.c:rx_queue_release
```
```
In net/core/netpoll.c (ffffffff817a4cba)
Location: include/linux/netdevice.h:3340
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_cleanup
  - net/core/netpoll.c:netpoll_setup
```
```
In net/core/netprio_cgroup.c (ffffffff817aa51a)
Location: include/linux/netdevice.h:3340
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:write_priomap
```
```
In net/sched/sch_generic.c (ffffffff817aeb8e)
Location: include/linux/netdevice.h:3340
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/sched/sch_api.c (ffffffff817b05ea)
Location: include/linux/netdevice.h:3340
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:qdisc_create
```
```
In net/netlink/af_netlink.c (ffffffff817b7e0b)
Location: include/linux/netdevice.h:3340
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_deliver_tap
```
```
In net/netfilter/nf_queue.c (ffffffff817be8a2)
Location: include/linux/netdevice.h:3340
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
```
```
In net/ipv4/route.c (ffffffff817c3d6a)
Location: include/linux/netdevice.h:3340
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_flush_dev
```
```
In net/ipv4/ip_sockglue.c (ffffffff817cd856)
Location: include/linux/netdevice.h:3340
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff817fccb1)
Location: include/linux/netdevice.h:3340
Inline: True
Inline callers:
  - net/ipv4/devinet.c:in_dev_finish_destroy
```
```
In net/ipv4/fib_semantics.c (ffffffff81809d27)
Location: include/linux/netdevice.h:3340
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
```
In net/ipv4/ipmr.c (ffffffff8189074b)
Location: include/linux/netdevice.h:3340
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
```
```
In net/xfrm/xfrm_policy.c (ffffffff8181de61)
Location: include/linux/netdevice.h:3340
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_ifdown
```
```
In net/xfrm/xfrm_input.c (ffffffff81828b20)
Location: include/linux/netdevice.h:3340
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/ipv6/addrconf.c (ffffffff8183a650)
Location: include/linux/netdevice.h:3340
Inline: True
```
```
In net/ipv6/route.c (ffffffff81846fe8)
Location: include/linux/netdevice.h:3340
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_ifdown
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:rt6_probe_deferred
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff8184bd13)
Location: include/linux/netdevice.h:3340
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff8186a725)
Location: include/linux/netdevice.h:3340
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:mif6_delete
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_policy.c (ffffffff8186b738)
Location: include/linux/netdevice.h:3340
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
```
```
In net/ipv6/addrconf_core.c (ffffffff81870fc8)
Location: include/linux/netdevice.h:3340
Inline: True
Inline callers:
  - net/ipv6/addrconf_core.c:in6_dev_finish_destroy
```
```
In net/packet/af_packet.c (ffffffff81874ed0)
Location: include/linux/netdevice.h:3340
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81881cd3)
Location: include/linux/netdevice.h:3340
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
```
In net/switchdev/switchdev.c (ffffffff81889f83)
Location: include/linux/netdevice.h:3340
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_deferred_process
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
In kernel/sysctl_binary.c (ffffffff81091c9a)
Location: include/linux/netdevice.h:3294
Inline: True
Inline callers:
  - kernel/sysctl_binary.c:do_sysctl
```
```
In security/selinux/netif.c (ffffffff8139998c)
Location: include/linux/netdevice.h:3294
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_sid
```
```
In security/lsm_audit.c (ffffffff813b327e)
Location: include/linux/netdevice.h:3294
Inline: True
Inline callers:
  - security/lsm_audit.c:common_lsm_audit
```
```
In drivers/net/tun.c (ffffffff8167e7c1)
Location: include/linux/netdevice.h:3294
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
In net/core/dev.c (ffffffff817ac1b5)
Location: include/linux/netdevice.h:3294
Inline: True
Inline callers:
  - net/core/dev.c:rollback_registered_many
```
```
In net/core/ethtool.c (ffffffff817b7f99)
Location: include/linux/netdevice.h:3294
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
```
```
In net/core/dst.c (ffffffff817baa7d)
Location: include/linux/netdevice.h:3294
Inline: True
Inline callers:
  - net/core/dst.c:dst_ifdown
  - net/core/dst.c:dst_destroy
```
```
In net/core/neighbour.c (ffffffff817bbc7a)
Location: include/linux/netdevice.h:3294
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_parms_release
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:pneigh_delete
  - net/core/neighbour.c:pneigh_lookup
  - net/core/neighbour.c:neigh_ifdown
  - net/core/neighbour.c:pneigh_queue_purge
```
```
In net/core/link_watch.c (ffffffff817c8a8f)
Location: include/linux/netdevice.h:3294
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_do_dev
```
```
In net/core/net-sysfs.c (ffffffff817d094f)
Location: include/linux/netdevice.h:3294
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_queue_release
  - net/core/net-sysfs.c:rx_queue_release
```
```
In net/core/netpoll.c (ffffffff817d372a)
Location: include/linux/netdevice.h:3294
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_cleanup
  - net/core/netpoll.c:netpoll_setup
```
```
In net/core/netprio_cgroup.c (ffffffff817d905a)
Location: include/linux/netdevice.h:3294
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:write_priomap
```
```
In net/sched/sch_generic.c (ffffffff817de20e)
Location: include/linux/netdevice.h:3294
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/sched/sch_api.c (ffffffff817dfd2a)
Location: include/linux/netdevice.h:3294
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:qdisc_create
```
```
In net/netlink/af_netlink.c (ffffffff817e78eb)
Location: include/linux/netdevice.h:3294
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_deliver_tap
```
```
In net/netfilter/nf_queue.c (ffffffff817ee172)
Location: include/linux/netdevice.h:3294
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
```
```
In net/ipv4/route.c (ffffffff817f388c)
Location: include/linux/netdevice.h:3294
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_flush_dev
```
```
In net/ipv4/ip_sockglue.c (ffffffff817fd5a0)
Location: include/linux/netdevice.h:3294
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff8182dc11)
Location: include/linux/netdevice.h:3294
Inline: True
Inline callers:
  - net/ipv4/devinet.c:in_dev_finish_destroy
```
```
In net/ipv4/fib_semantics.c (ffffffff8183aea7)
Location: include/linux/netdevice.h:3294
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
```
In net/ipv4/ipmr.c (ffffffff818c4d65)
Location: include/linux/netdevice.h:3294
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
```
```
In net/xfrm/xfrm_policy.c (ffffffff8184f6e1)
Location: include/linux/netdevice.h:3294
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_ifdown
```
```
In net/xfrm/xfrm_input.c (ffffffff8185a500)
Location: include/linux/netdevice.h:3294
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/ipv6/addrconf.c (ffffffff8186c055)
Location: include/linux/netdevice.h:3294
Inline: True
```
```
In net/ipv6/route.c (ffffffff81878e2a)
Location: include/linux/netdevice.h:3294
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_ifdown
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:rt6_probe_deferred
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff8187dbe5)
Location: include/linux/netdevice.h:3294
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff8189d575)
Location: include/linux/netdevice.h:3294
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:mif6_delete
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_policy.c (ffffffff8189e598)
Location: include/linux/netdevice.h:3294
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
```
```
In net/ipv6/addrconf_core.c (ffffffff818a5518)
Location: include/linux/netdevice.h:3294
Inline: True
Inline callers:
  - net/ipv6/addrconf_core.c:in6_dev_finish_destroy
```
```
In net/packet/af_packet.c (ffffffff818a9390)
Location: include/linux/netdevice.h:3294
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff818b6583)
Location: include/linux/netdevice.h:3294
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
```
In net/switchdev/switchdev.c (ffffffff818be793)
Location: include/linux/netdevice.h:3294
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_deferred_process
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
In kernel/sysctl_binary.c (ffffffff8108ee37)
Location: include/linux/netdevice.h:3340
Inline: True
```
```
In security/selinux/netif.c (ffffffff813afda2)
Location: include/linux/netdevice.h:3340
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_sid
```
```
In security/lsm_audit.c (ffffffff813c9c42)
Location: include/linux/netdevice.h:3340
Inline: True
Inline callers:
  - security/lsm_audit.c:common_lsm_audit
```
```
In drivers/net/tun.c (ffffffff81694084)
Location: include/linux/netdevice.h:3340
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
In net/core/dev.c (ffffffff817ca70b)
Location: include/linux/netdevice.h:3340
Inline: True
Inline callers:
  - net/core/dev.c:rollback_registered_many
```
```
In net/core/ethtool.c (ffffffff817d7015)
Location: include/linux/netdevice.h:3340
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
```
```
In net/core/dst.c (ffffffff817d9588)
Location: include/linux/netdevice.h:3340
Inline: True
Inline callers:
  - net/core/dst.c:dst_dev_put
  - net/core/dst.c:dst_destroy
```
```
In net/core/neighbour.c (ffffffff817db1f6)
Location: include/linux/netdevice.h:3340
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:pneigh_delete
  - net/core/neighbour.c:pneigh_lookup
  - net/core/neighbour.c:neigh_ifdown
  - net/core/neighbour.c:pneigh_queue_purge
```
```
In net/core/utils.c (ffffffff817e73dd)
Location: include/linux/netdevice.h:3340
Inline: True
Inline callers:
  - net/core/utils.c:inet6_pton
```
```
In net/core/link_watch.c (ffffffff817e765f)
Location: include/linux/netdevice.h:3340
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_do_dev
```
```
In net/core/net-sysfs.c (ffffffff817efd4f)
Location: include/linux/netdevice.h:3340
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_queue_release
  - net/core/net-sysfs.c:rx_queue_release
```
```
In net/core/netpoll.c (ffffffff817f2a7a)
Location: include/linux/netdevice.h:3340
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_cleanup
  - net/core/netpoll.c:netpoll_setup
```
```
In net/core/netprio_cgroup.c (ffffffff817f826a)
Location: include/linux/netdevice.h:3340
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:write_priomap
```
```
In net/sched/sch_generic.c (ffffffff817fd85e)
Location: include/linux/netdevice.h:3340
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/sched/sch_api.c (ffffffff817ff1f4)
Location: include/linux/netdevice.h:3340
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:qdisc_create
```
```
In net/netlink/af_netlink.c (ffffffff818075f4)
Location: include/linux/netdevice.h:3340
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_deliver_tap
```
```
In net/netfilter/nf_queue.c (ffffffff8180e282)
Location: include/linux/netdevice.h:3340
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
```
```
In net/ipv4/route.c (ffffffff818114b4)
Location: include/linux/netdevice.h:3340
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_flush_dev
```
```
In net/ipv4/ip_sockglue.c (ffffffff8181da23)
Location: include/linux/netdevice.h:3340
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff8184f101)
Location: include/linux/netdevice.h:3340
Inline: True
Inline callers:
  - net/ipv4/devinet.c:in_dev_finish_destroy
```
```
In net/ipv4/fib_semantics.c (ffffffff8185c39f)
Location: include/linux/netdevice.h:3340
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
```
In net/ipv4/ipmr.c (ffffffff81868f66)
Location: include/linux/netdevice.h:3340
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
```
```
In net/xfrm/xfrm_policy.c (ffffffff818731ae)
Location: include/linux/netdevice.h:3340
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_ifdown
```
```
In net/xfrm/xfrm_state.c (ffffffff81879c9a)
Location: include/linux/netdevice.h:3340
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_gc_task
```
```
In net/xfrm/xfrm_input.c (ffffffff8187e404)
Location: include/linux/netdevice.h:3340
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_device.c (ffffffff8188036f)
Location: include/linux/netdevice.h:3340
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff818909bc)
Location: include/linux/netdevice.h:3340
Inline: True
```
```
In net/ipv6/route.c (ffffffff8189e0a1)
Location: include/linux/netdevice.h:3340
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_ifdown
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:rt6_probe_deferred
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff818a3cab)
Location: include/linux/netdevice.h:3340
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff818c3ba6)
Location: include/linux/netdevice.h:3340
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:mif6_delete
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_policy.c (ffffffff818c49c7)
Location: include/linux/netdevice.h:3340
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
```
```
In net/ipv6/addrconf_core.c (ffffffff818cbfe1)
Location: include/linux/netdevice.h:3340
Inline: True
Inline callers:
  - net/ipv6/addrconf_core.c:in6_dev_finish_destroy
```
```
In net/packet/af_packet.c (ffffffff818cfdb4)
Location: include/linux/netdevice.h:3340
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff818dd012)
Location: include/linux/netdevice.h:3340
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
```
In net/switchdev/switchdev.c (ffffffff818e5123)
Location: include/linux/netdevice.h:3340
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_deferred_process
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
In kernel/sysctl_binary.c (ffffffff81095ceb)
Location: include/linux/netdevice.h:3369
Inline: True
```
```
In kernel/bpf/devmap.c (ffffffff811af1d6)
Location: include/linux/netdevice.h:3369
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:__dev_map_entry_free
  - kernel/bpf/devmap.c:dev_map_free
```
```
In security/selinux/netif.c (ffffffff813d5e52)
Location: include/linux/netdevice.h:3369
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_sid
```
```
In security/lsm_audit.c (ffffffff813f00da)
Location: include/linux/netdevice.h:3369
Inline: True
Inline callers:
  - security/lsm_audit.c:common_lsm_audit
```
```
In drivers/net/tun.c (ffffffff816fe081)
Location: include/linux/netdevice.h:3369
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
In net/core/dev.c (ffffffff81844204)
Location: include/linux/netdevice.h:3369
Inline: True
Inline callers:
  - net/core/dev.c:rollback_registered_many
```
```
In net/core/ethtool.c (ffffffff81850e71)
Location: include/linux/netdevice.h:3369
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
```
```
In net/core/dst.c (ffffffff81853c9b)
Location: include/linux/netdevice.h:3369
Inline: True
Inline callers:
  - net/core/dst.c:dst_dev_put
  - net/core/dst.c:dst_destroy
```
```
In net/core/neighbour.c (ffffffff818559a9)
Location: include/linux/netdevice.h:3369
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:pneigh_delete
  - net/core/neighbour.c:pneigh_lookup
  - net/core/neighbour.c:neigh_ifdown
  - net/core/neighbour.c:pneigh_queue_purge
```
```
In net/core/utils.c (ffffffff8186231d)
Location: include/linux/netdevice.h:3369
Inline: True
Inline callers:
  - net/core/utils.c:inet6_pton
```
```
In net/core/link_watch.c (ffffffff8186259f)
Location: include/linux/netdevice.h:3369
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_do_dev
```
```
In net/core/net-sysfs.c (ffffffff8186b36f)
Location: include/linux/netdevice.h:3369
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_queue_release
  - net/core/net-sysfs.c:rx_queue_release
```
```
In net/core/netpoll.c (ffffffff8186e03a)
Location: include/linux/netdevice.h:3369
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_cleanup
  - net/core/netpoll.c:netpoll_setup
```
```
In net/core/netprio_cgroup.c (ffffffff81875b2a)
Location: include/linux/netdevice.h:3369
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:write_priomap
```
```
In net/sched/sch_generic.c (ffffffff8187b446)
Location: include/linux/netdevice.h:3369
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/sched/sch_api.c (ffffffff8187ce84)
Location: include/linux/netdevice.h:3369
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:qdisc_create
```
```
In net/netlink/af_netlink.c (ffffffff8188613f)
Location: include/linux/netdevice.h:3369
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_deliver_tap
```
```
In net/netfilter/nf_queue.c (ffffffff8188d798)
Location: include/linux/netdevice.h:3369
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
```
```
In net/ipv4/route.c (ffffffff81890a8e)
Location: include/linux/netdevice.h:3369
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_flush_dev
```
```
In net/ipv4/ip_sockglue.c (ffffffff8189c99c)
Location: include/linux/netdevice.h:3369
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff818ced31)
Location: include/linux/netdevice.h:3369
Inline: True
Inline callers:
  - net/ipv4/devinet.c:in_dev_finish_destroy
```
```
In net/ipv4/fib_semantics.c (ffffffff818dc28f)
Location: include/linux/netdevice.h:3369
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
```
In net/ipv4/ipmr.c (ffffffff818e9637)
Location: include/linux/netdevice.h:3369
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
```
```
In net/xfrm/xfrm_policy.c (ffffffff818f3bbe)
Location: include/linux/netdevice.h:3369
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_ifdown
```
```
In net/xfrm/xfrm_state.c (ffffffff818fa6f6)
Location: include/linux/netdevice.h:3369
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_gc_task
```
```
In net/xfrm/xfrm_input.c (ffffffff818ff36c)
Location: include/linux/netdevice.h:3369
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_device.c (ffffffff819014e0)
Location: include/linux/netdevice.h:3369
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff819155de)
Location: include/linux/netdevice.h:3369
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/route.c (ffffffff8192063b)
Location: include/linux/netdevice.h:3369
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_ifdown
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:rt6_probe_deferred
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81926620)
Location: include/linux/netdevice.h:3369
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81946e3f)
Location: include/linux/netdevice.h:3369
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:mif6_delete
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81948175)
Location: include/linux/netdevice.h:3369
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
```
```
In net/ipv6/addrconf_core.c (ffffffff81950d91)
Location: include/linux/netdevice.h:3369
Inline: True
Inline callers:
  - net/ipv6/addrconf_core.c:in6_dev_finish_destroy
```
```
In net/packet/af_packet.c (ffffffff81954c84)
Location: include/linux/netdevice.h:3369
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81962c02)
Location: include/linux/netdevice.h:3369
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
```
In net/switchdev/switchdev.c (ffffffff8196adc9)
Location: include/linux/netdevice.h:3369
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_deferred_process
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
In kernel/bpf/devmap.c (ffffffff811c9ae1)
Location: include/linux/netdevice.h:3475
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:__dev_map_entry_free
  - kernel/bpf/devmap.c:dev_map_free
```
```
In kernel/bpf/offload.c (ffffffff811cb9ef)
Location: include/linux/netdevice.h:3475
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_prog_offload_init
  - kernel/bpf/offload.c:bpf_prog_offload_init
```
```
In security/selinux/netif.c (ffffffff81406451)
Location: include/linux/netdevice.h:3475
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_sid
```
```
In security/lsm_audit.c (ffffffff81420c60)
Location: include/linux/netdevice.h:3475
Inline: True
Inline callers:
  - security/lsm_audit.c:dump_common_audit_data
```
```
In drivers/net/tun.c (ffffffff8173c28a)
Location: include/linux/netdevice.h:3475
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
In net/core/dev.c (ffffffff81898139)
Location: include/linux/netdevice.h:3475
Inline: True
Inline callers:
  - net/core/dev.c:rollback_registered_many
```
```
In net/core/ethtool.c (ffffffff8189c6a1)
Location: include/linux/netdevice.h:3475
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
```
```
In net/core/dst.c (ffffffff8189f41e)
Location: include/linux/netdevice.h:3475
Inline: True
Inline callers:
  - net/core/dst.c:dst_dev_put
  - net/core/dst.c:dst_destroy
```
```
In net/core/neighbour.c (ffffffff818a0f47)
Location: include/linux/netdevice.h:3475
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:pneigh_delete
  - net/core/neighbour.c:pneigh_lookup
  - net/core/neighbour.c:neigh_ifdown
  - net/core/neighbour.c:pneigh_queue_purge
```
```
In net/core/utils.c (ffffffff818adf87)
Location: include/linux/netdevice.h:3475
Inline: True
Inline callers:
  - net/core/utils.c:inet6_pton
```
```
In net/core/link_watch.c (ffffffff818ae24f)
Location: include/linux/netdevice.h:3475
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_do_dev
```
```
In net/core/net-sysfs.c (ffffffff818bbae0)
Location: include/linux/netdevice.h:3475
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_queue_release
  - net/core/net-sysfs.c:rx_queue_release
```
```
In net/core/netpoll.c (ffffffff818bf00a)
Location: include/linux/netdevice.h:3475
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_cleanup
  - net/core/netpoll.c:netpoll_setup
```
```
In net/core/netprio_cgroup.c (ffffffff818c71c0)
Location: include/linux/netdevice.h:3475
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:write_priomap
```
```
In net/sched/sch_generic.c (ffffffff818cd8f6)
Location: include/linux/netdevice.h:3475
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/sched/sch_api.c (ffffffff818cf714)
Location: include/linux/netdevice.h:3475
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:qdisc_create
```
```
In net/netlink/af_netlink.c (ffffffff818d99f3)
Location: include/linux/netdevice.h:3475
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_deliver_tap
```
```
In net/netfilter/nf_queue.c (ffffffff818e134d)
Location: include/linux/netdevice.h:3475
Inline: True
```
```
In net/ipv4/route.c (ffffffff818e469e)
Location: include/linux/netdevice.h:3475
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_flush_dev
```
```
In net/ipv4/ip_sockglue.c (ffffffff818f0e82)
Location: include/linux/netdevice.h:3475
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff81925181)
Location: include/linux/netdevice.h:3475
Inline: True
Inline callers:
  - net/ipv4/devinet.c:in_dev_finish_destroy
```
```
In net/ipv4/fib_semantics.c (ffffffff81932eb3)
Location: include/linux/netdevice.h:3475
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
```
In net/ipv4/ipmr.c (ffffffff8193fb6a)
Location: include/linux/netdevice.h:3475
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
```
```
In net/xfrm/xfrm_policy.c (ffffffff8194a4ca)
Location: include/linux/netdevice.h:3475
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_ifdown
```
```
In net/xfrm/xfrm_state.c (ffffffff819511fb)
Location: include/linux/netdevice.h:3475
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_gc_task
```
```
In net/xfrm/xfrm_input.c (ffffffff81955eb5)
Location: include/linux/netdevice.h:3475
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_device.c (ffffffff81958036)
Location: include/linux/netdevice.h:3475
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
```
```
In net/ipv6/addrconf.c (ffffffff8196cbb8)
Location: include/linux/netdevice.h:3475
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/route.c (ffffffff81978989)
Location: include/linux/netdevice.h:3475
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:rt6_probe_deferred
```
```
In net/ipv6/ip6_fib.c (ffffffff81979b4a)
Location: include/linux/netdevice.h:3475
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_info_destroy_rcu
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff8197ea02)
Location: include/linux/netdevice.h:3475
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff8199ffba)
Location: include/linux/netdevice.h:3475
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:mif6_delete
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_policy.c (ffffffff819a1208)
Location: include/linux/netdevice.h:3475
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
```
```
In net/ipv6/addrconf_core.c (ffffffff819aa311)
Location: include/linux/netdevice.h:3475
Inline: True
Inline callers:
  - net/ipv6/addrconf_core.c:in6_dev_finish_destroy
```
```
In net/packet/af_packet.c (ffffffff819b0fa5)
Location: include/linux/netdevice.h:3475
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff819bc4e7)
Location: include/linux/netdevice.h:3475
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
```
In net/switchdev/switchdev.c (ffffffff819c48b3)
Location: include/linux/netdevice.h:3475
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_deferred_process
```
```
In net/ncsi/ncsi-netlink.c (ffffffff819ca854)
Location: include/linux/netdevice.h:3475
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ndp_from_ifindex
```
```
In net/xdp/xsk.c (ffffffff819cbd08)
Location: include/linux/netdevice.h:3475
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk.c:xsk_release
```
```
In net/xdp/xdp_umem.c (ffffffff819ccbd6)
Location: include/linux/netdevice.h:3475
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
  - net/xdp/xdp_umem.c:xdp_umem_assign_dev
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
In kernel/bpf/devmap.c (ffffffff811dd3e1)
Location: include/linux/netdevice.h:3701
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:__dev_map_entry_free
  - kernel/bpf/devmap.c:dev_map_free
```
```
In kernel/bpf/offload.c (ffffffff811dfb21)
Location: include/linux/netdevice.h:3701
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_prog_offload_init
  - kernel/bpf/offload.c:bpf_prog_offload_init
```
```
In security/selinux/netif.c (ffffffff81421fa3)
Location: include/linux/netdevice.h:3701
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_sid
```
```
In security/lsm_audit.c (ffffffff8143d341)
Location: include/linux/netdevice.h:3701
Inline: True
Inline callers:
  - security/lsm_audit.c:dump_common_audit_data
```
```
In drivers/net/tun.c (ffffffff8175fbca)
Location: include/linux/netdevice.h:3701
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
In net/core/dev.c (ffffffff818ba566)
Location: include/linux/netdevice.h:3701
Inline: True
Inline callers:
  - net/core/dev.c:rollback_registered_many
```
```
In net/core/ethtool.c (ffffffff818bfc95)
Location: include/linux/netdevice.h:3701
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
```
```
In net/core/dst.c (ffffffff818c1dde)
Location: include/linux/netdevice.h:3701
Inline: True
Inline callers:
  - net/core/dst.c:dst_dev_put
  - net/core/dst.c:dst_destroy
```
```
In net/core/neighbour.c (ffffffff818c3e07)
Location: include/linux/netdevice.h:3701
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:pneigh_delete
  - net/core/neighbour.c:pneigh_lookup
  - net/core/neighbour.c:__neigh_ifdown
  - net/core/neighbour.c:pneigh_queue_purge
```
```
In net/core/utils.c (ffffffff818d21f7)
Location: include/linux/netdevice.h:3701
Inline: True
Inline callers:
  - net/core/utils.c:inet6_pton
```
```
In net/core/link_watch.c (ffffffff818d24c7)
Location: include/linux/netdevice.h:3701
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_do_dev
```
```
In net/core/net-sysfs.c (ffffffff818e2b20)
Location: include/linux/netdevice.h:3701
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_queue_release
  - net/core/net-sysfs.c:rx_queue_release
```
```
In net/core/netpoll.c (ffffffff818e7dfa)
Location: include/linux/netdevice.h:3701
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_cleanup
  - net/core/netpoll.c:netpoll_setup
```
```
In net/core/netprio_cgroup.c (ffffffff818f0330)
Location: include/linux/netdevice.h:3701
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:write_priomap
```
```
In net/sched/sch_generic.c (ffffffff818f8b36)
Location: include/linux/netdevice.h:3701
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/sched/sch_api.c (ffffffff818fa604)
Location: include/linux/netdevice.h:3701
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:qdisc_create
```
```
In net/netlink/af_netlink.c (ffffffff81906446)
Location: include/linux/netdevice.h:3701
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_deliver_tap
```
```
In net/netfilter/nf_queue.c (ffffffff8190dedd)
Location: include/linux/netdevice.h:3701
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
```
```
In net/ipv4/route.c (ffffffff819115ce)
Location: include/linux/netdevice.h:3701
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_flush_dev
```
```
In net/ipv4/ip_sockglue.c (ffffffff8191e9bb)
Location: include/linux/netdevice.h:3701
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff81953f91)
Location: include/linux/netdevice.h:3701
Inline: True
Inline callers:
  - net/ipv4/devinet.c:in_dev_finish_destroy
```
```
In net/ipv4/fib_semantics.c (ffffffff81962743)
Location: include/linux/netdevice.h:3701
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
```
In net/ipv4/ipmr.c (ffffffff8196fbac)
Location: include/linux/netdevice.h:3701
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197c48a)
Location: include/linux/netdevice.h:3701
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_ifdown
```
```
In net/xfrm/xfrm_state.c (ffffffff819846dc)
Location: include/linux/netdevice.h:3701
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
```
```
In net/xfrm/xfrm_input.c (ffffffff8198aaa5)
Location: include/linux/netdevice.h:3701
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_device.c (ffffffff8198ca4b)
Location: include/linux/netdevice.h:3701
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
```
```
In net/ipv6/addrconf.c (ffffffff819a26aa)
Location: include/linux/netdevice.h:3701
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/route.c (ffffffff819ae570)
Location: include/linux/netdevice.h:3701
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:rt6_probe_deferred
```
```
In net/ipv6/ip6_fib.c (ffffffff819af734)
Location: include/linux/netdevice.h:3701
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_info_destroy_rcu
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff819b4f25)
Location: include/linux/netdevice.h:3701
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff819d6b55)
Location: include/linux/netdevice.h:3701
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:mif6_delete
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_policy.c (ffffffff819d7f2d)
Location: include/linux/netdevice.h:3701
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
```
```
In net/ipv6/addrconf_core.c (ffffffff819e0e21)
Location: include/linux/netdevice.h:3701
Inline: True
Inline callers:
  - net/ipv6/addrconf_core.c:in6_dev_finish_destroy
```
```
In net/packet/af_packet.c (ffffffff819e6395)
Location: include/linux/netdevice.h:3701
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:packet_sendmsg
  - net/packet/af_packet.c:tpacket_snd
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff819f374e)
Location: include/linux/netdevice.h:3701
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
```
In net/switchdev/switchdev.c (ffffffff819fbd53)
Location: include/linux/netdevice.h:3701
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_deferred_process
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81a02eb4)
Location: include/linux/netdevice.h:3701
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ndp_from_ifindex
```
```
In net/xdp/xsk.c (ffffffff81a04e97)
Location: include/linux/netdevice.h:3701
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk.c:xsk_release
```
```
In net/xdp/xdp_umem.c (ffffffff81a05c80)
Location: include/linux/netdevice.h:3701
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
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
In kernel/bpf/devmap.c (ffffffff811f2bcb)
Location: include/linux/netdevice.h:3722
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:__dev_map_entry_free
  - kernel/bpf/devmap.c:dev_map_free
```
```
In kernel/bpf/offload.c (ffffffff811f556e)
Location: include/linux/netdevice.h:3722
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_prog_offload_init
  - kernel/bpf/offload.c:bpf_prog_offload_init
```
```
In security/selinux/netif.c (ffffffff8144fba3)
Location: include/linux/netdevice.h:3722
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_sid
```
```
In security/lsm_audit.c (ffffffff8146b092)
Location: include/linux/netdevice.h:3722
Inline: True
Inline callers:
  - security/lsm_audit.c:dump_common_audit_data
```
```
In drivers/net/tun.c (ffffffff8179c909)
Location: include/linux/netdevice.h:3722
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
In net/core/dev.c (ffffffff818fc9ba)
Location: include/linux/netdevice.h:3722
Inline: True
Inline callers:
  - net/core/dev.c:rollback_registered_many
```
```
In net/core/ethtool.c (ffffffff8190b717)
Location: include/linux/netdevice.h:3722
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
```
```
In net/core/dst.c (ffffffff8190e521)
Location: include/linux/netdevice.h:3722
Inline: True
Inline callers:
  - net/core/dst.c:dst_dev_put
  - net/core/dst.c:dst_destroy
```
```
In net/core/neighbour.c (ffffffff8190ff69)
Location: include/linux/netdevice.h:3722
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:pneigh_delete
  - net/core/neighbour.c:pneigh_lookup
  - net/core/neighbour.c:__neigh_ifdown
  - net/core/neighbour.c:pneigh_queue_purge
```
```
In net/core/utils.c (ffffffff8191f484)
Location: include/linux/netdevice.h:3722
Inline: True
Inline callers:
  - net/core/utils.c:inet6_pton
```
```
In net/core/link_watch.c (ffffffff8191f767)
Location: include/linux/netdevice.h:3722
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_do_dev
```
```
In net/core/net-sysfs.c (ffffffff81932130)
Location: include/linux/netdevice.h:3722
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_queue_release
  - net/core/net-sysfs.c:rx_queue_release
```
```
In net/core/netpoll.c (ffffffff8193775a)
Location: include/linux/netdevice.h:3722
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_cleanup
  - net/core/netpoll.c:netpoll_setup
```
```
In net/core/netprio_cgroup.c (ffffffff81941ca0)
Location: include/linux/netdevice.h:3722
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:write_priomap
```
```
In net/core/devlink.c (ffffffff81951d92)
Location: include/linux/netdevice.h:3722
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_flash_update
  - net/core/devlink.c:devlink_compat_running_version
```
```
In net/sched/sch_generic.c (ffffffff81958306)
Location: include/linux/netdevice.h:3722
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/sched/sch_api.c (ffffffff81959eb6)
Location: include/linux/netdevice.h:3722
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:qdisc_create
```
```
In net/netlink/af_netlink.c (ffffffff8196760f)
Location: include/linux/netdevice.h:3722
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_deliver_tap
```
```
In net/netfilter/nf_queue.c (ffffffff8196f94d)
Location: include/linux/netdevice.h:3722
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
```
```
In net/ipv4/route.c (ffffffff81973c14)
Location: include/linux/netdevice.h:3722
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_flush_dev
```
```
In net/ipv4/ip_sockglue.c (ffffffff81981136)
Location: include/linux/netdevice.h:3722
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff819b89fa)
Location: include/linux/netdevice.h:3722
Inline: True
Inline callers:
  - net/ipv4/devinet.c:in_dev_finish_destroy
```
```
In net/ipv4/fib_semantics.c (ffffffff819c7818)
Location: include/linux/netdevice.h:3722
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nh_common_release
```
```
In net/ipv4/ipmr.c (ffffffff819d92b0)
Location: include/linux/netdevice.h:3722
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
```
```
In net/xfrm/xfrm_policy.c (ffffffff819e57aa)
Location: include/linux/netdevice.h:3722
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_ifdown
```
```
In net/xfrm/xfrm_state.c (ffffffff819ee3bd)
Location: include/linux/netdevice.h:3722
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
```
```
In net/xfrm/xfrm_input.c (ffffffff819f5697)
Location: include/linux/netdevice.h:3722
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_device.c (ffffffff819f7fe0)
Location: include/linux/netdevice.h:3722
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
```
```
In net/ipv6/addrconf.c (ffffffff81a0ed23)
Location: include/linux/netdevice.h:3722
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/route.c (ffffffff81a1c3dc)
Location: include/linux/netdevice.h:3722
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:rt6_probe_deferred
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81a23cba)
Location: include/linux/netdevice.h:3722
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81a45c33)
Location: include/linux/netdevice.h:3722
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:mif6_delete
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81a46ef7)
Location: include/linux/netdevice.h:3722
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
```
```
In net/ipv6/addrconf_core.c (ffffffff81a4fb85)
Location: include/linux/netdevice.h:3722
Inline: True
Inline callers:
  - net/ipv6/addrconf_core.c:in6_dev_finish_destroy
```
```
In net/packet/af_packet.c (ffffffff81a55df8)
Location: include/linux/netdevice.h:3722
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
In net/netlabel/netlabel_unlabeled.c (ffffffff81a62a0e)
Location: include/linux/netdevice.h:3722
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
```
In net/switchdev/switchdev.c (ffffffff81a6b352)
Location: include/linux/netdevice.h:3722
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_deferred_process
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81a721f4)
Location: include/linux/netdevice.h:3722
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ndp_from_ifindex
```
```
In net/xdp/xsk.c (ffffffff81a74393)
Location: include/linux/netdevice.h:3722
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk.c:xsk_unbind_dev
```
```
In net/xdp/xdp_umem.c (ffffffff81a7593e)
Location: include/linux/netdevice.h:3722
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_clear_dev
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
In kernel/bpf/devmap.c (ffffffff811ff7bb)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:__dev_map_entry_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/devmap.c:dev_map_free
```
```
In kernel/bpf/offload.c (ffffffff8120256e)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_prog_offload_init
  - kernel/bpf/offload.c:bpf_prog_offload_init
```
```
In security/selinux/netif.c (ffffffff81469a13)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_sid
```
```
In security/lsm_audit.c (ffffffff81484e72)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - security/lsm_audit.c:dump_common_audit_data
```
```
In drivers/net/tun.c (ffffffff817c03b9)
Location: include/linux/netdevice.h:3738
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
In net/core/dev.c (ffffffff8192f037)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/core/dev.c:rollback_registered_many
```
```
In net/core/ethtool.c (ffffffff8193dd45)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
```
```
In net/core/dst.c (ffffffff81940b61)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/core/dst.c:dst_dev_put
  - net/core/dst.c:dst_destroy
```
```
In net/core/neighbour.c (ffffffff819425d9)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:pneigh_delete
  - net/core/neighbour.c:pneigh_lookup
  - net/core/neighbour.c:__neigh_ifdown
  - net/core/neighbour.c:pneigh_queue_purge
```
```
In net/core/utils.c (ffffffff819516c4)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/core/utils.c:inet6_pton
```
```
In net/core/link_watch.c (ffffffff819519a7)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_do_dev
```
```
In net/core/net-sysfs.c (ffffffff81964c70)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_queue_release
  - net/core/net-sysfs.c:rx_queue_release
```
```
In net/core/netpoll.c (ffffffff8196a61a)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_cleanup
  - net/core/netpoll.c:netpoll_setup
```
```
In net/core/drop_monitor.c (ffffffff819746be)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_metadata_free
```
```
In net/core/netprio_cgroup.c (ffffffff81976bb0)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:write_priomap
```
```
In net/core/lwt_bpf.c (ffffffff81977bfe)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_input
```
```
In net/core/devlink.c (ffffffff819887d2)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_flash_update
  - net/core/devlink.c:devlink_compat_running_version
```
```
In net/sched/sch_generic.c (ffffffff8198e7b6)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/sched/sch_api.c (ffffffff81990356)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:qdisc_create
```
```
In net/netlink/af_netlink.c (ffffffff8199e09f)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_deliver_tap
```
```
In net/netfilter/nf_queue.c (ffffffff819a642d)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
```
```
In net/ipv4/route.c (ffffffff819aa634)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_flush_dev
```
```
In net/ipv4/ip_sockglue.c (ffffffff819b6c4a)
Location: include/linux/netdevice.h:3738
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff819ef6f2)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/ipv4/devinet.c:in_dev_finish_destroy
```
```
In net/ipv4/fib_semantics.c (ffffffff819fe3c8)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nh_common_release
```
```
In net/ipv4/ipmr.c (ffffffff81a10020)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a1c7da)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_ifdown
```
```
In net/xfrm/xfrm_state.c (ffffffff81a25267)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
```
```
In net/xfrm/xfrm_input.c (ffffffff81a2c347)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_device.c (ffffffff81a2ec30)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
```
```
In net/ipv6/addrconf.c (ffffffff81a45a66)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/route.c (ffffffff81a5305c)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:rt6_probe_deferred
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81a5a68e)
Location: include/linux/netdevice.h:3738
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81a7c823)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:mif6_delete
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81a7daa7)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
```
```
In net/ipv6/addrconf_core.c (ffffffff81a86811)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/ipv6/addrconf_core.c:in6_dev_finish_destroy
```
```
In net/packet/af_packet.c (ffffffff81a8d2d8)
Location: include/linux/netdevice.h:3738
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
In net/netlabel/netlabel_unlabeled.c (ffffffff81a995ee)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
```
In net/switchdev/switchdev.c (ffffffff81aa1d42)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_deferred_process
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81aa89b4)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ndp_from_ifindex
```
```
In net/xdp/xsk.c (ffffffff81aab523)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk.c:xsk_unbind_dev
```
```
In net/xdp/xdp_umem.c (ffffffff81aac7d1)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_clear_dev
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
In kernel/bpf/devmap.c (ffffffff81226796)
Location: include/linux/netdevice.h:3851
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:__dev_map_alloc_node
  - kernel/bpf/devmap.c:__dev_map_entry_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/devmap.c:dev_map_free
```
```
In kernel/bpf/offload.c (ffffffff81229b12)
Location: include/linux/netdevice.h:3851
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_prog_offload_init
  - kernel/bpf/offload.c:bpf_prog_offload_init
```
```
In security/selinux/netif.c (ffffffff814bdb95)
Location: include/linux/netdevice.h:3851
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_sid_slow
```
```
In security/lsm_audit.c (ffffffff814db12c)
Location: include/linux/netdevice.h:3851
Inline: True
Inline callers:
  - security/lsm_audit.c:dump_common_audit_data
```
```
In drivers/net/tun.c (ffffffff81889d9e)
Location: include/linux/netdevice.h:3851
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_show_fdinfo
  - drivers/net/tun.c:tun_peek_len
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_chr_read_iter
  - drivers/net/tun.c:tun_chr_write_iter
  - drivers/net/tun.c:tun_chr_poll
```
```
In net/core/dev.c (ffffffff81a0d9ae)
Location: include/linux/netdevice.h:3851
Inline: True
Inline callers:
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:__netdev_adjacent_dev_remove
  - net/core/dev.c:__netdev_adjacent_dev_insert
```
```
In net/core/dst.c (ffffffff81a106f9)
Location: include/linux/netdevice.h:3851
Inline: True
Inline callers:
  - net/core/dst.c:dst_dev_put
  - net/core/dst.c:dst_destroy
```
```
In net/core/neighbour.c (ffffffff81a1585f)
Location: include/linux/netdevice.h:3851
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_clear
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:pneigh_delete
  - net/core/neighbour.c:pneigh_lookup
```
```
In net/core/utils.c (ffffffff81a2252d)
Location: include/linux/netdevice.h:3851
Inline: True
Inline callers:
  - net/core/utils.c:inet6_pton
```
```
In net/core/link_watch.c (ffffffff81a22a00)
Location: include/linux/netdevice.h:3851
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_do_dev
```
```
In net/core/filter.c (ffffffff81a2a1e5)
Location: include/linux/netdevice.h:3851
Inline: True
Inline callers:
  - net/core/filter.c:_bpf_setsockopt
```
```
In net/core/net-sysfs.c (ffffffff81a37815)
Location: include/linux/netdevice.h:3851
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_queue_release
  - net/core/net-sysfs.c:rx_queue_release
```
```
In net/core/netpoll.c (ffffffff81a3e0a0)
Location: include/linux/netdevice.h:3851
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_cleanup
  - net/core/netpoll.c:netpoll_setup
```
```
In net/core/drop_monitor.c (ffffffff81a49f65)
Location: include/linux/netdevice.h:3851
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_monitor_stop
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
  - net/core/drop_monitor.c:net_dm_hw_packet_report
```
```
In net/core/netprio_cgroup.c (ffffffff81a4b8bb)
Location: include/linux/netdevice.h:3851
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:write_priomap
```
```
In net/core/lwt_bpf.c (ffffffff81a4d366)
Location: include/linux/netdevice.h:3851
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_input
```
```
In net/core/devlink.c (ffffffff81a604ce)
Location: include/linux/netdevice.h:3851
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_flash_update
  - net/core/devlink.c:devlink_compat_running_version
```
```
In net/sched/sch_generic.c (ffffffff81a66563)
Location: include/linux/netdevice.h:3851
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/sched/sch_api.c (ffffffff81a67e85)
Location: include/linux/netdevice.h:3851
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:qdisc_create
```
```
In net/netlink/af_netlink.c (ffffffff81a76e2d)
Location: include/linux/netdevice.h:3851
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_deliver_tap_skb
```
```
In net/ethtool/ioctl.c (ffffffff81a81623)
Location: include/linux/netdevice.h:3851
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_phys_id
```
```
In net/ethtool/netlink.c (ffffffff81a8618e)
Location: include/linux/netdevice.h:3851
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_start
  - net/ethtool/netlink.c:ethnl_default_dumpit
  - net/ethtool/netlink.c:ethnl_default_doit
  - net/ethtool/netlink.c:ethnl_default_doit
  - net/ethtool/netlink.c:ethnl_parse_header_dev_get
  - net/ethtool/netlink.c:ethnl_parse_header_dev_get
```
```
In net/ethtool/linkinfo.c (ffffffff81a88928)
Location: include/linux/netdevice.h:3851
Inline: True
Inline callers:
  - net/ethtool/linkinfo.c:ethnl_set_linkinfo
```
```
In net/ethtool/linkmodes.c (ffffffff81a890fb)
Location: include/linux/netdevice.h:3851
Inline: True
Inline callers:
  - net/ethtool/linkmodes.c:ethnl_set_linkmodes
```
```
In net/ethtool/debug.c (ffffffff81a89671)
Location: include/linux/netdevice.h:3851
Inline: True
Inline callers:
  - net/ethtool/debug.c:ethnl_set_debug
```
```
In net/ethtool/wol.c (ffffffff81a89a52)
Location: include/linux/netdevice.h:3851
Inline: True
Inline callers:
  - net/ethtool/wol.c:ethnl_set_wol
```
```
In net/ethtool/features.c (ffffffff81a8a1a3)
Location: include/linux/netdevice.h:3851
Inline: True
Inline callers:
  - net/ethtool/features.c:ethnl_set_features
```
```
In net/ethtool/privflags.c (ffffffff81a8a71a)
Location: include/linux/netdevice.h:3851
Inline: True
Inline callers:
  - net/ethtool/privflags.c:ethnl_set_privflags
```
```
In net/ethtool/rings.c (ffffffff81a8aba0)
Location: include/linux/netdevice.h:3851
Inline: True
Inline callers:
  - net/ethtool/rings.c:ethnl_set_rings
```
```
In net/ethtool/channels.c (ffffffff81a8b108)
Location: include/linux/netdevice.h:3851
Inline: True
Inline callers:
  - net/ethtool/channels.c:ethnl_set_channels
```
```
In net/ethtool/coalesce.c (ffffffff81a8bb02)
Location: include/linux/netdevice.h:3851
Inline: True
Inline callers:
  - net/ethtool/coalesce.c:ethnl_set_coalesce
```
```
In net/ethtool/pause.c (ffffffff81a8c18f)
Location: include/linux/netdevice.h:3851
Inline: True
Inline callers:
  - net/ethtool/pause.c:ethnl_set_pause
```
```
In net/ethtool/eee.c (ffffffff81a8c69e)
Location: include/linux/netdevice.h:3851
Inline: True
Inline callers:
  - net/ethtool/eee.c:ethnl_set_eee
```
```
In net/ethtool/cabletest.c (ffffffff81a8d844)
Location: include/linux/netdevice.h:3851
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_act_cable_test_tdr
  - net/ethtool/cabletest.c:ethnl_act_cable_test
```
```
In net/netfilter/nf_queue.c (ffffffff81a8f636)
Location: include/linux/netdevice.h:3851
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
```
```
In net/ipv4/route.c (ffffffff81a9496d)
Location: include/linux/netdevice.h:3851
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_flush_dev
```
```
In net/ipv4/ip_sockglue.c (ffffffff81aa149a)
Location: include/linux/netdevice.h:3851
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff81add64b)
Location: include/linux/netdevice.h:3851
Inline: True
Inline callers:
  - net/ipv4/devinet.c:in_dev_finish_destroy
```
```
In net/ipv4/fib_semantics.c (ffffffff81aed191)
Location: include/linux/netdevice.h:3851
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nh_common_release
```
```
In net/ipv4/ipmr.c (ffffffff81b01107)
Location: include/linux/netdevice.h:3851
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
  - net/ipv4/ipmr.c:ipmr_new_tunnel
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0db93)
Location: include/linux/netdevice.h:3851
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_ifdown
```
```
In net/xfrm/xfrm_state.c (ffffffff81b16e90)
Location: include/linux/netdevice.h:3851
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
```
```
In net/xfrm/xfrm_input.c (ffffffff81b1e7b6)
Location: include/linux/netdevice.h:3851
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_device.c (ffffffff81b21718)
Location: include/linux/netdevice.h:3851
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
```
```
In net/ipv6/addrconf.c (ffffffff81b3c825)
Location: include/linux/netdevice.h:3851
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:ipv6_add_dev
```
```
In net/ipv6/route.c (ffffffff81b49028)
Location: include/linux/netdevice.h:3851
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:rt6_probe_deferred
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81b52c19)
Location: include/linux/netdevice.h:3851
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff81b5ebaa)
Location: include/linux/netdevice.h:3851
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ip6mr.c (ffffffff81b73ec4)
Location: include/linux/netdevice.h:3851
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mif6_add
  - net/ipv6/ip6mr.c:mif6_add
  - net/ipv6/ip6mr.c:mif6_delete
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81b78315)
Location: include/linux/netdevice.h:3851
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
```
```
In net/ipv6/addrconf_core.c (ffffffff81b81b9c)
Location: include/linux/netdevice.h:3851
Inline: True
Inline callers:
  - net/ipv6/addrconf_core.c:in6_dev_finish_destroy
```
```
In net/packet/af_packet.c (ffffffff81b898ea)
Location: include/linux/netdevice.h:3851
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
In net/netlabel/netlabel_unlabeled.c (ffffffff81b93d9b)
Location: include/linux/netdevice.h:3851
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove_addr6
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove_addr4
```
```
In net/switchdev/switchdev.c (ffffffff81b9d706)
Location: include/linux/netdevice.h:3851
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_deferred_process
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81ba5601)
Location: include/linux/netdevice.h:3851
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
In net/xdp/xsk.c (ffffffff81ba65e9)
Location: include/linux/netdevice.h:3851
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_notifier
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk.c:xsk_release
```
```
In net/xdp/xdp_umem.c (ffffffff81ba8a66)
Location: include/linux/netdevice.h:3851
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_clear_dev
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
In kernel/bpf/devmap.c (ffffffff8122d38c)
Location: include/linux/netdevice.h:4019
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:__dev_map_alloc_node
  - kernel/bpf/devmap.c:__dev_map_entry_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/devmap.c:dev_map_free
```
```
In kernel/bpf/offload.c (ffffffff812316a2)
Location: include/linux/netdevice.h:4019
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_prog_offload_init
  - kernel/bpf/offload.c:bpf_prog_offload_init
```
```
In security/selinux/netif.c (ffffffff814db5f5)
Location: include/linux/netdevice.h:4019
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_sid_slow
```
```
In security/lsm_audit.c (ffffffff814f85c0)
Location: include/linux/netdevice.h:4019
Inline: True
Inline callers:
  - security/lsm_audit.c:dump_common_audit_data
```
```
In drivers/net/tun.c (ffffffff81899943)
Location: include/linux/netdevice.h:4019
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_show_fdinfo
  - drivers/net/tun.c:tun_peek_len
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_chr_read_iter
  - drivers/net/tun.c:tun_chr_write_iter
  - drivers/net/tun.c:tun_chr_poll
```
```
In net/core/dev.c (ffffffff81a05bd7)
Location: include/linux/netdevice.h:4019
Inline: True
Inline callers:
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:bpf_xdp_link_attach
  - net/core/dev.c:bpf_xdp_link_attach
  - net/core/dev.c:__netdev_adjacent_dev_remove
  - net/core/dev.c:__netdev_adjacent_dev_insert
```
```
In net/core/dst.c (ffffffff81a10ac9)
Location: include/linux/netdevice.h:4019
Inline: True
Inline callers:
  - net/core/dst.c:dst_dev_put
  - net/core/dst.c:dst_destroy
```
```
In net/core/neighbour.c (ffffffff81a15b4f)
Location: include/linux/netdevice.h:4019
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_clear
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:pneigh_delete
  - net/core/neighbour.c:pneigh_lookup
```
```
In net/core/utils.c (ffffffff81a228ad)
Location: include/linux/netdevice.h:4019
Inline: True
Inline callers:
  - net/core/utils.c:inet6_pton
```
```
In net/core/link_watch.c (ffffffff81a22d60)
Location: include/linux/netdevice.h:4019
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_do_dev
```
```
In net/core/filter.c (ffffffff81a2abce)
Location: include/linux/netdevice.h:4019
Inline: True
Inline callers:
  - net/core/filter.c:_bpf_setsockopt
```
```
In net/core/net-sysfs.c (ffffffff81a39c25)
Location: include/linux/netdevice.h:4019
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_queue_release
  - net/core/net-sysfs.c:rx_queue_release
```
```
In net/core/netpoll.c (ffffffff81a40e20)
Location: include/linux/netdevice.h:4019
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_cleanup
  - net/core/netpoll.c:netpoll_setup
```
```
In net/core/drop_monitor.c (ffffffff81a4fa81)
Location: include/linux/netdevice.h:4019
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_monitor_stop
  - net/core/drop_monitor.c:net_dm_hw_monitor_start
  - net/core/drop_monitor.c:net_dm_hw_trap_packet_probe
  - net/core/drop_monitor.c:net_dm_hw_packet_report
```
```
In net/core/netprio_cgroup.c (ffffffff81a5150b)
Location: include/linux/netdevice.h:4019
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:write_priomap
```
```
In net/core/lwt_bpf.c (ffffffff81a53026)
Location: include/linux/netdevice.h:4019
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_input
```
```
In net/core/devlink.c (ffffffff81a68d8e)
Location: include/linux/netdevice.h:4019
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_flash_update
  - net/core/devlink.c:devlink_compat_running_version
```
```
In net/sched/sch_generic.c (ffffffff81a6e643)
Location: include/linux/netdevice.h:4019
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/sched/sch_api.c (ffffffff81a7058b)
Location: include/linux/netdevice.h:4019
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:qdisc_create
```
```
In net/netlink/af_netlink.c (ffffffff81a7fbad)
Location: include/linux/netdevice.h:4019
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_deliver_tap_skb
```
```
In net/bpf/test_run.c (ffffffff81a88632)
Location: include/linux/netdevice.h:4019
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ethtool/ioctl.c (ffffffff81a8b21b)
Location: include/linux/netdevice.h:4019
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_phys_id
```
```
In net/ethtool/netlink.c (ffffffff81a8fa64)
Location: include/linux/netdevice.h:4019
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_start
  - net/ethtool/netlink.c:ethnl_default_dumpit
  - net/ethtool/netlink.c:ethnl_default_doit
  - net/ethtool/netlink.c:ethnl_default_doit
  - net/ethtool/netlink.c:ethnl_parse_header_dev_get
  - net/ethtool/netlink.c:ethnl_parse_header_dev_get
```
```
In net/ethtool/linkinfo.c (ffffffff81a92212)
Location: include/linux/netdevice.h:4019
Inline: True
Inline callers:
  - net/ethtool/linkinfo.c:ethnl_set_linkinfo
```
```
In net/ethtool/linkmodes.c (ffffffff81a929a9)
Location: include/linux/netdevice.h:4019
Inline: True
Inline callers:
  - net/ethtool/linkmodes.c:ethnl_set_linkmodes
```
```
In net/ethtool/debug.c (ffffffff81a92f94)
Location: include/linux/netdevice.h:4019
Inline: True
Inline callers:
  - net/ethtool/debug.c:ethnl_set_debug
```
```
In net/ethtool/wol.c (ffffffff81a93324)
Location: include/linux/netdevice.h:4019
Inline: True
Inline callers:
  - net/ethtool/wol.c:ethnl_set_wol
```
```
In net/ethtool/features.c (ffffffff81a93a31)
Location: include/linux/netdevice.h:4019
Inline: True
Inline callers:
  - net/ethtool/features.c:ethnl_set_features
```
```
In net/ethtool/privflags.c (ffffffff81a93f41)
Location: include/linux/netdevice.h:4019
Inline: True
Inline callers:
  - net/ethtool/privflags.c:ethnl_set_privflags
```
```
In net/ethtool/rings.c (ffffffff81a9435b)
Location: include/linux/netdevice.h:4019
Inline: True
Inline callers:
  - net/ethtool/rings.c:ethnl_set_rings
```
```
In net/ethtool/channels.c (ffffffff81a94832)
Location: include/linux/netdevice.h:4019
Inline: True
Inline callers:
  - net/ethtool/channels.c:ethnl_set_channels
```
```
In net/ethtool/coalesce.c (ffffffff81a9519d)
Location: include/linux/netdevice.h:4019
Inline: True
Inline callers:
  - net/ethtool/coalesce.c:ethnl_set_coalesce
```
```
In net/ethtool/pause.c (ffffffff81a9592f)
Location: include/linux/netdevice.h:4019
Inline: True
Inline callers:
  - net/ethtool/pause.c:ethnl_set_pause
```
```
In net/ethtool/eee.c (ffffffff81a95dd4)
Location: include/linux/netdevice.h:4019
Inline: True
Inline callers:
  - net/ethtool/eee.c:ethnl_set_eee
```
```
In net/ethtool/cabletest.c (ffffffff81a96f17)
Location: include/linux/netdevice.h:4019
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_act_cable_test_tdr
  - net/ethtool/cabletest.c:ethnl_act_cable_test
```
```
In net/ethtool/tunnels.c (ffffffff81a97685)
Location: include/linux/netdevice.h:4019
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_start
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
```
```
In net/netfilter/nf_queue.c (ffffffff81a99626)
Location: include/linux/netdevice.h:4019
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
```
```
In net/ipv4/route.c (ffffffff81a9e96d)
Location: include/linux/netdevice.h:4019
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_flush_dev
```
```
In net/ipv4/ip_sockglue.c (ffffffff81aac7cb)
Location: include/linux/netdevice.h:4019
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff81aea36b)
Location: include/linux/netdevice.h:4019
Inline: True
Inline callers:
  - net/ipv4/devinet.c:in_dev_finish_destroy
```
```
In net/ipv4/fib_semantics.c (ffffffff81afa0e1)
Location: include/linux/netdevice.h:4019
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nh_common_release
```
```
In net/ipv4/ipmr.c (ffffffff81b0f1e7)
Location: include/linux/netdevice.h:4019
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
  - net/ipv4/ipmr.c:ipmr_new_tunnel
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b1bda3)
Location: include/linux/netdevice.h:4019
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_ifdown
```
```
In net/xfrm/xfrm_state.c (ffffffff81b25100)
Location: include/linux/netdevice.h:4019
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
```
```
In net/xfrm/xfrm_input.c (ffffffff81b2d056)
Location: include/linux/netdevice.h:4019
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_device.c (ffffffff81b300e3)
Location: include/linux/netdevice.h:4019
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
```
```
In net/ipv6/addrconf.c (ffffffff81b4b535)
Location: include/linux/netdevice.h:4019
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:ipv6_add_dev
```
```
In net/ipv6/route.c (ffffffff81b57c48)
Location: include/linux/netdevice.h:4019
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:rt6_probe_deferred
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81b614c7)
Location: include/linux/netdevice.h:4019
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff81b6d321)
Location: include/linux/netdevice.h:4019
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ip6mr.c (ffffffff81b82c34)
Location: include/linux/netdevice.h:4019
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mif6_add
  - net/ipv6/ip6mr.c:mif6_add
  - net/ipv6/ip6mr.c:mif6_delete
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81b87276)
Location: include/linux/netdevice.h:4019
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
```
```
In net/ipv6/addrconf_core.c (ffffffff81b9129c)
Location: include/linux/netdevice.h:4019
Inline: True
Inline callers:
  - net/ipv6/addrconf_core.c:in6_dev_finish_destroy
```
```
In net/packet/af_packet.c (ffffffff81b993ff)
Location: include/linux/netdevice.h:4019
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
In net/netlabel/netlabel_unlabeled.c (ffffffff81ba3a02)
Location: include/linux/netdevice.h:4019
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove_addr6
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove_addr4
```
```
In net/switchdev/switchdev.c (ffffffff81bad016)
Location: include/linux/netdevice.h:4019
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_deferred_process
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81bb4ad7)
Location: include/linux/netdevice.h:4019
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
In net/xdp/xsk.c (ffffffff81bb6e50)
Location: include/linux/netdevice.h:4019
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_notifier
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk.c:xsk_release
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81bb97c4)
Location: include/linux/netdevice.h:4019
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_release_deferred
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
In kernel/bpf/devmap.c (ffffffff8123215a)
Location: include/linux/netdevice.h:4141
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:__dev_map_alloc_node
  - kernel/bpf/devmap.c:__dev_map_entry_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/devmap.c:dev_map_free
```
```
In kernel/bpf/offload.c (ffffffff81235822)
Location: include/linux/netdevice.h:4141
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_prog_offload_init
  - kernel/bpf/offload.c:bpf_prog_offload_init
```
```
In security/selinux/netif.c (ffffffff814e1f75)
Location: include/linux/netdevice.h:4141
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_sid_slow
```
```
In security/lsm_audit.c (ffffffff814ff32e)
Location: include/linux/netdevice.h:4141
Inline: True
Inline callers:
  - security/lsm_audit.c:dump_common_audit_data
```
```
In drivers/net/tun.c (ffffffff8187bdcb)
Location: include/linux/netdevice.h:4141
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
In net/core/dev.c (ffffffff819ec529)
Location: include/linux/netdevice.h:4141
Inline: True
Inline callers:
  - net/core/dev.c:unregister_netdevice_many
  - net/core/dev.c:bpf_xdp_link_attach
  - net/core/dev.c:bpf_xdp_link_attach
  - net/core/dev.c:__netdev_adjacent_dev_remove
  - net/core/dev.c:__netdev_adjacent_dev_insert
```
```
In net/core/dst.c (ffffffff819f7939)
Location: include/linux/netdevice.h:4141
Inline: True
Inline callers:
  - net/core/dst.c:dst_dev_put
  - net/core/dst.c:dst_destroy
```
```
In net/core/neighbour.c (ffffffff819fc6bf)
Location: include/linux/netdevice.h:4141
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_clear
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:pneigh_delete
  - net/core/neighbour.c:pneigh_lookup
```
```
In net/core/utils.c (ffffffff81a09bdc)
Location: include/linux/netdevice.h:4141
Inline: True
Inline callers:
  - net/core/utils.c:inet6_pton
```
```
In net/core/link_watch.c (ffffffff81a09fc8)
Location: include/linux/netdevice.h:4141
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_do_dev
```
```
In net/core/filter.c (ffffffff81a11f03)
Location: include/linux/netdevice.h:4141
Inline: True
Inline callers:
  - net/core/filter.c:_bpf_setsockopt
```
```
In net/core/net-sysfs.c (ffffffff81a20fe5)
Location: include/linux/netdevice.h:4141
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_queue_release
  - net/core/net-sysfs.c:rx_queue_release
```
```
In net/core/netpoll.c (ffffffff81a25ae0)
Location: include/linux/netdevice.h:4141
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_cleanup
  - net/core/netpoll.c:netpoll_setup
```
```
In net/core/drop_monitor.c (ffffffff81a34ca9)
Location: include/linux/netdevice.h:4141
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_hw_monitor_start
  - net/core/drop_monitor.c:net_dm_hw_trap_packet_probe
  - net/core/drop_monitor.c:net_dm_hw_packet_work
```
```
In net/core/netprio_cgroup.c (ffffffff81a36d7b)
Location: include/linux/netdevice.h:4141
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:write_priomap
```
```
In net/core/lwt_bpf.c (ffffffff81a38845)
Location: include/linux/netdevice.h:4141
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_input
```
```
In net/core/devlink.c (ffffffff81a4c14e)
Location: include/linux/netdevice.h:4141
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_flash_update
  - net/core/devlink.c:devlink_compat_running_version
```
```
In net/sched/sch_generic.c (ffffffff81a56ed3)
Location: include/linux/netdevice.h:4141
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/sched/sch_api.c (ffffffff81a58e8a)
Location: include/linux/netdevice.h:4141
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:qdisc_create
```
```
In net/netlink/af_netlink.c (ffffffff81a68b95)
Location: include/linux/netdevice.h:4141
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_deliver_tap
```
```
In net/bpf/test_run.c (ffffffff81a71892)
Location: include/linux/netdevice.h:4141
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ethtool/ioctl.c (ffffffff81a7454a)
Location: include/linux/netdevice.h:4141
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_phys_id
```
```
In net/ethtool/netlink.c (ffffffff81a79194)
Location: include/linux/netdevice.h:4141
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_start
  - net/ethtool/netlink.c:ethnl_default_dumpit
  - net/ethtool/netlink.c:ethnl_default_doit
  - net/ethtool/netlink.c:ethnl_default_doit
  - net/ethtool/netlink.c:ethnl_parse_header_dev_get
  - net/ethtool/netlink.c:ethnl_parse_header_dev_get
```
```
In net/ethtool/linkinfo.c (ffffffff81a7ba22)
Location: include/linux/netdevice.h:4141
Inline: True
Inline callers:
  - net/ethtool/linkinfo.c:ethnl_set_linkinfo
```
```
In net/ethtool/linkmodes.c (ffffffff81a7c3b0)
Location: include/linux/netdevice.h:4141
Inline: True
Inline callers:
  - net/ethtool/linkmodes.c:ethnl_set_linkmodes
```
```
In net/ethtool/debug.c (ffffffff81a7c9a4)
Location: include/linux/netdevice.h:4141
Inline: True
Inline callers:
  - net/ethtool/debug.c:ethnl_set_debug
```
```
In net/ethtool/wol.c (ffffffff81a7cd34)
Location: include/linux/netdevice.h:4141
Inline: True
Inline callers:
  - net/ethtool/wol.c:ethnl_set_wol
```
```
In net/ethtool/features.c (ffffffff81a7d426)
Location: include/linux/netdevice.h:4141
Inline: True
Inline callers:
  - net/ethtool/features.c:ethnl_set_features
```
```
In net/ethtool/privflags.c (ffffffff81a7d943)
Location: include/linux/netdevice.h:4141
Inline: True
Inline callers:
  - net/ethtool/privflags.c:ethnl_set_privflags
```
```
In net/ethtool/rings.c (ffffffff81a7dd6b)
Location: include/linux/netdevice.h:4141
Inline: True
Inline callers:
  - net/ethtool/rings.c:ethnl_set_rings
```
```
In net/ethtool/channels.c (ffffffff81a7e242)
Location: include/linux/netdevice.h:4141
Inline: True
Inline callers:
  - net/ethtool/channels.c:ethnl_set_channels
```
```
In net/ethtool/coalesce.c (ffffffff81a7ec20)
Location: include/linux/netdevice.h:4141
Inline: True
Inline callers:
  - net/ethtool/coalesce.c:ethnl_set_coalesce
```
```
In net/ethtool/pause.c (ffffffff81a7f3bf)
Location: include/linux/netdevice.h:4141
Inline: True
Inline callers:
  - net/ethtool/pause.c:ethnl_set_pause
```
```
In net/ethtool/eee.c (ffffffff81a7f864)
Location: include/linux/netdevice.h:4141
Inline: True
Inline callers:
  - net/ethtool/eee.c:ethnl_set_eee
```
```
In net/ethtool/cabletest.c (ffffffff81a8099f)
Location: include/linux/netdevice.h:4141
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_act_cable_test_tdr
  - net/ethtool/cabletest.c:ethnl_act_cable_test
```
```
In net/ethtool/tunnels.c (ffffffff81a810e5)
Location: include/linux/netdevice.h:4141
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_start
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
```
```
In net/ethtool/fec.c (ffffffff81a8192c)
Location: include/linux/netdevice.h:4141
Inline: True
Inline callers:
  - net/ethtool/fec.c:ethnl_set_fec
```
```
In net/netfilter/nf_queue.c (ffffffff81a84936)
Location: include/linux/netdevice.h:4141
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
```
```
In net/ipv4/route.c (ffffffff81a898cd)
Location: include/linux/netdevice.h:4141
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_flush_dev
```
```
In net/ipv4/ip_sockglue.c (ffffffff81a97a07)
Location: include/linux/netdevice.h:4141
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81ad5116)
Location: include/linux/netdevice.h:4141
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_echo
```
```
In net/ipv4/devinet.c (ffffffff81ad5abb)
Location: include/linux/netdevice.h:4141
Inline: True
Inline callers:
  - net/ipv4/devinet.c:in_dev_finish_destroy
```
```
In net/ipv4/fib_semantics.c (ffffffff81ae5821)
Location: include/linux/netdevice.h:4141
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nh_common_release
```
```
In net/ipv4/ipmr.c (ffffffff81afcee1)
Location: include/linux/netdevice.h:4141
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
  - net/ipv4/ipmr.c:ipmr_new_tunnel
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b09a93)
Location: include/linux/netdevice.h:4141
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_ifdown
```
```
In net/xfrm/xfrm_state.c (ffffffff81b12d20)
Location: include/linux/netdevice.h:4141
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
```
```
In net/xfrm/xfrm_input.c (ffffffff81b1ac99)
Location: include/linux/netdevice.h:4141
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_device.c (ffffffff81b1de1e)
Location: include/linux/netdevice.h:4141
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
```
```
In net/ipv6/addrconf.c (ffffffff81b39097)
Location: include/linux/netdevice.h:4141
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:ipv6_add_dev
```
```
In net/ipv6/route.c (ffffffff81b4725d)
Location: include/linux/netdevice.h:4141
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:rt6_probe_deferred
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81b4f79a)
Location: include/linux/netdevice.h:4141
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff81b5b65f)
Location: include/linux/netdevice.h:4141
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ip6mr.c (ffffffff81b718b0)
Location: include/linux/netdevice.h:4141
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mif6_add
  - net/ipv6/ip6mr.c:mif6_add
  - net/ipv6/ip6mr.c:mif6_delete
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81b75f42)
Location: include/linux/netdevice.h:4141
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
```
```
In net/ipv6/addrconf_core.c (ffffffff81b8049e)
Location: include/linux/netdevice.h:4141
Inline: True
Inline callers:
  - net/ipv6/addrconf_core.c:in6_dev_finish_destroy
```
```
In net/packet/af_packet.c (ffffffff81b8849f)
Location: include/linux/netdevice.h:4141
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
In net/netlabel/netlabel_unlabeled.c (ffffffff81b92b21)
Location: include/linux/netdevice.h:4141
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
```
In net/switchdev/switchdev.c (ffffffff81b9c2a6)
Location: include/linux/netdevice.h:4141
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_deferred_process
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81ba3ab3)
Location: include/linux/netdevice.h:4141
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
In net/xdp/xsk.c (ffffffff81ba5d70)
Location: include/linux/netdevice.h:4141
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_notifier
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk.c:xsk_release
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81ba87a4)
Location: include/linux/netdevice.h:4141
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_release_deferred
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
In kernel/bpf/devmap.c (ffffffff8126b3ae)
Location: include/linux/netdevice.h:4160
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:__dev_map_alloc_node
  - kernel/bpf/devmap.c:__dev_map_entry_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/devmap.c:dev_map_free
```
```
In kernel/bpf/offload.c (ffffffff8126f9c7)
Location: include/linux/netdevice.h:4160
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_prog_offload_init
  - kernel/bpf/offload.c:bpf_prog_offload_init
```
```
In security/selinux/netif.c (ffffffff8153af75)
Location: include/linux/netdevice.h:4160
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_sid_slow
```
```
In security/lsm_audit.c (ffffffff8155a1e4)
Location: include/linux/netdevice.h:4160
Inline: True
Inline callers:
  - security/lsm_audit.c:dump_common_audit_data
```
```
In drivers/net/tun.c (ffffffff8190d447)
Location: include/linux/netdevice.h:4160
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
In net/core/sock.c (ffffffff81a7de24)
Location: include/linux/netdevice.h:4160
Inline: True
Inline callers:
  - net/core/sock.c:sock_set_timestamping
```
```
In net/core/dev.c (ffffffff81a9d41a)
Location: include/linux/netdevice.h:4160
Inline: True
Inline callers:
  - net/core/dev.c:unregister_netdevice_many
  - net/core/dev.c:bpf_xdp_link_attach
  - net/core/dev.c:bpf_xdp_link_attach
  - net/core/dev.c:__netdev_adjacent_dev_remove
  - net/core/dev.c:__netdev_adjacent_dev_insert
```
```
In net/core/dst.c (ffffffff81aa951e)
Location: include/linux/netdevice.h:4160
Inline: True
Inline callers:
  - net/core/dst.c:dst_dev_put
  - net/core/dst.c:dst_destroy
```
```
In net/core/neighbour.c (ffffffff81aae6ed)
Location: include/linux/netdevice.h:4160
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_clear
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:pneigh_delete
  - net/core/neighbour.c:pneigh_lookup
```
```
In net/core/utils.c (ffffffff81abc0c6)
Location: include/linux/netdevice.h:4160
Inline: True
Inline callers:
  - net/core/utils.c:inet6_pton
```
```
In net/core/link_watch.c (ffffffff81abc4c8)
Location: include/linux/netdevice.h:4160
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_do_dev
```
```
In net/core/filter.c (ffffffff81acd221)
Location: include/linux/netdevice.h:4160
Inline: True
Inline callers:
  - net/core/filter.c:_bpf_setsockopt
```
```
In net/core/dev_ioctl.c (ffffffff81ad0c3d)
Location: include/linux/netdevice.h:4160
Inline: True
Inline callers:
  - net/core/dev_ioctl.c:dev_ifsioc
```
```
In net/core/net-sysfs.c (ffffffff81ad5468)
Location: include/linux/netdevice.h:4160
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_queue_release
  - net/core/net-sysfs.c:rx_queue_release
```
```
In net/core/netpoll.c (ffffffff81ada823)
Location: include/linux/netdevice.h:4160
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_cleanup
  - net/core/netpoll.c:netpoll_setup
```
```
In net/core/drop_monitor.c (ffffffff81aea52b)
Location: include/linux/netdevice.h:4160
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_monitor_stop
  - net/core/drop_monitor.c:net_dm_hw_monitor_start
  - net/core/drop_monitor.c:net_dm_hw_trap_packet_probe
  - net/core/drop_monitor.c:net_dm_hw_packet_work
```
```
In net/core/netprio_cgroup.c (ffffffff81aecb06)
Location: include/linux/netdevice.h:4160
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:write_priomap
```
```
In net/core/lwt_bpf.c (ffffffff81aee675)
Location: include/linux/netdevice.h:4160
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_input_reroute
```
```
In net/core/devlink.c (ffffffff81b045a7)
Location: include/linux/netdevice.h:4160
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_flash_update
  - net/core/devlink.c:devlink_compat_running_version
```
```
In net/sched/sch_generic.c (ffffffff81b0fcff)
Location: include/linux/netdevice.h:4160
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/sched/sch_api.c (ffffffff81b11eca)
Location: include/linux/netdevice.h:4160
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:qdisc_create
```
```
In net/netlink/af_netlink.c (ffffffff81b22125)
Location: include/linux/netdevice.h:4160
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_deliver_tap
```
```
In net/bpf/test_run.c (ffffffff81b2b6d2)
Location: include/linux/netdevice.h:4160
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ethtool/ioctl.c (ffffffff81b2e791)
Location: include/linux/netdevice.h:4160
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_phys_id
```
```
In net/ethtool/netlink.c (ffffffff81b3343f)
Location: include/linux/netdevice.h:4160
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_start
  - net/ethtool/netlink.c:ethnl_default_dumpit
  - net/ethtool/netlink.c:ethnl_default_doit
  - net/ethtool/netlink.c:ethnl_default_doit
  - net/ethtool/netlink.c:ethnl_parse_header_dev_get
```
```
In net/ethtool/linkinfo.c (ffffffff81b35e4b)
Location: include/linux/netdevice.h:4160
Inline: True
Inline callers:
  - net/ethtool/linkinfo.c:ethnl_set_linkinfo
```
```
In net/ethtool/linkmodes.c (ffffffff81b36768)
Location: include/linux/netdevice.h:4160
Inline: True
Inline callers:
  - net/ethtool/linkmodes.c:ethnl_set_linkmodes
```
```
In net/ethtool/debug.c (ffffffff81b36cf1)
Location: include/linux/netdevice.h:4160
Inline: True
Inline callers:
  - net/ethtool/debug.c:ethnl_set_debug
```
```
In net/ethtool/wol.c (ffffffff81b37041)
Location: include/linux/netdevice.h:4160
Inline: True
Inline callers:
  - net/ethtool/wol.c:ethnl_set_wol
```
```
In net/ethtool/features.c (ffffffff81b37616)
Location: include/linux/netdevice.h:4160
Inline: True
Inline callers:
  - net/ethtool/features.c:ethnl_set_features
```
```
In net/ethtool/privflags.c (ffffffff81b37bdf)
Location: include/linux/netdevice.h:4160
Inline: True
Inline callers:
  - net/ethtool/privflags.c:ethnl_set_privflags
```
```
In net/ethtool/rings.c (ffffffff81b37fcf)
Location: include/linux/netdevice.h:4160
Inline: True
Inline callers:
  - net/ethtool/rings.c:ethnl_set_rings
```
```
In net/ethtool/channels.c (ffffffff81b3852f)
Location: include/linux/netdevice.h:4160
Inline: True
Inline callers:
  - net/ethtool/channels.c:ethnl_set_channels
```
```
In net/ethtool/coalesce.c (ffffffff81b38f11)
Location: include/linux/netdevice.h:4160
Inline: True
Inline callers:
  - net/ethtool/coalesce.c:ethnl_set_coalesce
```
```
In net/ethtool/pause.c (ffffffff81b393af)
Location: include/linux/netdevice.h:4160
Inline: True
Inline callers:
  - net/ethtool/pause.c:ethnl_set_pause
```
```
In net/ethtool/eee.c (ffffffff81b397fe)
Location: include/linux/netdevice.h:4160
Inline: True
Inline callers:
  - net/ethtool/eee.c:ethnl_set_eee
```
```
In net/ethtool/cabletest.c (ffffffff81b3a737)
Location: include/linux/netdevice.h:4160
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_act_cable_test_tdr
  - net/ethtool/cabletest.c:ethnl_act_cable_test
```
```
In net/ethtool/tunnels.c (ffffffff81b3ae35)
Location: include/linux/netdevice.h:4160
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_start
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
```
```
In net/ethtool/fec.c (ffffffff81b3b76f)
Location: include/linux/netdevice.h:4160
Inline: True
Inline callers:
  - net/ethtool/fec.c:ethnl_set_fec
```
```
In net/netfilter/nf_queue.c (ffffffff81b3ef2e)
Location: include/linux/netdevice.h:4160
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
```
```
In net/ipv4/route.c (ffffffff81b4444b)
Location: include/linux/netdevice.h:4160
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_flush_dev
```
```
In net/ipv4/ip_sockglue.c (ffffffff81b52e9e)
Location: include/linux/netdevice.h:4160
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81b93175)
Location: include/linux/netdevice.h:4160
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_build_probe
```
```
In net/ipv4/devinet.c (ffffffff81b9497b)
Location: include/linux/netdevice.h:4160
Inline: True
Inline callers:
  - net/ipv4/devinet.c:in_dev_finish_destroy
```
```
In net/ipv4/fib_semantics.c (ffffffff81ba522c)
Location: include/linux/netdevice.h:4160
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nh_common_release
```
```
In net/ipv4/ipmr.c (ffffffff81bbe8d9)
Location: include/linux/netdevice.h:4160
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
  - net/ipv4/ipmr.c:ipmr_new_tunnel
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bcca58)
Location: include/linux/netdevice.h:4160
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_ifdown
```
```
In net/xfrm/xfrm_state.c (ffffffff81bd6c1b)
Location: include/linux/netdevice.h:4160
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
```
```
In net/xfrm/xfrm_input.c (ffffffff81bdf33e)
Location: include/linux/netdevice.h:4160
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_device.c (ffffffff81be2882)
Location: include/linux/netdevice.h:4160
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
```
```
In net/ipv6/addrconf.c (ffffffff81bff82b)
Location: include/linux/netdevice.h:4160
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:ipv6_add_dev
```
```
In net/ipv6/route.c (ffffffff81c0e499)
Location: include/linux/netdevice.h:4160
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:rt6_probe_deferred
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81c16af6)
Location: include/linux/netdevice.h:4160
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff81c22d6a)
Location: include/linux/netdevice.h:4160
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ip6mr.c (ffffffff81c3bd26)
Location: include/linux/netdevice.h:4160
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mif6_add
  - net/ipv6/ip6mr.c:mif6_add
  - net/ipv6/ip6mr.c:mif6_delete
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81c409b7)
Location: include/linux/netdevice.h:4160
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
```
```
In net/ipv6/addrconf_core.c (ffffffff81c4c4be)
Location: include/linux/netdevice.h:4160
Inline: True
Inline callers:
  - net/ipv6/addrconf_core.c:in6_dev_finish_destroy
```
```
In net/packet/af_packet.c (ffffffff81c545aa)
Location: include/linux/netdevice.h:4160
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
In net/netlabel/netlabel_unlabeled.c (ffffffff81c5f2c1)
Location: include/linux/netdevice.h:4160
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
```
In net/switchdev/switchdev.c (ffffffff81c6964b)
Location: include/linux/netdevice.h:4160
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_deferred_process
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81c710b3)
Location: include/linux/netdevice.h:4160
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
In net/xdp/xsk.c (ffffffff81c743e2)
Location: include/linux/netdevice.h:4160
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_notifier
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk.c:xsk_release
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81c764f8)
Location: include/linux/netdevice.h:4160
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_release_deferred
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
In kernel/bpf/devmap.c (ffffffff812b9fac)
Location: include/linux/netdevice.h:4035
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:__dev_map_alloc_node
  - kernel/bpf/devmap.c:__dev_map_entry_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/devmap.c:dev_map_free
```
```
In kernel/bpf/offload.c (ffffffff812bea31)
Location: include/linux/netdevice.h:4035
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_prog_offload_init
  - kernel/bpf/offload.c:bpf_prog_offload_init
```
```
In security/selinux/netif.c (ffffffff815d26e7)
Location: include/linux/netdevice.h:4035
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_sid_slow
```
```
In security/lsm_audit.c (ffffffff815f505e)
Location: include/linux/netdevice.h:4035
Inline: True
Inline callers:
  - security/lsm_audit.c:dump_common_audit_data
```
```
In drivers/net/tun.c (ffffffff81a6263b)
Location: include/linux/netdevice.h:4035
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
Location: include/linux/netdevice.h:4035
Inline: True
Inline callers:
  - net/core/sock.c:sock_set_timestamping
```
```
In net/core/dev.c (ffffffff81c1e269)
Location: include/linux/netdevice.h:4035
Inline: True
Inline callers:
  - net/core/dev.c:bpf_xdp_link_attach
  - net/core/dev.c:bpf_xdp_link_attach
```
```
In net/core/neighbour.c (ffffffff81c228d9)
Location: include/linux/netdevice.h:4035
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:pneigh_queue_purge
```
```
In net/core/utils.c (ffffffff81c36b1d)
Location: include/linux/netdevice.h:4035
Inline: True
Inline callers:
  - net/core/utils.c:inet6_pton
```
```
In net/core/filter.c (ffffffff81c4a9cd)
Location: include/linux/netdevice.h:4035
Inline: True
Inline callers:
  - net/core/filter.c:_bpf_setsockopt
```
```
In net/core/netpoll.c (ffffffff81c5c2c6)
Location: include/linux/netdevice.h:4035
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
```
```
In net/core/netprio_cgroup.c (ffffffff81c6f671)
Location: include/linux/netdevice.h:4035
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:write_priomap
```
```
In net/core/lwt_bpf.c (ffffffff81c7158b)
Location: include/linux/netdevice.h:4035
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_input_reroute
```
```
In net/sched/sch_api.c (ffffffff81c991b2)
Location: include/linux/netdevice.h:4035
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
```
```
In net/netlink/af_netlink.c (ffffffff81caad83)
Location: include/linux/netdevice.h:4035
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_deliver_tap
```
```
In net/bpf/test_run.c (ffffffff81cb5b82)
Location: include/linux/netdevice.h:4035
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ethtool/netlink.c (ffffffff81cbea26)
Location: include/linux/netdevice.h:4035
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_dumpit
  - net/ethtool/netlink.c:ethnl_parse_header_dev_get
```
```
In net/netfilter/nf_queue.c (ffffffff81ccb63e)
Location: include/linux/netdevice.h:4035
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
```
```
In net/ipv4/ip_sockglue.c (ffffffff81ce0d1e)
Location: include/linux/netdevice.h:4035
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81d25815)
Location: include/linux/netdevice.h:4035
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_build_probe
```
```
In net/ipv4/ipmr.c (ffffffff81d5382c)
Location: include/linux/netdevice.h:4035
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:ipmr_new_tunnel
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d62771)
Location: include/linux/netdevice.h:4035
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_ifdown
```
```
In net/xfrm/xfrm_input.c (ffffffff81d760c0)
Location: include/linux/netdevice.h:4035
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_device.c (ffffffff81d799f3)
Location: include/linux/netdevice.h:4035
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
```
```
In net/ipv6/addrconf.c (ffffffff81d99316)
Location: include/linux/netdevice.h:4035
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/route.c (ffffffff81da796c)
Location: include/linux/netdevice.h:4035
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81db23af)
Location: include/linux/netdevice.h:4035
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff81dbfc4c)
Location: include/linux/netdevice.h:4035
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ip6mr.c (ffffffff81dda08f)
Location: include/linux/netdevice.h:4035
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mif6_add
  - net/ipv6/ip6mr.c:mif6_add
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/packet/af_packet.c (ffffffff81df2d97)
Location: include/linux/netdevice.h:4035
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81e016a6)
Location: include/linux/netdevice.h:4035
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81e14c90)
Location: include/linux/netdevice.h:4035
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
Location: include/linux/netdevice.h:4035
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_notifier
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk.c:xsk_release
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81e1acb8)
Location: include/linux/netdevice.h:4035
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_release_deferred
  - net/xdp/xsk_buff_pool.c:xp_assign_dev
```
```
In net/mctp/device.c (ffffffff81e38760)
Location: include/linux/netdevice.h:4035
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
In kernel/bpf/devmap.c (ffffffff8131d2fc)
Location: include/linux/netdevice.h:4079
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:__dev_map_alloc_node
  - kernel/bpf/devmap.c:__dev_map_entry_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/devmap.c:dev_map_free
```
```
In kernel/bpf/offload.c (ffffffff81322061)
Location: include/linux/netdevice.h:4079
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_prog_offload_init
  - kernel/bpf/offload.c:bpf_prog_offload_init
```
```
In security/selinux/netif.c (ffffffff816805f7)
Location: include/linux/netdevice.h:4079
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_sid_slow
```
```
In security/lsm_audit.c (ffffffff816a5b2e)
Location: include/linux/netdevice.h:4079
Inline: True
Inline callers:
  - security/lsm_audit.c:dump_common_audit_data
```
```
In drivers/net/tun.c (ffffffff81bede0b)
Location: include/linux/netdevice.h:4079
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
Location: include/linux/netdevice.h:4079
Inline: True
Inline callers:
  - net/core/sock.c:sock_set_timestamping
```
```
In net/core/dev.c (ffffffff81dcf6a9)
Location: include/linux/netdevice.h:4079
Inline: True
Inline callers:
  - net/core/dev.c:bpf_xdp_link_attach
  - net/core/dev.c:bpf_xdp_link_attach
```
```
In net/core/neighbour.c (ffffffff81dd52bb)
Location: include/linux/netdevice.h:4079
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:pneigh_queue_purge
```
```
In net/core/utils.c (ffffffff81dea2ae)
Location: include/linux/netdevice.h:4079
Inline: True
Inline callers:
  - net/core/utils.c:inet6_pton
```
```
In net/core/netpoll.c (ffffffff81e1275b)
Location: include/linux/netdevice.h:4079
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_setup
```
```
In net/core/netprio_cgroup.c (ffffffff81e274c1)
Location: include/linux/netdevice.h:4079
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:write_priomap
```
```
In net/core/lwt_bpf.c (ffffffff81e2964b)
Location: include/linux/netdevice.h:4079
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_input_reroute
```
```
In net/sched/sch_api.c (ffffffff81e550a2)
Location: include/linux/netdevice.h:4079
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
```
```
In net/netlink/af_netlink.c (ffffffff81e67ed0)
Location: include/linux/netdevice.h:4079
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_deliver_tap
```
```
In net/bpf/test_run.c (ffffffff81e74052)
Location: include/linux/netdevice.h:4079
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ethtool/netlink.c (ffffffff81e7d546)
Location: include/linux/netdevice.h:4079
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_dumpit
  - net/ethtool/netlink.c:ethnl_parse_header_dev_get
```
```
In net/netfilter/nf_queue.c (ffffffff81e8b44e)
Location: include/linux/netdevice.h:4079
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
```
```
In net/ipv4/ip_sockglue.c (ffffffff81ea1116)
Location: include/linux/netdevice.h:4079
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
```
```
In net/ipv4/icmp.c (ffffffff81eed0a5)
Location: include/linux/netdevice.h:4079
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_build_probe
```
```
In net/ipv4/ipmr.c (ffffffff81f1d559)
Location: include/linux/netdevice.h:4079
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:ipmr_new_tunnel
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f2d281)
Location: include/linux/netdevice.h:4079
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_ifdown
```
```
In net/xfrm/xfrm_input.c (ffffffff81f42800)
Location: include/linux/netdevice.h:4079
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_device.c (ffffffff81f46454)
Location: include/linux/netdevice.h:4079
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_policy_add
  - net/xfrm/xfrm_device.c:xfrm_dev_policy_add
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
```
```
In net/ipv6/addrconf.c (ffffffff81f68036)
Location: include/linux/netdevice.h:4079
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/route.c (ffffffff81f76fa4)
Location: include/linux/netdevice.h:4079
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81f80e01)
Location: include/linux/netdevice.h:4079
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
```
```
In net/ipv6/icmp.c (ffffffff81f9039b)
Location: include/linux/netdevice.h:4079
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ip6mr.c (ffffffff81fabd39)
Location: include/linux/netdevice.h:4079
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mif6_add
  - net/ipv6/ip6mr.c:mif6_add
```
```
In net/packet/af_packet.c (ffffffff81fc7197)
Location: include/linux/netdevice.h:4079
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81fd6506)
Location: include/linux/netdevice.h:4079
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81febba0)
Location: include/linux/netdevice.h:4079
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
In net/xdp/xsk.c (ffffffff81fede4c)
Location: include/linux/netdevice.h:4079
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_notifier
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk.c:xsk_release
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81ff21c8)
Location: include/linux/netdevice.h:4079
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_release_deferred
  - net/xdp/xsk_buff_pool.c:xp_assign_dev
```
```
In net/mctp/device.c (ffffffff82011a20)
Location: include/linux/netdevice.h:4079
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
In kernel/bpf/devmap.c (ffffffff8134d0ac)
Location: include/linux/netdevice.h:4138
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:__dev_map_alloc_node
  - kernel/bpf/devmap.c:__dev_map_entry_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/devmap.c:dev_map_free
```
```
In kernel/bpf/offload.c (ffffffff81351ed7)
Location: include/linux/netdevice.h:4138
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_prog_dev_bound_init
```
```
In security/selinux/netif.c (ffffffff816b86c7)
Location: include/linux/netdevice.h:4138
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_sid_slow
```
```
In security/lsm_audit.c (ffffffff816de425)
Location: include/linux/netdevice.h:4138
Inline: True
Inline callers:
  - security/lsm_audit.c:dump_common_audit_data
```
```
In drivers/net/tun.c (ffffffff81c4633b)
Location: include/linux/netdevice.h:4138
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
In drivers/net/net_failover.c (ffffffff81c6ed00)
Location: include/linux/netdevice.h:4138
Inline: True
Inline callers:
  - drivers/net/net_failover.c:net_failover_slave_unregister
  - drivers/net/net_failover.c:net_failover_slave_register
```
```
In net/core/sock.c (ffffffff81e0d055)
Location: include/linux/netdevice.h:4138
Inline: True
Inline callers:
  - net/core/sock.c:sock_set_timestamping
```
```
In net/core/dev.c (ffffffff81e402b9)
Location: include/linux/netdevice.h:4138
Inline: True
Inline callers:
  - net/core/dev.c:bpf_xdp_link_attach
  - net/core/dev.c:bpf_xdp_link_attach
```
```
In net/core/neighbour.c (ffffffff81e4620f)
Location: include/linux/netdevice.h:4138
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:pneigh_queue_purge
```
```
In net/core/utils.c (ffffffff81e5ba9e)
Location: include/linux/netdevice.h:4138
Inline: True
Inline callers:
  - net/core/utils.c:inet6_pton
```
```
In net/core/netprio_cgroup.c (ffffffff81e9cad1)
Location: include/linux/netdevice.h:4138
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:write_priomap
```
```
In net/core/lwt_bpf.c (ffffffff81e9ec7b)
Location: include/linux/netdevice.h:4138
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_input_reroute
```
```
In net/sched/sch_api.c (ffffffff81eb0952)
Location: include/linux/netdevice.h:4138
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
```
```
In net/netlink/af_netlink.c (ffffffff81ec3d28)
Location: include/linux/netdevice.h:4138
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_deliver_tap
```
```
In net/bpf/test_run.c (ffffffff81ecfdd9)
Location: include/linux/netdevice.h:4138
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ethtool/netlink.c (ffffffff81ed9b06)
Location: include/linux/netdevice.h:4138
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_dumpit
```
```
In net/netfilter/nf_queue.c (ffffffff81ee949e)
Location: include/linux/netdevice.h:4138
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
```
```
In net/ipv4/ip_sockglue.c (ffffffff81eff8c2)
Location: include/linux/netdevice.h:4138
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
```
```
In net/ipv4/icmp.c (ffffffff81f4ca45)
Location: include/linux/netdevice.h:4138
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_build_probe
```
```
In net/ipv4/ipmr.c (ffffffff81f7ccb9)
Location: include/linux/netdevice.h:4138
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:ipmr_new_tunnel
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f8cd81)
Location: include/linux/netdevice.h:4138
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_ifdown
```
```
In net/xfrm/xfrm_input.c (ffffffff81fa2023)
Location: include/linux/netdevice.h:4138
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_device.c (ffffffff81fa5e7e)
Location: include/linux/netdevice.h:4138
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_policy_add
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
```
```
In net/ipv6/addrconf.c (ffffffff81fc8085)
Location: include/linux/netdevice.h:4138
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81fe1239)
Location: include/linux/netdevice.h:4138
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
```
```
In net/ipv6/icmp.c (ffffffff81ff0bec)
Location: include/linux/netdevice.h:4138
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ip6mr.c (ffffffff8200c4d9)
Location: include/linux/netdevice.h:4138
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mif6_add
  - net/ipv6/ip6mr.c:mif6_add
```
```
In net/packet/af_packet.c (ffffffff82027ef8)
Location: include/linux/netdevice.h:4138
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff820521c6)
Location: include/linux/netdevice.h:4138
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
```
In net/ncsi/ncsi-netlink.c (ffffffff82067e40)
Location: include/linux/netdevice.h:4138
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
In net/xdp/xsk.c (ffffffff82069fac)
Location: include/linux/netdevice.h:4138
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_notifier
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk.c:xsk_release
```
```
In net/xdp/xsk_buff_pool.c (ffffffff8206e3f8)
Location: include/linux/netdevice.h:4138
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_release_deferred
  - net/xdp/xsk_buff_pool.c:xp_assign_dev
```
```
In net/mctp/device.c (ffffffff8208e810)
Location: include/linux/netdevice.h:4138
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
In kernel/bpf/devmap.c (ffffffff813745d8)
Location: include/linux/netdevice.h:4205
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:__dev_map_alloc_node
  - kernel/bpf/devmap.c:__dev_map_entry_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/devmap.c:dev_map_free
```
```
In kernel/bpf/offload.c (ffffffff813793c2)
Location: include/linux/netdevice.h:4205
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_prog_dev_bound_init
```
```
In security/selinux/netif.c (ffffffff816f50f1)
Location: include/linux/netdevice.h:4205
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_sid_slow
```
```
In security/lsm_audit.c (ffffffff8171afe9)
Location: include/linux/netdevice.h:4205
Inline: True
Inline callers:
  - security/lsm_audit.c:dump_common_audit_data
```
```
In drivers/net/tun.c (ffffffff81cfbc4b)
Location: include/linux/netdevice.h:4205
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
In drivers/net/net_failover.c (ffffffff81d23595)
Location: include/linux/netdevice.h:4205
Inline: True
Inline callers:
  - drivers/net/net_failover.c:net_failover_slave_unregister
  - drivers/net/net_failover.c:net_failover_slave_register
```
```
In net/core/sock.c (ffffffff81ec99f4)
Location: include/linux/netdevice.h:4205
Inline: True
Inline callers:
  - net/core/sock.c:sock_set_timestamping
```
```
In net/core/dev.c (ffffffff81efec75)
Location: include/linux/netdevice.h:4205
Inline: True
Inline callers:
  - net/core/dev.c:bpf_xdp_link_attach
  - net/core/dev.c:bpf_xdp_link_attach
```
```
In net/core/neighbour.c (ffffffff81f04eb2)
Location: include/linux/netdevice.h:4205
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:pneigh_queue_purge
```
```
In net/core/utils.c (ffffffff81f1ae5e)
Location: include/linux/netdevice.h:4205
Inline: True
Inline callers:
  - net/core/utils.c:inet6_pton
```
```
In net/core/netprio_cgroup.c (ffffffff81f5f1f1)
Location: include/linux/netdevice.h:4205
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:write_priomap
```
```
In net/core/lwt_bpf.c (ffffffff81f613eb)
Location: include/linux/netdevice.h:4205
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_input_reroute
```
```
In net/sched/sch_api.c (ffffffff81f733c2)
Location: include/linux/netdevice.h:4205
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
```
```
In net/netlink/af_netlink.c (ffffffff81f870e8)
Location: include/linux/netdevice.h:4205
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_deliver_tap
```
```
In net/bpf/test_run.c (ffffffff81f9372c)
Location: include/linux/netdevice.h:4205
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ethtool/netlink.c (ffffffff81f9d967)
Location: include/linux/netdevice.h:4205
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_dumpit
```
```
In net/netfilter/nf_queue.c (ffffffff81fad20e)
Location: include/linux/netdevice.h:4205
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
```
```
In net/ipv4/ip_sockglue.c (ffffffff81fc3b52)
Location: include/linux/netdevice.h:4205
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
```
```
In net/ipv4/icmp.c (ffffffff82012b55)
Location: include/linux/netdevice.h:4205
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_build_probe
```
```
In net/ipv4/ipmr.c (ffffffff820433b9)
Location: include/linux/netdevice.h:4205
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:ipmr_new_tunnel
```
```
In net/xfrm/xfrm_policy.c (ffffffff8205a711)
Location: include/linux/netdevice.h:4205
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_ifdown
```
```
In net/xfrm/xfrm_input.c (ffffffff8206f23a)
Location: include/linux/netdevice.h:4205
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_device.c (ffffffff8207317e)
Location: include/linux/netdevice.h:4205
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_policy_add
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
```
```
In net/ipv6/addrconf.c (ffffffff82095793)
Location: include/linux/netdevice.h:4205
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff820ae706)
Location: include/linux/netdevice.h:4205
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
```
```
In net/ipv6/icmp.c (ffffffff820be7d9)
Location: include/linux/netdevice.h:4205
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/ip6mr.c (ffffffff820db4a9)
Location: include/linux/netdevice.h:4205
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mif6_add
  - net/ipv6/ip6mr.c:mif6_add
```
```
In net/packet/af_packet.c (ffffffff820f7758)
Location: include/linux/netdevice.h:4205
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:packet_snd
  - net/packet/af_packet.c:tpacket_snd
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff82124946)
Location: include/linux/netdevice.h:4205
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
```
In net/ncsi/ncsi-netlink.c (ffffffff8213b0c0)
Location: include/linux/netdevice.h:4205
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
In net/xdp/xsk.c (ffffffff8213d40c)
Location: include/linux/netdevice.h:4205
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_notifier
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk.c:xsk_release
```
```
In net/xdp/xsk_buff_pool.c (ffffffff82142478)
Location: include/linux/netdevice.h:4205
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_release_deferred
  - net/xdp/xsk_buff_pool.c:xp_assign_dev
```
```
In net/mctp/device.c (ffffffff82164d00)
Location: include/linux/netdevice.h:4205
Inline: True
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
In kernel/bpf/devmap.c (ffff800010286f30)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:__dev_map_entry_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/devmap.c:dev_map_free
```
```
In kernel/bpf/offload.c (ffff80001028a91c)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_prog_offload_init
  - kernel/bpf/offload.c:bpf_prog_offload_init
```
```
In security/selinux/netif.c (ffff800010558080)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_sid
```
```
In security/lsm_audit.c (ffff8000105773b0)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - security/lsm_audit.c:dump_common_audit_data
```
```
In drivers/net/tun.c (ffff8000109dcda0)
Location: include/linux/netdevice.h:3738
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
In net/core/dev.c (ffff800010bcbe48)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/core/dev.c:rollback_registered_many
```
```
In net/core/ethtool.c (ffff800010bdcbd8)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
```
```
In net/core/dst.c (ffff800010be0990)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/core/dst.c:dst_dev_put
  - net/core/dst.c:dst_destroy
```
```
In net/core/neighbour.c (ffff800010be4dbc)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:pneigh_delete
  - net/core/neighbour.c:pneigh_lookup
  - net/core/neighbour.c:__neigh_ifdown
  - net/core/neighbour.c:pneigh_queue_purge
```
```
In net/core/utils.c (ffff800010bf33e0)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/core/utils.c:inet6_pton
```
```
In net/core/link_watch.c (ffff800010bf3860)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_do_dev
```
```
In net/core/net-sysfs.c (ffff800010c0a2c4)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_queue_release
  - net/core/net-sysfs.c:rx_queue_release
```
```
In net/core/netpoll.c (ffff800010c10aa0)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_cleanup
  - net/core/netpoll.c:netpoll_setup
```
```
In net/core/drop_monitor.c (ffff800010c1aaa8)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_metadata_free
```
```
In net/core/netprio_cgroup.c (ffff800010c1d2b8)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:write_priomap
```
```
In net/core/lwt_bpf.c (ffff800010c1f1e0)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_input
```
```
In net/core/devlink.c (ffff800010c3073c)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_flash_update
  - net/core/devlink.c:devlink_compat_running_version
```
```
In net/sched/sch_generic.c (ffff800010c3a328)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/sched/sch_api.c (ffff800010c3c998)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:qdisc_create
```
```
In net/netlink/af_netlink.c (ffff800010c4b6d8)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_deliver_tap
```
```
In net/netfilter/nf_queue.c (ffff800010c55c64)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
```
```
In net/ipv4/route.c (ffff800010c5a95c)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_flush_dev
```
```
In net/ipv4/ip_sockglue.c (ffff800010c68d8c)
Location: include/linux/netdevice.h:3738
Inline: True
```
```
In net/ipv4/devinet.c (ffff800010ca65e4)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/ipv4/devinet.c:in_dev_finish_destroy
```
```
In net/ipv4/fib_semantics.c (ffff800010cb689c)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nh_common_release
```
```
In net/ipv4/ipmr.c (ffff800010ccd6fc)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
```
```
In net/xfrm/xfrm_policy.c (ffff800010cda874)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_ifdown
```
```
In net/xfrm/xfrm_state.c (ffff800010ce362c)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
```
```
In net/xfrm/xfrm_input.c (ffff800010ceabf0)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_device.c (ffff800010cee124)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
```
```
In net/ipv6/addrconf.c (ffff800010d083e0)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/route.c (ffff800010d171b8)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:rt6_probe_deferred
```
```
In net/ipv6/ipv6_sockglue.c (ffff800010d1f6a8)
Location: include/linux/netdevice.h:3738
Inline: True
```
```
In net/ipv6/ip6mr.c (ffff800010d46c58)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:mif6_delete
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_policy.c (ffff800010d48cc0)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
```
```
In net/ipv6/addrconf_core.c (ffff800010d52f34)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/ipv6/addrconf_core.c:in6_dev_finish_destroy
```
```
In net/packet/af_packet.c (ffff800010d5aeec)
Location: include/linux/netdevice.h:3738
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
In net/netlabel/netlabel_unlabeled.c (ffff800010d68f90)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
```
In net/switchdev/switchdev.c (ffff800010d74100)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_deferred_process
```
```
In net/ncsi/ncsi-netlink.c (ffff800010d7c350)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ndp_from_ifindex
```
```
In net/xdp/xsk.c (ffff800010d7eb50)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk.c:xsk_unbind_dev
```
```
In net/xdp/xdp_umem.c (ffff800010d8106c)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_clear_dev
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
In kernel/bpf/devmap.c (c04b6a04)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:__dev_map_entry_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/devmap.c:dev_map_free
```
```
In kernel/bpf/offload.c (c04ba218)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_prog_offload_init
  - kernel/bpf/offload.c:bpf_prog_offload_init
```
```
In security/selinux/netif.c (c070ce9c)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_sid
```
```
In security/lsm_audit.c (c072a038)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - security/lsm_audit.c:dump_common_audit_data
```
```
In drivers/net/tun.c (c0ac15c8)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_show_fdinfo
  - drivers/net/tun.c:tun_peek_len
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_chr_read_iter
  - drivers/net/tun.c:tun_chr_write_iter
  - drivers/net/tun.c:tun_chr_poll
```
```
In net/core/dev.c (c0ce9e60)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/core/dev.c:rollback_registered_many
```
```
In net/core/ethtool.c (c0cf74e0)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
```
```
In net/core/dst.c (c0cfa950)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/core/dst.c:dst_dev_put
  - net/core/dst.c:dst_destroy
```
```
In net/core/neighbour.c (c0cfd008)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:pneigh_delete
  - net/core/neighbour.c:pneigh_lookup
  - net/core/neighbour.c:__neigh_ifdown
  - net/core/neighbour.c:pneigh_queue_purge
```
```
In net/core/utils.c (c0d0bc08)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/core/utils.c:inet6_pton
```
```
In net/core/link_watch.c (c0d0bee0)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_do_dev
```
```
In net/core/net-sysfs.c (c0d2265c)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_queue_release
  - net/core/net-sysfs.c:rx_queue_release
```
```
In net/core/netpoll.c (c0d288d0)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_cleanup
  - net/core/netpoll.c:netpoll_setup
```
```
In net/core/drop_monitor.c (c0d32660)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_metadata_free
```
```
In net/core/netprio_cgroup.c (c0d351e8)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:write_priomap
```
```
In net/core/lwt_bpf.c (c0d36434)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_input
```
```
In net/core/devlink.c (c0d4773c)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_flash_update
  - net/core/devlink.c:devlink_compat_running_version
```
```
In net/sched/sch_generic.c (c0d4c334)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/sched/sch_api.c (c0d4e194)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:qdisc_create
```
```
In net/netlink/af_netlink.c (c0d5c078)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_deliver_tap
```
```
In net/netfilter/nf_queue.c (c0d65668)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
```
```
In net/ipv4/route.c (c0d69ea4)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_flush_dev
```
```
In net/ipv4/ip_sockglue.c (c0d7805c)
Location: include/linux/netdevice.h:3738
Inline: True
```
```
In net/ipv4/devinet.c (c0db1e2c)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/ipv4/devinet.c:in_dev_finish_destroy
```
```
In net/ipv4/fib_semantics.c (c0dc2048)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nh_common_release
```
```
In net/ipv4/ipmr.c (c0dd5204)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
```
```
In net/xfrm/xfrm_policy.c (c0de2630)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_ifdown
```
```
In net/xfrm/xfrm_state.c (c0debbd8)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
```
```
In net/xfrm/xfrm_input.c (c0df2f20)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_device.c (c0df5aa0)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
```
```
In net/ipv6/addrconf.c (c0e0eba8)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/route.c (c0e1cd74)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:rt6_probe_deferred
```
```
In net/ipv6/ipv6_sockglue.c (c0e243e8)
Location: include/linux/netdevice.h:3738
Inline: True
```
```
In net/ipv6/ip6mr.c (c0e49010)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:mif6_delete
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_policy.c (c0e49f30)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
```
```
In net/ipv6/addrconf_core.c (c0e53728)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/ipv6/addrconf_core.c:in6_dev_finish_destroy
```
```
In net/packet/af_packet.c (c0e57bc0)
Location: include/linux/netdevice.h:3738
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
In net/netlabel/netlabel_unlabeled.c (c0e665e8)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
```
In net/switchdev/switchdev.c (c0e7014c)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_deferred_process
```
```
In net/ncsi/ncsi-netlink.c (c0e771e8)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ndp_from_ifindex
```
```
In net/xdp/xsk.c (c0e78dc4)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk.c:xsk_unbind_dev
```
```
In net/xdp/xdp_umem.c (c0e7b570)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_clear_dev
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
In kernel/bpf/devmap.c (c0000000003325f0)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:__dev_map_entry_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/devmap.c:dev_map_free
```
```
In kernel/bpf/offload.c (c0000000003364ec)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_prog_offload_init
  - kernel/bpf/offload.c:bpf_prog_offload_init
```
```
In security/selinux/netif.c (c0000000006b615c)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_sid
```
```
In security/lsm_audit.c (c0000000006e0770)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - security/lsm_audit.c:dump_common_audit_data
```
```
In drivers/net/tun.c (c000000000aa2cc8)
Location: include/linux/netdevice.h:3738
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
In net/core/dev.c (c000000000ca8850)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/core/dev.c:rollback_registered_many
```
```
In net/core/ethtool.c (c000000000cbced8)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
```
```
In net/core/dst.c (c000000000cc2010)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/core/dst.c:dst_dev_put
  - net/core/dst.c:dst_destroy
```
```
In net/core/neighbour.c (c000000000cc6840)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:pneigh_delete
  - net/core/neighbour.c:pneigh_lookup
  - net/core/neighbour.c:__neigh_ifdown
  - net/core/neighbour.c:pneigh_queue_purge
```
```
In net/core/utils.c (c000000000cd8398)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/core/utils.c:inet6_pton
```
```
In net/core/link_watch.c (c000000000cd8910)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_do_dev
```
```
In net/core/net-sysfs.c (c000000000cf6f88)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_queue_release
  - net/core/net-sysfs.c:rx_queue_release
```
```
In net/core/netpoll.c (c000000000cfdda4)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_cleanup
  - net/core/netpoll.c:netpoll_setup
```
```
In net/core/drop_monitor.c (c000000000d0aa40)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_metadata_free
```
```
In net/core/netprio_cgroup.c (c000000000d0e6f8)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:write_priomap
```
```
In net/core/lwt_bpf.c (c000000000d101b4)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_input
```
```
In net/core/devlink.c (c000000000d295cc)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_flash_update
  - net/core/devlink.c:devlink_compat_running_version
```
```
In net/sched/sch_generic.c (c000000000d33360)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/sched/sch_api.c (c000000000d36780)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:qdisc_create
```
```
In net/netlink/af_netlink.c (c000000000d49924)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_deliver_tap
```
```
In net/netfilter/nf_queue.c (c000000000d56190)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
```
```
In net/ipv4/route.c (c000000000d5c570)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_flush_dev
```
```
In net/ipv4/ip_sockglue.c (c000000000d6d7cc)
Location: include/linux/netdevice.h:3738
Inline: True
```
```
In net/ipv4/devinet.c (c000000000db9368)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/ipv4/devinet.c:in_dev_finish_destroy
```
```
In net/ipv4/fib_semantics.c (c000000000dce6a4)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nh_common_release
```
```
In net/ipv4/ipmr.c (c000000000deca38)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
```
```
In net/xfrm/xfrm_policy.c (c000000000df9af4)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_ifdown
```
```
In net/xfrm/xfrm_state.c (c000000000e05730)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
```
```
In net/xfrm/xfrm_input.c (c000000000e0e8d4)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_device.c (c000000000e12d20)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
```
```
In net/ipv6/addrconf.c (c000000000e32830)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/route.c (c000000000e44a74)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:rt6_probe_deferred
```
```
In net/ipv6/ipv6_sockglue.c (c000000000e4db44)
Location: include/linux/netdevice.h:3738
Inline: True
```
```
In net/ipv6/ip6mr.c (c000000000e7c5b4)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:mif6_delete
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_policy.c (c000000000e7dcc0)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
```
```
In net/ipv6/addrconf_core.c (c000000000e8b430)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/ipv6/addrconf_core.c:in6_dev_finish_destroy
```
```
In net/packet/af_packet.c (c000000000e923d4)
Location: include/linux/netdevice.h:3738
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
In net/netlabel/netlabel_unlabeled.c (c000000000ea5c28)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
```
In net/switchdev/switchdev.c (c000000000eb25e8)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_deferred_process
```
```
In net/ncsi/ncsi-netlink.c (c000000000ebb9c4)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ndp_from_ifindex
```
```
In net/xdp/xsk.c (c000000000ebe3a8)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk.c:xsk_unbind_dev
```
```
In net/xdp/xdp_umem.c (c000000000ec0e80)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_clear_dev
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
In kernel/bpf/devmap.c (ffffffe0001bba5c)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:__dev_map_entry_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/devmap.c:dev_map_free
```
```
In kernel/bpf/offload.c (ffffffe0001be8ec)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_prog_offload_init
  - kernel/bpf/offload.c:bpf_prog_offload_init
```
```
In security/selinux/netif.c (ffffffe0003af878)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_sid
```
```
In security/lsm_audit.c (ffffffe0003c970a)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - security/lsm_audit.c:dump_common_audit_data
```
```
In drivers/net/tun.c (ffffffe000625832)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_show_fdinfo
  - drivers/net/tun.c:tun_peek_len
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_recvmsg
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_chr_read_iter
  - drivers/net/tun.c:tun_chr_write_iter
  - drivers/net/tun.c:tun_chr_poll
```
```
In net/core/dev.c (ffffffe000759740)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/core/dev.c:rollback_registered_many
```
```
In net/core/ethtool.c (ffffffe00076406a)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
```
```
In net/core/dst.c (ffffffe000766b32)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/core/dst.c:dst_dev_put
  - net/core/dst.c:dst_destroy
```
```
In net/core/neighbour.c (ffffffe000768556)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:pneigh_delete
  - net/core/neighbour.c:pneigh_lookup
  - net/core/neighbour.c:__neigh_ifdown
  - net/core/neighbour.c:pneigh_queue_purge
```
```
In net/core/utils.c (ffffffe000774d1c)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/core/utils.c:inet6_pton
```
```
In net/core/link_watch.c (ffffffe000774f10)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_do_dev
```
```
In net/core/net-sysfs.c (ffffffe000787ac0)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_queue_release
  - net/core/net-sysfs.c:rx_queue_release
```
```
In net/core/netpoll.c (ffffffe00078cf24)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_cleanup
  - net/core/netpoll.c:netpoll_setup
```
```
In net/core/drop_monitor.c (ffffffe000794b28)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_metadata_free
```
```
In net/core/netprio_cgroup.c (ffffffe000796fc4)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:write_priomap
```
```
In net/core/lwt_bpf.c (ffffffe000798124)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_input
```
```
In net/core/devlink.c (ffffffe0007a68d6)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_flash_update
  - net/core/devlink.c:devlink_compat_running_version
```
```
In net/sched/sch_generic.c (ffffffe0007ab2ee)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/sched/sch_api.c (ffffffe0007ad33a)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:qdisc_create
```
```
In net/netlink/af_netlink.c (ffffffe0007b8dfc)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_deliver_tap
```
```
In net/netfilter/nf_queue.c (ffffffe0007bfe7a)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
```
```
In net/ipv4/route.c (ffffffe0007c3d8e)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_flush_dev
```
```
In net/ipv4/ip_sockglue.c (ffffffe0007cee7e)
Location: include/linux/netdevice.h:3738
Inline: True
```
```
In net/ipv4/devinet.c (ffffffe000800d68)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/ipv4/devinet.c:in_dev_finish_destroy
```
```
In net/ipv4/fib_semantics.c (ffffffe00080dc74)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nh_common_release
```
```
In net/ipv4/ipmr.c (ffffffe00081dfd6)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
```
```
In net/xfrm/xfrm_policy.c (ffffffe000828f40)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_ifdown
```
```
In net/xfrm/xfrm_state.c (ffffffe0008310d2)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
```
```
In net/xfrm/xfrm_input.c (ffffffe000838974)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_device.c (ffffffe00083af68)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
```
```
In net/ipv6/addrconf.c (ffffffe0008504be)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/route.c (ffffffe00085c3b4)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:rt6_probe_deferred
```
```
In net/ipv6/ipv6_sockglue.c (ffffffe000861a8c)
Location: include/linux/netdevice.h:3738
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffe000881448)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:mif6_delete
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_policy.c (ffffffe000882020)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
```
```
In net/ipv6/addrconf_core.c (ffffffe00088ac02)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/ipv6/addrconf_core.c:in6_dev_finish_destroy
```
```
In net/packet/af_packet.c (ffffffe0008911d4)
Location: include/linux/netdevice.h:3738
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
In net/netlabel/netlabel_unlabeled.c (ffffffe00089c17a)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
```
In net/switchdev/switchdev.c (ffffffe0008a367a)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_deferred_process
```
```
In net/ncsi/ncsi-netlink.c (ffffffe0008aa222)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ndp_from_ifindex
```
```
In net/xdp/xsk.c (ffffffe0008abec2)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk.c:xsk_unbind_dev
```
```
In net/xdp/xdp_umem.c (ffffffe0008ad546)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_clear_dev
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
In kernel/sysctl_binary.c (ffffffff810a638b)
Location: include/linux/netdevice.h:3738
Inline: True
```
```
In kernel/bpf/devmap.c (ffffffff811f7ddb)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:__dev_map_entry_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/devmap.c:dev_map_free
```
```
In kernel/bpf/offload.c (ffffffff811fab8e)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_prog_offload_init
  - kernel/bpf/offload.c:bpf_prog_offload_init
```
```
In security/selinux/netif.c (ffffffff81461ff3)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_sid
```
```
In security/lsm_audit.c (ffffffff8147d452)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - security/lsm_audit.c:dump_common_audit_data
```
```
In drivers/net/tun.c (ffffffff81784e89)
Location: include/linux/netdevice.h:3738
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
In net/core/dev.c (ffffffff818cf037)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/core/dev.c:rollback_registered_many
```
```
In net/core/ethtool.c (ffffffff818ddd15)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
```
```
In net/core/dst.c (ffffffff818e0b31)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/core/dst.c:dst_dev_put
  - net/core/dst.c:dst_destroy
```
```
In net/core/neighbour.c (ffffffff818e25a9)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:pneigh_delete
  - net/core/neighbour.c:pneigh_lookup
  - net/core/neighbour.c:__neigh_ifdown
  - net/core/neighbour.c:pneigh_queue_purge
```
```
In net/core/utils.c (ffffffff818f1694)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/core/utils.c:inet6_pton
```
```
In net/core/link_watch.c (ffffffff818f1977)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_do_dev
```
```
In net/core/net-sysfs.c (ffffffff81904c40)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_queue_release
  - net/core/net-sysfs.c:rx_queue_release
```
```
In net/core/netpoll.c (ffffffff8190a5ea)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_cleanup
  - net/core/netpoll.c:netpoll_setup
```
```
In net/core/drop_monitor.c (ffffffff8191468e)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_metadata_free
```
```
In net/core/netprio_cgroup.c (ffffffff81916a20)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:write_priomap
```
```
In net/core/lwt_bpf.c (ffffffff81917a6e)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_input
```
```
In net/core/devlink.c (ffffffff81928642)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_flash_update
  - net/core/devlink.c:devlink_compat_running_version
```
```
In net/sched/sch_generic.c (ffffffff8192e626)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/sched/sch_api.c (ffffffff819301c6)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:qdisc_create
```
```
In net/netlink/af_netlink.c (ffffffff8193df0f)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_deliver_tap
```
```
In net/netfilter/nf_queue.c (ffffffff8194629d)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
```
```
In net/ipv4/route.c (ffffffff8194a4a4)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_flush_dev
```
```
In net/ipv4/ip_sockglue.c (ffffffff81956aba)
Location: include/linux/netdevice.h:3738
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff8198f492)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/ipv4/devinet.c:in_dev_finish_destroy
```
```
In net/ipv4/fib_semantics.c (ffffffff8199e168)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nh_common_release
```
```
In net/ipv4/ipmr.c (ffffffff819afa40)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
```
```
In net/xfrm/xfrm_policy.c (ffffffff819bbe6a)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_ifdown
```
```
In net/xfrm/xfrm_state.c (ffffffff819c48f7)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
```
```
In net/xfrm/xfrm_input.c (ffffffff819cb9d7)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_device.c (ffffffff819ce2c0)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
```
```
In net/ipv6/addrconf.c (ffffffff819e50f6)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/route.c (ffffffff819f26ec)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:rt6_probe_deferred
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff819f9d1e)
Location: include/linux/netdevice.h:3738
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81a1beb3)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:mif6_delete
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81a1d137)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
```
```
In net/ipv6/addrconf_core.c (ffffffff81a25ea1)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/ipv6/addrconf_core.c:in6_dev_finish_destroy
```
```
In net/packet/af_packet.c (ffffffff81a2c968)
Location: include/linux/netdevice.h:3738
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
In net/netlabel/netlabel_unlabeled.c (ffffffff81a3897e)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
```
In net/switchdev/switchdev.c (ffffffff81a410d2)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_deferred_process
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81a47d44)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ndp_from_ifindex
```
```
In net/xdp/xsk.c (ffffffff81a4a8b3)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk.c:xsk_unbind_dev
```
```
In net/xdp/xdp_umem.c (ffffffff81a4bb61)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_clear_dev
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
In kernel/sysctl_binary.c (ffffffff81094d6b)
Location: include/linux/netdevice.h:3738
Inline: True
```
```
In kernel/bpf/devmap.c (ffffffff811eab2b)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:__dev_map_entry_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/devmap.c:dev_map_free
```
```
In kernel/bpf/offload.c (ffffffff811ed8de)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_prog_offload_init
  - kernel/bpf/offload.c:bpf_prog_offload_init
```
```
In security/selinux/netif.c (ffffffff81452a23)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_sid
```
```
In security/lsm_audit.c (ffffffff8146de72)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - security/lsm_audit.c:dump_common_audit_data
```
```
In drivers/net/tun.c (ffffffff817647d9)
Location: include/linux/netdevice.h:3738
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
In net/core/dev.c (ffffffff81889157)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/core/dev.c:rollback_registered_many
```
```
In net/core/ethtool.c (ffffffff81897b55)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
```
```
In net/core/dst.c (ffffffff8189a971)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/core/dst.c:dst_dev_put
  - net/core/dst.c:dst_destroy
```
```
In net/core/neighbour.c (ffffffff8189c3e9)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:pneigh_delete
  - net/core/neighbour.c:pneigh_lookup
  - net/core/neighbour.c:__neigh_ifdown
  - net/core/neighbour.c:pneigh_queue_purge
```
```
In net/core/utils.c (ffffffff818ab4d4)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/core/utils.c:inet6_pton
```
```
In net/core/link_watch.c (ffffffff818ab7b7)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_do_dev
```
```
In net/core/net-sysfs.c (ffffffff818bea70)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_queue_release
  - net/core/net-sysfs.c:rx_queue_release
```
```
In net/core/netpoll.c (ffffffff818c449a)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_cleanup
  - net/core/netpoll.c:netpoll_setup
```
```
In net/core/drop_monitor.c (ffffffff818ce44e)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_metadata_free
```
```
In net/core/netprio_cgroup.c (ffffffff818d07d0)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:write_priomap
```
```
In net/core/lwt_bpf.c (ffffffff818d181e)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_input
```
```
In net/core/devlink.c (ffffffff818e23f2)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_flash_update
  - net/core/devlink.c:devlink_compat_running_version
```
```
In net/sched/sch_generic.c (ffffffff818e8126)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/sched/sch_api.c (ffffffff818e9cc6)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:qdisc_create
```
```
In net/netlink/af_netlink.c (ffffffff818f7a0f)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_deliver_tap
```
```
In net/netfilter/nf_queue.c (ffffffff818ffd8d)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
```
```
In net/ipv4/route.c (ffffffff81903f94)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_flush_dev
```
```
In net/ipv4/ip_sockglue.c (ffffffff819105aa)
Location: include/linux/netdevice.h:3738
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff81948f52)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/ipv4/devinet.c:in_dev_finish_destroy
```
```
In net/ipv4/fib_semantics.c (ffffffff81957c28)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nh_common_release
```
```
In net/ipv4/ipmr.c (ffffffff8196c070)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
```
```
In net/xfrm/xfrm_policy.c (ffffffff81978c5a)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_ifdown
```
```
In net/xfrm/xfrm_state.c (ffffffff819816e7)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
```
```
In net/xfrm/xfrm_input.c (ffffffff819887c7)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_device.c (ffffffff8198b0b0)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
```
```
In net/ipv6/addrconf.c (ffffffff819a1eb6)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/route.c (ffffffff819af4ac)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:rt6_probe_deferred
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff819b6ade)
Location: include/linux/netdevice.h:3738
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff819d8c73)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:mif6_delete
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_policy.c (ffffffff819d9ef7)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
```
```
In net/ipv6/addrconf_core.c (ffffffff819e2c61)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/ipv6/addrconf_core.c:in6_dev_finish_destroy
```
```
In net/packet/af_packet.c (ffffffff819e9b58)
Location: include/linux/netdevice.h:3738
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
In net/netlabel/netlabel_unlabeled.c (ffffffff819f559e)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
```
In net/switchdev/switchdev.c (ffffffff819fdcc2)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_deferred_process
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81a04934)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ndp_from_ifindex
```
```
In net/xdp/xsk.c (ffffffff81a074a3)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk.c:xsk_unbind_dev
```
```
In net/xdp/xdp_umem.c (ffffffff81a08751)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_clear_dev
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
In kernel/bpf/devmap.c (ffffffff811f5bab)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:__dev_map_entry_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/devmap.c:dev_map_free
```
```
In kernel/bpf/offload.c (ffffffff811f895e)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_prog_offload_init
  - kernel/bpf/offload.c:bpf_prog_offload_init
```
```
In security/selinux/netif.c (ffffffff8145e093)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_sid
```
```
In security/lsm_audit.c (ffffffff814794f2)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - security/lsm_audit.c:dump_common_audit_data
```
```
In drivers/net/tun.c (ffffffff817b5239)
Location: include/linux/netdevice.h:3738
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
In net/core/dev.c (ffffffff81920037)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/core/dev.c:rollback_registered_many
```
```
In net/core/ethtool.c (ffffffff8192ed45)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
```
```
In net/core/dst.c (ffffffff81931b61)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/core/dst.c:dst_dev_put
  - net/core/dst.c:dst_destroy
```
```
In net/core/neighbour.c (ffffffff819335d9)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:pneigh_delete
  - net/core/neighbour.c:pneigh_lookup
  - net/core/neighbour.c:__neigh_ifdown
  - net/core/neighbour.c:pneigh_queue_purge
```
```
In net/core/utils.c (ffffffff819426c4)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/core/utils.c:inet6_pton
```
```
In net/core/link_watch.c (ffffffff819429a7)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_do_dev
```
```
In net/core/net-sysfs.c (ffffffff81955c70)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_queue_release
  - net/core/net-sysfs.c:rx_queue_release
```
```
In net/core/netpoll.c (ffffffff8195b61a)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_cleanup
  - net/core/netpoll.c:netpoll_setup
```
```
In net/core/drop_monitor.c (ffffffff819656be)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_metadata_free
```
```
In net/core/netprio_cgroup.c (ffffffff81967bb0)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:write_priomap
```
```
In net/core/lwt_bpf.c (ffffffff81968bfe)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_input
```
```
In net/core/devlink.c (ffffffff819797d2)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_flash_update
  - net/core/devlink.c:devlink_compat_running_version
```
```
In net/sched/sch_generic.c (ffffffff8197f7b6)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/sched/sch_api.c (ffffffff81981356)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:qdisc_create
```
```
In net/netlink/af_netlink.c (ffffffff8198f09f)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_deliver_tap
```
```
In net/netfilter/nf_queue.c (ffffffff8199742d)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
```
```
In net/ipv4/route.c (ffffffff819b4c74)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_flush_dev
```
```
In net/ipv4/ip_sockglue.c (ffffffff819c128a)
Location: include/linux/netdevice.h:3738
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff819f9d32)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/ipv4/devinet.c:in_dev_finish_destroy
```
```
In net/ipv4/fib_semantics.c (ffffffff81a08a08)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nh_common_release
```
```
In net/ipv4/ipmr.c (ffffffff81a1a2e0)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a268ea)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_ifdown
```
```
In net/xfrm/xfrm_state.c (ffffffff81a2f377)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
```
```
In net/xfrm/xfrm_input.c (ffffffff81a36457)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_device.c (ffffffff81a38d40)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
```
```
In net/ipv6/addrconf.c (ffffffff81a4fb76)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/route.c (ffffffff81a5d16c)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:rt6_probe_deferred
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81a6479e)
Location: include/linux/netdevice.h:3738
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81a86933)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:mif6_delete
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81a87bb7)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
```
```
In net/ipv6/addrconf_core.c (ffffffff81a91a51)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/ipv6/addrconf_core.c:in6_dev_finish_destroy
```
```
In net/packet/af_packet.c (ffffffff81a98518)
Location: include/linux/netdevice.h:3738
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
In net/netlabel/netlabel_unlabeled.c (ffffffff81aa482e)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
```
In net/switchdev/switchdev.c (ffffffff81aacf82)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_deferred_process
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81ab3bf4)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ndp_from_ifindex
```
```
In net/xdp/xsk.c (ffffffff81ab6763)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk.c:xsk_unbind_dev
```
```
In net/xdp/xdp_umem.c (ffffffff81ab7a11)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_clear_dev
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
In kernel/bpf/devmap.c (ffffffff812042d5)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:__dev_map_entry_free
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/devmap.c:dev_map_free
```
```
In kernel/bpf/offload.c (ffffffff81207250)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_prog_offload_init
  - kernel/bpf/offload.c:bpf_prog_offload_init
```
```
In security/selinux/netif.c (ffffffff8147584a)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_sid
```
```
In security/lsm_audit.c (ffffffff81490fa2)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - security/lsm_audit.c:dump_common_audit_data
```
```
In drivers/net/tun.c (ffffffff817cf1ff)
Location: include/linux/netdevice.h:3738
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
In net/core/dev.c (ffffffff81941d97)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/core/dev.c:rollback_registered_many
```
```
In net/core/ethtool.c (ffffffff81950415)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
```
```
In net/core/dst.c (ffffffff81953231)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/core/dst.c:dst_dev_put
  - net/core/dst.c:dst_destroy
```
```
In net/core/neighbour.c (ffffffff81954f09)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:neigh_proxy_process
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:pneigh_delete
  - net/core/neighbour.c:pneigh_lookup
  - net/core/neighbour.c:__neigh_ifdown
  - net/core/neighbour.c:pneigh_queue_purge
```
```
In net/core/utils.c (ffffffff81963fc4)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/core/utils.c:inet6_pton
```
```
In net/core/link_watch.c (ffffffff819642a7)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_do_dev
```
```
In net/core/net-sysfs.c (ffffffff81977e60)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_queue_release
  - net/core/net-sysfs.c:rx_queue_release
```
```
In net/core/netpoll.c (ffffffff8197d83a)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_cleanup
  - net/core/netpoll.c:netpoll_setup
```
```
In net/core/drop_monitor.c (ffffffff819878fe)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_metadata_free
```
```
In net/core/netprio_cgroup.c (ffffffff81989ef0)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:write_priomap
```
```
In net/core/lwt_bpf.c (ffffffff8198afde)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_input
```
```
In net/core/devlink.c (ffffffff8199bcc2)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_compat_flash_update
  - net/core/devlink.c:devlink_compat_running_version
```
```
In net/sched/sch_generic.c (ffffffff819a1d14)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_deactivate_many
  - net/sched/sch_generic.c:qdisc_destroy
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/sched/sch_api.c (ffffffff819a38d6)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:qdisc_create
```
```
In net/netlink/af_netlink.c (ffffffff819b1987)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_deliver_tap
```
```
In net/netfilter/nf_queue.c (ffffffff819ba10d)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
```
```
In net/ipv4/route.c (ffffffff819be3b4)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_flush_dev
```
```
In net/ipv4/ip_sockglue.c (ffffffff819cac77)
Location: include/linux/netdevice.h:3738
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff81a04022)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/ipv4/devinet.c:in_dev_finish_destroy
```
```
In net/ipv4/fib_semantics.c (ffffffff81a13168)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nh_common_release
```
```
In net/ipv4/ipmr.c (ffffffff81a25110)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_add
  - net/ipv4/ipmr.c:vif_delete
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a31d9a)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_ifdown
```
```
In net/xfrm/xfrm_state.c (ffffffff81a3acc7)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
```
```
In net/xfrm/xfrm_input.c (ffffffff81a41da0)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_device.c (ffffffff81a44760)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
```
```
In net/ipv6/addrconf.c (ffffffff81a5bb56)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/route.c (ffffffff81a69555)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:rt6_probe_deferred
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81a70ccd)
Location: include/linux/netdevice.h:3738
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81a934f3)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:mif6_delete
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81a947ed)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_fill_dst
```
```
In net/ipv6/addrconf_core.c (ffffffff81a9db01)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/ipv6/addrconf_core.c:in6_dev_finish_destroy
```
```
In net/packet/af_packet.c (ffffffff81aa1b0f)
Location: include/linux/netdevice.h:3738
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
In net/netlabel/netlabel_unlabeled.c (ffffffff81ab0bd3)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
```
In net/switchdev/switchdev.c (ffffffff81ab92f2)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_deferred_process
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81abff94)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ndp_from_ifindex
```
```
In net/xdp/xsk.c (ffffffff81ac27c3)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk.c:xsk_unbind_dev
```
```
In net/xdp/xdp_umem.c (ffffffff81ac3e31)
Location: include/linux/netdevice.h:3738
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_clear_dev
```
</details>
</li>
</ul>

## Differences
