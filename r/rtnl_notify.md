# Function: <code>rtnl_notify</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void rtnl_notify(struct sk_buff *skb, struct net *net, u32 pid, u32 group, struct nlmsghdr *nlh, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff8172a0a0)
Location: net/core/rtnetlink.c:642
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
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
  - net/wireless/wext-core.c:wireless_nlevent_flush
  - net/dcb/dcbnl.c:dcbnl_notify
```
**Symbols:**

```
ffffffff8172a0a0-ffffffff8172a0dd: rtnl_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void rtnl_notify(struct sk_buff *skb, struct net *net, u32 pid, u32 group, struct nlmsghdr *nlh, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff8179406c)
Location: net/core/rtnetlink.c:664
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
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
  - net/wireless/wext-core.c:wireless_nlevent_flush
  - net/dcb/dcbnl.c:dcbnl_notify
```
**Symbols:**

```
ffffffff81793ad0-ffffffff81793b15: rtnl_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void rtnl_notify(struct sk_buff *skb, struct net *net, u32 pid, u32 group, struct nlmsghdr *nlh, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff817c18ec)
Location: net/core/rtnetlink.c:665
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
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
  - net/wireless/wext-core.c:wireless_nlevent_flush
  - net/dcb/dcbnl.c:dcbnl_notify
```
**Symbols:**

```
ffffffff817c13a0-ffffffff817c13e5: rtnl_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void rtnl_notify(struct sk_buff *skb, struct net *net, u32 pid, u32 group, struct nlmsghdr *nlh, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff817e008c)
Location: net/core/rtnetlink.c:667
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
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
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/wireless/wext-core.c:wireless_nlevent_flush
  - net/dcb/dcbnl.c:dcbnl_notify
```
**Symbols:**

```
ffffffff817dfb50-ffffffff817dfb86: rtnl_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void rtnl_notify(struct sk_buff *skb, struct net *net, u32 pid, u32 group, struct nlmsghdr *nlh, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff8185a962)
Location: net/core/rtnetlink.c:640
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
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
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/wireless/wext-core.c:wireless_nlevent_flush
  - net/dcb/dcbnl.c:dcbnl_notify
```
**Symbols:**

```
ffffffff8185a420-ffffffff8185a456: rtnl_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void rtnl_notify(struct sk_buff *skb, struct net *net, u32 pid, u32 group, struct nlmsghdr *nlh, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818a61e4)
Location: net/core/rtnetlink.c:723
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
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
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/wireless/wext-core.c:wireless_nlevent_flush
  - net/dcb/dcbnl.c:dcbnl_notify
```
**Symbols:**

```
ffffffff818a5cd0-ffffffff818a5d06: rtnl_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void rtnl_notify(struct sk_buff *skb, struct net *net, u32 pid, u32 group, struct nlmsghdr *nlh, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818c983d)
Location: net/core/rtnetlink.c:733
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
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
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/wireless/wext-core.c:wireless_nlevent_flush
  - net/dcb/dcbnl.c:dcbnl_notify
```
**Symbols:**

```
ffffffff818c9280-ffffffff818c92b6: rtnl_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void rtnl_notify(struct sk_buff *skb, struct net *net, u32 pid, u32 group, struct nlmsghdr *nlh, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff8191681e)
Location: net/core/rtnetlink.c:728
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
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
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/wireless/wext-core.c:wireless_nlevent_flush
  - net/dcb/dcbnl.c:dcbnl_notify
```
**Symbols:**

```
ffffffff81916250-ffffffff81916286: rtnl_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void rtnl_notify(struct sk_buff *skb, struct net *net, u32 pid, u32 group, struct nlmsghdr *nlh, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81948e6e)
Location: net/core/rtnetlink.c:728
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
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
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/wireless/wext-core.c:wireless_nlevent_flush
  - net/dcb/dcbnl.c:dcbnl_notify
```
**Symbols:**

```
ffffffff81948880-ffffffff819488b6: rtnl_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void rtnl_notify(struct sk_buff *skb, struct net *net, u32 pid, u32 group, struct nlmsghdr *nlh, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81a219ef)
Location: net/core/rtnetlink.c:728
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_event
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_newnet
  - net/core/rtnetlink.c:rtmsg_ifinfo
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
  - net/ipv6/route.c:__ip6_del_rt_siblings
  - net/ipv6/ndisc.c:ndisc_ra_useropt
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/wireless/wext-core.c:wireless_nlevent_flush
  - net/dcb/dcbnl.c:dcbnl_notify
```
**Symbols:**

```
ffffffff81a18670-ffffffff81a186a6: rtnl_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void rtnl_notify(struct sk_buff *skb, struct net *net, u32 pid, u32 group, struct nlmsghdr *nlh, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81a21e2f)
Location: net/core/rtnetlink.c:730
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_event
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_newnet
  - net/core/rtnetlink.c:rtmsg_ifinfo
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
  - net/ipv6/route.c:__ip6_del_rt_siblings
  - net/ipv6/ndisc.c:ndisc_ra_useropt
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/wireless/wext-core.c:wireless_nlevent_flush
  - net/dcb/dcbnl.c:dcbnl_notify
```
**Symbols:**

```
ffffffff81a18720-ffffffff81a18756: rtnl_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void rtnl_notify(struct sk_buff *skb, struct net *net, u32 pid, u32 group, struct nlmsghdr *nlh, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81a09164)
Location: net/core/rtnetlink.c:732
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_event
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_newnet
  - net/core/rtnetlink.c:rtmsg_ifinfo
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
  - net/ipv6/route.c:__ip6_del_rt_siblings
  - net/ipv6/ndisc.c:ndisc_ra_useropt
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/wireless/wext-core.c:wireless_nlevent_flush
  - net/dcb/dcbnl.c:dcbnl_notify
```
**Symbols:**

```
ffffffff819ff5f0-ffffffff819ff626: rtnl_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void rtnl_notify(struct sk_buff *skb, struct net *net, u32 pid, u32 group, struct nlmsghdr *nlh, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81abb634)
Location: net/core/rtnetlink.c:725
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_event
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_newnet
  - net/core/rtnetlink.c:rtmsg_ifinfo
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
  - net/ipv6/route.c:__ip6_del_rt_siblings
  - net/ipv6/ndisc.c:ndisc_ra_useropt
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/wireless/wext-core.c:wireless_nlevent_flush
  - net/dcb/dcbnl.c:dcbnl_notify
```
**Symbols:**

```
ffffffff81ab1890-ffffffff81ab18c6: rtnl_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void rtnl_notify(struct sk_buff *skb, struct net *net, u32 pid, u32 group, struct nlmsghdr *nlh, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81c35ea8)
Location: net/core/rtnetlink.c:762
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_event
  - net/core/rtnetlink.c:rtnl_offload_xstats_notify
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_newnet
  - net/core/rtnetlink.c:rtmsg_ifinfo
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
  - net/ipv6/route.c:__ip6_del_rt_siblings
  - net/ipv6/ndisc.c:ndisc_ra_useropt
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/wireless/wext-core.c:wireless_nlevent_flush
  - net/dcb/dcbnl.c:dcbnl_notify
  - net/mctp/device.c:mctp_addr_notify
```
**Symbols:**

```
ffffffff81c2aa50-ffffffff81c2aa9d: rtnl_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void rtnl_notify(struct sk_buff *skb, struct net *net, u32 pid, u32 group, const struct nlmsghdr *nlh, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81de946f)
Location: net/core/rtnetlink.c:763
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_event
  - net/core/rtnetlink.c:rtnl_offload_xstats_notify
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_newnet
  - net/core/rtnetlink.c:rtmsg_ifinfo
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
  - net/ipv6/route.c:__ip6_del_rt_siblings
  - net/ipv6/ndisc.c:ndisc_ra_useropt
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/wireless/wext-core.c:wireless_nlevent_flush
  - net/dcb/dcbnl.c:dcbnl_notify
  - net/mctp/device.c:mctp_addr_notify
```
**Symbols:**

```
ffffffff81ddd7c0-ffffffff81ddd80d: rtnl_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void rtnl_notify(struct sk_buff *skb, struct net *net, u32 pid, u32 group, const struct nlmsghdr *nlh, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81e5accf)
Location: net/core/rtnetlink.c:766
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_event
  - net/core/rtnetlink.c:rtnl_offload_xstats_notify
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_newnet
  - net/core/rtnetlink.c:rtmsg_ifinfo
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
  - net/ipv6/route.c:__ip6_del_rt_siblings
  - net/ipv6/ndisc.c:ndisc_ra_useropt
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/wireless/wext-core.c:wireless_nlevent_flush
  - net/dcb/dcbnl.c:dcbnl_notify
  - net/mctp/device.c:mctp_addr_notify
```
**Symbols:**

```
ffffffff81e4e510-ffffffff81e4e55d: rtnl_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void rtnl_notify(struct sk_buff *skb, struct net *net, u32 pid, u32 group, const struct nlmsghdr *nlh, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81f1a08f)
Location: net/core/rtnetlink.c:761
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_event
  - net/core/rtnetlink.c:rtnl_offload_xstats_notify
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_newnet
  - net/core/rtnetlink.c:rtmsg_ifinfo
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
  - net/ipv6/route.c:__ip6_del_rt_siblings
  - net/ipv6/ndisc.c:ndisc_ra_useropt
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/wireless/wext-core.c:wireless_nlevent_flush
  - net/dcb/dcbnl.c:dcbnl_notify
  - net/mctp/device.c:mctp_addr_notify
```
**Symbols:**

```
ffffffff81f0d270-ffffffff81f0d2bd: rtnl_notify (STB_GLOBAL)
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
void rtnl_notify(struct sk_buff *skb, struct net *net, u32 pid, u32 group, struct nlmsghdr *nlh, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffff800010bea860)
Location: net/core/rtnetlink.c:728
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
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
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/wireless/wext-core.c:wireless_nlevent_flush
  - net/dcb/dcbnl.c:dcbnl_notify
```
**Symbols:**

```
ffff800010bea528-ffff800010bea598: rtnl_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void rtnl_notify(struct sk_buff *skb, struct net *net, u32 pid, u32 group, struct nlmsghdr *nlh, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (c0d03680)
Location: net/core/rtnetlink.c:728
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
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
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/wireless/wext-core.c:wireless_nlevent_flush
  - net/dcb/dcbnl.c:dcbnl_notify
```
**Symbols:**

```
c0d02e94-c0d02edc: rtnl_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void rtnl_notify(struct sk_buff *skb, struct net *net, u32 pid, u32 group, struct nlmsghdr *nlh, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (c000000000ccd994)
Location: net/core/rtnetlink.c:728
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
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
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/wireless/wext-core.c:wireless_nlevent_flush
  - net/dcb/dcbnl.c:dcbnl_notify
```
**Symbols:**

```
c000000000cccd90-c000000000ccce10: rtnl_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void rtnl_notify(struct sk_buff *skb, struct net *net, u32 pid, u32 group, struct nlmsghdr *nlh, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffe00076e3ca)
Location: net/core/rtnetlink.c:728
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
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
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/wireless/wext-core.c:wireless_nlevent_flush
  - net/dcb/dcbnl.c:dcbnl_notify
```
**Symbols:**

```
ffffffe00076dcec-ffffffe00076dd4c: rtnl_notify (STB_GLOBAL)
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
void rtnl_notify(struct sk_buff *skb, struct net *net, u32 pid, u32 group, struct nlmsghdr *nlh, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818e8e3e)
Location: net/core/rtnetlink.c:728
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
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
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/wireless/wext-core.c:wireless_nlevent_flush
  - net/dcb/dcbnl.c:dcbnl_notify
```
**Symbols:**

```
ffffffff818e8850-ffffffff818e8886: rtnl_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void rtnl_notify(struct sk_buff *skb, struct net *net, u32 pid, u32 group, struct nlmsghdr *nlh, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818a2c7e)
Location: net/core/rtnetlink.c:728
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
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
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/wireless/wext-core.c:wireless_nlevent_flush
  - net/dcb/dcbnl.c:dcbnl_notify
```
**Symbols:**

```
ffffffff818a2690-ffffffff818a26c6: rtnl_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void rtnl_notify(struct sk_buff *skb, struct net *net, u32 pid, u32 group, struct nlmsghdr *nlh, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81939e6e)
Location: net/core/rtnetlink.c:728
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
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
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/wireless/wext-core.c:wireless_nlevent_flush
  - net/dcb/dcbnl.c:dcbnl_notify
```
**Symbols:**

```
ffffffff81939880-ffffffff819398b6: rtnl_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void rtnl_notify(struct sk_buff *skb, struct net *net, u32 pid, u32 group, struct nlmsghdr *nlh, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff8195b69e)
Location: net/core/rtnetlink.c:728
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
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
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/wireless/wext-core.c:wireless_nlevent_flush
  - net/dcb/dcbnl.c:dcbnl_notify
```
**Symbols:**

```
ffffffff8195af60-ffffffff8195af96: rtnl_notify (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct nlmsghdr *nlh</code> ➡️ <code>const struct nlmsghdr *nlh</code>
</li>
</ul>
</details>
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
