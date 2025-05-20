# Function: <code>radix_tree_deref_retry</code>

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
In mm/filemap.c (0)
Location: include/linux/radix-tree.h:222
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/radix-tree.h:222
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
In mm/filemap.c (0)
Location: include/linux/radix-tree.h:225
Inline: True
```
```
In mm/shmem.c (ffffffff811c3b75)
Location: include/linux/radix-tree.h:225
Inline: True
Inline callers:
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/khugepaged.c (ffffffff8121c6c3)
Location: include/linux/radix-tree.h:225
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
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
In mm/filemap.c (0)
Location: include/linux/radix-tree.h:259
Inline: True
```
```
In mm/shmem.c (ffffffff811d3c24)
Location: include/linux/radix-tree.h:259
Inline: True
Inline callers:
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/khugepaged.c (ffffffff8122e0e7)
Location: include/linux/radix-tree.h:259
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
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
In mm/filemap.c (0)
Location: include/linux/radix-tree.h:263
Inline: True
```
```
In mm/shmem.c (ffffffff811dc389)
Location: include/linux/radix-tree.h:263
Inline: True
Inline callers:
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/khugepaged.c (ffffffff8123a3c1)
Location: include/linux/radix-tree.h:263
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
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
In mm/filemap.c (0)
Location: include/linux/radix-tree.h:262
Inline: True
```
```
In mm/shmem.c (ffffffff811f2203)
Location: include/linux/radix-tree.h:262
Inline: True
Inline callers:
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/khugepaged.c (ffffffff812590e1)
Location: include/linux/radix-tree.h:262
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:262
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
In mm/filemap.c (0)
Location: include/linux/radix-tree.h:266
Inline: True
```
```
In mm/shmem.c (ffffffff81213b40)
Location: include/linux/radix-tree.h:266
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/khugepaged.c (ffffffff8127d451)
Location: include/linux/radix-tree.h:266
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
```
In mm/memfd.c (0)
Location: include/linux/radix-tree.h:266
Inline: True
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:266
Inline: True
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
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:205
Inline: True
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
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:192
Inline: True
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
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:192
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:192
Inline: True
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
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:193
Inline: True
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
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:193
Inline: True
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
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:193
Inline: True
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
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:195
Inline: True
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
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:195
Inline: True
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
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:204
Inline: True
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
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:204
Inline: True
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
In drivers/hwspinlock/hwspinlock_core.c (ffff800010b7e148)
Location: include/linux/radix-tree.h:192
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:of_hwspin_lock_get_id
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
In drivers/hwspinlock/hwspinlock_core.c (c0c61e24)
Location: include/linux/radix-tree.h:192
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:of_hwspin_lock_get_id
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (c000000000c5abec)
Location: include/linux/radix-tree.h:192
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:of_hwspin_lock_get_id
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
In drivers/hwspinlock/hwspinlock_core.c (ffffffe00072c6ce)
Location: include/linux/radix-tree.h:192
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:of_hwspin_lock_get_id
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
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:192
Inline: True
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
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:192
Inline: True
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
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:192
Inline: True
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
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:192
Inline: True
```
</details>
</li>
</ul>

## Differences
