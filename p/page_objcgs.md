# Function: <code>page_objcgs</code>

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
In mm/slub.c (ffffffff812e69b8)
Location: include/linux/memcontrol.h:448
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:__free_slab
  - mm/slub.c:memcg_slab_post_alloc_hook
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/memcontrol.c (ffffffff81308b6a)
Location: include/linux/memcontrol.h:448
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
In mm/slub.c (ffffffff812ee501)
Location: include/linux/memcontrol.h:552
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:memcg_slab_post_alloc_hook
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/memcontrol.c (ffffffff8130f2ad)
Location: include/linux/memcontrol.h:552
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
In mm/slub.c (ffffffff8133672f)
Location: include/linux/memcontrol.h:550
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:memcg_slab_post_alloc_hook
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/memcontrol.c (ffffffff8135a16f)
Location: include/linux/memcontrol.h:550
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_from_obj
```
</details>
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
