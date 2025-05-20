# Function: <code>__tcf_chain_get</code>

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
struct tcf_chain *__tcf_chain_get(struct tcf_block *block, u32 chain_index, bool create, bool by_act);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff818fed10)
Location: net/sched/cls_api.c:278
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_chain_get_by_act
```
**Symbols:**

```
ffffffff818fed10-ffffffff818fedbe: __tcf_chain_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct tcf_chain *__tcf_chain_get(struct tcf_block *block, u32 chain_index, bool create, bool by_act);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff8195e710)
Location: net/sched/cls_api.c:407
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_chain_get_by_act
```
**Symbols:**

```
ffffffff8195e710-ffffffff8195e7fd: __tcf_chain_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct tcf_chain *__tcf_chain_get(struct tcf_block *block, u32 chain_index, bool create, bool by_act);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81994fe0)
Location: net/sched/cls_api.c:459
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_chain_get_by_act
```
**Symbols:**

```
ffffffff81994fe0-ffffffff819950cd: __tcf_chain_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct tcf_chain *__tcf_chain_get(struct tcf_block *block, u32 chain_index, bool create, bool by_act);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a6dd10)
Location: net/sched/cls_api.c:474
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_chain_get_by_act
```
**Symbols:**

```
ffffffff81a6dd10-ffffffff81a6ddfd: __tcf_chain_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct tcf_chain *__tcf_chain_get(struct tcf_block *block, u32 chain_index, bool create, bool by_act);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a766e0)
Location: net/sched/cls_api.c:474
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_chain_get_by_act
```
**Symbols:**

```
ffffffff81a766e0-ffffffff81a767cd: __tcf_chain_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct tcf_chain *__tcf_chain_get(struct tcf_block *block, u32 chain_index, bool create, bool by_act);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a5e5e0)
Location: net/sched/cls_api.c:474
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_chain_get_by_act
```
**Symbols:**

```
ffffffff81a5e5e0-ffffffff81a5e6cd: __tcf_chain_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct tcf_chain *__tcf_chain_get(struct tcf_block *block, u32 chain_index, bool create, bool by_act);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81b177b0)
Location: net/sched/cls_api.c:474
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_chain_get_by_act
```
**Symbols:**

```
ffffffff81b177b0-ffffffff81b1789d: __tcf_chain_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct tcf_chain *__tcf_chain_get(struct tcf_block *block, u32 chain_index, bool create, bool by_act);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81c9f5b0)
Location: net/sched/cls_api.c:491
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_chain_get_by_act
```
**Symbols:**

```
ffffffff81c9f5b0-ffffffff81c9f6d9: __tcf_chain_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct tcf_chain *__tcf_chain_get(struct tcf_block *block, u32 chain_index, bool create, bool by_act);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81e5b810)
Location: net/sched/cls_api.c:493
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_chain_get_by_act
```
**Symbols:**

```
ffffffff81e5b810-ffffffff81e5b939: __tcf_chain_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct tcf_chain *__tcf_chain_get(struct tcf_block *block, u32 chain_index, bool create, bool by_act);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81eb7f70)
Location: net/sched/cls_api.c:596
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_chain_get_by_act
```
**Symbols:**

```
ffffffff81eb7f70-ffffffff81eb805c: __tcf_chain_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct tcf_chain *__tcf_chain_get(struct tcf_block *block, u32 chain_index, bool create, bool by_act);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81f7afc0)
Location: net/sched/cls_api.c:597
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_chain_get_by_act
```
**Symbols:**

```
ffffffff81f7afc0-ffffffff81f7b0b8: __tcf_chain_get (STB_LOCAL)
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
struct tcf_chain *__tcf_chain_get(struct tcf_block *block, u32 chain_index, bool create, bool by_act);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffff800010c41b70)
Location: net/sched/cls_api.c:459
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_chain_get_by_act
```
**Symbols:**

```
ffff800010c41b70-ffff800010c41ca0: __tcf_chain_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct tcf_chain *__tcf_chain_get(struct tcf_block *block, u32 chain_index, bool create, bool by_act);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (c0d53970)
Location: net/sched/cls_api.c:459
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_chain_get_by_act
```
**Symbols:**

```
c0d53970-c0d53a84: __tcf_chain_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct tcf_chain *__tcf_chain_get(struct tcf_block *block, u32 chain_index, bool create, bool by_act);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (c000000000d3d910)
Location: net/sched/cls_api.c:459
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_chain_get_by_act
```
**Symbols:**

```
c000000000d3d910-c000000000d3dad4: __tcf_chain_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct tcf_chain *__tcf_chain_get(struct tcf_block *block, u32 chain_index, bool create, bool by_act);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffe0007b149a)
Location: net/sched/cls_api.c:459
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_chain_get_by_act
```
**Symbols:**

```
ffffffe0007b149a-ffffffe0007b1570: __tcf_chain_get (STB_LOCAL)
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
struct tcf_chain *__tcf_chain_get(struct tcf_block *block, u32 chain_index, bool create, bool by_act);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81934e50)
Location: net/sched/cls_api.c:459
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_chain_get_by_act
```
**Symbols:**

```
ffffffff81934e50-ffffffff81934f3d: __tcf_chain_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct tcf_chain *__tcf_chain_get(struct tcf_block *block, u32 chain_index, bool create, bool by_act);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff818ee950)
Location: net/sched/cls_api.c:459
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_chain_get_by_act
```
**Symbols:**

```
ffffffff818ee950-ffffffff818eea3d: __tcf_chain_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct tcf_chain *__tcf_chain_get(struct tcf_block *block, u32 chain_index, bool create, bool by_act);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81985fe0)
Location: net/sched/cls_api.c:459
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_chain_get_by_act
```
**Symbols:**

```
ffffffff81985fe0-ffffffff819860cd: __tcf_chain_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct tcf_chain *__tcf_chain_get(struct tcf_block *block, u32 chain_index, bool create, bool by_act);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff819a8fe0)
Location: net/sched/cls_api.c:459
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_chain_get_by_act
```
**Symbols:**

```
ffffffff819a8fe0-ffffffff819a90cd: __tcf_chain_get (STB_LOCAL)
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
