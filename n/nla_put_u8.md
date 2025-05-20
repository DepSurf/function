# Function: <code>nla_put_u8</code>

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
In net/core/rtnetlink.c (ffffffff8172b650)
Location: include/net/netlink.h:746
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff817a432c)
Location: include/net/netlink.h:746
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
```
```
In net/ipv6/addrconf.c (ffffffff817cb070)
Location: include/net/netlink.h:746
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
```
```
In net/ipv6/route.c (ffffffff817d89b8)
Location: include/net/netlink.h:746
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff8180e597)
Location: include/net/netlink.h:746
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff8180ff35)
Location: include/net/netlink.h:746
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/dcb/dcbnl.c (ffffffff81812c9e)
Location: include/net/netlink.h:746
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_setdcbx
  - net/dcb/dcbnl.c:dcbnl_getdcbx
  - net/dcb/dcbnl.c:dcbnl_setpfcstate
  - net/dcb/dcbnl.c:dcbnl_getpfcstate
  - net/dcb/dcbnl.c:dcbnl_setstate
  - net/dcb/dcbnl.c:dcbnl_getstate
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_setcfg
  - net/dcb/dcbnl.c:dcbnl_setnumtcs
  - net/dcb/dcbnl.c:dcbnl_setpfccfg
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_setall
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getcap
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
In net/core/rtnetlink.c (ffffffff817990f4)
Location: include/net/netlink.h:757
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/fib_rules.c (ffffffff817a6359)
Location: include/net/netlink.h:757
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81811fd2)
Location: include/net/netlink.h:757
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
```
```
In net/ipv6/addrconf.c (ffffffff818388a6)
Location: include/net/netlink.h:757
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
```
```
In net/ipv6/route.c (ffffffff8184239e)
Location: include/net/netlink.h:757
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81880c18)
Location: include/net/netlink.h:757
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81882605)
Location: include/net/netlink.h:757
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/dcb/dcbnl.c (ffffffff8188663c)
Location: include/net/netlink.h:757
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_setdcbx
  - net/dcb/dcbnl.c:dcbnl_getdcbx
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_bcn_setcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_setall
  - net/dcb/dcbnl.c:dcbnl_setpfccfg
  - net/dcb/dcbnl.c:dcbnl_setstate
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_setpfcstate
  - net/dcb/dcbnl.c:dcbnl_getpfcstate
  - net/dcb/dcbnl.c:dcbnl_setnumtcs
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
  - net/dcb/dcbnl.c:dcbnl_getstate
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
In net/core/rtnetlink.c (ffffffff817c6ea4)
Location: include/net/netlink.h:757
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/fib_rules.c (ffffffff817d4ed6)
Location: include/net/netlink.h:757
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff818434e2)
Location: include/net/netlink.h:757
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
```
```
In net/ipv6/addrconf.c (ffffffff8186a3d6)
Location: include/net/netlink.h:757
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
```
```
In net/ipv6/route.c (ffffffff818740ee)
Location: include/net/netlink.h:757
Inline: True
```
```
In net/ipv6/seg6.c (ffffffff818998bc)
Location: include/net/netlink.h:757
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff818b54c8)
Location: include/net/netlink.h:757
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff818b6eb5)
Location: include/net/netlink.h:757
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/dcb/dcbnl.c (ffffffff818baeac)
Location: include/net/netlink.h:757
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_setdcbx
  - net/dcb/dcbnl.c:dcbnl_getdcbx
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_bcn_setcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_setall
  - net/dcb/dcbnl.c:dcbnl_setpfccfg
  - net/dcb/dcbnl.c:dcbnl_setstate
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_setpfcstate
  - net/dcb/dcbnl.c:dcbnl_getpfcstate
  - net/dcb/dcbnl.c:dcbnl_setnumtcs
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
  - net/dcb/dcbnl.c:dcbnl_getstate
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
In net/core/rtnetlink.c (ffffffff817e57b3)
Location: include/net/netlink.h:769
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/fib_rules.c (ffffffff817f4290)
Location: include/net/netlink.h:769
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81864d32)
Location: include/net/netlink.h:769
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
```
```
In net/ipv4/ipmr.c (ffffffff8186aab2)
Location: include/net/netlink.h:769
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (ffffffff8188e92f)
Location: include/net/netlink.h:769
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
```
```
In net/ipv6/route.c (ffffffff81899010)
Location: include/net/netlink.h:769
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/seg6.c (ffffffff818bfaca)
Location: include/net/netlink.h:769
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
```
In net/ipv6/ip6mr.c (ffffffff818c1683)
Location: include/net/netlink.h:769
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff818dbe14)
Location: include/net/netlink.h:769
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff818dd76d)
Location: include/net/netlink.h:769
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/dcb/dcbnl.c (ffffffff818e18b8)
Location: include/net/netlink.h:769
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_setdcbx
  - net/dcb/dcbnl.c:dcbnl_getdcbx
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_bcn_setcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_setall
  - net/dcb/dcbnl.c:dcbnl_setpfccfg
  - net/dcb/dcbnl.c:dcbnl_setstate
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_setpfcstate
  - net/dcb/dcbnl.c:dcbnl_getpfcstate
  - net/dcb/dcbnl.c:dcbnl_setnumtcs
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
  - net/dcb/dcbnl.c:dcbnl_getstate
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
In net/core/rtnetlink.c (ffffffff81860853)
Location: include/net/netlink.h:775
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/fib_rules.c (ffffffff8186f9f5)
Location: include/net/netlink.h:775
Inline: True
```
```
In net/sched/sch_api.c (ffffffff8187d515)
Location: include/net/netlink.h:775
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/ipv4/tcp.c (ffffffff818a6eba)
Location: include/net/netlink.h:775
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff818e4e8c)
Location: include/net/netlink.h:775
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
```
```
In net/ipv4/ipmr.c (ffffffff818eb233)
Location: include/net/netlink.h:775
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (ffffffff8190ff7f)
Location: include/net/netlink.h:775
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
```
```
In net/ipv6/route.c (ffffffff8191a316)
Location: include/net/netlink.h:775
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/seg6.c (ffffffff81942b95)
Location: include/net/netlink.h:775
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
```
In net/ipv6/ip6mr.c (ffffffff819449d3)
Location: include/net/netlink.h:775
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff819619ed)
Location: include/net/netlink.h:775
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff8196335d)
Location: include/net/netlink.h:775
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/dcb/dcbnl.c (ffffffff8196763e)
Location: include/net/netlink.h:775
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_setdcbx
  - net/dcb/dcbnl.c:dcbnl_getdcbx
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_bcn_setcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_setall
  - net/dcb/dcbnl.c:dcbnl_setpfccfg
  - net/dcb/dcbnl.c:dcbnl_setstate
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_setpfcstate
  - net/dcb/dcbnl.c:dcbnl_getpfcstate
  - net/dcb/dcbnl.c:dcbnl_setnumtcs
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
  - net/dcb/dcbnl.c:dcbnl_getstate
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
In drivers/net/tun.c (ffffffff8173bda7)
Location: include/net/netlink.h:775
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
```
```
In net/core/rtnetlink.c (ffffffff818aa70b)
Location: include/net/netlink.h:775
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_xdp_fill
```
```
In net/core/fib_rules.c (ffffffff818c0e46)
Location: include/net/netlink.h:775
Inline: True
```
```
In net/sched/sch_api.c (ffffffff818cfcae)
Location: include/net/netlink.h:775
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/ipv4/tcp.c (ffffffff818fbfba)
Location: include/net/netlink.h:775
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff8193b76c)
Location: include/net/netlink.h:775
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
```
```
In net/ipv4/ipmr.c (ffffffff81941a05)
Location: include/net/netlink.h:775
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (ffffffff8196738f)
Location: include/net/netlink.h:775
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
```
```
In net/ipv6/route.c (ffffffff819721cd)
Location: include/net/netlink.h:775
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/seg6.c (ffffffff8199bac6)
Location: include/net/netlink.h:775
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
```
In net/ipv6/ip6mr.c (ffffffff8199d6c6)
Location: include/net/netlink.h:775
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff819bb194)
Location: include/net/netlink.h:775
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff819bcbad)
Location: include/net/netlink.h:775
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/dcb/dcbnl.c (ffffffff819c0b4e)
Location: include/net/netlink.h:775
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_setdcbx
  - net/dcb/dcbnl.c:dcbnl_getdcbx
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_bcn_setcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_setall
  - net/dcb/dcbnl.c:dcbnl_setpfccfg
  - net/dcb/dcbnl.c:dcbnl_setstate
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_setpfcstate
  - net/dcb/dcbnl.c:dcbnl_getpfcstate
  - net/dcb/dcbnl.c:dcbnl_setnumtcs
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
  - net/dcb/dcbnl.c:dcbnl_getstate
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
In drivers/net/tun.c (ffffffff8175f6e7)
Location: include/net/netlink.h:918
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
```
```
In net/core/neighbour.c (ffffffff818c5afb)
Location: include/net/netlink.h:918
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
```
```
In net/core/rtnetlink.c (ffffffff818d05a8)
Location: include/net/netlink.h:918
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/fib_rules.c (ffffffff818e9c53)
Location: include/net/netlink.h:918
Inline: True
```
```
In net/sched/sch_api.c (ffffffff818faf2b)
Location: include/net/netlink.h:918
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/ipv4/tcp.c (ffffffff81929f2c)
Location: include/net/netlink.h:918
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff8196b45c)
Location: include/net/netlink.h:918
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
```
```
In net/ipv4/ipmr.c (ffffffff819712b0)
Location: include/net/netlink.h:918
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (ffffffff8199c99c)
Location: include/net/netlink.h:918
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
```
```
In net/ipv6/route.c (ffffffff819a7925)
Location: include/net/netlink.h:918
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/seg6.c (ffffffff819d2696)
Location: include/net/netlink.h:918
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
```
In net/ipv6/ip6mr.c (ffffffff819d4220)
Location: include/net/netlink.h:918
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff819f2404)
Location: include/net/netlink.h:918
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff819f3dff)
Location: include/net/netlink.h:918
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/dcb/dcbnl.c (ffffffff819f7efe)
Location: include/net/netlink.h:918
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_setdcbx
  - net/dcb/dcbnl.c:dcbnl_getdcbx
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_bcn_setcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_setall
  - net/dcb/dcbnl.c:dcbnl_setpfccfg
  - net/dcb/dcbnl.c:dcbnl_setstate
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_setpfcstate
  - net/dcb/dcbnl.c:dcbnl_getpfcstate
  - net/dcb/dcbnl.c:dcbnl_setnumtcs
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
  - net/dcb/dcbnl.c:dcbnl_getstate
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
In drivers/net/tun.c (ffffffff8179cf17)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
```
```
In net/core/neighbour.c (ffffffff81911b18)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
```
```
In net/core/rtnetlink.c (ffffffff8191d43f)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/fib_rules.c (ffffffff8193969e)
Location: include/net/netlink.h:1176
Inline: True
```
```
In net/core/devlink.c (ffffffff8194ed3a)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
```
```
In net/sched/sch_api.c (ffffffff8195a91b)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/ipv4/tcp.c (ffffffff8198d13b)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff819d2126)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
```
```
In net/ipv4/ipmr.c (ffffffff819daa38)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (ffffffff81a08b72)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
```
```
In net/ipv6/route.c (ffffffff81a13f7f)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/seg6.c (ffffffff81a41487)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
```
In net/ipv6/ip6mr.c (ffffffff81a430c3)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81a61753)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81a6325d)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/dcb/dcbnl.c (ffffffff81a67432)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_setdcbx
  - net/dcb/dcbnl.c:dcbnl_getdcbx
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_bcn_setcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_setall
  - net/dcb/dcbnl.c:dcbnl_setpfccfg
  - net/dcb/dcbnl.c:dcbnl_setstate
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_setpfcstate
  - net/dcb/dcbnl.c:dcbnl_getpfcstate
  - net/dcb/dcbnl.c:dcbnl_setnumtcs
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
  - net/dcb/dcbnl.c:dcbnl_getstate
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
In drivers/net/tun.c (ffffffff817c09b7)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
```
```
In net/core/neighbour.c (ffffffff81944186)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
```
```
In net/core/rtnetlink.c (ffffffff8194fa8c)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/fib_rules.c (ffffffff8196c56b)
Location: include/net/netlink.h:1176
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff819756e3)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_config_get
```
```
In net/core/devlink.c (ffffffff81983a46)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_fill
```
```
In net/sched/sch_api.c (ffffffff81990dcb)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/ipv4/tcp.c (ffffffff819c3adb)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81a08c96)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
```
```
In net/ipv4/ipmr.c (ffffffff81a118e6)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (ffffffff81a3f282)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
```
```
In net/ipv6/route.c (ffffffff81a4ab6f)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/seg6.c (ffffffff81a78107)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
```
In net/ipv6/ip6mr.c (ffffffff81a79c23)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81a98323)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81a99e0d)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/dcb/dcbnl.c (ffffffff81a9df52)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_setdcbx
  - net/dcb/dcbnl.c:dcbnl_getdcbx
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_bcn_setcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_setall
  - net/dcb/dcbnl.c:dcbnl_setpfccfg
  - net/dcb/dcbnl.c:dcbnl_setstate
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_setpfcstate
  - net/dcb/dcbnl.c:dcbnl_getpfcstate
  - net/dcb/dcbnl.c:dcbnl_setnumtcs
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
  - net/dcb/dcbnl.c:dcbnl_getstate
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
In drivers/net/tun.c (ffffffff8188a197)
Location: include/net/netlink.h:1228
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
```
```
In net/core/neighbour.c (ffffffff81a141cc)
Location: include/net/netlink.h:1228
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
```
```
In net/core/rtnetlink.c (ffffffff81a212aa)
Location: include/net/netlink.h:1228
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_xdp_fill
```
```
In net/core/fib_rules.c (ffffffff81a40416)
Location: include/net/netlink.h:1228
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:fib_nl_fill_rule
```
```
In net/core/drop_monitor.c (ffffffff81a4a49d)
Location: include/net/netlink.h:1228
Inline: True
```
```
In net/core/devlink.c (ffffffff81a5e731)
Location: include/net/netlink.h:1228
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_value_fill_one
  - net/core/devlink.c:devlink_nl_param_value_fill_one
  - net/core/devlink.c:devlink_resource_size_params_put
  - net/core/devlink.c:devlink_dpipe_header_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_nl_fill
```
```
In net/sched/sch_api.c (ffffffff81a68ddb)
Location: include/net/netlink.h:1228
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/ethtool/linkinfo.c (ffffffff81a88679)
Location: include/net/netlink.h:1228
Inline: True
Inline callers:
  - net/ethtool/linkinfo.c:linkinfo_fill_reply
  - net/ethtool/linkinfo.c:linkinfo_fill_reply
  - net/ethtool/linkinfo.c:linkinfo_fill_reply
  - net/ethtool/linkinfo.c:linkinfo_fill_reply
  - net/ethtool/linkinfo.c:linkinfo_fill_reply
```
```
In net/ethtool/linkmodes.c (ffffffff81a88ac4)
Location: include/net/netlink.h:1228
Inline: True
Inline callers:
  - net/ethtool/linkmodes.c:linkmodes_fill_reply
  - net/ethtool/linkmodes.c:linkmodes_fill_reply
  - net/ethtool/linkmodes.c:linkmodes_fill_reply
  - net/ethtool/linkmodes.c:linkmodes_fill_reply
```
```
In net/ethtool/linkstate.c (ffffffff81a892e9)
Location: include/net/netlink.h:1228
Inline: True
Inline callers:
  - net/ethtool/linkstate.c:linkstate_fill_reply
```
```
In net/ethtool/coalesce.c (ffffffff81a8b6fc)
Location: include/net/netlink.h:1228
Inline: True
Inline callers:
  - net/ethtool/coalesce.c:coalesce_fill_reply
  - net/ethtool/coalesce.c:coalesce_fill_reply
```
```
In net/ethtool/pause.c (ffffffff81a8bf72)
Location: include/net/netlink.h:1228
Inline: True
Inline callers:
  - net/ethtool/pause.c:pause_fill_reply
  - net/ethtool/pause.c:pause_fill_reply
  - net/ethtool/pause.c:pause_fill_reply
```
```
In net/ethtool/eee.c (ffffffff81a8c374)
Location: include/net/netlink.h:1228
Inline: True
Inline callers:
  - net/ethtool/eee.c:eee_fill_reply
  - net/ethtool/eee.c:eee_fill_reply
  - net/ethtool/eee.c:eee_fill_reply
```
```
In net/ethtool/cabletest.c (ffffffff81a8d427)
Location: include/net/netlink.h:1228
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_cable_test_amplitude
  - net/ethtool/cabletest.c:ethnl_cable_test_fault_length
  - net/ethtool/cabletest.c:ethnl_cable_test_result
  - net/ethtool/cabletest.c:ethnl_cable_test_result
  - net/ethtool/cabletest.c:ethnl_cable_test_alloc
```
```
In net/ipv4/tcp.c (ffffffff81aaf25d)
Location: include/net/netlink.h:1228
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af9d70)
Location: include/net/netlink.h:1228
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_opts_erspan
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_opts_erspan
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_opts_erspan
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_opts_geneve
```
```
In net/ipv4/ipmr.c (ffffffff81b001df)
Location: include/net/netlink.h:1228
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_fill_table
  - net/ipv4/ipmr.c:ipmr_fill_table
  - net/ipv4/ipmr.c:ipmr_fill_table
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
```
```
In net/ipv6/addrconf.c (ffffffff81b34f02)
Location: include/net/netlink.h:1228
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
```
```
In net/ipv6/route.c (ffffffff81b450d6)
Location: include/net/netlink.h:1228
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/seg6.c (ffffffff81b71f33)
Location: include/net/netlink.h:1228
Inline: True
Inline callers:
  - net/ipv6/seg6.c:__seg6_hmac_fill_info
  - net/ipv6/seg6.c:__seg6_hmac_fill_info
```
```
In net/ipv6/ip6mr.c (ffffffff81b7452b)
Location: include/net/netlink.h:1228
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81b93b93)
Location: include/net/netlink.h:1228
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81b9588d)
Location: include/net/netlink.h:1228
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/dcb/dcbnl.c (ffffffff81b99a10)
Location: include/net/netlink.h:1228
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_setdcbx
  - net/dcb/dcbnl.c:dcbnl_getdcbx
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_bcn_setcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_setall
  - net/dcb/dcbnl.c:dcbnl_setpfccfg
  - net/dcb/dcbnl.c:dcbnl_setstate
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_setpfcstate
  - net/dcb/dcbnl.c:dcbnl_getpfcstate
  - net/dcb/dcbnl.c:dcbnl_setnumtcs
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
  - net/dcb/dcbnl.c:dcbnl_getstate
```
```
In net/mptcp/diag.c (ffffffff81bb2c39)
Location: include/net/netlink.h:1228
Inline: True
Inline callers:
  - net/mptcp/diag.c:subflow_get_info
  - net/mptcp/diag.c:subflow_get_info
```
```
In net/mptcp/pm_netlink.c (ffffffff81bb2fec)
Location: include/net/netlink.h:1228
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
In drivers/net/tun.c (ffffffff81898297)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
```
```
In net/core/neighbour.c (ffffffff81a14474)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
```
```
In net/core/rtnetlink.c (ffffffff81a1f836)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_xdp_fill
```
```
In net/core/fib_rules.c (ffffffff81a43116)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:fib_nl_fill_rule
```
```
In net/core/drop_monitor.c (ffffffff81a500dd)
Location: include/net/netlink.h:1241
Inline: True
```
```
In net/core/devlink.c (ffffffff81a6558d)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_value_fill_one
  - net/core/devlink.c:devlink_nl_param_value_fill_one
  - net/core/devlink.c:devlink_resource_size_params_put
  - net/core/devlink.c:devlink_dpipe_header_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_nl_port_attrs_put
  - net/core/devlink.c:devlink_nl_port_attrs_put
  - net/core/devlink.c:devlink_nl_port_attrs_put
  - net/core/devlink.c:devlink_nl_fill
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
```
```
In net/sched/sch_api.c (ffffffff81a71510)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/ethtool/linkinfo.c (ffffffff81a91fa9)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - net/ethtool/linkinfo.c:linkinfo_fill_reply
  - net/ethtool/linkinfo.c:linkinfo_fill_reply
  - net/ethtool/linkinfo.c:linkinfo_fill_reply
  - net/ethtool/linkinfo.c:linkinfo_fill_reply
  - net/ethtool/linkinfo.c:linkinfo_fill_reply
```
```
In net/ethtool/linkmodes.c (ffffffff81a923a4)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - net/ethtool/linkmodes.c:linkmodes_fill_reply
  - net/ethtool/linkmodes.c:linkmodes_fill_reply
  - net/ethtool/linkmodes.c:linkmodes_fill_reply
  - net/ethtool/linkmodes.c:linkmodes_fill_reply
```
```
In net/ethtool/linkstate.c (ffffffff81a92b48)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - net/ethtool/linkstate.c:linkstate_fill_reply
  - net/ethtool/linkstate.c:linkstate_fill_reply
  - net/ethtool/linkstate.c:linkstate_fill_reply
```
```
In net/ethtool/coalesce.c (ffffffff81a94dcc)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - net/ethtool/coalesce.c:coalesce_fill_reply
  - net/ethtool/coalesce.c:coalesce_fill_reply
```
```
In net/ethtool/pause.c (ffffffff81a95689)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - net/ethtool/pause.c:pause_fill_reply
  - net/ethtool/pause.c:pause_fill_reply
  - net/ethtool/pause.c:pause_fill_reply
```
```
In net/ethtool/eee.c (ffffffff81a95b04)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - net/ethtool/eee.c:eee_fill_reply
  - net/ethtool/eee.c:eee_fill_reply
  - net/ethtool/eee.c:eee_fill_reply
```
```
In net/ethtool/cabletest.c (ffffffff81a96b67)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_cable_test_amplitude
  - net/ethtool/cabletest.c:ethnl_cable_test_fault_length
  - net/ethtool/cabletest.c:ethnl_cable_test_result
  - net/ethtool/cabletest.c:ethnl_cable_test_result
  - net/ethtool/cabletest.c:ethnl_cable_test_alloc
```
```
In net/ipv4/tcp.c (ffffffff81aba312)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81b074c0)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_opts_erspan
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_opts_erspan
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_opts_erspan
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_opts_geneve
```
```
In net/ipv4/ipmr.c (ffffffff81b0e21f)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_fill_table
  - net/ipv4/ipmr.c:ipmr_fill_table
  - net/ipv4/ipmr.c:ipmr_fill_table
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
```
```
In net/ipv6/addrconf.c (ffffffff81b43b27)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
```
```
In net/ipv6/route.c (ffffffff81b53a79)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/seg6.c (ffffffff81b80c93)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - net/ipv6/seg6.c:__seg6_hmac_fill_info
  - net/ipv6/seg6.c:__seg6_hmac_fill_info
```
```
In net/ipv6/ip6mr.c (ffffffff81b8329b)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81ba37d3)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81ba54e2)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/dcb/dcbnl.c (ffffffff81ba9710)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_setdcbx
  - net/dcb/dcbnl.c:dcbnl_getdcbx
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_bcn_setcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_setall
  - net/dcb/dcbnl.c:dcbnl_setpfccfg
  - net/dcb/dcbnl.c:dcbnl_setstate
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_setpfcstate
  - net/dcb/dcbnl.c:dcbnl_getpfcstate
  - net/dcb/dcbnl.c:dcbnl_setnumtcs
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
  - net/dcb/dcbnl.c:dcbnl_getstate
```
```
In net/mptcp/diag.c (ffffffff81bc706e)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - net/mptcp/diag.c:subflow_get_info
  - net/mptcp/diag.c:subflow_get_info
```
```
In net/mptcp/pm_netlink.c (ffffffff81bc747c)
Location: include/net/netlink.h:1241
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
In drivers/net/tun.c (ffffffff8187ab67)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
```
```
In net/core/neighbour.c (ffffffff819fae04)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
```
```
In net/core/rtnetlink.c (ffffffff81a068fe)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_xdp_fill
```
```
In net/core/fib_rules.c (ffffffff81a27e76)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:fib_nl_fill_rule
```
```
In net/core/drop_monitor.c (ffffffff81a34ec1)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_config_get
```
```
In net/core/devlink.c (ffffffff81a4ae4d)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_value_fill_one
  - net/core/devlink.c:devlink_nl_param_value_fill_one
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_attrs_put
  - net/core/devlink.c:devlink_nl_port_attrs_put
  - net/core/devlink.c:devlink_nl_port_attrs_put
  - net/core/devlink.c:devlink_nl_fill
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
```
```
In net/sched/sch_api.c (ffffffff81a59ed0)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/ethtool/linkinfo.c (ffffffff81a7b799)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - net/ethtool/linkinfo.c:linkinfo_fill_reply
  - net/ethtool/linkinfo.c:linkinfo_fill_reply
  - net/ethtool/linkinfo.c:linkinfo_fill_reply
  - net/ethtool/linkinfo.c:linkinfo_fill_reply
  - net/ethtool/linkinfo.c:linkinfo_fill_reply
```
```
In net/ethtool/linkmodes.c (ffffffff81a7bbd4)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - net/ethtool/linkmodes.c:linkmodes_fill_reply
  - net/ethtool/linkmodes.c:linkmodes_fill_reply
  - net/ethtool/linkmodes.c:linkmodes_fill_reply
  - net/ethtool/linkmodes.c:linkmodes_fill_reply
```
```
In net/ethtool/linkstate.c (ffffffff81a7c558)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - net/ethtool/linkstate.c:linkstate_fill_reply
  - net/ethtool/linkstate.c:linkstate_fill_reply
  - net/ethtool/linkstate.c:linkstate_fill_reply
```
```
In net/ethtool/coalesce.c (ffffffff81a7e829)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - net/ethtool/coalesce.c:coalesce_fill_reply
  - net/ethtool/coalesce.c:coalesce_fill_reply
```
```
In net/ethtool/pause.c (ffffffff81a7f059)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - net/ethtool/pause.c:pause_fill_reply
  - net/ethtool/pause.c:pause_fill_reply
  - net/ethtool/pause.c:pause_fill_reply
```
```
In net/ethtool/eee.c (ffffffff81a7f594)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - net/ethtool/eee.c:eee_fill_reply
  - net/ethtool/eee.c:eee_fill_reply
  - net/ethtool/eee.c:eee_fill_reply
```
```
In net/ethtool/cabletest.c (ffffffff81a80613)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_cable_test_amplitude
  - net/ethtool/cabletest.c:ethnl_cable_test_fault_length
  - net/ethtool/cabletest.c:ethnl_cable_test_result
  - net/ethtool/cabletest.c:ethnl_cable_test_result
  - net/ethtool/cabletest.c:ethnl_cable_test_alloc
```
```
In net/ethtool/fec.c (ffffffff81a814b8)
Location: include/net/netlink.h:1241
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff81aa5597)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af2c70)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
```
```
In net/ipv4/ipmr.c (ffffffff81b00a3e)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
```
```
In net/ipv6/addrconf.c (ffffffff81b31787)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
```
```
In net/ipv6/route.c (ffffffff81b4103b)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/seg6.c (ffffffff81b6fa37)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
```
In net/ipv6/ip6mr.c (ffffffff81b71f1d)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81b928f1)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81b9463d)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/dcb/dcbnl.c (ffffffff81b988a0)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_setdcbx
  - net/dcb/dcbnl.c:dcbnl_getdcbx
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_bcn_setcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_setall
  - net/dcb/dcbnl.c:dcbnl_setpfccfg
  - net/dcb/dcbnl.c:dcbnl_setstate
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_setpfcstate
  - net/dcb/dcbnl.c:dcbnl_getpfcstate
  - net/dcb/dcbnl.c:dcbnl_setnumtcs
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
  - net/dcb/dcbnl.c:dcbnl_getstate
```
```
In net/mptcp/diag.c (ffffffff81bb7d9d)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - net/mptcp/diag.c:subflow_get_info
  - net/mptcp/diag.c:subflow_get_info
```
```
In net/mptcp/pm_netlink.c (ffffffff81bbb7f7)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_event_addr_announced
  - net/mptcp/pm_netlink.c:mptcp_event_addr_removed
  - net/mptcp/pm_netlink.c:mptcp_event_put_token_and_ssk
  - net/mptcp/pm_netlink.c:mptcp_event_put_token_and_ssk
  - net/mptcp/pm_netlink.c:mptcp_event_add_subflow
  - net/mptcp/pm_netlink.c:mptcp_event_add_subflow
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
In drivers/net/tun.c (ffffffff8190c067)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
```
```
In net/core/neighbour.c (ffffffff81aaca44)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
```
```
In net/core/rtnetlink.c (ffffffff81ab8d4c)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_xdp_fill
```
```
In net/core/fib_rules.c (ffffffff81adcc16)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:fib_nl_fill_rule
```
```
In net/core/drop_monitor.c (ffffffff81aeaa91)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_config_get
```
```
In net/core/devlink.c (ffffffff81b034cd)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_value_fill_one
  - net/core/devlink.c:devlink_nl_param_value_fill_one
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_nl_port_function_attrs_put
  - net/core/devlink.c:devlink_nl_port_function_attrs_put
  - net/core/devlink.c:devlink_nl_port_attrs_put
  - net/core/devlink.c:devlink_nl_port_attrs_put
  - net/core/devlink.c:devlink_nl_port_attrs_put
  - net/core/devlink.c:devlink_nl_fill
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
```
```
In net/sched/sch_api.c (ffffffff81b12fa0)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/ethtool/linkinfo.c (ffffffff81b35b89)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - net/ethtool/linkinfo.c:linkinfo_fill_reply
  - net/ethtool/linkinfo.c:linkinfo_fill_reply
  - net/ethtool/linkinfo.c:linkinfo_fill_reply
  - net/ethtool/linkinfo.c:linkinfo_fill_reply
  - net/ethtool/linkinfo.c:linkinfo_fill_reply
```
```
In net/ethtool/linkmodes.c (ffffffff81b35f36)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - net/ethtool/linkmodes.c:linkmodes_fill_reply
  - net/ethtool/linkmodes.c:linkmodes_fill_reply
  - net/ethtool/linkmodes.c:linkmodes_fill_reply
  - net/ethtool/linkmodes.c:linkmodes_fill_reply
```
```
In net/ethtool/linkstate.c (ffffffff81b368af)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - net/ethtool/linkstate.c:linkstate_fill_reply
  - net/ethtool/linkstate.c:linkstate_fill_reply
  - net/ethtool/linkstate.c:linkstate_fill_reply
```
```
In net/ethtool/coalesce.c (ffffffff81b387f5)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - net/ethtool/coalesce.c:coalesce_put_bool
```
```
In net/ethtool/pause.c (ffffffff81b390b9)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - net/ethtool/pause.c:pause_fill_reply
  - net/ethtool/pause.c:pause_fill_reply
  - net/ethtool/pause.c:pause_fill_reply
```
```
In net/ethtool/eee.c (ffffffff81b394a4)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - net/ethtool/eee.c:eee_fill_reply
  - net/ethtool/eee.c:eee_fill_reply
  - net/ethtool/eee.c:eee_fill_reply
```
```
In net/ethtool/cabletest.c (ffffffff81b3a3e3)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_cable_test_amplitude
  - net/ethtool/cabletest.c:ethnl_cable_test_fault_length
  - net/ethtool/cabletest.c:ethnl_cable_test_result
  - net/ethtool/cabletest.c:ethnl_cable_test_result
  - net/ethtool/cabletest.c:ethnl_cable_test_alloc
```
```
In net/ethtool/fec.c (ffffffff81b3b238)
Location: include/net/netlink.h:1241
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff81b618e7)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81bb3180)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
```
```
In net/ipv4/ipmr.c (ffffffff81bbd9f1)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_fill_table
  - net/ipv4/ipmr.c:ipmr_fill_table
  - net/ipv4/ipmr.c:ipmr_fill_table
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
```
```
In net/ipv6/addrconf.c (ffffffff81bf7827)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
```
```
In net/ipv6/route.c (ffffffff81c08d0b)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/seg6.c (ffffffff81c37b87)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
```
In net/ipv6/ip6mr.c (ffffffff81c3c3cd)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81c5f091)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81c60e34)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/dcb/dcbnl.c (ffffffff81c654b3)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_setdcbx
  - net/dcb/dcbnl.c:dcbnl_getdcbx
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_bcn_setcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_setall
  - net/dcb/dcbnl.c:dcbnl_setpfccfg
  - net/dcb/dcbnl.c:dcbnl_setstate
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_setpfcstate
  - net/dcb/dcbnl.c:dcbnl_getpfcstate
  - net/dcb/dcbnl.c:dcbnl_setnumtcs
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
  - net/dcb/dcbnl.c:dcbnl_getstate
```
```
In net/mptcp/diag.c (ffffffff81c872ed)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - net/mptcp/diag.c:subflow_get_info
  - net/mptcp/diag.c:subflow_get_info
```
```
In net/mptcp/pm_netlink.c (ffffffff81c8b437)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_event_addr_announced
  - net/mptcp/pm_netlink.c:mptcp_event_addr_removed
  - net/mptcp/pm_netlink.c:mptcp_event_put_token_and_ssk
  - net/mptcp/pm_netlink.c:mptcp_event_put_token_and_ssk
  - net/mptcp/pm_netlink.c:mptcp_event_add_subflow
  - net/mptcp/pm_netlink.c:mptcp_event_add_subflow
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
In drivers/net/tun.c (ffffffff81a5fa67)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
```
```
In net/core/neighbour.c (ffffffff81c25a99)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
```
```
In net/core/rtnetlink.c (ffffffff81c33088)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_offload_xstats_fill
  - net/core/rtnetlink.c:rtnl_offload_xstats_fill
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_xdp_fill
```
```
In net/core/fib_rules.c (ffffffff81c5e19f)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:fib_nl_fill_rule
```
```
In net/core/drop_monitor.c (ffffffff81c6d295)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_config_get
```
```
In net/core/devlink.c (ffffffff81c84b3f)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_value_fill_one
  - net/core/devlink.c:devlink_nl_param_value_fill_one
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_nl_port_function_attrs_put
  - net/core/devlink.c:devlink_nl_port_function_attrs_put
  - net/core/devlink.c:devlink_nl_port_attrs_put
  - net/core/devlink.c:devlink_nl_port_attrs_put
  - net/core/devlink.c:devlink_nl_port_attrs_put
  - net/core/devlink.c:devlink_nl_fill
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
```
```
In net/sched/sch_api.c (ffffffff81c99bfb)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/ethtool/linkinfo.c (ffffffff81cc1459)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - net/ethtool/linkinfo.c:linkinfo_fill_reply
  - net/ethtool/linkinfo.c:linkinfo_fill_reply
  - net/ethtool/linkinfo.c:linkinfo_fill_reply
  - net/ethtool/linkinfo.c:linkinfo_fill_reply
  - net/ethtool/linkinfo.c:linkinfo_fill_reply
```
```
In net/ethtool/linkmodes.c (ffffffff81cc1826)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - net/ethtool/linkmodes.c:linkmodes_fill_reply
  - net/ethtool/linkmodes.c:linkmodes_fill_reply
  - net/ethtool/linkmodes.c:linkmodes_fill_reply
  - net/ethtool/linkmodes.c:linkmodes_fill_reply
```
```
In net/ethtool/linkstate.c (ffffffff81cc220b)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - net/ethtool/linkstate.c:linkstate_fill_reply
  - net/ethtool/linkstate.c:linkstate_fill_reply
  - net/ethtool/linkstate.c:linkstate_fill_reply
```
```
In net/ethtool/rings.c (ffffffff81cc377f)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - net/ethtool/rings.c:rings_fill_reply
  - net/ethtool/rings.c:rings_fill_reply
```
```
In net/ethtool/coalesce.c (ffffffff81cc4465)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - net/ethtool/coalesce.c:coalesce_put_bool
```
```
In net/ethtool/pause.c (ffffffff81cc4ea9)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - net/ethtool/pause.c:pause_fill_reply
  - net/ethtool/pause.c:pause_fill_reply
  - net/ethtool/pause.c:pause_fill_reply
```
```
In net/ethtool/eee.c (ffffffff81cc52b4)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - net/ethtool/eee.c:eee_fill_reply
  - net/ethtool/eee.c:eee_fill_reply
  - net/ethtool/eee.c:eee_fill_reply
```
```
In net/ethtool/cabletest.c (ffffffff81cc62fb)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_cable_test_amplitude
  - net/ethtool/cabletest.c:ethnl_cable_test_fault_length
  - net/ethtool/cabletest.c:ethnl_cable_test_result
  - net/ethtool/cabletest.c:ethnl_cable_test_result
  - net/ethtool/cabletest.c:ethnl_cable_test_alloc
```
```
In net/ethtool/fec.c (ffffffff81cc7157)
Location: include/net/netlink.h:1241
Inline: True
```
```
In net/ethtool/module.c (ffffffff81cc89b7)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - net/ethtool/module.c:module_fill_reply
  - net/ethtool/module.c:module_fill_reply
```
```
In net/ipv4/tcp.c (ffffffff81cf0328)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/devinet.c (ffffffff81d27367)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81d46990)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
```
```
In net/ipv4/ipmr.c (ffffffff81d522bd)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_fill_table
  - net/ipv4/ipmr.c:ipmr_fill_table
  - net/ipv4/ipmr.c:ipmr_fill_table
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
```
```
In net/ipv6/addrconf.c (ffffffff81d90cd4)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
```
```
In net/ipv6/route.c (ffffffff81da3837)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/seg6.c (ffffffff81dd5746)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
```
In net/ipv6/ip6mr.c (ffffffff81dda79f)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff81deb6ba)
Location: include/net/netlink.h:1241
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81e01445)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81e033ab)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/dcb/dcbnl.c (ffffffff81e0815d)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_setdcbx
  - net/dcb/dcbnl.c:dcbnl_getdcbx
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_bcn_setcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_setall
  - net/dcb/dcbnl.c:dcbnl_setpfccfg
  - net/dcb/dcbnl.c:dcbnl_setstate
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_setpfcstate
  - net/dcb/dcbnl.c:dcbnl_getpfcstate
  - net/dcb/dcbnl.c:dcbnl_setnumtcs
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
  - net/dcb/dcbnl.c:dcbnl_getstate
```
```
In net/mptcp/diag.c (ffffffff81e2db2f)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - net/mptcp/diag.c:subflow_get_info
  - net/mptcp/diag.c:subflow_get_info
```
```
In net/mptcp/pm_netlink.c (ffffffff81e32d5f)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_event
  - net/mptcp/pm_netlink.c:mptcp_event_addr_announced
  - net/mptcp/pm_netlink.c:mptcp_event_addr_removed
  - net/mptcp/pm_netlink.c:mptcp_event_put_token_and_ssk
  - net/mptcp/pm_netlink.c:mptcp_event_put_token_and_ssk
  - net/mptcp/pm_netlink.c:mptcp_event_add_subflow
  - net/mptcp/pm_netlink.c:mptcp_event_add_subflow
  - net/mptcp/pm_netlink.c:mptcp_nl_fill_addr
```
```
In net/mctp/device.c (ffffffff81e37f9e)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_fill_addrinfo
  - net/mctp/device.c:mctp_fill_addrinfo
```
```
In net/mctp/route.c (ffffffff81e3927e)
Location: include/net/netlink.h:1241
Inline: True
```
```
In net/mctp/neigh.c (ffffffff81e3b46f)
Location: include/net/netlink.h:1241
Inline: True
Inline callers:
  - net/mctp/neigh.c:mctp_rtm_getneigh
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
In drivers/net/tun.c (ffffffff81beaf57)
Location: include/net/netlink.h:1290
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
```
```
In net/core/neighbour.c (ffffffff81dd7cd9)
Location: include/net/netlink.h:1290
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
```
```
In net/core/rtnetlink.c (ffffffff81de64a8)
Location: include/net/netlink.h:1290
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_offload_xstats_fill
  - net/core/rtnetlink.c:rtnl_offload_xstats_fill
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_xdp_fill
```
```
In net/core/fib_rules.c (ffffffff81e149bf)
Location: include/net/netlink.h:1290
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:fib_nl_fill_rule
```
```
In net/core/drop_monitor.c (ffffffff81e24e95)
Location: include/net/netlink.h:1290
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_config_get
```
```
In net/core/devlink.c (ffffffff81e3ec9f)
Location: include/net/netlink.h:1290
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_nl_param_value_fill_one
  - net/core/devlink.c:devlink_nl_param_value_fill_one
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_fill
  - net/core/devlink.c:devlink_nl_port_attrs_put
  - net/core/devlink.c:devlink_nl_port_attrs_put
  - net/core/devlink.c:devlink_nl_port_attrs_put
  - net/core/devlink.c:devlink_nl_fill
  - net/core/devlink.c:devlink_reload_stats_put
  - net/core/devlink.c:devlink_reload_stats_put
```
```
In net/sched/sch_api.c (ffffffff81e55f2b)
Location: include/net/netlink.h:1290
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/ethtool/linkinfo.c (ffffffff81e801b9)
Location: include/net/netlink.h:1290
Inline: True
Inline callers:
  - net/ethtool/linkinfo.c:linkinfo_fill_reply
  - net/ethtool/linkinfo.c:linkinfo_fill_reply
  - net/ethtool/linkinfo.c:linkinfo_fill_reply
  - net/ethtool/linkinfo.c:linkinfo_fill_reply
  - net/ethtool/linkinfo.c:linkinfo_fill_reply
```
```
In net/ethtool/linkmodes.c (ffffffff81e805b6)
Location: include/net/netlink.h:1290
Inline: True
Inline callers:
  - net/ethtool/linkmodes.c:linkmodes_fill_reply
  - net/ethtool/linkmodes.c:linkmodes_fill_reply
  - net/ethtool/linkmodes.c:linkmodes_fill_reply
  - net/ethtool/linkmodes.c:linkmodes_fill_reply
  - net/ethtool/linkmodes.c:linkmodes_fill_reply
```
```
In net/ethtool/linkstate.c (ffffffff81e813c5)
Location: include/net/netlink.h:1290
Inline: True
Inline callers:
  - net/ethtool/linkstate.c:linkstate_fill_reply
  - net/ethtool/linkstate.c:linkstate_fill_reply
  - net/ethtool/linkstate.c:linkstate_fill_reply
```
```
In net/ethtool/rings.c (ffffffff81e82aff)
Location: include/net/netlink.h:1290
Inline: True
Inline callers:
  - net/ethtool/rings.c:rings_fill_reply
  - net/ethtool/rings.c:rings_fill_reply
```
```
In net/ethtool/coalesce.c (ffffffff81e838e5)
Location: include/net/netlink.h:1290
Inline: True
Inline callers:
  - net/ethtool/coalesce.c:coalesce_put_bool
```
```
In net/ethtool/pause.c (ffffffff81e843a9)
Location: include/net/netlink.h:1290
Inline: True
Inline callers:
  - net/ethtool/pause.c:pause_fill_reply
  - net/ethtool/pause.c:pause_fill_reply
  - net/ethtool/pause.c:pause_fill_reply
```
```
In net/ethtool/eee.c (ffffffff81e847d4)
Location: include/net/netlink.h:1290
Inline: True
Inline callers:
  - net/ethtool/eee.c:eee_fill_reply
  - net/ethtool/eee.c:eee_fill_reply
  - net/ethtool/eee.c:eee_fill_reply
```
```
In net/ethtool/cabletest.c (ffffffff81e8590b)
Location: include/net/netlink.h:1290
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_cable_test_amplitude
  - net/ethtool/cabletest.c:ethnl_cable_test_fault_length
  - net/ethtool/cabletest.c:ethnl_cable_test_result
  - net/ethtool/cabletest.c:ethnl_cable_test_result
  - net/ethtool/cabletest.c:ethnl_cable_test_alloc
```
```
In net/ethtool/fec.c (ffffffff81e867d7)
Location: include/net/netlink.h:1290
Inline: True
```
```
In net/ethtool/module.c (ffffffff81e881a7)
Location: include/net/netlink.h:1290
Inline: True
Inline callers:
  - net/ethtool/module.c:module_fill_reply
  - net/ethtool/module.c:module_fill_reply
```
```
In net/ipv4/tcp.c (ffffffff81eb3658)
Location: include/net/netlink.h:1290
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/devinet.c (ffffffff81eeed7c)
Location: include/net/netlink.h:1290
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f0fdb0)
Location: include/net/netlink.h:1290
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
```
```
In net/ipv4/ipmr.c (ffffffff81f1c31d)
Location: include/net/netlink.h:1290
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_fill_table
  - net/ipv4/ipmr.c:ipmr_fill_table
  - net/ipv4/ipmr.c:ipmr_fill_table
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
```
```
In net/ipv6/addrconf.c (ffffffff81f5f3f4)
Location: include/net/netlink.h:1290
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
```
```
In net/ipv6/route.c (ffffffff81f72c77)
Location: include/net/netlink.h:1290
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/seg6.c (ffffffff81fa6ed6)
Location: include/net/netlink.h:1290
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
```
In net/ipv6/ip6mr.c (ffffffff81fac4bf)
Location: include/net/netlink.h:1290
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
```
```
In net/ipv6/seg6_local.c (ffffffff81fbbfc6)
Location: include/net/netlink.h:1290
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:put_nla_flavors
  - net/ipv6/seg6_local.c:put_nla_flavors
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff81fbf30a)
Location: include/net/netlink.h:1290
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81fd6295)
Location: include/net/netlink.h:1290
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81fd832b)
Location: include/net/netlink.h:1290
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/dcb/dcbnl.c (ffffffff81fdd6cd)
Location: include/net/netlink.h:1290
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_setdcbx
  - net/dcb/dcbnl.c:dcbnl_getdcbx
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_bcn_setcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_setall
  - net/dcb/dcbnl.c:dcbnl_setpfccfg
  - net/dcb/dcbnl.c:dcbnl_setstate
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_setpfcstate
  - net/dcb/dcbnl.c:dcbnl_getpfcstate
  - net/dcb/dcbnl.c:dcbnl_setnumtcs
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
  - net/dcb/dcbnl.c:dcbnl_getstate
```
```
In net/mptcp/diag.c (ffffffff820060bf)
Location: include/net/netlink.h:1290
Inline: True
Inline callers:
  - net/mptcp/diag.c:subflow_get_info
  - net/mptcp/diag.c:subflow_get_info
```
```
In net/mptcp/pm_netlink.c (ffffffff8200b7bf)
Location: include/net/netlink.h:1290
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_event
  - net/mptcp/pm_netlink.c:mptcp_event_addr_announced
  - net/mptcp/pm_netlink.c:mptcp_event_addr_removed
  - net/mptcp/pm_netlink.c:mptcp_event_put_token_and_ssk
  - net/mptcp/pm_netlink.c:mptcp_event_put_token_and_ssk
  - net/mptcp/pm_netlink.c:mptcp_event_add_subflow
  - net/mptcp/pm_netlink.c:mptcp_event_add_subflow
  - net/mptcp/pm_netlink.c:mptcp_nl_fill_addr
```
```
In net/mctp/device.c (ffffffff820111ce)
Location: include/net/netlink.h:1290
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_fill_addrinfo
  - net/mctp/device.c:mctp_fill_addrinfo
```
```
In net/mctp/route.c (ffffffff8201253e)
Location: include/net/netlink.h:1290
Inline: True
```
```
In net/mctp/neigh.c (ffffffff82014b2f)
Location: include/net/netlink.h:1290
Inline: True
Inline callers:
  - net/mctp/neigh.c:mctp_rtm_getneigh
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
In drivers/net/tun.c (ffffffff81c43397)
Location: include/net/netlink.h:1291
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
```
```
In net/core/neighbour.c (ffffffff81e48aa1)
Location: include/net/netlink.h:1291
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
```
```
In net/core/rtnetlink.c (ffffffff81e5747e)
Location: include/net/netlink.h:1291
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_offload_xstats_fill
  - net/core/rtnetlink.c:rtnl_offload_xstats_fill
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_xdp_fill
```
```
In net/core/fib_rules.c (ffffffff81e882cf)
Location: include/net/netlink.h:1291
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:fib_nl_fill_rule
```
```
In net/core/drop_monitor.c (ffffffff81e9a3d5)
Location: include/net/netlink.h:1291
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_config_get
```
```
In net/sched/sch_api.c (ffffffff81eb22b6)
Location: include/net/netlink.h:1291
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/ethtool/linkinfo.c (ffffffff81edc969)
Location: include/net/netlink.h:1291
Inline: True
Inline callers:
  - net/ethtool/linkinfo.c:linkinfo_fill_reply
  - net/ethtool/linkinfo.c:linkinfo_fill_reply
  - net/ethtool/linkinfo.c:linkinfo_fill_reply
  - net/ethtool/linkinfo.c:linkinfo_fill_reply
  - net/ethtool/linkinfo.c:linkinfo_fill_reply
```
```
In net/ethtool/linkmodes.c (ffffffff81edcda6)
Location: include/net/netlink.h:1291
Inline: True
Inline callers:
  - net/ethtool/linkmodes.c:linkmodes_fill_reply
  - net/ethtool/linkmodes.c:linkmodes_fill_reply
  - net/ethtool/linkmodes.c:linkmodes_fill_reply
  - net/ethtool/linkmodes.c:linkmodes_fill_reply
  - net/ethtool/linkmodes.c:linkmodes_fill_reply
```
```
In net/ethtool/linkstate.c (ffffffff81eddad5)
Location: include/net/netlink.h:1291
Inline: True
Inline callers:
  - net/ethtool/linkstate.c:linkstate_fill_reply
  - net/ethtool/linkstate.c:linkstate_fill_reply
  - net/ethtool/linkstate.c:linkstate_fill_reply
```
```
In net/ethtool/rings.c (ffffffff81edf2eb)
Location: include/net/netlink.h:1291
Inline: True
Inline callers:
  - net/ethtool/rings.c:rings_fill_reply
  - net/ethtool/rings.c:rings_fill_reply
  - net/ethtool/rings.c:rings_fill_reply
```
```
In net/ethtool/coalesce.c (ffffffff81ee0015)
Location: include/net/netlink.h:1291
Inline: True
Inline callers:
  - net/ethtool/coalesce.c:coalesce_put_bool
```
```
In net/ethtool/pause.c (ffffffff81ee0f19)
Location: include/net/netlink.h:1291
Inline: True
Inline callers:
  - net/ethtool/pause.c:pause_fill_reply
  - net/ethtool/pause.c:pause_fill_reply
  - net/ethtool/pause.c:pause_fill_reply
```
```
In net/ethtool/eee.c (ffffffff81ee11b4)
Location: include/net/netlink.h:1291
Inline: True
Inline callers:
  - net/ethtool/eee.c:eee_fill_reply
  - net/ethtool/eee.c:eee_fill_reply
  - net/ethtool/eee.c:eee_fill_reply
```
```
In net/ethtool/cabletest.c (ffffffff81ee2237)
Location: include/net/netlink.h:1291
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_cable_test_amplitude
  - net/ethtool/cabletest.c:ethnl_cable_test_fault_length
  - net/ethtool/cabletest.c:ethnl_cable_test_result
  - net/ethtool/cabletest.c:ethnl_cable_test_result
  - net/ethtool/cabletest.c:ethnl_cable_test_alloc
```
```
In net/ethtool/fec.c (ffffffff81ee3227)
Location: include/net/netlink.h:1291
Inline: True
```
```
In net/ethtool/mm.c (ffffffff81ee580b)
Location: include/net/netlink.h:1291
Inline: True
Inline callers:
  - net/ethtool/mm.c:mm_fill_reply
  - net/ethtool/mm.c:mm_fill_reply
  - net/ethtool/mm.c:mm_fill_reply
  - net/ethtool/mm.c:mm_fill_reply
  - net/ethtool/mm.c:mm_fill_reply
```
```
In net/ethtool/module.c (ffffffff81ee5e17)
Location: include/net/netlink.h:1291
Inline: True
Inline callers:
  - net/ethtool/module.c:module_fill_reply
  - net/ethtool/module.c:module_fill_reply
```
```
In net/ethtool/plca.c (ffffffff81ee66ef)
Location: include/net/netlink.h:1291
Inline: True
Inline callers:
  - net/ethtool/plca.c:plca_get_status_fill_reply
  - net/ethtool/plca.c:plca_get_cfg_fill_reply
```
```
In net/ipv4/tcp.c (ffffffff81f11d78)
Location: include/net/netlink.h:1291
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/devinet.c (ffffffff81f4e73c)
Location: include/net/netlink.h:1291
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f6faa0)
Location: include/net/netlink.h:1291
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
```
```
In net/ipv4/ipmr.c (ffffffff81f7bdfd)
Location: include/net/netlink.h:1291
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_fill_table
  - net/ipv4/ipmr.c:ipmr_fill_table
  - net/ipv4/ipmr.c:ipmr_fill_table
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
```
```
In net/ipv6/addrconf.c (ffffffff81fbf122)
Location: include/net/netlink.h:1291
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
```
```
In net/ipv6/route.c (ffffffff81fd2d6d)
Location: include/net/netlink.h:1291
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/seg6.c (ffffffff82007736)
Location: include/net/netlink.h:1291
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
```
In net/ipv6/ip6mr.c (ffffffff8200cc5f)
Location: include/net/netlink.h:1291
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
```
```
In net/ipv6/seg6_local.c (ffffffff8201c8c6)
Location: include/net/netlink.h:1291
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:put_nla_flavors
  - net/ipv6/seg6_local.c:put_nla_flavors
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff8202029a)
Location: include/net/netlink.h:1291
Inline: True
```
```
In net/devlink/leftover.c (ffffffff8203f37f)
Location: include/net/netlink.h:1291
Inline: True
Inline callers:
  - net/devlink/leftover.c:devlink_nl_trap_fill
  - net/devlink/leftover.c:devlink_nl_trap_fill
  - net/devlink/leftover.c:devlink_nl_param_value_fill_one
  - net/devlink/leftover.c:devlink_nl_param_value_fill_one
  - net/devlink/leftover.c:devlink_dpipe_table_put
  - net/devlink/leftover.c:devlink_dpipe_action_put
  - net/devlink/leftover.c:devlink_dpipe_match_put
  - net/devlink/leftover.c:devlink_nl_port_fill
  - net/devlink/leftover.c:devlink_nl_port_fill
  - net/devlink/leftover.c:devlink_nl_port_attrs_put
  - net/devlink/leftover.c:devlink_nl_port_attrs_put
  - net/devlink/leftover.c:devlink_nl_port_attrs_put
```
```
In net/devlink/dev.c (ffffffff820438ce)
Location: include/net/netlink.h:1291
Inline: True
Inline callers:
  - net/devlink/dev.c:devlink_nl_fill
  - net/devlink/dev.c:devlink_reload_stats_put
  - net/devlink/dev.c:devlink_reload_stats_put
```
```
In net/devlink/health.c (ffffffff82047197)
Location: include/net/netlink.h:1291
Inline: True
Inline callers:
  - net/devlink/health.c:devlink_fmsg_prepare_skb
  - net/devlink/health.c:devlink_fmsg_prepare_skb
  - net/devlink/health.c:devlink_fmsg_prepare_skb
  - net/devlink/health.c:devlink_nl_health_reporter_fill
  - net/devlink/health.c:devlink_nl_health_reporter_fill
  - net/devlink/health.c:devlink_nl_health_reporter_fill
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff82051f55)
Location: include/net/netlink.h:1291
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff82053ffb)
Location: include/net/netlink.h:1291
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/dcb/dcbnl.c (ffffffff820598fd)
Location: include/net/netlink.h:1291
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_setdcbx
  - net/dcb/dcbnl.c:dcbnl_getdcbx
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_bcn_setcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_setall
  - net/dcb/dcbnl.c:dcbnl_setpfccfg
  - net/dcb/dcbnl.c:dcbnl_setstate
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_setpfcstate
  - net/dcb/dcbnl.c:dcbnl_getpfcstate
  - net/dcb/dcbnl.c:dcbnl_setnumtcs
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
  - net/dcb/dcbnl.c:dcbnl_getstate
```
```
In net/mptcp/diag.c (ffffffff82082443)
Location: include/net/netlink.h:1291
Inline: True
Inline callers:
  - net/mptcp/diag.c:subflow_get_info
  - net/mptcp/diag.c:subflow_get_info
```
```
In net/mptcp/pm_netlink.c (ffffffff82087b7d)
Location: include/net/netlink.h:1291
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_event
  - net/mptcp/pm_netlink.c:mptcp_event_addr_announced
  - net/mptcp/pm_netlink.c:mptcp_event_addr_removed
  - net/mptcp/pm_netlink.c:mptcp_event_put_token_and_ssk
  - net/mptcp/pm_netlink.c:mptcp_event_put_token_and_ssk
  - net/mptcp/pm_netlink.c:mptcp_event_add_subflow
  - net/mptcp/pm_netlink.c:mptcp_event_add_subflow
  - net/mptcp/pm_netlink.c:mptcp_nl_fill_addr
```
```
In net/mctp/device.c (ffffffff8208df8e)
Location: include/net/netlink.h:1291
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_fill_addrinfo
  - net/mctp/device.c:mctp_fill_addrinfo
```
```
In net/mctp/route.c (ffffffff8208f32e)
Location: include/net/netlink.h:1291
Inline: True
```
```
In net/mctp/neigh.c (ffffffff8209194f)
Location: include/net/netlink.h:1291
Inline: True
Inline callers:
  - net/mctp/neigh.c:mctp_rtm_getneigh
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
In drivers/net/netkit.c (ffffffff81ce50c2)
Location: include/net/netlink.h:1335
Inline: True
Inline callers:
  - drivers/net/netkit.c:netkit_fill_info
```
```
In drivers/net/tun.c (ffffffff81cf85c7)
Location: include/net/netlink.h:1335
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
```
```
In net/core/neighbour.c (ffffffff81f07661)
Location: include/net/netlink.h:1335
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
```
```
In net/core/rtnetlink.c (ffffffff81f167d7)
Location: include/net/netlink.h:1335
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_offload_xstats_fill
  - net/core/rtnetlink.c:rtnl_offload_xstats_fill
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_xdp_fill
```
```
In net/core/fib_rules.c (ffffffff81f4a2df)
Location: include/net/netlink.h:1335
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:fib_nl_fill_rule
```
```
In net/core/drop_monitor.c (ffffffff81f5cb05)
Location: include/net/netlink.h:1335
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_config_get
```
```
In net/sched/sch_api.c (ffffffff81f74d66)
Location: include/net/netlink.h:1335
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/ethtool/linkinfo.c (ffffffff81fa0739)
Location: include/net/netlink.h:1335
Inline: True
Inline callers:
  - net/ethtool/linkinfo.c:linkinfo_fill_reply
  - net/ethtool/linkinfo.c:linkinfo_fill_reply
  - net/ethtool/linkinfo.c:linkinfo_fill_reply
  - net/ethtool/linkinfo.c:linkinfo_fill_reply
  - net/ethtool/linkinfo.c:linkinfo_fill_reply
```
```
In net/ethtool/linkmodes.c (ffffffff81fa0b76)
Location: include/net/netlink.h:1335
Inline: True
Inline callers:
  - net/ethtool/linkmodes.c:linkmodes_fill_reply
  - net/ethtool/linkmodes.c:linkmodes_fill_reply
  - net/ethtool/linkmodes.c:linkmodes_fill_reply
  - net/ethtool/linkmodes.c:linkmodes_fill_reply
  - net/ethtool/linkmodes.c:linkmodes_fill_reply
```
```
In net/ethtool/linkstate.c (ffffffff81fa1905)
Location: include/net/netlink.h:1335
Inline: True
Inline callers:
  - net/ethtool/linkstate.c:linkstate_fill_reply
  - net/ethtool/linkstate.c:linkstate_fill_reply
  - net/ethtool/linkstate.c:linkstate_fill_reply
```
```
In net/ethtool/rings.c (ffffffff81fa316b)
Location: include/net/netlink.h:1335
Inline: True
Inline callers:
  - net/ethtool/rings.c:rings_fill_reply
  - net/ethtool/rings.c:rings_fill_reply
  - net/ethtool/rings.c:rings_fill_reply
```
```
In net/ethtool/coalesce.c (ffffffff81fa3eb5)
Location: include/net/netlink.h:1335
Inline: True
Inline callers:
  - net/ethtool/coalesce.c:coalesce_put_bool
```
```
In net/ethtool/pause.c (ffffffff81fa4da9)
Location: include/net/netlink.h:1335
Inline: True
Inline callers:
  - net/ethtool/pause.c:pause_fill_reply
  - net/ethtool/pause.c:pause_fill_reply
  - net/ethtool/pause.c:pause_fill_reply
```
```
In net/ethtool/eee.c (ffffffff81fa5044)
Location: include/net/netlink.h:1335
Inline: True
Inline callers:
  - net/ethtool/eee.c:eee_fill_reply
  - net/ethtool/eee.c:eee_fill_reply
  - net/ethtool/eee.c:eee_fill_reply
```
```
In net/ethtool/cabletest.c (ffffffff81fa60c7)
Location: include/net/netlink.h:1335
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_cable_test_amplitude
  - net/ethtool/cabletest.c:ethnl_cable_test_fault_length
  - net/ethtool/cabletest.c:ethnl_cable_test_result
  - net/ethtool/cabletest.c:ethnl_cable_test_result
  - net/ethtool/cabletest.c:ethnl_cable_test_alloc
```
```
In net/ethtool/fec.c (ffffffff81fa7007)
Location: include/net/netlink.h:1335
Inline: True
```
```
In net/ethtool/mm.c (ffffffff81fa95eb)
Location: include/net/netlink.h:1335
Inline: True
Inline callers:
  - net/ethtool/mm.c:mm_fill_reply
  - net/ethtool/mm.c:mm_fill_reply
  - net/ethtool/mm.c:mm_fill_reply
  - net/ethtool/mm.c:mm_fill_reply
  - net/ethtool/mm.c:mm_fill_reply
```
```
In net/ethtool/module.c (ffffffff81fa9bf7)
Location: include/net/netlink.h:1335
Inline: True
Inline callers:
  - net/ethtool/module.c:module_fill_reply
  - net/ethtool/module.c:module_fill_reply
```
```
In net/ethtool/plca.c (ffffffff81faa33f)
Location: include/net/netlink.h:1335
Inline: True
Inline callers:
  - net/ethtool/plca.c:plca_get_status_fill_reply
  - net/ethtool/plca.c:plca_get_cfg_fill_reply
```
```
In net/ipv4/tcp.c (ffffffff81fd6018)
Location: include/net/netlink.h:1335
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/devinet.c (ffffffff8201487f)
Location: include/net/netlink.h:1335
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_fill_ifaddr
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff820361d0)
Location: include/net/netlink.h:1335
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
```
```
In net/ipv4/ipmr.c (ffffffff820424ed)
Location: include/net/netlink.h:1335
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_fill_table
  - net/ipv4/ipmr.c:ipmr_fill_table
  - net/ipv4/ipmr.c:ipmr_fill_table
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
```
```
In net/ipv6/addrconf.c (ffffffff8208c5ba)
Location: include/net/netlink.h:1335
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifaddr
```
```
In net/ipv6/route.c (ffffffff820a067d)
Location: include/net/netlink.h:1335
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/seg6.c (ffffffff820d65c6)
Location: include/net/netlink.h:1335
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
```
In net/ipv6/ip6mr.c (ffffffff820dbc2f)
Location: include/net/netlink.h:1335
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
```
```
In net/ipv6/seg6_local.c (ffffffff820eb6f6)
Location: include/net/netlink.h:1335
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:put_nla_flavors
  - net/ipv6/seg6_local.c:put_nla_flavors
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff820ef3ca)
Location: include/net/netlink.h:1335
Inline: True
```
```
In net/devlink/dev.c (ffffffff82102f59)
Location: include/net/netlink.h:1335
Inline: True
Inline callers:
  - net/devlink/dev.c:devlink_nl_fill
  - net/devlink/dev.c:devlink_reload_stats_put
  - net/devlink/dev.c:devlink_reload_stats_put
```
```
In net/devlink/port.c (ffffffff821066e5)
Location: include/net/netlink.h:1335
Inline: True
Inline callers:
  - net/devlink/port.c:devlink_nl_port_function_attrs_put
  - net/devlink/port.c:devlink_nl_port_function_attrs_put
  - net/devlink/port.c:devlink_nl_port_attrs_put
  - net/devlink/port.c:devlink_nl_port_attrs_put
  - net/devlink/port.c:devlink_nl_port_attrs_put
```
```
In net/devlink/sb.c (ffffffff8210886a)
Location: include/net/netlink.h:1335
Inline: True
```
```
In net/devlink/dpipe.c (ffffffff8210b9ae)
Location: include/net/netlink.h:1335
Inline: True
Inline callers:
  - net/devlink/dpipe.c:devlink_dpipe_table_put
  - net/devlink/dpipe.c:devlink_dpipe_action_put
  - net/devlink/dpipe.c:devlink_dpipe_match_put
```
```
In net/devlink/resource.c (ffffffff8210c5a0)
Location: include/net/netlink.h:1335
Inline: True
```
```
In net/devlink/param.c (ffffffff8210daf9)
Location: include/net/netlink.h:1335
Inline: True
Inline callers:
  - net/devlink/param.c:devlink_nl_param_value_fill_one
  - net/devlink/param.c:devlink_nl_param_value_fill_one
```
```
In net/devlink/health.c (ffffffff821130c7)
Location: include/net/netlink.h:1335
Inline: True
Inline callers:
  - net/devlink/health.c:devlink_fmsg_prepare_skb
  - net/devlink/health.c:devlink_fmsg_prepare_skb
  - net/devlink/health.c:devlink_fmsg_prepare_skb
  - net/devlink/health.c:devlink_nl_health_reporter_fill
  - net/devlink/health.c:devlink_nl_health_reporter_fill
  - net/devlink/health.c:devlink_nl_health_reporter_fill
```
```
In net/devlink/trap.c (ffffffff82115f2d)
Location: include/net/netlink.h:1335
Inline: True
Inline callers:
  - net/devlink/trap.c:devlink_nl_trap_fill
  - net/devlink/trap.c:devlink_nl_trap_fill
```
```
In net/devlink/linecard.c (ffffffff82119971)
Location: include/net/netlink.h:1335
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff82124735)
Location: include/net/netlink.h:1335
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff821267db)
Location: include/net/netlink.h:1335
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/dcb/dcbnl.c (ffffffff8212c480)
Location: include/net/netlink.h:1335
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_setdcbx
  - net/dcb/dcbnl.c:dcbnl_getdcbx
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_getapptrust
  - net/dcb/dcbnl.c:dcbnl_bcn_setcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_setall
  - net/dcb/dcbnl.c:dcbnl_setpfccfg
  - net/dcb/dcbnl.c:dcbnl_setstate
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_setpfcstate
  - net/dcb/dcbnl.c:dcbnl_getpfcstate
  - net/dcb/dcbnl.c:dcbnl_setnumtcs
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
  - net/dcb/dcbnl.c:dcbnl_getstate
```
```
In net/mptcp/diag.c (ffffffff82157a8d)
Location: include/net/netlink.h:1335
Inline: True
Inline callers:
  - net/mptcp/diag.c:subflow_get_info
  - net/mptcp/diag.c:subflow_get_info
```
```
In net/mptcp/pm_netlink.c (ffffffff8215d3b5)
Location: include/net/netlink.h:1335
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_event
  - net/mptcp/pm_netlink.c:mptcp_event_addr_announced
  - net/mptcp/pm_netlink.c:mptcp_event_addr_removed
  - net/mptcp/pm_netlink.c:mptcp_event_put_token_and_ssk
  - net/mptcp/pm_netlink.c:mptcp_event_put_token_and_ssk
  - net/mptcp/pm_netlink.c:mptcp_event_add_subflow
  - net/mptcp/pm_netlink.c:mptcp_event_add_subflow
  - net/mptcp/pm_netlink.c:mptcp_nl_fill_addr
```
```
In net/mctp/device.c (ffffffff8216444e)
Location: include/net/netlink.h:1335
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_fill_addrinfo
  - net/mctp/device.c:mctp_fill_addrinfo
```
```
In net/mctp/route.c (ffffffff8216580e)
Location: include/net/netlink.h:1335
Inline: True
```
```
In net/mctp/neigh.c (ffffffff82167eef)
Location: include/net/netlink.h:1335
Inline: True
Inline callers:
  - net/mctp/neigh.c:mctp_rtm_getneigh
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
In drivers/net/tun.c (ffff8000109daf0c)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
```
```
In net/core/neighbour.c (ffff800010be402c)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
```
```
In net/core/rtnetlink.c (ffff800010bf1778)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/fib_rules.c (ffff800010c12e4c)
Location: include/net/netlink.h:1176
Inline: True
```
```
In net/core/drop_monitor.c (ffff800010c1b718)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_config_get
```
```
In net/core/devlink.c (ffff800010c2c08c)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_fill
```
```
In net/sched/sch_api.c (ffff800010c3d30c)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/ipv4/tcp.c (ffff800010c76654)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/ip_tunnel_core.c (ffff800010cc1fd4)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
```
```
In net/ipv4/ipmr.c (ffff800010cc9fbc)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (ffff800010d02768)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
```
```
In net/ipv6/route.c (ffff800010d0dbf4)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/seg6.c (ffff800010d416a0)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
```
In net/ipv6/ip6mr.c (ffff800010d43f5c)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/netlabel/netlabel_unlabeled.c (ffff800010d679ec)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffff800010d698a0)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/dcb/dcbnl.c (ffff800010d6e8c8)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_setdcbx
  - net/dcb/dcbnl.c:dcbnl_getdcbx
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_bcn_setcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_setall
  - net/dcb/dcbnl.c:dcbnl_setpfccfg
  - net/dcb/dcbnl.c:dcbnl_setstate
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_setpfcstate
  - net/dcb/dcbnl.c:dcbnl_getpfcstate
  - net/dcb/dcbnl.c:dcbnl_setnumtcs
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
  - net/dcb/dcbnl.c:dcbnl_getstate
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
In drivers/net/tun.c (c0ac2154)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
```
```
In net/core/neighbour.c (c0cfe524)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
```
```
In net/core/rtnetlink.c (c0d09f40)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/fib_rules.c (c0d2a734)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:fib_nl_fill_rule
```
```
In net/core/drop_monitor.c (c0d33920)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_config_get
```
```
In net/core/devlink.c (c0d42c14)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_fill
```
```
In net/sched/sch_api.c (c0d4edd4)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/ipv4/tcp.c (c0d84d74)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/ip_tunnel_core.c (c0dcd66c)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
```
```
In net/ipv4/ipmr.c (c0dd5f64)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (c0e08578)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
```
```
In net/ipv6/route.c (c0e144dc)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/seg6.c (c0e44090)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
```
In net/ipv6/ip6mr.c (c0e45ccc)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/netlabel/netlabel_unlabeled.c (c0e66384)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (c0e67e98)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/dcb/dcbnl.c (c0e6c824)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_setdcbx
  - net/dcb/dcbnl.c:dcbnl_getdcbx
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_bcn_setcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_setall
  - net/dcb/dcbnl.c:dcbnl_setpfccfg
  - net/dcb/dcbnl.c:dcbnl_setstate
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_setpfcstate
  - net/dcb/dcbnl.c:dcbnl_getpfcstate
  - net/dcb/dcbnl.c:dcbnl_setnumtcs
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
  - net/dcb/dcbnl.c:dcbnl_getstate
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
In drivers/net/tun.c (c000000000a9d7dc)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
```
```
In net/core/neighbour.c (c000000000cc74b0)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
```
```
In net/core/rtnetlink.c (c000000000cd62d8)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/fib_rules.c (c000000000cffdd4)
Location: include/net/netlink.h:1176
Inline: True
```
```
In net/core/drop_monitor.c (c000000000d0c650)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_config_get
```
```
In net/core/devlink.c (c000000000d22b88)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_fill
```
```
In net/sched/sch_api.c (c000000000d36b4c)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/ipv4/tcp.c (c000000000d7e1dc)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/ip_tunnel_core.c (c000000000ddd570)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
```
```
In net/ipv4/ipmr.c (c000000000de9458)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (c000000000e2a014)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
```
```
In net/ipv6/route.c (c000000000e39a5c)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/seg6.c (c000000000e75f14)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
```
In net/ipv6/ip6mr.c (c000000000e78b08)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/netlabel/netlabel_unlabeled.c (c000000000ea42e4)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (c000000000ea6750)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/dcb/dcbnl.c (c000000000ead204)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_setdcbx
  - net/dcb/dcbnl.c:dcbnl_getdcbx
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_bcn_setcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_setall
  - net/dcb/dcbnl.c:dcbnl_setpfccfg
  - net/dcb/dcbnl.c:dcbnl_setstate
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_setpfcstate
  - net/dcb/dcbnl.c:dcbnl_getpfcstate
  - net/dcb/dcbnl.c:dcbnl_setnumtcs
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
  - net/dcb/dcbnl.c:dcbnl_getstate
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
In drivers/net/tun.c (ffffffe000625efa)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
```
```
In net/core/neighbour.c (ffffffe00076aa20)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
```
```
In net/core/rtnetlink.c (ffffffe0007734d2)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/fib_rules.c (ffffffe00078e82c)
Location: include/net/netlink.h:1176
Inline: True
```
```
In net/core/drop_monitor.c (ffffffe000795d16)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_config_get
```
```
In net/core/devlink.c (ffffffe0007a36a6)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_fill
```
```
In net/sched/sch_api.c (ffffffe0007ad7bc)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/ipv4/tcp.c (ffffffe0007d97ce)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/ip_tunnel_core.c (ffffffe000817518)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
```
```
In net/ipv4/ipmr.c (ffffffe00081f496)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (ffffffe00084ab70)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
```
```
In net/ipv6/route.c (ffffffe00085587c)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/seg6.c (ffffffe00087cd78)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
```
In net/ipv6/ip6mr.c (ffffffe00087ea66)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffe00089affe)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffe00089c792)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/dcb/dcbnl.c (ffffffe0008a073a)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_setdcbx
  - net/dcb/dcbnl.c:dcbnl_getdcbx
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_bcn_setcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_setall
  - net/dcb/dcbnl.c:dcbnl_setpfccfg
  - net/dcb/dcbnl.c:dcbnl_setstate
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_setpfcstate
  - net/dcb/dcbnl.c:dcbnl_getpfcstate
  - net/dcb/dcbnl.c:dcbnl_setnumtcs
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
  - net/dcb/dcbnl.c:dcbnl_getstate
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
In drivers/net/tun.c (ffffffff81785487)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
```
```
In net/core/neighbour.c (ffffffff818e4156)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
```
```
In net/core/rtnetlink.c (ffffffff818efa5c)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/fib_rules.c (ffffffff8190c53b)
Location: include/net/netlink.h:1176
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff819156b3)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_config_get
```
```
In net/core/devlink.c (ffffffff819238b6)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_fill
```
```
In net/sched/sch_api.c (ffffffff81930c3b)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/ipv4/tcp.c (ffffffff8196394b)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff819a8a36)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
```
```
In net/ipv4/ipmr.c (ffffffff819b1240)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (ffffffff819de912)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
```
```
In net/ipv6/route.c (ffffffff819ea1ff)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/seg6.c (ffffffff81a17797)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
```
In net/ipv6/ip6mr.c (ffffffff81a192b3)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81a376b3)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81a3919d)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/dcb/dcbnl.c (ffffffff81a3d2e2)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_setdcbx
  - net/dcb/dcbnl.c:dcbnl_getdcbx
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_bcn_setcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_setall
  - net/dcb/dcbnl.c:dcbnl_setpfccfg
  - net/dcb/dcbnl.c:dcbnl_setstate
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_setpfcstate
  - net/dcb/dcbnl.c:dcbnl_getpfcstate
  - net/dcb/dcbnl.c:dcbnl_setnumtcs
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
  - net/dcb/dcbnl.c:dcbnl_getstate
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
In drivers/net/tun.c (ffffffff81764dd7)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
```
```
In drivers/net/vxlan.c (ffffffff8176d969)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - drivers/net/vxlan.c:vxlan_fill_info
  - drivers/net/vxlan.c:vxlan_fill_info
  - drivers/net/vxlan.c:vxlan_fill_info
  - drivers/net/vxlan.c:vxlan_fill_info
  - drivers/net/vxlan.c:vxlan_fill_info
  - drivers/net/vxlan.c:vxlan_fill_info
  - drivers/net/vxlan.c:vxlan_fill_info
  - drivers/net/vxlan.c:vxlan_fill_info
  - drivers/net/vxlan.c:vxlan_fill_info
  - drivers/net/vxlan.c:vxlan_fill_info
  - drivers/net/vxlan.c:vxlan_fill_info
  - drivers/net/vxlan.c:vxlan_fill_info
  - drivers/net/vxlan.c:vxlan_fill_info
  - drivers/net/vxlan.c:vxlan_fill_info
  - drivers/net/vxlan.c:vxlan_fill_info
```
```
In net/core/neighbour.c (ffffffff8189df96)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
```
```
In net/core/rtnetlink.c (ffffffff818a989c)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/fib_rules.c (ffffffff818c62fb)
Location: include/net/netlink.h:1176
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff818cf463)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_config_get
```
```
In net/core/devlink.c (ffffffff818dd666)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_fill
```
```
In net/sched/sch_api.c (ffffffff818ea73b)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/ipv4/tcp.c (ffffffff8191d43b)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff819624f6)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
```
```
In net/ipv4/ipmr.c (ffffffff8196d870)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (ffffffff8199b6d2)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
```
```
In net/ipv6/route.c (ffffffff819a6fbf)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/seg6.c (ffffffff819d4557)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
```
In net/ipv6/ip6mr.c (ffffffff819d6073)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff819f42d3)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff819f5dbd)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/dcb/dcbnl.c (ffffffff819f9ed2)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_setdcbx
  - net/dcb/dcbnl.c:dcbnl_getdcbx
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_bcn_setcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_setall
  - net/dcb/dcbnl.c:dcbnl_setpfccfg
  - net/dcb/dcbnl.c:dcbnl_setstate
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_setpfcstate
  - net/dcb/dcbnl.c:dcbnl_getpfcstate
  - net/dcb/dcbnl.c:dcbnl_setnumtcs
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
  - net/dcb/dcbnl.c:dcbnl_getstate
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
In drivers/net/tun.c (ffffffff817b5837)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
```
```
In net/core/neighbour.c (ffffffff81935186)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
```
```
In net/core/rtnetlink.c (ffffffff81940a8c)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/fib_rules.c (ffffffff8195d56b)
Location: include/net/netlink.h:1176
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff819666e3)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_config_get
```
```
In net/core/devlink.c (ffffffff81974a46)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_fill
```
```
In net/sched/sch_api.c (ffffffff81981dcb)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/netfilter/nf_conntrack_proto_tcp.c (ffffffff819a521b)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_proto_tcp.c:tcp_to_nlattr
  - net/netfilter/nf_conntrack_proto_tcp.c:tcp_to_nlattr
  - net/netfilter/nf_conntrack_proto_tcp.c:tcp_to_nlattr
```
```
In net/netfilter/nf_conntrack_proto_icmp.c (ffffffff819a7674)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_proto_icmp.c:icmp_tuple_to_nlattr
  - net/netfilter/nf_conntrack_proto_icmp.c:icmp_tuple_to_nlattr
```
```
In net/netfilter/nf_conntrack_proto_icmpv6.c (ffffffff819a86a4)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_proto_icmpv6.c:icmpv6_tuple_to_nlattr
  - net/netfilter/nf_conntrack_proto_icmpv6.c:icmpv6_tuple_to_nlattr
```
```
In net/netfilter/nf_conntrack_proto_dccp.c (ffffffff819a9ac5)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_proto_dccp.c:dccp_to_nlattr
  - net/netfilter/nf_conntrack_proto_dccp.c:dccp_to_nlattr
```
```
In net/netfilter/nf_conntrack_proto_sctp.c (ffffffff819aa6b5)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_proto_sctp.c:sctp_to_nlattr
```
```
In net/netfilter/nf_conntrack_netlink.c (ffffffff819acde1)
Location: include/net/netlink.h:1176
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff819ce11b)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81a132d6)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
```
```
In net/ipv4/ipmr.c (ffffffff81a1bae0)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (ffffffff81a49392)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
```
```
In net/ipv6/route.c (ffffffff81a54c7f)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/seg6.c (ffffffff81a82217)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
```
In net/ipv6/ip6mr.c (ffffffff81a83d33)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81aa3563)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81aa504d)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/dcb/dcbnl.c (ffffffff81aa9192)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_setdcbx
  - net/dcb/dcbnl.c:dcbnl_getdcbx
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_bcn_setcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_setall
  - net/dcb/dcbnl.c:dcbnl_setpfccfg
  - net/dcb/dcbnl.c:dcbnl_setstate
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_setpfcstate
  - net/dcb/dcbnl.c:dcbnl_getpfcstate
  - net/dcb/dcbnl.c:dcbnl_setnumtcs
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
  - net/dcb/dcbnl.c:dcbnl_getstate
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
In drivers/net/tun.c (ffffffff817cfbd7)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
  - drivers/net/tun.c:tun_fill_info
```
```
In net/core/neighbour.c (ffffffff81956896)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_fill_info
```
```
In net/core/rtnetlink.c (ffffffff8196239c)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/core/rtnetlink.c:ndo_dflt_bridge_getlink
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
  - net/core/rtnetlink.c:rtnl_fill_ifinfo
```
```
In net/core/fib_rules.c (ffffffff8197f7bb)
Location: include/net/netlink.h:1176
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff81988973)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_config_get
```
```
In net/core/devlink.c (ffffffff81996f36)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_nl_trap_fill
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_fmsg_prepare_skb
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_nl_param_fill
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_resource_put
  - net/core/devlink.c:devlink_dpipe_table_put
  - net/core/devlink.c:devlink_dpipe_action_put
  - net/core/devlink.c:devlink_dpipe_match_put
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit
  - net/core/devlink.c:devlink_nl_fill
```
```
In net/sched/sch_api.c (ffffffff819a430b)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_fill_qdisc
```
```
In net/ipv4/tcp.c (ffffffff819d7cab)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
  - net/ipv4/tcp.c:tcp_get_timestamping_opt_stats
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81a1dca6)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
```
```
In net/ipv4/ipmr.c (ffffffff81a269f6)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/ipv6/addrconf.c (ffffffff81a552b2)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifinfo
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
```
```
In net/ipv6/route.c (ffffffff81a60c6f)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
```
In net/ipv6/seg6.c (ffffffff81a8eb27)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_genl_dumphmac
  - net/ipv6/seg6.c:seg6_genl_dumphmac
```
```
In net/ipv6/ip6mr.c (ffffffff81a90658)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81aaf983)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81ab13d6)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list
```
```
In net/dcb/dcbnl.c (ffffffff81ab5502)
Location: include/net/netlink.h:1176
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_setdcbx
  - net/dcb/dcbnl.c:dcbnl_getdcbx
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_cee_pg_fill
  - net/dcb/dcbnl.c:dcbnl_ieee_fill
  - net/dcb/dcbnl.c:dcbnl_bcn_setcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_setall
  - net/dcb/dcbnl.c:dcbnl_setpfccfg
  - net/dcb/dcbnl.c:dcbnl_setstate
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_setpfcstate
  - net/dcb/dcbnl.c:dcbnl_getpfcstate
  - net/dcb/dcbnl.c:dcbnl_setnumtcs
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
  - net/dcb/dcbnl.c:dcbnl_getstate
```
</details>
</li>
</ul>

## Differences
