# Function: <code>netlink_strict_get_check</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool netlink_strict_get_check(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81966780)
Location: net/netlink/af_netlink.c:1366
Inline: False
Direct callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_getlink
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/route.c:inet6_rtm_getroute
```
**Symbols:**

```
ffffffff81966780-ffffffff81966798: netlink_strict_get_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool netlink_strict_get_check(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff8199d210)
Location: net/netlink/af_netlink.c:1367
Inline: False
Direct callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_getlink
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/route.c:inet6_rtm_getroute
```
**Symbols:**

```
ffffffff8199d210-ffffffff8199d228: netlink_strict_get_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool netlink_strict_get_check(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81a76450)
Location: net/netlink/af_netlink.c:1367
Inline: False
Direct callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_getlink
  - net/ipv4/route.c:inet_rtm_valid_getroute_req
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/ipmr.c:ipmr_rtm_valid_getroute_req
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/route.c:inet6_rtm_valid_getroute_req
```
**Symbols:**

```
ffffffff81a76450-ffffffff81a76468: netlink_strict_get_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool netlink_strict_get_check(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81a7f1c0)
Location: net/netlink/af_netlink.c:1368
Inline: False
Direct callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_getlink
  - net/ipv4/route.c:inet_rtm_valid_getroute_req
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/ipmr.c:ipmr_rtm_valid_getroute_req
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/route.c:inet6_rtm_valid_getroute_req
```
**Symbols:**

```
ffffffff81a7f1c0-ffffffff81a7f1d8: netlink_strict_get_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool netlink_strict_get_check(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81a68060)
Location: net/netlink/af_netlink.c:1378
Inline: False
Direct callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_getlink
  - net/ipv4/route.c:inet_rtm_valid_getroute_req
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/ipmr.c:ipmr_rtm_valid_getroute_req
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/route.c:inet6_rtm_valid_getroute_req
```
**Symbols:**

```
ffffffff81a68060-ffffffff81a68078: netlink_strict_get_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool netlink_strict_get_check(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81b21580)
Location: net/netlink/af_netlink.c:1383
Inline: False
Direct callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_getlink
  - net/ipv4/route.c:inet_rtm_valid_getroute_req
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/ipmr.c:ipmr_rtm_valid_getroute_req
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/route.c:inet6_rtm_valid_getroute_req
```
**Symbols:**

```
ffffffff81b21580-ffffffff81b21598: netlink_strict_get_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool netlink_strict_get_check(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81ca99c0)
Location: net/netlink/af_netlink.c:1383
Inline: False
Direct callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/rtnetlink.c:rtnl_stats_set
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_getlink
  - net/ipv4/route.c:inet_rtm_valid_getroute_req
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/ipmr.c:ipmr_rtm_valid_getroute_req
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/route.c:inet6_rtm_valid_getroute_req
```
**Symbols:**

```
ffffffff81ca99c0-ffffffff81ca99de: netlink_strict_get_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool netlink_strict_get_check(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81e66970)
Location: net/netlink/af_netlink.c:1403
Inline: False
Direct callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/rtnetlink.c:rtnl_stats_set
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_getlink
  - net/ipv4/route.c:inet_rtm_valid_getroute_req
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/ipmr.c:ipmr_rtm_valid_getroute_req
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/route.c:inet6_rtm_valid_getroute_req
```
**Symbols:**

```
ffffffff81e66970-ffffffff81e6698e: netlink_strict_get_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool netlink_strict_get_check(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81ec2730)
Location: net/netlink/af_netlink.c:1403
Inline: False
Direct callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/rtnetlink.c:rtnl_stats_set
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_getlink
  - net/ipv4/route.c:inet_rtm_valid_getroute_req
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/ipmr.c:ipmr_rtm_valid_getroute_req
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/route.c:inet6_rtm_valid_getroute_req
```
**Symbols:**

```
ffffffff81ec2730-ffffffff81ec274e: netlink_strict_get_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool netlink_strict_get_check(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81f85a80)
Location: net/netlink/af_netlink.c:1405
Inline: False
Direct callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/rtnetlink.c:rtnl_stats_set
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_getlink
  - net/ipv4/route.c:inet_rtm_valid_getroute_req
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/ipmr.c:ipmr_rtm_valid_getroute_req
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/route.c:inet6_rtm_valid_getroute_req
```
**Symbols:**

```
ffffffff81f85a80-ffffffff81f85a9f: netlink_strict_get_check (STB_GLOBAL)
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
bool netlink_strict_get_check(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffff800010c4a7e0)
Location: net/netlink/af_netlink.c:1367
Inline: False
Direct callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_getlink
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/route.c:inet6_rtm_getroute
```
**Symbols:**

```
ffff800010c4a7e0-ffff800010c4a810: netlink_strict_get_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool netlink_strict_get_check(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (c0d5b2d8)
Location: net/netlink/af_netlink.c:1367
Inline: False
Direct callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_getlink
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/route.c:inet6_rtm_getroute
```
**Symbols:**

```
c0d5b2d8-c0d5b2fc: netlink_strict_get_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool netlink_strict_get_check(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (c000000000d48520)
Location: net/netlink/af_netlink.c:1367
Inline: False
Direct callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_getlink
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/route.c:inet6_rtm_getroute
```
**Symbols:**

```
c000000000d48520-c000000000d48538: netlink_strict_get_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool netlink_strict_get_check(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffe0007b7a0c)
Location: net/netlink/af_netlink.c:1367
Inline: False
Direct callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_getlink
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/route.c:inet6_rtm_getroute
```
**Symbols:**

```
ffffffe0007b7a0c-ffffffe0007b7a38: netlink_strict_get_check (STB_GLOBAL)
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
bool netlink_strict_get_check(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff8193d080)
Location: net/netlink/af_netlink.c:1367
Inline: False
Direct callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_getlink
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/route.c:inet6_rtm_getroute
```
**Symbols:**

```
ffffffff8193d080-ffffffff8193d098: netlink_strict_get_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool netlink_strict_get_check(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff818f6b80)
Location: net/netlink/af_netlink.c:1367
Inline: False
Direct callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_getlink
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/route.c:inet6_rtm_getroute
```
**Symbols:**

```
ffffffff818f6b80-ffffffff818f6b98: netlink_strict_get_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool netlink_strict_get_check(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff8198e210)
Location: net/netlink/af_netlink.c:1367
Inline: False
Direct callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_getlink
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/route.c:inet6_rtm_getroute
```
**Symbols:**

```
ffffffff8198e210-ffffffff8198e228: netlink_strict_get_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool netlink_strict_get_check(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff819b0ab0)
Location: net/netlink/af_netlink.c:1367
Inline: False
Direct callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/rtnetlink.c:rtnl_stats_get
  - net/core/rtnetlink.c:rtnl_getlink
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrlabel.c:ip6addrlbl_get
  - net/ipv6/route.c:inet6_rtm_getroute
```
**Symbols:**

```
ffffffff819b0ab0-ffffffff819b0ac8: netlink_strict_get_check (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
