# Function: <code>rtnl_unicast</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int rtnl_unicast(struct sk_buff *skb, struct net *net, u32 pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff8172a070)
Location: net/core/rtnetlink.c:634
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_getlink
Direct callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/sched/act_api.c:tca_action_gd
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/dcb/dcbnl.c:dcb_doit
```
**Symbols:**

```
ffffffff8172a070-ffffffff8172a09c: rtnl_unicast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int rtnl_unicast(struct sk_buff *skb, struct net *net, u32 pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff8179675c)
Location: net/core/rtnetlink.c:656
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_getlink
Direct callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/sched/act_api.c:tca_action_gd
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/dcb/dcbnl.c:dcb_doit
```
**Symbols:**

```
ffffffff81793aa0-ffffffff81793acc: rtnl_unicast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int rtnl_unicast(struct sk_buff *skb, struct net *net, u32 pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff817c4db9)
Location: net/core/rtnetlink.c:657
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_getlink
Direct callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/sched/act_api.c:tca_action_gd
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/dcb/dcbnl.c:dcb_doit
```
**Symbols:**

```
ffffffff817c1370-ffffffff817c139c: rtnl_unicast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int rtnl_unicast(struct sk_buff *skb, struct net *net, u32 pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff817e3846)
Location: net/core/rtnetlink.c:659
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_getlink
Direct callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/sched/act_api.c:tca_action_gd
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/dcb/dcbnl.c:dcb_doit
```
**Symbols:**

```
ffffffff817dfb20-ffffffff817dfb4c: rtnl_unicast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int rtnl_unicast(struct sk_buff *skb, struct net *net, u32 pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff8185e77f)
Location: net/core/rtnetlink.c:632
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_getlink
Direct callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/sched/act_api.c:tca_action_gd
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/dcb/dcbnl.c:dcb_doit
```
**Symbols:**

```
ffffffff8185a3f0-ffffffff8185a41c: rtnl_unicast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int rtnl_unicast(struct sk_buff *skb, struct net *net, u32 pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818aa33a)
Location: net/core/rtnetlink.c:715
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_getlink
Direct callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/sched/act_api.c:tca_action_gd
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/dcb/dcbnl.c:dcb_doit
```
**Symbols:**

```
ffffffff818a5ca0-ffffffff818a5ccc: rtnl_unicast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int rtnl_unicast(struct sk_buff *skb, struct net *net, u32 pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818cea2a)
Location: net/core/rtnetlink.c:725
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_getlink
Direct callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_get
  - net/sched/act_api.c:tca_action_gd
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/dcb/dcbnl.c:dcb_doit
```
**Symbols:**

```
ffffffff818c9250-ffffffff818c927c: rtnl_unicast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int rtnl_unicast(struct sk_buff *skb, struct net *net, u32 pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff8191b83a)
Location: net/core/rtnetlink.c:720
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_getlink
Direct callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_get
  - net/sched/act_api.c:tca_action_gd
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/dcb/dcbnl.c:dcb_doit
```
**Symbols:**

```
ffffffff81916220-ffffffff8191624c: rtnl_unicast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int rtnl_unicast(struct sk_buff *skb, struct net *net, u32 pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff8194de71)
Location: net/core/rtnetlink.c:720
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_getlink
Direct callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_get
  - net/sched/act_api.c:tca_action_gd
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/dcb/dcbnl.c:dcb_doit
```
**Symbols:**

```
ffffffff81948850-ffffffff8194887c: rtnl_unicast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int rtnl_unicast(struct sk_buff *skb, struct net *net, u32 pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81a1f9f7)
Location: net/core/rtnetlink.c:720
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_getlink
Direct callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_get
  - net/sched/act_api.c:tca_action_gd
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:ipmr_cache_resolve
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/ip6mr.c:ip6mr_cache_resolve
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/dcb/dcbnl.c:dcb_doit
```
**Symbols:**

```
ffffffff81a18640-ffffffff81a1866c: rtnl_unicast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int rtnl_unicast(struct sk_buff *skb, struct net *net, u32 pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81a1f457)
Location: net/core/rtnetlink.c:722
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_getlink
Direct callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_get
  - net/sched/act_api.c:tca_action_gd
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:ipmr_cache_resolve
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/ip6mr.c:ip6mr_cache_resolve
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/dcb/dcbnl.c:dcb_doit
```
**Symbols:**

```
ffffffff81a186f0-ffffffff81a1871c: rtnl_unicast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int rtnl_unicast(struct sk_buff *skb, struct net *net, u32 pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81a064fc)
Location: net/core/rtnetlink.c:724
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_getlink
Direct callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_get
  - net/sched/act_api.c:tca_action_gd
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/nexthop.c:rtm_get_nexthop_bucket
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/dcb/dcbnl.c:dcb_doit
```
**Symbols:**

```
ffffffff819ff5c0-ffffffff819ff5e9: rtnl_unicast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int rtnl_unicast(struct sk_buff *skb, struct net *net, u32 pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81ab8b7c)
Location: net/core/rtnetlink.c:717
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_getlink
Direct callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_get
  - net/sched/cls_api.c:tc_chain_notify
  - net/sched/cls_api.c:tfilter_notify
  - net/sched/act_api.c:tca_action_gd
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/nexthop.c:rtm_get_nexthop_bucket
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/dcb/dcbnl.c:dcb_doit
```
**Symbols:**

```
ffffffff81ab18d0-ffffffff81ab18f9: rtnl_unicast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int rtnl_unicast(struct sk_buff *skb, struct net *net, u32 pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81c33f72)
Location: net/core/rtnetlink.c:754
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_getlink
Direct callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_get
  - net/sched/cls_api.c:tc_chain_notify
  - net/sched/cls_api.c:tfilter_notify
  - net/sched/act_api.c:tca_action_gd
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/nexthop.c:rtm_get_nexthop_bucket
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:ipmr_cache_resolve
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/dcb/dcbnl.c:dcb_doit
```
**Symbols:**

```
ffffffff81c2aaa0-ffffffff81c2aad5: rtnl_unicast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int rtnl_unicast(struct sk_buff *skb, struct net *net, u32 pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81de73e2)
Location: net/core/rtnetlink.c:755
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_getlink
Direct callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_get
  - net/sched/cls_api.c:tc_chain_notify
  - net/sched/cls_api.c:tfilter_notify
  - net/sched/act_api.c:tca_action_gd
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/nexthop.c:rtm_get_nexthop_bucket
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:ipmr_cache_resolve
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/ip6mr.c:ip6mr_rtm_getroute
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/dcb/dcbnl.c:dcb_doit
```
**Symbols:**

```
ffffffff81ddd820-ffffffff81ddd855: rtnl_unicast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int rtnl_unicast(struct sk_buff *skb, struct net *net, u32 pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81e583d2)
Location: net/core/rtnetlink.c:758
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_getlink
Direct callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_get
  - net/sched/cls_api.c:tc_chain_notify
  - net/sched/cls_api.c:tfilter_notify
  - net/sched/act_api.c:tca_action_gd
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/nexthop.c:rtm_get_nexthop_bucket
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:ipmr_cache_resolve
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/ip6mr.c:ip6mr_rtm_getroute
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/dcb/dcbnl.c:dcb_doit
```
**Symbols:**

```
ffffffff81e4e570-ffffffff81e4e5a5: rtnl_unicast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int rtnl_unicast(struct sk_buff *skb, struct net *net, u32 pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81f17722)
Location: net/core/rtnetlink.c:753
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_getlink
Direct callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_get
  - net/sched/cls_api.c:tc_chain_notify
  - net/sched/cls_api.c:tfilter_notify
  - net/sched/act_api.c:tca_action_gd
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/nexthop.c:rtm_get_nexthop_bucket
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:ipmr_cache_resolve
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/ip6mr.c:ip6mr_rtm_getroute
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/dcb/dcbnl.c:dcb_doit
```
**Symbols:**

```
ffffffff81f0d2d0-ffffffff81f0d305: rtnl_unicast (STB_GLOBAL)
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
int rtnl_unicast(struct sk_buff *skb, struct net *net, u32 pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffff800010befdcc)
Location: net/core/rtnetlink.c:720
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_getlink
Direct callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_get
  - net/sched/act_api.c:tca_action_gd
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/dcb/dcbnl.c:dcb_doit
```
**Symbols:**

```
ffff800010bea4d8-ffff800010bea528: rtnl_unicast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int rtnl_unicast(struct sk_buff *skb, struct net *net, u32 pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (c0d08404)
Location: net/core/rtnetlink.c:720
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_getlink
Direct callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_get
  - net/sched/act_api.c:tca_action_gd
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/dcb/dcbnl.c:dcb_doit
```
**Symbols:**

```
c0d02e64-c0d02e94: rtnl_unicast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int rtnl_unicast(struct sk_buff *skb, struct net *net, u32 pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (c000000000cd4160)
Location: net/core/rtnetlink.c:720
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_getlink
Direct callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_get
  - net/sched/act_api.c:tca_action_gd
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/dcb/dcbnl.c:dcb_doit
```
**Symbols:**

```
c000000000cccd30-c000000000cccd84: rtnl_unicast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int rtnl_unicast(struct sk_buff *skb, struct net *net, u32 pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffe00077202a)
Location: net/core/rtnetlink.c:720
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_getlink
Direct callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_get
  - net/sched/act_api.c:tca_action_gd
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/dcb/dcbnl.c:dcb_doit
```
**Symbols:**

```
ffffffe00076dca0-ffffffe00076dcec: rtnl_unicast (STB_GLOBAL)
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
int rtnl_unicast(struct sk_buff *skb, struct net *net, u32 pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818ede41)
Location: net/core/rtnetlink.c:720
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_getlink
Direct callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_get
  - net/sched/act_api.c:tca_action_gd
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/dcb/dcbnl.c:dcb_doit
```
**Symbols:**

```
ffffffff818e8820-ffffffff818e884c: rtnl_unicast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int rtnl_unicast(struct sk_buff *skb, struct net *net, u32 pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818a7c81)
Location: net/core/rtnetlink.c:720
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_getlink
Direct callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_get
  - net/sched/act_api.c:tca_action_gd
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/dcb/dcbnl.c:dcb_doit
```
**Symbols:**

```
ffffffff818a2660-ffffffff818a268c: rtnl_unicast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int rtnl_unicast(struct sk_buff *skb, struct net *net, u32 pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff8193ee71)
Location: net/core/rtnetlink.c:720
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_getlink
Direct callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_get
  - net/sched/act_api.c:tca_action_gd
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/dcb/dcbnl.c:dcb_doit
```
**Symbols:**

```
ffffffff81939850-ffffffff8193987c: rtnl_unicast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int rtnl_unicast(struct sk_buff *skb, struct net *net, u32 pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff8196072f)
Location: net/core/rtnetlink.c:720
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_getlink
Direct callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_get
  - net/sched/act_api.c:tca_action_gd
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_destroy_unres
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_destroy_unres
  - net/dcb/dcbnl.c:dcb_doit
```
**Symbols:**

```
ffffffff8195af30-ffffffff8195af5c: rtnl_unicast (STB_GLOBAL)
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
