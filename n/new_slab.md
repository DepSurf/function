# Function: <code>new_slab</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct page *new_slab(struct kmem_cache *s, gfp_t flags, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff811e96a0)
Location: mm/slub.c:1491
Inline: False
Direct callers:
  - mm/slub.c:___slab_alloc
  - mm/slub.c:kmem_cache_open
```
**Symbols:**

```
ffffffff811e96a0-ffffffff811e9b2a: new_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct page *new_slab(struct kmem_cache *s, gfp_t flags, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81208170)
Location: mm/slub.c:1623
Inline: False
Direct callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
ffffffff81208170-ffffffff81208845: new_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct page *new_slab(struct kmem_cache *s, gfp_t flags, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8121a1d0)
Location: mm/slub.c:1626
Inline: False
Direct callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
ffffffff8121a1d0-ffffffff8121a8b1: new_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct page *new_slab(struct kmem_cache *s, gfp_t flags, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81225c90)
Location: mm/slub.c:1628
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_create
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
ffffffff81225c90-ffffffff812262e4: new_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct page *new_slab(struct kmem_cache *s, gfp_t flags, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81242f40)
Location: mm/slub.c:1643
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_create
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
ffffffff81242f40-ffffffff812435ad: new_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
struct page *new_slab(struct kmem_cache *s, gfp_t flags, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:1646
Inline: False
Direct callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
ffffffff812647b0-ffffffff81264ead: new_slab (STB_LOCAL)
ffffffff8126ae9f-ffffffff8126aecd: new_slab.cold.92 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
struct page *new_slab(struct kmem_cache *s, gfp_t flags, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:1705
Inline: False
Direct callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
ffffffff81278ee0-ffffffff8127961a: new_slab (STB_LOCAL)
ffffffff8127f72f-ffffffff8127f75d: new_slab.cold.94 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct page *new_slab(struct kmem_cache *s, gfp_t flags, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:1717
Inline: False
Direct callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
ffffffff812945d0-ffffffff81294638: new_slab (STB_LOCAL)
ffffffff8129b5d8-ffffffff8129b60b: new_slab.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct page *new_slab(struct kmem_cache *s, gfp_t flags, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:1696
Inline: False
Direct callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
ffffffff812a4300-ffffffff812a4368: new_slab (STB_LOCAL)
ffffffff812ab485-ffffffff812ab4b8: new_slab.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct page *new_slab(struct kmem_cache *s, gfp_t flags, int node);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/slub.c (ffffffff812d9e32)
Location: mm/slub.c:1746
Inline: True
Inline callers:
  - mm/slub.c:early_kmem_cache_node_alloc
Direct callers:
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
ffffffff812d9da0-ffffffff812d9e08: new_slab (STB_LOCAL)
ffffffff812dfe4b-ffffffff812dfe7e: new_slab.cold (STB_LOCAL)
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
In mm/slub.c (ffffffff812e5162)
Location: mm/slub.c:1816
Inline: True
Inline callers:
  - mm/slub.c:early_kmem_cache_node_alloc
  - mm/slub.c:___slab_alloc
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
In mm/slub.c (ffffffff812ecd32)
Location: mm/slub.c:1844
Inline: True
Inline callers:
  - mm/slub.c:early_kmem_cache_node_alloc
  - mm/slub.c:___slab_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct page *new_slab(struct kmem_cache *s, gfp_t flags, int node);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81334f42)
Location: mm/slub.c:1963
Inline: True
Inline callers:
  - mm/slub.c:early_kmem_cache_node_alloc
Direct callers:
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
ffffffff81334ec0-ffffffff81334f11: new_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct slab *new_slab(struct kmem_cache *s, gfp_t flags, int node);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff813ad391)
Location: mm/slub.c:2022
Inline: True
Inline callers:
  - mm/slub.c:init_kmem_cache_nodes
Direct callers:
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
ffffffff813a6760-ffffffff813a67b9: new_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct slab *new_slab(struct kmem_cache *s, gfp_t flags, int node);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81427c04)
Location: mm/slub.c:2044
Inline: True
Inline callers:
  - mm/slub.c:early_kmem_cache_node_alloc
Direct callers:
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
ffffffff81427b70-ffffffff81427bc9: new_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct slab *new_slab(struct kmem_cache *s, gfp_t flags, int node);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8145d17a)
Location: mm/slub.c:2055
Inline: True
Inline callers:
  - mm/slub.c:early_kmem_cache_node_alloc
Direct callers:
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
ffffffff8145d0e0-ffffffff8145d139: new_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct slab *new_slab(struct kmem_cache *s, gfp_t flags, int node);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8145787a)
Location: mm/slub.c:2400
Inline: True
Inline callers:
  - mm/slub.c:early_kmem_cache_node_alloc
Direct callers:
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
ffffffff814577e0-ffffffff81457839: new_slab (STB_LOCAL)
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
struct page *new_slab(struct kmem_cache *s, gfp_t flags, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffff800010346088)
Location: mm/slub.c:1696
Inline: False
Direct callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
ffff800010346088-ffff800010346140: new_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct page *new_slab(struct kmem_cache *s, gfp_t flags, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (c0549ddc)
Location: mm/slub.c:1696
Inline: False
Direct callers:
  - mm/slub.c:kmem_cache_open
```
**Symbols:**

```
c0549ddc-c0549ea0: new_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct page *new_slab(struct kmem_cache *s, gfp_t flags, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (c000000000422880)
Location: mm/slub.c:1696
Inline: False
Direct callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
c000000000422880-c00000000042295c: new_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct page *new_slab(struct kmem_cache *s, gfp_t flags, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffe000238764)
Location: mm/slub.c:1696
Inline: False
Direct callers:
  - mm/slub.c:kmem_cache_open
```
**Symbols:**

```
ffffffe000238764-ffffffe0002387ea: new_slab (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
struct page *new_slab(struct kmem_cache *s, gfp_t flags, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:1696
Inline: False
Direct callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
ffffffff8129c8e0-ffffffff8129c948: new_slab (STB_LOCAL)
ffffffff812a3a65-ffffffff812a3a98: new_slab.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct page *new_slab(struct kmem_cache *s, gfp_t flags, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:1696
Inline: False
Direct callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
ffffffff8128e470-ffffffff8128e4d8: new_slab (STB_LOCAL)
ffffffff81295535-ffffffff81295568: new_slab.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct page *new_slab(struct kmem_cache *s, gfp_t flags, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:1696
Inline: False
Direct callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
ffffffff8129a6f0-ffffffff8129a758: new_slab (STB_LOCAL)
ffffffff812a1875-ffffffff812a18a8: new_slab.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct page *new_slab(struct kmem_cache *s, gfp_t flags, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:1696
Inline: False
Direct callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
ffffffff812aa5d0-ffffffff812aa638: new_slab (STB_LOCAL)
ffffffff812b1a25-ffffffff812b1a58: new_slab.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
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
No changes between <code>4.15</code> and <code>4.18</code> ✅
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>struct page *</code> ➡️ <code>struct slab *</code>
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
