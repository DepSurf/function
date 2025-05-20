# Function: <code>__kmem_cache_alloc_node</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
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
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *__kmem_cache_alloc_node(struct kmem_cache *s, gfp_t gfpflags, int node, size_t orig_size, long unsigned int caller);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8142d250)
Location: mm/slub.c:3487
Inline: False
Direct callers:
  - mm/slab_common.c:kmalloc_node_trace
  - mm/slab_common.c:kmalloc_trace
  - mm/slab_common.c:__kmalloc_node_track_caller
  - mm/slab_common.c:__kmalloc
  - mm/slab_common.c:__kmalloc_node
```
**Symbols:**

```
ffffffff8142d250-ffffffff8142d587: __kmem_cache_alloc_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *__kmem_cache_alloc_node(struct kmem_cache *s, gfp_t gfpflags, int node, size_t orig_size, long unsigned int caller);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81462850)
Location: mm/slub.c:3505
Inline: False
Direct callers:
  - mm/slab_common.c:kmalloc_node_trace
  - mm/slab_common.c:kmalloc_trace
  - mm/slab_common.c:__kmalloc_node_track_caller
  - mm/slab_common.c:__kmalloc
  - mm/slab_common.c:__kmalloc_node
```
**Symbols:**

```
ffffffff81462850-ffffffff81462baf: __kmem_cache_alloc_node (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
</ul>
