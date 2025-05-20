# Function: <code>folio_test_slab</code>

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
In mm/util.c (ffffffff8131d535)
Location: include/linux/page-flags.h:506
Inline: True
```
```
In mm/slab_common.c (ffffffff8132bd07)
Location: include/linux/page-flags.h:506
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_dump_obj
```
```
In mm/slub.c (ffffffff813a7d0e)
Location: include/linux/page-flags.h:506
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:__ksize
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
  - mm/slub.c:check_slab
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/kfence/core.c (ffffffff813aeccb)
Location: include/linux/page-flags.h:506
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_guarded_alloc
  - mm/kfence/core.c:kfence_init
```
```
In mm/memcontrol.c (ffffffff813d3494)
Location: include/linux/page-flags.h:506
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_from_obj
```
```
In mm/usercopy.c (ffffffff813e6c8e)
Location: include/linux/page-flags.h:506
Inline: True
Inline callers:
  - mm/usercopy.c:check_heap_object
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
In mm/util.c (ffffffff813911e5)
Location: include/linux/page-flags.h:485
Inline: True
```
```
In mm/slab_common.c (ffffffff813a23ed)
Location: include/linux/page-flags.h:485
Inline: True
Inline callers:
  - mm/slab_common.c:__ksize
  - mm/slab_common.c:kfree
  - mm/slab_common.c:kmem_dump_obj
```
```
In mm/slub.c (ffffffff8142c4dc)
Location: include/linux/page-flags.h:485
Inline: True
Inline callers:
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:__kmem_cache_free
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
  - mm/slub.c:check_slab
  - mm/slub.c:cache_from_obj
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/kfence/core.c (ffffffff8142f21c)
Location: include/linux/page-flags.h:485
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_guarded_alloc
  - mm/kfence/core.c:kfence_init
```
```
In mm/memcontrol.c (ffffffff81458e74)
Location: include/linux/page-flags.h:485
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_from_slab_obj
  - mm/memcontrol.c:mem_cgroup_from_obj
```
```
In mm/usercopy.c (ffffffff8146e865)
Location: include/linux/page-flags.h:485
Inline: True
Inline callers:
  - mm/usercopy.c:check_heap_object
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
In mm/util.c (ffffffff813c3ba5)
Location: include/linux/page-flags.h:479
Inline: True
```
```
In mm/slab_common.c (ffffffff813d58da)
Location: include/linux/page-flags.h:479
Inline: True
Inline callers:
  - mm/slab_common.c:__ksize
  - mm/slab_common.c:kfree
  - mm/slab_common.c:kmem_dump_obj
```
```
In mm/gup.c (ffffffff813e26e8)
Location: include/linux/page-flags.h:479
Inline: True
Inline callers:
  - mm/gup.c:folio_fast_pin_allowed
```
```
In mm/slub.c (ffffffff81461a8c)
Location: include/linux/page-flags.h:479
Inline: True
Inline callers:
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:__kmem_cache_free
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
  - mm/slub.c:check_slab
  - mm/slub.c:cache_from_obj
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/kfence/core.c (ffffffff81464f27)
Location: include/linux/page-flags.h:479
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_guarded_alloc
```
```
In mm/migrate.c (ffffffff81469154)
Location: include/linux/page-flags.h:479
Inline: True
Inline callers:
  - mm/migrate.c:isolate_movable_page
  - mm/migrate.c:isolate_movable_page
```
```
In mm/memcontrol.c (ffffffff8148eb04)
Location: include/linux/page-flags.h:479
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_from_slab_obj
  - mm/memcontrol.c:mem_cgroup_from_obj
```
```
In mm/memory-failure.c (ffffffff81496c17)
Location: include/linux/page-flags.h:479
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
```
```
In mm/usercopy.c (ffffffff814a2ffd)
Location: include/linux/page-flags.h:479
Inline: True
Inline callers:
  - mm/usercopy.c:check_heap_object
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
In mm/util.c (ffffffff813ee755)
Location: include/linux/page-flags.h:481
Inline: True
```
```
In mm/slab_common.c (ffffffff813ff58d)
Location: include/linux/page-flags.h:481
Inline: True
Inline callers:
  - mm/slab_common.c:__ksize
  - mm/slab_common.c:kmem_dump_obj
```
```
In mm/gup.c (ffffffff8140cf08)
Location: include/linux/page-flags.h:481
Inline: True
```
```
In mm/memory.c (ffffffff8141cde0)
Location: include/linux/page-flags.h:481
Inline: True
Inline callers:
  - mm/memory.c:vm_insert_page
  - mm/memory.c:vm_insert_pages
```
```
In mm/slub.c (ffffffff8145dd2b)
Location: include/linux/page-flags.h:481
Inline: True
Inline callers:
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:kfree
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:free_debug_processing
  - mm/slub.c:__memcg_slab_post_alloc_hook
  - mm/slub.c:alloc_debug_processing
  - mm/slub.c:check_slab
```
```
In mm/kfence/core.c (ffffffff81493b6e)
Location: include/linux/page-flags.h:481
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_guarded_alloc
```
```
In mm/migrate.c (ffffffff81498074)
Location: include/linux/page-flags.h:481
Inline: True
Inline callers:
  - mm/migrate.c:isolate_movable_page
  - mm/migrate.c:isolate_movable_page
```
```
In mm/memcontrol.c (ffffffff814be4b4)
Location: include/linux/page-flags.h:481
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_from_slab_obj
  - mm/memcontrol.c:mem_cgroup_from_obj
```
```
In mm/memory-failure.c (ffffffff814c69e5)
Location: include/linux/page-flags.h:481
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
```
```
In mm/usercopy.c (ffffffff814d3e91)
Location: include/linux/page-flags.h:481
Inline: True
Inline callers:
  - mm/usercopy.c:check_heap_object
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
