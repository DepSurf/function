# Function: <code>nla_parse_nested_deprecated</code>

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
In net/core/neighbour.c (ffffffff81910c8d)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_set
```
```
In net/core/rtnetlink.c (ffffffff8191dab6)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/lwt_bpf.c (ffffffff81942e02)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_build_state
```
```
In net/sched/sch_api.c (ffffffff819596ad)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_get_stab
```
```
In net/sched/act_api.c (ffffffff8196312f)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/sched/act_api.c:find_dump_kind
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_action_init
  - net/sched/act_api.c:tcf_action_init_1
```
```
In net/sched/ematch.c (ffffffff81966248)
Location: include/net/netlink.h:1161
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff819b9aed)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff819d2314)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
```
```
In net/ipv6/addrconf.c (ffffffff81a07cdb)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_validate_link_af
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a4c596)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
```
```
In net/ipv6/seg6_local.c (ffffffff81a4da21)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_build_state
  - net/ipv6/seg6_local.c:parse_nla_bpf
```
```
In net/dcb/dcbnl.c (ffffffff81a673d2)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_bcn_setcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_setpfccfg
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_setnumtcs
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
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
In net/core/neighbour.c (ffffffff81943a5d)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_set
```
```
In net/core/rtnetlink.c (ffffffff819500e6)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/lwt_bpf.c (ffffffff81977db2)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_build_state
```
```
In net/sched/sch_api.c (ffffffff8198fb4d)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_get_stab
```
```
In net/sched/act_api.c (ffffffff81999caf)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/sched/act_api.c:find_dump_kind
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_action_init
  - net/sched/act_api.c:tcf_action_init_1
```
```
In net/sched/ematch.c (ffffffff8199ccd8)
Location: include/net/netlink.h:1161
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff819f1ded)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81a08e84)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
```
```
In net/ipv6/addrconf.c (ffffffff81a3e84b)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_validate_link_af
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a83166)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
```
```
In net/ipv6/seg6_local.c (ffffffff81a845f1)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_build_state
  - net/ipv6/seg6_local.c:parse_nla_bpf
```
```
In net/dcb/dcbnl.c (ffffffff81a9def2)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_bcn_setcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_setpfccfg
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_setnumtcs
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
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
In net/core/neighbour.c (ffffffff81a147c5)
Location: include/net/netlink.h:1213
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_set
```
```
In net/core/rtnetlink.c (ffffffff81a1d0a7)
Location: include/net/netlink.h:1213
Inline: True
Inline callers:
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/lwt_bpf.c (ffffffff81a4d0f7)
Location: include/net/netlink.h:1213
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_build_state
  - net/core/lwt_bpf.c:bpf_parse_prog
```
```
In net/sched/sch_api.c (ffffffff81a6812d)
Location: include/net/netlink.h:1213
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_get_stab
```
```
In net/sched/act_api.c (ffffffff81a7311f)
Location: include/net/netlink.h:1213
Inline: True
Inline callers:
  - net/sched/act_api.c:find_dump_kind
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tcf_action_init
  - net/sched/act_api.c:tcf_action_init_1
```
```
In net/sched/ematch.c (ffffffff81a75f35)
Location: include/net/netlink.h:1213
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff81adfacd)
Location: include/net/netlink.h:1213
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af93e2)
Location: include/net/netlink.h:1213
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
```
```
In net/ipv6/addrconf.c (ffffffff81b3e929)
Location: include/net/netlink.h:1213
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_validate_link_af
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b7e00c)
Location: include/net/netlink.h:1213
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
```
```
In net/ipv6/seg6_local.c (ffffffff81b7f654)
Location: include/net/netlink.h:1213
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_build_state
  - net/ipv6/seg6_local.c:parse_nla_bpf
```
```
In net/dcb/dcbnl.c (ffffffff81b999b0)
Location: include/net/netlink.h:1213
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_bcn_setcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_setpfccfg
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_setnumtcs
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
```
```
In net/mptcp/pm_netlink.c (ffffffff81bb3165)
Location: include/net/netlink.h:1213
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
In net/core/neighbour.c (ffffffff81a14ad5)
Location: include/net/netlink.h:1226
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_set
```
```
In net/core/rtnetlink.c (ffffffff81a1d5a7)
Location: include/net/netlink.h:1226
Inline: True
Inline callers:
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/lwt_bpf.c (ffffffff81a52db7)
Location: include/net/netlink.h:1226
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_build_state
  - net/core/lwt_bpf.c:bpf_parse_prog
```
```
In net/sched/sch_api.c (ffffffff81a7083d)
Location: include/net/netlink.h:1226
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_get_stab
```
```
In net/sched/act_api.c (ffffffff81a7bcdf)
Location: include/net/netlink.h:1226
Inline: True
Inline callers:
  - net/sched/act_api.c:find_dump_kind
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tcf_action_init
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tc_action_load_ops
```
```
In net/sched/ematch.c (ffffffff81a7ece5)
Location: include/net/netlink.h:1226
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff81aec94d)
Location: include/net/netlink.h:1226
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81b06052)
Location: include/net/netlink.h:1226
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
```
```
In net/ipv6/addrconf.c (ffffffff81b4d4b9)
Location: include/net/netlink.h:1226
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_validate_link_af
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b8d01c)
Location: include/net/netlink.h:1226
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
```
```
In net/ipv6/seg6_local.c (ffffffff81b8f8c4)
Location: include/net/netlink.h:1226
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_build_state
  - net/ipv6/seg6_local.c:parse_nla_bpf
```
```
In net/dcb/dcbnl.c (ffffffff81ba96b0)
Location: include/net/netlink.h:1226
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_bcn_setcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_setpfccfg
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_setnumtcs
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
```
```
In net/mptcp/pm_netlink.c (ffffffff81bc7605)
Location: include/net/netlink.h:1226
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
In net/core/neighbour.c (ffffffff819fb5d5)
Location: include/net/netlink.h:1226
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_set
```
```
In net/core/rtnetlink.c (ffffffff81a04377)
Location: include/net/netlink.h:1226
Inline: True
Inline callers:
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/lwt_bpf.c (ffffffff81a385b9)
Location: include/net/netlink.h:1226
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_build_state
  - net/core/lwt_bpf.c:bpf_parse_prog
```
```
In net/sched/sch_api.c (ffffffff81a5913d)
Location: include/net/netlink.h:1226
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_get_stab
```
```
In net/sched/act_api.c (ffffffff81a6491f)
Location: include/net/netlink.h:1226
Inline: True
Inline callers:
  - net/sched/act_api.c:find_dump_kind
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tcf_action_init
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tc_action_load_ops
```
```
In net/sched/ematch.c (ffffffff81a67b35)
Location: include/net/netlink.h:1226
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff81ad687d)
Location: include/net/netlink.h:1226
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af18af)
Location: include/net/netlink.h:1226
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
```
```
In net/ipv6/addrconf.c (ffffffff81b3b363)
Location: include/net/netlink.h:1226
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_validate_link_af
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b7becc)
Location: include/net/netlink.h:1226
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
```
```
In net/ipv6/seg6_local.c (ffffffff81b7e494)
Location: include/net/netlink.h:1226
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_build_state
  - net/ipv6/seg6_local.c:parse_nla_counters
  - net/ipv6/seg6_local.c:parse_nla_bpf
```
```
In net/dcb/dcbnl.c (ffffffff81b98840)
Location: include/net/netlink.h:1226
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_bcn_setcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_setpfccfg
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_setnumtcs
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
```
```
In net/mptcp/pm_netlink.c (ffffffff81bb8aa4)
Location: include/net/netlink.h:1226
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
In drivers/net/wwan/wwan_core.c (ffffffff8191aaa4)
Location: include/net/netlink.h:1226
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
```
```
In net/core/neighbour.c (ffffffff81aad90c)
Location: include/net/netlink.h:1226
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_set
```
```
In net/core/rtnetlink.c (ffffffff81ab6963)
Location: include/net/netlink.h:1226
Inline: True
Inline callers:
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/lwt_bpf.c (ffffffff81aee429)
Location: include/net/netlink.h:1226
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_build_state
  - net/core/lwt_bpf.c:bpf_parse_prog
```
```
In net/sched/sch_api.c (ffffffff81b1242d)
Location: include/net/netlink.h:1226
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_get_stab
```
```
In net/sched/act_api.c (ffffffff81b1dbef)
Location: include/net/netlink.h:1226
Inline: True
Inline callers:
  - net/sched/act_api.c:find_dump_kind
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tcf_action_init
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tc_action_load_ops
```
```
In net/sched/ematch.c (ffffffff81b210a5)
Location: include/net/netlink.h:1226
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff81b96503)
Location: include/net/netlink.h:1226
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81bb1dbf)
Location: include/net/netlink.h:1226
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
```
```
In net/ipv6/addrconf.c (ffffffff81c01b63)
Location: include/net/netlink.h:1226
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_validate_link_af
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81c46d8c)
Location: include/net/netlink.h:1226
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
```
```
In net/ipv6/seg6_local.c (ffffffff81c49ed4)
Location: include/net/netlink.h:1226
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_build_state
  - net/ipv6/seg6_local.c:parse_nla_counters
  - net/ipv6/seg6_local.c:parse_nla_bpf
```
```
In net/dcb/dcbnl.c (ffffffff81c65434)
Location: include/net/netlink.h:1226
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_bcn_setcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_setpfccfg
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_setnumtcs
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
```
```
In net/mptcp/pm_netlink.c (ffffffff81c88074)
Location: include/net/netlink.h:1226
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
In drivers/net/wwan/wwan_core.c (ffffffff81a6fef0)
Location: include/net/netlink.h:1226
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
```
```
In net/core/neighbour.c (ffffffff81c26571)
Location: include/net/netlink.h:1226
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_set
```
```
In net/core/rtnetlink.c (ffffffff81c306d1)
Location: include/net/netlink.h:1226
Inline: True
Inline callers:
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/lwt_bpf.c (ffffffff81c71314)
Location: include/net/netlink.h:1226
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_build_state
  - net/core/lwt_bpf.c:bpf_parse_prog
```
```
In net/sched/sch_api.c (ffffffff81c99798)
Location: include/net/netlink.h:1226
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_get_stab
```
```
In net/sched/act_api.c (ffffffff81ca51e7)
Location: include/net/netlink.h:1226
Inline: True
Inline callers:
  - net/sched/act_api.c:find_dump_kind
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tcf_action_init
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tc_action_load_ops
```
```
In net/sched/ematch.c (ffffffff81ca9010)
Location: include/net/netlink.h:1226
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_tree_validate
```
```
In net/ipv4/devinet.c (ffffffff81d26993)
Location: include/net/netlink.h:1226
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81d454e5)
Location: include/net/netlink.h:1226
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
```
```
In net/ipv6/addrconf.c (ffffffff81d9b896)
Location: include/net/netlink.h:1226
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_validate_link_af
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81de609e)
Location: include/net/netlink.h:1226
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
```
```
In net/ipv6/seg6_local.c (ffffffff81de9776)
Location: include/net/netlink.h:1226
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_build_state
  - net/ipv6/seg6_local.c:parse_nla_counters
  - net/ipv6/seg6_local.c:parse_nla_bpf
```
```
In net/dcb/dcbnl.c (ffffffff81e080de)
Location: include/net/netlink.h:1226
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_bcn_setcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_setpfccfg
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_setnumtcs
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
```
```
In net/mptcp/pm_netlink.c (ffffffff81e2e988)
Location: include/net/netlink.h:1226
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_parse_pm_addr_attr
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
In drivers/net/wwan/wwan_core.c (ffffffff81c02d80)
Location: include/net/netlink.h:1275
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
```
```
In net/core/neighbour.c (ffffffff81dd8f65)
Location: include/net/netlink.h:1275
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_set
```
```
In net/core/rtnetlink.c (ffffffff81de3a02)
Location: include/net/netlink.h:1275
Inline: True
Inline callers:
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/lwt_bpf.c (ffffffff81e293c4)
Location: include/net/netlink.h:1275
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_build_state
  - net/core/lwt_bpf.c:bpf_parse_prog
```
```
In net/sched/sch_api.c (ffffffff81e55ab8)
Location: include/net/netlink.h:1275
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_get_stab
```
```
In net/sched/act_api.c (ffffffff81e61ca7)
Location: include/net/netlink.h:1275
Inline: True
Inline callers:
  - net/sched/act_api.c:find_dump_kind
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tcf_action_init
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tc_action_load_ops
```
```
In net/sched/ematch.c (ffffffff81e65f20)
Location: include/net/netlink.h:1275
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_tree_validate
```
```
In net/ipv4/devinet.c (ffffffff81eee323)
Location: include/net/netlink.h:1275
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f0e885)
Location: include/net/netlink.h:1275
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
```
```
In net/ipv6/addrconf.c (ffffffff81f6a4e6)
Location: include/net/netlink.h:1275
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_validate_link_af
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81fb8a3e)
Location: include/net/netlink.h:1275
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
```
```
In net/ipv6/seg6_local.c (ffffffff81fbcb56)
Location: include/net/netlink.h:1275
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_build_state
  - net/ipv6/seg6_local.c:parse_nla_flavors
  - net/ipv6/seg6_local.c:parse_nla_counters
  - net/ipv6/seg6_local.c:parse_nla_bpf
```
```
In net/dcb/dcbnl.c (ffffffff81fdd64e)
Location: include/net/netlink.h:1275
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_bcn_setcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_setpfccfg
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_setnumtcs
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
```
```
In net/mptcp/pm_netlink.c (ffffffff82006b18)
Location: include/net/netlink.h:1275
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_parse_pm_addr_attr
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
In drivers/net/wwan/wwan_core.c (ffffffff81c68430)
Location: include/net/netlink.h:1276
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
```
```
In net/core/neighbour.c (ffffffff81e49cce)
Location: include/net/netlink.h:1276
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_set
```
```
In net/core/rtnetlink.c (ffffffff81e54ee2)
Location: include/net/netlink.h:1276
Inline: True
Inline callers:
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/lwt_bpf.c (ffffffff81e9e9f4)
Location: include/net/netlink.h:1276
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_build_state
  - net/core/lwt_bpf.c:bpf_parse_prog
```
```
In net/sched/sch_api.c (ffffffff81eb1358)
Location: include/net/netlink.h:1276
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_get_stab
```
```
In net/sched/act_api.c (ffffffff81ebe367)
Location: include/net/netlink.h:1276
Inline: True
Inline callers:
  - net/sched/act_api.c:find_dump_kind
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tcf_action_init
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tc_action_load_ops
```
```
In net/sched/ematch.c (ffffffff81ec1e60)
Location: include/net/netlink.h:1276
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_tree_validate
```
```
In net/ipv4/devinet.c (ffffffff81f4dce3)
Location: include/net/netlink.h:1276
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f6e545)
Location: include/net/netlink.h:1276
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
```
```
In net/ipv6/addrconf.c (ffffffff81fca526)
Location: include/net/netlink.h:1276
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_validate_link_af
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff8201919e)
Location: include/net/netlink.h:1276
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
```
```
In net/ipv6/seg6_local.c (ffffffff8201dc36)
Location: include/net/netlink.h:1276
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_build_state
  - net/ipv6/seg6_local.c:parse_nla_flavors
  - net/ipv6/seg6_local.c:parse_nla_counters
  - net/ipv6/seg6_local.c:parse_nla_bpf
```
```
In net/dcb/dcbnl.c (ffffffff8205987e)
Location: include/net/netlink.h:1276
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_bcn_setcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_setpfccfg
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_setnumtcs
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
```
```
In net/mptcp/pm_netlink.c (ffffffff82082eb8)
Location: include/net/netlink.h:1276
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_parse_pm_addr_attr
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
In net/core/neighbour.c (ffffffff81f089ee)
Location: include/net/netlink.h:1320
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_set
```
```
In net/core/rtnetlink.c (ffffffff81f14252)
Location: include/net/netlink.h:1320
Inline: True
Inline callers:
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/lwt_bpf.c (ffffffff81f61164)
Location: include/net/netlink.h:1320
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_build_state
  - net/core/lwt_bpf.c:bpf_parse_prog
```
```
In net/sched/sch_api.c (ffffffff81f73df5)
Location: include/net/netlink.h:1320
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_get_stab
```
```
In net/sched/act_api.c (ffffffff81f8157d)
Location: include/net/netlink.h:1320
Inline: True
Inline callers:
  - net/sched/act_api.c:find_dump_kind
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tcf_action_init
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tc_action_load_ops
```
```
In net/sched/ematch.c (ffffffff81f851a0)
Location: include/net/netlink.h:1320
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_tree_validate
```
```
In net/ipv4/devinet.c (ffffffff82013e13)
Location: include/net/netlink.h:1320
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff82034c65)
Location: include/net/netlink.h:1320
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
```
```
In net/ipv6/addrconf.c (ffffffff82097cc6)
Location: include/net/netlink.h:1320
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_validate_link_af
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff820e816e)
Location: include/net/netlink.h:1320
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
```
```
In net/ipv6/seg6_local.c (ffffffff820ecc16)
Location: include/net/netlink.h:1320
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_build_state
  - net/ipv6/seg6_local.c:parse_nla_flavors
  - net/ipv6/seg6_local.c:parse_nla_counters
  - net/ipv6/seg6_local.c:parse_nla_bpf
```
```
In net/dcb/dcbnl.c (ffffffff8212c3fe)
Location: include/net/netlink.h:1320
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_bcn_setcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_setpfccfg
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_setnumtcs
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
```
```
In net/mptcp/pm_netlink.c (ffffffff82158532)
Location: include/net/netlink.h:1320
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_parse_pm_addr_attr
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
In net/core/neighbour.c (ffff800010be6934)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_set
```
```
In net/core/rtnetlink.c (ffff800010bf1d84)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/lwt_bpf.c (ffff800010c1e618)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_build_state
```
```
In net/sched/sch_api.c (ffff800010c3bad4)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_get_stab
```
```
In net/sched/act_api.c (ffff800010c469c8)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/sched/act_api.c:find_dump_kind
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_action_init
  - net/sched/act_api.c:tcf_action_init_1
```
```
In net/sched/ematch.c (ffff800010c4a204)
Location: include/net/netlink.h:1161
Inline: True
```
```
In net/ipv4/devinet.c (ffff800010ca7fb0)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/ip_tunnel_core.c (ffff800010cc21c8)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
```
```
In net/ipv6/addrconf.c (ffff800010cff81c)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_validate_link_af
```
```
In net/ipv6/seg6_iptunnel.c (ffff800010d4ef80)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
```
```
In net/ipv6/seg6_local.c (ffff800010d505cc)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_build_state
  - net/ipv6/seg6_local.c:parse_nla_bpf
```
```
In net/dcb/dcbnl.c (ffff800010d6e858)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_bcn_setcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_setpfccfg
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_setnumtcs
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
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
In net/core/neighbour.c (c0d0097c)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_set
```
```
In net/core/rtnetlink.c (c0d0a638)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:linkinfo_to_kind_ops
```
```
In net/core/lwt_bpf.c (c0d36668)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_build_state
  - net/core/lwt_bpf.c:bpf_parse_prog
```
```
In net/sched/sch_api.c (c0d4dacc)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_get_stab
```
```
In net/sched/act_api.c (c0d57ab4)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/sched/act_api.c:find_dump_kind
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tcf_action_init
  - net/sched/act_api.c:tcf_action_init_1
```
```
In net/sched/ematch.c (c0d5add0)
Location: include/net/netlink.h:1161
Inline: True
```
```
In net/ipv4/devinet.c (c0db2954)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/ip_tunnel_core.c (c0dcd8a0)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
```
```
In net/ipv6/addrconf.c (c0e07d90)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_validate_link_af
```
```
In net/ipv6/seg6_iptunnel.c (c0e4fd0c)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
```
```
In net/ipv6/seg6_local.c (c0e51158)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_build_state
  - net/ipv6/seg6_local.c:parse_nla_bpf
```
```
In net/dcb/dcbnl.c (c0e6c7a8)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_bcn_setcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_setpfccfg
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_setnumtcs
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
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
In net/core/neighbour.c (c000000000cc6110)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_set
```
```
In net/core/rtnetlink.c (c000000000cd6a64)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/lwt_bpf.c (c000000000d10610)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_build_state
```
```
In net/sched/sch_api.c (c000000000d353a0)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_get_stab
```
```
In net/sched/act_api.c (c000000000d433f8)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/sched/act_api.c:find_dump_kind
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_action_init
  - net/sched/act_api.c:tcf_action_init_1
```
```
In net/sched/ematch.c (c000000000d47d20)
Location: include/net/netlink.h:1161
Inline: True
```
```
In net/ipv4/devinet.c (c000000000db9e70)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/ip_tunnel_core.c (c000000000ddd7e4)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
```
```
In net/ipv6/addrconf.c (c000000000e29200)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_validate_link_af
```
```
In net/ipv6/seg6_iptunnel.c (c000000000e862a0)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
```
```
In net/ipv6/seg6_local.c (c000000000e88130)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_build_state
  - net/ipv6/seg6_local.c:parse_nla_bpf
```
```
In net/dcb/dcbnl.c (c000000000ead150)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_bcn_setcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_setpfccfg
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_setnumtcs
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
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
In net/core/neighbour.c (ffffffe000769e56)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_set
```
```
In net/core/rtnetlink.c (ffffffe0007739f0)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/lwt_bpf.c (ffffffe000798308)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_build_state
```
```
In net/sched/sch_api.c (ffffffe0007ac770)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_get_stab
```
```
In net/sched/act_api.c (ffffffe0007b4d96)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/sched/act_api.c:find_dump_kind
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_action_init
  - net/sched/act_api.c:tcf_action_init_1
```
```
In net/sched/ematch.c (ffffffe0007b75ec)
Location: include/net/netlink.h:1161
Inline: True
```
```
In net/ipv4/devinet.c (ffffffe000801552)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/ip_tunnel_core.c (ffffffe000817682)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
```
```
In net/ipv6/addrconf.c (ffffffe00084a09c)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_validate_link_af
```
```
In net/ipv6/seg6_iptunnel.c (ffffffe00088780c)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
```
```
In net/ipv6/seg6_local.c (ffffffe000888b9a)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_build_state
  - net/ipv6/seg6_local.c:parse_nla_bpf
```
```
In net/dcb/dcbnl.c (ffffffe0008a06e6)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_bcn_setcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_setpfccfg
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_setnumtcs
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
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
In net/core/neighbour.c (ffffffff818e3a2d)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_set
```
```
In net/core/rtnetlink.c (ffffffff818f00b6)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/lwt_bpf.c (ffffffff81917c22)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_build_state
```
```
In net/sched/sch_api.c (ffffffff8192f9bd)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_get_stab
```
```
In net/sched/act_api.c (ffffffff81939b1f)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/sched/act_api.c:find_dump_kind
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_action_init
  - net/sched/act_api.c:tcf_action_init_1
```
```
In net/sched/ematch.c (ffffffff8193cb48)
Location: include/net/netlink.h:1161
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff81991b8d)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff819a8c24)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
```
```
In net/ipv6/addrconf.c (ffffffff819ddedb)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_validate_link_af
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a227f6)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
```
```
In net/ipv6/seg6_local.c (ffffffff81a23c81)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_build_state
  - net/ipv6/seg6_local.c:parse_nla_bpf
```
```
In net/dcb/dcbnl.c (ffffffff81a3d282)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_bcn_setcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_setpfccfg
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_setnumtcs
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
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
In net/core/neighbour.c (ffffffff8189d86d)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_set
```
```
In net/core/rtnetlink.c (ffffffff818a9ef6)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/lwt_bpf.c (ffffffff818d19d2)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_build_state
```
```
In net/sched/sch_api.c (ffffffff818e94bd)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_get_stab
```
```
In net/sched/act_api.c (ffffffff818f361f)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/sched/act_api.c:find_dump_kind
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_action_init
  - net/sched/act_api.c:tcf_action_init_1
```
```
In net/sched/ematch.c (ffffffff818f6648)
Location: include/net/netlink.h:1161
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff8194b64d)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff819626e4)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
```
```
In net/ipv6/addrconf.c (ffffffff8199ac9b)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_validate_link_af
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819df5b6)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
```
```
In net/ipv6/seg6_local.c (ffffffff819e0a41)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_build_state
  - net/ipv6/seg6_local.c:parse_nla_bpf
```
```
In net/dcb/dcbnl.c (ffffffff819f9e72)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_bcn_setcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_setpfccfg
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_setnumtcs
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
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
In net/core/neighbour.c (ffffffff81934a5d)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_set
```
```
In net/core/rtnetlink.c (ffffffff819410e6)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/lwt_bpf.c (ffffffff81968db2)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_build_state
```
```
In net/sched/sch_api.c (ffffffff81980b4d)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_get_stab
```
```
In net/sched/act_api.c (ffffffff8198acaf)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/sched/act_api.c:find_dump_kind
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_action_init
  - net/sched/act_api.c:tcf_action_init_1
```
```
In net/sched/ematch.c (ffffffff8198dcd8)
Location: include/net/netlink.h:1161
Inline: True
```
```
In net/netfilter/nfnetlink_queue.c (ffffffff81999a0f)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/netfilter/nfnetlink_queue.c:nfqnl_recv_verdict
```
```
In net/netfilter/nf_conntrack_proto_tcp.c (ffffffff819a53a8)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_proto_tcp.c:nlattr_to_tcp
```
```
In net/netfilter/nf_conntrack_proto_dccp.c (ffffffff819a9974)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_proto_dccp.c:nlattr_to_dccp
```
```
In net/netfilter/nf_conntrack_proto_sctp.c (ffffffff819aa7b4)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_proto_sctp.c:nlattr_to_sctp
```
```
In net/netfilter/nf_conntrack_netlink.c (ffffffff819ad8d8)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_glue_attach_expect
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_glue_parse
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_change_synproxy
  - net/netfilter/nf_conntrack_netlink.c:change_seq_adj
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_change_protoinfo
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_parse_tuple
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_parse_tuple
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_parse_tuple_proto
```
```
In net/ipv4/devinet.c (ffffffff819fc42d)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81a134c4)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
```
```
In net/ipv6/addrconf.c (ffffffff81a4895b)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_validate_link_af
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a8d276)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
```
```
In net/ipv6/seg6_local.c (ffffffff81a8e701)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_build_state
  - net/ipv6/seg6_local.c:parse_nla_bpf
```
```
In net/dcb/dcbnl.c (ffffffff81aa9132)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_bcn_setcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_setpfccfg
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_setnumtcs
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
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
In net/core/neighbour.c (ffffffff81955dcd)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_set
```
```
In net/core/rtnetlink.c (ffffffff819629e6)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/lwt_bpf.c (ffffffff8198b192)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_build_state
```
```
In net/sched/sch_api.c (ffffffff819a30cd)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_get_stab
```
```
In net/sched/act_api.c (ffffffff819ad50f)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/sched/act_api.c:find_dump_kind
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_action_init
  - net/sched/act_api.c:tcf_action_init_1
```
```
In net/sched/ematch.c (ffffffff819b0578)
Location: include/net/netlink.h:1161
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff81a0679d)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81a1de94)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
```
```
In net/ipv6/addrconf.c (ffffffff81a54a8b)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_validate_link_af
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a99f66)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
```
```
In net/ipv6/seg6_local.c (ffffffff81a9b471)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_build_state
  - net/ipv6/seg6_local.c:parse_nla_bpf
```
```
In net/dcb/dcbnl.c (ffffffff81ab54a2)
Location: include/net/netlink.h:1161
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_getfeatcfg
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_bcn_setcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_getcfg
  - net/dcb/dcbnl.c:dcbnl_setpfccfg
  - net/dcb/dcbnl.c:dcbnl_setapp
  - net/dcb/dcbnl.c:dcbnl_getapp
  - net/dcb/dcbnl.c:dcbnl_setnumtcs
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_getcap
  - net/dcb/dcbnl.c:dcbnl_getpfccfg
```
</details>
</li>
</ul>

## Differences
