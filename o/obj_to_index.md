# Function: <code>obj_to_index</code>

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
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812e69d2)
Location: include/linux/slub_def.h:185
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/memcontrol.c (ffffffff81308b3c)
Location: include/linux/slub_def.h:185
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
In mm/slub.c (ffffffff812ee1a5)
Location: include/linux/slub_def.h:186
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:kmem_obj_info
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/memcontrol.c (ffffffff8130f27f)
Location: include/linux/slub_def.h:186
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
In mm/slub.c (ffffffff8133b398)
Location: include/linux/slub_def.h:192
Inline: True
Inline callers:
  - mm/slub.c:kmem_obj_info
  - mm/slub.c:kmem_obj_info
  - mm/slub.c:memcg_slab_post_alloc_hook
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/memcontrol.c (ffffffff8135a0fd)
Location: include/linux/slub_def.h:192
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
In mm/slub.c (ffffffff813adad9)
Location: include/linux/slub_def.h:179
Inline: True
Inline callers:
  - mm/slub.c:__kmem_obj_info
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/memcontrol.c (ffffffff813d34cf)
Location: include/linux/slub_def.h:179
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
In mm/slub.c (ffffffff8142de59)
Location: include/linux/slub_def.h:185
Inline: True
Inline callers:
  - mm/slub.c:__kmem_obj_info
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:__kmem_cache_free
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/memcontrol.c (ffffffff81458eb2)
Location: include/linux/slub_def.h:185
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
In mm/slub.c (ffffffff81463586)
Location: include/linux/slub_def.h:191
Inline: True
Inline callers:
  - mm/slub.c:__kmem_obj_info
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:__kmem_cache_free
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/memcontrol.c (ffffffff8148eb42)
Location: include/linux/slub_def.h:191
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
In mm/slub.c (ffffffff8145f7d6)
Location: mm/slab.h:341
Inline: True
Inline callers:
  - mm/slub.c:__kmem_obj_info
  - mm/slub.c:__memcg_slab_free_hook
  - mm/slub.c:__memcg_slab_post_alloc_hook
```
```
In mm/memcontrol.c (ffffffff814be4f2)
Location: mm/slab.h:341
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
