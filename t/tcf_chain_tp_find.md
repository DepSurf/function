# Function: <code>tcf_chain_tp_find</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff8180299c)
Location: net/sched/cls_api.c:391
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_ctl_tfilter
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81880c72)
Location: net/sched/cls_api.c:568
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_ctl_tfilter
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
In net/sched/cls_api.c (ffffffff818d3b17)
Location: net/sched/cls_api.c:914
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
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
In net/sched/cls_api.c (ffffffff81900525)
Location: net/sched/cls_api.c:1360
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct tcf_proto *tcf_chain_tp_find(struct tcf_chain *chain, struct tcf_chain_info *chain_info, u32 protocol, u32 prio, bool prio_allocate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff8195cff0)
Location: net/sched/cls_api.c:1803
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
**Symbols:**

```
ffffffff8195cff0-ffffffff8195d06a: tcf_chain_tp_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct tcf_proto *tcf_chain_tp_find(struct tcf_chain *chain, struct tcf_chain_info *chain_info, u32 protocol, u32 prio, bool prio_allocate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff819934d0)
Location: net/sched/cls_api.c:1748
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
**Symbols:**

```
ffffffff819934d0-ffffffff8199354a: tcf_chain_tp_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct tcf_proto *tcf_chain_tp_find(struct tcf_chain *chain, struct tcf_chain_info *chain_info, u32 protocol, u32 prio, bool prio_allocate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a6cce0)
Location: net/sched/cls_api.c:1761
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_chain_tp_insert_unique
```
**Symbols:**

```
ffffffff81a6cce0-ffffffff81a6cd87: tcf_chain_tp_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct tcf_proto *tcf_chain_tp_find(struct tcf_chain *chain, struct tcf_chain_info *chain_info, u32 protocol, u32 prio, bool prio_allocate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a75560)
Location: net/sched/cls_api.c:1763
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_chain_tp_insert_unique
```
**Symbols:**

```
ffffffff81a75560-ffffffff81a75607: tcf_chain_tp_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct tcf_proto *tcf_chain_tp_find(struct tcf_chain *chain, struct tcf_chain_info *chain_info, u32 protocol, u32 prio, bool prio_allocate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a5dcb0)
Location: net/sched/cls_api.c:1764
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_chain_tp_insert_unique
```
**Symbols:**

```
ffffffff81a5dcb0-ffffffff81a5dd55: tcf_chain_tp_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct tcf_proto *tcf_chain_tp_find(struct tcf_chain *chain, struct tcf_chain_info *chain_info, u32 protocol, u32 prio, bool prio_allocate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81b16e70)
Location: net/sched/cls_api.c:1762
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_chain_tp_insert_unique
```
**Symbols:**

```
ffffffff81b16e70-ffffffff81b16f15: tcf_chain_tp_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct tcf_proto *tcf_chain_tp_find(struct tcf_chain *chain, struct tcf_chain_info *chain_info, u32 protocol, u32 prio, bool prio_allocate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81c9e850)
Location: net/sched/cls_api.c:1781
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_chain_tp_insert_unique
```
**Symbols:**

```
ffffffff81c9e850-ffffffff81c9e94f: tcf_chain_tp_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct tcf_proto *tcf_chain_tp_find(struct tcf_chain *chain, struct tcf_chain_info *chain_info, u32 protocol, u32 prio, bool prio_allocate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81e5aff0)
Location: net/sched/cls_api.c:1783
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_chain_tp_insert_unique
```
**Symbols:**

```
ffffffff81e5aff0-ffffffff81e5b0ef: tcf_chain_tp_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct tcf_proto *tcf_chain_tp_find(struct tcf_chain *chain, struct tcf_chain_info *chain_info, u32 protocol, u32 prio, bool prio_allocate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81eb6db0)
Location: net/sched/cls_api.c:1931
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_chain_tp_insert_unique
```
**Symbols:**

```
ffffffff81eb6db0-ffffffff81eb6eaf: tcf_chain_tp_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct tcf_proto *tcf_chain_tp_find(struct tcf_chain *chain, struct tcf_chain_info *chain_info, u32 protocol, u32 prio, bool prio_allocate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81f79b50)
Location: net/sched/cls_api.c:1981
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_chain_tp_insert_unique
```
**Symbols:**

```
ffffffff81f79b50-ffffffff81f79c4f: tcf_chain_tp_find (STB_LOCAL)
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
In net/sched/cls_api.c (ffff800010c40688)
Location: net/sched/cls_api.c:1748
Inline: True
Direct callers:
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
**Symbols:**

```
ffff800010c40688-ffff800010c40760: tcf_chain_tp_find.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct tcf_proto *tcf_chain_tp_find(struct tcf_chain *chain, struct tcf_chain_info *chain_info, u32 protocol, u32 prio, bool prio_allocate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (c0d51b5c)
Location: net/sched/cls_api.c:1748
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
**Symbols:**

```
c0d51b5c-c0d51bf8: tcf_chain_tp_find (STB_LOCAL)
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
In net/sched/cls_api.c (c000000000d40334)
Location: net/sched/cls_api.c:1748
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
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
In net/sched/cls_api.c (ffffffe0007b2d54)
Location: net/sched/cls_api.c:1748
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
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
struct tcf_proto *tcf_chain_tp_find(struct tcf_chain *chain, struct tcf_chain_info *chain_info, u32 protocol, u32 prio, bool prio_allocate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81933340)
Location: net/sched/cls_api.c:1748
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
**Symbols:**

```
ffffffff81933340-ffffffff819333ba: tcf_chain_tp_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct tcf_proto *tcf_chain_tp_find(struct tcf_chain *chain, struct tcf_chain_info *chain_info, u32 protocol, u32 prio, bool prio_allocate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff818ece40)
Location: net/sched/cls_api.c:1748
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
**Symbols:**

```
ffffffff818ece40-ffffffff818eceba: tcf_chain_tp_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct tcf_proto *tcf_chain_tp_find(struct tcf_chain *chain, struct tcf_chain_info *chain_info, u32 protocol, u32 prio, bool prio_allocate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff819844d0)
Location: net/sched/cls_api.c:1748
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
**Symbols:**

```
ffffffff819844d0-ffffffff8198454a: tcf_chain_tp_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct tcf_proto *tcf_chain_tp_find(struct tcf_chain *chain, struct tcf_chain_info *chain_info, u32 protocol, u32 prio, bool prio_allocate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff819a6a10)
Location: net/sched/cls_api.c:1748
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
**Symbols:**

```
ffffffff819a6a10-ffffffff819a6a8a: tcf_chain_tp_find (STB_LOCAL)
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
No changes between <code>amd64</code> and <code>armhf</code> ✅
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
