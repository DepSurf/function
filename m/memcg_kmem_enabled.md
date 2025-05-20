# Function: <code>memcg_kmem_enabled</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81195021)
Location: include/linux/memcontrol.h:733
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_kmem_pages
  - mm/page_alloc.c:__free_kmem_pages
  - mm/page_alloc.c:alloc_kmem_pages_node
```
```
In mm/list_lru.c (ffffffff811b8f5a)
Location: include/linux/memcontrol.h:733
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_add
  - mm/list_lru.c:list_lru_del
```
```
In mm/slub.c (ffffffff811e9778)
Location: include/linux/memcontrol.h:733
Inline: True
Inline callers:
  - mm/slub.c:new_slab
  - mm/slub.c:new_slab
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
  - mm/slub.c:kmem_cache_alloc
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_free_bulk
  - mm/slub.c:__kmalloc
  - mm/slub.c:__kmalloc
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_node_track_caller
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8107fb39)
Location: include/linux/memcontrol.h:808
Inline: True
Inline callers:
  - kernel/fork.c:account_kernel_stack
```
```
In mm/page_alloc.c (ffffffff811ab14d)
Location: include/linux/memcontrol.h:808
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:free_hot_cold_page
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/vmscan.c (ffffffff811b6a0a)
Location: include/linux/memcontrol.h:808
Inline: True
```
```
In mm/list_lru.c (ffffffff811d3a34)
Location: include/linux/memcontrol.h:808
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
```
```
In mm/workingset.c (ffffffff811d4155)
Location: include/linux/memcontrol.h:808
Inline: True
Inline callers:
  - mm/workingset.c:count_shadow_nodes
```
```
In mm/slub.c (ffffffff8120e007)
Location: include/linux/memcontrol.h:808
Inline: True
Inline callers:
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_free_bulk
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
  - mm/slub.c:kmem_cache_alloc
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:new_slab
  - mm/slub.c:new_slab
  - mm/slub.c:new_slab
  - mm/slub.c:new_slab
```
```
In fs/pipe.c (ffffffff8123ba0c)
Location: include/linux/memcontrol.h:808
Inline: True
Inline callers:
  - fs/pipe.c:anon_pipe_buf_steal
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81084272)
Location: include/linux/memcontrol.h:845
Inline: True
Inline callers:
  - kernel/fork.c:account_kernel_stack
  - kernel/fork.c:account_kernel_stack
```
```
In mm/page_alloc.c (ffffffff811bb78f)
Location: include/linux/memcontrol.h:845
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:free_hot_cold_page
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/vmscan.c (ffffffff811c6fbd)
Location: include/linux/memcontrol.h:845
Inline: True
```
```
In mm/list_lru.c (ffffffff811e3900)
Location: include/linux/memcontrol.h:845
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
```
```
In mm/slub.c (ffffffff81220047)
Location: include/linux/memcontrol.h:845
Inline: True
Inline callers:
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_free_bulk
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
  - mm/slub.c:kmem_cache_alloc
  - mm/slub.c:__free_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:new_slab
  - mm/slub.c:new_slab
  - mm/slub.c:new_slab
  - mm/slub.c:new_slab
```
```
In fs/pipe.c (ffffffff8124e7ac)
Location: include/linux/memcontrol.h:845
Inline: True
Inline callers:
  - fs/pipe.c:anon_pipe_buf_steal
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811c3a97)
Location: include/linux/memcontrol.h:1109
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:free_hot_cold_page
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/vmscan.c (ffffffff811cf74a)
Location: include/linux/memcontrol.h:1109
Inline: True
```
```
In mm/list_lru.c (ffffffff811edd61)
Location: include/linux/memcontrol.h:1109
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
```
```
In mm/slub.c (ffffffff8122bda7)
Location: include/linux/memcontrol.h:1109
Inline: True
Inline callers:
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
  - mm/slub.c:kmem_cache_alloc
  - mm/slub.c:__free_slab
  - mm/slub.c:new_slab
  - mm/slub.c:new_slab
```
```
In fs/pipe.c (ffffffff8125a70c)
Location: include/linux/memcontrol.h:1109
Inline: True
Inline callers:
  - fs/pipe.c:anon_pipe_buf_steal
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811d8837)
Location: include/linux/memcontrol.h:1121
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/vmscan.c (ffffffff811e4b72)
Location: include/linux/memcontrol.h:1121
Inline: True
```
```
In mm/list_lru.c (ffffffff812041c1)
Location: include/linux/memcontrol.h:1121
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
```
```
In mm/slub.c (ffffffff812474d7)
Location: include/linux/memcontrol.h:1121
Inline: True
Inline callers:
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
  - mm/slub.c:kmem_cache_alloc
  - mm/slub.c:__free_slab
  - mm/slub.c:new_slab
  - mm/slub.c:new_slab
```
```
In fs/pipe.c (ffffffff8127ca6c)
Location: include/linux/memcontrol.h:1121
Inline: True
Inline callers:
  - fs/pipe.c:anon_pipe_buf_steal
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811f99f7)
Location: include/linux/memcontrol.h:1213
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/vmscan.c (ffffffff812062de)
Location: include/linux/memcontrol.h:1213
Inline: True
```
```
In mm/list_lru.c (ffffffff81224e6e)
Location: include/linux/memcontrol.h:1213
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
```
```
In mm/slub.c (ffffffff8126a439)
Location: include/linux/memcontrol.h:1213
Inline: True
Inline callers:
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
  - mm/slub.c:kmem_cache_alloc
  - mm/slub.c:__free_slab
  - mm/slub.c:new_slab
  - mm/slub.c:new_slab
```
```
In fs/pipe.c (ffffffff812a39bc)
Location: include/linux/memcontrol.h:1213
Inline: True
Inline callers:
  - fs/pipe.c:anon_pipe_buf_steal
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8120c07b)
Location: include/linux/memcontrol.h:1298
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/vmscan.c (ffffffff81218f4e)
Location: include/linux/memcontrol.h:1298
Inline: True
```
```
In mm/list_lru.c (ffffffff81237f82)
Location: include/linux/memcontrol.h:1298
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
```
```
In mm/slub.c (ffffffff8127ecd9)
Location: include/linux/memcontrol.h:1298
Inline: True
Inline callers:
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
  - mm/slub.c:kmem_cache_alloc
  - mm/slub.c:__free_slab
  - mm/slub.c:new_slab
  - mm/slub.c:new_slab
```
```
In fs/pipe.c (ffffffff812b8a2c)
Location: include/linux/memcontrol.h:1298
Inline: True
Inline callers:
  - fs/pipe.c:anon_pipe_buf_steal
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810983a6)
Location: include/linux/memcontrol.h:1311
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:put_task_stack
```
```
In mm/vmscan.c (ffffffff81228fe9)
Location: include/linux/memcontrol.h:1311
Inline: True
```
```
In mm/list_lru.c (ffffffff81249533)
Location: include/linux/memcontrol.h:1311
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
```
```
In mm/page_alloc.c (ffffffff812722cf)
Location: include/linux/memcontrol.h:1311
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/slub.c (ffffffff8129ab16)
Location: include/linux/memcontrol.h:1311
Inline: True
Inline callers:
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
  - mm/slub.c:kmem_cache_alloc
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
```
```
In fs/pipe.c (ffffffff812d576c)
Location: include/linux/memcontrol.h:1311
Inline: True
Inline callers:
  - fs/pipe.c:anon_pipe_buf_steal
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8109e97c)
Location: include/linux/memcontrol.h:1397
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:put_task_stack
```
```
In mm/vmscan.c (ffffffff81236e71)
Location: include/linux/memcontrol.h:1397
Inline: True
```
```
In mm/list_lru.c (ffffffff81257983)
Location: include/linux/memcontrol.h:1397
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
```
```
In mm/page_alloc.c (ffffffff8128112f)
Location: include/linux/memcontrol.h:1397
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/slub.c (ffffffff812aa9d6)
Location: include/linux/memcontrol.h:1397
Inline: True
Inline callers:
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
  - mm/slub.c:kmem_cache_alloc
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
```
```
In fs/pipe.c (ffffffff812e72dc)
Location: include/linux/memcontrol.h:1397
Inline: True
Inline callers:
  - fs/pipe.c:anon_pipe_buf_steal
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a43e5)
Location: include/linux/memcontrol.h:1369
Inline: True
Inline callers:
  - kernel/fork.c:memcg_charge_kernel_stack
```
```
In mm/vmscan.c (ffffffff81266a25)
Location: include/linux/memcontrol.h:1369
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_slab_memcg
```
```
In mm/page_alloc.c (ffffffff812b3609)
Location: include/linux/memcontrol.h:1369
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/slub.c (ffffffff812dcc7d)
Location: include/linux/memcontrol.h:1369
Inline: True
Inline callers:
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
  - mm/slub.c:kmem_cache_alloc
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:cache_from_obj
```
```
In fs/pipe.c (ffffffff8131ec4c)
Location: include/linux/memcontrol.h:1369
Inline: True
Inline callers:
  - fs/pipe.c:anon_pipe_buf_try_steal
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a1347)
Location: include/linux/memcontrol.h:1627
Inline: True
Inline callers:
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:put_task_stack
```
```
In mm/vmscan.c (ffffffff81271475)
Location: include/linux/memcontrol.h:1627
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_slab_memcg
```
```
In mm/percpu.c (ffffffff81285a22)
Location: include/linux/memcontrol.h:1627
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc
```
```
In mm/page_alloc.c (ffffffff812bf0c0)
Location: include/linux/memcontrol.h:1627
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/slub.c (ffffffff812e6969)
Location: include/linux/memcontrol.h:1627
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:__free_slab
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In fs/pipe.c (ffffffff8132a16c)
Location: include/linux/memcontrol.h:1627
Inline: True
Inline callers:
  - fs/pipe.c:anon_pipe_buf_try_steal
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a20be)
Location: include/linux/memcontrol.h:1657
Inline: True
Inline callers:
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:put_task_stack
```
```
In mm/vmscan.c (ffffffff81276679)
Location: include/linux/memcontrol.h:1657
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_slab_memcg
```
```
In mm/percpu.c (ffffffff8128a5f7)
Location: include/linux/memcontrol.h:1657
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc
```
```
In mm/page_alloc.c (ffffffff812c415a)
Location: include/linux/memcontrol.h:1657
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/slub.c (ffffffff812ee129)
Location: include/linux/memcontrol.h:1657
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:__free_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In fs/pipe.c (ffffffff8133011c)
Location: include/linux/memcontrol.h:1657
Inline: True
Inline callers:
  - fs/pipe.c:anon_pipe_buf_try_steal
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
In kernel/fork.c (ffffffff810b2ea1)
Location: include/linux/memcontrol.h:1666
Inline: True
Inline callers:
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:put_task_stack
```
```
In mm/vmscan.c (ffffffff812b3e96)
Location: include/linux/memcontrol.h:1666
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_slab_memcg
```
```
In mm/percpu.c (ffffffff812caa15)
Location: include/linux/memcontrol.h:1666
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc
```
```
In mm/page_alloc.c (ffffffff8130800a)
Location: include/linux/memcontrol.h:1666
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/slub.c (ffffffff81338c0c)
Location: include/linux/memcontrol.h:1666
Inline: True
Inline callers:
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
  - mm/slub.c:__free_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In fs/pipe.c (ffffffff8137d8dc)
Location: include/linux/memcontrol.h:1666
Inline: True
Inline callers:
  - fs/pipe.c:anon_pipe_buf_try_steal
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
In kernel/fork.c (ffffffff810c8ff0)
Location: include/linux/memcontrol.h:1725
Inline: True
Inline callers:
  - kernel/fork.c:exit_task_stack_account
```
```
In mm/vmscan.c (ffffffff8130febe)
Location: include/linux/memcontrol.h:1725
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_slab_memcg
```
```
In mm/percpu.c (ffffffff81328312)
Location: include/linux/memcontrol.h:1725
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc
```
```
In mm/page_alloc.c (ffffffff81370333)
Location: include/linux/memcontrol.h:1725
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/slub.c (ffffffff813aa7dd)
Location: include/linux/memcontrol.h:1725
Inline: True
Inline callers:
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
  - mm/slub.c:__free_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/memcontrol.c (ffffffff813d3805)
Location: include/linux/memcontrol.h:1725
Inline: True
Inline callers:
  - mm/memcontrol.c:get_obj_cgroup_from_page
```
```
In fs/pipe.c (ffffffff813fe5ff)
Location: include/linux/memcontrol.h:1725
Inline: True
Inline callers:
  - fs/pipe.c:anon_pipe_buf_try_steal
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
In kernel/fork.c (ffffffff810e64b0)
Location: include/linux/memcontrol.h:1759
Inline: True
Inline callers:
  - kernel/fork.c:exit_task_stack_account
```
```
In mm/vmscan.c (ffffffff813834c4)
Location: include/linux/memcontrol.h:1759
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_slab_memcg
```
```
In mm/percpu.c (ffffffff8139d582)
Location: include/linux/memcontrol.h:1759
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc
```
```
In mm/page_alloc.c (ffffffff813ec9d3)
Location: include/linux/memcontrol.h:1759
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/zswap.c (ffffffff81403361)
Location: include/linux/memcontrol.h:1759
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/slub.c (ffffffff8142cc35)
Location: include/linux/memcontrol.h:1759
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
In mm/memcontrol.c (ffffffff81459205)
Location: include/linux/memcontrol.h:1759
Inline: True
Inline callers:
  - mm/memcontrol.c:get_obj_cgroup_from_page
```
```
In fs/pipe.c (ffffffff8148829f)
Location: include/linux/memcontrol.h:1759
Inline: True
Inline callers:
  - fs/pipe.c:anon_pipe_buf_try_steal
```
</details>
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
In kernel/fork.c (ffff8000100f30a8)
Location: include/linux/memcontrol.h:1397
Inline: True
Inline callers:
  - kernel/fork.c:dup_task_struct
```
```
In mm/vmscan.c (ffff8000102c848c)
Location: include/linux/memcontrol.h:1397
Inline: True
```
```
In mm/list_lru.c (ffff8000102ef4fc)
Location: include/linux/memcontrol.h:1397
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
```
```
In mm/page_alloc.c (ffff800010318db4)
Location: include/linux/memcontrol.h:1397
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/slub.c (ffff80001034c95c)
Location: include/linux/memcontrol.h:1397
Inline: True
Inline callers:
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
  - mm/slub.c:kmem_cache_alloc
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
```
```
In fs/pipe.c (ffff80001038fb90)
Location: include/linux/memcontrol.h:1397
Inline: True
Inline callers:
  - fs/pipe.c:anon_pipe_buf_steal
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
In mm/vmscan.c (c04f1c74)
Location: include/linux/memcontrol.h:1397
Inline: True
```
```
In mm/list_lru.c (c0512f64)
Location: include/linux/memcontrol.h:1397
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
```
```
In mm/page_alloc.c (c053376c)
Location: include/linux/memcontrol.h:1397
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/slub.c (c05501bc)
Location: include/linux/memcontrol.h:1397
Inline: True
Inline callers:
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
  - mm/slub.c:kmem_cache_alloc
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
```
```
In fs/pipe.c (c05767e8)
Location: include/linux/memcontrol.h:1397
Inline: True
Inline callers:
  - fs/pipe.c:anon_pipe_buf_steal
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (c000000000382e7c)
Location: include/linux/memcontrol.h:1397
Inline: True
```
```
In mm/list_lru.c (c0000000003b3af8)
Location: include/linux/memcontrol.h:1397
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
```
```
In mm/page_alloc.c (c0000000003eb728)
Location: include/linux/memcontrol.h:1397
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/slub.c (c00000000042c550)
Location: include/linux/memcontrol.h:1397
Inline: True
Inline callers:
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
  - mm/slub.c:kmem_cache_alloc
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
```
```
In fs/pipe.c (c000000000487870)
Location: include/linux/memcontrol.h:1397
Inline: True
Inline callers:
  - fs/pipe.c:anon_pipe_buf_steal
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffe0001e6e82)
Location: include/linux/memcontrol.h:1397
Inline: True
```
```
In mm/list_lru.c (ffffffe000203208)
Location: include/linux/memcontrol.h:1397
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
```
```
In mm/page_alloc.c (ffffffe00021eb02)
Location: include/linux/memcontrol.h:1397
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/slub.c (ffffffe00023d6f4)
Location: include/linux/memcontrol.h:1397
Inline: True
Inline callers:
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
  - mm/slub.c:kmem_cache_alloc
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
```
```
In fs/pipe.c (ffffffe00025f7b2)
Location: include/linux/memcontrol.h:1397
Inline: True
Inline callers:
  - fs/pipe.c:anon_pipe_buf_steal
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8109829c)
Location: include/linux/memcontrol.h:1397
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:put_task_stack
```
```
In mm/vmscan.c (ffffffff8122f4c1)
Location: include/linux/memcontrol.h:1397
Inline: True
```
```
In mm/list_lru.c (ffffffff8124ffd3)
Location: include/linux/memcontrol.h:1397
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
```
```
In mm/page_alloc.c (ffffffff8127977f)
Location: include/linux/memcontrol.h:1397
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/slub.c (ffffffff812a2fb6)
Location: include/linux/memcontrol.h:1397
Inline: True
Inline callers:
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
  - mm/slub.c:kmem_cache_alloc
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
```
```
In fs/pipe.c (ffffffff812df8bc)
Location: include/linux/memcontrol.h:1397
Inline: True
Inline callers:
  - fs/pipe.c:anon_pipe_buf_steal
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81086cf6)
Location: include/linux/memcontrol.h:1397
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:put_task_stack
```
```
In mm/vmscan.c (ffffffff81222581)
Location: include/linux/memcontrol.h:1397
Inline: True
```
```
In mm/list_lru.c (ffffffff81242f73)
Location: include/linux/memcontrol.h:1397
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
```
```
In mm/page_alloc.c (ffffffff8126b66f)
Location: include/linux/memcontrol.h:1397
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/slub.c (ffffffff81294a86)
Location: include/linux/memcontrol.h:1397
Inline: True
Inline callers:
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
  - mm/slub.c:kmem_cache_alloc
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
```
```
In fs/pipe.c (ffffffff812d04fc)
Location: include/linux/memcontrol.h:1397
Inline: True
Inline callers:
  - fs/pipe.c:anon_pipe_buf_steal
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8109824c)
Location: include/linux/memcontrol.h:1397
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:put_task_stack
```
```
In mm/vmscan.c (ffffffff8122d261)
Location: include/linux/memcontrol.h:1397
Inline: True
```
```
In mm/list_lru.c (ffffffff8124dd73)
Location: include/linux/memcontrol.h:1397
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
```
```
In mm/page_alloc.c (ffffffff8127751f)
Location: include/linux/memcontrol.h:1397
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/slub.c (ffffffff812a0dc6)
Location: include/linux/memcontrol.h:1397
Inline: True
Inline callers:
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
  - mm/slub.c:kmem_cache_alloc
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
```
```
In fs/pipe.c (ffffffff812dd6cc)
Location: include/linux/memcontrol.h:1397
Inline: True
Inline callers:
  - fs/pipe.c:anon_pipe_buf_steal
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8109fe43)
Location: include/linux/memcontrol.h:1397
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:put_task_stack
```
```
In mm/vmscan.c (ffffffff8123c691)
Location: include/linux/memcontrol.h:1397
Inline: True
```
```
In mm/list_lru.c (ffffffff8125d721)
Location: include/linux/memcontrol.h:1397
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
```
```
In mm/page_alloc.c (ffffffff81287102)
Location: include/linux/memcontrol.h:1397
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/slub.c (ffffffff812b0f31)
Location: include/linux/memcontrol.h:1397
Inline: True
Inline callers:
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
  - mm/slub.c:kmem_cache_alloc
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
```
```
In fs/pipe.c (ffffffff812ee64c)
Location: include/linux/memcontrol.h:1397
Inline: True
Inline callers:
  - fs/pipe.c:anon_pipe_buf_steal
```
</details>
</li>
</ul>

## Differences
