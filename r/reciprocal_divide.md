# Function: <code>reciprocal_divide</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/flex_array.c (ffffffff813facec)
Location: include/linux/reciprocal_div.h:29
Inline: True
Inline callers:
  - lib/flex_array.c:flex_array_get
  - lib/flex_array.c:flex_array_clear
  - lib/flex_array.c:flex_array_put
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/flex_array.c (ffffffff81441f0c)
Location: include/linux/reciprocal_div.h:29
Inline: True
Inline callers:
  - lib/flex_array.c:flex_array_get
  - lib/flex_array.c:flex_array_clear
  - lib/flex_array.c:flex_array_put
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/flex_array.c (ffffffff8145f11c)
Location: include/linux/reciprocal_div.h:29
Inline: True
Inline callers:
  - lib/flex_array.c:flex_array_get
  - lib/flex_array.c:flex_array_clear
  - lib/flex_array.c:flex_array_put
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/flex_array.c (ffffffff8146445c)
Location: include/linux/reciprocal_div.h:29
Inline: True
Inline callers:
  - lib/flex_array.c:flex_array_get
  - lib/flex_array.c:flex_array_clear
  - lib/flex_array.c:flex_array_put
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/flex_array.c (ffffffff814903dc)
Location: include/linux/reciprocal_div.h:30
Inline: True
Inline callers:
  - lib/flex_array.c:flex_array_get
  - lib/flex_array.c:flex_array_clear
  - lib/flex_array.c:flex_array_put
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/flex_array.c (ffffffff814c51db)
Location: include/linux/reciprocal_div.h:30
Inline: True
Inline callers:
  - lib/flex_array.c:flex_array_get
  - lib/flex_array.c:flex_array_clear
  - lib/flex_array.c:flex_array_put
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/flex_array.c (ffffffff814d98da)
Location: include/linux/reciprocal_div.h:33
Inline: True
Inline callers:
  - lib/flex_array.c:flex_array_get
  - lib/flex_array.c:flex_array_clear
  - lib/flex_array.c:flex_array_put
```
</details>
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
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812e466e)
Location: include/linux/reciprocal_div.h:33
Inline: True
Inline callers:
  - mm/slub.c:process_slab
  - mm/slub.c:validate_slab
  - mm/slub.c:kfree
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:get_map
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/memcontrol.c (ffffffff81308b5c)
Location: include/linux/reciprocal_div.h:33
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_from_obj
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
In mm/slub.c (ffffffff812ebece)
Location: include/linux/reciprocal_div.h:33
Inline: True
Inline callers:
  - mm/slub.c:process_slab
  - mm/slub.c:validate_slab
  - mm/slub.c:kfree
  - mm/slub.c:kmem_obj_info
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:get_map
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/memcontrol.c (ffffffff8130f29c)
Location: include/linux/reciprocal_div.h:33
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_from_obj
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
In mm/slub.c (ffffffff81333f4f)
Location: include/linux/reciprocal_div.h:33
Inline: True
Inline callers:
  - mm/slub.c:process_slab
  - mm/slub.c:validate_slab
  - mm/slub.c:kmem_obj_info
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__fill_map
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/memcontrol.c (ffffffff8135a141)
Location: include/linux/reciprocal_div.h:33
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
In mm/slub.c (ffffffff813a53ed)
Location: include/linux/reciprocal_div.h:33
Inline: True
Inline callers:
  - mm/slub.c:process_slab
  - mm/slub.c:validate_slab
  - mm/slub.c:__kmem_obj_info
  - mm/slub.c:free_partial
  - mm/slub.c:__fill_map
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/memcontrol.c (ffffffff813d34fa)
Location: include/linux/reciprocal_div.h:33
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
In mm/slub.c (ffffffff81426589)
Location: include/linux/reciprocal_div.h:33
Inline: True
Inline callers:
  - mm/slub.c:process_slab
  - mm/slub.c:validate_slab
  - mm/slub.c:__kmem_obj_info
  - mm/slub.c:free_partial
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:__kmem_cache_free
  - mm/slub.c:__fill_map
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/memcontrol.c (ffffffff81458edd)
Location: include/linux/reciprocal_div.h:33
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
In mm/slub.c (ffffffff8145b5f9)
Location: include/linux/reciprocal_div.h:33
Inline: True
Inline callers:
  - mm/slub.c:process_slab
  - mm/slub.c:validate_slab
  - mm/slub.c:__kmem_obj_info
  - mm/slub.c:free_partial
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:__kmem_cache_free
  - mm/slub.c:__fill_map
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/memcontrol.c (ffffffff8148eb6d)
Location: include/linux/reciprocal_div.h:33
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
In mm/slub.c (ffffffff814567d9)
Location: include/linux/reciprocal_div.h:33
Inline: True
Inline callers:
  - mm/slub.c:process_slab
  - mm/slub.c:validate_slab
  - mm/slub.c:__kmem_obj_info
  - mm/slub.c:free_partial
  - mm/slub.c:__memcg_slab_free_hook
  - mm/slub.c:__memcg_slab_post_alloc_hook
  - mm/slub.c:__fill_map
```
```
In mm/memcontrol.c (ffffffff814be51d)
Location: include/linux/reciprocal_div.h:33
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
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/storvsc_drv.c (ffffffff817144b8)
Location: include/linux/reciprocal_div.h:33
Inline: True
Inline callers:
  - drivers/scsi/storvsc_drv.c:storvsc_queuecommand
  - drivers/scsi/storvsc_drv.c:storvsc_queuecommand
  - drivers/scsi/storvsc_drv.c:storvsc_queuecommand
```
</details>
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
