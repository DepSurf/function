# Function: <code>memcg_cache_id</code>

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
In mm/slab_common.c (ffffffff811b4799)
Location: include/linux/memcontrol.h:764
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_create_kmem_cache
  - mm/slab_common.c:memcg_deactivate_kmem_caches
```
```
In mm/list_lru.c (ffffffff811b8fd2)
Location: include/linux/memcontrol.h:764
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_add
  - mm/list_lru.c:list_lru_count_one
  - mm/list_lru.c:list_lru_walk_one
  - mm/list_lru.c:list_lru_del
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
In mm/slab_common.c (ffffffff811cd966)
Location: include/linux/memcontrol.h:818
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:memcg_create_kmem_cache
```
```
In mm/list_lru.c (ffffffff811d35b6)
Location: include/linux/memcontrol.h:818
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_walk_one
  - mm/list_lru.c:list_lru_count_one
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
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
In mm/slab_common.c (ffffffff811dda36)
Location: include/linux/memcontrol.h:855
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:memcg_create_kmem_cache
```
```
In mm/list_lru.c (ffffffff811e3466)
Location: include/linux/memcontrol.h:855
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_walk_one
  - mm/list_lru.c:list_lru_count_one
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
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
In mm/slab_common.c (ffffffff811e7816)
Location: include/linux/memcontrol.h:1119
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:memcg_create_kmem_cache
```
```
In mm/list_lru.c (ffffffff811ed8a6)
Location: include/linux/memcontrol.h:1119
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_walk_one
  - mm/list_lru.c:list_lru_count_one
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
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
In mm/slab_common.c (ffffffff811fda56)
Location: include/linux/memcontrol.h:1131
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:memcg_create_kmem_cache
```
```
In mm/list_lru.c (ffffffff81203d06)
Location: include/linux/memcontrol.h:1131
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_walk_one
  - mm/list_lru.c:list_lru_count_one
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
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
In mm/slab_common.c (ffffffff8121ed85)
Location: include/linux/memcontrol.h:1223
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:memcg_create_kmem_cache
```
```
In mm/list_lru.c (ffffffff81224895)
Location: include/linux/memcontrol.h:1223
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_walk_one
  - mm/list_lru.c:list_lru_count_one
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
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
In mm/slab_common.c (ffffffff81231d65)
Location: include/linux/memcontrol.h:1308
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:memcg_create_kmem_cache
```
```
In mm/list_lru.c (ffffffff81238083)
Location: include/linux/memcontrol.h:1308
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_walk_one_irq
  - mm/list_lru.c:list_lru_walk_one
  - mm/list_lru.c:list_lru_count_one
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
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
In mm/slab_common.c (ffffffff81242135)
Location: include/linux/memcontrol.h:1349
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:memcg_create_kmem_cache
```
```
In mm/list_lru.c (ffffffff81249663)
Location: include/linux/memcontrol.h:1349
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_walk_one_irq
  - mm/list_lru.c:list_lru_walk_one
  - mm/list_lru.c:list_lru_count_one
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
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
In mm/slab_common.c (ffffffff812505c5)
Location: include/linux/memcontrol.h:1435
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:memcg_create_kmem_cache
```
```
In mm/list_lru.c (ffffffff81257ab3)
Location: include/linux/memcontrol.h:1435
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_walk_one_irq
  - mm/list_lru.c:list_lru_walk_one
  - mm/list_lru.c:list_lru_count_one
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
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
In mm/slab_common.c (ffffffff8127ec25)
Location: include/linux/memcontrol.h:1408
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:memcg_create_kmem_cache
```
```
In mm/list_lru.c (ffffffff81286270)
Location: include/linux/memcontrol.h:1408
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_walk_one_irq
  - mm/list_lru.c:list_lru_count_one
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff81290520)
Location: include/linux/memcontrol.h:1650
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_walk_one_irq
  - mm/list_lru.c:list_lru_count_one
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff812959b0)
Location: include/linux/memcontrol.h:1680
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_walk_one_irq
  - mm/list_lru.c:list_lru_count_one
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff812d6030)
Location: include/linux/memcontrol.h:1689
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_walk_one_irq
  - mm/list_lru.c:list_lru_count_one
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
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
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffff8000102e762c)
Location: include/linux/memcontrol.h:1435
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:memcg_create_kmem_cache
```
```
In mm/list_lru.c (ffff8000102ef5fc)
Location: include/linux/memcontrol.h:1435
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_walk_one_irq
  - mm/list_lru.c:list_lru_walk_one
  - mm/list_lru.c:list_lru_count_one
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
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
In mm/slab_common.c (c050b748)
Location: include/linux/memcontrol.h:1435
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:memcg_create_kmem_cache
```
```
In mm/list_lru.c (c051306c)
Location: include/linux/memcontrol.h:1435
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_walk_one_irq
  - mm/list_lru.c:list_lru_walk_one
  - mm/list_lru.c:list_lru_count_one
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
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
In mm/slab_common.c (c0000000003a937c)
Location: include/linux/memcontrol.h:1435
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:memcg_create_kmem_cache
```
```
In mm/list_lru.c (c0000000003b3cc0)
Location: include/linux/memcontrol.h:1435
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_walk_one_irq
  - mm/list_lru.c:list_lru_walk_one
  - mm/list_lru.c:list_lru_count_one
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
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
In mm/slab_common.c (ffffffe0001fd1ce)
Location: include/linux/memcontrol.h:1435
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:memcg_create_kmem_cache
```
```
In mm/list_lru.c (ffffffe000203358)
Location: include/linux/memcontrol.h:1435
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_walk_one_irq
  - mm/list_lru.c:list_lru_walk_one
  - mm/list_lru.c:list_lru_count_one
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
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
In mm/slab_common.c (ffffffff81248c15)
Location: include/linux/memcontrol.h:1435
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:memcg_create_kmem_cache
```
```
In mm/list_lru.c (ffffffff81250103)
Location: include/linux/memcontrol.h:1435
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_walk_one_irq
  - mm/list_lru.c:list_lru_walk_one
  - mm/list_lru.c:list_lru_count_one
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
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
In mm/slab_common.c (ffffffff8123bbc5)
Location: include/linux/memcontrol.h:1435
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:memcg_create_kmem_cache
```
```
In mm/list_lru.c (ffffffff812430a3)
Location: include/linux/memcontrol.h:1435
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_walk_one_irq
  - mm/list_lru.c:list_lru_walk_one
  - mm/list_lru.c:list_lru_count_one
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
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
In mm/slab_common.c (ffffffff812469b5)
Location: include/linux/memcontrol.h:1435
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:memcg_create_kmem_cache
```
```
In mm/list_lru.c (ffffffff8124dea3)
Location: include/linux/memcontrol.h:1435
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_walk_one_irq
  - mm/list_lru.c:list_lru_walk_one
  - mm/list_lru.c:list_lru_count_one
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
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
In mm/slab_common.c (ffffffff812561c5)
Location: include/linux/memcontrol.h:1435
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:memcg_create_kmem_cache
```
```
In mm/list_lru.c (ffffffff8125d843)
Location: include/linux/memcontrol.h:1435
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_walk_one_irq
  - mm/list_lru.c:list_lru_walk_one
  - mm/list_lru.c:list_lru_count_one
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
```
</details>
</li>
</ul>

## Differences
