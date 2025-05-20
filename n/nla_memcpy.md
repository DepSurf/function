# Function: <code>nla_memcpy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int nla_memcpy(void *dest, const struct nlattr *src, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff81415950)
Location: lib/nlattr.c:277
Inline: False
Direct callers:
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/rtnetlink.c:do_setlink
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/fib6_rules.c:fib6_rule_configure
  - net/ipv6/fib6_rules.c:fib6_rule_configure
```
**Symbols:**

```
ffffffff81415950-ffffffff81415995: nla_memcpy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int nla_memcpy(void *dest, const struct nlattr *src, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff8145d6a0)
Location: lib/nlattr.c:277
Inline: False
Direct callers:
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/rtnetlink.c:do_setlink
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/fib6_rules.c:fib6_rule_configure
  - net/ipv6/fib6_rules.c:fib6_rule_configure
```
**Symbols:**

```
ffffffff8145d6a0-ffffffff8145d6e5: nla_memcpy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int nla_memcpy(void *dest, const struct nlattr *src, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff8147c160)
Location: lib/nlattr.c:277
Inline: False
Direct callers:
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/rtnetlink.c:do_setlink
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/fib6_rules.c:fib6_rule_configure
  - net/ipv6/fib6_rules.c:fib6_rule_configure
```
**Symbols:**

```
ffffffff8147c160-ffffffff8147c1a5: nla_memcpy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int nla_memcpy(void *dest, const struct nlattr *src, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff81485480)
Location: lib/nlattr.c:285
Inline: False
Direct callers:
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/rtnetlink.c:do_setlink
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/fib6_rules.c:fib6_rule_configure
  - net/ipv6/fib6_rules.c:fib6_rule_configure
```
**Symbols:**

```
ffffffff81485480-ffffffff814854c5: nla_memcpy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int nla_memcpy(void *dest, const struct nlattr *src, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff814c1590)
Location: lib/nlattr.c:363
Inline: False
Direct callers:
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/rtnetlink.c:do_setlink
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
  - net/sched/act_api.c:tc_dump_action
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/fib6_rules.c:fib6_rule_configure
  - net/ipv6/fib6_rules.c:fib6_rule_configure
```
**Symbols:**

```
ffffffff814c1590-ffffffff814c15d5: nla_memcpy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int nla_memcpy(void *dest, const struct nlattr *src, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff814f22b0)
Location: lib/nlattr.c:363
Inline: False
Direct callers:
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/rtnetlink.c:do_setlink
  - net/sched/act_api.c:tc_dump_action
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/fib6_rules.c:fib6_rule_configure
  - net/ipv6/fib6_rules.c:fib6_rule_configure
```
**Symbols:**

```
ffffffff814f22b0-ffffffff814f22f5: nla_memcpy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int nla_memcpy(void *dest, const struct nlattr *src, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff81505fd0)
Location: lib/nlattr.c:538
Inline: False
Direct callers:
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:validate_nla
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/rtnetlink.c:do_setlink
  - net/sched/act_api.c:tc_dump_action
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/fib6_rules.c:fib6_rule_configure
  - net/ipv6/fib6_rules.c:fib6_rule_configure
```
**Symbols:**

```
ffffffff81505fd0-ffffffff81506015: nla_memcpy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int nla_memcpy(void *dest, const struct nlattr *src, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff815341e0)
Location: lib/nlattr.c:570
Inline: False
Direct callers:
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:validate_nla
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/rtnetlink.c:do_setlink
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_resource_set
  - net/core/devlink.c:devlink_nl_cmd_resource_set
  - net/sched/act_api.c:tc_dump_action
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/fib6_rules.c:fib6_rule_configure
  - net/ipv6/fib6_rules.c:fib6_rule_configure
```
**Symbols:**

```
ffffffff815341e0-ffffffff8153422b: nla_memcpy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int nla_memcpy(void *dest, const struct nlattr *src, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff81555020)
Location: lib/nlattr.c:570
Inline: False
Direct callers:
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:validate_nla
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/rtnetlink.c:do_setlink
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_resource_set
  - net/core/devlink.c:devlink_nl_cmd_resource_set
  - net/sched/act_api.c:tc_dump_action
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/fib6_rules.c:fib6_rule_configure
  - net/ipv6/fib6_rules.c:fib6_rule_configure
```
**Symbols:**

```
ffffffff81555020-ffffffff8155506b: nla_memcpy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int nla_memcpy(void *dest, const struct nlattr *src, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff815de580)
Location: lib/nlattr.c:722
Inline: False
Direct callers:
  - lib/nlattr.c:nla_validate_int_range
  - lib/nlattr.c:nla_validate_int_range
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/rtnetlink.c:do_setlink
  - net/core/devlink.c:devlink_trap_policer_set
  - net/core/devlink.c:devlink_trap_policer_set
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_resource_set
  - net/core/devlink.c:devlink_nl_cmd_resource_set
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_init_1
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/fib6_rules.c:fib6_rule_configure
  - net/ipv6/fib6_rules.c:fib6_rule_configure
  - net/mptcp/pm_netlink.c:mptcp_pm_parse_addr
```
**Symbols:**

```
ffffffff815de580-ffffffff815de5cb: nla_memcpy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int nla_memcpy(void *dest, const struct nlattr *src, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff815fbb80)
Location: lib/nlattr.c:789
Inline: False
Direct callers:
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:nla_validate_int_range
  - lib/nlattr.c:nla_validate_int_range
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/rtnetlink.c:do_setlink
  - net/core/devlink.c:devlink_trap_policer_set
  - net/core/devlink.c:devlink_trap_policer_set
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_flash_update
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_nl_cmd_resource_set
  - net/core/devlink.c:devlink_nl_cmd_resource_set
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_init_1
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/fib6_rules.c:fib6_rule_configure
  - net/ipv6/fib6_rules.c:fib6_rule_configure
  - net/mptcp/pm_netlink.c:mptcp_pm_parse_addr
```
**Symbols:**

```
ffffffff815fbb80-ffffffff815fbbcb: nla_memcpy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int nla_memcpy(void *dest, const struct nlattr *src, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff815de7d0)
Location: lib/nlattr.c:789
Inline: False
Direct callers:
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:nla_validate_int_range
  - lib/nlattr.c:nla_validate_int_range
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/rtnetlink.c:do_setlink
  - net/core/devlink.c:devlink_nl_cmd_trap_policer_set_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_policer_set_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_flash_update
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_nl_cmd_resource_set
  - net/core/devlink.c:devlink_nl_cmd_resource_set
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_init_1
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/fib6_rules.c:fib6_rule_configure
  - net/ipv6/fib6_rules.c:fib6_rule_configure
  - net/mptcp/pm_netlink.c:mptcp_pm_parse_addr
```
**Symbols:**

```
ffffffff815de7d0-ffffffff815de81b: nla_memcpy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int nla_memcpy(void *dest, const struct nlattr *src, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff8164a350)
Location: lib/nlattr.c:789
Inline: False
Direct callers:
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:nla_validate_int_range
  - lib/nlattr.c:nla_validate_int_range
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/rtnetlink.c:do_setlink
  - net/core/devlink.c:devlink_nl_cmd_trap_policer_set_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_policer_set_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_flash_update
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_nl_cmd_resource_set
  - net/core/devlink.c:devlink_nl_cmd_resource_set
  - net/core/devlink.c:devlink_nl_rate_set
  - net/core/devlink.c:devlink_nl_rate_set
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_init_1
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
  - net/ipv6/fib6_rules.c:fib6_rule_configure
  - net/ipv6/fib6_rules.c:fib6_rule_configure
  - net/mptcp/pm_netlink.c:mptcp_pm_parse_addr
```
**Symbols:**

```
ffffffff8164a350-ffffffff8164a39b: nla_memcpy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int nla_memcpy(void *dest, const struct nlattr *src, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff81760ab0)
Location: lib/nlattr.c:789
Inline: False
Direct callers:
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:nla_validate_int_range
  - lib/nlattr.c:nla_validate_int_range
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/rtnetlink.c:do_setlink
  - net/core/devlink.c:devlink_nl_cmd_trap_policer_set_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_policer_set_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_flash_update
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_nl_cmd_resource_set
  - net/core/devlink.c:devlink_nl_cmd_resource_set
  - net/core/devlink.c:devlink_nl_rate_set
  - net/core/devlink.c:devlink_nl_rate_set
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_init_1
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
  - net/ipv6/fib6_rules.c:fib6_rule_configure
  - net/ipv6/fib6_rules.c:fib6_rule_configure
  - net/ipv6/ioam6_iptunnel.c:ioam6_build_state
  - net/mptcp/pm_netlink.c:mptcp_pm_parse_pm_addr_attr
```
**Symbols:**

```
ffffffff81760ab0-ffffffff81760b01: nla_memcpy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int nla_memcpy(void *dest, const struct nlattr *src, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff8188fad0)
Location: lib/nlattr.c:804
Inline: False
Direct callers:
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:nla_validate_range_unsigned
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/rtnetlink.c:do_setlink
  - net/core/devlink.c:devlink_nl_cmd_trap_policer_set_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_policer_set_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_flash_update
  - net/core/devlink.c:devlink_nl_cmd_reload
  - net/core/devlink.c:devlink_nl_cmd_resource_set
  - net/core/devlink.c:devlink_nl_cmd_resource_set
  - net/core/devlink.c:devlink_nl_rate_set
  - net/core/devlink.c:devlink_nl_rate_set
  - net/core/devlink.c:devlink_port_function_set
  - net/core/devlink.c:devlink_port_function_set
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_init_1
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
  - net/ipv6/ip6mr.c:ip6mr_rtm_getroute
  - net/ipv6/ip6mr.c:ip6mr_rtm_getroute
  - net/ipv6/fib6_rules.c:fib6_rule_configure
  - net/ipv6/fib6_rules.c:fib6_rule_configure
  - net/ipv6/ioam6_iptunnel.c:ioam6_build_state
  - net/mptcp/pm_netlink.c:mptcp_pm_parse_pm_addr_attr
```
**Symbols:**

```
ffffffff8188fad0-ffffffff8188fb21: nla_memcpy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int nla_memcpy(void *dest, const struct nlattr *src, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff818d1f40)
Location: lib/nlattr.c:804
Inline: False
Direct callers:
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:nla_validate_range_unsigned
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/rtnetlink.c:do_setlink
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_init_1
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
  - net/ipv6/ip6mr.c:ip6mr_rtm_getroute
  - net/ipv6/ip6mr.c:ip6mr_rtm_getroute
  - net/ipv6/fib6_rules.c:fib6_rule_configure
  - net/ipv6/fib6_rules.c:fib6_rule_configure
  - net/ipv6/ioam6_iptunnel.c:ioam6_build_state
  - net/devlink/leftover.c:devlink_nl_cmd_trap_policer_set_doit
  - net/devlink/leftover.c:devlink_nl_cmd_trap_policer_set_doit
  - net/devlink/leftover.c:devlink_nl_cmd_region_read_dumpit
  - net/devlink/leftover.c:devlink_nl_cmd_region_read_dumpit
  - net/devlink/leftover.c:devlink_nl_cmd_region_read_dumpit
  - net/devlink/leftover.c:devlink_nl_cmd_resource_set
  - net/devlink/leftover.c:devlink_nl_cmd_resource_set
  - net/devlink/leftover.c:devlink_nl_rate_set
  - net/devlink/leftover.c:devlink_nl_rate_set
  - net/devlink/leftover.c:devlink_port_function_set
  - net/devlink/leftover.c:devlink_port_function_set
  - net/devlink/dev.c:devlink_nl_cmd_flash_update
  - net/devlink/dev.c:devlink_nl_cmd_reload
  - net/devlink/health.c:devlink_nl_cmd_health_reporter_set_doit
  - net/mptcp/pm_netlink.c:mptcp_pm_parse_pm_addr_attr
```
**Symbols:**

```
ffffffff818d1f40-ffffffff818d1f91: nla_memcpy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int nla_memcpy(void *dest, const struct nlattr *src, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff81923f10)
Location: lib/nlattr.c:836
Inline: False
Direct callers:
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:nla_validate_range_unsigned
  - drivers/dpll/dpll_netlink.c:dpll_device_find_from_nlattr
  - drivers/dpll/dpll_netlink.c:dpll_pin_find_from_nlattr
  - drivers/dpll/dpll_netlink.c:dpll_pin_freq_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/rtnetlink.c:do_setlink
  - net/core/page_pool_user.c:netdev_nl_page_pool_get_doit
  - net/core/page_pool_user.c:netdev_nl_page_pool_stats_get_doit
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/act_api.c:tc_dump_action
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_init_1
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
  - net/ipv6/ip6mr.c:ip6mr_rtm_getroute
  - net/ipv6/ip6mr.c:ip6mr_rtm_getroute
  - net/ipv6/fib6_rules.c:fib6_rule_configure
  - net/ipv6/fib6_rules.c:fib6_rule_configure
  - net/ipv6/ioam6_iptunnel.c:ioam6_build_state
  - net/devlink/dev.c:devlink_nl_flash_update_doit
  - net/devlink/dev.c:devlink_nl_reload_doit
  - net/devlink/port.c:devlink_port_function_set
  - net/devlink/port.c:devlink_port_function_validate
  - net/devlink/resource.c:devlink_nl_resource_set_doit
  - net/devlink/resource.c:devlink_nl_resource_set_doit
  - net/devlink/region.c:devlink_nl_region_read_dumpit
  - net/devlink/region.c:devlink_nl_region_read_dumpit
  - net/devlink/region.c:devlink_nl_region_read_dumpit
  - net/devlink/health.c:devlink_nl_health_reporter_set_doit
  - net/devlink/trap.c:devlink_nl_trap_policer_set_doit
  - net/devlink/trap.c:devlink_nl_trap_policer_set_doit
  - net/devlink/rate.c:devlink_nl_rate_set
  - net/devlink/rate.c:devlink_nl_rate_set
  - net/mptcp/pm_netlink.c:mptcp_pm_parse_pm_addr_attr
```
**Symbols:**

```
ffffffff81923f10-ffffffff81923f64: nla_memcpy (STB_GLOBAL)
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
int nla_memcpy(void *dest, const struct nlattr *src, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffff8000106613d0)
Location: lib/nlattr.c:570
Inline: False
Direct callers:
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:validate_nla
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/rtnetlink.c:do_setlink
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_resource_set
  - net/core/devlink.c:devlink_nl_cmd_resource_set
  - net/sched/act_api.c:tc_dump_action
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/fib6_rules.c:fib6_rule_configure
  - net/ipv6/fib6_rules.c:fib6_rule_configure
```
**Symbols:**

```
ffff8000106613d0-ffff800010661434: nla_memcpy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int nla_memcpy(void *dest, const struct nlattr *src, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (c080a3f4)
Location: lib/nlattr.c:570
Inline: False
Direct callers:
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:validate_nla
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/rtnetlink.c:do_setlink
  - net/core/fib_rules.c:fib_nl2rule
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_resource_set
  - net/core/devlink.c:devlink_nl_cmd_resource_set
  - net/sched/act_api.c:tc_dump_action
  - net/ipv4/tcp_metrics.c:__parse_nl_addr
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/fib6_rules.c:fib6_rule_configure
  - net/ipv6/fib6_rules.c:fib6_rule_configure
```
**Symbols:**

```
c080a3f4-c080a440: nla_memcpy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int nla_memcpy(void *dest, const struct nlattr *src, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (c000000000815180)
Location: lib/nlattr.c:570
Inline: False
Direct callers:
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:validate_nla
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/rtnetlink.c:do_setlink
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_resource_set
  - net/core/devlink.c:devlink_nl_cmd_resource_set
  - net/sched/act_api.c:tc_dump_action
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/fib6_rules.c:fib6_rule_configure
  - net/ipv6/fib6_rules.c:fib6_rule_configure
```
**Symbols:**

```
c000000000815180-c000000000815214: nla_memcpy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int nla_memcpy(void *dest, const struct nlattr *src, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffe00048deb4)
Location: lib/nlattr.c:570
Inline: False
Direct callers:
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:validate_nla
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/rtnetlink.c:do_setlink
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_resource_set
  - net/core/devlink.c:devlink_nl_cmd_resource_set
  - net/sched/act_api.c:tc_dump_action
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/fib6_rules.c:fib6_rule_configure
  - net/ipv6/fib6_rules.c:fib6_rule_configure
```
**Symbols:**

```
ffffffe00048deb4-ffffffe00048df1c: nla_memcpy (STB_GLOBAL)
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
int nla_memcpy(void *dest, const struct nlattr *src, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff8154d600)
Location: lib/nlattr.c:570
Inline: False
Direct callers:
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:validate_nla
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/rtnetlink.c:do_setlink
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_resource_set
  - net/core/devlink.c:devlink_nl_cmd_resource_set
  - net/sched/act_api.c:tc_dump_action
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/fib6_rules.c:fib6_rule_configure
  - net/ipv6/fib6_rules.c:fib6_rule_configure
```
**Symbols:**

```
ffffffff8154d600-ffffffff8154d64b: nla_memcpy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int nla_memcpy(void *dest, const struct nlattr *src, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff8153d8e0)
Location: lib/nlattr.c:570
Inline: False
Direct callers:
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:validate_nla
  - drivers/net/vxlan.c:vxlan_nl2conf
  - drivers/net/vxlan.c:vxlan_nl2conf
  - drivers/net/vxlan.c:vxlan_fdb_parse
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/rtnetlink.c:do_setlink
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_resource_set
  - net/core/devlink.c:devlink_nl_cmd_resource_set
  - net/sched/act_api.c:tc_dump_action
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/fib6_rules.c:fib6_rule_configure
  - net/ipv6/fib6_rules.c:fib6_rule_configure
```
**Symbols:**

```
ffffffff8153d8e0-ffffffff8153d92b: nla_memcpy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int nla_memcpy(void *dest, const struct nlattr *src, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff81549340)
Location: lib/nlattr.c:570
Inline: False
Direct callers:
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:validate_nla
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/rtnetlink.c:do_setlink
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_resource_set
  - net/core/devlink.c:devlink_nl_cmd_resource_set
  - net/sched/act_api.c:tc_dump_action
  - net/netfilter/nf_conntrack_proto_dccp.c:nlattr_to_dccp
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/fib6_rules.c:fib6_rule_configure
  - net/ipv6/fib6_rules.c:fib6_rule_configure
```
**Symbols:**

```
ffffffff81549340-ffffffff8154938b: nla_memcpy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int nla_memcpy(void *dest, const struct nlattr *src, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff81563190)
Location: lib/nlattr.c:570
Inline: False
Direct callers:
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:validate_nla
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/rtnetlink.c:do_setlink
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
  - net/core/devlink.c:devlink_nl_cmd_resource_set
  - net/core/devlink.c:devlink_nl_cmd_resource_set
  - net/sched/act_api.c:tc_dump_action
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/fib6_rules.c:fib6_rule_configure
  - net/ipv6/fib6_rules.c:fib6_rule_configure
```
**Symbols:**

```
ffffffff81563190-ffffffff815631db: nla_memcpy (STB_GLOBAL)
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
