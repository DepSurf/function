# Function: <code>unregister_netdevice_notifier</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int unregister_netdevice_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81714f10)
Location: net/core/dev.c:1598
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/ndisc.c:ndisc_late_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/ipv6/ip6mr.c:ip6_mr_cleanup
  - net/packet/af_packet.c:packet_exit
```
**Symbols:**

```
ffffffff81714f10-ffffffff81715012: unregister_netdevice_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int unregister_netdevice_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8177cf10)
Location: net/core/dev.c:1602
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_cleanup
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/ndisc.c:ndisc_late_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/packet/af_packet.c:packet_exit
```
**Symbols:**

```
ffffffff8177cf10-ffffffff8177d012: unregister_netdevice_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int unregister_netdevice_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817aa550)
Location: net/core/dev.c:1601
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_cleanup
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/ndisc.c:ndisc_late_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/packet/af_packet.c:packet_exit
```
**Symbols:**

```
ffffffff817aa550-ffffffff817aa652: unregister_netdevice_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int unregister_netdevice_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817c8bb0)
Location: net/core/dev.c:1635
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_cleanup
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/ndisc.c:ndisc_late_cleanup
  - net/ipv6/mcast.c:igmp6_late_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/packet/af_packet.c:packet_exit
```
**Symbols:**

```
ffffffff817c8bb0-ffffffff817c8cb2: unregister_netdevice_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int unregister_netdevice_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81842830)
Location: net/core/dev.c:1650
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_cleanup
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/ndisc.c:ndisc_late_cleanup
  - net/ipv6/mcast.c:igmp6_late_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/packet/af_packet.c:packet_exit
```
**Symbols:**

```
ffffffff81842830-ffffffff8184295d: unregister_netdevice_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int unregister_netdevice_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8188cc50)
Location: net/core/dev.c:1692
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_cleanup
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/ndisc.c:ndisc_late_cleanup
  - net/ipv6/mcast.c:igmp6_late_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/packet/af_packet.c:packet_exit
```
**Symbols:**

```
ffffffff8188cc50-ffffffff8188cd95: unregister_netdevice_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int unregister_netdevice_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818adea0)
Location: net/core/dev.c:1696
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_cleanup
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/ndisc.c:ndisc_late_cleanup
  - net/ipv6/mcast.c:igmp6_late_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/packet/af_packet.c:packet_exit
```
**Symbols:**

```
ffffffff818adea0-ffffffff818adfe5: unregister_netdevice_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int unregister_netdevice_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818f97d0)
Location: net/core/dev.c:1706
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_cleanup
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/ndisc.c:ndisc_late_cleanup
  - net/ipv6/mcast.c:igmp6_late_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/packet/af_packet.c:packet_exit
```
**Symbols:**

```
ffffffff818f97d0-ffffffff818f9915: unregister_netdevice_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int unregister_netdevice_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8192b930)
Location: net/core/dev.c:1624
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_cleanup
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/ndisc.c:ndisc_late_cleanup
  - net/ipv6/mcast.c:igmp6_late_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/packet/af_packet.c:packet_exit
```
**Symbols:**

```
ffffffff8192b930-ffffffff8192ba75: unregister_netdevice_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int unregister_netdevice_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a01180)
Location: net/core/dev.c:1849
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_cleanup
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/ndisc.c:ndisc_late_cleanup
  - net/ipv6/mcast.c:igmp6_late_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/packet/af_packet.c:packet_exit
```
**Symbols:**

```
ffffffff81a01180-ffffffff81a0122d: unregister_netdevice_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int unregister_netdevice_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a012d0)
Location: net/core/dev.c:1874
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_cleanup
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/ndisc.c:ndisc_late_cleanup
  - net/ipv6/mcast.c:igmp6_late_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/packet/af_packet.c:packet_exit
```
**Symbols:**

```
ffffffff81a012d0-ffffffff81a0137d: unregister_netdevice_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int unregister_netdevice_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819e7f80)
Location: net/core/dev.c:1943
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_cleanup
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/ndisc.c:ndisc_late_cleanup
  - net/ipv6/mcast.c:igmp6_late_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/packet/af_packet.c:packet_exit
```
**Symbols:**

```
ffffffff819e7f80-ffffffff819e802d: unregister_netdevice_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int unregister_netdevice_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a98f80)
Location: net/core/dev.c:1818
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_cleanup
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/ndisc.c:ndisc_late_cleanup
  - net/ipv6/mcast.c:igmp6_late_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/packet/af_packet.c:packet_exit
```
**Symbols:**

```
ffffffff81a98f80-ffffffff81a9902d: unregister_netdevice_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int unregister_netdevice_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c10540)
Location: net/core/dev.c:1767
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_cleanup
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/ndisc.c:ndisc_late_cleanup
  - net/ipv6/mcast.c:igmp6_late_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/packet/af_packet.c:packet_exit
  - net/mctp/device.c:mctp_device_exit
```
**Symbols:**

```
ffffffff81c10540-ffffffff81c105f5: unregister_netdevice_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int unregister_netdevice_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dc00e0)
Location: net/core/dev.c:1752
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_cleanup
  - net/core/devlink.c:devlink_free
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/ndisc.c:ndisc_late_cleanup
  - net/ipv6/mcast.c:igmp6_late_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/packet/af_packet.c:packet_init
  - net/packet/af_packet.c:packet_exit
  - net/mctp/device.c:mctp_device_exit
```
**Symbols:**

```
ffffffff81dc00e0-ffffffff81dc0195: unregister_netdevice_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int unregister_netdevice_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e2fc80)
Location: net/core/dev.c:1778
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_cleanup
  - net/core/netdev-genl.c:netdev_genl_init
  - net/core/failover.c:failover_exit
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/ndisc.c:ndisc_late_cleanup
  - net/ipv6/mcast.c:igmp6_late_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/packet/af_packet.c:packet_init
  - net/packet/af_packet.c:packet_exit
  - net/mctp/device.c:mctp_device_exit
```
**Symbols:**

```
ffffffff81e2fc80-ffffffff81e2fd35: unregister_netdevice_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int unregister_netdevice_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81eee860)
Location: net/core/dev.c:1782
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_cleanup
  - net/core/netdev-genl.c:netdev_genl_init
  - net/core/failover.c:failover_exit
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/ndisc.c:ndisc_late_cleanup
  - net/ipv6/mcast.c:igmp6_late_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/packet/af_packet.c:packet_init
  - net/packet/af_packet.c:packet_exit
  - net/mctp/device.c:mctp_device_exit
```
**Symbols:**

```
ffffffff81eee860-ffffffff81eee91e: unregister_netdevice_notifier (STB_GLOBAL)
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
int unregister_netdevice_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bc7fe0)
Location: net/core/dev.c:1624
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_cleanup
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/ndisc.c:ndisc_late_cleanup
  - net/ipv6/mcast.c:igmp6_late_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/packet/af_packet.c:packet_exit
```
**Symbols:**

```
ffff800010bc7fe0-ffff800010bc8128: unregister_netdevice_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int unregister_netdevice_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0ce3914)
Location: net/core/dev.c:1624
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_cleanup
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/ndisc.c:ndisc_late_cleanup
  - net/ipv6/mcast.c:igmp6_late_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/packet/af_packet.c:packet_exit
```
**Symbols:**

```
c0ce3914-c0ce3a50: unregister_netdevice_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int unregister_netdevice_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000ca3cd0)
Location: net/core/dev.c:1624
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_cleanup
  - net/core/drop_monitor.c:exit_net_drop_monitor
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/ndisc.c:ndisc_late_cleanup
  - net/ipv6/mcast.c:igmp6_late_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/packet/af_packet.c:packet_exit
```
**Symbols:**

```
c000000000ca3cd0-c000000000ca3ebc: unregister_netdevice_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int unregister_netdevice_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe00075460c)
Location: net/core/dev.c:1624
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_cleanup
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/ndisc.c:ndisc_late_cleanup
  - net/ipv6/mcast.c:igmp6_late_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/packet/af_packet.c:packet_exit
```
**Symbols:**

```
ffffffe00075460c-ffffffe00075470c: unregister_netdevice_notifier (STB_GLOBAL)
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
int unregister_netdevice_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818cb930)
Location: net/core/dev.c:1624
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_cleanup
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/ndisc.c:ndisc_late_cleanup
  - net/ipv6/mcast.c:igmp6_late_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/packet/af_packet.c:packet_exit
```
**Symbols:**

```
ffffffff818cb930-ffffffff818cba75: unregister_netdevice_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int unregister_netdevice_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81885870)
Location: net/core/dev.c:1624
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_cleanup
  - drivers/net/vxlan.c:vxlan_cleanup_module
  - drivers/net/vxlan.c:vxlan_init_module
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/ndisc.c:ndisc_late_cleanup
  - net/ipv6/mcast.c:igmp6_late_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/packet/af_packet.c:packet_exit
```
**Symbols:**

```
ffffffff81885870-ffffffff818859b5: unregister_netdevice_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int unregister_netdevice_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8191c930)
Location: net/core/dev.c:1624
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_cleanup
  - net/netfilter/nfnetlink_queue.c:nfnetlink_queue_fini
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/ndisc.c:ndisc_late_cleanup
  - net/ipv6/mcast.c:igmp6_late_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/packet/af_packet.c:packet_exit
```
**Symbols:**

```
ffffffff8191c930-ffffffff8191ca75: unregister_netdevice_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int unregister_netdevice_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8193de00)
Location: net/core/dev.c:1624
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_cleanup
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/ndisc.c:ndisc_late_cleanup
  - net/ipv6/mcast.c:igmp6_late_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/packet/af_packet.c:packet_exit
```
**Symbols:**

```
ffffffff8193de00-ffffffff8193df45: unregister_netdevice_notifier (STB_GLOBAL)
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
