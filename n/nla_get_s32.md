# Function: <code>nla_get_s32</code>

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
In net/core/net_namespace.c (ffffffff817100d4)
Location: include/net/netlink.h:1090
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/rtnetlink.c (0)
Location: include/net/netlink.h:1090
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff817904f1)
Location: include/net/netlink.h:1090
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
```
```
In net/ipv6/addrconf.c (ffffffff817ccee1)
Location: include/net/netlink.h:1090
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
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
In drivers/net/ppp/ppp_generic.c (ffffffff81656239)
Location: include/net/netlink.h:1114
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_nl_newlink
```
```
In net/core/net_namespace.c (ffffffff81777a1b)
Location: include/net/netlink.h:1114
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/rtnetlink.c (0)
Location: include/net/netlink.h:1114
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff817fd971)
Location: include/net/netlink.h:1114
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
```
```
In net/ipv6/addrconf.c (ffffffff81839971)
Location: include/net/netlink.h:1114
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
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
In drivers/net/ppp/ppp_generic.c (ffffffff81683f1e)
Location: include/net/netlink.h:1114
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_nl_newlink
```
```
In net/core/net_namespace.c (ffffffff817a49f7)
Location: include/net/netlink.h:1114
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/rtnetlink.c (0)
Location: include/net/netlink.h:1114
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff8182e8d1)
Location: include/net/netlink.h:1114
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
```
```
In net/ipv6/addrconf.c (ffffffff8186b391)
Location: include/net/netlink.h:1114
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
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
In drivers/net/ppp/ppp_generic.c (ffffffff8169950e)
Location: include/net/netlink.h:1126
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_nl_newlink
```
```
In net/core/net_namespace.c (ffffffff817c2aff)
Location: include/net/netlink.h:1126
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/rtnetlink.c (0)
Location: include/net/netlink.h:1126
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff8184f9f2)
Location: include/net/netlink.h:1126
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
```
```
In net/ipv6/addrconf.c (ffffffff8188fa02)
Location: include/net/netlink.h:1126
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
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
In drivers/net/ppp/ppp_generic.c (ffffffff8170635e)
Location: include/net/netlink.h:1169
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_nl_newlink
```
```
In net/core/net_namespace.c (ffffffff8183c88f)
Location: include/net/netlink.h:1169
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/rtnetlink.c (ffffffff818600af)
Location: include/net/netlink.h:1169
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/ipv4/devinet.c (ffffffff818cf622)
Location: include/net/netlink.h:1169
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
```
```
In net/ipv6/addrconf.c (ffffffff819112e6)
Location: include/net/netlink.h:1169
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
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
In drivers/net/ppp/ppp_generic.c (ffffffff817440ed)
Location: include/net/netlink.h:1169
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_nl_newlink
  - drivers/net/ppp/ppp_generic.c:ppp_nl_validate
```
```
In net/core/net_namespace.c (ffffffff8188733b)
Location: include/net/netlink.h:1169
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/rtnetlink.c (ffffffff818ac1a7)
Location: include/net/netlink.h:1169
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/ipv4/devinet.c (ffffffff81926062)
Location: include/net/netlink.h:1169
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
```
```
In net/ipv6/addrconf.c (ffffffff819681a6)
Location: include/net/netlink.h:1169
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
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
In lib/nlattr.c (ffffffff8150686c)
Location: include/net/netlink.h:1312
Inline: True
Inline callers:
  - lib/nlattr.c:validate_nla
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81766c9d)
Location: include/net/netlink.h:1312
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_nl_newlink
  - drivers/net/ppp/ppp_generic.c:ppp_nl_validate
```
```
In net/core/net_namespace.c (ffffffff818a8425)
Location: include/net/netlink.h:1312
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/rtnetlink.c (ffffffff818d022c)
Location: include/net/netlink.h:1312
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/ipv4/devinet.c (ffffffff81955082)
Location: include/net/netlink.h:1312
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
```
```
In net/ipv6/addrconf.c (ffffffff819a25d0)
Location: include/net/netlink.h:1312
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
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
In lib/nlattr.c (ffffffff815347e6)
Location: include/net/netlink.h:1570
Inline: True
Inline callers:
  - lib/nlattr.c:validate_nla
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817a5aed)
Location: include/net/netlink.h:1570
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_nl_newlink
  - drivers/net/ppp/ppp_generic.c:ppp_nl_validate
```
```
In net/core/net_namespace.c (ffffffff818f3a09)
Location: include/net/netlink.h:1570
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/rtnetlink.c (ffffffff8191d099)
Location: include/net/netlink.h:1570
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/ipv4/devinet.c (ffffffff819b991b)
Location: include/net/netlink.h:1570
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
```
```
In net/ipv6/addrconf.c (ffffffff81a0ec37)
Location: include/net/netlink.h:1570
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
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
In lib/nlattr.c (ffffffff81555642)
Location: include/net/netlink.h:1570
Inline: True
Inline callers:
  - lib/nlattr.c:validate_nla
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817c814d)
Location: include/net/netlink.h:1570
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_nl_newlink
  - drivers/net/ppp/ppp_generic.c:ppp_nl_validate
```
```
In net/core/net_namespace.c (ffffffff819259b9)
Location: include/net/netlink.h:1570
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/rtnetlink.c (ffffffff8194f6cd)
Location: include/net/netlink.h:1570
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/ipv4/devinet.c (ffffffff819f060e)
Location: include/net/netlink.h:1570
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
```
```
In net/ipv6/addrconf.c (ffffffff81a45979)
Location: include/net/netlink.h:1570
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
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
In lib/nlattr.c (ffffffff815dec7d)
Location: include/net/netlink.h:1637
Inline: True
Inline callers:
  - lib/nlattr.c:nla_validate_int_range
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81891bd4)
Location: include/net/netlink.h:1637
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_nl_newlink
  - drivers/net/ppp/ppp_generic.c:ppp_nl_validate
```
```
In net/core/net_namespace.c (ffffffff819f9b56)
Location: include/net/netlink.h:1637
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/rtnetlink.c (ffffffff81a20e93)
Location: include/net/netlink.h:1637
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/ipv4/devinet.c (ffffffff81ade57c)
Location: include/net/netlink.h:1637
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
```
```
In net/ipv6/addrconf.c (ffffffff81b3c70c)
Location: include/net/netlink.h:1637
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/mptcp/pm_netlink.c (ffffffff81bb31f1)
Location: include/net/netlink.h:1637
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_parse_addr
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
In lib/nlattr.c (ffffffff815fc3c1)
Location: include/net/netlink.h:1650
Inline: True
Inline callers:
  - lib/nlattr.c:nla_validate_int_range
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8189fea4)
Location: include/net/netlink.h:1650
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_nl_newlink
  - drivers/net/ppp/ppp_generic.c:ppp_nl_validate
```
```
In net/core/net_namespace.c (ffffffff819f96a6)
Location: include/net/netlink.h:1650
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/rtnetlink.c (ffffffff81a218f3)
Location: include/net/netlink.h:1650
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/ipv4/devinet.c (ffffffff81aeb35c)
Location: include/net/netlink.h:1650
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
```
```
In net/ipv6/addrconf.c (ffffffff81b4b41c)
Location: include/net/netlink.h:1650
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/mptcp/pm_netlink.c (ffffffff81bc7691)
Location: include/net/netlink.h:1650
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_parse_addr
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
In lib/nlattr.c (ffffffff815df03c)
Location: include/net/netlink.h:1650
Inline: True
Inline callers:
  - lib/nlattr.c:nla_validate_int_range
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff818829a4)
Location: include/net/netlink.h:1650
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_nl_newlink
  - drivers/net/ppp/ppp_generic.c:ppp_nl_validate
```
```
In net/core/net_namespace.c (ffffffff819df812)
Location: include/net/netlink.h:1650
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/rtnetlink.c (ffffffff81a08be9)
Location: include/net/netlink.h:1650
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/ipv4/devinet.c (ffffffff81ad808c)
Location: include/net/netlink.h:1650
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
```
```
In net/ipv6/addrconf.c (ffffffff81b38f82)
Location: include/net/netlink.h:1650
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/mptcp/pm_netlink.c (ffffffff81bb8b35)
Location: include/net/netlink.h:1650
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_parse_addr
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
In lib/nlattr.c (ffffffff8164abbc)
Location: include/net/netlink.h:1650
Inline: True
Inline callers:
  - lib/nlattr.c:nla_validate_int_range
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81914344)
Location: include/net/netlink.h:1650
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_nl_newlink
  - drivers/net/ppp/ppp_generic.c:ppp_nl_validate
```
```
In net/core/net_namespace.c (ffffffff81a8fbf2)
Location: include/net/netlink.h:1650
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/rtnetlink.c (ffffffff81abaa09)
Location: include/net/netlink.h:1650
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/ipv4/devinet.c (ffffffff81b96eec)
Location: include/net/netlink.h:1650
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
```
```
In net/ipv6/addrconf.c (ffffffff81bff722)
Location: include/net/netlink.h:1650
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_valid_dump_ifaddr_req
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/mptcp/pm_netlink.c (ffffffff81c88105)
Location: include/net/netlink.h:1650
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_parse_addr
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
In lib/nlattr.c (ffffffff8176157a)
Location: include/net/netlink.h:1650
Inline: True
Inline callers:
  - lib/nlattr.c:nla_validate_int_range
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81a698f4)
Location: include/net/netlink.h:1650
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_nl_newlink
  - drivers/net/ppp/ppp_generic.c:ppp_nl_validate
```
```
In net/core/net_namespace.c (ffffffff81c059a3)
Location: include/net/netlink.h:1650
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/rtnetlink.c (ffffffff81c351fa)
Location: include/net/netlink.h:1650
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_newlink_create
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/ipv4/devinet.c (ffffffff81d28a90)
Location: include/net/netlink.h:1650
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
```
```
In net/ipv6/addrconf.c (ffffffff81d99205)
Location: include/net/netlink.h:1650
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/mptcp/pm_netlink.c (ffffffff81e316db)
Location: include/net/netlink.h:1650
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_parse_entry
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
In lib/nlattr.c (ffffffff8189095b)
Location: include/net/netlink.h:1699
Inline: True
Inline callers:
  - lib/nlattr.c:validate_nla
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81bfc454)
Location: include/net/netlink.h:1699
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_nl_newlink
  - drivers/net/ppp/ppp_generic.c:ppp_nl_validate
```
```
In net/core/net_namespace.c (ffffffff81db5273)
Location: include/net/netlink.h:1699
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/rtnetlink.c (ffffffff81de873a)
Location: include/net/netlink.h:1699
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_newlink_create
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/ipv4/devinet.c (ffffffff81ef04e0)
Location: include/net/netlink.h:1699
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
```
```
In net/ipv6/addrconf.c (ffffffff81f67f25)
Location: include/net/netlink.h:1699
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/mptcp/pm_netlink.c (ffffffff82009d0b)
Location: include/net/netlink.h:1699
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_parse_entry
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
In lib/nlattr.c (ffffffff818d2d9a)
Location: include/net/netlink.h:1700
Inline: True
Inline callers:
  - lib/nlattr.c:validate_nla
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81c61ad4)
Location: include/net/netlink.h:1700
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_nl_newlink
  - drivers/net/ppp/ppp_generic.c:ppp_nl_validate
```
```
In net/core/net_namespace.c (ffffffff81e25843)
Location: include/net/netlink.h:1700
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/rtnetlink.c (ffffffff81e59fb5)
Location: include/net/netlink.h:1700
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_newlink_create
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/ipv4/devinet.c (ffffffff81f4ff30)
Location: include/net/netlink.h:1700
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
```
```
In net/ipv6/addrconf.c (ffffffff81fc7f74)
Location: include/net/netlink.h:1700
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/mptcp/pm_netlink.c (ffffffff8208601b)
Location: include/net/netlink.h:1700
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_parse_entry
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
In lib/nlattr.c (ffffffff81924e77)
Location: include/net/netlink.h:1787
Inline: True
Inline callers:
  - lib/nlattr.c:validate_nla
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81d184c4)
Location: include/net/netlink.h:1787
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_nl_newlink
  - drivers/net/ppp/ppp_generic.c:ppp_nl_validate
```
```
In drivers/dpll/dpll_netlink.c (ffffffff81eba31a)
Location: include/net/netlink.h:1787
Inline: True
Inline callers:
  - drivers/dpll/dpll_netlink.c:dpll_pin_phase_adj_set
```
```
In net/core/net_namespace.c (ffffffff81ee37a3)
Location: include/net/netlink.h:1787
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/rtnetlink.c (ffffffff81f19348)
Location: include/net/netlink.h:1787
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_newlink_create
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/ipv4/devinet.c (ffffffff820160e0)
Location: include/net/netlink.h:1787
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
```
```
In net/ipv6/addrconf.c (ffffffff82095699)
Location: include/net/netlink.h:1787
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
```
In net/mptcp/pm_netlink.c (ffffffff8215b1cb)
Location: include/net/netlink.h:1787
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_parse_entry
```
```
In net/handshake/netlink.c (ffffffff82169126)
Location: include/net/netlink.h:1787
Inline: True
Inline callers:
  - net/handshake/netlink.c:handshake_nl_done_doit
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
In lib/nlattr.c (ffff8000106619f8)
Location: include/net/netlink.h:1570
Inline: True
Inline callers:
  - lib/nlattr.c:validate_nla
```
```
In drivers/net/ppp/ppp_generic.c (ffff8000109fed20)
Location: include/net/netlink.h:1570
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_nl_newlink
  - drivers/net/ppp/ppp_generic.c:ppp_nl_validate
```
```
In net/core/net_namespace.c (ffff800010bc1d5c)
Location: include/net/netlink.h:1570
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/rtnetlink.c (ffff800010bf140c)
Location: include/net/netlink.h:1570
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/ipv4/devinet.c (ffff800010ca6478)
Location: include/net/netlink.h:1570
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
```
```
In net/ipv6/addrconf.c (ffff800010d08320)
Location: include/net/netlink.h:1570
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
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
In lib/nlattr.c (c080a9ec)
Location: include/net/netlink.h:1570
Inline: True
Inline callers:
  - lib/nlattr.c:validate_nla
```
```
In drivers/net/ppp/ppp_generic.c (c0add5e4)
Location: include/net/netlink.h:1570
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_nl_newlink
  - drivers/net/ppp/ppp_generic.c:ppp_nl_validate
```
```
In net/core/net_namespace.c (c0cdca10)
Location: include/net/netlink.h:1570
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/rtnetlink.c (c0d09b98)
Location: include/net/netlink.h:1570
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/ipv4/devinet.c (c0db2f4c)
Location: include/net/netlink.h:1570
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
  - net/ipv4/devinet.c:inet_dump_ifaddr
```
```
In net/ipv6/addrconf.c (c0e0eae8)
Location: include/net/netlink.h:1570
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
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
In lib/nlattr.c (c0000000008156bc)
Location: include/net/netlink.h:1570
Inline: True
Inline callers:
  - lib/nlattr.c:validate_nla
```
```
In drivers/net/ppp/ppp_generic.c (c000000000aa8618)
Location: include/net/netlink.h:1570
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_nl_newlink
  - drivers/net/ppp/ppp_generic.c:ppp_nl_validate
```
```
In net/core/net_namespace.c (c000000000c9b564)
Location: include/net/netlink.h:1570
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/rtnetlink.c (c000000000cd5dac)
Location: include/net/netlink.h:1570
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/ipv4/devinet.c (c000000000dbac78)
Location: include/net/netlink.h:1570
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
```
```
In net/ipv6/addrconf.c (c000000000e3273c)
Location: include/net/netlink.h:1570
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
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
In lib/nlattr.c (ffffffe00048e0f6)
Location: include/net/netlink.h:1570
Inline: True
Inline callers:
  - lib/nlattr.c:validate_nla
```
```
In drivers/net/ppp/ppp_generic.c (ffffffe00062ceae)
Location: include/net/netlink.h:1570
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_nl_newlink
  - drivers/net/ppp/ppp_generic.c:ppp_nl_validate
```
```
In net/core/net_namespace.c (ffffffe00074edac)
Location: include/net/netlink.h:1570
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/rtnetlink.c (ffffffe000773224)
Location: include/net/netlink.h:1570
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/ipv4/devinet.c (ffffffe000801c7a)
Location: include/net/netlink.h:1570
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
```
```
In net/ipv6/addrconf.c (ffffffe00085040c)
Location: include/net/netlink.h:1570
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
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
In lib/nlattr.c (ffffffff8154dc22)
Location: include/net/netlink.h:1570
Inline: True
Inline callers:
  - lib/nlattr.c:validate_nla
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8178cc2d)
Location: include/net/netlink.h:1570
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_nl_newlink
  - drivers/net/ppp/ppp_generic.c:ppp_nl_validate
```
```
In net/core/net_namespace.c (ffffffff818c59b9)
Location: include/net/netlink.h:1570
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/rtnetlink.c (ffffffff818ef69d)
Location: include/net/netlink.h:1570
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/ipv4/devinet.c (ffffffff819903ae)
Location: include/net/netlink.h:1570
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
```
```
In net/ipv6/addrconf.c (ffffffff819e5009)
Location: include/net/netlink.h:1570
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
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
In lib/nlattr.c (ffffffff8153df02)
Location: include/net/netlink.h:1570
Inline: True
Inline callers:
  - lib/nlattr.c:validate_nla
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817759fd)
Location: include/net/netlink.h:1570
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_nl_newlink
  - drivers/net/ppp/ppp_generic.c:ppp_nl_validate
```
```
In net/core/net_namespace.c (ffffffff8187f8f9)
Location: include/net/netlink.h:1570
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/rtnetlink.c (ffffffff818a94dd)
Location: include/net/netlink.h:1570
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/ipv4/devinet.c (ffffffff81949e6e)
Location: include/net/netlink.h:1570
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
```
```
In net/ipv6/addrconf.c (ffffffff819a1dc9)
Location: include/net/netlink.h:1570
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
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
In lib/nlattr.c (ffffffff81549962)
Location: include/net/netlink.h:1570
Inline: True
Inline callers:
  - lib/nlattr.c:validate_nla
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817bcfcd)
Location: include/net/netlink.h:1570
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_nl_newlink
  - drivers/net/ppp/ppp_generic.c:ppp_nl_validate
```
```
In net/core/net_namespace.c (ffffffff819169b9)
Location: include/net/netlink.h:1570
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/rtnetlink.c (ffffffff819406cd)
Location: include/net/netlink.h:1570
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/ipv4/devinet.c (ffffffff819fac4e)
Location: include/net/netlink.h:1570
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
```
```
In net/ipv6/addrconf.c (ffffffff81a4fa89)
Location: include/net/netlink.h:1570
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
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
In lib/nlattr.c (ffffffff815637b2)
Location: include/net/netlink.h:1570
Inline: True
Inline callers:
  - lib/nlattr.c:validate_nla
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817d7bdd)
Location: include/net/netlink.h:1570
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_nl_newlink
  - drivers/net/ppp/ppp_generic.c:ppp_nl_validate
```
```
In net/core/net_namespace.c (ffffffff81937bc9)
Location: include/net/netlink.h:1570
Inline: True
Inline callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
```
```
In net/core/rtnetlink.c (ffffffff81961fdd)
Location: include/net/netlink.h:1570
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/ipv4/devinet.c (ffffffff81a04f9e)
Location: include/net/netlink.h:1570
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_netconf_get_devconf
```
```
In net/ipv6/addrconf.c (ffffffff81a5ba69)
Location: include/net/netlink.h:1570
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
```
</details>
</li>
</ul>

## Differences
