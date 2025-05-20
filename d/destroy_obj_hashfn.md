# Function: <code>destroy_obj_hashfn</code>

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
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81999438)
Location: net/sched/cls_api.c:51
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_new_tfilter
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
In net/sched/cls_api.c (ffffffff81a6c310)
Location: net/sched/cls_api.c:52
Inline: True
Direct callers:
  - net/sched/cls_api.c:tcf_chain_tp_insert_unique
```
**Symbols:**

```
ffffffff81a6c310-ffffffff81a6c36d: destroy_obj_hashfn.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a74cb0)
Location: net/sched/cls_api.c:52
Inline: True
Direct callers:
  - net/sched/cls_api.c:tcf_chain_tp_insert_unique
```
**Symbols:**

```
ffffffff81a74cb0-ffffffff81a74d0d: destroy_obj_hashfn.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a5d860)
Location: net/sched/cls_api.c:52
Inline: True
Direct callers:
  - net/sched/cls_api.c:tcf_chain_tp_insert_unique
```
**Symbols:**

```
ffffffff81a5d860-ffffffff81a5d8bd: destroy_obj_hashfn.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (ffffffff81b16770)
Location: net/sched/cls_api.c:52
Inline: True
Direct callers:
  - net/sched/cls_api.c:tcf_chain_tp_insert_unique
```
**Symbols:**

```
ffffffff81b16770-ffffffff81b167cd: destroy_obj_hashfn.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (ffffffff81c9de60)
Location: net/sched/cls_api.c:69
Inline: True
Direct callers:
  - net/sched/cls_api.c:tcf_chain_tp_insert_unique
```
**Symbols:**

```
ffffffff81c9de60-ffffffff81c9dec9: destroy_obj_hashfn.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (ffffffff81e5a550)
Location: net/sched/cls_api.c:70
Inline: True
Direct callers:
  - net/sched/cls_api.c:tcf_chain_tp_insert_unique
```
**Symbols:**

```
ffffffff81e5a550-ffffffff81e5a5b9: destroy_obj_hashfn.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (ffffffff81eb5e00)
Location: net/sched/cls_api.c:172
Inline: True
Direct callers:
  - net/sched/cls_api.c:tcf_chain_tp_insert_unique
```
**Symbols:**

```
ffffffff81eb5e00-ffffffff81eb5e69: destroy_obj_hashfn.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (ffffffff81f78b10)
Location: net/sched/cls_api.c:172
Inline: True
Direct callers:
  - net/sched/cls_api.c:tcf_chain_tp_insert_unique
```
**Symbols:**

```
ffffffff81f78b10-ffffffff81f78b79: destroy_obj_hashfn.isra.0 (STB_LOCAL)
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
In net/sched/cls_api.c (ffff800010c46138)
Location: net/sched/cls_api.c:51
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
In net/sched/cls_api.c (c0d55fcc)
Location: net/sched/cls_api.c:51
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_proto_signal_destroying
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
In net/sched/cls_api.c (c000000000d40b50)
Location: net/sched/cls_api.c:51
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_proto_signal_destroying
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
In net/sched/cls_api.c (ffffffe0007b3018)
Location: net/sched/cls_api.c:51
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_proto_signal_destroying
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
In net/sched/cls_api.c (ffffffff819392a8)
Location: net/sched/cls_api.c:51
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
In net/sched/cls_api.c (ffffffff818f2da8)
Location: net/sched/cls_api.c:51
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
In net/sched/cls_api.c (ffffffff8198a438)
Location: net/sched/cls_api.c:51
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
In net/sched/cls_api.c (ffffffff819ab7a7)
Location: net/sched/cls_api.c:51
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_new_tfilter
```
</details>
</li>
</ul>

## Differences
