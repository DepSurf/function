# Function: <code>memcg_kmem_put_cache</code>

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
In mm/slub.c (ffffffff811eadd3)
Location: include/linux/memcontrol.h:825
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:__kmalloc
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_node_track_caller
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void memcg_kmem_put_cache(struct kmem_cache *cachep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812236e0)
Location: mm/memcontrol.c:2299
Inline: False
Direct callers:
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
```
**Symbols:**

```
ffffffff812236e0-ffffffff81223720: memcg_kmem_put_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void memcg_kmem_put_cache(struct kmem_cache *cachep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81235bd0)
Location: mm/memcontrol.c:2272
Inline: False
Direct callers:
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
```
**Symbols:**

```
ffffffff81235bd0-ffffffff81235c10: memcg_kmem_put_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void memcg_kmem_put_cache(struct kmem_cache *cachep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81241620)
Location: mm/memcontrol.c:2281
Inline: False
Direct callers:
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
```
**Symbols:**

```
ffffffff81241620-ffffffff81241661: memcg_kmem_put_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void memcg_kmem_put_cache(struct kmem_cache *cachep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81261360)
Location: mm/memcontrol.c:2308
Inline: False
Direct callers:
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
```
**Symbols:**

```
ffffffff81261360-ffffffff812613a8: memcg_kmem_put_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void memcg_kmem_put_cache(struct kmem_cache *cachep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81285370)
Location: mm/memcontrol.c:2295
Inline: False
Direct callers:
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
```
**Symbols:**

```
ffffffff81285370-ffffffff812853b7: memcg_kmem_put_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void memcg_kmem_put_cache(struct kmem_cache *cachep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8129a1f0)
Location: mm/memcontrol.c:2569
Inline: False
Direct callers:
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
```
**Symbols:**

```
ffffffff8129a1f0-ffffffff8129a237: memcg_kmem_put_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void memcg_kmem_put_cache(struct kmem_cache *cachep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812b5490)
Location: mm/memcontrol.c:2796
Inline: False
Direct callers:
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
```
**Symbols:**

```
ffffffff812b5490-ffffffff812b54d7: memcg_kmem_put_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void memcg_kmem_put_cache(struct kmem_cache *cachep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812c7130)
Location: mm/memcontrol.c:2995
Inline: False
Direct callers:
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
```
**Symbols:**

```
ffffffff812c7130-ffffffff812c7177: memcg_kmem_put_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void memcg_kmem_put_cache(struct kmem_cache *cachep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812fcb80)
Location: mm/memcontrol.c:2882
Inline: False
Direct callers:
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
```
**Symbols:**

```
ffffffff812fcb80-ffffffff812fcbc7: memcg_kmem_put_cache (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void memcg_kmem_put_cache(struct kmem_cache *cachep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffff800010369f30)
Location: mm/memcontrol.c:2995
Inline: False
Direct callers:
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
```
**Symbols:**

```
ffff800010369f30-ffff800010369f68: memcg_kmem_put_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void memcg_kmem_put_cache(struct kmem_cache *cachep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c055b2e8)
Location: mm/memcontrol.c:2995
Inline: False
Direct callers:
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
```
**Symbols:**

```
c055b2e8-c055b370: memcg_kmem_put_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void memcg_kmem_put_cache(struct kmem_cache *cachep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c000000000458bd0)
Location: mm/memcontrol.c:2995
Inline: False
Direct callers:
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
```
**Symbols:**

```
c000000000458bd0-c000000000458c94: memcg_kmem_put_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void memcg_kmem_put_cache(struct kmem_cache *cachep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffe000247790)
Location: mm/memcontrol.c:2995
Inline: False
Direct callers:
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
```
**Symbols:**

```
ffffffe000247790-ffffffe0002477fc: memcg_kmem_put_cache (STB_GLOBAL)
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
void memcg_kmem_put_cache(struct kmem_cache *cachep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812bf710)
Location: mm/memcontrol.c:2995
Inline: False
Direct callers:
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
```
**Symbols:**

```
ffffffff812bf710-ffffffff812bf757: memcg_kmem_put_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void memcg_kmem_put_cache(struct kmem_cache *cachep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812b07f0)
Location: mm/memcontrol.c:2995
Inline: False
Direct callers:
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
```
**Symbols:**

```
ffffffff812b07f0-ffffffff812b0837: memcg_kmem_put_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void memcg_kmem_put_cache(struct kmem_cache *cachep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812bd520)
Location: mm/memcontrol.c:2995
Inline: False
Direct callers:
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
```
**Symbols:**

```
ffffffff812bd520-ffffffff812bd567: memcg_kmem_put_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void memcg_kmem_put_cache(struct kmem_cache *cachep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812cddf0)
Location: mm/memcontrol.c:2995
Inline: False
Direct callers:
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
```
**Symbols:**

```
ffffffff812cddf0-ffffffff812cde4f: memcg_kmem_put_cache (STB_GLOBAL)
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
