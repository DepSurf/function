# Function: <code>nla_reserve</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct nlattr *nla_reserve(struct sk_buff *skb, int attrtype, int attrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff81415a40)
Location: lib/nlattr.c:390
Inline: False
Direct callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
  - kernel/taskstats.c:mk_reply
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
  - net/core/rtnetlink.c:rtnl_fill_stats
  - net/core/rtnetlink.c:rtnl_fill_stats
  - net/core/sock_diag.c:sock_diag_put_filterinfo
  - net/core/sock_diag.c:sock_diag_put_filterinfo
  - net/ipv4/devinet.c:inet_fill_link_af
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
**Symbols:**

```
ffffffff81415a40-ffffffff81415a70: nla_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct nlattr *nla_reserve(struct sk_buff *skb, int attrtype, int attrlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff8145d790)
Location: lib/nlattr.c:414
Inline: True
Direct callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
  - net/core/rtnetlink.c:rtnl_fill_stats
  - net/core/sock_diag.c:sock_diag_put_filterinfo
  - net/core/sock_diag.c:sock_diag_put_filterinfo
  - net/ipv4/devinet.c:inet_fill_link_af
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
**Symbols:**

```
ffffffff8145d790-ffffffff8145d7c0: nla_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct nlattr *nla_reserve(struct sk_buff *skb, int attrtype, int attrlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff8147c250)
Location: lib/nlattr.c:414
Inline: True
Direct callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
  - net/core/rtnetlink.c:rtnl_fill_stats
  - net/core/sock_diag.c:sock_diag_put_filterinfo
  - net/core/sock_diag.c:sock_diag_put_filterinfo
  - net/ipv4/devinet.c:inet_fill_link_af
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/seg6_iptunnel.c:nla_put_srh
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
**Symbols:**

```
ffffffff8147c250-ffffffff8147c280: nla_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct nlattr *nla_reserve(struct sk_buff *skb, int attrtype, int attrlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff81485570)
Location: lib/nlattr.c:417
Inline: True
Direct callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
  - net/core/rtnetlink.c:rtnl_fill_stats
  - net/core/sock_diag.c:sock_diag_put_filterinfo
  - net/core/sock_diag.c:sock_diag_put_filterinfo
  - net/ipv4/devinet.c:inet_fill_link_af
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/seg6_iptunnel.c:seg6_fill_encap_info
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
**Symbols:**

```
ffffffff81485570-ffffffff814855a0: nla_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct nlattr *nla_reserve(struct sk_buff *skb, int attrtype, int attrlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff814c1700)
Location: lib/nlattr.c:495
Inline: True
Direct callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
  - net/core/rtnetlink.c:rtnl_fill_stats
  - net/core/sock_diag.c:sock_diag_put_filterinfo
  - net/core/sock_diag.c:sock_diag_put_filterinfo
  - net/sched/act_api.c:tc_dump_action
  - net/ipv4/devinet.c:inet_fill_link_af
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/seg6_iptunnel.c:seg6_fill_encap_info
  - net/ipv6/seg6_local.c:put_nla_nh6
  - net/ipv6/seg6_local.c:put_nla_nh4
  - net/ipv6/seg6_local.c:put_nla_srh
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
**Symbols:**

```
ffffffff814c1700-ffffffff814c1730: nla_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct nlattr *nla_reserve(struct sk_buff *skb, int attrtype, int attrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff814f2430)
Location: lib/nlattr.c:495
Inline: False
Direct callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
  - net/core/rtnetlink.c:rtnl_fill_stats
  - net/core/sock_diag.c:sock_diag_put_filterinfo
  - net/core/sock_diag.c:sock_diag_put_filterinfo
  - net/sched/act_api.c:tc_dump_action
  - net/ipv4/devinet.c:inet_fill_link_af
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/seg6_iptunnel.c:seg6_fill_encap_info
  - net/ipv6/seg6_local.c:put_nla_nh6
  - net/ipv6/seg6_local.c:put_nla_nh4
  - net/ipv6/seg6_local.c:put_nla_srh
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
**Symbols:**

```
ffffffff814f2430-ffffffff814f2460: nla_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct nlattr *nla_reserve(struct sk_buff *skb, int attrtype, int attrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff81506170)
Location: lib/nlattr.c:670
Inline: False
Direct callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
  - net/core/rtnetlink.c:rtnl_fill_stats
  - net/core/sock_diag.c:sock_diag_put_filterinfo
  - net/core/sock_diag.c:sock_diag_put_filterinfo
  - net/sched/act_api.c:tc_dump_action
  - net/ipv4/devinet.c:inet_fill_link_af
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/seg6_iptunnel.c:seg6_fill_encap_info
  - net/ipv6/seg6_local.c:put_nla_nh6
  - net/ipv6/seg6_local.c:put_nla_nh4
  - net/ipv6/seg6_local.c:put_nla_srh
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
**Symbols:**

```
ffffffff81506170-ffffffff8150619d: nla_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct nlattr *nla_reserve(struct sk_buff *skb, int attrtype, int attrlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff81534b30)
Location: lib/nlattr.c:702
Inline: True
Direct callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
  - net/core/rtnetlink.c:rtnl_fill_stats
  - net/core/sock_diag.c:sock_diag_put_filterinfo
  - net/core/sock_diag.c:sock_diag_put_filterinfo
  - net/sched/act_api.c:tc_dump_action
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/devinet.c:inet_fill_link_af
  - net/ipv4/fib_semantics.c:fib_nexthop_info
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/seg6_iptunnel.c:seg6_fill_encap_info
  - net/ipv6/seg6_local.c:put_nla_nh6
  - net/ipv6/seg6_local.c:put_nla_nh4
  - net/ipv6/seg6_local.c:put_nla_srh
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
**Symbols:**

```
ffffffff81534b30-ffffffff81534b5d: nla_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct nlattr *nla_reserve(struct sk_buff *skb, int attrtype, int attrlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff81555960)
Location: lib/nlattr.c:702
Inline: True
Direct callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
  - net/core/rtnetlink.c:rtnl_fill_stats
  - net/core/sock_diag.c:sock_diag_put_filterinfo
  - net/core/sock_diag.c:sock_diag_put_filterinfo
  - net/core/drop_monitor.c:reset_per_cpu_data
  - net/sched/act_api.c:tc_dump_action
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/devinet.c:inet_fill_link_af
  - net/ipv4/fib_semantics.c:fib_nexthop_info
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/seg6_iptunnel.c:seg6_fill_encap_info
  - net/ipv6/seg6_local.c:put_nla_nh6
  - net/ipv6/seg6_local.c:put_nla_nh4
  - net/ipv6/seg6_local.c:put_nla_srh
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
**Symbols:**

```
ffffffff81555960-ffffffff8155598d: nla_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct nlattr *nla_reserve(struct sk_buff *skb, int attrtype, int attrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff815de6f0)
Location: lib/nlattr.c:854
Inline: False
Direct callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - net/core/rtnetlink.c:rtnl_fill_stats
  - net/core/sock_diag.c:sock_diag_put_filterinfo
  - net/core/sock_diag.c:sock_diag_put_filterinfo
  - net/core/drop_monitor.c:reset_per_cpu_data
  - net/sched/act_api.c:tc_dump_action
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/devinet.c:inet_fill_link_af
  - net/ipv4/fib_semantics.c:fib_nexthop_info
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/seg6_iptunnel.c:seg6_fill_encap_info
  - net/ipv6/seg6_local.c:put_nla_nh6
  - net/ipv6/seg6_local.c:put_nla_nh4
  - net/ipv6/seg6_local.c:put_nla_srh
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
**Symbols:**

```
ffffffff815de6f0-ffffffff815de71d: nla_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct nlattr *nla_reserve(struct sk_buff *skb, int attrtype, int attrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff815fbd90)
Location: lib/nlattr.c:920
Inline: False
Direct callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - net/core/rtnetlink.c:rtnl_fill_stats
  - net/core/sock_diag.c:sock_diag_put_filterinfo
  - net/core/sock_diag.c:sock_diag_put_filterinfo
  - net/core/drop_monitor.c:reset_per_cpu_data
  - net/sched/act_api.c:tc_dump_action
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/devinet.c:inet_fill_link_af
  - net/ipv4/fib_semantics.c:fib_nexthop_info
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/seg6_iptunnel.c:seg6_fill_encap_info
  - net/ipv6/seg6_local.c:put_nla_nh6
  - net/ipv6/seg6_local.c:put_nla_nh4
  - net/ipv6/seg6_local.c:put_nla_srh
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
**Symbols:**

```
ffffffff815fbd90-ffffffff815fbdbd: nla_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct nlattr *nla_reserve(struct sk_buff *skb, int attrtype, int attrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff815de9d0)
Location: lib/nlattr.c:920
Inline: False
Direct callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - net/core/rtnetlink.c:rtnl_fill_stats
  - net/core/sock_diag.c:sock_diag_put_filterinfo
  - net/core/sock_diag.c:sock_diag_put_filterinfo
  - net/core/drop_monitor.c:reset_per_cpu_data
  - net/sched/act_api.c:tc_dump_action
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/strset.c:strset_fill_reply
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/devinet.c:inet_fill_link_af
  - net/ipv4/fib_semantics.c:fib_nexthop_info
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/seg6_iptunnel.c:seg6_fill_encap_info
  - net/ipv6/seg6_local.c:put_nla_nh6
  - net/ipv6/seg6_local.c:put_nla_nh4
  - net/ipv6/seg6_local.c:put_nla_srh
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
**Symbols:**

```
ffffffff815de9d0-ffffffff815de9fd: nla_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct nlattr *nla_reserve(struct sk_buff *skb, int attrtype, int attrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff8164a550)
Location: lib/nlattr.c:920
Inline: False
Direct callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - net/core/rtnetlink.c:rtnl_fill_stats
  - net/core/sock_diag.c:sock_diag_put_filterinfo
  - net/core/sock_diag.c:sock_diag_put_filterinfo
  - net/core/drop_monitor.c:reset_per_cpu_data
  - net/sched/act_api.c:tc_dump_action
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/strset.c:strset_fill_reply
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/devinet.c:inet_fill_link_af
  - net/ipv4/fib_semantics.c:fib_nexthop_info
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/seg6_iptunnel.c:seg6_fill_encap_info
  - net/ipv6/seg6_local.c:put_nla_nh6
  - net/ipv6/seg6_local.c:put_nla_nh4
  - net/ipv6/seg6_local.c:put_nla_srh
  - net/ipv6/ioam6_iptunnel.c:ioam6_fill_encap_info
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
**Symbols:**

```
ffffffff8164a550-ffffffff8164a57d: nla_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct nlattr *nla_reserve(struct sk_buff *skb, int attrtype, int attrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff81760d20)
Location: lib/nlattr.c:920
Inline: False
Direct callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - net/core/rtnetlink.c:rtnl_fill_stats
  - net/core/sock_diag.c:sock_diag_put_filterinfo
  - net/core/sock_diag.c:sock_diag_put_filterinfo
  - net/core/drop_monitor.c:reset_per_cpu_data
  - net/sched/act_api.c:tc_dump_action
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/devinet.c:inet_fill_link_af
  - net/ipv4/fib_semantics.c:fib_nexthop_info
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/seg6_iptunnel.c:seg6_fill_encap_info
  - net/ipv6/seg6_local.c:put_nla_nh6
  - net/ipv6/seg6_local.c:put_nla_nh4
  - net/ipv6/seg6_local.c:put_nla_srh
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
**Symbols:**

```
ffffffff81760d20-ffffffff81760d65: nla_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct nlattr *nla_reserve(struct sk_buff *skb, int attrtype, int attrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff8188f720)
Location: lib/nlattr.c:935
Inline: False
Direct callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - net/core/rtnetlink.c:rtnl_fill_stats
  - net/core/sock_diag.c:sock_diag_put_filterinfo
  - net/core/sock_diag.c:sock_diag_put_filterinfo
  - net/core/drop_monitor.c:reset_per_cpu_data
  - net/sched/act_api.c:tc_dump_action
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/devinet.c:inet_fill_link_af
  - net/ipv4/fib_semantics.c:fib_nexthop_info
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/seg6_local.c:put_nla_nh6
  - net/ipv6/seg6_local.c:put_nla_nh4
  - net/ipv6/seg6_local.c:put_nla_srh
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
**Symbols:**

```
ffffffff8188f720-ffffffff8188f765: nla_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct nlattr *nla_reserve(struct sk_buff *skb, int attrtype, int attrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff818d1b60)
Location: lib/nlattr.c:935
Inline: False
Direct callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - net/core/rtnetlink.c:rtnl_fill_stats
  - net/core/sock_diag.c:sock_diag_put_filterinfo
  - net/core/sock_diag.c:sock_diag_put_filterinfo
  - net/core/drop_monitor.c:reset_per_cpu_data
  - net/sched/act_api.c:tc_dump_action
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/devinet.c:inet_fill_link_af
  - net/ipv4/fib_semantics.c:fib_nexthop_info
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/seg6_local.c:put_nla_nh6
  - net/ipv6/seg6_local.c:put_nla_nh4
  - net/ipv6/seg6_local.c:put_nla_srh
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
**Symbols:**

```
ffffffff818d1b60-ffffffff818d1ba5: nla_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct nlattr *nla_reserve(struct sk_buff *skb, int attrtype, int attrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff81923b60)
Location: lib/nlattr.c:967
Inline: False
Direct callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - drivers/regulator/event.c:reg_generate_netlink_event
  - net/core/rtnetlink.c:rtnl_fill_stats
  - net/core/sock_diag.c:sock_diag_put_filterinfo
  - net/core/sock_diag.c:sock_diag_put_filterinfo
  - net/core/drop_monitor.c:reset_per_cpu_data
  - net/sched/act_api.c:tc_dump_action
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ethtool/bitset.c:ethnl_put_bitset32
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/devinet.c:inet_fill_link_af
  - net/ipv4/fib_semantics.c:fib_nexthop_info
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/seg6_local.c:put_nla_nh6
  - net/ipv6/seg6_local.c:put_nla_nh4
  - net/ipv6/seg6_local.c:put_nla_srh
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
**Symbols:**

```
ffffffff81923b60-ffffffff81923ba5: nla_reserve (STB_GLOBAL)
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
struct nlattr *nla_reserve(struct sk_buff *skb, int attrtype, int attrlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffff800010661df0)
Location: lib/nlattr.c:702
Inline: True
Direct callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
  - net/core/rtnetlink.c:rtnl_fill_stats
  - net/core/sock_diag.c:sock_diag_put_filterinfo
  - net/core/sock_diag.c:sock_diag_put_filterinfo
  - net/core/drop_monitor.c:reset_per_cpu_data
  - net/sched/act_api.c:tc_dump_action
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/devinet.c:inet_fill_link_af
  - net/ipv4/fib_semantics.c:fib_nexthop_info
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/seg6_iptunnel.c:seg6_fill_encap_info
  - net/ipv6/seg6_local.c:put_nla_nh6
  - net/ipv6/seg6_local.c:put_nla_nh4
  - net/ipv6/seg6_local.c:put_nla_srh
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
**Symbols:**

```
ffff800010661df0-ffff800010661e30: nla_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct nlattr *nla_reserve(struct sk_buff *skb, int attrtype, int attrlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (c080ae80)
Location: lib/nlattr.c:702
Inline: True
Direct callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
  - net/core/rtnetlink.c:rtnl_fill_stats
  - net/core/sock_diag.c:sock_diag_put_filterinfo
  - net/core/sock_diag.c:sock_diag_put_filterinfo
  - net/core/drop_monitor.c:reset_per_cpu_data
  - net/sched/act_api.c:tc_dump_action
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/devinet.c:inet_fill_link_af
  - net/ipv4/fib_semantics.c:fib_nexthop_info
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/seg6_iptunnel.c:seg6_fill_encap_info
  - net/ipv6/seg6_local.c:put_nla_nh6
  - net/ipv6/seg6_local.c:put_nla_nh4
  - net/ipv6/seg6_local.c:put_nla_srh
  - net/wireless/wext-core.c:wireless_send_event
```
**Symbols:**

```
c080ae80-c080aec4: nla_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct nlattr *nla_reserve(struct sk_buff *skb, int attrtype, int attrlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (c000000000816030)
Location: lib/nlattr.c:702
Inline: True
Direct callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
  - net/core/rtnetlink.c:rtnl_fill_stats
  - net/core/sock_diag.c:sock_diag_put_filterinfo
  - net/core/sock_diag.c:sock_diag_put_filterinfo
  - net/core/drop_monitor.c:reset_per_cpu_data
  - net/sched/act_api.c:tc_dump_action
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/devinet.c:inet_fill_link_af
  - net/ipv4/fib_semantics.c:fib_nexthop_info
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/seg6_iptunnel.c:seg6_fill_encap_info
  - net/ipv6/seg6_local.c:put_nla_nh6
  - net/ipv6/seg6_local.c:put_nla_nh4
  - net/ipv6/seg6_local.c:put_nla_srh
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
**Symbols:**

```
c000000000816030-c000000000816078: nla_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct nlattr *nla_reserve(struct sk_buff *skb, int attrtype, int attrlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffe00048e76e)
Location: lib/nlattr.c:702
Inline: True
Inline callers:
  - lib/nlattr.c:__nla_reserve_64bit
Direct callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
  - net/core/rtnetlink.c:rtnl_fill_stats
  - net/core/sock_diag.c:sock_diag_put_filterinfo
  - net/core/sock_diag.c:sock_diag_put_filterinfo
  - net/core/drop_monitor.c:reset_per_cpu_data
  - net/sched/act_api.c:tc_dump_action
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/devinet.c:inet_fill_link_af
  - net/ipv4/fib_semantics.c:fib_nexthop_info
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/seg6_iptunnel.c:seg6_fill_encap_info
  - net/ipv6/seg6_local.c:put_nla_nh6
  - net/ipv6/seg6_local.c:put_nla_nh4
  - net/ipv6/seg6_local.c:put_nla_srh
  - net/wireless/wext-core.c:wireless_send_event
```
**Symbols:**

```
ffffffe00048e6fa-ffffffe00048e732: nla_reserve (STB_GLOBAL)
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
struct nlattr *nla_reserve(struct sk_buff *skb, int attrtype, int attrlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff8154df40)
Location: lib/nlattr.c:702
Inline: True
Direct callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
  - net/core/rtnetlink.c:rtnl_fill_stats
  - net/core/sock_diag.c:sock_diag_put_filterinfo
  - net/core/sock_diag.c:sock_diag_put_filterinfo
  - net/core/drop_monitor.c:reset_per_cpu_data
  - net/sched/act_api.c:tc_dump_action
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/devinet.c:inet_fill_link_af
  - net/ipv4/fib_semantics.c:fib_nexthop_info
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/seg6_iptunnel.c:seg6_fill_encap_info
  - net/ipv6/seg6_local.c:put_nla_nh6
  - net/ipv6/seg6_local.c:put_nla_nh4
  - net/ipv6/seg6_local.c:put_nla_srh
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
**Symbols:**

```
ffffffff8154df40-ffffffff8154df6d: nla_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct nlattr *nla_reserve(struct sk_buff *skb, int attrtype, int attrlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff8153e220)
Location: lib/nlattr.c:702
Inline: True
Direct callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
  - net/core/rtnetlink.c:rtnl_fill_stats
  - net/core/sock_diag.c:sock_diag_put_filterinfo
  - net/core/sock_diag.c:sock_diag_put_filterinfo
  - net/core/drop_monitor.c:reset_per_cpu_data
  - net/sched/act_api.c:tc_dump_action
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/devinet.c:inet_fill_link_af
  - net/ipv4/fib_semantics.c:fib_nexthop_info
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/seg6_iptunnel.c:seg6_fill_encap_info
  - net/ipv6/seg6_local.c:put_nla_nh6
  - net/ipv6/seg6_local.c:put_nla_nh4
  - net/ipv6/seg6_local.c:put_nla_srh
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
**Symbols:**

```
ffffffff8153e220-ffffffff8153e24d: nla_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct nlattr *nla_reserve(struct sk_buff *skb, int attrtype, int attrlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff81549c80)
Location: lib/nlattr.c:702
Inline: True
Direct callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
  - net/core/rtnetlink.c:rtnl_fill_stats
  - net/core/sock_diag.c:sock_diag_put_filterinfo
  - net/core/sock_diag.c:sock_diag_put_filterinfo
  - net/core/drop_monitor.c:reset_per_cpu_data
  - net/sched/act_api.c:tc_dump_action
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/devinet.c:inet_fill_link_af
  - net/ipv4/fib_semantics.c:fib_nexthop_info
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/seg6_iptunnel.c:seg6_fill_encap_info
  - net/ipv6/seg6_local.c:put_nla_nh6
  - net/ipv6/seg6_local.c:put_nla_nh4
  - net/ipv6/seg6_local.c:put_nla_srh
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
**Symbols:**

```
ffffffff81549c80-ffffffff81549cad: nla_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct nlattr *nla_reserve(struct sk_buff *skb, int attrtype, int attrlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff81563ad0)
Location: lib/nlattr.c:702
Inline: True
Direct callers:
  - kernel/taskstats.c:cgroupstats_user_cmd
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - drivers/thermal/thermal_core.c:thermal_generate_netlink_event
  - net/core/rtnetlink.c:rtnl_fill_stats
  - net/core/drop_monitor.c:reset_per_cpu_data
  - net/sched/act_api.c:tc_dump_action
  - net/ipv4/route.c:rt_fill_info
  - net/ipv4/devinet.c:inet_fill_link_af
  - net/ipv4/fib_semantics.c:fib_nexthop_info
  - net/ipv4/nexthop.c:nh_fill_node
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/seg6_iptunnel.c:seg6_fill_encap_info
  - net/ipv6/seg6_local.c:put_nla_nh6
  - net/ipv6/seg6_local.c:put_nla_nh4
  - net/ipv6/seg6_local.c:put_nla_srh
  - net/wireless/wext-core.c:wireless_send_event
  - net/wireless/wext-core.c:wireless_send_event
```
**Symbols:**

```
ffffffff81563ad0-ffffffff81563afd: nla_reserve (STB_GLOBAL)
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
