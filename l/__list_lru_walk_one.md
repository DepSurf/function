# Function: <code>__list_lru_walk_one</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/list_lru.c (ffffffff811b9180)
Location: mm/list_lru.c:199
Inline: True
Direct callers:
  - mm/list_lru.c:list_lru_walk_one
  - mm/list_lru.c:list_lru_walk_node
  - mm/list_lru.c:list_lru_walk_node
```
**Symbols:**

```
ffffffff811b9180-ffffffff811b92a5: __list_lru_walk_one.isra.3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/list_lru.c (ffffffff811d3480)
Location: mm/list_lru.c:199
Inline: True
Direct callers:
  - mm/list_lru.c:list_lru_walk_node
  - mm/list_lru.c:list_lru_walk_node
  - mm/list_lru.c:list_lru_walk_one
```
**Symbols:**

```
ffffffff811d3480-ffffffff811d35a5: __list_lru_walk_one.isra.3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/list_lru.c (ffffffff811e3330)
Location: mm/list_lru.c:199
Inline: True
Direct callers:
  - mm/list_lru.c:list_lru_walk_node
  - mm/list_lru.c:list_lru_walk_node
  - mm/list_lru.c:list_lru_walk_one
```
**Symbols:**

```
ffffffff811e3330-ffffffff811e3455: __list_lru_walk_one.isra.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/list_lru.c (ffffffff811ed770)
Location: mm/list_lru.c:196
Inline: True
Direct callers:
  - mm/list_lru.c:list_lru_walk_node
  - mm/list_lru.c:list_lru_walk_node
  - mm/list_lru.c:list_lru_walk_one
```
**Symbols:**

```
ffffffff811ed770-ffffffff811ed89e: __list_lru_walk_one.isra.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/list_lru.c (ffffffff81203bc0)
Location: mm/list_lru.c:196
Inline: True
Direct callers:
  - mm/list_lru.c:list_lru_walk_node
  - mm/list_lru.c:list_lru_walk_node
  - mm/list_lru.c:list_lru_walk_one
```
**Symbols:**

```
ffffffff81203bc0-ffffffff81203cf7: __list_lru_walk_one.isra.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/list_lru.c (ffffffff81224750)
Location: mm/list_lru.c:197
Inline: True
Direct callers:
  - mm/list_lru.c:list_lru_walk_node
  - mm/list_lru.c:list_lru_walk_node
  - mm/list_lru.c:list_lru_walk_one
```
**Symbols:**

```
ffffffff81224750-ffffffff8122488a: __list_lru_walk_one.isra.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long unsigned int __list_lru_walk_one(struct list_lru_node *nlru, int memcg_idx, list_lru_walk_cb isolate, void *cb_arg, long unsigned int *nr_to_walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff812376b0)
Location: mm/list_lru.c:212
Inline: False
Direct callers:
  - mm/list_lru.c:list_lru_walk_node
  - mm/list_lru.c:list_lru_walk_one_irq
  - mm/list_lru.c:list_lru_walk_one
```
**Symbols:**

```
ffffffff812376b0-ffffffff812377cc: __list_lru_walk_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long unsigned int __list_lru_walk_one(struct list_lru_node *nlru, int memcg_idx, list_lru_walk_cb isolate, void *cb_arg, long unsigned int *nr_to_walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff81248c60)
Location: mm/list_lru.c:210
Inline: False
Direct callers:
  - mm/list_lru.c:list_lru_walk_node
  - mm/list_lru.c:list_lru_walk_one_irq
  - mm/list_lru.c:list_lru_walk_one
```
**Symbols:**

```
ffffffff81248c60-ffffffff81248d69: __list_lru_walk_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int __list_lru_walk_one(struct list_lru_node *nlru, int memcg_idx, list_lru_walk_cb isolate, void *cb_arg, long unsigned int *nr_to_walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff812570b0)
Location: mm/list_lru.c:210
Inline: False
Direct callers:
  - mm/list_lru.c:list_lru_walk_node
  - mm/list_lru.c:list_lru_walk_one_irq
  - mm/list_lru.c:list_lru_walk_one
```
**Symbols:**

```
ffffffff812570b0-ffffffff812571b9: __list_lru_walk_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int __list_lru_walk_one(struct list_lru_node *nlru, int memcg_idx, list_lru_walk_cb isolate, void *cb_arg, long unsigned int *nr_to_walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff81285790)
Location: mm/list_lru.c:200
Inline: False
Direct callers:
  - mm/list_lru.c:list_lru_walk_node
  - mm/list_lru.c:list_lru_walk_node
  - mm/list_lru.c:list_lru_walk_one_irq
```
**Symbols:**

```
ffffffff81285790-ffffffff81285899: __list_lru_walk_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int __list_lru_walk_one(struct list_lru_node *nlru, int memcg_idx, list_lru_walk_cb isolate, void *cb_arg, long unsigned int *nr_to_walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff8128fa70)
Location: mm/list_lru.c:200
Inline: False
Direct callers:
  - mm/list_lru.c:list_lru_walk_node
  - mm/list_lru.c:list_lru_walk_node
  - mm/list_lru.c:list_lru_walk_one_irq
```
**Symbols:**

```
ffffffff8128fa70-ffffffff8128fb79: __list_lru_walk_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int __list_lru_walk_one(struct list_lru_node *nlru, int memcg_idx, list_lru_walk_cb isolate, void *cb_arg, long unsigned int *nr_to_walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff812950d0)
Location: mm/list_lru.c:200
Inline: False
Direct callers:
  - mm/list_lru.c:list_lru_walk_node
  - mm/list_lru.c:list_lru_walk_node
  - mm/list_lru.c:list_lru_walk_one_irq
```
**Symbols:**

```
ffffffff812950d0-ffffffff812951d9: __list_lru_walk_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long unsigned int __list_lru_walk_one(struct list_lru_node *nlru, int memcg_idx, list_lru_walk_cb isolate, void *cb_arg, long unsigned int *nr_to_walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff812d5730)
Location: mm/list_lru.c:200
Inline: False
Direct callers:
  - mm/list_lru.c:list_lru_walk_node
  - mm/list_lru.c:list_lru_walk_node
  - mm/list_lru.c:list_lru_walk_one_irq
```
**Symbols:**

```
ffffffff812d5730-ffffffff812d5839: __list_lru_walk_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
long unsigned int __list_lru_walk_one(struct list_lru *lru, int nid, int memcg_idx, list_lru_walk_cb isolate, void *cb_arg, long unsigned int *nr_to_walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/list_lru.c (0)
Location: mm/list_lru.c:206
Inline: False
Direct callers:
  - mm/list_lru.c:list_lru_walk_node
  - mm/list_lru.c:list_lru_walk_node
  - mm/list_lru.c:list_lru_walk_one_irq
```
**Symbols:**

```
ffffffff81334e00-ffffffff81334fb1: __list_lru_walk_one (STB_LOCAL)
ffffffff81e6d8cf-ffffffff81e6d8e4: __list_lru_walk_one.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
long unsigned int __list_lru_walk_one(struct list_lru *lru, int nid, int memcg_idx, list_lru_walk_cb isolate, void *cb_arg, long unsigned int *nr_to_walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/list_lru.c (0)
Location: mm/list_lru.c:206
Inline: False
Direct callers:
  - mm/list_lru.c:list_lru_walk_node
  - mm/list_lru.c:list_lru_walk_node
  - mm/list_lru.c:list_lru_walk_one_irq
```
**Symbols:**

```
ffffffff813abb60-ffffffff813abd11: __list_lru_walk_one (STB_LOCAL)
ffffffff82063bea-ffffffff82063bff: __list_lru_walk_one.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
long unsigned int __list_lru_walk_one(struct list_lru *lru, int nid, int memcg_idx, list_lru_walk_cb isolate, void *cb_arg, long unsigned int *nr_to_walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/list_lru.c (0)
Location: mm/list_lru.c:206
Inline: False
Direct callers:
  - mm/list_lru.c:list_lru_walk_node
  - mm/list_lru.c:list_lru_walk_node
  - mm/list_lru.c:list_lru_walk_one_irq
```
**Symbols:**

```
ffffffff813dfef0-ffffffff813e00b1: __list_lru_walk_one (STB_LOCAL)
ffffffff820e32e1-ffffffff820e32f6: __list_lru_walk_one.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
long unsigned int __list_lru_walk_one(struct list_lru *lru, int nid, int memcg_idx, list_lru_walk_cb isolate, void *cb_arg, long unsigned int *nr_to_walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/list_lru.c (0)
Location: mm/list_lru.c:207
Inline: False
Direct callers:
  - mm/list_lru.c:list_lru_walk_node
  - mm/list_lru.c:list_lru_walk_node
  - mm/list_lru.c:list_lru_walk_one_irq
```
**Symbols:**

```
ffffffff8140a7a0-ffffffff8140a961: __list_lru_walk_one (STB_LOCAL)
ffffffff821bfd2e-ffffffff821bfd43: __list_lru_walk_one.cold (STB_LOCAL)
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
long unsigned int __list_lru_walk_one(struct list_lru_node *nlru, int memcg_idx, list_lru_walk_cb isolate, void *cb_arg, long unsigned int *nr_to_walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffff8000102eeab0)
Location: mm/list_lru.c:210
Inline: False
Direct callers:
  - mm/list_lru.c:list_lru_walk_node
  - mm/list_lru.c:list_lru_walk_one_irq
  - mm/list_lru.c:list_lru_walk_one
```
**Symbols:**

```
ffff8000102eeab0-ffff8000102eebec: __list_lru_walk_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long unsigned int __list_lru_walk_one(struct list_lru_node *nlru, int memcg_idx, list_lru_walk_cb isolate, void *cb_arg, long unsigned int *nr_to_walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (c0512990)
Location: mm/list_lru.c:210
Inline: False
Direct callers:
  - mm/list_lru.c:list_lru_walk_node
  - mm/list_lru.c:list_lru_walk_one_irq
  - mm/list_lru.c:list_lru_walk_one
```
**Symbols:**

```
c0512990-c0512aec: __list_lru_walk_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long unsigned int __list_lru_walk_one(struct list_lru_node *nlru, int memcg_idx, list_lru_walk_cb isolate, void *cb_arg, long unsigned int *nr_to_walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (c0000000003b2c50)
Location: mm/list_lru.c:210
Inline: False
Direct callers:
  - mm/list_lru.c:list_lru_walk_node
  - mm/list_lru.c:list_lru_walk_one_irq
  - mm/list_lru.c:list_lru_walk_one
```
**Symbols:**

```
c0000000003b2c50-c0000000003b2e44: __list_lru_walk_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long unsigned int __list_lru_walk_one(struct list_lru_node *nlru, int memcg_idx, list_lru_walk_cb isolate, void *cb_arg, long unsigned int *nr_to_walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffe000202a6e)
Location: mm/list_lru.c:210
Inline: False
Direct callers:
  - mm/list_lru.c:list_lru_walk_node
  - mm/list_lru.c:list_lru_walk_one_irq
  - mm/list_lru.c:list_lru_walk_one
```
**Symbols:**

```
ffffffe000202a6e-ffffffe000202b74: __list_lru_walk_one (STB_LOCAL)
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
long unsigned int __list_lru_walk_one(struct list_lru_node *nlru, int memcg_idx, list_lru_walk_cb isolate, void *cb_arg, long unsigned int *nr_to_walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff8124f700)
Location: mm/list_lru.c:210
Inline: False
Direct callers:
  - mm/list_lru.c:list_lru_walk_node
  - mm/list_lru.c:list_lru_walk_one_irq
  - mm/list_lru.c:list_lru_walk_one
```
**Symbols:**

```
ffffffff8124f700-ffffffff8124f809: __list_lru_walk_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long unsigned int __list_lru_walk_one(struct list_lru_node *nlru, int memcg_idx, list_lru_walk_cb isolate, void *cb_arg, long unsigned int *nr_to_walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff812426a0)
Location: mm/list_lru.c:210
Inline: False
Direct callers:
  - mm/list_lru.c:list_lru_walk_node
  - mm/list_lru.c:list_lru_walk_one_irq
  - mm/list_lru.c:list_lru_walk_one
```
**Symbols:**

```
ffffffff812426a0-ffffffff812427a9: __list_lru_walk_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long unsigned int __list_lru_walk_one(struct list_lru_node *nlru, int memcg_idx, list_lru_walk_cb isolate, void *cb_arg, long unsigned int *nr_to_walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff8124d4a0)
Location: mm/list_lru.c:210
Inline: False
Direct callers:
  - mm/list_lru.c:list_lru_walk_node
  - mm/list_lru.c:list_lru_walk_one_irq
  - mm/list_lru.c:list_lru_walk_one
```
**Symbols:**

```
ffffffff8124d4a0-ffffffff8124d5a9: __list_lru_walk_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int __list_lru_walk_one(struct list_lru_node *nlru, int memcg_idx, list_lru_walk_cb isolate, void *cb_arg, long unsigned int *nr_to_walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff8125d020)
Location: mm/list_lru.c:210
Inline: False
Direct callers:
  - mm/list_lru.c:list_lru_walk_node
  - mm/list_lru.c:list_lru_walk_one_irq
  - mm/list_lru.c:list_lru_walk_one
```
**Symbols:**

```
ffffffff8125d020-ffffffff8125d129: __list_lru_walk_one (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct list_lru *lru</code>
</li>
<li>
<b>Param added. </b>
<code>int nid</code>
</li>
<li>
<b>Param removed. </b>
<code>struct list_lru_node *nlru</code>
</li>
<li>
<b>Param reordered. </b>
<code>nlru, memcg_idx, isolate, cb_arg, nr_to_walk</code> ➡️ <code>lru, nid, memcg_idx, isolate, cb_arg, nr_to_walk</code>
</li>
</ul>
</details>
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
