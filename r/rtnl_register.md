# Function: <code>rtnl_register</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void rtnl_register(int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, rtnl_calcit_func calcit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff8172b5c0)
Location: net/core/rtnetlink.c:226
Inline: False
Direct callers:
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/neighbour.c:neigh_init
  - net/core/neighbour.c:neigh_init
  - net/core/neighbour.c:neigh_init
  - net/core/neighbour.c:neigh_init
  - net/core/neighbour.c:neigh_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/fib_rules.c:fib_rules_init
  - net/core/fib_rules.c:fib_rules_init
  - net/core/fib_rules.c:fib_rules_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/act_api.c:tc_action_init
  - net/sched/act_api.c:tc_action_init
  - net/sched/act_api.c:tc_action_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/dcb/dcbnl.c:dcbnl_init
  - net/dcb/dcbnl.c:dcbnl_init
```
**Symbols:**

```
ffffffff8172b5c0-ffffffff8172b5f0: rtnl_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void rtnl_register(int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, rtnl_calcit_func calcit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81795170)
Location: net/core/rtnetlink.c:248
Inline: False
Direct callers:
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/neighbour.c:neigh_init
  - net/core/neighbour.c:neigh_init
  - net/core/neighbour.c:neigh_init
  - net/core/neighbour.c:neigh_init
  - net/core/neighbour.c:neigh_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/fib_rules.c:fib_rules_init
  - net/core/fib_rules.c:fib_rules_init
  - net/core/fib_rules.c:fib_rules_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/act_api.c:tc_action_init
  - net/sched/act_api.c:tc_action_init
  - net/sched/act_api.c:tc_action_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/dcb/dcbnl.c:dcbnl_init
  - net/dcb/dcbnl.c:dcbnl_init
```
**Symbols:**

```
ffffffff81795170-ffffffff817951a0: rtnl_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void rtnl_register(int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, rtnl_calcit_func calcit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff817c29e0)
Location: net/core/rtnetlink.c:248
Inline: False
Direct callers:
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/neighbour.c:neigh_init
  - net/core/neighbour.c:neigh_init
  - net/core/neighbour.c:neigh_init
  - net/core/neighbour.c:neigh_init
  - net/core/neighbour.c:neigh_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/fib_rules.c:fib_rules_init
  - net/core/fib_rules.c:fib_rules_init
  - net/core/fib_rules.c:fib_rules_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/act_api.c:tc_action_init
  - net/sched/act_api.c:tc_action_init
  - net/sched/act_api.c:tc_action_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/dcb/dcbnl.c:dcbnl_init
  - net/dcb/dcbnl.c:dcbnl_init
```
**Symbols:**

```
ffffffff817c29e0-ffffffff817c2a10: rtnl_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void rtnl_register(int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, rtnl_calcit_func calcit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff817e1190)
Location: net/core/rtnetlink.c:250
Inline: False
Direct callers:
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/neighbour.c:neigh_init
  - net/core/neighbour.c:neigh_init
  - net/core/neighbour.c:neigh_init
  - net/core/neighbour.c:neigh_init
  - net/core/neighbour.c:neigh_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/fib_rules.c:fib_rules_init
  - net/core/fib_rules.c:fib_rules_init
  - net/core/fib_rules.c:fib_rules_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/act_api.c:tc_action_init
  - net/sched/act_api.c:tc_action_init
  - net/sched/act_api.c:tc_action_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/dcb/dcbnl.c:dcbnl_init
  - net/dcb/dcbnl.c:dcbnl_init
```
**Symbols:**

```
ffffffff817e1190-ffffffff817e11c0: rtnl_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void rtnl_register(int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff8185b8f0)
Location: net/core/rtnetlink.c:203
Inline: False
Direct callers:
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/neighbour.c:neigh_init
  - net/core/neighbour.c:neigh_init
  - net/core/neighbour.c:neigh_init
  - net/core/neighbour.c:neigh_init
  - net/core/neighbour.c:neigh_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/fib_rules.c:fib_rules_init
  - net/core/fib_rules.c:fib_rules_init
  - net/core/fib_rules.c:fib_rules_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/cls_api.c:tc_filter_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/dcb/dcbnl.c:dcbnl_init
  - net/dcb/dcbnl.c:dcbnl_init
```
**Symbols:**

```
ffffffff8185b8f0-ffffffff8185b920: rtnl_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void rtnl_register(int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:266
Inline: False
Direct callers:
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/neighbour.c:neigh_init
  - net/core/neighbour.c:neigh_init
  - net/core/neighbour.c:neigh_init
  - net/core/neighbour.c:neigh_init
  - net/core/neighbour.c:neigh_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/fib_rules.c:fib_rules_init
  - net/core/fib_rules.c:fib_rules_init
  - net/core/fib_rules.c:fib_rules_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/act_api.c:tc_action_init
  - net/sched/act_api.c:tc_action_init
  - net/sched/act_api.c:tc_action_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/dcb/dcbnl.c:dcbnl_init
  - net/dcb/dcbnl.c:dcbnl_init
```
**Symbols:**

```
ffffffff818ad5c2-ffffffff818ad5d8: rtnl_register.cold.46 (STB_LOCAL)
ffffffff818ad230-ffffffff818ad262: rtnl_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void rtnl_register(int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:272
Inline: False
Direct callers:
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/neighbour.c:neigh_init
  - net/core/neighbour.c:neigh_init
  - net/core/neighbour.c:neigh_init
  - net/core/neighbour.c:neigh_init
  - net/core/neighbour.c:neigh_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/fib_rules.c:fib_rules_init
  - net/core/fib_rules.c:fib_rules_init
  - net/core/fib_rules.c:fib_rules_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/act_api.c:tc_action_init
  - net/sched/act_api.c:tc_action_init
  - net/sched/act_api.c:tc_action_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/dcb/dcbnl.c:dcbnl_init
  - net/dcb/dcbnl.c:dcbnl_init
```
**Symbols:**

```
ffffffff818d1822-ffffffff818d1838: rtnl_register.cold.47 (STB_LOCAL)
ffffffff818d1490-ffffffff818d14c2: rtnl_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void rtnl_register(int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:267
Inline: False
Direct callers:
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/neighbour.c:neigh_init
  - net/core/neighbour.c:neigh_init
  - net/core/neighbour.c:neigh_init
  - net/core/neighbour.c:neigh_init
  - net/core/neighbour.c:neigh_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/fib_rules.c:fib_rules_init
  - net/core/fib_rules.c:fib_rules_init
  - net/core/fib_rules.c:fib_rules_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/act_api.c:tc_action_init
  - net/sched/act_api.c:tc_action_init
  - net/sched/act_api.c:tc_action_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/dcb/dcbnl.c:dcbnl_init
  - net/dcb/dcbnl.c:dcbnl_init
```
**Symbols:**

```
ffffffff8191ea95-ffffffff8191eaac: rtnl_register.cold (STB_LOCAL)
ffffffff8191e350-ffffffff8191e385: rtnl_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void rtnl_register(int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:267
Inline: False
Direct callers:
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/neighbour.c:neigh_init
  - net/core/neighbour.c:neigh_init
  - net/core/neighbour.c:neigh_init
  - net/core/neighbour.c:neigh_init
  - net/core/neighbour.c:neigh_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/fib_rules.c:fib_rules_init
  - net/core/fib_rules.c:fib_rules_init
  - net/core/fib_rules.c:fib_rules_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/act_api.c:tc_action_init
  - net/sched/act_api.c:tc_action_init
  - net/sched/act_api.c:tc_action_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/dcb/dcbnl.c:dcbnl_init
  - net/dcb/dcbnl.c:dcbnl_init
```
**Symbols:**

```
ffffffff81950d2e-ffffffff81950d45: rtnl_register.cold (STB_LOCAL)
ffffffff81950980-ffffffff819509b5: rtnl_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void rtnl_register(int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:267
Inline: False
Direct callers:
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/neighbour.c:neigh_init
  - net/core/neighbour.c:neigh_init
  - net/core/neighbour.c:neigh_init
  - net/core/neighbour.c:neigh_init
  - net/core/neighbour.c:neigh_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/fib_rules.c:fib_rules_init
  - net/core/fib_rules.c:fib_rules_init
  - net/core/fib_rules.c:fib_rules_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/act_api.c:tc_action_init
  - net/sched/act_api.c:tc_action_init
  - net/sched/act_api.c:tc_action_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/dcb/dcbnl.c:dcbnl_init
  - net/dcb/dcbnl.c:dcbnl_init
```
**Symbols:**

```
ffffffff81a21bc6-ffffffff81a21bdd: rtnl_register.cold (STB_LOCAL)
ffffffff81a21790-ffffffff81a217c5: rtnl_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void rtnl_register(int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:267
Inline: False
Direct callers:
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/neighbour.c:neigh_init
  - net/core/neighbour.c:neigh_init
  - net/core/neighbour.c:neigh_init
  - net/core/neighbour.c:neigh_init
  - net/core/neighbour.c:neigh_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/fib_rules.c:fib_rules_init
  - net/core/fib_rules.c:fib_rules_init
  - net/core/fib_rules.c:fib_rules_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/act_api.c:tc_action_init
  - net/sched/act_api.c:tc_action_init
  - net/sched/act_api.c:tc_action_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/dcb/dcbnl.c:dcbnl_init
  - net/dcb/dcbnl.c:dcbnl_init
```
**Symbols:**

```
ffffffff81c31703-ffffffff81c3171a: rtnl_register.cold (STB_LOCAL)
ffffffff81a21bd0-ffffffff81a21c05: rtnl_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void rtnl_register(int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:267
Inline: False
Direct callers:
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/neighbour.c:neigh_init
  - net/core/neighbour.c:neigh_init
  - net/core/neighbour.c:neigh_init
  - net/core/neighbour.c:neigh_init
  - net/core/neighbour.c:neigh_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/fib_rules.c:fib_rules_init
  - net/core/fib_rules.c:fib_rules_init
  - net/core/fib_rules.c:fib_rules_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/act_api.c:tc_action_init
  - net/sched/act_api.c:tc_action_init
  - net/sched/act_api.c:tc_action_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/dcb/dcbnl.c:dcbnl_init
  - net/dcb/dcbnl.c:dcbnl_init
```
**Symbols:**

```
ffffffff81c23a0c-ffffffff81c23a23: rtnl_register.cold (STB_LOCAL)
ffffffff81a08f10-ffffffff81a08f45: rtnl_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void rtnl_register(int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:267
Inline: False
Direct callers:
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/neighbour.c:neigh_init
  - net/core/neighbour.c:neigh_init
  - net/core/neighbour.c:neigh_init
  - net/core/neighbour.c:neigh_init
  - net/core/neighbour.c:neigh_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/fib_rules.c:fib_rules_init
  - net/core/fib_rules.c:fib_rules_init
  - net/core/fib_rules.c:fib_rules_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/act_api.c:tc_action_init
  - net/sched/act_api.c:tc_action_init
  - net/sched/act_api.c:tc_action_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/dcb/dcbnl.c:dcbnl_init
  - net/dcb/dcbnl.c:dcbnl_init
```
**Symbols:**

```
ffffffff81d36f4b-ffffffff81d36f62: rtnl_register.cold (STB_LOCAL)
ffffffff81abb470-ffffffff81abb4a5: rtnl_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void rtnl_register(int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81f0389e)
Location: net/core/rtnetlink.c:304
Inline: True
Direct callers:
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/neighbour.c:neigh_init
  - net/core/neighbour.c:neigh_init
  - net/core/neighbour.c:neigh_init
  - net/core/neighbour.c:neigh_init
  - net/core/neighbour.c:neigh_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/fib_rules.c:fib_rules_init
  - net/core/fib_rules.c:fib_rules_init
  - net/core/fib_rules.c:fib_rules_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/act_api.c:tc_action_init
  - net/sched/act_api.c:tc_action_init
  - net/sched/act_api.c:tc_action_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/dcb/dcbnl.c:dcbnl_init
  - net/dcb/dcbnl.c:dcbnl_init
```
**Symbols:**

```
ffffffff81f0389e-ffffffff81f038b4: rtnl_register.cold (STB_LOCAL)
ffffffff81c35c80-ffffffff81c35cc6: rtnl_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void rtnl_register(int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff83f0ce19)
Location: net/core/rtnetlink.c:305
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
Direct callers:
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/neighbour.c:neigh_init
  - net/core/neighbour.c:neigh_init
  - net/core/neighbour.c:neigh_init
  - net/core/neighbour.c:neigh_init
  - net/core/neighbour.c:neigh_init
  - net/core/fib_rules.c:fib_rules_init
  - net/core/fib_rules.c:fib_rules_init
  - net/core/fib_rules.c:fib_rules_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/act_api.c:tc_action_init
  - net/sched/act_api.c:tc_action_init
  - net/sched/act_api.c:tc_action_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/dcb/dcbnl.c:dcbnl_init
  - net/dcb/dcbnl.c:dcbnl_init
```
**Symbols:**

```
ffffffff81de91f0-ffffffff81de925c: rtnl_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void rtnl_register(int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff837331b9)
Location: net/core/rtnetlink.c:308
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
Direct callers:
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/neighbour.c:neigh_init
  - net/core/neighbour.c:neigh_init
  - net/core/neighbour.c:neigh_init
  - net/core/neighbour.c:neigh_init
  - net/core/neighbour.c:neigh_init
  - net/core/fib_rules.c:fib_rules_init
  - net/core/fib_rules.c:fib_rules_init
  - net/core/fib_rules.c:fib_rules_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/act_api.c:tc_action_init
  - net/sched/act_api.c:tc_action_init
  - net/sched/act_api.c:tc_action_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/dcb/dcbnl.c:dcbnl_init
  - net/dcb/dcbnl.c:dcbnl_init
```
**Symbols:**

```
ffffffff81e5aa30-ffffffff81e5aa9c: rtnl_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void rtnl_register(int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff83967699)
Location: net/core/rtnetlink.c:309
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
Direct callers:
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/neighbour.c:neigh_init
  - net/core/neighbour.c:neigh_init
  - net/core/neighbour.c:neigh_init
  - net/core/neighbour.c:neigh_init
  - net/core/neighbour.c:neigh_init
  - net/core/fib_rules.c:fib_rules_init
  - net/core/fib_rules.c:fib_rules_init
  - net/core/fib_rules.c:fib_rules_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/act_api.c:tc_action_init
  - net/sched/act_api.c:tc_action_init
  - net/sched/act_api.c:tc_action_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/dcb/dcbnl.c:dcbnl_init
  - net/dcb/dcbnl.c:dcbnl_init
```
**Symbols:**

```
ffffffff81f19df0-ffffffff81f19e5c: rtnl_register (STB_GLOBAL)
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
void rtnl_register(int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffff800010bf23c8)
Location: net/core/rtnetlink.c:267
Inline: False
Direct callers:
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/neighbour.c:neigh_init
  - net/core/neighbour.c:neigh_init
  - net/core/neighbour.c:neigh_init
  - net/core/neighbour.c:neigh_init
  - net/core/neighbour.c:neigh_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/fib_rules.c:fib_rules_init
  - net/core/fib_rules.c:fib_rules_init
  - net/core/fib_rules.c:fib_rules_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/act_api.c:tc_action_init
  - net/sched/act_api.c:tc_action_init
  - net/sched/act_api.c:tc_action_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/dcb/dcbnl.c:dcbnl_init
  - net/dcb/dcbnl.c:dcbnl_init
```
**Symbols:**

```
ffff800010bf23c8-ffff800010bf2444: rtnl_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void rtnl_register(int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (c0d0acf0)
Location: net/core/rtnetlink.c:267
Inline: False
Direct callers:
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/neighbour.c:neigh_init
  - net/core/neighbour.c:neigh_init
  - net/core/neighbour.c:neigh_init
  - net/core/neighbour.c:neigh_init
  - net/core/neighbour.c:neigh_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/fib_rules.c:fib_rules_init
  - net/core/fib_rules.c:fib_rules_init
  - net/core/fib_rules.c:fib_rules_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/act_api.c:tc_action_init
  - net/sched/act_api.c:tc_action_init
  - net/sched/act_api.c:tc_action_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/dcb/dcbnl.c:dcbnl_init
  - net/dcb/dcbnl.c:dcbnl_init
```
**Symbols:**

```
c0d0acf0-c0d0ad5c: rtnl_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void rtnl_register(int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (c000000000cd7290)
Location: net/core/rtnetlink.c:267
Inline: False
Direct callers:
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/neighbour.c:neigh_init
  - net/core/neighbour.c:neigh_init
  - net/core/neighbour.c:neigh_init
  - net/core/neighbour.c:neigh_init
  - net/core/neighbour.c:neigh_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/fib_rules.c:fib_rules_init
  - net/core/fib_rules.c:fib_rules_init
  - net/core/fib_rules.c:fib_rules_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/act_api.c:tc_action_init
  - net/sched/act_api.c:tc_action_init
  - net/sched/act_api.c:tc_action_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/dcb/dcbnl.c:dcbnl_init
  - net/dcb/dcbnl.c:dcbnl_init
```
**Symbols:**

```
c000000000cd7290-c000000000cd7318: rtnl_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void rtnl_register(int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffe000773f68)
Location: net/core/rtnetlink.c:267
Inline: False
Direct callers:
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/neighbour.c:neigh_init
  - net/core/neighbour.c:neigh_init
  - net/core/neighbour.c:neigh_init
  - net/core/neighbour.c:neigh_init
  - net/core/neighbour.c:neigh_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/fib_rules.c:fib_rules_init
  - net/core/fib_rules.c:fib_rules_init
  - net/core/fib_rules.c:fib_rules_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/act_api.c:tc_action_init
  - net/sched/act_api.c:tc_action_init
  - net/sched/act_api.c:tc_action_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/dcb/dcbnl.c:dcbnl_init
  - net/dcb/dcbnl.c:dcbnl_init
```
**Symbols:**

```
ffffffe000773f68-ffffffe000773fcc: rtnl_register (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void rtnl_register(int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:267
Inline: False
Direct callers:
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/neighbour.c:neigh_init
  - net/core/neighbour.c:neigh_init
  - net/core/neighbour.c:neigh_init
  - net/core/neighbour.c:neigh_init
  - net/core/neighbour.c:neigh_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/fib_rules.c:fib_rules_init
  - net/core/fib_rules.c:fib_rules_init
  - net/core/fib_rules.c:fib_rules_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/act_api.c:tc_action_init
  - net/sched/act_api.c:tc_action_init
  - net/sched/act_api.c:tc_action_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/dcb/dcbnl.c:dcbnl_init
  - net/dcb/dcbnl.c:dcbnl_init
```
**Symbols:**

```
ffffffff818f0cfe-ffffffff818f0d15: rtnl_register.cold (STB_LOCAL)
ffffffff818f0950-ffffffff818f0985: rtnl_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void rtnl_register(int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:267
Inline: False
Direct callers:
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/neighbour.c:neigh_init
  - net/core/neighbour.c:neigh_init
  - net/core/neighbour.c:neigh_init
  - net/core/neighbour.c:neigh_init
  - net/core/neighbour.c:neigh_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/fib_rules.c:fib_rules_init
  - net/core/fib_rules.c:fib_rules_init
  - net/core/fib_rules.c:fib_rules_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/act_api.c:tc_action_init
  - net/sched/act_api.c:tc_action_init
  - net/sched/act_api.c:tc_action_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/dcb/dcbnl.c:dcbnl_init
  - net/dcb/dcbnl.c:dcbnl_init
```
**Symbols:**

```
ffffffff818aab3e-ffffffff818aab55: rtnl_register.cold (STB_LOCAL)
ffffffff818aa790-ffffffff818aa7c5: rtnl_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void rtnl_register(int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:267
Inline: False
Direct callers:
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/neighbour.c:neigh_init
  - net/core/neighbour.c:neigh_init
  - net/core/neighbour.c:neigh_init
  - net/core/neighbour.c:neigh_init
  - net/core/neighbour.c:neigh_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/fib_rules.c:fib_rules_init
  - net/core/fib_rules.c:fib_rules_init
  - net/core/fib_rules.c:fib_rules_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/act_api.c:tc_action_init
  - net/sched/act_api.c:tc_action_init
  - net/sched/act_api.c:tc_action_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/dcb/dcbnl.c:dcbnl_init
  - net/dcb/dcbnl.c:dcbnl_init
```
**Symbols:**

```
ffffffff81941d2e-ffffffff81941d45: rtnl_register.cold (STB_LOCAL)
ffffffff81941980-ffffffff819419b5: rtnl_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void rtnl_register(int protocol, int msgtype, rtnl_doit_func doit, rtnl_dumpit_func dumpit, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:267
Inline: False
Direct callers:
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/neighbour.c:neigh_init
  - net/core/neighbour.c:neigh_init
  - net/core/neighbour.c:neigh_init
  - net/core/neighbour.c:neigh_init
  - net/core/neighbour.c:neigh_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/rtnetlink.c:rtnetlink_init
  - net/core/fib_rules.c:fib_rules_init
  - net/core/fib_rules.c:fib_rules_init
  - net/core/fib_rules.c:fib_rules_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/sch_api.c:pktsched_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/cls_api.c:tc_filter_init
  - net/sched/act_api.c:tc_action_init
  - net/sched/act_api.c:tc_action_init
  - net/sched/act_api.c:tc_action_init
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/fib_frontend.c:ip_fib_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/nexthop.c:nexthop_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv4/ipmr.c:ip_mr_init
  - net/dcb/dcbnl.c:dcbnl_init
  - net/dcb/dcbnl.c:dcbnl_init
```
**Symbols:**

```
ffffffff8196362e-ffffffff81963645: rtnl_register.cold (STB_LOCAL)
ffffffff81963280-ffffffff819632b5: rtnl_register (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int flags</code>
</li>
<li>
<b>Param removed. </b>
<code>rtnl_calcit_func calcit</code>
</li>
</ul>
</details>
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
