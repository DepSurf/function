# Function: <code>atomic_long_set_release</code>

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
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffff800010349598)
Location: include/asm-generic/atomic-long.h:44
Inline: True
Inline callers:
  - mm/slub.c:validate_slab_slab
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:free_debug_processing
```
```
In fs/dcache.c (ffff8000103a5720)
Location: include/asm-generic/atomic-long.h:44
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
```
```
In fs/mbcache.c (ffff80001042533c)
Location: include/asm-generic/atomic-long.h:44
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
  - fs/mbcache.c:mb_cache_entry_create
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (c054d5a4)
Location: include/asm-generic/atomic-long.h:538
Inline: True
Inline callers:
  - mm/slub.c:validate_slab_slab
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
  - mm/slub.c:unfreeze_partials
  - mm/slub.c:unfreeze_partials
  - mm/slub.c:deactivate_slab
  - mm/slub.c:deactivate_slab
  - mm/slub.c:deactivate_slab
  - mm/slub.c:deactivate_slab
  - mm/slub.c:free_debug_processing
```
```
In fs/dcache.c (c0588f38)
Location: include/asm-generic/atomic-long.h:538
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
```
```
In fs/mbcache.c (c05edee8)
Location: include/asm-generic/atomic-long.h:538
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
  - fs/mbcache.c:mb_cache_entry_create
```
</details>
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
