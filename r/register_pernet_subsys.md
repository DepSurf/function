# Function: <code>register_pernet_subsys</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int register_pernet_subsys(struct pernet_operations *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff817108b0)
Location: net/core/net_namespace.c:884
Inline: False
Direct callers:
  - fs/proc/proc_net.c:proc_net_init
  - lib/kobject_uevent.c:kobject_uevent_init
  - net/core/sock.c:proto_init
  - net/core/sock.c:net_inuse_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/sysctl_net_core.c:sysctl_core_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/net-procfs.c:dev_proc_init
  - net/core/net-procfs.c:dev_proc_init
  - net/core/fib_rules.c:fib_rules_init
  - net/sched/sch_api.c:pktsched_init
  - net/netlink/genetlink.c:genl_init
  - net/netfilter/core.c:netfilter_init
  - net/netfilter/nf_log.c:netfilter_log_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/ip_fragment.c:ipfrag_init
  - net/ipv4/tcp_ipv4.c:tcp4_proc_init
  - net/ipv4/tcp_ipv4.c:tcp_v4_init
  - net/ipv4/tcp_metrics.c:tcp_metrics_init
  - net/ipv4/raw.c:raw_proc_init
  - net/ipv4/udp.c:udp4_proc_init
  - net/ipv4/udplite.c:udplite4_register
  - net/ipv4/arp.c:arp_init
  - net/ipv4/icmp.c:icmp_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/igmp.c:igmp_mc_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/ping.c:ping_proc_init
  - net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init
  - net/ipv4/proc.c:ip_misc_proc_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/xfrm4_policy.c:xfrm4_init
  - net/xfrm/xfrm_policy.c:xfrm_init
  - net/ipv6/addrconf.c:if6_proc_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrlabel.c:ipv6_addr_label_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ndisc.c:ndisc_init
  - net/ipv6/udplite.c:udplite6_proc_init
  - net/ipv6/raw.c:raw6_proc_init
  - net/ipv6/icmp.c:icmpv6_init
  - net/ipv6/mcast.c:igmp6_init
  - net/ipv6/reassembly.c:ipv6_frag_init
  - net/ipv6/tcp_ipv6.c:tcpv6_init
  - net/ipv6/ping.c:pingv6_init
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/ipv6/xfrm6_policy.c:xfrm6_init
  - net/ipv6/fib6_rules.c:fib6_rules_init
  - net/ipv6/proc.c:ipv6_misc_proc_init
  - net/sysctl_net.c:net_sysctl_init
```
**Symbols:**

```
ffffffff817108b0-ffffffff817108eb: register_pernet_subsys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int register_pernet_subsys(struct pernet_operations *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff817781f0)
Location: net/core/net_namespace.c:884
Inline: False
Direct callers:
  - fs/proc/proc_net.c:proc_net_init
  - lib/kobject_uevent.c:kobject_uevent_init
  - net/core/sock.c:proto_init
  - net/core/sock.c:net_inuse_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/sysctl_net_core.c:sysctl_core_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/net-procfs.c:dev_proc_init
  - net/core/net-procfs.c:dev_proc_init
  - net/core/fib_rules.c:fib_rules_init
  - net/sched/sch_api.c:pktsched_init
  - net/netlink/genetlink.c:genl_init
  - net/netfilter/core.c:netfilter_init
  - net/netfilter/nf_log.c:netfilter_log_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/ip_fragment.c:ipfrag_init
  - net/ipv4/tcp_ipv4.c:tcp_v4_init
  - net/ipv4/tcp_ipv4.c:tcp4_proc_init
  - net/ipv4/tcp_metrics.c:tcp_metrics_init
  - net/ipv4/raw.c:raw_proc_init
  - net/ipv4/udp.c:udp4_proc_init
  - net/ipv4/udplite.c:udplite4_register
  - net/ipv4/arp.c:arp_init
  - net/ipv4/icmp.c:icmp_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/igmp.c:igmp_mc_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/ping.c:ping_proc_init
  - net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init
  - net/ipv4/proc.c:ip_misc_proc_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/xfrm4_policy.c:xfrm4_init
  - net/xfrm/xfrm_policy.c:xfrm_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:if6_proc_init
  - net/ipv6/addrlabel.c:ipv6_addr_label_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ndisc.c:ndisc_init
  - net/ipv6/udplite.c:udplite6_proc_init
  - net/ipv6/raw.c:raw6_proc_init
  - net/ipv6/icmp.c:icmpv6_init
  - net/ipv6/mcast.c:igmp6_init
  - net/ipv6/reassembly.c:ipv6_frag_init
  - net/ipv6/tcp_ipv6.c:tcpv6_init
  - net/ipv6/ping.c:pingv6_init
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/ipv6/xfrm6_policy.c:xfrm6_init
  - net/ipv6/fib6_rules.c:fib6_rules_init
  - net/ipv6/proc.c:ipv6_misc_proc_init
  - net/sysctl_net.c:net_sysctl_init
```
**Symbols:**

```
ffffffff817781f0-ffffffff8177822b: register_pernet_subsys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int register_pernet_subsys(struct pernet_operations *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff817a5340)
Location: net/core/net_namespace.c:924
Inline: False
Direct callers:
  - fs/proc/proc_net.c:proc_net_init
  - lib/kobject_uevent.c:kobject_uevent_init
  - net/core/sock.c:proto_init
  - net/core/sock.c:net_inuse_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/sysctl_net_core.c:sysctl_core_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/net-procfs.c:dev_proc_init
  - net/core/net-procfs.c:dev_proc_init
  - net/core/fib_rules.c:fib_rules_init
  - net/sched/sch_api.c:pktsched_init
  - net/netlink/genetlink.c:genl_init
  - net/netfilter/core.c:netfilter_init
  - net/netfilter/nf_log.c:netfilter_log_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/ip_fragment.c:ipfrag_init
  - net/ipv4/tcp_ipv4.c:tcp_v4_init
  - net/ipv4/tcp_ipv4.c:tcp4_proc_init
  - net/ipv4/tcp_metrics.c:tcp_metrics_init
  - net/ipv4/raw.c:raw_proc_init
  - net/ipv4/udp.c:udp4_proc_init
  - net/ipv4/udplite.c:udplite4_register
  - net/ipv4/arp.c:arp_init
  - net/ipv4/icmp.c:icmp_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/igmp.c:igmp_mc_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/ping.c:ping_proc_init
  - net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init
  - net/ipv4/proc.c:ip_misc_proc_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/xfrm4_policy.c:xfrm4_init
  - net/xfrm/xfrm_policy.c:xfrm_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:if6_proc_init
  - net/ipv6/addrlabel.c:ipv6_addr_label_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ndisc.c:ndisc_init
  - net/ipv6/udplite.c:udplite6_proc_init
  - net/ipv6/raw.c:raw6_proc_init
  - net/ipv6/icmp.c:icmpv6_init
  - net/ipv6/mcast.c:igmp6_init
  - net/ipv6/reassembly.c:ipv6_frag_init
  - net/ipv6/tcp_ipv6.c:tcpv6_init
  - net/ipv6/ping.c:pingv6_init
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_init
  - net/ipv6/seg6.c:seg6_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/ipv6/xfrm6_policy.c:xfrm6_init
  - net/ipv6/fib6_rules.c:fib6_rules_init
  - net/ipv6/proc.c:ipv6_misc_proc_init
  - net/sysctl_net.c:net_sysctl_init
```
**Symbols:**

```
ffffffff817a5340-ffffffff817a537b: register_pernet_subsys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int register_pernet_subsys(struct pernet_operations *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff817c35b0)
Location: net/core/net_namespace.c:990
Inline: False
Direct callers:
  - fs/proc/proc_net.c:proc_net_init
  - net/core/sock.c:proto_init
  - net/core/sock.c:net_inuse_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_defaults_init
  - net/core/sysctl_net_core.c:sysctl_core_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/net-procfs.c:dev_proc_init
  - net/core/net-procfs.c:dev_proc_init
  - net/core/fib_rules.c:fib_rules_init
  - net/sched/sch_api.c:pktsched_init
  - net/netlink/genetlink.c:genl_init
  - net/netfilter/core.c:netfilter_init
  - net/netfilter/nf_log.c:netfilter_log_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/ip_fragment.c:ipfrag_init
  - net/ipv4/tcp_ipv4.c:tcp_v4_init
  - net/ipv4/tcp_ipv4.c:tcp4_proc_init
  - net/ipv4/tcp_metrics.c:tcp_metrics_init
  - net/ipv4/raw.c:raw_proc_init
  - net/ipv4/udp.c:udp4_proc_init
  - net/ipv4/udplite.c:udplite4_register
  - net/ipv4/arp.c:arp_init
  - net/ipv4/icmp.c:icmp_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/igmp.c:igmp_mc_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/ping.c:ping_proc_init
  - net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init
  - net/ipv4/proc.c:ip_misc_proc_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/xfrm4_policy.c:xfrm4_init
  - net/xfrm/xfrm_policy.c:xfrm_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:if6_proc_init
  - net/ipv6/addrlabel.c:ipv6_addr_label_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ndisc.c:ndisc_init
  - net/ipv6/udplite.c:udplite6_proc_init
  - net/ipv6/raw.c:raw6_proc_init
  - net/ipv6/icmp.c:icmpv6_init
  - net/ipv6/mcast.c:igmp6_init
  - net/ipv6/reassembly.c:ipv6_frag_init
  - net/ipv6/tcp_ipv6.c:tcpv6_init
  - net/ipv6/ping.c:pingv6_init
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_init
  - net/ipv6/seg6.c:seg6_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/ipv6/xfrm6_policy.c:xfrm6_init
  - net/ipv6/fib6_rules.c:fib6_rules_init
  - net/ipv6/proc.c:ipv6_misc_proc_init
  - net/sysctl_net.c:net_sysctl_init
  - lib/kobject_uevent.c:kobject_uevent_init
```
**Symbols:**

```
ffffffff817c35b0-ffffffff817c35eb: register_pernet_subsys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int register_pernet_subsys(struct pernet_operations *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff8183d100)
Location: net/core/net_namespace.c:992
Inline: False
Direct callers:
  - fs/proc/proc_net.c:proc_net_init
  - net/core/sock.c:proto_init
  - net/core/sock.c:net_inuse_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_defaults_init
  - net/core/sysctl_net_core.c:sysctl_core_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/fib_notifier.c:fib_notifier_init
  - net/core/net-procfs.c:dev_proc_init
  - net/core/net-procfs.c:dev_proc_init
  - net/core/fib_rules.c:fib_rules_init
  - net/sched/sch_api.c:pktsched_init
  - net/netlink/genetlink.c:genl_init
  - net/netfilter/core.c:netfilter_init
  - net/netfilter/nf_log.c:netfilter_log_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/ip_fragment.c:ipfrag_init
  - net/ipv4/tcp_ipv4.c:tcp_v4_init
  - net/ipv4/tcp_ipv4.c:tcp4_proc_init
  - net/ipv4/tcp_metrics.c:tcp_metrics_init
  - net/ipv4/raw.c:raw_proc_init
  - net/ipv4/udp.c:udp4_proc_init
  - net/ipv4/udplite.c:udplite4_register
  - net/ipv4/arp.c:arp_init
  - net/ipv4/icmp.c:icmp_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/igmp.c:igmp_mc_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/ping.c:ping_proc_init
  - net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init
  - net/ipv4/proc.c:ip_misc_proc_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/xfrm4_policy.c:xfrm4_init
  - net/xfrm/xfrm_policy.c:xfrm_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:if6_proc_init
  - net/ipv6/addrlabel.c:ipv6_addr_label_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ndisc.c:ndisc_init
  - net/ipv6/udplite.c:udplite6_proc_init
  - net/ipv6/raw.c:raw6_proc_init
  - net/ipv6/icmp.c:icmpv6_init
  - net/ipv6/mcast.c:igmp6_init
  - net/ipv6/reassembly.c:ipv6_frag_init
  - net/ipv6/tcp_ipv6.c:tcpv6_init
  - net/ipv6/ping.c:pingv6_init
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_init
  - net/ipv6/seg6.c:seg6_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/ipv6/xfrm6_policy.c:xfrm6_init
  - net/ipv6/fib6_rules.c:fib6_rules_init
  - net/ipv6/proc.c:ipv6_misc_proc_init
  - net/sysctl_net.c:net_sysctl_init
  - lib/kobject_uevent.c:kobject_uevent_init
```
**Symbols:**

```
ffffffff8183d100-ffffffff8183d13b: register_pernet_subsys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int register_pernet_subsys(struct pernet_operations *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff818879b0)
Location: net/core/net_namespace.c:1052
Inline: False
Direct callers:
  - kernel/audit.c:audit_init
  - fs/proc/proc_net.c:proc_net_init
  - security/selinux/hooks.c:selinux_nf_ip_init
  - security/smack/smack_netfilter.c:smack_nf_ip_init
  - net/core/sock.c:proto_init
  - net/core/sock.c:net_inuse_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_defaults_init
  - net/core/sysctl_net_core.c:sysctl_core_init
  - net/core/dev.c:net_dev_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/sock_diag.c:sock_diag_init
  - net/core/fib_notifier.c:fib_notifier_init
  - net/core/net-procfs.c:dev_proc_init
  - net/core/net-procfs.c:dev_proc_init
  - net/core/fib_rules.c:fib_rules_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/act_api.c:tc_action_init
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/genetlink.c:genl_init
  - net/netfilter/core.c:netfilter_init
  - net/netfilter/nf_log.c:netfilter_log_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/ip_fragment.c:ipfrag_init
  - net/ipv4/tcp_ipv4.c:tcp_v4_init
  - net/ipv4/tcp_ipv4.c:tcp4_proc_init
  - net/ipv4/tcp_metrics.c:tcp_metrics_init
  - net/ipv4/raw.c:raw_proc_init
  - net/ipv4/udp.c:udp_init
  - net/ipv4/udp.c:udp4_proc_init
  - net/ipv4/udplite.c:udplite4_register
  - net/ipv4/arp.c:arp_init
  - net/ipv4/icmp.c:icmp_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/igmp.c:igmp_mc_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/ping.c:ping_proc_init
  - net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init
  - net/ipv4/proc.c:ip_misc_proc_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/xfrm4_policy.c:xfrm4_init
  - net/xfrm/xfrm_policy.c:xfrm_init
  - net/unix/af_unix.c:af_unix_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:if6_proc_init
  - net/ipv6/addrlabel.c:ipv6_addr_label_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ndisc.c:ndisc_init
  - net/ipv6/udplite.c:udplite6_proc_init
  - net/ipv6/raw.c:raw6_proc_init
  - net/ipv6/icmp.c:icmpv6_init
  - net/ipv6/mcast.c:igmp6_init
  - net/ipv6/reassembly.c:ipv6_frag_init
  - net/ipv6/tcp_ipv6.c:tcpv6_init
  - net/ipv6/ping.c:pingv6_init
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_init
  - net/ipv6/seg6.c:seg6_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/ipv6/xfrm6_policy.c:xfrm6_init
  - net/ipv6/fib6_rules.c:fib6_rules_init
  - net/ipv6/proc.c:ipv6_misc_proc_init
  - net/packet/af_packet.c:packet_init
  - net/wireless/wext-core.c:wireless_nlevent_init
  - net/sysctl_net.c:net_sysctl_init
  - lib/kobject_uevent.c:kobject_uevent_init
```
**Symbols:**

```
ffffffff818879b0-ffffffff818879eb: register_pernet_subsys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int register_pernet_subsys(struct pernet_operations *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff818a8220)
Location: net/core/net_namespace.c:1162
Inline: False
Direct callers:
  - kernel/audit.c:audit_init
  - fs/proc/proc_net.c:proc_net_init
  - security/selinux/hooks.c:selinux_nf_ip_init
  - security/smack/smack_netfilter.c:smack_nf_ip_init
  - net/core/sock.c:proto_init
  - net/core/sock.c:net_inuse_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_defaults_init
  - net/core/sysctl_net_core.c:sysctl_core_init
  - net/core/dev.c:net_dev_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/sock_diag.c:sock_diag_init
  - net/core/fib_notifier.c:fib_notifier_init
  - net/core/net-procfs.c:dev_proc_init
  - net/core/net-procfs.c:dev_proc_init
  - net/core/fib_rules.c:fib_rules_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/cls_api.c:tc_filter_init
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/genetlink.c:genl_init
  - net/netfilter/core.c:netfilter_init
  - net/netfilter/nf_log.c:netfilter_log_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/ip_fragment.c:ipfrag_init
  - net/ipv4/tcp_ipv4.c:tcp_v4_init
  - net/ipv4/tcp_ipv4.c:tcp4_proc_init
  - net/ipv4/tcp_metrics.c:tcp_metrics_init
  - net/ipv4/raw.c:raw_init
  - net/ipv4/raw.c:raw_proc_init
  - net/ipv4/udp.c:udp_init
  - net/ipv4/udp.c:udp4_proc_init
  - net/ipv4/udplite.c:udplite4_register
  - net/ipv4/arp.c:arp_init
  - net/ipv4/icmp.c:icmp_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/igmp.c:igmp_mc_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/ping.c:ping_proc_init
  - net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init
  - net/ipv4/proc.c:ip_misc_proc_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/xfrm4_policy.c:xfrm4_init
  - net/xfrm/xfrm_policy.c:xfrm_init
  - net/unix/af_unix.c:af_unix_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:if6_proc_init
  - net/ipv6/addrlabel.c:ipv6_addr_label_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ndisc.c:ndisc_init
  - net/ipv6/udplite.c:udplite6_proc_init
  - net/ipv6/raw.c:raw6_proc_init
  - net/ipv6/icmp.c:icmpv6_init
  - net/ipv6/mcast.c:igmp6_init
  - net/ipv6/reassembly.c:ipv6_frag_init
  - net/ipv6/tcp_ipv6.c:tcpv6_init
  - net/ipv6/ping.c:pingv6_init
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_init
  - net/ipv6/seg6.c:seg6_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/ipv6/xfrm6_policy.c:xfrm6_init
  - net/ipv6/fib6_rules.c:fib6_rules_init
  - net/ipv6/proc.c:ipv6_misc_proc_init
  - net/packet/af_packet.c:packet_init
  - net/wireless/wext-core.c:wireless_nlevent_init
  - net/sysctl_net.c:net_sysctl_init
  - lib/kobject_uevent.c:kobject_uevent_init
```
**Symbols:**

```
ffffffff818a8220-ffffffff818a825b: register_pernet_subsys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int register_pernet_subsys(struct pernet_operations *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff818f3260)
Location: net/core/net_namespace.c:1249
Inline: False
Direct callers:
  - kernel/audit.c:audit_init
  - fs/proc/proc_net.c:proc_net_init
  - security/selinux/hooks.c:selinux_nf_ip_init
  - security/smack/smack_netfilter.c:smack_nf_ip_init
  - net/core/sock.c:proto_init
  - net/core/sock.c:net_inuse_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_defaults_init
  - net/core/sysctl_net_core.c:sysctl_core_init
  - net/core/dev.c:net_dev_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/sock_diag.c:sock_diag_init
  - net/core/fib_notifier.c:fib_notifier_init
  - net/core/net-procfs.c:dev_proc_init
  - net/core/net-procfs.c:dev_proc_init
  - net/core/fib_rules.c:fib_rules_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/cls_api.c:tc_filter_init
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/genetlink.c:genl_init
  - net/netfilter/core.c:netfilter_init
  - net/netfilter/nf_log.c:netfilter_log_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/ip_fragment.c:ipfrag_init
  - net/ipv4/tcp_ipv4.c:tcp_v4_init
  - net/ipv4/tcp_ipv4.c:tcp4_proc_init
  - net/ipv4/tcp_metrics.c:tcp_metrics_init
  - net/ipv4/raw.c:raw_init
  - net/ipv4/raw.c:raw_proc_init
  - net/ipv4/udp.c:udp_init
  - net/ipv4/udp.c:udp4_proc_init
  - net/ipv4/udplite.c:udplite4_register
  - net/ipv4/arp.c:arp_init
  - net/ipv4/icmp.c:icmp_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/igmp.c:igmp_mc_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/ping.c:ping_proc_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init
  - net/ipv4/proc.c:ip_misc_proc_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/xfrm4_policy.c:xfrm4_init
  - net/xfrm/xfrm_policy.c:xfrm_init
  - net/unix/af_unix.c:af_unix_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:if6_proc_init
  - net/ipv6/addrlabel.c:ipv6_addr_label_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ndisc.c:ndisc_init
  - net/ipv6/udplite.c:udplite6_proc_init
  - net/ipv6/raw.c:raw6_proc_init
  - net/ipv6/icmp.c:icmpv6_init
  - net/ipv6/mcast.c:igmp6_init
  - net/ipv6/reassembly.c:ipv6_frag_init
  - net/ipv6/tcp_ipv6.c:tcpv6_init
  - net/ipv6/ping.c:pingv6_init
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_init
  - net/ipv6/seg6.c:seg6_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/ipv6/xfrm6_policy.c:xfrm6_init
  - net/ipv6/fib6_rules.c:fib6_rules_init
  - net/ipv6/proc.c:ipv6_misc_proc_init
  - net/packet/af_packet.c:packet_init
  - net/wireless/wext-core.c:wireless_nlevent_init
  - net/sysctl_net.c:net_sysctl_init
  - net/xdp/xsk.c:xsk_init
  - lib/kobject_uevent.c:kobject_uevent_init
```
**Symbols:**

```
ffffffff818f3260-ffffffff818f329f: register_pernet_subsys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int register_pernet_subsys(struct pernet_operations *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff819251c0)
Location: net/core/net_namespace.c:1256
Inline: False
Direct callers:
  - kernel/audit.c:audit_init
  - fs/proc/proc_net.c:proc_net_init
  - security/selinux/hooks.c:selinux_nf_ip_init
  - security/smack/smack_netfilter.c:smack_nf_ip_init
  - net/core/sock.c:proto_init
  - net/core/sock.c:net_inuse_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_defaults_init
  - net/core/sysctl_net_core.c:sysctl_core_init
  - net/core/dev.c:net_dev_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/sock_diag.c:sock_diag_init
  - net/core/fib_notifier.c:fib_notifier_init
  - net/core/net-procfs.c:dev_proc_init
  - net/core/net-procfs.c:dev_proc_init
  - net/core/fib_rules.c:fib_rules_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/cls_api.c:tc_filter_init
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/genetlink.c:genl_init
  - net/netfilter/core.c:netfilter_init
  - net/netfilter/nf_log.c:netfilter_log_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/ip_fragment.c:ipfrag_init
  - net/ipv4/tcp_ipv4.c:tcp_v4_init
  - net/ipv4/tcp_ipv4.c:tcp4_proc_init
  - net/ipv4/tcp_metrics.c:tcp_metrics_init
  - net/ipv4/raw.c:raw_init
  - net/ipv4/raw.c:raw_proc_init
  - net/ipv4/udp.c:udp_init
  - net/ipv4/udp.c:udp4_proc_init
  - net/ipv4/udplite.c:udplite4_register
  - net/ipv4/arp.c:arp_init
  - net/ipv4/icmp.c:icmp_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/igmp.c:igmp_mc_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/ping.c:ping_proc_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init
  - net/ipv4/proc.c:ip_misc_proc_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/xfrm4_policy.c:xfrm4_init
  - net/xfrm/xfrm_policy.c:xfrm_init
  - net/unix/af_unix.c:af_unix_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:if6_proc_init
  - net/ipv6/addrlabel.c:ipv6_addr_label_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ndisc.c:ndisc_init
  - net/ipv6/udplite.c:udplite6_proc_init
  - net/ipv6/raw.c:raw6_proc_init
  - net/ipv6/icmp.c:icmpv6_init
  - net/ipv6/mcast.c:igmp6_init
  - net/ipv6/reassembly.c:ipv6_frag_init
  - net/ipv6/tcp_ipv6.c:tcpv6_init
  - net/ipv6/ping.c:pingv6_init
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_init
  - net/ipv6/seg6.c:seg6_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/ipv6/xfrm6_policy.c:xfrm6_init
  - net/ipv6/fib6_rules.c:fib6_rules_init
  - net/ipv6/proc.c:ipv6_misc_proc_init
  - net/packet/af_packet.c:packet_init
  - net/wireless/wext-core.c:wireless_nlevent_init
  - net/sysctl_net.c:net_sysctl_init
  - net/xdp/xsk.c:xsk_init
  - lib/kobject_uevent.c:kobject_uevent_init
```
**Symbols:**

```
ffffffff819251c0-ffffffff819251ff: register_pernet_subsys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int register_pernet_subsys(struct pernet_operations *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff819f9850)
Location: net/core/net_namespace.c:1254
Inline: False
Direct callers:
  - kernel/audit.c:audit_init
  - kernel/bpf/net_namespace.c:netns_bpf_init
  - fs/proc/proc_net.c:proc_net_init
  - security/selinux/hooks.c:selinux_nf_ip_init
  - security/smack/smack_netfilter.c:smack_nf_ip_init
  - security/apparmor/lsm.c:apparmor_nf_ip_init
  - lib/kobject_uevent.c:kobject_uevent_init
  - net/core/sock.c:proto_init
  - net/core/sock.c:net_inuse_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_defaults_init
  - net/core/sysctl_net_core.c:sysctl_core_init
  - net/core/dev.c:net_dev_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/sock_diag.c:sock_diag_init
  - net/core/fib_notifier.c:fib_notifier_init
  - net/core/net-procfs.c:dev_proc_init
  - net/core/net-procfs.c:dev_proc_init
  - net/core/fib_rules.c:fib_rules_init
  - net/core/devlink.c:devlink_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/act_api.c:tcf_register_action
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/genetlink.c:genl_init
  - net/netfilter/core.c:netfilter_init
  - net/netfilter/nf_log.c:netfilter_log_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/ip_fragment.c:ipfrag_init
  - net/ipv4/tcp_ipv4.c:tcp_v4_init
  - net/ipv4/tcp_ipv4.c:tcp4_proc_init
  - net/ipv4/tcp_metrics.c:tcp_metrics_init
  - net/ipv4/raw.c:raw_init
  - net/ipv4/raw.c:raw_proc_init
  - net/ipv4/udp.c:udp_init
  - net/ipv4/udp.c:udp4_proc_init
  - net/ipv4/udplite.c:udplite4_register
  - net/ipv4/arp.c:arp_init
  - net/ipv4/icmp.c:icmp_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/igmp.c:igmp_mc_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/ping.c:ping_proc_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init
  - net/ipv4/proc.c:ip_misc_proc_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/xfrm4_policy.c:xfrm4_init
  - net/xfrm/xfrm_policy.c:xfrm_init
  - net/unix/af_unix.c:af_unix_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:if6_proc_init
  - net/ipv6/addrlabel.c:ipv6_addr_label_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ndisc.c:ndisc_init
  - net/ipv6/udplite.c:udplite6_proc_init
  - net/ipv6/raw.c:raw6_proc_init
  - net/ipv6/icmp.c:icmpv6_init
  - net/ipv6/mcast.c:igmp6_init
  - net/ipv6/reassembly.c:ipv6_frag_init
  - net/ipv6/tcp_ipv6.c:tcpv6_init
  - net/ipv6/ping.c:pingv6_init
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_init
  - net/ipv6/seg6.c:seg6_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/ipv6/xfrm6_policy.c:xfrm6_init
  - net/ipv6/fib6_rules.c:fib6_rules_init
  - net/ipv6/proc.c:ipv6_misc_proc_init
  - net/packet/af_packet.c:packet_init
  - net/wireless/wext-core.c:wireless_nlevent_init
  - net/sysctl_net.c:net_sysctl_init
  - net/xdp/xsk.c:xsk_init
  - net/mptcp/ctrl.c:mptcp_init
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_init
```
**Symbols:**

```
ffffffff819f9850-ffffffff819f9891: register_pernet_subsys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int register_pernet_subsys(struct pernet_operations *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff819f9090)
Location: net/core/net_namespace.c:1258
Inline: False
Direct callers:
  - kernel/audit.c:audit_init
  - kernel/bpf/net_namespace.c:netns_bpf_init
  - fs/proc/proc_net.c:proc_net_init
  - security/selinux/hooks.c:selinux_nf_ip_init
  - security/smack/smack_netfilter.c:smack_nf_ip_init
  - security/apparmor/lsm.c:apparmor_nf_ip_init
  - lib/kobject_uevent.c:kobject_uevent_init
  - net/core/sock.c:proto_init
  - net/core/sock.c:net_inuse_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_defaults_init
  - net/core/sysctl_net_core.c:sysctl_core_init
  - net/core/dev.c:net_dev_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/sock_diag.c:sock_diag_init
  - net/core/fib_notifier.c:fib_notifier_init
  - net/core/net-procfs.c:dev_proc_init
  - net/core/net-procfs.c:dev_proc_init
  - net/core/fib_rules.c:fib_rules_init
  - net/core/devlink.c:devlink_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/act_api.c:tcf_register_action
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/genetlink.c:genl_init
  - net/netfilter/core.c:netfilter_init
  - net/netfilter/nf_log.c:netfilter_log_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/ip_fragment.c:ipfrag_init
  - net/ipv4/tcp_ipv4.c:tcp_v4_init
  - net/ipv4/tcp_ipv4.c:tcp4_proc_init
  - net/ipv4/tcp_metrics.c:tcp_metrics_init
  - net/ipv4/raw.c:raw_init
  - net/ipv4/raw.c:raw_proc_init
  - net/ipv4/udp.c:udp_init
  - net/ipv4/udp.c:udp4_proc_init
  - net/ipv4/udplite.c:udplite4_register
  - net/ipv4/arp.c:arp_init
  - net/ipv4/icmp.c:icmp_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/igmp.c:igmp_mc_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/ping.c:ping_proc_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init
  - net/ipv4/proc.c:ip_misc_proc_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/xfrm4_policy.c:xfrm4_init
  - net/xfrm/xfrm_policy.c:xfrm_init
  - net/unix/af_unix.c:af_unix_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:if6_proc_init
  - net/ipv6/addrlabel.c:ipv6_addr_label_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ndisc.c:ndisc_init
  - net/ipv6/udplite.c:udplite6_proc_init
  - net/ipv6/raw.c:raw6_proc_init
  - net/ipv6/icmp.c:icmpv6_init
  - net/ipv6/mcast.c:igmp6_init
  - net/ipv6/reassembly.c:ipv6_frag_init
  - net/ipv6/tcp_ipv6.c:tcpv6_init
  - net/ipv6/ping.c:pingv6_init
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_init
  - net/ipv6/seg6.c:seg6_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/ipv6/xfrm6_policy.c:xfrm6_init
  - net/ipv6/fib6_rules.c:fib6_rules_init
  - net/ipv6/proc.c:ipv6_misc_proc_init
  - net/packet/af_packet.c:packet_init
  - net/wireless/wext-core.c:wireless_nlevent_init
  - net/sysctl_net.c:net_sysctl_init
  - net/xdp/xsk.c:xsk_init
  - net/mptcp/ctrl.c:mptcp_init
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_init
```
**Symbols:**

```
ffffffff819f9090-ffffffff819f90d1: register_pernet_subsys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int register_pernet_subsys(struct pernet_operations *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff819de1a0)
Location: net/core/net_namespace.c:1251
Inline: False
Direct callers:
  - kernel/audit.c:audit_init
  - kernel/bpf/net_namespace.c:netns_bpf_init
  - fs/proc/proc_net.c:proc_net_init
  - security/selinux/hooks.c:selinux_nf_ip_init
  - security/smack/smack_netfilter.c:smack_nf_ip_init
  - security/apparmor/lsm.c:apparmor_nf_ip_init
  - lib/kobject_uevent.c:kobject_uevent_init
  - net/core/sock.c:proto_init
  - net/core/sock.c:net_inuse_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_defaults_init
  - net/core/sysctl_net_core.c:sysctl_core_init
  - net/core/dev.c:net_dev_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/sock_diag.c:sock_diag_init
  - net/core/fib_notifier.c:fib_notifier_init
  - net/core/net-procfs.c:dev_proc_init
  - net/core/net-procfs.c:dev_proc_init
  - net/core/fib_rules.c:fib_rules_init
  - net/core/devlink.c:devlink_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/act_api.c:tcf_register_action
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/genetlink.c:genl_init
  - net/netfilter/core.c:netfilter_init
  - net/netfilter/nf_log.c:netfilter_log_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/ip_fragment.c:ipfrag_init
  - net/ipv4/tcp_ipv4.c:tcp_v4_init
  - net/ipv4/tcp_ipv4.c:tcp4_proc_init
  - net/ipv4/tcp_metrics.c:tcp_metrics_init
  - net/ipv4/raw.c:raw_init
  - net/ipv4/raw.c:raw_proc_init
  - net/ipv4/udp.c:udp_init
  - net/ipv4/udp.c:udp4_proc_init
  - net/ipv4/udplite.c:udplite4_register
  - net/ipv4/arp.c:arp_init
  - net/ipv4/icmp.c:icmp_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/igmp.c:igmp_mc_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/ping.c:ping_proc_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init
  - net/ipv4/proc.c:ip_misc_proc_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/xfrm4_policy.c:xfrm4_init
  - net/xfrm/xfrm_policy.c:xfrm_init
  - net/unix/af_unix.c:af_unix_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:if6_proc_init
  - net/ipv6/addrlabel.c:ipv6_addr_label_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ndisc.c:ndisc_init
  - net/ipv6/udplite.c:udplite6_proc_init
  - net/ipv6/raw.c:raw6_proc_init
  - net/ipv6/icmp.c:icmpv6_init
  - net/ipv6/mcast.c:igmp6_init
  - net/ipv6/reassembly.c:ipv6_frag_init
  - net/ipv6/tcp_ipv6.c:tcpv6_init
  - net/ipv6/ping.c:pingv6_init
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_init
  - net/ipv6/seg6.c:seg6_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/ipv6/xfrm6_policy.c:xfrm6_init
  - net/ipv6/fib6_rules.c:fib6_rules_init
  - net/ipv6/proc.c:ipv6_misc_proc_init
  - net/packet/af_packet.c:packet_init
  - net/wireless/wext-core.c:wireless_nlevent_init
  - net/sysctl_net.c:net_sysctl_init
  - net/xdp/xsk.c:xsk_init
  - net/mptcp/ctrl.c:mptcp_init
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_init
```
**Symbols:**

```
ffffffff819de1a0-ffffffff819de1e1: register_pernet_subsys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int register_pernet_subsys(struct pernet_operations *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff81a8eab0)
Location: net/core/net_namespace.c:1253
Inline: False
Direct callers:
  - kernel/audit.c:audit_init
  - kernel/bpf/net_namespace.c:netns_bpf_init
  - fs/proc/proc_net.c:proc_net_init
  - security/selinux/hooks.c:selinux_nf_ip_init
  - security/smack/smack_netfilter.c:smack_nf_ip_init
  - security/apparmor/lsm.c:apparmor_nf_ip_init
  - lib/kobject_uevent.c:kobject_uevent_init
  - net/core/sock.c:proto_init
  - net/core/sock.c:net_inuse_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_defaults_init
  - net/core/sysctl_net_core.c:sysctl_core_init
  - net/core/dev.c:net_dev_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/sock_diag.c:sock_diag_init
  - net/core/fib_notifier.c:fib_notifier_init
  - net/core/net-procfs.c:dev_proc_init
  - net/core/net-procfs.c:dev_proc_init
  - net/core/fib_rules.c:fib_rules_init
  - net/core/devlink.c:devlink_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/act_api.c:tcf_register_action
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/genetlink.c:genl_init
  - net/netfilter/core.c:netfilter_init
  - net/netfilter/nf_log.c:netfilter_log_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/ip_fragment.c:ipfrag_init
  - net/ipv4/tcp_ipv4.c:tcp_v4_init
  - net/ipv4/tcp_ipv4.c:tcp4_proc_init
  - net/ipv4/tcp_metrics.c:tcp_metrics_init
  - net/ipv4/raw.c:raw_init
  - net/ipv4/raw.c:raw_proc_init
  - net/ipv4/udp.c:udp_init
  - net/ipv4/udp.c:udp4_proc_init
  - net/ipv4/udplite.c:udplite4_register
  - net/ipv4/arp.c:arp_init
  - net/ipv4/icmp.c:icmp_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/igmp.c:igmp_mc_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/ping.c:ping_proc_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init
  - net/ipv4/proc.c:ip_misc_proc_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/xfrm4_policy.c:xfrm4_init
  - net/xfrm/xfrm_policy.c:xfrm_init
  - net/unix/af_unix.c:af_unix_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:if6_proc_init
  - net/ipv6/addrlabel.c:ipv6_addr_label_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ndisc.c:ndisc_init
  - net/ipv6/udplite.c:udplite6_proc_init
  - net/ipv6/raw.c:raw6_proc_init
  - net/ipv6/icmp.c:icmpv6_init
  - net/ipv6/mcast.c:igmp6_init
  - net/ipv6/reassembly.c:ipv6_frag_init
  - net/ipv6/tcp_ipv6.c:tcpv6_init
  - net/ipv6/ping.c:pingv6_init
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_init
  - net/ipv6/seg6.c:seg6_init
  - net/ipv6/ioam6.c:ioam6_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/ipv6/xfrm6_policy.c:xfrm6_init
  - net/ipv6/fib6_rules.c:fib6_rules_init
  - net/ipv6/proc.c:ipv6_misc_proc_init
  - net/packet/af_packet.c:packet_init
  - net/wireless/wext-core.c:wireless_nlevent_init
  - net/sysctl_net.c:net_sysctl_init
  - net/xdp/xsk.c:xsk_init
  - net/mptcp/ctrl.c:mptcp_init
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_init
```
**Symbols:**

```
ffffffff81a8eab0-ffffffff81a8eaf1: register_pernet_subsys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int register_pernet_subsys(struct pernet_operations *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff81c049e0)
Location: net/core/net_namespace.c:1252
Inline: False
Direct callers:
  - kernel/audit.c:audit_init
  - kernel/bpf/net_namespace.c:netns_bpf_init
  - fs/proc/proc_net.c:proc_net_init
  - security/selinux/hooks.c:selinux_nf_ip_init
  - security/smack/smack_netfilter.c:smack_nf_ip_init
  - security/apparmor/lsm.c:apparmor_nf_ip_init
  - lib/kobject_uevent.c:kobject_uevent_init
  - net/core/sock.c:proto_init
  - net/core/sock.c:net_inuse_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_defaults_init
  - net/core/sysctl_net_core.c:sysctl_core_init
  - net/core/dev.c:net_dev_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/sock_diag.c:sock_diag_init
  - net/core/fib_notifier.c:fib_notifier_init
  - net/core/net-procfs.c:dev_proc_init
  - net/core/net-procfs.c:dev_proc_init
  - net/core/fib_rules.c:fib_rules_init
  - net/core/devlink.c:devlink_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/act_api.c:tcf_register_action
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/genetlink.c:genl_init
  - net/netfilter/core.c:netfilter_init
  - net/netfilter/nf_log.c:netfilter_log_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/ip_fragment.c:ipfrag_init
  - net/ipv4/tcp_ipv4.c:tcp_v4_init
  - net/ipv4/tcp_ipv4.c:tcp4_proc_init
  - net/ipv4/tcp_metrics.c:tcp_metrics_init
  - net/ipv4/raw.c:raw_init
  - net/ipv4/raw.c:raw_proc_init
  - net/ipv4/udp.c:udp_init
  - net/ipv4/udp.c:udp4_proc_init
  - net/ipv4/udplite.c:udplite4_register
  - net/ipv4/arp.c:arp_init
  - net/ipv4/icmp.c:icmp_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/igmp.c:igmp_mc_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/ping.c:ping_proc_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init
  - net/ipv4/proc.c:ip_misc_proc_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/xfrm4_policy.c:xfrm4_init
  - net/xfrm/xfrm_policy.c:xfrm_init
  - net/unix/af_unix.c:af_unix_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:if6_proc_init
  - net/ipv6/addrlabel.c:ipv6_addr_label_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ndisc.c:ndisc_init
  - net/ipv6/udplite.c:udplite6_proc_init
  - net/ipv6/raw.c:raw6_proc_init
  - net/ipv6/mcast.c:igmp6_init
  - net/ipv6/reassembly.c:ipv6_frag_init
  - net/ipv6/tcp_ipv6.c:tcpv6_init
  - net/ipv6/ping.c:pingv6_init
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_init
  - net/ipv6/seg6.c:seg6_init
  - net/ipv6/ioam6.c:ioam6_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/ipv6/xfrm6_policy.c:xfrm6_init
  - net/ipv6/fib6_rules.c:fib6_rules_init
  - net/ipv6/proc.c:ipv6_misc_proc_init
  - net/packet/af_packet.c:packet_init
  - net/wireless/wext-core.c:wireless_nlevent_init
  - net/sysctl_net.c:net_sysctl_init
  - net/xdp/xsk.c:xsk_init
  - net/mptcp/ctrl.c:mptcp_init
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_init
  - net/mctp/route.c:mctp_routes_init
  - net/mctp/neigh.c:mctp_neigh_init
```
**Symbols:**

```
ffffffff81c049e0-ffffffff81c04a26: register_pernet_subsys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int register_pernet_subsys(struct pernet_operations *ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff83f0c76f)
Location: net/core/net_namespace.c:1272
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_defaults_init
Direct callers:
  - kernel/audit.c:audit_init
  - kernel/bpf/net_namespace.c:netns_bpf_init
  - fs/proc/proc_net.c:proc_net_init
  - security/selinux/hooks.c:selinux_nf_ip_init
  - security/smack/smack_netfilter.c:smack_nf_ip_init
  - security/apparmor/lsm.c:apparmor_nf_ip_init
  - net/core/sock.c:proto_init
  - net/core/sock.c:net_inuse_init
  - net/core/sysctl_net_core.c:sysctl_core_init
  - net/core/dev.c:net_dev_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/sock_diag.c:sock_diag_init
  - net/core/fib_notifier.c:fib_notifier_init
  - net/core/net-procfs.c:dev_proc_init
  - net/core/net-procfs.c:dev_proc_init
  - net/core/fib_rules.c:fib_rules_init
  - net/core/devlink.c:devlink_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/cls_api.c:tc_filter_init
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/genetlink.c:genl_init
  - net/netfilter/core.c:netfilter_init
  - net/netfilter/nf_log.c:netfilter_log_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/ip_fragment.c:ipfrag_init
  - net/ipv4/tcp_ipv4.c:tcp_v4_init
  - net/ipv4/tcp_ipv4.c:tcp4_proc_init
  - net/ipv4/tcp_metrics.c:tcp_metrics_init
  - net/ipv4/raw.c:raw_init
  - net/ipv4/raw.c:raw_proc_init
  - net/ipv4/udp.c:udp_init
  - net/ipv4/udp.c:udp4_proc_init
  - net/ipv4/udplite.c:udplite4_register
  - net/ipv4/arp.c:arp_init
  - net/ipv4/icmp.c:icmp_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/igmp.c:igmp_mc_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/ping.c:ping_proc_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init
  - net/ipv4/proc.c:ip_misc_proc_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/xfrm4_policy.c:xfrm4_init
  - net/xfrm/xfrm_policy.c:xfrm_init
  - net/unix/af_unix.c:af_unix_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:if6_proc_init
  - net/ipv6/addrlabel.c:ipv6_addr_label_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ndisc.c:ndisc_init
  - net/ipv6/udplite.c:udplite6_proc_init
  - net/ipv6/raw.c:raw6_proc_init
  - net/ipv6/mcast.c:igmp6_init
  - net/ipv6/reassembly.c:ipv6_frag_init
  - net/ipv6/tcp_ipv6.c:tcpv6_init
  - net/ipv6/ping.c:pingv6_init
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_init
  - net/ipv6/seg6.c:seg6_init
  - net/ipv6/ioam6.c:ioam6_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/ipv6/xfrm6_policy.c:xfrm6_init
  - net/ipv6/fib6_rules.c:fib6_rules_init
  - net/ipv6/proc.c:ipv6_misc_proc_init
  - net/packet/af_packet.c:packet_init
  - net/wireless/wext-core.c:wireless_nlevent_init
  - net/sysctl_net.c:net_sysctl_init
  - net/xdp/xsk.c:xsk_init
  - net/mptcp/ctrl.c:mptcp_init
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_init
  - net/mctp/route.c:mctp_routes_init
  - net/mctp/neigh.c:mctp_neigh_init
  - lib/kobject_uevent.c:kobject_uevent_init
```
**Symbols:**

```
ffffffff81db3f10-ffffffff81db3f56: register_pernet_subsys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int register_pernet_subsys(struct pernet_operations *ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff83732b0f)
Location: net/core/net_namespace.c:1271
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_defaults_init
Direct callers:
  - kernel/audit.c:audit_init
  - kernel/bpf/net_namespace.c:netns_bpf_init
  - fs/proc/proc_net.c:proc_net_init
  - security/selinux/hooks.c:selinux_nf_ip_init
  - security/smack/smack_netfilter.c:smack_nf_ip_init
  - security/apparmor/lsm.c:apparmor_nf_ip_init
  - net/core/sock.c:proto_init
  - net/core/sock.c:net_inuse_init
  - net/core/sysctl_net_core.c:sysctl_core_init
  - net/core/dev.c:net_dev_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/sock_diag.c:sock_diag_init
  - net/core/fib_notifier.c:fib_notifier_init
  - net/core/net-procfs.c:dev_proc_init
  - net/core/net-procfs.c:dev_proc_init
  - net/core/fib_rules.c:fib_rules_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/cls_api.c:tc_filter_init
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/genetlink.c:genl_init
  - net/netfilter/core.c:netfilter_init
  - net/netfilter/nf_log.c:netfilter_log_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/ip_fragment.c:ipfrag_init
  - net/ipv4/tcp_ipv4.c:tcp_v4_init
  - net/ipv4/tcp_ipv4.c:tcp4_proc_init
  - net/ipv4/tcp_metrics.c:tcp_metrics_init
  - net/ipv4/raw.c:raw_init
  - net/ipv4/raw.c:raw_proc_init
  - net/ipv4/udp.c:udp_init
  - net/ipv4/udp.c:udp4_proc_init
  - net/ipv4/udplite.c:udplite4_register
  - net/ipv4/arp.c:arp_init
  - net/ipv4/icmp.c:icmp_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/igmp.c:igmp_mc_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/ping.c:ping_proc_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init
  - net/ipv4/proc.c:ip_misc_proc_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/xfrm4_policy.c:xfrm4_init
  - net/xfrm/xfrm_policy.c:xfrm_init
  - net/unix/af_unix.c:af_unix_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:if6_proc_init
  - net/ipv6/addrlabel.c:ipv6_addr_label_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ndisc.c:ndisc_init
  - net/ipv6/udplite.c:udplite6_proc_init
  - net/ipv6/raw.c:raw6_proc_init
  - net/ipv6/mcast.c:igmp6_init
  - net/ipv6/reassembly.c:ipv6_frag_init
  - net/ipv6/tcp_ipv6.c:tcpv6_init
  - net/ipv6/ping.c:pingv6_init
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_init
  - net/ipv6/seg6.c:seg6_init
  - net/ipv6/ioam6.c:ioam6_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/ipv6/xfrm6_policy.c:xfrm6_init
  - net/ipv6/fib6_rules.c:fib6_rules_init
  - net/ipv6/proc.c:ipv6_misc_proc_init
  - net/packet/af_packet.c:packet_init
  - net/devlink/core.c:devlink_init
  - net/wireless/wext-core.c:wireless_nlevent_init
  - net/sysctl_net.c:net_sysctl_init
  - net/xdp/xsk.c:xsk_init
  - net/mptcp/ctrl.c:mptcp_init
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_init
  - net/mctp/route.c:mctp_routes_init
  - net/mctp/neigh.c:mctp_neigh_init
  - net/handshake/netlink.c:handshake_init
  - lib/kobject_uevent.c:kobject_uevent_init
```
**Symbols:**

```
ffffffff81e245c0-ffffffff81e24606: register_pernet_subsys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int register_pernet_subsys(struct pernet_operations *ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff83966fdf)
Location: net/core/net_namespace.c:1320
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_defaults_init
Direct callers:
  - kernel/audit.c:audit_init
  - kernel/bpf/net_namespace.c:netns_bpf_init
  - fs/proc/proc_net.c:proc_net_init
  - security/selinux/hooks.c:selinux_nf_ip_init
  - security/smack/smack_netfilter.c:smack_nf_ip_init
  - security/apparmor/lsm.c:apparmor_nf_ip_init
  - net/core/sock.c:proto_init
  - net/core/sock.c:net_inuse_init
  - net/core/sysctl_net_core.c:sysctl_core_init
  - net/core/dev.c:net_dev_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/sock_diag.c:sock_diag_init
  - net/core/fib_notifier.c:fib_notifier_init
  - net/core/net-procfs.c:dev_proc_init
  - net/core/net-procfs.c:dev_proc_init
  - net/core/fib_rules.c:fib_rules_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/cls_api.c:tc_filter_init
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/genetlink.c:genl_init
  - net/netfilter/core.c:netfilter_init
  - net/netfilter/nf_log.c:netfilter_log_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/ip_fragment.c:ipfrag_init
  - net/ipv4/tcp_ipv4.c:tcp_v4_init
  - net/ipv4/tcp_ipv4.c:tcp4_proc_init
  - net/ipv4/tcp_metrics.c:tcp_metrics_init
  - net/ipv4/raw.c:raw_init
  - net/ipv4/raw.c:raw_proc_init
  - net/ipv4/udp.c:udp_init
  - net/ipv4/udp.c:udp4_proc_init
  - net/ipv4/udplite.c:udplite4_register
  - net/ipv4/arp.c:arp_init
  - net/ipv4/icmp.c:icmp_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/igmp.c:igmp_mc_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/ping.c:ping_proc_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init
  - net/ipv4/proc.c:ip_misc_proc_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/xfrm4_policy.c:xfrm4_init
  - net/xfrm/xfrm_policy.c:xfrm_init
  - net/unix/af_unix.c:af_unix_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:if6_proc_init
  - net/ipv6/addrlabel.c:ipv6_addr_label_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ndisc.c:ndisc_init
  - net/ipv6/udplite.c:udplite6_proc_init
  - net/ipv6/raw.c:raw6_proc_init
  - net/ipv6/mcast.c:igmp6_init
  - net/ipv6/reassembly.c:ipv6_frag_init
  - net/ipv6/tcp_ipv6.c:tcpv6_init
  - net/ipv6/ping.c:pingv6_init
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_init
  - net/ipv6/seg6.c:seg6_init
  - net/ipv6/ioam6.c:ioam6_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/ipv6/xfrm6_policy.c:xfrm6_init
  - net/ipv6/fib6_rules.c:fib6_rules_init
  - net/ipv6/proc.c:ipv6_misc_proc_init
  - net/packet/af_packet.c:packet_init
  - net/devlink/core.c:devlink_init
  - net/wireless/wext-core.c:wireless_nlevent_init
  - net/sysctl_net.c:net_sysctl_init
  - net/xdp/xsk.c:xsk_init
  - net/mptcp/ctrl.c:mptcp_init
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_init
  - net/mctp/route.c:mctp_routes_init
  - net/mctp/neigh.c:mctp_neigh_init
  - net/handshake/netlink.c:handshake_init
  - lib/kobject_uevent.c:kobject_uevent_init
```
**Symbols:**

```
ffffffff81ee27d0-ffffffff81ee2816: register_pernet_subsys (STB_GLOBAL)
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
int register_pernet_subsys(struct pernet_operations *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffff800010bc0cf8)
Location: net/core/net_namespace.c:1256
Inline: False
Direct callers:
  - kernel/audit.c:audit_init
  - fs/proc/proc_net.c:proc_net_init
  - security/selinux/hooks.c:selinux_nf_ip_init
  - security/smack/smack_netfilter.c:smack_nf_ip_init
  - net/core/sock.c:proto_init
  - net/core/sock.c:net_inuse_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_defaults_init
  - net/core/sysctl_net_core.c:sysctl_core_init
  - net/core/dev.c:net_dev_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/sock_diag.c:sock_diag_init
  - net/core/fib_notifier.c:fib_notifier_init
  - net/core/net-procfs.c:dev_proc_init
  - net/core/net-procfs.c:dev_proc_init
  - net/core/fib_rules.c:fib_rules_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/cls_api.c:tc_filter_init
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/genetlink.c:genl_init
  - net/netfilter/core.c:netfilter_init
  - net/netfilter/nf_log.c:netfilter_log_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/ip_fragment.c:ipfrag_init
  - net/ipv4/tcp_ipv4.c:tcp_v4_init
  - net/ipv4/tcp_ipv4.c:tcp4_proc_init
  - net/ipv4/tcp_metrics.c:tcp_metrics_init
  - net/ipv4/raw.c:raw_init
  - net/ipv4/raw.c:raw_proc_init
  - net/ipv4/udp.c:udp_init
  - net/ipv4/udp.c:udp4_proc_init
  - net/ipv4/udplite.c:udplite4_register
  - net/ipv4/arp.c:arp_init
  - net/ipv4/icmp.c:icmp_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/igmp.c:igmp_mc_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/ping.c:ping_proc_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init
  - net/ipv4/proc.c:ip_misc_proc_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/xfrm4_policy.c:xfrm4_init
  - net/xfrm/xfrm_policy.c:xfrm_init
  - net/unix/af_unix.c:af_unix_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:if6_proc_init
  - net/ipv6/addrlabel.c:ipv6_addr_label_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ndisc.c:ndisc_init
  - net/ipv6/udplite.c:udplite6_proc_init
  - net/ipv6/raw.c:raw6_proc_init
  - net/ipv6/icmp.c:icmpv6_init
  - net/ipv6/mcast.c:igmp6_init
  - net/ipv6/reassembly.c:ipv6_frag_init
  - net/ipv6/tcp_ipv6.c:tcpv6_init
  - net/ipv6/ping.c:pingv6_init
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_init
  - net/ipv6/seg6.c:seg6_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/ipv6/xfrm6_policy.c:xfrm6_init
  - net/ipv6/fib6_rules.c:fib6_rules_init
  - net/ipv6/proc.c:ipv6_misc_proc_init
  - net/packet/af_packet.c:packet_init
  - net/wireless/wext-core.c:wireless_nlevent_init
  - net/sysctl_net.c:net_sysctl_init
  - net/xdp/xsk.c:xsk_init
  - lib/kobject_uevent.c:kobject_uevent_init
```
**Symbols:**

```
ffff800010bc0cf8-ffff800010bc0d48: register_pernet_subsys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int register_pernet_subsys(struct pernet_operations *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (c0cdcfc4)
Location: net/core/net_namespace.c:1256
Inline: False
Direct callers:
  - kernel/audit.c:audit_init
  - fs/proc/proc_net.c:proc_net_init
  - security/selinux/hooks.c:selinux_nf_ip_init
  - security/smack/smack_netfilter.c:smack_nf_ip_init
  - net/core/sock.c:proto_init
  - net/core/sock.c:net_inuse_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_defaults_init
  - net/core/sysctl_net_core.c:sysctl_core_init
  - net/core/dev.c:net_dev_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/sock_diag.c:sock_diag_init
  - net/core/fib_notifier.c:fib_notifier_init
  - net/core/net-procfs.c:dev_proc_init
  - net/core/net-procfs.c:dev_proc_init
  - net/core/fib_rules.c:fib_rules_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/cls_api.c:tc_filter_init
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/genetlink.c:genl_init
  - net/netfilter/core.c:netfilter_init
  - net/netfilter/nf_log.c:netfilter_log_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/ip_fragment.c:ipfrag_init
  - net/ipv4/tcp_ipv4.c:tcp_v4_init
  - net/ipv4/tcp_ipv4.c:tcp4_proc_init
  - net/ipv4/tcp_metrics.c:tcp_metrics_init
  - net/ipv4/raw.c:raw_init
  - net/ipv4/raw.c:raw_proc_init
  - net/ipv4/udp.c:udp_init
  - net/ipv4/udp.c:udp4_proc_init
  - net/ipv4/udplite.c:udplite4_register
  - net/ipv4/arp.c:arp_init
  - net/ipv4/icmp.c:icmp_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/igmp.c:igmp_mc_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/ping.c:ping_proc_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init
  - net/ipv4/proc.c:ip_misc_proc_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/xfrm4_policy.c:xfrm4_init
  - net/xfrm/xfrm_policy.c:xfrm_init
  - net/unix/af_unix.c:af_unix_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:if6_proc_init
  - net/ipv6/addrlabel.c:ipv6_addr_label_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ndisc.c:ndisc_init
  - net/ipv6/udplite.c:udplite6_proc_init
  - net/ipv6/raw.c:raw6_proc_init
  - net/ipv6/icmp.c:icmpv6_init
  - net/ipv6/mcast.c:igmp6_init
  - net/ipv6/reassembly.c:ipv6_frag_init
  - net/ipv6/tcp_ipv6.c:tcpv6_init
  - net/ipv6/ping.c:pingv6_init
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_init
  - net/ipv6/seg6.c:seg6_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/ipv6/xfrm6_policy.c:xfrm6_init
  - net/ipv6/fib6_rules.c:fib6_rules_init
  - net/ipv6/proc.c:ipv6_misc_proc_init
  - net/packet/af_packet.c:packet_init
  - net/wireless/wext-core.c:wireless_nlevent_init
  - net/sysctl_net.c:net_sysctl_init
  - net/xdp/xsk.c:xsk_init
  - lib/kobject_uevent.c:kobject_uevent_init
```
**Symbols:**

```
c0cdcfc4-c0cdd00c: register_pernet_subsys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int register_pernet_subsys(struct pernet_operations *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (c000000000c9b160)
Location: net/core/net_namespace.c:1256
Inline: False
Direct callers:
  - kernel/audit.c:audit_init
  - fs/proc/proc_net.c:proc_net_init
  - security/selinux/hooks.c:selinux_nf_ip_init
  - security/smack/smack_netfilter.c:smack_nf_ip_init
  - net/core/sock.c:proto_init
  - net/core/sock.c:net_inuse_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_defaults_init
  - net/core/sysctl_net_core.c:sysctl_core_init
  - net/core/dev.c:net_dev_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/sock_diag.c:sock_diag_init
  - net/core/fib_notifier.c:fib_notifier_init
  - net/core/net-procfs.c:dev_proc_init
  - net/core/net-procfs.c:dev_proc_init
  - net/core/fib_rules.c:fib_rules_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/cls_api.c:tc_filter_init
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/genetlink.c:genl_init
  - net/netfilter/core.c:netfilter_init
  - net/netfilter/nf_log.c:netfilter_log_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/ip_fragment.c:ipfrag_init
  - net/ipv4/tcp_ipv4.c:tcp_v4_init
  - net/ipv4/tcp_ipv4.c:tcp4_proc_init
  - net/ipv4/tcp_metrics.c:tcp_metrics_init
  - net/ipv4/raw.c:raw_init
  - net/ipv4/raw.c:raw_proc_init
  - net/ipv4/udp.c:udp_init
  - net/ipv4/udp.c:udp4_proc_init
  - net/ipv4/udplite.c:udplite4_register
  - net/ipv4/arp.c:arp_init
  - net/ipv4/icmp.c:icmp_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/igmp.c:igmp_mc_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/ping.c:ping_proc_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init
  - net/ipv4/proc.c:ip_misc_proc_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/xfrm4_policy.c:xfrm4_init
  - net/xfrm/xfrm_policy.c:xfrm_init
  - net/unix/af_unix.c:af_unix_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:if6_proc_init
  - net/ipv6/addrlabel.c:ipv6_addr_label_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ndisc.c:ndisc_init
  - net/ipv6/udplite.c:udplite6_proc_init
  - net/ipv6/raw.c:raw6_proc_init
  - net/ipv6/icmp.c:icmpv6_init
  - net/ipv6/mcast.c:igmp6_init
  - net/ipv6/reassembly.c:ipv6_frag_init
  - net/ipv6/tcp_ipv6.c:tcpv6_init
  - net/ipv6/ping.c:pingv6_init
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_init
  - net/ipv6/seg6.c:seg6_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/ipv6/xfrm6_policy.c:xfrm6_init
  - net/ipv6/fib6_rules.c:fib6_rules_init
  - net/ipv6/proc.c:ipv6_misc_proc_init
  - net/packet/af_packet.c:packet_init
  - net/wireless/wext-core.c:wireless_nlevent_init
  - net/sysctl_net.c:net_sysctl_init
  - net/xdp/xsk.c:xsk_init
  - lib/kobject_uevent.c:kobject_uevent_init
```
**Symbols:**

```
c000000000c9b160-c000000000c9b1d8: register_pernet_subsys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int register_pernet_subsys(struct pernet_operations *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffe00074eb40)
Location: net/core/net_namespace.c:1256
Inline: False
Direct callers:
  - kernel/audit.c:audit_init
  - fs/proc/proc_net.c:proc_net_init
  - security/selinux/hooks.c:selinux_nf_ip_init
  - security/smack/smack_netfilter.c:smack_nf_ip_init
  - net/core/sock.c:proto_init
  - net/core/sock.c:net_inuse_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_defaults_init
  - net/core/sysctl_net_core.c:sysctl_core_init
  - net/core/dev.c:net_dev_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/sock_diag.c:sock_diag_init
  - net/core/fib_notifier.c:fib_notifier_init
  - net/core/net-procfs.c:dev_proc_init
  - net/core/net-procfs.c:dev_proc_init
  - net/core/fib_rules.c:fib_rules_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/cls_api.c:tc_filter_init
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/genetlink.c:genl_init
  - net/netfilter/core.c:netfilter_init
  - net/netfilter/nf_log.c:netfilter_log_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/ip_fragment.c:ipfrag_init
  - net/ipv4/tcp_ipv4.c:tcp_v4_init
  - net/ipv4/tcp_ipv4.c:tcp4_proc_init
  - net/ipv4/tcp_metrics.c:tcp_metrics_init
  - net/ipv4/raw.c:raw_init
  - net/ipv4/raw.c:raw_proc_init
  - net/ipv4/udp.c:udp_init
  - net/ipv4/udp.c:udp4_proc_init
  - net/ipv4/udplite.c:udplite4_register
  - net/ipv4/arp.c:arp_init
  - net/ipv4/icmp.c:icmp_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/igmp.c:igmp_mc_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/ping.c:ping_proc_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init
  - net/ipv4/proc.c:ip_misc_proc_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/xfrm4_policy.c:xfrm4_init
  - net/xfrm/xfrm_policy.c:xfrm_init
  - net/unix/af_unix.c:af_unix_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:if6_proc_init
  - net/ipv6/addrlabel.c:ipv6_addr_label_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ndisc.c:ndisc_init
  - net/ipv6/udplite.c:udplite6_proc_init
  - net/ipv6/raw.c:raw6_proc_init
  - net/ipv6/icmp.c:icmpv6_init
  - net/ipv6/mcast.c:igmp6_init
  - net/ipv6/reassembly.c:ipv6_frag_init
  - net/ipv6/tcp_ipv6.c:tcpv6_init
  - net/ipv6/ping.c:pingv6_init
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_init
  - net/ipv6/seg6.c:seg6_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/ipv6/xfrm6_policy.c:xfrm6_init
  - net/ipv6/fib6_rules.c:fib6_rules_init
  - net/ipv6/proc.c:ipv6_misc_proc_init
  - net/packet/af_packet.c:packet_init
  - net/wireless/wext-core.c:wireless_nlevent_init
  - net/sysctl_net.c:net_sysctl_init
  - net/xdp/xsk.c:xsk_init
  - lib/kobject_uevent.c:kobject_uevent_init
```
**Symbols:**

```
ffffffe00074eb40-ffffffe00074eb96: register_pernet_subsys (STB_GLOBAL)
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
int register_pernet_subsys(struct pernet_operations *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff818c51c0)
Location: net/core/net_namespace.c:1256
Inline: False
Direct callers:
  - kernel/audit.c:audit_init
  - fs/proc/proc_net.c:proc_net_init
  - security/selinux/hooks.c:selinux_nf_ip_init
  - security/smack/smack_netfilter.c:smack_nf_ip_init
  - net/core/sock.c:proto_init
  - net/core/sock.c:net_inuse_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_defaults_init
  - net/core/sysctl_net_core.c:sysctl_core_init
  - net/core/dev.c:net_dev_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/sock_diag.c:sock_diag_init
  - net/core/fib_notifier.c:fib_notifier_init
  - net/core/net-procfs.c:dev_proc_init
  - net/core/net-procfs.c:dev_proc_init
  - net/core/fib_rules.c:fib_rules_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/cls_api.c:tc_filter_init
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/genetlink.c:genl_init
  - net/netfilter/core.c:netfilter_init
  - net/netfilter/nf_log.c:netfilter_log_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/ip_fragment.c:ipfrag_init
  - net/ipv4/tcp_ipv4.c:tcp_v4_init
  - net/ipv4/tcp_ipv4.c:tcp4_proc_init
  - net/ipv4/tcp_metrics.c:tcp_metrics_init
  - net/ipv4/raw.c:raw_init
  - net/ipv4/raw.c:raw_proc_init
  - net/ipv4/udp.c:udp_init
  - net/ipv4/udp.c:udp4_proc_init
  - net/ipv4/udplite.c:udplite4_register
  - net/ipv4/arp.c:arp_init
  - net/ipv4/icmp.c:icmp_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/igmp.c:igmp_mc_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/ping.c:ping_proc_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init
  - net/ipv4/proc.c:ip_misc_proc_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/xfrm4_policy.c:xfrm4_init
  - net/xfrm/xfrm_policy.c:xfrm_init
  - net/unix/af_unix.c:af_unix_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:if6_proc_init
  - net/ipv6/addrlabel.c:ipv6_addr_label_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ndisc.c:ndisc_init
  - net/ipv6/udplite.c:udplite6_proc_init
  - net/ipv6/raw.c:raw6_proc_init
  - net/ipv6/icmp.c:icmpv6_init
  - net/ipv6/mcast.c:igmp6_init
  - net/ipv6/reassembly.c:ipv6_frag_init
  - net/ipv6/tcp_ipv6.c:tcpv6_init
  - net/ipv6/ping.c:pingv6_init
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_init
  - net/ipv6/seg6.c:seg6_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/ipv6/xfrm6_policy.c:xfrm6_init
  - net/ipv6/fib6_rules.c:fib6_rules_init
  - net/ipv6/proc.c:ipv6_misc_proc_init
  - net/packet/af_packet.c:packet_init
  - net/wireless/wext-core.c:wireless_nlevent_init
  - net/sysctl_net.c:net_sysctl_init
  - net/xdp/xsk.c:xsk_init
  - lib/kobject_uevent.c:kobject_uevent_init
```
**Symbols:**

```
ffffffff818c51c0-ffffffff818c51ff: register_pernet_subsys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int register_pernet_subsys(struct pernet_operations *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff8187f100)
Location: net/core/net_namespace.c:1256
Inline: False
Direct callers:
  - kernel/audit.c:audit_init
  - fs/proc/proc_net.c:proc_net_init
  - security/selinux/hooks.c:selinux_nf_ip_init
  - security/smack/smack_netfilter.c:smack_nf_ip_init
  - drivers/net/vxlan.c:vxlan_init_module
  - net/core/sock.c:proto_init
  - net/core/sock.c:net_inuse_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_defaults_init
  - net/core/sysctl_net_core.c:sysctl_core_init
  - net/core/dev.c:net_dev_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/sock_diag.c:sock_diag_init
  - net/core/fib_notifier.c:fib_notifier_init
  - net/core/net-procfs.c:dev_proc_init
  - net/core/net-procfs.c:dev_proc_init
  - net/core/fib_rules.c:fib_rules_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/cls_api.c:tc_filter_init
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/genetlink.c:genl_init
  - net/netfilter/core.c:netfilter_init
  - net/netfilter/nf_log.c:netfilter_log_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/ip_fragment.c:ipfrag_init
  - net/ipv4/tcp_ipv4.c:tcp_v4_init
  - net/ipv4/tcp_ipv4.c:tcp4_proc_init
  - net/ipv4/tcp_metrics.c:tcp_metrics_init
  - net/ipv4/raw.c:raw_init
  - net/ipv4/raw.c:raw_proc_init
  - net/ipv4/udp.c:udp_init
  - net/ipv4/udp.c:udp4_proc_init
  - net/ipv4/udplite.c:udplite4_register
  - net/ipv4/arp.c:arp_init
  - net/ipv4/icmp.c:icmp_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/igmp.c:igmp_mc_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/ping.c:ping_proc_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init
  - net/ipv4/proc.c:ip_misc_proc_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/xfrm4_policy.c:xfrm4_init
  - net/xfrm/xfrm_policy.c:xfrm_init
  - net/unix/af_unix.c:af_unix_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:if6_proc_init
  - net/ipv6/addrlabel.c:ipv6_addr_label_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ndisc.c:ndisc_init
  - net/ipv6/udplite.c:udplite6_proc_init
  - net/ipv6/raw.c:raw6_proc_init
  - net/ipv6/icmp.c:icmpv6_init
  - net/ipv6/mcast.c:igmp6_init
  - net/ipv6/reassembly.c:ipv6_frag_init
  - net/ipv6/tcp_ipv6.c:tcpv6_init
  - net/ipv6/ping.c:pingv6_init
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_init
  - net/ipv6/seg6.c:seg6_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/ipv6/xfrm6_policy.c:xfrm6_init
  - net/ipv6/fib6_rules.c:fib6_rules_init
  - net/ipv6/proc.c:ipv6_misc_proc_init
  - net/packet/af_packet.c:packet_init
  - net/wireless/wext-core.c:wireless_nlevent_init
  - net/sysctl_net.c:net_sysctl_init
  - net/xdp/xsk.c:xsk_init
  - lib/kobject_uevent.c:kobject_uevent_init
```
**Symbols:**

```
ffffffff8187f100-ffffffff8187f13f: register_pernet_subsys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int register_pernet_subsys(struct pernet_operations *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff819161c0)
Location: net/core/net_namespace.c:1256
Inline: False
Direct callers:
  - kernel/audit.c:audit_init
  - fs/proc/proc_net.c:proc_net_init
  - security/selinux/hooks.c:selinux_nf_ip_init
  - security/smack/smack_netfilter.c:smack_nf_ip_init
  - net/core/sock.c:proto_init
  - net/core/sock.c:net_inuse_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_defaults_init
  - net/core/sysctl_net_core.c:sysctl_core_init
  - net/core/dev.c:net_dev_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/sock_diag.c:sock_diag_init
  - net/core/fib_notifier.c:fib_notifier_init
  - net/core/net-procfs.c:dev_proc_init
  - net/core/net-procfs.c:dev_proc_init
  - net/core/fib_rules.c:fib_rules_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/cls_api.c:tc_filter_init
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/genetlink.c:genl_init
  - net/netfilter/core.c:netfilter_init
  - net/netfilter/nf_log.c:netfilter_log_init
  - net/netfilter/nfnetlink.c:nfnetlink_init
  - net/netfilter/nfnetlink_queue.c:nfnetlink_queue_init
  - net/netfilter/nfnetlink_log.c:nfnetlink_log_init
  - net/netfilter/nf_conntrack_standalone.c:nf_conntrack_standalone_init
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/ip_fragment.c:ipfrag_init
  - net/ipv4/tcp_ipv4.c:tcp_v4_init
  - net/ipv4/tcp_ipv4.c:tcp4_proc_init
  - net/ipv4/tcp_metrics.c:tcp_metrics_init
  - net/ipv4/raw.c:raw_init
  - net/ipv4/raw.c:raw_proc_init
  - net/ipv4/udp.c:udp_init
  - net/ipv4/udp.c:udp4_proc_init
  - net/ipv4/udplite.c:udplite4_register
  - net/ipv4/arp.c:arp_init
  - net/ipv4/icmp.c:icmp_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/igmp.c:igmp_mc_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/ping.c:ping_proc_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init
  - net/ipv4/proc.c:ip_misc_proc_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/netfilter/nf_defrag_ipv4.c:nf_defrag_init
  - net/ipv4/xfrm4_policy.c:xfrm4_init
  - net/xfrm/xfrm_policy.c:xfrm_init
  - net/unix/af_unix.c:af_unix_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:if6_proc_init
  - net/ipv6/addrlabel.c:ipv6_addr_label_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ndisc.c:ndisc_init
  - net/ipv6/udplite.c:udplite6_proc_init
  - net/ipv6/raw.c:raw6_proc_init
  - net/ipv6/icmp.c:icmpv6_init
  - net/ipv6/mcast.c:igmp6_init
  - net/ipv6/reassembly.c:ipv6_frag_init
  - net/ipv6/tcp_ipv6.c:tcpv6_init
  - net/ipv6/ping.c:pingv6_init
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_init
  - net/ipv6/seg6.c:seg6_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/ipv6/xfrm6_policy.c:xfrm6_init
  - net/ipv6/fib6_rules.c:fib6_rules_init
  - net/ipv6/proc.c:ipv6_misc_proc_init
  - net/ipv6/netfilter/nf_defrag_ipv6_hooks.c:nf_defrag_init
  - net/ipv6/netfilter/nf_conntrack_reasm.c:nf_ct_frag6_init
  - net/packet/af_packet.c:packet_init
  - net/wireless/wext-core.c:wireless_nlevent_init
  - net/sysctl_net.c:net_sysctl_init
  - net/xdp/xsk.c:xsk_init
  - lib/kobject_uevent.c:kobject_uevent_init
```
**Symbols:**

```
ffffffff819161c0-ffffffff819161ff: register_pernet_subsys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int register_pernet_subsys(struct pernet_operations *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff819373c0)
Location: net/core/net_namespace.c:1256
Inline: False
Direct callers:
  - kernel/audit.c:audit_init
  - fs/proc/proc_net.c:proc_net_init
  - security/selinux/hooks.c:selinux_nf_ip_init
  - security/smack/smack_netfilter.c:smack_nf_ip_init
  - net/core/sock.c:proto_init
  - net/core/sock.c:net_inuse_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_defaults_init
  - net/core/sysctl_net_core.c:sysctl_core_init
  - net/core/dev.c:net_dev_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/sock_diag.c:sock_diag_init
  - net/core/fib_notifier.c:fib_notifier_init
  - net/core/net-procfs.c:dev_proc_init
  - net/core/net-procfs.c:dev_proc_init
  - net/core/fib_rules.c:fib_rules_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/cls_api.c:tc_filter_init
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/genetlink.c:genl_init
  - net/netfilter/core.c:netfilter_init
  - net/netfilter/nf_log.c:netfilter_log_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/ip_fragment.c:ipfrag_init
  - net/ipv4/tcp_ipv4.c:tcp_v4_init
  - net/ipv4/tcp_ipv4.c:tcp4_proc_init
  - net/ipv4/tcp_metrics.c:tcp_metrics_init
  - net/ipv4/raw.c:raw_init
  - net/ipv4/raw.c:raw_proc_init
  - net/ipv4/udp.c:udp_init
  - net/ipv4/udp.c:udp4_proc_init
  - net/ipv4/udplite.c:udplite4_register
  - net/ipv4/arp.c:arp_init
  - net/ipv4/icmp.c:icmp_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/igmp.c:igmp_mc_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/ping.c:ping_proc_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init
  - net/ipv4/proc.c:ip_misc_proc_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/xfrm4_policy.c:xfrm4_init
  - net/xfrm/xfrm_policy.c:xfrm_init
  - net/unix/af_unix.c:af_unix_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:if6_proc_init
  - net/ipv6/addrlabel.c:ipv6_addr_label_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ndisc.c:ndisc_init
  - net/ipv6/udplite.c:udplite6_proc_init
  - net/ipv6/raw.c:raw6_proc_init
  - net/ipv6/icmp.c:icmpv6_init
  - net/ipv6/mcast.c:igmp6_init
  - net/ipv6/reassembly.c:ipv6_frag_init
  - net/ipv6/tcp_ipv6.c:tcpv6_init
  - net/ipv6/ping.c:pingv6_init
  - net/ipv6/ip6_flowlabel.c:ip6_flowlabel_init
  - net/ipv6/seg6.c:seg6_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/ipv6/xfrm6_policy.c:xfrm6_init
  - net/ipv6/fib6_rules.c:fib6_rules_init
  - net/ipv6/proc.c:ipv6_misc_proc_init
  - net/packet/af_packet.c:packet_init
  - net/wireless/wext-core.c:wireless_nlevent_init
  - net/sysctl_net.c:net_sysctl_init
  - net/xdp/xsk.c:xsk_init
  - lib/kobject_uevent.c:kobject_uevent_init
```
**Symbols:**

```
ffffffff819373c0-ffffffff819373ff: register_pernet_subsys (STB_GLOBAL)
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
