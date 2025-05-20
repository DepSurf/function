# Function: <code>list_lru_walk_one_irq</code>

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
long unsigned int list_lru_walk_one_irq(struct list_lru *lru, int nid, struct mem_cgroup *memcg, list_lru_walk_cb isolate, void *cb_arg, long unsigned int *nr_to_walk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff81238050)
Location: mm/list_lru.c:286
Inline: False
Direct callers:
  - mm/workingset.c:scan_shadow_nodes
```
**Symbols:**

```
ffffffff81238050-ffffffff812380c9: list_lru_walk_one_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long unsigned int list_lru_walk_one_irq(struct list_lru *lru, int nid, struct mem_cgroup *memcg, list_lru_walk_cb isolate, void *cb_arg, long unsigned int *nr_to_walk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff81249630)
Location: mm/list_lru.c:284
Inline: False
Direct callers:
  - mm/workingset.c:scan_shadow_nodes
```
**Symbols:**

```
ffffffff81249630-ffffffff812496a8: list_lru_walk_one_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int list_lru_walk_one_irq(struct list_lru *lru, int nid, struct mem_cgroup *memcg, list_lru_walk_cb isolate, void *cb_arg, long unsigned int *nr_to_walk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff81257a80)
Location: mm/list_lru.c:284
Inline: False
Direct callers:
  - mm/workingset.c:scan_shadow_nodes
```
**Symbols:**

```
ffffffff81257a80-ffffffff81257af8: list_lru_walk_one_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int list_lru_walk_one_irq(struct list_lru *lru, int nid, struct mem_cgroup *memcg, list_lru_walk_cb isolate, void *cb_arg, long unsigned int *nr_to_walk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff81286240)
Location: mm/list_lru.c:274
Inline: False
Direct callers:
  - mm/workingset.c:scan_shadow_nodes
```
**Symbols:**

```
ffffffff81286240-ffffffff812862b5: list_lru_walk_one_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int list_lru_walk_one_irq(struct list_lru *lru, int nid, struct mem_cgroup *memcg, list_lru_walk_cb isolate, void *cb_arg, long unsigned int *nr_to_walk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff812904f0)
Location: mm/list_lru.c:274
Inline: False
Direct callers:
  - mm/workingset.c:scan_shadow_nodes
```
**Symbols:**

```
ffffffff812904f0-ffffffff81290565: list_lru_walk_one_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int list_lru_walk_one_irq(struct list_lru *lru, int nid, struct mem_cgroup *memcg, list_lru_walk_cb isolate, void *cb_arg, long unsigned int *nr_to_walk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff81295980)
Location: mm/list_lru.c:274
Inline: False
Direct callers:
  - mm/workingset.c:scan_shadow_nodes
```
**Symbols:**

```
ffffffff81295980-ffffffff812959f5: list_lru_walk_one_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long unsigned int list_lru_walk_one_irq(struct list_lru *lru, int nid, struct mem_cgroup *memcg, list_lru_walk_cb isolate, void *cb_arg, long unsigned int *nr_to_walk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff812d6000)
Location: mm/list_lru.c:274
Inline: False
Direct callers:
  - mm/workingset.c:scan_shadow_nodes
```
**Symbols:**

```
ffffffff812d6000-ffffffff812d6075: list_lru_walk_one_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long unsigned int list_lru_walk_one_irq(struct list_lru *lru, int nid, struct mem_cgroup *memcg, list_lru_walk_cb isolate, void *cb_arg, long unsigned int *nr_to_walk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff81335550)
Location: mm/list_lru.c:284
Inline: False
Direct callers:
  - mm/workingset.c:scan_shadow_nodes
```
**Symbols:**

```
ffffffff81335550-ffffffff813355e4: list_lru_walk_one_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int list_lru_walk_one_irq(struct list_lru *lru, int nid, struct mem_cgroup *memcg, list_lru_walk_cb isolate, void *cb_arg, long unsigned int *nr_to_walk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff813ac300)
Location: mm/list_lru.c:284
Inline: False
Direct callers:
  - mm/workingset.c:scan_shadow_nodes
```
**Symbols:**

```
ffffffff813ac300-ffffffff813ac394: list_lru_walk_one_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int list_lru_walk_one_irq(struct list_lru *lru, int nid, struct mem_cgroup *memcg, list_lru_walk_cb isolate, void *cb_arg, long unsigned int *nr_to_walk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff813e06a0)
Location: mm/list_lru.c:284
Inline: False
Direct callers:
  - mm/workingset.c:scan_shadow_nodes
```
**Symbols:**

```
ffffffff813e06a0-ffffffff813e0734: list_lru_walk_one_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int list_lru_walk_one_irq(struct list_lru *lru, int nid, struct mem_cgroup *memcg, list_lru_walk_cb isolate, void *cb_arg, long unsigned int *nr_to_walk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff8140af70)
Location: mm/list_lru.c:285
Inline: False
Direct callers:
  - mm/workingset.c:scan_shadow_nodes
```
**Symbols:**

```
ffffffff8140af70-ffffffff8140b004: list_lru_walk_one_irq (STB_GLOBAL)
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
long unsigned int list_lru_walk_one_irq(struct list_lru *lru, int nid, struct mem_cgroup *memcg, list_lru_walk_cb isolate, void *cb_arg, long unsigned int *nr_to_walk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffff8000102ef590)
Location: mm/list_lru.c:284
Inline: False
Direct callers:
  - mm/workingset.c:scan_shadow_nodes
```
**Symbols:**

```
ffff8000102ef590-ffff8000102ef668: list_lru_walk_one_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long unsigned int list_lru_walk_one_irq(struct list_lru *lru, int nid, struct mem_cgroup *memcg, list_lru_walk_cb isolate, void *cb_arg, long unsigned int *nr_to_walk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (c0513034)
Location: mm/list_lru.c:284
Inline: False
Direct callers:
  - mm/workingset.c:scan_shadow_nodes
```
**Symbols:**

```
c0513034-c05130b0: list_lru_walk_one_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long unsigned int list_lru_walk_one_irq(struct list_lru *lru, int nid, struct mem_cgroup *memcg, list_lru_walk_cb isolate, void *cb_arg, long unsigned int *nr_to_walk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (c0000000003b3c70)
Location: mm/list_lru.c:284
Inline: False
Direct callers:
  - mm/workingset.c:scan_shadow_nodes
```
**Symbols:**

```
c0000000003b3c70-c0000000003b3d58: list_lru_walk_one_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long unsigned int list_lru_walk_one_irq(struct list_lru *lru, int nid, struct mem_cgroup *memcg, list_lru_walk_cb isolate, void *cb_arg, long unsigned int *nr_to_walk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffe00020331a)
Location: mm/list_lru.c:284
Inline: False
Direct callers:
  - mm/workingset.c:scan_shadow_nodes
```
**Symbols:**

```
ffffffe00020331a-ffffffe0002033ce: list_lru_walk_one_irq (STB_GLOBAL)
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
long unsigned int list_lru_walk_one_irq(struct list_lru *lru, int nid, struct mem_cgroup *memcg, list_lru_walk_cb isolate, void *cb_arg, long unsigned int *nr_to_walk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff812500d0)
Location: mm/list_lru.c:284
Inline: False
Direct callers:
  - mm/workingset.c:scan_shadow_nodes
```
**Symbols:**

```
ffffffff812500d0-ffffffff81250148: list_lru_walk_one_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long unsigned int list_lru_walk_one_irq(struct list_lru *lru, int nid, struct mem_cgroup *memcg, list_lru_walk_cb isolate, void *cb_arg, long unsigned int *nr_to_walk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff81243070)
Location: mm/list_lru.c:284
Inline: False
Direct callers:
  - mm/workingset.c:scan_shadow_nodes
```
**Symbols:**

```
ffffffff81243070-ffffffff812430e2: list_lru_walk_one_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long unsigned int list_lru_walk_one_irq(struct list_lru *lru, int nid, struct mem_cgroup *memcg, list_lru_walk_cb isolate, void *cb_arg, long unsigned int *nr_to_walk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff8124de70)
Location: mm/list_lru.c:284
Inline: False
Direct callers:
  - mm/workingset.c:scan_shadow_nodes
```
**Symbols:**

```
ffffffff8124de70-ffffffff8124dee8: list_lru_walk_one_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int list_lru_walk_one_irq(struct list_lru *lru, int nid, struct mem_cgroup *memcg, list_lru_walk_cb isolate, void *cb_arg, long unsigned int *nr_to_walk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff8125d810)
Location: mm/list_lru.c:284
Inline: False
Direct callers:
  - mm/workingset.c:scan_shadow_nodes
```
**Symbols:**

```
ffffffff8125d810-ffffffff8125d87f: list_lru_walk_one_irq (STB_GLOBAL)
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
