# Function: <code>create_cache</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct kmem_cache *create_cache(const char *name, size_t object_size, size_t size, size_t align, long unsigned int flags, void (*ctor)(void *), struct mem_cgroup *memcg, struct kmem_cache *root_cache);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff811b2d00)
Location: mm/slab_common.c:319
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_create
  - mm/slab_common.c:memcg_create_kmem_cache
```
**Symbols:**

```
ffffffff811b2d00-ffffffff811b2ea0: create_cache (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision, Selective Inline ⚠️</summary>

```c
struct kmem_cache *create_cache(const char *name, size_t object_size, size_t size, size_t align, long unsigned int flags, void (*ctor)(void *), struct mem_cgroup *memcg, struct kmem_cache *root_cache);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff811cc770)
Location: mm/slab_common.c:324
Inline: False
Direct callers:
  - mm/slab_common.c:memcg_create_kmem_cache
  - mm/slab_common.c:kmem_cache_create
```
```
In mm/zsmalloc.c (ffffffff8122a70e)
Location: mm/zsmalloc.c:328
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_create_pool
```
**Symbols:**

```
ffffffff811cc770-ffffffff811cc910: create_cache (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision, Selective Inline ⚠️</summary>

```c
struct kmem_cache *create_cache(const char *name, size_t object_size, size_t size, size_t align, long unsigned int flags, void (*ctor)(void *), struct mem_cgroup *memcg, struct kmem_cache *root_cache);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff811dc840)
Location: mm/slab_common.c:324
Inline: False
Direct callers:
  - mm/slab_common.c:memcg_create_kmem_cache
  - mm/slab_common.c:kmem_cache_create
```
```
In mm/zsmalloc.c (ffffffff8123cc5e)
Location: mm/zsmalloc.c:328
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_create_pool
```
**Symbols:**

```
ffffffff811dc840-ffffffff811dc9e0: create_cache (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision, Selective Inline ⚠️</summary>

```c
struct kmem_cache *create_cache(const char *name, size_t object_size, size_t size, size_t align, long unsigned int flags, void (*ctor)(void *), struct mem_cgroup *memcg, struct kmem_cache *root_cache);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff811e7110)
Location: mm/slab_common.c:358
Inline: False
Direct callers:
  - mm/slab_common.c:memcg_create_kmem_cache
  - mm/slab_common.c:kmem_cache_create
```
```
In mm/zsmalloc.c (ffffffff812492d5)
Location: mm/zsmalloc.c:321
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_create_pool
```
**Symbols:**

```
ffffffff811e7110-ffffffff811e72d4: create_cache (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Selective Inline ⚠️</summary>

```c
struct kmem_cache *create_cache(const char *name, size_t object_size, size_t size, size_t align, slab_flags_t flags, void (*ctor)(void *), struct mem_cgroup *memcg, struct kmem_cache *root_cache);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff811fd360)
Location: mm/slab_common.c:367
Inline: False
Direct callers:
  - mm/slab_common.c:memcg_create_kmem_cache
  - mm/slab_common.c:kmem_cache_create
```
```
In mm/zsmalloc.c (ffffffff812696f5)
Location: mm/zsmalloc.c:322
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_create_pool
```
**Symbols:**

```
ffffffff811fd360-ffffffff811fd516: create_cache (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Selective Inline ⚠️</summary>

```c
struct kmem_cache *create_cache(const char *name, unsigned int object_size, unsigned int align, slab_flags_t flags, unsigned int useroffset, unsigned int usersize, void (*ctor)(void *), struct mem_cgroup *memcg, struct kmem_cache *root_cache);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff8121e660)
Location: mm/slab_common.c:363
Inline: False
Direct callers:
  - mm/slab_common.c:memcg_create_kmem_cache
  - mm/slab_common.c:kmem_cache_create_usercopy
```
```
In mm/zsmalloc.c (ffffffff8128d5f5)
Location: mm/zsmalloc.c:321
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_create_pool
```
**Symbols:**

```
ffffffff8121e660-ffffffff8121e835: create_cache (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Selective Inline ⚠️</summary>

```c
struct kmem_cache *create_cache(const char *name, unsigned int object_size, unsigned int align, slab_flags_t flags, unsigned int useroffset, unsigned int usersize, void (*ctor)(void *), struct mem_cgroup *memcg, struct kmem_cache *root_cache);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff81231640)
Location: mm/slab_common.c:363
Inline: False
Direct callers:
  - mm/slab_common.c:memcg_create_kmem_cache
  - mm/slab_common.c:kmem_cache_create_usercopy
```
```
In mm/zsmalloc.c (ffffffff812a2375)
Location: mm/zsmalloc.c:321
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_create_pool
```
**Symbols:**

```
ffffffff81231640-ffffffff81231815: create_cache (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
struct kmem_cache *create_cache(const char *name, unsigned int object_size, unsigned int align, slab_flags_t flags, unsigned int useroffset, unsigned int usersize, void (*ctor)(void *), struct mem_cgroup *memcg, struct kmem_cache *root_cache);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/slab_common.c (0)
Location: mm/slab_common.c:378
Inline: False
Direct callers:
  - mm/slab_common.c:memcg_create_kmem_cache
  - mm/slab_common.c:kmem_cache_create_usercopy
```
```
In mm/zsmalloc.c (ffffffff812bd4d3)
Location: mm/zsmalloc.c:327
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_create_pool
```
**Symbols:**

```
ffffffff81241a50-ffffffff81241c65: create_cache (STB_LOCAL)
ffffffff8124276c-ffffffff81242784: create_cache.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Selective Inline ⚠️</summary>

```c
struct kmem_cache *create_cache(const char *name, unsigned int object_size, unsigned int align, slab_flags_t flags, unsigned int useroffset, unsigned int usersize, void (*ctor)(void *), struct mem_cgroup *memcg, struct kmem_cache *root_cache);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff8124fef0)
Location: mm/slab_common.c:379
Inline: False
Direct callers:
  - mm/slab_common.c:memcg_create_kmem_cache
  - mm/slab_common.c:kmem_cache_create_usercopy
```
```
In mm/zsmalloc.c (ffffffff812cf3c3)
Location: mm/zsmalloc.c:327
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_create_pool
```
**Symbols:**

```
ffffffff8124fef0-ffffffff812500e7: create_cache (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Selective Inline ⚠️</summary>

```c
struct kmem_cache *create_cache(const char *name, unsigned int object_size, unsigned int align, slab_flags_t flags, unsigned int useroffset, unsigned int usersize, void (*ctor)(void *), struct mem_cgroup *memcg, struct kmem_cache *root_cache);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff8127e530)
Location: mm/slab_common.c:379
Inline: False
Direct callers:
  - mm/slab_common.c:memcg_create_kmem_cache
  - mm/slab_common.c:kmem_cache_create_usercopy
```
```
In mm/zsmalloc.c (ffffffff81305456)
Location: mm/zsmalloc.c:327
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_create_pool
```
**Symbols:**

```
ffffffff8127e530-ffffffff8127e727: create_cache (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff81287d2d)
Location: mm/slab_common.c:233
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_create_usercopy
```
```
In mm/zsmalloc.c (ffffffff813111b6)
Location: mm/zsmalloc.c:323
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_create_pool
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff8128cff1)
Location: mm/slab_common.c:241
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_create_usercopy
```
```
In mm/zsmalloc.c (ffffffff81317286)
Location: mm/zsmalloc.c:323
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_create_pool
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff812cce11)
Location: mm/slab_common.c:241
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_create_usercopy
```
```
In mm/zsmalloc.c (ffffffff81363770)
Location: mm/zsmalloc.c:323
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_create_pool
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff8132b623)
Location: mm/slab_common.c:233
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_create_usercopy
```
```
In mm/zsmalloc.c (ffffffff813e0444)
Location: mm/zsmalloc.c:325
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_create_pool
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff813a0aa3)
Location: mm/slab_common.c:207
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_create_usercopy
```
```
In mm/zsmalloc.c (ffffffff81467364)
Location: mm/zsmalloc.c:341
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_create_pool
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff813d3d55)
Location: mm/slab_common.c:209
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_create_usercopy
```
```
In mm/zsmalloc.c (ffffffff8149c94f)
Location: mm/zsmalloc.c:298
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_create_pool
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff813fe9f5)
Location: mm/slab_common.c:204
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_create_usercopy
```
```
In mm/zsmalloc.c (ffffffff814cc0ce)
Location: mm/zsmalloc.c:298
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_create_pool
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision, Selective Inline ⚠️</summary>

```c
struct kmem_cache *create_cache(const char *name, unsigned int object_size, unsigned int align, slab_flags_t flags, unsigned int useroffset, unsigned int usersize, void (*ctor)(void *), struct mem_cgroup *memcg, struct kmem_cache *root_cache);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffff8000102e6e68)
Location: mm/slab_common.c:379
Inline: False
Direct callers:
  - mm/slab_common.c:memcg_create_kmem_cache
  - mm/slab_common.c:kmem_cache_create_usercopy
```
```
In mm/zsmalloc.c (ffff800010374154)
Location: mm/zsmalloc.c:327
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_create_pool
```
**Symbols:**

```
ffff8000102e6e68-ffff8000102e7038: create_cache (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision, Selective Inline ⚠️</summary>

```c
struct kmem_cache *create_cache(const char *name, unsigned int object_size, unsigned int align, slab_flags_t flags, unsigned int useroffset, unsigned int usersize, void (*ctor)(void *), struct mem_cgroup *memcg, struct kmem_cache *root_cache);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (c050b054)
Location: mm/slab_common.c:379
Inline: False
Direct callers:
  - mm/slab_common.c:memcg_create_kmem_cache
  - mm/slab_common.c:kmem_cache_create_usercopy
```
```
In mm/zsmalloc.c (c056053c)
Location: mm/zsmalloc.c:327
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_create_pool
```
**Symbols:**

```
c050b054-c050b20c: create_cache (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision, Selective Inline ⚠️</summary>

```c
struct kmem_cache *create_cache(const char *name, unsigned int object_size, unsigned int align, slab_flags_t flags, unsigned int useroffset, unsigned int usersize, void (*ctor)(void *), struct mem_cgroup *memcg, struct kmem_cache *root_cache);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (c0000000003a8920)
Location: mm/slab_common.c:379
Inline: False
Direct callers:
  - mm/slab_common.c:memcg_create_kmem_cache
  - mm/slab_common.c:kmem_cache_create_usercopy
```
```
In mm/zsmalloc.c (c000000000466f10)
Location: mm/zsmalloc.c:327
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_create_pool
```
**Symbols:**

```
c0000000003a8920-c0000000003a8b88: create_cache (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision, Selective Inline ⚠️</summary>

```c
struct kmem_cache *create_cache(const char *name, unsigned int object_size, unsigned int align, slab_flags_t flags, unsigned int useroffset, unsigned int usersize, void (*ctor)(void *), struct mem_cgroup *memcg, struct kmem_cache *root_cache);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffe0001fcb9c)
Location: mm/slab_common.c:379
Inline: False
Direct callers:
  - mm/slab_common.c:memcg_create_kmem_cache
  - mm/slab_common.c:kmem_cache_create_usercopy
```
```
In mm/zsmalloc.c (ffffffe00024d2d4)
Location: mm/zsmalloc.c:327
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_create_pool
```
**Symbols:**

```
ffffffe0001fcb9c-ffffffe0001fcd0c: create_cache (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision, Selective Inline ⚠️</summary>

```c
struct kmem_cache *create_cache(const char *name, unsigned int object_size, unsigned int align, slab_flags_t flags, unsigned int useroffset, unsigned int usersize, void (*ctor)(void *), struct mem_cgroup *memcg, struct kmem_cache *root_cache);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff81248540)
Location: mm/slab_common.c:379
Inline: False
Direct callers:
  - mm/slab_common.c:memcg_create_kmem_cache
  - mm/slab_common.c:kmem_cache_create_usercopy
```
```
In mm/zsmalloc.c (ffffffff812c79a3)
Location: mm/zsmalloc.c:327
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_create_pool
```
**Symbols:**

```
ffffffff81248540-ffffffff81248737: create_cache (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Selective Inline ⚠️</summary>

```c
struct kmem_cache *create_cache(const char *name, unsigned int object_size, unsigned int align, slab_flags_t flags, unsigned int useroffset, unsigned int usersize, void (*ctor)(void *), struct mem_cgroup *memcg, struct kmem_cache *root_cache);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff8123b4f0)
Location: mm/slab_common.c:379
Inline: False
Direct callers:
  - mm/slab_common.c:memcg_create_kmem_cache
  - mm/slab_common.c:kmem_cache_create_usercopy
```
```
In mm/zsmalloc.c (ffffffff812b89e3)
Location: mm/zsmalloc.c:327
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_create_pool
```
**Symbols:**

```
ffffffff8123b4f0-ffffffff8123b6e7: create_cache (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Selective Inline ⚠️</summary>

```c
struct kmem_cache *create_cache(const char *name, unsigned int object_size, unsigned int align, slab_flags_t flags, unsigned int useroffset, unsigned int usersize, void (*ctor)(void *), struct mem_cgroup *memcg, struct kmem_cache *root_cache);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff812462e0)
Location: mm/slab_common.c:379
Inline: False
Direct callers:
  - mm/slab_common.c:memcg_create_kmem_cache
  - mm/slab_common.c:kmem_cache_create_usercopy
```
```
In mm/zsmalloc.c (ffffffff812c57b3)
Location: mm/zsmalloc.c:327
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_create_pool
```
**Symbols:**

```
ffffffff812462e0-ffffffff812464d7: create_cache (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Selective Inline ⚠️</summary>

```c
struct kmem_cache *create_cache(const char *name, unsigned int object_size, unsigned int align, slab_flags_t flags, unsigned int useroffset, unsigned int usersize, void (*ctor)(void *), struct mem_cgroup *memcg, struct kmem_cache *root_cache);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff81255af0)
Location: mm/slab_common.c:379
Inline: False
Direct callers:
  - mm/slab_common.c:memcg_create_kmem_cache
  - mm/slab_common.c:kmem_cache_create_usercopy
```
```
In mm/zsmalloc.c (ffffffff812d63d3)
Location: mm/zsmalloc.c:327
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_create_pool
```
**Symbols:**

```
ffffffff81255af0-ffffffff81255ce7: create_cache (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>long unsigned int flags</code> ➡️ <code>slab_flags_t flags</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int useroffset</code>
</li>
<li>
<b>Param added. </b>
<code>unsigned int usersize</code>
</li>
<li>
<b>Param removed. </b>
<code>size_t size</code>
</li>
<li>
<b>Param reordered. </b>
<code>name, object_size, size, align, flags, ctor, memcg, root_cache</code> ➡️ <code>name, object_size, align, flags, useroffset, usersize, ctor, memcg, root_cache</code>
</li>
<li>
<b>Param type changed. </b>
<code>size_t object_size</code> ➡️ <code>unsigned int object_size</code>
</li>
<li>
<b>Param type changed. </b>
<code>size_t align</code> ➡️ <code>unsigned int align</code>
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
