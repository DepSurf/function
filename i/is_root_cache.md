# Function: <code>is_root_cache</code>

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
In mm/slab_common.c (0)
Location: mm/slab.h:184
Inline: True
```
```
In mm/slub.c (0)
Location: mm/slab.h:184
Inline: True
```
```
In mm/memcontrol.c (0)
Location: mm/slab.h:184
Inline: True
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
In mm/slab_common.c (0)
Location: mm/slab.h:191
Inline: True
```
```
In mm/slub.c (0)
Location: mm/slab.h:191
Inline: True
```
```
In mm/memcontrol.c (0)
Location: mm/slab.h:191
Inline: True
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
In mm/slab_common.c (0)
Location: mm/slab.h:206
Inline: True
```
```
In mm/slub.c (0)
Location: mm/slab.h:206
Inline: True
```
```
In mm/memcontrol.c (0)
Location: mm/slab.h:206
Inline: True
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
In mm/slab_common.c (0)
Location: mm/slab.h:218
Inline: True
```
```
In mm/slub.c (0)
Location: mm/slab.h:218
Inline: True
```
```
In mm/memcontrol.c (0)
Location: mm/slab.h:218
Inline: True
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
In mm/slab_common.c (0)
Location: mm/slab.h:218
Inline: True
```
```
In mm/slub.c (0)
Location: mm/slab.h:218
Inline: True
```
```
In mm/memcontrol.c (0)
Location: mm/slab.h:218
Inline: True
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
In mm/slab_common.c (0)
Location: mm/slab.h:220
Inline: True
```
```
In mm/slub.c (0)
Location: mm/slab.h:220
Inline: True
```
```
In mm/memcontrol.c (0)
Location: mm/slab.h:220
Inline: True
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
In mm/slab_common.c (0)
Location: mm/slab.h:221
Inline: True
```
```
In mm/slub.c (0)
Location: mm/slab.h:221
Inline: True
```
```
In mm/memcontrol.c (0)
Location: mm/slab.h:221
Inline: True
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
In mm/slab_common.c (0)
Location: mm/slab.h:228
Inline: True
```
```
In mm/list_lru.c (0)
Location: mm/slab.h:228
Inline: True
```
```
In mm/slub.c (0)
Location: mm/slab.h:228
Inline: True
```
```
In mm/memcontrol.c (0)
Location: mm/slab.h:228
Inline: True
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
In mm/slab_common.c (0)
Location: mm/slab.h:292
Inline: True
```
```
In mm/list_lru.c (0)
Location: mm/slab.h:292
Inline: True
```
```
In mm/slub.c (0)
Location: mm/slab.h:292
Inline: True
```
```
In mm/memcontrol.c (0)
Location: mm/slab.h:292
Inline: True
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
In mm/slab_common.c (ffffffff8127d0e2)
Location: mm/slab.h:292
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_slabinfo_show
  - mm/slab_common.c:memcg_slabinfo_show
  - mm/slab_common.c:dump_unreclaimable_slab
  - mm/slab_common.c:dump_unreclaimable_slab
  - mm/slab_common.c:cache_show
  - mm/slab_common.c:memcg_accumulate_slabinfo
  - mm/slab_common.c:kmem_cache_shrink_all
  - mm/slab_common.c:shutdown_memcg_caches
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:shutdown_cache
  - mm/slab_common.c:find_mergeable
  - mm/slab_common.c:destroy_memcg_params
```
```
In mm/slub.c (ffffffff812de195)
Location: mm/slab.h:292
Inline: True
Inline callers:
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:slab_attr_store
  - mm/slub.c:__kmem_cache_create
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812fcb85)
Location: mm/slab.h:292
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_kmem_put_cache
  - mm/memcontrol.c:mem_cgroup_from_obj
  - mm/memcontrol.c:page_cgroup_ino
```
</details>
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
In mm/slab_common.c (0)
Location: mm/slab.h:292
Inline: True
```
```
In mm/list_lru.c (0)
Location: mm/slab.h:292
Inline: True
```
```
In mm/slub.c (0)
Location: mm/slab.h:292
Inline: True
```
```
In mm/memcontrol.c (0)
Location: mm/slab.h:292
Inline: True
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
In mm/slab_common.c (c050a010)
Location: mm/slab.h:292
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_slabinfo_show
  - mm/slab_common.c:memcg_slabinfo_show
  - mm/slab_common.c:dump_unreclaimable_slab
  - mm/slab_common.c:dump_unreclaimable_slab
  - mm/slab_common.c:cache_show
  - mm/slab_common.c:kmem_cache_shrink_all
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:shutdown_cache
  - mm/slab_common.c:destroy_memcg_params
```
```
In mm/list_lru.c (c0512fac)
Location: mm/slab.h:292
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
```
```
In mm/slub.c (c054eff0)
Location: mm/slab.h:292
Inline: True
Inline callers:
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:slab_attr_store
  - mm/slub.c:__kmem_cache_create
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (c055b2fc)
Location: mm/slab.h:292
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_kmem_put_cache
  - mm/memcontrol.c:mem_cgroup_from_obj
  - mm/memcontrol.c:__mod_lruvec_slab_state
  - mm/memcontrol.c:page_cgroup_ino
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
In mm/slab_common.c (0)
Location: mm/slab.h:292
Inline: True
```
```
In mm/list_lru.c (0)
Location: mm/slab.h:292
Inline: True
```
```
In mm/slub.c (0)
Location: mm/slab.h:292
Inline: True
```
```
In mm/memcontrol.c (0)
Location: mm/slab.h:292
Inline: True
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
In mm/slab_common.c (0)
Location: mm/slab.h:292
Inline: True
```
```
In mm/list_lru.c (0)
Location: mm/slab.h:292
Inline: True
```
```
In mm/slub.c (0)
Location: mm/slab.h:292
Inline: True
```
```
In mm/memcontrol.c (0)
Location: mm/slab.h:292
Inline: True
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
In mm/slab_common.c (0)
Location: mm/slab.h:292
Inline: True
```
```
In mm/list_lru.c (0)
Location: mm/slab.h:292
Inline: True
```
```
In mm/slub.c (0)
Location: mm/slab.h:292
Inline: True
```
```
In mm/memcontrol.c (0)
Location: mm/slab.h:292
Inline: True
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
In mm/slab_common.c (0)
Location: mm/slab.h:292
Inline: True
```
```
In mm/list_lru.c (0)
Location: mm/slab.h:292
Inline: True
```
```
In mm/slub.c (0)
Location: mm/slab.h:292
Inline: True
```
```
In mm/memcontrol.c (0)
Location: mm/slab.h:292
Inline: True
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
In mm/slab_common.c (0)
Location: mm/slab.h:292
Inline: True
```
```
In mm/list_lru.c (0)
Location: mm/slab.h:292
Inline: True
```
```
In mm/slub.c (0)
Location: mm/slab.h:292
Inline: True
```
```
In mm/memcontrol.c (0)
Location: mm/slab.h:292
Inline: True
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
In mm/slab_common.c (0)
Location: mm/slab.h:292
Inline: True
```
```
In mm/list_lru.c (0)
Location: mm/slab.h:292
Inline: True
```
```
In mm/slub.c (0)
Location: mm/slab.h:292
Inline: True
```
```
In mm/memcontrol.c (0)
Location: mm/slab.h:292
Inline: True
```
</details>
</li>
</ul>

## Differences
