# Function: <code>nla_put_s32</code>

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
In net/core/net_namespace.c (ffffffff8170fe08)
Location: include/net/netlink.h:911
Inline: True
```
```
In net/core/rtnetlink.c (ffffffff8172e990)
Location: include/net/netlink.h:911
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/ipv4/tcp_metrics.c (ffffffff81781265)
Location: include/net/netlink.h:911
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/devinet.c (ffffffff81790276)
Location: include/net/netlink.h:911
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff817cccb6)
Location: include/net/netlink.h:911
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
In net/core/net_namespace.c (ffffffff81777748)
Location: include/net/netlink.h:931
Inline: True
```
```
In net/core/rtnetlink.c (ffffffff817983c6)
Location: include/net/netlink.h:931
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/ipv4/tcp_metrics.c (ffffffff817ee72b)
Location: include/net/netlink.h:931
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/devinet.c (ffffffff817fd6c2)
Location: include/net/netlink.h:931
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81839702)
Location: include/net/netlink.h:931
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
In net/core/net_namespace.c (ffffffff817a47c8)
Location: include/net/netlink.h:931
Inline: True
```
```
In net/core/rtnetlink.c (ffffffff817c614a)
Location: include/net/netlink.h:931
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/ipv4/tcp_metrics.c (ffffffff8181f13b)
Location: include/net/netlink.h:931
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
```
```
In net/ipv4/devinet.c (ffffffff8182e622)
Location: include/net/netlink.h:931
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff8186b122)
Location: include/net/netlink.h:931
Inline: True
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
In net/core/net_namespace.c (ffffffff817c2908)
Location: include/net/netlink.h:943
Inline: True
```
```
In net/core/rtnetlink.c (ffffffff817e49ab)
Location: include/net/netlink.h:943
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/ipv4/devinet.c (ffffffff8184f241)
Location: include/net/netlink.h:943
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
```
```
In net/ipv4/ipmr.c (ffffffff8186aa88)
Location: include/net/netlink.h:943
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
```
```
In net/ipv6/addrconf.c (ffffffff8188f618)
Location: include/net/netlink.h:943
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
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
In net/core/net_namespace.c (ffffffff8183c248)
Location: include/net/netlink.h:980
Inline: True
```
```
In net/core/rtnetlink.c (ffffffff8185f1cc)
Location: include/net/netlink.h:980
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/ipv4/devinet.c (ffffffff818cee68)
Location: include/net/netlink.h:980
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
```
```
In net/ipv4/ipmr.c (ffffffff818eb20b)
Location: include/net/netlink.h:980
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
```
```
In net/ipv6/addrconf.c (ffffffff81910ef8)
Location: include/net/netlink.h:980
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
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
In net/core/net_namespace.c (ffffffff81886cac)
Location: include/net/netlink.h:980
Inline: True
```
```
In net/core/rtnetlink.c (ffffffff818ab325)
Location: include/net/netlink.h:980
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/ipv4/devinet.c (ffffffff81925c55)
Location: include/net/netlink.h:980
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
```
```
In net/ipv4/ipmr.c (ffffffff819419dc)
Location: include/net/netlink.h:980
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
```
```
In net/ipv6/addrconf.c (ffffffff81967dd9)
Location: include/net/netlink.h:980
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
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
In net/core/net_namespace.c (ffffffff818a73a0)
Location: include/net/netlink.h:1123
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/rtnetlink.c (ffffffff818cedb0)
Location: include/net/netlink.h:1123
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/ipv4/devinet.c (ffffffff81954bde)
Location: include/net/netlink.h:1123
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/ipmr.c (ffffffff81971288)
Location: include/net/netlink.h:1123
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
```
```
In net/ipv6/addrconf.c (ffffffff8199d2c6)
Location: include/net/netlink.h:1123
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
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
In net/core/net_namespace.c (ffffffff818f2440)
Location: include/net/netlink.h:1381
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/rtnetlink.c (ffffffff8191bb65)
Location: include/net/netlink.h:1381
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/ipv4/devinet.c (ffffffff819b8b4e)
Location: include/net/netlink.h:1381
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/ipmr.c (ffffffff819daa10)
Location: include/net/netlink.h:1381
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
```
```
In net/ipv6/addrconf.c (ffffffff81a094bd)
Location: include/net/netlink.h:1381
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
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
In net/core/net_namespace.c (ffffffff81924390)
Location: include/net/netlink.h:1381
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/rtnetlink.c (ffffffff8194e18c)
Location: include/net/netlink.h:1381
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/ipv4/devinet.c (ffffffff819ef84e)
Location: include/net/netlink.h:1381
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/ipmr.c (ffffffff81a118c2)
Location: include/net/netlink.h:1381
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
```
```
In net/ipv6/addrconf.c (ffffffff81a401ad)
Location: include/net/netlink.h:1381
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
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
In net/core/net_namespace.c (ffffffff819f8060)
Location: include/net/netlink.h:1433
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/rtnetlink.c (ffffffff81a1fd13)
Location: include/net/netlink.h:1433
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/ipv4/devinet.c (ffffffff81addc8e)
Location: include/net/netlink.h:1433
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/ipmr.c (ffffffff81b001bc)
Location: include/net/netlink.h:1433
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_fill_table
```
```
In net/ipv6/addrconf.c (ffffffff81b343fa)
Location: include/net/netlink.h:1433
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
  - net/ipv6/addrconf.c:inet6_fill_ifmcaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
```
```
In net/mptcp/pm_netlink.c (ffffffff81bb308e)
Location: include/net/netlink.h:1433
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_fill_addr
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
In net/core/net_namespace.c (ffffffff819f7ac0)
Location: include/net/netlink.h:1446
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/rtnetlink.c (ffffffff81a20673)
Location: include/net/netlink.h:1446
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/ipv4/devinet.c (ffffffff81aeaa6e)
Location: include/net/netlink.h:1446
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/ipmr.c (ffffffff81b0e1fc)
Location: include/net/netlink.h:1446
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_fill_table
```
```
In net/ipv6/addrconf.c (ffffffff81b44c4a)
Location: include/net/netlink.h:1446
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
  - net/ipv6/addrconf.c:inet6_fill_ifmcaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
```
```
In net/mptcp/pm_netlink.c (ffffffff81bc751f)
Location: include/net/netlink.h:1446
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_fill_addr
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
In net/core/net_namespace.c (ffffffff819ddc40)
Location: include/net/netlink.h:1446
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/rtnetlink.c (ffffffff81a07743)
Location: include/net/netlink.h:1446
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/ipv4/devinet.c (ffffffff81ad61ae)
Location: include/net/netlink.h:1446
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/ipmr.c (ffffffff81b00a1a)
Location: include/net/netlink.h:1446
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
```
```
In net/ipv6/addrconf.c (ffffffff81b32f06)
Location: include/net/netlink.h:1446
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
```
```
In net/mptcp/pm_netlink.c (ffffffff81bb83da)
Location: include/net/netlink.h:1446
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_event_put_token_and_ssk
  - net/mptcp/pm_netlink.c:mptcp_nl_fill_addr
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
In net/core/net_namespace.c (ffffffff81a8dec2)
Location: include/net/netlink.h:1446
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/rtnetlink.c (ffffffff81ab9ba7)
Location: include/net/netlink.h:1446
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/ipv4/devinet.c (ffffffff81b94ede)
Location: include/net/netlink.h:1446
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/ipmr.c (ffffffff81bbd9bc)
Location: include/net/netlink.h:1446
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_fill_table
```
```
In net/ipv6/addrconf.c (ffffffff81bf91a6)
Location: include/net/netlink.h:1446
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
```
```
In net/mptcp/pm_netlink.c (ffffffff81c87a6a)
Location: include/net/netlink.h:1446
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_event_put_token_and_ssk
  - net/mptcp/pm_netlink.c:mptcp_nl_fill_addr
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
In net/core/net_namespace.c (ffffffff81c03b53)
Location: include/net/netlink.h:1446
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/rtnetlink.c (ffffffff81c340c1)
Location: include/net/netlink.h:1446
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/ipv4/devinet.c (ffffffff81d26b74)
Location: include/net/netlink.h:1446
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/ipmr.c (ffffffff81d52288)
Location: include/net/netlink.h:1446
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_fill_table
```
```
In net/ipv6/addrconf.c (ffffffff81d92598)
Location: include/net/netlink.h:1446
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
```
```
In net/mptcp/pm_netlink.c (ffffffff81e2e286)
Location: include/net/netlink.h:1446
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_event_put_token_and_ssk
  - net/mptcp/pm_netlink.c:mptcp_nl_fill_addr
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
In net/core/net_namespace.c (ffffffff81db3203)
Location: include/net/netlink.h:1495
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/rtnetlink.c (ffffffff81de7541)
Location: include/net/netlink.h:1495
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/ipv4/devinet.c (ffffffff81eee514)
Location: include/net/netlink.h:1495
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/ipmr.c (ffffffff81f1c2e8)
Location: include/net/netlink.h:1495
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_fill_table
```
```
In net/ipv6/addrconf.c (ffffffff81f60cc8)
Location: include/net/netlink.h:1495
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
```
```
In net/mptcp/pm_netlink.c (ffffffff82007306)
Location: include/net/netlink.h:1495
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_event_put_token_and_ssk
  - net/mptcp/pm_netlink.c:mptcp_nl_fill_addr
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
In net/core/net_namespace.c (ffffffff81e237d3)
Location: include/net/netlink.h:1496
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/rtnetlink.c (ffffffff81e58f7a)
Location: include/net/netlink.h:1496
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/ipv4/devinet.c (ffffffff81f4dea8)
Location: include/net/netlink.h:1496
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/ipmr.c (ffffffff81f7bdc8)
Location: include/net/netlink.h:1496
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_fill_table
```
```
In net/ipv6/addrconf.c (ffffffff81fc0b45)
Location: include/net/netlink.h:1496
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
```
```
In net/mptcp/pm_netlink.c (ffffffff820836a6)
Location: include/net/netlink.h:1496
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_event_put_token_and_ssk
  - net/mptcp/pm_netlink.c:mptcp_nl_fill_addr
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
In drivers/dpll/dpll_netlink.c (ffffffff81eb9b37)
Location: include/net/netlink.h:1556
Inline: True
Inline callers:
  - drivers/dpll/dpll_netlink.c:dpll_cmd_pin_get_one
  - drivers/dpll/dpll_netlink.c:dpll_cmd_pin_get_one
  - drivers/dpll/dpll_netlink.c:dpll_cmd_pin_get_one
  - drivers/dpll/dpll_netlink.c:dpll_cmd_pin_get_one
```
```
In net/core/net_namespace.c (ffffffff81ee1733)
Location: include/net/netlink.h:1556
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/rtnetlink.c (ffffffff81f1829a)
Location: include/net/netlink.h:1556
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/ipv4/devinet.c (ffffffff82013fd8)
Location: include/net/netlink.h:1556
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/ipmr.c (ffffffff820424b8)
Location: include/net/netlink.h:1556
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_fill_table
```
```
In net/ipv6/addrconf.c (ffffffff8208e005)
Location: include/net/netlink.h:1556
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
```
```
In net/devlink/netlink.c (ffffffff8210172b)
Location: include/net/netlink.h:1556
Inline: True
Inline callers:
  - net/devlink/netlink.c:devlink_nl_put_nested_handle
```
```
In net/mptcp/pm_netlink.c (ffffffff82158e36)
Location: include/net/netlink.h:1556
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_event_put_token_and_ssk
  - net/mptcp/pm_netlink.c:mptcp_nl_fill_addr
```
```
In net/handshake/tlshd.c (ffffffff8216a7d7)
Location: include/net/netlink.h:1556
Inline: True
Inline callers:
  - net/handshake/tlshd.c:tls_handshake_accept
  - net/handshake/tlshd.c:tls_handshake_accept
  - net/handshake/tlshd.c:tls_handshake_accept
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
In net/core/net_namespace.c (ffff800010bbfcfc)
Location: include/net/netlink.h:1381
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/rtnetlink.c (ffff800010bf0118)
Location: include/net/netlink.h:1381
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/ipv4/devinet.c (ffff800010ca56cc)
Location: include/net/netlink.h:1381
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/ipmr.c (ffff800010cc9f9c)
Location: include/net/netlink.h:1381
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
```
```
In net/ipv6/addrconf.c (ffff800010d01458)
Location: include/net/netlink.h:1381
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
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
In net/core/net_namespace.c (c0cdb7d8)
Location: include/net/netlink.h:1381
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/rtnetlink.c (c0d0872c)
Location: include/net/netlink.h:1381
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/ipv4/devinet.c (c0db2024)
Location: include/net/netlink.h:1381
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/ipmr.c (c0dd5f40)
Location: include/net/netlink.h:1381
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
```
```
In net/ipv6/addrconf.c (c0e08fa4)
Location: include/net/netlink.h:1381
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
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
In net/core/net_namespace.c (c000000000c99128)
Location: include/net/netlink.h:1381
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/rtnetlink.c (c000000000cd4618)
Location: include/net/netlink.h:1381
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/ipv4/devinet.c (c000000000db9578)
Location: include/net/netlink.h:1381
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/ipmr.c (c000000000de9430)
Location: include/net/netlink.h:1381
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
```
```
In net/ipv6/addrconf.c (c000000000e2b408)
Location: include/net/netlink.h:1381
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
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
In net/core/net_namespace.c (ffffffe00074d5be)
Location: include/net/netlink.h:1381
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/rtnetlink.c (ffffffe00077229a)
Location: include/net/netlink.h:1381
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/ipv4/devinet.c (ffffffe000800f80)
Location: include/net/netlink.h:1381
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/ipmr.c (ffffffe00081f47a)
Location: include/net/netlink.h:1381
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
```
```
In net/ipv6/addrconf.c (ffffffe00084b33e)
Location: include/net/netlink.h:1381
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
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
In net/core/net_namespace.c (ffffffff818c4390)
Location: include/net/netlink.h:1381
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/rtnetlink.c (ffffffff818ee15c)
Location: include/net/netlink.h:1381
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/ipv4/devinet.c (ffffffff8198f5ee)
Location: include/net/netlink.h:1381
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/ipmr.c (ffffffff819b1218)
Location: include/net/netlink.h:1381
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
```
```
In net/ipv6/addrconf.c (ffffffff819df83d)
Location: include/net/netlink.h:1381
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
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
In drivers/net/vxlan.c (ffffffff8176cdf1)
Location: include/net/netlink.h:1381
Inline: True
Inline callers:
  - drivers/net/vxlan.c:vxlan_fdb_info
```
```
In net/core/net_namespace.c (ffffffff8187e2d0)
Location: include/net/netlink.h:1381
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/rtnetlink.c (ffffffff818a7f9c)
Location: include/net/netlink.h:1381
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/ipv4/devinet.c (ffffffff819490ae)
Location: include/net/netlink.h:1381
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/ipmr.c (ffffffff8196d848)
Location: include/net/netlink.h:1381
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
```
```
In net/ipv6/addrconf.c (ffffffff8199c5fd)
Location: include/net/netlink.h:1381
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
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
In net/core/net_namespace.c (ffffffff81915390)
Location: include/net/netlink.h:1381
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/rtnetlink.c (ffffffff8193f18c)
Location: include/net/netlink.h:1381
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/ipv4/devinet.c (ffffffff819f9e8e)
Location: include/net/netlink.h:1381
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/ipmr.c (ffffffff81a1bab8)
Location: include/net/netlink.h:1381
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
```
```
In net/ipv6/addrconf.c (ffffffff81a4a2bd)
Location: include/net/netlink.h:1381
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
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
In net/core/net_namespace.c (ffffffff81936570)
Location: include/net/netlink.h:1381
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_fill
  - net/core/net_namespace.c:rtnl_net_fill
```
```
In net/core/rtnetlink.c (ffffffff81960a5c)
Location: include/net/netlink.h:1381
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/ipv4/devinet.c (ffffffff81a0419e)
Location: include/net/netlink.h:1381
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_netconf_fill_devconf
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/ipmr.c (ffffffff81a269d2)
Location: include/net/netlink.h:1381
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
```
```
In net/ipv6/addrconf.c (ffffffff81a561fd)
Location: include/net/netlink.h:1381
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:in6_dump_addrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
  - net/ipv6/addrconf.c:inet6_netconf_fill_devconf
```
</details>
</li>
</ul>

## Differences
