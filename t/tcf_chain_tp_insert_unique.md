# Function: <code>tcf_chain_tp_insert_unique</code>

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
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff8196225b)
Location: net/sched/cls_api.c:1735
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_new_tfilter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81999433)
Location: net/sched/cls_api.c:1673
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_new_tfilter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct tcf_proto *tcf_chain_tp_insert_unique(struct tcf_chain *chain, struct tcf_proto *tp_new, u32 protocol, u32 prio, bool rtnl_held);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a6e260)
Location: net/sched/cls_api.c:1686
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_new_tfilter
```
**Symbols:**

```
ffffffff81a6e260-ffffffff81a6e419: tcf_chain_tp_insert_unique (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct tcf_proto *tcf_chain_tp_insert_unique(struct tcf_chain *chain, struct tcf_proto *tp_new, u32 protocol, u32 prio, bool rtnl_held);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a771a0)
Location: net/sched/cls_api.c:1688
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_new_tfilter
```
**Symbols:**

```
ffffffff81a771a0-ffffffff81a77366: tcf_chain_tp_insert_unique (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct tcf_proto *tcf_chain_tp_insert_unique(struct tcf_chain *chain, struct tcf_proto *tp_new, u32 protocol, u32 prio, bool rtnl_held);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a5ec00)
Location: net/sched/cls_api.c:1689
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_new_tfilter
```
**Symbols:**

```
ffffffff81a5ec00-ffffffff81a5edc0: tcf_chain_tp_insert_unique (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct tcf_proto *tcf_chain_tp_insert_unique(struct tcf_chain *chain, struct tcf_proto *tp_new, u32 protocol, u32 prio, bool rtnl_held);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (0)
Location: net/sched/cls_api.c:1687
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_new_tfilter
```
**Symbols:**

```
ffffffff81b17dd0-ffffffff81b17fa1: tcf_chain_tp_insert_unique (STB_LOCAL)
ffffffff81d3916f-ffffffff81d39184: tcf_chain_tp_insert_unique.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct tcf_proto *tcf_chain_tp_insert_unique(struct tcf_chain *chain, struct tcf_proto *tp_new, u32 protocol, u32 prio, bool rtnl_held);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (0)
Location: net/sched/cls_api.c:1706
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_new_tfilter
```
**Symbols:**

```
ffffffff81ca0050-ffffffff81ca0236: tcf_chain_tp_insert_unique (STB_LOCAL)
ffffffff81f059ae-ffffffff81f059c3: tcf_chain_tp_insert_unique.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct tcf_proto *tcf_chain_tp_insert_unique(struct tcf_chain *chain, struct tcf_proto *tp_new, u32 protocol, u32 prio, bool rtnl_held);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (0)
Location: net/sched/cls_api.c:1708
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_new_tfilter
```
**Symbols:**

```
ffffffff81e5bff0-ffffffff81e5c1d6: tcf_chain_tp_insert_unique (STB_LOCAL)
ffffffff820ad7b8-ffffffff820ad7cd: tcf_chain_tp_insert_unique.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct tcf_proto *tcf_chain_tp_insert_unique(struct tcf_chain *chain, struct tcf_proto *tp_new, u32 protocol, u32 prio, bool rtnl_held);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (0)
Location: net/sched/cls_api.c:1856
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_new_tfilter
```
**Symbols:**

```
ffffffff81eb8b80-ffffffff81eb8d66: tcf_chain_tp_insert_unique (STB_LOCAL)
ffffffff8212e9b0-ffffffff8212e9c5: tcf_chain_tp_insert_unique.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct tcf_proto *tcf_chain_tp_insert_unique(struct tcf_chain *chain, struct tcf_proto *tp_new, u32 protocol, u32 prio, bool rtnl_held);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (0)
Location: net/sched/cls_api.c:1906
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_new_tfilter
```
**Symbols:**

```
ffffffff81f7bc50-ffffffff81f7be36: tcf_chain_tp_insert_unique (STB_LOCAL)
ffffffff82210754-ffffffff82210769: tcf_chain_tp_insert_unique.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffff800010c4612c)
Location: net/sched/cls_api.c:1673
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_new_tfilter
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (c0d55fc0)
Location: net/sched/cls_api.c:1673
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_new_tfilter
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (c000000000d40b44)
Location: net/sched/cls_api.c:1673
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_new_tfilter
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffe0007b300e)
Location: net/sched/cls_api.c:1673
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_new_tfilter
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff819392a3)
Location: net/sched/cls_api.c:1673
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_new_tfilter
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff818f2da3)
Location: net/sched/cls_api.c:1673
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_new_tfilter
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff8198a433)
Location: net/sched/cls_api.c:1673
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_new_tfilter
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff819ab7a2)
Location: net/sched/cls_api.c:1673
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_new_tfilter
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
