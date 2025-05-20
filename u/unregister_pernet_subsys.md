# Function: <code>unregister_pernet_subsys</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void unregister_pernet_subsys(struct pernet_operations *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff81710330)
Location: net/core/net_namespace.c:903
Inline: False
Direct callers:
  - net/core/fib_rules.c:fib_rules_init
  - net/netfilter/core.c:netfilter_init
  - net/ipv4/tcp_ipv4.c:tcp4_proc_exit
  - net/ipv4/raw.c:raw_proc_exit
  - net/ipv4/udp.c:udp4_proc_exit
  - net/ipv4/igmp.c:igmp_mc_init
  - net/ipv4/ping.c:ping_proc_exit
  - net/ipv4/ipmr.c:ip_mr_init
  - net/unix/af_unix.c:af_unix_exit
  - net/ipv6/addrconf.c:if6_proc_exit
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrlabel.c:ipv6_addr_label_cleanup
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ip6_fib.c:fib6_gc_cleanup
  - net/ipv6/ndisc.c:ndisc_init
  - net/ipv6/ndisc.c:ndisc_cleanup
  - net/ipv6/udplite.c:udplite6_proc_exit
  - net/ipv6/raw.c:raw6_proc_exit
  - net/ipv6/icmp.c:icmpv6_init
  - net/ipv6/icmp.c:icmpv6_cleanup
  - net/ipv6/mcast.c:igmp6_cleanup
  - net/ipv6/reassembly.c:ipv6_frag_exit
  - net/ipv6/tcp_ipv6.c:tcpv6_exit
  - net/ipv6/ping.c:pingv6_exit
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_unregister
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/ipv6/ip6mr.c:ip6_mr_cleanup
  - net/ipv6/xfrm6_policy.c:xfrm6_fini
  - net/ipv6/fib6_rules.c:fib6_rules_cleanup
  - net/ipv6/proc.c:ipv6_misc_proc_exit
  - net/packet/af_packet.c:packet_exit
```
**Symbols:**

```
ffffffff81710330-ffffffff81710360: unregister_pernet_subsys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void unregister_pernet_subsys(struct pernet_operations *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff81777c80)
Location: net/core/net_namespace.c:903
Inline: False
Direct callers:
  - net/core/fib_rules.c:fib_rules_init
  - net/sched/act_api.c:tcf_unregister_action
  - net/netfilter/core.c:netfilter_init
  - net/ipv4/tcp_ipv4.c:tcp4_proc_exit
  - net/ipv4/raw.c:raw_proc_exit
  - net/ipv4/udp.c:udp4_proc_exit
  - net/ipv4/igmp.c:igmp_mc_init
  - net/ipv4/ping.c:ping_proc_exit
  - net/ipv4/ipmr.c:ip_mr_init
  - net/unix/af_unix.c:af_unix_exit
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:if6_proc_exit
  - net/ipv6/addrlabel.c:ipv6_addr_label_cleanup
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_gc_cleanup
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ndisc.c:ndisc_cleanup
  - net/ipv6/ndisc.c:ndisc_init
  - net/ipv6/udplite.c:udplite6_proc_exit
  - net/ipv6/raw.c:raw6_proc_exit
  - net/ipv6/icmp.c:icmpv6_cleanup
  - net/ipv6/icmp.c:icmpv6_init
  - net/ipv6/mcast.c:igmp6_cleanup
  - net/ipv6/reassembly.c:ipv6_frag_exit
  - net/ipv6/tcp_ipv6.c:tcpv6_exit
  - net/ipv6/ping.c:pingv6_exit
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_unregister
  - net/ipv6/ip6mr.c:ip6_mr_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/ipv6/xfrm6_policy.c:xfrm6_fini
  - net/ipv6/fib6_rules.c:fib6_rules_cleanup
  - net/ipv6/proc.c:ipv6_misc_proc_exit
  - net/packet/af_packet.c:packet_exit
```
**Symbols:**

```
ffffffff81777c80-ffffffff81777cb0: unregister_pernet_subsys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void unregister_pernet_subsys(struct pernet_operations *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff817a4c50)
Location: net/core/net_namespace.c:943
Inline: False
Direct callers:
  - net/core/fib_rules.c:fib_rules_init
  - net/sched/act_api.c:tcf_unregister_action
  - net/netfilter/core.c:netfilter_init
  - net/ipv4/tcp_ipv4.c:tcp4_proc_exit
  - net/ipv4/raw.c:raw_proc_exit
  - net/ipv4/udp.c:udp4_proc_exit
  - net/ipv4/igmp.c:igmp_mc_init
  - net/ipv4/ping.c:ping_proc_exit
  - net/ipv4/ipmr.c:ip_mr_init
  - net/unix/af_unix.c:af_unix_exit
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:if6_proc_exit
  - net/ipv6/addrlabel.c:ipv6_addr_label_cleanup
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_gc_cleanup
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ndisc.c:ndisc_cleanup
  - net/ipv6/ndisc.c:ndisc_init
  - net/ipv6/udplite.c:udplite6_proc_exit
  - net/ipv6/raw.c:raw6_proc_exit
  - net/ipv6/icmp.c:icmpv6_cleanup
  - net/ipv6/icmp.c:icmpv6_init
  - net/ipv6/mcast.c:igmp6_cleanup
  - net/ipv6/reassembly.c:ipv6_frag_exit
  - net/ipv6/tcp_ipv6.c:tcpv6_exit
  - net/ipv6/ping.c:pingv6_exit
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup
  - net/ipv6/seg6.c:seg6_exit
  - net/ipv6/seg6.c:seg6_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_unregister
  - net/ipv6/ip6mr.c:ip6_mr_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/ipv6/xfrm6_policy.c:xfrm6_fini
  - net/ipv6/fib6_rules.c:fib6_rules_cleanup
  - net/ipv6/proc.c:ipv6_misc_proc_exit
  - net/packet/af_packet.c:packet_exit
```
**Symbols:**

```
ffffffff817a4c50-ffffffff817a4c80: unregister_pernet_subsys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void unregister_pernet_subsys(struct pernet_operations *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff817c2e80)
Location: net/core/net_namespace.c:1009
Inline: False
Direct callers:
  - net/core/fib_rules.c:fib_rules_init
  - net/netfilter/core.c:netfilter_init
  - net/ipv4/tcp_ipv4.c:tcp4_proc_exit
  - net/ipv4/raw.c:raw_proc_exit
  - net/ipv4/udp.c:udp4_proc_exit
  - net/ipv4/igmp.c:igmp_mc_init
  - net/ipv4/ping.c:ping_proc_exit
  - net/ipv4/ipmr.c:ip_mr_init
  - net/unix/af_unix.c:af_unix_exit
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:if6_proc_exit
  - net/ipv6/addrlabel.c:ipv6_addr_label_cleanup
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_gc_cleanup
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ndisc.c:ndisc_cleanup
  - net/ipv6/ndisc.c:ndisc_init
  - net/ipv6/udplite.c:udplite6_proc_exit
  - net/ipv6/raw.c:raw6_proc_exit
  - net/ipv6/icmp.c:icmpv6_cleanup
  - net/ipv6/icmp.c:icmpv6_init
  - net/ipv6/mcast.c:igmp6_cleanup
  - net/ipv6/reassembly.c:ipv6_frag_exit
  - net/ipv6/tcp_ipv6.c:tcpv6_exit
  - net/ipv6/ping.c:pingv6_exit
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup
  - net/ipv6/seg6.c:seg6_exit
  - net/ipv6/seg6.c:seg6_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_unregister
  - net/ipv6/ip6mr.c:ip6_mr_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/ipv6/xfrm6_policy.c:xfrm6_fini
  - net/ipv6/fib6_rules.c:fib6_rules_cleanup
  - net/ipv6/proc.c:ipv6_misc_proc_exit
  - net/packet/af_packet.c:packet_exit
```
**Symbols:**

```
ffffffff817c2e80-ffffffff817c2eb0: unregister_pernet_subsys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void unregister_pernet_subsys(struct pernet_operations *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff8183c5b0)
Location: net/core/net_namespace.c:1011
Inline: False
Direct callers:
  - net/core/fib_rules.c:fib_rules_init
  - net/netfilter/core.c:netfilter_init
  - net/ipv4/tcp_ipv4.c:tcp4_proc_exit
  - net/ipv4/raw.c:raw_proc_exit
  - net/ipv4/udp.c:udp4_proc_exit
  - net/ipv4/igmp.c:igmp_mc_init
  - net/ipv4/ping.c:ping_proc_exit
  - net/ipv4/ipmr.c:ip_mr_init
  - net/unix/af_unix.c:af_unix_exit
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:if6_proc_exit
  - net/ipv6/addrlabel.c:ipv6_addr_label_cleanup
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_gc_cleanup
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ndisc.c:ndisc_cleanup
  - net/ipv6/ndisc.c:ndisc_init
  - net/ipv6/udplite.c:udplite6_proc_exit
  - net/ipv6/raw.c:raw6_proc_exit
  - net/ipv6/icmp.c:icmpv6_cleanup
  - net/ipv6/icmp.c:icmpv6_init
  - net/ipv6/mcast.c:igmp6_cleanup
  - net/ipv6/reassembly.c:ipv6_frag_exit
  - net/ipv6/tcp_ipv6.c:tcpv6_exit
  - net/ipv6/ping.c:pingv6_exit
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup
  - net/ipv6/seg6.c:seg6_exit
  - net/ipv6/seg6.c:seg6_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_unregister
  - net/ipv6/ip6mr.c:ip6_mr_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/ipv6/xfrm6_policy.c:xfrm6_fini
  - net/ipv6/fib6_rules.c:fib6_rules_cleanup
  - net/ipv6/proc.c:ipv6_misc_proc_exit
  - net/packet/af_packet.c:packet_exit
```
**Symbols:**

```
ffffffff8183c5b0-ffffffff8183c5e0: unregister_pernet_subsys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void unregister_pernet_subsys(struct pernet_operations *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff81886b20)
Location: net/core/net_namespace.c:1071
Inline: False
Direct callers:
  - net/core/fib_rules.c:fib_rules_init
  - net/sched/act_api.c:tcf_unregister_action
  - net/netfilter/core.c:netfilter_init
  - net/ipv4/tcp_ipv4.c:tcp4_proc_exit
  - net/ipv4/raw.c:raw_proc_exit
  - net/ipv4/udp.c:udp4_proc_exit
  - net/ipv4/igmp.c:igmp_mc_init
  - net/ipv4/ping.c:ping_proc_exit
  - net/ipv4/ipmr.c:ip_mr_init
  - net/unix/af_unix.c:af_unix_exit
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:if6_proc_exit
  - net/ipv6/addrlabel.c:ipv6_addr_label_cleanup
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_gc_cleanup
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ndisc.c:ndisc_cleanup
  - net/ipv6/ndisc.c:ndisc_init
  - net/ipv6/udplite.c:udplite6_proc_exit
  - net/ipv6/raw.c:raw6_proc_exit
  - net/ipv6/icmp.c:icmpv6_cleanup
  - net/ipv6/icmp.c:icmpv6_init
  - net/ipv6/mcast.c:igmp6_cleanup
  - net/ipv6/reassembly.c:ipv6_frag_exit
  - net/ipv6/tcp_ipv6.c:tcpv6_exit
  - net/ipv6/ping.c:pingv6_exit
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup
  - net/ipv6/seg6.c:seg6_exit
  - net/ipv6/seg6.c:seg6_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_unregister
  - net/ipv6/ip6mr.c:ip6_mr_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/ipv6/xfrm6_policy.c:xfrm6_fini
  - net/ipv6/fib6_rules.c:fib6_rules_cleanup
  - net/ipv6/proc.c:ipv6_misc_proc_exit
  - net/packet/af_packet.c:packet_exit
  - net/wireless/wext-core.c:wireless_nlevent_init
```
**Symbols:**

```
ffffffff81886b20-ffffffff81886b50: unregister_pernet_subsys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void unregister_pernet_subsys(struct pernet_operations *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff818a7210)
Location: net/core/net_namespace.c:1181
Inline: False
Direct callers:
  - net/core/fib_rules.c:fib_rules_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/act_api.c:tcf_unregister_action
  - net/netfilter/core.c:netfilter_init
  - net/ipv4/tcp_ipv4.c:tcp4_proc_exit
  - net/ipv4/raw.c:raw_proc_exit
  - net/ipv4/udp.c:udp4_proc_exit
  - net/ipv4/igmp.c:igmp_mc_init
  - net/ipv4/ping.c:ping_proc_exit
  - net/ipv4/ipmr.c:ip_mr_init
  - net/unix/af_unix.c:af_unix_exit
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:if6_proc_exit
  - net/ipv6/addrlabel.c:ipv6_addr_label_cleanup
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_gc_cleanup
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ndisc.c:ndisc_cleanup
  - net/ipv6/ndisc.c:ndisc_init
  - net/ipv6/udplite.c:udplite6_proc_exit
  - net/ipv6/raw.c:raw6_proc_exit
  - net/ipv6/icmp.c:icmpv6_cleanup
  - net/ipv6/icmp.c:icmpv6_init
  - net/ipv6/mcast.c:igmp6_cleanup
  - net/ipv6/reassembly.c:ipv6_frag_exit
  - net/ipv6/tcp_ipv6.c:tcpv6_exit
  - net/ipv6/ping.c:pingv6_exit
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup
  - net/ipv6/seg6.c:seg6_exit
  - net/ipv6/seg6.c:seg6_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_unregister
  - net/ipv6/ip6mr.c:ip6_mr_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/ipv6/xfrm6_policy.c:xfrm6_fini
  - net/ipv6/fib6_rules.c:fib6_rules_cleanup
  - net/ipv6/proc.c:ipv6_misc_proc_exit
  - net/packet/af_packet.c:packet_exit
  - net/wireless/wext-core.c:wireless_nlevent_init
```
**Symbols:**

```
ffffffff818a7210-ffffffff818a7240: unregister_pernet_subsys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void unregister_pernet_subsys(struct pernet_operations *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff818f2940)
Location: net/core/net_namespace.c:1268
Inline: False
Direct callers:
  - net/core/fib_rules.c:fib_rules_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/act_api.c:tcf_unregister_action
  - net/netfilter/core.c:netfilter_init
  - net/ipv4/tcp_ipv4.c:tcp4_proc_exit
  - net/ipv4/raw.c:raw_proc_exit
  - net/ipv4/udp.c:udp4_proc_exit
  - net/ipv4/igmp.c:igmp_mc_init
  - net/ipv4/ping.c:ping_proc_exit
  - net/ipv4/ipmr.c:ip_mr_init
  - net/unix/af_unix.c:af_unix_exit
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:if6_proc_exit
  - net/ipv6/addrlabel.c:ipv6_addr_label_cleanup
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_gc_cleanup
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ndisc.c:ndisc_cleanup
  - net/ipv6/ndisc.c:ndisc_init
  - net/ipv6/udplite.c:udplite6_proc_exit
  - net/ipv6/raw.c:raw6_proc_exit
  - net/ipv6/icmp.c:icmpv6_cleanup
  - net/ipv6/icmp.c:icmpv6_init
  - net/ipv6/mcast.c:igmp6_cleanup
  - net/ipv6/reassembly.c:ipv6_frag_exit
  - net/ipv6/tcp_ipv6.c:tcpv6_exit
  - net/ipv6/ping.c:pingv6_exit
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup
  - net/ipv6/seg6.c:seg6_exit
  - net/ipv6/seg6.c:seg6_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_unregister
  - net/ipv6/ip6mr.c:ip6_mr_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/ipv6/xfrm6_policy.c:xfrm6_fini
  - net/ipv6/fib6_rules.c:fib6_rules_cleanup
  - net/ipv6/proc.c:ipv6_misc_proc_exit
  - net/packet/af_packet.c:packet_init
  - net/packet/af_packet.c:packet_exit
  - net/wireless/wext-core.c:wireless_nlevent_init
  - net/xdp/xsk.c:xsk_init
```
**Symbols:**

```
ffffffff818f2940-ffffffff818f2972: unregister_pernet_subsys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void unregister_pernet_subsys(struct pernet_operations *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff819248a0)
Location: net/core/net_namespace.c:1275
Inline: False
Direct callers:
  - net/core/fib_rules.c:fib_rules_init
  - net/sched/act_api.c:tcf_unregister_action
  - net/netfilter/core.c:netfilter_init
  - net/ipv4/tcp_ipv4.c:tcp4_proc_exit
  - net/ipv4/raw.c:raw_proc_exit
  - net/ipv4/udp.c:udp4_proc_exit
  - net/ipv4/igmp.c:igmp_mc_init
  - net/ipv4/ping.c:ping_proc_exit
  - net/ipv4/ipmr.c:ip_mr_init
  - net/unix/af_unix.c:af_unix_exit
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:if6_proc_exit
  - net/ipv6/addrlabel.c:ipv6_addr_label_cleanup
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_gc_cleanup
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ndisc.c:ndisc_cleanup
  - net/ipv6/ndisc.c:ndisc_init
  - net/ipv6/udplite.c:udplite6_proc_exit
  - net/ipv6/raw.c:raw6_proc_exit
  - net/ipv6/icmp.c:icmpv6_cleanup
  - net/ipv6/icmp.c:icmpv6_init
  - net/ipv6/mcast.c:igmp6_cleanup
  - net/ipv6/reassembly.c:ipv6_frag_exit
  - net/ipv6/tcp_ipv6.c:tcpv6_exit
  - net/ipv6/ping.c:pingv6_exit
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup
  - net/ipv6/seg6.c:seg6_exit
  - net/ipv6/seg6.c:seg6_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_unregister
  - net/ipv6/ip6mr.c:ip6_mr_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/ipv6/xfrm6_policy.c:xfrm6_fini
  - net/ipv6/fib6_rules.c:fib6_rules_cleanup
  - net/ipv6/proc.c:ipv6_misc_proc_exit
  - net/packet/af_packet.c:packet_init
  - net/packet/af_packet.c:packet_exit
  - net/wireless/wext-core.c:wireless_nlevent_init
  - net/xdp/xsk.c:xsk_init
```
**Symbols:**

```
ffffffff819248a0-ffffffff819248d2: unregister_pernet_subsys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void unregister_pernet_subsys(struct pernet_operations *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff819f88a0)
Location: net/core/net_namespace.c:1273
Inline: False
Direct callers:
  - net/core/fib_rules.c:fib_rules_init
  - net/sched/act_api.c:tcf_unregister_action
  - net/sched/act_api.c:tcf_register_action
  - net/netfilter/core.c:netfilter_init
  - net/ipv4/tcp_ipv4.c:tcp4_proc_exit
  - net/ipv4/raw.c:raw_proc_exit
  - net/ipv4/udp.c:udp4_proc_exit
  - net/ipv4/igmp.c:igmp_mc_init
  - net/ipv4/ping.c:ping_proc_exit
  - net/ipv4/ipmr.c:ip_mr_init
  - net/unix/af_unix.c:af_unix_exit
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:if6_proc_exit
  - net/ipv6/addrlabel.c:ipv6_addr_label_cleanup
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_gc_cleanup
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ndisc.c:ndisc_cleanup
  - net/ipv6/ndisc.c:ndisc_init
  - net/ipv6/udplite.c:udplite6_proc_exit
  - net/ipv6/raw.c:raw6_proc_exit
  - net/ipv6/icmp.c:icmpv6_cleanup
  - net/ipv6/icmp.c:icmpv6_init
  - net/ipv6/mcast.c:igmp6_cleanup
  - net/ipv6/reassembly.c:ipv6_frag_exit
  - net/ipv6/tcp_ipv6.c:tcpv6_exit
  - net/ipv6/tcp_ipv6.c:tcpv6_init
  - net/ipv6/ping.c:pingv6_exit
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup
  - net/ipv6/seg6.c:seg6_exit
  - net/ipv6/seg6.c:seg6_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_unregister
  - net/ipv6/ip6mr.c:ip6_mr_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/ipv6/xfrm6_policy.c:xfrm6_fini
  - net/ipv6/fib6_rules.c:fib6_rules_cleanup
  - net/ipv6/proc.c:ipv6_misc_proc_exit
  - net/packet/af_packet.c:packet_init
  - net/packet/af_packet.c:packet_exit
  - net/wireless/wext-core.c:wireless_nlevent_init
  - net/xdp/xsk.c:xsk_init
```
**Symbols:**

```
ffffffff819f88a0-ffffffff819f88d4: unregister_pernet_subsys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void unregister_pernet_subsys(struct pernet_operations *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff819f83c0)
Location: net/core/net_namespace.c:1277
Inline: False
Direct callers:
  - net/core/fib_rules.c:fib_rules_init
  - net/sched/act_api.c:tcf_unregister_action
  - net/sched/act_api.c:tcf_register_action
  - net/netfilter/core.c:netfilter_init
  - net/ipv4/tcp_ipv4.c:tcp4_proc_exit
  - net/ipv4/raw.c:raw_proc_exit
  - net/ipv4/udp.c:udp4_proc_exit
  - net/ipv4/igmp.c:igmp_mc_init
  - net/ipv4/ping.c:ping_proc_exit
  - net/ipv4/ipmr.c:ip_mr_init
  - net/unix/af_unix.c:af_unix_exit
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:if6_proc_exit
  - net/ipv6/addrlabel.c:ipv6_addr_label_cleanup
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_gc_cleanup
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ndisc.c:ndisc_cleanup
  - net/ipv6/ndisc.c:ndisc_init
  - net/ipv6/udplite.c:udplite6_proc_exit
  - net/ipv6/raw.c:raw6_proc_exit
  - net/ipv6/icmp.c:icmpv6_cleanup
  - net/ipv6/icmp.c:icmpv6_init
  - net/ipv6/mcast.c:igmp6_cleanup
  - net/ipv6/reassembly.c:ipv6_frag_exit
  - net/ipv6/tcp_ipv6.c:tcpv6_exit
  - net/ipv6/tcp_ipv6.c:tcpv6_init
  - net/ipv6/ping.c:pingv6_exit
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup
  - net/ipv6/seg6.c:seg6_exit
  - net/ipv6/seg6.c:seg6_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_unregister
  - net/ipv6/ip6mr.c:ip6_mr_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/ipv6/xfrm6_policy.c:xfrm6_fini
  - net/ipv6/fib6_rules.c:fib6_rules_cleanup
  - net/ipv6/proc.c:ipv6_misc_proc_exit
  - net/packet/af_packet.c:packet_init
  - net/packet/af_packet.c:packet_exit
  - net/wireless/wext-core.c:wireless_nlevent_init
  - net/xdp/xsk.c:xsk_init
```
**Symbols:**

```
ffffffff819f83c0-ffffffff819f83f4: unregister_pernet_subsys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void unregister_pernet_subsys(struct pernet_operations *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff819debc0)
Location: net/core/net_namespace.c:1270
Inline: False
Direct callers:
  - net/core/fib_rules.c:fib_rules_init
  - net/sched/act_api.c:tcf_unregister_action
  - net/sched/act_api.c:tcf_register_action
  - net/netfilter/core.c:netfilter_init
  - net/ipv4/tcp_ipv4.c:tcp4_proc_exit
  - net/ipv4/raw.c:raw_proc_exit
  - net/ipv4/udp.c:udp4_proc_exit
  - net/ipv4/igmp.c:igmp_mc_init
  - net/ipv4/ping.c:ping_proc_exit
  - net/ipv4/ipmr.c:ip_mr_init
  - net/unix/af_unix.c:af_unix_exit
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:if6_proc_exit
  - net/ipv6/addrlabel.c:ipv6_addr_label_cleanup
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_gc_cleanup
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ndisc.c:ndisc_cleanup
  - net/ipv6/ndisc.c:ndisc_init
  - net/ipv6/udplite.c:udplite6_proc_exit
  - net/ipv6/raw.c:raw6_proc_exit
  - net/ipv6/icmp.c:icmpv6_cleanup
  - net/ipv6/icmp.c:icmpv6_init
  - net/ipv6/mcast.c:igmp6_cleanup
  - net/ipv6/mcast.c:igmp6_init
  - net/ipv6/reassembly.c:ipv6_frag_exit
  - net/ipv6/tcp_ipv6.c:tcpv6_exit
  - net/ipv6/tcp_ipv6.c:tcpv6_init
  - net/ipv6/ping.c:pingv6_exit
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup
  - net/ipv6/seg6.c:seg6_exit
  - net/ipv6/seg6.c:seg6_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_unregister
  - net/ipv6/ip6mr.c:ip6_mr_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/ipv6/xfrm6_policy.c:xfrm6_fini
  - net/ipv6/fib6_rules.c:fib6_rules_cleanup
  - net/ipv6/proc.c:ipv6_misc_proc_exit
  - net/packet/af_packet.c:packet_init
  - net/packet/af_packet.c:packet_exit
  - net/wireless/wext-core.c:wireless_nlevent_init
  - net/xdp/xsk.c:xsk_init
```
**Symbols:**

```
ffffffff819debc0-ffffffff819debf4: unregister_pernet_subsys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void unregister_pernet_subsys(struct pernet_operations *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff81a8ee90)
Location: net/core/net_namespace.c:1272
Inline: False
Direct callers:
  - net/core/fib_rules.c:fib_rules_init
  - net/sched/act_api.c:tcf_unregister_action
  - net/sched/act_api.c:tcf_register_action
  - net/netfilter/core.c:netfilter_init
  - net/ipv4/tcp_ipv4.c:tcp4_proc_exit
  - net/ipv4/raw.c:raw_proc_exit
  - net/ipv4/udp.c:udp4_proc_exit
  - net/ipv4/igmp.c:igmp_mc_init
  - net/ipv4/ping.c:ping_proc_exit
  - net/ipv4/ipmr.c:ip_mr_init
  - net/unix/af_unix.c:af_unix_exit
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:if6_proc_exit
  - net/ipv6/addrlabel.c:ipv6_addr_label_cleanup
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_gc_cleanup
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ndisc.c:ndisc_cleanup
  - net/ipv6/ndisc.c:ndisc_init
  - net/ipv6/udplite.c:udplite6_proc_exit
  - net/ipv6/raw.c:raw6_proc_exit
  - net/ipv6/icmp.c:icmpv6_cleanup
  - net/ipv6/icmp.c:icmpv6_init
  - net/ipv6/mcast.c:igmp6_cleanup
  - net/ipv6/mcast.c:igmp6_init
  - net/ipv6/reassembly.c:ipv6_frag_exit
  - net/ipv6/tcp_ipv6.c:tcpv6_exit
  - net/ipv6/tcp_ipv6.c:tcpv6_init
  - net/ipv6/ping.c:pingv6_exit
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup
  - net/ipv6/seg6.c:seg6_exit
  - net/ipv6/seg6.c:seg6_init
  - net/ipv6/ioam6.c:ioam6_exit
  - net/ipv6/ioam6.c:ioam6_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_unregister
  - net/ipv6/ip6mr.c:ip6_mr_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/ipv6/xfrm6_policy.c:xfrm6_fini
  - net/ipv6/fib6_rules.c:fib6_rules_cleanup
  - net/ipv6/proc.c:ipv6_misc_proc_exit
  - net/packet/af_packet.c:packet_init
  - net/packet/af_packet.c:packet_exit
  - net/wireless/wext-core.c:wireless_nlevent_init
  - net/xdp/xsk.c:xsk_init
```
**Symbols:**

```
ffffffff81a8ee90-ffffffff81a8eec4: unregister_pernet_subsys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void unregister_pernet_subsys(struct pernet_operations *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff81c04bd0)
Location: net/core/net_namespace.c:1271
Inline: False
Direct callers:
  - net/core/fib_rules.c:fib_rules_init
  - net/sched/act_api.c:tcf_register_action
  - net/netfilter/core.c:netfilter_init
  - net/ipv4/tcp_ipv4.c:tcp4_proc_exit
  - net/ipv4/raw.c:raw_proc_exit
  - net/ipv4/udp.c:udp4_proc_exit
  - net/ipv4/igmp.c:igmp_mc_init
  - net/ipv4/ping.c:ping_proc_exit
  - net/ipv4/ipmr.c:ip_mr_init
  - net/unix/af_unix.c:af_unix_exit
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:if6_proc_exit
  - net/ipv6/addrlabel.c:ipv6_addr_label_cleanup
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_gc_cleanup
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ndisc.c:ndisc_cleanup
  - net/ipv6/ndisc.c:ndisc_init
  - net/ipv6/udplite.c:udplite6_proc_exit
  - net/ipv6/raw.c:raw6_proc_exit
  - net/ipv6/mcast.c:igmp6_cleanup
  - net/ipv6/mcast.c:igmp6_init
  - net/ipv6/reassembly.c:ipv6_frag_exit
  - net/ipv6/tcp_ipv6.c:tcpv6_exit
  - net/ipv6/tcp_ipv6.c:tcpv6_init
  - net/ipv6/ping.c:pingv6_exit
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup
  - net/ipv6/seg6.c:seg6_exit
  - net/ipv6/seg6.c:seg6_init
  - net/ipv6/ioam6.c:ioam6_exit
  - net/ipv6/ioam6.c:ioam6_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_unregister
  - net/ipv6/ip6mr.c:ip6_mr_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/ipv6/xfrm6_policy.c:xfrm6_fini
  - net/ipv6/fib6_rules.c:fib6_rules_cleanup
  - net/ipv6/proc.c:ipv6_misc_proc_exit
  - net/packet/af_packet.c:packet_init
  - net/packet/af_packet.c:packet_exit
  - net/wireless/wext-core.c:wireless_nlevent_init
  - net/xdp/xsk.c:xsk_init
  - net/mctp/route.c:mctp_routes_exit
  - net/mctp/neigh.c:mctp_neigh_exit
```
**Symbols:**

```
ffffffff81c04bd0-ffffffff81c04c09: unregister_pernet_subsys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void unregister_pernet_subsys(struct pernet_operations *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff81db43e0)
Location: net/core/net_namespace.c:1291
Inline: False
Direct callers:
  - net/core/fib_rules.c:fib_rules_init
  - net/netfilter/core.c:netfilter_init
  - net/ipv4/tcp_ipv4.c:tcp4_proc_exit
  - net/ipv4/raw.c:raw_proc_exit
  - net/ipv4/udp.c:udp4_proc_exit
  - net/ipv4/igmp.c:igmp_mc_init
  - net/ipv4/ping.c:ping_proc_exit
  - net/ipv4/ipmr.c:ip_mr_init
  - net/unix/af_unix.c:af_unix_exit
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:if6_proc_exit
  - net/ipv6/addrlabel.c:ipv6_addr_label_cleanup
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_gc_cleanup
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ndisc.c:ndisc_cleanup
  - net/ipv6/ndisc.c:ndisc_init
  - net/ipv6/udplite.c:udplite6_proc_exit
  - net/ipv6/raw.c:raw6_proc_exit
  - net/ipv6/mcast.c:igmp6_cleanup
  - net/ipv6/mcast.c:igmp6_init
  - net/ipv6/reassembly.c:ipv6_frag_exit
  - net/ipv6/tcp_ipv6.c:tcpv6_exit
  - net/ipv6/tcp_ipv6.c:tcpv6_init
  - net/ipv6/ping.c:pingv6_exit
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup
  - net/ipv6/seg6.c:seg6_exit
  - net/ipv6/seg6.c:seg6_init
  - net/ipv6/ioam6.c:ioam6_exit
  - net/ipv6/ioam6.c:ioam6_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_unregister
  - net/ipv6/ip6mr.c:ip6_mr_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/ipv6/xfrm6_policy.c:xfrm6_fini
  - net/ipv6/fib6_rules.c:fib6_rules_cleanup
  - net/ipv6/proc.c:ipv6_misc_proc_exit
  - net/packet/af_packet.c:packet_init
  - net/packet/af_packet.c:packet_exit
  - net/wireless/wext-core.c:wireless_nlevent_init
  - net/xdp/xsk.c:xsk_init
  - net/mctp/route.c:mctp_routes_exit
  - net/mctp/neigh.c:mctp_neigh_exit
```
**Symbols:**

```
ffffffff81db43e0-ffffffff81db4419: unregister_pernet_subsys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void unregister_pernet_subsys(struct pernet_operations *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff81e24a90)
Location: net/core/net_namespace.c:1290
Inline: False
Direct callers:
  - net/core/fib_rules.c:fib_rules_init
  - net/netfilter/core.c:netfilter_init
  - net/ipv4/tcp_ipv4.c:tcp4_proc_exit
  - net/ipv4/raw.c:raw_proc_exit
  - net/ipv4/udp.c:udp4_proc_exit
  - net/ipv4/igmp.c:igmp_mc_init
  - net/ipv4/ping.c:ping_proc_exit
  - net/ipv4/ipmr.c:ip_mr_init
  - net/unix/af_unix.c:af_unix_exit
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:if6_proc_exit
  - net/ipv6/addrlabel.c:ipv6_addr_label_cleanup
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_gc_cleanup
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ndisc.c:ndisc_cleanup
  - net/ipv6/ndisc.c:ndisc_init
  - net/ipv6/udplite.c:udplite6_proc_exit
  - net/ipv6/raw.c:raw6_proc_exit
  - net/ipv6/mcast.c:igmp6_cleanup
  - net/ipv6/mcast.c:igmp6_init
  - net/ipv6/reassembly.c:ipv6_frag_exit
  - net/ipv6/tcp_ipv6.c:tcpv6_exit
  - net/ipv6/tcp_ipv6.c:tcpv6_init
  - net/ipv6/ping.c:pingv6_exit
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup
  - net/ipv6/seg6.c:seg6_exit
  - net/ipv6/seg6.c:seg6_init
  - net/ipv6/ioam6.c:ioam6_exit
  - net/ipv6/ioam6.c:ioam6_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_unregister
  - net/ipv6/ip6mr.c:ip6_mr_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/ipv6/xfrm6_policy.c:xfrm6_fini
  - net/ipv6/fib6_rules.c:fib6_rules_cleanup
  - net/ipv6/proc.c:ipv6_misc_proc_exit
  - net/packet/af_packet.c:packet_init
  - net/packet/af_packet.c:packet_exit
  - net/wireless/wext-core.c:wireless_nlevent_init
  - net/xdp/xsk.c:xsk_init
  - net/mctp/route.c:mctp_routes_exit
  - net/mctp/neigh.c:mctp_neigh_exit
  - net/handshake/netlink.c:handshake_exit
```
**Symbols:**

```
ffffffff81e24a90-ffffffff81e24ac9: unregister_pernet_subsys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void unregister_pernet_subsys(struct pernet_operations *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff81ee29f0)
Location: net/core/net_namespace.c:1339
Inline: False
Direct callers:
  - net/core/fib_rules.c:fib_rules_init
  - net/netfilter/core.c:netfilter_init
  - net/ipv4/tcp_ipv4.c:tcp4_proc_exit
  - net/ipv4/raw.c:raw_proc_exit
  - net/ipv4/udp.c:udp4_proc_exit
  - net/ipv4/igmp.c:igmp_mc_init
  - net/ipv4/ping.c:ping_proc_exit
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:if6_proc_exit
  - net/ipv6/addrlabel.c:ipv6_addr_label_cleanup
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_gc_cleanup
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ndisc.c:ndisc_cleanup
  - net/ipv6/ndisc.c:ndisc_init
  - net/ipv6/udplite.c:udplite6_proc_exit
  - net/ipv6/raw.c:raw6_proc_exit
  - net/ipv6/mcast.c:igmp6_cleanup
  - net/ipv6/mcast.c:igmp6_init
  - net/ipv6/reassembly.c:ipv6_frag_exit
  - net/ipv6/tcp_ipv6.c:tcpv6_exit
  - net/ipv6/tcp_ipv6.c:tcpv6_init
  - net/ipv6/ping.c:pingv6_exit
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup
  - net/ipv6/seg6.c:seg6_exit
  - net/ipv6/seg6.c:seg6_init
  - net/ipv6/ioam6.c:ioam6_exit
  - net/ipv6/ioam6.c:ioam6_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_unregister
  - net/ipv6/ip6mr.c:ip6_mr_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/ipv6/xfrm6_policy.c:xfrm6_fini
  - net/ipv6/fib6_rules.c:fib6_rules_cleanup
  - net/ipv6/proc.c:ipv6_misc_proc_exit
  - net/packet/af_packet.c:packet_init
  - net/packet/af_packet.c:packet_exit
  - net/devlink/core.c:devlink_init
  - net/wireless/wext-core.c:wireless_nlevent_init
  - net/xdp/xsk.c:xsk_init
  - net/mctp/route.c:mctp_routes_exit
  - net/mctp/neigh.c:mctp_neigh_exit
  - net/handshake/netlink.c:handshake_exit
```
**Symbols:**

```
ffffffff81ee29f0-ffffffff81ee2a29: unregister_pernet_subsys (STB_GLOBAL)
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
void unregister_pernet_subsys(struct pernet_operations *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffff800010bc02f8)
Location: net/core/net_namespace.c:1275
Inline: False
Direct callers:
  - net/core/fib_rules.c:fib_rules_init
  - net/sched/act_api.c:tcf_unregister_action
  - net/netfilter/core.c:netfilter_init
  - net/ipv4/tcp_ipv4.c:tcp4_proc_exit
  - net/ipv4/raw.c:raw_proc_exit
  - net/ipv4/udp.c:udp4_proc_exit
  - net/ipv4/igmp.c:igmp_mc_init
  - net/ipv4/ping.c:ping_proc_exit
  - net/ipv4/ipmr.c:ip_mr_init
  - net/unix/af_unix.c:af_unix_exit
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:if6_proc_exit
  - net/ipv6/addrlabel.c:ipv6_addr_label_cleanup
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_gc_cleanup
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ndisc.c:ndisc_cleanup
  - net/ipv6/ndisc.c:ndisc_init
  - net/ipv6/udplite.c:udplite6_proc_exit
  - net/ipv6/raw.c:raw6_proc_exit
  - net/ipv6/icmp.c:icmpv6_cleanup
  - net/ipv6/icmp.c:icmpv6_init
  - net/ipv6/mcast.c:igmp6_cleanup
  - net/ipv6/reassembly.c:ipv6_frag_exit
  - net/ipv6/tcp_ipv6.c:tcpv6_exit
  - net/ipv6/ping.c:pingv6_exit
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup
  - net/ipv6/seg6.c:seg6_exit
  - net/ipv6/seg6.c:seg6_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_unregister
  - net/ipv6/ip6mr.c:ip6_mr_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/ipv6/xfrm6_policy.c:xfrm6_fini
  - net/ipv6/fib6_rules.c:fib6_rules_cleanup
  - net/ipv6/proc.c:ipv6_misc_proc_exit
  - net/packet/af_packet.c:packet_init
  - net/packet/af_packet.c:packet_exit
  - net/wireless/wext-core.c:wireless_nlevent_init
  - net/xdp/xsk.c:xsk_init
```
**Symbols:**

```
ffff800010bc02f8-ffff800010bc033c: unregister_pernet_subsys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void unregister_pernet_subsys(struct pernet_operations *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (c0cdbdd4)
Location: net/core/net_namespace.c:1275
Inline: False
Direct callers:
  - net/core/fib_rules.c:fib_rules_init
  - net/sched/act_api.c:tcf_unregister_action
  - net/netfilter/core.c:netfilter_init
  - net/ipv4/tcp_ipv4.c:tcp4_proc_exit
  - net/ipv4/raw.c:raw_proc_exit
  - net/ipv4/udp.c:udp4_proc_exit
  - net/ipv4/igmp.c:igmp_mc_init
  - net/ipv4/ping.c:ping_proc_exit
  - net/ipv4/ipmr.c:ip_mr_init
  - net/unix/af_unix.c:af_unix_exit
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:if6_proc_exit
  - net/ipv6/addrlabel.c:ipv6_addr_label_cleanup
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_gc_cleanup
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ndisc.c:ndisc_cleanup
  - net/ipv6/ndisc.c:ndisc_init
  - net/ipv6/udplite.c:udplite6_proc_exit
  - net/ipv6/raw.c:raw6_proc_exit
  - net/ipv6/icmp.c:icmpv6_cleanup
  - net/ipv6/icmp.c:icmpv6_init
  - net/ipv6/mcast.c:igmp6_cleanup
  - net/ipv6/reassembly.c:ipv6_frag_exit
  - net/ipv6/tcp_ipv6.c:tcpv6_exit
  - net/ipv6/ping.c:pingv6_exit
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup
  - net/ipv6/seg6.c:seg6_exit
  - net/ipv6/seg6.c:seg6_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_unregister
  - net/ipv6/ip6mr.c:ip6_mr_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/ipv6/xfrm6_policy.c:xfrm6_fini
  - net/ipv6/fib6_rules.c:fib6_rules_cleanup
  - net/ipv6/proc.c:ipv6_misc_proc_exit
  - net/packet/af_packet.c:packet_init
  - net/packet/af_packet.c:packet_exit
  - net/wireless/wext-core.c:wireless_nlevent_init
  - net/xdp/xsk.c:xsk_init
```
**Symbols:**

```
c0cdbdd4-c0cdbe10: unregister_pernet_subsys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void unregister_pernet_subsys(struct pernet_operations *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (c000000000c99a50)
Location: net/core/net_namespace.c:1275
Inline: False
Direct callers:
  - net/core/fib_rules.c:fib_rules_init
  - net/sched/act_api.c:tcf_unregister_action
  - net/netfilter/core.c:netfilter_init
  - net/ipv4/tcp_ipv4.c:tcp4_proc_exit
  - net/ipv4/raw.c:raw_proc_exit
  - net/ipv4/udp.c:udp4_proc_exit
  - net/ipv4/igmp.c:igmp_mc_init
  - net/ipv4/ping.c:ping_proc_exit
  - net/ipv4/ipmr.c:ip_mr_init
  - net/unix/af_unix.c:af_unix_exit
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:if6_proc_exit
  - net/ipv6/addrlabel.c:ipv6_addr_label_cleanup
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_gc_cleanup
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ndisc.c:ndisc_cleanup
  - net/ipv6/ndisc.c:ndisc_init
  - net/ipv6/udplite.c:udplite6_proc_exit
  - net/ipv6/raw.c:raw6_proc_exit
  - net/ipv6/icmp.c:icmpv6_cleanup
  - net/ipv6/icmp.c:icmpv6_init
  - net/ipv6/mcast.c:igmp6_cleanup
  - net/ipv6/reassembly.c:ipv6_frag_exit
  - net/ipv6/tcp_ipv6.c:tcpv6_exit
  - net/ipv6/ping.c:pingv6_exit
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup
  - net/ipv6/seg6.c:seg6_exit
  - net/ipv6/seg6.c:seg6_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_unregister
  - net/ipv6/ip6mr.c:ip6_mr_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/ipv6/xfrm6_policy.c:xfrm6_fini
  - net/ipv6/fib6_rules.c:fib6_rules_cleanup
  - net/ipv6/proc.c:ipv6_misc_proc_exit
  - net/packet/af_packet.c:packet_init
  - net/packet/af_packet.c:packet_exit
  - net/wireless/wext-core.c:wireless_nlevent_init
  - net/xdp/xsk.c:xsk_init
```
**Symbols:**

```
c000000000c99a50-c000000000c99ab8: unregister_pernet_subsys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void unregister_pernet_subsys(struct pernet_operations *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffe00074db8a)
Location: net/core/net_namespace.c:1275
Inline: False
Direct callers:
  - net/core/fib_rules.c:fib_rules_init
  - net/sched/act_api.c:tcf_unregister_action
  - net/netfilter/core.c:netfilter_init
  - net/ipv4/tcp_ipv4.c:tcp4_proc_exit
  - net/ipv4/raw.c:raw_proc_exit
  - net/ipv4/udp.c:udp4_proc_exit
  - net/ipv4/igmp.c:igmp_mc_init
  - net/ipv4/ping.c:ping_proc_exit
  - net/ipv4/ipmr.c:ip_mr_init
  - net/unix/af_unix.c:af_unix_exit
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:if6_proc_exit
  - net/ipv6/addrlabel.c:ipv6_addr_label_cleanup
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_gc_cleanup
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ndisc.c:ndisc_cleanup
  - net/ipv6/ndisc.c:ndisc_init
  - net/ipv6/udplite.c:udplite6_proc_exit
  - net/ipv6/raw.c:raw6_proc_exit
  - net/ipv6/icmp.c:icmpv6_cleanup
  - net/ipv6/icmp.c:icmpv6_init
  - net/ipv6/mcast.c:igmp6_cleanup
  - net/ipv6/reassembly.c:ipv6_frag_exit
  - net/ipv6/tcp_ipv6.c:tcpv6_exit
  - net/ipv6/ping.c:pingv6_exit
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup
  - net/ipv6/seg6.c:seg6_exit
  - net/ipv6/seg6.c:seg6_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_unregister
  - net/ipv6/ip6mr.c:ip6_mr_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/ipv6/xfrm6_policy.c:xfrm6_fini
  - net/ipv6/fib6_rules.c:fib6_rules_cleanup
  - net/ipv6/proc.c:ipv6_misc_proc_exit
  - net/packet/af_packet.c:packet_init
  - net/packet/af_packet.c:packet_exit
  - net/wireless/wext-core.c:wireless_nlevent_init
  - net/xdp/xsk.c:xsk_init
```
**Symbols:**

```
ffffffe00074db8a-ffffffe00074dbd4: unregister_pernet_subsys (STB_GLOBAL)
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
void unregister_pernet_subsys(struct pernet_operations *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff818c48a0)
Location: net/core/net_namespace.c:1275
Inline: False
Direct callers:
  - net/core/fib_rules.c:fib_rules_init
  - net/sched/act_api.c:tcf_unregister_action
  - net/netfilter/core.c:netfilter_init
  - net/ipv4/tcp_ipv4.c:tcp4_proc_exit
  - net/ipv4/raw.c:raw_proc_exit
  - net/ipv4/udp.c:udp4_proc_exit
  - net/ipv4/igmp.c:igmp_mc_init
  - net/ipv4/ping.c:ping_proc_exit
  - net/ipv4/ipmr.c:ip_mr_init
  - net/unix/af_unix.c:af_unix_exit
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:if6_proc_exit
  - net/ipv6/addrlabel.c:ipv6_addr_label_cleanup
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_gc_cleanup
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ndisc.c:ndisc_cleanup
  - net/ipv6/ndisc.c:ndisc_init
  - net/ipv6/udplite.c:udplite6_proc_exit
  - net/ipv6/raw.c:raw6_proc_exit
  - net/ipv6/icmp.c:icmpv6_cleanup
  - net/ipv6/icmp.c:icmpv6_init
  - net/ipv6/mcast.c:igmp6_cleanup
  - net/ipv6/reassembly.c:ipv6_frag_exit
  - net/ipv6/tcp_ipv6.c:tcpv6_exit
  - net/ipv6/ping.c:pingv6_exit
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup
  - net/ipv6/seg6.c:seg6_exit
  - net/ipv6/seg6.c:seg6_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_unregister
  - net/ipv6/ip6mr.c:ip6_mr_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/ipv6/xfrm6_policy.c:xfrm6_fini
  - net/ipv6/fib6_rules.c:fib6_rules_cleanup
  - net/ipv6/proc.c:ipv6_misc_proc_exit
  - net/packet/af_packet.c:packet_init
  - net/packet/af_packet.c:packet_exit
  - net/wireless/wext-core.c:wireless_nlevent_init
  - net/xdp/xsk.c:xsk_init
```
**Symbols:**

```
ffffffff818c48a0-ffffffff818c48d2: unregister_pernet_subsys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void unregister_pernet_subsys(struct pernet_operations *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff8187e7e0)
Location: net/core/net_namespace.c:1275
Inline: False
Direct callers:
  - drivers/net/vxlan.c:vxlan_cleanup_module
  - drivers/net/vxlan.c:vxlan_init_module
  - net/core/fib_rules.c:fib_rules_init
  - net/sched/act_api.c:tcf_unregister_action
  - net/netfilter/core.c:netfilter_init
  - net/ipv4/tcp_ipv4.c:tcp4_proc_exit
  - net/ipv4/raw.c:raw_proc_exit
  - net/ipv4/udp.c:udp4_proc_exit
  - net/ipv4/igmp.c:igmp_mc_init
  - net/ipv4/ping.c:ping_proc_exit
  - net/ipv4/ipmr.c:ip_mr_init
  - net/unix/af_unix.c:af_unix_exit
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:if6_proc_exit
  - net/ipv6/addrlabel.c:ipv6_addr_label_cleanup
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_gc_cleanup
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ndisc.c:ndisc_cleanup
  - net/ipv6/ndisc.c:ndisc_init
  - net/ipv6/udplite.c:udplite6_proc_exit
  - net/ipv6/raw.c:raw6_proc_exit
  - net/ipv6/icmp.c:icmpv6_cleanup
  - net/ipv6/icmp.c:icmpv6_init
  - net/ipv6/mcast.c:igmp6_cleanup
  - net/ipv6/reassembly.c:ipv6_frag_exit
  - net/ipv6/tcp_ipv6.c:tcpv6_exit
  - net/ipv6/ping.c:pingv6_exit
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup
  - net/ipv6/seg6.c:seg6_exit
  - net/ipv6/seg6.c:seg6_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_unregister
  - net/ipv6/ip6mr.c:ip6_mr_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/ipv6/xfrm6_policy.c:xfrm6_fini
  - net/ipv6/fib6_rules.c:fib6_rules_cleanup
  - net/ipv6/proc.c:ipv6_misc_proc_exit
  - net/packet/af_packet.c:packet_init
  - net/packet/af_packet.c:packet_exit
  - net/wireless/wext-core.c:wireless_nlevent_init
  - net/xdp/xsk.c:xsk_init
```
**Symbols:**

```
ffffffff8187e7e0-ffffffff8187e812: unregister_pernet_subsys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void unregister_pernet_subsys(struct pernet_operations *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff819158a0)
Location: net/core/net_namespace.c:1275
Inline: False
Direct callers:
  - net/core/fib_rules.c:fib_rules_init
  - net/sched/act_api.c:tcf_unregister_action
  - net/netfilter/core.c:netfilter_init
  - net/netfilter/nfnetlink.c:nfnetlink_exit
  - net/netfilter/nfnetlink_queue.c:nfnetlink_queue_fini
  - net/netfilter/nfnetlink_queue.c:nfnetlink_queue_init
  - net/netfilter/nfnetlink_log.c:nfnetlink_log_fini
  - net/netfilter/nfnetlink_log.c:nfnetlink_log_init
  - net/netfilter/nf_conntrack_standalone.c:nf_conntrack_standalone_fini
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_exit
  - net/ipv4/tcp_ipv4.c:tcp4_proc_exit
  - net/ipv4/raw.c:raw_proc_exit
  - net/ipv4/udp.c:udp4_proc_exit
  - net/ipv4/igmp.c:igmp_mc_init
  - net/ipv4/ping.c:ping_proc_exit
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/netfilter/nf_defrag_ipv4.c:nf_defrag_fini
  - net/unix/af_unix.c:af_unix_exit
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:if6_proc_exit
  - net/ipv6/addrlabel.c:ipv6_addr_label_cleanup
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_gc_cleanup
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ndisc.c:ndisc_cleanup
  - net/ipv6/ndisc.c:ndisc_init
  - net/ipv6/udplite.c:udplite6_proc_exit
  - net/ipv6/raw.c:raw6_proc_exit
  - net/ipv6/icmp.c:icmpv6_cleanup
  - net/ipv6/icmp.c:icmpv6_init
  - net/ipv6/mcast.c:igmp6_cleanup
  - net/ipv6/reassembly.c:ipv6_frag_exit
  - net/ipv6/tcp_ipv6.c:tcpv6_exit
  - net/ipv6/ping.c:pingv6_exit
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup
  - net/ipv6/seg6.c:seg6_exit
  - net/ipv6/seg6.c:seg6_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_unregister
  - net/ipv6/ip6mr.c:ip6_mr_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/ipv6/xfrm6_policy.c:xfrm6_fini
  - net/ipv6/fib6_rules.c:fib6_rules_cleanup
  - net/ipv6/proc.c:ipv6_misc_proc_exit
  - net/ipv6/netfilter/nf_defrag_ipv6_hooks.c:nf_defrag_fini
  - net/ipv6/netfilter/nf_conntrack_reasm.c:nf_ct_frag6_cleanup
  - net/packet/af_packet.c:packet_init
  - net/packet/af_packet.c:packet_exit
  - net/wireless/wext-core.c:wireless_nlevent_init
  - net/xdp/xsk.c:xsk_init
```
**Symbols:**

```
ffffffff819158a0-ffffffff819158d2: unregister_pernet_subsys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void unregister_pernet_subsys(struct pernet_operations *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff81936a90)
Location: net/core/net_namespace.c:1275
Inline: False
Direct callers:
  - net/core/fib_rules.c:fib_rules_init
  - net/sched/act_api.c:tcf_unregister_action
  - net/netfilter/core.c:netfilter_init
  - net/ipv4/tcp_ipv4.c:tcp4_proc_exit
  - net/ipv4/raw.c:raw_proc_exit
  - net/ipv4/udp.c:udp4_proc_exit
  - net/ipv4/igmp.c:igmp_mc_init
  - net/ipv4/ping.c:ping_proc_exit
  - net/ipv4/ipmr.c:ip_mr_init
  - net/unix/af_unix.c:af_unix_exit
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:if6_proc_exit
  - net/ipv6/addrlabel.c:ipv6_addr_label_cleanup
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_gc_cleanup
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ndisc.c:ndisc_cleanup
  - net/ipv6/ndisc.c:ndisc_init
  - net/ipv6/udplite.c:udplite6_proc_exit
  - net/ipv6/raw.c:raw6_proc_exit
  - net/ipv6/icmp.c:icmpv6_cleanup
  - net/ipv6/icmp.c:icmpv6_init
  - net/ipv6/mcast.c:igmp6_cleanup
  - net/ipv6/reassembly.c:ipv6_frag_exit
  - net/ipv6/tcp_ipv6.c:tcpv6_exit
  - net/ipv6/ping.c:pingv6_exit
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_cleanup
  - net/ipv6/seg6.c:seg6_exit
  - net/ipv6/seg6.c:seg6_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_unregister
  - net/ipv6/ip6mr.c:ip6_mr_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/ipv6/xfrm6_policy.c:xfrm6_fini
  - net/ipv6/fib6_rules.c:fib6_rules_cleanup
  - net/ipv6/proc.c:ipv6_misc_proc_exit
  - net/packet/af_packet.c:packet_init
  - net/packet/af_packet.c:packet_exit
  - net/wireless/wext-core.c:wireless_nlevent_init
  - net/xdp/xsk.c:xsk_init
```
**Symbols:**

```
ffffffff81936a90-ffffffff81936ac2: unregister_pernet_subsys (STB_GLOBAL)
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
