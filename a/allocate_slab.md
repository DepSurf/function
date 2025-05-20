# Function: <code>allocate_slab</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff811e96c3)
Location: mm/slub.c:1395
Inline: True
Inline callers:
  - mm/slub.c:new_slab
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812081b1)
Location: mm/slub.c:1522
Inline: True
Inline callers:
  - mm/slub.c:new_slab
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8121a211)
Location: mm/slub.c:1525
Inline: True
Inline callers:
  - mm/slub.c:new_slab
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81225cd2)
Location: mm/slub.c:1527
Inline: True
Inline callers:
  - mm/slub.c:new_slab
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
In mm/slub.c (ffffffff81242f82)
Location: mm/slub.c:1558
Inline: True
Inline callers:
  - mm/slub.c:new_slab
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
In mm/slub.c (ffffffff812647ec)
Location: mm/slub.c:1561
Inline: True
Inline callers:
  - mm/slub.c:new_slab
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
In mm/slub.c (ffffffff81278f1c)
Location: mm/slub.c:1619
Inline: True
Inline callers:
  - mm/slub.c:new_slab
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct page *allocate_slab(struct kmem_cache *s, gfp_t flags, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81294150)
Location: mm/slub.c:1636
Inline: False
Direct callers:
  - mm/slub.c:new_slab
```
**Symbols:**

```
ffffffff81294150-ffffffff812945c4: allocate_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct page *allocate_slab(struct kmem_cache *s, gfp_t flags, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812a3e60)
Location: mm/slub.c:1616
Inline: False
Direct callers:
  - mm/slub.c:new_slab
```
**Symbols:**

```
ffffffff812a3e60-ffffffff812a42f3: allocate_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct page *allocate_slab(struct kmem_cache *s, gfp_t flags, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812d9980)
Location: mm/slub.c:1666
Inline: False
Direct callers:
  - mm/slub.c:early_kmem_cache_node_alloc
```
**Symbols:**

```
ffffffff812d9980-ffffffff812d9d99: allocate_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct page *allocate_slab(struct kmem_cache *s, gfp_t flags, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812e4cb0)
Location: mm/slub.c:1734
Inline: False
Direct callers:
  - mm/slub.c:early_kmem_cache_node_alloc
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
ffffffff812e4cb0-ffffffff812e513f: allocate_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct page *allocate_slab(struct kmem_cache *s, gfp_t flags, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812ec870)
Location: mm/slub.c:1762
Inline: False
Direct callers:
  - mm/slub.c:early_kmem_cache_node_alloc
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
ffffffff812ec870-ffffffff812ecd06: allocate_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct page *allocate_slab(struct kmem_cache *s, gfp_t flags, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:1886
Inline: False
Direct callers:
  - mm/slub.c:early_kmem_cache_node_alloc
```
**Symbols:**

```
ffffffff81334a60-ffffffff81334eb1: allocate_slab (STB_LOCAL)
ffffffff81cc12a4-ffffffff81cc12d6: allocate_slab.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct slab *allocate_slab(struct kmem_cache *s, gfp_t flags, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:1948
Inline: False
Direct callers:
  - mm/slub.c:init_kmem_cache_nodes
```
**Symbols:**

```
ffffffff813a62b0-ffffffff813a6757: allocate_slab (STB_LOCAL)
ffffffff81e737c4-ffffffff81e737f7: allocate_slab.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct slab *allocate_slab(struct kmem_cache *s, gfp_t flags, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:1977
Inline: False
Direct callers:
  - mm/slub.c:early_kmem_cache_node_alloc
```
**Symbols:**

```
ffffffff814277e0-ffffffff81427b5f: allocate_slab (STB_LOCAL)
ffffffff8206765a-ffffffff8206768d: allocate_slab.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct slab *allocate_slab(struct kmem_cache *s, gfp_t flags, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:1988
Inline: False
Direct callers:
  - mm/slub.c:early_kmem_cache_node_alloc
```
**Symbols:**

```
ffffffff8145cd50-ffffffff8145d0c1: allocate_slab (STB_LOCAL)
ffffffff820e6f3b-ffffffff820e6f6e: allocate_slab.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct slab *allocate_slab(struct kmem_cache *s, gfp_t flags, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:2333
Inline: False
Direct callers:
  - mm/slub.c:early_kmem_cache_node_alloc
```
**Symbols:**

```
ffffffff81457460-ffffffff814577ce: allocate_slab (STB_LOCAL)
ffffffff821c1f72-ffffffff821c1fa4: allocate_slab.cold (STB_LOCAL)
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
struct page *allocate_slab(struct kmem_cache *s, gfp_t flags, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffff800010345bd0)
Location: mm/slub.c:1616
Inline: False
Direct callers:
  - mm/slub.c:new_slab
```
**Symbols:**

```
ffff800010345bd0-ffff800010346084: allocate_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct page *allocate_slab(struct kmem_cache *s, gfp_t flags, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (c0549978)
Location: mm/slub.c:1616
Inline: False
Direct callers:
  - mm/slub.c:new_slab
```
**Symbols:**

```
c0549978-c0549ddc: allocate_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct page *allocate_slab(struct kmem_cache *s, gfp_t flags, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (c000000000422290)
Location: mm/slub.c:1616
Inline: False
Direct callers:
  - mm/slub.c:new_slab
```
**Symbols:**

```
c000000000422290-c000000000422874: allocate_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct page *allocate_slab(struct kmem_cache *s, gfp_t flags, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffe00023835c)
Location: mm/slub.c:1616
Inline: False
Direct callers:
  - mm/slub.c:new_slab
```
**Symbols:**

```
ffffffe00023835c-ffffffe000238764: allocate_slab (STB_LOCAL)
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
struct page *allocate_slab(struct kmem_cache *s, gfp_t flags, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8129c440)
Location: mm/slub.c:1616
Inline: False
Direct callers:
  - mm/slub.c:new_slab
```
**Symbols:**

```
ffffffff8129c440-ffffffff8129c8d3: allocate_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct page *allocate_slab(struct kmem_cache *s, gfp_t flags, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8128dff0)
Location: mm/slub.c:1616
Inline: False
Direct callers:
  - mm/slub.c:new_slab
```
**Symbols:**

```
ffffffff8128dff0-ffffffff8128e465: allocate_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct page *allocate_slab(struct kmem_cache *s, gfp_t flags, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8129a250)
Location: mm/slub.c:1616
Inline: False
Direct callers:
  - mm/slub.c:new_slab
```
**Symbols:**

```
ffffffff8129a250-ffffffff8129a6e3: allocate_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct page *allocate_slab(struct kmem_cache *s, gfp_t flags, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812aa130)
Location: mm/slub.c:1616
Inline: False
Direct callers:
  - mm/slub.c:new_slab
```
**Symbols:**

```
ffffffff812aa130-ffffffff812aa5c3: allocate_slab (STB_LOCAL)
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
