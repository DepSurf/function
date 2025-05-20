# Function: <code>kvzalloc_node</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-stats.c (ffffffff81759491)
Location: include/linux/mm.h:526
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_kvzalloc
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
In drivers/md/dm.c (ffffffff817c10a3)
Location: include/linux/mm.h:543
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_create
```
```
In drivers/md/dm-stats.c (ffffffff817cb6f1)
Location: include/linux/mm.h:543
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_kvzalloc
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
In drivers/md/dm.c (ffffffff81809726)
Location: include/linux/mm.h:578
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_create
```
```
In drivers/md/dm-stats.c (ffffffff818144c0)
Location: include/linux/mm.h:578
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_kvzalloc
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
In drivers/md/dm.c (ffffffff81835831)
Location: include/linux/mm.h:606
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_create
```
```
In drivers/md/dm-stats.c (ffffffff818404c0)
Location: include/linux/mm.h:606
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_kvzalloc
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
In drivers/md/dm.c (ffffffff81877df8)
Location: include/linux/mm.h:672
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
```
```
In drivers/md/dm-stats.c (ffffffff81883381)
Location: include/linux/mm.h:672
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_kvzalloc
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
In drivers/md/dm.c (ffffffff818a9c28)
Location: include/linux/mm.h:672
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
```
```
In drivers/md/dm-stats.c (ffffffff818b5221)
Location: include/linux/mm.h:672
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_kvzalloc
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
In mm/memcontrol.c (ffffffff812f5ae2)
Location: include/linux/mm.h:755
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_alloc_shrinker_maps
```
```
In drivers/md/dm.c (ffffffff8197a17d)
Location: include/linux/mm.h:755
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
```
```
In drivers/md/dm-stats.c (ffffffff81985fbb)
Location: include/linux/mm.h:755
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_kvzalloc
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
In mm/memcontrol.c (ffffffff813010c2)
Location: include/linux/mm.h:783
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_alloc_shrinker_maps
```
```
In drivers/md/dm.c (ffffffff8197e7bb)
Location: include/linux/mm.h:783
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
```
```
In drivers/md/dm-stats.c (ffffffff8198a01b)
Location: include/linux/mm.h:783
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_kvzalloc
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
In mm/vmscan.c (ffffffff81276523)
Location: include/linux/mm.h:806
Inline: True
Inline callers:
  - mm/vmscan.c:alloc_shrinker_info
```
```
In drivers/md/dm.c (ffffffff8196260b)
Location: include/linux/mm.h:806
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
```
```
In drivers/md/dm-stats.c (ffffffff8196e5eb)
Location: include/linux/mm.h:806
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_kvzalloc
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
In mm/vmscan.c (ffffffff812b3d43)
Location: include/linux/mm.h:807
Inline: True
Inline callers:
  - mm/vmscan.c:alloc_shrinker_info
```
```
In drivers/md/dm.c (ffffffff81a0984b)
Location: include/linux/mm.h:807
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
```
```
In drivers/md/dm-stats.c (ffffffff81a16e5b)
Location: include/linux/mm.h:807
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_kvzalloc
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
In mm/vmscan.c (ffffffff8130fc70)
Location: include/linux/slab.h:752
Inline: True
Inline callers:
  - mm/vmscan.c:alloc_shrinker_info
```
```
In lib/sbitmap.c (ffffffff8177271c)
Location: include/linux/slab.h:752
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_init_node
```
```
In drivers/md/dm.c (ffffffff81b7118c)
Location: include/linux/slab.h:752
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
```
```
In drivers/md/dm-stats.c (ffffffff81b7e8ed)
Location: include/linux/slab.h:752
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_kvzalloc
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
In mm/vmscan.c (ffffffff81383280)
Location: include/linux/slab.h:739
Inline: True
Inline callers:
  - mm/vmscan.c:alloc_shrinker_info
```
```
In lib/sbitmap.c (ffffffff818a3a7c)
Location: include/linux/slab.h:739
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_init_node
```
```
In drivers/md/dm.c (ffffffff81d0df9c)
Location: include/linux/slab.h:739
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
```
```
In drivers/md/dm-stats.c (ffffffff81d1ca4d)
Location: include/linux/slab.h:739
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_kvzalloc
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
In mm/vmscan.c (ffffffff813b4aa0)
Location: include/linux/slab.h:722
Inline: True
Inline callers:
  - mm/vmscan.c:alloc_shrinker_info
```
```
In lib/sbitmap.c (ffffffff818e5f5c)
Location: include/linux/slab.h:722
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_init_node
```
```
In drivers/md/dm.c (ffffffff81d7759c)
Location: include/linux/slab.h:722
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
```
```
In drivers/md/dm-stats.c (ffffffff81d85c31)
Location: include/linux/slab.h:722
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_kvzalloc
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
In mm/shrinker.c (ffffffff813e3bbd)
Location: include/linux/slab.h:730
Inline: True
Inline callers:
  - mm/shrinker.c:expand_one_shrinker_info
  - mm/shrinker.c:alloc_shrinker_info
```
```
In lib/sbitmap.c (ffffffff8192cf5c)
Location: include/linux/slab.h:730
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_init_node
```
```
In drivers/md/dm.c (ffffffff81e2e7cc)
Location: include/linux/slab.h:730
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
```
```
In drivers/md/dm-stats.c (ffffffff81e3d371)
Location: include/linux/slab.h:730
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_kvzalloc
```
</details>
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
In drivers/md/dm.c (ffff800010aff880)
Location: include/linux/mm.h:672
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
```
```
In drivers/md/dm-stats.c (ffff800010b0d064)
Location: include/linux/mm.h:672
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_kvzalloc
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
In drivers/md/dm.c (c0bde548)
Location: include/linux/mm.h:672
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
```
```
In drivers/md/dm-stats.c (c0bea638)
Location: include/linux/mm.h:672
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_kvzalloc
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
In drivers/md/dm.c (c000000000beb470)
Location: include/linux/mm.h:672
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
```
```
In drivers/md/dm-stats.c (c000000000bff878)
Location: include/linux/mm.h:672
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_kvzalloc
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
In drivers/md/dm.c (ffffffe0006f00d2)
Location: include/linux/mm.h:672
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
```
```
In drivers/md/dm-stats.c (ffffffe0006fa6ea)
Location: include/linux/mm.h:672
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_kvzalloc
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
In drivers/md/dm.c (ffffffff8184faa8)
Location: include/linux/mm.h:672
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
```
```
In drivers/md/dm-stats.c (ffffffff8185b0a1)
Location: include/linux/mm.h:672
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_kvzalloc
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
In drivers/md/dm.c (ffffffff818170b8)
Location: include/linux/mm.h:672
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
```
```
In drivers/md/dm-stats.c (ffffffff8182267b)
Location: include/linux/mm.h:672
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_kvzalloc
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
In drivers/md/dm.c (ffffffff8189f0d8)
Location: include/linux/mm.h:672
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
```
```
In drivers/md/dm-stats.c (ffffffff818aa6d1)
Location: include/linux/mm.h:672
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_kvzalloc
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
In drivers/md/dm.c (ffffffff818ba1f6)
Location: include/linux/mm.h:672
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
```
```
In drivers/md/dm-stats.c (ffffffff818c5ee8)
Location: include/linux/mm.h:672
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_kvzalloc
```
</details>
</li>
</ul>

## Differences
