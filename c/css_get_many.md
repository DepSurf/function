# Function: <code>css_get_many</code>

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
In mm/memcontrol.c (ffffffff811fbc69)
Location: include/linux/cgroup.h:306
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
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
In mm/memcontrol.c (ffffffff812241aa)
Location: include/linux/cgroup.h:305
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
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
In mm/memcontrol.c (ffffffff812366aa)
Location: include/linux/cgroup.h:305
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
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
In mm/memcontrol.c (ffffffff8124215e)
Location: include/linux/cgroup.h:305
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
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
In mm/memcontrol.c (ffffffff81261f57)
Location: include/linux/cgroup.h:317
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
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
In mm/memcontrol.c (ffffffff81285f61)
Location: include/linux/cgroup.h:317
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
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
In mm/memcontrol.c (ffffffff8129aec1)
Location: include/linux/cgroup.h:319
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
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
In mm/slab_common.c (ffffffff812422e6)
Location: include/linux/cgroup.h:326
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
```
```
In mm/memcontrol.c (ffffffff812b615a)
Location: include/linux/cgroup.h:326
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
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
In mm/slab_common.c (ffffffff81250776)
Location: include/linux/cgroup.h:328
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
```
```
In mm/memcontrol.c (ffffffff812c804a)
Location: include/linux/cgroup.h:328
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
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
In mm/slab_common.c (ffffffff8127edd4)
Location: include/linux/cgroup.h:334
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
```
```
In mm/memcontrol.c (ffffffff812fd8fa)
Location: include/linux/cgroup.h:334
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
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
In mm/memcontrol.c (ffffffff8130936a)
Location: include/linux/cgroup.h:334
Inline: True
Inline callers:
  - mm/memcontrol.c:split_page_memcg
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
In mm/memcontrol.c (ffffffff8130f94f)
Location: include/linux/cgroup.h:334
Inline: True
Inline callers:
  - mm/memcontrol.c:split_page_memcg
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
In mm/memcontrol.c (ffffffff8135abdc)
Location: include/linux/cgroup.h:334
Inline: True
Inline callers:
  - mm/memcontrol.c:split_page_memcg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff813d4293)
Location: include/linux/cgroup.h:334
Inline: True
Inline callers:
  - mm/memcontrol.c:split_page_memcg
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81459c73)
Location: include/linux/cgroup_refcnt.h:23
Inline: True
Inline callers:
  - mm/memcontrol.c:split_page_memcg
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8148f903)
Location: include/linux/cgroup_refcnt.h:23
Inline: True
Inline callers:
  - mm/memcontrol.c:split_page_memcg
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff814bf140)
Location: include/linux/cgroup_refcnt.h:23
Inline: True
Inline callers:
  - mm/memcontrol.c:split_page_memcg
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
In mm/slab_common.c (ffff8000102e77dc)
Location: include/linux/cgroup.h:328
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
```
```
In mm/memcontrol.c (ffff80001036af78)
Location: include/linux/cgroup.h:328
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
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
In mm/slab_common.c (c050b908)
Location: include/linux/cgroup.h:328
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
```
```
In mm/memcontrol.c (c055c5c0)
Location: include/linux/cgroup.h:328
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
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
In mm/slab_common.c (c0000000003a95b8)
Location: include/linux/cgroup.h:328
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
```
```
In mm/memcontrol.c (c00000000045a608)
Location: include/linux/cgroup.h:328
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
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
In mm/slab_common.c (ffffffe0001fd364)
Location: include/linux/cgroup.h:328
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
```
```
In mm/memcontrol.c (ffffffe0002486b2)
Location: include/linux/cgroup.h:328
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
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
In mm/slab_common.c (ffffffff81248dc6)
Location: include/linux/cgroup.h:328
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
```
```
In mm/memcontrol.c (ffffffff812c062a)
Location: include/linux/cgroup.h:328
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
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
In mm/slab_common.c (ffffffff8123bd70)
Location: include/linux/cgroup.h:328
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
```
```
In mm/memcontrol.c (ffffffff812b16fa)
Location: include/linux/cgroup.h:328
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
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
In mm/slab_common.c (ffffffff81246b66)
Location: include/linux/cgroup.h:328
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
```
```
In mm/memcontrol.c (ffffffff812be43a)
Location: include/linux/cgroup.h:328
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
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
In mm/slab_common.c (ffffffff81256383)
Location: include/linux/cgroup.h:328
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
```
```
In mm/memcontrol.c (ffffffff812cee2a)
Location: include/linux/cgroup.h:328
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
```
</details>
</li>
</ul>

## Differences
