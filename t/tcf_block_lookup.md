# Function: <code>tcf_block_lookup</code>

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
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff818d3602)
Location: net/sched/cls_api.c:433
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tcf_block_get_ext
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff818fdb05)
Location: net/sched/cls_api.c:782
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_refcnt_get
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff8195d449)
Location: net/sched/cls_api.c:1009
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_refcnt_get
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
In net/sched/cls_api.c (ffffffff81993949)
Location: net/sched/cls_api.c:923
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_refcnt_get
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a6c8eb)
Location: net/sched/cls_api.c:886
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_refcnt_get
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a7528f)
Location: net/sched/cls_api.c:888
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_refcnt_get
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a5dc2f)
Location: net/sched/cls_api.c:888
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_refcnt_get
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81b16def)
Location: net/sched/cls_api.c:889
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_refcnt_get
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81c9e798)
Location: net/sched/cls_api.c:906
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_refcnt_get
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81e5af28)
Location: net/sched/cls_api.c:908
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_refcnt_get
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81eb6cf8)
Location: net/sched/cls_api.c:1013
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_refcnt_get
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct tcf_block *tcf_block_lookup(struct net *net, u32 block_index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81f79a98)
Location: net/sched/cls_api.c:1014
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_refcnt_get
```
**Symbols:**

```
ffffffff81f78000-ffffffff81f7804a: tcf_block_lookup (STB_GLOBAL)
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
In net/sched/cls_api.c (ffff800010c3fd64)
Location: net/sched/cls_api.c:923
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_refcnt_get
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
In net/sched/cls_api.c (c0d51c0c)
Location: net/sched/cls_api.c:923
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_refcnt_get
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
In net/sched/cls_api.c (c000000000d3a80c)
Location: net/sched/cls_api.c:923
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_refcnt_get
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
In net/sched/cls_api.c (ffffffe0007af948)
Location: net/sched/cls_api.c:923
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_refcnt_get
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
In net/sched/cls_api.c (ffffffff819337b9)
Location: net/sched/cls_api.c:923
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_refcnt_get
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
In net/sched/cls_api.c (ffffffff818ed2b9)
Location: net/sched/cls_api.c:923
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_refcnt_get
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
In net/sched/cls_api.c (ffffffff81984949)
Location: net/sched/cls_api.c:923
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_refcnt_get
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
In net/sched/cls_api.c (ffffffff819a7119)
Location: net/sched/cls_api.c:923
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_refcnt_get
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
