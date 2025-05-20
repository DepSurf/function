# Function: <code>tcf_block_offload_unbind</code>

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
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff8187f7f6)
Location: net/sched/cls_api.c:277
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_put_ext
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff818d2d5f)
Location: net/sched/cls_api.c:317
Inline: True
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
In net/sched/cls_api.c (ffffffff818ff1d0)
Location: net/sched/cls_api.c:663
Inline: True
Direct callers:
  - net/sched/cls_api.c:__tcf_block_put
  - net/sched/cls_api.c:__tcf_block_put
  - net/sched/cls_api.c:__tcf_block_put
```
**Symbols:**

```
ffffffff818ff1d0-ffffffff818ff283: tcf_block_offload_unbind.isra.47 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (ffffffff81962cef)
Location: net/sched/cls_api.c:863
Inline: True
Direct callers:
  - net/sched/cls_api.c:__tcf_block_put
```
**Symbols:**

```
ffffffff8195fa30-ffffffff8195fa9f: tcf_block_offload_unbind.isra.0 (STB_LOCAL)
ffffffff81962cef-ffffffff81962d02: tcf_block_offload_unbind.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (ffffffff819967f0)
Location: net/sched/cls_api.c:772
Inline: True
Direct callers:
  - net/sched/cls_api.c:__tcf_block_put
```
**Symbols:**

```
ffffffff819967f0-ffffffff81996881: tcf_block_offload_unbind.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a6eff0)
Location: net/sched/cls_api.c:739
Inline: True
Direct callers:
  - net/sched/cls_api.c:__tcf_block_put
  - net/sched/cls_api.c:__tcf_block_put
```
**Symbols:**

```
ffffffff81a6eff0-ffffffff81a6f059: tcf_block_offload_unbind.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void tcf_block_offload_unbind(struct tcf_block *block, struct Qdisc *q, struct tcf_block_ext_info *ei);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a779c0)
Location: net/sched/cls_api.c:741
Inline: False
Direct callers:
  - net/sched/cls_api.c:__tcf_block_put
  - net/sched/cls_api.c:__tcf_block_put
```
**Symbols:**

```
ffffffff81a779c0-ffffffff81a77a38: tcf_block_offload_unbind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void tcf_block_offload_unbind(struct tcf_block *block, struct Qdisc *q, struct tcf_block_ext_info *ei);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a5fff0)
Location: net/sched/cls_api.c:741
Inline: False
Direct callers:
  - net/sched/cls_api.c:__tcf_block_put
  - net/sched/cls_api.c:__tcf_block_put
```
**Symbols:**

```
ffffffff81a5fff0-ffffffff81a60068: tcf_block_offload_unbind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void tcf_block_offload_unbind(struct tcf_block *block, struct Qdisc *q, struct tcf_block_ext_info *ei);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81b19270)
Location: net/sched/cls_api.c:742
Inline: False
Direct callers:
  - net/sched/cls_api.c:__tcf_block_put
  - net/sched/cls_api.c:__tcf_block_put
```
**Symbols:**

```
ffffffff81b19270-ffffffff81b192e8: tcf_block_offload_unbind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void tcf_block_offload_unbind(struct tcf_block *block, struct Qdisc *q, struct tcf_block_ext_info *ei);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81ca0980)
Location: net/sched/cls_api.c:759
Inline: False
Direct callers:
  - net/sched/cls_api.c:__tcf_block_put
  - net/sched/cls_api.c:__tcf_block_put
```
**Symbols:**

```
ffffffff81ca0980-ffffffff81ca0a0c: tcf_block_offload_unbind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void tcf_block_offload_unbind(struct tcf_block *block, struct Qdisc *q, struct tcf_block_ext_info *ei);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81e5c9a0)
Location: net/sched/cls_api.c:761
Inline: False
Direct callers:
  - net/sched/cls_api.c:__tcf_block_put
  - net/sched/cls_api.c:__tcf_block_put
```
**Symbols:**

```
ffffffff81e5c9a0-ffffffff81e5ca2c: tcf_block_offload_unbind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void tcf_block_offload_unbind(struct tcf_block *block, struct Qdisc *q, struct tcf_block_ext_info *ei);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81eb9550)
Location: net/sched/cls_api.c:866
Inline: False
Direct callers:
  - net/sched/cls_api.c:__tcf_block_put
  - net/sched/cls_api.c:__tcf_block_put
```
**Symbols:**

```
ffffffff81eb9550-ffffffff81eb95dc: tcf_block_offload_unbind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void tcf_block_offload_unbind(struct tcf_block *block, struct Qdisc *q, struct tcf_block_ext_info *ei);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81f7c6a0)
Location: net/sched/cls_api.c:866
Inline: False
Direct callers:
  - net/sched/cls_api.c:__tcf_block_put
  - net/sched/cls_api.c:__tcf_block_put
```
**Symbols:**

```
ffffffff81f7c6a0-ffffffff81f7c72c: tcf_block_offload_unbind (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (ffff800010c43138)
Location: net/sched/cls_api.c:772
Inline: True
Direct callers:
  - net/sched/cls_api.c:__tcf_block_put
```
**Symbols:**

```
ffff800010c43138-ffff800010c431e0: tcf_block_offload_unbind.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void tcf_block_offload_unbind(struct tcf_block *block, struct Qdisc *q, struct tcf_block_ext_info *ei);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (c0d546f8)
Location: net/sched/cls_api.c:772
Inline: False
Direct callers:
  - net/sched/cls_api.c:__tcf_block_put
```
**Symbols:**

```
c0d546f8-c0d547b4: tcf_block_offload_unbind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void tcf_block_offload_unbind(struct tcf_block *block, struct Qdisc *q, struct tcf_block_ext_info *ei);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (c000000000d3ed80)
Location: net/sched/cls_api.c:772
Inline: False
Direct callers:
  - net/sched/cls_api.c:__tcf_block_put
```
**Symbols:**

```
c000000000d3ed80-c000000000d3ee84: tcf_block_offload_unbind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void tcf_block_offload_unbind(struct tcf_block *block, struct Qdisc *q, struct tcf_block_ext_info *ei);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffe0007b2016)
Location: net/sched/cls_api.c:772
Inline: False
Direct callers:
  - net/sched/cls_api.c:__tcf_block_put
```
**Symbols:**

```
ffffffe0007b2016-ffffffe0007b20b2: tcf_block_offload_unbind (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (ffffffff81936660)
Location: net/sched/cls_api.c:772
Inline: True
Direct callers:
  - net/sched/cls_api.c:__tcf_block_put
```
**Symbols:**

```
ffffffff81936660-ffffffff819366f1: tcf_block_offload_unbind.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (ffffffff818f0160)
Location: net/sched/cls_api.c:772
Inline: True
Direct callers:
  - net/sched/cls_api.c:__tcf_block_put
```
**Symbols:**

```
ffffffff818f0160-ffffffff818f01f1: tcf_block_offload_unbind.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (ffffffff819877f0)
Location: net/sched/cls_api.c:772
Inline: True
Direct callers:
  - net/sched/cls_api.c:__tcf_block_put
```
**Symbols:**

```
ffffffff819877f0-ffffffff81987881: tcf_block_offload_unbind.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (ffffffff819a9cb0)
Location: net/sched/cls_api.c:772
Inline: True
Direct callers:
  - net/sched/cls_api.c:__tcf_block_put
```
**Symbols:**

```
ffffffff819a9cb0-ffffffff819a9d41: tcf_block_offload_unbind.isra.0 (STB_LOCAL)
```
</details>
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
<b>Arch</b>
<ul>
</ul>
