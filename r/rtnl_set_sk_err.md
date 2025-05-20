# Function: <code>rtnl_set_sk_err</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void rtnl_set_sk_err(struct net *net, u32 group, int error);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff8172a0e0)
Location: net/core/rtnetlink.c:655
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
Direct callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/neighbour.c:__neigh_notify
  - net/core/fib_rules.c:notify_rule_change
  - net/ipv4/devinet.c:rtmsg_ifa
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/ipmr.c:mroute_netlink_event
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/dcb/dcbnl.c:dcbnl_notify
```
**Symbols:**

```
ffffffff8172a0e0-ffffffff8172a0fd: rtnl_set_sk_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void rtnl_set_sk_err(struct net *net, u32 group, int error);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff8179403f)
Location: net/core/rtnetlink.c:677
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
Direct callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/neighbour.c:__neigh_notify
  - net/core/fib_rules.c:notify_rule_change
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
  - net/ipv4/devinet.c:rtmsg_ifa
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/ipmr.c:mroute_netlink_event
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/dcb/dcbnl.c:dcbnl_notify
```
**Symbols:**

```
ffffffff81793b20-ffffffff81793b3d: rtnl_set_sk_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void rtnl_set_sk_err(struct net *net, u32 group, int error);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff817c18bf)
Location: net/core/rtnetlink.c:678
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
Direct callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/neighbour.c:__neigh_notify
  - net/core/fib_rules.c:notify_rule_change
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
  - net/ipv4/devinet.c:rtmsg_ifa
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/ipmr.c:mroute_netlink_event
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/dcb/dcbnl.c:dcbnl_notify
```
**Symbols:**

```
ffffffff817c13f0-ffffffff817c140d: rtnl_set_sk_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void rtnl_set_sk_err(struct net *net, u32 group, int error);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff817e006e)
Location: net/core/rtnetlink.c:680
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
Direct callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/neighbour.c:__neigh_notify
  - net/core/fib_rules.c:notify_rule_change
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
  - net/ipv4/devinet.c:rtmsg_ifa
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/ipmr.c:mroute_netlink_event
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/dcb/dcbnl.c:dcbnl_notify
```
**Symbols:**

```
ffffffff817dfb90-ffffffff817dfbad: rtnl_set_sk_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void rtnl_set_sk_err(struct net *net, u32 group, int error);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff8185a944)
Location: net/core/rtnetlink.c:653
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
Direct callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/neighbour.c:__neigh_notify
  - net/core/fib_rules.c:notify_rule_change
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
  - net/ipv4/devinet.c:rtmsg_ifa
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/ipmr.c:mroute_netlink_event
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/dcb/dcbnl.c:dcbnl_notify
```
**Symbols:**

```
ffffffff8185a460-ffffffff8185a47d: rtnl_set_sk_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void rtnl_set_sk_err(struct net *net, u32 group, int error);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818a622b)
Location: net/core/rtnetlink.c:736
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
Direct callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/neighbour.c:__neigh_notify
  - net/core/fib_rules.c:notify_rule_change
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
  - net/ipv4/devinet.c:rtmsg_ifa
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/ipmr.c:mroute_netlink_event
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/dcb/dcbnl.c:dcbnl_notify
```
**Symbols:**

```
ffffffff818a5d10-ffffffff818a5d2d: rtnl_set_sk_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void rtnl_set_sk_err(struct net *net, u32 group, int error);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818c9884)
Location: net/core/rtnetlink.c:746
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
Direct callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/neighbour.c:__neigh_notify
  - net/core/fib_rules.c:notify_rule_change
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
  - net/ipv4/devinet.c:rtmsg_ifa
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/ipmr.c:mroute_netlink_event
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/dcb/dcbnl.c:dcbnl_notify
```
**Symbols:**

```
ffffffff818c92c0-ffffffff818c92dd: rtnl_set_sk_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void rtnl_set_sk_err(struct net *net, u32 group, int error);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81916866)
Location: net/core/rtnetlink.c:741
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
Direct callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/neighbour.c:__neigh_notify
  - net/core/fib_rules.c:notify_rule_change
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
  - net/ipv4/devinet.c:rtmsg_ifa
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/nexthop.c:nexthop_notify
  - net/ipv4/ipmr.c:mroute_netlink_event
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/dcb/dcbnl.c:dcbnl_notify
```
**Symbols:**

```
ffffffff81916290-ffffffff819162ad: rtnl_set_sk_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void rtnl_set_sk_err(struct net *net, u32 group, int error);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81948eb8)
Location: net/core/rtnetlink.c:741
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
Direct callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/neighbour.c:__neigh_notify
  - net/core/fib_rules.c:notify_rule_change
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
  - net/ipv4/devinet.c:rtmsg_ifa
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/nexthop.c:nexthop_notify
  - net/ipv4/ipmr.c:mroute_netlink_event
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/dcb/dcbnl.c:dcbnl_notify
```
**Symbols:**

```
ffffffff819488c0-ffffffff819488dd: rtnl_set_sk_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void rtnl_set_sk_err(struct net *net, u32 group, int error);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81a197d8)
Location: net/core/rtnetlink.c:741
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
Direct callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/neighbour.c:__neigh_notify
  - net/core/fib_rules.c:notify_rule_change
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
  - net/ipv4/devinet.c:rtmsg_ifa
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/nexthop.c:nexthop_notify
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:mroute_netlink_event
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_ifa_notify
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/ndisc.c:ndisc_ra_useropt
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/dcb/dcbnl.c:dcbnl_notify
```
**Symbols:**

```
ffffffff81a186b0-ffffffff81a186cd: rtnl_set_sk_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void rtnl_set_sk_err(struct net *net, u32 group, int error);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81a199c8)
Location: net/core/rtnetlink.c:743
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
Direct callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/neighbour.c:__neigh_notify
  - net/core/fib_rules.c:notify_rule_change
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
  - net/ipv4/devinet.c:rtmsg_ifa
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/nexthop.c:nexthop_notify
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:mroute_netlink_event
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_ifa_notify
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/ndisc.c:ndisc_ra_useropt
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/dcb/dcbnl.c:dcbnl_notify
```
**Symbols:**

```
ffffffff81a18760-ffffffff81a1877d: rtnl_set_sk_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void rtnl_set_sk_err(struct net *net, u32 group, int error);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81a009b8)
Location: net/core/rtnetlink.c:745
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
Direct callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/neighbour.c:__neigh_notify
  - net/core/fib_rules.c:notify_rule_change
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
  - net/ipv4/devinet.c:rtmsg_ifa
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/fib_trie.c:fib_alias_hw_flags_set
  - net/ipv4/nexthop.c:nh_res_bucket_migrate
  - net/ipv4/nexthop.c:nexthop_notify
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:mroute_netlink_event
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
  - net/ipv6/route.c:fib6_info_hw_flags_set
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/ndisc.c:ndisc_ra_useropt
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/dcb/dcbnl.c:dcbnl_notify
```
**Symbols:**

```
ffffffff819ff630-ffffffff819ff64d: rtnl_set_sk_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void rtnl_set_sk_err(struct net *net, u32 group, int error);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81ab2d78)
Location: net/core/rtnetlink.c:734
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
Direct callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/neighbour.c:__neigh_notify
  - net/core/fib_rules.c:notify_rule_change
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
  - net/ipv4/devinet.c:rtmsg_ifa
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/fib_trie.c:fib_alias_hw_flags_set
  - net/ipv4/nexthop.c:nh_res_table_upkeep
  - net/ipv4/nexthop.c:nexthop_notify
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:mroute_netlink_event
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
  - net/ipv6/route.c:fib6_info_hw_flags_set
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/ndisc.c:ndisc_ra_useropt
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/dcb/dcbnl.c:dcbnl_notify
```
**Symbols:**

```
ffffffff81ab1900-ffffffff81ab191d: rtnl_set_sk_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void rtnl_set_sk_err(struct net *net, u32 group, int error);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81c33be2)
Location: net/core/rtnetlink.c:771
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_offload_xstats_notify
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
Direct callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/neighbour.c:__neigh_notify
  - net/core/fib_rules.c:notify_rule_change
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
  - net/ipv4/devinet.c:rtmsg_ifa
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/fib_trie.c:fib_alias_hw_flags_set
  - net/ipv4/nexthop.c:nh_res_table_upkeep
  - net/ipv4/nexthop.c:nexthop_notify
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:mroute_netlink_event
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
  - net/ipv6/route.c:fib6_info_hw_flags_set
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/ndisc.c:ndisc_ra_useropt
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/dcb/dcbnl.c:dcbnl_notify
  - net/mctp/device.c:mctp_addr_notify
```
**Symbols:**

```
ffffffff81c2aae0-ffffffff81c2ab0b: rtnl_set_sk_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void rtnl_set_sk_err(struct net *net, u32 group, int error);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81de7032)
Location: net/core/rtnetlink.c:772
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_offload_xstats_notify
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
Direct callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/neighbour.c:__neigh_notify
  - net/core/fib_rules.c:notify_rule_change
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
  - net/ipv4/devinet.c:rtmsg_ifa
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/fib_trie.c:fib_alias_hw_flags_set
  - net/ipv4/nexthop.c:nh_res_bucket_migrate
  - net/ipv4/nexthop.c:nexthop_notify
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:mroute_netlink_event
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
  - net/ipv6/route.c:fib6_info_hw_flags_set
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/ndisc.c:ndisc_ra_useropt
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/dcb/dcbnl.c:dcbnl_notify
  - net/mctp/device.c:mctp_addr_notify
```
**Symbols:**

```
ffffffff81ddd870-ffffffff81ddd89b: rtnl_set_sk_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void rtnl_set_sk_err(struct net *net, u32 group, int error);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81e58022)
Location: net/core/rtnetlink.c:775
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_offload_xstats_notify
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
Direct callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/neighbour.c:__neigh_notify
  - net/core/fib_rules.c:notify_rule_change
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
  - net/ipv4/devinet.c:rtmsg_ifa
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/fib_trie.c:fib_alias_hw_flags_set
  - net/ipv4/nexthop.c:nh_res_bucket_migrate
  - net/ipv4/nexthop.c:nexthop_notify
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:mroute_netlink_event
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
  - net/ipv6/route.c:fib6_info_hw_flags_set
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/ndisc.c:ndisc_ra_useropt
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/dcb/dcbnl.c:dcbnl_notify
  - net/mctp/device.c:mctp_addr_notify
```
**Symbols:**

```
ffffffff81e4e5c0-ffffffff81e4e5eb: rtnl_set_sk_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void rtnl_set_sk_err(struct net *net, u32 group, int error);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81f17372)
Location: net/core/rtnetlink.c:770
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_offload_xstats_notify
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
Direct callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/neighbour.c:__neigh_notify
  - net/core/fib_rules.c:notify_rule_change
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
  - net/ipv4/devinet.c:rtmsg_ifa
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/fib_trie.c:fib_alias_hw_flags_set
  - net/ipv4/nexthop.c:nh_res_bucket_migrate
  - net/ipv4/nexthop.c:nexthop_notify
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv4/ipmr.c:mroute_netlink_event
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
  - net/ipv6/route.c:fib6_info_hw_flags_set
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/ndisc.c:ndisc_ra_useropt
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/dcb/dcbnl.c:dcbnl_notify
  - net/mctp/device.c:mctp_addr_notify
```
**Symbols:**

```
ffffffff81f0d320-ffffffff81f0d34b: rtnl_set_sk_err (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void rtnl_set_sk_err(struct net *net, u32 group, int error);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffff800010bea8d0)
Location: net/core/rtnetlink.c:741
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
Direct callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/neighbour.c:__neigh_notify
  - net/core/fib_rules.c:notify_rule_change
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
  - net/ipv4/devinet.c:rtmsg_ifa
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/nexthop.c:nexthop_notify
  - net/ipv4/ipmr.c:mroute_netlink_event
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/dcb/dcbnl.c:dcbnl_notify
```
**Symbols:**

```
ffff800010bea598-ffff800010bea5e0: rtnl_set_sk_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void rtnl_set_sk_err(struct net *net, u32 group, int error);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (c0d036f8)
Location: net/core/rtnetlink.c:741
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
Direct callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/neighbour.c:__neigh_notify
  - net/core/fib_rules.c:notify_rule_change
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
  - net/ipv4/devinet.c:rtmsg_ifa
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/nexthop.c:nexthop_notify
  - net/ipv4/ipmr.c:mroute_netlink_event
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/dcb/dcbnl.c:dcbnl_notify
```
**Symbols:**

```
c0d02edc-c0d02f08: rtnl_set_sk_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void rtnl_set_sk_err(struct net *net, u32 group, int error);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (c000000000ccda3c)
Location: net/core/rtnetlink.c:741
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
Direct callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/neighbour.c:__neigh_notify
  - net/core/fib_rules.c:notify_rule_change
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
  - net/ipv4/devinet.c:rtmsg_ifa
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/nexthop.c:nexthop_notify
  - net/ipv4/ipmr.c:mroute_netlink_event
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/dcb/dcbnl.c:dcbnl_notify
```
**Symbols:**

```
c000000000ccce10-c000000000ccce58: rtnl_set_sk_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void rtnl_set_sk_err(struct net *net, u32 group, int error);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffe00076e418)
Location: net/core/rtnetlink.c:741
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
Direct callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/neighbour.c:__neigh_notify
  - net/core/fib_rules.c:notify_rule_change
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
  - net/ipv4/devinet.c:rtmsg_ifa
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/nexthop.c:nexthop_notify
  - net/ipv4/ipmr.c:mroute_netlink_event
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/dcb/dcbnl.c:dcbnl_notify
```
**Symbols:**

```
ffffffe00076dd4c-ffffffe00076dd8a: rtnl_set_sk_err (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void rtnl_set_sk_err(struct net *net, u32 group, int error);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818e8e88)
Location: net/core/rtnetlink.c:741
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
Direct callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/neighbour.c:__neigh_notify
  - net/core/fib_rules.c:notify_rule_change
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
  - net/ipv4/devinet.c:rtmsg_ifa
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/nexthop.c:nexthop_notify
  - net/ipv4/ipmr.c:mroute_netlink_event
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/dcb/dcbnl.c:dcbnl_notify
```
**Symbols:**

```
ffffffff818e8890-ffffffff818e88ad: rtnl_set_sk_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void rtnl_set_sk_err(struct net *net, u32 group, int error);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818a2cc8)
Location: net/core/rtnetlink.c:741
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
Direct callers:
  - drivers/net/vxlan.c:__vxlan_fdb_notify
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/neighbour.c:__neigh_notify
  - net/core/fib_rules.c:notify_rule_change
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
  - net/ipv4/devinet.c:rtmsg_ifa
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/nexthop.c:nexthop_notify
  - net/ipv4/ipmr.c:mroute_netlink_event
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/dcb/dcbnl.c:dcbnl_notify
```
**Symbols:**

```
ffffffff818a26d0-ffffffff818a26ed: rtnl_set_sk_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void rtnl_set_sk_err(struct net *net, u32 group, int error);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81939eb8)
Location: net/core/rtnetlink.c:741
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
Direct callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/neighbour.c:__neigh_notify
  - net/core/fib_rules.c:notify_rule_change
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
  - net/ipv4/devinet.c:rtmsg_ifa
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/nexthop.c:nexthop_notify
  - net/ipv4/ipmr.c:mroute_netlink_event
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/dcb/dcbnl.c:dcbnl_notify
```
**Symbols:**

```
ffffffff819398c0-ffffffff819398dd: rtnl_set_sk_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void rtnl_set_sk_err(struct net *net, u32 group, int error);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff8195b6e8)
Location: net/core/rtnetlink.c:741
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
Direct callers:
  - net/core/net_namespace.c:rtnl_net_notifyid
  - net/core/neighbour.c:__neigh_notify
  - net/core/fib_rules.c:notify_rule_change
  - net/ipv4/devinet.c:inet_netconf_notify_devconf
  - net/ipv4/devinet.c:rtmsg_ifa
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/nexthop.c:nexthop_notify
  - net/ipv4/ipmr.c:mroute_netlink_event
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:inet6_ifinfo_notify
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:inet6_netconf_notify_devconf
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/dcb/dcbnl.c:dcbnl_notify
```
**Symbols:**

```
ffffffff8195afa0-ffffffff8195afbd: rtnl_set_sk_err (STB_GLOBAL)
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
