# Function: <code>get_node</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff811e77eb)
Location: mm/slab.h:354
Inline: True
Inline callers:
  - mm/slub.c:slab_out_of_memory
  - mm/slub.c:discard_slab
  - mm/slub.c:new_slab
  - mm/slub.c:free_debug_processing
  - mm/slub.c:deactivate_slab
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:bootstrap
  - mm/slub.c:__slab_free
  - mm/slub.c:free_kmem_cache_nodes
  - mm/slub.c:show_slab_objects
  - mm/slub.c:show_slab_objects
  - mm/slub.c:list_locations
  - mm/slub.c:validate_store
  - mm/slub.c:store_user_store
  - mm/slub.c:poison_store
  - mm/slub.c:red_zone_store
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:slab_memory_callback
  - mm/slub.c:__kmem_cache_create
  - mm/slub.c:__kmem_cache_create
  - mm/slub.c:get_slabinfo
```
```
In drivers/md/dm-table.c (ffffffff816a6468)
Location: drivers/md/dm-table.c:94
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_find_target
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8120e2d6)
Location: mm/slab.h:456
Inline: True
Inline callers:
  - mm/slub.c:get_slabinfo
  - mm/slub.c:validate_store
  - mm/slub.c:store_user_store
  - mm/slub.c:poison_store
  - mm/slub.c:red_zone_store
  - mm/slub.c:show_slab_objects
  - mm/slub.c:show_slab_objects
  - mm/slub.c:list_locations
  - mm/slub.c:bootstrap
  - mm/slub.c:slab_memory_callback
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:free_kmem_cache_nodes
  - mm/slub.c:__slab_free
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:slab_out_of_memory
  - mm/slub.c:deactivate_slab
  - mm/slub.c:discard_slab
  - mm/slub.c:new_slab
  - mm/slub.c:free_debug_processing
```
```
In drivers/md/dm-table.c (ffffffff81706b55)
Location: drivers/md/dm-table.c:96
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_find_target
  - drivers/md/dm-table.c:dm_table_complete
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81220316)
Location: mm/slab.h:473
Inline: True
Inline callers:
  - mm/slub.c:get_slabinfo
  - mm/slub.c:validate_store
  - mm/slub.c:store_user_store
  - mm/slub.c:poison_store
  - mm/slub.c:red_zone_store
  - mm/slub.c:show_slab_objects
  - mm/slub.c:show_slab_objects
  - mm/slub.c:list_locations
  - mm/slub.c:bootstrap
  - mm/slub.c:slab_memory_callback
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:free_kmem_cache_nodes
  - mm/slub.c:__slab_free
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:slab_out_of_memory
  - mm/slub.c:deactivate_slab
  - mm/slub.c:discard_slab
  - mm/slub.c:new_slab
  - mm/slub.c:free_debug_processing
```
```
In drivers/md/dm-table.c (ffffffff81738a25)
Location: drivers/md/dm-table.c:96
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_find_target
  - drivers/md/dm-table.c:dm_table_complete
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8122c04a)
Location: mm/slab.h:481
Inline: True
Inline callers:
  - mm/slub.c:get_slabinfo
  - mm/slub.c:validate_store
  - mm/slub.c:store_user_store
  - mm/slub.c:poison_store
  - mm/slub.c:red_zone_store
  - mm/slub.c:show_slab_objects
  - mm/slub.c:show_slab_objects
  - mm/slub.c:list_locations
  - mm/slub.c:__kmem_cache_create
  - mm/slub.c:bootstrap
  - mm/slub.c:slab_memory_callback
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:free_kmem_cache_nodes
  - mm/slub.c:__slab_free
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:slab_out_of_memory
  - mm/slub.c:discard_slab
  - mm/slub.c:new_slab
  - mm/slub.c:free_debug_processing
```
```
In drivers/md/dm-table.c (ffffffff81751f85)
Location: drivers/md/dm-table.c:98
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_find_target
  - drivers/md/dm-table.c:dm_table_complete
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812477aa)
Location: mm/slab.h:483
Inline: True
Inline callers:
  - mm/slub.c:get_slabinfo
  - mm/slub.c:validate_store
  - mm/slub.c:store_user_store
  - mm/slub.c:poison_store
  - mm/slub.c:red_zone_store
  - mm/slub.c:show_slab_objects
  - mm/slub.c:show_slab_objects
  - mm/slub.c:list_locations
  - mm/slub.c:__kmem_cache_create
  - mm/slub.c:bootstrap
  - mm/slub.c:slab_memory_callback
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:free_kmem_cache_nodes
  - mm/slub.c:__slab_free
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:slab_out_of_memory
  - mm/slub.c:discard_slab
  - mm/slub.c:new_slab
  - mm/slub.c:free_debug_processing
```
```
In drivers/md/dm-table.c (ffffffff817c4165)
Location: drivers/md/dm-table.c:98
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_find_target
  - drivers/md/dm-table.c:dm_table_complete
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8126a702)
Location: mm/slab.h:485
Inline: True
Inline callers:
  - mm/slub.c:get_slabinfo
  - mm/slub.c:validate_store
  - mm/slub.c:store_user_store
  - mm/slub.c:poison_store
  - mm/slub.c:red_zone_store
  - mm/slub.c:show_slab_objects
  - mm/slub.c:show_slab_objects
  - mm/slub.c:list_locations
  - mm/slub.c:bootstrap
  - mm/slub.c:slab_memory_callback
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__kmem_cache_empty
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:free_kmem_cache_nodes
  - mm/slub.c:__slab_free
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:slab_out_of_memory
  - mm/slub.c:discard_slab
  - mm/slub.c:new_slab
  - mm/slub.c:free_debug_processing
```
```
In drivers/md/dm-table.c (ffffffff8180cc61)
Location: drivers/md/dm-table.c:98
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_find_target
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_complete
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8127ef92)
Location: mm/slab.h:485
Inline: True
Inline callers:
  - mm/slub.c:get_slabinfo
  - mm/slub.c:validate_store
  - mm/slub.c:store_user_store
  - mm/slub.c:poison_store
  - mm/slub.c:red_zone_store
  - mm/slub.c:show_slab_objects
  - mm/slub.c:show_slab_objects
  - mm/slub.c:list_locations
  - mm/slub.c:bootstrap
  - mm/slub.c:slab_memory_callback
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__kmem_cache_empty
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:free_kmem_cache_nodes
  - mm/slub.c:__slab_free
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:slab_out_of_memory
  - mm/slub.c:discard_slab
  - mm/slub.c:new_slab
  - mm/slub.c:free_debug_processing
```
```
In drivers/md/dm-table.c (ffffffff81838b91)
Location: drivers/md/dm-table.c:97
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_find_target
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_complete
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8129ae32)
Location: mm/slab.h:564
Inline: True
Inline callers:
  - mm/slub.c:get_slabinfo
  - mm/slub.c:validate_store
  - mm/slub.c:store_user_store
  - mm/slub.c:poison_store
  - mm/slub.c:red_zone_store
  - mm/slub.c:show_slab_objects
  - mm/slub.c:show_slab_objects
  - mm/slub.c:list_locations
  - mm/slub.c:bootstrap
  - mm/slub.c:slab_memory_callback
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__kmem_cache_empty
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:free_kmem_cache_nodes
  - mm/slub.c:__slab_free
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:slab_out_of_memory
  - mm/slub.c:discard_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:free_debug_processing
```
```
In drivers/md/dm-table.c (ffffffff8187b757)
Location: drivers/md/dm-table.c:97
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_find_target
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_complete
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812aacf2)
Location: mm/slab.h:628
Inline: True
Inline callers:
  - mm/slub.c:get_slabinfo
  - mm/slub.c:validate_store
  - mm/slub.c:store_user_store
  - mm/slub.c:poison_store
  - mm/slub.c:red_zone_store
  - mm/slub.c:show_slab_objects
  - mm/slub.c:show_slab_objects
  - mm/slub.c:list_locations
  - mm/slub.c:bootstrap
  - mm/slub.c:slab_memory_callback
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__kmem_cache_empty
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:free_kmem_cache_nodes
  - mm/slub.c:__slab_free
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:slab_out_of_memory
  - mm/slub.c:discard_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:free_debug_processing
```
```
In drivers/md/dm-table.c (ffffffff818ad534)
Location: drivers/md/dm-table.c:97
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_find_target
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_complete
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812df497)
Location: mm/slab.h:630
Inline: True
Inline callers:
  - mm/slub.c:get_slabinfo
  - mm/slub.c:validate_store
  - mm/slub.c:store_user_store
  - mm/slub.c:poison_store
  - mm/slub.c:red_zone_store
  - mm/slub.c:show_slab_objects
  - mm/slub.c:show_slab_objects
  - mm/slub.c:list_locations
  - mm/slub.c:bootstrap
  - mm/slub.c:slab_memory_callback
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__kmem_cache_empty
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:init_kmem_cache_nodes
  - mm/slub.c:__kmem_cache_release
  - mm/slub.c:early_kmem_cache_node_alloc
  - mm/slub.c:__slab_free
  - mm/slub.c:___slab_alloc
  - mm/slub.c:slab_out_of_memory
  - mm/slub.c:unfreeze_partials
  - mm/slub.c:deactivate_slab
  - mm/slub.c:get_any_partial
  - mm/slub.c:discard_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:free_debug_processing
```
```
In drivers/md/dm-table.c (ffffffff8197d809)
Location: drivers/md/dm-table.c:97
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_find_target
  - drivers/md/dm-table.c:setup_indexes
  - drivers/md/dm-table.c:setup_indexes
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
In mm/slub.c (ffffffff812eb107)
Location: mm/slab.h:555
Inline: True
Inline callers:
  - mm/slub.c:get_slabinfo
  - mm/slub.c:validate_store
  - mm/slub.c:show_slab_objects
  - mm/slub.c:show_slab_objects
  - mm/slub.c:list_locations
  - mm/slub.c:__kmem_cache_create
  - mm/slub.c:bootstrap
  - mm/slub.c:slab_memory_callback
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__kmem_cache_empty
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:init_kmem_cache_nodes
  - mm/slub.c:early_kmem_cache_node_alloc
  - mm/slub.c:__slab_free
  - mm/slub.c:___slab_alloc
  - mm/slub.c:slab_out_of_memory
  - mm/slub.c:unfreeze_partials
  - mm/slub.c:deactivate_slab
  - mm/slub.c:get_any_partial
  - mm/slub.c:discard_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:free_debug_processing
```
```
In drivers/md/dm-table.c (ffffffff81981d89)
Location: drivers/md/dm-table.c:57
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_find_target
  - drivers/md/dm-table.c:setup_indexes
  - drivers/md/dm-table.c:setup_indexes
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
In mm/slub.c (ffffffff812f2bd7)
Location: mm/slab.h:567
Inline: True
Inline callers:
  - mm/slub.c:get_slabinfo
  - mm/slub.c:validate_store
  - mm/slub.c:show_slab_objects
  - mm/slub.c:show_slab_objects
  - mm/slub.c:list_locations
  - mm/slub.c:__kmem_cache_create
  - mm/slub.c:bootstrap
  - mm/slub.c:slab_memory_callback
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__kmem_cache_empty
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:early_kmem_cache_node_alloc
  - mm/slub.c:__slab_free
  - mm/slub.c:___slab_alloc
  - mm/slub.c:slab_out_of_memory
  - mm/slub.c:unfreeze_partials
  - mm/slub.c:deactivate_slab
  - mm/slub.c:get_any_partial
  - mm/slub.c:discard_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:free_debug_processing
```
```
In drivers/md/dm-table.c (ffffffff81966149)
Location: drivers/md/dm-table.c:57
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_find_target
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_complete
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
In mm/slub.c (ffffffff8133b907)
Location: mm/slab.h:563
Inline: True
Inline callers:
  - mm/slub.c:get_slabinfo
  - mm/slub.c:slab_debug_trace_open
  - mm/slub.c:show_slab_objects
  - mm/slub.c:show_slab_objects
  - mm/slub.c:validate_slab_cache
  - mm/slub.c:bootstrap
  - mm/slub.c:slab_memory_callback
  - mm/slub.c:__kmem_cache_do_shrink
  - mm/slub.c:__kmem_cache_do_shrink
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__kmem_cache_empty
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:__kmem_cache_release
  - mm/slub.c:early_kmem_cache_node_alloc
  - mm/slub.c:__slab_free
  - mm/slub.c:___slab_alloc
  - mm/slub.c:slab_out_of_memory
  - mm/slub.c:__unfreeze_partials
  - mm/slub.c:deactivate_slab
  - mm/slub.c:get_any_partial
  - mm/slub.c:discard_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:free_debug_processing
```
```
In drivers/md/dm-table.c (ffffffff81a0e334)
Location: drivers/md/dm-table.c:57
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_find_target
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_complete
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
In mm/slub.c (ffffffff813ae037)
Location: mm/slab.h:794
Inline: True
Inline callers:
  - mm/slub.c:get_slabinfo
  - mm/slub.c:slab_debug_trace_open
  - mm/slub.c:show_slab_objects
  - mm/slub.c:show_slab_objects
  - mm/slub.c:validate_slab_cache
  - mm/slub.c:bootstrap
  - mm/slub.c:slab_memory_callback
  - mm/slub.c:__kmem_cache_do_shrink
  - mm/slub.c:__kmem_cache_do_shrink
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__kmem_cache_empty
  - mm/slub.c:init_kmem_cache_nodes
  - mm/slub.c:init_kmem_cache_nodes
  - mm/slub.c:__kmem_cache_release
  - mm/slub.c:__slab_free
  - mm/slub.c:___slab_alloc
  - mm/slub.c:slab_out_of_memory
  - mm/slub.c:__unfreeze_partials
  - mm/slub.c:deactivate_slab
  - mm/slub.c:get_any_partial
  - mm/slub.c:discard_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:free_debug_processing
```
```
In drivers/md/dm-table.c (ffffffff81b76a86)
Location: drivers/md/dm-table.c:58
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_find_target
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_complete
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
In mm/slub.c (ffffffff8142e437)
Location: mm/slab.h:806
Inline: True
Inline callers:
  - mm/slub.c:get_slabinfo
  - mm/slub.c:slab_debug_trace_open
  - mm/slub.c:show_slab_objects
  - mm/slub.c:show_slab_objects
  - mm/slub.c:validate_slab_cache
  - mm/slub.c:bootstrap
  - mm/slub.c:slab_memory_callback
  - mm/slub.c:__kmem_cache_do_shrink
  - mm/slub.c:__kmem_cache_do_shrink
  - mm/slub.c:__kmem_cache_do_shrink
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__kmem_cache_empty
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:__kmem_cache_release
  - mm/slub.c:early_kmem_cache_node_alloc
  - mm/slub.c:early_kmem_cache_node_alloc
  - mm/slub.c:__slab_free
  - mm/slub.c:free_to_partial_list
  - mm/slub.c:free_to_partial_list
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:slab_out_of_memory
  - mm/slub.c:__unfreeze_partials
  - mm/slub.c:deactivate_slab
  - mm/slub.c:get_any_partial
  - mm/slub.c:discard_slab
```
```
In drivers/md/dm-table.c (ffffffff81d13e26)
Location: drivers/md/dm-table.c:59
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_find_target
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_complete
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
In mm/slub.c (ffffffff81463b77)
Location: mm/slab.h:806
Inline: True
Inline callers:
  - mm/slub.c:get_slabinfo
  - mm/slub.c:slab_debug_trace_open
  - mm/slub.c:show_slab_objects
  - mm/slub.c:show_slab_objects
  - mm/slub.c:validate_slab_cache
  - mm/slub.c:bootstrap
  - mm/slub.c:slab_memory_callback
  - mm/slub.c:__kmem_cache_do_shrink
  - mm/slub.c:__kmem_cache_do_shrink
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__kmem_cache_empty
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:__kmem_cache_release
  - mm/slub.c:early_kmem_cache_node_alloc
  - mm/slub.c:early_kmem_cache_node_alloc
  - mm/slub.c:__slab_free
  - mm/slub.c:free_to_partial_list
  - mm/slub.c:free_to_partial_list
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:slab_out_of_memory
  - mm/slub.c:__unfreeze_partials
  - mm/slub.c:deactivate_slab
  - mm/slub.c:get_any_partial
  - mm/slub.c:discard_slab
```
```
In drivers/md/dm-table.c (ffffffff81d7cf56)
Location: drivers/md/dm-table.c:60
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_find_target
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_complete
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
In mm/slub.c (ffffffff8145fdc7)
Location: mm/slub.c:436
Inline: True
Inline callers:
  - mm/slub.c:get_slabinfo
  - mm/slub.c:slab_debug_trace_open
  - mm/slub.c:show_slab_objects
  - mm/slub.c:show_slab_objects
  - mm/slub.c:validate_slab_cache
  - mm/slub.c:bootstrap
  - mm/slub.c:slab_memory_callback
  - mm/slub.c:__kmem_cache_do_shrink
  - mm/slub.c:__kmem_cache_do_shrink
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__kmem_cache_empty
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:__kmem_cache_release
  - mm/slub.c:early_kmem_cache_node_alloc
  - mm/slub.c:early_kmem_cache_node_alloc
  - mm/slub.c:__slab_free
  - mm/slub.c:free_to_partial_list
  - mm/slub.c:free_to_partial_list
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:slab_out_of_memory
  - mm/slub.c:__put_partials
  - mm/slub.c:deactivate_slab
  - mm/slub.c:get_any_partial
  - mm/slub.c:discard_slab
```
```
In drivers/md/dm-table.c (ffffffff81e34436)
Location: drivers/md/dm-table.c:60
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_find_target
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_complete
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffff80001034cc48)
Location: mm/slab.h:628
Inline: True
Inline callers:
  - mm/slub.c:get_slabinfo
  - mm/slub.c:validate_store
  - mm/slub.c:store_user_store
  - mm/slub.c:poison_store
  - mm/slub.c:red_zone_store
  - mm/slub.c:show_slab_objects
  - mm/slub.c:show_slab_objects
  - mm/slub.c:list_locations
  - mm/slub.c:bootstrap
  - mm/slub.c:slab_memory_callback
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__kmem_cache_empty
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:free_kmem_cache_nodes
  - mm/slub.c:__slab_free
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:slab_out_of_memory
  - mm/slub.c:discard_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:free_debug_processing
```
```
In drivers/md/dm-table.c (ffff800010b040f0)
Location: drivers/md/dm-table.c:97
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_find_target
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_complete
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (c0550560)
Location: mm/slab.h:628
Inline: True
Inline callers:
  - mm/slub.c:get_slabinfo
  - mm/slub.c:validate_store
  - mm/slub.c:store_user_store
  - mm/slub.c:poison_store
  - mm/slub.c:red_zone_store
  - mm/slub.c:show_slab_objects
  - mm/slub.c:show_slab_objects
  - mm/slub.c:list_locations
  - mm/slub.c:bootstrap
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__kmem_cache_empty
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:__kmem_cache_release
  - mm/slub.c:__slab_free
  - mm/slub.c:slab_out_of_memory
  - mm/slub.c:unfreeze_partials
  - mm/slub.c:deactivate_slab
  - mm/slub.c:discard_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:free_debug_processing
```
```
In drivers/md/dm-table.c (c0be312c)
Location: drivers/md/dm-table.c:97
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_find_target
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_complete
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (c00000000042ca80)
Location: mm/slab.h:628
Inline: True
Inline callers:
  - mm/slub.c:get_slabinfo
  - mm/slub.c:validate_store
  - mm/slub.c:store_user_store
  - mm/slub.c:poison_store
  - mm/slub.c:red_zone_store
  - mm/slub.c:show_slab_objects
  - mm/slub.c:show_slab_objects
  - mm/slub.c:list_locations
  - mm/slub.c:bootstrap
  - mm/slub.c:slab_memory_callback
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__kmem_cache_empty
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:free_kmem_cache_nodes
  - mm/slub.c:__slab_free
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:slab_out_of_memory
  - mm/slub.c:discard_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:free_debug_processing
```
```
In drivers/md/dm-table.c (c000000000bf39b4)
Location: drivers/md/dm-table.c:97
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_find_target
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_complete
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffe00023d9f0)
Location: mm/slab.h:628
Inline: True
Inline callers:
  - mm/slub.c:get_slabinfo
  - mm/slub.c:validate_store
  - mm/slub.c:store_user_store
  - mm/slub.c:poison_store
  - mm/slub.c:red_zone_store
  - mm/slub.c:list_locations
  - mm/slub.c:bootstrap
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__kmem_cache_empty
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:__kmem_cache_release
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
  - mm/slub.c:slab_out_of_memory
  - mm/slub.c:allocate_slab
  - mm/slub.c:free_debug_processing
```
```
In drivers/md/dm-table.c (ffffffe0006f3454)
Location: drivers/md/dm-table.c:97
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_find_target
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_complete
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812a32d2)
Location: mm/slab.h:628
Inline: True
Inline callers:
  - mm/slub.c:get_slabinfo
  - mm/slub.c:validate_store
  - mm/slub.c:store_user_store
  - mm/slub.c:poison_store
  - mm/slub.c:red_zone_store
  - mm/slub.c:show_slab_objects
  - mm/slub.c:show_slab_objects
  - mm/slub.c:list_locations
  - mm/slub.c:bootstrap
  - mm/slub.c:slab_memory_callback
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__kmem_cache_empty
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:free_kmem_cache_nodes
  - mm/slub.c:__slab_free
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:slab_out_of_memory
  - mm/slub.c:discard_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:free_debug_processing
```
```
In drivers/md/dm-table.c (ffffffff818533b4)
Location: drivers/md/dm-table.c:97
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_find_target
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_complete
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81294da2)
Location: mm/slab.h:628
Inline: True
Inline callers:
  - mm/slub.c:get_slabinfo
  - mm/slub.c:validate_store
  - mm/slub.c:store_user_store
  - mm/slub.c:poison_store
  - mm/slub.c:red_zone_store
  - mm/slub.c:show_slab_objects
  - mm/slub.c:show_slab_objects
  - mm/slub.c:list_locations
  - mm/slub.c:bootstrap
  - mm/slub.c:slab_memory_callback
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__kmem_cache_empty
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:free_kmem_cache_nodes
  - mm/slub.c:__slab_free
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:slab_out_of_memory
  - mm/slub.c:discard_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:free_debug_processing
```
```
In drivers/md/dm-table.c (ffffffff8181a9c4)
Location: drivers/md/dm-table.c:97
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_find_target
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_complete
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812a10e2)
Location: mm/slab.h:628
Inline: True
Inline callers:
  - mm/slub.c:get_slabinfo
  - mm/slub.c:validate_store
  - mm/slub.c:store_user_store
  - mm/slub.c:poison_store
  - mm/slub.c:red_zone_store
  - mm/slub.c:show_slab_objects
  - mm/slub.c:show_slab_objects
  - mm/slub.c:list_locations
  - mm/slub.c:bootstrap
  - mm/slub.c:slab_memory_callback
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__kmem_cache_empty
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:free_kmem_cache_nodes
  - mm/slub.c:__slab_free
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:slab_out_of_memory
  - mm/slub.c:discard_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:free_debug_processing
```
```
In drivers/md/dm-table.c (ffffffff818a29e4)
Location: drivers/md/dm-table.c:97
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_find_target
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_complete
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812b1292)
Location: mm/slab.h:628
Inline: True
Inline callers:
  - mm/slub.c:get_slabinfo
  - mm/slub.c:validate_store
  - mm/slub.c:store_user_store
  - mm/slub.c:poison_store
  - mm/slub.c:red_zone_store
  - mm/slub.c:show_slab_objects
  - mm/slub.c:show_slab_objects
  - mm/slub.c:list_locations
  - mm/slub.c:bootstrap
  - mm/slub.c:slab_memory_callback
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__kmem_cache_empty
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:free_kmem_cache_nodes
  - mm/slub.c:__slab_free
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:slab_out_of_memory
  - mm/slub.c:discard_slab
  - mm/slub.c:allocate_slab
  - mm/slub.c:free_debug_processing
```
```
In drivers/md/dm-table.c (ffffffff818bec24)
Location: drivers/md/dm-table.c:97
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_find_target
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_complete
```
</details>
</li>
</ul>

## Differences
