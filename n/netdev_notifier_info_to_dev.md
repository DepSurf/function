# Function: <code>netdev_notifier_info_to_dev</code>

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
In security/selinux/netif.c (ffffffff8134cdfc)
Location: include/linux/netdevice.h:2198
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_netdev_notifier_handler
```
```
In net/core/dst.c (ffffffff81723971)
Location: include/linux/netdevice.h:2198
Inline: True
Inline callers:
  - net/core/dst.c:dst_dev_event
```
```
In net/core/rtnetlink.c (ffffffff8172fbcc)
Location: include/linux/netdevice.h:2198
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_event
```
```
In net/core/fib_rules.c (ffffffff8173992e)
Location: include/linux/netdevice.h:2198
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_event
```
```
In net/core/netprio_cgroup.c (ffffffff8173d95b)
Location: include/linux/netdevice.h:2198
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:netprio_device_event
```
```
In net/ipv4/arp.c (ffffffff8178bebe)
Location: include/linux/netdevice.h:2198
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_netdev_event
```
```
In net/ipv4/devinet.c (ffffffff81791cbd)
Location: include/linux/netdevice.h:2198
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/netdevice.h:2198
Inline: True
```
```
In net/ipv4/fib_frontend.c (ffffffff8179b862)
Location: include/linux/netdevice.h:2198
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_netdev_event
```
```
In net/ipv4/ipmr.c (ffffffff817a7809)
Location: include/linux/netdevice.h:2198
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_device_event
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/netdevice.h:2198
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff817d155a)
Location: include/linux/netdevice.h:2198
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_notify
```
```
In net/ipv6/route.c (ffffffff817d3276)
Location: include/linux/netdevice.h:2198
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_dev_notify
```
```
In net/ipv6/ndisc.c (ffffffff817e0860)
Location: include/linux/netdevice.h:2198
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_netdev_event
```
```
In net/ipv6/ip6mr.c (ffffffff817f814a)
Location: include/linux/netdevice.h:2198
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_device_event
```
```
In net/packet/af_packet.c (ffffffff81803d82)
Location: include/linux/netdevice.h:2198
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_notifier
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff8180e32a)
Location: include/linux/netdevice.h:2198
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_netdev_handler
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
In security/selinux/netif.c (ffffffff81382dac)
Location: include/linux/netdevice.h:2333
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_netdev_notifier_handler
```
```
In drivers/net/tun.c (ffffffff816506c5)
Location: include/linux/netdevice.h:2333
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
```
```
In net/core/dst.c (ffffffff8178d3c9)
Location: include/linux/netdevice.h:2333
Inline: True
Inline callers:
  - net/core/dst.c:dst_dev_event
```
```
In net/core/rtnetlink.c (ffffffff8179a31c)
Location: include/linux/netdevice.h:2333
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_event
```
```
In net/core/fib_rules.c (ffffffff817a5c3e)
Location: include/linux/netdevice.h:2333
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_event
```
```
In net/core/netprio_cgroup.c (ffffffff817aa11b)
Location: include/linux/netdevice.h:2333
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:netprio_device_event
```
```
In net/ipv4/arp.c (ffffffff817f94ee)
Location: include/linux/netdevice.h:2333
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_netdev_event
```
```
In net/ipv4/devinet.c (ffffffff817ffb9d)
Location: include/linux/netdevice.h:2333
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/netdevice.h:2333
Inline: True
```
```
In net/ipv4/fib_frontend.c (ffffffff81809462)
Location: include/linux/netdevice.h:2333
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_netdev_event
```
```
In net/ipv4/ipmr.c (ffffffff818154e9)
Location: include/linux/netdevice.h:2333
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_device_event
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/netdevice.h:2333
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff8183ed8a)
Location: include/linux/netdevice.h:2333
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_notify
```
```
In net/ipv6/route.c (ffffffff81840c76)
Location: include/linux/netdevice.h:2333
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_dev_notify
```
```
In net/ipv6/ndisc.c (ffffffff8184d7b0)
Location: include/linux/netdevice.h:2333
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_netdev_event
```
```
In net/ipv6/ip6mr.c (ffffffff818678aa)
Location: include/linux/netdevice.h:2333
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_device_event
```
```
In net/packet/af_packet.c (ffffffff81874d42)
Location: include/linux/netdevice.h:2333
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_notifier
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff818809aa)
Location: include/linux/netdevice.h:2333
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_netdev_handler
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
In security/selinux/netif.c (ffffffff8139982c)
Location: include/linux/netdevice.h:2330
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_netdev_notifier_handler
```
```
In drivers/net/tun.c (ffffffff816823a5)
Location: include/linux/netdevice.h:2330
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
```
```
In net/core/dst.c (ffffffff817bac99)
Location: include/linux/netdevice.h:2330
Inline: True
Inline callers:
  - net/core/dst.c:dst_dev_event
```
```
In net/core/rtnetlink.c (ffffffff817c80bc)
Location: include/linux/netdevice.h:2330
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_event
```
```
In net/core/fib_rules.c (ffffffff817d470e)
Location: include/linux/netdevice.h:2330
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_event
```
```
In net/core/netprio_cgroup.c (ffffffff817d8c5b)
Location: include/linux/netdevice.h:2330
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:netprio_device_event
```
```
In net/ipv4/arp.c (ffffffff8182a3be)
Location: include/linux/netdevice.h:2330
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_netdev_event
```
```
In net/ipv4/devinet.c (ffffffff81830afd)
Location: include/linux/netdevice.h:2330
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/netdevice.h:2330
Inline: True
```
```
In net/ipv4/fib_frontend.c (ffffffff8183a572)
Location: include/linux/netdevice.h:2330
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_netdev_event
```
```
In net/ipv4/ipmr.c (ffffffff81846ca9)
Location: include/linux/netdevice.h:2330
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_device_event
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/netdevice.h:2330
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff8187099a)
Location: include/linux/netdevice.h:2330
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_notify
```
```
In net/ipv6/route.c (ffffffff81872946)
Location: include/linux/netdevice.h:2330
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_dev_notify
```
```
In net/ipv6/ndisc.c (ffffffff8187f660)
Location: include/linux/netdevice.h:2330
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_netdev_event
```
```
In net/ipv6/ip6mr.c (ffffffff8189a70a)
Location: include/linux/netdevice.h:2330
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_device_event
```
```
In net/packet/af_packet.c (ffffffff818a9202)
Location: include/linux/netdevice.h:2330
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_notifier
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff818b525a)
Location: include/linux/netdevice.h:2330
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_netdev_handler
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
In security/selinux/netif.c (ffffffff813afc3c)
Location: include/linux/netdevice.h:2345
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_netdev_notifier_handler
```
```
In drivers/net/tun.c (ffffffff816974b8)
Location: include/linux/netdevice.h:2345
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
```
```
In net/core/rtnetlink.c (ffffffff817e69ab)
Location: include/linux/netdevice.h:2345
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_event
```
```
In net/core/fib_rules.c (ffffffff817f39fe)
Location: include/linux/netdevice.h:2345
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_event
```
```
In net/core/netprio_cgroup.c (ffffffff817f7e7b)
Location: include/linux/netdevice.h:2345
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:netprio_device_event
```
```
In net/ipv4/arp.c (ffffffff8184b5de)
Location: include/linux/netdevice.h:2345
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_netdev_event
```
```
In net/ipv4/devinet.c (ffffffff818520c8)
Location: include/linux/netdevice.h:2345
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/netdevice.h:2345
Inline: True
```
```
In net/ipv4/fib_frontend.c (ffffffff8185bae2)
Location: include/linux/netdevice.h:2345
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_netdev_event
```
```
In net/ipv4/ipmr.c (ffffffff81868659)
Location: include/linux/netdevice.h:2345
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_device_event
```
```
In net/xfrm/xfrm_device.c (ffffffff8188022e)
Location: include/linux/netdevice.h:2345
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_event
```
```
In net/ipv6/addrconf.c (ffffffff81895775)
Location: include/linux/netdevice.h:2345
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_notify
```
```
In net/ipv6/route.c (ffffffff8189a805)
Location: include/linux/netdevice.h:2345
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_dev_notify
```
```
In net/ipv6/ndisc.c (ffffffff818a5744)
Location: include/linux/netdevice.h:2345
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_netdev_event
```
```
In net/ipv6/mcast.c (ffffffff818b1f20)
Location: include/linux/netdevice.h:2345
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_netdev_event
```
```
In net/ipv6/ip6mr.c (ffffffff818c08fb)
Location: include/linux/netdevice.h:2345
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_device_event
```
```
In net/packet/af_packet.c (ffffffff818cfc52)
Location: include/linux/netdevice.h:2345
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_notifier
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff818dbbaa)
Location: include/linux/netdevice.h:2345
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_netdev_handler
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
In kernel/bpf/devmap.c (0)
Location: include/linux/netdevice.h:2364
Inline: True
```
```
In kernel/bpf/offload.c (0)
Location: include/linux/netdevice.h:2364
Inline: True
```
```
In security/selinux/netif.c (0)
Location: include/linux/netdevice.h:2364
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/netdevice.h:2364
Inline: True
```
```
In net/core/rtnetlink.c (0)
Location: include/linux/netdevice.h:2364
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/linux/netdevice.h:2364
Inline: True
```
```
In net/core/netprio_cgroup.c (0)
Location: include/linux/netdevice.h:2364
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/netdevice.h:2364
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/linux/netdevice.h:2364
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/netdevice.h:2364
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/netdevice.h:2364
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/netdevice.h:2364
Inline: True
```
```
In net/xfrm/xfrm_device.c (0)
Location: include/linux/netdevice.h:2364
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/netdevice.h:2364
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/netdevice.h:2364
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/linux/netdevice.h:2364
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/netdevice.h:2364
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/netdevice.h:2364
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/netdevice.h:2364
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/linux/netdevice.h:2364
Inline: True
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
In kernel/bpf/devmap.c (0)
Location: include/linux/netdevice.h:2449
Inline: True
```
```
In kernel/bpf/offload.c (0)
Location: include/linux/netdevice.h:2449
Inline: True
```
```
In security/selinux/netif.c (0)
Location: include/linux/netdevice.h:2449
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/netdevice.h:2449
Inline: True
```
```
In net/core/rtnetlink.c (0)
Location: include/linux/netdevice.h:2449
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/linux/netdevice.h:2449
Inline: True
```
```
In net/core/netprio_cgroup.c (0)
Location: include/linux/netdevice.h:2449
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/netdevice.h:2449
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/linux/netdevice.h:2449
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/netdevice.h:2449
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/netdevice.h:2449
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/netdevice.h:2449
Inline: True
```
```
In net/xfrm/xfrm_device.c (0)
Location: include/linux/netdevice.h:2449
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/netdevice.h:2449
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/netdevice.h:2449
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/linux/netdevice.h:2449
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/netdevice.h:2449
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/netdevice.h:2449
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/netdevice.h:2449
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/linux/netdevice.h:2449
Inline: True
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
In kernel/bpf/devmap.c (0)
Location: include/linux/netdevice.h:2537
Inline: True
```
```
In security/selinux/netif.c (0)
Location: include/linux/netdevice.h:2537
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/netdevice.h:2537
Inline: True
```
```
In net/core/rtnetlink.c (0)
Location: include/linux/netdevice.h:2537
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/linux/netdevice.h:2537
Inline: True
```
```
In net/core/netprio_cgroup.c (0)
Location: include/linux/netdevice.h:2537
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/netdevice.h:2537
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/linux/netdevice.h:2537
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/netdevice.h:2537
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/netdevice.h:2537
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/netdevice.h:2537
Inline: True
```
```
In net/xfrm/xfrm_device.c (0)
Location: include/linux/netdevice.h:2537
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/netdevice.h:2537
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/netdevice.h:2537
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/linux/netdevice.h:2537
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/netdevice.h:2537
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/netdevice.h:2537
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/netdevice.h:2537
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/linux/netdevice.h:2537
Inline: True
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
In kernel/bpf/devmap.c (0)
Location: include/linux/netdevice.h:2528
Inline: True
```
```
In security/selinux/netif.c (0)
Location: include/linux/netdevice.h:2528
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/netdevice.h:2528
Inline: True
```
```
In net/core/rtnetlink.c (0)
Location: include/linux/netdevice.h:2528
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/linux/netdevice.h:2528
Inline: True
```
```
In net/core/netprio_cgroup.c (0)
Location: include/linux/netdevice.h:2528
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/netdevice.h:2528
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/linux/netdevice.h:2528
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/netdevice.h:2528
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/netdevice.h:2528
Inline: True
```
```
In net/ipv4/nexthop.c (0)
Location: include/linux/netdevice.h:2528
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/netdevice.h:2528
Inline: True
```
```
In net/xfrm/xfrm_device.c (0)
Location: include/linux/netdevice.h:2528
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/netdevice.h:2528
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/netdevice.h:2528
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/linux/netdevice.h:2528
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/netdevice.h:2528
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/netdevice.h:2528
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/netdevice.h:2528
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/linux/netdevice.h:2528
Inline: True
```
```
In net/xdp/xsk.c (0)
Location: include/linux/netdevice.h:2528
Inline: True
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
In kernel/bpf/devmap.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In security/selinux/netif.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/core/rtnetlink.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/core/drop_monitor.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/core/netprio_cgroup.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/ipv4/nexthop.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/xfrm/xfrm_device.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/xdp/xsk.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
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
In kernel/bpf/devmap.c (ffffffff81226a45)
Location: include/linux/netdevice.h:2648
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_notification
```
```
In security/selinux/netif.c (ffffffff814bda45)
Location: include/linux/netdevice.h:2648
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_netdev_notifier_handler
```
```
In drivers/net/tun.c (ffffffff8188c025)
Location: include/linux/netdevice.h:2648
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
```
```
In net/core/rtnetlink.c (ffffffff81a21975)
Location: include/linux/netdevice.h:2648
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_event
```
```
In net/core/fib_rules.c (ffffffff81a3fab5)
Location: include/linux/netdevice.h:2648
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_event
```
```
In net/core/drop_monitor.c (ffffffff81a49a25)
Location: include/linux/netdevice.h:2648
Inline: True
Inline callers:
  - net/core/drop_monitor.c:dropmon_net_event
```
```
In net/core/netprio_cgroup.c (ffffffff81a4b5a5)
Location: include/linux/netdevice.h:2648
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:netprio_device_event
```
```
In net/ethtool/netlink.c (ffffffff81a85942)
Location: include/linux/netdevice.h:2648
Inline: True
```
```
In net/ipv4/arp.c (ffffffff81ad9445)
Location: include/linux/netdevice.h:2648
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_netdev_event
```
```
In net/ipv4/devinet.c (ffffffff81ae17d5)
Location: include/linux/netdevice.h:2648
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
```
```
In net/ipv4/igmp.c (ffffffff81ae6035)
Location: include/linux/netdevice.h:2648
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_netdev_event
```
```
In net/ipv4/fib_frontend.c (ffffffff81aec085)
Location: include/linux/netdevice.h:2648
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_netdev_event
```
```
In net/ipv4/nexthop.c (ffffffff81afccf5)
Location: include/linux/netdevice.h:2648
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_netdev_event
```
```
In net/ipv4/ipmr.c (ffffffff81b01895)
Location: include/linux/netdevice.h:2648
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_device_event
```
```
In net/xfrm/xfrm_device.c (ffffffff81b218b5)
Location: include/linux/netdevice.h:2648
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_event
```
```
In net/ipv6/addrconf.c (ffffffff81b3dda5)
Location: include/linux/netdevice.h:2648
Inline: True
```
```
In net/ipv6/route.c (ffffffff81b43ff5)
Location: include/linux/netdevice.h:2648
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_dev_notify
```
```
In net/ipv6/ndisc.c (ffffffff81b55d55)
Location: include/linux/netdevice.h:2648
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_netdev_event
```
```
In net/ipv6/mcast.c (ffffffff81b626a5)
Location: include/linux/netdevice.h:2648
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_netdev_event
```
```
In net/ipv6/ip6mr.c (ffffffff81b74e25)
Location: include/linux/netdevice.h:2648
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_device_event
```
```
In net/packet/af_packet.c (ffffffff81b89765)
Location: include/linux/netdevice.h:2648
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_notifier
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81b94945)
Location: include/linux/netdevice.h:2648
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_netdev_handler
```
```
In net/xdp/xsk.c (ffffffff81ba6505)
Location: include/linux/netdevice.h:2648
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_notifier
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
In kernel/bpf/devmap.c (ffffffff8122d4d5)
Location: include/linux/netdevice.h:2785
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_notification
```
```
In security/selinux/netif.c (ffffffff814db4a5)
Location: include/linux/netdevice.h:2785
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_netdev_notifier_handler
```
```
In drivers/net/tun.c (ffffffff8189a485)
Location: include/linux/netdevice.h:2785
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
```
```
In net/core/rtnetlink.c (ffffffff81a21db5)
Location: include/linux/netdevice.h:2785
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_event
```
```
In net/core/fib_rules.c (ffffffff81a427b5)
Location: include/linux/netdevice.h:2785
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_event
```
```
In net/core/drop_monitor.c (ffffffff81a4f1f5)
Location: include/linux/netdevice.h:2785
Inline: True
Inline callers:
  - net/core/drop_monitor.c:dropmon_net_event
```
```
In net/core/netprio_cgroup.c (ffffffff81a51245)
Location: include/linux/netdevice.h:2785
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:netprio_device_event
```
```
In net/ethtool/netlink.c (ffffffff81a8f2b2)
Location: include/linux/netdevice.h:2785
Inline: True
```
```
In net/ipv4/arp.c (ffffffff81ae5ea5)
Location: include/linux/netdevice.h:2785
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_netdev_event
```
```
In net/ipv4/devinet.c (ffffffff81aee675)
Location: include/linux/netdevice.h:2785
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
```
```
In net/ipv4/igmp.c (ffffffff81af2f05)
Location: include/linux/netdevice.h:2785
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_netdev_event
```
```
In net/ipv4/fib_frontend.c (ffffffff81af8f85)
Location: include/linux/netdevice.h:2785
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_netdev_event
```
```
In net/ipv4/nexthop.c (ffffffff81b0aae5)
Location: include/linux/netdevice.h:2785
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_netdev_event
```
```
In net/ipv4/ipmr.c (ffffffff81b0f975)
Location: include/linux/netdevice.h:2785
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_device_event
```
```
In net/xfrm/xfrm_device.c (ffffffff81b30285)
Location: include/linux/netdevice.h:2785
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_event
```
```
In net/ipv6/addrconf.c (ffffffff81b4c935)
Location: include/linux/netdevice.h:2785
Inline: True
```
```
In net/ipv6/route.c (ffffffff81b530f5)
Location: include/linux/netdevice.h:2785
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_dev_notify
```
```
In net/ipv6/ndisc.c (ffffffff81b64365)
Location: include/linux/netdevice.h:2785
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_netdev_event
```
```
In net/ipv6/mcast.c (ffffffff81b71415)
Location: include/linux/netdevice.h:2785
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_netdev_event
```
```
In net/ipv6/ip6mr.c (ffffffff81b83b95)
Location: include/linux/netdevice.h:2785
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_device_event
```
```
In net/packet/af_packet.c (ffffffff81b99275)
Location: include/linux/netdevice.h:2785
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_notifier
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81ba4585)
Location: include/linux/netdevice.h:2785
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_netdev_handler
```
```
In net/xdp/xsk.c (ffffffff81bb6d65)
Location: include/linux/netdevice.h:2785
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_notifier
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
In kernel/bpf/devmap.c (ffffffff81232505)
Location: include/linux/netdevice.h:2850
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_notification
```
```
In security/selinux/netif.c (ffffffff814e1e25)
Location: include/linux/netdevice.h:2850
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_netdev_notifier_handler
```
```
In drivers/net/tun.c (ffffffff8187cbe5)
Location: include/linux/netdevice.h:2850
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
```
```
In net/core/rtnetlink.c (ffffffff81a090f5)
Location: include/linux/netdevice.h:2850
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_event
```
```
In net/core/fib_rules.c (ffffffff81a273f5)
Location: include/linux/netdevice.h:2850
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_event
```
```
In net/core/drop_monitor.c (ffffffff81a34235)
Location: include/linux/netdevice.h:2850
Inline: True
Inline callers:
  - net/core/drop_monitor.c:dropmon_net_event
```
```
In net/core/netprio_cgroup.c (ffffffff81a36ab5)
Location: include/linux/netdevice.h:2850
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:netprio_device_event
```
```
In net/ethtool/netlink.c (ffffffff81a789b2)
Location: include/linux/netdevice.h:2850
Inline: True
```
```
In net/ipv4/arp.c (ffffffff81ad1185)
Location: include/linux/netdevice.h:2850
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_netdev_event
```
```
In net/ipv4/devinet.c (ffffffff81ad9c85)
Location: include/linux/netdevice.h:2850
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
```
```
In net/ipv4/igmp.c (ffffffff81ade5b5)
Location: include/linux/netdevice.h:2850
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_netdev_event
```
```
In net/ipv4/fib_frontend.c (ffffffff81ae4745)
Location: include/linux/netdevice.h:2850
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_netdev_event
```
```
In net/ipv4/nexthop.c (ffffffff81af8375)
Location: include/linux/netdevice.h:2850
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_netdev_event
```
```
In net/ipv4/ipmr.c (ffffffff81afd575)
Location: include/linux/netdevice.h:2850
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_device_event
```
```
In net/xfrm/xfrm_device.c (ffffffff81b1e105)
Location: include/linux/netdevice.h:2850
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_event
```
```
In net/ipv6/addrconf.c (ffffffff81b3a605)
Location: include/linux/netdevice.h:2850
Inline: True
```
```
In net/ipv6/route.c (ffffffff81b40a85)
Location: include/linux/netdevice.h:2850
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_dev_notify
```
```
In net/ipv6/ndisc.c (ffffffff81b52635)
Location: include/linux/netdevice.h:2850
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_netdev_event
```
```
In net/ipv6/mcast.c (ffffffff81b5f295)
Location: include/linux/netdevice.h:2850
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_netdev_event
```
```
In net/ipv6/ip6mr.c (ffffffff81b72825)
Location: include/linux/netdevice.h:2850
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_device_event
```
```
In net/packet/af_packet.c (ffffffff81b88315)
Location: include/linux/netdevice.h:2850
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_notifier
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81b93195)
Location: include/linux/netdevice.h:2850
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_netdev_handler
```
```
In net/xdp/xsk.c (ffffffff81ba5c85)
Location: include/linux/netdevice.h:2850
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_notifier
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
In kernel/bpf/devmap.c (ffffffff8126b895)
Location: include/linux/netdevice.h:2871
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_notification
```
```
In security/selinux/netif.c (ffffffff8153ae25)
Location: include/linux/netdevice.h:2871
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_netdev_notifier_handler
```
```
In drivers/net/tun.c (ffffffff8190e1b5)
Location: include/linux/netdevice.h:2871
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
```
```
In net/core/rtnetlink.c (ffffffff81abb5c5)
Location: include/linux/netdevice.h:2871
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_event
```
```
In net/core/fib_rules.c (ffffffff81adc185)
Location: include/linux/netdevice.h:2871
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_event
```
```
In net/core/drop_monitor.c (ffffffff81ae9d45)
Location: include/linux/netdevice.h:2871
Inline: True
Inline callers:
  - net/core/drop_monitor.c:dropmon_net_event
```
```
In net/core/netprio_cgroup.c (ffffffff81aec7f5)
Location: include/linux/netdevice.h:2871
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:netprio_device_event
```
```
In net/ethtool/netlink.c (ffffffff81b32b82)
Location: include/linux/netdevice.h:2871
Inline: True
```
```
In net/ipv4/arp.c (ffffffff81b8fba5)
Location: include/linux/netdevice.h:2871
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_netdev_event
```
```
In net/ipv4/devinet.c (ffffffff81b98dc5)
Location: include/linux/netdevice.h:2871
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
```
```
In net/ipv4/igmp.c (ffffffff81b9da85)
Location: include/linux/netdevice.h:2871
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_netdev_event
```
```
In net/ipv4/fib_frontend.c (ffffffff81ba4075)
Location: include/linux/netdevice.h:2871
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_netdev_event
```
```
In net/ipv4/nexthop.c (ffffffff81bb9115)
Location: include/linux/netdevice.h:2871
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_netdev_event
```
```
In net/ipv4/ipmr.c (ffffffff81bbedd5)
Location: include/linux/netdevice.h:2871
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_device_event
```
```
In net/xfrm/xfrm_device.c (ffffffff81be2bf5)
Location: include/linux/netdevice.h:2871
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_event
```
```
In net/ipv6/addrconf.c (ffffffff81c00da5)
Location: include/linux/netdevice.h:2871
Inline: True
```
```
In net/ipv6/route.c (ffffffff81c070b5)
Location: include/linux/netdevice.h:2871
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_dev_notify
```
```
In net/ipv6/ndisc.c (ffffffff81c19b45)
Location: include/linux/netdevice.h:2871
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_netdev_event
```
```
In net/ipv6/mcast.c (ffffffff81c26a45)
Location: include/linux/netdevice.h:2871
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_netdev_event
```
```
In net/ipv6/ip6mr.c (ffffffff81c3cd65)
Location: include/linux/netdevice.h:2871
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_device_event
```
```
In net/packet/af_packet.c (ffffffff81c54425)
Location: include/linux/netdevice.h:2871
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_notifier
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81c5f935)
Location: include/linux/netdevice.h:2871
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_netdev_handler
```
```
In net/dcb/dcbnl.c (ffffffff81c64c45)
Location: include/linux/netdevice.h:2871
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_netdevice_event
```
```
In net/xdp/xsk.c (ffffffff81c742f5)
Location: include/linux/netdevice.h:2871
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_notifier
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
In kernel/bpf/devmap.c (ffffffff812ba695)
Location: include/linux/netdevice.h:2903
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_notification
```
```
In security/selinux/netif.c (ffffffff815d2575)
Location: include/linux/netdevice.h:2903
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_netdev_notifier_handler
```
```
In drivers/net/tun.c (ffffffff81a621b5)
Location: include/linux/netdevice.h:2903
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
```
```
In net/core/rtnetlink.c (ffffffff81c35e15)
Location: include/linux/netdevice.h:2903
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_event
```
```
In net/core/fib_rules.c (ffffffff81c5d5e5)
Location: include/linux/netdevice.h:2903
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_event
```
```
In net/core/drop_monitor.c (ffffffff81c6c5b5)
Location: include/linux/netdevice.h:2903
Inline: True
Inline callers:
  - net/core/drop_monitor.c:dropmon_net_event
```
```
In net/core/netprio_cgroup.c (ffffffff81c6f2e5)
Location: include/linux/netdevice.h:2903
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:netprio_device_event
```
```
In net/ethtool/netlink.c (ffffffff81cbe148)
Location: include/linux/netdevice.h:2903
Inline: True
```
```
In net/ipv4/arp.c (ffffffff81d20f05)
Location: include/linux/netdevice.h:2903
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_netdev_event
```
```
In net/ipv4/devinet.c (ffffffff81d2ac75)
Location: include/linux/netdevice.h:2903
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
```
```
In net/ipv4/igmp.c (ffffffff81d2fca5)
Location: include/linux/netdevice.h:2903
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_netdev_event
```
```
In net/ipv4/fib_frontend.c (ffffffff81d36985)
Location: include/linux/netdevice.h:2903
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_netdev_event
```
```
In net/ipv4/nexthop.c (ffffffff81d4d0c5)
Location: include/linux/netdevice.h:2903
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_netdev_event
```
```
In net/ipv4/ipmr.c (ffffffff81d53b55)
Location: include/linux/netdevice.h:2903
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_device_event
```
```
In net/xfrm/xfrm_device.c (ffffffff81d79d75)
Location: include/linux/netdevice.h:2903
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_event
```
```
In net/ipv6/addrconf.c (ffffffff81d9aa95)
Location: include/linux/netdevice.h:2903
Inline: True
```
```
In net/ipv6/route.c (ffffffff81da1745)
Location: include/linux/netdevice.h:2903
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_dev_notify
```
```
In net/ipv6/ndisc.c (ffffffff81db6005)
Location: include/linux/netdevice.h:2903
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_netdev_event
```
```
In net/ipv6/mcast.c (ffffffff81dc35b5)
Location: include/linux/netdevice.h:2903
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_netdev_event
```
```
In net/ipv6/ip6mr.c (ffffffff81ddb335)
Location: include/linux/netdevice.h:2903
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_device_event
```
```
In net/packet/af_packet.c (ffffffff81df2ad5)
Location: include/linux/netdevice.h:2903
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_notifier
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81e011a5)
Location: include/linux/netdevice.h:2903
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_netdev_handler
```
```
In net/dcb/dcbnl.c (ffffffff81e077d5)
Location: include/linux/netdevice.h:2903
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_netdevice_event
```
```
In net/xdp/xsk.c (ffffffff81e17325)
Location: include/linux/netdevice.h:2903
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_notifier
```
```
In net/mctp/device.c (ffffffff81e389e5)
Location: include/linux/netdevice.h:2903
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_dev_notify
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
In kernel/bpf/devmap.c (ffffffff8131db55)
Location: include/linux/netdevice.h:2928
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_notification
```
```
In security/selinux/netif.c (ffffffff81680475)
Location: include/linux/netdevice.h:2928
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_netdev_notifier_handler
```
```
In drivers/net/tun.c (ffffffff81bedb95)
Location: include/linux/netdevice.h:2928
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
```
```
In net/core/rtnetlink.c (ffffffff81de93d5)
Location: include/linux/netdevice.h:2928
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_event
```
```
In net/core/fib_rules.c (ffffffff81e13db5)
Location: include/linux/netdevice.h:2928
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_event
```
```
In net/core/drop_monitor.c (ffffffff81e23fc5)
Location: include/linux/netdevice.h:2928
Inline: True
Inline callers:
  - net/core/drop_monitor.c:dropmon_net_event
```
```
In net/core/netprio_cgroup.c (ffffffff81e270d5)
Location: include/linux/netdevice.h:2928
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:netprio_device_event
```
```
In net/core/devlink.c (ffffffff81e3e375)
Location: include/linux/netdevice.h:2928
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_netdevice_event
```
```
In net/ethtool/netlink.c (ffffffff81e7cbc8)
Location: include/linux/netdevice.h:2928
Inline: True
```
```
In net/ipv4/arp.c (ffffffff81ee8285)
Location: include/linux/netdevice.h:2928
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_netdev_event
```
```
In net/ipv4/devinet.c (ffffffff81ef2985)
Location: include/linux/netdevice.h:2928
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
```
```
In net/ipv4/igmp.c (ffffffff81ef7d95)
Location: include/linux/netdevice.h:2928
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_netdev_event
```
```
In net/ipv4/fib_frontend.c (ffffffff81eff015)
Location: include/linux/netdevice.h:2928
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_netdev_event
```
```
In net/ipv4/nexthop.c (ffffffff81f169a5)
Location: include/linux/netdevice.h:2928
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_netdev_event
```
```
In net/ipv4/ipmr.c (ffffffff81f1dd25)
Location: include/linux/netdevice.h:2928
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_device_event
```
```
In net/xfrm/xfrm_device.c (ffffffff81f46b95)
Location: include/linux/netdevice.h:2928
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_event
```
```
In net/ipv6/addrconf.c (ffffffff81f69905)
Location: include/linux/netdevice.h:2928
Inline: True
```
```
In net/ipv6/route.c (ffffffff81f70aa5)
Location: include/linux/netdevice.h:2928
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_dev_notify
```
```
In net/ipv6/ndisc.c (ffffffff81f85c65)
Location: include/linux/netdevice.h:2928
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_netdev_event
```
```
In net/ipv6/mcast.c (ffffffff81f94745)
Location: include/linux/netdevice.h:2928
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_netdev_event
```
```
In net/ipv6/ip6mr.c (ffffffff81fad025)
Location: include/linux/netdevice.h:2928
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_device_event
```
```
In net/packet/af_packet.c (ffffffff81fc6ec5)
Location: include/linux/netdevice.h:2928
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_notifier
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81fd5fd5)
Location: include/linux/netdevice.h:2928
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_netdev_handler
```
```
In net/dcb/dcbnl.c (ffffffff81fdcb35)
Location: include/linux/netdevice.h:2928
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_netdevice_event
```
```
In net/xdp/xsk.c (ffffffff81fedd75)
Location: include/linux/netdevice.h:2928
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_notifier
```
```
In net/mctp/device.c (ffffffff82011cd5)
Location: include/linux/netdevice.h:2928
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_dev_notify
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
In kernel/bpf/devmap.c (ffffffff8134d925)
Location: include/linux/netdevice.h:2982
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_notification
```
```
In security/selinux/netif.c (ffffffff816b8555)
Location: include/linux/netdevice.h:2982
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_netdev_notifier_handler
```
```
In drivers/net/tun.c (ffffffff81c460c5)
Location: include/linux/netdevice.h:2982
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
```
```
In net/core/rtnetlink.c (ffffffff81e5ac35)
Location: include/linux/netdevice.h:2982
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_event
```
```
In net/core/netdev-genl.c (ffffffff81e7d035)
Location: include/linux/netdevice.h:2982
Inline: True
Inline callers:
  - net/core/netdev-genl.c:netdev_genl_netdevice_event
```
```
In net/core/fib_rules.c (ffffffff81e876e5)
Location: include/linux/netdevice.h:2982
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_event
```
```
In net/core/drop_monitor.c (ffffffff81e99505)
Location: include/linux/netdevice.h:2982
Inline: True
Inline callers:
  - net/core/drop_monitor.c:dropmon_net_event
```
```
In net/core/netprio_cgroup.c (ffffffff81e9c645)
Location: include/linux/netdevice.h:2982
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:netprio_device_event
```
```
In net/core/failover.c (ffffffff81ea0352)
Location: include/linux/netdevice.h:2982
Inline: True
Inline callers:
  - net/core/failover.c:failover_event
```
```
In net/ethtool/netlink.c (ffffffff81ed8f88)
Location: include/linux/netdevice.h:2982
Inline: True
```
```
In net/ipv4/arp.c (ffffffff81f47b45)
Location: include/linux/netdevice.h:2982
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_netdev_event
```
```
In net/ipv4/devinet.c (ffffffff81f52445)
Location: include/linux/netdevice.h:2982
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
```
```
In net/ipv4/igmp.c (ffffffff81f57825)
Location: include/linux/netdevice.h:2982
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_netdev_event
```
```
In net/ipv4/fib_frontend.c (ffffffff81f5eaa5)
Location: include/linux/netdevice.h:2982
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_netdev_event
```
```
In net/ipv4/nexthop.c (ffffffff81f76655)
Location: include/linux/netdevice.h:2982
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_netdev_event
```
```
In net/ipv4/ipmr.c (ffffffff81f7d815)
Location: include/linux/netdevice.h:2982
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_device_event
```
```
In net/xfrm/xfrm_device.c (ffffffff81fa64d5)
Location: include/linux/netdevice.h:2982
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_event
```
```
In net/ipv6/addrconf.c (ffffffff81fc9975)
Location: include/linux/netdevice.h:2982
Inline: True
```
```
In net/ipv6/route.c (ffffffff81fd0b95)
Location: include/linux/netdevice.h:2982
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_dev_notify
```
```
In net/ipv6/ndisc.c (ffffffff81fe6025)
Location: include/linux/netdevice.h:2982
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_netdev_event
```
```
In net/ipv6/mcast.c (ffffffff81ff50c5)
Location: include/linux/netdevice.h:2982
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_netdev_event
```
```
In net/ipv6/ip6mr.c (ffffffff8200d7e5)
Location: include/linux/netdevice.h:2982
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_device_event
```
```
In net/packet/af_packet.c (ffffffff82027be5)
Location: include/linux/netdevice.h:2982
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_notifier
```
```
In net/devlink/leftover.c (ffffffff82041995)
Location: include/linux/netdevice.h:2982
Inline: True
Inline callers:
  - net/devlink/leftover.c:devlink_port_netdevice_event
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff82051c95)
Location: include/linux/netdevice.h:2982
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_netdev_handler
```
```
In net/dcb/dcbnl.c (ffffffff820589c5)
Location: include/linux/netdevice.h:2982
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_netdevice_event
```
```
In net/xdp/xsk.c (ffffffff82069ed5)
Location: include/linux/netdevice.h:2982
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_notifier
```
```
In net/mctp/device.c (ffffffff8208eab5)
Location: include/linux/netdevice.h:2982
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_dev_notify
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
In kernel/bpf/devmap.c (ffffffff81374e45)
Location: include/linux/netdevice.h:3060
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_notification
```
```
In security/selinux/netif.c (ffffffff816f4f85)
Location: include/linux/netdevice.h:3060
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_netdev_notifier_handler
```
```
In drivers/net/tun.c (ffffffff81cfb9d5)
Location: include/linux/netdevice.h:3060
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
```
```
In net/core/rtnetlink.c (ffffffff81f19ff5)
Location: include/linux/netdevice.h:3060
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_event
```
```
In net/core/netdev-genl.c (ffffffff81f3d7c5)
Location: include/linux/netdevice.h:3060
Inline: True
Inline callers:
  - net/core/netdev-genl.c:netdev_genl_netdevice_event
```
```
In net/core/page_pool_user.c (ffffffff81f45605)
Location: include/linux/netdevice.h:3060
Inline: True
Inline callers:
  - net/core/page_pool_user.c:page_pool_netdevice_event
```
```
In net/core/fib_rules.c (ffffffff81f496f5)
Location: include/linux/netdevice.h:3060
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_event
```
```
In net/core/drop_monitor.c (ffffffff81f5bbf5)
Location: include/linux/netdevice.h:3060
Inline: True
Inline callers:
  - net/core/drop_monitor.c:dropmon_net_event
```
```
In net/core/netprio_cgroup.c (ffffffff81f5edd5)
Location: include/linux/netdevice.h:3060
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:netprio_device_event
```
```
In net/core/failover.c (ffffffff81f62ac2)
Location: include/linux/netdevice.h:3060
Inline: True
Inline callers:
  - net/core/failover.c:failover_event
```
```
In net/ethtool/netlink.c (ffffffff81f9ce38)
Location: include/linux/netdevice.h:3060
Inline: True
```
```
In net/ipv4/arp.c (ffffffff8200dc85)
Location: include/linux/netdevice.h:3060
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_netdev_event
```
```
In net/ipv4/devinet.c (ffffffff82018725)
Location: include/linux/netdevice.h:3060
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
```
```
In net/ipv4/igmp.c (ffffffff8201dcb5)
Location: include/linux/netdevice.h:3060
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_netdev_event
```
```
In net/ipv4/fib_frontend.c (ffffffff82025075)
Location: include/linux/netdevice.h:3060
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_netdev_event
```
```
In net/ipv4/nexthop.c (ffffffff8203ce25)
Location: include/linux/netdevice.h:3060
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_netdev_event
```
```
In net/ipv4/ipmr.c (ffffffff82044055)
Location: include/linux/netdevice.h:3060
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_device_event
```
```
In net/xfrm/xfrm_device.c (ffffffff820737c5)
Location: include/linux/netdevice.h:3060
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_event
```
```
In net/ipv6/addrconf.c (ffffffff82097115)
Location: include/linux/netdevice.h:3060
Inline: True
```
```
In net/ipv6/route.c (ffffffff8209e485)
Location: include/linux/netdevice.h:3060
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_dev_notify
```
```
In net/ipv6/ndisc.c (ffffffff820b3e85)
Location: include/linux/netdevice.h:3060
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_netdev_event
```
```
In net/ipv6/mcast.c (ffffffff820c2c95)
Location: include/linux/netdevice.h:3060
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_netdev_event
```
```
In net/ipv6/ip6mr.c (ffffffff820dc7a5)
Location: include/linux/netdevice.h:3060
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_device_event
```
```
In net/packet/af_packet.c (ffffffff820f7445)
Location: include/linux/netdevice.h:3060
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_notifier
```
```
In net/devlink/port.c (ffffffff821081e5)
Location: include/linux/netdevice.h:3060
Inline: True
Inline callers:
  - net/devlink/port.c:devlink_port_netdevice_event
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff82124475)
Location: include/linux/netdevice.h:3060
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_netdev_handler
```
```
In net/dcb/dcbnl.c (ffffffff8212b515)
Location: include/linux/netdevice.h:3060
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_netdevice_event
```
```
In net/xdp/xsk.c (ffffffff8213d335)
Location: include/linux/netdevice.h:3060
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_notifier
```
```
In net/mctp/device.c (ffffffff82164fa5)
Location: include/linux/netdevice.h:3060
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_dev_notify
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
In kernel/bpf/devmap.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In security/selinux/netif.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/core/rtnetlink.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/core/drop_monitor.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/core/netprio_cgroup.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/ipv4/nexthop.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/xfrm/xfrm_device.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/xdp/xsk.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
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
In kernel/bpf/devmap.c (c04b7208)
Location: include/linux/netdevice.h:2541
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_notification
```
```
In security/selinux/netif.c (c070ccf8)
Location: include/linux/netdevice.h:2541
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_netdev_notifier_handler
```
```
In drivers/net/tun.c (c0ac6d98)
Location: include/linux/netdevice.h:2541
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_device_event
```
```
In net/core/rtnetlink.c (c0d0af74)
Location: include/linux/netdevice.h:2541
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_event
```
```
In net/core/fib_rules.c (c0d29d30)
Location: include/linux/netdevice.h:2541
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_event
```
```
In net/core/drop_monitor.c (c0d32be0)
Location: include/linux/netdevice.h:2541
Inline: True
Inline callers:
  - net/core/drop_monitor.c:dropmon_net_event
```
```
In net/core/netprio_cgroup.c (c0d34d7c)
Location: include/linux/netdevice.h:2541
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:netprio_device_event
```
```
In net/ipv4/arp.c (c0dae3fc)
Location: include/linux/netdevice.h:2541
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_netdev_event
```
```
In net/ipv4/devinet.c (c0db5820)
Location: include/linux/netdevice.h:2541
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
```
```
In net/ipv4/igmp.c (c0dbb9b8)
Location: include/linux/netdevice.h:2541
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_netdev_event
```
```
In net/ipv4/fib_frontend.c (c0dc11f4)
Location: include/linux/netdevice.h:2541
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_netdev_event
```
```
In net/ipv4/nexthop.c (c0dd0fd4)
Location: include/linux/netdevice.h:2541
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_netdev_event
```
```
In net/ipv4/ipmr.c (c0dd5820)
Location: include/linux/netdevice.h:2541
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_device_event
```
```
In net/xfrm/xfrm_device.c (c0df5ea0)
Location: include/linux/netdevice.h:2541
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_event
```
```
In net/ipv6/addrconf.c (c0e10178)
Location: include/linux/netdevice.h:2541
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_notify
```
```
In net/ipv6/route.c (c0e16554)
Location: include/linux/netdevice.h:2541
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_dev_notify
```
```
In net/ipv6/ndisc.c (c0e25d48)
Location: include/linux/netdevice.h:2541
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_netdev_event
```
```
In net/ipv6/mcast.c (c0e3401c)
Location: include/linux/netdevice.h:2541
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_netdev_event
```
```
In net/ipv6/ip6mr.c (c0e46448)
Location: include/linux/netdevice.h:2541
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_device_event
```
```
In net/packet/af_packet.c (c0e57a40)
Location: include/linux/netdevice.h:2541
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_notifier
```
```
In net/netlabel/netlabel_unlabeled.c (c0e660b8)
Location: include/linux/netdevice.h:2541
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_netdev_handler
```
```
In net/xdp/xsk.c (c0e78944)
Location: include/linux/netdevice.h:2541
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_notifier
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
In kernel/bpf/devmap.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In security/selinux/netif.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/core/rtnetlink.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/core/drop_monitor.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/core/netprio_cgroup.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/ipv4/nexthop.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/xfrm/xfrm_device.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/xdp/xsk.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
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
In kernel/bpf/devmap.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In security/selinux/netif.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/core/rtnetlink.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/core/drop_monitor.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/core/netprio_cgroup.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/ipv4/nexthop.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/xfrm/xfrm_device.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/xdp/xsk.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
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
In kernel/bpf/devmap.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In security/selinux/netif.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/core/rtnetlink.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/core/drop_monitor.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/core/netprio_cgroup.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/ipv4/nexthop.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/xfrm/xfrm_device.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/xdp/xsk.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
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
In kernel/bpf/devmap.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In security/selinux/netif.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In drivers/net/vxlan.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/core/rtnetlink.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/core/drop_monitor.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/core/netprio_cgroup.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/ipv4/nexthop.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/xfrm/xfrm_device.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/xdp/xsk.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
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
In kernel/bpf/devmap.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In security/selinux/netif.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/core/rtnetlink.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/core/drop_monitor.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/core/netprio_cgroup.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/netfilter/nfnetlink_queue.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/ipv4/nexthop.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/xfrm/xfrm_device.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/xdp/xsk.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
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
In kernel/bpf/devmap.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In security/selinux/netif.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/core/rtnetlink.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/core/drop_monitor.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/core/netprio_cgroup.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/ipv4/nexthop.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/xfrm/xfrm_device.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
```
In net/xdp/xsk.c (0)
Location: include/linux/netdevice.h:2541
Inline: True
```
</details>
</li>
</ul>

## Differences
