# Function: <code>memcg_slab_post_alloc_hook</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void memcg_slab_post_alloc_hook(struct kmem_cache *s, struct obj_cgroup *objcg, gfp_t flags, size_t size, void **p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812e4140)
Location: mm/slab.h:302
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
ffffffff812e4140-ffffffff812e4368: memcg_slab_post_alloc_hook (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void memcg_slab_post_alloc_hook(struct kmem_cache *s, struct obj_cgroup *objcg, gfp_t flags, size_t size, void **p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812ec370)
Location: mm/slab.h:300
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
ffffffff812ec370-ffffffff812ec59f: memcg_slab_post_alloc_hook (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void memcg_slab_post_alloc_hook(struct kmem_cache *s, struct obj_cgroup *objcg, gfp_t flags, size_t size, void **p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slab.h:296
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
ffffffff813342c0-ffffffff813344c3: memcg_slab_post_alloc_hook (STB_LOCAL)
ffffffff81cc10fa-ffffffff81cc114b: memcg_slab_post_alloc_hook.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void memcg_slab_post_alloc_hook(struct kmem_cache *s, struct obj_cgroup *objcg, gfp_t flags, size_t size, void **p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slab.h:515
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
  - mm/slub.c:kmem_cache_alloc_lru
  - mm/slub.c:kmem_cache_alloc
```
**Symbols:**

```
ffffffff813a5de0-ffffffff813a605c: memcg_slab_post_alloc_hook (STB_LOCAL)
ffffffff81e7369e-ffffffff81e736ea: memcg_slab_post_alloc_hook.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void memcg_slab_post_alloc_hook(struct kmem_cache *s, struct obj_cgroup *objcg, gfp_t flags, size_t size, void **p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slab.h:521
Inline: False
Direct callers:
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:__kmem_cache_alloc_bulk
  - mm/slub.c:__kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:__kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_lru
  - mm/slub.c:kmem_cache_alloc
```
**Symbols:**

```
ffffffff81426fa0-ffffffff8142721c: memcg_slab_post_alloc_hook (STB_LOCAL)
ffffffff8206760e-ffffffff8206765a: memcg_slab_post_alloc_hook.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void memcg_slab_post_alloc_hook(struct kmem_cache *s, struct obj_cgroup *objcg, gfp_t flags, size_t size, void **p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slab.h:513
Inline: False
Direct callers:
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:__kmem_cache_alloc_bulk
  - mm/slub.c:__kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:__kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_lru
  - mm/slub.c:kmem_cache_alloc
```
**Symbols:**

```
ffffffff8145bf40-ffffffff8145c1bc: memcg_slab_post_alloc_hook (STB_LOCAL)
ffffffff820e6eef-ffffffff820e6f3b: memcg_slab_post_alloc_hook.cold (STB_LOCAL)
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
In mm/slub.c (ffffffff8145e80b)
Location: mm/slub.c:1987
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_alloc_bulk
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
</ul>
