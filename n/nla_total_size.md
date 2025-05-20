# Function: <code>nla_total_size</code>

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
In kernel/taskstats.c (0)
Location: include/net/netlink.h:642
Inline: True
```
```
In fs/quota/netlink.c (0)
Location: include/net/netlink.h:642
Inline: True
```
```
In lib/nlattr.c (ffffffff814159fa)
Location: include/net/netlink.h:642
Inline: True
Inline callers:
  - lib/nlattr.c:__nla_reserve
```
```
In drivers/acpi/event.c (0)
Location: include/net/netlink.h:642
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/net/netlink.h:642
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:642
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/net/netlink.h:642
Inline: True
```
```
In net/core/rtnetlink.c (0)
Location: include/net/netlink.h:642
Inline: True
```
```
In net/core/sock_diag.c (0)
Location: include/net/netlink.h:642
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:642
Inline: True
```
```
In net/core/lwtunnel.c (ffffffff8173e105)
Location: include/net/netlink.h:642
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_get_encap_size
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netlink.h:642
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/net/netlink.h:642
Inline: True
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/net/netlink.h:642
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (0)
Location: include/net/netlink.h:642
Inline: True
```
```
In net/ipv4/fib_rules.c (0)
Location: include/net/netlink.h:642
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/net/netlink.h:642
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/netlink.h:642
Inline: True
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:642
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/net/netlink.h:642
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/net/netlink.h:642
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/net/netlink.h:642
Inline: True
```
```
In net/ipv6/fib6_rules.c (0)
Location: include/net/netlink.h:642
Inline: True
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
In kernel/taskstats.c (0)
Location: include/net/netlink.h:653
Inline: True
```
```
In fs/quota/netlink.c (0)
Location: include/net/netlink.h:653
Inline: True
```
```
In lib/nlattr.c (ffffffff8145d846)
Location: include/net/netlink.h:653
Inline: True
Inline callers:
  - lib/nlattr.c:nla_put_64bit
  - lib/nlattr.c:nla_put
  - lib/nlattr.c:nla_reserve_64bit
  - lib/nlattr.c:__nla_reserve
  - lib/nlattr.c:nla_policy_len
```
```
In drivers/acpi/event.c (0)
Location: include/net/netlink.h:653
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/net/netlink.h:653
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:653
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/net/netlink.h:653
Inline: True
```
```
In net/core/rtnetlink.c (ffffffff817966bb)
Location: include/net/netlink.h:653
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:if_nlmsg_size
  - net/core/rtnetlink.c:if_nlmsg_size
  - net/core/rtnetlink.c:if_nlmsg_size
```
```
In net/core/sock_diag.c (0)
Location: include/net/netlink.h:653
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:653
Inline: True
```
```
In net/core/lwtunnel.c (ffffffff817aa975)
Location: include/net/netlink.h:653
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_get_encap_size
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netlink.h:653
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/net/netlink.h:653
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff8180b98a)
Location: include/net/netlink.h:653
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/ip_tunnel_core.c (0)
Location: include/net/netlink.h:653
Inline: True
```
```
In net/ipv4/fib_rules.c (0)
Location: include/net/netlink.h:653
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/net/netlink.h:653
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/netlink.h:653
Inline: True
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:653
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/net/netlink.h:653
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/net/netlink.h:653
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/net/netlink.h:653
Inline: True
```
```
In net/ipv6/fib6_rules.c (0)
Location: include/net/netlink.h:653
Inline: True
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
In kernel/taskstats.c (0)
Location: include/net/netlink.h:653
Inline: True
```
```
In fs/quota/netlink.c (0)
Location: include/net/netlink.h:653
Inline: True
```
```
In lib/nlattr.c (ffffffff8147c306)
Location: include/net/netlink.h:653
Inline: True
Inline callers:
  - lib/nlattr.c:nla_put_64bit
  - lib/nlattr.c:nla_put
  - lib/nlattr.c:nla_reserve_64bit
  - lib/nlattr.c:__nla_reserve
  - lib/nlattr.c:nla_policy_len
```
```
In drivers/acpi/event.c (0)
Location: include/net/netlink.h:653
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/net/netlink.h:653
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:653
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/net/netlink.h:653
Inline: True
```
```
In net/core/rtnetlink.c (ffffffff817c4cd9)
Location: include/net/netlink.h:653
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:if_nlmsg_size
  - net/core/rtnetlink.c:if_nlmsg_size
```
```
In net/core/sock_diag.c (0)
Location: include/net/netlink.h:653
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:653
Inline: True
```
```
In net/core/lwtunnel.c (ffffffff817d94f5)
Location: include/net/netlink.h:653
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_get_encap_size
```
```
In net/core/lwt_bpf.c (0)
Location: include/net/netlink.h:653
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netlink.h:653
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/net/netlink.h:653
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff8183caaa)
Location: include/net/netlink.h:653
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/ip_tunnel_core.c (0)
Location: include/net/netlink.h:653
Inline: True
```
```
In net/ipv4/fib_rules.c (0)
Location: include/net/netlink.h:653
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/net/netlink.h:653
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/netlink.h:653
Inline: True
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:653
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/net/netlink.h:653
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/net/netlink.h:653
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/net/netlink.h:653
Inline: True
```
```
In net/ipv6/fib6_rules.c (0)
Location: include/net/netlink.h:653
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff818a3e9e)
Location: include/net/netlink.h:653
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_encap_nlsize
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
In kernel/taskstats.c (0)
Location: include/net/netlink.h:662
Inline: True
```
```
In fs/quota/netlink.c (0)
Location: include/net/netlink.h:662
Inline: True
```
```
In lib/nlattr.c (ffffffff81485626)
Location: include/net/netlink.h:662
Inline: True
Inline callers:
  - lib/nlattr.c:nla_put_64bit
  - lib/nlattr.c:nla_put
  - lib/nlattr.c:nla_reserve_64bit
  - lib/nlattr.c:__nla_reserve
  - lib/nlattr.c:nla_policy_len
```
```
In drivers/acpi/event.c (0)
Location: include/net/netlink.h:662
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/net/netlink.h:662
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:662
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/net/netlink.h:662
Inline: True
```
```
In net/core/rtnetlink.c (ffffffff817e3708)
Location: include/net/netlink.h:662
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:if_nlmsg_size
  - net/core/rtnetlink.c:if_nlmsg_size
  - net/core/rtnetlink.c:if_nlmsg_size
```
```
In net/core/sock_diag.c (0)
Location: include/net/netlink.h:662
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:662
Inline: True
```
```
In net/core/lwtunnel.c (ffffffff817f8704)
Location: include/net/netlink.h:662
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_get_encap_size
```
```
In net/core/lwt_bpf.c (0)
Location: include/net/netlink.h:662
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff8180a4a0)
Location: include/net/netlink.h:662
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netlink.h:662
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/net/netlink.h:662
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff8185e133)
Location: include/net/netlink.h:662
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/ip_tunnel_core.c (0)
Location: include/net/netlink.h:662
Inline: True
```
```
In net/ipv4/fib_rules.c (0)
Location: include/net/netlink.h:662
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81869659)
Location: include/net/netlink.h:662
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/netlink.h:662
Inline: True
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:662
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/net/netlink.h:662
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/net/netlink.h:662
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff818c15c9)
Location: include/net/netlink.h:662
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/fib6_rules.c (0)
Location: include/net/netlink.h:662
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff818ca40e)
Location: include/net/netlink.h:662
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_encap_nlsize
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
In kernel/taskstats.c (0)
Location: include/net/netlink.h:668
Inline: True
```
```
In fs/quota/netlink.c (0)
Location: include/net/netlink.h:668
Inline: True
```
```
In lib/nlattr.c (ffffffff814c17b6)
Location: include/net/netlink.h:668
Inline: True
Inline callers:
  - lib/nlattr.c:nla_put_64bit
  - lib/nlattr.c:nla_put
  - lib/nlattr.c:nla_reserve_64bit
  - lib/nlattr.c:__nla_reserve
  - lib/nlattr.c:nla_policy_len
```
```
In drivers/acpi/event.c (0)
Location: include/net/netlink.h:668
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/net/netlink.h:668
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:668
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/net/netlink.h:668
Inline: True
```
```
In net/core/rtnetlink.c (ffffffff8185e63b)
Location: include/net/netlink.h:668
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:if_nlmsg_size
  - net/core/rtnetlink.c:if_nlmsg_size
  - net/core/rtnetlink.c:if_nlmsg_size
```
```
In net/core/sock_diag.c (0)
Location: include/net/netlink.h:668
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:668
Inline: True
```
```
In net/core/lwtunnel.c (ffffffff81875fd7)
Location: include/net/netlink.h:668
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_get_encap_size
```
```
In net/core/lwt_bpf.c (0)
Location: include/net/netlink.h:668
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81889281)
Location: include/net/netlink.h:668
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/ipv4/tcp.c (0)
Location: include/net/netlink.h:668
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netlink.h:668
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/net/netlink.h:668
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff818de173)
Location: include/net/netlink.h:668
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/ip_tunnel_core.c (0)
Location: include/net/netlink.h:668
Inline: True
```
```
In net/ipv4/fib_rules.c (0)
Location: include/net/netlink.h:668
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff818e9ca6)
Location: include/net/netlink.h:668
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/netlink.h:668
Inline: True
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:668
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/net/netlink.h:668
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/net/netlink.h:668
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81944919)
Location: include/net/netlink.h:668
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/fib6_rules.c (0)
Location: include/net/netlink.h:668
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff8194db9e)
Location: include/net/netlink.h:668
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_encap_nlsize
```
```
In net/ipv6/seg6_local.c (0)
Location: include/net/netlink.h:668
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
In kernel/taskstats.c (0)
Location: include/net/netlink.h:668
Inline: True
```
```
In fs/quota/netlink.c (0)
Location: include/net/netlink.h:668
Inline: True
```
```
In lib/nlattr.c (ffffffff814f24e0)
Location: include/net/netlink.h:668
Inline: True
Inline callers:
  - lib/nlattr.c:nla_put_64bit
  - lib/nlattr.c:nla_put
  - lib/nlattr.c:nla_reserve_64bit
  - lib/nlattr.c:nla_reserve
  - lib/nlattr.c:__nla_reserve
  - lib/nlattr.c:nla_policy_len
```
```
In drivers/acpi/event.c (0)
Location: include/net/netlink.h:668
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/net/netlink.h:668
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/net/netlink.h:668
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:668
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/net/netlink.h:668
Inline: True
```
```
In net/core/rtnetlink.c (ffffffff818aa1ec)
Location: include/net/netlink.h:668
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:if_nlmsg_size
  - net/core/rtnetlink.c:if_nlmsg_size
  - net/core/rtnetlink.c:if_nlmsg_size
```
```
In net/core/sock_diag.c (0)
Location: include/net/netlink.h:668
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:668
Inline: True
```
```
In net/core/lwtunnel.c (ffffffff818c76f7)
Location: include/net/netlink.h:668
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_get_encap_size
```
```
In net/core/lwt_bpf.c (0)
Location: include/net/netlink.h:668
Inline: True
```
```
In net/sched/act_api.c (ffffffff818d7767)
Location: include/net/netlink.h:668
Inline: True
Inline callers:
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_action_init
```
```
In net/netlink/af_netlink.c (ffffffff818dccfb)
Location: include/net/netlink.h:668
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/ipv4/tcp.c (0)
Location: include/net/netlink.h:668
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netlink.h:668
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/net/netlink.h:668
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff81934ce0)
Location: include/net/netlink.h:668
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/ip_tunnel_core.c (0)
Location: include/net/netlink.h:668
Inline: True
```
```
In net/ipv4/fib_rules.c (0)
Location: include/net/netlink.h:668
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff8194036c)
Location: include/net/netlink.h:668
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/netlink.h:668
Inline: True
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:668
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/net/netlink.h:668
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/net/netlink.h:668
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff8199d643)
Location: include/net/netlink.h:668
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/fib6_rules.c (0)
Location: include/net/netlink.h:668
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819a6e15)
Location: include/net/netlink.h:668
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_encap_nlsize
```
```
In net/ipv6/seg6_local.c (ffffffff819a7d6b)
Location: include/net/netlink.h:668
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_get_encap_size
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
In kernel/taskstats.c (0)
Location: include/net/netlink.h:811
Inline: True
```
```
In fs/quota/netlink.c (0)
Location: include/net/netlink.h:811
Inline: True
```
```
In lib/nlattr.c (ffffffff81506220)
Location: include/net/netlink.h:811
Inline: True
Inline callers:
  - lib/nlattr.c:nla_put_64bit
  - lib/nlattr.c:nla_put
  - lib/nlattr.c:nla_reserve_64bit
  - lib/nlattr.c:nla_reserve
  - lib/nlattr.c:__nla_reserve
  - lib/nlattr.c:nla_policy_len
```
```
In drivers/acpi/event.c (0)
Location: include/net/netlink.h:811
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/net/netlink.h:811
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/net/netlink.h:811
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:811
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/net/netlink.h:811
Inline: True
```
```
In net/core/rtnetlink.c (ffffffff818ce8dc)
Location: include/net/netlink.h:811
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:if_nlmsg_size
  - net/core/rtnetlink.c:if_nlmsg_size
  - net/core/rtnetlink.c:if_nlmsg_size
```
```
In net/core/sock_diag.c (0)
Location: include/net/netlink.h:811
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:811
Inline: True
```
```
In net/core/lwtunnel.c (ffffffff818f0837)
Location: include/net/netlink.h:811
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_get_encap_size
```
```
In net/core/lwt_bpf.c (0)
Location: include/net/netlink.h:811
Inline: True
```
```
In net/sched/act_api.c (ffffffff81903b73)
Location: include/net/netlink.h:811
Inline: True
Inline callers:
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_action_init
```
```
In net/netlink/af_netlink.c (ffffffff819096cb)
Location: include/net/netlink.h:811
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/ipv4/tcp.c (0)
Location: include/net/netlink.h:811
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netlink.h:811
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/net/netlink.h:811
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff81964630)
Location: include/net/netlink.h:811
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/ip_tunnel_core.c (0)
Location: include/net/netlink.h:811
Inline: True
```
```
In net/ipv4/fib_rules.c (0)
Location: include/net/netlink.h:811
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff819701e9)
Location: include/net/netlink.h:811
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/netlink.h:811
Inline: True
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:811
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/net/netlink.h:811
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/net/netlink.h:811
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff819d4189)
Location: include/net/netlink.h:811
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/fib6_rules.c (0)
Location: include/net/netlink.h:811
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819dd975)
Location: include/net/netlink.h:811
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_encap_nlsize
```
```
In net/ipv6/seg6_local.c (ffffffff819de8cb)
Location: include/net/netlink.h:811
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_get_encap_size
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
In kernel/taskstats.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In fs/quota/netlink.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In lib/nlattr.c (ffffffff81534be0)
Location: include/net/netlink.h:1045
Inline: True
Inline callers:
  - lib/nlattr.c:nla_put_64bit
  - lib/nlattr.c:nla_put
  - lib/nlattr.c:nla_reserve_64bit
  - lib/nlattr.c:__nla_reserve
  - lib/nlattr.c:nla_policy_len
```
```
In drivers/acpi/event.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/core/rtnetlink.c (ffffffff8191b6d2)
Location: include/net/netlink.h:1045
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:if_nlmsg_size
  - net/core/rtnetlink.c:if_nlmsg_size
  - net/core/rtnetlink.c:if_nlmsg_size
```
```
In net/core/sock_diag.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/core/lwtunnel.c (ffffffff8194263a)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/core/lwt_bpf.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/sched/act_api.c (ffffffff81962d5d)
Location: include/net/netlink.h:1045
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_fill_size
```
```
In net/netlink/af_netlink.c (ffffffff8196a9dd)
Location: include/net/netlink.h:1045
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/ipv4/tcp.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff819ca2e8)
Location: include/net/netlink.h:1045
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/ip_tunnel_core.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff819d3be0)
Location: include/net/netlink.h:1045
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_notify
```
```
In net/ipv4/fib_rules.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff819d9a9c)
Location: include/net/netlink.h:1045
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81a43032)
Location: include/net/netlink.h:1045
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/fib6_rules.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a4c4e5)
Location: include/net/netlink.h:1045
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_encap_nlsize
```
```
In net/ipv6/seg6_local.c (ffffffff81a4d43b)
Location: include/net/netlink.h:1045
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_get_encap_size
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
In kernel/taskstats.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In fs/quota/netlink.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In lib/nlattr.c (ffffffff81555a10)
Location: include/net/netlink.h:1045
Inline: True
Inline callers:
  - lib/nlattr.c:nla_put_64bit
  - lib/nlattr.c:nla_put
  - lib/nlattr.c:nla_reserve_64bit
  - lib/nlattr.c:__nla_reserve
  - lib/nlattr.c:nla_policy_len
```
```
In drivers/acpi/event.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/core/rtnetlink.c (ffffffff8194dd0f)
Location: include/net/netlink.h:1045
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:if_nlmsg_size
  - net/core/rtnetlink.c:if_nlmsg_size
  - net/core/rtnetlink.c:if_nlmsg_size
```
```
In net/core/sock_diag.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff81975cbe)
Location: include/net/netlink.h:1045
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/lwtunnel.c (ffffffff8197756a)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/core/lwt_bpf.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/sched/act_api.c (ffffffff819998bd)
Location: include/net/netlink.h:1045
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_fill_size
```
```
In net/netlink/af_netlink.c (ffffffff819a146d)
Location: include/net/netlink.h:1045
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/ipv4/tcp.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff81a00eb8)
Location: include/net/netlink.h:1045
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/ip_tunnel_core.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81a0a750)
Location: include/net/netlink.h:1045
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_notify
```
```
In net/ipv4/fib_rules.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81a108f4)
Location: include/net/netlink.h:1045
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81a79b92)
Location: include/net/netlink.h:1045
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/fib6_rules.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a830b5)
Location: include/net/netlink.h:1045
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_encap_nlsize
```
```
In net/ipv6/seg6_local.c (ffffffff81a8400b)
Location: include/net/netlink.h:1045
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_get_encap_size
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
In kernel/taskstats.c (0)
Location: include/net/netlink.h:1097
Inline: True
```
```
In fs/quota/netlink.c (0)
Location: include/net/netlink.h:1097
Inline: True
```
```
In lib/nlattr.c (ffffffff815de7a0)
Location: include/net/netlink.h:1097
Inline: True
Inline callers:
  - lib/nlattr.c:nla_put_64bit
  - lib/nlattr.c:nla_put
  - lib/nlattr.c:nla_reserve_64bit
  - lib/nlattr.c:nla_reserve
  - lib/nlattr.c:__nla_reserve
  - lib/nlattr.c:nla_policy_len
```
```
In drivers/acpi/event.c (0)
Location: include/net/netlink.h:1097
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/net/netlink.h:1097
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:1097
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/net/netlink.h:1097
Inline: True
```
```
In net/core/rtnetlink.c (ffffffff81a1919f)
Location: include/net/netlink.h:1097
Inline: True
Inline callers:
  - net/core/rtnetlink.c:if_nlmsg_stats_size
  - net/core/rtnetlink.c:if_nlmsg_stats_size
  - net/core/rtnetlink.c:if_nlmsg_stats_size
  - net/core/rtnetlink.c:if_nlmsg_size
  - net/core/rtnetlink.c:rtnl_link_get_size
  - net/core/rtnetlink.c:rtnl_link_get_size
```
```
In net/core/sock_diag.c (0)
Location: include/net/netlink.h:1097
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:1097
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff81a4aa4a)
Location: include/net/netlink.h:1097
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_hw_packet_report_size
  - net/core/drop_monitor.c:net_dm_hw_packet_report_size
  - net/core/drop_monitor.c:net_dm_hw_packet_report_size
  - net/core/drop_monitor.c:net_dm_hw_packet_report_size
  - net/core/drop_monitor.c:net_dm_packet_report
  - net/core/drop_monitor.c:net_dm_packet_report_fill
```
```
In net/core/lwtunnel.c (ffffffff81a4c35a)
Location: include/net/netlink.h:1097
Inline: True
```
```
In net/core/lwt_bpf.c (0)
Location: include/net/netlink.h:1097
Inline: True
```
```
In net/core/bpf_sk_storage.c (0)
Location: include/net/netlink.h:1097
Inline: True
```
```
In net/sched/act_api.c (ffffffff81a7222d)
Location: include/net/netlink.h:1097
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_fill_size
```
```
In net/netlink/af_netlink.c (ffffffff81a7ae17)
Location: include/net/netlink.h:1097
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/ethtool/netlink.c (0)
Location: include/net/netlink.h:1097
Inline: True
```
```
In net/ethtool/bitset.c (ffffffff81a872e5)
Location: include/net/netlink.h:1097
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_bitset32_size
  - net/ethtool/bitset.c:ethnl_bitset32_size
  - net/ethtool/bitset.c:ethnl_bitset32_size
  - net/ethtool/bitset.c:ethnl_bitset32_size
  - net/ethtool/bitset.c:ethnl_bitset32_size
```
```
In net/ethtool/strset.c (ffffffff81a87dde)
Location: include/net/netlink.h:1097
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_reply_size
  - net/ethtool/strset.c:strset_reply_size
  - net/ethtool/strset.c:strset_reply_size
  - net/ethtool/strset.c:strset_reply_size
```
```
In net/ethtool/linkinfo.c (0)
Location: include/net/netlink.h:1097
Inline: True
```
```
In net/ethtool/linkmodes.c (0)
Location: include/net/netlink.h:1097
Inline: True
```
```
In net/ethtool/linkstate.c (0)
Location: include/net/netlink.h:1097
Inline: True
```
```
In net/ethtool/wol.c (0)
Location: include/net/netlink.h:1097
Inline: True
```
```
In net/ethtool/features.c (0)
Location: include/net/netlink.h:1097
Inline: True
```
```
In net/ethtool/rings.c (0)
Location: include/net/netlink.h:1097
Inline: True
```
```
In net/ethtool/channels.c (0)
Location: include/net/netlink.h:1097
Inline: True
```
```
In net/ethtool/coalesce.c (0)
Location: include/net/netlink.h:1097
Inline: True
```
```
In net/ethtool/pause.c (0)
Location: include/net/netlink.h:1097
Inline: True
```
```
In net/ethtool/eee.c (0)
Location: include/net/netlink.h:1097
Inline: True
```
```
In net/ethtool/tsinfo.c (0)
Location: include/net/netlink.h:1097
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/net/netlink.h:1097
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netlink.h:1097
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/net/netlink.h:1097
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff81aeff66)
Location: include/net/netlink.h:1097
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af8938)
Location: include/net/netlink.h:1097
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81afba03)
Location: include/net/netlink.h:1097
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_notify
```
```
In net/ipv4/fib_rules.c (0)
Location: include/net/netlink.h:1097
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81b01f94)
Location: include/net/netlink.h:1097
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/netlink.h:1097
Inline: True
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:1097
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/net/netlink.h:1097
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/net/netlink.h:1097
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81b744b4)
Location: include/net/netlink.h:1097
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
```
```
In net/ipv6/fib6_rules.c (0)
Location: include/net/netlink.h:1097
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b7ded5)
Location: include/net/netlink.h:1097
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_encap_nlsize
```
```
In net/ipv6/seg6_local.c (ffffffff81b7ee8b)
Location: include/net/netlink.h:1097
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_get_encap_size
```
```
In net/mptcp/diag.c (0)
Location: include/net/netlink.h:1097
Inline: True
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
In kernel/taskstats.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In fs/quota/netlink.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In lib/nlattr.c (ffffffff815fbe40)
Location: include/net/netlink.h:1110
Inline: True
Inline callers:
  - lib/nlattr.c:nla_put_64bit
  - lib/nlattr.c:nla_put
  - lib/nlattr.c:nla_reserve_64bit
  - lib/nlattr.c:nla_reserve
  - lib/nlattr.c:__nla_reserve
  - lib/nlattr.c:nla_policy_len
```
```
In drivers/acpi/event.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/core/rtnetlink.c (ffffffff81a1938f)
Location: include/net/netlink.h:1110
Inline: True
Inline callers:
  - net/core/rtnetlink.c:if_nlmsg_stats_size
  - net/core/rtnetlink.c:if_nlmsg_stats_size
  - net/core/rtnetlink.c:if_nlmsg_stats_size
  - net/core/rtnetlink.c:if_nlmsg_size
  - net/core/rtnetlink.c:rtnl_link_get_size
  - net/core/rtnetlink.c:rtnl_link_get_size
```
```
In net/core/sock_diag.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff81a5068a)
Location: include/net/netlink.h:1110
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_hw_packet_report_size
  - net/core/drop_monitor.c:net_dm_hw_packet_report_size
  - net/core/drop_monitor.c:net_dm_hw_packet_report_size
  - net/core/drop_monitor.c:net_dm_hw_packet_report_size
  - net/core/drop_monitor.c:net_dm_packet_report
  - net/core/drop_monitor.c:net_dm_packet_report_fill
```
```
In net/core/lwtunnel.c (ffffffff81a51fbd)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/core/lwt_bpf.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/core/bpf_sk_storage.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/sched/act_api.c (ffffffff81a7af62)
Location: include/net/netlink.h:1110
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_fill_size
```
```
In net/netlink/af_netlink.c (ffffffff81a83df5)
Location: include/net/netlink.h:1110
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/ethtool/netlink.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/ethtool/bitset.c (ffffffff81a90c75)
Location: include/net/netlink.h:1110
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_bitset32_size
  - net/ethtool/bitset.c:ethnl_bitset32_size
  - net/ethtool/bitset.c:ethnl_bitset32_size
  - net/ethtool/bitset.c:ethnl_bitset32_size
  - net/ethtool/bitset.c:ethnl_bitset32_size
```
```
In net/ethtool/strset.c (ffffffff81a9178e)
Location: include/net/netlink.h:1110
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_reply_size
  - net/ethtool/strset.c:strset_reply_size
  - net/ethtool/strset.c:strset_reply_size
  - net/ethtool/strset.c:strset_reply_size
```
```
In net/ethtool/linkinfo.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/ethtool/linkmodes.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/ethtool/linkstate.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/ethtool/wol.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/ethtool/features.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/ethtool/rings.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/ethtool/channels.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/ethtool/coalesce.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/ethtool/pause.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/ethtool/eee.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/ethtool/tsinfo.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/ethtool/tunnels.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff81afcea6)
Location: include/net/netlink.h:1110
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81b05708)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81b090d3)
Location: include/net/netlink.h:1110
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_notify
```
```
In net/ipv4/fib_rules.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81b10303)
Location: include/net/netlink.h:1110
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81b83224)
Location: include/net/netlink.h:1110
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
```
```
In net/ipv6/fib6_rules.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b8cee5)
Location: include/net/netlink.h:1110
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_encap_nlsize
```
```
In net/ipv6/seg6_local.c (ffffffff81b8de05)
Location: include/net/netlink.h:1110
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_get_encap_size
```
```
In net/mptcp/diag.c (0)
Location: include/net/netlink.h:1110
Inline: True
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
In kernel/taskstats.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In fs/quota/netlink.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In lib/nlattr.c (ffffffff815dea80)
Location: include/net/netlink.h:1110
Inline: True
Inline callers:
  - lib/nlattr.c:nla_put_64bit
  - lib/nlattr.c:nla_put
  - lib/nlattr.c:nla_reserve_64bit
  - lib/nlattr.c:nla_reserve
  - lib/nlattr.c:__nla_reserve
  - lib/nlattr.c:nla_policy_len
```
```
In drivers/acpi/event.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/core/rtnetlink.c (ffffffff81a0029f)
Location: include/net/netlink.h:1110
Inline: True
Inline callers:
  - net/core/rtnetlink.c:if_nlmsg_stats_size
  - net/core/rtnetlink.c:if_nlmsg_stats_size
  - net/core/rtnetlink.c:if_nlmsg_stats_size
  - net/core/rtnetlink.c:if_nlmsg_size
  - net/core/rtnetlink.c:rtnl_link_get_size
  - net/core/rtnetlink.c:rtnl_link_get_size
```
```
In net/core/sock_diag.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff81a355b5)
Location: include/net/netlink.h:1110
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_hw_packet_report_size
  - net/core/drop_monitor.c:net_dm_hw_packet_report_size
  - net/core/drop_monitor.c:net_dm_hw_packet_report_size
  - net/core/drop_monitor.c:net_dm_hw_packet_report_size
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_report_fill
```
```
In net/core/lwtunnel.c (ffffffff81a378bd)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/core/lwt_bpf.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/core/bpf_sk_storage.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/sched/act_api.c (ffffffff81a63cc2)
Location: include/net/netlink.h:1110
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_fill_size
```
```
In net/netlink/af_netlink.c (ffffffff81a6cd88)
Location: include/net/netlink.h:1110
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/ethtool/netlink.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/ethtool/bitset.c (ffffffff81a7a473)
Location: include/net/netlink.h:1110
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_bitset32_size
  - net/ethtool/bitset.c:ethnl_bitset32_size
  - net/ethtool/bitset.c:ethnl_bitset32_size
  - net/ethtool/bitset.c:ethnl_bitset32_size
  - net/ethtool/bitset.c:ethnl_bitset32_size
```
```
In net/ethtool/strset.c (ffffffff81a7b130)
Location: include/net/netlink.h:1110
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_reply_size
  - net/ethtool/strset.c:strset_reply_size
  - net/ethtool/strset.c:strset_reply_size
  - net/ethtool/strset.c:strset_reply_size
```
```
In net/ethtool/linkinfo.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/ethtool/linkmodes.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/ethtool/linkstate.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/ethtool/wol.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/ethtool/features.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/ethtool/rings.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/ethtool/channels.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/ethtool/coalesce.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/ethtool/pause.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/ethtool/eee.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/ethtool/tsinfo.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/ethtool/tunnels.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/ethtool/fec.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/ethtool/eeprom.c (ffffffff81a81bd5)
Location: include/net/netlink.h:1110
Inline: True
Inline callers:
  - net/ethtool/eeprom.c:eeprom_reply_size
```
```
In net/ethtool/stats.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff81ae6939)
Location: include/net/netlink.h:1110
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nlmsg_size
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af0f88)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81af7263)
Location: include/net/netlink.h:1110
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_notify
```
```
In net/ipv4/fib_rules.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81afdf13)
Location: include/net/netlink.h:1110
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81b71ea5)
Location: include/net/netlink.h:1110
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
```
```
In net/ipv6/fib6_rules.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b7bd95)
Location: include/net/netlink.h:1110
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_encap_nlsize
```
```
In net/ipv6/seg6_local.c (ffffffff81b7cd25)
Location: include/net/netlink.h:1110
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_get_encap_size
```
```
In net/mptcp/diag.c (0)
Location: include/net/netlink.h:1110
Inline: True
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
In kernel/taskstats.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In fs/quota/netlink.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In lib/nlattr.c (ffffffff8164a600)
Location: include/net/netlink.h:1110
Inline: True
Inline callers:
  - lib/nlattr.c:nla_put_64bit
  - lib/nlattr.c:nla_put
  - lib/nlattr.c:nla_reserve_64bit
  - lib/nlattr.c:nla_reserve
  - lib/nlattr.c:__nla_reserve
  - lib/nlattr.c:nla_policy_len
  - lib/nlattr.c:nla_policy_len
  - lib/nlattr.c:nla_policy_len
```
```
In drivers/acpi/event.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In drivers/net/wwan/wwan_core.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/core/rtnetlink.c (ffffffff81ab23f3)
Location: include/net/netlink.h:1110
Inline: True
Inline callers:
  - net/core/rtnetlink.c:if_nlmsg_stats_size
  - net/core/rtnetlink.c:if_nlmsg_stats_size
  - net/core/rtnetlink.c:if_nlmsg_stats_size
  - net/core/rtnetlink.c:if_nlmsg_size
  - net/core/rtnetlink.c:rtnl_link_get_size
  - net/core/rtnetlink.c:rtnl_link_get_size
```
```
In net/core/sock_diag.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff81aeb185)
Location: include/net/netlink.h:1110
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_hw_packet_report_size
  - net/core/drop_monitor.c:net_dm_hw_packet_report_size
  - net/core/drop_monitor.c:net_dm_hw_packet_report_size
  - net/core/drop_monitor.c:net_dm_hw_packet_report_size
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_report_fill
```
```
In net/core/lwtunnel.c (ffffffff81aed67c)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/core/lwt_bpf.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/core/bpf_sk_storage.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/sched/act_api.c (ffffffff81b1d042)
Location: include/net/netlink.h:1110
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_fill_size
```
```
In net/netlink/af_netlink.c (ffffffff81b26408)
Location: include/net/netlink.h:1110
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/ethtool/netlink.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/ethtool/bitset.c (ffffffff81b34883)
Location: include/net/netlink.h:1110
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_bitset32_size
  - net/ethtool/bitset.c:ethnl_bitset32_size
  - net/ethtool/bitset.c:ethnl_bitset32_size
  - net/ethtool/bitset.c:ethnl_bitset32_size
  - net/ethtool/bitset.c:ethnl_bitset32_size
```
```
In net/ethtool/strset.c (ffffffff81b3525a)
Location: include/net/netlink.h:1110
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_reply_size
  - net/ethtool/strset.c:strset_reply_size
  - net/ethtool/strset.c:strset_reply_size
  - net/ethtool/strset.c:strset_reply_size
```
```
In net/ethtool/linkinfo.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/ethtool/linkmodes.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/ethtool/linkstate.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/ethtool/wol.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/ethtool/features.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/ethtool/rings.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/ethtool/channels.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/ethtool/coalesce.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/ethtool/pause.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/ethtool/eee.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/ethtool/tsinfo.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/ethtool/tunnels.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/ethtool/fec.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/ethtool/eeprom.c (ffffffff81b3b855)
Location: include/net/netlink.h:1110
Inline: True
Inline callers:
  - net/ethtool/eeprom.c:eeprom_reply_size
```
```
In net/ethtool/stats.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/ethtool/phc_vclocks.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff81ba6540)
Location: include/net/netlink.h:1110
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nlmsg_size
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81bb1698)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81bb6c12)
Location: include/net/netlink.h:1110
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_notify
```
```
In net/ipv4/fib_rules.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81bbf1a3)
Location: include/net/netlink.h:1110
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81c3c355)
Location: include/net/netlink.h:1110
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
```
```
In net/ipv6/fib6_rules.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81c46a95)
Location: include/net/netlink.h:1110
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_encap_nlsize
```
```
In net/ipv6/seg6_local.c (ffffffff81c47fb5)
Location: include/net/netlink.h:1110
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_get_encap_size
```
```
In net/ipv6/ioam6_iptunnel.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/mptcp/diag.c (0)
Location: include/net/netlink.h:1110
Inline: True
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
In kernel/taskstats.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In fs/quota/netlink.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In lib/nlattr.c (ffffffff81761080)
Location: include/net/netlink.h:1110
Inline: True
Inline callers:
  - lib/nlattr.c:nla_put_64bit
  - lib/nlattr.c:nla_put
  - lib/nlattr.c:nla_reserve_64bit
  - lib/nlattr.c:nla_reserve
  - lib/nlattr.c:__nla_reserve
  - lib/nlattr.c:nla_policy_len
  - lib/nlattr.c:nla_policy_len
  - lib/nlattr.c:nla_policy_len
```
```
In drivers/acpi/event.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In drivers/net/wwan/wwan_core.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/core/rtnetlink.c (ffffffff81c2cd15)
Location: include/net/netlink.h:1110
Inline: True
Inline callers:
  - net/core/rtnetlink.c:if_nlmsg_size
  - net/core/rtnetlink.c:rtnl_link_get_size
  - net/core/rtnetlink.c:rtnl_link_get_size
```
```
In net/core/sock_diag.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff81c6d9e8)
Location: include/net/netlink.h:1110
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_hw_packet_report_size
  - net/core/drop_monitor.c:net_dm_hw_packet_report_size
  - net/core/drop_monitor.c:net_dm_hw_packet_report_size
  - net/core/drop_monitor.c:net_dm_hw_packet_report_size
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_report_fill
```
```
In net/core/lwtunnel.c (ffffffff81c70540)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/core/lwt_bpf.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/core/bpf_sk_storage.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/sched/act_api.c (ffffffff81ca4556)
Location: include/net/netlink.h:1110
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_fill_size
```
```
In net/netlink/af_netlink.c (ffffffff81caf1cd)
Location: include/net/netlink.h:1110
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/ethtool/netlink.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/ethtool/bitset.c (ffffffff81cbfe1a)
Location: include/net/netlink.h:1110
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_bitset32_size
  - net/ethtool/bitset.c:ethnl_bitset32_size
  - net/ethtool/bitset.c:ethnl_bitset32_size
  - net/ethtool/bitset.c:ethnl_bitset32_size
  - net/ethtool/bitset.c:ethnl_bitset32_size
```
```
In net/ethtool/strset.c (ffffffff81cc0aba)
Location: include/net/netlink.h:1110
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_reply_size
  - net/ethtool/strset.c:strset_reply_size
  - net/ethtool/strset.c:strset_reply_size
  - net/ethtool/strset.c:strset_reply_size
```
```
In net/ethtool/linkinfo.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/ethtool/linkmodes.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/ethtool/linkstate.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/ethtool/wol.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/ethtool/features.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/ethtool/rings.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/ethtool/channels.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/ethtool/coalesce.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/ethtool/pause.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/ethtool/eee.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/ethtool/tsinfo.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/ethtool/tunnels.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/ethtool/fec.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/ethtool/eeprom.c (ffffffff81cc7865)
Location: include/net/netlink.h:1110
Inline: True
Inline callers:
  - net/ethtool/eeprom.c:eeprom_reply_size
```
```
In net/ethtool/stats.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/ethtool/phc_vclocks.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/ethtool/module.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff81d38f1a)
Location: include/net/netlink.h:1110
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nlmsg_size
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81d44d77)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81d4a874)
Location: include/net/netlink.h:1110
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_notify
```
```
In net/ipv4/fib_rules.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81d53f12)
Location: include/net/netlink.h:1110
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81dda70f)
Location: include/net/netlink.h:1110
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
```
```
In net/ipv6/fib6_rules.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81de5d55)
Location: include/net/netlink.h:1110
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_encap_nlsize
```
```
In net/ipv6/seg6_local.c (ffffffff81de7495)
Location: include/net/netlink.h:1110
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_get_encap_size
```
```
In net/ipv6/ioam6_iptunnel.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/mptcp/diag.c (0)
Location: include/net/netlink.h:1110
Inline: True
```
```
In net/mctp/device.c (0)
Location: include/net/netlink.h:1110
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
In kernel/taskstats.c (0)
Location: include/net/netlink.h:1159
Inline: True
```
```
In fs/quota/netlink.c (0)
Location: include/net/netlink.h:1159
Inline: True
```
```
In lib/nlattr.c (ffffffff8188f860)
Location: include/net/netlink.h:1159
Inline: True
Inline callers:
  - lib/nlattr.c:nla_put_64bit
  - lib/nlattr.c:nla_put
  - lib/nlattr.c:nla_reserve_64bit
  - lib/nlattr.c:nla_reserve
  - lib/nlattr.c:__nla_reserve
  - lib/nlattr.c:nla_policy_len
  - lib/nlattr.c:nla_policy_len
  - lib/nlattr.c:nla_policy_len
```
```
In drivers/acpi/event.c (0)
Location: include/net/netlink.h:1159
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/net/netlink.h:1159
Inline: True
```
```
In drivers/net/wwan/wwan_core.c (0)
Location: include/net/netlink.h:1159
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:1159
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/net/netlink.h:1159
Inline: True
```
```
In net/core/rtnetlink.c (ffffffff81ddfe55)
Location: include/net/netlink.h:1159
Inline: True
Inline callers:
  - net/core/rtnetlink.c:if_nlmsg_size
  - net/core/rtnetlink.c:rtnl_link_get_size
  - net/core/rtnetlink.c:rtnl_link_get_size
```
```
In net/core/sock_diag.c (0)
Location: include/net/netlink.h:1159
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:1159
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff81e25648)
Location: include/net/netlink.h:1159
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_hw_packet_report_size
  - net/core/drop_monitor.c:net_dm_hw_packet_report_size
  - net/core/drop_monitor.c:net_dm_hw_packet_report_size
  - net/core/drop_monitor.c:net_dm_hw_packet_report_size
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_report_fill
```
```
In net/core/lwtunnel.c (ffffffff81e284f0)
Location: include/net/netlink.h:1159
Inline: True
```
```
In net/core/lwt_bpf.c (0)
Location: include/net/netlink.h:1159
Inline: True
```
```
In net/core/devlink.c (ffffffff81e44714)
Location: include/net/netlink.h:1159
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_port_handle_size
  - net/core/devlink.c:devlink_nl_port_handle_size
```
```
In net/core/bpf_sk_storage.c (0)
Location: include/net/netlink.h:1159
Inline: True
```
```
In net/sched/act_api.c (ffffffff81e60f26)
Location: include/net/netlink.h:1159
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_fill_size
```
```
In net/netlink/af_netlink.c (ffffffff81e6c6b1)
Location: include/net/netlink.h:1159
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/ethtool/netlink.c (0)
Location: include/net/netlink.h:1159
Inline: True
```
```
In net/ethtool/bitset.c (ffffffff81e7ea0a)
Location: include/net/netlink.h:1159
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_bitset32_size
  - net/ethtool/bitset.c:ethnl_bitset32_size
  - net/ethtool/bitset.c:ethnl_bitset32_size
  - net/ethtool/bitset.c:ethnl_bitset32_size
  - net/ethtool/bitset.c:ethnl_bitset32_size
```
```
In net/ethtool/strset.c (ffffffff81e7f776)
Location: include/net/netlink.h:1159
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_reply_size
  - net/ethtool/strset.c:strset_reply_size
  - net/ethtool/strset.c:strset_reply_size
  - net/ethtool/strset.c:strset_reply_size
```
```
In net/ethtool/linkinfo.c (0)
Location: include/net/netlink.h:1159
Inline: True
```
```
In net/ethtool/linkmodes.c (0)
Location: include/net/netlink.h:1159
Inline: True
```
```
In net/ethtool/rss.c (ffffffff81e80f55)
Location: include/net/netlink.h:1159
Inline: True
Inline callers:
  - net/ethtool/rss.c:rss_reply_size
  - net/ethtool/rss.c:rss_reply_size
```
```
In net/ethtool/linkstate.c (0)
Location: include/net/netlink.h:1159
Inline: True
```
```
In net/ethtool/wol.c (0)
Location: include/net/netlink.h:1159
Inline: True
```
```
In net/ethtool/features.c (0)
Location: include/net/netlink.h:1159
Inline: True
```
```
In net/ethtool/rings.c (0)
Location: include/net/netlink.h:1159
Inline: True
```
```
In net/ethtool/channels.c (0)
Location: include/net/netlink.h:1159
Inline: True
```
```
In net/ethtool/coalesce.c (0)
Location: include/net/netlink.h:1159
Inline: True
```
```
In net/ethtool/pause.c (0)
Location: include/net/netlink.h:1159
Inline: True
```
```
In net/ethtool/eee.c (0)
Location: include/net/netlink.h:1159
Inline: True
```
```
In net/ethtool/tsinfo.c (0)
Location: include/net/netlink.h:1159
Inline: True
```
```
In net/ethtool/tunnels.c (0)
Location: include/net/netlink.h:1159
Inline: True
```
```
In net/ethtool/fec.c (0)
Location: include/net/netlink.h:1159
Inline: True
```
```
In net/ethtool/eeprom.c (ffffffff81e86ee5)
Location: include/net/netlink.h:1159
Inline: True
Inline callers:
  - net/ethtool/eeprom.c:eeprom_reply_size
```
```
In net/ethtool/stats.c (0)
Location: include/net/netlink.h:1159
Inline: True
```
```
In net/ethtool/phc_vclocks.c (0)
Location: include/net/netlink.h:1159
Inline: True
```
```
In net/ethtool/module.c (0)
Location: include/net/netlink.h:1159
Inline: True
```
```
In net/ethtool/pse-pd.c (0)
Location: include/net/netlink.h:1159
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/net/netlink.h:1159
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netlink.h:1159
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/net/netlink.h:1159
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff81f017ca)
Location: include/net/netlink.h:1159
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nlmsg_size
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f0e027)
Location: include/net/netlink.h:1159
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81f13f34)
Location: include/net/netlink.h:1159
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_notify
```
```
In net/ipv4/fib_rules.c (0)
Location: include/net/netlink.h:1159
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81f1e0e2)
Location: include/net/netlink.h:1159
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/netlink.h:1159
Inline: True
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:1159
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/net/netlink.h:1159
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/net/netlink.h:1159
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81fac42f)
Location: include/net/netlink.h:1159
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
```
```
In net/ipv6/fib6_rules.c (0)
Location: include/net/netlink.h:1159
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81fb85b5)
Location: include/net/netlink.h:1159
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_encap_nlsize
```
```
In net/ipv6/seg6_local.c (ffffffff81fba3c8)
Location: include/net/netlink.h:1159
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_get_encap_size
```
```
In net/ipv6/ioam6_iptunnel.c (0)
Location: include/net/netlink.h:1159
Inline: True
```
```
In net/mptcp/diag.c (0)
Location: include/net/netlink.h:1159
Inline: True
```
```
In net/mctp/device.c (0)
Location: include/net/netlink.h:1159
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
In kernel/taskstats.c (0)
Location: include/net/netlink.h:1160
Inline: True
```
```
In fs/quota/netlink.c (0)
Location: include/net/netlink.h:1160
Inline: True
```
```
In lib/nlattr.c (ffffffff818d1ca0)
Location: include/net/netlink.h:1160
Inline: True
Inline callers:
  - lib/nlattr.c:nla_put_64bit
  - lib/nlattr.c:nla_put
  - lib/nlattr.c:nla_reserve_64bit
  - lib/nlattr.c:nla_reserve
  - lib/nlattr.c:__nla_reserve
  - lib/nlattr.c:nla_policy_len
  - lib/nlattr.c:nla_policy_len
  - lib/nlattr.c:nla_policy_len
```
```
In drivers/acpi/event.c (0)
Location: include/net/netlink.h:1160
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/net/netlink.h:1160
Inline: True
```
```
In drivers/net/wwan/wwan_core.c (0)
Location: include/net/netlink.h:1160
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:1160
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/net/netlink.h:1160
Inline: True
```
```
In net/core/rtnetlink.c (ffffffff81e55bbf)
Location: include/net/netlink.h:1160
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:if_nlmsg_size
  - net/core/rtnetlink.c:rtnl_link_get_size
  - net/core/rtnetlink.c:rtnl_link_get_size
```
```
In net/core/sock_diag.c (0)
Location: include/net/netlink.h:1160
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:1160
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff81e9ab88)
Location: include/net/netlink.h:1160
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_hw_packet_report_size
  - net/core/drop_monitor.c:net_dm_hw_packet_report_size
  - net/core/drop_monitor.c:net_dm_hw_packet_report_size
  - net/core/drop_monitor.c:net_dm_hw_packet_report_size
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_report_fill
```
```
In net/core/lwtunnel.c (ffffffff81e9db10)
Location: include/net/netlink.h:1160
Inline: True
```
```
In net/core/lwt_bpf.c (0)
Location: include/net/netlink.h:1160
Inline: True
```
```
In net/core/bpf_sk_storage.c (0)
Location: include/net/netlink.h:1160
Inline: True
```
```
In net/sched/act_api.c (ffffffff81ebcf36)
Location: include/net/netlink.h:1160
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_fill_size
```
```
In net/netlink/af_netlink.c (ffffffff81ec8711)
Location: include/net/netlink.h:1160
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/ethtool/netlink.c (0)
Location: include/net/netlink.h:1160
Inline: True
```
```
In net/ethtool/bitset.c (ffffffff81edaffd)
Location: include/net/netlink.h:1160
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_bitset32_size
  - net/ethtool/bitset.c:ethnl_bitset32_size
  - net/ethtool/bitset.c:ethnl_bitset32_size
  - net/ethtool/bitset.c:ethnl_bitset32_size
  - net/ethtool/bitset.c:ethnl_bitset32_size
```
```
In net/ethtool/strset.c (ffffffff81edbe11)
Location: include/net/netlink.h:1160
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_reply_size
  - net/ethtool/strset.c:strset_reply_size
  - net/ethtool/strset.c:strset_reply_size
  - net/ethtool/strset.c:strset_reply_size
```
```
In net/ethtool/linkinfo.c (0)
Location: include/net/netlink.h:1160
Inline: True
```
```
In net/ethtool/linkmodes.c (0)
Location: include/net/netlink.h:1160
Inline: True
```
```
In net/ethtool/rss.c (ffffffff81edd665)
Location: include/net/netlink.h:1160
Inline: True
Inline callers:
  - net/ethtool/rss.c:rss_reply_size
  - net/ethtool/rss.c:rss_reply_size
```
```
In net/ethtool/linkstate.c (0)
Location: include/net/netlink.h:1160
Inline: True
```
```
In net/ethtool/wol.c (0)
Location: include/net/netlink.h:1160
Inline: True
```
```
In net/ethtool/features.c (0)
Location: include/net/netlink.h:1160
Inline: True
```
```
In net/ethtool/rings.c (0)
Location: include/net/netlink.h:1160
Inline: True
```
```
In net/ethtool/channels.c (0)
Location: include/net/netlink.h:1160
Inline: True
```
```
In net/ethtool/coalesce.c (0)
Location: include/net/netlink.h:1160
Inline: True
```
```
In net/ethtool/pause.c (0)
Location: include/net/netlink.h:1160
Inline: True
```
```
In net/ethtool/eee.c (0)
Location: include/net/netlink.h:1160
Inline: True
```
```
In net/ethtool/tsinfo.c (0)
Location: include/net/netlink.h:1160
Inline: True
```
```
In net/ethtool/tunnels.c (0)
Location: include/net/netlink.h:1160
Inline: True
```
```
In net/ethtool/fec.c (0)
Location: include/net/netlink.h:1160
Inline: True
```
```
In net/ethtool/eeprom.c (ffffffff81ee3945)
Location: include/net/netlink.h:1160
Inline: True
Inline callers:
  - net/ethtool/eeprom.c:eeprom_reply_size
```
```
In net/ethtool/stats.c (0)
Location: include/net/netlink.h:1160
Inline: True
```
```
In net/ethtool/phc_vclocks.c (0)
Location: include/net/netlink.h:1160
Inline: True
```
```
In net/ethtool/mm.c (0)
Location: include/net/netlink.h:1160
Inline: True
```
```
In net/ethtool/module.c (0)
Location: include/net/netlink.h:1160
Inline: True
```
```
In net/ethtool/pse-pd.c (0)
Location: include/net/netlink.h:1160
Inline: True
```
```
In net/ethtool/plca.c (0)
Location: include/net/netlink.h:1160
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/net/netlink.h:1160
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netlink.h:1160
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/net/netlink.h:1160
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff81f6123a)
Location: include/net/netlink.h:1160
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nlmsg_size
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f6dcd7)
Location: include/net/netlink.h:1160
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81f73c04)
Location: include/net/netlink.h:1160
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_notify
```
```
In net/ipv4/fib_rules.c (0)
Location: include/net/netlink.h:1160
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81f7dbd2)
Location: include/net/netlink.h:1160
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/netlink.h:1160
Inline: True
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:1160
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/net/netlink.h:1160
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/net/netlink.h:1160
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff8200cbcf)
Location: include/net/netlink.h:1160
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
```
```
In net/ipv6/fib6_rules.c (0)
Location: include/net/netlink.h:1160
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff82018d25)
Location: include/net/netlink.h:1160
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_encap_nlsize
```
```
In net/ipv6/seg6_local.c (ffffffff8201aaf8)
Location: include/net/netlink.h:1160
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_get_encap_size
```
```
In net/ipv6/ioam6_iptunnel.c (0)
Location: include/net/netlink.h:1160
Inline: True
```
```
In net/devlink/leftover.c (ffffffff82041384)
Location: include/net/netlink.h:1160
Inline: True
Inline callers:
  - net/devlink/leftover.c:devlink_nl_port_handle_size
  - net/devlink/leftover.c:devlink_nl_port_handle_size
```
```
In net/mptcp/diag.c (0)
Location: include/net/netlink.h:1160
Inline: True
```
```
In net/mctp/device.c (0)
Location: include/net/netlink.h:1160
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
In kernel/taskstats.c (0)
Location: include/net/netlink.h:1204
Inline: True
```
```
In fs/quota/netlink.c (0)
Location: include/net/netlink.h:1204
Inline: True
```
```
In lib/nlattr.c (ffffffff81923ca0)
Location: include/net/netlink.h:1204
Inline: True
Inline callers:
  - lib/nlattr.c:nla_put_64bit
  - lib/nlattr.c:nla_put
  - lib/nlattr.c:nla_reserve_64bit
  - lib/nlattr.c:nla_reserve
  - lib/nlattr.c:__nla_reserve
  - lib/nlattr.c:nla_policy_len
  - lib/nlattr.c:nla_policy_len
  - lib/nlattr.c:nla_policy_len
```
```
In drivers/acpi/event.c (0)
Location: include/net/netlink.h:1204
Inline: True
```
```
In drivers/regulator/event.c (0)
Location: include/net/netlink.h:1204
Inline: True
```
```
In drivers/net/netkit.c (0)
Location: include/net/netlink.h:1204
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/net/netlink.h:1204
Inline: True
```
```
In drivers/dpll/dpll_netlink.c (0)
Location: include/net/netlink.h:1204
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:1204
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/net/netlink.h:1204
Inline: True
```
```
In net/core/rtnetlink.c (ffffffff81f14f5f)
Location: include/net/netlink.h:1204
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:if_nlmsg_size
  - net/core/rtnetlink.c:rtnl_link_get_size
  - net/core/rtnetlink.c:rtnl_link_get_size
```
```
In net/core/sock_diag.c (0)
Location: include/net/netlink.h:1204
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:1204
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff81f5d2cf)
Location: include/net/netlink.h:1204
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_hw_packet_report_size
  - net/core/drop_monitor.c:net_dm_hw_packet_report_size
  - net/core/drop_monitor.c:net_dm_hw_packet_report_size
  - net/core/drop_monitor.c:net_dm_hw_packet_report_size
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/core/drop_monitor.c:net_dm_packet_report_fill
```
```
In net/core/lwtunnel.c (ffffffff81f60290)
Location: include/net/netlink.h:1204
Inline: True
```
```
In net/core/lwt_bpf.c (0)
Location: include/net/netlink.h:1204
Inline: True
```
```
In net/core/bpf_sk_storage.c (0)
Location: include/net/netlink.h:1204
Inline: True
```
```
In net/sched/act_api.c (ffffffff81f80136)
Location: include/net/netlink.h:1204
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_fill_size
```
```
In net/netlink/af_netlink.c (ffffffff81f86777)
Location: include/net/netlink.h:1204
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack_tlv_len
  - net/netlink/af_netlink.c:netlink_ack_tlv_len
```
```
In net/ethtool/netlink.c (0)
Location: include/net/netlink.h:1204
Inline: True
```
```
In net/ethtool/bitset.c (ffffffff81f9edbd)
Location: include/net/netlink.h:1204
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_bitset32_size
  - net/ethtool/bitset.c:ethnl_bitset32_size
  - net/ethtool/bitset.c:ethnl_bitset32_size
  - net/ethtool/bitset.c:ethnl_bitset32_size
  - net/ethtool/bitset.c:ethnl_bitset32_size
```
```
In net/ethtool/strset.c (ffffffff81f9fbd1)
Location: include/net/netlink.h:1204
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_reply_size
  - net/ethtool/strset.c:strset_reply_size
  - net/ethtool/strset.c:strset_reply_size
  - net/ethtool/strset.c:strset_reply_size
```
```
In net/ethtool/linkinfo.c (0)
Location: include/net/netlink.h:1204
Inline: True
```
```
In net/ethtool/linkmodes.c (0)
Location: include/net/netlink.h:1204
Inline: True
```
```
In net/ethtool/rss.c (ffffffff81fa1435)
Location: include/net/netlink.h:1204
Inline: True
Inline callers:
  - net/ethtool/rss.c:rss_reply_size
  - net/ethtool/rss.c:rss_reply_size
```
```
In net/ethtool/linkstate.c (0)
Location: include/net/netlink.h:1204
Inline: True
```
```
In net/ethtool/wol.c (0)
Location: include/net/netlink.h:1204
Inline: True
```
```
In net/ethtool/features.c (0)
Location: include/net/netlink.h:1204
Inline: True
```
```
In net/ethtool/rings.c (0)
Location: include/net/netlink.h:1204
Inline: True
```
```
In net/ethtool/channels.c (0)
Location: include/net/netlink.h:1204
Inline: True
```
```
In net/ethtool/coalesce.c (0)
Location: include/net/netlink.h:1204
Inline: True
```
```
In net/ethtool/pause.c (0)
Location: include/net/netlink.h:1204
Inline: True
```
```
In net/ethtool/eee.c (0)
Location: include/net/netlink.h:1204
Inline: True
```
```
In net/ethtool/tsinfo.c (0)
Location: include/net/netlink.h:1204
Inline: True
```
```
In net/ethtool/tunnels.c (0)
Location: include/net/netlink.h:1204
Inline: True
```
```
In net/ethtool/fec.c (0)
Location: include/net/netlink.h:1204
Inline: True
```
```
In net/ethtool/eeprom.c (ffffffff81fa7725)
Location: include/net/netlink.h:1204
Inline: True
Inline callers:
  - net/ethtool/eeprom.c:eeprom_reply_size
```
```
In net/ethtool/stats.c (0)
Location: include/net/netlink.h:1204
Inline: True
```
```
In net/ethtool/phc_vclocks.c (0)
Location: include/net/netlink.h:1204
Inline: True
```
```
In net/ethtool/mm.c (0)
Location: include/net/netlink.h:1204
Inline: True
```
```
In net/ethtool/module.c (0)
Location: include/net/netlink.h:1204
Inline: True
```
```
In net/ethtool/pse-pd.c (0)
Location: include/net/netlink.h:1204
Inline: True
```
```
In net/ethtool/plca.c (0)
Location: include/net/netlink.h:1204
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/net/netlink.h:1204
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netlink.h:1204
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/net/netlink.h:1204
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff8202780a)
Location: include/net/netlink.h:1204
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nlmsg_size
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff820343f7)
Location: include/net/netlink.h:1204
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff8203a3f4)
Location: include/net/netlink.h:1204
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_notify
```
```
In net/ipv4/fib_rules.c (0)
Location: include/net/netlink.h:1204
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff82044412)
Location: include/net/netlink.h:1204
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/netlink.h:1204
Inline: True
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:1204
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/net/netlink.h:1204
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/net/netlink.h:1204
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff820dbb9f)
Location: include/net/netlink.h:1204
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
```
```
In net/ipv6/fib6_rules.c (0)
Location: include/net/netlink.h:1204
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff820e7cf5)
Location: include/net/netlink.h:1204
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_encap_nlsize
```
```
In net/ipv6/seg6_local.c (ffffffff820e9ab8)
Location: include/net/netlink.h:1204
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_get_encap_size
```
```
In net/ipv6/ioam6_iptunnel.c (0)
Location: include/net/netlink.h:1204
Inline: True
```
```
In net/devlink/port.c (ffffffff82107b44)
Location: include/net/netlink.h:1204
Inline: True
Inline callers:
  - net/devlink/port.c:devlink_nl_port_handle_size
  - net/devlink/port.c:devlink_nl_port_handle_size
```
```
In net/mptcp/diag.c (0)
Location: include/net/netlink.h:1204
Inline: True
```
```
In net/mctp/device.c (0)
Location: include/net/netlink.h:1204
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
In kernel/taskstats.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In fs/quota/netlink.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In lib/nlattr.c (ffff800010661ec8)
Location: include/net/netlink.h:1045
Inline: True
Inline callers:
  - lib/nlattr.c:nla_put_64bit
  - lib/nlattr.c:nla_put
  - lib/nlattr.c:nla_reserve_64bit
  - lib/nlattr.c:__nla_reserve
  - lib/nlattr.c:nla_policy_len
  - lib/nlattr.c:nla_policy_len
```
```
In drivers/acpi/event.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/core/rtnetlink.c (ffff800010befc74)
Location: include/net/netlink.h:1045
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:if_nlmsg_size
  - net/core/rtnetlink.c:if_nlmsg_size
  - net/core/rtnetlink.c:if_nlmsg_size
```
```
In net/core/sock_diag.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/core/drop_monitor.c (ffff800010c1c15c)
Location: include/net/netlink.h:1045
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/lwtunnel.c (ffff800010c1e030)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/core/lwt_bpf.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/sched/act_api.c (ffff800010c4668c)
Location: include/net/netlink.h:1045
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_fill_size
```
```
In net/netlink/af_netlink.c (ffff800010c4faf0)
Location: include/net/netlink.h:1045
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/ipv4/tcp.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffff800010cb94b8)
Location: include/net/netlink.h:1045
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/ip_tunnel_core.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/ipv4/nexthop.c (ffff800010cc3cec)
Location: include/net/netlink.h:1045
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_notify
```
```
In net/ipv4/fib_rules.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/ipv4/ipmr.c (ffff800010ccb540)
Location: include/net/netlink.h:1045
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/ipv6/ip6mr.c (ffff800010d43ea8)
Location: include/net/netlink.h:1045
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/fib6_rules.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (ffff800010d4ee90)
Location: include/net/netlink.h:1045
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_encap_nlsize
```
```
In net/ipv6/seg6_local.c (ffff800010d4fe08)
Location: include/net/netlink.h:1045
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_get_encap_size
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
In kernel/taskstats.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In fs/quota/netlink.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In lib/nlattr.c (c080af58)
Location: include/net/netlink.h:1045
Inline: True
Inline callers:
  - lib/nlattr.c:nla_put_64bit
  - lib/nlattr.c:nla_put
  - lib/nlattr.c:nla_reserve_64bit
  - lib/nlattr.c:__nla_reserve
  - lib/nlattr.c:nla_policy_len
  - lib/nlattr.c:nla_policy_len
  - lib/nlattr.c:nla_policy_len
```
```
In drivers/net/tun.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/core/rtnetlink.c (c0d0828c)
Location: include/net/netlink.h:1045
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:if_nlmsg_size
  - net/core/rtnetlink.c:if_nlmsg_size
  - net/core/rtnetlink.c:if_nlmsg_size
```
```
In net/core/sock_diag.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/core/drop_monitor.c (c0d33f94)
Location: include/net/netlink.h:1045
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/lwtunnel.c (c0d35bbc)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/core/lwt_bpf.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/sched/act_api.c (c0d576cc)
Location: include/net/netlink.h:1045
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_fill_size
```
```
In net/netlink/af_netlink.c (c0d5fcc8)
Location: include/net/netlink.h:1045
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/ipv4/tcp.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/ipv4/fib_semantics.c (c0dc4c5c)
Location: include/net/netlink.h:1045
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/ip_tunnel_core.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/ipv4/nexthop.c (c0dcf1c8)
Location: include/net/netlink.h:1045
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_notify
```
```
In net/ipv4/fib_rules.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/ipv4/ipmr.c (c0dd5a24)
Location: include/net/netlink.h:1045
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/ipv6/ip6mr.c (c0e45c4c)
Location: include/net/netlink.h:1045
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/fib6_rules.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (c0e4fc44)
Location: include/net/netlink.h:1045
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_encap_nlsize
```
```
In net/ipv6/seg6_local.c (c0e50af0)
Location: include/net/netlink.h:1045
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_get_encap_size
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
In kernel/taskstats.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In fs/quota/netlink.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In lib/nlattr.c (c000000000816148)
Location: include/net/netlink.h:1045
Inline: True
Inline callers:
  - lib/nlattr.c:nla_put_64bit
  - lib/nlattr.c:nla_put
  - lib/nlattr.c:nla_reserve_64bit
  - lib/nlattr.c:__nla_reserve
  - lib/nlattr.c:nla_policy_len
  - lib/nlattr.c:nla_policy_len
  - lib/nlattr.c:nla_policy_len
```
```
In drivers/net/tun.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/core/rtnetlink.c (c000000000cd3f84)
Location: include/net/netlink.h:1045
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:if_nlmsg_size
  - net/core/rtnetlink.c:if_nlmsg_size
  - net/core/rtnetlink.c:if_nlmsg_size
```
```
In net/core/sock_diag.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/core/drop_monitor.c (c000000000d0ceac)
Location: include/net/netlink.h:1045
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/lwtunnel.c (c000000000d0f714)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/core/lwt_bpf.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/sched/act_api.c (c000000000d42d38)
Location: include/net/netlink.h:1045
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_fill_size
```
```
In net/netlink/af_netlink.c (c000000000d4e594)
Location: include/net/netlink.h:1045
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/ipv4/tcp.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/ipv4/fib_semantics.c (c000000000dd22b0)
Location: include/net/netlink.h:1045
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/ip_tunnel_core.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/ipv4/nexthop.c (c000000000ddfa94)
Location: include/net/netlink.h:1045
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_notify
```
```
In net/ipv4/fib_rules.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/ipv4/ipmr.c (c000000000de81c8)
Location: include/net/netlink.h:1045
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/ipv6/ip6mr.c (c000000000e789fc)
Location: include/net/netlink.h:1045
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/fib6_rules.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (c000000000e86168)
Location: include/net/netlink.h:1045
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_encap_nlsize
```
```
In net/ipv6/seg6_local.c (c000000000e8765c)
Location: include/net/netlink.h:1045
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_get_encap_size
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
In kernel/taskstats.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In fs/quota/netlink.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In lib/nlattr.c (ffffffe00048e89e)
Location: include/net/netlink.h:1045
Inline: True
Inline callers:
  - lib/nlattr.c:nla_put
  - lib/nlattr.c:__nla_reserve
  - lib/nlattr.c:nla_policy_len
  - lib/nlattr.c:nla_policy_len
  - lib/nlattr.c:nla_policy_len
```
```
In drivers/net/tun.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/core/rtnetlink.c (ffffffe000771f2c)
Location: include/net/netlink.h:1045
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:if_nlmsg_size
  - net/core/rtnetlink.c:if_nlmsg_size
  - net/core/rtnetlink.c:if_nlmsg_size
```
```
In net/core/sock_diag.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/core/drop_monitor.c (ffffffe000796210)
Location: include/net/netlink.h:1045
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/lwtunnel.c (ffffffe000797a8a)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/core/lwt_bpf.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/sched/act_api.c (ffffffe0007b4858)
Location: include/net/netlink.h:1045
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_fill_size
```
```
In net/netlink/af_netlink.c (ffffffe0007bb6b8)
Location: include/net/netlink.h:1045
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/ipv4/tcp.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffe00081016a)
Location: include/net/netlink.h:1045
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/ip_tunnel_core.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffe000818e90)
Location: include/net/netlink.h:1045
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_notify
```
```
In net/ipv4/fib_rules.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffe00081e836)
Location: include/net/netlink.h:1045
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffe00087ea02)
Location: include/net/netlink.h:1045
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/fib6_rules.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (ffffffe00088772a)
Location: include/net/netlink.h:1045
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_encap_nlsize
```
```
In net/ipv6/seg6_local.c (ffffffe0008884e4)
Location: include/net/netlink.h:1045
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_get_encap_size
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
In kernel/taskstats.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In fs/quota/netlink.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In lib/nlattr.c (ffffffff8154dff0)
Location: include/net/netlink.h:1045
Inline: True
Inline callers:
  - lib/nlattr.c:nla_put_64bit
  - lib/nlattr.c:nla_put
  - lib/nlattr.c:nla_reserve_64bit
  - lib/nlattr.c:__nla_reserve
  - lib/nlattr.c:nla_policy_len
```
```
In drivers/acpi/event.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/core/rtnetlink.c (ffffffff818edcdf)
Location: include/net/netlink.h:1045
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:if_nlmsg_size
  - net/core/rtnetlink.c:if_nlmsg_size
  - net/core/rtnetlink.c:if_nlmsg_size
```
```
In net/core/sock_diag.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff81915c8e)
Location: include/net/netlink.h:1045
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/lwtunnel.c (ffffffff819173da)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/core/lwt_bpf.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/sched/act_api.c (ffffffff8193972d)
Location: include/net/netlink.h:1045
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_fill_size
```
```
In net/netlink/af_netlink.c (ffffffff819412dd)
Location: include/net/netlink.h:1045
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/ipv4/tcp.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff819a0c58)
Location: include/net/netlink.h:1045
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/ip_tunnel_core.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff819aa4f0)
Location: include/net/netlink.h:1045
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_notify
```
```
In net/ipv4/fib_rules.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff819b0304)
Location: include/net/netlink.h:1045
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81a19222)
Location: include/net/netlink.h:1045
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/fib6_rules.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a22745)
Location: include/net/netlink.h:1045
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_encap_nlsize
```
```
In net/ipv6/seg6_local.c (ffffffff81a2369b)
Location: include/net/netlink.h:1045
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_get_encap_size
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
In kernel/taskstats.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In fs/quota/netlink.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In lib/nlattr.c (ffffffff8153e2d0)
Location: include/net/netlink.h:1045
Inline: True
Inline callers:
  - lib/nlattr.c:nla_put_64bit
  - lib/nlattr.c:nla_put
  - lib/nlattr.c:nla_reserve_64bit
  - lib/nlattr.c:__nla_reserve
  - lib/nlattr.c:nla_policy_len
```
```
In drivers/acpi/event.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In drivers/net/vxlan.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/core/rtnetlink.c (ffffffff818a7b1f)
Location: include/net/netlink.h:1045
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:if_nlmsg_size
  - net/core/rtnetlink.c:if_nlmsg_size
  - net/core/rtnetlink.c:if_nlmsg_size
```
```
In net/core/sock_diag.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff818cfa3e)
Location: include/net/netlink.h:1045
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/lwtunnel.c (ffffffff818d118a)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/core/lwt_bpf.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/sched/act_api.c (ffffffff818f322d)
Location: include/net/netlink.h:1045
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_fill_size
```
```
In net/netlink/af_netlink.c (ffffffff818fadcd)
Location: include/net/netlink.h:1045
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/ipv4/tcp.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff8195a718)
Location: include/net/netlink.h:1045
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/ip_tunnel_core.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81963fb0)
Location: include/net/netlink.h:1045
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_notify
```
```
In net/ipv4/fib_rules.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff8196c934)
Location: include/net/netlink.h:1045
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff819d5fe2)
Location: include/net/netlink.h:1045
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/fib6_rules.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819df505)
Location: include/net/netlink.h:1045
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_encap_nlsize
```
```
In net/ipv6/seg6_local.c (ffffffff819e045b)
Location: include/net/netlink.h:1045
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_get_encap_size
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
In kernel/taskstats.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In fs/quota/netlink.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In lib/nlattr.c (ffffffff81549d30)
Location: include/net/netlink.h:1045
Inline: True
Inline callers:
  - lib/nlattr.c:nla_put_64bit
  - lib/nlattr.c:nla_put
  - lib/nlattr.c:nla_reserve_64bit
  - lib/nlattr.c:__nla_reserve
  - lib/nlattr.c:nla_policy_len
```
```
In drivers/acpi/event.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/core/rtnetlink.c (ffffffff8193ed0f)
Location: include/net/netlink.h:1045
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:if_nlmsg_size
  - net/core/rtnetlink.c:if_nlmsg_size
  - net/core/rtnetlink.c:if_nlmsg_size
```
```
In net/core/sock_diag.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff81966cbe)
Location: include/net/netlink.h:1045
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/lwtunnel.c (ffffffff8196856a)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/core/lwt_bpf.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/sched/act_api.c (ffffffff8198a8bd)
Location: include/net/netlink.h:1045
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_fill_size
```
```
In net/netlink/af_netlink.c (ffffffff8199246d)
Location: include/net/netlink.h:1045
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/netfilter/nfnetlink_queue.c (ffffffff81999c70)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/netfilter/nfnetlink_log.c (ffffffff8199c6c8)
Location: include/net/netlink.h:1045
Inline: True
Inline callers:
  - net/netfilter/nfnetlink_log.c:nfulnl_log_packet
  - net/netfilter/nfnetlink_log.c:nfulnl_log_packet
  - net/netfilter/nfnetlink_log.c:nfulnl_log_packet
  - net/netfilter/nfnetlink_log.c:__build_packet_message
```
```
In net/netfilter/nf_conntrack_netlink.c (ffffffff819ae30c)
Location: include/net/netlink.h:1045
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_glue_build_size
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_conntrack_event
```
```
In net/ipv4/tcp.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff81a0b4f8)
Location: include/net/netlink.h:1045
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/ip_tunnel_core.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81a14d90)
Location: include/net/netlink.h:1045
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_notify
```
```
In net/ipv4/fib_rules.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81a1aba4)
Location: include/net/netlink.h:1045
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81a83ca2)
Location: include/net/netlink.h:1045
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/fib6_rules.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a8d1c5)
Location: include/net/netlink.h:1045
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_encap_nlsize
```
```
In net/ipv6/seg6_local.c (ffffffff81a8e11b)
Location: include/net/netlink.h:1045
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_get_encap_size
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
In kernel/taskstats.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In fs/quota/netlink.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In lib/nlattr.c (ffffffff81563b80)
Location: include/net/netlink.h:1045
Inline: True
Inline callers:
  - lib/nlattr.c:nla_put_64bit
  - lib/nlattr.c:nla_put
  - lib/nlattr.c:nla_reserve_64bit
  - lib/nlattr.c:__nla_reserve
  - lib/nlattr.c:nla_policy_len
```
```
In drivers/acpi/event.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/core/rtnetlink.c (ffffffff819605af)
Location: include/net/netlink.h:1045
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:if_nlmsg_size
  - net/core/rtnetlink.c:if_nlmsg_size
  - net/core/rtnetlink.c:if_nlmsg_size
```
```
In net/core/sock_diag.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff81988f4e)
Location: include/net/netlink.h:1045
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/lwtunnel.c (ffffffff8198a8c5)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/core/lwt_bpf.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/sched/act_api.c (ffffffff819ad477)
Location: include/net/netlink.h:1045
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_fill_size
```
```
In net/netlink/af_netlink.c (ffffffff819b4f5d)
Location: include/net/netlink.h:1045
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/ipv4/tcp.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff81a15cd8)
Location: include/net/netlink.h:1045
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
```
In net/ipv4/ip_tunnel_core.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81a1f7a0)
Location: include/net/netlink.h:1045
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_notify
```
```
In net/ipv4/fib_rules.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81a25a09)
Location: include/net/netlink.h:1045
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81a905c7)
Location: include/net/netlink.h:1045
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/fib6_rules.c (0)
Location: include/net/netlink.h:1045
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a99eb5)
Location: include/net/netlink.h:1045
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_encap_nlsize
```
```
In net/ipv6/seg6_local.c (ffffffff81a9ae8b)
Location: include/net/netlink.h:1045
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_get_encap_size
```
</details>
</li>
</ul>

## Differences
