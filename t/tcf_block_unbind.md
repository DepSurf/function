# Function: <code>tcf_block_unbind</code>

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
In net/sched/cls_api.c (ffffffff8195efb1)
Location: net/sched/cls_api.c:1596
Inline: True
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
In net/sched/cls_api.c (ffffffff81996446)
Location: net/sched/cls_api.c:1518
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void tcf_block_unbind(struct tcf_block *block, struct flow_block_offload *bo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a6eaf0)
Location: net/sched/cls_api.c:1481
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_block_indr_cleanup
```
**Symbols:**

```
ffffffff81a6eaf0-ffffffff81a6ebc5: tcf_block_unbind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void tcf_block_unbind(struct tcf_block *block, struct flow_block_offload *bo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a774d0)
Location: net/sched/cls_api.c:1482
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_block_indr_cleanup
```
**Symbols:**

```
ffffffff81a774d0-ffffffff81a775a5: tcf_block_unbind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void tcf_block_unbind(struct tcf_block *block, struct flow_block_offload *bo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a5fae0)
Location: net/sched/cls_api.c:1482
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_block_indr_cleanup
```
**Symbols:**

```
ffffffff81a5fae0-ffffffff81a5fbb5: tcf_block_unbind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void tcf_block_unbind(struct tcf_block *block, struct flow_block_offload *bo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (0)
Location: net/sched/cls_api.c:1483
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_block_indr_cleanup
```
**Symbols:**

```
ffffffff81b18cf0-ffffffff81b18dd8: tcf_block_unbind (STB_LOCAL)
ffffffff81d391c2-ffffffff81d391d7: tcf_block_unbind.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void tcf_block_unbind(struct tcf_block *block, struct flow_block_offload *bo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (0)
Location: net/sched/cls_api.c:1500
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_block_indr_cleanup
```
**Symbols:**

```
ffffffff81ca03c0-ffffffff81ca04b5: tcf_block_unbind (STB_LOCAL)
ffffffff81f059c3-ffffffff81f059d7: tcf_block_unbind.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void tcf_block_unbind(struct tcf_block *block, struct flow_block_offload *bo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (0)
Location: net/sched/cls_api.c:1502
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_block_indr_cleanup
```
**Symbols:**

```
ffffffff81e5c380-ffffffff81e5c475: tcf_block_unbind (STB_LOCAL)
ffffffff820ad7cd-ffffffff820ad7e1: tcf_block_unbind.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void tcf_block_unbind(struct tcf_block *block, struct flow_block_offload *bo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (0)
Location: net/sched/cls_api.c:1608
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_block_indr_cleanup
```
**Symbols:**

```
ffffffff81eb8f10-ffffffff81eb9005: tcf_block_unbind (STB_LOCAL)
ffffffff8212e9c5-ffffffff8212e9d9: tcf_block_unbind.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void tcf_block_unbind(struct tcf_block *block, struct flow_block_offload *bo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (0)
Location: net/sched/cls_api.c:1638
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_block_indr_cleanup
```
**Symbols:**

```
ffffffff81f7c060-ffffffff81f7c155: tcf_block_unbind (STB_LOCAL)
ffffffff82210769-ffffffff8221077d: tcf_block_unbind.cold (STB_LOCAL)
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
In net/sched/cls_api.c (ffff800010c42ce4)
Location: net/sched/cls_api.c:1518
Inline: True
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
In net/sched/cls_api.c (c0d542d8)
Location: net/sched/cls_api.c:1518
Inline: True
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
In net/sched/cls_api.c (c000000000d3e7ec)
Location: net/sched/cls_api.c:1518
Inline: True
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
In net/sched/cls_api.c (ffffffe0007b1d04)
Location: net/sched/cls_api.c:1518
Inline: True
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
In net/sched/cls_api.c (ffffffff819362b6)
Location: net/sched/cls_api.c:1518
Inline: True
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
In net/sched/cls_api.c (ffffffff818efdb6)
Location: net/sched/cls_api.c:1518
Inline: True
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
In net/sched/cls_api.c (ffffffff81987446)
Location: net/sched/cls_api.c:1518
Inline: True
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
In net/sched/cls_api.c (ffffffff819a9906)
Location: net/sched/cls_api.c:1518
Inline: True
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
