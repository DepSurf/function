# Function: <code>__slab_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void *__slab_alloc(struct kmem_cache *s, gfp_t gfpflags, int node, long unsigned int addr, struct kmem_cache_cpu *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff811eabb0)
Location: mm/slub.c:2451
Inline: False
Direct callers:
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:__kmalloc
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_node_track_caller
```
**Symbols:**

```
ffffffff811eabb0-ffffffff811eabe3: __slab_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void *__slab_alloc(struct kmem_cache *s, gfp_t gfpflags, int node, long unsigned int addr, struct kmem_cache_cpu *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8120a210)
Location: mm/slub.c:2580
Inline: False
Direct callers:
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
```
**Symbols:**

```
ffffffff8120a210-ffffffff8120a243: __slab_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *__slab_alloc(struct kmem_cache *s, gfp_t gfpflags, int node, long unsigned int addr, struct kmem_cache_cpu *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8121c280)
Location: mm/slub.c:2602
Inline: False
Direct callers:
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
```
**Symbols:**

```
ffffffff8121c280-ffffffff8121c2b3: __slab_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *__slab_alloc(struct kmem_cache *s, gfp_t gfpflags, int node, long unsigned int addr, struct kmem_cache_cpu *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81227d60)
Location: mm/slub.c:2599
Inline: False
Direct callers:
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
```
**Symbols:**

```
ffffffff81227d60-ffffffff81227d93: __slab_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *__slab_alloc(struct kmem_cache *s, gfp_t gfpflags, int node, long unsigned int addr, struct kmem_cache_cpu *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81243ea0)
Location: mm/slub.c:2612
Inline: False
Direct callers:
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
```
**Symbols:**

```
ffffffff81243ea0-ffffffff81243ed3: __slab_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *__slab_alloc(struct kmem_cache *s, gfp_t gfpflags, int node, long unsigned int addr, struct kmem_cache_cpu *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812665c0)
Location: mm/slub.c:2595
Inline: False
Direct callers:
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
```
**Symbols:**

```
ffffffff812665c0-ffffffff812665f3: __slab_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *__slab_alloc(struct kmem_cache *s, gfp_t gfpflags, int node, long unsigned int addr, struct kmem_cache_cpu *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8127b2f0)
Location: mm/slub.c:2645
Inline: False
Direct callers:
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
```
**Symbols:**

```
ffffffff8127b2f0-ffffffff8127b323: __slab_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *__slab_alloc(struct kmem_cache *s, gfp_t gfpflags, int node, long unsigned int addr, struct kmem_cache_cpu *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81296c90)
Location: mm/slub.c:2651
Inline: False
Direct callers:
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
```
**Symbols:**

```
ffffffff81296c90-ffffffff81296cc3: __slab_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *__slab_alloc(struct kmem_cache *s, gfp_t gfpflags, int node, long unsigned int addr, struct kmem_cache_cpu *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812a6a90)
Location: mm/slub.c:2640
Inline: False
Direct callers:
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
```
**Symbols:**

```
ffffffff812a6a90-ffffffff812a6ac3: __slab_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *__slab_alloc(struct kmem_cache *s, gfp_t gfpflags, int node, long unsigned int addr, struct kmem_cache_cpu *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812db920)
Location: mm/slub.c:2698
Inline: False
Direct callers:
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
```
**Symbols:**

```
ffffffff812db920-ffffffff812db956: __slab_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *__slab_alloc(struct kmem_cache *s, gfp_t gfpflags, int node, long unsigned int addr, struct kmem_cache_cpu *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812e7e30)
Location: mm/slub.c:2765
Inline: False
Direct callers:
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
```
**Symbols:**

```
ffffffff812e7e30-ffffffff812e7e66: __slab_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void *__slab_alloc(struct kmem_cache *s, gfp_t gfpflags, int node, long unsigned int addr, struct kmem_cache_cpu *c);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812f02ca)
Location: mm/slub.c:2782
Inline: True
Inline callers:
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
Direct callers:
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc
```
**Symbols:**

```
ffffffff812ef5d0-ffffffff812ef611: __slab_alloc (STB_LOCAL)
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
In mm/slub.c (ffffffff81338cb3)
Location: mm/slub.c:3074
Inline: True
Inline callers:
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
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
In mm/slub.c (ffffffff813aa864)
Location: mm/slub.c:3104
Inline: True
Inline callers:
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc_lru
  - mm/slub.c:kmem_cache_alloc
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
In mm/slub.c (ffffffff8142ac7b)
Location: mm/slub.c:3278
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:__kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_lru
  - mm/slub.c:kmem_cache_alloc
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
In mm/slub.c (ffffffff81460193)
Location: mm/slub.c:3300
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:__kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_lru
  - mm/slub.c:kmem_cache_alloc
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
In mm/slub.c (ffffffff8145b822)
Location: mm/slub.c:3611
Inline: True
Inline callers:
  - mm/slub.c:kmalloc_node_trace
  - mm/slub.c:kmalloc_trace
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_lru
  - mm/slub.c:kmem_cache_alloc
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
void *__slab_alloc(struct kmem_cache *s, gfp_t gfpflags, int node, long unsigned int addr, struct kmem_cache_cpu *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffff800010347d78)
Location: mm/slub.c:2640
Inline: False
Direct callers:
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
```
**Symbols:**

```
ffff800010347d78-ffff800010347df4: __slab_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (c055035c)
Location: mm/slub.c:2640
Inline: True
Inline callers:
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void *__slab_alloc(struct kmem_cache *s, gfp_t gfpflags, int node, long unsigned int addr, struct kmem_cache_cpu *c);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slub.c (c00000000042c5a8)
Location: mm/slub.c:2640
Inline: True
Inline callers:
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_track_caller
Direct callers:
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
```
**Symbols:**

```
c000000000426150-c0000000004261b0: __slab_alloc (STB_LOCAL)
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
In mm/slub.c (ffffffe00023d844)
Location: mm/slub.c:2640
Inline: True
Inline callers:
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
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
void *__slab_alloc(struct kmem_cache *s, gfp_t gfpflags, int node, long unsigned int addr, struct kmem_cache_cpu *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8129f070)
Location: mm/slub.c:2640
Inline: False
Direct callers:
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
```
**Symbols:**

```
ffffffff8129f070-ffffffff8129f0a3: __slab_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void *__slab_alloc(struct kmem_cache *s, gfp_t gfpflags, int node, long unsigned int addr, struct kmem_cache_cpu *c);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81294acd)
Location: mm/slub.c:2640
Inline: True
Inline callers:
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_track_caller
Direct callers:
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
```
**Symbols:**

```
ffffffff81290bb0-ffffffff81290bc7: __slab_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *__slab_alloc(struct kmem_cache *s, gfp_t gfpflags, int node, long unsigned int addr, struct kmem_cache_cpu *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8129ce80)
Location: mm/slub.c:2640
Inline: False
Direct callers:
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
```
**Symbols:**

```
ffffffff8129ce80-ffffffff8129ceb3: __slab_alloc (STB_LOCAL)
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
In mm/slub.c (ffffffff812acef0)
Location: mm/slub.c:2640
Inline: True
Direct callers:
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
```
**Symbols:**

```
ffffffff812acef0-ffffffff812acf2e: __slab_alloc.isra.0 (STB_LOCAL)
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
</ul>
