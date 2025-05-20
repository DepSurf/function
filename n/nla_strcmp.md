# Function: <code>nla_strcmp</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int nla_strcmp(const struct nlattr *nla, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff814159a0)
Location: lib/nlattr.c:312
Inline: False
Direct callers:
  - net/core/neighbour.c:neightbl_set
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_delrule
  - net/sched/sch_api.c:qdisc_lookup_ops
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/cls_api.c:tcf_proto_lookup_ops
  - net/sched/cls_api.c:tc_ctl_tfilter
  - net/sched/act_api.c:tc_lookup_action
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
**Symbols:**

```
ffffffff814159a0-ffffffff814159e9: nla_strcmp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int nla_strcmp(const struct nlattr *nla, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff8145d6f0)
Location: lib/nlattr.c:312
Inline: False
Direct callers:
  - net/core/neighbour.c:neightbl_set
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_delrule
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:qdisc_lookup_ops
  - net/sched/cls_api.c:tc_ctl_tfilter
  - net/sched/cls_api.c:tcf_proto_lookup_ops
  - net/sched/act_api.c:tc_lookup_action
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
**Symbols:**

```
ffffffff8145d6f0-ffffffff8145d739: nla_strcmp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int nla_strcmp(const struct nlattr *nla, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff8147c1b0)
Location: lib/nlattr.c:312
Inline: False
Direct callers:
  - net/core/neighbour.c:neightbl_set
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_delrule
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:qdisc_lookup_ops
  - net/sched/cls_api.c:tc_ctl_tfilter
  - net/sched/cls_api.c:tcf_proto_lookup_ops
  - net/sched/act_api.c:tc_lookup_action
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
**Symbols:**

```
ffffffff8147c1b0-ffffffff8147c1f9: nla_strcmp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int nla_strcmp(const struct nlattr *nla, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff814854d0)
Location: lib/nlattr.c:320
Inline: False
Direct callers:
  - net/core/neighbour.c:neightbl_set
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_delrule
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:qdisc_lookup_ops
  - net/sched/cls_api.c:tc_ctl_tfilter
  - net/sched/act_api.c:tc_lookup_action
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
**Symbols:**

```
ffffffff814854d0-ffffffff8148551a: nla_strcmp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int nla_strcmp(const struct nlattr *nla, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff814c1660)
Location: lib/nlattr.c:398
Inline: False
Direct callers:
  - net/core/neighbour.c:neightbl_set
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_delrule
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:qdisc_lookup_ops
  - net/sched/cls_api.c:tc_ctl_tfilter
  - net/sched/act_api.c:tc_lookup_action
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
**Symbols:**

```
ffffffff814c1660-ffffffff814c16aa: nla_strcmp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int nla_strcmp(const struct nlattr *nla, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff814f2390)
Location: lib/nlattr.c:398
Inline: False
Direct callers:
  - net/core/neighbour.c:neightbl_set
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:qdisc_lookup_ops
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/act_api.c:tc_lookup_action
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
**Symbols:**

```
ffffffff814f2390-ffffffff814f23d8: nla_strcmp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int nla_strcmp(const struct nlattr *nla, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff815060d0)
Location: lib/nlattr.c:573
Inline: False
Direct callers:
  - net/core/neighbour.c:neightbl_set
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:qdisc_lookup_ops
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/act_api.c:tc_lookup_action
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
**Symbols:**

```
ffffffff815060d0-ffffffff81506118: nla_strcmp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int nla_strcmp(const struct nlattr *nla, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff81534a90)
Location: lib/nlattr.c:605
Inline: False
Direct callers:
  - net/core/neighbour.c:neightbl_set
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:qdisc_lookup_ops
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/act_api.c:tc_lookup_action
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
**Symbols:**

```
ffffffff81534a90-ffffffff81534ad9: nla_strcmp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int nla_strcmp(const struct nlattr *nla, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff815558c0)
Location: lib/nlattr.c:605
Inline: False
Direct callers:
  - net/core/neighbour.c:neightbl_set
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:qdisc_lookup_ops
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/act_api.c:tc_lookup_action
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
**Symbols:**

```
ffffffff815558c0-ffffffff81555909: nla_strcmp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int nla_strcmp(const struct nlattr *nla, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff815de640)
Location: lib/nlattr.c:757
Inline: False
Direct callers:
  - net/core/neighbour.c:neightbl_set
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:qdisc_lookup_ops
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/act_api.c:tc_lookup_action
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
**Symbols:**

```
ffffffff815de640-ffffffff815de68b: nla_strcmp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int nla_strcmp(const struct nlattr *nla, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff815fbce0)
Location: lib/nlattr.c:824
Inline: False
Direct callers:
  - net/core/neighbour.c:neightbl_set
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:qdisc_lookup_ops
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/act_api.c:tc_lookup_action
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
**Symbols:**

```
ffffffff815fbce0-ffffffff815fbd2b: nla_strcmp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int nla_strcmp(const struct nlattr *nla, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff815de920)
Location: lib/nlattr.c:824
Inline: False
Direct callers:
  - net/core/neighbour.c:neightbl_set
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:qdisc_lookup_ops
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/act_api.c:tc_lookup_action
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
**Symbols:**

```
ffffffff815de920-ffffffff815de974: nla_strcmp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int nla_strcmp(const struct nlattr *nla, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff8164a4a0)
Location: lib/nlattr.c:824
Inline: False
Direct callers:
  - net/core/neighbour.c:neightbl_set
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:qdisc_lookup_ops
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/act_api.c:tc_lookup_action
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
**Symbols:**

```
ffffffff8164a4a0-ffffffff8164a4f4: nla_strcmp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int nla_strcmp(const struct nlattr *nla, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff81760c50)
Location: lib/nlattr.c:824
Inline: False
Direct callers:
  - net/core/neighbour.c:neightbl_set
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:qdisc_lookup_ops
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/act_api.c:tc_lookup_action
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
**Symbols:**

```
ffffffff81760c50-ffffffff81760cb3: nla_strcmp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int nla_strcmp(const struct nlattr *nla, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff8188f630)
Location: lib/nlattr.c:839
Inline: False
Direct callers:
  - net/core/neighbour.c:neightbl_set
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:qdisc_lookup_ops
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/act_api.c:tc_lookup_action
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
**Symbols:**

```
ffffffff8188f630-ffffffff8188f693: nla_strcmp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int nla_strcmp(const struct nlattr *nla, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff818d1a70)
Location: lib/nlattr.c:839
Inline: False
Direct callers:
  - net/core/neighbour.c:neightbl_set
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:qdisc_lookup_ops
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/act_api.c:tc_lookup_action
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
**Symbols:**

```
ffffffff818d1a70-ffffffff818d1ad3: nla_strcmp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int nla_strcmp(const struct nlattr *nla, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff81923a70)
Location: lib/nlattr.c:871
Inline: False
Direct callers:
  - drivers/dpll/dpll_netlink.c:dpll_device_find_from_nlattr
  - drivers/dpll/dpll_netlink.c:dpll_pin_find
  - drivers/dpll/dpll_netlink.c:dpll_pin_find
  - drivers/dpll/dpll_netlink.c:dpll_pin_find
  - drivers/dpll/dpll_netlink.c:dpll_pin_find
  - net/core/neighbour.c:neightbl_set
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:qdisc_lookup_ops
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/act_api.c:tc_lookup_action
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
**Symbols:**

```
ffffffff81923a70-ffffffff81923ada: nla_strcmp (STB_GLOBAL)
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
int nla_strcmp(const struct nlattr *nla, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffff800010661d20)
Location: lib/nlattr.c:605
Inline: False
Direct callers:
  - net/core/neighbour.c:neightbl_set
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:qdisc_lookup_ops
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/act_api.c:tc_lookup_action
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
**Symbols:**

```
ffff800010661d20-ffff800010661d88: nla_strcmp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int nla_strcmp(const struct nlattr *nla, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (c080addc)
Location: lib/nlattr.c:605
Inline: False
Direct callers:
  - net/core/neighbour.c:neightbl_set
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:qdisc_lookup_ops
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/act_api.c:tc_lookup_action
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
**Symbols:**

```
c080addc-c080ae34: nla_strcmp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int nla_strcmp(const struct nlattr *nla, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (c000000000815f00)
Location: lib/nlattr.c:605
Inline: False
Direct callers:
  - net/core/neighbour.c:neightbl_set
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:qdisc_lookup_ops
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/act_api.c:tc_lookup_action
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
**Symbols:**

```
c000000000815f00-c000000000815f9c: nla_strcmp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int nla_strcmp(const struct nlattr *nla, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffe00048e646)
Location: lib/nlattr.c:605
Inline: False
Direct callers:
  - net/core/neighbour.c:neightbl_set
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:qdisc_lookup_ops
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/act_api.c:tc_lookup_action
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
**Symbols:**

```
ffffffe00048e646-ffffffe00048e6a0: nla_strcmp (STB_GLOBAL)
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
int nla_strcmp(const struct nlattr *nla, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff8154dea0)
Location: lib/nlattr.c:605
Inline: False
Direct callers:
  - net/core/neighbour.c:neightbl_set
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:qdisc_lookup_ops
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/act_api.c:tc_lookup_action
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
**Symbols:**

```
ffffffff8154dea0-ffffffff8154dee9: nla_strcmp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int nla_strcmp(const struct nlattr *nla, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff8153e180)
Location: lib/nlattr.c:605
Inline: False
Direct callers:
  - net/core/neighbour.c:neightbl_set
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:qdisc_lookup_ops
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/act_api.c:tc_lookup_action
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
**Symbols:**

```
ffffffff8153e180-ffffffff8153e1c9: nla_strcmp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int nla_strcmp(const struct nlattr *nla, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff81549be0)
Location: lib/nlattr.c:605
Inline: False
Direct callers:
  - net/core/neighbour.c:neightbl_set
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:qdisc_lookup_ops
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/act_api.c:tc_lookup_action
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
**Symbols:**

```
ffffffff81549be0-ffffffff81549c29: nla_strcmp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int nla_strcmp(const struct nlattr *nla, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff81563a30)
Location: lib/nlattr.c:605
Inline: False
Direct callers:
  - net/core/neighbour.c:neightbl_set
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:qdisc_lookup_ops
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/act_api.c:tc_lookup_action
  - net/ipv4/devinet.c:inet_rtm_deladdr
```
**Symbols:**

```
ffffffff81563a30-ffffffff81563a79: nla_strcmp (STB_GLOBAL)
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
