# Function: <code>tc_action_load_ops</code>

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
struct tc_action_ops *tc_action_load_ops(char *name, struct nlattr *nla, bool rtnl_held, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81a7c720)
Location: net/sched/act_api.c:931
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_exts_validate
  - net/sched/act_api.c:tcf_action_init
```
**Symbols:**

```
ffffffff81a7c720-ffffffff81a7c941: tc_action_load_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct tc_action_ops *tc_action_load_ops(char *name, struct nlattr *nla, bool rtnl_held, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81a653b0)
Location: net/sched/act_api.c:944
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_exts_validate
  - net/sched/act_api.c:tcf_action_init
```
**Symbols:**

```
ffffffff81a653b0-ffffffff81a655fd: tc_action_load_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct tc_action_ops *tc_action_load_ops(struct nlattr *nla, bool police, bool rtnl_held, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81b1e670)
Location: net/sched/act_api.c:953
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_exts_validate
  - net/sched/act_api.c:tcf_action_init
```
**Symbols:**

```
ffffffff81b1e670-ffffffff81b1e803: tc_action_load_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct tc_action_ops *tc_action_load_ops(struct nlattr *nla, bool police, bool rtnl_held, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81ca60a0)
Location: net/sched/act_api.c:1276
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_exts_validate_ex
  - net/sched/act_api.c:tcf_action_init
```
**Symbols:**

```
ffffffff81ca60a0-ffffffff81ca6270: tc_action_load_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct tc_action_ops *tc_action_load_ops(struct nlattr *nla, bool police, bool rtnl_held, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81e62570)
Location: net/sched/act_api.c:1302
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_exts_validate_ex
  - net/sched/act_api.c:tcf_action_init
```
**Symbols:**

```
ffffffff81e62570-ffffffff81e62740: tc_action_load_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct tc_action_ops *tc_action_load_ops(struct nlattr *nla, bool police, bool rtnl_held, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81ebe600)
Location: net/sched/act_api.c:1297
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_exts_validate_ex
  - net/sched/act_api.c:tcf_action_init
```
**Symbols:**

```
ffffffff81ebe600-ffffffff81ebe7ca: tc_action_load_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct tc_action_ops *tc_action_load_ops(struct nlattr *nla, u32 flags, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81f81760)
Location: net/sched/act_api.c:1327
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_exts_validate_ex
  - net/sched/act_api.c:tcf_action_init
```
**Symbols:**

```
ffffffff81f81760-ffffffff81f81936: tc_action_load_ops (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool police</code>
</li>
<li>
<b>Param removed. </b>
<code>char *name</code>
</li>
<li>
<b>Param reordered. </b>
<code>name, nla, rtnl_held, extack</code> ➡️ <code>nla, police, rtnl_held, extack</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u32 flags</code>
</li>
<li>
<b>Param removed. </b>
<code>bool police</code>
</li>
<li>
<b>Param removed. </b>
<code>bool rtnl_held</code>
</li>
<li>
<b>Param reordered. </b>
<code>nla, police, rtnl_held, extack</code> ➡️ <code>nla, flags, extack</code>
</li>
</ul>
</details>
</li>
</ul>
