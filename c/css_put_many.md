# Function: <code>css_put_many</code>

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
In mm/memcontrol.c (ffffffff811fb4b3)
Location: include/linux/cgroup.h:366
Inline: True
Inline callers:
  - mm/memcontrol.c:cancel_charge
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:__memcg_kmem_uncharge
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
In mm/memcontrol.c (ffffffff812243d9)
Location: include/linux/cgroup.h:365
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_skmem
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:memcg_kmem_uncharge
  - mm/memcontrol.c:cancel_charge
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
In mm/memcontrol.c (ffffffff812369a9)
Location: include/linux/cgroup.h:365
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_skmem
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:memcg_kmem_uncharge
  - mm/memcontrol.c:cancel_charge
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
In mm/memcontrol.c (ffffffff8124244c)
Location: include/linux/cgroup.h:385
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_skmem
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:memcg_kmem_uncharge
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
In mm/memcontrol.c (ffffffff8126236a)
Location: include/linux/cgroup.h:397
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:memcg_kmem_uncharge
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
In mm/memcontrol.c (ffffffff81286447)
Location: include/linux/cgroup.h:397
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:memcg_kmem_uncharge
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
In mm/memcontrol.c (ffffffff8129b399)
Location: include/linux/cgroup.h:399
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:memcg_kmem_uncharge
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
In mm/slub.c (ffffffff81293ef6)
Location: include/linux/cgroup.h:406
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812b65e6)
Location: include/linux/cgroup.h:406
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__memcg_kmem_uncharge
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
In mm/slub.c (ffffffff812a3c66)
Location: include/linux/cgroup.h:408
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812c84b6)
Location: include/linux/cgroup.h:408
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__memcg_kmem_uncharge
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
In mm/slub.c (ffffffff812d97a5)
Location: include/linux/cgroup.h:414
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812fdd07)
Location: include/linux/cgroup.h:414
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__memcg_kmem_uncharge_page
  - mm/memcontrol.c:drain_stock
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
In mm/slub.c (ffff800010345928)
Location: include/linux/cgroup.h:408
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffff80001036b3cc)
Location: include/linux/cgroup.h:408
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__memcg_kmem_uncharge
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
In mm/slub.c (c05496f0)
Location: include/linux/cgroup.h:408
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (c055cac0)
Location: include/linux/cgroup.h:408
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__memcg_kmem_uncharge
  - mm/memcontrol.c:drain_stock
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
In mm/slub.c (c000000000421e94)
Location: include/linux/cgroup.h:408
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (c00000000045ace4)
Location: include/linux/cgroup.h:408
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__memcg_kmem_uncharge
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
In mm/slub.c (ffffffe00023813c)
Location: include/linux/cgroup.h:408
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffe000248af2)
Location: include/linux/cgroup.h:408
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__memcg_kmem_uncharge
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
In mm/slub.c (ffffffff8129c246)
Location: include/linux/cgroup.h:408
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812c0a96)
Location: include/linux/cgroup.h:408
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__memcg_kmem_uncharge
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
In mm/slub.c (ffffffff8128ddf7)
Location: include/linux/cgroup.h:408
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812b1b22)
Location: include/linux/cgroup.h:408
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__memcg_kmem_uncharge
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
In mm/slub.c (ffffffff8129a056)
Location: include/linux/cgroup.h:408
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812be8a6)
Location: include/linux/cgroup.h:408
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__memcg_kmem_uncharge
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
In mm/slub.c (ffffffff812a9eab)
Location: include/linux/cgroup.h:408
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812cf306)
Location: include/linux/cgroup.h:408
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:__memcg_kmem_uncharge
```
</details>
</li>
</ul>

## Differences
