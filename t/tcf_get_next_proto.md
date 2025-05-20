# Function: <code>tcf_get_next_proto</code>

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
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct tcf_proto *tcf_get_next_proto(struct tcf_chain *chain, struct tcf_proto *tp, bool rtnl_held);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81960cef)
Location: net/sched/cls_api.c:1115
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_del_tfilter
Direct callers:
  - net/sched/sch_api.c:tc_bind_tclass
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_del_tfilter
```
**Symbols:**

```
ffffffff8195ecd0-ffffffff8195ed07: tcf_get_next_proto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct tcf_proto *tcf_get_next_proto(struct tcf_chain *chain, struct tcf_proto *tp, bool rtnl_held);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81997de6)
Location: net/sched/cls_api.c:1029
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_del_tfilter
Direct callers:
  - net/sched/sch_api.c:tc_bind_class_walker
  - net/sched/sch_api.c:tc_bind_class_walker
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_del_tfilter
```
**Symbols:**

```
ffffffff81996130-ffffffff81996167: tcf_get_next_proto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct tcf_proto *tcf_get_next_proto(struct tcf_chain *chain, struct tcf_proto *tp, bool rtnl_held);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a6e470)
Location: net/sched/cls_api.c:992
Inline: True
Direct callers:
  - net/sched/sch_api.c:tc_bind_class_walker
  - net/sched/sch_api.c:tc_bind_class_walker
```
**Symbols:**

```
ffffffff81a6e470-ffffffff81a6e4a7: tcf_get_next_proto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct tcf_proto *tcf_get_next_proto(struct tcf_chain *chain, struct tcf_proto *tp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a76c80)
Location: net/sched/cls_api.c:994
Inline: True
Direct callers:
  - net/sched/sch_api.c:tc_bind_class_walker
  - net/sched/sch_api.c:tc_bind_class_walker
```
**Symbols:**

```
ffffffff81a76c80-ffffffff81a76cb5: tcf_get_next_proto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct tcf_proto *tcf_get_next_proto(struct tcf_chain *chain, struct tcf_proto *tp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a5f6b0)
Location: net/sched/cls_api.c:994
Inline: True
Direct callers:
  - net/sched/sch_api.c:tc_bind_class_walker
  - net/sched/sch_api.c:tc_bind_class_walker
```
**Symbols:**

```
ffffffff81a5f6b0-ffffffff81a5f6e5: tcf_get_next_proto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct tcf_proto *tcf_get_next_proto(struct tcf_chain *chain, struct tcf_proto *tp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81b188c0)
Location: net/sched/cls_api.c:995
Inline: True
Direct callers:
  - net/sched/sch_api.c:tc_bind_class_walker
  - net/sched/sch_api.c:tc_bind_class_walker
```
**Symbols:**

```
ffffffff81b188c0-ffffffff81b188f5: tcf_get_next_proto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct tcf_proto *tcf_get_next_proto(struct tcf_chain *chain, struct tcf_proto *tp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81c9fb90)
Location: net/sched/cls_api.c:1012
Inline: True
Direct callers:
  - net/sched/sch_api.c:tc_bind_class_walker
```
**Symbols:**

```
ffffffff81c9fb90-ffffffff81c9fbcd: tcf_get_next_proto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct tcf_proto *tcf_get_next_proto(struct tcf_chain *chain, struct tcf_proto *tp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81e5be70)
Location: net/sched/cls_api.c:1014
Inline: True
Direct callers:
  - net/sched/sch_api.c:tc_bind_class_walker
```
**Symbols:**

```
ffffffff81e5be70-ffffffff81e5bead: tcf_get_next_proto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct tcf_proto *tcf_get_next_proto(struct tcf_chain *chain, struct tcf_proto *tp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81eb8670)
Location: net/sched/cls_api.c:1119
Inline: True
Direct callers:
  - net/sched/sch_api.c:tc_bind_class_walker
```
**Symbols:**

```
ffffffff81eb8670-ffffffff81eb86ad: tcf_get_next_proto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct tcf_proto *tcf_get_next_proto(struct tcf_chain *chain, struct tcf_proto *tp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81f7b740)
Location: net/sched/cls_api.c:1121
Inline: True
Direct callers:
  - net/sched/sch_api.c:tc_bind_class_walker
```
**Symbols:**

```
ffffffff81f7b740-ffffffff81f7b77d: tcf_get_next_proto (STB_GLOBAL)
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
struct tcf_proto *tcf_get_next_proto(struct tcf_chain *chain, struct tcf_proto *tp, bool rtnl_held);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffff800010c429a0)
Location: net/sched/cls_api.c:1029
Inline: True
Direct callers:
  - net/sched/sch_api.c:tc_bind_class_walker
  - net/sched/sch_api.c:tc_bind_class_walker
```
**Symbols:**

```
ffff800010c429a0-ffff800010c429fc: tcf_get_next_proto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct tcf_proto *tcf_get_next_proto(struct tcf_chain *chain, struct tcf_proto *tp, bool rtnl_held);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (c0d56718)
Location: net/sched/cls_api.c:1029
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_del_tfilter
Direct callers:
  - net/sched/sch_api.c:tc_bind_class_walker
  - net/sched/sch_api.c:tc_bind_class_walker
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_del_tfilter
```
**Symbols:**

```
c0d53de4-c0d53e28: tcf_get_next_proto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct tcf_proto *tcf_get_next_proto(struct tcf_chain *chain, struct tcf_proto *tp, bool rtnl_held);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (c000000000d3e2e0)
Location: net/sched/cls_api.c:1029
Inline: True
Direct callers:
  - net/sched/sch_api.c:tc_bind_class_walker
  - net/sched/sch_api.c:tc_bind_class_walker
```
**Symbols:**

```
c000000000d3e2e0-c000000000d3e350: tcf_get_next_proto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct tcf_proto *tcf_get_next_proto(struct tcf_chain *chain, struct tcf_proto *tp, bool rtnl_held);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffe0007b19fe)
Location: net/sched/cls_api.c:1029
Inline: True
Direct callers:
  - net/sched/sch_api.c:tc_bind_class_walker
  - net/sched/sch_api.c:tc_bind_class_walker
```
**Symbols:**

```
ffffffe0007b19fe-ffffffe0007b1a6e: tcf_get_next_proto (STB_GLOBAL)
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
struct tcf_proto *tcf_get_next_proto(struct tcf_chain *chain, struct tcf_proto *tp, bool rtnl_held);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81937c56)
Location: net/sched/cls_api.c:1029
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_del_tfilter
Direct callers:
  - net/sched/sch_api.c:tc_bind_class_walker
  - net/sched/sch_api.c:tc_bind_class_walker
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_del_tfilter
```
**Symbols:**

```
ffffffff81935fa0-ffffffff81935fd7: tcf_get_next_proto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct tcf_proto *tcf_get_next_proto(struct tcf_chain *chain, struct tcf_proto *tp, bool rtnl_held);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff818f1756)
Location: net/sched/cls_api.c:1029
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_del_tfilter
Direct callers:
  - net/sched/sch_api.c:tc_bind_class_walker
  - net/sched/sch_api.c:tc_bind_class_walker
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_del_tfilter
```
**Symbols:**

```
ffffffff818efaa0-ffffffff818efad7: tcf_get_next_proto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct tcf_proto *tcf_get_next_proto(struct tcf_chain *chain, struct tcf_proto *tp, bool rtnl_held);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81988de6)
Location: net/sched/cls_api.c:1029
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_del_tfilter
Direct callers:
  - net/sched/sch_api.c:tc_bind_class_walker
  - net/sched/sch_api.c:tc_bind_class_walker
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_del_tfilter
```
**Symbols:**

```
ffffffff81987130-ffffffff81987167: tcf_get_next_proto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct tcf_proto *tcf_get_next_proto(struct tcf_chain *chain, struct tcf_proto *tp, bool rtnl_held);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff819ac0e6)
Location: net/sched/cls_api.c:1029
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_del_tfilter
Direct callers:
  - net/sched/sch_api.c:tc_bind_class_walker
  - net/sched/sch_api.c:tc_bind_class_walker
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_del_tfilter
```
**Symbols:**

```
ffffffff819a95f0-ffffffff819a9627: tcf_get_next_proto (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool rtnl_held</code>
</li>
</ul>
</details>
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
