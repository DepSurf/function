# Function: <code>tcf_proto_lookup_ops</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
const struct tcf_proto_ops *tcf_proto_lookup_ops(struct nlattr *kind);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81745dd0)
Location: net/sched/cls_api.c:41
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_ctl_tfilter
  - net/sched/cls_api.c:tc_ctl_tfilter
```
**Symbols:**

```
ffffffff81745dd0-ffffffff81745e46: tcf_proto_lookup_ops (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
const struct tcf_proto_ops *tcf_proto_lookup_ops(struct nlattr *kind);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff817b2d10)
Location: net/sched/cls_api.c:41
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_ctl_tfilter
  - net/sched/cls_api.c:tc_ctl_tfilter
```
**Symbols:**

```
ffffffff817b2d10-ffffffff817b2d86: tcf_proto_lookup_ops (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
const struct tcf_proto_ops *tcf_proto_lookup_ops(struct nlattr *kind);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff817e2590)
Location: net/sched/cls_api.c:41
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_ctl_tfilter
  - net/sched/cls_api.c:tc_ctl_tfilter
```
**Symbols:**

```
ffffffff817e2590-ffffffff817e2606: tcf_proto_lookup_ops (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
const struct tcf_proto_ops *tcf_proto_lookup_ops(const char *kind);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81801e00)
Location: net/sched/cls_api.c:42
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_ctl_tfilter
  - net/sched/cls_api.c:tc_ctl_tfilter
```
**Symbols:**

```
ffffffff81801e00-ffffffff81801e76: tcf_proto_lookup_ops (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
const struct tcf_proto_ops *tcf_proto_lookup_ops(const char *kind);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff8187ff90)
Location: net/sched/cls_api.c:41
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_ctl_tfilter
  - net/sched/cls_api.c:tc_ctl_tfilter
```
**Symbols:**

```
ffffffff8187ff90-ffffffff81880006: tcf_proto_lookup_ops (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
const struct tcf_proto_ops *tcf_proto_lookup_ops(const char *kind);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff818d2af0)
Location: net/sched/cls_api.c:42
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
**Symbols:**

```
ffffffff818d2af0-ffffffff818d2b64: tcf_proto_lookup_ops (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (ffffffff819000e7)
Location: net/sched/cls_api.c:64
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_new_tfilter
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_new_tfilter
```
**Symbols:**

```
ffffffff818fe440-ffffffff818fe4ae: tcf_proto_lookup_ops.part.54 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
const struct tcf_proto_ops *tcf_proto_lookup_ops(const char *kind, bool rtnl_held, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff8195dd10)
Location: net/sched/cls_api.c:69
Inline: True
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_proto_is_unlocked
```
**Symbols:**

```
ffffffff8195dd10-ffffffff8195ddb1: tcf_proto_lookup_ops (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
const struct tcf_proto_ops *tcf_proto_lookup_ops(const char *kind, bool rtnl_held, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff819943e0)
Location: net/sched/cls_api.c:128
Inline: True
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_new_tfilter
```
**Symbols:**

```
ffffffff819943e0-ffffffff81994481: tcf_proto_lookup_ops (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
const struct tcf_proto_ops *tcf_proto_lookup_ops(const char *kind, bool rtnl_held, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a6c1f0)
Location: net/sched/cls_api.c:129
Inline: True
Direct callers:
  - net/sched/cls_api.c:tc_chain_tmplt_add
  - net/sched/cls_api.c:tcf_proto_create
```
**Symbols:**

```
ffffffff81a6c1f0-ffffffff81a6c291: tcf_proto_lookup_ops (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
const struct tcf_proto_ops *tcf_proto_lookup_ops(const char *kind, bool rtnl_held, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a74aa0)
Location: net/sched/cls_api.c:129
Inline: True
Direct callers:
  - net/sched/cls_api.c:tc_chain_tmplt_add
  - net/sched/cls_api.c:tcf_proto_create
```
**Symbols:**

```
ffffffff81a74aa0-ffffffff81a74b41: tcf_proto_lookup_ops (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
const struct tcf_proto_ops *tcf_proto_lookup_ops(const char *kind, bool rtnl_held, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a5d640)
Location: net/sched/cls_api.c:129
Inline: True
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
**Symbols:**

```
ffffffff81a5d640-ffffffff81a5d6ed: tcf_proto_lookup_ops (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
const struct tcf_proto_ops *tcf_proto_lookup_ops(const char *kind, bool rtnl_held, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81b16650)
Location: net/sched/cls_api.c:129
Inline: True
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
**Symbols:**

```
ffffffff81b16650-ffffffff81b166fd: tcf_proto_lookup_ops (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
const struct tcf_proto_ops *tcf_proto_lookup_ops(const char *kind, bool rtnl_held, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81c9d9b0)
Location: net/sched/cls_api.c:146
Inline: True
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_proto_is_unlocked
```
**Symbols:**

```
ffffffff81c9d9b0-ffffffff81c9da80: tcf_proto_lookup_ops (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
const struct tcf_proto_ops *tcf_proto_lookup_ops(const char *kind, bool rtnl_held, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81e59ff0)
Location: net/sched/cls_api.c:147
Inline: True
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_proto_is_unlocked
```
**Symbols:**

```
ffffffff81e59ff0-ffffffff81e5a0c0: tcf_proto_lookup_ops (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
const struct tcf_proto_ops *tcf_proto_lookup_ops(const char *kind, bool rtnl_held, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81eb5a30)
Location: net/sched/cls_api.c:249
Inline: True
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_proto_is_unlocked
```
**Symbols:**

```
ffffffff81eb5a30-ffffffff81eb5b00: tcf_proto_lookup_ops (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
const struct tcf_proto_ops *tcf_proto_lookup_ops(const char *kind, bool rtnl_held, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81f78740)
Location: net/sched/cls_api.c:249
Inline: True
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_proto_is_unlocked
```
**Symbols:**

```
ffffffff81f78740-ffffffff81f78810: tcf_proto_lookup_ops (STB_LOCAL)
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
const struct tcf_proto_ops *tcf_proto_lookup_ops(const char *kind, bool rtnl_held, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffff800010c41760)
Location: net/sched/cls_api.c:128
Inline: True
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_new_tfilter
```
**Symbols:**

```
ffff800010c41760-ffff800010c41828: tcf_proto_lookup_ops (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
const struct tcf_proto_ops *tcf_proto_lookup_ops(const char *kind, bool rtnl_held, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (c0d52e1c)
Location: net/sched/cls_api.c:128
Inline: True
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_new_tfilter
```
**Symbols:**

```
c0d52e1c-c0d52ec0: tcf_proto_lookup_ops (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
const struct tcf_proto_ops *tcf_proto_lookup_ops(const char *kind, bool rtnl_held, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (c000000000d3bbe0)
Location: net/sched/cls_api.c:128
Inline: True
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_new_tfilter
```
**Symbols:**

```
c000000000d3bbe0-c000000000d3bd0c: tcf_proto_lookup_ops (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
const struct tcf_proto_ops *tcf_proto_lookup_ops(const char *kind, bool rtnl_held, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffe0007b0376)
Location: net/sched/cls_api.c:128
Inline: True
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_new_tfilter
```
**Symbols:**

```
ffffffe0007b0376-ffffffe0007b0432: tcf_proto_lookup_ops (STB_LOCAL)
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
const struct tcf_proto_ops *tcf_proto_lookup_ops(const char *kind, bool rtnl_held, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81934250)
Location: net/sched/cls_api.c:128
Inline: True
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_new_tfilter
```
**Symbols:**

```
ffffffff81934250-ffffffff819342f1: tcf_proto_lookup_ops (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
const struct tcf_proto_ops *tcf_proto_lookup_ops(const char *kind, bool rtnl_held, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff818edd50)
Location: net/sched/cls_api.c:128
Inline: True
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_new_tfilter
```
**Symbols:**

```
ffffffff818edd50-ffffffff818eddf1: tcf_proto_lookup_ops (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
const struct tcf_proto_ops *tcf_proto_lookup_ops(const char *kind, bool rtnl_held, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff819853e0)
Location: net/sched/cls_api.c:128
Inline: True
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_new_tfilter
```
**Symbols:**

```
ffffffff819853e0-ffffffff81985481: tcf_proto_lookup_ops (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
const struct tcf_proto_ops *tcf_proto_lookup_ops(const char *kind, bool rtnl_held, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff819a8180)
Location: net/sched/cls_api.c:128
Inline: True
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_new_tfilter
```
**Symbols:**

```
ffffffff819a8180-ffffffff819a8221: tcf_proto_lookup_ops (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct nlattr *kind</code> ➡️ <code>const char *kind</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
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
