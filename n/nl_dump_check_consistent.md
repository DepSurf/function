# Function: <code>nl_dump_check_consistent</code>

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
In net/core/rtnetlink.c (ffffffff8172f0f1)
Location: include/net/netlink.h:617
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/netlink/af_netlink.c (ffffffff8174c39d)
Location: include/net/netlink.h:617
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/ipv4/devinet.c (ffffffff817906c0)
Location: include/net/netlink.h:617
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_dump_ifaddr
```
```
In net/ipv6/addrconf.c (ffffffff817cca05)
Location: include/net/netlink.h:617
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
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
In net/core/rtnetlink.c (ffffffff8179690a)
Location: include/net/netlink.h:628
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_dump
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/netlink/af_netlink.c (ffffffff817b80d9)
Location: include/net/netlink.h:628
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/ipv4/devinet.c (ffffffff817fdb50)
Location: include/net/netlink.h:628
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_dump_ifaddr
```
```
In net/ipv6/addrconf.c (ffffffff8183953e)
Location: include/net/netlink.h:628
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
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
In net/core/rtnetlink.c (ffffffff817c4f78)
Location: include/net/netlink.h:628
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_dump
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/netlink/af_netlink.c (ffffffff817e7bb9)
Location: include/net/netlink.h:628
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/ipv4/devinet.c (ffffffff8182eab0)
Location: include/net/netlink.h:628
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_dump_ifaddr
```
```
In net/ipv6/addrconf.c (ffffffff8186af5e)
Location: include/net/netlink.h:628
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
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
In net/core/rtnetlink.c (ffffffff817e39e4)
Location: include/net/netlink.h:637
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_dump
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/netlink/af_netlink.c (ffffffff818078b7)
Location: include/net/netlink.h:637
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/ipv4/devinet.c (ffffffff8184f5a5)
Location: include/net/netlink.h:637
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_dump_ifaddr
```
```
In net/ipv6/addrconf.c (ffffffff8188f36e)
Location: include/net/netlink.h:637
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
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
In net/core/rtnetlink.c (ffffffff8185e924)
Location: include/net/netlink.h:643
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_dump
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/netlink/af_netlink.c (ffffffff81886425)
Location: include/net/netlink.h:643
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/ipv4/devinet.c (ffffffff818cf1d5)
Location: include/net/netlink.h:643
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_dump_ifaddr
```
```
In net/ipv6/addrconf.c (ffffffff819109be)
Location: include/net/netlink.h:643
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
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
In net/core/rtnetlink.c (ffffffff818aa4bd)
Location: include/net/netlink.h:643
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_dump
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/netlink/af_netlink.c (ffffffff818d9cb8)
Location: include/net/netlink.h:643
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/ipv4/devinet.c (ffffffff81925ed6)
Location: include/net/netlink.h:643
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:inet_dump_ifaddr
```
```
In net/ipv6/addrconf.c (ffffffff819684b5)
Location: include/net/netlink.h:643
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
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
In net/core/rtnetlink.c (ffffffff818cebc1)
Location: include/net/netlink.h:786
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_dump
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/netlink/af_netlink.c (ffffffff81906777)
Location: include/net/netlink.h:786
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/ipv4/devinet.c (ffffffff81954ebf)
Location: include/net/netlink.h:786
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
```
```
In net/ipv6/addrconf.c (ffffffff8199d44e)
Location: include/net/netlink.h:786
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
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
In net/core/rtnetlink.c (ffffffff8191b9bd)
Location: include/net/netlink.h:1020
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_dump
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/netlink/af_netlink.c (ffffffff81967a20)
Location: include/net/netlink.h:1020
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/ipv4/devinet.c (ffffffff819b8e2e)
Location: include/net/netlink.h:1020
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
```
```
In net/ipv4/nexthop.c (ffffffff819d48c9)
Location: include/net/netlink.h:1020
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
```
```
In net/ipv6/addrconf.c (ffffffff81a09616)
Location: include/net/netlink.h:1020
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
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
In net/core/rtnetlink.c (ffffffff8194dfea)
Location: include/net/netlink.h:1020
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_dump
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/netlink/af_netlink.c (ffffffff8199e4b0)
Location: include/net/netlink.h:1020
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/ipv4/devinet.c (ffffffff819efb3b)
Location: include/net/netlink.h:1020
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
```
```
In net/ipv4/nexthop.c (ffffffff81a0b439)
Location: include/net/netlink.h:1020
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
```
```
In net/ipv6/addrconf.c (ffffffff81a40306)
Location: include/net/netlink.h:1020
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
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
In net/core/rtnetlink.c (ffffffff81a1fb72)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_dump
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/netlink/af_netlink.c (ffffffff81a78080)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/ethtool/netlink.c (ffffffff81a85d46)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_dumpit
```
```
In net/ipv4/devinet.c (ffffffff81addf7b)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
```
```
In net/ipv4/nexthop.c (ffffffff81afbe02)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
```
```
In net/ipv6/addrconf.c (ffffffff81b35f1a)
Location: include/net/netlink.h:1072
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
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
In net/core/rtnetlink.c (ffffffff81a1f5d2)
Location: include/net/netlink.h:1085
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_dump
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/netlink/af_netlink.c (ffffffff81a804e7)
Location: include/net/netlink.h:1085
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump_done
```
```
In net/ethtool/netlink.c (ffffffff81a8f6d6)
Location: include/net/netlink.h:1085
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_dumpit
```
```
In net/ethtool/tunnels.c (ffffffff81a977f5)
Location: include/net/netlink.h:1085
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
```
```
In net/ipv4/devinet.c (ffffffff81aead5b)
Location: include/net/netlink.h:1085
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
```
```
In net/ipv4/nexthop.c (ffffffff81b09692)
Location: include/net/netlink.h:1085
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
```
```
In net/ipv6/addrconf.c (ffffffff81b453fa)
Location: include/net/netlink.h:1085
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
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
In net/core/rtnetlink.c (ffffffff81a06688)
Location: include/net/netlink.h:1085
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_dump
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/netlink/af_netlink.c (ffffffff81a69438)
Location: include/net/netlink.h:1085
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump_done
```
```
In net/ethtool/netlink.c (ffffffff81a78dbf)
Location: include/net/netlink.h:1085
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_dumpit
```
```
In net/ethtool/tunnels.c (ffffffff81a81255)
Location: include/net/netlink.h:1085
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
```
```
In net/ipv4/devinet.c (ffffffff81ad649e)
Location: include/net/netlink.h:1085
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
```
```
In net/ipv4/nexthop.c (ffffffff81af8c57)
Location: include/net/netlink.h:1085
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop_bucket
  - net/ipv4/nexthop.c:rtm_dump_nexthop
```
```
In net/ipv6/addrconf.c (ffffffff81b330c3)
Location: include/net/netlink.h:1085
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
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
In net/core/rtnetlink.c (ffffffff81ab8977)
Location: include/net/netlink.h:1085
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_dump
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/netlink/af_netlink.c (ffffffff81b229e8)
Location: include/net/netlink.h:1085
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump_done
```
```
In net/ethtool/netlink.c (ffffffff81b32f8f)
Location: include/net/netlink.h:1085
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_dumpit
```
```
In net/ethtool/tunnels.c (ffffffff81b3afa5)
Location: include/net/netlink.h:1085
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
```
```
In net/ipv4/devinet.c (ffffffff81b951dc)
Location: include/net/netlink.h:1085
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
```
```
In net/ipv4/nexthop.c (ffffffff81bb7330)
Location: include/net/netlink.h:1085
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop_bucket
  - net/ipv4/nexthop.c:rtm_dump_nexthop
```
```
In net/ipv6/addrconf.c (ffffffff81bf9363)
Location: include/net/netlink.h:1085
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
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
In net/core/rtnetlink.c (ffffffff81c339c4)
Location: include/net/netlink.h:1085
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_dump
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/netlink/af_netlink.c (ffffffff81cab59e)
Location: include/net/netlink.h:1085
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump_done
```
```
In net/ethtool/netlink.c (ffffffff81cbeb24)
Location: include/net/netlink.h:1085
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_dumpit
```
```
In net/ethtool/tunnels.c (ffffffff81cc6f45)
Location: include/net/netlink.h:1085
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
```
```
In net/ipv4/devinet.c (ffffffff81d26e4c)
Location: include/net/netlink.h:1085
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
```
```
In net/ipv4/nexthop.c (ffffffff81d4b028)
Location: include/net/netlink.h:1085
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop_bucket
  - net/ipv4/nexthop.c:rtm_dump_nexthop
```
```
In net/ipv6/addrconf.c (ffffffff81d92759)
Location: include/net/netlink.h:1085
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
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
In net/core/rtnetlink.c (ffffffff81de6e04)
Location: include/net/netlink.h:1134
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_dump
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/netlink/af_netlink.c (ffffffff81e6838e)
Location: include/net/netlink.h:1134
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump_done
```
```
In net/ethtool/netlink.c (ffffffff81e7d644)
Location: include/net/netlink.h:1134
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_dumpit
```
```
In net/ethtool/tunnels.c (ffffffff81e86595)
Location: include/net/netlink.h:1134
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
```
```
In net/ipv4/devinet.c (ffffffff81eee7fc)
Location: include/net/netlink.h:1134
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
```
```
In net/ipv4/nexthop.c (ffffffff81f14738)
Location: include/net/netlink.h:1134
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop_bucket
  - net/ipv4/nexthop.c:rtm_dump_nexthop
```
```
In net/ipv6/addrconf.c (ffffffff81f60e89)
Location: include/net/netlink.h:1134
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
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
In net/core/rtnetlink.c (ffffffff81e57df4)
Location: include/net/netlink.h:1135
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_dump
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/netlink/af_netlink.c (ffffffff81ec41fe)
Location: include/net/netlink.h:1135
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump_done
```
```
In net/ethtool/netlink.c (ffffffff81ed9c04)
Location: include/net/netlink.h:1135
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_dumpit
```
```
In net/ethtool/tunnels.c (ffffffff81ee2f77)
Location: include/net/netlink.h:1135
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
```
```
In net/ipv4/devinet.c (ffffffff81f4e1bc)
Location: include/net/netlink.h:1135
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
```
```
In net/ipv4/nexthop.c (ffffffff81f74413)
Location: include/net/netlink.h:1135
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop_bucket
  - net/ipv4/nexthop.c:rtm_dump_nexthop
```
```
In net/ipv6/addrconf.c (ffffffff81fc0d0a)
Location: include/net/netlink.h:1135
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
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
In net/core/rtnetlink.c (ffffffff81f17144)
Location: include/net/netlink.h:1179
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_dump
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/netlink/af_netlink.c (ffffffff81f875be)
Location: include/net/netlink.h:1179
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump_done
```
```
In net/ipv4/devinet.c (ffffffff820142f4)
Location: include/net/netlink.h:1179
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
```
```
In net/ipv4/nexthop.c (ffffffff8203abb4)
Location: include/net/netlink.h:1179
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop_bucket
  - net/ipv4/nexthop.c:rtm_dump_nexthop
```
```
In net/ipv6/addrconf.c (ffffffff8208e1cc)
Location: include/net/netlink.h:1179
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
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
In net/core/rtnetlink.c (ffff800010beff34)
Location: include/net/netlink.h:1020
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_dump
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/netlink/af_netlink.c (ffff800010c4baa8)
Location: include/net/netlink.h:1020
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/ipv4/devinet.c (ffff800010ca596c)
Location: include/net/netlink.h:1020
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
```
```
In net/ipv4/nexthop.c (ffff800010cc4984)
Location: include/net/netlink.h:1020
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
```
```
In net/ipv6/addrconf.c (ffff800010d015c0)
Location: include/net/netlink.h:1020
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
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
In net/core/rtnetlink.c (c0d08580)
Location: include/net/netlink.h:1020
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_dump
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/netlink/af_netlink.c (c0d5c378)
Location: include/net/netlink.h:1020
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/ipv4/devinet.c (c0db22ec)
Location: include/net/netlink.h:1020
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:in_dev_dump_addr
```
```
In net/ipv4/nexthop.c (c0dd0440)
Location: include/net/netlink.h:1020
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
```
```
In net/ipv6/addrconf.c (c0e090d4)
Location: include/net/netlink.h:1020
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
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
In net/core/rtnetlink.c (c000000000cd432c)
Location: include/net/netlink.h:1020
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_dump
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/netlink/af_netlink.c (c000000000d49c2c)
Location: include/net/netlink.h:1020
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/ipv4/devinet.c (c000000000db9950)
Location: include/net/netlink.h:1020
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:in_dev_dump_addr
```
```
In net/ipv4/nexthop.c (c000000000de0a8c)
Location: include/net/netlink.h:1020
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
```
```
In net/ipv6/addrconf.c (c000000000e2b564)
Location: include/net/netlink.h:1020
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
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
In net/core/rtnetlink.c (ffffffe00077212e)
Location: include/net/netlink.h:1020
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_dump
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/netlink/af_netlink.c (ffffffe0007b8fc2)
Location: include/net/netlink.h:1020
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/ipv4/devinet.c (ffffffe000801226)
Location: include/net/netlink.h:1020
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
  - net/ipv4/devinet.c:in_dev_dump_addr
```
```
In net/ipv4/nexthop.c (ffffffe000819d60)
Location: include/net/netlink.h:1020
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
```
```
In net/ipv6/addrconf.c (ffffffe00084b3fa)
Location: include/net/netlink.h:1020
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
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
In net/core/rtnetlink.c (ffffffff818edfba)
Location: include/net/netlink.h:1020
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_dump
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/netlink/af_netlink.c (ffffffff8193e320)
Location: include/net/netlink.h:1020
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/ipv4/devinet.c (ffffffff8198f8db)
Location: include/net/netlink.h:1020
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
```
```
In net/ipv4/nexthop.c (ffffffff819ab1d9)
Location: include/net/netlink.h:1020
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
```
```
In net/ipv6/addrconf.c (ffffffff819df996)
Location: include/net/netlink.h:1020
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
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
In net/core/rtnetlink.c (ffffffff818a7dfa)
Location: include/net/netlink.h:1020
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_dump
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/netlink/af_netlink.c (ffffffff818f7e20)
Location: include/net/netlink.h:1020
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/ipv4/devinet.c (ffffffff8194939b)
Location: include/net/netlink.h:1020
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
```
```
In net/ipv4/nexthop.c (ffffffff81964c99)
Location: include/net/netlink.h:1020
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
```
```
In net/ipv6/addrconf.c (ffffffff8199c756)
Location: include/net/netlink.h:1020
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
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
In net/core/rtnetlink.c (ffffffff8193efea)
Location: include/net/netlink.h:1020
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_dump
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/netlink/af_netlink.c (ffffffff8198f4b0)
Location: include/net/netlink.h:1020
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/ipv4/devinet.c (ffffffff819fa17b)
Location: include/net/netlink.h:1020
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
```
```
In net/ipv4/nexthop.c (ffffffff81a15a79)
Location: include/net/netlink.h:1020
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
```
```
In net/ipv6/addrconf.c (ffffffff81a4a416)
Location: include/net/netlink.h:1020
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
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
In net/core/rtnetlink.c (ffffffff819608ba)
Location: include/net/netlink.h:1020
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_dump
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/netlink/af_netlink.c (ffffffff819b1d90)
Location: include/net/netlink.h:1020
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_dump
```
```
In net/ipv4/devinet.c (ffffffff81a04493)
Location: include/net/netlink.h:1020
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_dump_devconf
```
```
In net/ipv4/nexthop.c (ffffffff81a204b9)
Location: include/net/netlink.h:1020
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
```
```
In net/ipv6/addrconf.c (ffffffff81a56356)
Location: include/net/netlink.h:1020
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_netconf_dump_devconf
```
</details>
</li>
</ul>

## Differences
