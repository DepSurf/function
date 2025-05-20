# Function: <code>nlmsg_parse_deprecated_strict</code>

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
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff818f392d)
Location: include/net/netlink.h:721
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
```
```
In net/core/neighbour.c (ffffffff819101d1)
Location: include/net/netlink.h:721
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_valid_dump_req
```
```
In net/core/rtnetlink.c (ffffffff8191828e)
Location: include/net/netlink.h:721
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:valid_fdb_dump_strict
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/ipv4/route.c (ffffffff81975e95)
Location: include/net/netlink.h:721
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/devinet.c (ffffffff819b984f)
Location: include/net/netlink.h:721
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
```
```
In net/ipv4/fib_frontend.c (ffffffff819c4f62)
Location: include/net/netlink.h:721
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
```
```
In net/ipv4/ipmr.c (ffffffff819db563)
Location: include/net/netlink.h:721
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
```
```
In net/ipv6/addrconf.c (ffffffff81a0eb5e)
Location: include/net/netlink.h:721
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81a11884)
Location: include/net/netlink.h:721
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
```
```
In net/ipv6/route.c (ffffffff81a151e8)
Location: include/net/netlink.h:721
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
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
In net/core/net_namespace.c (ffffffff819258dd)
Location: include/net/netlink.h:721
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
```
```
In net/core/neighbour.c (ffffffff81942841)
Location: include/net/netlink.h:721
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_valid_dump_req
```
```
In net/core/rtnetlink.c (ffffffff8194a8ae)
Location: include/net/netlink.h:721
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:valid_fdb_dump_strict
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/ipv4/route.c (ffffffff819ac8a5)
Location: include/net/netlink.h:721
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/devinet.c (ffffffff819f0550)
Location: include/net/netlink.h:721
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
```
```
In net/ipv4/fib_frontend.c (ffffffff819fbb02)
Location: include/net/netlink.h:721
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
```
```
In net/ipv4/ipmr.c (ffffffff81a12438)
Location: include/net/netlink.h:721
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
```
```
In net/ipv6/addrconf.c (ffffffff81a4589c)
Location: include/net/netlink.h:721
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81a484a4)
Location: include/net/netlink.h:721
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
```
```
In net/ipv6/route.c (ffffffff81a4bdb8)
Location: include/net/netlink.h:721
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
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
In net/core/net_namespace.c (ffffffff819f9a5d)
Location: include/net/netlink.h:773
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
```
```
In net/core/neighbour.c (ffffffff81a12921)
Location: include/net/netlink.h:773
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_valid_dump_req
```
```
In net/core/rtnetlink.c (ffffffff81a1b0ea)
Location: include/net/netlink.h:773
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/ipv4/route.c (ffffffff81a91bf9)
Location: include/net/netlink.h:773
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_valid_getroute_req
```
```
In net/ipv4/devinet.c (ffffffff81ade4be)
Location: include/net/netlink.h:773
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
```
```
In net/ipv4/fib_frontend.c (ffffffff81ae9e19)
Location: include/net/netlink.h:773
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
```
```
In net/ipv4/ipmr.c (ffffffff81b013b1)
Location: include/net/netlink.h:773
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_valid_getroute_req
```
```
In net/ipv6/addrconf.c (ffffffff81b3c62c)
Location: include/net/netlink.h:773
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81b3f332)
Location: include/net/netlink.h:773
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
```
```
In net/ipv6/route.c (ffffffff81b41319)
Location: include/net/netlink.h:773
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_valid_getroute_req
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
In net/core/net_namespace.c (ffffffff819f95ad)
Location: include/net/netlink.h:787
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
```
```
In net/core/neighbour.c (ffffffff81a12c71)
Location: include/net/netlink.h:787
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_valid_dump_req
```
```
In net/core/rtnetlink.c (ffffffff81a1b27a)
Location: include/net/netlink.h:787
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/ipv4/route.c (ffffffff81a9ba89)
Location: include/net/netlink.h:787
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_valid_getroute_req
```
```
In net/ipv4/devinet.c (ffffffff81aeb29e)
Location: include/net/netlink.h:787
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
```
```
In net/ipv4/fib_frontend.c (ffffffff81af6c79)
Location: include/net/netlink.h:787
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
```
```
In net/ipv4/ipmr.c (ffffffff81b0f491)
Location: include/net/netlink.h:787
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_valid_getroute_req
```
```
In net/ipv6/addrconf.c (ffffffff81b4b33c)
Location: include/net/netlink.h:787
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81b4ddc2)
Location: include/net/netlink.h:787
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
```
```
In net/ipv6/route.c (ffffffff81b4fdd9)
Location: include/net/netlink.h:787
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_valid_getroute_req
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
In net/core/net_namespace.c (ffffffff819df70d)
Location: include/net/netlink.h:787
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
```
```
In net/core/neighbour.c (ffffffff819fa105)
Location: include/net/netlink.h:787
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_valid_dump_req
```
```
In net/core/rtnetlink.c (ffffffff81a08b20)
Location: include/net/netlink.h:787
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/ipv4/route.c (ffffffff81a86fc9)
Location: include/net/netlink.h:787
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_valid_getroute_req
```
```
In net/ipv4/devinet.c (ffffffff81ad7fbe)
Location: include/net/netlink.h:787
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
```
```
In net/ipv4/fib_frontend.c (ffffffff81ae23c9)
Location: include/net/netlink.h:787
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
```
```
In net/ipv4/ipmr.c (ffffffff81afd191)
Location: include/net/netlink.h:787
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_valid_getroute_req
```
```
In net/ipv6/addrconf.c (ffffffff81b38ecc)
Location: include/net/netlink.h:787
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81b3b862)
Location: include/net/netlink.h:787
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
```
```
In net/ipv6/route.c (ffffffff81b3e3f9)
Location: include/net/netlink.h:787
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_valid_getroute_req
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
In net/core/net_namespace.c (ffffffff81a8faed)
Location: include/net/netlink.h:787
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
```
```
In net/core/neighbour.c (ffffffff81aabe81)
Location: include/net/netlink.h:787
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_valid_dump_req
```
```
In net/core/rtnetlink.c (ffffffff81aba940)
Location: include/net/netlink.h:787
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/ipv4/route.c (ffffffff81b41789)
Location: include/net/netlink.h:787
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_valid_getroute_req
```
```
In net/ipv4/devinet.c (ffffffff81b96e1e)
Location: include/net/netlink.h:787
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
```
```
In net/ipv4/fib_frontend.c (ffffffff81ba1b99)
Location: include/net/netlink.h:787
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
```
```
In net/ipv4/ipmr.c (ffffffff81bbe981)
Location: include/net/netlink.h:787
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_valid_getroute_req
```
```
In net/ipv6/addrconf.c (ffffffff81bff66c)
Location: include/net/netlink.h:787
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_valid_dump_ifaddr_req
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81c020f2)
Location: include/net/netlink.h:787
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
```
```
In net/ipv6/route.c (ffffffff81c04cd9)
Location: include/net/netlink.h:787
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_valid_getroute_req
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
In net/core/net_namespace.c (ffffffff81c05899)
Location: include/net/netlink.h:787
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
```
```
In net/core/neighbour.c (ffffffff81c242c0)
Location: include/net/netlink.h:787
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_valid_dump_req
```
```
In net/core/rtnetlink.c (ffffffff81c2e1e6)
Location: include/net/netlink.h:787
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/ipv4/route.c (ffffffff81cce201)
Location: include/net/netlink.h:787
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_valid_getroute_req
```
```
In net/ipv4/devinet.c (ffffffff81d289ec)
Location: include/net/netlink.h:787
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
```
```
In net/ipv4/fib_frontend.c (ffffffff81d3427f)
Location: include/net/netlink.h:787
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
```
```
In net/ipv4/ipmr.c (ffffffff81d52d9b)
Location: include/net/netlink.h:787
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_valid_getroute_req
```
```
In net/ipv6/addrconf.c (ffffffff81d990ed)
Location: include/net/netlink.h:787
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81d9c08a)
Location: include/net/netlink.h:787
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
```
```
In net/ipv6/route.c (ffffffff81d9ea11)
Location: include/net/netlink.h:787
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_valid_getroute_req
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
In net/core/net_namespace.c (ffffffff81db5169)
Location: include/net/netlink.h:805
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
```
```
In net/core/neighbour.c (ffffffff81dd68f0)
Location: include/net/netlink.h:805
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_valid_dump_req
```
```
In net/core/rtnetlink.c (ffffffff81de1406)
Location: include/net/netlink.h:805
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/ipv4/route.c (ffffffff81e8e1d1)
Location: include/net/netlink.h:805
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_valid_getroute_req
```
```
In net/ipv4/devinet.c (ffffffff81ef043c)
Location: include/net/netlink.h:805
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
```
```
In net/ipv4/fib_frontend.c (ffffffff81efc74f)
Location: include/net/netlink.h:805
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
```
```
In net/ipv4/ipmr.c (ffffffff81f1d72b)
Location: include/net/netlink.h:805
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_valid_getroute_req
```
```
In net/ipv6/addrconf.c (ffffffff81f67e0d)
Location: include/net/netlink.h:805
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81f6ad5a)
Location: include/net/netlink.h:805
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
```
```
In net/ipv6/route.c (ffffffff81f6d9d1)
Location: include/net/netlink.h:805
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_valid_getroute_req
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
In net/core/net_namespace.c (ffffffff81e25739)
Location: include/net/netlink.h:806
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
```
```
In net/core/neighbour.c (ffffffff81e47720)
Location: include/net/netlink.h:806
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_valid_dump_req
```
```
In net/core/rtnetlink.c (ffffffff81e52af6)
Location: include/net/netlink.h:806
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/ipv4/route.c (ffffffff81eec911)
Location: include/net/netlink.h:806
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_valid_getroute_req
```
```
In net/ipv4/devinet.c (ffffffff81f4fe8c)
Location: include/net/netlink.h:806
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
```
```
In net/ipv4/fib_frontend.c (ffffffff81f5c17f)
Location: include/net/netlink.h:806
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
```
```
In net/ipv4/ipmr.c (ffffffff81f7d22b)
Location: include/net/netlink.h:806
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_valid_getroute_req
```
```
In net/ipv6/addrconf.c (ffffffff81fc7efd)
Location: include/net/netlink.h:806
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81fcad8a)
Location: include/net/netlink.h:806
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
```
```
In net/ipv6/route.c (ffffffff81fcdaa1)
Location: include/net/netlink.h:806
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_valid_getroute_req
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
In net/core/net_namespace.c (ffffffff81ee3699)
Location: include/net/netlink.h:813
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
```
```
In net/core/neighbour.c (ffffffff81f063d0)
Location: include/net/netlink.h:813
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_valid_dump_req
```
```
In net/core/rtnetlink.c (ffffffff81f11e06)
Location: include/net/netlink.h:813
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/ipv4/route.c (ffffffff81fb0971)
Location: include/net/netlink.h:813
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_valid_getroute_req
```
```
In net/ipv4/devinet.c (ffffffff8201603c)
Location: include/net/netlink.h:813
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
```
```
In net/ipv4/fib_frontend.c (ffffffff820226df)
Location: include/net/netlink.h:813
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
```
```
In net/ipv4/ipmr.c (ffffffff8204392b)
Location: include/net/netlink.h:813
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_valid_getroute_req
```
```
In net/ipv6/addrconf.c (ffffffff82095629)
Location: include/net/netlink.h:813
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff8209852a)
Location: include/net/netlink.h:813
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
```
```
In net/ipv6/route.c (ffffffff8209b2f1)
Location: include/net/netlink.h:813
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_valid_getroute_req
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
In net/core/net_namespace.c (ffff800010bc1c7c)
Location: include/net/netlink.h:721
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
```
```
In net/core/neighbour.c (ffff800010be2000)
Location: include/net/netlink.h:721
Inline: True
```
```
In net/core/rtnetlink.c (ffff800010bed7f4)
Location: include/net/netlink.h:721
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:valid_fdb_dump_strict
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/ipv4/route.c (ffff800010c5ca3c)
Location: include/net/netlink.h:721
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/devinet.c (ffff800010ca63a4)
Location: include/net/netlink.h:721
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
```
```
In net/ipv4/fib_frontend.c (ffff800010cb3b48)
Location: include/net/netlink.h:721
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
```
```
In net/ipv4/ipmr.c (ffff800010ccb118)
Location: include/net/netlink.h:721
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
```
```
In net/ipv6/addrconf.c (ffff800010d0821c)
Location: include/net/netlink.h:721
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/addrlabel.c (ffff800010d0b810)
Location: include/net/netlink.h:721
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
```
```
In net/ipv6/route.c (ffff800010d11344)
Location: include/net/netlink.h:721
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
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
In net/core/net_namespace.c (c0cdc84c)
Location: include/net/netlink.h:721
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_getid
```
```
In net/core/neighbour.c (c0d00194)
Location: include/net/netlink.h:721
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_dump_info
```
```
In net/core/rtnetlink.c (c0d05d68)
Location: include/net/netlink.h:721
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:rtnl_fdb_dump
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/ipv4/route.c (c0d6c104)
Location: include/net/netlink.h:721
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/devinet.c (c0db2e84)
Location: include/net/netlink.h:721
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_dump_ifaddr
```
```
In net/ipv4/fib_frontend.c (c0dbee2c)
Location: include/net/netlink.h:721
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
```
```
In net/ipv4/ipmr.c (c0dd6a54)
Location: include/net/netlink.h:721
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
```
```
In net/ipv6/addrconf.c (c0e0ea0c)
Location: include/net/netlink.h:721
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/addrlabel.c (c0e116f4)
Location: include/net/netlink.h:721
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
```
```
In net/ipv6/route.c (c0e156a8)
Location: include/net/netlink.h:721
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
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
In net/core/net_namespace.c (c000000000c9b43c)
Location: include/net/netlink.h:721
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
```
```
In net/core/neighbour.c (c000000000cc4658)
Location: include/net/netlink.h:721
Inline: True
```
```
In net/core/rtnetlink.c (c000000000cd02f0)
Location: include/net/netlink.h:721
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:valid_fdb_dump_strict
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/ipv4/route.c (c000000000d5ef8c)
Location: include/net/netlink.h:721
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/devinet.c (c000000000dbab64)
Location: include/net/netlink.h:721
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
```
```
In net/ipv4/fib_frontend.c (c000000000dcacb4)
Location: include/net/netlink.h:721
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
```
```
In net/ipv4/ipmr.c (c000000000dec280)
Location: include/net/netlink.h:721
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
```
```
In net/ipv6/addrconf.c (c000000000e32618)
Location: include/net/netlink.h:721
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/addrlabel.c (c000000000e35fcc)
Location: include/net/netlink.h:721
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
```
```
In net/ipv6/route.c (c000000000e3a728)
Location: include/net/netlink.h:721
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
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
In net/core/net_namespace.c (ffffffe00074ed06)
Location: include/net/netlink.h:721
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
```
```
In net/core/neighbour.c (ffffffe000768d18)
Location: include/net/netlink.h:721
Inline: True
```
```
In net/core/rtnetlink.c (ffffffe000770504)
Location: include/net/netlink.h:721
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:valid_fdb_dump_strict
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/ipv4/route.c (ffffffe0007c58c0)
Location: include/net/netlink.h:721
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/devinet.c (ffffffe000801be8)
Location: include/net/netlink.h:721
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
```
```
In net/ipv4/fib_frontend.c (ffffffe00080ba9a)
Location: include/net/netlink.h:721
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
```
```
In net/ipv4/ipmr.c (ffffffe000821332)
Location: include/net/netlink.h:721
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
```
```
In net/ipv6/addrconf.c (ffffffe000850360)
Location: include/net/netlink.h:721
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/addrlabel.c (ffffffe0008528c6)
Location: include/net/netlink.h:721
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
```
```
In net/ipv6/route.c (ffffffe000856046)
Location: include/net/netlink.h:721
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
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
In net/core/net_namespace.c (ffffffff818c58dd)
Location: include/net/netlink.h:721
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
```
```
In net/core/neighbour.c (ffffffff818e2811)
Location: include/net/netlink.h:721
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_valid_dump_req
```
```
In net/core/rtnetlink.c (ffffffff818ea87e)
Location: include/net/netlink.h:721
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:valid_fdb_dump_strict
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/ipv4/route.c (ffffffff8194c715)
Location: include/net/netlink.h:721
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/devinet.c (ffffffff819902f0)
Location: include/net/netlink.h:721
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
```
```
In net/ipv4/fib_frontend.c (ffffffff8199b8a2)
Location: include/net/netlink.h:721
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
```
```
In net/ipv4/ipmr.c (ffffffff819b1d53)
Location: include/net/netlink.h:721
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
```
```
In net/ipv6/addrconf.c (ffffffff819e4f2c)
Location: include/net/netlink.h:721
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff819e7b34)
Location: include/net/netlink.h:721
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
```
```
In net/ipv6/route.c (ffffffff819eb448)
Location: include/net/netlink.h:721
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
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
In net/core/net_namespace.c (ffffffff8187f81d)
Location: include/net/netlink.h:721
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
```
```
In net/core/neighbour.c (ffffffff8189c651)
Location: include/net/netlink.h:721
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_valid_dump_req
```
```
In net/core/rtnetlink.c (ffffffff818a46be)
Location: include/net/netlink.h:721
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:valid_fdb_dump_strict
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/ipv4/route.c (ffffffff81906205)
Location: include/net/netlink.h:721
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/devinet.c (ffffffff81949db0)
Location: include/net/netlink.h:721
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
```
```
In net/ipv4/fib_frontend.c (ffffffff81955362)
Location: include/net/netlink.h:721
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
```
```
In net/ipv4/ipmr.c (ffffffff8196e383)
Location: include/net/netlink.h:721
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
```
```
In net/ipv6/addrconf.c (ffffffff819a1cec)
Location: include/net/netlink.h:721
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff819a48f4)
Location: include/net/netlink.h:721
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
```
```
In net/ipv6/route.c (ffffffff819a8208)
Location: include/net/netlink.h:721
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
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
In net/core/net_namespace.c (ffffffff819168dd)
Location: include/net/netlink.h:721
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
```
```
In net/core/neighbour.c (ffffffff81933841)
Location: include/net/netlink.h:721
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_valid_dump_req
```
```
In net/core/rtnetlink.c (ffffffff8193b8ae)
Location: include/net/netlink.h:721
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:valid_fdb_dump_strict
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/ipv4/route.c (ffffffff819b6ee5)
Location: include/net/netlink.h:721
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/devinet.c (ffffffff819fab90)
Location: include/net/netlink.h:721
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
```
```
In net/ipv4/fib_frontend.c (ffffffff81a06142)
Location: include/net/netlink.h:721
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
```
```
In net/ipv4/ipmr.c (ffffffff81a1c5f3)
Location: include/net/netlink.h:721
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
```
```
In net/ipv6/addrconf.c (ffffffff81a4f9ac)
Location: include/net/netlink.h:721
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81a525b4)
Location: include/net/netlink.h:721
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
```
```
In net/ipv6/route.c (ffffffff81a55ec8)
Location: include/net/netlink.h:721
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
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
In net/core/net_namespace.c (ffffffff81937aed)
Location: include/net/netlink.h:721
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
```
```
In net/core/neighbour.c (ffffffff81955171)
Location: include/net/netlink.h:721
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_valid_dump_req
```
```
In net/core/rtnetlink.c (ffffffff8195d12e)
Location: include/net/netlink.h:721
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fdb_get
  - net/core/rtnetlink.c:valid_fdb_dump_strict
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/ipv4/route.c (ffffffff819c0765)
Location: include/net/netlink.h:721
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/devinet.c (ffffffff81a04ee0)
Location: include/net/netlink.h:721
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
```
```
In net/ipv4/fib_frontend.c (ffffffff81a107b2)
Location: include/net/netlink.h:721
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_valid_fib_dump_req
```
```
In net/ipv4/ipmr.c (ffffffff81a27548)
Location: include/net/netlink.h:721
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
```
```
In net/ipv6/addrconf.c (ffffffff81a5b98c)
Location: include/net/netlink.h:721
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/ipv6/addrlabel.c (ffffffff81a5e5b4)
Location: include/net/netlink.h:721
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_get
```
```
In net/ipv6/route.c (ffffffff81a61ef8)
Location: include/net/netlink.h:721
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
```
</details>
</li>
</ul>

## Differences
