# Function: <code>nla_strscpy</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t nla_strscpy(char *dst, const struct nlattr *nla, size_t dstsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff815fbbd0)
Location: lib/nlattr.c:725
Inline: False
Direct callers:
  - kernel/taskstats.c:parse
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/sched/sch_api.c:qdisc_create
  - net/sched/cls_api.c:tc_chain_tmplt_add
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/act_api.c:tc_action_load_ops
  - net/ipv4/devinet.c:rtm_to_ifaddr
  - net/ipv4/fib_semantics.c:fib_metrics_match
  - net/ipv4/metrics.c:ip_metrics_convert
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common
```
**Symbols:**

```
ffffffff815fbbd0-ffffffff815fbc67: nla_strscpy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t nla_strscpy(char *dst, const struct nlattr *nla, size_t dstsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff815de820)
Location: lib/nlattr.c:725
Inline: False
Direct callers:
  - kernel/taskstats.c:parse
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/sched/sch_api.c:qdisc_create
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/act_api.c:tc_action_load_ops
  - net/ipv4/devinet.c:rtm_to_ifaddr
  - net/ipv4/fib_semantics.c:fib_metrics_match
  - net/ipv4/metrics.c:ip_metrics_convert
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common
```
**Symbols:**

```
ffffffff815de820-ffffffff815de8b7: nla_strscpy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t nla_strscpy(char *dst, const struct nlattr *nla, size_t dstsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff8164a3a0)
Location: lib/nlattr.c:725
Inline: False
Direct callers:
  - kernel/taskstats.c:parse
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/sched/sch_api.c:qdisc_create
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/act_api.c:tc_action_load_ops
  - net/ipv4/devinet.c:rtm_to_ifaddr
  - net/ipv4/fib_semantics.c:fib_metrics_match
  - net/ipv4/metrics.c:ip_metrics_convert
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common
```
**Symbols:**

```
ffffffff8164a3a0-ffffffff8164a437: nla_strscpy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t nla_strscpy(char *dst, const struct nlattr *nla, size_t dstsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff81760b10)
Location: lib/nlattr.c:725
Inline: False
Direct callers:
  - kernel/taskstats.c:parse
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_newlink_create
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/act_api.c:tc_action_load_ops
  - net/ipv4/fib_semantics.c:fib_metrics_match
  - net/ipv4/metrics.c:ip_metrics_convert
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common
```
**Symbols:**

```
ffffffff81760b10-ffffffff81760bad: nla_strscpy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t nla_strscpy(char *dst, const struct nlattr *nla, size_t dstsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff8188f9a0)
Location: lib/nlattr.c:740
Inline: False
Direct callers:
  - kernel/taskstats.c:parse
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_newlink_create
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/sched/sch_api.c:qdisc_create
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/act_api.c:tc_action_load_ops
  - net/ipv4/fib_semantics.c:fib_metrics_match
  - net/ipv4/metrics.c:ip_metrics_convert
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common
```
**Symbols:**

```
ffffffff8188f9a0-ffffffff8188fa3d: nla_strscpy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t nla_strscpy(char *dst, const struct nlattr *nla, size_t dstsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff818d1de0)
Location: lib/nlattr.c:740
Inline: False
Direct callers:
  - kernel/taskstats.c:parse
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_newlink_create
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/sched/sch_api.c:qdisc_create
  - net/sched/cls_api.c:tcf_proto_check_kind
  - net/sched/act_api.c:tc_action_load_ops
  - net/ipv4/fib_semantics.c:fib_metrics_match
  - net/ipv4/metrics.c:ip_metrics_convert
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common
```
**Symbols:**

```
ffffffff818d1de0-ffffffff818d1e7d: nla_strscpy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t nla_strscpy(char *dst, const struct nlattr *nla, size_t dstsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff81923de0)
Location: lib/nlattr.c:772
Inline: False
Direct callers:
  - kernel/taskstats.c:parse
  - drivers/net/netkit.c:netkit_new_link
  - drivers/net/netkit.c:netkit_new_link
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_newlink_create
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/sched/sch_api.c:qdisc_create
  - net/sched/cls_api.c:tcf_proto_check_kind
  - net/sched/act_api.c:tc_action_load_ops
  - net/ipv4/fib_semantics.c:fib_metrics_match
  - net/ipv4/metrics.c:ip_metrics_convert
  - net/devlink/netlink.c:devlink_nl_notify_filter_set_doit
  - net/devlink/netlink.c:devlink_nl_notify_filter_set_doit
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common
```
**Symbols:**

```
ffffffff81923de0-ffffffff81923e7d: nla_strscpy (STB_GLOBAL)
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
<b>Regular</b>
<ul>
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
