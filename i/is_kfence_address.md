# Function: <code>is_kfence_address</code>

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
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (0)
Location: include/linux/kfence.h:206
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/kfence.h:206
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8133b5b5)
Location: include/linux/kfence.h:49
Inline: True
Inline callers:
  - mm/slub.c:__check_heap_object
  - mm/slub.c:kmem_obj_info
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:__slab_free
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/kfence/core.c (ffffffff8133c97f)
Location: include/linux/kfence.h:49
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_handle_page_fault
  - mm/kfence/core.c:kfence_handle_page_fault
  - mm/kfence/core.c:kfence_handle_page_fault
  - mm/kfence/core.c:kfence_handle_page_fault
  - mm/kfence/core.c:__kfence_free
  - mm/kfence/core.c:kfence_object_start
  - mm/kfence/core.c:kfence_ksize
  - mm/kfence/core.c:kfence_init_pool
  - mm/kfence/core.c:kfence_guarded_free
  - mm/kfence/core.c:kfence_guarded_free
```
```
In mm/memcontrol.c (ffffffff8135a0fd)
Location: include/linux/kfence.h:49
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_from_obj
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff81e6cda4)
Location: include/linux/kfence.h:51
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_dump_obj
```
```
In mm/slub.c (ffffffff813a7d2d)
Location: include/linux/kfence.h:51
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:__check_heap_object
  - mm/slub.c:__kmem_obj_info
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:__slab_free
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/kfence/core.c (ffffffff813afd9e)
Location: include/linux/kfence.h:51
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_handle_page_fault
  - mm/kfence/core.c:kfence_handle_page_fault
  - mm/kfence/core.c:kfence_handle_page_fault
  - mm/kfence/core.c:kfence_handle_page_fault
  - mm/kfence/core.c:__kfence_free
  - mm/kfence/core.c:kfence_object_start
  - mm/kfence/core.c:kfence_ksize
  - mm/kfence/core.c:kfence_check_all_canary
  - mm/kfence/core.c:kfence_check_all_canary
  - mm/kfence/core.c:kfence_init_pool
  - mm/kfence/core.c:kfence_guarded_free
  - mm/kfence/core.c:kfence_guarded_free
```
```
In mm/kfence/report.c (ffffffff813b0755)
Location: include/linux/kfence.h:51
Inline: True
Inline callers:
  - mm/kfence/report.c:__kfence_obj_info
```
```
In mm/memcontrol.c (ffffffff813d34cf)
Location: include/linux/kfence.h:51
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_from_obj
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
In mm/slab_common.c (ffffffff813a14ed)
Location: include/linux/kfence.h:51
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_dump_obj
```
```
In mm/slub.c (ffffffff8142e095)
Location: include/linux/kfence.h:51
Inline: True
Inline callers:
  - mm/slub.c:__check_heap_object
  - mm/slub.c:__kmem_obj_info
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:__kmem_cache_free
  - mm/slub.c:__kmem_cache_free
  - mm/slub.c:__slab_free
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/kfence/core.c (ffffffff8143039e)
Location: include/linux/kfence.h:51
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_handle_page_fault
  - mm/kfence/core.c:kfence_handle_page_fault
  - mm/kfence/core.c:kfence_handle_page_fault
  - mm/kfence/core.c:kfence_handle_page_fault
  - mm/kfence/core.c:__kfence_free
  - mm/kfence/core.c:kfence_object_start
  - mm/kfence/core.c:kfence_ksize
  - mm/kfence/core.c:kfence_check_all_canary
  - mm/kfence/core.c:kfence_check_all_canary
  - mm/kfence/core.c:kfence_init_pool
  - mm/kfence/core.c:kfence_guarded_free
  - mm/kfence/core.c:kfence_guarded_free
```
```
In mm/kfence/report.c (ffffffff814312b5)
Location: include/linux/kfence.h:51
Inline: True
Inline callers:
  - mm/kfence/report.c:__kfence_obj_info
```
```
In mm/memcontrol.c (ffffffff81458eb2)
Location: include/linux/kfence.h:51
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_from_slab_obj
  - mm/memcontrol.c:mem_cgroup_from_obj
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
In mm/slab_common.c (ffffffff813d475d)
Location: include/linux/kfence.h:51
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_dump_obj
```
```
In mm/slub.c (ffffffff814637d5)
Location: include/linux/kfence.h:51
Inline: True
Inline callers:
  - mm/slub.c:__check_heap_object
  - mm/slub.c:__kmem_obj_info
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:__kmem_cache_free
  - mm/slub.c:__kmem_cache_free
  - mm/slub.c:__slab_free
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/kfence/core.c (ffffffff81465d17)
Location: include/linux/kfence.h:51
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_handle_page_fault
  - mm/kfence/core.c:kfence_handle_page_fault
  - mm/kfence/core.c:kfence_handle_page_fault
  - mm/kfence/core.c:kfence_handle_page_fault
  - mm/kfence/core.c:__kfence_free
  - mm/kfence/core.c:kfence_object_start
  - mm/kfence/core.c:kfence_ksize
  - mm/kfence/core.c:kfence_init_pool
  - mm/kfence/core.c:check_canary
  - mm/kfence/core.c:check_canary
  - mm/kfence/core.c:check_canary
```
```
In mm/kfence/report.c (ffffffff81466c35)
Location: include/linux/kfence.h:51
Inline: True
Inline callers:
  - mm/kfence/report.c:__kfence_obj_info
```
```
In mm/memcontrol.c (ffffffff8148eb42)
Location: include/linux/kfence.h:51
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_from_slab_obj
  - mm/memcontrol.c:mem_cgroup_from_obj
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
In mm/slab_common.c (ffffffff813fe358)
Location: include/linux/kfence.h:51
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_dump_obj
```
```
In mm/slub.c (ffffffff8145fa25)
Location: include/linux/kfence.h:51
Inline: True
Inline callers:
  - mm/slub.c:__check_heap_object
  - mm/slub.c:__kmem_obj_info
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:kfree
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:__memcg_slab_free_hook
  - mm/slub.c:__memcg_slab_post_alloc_hook
```
```
In mm/kfence/core.c (ffffffff81494f9c)
Location: include/linux/kfence.h:51
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_handle_page_fault
  - mm/kfence/core.c:kfence_handle_page_fault
  - mm/kfence/core.c:kfence_handle_page_fault
  - mm/kfence/core.c:kfence_handle_page_fault
  - mm/kfence/core.c:__kfence_free
  - mm/kfence/core.c:kfence_object_start
  - mm/kfence/core.c:kfence_ksize
  - mm/kfence/core.c:check_canary
  - mm/kfence/core.c:check_canary
  - mm/kfence/core.c:check_canary
```
```
In mm/kfence/report.c (ffffffff81495e45)
Location: include/linux/kfence.h:51
Inline: True
Inline callers:
  - mm/kfence/report.c:__kfence_obj_info
```
```
In mm/memcontrol.c (ffffffff814be4f2)
Location: include/linux/kfence.h:51
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_from_slab_obj
  - mm/memcontrol.c:mem_cgroup_from_obj
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
