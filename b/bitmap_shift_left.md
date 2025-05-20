# Function: <code>bitmap_shift_left</code>

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
In drivers/base/regmap/regcache-rbtree.c (ffffffff81568be4)
Location: include/linux/bitmap.h:314
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
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
In drivers/base/regmap/regcache-rbtree.c (ffffffff815bd78f)
Location: include/linux/bitmap.h:327
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
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
In drivers/base/regmap/regcache-rbtree.c (ffffffff815ecb9f)
Location: include/linux/bitmap.h:327
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
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
In drivers/base/regmap/regcache-rbtree.c (ffffffff81601322)
Location: include/linux/bitmap.h:348
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
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
In drivers/base/regmap/regcache-rbtree.c (ffffffff816696a2)
Location: include/linux/bitmap.h:370
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
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
In drivers/base/regmap/regcache-rbtree.c (ffffffff816a505e)
Location: include/linux/bitmap.h:401
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
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
In drivers/base/regmap/regcache-rbtree.c (ffffffff816c5ba1)
Location: include/linux/bitmap.h:402
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache-rbtree.c (ffffffff81700cf7)
Location: include/linux/bitmap.h:402
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache-rbtree.c (ffffffff81725047)
Location: include/linux/bitmap.h:426
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
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
In drivers/base/regmap/regcache-rbtree.c (ffffffff817e0fec)
Location: include/linux/bitmap.h:442
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_insert_to_block
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8189f674)
Location: include/linux/bitmap.h:442
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:update_user_bitmap
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
In drivers/base/regmap/regcache-rbtree.c (ffffffff817f5d3c)
Location: include/linux/bitmap.h:440
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_insert_to_block
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff818ae6d8)
Location: include/linux/bitmap.h:440
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:update_user_bitmap
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
In drivers/base/regmap/regcache-rbtree.c (ffffffff817da4eb)
Location: include/linux/bitmap.h:440
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_insert_to_block
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff818929e6)
Location: include/linux/bitmap.h:440
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:update_user_bitmap
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
In drivers/base/regmap/regcache-rbtree.c (ffffffff81865d32)
Location: include/linux/bitmap.h:446
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_insert_to_block
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8192388d)
Location: include/linux/bitmap.h:446
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:update_user_bitmap
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
In drivers/base/regmap/regcache-rbtree.c (ffffffff819ae203)
Location: include/linux/bitmap.h:466
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_insert_to_block
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81a79263)
Location: include/linux/bitmap.h:466
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:update_user_bitmap
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
In drivers/base/regmap/regcache-rbtree.c (ffffffff81b21f13)
Location: include/linux/bitmap.h:494
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_insert_to_block
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
In drivers/base/regmap/regcache-rbtree.c (ffffffff81b711da)
Location: include/linux/bitmap.h:492
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_insert_to_block
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
In drivers/base/regmap/regcache-rbtree.c (ffffffff81bc4eda)
Location: include/linux/bitmap.h:469
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_insert_to_block
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache-rbtree.c (ffff800010919d18)
Location: include/linux/bitmap.h:426
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache-rbtree.c (c09ff958)
Location: include/linux/bitmap.h:426
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
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
In arch/powerpc/kernel/rtas.c (c00000000003ce48)
Location: include/linux/bitmap.h:426
Inline: True
Inline callers:
  - arch/powerpc/kernel/rtas.c:rtas_cpu_state_change_mask
```
```
In arch/powerpc/platforms/powernv/idle.c (c0000000000c7904)
Location: include/linux/bitmap.h:426
Inline: True
```
```
In arch/powerpc/platforms/powernv/opal-imc.c (c0000000000dfd64)
Location: include/linux/bitmap.h:426
Inline: True
```
```
In arch/powerpc/platforms/pseries/hotplug-cpu.c (c0000000000fa05c)
Location: include/linux/bitmap.h:426
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/hotplug-cpu.c:pseries_add_processor
```
```
In drivers/base/regmap/regcache-rbtree.c (c0000000009bdc68)
Location: include/linux/bitmap.h:426
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache-rbtree.c (ffffffe000599f22)
Location: include/linux/bitmap.h:426
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache-rbtree.c (ffffffff816eb377)
Location: include/linux/bitmap.h:426
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache-rbtree.c (ffffffff816c59b7)
Location: include/linux/bitmap.h:426
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache-rbtree.c (ffffffff81718507)
Location: include/linux/bitmap.h:426
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache-rbtree.c (ffffffff81733867)
Location: include/linux/bitmap.h:426
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
```
</details>
</li>
</ul>

## Differences
