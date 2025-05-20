# Function: <code>tcf_block_refcnt_get</code>

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
<summary>In <code>5.0</code>: ✅</summary>

```c
struct tcf_block *tcf_block_refcnt_get(struct net *net, u32 block_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff818fdb00)
Location: net/sched/cls_api.c:789
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tcf_block_get_ext
```
**Symbols:**

```
ffffffff818fdb00-ffffffff818fdb88: tcf_block_refcnt_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct tcf_block *tcf_block_refcnt_get(struct net *net, u32 block_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff8195d440)
Location: net/sched/cls_api.c:1016
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:__tcf_block_find
```
**Symbols:**

```
ffffffff8195d440-ffffffff8195d4a3: tcf_block_refcnt_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct tcf_block *tcf_block_refcnt_get(struct net *net, u32 block_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81993940)
Location: net/sched/cls_api.c:930
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:__tcf_block_find
```
**Symbols:**

```
ffffffff81993940-ffffffff819939a3: tcf_block_refcnt_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct tcf_block *tcf_block_refcnt_get(struct net *net, u32 block_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a6c8e0)
Location: net/sched/cls_api.c:893
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:__tcf_block_find
```
**Symbols:**

```
ffffffff81a6c8e0-ffffffff81a6c94d: tcf_block_refcnt_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct tcf_block *tcf_block_refcnt_get(struct net *net, u32 block_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a75280)
Location: net/sched/cls_api.c:895
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:__tcf_block_find
```
**Symbols:**

```
ffffffff81a75280-ffffffff81a752ff: tcf_block_refcnt_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct tcf_block *tcf_block_refcnt_get(struct net *net, u32 block_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a5dc20)
Location: net/sched/cls_api.c:895
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:__tcf_block_find
```
**Symbols:**

```
ffffffff81a5dc20-ffffffff81a5dca8: tcf_block_refcnt_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct tcf_block *tcf_block_refcnt_get(struct net *net, u32 block_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81b16de0)
Location: net/sched/cls_api.c:896
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:__tcf_block_find
```
**Symbols:**

```
ffffffff81b16de0-ffffffff81b16e68: tcf_block_refcnt_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct tcf_block *tcf_block_refcnt_get(struct net *net, u32 block_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81c9e780)
Location: net/sched/cls_api.c:913
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:__tcf_block_find
```
**Symbols:**

```
ffffffff81c9e780-ffffffff81c9e844: tcf_block_refcnt_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct tcf_block *tcf_block_refcnt_get(struct net *net, u32 block_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81e5af10)
Location: net/sched/cls_api.c:915
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:__tcf_block_find
```
**Symbols:**

```
ffffffff81e5af10-ffffffff81e5afd4: tcf_block_refcnt_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct tcf_block *tcf_block_refcnt_get(struct net *net, u32 block_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81eb6ce0)
Location: net/sched/cls_api.c:1020
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:__tcf_block_find
```
**Symbols:**

```
ffffffff81eb6ce0-ffffffff81eb6da0: tcf_block_refcnt_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct tcf_block *tcf_block_refcnt_get(struct net *net, u32 block_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81f79a80)
Location: net/sched/cls_api.c:1022
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:__tcf_block_find
```
**Symbols:**

```
ffffffff81f79a80-ffffffff81f79b40: tcf_block_refcnt_get (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct tcf_block *tcf_block_refcnt_get(struct net *net, u32 block_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffff800010c3fd48)
Location: net/sched/cls_api.c:930
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tcf_block_get_ext
```
**Symbols:**

```
ffff800010c3fd48-ffff800010c3fdbc: tcf_block_refcnt_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct tcf_block *tcf_block_refcnt_get(struct net *net, u32 block_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (c0d51bf8)
Location: net/sched/cls_api.c:930
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tcf_block_get_ext
```
**Symbols:**

```
c0d51bf8-c0d51c54: tcf_block_refcnt_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct tcf_block *tcf_block_refcnt_get(struct net *net, u32 block_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (c000000000d3a7f0)
Location: net/sched/cls_api.c:930
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tcf_block_get_ext
```
**Symbols:**

```
c000000000d3a7f0-c000000000d3a894: tcf_block_refcnt_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct tcf_block *tcf_block_refcnt_get(struct net *net, u32 block_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffe0007af92e)
Location: net/sched/cls_api.c:930
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tcf_block_get_ext
```
**Symbols:**

```
ffffffe0007af92e-ffffffe0007af9ae: tcf_block_refcnt_get (STB_LOCAL)
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
struct tcf_block *tcf_block_refcnt_get(struct net *net, u32 block_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff819337b0)
Location: net/sched/cls_api.c:930
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:__tcf_block_find
```
**Symbols:**

```
ffffffff819337b0-ffffffff81933813: tcf_block_refcnt_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct tcf_block *tcf_block_refcnt_get(struct net *net, u32 block_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff818ed2b0)
Location: net/sched/cls_api.c:930
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:__tcf_block_find
```
**Symbols:**

```
ffffffff818ed2b0-ffffffff818ed313: tcf_block_refcnt_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct tcf_block *tcf_block_refcnt_get(struct net *net, u32 block_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81984940)
Location: net/sched/cls_api.c:930
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:__tcf_block_find
```
**Symbols:**

```
ffffffff81984940-ffffffff819849a3: tcf_block_refcnt_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct tcf_block *tcf_block_refcnt_get(struct net *net, u32 block_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff819a7100)
Location: net/sched/cls_api.c:930
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:__tcf_block_find
```
**Symbols:**

```
ffffffff819a7100-ffffffff819a719c: tcf_block_refcnt_get (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
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
