# Function: <code>nlmsg_msg_size</code>

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
In kernel/audit.c (0)
Location: include/net/netlink.h:265
Inline: True
```
```
In kernel/taskstats.c (0)
Location: include/net/netlink.h:265
Inline: True
```
```
In fs/quota/netlink.c (0)
Location: include/net/netlink.h:265
Inline: True
```
```
In security/selinux/netlink.c (0)
Location: include/net/netlink.h:265
Inline: True
```
```
In drivers/acpi/event.c (0)
Location: include/net/netlink.h:265
Inline: True
```
```
In drivers/connector/connector.c (0)
Location: include/net/netlink.h:265
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/net/netlink.h:265
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:265
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/net/netlink.h:265
Inline: True
```
```
In net/core/rtnetlink.c (0)
Location: include/net/netlink.h:265
Inline: True
```
```
In net/core/sock_diag.c (0)
Location: include/net/netlink.h:265
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:265
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/net/netlink.h:265
Inline: True
```
```
In net/sched/cls_api.c (0)
Location: include/net/netlink.h:265
Inline: True
```
```
In net/sched/act_api.c (0)
Location: include/net/netlink.h:265
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/net/netlink.h:265
Inline: True
```
```
In net/netlink/genetlink.c (0)
Location: include/net/netlink.h:265
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/net/netlink.h:265
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/net/netlink.h:265
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netlink.h:265
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/net/netlink.h:265
Inline: True
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/net/netlink.h:265
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/net/netlink.h:265
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/netlink.h:265
Inline: True
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:265
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/net/netlink.h:265
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/net/netlink.h:265
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/net/netlink.h:265
Inline: True
```
```
In net/wireless/wext-core.c (0)
Location: include/net/netlink.h:265
Inline: True
```
```
In net/netlabel/netlabel_mgmt.c (0)
Location: include/net/netlink.h:265
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/net/netlink.h:265
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (0)
Location: include/net/netlink.h:265
Inline: True
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/netlink.h:265
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
In kernel/audit.c (0)
Location: include/net/netlink.h:276
Inline: True
```
```
In kernel/taskstats.c (0)
Location: include/net/netlink.h:276
Inline: True
```
```
In fs/quota/netlink.c (0)
Location: include/net/netlink.h:276
Inline: True
```
```
In security/selinux/netlink.c (0)
Location: include/net/netlink.h:276
Inline: True
```
```
In drivers/acpi/event.c (0)
Location: include/net/netlink.h:276
Inline: True
```
```
In drivers/connector/connector.c (0)
Location: include/net/netlink.h:276
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/net/netlink.h:276
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:276
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/net/netlink.h:276
Inline: True
```
```
In net/core/rtnetlink.c (0)
Location: include/net/netlink.h:276
Inline: True
```
```
In net/core/sock_diag.c (0)
Location: include/net/netlink.h:276
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:276
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/net/netlink.h:276
Inline: True
```
```
In net/sched/cls_api.c (0)
Location: include/net/netlink.h:276
Inline: True
```
```
In net/sched/act_api.c (0)
Location: include/net/netlink.h:276
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff817b74cc)
Location: include/net/netlink.h:276
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__nlmsg_put
```
```
In net/netlink/genetlink.c (ffffffff817bb4fd)
Location: include/net/netlink.h:276
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/ipv4/route.c (0)
Location: include/net/netlink.h:276
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/net/netlink.h:276
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netlink.h:276
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/net/netlink.h:276
Inline: True
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/net/netlink.h:276
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/net/netlink.h:276
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/netlink.h:276
Inline: True
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:276
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/net/netlink.h:276
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/net/netlink.h:276
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/net/netlink.h:276
Inline: True
```
```
In net/wireless/wext-core.c (0)
Location: include/net/netlink.h:276
Inline: True
```
```
In net/netlabel/netlabel_mgmt.c (0)
Location: include/net/netlink.h:276
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/net/netlink.h:276
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (0)
Location: include/net/netlink.h:276
Inline: True
```
```
In net/netlabel/netlabel_calipso.c (0)
Location: include/net/netlink.h:276
Inline: True
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/netlink.h:276
Inline: True
```
```
In net/switchdev/switchdev.c (0)
Location: include/net/netlink.h:276
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
In kernel/audit.c (0)
Location: include/net/netlink.h:276
Inline: True
```
```
In kernel/taskstats.c (0)
Location: include/net/netlink.h:276
Inline: True
```
```
In fs/quota/netlink.c (0)
Location: include/net/netlink.h:276
Inline: True
```
```
In security/selinux/netlink.c (0)
Location: include/net/netlink.h:276
Inline: True
```
```
In drivers/acpi/event.c (0)
Location: include/net/netlink.h:276
Inline: True
```
```
In drivers/connector/connector.c (0)
Location: include/net/netlink.h:276
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/net/netlink.h:276
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:276
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/net/netlink.h:276
Inline: True
```
```
In net/core/rtnetlink.c (0)
Location: include/net/netlink.h:276
Inline: True
```
```
In net/core/sock_diag.c (0)
Location: include/net/netlink.h:276
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:276
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/net/netlink.h:276
Inline: True
```
```
In net/sched/cls_api.c (0)
Location: include/net/netlink.h:276
Inline: True
```
```
In net/sched/act_api.c (0)
Location: include/net/netlink.h:276
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff817e6f6c)
Location: include/net/netlink.h:276
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__nlmsg_put
```
```
In net/netlink/genetlink.c (ffffffff817eaf02)
Location: include/net/netlink.h:276
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/ipv4/route.c (0)
Location: include/net/netlink.h:276
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/net/netlink.h:276
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netlink.h:276
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/net/netlink.h:276
Inline: True
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/net/netlink.h:276
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/net/netlink.h:276
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/netlink.h:276
Inline: True
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:276
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/net/netlink.h:276
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/net/netlink.h:276
Inline: True
```
```
In net/ipv6/seg6.c (0)
Location: include/net/netlink.h:276
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/net/netlink.h:276
Inline: True
```
```
In net/wireless/wext-core.c (0)
Location: include/net/netlink.h:276
Inline: True
```
```
In net/netlabel/netlabel_mgmt.c (0)
Location: include/net/netlink.h:276
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/net/netlink.h:276
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (0)
Location: include/net/netlink.h:276
Inline: True
```
```
In net/netlabel/netlabel_calipso.c (0)
Location: include/net/netlink.h:276
Inline: True
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/netlink.h:276
Inline: True
```
```
In net/switchdev/switchdev.c (0)
Location: include/net/netlink.h:276
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
In kernel/audit.c (0)
Location: include/net/netlink.h:280
Inline: True
```
```
In kernel/taskstats.c (0)
Location: include/net/netlink.h:280
Inline: True
```
```
In fs/quota/netlink.c (0)
Location: include/net/netlink.h:280
Inline: True
```
```
In security/selinux/netlink.c (0)
Location: include/net/netlink.h:280
Inline: True
```
```
In drivers/acpi/event.c (0)
Location: include/net/netlink.h:280
Inline: True
```
```
In drivers/connector/connector.c (0)
Location: include/net/netlink.h:280
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/net/netlink.h:280
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:280
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/net/netlink.h:280
Inline: True
```
```
In net/core/rtnetlink.c (0)
Location: include/net/netlink.h:280
Inline: True
```
```
In net/core/sock_diag.c (0)
Location: include/net/netlink.h:280
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:280
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/net/netlink.h:280
Inline: True
```
```
In net/sched/cls_api.c (0)
Location: include/net/netlink.h:280
Inline: True
```
```
In net/sched/act_api.c (0)
Location: include/net/netlink.h:280
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81806ccc)
Location: include/net/netlink.h:280
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__nlmsg_put
```
```
In net/netlink/genetlink.c (ffffffff8180ae69)
Location: include/net/netlink.h:280
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/ipv4/route.c (0)
Location: include/net/netlink.h:280
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/net/netlink.h:280
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netlink.h:280
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/net/netlink.h:280
Inline: True
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/net/netlink.h:280
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/net/netlink.h:280
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/netlink.h:280
Inline: True
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:280
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/net/netlink.h:280
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/net/netlink.h:280
Inline: True
```
```
In net/ipv6/seg6.c (0)
Location: include/net/netlink.h:280
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/net/netlink.h:280
Inline: True
```
```
In net/wireless/wext-core.c (0)
Location: include/net/netlink.h:280
Inline: True
```
```
In net/netlabel/netlabel_mgmt.c (0)
Location: include/net/netlink.h:280
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/net/netlink.h:280
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (0)
Location: include/net/netlink.h:280
Inline: True
```
```
In net/netlabel/netlabel_calipso.c (0)
Location: include/net/netlink.h:280
Inline: True
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/netlink.h:280
Inline: True
```
```
In net/switchdev/switchdev.c (0)
Location: include/net/netlink.h:280
Inline: True
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
In kernel/audit.c (0)
Location: include/net/netlink.h:286
Inline: True
```
```
In kernel/taskstats.c (0)
Location: include/net/netlink.h:286
Inline: True
```
```
In fs/quota/netlink.c (0)
Location: include/net/netlink.h:286
Inline: True
```
```
In security/selinux/netlink.c (0)
Location: include/net/netlink.h:286
Inline: True
```
```
In drivers/acpi/event.c (0)
Location: include/net/netlink.h:286
Inline: True
```
```
In drivers/connector/connector.c (0)
Location: include/net/netlink.h:286
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/net/netlink.h:286
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:286
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/net/netlink.h:286
Inline: True
```
```
In net/core/rtnetlink.c (0)
Location: include/net/netlink.h:286
Inline: True
```
```
In net/core/sock_diag.c (0)
Location: include/net/netlink.h:286
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:286
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/net/netlink.h:286
Inline: True
```
```
In net/sched/cls_api.c (0)
Location: include/net/netlink.h:286
Inline: True
```
```
In net/sched/act_api.c (0)
Location: include/net/netlink.h:286
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff818859ac)
Location: include/net/netlink.h:286
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__nlmsg_put
```
```
In net/netlink/genetlink.c (ffffffff81889db9)
Location: include/net/netlink.h:286
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/ipv4/route.c (0)
Location: include/net/netlink.h:286
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/net/netlink.h:286
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netlink.h:286
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/net/netlink.h:286
Inline: True
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/net/netlink.h:286
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/net/netlink.h:286
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/netlink.h:286
Inline: True
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:286
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/net/netlink.h:286
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/net/netlink.h:286
Inline: True
```
```
In net/ipv6/seg6.c (0)
Location: include/net/netlink.h:286
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/net/netlink.h:286
Inline: True
```
```
In net/wireless/wext-core.c (0)
Location: include/net/netlink.h:286
Inline: True
```
```
In net/netlabel/netlabel_mgmt.c (0)
Location: include/net/netlink.h:286
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/net/netlink.h:286
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (0)
Location: include/net/netlink.h:286
Inline: True
```
```
In net/netlabel/netlabel_calipso.c (0)
Location: include/net/netlink.h:286
Inline: True
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/netlink.h:286
Inline: True
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
In kernel/audit.c (0)
Location: include/net/netlink.h:286
Inline: True
```
```
In kernel/taskstats.c (0)
Location: include/net/netlink.h:286
Inline: True
```
```
In fs/quota/netlink.c (0)
Location: include/net/netlink.h:286
Inline: True
```
```
In security/selinux/netlink.c (0)
Location: include/net/netlink.h:286
Inline: True
```
```
In drivers/acpi/event.c (0)
Location: include/net/netlink.h:286
Inline: True
```
```
In drivers/connector/connector.c (0)
Location: include/net/netlink.h:286
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/net/netlink.h:286
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:286
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/net/netlink.h:286
Inline: True
```
```
In net/core/rtnetlink.c (0)
Location: include/net/netlink.h:286
Inline: True
```
```
In net/core/sock_diag.c (0)
Location: include/net/netlink.h:286
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:286
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/net/netlink.h:286
Inline: True
```
```
In net/sched/cls_api.c (0)
Location: include/net/netlink.h:286
Inline: True
```
```
In net/sched/act_api.c (0)
Location: include/net/netlink.h:286
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff818d9335)
Location: include/net/netlink.h:286
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__nlmsg_put
```
```
In net/netlink/genetlink.c (ffffffff818dec58)
Location: include/net/netlink.h:286
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/ipv4/route.c (0)
Location: include/net/netlink.h:286
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/net/netlink.h:286
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netlink.h:286
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/net/netlink.h:286
Inline: True
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/net/netlink.h:286
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/net/netlink.h:286
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/netlink.h:286
Inline: True
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:286
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/net/netlink.h:286
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/net/netlink.h:286
Inline: True
```
```
In net/ipv6/seg6.c (0)
Location: include/net/netlink.h:286
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/net/netlink.h:286
Inline: True
```
```
In net/wireless/wext-core.c (0)
Location: include/net/netlink.h:286
Inline: True
```
```
In net/netlabel/netlabel_mgmt.c (0)
Location: include/net/netlink.h:286
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/net/netlink.h:286
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (0)
Location: include/net/netlink.h:286
Inline: True
```
```
In net/netlabel/netlabel_calipso.c (0)
Location: include/net/netlink.h:286
Inline: True
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/netlink.h:286
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (ffffffff819cafa4)
Location: include/net/netlink.h:286
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
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
In kernel/audit.c (0)
Location: include/net/netlink.h:413
Inline: True
```
```
In kernel/taskstats.c (0)
Location: include/net/netlink.h:413
Inline: True
```
```
In fs/quota/netlink.c (0)
Location: include/net/netlink.h:413
Inline: True
```
```
In security/selinux/netlink.c (0)
Location: include/net/netlink.h:413
Inline: True
```
```
In drivers/acpi/event.c (0)
Location: include/net/netlink.h:413
Inline: True
```
```
In drivers/connector/connector.c (0)
Location: include/net/netlink.h:413
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/net/netlink.h:413
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:413
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/net/netlink.h:413
Inline: True
```
```
In net/core/rtnetlink.c (0)
Location: include/net/netlink.h:413
Inline: True
```
```
In net/core/sock_diag.c (0)
Location: include/net/netlink.h:413
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:413
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/net/netlink.h:413
Inline: True
```
```
In net/sched/cls_api.c (0)
Location: include/net/netlink.h:413
Inline: True
```
```
In net/sched/act_api.c (0)
Location: include/net/netlink.h:413
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81905b25)
Location: include/net/netlink.h:413
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__nlmsg_put
```
```
In net/netlink/genetlink.c (ffffffff8190b618)
Location: include/net/netlink.h:413
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/ipv4/route.c (0)
Location: include/net/netlink.h:413
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/net/netlink.h:413
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netlink.h:413
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/net/netlink.h:413
Inline: True
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/net/netlink.h:413
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/net/netlink.h:413
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/netlink.h:413
Inline: True
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:413
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/net/netlink.h:413
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/net/netlink.h:413
Inline: True
```
```
In net/ipv6/seg6.c (0)
Location: include/net/netlink.h:413
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/net/netlink.h:413
Inline: True
```
```
In net/wireless/wext-core.c (0)
Location: include/net/netlink.h:413
Inline: True
```
```
In net/netlabel/netlabel_mgmt.c (0)
Location: include/net/netlink.h:413
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/net/netlink.h:413
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (0)
Location: include/net/netlink.h:413
Inline: True
```
```
In net/netlabel/netlabel_calipso.c (0)
Location: include/net/netlink.h:413
Inline: True
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/netlink.h:413
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81a03a64)
Location: include/net/netlink.h:413
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
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
In kernel/audit.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In kernel/taskstats.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In fs/quota/netlink.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In security/selinux/netlink.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In drivers/acpi/event.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In drivers/connector/connector.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/core/rtnetlink.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/core/sock_diag.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/core/devlink.c (ffffffff819518b9)
Location: include/net/netlink.h:474
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
```
```
In net/sched/sch_api.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/sched/cls_api.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/sched/act_api.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81966d75)
Location: include/net/netlink.h:474
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__nlmsg_put
```
```
In net/netlink/genetlink.c (ffffffff8196c5cb)
Location: include/net/netlink.h:474
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/ipv4/route.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv4/nexthop.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv6/seg6.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/wireless/wext-core.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/netlabel/netlabel_mgmt.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/netlabel/netlabel_calipso.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81a72d14)
Location: include/net/netlink.h:474
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
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
In kernel/audit.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In kernel/taskstats.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In fs/quota/netlink.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In security/selinux/netlink.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In drivers/acpi/event.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In drivers/connector/connector.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/core/rtnetlink.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/core/sock_diag.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff81975c9b)
Location: include/net/netlink.h:474
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/devlink.c (ffffffff819882f9)
Location: include/net/netlink.h:474
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
```
```
In net/sched/sch_api.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/sched/cls_api.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/sched/act_api.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff8199d7f5)
Location: include/net/netlink.h:474
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__nlmsg_put
```
```
In net/netlink/genetlink.c (ffffffff819a2f7b)
Location: include/net/netlink.h:474
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/ipv4/route.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv4/nexthop.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv6/seg6.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/wireless/wext-core.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/netlabel/netlabel_mgmt.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/netlabel/netlabel_calipso.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81aa94f4)
Location: include/net/netlink.h:474
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
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
In kernel/audit.c (0)
Location: include/net/netlink.h:526
Inline: True
```
```
In kernel/taskstats.c (0)
Location: include/net/netlink.h:526
Inline: True
```
```
In fs/quota/netlink.c (0)
Location: include/net/netlink.h:526
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/net/netlink.h:526
Inline: True
```
```
In security/selinux/netlink.c (0)
Location: include/net/netlink.h:526
Inline: True
```
```
In drivers/acpi/event.c (0)
Location: include/net/netlink.h:526
Inline: True
```
```
In drivers/connector/connector.c (0)
Location: include/net/netlink.h:526
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:526
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/net/netlink.h:526
Inline: True
```
```
In net/core/rtnetlink.c (0)
Location: include/net/netlink.h:526
Inline: True
```
```
In net/core/sock_diag.c (0)
Location: include/net/netlink.h:526
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:526
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff81a491d5)
Location: include/net/netlink.h:526
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_report_size
  - net/core/drop_monitor.c:net_dm_packet_report
```
```
In net/core/devlink.c (0)
Location: include/net/netlink.h:526
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/net/netlink.h:526
Inline: True
```
```
In net/sched/cls_api.c (0)
Location: include/net/netlink.h:526
Inline: True
```
```
In net/sched/act_api.c (0)
Location: include/net/netlink.h:526
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81a767d5)
Location: include/net/netlink.h:526
Inline: True
```
```
In net/netlink/genetlink.c (ffffffff81a7c59f)
Location: include/net/netlink.h:526
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:genl_family_rcv_msg
  - net/netlink/genetlink.c:genl_start
```
```
In net/ethtool/netlink.c (0)
Location: include/net/netlink.h:526
Inline: True
```
```
In net/ethtool/linkinfo.c (0)
Location: include/net/netlink.h:526
Inline: True
```
```
In net/ethtool/linkmodes.c (0)
Location: include/net/netlink.h:526
Inline: True
```
```
In net/ethtool/debug.c (0)
Location: include/net/netlink.h:526
Inline: True
```
```
In net/ethtool/wol.c (0)
Location: include/net/netlink.h:526
Inline: True
```
```
In net/ethtool/features.c (0)
Location: include/net/netlink.h:526
Inline: True
```
```
In net/ethtool/privflags.c (0)
Location: include/net/netlink.h:526
Inline: True
```
```
In net/ethtool/rings.c (0)
Location: include/net/netlink.h:526
Inline: True
```
```
In net/ethtool/channels.c (0)
Location: include/net/netlink.h:526
Inline: True
```
```
In net/ethtool/coalesce.c (0)
Location: include/net/netlink.h:526
Inline: True
```
```
In net/ethtool/pause.c (0)
Location: include/net/netlink.h:526
Inline: True
```
```
In net/ethtool/eee.c (0)
Location: include/net/netlink.h:526
Inline: True
```
```
In net/ethtool/cabletest.c (0)
Location: include/net/netlink.h:526
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/net/netlink.h:526
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/net/netlink.h:526
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netlink.h:526
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/net/netlink.h:526
Inline: True
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/net/netlink.h:526
Inline: True
```
```
In net/ipv4/nexthop.c (0)
Location: include/net/netlink.h:526
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/net/netlink.h:526
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/netlink.h:526
Inline: True
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:526
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/net/netlink.h:526
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/net/netlink.h:526
Inline: True
```
```
In net/ipv6/seg6.c (0)
Location: include/net/netlink.h:526
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/net/netlink.h:526
Inline: True
```
```
In net/wireless/wext-core.c (0)
Location: include/net/netlink.h:526
Inline: True
```
```
In net/netlabel/netlabel_mgmt.c (0)
Location: include/net/netlink.h:526
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/net/netlink.h:526
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (0)
Location: include/net/netlink.h:526
Inline: True
```
```
In net/netlabel/netlabel_calipso.c (0)
Location: include/net/netlink.h:526
Inline: True
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/netlink.h:526
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81ba5864)
Location: include/net/netlink.h:526
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
```
```
In net/mptcp/pm_netlink.c (0)
Location: include/net/netlink.h:526
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
In kernel/audit.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In kernel/taskstats.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In fs/quota/netlink.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In security/selinux/netlink.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In drivers/acpi/event.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In drivers/connector/connector.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In drivers/thermal/thermal_netlink.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/core/rtnetlink.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/core/sock_diag.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff81a4e9c5)
Location: include/net/netlink.h:541
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_report_size
  - net/core/drop_monitor.c:net_dm_packet_report
```
```
In net/core/devlink.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/sched/cls_api.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/sched/act_api.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81a7f53b)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/netlink/genetlink.c (ffffffff81a8553a)
Location: include/net/netlink.h:541
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
  - net/netlink/genetlink.c:genl_start
```
```
In net/ethtool/netlink.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/ethtool/cabletest.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/ipv4/nexthop.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/ipv6/seg6.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/wireless/wext-core.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/netlabel/netlabel_mgmt.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/netlabel/netlabel_calipso.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81bb4d34)
Location: include/net/netlink.h:541
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
```
```
In net/mptcp/pm_netlink.c (0)
Location: include/net/netlink.h:541
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
In kernel/audit.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In kernel/taskstats.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In fs/quota/netlink.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In security/selinux/netlink.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In drivers/acpi/event.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In drivers/connector/connector.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In drivers/thermal/thermal_netlink.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/core/rtnetlink.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/core/sock_diag.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff81a339e5)
Location: include/net/netlink.h:541
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_report_size
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/devlink.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/sched/cls_api.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/sched/act_api.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81a6851b)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/netlink/genetlink.c (ffffffff81a6e63f)
Location: include/net/netlink.h:541
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_rcv_msg
  - net/netlink/genetlink.c:genl_start
```
```
In net/ethtool/netlink.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/ethtool/cabletest.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/ipv4/fib_trie.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/ipv4/nexthop.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/ipv6/seg6.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/wireless/wext-core.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/netlabel/netlabel_mgmt.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/netlabel/netlabel_calipso.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81ba3d14)
Location: include/net/netlink.h:541
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
```
```
In net/mptcp/pm_netlink.c (0)
Location: include/net/netlink.h:541
Inline: True
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
In kernel/audit.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In kernel/taskstats.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In fs/quota/netlink.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In security/selinux/netlink.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In drivers/acpi/event.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In drivers/connector/connector.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In drivers/net/wwan/wwan_core.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In drivers/thermal/thermal_netlink.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/core/rtnetlink.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/core/sock_diag.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff81ae93d5)
Location: include/net/netlink.h:541
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_report_size
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/devlink.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/sched/cls_api.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/sched/act_api.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81b21a8b)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/netlink/genetlink.c (ffffffff81b27cbf)
Location: include/net/netlink.h:541
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_rcv_msg
  - net/netlink/genetlink.c:genl_start
```
```
In net/ethtool/netlink.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/ethtool/cabletest.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/ipv4/fib_trie.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/ipv4/nexthop.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/ipv6/seg6.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/wireless/wext-core.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/netlabel/netlabel_mgmt.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/netlabel/netlabel_calipso.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81c71674)
Location: include/net/netlink.h:541
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
```
```
In net/mptcp/pm_netlink.c (0)
Location: include/net/netlink.h:541
Inline: True
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
In kernel/audit.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In kernel/taskstats.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In fs/quota/netlink.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In security/selinux/netlink.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In drivers/acpi/event.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In drivers/connector/connector.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In drivers/net/wwan/wwan_core.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In drivers/thermal/thermal_netlink.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/core/rtnetlink.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/core/sock_diag.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff81c6bb95)
Location: include/net/netlink.h:541
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_report_size
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/devlink.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/sched/cls_api.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/sched/act_api.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81caa24a)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/netlink/genetlink.c (ffffffff81cb0d51)
Location: include/net/netlink.h:541
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_rcv_msg
  - net/netlink/genetlink.c:genl_start
```
```
In net/ethtool/netlink.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/ethtool/cabletest.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/ipv4/fib_trie.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/ipv4/nexthop.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/ipv6/seg6.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/wireless/wext-core.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/netlabel/netlabel_mgmt.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/netlabel/netlabel_calipso.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81e15229)
Location: include/net/netlink.h:541
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
```
```
In net/mptcp/pm_netlink.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/mctp/device.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/mctp/route.c (0)
Location: include/net/netlink.h:541
Inline: True
```
```
In net/mctp/neigh.c (0)
Location: include/net/netlink.h:541
Inline: True
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
In kernel/audit.c (0)
Location: include/net/netlink.h:556
Inline: True
```
```
In kernel/taskstats.c (0)
Location: include/net/netlink.h:556
Inline: True
```
```
In fs/quota/netlink.c (0)
Location: include/net/netlink.h:556
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/net/netlink.h:556
Inline: True
```
```
In security/selinux/netlink.c (0)
Location: include/net/netlink.h:556
Inline: True
```
```
In drivers/acpi/event.c (0)
Location: include/net/netlink.h:556
Inline: True
```
```
In drivers/connector/connector.c (0)
Location: include/net/netlink.h:556
Inline: True
```
```
In drivers/net/wwan/wwan_core.c (0)
Location: include/net/netlink.h:556
Inline: True
```
```
In drivers/thermal/thermal_netlink.c (0)
Location: include/net/netlink.h:556
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:556
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/net/netlink.h:556
Inline: True
```
```
In net/core/rtnetlink.c (0)
Location: include/net/netlink.h:556
Inline: True
```
```
In net/core/sock_diag.c (0)
Location: include/net/netlink.h:556
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:556
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff81e23645)
Location: include/net/netlink.h:556
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_report_size
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/devlink.c (0)
Location: include/net/netlink.h:556
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/net/netlink.h:556
Inline: True
```
```
In net/sched/cls_api.c (0)
Location: include/net/netlink.h:556
Inline: True
```
```
In net/sched/act_api.c (0)
Location: include/net/netlink.h:556
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81e6732a)
Location: include/net/netlink.h:556
Inline: True
```
```
In net/netlink/genetlink.c (ffffffff81e6e8df)
Location: include/net/netlink.h:556
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
  - net/netlink/genetlink.c:genl_start
```
```
In net/ethtool/netlink.c (0)
Location: include/net/netlink.h:556
Inline: True
```
```
In net/ethtool/cabletest.c (0)
Location: include/net/netlink.h:556
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/net/netlink.h:556
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/net/netlink.h:556
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netlink.h:556
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/net/netlink.h:556
Inline: True
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/net/netlink.h:556
Inline: True
```
```
In net/ipv4/fib_trie.c (0)
Location: include/net/netlink.h:556
Inline: True
```
```
In net/ipv4/nexthop.c (0)
Location: include/net/netlink.h:556
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/net/netlink.h:556
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/netlink.h:556
Inline: True
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:556
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/net/netlink.h:556
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/net/netlink.h:556
Inline: True
```
```
In net/ipv6/seg6.c (0)
Location: include/net/netlink.h:556
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/net/netlink.h:556
Inline: True
```
```
In net/wireless/wext-core.c (0)
Location: include/net/netlink.h:556
Inline: True
```
```
In net/netlabel/netlabel_mgmt.c (0)
Location: include/net/netlink.h:556
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/net/netlink.h:556
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (0)
Location: include/net/netlink.h:556
Inline: True
```
```
In net/netlabel/netlabel_calipso.c (0)
Location: include/net/netlink.h:556
Inline: True
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/netlink.h:556
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81fec189)
Location: include/net/netlink.h:556
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
```
```
In net/mptcp/pm_netlink.c (0)
Location: include/net/netlink.h:556
Inline: True
```
```
In net/mctp/device.c (0)
Location: include/net/netlink.h:556
Inline: True
```
```
In net/mctp/route.c (0)
Location: include/net/netlink.h:556
Inline: True
```
```
In net/mctp/neigh.c (0)
Location: include/net/netlink.h:556
Inline: True
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
In kernel/audit.c (0)
Location: include/net/netlink.h:557
Inline: True
```
```
In kernel/taskstats.c (0)
Location: include/net/netlink.h:557
Inline: True
```
```
In fs/quota/netlink.c (0)
Location: include/net/netlink.h:557
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/net/netlink.h:557
Inline: True
```
```
In security/selinux/netlink.c (0)
Location: include/net/netlink.h:557
Inline: True
```
```
In drivers/acpi/event.c (0)
Location: include/net/netlink.h:557
Inline: True
```
```
In drivers/connector/connector.c (0)
Location: include/net/netlink.h:557
Inline: True
```
```
In drivers/net/wwan/wwan_core.c (0)
Location: include/net/netlink.h:557
Inline: True
```
```
In drivers/thermal/thermal_netlink.c (0)
Location: include/net/netlink.h:557
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:557
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/net/netlink.h:557
Inline: True
```
```
In net/core/rtnetlink.c (0)
Location: include/net/netlink.h:557
Inline: True
```
```
In net/core/sock_diag.c (0)
Location: include/net/netlink.h:557
Inline: True
```
```
In net/core/netdev-genl.c (0)
Location: include/net/netlink.h:557
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:557
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff81e98b85)
Location: include/net/netlink.h:557
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_report_size
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/sched/sch_api.c (0)
Location: include/net/netlink.h:557
Inline: True
```
```
In net/sched/cls_api.c (0)
Location: include/net/netlink.h:557
Inline: True
```
```
In net/sched/act_api.c (0)
Location: include/net/netlink.h:557
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81ec311a)
Location: include/net/netlink.h:557
Inline: True
```
```
In net/netlink/genetlink.c (ffffffff81eca86f)
Location: include/net/netlink.h:557
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
  - net/netlink/genetlink.c:genl_start
```
```
In net/ethtool/netlink.c (0)
Location: include/net/netlink.h:557
Inline: True
```
```
In net/ethtool/cabletest.c (0)
Location: include/net/netlink.h:557
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/net/netlink.h:557
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/net/netlink.h:557
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netlink.h:557
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/net/netlink.h:557
Inline: True
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/net/netlink.h:557
Inline: True
```
```
In net/ipv4/fib_trie.c (0)
Location: include/net/netlink.h:557
Inline: True
```
```
In net/ipv4/nexthop.c (0)
Location: include/net/netlink.h:557
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/net/netlink.h:557
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/netlink.h:557
Inline: True
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:557
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/net/netlink.h:557
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/net/netlink.h:557
Inline: True
```
```
In net/ipv6/seg6.c (0)
Location: include/net/netlink.h:557
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/net/netlink.h:557
Inline: True
```
```
In net/devlink/leftover.c (0)
Location: include/net/netlink.h:557
Inline: True
```
```
In net/devlink/dev.c (0)
Location: include/net/netlink.h:557
Inline: True
```
```
In net/devlink/health.c (0)
Location: include/net/netlink.h:557
Inline: True
```
```
In net/wireless/wext-core.c (0)
Location: include/net/netlink.h:557
Inline: True
```
```
In net/netlabel/netlabel_mgmt.c (0)
Location: include/net/netlink.h:557
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/net/netlink.h:557
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (0)
Location: include/net/netlink.h:557
Inline: True
```
```
In net/netlabel/netlabel_calipso.c (0)
Location: include/net/netlink.h:557
Inline: True
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/netlink.h:557
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (ffffffff82068429)
Location: include/net/netlink.h:557
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
```
```
In net/mptcp/pm_netlink.c (0)
Location: include/net/netlink.h:557
Inline: True
```
```
In net/mctp/device.c (0)
Location: include/net/netlink.h:557
Inline: True
```
```
In net/mctp/route.c (0)
Location: include/net/netlink.h:557
Inline: True
```
```
In net/mctp/neigh.c (0)
Location: include/net/netlink.h:557
Inline: True
```
```
In net/handshake/netlink.c (0)
Location: include/net/netlink.h:557
Inline: True
```
```
In net/handshake/tlshd.c (0)
Location: include/net/netlink.h:557
Inline: True
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
In kernel/audit.c (0)
Location: include/net/netlink.h:564
Inline: True
```
```
In kernel/taskstats.c (0)
Location: include/net/netlink.h:564
Inline: True
```
```
In fs/quota/netlink.c (0)
Location: include/net/netlink.h:564
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/net/netlink.h:564
Inline: True
```
```
In security/selinux/netlink.c (0)
Location: include/net/netlink.h:564
Inline: True
```
```
In drivers/acpi/event.c (0)
Location: include/net/netlink.h:564
Inline: True
```
```
In drivers/regulator/event.c (0)
Location: include/net/netlink.h:564
Inline: True
```
```
In drivers/connector/connector.c (0)
Location: include/net/netlink.h:564
Inline: True
```
```
In drivers/thermal/thermal_netlink.c (0)
Location: include/net/netlink.h:564
Inline: True
```
```
In drivers/dpll/dpll_netlink.c (0)
Location: include/net/netlink.h:564
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:564
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/net/netlink.h:564
Inline: True
```
```
In net/core/rtnetlink.c (0)
Location: include/net/netlink.h:564
Inline: True
```
```
In net/core/sock_diag.c (0)
Location: include/net/netlink.h:564
Inline: True
```
```
In net/core/netdev-genl.c (0)
Location: include/net/netlink.h:564
Inline: True
```
```
In net/core/page_pool_user.c (0)
Location: include/net/netlink.h:564
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:564
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff81f5b215)
Location: include/net/netlink.h:564
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_report_size
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/sched/sch_api.c (0)
Location: include/net/netlink.h:564
Inline: True
```
```
In net/sched/cls_api.c (0)
Location: include/net/netlink.h:564
Inline: True
```
```
In net/sched/act_api.c (0)
Location: include/net/netlink.h:564
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81f8646a)
Location: include/net/netlink.h:564
Inline: True
```
```
In net/netlink/genetlink.c (ffffffff81f8da7e)
Location: include/net/netlink.h:564
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
  - net/netlink/genetlink.c:genl_start
```
```
In net/ethtool/netlink.c (0)
Location: include/net/netlink.h:564
Inline: True
```
```
In net/ethtool/cabletest.c (0)
Location: include/net/netlink.h:564
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/net/netlink.h:564
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/net/netlink.h:564
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netlink.h:564
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/net/netlink.h:564
Inline: True
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/net/netlink.h:564
Inline: True
```
```
In net/ipv4/fib_trie.c (0)
Location: include/net/netlink.h:564
Inline: True
```
```
In net/ipv4/nexthop.c (0)
Location: include/net/netlink.h:564
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/net/netlink.h:564
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/netlink.h:564
Inline: True
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:564
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/net/netlink.h:564
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/net/netlink.h:564
Inline: True
```
```
In net/ipv6/seg6.c (0)
Location: include/net/netlink.h:564
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/net/netlink.h:564
Inline: True
```
```
In net/devlink/netlink.c (0)
Location: include/net/netlink.h:564
Inline: True
```
```
In net/devlink/dev.c (0)
Location: include/net/netlink.h:564
Inline: True
```
```
In net/devlink/port.c (0)
Location: include/net/netlink.h:564
Inline: True
```
```
In net/devlink/sb.c (0)
Location: include/net/netlink.h:564
Inline: True
```
```
In net/devlink/dpipe.c (0)
Location: include/net/netlink.h:564
Inline: True
```
```
In net/devlink/resource.c (0)
Location: include/net/netlink.h:564
Inline: True
```
```
In net/devlink/param.c (0)
Location: include/net/netlink.h:564
Inline: True
```
```
In net/devlink/region.c (0)
Location: include/net/netlink.h:564
Inline: True
```
```
In net/devlink/health.c (0)
Location: include/net/netlink.h:564
Inline: True
```
```
In net/devlink/trap.c (0)
Location: include/net/netlink.h:564
Inline: True
```
```
In net/devlink/rate.c (0)
Location: include/net/netlink.h:564
Inline: True
```
```
In net/devlink/linecard.c (0)
Location: include/net/netlink.h:564
Inline: True
```
```
In net/wireless/wext-core.c (0)
Location: include/net/netlink.h:564
Inline: True
```
```
In net/netlabel/netlabel_mgmt.c (0)
Location: include/net/netlink.h:564
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/net/netlink.h:564
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (0)
Location: include/net/netlink.h:564
Inline: True
```
```
In net/netlabel/netlabel_calipso.c (0)
Location: include/net/netlink.h:564
Inline: True
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/netlink.h:564
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (ffffffff8213b6a9)
Location: include/net/netlink.h:564
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
```
```
In net/mptcp/pm_netlink.c (0)
Location: include/net/netlink.h:564
Inline: True
```
```
In net/mctp/device.c (0)
Location: include/net/netlink.h:564
Inline: True
```
```
In net/mctp/route.c (0)
Location: include/net/netlink.h:564
Inline: True
```
```
In net/mctp/neigh.c (0)
Location: include/net/netlink.h:564
Inline: True
```
```
In net/handshake/netlink.c (0)
Location: include/net/netlink.h:564
Inline: True
```
```
In net/handshake/tlshd.c (0)
Location: include/net/netlink.h:564
Inline: True
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
In kernel/audit.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In kernel/taskstats.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In fs/quota/netlink.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In security/selinux/netlink.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In drivers/acpi/event.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In drivers/connector/connector.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/core/rtnetlink.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/core/sock_diag.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/core/drop_monitor.c (ffff800010c1c148)
Location: include/net/netlink.h:474
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/devlink.c (ffff800010c2e290)
Location: include/net/netlink.h:474
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
```
```
In net/sched/sch_api.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/sched/cls_api.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/sched/act_api.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/netlink/af_netlink.c (ffff800010c4ad08)
Location: include/net/netlink.h:474
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__nlmsg_put
```
```
In net/netlink/genetlink.c (ffff800010c511ac)
Location: include/net/netlink.h:474
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/ipv4/route.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv4/nexthop.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv6/seg6.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/wireless/wext-core.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/netlabel/netlabel_mgmt.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/netlabel/netlabel_calipso.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (ffff800010d7cf7c)
Location: include/net/netlink.h:474
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
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
In kernel/audit.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In kernel/taskstats.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In fs/quota/netlink.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In security/selinux/netlink.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In drivers/connector/connector.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/core/rtnetlink.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/core/sock_diag.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/core/drop_monitor.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/core/devlink.c (c0d45530)
Location: include/net/netlink.h:474
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
```
```
In net/sched/sch_api.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/sched/cls_api.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/sched/act_api.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/netlink/af_netlink.c (c0d5b884)
Location: include/net/netlink.h:474
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__nlmsg_put
```
```
In net/netlink/genetlink.c (c0d619ac)
Location: include/net/netlink.h:474
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/ipv4/route.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv4/nexthop.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv6/seg6.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/wireless/wext-core.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/netlabel/netlabel_mgmt.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/netlabel/netlabel_calipso.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (c0e77d80)
Location: include/net/netlink.h:474
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
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
In kernel/audit.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In kernel/taskstats.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In fs/quota/netlink.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In security/selinux/netlink.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In drivers/connector/connector.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/core/rtnetlink.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/core/sock_diag.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/core/drop_monitor.c (c000000000d0ce90)
Location: include/net/netlink.h:474
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/devlink.c (c000000000d28ea4)
Location: include/net/netlink.h:474
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
```
```
In net/sched/sch_api.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/sched/cls_api.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/sched/act_api.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/netlink/af_netlink.c (c000000000d48e28)
Location: include/net/netlink.h:474
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__nlmsg_put
```
```
In net/netlink/genetlink.c (c000000000d51a00)
Location: include/net/netlink.h:474
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/ipv4/route.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv4/nexthop.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv6/seg6.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/wireless/wext-core.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/netlabel/netlabel_mgmt.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/netlabel/netlabel_calipso.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (c000000000ebcad4)
Location: include/net/netlink.h:474
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
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
In kernel/audit.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In kernel/taskstats.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In fs/quota/netlink.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In security/selinux/netlink.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In drivers/connector/connector.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/core/rtnetlink.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/core/sock_diag.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/core/drop_monitor.c (ffffffe0007961fa)
Location: include/net/netlink.h:474
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/devlink.c (ffffffe0007a156a)
Location: include/net/netlink.h:474
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
```
```
In net/sched/sch_api.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/sched/cls_api.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/sched/act_api.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffe0007b801c)
Location: include/net/netlink.h:474
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__nlmsg_put
```
```
In net/netlink/genetlink.c (ffffffe0007bc4da)
Location: include/net/netlink.h:474
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/ipv4/route.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv4/nexthop.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv6/seg6.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/wireless/wext-core.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/netlabel/netlabel_mgmt.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/netlabel/netlabel_calipso.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (ffffffe0008aabe4)
Location: include/net/netlink.h:474
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
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
In kernel/audit.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In kernel/taskstats.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In fs/quota/netlink.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In security/selinux/netlink.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In drivers/acpi/event.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In drivers/connector/connector.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/core/rtnetlink.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/core/sock_diag.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff81915c6b)
Location: include/net/netlink.h:474
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/devlink.c (ffffffff81928169)
Location: include/net/netlink.h:474
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
```
```
In net/sched/sch_api.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/sched/cls_api.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/sched/act_api.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff8193d665)
Location: include/net/netlink.h:474
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__nlmsg_put
```
```
In net/netlink/genetlink.c (ffffffff81942deb)
Location: include/net/netlink.h:474
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/ipv4/route.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv4/nexthop.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv6/seg6.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/wireless/wext-core.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/netlabel/netlabel_mgmt.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/netlabel/netlabel_calipso.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81a48884)
Location: include/net/netlink.h:474
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
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
In kernel/audit.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In kernel/taskstats.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In fs/quota/netlink.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In security/selinux/netlink.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In drivers/acpi/event.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In drivers/connector/connector.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In drivers/scsi/scsi_transport_fc.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In drivers/net/vxlan.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/core/rtnetlink.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/core/sock_diag.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff818cfa1b)
Location: include/net/netlink.h:474
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/devlink.c (ffffffff818e1f19)
Location: include/net/netlink.h:474
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
```
```
In net/sched/sch_api.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/sched/cls_api.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/sched/act_api.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff818f7165)
Location: include/net/netlink.h:474
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__nlmsg_put
```
```
In net/netlink/genetlink.c (ffffffff818fc8db)
Location: include/net/netlink.h:474
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/ipv4/route.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv4/nexthop.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv6/seg6.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/wireless/wext-core.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/netlabel/netlabel_mgmt.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/netlabel/netlabel_calipso.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81a05474)
Location: include/net/netlink.h:474
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
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
In kernel/audit.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In kernel/taskstats.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In fs/quota/netlink.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In security/selinux/netlink.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In drivers/acpi/event.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In drivers/connector/connector.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/core/rtnetlink.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/core/sock_diag.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff81966c9b)
Location: include/net/netlink.h:474
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/devlink.c (ffffffff819792f9)
Location: include/net/netlink.h:474
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
```
```
In net/sched/sch_api.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/sched/cls_api.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/sched/act_api.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff8198e7f5)
Location: include/net/netlink.h:474
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__nlmsg_put
```
```
In net/netlink/genetlink.c (ffffffff81993f7b)
Location: include/net/netlink.h:474
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/netfilter/nfnetlink.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/netfilter/nfnetlink_queue.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/netfilter/nfnetlink_log.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/netfilter/nf_conntrack_netlink.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv4/nexthop.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv6/seg6.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/wireless/wext-core.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/netlabel/netlabel_mgmt.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/netlabel/netlabel_calipso.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81ab4734)
Location: include/net/netlink.h:474
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
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
In kernel/audit.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In kernel/taskstats.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In fs/quota/netlink.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In security/selinux/netlink.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In drivers/acpi/event.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In drivers/connector/connector.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/core/rtnetlink.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/core/sock_diag.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff81988f2b)
Location: include/net/netlink.h:474
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
```
In net/core/devlink.c (ffffffff8199b7e9)
Location: include/net/netlink.h:474
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_read_dumpit
```
```
In net/sched/sch_api.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/sched/cls_api.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/sched/act_api.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff819b10a5)
Location: include/net/netlink.h:474
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__nlmsg_put
```
```
In net/netlink/genetlink.c (ffffffff819b6a7b)
Location: include/net/netlink.h:474
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
```
In net/ipv4/route.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv4/nexthop.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv6/addrlabel.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv6/seg6.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/wireless/wext-core.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/netlabel/netlabel_mgmt.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/netlabel/netlabel_calipso.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/dcb/dcbnl.c (0)
Location: include/net/netlink.h:474
Inline: True
```
```
In net/ncsi/ncsi-netlink.c (ffffffff81ac0ad4)
Location: include/net/netlink.h:474
Inline: True
Inline callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
```
</details>
</li>
</ul>

## Differences
