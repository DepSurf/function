# Function: <code>tc_setup_flow_action</code>

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
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tc_setup_flow_action(struct flow_action *flow_action, const struct tcf_exts *exts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (ffffffff8195de10)
Location: net/sched/cls_api.c:3178
Inline: True
```
**Symbols:**

```
ffffffff8195de10-ffffffff8195e2e3: tc_setup_flow_action.part.0 (STB_LOCAL)
ffffffff8195e2f0-ffffffff8195e308: tc_setup_flow_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int tc_setup_flow_action(struct flow_action *flow_action, const struct tcf_exts *exts, bool rtnl_held);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff819944e0)
Location: net/sched/cls_api.c:3435
Inline: False
```
**Symbols:**

```
ffffffff819944e0-ffffffff81994be8: tc_setup_flow_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tc_setup_flow_action(struct flow_action *flow_action, const struct tcf_exts *exts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a71900)
Location: net/sched/cls_api.c:3554
Inline: True
```
**Symbols:**

```
ffffffff81a71900-ffffffff81a7219c: tc_setup_flow_action.part.0 (STB_LOCAL)
ffffffff81a721a0-ffffffff81a721b8: tc_setup_flow_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tc_setup_flow_action(struct flow_action *flow_action, const struct tcf_exts *exts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a7a380)
Location: net/sched/cls_api.c:3553
Inline: True
```
**Symbols:**

```
ffffffff81a7a380-ffffffff81a7ade3: tc_setup_flow_action.part.0 (STB_LOCAL)
ffffffff81a7adf0-ffffffff81a7ae08: tc_setup_flow_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tc_setup_flow_action(struct flow_action *flow_action, const struct tcf_exts *exts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a60110)
Location: net/sched/cls_api.c:3554
Inline: True
```
**Symbols:**

```
ffffffff81a60110-ffffffff81a60ba9: tc_setup_flow_action.part.0 (STB_LOCAL)
ffffffff81a60bb0-ffffffff81a60bc8: tc_setup_flow_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tc_setup_flow_action(struct flow_action *flow_action, const struct tcf_exts *exts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (ffffffff81b19e20)
Location: net/sched/cls_api.c:3555
Inline: True
```
**Symbols:**

```
ffffffff81b19390-ffffffff81b19e1a: tc_setup_flow_action.part.0 (STB_LOCAL)
ffffffff81d3920d-ffffffff81d3923b: tc_setup_flow_action.part.0.cold (STB_LOCAL)
ffffffff81b19e20-ffffffff81b19e38: tc_setup_flow_action (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int tc_setup_flow_action(struct flow_action *flow_action, const struct tcf_exts *exts, bool rtnl_held);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffff800010c40b48)
Location: net/sched/cls_api.c:3435
Inline: False
```
**Symbols:**

```
ffff800010c40b48-ffff800010c412d0: tc_setup_flow_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tc_setup_flow_action(struct flow_action *flow_action, const struct tcf_exts *exts, bool rtnl_held);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (c0d52f0c)
Location: net/sched/cls_api.c:3435
Inline: False
```
**Symbols:**

```
c0d52f0c-c0d53590: tc_setup_flow_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tc_setup_flow_action(struct flow_action *flow_action, const struct tcf_exts *exts, bool rtnl_held);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (c000000000d3bda0)
Location: net/sched/cls_api.c:3435
Inline: False
```
**Symbols:**

```
c000000000d3bda0-c000000000d3c570: tc_setup_flow_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tc_setup_flow_action(struct flow_action *flow_action, const struct tcf_exts *exts, bool rtnl_held);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffe0007b0486)
Location: net/sched/cls_api.c:3435
Inline: False
```
**Symbols:**

```
ffffffe0007b0486-ffffffe0007b0988: tc_setup_flow_action (STB_GLOBAL)
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
int tc_setup_flow_action(struct flow_action *flow_action, const struct tcf_exts *exts, bool rtnl_held);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81934350)
Location: net/sched/cls_api.c:3435
Inline: False
```
**Symbols:**

```
ffffffff81934350-ffffffff81934a58: tc_setup_flow_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int tc_setup_flow_action(struct flow_action *flow_action, const struct tcf_exts *exts, bool rtnl_held);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff818ede50)
Location: net/sched/cls_api.c:3435
Inline: False
```
**Symbols:**

```
ffffffff818ede50-ffffffff818ee558: tc_setup_flow_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int tc_setup_flow_action(struct flow_action *flow_action, const struct tcf_exts *exts, bool rtnl_held);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff819854e0)
Location: net/sched/cls_api.c:3435
Inline: False
```
**Symbols:**

```
ffffffff819854e0-ffffffff81985be8: tc_setup_flow_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int tc_setup_flow_action(struct flow_action *flow_action, const struct tcf_exts *exts, bool rtnl_held);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff819a8280)
Location: net/sched/cls_api.c:3435
Inline: False
```
**Symbols:**

```
ffffffff819a8280-ffffffff819a8bee: tc_setup_flow_action (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.3</code> and <code>5.4</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool rtnl_held</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool rtnl_held</code>
</li>
</ul>
</details>
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
