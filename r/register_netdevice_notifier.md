# Function: <code>register_netdevice_notifier</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int register_netdevice_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81714d30)
Location: net/core/dev.c:1531
Inline: False
Direct callers:
  - net/core/dst.c:dst_subsys_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/fib_rules.c:fib_rules_init
  - net/core/netprio_cgroup.c:init_cgroup_netprio
  - net/ipv4/arp.c:arp_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/igmp.c:igmp_mc_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ndisc.c:ndisc_late_init
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_init
```
**Symbols:**

```
ffffffff81714d30-ffffffff81714f0c: register_netdevice_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int register_netdevice_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8177cd30)
Location: net/core/dev.c:1535
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_init
  - net/core/dst.c:dst_subsys_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/fib_rules.c:fib_rules_init
  - net/core/netprio_cgroup.c:init_cgroup_netprio
  - net/ipv4/arp.c:arp_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/igmp.c:igmp_mc_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ndisc.c:ndisc_late_init
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_init
```
**Symbols:**

```
ffffffff8177cd30-ffffffff8177cf0c: register_netdevice_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int register_netdevice_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817aa370)
Location: net/core/dev.c:1534
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_init
  - net/core/dst.c:dst_subsys_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/fib_rules.c:fib_rules_init
  - net/core/netprio_cgroup.c:init_cgroup_netprio
  - net/ipv4/arp.c:arp_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/igmp.c:igmp_mc_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ndisc.c:ndisc_late_init
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_init
```
**Symbols:**

```
ffffffff817aa370-ffffffff817aa54c: register_netdevice_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int register_netdevice_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817c89d0)
Location: net/core/dev.c:1568
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/fib_rules.c:fib_rules_init
  - net/core/netprio_cgroup.c:init_cgroup_netprio
  - net/ipv4/arp.c:arp_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/igmp.c:igmp_mc_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/xfrm/xfrm_device.c:xfrm_dev_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ndisc.c:ndisc_late_init
  - net/ipv6/mcast.c:igmp6_late_init
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_init
```
**Symbols:**

```
ffffffff817c89d0-ffffffff817c8ba7: register_netdevice_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int register_netdevice_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81842610)
Location: net/core/dev.c:1583
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_init
  - kernel/bpf/offload.c:bpf_offload_init
  - drivers/net/tun.c:tun_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/fib_rules.c:fib_rules_init
  - net/core/netprio_cgroup.c:init_cgroup_netprio
  - net/ipv4/arp.c:arp_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/igmp.c:igmp_mc_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/xfrm/xfrm_device.c:xfrm_dev_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ndisc.c:ndisc_late_init
  - net/ipv6/mcast.c:igmp6_late_init
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_init
```
**Symbols:**

```
ffffffff81842610-ffffffff8184282b: register_netdevice_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int register_netdevice_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8188ca20)
Location: net/core/dev.c:1622
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_init
  - kernel/bpf/offload.c:bpf_offload_init
  - security/selinux/netif.c:sel_netif_init
  - drivers/net/tun.c:tun_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/fib_rules.c:fib_rules_init
  - net/core/netprio_cgroup.c:init_cgroup_netprio
  - net/ipv4/arp.c:arp_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/igmp.c:igmp_mc_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/xfrm/xfrm_device.c:xfrm_dev_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ndisc.c:ndisc_late_init
  - net/ipv6/mcast.c:igmp6_late_init
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/packet/af_packet.c:packet_init
  - net/wireless/wext-core.c:wireless_nlevent_init
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_init
```
**Symbols:**

```
ffffffff8188ca20-ffffffff8188cc4d: register_netdevice_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int register_netdevice_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818adc70)
Location: net/core/dev.c:1626
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_init
  - security/selinux/netif.c:sel_netif_init
  - drivers/net/tun.c:tun_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/fib_rules.c:fib_rules_init
  - net/core/netprio_cgroup.c:init_cgroup_netprio
  - net/ipv4/arp.c:arp_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/igmp.c:igmp_mc_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/xfrm/xfrm_device.c:xfrm_dev_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ndisc.c:ndisc_late_init
  - net/ipv6/mcast.c:igmp6_late_init
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/packet/af_packet.c:packet_init
  - net/wireless/wext-core.c:wireless_nlevent_init
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_init
```
**Symbols:**

```
ffffffff818adc70-ffffffff818ade9d: register_netdevice_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int register_netdevice_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818f9590)
Location: net/core/dev.c:1636
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_init
  - security/selinux/netif.c:sel_netif_init
  - drivers/net/tun.c:tun_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/fib_rules.c:fib_rules_init
  - net/core/netprio_cgroup.c:init_cgroup_netprio
  - net/ipv4/arp.c:arp_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/igmp.c:igmp_mc_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/xfrm/xfrm_device.c:xfrm_dev_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ndisc.c:ndisc_late_init
  - net/ipv6/mcast.c:igmp6_late_init
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/packet/af_packet.c:packet_init
  - net/wireless/wext-core.c:wireless_nlevent_init
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_init
  - net/xdp/xsk.c:xsk_init
```
**Symbols:**

```
ffffffff818f9590-ffffffff818f97cc: register_netdevice_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int register_netdevice_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8192b6f0)
Location: net/core/dev.c:1554
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_init
  - security/selinux/netif.c:sel_netif_init
  - drivers/net/tun.c:tun_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/fib_rules.c:fib_rules_init
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/core/netprio_cgroup.c:init_cgroup_netprio
  - net/ipv4/arp.c:arp_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/igmp.c:igmp_mc_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/xfrm/xfrm_device.c:xfrm_dev_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ndisc.c:ndisc_late_init
  - net/ipv6/mcast.c:igmp6_late_init
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/packet/af_packet.c:packet_init
  - net/wireless/wext-core.c:wireless_nlevent_init
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_init
  - net/xdp/xsk.c:xsk_init
```
**Symbols:**

```
ffffffff8192b6f0-ffffffff8192b92c: register_netdevice_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int register_netdevice_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a01350)
Location: net/core/dev.c:1802
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_init
  - security/selinux/netif.c:sel_netif_init
  - drivers/net/tun.c:tun_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/fib_rules.c:fib_rules_init
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/core/netprio_cgroup.c:init_cgroup_netprio
  - net/ethtool/netlink.c:ethnl_init
  - net/ipv4/arp.c:arp_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/igmp.c:igmp_mc_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/xfrm/xfrm_device.c:xfrm_dev_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ndisc.c:ndisc_late_init
  - net/ipv6/mcast.c:igmp6_late_init
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/packet/af_packet.c:packet_init
  - net/wireless/wext-core.c:wireless_nlevent_init
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_init
  - net/xdp/xsk.c:xsk_init
```
**Symbols:**

```
ffffffff81a01350-ffffffff81a01458: register_netdevice_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int register_netdevice_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a01680)
Location: net/core/dev.c:1827
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_init
  - security/selinux/netif.c:sel_netif_init
  - drivers/net/tun.c:tun_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/fib_rules.c:fib_rules_init
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/core/netprio_cgroup.c:init_cgroup_netprio
  - net/ethtool/netlink.c:ethnl_init
  - net/ipv4/arp.c:arp_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/igmp.c:igmp_mc_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/xfrm/xfrm_device.c:xfrm_dev_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ndisc.c:ndisc_late_init
  - net/ipv6/mcast.c:igmp6_late_init
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/packet/af_packet.c:packet_init
  - net/wireless/wext-core.c:wireless_nlevent_init
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_init
  - net/xdp/xsk.c:xsk_init
```
**Symbols:**

```
ffffffff81a01680-ffffffff81a01788: register_netdevice_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int register_netdevice_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819e8130)
Location: net/core/dev.c:1896
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_init
  - security/selinux/netif.c:sel_netif_init
  - drivers/net/tun.c:tun_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/fib_rules.c:fib_rules_init
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/core/netprio_cgroup.c:init_cgroup_netprio
  - net/ethtool/netlink.c:ethnl_init
  - net/ipv4/arp.c:arp_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/igmp.c:igmp_mc_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/xfrm/xfrm_device.c:xfrm_dev_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ndisc.c:ndisc_late_init
  - net/ipv6/mcast.c:igmp6_late_init
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/packet/af_packet.c:packet_init
  - net/wireless/wext-core.c:wireless_nlevent_init
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_init
  - net/xdp/xsk.c:xsk_init
```
**Symbols:**

```
ffffffff819e8130-ffffffff819e8238: register_netdevice_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int register_netdevice_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a99130)
Location: net/core/dev.c:1771
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_init
  - security/selinux/netif.c:sel_netif_init
  - drivers/net/tun.c:tun_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/fib_rules.c:fib_rules_init
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/core/netprio_cgroup.c:init_cgroup_netprio
  - net/ethtool/netlink.c:ethnl_init
  - net/ipv4/arp.c:arp_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/igmp.c:igmp_mc_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/xfrm/xfrm_device.c:xfrm_dev_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ndisc.c:ndisc_late_init
  - net/ipv6/mcast.c:igmp6_late_init
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/packet/af_packet.c:packet_init
  - net/wireless/wext-core.c:wireless_nlevent_init
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_init
  - net/dcb/dcbnl.c:dcbnl_init
  - net/xdp/xsk.c:xsk_init
```
**Symbols:**

```
ffffffff81a99130-ffffffff81a99238: register_netdevice_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int register_netdevice_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c10ce0)
Location: net/core/dev.c:1720
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_init
  - security/selinux/netif.c:sel_netif_init
  - drivers/net/tun.c:tun_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/fib_rules.c:fib_rules_init
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/core/netprio_cgroup.c:init_cgroup_netprio
  - net/ethtool/netlink.c:ethnl_init
  - net/ipv4/arp.c:arp_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/igmp.c:igmp_mc_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/xfrm/xfrm_device.c:xfrm_dev_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ndisc.c:ndisc_late_init
  - net/ipv6/mcast.c:igmp6_late_init
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/packet/af_packet.c:packet_init
  - net/wireless/wext-core.c:wireless_nlevent_init
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_init
  - net/dcb/dcbnl.c:dcbnl_init
  - net/xdp/xsk.c:xsk_init
  - net/mctp/device.c:mctp_device_init
```
**Symbols:**

```
ffffffff81c10ce0-ffffffff81c10df0: register_netdevice_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int register_netdevice_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dc0b10)
Location: net/core/dev.c:1705
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_init
  - security/selinux/netif.c:sel_netif_init
  - drivers/net/tun.c:tun_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/fib_rules.c:fib_rules_init
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/core/netprio_cgroup.c:init_cgroup_netprio
  - net/core/devlink.c:devlink_alloc_ns
  - net/ethtool/netlink.c:ethnl_init
  - net/ipv4/arp.c:arp_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/igmp.c:igmp_mc_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/xfrm/xfrm_device.c:xfrm_dev_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ndisc.c:ndisc_late_init
  - net/ipv6/mcast.c:igmp6_late_init
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/packet/af_packet.c:packet_init
  - net/wireless/wext-core.c:wireless_nlevent_init
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_init
  - net/dcb/dcbnl.c:dcbnl_init
  - net/xdp/xsk.c:xsk_init
  - net/mctp/device.c:mctp_device_init
```
**Symbols:**

```
ffffffff81dc0b10-ffffffff81dc0c20: register_netdevice_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int register_netdevice_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e30690)
Location: net/core/dev.c:1731
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_init
  - security/selinux/netif.c:sel_netif_init
  - drivers/net/tun.c:tun_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/netdev-genl.c:netdev_genl_init
  - net/core/fib_rules.c:fib_rules_init
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/core/netprio_cgroup.c:init_cgroup_netprio
  - net/core/failover.c:failover_init
  - net/ethtool/netlink.c:ethnl_init
  - net/ipv4/arp.c:arp_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/igmp.c:igmp_mc_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/xfrm/xfrm_device.c:xfrm_dev_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ndisc.c:ndisc_late_init
  - net/ipv6/mcast.c:igmp6_late_init
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/packet/af_packet.c:packet_init
  - net/devlink/core.c:devlink_init
  - net/wireless/wext-core.c:wireless_nlevent_init
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_init
  - net/dcb/dcbnl.c:dcbnl_init
  - net/xdp/xsk.c:xsk_init
  - net/mctp/device.c:mctp_device_init
```
**Symbols:**

```
ffffffff81e30690-ffffffff81e307a0: register_netdevice_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int register_netdevice_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81eef020)
Location: net/core/dev.c:1735
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_init
  - security/selinux/netif.c:sel_netif_init
  - drivers/net/tun.c:tun_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/netdev-genl.c:netdev_genl_init
  - net/core/page_pool_user.c:page_pool_user_init
  - net/core/fib_rules.c:fib_rules_init
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/core/netprio_cgroup.c:init_cgroup_netprio
  - net/core/failover.c:failover_init
  - net/ethtool/netlink.c:ethnl_init
  - net/ipv4/arp.c:arp_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/igmp.c:igmp_mc_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/xfrm/xfrm_device.c:xfrm_dev_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ndisc.c:ndisc_late_init
  - net/ipv6/mcast.c:igmp6_late_init
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/packet/af_packet.c:packet_init
  - net/devlink/core.c:devlink_init
  - net/wireless/wext-core.c:wireless_nlevent_init
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_init
  - net/dcb/dcbnl.c:dcbnl_init
  - net/xdp/xsk.c:xsk_init
  - net/mctp/device.c:mctp_device_init
```
**Symbols:**

```
ffffffff81eef020-ffffffff81eef139: register_netdevice_notifier (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int register_netdevice_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bc7dd8)
Location: net/core/dev.c:1554
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_init
  - security/selinux/netif.c:sel_netif_init
  - drivers/net/tun.c:tun_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/fib_rules.c:fib_rules_init
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/core/netprio_cgroup.c:init_cgroup_netprio
  - net/ipv4/arp.c:arp_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/igmp.c:igmp_mc_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/xfrm/xfrm_device.c:xfrm_dev_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ndisc.c:ndisc_late_init
  - net/ipv6/mcast.c:igmp6_late_init
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/packet/af_packet.c:packet_init
  - net/wireless/wext-core.c:wireless_nlevent_init
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_init
  - net/xdp/xsk.c:xsk_init
```
**Symbols:**

```
ffff800010bc7dd8-ffff800010bc7fe0: register_netdevice_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int register_netdevice_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0ce36f8)
Location: net/core/dev.c:1554
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_init
  - security/selinux/netif.c:sel_netif_init
  - drivers/net/tun.c:tun_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/fib_rules.c:fib_rules_init
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/core/netprio_cgroup.c:init_cgroup_netprio
  - net/ipv4/arp.c:arp_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/igmp.c:igmp_mc_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/xfrm/xfrm_device.c:xfrm_dev_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ndisc.c:ndisc_late_init
  - net/ipv6/mcast.c:igmp6_late_init
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/packet/af_packet.c:packet_init
  - net/wireless/wext-core.c:wireless_nlevent_init
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_init
  - net/xdp/xsk.c:xsk_init
```
**Symbols:**

```
c0ce36f8-c0ce3914: register_netdevice_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int register_netdevice_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000ca39d0)
Location: net/core/dev.c:1554
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_init
  - security/selinux/netif.c:sel_netif_init
  - drivers/net/tun.c:tun_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/fib_rules.c:fib_rules_init
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/core/netprio_cgroup.c:init_cgroup_netprio
  - net/ipv4/arp.c:arp_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/igmp.c:igmp_mc_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/xfrm/xfrm_device.c:xfrm_dev_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ndisc.c:ndisc_late_init
  - net/ipv6/mcast.c:igmp6_late_init
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/packet/af_packet.c:packet_init
  - net/wireless/wext-core.c:wireless_nlevent_init
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_init
  - net/xdp/xsk.c:xsk_init
```
**Symbols:**

```
c000000000ca39d0-c000000000ca3ccc: register_netdevice_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int register_netdevice_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe000754464)
Location: net/core/dev.c:1554
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_init
  - security/selinux/netif.c:sel_netif_init
  - drivers/net/tun.c:tun_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/fib_rules.c:fib_rules_init
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/core/netprio_cgroup.c:init_cgroup_netprio
  - net/ipv4/arp.c:arp_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/igmp.c:igmp_mc_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/xfrm/xfrm_device.c:xfrm_dev_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ndisc.c:ndisc_late_init
  - net/ipv6/mcast.c:igmp6_late_init
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/packet/af_packet.c:packet_init
  - net/wireless/wext-core.c:wireless_nlevent_init
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_init
  - net/xdp/xsk.c:xsk_init
```
**Symbols:**

```
ffffffe000754464-ffffffe00075460c: register_netdevice_notifier (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int register_netdevice_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818cb6f0)
Location: net/core/dev.c:1554
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_init
  - security/selinux/netif.c:sel_netif_init
  - drivers/net/tun.c:tun_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/fib_rules.c:fib_rules_init
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/core/netprio_cgroup.c:init_cgroup_netprio
  - net/ipv4/arp.c:arp_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/igmp.c:igmp_mc_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/xfrm/xfrm_device.c:xfrm_dev_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ndisc.c:ndisc_late_init
  - net/ipv6/mcast.c:igmp6_late_init
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/packet/af_packet.c:packet_init
  - net/wireless/wext-core.c:wireless_nlevent_init
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_init
  - net/xdp/xsk.c:xsk_init
```
**Symbols:**

```
ffffffff818cb6f0-ffffffff818cb92c: register_netdevice_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int register_netdevice_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81885630)
Location: net/core/dev.c:1554
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_init
  - security/selinux/netif.c:sel_netif_init
  - drivers/net/tun.c:tun_init
  - drivers/net/vxlan.c:vxlan_init_module
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/fib_rules.c:fib_rules_init
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/core/netprio_cgroup.c:init_cgroup_netprio
  - net/ipv4/arp.c:arp_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/igmp.c:igmp_mc_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/xfrm/xfrm_device.c:xfrm_dev_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ndisc.c:ndisc_late_init
  - net/ipv6/mcast.c:igmp6_late_init
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/packet/af_packet.c:packet_init
  - net/wireless/wext-core.c:wireless_nlevent_init
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_init
  - net/xdp/xsk.c:xsk_init
```
**Symbols:**

```
ffffffff81885630-ffffffff8188586c: register_netdevice_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int register_netdevice_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8191c6f0)
Location: net/core/dev.c:1554
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_init
  - security/selinux/netif.c:sel_netif_init
  - drivers/net/tun.c:tun_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/fib_rules.c:fib_rules_init
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/core/netprio_cgroup.c:init_cgroup_netprio
  - net/netfilter/nfnetlink_queue.c:nfnetlink_queue_init
  - net/ipv4/arp.c:arp_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/igmp.c:igmp_mc_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/xfrm/xfrm_device.c:xfrm_dev_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ndisc.c:ndisc_late_init
  - net/ipv6/mcast.c:igmp6_late_init
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/packet/af_packet.c:packet_init
  - net/wireless/wext-core.c:wireless_nlevent_init
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_init
  - net/xdp/xsk.c:xsk_init
```
**Symbols:**

```
ffffffff8191c6f0-ffffffff8191c92c: register_netdevice_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int register_netdevice_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8193dbc0)
Location: net/core/dev.c:1554
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_init
  - security/selinux/netif.c:sel_netif_init
  - drivers/net/tun.c:tun_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/fib_rules.c:fib_rules_init
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/core/netprio_cgroup.c:init_cgroup_netprio
  - net/ipv4/arp.c:arp_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/igmp.c:igmp_mc_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/xfrm/xfrm_device.c:xfrm_dev_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ndisc.c:ndisc_late_init
  - net/ipv6/mcast.c:igmp6_late_init
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/packet/af_packet.c:packet_init
  - net/wireless/wext-core.c:wireless_nlevent_init
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_init
  - net/xdp/xsk.c:xsk_init
```
**Symbols:**

```
ffffffff8193dbc0-ffffffff8193ddfc: register_netdevice_notifier (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
