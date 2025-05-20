# Function: <code>alloc_slab_page</code>

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
In mm/slub.c (ffffffff811e971a)
Location: mm/slub.c:1374
Inline: True
Inline callers:
  - mm/slub.c:new_slab
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
In mm/slub.c (ffffffff812081f5)
Location: mm/slub.c:1398
Inline: True
Inline callers:
  - mm/slub.c:new_slab
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
In mm/slub.c (ffffffff8121a255)
Location: mm/slub.c:1397
Inline: True
Inline callers:
  - mm/slub.c:new_slab
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
In mm/slub.c (ffffffff81225d2e)
Location: mm/slub.c:1399
Inline: True
Inline callers:
  - mm/slub.c:new_slab
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
In mm/slub.c (ffffffff81242fcb)
Location: mm/slub.c:1432
Inline: True
Inline callers:
  - mm/slub.c:new_slab
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
In mm/slub.c (ffffffff8126483f)
Location: mm/slub.c:1433
Inline: True
Inline callers:
  - mm/slub.c:new_slab
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
In mm/slub.c (ffffffff81278f65)
Location: mm/slub.c:1491
Inline: True
Inline callers:
  - mm/slub.c:new_slab
  - mm/slub.c:new_slab
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct page *alloc_slab_page(struct kmem_cache *s, gfp_t flags, int node, struct kmem_cache_order_objects oo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81293df0)
Location: mm/slub.c:1508
Inline: False
Direct callers:
  - mm/slub.c:allocate_slab
  - mm/slub.c:allocate_slab
```
**Symbols:**

```
ffffffff81293df0-ffffffff812940e6: alloc_slab_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct page *alloc_slab_page(struct kmem_cache *s, gfp_t flags, int node, struct kmem_cache_order_objects oo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812a3b60)
Location: mm/slub.c:1488
Inline: False
Direct callers:
  - mm/slub.c:allocate_slab
  - mm/slub.c:allocate_slab
```
**Symbols:**

```
ffffffff812a3b60-ffffffff812a3e56: alloc_slab_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct page *alloc_slab_page(struct kmem_cache *s, gfp_t flags, int node, struct kmem_cache_order_objects oo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812d96a0)
Location: mm/slub.c:1538
Inline: False
Direct callers:
  - mm/slub.c:allocate_slab
  - mm/slub.c:allocate_slab
```
**Symbols:**

```
ffffffff812d96a0-ffffffff812d9980: alloc_slab_page (STB_LOCAL)
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
In mm/slub.c (ffffffff812e4d23)
Location: mm/slub.c:1611
Inline: True
Inline callers:
  - mm/slub.c:allocate_slab
  - mm/slub.c:allocate_slab
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
In mm/slub.c (ffffffff812ec8e3)
Location: mm/slub.c:1639
Inline: True
Inline callers:
  - mm/slub.c:allocate_slab
  - mm/slub.c:allocate_slab
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81334ac0)
Location: mm/slub.c:1763
Inline: True
Inline callers:
  - mm/slub.c:allocate_slab
  - mm/slub.c:allocate_slab
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff813a6310)
Location: mm/slub.c:1816
Inline: True
Inline callers:
  - mm/slub.c:allocate_slab
  - mm/slub.c:allocate_slab
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81427850)
Location: mm/slub.c:1843
Inline: True
Inline callers:
  - mm/slub.c:allocate_slab
  - mm/slub.c:allocate_slab
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8145cdc0)
Location: mm/slub.c:1854
Inline: True
Inline callers:
  - mm/slub.c:allocate_slab
  - mm/slub.c:allocate_slab
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff814574d3)
Location: mm/slub.c:2183
Inline: True
Inline callers:
  - mm/slub.c:allocate_slab
  - mm/slub.c:allocate_slab
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
struct page *alloc_slab_page(struct kmem_cache *s, gfp_t flags, int node, struct kmem_cache_order_objects oo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffff800010345820)
Location: mm/slub.c:1488
Inline: False
Direct callers:
  - mm/slub.c:allocate_slab
  - mm/slub.c:allocate_slab
```
**Symbols:**

```
ffff800010345820-ffff800010345bcc: alloc_slab_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct page *alloc_slab_page(struct kmem_cache *s, gfp_t flags, int node, struct kmem_cache_order_objects oo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (c05495d4)
Location: mm/slub.c:1488
Inline: False
Direct callers:
  - mm/slub.c:allocate_slab
  - mm/slub.c:allocate_slab
```
**Symbols:**

```
c05495d4-c0549978: alloc_slab_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct page *alloc_slab_page(struct kmem_cache *s, gfp_t flags, int node, struct kmem_cache_order_objects oo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (c000000000421d30)
Location: mm/slub.c:1488
Inline: False
Direct callers:
  - mm/slub.c:allocate_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:allocate_slab
```
**Symbols:**

```
c000000000421d30-c000000000422288: alloc_slab_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct page *alloc_slab_page(struct kmem_cache *s, gfp_t flags, int node, struct kmem_cache_order_objects oo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffe00023803e)
Location: mm/slub.c:1488
Inline: False
Direct callers:
  - mm/slub.c:allocate_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:allocate_slab
```
**Symbols:**

```
ffffffe00023803e-ffffffe00023835c: alloc_slab_page (STB_LOCAL)
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
struct page *alloc_slab_page(struct kmem_cache *s, gfp_t flags, int node, struct kmem_cache_order_objects oo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8129c140)
Location: mm/slub.c:1488
Inline: False
Direct callers:
  - mm/slub.c:allocate_slab
  - mm/slub.c:allocate_slab
```
**Symbols:**

```
ffffffff8129c140-ffffffff8129c436: alloc_slab_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct page *alloc_slab_page(struct kmem_cache *s, gfp_t flags, int node, struct kmem_cache_order_objects oo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8128dd00)
Location: mm/slub.c:1488
Inline: False
Direct callers:
  - mm/slub.c:allocate_slab
  - mm/slub.c:allocate_slab
```
**Symbols:**

```
ffffffff8128dd00-ffffffff8128dfe7: alloc_slab_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct page *alloc_slab_page(struct kmem_cache *s, gfp_t flags, int node, struct kmem_cache_order_objects oo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81299f50)
Location: mm/slub.c:1488
Inline: False
Direct callers:
  - mm/slub.c:allocate_slab
  - mm/slub.c:allocate_slab
```
**Symbols:**

```
ffffffff81299f50-ffffffff8129a246: alloc_slab_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct page *alloc_slab_page(struct kmem_cache *s, gfp_t flags, int node, struct kmem_cache_order_objects oo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812a9d90)
Location: mm/slub.c:1488
Inline: False
Direct callers:
  - mm/slub.c:allocate_slab
  - mm/slub.c:allocate_slab
```
**Symbols:**

```
ffffffff812a9d90-ffffffff812aa125: alloc_slab_page (STB_LOCAL)
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
