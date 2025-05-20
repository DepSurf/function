# Function: <code>slab_objcgs</code>

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
In mm/slub.c (ffffffff813a80a5)
Location: mm/slab.h:442
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:memcg_slab_post_alloc_hook
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/memcontrol.c (ffffffff813d34a0)
Location: mm/slab.h:442
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
In mm/slub.c (ffffffff8142c06e)
Location: mm/slab.h:448
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:__kmem_cache_free
  - mm/slub.c:__free_slab
  - mm/slub.c:memcg_slab_post_alloc_hook
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/memcontrol.c (ffffffff81458e80)
Location: mm/slab.h:448
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
In mm/slub.c (ffffffff814615f2)
Location: mm/slab.h:440
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:__kmem_cache_free
  - mm/slub.c:__free_slab
  - mm/slub.c:memcg_slab_post_alloc_hook
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/memcontrol.c (ffffffff8148eb10)
Location: mm/slab.h:440
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
In mm/slub.c (ffffffff8145945d)
Location: mm/slab.h:552
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:__free_slab
  - mm/slub.c:__memcg_slab_post_alloc_hook
  - mm/slub.c:__memcg_slab_post_alloc_hook
```
```
In mm/memcontrol.c (ffffffff814be4c0)
Location: mm/slab.h:552
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
