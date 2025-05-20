# Function: <code>memcg_kmem_online</code>

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
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810f1e20)
Location: include/linux/memcontrol.h:1782
Inline: True
Inline callers:
  - kernel/fork.c:exit_task_stack_account
```
```
In mm/vmscan.c (ffffffff813b4cee)
Location: include/linux/memcontrol.h:1782
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_slab_memcg
```
```
In mm/percpu.c (ffffffff813d06b6)
Location: include/linux/memcontrol.h:1782
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc
```
```
In mm/page_alloc.c (ffffffff81421945)
Location: include/linux/memcontrol.h:1782
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:free_unref_page_prepare
  - mm/page_alloc.c:free_unref_page_prepare
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/zswap.c (ffffffff814368f4)
Location: include/linux/memcontrol.h:1782
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/slub.c (ffffffff81462245)
Location: include/linux/memcontrol.h:1782
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:__kmem_cache_free
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:__kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc
  - mm/slub.c:__free_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/memcontrol.c (ffffffff8148ee95)
Location: include/linux/memcontrol.h:1782
Inline: True
Inline callers:
  - mm/memcontrol.c:get_obj_cgroup_from_page
```
```
In fs/pipe.c (ffffffff814bd1a7)
Location: include/linux/memcontrol.h:1782
Inline: True
Inline callers:
  - fs/pipe.c:anon_pipe_buf_try_steal
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
In kernel/fork.c (ffffffff810fba82)
Location: include/linux/memcontrol.h:1838
Inline: True
Inline callers:
  - kernel/fork.c:exit_task_stack_account
```
```
In mm/shrinker.c (ffffffff813e4a33)
Location: include/linux/memcontrol.h:1838
Inline: True
Inline callers:
  - mm/shrinker.c:shrink_slab_memcg
```
```
In mm/percpu.c (ffffffff813fb076)
Location: include/linux/memcontrol.h:1838
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc
```
```
In mm/page_alloc.c (ffffffff8144e775)
Location: include/linux/memcontrol.h:1838
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:free_unref_page_prepare
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/slub.c (ffffffff8145e761)
Location: include/linux/memcontrol.h:1838
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kfree
  - mm/slub.c:kmem_cache_free
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
  - mm/slub.c:__free_slab
  - mm/slub.c:allocate_slab
```
```
In mm/zswap.c (ffffffff814713fd)
Location: include/linux/memcontrol.h:1838
Inline: True
Inline callers:
  - mm/zswap.c:zswap_load
  - mm/zswap.c:zswap_store
  - mm/zswap.c:shrink_memcg_cb
```
```
In mm/memcontrol.c (ffffffff814be7e5)
Location: include/linux/memcontrol.h:1838
Inline: True
Inline callers:
  - mm/memcontrol.c:get_obj_cgroup_from_folio
```
```
In fs/pipe.c (ffffffff814ef644)
Location: include/linux/memcontrol.h:1838
Inline: True
Inline callers:
  - fs/pipe.c:anon_pipe_buf_try_steal
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
