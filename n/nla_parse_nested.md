# Function: <code>nla_parse_nested</code>

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
In net/core/neighbour.c (ffffffff81727ff4)
Location: include/net/netlink.h:733
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_set
```
```
In net/core/rtnetlink.c (ffffffff8172be22)
Location: include/net/netlink.h:733
Inline: True
Inline callers:
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:rtnl_newlink
```
```
In net/sched/sch_api.c (ffffffff81742d56)
Location: include/net/netlink.h:733
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_get_stab
```
```
In net/sched/act_api.c (ffffffff81747170)
Location: include/net/netlink.h:733
Inline: True
Inline callers:
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_init
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
```
```
In net/sched/ematch.c (ffffffff81749a0d)
Location: include/net/netlink.h:733
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_tree_validate
```
```
In net/ipv4/devinet.c (ffffffff8178f85d)
Location: include/net/netlink.h:733
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff817a44f6)
Location: include/net/netlink.h:733
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
```
```
In net/ipv6/addrconf.c (ffffffff817ca20d)
Location: include/net/netlink.h:733
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_validate_link_af
  - net/ipv6/addrconf.c:inet6_set_link_af
```
```
In net/dcb/dcbnl.c (ffffffff818136f5)
Location: include/net/netlink.h:733
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcbnl_setfeatcfg
  - net/dcb/dcbnl.c:dcbnl_bcn_setcfg
  - net/dcb/dcbnl.c:dcbnl_setnumtcs
  - net/dcb/dcbnl.c:dcbnl_setpfccfg
  - net/dcb/dcbnl.c:dcbnl_getnumtcs
  - net/dcb/dcbnl.c:dcbnl_ieee_del
  - net/dcb/dcbnl.c:dcbnl_ieee_set
  - net/dcb/dcbnl.c:dcbnl_setapp
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
In net/core/neighbour.c (ffffffff8179189c)
Location: include/net/netlink.h:744
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_set
```
```
In net/core/rtnetlink.c (ffffffff817998bd)
Location: include/net/netlink.h:744
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/sched/sch_api.c (ffffffff817afbe6)
Location: include/net/netlink.h:744
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_get_stab
```
```
In net/sched/act_api.c (ffffffff817b597c)
Location: include/net/netlink.h:744
Inline: True
Inline callers:
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tcf_action_init
  - net/sched/act_api.c:tcf_action_init_1
```
```
In net/sched/ematch.c (ffffffff817b697d)
Location: include/net/netlink.h:744
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_tree_validate
```
```
In net/ipv4/devinet.c (ffffffff817fcf4d)
Location: include/net/netlink.h:744
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff818122a6)
Location: include/net/netlink.h:744
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
```
```
In net/ipv6/addrconf.c (ffffffff8183fb1f)
Location: include/net/netlink.h:744
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_validate_link_af
```
```
In net/dcb/dcbnl.c (ffffffff818865d5)
Location: include/net/netlink.h:744
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
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff817bf3ec)
Location: include/net/netlink.h:744
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_set
```
```
In net/core/rtnetlink.c (ffffffff817c765d)
Location: include/net/netlink.h:744
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/lwt_bpf.c (ffffffff817d9c65)
Location: include/net/netlink.h:744
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_build_state
  - net/core/lwt_bpf.c:bpf_parse_prog
```
```
In net/sched/sch_api.c (ffffffff817df2d6)
Location: include/net/netlink.h:744
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_get_stab
```
```
In net/sched/act_api.c (ffffffff817e3ad9)
Location: include/net/netlink.h:744
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
In net/sched/ematch.c (ffffffff817e640d)
Location: include/net/netlink.h:744
Inline: True
Inline callers:
  - net/sched/ematch.c:tcf_em_tree_validate
```
```
In net/ipv4/devinet.c (ffffffff8182dead)
Location: include/net/netlink.h:744
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff818437b6)
Location: include/net/netlink.h:744
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
```
```
In net/ipv6/addrconf.c (ffffffff8187174f)
Location: include/net/netlink.h:744
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_validate_link_af
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff818a3f16)
Location: include/net/netlink.h:744
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
```
```
In net/dcb/dcbnl.c (ffffffff818bae45)
Location: include/net/netlink.h:744
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
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff817ddcc3)
Location: include/net/netlink.h:754
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_set
```
```
In net/core/rtnetlink.c (ffffffff817e5ed3)
Location: include/net/netlink.h:754
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/lwt_bpf.c (ffffffff817f92a2)
Location: include/net/netlink.h:754
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_build_state
  - net/core/lwt_bpf.c:bpf_parse_prog
```
```
In net/sched/sch_api.c (ffffffff817fe766)
Location: include/net/netlink.h:754
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_get_stab
```
```
In net/sched/act_api.c (ffffffff8180341c)
Location: include/net/netlink.h:754
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
In net/sched/ematch.c (ffffffff81805f5d)
Location: include/net/netlink.h:754
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff8184fb2d)
Location: include/net/netlink.h:754
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff8186500e)
Location: include/net/netlink.h:754
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
```
```
In net/ipv6/addrconf.c (ffffffff818964c4)
Location: include/net/netlink.h:754
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_validate_link_af
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff818ca486)
Location: include/net/netlink.h:754
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
```
```
In net/dcb/dcbnl.c (ffffffff818e1853)
Location: include/net/netlink.h:754
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
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81856ab3)
Location: include/net/netlink.h:760
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_set
```
```
In net/core/rtnetlink.c (ffffffff81860f86)
Location: include/net/netlink.h:760
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/lwt_bpf.c (ffffffff81876bb2)
Location: include/net/netlink.h:760
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_build_state
  - net/core/lwt_bpf.c:bpf_parse_prog
```
```
In net/sched/sch_api.c (ffffffff8187c3f6)
Location: include/net/netlink.h:760
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_get_stab
```
```
In net/sched/act_api.c (ffffffff8188189c)
Location: include/net/netlink.h:760
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
In net/sched/ematch.c (ffffffff81884c8d)
Location: include/net/netlink.h:760
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff818cf75d)
Location: include/net/netlink.h:760
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff818e516e)
Location: include/net/netlink.h:760
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
```
```
In net/ipv6/addrconf.c (ffffffff81917894)
Location: include/net/netlink.h:760
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_validate_link_af
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff8194dc46)
Location: include/net/netlink.h:760
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
```
```
In net/ipv6/seg6_local.c (ffffffff8194f082)
Location: include/net/netlink.h:760
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_build_state
```
```
In net/dcb/dcbnl.c (ffffffff819675d3)
Location: include/net/netlink.h:760
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
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff818a1afc)
Location: include/net/netlink.h:760
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_set
```
```
In net/core/rtnetlink.c (ffffffff818acb32)
Location: include/net/netlink.h:760
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
```
In net/core/lwt_bpf.c (ffffffff818c8372)
Location: include/net/netlink.h:760
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_build_state
```
```
In net/sched/sch_api.c (ffffffff818cec52)
Location: include/net/netlink.h:760
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_get_stab
```
```
In net/sched/act_api.c (ffffffff818d536c)
Location: include/net/netlink.h:760
Inline: True
Inline callers:
  - net/sched/act_api.c:find_dump_kind
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_action_init
  - net/sched/act_api.c:tcf_action_init_1
```
```
In net/sched/ematch.c (ffffffff818d87f6)
Location: include/net/netlink.h:760
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff8192545d)
Location: include/net/netlink.h:760
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff8193ba7d)
Location: include/net/netlink.h:760
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
```
```
In net/ipv6/addrconf.c (ffffffff8196efd0)
Location: include/net/netlink.h:760
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_validate_link_af
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819a6ec6)
Location: include/net/netlink.h:760
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
```
```
In net/ipv6/seg6_local.c (ffffffff819a8361)
Location: include/net/netlink.h:760
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_build_state
  - net/ipv6/seg6_local.c:parse_nla_bpf
```
```
In net/dcb/dcbnl.c (ffffffff819c0af0)
Location: include/net/netlink.h:760
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
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff818c4c6c)
Location: include/net/netlink.h:903
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_set
```
```
In net/core/rtnetlink.c (ffffffff818d0c52)
Location: include/net/netlink.h:903
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
In net/core/lwt_bpf.c (ffffffff818f14e2)
Location: include/net/netlink.h:903
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_build_state
```
```
In net/sched/sch_api.c (ffffffff818f9f52)
Location: include/net/netlink.h:903
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_get_stab
```
```
In net/sched/act_api.c (ffffffff81901fac)
Location: include/net/netlink.h:903
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
In net/sched/ematch.c (ffffffff81904fe6)
Location: include/net/netlink.h:903
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff8195426d)
Location: include/net/netlink.h:903
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inet_validate_link_af
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff8196b76d)
Location: include/net/netlink.h:903
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
```
```
In net/ipv6/addrconf.c (ffffffff819a4b80)
Location: include/net/netlink.h:903
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_set_link_af
  - net/ipv6/addrconf.c:inet6_validate_link_af
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819dda26)
Location: include/net/netlink.h:903
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_build_state
```
```
In net/ipv6/seg6_local.c (ffffffff819deeb1)
Location: include/net/netlink.h:903
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_build_state
  - net/ipv6/seg6_local.c:parse_nla_bpf
```
```
In net/dcb/dcbnl.c (ffffffff819f7ea0)
Location: include/net/netlink.h:903
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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ethtool/netlink.c (ffffffff81a85dc9)
Location: include/net/netlink.h:1189
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_parse_header_dev_get
```
```
In net/ethtool/bitset.c (ffffffff81a8782d)
Location: include/net/netlink.h:1189
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_parse_bit
  - net/ethtool/bitset.c:ethnl_bitset_is_compact
```
```
In net/ethtool/strset.c (ffffffff81a87c7a)
Location: include/net/netlink.h:1189
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_parse_request
```
```
In net/ethtool/cabletest.c (ffffffff81a8cc6a)
Location: include/net/netlink.h:1189
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_act_cable_test_tdr_cfg
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af90a0)
Location: include/net/netlink.h:1189
Inline: True
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
In net/core/devlink.c (ffffffff81a66838)
Location: include/net/netlink.h:1202
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_port_set_doit
```
```
In net/ethtool/netlink.c (ffffffff81a8f759)
Location: include/net/netlink.h:1202
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_parse_header_dev_get
```
```
In net/ethtool/bitset.c (ffffffff81a911ad)
Location: include/net/netlink.h:1202
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_parse_bit
  - net/ethtool/bitset.c:ethnl_parse_bit
  - net/ethtool/bitset.c:ethnl_bitset_is_compact
```
```
In net/ethtool/strset.c (ffffffff81a915ea)
Location: include/net/netlink.h:1202
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_parse_request
```
```
In net/ethtool/cabletest.c (ffffffff81a9637a)
Location: include/net/netlink.h:1202
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_act_cable_test_tdr_cfg
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81b05d00)
Location: include/net/netlink.h:1202
Inline: True
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
In net/core/devlink.c (ffffffff81a46715)
Location: include/net/netlink.h:1202
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_port_function_set
```
```
In net/ethtool/netlink.c (ffffffff81a78e4d)
Location: include/net/netlink.h:1202
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_parse_header_dev_get
```
```
In net/ethtool/bitset.c (ffffffff81a7a9bd)
Location: include/net/netlink.h:1202
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_parse_bit
  - net/ethtool/bitset.c:ethnl_parse_bit
  - net/ethtool/bitset.c:ethnl_bitset_is_compact
  - net/ethtool/bitset.c:ethnl_bitset_is_compact
```
```
In net/ethtool/strset.c (ffffffff81a7ae0a)
Location: include/net/netlink.h:1202
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_parse_request
```
```
In net/ethtool/cabletest.c (ffffffff81a7fe01)
Location: include/net/netlink.h:1202
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_act_cable_test_tdr_cfg
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af156a)
Location: include/net/netlink.h:1202
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81af5996)
Location: include/net/netlink.h:1202
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_valid_get_bucket_req
  - net/ipv4/nexthop.c:nh_valid_get_bucket_req
  - net/ipv4/nexthop.c:nh_valid_dump_bucket_req
  - net/ipv4/nexthop.c:nh_valid_dump_bucket_req
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv4/nexthop.c:rtm_to_nh_config
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
In net/core/devlink.c (ffffffff81b01483)
Location: include/net/netlink.h:1202
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_port_function_set
```
```
In net/ethtool/netlink.c (ffffffff81b3311d)
Location: include/net/netlink.h:1202
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_parse_header_dev_get
```
```
In net/ethtool/bitset.c (ffffffff81b34dcd)
Location: include/net/netlink.h:1202
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_parse_bit
  - net/ethtool/bitset.c:ethnl_parse_bit
  - net/ethtool/bitset.c:ethnl_bitset_is_compact
  - net/ethtool/bitset.c:ethnl_bitset_is_compact
```
```
In net/ethtool/strset.c (ffffffff81b3536a)
Location: include/net/netlink.h:1202
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_parse_request
```
```
In net/ethtool/cabletest.c (ffffffff81b39bd1)
Location: include/net/netlink.h:1202
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_act_cable_test_tdr_cfg
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81bb1a7a)
Location: include/net/netlink.h:1202
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81bb6296)
Location: include/net/netlink.h:1202
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_valid_get_bucket_req
  - net/ipv4/nexthop.c:nh_valid_get_bucket_req
  - net/ipv4/nexthop.c:nh_valid_dump_bucket_req
  - net/ipv4/nexthop.c:nh_valid_dump_bucket_req
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff81c4bc04)
Location: include/net/netlink.h:1202
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_build_state
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
In net/core/rtnetlink.c (ffffffff81c2cfe2)
Location: include/net/netlink.h:1202
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get_parse
```
```
In net/core/devlink.c (ffffffff81c80a37)
Location: include/net/netlink.h:1202
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_port_function_set
```
```
In net/ethtool/netlink.c (ffffffff81cbe30d)
Location: include/net/netlink.h:1202
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_parse_header_dev_get
```
```
In net/ethtool/bitset.c (ffffffff81cc05b8)
Location: include/net/netlink.h:1202
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_update_bitset32
  - net/ethtool/bitset.c:ethnl_update_bitset32
  - net/ethtool/bitset.c:ethnl_parse_bit
  - net/ethtool/bitset.c:ethnl_parse_bit
  - net/ethtool/bitset.c:ethnl_bitset_is_compact
  - net/ethtool/bitset.c:ethnl_bitset_is_compact
```
```
In net/ethtool/strset.c (ffffffff81cc0bf0)
Location: include/net/netlink.h:1202
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_parse_request
```
```
In net/ethtool/cabletest.c (ffffffff81cc5a7b)
Location: include/net/netlink.h:1202
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_act_cable_test_tdr_cfg
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81d45152)
Location: include/net/netlink.h:1202
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81d49ea0)
Location: include/net/netlink.h:1202
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_valid_get_bucket_req
  - net/ipv4/nexthop.c:nh_valid_get_bucket_req
  - net/ipv4/nexthop.c:nh_valid_dump_bucket_req
  - net/ipv4/nexthop.c:nh_valid_dump_bucket_req
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff81deb784)
Location: include/net/netlink.h:1202
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_build_state
```
```
In net/mctp/device.c (ffffffff81e37e52)
Location: include/net/netlink.h:1202
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_set_link_af
```
```
In net/mctp/route.c (ffffffff81e39c4b)
Location: include/net/netlink.h:1202
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_newroute
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
In net/core/rtnetlink.c (ffffffff81de0142)
Location: include/net/netlink.h:1251
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get_parse
```
```
In net/core/devlink.c (ffffffff81e3cb27)
Location: include/net/netlink.h:1251
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_selftests_run
  - net/core/devlink.c:devlink_nl_cmd_selftests_run
  - net/core/devlink.c:devlink_port_function_set
  - net/core/devlink.c:devlink_port_function_set
```
```
In net/ethtool/netlink.c (ffffffff81e7cdcd)
Location: include/net/netlink.h:1251
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_parse_header_dev_get
```
```
In net/ethtool/bitset.c (ffffffff81e7f208)
Location: include/net/netlink.h:1251
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_update_bitset32
  - net/ethtool/bitset.c:ethnl_update_bitset32
  - net/ethtool/bitset.c:ethnl_parse_bit
  - net/ethtool/bitset.c:ethnl_parse_bit
  - net/ethtool/bitset.c:ethnl_bitset_is_compact
  - net/ethtool/bitset.c:ethnl_bitset_is_compact
```
```
In net/ethtool/strset.c (ffffffff81e7f8d0)
Location: include/net/netlink.h:1251
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_parse_request
```
```
In net/ethtool/cabletest.c (ffffffff81e8502b)
Location: include/net/netlink.h:1251
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_act_cable_test_tdr_cfg
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f0e13d)
Location: include/net/netlink.h:1251
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip_tun_parse_opts_geneve
  - net/ipv4/ip_tunnel_core.c:ip_tun_parse_opts_geneve
```
```
In net/ipv4/nexthop.c (ffffffff81f13510)
Location: include/net/netlink.h:1251
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_valid_get_bucket_req
  - net/ipv4/nexthop.c:nh_valid_get_bucket_req
  - net/ipv4/nexthop.c:nh_valid_dump_bucket_req
  - net/ipv4/nexthop.c:nh_valid_dump_bucket_req
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff81fbf3e4)
Location: include/net/netlink.h:1251
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_build_state
```
```
In net/mctp/device.c (ffffffff82011072)
Location: include/net/netlink.h:1251
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_set_link_af
```
```
In net/mctp/route.c (ffffffff82012d2b)
Location: include/net/netlink.h:1251
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_newroute
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
In net/core/rtnetlink.c (ffffffff81e51812)
Location: include/net/netlink.h:1252
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get_parse
```
```
In net/ethtool/netlink.c (ffffffff81ed918c)
Location: include/net/netlink.h:1252
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_parse_header_dev_get
```
```
In net/ethtool/bitset.c (ffffffff81edb7f8)
Location: include/net/netlink.h:1252
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_update_bitset32
  - net/ethtool/bitset.c:ethnl_update_bitset32
  - net/ethtool/bitset.c:ethnl_parse_bit
  - net/ethtool/bitset.c:ethnl_parse_bit
  - net/ethtool/bitset.c:ethnl_bitset_is_compact
  - net/ethtool/bitset.c:ethnl_bitset_is_compact
```
```
In net/ethtool/strset.c (ffffffff81edbf7d)
Location: include/net/netlink.h:1252
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_parse_request
```
```
In net/ethtool/cabletest.c (ffffffff81ee195b)
Location: include/net/netlink.h:1252
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_act_cable_test_tdr_cfg
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f6dded)
Location: include/net/netlink.h:1252
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip_tun_parse_opts_geneve
  - net/ipv4/ip_tunnel_core.c:ip_tun_parse_opts_geneve
```
```
In net/ipv4/nexthop.c (ffffffff81f731e0)
Location: include/net/netlink.h:1252
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_valid_get_bucket_req
  - net/ipv4/nexthop.c:nh_valid_get_bucket_req
  - net/ipv4/nexthop.c:nh_valid_dump_bucket_req
  - net/ipv4/nexthop.c:nh_valid_dump_bucket_req
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff82020374)
Location: include/net/netlink.h:1252
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_build_state
```
```
In net/devlink/leftover.c (ffffffff8203d473)
Location: include/net/netlink.h:1252
Inline: True
Inline callers:
  - net/devlink/leftover.c:devlink_port_function_set
```
```
In net/devlink/dev.c (ffffffff82045897)
Location: include/net/netlink.h:1252
Inline: True
Inline callers:
  - net/devlink/dev.c:devlink_nl_cmd_selftests_run
```
```
In net/mctp/device.c (ffffffff8208de32)
Location: include/net/netlink.h:1252
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_set_link_af
```
```
In net/mctp/route.c (ffffffff8208fb4f)
Location: include/net/netlink.h:1252
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_newroute
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
In drivers/dpll/dpll_netlink.c (ffffffff81ebaba9)
Location: include/net/netlink.h:1296
Inline: True
Inline callers:
  - drivers/dpll/dpll_netlink.c:dpll_pin_parent_pin_set
  - drivers/dpll/dpll_netlink.c:dpll_pin_parent_pin_set
  - drivers/dpll/dpll_netlink.c:dpll_pin_parent_device_set
  - drivers/dpll/dpll_netlink.c:dpll_pin_parent_device_set
```
```
In net/core/rtnetlink.c (ffffffff81f10982)
Location: include/net/netlink.h:1296
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_stats_get_parse
```
```
In net/core/page_pool_user.c (ffffffff81f45e0e)
Location: include/net/netlink.h:1296
Inline: True
Inline callers:
  - net/core/page_pool_user.c:netdev_nl_page_pool_stats_get_doit
```
```
In net/ethtool/netlink.c (ffffffff81f9d04c)
Location: include/net/netlink.h:1296
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_parse_header_dev_get
```
```
In net/ethtool/bitset.c (ffffffff81f9f5b8)
Location: include/net/netlink.h:1296
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_update_bitset32
  - net/ethtool/bitset.c:ethnl_update_bitset32
  - net/ethtool/bitset.c:ethnl_parse_bit
  - net/ethtool/bitset.c:ethnl_parse_bit
  - net/ethtool/bitset.c:ethnl_bitset_is_compact
  - net/ethtool/bitset.c:ethnl_bitset_is_compact
```
```
In net/ethtool/strset.c (ffffffff81f9fd43)
Location: include/net/netlink.h:1296
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_parse_request
```
```
In net/ethtool/cabletest.c (ffffffff81fa57eb)
Location: include/net/netlink.h:1296
Inline: True
Inline callers:
  - net/ethtool/cabletest.c:ethnl_act_cable_test_tdr_cfg
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff82034510)
Location: include/net/netlink.h:1296
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip_tun_parse_opts_geneve
  - net/ipv4/ip_tunnel_core.c:ip_tun_parse_opts_geneve
```
```
In net/ipv4/nexthop.c (ffffffff820392a0)
Location: include/net/netlink.h:1296
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_valid_get_bucket_req
  - net/ipv4/nexthop.c:nh_valid_get_bucket_req
  - net/ipv4/nexthop.c:nh_valid_dump_bucket_req
  - net/ipv4/nexthop.c:nh_valid_dump_bucket_req
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff820ef4a4)
Location: include/net/netlink.h:1296
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_build_state
```
```
In net/devlink/dev.c (ffffffff821051d7)
Location: include/net/netlink.h:1296
Inline: True
Inline callers:
  - net/devlink/dev.c:devlink_nl_selftests_run_doit
```
```
In net/devlink/port.c (ffffffff82106ecf)
Location: include/net/netlink.h:1296
Inline: True
Inline callers:
  - net/devlink/port.c:devlink_port_function_set
```
```
In net/mctp/device.c (ffffffff821642f2)
Location: include/net/netlink.h:1296
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_set_link_af
```
```
In net/mctp/route.c (ffffffff8216605f)
Location: include/net/netlink.h:1296
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_newroute
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
