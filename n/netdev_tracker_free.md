# Function: <code>netdev_tracker_free</code>

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
In kernel/bpf/devmap.c (0)
Location: include/linux/netdevice.h:3990
Inline: True
```
```
In kernel/bpf/offload.c (0)
Location: include/linux/netdevice.h:3990
Inline: True
```
```
In security/selinux/netif.c (0)
Location: include/linux/netdevice.h:3990
Inline: True
```
```
In security/lsm_audit.c (0)
Location: include/linux/netdevice.h:3990
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/netdevice.h:3990
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/netdevice.h:3990
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/netdevice.h:3990
Inline: True
```
```
In net/core/dst.c (0)
Location: include/linux/netdevice.h:3990
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/netdevice.h:3990
Inline: True
```
```
In net/core/utils.c (0)
Location: include/linux/netdevice.h:3990
Inline: True
```
```
In net/core/link_watch.c (0)
Location: include/linux/netdevice.h:3990
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/netdevice.h:3990
Inline: True
```
```
In net/core/dev_ioctl.c (0)
Location: include/linux/netdevice.h:3990
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/netdevice.h:3990
Inline: True
```
```
In net/core/netpoll.c (0)
Location: include/linux/netdevice.h:3990
Inline: True
```
```
In net/core/drop_monitor.c (0)
Location: include/linux/netdevice.h:3990
Inline: True
```
```
In net/core/netprio_cgroup.c (0)
Location: include/linux/netdevice.h:3990
Inline: True
```
```
In net/core/lwt_bpf.c (0)
Location: include/linux/netdevice.h:3990
Inline: True
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/netdevice.h:3990
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/linux/netdevice.h:3990
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/netdevice.h:3990
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/linux/netdevice.h:3990
Inline: True
```
```
In net/ethtool/ioctl.c (0)
Location: include/linux/netdevice.h:3990
Inline: True
```
```
In net/ethtool/netlink.c (0)
Location: include/linux/netdevice.h:3990
Inline: True
```
```
In net/ethtool/linkinfo.c (0)
Location: include/linux/netdevice.h:3990
Inline: True
```
```
In net/ethtool/linkmodes.c (0)
Location: include/linux/netdevice.h:3990
Inline: True
```
```
In net/ethtool/debug.c (0)
Location: include/linux/netdevice.h:3990
Inline: True
```
```
In net/ethtool/wol.c (0)
Location: include/linux/netdevice.h:3990
Inline: True
```
```
In net/ethtool/features.c (0)
Location: include/linux/netdevice.h:3990
Inline: True
```
```
In net/ethtool/privflags.c (0)
Location: include/linux/netdevice.h:3990
Inline: True
```
```
In net/ethtool/rings.c (0)
Location: include/linux/netdevice.h:3990
Inline: True
```
```
In net/ethtool/channels.c (0)
Location: include/linux/netdevice.h:3990
Inline: True
```
```
In net/ethtool/coalesce.c (0)
Location: include/linux/netdevice.h:3990
Inline: True
```
```
In net/ethtool/pause.c (0)
Location: include/linux/netdevice.h:3990
Inline: True
```
```
In net/ethtool/eee.c (0)
Location: include/linux/netdevice.h:3990
Inline: True
```
```
In net/ethtool/cabletest.c (0)
Location: include/linux/netdevice.h:3990
Inline: True
```
```
In net/ethtool/tunnels.c (0)
Location: include/linux/netdevice.h:3990
Inline: True
```
```
In net/ethtool/fec.c (0)
Location: include/linux/netdevice.h:3990
Inline: True
```
```
In net/ethtool/module.c (0)
Location: include/linux/netdevice.h:3990
Inline: True
```
```
In net/netfilter/nf_queue.c (0)
Location: include/linux/netdevice.h:3990
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/netdevice.h:3990
Inline: True
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/netdevice.h:3990
Inline: True
```
```
In net/ipv4/icmp.c (0)
Location: include/linux/netdevice.h:3990
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/linux/netdevice.h:3990
Inline: True
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/linux/netdevice.h:3990
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/netdevice.h:3990
Inline: True
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/netdevice.h:3990
Inline: True
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/linux/netdevice.h:3990
Inline: True
```
```
In net/xfrm/xfrm_input.c (0)
Location: include/linux/netdevice.h:3990
Inline: True
```
```
In net/xfrm/xfrm_device.c (0)
Location: include/linux/netdevice.h:3990
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/netdevice.h:3990
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/netdevice.h:3990
Inline: True
```
```
In net/ipv6/ipv6_sockglue.c (0)
Location: include/linux/netdevice.h:3990
Inline: True
```
```
In net/ipv6/icmp.c (0)
Location: include/linux/netdevice.h:3990
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/netdevice.h:3990
Inline: True
```
```
In net/ipv6/xfrm6_policy.c (0)
Location: include/linux/netdevice.h:3990
Inline: True
```
```
In net/ipv6/addrconf_core.c (0)
Location: include/linux/netdevice.h:3990
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/netdevice.h:3990
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/linux/netdevice.h:3990
Inline: True
```
```
In net/switchdev/switchdev.c (0)
Location: include/linux/netdevice.h:3990
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/linux/netdevice.h:3990
Inline: True
```
```
In net/xdp/xsk.c (0)
Location: include/linux/netdevice.h:3990
Inline: True
```
```
In net/xdp/xsk_buff_pool.c (0)
Location: include/linux/netdevice.h:3990
Inline: True
```
```
In net/mctp/device.c (0)
Location: include/linux/netdevice.h:3990
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
In kernel/bpf/devmap.c (0)
Location: include/linux/netdevice.h:4034
Inline: True
```
```
In kernel/bpf/offload.c (0)
Location: include/linux/netdevice.h:4034
Inline: True
```
```
In security/selinux/netif.c (0)
Location: include/linux/netdevice.h:4034
Inline: True
```
```
In security/lsm_audit.c (0)
Location: include/linux/netdevice.h:4034
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/netdevice.h:4034
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/netdevice.h:4034
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/netdevice.h:4034
Inline: True
```
```
In net/core/dst.c (0)
Location: include/linux/netdevice.h:4034
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/netdevice.h:4034
Inline: True
```
```
In net/core/utils.c (0)
Location: include/linux/netdevice.h:4034
Inline: True
```
```
In net/core/link_watch.c (0)
Location: include/linux/netdevice.h:4034
Inline: True
```
```
In net/core/dev_ioctl.c (0)
Location: include/linux/netdevice.h:4034
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/netdevice.h:4034
Inline: True
```
```
In net/core/netpoll.c (0)
Location: include/linux/netdevice.h:4034
Inline: True
```
```
In net/core/drop_monitor.c (0)
Location: include/linux/netdevice.h:4034
Inline: True
```
```
In net/core/netprio_cgroup.c (0)
Location: include/linux/netdevice.h:4034
Inline: True
```
```
In net/core/lwt_bpf.c (0)
Location: include/linux/netdevice.h:4034
Inline: True
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/netdevice.h:4034
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/linux/netdevice.h:4034
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/netdevice.h:4034
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/linux/netdevice.h:4034
Inline: True
```
```
In net/ethtool/ioctl.c (0)
Location: include/linux/netdevice.h:4034
Inline: True
```
```
In net/ethtool/netlink.c (0)
Location: include/linux/netdevice.h:4034
Inline: True
```
```
In net/ethtool/linkinfo.c (0)
Location: include/linux/netdevice.h:4034
Inline: True
```
```
In net/ethtool/linkmodes.c (0)
Location: include/linux/netdevice.h:4034
Inline: True
```
```
In net/ethtool/debug.c (0)
Location: include/linux/netdevice.h:4034
Inline: True
```
```
In net/ethtool/wol.c (0)
Location: include/linux/netdevice.h:4034
Inline: True
```
```
In net/ethtool/features.c (0)
Location: include/linux/netdevice.h:4034
Inline: True
```
```
In net/ethtool/privflags.c (0)
Location: include/linux/netdevice.h:4034
Inline: True
```
```
In net/ethtool/rings.c (0)
Location: include/linux/netdevice.h:4034
Inline: True
```
```
In net/ethtool/channels.c (0)
Location: include/linux/netdevice.h:4034
Inline: True
```
```
In net/ethtool/coalesce.c (0)
Location: include/linux/netdevice.h:4034
Inline: True
```
```
In net/ethtool/pause.c (0)
Location: include/linux/netdevice.h:4034
Inline: True
```
```
In net/ethtool/eee.c (0)
Location: include/linux/netdevice.h:4034
Inline: True
```
```
In net/ethtool/cabletest.c (0)
Location: include/linux/netdevice.h:4034
Inline: True
```
```
In net/ethtool/tunnels.c (0)
Location: include/linux/netdevice.h:4034
Inline: True
```
```
In net/ethtool/fec.c (0)
Location: include/linux/netdevice.h:4034
Inline: True
```
```
In net/ethtool/module.c (0)
Location: include/linux/netdevice.h:4034
Inline: True
```
```
In net/ethtool/pse-pd.c (0)
Location: include/linux/netdevice.h:4034
Inline: True
```
```
In net/netfilter/nf_queue.c (0)
Location: include/linux/netdevice.h:4034
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/netdevice.h:4034
Inline: True
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/netdevice.h:4034
Inline: True
```
```
In net/ipv4/icmp.c (0)
Location: include/linux/netdevice.h:4034
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/linux/netdevice.h:4034
Inline: True
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/linux/netdevice.h:4034
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/netdevice.h:4034
Inline: True
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/netdevice.h:4034
Inline: True
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/linux/netdevice.h:4034
Inline: True
```
```
In net/xfrm/xfrm_input.c (0)
Location: include/linux/netdevice.h:4034
Inline: True
```
```
In net/xfrm/xfrm_device.c (0)
Location: include/linux/netdevice.h:4034
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/netdevice.h:4034
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/netdevice.h:4034
Inline: True
```
```
In net/ipv6/ipv6_sockglue.c (0)
Location: include/linux/netdevice.h:4034
Inline: True
```
```
In net/ipv6/icmp.c (0)
Location: include/linux/netdevice.h:4034
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/netdevice.h:4034
Inline: True
```
```
In net/ipv6/xfrm6_policy.c (0)
Location: include/linux/netdevice.h:4034
Inline: True
```
```
In net/ipv6/addrconf_core.c (0)
Location: include/linux/netdevice.h:4034
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/netdevice.h:4034
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/linux/netdevice.h:4034
Inline: True
```
```
In net/switchdev/switchdev.c (0)
Location: include/linux/netdevice.h:4034
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/linux/netdevice.h:4034
Inline: True
```
```
In net/xdp/xsk.c (0)
Location: include/linux/netdevice.h:4034
Inline: True
```
```
In net/xdp/xsk_buff_pool.c (0)
Location: include/linux/netdevice.h:4034
Inline: True
```
```
In net/mctp/device.c (0)
Location: include/linux/netdevice.h:4034
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
In kernel/bpf/devmap.c (0)
Location: include/linux/netdevice.h:4093
Inline: True
```
```
In kernel/bpf/offload.c (0)
Location: include/linux/netdevice.h:4093
Inline: True
```
```
In security/selinux/netif.c (0)
Location: include/linux/netdevice.h:4093
Inline: True
```
```
In security/lsm_audit.c (0)
Location: include/linux/netdevice.h:4093
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/netdevice.h:4093
Inline: True
```
```
In drivers/net/net_failover.c (0)
Location: include/linux/netdevice.h:4093
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/netdevice.h:4093
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/netdevice.h:4093
Inline: True
```
```
In net/core/dst.c (0)
Location: include/linux/netdevice.h:4093
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/netdevice.h:4093
Inline: True
```
```
In net/core/utils.c (0)
Location: include/linux/netdevice.h:4093
Inline: True
```
```
In net/core/link_watch.c (0)
Location: include/linux/netdevice.h:4093
Inline: True
```
```
In net/core/dev_ioctl.c (0)
Location: include/linux/netdevice.h:4093
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/netdevice.h:4093
Inline: True
```
```
In net/core/netpoll.c (0)
Location: include/linux/netdevice.h:4093
Inline: True
```
```
In net/core/drop_monitor.c (0)
Location: include/linux/netdevice.h:4093
Inline: True
```
```
In net/core/netprio_cgroup.c (0)
Location: include/linux/netdevice.h:4093
Inline: True
```
```
In net/core/lwt_bpf.c (0)
Location: include/linux/netdevice.h:4093
Inline: True
```
```
In net/core/failover.c (0)
Location: include/linux/netdevice.h:4093
Inline: True
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/netdevice.h:4093
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/linux/netdevice.h:4093
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/netdevice.h:4093
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/linux/netdevice.h:4093
Inline: True
```
```
In net/ethtool/ioctl.c (0)
Location: include/linux/netdevice.h:4093
Inline: True
```
```
In net/ethtool/netlink.c (0)
Location: include/linux/netdevice.h:4093
Inline: True
```
```
In net/ethtool/features.c (0)
Location: include/linux/netdevice.h:4093
Inline: True
```
```
In net/ethtool/cabletest.c (0)
Location: include/linux/netdevice.h:4093
Inline: True
```
```
In net/ethtool/tunnels.c (0)
Location: include/linux/netdevice.h:4093
Inline: True
```
```
In net/netfilter/nf_queue.c (0)
Location: include/linux/netdevice.h:4093
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/netdevice.h:4093
Inline: True
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/netdevice.h:4093
Inline: True
```
```
In net/ipv4/icmp.c (0)
Location: include/linux/netdevice.h:4093
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/linux/netdevice.h:4093
Inline: True
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/linux/netdevice.h:4093
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/netdevice.h:4093
Inline: True
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/netdevice.h:4093
Inline: True
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/linux/netdevice.h:4093
Inline: True
```
```
In net/xfrm/xfrm_input.c (0)
Location: include/linux/netdevice.h:4093
Inline: True
```
```
In net/xfrm/xfrm_device.c (0)
Location: include/linux/netdevice.h:4093
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/netdevice.h:4093
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/netdevice.h:4093
Inline: True
```
```
In net/ipv6/ipv6_sockglue.c (0)
Location: include/linux/netdevice.h:4093
Inline: True
```
```
In net/ipv6/icmp.c (0)
Location: include/linux/netdevice.h:4093
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/netdevice.h:4093
Inline: True
```
```
In net/ipv6/xfrm6_policy.c (0)
Location: include/linux/netdevice.h:4093
Inline: True
```
```
In net/ipv6/addrconf_core.c (0)
Location: include/linux/netdevice.h:4093
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/netdevice.h:4093
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/linux/netdevice.h:4093
Inline: True
```
```
In net/switchdev/switchdev.c (0)
Location: include/linux/netdevice.h:4093
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/linux/netdevice.h:4093
Inline: True
```
```
In net/xdp/xsk.c (0)
Location: include/linux/netdevice.h:4093
Inline: True
```
```
In net/xdp/xsk_buff_pool.c (0)
Location: include/linux/netdevice.h:4093
Inline: True
```
```
In net/mctp/device.c (0)
Location: include/linux/netdevice.h:4093
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
In kernel/bpf/devmap.c (0)
Location: include/linux/netdevice.h:4160
Inline: True
```
```
In kernel/bpf/offload.c (0)
Location: include/linux/netdevice.h:4160
Inline: True
```
```
In security/selinux/netif.c (0)
Location: include/linux/netdevice.h:4160
Inline: True
```
```
In security/lsm_audit.c (0)
Location: include/linux/netdevice.h:4160
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/netdevice.h:4160
Inline: True
```
```
In drivers/net/net_failover.c (0)
Location: include/linux/netdevice.h:4160
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/netdevice.h:4160
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/netdevice.h:4160
Inline: True
```
```
In net/core/dst.c (0)
Location: include/linux/netdevice.h:4160
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/netdevice.h:4160
Inline: True
```
```
In net/core/utils.c (0)
Location: include/linux/netdevice.h:4160
Inline: True
```
```
In net/core/link_watch.c (0)
Location: include/linux/netdevice.h:4160
Inline: True
```
```
In net/core/dev_ioctl.c (0)
Location: include/linux/netdevice.h:4160
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/netdevice.h:4160
Inline: True
```
```
In net/core/netpoll.c (0)
Location: include/linux/netdevice.h:4160
Inline: True
```
```
In net/core/drop_monitor.c (0)
Location: include/linux/netdevice.h:4160
Inline: True
```
```
In net/core/netprio_cgroup.c (0)
Location: include/linux/netdevice.h:4160
Inline: True
```
```
In net/core/lwt_bpf.c (0)
Location: include/linux/netdevice.h:4160
Inline: True
```
```
In net/core/failover.c (0)
Location: include/linux/netdevice.h:4160
Inline: True
```
```
In net/sched/sch_generic.c (0)
Location: include/linux/netdevice.h:4160
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/linux/netdevice.h:4160
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/netdevice.h:4160
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/linux/netdevice.h:4160
Inline: True
```
```
In net/ethtool/ioctl.c (0)
Location: include/linux/netdevice.h:4160
Inline: True
```
```
In net/ethtool/netlink.c (0)
Location: include/linux/netdevice.h:4160
Inline: True
```
```
In net/ethtool/features.c (0)
Location: include/linux/netdevice.h:4160
Inline: True
```
```
In net/ethtool/cabletest.c (0)
Location: include/linux/netdevice.h:4160
Inline: True
```
```
In net/ethtool/tunnels.c (0)
Location: include/linux/netdevice.h:4160
Inline: True
```
```
In net/netfilter/nf_queue.c (0)
Location: include/linux/netdevice.h:4160
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/netdevice.h:4160
Inline: True
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/netdevice.h:4160
Inline: True
```
```
In net/ipv4/icmp.c (0)
Location: include/linux/netdevice.h:4160
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/linux/netdevice.h:4160
Inline: True
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/linux/netdevice.h:4160
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/netdevice.h:4160
Inline: True
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/netdevice.h:4160
Inline: True
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/linux/netdevice.h:4160
Inline: True
```
```
In net/xfrm/xfrm_input.c (0)
Location: include/linux/netdevice.h:4160
Inline: True
```
```
In net/xfrm/xfrm_device.c (0)
Location: include/linux/netdevice.h:4160
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/netdevice.h:4160
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/netdevice.h:4160
Inline: True
```
```
In net/ipv6/ipv6_sockglue.c (0)
Location: include/linux/netdevice.h:4160
Inline: True
```
```
In net/ipv6/icmp.c (0)
Location: include/linux/netdevice.h:4160
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/netdevice.h:4160
Inline: True
```
```
In net/ipv6/xfrm6_policy.c (0)
Location: include/linux/netdevice.h:4160
Inline: True
```
```
In net/ipv6/addrconf_core.c (0)
Location: include/linux/netdevice.h:4160
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/netdevice.h:4160
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/linux/netdevice.h:4160
Inline: True
```
```
In net/switchdev/switchdev.c (0)
Location: include/linux/netdevice.h:4160
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (0)
Location: include/linux/netdevice.h:4160
Inline: True
```
```
In net/xdp/xsk.c (0)
Location: include/linux/netdevice.h:4160
Inline: True
```
```
In net/xdp/xsk_buff_pool.c (0)
Location: include/linux/netdevice.h:4160
Inline: True
```
```
In net/mctp/device.c (0)
Location: include/linux/netdevice.h:4160
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
