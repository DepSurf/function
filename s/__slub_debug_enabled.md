# Function: <code>__slub_debug_enabled</code>

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
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool __slub_debug_enabled();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81333903)
Location: mm/slab.h:219
Inline: True
Inline callers:
  - mm/slub.c:cpu_partial_store
  - mm/slub.c:process_slab
  - mm/slub.c:validate_slab
  - mm/slub.c:__check_heap_object
  - mm/slub.c:kmem_obj_info
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
  - mm/slub.c:___slab_alloc
  - mm/slub.c:deactivate_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:allocate_slab
Direct callers:
  - mm/slub.c:kmem_cache_init
```
**Symbols:**

```
ffffffff81cc0b0d-ffffffff81cc0b15: __slub_debug_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool __slub_debug_enabled();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff813a5333)
Location: mm/slab.h:406
Inline: True
Inline callers:
  - mm/slub.c:cpu_partial_store
  - mm/slub.c:process_slab
  - mm/slub.c:validate_slab
  - mm/slub.c:__check_heap_object
  - mm/slub.c:__kmem_obj_info
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
  - mm/slub.c:___slab_alloc
  - mm/slub.c:deactivate_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:setup_object
Direct callers:
  - mm/slub.c:kmem_cache_init
```
**Symbols:**

```
ffffffff81e730fc-ffffffff81e7310c: __slub_debug_enabled (STB_LOCAL)
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
In mm/slub.c (ffffffff8142b51e)
Location: mm/slab.h:412
Inline: True
Inline callers:
  - mm/slub.c:validate_store
  - mm/slub.c:cpu_partial_store
  - mm/slub.c:process_slab
  - mm/slub.c:process_slab
  - mm/slub.c:validate_slab
  - mm/slub.c:__check_heap_object
  - mm/slub.c:__kmem_obj_info
  - mm/slub.c:free_partial
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:calculate_sizes
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:__kmem_cache_alloc_bulk
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:__kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_lru
  - mm/slub.c:kmem_cache_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:free_slab
  - mm/slub.c:free_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:shuffle_freelist
  - mm/slub.c:setup_object
  - mm/slub.c:alloc_debug_processing
  - mm/slub.c:check_object
  - mm/slub.c:check_object
  - mm/slub.c:init_object
  - mm/slub.c:init_object
  - mm/slub.c:print_trailer
  - mm/slub.c:skip_orig_size_check
  - mm/slub.c:kmem_cache_init
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
In mm/slub.c (ffffffff81460a8e)
Location: mm/slab.h:404
Inline: True
Inline callers:
  - mm/slub.c:validate_store
  - mm/slub.c:cpu_partial_store
  - mm/slub.c:process_slab
  - mm/slub.c:process_slab
  - mm/slub.c:validate_slab
  - mm/slub.c:__check_heap_object
  - mm/slub.c:__kmem_obj_info
  - mm/slub.c:free_partial
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:calculate_sizes
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:__kmem_cache_alloc_bulk
  - mm/slub.c:__kmem_cache_alloc_bulk
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:__kmem_cache_alloc_node
  - mm/slub.c:__kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_lru
  - mm/slub.c:kmem_cache_alloc_lru
  - mm/slub.c:kmem_cache_alloc
  - mm/slub.c:kmem_cache_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:free_slab
  - mm/slub.c:free_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:shuffle_freelist
  - mm/slub.c:setup_object
  - mm/slub.c:alloc_debug_processing
  - mm/slub.c:check_object
  - mm/slub.c:check_object
  - mm/slub.c:init_object
  - mm/slub.c:init_object
  - mm/slub.c:print_trailer
  - mm/slub.c:skip_orig_size_check
  - mm/slub.c:kmem_cache_init
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
In mm/slub.c (ffffffff81458a4e)
Location: mm/slab.h:516
Inline: True
Inline callers:
  - mm/slub.c:validate_store
  - mm/slub.c:cpu_partial_store
  - mm/slub.c:process_slab
  - mm/slub.c:process_slab
  - mm/slub.c:validate_slab
  - mm/slub.c:__check_heap_object
  - mm/slub.c:__kmem_obj_info
  - mm/slub.c:free_partial
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:calculate_sizes
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
  - mm/slub.c:kmalloc_node_trace
  - mm/slub.c:kmalloc_node_trace
  - mm/slub.c:kmalloc_trace
  - mm/slub.c:kmalloc_trace
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc
  - mm/slub.c:__kmalloc
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_lru
  - mm/slub.c:kmem_cache_alloc_lru
  - mm/slub.c:kmem_cache_alloc
  - mm/slub.c:kmem_cache_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:free_slab
  - mm/slub.c:free_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:shuffle_freelist
  - mm/slub.c:setup_object
  - mm/slub.c:alloc_debug_processing
  - mm/slub.c:check_object
  - mm/slub.c:check_object
  - mm/slub.c:init_object
  - mm/slub.c:init_object
  - mm/slub.c:print_trailer
  - mm/slub.c:skip_orig_size_check
  - mm/slub.c:kmem_cache_init
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
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
</ul>
