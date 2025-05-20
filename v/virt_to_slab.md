# Function: <code>virt_to_slab</code>

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
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff8132bccb)
Location: mm/slab.h:173
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_dump_obj
```
```
In mm/slub.c (ffffffff813ac2ae)
Location: mm/slab.h:173
Inline: True
Inline callers:
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/kfence/core.c (ffffffff813aec83)
Location: mm/slab.h:173
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_guarded_alloc
  - mm/kfence/core.c:kfence_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff813a145b)
Location: mm/slab.h:183
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_dump_obj
```
```
In mm/slub.c (ffffffff8142c49e)
Location: mm/slab.h:183
Inline: True
Inline callers:
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:__kmem_cache_free
  - mm/slub.c:cache_from_obj
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/kfence/core.c (ffffffff8142f1d4)
Location: mm/slab.h:183
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_guarded_alloc
  - mm/kfence/core.c:kfence_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff813d46cb)
Location: mm/slab.h:211
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_dump_obj
```
```
In mm/slub.c (ffffffff81461a4e)
Location: mm/slab.h:211
Inline: True
Inline callers:
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:__kmem_cache_free
  - mm/slub.c:cache_from_obj
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/kfence/core.c (ffffffff81464edf)
Location: mm/slab.h:211
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_guarded_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff813fe2bc)
Location: mm/slab.h:202
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_dump_obj
```
```
In mm/slub.c (ffffffff8145dced)
Location: mm/slab.h:202
Inline: True
Inline callers:
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:__memcg_slab_post_alloc_hook
```
```
In mm/kfence/core.c (ffffffff81493b26)
Location: mm/slab.h:202
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_guarded_alloc
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
