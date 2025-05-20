# Function: <code>shrink_slab</code>

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
In mm/vmscan.c (ffffffff811a0560)
Location: mm/vmscan.c:406
Inline: True
Inline callers:
  - mm/vmscan.c:drop_slab_node
  - mm/vmscan.c:shrink_zone
  - mm/vmscan.c:shrink_zone
Direct callers:
  - mm/vmscan.c:drop_slab_node
  - mm/vmscan.c:shrink_zone
  - mm/vmscan.c:shrink_zone
```
**Symbols:**

```
ffffffff811a0560-ffffffff811a0928: shrink_slab.part.40 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int shrink_slab(gfp_t gfp_mask, int nid, struct mem_cgroup *memcg, long unsigned int nr_scanned, long unsigned int nr_eligible);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/vmscan.c (ffffffff811bb6f6)
Location: mm/vmscan.c:419
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
Direct callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:drop_slab_node
```
**Symbols:**

```
ffffffff811b6930-ffffffff811b6cf8: shrink_slab.part.38 (STB_LOCAL)
ffffffff811b6d00-ffffffff811b6d2b: shrink_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int shrink_slab(gfp_t gfp_mask, int nid, struct mem_cgroup *memcg, long unsigned int nr_scanned, long unsigned int nr_eligible);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/vmscan.c (ffffffff811cbdc6)
Location: mm/vmscan.c:454
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
Direct callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:drop_slab_node
```
**Symbols:**

```
ffffffff811c6ee0-ffffffff811c72f4: shrink_slab.part.40 (STB_LOCAL)
ffffffff811c7300-ffffffff811c732b: shrink_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int shrink_slab(gfp_t gfp_mask, int nid, struct mem_cgroup *memcg, long unsigned int nr_scanned, long unsigned int nr_eligible);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/vmscan.c (ffffffff811d4a22)
Location: mm/vmscan.c:455
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
Direct callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:drop_slab_node
```
**Symbols:**

```
ffffffff811cf680-ffffffff811cfa49: shrink_slab.part.48 (STB_LOCAL)
ffffffff811cfa50-ffffffff811cfa7c: shrink_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int shrink_slab(gfp_t gfp_mask, int nid, struct mem_cgroup *memcg, long unsigned int nr_scanned, long unsigned int nr_eligible);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/vmscan.c (ffffffff811e9f72)
Location: mm/vmscan.c:460
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
Direct callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:drop_slab_node
```
**Symbols:**

```
ffffffff811e4aa0-ffffffff811e4e80: shrink_slab.part.51 (STB_LOCAL)
ffffffff811e4e80-ffffffff811e4eab: shrink_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int shrink_slab(gfp_t gfp_mask, int nid, struct mem_cgroup *memcg, int priority);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/vmscan.c (ffffffff8120b61d)
Location: mm/vmscan.c:499
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
Direct callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:drop_slab_node
```
**Symbols:**

```
ffffffff81206240-ffffffff812065e1: shrink_slab.part.45 (STB_LOCAL)
ffffffff8120cd89-ffffffff8120cdac: shrink_slab.part.45.cold.58 (STB_LOCAL)
ffffffff812069c0-ffffffff812069eb: shrink_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
long unsigned int shrink_slab(gfp_t gfp_mask, int nid, struct mem_cgroup *memcg, int priority);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81218f10)
Location: mm/vmscan.c:680
Inline: True
Direct callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:drop_slab_node
```
**Symbols:**

```
ffffffff81218f10-ffffffff812191a9: shrink_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
long unsigned int shrink_slab(gfp_t gfp_mask, int nid, struct mem_cgroup *memcg, int priority);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81228ee0)
Location: mm/vmscan.c:692
Inline: True
Direct callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:drop_slab_node
```
**Symbols:**

```
ffffffff81228ee0-ffffffff8122916e: shrink_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
long unsigned int shrink_slab(gfp_t gfp_mask, int nid, struct mem_cgroup *memcg, int priority);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81236c80)
Location: mm/vmscan.c:695
Inline: True
Direct callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:drop_slab_node
```
**Symbols:**

```
ffffffff81236c80-ffffffff81236f15: shrink_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int shrink_slab(gfp_t gfp_mask, int nid, struct mem_cgroup *memcg, int priority);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81266b40)
Location: mm/vmscan.c:652
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:drop_slab_node
```
**Symbols:**

```
ffffffff81266b40-ffffffff81266c53: shrink_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int shrink_slab(gfp_t gfp_mask, int nid, struct mem_cgroup *memcg, int priority);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81271590)
Location: mm/vmscan.c:645
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:drop_slab_node
```
**Symbols:**

```
ffffffff81271590-ffffffff812716a3: shrink_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int shrink_slab(gfp_t gfp_mask, int nid, struct mem_cgroup *memcg, int priority);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff812767a0)
Location: mm/vmscan.c:845
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:drop_slab_node
```
**Symbols:**

```
ffffffff812767a0-ffffffff812768b3: shrink_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long unsigned int shrink_slab(gfp_t gfp_mask, int nid, struct mem_cgroup *memcg, int priority);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff812b3fc0)
Location: mm/vmscan.c:891
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:drop_slab_node
```
**Symbols:**

```
ffffffff812b3fc0-ffffffff812b40d0: shrink_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long unsigned int shrink_slab(gfp_t gfp_mask, int nid, struct mem_cgroup *memcg, int priority);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8130ff70)
Location: mm/vmscan.c:903
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:drop_slab
```
**Symbols:**

```
ffffffff8130ff70-ffffffff8131008e: shrink_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int shrink_slab(gfp_t gfp_mask, int nid, struct mem_cgroup *memcg, int priority);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81383580)
Location: mm/vmscan.c:980
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:drop_slab
```
**Symbols:**

```
ffffffff81383580-ffffffff8138369e: shrink_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int shrink_slab(gfp_t gfp_mask, int nid, struct mem_cgroup *memcg, int priority);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff813b4db0)
Location: mm/vmscan.c:1033
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:shrink_one
  - mm/vmscan.c:drop_slab
```
**Symbols:**

```
ffffffff813b4db0-ffffffff813b4ece: shrink_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int shrink_slab(gfp_t gfp_mask, int nid, struct mem_cgroup *memcg, int priority);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shrinker.c (ffffffff813e4d40)
Location: mm/shrinker.c:612
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:shrink_one
  - mm/vmscan.c:drop_slab
```
**Symbols:**

```
ffffffff813e4d40-ffffffff813e4ea7: shrink_slab (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
long unsigned int shrink_slab(gfp_t gfp_mask, int nid, struct mem_cgroup *memcg, int priority);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffff8000102c8298)
Location: mm/vmscan.c:695
Inline: True
Direct callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:drop_slab_node
```
**Symbols:**

```
ffff8000102c8298-ffff8000102c8568: shrink_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
long unsigned int shrink_slab(gfp_t gfp_mask, int nid, struct mem_cgroup *memcg, int priority);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (c04f1a24)
Location: mm/vmscan.c:695
Inline: True
Direct callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:drop_slab_node
```
**Symbols:**

```
c04f1a24-c04f1d34: shrink_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
long unsigned int shrink_slab(gfp_t gfp_mask, int nid, struct mem_cgroup *memcg, int priority);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (c000000000382ba0)
Location: mm/vmscan.c:695
Inline: True
Direct callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:drop_slab_node
```
**Symbols:**

```
c000000000382ba0-c000000000383038: shrink_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
long unsigned int shrink_slab(gfp_t gfp_mask, int nid, struct mem_cgroup *memcg, int priority);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffe0001e6d1e)
Location: mm/vmscan.c:695
Inline: True
Direct callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:drop_slab_node
```
**Symbols:**

```
ffffffe0001e6d1e-ffffffe0001e6fce: shrink_slab (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
long unsigned int shrink_slab(gfp_t gfp_mask, int nid, struct mem_cgroup *memcg, int priority);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8122f2d0)
Location: mm/vmscan.c:695
Inline: True
Direct callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:drop_slab_node
```
**Symbols:**

```
ffffffff8122f2d0-ffffffff8122f565: shrink_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
long unsigned int shrink_slab(gfp_t gfp_mask, int nid, struct mem_cgroup *memcg, int priority);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81222390)
Location: mm/vmscan.c:695
Inline: True
Direct callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:drop_slab_node
```
**Symbols:**

```
ffffffff81222390-ffffffff81222625: shrink_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
long unsigned int shrink_slab(gfp_t gfp_mask, int nid, struct mem_cgroup *memcg, int priority);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8122d070)
Location: mm/vmscan.c:695
Inline: True
Direct callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:drop_slab_node
```
**Symbols:**

```
ffffffff8122d070-ffffffff8122d305: shrink_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
long unsigned int shrink_slab(gfp_t gfp_mask, int nid, struct mem_cgroup *memcg, int priority);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8123c4b0)
Location: mm/vmscan.c:695
Inline: True
Direct callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:drop_slab_node
```
**Symbols:**

```
ffffffff8123c4b0-ffffffff8123c710: shrink_slab (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int priority</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int nr_scanned</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int nr_eligible</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
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
