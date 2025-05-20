# Function: <code>slab_nid</code>

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
In mm/slub.c (ffffffff813ab1ce)
Location: mm/slab.h:163
Inline: True
Inline callers:
  - mm/slub.c:show_slab_objects
  - mm/slub.c:show_slab_objects
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:init_kmem_cache_nodes
  - mm/slub.c:__slab_free
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:___slab_alloc
  - mm/slub.c:__unfreeze_partials
  - mm/slub.c:deactivate_slab
  - mm/slub.c:discard_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:free_debug_processing
```
```
In mm/memcontrol.c (ffffffff813d33b5)
Location: mm/slab.h:163
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_alloc_slab_cgroups
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
In mm/slub.c (ffffffff814272be)
Location: mm/slab.h:173
Inline: True
Inline callers:
  - mm/slub.c:show_slab_objects
  - mm/slub.c:show_slab_objects
  - mm/slub.c:early_kmem_cache_node_alloc
  - mm/slub.c:early_kmem_cache_node_alloc
  - mm/slub.c:__slab_free
  - mm/slub.c:free_to_partial_list
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:__kmem_cache_alloc_node
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:__unfreeze_partials
  - mm/slub.c:deactivate_slab
  - mm/slub.c:discard_slab
```
```
In mm/memcontrol.c (ffffffff81458b75)
Location: mm/slab.h:173
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_alloc_slab_cgroups
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
In mm/slub.c (ffffffff8145c25e)
Location: mm/slab.h:201
Inline: True
Inline callers:
  - mm/slub.c:show_slab_objects
  - mm/slub.c:show_slab_objects
  - mm/slub.c:early_kmem_cache_node_alloc
  - mm/slub.c:early_kmem_cache_node_alloc
  - mm/slub.c:__slab_free
  - mm/slub.c:free_to_partial_list
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:__kmem_cache_alloc_node
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:__unfreeze_partials
  - mm/slub.c:deactivate_slab
  - mm/slub.c:discard_slab
```
```
In mm/memcontrol.c (ffffffff8148e7f5)
Location: mm/slab.h:201
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_alloc_slab_cgroups
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
In mm/slub.c (ffffffff8145d4be)
Location: mm/slab.h:192
Inline: True
Inline callers:
  - mm/slub.c:show_slab_objects
  - mm/slub.c:show_slab_objects
  - mm/slub.c:early_kmem_cache_node_alloc
  - mm/slub.c:early_kmem_cache_node_alloc
  - mm/slub.c:__slab_free
  - mm/slub.c:free_to_partial_list
  - mm/slub.c:kmalloc_node_trace
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:__put_partials
  - mm/slub.c:deactivate_slab
  - mm/slub.c:discard_slab
```
```
In mm/memcontrol.c (ffffffff814be1b5)
Location: mm/slab.h:192
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_alloc_slab_cgroups
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
