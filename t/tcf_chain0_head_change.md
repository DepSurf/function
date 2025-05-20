# Function: <code>tcf_chain0_head_change</code>

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
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81901492)
Location: net/sched/cls_api.c:226
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_chain_flush
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
In net/sched/cls_api.c (ffffffff8195da00)
Location: net/sched/cls_api.c:323
Inline: True
Direct callers:
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_chain_tp_delete_empty
  - net/sched/cls_api.c:tcf_chain_flush
```
**Symbols:**

```
ffffffff8195da00-ffffffff8195da61: tcf_chain0_head_change.isra.0 (STB_LOCAL)
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
In net/sched/cls_api.c (ffffffff819940f0)
Location: net/sched/cls_api.c:374
Inline: True
Direct callers:
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_chain_tp_delete_empty
  - net/sched/cls_api.c:tcf_chain_flush
  - net/sched/cls_api.c:tcf_chain_flush
```
**Symbols:**

```
ffffffff819940f0-ffffffff81994151: tcf_chain0_head_change.isra.0 (STB_LOCAL)
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
In net/sched/cls_api.c (ffffffff81a6c2a0)
Location: net/sched/cls_api.c:375
Inline: True
Direct callers:
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tcf_chain_tp_delete_empty
  - net/sched/cls_api.c:tcf_chain_tp_insert_unique
  - net/sched/cls_api.c:tcf_chain_flush
  - net/sched/cls_api.c:tcf_chain_flush
```
**Symbols:**

```
ffffffff81a6c2a0-ffffffff81a6c301: tcf_chain0_head_change.isra.0 (STB_LOCAL)
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
In net/sched/cls_api.c (ffffffff81a74c40)
Location: net/sched/cls_api.c:375
Inline: True
Direct callers:
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tcf_chain_tp_delete_empty
  - net/sched/cls_api.c:tcf_chain_tp_insert_unique
  - net/sched/cls_api.c:tcf_chain_flush
  - net/sched/cls_api.c:tcf_chain_flush
```
**Symbols:**

```
ffffffff81a74c40-ffffffff81a74ca1: tcf_chain0_head_change.isra.0 (STB_LOCAL)
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
In net/sched/cls_api.c (ffffffff81a5d7f0)
Location: net/sched/cls_api.c:375
Inline: True
Direct callers:
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tcf_chain_tp_delete_empty
  - net/sched/cls_api.c:tcf_chain_tp_insert_unique
  - net/sched/cls_api.c:tcf_chain_flush
  - net/sched/cls_api.c:tcf_chain_flush
```
**Symbols:**

```
ffffffff81a5d7f0-ffffffff81a5d851: tcf_chain0_head_change.isra.0 (STB_LOCAL)
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
In net/sched/cls_api.c (ffffffff81b16700)
Location: net/sched/cls_api.c:375
Inline: True
Direct callers:
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tcf_chain_tp_delete_empty
  - net/sched/cls_api.c:tcf_chain_tp_insert_unique
  - net/sched/cls_api.c:tcf_chain_flush
  - net/sched/cls_api.c:tcf_chain_flush
```
**Symbols:**

```
ffffffff81b16700-ffffffff81b16761: tcf_chain0_head_change.isra.0 (STB_LOCAL)
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
In net/sched/cls_api.c (ffffffff81c9dde0)
Location: net/sched/cls_api.c:392
Inline: True
Direct callers:
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tcf_chain_tp_delete_empty
  - net/sched/cls_api.c:tcf_chain_tp_insert_unique
  - net/sched/cls_api.c:tcf_chain_flush
  - net/sched/cls_api.c:tcf_chain_flush
```
**Symbols:**

```
ffffffff81c9dde0-ffffffff81c9de59: tcf_chain0_head_change.isra.0 (STB_LOCAL)
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
In net/sched/cls_api.c (ffffffff81e5a4c0)
Location: net/sched/cls_api.c:394
Inline: True
Direct callers:
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tcf_chain_tp_delete_empty
  - net/sched/cls_api.c:tcf_chain_tp_insert_unique
  - net/sched/cls_api.c:tcf_chain_flush
  - net/sched/cls_api.c:tcf_chain_flush
```
**Symbols:**

```
ffffffff81e5a4c0-ffffffff81e5a539: tcf_chain0_head_change.isra.0 (STB_LOCAL)
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
In net/sched/cls_api.c (ffffffff81eb5d70)
Location: net/sched/cls_api.c:496
Inline: True
Direct callers:
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tcf_chain_tp_delete_empty
  - net/sched/cls_api.c:tcf_chain_tp_insert_unique
  - net/sched/cls_api.c:tcf_chain_flush
  - net/sched/cls_api.c:tcf_chain_flush
```
**Symbols:**

```
ffffffff81eb5d70-ffffffff81eb5de9: tcf_chain0_head_change.isra.0 (STB_LOCAL)
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
In net/sched/cls_api.c (ffffffff81f78a80)
Location: net/sched/cls_api.c:496
Inline: True
Direct callers:
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tcf_chain_tp_delete_empty
  - net/sched/cls_api.c:tcf_chain_tp_insert_unique
  - net/sched/cls_api.c:tcf_chain_flush
  - net/sched/cls_api.c:tcf_chain_flush
```
**Symbols:**

```
ffffffff81f78a80-ffffffff81f78afd: tcf_chain0_head_change.isra.0 (STB_LOCAL)
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
In net/sched/cls_api.c (ffff800010c40600)
Location: net/sched/cls_api.c:374
Inline: True
Direct callers:
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_chain_tp_delete_empty
  - net/sched/cls_api.c:tcf_chain_flush
  - net/sched/cls_api.c:tcf_chain_flush
```
**Symbols:**

```
ffff800010c40600-ffff800010c40688: tcf_chain0_head_change.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void tcf_chain0_head_change(struct tcf_chain *chain, struct tcf_proto *tp_head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (c0d5194c)
Location: net/sched/cls_api.c:374
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_chain_tp_delete_empty
  - net/sched/cls_api.c:tcf_chain_flush
  - net/sched/cls_api.c:tcf_chain_flush
```
**Symbols:**

```
c0d5194c-c0d519bc: tcf_chain0_head_change (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void tcf_chain0_head_change(struct tcf_chain *chain, struct tcf_proto *tp_head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (c000000000d3a730)
Location: net/sched/cls_api.c:374
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_chain_tp_delete_empty
  - net/sched/cls_api.c:tcf_chain_flush
  - net/sched/cls_api.c:tcf_chain_flush
```
**Symbols:**

```
c000000000d3a730-c000000000d3a7ec: tcf_chain0_head_change (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void tcf_chain0_head_change(struct tcf_chain *chain, struct tcf_proto *tp_head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffe0007af82c)
Location: net/sched/cls_api.c:374
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_chain_tp_delete_empty
  - net/sched/cls_api.c:tcf_chain_flush
  - net/sched/cls_api.c:tcf_chain_flush
```
**Symbols:**

```
ffffffe0007af82c-ffffffe0007af8a2: tcf_chain0_head_change (STB_LOCAL)
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
In net/sched/cls_api.c (ffffffff81933f60)
Location: net/sched/cls_api.c:374
Inline: True
Direct callers:
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_chain_tp_delete_empty
  - net/sched/cls_api.c:tcf_chain_flush
  - net/sched/cls_api.c:tcf_chain_flush
```
**Symbols:**

```
ffffffff81933f60-ffffffff81933fc1: tcf_chain0_head_change.isra.0 (STB_LOCAL)
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
In net/sched/cls_api.c (ffffffff818eda60)
Location: net/sched/cls_api.c:374
Inline: True
Direct callers:
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_chain_tp_delete_empty
  - net/sched/cls_api.c:tcf_chain_flush
  - net/sched/cls_api.c:tcf_chain_flush
```
**Symbols:**

```
ffffffff818eda60-ffffffff818edac1: tcf_chain0_head_change.isra.0 (STB_LOCAL)
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
In net/sched/cls_api.c (ffffffff819850f0)
Location: net/sched/cls_api.c:374
Inline: True
Direct callers:
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_chain_tp_delete_empty
  - net/sched/cls_api.c:tcf_chain_flush
  - net/sched/cls_api.c:tcf_chain_flush
```
**Symbols:**

```
ffffffff819850f0-ffffffff81985151: tcf_chain0_head_change.isra.0 (STB_LOCAL)
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
In net/sched/cls_api.c (ffffffff819a7e60)
Location: net/sched/cls_api.c:374
Inline: True
Direct callers:
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_chain_tp_delete_empty
  - net/sched/cls_api.c:tcf_chain_flush
  - net/sched/cls_api.c:tcf_chain_flush
```
**Symbols:**

```
ffffffff819a7e60-ffffffff819a7ec1: tcf_chain0_head_change.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
