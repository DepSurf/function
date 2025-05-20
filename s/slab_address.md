# Function: <code>slab_address</code>

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
In mm/slub.c (ffffffff813a5377)
Location: mm/slab.h:158
Inline: True
Inline callers:
  - mm/slub.c:process_slab
  - mm/slub.c:validate_slab
  - mm/slub.c:__check_heap_object
  - mm/slub.c:__kmem_obj_info
  - mm/slub.c:free_partial
  - mm/slub.c:deactivate_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
  - mm/slub.c:on_freelist
  - mm/slub.c:check_object
  - mm/slub.c:slab_pad_check
  - mm/slub.c:check_bytes_and_report
  - mm/slub.c:print_trailer
  - mm/slub.c:__fill_map
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/memcontrol.c (ffffffff813d34e0)
Location: mm/slab.h:158
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
In mm/slub.c (ffffffff814264b5)
Location: mm/slab.h:168
Inline: True
Inline callers:
  - mm/slub.c:process_slab
  - mm/slub.c:validate_slab
  - mm/slub.c:__check_heap_object
  - mm/slub.c:__kmem_obj_info
  - mm/slub.c:free_partial
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:__kmem_cache_free
  - mm/slub.c:free_debug_processing
  - mm/slub.c:deactivate_slab
  - mm/slub.c:free_slab
  - mm/slub.c:free_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:shuffle_freelist
  - mm/slub.c:alloc_debug_processing
  - mm/slub.c:on_freelist
  - mm/slub.c:check_object
  - mm/slub.c:slab_pad_check
  - mm/slub.c:check_bytes_and_report
  - mm/slub.c:print_trailer
  - mm/slub.c:__fill_map
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/memcontrol.c (ffffffff81458ec3)
Location: mm/slab.h:168
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
In mm/slub.c (ffffffff8145b525)
Location: mm/slab.h:196
Inline: True
Inline callers:
  - mm/slub.c:process_slab
  - mm/slub.c:validate_slab
  - mm/slub.c:__check_heap_object
  - mm/slub.c:__kmem_obj_info
  - mm/slub.c:free_partial
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:__kmem_cache_free
  - mm/slub.c:free_debug_processing
  - mm/slub.c:deactivate_slab
  - mm/slub.c:free_slab
  - mm/slub.c:free_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:shuffle_freelist
  - mm/slub.c:alloc_debug_processing
  - mm/slub.c:on_freelist
  - mm/slub.c:check_object
  - mm/slub.c:slab_pad_check
  - mm/slub.c:check_bytes_and_report
  - mm/slub.c:print_trailer
  - mm/slub.c:__fill_map
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/memcontrol.c (ffffffff8148eb53)
Location: mm/slab.h:196
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
In mm/slub.c (ffffffff81456705)
Location: mm/slab.h:187
Inline: True
Inline callers:
  - mm/slub.c:process_slab
  - mm/slub.c:validate_slab
  - mm/slub.c:__check_heap_object
  - mm/slub.c:__kmem_obj_info
  - mm/slub.c:free_partial
  - mm/slub.c:free_debug_processing
  - mm/slub.c:deactivate_slab
  - mm/slub.c:free_slab
  - mm/slub.c:free_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:shuffle_freelist
  - mm/slub.c:__memcg_slab_free_hook
  - mm/slub.c:__memcg_slab_post_alloc_hook
  - mm/slub.c:alloc_debug_processing
  - mm/slub.c:on_freelist
  - mm/slub.c:check_object
  - mm/slub.c:slab_pad_check
  - mm/slub.c:check_bytes_and_report
  - mm/slub.c:print_trailer
  - mm/slub.c:__fill_map
```
```
In mm/memcontrol.c (ffffffff814be503)
Location: mm/slab.h:187
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
